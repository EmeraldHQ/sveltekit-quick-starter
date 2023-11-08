# sveltekit-quick-starter

Quick starter for SvelteKit, with additional features.

## Base stack

- Svelte
- SvelteKit
- TailwindCSS
- TypeScript
- Prettier + ESLint
- PNPM

## Additional features

- Improved TailwindCSS configuration
- More `package.json` scripts
- DevOps
  - Renovate with validation workflow
  - Husky with post-checkout dependencies installation & branch cleanup
  - `pr-auto-assign`: Automatically assign PRs to their author
  - Main build pipeline with prechecks (linting & formatting) and build steps
  - Auto-release CI pipeline
