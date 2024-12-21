# AI-Makerthon 팀 프로젝트 소개
 
![프로젝트 로고](https://via.placeholder.com/200)

## 목차
- [팀 소개](#팀-소개)
- [프로젝트 개발 이유](#프로젝트-개발-이유)
- [프로젝트 개요](#프로젝트-개요)
- [실행 방법](#실행-방법)
- [문의](#문의)

---

## 팀 소개

### 팀 이름: **Digital Alchemist**

| 이름          | 역할           | GitHub Profile                                   |
|---------------|----------------|-------------------------------------------------|
| 이제석       | 프로젝트 파이프라인 설계 및 프로젝트 리딩 / 서버 구축  | [@Jeseok Lee](https://github.com/itsjay83)   |
| 정은교       | 인공지능 모델 학습 및 변환 및 수어 인식 모델 개발     | [@kyo](https://github.com/eunkyo3) |
| 우진호       | 수어 데이터셋 구축 및 출력 모델 구현 | [@woojinho](https://github.com/jinho-22)     |
| 최 환        | UI/UX 설계 및 개발/구현 | [@최환](https://github.com/hwan06) |

---

## 프로젝트 개발 이유

ChatGPT의 출시 이후, 우리의 일상이 한층 더 편리해졌습니다. 하지만 "수어를 사용하는 농인들도 ChatGPT와 같은 기술 혁신의 혜택을 누리고 있을까?"라는 의문을 가지게 되었습니다.

이에 따라 자료를 조사한 결과, "필담을 완벽히 이해하는 비율 12%", "모든 회의록, 일지 및 행정 처리를 수어로만 진행", "한국어로 글을 쓰거나 의사소통하는 것이 실질적으로 어렵다"는 조사 결과를 청각장애인 고용 차별 및 개선 방안 실태 조사를 통해 확인할 수 있었습니다.

이러한 문제를 해결하고자 저희는 농인의 정보 격차를 줄이며, 이들의 사회적 참여와 기회를 확대하기 위해 이번 메이커톤에 참여하게 되었습니다.


### 주요 동기:
1. **문제 정의**: 농인들이 이런 불편함을 느낌
2. **해결 목표**: 그래서 우리는 이런 프로젝트를 만들었음
3. **핵심 가치**: 이 프로젝트를 통행 얻는 이점

---

## 프로젝트 개요

### 프로젝트 이름: **Sign-GPT**

### 주요 기능:
- **기능 A**: 수어 인식
- **기능 B**: LLM서버를 통해 어쩌구 저쩌구
- **기능 C**: 답변을 수어로 출력

### 기술 스택:
- **프론트엔드**: Python
- **백엔드**: Python
- **데이터베이스**: MongoDB
- **배포**: AWS, Docker

![시스템 구조](https://via.placeholder.com/800x400)

---

## 실행 방법

### 1. 환경 설정
1. **프로젝트 클론**
   ```bash
   git clone https://github.com/username/project.git
   cd project
   ```

2. **필요한 패키지 설치**
   ```bash
   npm install
   ```

3. **환경 변수 설정**
   프로젝트 루트에 `.env` 파일을 생성하고 아래 내용을 추가:
   ```env
   DB_URL=your_database_url
   API_KEY=your_api_key
   ```

### 2. 실행
1. **개발 서버 실행**
   ```bash
   npm run dev
   ```

2. **프로덕션 빌드** (선택 사항)
   ```bash
   npm run build
   npm start
   ```

### 3. 접속
   - 로컬에서: `http://localhost:3000`
   - 배포된 서버: `https://your-deployed-site.com`

---

## 문의

프로젝트에 대한 문의 사항은 아래로 연락해주세요:

- **이메일**: example@example.com
- **GitHub Issues**: [링크](https://github.com/username/project/issues)
- **팀 웹사이트**: [https://team-website.com](https://team-website.com)

---

감사합니다! 🙌
