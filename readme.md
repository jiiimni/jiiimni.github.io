# 이지민 포트폴리오

GitHub Pages에 올릴 수 있는 정적 포트폴리오 사이트입니다.

## 파일 구조

```text
index.html
styles.css
script.js
```

## 배포 확인

이 저장소는 GitHub Pages용 저장소입니다.

1. `main` 브랜치에 변경 사항을 push합니다.
2. 저장소의 `Settings > Pages`에서 `Deploy from a branch`가 켜져 있는지 확인합니다.
3. Branch는 `main`, 폴더는 `/root`로 설정합니다.
4. 잠시 후 `https://jiiimni.github.io`에서 확인할 수 있습니다.

## 수정할 곳

- 소개 문장: `index.html`의 `hero-description`, `about-section`
- 프로젝트: `index.html`의 `project-card`
- 색상: `styles.css`의 `:root` 변수
- 필터: `script.js`와 각 프로젝트 카드의 `data-category`
