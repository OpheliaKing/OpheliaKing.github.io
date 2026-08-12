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

## 포함된 내용

- Experience: 라이펄스, 리본게임즈
- Education: 연성대 / 평촌정보산업고 / 정보처리기능사
- Projects: SHIN 덱빌딩, Multi Puzzle (2025Game)
- Contact: ophelia01@naver.com

- SHIN: https://github.com/OpheliaKing/2026_DeckBuilding
- Multi Puzzle: https://github.com/OpheliaKing/2025Game
- 영상: https://www.youtube.com/watch?v=8iVBcelnfdc
