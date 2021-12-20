![1](https://user-images.githubusercontent.com/86215668/146786108-f3962b49-84e0-4c73-a839-d92d8c0ca284.png)  
  
  
------------------------------------------------------------------------------------------------  
# Smart_Factory_APS_System  
Use machine learning techniques to predict sales and automatize production and shipping process at a factory  
  
2021/10/18 ~ 2021/11/12  
  
  
  
  
APS System 발주자동화 시스템 구축  
------------------------------------------------------------------------------------------------  
  
  
  
  
### 비즈니스 이슈  
  
1. 고객사는 직전 3개월 판매량을 기반으로 이후 3개월을 예측하고있으나 실제 판매량과  
  약 30% 의 오차로 납기 지연 및 재고증가등의 문제로 불필요한 비용 발생의 리스크가 있음  
  
2. 경험에 따른 단기예측으로 중장기 수요에 대한 대비의 부족  
  
3. 원재료 재고파악부터 발주량 산출 및 원재료 발주를 모두 수작업으로 진행,  
   원재료 재고파악 부분의 경우 매일 약 90분의 소요시간이 발생  
   다소 비효율적인 업무를 진행하고 있음  
  
  
  
  

### 비즈니스 이슈를 해결을 위한 APS 도입을 통하여 생산판매, 중장기수요예측, 업무 자동화를 프로젝트 과제로 정의  
  
* APS(Advanced Planning & Scheduling) System  
  자재, 설비, 작업자 등과 같은 다양한 변수와 제약된 조건들을 동시에 고려하여  
  현실성 있는 최적의 스케줄링을 제공하는 시스템  
  
  
- 중장기예측 : keras GRU 모델을 활용한 시계열 예측 (예측일 180일)
- 회귀분석 을 통한 단기 일별예측 상관관계가 높은 변수를 추가하여 정확도 95% 로 기존70%에서 약 25% 높은 정확도의 결과를 도출
- 수주 => 발주 => 생산/판매 까지의 '리드타임' 고려하여 업무 자동화
- 앞선 단기판매예측모델을 활용한 자동발주 시스템 구축
- 재고 자동확인, 부족재고 자동발주로 업무효율성개선
       
  
  
  
### 기대효과  
  
1. 생산판매계획의 오차 최소화로 불필요한 비용 감소  
  
2. 중장기 수요예측 모델을 통한 설비투자 및 리스크 대비를 위한 예산계획 수립  
  
3. 업무 자동화를 통한 업무효율성 증대  
  
