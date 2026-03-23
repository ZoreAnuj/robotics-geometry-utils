# robotics-geometry-utils

A Rust library for 2D and 3D geometric transformations, tailored for robotics and computer vision applications. This project provides essential tools for working with rotations, poses, and transformations, serving as a personal exploration and implementation of core concepts in the field.

## Key Features
*   Implementations for SO(2), SE(2), SO(3), and SE(3) Lie groups.
*   Operations for rotation, translation, and pose composition.
*   Utilities for interpolation, perturbation, and conversion between representations.

## Tech Stack
*   **Language:** Rust
*   **Key Dependencies:** `nalgebra` for linear algebra, `num-traits` for numeric abstractions.

## Getting Started
Add the library to your `Cargo.toml`:
```toml
[dependencies]
robotics-geometry-utils = { git = "https://github.com/zoreanuj/robotics-geometry-utils" }
```
Import and use the modules in your code:
```rust
use robotics_geometry_utils::se3;
```