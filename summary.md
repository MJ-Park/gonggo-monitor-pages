# 공공지원사업 공고 모니터 — 2026-10-22

- started (UTC): 2026-10-21T23:00:23.812159+00:00
- finished (UTC): 2026-10-21T23:05:35.757364+00:00
- baseline: False
- dry_run: True

## 요약

- NEW (processed): 19
- UPDATED (processed): 2
- list totals: {'NEW': 19, 'UPDATED': 2, 'UNCHANGED': 279, 'FAILED': 2}
- process failures (notice-level): 0
- conflicts (analysis): 2
- extraction failures: 15

## 소스별 성공/실패

- **bizinfo** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)
- **iris** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **kstartup** [OK]: {'NEW': 19, 'UPDATED': 2, 'UNCHANGED': 79, 'FAILED': 0}
- **ntis** [OK]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 100, 'FAILED': 0}
- **smtech** [FAIL]: {'NEW': 0, 'UPDATED': 0, 'UNCHANGED': 0, 'FAILED': 1} — request failed: [SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1029)

## 마감 7일 이내

- [kstartup] 2026 문화예술 창업교육의 모든 것.zip 2기 참여자 모집 새로운게시글 — 마감 2026-10-27
- [kstartup] 2026 초격차 클리마 데이 (Clima Day) 행사 개최 안내 새로운게시글 — 마감 2026-10-28
- [kstartup] TIPS · LIPS를 준비하는 스타트업을 위한 IR 전략 - 제10차 DDM 벤처스타트업 아카데미 새로운게시글 — 마감 2026-10-29
- [kstartup] 2026 관광기업 동반성장 기술역량 강화교육 새로운게시글 — 마감 2026-10-27
- [kstartup] COMEUP 2026 사전 오프라인 행사 '스타트업 커리어 TALK' 새로운게시글 — 마감 2026-10-28
- [kstartup] 2026년도 투자기업 발굴 플랫폼 빅웨이브(BiiG WAVE) IR사업 3회차 초격차 분야 IR 참여기업 모집공고 새로운게시글 — 마감 2026-10-29
- [kstartup] 기업 판로 지원 프로그램 수혜기업 모집(~10/29) 새로운게시글 — 마감 2026-10-29
- [kstartup] 「2026 기업지원실 운영」 지역 환경기업 육성 프로그램 참여기업 수정 모집공고 새로운게시글 — 마감 2026-10-26
- [kstartup] [2026 에코스타트업 Green IR DAY] 참관 신청 새로운게시글 — 마감 2026-10-25
- [kstartup] 제3회 판다밋업 : Inside Japan 제약·바이오·의료기기 가치사슬 기반 일본 진출 전략 — 마감 2026-10-22
- [kstartup] [중앙사회서비스원] 2026년 제3회 사회서비스 투자교류회 — 마감 2026-10-22

## Delivery notes

- Artifacts on disk only (no Telegram / no Grok Bot chat notify in this phase).
- Agent handoff: see `agent_handoff.json` and `docs/AGENT_DELIVERY.md`.
- Parent agent: re-analyze evidence at delivery, post `summary.md` + attach `index.html`/`index.csv`.
- Do not create Bot routines or enable schedule without user approval.
