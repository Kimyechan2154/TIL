# 📅 2026-01-25 공부 기록
# 주제: OverTheWire Bandit (Level 13 → 14)

---

## 1. 문제 목표
다음 레벨(bandit14)로 가기 위한 비밀번호가 주어지지 않고, 대신 **SSH 개인키(private key)**가 홈 디렉토리에 있음.
이 키를 이용해서 bandit14 계정으로 로그인을 성공해야 함.

## 2. 접근 방법
보통은 패스워드를 찾아서 입력하는데, 이번엔 파일(`sshkey.private`)만 덩그러니 있음.
이 파일이 '집 열쇠' 같은 역할을 한다는 것을 파악함.
내 컴퓨터에서 원격 서버로 접속할 때 쓰는 ssh 명령어를, **서버 내부에서 다시 자기 자신(localhost)에게 접속**하는 방식으로 응용해서 풀어야 함.

## 3. 풀이 명령어
```bash
# 1. 키 파일 확인
ls
# (sshkey.private 파일이 보임)

# 2. 개인키를 이용해 다음 레벨 유저로 접속 (localhost = 나 자신)
ssh -i sshkey.private bandit14@localhost
