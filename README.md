## 기능 목록
숫자 야구 게임을 위한 클래스와 구현 항목

### BaseBallGame
- Pitcher 객체와 Catcher 객체를 전달 받아 BaseBallGame 객체 생성
- 게임 시작
- 매 턴마다 게임이 진행 중인지 boolean값으로 확인
- 한 게임 종료 시 사용자로부터 재시작/종료 인풋 받기

### Pitcher
- 게임 턴마다 숫자 입력 받기
- 입력 받은 숫자 유효성 검증(음수, 3자리수, 중복된수)
- int 타입으로 받은 값 int[]로 반환

### Catcher
- 게임 시작시 Catcher숫자 랜덤 생성(중복없는 1부터 9까지의 3자리수)
- Pitcher로 부터 전달 받은 숫자 비교로 스코어 연산
- 결과값 출력
- 게임 진행 중인지 3 strike 인지 boolean값으로 반환

### Utils
- 사용자 인풋값 숫자인지 유효성 검증
