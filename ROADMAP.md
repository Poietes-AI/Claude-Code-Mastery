# 개발자 웹 이력서 개발 로드맵

## 📋 프로젝트 개요
HTML, CSS, JavaScript, TailwindCSS를 활용한 반응형 개발자 웹 이력서 개발

## 🛠 기술 스택
- **HTML5**: 시맨틱 마크업
- **CSS3**: 기본 스타일링
- **JavaScript**: 인터랙션 및 동적 기능
- **TailwindCSS**: 유틸리티 기반 스타일링

## 📁 디렉토리 구조
```
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   └── profile.jpg
└── README.md
```

## 🎯 주요 섹션
1. **Hero / 소개 섹션**
   - 프로필 사진
   - 이름 및 직무
   - 간단한 소개글
   - 소셜 링크 (GitHub, LinkedIn, Email 등)

2. **About / 자기소개**
   - 상세 소개
   - 주요 역량

3. **Skills / 기술 스택**
   - 프론트엔드 기술
   - 백엔드 기술
   - 도구 및 기타

4. **Experience / 경력**
   - 회사명, 직책, 기간
   - 주요 업무 및 성과

5. **Projects / 프로젝트**
   - 프로젝트명
   - 설명
   - 사용 기술
   - 링크 (GitHub, Demo)

6. **Education / 학력**
   - 학교명
   - 전공
   - 졸업 연도

7. **Contact / 연락처**
   - 이메일
   - GitHub
   - LinkedIn
   - 기타 연락 방법

## 📝 개발 단계

### Phase 1: 기본 구조 설정 (1일차)
- [x] 프로젝트 디렉토리 구조 생성
- [ ] HTML 기본 구조 작성
- [ ] TailwindCSS CDN 설정
- [ ] 기본 레이아웃 구성

### Phase 2: Hero & Navigation (1일차)
- [ ] 네비게이션 바 구현
  - 로고/이름
  - 메뉴 링크 (스크롤 이동)
  - 모바일 햄버거 메뉴
- [ ] Hero 섹션 구현
  - 프로필 이미지
  - 타이핑 효과 (optional)
  - CTA 버튼

### Phase 3: About & Skills (2일차)
- [ ] About 섹션
  - 자기소개 텍스트
  - 레이아웃 디자인
- [ ] Skills 섹션
  - 스킬 카드/배지 형태
  - 애니메이션 효과

### Phase 4: Experience & Projects (2-3일차)
- [ ] Experience 섹션
  - 타임라인 형태 디자인
  - 각 경력 카드
- [ ] Projects 섹션
  - 프로젝트 카드 그리드
  - 호버 효과
  - 모달 또는 상세 페이지 (optional)

### Phase 5: Education & Contact (3일차)
- [ ] Education 섹션
  - 학력 정보 카드
- [ ] Contact 섹션
  - 연락처 정보
  - 소셜 아이콘 링크
  - 컨택 폼 (optional)

### Phase 6: 인터랙션 & 애니메이션 (4일차)
- [ ] 스크롤 애니메이션 구현
  - Intersection Observer API 활용
  - Fade-in, Slide-in 효과
- [ ] Smooth scroll 구현
- [ ] 상단 이동 버튼
- [ ] 다크모드 토글 (optional)

### Phase 7: 반응형 디자인 (4-5일차)
- [ ] 모바일 최적화 (< 640px)
- [ ] 태블릿 최적화 (640px - 1024px)
- [ ] 데스크톱 최적화 (> 1024px)
- [ ] 크로스 브라우저 테스트

### Phase 8: 최적화 & 배포 (5일차)
- [ ] 이미지 최적화
- [ ] CSS/JS 압축
- [ ] SEO 메타 태그 추가
- [ ] Open Graph 태그
- [ ] GitHub Pages 배포 또는 Netlify/Vercel 배포

## 🎨 디자인 가이드라인
- **색상 테마**:
  - Primary: #3B82F6 (Blue)
  - Secondary: #10B981 (Green)
  - Dark: #1F2937
  - Light: #F9FAFB
- **타이포그래피**:
  - 헤딩: 'Poppins' 또는 'Inter'
  - 본문: 'Roboto' 또는 'Open Sans'
- **간격**: TailwindCSS 기본 spacing 활용
- **반응형 브레이크포인트**:
  - sm: 640px
  - md: 768px
  - lg: 1024px
  - xl: 1280px

## 🚀 주요 기능
1. **반응형 디자인**: 모든 디바이스에서 최적화된 뷰
2. **부드러운 스크롤**: 네비게이션 클릭 시 해당 섹션으로 이동
3. **애니메이션**: 스크롤 시 요소 등장 효과
4. **다크모드**: 사용자 선호에 따른 테마 전환 (선택사항)
5. **인터랙티브 요소**: 호버 효과, 클릭 효과

## 📚 참고 자료
- [TailwindCSS 공식 문서](https://tailwindcss.com/docs)
- [MDN Web Docs](https://developer.mozilla.org/)
- 포트폴리오 디자인 영감: Dribbble, Behance

## ✅ 완료 기준
- [ ] 모든 섹션 구현 완료
- [ ] 반응형 디자인 적용
- [ ] 크로스 브라우저 호환성 확인
- [ ] 성능 최적화 완료
- [ ] 배포 완료
- [ ] README.md 문서 작성

## 🎯 다음 단계 (향후 개선)
- 블로그 섹션 추가
- 다국어 지원
- 방문자 통계
- 컨택 폼 백엔드 연동
