# 🔢 Factorial Calculator

A simple JavaScript utility that calculates the factorial of any non-negative integer using an efficient iterative approach.

---

## 📋 Features

- Computes the factorial of any non-negative integer
- Uses an **iterative loop** — no recursion, no stack overflows
- Outputs a clean, readable result message
- Lightweight with **zero dependencies**

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine

### Installation

Clone the repository:

```bash
git clone https://github.com/lorddrago12/Factorial-Calculator.git
```

Navigate into the project directory:

```bash
cd Factorial-Calculator
```

Run the application:

```bash
node main.js
```

---

## 🗂️ Project Structure

```
-Factorial-Calculator/
├── main.js        # Main application logic
└── README.md      # Project documentation
```

---

## 📊 Sample Outputs

| Input | Output       |
|-------|--------------|
| `0`   | `1`          |
| `1`   | `1`          |
| `5`   | `120`        |
| `10`  | `3628800`    |
| `12`  | `479001600`  |

---

## 🧠 How It Works

The core function uses a `for` loop to multiply all integers from `1` up to the given number:

```js
function factorialCalculator(number) {
  let result = 1;
  for (let i = 1; i <= number; i++) {
    result *= i;
  }
  return result;
}
```

The result is then logged to the console:

```js
const num = 10;
const factorial = factorialCalculator(num);
console.log(`Factorial of ${num} is ${factorial}`);
// Output: Factorial of 10 is 3628800
```

---

## 🛠️ Built With

- **JavaScript** (vanilla, no dependencies)
- **Node.js**

---

## 🤝 How to Contribute

Contributions are welcome! Follow these steps to contribute:

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/your-username/Factorial-Calculator.git
   ```
3. **Create** a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make** your changes and commit:
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push** to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a **Pull Request** and describe what you changed

---
