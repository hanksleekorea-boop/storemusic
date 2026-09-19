# 5단계 상세 개발계획

## 1. 경계·권한
- 입력: Google origin, WeSaver OAuth, PG/DB/R2 접근권.
- 완료 증거: 계정·환경 확인 로그, 비밀값은 기록하지 않음.

## 2. 상용 백엔드
- PostgreSQL 16 ledger/identity, idempotency, credit zones, audit log.
- 완료 증거: migration 실행·rollback 리허설·스키마 검사.

## 3. 재생 클라이언트
- Android Media3, session-independent playback, watchdog/cache, two-button override.
- 완료 증거: 연결된 기기에서 60초 RMS 로그·복구 시나리오.

## 4. 지역 파일럿
- 5개 매장 모집, 2km/동일업종/14일 집계, 완주율 랭킹만 엔진에 입력.
- 완료 증거: 익명 격자 aggregate와 참여 조건.

## 5. 유료 공개·운영
- PG 실거래, 환불 원장, 법률/접근성 검토, alert/runbook, staged rollout.
- 완료 증거: 대상환경·실사용 증거; 날짜는 외부 의존성 해결 후 기입.

→ 이 계획의 뜻: 다섯 증거 단계(작성→로컬→빌드→대상환경→실사용)를 순서대로 올린다.
