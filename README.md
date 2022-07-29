# android-app-dev-checklist

완벽한 앱을 위한 체크리스트

참고 자료: [pluu님의 코드 품질 1% 올리기](https://speakerdeck.com/pluu/kodeu-pumjil-1-percent-olrigi?slide=53) + 성빈의 주관적인 생각

---

1. 깃 커밋 단위 및 메시지
2. 코드 포멧팅 (린트 적극 사용)
3. 인터넷 연결 없을 때
4. Configuration changes
5. 코드 복잡성 (가독성)
6. 부수 효과 관리
7. 한 이벤트가 매우 짧은 시간에 반복적으로 발생할 때 (swipe-to-refresh 같은 경우 매우 짧은 시간에 여러번 발생할 수 있음)
8. 앱이 백그라운드로 갔다가 포그라운드로 돌아왔을 때 기존 작업 유지 여부 (ex_파일 다운로드 작업은 유지되야 함)
