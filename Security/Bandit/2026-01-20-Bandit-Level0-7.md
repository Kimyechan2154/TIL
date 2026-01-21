#Bandit

Bandit 0	완료	ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

Bandit 1	완료	263JGJPfgU6LtdEvgfWU1XP5yac29mFx

Bandit 2	완료	MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

Bandit 3	완료	2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

Bandit 4	완료	4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

Bandit 5	완료	HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

Bandit 6	완료	morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

Bandit 7	완료	dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

Linux Command Dictionary

기본 명령어

- **ls** - 현재 위치한 폴더 안에 있는 파일과 폴더의 이름 목록을 보여줌.
- **ls -a** - 숨겨진 파일(이름이 `.`으로 시작하는 파일)까지 포함해 모든 목록을 보여줌.
- **cat [파일명]** - 파일의 내용을 터미널 화면에 텍스트로 출력하여 읽음.
- **file [파일명]** - 파일의 내용을 열어보지 않고도 종류(Text, Data 등)를 알려줌.
- **clear** - 복잡해진 터미널 화면을 깨끗하게 지움.
- **exit** - 현재 접속 중인 터미널 세션을 종료하고 빠져나옴.

**특수 기호 (Syntax)**

- **./** - '현재 폴더'를 의미하는 기호 (파일명이  등으로 시작할 때 경로 지정용으로 사용).
- - '모든 것(All)'을 의미하는 와일드카드. (예: `file *`는 모든 파일 검사).
- **" "** - 파일명에 **공백(띄어쓰기)**이 포함되었을 때, 하나의 이름으로 묶어주는 기호.

**검색 명령어 (Find)**

- **find . -size [크기]** - 현재 폴더(`.`)를 포함한 하위 경로에서 지정한 **크기(size)**를 가진 파일을 검색함.
- **1033c** - find 명령어에서 크기 단위. (숫자 뒤에 `c`는 **바이트(byte)**, `k`는 **킬로바이트(KB)**를 의미).********
