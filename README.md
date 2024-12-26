### 📋 프로젝트 기본 정보  
**프로젝트명**: 카카오 소셜 로그인 연동  
**목적**: 카카오 소셜 로그인을 활용한 사용자 인증 및 React 기반 UI 제공  

---

### 🛠 기술 스택  
**프론트엔드**: React  
**API**: Kakao API  
**기타**: Axios, React Router, dotenv  

---

### 🚀 설치 및 실행 가이드  
프로젝트를 로컬 환경에서 실행하려면 다음 단계를 따르세요.  

#### 1️⃣ 레포지토리 클론  
```bash  
git clone https://github.com/jiwon887/hw4.git  
```

#### 2️⃣ 패키지 설치
```bash
npm install react react-dom react-router-dom react-transition-group axios dotenv  
```

#### 3️⃣ 환경변수 설정
```bash
REACT_APP_REST_API_KEY=카카오API_키  
REACT_APP_REDIRECT_URI=카카오_리다이렉션_URI  
```

#### 4️⃣ 프로젝트 실행
```bash
npm start  
```


### 📂 프로젝트 주요 구조 설명

프로젝트명/  
├── public/                   # 정적 파일 디렉토리  
├── src/                      # 주요 소스 코드  
│   ├── App.js                # 앱 전체 라우팅 구성  
│   ├── index.js              # React 렌더링 진입점  
│   ├── component/            # 개별 컴포넌트 디렉토리  
│   │   ├── login.js          # 로그인 페이지  
│   │   ├── signup.js         # 회원가입 페이지  
│   │   ├── wishlist.js       # 위시리스트  
│   │   ├── popular.js        # 인기 콘텐츠 페이지  
│   │   ├── search.js         # 검색 기능  
│   │   └── filter.js         # 필터 기능  
│   └── styles/               # 스타일 시트 디렉토리  
├── .env-dev                  # 환경 변수 파일  
├── .env-prod                 # 환경 변수 파일(배포용)
├── package.json              # 프로젝트 설정 및 의존성  
├── README.md                 # 프로젝트 문서  
└── build/                    # 빌드된 정적 파일 



