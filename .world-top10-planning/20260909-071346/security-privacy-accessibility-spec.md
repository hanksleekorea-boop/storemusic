# 보안·개인정보·접근성 명세

- OAuth: WeSaver client, origin allow-list and session secret required; public client secret exposure prohibited.
- Location: transmit only 500m grid cell; no store_id in neighborhood schema; never show a neighboring store’s current track.
- Accessibility: keyboard focus, labels, contrast, screen reader and Korean web accessibility checks remain release gates; no external audit evidence yet.

→ 이 명세의 뜻: 설계 원칙과 실제 감사 증거를 구분한다.
