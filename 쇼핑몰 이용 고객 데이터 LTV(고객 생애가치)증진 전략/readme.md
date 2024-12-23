# 쇼핑몰 고객 데이터 분석을 통한 LTV(고객 생애가치) 증진 전략

전자상거래 플랫폼에서 **고객 유지(Customer Retention)**는 기업의 지속적인 성장과 수익성 향상을 위한 **핵심 전략**입니다. 이는 **신규 고객 획득(Customer Acquisition)**보다 **기존 고객의 재구매율과 구매 빈도**를 높이는 것이 더 **비용 효율적**이기 때문입니다. 

이를 위해 **기간별(Time Series Analysis)** 및 **카테고리별(Category Analysis)** 매출 데이터를 분석하여 **주요 고객 세그먼트**와 **매출 추세**를 파악합니다. 또한 **RFM(Recency, Frequency, Monetary) 분석**을 통해 현재 고객들의 **구매 행동 패턴**을 심층적으로 평가합니다. 이러한 분석 결과를 기반으로 **구매 활동성이 감소한 고객**을 식별하고, **개인화된 알림 메시지(Personalized Notifications)**를 전송하여 **재방문율**과 **고객 생애가치(Lifetime Value)**를 증진시키고자 합니다.

## 분석 목표

- 고객의 **추가 구매 유도**를 위한 **전략 수립**

## 분석 방법론

1. **기간별 매출 분석**: 시간에 따른 매출 추이 파악
2. **카테고리별 판매량 및 매출 분석**: 제품 카테고리별 성과 분석
3. **재방문 고객 분석**: 고객의 재구매 패턴 및 충성도 평가
4. **RFM 분석**: 고객의 최근성, 빈도, 금액을 기반으로 **구매 활동성 평가**

## 실행 방안

**고객 생애가치(LTV) 증진 전략**

- 다잇다 플랫폼의 모바일 고객 중 약 **57%**가 **1회 이상 구매한 재방문 고객**으로 확인되었습니다. 따라서 이 **재방문 고객을 대상으로 한 LTV 증진 전략**이 효과적일 것으로 판단됩니다.

1. **모바일 고객의 군집 생성**: 고객 데이터를 기반으로 **클러스터링 알고리즘**을 활용하여 고객 군집화
2. **군집별 적정 LTV 수준 파악**: 각 군집의 평균 LTV 분석 및 목표 설정
3. **LTV 수준이 낮은 고객에게 개인화된 알림 메시지 전송**: 구매 활동성 향상을 위한 **마케팅 캠페인 실행**