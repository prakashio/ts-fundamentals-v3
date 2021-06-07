---
title: Intro
date: "2015-05-01T22:12:03.284Z"
description: |
  We'll discuss the goals and agenda of this course, and how to get up and
  running with the workshop project in 2 minutes or less.
course: fundamentals-v3
order: 1
---

## What is TypeScript?

> TypeScript is a **syntactic superset** of JavaScript

- An [open source programming language](https://github.com/microsoft/TypeScript), maintained by Microsoft
- The foundation of an excellent developer experience
- "A fancy linter"

**It allows code authors to leave more of their intent "on the page"**, at least
on-par with very-well-documented JavaScript

```ts twoslash
// @errors: 2345
function add(a: number, b: number): number {
  return a + b
}
add(3, "4")
```

## #1 Goal for this course

> By the end of this course, **I want you to have a rock solid mental model that will serve well for years**

## Setup

As long as you can access the following websites, you should require no further setup :tada:

- [The course website you're reading right now](https://fun-v3.typescript-training.com)
- [The official TypeScript website](https://www.typescriptlang.org)

### Agenda

- Using `tsc` and **compiling** TS code into JavaScript
- **Variables** and simple values
- **Objects** and arrays
  <br/>`--- BREAK ---`
- Categorizing **type systems**
- Set theory, **Union and Intersection types**
- **Interfaces and Type Aliases**
  <br/>`--- LUNCH ---`
- **Hack**: Writing types for JSON values
- **Functions**
- **Classes** in TypeScript
- **Top and bottom types**
- User-defined **Type guards**
  <br/>`--- BREAK ---`
- Handling **nullish values**
- **Generics**
- **Hack**: higher-order functions for dictionaries
- Wrap up