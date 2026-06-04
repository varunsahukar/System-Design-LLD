# Low-Level Design (LLD) — System Design Roadmap

A structured, progressive learning path to master Low-Level Design concepts, object-oriented principles, design patterns, and real-world system modeling.

---

## Table of Contents

- [Overview](#overview)
- [Roadmap](#roadmap)
  - [Phase 1 — Foundations](#phase-1--foundations)
  - [Phase 2 — Design Patterns](#phase-2--design-patterns)
  - [Phase 3 — Real-World LLD Problems](#phase-3--real-world-lld-problems)
  - [Phase 4 — Advanced Concepts](#phase-4--advanced-concepts)
- [Repository Structure](#repository-structure)
- [Progress Tracker](#progress-tracker)
- [Tech Stack](#tech-stack)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Low-Level Design (LLD) is the practice of **component-level software design** — translating high-level architectural decisions into concrete class structures, object relationships, design patterns, and maintainable code.

Where High-Level Design answers _"What are we building?"_, LLD answers _"How exactly do we build it?"_

This repository is a self-contained roadmap that covers foundational OOP principles, all major Gang of Four design patterns, and a curated set of real-world system design problems commonly asked in engineering interviews at product-based companies.

---

## Roadmap

### Phase 1 — Foundations

Build a solid base in object-oriented thinking and modeling before moving to patterns or problems.

| Topic            | Description                                                          | Status |
| ---------------- | -------------------------------------------------------------------- | ------ |
| OOP Principles   | Encapsulation, Abstraction, Inheritance, Polymorphism                | [ ]    |
| SOLID Principles | SRP, OCP, LSP, ISP, DIP with examples                                | [ ]    |
| UML Diagrams     | Class, Sequence, Activity, and Use-case diagrams                     | [ ]    |
| Object Modeling  | Identifying classes, attributes, and relationships from requirements | [ ]    |

---

### Phase 2 — Design Patterns

Based on the Gang of Four (GoF) catalog. Each pattern includes intent, structure, and a coded example.

#### Creational Patterns

| Pattern          | Intent                                                                              | Status |
| ---------------- | ----------------------------------------------------------------------------------- | ------ |
| Singleton        | Guarantee a single instance across the application                                  | [ ]    |
| Factory Method   | Delegate instantiation to subclasses                                                | [ ]    |
| Abstract Factory | Create families of related objects without specifying concrete classes              | [ ]    |
| Builder          | Construct complex objects step by step, separating construction from representation | [ ]    |
| Prototype        | Create new objects by cloning an existing instance                                  | [ ]    |

#### Structural Patterns

| Pattern   | Intent                                                                   | Status |
| --------- | ------------------------------------------------------------------------ | ------ |
| Adapter   | Convert one interface into another that clients expect                   | [ ]    |
| Decorator | Attach additional responsibilities to objects dynamically                | [ ]    |
| Facade    | Provide a simplified interface to a complex subsystem                    | [ ]    |
| Composite | Compose objects into tree structures to represent part-whole hierarchies | [ ]    |
| Proxy     | Control access to another object through a surrogate                     | [ ]    |

#### Behavioral Patterns

| Pattern                 | Intent                                                                      | Status |
| ----------------------- | --------------------------------------------------------------------------- | ------ |
| Observer                | Define a one-to-many dependency so dependents update automatically          | [ ]    |
| Strategy                | Define a family of algorithms and make them interchangeable at runtime      | [ ]    |
| Command                 | Encapsulate a request as an object for parameterization and queuing         | [ ]    |
| State                   | Allow an object to alter its behavior when its internal state changes       | [ ]    |
| Iterator                | Access elements of a collection sequentially without exposing its structure | [ ]    |
| Chain of Responsibility | Pass a request along a chain of handlers until one handles it               | [ ]    |

---

### Phase 3 — Real-World LLD Problems

Each problem includes a requirements breakdown, class diagram, and full implementation.

| Problem                           | Key Patterns Applied           | Status |
| --------------------------------- | ------------------------------ | ------ |
| Parking Lot                       | OOP, State, Strategy           | [ ]    |
| ATM Machine                       | State Machine, Command         | [ ]    |
| Library Management System         | Relationships, SOLID           | [ ]    |
| Hotel Booking System              | Factory, Observer              | [ ]    |
| Chess Game                        | Composite, Strategy            | [ ]    |
| Elevator System                   | State, Chain of Responsibility | [ ]    |
| Ride-Sharing App (Uber/Ola)       | Observer, Strategy, Factory    | [ ]    |
| Food Delivery App (Swiggy/Zomato) | Builder, Observer, State       | [ ]    |
| E-Commerce Cart                   | Composite, Decorator           | [ ]    |
| Notification System               | Observer, Strategy             | [ ]    |
| LRU Cache                         | Design + Data Structures       | [ ]    |
| Rate Limiter                      | Token Bucket, Sliding Window   | [ ]    |
| Task Manager (Trello-like)        | Composite, State, Command      | [ ]    |
| Expense Splitter (Splitwise)      | Graph, SOLID                   | [ ]    |
| Movie Ticket Booking System       | Factory, State, Observer       | [ ]    |

---

### Phase 4 — Advanced Concepts

Topics that bridge clean design with production-grade engineering.

| Topic                    | Description                                             | Status |
| ------------------------ | ------------------------------------------------------- | ------ |
| Concurrency in LLD       | Thread safety, locks, and concurrent design patterns    | [ ]    |
| Clean Code Principles    | Naming conventions, function design, error handling     | [ ]    |
| Refactoring Techniques   | Identifying code smells and applying targeted refactors | [ ]    |
| Test-Driven Design (TDD) | Writing tests first to drive better LLD decisions       | [ ]    |
| LLD + HLD Integration    | How component design feeds into system architecture     | [ ]    |

---

## Repository Structure

```
lld-system-design/
|
|-- 01-foundations/
|   |-- oop-principles/
|   |-- solid-principles/
|   `-- uml-diagrams/
|
|-- 02-design-patterns/
|   |-- creational/
|   |-- structural/
|   `-- behavioral/
|
|-- 03-problems/
|   |-- parking-lot/
|   |-- atm/
|   |-- chess-game/
|   |-- ride-sharing/
|   `-- ...
|
`-- 04-advanced/
    |-- concurrency/
    |-- clean-code/
    `-- tdd/
```

Each problem folder follows a consistent structure:

```
problem-name/
|-- README.md          # Problem statement, requirements, and approach
|-- diagram.png        # UML class diagram
`-- src/               # Implementation
```

---

## Progress Tracker

| Phase                         | Total Topics | Completed | Progress |
| ----------------------------- | ------------ | --------- | -------- |
| Phase 1 — Foundations         | 4            | 0         | 0%       |
| Phase 2 — Design Patterns     | 16           | 0         | 0%       |
| Phase 3 — Real-World Problems | 15           | 0         | 0%       |
| Phase 4 — Advanced Concepts   | 5            | 0         | 0%       |
| **Total**                     | **40**       | **0**     | **0%**   |

Status convention used across all tables:

| Symbol | Meaning     |
| ------ | ----------- |
| [ ]    | Not started |
| [~]    | In progress |
| [x]    | Completed   |

---

## Tech Stack

| Category         | Tools                           |
| ---------------- | ------------------------------- |
| Primary Language | Java / Python / C++             |
| Diagram Tooling  | draw.io, PlantUML, Excalidraw   |
| Testing          | JUnit 5 (Java), pytest (Python) |
| Documentation    | Markdown                        |

---

## Resources

**Books**

- _Design Patterns: Elements of Reusable Object-Oriented Software_ — GoF (Gamma, Helm, Johnson, Vlissides)
- _Head First Design Patterns_ — Freeman & Robson
- _Clean Code_ — Robert C. Martin
- _Refactoring: Improving the Design of Existing Code_ — Martin Fowler

**Online**

- [Refactoring Guru — Design Patterns](https://refactoring.guru/design-patterns)
- [Grokking the Object-Oriented Design Interview — Educative](https://www.educative.io/courses/grokking-the-object-oriented-design-interview)
- [Source Making — Design Patterns](https://sourcemaking.com/design_patterns)
