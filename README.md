# LocalFit Frontend

지역 기반 운동 커뮤니티/모임 서비스 LocalFit의 프론트엔드 레포입니다. React + Vite 기반으로 구성되어 있으며, UI는 MUI와 Emotion, 상태 관리는 Zustand를 사용합니다.

## 빠른 시작

1. 의존성 설치

```bash
npm install
```

2. 개발 서버 실행

```bash
npm run dev
```

기본 포트는 `5173` 입니다.

## 스크립트

- `npm run dev`: 개발 서버 실행
- `npm run build`: 프로덕션 빌드
- `npm run preview`: 빌드 결과 프리뷰
- `npm run lint`: ESLint 실행

## 기술 스택

- React 18 + Vite
- React Router
- Zustand
- MUI + Emotion
- Axios
- React DnD
- Quill / React-Quill
- Date-fns
- Kakao Maps SDK
- STOMP (WebSocket)

## 프로젝트 구조

```
src/
  api/            # API 모듈
  assets/         # 정적 리소스
  components/     # 공통 컴포넌트
  images/         # 이미지 리소스
  pages/          # 라우팅 페이지
  stores/         # 전역 상태 (Zustand)
  styles/         # 스타일 유틸/테마
  utils/          # 유틸 함수
  App.jsx
  main.jsx
```

## 환경 변수

프로젝트에 필요한 환경 변수는 `.env`에 설정합니다. 실제 키 이름은 프로젝트 요구사항에 맞게 추가하세요.

예시:

```
VITE_API_BASE_URL=
VITE_KAKAO_MAP_API_KEY=
```

## 커밋/브랜치 규칙 (선택)

프로젝트 팀 규칙에 맞게 작성해주세요.

- 브랜치: `feature/`, `fix/`, `refactor/` 등
- 커밋: `feat:`, `fix:`, `refactor:`, `chore:` 등

## 배포 (선택)

배포 환경과 방법을 여기에 기록합니다. 예: Vercel, Netlify, S3+CloudFront 등.
