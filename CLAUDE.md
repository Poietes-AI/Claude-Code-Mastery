# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 언어 및 커뮤니케이션 규칙

- **기본 응답 언어**: 한국어
- **코드 주석**: 한국어로 작성
- **커밋 메시지**: 한국어로 작성
- **문서화**: 한국어로 작성
- **변수명/함수명**: 영어(코드 표준 준수)

## 프로젝트 개요

Claude Code 사용법을 학습하고 마스터하기 위한 저장소입니다.
현재 개발자 웹 이력서(포트폴리오) 프로젝트를 진행 중입니다.

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 기본 스타일링
- **JavaScript**: 바닐라 JS로 인터랙션 구현
- **TailwindCSS**: 유틸리티 기반 스타일링 프레임워크

## 프로젝트 구조

이력서 프로젝트는 다음과 같은 구조를 따릅니다:

```
portfolio/
├── index.html          # 메인 HTML 파일 (모든 섹션 포함)
├── css/
│   └── style.css      # 커스텀 CSS (TailwindCSS 보완용)
├── js/
│   └── main.js        # JavaScript 기능 (스크롤, 애니메이션, 다크모드 등)
└── images/
    └── profile.jpg    # 프로필 및 리소스 이미지
```

## 개발 가이드

### HTML 구조
- 시맨틱 태그 사용 (`<header>`, `<nav>`, `<section>`, `<footer>`)
- 각 섹션은 ID를 가져야 함 (네비게이션 스크롤용)
- 접근성을 위한 ARIA 레이블 적용

### CSS/TailwindCSS
- TailwindCSS CDN 사용 (빌드 프로세스 불필요)
- 커스텀 스타일은 `css/style.css`에 작성
- 반응형 브레이크포인트: sm(640px), md(768px), lg(1024px), xl(1280px)
- 디자인 시스템:
  - Primary: #3B82F6 (Blue)
  - Secondary: #10B981 (Green)
  - Dark: #1F2937
  - Light: #F9FAFB

### JavaScript
- Vanilla JS 사용 (프레임워크 없음)
- Intersection Observer API로 스크롤 애니메이션 구현
- 부드러운 스크롤(`scrollIntoView`)은 네비게이션에 적용
- 다크모드는 localStorage로 사용자 선호도 저장

## 페이지 섹션 순서

1. **Navigation**: 고정 네비게이션 바 (모바일 햄버거 메뉴 포함)
2. **Hero**: 프로필 사진, 이름, 직무, 소셜 링크
3. **About**: 자기소개 및 주요 역량
4. **Skills**: 기술 스택 (카드/배지 형태)
5. **Experience**: 경력 (타임라인 형태)
6. **Projects**: 프로젝트 포트폴리오 (그리드 레이아웃)
7. **Education**: 학력
8. **Contact**: 연락처 정보 및 소셜 링크

## 로컬 개발

이 프로젝트는 정적 HTML 사이트이므로 빌드 도구가 필요 없습니다.

### 로컬 서버 실행
```bash
# Python 3
python -m http.server 8000

# Node.js (http-server 설치 필요)
npx http-server -p 8000
```

브라우저에서 `http://localhost:8000` 접속

## 배포

- **GitHub Pages**: 저장소 Settings > Pages에서 활성화
- **Netlify**: 드래그 앤 드롭 배포
- **Vercel**: GitHub 연동 자동 배포

## 작업 시 유의사항

- 모든 사용자 커뮤니케이션은 한국어로 진행
- 코드 내 주석은 한국어로 작성하되, 변수명과 함수명은 영어 명명 규칙 준수
- Git 커밋 메시지는 한국어로 작성
- ROADMAP.md의 체크리스트를 따라 단계별로 진행
- 이미지 파일은 최적화 후 `images/` 디렉토리에 저장
- 크로스 브라우저 호환성 유지 (Chrome, Firefox, Safari, Edge)
