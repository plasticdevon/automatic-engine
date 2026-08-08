# Automatic Engine

A starter repository for an Angular / TypeScript web application. The repo was empty when I inspected it; this README provides a short bootstrap guide and minimal boilerplate so you can initialize the project locally with the Angular CLI.

## Stack
- Language: TypeScript (Angular)
- Framework: Angular (recommended via Angular CLI)

## Quickstart (recommended)
From a local clone of this repository, bootstrap the full Angular app using the Angular CLI. This keeps the canonical Angular project layout and configuration:

```bash
# from a fresh clone
cd automatic-engine
# Use npx so you don't need a global install of @angular/cli
npx @angular/cli new . --skip-git --minimal --directory=.
npm install
npm start
```

If you prefer to create the app in a subfolder instead of the repository root:

```bash
npx @angular/cli new my-app
cd my-app
npm install
npm start
```

## Scripts
This repo contains a minimal package.json with scripts that call the Angular CLI. After running `npm install`, you'll be able to run `npm start`, `npm run build`, and `npm test`.

## Contributing
If you'd like me to scaffold a minimal Angular app directly in this repo (create `src/`, `angular.json`, `package.json` with full config), tell me and I can add those files on a new branch or directly on `main`.
