Codex vs Claude Code
# 강의 개요 및 목표

클로드코드 만든사람도 직접 코딩하지않고 있음(여러개의 클로드창을 띄워서 일시키고 실수는 계속 학습기록시켜서 고도화함)

Agent.md는 매작업마다 참조하는 프로젝트 상시 메모리 파일

- agent가 항상 기억해야하는 공통 규칙을 담는것
- 엔터 칠때마다 context에 포함되어 토큰을 사용하게됨
- context는 강제사항이 아니라서, 강하게 참조하는 정도라 반드시 지켜지는지는 확신할수없음
- 

**일 시키는법**

1. Exolore 탐색
2. Plan  - 구현직전에 계획을 우선 수립한다. 요구사항 수정 범위 지정
3. Code - 작은단위별로 계획 범위안에서 수정진행
4. Test - 단위 테스트, 통합 테스트
5. Commit - 검증 및 테스트 통과 후 커밋

Agent구성은 

1.Command

자주사용하는 프롬프트 작업을 단축명령처럼 재사용하는 시스템

1.무엇을 알고있냐 claude.md agent.md

2.무엇을 어떻게 할 수 있는가? seetings.json, config.toml 

3.어떤 작업을 갖고있는가 ? 대화 컨텍스트

새로 시작할때는 /clear

/compact  - 답변이 길어질때도 유의미

대화가 이어지긴한데 그대로 사용하기보다, summarize conversation.

복잡한설계.리팩토링 →고급모델

단순코딩 디버깅 →일반 모델 , 소넷정도

클로드

/context 명령어, 얼마나 context가 많이 잡아먹고있는지 확인 할 수있다.

/statusline dir, git-branch, model, effort, remain token

/effort 하면 잘안쓰는 화려한

안드레아 카파시 Agent.md

강의 개요 및 목표 (1)
