# 해외 기술 블로그 허브

전 세계 주요 테크 기업들의 최신 기술 블로그를 한국어로 제공하는 문서 사이트입니다.

## 주요 기능

- **21개 주요 기업** 기술 블로그 카테고리
- **N8N 자동화** 워크플로우 가이드
- **실시간 업데이트** RSS 피드 기반 자동 수집
- **한글 번역** 주요 아티클 한글 제공

## 포함된 기업

- Meta, Netflix, Airbnb, Spotify, GitHub
- Facebook, Instagram, Slack, Medium
- Cloudflare, Dropbox, Docker
- 그 외 다수 테크 기업

**[전체 블로그 보기](https://ghostflare76.github.io/engineering-rss/newsletters/)**

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
