# 05-hot-module-replacement

- Hot Module Replacement (or HMR) is one of the *most useful features* offered by webpack. 
- It allows all kinds of modules to be *updated at runtime* *without* the need for a *full refresh*.

## Via the Node.js API

- When using Webpack Dev Server with the Node.js API, don't put the dev server options on the webpack config object. 
- Instead, pass them as a second parameter upon creation.  