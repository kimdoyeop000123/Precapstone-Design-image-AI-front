# AI 기반 이미지 생성 & 문자 전송 서비스

> 사용자가 문자 메시지를 입력하면 AI가 자동으로 이미지를 생성해 문자로 전송하는 서비스

🎬 **[시연 영상 보기](https://www.youtube.com/watch?v=14B8NUl3yfs)**

---

## 📌 프로젝트 개요

| 항목 | 내용 |
|------|------|
| 기간 | 2024.09 ~ 2024.12 (4개월) |
| 유형 | 팀 프로젝트 (5명) · 기업 연계 (다우기술) |
| 역할 | AI 이미지 생성 모델 테스트 · 성능 최적화 · 발표 |

---

## 🛠 기술 스택

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)

| 분류 | 기술 |
|------|------|
| 프론트엔드 | React |
| 백엔드 | Spring Boot |
| AI 서버 | Flask, Stable Diffusion XL, OpenAI API |
| DB | MariaDB |
| 인프라 | AWS EC2 |

---

## 🔍 핵심 기능

| 기능 | 설명 |
|------|------|
| ✍️ 메시지 입력 | 사용자가 문자 메시지 내용 입력 |
| 🤖 프롬프트 생성 | OpenAI API로 이미지 생성용 프롬프트 자동 변환 |
| 🎨 이미지 생성 | Stable Diffusion XL로 일러스트 이미지 자동 생성 |
| 📱 문자 전송 | 생성된 이미지를 포함한 문자 발송 |

---

## 🙋 나의 역할

- Stable Diffusion XL 기반 이미지 생성 AI 테스트 및 성능 분석
- LoRA 모델 탐색 및 적용 검토
- 샘플링 메소드 비교·테스트 (DDIM, Euler, DPM 등) → 생성 시간 12초에서 5~7초로 단축 (약 40% 개선)
- 이미지 생성 과정에서 텍스트가 제대로 표현되지 않는 문제 해결 → 사용자가 원하는 문구를 직접 삽입할 수 있는 기능 추가
- 최종 발표 담당

---

## 🏆 성과

- 기업(다우기술) 요구사항 반영 및 최종 심사 시연 성공
- 기업 관계자로부터 긍정적인 평가

---

## 📁 레포지토리

- [Frontend](https://github.com/kimdoyeop000123/Precapstone-Design-image-AI-front)
- [Backend](https://github.com/kimdoyeop000123/Precapstone-Design-image-AI-back)
