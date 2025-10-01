# Strategy Pattern

## Overview
The *Strategy Pattern* allows selecting an algorithm’s behavior at runtime.  
It defines a family of algorithms, encapsulates each one, and makes them interchangeable.

## Intent
- Eliminate conditional statements for algorithm selection.
- Allow runtime behavior change.
- Improve flexibility and reusability.

## Use Case in This Project
This example demonstrates *payment strategies* where different payment methods (e.g., credit card, PayPal) can be chosen dynamically.

## Files
- PaymentStrategy.java → Defines strategy interface and implementations.

## How to Run
```bash
javac PaymentStrategy.java
java PaymentStrategy