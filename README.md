# 작품 아카이브 (배너 포함)
이 저장소는 제공하신 사진과 문구를 사용해 만든 **반응형 웹 배너** 템플릿입니다.

## 파일 구조
```
story_site/
 ├── index.html
 ├── styles.css
 └── assets/
     └── banner.jpg  (제공 이미지 복사본)
```

## 로컬 미리보기
1) 폴더를 압축 해제한 뒤, `index.html`을 브라우저로 열면 끝입니다.
2) 더 편하게 보려면 VS Code의 Live Server 확장이나 간단한 HTTP 서버를 사용하세요.

## 배포 (둘 중 선택)
- **GitHub Pages**
  1. GitHub에 새 Repo 만들기 → 이 폴더 전체 업로드
  2. Repo → Settings → Pages → Branch: `main` → `/ (root)` 저장
  3. 몇 분 뒤 발급된 URL에서 접속
- **Vercel/Netlify**
  - 새 프로젝트로 `story_site` 폴더 업로드 → 자동 배포

## 문구/이미지 교체
- 텍스트: `index.html`의 `<p class="lead">...</p>` 수정
- 이미지: `assets/banner.jpg` 교체 (가로 1920px 내외 권장)

## 디자인 포인트
- 텍스트 가독성을 위한 **그라데이션 오버레이**
- 모바일/데스크탑 대응 **반응형 레이아웃**
- 외부 폰트 없이도 깔끔한 **시스템 글꼴 폴백**
