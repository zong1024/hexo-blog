# zong1024's Blog

Hexo + Fluid blog, deployed to `http://202.60.232.93`.

## Local development

```bash
npm install
npm run server
```

## Build

```bash
npm run clean
npm run build
```

## Content

- Posts: `source/_posts`
- Pages: `source/about`, `source/archives`, `source/categories`, `source/tags`
- Theme config override: `_config.fluid.yml`

## Server deploy

The static site is generated into `public/` and served by Nginx on the server.
