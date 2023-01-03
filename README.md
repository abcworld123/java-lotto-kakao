# java-lotto-kakao

# OOP-로또 자동 1단계

## 기능 요구사항
- 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
- 로또 1장의 가격은 1000원이다.
```
구입금액을 입력해 주세요.
2000
2개를 구매했습니다.
[1, 3, 5, 14, 22, 45]
[2, 8, 9, 18, 19, 21]

지난 주 당첨 번호를 입력해 주세요.
1, 2, 3, 4, 5, 6
보너스 볼을 입력해 주세요.
7

당첨 통계
---------
3개 일치 (5000원)- 1개
4개 일치 (50000원)- 0개
5개 일치 (1500000원)- 0개
5개 일치, 보너스 볼 일치(30000000원) - 0개
6개 일치 (2000000000원)- 0개
총 수익률은 2.5입니다.(기준이 1이기 때문에 결과적으로 손해라는 의미임)
```

## 기능 정의
- [ ] 금액 입력 받기
- [ ] 장 수가 몇 장인지 계산
- [ ] 금액 예외처리
- [ ] 로또 6자리 발급 기능
  - [x] 로또 번호는 1 ~ 45 사이의 자연수이다.
  - [x] 로또 번호는 중복되면 안된다.
- [x] 여러 장의 로또를 발급할 수 있어야 한다.
- [ ] 당첨 번호와 보너스 번호 입력 받기
- [ ] 당첨 번호와 보너스 번호 예외처리
- [ ] 당첨 통계 정보를 제공
  - [x] 3개 일치 시 5000원
  - [ ] 3개 일치한 로또의 개수
  - [x] 4개 일치 시 50000원
  - [ ] 4개 일치한 로또의 개수
  - [x] 5개 일치 시 1500000원
  - [ ] 5개 일치한 로또의 개수
  - [x] 5개 일치, 보너스 볼 일치 시 30000000원
  - [ ] 5개 일치, 보너스 볼 일치한 로또의 개수
  - [x] 6개 일치 시 2000000000원
  - [ ] 6개 일치한 로또의 개수
  - [ ] 총 수익률 계산
