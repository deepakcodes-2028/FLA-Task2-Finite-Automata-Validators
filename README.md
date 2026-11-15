# Automata Casebook

### Course: 21CSC301T – Formal Language and Automata
**Assessment:** CLA-2 – Tasks 2 & 3

| Student Details | Information |
|---|---|
| **Student Name** | B. Deepak |
| **Roll ID** | RA2411026050174 |
| **Programme** | B.Tech. Artificial Intelligence and Machine Learning |
| **Institution** | SRM Institute of Science and Technology |
| **Campus** | Tiruchirappalli |

---

## Project Overview

**Automata Casebook** is a Python-based educational workbench demonstrating concepts from Formal Languages and Automata Theory.

The project includes implementations of:

- Deterministic Finite Automata (DFA)
- Nondeterministic Finite Automata (NFA)
- Context-Free Grammars (CFG)
- Pushdown Automata (PDA)
- Subset construction and DFA minimisation
- Input validation using finite automata
- Grammar-based parsing and recognition

The implementation follows an independent project structure with its own validation examples, test cases, and visual representations.

## Tasks Implemented

### Task 2 – Finite Automata for Input Validation

This task demonstrates how finite automata can validate different types of application inputs.

**1. Student Roll ID Validation**

- Format: `RA` followed by exactly 13 ASCII digits.
- Example: `RA2411026050020`
- Accepts only uppercase `RA` followed by 13 digits.

**2. Username Validation**

- Length: 5–15 characters.
- First character must be an alphabetic letter.
- Remaining characters may contain letters, digits, or underscores.
- Example: `Jagan_24`

**3. Course Code Validation**

- Allowed prefixes: `AIM`, `CSE`, and `ECE`.
- Followed by exactly three digits.
- Examples: `AIM305`, `CSE201`, `ECE110`.

**Automata Implementation**

The validation models are developed
