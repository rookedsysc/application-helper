## 디자인 가이드

### 1. 컬러 팔레트
- **Primary**: #2D6A4F (딥 그린) — 신뢰감, 안정감
- **Secondary**: #40916C (밝은 그린), #F9F9F9 (배경용 화이트)
- **Accent**: #FFD166 (포인트, 버튼 등)
- **Text**: #222831 (기본 텍스트), #6C757D (보조 텍스트)

### 2. 타이포그래피
- **한글**: Noto Sans KR, Pretendard, Apple SD Gothic Neo
- **영문**: Inter, Roboto
- **제목**: Bold, 20~28px
- **본문**: Regular, 14~16px
- **설명/보조**: Light, 12~14px

### 3. 버튼
- **Primary Button**: 딥 그린 배경, 흰색 텍스트, 라운드(6~8px)
- **Secondary Button**: 테두리만 딥 그린, 흰색 배경, 딥 그린 텍스트
- **Disabled**: #E0E0E0 배경, #B0B0B0 텍스트

### 4. 입력창 & 카드
- **입력창**: 라운드(6px), #F9F9F9 배경, #40916C 포커스 테두리
- **카드**: 흰색 배경, 그림자(약하게), 라운드(10px)

### 5. 아이콘
- 직관적이고 심플한 라인 아이콘 사용 (예: Tabler Icons, Material Icons)
- 주요 기능(분석, 업로드, 다운로드, 상태 등)에 일관된 아이콘 적용

### 6. 레이아웃
- **최대 폭**: 800~1000px, 중앙 정렬
- **상단 바**: 로고, 메뉴(지원 등록, 내역 관리 등)
- **카드/리스트**: 여백 충분히, 정보 구분 명확하게
- **모바일 대응**: 반응형 디자인 필수 (모바일/태블릿에서 주요 기능 사용 가능)

### 7. 접근성
- 색상 대비 충분히 확보 (WCAG AA 이상)
- 버튼/입력창 크기 최소 44px
- 폰트 크기 14px 이상
- 스크린리더를 위한 aria-label 등 적용

### 8. 기타
- **로딩/피드백**: 주요 액션(분석, 업로드, 저장 등) 시 스피너/토스트 메시지 제공
- **에러/성공 메시지**: 명확한 색상(빨강/초록)과 아이콘으로 구분
- **파일 업로드**: 드래그 앤 드롭 지원, 업로드 상태 표시