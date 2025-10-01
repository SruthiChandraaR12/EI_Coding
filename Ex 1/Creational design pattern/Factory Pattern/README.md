# Factory Pattern

## Overview
The *Factory Pattern* provides an interface for creating objects but lets subclasses decide which class to instantiate.

## Intent
- Hide object creation logic.
- Promote loose coupling.
- Create objects without exposing the instantiation logic.

## Use Case in This Project
This example simulates a *food delivery application* where the factory creates appropriate food objects dynamically.

## Files
- FoodDeliveryApp.java → Implements factory logic for food delivery.

## How to Run
```bash
javac FoodDeliveryApp.java
java FoodDeliveryApp