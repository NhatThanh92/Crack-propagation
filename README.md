# Crack Propagation 
This project concentrated on investigating tibial bone fractures, both with and without implants, aiming to furnish objective and quantitative measures for a deeper comprehension of the complete crack trajectory and fracture mechanics. The methodology employed the Extended Finite Element Method (X-FEM) integrated into Code Aster.

X-FEM enables the simulation of crack initiation and propagation along arbitrary paths without necessitating remeshing.

## Fracture Mechanics Analysis under Monotonic and Cyclic Loading Conditions:
### 1. Under monotonic loading:
   Incorporate the shape of the crack, such as elliptic, demi-planar, or circular, at the location where crack initiation is assumed. Under monotonic loading conditions, it was assumed that a crack would propagate instantaneously once the stress intensity factor (K) or energy release rate (G) reached a critical value denoted as 𝐾I𝑐 or 𝐺𝑐.
![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/ba6c3081-c46b-4dc0-b9e0-2f7fd5d12572)
   **Fig 1. Stress intensity factors K1,2,3 from elliptical crack.**
   ![image](https://github.com/NhatThanh92/CrackPropagation/assets/51020597/c0427191-0221-4c17-827a-0ced7f808e26)
   **Fig 2. Crack propagation with demi-plan (a) and elliptical crack (b).**
### 2. Under cyclic loading conditions:
   Crack initiation occurs at a critical point, pinpointed as the location where fatigue damage peaks. At this juncture, damage accrues during cyclic loading, potentially leading to crack formation.

   Furthermore, fatigue damage, represented by D = 1/N, can be inferred from the number of cycles N, determined through interpolation from an endurance diagram, commonly known as the Wöhler curve (or S–N curve).
   ![image](https://github.com/user-attachments/assets/b02c1e1e-779b-4e06-9bf3-fae1c1da261f)


   Finally, incorporate the shape of the crack at the critical point and conduct comprehensive crack analysis (Ki, G) and crack propagation analysis.
   
   ![image](https://github.com/user-attachments/assets/c6167b93-b290-4caa-9d8c-03ddb93cb053)
   **Fig 3. Critical Point Identification Process.**

## References
   Nguyen, Ho-Quang, Trieu-Nhat-Thanh Nguyen, Thinh-Quy-Duc Pham, Van-Dung Nguyen, Xuan Van Tran, and Tien-Tuan Dao. "Crack propagation in the tibia bone within total knee replacement using the extended finite element method." Applied Sciences 11, no. 10 (2021): 4435.  https://doi.org/10.3390/app11104435
