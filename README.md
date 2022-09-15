# ctix-51
https://github.com/imjuni/ctix/issues/51


Run `npm run test:51` to reproduce:

```
> ctix-51@1.0.0 test:51 /Users/my_name/Desktop/ctix-51
> ctix single -p ./tsconfig.json -o ./src/index.ts

  ignore file loading complete
[22-09-15 17:27:31] error: detailIgnoreds.at is not a function
[22-09-15 17:27:31] error: TypeError: detailIgnoreds.at is not a function
    at getCtiIgnorePattern (/Users/my_name/Desktop/ctix-51/node_modules/ctix/dist/cli.js:946:31)
    at getExportInfo (/Users/my_name/Desktop/ctix-51/node_modules/ctix/dist/cli.js:984:26)
    at async Promise.all (index 0)
    at getExportInfos (/Users/my_name/Desktop/ctix-51/node_modules/ctix/dist/cli.js:1067:26)
    at singleWritor (/Users/my_name/Desktop/ctix-51/node_modules/ctix/dist/cli.js:2047:34)
    at Object.handler (/Users/my_name/Desktop/ctix-51/node_modules/ctix/dist/cli.js:2213:13)
```