# rollup-plugin-vue2


> Roll Vue 2 SFCs with Rollup.

## Install

`
npm i rollup-plugin-ue2 --save-dev
`

<div class="text-xs-center" align="center" style="margin: 20px">
  <img src="https://raw.githubusercontent.com/vuejs/rollup-plugin-vue/master/docs/.vuepress/public/logo.png">
</div>

## Introduction

As vue-loader is for webpack and vueify is for browserify, similarly its for rollup. As we know, webpack and browserify concat stuff and make it runnable in browser. Its difficult to share .vue components. **Now roll your [Vue](http://vuejs.org/) components.**

With rollup you can break your application into reusable modules.

<p align="center">
  <a href="https://circleci.com/gh/vuejs/rollup-plugin-vue">
    <img src="https://circleci.com/gh/vuejs/rollup-plugin-vue.svg?style=svg" alt="Build Status" />
  </a>
  <a href="https://coveralls.io/github/znck/rollup-plugin-vue?branch=master">
    <img src="https://coveralls.io/repos/github/znck/rollup-plugin-vue/badge.svg?branch=master&style=flat-square" alt="Coverage Status" />
  </a>
</p>

## Usage

> This document applies to v4.0+. If you are looking for older versions, docs are [here](https://github.com/vuejs/rollup-plugin-vue/tree/2.2/docs)

```js
import commonjs from 'rollup-plugin-commonjs' 
import VuePlugin from 'rollup-plugin-ue2'

export default {
  entry: 'main.js',
  plugins: [
    commonjs(),
    VuePlugin(/* VuePluginOptions */)
  ]
}
```

See [available options](https://rollup-plugin-vue.vuejs.org/options.html) for `VuePluginOptions`.
