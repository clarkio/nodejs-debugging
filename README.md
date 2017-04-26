# Node.js Debugging
This repository is supplemental material for the blog post [Debugging in Node.js](https://www.clarkio.com/2017/04/25/debugging-in-nodejs/). Please follow along there for further details.

## Quick Start
1. Make sure you have Node.js installed (I suggest using [nvm](https://github.com/creationix/nvm))
2. Clone the repository
3. Change to the directory where the repository was cloned (`nodejs-debuggin`).
4. To run the `console-log.js` code use `node console-log.js`
5. To run the `built-in.js` code with the built-in Node.js debugger use `node debug built-in.js`
6. To run the `built-in.js` code with the built-in Node.js inspector use `node --inspect --debug-brk built-in.js`

You can run the following commands in your terminal to get started as well:
```bash
git clone git@github.com:clarkio/nodejs-debugging.git
cd nodejs-debugging
node console-log.js
```

### Console.log
The `console-log.js` files is to be used for debugging using `console.log()` statements throughout the code.

### Built-in
The `built-in.js` file is to be used for debugging with the either the Node.js built-in debugger or inspector. It is also later used as part of debugging with Visual Studio Code.
