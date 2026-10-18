# 공공지원사업 공고 모니터 — 2026-10-19

- started (UTC): 2026-10-18T23:01:43.741038+00:00
- finished (UTC): 2026-10-18T23:09:25.629553+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 11
- UPDATED (processed): 30
- list totals: {'NEW': 11, 'UPDATED': 30, 'UNCHANGED': 259, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 5
- extraction failures: 41

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 1, 'UPDATED': 2, 'UNCHANGED': 97, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 10, 'UPDATED': 28, 'UNCHANGED': 62, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026년 하반기 과천시 창업지원센터 스마트오피스 입주기업 모집 공고 새로운게시글 — 마감 2026-10-25
- [kstartup] 2026 충남창업마루나비 하반기 입주기업 모집 공고 새로운게시글 — 마감 2026-10-21
- [kstartup] [소담스퀘어 당산] 온라인 판매를 위한, 디지털 전환 이해 및 판매 채널 분석 — 마감 2026-10-26
- [kstartup] 2026년 나주형 청년 에너지 창업 사관학교(직·주·락·비) 사업 1차 수행기업 모집 — 마감 2026-10-23
- [kstartup] 2026 Invest Seoul Partners Night — 마감 2026-10-19
- [kstartup] 제3회 판다밋업 : Inside Japan 제약·바이오·의료기기 가치사슬 기반 일본 진출 전략 — 마감 2026-10-22
- [kstartup] 2026-9회 충청권 엔젤투자 피칭룸 프로그램 참가기업 모집 — 마감 2026-10-23
- [kstartup] [광운대x동국대x시립대 캠퍼스타운] AI+X Connect Forum — 마감 2026-10-23
- [kstartup] 가죽·패션 제품개발 협업사업 모집 공고 — 마감 2026-10-20
- [kstartup] [중앙사회서비스원] 2026년 제3회 사회서비스 투자교류회 — 마감 2026-10-22
- [kstartup] 마포비즈니스센터 4차 신규입주기업 모집 — 마감 2026-10-22
- [kstartup] 2026 산업단지 오픈이노베이션프로그램 KICXUP 챌린지 & 로컬 스타트업 2차 모집 공고 — 마감 2026-10-23
- [kstartup] 2026 시흥시 청년창업가 네트워킹 행사 참가자 모집 — 마감 2026-10-24
- [kstartup] 바이오/헬스케어 기업들을 위한 「2026 혁신신약살롱 마곡」 참여 안내 — 마감 2026-10-21
- [kstartup] 「2026 슈퍼:콘 엑셀러레이팅」 지원사업 참여기업 모집공고 수정업데이트게시글 — 마감 2026-10-19
- [kstartup] 2026년 광명 글로컬 데모데이 참관객 모집 — 마감 2026-10-26
- [kstartup] 2026년 프로젝트 창업 인큐베이팅 : 2027 모두의 창업 선정 프로젝트 — 마감 2026-10-20
- [kstartup] IR 피칭 청년 창업 오디션 「2026 D-MADE 오디션」 참여기업 모집 (~10. 20. 연장) — 마감 2026-10-20
- [kstartup] 한국기술교육대학교 오픈이노베이션 프로그램 참여기업 모집 안내(엠아이텍 재공고) — 마감 2026-10-21

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
