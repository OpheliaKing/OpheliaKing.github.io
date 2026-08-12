# GitHub Pages Portfolio

정적 1페이지 포트폴리오입니다. Notion/AI 없이 HTML만 수정하면 됩니다.

## 로컬 확인

`portfolio-site/index.html`을 브라우저로 열거나:

```bash
cd portfolio-site
npx --yes serve .
```

## 배포 (추천: 전용 레포)

1. GitHub에서 새 레포 생성: `OpheliaKing.github.io` (유저페이지)  
   또는 `portfolio` 같은 프로젝트 페이지 레포
2. 이 폴더 내용만 푸시

```bash
cd portfolio-site
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/OpheliaKing/OpheliaKing.github.io.git
git push -u origin main
```

3. 레포 **Settings → Pages → Branch: main / root** 저장  
4. 접속: `https://opheliaking.github.io/`

프로젝트 페이지 레포(`portfolio`)를 쓰면 URL은  
`https://opheliaking.github.io/portfolio/` 형태입니다.

## 수정할 곳

`index.html`에서 `<!-- TODO -->` 검색:

- Experience (회사/기간/업무)
- Contact 이메일
- 추가 프로젝트 카드

덱빌딩 프로젝트 링크는 이미 연결되어 있습니다.

- GitHub: https://github.com/OpheliaKing/2026_DeckBuilding
- 영상: https://www.youtube.com/watch?v=8iVBcelnfdc
