# ZJU_Summer_School Demo Project

## How to run
构建项目时请使用nodejs 18版本及以上，推荐使用pnpm作为包管理工具。
- requirements
  - nodejs@18 https://nodejs.org/en/download
  - pnpm https://pnpm.io/installation

- setup project
  ```shell
  pnpm install
  ```

- run dev server
  ```shell
  pnpm run dev
  ```

- open webpage http://localhost:5173/


## Project Structure

- `package.json` - Project dependencies and scripts
- `public/` - Public assets (vis data or some big files)
- `src/`'
  - `assets/` - Static assets like images and styles
  - `components/` - Vue components
  - `pages/` - Vue pages for different routes
  - `router.ts` - Vue Router configuration
  - `main.ts` - Entry point to load vue app
  - `App.vue` - Main vue component
  - `data.ts` - Handle data fetch
  - `models.ts` - Define data models in ts type

## Tip
该项目为2025年浙江大学暑期学校(课程综合实践I) project2 的demo项目，主要用于展示如何使用Vue3+Vite+TypeScript进行前端开发。
注意视图的设计以及数据处理与可视化设计无关，该项目仅用于展示前端开发的基本流程和结构。
