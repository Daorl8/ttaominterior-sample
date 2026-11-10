# STRUCTURE · ttaominterior-sample (v0.1)

```
ttaominterior-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인 · 모바일 메뉴 · 리빌 · 앵커 스크롤)
├─ wrangler.toml              name = ttaominterior-sample → ttaominterior-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ tt-cormorant.woff2         워드마크 · 영문 라벨 (Cormorant Garamond 400–600, 라틴)
├─ tt-pretendard.woff2        한글 · 본문 (Pretendard 300–600, 쓰는 글자만)
├─ tt-hero.webp               히어로
├─ tt-work-01 ~ 12.webp       Portfolio 갤러리
├─ favicon.png · og-ttaom.jpg
├─ img/                       다올 제공 원본 57장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 모바일 메뉴 `#m-nav`) → 히어로 → `#works`(띠색 · 갤러리 + 최근 시공 목록) → `#services` → `#contact`(먹 띠) → `#stores`(띠색 · 매장 2 + 지도 2) → 푸터 + 모바일 `.quick`.

## 연락 채널
온라인 견적문의 `naver.me/IDFTjpAU`(헤더 · 히어로 · 상담 · 하단 바) · 전화 `010-8321-6666` · 인스타 · 블로그 · 오늘의집.

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27). 오시는 길 R-1(모바일 지도 1열 전체 폭).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). Cormorant는 영문에만.
