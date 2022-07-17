# jabis

swagger url 
http://localhost:8080/swagger-ui/index.html 

## 현재 config 오류로 작동 안됨

- /szs/signup
- /szs/login (id, password 쿼리 스트링으로 동작)
- /szs/scrap
- /szs/refund

## todo
- 예외 공통 로직
- Request 유효성 체크
- /szs/refund 미구현
- 회원 체크 (로그인, 회원 가입 중복, 권한 체크) 
- 주민 번호 인코딩
- 버전 동기화
- scrap db table 설계
- 테스트 코드 추가