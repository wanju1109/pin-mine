# 금광 두더지 - Pin Mine

핀을 뽑아 금을 두더지의 수레에 담는 휴대폰용 퍼즐 게임입니다. `index.html` 한 파일(Canvas, 외부 라이브러리 없음)로 동작합니다.

- 조작: 핀 탭(휴대폰) / 숫자키 1~9로 핀 뽑기, R 다시, Enter 확인(PC)
- 규칙: 용암이 수레에 닿으면 실패, 물을 부으면 용암이 돌로 굳고, 금이 용암에 닿으면 재가 됩니다.
- 난이도: 레벨마다 핀·방·용암 수, 목표 금 비율이 늘고, 6레벨부터는 제한 시간이 점점 줄어듭니다. 퍼즐은 매 레벨 자동 생성되며, 풀이가 있는 판만 냅니다.

임베드 예시:

```html
<iframe src="https://wanju1109.github.io/pin-mine/" width="400" height="720" style="border:0;max-width:100%" allow="autoplay"></iframe>
```
