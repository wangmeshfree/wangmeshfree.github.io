---
title: NEW ARTICLE ABOUT TEMPORAL INSTABILITY IN NON-SYMMETRIC NUMERICAL METHODS 
date: 2022-03-16
image:
  focal_point: 'bottom'
---

New article published in CMAME.

​Link: https://authors.elsevier.com/c/1eks2AQEIzVOs

Abstract:
Non-symmetric matrices may arise in the discretization of self-adjoint problems when a Petrov–Galerkin, collocation, or finite-volume method is employed. While these methods have been widely applied, in this paper it is shown that the use of these non-symmetric matrices is incompatable with the conservation of energy in elastodynamics. First, the consistency between the continuous forms of the momentum equation and the energy equation is examined. It is shown that the conservation of linear momentum is equivalent to conservation of energy provided the solution is sufficiently smooth. The semi-discrete counterparts are then analyzed, where it is demonstrated that they are also equivalent, but only conditionally: the mass and stiffness matrices must be symmetric. As a result, employing a non-symmetric method in elastodynamics may artificially generate or dissipate energy. The fully discrete forms with Newmark time integration are then examined where it is shown that unconditionally unstable algorithms may arise. An energy-conserving time integration algorithm is then proposed which provides stability in the solutions of non-symmetric systems. The collocation and finite-volume methods are employed in numerical examples to demonstrate stability issues and the effectiveness of the proposed time integration methodology.