📘 Exercise_1 & SmartOffice Projects

This repository contains two Java-based projects:

Exercise_1 – A collection of coding exercises that demonstrate important Design Patterns (Creational, Structural, Behavioral).

SmartOffice – A smart office simulation system with booking, occupancy tracking, and IoT-inspired device control.

Both are intended for learning object-oriented programming, design principles, and real-world system simulation.

📂 Repository Structure
root/
│── Exercise_1/                  # Design pattern exercises
│   ├── Behavioural design pattern/
│   │   ├── Observer Pattern/StockChange.java
│   │   └── Strategy Pattern/PaymentStrategy.java
│   ├── Creational design pattern/
│   │   ├── Factory Pattern/FoodDeliveryApp.java
│   │   └── Singleton Pattern/SingletonDB.java
│   ├── Structural design pattern/
│   │   ├── Adapter Pattern/SocialMediaApp.java
│   │   └── Decorator Pattern/DecoratorUseCase.java
│   └── .git/                    
│
│── SmartOffice/                 # Smart office management system
│   ├── src/com/smartoffice/     # Java source files
│   ├── out/com/smartoffice/     # Compiled classes
│   ├── run.txt                  # Run instructions
│   └── sources.txt              # Source listing
│
└── README.md

📚 Exercise_1 – Design Pattern Demos

A collection of Java programs demonstrating design patterns:

Creational Patterns

Factory Pattern → FoodDeliveryApp.java

Singleton Pattern → SingletonDB.java

Structural Patterns

Adapter Pattern → SocialMediaApp.java

Decorator Pattern → DecoratorUseCase.java

Behavioral Patterns

Observer Pattern → StockChange.java

Strategy Pattern → PaymentStrategy.java

▶ Run Example
# Compile & run a specific example
javac Exercise_1/Creational\ design\ pattern/Factory\ Pattern/FoodDeliveryApp.java
java Exercise_1.Creational.design.pattern.FactoryPattern.FoodDeliveryApp

🚀 SmartOffice – Office Simulation

A Java application that simulates smart office operations with room booking, sensors, and IoT-style devices.

✨ Features

Room booking & cancellation system.

Occupancy tracking with sensors.

Configurable room capacity.

Device management (Lights, Air Conditioners).

Notifications (SMS, Email).

Command pattern for flexible actions.

▶ Run Instructions (from run.txt)
javac -d out src/com/smartoffice//*.java
java -cp out com.smartoffice.SmartOfficeApp

🛠 Requirements

Java JDK 8+

Any IDE (Eclipse, IntelliJ, VS Code) or command-line tools.

🧪 Testing

Run individual .java files inside Exercise_1 for design pattern examples.

Run SmartOfficeApp in the SmartOffice project for simulation.