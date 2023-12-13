## 📽️ 포트폴리오 소개
   - 배경색 : #222
   - 포인트 색 : #A785EF
   - 기본 폰트색 : #000
   - 벤치마킹한 사이트 : 키노라이츠(https://m.kinolights.com)
   - 들어간 기술 : Html, Jsp, Css, JavaScript, jQuery, Apache Tomcat, Spring, MySQL, aJax, Python, MyBatis
   - 사용한 툴 : Visual Studio Code, IntelliJ, Notion, MySQL Workbench

## 📽️ 페이지 구성
	- 헤더
		1. 로고 클릭 : 메인 페이지로 이동.
		2. 영화 전체보기 클릭 : 전체 영화 리스트 페이지로 이동.
		3. 차트 클릭 : 분류 별로 영화를 찾아볼 수 있는 페이지로 이동.
		4. 키워드 찾기 클릭 : 키워드를 골라 영화를 찾아볼 수 있는 페이지로 이동.
		5. 로그인 세션 없을 시 로그인 / 회원가입, 있을 시 로그아웃 / 마이페이지 보임.

   	- 메인 페이지
        	https://github.com/songyouyoung/movieLike/assets/144079150/d8c73b20-2639-44d3-b2ae-3ee66f73f06e
		https://github.com/songyouyoung/movieLike/assets/144079150/57980a38-b8cb-4e6c-b25c-31fb6d9bdae9
		1. 메인 배너 : 로그인 세션 있을 시 해당 회원의 관심 장르에 맞춰 최신 영화 출력, 로그인 세션 없을 시 최신 영화 출력.
		2. 검색바 : 돋보기 버튼 클릭, 엔터 쳤을 시 검색어에 맞는 영화 리스트 페이지로 이동.
		3. 인기 순위, 넷플릭스 인기 순위 : 영화 평점 준 사람 수, 영화 평점으로 정렬해서 Top 10개 출력.
		4. 많이 검색한 영화 : 영화 상세 페이지에 들어간 count 수로 정렬해서 Top 10개 출력.
		5. 베스트 리뷰 : 리뷰 좋아요 순으로 정렬해서 Top 3개 출력.
		6. 시리즈 : 시리즈 별 최신 순으로 정렬해서 Top 6개 출력.

   	- 리스트 페이지
	     	https://github.com/songyouyoung/movieLike/assets/144079150/b11a99dc-6147-44fb-9732-6dd98d793435
		1. 메인 -> 검색 : 검색어에 맞는 영화 출력. 영화 제목, 배우, 감독 다 조회 가능. 
		2. 메인 -> 시리즈 더보기 : 선택한 시리즈에 맞는 영화 출력. 
		3. 차트 -> 분류 : 선택한 분류에 맞는 영화 출력. 
		4. 차트 -> 나이대별 : 현재 날짜 기준으로 해당 나이의 연도를 계산해서 그 날짜 사이의 값을 조회.
   			- 해당 나이대의 사람이 봤다고 체크한 영화 출력. 
			- 해당 나이대의 사람이 많이 본, 평점 준 사람 수, 평점 순으로 정렬해서 출력.
		5. 마이페이지 -> 봤어요, 찜, 평점 : 선택한 분류에 맞는 영화 출력. 
		6. 불러오는 리스트에 맞게 타이틀 변경.
		7. 무한 스크롤로 영화 추가로 출력. 

   	- 키워드 찾기 페이지
     		https://github.com/songyouyoung/movieLike/assets/144079150/0f50f109-4d7a-41e8-8282-4fb88cef9a0b"
		1. 장르별, 국가별, OTT별, 리뷰 수, 평점 별로 원하는 키워드 클릭 시 비동기방식으로 즉시 영화 리스트 출력
		2. 리뷰 수, 평점은 하나만 선택 가능. 
		3. 키워드 선택 시 배경색 바뀌고, 아래에 선택한 태그들 출력. 
		4. 같은 분류 내에서는 or검색, 분류끼리는 and검색으로 영화 조회. 
		5. 영화 출력 후 최 하단에 더보기 버튼 생김. 더보기 버튼 클릭 시 영화 추가로 출력. 

   	- 차트 페이지
	     	https://github.com/songyouyoung/movieLike/assets/144079150/7524279a-14b8-432d-8efe-94bb3c547941"
		1. 장르별, 국가별, OTT별, 연도별, 나이대별로 나누어서 해당 분류에 대항하는 리스트 페이지로 이동. 

   	- 상세 페이지
		1. 영화 정보 출력. 
		2. 해당 영화의 베스트 리뷰 3개 출력. 
		3. 찜, 좋아요 클릭 시 로그인 안했을 때 로그인하라고 함. 
		4. 하단에 해당 영화의 리뷰 리스트 출력. 
		5. 리뷰 등록 클릭 시 로그인 안했을 때 로그인하라고 함.
		6. 자신이 등록한 리뷰만 수정 / 삭제 보임. 
		7. 자신이 좋아요 누른 댓글만 좋아요 이미지에 빨간색 표시. 

   	- 마이 페이지
	     	https://github.com/songyouyoung/movieLike/assets/144079150/82f035a5-978f-4bc4-99c5-470fa69ef5d4
		1. 회원가입 시 선택한 선호 장르 태그 출력. 클릭 시 해당 장르 영화 리스트 페이지로 이동.
		2. 자신이 작성한 리뷰 수 출력. 클릭 시 하단 자신이 작성한 리뷰 리스트로 이동.
		3. 자신이 본 영화 수, 찜한 영화 수 출력. 클릭 시 자신이 본, 찜한 영화 리스트 페이지로 이동. 
		4. 사용자가 준 평점 파트 출력. 클릭 시 자신이 준 평점에 해당하는 영화 리스트 페이지로 이동. 
		5. 톱니바퀴 클릭 시 개인정보변경 / 회원탈퇴 가능. 
		6. 개인정보 변경 / 회원탈퇴 시 비밀번호 한 번 확인하고 진행. 
		7. 개인정보 변경 클릭 시 고객 정보 불러와서 출력하고, 입력한 값들 정규식으로 유효성체크하고 빈값 체크해서 유저정보 update. 
		8. 회원탈퇴 클릭 시 해당 회원 정보, 작성한 리뷰, 본 영화, 찜한 영화 삭제. 

	- 로그인 페이지
		1. 아이디, 비밀번호가 공란일 시 오류메시지 표시.

	- 회원가입 페이지
		1. 입력칸 정규식으로 유효성체크하고 공란 체크해서 오류메시지 표시.
		2. 장르 선택 3개 초과해서 선택 시 오류메시지 표시.

	- 아이디/비밀번호 찾기 페이지
		1. 아이디 찾기 : 유저 정보를 입력하면 해당 유저의 아이디를 팝업 띄움.
		2. 비밀번호 찾기 : 유저 정보를 입력하면 비밀번호 수정할 수 있는 팝업 띄움.
