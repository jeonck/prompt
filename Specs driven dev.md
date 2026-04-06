쓰는 방법은 간단해요.

설치 한 줄.
`npx skills add addyosmani/agent-skills`

Claude Code에서는:
`claude plugin add agent-skills`

설치하면 슬래시 커맨드 7개가 생겨요.
`/spec` — 스펙 먼저 쓰기.
`/plan` — 태스크 분해.
`/build` — 점진적 구현.
`/test` — TDD 워크플로.
`/review` — 코드 리뷰.
`/code-simplify` — 코드 단순화.
`/ship` — 배포 전 체크리스트.

에이전트 페르소나도 3개 있습니다.
code-reviewer, test-engineer, security-auditor.
각각 코드 리뷰, 테스트 전략, 보안 점검에 특화돼 있어요.￼


→ GitHub: https://github.com/addyosmani/agent-skills
→ Beyond Vibe Coding: https://beyond.addy.ie
→ Addy Osmani: https://addyosmani.com￼


이 중에서 눈여겨볼 스킬을 뽑아보면요.

spec-driven-development.

에이전트한테 "인증 시스템 만들어줘"라고 하면
알아서 뭔가 만들긴 해요.
근데 빠진 게 많습니다.

이 스킬은 코드 한 줄 쓰기 전에 명세서를 먼저 작성하게 강제해요.

Specify → Plan → Tasks → Implement.
각 단계를 통과해야 다음으로 넘어갑니다.

Osmani가 강조한 부분이 있어요.
"당신의 전문 지식이 그 어느 때보다 중요하다.
데이터베이스 테이블 간의 관계,
서드파티 라이브러리의 함정,
시니어 엔지니어 머릿속에만 있는 비즈니스 규칙.
이런 건 훈련 데이터에 없다.
스펙에 직접 넣어야 한다."￼


되짚어봅니다.

Osmani가 이런 말을 했어요.
"소프트웨어 엔지니어링은 더 이상 코드를 쓰는 것이 아니다.
소프트웨어를 만드는 팩토리를 만드는 것이다."

agent-skills가 하는 일이 그거예요.
에이전트한테 코드를 짜게 하는 게 아니라,
코드를 올바르게 짜는 프로세스를 심는 것.

에이전트가 아무리 똑똑해져도
스펙 없이 코딩하고, 테스트 없이 머지하고, 리뷰 없이 배포하면
결과물은 불안정합니다.

도구가 아니라 습관이 품질을 결정해요.￼
