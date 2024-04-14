# Crack Propagation 
This project concentrated on investigating tibial bone fractures, both with and without implants, aiming to furnish objective and quantitative measures for a deeper comprehension of the complete crack trajectory and fracture mechanics. The methodology employed the Extended Finite Element Method (X-FEM) integrated into Code Aster.

X-FEM enables the simulation of crack initiation and propagation along arbitrary paths without necessitating remeshing.

Fracture Mechanics Analysis under Monotonic and Cyclic Loading Conditions:
1. Under monotonic loading:

   Incorporate the shape of the crack, such as elliptic, demi-planar, or circular, at the location where crack initiation is assumed. Under monotonic loading conditions, it was assumed that a crack would propagate instantaneously once the stress intensity factor (K) or energy release rate (G) reached a critical value denoted as 𝐾I𝑐 or 𝐺𝑐.
   ![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/632f4704-ef04-4687-8026-2e45a421c01e)
               **Fig 1. Stress intensity factors K1,2,3 from elliptical crack**
   ![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/0e7ca93f-06b1-4216-8892-6faceaddab40)
               **Fig 2. Crack propagation with demi-plan.**

