# Sources

- [Amazon Web Services: Evaluating AI Agents: A production blueprint with Strands and AgentCore](https://aws.amazon.com/blogs/machine-learning/evaluating-ai-agents-a-production-blueprint-with-strands-and-agentcore/)
  - 유형: technical_blog
  - 확인: AWS와 Motorway가 공동 작성한 공식 기술 글에서 AI 재고 검색 에이전트의 오답이 질의 8건 중 1건에서 50건 중 1건으로 감소하고 문제 탐지 시간이 몇 시간에서 몇 분으로 줄었다는 결과를 확인했습니다. 개발·운영 2단계 평가, 세 층의 품질 기준, 배포 차단 게이트, 실제 트래픽 표본 평가, 20~50개 초기 테스트 권고를 원문 범위 안에서 사용했습니다.
  - 사용 범위: 공식 AWS 글의 텍스트 사실, 공식 표지 이미지, Figure 2 평가 프레임워크를 사용합니다. 고객 사례 수치는 AWS와 Motorway의 공동 발표로 표시하며 보편 성과로 확장하지 않습니다.
- [Amazon Web Services: Evaluation types - Amazon Bedrock AgentCore](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/evaluations-types.html)
  - 유형: official_documentation
  - 확인: 공식 개발자 문서에서 AgentCore Evaluations가 온라인, 온디맨드, 배치 평가를 제공하며 온라인 평가는 운영 트래픽을 표본화해 지속적으로 품질을 측정하고, 배치 평가는 여러 세션의 회귀 검사와 변경 전후 비교에 쓰인다는 점을 확인했습니다.
  - 사용 범위: 문서의 기능 설명만 사용했습니다. publishedAt은 조회 시 확인한 공식 문서 HTTP Last-Modified 값입니다.

생성 방식: chatgpt_codex
OpenAI Platform API 호출: 0
