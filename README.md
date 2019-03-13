## Akagi's SSR + Typescript Starter

- [React](https://reactjs.org/docs/getting-started.html)
- [Next.js](https://nextjs.org/)
- [Typescript](https://www.typescriptlang.org/docs/home.html)
- [Styled Components](https://www.styled-components.com/)

### Requirements
- node -v `v10.11.0`
- npm -v `6.9.0`

## Quick Start

Install Dependencies
```
npm i
```

Run Dev Server
```
npm run dev
```

## Deployment

This repo is configured to deploy easily to Heroku via these two lines in the `package.json`.
```
{
...
  "start": "NODE_ENV=production node ./server/index.js -p $PORT",
  "heroku-postbuild": "npm run build"
}
```
