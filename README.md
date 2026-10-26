# AquaReach

## Description
AquaReach is a Java-based water donation management system designed to manage water donations and track their distribution to different locations.

## Features
- Add Donations: Record donations from donors, including water bottles, water boxes, and water coolers.
- View Distribution Records: View donation and distribution records, including locations, quantities, statuses, and dates.
- Donation Summary Report: Display the total number of donated water bottles, boxes, and coolers, along with the number of donors.
- Water Stock Management: Manage available water quantities and support restocking and distribution.
- Donor and Location Management: Organize donor information and distribution locations.

## Technologies Used
- Java
- Object-Oriented Programming (OOP)
- Java Collections Framework

## Object-Oriented Programming Concepts
- Inheritance: `WaterBottle`, `WaterBox`, and `WaterCooler` extend `WaterItem`.
- Abstraction: `WaterItem` is an abstract class.
- Interfaces: `Distributable` defines distribution and restocking operations.
- Polymorphism: Different water item types implement their own `displayInfo()` methods.
- Composition: Donors contain donation records, and locations contain placement records.
- Exception Handling: `WaterNotAvailableException` handles unavailable items and insufficient stock.
- Collections: `ArrayList` and `TreeSet` are used to manage and organize project data.

## Water Item Types
- Water Bottles: Each bottle has a capacity of 0.5 liters.
- Water Boxes: Each box contains 6 bottles.
- Water Coolers: Each cooler has a capacity of 20 liters.

## Distribution Locations
The system supports the following location types:
- Mosque
- Hospital
- University
- Walkway
- Park

## How to Run
1. Clone or download this repository.
2. Open the project in NetBeans IDE.
3. Locate the `AquaReach.java` class in the `aquareach` package.
4. Run the `AquaReach.java` file.
5. Follow the console menu to manage donations and view reports.

## Authors
- Reham Alhawsawi
- Elham Alzahrani

## Project Type
University Java Programming Project
