# ABSTRACTION-AUTOMATION-SYSTEM
# ABSTRACTION - Automation System

## Overview
This repository contains the solution for the Week 7 OOP Abstraction Lab for UMaT's new automated auditorium system. 

The project demonstrates object-oriented abstraction in Python using the abc module. By defining an abstract base class BuildingSystem, we enforce a uniform contract (start(), stop(), and status()) across various sub-systems without forcing a rigid shared implementation.

## Project Structure
- BuildingSystem (Abstract Base Class): Enforces the interface contract.
- Subclasses implementing the contract:
  - AirConditioningSystem
  - LightingSystem
  - SecuritySystem
  - FireAlarmSystem (demonstrates system extensibility without modifying existing loop processing)

## Requirements & Design
- Uses Python's built-in abc module (ABC and @abstractmethod).
- Demonstrates polymorphic behaviour by processing all instantiated systems through a single loop interface.

## How to Run
1. Clone the repository:
   `bash
   git clone [https://github.com/](https://github.com/)<pascalyaovi>/ABSTRACTION-Automation-System.git
