# 저숙련 AI 실행 핸드북

1. 문서와 run-manifest를 먼저 읽는다.
2. secret을 채팅·로그·Git에 출력하지 않는다.
3. 각 TASK의 precondition을 확인하고 없으면 blocked로 남긴다.
4. 명령을 실제 실행한 경우에만 evidence 경로와 시각을 기록한다.
5. 끝나면 readiness 엔진을 재실행하고 이전 결과를 덮어쓰지 않는다.

→ 이 핸드북의 뜻: 다음 실행자가 안전하게 같은 증거 체계를 반복한다.
