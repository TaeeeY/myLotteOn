# LotteON 쇼핑몰 프로젝트

### 제작기간
--------------------------------------------------------------
2024.04.17 ~ 2024.05.17(1달)

### 프로젝트 개요
--------------------------------------------------------------

|항목|내용|
|------|---|
|프로젝트 소개|롯데e-커머스 기반 LOTTE ON 쇼핑몰 기능 개발|
|참여인원|총4명(Front/Back 동시 작업)|
|담당기능|상품 관련기능 구현, 마이페이지 일부기능 구현|


### 사용기술 
--------------------------------------------------------------
### 1. Front-End
  HTML<br>

  CSS<br>

  Thymeleaf<br>

  JavaScript
### 2. Back-end
  SpringBoot<br>

  JPA<br>

  QueryDSL<br>

  MyBatis

### 3. DataBase
  MySQL


### ERD
--------------------------------------------------------------
<details>
  <summary>ERD</summary>
  <img src="https://github.com/Taeyoung20230727/myLotteOn/assets/140632598/c1fe3251-5b57-4d09-934e-cf9cf4f0404c" alt="Description of the image">
</details>


### 핵심 구현기능
--------------------------------------------------------------
### 1. 메인페이지
- 배너 출력
- 상품 카테고리 마우스 hover 시 1,2,3 차 카테고리 출력
- 히트, 추천, 최신, 인기, 할인 상품 페이지 출력


### 2. 회원
 - 로그인, 아이디 기억하기 기능
 - 일반, 판매자 회원가입 구분
 - 선택한 회원 종류에 따른 이용약관 출력
 - 회원가입 유효성/중복 검사
 - 판매자 회원가입 유효성/중복검사
 - 아이디/비밀번호 찾기 가입시 입력한 이메일 사용하여 발송된 메일의 인증번호 기입 후 아이디 찾기, 비밀번호 재설정.


### 3. 고객서비스(CS)
 - 메인 : 공지사항, 문의하기, 자주하는 질문 카테고리 별 아이콘 출력 문의글 작성 클릭 시 작성 화면 이동.
 - 자주묻는 질문 : 유형별로 3개씩 출력 하고 아코디언 설정하여 더보기 가능함.
 - 공지사항 : 카테고리별로 출력함.
 - 문의하기 : 문의하기 카테고리 별로 출력 하며 문의하기글 작성 가능. 답변이 있는 경우 답변완료 답변이 없으면 검토중 출력


### 4. 상품

###  상품 목록
- 1,2,3차 카테고리 별로 등록된 상품 조회
- 상품 정보 출력하며 무료배송 시 아이콘 출력
- 
###  상품 검색
- 상품명 키워드로 검색
  
### 상품 상세
- 상품 정보 출력, 별점 및 상품평 보기
- 장바구니 / 구매하기 / 찜하기 기능
  
### 장바구니
- 상품 정보 출력 및 상품 체크 후 삭제, 수량 변경 및 선택한 항목만 구매가능
  
### 주문하기
- 구매할 상품 정보 출력 및 로그인 된 유저 기본 정보 출력, 수령자 정보 입력 가능 및 포인트 사용 가능. 최종결제 정보 확인 가능.
- 
### 주문완료
- 주문된 상품 및 금액, 주문자와 입력된 배송 정보 확인가능

 
### 5. 마이페이지
- 최근 주문내역, 포인트 적립내역, 상품평, 문의내역, 기본 정보 확인 가능
- 상품평 작성, 반품신청, 제품 문의 가능
- 포인트 내역
- 작성한 리뷰 확인 및 해당 상품으로 이동
- 작성한 고객문의, 상품 문의 답변 확인
- 비밀번호, E-mail, 휴대폰, 주소 변경
  
### 6. 판매자 상점 관리

### 메인
- 쇼핑몰 총 운영 현황 출력(주문 건수, 주문 금액, 배송 관리, 주문관리)
- 공지사항, 고객문의 확인 가능
  
### 상품관리
- 상품 목록 : 본인이 등록한 상품 검색 조회 및 삭제, 수정 가능(+옵션설정)
- 상품 등록 : 상품 등록 가능
  
### 주문관리
- 주문 현황 : 상품명/구매자 별 주문 현황 조회
- 매출 현황 : 판매 상품별 매출액/판매수 조회
  
### 7. 관리자(admin)

### 메인
- 쇼핑몰 총 운영 현황 출력(기간별 주문현황/ TOP3 카테고리 주문현황)
- 공지사항, 고객문의 확인 가능
 
### 환경설정
- 기본 환경 정보 : 쇼핑몰 이용약관 수정 가능
- 배너관리 : 배너 등록, 활성화 여부, 시작&종료 날짜 시간 조절 가능
- 
### 상점관리
- 가입한 모든 판매자 현황조회, 검색, 정보 열람 가능
  
### 회원관리
- 가입한 모든 유저 현황 조회, 수정, 탈퇴

### 상품관리
- 상품 목록 : 사이트에 등록된 모든 상품 검색 조회 및 삭제 가능
- 상품 등록 : 상품 등록 가능
  
### 배송 관리
- 배송현황 조회/수정
- 
### 고객센터
- 공지사항 : 카테고리에 따른 조회 및 글 등록, 삭제, 수정
- 자주묻는 질문 : 카테고리에 따른 조회 및 글 등록, 삭제, 수정
- 문의하기 : 카테고리에 따른 조회 및 답변 등록, 삭제, 수정
- 
### 8. 회사 소개(company)
- 메인, 기업문화, 소식과 이야기, 채용, 미디어 회사 소개 페이지
