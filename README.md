# Engineering Counseling and Admission System

## Overview

This project aims to develop a robust software system to streamline the engineering counseling and admission process for two sets of prestigious institutes, namely IITs and NITs. The system efficiently allocates seats to candidates based on their preferences and ranks obtained in the JEE-Advanced and JEE-Main qualifying exams.

## Problem Statement

### Objective
The primary objective is to design a comprehensive system that considers multiple sets of institutes, each offering various branches, and allocates seats to candidates based on their preferences and merit.

### Key Features
1. **Multiple Sets of Institutes and Branches:**
   - The system caters to two sets of institutes (e.g., IITs and NITs), each with its own set of branches such as Computer Science, Mechanical Engineering, etc.

2. **Candidate Preferences and Rank Lists:**
   - Candidates provide a ranked list of preferences, indicating their desired institutes and branches.
   - Candidates hold ranks in JEE-Advanced, JEE-Main, or both, influencing their eligibility for specific choices.

3. **Constraints and Policies:**
   - Seat allocation adheres to constraints such as assigning a seat to each candidate from their list of preferences.
   - Candidates can provide a maximum number of preferences determined by the total number of institutes and branches.
   - Each candidate is allocated only one choice from their preferences.
   - All available seats across all branches must be filled to optimize admission opportunities.

4. **Merit-Based Allocation:**
   - The system ensures merit-based allocation, where candidates denied their preferred choice must have lower ranks than those who were allocated that choice.

## Input

- Number of institutes
- Number of branches in each institute
- Number of seats for each branch in each institute
- Rank list of candidates for each qualifying exam

## Output

The output includes the allocation of institutes and branches to individual candidates based on the established policies and constraints.

## Implementation

The system utilizes this input data to efficiently allocate seats, taking into consideration candidate preferences, merit, and adherence to specified constraints. The resulting allocation is presented in a detailed report containing college codes, names, branches, and corresponding student details.

## Conclusion

This software system enhances the engineering counseling and admission process, promoting fairness and transparency. It efficiently manages the complex task of allocating seats, ensuring that candidates receive opportunities based on their preferences and merit.
