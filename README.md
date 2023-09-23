# ReScript Google Apps Script Starter

This configuration generates GAS-compatible JS from a ReScript file using rollup and strips the final `export` statements.

## Setup

Follow the setup instructions for [Clasp](https://github.com/google/clasp), including [cloning](https://github.com/google/clasp#clone) a script project to a local directory.

Clone this repository with `git clone --depth=1` and remove the `.git` directory (or use or `npx degit`). Run `npm install` to install dependencies.

## Build

- Build: `npm run build`
- Clean: `npm run clean`
- Push to Google Scripts: `npm run deploy`

Credit to [ReScript Project Template](https://github.com/rescript-lang/rescript-project-template) & [Example repo of using esmodules with Apps Script](https://github.com/atti187/esmodules).