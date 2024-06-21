# macOS Scientific Calculator Clone

A web-based clone of the macOS Scientific Calculator built using React. This calculator includes basic arithmetic operations, advanced functions like trigonometry, logarithms, exponents, and special functions (e.g., factorial, random number generation).

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Responsive design that mimics the macOS Scientific Calculator.
- Basic operations: addition, subtraction, multiplication, and division.
- Advanced functions: sine, cosine, tangent, logarithms, exponents, square roots, factorial, random number generation.
- Special feature: Confetti explosion for operations involving 5 and 6 as operands.
- Ability to handle multiple operations and parentheses (order of operations).
- Use previous result as an operand for new calculations.

## Demo

![Calculator Demo](path_to_demo_image_or_gif)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/macos-scientific-calculator.git
    cd macos-scientific-calculator
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

## Usage

1. Start the development server:

    ```sh
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`.

## Technologies Used

- React
- JavaScript
- HTML
- CSS
- [react-confetti-explosion](https://www.npmjs.com/package/react-confetti-explosion)

## File Structure

```plaintext
macos-scientific-calculator/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Button.js
│   │   ├── Button.css
│   │   ├── ButtonPanel.js
│   │   ├── Calculator.js
│   │   ├── Calculator.css
│   │   ├── Display.js
│   │   ├── Display.css
│   │   ├── MemoryButtons.js
│   │   ├── ScientificButtons.js
│   └── logic/
│       ├── calculate.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   ├── index.css
└── package.json
