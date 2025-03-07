# YonseiBookmate 📖📚

YonseiBookmate는 연세대학교 미래캠퍼스 원주학술도서관의 도서 검색 & 추천을 제공하는 AI 기반 모바일 애플리케이션입니다.  

## 📌 주요 기능
- 🔍 맞춤형 도서 추천: AI 기반 추천 시스템
- 📚 실시간 대출 가능 도서 확인: 크롤링을 통해 최신 대출 상태 제공
- 📅 반납 일정 알림: 대출한 책의 반납일 관리 및 푸시 알림
- 📖 사용자 선호 분석: 이전 대출 기록을 바탕으로 맞춤 추천 제공

## 🚀 기술 스택
- 프론트엔드: Flutter (Dart) / React Native
- 백엔드: FastAPI (Python) / Flask
- 크롤링: BeautifulSoup, Selenium (Python)
- AI 추천 시스템: TensorFlow / Scikit-learn
- 데이터베이스: PostgreSQL / Firebase
- 호스팅: AWS / Vercel / Firebase

## 🔧 설치 방법
### 1. Backend (FastAPI 실행)
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
