# LED lotto

E포트에 연결된 8개의 led를 0.25초 간격으로 순차적으로 점등시키다가
푸쉬 버튼이 눌린 순간 켜져있는 led의 번호를 fnd에 출력한다.
5개의 번호를 다 맞추면 LCD에 "success"출력, 실패시에는 "fail"출력을 반복한다.



- A 포트 - LCD 데이터 핀
- C 포트 - LCD 제어 핀
- B 포트 - FND 연결 핀
- E 포트 - LED 연결 핀