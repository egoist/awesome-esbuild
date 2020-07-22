# Awesome esbuild

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[esbuild](https://github.com/evanw/esbuild) is a super fast JavaScript bundler written in Go.

## Reading

- [How does esbuild transform TypeScript?](https://github.com/evanw/esbuild/issues/101#issuecomment-626239597): Like babel, esbuild treats types as whitespaces and remove them from output code.
- [Discussions about the plugin API](https://github.com/evanw/esbuild/issues/111): You will be able to build plugins in JS, you can also use esbuild as a Go library to build your own bundler for best performance. 
- [Why esbuild is written in Go rather than your favorite language](https://news.ycombinator.com/item?id=22336119): Written in a "faster" language doesn't automatically make your code run faster, esbuild is already faster than [SWC](https://github.com/swc-project/swc) which is implemented in Rust as of writting. The author is also more productive in Go and Go's compiler is faster compared to Rust, which allows him to iterate much quicker.

## JavaScript Ecosystem

- [rollup-plugin-esbuild](https://github.com/egoist/rollup-plugin-esbuild): A Rollup plugin to transform JS/TS with esbuild.
- [esbuild-loader](https://github.com/egoist/esbuild-loader): A webpack loader and plugin to transform JS/TS with esbuild.
- [tsup](https://github.com/egoist/tsup): An esbuild based bundler for Node.js libraries.
- [Maho](https://github.com/egoist/maho): An attempt to build a SSR framework with esbuild and React.
- [Vite](https://github.com/vitejs/vite): An ESM-based build tool, using esbuild to transform JS/TS code.
- [Snowpack](https://github.com/pikapkg/snowpack): The near-instant build tool for modern web apps, using esbuild to transform JS/TS code.
- [serverless-esbuild](https://github.com/floydspace/serverless-esbuild): A Serverless framework plugin to bundle JavaScript and TypeScript with extremely fast esbuild

## Go Ecosystem

- [esbuild-service](https://github.com/egoist/esbuild-service): A web server that bundles any npm package on the fly as you fetch.
- [Hugo](https://gohugo.io/): A static site generator, using esbuild to bundle front-end assets.
