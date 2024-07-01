# Function Types
- Give types to function
```ts
function add(a: number, b: number): number {
  return a + b;
}
```
- Function overloading
```ts
function add(a: number, b: number): number;
function add(a: string, b: string): string;

function add(a: any, b: any): any {
  return a + b;
}

console.log(add(1, 2)); // 3
console.log(add('Hello', ' World')); // "Hello World"
```