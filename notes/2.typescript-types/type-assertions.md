# Type Assertions
- in TypeScript, we can tell the compiler to treat a value as a specific type using `<>` angle brackets or `as` syntax

```ts
let num = 42;

// using angle-bracket syntax
let str = <string>num;

// using as syntax
let str2 = num as string;
```

- `as const`, treated as read-only value
- `as [type]`
- `as any`

## Non Null Assertion
- The non-null assertion operator (!) is a type assertion in TypeScript that allows you to tell the compiler that a value will never be null or undefined.
```ts
let name: string | null = null;

// we use the non-null assertion operator to tell the compiler that name will never be null
let nameLength = name!.length;
```

## satisfies Keyword
https://www.typescriptlang.org/docs/handbook/release-notes/typescript-4-9.html#the-satisfies-operator