# EPUB 3.0 eBook Creator

이 프로젝트는 Sigil 등 주요 에디터에서 완벽하게 작동하는 EPUB 3.0 이상 전자책을 쉽고 빠르게 제작할 수 있는 데스크탑 프로그램입니다.

## 프로젝트 구조

```
OEBPS/
├── Text/
│   ├── page1.xhtml
│   └── page2.xhtml
├── Styles/
│   ├── sgc-nav.css
│   └── style1.css
├── Images/
├── Fonts/
├── Audio/
├── Video/
├── Misc/
│   └── script1.js
└── content.opf
```

- **Text**: 본문 페이지 (XHTML)
- **Styles**: CSS 스타일시트
- **Images**: 이미지 리소스
- **Fonts**: 폰트 리소스
- **Audio**: 오디오 리소스
- **Video**: 비디오 리소스
- **Misc**: 기타 리소스 (JavaScript 등)
- **content.opf**: eBook 메타데이터 및 매니페스트

## 주요 기능

- EPUB 3.0 이상 지원
- Sigil 호환 구조 자동 생성
- WYSIWYG 편집기
- 미리보기 및 검증
- 내보내기/가져오기
- 다국어 및 접근성 지원

## 기술 스택

- **프론트엔드:** Electron + React
- **백엔드:** Node.js
- **EPUB 라이브러리:** node-epub, epub.js

## 시작하기

1. 저장소 클론
2. 의존성 설치: `npm install`
3. 개발 서버 실행: `npm start`

## 라이선스

MIT 

by sun4