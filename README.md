<div align="center">

# Lee Heon Young | 이헌영

### 상상을 현실로 짓는 시스템 개발자

<p>
기획에 머무른 아이디어를 코드와 구조로 구체화해<br>
현실의 결과물로 완성하는 과정을 좋아합니다.
</p>

[![Notion Portfolio](https://img.shields.io/badge/Notion_Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://app.notion.com/p/Portfolio-3c984bb1d49380f6b486d9b807994f46?source=copy_link)
[![GitHub Repositories](https://img.shields.io/badge/GitHub_Repos-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/heon000)
[![Email Contact](https://img.shields.io/badge/Contact_Me-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ggamci2001@example.com)

</div>

<br>

---

## Tech Stack

| Category | Skills |
| --- | --- |
| **Language** | <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" /> |
| **Embedded & Firmware** | <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" /> <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" /> <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" /><br>`FreeRTOS` `UART` `I2S` `HX711` |
| **System & Network** | <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" /> <img src="https://img.shields.io/badge/TCP%2FIP-2563EB?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/Socket-4A154B?style=flat-square&logoColor=white" /><br>`Protocol Design` `Non-blocking I/O` |
| **DB & Backend** | <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" /><br>`Mongoose` `Session` `RBAC` `Pug` |
| **AI & Data Engineering** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" /> <img src="https://img.shields.io/badge/RAG-2563EB?style=flat-square&logoColor=white" /><br> `Prompt Engineering` |
| **Hardware Prototyping** | <img src="https://img.shields.io/badge/EasyEDA-1765F3?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/JLCPCB-F97316?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/SketchUp-005F9E?style=flat-square&logoColor=white" /><br>`PCB Artwork`  `3D Modeling` |
| **Development Tools** | <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" /> <img src="https://img.shields.io/badge/IntelliJ-000000?style=flat-square&logo=intellijidea&logoColor=white" /> <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" /><br>`AWS CloudWatch` |



---

## Featured Projects

### 1. 날씨 기반 AI 조향 및 개인화 스마트 디퓨저
> 날씨 데이터와 사용자 상태를 반영해 향을 추천·제어하는 스마트 디퓨저 프로젝트

- **Stack**: `C++`, `ESP32`, `FreeRTOS`, `I2S`, `HX711`, `EasyEDA`, `SketchUp`, `AWS CloudWatch`
- **My Role**: 임베디드 제어, 센서 처리, PCB 설계, 기구 구조 검토, 통합 디버깅 참여
- **What I Did**
  - 로드셀 잔량 % 변환 로직과 영점 보정 구조 정리
  - 센서 데이터 안정화를 위한 EMA 기반 필터링 적용
  - 맞춤형 PCB 아트웍 설계 및 발주 진행
  - 하우징 내부 구조와 부품 간 물리적 간섭 검토
- **Repository**: [Smart-diffuser](https://github.com/heon000/Smart-diffuser)

<br>

### 2. 라즈베리 파이를 활용한 LED 두더지 게임
> TCP/IP 소켓 통신 기반 실시간 네트워크 대전 게임

- **Stack**: `C`, `Python`, `Raspberry Pi`, `TCP/IP`, `Socket`, `Firebase`
- **My Role**: 팀장, 게임 흐름 통합, 멀티 게임 로직 구현 및 입출력 제어 통합, TCP/IP 소켓 통신 구조 설계, 최종 디버깅
- **What I Did**
  - `millis()` 기반 논블로킹 게임 루프 구성
  - 비트마스킹과 상승 엣지 검출 기반 입력 처리 구현
  - Python TCP/IP 서버와 클라이언트 메시지 흐름 설계
  - 로컬 2인 구조를 네트워크 멀티플레이 구조로 전환
- **Repository**: [LED-Mole-Game](https://github.com/heon000/LED-Mole-Game)

<br>

### 3. RAG 기반 데이터시트 챗봇 (진행 중)
> 영문 하드웨어 데이터시트를 기반으로 한국어 답변과 출처 페이지를 반환하는 RAG 프로젝트

- **Stack**: `Python`, `Gemini API`, `Pydantic` , `RAG`
- **My Role**: AI 응답 엔진 설계, 프롬프트 작성, 구조화 출력 및 출처 검증 로직 구현
- **What I Did**
  - 검색 청크 기반 응답용 프롬프트 설계
  - Pydantic 기반 JSON 응답 스키마 구성
  - 출처 페이지 검증 및 예외 처리 로직 구현
  - 단위 테스트용 입력 구조 정의 및 AI 모듈 독립 검증
- **Repository**: [RAG_ChatBot](https://github.com/heon000/RAG_ChatBot)

---

## Education / Awards / Credentials

| Category | Details |
| --- | --- |
| **Education** | 성결대학교 정보통신공학과 (2020.03 ~ 2027.02 졸업예정) |
| **GPA** | 전공평점 4.0 / 4.5 |
| **Awards** | 2025-2 종합 설계 기획 경진대회 **최우수상** |
| **Activities** | 2026 한이음 ICT 멘토링 프로젝트 수행 |
| **Certificates** | 정보처리기사 필기 합격 / 리눅스마스터 2급 |

---

## Links

- **Notion Portfolio**: https://app.notion.com/p/Portfolio-3c984bb1d49380f6b486d9b807994f46?source=copy_link
- **GitHub**: https://github.com/heon000
