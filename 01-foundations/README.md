# Phase 1: Foundations

Foundations build the vocabulary and design habits needed before studying
patterns or solving full LLD problems. The goal of this phase is to move from
"I can write classes" to "I can assign responsibilities, model relationships,
and explain why the design can change safely."

## Phase Goal

By the end of this phase, you should be able to:

- Identify domain objects from requirements.
- Separate data ownership from behavior ownership.
- Hide internal state behind meaningful methods.
- Use abstraction when behavior can vary.
- Decide when inheritance is appropriate and when composition is safer.
- Read and sketch simple UML class and sequence diagrams.
- Explain design choices using OOP and SOLID language.

## Topic Map

| Order | Topic | Focus | Status |
| ----- | ----- | ----- | ------ |
| 1 | [OOP Principles](oop-principles/README.md) | Encapsulation, abstraction, inheritance, polymorphism | [x] |
| 2 | SOLID Principles | Five maintainability principles with class-level examples | [ ] |
| 3 | UML Diagrams | Class, sequence, activity, and use-case diagrams | [ ] |
| 4 | Object Modeling | Classes, attributes, relationships, and responsibilities | [ ] |

## Study Flow

Use this loop for every foundation topic:

1. Read the concept and summarize it in your own words.
2. Map the concept to a small real-world scenario.
3. Sketch the candidate classes and relationships.
4. Write the smallest working example.
5. Review the design for responsibility, coupling, and extensibility.
6. Record the trade-offs before moving forward.

## Foundation Design Checklist

Before marking a foundation topic complete, check that:

- The concept has a clear definition.
- The example includes real behavior, not only data containers.
- Class names come from the domain language.
- Each class has one main reason to change.
- Object state cannot be made invalid through public access.
- Extension points are intentional and easy to explain.
- At least one trade-off or alternative design is documented.

## Current Position

OOP Principles are complete. Continue with SOLID Principles next so the
foundation work moves from object modeling into maintainable class design.
