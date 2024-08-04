# Astro Starter

My lightweight Astro starter template

Demo: https://lokimckay.github.io/astro-starter/

## Features

- [Dark/light mode toggle](https://docs.astro.build/en/tutorial/6-islands/2/)
- [Emoji favicon](https://css-tricks.com/emoji-as-a-favicon/)
- [Fixel font](https://fixel.macpaw.com/)
- TS config `"@/*": ["./src/*"]` path mapping
- [View transitions](https://docs.astro.build/en/guides/view-transitions/)
- Github pages deployment

## Usage

1. `npx degit lokimckay/astro-starter my-new-project`
1. `cd my-new-project`
1. `npm install`
1. `npm start`

## Optional next steps

### Add preact integration

https://docs.astro.build/en/guides/integrations-guide/preact/

### Remove github pages deployment

1. Delete `.github` directory
1. Remove `site` and `base` configuration from `astro.config.mjs`
1. Change relative navigation links (e.g. `"./about"`) to absolute in `layouts/base.astro`
1. Change relative asset links (e.g. `"./fonts/*`) to absolute in `styles/base.css`
