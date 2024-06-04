# 룰렛 어벤져스 1차 프로젝트
WEB IDE 서비스

## 정보
- **백엔드**: Spring Security, Spring Boot, OAuth 2.0, Kakao API
- **프론트엔드**: React
- **배포 환경**: Kubernetes (Krampolin 사용)

## 기능 설명
1. **소셜 로그인 서비스 구현**
   - 카카오 로그인 API와 OAuth 2.0을 사용하여 소셜 로그인 서비스 구현
   - JWT토큰 사용
2. **게시판 CRUD 서비스 구현**
   - 사용자는 내가 원하는 디자인을 올려서 의뢰 게시물 생성가능
   - 개발자는 의뢰를 보고 그에 맞는 디자인의 코드를 생성 할 수 있다.
   - 게시판에서 게시물 작성, 읽기, 수정, 삭제 기능 제공
3. **WEB IDE 코드 렌더링**
   - html, css, javascript를 WEB IDE 상에서 입력하면 코드를 조합한 뒤 렌더링해서 출력
   - 코드는 txt 파일 형태로 서버에 저장 돼서 로그인 후 불러오기 가능
4. **웹소켓을 이용한 채팅 서비스 구현**
   - 의뢰주와 개발자가 채팅방 생성해서 실시간 채팅 가능
     
## 스크린샷
### 소셜 로그인 서비스 구현
<p align="center">
  <img src="https://github.com/kitewater/back/assets/97283971/71b74cd2-11e1-45f9-8baf-8dafc0bd5a8e" width="70%">
</p>

### 게시판 CRUD 서비스 구현
<p align="center">
  <img src="https://github.com/kitewater/back/assets/97283971/1883f55d-a4f2-4488-877f-e70ec580da27" width="70%">
</p>

### WEB IDE 코드 렌더링
<p align="center">
  <img src="https://github.com/kitewater/back/assets/97283971/2d9e8efc-871f-4b50-8d73-314ad050d5fd" width="70%">
</p>

### 웹소켓을 이용한 채팅 서비스 구현
<p align="center">
  <img src="https://github.com/kitewater/back/assets/97283971/f89b4b5a-8e90-44ee-bc94-e69c02b4a562" width="70%">
</p>
## 프로젝트 구조
<p align="center">
  <img src="https://github.com/kitewater/WEBIDE/assets/97283971/9991df56-1d15-401a-9d6c-ef5d80f8aa36" width="100%">
</p>  

## 크램폴린을 사용한 배포
### 크램폴린 배포 프로세스
<p align="center">
  <img src="https://github.com/kitewater/WEBIDE/assets/97283971/bea5556b-eeb2-4fec-bb0e-c3e996912762" width="100%">
</p>  

### 크램폴린 구조
<p align="center">
  <img src="https://github.com/kitewater/WEBIDE/assets/97283971/820eefbd-ad06-4148-b4f6-bec9ce0b82a8" width="100%">
</p>
