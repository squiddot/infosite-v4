# info.leaderboards.gg - Info Site Subdomain
In progress new infosite with content management system.

### References

Our Other Repos:
- leaderboards.gg Main Site - https://github.com/leaderboardsgg/leaderboard-site
- leaderboards.gg Backend - https://github.com/leaderboardsgg/leaderboard-backend

Other Links:
- Discord - https://discord.leaderboards.gg

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Build Setup](#build-setup)

[//]: # (- [Status]&#40;#status&#41;)

[//]: # (- [Repo Structure]&#40;#repo-structure&#41;)
- [Strapi(Backend) Readme](#strapi-readme)
- [Nuxt Readme](#nuxt-readme)

## Introduction
Leaderboards.gg (lbgg) was sparked by the purchase of speedrun.com by the esports data analytics company Elo Entertainment.

In lbgg we see an opportunity to help the "Online and competitive retro gaming" (basically speedruns and scoreruns) community continue to grow and thrive with tools (a centralized website and database, an API, a smaller site for clear documentation) built to scale, on modern technologies, curated to what its users want, without it being monetized. Because its open source, the community owns it and can use it as they wish.

Because it is currently under construction (and in two separate repos), we are using this repo to represent the project as a whole.

## Technologies
- Frontend
  - Nuxt3
  - Vue3
  - Tailwind
- Backend
  - C#
  - ASP.NET Core
  - .NET 6.0
- Info site
  - Nuxt3
  - Vue3
  - Tailwind
  - GSAP

## Frontend Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run develop

# build for production and launch server
$ npm run build
$ npm run start

# I don't know what this does yet
$ npm run strapi
```

[//]: # (## Status)

[//]: # (Very under construction. Please excuse our mess.)

[//]: # (## Repo Structure )

# Strapi Readme

## 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project. Find the one that suits you on the [deployment section of the documentation](https://docs.strapi.io/developer-docs/latest/setup-deployment-guides/deployment.html).

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://docs.strapi.io) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>


# Nuxt Readme
## Nuxt 3 Minimal Starter

Look at the [nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
