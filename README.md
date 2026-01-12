Java Console Banking System

A lightweight, command-line application that simulates essential bank account operations. Built using Java within the Eclipse IDE, this project demonstrates core Object-Oriented Programming (OOP) concepts.

Interface & Controls:
The application runs a continuous loop allowing the user to perform multiple transactions until they choose to exit.

System Logic

The system is built on a single-file architecture (`BankingApplication.java`) containing two main classes:

1.  `BankingApplication` (Main):
    * Initializes the session.
    * Creates a `BankAccount` object with a hardcoded User Name and ID ("Sheem", "BA00001").
    * Triggers the menu interface.

2.  `BankAccount` (Logic):
    * State Management:** Tracks `balance` and `previousTransaction`.
    * Math.abs():** Used in the logic to ensure transaction history is displayed as absolute positive numbers.
    * Input Handling:** Uses `java.util.Scanner` to read characters and integers from the console.

