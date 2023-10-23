# Amazon Lex ChatBot을 Facebook 메신저와 통합
이 프로젝트에서는 Amazon Lex ChatBot을 Facebook Messenger와 통합하여 사용자를 위한 대화형 채팅 환경을 만듭니다.

### 1단계: Amazon Lex ChatBot 생성
- AWS Management Console에 로그인하고 Amazon Lex 콘솔을 선택
- "만들기"를 클릭하고 봇 이름, 출력 음성 및 세션 시간 초과를 정의
- 의도, 슬롯 및 샘플 발화를 생성하여 봇이 사용자와 상호 작용하는 방식을 정의
- Lex 콘솔 내에서 봇을 구축하고 테스트

![image](https://github.com/plintAn/AWS_Chatbot_Facebook/assets/124107186/47ac8ae2-000c-45f1-bc2e-c1c0a382cb2f)

Chatbot 구축 - 배포 - 테스트

![AWS_Chatbot3](https://github.com/plintAn/AWS_Chatbot_Facebook/assets/124107186/834f21da-0483-4770-a7d3-3136dc10fce4)


### 2단계: Facebook 메신저 설정
- Facebook 개발자 포털을 사용하여 Facebook 페이지와 앱을 만들기
- 인증을 위한 페이지 액세스 토큰을 생성
- Facebook 사용자로부터 메시지를 수신하려면 웹훅을 설정
- 메시징을 활성화하려면 페이지에 앱을 구독

![AWS_Chatbot5](https://github.com/plintAn/AWS_Chatbot_Facebook/assets/124107186/20c8dda9-2103-4e23-9b98-0433edba4181)

### 3단계: Amazon Lex를 Facebook Messenger와 통합
- Amazon Lex 콘솔에서 봇을 선택하고 "채널"을 선택
- 'Facebook'을 클릭하고 페이지 액세스 토큰, 앱 비밀 키 등 필수 정보를 입력
- 인증 토큰을 제공하고 콜백 URL을 복사
- 콜백 URL을 Facebook 개발자 포털에 붙여넣어 Lex 봇을 Facebook Messenger와 연결
- 페이스북 페이지 메시지 활성화 등 필요한 권한과 설정을 구성

![AWS_Chatbot4](https://github.com/plintAn/AWS_Chatbot_Facebook/assets/124107186/24d09a2f-857d-4436-bd66-e0f2c66ec310)

### 4단계: ChatBot 테스트 및 배포
- 메시지를 보내고 응답을 확인하여 Facebook 메신저 내에서 챗봇을 테스트
- Lex 콘솔에서 로그와 지표를 검토하여 문제나 개선이 필요한 영역을 식별
- Facebook의 검토 및 승인 프로세스에 따라 Facebook 사용자가 사용할 수 있도록 봇을 배포

Output

![AWS_Chatbot_final](https://github.com/plintAn/AWS_Chatbot_Facebook/assets/124107186/900f1867-c3d0-4bd4-8256-647213b1f39f)



배운점

Amazon Lex ChatBot을 Facebook Messenger와 통합하여 반응형 대화 인터페이스를 생성했습니다.


