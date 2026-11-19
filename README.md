# FOD-0 공구관제

공군 부품정비 작업장용 공구·소모품 관리 시스템의 개념 랜딩 페이지입니다.
페이지의 인물, 작업번호, 수치는 모두 설명용 예시입니다.

## 구조

- `public/index.html` — 랜딩 페이지 (단일 HTML 파일)
- `firebase.json` — Firebase Hosting 설정
- `.github/workflows/firebase-hosting.yml` — `main`에 푸시하면 Firebase Hosting에 자동 배포

## 배포

`main` 브랜치에 푸시하면 GitHub Actions가 Firebase Hosting에 배포합니다.
저장소 Secrets에 `FIREBASE_SERVICE_ACCOUNT`(Firebase 서비스 계정 JSON)가 있어야 합니다.
