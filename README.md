# Nuxt 3 and Electron Starter

Chased all over the place to figure out how to get Nuxt 3 and Electron to work together. Finally cracked it. The frustrating parts seemed to turn out to be where to put stuff, and how to tell NUXT to build it. I guess?...

### This was helpful in figuring shit out:

https://github.com/gurvan-guss/nuxt-electron-sample/blob/master/electron/main.ts

## Quickstart: Clone and Install

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
