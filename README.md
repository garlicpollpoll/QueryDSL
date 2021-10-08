# QueryDSL

QueryDSL 강의를 마치고 만든 토이프로젝트 입니다. JPA강의가 모두 끝났으므로 배운 내용을 총 집합시켜서 복습하는 느낌으로 만든 프로젝트 입니다. 

주제 : 간단한 회원가입, 상품등록, 상품구매, 주문취소, 다양한 검색을 포함하고 있는 커머스 카피캣

구현한 내용 (타임리프를 활용한 뷰, RestfulAPI)

*Member 부분
1. 이름, 나이, 로그인아이디, 로그인패스워드, 주소를 입력받아 회원가입
2. 로그인 (세션사용)
3. 전체 회원 조회

*Item 부분
1. 아이템이름, 가격, 수량, 프랜드명(없어도됨), 카테고리를 입력받아 상품 등록 
2. 모든 상품을 볼 수 있는 조회
3. 브랜드명, 카테고리, 최소금액, 최대금액을 설정해서 검색할 수 있는 기능 추가 (QueryDSL사용)
4. 상품 상세에서 댓글 달기 기능 추가
5. 상품 주문 (주문하면 수량에서 1 깎임)

*Order 부분
1. 상품을 주문할 수 있음
2. 아이템이름, 주문상태를 설정해서 검색할 수 있음 (QueryDSL 사용)
3. 주문 취소 (취소하면 수량 1증가)
