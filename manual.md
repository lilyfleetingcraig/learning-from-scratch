# 📖 Operating Manual

## 💻 Accessing Web Blocks

<div float="left" align="center">
  <img width="45%" src="https://github.com/user-attachments/assets/78d64d05-a413-41f4-8aa3-a7b89f3898b9" />
  <img width="45%" src="https://github.com/user-attachments/assets/7a2d0bfe-1322-4ffc-9768-36b8ae0de63f" />
</div>

Web Blocks can be accessed easily online [here](https://lilyfleetingcraig.github.io/dissertation/webblocks).

---

### 🚀 Installation 

> [!WARNING]
> NPM is a prerequisite for installing and running WebBlocks.
> 
> [![npm](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff)](#)

Installing Web Blocks is a very simple process!

1. Clone the codebase:

`git clone https://github.com/lilyfleetingcraig/dissertation.git`

`cd dissertation`

`cd webblocks`

2. Install the packages:

`npm install`

3. Done! 🎉
   
---

### 🏃 Running Web Blocks

Running Web Blocks is as simple as:

1. Run the code:
   
`npm run dev`

2. Done! 🎉

---

### 🧪 Test

Tests can be ran with: 
`npm run test`.

The code coverage can be viewed using the command:
`npm run test:coverage`.

The coverage report can be accessed with:
`start coverage/lcov-report/index.html`.

#### 🧱 Build Quality

The codebase can be built using the command:
`npm run build`.

##### 🕸️ Linting

Linting is performed with `ESLint` - this can be ran using the command:
`npm run lint`.

Issues discovered can be fixed with:
`npm run lint:fix`.

##### 🧼 Code Style

Adherence to style conventions is checked using `Prettier` - this can be ran with:
`npm run format:check`.

Discovered issues can be corrected using:
`npm run format`.

##### ⌨️ Typing

TypeScript typing can be checked using the command:
`npm run typecheck`.
