FAST University – Discrete Structures Management System
A Computational Framework for Modeling Courses, Prerequisites, Enrollment, Logic Rules, and Academic Operations
Overview

This project implements a comprehensive academic management and verification framework for FAST University using concepts from Discrete Structures. It models courses, prerequisites, student enrollment, faculty assignments, room allocations, and academic rules through mathematical structures such as sets, relations, functions, logic, and induction.
The system validates correctness, detects conflicts, and ensures consistency across all components using formal reasoning techniques.

Project Modules
1. Course and Scheduling Module

Generates valid course-taking sequences based on prerequisite constraints.
Supports recursive algorithms and dynamic programming to handle complex prerequisite graphs efficiently.

2. Student Group Combination Module

Assigns students to project groups, laboratory sections, and electives using combination logic, set operations, and counting principles.
Handles various grouping and allocation scenarios.

3. Induction and Strong Induction Module

Validates multi-term prerequisite chains using mathematical induction and strong induction.
Ensures that all direct and indirect prerequisite conditions are satisfied before a student enrolls in a course.

4. Logic and Inference Engine

Interprets academic rules involving courses, faculty, and rooms using propositional and predicate logic.
Performs inference to detect rule violations, uncover contradictions, and enforce mandatory policies.

5. Set Operations Module

Represents students, courses, faculties, and rooms as mathematical sets.
Implements union, intersection, set difference, subset checks, and power set generation for analysis.

6. Relations Module

Models student-course, faculty-course, and course-room assignments as binary relations.
Checks relational properties such as reflexivity, symmetry, antisymmetry, transitivity, equivalence relations, and partial orders.
Performs relation composition to uncover indirect connections or conflicts.

7. Functions Module

Defines mappings such as Students → Courses, Courses → Faculty, and Faculty → Rooms.
Evaluates injective, surjective, and bijective properties.
Supports function composition and inverse mapping operations.

8. Automated Proof and Verification Module

Produces step-by-step formal proofs for prerequisite chains, logical constraints, and policy validations.
Ensures every academic rule and relation adheres to discrete structure requirements.

9. Consistency Checker Module

Integrates data from all modules to detect conflicts such as:
incomplete prerequisites, course overlaps, faculty overload, room assignment conflicts, and invalid relations.
This module acts as a global validator for the entire system.

10. Algorithmic Efficiency and Benchmarking

Optimizes discrete structure operations using recursion, memoization, dynamic programming techniques, and bit-level optimizations.
Benchmarks performance for large datasets representing real university course loads.

11. Command-Line Interface (CLI)

Provides a text-based interactive menu system for adding students, courses, rules, prerequisites, and running verification or analysis modules.
Designed for ease of use and structured interaction.

12. Unit Testing and Benchmarking

Includes modular test cases to ensure correctness, robustness, and performance.
Tests cover sets, relations, logic inference, scheduling algorithms, and prerequisite validation.

Key Concepts Applied

This system is built upon fundamental discrete mathematics topics, including:
Sets and Subsets,  Relations and Functions, Equivalence Relations and Partial Orders, Propositional and Predicate Logic, Mathematical Induction and Strong Induction, Recursion and Dynamic Programming, Combinatorics and Counting Principles, Graph Theory (Prerequisite Modeling)
