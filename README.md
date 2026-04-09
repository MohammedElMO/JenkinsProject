# BMI Calculator & Diet Planner (Testing Project)

This project is a Java-based application designed to demonstrate and practice unit testing using **JUnit 5**. It includes business logic for a Body Mass Index (BMI) Calculator and a Diet Planner, tailored primarily for learning how to write effective test cases and configuring continuous integration workflows (e.g., Jenkins polling).

## Features
- **BMI Calculator:** Calculates Body Mass Index, identifies if a diet is recommended based on a threshold, and analyzes a list of users (coders) to find the one with the worst BMI.
- **Diet Planner:** Generates diet plans and recommendations based on user profiles.

## Technical Stack
- **Language:** Java 17
- **Testing Framework:** JUnit 5 (Jupiter API)
- **Build Tool:** Maven

## Project Structure
- `src/main/java`: Contains the core application models and logic (`BMICalculator`, `DietPlanner`, `DietPlan`, `Coder`, `Gender`).
- `src/test/java`: Contains the test suites categorized into:
  - `basics`: Fundamental unit tests covering standard input scenarios.
  - `advancedconcepts`: More complex testing structures, such as nested tests (`BMICalculatorNestedTest.java`) and edge cases.