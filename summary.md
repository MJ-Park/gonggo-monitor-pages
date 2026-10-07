# 공공지원사업 공고 모니터 — 2026-10-08

- started (UTC): 2026-10-07T23:02:10.536067+00:00
- finished (UTC): 2026-10-07T23:06:06.797841+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 4
- UPDATED (processed): 2
- list totals: {'NEW': 4, 'UPDATED': 2, 'UNCHANGED': 294, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 0
- extraction failures: 5

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 1, 'UPDATED': 0, 'UNCHANGED': 99, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 3, 'UPDATED': 2, 'UNCHANGED': 95, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026년 한수원 우문현답 현장 클리닉센터 지원사업 「원전·에너지 분야 선택형 과제」참여기업 모집 공고 — 마감 2026-10-08
- [kstartup] 2026 제10회 G밸리창업경진대회 참가기업 모집 — 마감 2026-10-08
- [iris] 2026년 팁스(TIPS) 창업기업 지원계획 수정 공고(일반트랙) — 마감 2026-10-14

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
