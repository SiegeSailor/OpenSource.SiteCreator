# Site Creator

File structure:

```
├── articles/
│   ├── blog/
│   │   ├── [article].md
│   ├── notes/
│   │   ├── [category]/
│   │   │   ├── [article].md
├── configuration/
│   ├── credential.ts
│   ├── format.ts
│   ├── setup.ts
│   ├── ...
├── components/
├── hooks/
├── queries/
|── utils/
├── modules/
│   ├── [module]/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── queries/
│   │   |── utils/
├── pages/
│   ├── _app.scss
│   ├── _app.tsx
│   ├── _document.tsx
│   ├── global.scss
│   ├── index.tsx
│   ├── brief/
│   │   ├── index.tsx
│   ├── [route]/
│   │   ├── index.tsx
│   │   ├── index.scss
│   │   ├── [identity].tsx
├── public/
│   ├── files/
│   ├── fonts/
│   ├── images/
│   ├── favicon.ico
│   ├── robots.txt
│   ├── manifest.json
├── next-env.d.ts
├── package-lock.json
├── package.json
├── tsconfig.json
└── ...
```

## Document Format

There are a few features must be implemented for **Blog** and **Note**:

- Markdown parsing
- Mermaid charts
- Customized blocks
- Customized information section and fields
- Latex support
