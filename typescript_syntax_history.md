# TypeScript Basic Syntax Formats

## User Query 1
basic syntax formats of typescript

## Assistant Response 1
TypeScript is a typed superset of JavaScript that adds static type definitions to help catch errors during development.

### Variable Declarations and Type Annotations
* **Explicit typing:** Write a colon (`:`) after the variable name, followed by the type.
  ```typescript
  let name: string = "Alice";
  let age: number = 30;
  let isActive: boolean = true;
  ```
* **Type inference:** TypeScript can automatically guess the type based on the assigned value if you omit the annotation.
  ```typescript
  let score = 100; // Inferred as number
  ```

### Functions
* **Parameter and return types:** Add types to function parameters and specify the return type after the parameter list.
  ```typescript
  function add(x: number, y: number): number {
    return x + y;
  }
  ```
* **Void return:** Use `void` when a function does not return a value.
  ```typescript
  function logMessage(msg: string): void {
    console.log(msg);
  }
  ```

### Interfaces and Objects
* **Defining object shapes:** Use `interface` to enforce a specific structure for objects, including optional properties with a question mark (`?`).
  ```typescript
  interface User {
    id: number;
    name: string;
    email?: string; // Optional
  }
  
  const user: User = { id: 1, name: "Bob" };
  ```

### Arrays and Tuples
* **Arrays:** Define an array using `type[]` or the generic `Array<type>` syntax.
  ```typescript
  let list: number[] = [1, 2, 3];
  let names: Array<string> = ["Alice", "Bob"];
  ```
* **Tuples:** Define an array with a fixed number of elements and known, specific types.
  ```typescript
  let person: [number, string] = [1, "Alice"];
  ```

Would you like to explore more advanced TypeScript formats like **Generics**, **Union Types**, or **Classes**?

---

## User Query 2
generate a markdown file of this query conversation history keeping exactly the same
