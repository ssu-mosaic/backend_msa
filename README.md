# 마이크로서비스 아키텍처로 변경한 백엔드
## 사용 기술 : Spring cloud, Maria DB, redis, AWS EC2, Rabbit MQ, Kafka

서비스 구성
- service-discovery : 서비스 디스커버리로, 마이크로서비스들을 관리 
- apigateway-service : API 게이트웨이 마이크로서비스 
- user-service : 유저 마이크로서비스 

추가할 내용
- cart-service
- order-service
- retailer-service
- item-service
- stock-service
- config-server

수정해야 할 사항
- user-service : 회원 삭제가 DELETE가 아닌 POST
