# javascript-racingcar-precourse

자동차 경주 게임 구현

## 기능 목록

### 유저 입력 처리

- [x] 사용자는 경주할 자동차에 각각 이름(name)을 부여할 수 있다.
- [x] 자동차 이름 입력시 n대의 자동차 이름을 입력하며, 이를 통해 경주에 참여하는 자동차 수를 정한다.
- [x] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
- [x] 사용자에게 몇 번의 이동을 할 것인지 라운드 횟수(total round)를 입력할 수 있다.

### 자동차 경주 실행 및 실행 결과 출력

- [x] 사용자가 입력한 이동 횟수(total round) 만큼 자동차 경주 함수를 실행한다.
- [x] 각 차수(round)마다 n대의 자동차는 각각 전진 또는 정지(전진하지 않음) 할 수 있다.
- [x] 자동차는 매번 0에서 9 사이의 무작위 값을 구한 후, 무작위 값이 4 이상일 경우 전진하고 4 미만일 경우 정지한다.
- [x] 실행 결과를 출력한다. (자동차마다의 출력 문구: `${자동차 이름(name)} : ${자동차 위치(position)}`)
- [x] 자동차의 위치(position)는 '-'로 표시한다. ('-'는 1회 전진, '--'는 2회 전진)

### 우승자 계산 및 출력

- [ ] 주어진 횟수 동안 가장 많이 전진한 자동차를 우승자(winner)로 출력한다. (출력 문구: `최종 우승자 : ${우승자(winner)}`)
- [ ] 우승자는 한 명 이상일 수 있다.
- [ ] 우승자가 여러 명일 경우 쉼표를 이용하여 구분한다.

### 에러 처리

- [x] 사용자가 잘못된 값을 입력한 경우 "[ERROR]"로 시작하는 메시지와 함께 `Error`를 발생시킨 후 애플리케이션이 종료된다.
- [x] 자동차 이름이 5자를 초과할 경우
- [x] 경주할 자동차 이름을 1개 이하로 지정한 경우
- [x] 시도할 횟수에 양의 정수 값이 아닌 값을 입력한 경우
- [x] 값을 입력하지 않은 경우
