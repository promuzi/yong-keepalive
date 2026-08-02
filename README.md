# yong-keepalive

[용사냥꾼](https://yong-server.onrender.com) 게임 서버(Render 무료 티어)가 잠들지 않게
10분마다 헬스 체크를 보내는 워크플로 전용 저장소.

- `ping.yml` — 10분마다 `https://yong-server.onrender.com/` 핑 (15분 유휴 슬립 방지)
- `heartbeat.yml` — 주 1회 더미 커밋 (60일 무활동 시 GitHub가 스케줄을 끄는 것 방지)

게임 코드는 별도 비공개 저장소에 있다. 여기엔 비밀이 없다.
