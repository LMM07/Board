# 확장형 게시판
기본 CRUD 게시판에 기능을 붙이는 확장형 게시판입니다.


### 사용한 것
Java, SpringBoot, Spring Security, JPA, H2, Thymeleaf, JavaScript, CSS, Bootstrap


### 구현된 기능
- 로그인
- 회원가입
- 질문 CRUD
- 답변 CRUD
- 추천기능
- 앵커기능
- 마크다운
- 검색
- 마이페이지 : 내가 쓴 글, 내가 쓴 답변
- 조회수


### 화면 구성
- 게시글 목록
  ![list](https://github.com/LMM07/Board/assets/93696194/e507bd3b-3893-4fc1-919c-1babe2ff7608)
1. 게시글 넘버링, 제목, 글쓴이, 작성일시, 조회수로 화면 구성
2. Page, PageRequest, Pageable 클래스를 이용해 페이징 구현
3. JPA의 Specification 인터페이스를 사용해 검색 구현


- 로그인 및 회원가입
  ![login_02](https://github.com/LMM07/Board/assets/93696194/71f95678-32c8-4d27-92eb-5d6aa719a650)
  ![signup_02](https://github.com/LMM07/Board/assets/93696194/2e69f93d-6d0f-4dfa-a4c8-7f8d22ff7674)
1. Spring Securiry 를 이용해 로그인 및 회원가입 기능 구현
2. 중복 회원가입 방지
3. 아이디 혹은 비밀번호 입력 실패 시 오류 메세지 발생


- 질문 및 답변 게시글 CRUD
  ![detail_question 02PNG](https://github.com/LMM07/Board/assets/93696194/12f9949e-58a5-472b-8a01-49c3cdfa9fc2)
  ![detail_answer](https://github.com/LMM07/Board/assets/93696194/51236e69-d932-40f7-8b19-48bbd52f34e1)
1. 질문 및 답변 게시글 작성, 수정, 삭제, 읽기 기능 구현
2. 게시글 추천 기능 추가
3. 게시글 작성일, 수정일 추가
4. 게시글 마크다운 추가
5. 답변 앵커 기능 추가


- 마이페이지
  ![mypage](https://github.com/LMM07/Board/assets/93696194/28dbfa76-0912-417a-9969-a31f2a31e1b1)
1. 나의 정보 불러오기
2. 내가 쓴 글, 답변 확인 및 바로가기 링크 추가
  


#### 참고 및 출처
[위키독스](https://wikidocs.net/book/7601)



