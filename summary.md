# 공공지원사업 공고 모니터 — 2026-10-23

- started (UTC): 2026-10-22T23:05:09.519858+00:00
- finished (UTC): 2026-10-22T23:09:49.698769+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 10
- UPDATED (processed): 3
- list totals: {'NEW': 10, 'UPDATED': 3, 'UNCHANGED': 287, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 2
- extraction failures: 9

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 1, 'UPDATED': 0, 'UNCHANGED': 99, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 9, 'UPDATED': 3, 'UNCHANGED': 88, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026 FAST TRACK 농식품 데모데이 새로운게시글 — 마감 2026-10-30
- [kstartup] [강원ICT융합연구원] 강원 미래산업 AX혁신과 지산학연 신사업 발굴 포럼 새로운게시글 — 마감 2026-10-27
- [kstartup] 2026년 나주형 청년 에너지 창업 사관학교(직·주·락·비) 사업 1차 수행기업 모집 — 마감 2026-10-23
- [kstartup] 2026 산업단지 오픈이노베이션프로그램 KICXUP 챌린지 & 로컬 스타트업 2차 모집 공고 — 마감 2026-10-26
- [kstartup] 2026년 초기창업패키지 로켓십 IR 경진대회 참가기업 모집 (3회차: 기후·ESG) — 마감 2026-10-23

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
