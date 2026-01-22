# Linear Data Structures in JavaScript

A beginner-to-intermediate JavaScript repository that demonstrates **core linear data structures**, their **implementations**, and **common operations** using clean, well-documented code. This repository is intended for **students**, **self-learners**, and **developers** who want a solid foundation in data structures using JavaScript.

---

## 📚 Covered Data Structures

* Arrays
* Strings
* Linked Lists

  * Singly Linked List
  * Doubly Linked List
* Stacks
* Queues
* Deques (Double-Ended Queues)

Each data structure includes:

* Concept overview
* Implementation in JavaScript
* Common operations
* Time and space complexity notes

---

## 🗂️ Project Structure

```
linear-data-structures-js/
│
├── arrays/
│   ├── basics.js
│   └── operations.js
│
├── strings/
│   └── string-operations.js
│
├── linked-lists/
│   ├── singly-linked-list.js
│   └── doubly-linked-list.js
│
├── stacks/
│   ├── stack-array.js
│   └── stack-linked-list.js
│
├── queues/
│   ├── queue-array.js
│   └── circular-queue.js
│
├── deques/
│   └── deque.js
│
├── utils/
│   └── helpers.js
│
├── examples/
│   └── usage-examples.js
│
├── README.md
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js (v16 or later recommended)
* Basic knowledge of JavaScript

### Installation

```bash
git clone https://github.com/your-username/linear-data-structures-js.git
cd linear-data-structures-js
npm install
```

---

## ▶️ Running Examples

You can run individual files using Node.js:

```bash
node stacks/stack-array.js
```

Or run bundled examples:

```bash
node examples/usage-examples.js
```

---

## ✨ Example (Stack Implementation)

```js
class Stack {
  constructor() {
    this.items = [];
  }

  push(element) {
    this.items.push(element);
  }

  pop() {
    return this.items.pop();
  }

  peek() {
    return this.items[this.items.length - 1];
  }
}
```

---

## ⏱️ Complexity Reference

| Data Structure | Access | Search | Insert | Delete |
| -------------- | ------ | ------ | ------ | ------ |
| Array          | O(1)   | O(n)   | O(n)   | O(n)   |
| Linked List    | O(n)   | O(n)   | O(1)   | O(1)   |
| Stack          | O(n)   | O(n)   | O(1)   | O(1)   |
| Queue          | O(n)   | O(n)   | O(1)   | O(1)   |

---

## 🎯 Learning Goals

* Understand how linear data structures work internally
* Learn when to use each data structure
* Analyze time and space complexity
* Apply data structures to real-world problems

---

## 🛠️ Tech Stack

* JavaScript (ES6+)
* Node.js

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/new-structure`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgements

Inspired by classic data structures courses and algorithm textbooks, adapted for modern JavaScript learners.

Happy coding 🚀
