# Setup
`npm install`
Installs all the depencies needed to compile your project

## Build 
`npm run build`
 
 Runs `babel src --out-dir lib`

## Test

`npm run test`

Runs jest 

### Worth knowing

If jest throws a ReferenceError `regeneratorRuntime` not found you can `import babel-polyfill` in the failing test.