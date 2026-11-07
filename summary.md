# 공공지원사업 공고 모니터 — 2026-11-07

- started (UTC): 2026-11-07T02:14:29.686999+00:00
- finished (UTC): 2026-11-07T02:19:39.379679+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 8
- UPDATED (processed): 5
- list totals: {'NEW': 8, 'UPDATED': 5, 'UNCHANGED': 287, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 1
- extraction failures: 21

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 8, 'UPDATED': 5, 'UNCHANGED': 87, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] [벤처기업협회] 2026년 예비창업패키지 특화분야(소셜벤처)「임팩트스타 IR 데모데이」개최 (11/10) 새로운게시글 — 마감 2026-11-09
- [kstartup] 2026년 스타트업 법률지원사업 전남광주통합특별시 법률상담회 참여기업 모집 — 마감 2026-11-09

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
