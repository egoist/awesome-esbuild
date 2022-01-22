# Awesome esbuild

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[esbuild](https://github.com/evanw/esbuild) is a super fast JavaScript bundler written in Go.

## Reading

- [How does esbuild transform TypeScript?](https://github.com/evanw/esbuild/issues/101#issuecomment-626239597): Like babel, esbuild treats types as whitespaces and remove them from output code.
- [Discussions about the plugin API](https://github.com/evanw/esbuild/issues/111): You will be able to build plugins in JS, you can also use esbuild as a Go library to build your own bundler for best performance. 
- [Why esbuild is written in Go rather than your favorite language](https://news.ycombinator.com/item?id=22336119): Written in a "faster" language doesn't automatically make your code run faster, esbuild is already faster than [SWC](https://github.com/swc-project/swc) which is implemented in Rust as of writting. The author is also more productive in Go and Go's compiler is faster compared to Rust, which allows him to iterate much quicker.

## JavaScript Ecosystem

- [estrella](https://github.com/rsms/estrella): A file watcher running rebuild automatically.
- [rollup-plugin-esbuild](https://github.com/egoist/rollup-plugin-esbuild): A Rollup plugin to transform JS/TS with esbuild.
- [esbuild-loader](https://github.com/egoist/esbuild-loader): A webpack loader and plugin to transform JS/TS with esbuild.
- [esbuild-webpack-plugin](https://github.com/sorrycc/esbuild-webpack-plugin): Use esbuild as minifier for webpack.
- [tsup](https://github.com/egoist/tsup): An esbuild based bundler for Node.js libraries.
- [esbuild-node-tsc](https://github.com/a7ul/esbuild-node-tsc): Build your Typescript Node.js projects using blazing fast esbuild.
- [Maho](https://github.com/egoist/maho): An attempt to build a SSR framework with esbuild and React.
- [Vite](https://github.com/vitejs/vite): An ESM-based build tool, using esbuild to transform JS/TS code.
- [Snowpack](https://github.com/pikapkg/snowpack): The near-instant build tool for modern web apps, using esbuild to transform JS/TS code.
- [serverless-esbuild](https://github.com/floydspace/serverless-esbuild): A Serverless framework plugin to bundle JavaScript and TypeScript using esbuild.
- [gulp-esbuild](https://github.com/ym-project/gulp-esbuild): A gulp plugin for esbuild bundler
- [aws-lambda-nodejs-esbuild](https://github.com/floydspace/aws-lambda-nodejs-esbuild): AWS CDK Construct to bundle JavaScript and TypeScript lambdas using esbuild.
- [esm.sh](https://github.com/postui/esm.sh): A fast, global content delivery network for ES Modules using esbuild.

## Plugins

> ⚠️ _These plugins are from the community and are not officially supported._ ⚠️

- [esbuild-dynamic-import-plugin](https://github.com/thx/gogocode/tree/main/packages/esbuild-import-plugin) A plugin that transform imports to dynamic import(import on demand).
- [esbuild-graphql-loader](https://github.com/luckycatfactory/esbuild-graphql-loader): A plugin allowing for GraphQL file imports.
- [esbuild-mdx](https://github.com/zaydek/esbuild-mdx): A plugin to render `.md` and `.mdx`-delimited files as React components.
- [esbuild-plugin-glsl](https://github.com/vanruesc/esbuild-plugin-glsl): A plugin that adds support for GLSL file imports with optional shader minification.
- [esbuild-plugin-glslx](https://github.com/evanw/esbuild-plugin-glslx): A plugin that supports [`*.glslx` files](http://evanw.github.io/glslx/) including type checking of GLSL code.
- [esbuild-plugin-less](https://github.com/iam-medvedev/esbuild-plugin-less): A plugin to transform LESS files to CSS files.
- [esbuild-plugin-postcss](https://github.com/deanc/esbuild-plugin-postcss): A plugin to use postcss.
- [esbuild-plugin-sass](https://github.com/koluch/esbuild-plugin-sass/): A plugin to transform SASS files to CSS files
- [esbuild-plugin-svgr](https://github.com/kazijawad/esbuild-plugin-svgr): A plugin to import `*.svg` files as React components.
- [esbuild-sass-plugin](https://github.com/glromeo/esbuild-sass-plugin/): Yet another SASS to CSS but with support for [lit-element's styles](https://lit-element.polymer-project.org/guide/styles)
- [esbuild-stylus-loader](https://github.com/ym-project/esbuild-stylus-loader): A plugin to transform stylus files to css files.
- [esbuild-svelte](https://github.com/EMH333/esbuild-svelte): A plugin to load and compile Svelte components.
- [essass](https://github.com/fayismahmood/sassEs/): A plugin to transform SASS files to CSS files.
- [esbuild-plugin-cache](https://github.com/dalcib/esbuild-plugin-cache): A plugin to cache http/https modules.
- [esbuild-plugin-flow](https://github.com/dalcib/esbuild-plugin-flow): A plugin to strip types for Flow files using flow-remove-types package.
- [vite-esbuild-typescript-checker](https://github.com/time4dev/vite-esbuild-typescript-checker) - Fast type checker (TypeScript, Vue SFC, etc.) Based on the webpack 5 plugin (fork-ts-checker-webpack-plugin).

## Templates

- [typescript-project-skeleton-esbuild-jest](https://github.com/permafrost-dev/typescript-project-skeleton-esbuild-jest) - Template with the latest versions of Typescript, ESBuild, Jest, ESLint & Prettier.

## Testing

- [cypress-plugins](https://github.com/glromeo/cypress-plugins) - Cypress plugins to use esbuild and v8 code coverage for e2e and component tests.
## Communities

- [Reddit](https://www.reddit.com/r/esbuild/): Unofficial subreddit for everything related to esbuild.

## Go Ecosystem

- [esbuild-service](https://github.com/egoist/esbuild-service): A web server that bundles any npm package on the fly as you fetch.
- [Hugo](https://gohugo.io/): A static site generator, using esbuild to bundle front-end assets.
