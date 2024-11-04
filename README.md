# 프리코스 3주차 _ 로또

## 📍 구현할 기능 목록
1. 로또 금액 입력받기
    - [x] '구입금액을 입력해 주세요.' 메시지 출력
    - [x] 사용자 입력 받기
    - 입력받은 로또 금액 유효성 검사 (* `[ERROR]`로 시작하는 에러 문구 출력)
        - [x] 빈 값을 입력한 경우
        - [x] 양의 정수가 아닌 값을 입력한 경우
        - [x] 숫자가 아닌 값을 입력한 경우
        - [x] Int 범위를 벗어나는 값을 입력한 경우
        - [x] 1000원으로 나누어 떨어지지 않는 경우

<br>

2. 로또 번호 생성
    - [ ] 로또 번호를 생성
    - [ ] `Randoms.pickUniqueNumbersInRange(1, 45, 6)` 이용
    - 제공된 `Lotto` 클래스를 사용하여 구현

<br>

3. 발행한 로또 수량 및 번호 출력
    - [ ] 입력한 금액만큼 발행한 로또 수량 출력
    - [ ] 수량만큼 발행된 번호 출력

<br>

4. 당첨 번호 입력받기
    - [x] '당첨 번호를 입력해 주세요.' 메시지 출력
    - [x] 사용자 입력 입력받기
    - 입력받은 당첨 번호 유효성 검사 (* `[ERROR]`로 시작하는 에러 문구 출력)
        - [x] 빈 값을 입력한 경우
        - [x] 구분자로 쉼표를 사용하지 않은 경우 (문자열로 처리해서 에러 발생)
        - [x] 1 ~ 45 범위를 넘어간 값을 입력한 경우
        - [x] 6개보다 적거나 6개를 넘게 입력한 경우

<br>

5. 보너스 번호 입력받기
    - [ ] '보너스 번호를 입력해 주세요.' 메시지 출력
    - [ ] 사용자 입력받기
    - 입력받은 보너스 번호 유효성 검사 (* `[ERROR]`로 시작하는 에러 문구 출력)
        - [ ] 1 ~ 45 범위를 넘어간 값을 입력한 경우
        - [ ] 빈 값을 입력한 경우
        - [ ] 당첨 번호와 중복되는 경우

<br>

6. 당첨 내역 출력하기
    - [ ] 당첨금은 3자리 마다 쉼표(,)로 구분
    - [ ] 3개부터 6까지 일치하는 내역 계산
    - [ ] 당첨 내역 출력

<br>

7. 수익률 출력하기
    - [ ] `당첨금액 / 구입금액 * 100` 으로 수익률 계산
    - [ ] 수익률 결과값은 소수점 둘째 자리에서 반올림

<br>

8. 단위 테스트 진행하기
    - [ ] 구현한 기능에 대한 단위 테스트 진행