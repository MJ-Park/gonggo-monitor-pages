# 공공지원사업 공고 모니터 — 2026-10-20

- started (UTC): 2026-10-19T23:03:33.396922+00:00
- finished (UTC): 2026-10-19T23:08:28.509998+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 1
- UPDATED (processed): 20
- list totals: {'NEW': 1, 'UPDATED': 20, 'UNCHANGED': 279, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 3
- extraction failures: 11

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 0, 'UPDATED': 2, 'UNCHANGED': 98, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 1, 'UPDATED': 13, 'UNCHANGED': 86, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 5, 'UNCHANGED': 95, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026년 하반기 과천시 창업지원센터 스마트오피스 입주기업 모집 공고 — 마감 2026-10-25
- [kstartup] 2026 충남창업마루나비 하반기 입주기업 모집 공고 — 마감 2026-10-21
- [kstartup] 가죽·패션 제품개발 협업사업 모집 공고 — 마감 2026-10-20
- [kstartup] 2026년 웰컴 투 팁스 5차 참가기업 모집 (호남권) — 마감 2026-10-20
- [kstartup] 2026년 웰컴 투 팁스 6차 참가기업 모집 (전북권) — 마감 2026-10-20
- [kstartup] 2026 생물자원 활용 창업벤처 지원을 위한 기업 간담회 (3회차) 참여기업 모집 — 마감 2026-10-20
- [iris] 2026년 연구산업육성사업(투자연계형 연구산업 혁신기술 개발) 본과제 신청 공고 — 마감 2026-10-20
- [iris] 2026년도 우주기술혁신인재양성(R&D)사업[우주항공 글로벌 인력양성 및 활용] 2차 추가공고 — 마감 2026-10-20
- [ntis] 2026년도 우주기술혁신인재양성(RD)사업[우주항공 글로벌 인력양성 및 활용] 2차 추가공고 — 마감 2026-10-20

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
