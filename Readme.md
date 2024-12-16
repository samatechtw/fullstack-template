<h2 align='center'>Fullstack Template</h2>

<p align='center'>Fullstack template for Vue3 + Rust/Axum apps.</p>

<br>

### Usage

This is a rough template for a full stack app, using Vue3 for the frontend and Rust/Axum for the backend API.

Clone or copy/paste all files, and choose a name for your app (e.g. Cool App). Replace text according this table in order (case sensitive):

Finally, rename the `backend/fullstack-api` folder to `backend/cool-api`, and update information in the Readme/package.json.

#### Prerequisites

- Install [PNPM](https://pnpm.io/)

#### Setup

```bash
# Clone monorepo
git clone git@github.com:samatechtw/fullstack-template

# Install packages
pnpm i
```

#### Run

```bash
# Run site in development mode
npm run prod:web:run

# Run web admin
npm run prod:web-admin:run
```

**Build**

```bash
# Build web app for production
npm run prod:web:build

# Build web admin
npm run prod:web-admin:build
```

### Development

**Add a new frontend folder/module**

- Create the folder in `web/src`
- Create `index.ts` and export any files used externally
- Add to tsconfig `paths`
