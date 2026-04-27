# Astro Starter Kit: Minimal

```sh
npm create astro@latest -- --template minimal
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## ▲ Deploy on Vercel

This Astro project lives in the `site/` subfolder of the repo. When importing into Vercel:

1. **Import** the GitHub repo into Vercel.
2. Set **Root Directory** to `site`. Framework preset is auto-detected as Astro.
3. Leave **Build Command** (`astro build`) and **Output Directory** (`dist`) at their defaults — they're also pinned in `vercel.json`.
4. **Node version** is pinned via `.nvmrc` (22.12.0).

No SSR adapter is needed — the site builds to fully static HTML.

Local Vercel CLI deploys:

```sh
npm i -g vercel
vercel link        # link the local site/ folder to a Vercel project
vercel             # preview deploy
vercel --prod      # production deploy
```
