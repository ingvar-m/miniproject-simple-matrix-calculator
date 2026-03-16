# 🧮 Simple Matrix Calculator

Matrix calculator built with Flutter.

## Technologies

* **Dart / Flutter**
* **State Management:** `ChangeNotifier` / `ListenableBuilder`

## Features

* **Calculations:** Uses a custom `Fraction` class with Euclidean algorithm simplification to prevent standard `double` rounding errors during complex operations like determinants.
* **Advanced Operations:** Supports Unary and Binary operations, Matrix Transposition, and Determinants using both Laplace (recursive minor decomposition) and Gauss (pivot search and elimination) methods.
* **UI:** Pre-allocated 8x8 grid of `TextEditingController`s ensures zero overhead and instantaneous visual resizing.
* **Smart Data Formatting:** Displays results in Decimal, Proper, or Improper fractions. Uses a customized `Table` widget with `IntrinsicColumnWidth` for mathematically perfect vertical alignment.

## Running the Project (Android)

Since this repository contains only the core source code (`lib`) and resources (`assets`), please follow these steps to integrate and run it on an Android device or emulator:

1. Create a new Flutter project.
2. Navigate into your new project directory.
3. Replace the contents of the newly created lib folder with the files from this repository.
4. Connect an Android device or start an Android emulator, then run.

## Preview

![App Demo](https://github.com/ingvar-m/miniproject-simple-matrix-calculator/blob/main/matrix_calculator.gif)
