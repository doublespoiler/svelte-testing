# SvelteKit starter template

*Note: This is a work in progress personal project. Use it at your own risk.*

[![twitter](https://badgen.net/twitter/follow/veniplexx?icon=twitter)](https://twitter.com/veniplexx)
![contributors](https://badgen.net/github/contributors/veniplex/sveltekit-starter?color=gray&icon=github)
![stars](https://badgen.net/github/stars/veniplex/sveltekit-starter?color=gray&icon=github)
![watchers](https://badgen.net/github/watchers/veniplex/sveltekit-starter?color=gray&icon=github)
![forks](https://badgen.net/github/forks/veniplex/sveltekit-starter?color=gray&icon=github)
![license](https://badgen.net/github/license/veniplex/sveltekit-starter?color=gray&icon=github)

[![latest release](https://badgen.net/github/release/veniplex/sveltekit-starter?color=purple&icon=github)](https://github.com/veniplex/sveltekit-starter/releases)
[![open issues](https://badgen.net/github/open-issues/veniplex/sveltekit-starter?color=yellow&icon=github)](https://github.com/veniplex/sveltekit-starter/issues/)
[![open prs](https://badgen.net/github/open-prs/veniplex/sveltekit-starter?color=yellow&icon=github)](https://github.com/veniplex/sveltekit-starter/pulls?q=is%3Apr+is%3Aopen)

[![sveltekit version](https://badgen.net/badge/SvelteKit/1.0.0-next.538/purple)](https://github.com/sveltejs/kit/blob/master/packages/kit/CHANGELOG.md#100-next538)

# Table of contents

- [Description](#description)  
- [Different Branches](#different-branches)
- [Installation with degit](#installation-with-degit)  
- [Start the app](#start-the-app)  
- [Build the app](#build-the-app)  

# Description

Use this repository as a [SvelteKit](https://kit.svelte.dev/) starter template for your project. This template includes the following add-ons and configurations in every branch:
- TypeScript
- Prettier
- ESLint

# Different Branches

There are different branches with different add-ons. The following branches are available:
- [`main`](https://github.com/veniplex/sveltekit-starter/tree/main) - clean template without any additional add-ons (except those mentioned above)
- [`tailwind`](https://github.com/veniplex/sveltekit-starter/tree/tailwind) - includes TailwindCSS

# Installation with [degit](https://github.com/Rich-Harris/degit)

1. Install degit:
    ```bash
    npm install -g degit
    ```
2. Get this starter template:
    ```bash
    degit veniplex/sveltekit-starter [your-project-name]
    ```
3. Navigate to your project folder:
    ```bash
    cd [your-project-name]
    ```
4. Install all dependencies:
    ```bash
    npm install
    ```

# Start the app

To start your app in dev mode:

```bash
# start only the dev server
npm run dev
```
```bash
# or also open the app
npm run dev -- --open
```

# Build the app

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with:
```bash
npm run preview
```

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

---

### TODO:
- Add requirements like NodeJS
