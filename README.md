# lifepath-flow
운세그래프(life graph) 웹 서비스
# 운세그래프(Lifepath Flow) 웹 서비스

생년월일 기반의 운세그래프를 제공하는 웹 및 모바일 서비스입니다.

## 기능

- 사용자 인증 (로그인, 회원가입, 소셜 로그인)
- 운세그래프 생성 및 분석
- 회원 등급별 차별화된 서비스 제공
- 결제 시스템

## 기술 스택

### 백엔드
- Python (FastAPI)
- PostgreSQL
- JWT 인증

### 프론트엔드
- React
- Chart.js
- Axios

## 개발 환경 설정

### 요구사항
- Python 3.10+
- Node.js 16+
- PostgreSQL 14+

### 백엔드 설정
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python -m app.main

## 디렉토리
lifepath-flow/
├── README.md
├── .gitignore
├── backend/
│   ├── app/
│   ├── requirements.txt
│   └── ...
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
└── docs/
    ├── api_docs.md
    ├── setup_guide.md
    └── ...
