# CS81 Module 3B – Math Toolkit Builder

This project is part of **Module 3 Assignment 3B** for Santa Monica College's CS81 JavaScript Programming course.  
It focuses on creating a custom JavaScript math toolkit using functions, documenting predictions and results, and using Git for version tracking.

---

## Repository Structure

```
.
├── math.js           # JavaScript file with all math utility functions
├── index.js          # Entry point to test functions via console (CommonJS)
├── PREDICTIONS.md    # Predictions of what each function is expected to do
├── RESULTS.md        # Actual results after running and testing each function
├── REFLECTION.md     # Final reflection on the process and learning
└── README.md         # Project overview and usage instructions
```

---

## Requirements

- Node.js installed (v14 or higher recommended)
- Git (for cloning the repository)

---

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/sergehall/cs81-module3b-toolkit.git
cd cs81-module3b-toolkit
```

2. **Install Node.js** (if not already installed)

Visit https://nodejs.org and download for your system.

3. **Run the test file to view function outputs**

```bash
node index.js
```

This will run all math functions (`double`, `square`, `isEven`, `isOdd`, `multiply`) and display results in the console.

---

## Functions Included

- `double(n)` – Returns n * 2
- `square(n)` – Returns n * n
- `isEven(n)` – Returns true if n is divisible by 2
- `isOdd(n)` – Returns true if n is not divisible by 2
- `multiply(a, b)` – Returns the product of two numbers

Each function is:
- Described in `PREDICTIONS.md` (expected behavior)
- Tested and logged in `RESULTS.md` (actual behavior)
- Reflected on in `REFLECTION.md` (insights and learning)

---

## What This Assignment Covers

- JavaScript function creation  
- Testing and debugging logic  
- Clean, reusable coding practices  
- Git & GitHub version tracking  
- Writing predictions, results, and reflection  

---

## Submission Requirements

- [x] `math.js` — contains all required functions
- [x] `PREDICTIONS.md` — your expected outputs
- [x] `RESULTS.md` — tested results
- [x] `REFLECTION.md` — thoughts and patterns
- [x] At least **5 separate commits**

## License

This project is for educational purposes only as part of Santa Monica College's CS81 coursework.
