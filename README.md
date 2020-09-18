# Next.js, TypeScript, Emotion and Netlify Egghead Course

The code in this repository is based on the following video course:
[Build a site from scratch with Next.js, TypeScript, Emotion and Netlify](https://egghead.io/playlists/build-a-blog-with-next-js-typescript-emotion-and-netlify-adcc)

```bash
npx create-nextjs-app my-nextjs-blog
touch tsconfig.json # in the my-nextjs-blog directory
npm run dev # this will now provide you with typescript setup instructions
yarn add --dev typescript @types/react @types/node # above cmd recommends this
npm run dev # this overwrites tsconfig.json with a project specific setup
vi tsconfig.json # set strict: true and strictNullChecks: true
mv index.js index.tsx # add title with ts const string and delete all but title
mv _app.js _app.tsx # restart dev server and import AppProps from "next/app"
vi styles/globals.css # change the font to "Comic Sans MS"
yarn add @emotion/core @emotion/styled
vi index.tsx # copy Home.module.css styles to <Container>, <Main>, <BlogTitle>
vi tsconfig.json # "baseUrl": "./", "paths": {"@components/*": ["components/*"]}
vi package.json # "export" : "next export"
```
