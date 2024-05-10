# Astro Starter Template: MINIMAL

A very minimal starter template with some CSS resets. Note this template uses vanilla CSS.

There are no dependecies in this template so that it is fully customisable.

To use this template do the following:

1. clone to repo
2. `cd` into the repo
3. run `npm install`
4. I have set a ludicurous background `color` and `background-color`. Change the color in the `base.css`file on lines `47-48` for a sanity check that CSS is running as it should.

## 🚀 Project Structure

Inside this template Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│   │    └── index.astro
│   └── styles/
│        └── base.css
│        └── main.css
│        └── typography.css
│        └── variables.css
└── package.json
```

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

## Astro docs

Astro is awesome. Learn more by checking the [documentation](https://docs.astro.build).
