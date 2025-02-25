# Software Architecture - Summary (Based on Ian Sommerville, Chapter 6)

## Overview
This document provides a summary of key points from Chapter 6 of Ian Sommerville’s book on **Software Architecture**. It highlights essential architectural concepts, design decisions, and best practices for structuring software systems.

## Key Points

### 1. **Introduction to Software Architecture**
- Software architecture defines the high-level structure of a system.
- It involves defining software components, their relationships, and interactions.
- A well-designed architecture improves maintainability, scalability, and performance.

### 2. **Architectural Design Decisions**
- Selecting appropriate architectural patterns.
- Considering system requirements (functional and non-functional).
- Addressing quality attributes such as security, performance, and availability.

### 3. **Common Architectural Patterns**
```plaintext
- Layered Architecture: Organizes the system into hierarchical layers (e.g., presentation, business logic, data).
- Client-Server Architecture: Divides the system into clients that request services and servers that provide them.
- Microservices Architecture: Breaks down the application into small, independent services.
- Model-View-Controller (MVC): Separates concerns into models (data), views (UI), and controllers (logic).
```

### 4. **Architectural Styles and Their Trade-offs**
```plaintext
- Monolithic vs. Microservices: Monolithic architectures are easier to develop but harder to scale; microservices offer flexibility but increase complexity.
- Event-Driven Architectures: Improve decoupling but require careful event handling.
- Service-Oriented Architecture (SOA): Facilitates interoperability but requires strong governance.
```

### 5. **Evaluation and Documentation**
```plaintext
- Architectural Views: Different perspectives (e.g., logical, physical, development, process views) help stakeholders understand the system.
- Quality Attribute Scenarios: Testing architecture against expected performance, reliability, and security needs.
- Architectural Decision Records (ADR): Capturing key design decisions and their rationale.
```

### 6. **Download the PDF**
[Download Software Architecture PDF](https://drive.google.com/file/d/1JtH1TFIp9iUYP35IomBq9FFKvvtIB-GU/view)

---

## Conclusion
A well-structured software architecture is critical for building robust, scalable, and maintainable systems. By following best practices and selecting suitable architectural patterns, developers can ensure long-term success and adaptability of their software solutions.

---

**Reference:** Ian Sommerville - Software Engineering (Chapter 6)  
**Date:** 25/02/2025
