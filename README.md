This repository contains a collection of hands-on TypeScript projects built to strengthen core TypeScript concepts such as types, interfaces, classes, generics, and type safety.

Each project is designed to be simple, practical, and runnable directly from the VS Code terminal, without any UI framework.

🚀 How to Run Projects (VS Code Terminal)

1️⃣ Clone the Repository

git clone https://github.com/your-username/typescript-projects.git
cd typescript-projects

2️⃣ Install TypeScript (If Not Installed)

npm install -g typescript

3️⃣ Initialize TypeScript Configuration (One-time)

tsc --init

This creates a tsconfig.json file which controls TypeScript compilation.

4️⃣ Compile TypeScript to JavaScript

Navigate into any project folder (example: generic-data-store):

cd generic-data-store
tsc
This compiles index.ts → index.js.

5️⃣ Run the Compiled JavaScript
node index.js

The output will be displayed in the terminal.

📂 Projects Included
1️⃣ Generic Data Store

Concepts used:
TypeScript Generics
Generic Constraints
Interfaces
Classes
Readonly properties
Type safety without any

Description:

A reusable, type-safe data store that can manage different data models (such as Users and Products) using TypeScript generics. This project demonstrates how generics help create scalable and maintainable code.

Key Learning:

How to build reusable logic using T extends Interface instead of relying on any.

🔜 More TypeScript projects will be added to this repository as learning progresses.

🛠 Tools & Technologies

TypeScript
Node.js
VS Code
Git & GitHub

📌 Notes

All projects are console-based
Focus is on TypeScript fundamentals, not UI
Code is written with clean structure and readability

✨ Author

Payel Acharyya
Frontend Developer | TypeScript Enthusiast
