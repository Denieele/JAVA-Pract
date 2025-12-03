# Overview

This is a Java-based educational repository containing practical exercises and projects. The repository demonstrates various Java programming concepts including e-commerce order management systems and finite state machine (FSM) implementations. The project appears to be structured as a learning resource with multiple practice modules.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Application Structure
The repository is organized into multiple practice modules (`prac1`, `prac5`, etc.), each focusing on different Java programming concepts and patterns.

### Practice Module 1 (prac1) - E-commerce Order System
- **Domain Model**: Implements a product catalog and order management system using object-oriented principles
- **Data Model**: Includes Product entities with properties (id, name, price, description) and Category entities with hierarchical relationships
- **Persistence**: Uses file-based storage (order_history.txt) to maintain order records in a human-readable text format
- **Business Logic**: Handles order creation, product management, and order history tracking
- **Internationalization**: All text content and data is in Ukrainian language

### Practice Module 5 (prac5) - Finite State Machine
- **Testing Framework**: Uses JUnit with Maven's Surefire plugin for automated testing
- **Test Coverage**: Comprehensive test suite with 48 test cases covering FSM functionality
- **Build System**: Maven-based project structure with proper test reporting

## Design Patterns
- **Entity Pattern**: Product and Category entities represent core domain objects
- **Value Object Pattern**: Order summaries with timestamps and calculated totals
- **State Pattern**: FSM implementation (in prac5) for modeling state transitions

## Data Storage
- **Format**: Plain text files for data persistence
- **Structure**: Formatted records with delimiters for order separation
- **Encoding**: UTF-8 encoding to support Ukrainian characters

## Technology Stack
- **Language**: Java
- **Build Tool**: Maven
- **Testing**: JUnit framework
- **Test Runner**: Maven Surefire Plugin

# External Dependencies

## Build and Testing Tools
- **Maven**: Project build and dependency management
- **Maven Surefire Plugin**: Test execution and reporting framework
- **JUnit**: Unit testing framework for test-driven development

## Language Support
- **Character Encoding**: UTF-8 support for Ukrainian language content
- **Localization**: Application designed with Ukrainian as the primary language

## File System
- **Local Storage**: File-based persistence for order history and application data
- **No Database**: Currently uses text files instead of a traditional database system