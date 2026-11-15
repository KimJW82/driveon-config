# driveon-config

드라이브온(com.jw.driveon) 앱이 읽는 원격 스위치 설정입니다. 개인정보는 없습니다.

| 키 | 뜻 |
|---|---|
| routeOff | 목적지 링크를 잠시 끌 네비 패키지 목록 (예: `["com.nhn.android.nmap"]`) |
| closeCardsOff | true면 '켰던 앱만 끄기' 대신 홈+백그라운드 종료 |
| quickPickOff | true면 목적지 빠른 선택 카드 끔 |
| parkingOff | true면 주차 위치 저장 끔 |
| adsOff | true면 광고 끔 |
| notice | 앱 메인에 띄울 공지 (빈 문자열이면 없음) |

네비 업데이트로 문제가 생기면 여기 값만 바꿔 커밋하면 앱이 다음 하차 때 반영합니다.
