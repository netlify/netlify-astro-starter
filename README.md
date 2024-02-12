# Netlify Astro Starter

_This is [Astro's](https://astro.build) default starter site, ready to deploy to [Netlify](https://www.netlify.com/)._

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify/netlify-astro-starter)

## Working Locally

To work locally on a machine with Node.js v18 installed, clone the repository:

    git clone git@github.com:netlify/netlify-astro-starter.git

Change into the project directory and install the dependencies:

    cd netlify-astro-starter
    yarn install

Start the development server:

    yarn dev

The development site will be available at `http://localhost:4321`. Happy coding! 🚀

## About the Project

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

### Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Resources

For help with Astro, check out [the documentation](https://docs.astro.build) or jump into [Astro's Discord server](https://astro.build/chat). For help with Netlify, visit [the Netlify documentation](https://docs.netlify.com) or [Netlify's community forums](https://answers.netlify.com/).
