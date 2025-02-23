# Yelp-Camp

Yelp-Camp는 캠핑장 리뷰 및 공유 웹 애플리케이션.
 사용자는 캠핑장을 등록하고, 리뷰를 작성하며, 지도에서 위치를 확인할 수 있다. 이 프로젝트는 [The Web Developer Bootcamp 2025](https://www.udemy.com/course/the-web-developer-bootcamp/) 강의에서 클론코딩한 프로젝트이다.

## 📌 프로젝트 개요
- 캠핑장 정보를 등록하고 관리할 수 있는 기능 제공
- 사용자 리뷰 및 평가 기능 지원
- 지도 API를 활용한 위치 표시 기능
- 사용자 인증 및 권한 관리

## 🚀 기술 스택
- **프론트엔드**: HTML, CSS, Bootstrap, EJS
- **백엔드**: Node.js, Express.js
- **데이터베이스**: MongoDB, Mongoose
- **인증 및 보안**: Passport.js, bcrypt
- **파일 업로드**: Cloudinary
- **기타**: Express-Session, Method-Override, JOI

## 📂 프로젝트 구조
```
yelpcamp/
├─ cloudinary/         # Cloudinary 설정 및 스토리지
├─ controllers/        # 기능별 비즈니스 로직 (캠핑장, 사용자, 리뷰 등)
├─ models/             # Mongoose 모델 (캠핑장, 사용자, 리뷰)
├─ public/             # 정적 파일 (CSS, JS, 이미지)
├─ routes/             # 라우팅 파일 (캠핑장, 리뷰, 사용자)
├─ seeds/              # 초기 데이터 시딩
├─ utils/              # 에러 핸들링 및 유틸리티 함수
├─ views/              # EJS 템플릿
│  ├─ layouts/         # 기본 레이아웃 (header, footer)
│  ├─ partials/        # 재사용 가능한 컴포넌트
│  ├─ users/           # 사용자 관련 페이지
│  ├─ error.ejs        # 에러 페이지
│  └─ home.ejs         # 홈페이지
├─ .env                # 환경 변수
├─ app.js              # 주요 애플리케이션 파일
├─ middleware.js       # 미들웨어 함수
└─ schemas.js          # 입력 검증 스키마

```

## 🛠 기능
- 사용자 회원가입 및 로그인 (Passport.js 활용)
- 캠핑장 등록, 수정, 삭제 (CRUD)
- 리뷰 작성 및 삭제
- 클라우드 스토리지를 이용한 이미지 업로드 (Cloudinary)
- 보안 강화 : 입력값 검증과 MongodDB 데이터 보호


## 📌 출처 (Attribution)
이 프로젝트는 [The Web Developer Bootcamp 2025](https://www.udemy.com/course/the-web-developer-bootcamp/) 강의를 참고하여 제작

마지막 배포 단계에 오류가 생겨 구현을 하지 못함
