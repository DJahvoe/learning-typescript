# ts-node
- TypeScript execution and REPL for node.js (source map and native ESM support)
- REPL (read-evaluate-print loop)

```
Under the hood, ts-node takes your script, does some semantic checking to ensure your code is error-free, and then compiles your TypeScript into JavaScript.

This is the safest option. But if you’re not worried about TypeScript errors, you can pass in the -T or --transpileOnly flag. This flag tells ts-node to transpile down to JavaScript without checking for any TypeScript errors.

While it’s not always advisable to use this flag, there are scenarios where it makes sense. If you’re trying to run someone else’s script or if you’re confident that your editor and linter are catching everything, using the -T or --transpileOnly flag is appropriate.
```

https://www.digitalocean.com/community/tutorials/typescript-running-typescript-ts-node