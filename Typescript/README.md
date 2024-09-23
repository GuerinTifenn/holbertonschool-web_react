# TypeScript Project

## Learning Objectives

At the end of this project, you should be able to:

- Understand and use basic types in TypeScript
- Work with interfaces, classes, and functions
- Manipulate the DOM using TypeScript
- Utilize generic types
- Apply namespaces and declaration merging
- Work with ambient namespaces and import external libraries
- Understand basic nominal typing with TypeScript

---

## Project Requirements

- **Editors:** vi, vim, emacs, Visual Studio Code
- **Environment:** Files must be transpiled on Ubuntu 18.04, using `jest` for testing.
- **File Naming:** All files should end with a new line and use `.ts` extension.
- **Compiler:** No TypeScript errors or warnings should appear during compilation.
- **Repository Structure:** Ensure each task is organized in its respective folder (e.g., `task_0`, `task_1`).

---

## Tasks Overview

<details>
<summary>Task 0: Creating an Interface for a Student</summary>

- **Directory:** `task_0`
- **Objective:** Create a `Student` interface with properties for `firstName`, `lastName`, `age`, and `location`.
- **Steps:**
  1. Define `Student` interface.
  2. Create two student objects and store them in an array.
  3. Render a table in the DOM using Vanilla JavaScript.
- **Requirements:**
  - Use Webpack to transpile and check for errors.
  - Ensure all variables are typed.
</details>

<details>
<summary>Task 1: Let's Build a Teacher Interface</summary>

- **Directory:** `task_1`
- **Objective:** Create a `Teacher` interface.
- **Steps:**
  1. Define `Teacher` with properties `firstName`, `lastName`, `fullTimeEmployee`, `yearsOfExperience`, and `location`.
  2. Allow for dynamic attributes by using a string index signature.
- **Example:**
    ```typescript
    const teacher: Teacher = {
      firstName: 'John',
      lastName: 'Doe',
      location: 'London',
      fullTimeEmployee: true,
      contract: false
    };
    ```
</details>

<details>
<summary>Task 2: Extending the Teacher Class</summary>

- **Directory:** `task_1`
- **Objective:** Extend `Teacher` to create a `Directors` interface.
- **Steps:**
  1. Extend the `Teacher` interface by adding a `numberOfReports` property.
  2. Implement example usage.
</details>

<details>
<summary>Task 3: Printing Teachers</summary>

- **Directory:** `task_1`
- **Objective:** Write a function `printTeacher`.
- **Steps:**
  1. Define a function `printTeacher` that returns the first letter of `firstName` and the full `lastName`.
  2. Create an interface for `printTeacherFunction`.
</details>

<details>
<summary>Task 4: Writing a Class</summary>

- **Directory:** `task_1`
- **Objective:** Create a `StudentClass`.
- **Steps:**
  1. Define a constructor for `StudentClass`.
  2. Add methods `workOnHomework` and `displayName`.
</details>

<details>
<summary>Task 5: Advanced Types Part 1</summary>

- **Directory:** `task_2`
- **Objective:** Implement `DirectorInterface` and `TeacherInterface`.
- **Steps:**
  1. Define two interfaces, `DirectorInterface` and `TeacherInterface`.
  2. Implement classes `Director` and `Teacher`.
  3. Write a function `createEmployee` that returns either a `Director` or `Teacher`.
</details>

<details>
<summary>Task 6: Creating Functions Specific to Employees</summary>

- **Directory:** `task_2`
- **Objective:** Write functions `isDirector` and `executeWork`.
- **Steps:**
  1. Define `isDirector` as a type predicate.
  2. Define `executeWork` to call the correct method depending on employee type.
</details>

<details>
<summary>Task 7: String Literal Types</summary>

- **Directory:** `task_2`
- **Objective:** Create a string literal type `Subjects` and implement the `teachClass` function.
- **Steps:**
  1. Define a type `Subjects` that can be either `"Math"` or `"History"`.
  2. Write a function `teachClass` that returns the appropriate string based on the subject.
</details>

<details>
<summary>Task 8: Ambient Namespaces</summary>

- **Directory:** `task_3`
- **Objective:** Work with ambient namespaces and external libraries.
- **Steps:**
  1. Define `RowID` and `RowElement`.
  2. Create an ambient declaration file for `crud.js`.
  3. Implement interactions with the external library.
</details>

<details>
<summary>Task 9: Namespace & Declaration Merging</summary>

- **Directory:** `task_4`
- **Objective:** Implement multiple classes and interfaces using namespaces and declaration merging.
- **Steps:**
  1. Define `Teacher` in the `Subjects` namespace.
  2. Use declaration merging to add properties to the `Teacher` interface.
  3. Create `Cpp`, `React`, and `Java` classes, each with their specific methods.
</details>

<details>
<summary>Task 10: Brand Convention & Nominal Typing</summary>

- **Directory:** `task_5`
- **Objective:** Implement `MajorCredits` and `MinorCredits`.
- **Steps:**
  1. Define `MajorCredits` and `MinorCredits` interfaces.
  2. Implement functions `sumMajorCredits` and `sumMinorCredits`.
</details>
