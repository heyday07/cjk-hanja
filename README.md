# 삼국한자 · CJK Characters · 日中韓漢字 · 中日韓漢字

> **한 · 중 · 일 한자 비교 사전 + SRS 학습 앱** — Play Store 공개 페이지

이 저장소는 **삼국한자 (CJK Characters)** 앱의 개인정보처리방침을 GitHub Pages 로 호스팅합니다.

## 🔗 Privacy Policy URL — Play Console 등록용 풀네임

각 locale 별 풀 URL (Play Console 의 "다국어 등록정보 > 개인정보처리방침" 칸에 그대로 사용):

| Locale | Full URL |
|---|---|
| 🇰🇷 한국어 (ko) | <https://heyday07.github.io/cjk-hanja/privacy-ko.html> |
| 🇺🇸 English (en) | <https://heyday07.github.io/cjk-hanja/privacy-en.html> |
| 🇯🇵 日本語 (ja) | <https://heyday07.github.io/cjk-hanja/privacy-ja.html> |
| 🇹🇼 繁體中文 (zh-TW) | <https://heyday07.github.io/cjk-hanja/privacy-zh.html> |

각 풀네임 페이지는 즉시 메인 `index.html` 로 redirect 되며 해당 locale 섹션이 활성화됩니다.

## 🏗️ 구조

실제 콘텐츠는 **단일 파일** `index.html` 하나에 모두 들어있고 (4 locale × 13 조항 = 약 49KB), 상단 sticky 버튼 4개로 locale 을 전환합니다.

```
cjk-hanja/
├── index.html         ← 실제 콘텐츠 (단일 파일, 4 locale 통합)
├── privacy-ko.html    ← 한국어 풀네임 (index.html?lang=ko 로 redirect)
├── privacy-en.html    ← 영어 풀네임
├── privacy-ja.html    ← 일본어 풀네임
├── privacy-zh.html    ← 번체중국어 풀네임
└── README.md
```

`index.html` 직접 진입 시 (`https://heyday07.github.io/cjk-hanja/`) `navigator.language` 자동 감지로 ko/en/ja/zh 중 적합한 섹션을 표시합니다. URL `?lang=xx` 쿼리로 강제 가능.

## 📱 앱 정보

- **개발사**: RedMoon Studio
- **이메일**: teamstar13000@gmail.com
- **패키지명**: `com.redmoon.cjkhanja`
- **지원 언어**: 한국어 · 영어 · 일본어 · 번체중국어
- **버전**: v1.0.0+1 (2026-05-18)

## 📄 라이선스

이 페이지의 콘텐츠 © 2026 RedMoon Studio. All rights reserved.
