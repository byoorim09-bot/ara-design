# 아라광고 · ARA DESIGN

아라광고 상세페이지 제작 웹앱(한 장짜리 HTML)입니다.

- 주소: https://byoorim09-bot.github.io/ara-design/
- 파일: `index.html` — 스타일·스크립트·폰트 로딩이 모두 이 한 파일 안에 있습니다.
  (`opentype.js`만 cdn.jsdelivr.net에서 불러옵니다.)

## 홈 화면 아이콘

`manifest.webmanifest` + 아래 아이콘 파일로 휴대폰 홈 화면에 추가했을 때 앱처럼 뜹니다.
(아이콘 원본: 네이비 바탕에 금색 '아라' — 검은 모서리를 지워 정사각으로 편집한 것)

| 파일 | 크기 | 쓰는 곳 |
|---|---|---|
| `apple-touch-icon.png` | 180×180 | 아이폰 홈 화면 |
| `icon-192.png` | 192×192 | 안드로이드 홈 화면(작은 크기) |
| `icon-512.png` | 512×512 | 안드로이드 홈 화면(큰 크기)·설치 배너 |
| `favicon.png` | 64×64 | 브라우저 탭 아이콘 |
| `favicon.ico` | 16·32·48 | 옛 브라우저·윈도 바탕화면 바로가기 |

## 사용

위 주소를 열면 바로 실행됩니다. 설치나 서버가 필요 없습니다.
사진·글자는 브라우저 안에서만 처리되고 어디로도 전송되지 않습니다.

## 고칠 때

이 저장소는 두 브랜치를 씁니다.

- `main` — 원본 소스
- `gh-pages` — 실제로 배포되는 브랜치 (GitHub Pages가 이 브랜치를 보고 있음)

수정한 파일은 **`main`과 `gh-pages` 양쪽에** 올려야 사이트에 반영됩니다.

```bash
git add -A && git commit -m "수정 내용"
git push origin main
git push origin main:gh-pages
```
