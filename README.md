# My Portfolio Website

Template based off of https://github.com/manuelernestog/astrofy

## Installation

Run the following command in your terminal

```bash
npm install
```

Once the packages are installed astro comes with a built-in development server that has everything you need for project development. The astro dev command will start the local development server so that changes to the website are updated in real time locally.

```bash
npm run dev
```

## Tech Stack

- [Astro](https://astro.build)
- [tailwindcss](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)

### Site config

Global site configuration lives in the '/src/config.ts' file:

- **SITE_TITLE**: Default pages title.
- **SITE_DESCRIPTION**: Default pages title.
- **GENERATE_SLUG_FROM_TITLE**: By default Astrofy will generate the blog slug pages base on the article name. Set this var to false if I want to use the Astro file base (Compatible with Astrofy older versions).
- **TRANSITION_API**: Enable and disable transition API

### Theming

Template theme is controlled the `data-theme` attribute of the `<html>` tag in `BaseLayout.astro` file.

Default themes available [here](https://daisyui.com/docs/themes/). Custom themes are also possible.

## Deploy

The website is hosted with GitHub pages. See the [official Astro documentation](https://docs.astro.build/en/guides/deploy/github/) for details
