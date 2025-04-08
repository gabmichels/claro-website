# Claro Website

A modern, responsive website for Claro, an AI-powered translation app.

## 🚀 Project Structure

```
/
├── public/
│   ├── favicon.svg
│   └── privacy-policy.html
├── src/
│   ├── components/
│   │   ├── DownloadApp.astro
│   │   ├── Features.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   └── Pricing.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── features.astro (coming soon page)
│   │   ├── how-it-works.astro (coming soon page)
│   │   ├── help-center.astro (redirects to external site)
│   │   └── faq.astro (redirects to external site)
│   └── styles/
│       └── global.css
└── package.json
```

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

## 👀 Features

- Responsive design that works on all devices
- Modern, clean UI with smooth animations
- Integrated Tawk.to live chat widget
- External Help Center and FAQs hosted on tawk.to
- Privacy Policy page
- Pricing information
- Easy navigation with mobile support
- Download section for app store links

## 🛠️ Technologies Used

- [Astro](https://astro.build) - Fast, modern static site generator
- [TailwindCSS](https://tailwindcss.com) - Utility-first CSS framework
- [Tawk.to](https://tawk.to) - Live chat and Help Center integration

## 📝 Customization

- To update content, edit the relevant component files in `src/components/`
- To add new pages, create new `.astro` files in `src/pages/`
- To modify styles, edit `src/styles/global.css`
- To change images, replace the placeholder images with your own
- The privacy policy is in `public/privacy-policy.html`
- The Help Center and FAQs are hosted externally at Tawk.to: https://claro-ai.tawk.help/

## 📦 Deployment

This site can be deployed to any static hosting service:

1. Run `npm run build` to generate the production build
2. Upload the contents of the `dist` directory to your hosting service
3. Configure your domain and enjoy your new website!

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

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
