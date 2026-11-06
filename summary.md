# 공공지원사업 공고 모니터 — 2026-11-06

- started (UTC): 2026-11-06T02:27:28.973737+00:00
- finished (UTC): 2026-11-06T02:33:07.109799+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 22
- UPDATED (processed): 10
- list totals: {'NEW': 22, 'UPDATED': 10, 'UNCHANGED': 268, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 1
- extraction failures: 21

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 13, 'UPDATED': 0, 'UNCHANGED': 87, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 9, 'UPDATED': 10, 'UNCHANGED': 81, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [iris] test — 마감 2026-11-11
- [kstartup] 2026년 웰컴 투 팁스 7차 참가기업 모집 (제주권) 연장 공고 — 마감 2026-11-06
- [kstartup] 2026 별별상상 스타트업 챌린지 — 마감 2026-11-08
- [kstartup] 2026년 대전 테스트베드 연계사업 공모 — 마감 2026-11-11
- [kstartup] [로컬창업트랙 2기]기억되는 브랜드가 되는 법 — 마감 2026-11-12
- [kstartup] 2026년 위치정보 보호조치 교육 (7차) — 마감 2026-11-11
- [kstartup] 2026년 5차 국립공주대학교 창업보육센터 입주기업 모집 연장공고 — 마감 2026-11-13
- [kstartup] 2026년 중동 상황 대응 규격 컨설팅 지원사업「수혜기업 모집」 새로운게시글 — 마감 2026-11-09
- [kstartup] 2026 아산 스타트업 Scale-UP 프로그램 참여기업 모집 새로운게시글 — 마감 2026-11-13
- [kstartup] 2026 아산 투자유치 Build-Up 프로그램 참여기업 모집 새로운게시글 — 마감 2026-11-13

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
