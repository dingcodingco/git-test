# 프로젝트 이름

React와 Node.js를 사용하는 웹 애플리케이션

## 📚 기술 스택

### Frontend
- **React** - UI 라이브러리
- **React Router** - 클라이언트 사이드 라우팅
- **Axios** - HTTP 클라이언트

### Backend
- **Node.js** - 런타임 환경
- **Express** - 웹 프레임워크
- **MongoDB / PostgreSQL** - 데이터베이스 (선택)

## 📁 프로젝트 구조

```
project-root/
├── client/                 # React 프론트엔드
│   ├── public/            # 정적 파일
│   ├── src/
│   │   ├── components/    # 재사용 가능한 컴포넌트
│   │   ├── pages/         # 페이지 컴포넌트
│   │   ├── hooks/         # 커스텀 훅
│   │   ├── utils/         # 유틸리티 함수
│   │   ├── api/           # API 호출 함수
│   │   ├── App.js         # 루트 컴포넌트
│   │   └── index.js       # 엔트리 포인트
│   └── package.json
│
├── server/                # Node.js 백엔드
│   ├── src/
│   │   ├── routes/        # API 라우트
│   │   ├── controllers/   # 비즈니스 로직
│   │   ├── models/        # 데이터 모델
│   │   ├── middleware/    # 미들웨어
│   │   ├── config/        # 설정 파일
│   │   └── app.js         # Express 앱
│   ├── server.js          # 서버 엔트리 포인트
│   └── package.json
│
├── .gitignore
└── README.md
```

## 🚀 시작하기

### 사전 요구사항
- Node.js (v16 이상)
- npm 또는 yarn

### 설치

1. 저장소 클론
```bash
git clone <repository-url>
cd <project-name>
```

2. 의존성 설치

**Frontend:**
```bash
cd client
npm install
```

**Backend:**
```bash
cd server
npm install
```

3. 환경 변수 설정

**Backend (.env):**
```
PORT=5000
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
```

**Frontend (.env):**
```
REACT_APP_API_URL=http://localhost:5000/api
```

### 실행

**개발 모드:**

터미널 1 - Backend:
```bash
cd server
npm run dev
```

터미널 2 - Frontend:
```bash
cd client
npm start
```

**프로덕션 빌드:**
```bash
# Frontend 빌드
cd client
npm run build

# Backend 실행
cd server
npm start
```

## 📝 주요 기능

- [ ] 사용자 인증 (로그인/회원가입)
- [ ] CRUD 기능
- [ ] RESTful API
- [ ] 반응형 디자인

## 🛠 개발 가이드

### 코딩 컨벤션
- ESLint와 Prettier 사용
- 컴포넌트명은 PascalCase
- 함수/변수명은 camelCase

### Git 커밋 컨벤션
- `feat:` 새로운 기능
- `fix:` 버그 수정
- `docs:` 문서 수정
- `style:` 코드 포맷팅
- `refactor:` 코드 리팩토링
- `test:` 테스트 코드

## 📄 라이선스

MIT

## 👥 기여자

- [Your Name](https://github.com/yourusername)
