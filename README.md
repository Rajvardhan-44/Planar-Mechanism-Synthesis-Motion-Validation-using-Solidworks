# Mechanism Synthesis for Prescribed Motion of a Partial Circular Object

## Overview

This project presents a **MATLAB-based mechanism synthesis** solution for generating the prescribed motion of a partial circular object using only **revolute and prismatic joints**.

The mechanism moves the object through three specified orientations:

- **Stage 1:** Orientation **A → B**
- **Stage 2:** Orientation **B → C**
- **Stage 3:** Return **C → A** at **twice the forward speed**

The implementation is fully parameterized so that changes in the problem dimensions (radius, offsets, etc.) require only modification of input parameters rather than rewriting the algorithm.

---

## Problem Statement

A partial circular object of radius **5 cm** must move through three prescribed orientations while satisfying the following conditions:

- Motion sequence:
  - **A → B**
  - **B → C**
  - **C → A** (2× faster)

- The object's **center does not translate horizontally**.
- The center only moves **vertically downward**.
- The mechanism must use **only revolute and/or prismatic joints**.
- The program should remain **generic** for different geometric dimensions.
