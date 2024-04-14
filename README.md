# Crack Propagation 
This project concentrated on investigating tibial bone fractures, both with and without implants, aiming to furnish objective and quantitative measures for a deeper comprehension of the complete crack trajectory and fracture mechanics. The methodology employed the Extended Finite Element Method (X-FEM) integrated into Code Aster.

X-FEM enables the simulation of crack initiation and propagation along arbitrary paths without necessitating remeshing.
![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/873499de-6885-487f-828f-4d3dbb2f6c96)

Fracture Mechanics Analysis under Monotonic and Cyclic Loading Conditions:
## 1. Under monotonic loading:
   Incorporate the shape of the crack, such as elliptic, demi-planar, or circular, at the location where crack initiation is assumed. Under monotonic loading conditions, it was assumed that a crack would propagate instantaneously once the stress intensity factor (K) or energy release rate (G) reached a critical value denoted as 𝐾I𝑐 or 𝐺𝑐.
![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/ba6c3081-c46b-4dc0-b9e0-2f7fd5d12572)
   **Fig 1. Stress intensity factors K1,2,3 from elliptical crack.**
![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/dcfe48b9-a8ca-45ab-8cdb-d31cc808d624)
   **Fig 2. Crack propagation with demi-plan (a) and elliptical crack (b).**
## 2. Under cyclic loading conditions:
   Crack initiation occurs at a critical point, pinpointed as the location where fatigue damage peaks. At this juncture, damage accrues during cyclic loading, potentially leading to crack formation.

   Furthermore, fatigue damage, represented by D = 1/N, can be inferred from the number of cycles N, determined through interpolation from an endurance diagram, commonly known as the Wöhler curve (or S–N curve).

   Finally, incorporate the shape of the crack at the critical point and conduct comprehensive crack analysis (Ki, G) and crack propagation analysis.

