# 첫 작업 워크스루

1. 사장님이 WeSaver OAuth origin 승인과 secret 주입을 확인한다.
2. AI가 secret 없이 Cloudflare Worker 환경 점검과 PostgreSQL migration dry-run을 실행한다.
3. 실제 billing key로 sandbox 거래 1건과 idempotency 재시도 1건을 기록한다.
4. 연결된 Android 기기에서 APK를 설치하고 60초 RMS watchdog을 관찰한다.
5. 결과를 다시 readiness 입력에 반영한다.

현재 1번과 3번과 4번은 사장님/외부 환경이 없으면 시작할 수 없다.

→ 이 워크스루의 뜻: 다음 실행자가 첫 세션에서 무엇을 확인해야 하는지 한 줄씩 안내한다.
