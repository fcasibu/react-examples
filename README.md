# React Examples

This repository houses react examples which are uploaded to The Odin Project's CodeSandbox account. Ultimately, these examples appear as CodeSandbox embeds in The Odin Project's React Curriculum .

## How To Add A React Example

1. Read through the [contributing guide](https://github.com/TheOdinProject/theodinproject/blob/main/CONTRIBUTING.md#curriculum-structure).
2. Make sure you have node, npm and npx installed. You may use the [Installing Node.js](https://www.theodinproject.com/lessons/foundations-installing-node-js) lesson to install these tools.
2. Fork & clone this repository. Install dependencies by running `npm install`.
3. Create a new example folder by copying the `boilerplate` folder. And `cd` into it and install dependencies.
   ```bash
     cp -R ./boilerplate ./<example-name>
     cd ./<example-name>
     npm install
   ```
4. Code out your example.
5. Start the dev server `npm run start` to make sure the example runs as expected. 
6. Run `npm run lint` for ESLint and Prettier to format the code. 
7. Create the pull request. (remember to mention which lesson will require the example)

### Naming examples

Make sure that examples are clearly named, meaning they should convey what the example is about on a glance. Examples:

```c
// bad
example-1 
state-example 
arrays

// good
hello-world
passing-props 
rendering-arrays-in-jsx
```
