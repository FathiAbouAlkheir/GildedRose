# Gilded Rose starting position in C# NUnit

## Overview

The Gilded Rose Refactoring Kata is a coding exercise designed to help improve your refactoring and software design skills. The project involves a system that manages the inventory of an inn, where items degrade in quality over time. The goal is to add new features and refactor the existing code without altering the core functionality of the system.

## Project Structure

- **GildedRose.cs**: Contains the `GildedRose` class responsible for updating item quality and sell-in values.
- **Item.cs**: Defines the `Item` class with properties for `Name`, `SellIn`, and `Quality`.
- **Program.cs**: Contains the `Main` method which demonstrates the functionality of the `GildedRose` system.
- **GildedRoseTests**: Contains NUnit tests to validate the functionality of the system.
  - **ApprovalTest.cs**: Includes tests that verify the system output against expected results.
  - **GildedRoseTest.cs**: Contains various unit tests for different item types.

## Features

1. **Standard Items**: Items degrade in quality over time, and the rate of degradation increases after the sell-by date.
2. **Aged Brie**: Quality increases as it gets older.
3. **Sulfuras**: A legendary item that never degrades in quality or changes its sell-by date.
4. **Backstage Passes**: Quality increases as the sell-by date approaches and drops to 0 after the concert.
5. **Conjured Items**: These items degrade in quality twice as fast as normal items.

## Setup

To run the project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/FathiAbouAlkheir/GildedRose.git
   cd GildedRose
2. **Open the Project:**
   Open GildedRose.sln in your preferred C# IDE (e.g., Visual Studio or VS Code).
