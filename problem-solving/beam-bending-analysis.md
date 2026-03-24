# Beam Bending Analysis (AI Evaluation Style)

## Problem
A simply supported beam of length 2 m is subjected to a central point load of 1000 N. Determine the maximum bending stress.
Assume linear elastic behavior and small deformations.

## Solution

1. Maximum bending moment for a simply supported beam with central load:
   M = (F * L) / 4

   M = (1000 N * 2 m) / 4 = 500 Nm

2. Assume rectangular cross-section:
   Width (b) = 0.05 m  
   Height (h) = 0.1 m  

3. Moment of inertia:
   I = (b * h^3) / 12  
   I = (0.05 * 0.1^3) / 12 = 4.17e-6 m^4

4. Maximum stress:
   sigma = (M * c) / I  
   c = h/2 = 0.05 m  

   sigma = (500 * 0.05) / (4.17 × 10⁻⁶) = 6.0 × 10⁶ Pa = 6 MPa

## Common Mistakes

- Using incorrect bending moment formula
- Forgetting unit consistency (Nm vs Nmm)
- Miscalculating moment of inertia
- Not identifying correct location of maximum stress

## Final Answer

Maximum bending stress ≈ **6 MPa**

## Engineering Insight

The maximum bending stress occurs at the outer fibers of the beam (top and bottom surfaces). The relatively low stress value suggests that the selected cross-section is adequate for the applied load, assuming typical structural materials.
