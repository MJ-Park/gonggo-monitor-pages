# 공공지원사업 공고 모니터 — 2026-11-06

- started (UTC): 2026-11-06T02:33:28.218655+00:00
- finished (UTC): 2026-11-06T02:33:44.757086+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 0
- UPDATED (processed): 0
- list totals: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1}
- process failures (notice-level): 0
- conflicts (analysis): 0
- extraction failures: 0

## 소스별 성공/실패

- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- (없음)

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
