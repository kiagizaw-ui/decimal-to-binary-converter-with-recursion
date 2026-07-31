# 🔢 Decimal to Binary Converter

A simple and interactive **Decimal to Binary Converter** built with **HTML, CSS, and JavaScript**. This project converts a decimal number into its binary equivalent using **recursion**, helping demonstrate how recursive functions solve problems by repeatedly calling themselves until reaching a base case.


## ✨ Features

- Convert decimal numbers to binary
- Uses **recursion** instead of loops
- Animated conversion process
- Input validation
- Clean and responsive user interface
- Beginner-friendly JavaScript project

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript (ES6)

## 📂 Project Structure

```
decimal-to-binary-converter/
│
├── index.html
├── styles.css
├── script.js
└── README.md
```

## 🧠 How It Works

The application:

1. Takes a decimal number from the user.
2. Uses a **recursive function** to divide the number by 2.
3. Stores the remainder from each recursive call.
4. Combines the remainders in reverse order to produce the binary representation.
5. Displays an animated visualization of the conversion process.

### Example

| Decimal | Binary |
|---------:|:------:|
| 2 | 10 |
| 5 | 101 |
| 10 | 1010 |
| 15 | 1111 |
| 32 | 100000 |

## 📖 Recursion Explained

Recursion is a programming technique where a function calls itself until it reaches a stopping condition (called the **base case**).

Example:

```javascript
function decimalToBinary(num) {
  if (num === 0) {
    return "";
  }

  return decimalToBinary(Math.floor(num / 2)) + (num % 2);
}
```

Each recursive call reduces the problem into a smaller one until it reaches the base case.

## 🚀 Getting Started

1. Clone the repository.

```bash
git clone https://github.com/kiagizaw-ui/decimal-to-binary-converter.git
```

2. Navigate into the project folder.

```bash
cd decimal-to-binary-converter
```

3. Open `index.html` in your browser.

No additional installation is required.

## 🎯 What I Learned

Through this project, I learned:

- How recursion works in JavaScript
- Base cases and recursive calls
- DOM manipulation
- Event handling
- Input validation
- Updating the UI dynamically
- Creating simple animations with JavaScript

## 🔮 Future Improvements

- Convert binary back to decimal
- Support octal and hexadecimal conversions
- Dark mode
- Conversion history
- Copy result button

## 👨‍💻 Author

**Kiya Gizaw**

- GitHub: https://github.com/kiagizaw-ui 


