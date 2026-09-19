# 5단계 위험·되돌리기 레지스터

- 인증/권한: Google origin·secret 없으면 BLOCKED_EXTERNAL; 기존 정적판 유지.
- 결제: PG key·sandbox 증거 없으면 결제 성공 표시 금지; 원장 변경 금지.
- 데이터 이사: PostgreSQL 16 실제 endpoint 없으면 dry-run만; rollback 로그 보존.
- 재생: Android·live audio 없으면 APK 존재를 재생 완료로 표시하지 않음.
- 공개: 모든 단계 종료 전 Cloudflare 공개판 변경 금지.

→ 이 레지스터의 뜻: 실패 시 무엇을 되돌리고 무엇을 보존할지 먼저 정한다.
