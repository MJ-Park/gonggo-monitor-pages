# 공공지원사업 공고 모니터 — 2026-10-15

- started (UTC): 2026-10-14T23:02:37.296460+00:00
- finished (UTC): 2026-10-14T23:07:26.466989+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 14
- UPDATED (processed): 1
- list totals: {'NEW': 14, 'UPDATED': 1, 'UNCHANGED': 285, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 0
- extraction failures: 14

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 3, 'UPDATED': 0, 'UNCHANGED': 97, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 11, 'UPDATED': 1, 'UNCHANGED': 88, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] [중앙사회서비스원] 2026년 제3회 사회서비스 투자교류회 새로운게시글 — 마감 2026-10-22
- [kstartup] 마포비즈니스센터 4차 신규입주기업 모집 새로운게시글 — 마감 2026-10-22
- [kstartup] 바이오/헬스케어 기업들을 위한 「2026 혁신신약살롱 마곡」 참여 안내 새로운게시글 — 마감 2026-10-21
- [kstartup] (Plug in: Tokyo) 일본 도쿄 Startup JAPAN expo 2026 참여 스타트업 모집(~10/15) — 마감 2026-10-15

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
