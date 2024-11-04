<p align="center">
    <img src="https://www.mdanalysis.org/public/mdanalysis-logo_square.png" width="300" height="200">
</p>

# MDAnalysis Tutorial: A Guide to Molecular Dynamics Data Analysis

This repository provides an in-depth tutorial on using **MDAnalysis**, a Python library for analyzing molecular dynamics (MD) simulations. It covers the fundamental components and operations in MDAnalysis, making it ideal for beginners and intermediates looking to understand the library's capabilities and practical applications in MD data analysis.

## Contents

### Getting Started
- Installation steps and basic setup.

### 1. What is MDAnalysis?
   - Overview of MDAnalysis and its use in handling MD data.

### 2. Universe
   - Introduction to the `Universe` object, the central data structure for MD simulations.

### 3. AtomGroup
   - Basics of `AtomGroup`, used to work with specific atom selections.

#### Selecting AtomGroups
   - **Keyword Selection**: Select atoms by keywords like "protein" or "backbone."
   - **Index Selection**: Select atoms by index numbers.

#### Key AtomGroup Methods
   - Get atom positions (x, y, z).
   - Access atom names and types.
   - Calculate center of mass and center of geometry.

### 4. Group Operators and Set Methods
   - Combine and refine AtomGroups.

### 5. Trajectory
   - Work with time-dependent data and simulation trajectories.

### 6. Alignment
   - Align structures.

### 7. RMSD and RMSF
   - **RMSD**: Calculate structural similarity over time.
   - **RMSF**: Identify flexible regions by atomic fluctuations.

### 8. Radius of Gyration
   - Measure structure compactness.

### 9. Visualization
   - Visualize structures and flexible regions.

This guide includes code examples to demonstrate each topic, making it easy to apply MDAnalysis to your own data.
