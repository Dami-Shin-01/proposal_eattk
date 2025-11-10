# EATTK 웹사이트 리뉴얼 제안서

**잇테이블코리아 웹사이트 리뉴얼 전략 제안서 - HTML 프레젠테이션**

제안일: 2025년 11월 10일
제안자: 디온닷
기술: Reveal.js, Chart.js, Pretendard Font

---

## 📋 목차

1. [프로젝트 개요](#프로젝트-개요)
2. [시작하기](#시작하기)
3. [슬라이드 구성](#슬라이드-구성)
4. [자산 교체 가이드](#자산-교체-가이드)
5. [커스터마이징](#커스터마이징)
6. [PDF 출력](#pdf-출력)
7. [배포하기](#배포하기)
8. [문제 해결](#문제-해결)

---

## 🎯 프로젝트 개요

이 프로젝트는 EATTK 웹사이트 리뉴얼을 위한 전략 제안서로, Reveal.js를 사용한 인터랙티브 HTML 프레젠테이션입니다.

### 주요 특징

- ✅ 12장의 완성도 높은 슬라이드
- ✅ 인터랙티브 차트 (Chart.js)
- ✅ 반응형 디자인 (모바일/태블릿/데스크톱)
- ✅ PDF 출력 지원
- ✅ 키보드 네비게이션
- ✅ 디자인 가이드라인 완벽 반영

### 기술 스택

- **Reveal.js 5.0.4** - HTML 프레젠테이션 프레임워크
- **Chart.js 4.4.0** - 데이터 시각화
- **Pretendard Font** - 한글 웹폰트
- **HTML5 / CSS3 / JavaScript**

---

## 🚀 시작하기

### 1. 파일 구조

```
eattk-proposal/
├── index.html          # 메인 프레젠테이션 파일
├── css/
│   └── custom.css      # 커스텀 스타일
├── js/
│   └── main.js         # JavaScript 로직
├── assets/
│   └── images/         # 이미지 리소스
└── README.md           # 이 파일
```

### 2. 로컬에서 실행하기

#### 방법 1: 브라우저에서 직접 열기

1. `index.html` 파일을 더블클릭
2. 브라우저에서 자동으로 열림

#### 방법 2: 로컬 서버 사용 (권장)

**Node.js가 설치된 경우:**

```bash
# 프로젝트 디렉토리로 이동
cd eattk-proposal

# 간단한 HTTP 서버 실행
npx http-server -p 8080

# 또는
npx serve
```

**Python이 설치된 경우:**

```bash
# Python 3.x
python -m http.server 8080

# Python 2.x
python -m SimpleHTTPServer 8080
```

브라우저에서 `http://localhost:8080` 접속

#### 방법 3: VS Code Live Server

1. VS Code에서 프로젝트 폴더 열기
2. Live Server 확장 프로그램 설치
3. `index.html`에서 우클릭 → "Open with Live Server"

### 3. 키보드 단축키

| 키 | 동작 |
|---|---|
| `→` / `↓` | 다음 슬라이드 |
| `←` / `↑` | 이전 슬라이드 |
| `Space` | 다음 슬라이드 |
| `ESC` / `O` | 슬라이드 오버뷰 |
| `F` | 전체화면 토글 |
| `P` | PDF 출력 |
| `Home` | 첫 슬라이드 |
| `End` | 마지막 슬라이드 |

---

## 📊 슬라이드 구성

### Slide 1: 표지
- EATTK 로고
- 제안 정보

### Slide 2: Executive Summary
- 프로젝트 목표
- 3가지 문제점
- 3가지 솔루션
- 제안 조건

### Slide 3: 현황 분석 - 성능 진단
- PageSpeed Insights 결과
- 모바일/데스크톱 성능
- 비즈니스 임팩트
- 개선 목표

### Slide 4: 경쟁사 벤치마킹
- 기프트럭 vs EATTK 비교
- 정량 비교 테이블
- 핵심 차이점

### Slide 5: 솔루션 제안
- 3단계 개선 전략
- 기술 기반 마련
- 디자인 차별화
- 전환 최적화

### Slide 6: 기술 스택 & 차별점
- Next.js 기반 아키텍처
- WordPress 대비 장점
- 클라이언트 이점

### Slide 7: 페이지 구성 & F&B 메뉴
- 사이트맵
- F&B 메뉴 서비스 상세
- 반응형 그리드

### Slide 8: 작업 프로세스
- 협업 프로세스
- 소통 채널
- 빠른 의사결정 원칙

### Slide 9: 6주 상세 일정
- 주차별 타임라인
- 마일스톤
- 체크포인트

### Slide 10: 투자 대비 효과
- ROI 시뮬레이션
- 투자 회수 계산
- 예상 누적 효과 (인터랙티브 차트)
- 정성적 가치

### Slide 11: 포트폴리오 & 역량
- 디온닷의 차별화 포인트
- 디자인 역량
- 마케팅 이해도
- 클라이언트 코멘트

### Slide 12: Next Steps
- 계약 조건 요약
- 진행 프로세스
- 클라이언트 준비 사항
- 연락처

---

## 🖼️ 자산 교체 가이드

현재 프레젠테이션에는 플레이스홀더가 사용되고 있습니다. 실제 이미지로 교체하는 방법을 안내합니다.

### 필요한 자산 목록

#### 1. 로고 및 브랜드 이미지
- **EATTK 로고** (PNG, SVG)
  - 위치: Slide 1 (표지)
  - 권장 크기: 300x300px 이상
  - 배경: 투명 또는 흰색

#### 2. 성능 분석 스크린샷
- **PageSpeed Insights 스크린샷**
  - 위치: Slide 3 (성능 진단)
  - 권장 크기: 1200x800px
  - 포맷: PNG

#### 3. 경쟁사 비교 스크린샷
- **EATTK 히어로 섹션 캡처**
  - 위치: Slide 4 (경쟁사 벤치마킹)
  - 권장 크기: 1200x800px
- **기프트럭 히어로 섹션 캡처**
  - 위치: Slide 4 (경쟁사 벤치마킹)
  - 권장 크기: 1200x800px

#### 4. F&B 메뉴 이미지
- **음식 사진 (여러 장)**
  - 위치: Slide 7 (페이지 구성 & F&B 메뉴)
  - 권장 크기: 600x400px
  - 포맷: JPG, PNG

#### 5. SNS 포트폴리오 샘플
- **SNS 콘텐츠 디자인 샘플 (3-4개)**
  - 위치: Slide 11 (포트폴리오)
  - 권장 크기: 400x400px (정사각형)
  - 포맷: JPG, PNG

### 이미지 교체 방법

#### 방법 1: HTML 직접 수정

1. `index.html` 파일을 텍스트 에디터로 엽니다
2. 플레이스홀더를 찾습니다 (예: `[EATTK 로고]`)
3. 다음과 같이 이미지 태그로 교체합니다:

```html
<!-- 변경 전 -->
<div class="logo-placeholder">[EATTK 로고]</div>

<!-- 변경 후 -->
<div class="logo-placeholder">
    <img src="assets/images/eattk-logo.png" alt="EATTK 로고" style="max-width: 300px;">
</div>
```

#### 방법 2: CSS 배경 이미지 사용

1. 이미지를 `assets/images/` 폴더에 저장
2. `css/custom.css` 파일에서 스타일 추가:

```css
.logo-placeholder {
    background-image: url('../assets/images/eattk-logo.png');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
    min-height: 200px;
}
```

### 자주 교체해야 할 플레이스홀더

#### Slide 1 - 표지
```html
<!-- 검색: [EATTK 로고] -->
<img src="assets/images/eattk-logo.png" alt="EATTK 로고">
```

#### Slide 3 - 성능 진단
```html
<!-- 검색: PageSpeed -->
<img src="assets/images/pagespeed-screenshot.png" alt="PageSpeed 결과">
```

#### Slide 4 - 경쟁사 벤치마킹
```html
<!-- 검색: [EATTK 히어로 섹션 캡처] -->
<img src="assets/images/eattk-hero.png" alt="EATTK 웹사이트">

<!-- 검색: [기프트럭 히어로 섹션 캡처] -->
<img src="assets/images/giftluck-hero.png" alt="기프트럭 웹사이트">
```

#### Slide 7 - F&B 메뉴
```html
<!-- 검색: [음식 이미지] -->
<img src="assets/images/menu-tteokbokki.jpg" alt="떡볶이 세트">
```

#### Slide 11 - 포트폴리오
```html
<!-- 검색: [SNS 포트폴리오 샘플] -->
<img src="assets/images/portfolio-1.jpg" alt="포트폴리오 샘플">
```

### 연락처 정보 업데이트

#### Slide 1 & 12
```html
<!-- 검색: [이메일] -->
<p>연락처: contact@deondot.com</p>

<!-- 검색: [ID] -->
<p>💬 카카오톡: deondot</p>

<!-- 검색: [전화번호] -->
<p>📱 전화: 010-1234-5678</p>
```

---

## 🎨 커스터마이징

### 컬러 변경

`css/custom.css` 파일 상단의 CSS 변수를 수정하세요:

```css
:root {
    --primary: #2B5BBA;      /* 주요 색상 */
    --secondary: #FF6B35;    /* 보조 색상 */
    --accent: #4ECDC4;       /* 강조 색상 */
    --background: #F7F9FC;   /* 배경 색상 */
    --text: #2D3436;         /* 텍스트 색상 */
    --success: #00D98C;      /* 성공 색상 */
    --warning: #FFB020;      /* 경고 색상 */
    --error: #FF3B3B;        /* 에러 색상 */
}
```

### 폰트 변경

현재 Pretendard 폰트를 사용 중입니다. 다른 폰트로 변경하려면:

```css
/* css/custom.css */
.reveal {
    font-family: '원하는폰트', -apple-system, BlinkMacSystemFont, system-ui, sans-serif;
}
```

### ROI 차트 데이터 수정

`js/main.js` 파일에서 차트 데이터를 수정할 수 있습니다:

```javascript
const data = {
    labels: ['1개월', '2개월', '3개월', '6개월', '12개월'],
    datasets: [
        {
            label: '현재 상황',
            data: [1500, 3000, 4500, 9000, 18000], // 만원 단위
            // ...
        },
        // ...
    ]
};
```

### 슬라이드 전환 효과 변경

`js/main.js` 파일에서 Reveal.js 설정을 수정:

```javascript
Reveal.initialize({
    transition: 'slide', // none/fade/slide/convex/concave/zoom
    transitionSpeed: 'default', // default/fast/slow
    // ...
});
```

---

## 📄 PDF 출력

### 방법 1: 브라우저 인쇄 기능

1. 프레젠테이션을 브라우저에서 엽니다
2. `P` 키를 누르거나 `Ctrl+P` (Windows) / `Cmd+P` (Mac)
3. 인쇄 설정:
   - **대상**: PDF로 저장
   - **레이아웃**: 가로
   - **여백**: 없음
   - **배경 그래픽**: 켜기
4. "저장" 클릭

### 방법 2: Reveal.js PDF 출력 모드

1. URL에 `?print-pdf` 추가:
   ```
   http://localhost:8080/index.html?print-pdf
   ```
2. 페이지가 로드되면 `Ctrl+P` / `Cmd+P`
3. PDF로 저장

### PDF 출력 팁

- 각 슬라이드가 한 페이지에 맞도록 설정되어 있습니다
- 배경 그래픽을 반드시 활성화하세요
- 인쇄 미리보기에서 모든 슬라이드가 보이는지 확인하세요

---

## 🌐 배포하기

### Vercel (추천)

1. GitHub에 프로젝트 업로드
2. [Vercel](https://vercel.com) 접속 및 로그인
3. "New Project" 클릭
4. GitHub 저장소 선택
5. "Deploy" 클릭
6. 몇 초 후 URL 생성 완료

### Netlify

1. [Netlify](https://www.netlify.com) 접속 및 로그인
2. "Add new site" → "Import an existing project"
3. GitHub 저장소 선택
4. "Deploy site" 클릭

### GitHub Pages

1. GitHub 저장소의 Settings → Pages
2. Source: `main` 브랜치 선택
3. 폴더: `/ (root)` 선택
4. "Save" 클릭
5. `https://<username>.github.io/<repository-name>` 에서 접속

### 단순 호스팅

`eattk-proposal` 폴더 전체를 웹 호스팅 서버에 업로드하면 됩니다.

---

## 🔧 문제 해결

### 문제: 폰트가 제대로 표시되지 않음

**해결책**:
- 인터넷 연결을 확인하세요 (Pretendard 폰트가 CDN에서 로드됩니다)
- 로컬 폰트 파일을 다운로드하여 사용하세요

### 문제: 차트가 표시되지 않음

**해결책**:
- 브라우저 콘솔(F12)에서 에러 확인
- Chart.js CDN이 정상적으로 로드되는지 확인
- 로컬 서버를 사용하여 실행 (직접 파일 열기 대신)

### 문제: 이미지가 표시되지 않음

**해결책**:
- 이미지 경로가 올바른지 확인 (`assets/images/파일명.png`)
- 파일 이름 대소문자 확인 (Linux 서버는 대소문자 구분)
- 로컬 서버를 사용하여 실행

### 문제: PDF 출력 시 배경색이 없음

**해결책**:
- 인쇄 설정에서 "배경 그래픽" 옵션 활성화
- Chrome: 더보기 옵션 → 배경 그래픽 체크
- Firefox: 페이지 설정 → 배경색 및 이미지 인쇄 체크

### 문제: 모바일에서 레이아웃이 깨짐

**해결책**:
- 반응형 디자인이 적용되어 있지만, 프레젠테이션은 데스크톱/태블릿 최적화
- 모바일에서는 가로 모드로 보는 것을 권장
- 필요시 `css/custom.css`의 미디어 쿼리 조정

---

## 📞 지원 및 문의

제안서에 대한 문의사항이나 기술적 문제가 있다면 연락주세요:

- **이메일**: [이메일 주소]
- **카카오톡**: [카카오톡 ID]
- **전화**: [전화번호]

---

## 📝 라이선스

이 프로젝트는 EATTK 웹사이트 리뉴얼 제안을 위해 제작되었습니다.

### 사용된 오픈소스 라이브러리

- [Reveal.js](https://revealjs.com/) - MIT License
- [Chart.js](https://www.chartjs.org/) - MIT License
- [Pretendard Font](https://github.com/orioncactus/pretendard) - SIL Open Font License

---

## 🎉 프로젝트 체크리스트

제안서 전달 전 확인사항:

- [ ] 모든 플레이스홀더를 실제 이미지로 교체
- [ ] 연락처 정보 업데이트 (Slide 1, 12)
- [ ] 로컬에서 모든 슬라이드 정상 작동 확인
- [ ] 차트가 올바르게 표시되는지 확인
- [ ] PDF 출력 테스트
- [ ] 모바일/태블릿에서 확인
- [ ] 오타 및 내용 최종 검토
- [ ] 배포 URL 확인 (필요시)

---

**제작일**: 2025년 11월 10일
**버전**: 1.0.0
**제작자**: 디온닷
