# 01 Exercise - Sunglass Shop - Destructuring

## Brief

A common pattern in modern JavaScript is to destructure objects when they are passed into functions.

The `getProductEl` takes a single argument `product`, which is the entire product object. Instead, destructure the `product` object in `getProductEl`.

![exercise](docs/exercise.png)

## Rationale

Destructuring objects as function parameters is a common pattern used in modern JavaScript, and especially in React components and Asynchronous JavaScript. Understanding how it works is useful when reading tutorials and reference material, and using it makes your code more concise and easy to read.

## Instructions - Destructure the `product` object

1. The automated tests are already passing for this exercise. Your job is to [refactor](https://www.martinfowler.com/bliki/DefinitionOfRefactoring.html) (change the existing code) without breaking the existing tests.
2. Open `Submission/script.js` in VS Code, and `Submission/index.html` in Live Server
3. In `script.js`, find the `getProductEl` function. Notice how it has one argument, which is a product object. Change this to be a destructured object, and only use the properties you need
   - Note: the `images` property is an array, so you will need to reference the image by using `images[0]` when assigning it to the `src` attribute of the `img` element
4. Ensure the automated tests are still passing

---

# Submit your Exercise

- [ ] Commits are pushed to GitHub
- [ ] Automated tests pass in GitHub

---

## Exercise answer walkthrough

- [Sunglass Shop - Destructuring exercise walkthrough](https://www.loom.com/share/3504442edcd44957b5eb3217d8bf6a2b)
