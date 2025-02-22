# Yelp-Camp

Yelp-Camp는 캠핑장 리뷰 및 공유 웹 애플리케이션.
 사용자는 캠핑장을 등록하고, 리뷰를 작성하며, 지도에서 위치를 확인할 수 있다. 이 프로젝트는 [The Web Developer Bootcamp 2025](https://www.udemy.com/course/the-web-developer-bootcamp/) 강의에서 클론코딩한 프로젝트.

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
- **지도 API**: Mapbox
- **파일 업로드**: Cloudinary
- **기타**: Express-Session, Method-Override

## 📂 프로젝트 구조
```
Yelp-Camp/
├── models/             # 데이터 모델 정의
├── public/             # 정적 파일 (CSS, JS, 이미지)
├── routes/             # 라우터 모음 (캠핑장, 사용자, 리뷰)
├── views/              # EJS 템플릿 파일
├── app.js              # 메인 서버 파일
├── package.json        # 프로젝트 의존성 및 설정
└── .env                # 환경 변수 파일
```

## 🛠 기능
- 사용자 회원가입 및 로그인 (Passport.js 활용)
- 캠핑장 등록, 수정, 삭제
- 리뷰 작성 및 삭제
- 지도 API를 활용한 위치 표시
- 클라우드 스토리지를 이용한 이미지 업로드 (Cloudinary)


## 📌 출처 (Attribution)
이 프로젝트는 [The Web Developer Bootcamp 2025](https://www.udemy.com/course/the-web-developer-bootcamp/) 강의를 참고하여 제작
