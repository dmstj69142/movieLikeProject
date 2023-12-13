## 📽️ 포트폴리오 소개
- 주제: 사용자가 고민 없이 편리하게 영화 선택을 돕는 웹사이트
- 배경색 : #222
- 포인트 색 : #A785EF
- 기본 폰트색 : #fff
- 벤치마킹한 사이트 : 키노라이츠(https://m.kinolights.com)
- 들어간 기술 : Html, Jsp, Css, JavaScript, jQuery, Apache Tomcat, Spring, MySQL, aJax, Python, MyBatis
- 사용한 툴 : Visual Studio Code, IntelliJ, Notion, MySQL Workbench


## 📽️ 개발 기간
- 2023.11.09 ~ 2023.11.29


## 📽️ 페이지 구성
#### 헤더
- 로고 클릭 : 메인 페이지로 이동
- 영화 전체보기 클릭 : 전체 영화 리스트 페이지로 이동
- 차트 클릭 : 분류 별로 영화를 찾아볼 수 있는 페이지로 이동
- 키워드 찾기 클릭 : 키워드를 골라 영화를 찾아볼 수 있는 페이지로 이동
- 로그인 세션 없을 시 로그인 / 회원가입, 있을 시 로그아웃 / 마이페이지 보임


#### 메인 페이지 ( <a href="https://github.com/songyouyoung/movieLike/assets/144079150/d8c73b20-2639-44d3-b2ae-3ee66f73f06e">메인페이지</a> / <a href="https://github.com/songyouyoung/movieLike/assets/144079150/57980a38-b8cb-4e6c-b25c-31fb6d9bdae9">검색페이지</a> )
- 메인 배너
  	- 회원가입시 선택한 영화장르로 메인베너에 추천 영화의 예고편 출력하고 로그인 세션 없을 시 최신 영화 예고편 출력
  	- 메인베너 자동으로 돌아가고 오른쪽 버튼 클릭시 다음 영상 보이고 왼쪽 버튼 클릭시 이전 영상 보임
- 검색바 : 영화제목, 감독, 배우 검색시 검색 페이지로 이동, 검색한 영화 리스트 불러옴
- 인기 순위, 넷플릭스 인기 순위 : 스와이퍼 기능 / 영화 평점 준 사람 수, 영화 평점으로 정렬해서 Top 10개 출력
- 많이 검색한 영화 : 스와이퍼 기능 / 영화 상세 페이지에 들어간 count 수로 정렬해서 Top 10개 출력
- 베스트 리뷰 : 전체 영화 리뷰 좋아요 순으로 정렬해서 Top 3개 출력
- 시리즈 : 시리즈 별 최신 순으로 정렬해서 Top 6개 출력, 더보기 버튼 클릭시 해당 영화 리스트 페이지로 이동
- 영화 포스터 클릭 : 해당 영화의 상세 페이지로 이동

#### 상세 페이지
- 해당 영화 정보 출력
- 해당 영화의 베스트 리뷰 3개 출력
- 로그인 안되어있을 경우 로그인 후 사용가능한 팝업창 띄우고 로그인 후 찜, 봤어요 버튼 클릭시 애니메이션으로 클릭 효과
- 공유 버튼 클릭시 해당 링크 복사됨
- 리뷰 작성
	- 리뷰 작성 버튼 누르면 리뷰 작성 칸으로 이동 
	- 별점 (1~5) 선택 (5 누르면 5개) 색상 변화 
	- 리뷰내용 입력 후 등록 버튼 누르면 리뷰리스트에서 확인 가능 
	- 로그인 안되어있을 경우 로그인 후 사용가능한 팝업창 띄우기 
	- 별점이나 리뷰내용 비어있으면 입력하라는 메시지 띄움 
	- 좋아요 버튼 (애니메이션 효과와 숫자 1 증가)
	- 수정 버튼 클릭시 수정 가능하도록 변경
	- 삭제 버튼 클릭시 해당 리뷰 삭제 
	- 최신순, 좋아요순 선택 가능 

#### 리스트 페이지 ( <a href="https://github.com/songyouyoung/movieLike/assets/144079150/b11a99dc-6147-44fb-9732-6dd98d793435">리스트페이지</a> )
- 해당 영화의 리스트 확인 가능
- 최신순, 인기순으로 선택 가능
- 무한 스크롤로 영화 추가로 출력

#### 키워드 찾기 페이지 ( <a href="https://github.com/songyouyoung/movieLike/assets/144079150/0f50f109-4d7a-41e8-8282-4fb88cef9a0b">키워드 페이지</a> )
- 장르별, 국가별, OTT별, 리뷰 수, 평점 별로 원하는 키워드 클릭 시 비동기방식으로 즉시 영화 리스트 출력
- 리뷰 수, 평점은 하나만 선택 가능
- 키워드 선택시 배경색 변경, 선택한 키워드 하단에 출력, X 버튼 클릭시 선택한 키워드 선택해제 
- 같은 분류 내에서는 or검색, 분류끼리는 and검색으로 영화 조회
- 키워드에 해당하는 영화 목록 출력, 더보기 버튼 클릭시 20개씩 리스트 출력
- 최신순, 인기순으로 선택 가능
- 영화 호버시 테두리, 그림자
- 영화 클릭시 해당 영화 상세 페이지로 이동

#### 차트 페이지 ( <a href="https://github.com/songyouyoung/movieLike/assets/144079150/7524279a-14b8-432d-8efe-94bb3c547941">차트 페이지<a/> )
- 장르별, 국가별, OTT별, 연도별, 나이대별로 나누어서 해당 분류에 대항하는 리스트 페이지로 이동.
- 장르별, 국가별 키워드 호버시 판 위로 올라옴

#### 마이 페이지 ( <a href="https://github.com/songyouyoung/movieLike/assets/144079150/82f035a5-978f-4bc4-99c5-470fa69ef5d4">마이페이지<a/> )
- 로그인 후 이동 가능 (로그인하면 메인페이지에 마이페이지가 뜸) 
- 회원가입 시 선택한 선호 장르 태그 출력, 클릭 시 해당 장르 영화 리스트 페이지로 이동
- 톱니바퀴 호버 시 개인정보변경 / 회원탈퇴 가능
- 개인정보 변경 / 회원탈퇴 시 비밀번호 한 번 확인하고 진행
- 개인정보 변경 클릭 시 고객 정보 불러와서 출력하고, 입력한 값들 정규식으로 유효성체크하고 빈값 체크해서 유저정보 update
- 회원탈퇴 클릭 시 해당 회원 정보, 작성한 리뷰, 본 영화, 찜한 영화 삭제
- 내가 찜한 목록, 봤어요 목록, 리뷰수 확인 가능, 찜, 봤어요 클릭시 리스트 페이지로 이동, 내가 찜한, 본 목록 확인 가능 
- 차트 (평점 준 영화들 차트로 확인 가능)
- 내가 작성한 리뷰 정보 확인 가능, 최신순/좋아요순 확인, 수정/삭제 가능

#### 로그인 페이지
- 아이디, 비밀번호가 공란일 시 오류메시지 표시.
- 아이디 기억하기
- 아이디/비밀번호 찾기 클릭시 해당 페이지로 이동

#### 회원가입 페이지
- 입력칸 정규식으로 유효성체크하고 공란 체크해서 오류메시지 표시
- 생년월일 1940년부터 현재 년도까지 보이고 월 선택에 따라 일 수가 다르게 나타남
- 전화번호 자동 줄바꿈
- 장르 선택 3개 초과해서 선택 시 오류메시지 표시

#### 아이디/비밀번호 찾기 페이지
- 아이디 찾기 : 유저 정보를 입력하면 해당 유저의 아이디를 팝업 띄움
- 비밀번호 찾기 : 유저 정보를 입력하면 비밀번호 수정할 수 있는 팝업 띄움
