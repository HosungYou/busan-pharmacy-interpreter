# 약국 한영 음성 통역 실습

부산 세미나 참석 약사님을 위한 시작문 준비 플러그인 0.4.0-rc.3과 쉬운 설명서입니다.

## 다운로드

- [설치 ZIP](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.3/pharmacy-install.zip)
- [PDF 가이드](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.3/pharmacy-guide-ko-v6.pdf)
- [HWPX 정본](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.3/pharmacy-guide-ko-v6.hwpx)
- [편집용 Word](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.3/pharmacy-guide-ko-v6.docx)
- [일반 Chat용 시작문](https://github.com/HosungYou/busan-pharmacy-interpreter/releases/download/v0.4.0-rc.3/voice-start-ko-en.txt)

공개 파일이므로 GitHub 계정이나 초대가 필요 없습니다. 설치 ZIP은 압축을 풀지 마세요.

## 사용 장소와 설치 메뉴

실제 통역은 일반 ChatGPT의 Chat 음성 대화에서 합니다. Work나 Codex 실행은 필요 없습니다. 플러그인은 시작문 준비 도우미입니다. 설치 메뉴가 없으면 위의 일반 Chat용 시작문을 복사해 새 채팅에 보내세요. ZIP을 대화에 첨부하는 것은 설치가 아닙니다. 메뉴와 음성 기능은 계정·앱·요금제·조직 설정에 따라 다릅니다. Codex는 직접 만들기 추가 실습에서 사용합니다.

## 시작하기

1. ChatGPT의 플러그인 → 추가 → 플러그인 압축 파일 업로드에서 ZIP을 고릅니다.
2. 플러그인 추가 → 플러그인 설치를 누릅니다.
3. 채팅에서 사용해 보기를 누르고 “약국 통역 시작해 줘”라고 요청합니다.
4. 받은 시작문을 새 일반 Chat에 한 번 복사해 보냅니다. 이 채팅에는 플러그인을 다시 선택하지 않습니다.
5. Ready가 나오면 파형 모양의 **실시간 음성 대화** 버튼을 누릅니다. 옆의 마이크 모양은 받아쓰기입니다.
6. 손님이 영어로 말하면 한국어 음성으로 듣고, 약사가 한국어로 답하면 영어 음성으로 전달합니다. 한 문장씩 번갈아 말하고 통역이 끝날 때까지 기다립니다.

복사·전송은 준비 단계에서만 합니다. 실제 통역 중에는 전송 버튼을 누르지 않습니다. Python·Git·명령어·API 키·별도 서버는 필요하지 않습니다.

## 확인한 범위

설명서의 대화 캡처는 가상 문장을 한 줄씩 텍스트로 재현한 연습입니다. 실제 번역 음성 출력·연속 음성 성공·첫 소리 지연을 검증했다는 뜻은 아닙니다. Windows 앱 설치도 미검증입니다. 실제 2인 시험을 문서 배포 조건으로 요구하지 않습니다.

rc.1·rc.2의 Work 통역에서는 2분 이상 지연과 대기 발화가 재현됐습니다. 이 버전은 플러그인을 시작문 준비에만 쓰고 실제 통역은 일반 Chat의 실시간 음성에서 수행하도록 안내합니다. 1~2초 시작·최대 3초는 목표이며 보장하지 않습니다.

## 다른 환경과 다음 실습

마켓플레이스 추가 메뉴가 있는 데스크톱 앱에서는 출처에 이 저장소 주소, Git ref에 main을 입력하고 Sparse 경로는 비웁니다. 이번 플러그인의 Windows 마켓플레이스 설치는 별도 확인이 필요합니다.

베트남어 변경은 직접 만들기 실습의 확장 예제이며 실제 음성 시험이 필요합니다. 식약처 제품 조회는 별도 실습에서 연결합니다. 제품 정보로 약국 재고를 추측하지 않습니다.

## 개인정보와 문의

플러그인은 별도 대화 파일을 자동 저장하지 않습니다. 앱 자체의 채팅 기록은 남을 수 있습니다.

문의: hs.you@enactionlabs.com. 환자 대화·이름·연락처·건강 정보는 보내지 마세요. 개인정보를 가린 오류 부분만 보내 주세요.

[공식 플러그인 형식 안내](https://developers.openai.com/plugins/build/plugins)
