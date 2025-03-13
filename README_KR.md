# RolittHub - AI 스마트 하드웨어 로봇 <img src="assets/icons/robot.svg" width="32" height="32" alt="로봇 아이콘" style="vertical-align: middle">

RolittHub는 ARM 플랫폼 기반의 오픈소스 AI 챗봇 프로젝트로, Python을 주요 개발 언어로 사용합니다. 이 프로젝트는 지능형 하드웨어 기능과 AI 챗봇 기능을 결합하여 대화형 다기능 로봇 플랫폼을 구현합니다. 자세한 내용은 당사 웹사이트 [www.rolitt.com](https://www.rolitt.com)을 방문해 주세요! 🌟

## 주요 기능 <img src="assets/icons/features.svg" width="24" height="24" alt="기능 아이콘" style="vertical-align: middle">

### 오디오 처리 🎤
- 실시간 음성 인식 및 처리
- 다국어 음성 인식 ✨
- 노이즈 제거 및 에코 제거 🔇
- 사용자 정의 웨이크 워드 감지 🗣️

### 디스플레이 드라이버 🖥️
- 다양한 디스플레이 유형 지원 (LCD, OLED 등)
- 동적 UI 렌더링 🎨
- 다국어 문자 표시 🌐
- 사용자 정의 애니메이션 지원 ✨

### LED 제어 💡
- RGB LED 상태 표시
- 프로그래밍 가능한 조명 패턴 🌈
- 대화형 조명 피드백 ⚡
- 전력 효율적인 LED 관리 🔋

### IoT 기능 🌐
- Wi-Fi 및 블루투스 연결 📡
- 클라우드 서비스 통합 ☁️
- 원격 장치 관리 🔄
- 실시간 데이터 동기화 📊

### OTA 업데이트 🚀
- 안전한 무선 펌웨어 업데이트 🔒
- 자동 업데이트 확인 ⚡
- 롤백 보호 🛡️
- 업데이트 진행 상황 모니터링 📈

## 지원 하드웨어
- 다양한 ARM 개발 보드
- Ubuntu 시스템 중심 지원
- 권장 사양:
  - ARM 프로세서
  - 최소 1GB RAM
  - Wi-Fi/블루투스 기능
  - 오디오 입출력 지원

## 시스템 요구사항
- Ubuntu (권장)
- Python 3.7 이상
- 필요한 Python 패키지 (requirements.txt 참조)

## 설치 방법

1. 저장소 복제:
```bash
git clone https://github.com/RolittAI/RolittHub.git
cd RolittHub
```

2. 의존성 설치:
```bash
pip install -r requirements.txt
```

3. config.yaml에서 하드웨어 설정 구성

4. 메인 프로그램 실행:
```bash
python main.py
```

## 사용 방법

1. 장치 전원을 켜고 모든 연결이 올바른지 확인
2. 시스템 초기화 대기
3. LED 표시등으로 시스템 상태 확인
4. 웨이크 워드로 로봇 활성화
5. 음성 명령 또는 웹 인터페이스로 상호작용

## 기여 방법

기여를 환영합니다! 풀 리퀘스트를 제출하기 전에 기여 가이드라인을 읽어주세요.

## 라이선스

이 프로젝트는 Apache License 2.0 하에 라이선스가 부여됩니다 - 자세한 내용은 LICENSE 파일을 참조하세요.

## 지원

지원 및 문의사항:
- GitHub에서 이슈 생성
- 커뮤니티 포럼 참여
- 문서 확인

## 감사의 말

모든 기여자와 오픈소스 커뮤니티에 특별한 감사를 드립니다.