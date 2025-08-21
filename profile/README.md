# TodAi : AI 음성 감정 일기 애플리케이션

> 바쁜 일상 속, **말하기**만으로 감정을 기록하고 AI로 스스로를 더 깊이 이해하세요.

<p align="center">
  <img width="1433" height="802" alt="Image" src="https://github.com/user-attachments/assets/bc148cf7-6f8a-4813-9b91-b8c80ad7c47e" />
</p>

---

## 📌 목차
- [🚀 프로젝트 배경 (Background)](#-프로젝트-배경-background)
- [🎯 프로젝트 목표 (Goal)](#-프로젝트-목표-goal)
- [✨ 주요 기능 (Features)](#-주요-기능-features)
- [🛠️ 기술 스택 (Tech Stack)](#️-기술-스택-tech-stack)
- [👨‍💻 팀원 (Team)](#-팀원-team)

---

## 🚀 프로젝트 배경 (Background)

1. **정신 건강 관리의 필요성 증가**
   
     현대 사회의 바쁜 일상과 경쟁적인 환경 속에서 많은 사람들은 자신의 감정을 돌볼 여유를 잃어가고 있습니다. 특히 비대면 소통이 증가하면서 감정 교류는 줄어들고, 스트레스와 피로가 제대로 해소되지 못해 우울감과 불안감 등 정신 건강에 부정적인 영향을 미치는 경우가 많아졌습니다.

   
   
2. **기존 텍스트 기반 기록의 한계**
   
     기존에도 일기를 통해 감정을 기록하고 분석하는 서비스는 존재했지만, 글로 감정을 표현할 때는 문장을 다듬는 과정에서 심리적 부담이 발생하고 감정이 왜곡되거나 정제될 수 있다는 한계가 있었습니다.

   
  
3. **'말하기'를 통한 진솔한 감정 표현**
   
     베일러 대학교의 연구에 따르면, 말하기는 글쓰기보다 더 직관적이고 진솔한 감정 표현을 유도하는 경향이 있습니다. 감정을 소리 내어 말하는 행위는 자기 인식을 높이고 내면을 객관적으로 바라보는 계기를 제공하여 정신적 안정감 향상에 도움을 줄 수 있습니다. 

**TodAi**는 사용자가 음성을 통해 부담 없이 감정을 기록하고, AI로부터 객관적인 분석과 관리를 받을 수 있는 새로운 솔루션을 제공합니다.

---

## 🎯 프로젝트 목표 (Goal)

사용자가 음성으로 하루의 일기를 기록하면, AI 모델이 이를 분석하여 감정 변화를 추적하고 관리해주는 애플리케이션을 개발합니다. 이를 통해 사용자의 장기적인 감정 흐름을 모니터링하고 정서적 건강 유지에 도움을 주는 맞춤형 서비스를 제공합니다.

### 세부 목표
- **음성 기반 감정 기록 시스템 구현**

  음성 → 텍스트 변환 + 멀티모달(음성+텍스트) 감정 분석 결과 시각화

  
- **고성능 감정 분석 모델 개발**

  한국어 특화, 6가지 핵심 감정(기쁨/슬픔/분노/놀람/공포/혐오) 정밀 분류

  
- **보호자 연동**

  공유 범위 설정 및 연동된 사용자의 감정 추이 파악

---

## ✨ 주요 기능 (Features)

### 📝 회원가입 및 로그인
- 닉네임 | 아이디 | 비밀번호 | 이메일 | 생년월일 | 사용자 유형 | 성별

<img src="https://github.com/user-attachments/assets/a9b43f4a-672b-432a-a08d-744079040e1a" width="250" height="500" />

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/2d9d222b-b408-43c8-b232-a0cb6ea5def5" />

---
## 🔵 사용자 화면

### 🎙️ 음성 녹음 및 AI 감정 분석
- 메인 화면의 마이크 버튼으로 녹음
- 녹음 종료 시 AI가 음성을 통해 감정 비율 분포 계산
- 6가지 감정(기쁨, 슬픔, 분노, 놀람, 공포, 혐오) + 음성 요약 및 코멘트 제공

<img src="https://github.com/user-attachments/assets/57c1e1cc-9256-4ef3-bf8e-1e56b8716890" width="250" height="500" />

---

### 📅 감정 캘린더 & 시각화 그래프
- 월별 캘린더에서 대표 감정 이모티콘으로 한눈에 확인
- 날짜 선택 → 일별 상세 리포트 제공 및 일기 작성 가능
- 장기적인 감정 흐름 추적 지원

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/a586caf8-f856-44e9-b9d2-8e9250360266" />

---

### 📊 일별 상세 리포트
- 각 날짜별 일기 내용 & 감정 분석 결과 확인
- 레이더 차트로 6가지 감정 분포를 직관적으로 파악
- 즐겨찾기로 중요한 기록 보관, 스크린샷 저장/공유

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/0170a8a2-47d6-41bb-87fc-7ea04f9737c4" />

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/505b8903-5e60-416b-9aad-a5bcb69b9444" />

---

### 👤 마이페이지
- 사용자 정보, 연동된 보호자 목록, 받은 메세지 확인 가능
- 전체/일부 공개 등 프라이버시 보호 옵션 제공

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/60141984-9578-474a-a465-3d7eca508a3d" />

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/55104cf2-bea4-48cd-826f-717ae8383adf" />

<img src="https://github.com/user-attachments/assets/2d10c18f-126b-44a9-9e01-c0ea90d0a1ed" width="250" height="500" />

---
## 🔵 보호자 화면

### 🤝 보호자 대시보드
- 사용자 계정과 연동하여 감정 기록 공유
- 사용자에게 연동 요청 및 연동 수락/거절 알림, 연결된 보호자 목록 관리
- 연동된 사용자 감정 변화 추이 확인 가능

<img src="https://github.com/user-attachments/assets/d6f041cb-8327-409c-9a79-f94ee4757d86" width="250" height="500" />

---

### 🧑‍🤝‍🧑 보호자 모니터링
- 연동된 사용자의 감정 캘린더 모니터링
- 사용자가 4일 이상 연속 부정 감정일 경우 자동 알림
- 공개 범위가 전체일 때, 일기 전문 & 상세 감정 차트 열람 가능

<img src="https://github.com/user-attachments/assets/9340cdca-a3b0-44b2-be4e-b2c0dfd7d55b" width="250" height="500" />

---

### 💌 메세지 전송

- 연동된 사용자에게 응원의 메세지 전송 가능

<img width="250" height="500" alt="Image" src="https://github.com/user-attachments/assets/137a779b-2d4c-49c9-884c-b87f076a2696" />

---

## 🛠️ 기술 스택 (Tech Stack)

**Frontend**
- React Native

**Backend**
- Django, Django REST Framework, Spring Boot

**AI**
- KoBERT, Whisper, Wav2Vec2

**Database**
- PostgreSQL

**Deployment**
- Cloudtype, Local deployment

---

## 👨‍💻 팀원 소개

| 이름   | 포지션        | GitHub |
|--------|---------------|--------|
| 이재혁 | Backend, AI   | [@Hyuk-II](https://github.com/Hyuk-II) |
| 이채원 | Backend       | llcc-ww |
| 김태이 | Frontend      | EH-OI |
| 서예원 | Frontend      | yewonida |
| 박현서 | AI            | hyunseo0524 |

---

