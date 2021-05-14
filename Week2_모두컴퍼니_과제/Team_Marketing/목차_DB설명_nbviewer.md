목차
Cohort
1. 사용일자(DATE) 칼럼으로 단위 기간 만들기
2. 유저의 첫번째 사용일 토대로 유저별 코호트 그룹 설정하기
3. 코호트 그룹과 주문기간으로 데이터 집계하기
4. Insight 도출 / Action Plan 제시 (pdf)
RFM 
1.Recency Generated
2. Frequency Generated
3. Monetary Generated
    - 모두의 주차장 가격표 전처리
    - A,B,C,D를 구분을 나눈 논리적인 기준 EDA
    - 논리적으로 나눈 A,B,C,D GOODS_TYPE에 가격 매칭
    - Monetary 컬럼 생성
4. RFM 테이블 생성
    - RFM 점수별 count 오름차순 시각화 

분석 Insight / Action Plan 
1. PDF 참조 

DB 설명
1. 실전db_after_2013.csv: 2013년 이후만 포함한 db
2. 강북_강남.xlsx: 처음 가격표 수기 작업시 excel로 작업한 db
3. 지하철노선위경도정보3.xlsx 지하철목록db 
    - 출처:https://blog.naver.com/yug311861/221970210014 (전처리됨 credit by 박성준)
4. 가격데이터.csv 모두의 주차장 가격표 전처리 db
5. price_column_added: A,B,C,D로 분류된 value에 값을 부여한 db

nbviewer 주소: 

Warning
1. nbviewer에러 코드: nbviewer 서버에 Remote HTTP 404에러코드 발생. 