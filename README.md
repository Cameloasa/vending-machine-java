# Vending Machine – Java OOP Project

This project is a simple Java OOP implementation of a vending machine.
It demonstrates object‑oriented design, inheritance, interfaces, and basic application logic without external frameworks.

## 🎯 Project Purpose

The goal of this project is to practice:

- Java classes and objects

- Inheritance and polymorphism

- Interfaces

- Arrays and basic collections

- Encapsulation

- Simple business logic

- Clean code structure

- Unit testing with JUnit 5

This project is part of a series of older Java exercises that are currently being updated and prepared for future improvements.

## 📦 Current Features

Multiple product types:

- Drink

- Candy

- Snack

Vending machine logic:

- addCurrency

- getBalance

- request

- getProducts

- getDescription

Basic console output

Clean formatting using Spotless

Code quality checks using Checkstyle

JUnit 5 test support

## 🧪 Running the Project

Compile:

```bash
mvn compile
```

Run:

```bash
mvn exec:java
```

Run tests:

```bash
mvn test
```

Full rebuild:

```bash
mvn clean install
```

## 🎨 Code Formatting & Linting

Format code (Spotless):

```bash
mvn spotless:apply
```

Check code style (Checkstyle):

```bash
mvn checkstyle:check
```

## 📁 Project Structure

```text
src/
  main/
    java/
      dev/cameloasa/
        model/
        App.java
        VendingMachineImpl.java
  test/
    java/
      dev/cameloasa/
```

## 🚀 Planned Improvements (Future Work)

This project will later be upgraded to a full backend application using:

- Spring Boot

- SQLite database

- Repository layer

- Service layer

- REST controllers

- DTOs & mapping (MapStruct)

- Validation & exception handling

But for now, the focus is on cleaning and modernizing the older Java OOP projects.

## 📝 Notes

This project is part of a collection of older Java exercises that are being updated and prepared for migration into the GitHub organization.
The current version is intentionally simple and does not use frameworks or databases.
