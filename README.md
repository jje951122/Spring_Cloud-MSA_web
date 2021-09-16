# Spring Cloud, Eureka를 이용한 간단한 MSA 실습

## 웹 쇼핑몰 사이트
> MSA의 동작위주의 실습  
> MSA의 동작 학습/응용이 목적이기 때문에 상세한 기능 구현없이 ResponseEntity로 데이터만 출력  
> 사용한 기술 : 
>* Spring Boot  
>* Spring Cloud
>* Eureka
>* H2 DB
  
## 시스템 구성
> ![image](https://user-images.githubusercontent.com/76868571/133599444-77225bd5-c70c-4b39-bc9b-a056cb313985.png)

## 기능
> * user Micro service
>   + 사용자 등록
>   + 사용자 전체 조회
>   + 사용자 정보 조회
>   + 환영 메시지
> * catalog Micro service
>   + 상품 목록 조회
> * order Micro service
>   + 회원 상품 주문
>   + 회원 주문 내역 조회
