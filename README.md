# Musinsa Clothes Recommendation System
- - - 
### 추천 시스템의 목적 - 주제 선정 이유
> 과도한 정보와 선택지로 인한 의사결정 시간의 기회비용 증가
> 개인 맞춤화 상품 추천 서비스의 중요성 부각
> 추천시스템의 작동원리 파악
> 사용 목적이나 사용자의 특성을 파악한 맞춤형 추천 시스템 개발

### 프로젝트 진행 개요 
> 3월 : 크롤링, 추천시스템 관련 스터디 진행
  * 프로젝트 1주차 과제.ipynb ~ 프로젝트 6주차 과제.ipynb
> 4월 : 데이터 수집 및 분석 
  * Crawling code.ipynb
> 5월 ~ 6월 
  * ContentsBased Recommendation.ipynb   
  * Recommendation system Final.ipynb
  * Sentiment Analysis User review .ipynb

### 데이터 수집 방식
![image](https://user-images.githubusercontent.com/83954540/143733290-cb87b4c1-a75c-4393-a4a0-674e9f7b6724.png)

* 데이터 
![image](https://user-images.githubusercontent.com/83954540/143733302-1c12aad8-87d7-444f-8f2c-b77dbbc0762f.png)
![image](https://user-images.githubusercontent.com/83954540/143733322-f69d9fef-c9aa-41bc-9693-32b8e39e5438.png)
- - - 
### 프로세스 개요 
* 컨텐츠 메타 데이터 
![image](https://user-images.githubusercontent.com/83954540/143733358-8097dd0b-4bcd-44fe-bd4a-ce7384aa50aa.png)
![image](https://user-images.githubusercontent.com/83954540/143733373-1e067a1e-51e7-496a-960d-c3056c475184.png)
![image](https://user-images.githubusercontent.com/83954540/143733384-f59e80d9-4cac-4385-833b-58e25dfc5fff.png)
- - - 
* 사용자 행동 데이터 
![image](https://user-images.githubusercontent.com/83954540/143733421-366248e6-9bb0-45d7-b62b-0c9e1c6fce5a.png)
![image](https://user-images.githubusercontent.com/83954540/143733413-acba7786-4618-4336-8eca-77093f32da98.png)
![image](https://user-images.githubusercontent.com/83954540/143733432-3656aef1-0f66-47b3-85b8-0610d597a0a3.png)
- - - 
* 결과 앙상블 
![image](https://user-images.githubusercontent.com/83954540/143733449-7086afb6-f347-4cbc-ba74-ac128a7d783a.png)
- - - 

### 보완 사항
- 수집한 모든 데이터를 활용하지 못한 점
- (키, 몸무게를 비롯한 개인의 정보를 충분히 활용하지 못함)
- 신발이나 악세서리를 비롯한 다른 데이터를 추가적으로 수집하지 못한 점
- (단순히 상의와 하의에 대해서만 추천)

### 한계 
*cold-start problem*
- 추천서비스를 위한 데이터 부족
- 기본적인 성능을 보장하는 협업필터링 모델 구축이 쉽지 않은 것이 일반적
- 컨텐츠 기반 또는 지식 기반의 방법 역시 서비스로 적용하기 어려움
*Scalability*
- 실제 서비스 상황은 다양한 종류의 데이터
- 학습 또는 분석에 사용한 데이터와는 전혀 다른 실전 데이터
*The Long Tail Model*
- 초록 이외 부분이 90%라고 했을 때, 추천 시스템은 Highly popular한 10%에 대해서만 집중적으로 추천
- 이는 플랫폼을 운영하는 사람 입장에서 한쪽으로 치우치게 되며 결과적으로 좋지 않은 현상
![image](https://user-images.githubusercontent.com/83954540/143733533-33714071-4326-42d4-a247-6180a5c01c3d.png)

### 첨고 문헌
• https://brunch.co.kr/@kakao-it/72
• 평점과 리뷰 텍스트 감성분석을 결합한 추천시스템 향상 방안 연구
• https://eda-ai-lab.tistory.com/528
• https://greeksharifa.github.io/machine_learning/2019/12/17/Recommendation-System/
