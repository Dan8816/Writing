# Introducing TypeScript

[<img src="https://images.unsplash.com/photo-1498309313100-e308c8946b45?dpr=2&auto=format&fit=crop&w=1080&h=1620&q=80&cs=tinysrgb&crop=">](
https://unsplash.com/photos/4Cjn0FDEud8)
Photo by 张 学欢 on Unsplash - https://unsplash.com/photos/4Cjn0FDEud8


Since I am getting more and more advanced, now it was time to take a look into Typescript. Not because of the simple linting of JavaScript code, but rather because of the static typing concept.

For most of my conclusions I refer to: 

- [The Github repository and wiki of Microsoft (who maintains the project)](https://github.com/Microsoft/TypeScript/wiki/TypeScript-Design-Goals)
- [TypeScript DeepDive Gitbook by Basarat Ali Syed and it's contributors](https://basarat.gitbooks.io/typescript/docs/why-typescript.html)


## 📄 Table of contents


---
> "Lack of documentation is becoming a problem for acceptance." - Wietse Venema

---

## What is it and where is it heading?

The idea behind TypeScript is to provide an optional type system for JavaScript. 

It enhances code quality by
- increase your agility when doing refactoring. It's better for the compiler to catch errors than to have things fail at runtime.
- types are one of the best forms of documentation you can have. The function signature is a theorem and the function body is the proof.

> Your JavaScript code .js file can be renamed to a .ts file and TypeScript will still give you back valid .js equivalent to the original JavaScript file. TypeScript is intentionally and strictly a superset of JavaScript with optional Type checking.

It's goals (according to the official documentation) are:
- Statically identify constructs that are likely to be errors.
- Provide a structuring mechanism for larger pieces of code.
- Impose no runtime overhead on emitted programs.
- Emit clean, idiomatic, recognizable JavaScript code.
- Produce a language that is composable and easy to reason about.
- Align with current and future ECMAScript proposals.
- Preserve runtime behavior of all JavaScript code.
- Avoid adding expression-level syntax.
- Use a consistent, fully erasable, structural type system.
- Be a cross-platform development tool.
- Do not cause substantial breaking changes from TypeScript 1.0.

## Concepts

___
> Essentially TypeScript is linting JavaScript. Just doing a better job at it than other linters that don't have type information.
___

#### Basics Types

Types are annotated using `:TypeAnnotation` syntax.

- Boolean (`let isDone: boolean = false;`)
- Number (`let decimal: number = 6;`)
- String (`let color: string = "blue";`)
- Array  (`let list: number[] = [1, 2, 3];` or `let list: Array<number> = [1, 2, 3];`)
- Tuple (`let x: [string, number]; x = ["hello", 10];`)
- Enum (`enum Color {Red, Green, Blue} let c: Color = Color.Green;`)
- Any (opt-out of type-checking and let some values pass through compile-time checks)
- Void (the absence of having any type at all)
- Null / Undefined (are subtypes of all other types. That means you can assign null and undefined to something like number)
- Never (is the return type for a function expression or an arrow function expression that always throws an exception or one that never returns)






## Useful links & credits
- [📄 "Begin"](afgafgadgads)



Thanks for reading my article! Feel free to leave any feedback! 


<!-- Written by Daniel Deutsch (deudan1010@gmail.com) -->