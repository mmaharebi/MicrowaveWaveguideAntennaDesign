# Microwave and Optical Design Lab Project 1

## Introduction
This project aims to provide a hands-on experience with the concepts and methods of matching in waveguide circuits, utilizing various discontinuities such as capacitive and inductive irises and E-plane posts. The designs were simulated and measured using HFSS software and AutoCAD.

## Experiments

### Experiment 1: Two-port iris structures
- **Objective**: Simulate and analyze the frequency response of a waveguide circuit with two assigned irises.
- **Steps**:
  1. Open AutoCAD files (`dwg1._3EXP_StudentID`) for iris designs.
  2. Simulate transmission and reflection coefficients in the 8-12 GHz range.
  3. Extract the circuit model using S-parameters and transmission line model.
  4. Use embedding-deembedding technique to compensate for extra lengths.

### Experiment 2: Open-ended waveguide antenna with an iris
- **Objective**: Measure reflection coefficient, compare results with Experiment 1, and analyze radiation patterns.
- **Steps**:
  1. Open AutoCAD files (`dwg1._3EXP_StudentID`) for iris designs.
  2. Measure reflection coefficient with absorbing boundary condition.
  3. Find the circuit model using measured reflection coefficient and transmission line model.
  4. Compare results with Experiment 1 and explain admittance differences.
  5. Calculate and plot realized gain pattern and beamwidth in E and H planes.

### Experiment 3: Matching the open-ended waveguide antenna with E-plane posts
- **Objective**: Match the waveguide antenna with metallic posts, analyze bandwidth, and radiation parameters.
- **Steps**:
  1. Open AutoCAD files (`dwg2._3EXP_StudentID`, `dwg3._3EXP_StudentID`) for post designs.
  2. Measure reflection coefficient with absorbing boundary condition.
  3. Use single-stub matching on the Smith chart to determine post distance and required admittance.
  4. Implement required admittance by designing post width using HFSS and plot admittance versus width curve.
  5. Plot frequency response, report 15 dB bandwidth, and optionally improve bandwidth with more posts.
  6. Calculate and plot realized gain pattern and beamwidth, comparing with unmatched antenna. Explain the effect of matching on radiation parameters.

## Submission
- Ensure that AutoCAD files for iris and post designs are named according to the provided format.
- Include a detailed report covering simulations, measurements, calculations, and plots for each experiment.
- Explain observations, comparisons, and the impact of matching on radiation parameters.

## How to Reproduce
1. Clone the repository: `git clone https://github.com/your-username/your-project.git`
2. Open AutoCAD files for iris and post designs.
3. Follow instructions in the README to reproduce each experiment.
4. Submit your results and report following the guidelines provided in the Submission section.

Feel free to reach out for any clarifications or assistance!
