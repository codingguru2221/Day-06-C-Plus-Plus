# Day 6: Mathematical Functions and Booleans in C++

Welcome to **Day 6** of my C++ learning journey! This series is created by **The Codex**, and today, I explored **mathematical functions** and **booleans** in C++. This repository contains examples, explanations, and resources to help you understand these concepts in depth.

---

## Table of Contents
1. [Mathematical Functions](#mathematical-functions)
2. [Booleans](#booleans)
3. [Code Examples](#code-examples)
4. [How to Use](#how-to-use)
5. [Tips for Learning](#tips-for-learning)
6. [Resources](#resources)
7. [Contributing](#contributing)

---

## Mathematical Functions

C++ provides a powerful set of mathematical functions through the `<cmath>` library. These functions allow you to perform advanced mathematical operations, making it easier to handle complex calculations in your programs.

### Commonly Used Mathematical Functions:
- **`sqrt(x)`**: Computes the square root of `x`.
- **`pow(x, y)`**: Raises `x` to the power of `y`.
- **`abs(x)`**: Returns the absolute value of `x`.
- **`sin(x)`**, **`cos(x)`**, **`tan(x)`**: Trigonometric functions (input in radians).
- **`log(x)`**: Computes the natural logarithm of `x`.
- **`log10(x)`**: Computes the base-10 logarithm of `x`.
- **`ceil(x)`**: Rounds `x` up to the nearest integer.
- **`floor(x)`**: Rounds `x` down to the nearest integer.
- **`round(x)`**: Rounds `x` to the nearest integer.

### Example Usage:
```cpp
#include <iostream>
#include <cmath>

int main() {
    double num = 9.0;
    std::cout << "Square root of " << num << " is " << sqrt(num) << std::endl;
    std::cout << "2^3 is " << pow(2, 3) << std::endl;
    std::cout << "Ceil of 3.7 is " << ceil(3.7) << std::endl;
    return 0;
}
```

---

## Booleans

Booleans are a fundamental data type in C++ used to represent **true** or **false** values. They are essential for controlling the flow of your program using conditional statements and loops.

### Key Points:
- The `bool` data type can hold two values: `true` (1) or `false` (0).
- Boolean expressions are often created using **relational operators**:
  - `==` (equal to)
  - `!=` (not equal to)
  - `>` (greater than)
  - `<` (less than)
  - `>=` (greater than or equal to)
  - `<=` (less than or equal to)
- **Logical operators** are used to combine boolean expressions:
  - `&&` (logical AND)
  - `||` (logical OR)
  - `!` (logical NOT)

### Example Usage:
```cpp
#include <iostream>

int main() {
    bool isRaining = true;
    bool isSunny = false;

    if (isRaining && !isSunny) {
        std::cout << "Take an umbrella!" << std::endl;
    } else {
        std::cout << "Enjoy the weather!" << std::endl;
    }

    return 0;
}
```

---

## Code Examples

### Example 1: Mathematical Functions
```cpp
#include <iostream>
#include <cmath>

int main() {
    double x = 25.0;
    double y = 3.0;

    std::cout << "Square root of " << x << " is " << sqrt(x) << std::endl;
    std::cout << x << " raised to the power of " << y << " is " << pow(x, y) << std::endl;
    std::cout << "Absolute value of -10 is " << abs(-10) << std::endl;
    std::cout << "Ceil of 4.3 is " << ceil(4.3) << std::endl;
    std::cout << "Floor of 4.7 is " << floor(4.7) << std::endl;

    return 0;
}
```

### Example 2: Booleans and Logical Operators
```cpp
#include <iostream>

int main() {
    int age = 18;
    bool hasLicense = true;

    if (age >= 18 && hasLicense) {
        std::cout << "You are eligible to drive!" << std::endl;
    } else {
        std::cout << "You are not eligible to drive." << std::endl;
    }

    return 0;
}
```

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the repository:
   ```bash
   cd your-repo-name
   ```
3. Compile and run the C++ files:
   ```bash
   g++ example1.cpp -o example1
   ./example1
   ```

---

## Tips for Learning

1. **Practice Regularly**: Write small programs to experiment with mathematical functions and booleans.
2. **Debugging**: Use `std::cout` to print intermediate values and debug your code.
3. **Read Documentation**: Refer to the [C++ documentation](https://en.cppreference.com/) for detailed explanations of functions and libraries.
4. **Experiment**: Try combining mathematical functions and booleans in creative ways to solve problems.

---

## Resources

- [C++ `<cmath>` Library Reference](https://en.cppreference.com/w/cpp/header/cmath)
- [C++ Boolean and Logical Operators](https://www.learncpp.com/cpp-tutorial/boolean-values/)
- [C++ Tutorial for Beginners](https://www.w3schools.com/cpp/)

---

## Contributing

If you have suggestions, improvements, or additional examples, feel free to open an issue or submit a pull request. Let's learn and grow together!

---

**Created by The Codex**  
Be prepared 🚀
```
