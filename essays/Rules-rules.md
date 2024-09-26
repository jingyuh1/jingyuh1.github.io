---
layout: essay
type: essay
title: Rules-rules
# All dates must be YYYY-MM-DD format!
date: 2024-09-25
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

![coding-standards-for-programming-languages-1024x512](https://github.com/jingyuh1/jingyuh1.github.io/assets/156954674/cc498319-1c9c-447c-b921-b2b526f2975e)


## coding standards

Code specifications are a vital part of software development. They cover guidelines for code writing style, structure, naming conventions, annotation rules, etc. Standard code is easier to read and understand, which is very important for team collaboration and code maintenance. When multiple developers work on a project, following the same specifications ensures code consistency, reducing the possibility of confusion and errors. Reduce error rates: Standardized code is easier for developers to write and maintain correctly. It can help developers avoid some common coding errors, such as spelling errors, grammatical errors, etc., thereby improving the quality of the code. Improve code scalability: Standardized code is easier to extend and modify. When new features need to be added or refactored, code that conforms to the specification can adapt to changes more easily, reducing the risk of introducing bugs.

## ESLint with IntelliJ

ESLint is a really cool tool that cleans up your Javascript code for you! But who wants to run npm run lint all the time when you're running an IDE like IntelliJ/WebStorm/VSCode, right? "Let me It would be great for an IDE to automatically run my linting... but how?" Let's start with IntelliJ first, because it's the easiest! It's usually already set up on IntelliJ (and subsequently WebStorm). JSHint is inherited from JSLint, so it follows the JSLint Top Down Operator Precedence (top-down operator priority) technology to implement source code parsing. However, the huge demand brought by the explosive growth of the front end makes JSHint increasingly difficult to cope with. , supporting third-party plug-ins by exposing AST information is undoubtedly a good solution. ESLint parses the source code into AST, and then detects the AST to determine whether the code complies with the rules, laying a solid foundation for ESLint's high scalability. ESLint keeps the kernel simple enough, with only 100 lines of code, and the implementation of the rules is completely separated from the kernel.


## Conclusion

Coding Standards are the rules that must be followed when coding programs. Pay attention to the correctness, stability, and readability of the code. Avoid using numbers that are difficult to understand, replace them with meaningful symbols, and do not use technical statements that are difficult to understand. Closely related codes in the source program should be as adjacent as possible. Keep the code style consistent and reduce the chance of code errors. In order to solve this type of static code problem, each team needs a unified JS code specification, and team members follow this code specification to write code. Of course, it is unreliable to rely on people to ensure code specifications. Corresponding tools are needed to ensure this. ESLint is this tool.
