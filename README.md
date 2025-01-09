## 데이터

https://rees46.com/en/datasets

## AARRR을 통한 데이터 분석
1. Acquisition(고객 유치)
    - MAU, DAU

2. Activation(활성화)
    - DT(Duration Time, 체류시간)
    - 전환율 (퍼널)

3. Retention(리텐션)
    - retention (classic, range, rolling)
        - 월별
        - 주별
        - 카테고리별
    - engagement = DAU / MAU  (서비스 리텐션 수준을 볼 수 있는 간단한 지표)
    - cohort

4. Revenue(수익화)
    - LTV(Life Time Value, 고객 생애 가치)
    - PU(Paying User, 결제 유저)
    - ARPU(Average Revenue Per User, 유저 당 평균 수익)
    - ARPDAU 데일리
    - ARPWAU 위클리
    - ARPPU (Average Revenue Per Paying User, 결제 유저 당 평균 수익)
    - 

5. Referral(추천)
    - 불가

## 데이터 전처리
1. user_session null 값
    - 총 226건
    - 연속성 없는 데이터들
        - 같은 달에 같은 user_id의 user_session null 값 있는 지 확인 하였지만 존재 하지 않음
    - 제거하기로 결정


사용자 집단???
사용자 RFM(고객 세분화 -> 등급화) -> 리텐션
 - Recency
 - Frequency
 - Monetary
RFM -> 빈도수랑 사용금액 