# Observer Pattern

## Overview
The *Observer Pattern* defines a one-to-many dependency between objects.  
When one object (the subject) changes state, all its dependents (observers) are notified and updated automatically.

## Intent
- Establish a publish/subscribe mechanism.
- Decouple subjects from observers.
- Useful when changes in one object should update others automatically.

## Use Case in This Project
This example simulates *stock changes* where observers get notified whenever the stock value updates.

## Files
- StockChange.java → Demonstrates subject and observer interaction.

## How to Run
```bash
javac StockChange.java
java StockChange