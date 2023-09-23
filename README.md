# EIDO Healthcare Corporate Website

This is the repository for the EIDO Healthcare corporate website. It is built using [Hugo](https://gohugo.io/) and hosted on [Netlify](https://www.netlify.com/).

## Requirements

- [Hugo](https://gohugo.io/getting-started/installing/) >= 0.118
- [Node.js](https://nodejs.org/en/) >= 16
- [Yarn](https://yarnpkg.com/) >= 1.22

## Getting started

1. Clone the repository:

   ```bash
   git clone git@github.com:EIDO-Systems/eido-website-conf.git
   ```

2. Install the dependencies:

   ```bash
   yarn
   ```

3. Start the development server:

   ```bash
   yarn start
   ```

   The site will be available at <http://localhost:1313>.

## Deployment

Deployments are handled by Netlify when PRs are merged into the `main` branch, and CircleCI runs the local test suite on each PR.

To run tests locally:

```bash
yarn test
```

Code should also be linted before committing:

```bash
yarn lint
```

## Content

Content can be contributed directly to the repo using Markdown (or MDX files), or via a yet to be determined CMS
