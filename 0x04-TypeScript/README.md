# 0x04. TypeScript

This project demonstrates TypeScript fundamentals including interfaces, classes, functions, namespaces, and advanced type features.

## Environment

- **OS**: Ubuntu 18.04
- **TypeScript**: 3.6.4
- **Jest**: 24.9.0
- **Webpack**: 4.41.2

## Tasks

### Task 0: Creating an interface for a student

- **Directory**: `task_0`
- **Files**: `js/main.ts`, `package.json`, `.eslintrc.js`, `tsconfig.json`, `webpack.config.js`
- Creates a `Student` interface and renders a table displaying student data in the DOM.

### Task 1: Teacher interface

- **Directory**: `task_1`
- **Files**: `js/main.ts`, `package.json`, `webpack.config.js`, `tsconfig.json`
- Defines a `Teacher` interface with readonly properties and index signature for dynamic attributes.

### Task 2: Extending the Teacher class

- **Directory**: `task_1`
- **File**: `js/main.ts`
- Extends `Teacher` interface with `Directors` interface requiring `numberOfReports`.

### Task 3: Printing teachers

- **Directory**: `task_1`
- **File**: `js/main.ts`
- Implements `printTeacher` function with typed interface.

### Task 4: Writing a class

- **Directory**: `task_1`
- **File**: `js/main.ts`
- Creates `StudentClass` with constructor and method interfaces.

### Task 5: Advanced types Part 1

- **Directory**: `task_2`
- **Files**: `js/main.ts`, `package.json`, `webpack.config.js`, `tsconfig.json`
- Implements `Director` and `Teacher` classes with `createEmployee` factory function.

### Task 6: Creating functions specific to employees

- **Directory**: `task_2`
- **File**: `js/main.ts`
- Adds type predicate `isDirector` and `executeWork` function.

### Task 7: String literal types

- **Directory**: `task_2`
- **File**: `js/main.ts`
- Uses string literal type `Subjects` and `teachClass` function.

### Task 8: Ambient Namespaces

- **Directory**: `task_3`
- **Files**: `js/main.ts`, `js/interface.ts`, `js/crud.d.ts`, `js/crud.js`
- Demonstrates ambient type declarations for external JavaScript library.

### Task 9: Namespace & Declaration merging

- **Directory**: `task_4`
- **Files**: `js/subjects/*.ts`, `js/main.ts`, `package.json`, `tsconfig.json`
- Uses namespaces and declaration merging for subject-specific teacher attributes.

### Task 10: Update task_4/js/main.ts

- **Directory**: `task_4`
- **File**: `js/main.ts`
- Creates subject instances and demonstrates teacher assignment.

### Task 11: Brand convention & Nominal typing

- **Directory**: `task_5`
- **Files**: `js/main.ts`, `package.json`, `webpack.config.js`, `tsconfig.json`
- Implements nominal typing with brand properties for `MajorCredits` and `MinorCredits`.

## Setup

Each task directory contains its own build configuration. To build a task:

```bash
cd task_X
npm install
npm run build
```

## Testing

Run tests (where applicable):

```bash
npm test
```

## Author

ALX Frontend JavaScript - TypeScript Project
