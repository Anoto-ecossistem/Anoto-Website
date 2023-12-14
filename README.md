<h1 align="center"> Anoto Website</h1>

## Installation

1. Clone the repository:

```bash
$ git clone https://github.com/MatheusAlvesPereira/Anoto-Website.git
```

2. run `pnpm install`
3. If you want to switch to npm make sure to remove pnpm-lock.yaml and node_modules folder and then run `npm install`

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `pnpm install`         | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |

### Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   ├── locales/
│   ├── middleware/
│   ├── pages/
│   ├── styles/
│   ├── utils/
│   └── consts.ts/
├── astro.config.mjs
├── README.md
├── package.json
├── .prettierrc
├── tailwind.config.cjs
└── tsconfig.json
```

This project use the template [Astro-starter](https://github.com/zankhq/astro-starter)

### About Astro.js...

Check out [Astro documentation](https://docs.astro.build) 

### Check the AnotoApp...

[AnotoApp](https://github.com/MatheusAlvesPereira/Anoto-App)