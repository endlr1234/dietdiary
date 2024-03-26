# 나의 식이요법 일기 프로젝트

## 기대효과

다어이트를 하는 사람들에게 오늘 하루 먹은 음식과 칼로리를 계산할 수 있고, 그날 하루에 대한 일기를 적으며 매일 내가 먹는 음식에 대해 기록하고 평가하여 다이어트에 도움을 줄 수 있게한다.

## 기능

- 회원가입 및 로그인
  - 회원가입시 이메일,비밀번호,휴대폰,이름,생년월일을 입력하여 가입한다.
  - 회원가입된 사용자는 로그인 할 수 있으며, 인증에는 jwt토큰을 이용한다.
  - 회원가입된 사용자는 이메일(아이디)을 통해서 인증 후 비밀번호 변경을 할 수 있다.(비밀번호 찾기에도 사용)

- 일기
  - 로그인된 회원은 그날의 먹은 음식과 칼로리를 계산하여 일기를 작성,수정,삭제 할 수 있다.
  - 사진도 업로드 할 수 있다.(10개 제한)

- 일기 조회
  - 로그인된 사용자는 본인의 일기를 날짜(기간)를 설정하여 조회할 수 있다.
  - 로그인된 사용자는 본인의 일기를 키워드를 이용하여 조회할 수 있다.(내용 또는 제목)

- 칼로리 계산기
  - 오늘 먹은 음식의 칼로리를 검색할 수 있다.
  - 칼로리 정보는 공공데이터 포털의 식품영양정보를 이용한다(https://www.data.go.kr/data/15057436/openapi.do)
  - 선택한 오늘 먹은 음식의 전체 칼로리를 합산한다. 

## ERD
