# 공공지원사업 공고 모니터 — 2026-10-16

- started (UTC): 2026-10-15T23:00:57.423922+00:00
- finished (UTC): 2026-10-15T23:07:35.077518+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 11
- UPDATED (processed): 20
- list totals: {'NEW': 11, 'UPDATED': 20, 'UNCHANGED': 269, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 2
- extraction failures: 30

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 0, 'UPDATED': 2, 'UNCHANGED': 98, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 11, 'UPDATED': 18, 'UNCHANGED': 71, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026 Invest Seoul Partners Night 새로운게시글 — 마감 2026-10-19
- [kstartup] 제3회 판다밋업 : Inside Japan 제약·바이오·의료기기 가치사슬 기반 일본 진출 전략 새로운게시글 — 마감 2026-10-22
- [kstartup] 2026-9회 충청권 엔젤투자 피칭룸 프로그램 참가기업 모집 새로운게시글 — 마감 2026-10-23
- [kstartup] [광운대캠퍼스타운] AI+X Connect Forum 새로운게시글 — 마감 2026-10-23
- [kstartup] 성남 기후테크 UpSkill 아카데미 Vol.3 - 투자유치를 위한 IR 전략 새로운게시글 — 마감 2026-10-16
- [kstartup] 가죽·패션 제품개발 협업사업 모집 공고 새로운게시글 — 마감 2026-10-20
- [kstartup] [제주창조경제혁신센터]「상시매칭 오픈이노베이션 플랫폼」'에코프로 계열사''수요과제 매칭 스타트업 모집 (~10/16) 새로운게시글 — 마감 2026-10-16
- [kstartup] [대전창조경제혁신센터] 2026 대전 제조파트너스 매칭데이 참가자 모집 — 마감 2026-10-20
- [kstartup] 2027년 K-water 해외시장개척단 참여기업 모집 공고 — 마감 2026-10-23
- [kstartup] 2026년 초기창업패키지 로켓십 IR 경진대회 참가기업 모집 (3회차: 기후·ESG) — 마감 2026-10-23
- [kstartup] [강동구 청년해냄센터] 2026 모의창업스쿨 2차 교육 참가자 모집 공고 — 마감 2026-10-22
- [kstartup] 구로구 청년창업지원센터 일반 창업교육(하반기: 5회차): 투자를 위한 비즈니스 모델 수립 전략 — 마감 2026-10-21
- [kstartup] 2026년 서울 라이프스타일 거점(일본) 진출사업 참여기업 모집 — 마감 2026-10-16
- [kstartup] 2026 오세아니아 전략시장 진출 사업 참여기업 모집 — 마감 2026-10-16
- [kstartup] ETRI 기술활용 신사업 모델 공모전 — 마감 2026-10-16

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
