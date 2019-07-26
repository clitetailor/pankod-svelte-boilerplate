<br/>
<div align="center" >SvelteJS application boilerplate with Webpack, scss, babel, fetchjs, postcss, jest, .env.</div>
<br/>

<div align="center">
  <!-- CodeClimate -->
  <a href="https://codeclimate.com/github/pankod/svelte-boilerplate/maintainability">
    <img src="https://api.codeclimate.com/v1/badges/077c02d5cb9ec7d8a654/maintainability" />
  </a>
  <!-- TestCoverage -->
  <a href="https://codeclimate.com/github/pankod/svelte-boilerplate/test_coverage"><img src="https://api.codeclimate.com/v1/badges/077c02d5cb9ec7d8a654/test_coverage" /></a>
  <!-- Build Status -->
  <a href="https://travis-ci.org/pankod/svelte-boilerplate">
    <img src="https://travis-ci.org/pankod/svelte-boilerplate.svg?branch=master" alt="Build Status" />
  </a>
  <!-- Dependency Status -->
  <a href="https://david-dm.org/pankod/svelte-boilerplate">
    <img src="https://david-dm.org/pankod/svelte-boilerplate.svg" alt="Dependency Status" />
  </a>
  <!-- devDependency Status -->
  <a href="https://david-dm.org/pankod/svelte-boilerplate#info=devDependencies"> 
    <img src="https://david-dm.org/pankod/svelte-boilerplate/dev-status.svg" alt="devDependency Status" />
  </a>
</div>

This boilerplate make it easier to get started with a well-structured SvelteJS application.

<br/>
<div align="center">
  <sub>Created by <a href="https://www.pankod.com">Pankod</a></sub>
</div>


## Get started

Install the dependencies...

```bash
cd svelte-boilerplate
npm install
```

...then start webpack:

```bash
npm run start:dev
```

Navigate to [localhost:8080](http://localhost:8080). You should see your app running. Edit a component file in `src`, save it, and the page should reload with your changes.

## Deploying to the web

Then, from within your project folder:

```bash
npm run build
surge public
```
