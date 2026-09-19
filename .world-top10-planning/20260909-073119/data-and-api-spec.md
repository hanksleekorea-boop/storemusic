# 데이터·API 명세

- credits_ledger: append-only, 1 credit=1 second, idempotency `{session_id}:{chunk_seq}`.
- neighborhood aggregate: 500m grid cell only; store_id absent; active only after radius 2km/same industry/5 stores/14 days.
- playback watchdog: 60-second RMS sample; RMS ≤ 0.005 is not billable.
- Auth/API/PG endpoints are design contracts only until target-environment evidence exists.

→ 이 명세의 뜻: 개인정보 최소화와 실제 소리 기준 과금을 데이터 모델에 연결한다.
