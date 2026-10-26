# 약국 한영 통역

부산 세미나 참석 약사님을 위한 배포 후보 0.4.0-rc.1입니다. Windows 설치와 실제 음성 테스트가 끝나기 전에는 검증 완료 배포본으로 전달하지 마세요.

## 무엇을 하나요

손님이 영어로 말합니다 → 한국어 통역을 듣습니다 → 약사가 한국어로 답합니다 → 영어 통역을 듣습니다.

노트북 한 대로 한 문장씩 번갈아 말합니다. 시작 문장은 **약국 통역 시작해 줘**입니다. 잘 안 들린 말은 말한 사람의 언어로 다시 묻습니다.

## 설치 준비

**[설치 ZIP 바로 받기](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.1/pharmacy-install.zip)**

**[PDF 가이드](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.1/pharmacy-guide-ko-v3.pdf)** · **[HWPX 정본](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.1/pharmacy-guide-ko-v3.hwpx)** · **[Word 파생본](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.1/pharmacy-guide-ko-v3.docx)**

쉬운 설치는 제공된 `pharmacy-install.zip`을 그대로 업로드하는 방법입니다. 압축을 풀지 마세요. 한글 화면에서 **플러그인 → 추가 → 플러그인 압축 파일 업로드 → 파일 선택 → 플러그인 추가 → 플러그인 설치** 순서로 진행합니다. 이 경로로 제작자 계정의 Aside 브라우저에서 업로드와 설치 완료를 확인했습니다. Windows 앱과 실제 음성 왕복은 별도 확인이 필요합니다.

Git 저장소는 배포 파일과 소스를 관리하는 곳입니다. 저장소 링크를 열었다고 ChatGPT에 자동 설치되는 것은 아닙니다. 위의 ZIP 바로 받기 링크를 눌러 저장한 뒤 설치하세요. 공개 저장소이므로 다운로드에 GitHub 계정이나 초대가 필요하지 않습니다.

Python, Node, Git, API 키, 별도 서버는 이 패키지의 실행 의존성이 아닙니다. Git 명령어는 약사님께 요구하지 않습니다. 앱 설치는 공식 공급자의 다운로드 경로를 사용하세요. 이 저장소의 marketplace는 Codex 프로젝트에서 사용할 수 있는 대체 배포 구성입니다.

데스크톱 앱에 **마켓플레이스 추가** 메뉴가 있으면 출처에 `https://github.com/HosungYou/busan-pharmacy-interpreter`, Git ref에 `main`을 입력하고 Sparse 경로를 비워 목록을 추가할 수도 있습니다. 새 목록에서 약국 한영 통역을 찾아 설치합니다. 이 대체 경로의 Windows 설치는 아직 미검증입니다.

## 이전 버전과 달라진 점

기존 0.3.1에서 역할과 번역 방향을 지키는 규칙을 가져왔습니다. 첫 실습에서 사용하지 않는 MCP 서버와 식약처 조회를 제외했습니다. 별도 대화 파일을 쓰는 코드도 포함하지 않았습니다. 기존 설치나 기록은 변경하지 않았습니다. 식약처 조회는 별도 실습에서 인증과 실제 조회를 확인한 뒤 추가합니다.

## 개인정보와 문의

플러그인은 별도 파일 저장을 하지 않습니다. 앱 채팅 기록은 남을 수 있습니다. 실습에는 가상 사례만 사용하세요.

문의: hs.you@enactionlabs.com. 환자 대화·이름·연락처·건강 정보는 보내지 마세요. 개인정보를 가린 오류 부분만 보내 주세요.

## 제작자 확인 사항

2026년 10월 26일 Aside에서 한글 UI, 업로드·설치, 시작 문장, 텍스트 한영 왕복, 음성 화면 진입·종료, 삭제 메뉴 위치를 확인했습니다. 음성 모드에 입력한 가상 영어 문장은 한국어로 통역됐지만 전사에 원문에 없는 `One moment`가 붙었습니다. 실제 마이크 인식과 소리의 정확성, Windows 설치, 되묻기는 확인하지 않았습니다. 현재는 시험 버전이며 현장용 검증 완료판이 아닙니다.

Windows 새 계정에서 설치, 플러그인 선택, 음성 시작, 한영 왕복 통역, 되묻기를 확인해야 합니다. Mac 공통 UI 캡처는 Windows 실행 증거로 사용하지 않습니다. 다른 언어는 변경 후 해당 언어 사용자와 실제 음성 테스트가 필요합니다.

형식 근거: https://developers.openai.com/plugins/build/plugins
