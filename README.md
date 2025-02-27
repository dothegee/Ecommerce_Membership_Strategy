## 데이터

https://rees46.com/en/datasets

## 목적
고객 유입 분석을 토대로 구매 전환율을 높이는 것이 목표. 
전환율 상승을 위한 액션 플랜을 제시.

    장바구니에 담았지만 구매하지 않은 고객에 대한 리타겟팅 전략 필요

## AARRR을 통한 데이터 분석

1. Acquisition(고객 유치)
    데이터 상 고객의 유입경로를 알 수 없음

2. Activation(활성화)
    
    FUNNEL
        구매 전환율 확인
        (https://www.littledata.io/ecommerce-conversion-rate)


    장바구니에 제품을 추가했지만 결제하지 않은 비율
        구매를 하진 않았지만, 구매 전환 가능성 있는 고객을 확인하기 위해
        ==> 구매전환율과 연관 있음


        <장바구니구매전환율>
            동일한 user_id가 장바구니에 담은 상품과 동일 상품을 실제로 구매한 사용자 수 / 장바구니 담은 user 수
            =
            장바구니에 상품을 담은 사용자 중 실제로 구매한 사용자의 비율
            = 45%


            <추후 도전>
            동일한 user_id가 장바구니에 담은 상품의 category_id와 동일한 카테고리의 상품을 실제로 구매한 사용자 수

            퍼널 분석에 따른 장바구니구매전환율 = 35.831%

            구매로 전환한 사용자가 장바구니에 여러 개의 상품을 담았을 가능성이 높음을 유추 가능.
    <요약>
        장바구니 구매 전환율 분석 및 인사이트
            1. 장바구니 추가 후 결제하지 않은 비율
            장바구니에 상품을 추가했지만 결제하지 않은 고객의 비율은 구매 전환율과 밀접한 연관이 있습니다.
            이를 통해 구매 가능성이 높은 고객을 식별하고, 전환을 유도하는 전략을 수립할 수 있습니다.
            2. 장바구니 구매 전환율 (Purchase Conversion Rate)
            정의:
            동일한 user_id가 장바구니에 담은 상품과 동일한 상품을 실제로 구매한 사용자 수 ÷ 장바구니에 상품을 담은 사용자 수
            결과:
            45%
            → 장바구니에 상품을 담은 사용자 중 45%가 실제 구매로 이어짐.
            3. 퍼널 분석 기반 장바구니 구매 전환율
            퍼널 분석(Funnel Analysis)을 적용한 장바구니 구매 전환율:
            35.831%
            → 단계별 사용자 흐름을 고려했을 때, 실제 구매로 전환된 비율이 다소 낮아짐.
            4. 주요 인사이트
            구매로 전환한 사용자는 장바구니에 여러 개의 상품을 담았을 가능성이 높음.
            전환율을 높이기 위해, 장바구니에서 자주 담기지만 구매되지 않는 상품에 대한 인센티브(할인, 추천 등)를 고려할 필요가 있음.
            특정 카테고리에서의 전환율을 분석하여, 구매 유도 전략을 세분화하는 방향도 유효할 것으로 예상됨.

    카테고리별/요일별 전환율
        특정 EVENT에 따른 구매 전환율이 영향이 있는지

    DT => 체류시간이 얼마나 긴지 짧은지 
        체류시간이 의미하는 바는 무엇인가??
            DT가 높을수록 유저가 서비스와의 상호작용이 많다고 기대
        이커머스 평균 5~15분 높은 경우 20분이상 존재(출처 : http://m.apparelnews.co.kr/news/news_view/?idx=187387)


    DT가 높음에도 불구하고 구매전환이 되지 않은 유저들
        충분한 상호작용을 했음에도 불구하고 현재 서비스에 대해서 불만족을 느껴???
        그 수치가 얼마나 되는지



3. Retention(리텐션)
# 📊 주간 리텐션 vs. 월간 리텐션: 어떤 걸 선택해야 할까?

## ✅ 1️⃣ 리텐션을 선택할 때 고려해야 할 3가지 핵심 요소

### 📌 1) 고객의 구매 주기 & 소비 패턴 분석
리텐션 지표를 선택하기 전에, **고객이 어떤 패턴으로 구매하는지 분석해야 한다.**  
- **주간 리텐션(Weekly Retention)** → **고객이 매주 방문하는 서비스인지?**  
- **월간 리텐션(Monthly Retention)** → **고객이 한 달 단위로 방문하는 서비스인지?**  

#### 🔍 판단 기준
✔ **고객이 주 단위로 자주 구매하는가?**  
✔ **고객이 한 달에 몇 번 방문하는가?**  

#### 📌 적용 예시
✅ **주간 리텐션을 봐야 하는 경우 (짧은 구매 주기 / 자주 사용하는 서비스)**  
- **식료품 & 배달 앱** (배달의민족, 쿠팡이츠, 마켓컬리) → 주 1~2회 이상 사용  
- **패션 & 생활용품** (H&M, 유니클로, 올리브영) → 트렌드 변화가 빨라 주기적인 방문 유도  
- **정기 배송 서비스** (정수기 필터 교체, 반려동물 사료, 화장품 구독)  

✅ **월간 리텐션을 봐야 하는 경우 (긴 구매 주기 / 특정 이벤트 발생 시 사용)**  
- **전자제품 & 가구** (LG전자, IKEA) → 구매 주기가 길고, 고객이 비교 후 구매  
- **고가 제품 (명품, 자동차 등)** → 월 단위 관심도가 중요  
- **여행 & 항공권 예약 서비스** → 고객이 자주 방문하지 않지만, 특정 시점에 집중적으로 사용  

---

### 📌 2) 비즈니스 모델에 따라 다르게 접근해야 함  

#### 📌 비즈니스 모델에 따른 리텐션 선택 기준

| 비즈니스 모델 | 주간 리텐션 (Weekly Retention) | 월간 리텐션 (Monthly Retention) |
|--------------|----------------|----------------|
| **구독 기반 서비스** | ✅ 정기적으로 방문 & 소비하는 서비스 (넷플릭스, 마켓컬리 정기배송) | 🚫 필요 없음 |
| **이커머스 & 마켓플레이스** | ✅ 반복 구매가 많다면 (쿠팡, 올리브영, 무신사) | ✅ 가전제품, 명품, 가구 등 |
| **단기 트랜잭션 기반 서비스** | 🚫 필요 없음 | ✅ 한 달에 한두 번 방문하는 경우 (항공권, 호텔 예약) |

#### 🔍 판단 기준
✔ **자주 방문 & 소비하는 서비스** → **주간 리텐션**  
✔ **구매 주기가 길고, 한 번 방문하면 오래 체류하는 서비스** → **월간 리텐션**  

---

### 📌 3) 리텐션을 통해 달성하려는 목표 설정  

리텐션을 분석하는 이유는 결국 **고객 유지(Customer Retention)를 높이고, 충성 고객을 늘리는 것**이다.  
💡 **어떤 목표를 달성하고 싶은지에 따라 적절한 리텐션 지표를 선택해야 한다.**  

#### 🎯 (A) 사용자 참여율(Engagement) 증대 → **주간 리텐션 분석 필요**  
- "고객이 매주 방문하도록 만들고 싶다."  
- **목표:** 앱 방문 빈도 증가 & 활성 사용자 수(Active Users) 상승  
- **예시:**  
  - 배달의민족 → 고객이 매주 여러 번 주문하도록 만들고 싶음  
  - 올리브영 → 새로운 프로모션을 통해 자주 방문하도록 유도  

#### 🎯 (B) 고객 충성도 유지 & 재구매율 상승 → **월간 리텐션 분석 필요**  
- "고객이 1개월 안에 다시 돌아오게 만들고 싶다."  
- **목표:** 고객이 한 번 이탈하면 다시 돌아오지 않는 것을 방지  
- **예시:**  
  - 넷플릭스 → 한 달 내 시청을 지속적으로 유지하는 것이 중요  
  - 이케아 → 한 달에 한 번 이상 방문하는 고객을 유지하는 것이 중요  

---

## 🚀 2️⃣ 최종 결론: 주간 리텐션 vs. 월간 리텐션 선택 가이드  

### 📌 최종 선택 기준

| 비교 요소 | 주간 리텐션 (Weekly Retention) | 월간 리텐션 (Monthly Retention) |
|-----------|----------------|----------------|
| 고객 구매 주기 | **짧음 (식품, 생활용품, 배달)** | **김 (가전, 가구, 명품, 항공권)** |
| 비즈니스 모델 | **정기적 방문이 중요한 경우 (구독, 반복 구매)** | **장기적 고객 충성도 & 재구매 유도** |
| 목표 | **사용자 참여(Engagement) 증대** | **충성 고객 유지 & 재구매율 상승** |
| 적합한 예시 | **배달 앱, 정기 배송, 패션, 마트** | **가전, 가구, 명품, 자동차, 여행 서비스** |

### ✅ 즉, 어떻게 결정해야 할까?
✔ **사용자가 매주 재방문하는 것이 중요하다면 → 주간 리텐션**  
✔ **구매 주기가 길고, 한 달 내 재방문율이 중요한 경우 → 월간 리텐션**  

### 🚀 최적의 접근법
- **주 단위로 지속적인 방문을 유도하는 서비스라면 → 주간 리텐션(Weekly Retention) 추적**  
- **고객이 한 달 내 다시 방문 & 구매하는 게 중요하다면 → 월간 리텐션(Monthly Retention) 추적**  
- **이커머스에서 상품군이 다양하다면, 카테고리별로 주간 vs. 월간 리텐션을 분리 분석하는 것이 가장 효과적!**  

---

## 💡 추가 추천: 주간 & 월간 리텐션을 동시에 분석하는 방법  

### 📊 1️⃣ 핵심 고객 세그먼트 구분
- **주간 리텐션 높은 고객 (High Weekly Retention)**  
  - 충성 고객, VIP, 반복 구매 가능성이 높은 유저  
  - 이들을 위한 **로열티 프로그램, 추가 혜택 제공**  

- **월간 리텐션 높은 고객 (High Monthly Retention)**  
  - 재방문하지만 빈도가 낮은 고객  
  - **리마케팅을 강화하여 주간 리텐션으로 전환할 기회 존재**  

### 📊 2️⃣ 카테고리별 구매 주기 분석
- 고객이 **어떤 상품을 구매하는지에 따라 리텐션 주기가 달라질 수 있음**  
  - 화장품 & 생활용품 → **주간 리텐션이 중요**  
  - 가전 & 명품 → **월간 리텐션이 더 유효**  

📌 **실행 방법:**  
✔ 특정 카테고리는 주간 리텐션, 특정 카테고리는 월간 리텐션을 따로 분석  
✔ 각 카테고리에 맞춘 리텐션 개선 전략 적용  

---

# 🚀 최종 결론
**비즈니스 목표, 고객의 구매 주기, 그리고 서비스 특성을 고려하여 주간 리텐션과 월간 리텐션 중 하나를 선택해야 한다.**  
✅ **고객이 자주 방문 & 반복 구매해야 하는 서비스라면 주간 리텐션을 추적**  
✅ **고객의 재방문 주기가 길고, 재구매율을 높이는 것이 목표라면 월간 리텐션을 추적**  
✅ **이커머스에서는 상품군별로 주간 & 월간 리텐션을 병행하여 분석하는 것이 최적의 방법!** 🚀


    리텐션 주기 : 7일 (이유 : EVENT 단위가 주별 생성되기 때문에 분석하기 용이)

    재구매율

    구매 주기
        카테고리 별
    
    제품 카테고리별 리텐션 

    7일주기 리텐션

    - 사용자 RFM(고객 세분화 -> 등급화) -> 리텐션 ==> 7일 주기
        - Recency
        - Frequency
        - Monetary

        RFM -> 빈도수랑 사용금액 

        - 그룹화 기준

            VIP
            333

            충성고객
            332, 323, 322

            잠재적 고가치 고객 ==> 프로모션 많이 해서 충성고객으로 만들어야 되는 그룹인 고객(돈 많이 쓰게 해야됨)
            331, 321

            신규 고객
            311, 312, 313

            이탈 유려
            221,231, 222, 223, 232, 233

            일시적 고객(찍먹 고객)
            111, 112, 113, 211, 212, 213

            이탈 고객
            133, 132, 121, 131, 122, 123

            
# 📊 RFM 기반 고객 세분화 및 맞춤 액션 플랜 (이커머스 특화)

## 🎯 목표
✅ **VIP 고객 유지** → 고액 소비 지속 유도  
✅ **충성 고객 육성** → VIP로 전환 유도  
✅ **이탈 방지** → 재구매 가능성 증가  
✅ **잠재적 고가치 고객 락인** → 장기적으로 충성 고객화  
✅ **신규 고객 온보딩** → 첫 구매 후 지속적인 거래 유도  
✅ **일시적 고객 재유입** → 브랜드 경험 강화  
✅ **이탈 고객 재활성화** → 이탈 고객 리타겟팅  

---

## 🏆 1️⃣ VIP 고객 (333)
**💎 특징:**  
- 이커머스에서 **가장 중요한 고객군**  
- **고액 소비 및 높은 브랜드 충성도 유지**  

**🔥 액션 플랜:**  
- 🎁 **VIP 전용 프로모션** (한정 할인, 독점 제품)  
- 🎟️ **대형 세일 우선 입장권 제공** (블랙프라이데이, 시즌 세일)  
- 🚀 **개인화된 VIP 고객 케어** (전담 고객 서비스)  
- 🎫 **프리미엄 멤버십 도입** (무료 배송, 특별 할인)  
- ⭐️ **SNS 후기 이벤트 참여 유도**  

---

## 💙 2️⃣ 충성 고객 (332, 323, 322)
**💎 특징:**  
- VIP로 **승급 가능성이 높은 고객군**  
- **자주 구매**하지만 평균 주문 금액이 낮음  

**🔥 액션 플랜:**  
- 💰 **VIP 전환 인센티브 제공** (누적 구매 기준 VIP 승급)  
- 🎯 **정기 구독 서비스 유도** (서브스크립션 모델 도입)  
- 🛍️ **3회 구매 시 추가 할인 프로모션 진행**  
- 🔥 **구매 이력 기반 개인화 추천**  

---

## 🚀 3️⃣ 잠재적 고가치 고객 (331, 321)
**💎 특징:**  
- **1회 구매 금액이 크지만, 구매 빈도가 낮음**  
- 적극적인 프로모션을 통해 **충성 고객으로 전환 가능**  

**🔥 액션 플랜:**  
- 💰 **재구매 유도를 위한 리워드 제공** (두 번째 구매 시 추가 할인)  
- 🎟️ **VIP 무료 체험 기회 제공**  
- 🔄 **다양한 상품 추천 마케팅 진행**  

---

## 🌱 4️⃣ 신규 고객 (311, 312, 313)
**💎 특징:**  
- 첫 구매를 한 고객 → **이탈 방지가 중요**  

**🔥 액션 플랜:**  
- 🎁 **첫 구매 감사 쿠폰 지급**  
- 📩 **구매 후 7일 내 개인화 추천 상품 메일 발송**  
- 🎯 **30일 내 재구매 시 10% 추가 할인 캠페인**  
- ⭐️ **리뷰 작성 시 추가 적립금 제공**  

---

## ⚠️ 5️⃣ 이탈 위험 고객 (221, 231, 222, 223, 232, 233)
**💎 특징:**  
- **과거 구매했지만 최근 활동 없음**  
- 이탈을 막고 **재구매를 유도해야 함**  

**🔥 액션 플랜:**  
- 📩 **맞춤형 리타겟팅 캠페인 (쿠폰 제공)**  
- 🛒 **장바구니 이탈 고객 대상 리마인드 광고**  
- 🎯 **"마지막 구매 이후 X개월이 지났습니다. 특별 혜택을 드립니다!"**  
- 🔄 **이전 구매 제품과 연관된 제품 추천**  

---

## ⏳ 6️⃣ 일시적 고객 (찍먹 고객: 111, 112, 113, 211, 212, 213)
**💎 특징:**  
- 단 1~2회 구매하고 재구매 의향이 낮음  
- 브랜드 락인을 실패한 고객  

**🔥 액션 플랜:**  
- 🛍️ **"첫 구매 고객을 위한 특별 쿠폰 지급"**  
- 🎯 **샘플 키트 제공 (다른 제품도 사용해볼 기회 제공)**  
- 📩 **"마지막 구매 이후 방문이 없습니다. 재구매 시 15% 할인!"**  

---

## 🚨 7️⃣ 이탈 고객 (133, 132, 121, 131, 122, 123)
**💎 특징:**  
- 장기간 구매가 없는 고객 → **완전한 이탈 가능성**  

**🔥 액션 플랜:**  
- 💰 **이탈 고객 전용 "복귀 환영 할인" 제공**  
- 📩 **"우리를 다시 찾아주시면, 특별 혜택을 드립니다!"**  
- 🔥 **SNS 리타겟팅 광고 진행 (페이스북, 인스타 광고 활용)**  

---

## 🚀 **최종 정리: RFM 기반 맞춤 액션 플랜**
1️⃣ **VIP & 충성 고객 유지** → 특별 혜택 제공 & 멤버십 운영  
2️⃣ **잠재적 고가치 고객 락인** → 추가 리워드 & VIP 전환 유도  
3️⃣ **신규 고객 온보딩 최적화** → 첫 30일 내 브랜드 경험 강화  
4️⃣ **이탈 위험 & 일시적 고객 재구매 유도** → 맞춤형 프로모션 진행  
5️⃣ **이탈 고객 복귀 전략** → 강력한 할인 & 리타겟팅 마케팅 진행  

🔥 **결론:**  
_"이커머스에서 RFM 전략을 최적화하면 충성 고객을 극대화하고, 이탈을 최소화할 수 있다."_ 🚀



4. Revenue(수익화)
 
    - LTV(Life Time Value, 고객 생애 가치)
        사용자당 평균 월간 수익(ARPU) 기반 계산법: LTV = ARPU × 평균 구독 기간
            ARPU: 사용자당 (월간) 평균 구독 매출
        이탈률(Churn Rate) 기반 계산법: LTV = ARPU / 이탈률(Churn Rate)
            이탈률: 전체 고객 중 구독을 취소한 고객의 비율
    
    - LTR

    - CAC = 총 획득 비용 / 획득한 신규 고객 수
    (임의 지정)
        https://www.newstap.co.kr/news/articleView.html?idxno=185414
        ==> 전체 매출의 20~30% 광고비로 지출
    - PU(Paying User, 결제 유저)
    - ARPU(Average Revenue Per User, 유저 당 평균 수익)
    - ARPDAU 데일리
    - ARPWAU 위클리
    - ARPPU (Average Revenue Per Paying User, 결제 유저 당 평균 수익)

    ==> 매출 예측




## 데이터 전처리















PROBLEM
유입 경로 X
가입 일자 X