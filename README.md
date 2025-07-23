# AIDrivenDev

## Implementation Process
First, we have to create specifications.md that represents what and how we create.
If we needed, we create ui-mockup as svg file.

-------

## Principles

### 1. Separation of Concerns
**Rationale**: 
The most fundamental principle for managing complexity in large-scale systems. When each component holds only specific responsibilities, understanding, testing, and maintenance become dramatically easier.

**Essential Implications**: 
A design philosophy that accounts for human cognitive limitations. Since there are bounds to the amount of information we can process simultaneously, dividing problems into smaller parts makes the whole system controllable and comprehensible.

### 2. Loose Coupling & High Cohesion
**Rationale**: 
Achieves the dual goals of system changeability and stability. By minimizing dependencies between components while maximizing internal coherence, we suppress the risk of local changes cascading throughout the entire system.

**Essential Implications**: 
Mimics the organizational principles of biological systems. Similar to how cells maintain independence while specializing in specific functions and cooperating through minimal information exchange, software components should operate with bounded autonomy.

### 3. DRY (Don't Repeat Yourself)
**Rationale**: 
Code duplication is the nemesis of maintainability. When identical logic exists in multiple locations, ensuring consistency during changes becomes difficult and creates breeding grounds for bugs.

**Essential Implications**: 
Embodies the concept of "single source of truth." From an information theory perspective, eliminating redundancy increases information density and directly contributes to improved system reliability.

### 4. Observability
**Rationale**: 
Understanding internal state becomes challenging in large-scale systems. Without visibility through logs, metrics, and tracing, detecting, diagnosing, and resolving issues becomes impossible.

**Essential Implications**: 
Reflects control theory's principle that "observation is necessary for control." As system complexity increases, measurement capabilities become the lifeline for understanding system behavior.

### 5. Dependency Inversion Principle (DIP)
**Rationale**: 
Design that depends on abstractions rather than concrete implementations. This ensures that implementation changes don't affect other parts and improves testability—particularly crucial in large-scale systems.

**Essential Implications**: Embodies the principle of hierarchical stability. By creating structures where upper layers remain unaffected by changes in lower layers, we ensure overall system stability and establish the foundation for pluggable architectures.

----

## Test Strategy
Test ensures that an implementation meets requirements and preserve existing other logic.
Use testing framework.
Always consider edge cases.
Create tests folder first.

----

## Modification Process
Track down the part where we need to modify considering "Issue Description", "Root Cause Analysis" and "Proposed Solustion" before implementing any edits.

----

## Logging Strategy
We need a general-purpose, highly extensible logger that can perform detailed log investigation.
