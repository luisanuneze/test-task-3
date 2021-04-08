# test-task-3

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Tasks

### 1. Write a file and folder skeleton from the following [configurator](https://global-memories-frontend.onrender.com/configurator)

**Hint1.** You don't need to write a single line of css.

**Hint2.** You don't need to write any functionality.

**Hint3.** You don't need to write any working navigation.

**Hint4.** You don't need to write any html elements.

**Hint5.** You only need a file and folder skeleton, no renderable view in the browser.

1.1 Write all required files and folders like you would expect it in a real world scenario.

1.2 Build the file and folder architecture in the most modular and reusable way possible.

1.3 Even though you're not required to write css, you need to know that any global css would be entirely forbidden if you would build the complete configurator. You need to write files and folders in a way that enables you to use `scoped` css only. Please keep in mind that also any single line of duplicate css would not be allowed neither. So, all components that you find in the configurator have to be a unique file.

1.4 Files and folders should describe themselves.

1.5 Inside each file you can write a few words to describe the component. (e.g `I am a selectpicker`, `I am a cornered foto thumbnail`). If you do really well, it should be possible to immediately understand what a file is doing, without having to take a look inside the file.

1.6 Make sure to capture all details and don't miss to write components for even the smallest elements you find in the configurator.

### 2. Write `Nuxt.js Store` modules and state models for the same [configurator](https://global-memories-frontend.onrender.com/configurator).

**Hint1.** Use the `Nuxt.js` storage. It automatically uses `Vuex`, you don't need to install it separately.

**Hint2.** You don't need to write `mutations`, or `getters`.

2.1 Please setup all configurator settings

2.2 Use `store` modules to give it a maintainable structure

2.3 In the state of each module write the model for all required settings
