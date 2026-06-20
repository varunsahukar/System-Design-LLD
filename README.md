# Low-Level Design (LLD) — System Design Roadmap

A structured, progressive learning path to master Low-Level Design concepts, object-oriented principles, design patterns, and real-world system modeling.

---

## Table of Contents

- [Overview](#overview)
- [Quick Start Checklist](#quick-start-checklist)
- [Learning Process](#learning-process)
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

## Quick Start Checklist

Use this checklist when you open the repository for a new study session:

- Pick the next unchecked topic from the roadmap.
- Read the concept and write a short summary in your own words.
- Sketch the expected classes, interfaces, and relationships.
- Implement the smallest working version before adding extra features.
- Add tests for core behavior and one edge case.
- Update the status table before moving to the next topic.

---

## Learning Process

### How to Use This Roadmap

This repository is designed as a **progressive, hands-on learning path**. Follow these principles:

#### 1. **Learn in Phase Order**

Complete phases sequentially. Each phase builds upon the previous one:

- **Phase 1** establishes the mental models needed for design
- **Phase 2** teaches reusable patterns built on strong foundations
- **Phase 3** applies patterns to realistic scenarios
- **Phase 4** bridges component design with production engineering

#### 2. **Understand Before Implementing**

For each topic:

1. Read the concept explanation
2. Study the provided diagrams and examples
3. Understand the trade-offs and when to use it
4. Then implement from scratch (without looking at reference code initially)

#### 3. **Code-First Learning**

- **Do not just read**. Write code for every pattern and problem
- Implement in your chosen language (Java, Python, or C++)
- Create unit tests to validate your implementation
- Refactor and optimize after it works

#### 4. **Real-World Context**

Connect theory to practice:

- For Phase 3 problems, start with requirements, not code
- Draw a class diagram before coding
- Identify which patterns apply and why
- Discuss trade-offs with peers or in design reviews

---

### Prerequisites and Setup

**What You Should Know Before Starting**

- **Basic Programming**: Comfortable with OOP concepts (classes, inheritance, interfaces)
- **Data Structures**: Familiarity with arrays, linked lists, trees, hash maps
- **Git**: Basic commands for cloning, committing, and pushing

**Setting Up Locally**

```bash
# 1. Clone this repository
git clone https://github.com/varunsahukar/System-Design-LLD-.git
cd System-Design-LLD-

# 2. Set up your language environment
# For Java: Ensure JDK 11+ and Maven are installed
# For Python: Ensure Python 3.8+ is installed
# For C++: Ensure C++17 compiler and CMake are installed

# 3. Navigate to a problem directory and start coding
cd 03-problems/parking-lot/
```

**Best Practices for This Repository**

- Create a **feature branch** for each problem you solve: `git checkout -b feature/solve-parking-lot`
- Commit incrementally as you make progress
- Push your work regularly to avoid data loss
- Compare your implementation with reference solutions after completing your own version
- Leave detailed comments in your code explaining design decisions

---

### Suggested Learning Timeline

**Recommended Pace: 12–16 Weeks** (assuming 5–10 hours per week)

| Phase   | Topics                            | Suggested Duration | Focus                                         |
| ------- | --------------------------------- | ------------------ | --------------------------------------------- |
| Phase 1 | Foundations (4 topics)            | 2–3 weeks          | Core concepts, mental models                  |
| Phase 2 | Design Patterns (16 patterns)     | 5–6 weeks          | One pattern every 2 days, code examples       |
| Phase 3 | Real-World Problems (15 problems) | 4–5 weeks          | One problem per 4–5 days, full implementation |
| Phase 4 | Advanced Concepts (5 topics)      | 1–2 weeks          | Integration, best practices, optimization     |

**Weekly Study Routine (Suggested)**

**Days 1–2**: Theory

- Read the concept/pattern documentation
- Study provided diagrams and class structures
- Understand the problem statement (for Phase 3)

**Days 3–5**: Implementation

- Design the solution (UML diagram or pseudocode)
- Write code from scratch
- Implement unit tests
- Compare with reference solution

**Days 6–7**: Reflection & Consolidation

- Refactor and optimize your code
- Write a brief summary in comments
- Discuss trade-offs and alternative approaches
- Mark progress in this README

---

### Tips for Success

**Active Learning Strategies**

1. **Teach Others**: Explain concepts to a peer or write a blog post
2. **Implement Variations**: Modify problems slightly to deepen understanding
   - Example: Add multi-threading to the Parking Lot system
   - Example: Add search filters to the Library system
3. **Code Reviews**: Review others' implementations and provide feedback
4. **Interview Simulation**: Time yourself solving Phase 3 problems (1–1.5 hours)
5. **Diagram First**: Always sketch class and sequence diagrams before coding

**Design Review Checklist**

- Every class has one clear responsibility
- Public methods expose behavior, not internal data structure details
- Object relationships match the requirements and diagram
- Extension points are intentional and not speculative
- Error cases are modeled explicitly
- Tests cover the main flow, boundary cases, and invalid inputs

**Common Pitfalls to Avoid**

- ❌ Reading without coding → Passive learning leads to retention loss
- ❌ Rushing through phases → Weak foundations cause confusion later
- ❌ Ignoring SOLID principles → Code becomes unmaintainable
- ❌ Copying reference solutions directly → Misses learning opportunity
- ❌ Not testing your code → Missing edge cases and bugs

### Assessment Checkpoints

**Milestone 1: End of Phase 1** (Weeks 2–3)

- [ ] Can explain OOP principles with real-world examples
- [ ] Have created 2–3 UML diagrams from scratch
- [ ] Understand when and why to apply SOLID principles

**Milestone 2: Mid-Phase 2** (Week 4)

- [ ] Have implemented 8 creational and structural patterns
- [ ] Can identify patterns in existing codebases
- [ ] Understand trade-offs between similar patterns

**Milestone 3: End of Phase 2** (Week 6)

- [ ] Have implemented all 16 GoF patterns
- [ ] Can explain the difference between each behavioral pattern
- [ ] Comfortable combining multiple patterns in one system

**Milestone 4: Phase 3 Completion** (Week 10)

- [ ] Have fully implemented 8–10 real-world problems
- [ ] Each implementation includes unit tests
- [ ] Can explain pattern choices and trade-offs
- [ ] Solutions handle edge cases robustly

**Milestone 5: Capstone** (Week 12–16)

- [ ] Understand concurrency and thread safety in LLD
- [ ] Can apply clean code principles to large codebases
- [ ] Have written or reviewed refactoring documents
- [ ] Ready for system design interviews

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


> Tip: Update your progress tracker after each study session so you can measure momentum and identify where to focus next.

Update the completed counts and progress percentages every time you finish a topic, so the roadmap stays accurate and actionable.

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

---

## Contributing

Contributions are welcome. If you want to add a new problem, improve an existing solution, or fix a diagram, please follow this workflow:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/add-snake-game-lld`
3. Commit your changes with a clear message.
- Use a descriptive feature branch name, e.g. `feature/solve-parking-lot` or `improvement/refactor-user-service`.
- Push each focused change as its own commit and keep pull requests small.
4. Open a pull request with a description of what was added or changed.

Please ensure every new problem includes a `README.md`, a class diagram, and a working implementation with tests where applicable.

---

## Frequently Asked Questions (FAQ)

**Q: Should I learn all patterns before starting Phase 3 problems?**

A: Yes, it's recommended to complete Phase 2 first. The problems in Phase 3 combine multiple patterns, and having solid pattern knowledge makes them easier to understand and implement.

**Q: Can I skip patterns I already know?**

A: Yes, but ensure you understand each pattern deeply. Even if you've seen a pattern before, implementing it from scratch in this repository reinforces learning. Use your existing knowledge to move faster through those sections.

**Q: How long does each problem typically take to solve?**

A: Phase 3 problems typically take 4–8 hours to complete fully (design + implementation + testing + refactoring). Don't rush; quality implementation is more valuable than speed.

**Q: Should I look at reference solutions?**

A: Implement the problem first without looking at solutions. After completing your version, review reference solutions to learn alternative approaches and identify improvements.

**Q: Can I use different languages for different problems?**

A: Absolutely! This repository supports Java, Python, and C++. Mixing languages deepens your understanding of OOP concepts across different paradigms.

**Q: How do I know if my design is good?**

A: Your design is good if:

- It follows SOLID principles
- Classes have single, well-defined responsibilities
- Relationships between classes are clear and minimal
- It's easy to extend without modifying existing code
- Tests pass and edge cases are handled

**Q: Do I need to memorize all 16 design patterns?**

A: No, but you should understand their intent, trade-offs, and when to apply them. Practical experience (through implementation) makes patterns memorable naturally.

---

## Troubleshooting Guide

### Common Issues and Solutions

**Issue: I don't understand a design pattern**

_Solution:_

- Read the official GoF book chapter (referenced in Resources)
- Study the intent and when to use it before looking at code
- Check multiple examples (this repo + Refactoring Guru)
- Implement a simple version before the full pattern

**Issue: My code works but feels over-engineered**

_Solution:_

- You may be applying patterns unnecessarily. Patterns solve specific problems.
- Start with the simplest solution that works
- Refactor to introduce patterns only when needed
- Remember: "Premature optimization is the root of all evil"

**Issue: I'm stuck on a real-world problem (Phase 3)**

_Solution:_

- Break the problem into smaller components
- Focus on one class/module at a time
- Draw a class diagram before writing code
- Check the problem's README for hints on patterns to use
- Implement one use case fully before adding others

**Issue: I don't know where to start designing a solution**

_Solution:_
Follow this sequence:

1. List all entities/objects (User, Account, Transaction, etc.)
2. Identify relationships (one-to-one, one-to-many, etc.)
3. Define responsibilities for each class
4. Identify which patterns apply
5. Draw the class diagram
6. Implement one entity at a time

**Issue: My test coverage is low**

_Solution:_

- Write tests for edge cases (null values, empty collections, boundary conditions)
- Test error scenarios (invalid inputs, exceptions)
- Test interactions between classes (integration tests)
- Aim for at least 80% code coverage for Phase 3 problems

**Issue: I'm not sure if my design violates SOLID principles**

_Solution:_
Check each principle:

- **S**RP: Does each class have one reason to change?
- **O**CP: Can I extend without modifying existing code?
- **L**SP: Can derived classes substitute base classes?
- **I**SP: Do classes implement only needed methods?
- **D**IP: Do I depend on abstractions, not concrete classes?

---

## Community & Support

### Getting Help

**When you're stuck:**

1. **Check the problem's README** — It often contains hints and links to relevant patterns
2. **Review Refactoring Guru** — Excellent visual explanations of all GoF patterns
3. **Search GitHub Issues** — Check if someone else had the same question
4. **Create an Issue** — Describe your problem clearly with code snippets
5. **Join discussions** — Engage with other learners solving the same problems

### Contributing Solutions

We welcome contributions! Here's how:

1. **Solve a problem** using this repository's structure
2. **Write clean code** with meaningful names and comments
3. **Add unit tests** (aim for high coverage)
4. **Create a UML diagram** (PNG or Excalidraw)
5. **Submit a Pull Request** with a clear description

**PR Guidelines:**

- One problem per PR
- Include tests and diagrams
- Ensure code follows the language's conventions
- Reference relevant patterns in comments
- Compare your approach with alternatives

### Sharing Your Progress

Consider documenting your journey:

- Write a **blog post** on what you learned
- Create **implementation notes** in your fork
- Share your **UML diagrams** and design decisions
- Discuss **trade-offs** you discovered

Your experience helps others learn better!

---

## Quick Reference Guide

### Design Pattern Categories at a Glance

**Creational Patterns** (Object Creation)
| Pattern | Use When | Key Benefit |
|---------|----------|------------|
| Singleton | Need exactly one instance | Global access, resource control |
| Factory Method | Creating objects polymorphically | Decouple client from concrete classes |
| Abstract Factory | Creating families of related objects | Ensure object family consistency |
| Builder | Complex object construction | Clean API, step-by-step building |
| Prototype | Clone objects instead of new instances | Avoid expensive initialization |

**Structural Patterns** (Object Composition)
| Pattern | Use When | Key Benefit |
|---------|----------|------------|
| Adapter | Bridge incompatible interfaces | Reuse incompatible classes |
| Decorator | Add behavior dynamically | More flexible than inheritance |
| Facade | Simplify complex subsystems | Single entry point, reduced coupling |
| Composite | Tree-like hierarchies | Treat individual and composite uniformly |
| Proxy | Control object access | Lazy loading, security, caching |

**Behavioral Patterns** (Object Interaction)
| Pattern | Use When | Key Benefit |
|---------|----------|------------|
| Observer | Notify multiple objects of state change | Loose coupling, real-time updates |
| Strategy | Multiple interchangeable algorithms | Runtime algorithm selection |
| Command | Encapsulate requests as objects | Queuing, undo/redo, logging |
| State | Alter behavior based on internal state | Cleaner than large switch statements |
| Iterator | Traverse collections uniformly | Hide internal structure |
| Chain of Responsibility | Pass requests along handler chain | Decouple sender from receiver |

### SOLID Principles Quick Check

- **S** — Single Responsibility: One class, one reason to change
- **O** — Open/Closed: Open for extension, closed for modification
- **L** — Liskov Substitution: Derived classes can replace base classes
- **I** — Interface Segregation: Many specific interfaces, not one general
- **D** — Dependency Inversion: Depend on abstractions, not concretions

### Common Problem Patterns

| Problem Type               | Likely Patterns                  | Phase |
| -------------------------- | -------------------------------- | ----- |
| System state management    | State, Command, Memento          | 3     |
| Multiple similar behaviors | Strategy, Decorator, Composite   | 3     |
| Object creation            | Singleton, Factory, Builder      | 3     |
| Complex workflows          | Chain of Responsibility, Command | 3     |
| Real-time updates          | Observer, Publisher-Subscriber   | 3     |
| Resource pooling           | Singleton, Object Pool           | 3     |
| Transparent caching        | Proxy, Decorator                 | 3     |

### Implementation Checklist

Before submitting your Phase 3 solution:

- [ ] All classes follow SOLID principles
- [ ] At least 2–3 design patterns applied appropriately
- [ ] Unit tests cover normal and edge cases (80%+ coverage)
- [ ] UML class diagram included
- [ ] No hardcoded values (use constants or configuration)
- [ ] Error handling for invalid inputs
- [ ] Code is readable with meaningful names
- [ ] Comments explain "why", not "what"
- [ ] No circular dependencies between classes
- [ ] Extensible for future requirements

---

## License

This project is licensed under the [MIT License](./LICENSE).

---

_Maintained as an open learning resource for software engineers preparing for system design interviews or deepening their understanding of object-oriented design._
