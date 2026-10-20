# 공공지원사업 공고 모니터 — 2026-10-21

- started (UTC): 2026-10-20T23:00:40.066089+00:00
- finished (UTC): 2026-10-20T23:04:39.431070+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 8
- UPDATED (processed): 1
- list totals: {'NEW': 8, 'UPDATED': 1, 'UNCHANGED': 291, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 0
- extraction failures: 10

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 1, 'UPDATED': 0, 'UNCHANGED': 99, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 7, 'UPDATED': 1, 'UNCHANGED': 92, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026년 영등포구 소상공인 디지털 전환교육 교육생 모집 새로운게시글 — 마감 2026-10-23
- [kstartup] 충북테크노파크 차세대에너지 스타트업 DEMO DAY 새로운게시글 — 마감 2026-10-21
- [kstartup] 한국기술교육대학교 오픈이노베이션 프로그램 참여기업 모집 안내(엠아이텍 재공고) — 마감 2026-10-21

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
