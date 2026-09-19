# 5단계 의존 그래프

STAGE-1-BASELINE → STAGE-2-FOUNDATION → STAGE-3-CORE → STAGE-4-QUALITY → STAGE-5-RELEASE

각 단계 내부는 TASK 순서대로 수행한다. Google/DB/PG/Android가 필요한 작업은 DISCOVERY 또는 BLOCKED_BY_DECISION으로 멈추고 이전 단계 증거를 보존한다.

→ 이 그래프의 뜻: 단계 건너뛰기와 “1~2단계” 같은 모호한 배치를 막는다.
