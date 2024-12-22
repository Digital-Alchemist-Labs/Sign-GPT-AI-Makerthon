# AI-Makerthon 팀 프로젝트 소개

<img src="https://github.com/SignGPT-pro/.github/raw/main/imgs/sign%20gpt%20(upscale).png" alt="Sign GPT" width="200" height="200">

## 목차
- [팀 소개](#팀-소개)
- [프로젝트 개발 이유](#프로젝트-개발-이유)
- [프로젝트 개요](#프로젝트-개요)
- [실행 방법](#실행-방법)
- [시연영상](#시연영상)
- [문의](#문의)

---

## 팀 소개

### 팀 이름: **Digital Alchemist**

| 이름    | 역할                                   | GitHub Profile                                   |
|---------|----------------------------------------|---------------------------------------------------|
| 이제석  | 프로젝트 파이프라인 설계 및 프로젝트 리딩 / 서버 구축 | [@Jeseok Lee](https://github.com/itsjay83)        |
| 정은교  | 인공지능 모델 학습 및 변환 및 수어 인식 모델 개발     | [@kyo](https://github.com/eunkyo3)                 |
| 우진호  | 수어 데이터셋 구축 및 출력 모델 구현           | [@woojinho](https://github.com/jinho-22)           |
| 최 환   | UI/UX 설계 및 개발/구현                     | [@최환](https://github.com/hwan06)                  |

---

## 프로젝트 개발 이유

ChatGPT의 출시 이후, 우리의 일상이 한층 더 편리해졌습니다. 하지만 "수어를 사용하는 농인들도 ChatGPT와 같은 기술 혁신의 혜택을 누리고 있을까?"라는 의문을 가지게 되었습니다.

이에 따라 자료를 조사한 결과, "필담을 완벽히 이해하는 비율 12%", "모든 회의록, 일지 및 행정 처리를 수어로만 진행", "한국어로 글을 쓰거나 의사소통하는 것이 실질적으로 어렵다"는 조사 결과를 청각장애인 고용 차별 및 개선 방안 실태 조사를 통해 확인할 수 있었습니다.

이러한 문제를 해결하고자 저희는 농인의 정보 격차를 줄이며, 이들의 사회적 참여와 기회를 확대하기 위해 이번 프로젝트를 진행하게 되었습니다.

### 주요 동기:
1. **문제 정의**: 수어를 사용하는 농인들이 필담을 통한 의사소통에서 낮은 이해율(12%)을 보이며, 모든 행정 처리와 기록 관리에 있어 수어 사용에 의존해야 하는 어려움을 겪고 있습니다. 또한, 한국어로 글을 쓰거나 의사소통하는 데에 실질적인 어려움이 존재합니다. 이러한 문제는 농인들의 정보 접근성과 사회적 참여를 제한하고 있습니다.
2. **해결 목표**: 농인의 정보 격차를 줄이고, 이들이 디지털 혁신 기술의 혜택을 누릴 수 있도록 지원하는 것을 목표로 합니다. 이를 통해 농인들의 의사소통 방식을 개선하고, 정보 접근성과 사회적 기회를 확대할 수 있는 솔루션을 제공합니다.
3. **핵심 가치**: 이 프로젝트는 농인들에게 실질적인 도움을 주며, 정보의 평등한 접근성을 보장하는 데 기여합니다. 또한, 디지털 기술의 혜택을 모두가 공평하게 누릴 수 있는 사회를 지향하며, 농인의 자립과 사회적 참여를 돕는 기반을 마련합니다.

---

## 프로젝트 개요

### 프로젝트 이름: **Sign-GPT**

### 주요 기능:
- **수어 동작 키포인트 인식**: 수어 영상을 인식하여 주요 키포인트를 추출하고, 이를 기반으로 관련 단어를 생성한 후 LLM 서버로 전달합니다.
- **LLM Server**: LLM 서버에서 입력된 단어를 활용해 질문을 생성하고, 이를 GPT에게 전달합니다. GPT로부터 받은 답변을 바탕으로 데이터베이스에서 해당 수어 영상을 검색하여 프론트엔드에 전달합니다.
- **수어 답변 연속 출력**: 프론트엔드에서 전달받은 수어 답변 영상을 자연스럽게 연속 출력하여 농인 사용자에게 정보를 제공합니다.

### 기술 스택:
- **프론트엔드**: Python
- **백엔드**: Python
- **데이터베이스**: MongoDB
- **배포**: Vercel

### 기술 설명
- **수어 인식 후 서버에 값 전달**
  
  ![수어 인식 후 서버에 값 전달](https://github.com/user-attachments/assets/458f732a-bda4-4a02-8759-1d6796ec2991)

  - 인식 과정
  ![프로젝트 최종 프로세스](https://github.com/user-attachments/assets/1cf8f18b-582a-4c02-9d8a-6831f1020e80)

---

- **LLM Server 처리**

  ![LLM Server 처리](https://github.com/user-attachments/assets/08a780e5-fa52-4c4a-a8e6-c411b86b3be9)

  - 서버 로그 처리
  ![image](https://github.com/user-attachments/assets/1743c932-f28c-4349-ad98-abb0b4aa86b5)
    
---

- **수어 답변 출력**

  <img width="996" alt="image" src="https://github.com/user-attachments/assets/28be370f-9baa-42c5-9309-077230961163" />

---

- **프로젝트 진행 흐름**

![결과 화면](https://github.com/user-attachments/assets/fad126f5-1b4f-44c9-bed5-cb72158de21c)

---

## 1일차

1. **지금까지 한 것:**
    - LLM 서버 배포 및 클라이언트 배포 (진행중)
    - 대화 기록 및 과거 메세지 접근 (진행중)
2. **어라.. 이게 되네 했던것:** 없음
3. **앞으로 해야하는 기능 구현:** 로컬 LLM 서버
4. **남은 기간 가장 큰 어려운 것:** 서버 배포 (구 버전 패키지만 Vercel 배포를 지원함)

---

## 실행 방법

### 1. 환경 설정

#### **서버 설정**
1. **프로젝트 클론**
    ```bash
    git clone https://github.com/Digital-Alchemist-Labs/SignGPT-Server
    cd SignGPT-Server
    ```

2. **가상환경 및 필요한 패키지 설치**
    ```bash
    python3 -m venv env
    source env/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

3. **환경 변수 설정**
    프로젝트 루트에 `.env` 파일을 생성하고 아래 내용을 추가:
    ```env
    OPENAI_API_KEY="your_api_key"
    ```

---

2. **클라이언트 설정**
    ```bash
    git clone https://github.com/Digital-Alchemist-Labs/SignGPT-Client
    cd SignGPT-Client
    ```

3. **가상환경 및 필요한 패키지 설치**
    ```bash
    python3 -m venv env
    source env/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

### 2. 실행
1. **서버 실행**
    ```bash
    python3 app/legacy.py
    ```

2. **클라이언트 실행**
    ```bash
    streamlit run main.py
    ```

### 3. 접속
- 서버 : [http://0.0.0.0:8000](http://0.0.0.0:8000)
- 클라이언트 : 클라이언트 실행시 접속됨

---

## 시연영상

썸네일 이미지를 클릭하여 시연 영상 시청

[![시연 영상](https://img.youtube.com/vi/3sW5sfu0VPc/maxresdefault.jpg)](https://www.youtube.com/watch?v=3sW5sfu0VPc&si=C_A63wrLHFQ5b6PM)

---

## 문의

프로젝트에 대한 문의 사항은 아래로 연락해주세요:

- **이메일**: [example@example.com](mailto:example@example.com)
- **GitHub Issues**:
  - [클라이언트 이슈 바로가기](https://github.com/Digital-Alchemist-Labs/SignGPT-Client/issues)
  - [서버 이슈 바로가가기](https://github.com/Digital-Alchemist-Labs/SignGPT-Server/issues)
- **팀 웹사이트**: [[https://team-website.com](https://team-website.com](https://github.com/Digital-Alchemist-Labs))

---

감사합니다! 🙌
