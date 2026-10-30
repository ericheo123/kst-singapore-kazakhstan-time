# KST Singapore & Kazakhstan Time

한국 시간을 기준으로 싱가포르와 카자흐스탄의 현재 시간 및 근무시간 겹침을 보여주는 별도 사이트입니다.

## Features

- 서울 시간을 기준 시계로 상단에 고정
- 각 국가 현지 시간과 날짜를 1초마다 자동 갱신
- 한국 대비 시차를 자연어로 표시
- 한국 09:00–18:00 기준 시간대별 현지 근무시간 비교
- 현지 근무시간과 겹치는 구간 강조 표시
- GitHub Pages 배포용 GitHub Actions 포함

## Local Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy

`main` 브랜치에 푸시하면 `.github/workflows/deploy.yml`을 통해 GitHub Pages로 배포됩니다.

