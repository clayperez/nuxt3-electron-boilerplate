# Nuxt 3 and Electron Quickstart

[ 2022-12-17 ]
This is a working quickstart for NUXT3 and Electron (meaning Vue3!)

Credit for helping figure stuff out goes to [Gurvan-guss](https://github.com/gurvan-guss).

Ultimately, I had to refactor things to get this to work on OSX. Here is the result. You should be able to clone this and get started developing right away. If I run into things that need to be fixed up, I'll try to keep this quickstart boilerplate up to date.

### Environment

Here are the versions of core software that makes this work for now:

- Node 19.2.0
- Electron 22.0.0
- Nuxt 3.0.0

#### Tailwind CSS

I also like to start with [Tailwind](https://tailwindcss.com/).  
[These installation instructions work for NUXT 3](https://tailwindcss.com/docs/guides/nuxtjs#3)

# Quickstart: Clone and Install

For people who are shy with GIT...

```bash
# Close this repo to your system
git clone git@github.com:clayperez/nuxt3-electron-boilerplate.git <destination_folder>

# move to the app directory
cd <destination_folder>

# Install dependencies
yarn install
```

#### Configure Electron Build

1. Configure Electron's `build` parameter for your preferred configuration inside package.json.

## Development

Start a nuxt-electron HMR dev app that you can go crazy with:

```bash
# yarn
yarn dev

# npm
npm run dev
```

## Build

Build the application for distribution. This puts a packaged distributable inside the "dist" folder in the root of your app:

```bash
yarn build
npm run build
```
