---
layout: page
title: Publications
permalink: /Publications/
---

# Journal Articles:

#### Dissipative Imitation Learning for Discrete Dynamic Output Feedback Control with Sparse Data Sets
[Link](https://onlinelibrary.wiley.com/doi/abs/10.1002/rnc.7398)

Amy K. Strong, Ethan J. LoCicero, Leila J. Bridgeman

*International Journal of Robust and Nonlinear Control*, 2024

Abstract:
Imitation learning enables synthesis of controllers for systems with complex objectives and uncertain plant models. However, ensuring an imitation learned controller is stable requires copious amounts of data and/or a known plant model. In this paper, we explore an input–output (IO) stability approach to imitation learning, which achieves stability with sparse data sets while only requiring coarse knowledge of the energy characteristics of the plant. A constrained optimization problem is developed, in which the controller learns to mimic expert data while maintaining stabilizing energy characteristics induced by the plant. While the learning objective is nonconvex, iterative convex overbounding (ICO) and projected gradient descent (PGD) are explored as methods to learn the controller. In numerical examples, it is shown that with little knowledge of the plant model and a small data set, the dissipativity constrained learned controller achieves closed loop stability and successfully mimics the behavior of the expert controller, while other methods often fail to maintain stability and achieve good performance.

#### Stochastic Dissipativity for Systems with Probabilistic Input Delays
[Link](https://arxiv.org/pdf/2401.02569)
 
Ethan J. LoCicero, Amy K. Strong, Leila J. Bridgeman

*Automatica*, 2023 (Submitted)

Abstract: 
This work considers stochastic operators in general inner-product spaces, and in particular, systems with stochastically timevarying input delays of a known probability distribution. Stochastic dissipativity and stability are defined from an operatortheoretic perspective, and the well-known open-loop dissipativity conditions for closed-loop/network stability are extended to the stochastic case. Criteria are derived to identify dissipative nonlinear systems with stochastic input delays, and this result is used to find delay-distribution-dependent linear matrix inequality conditions for stochastic dissipativity of a linear system with input delays of a known probability distribution. A numerical experiment demonstrates the utility of the resulting criteria for robust plant analysis and controller design, highlighting significantly reduced conservatism compared to deterministic methods.

#### Development and Testing of a Durable and Novel Breast Phantom for Robotic Autonomous Ultrasound Systems
[Link](https://www.worldscientific.com/doi/abs/10.1142/S2424905X22410100)

Siobhan R. Oca, Amy K. Strong, Jiselle Havas, Daniel M. Buckland, and Leila J. Bridgeman

*Journal of Medical Robotics Reseach*, 2022

Abstract:
For the safe and effective development of evolving autonomous medical robotic systems that traverse the surface of the body, like in breast ultrasound scans, developing phantoms that are durable and mechanically mimic human tissue is critical. In this work a long lasting, inexpensive, and geometrically customizable phantom is described with mechanical and ultrasound acoustic properties that simulate human breast tissue. In comparison to prior work, a priority was designing a highly elastic phantom outer layer modulus ~20 kPa and inner semi liquid layer to mimic the difficulties of traversing human breast tissue with autonomous medical robotic systems. In addition, ultrasound images of the novel phantom with enclosed tumor are similar to in-vivo image of human breast tissue with invasive ductal carcinoma, representing 80\% of breast cancer cases. The performance of a force feedback controller on an autonomous ultrasound scanning system was compared for the novel phantom and a commercial phantom. Overall, the controller performed worse on the novel phantom -- highlighting the importance of testing autonomous systems on realistic phantoms.

# Peer Reviwed Conference Papers:

#### Improved Small Signal L2 Gain Analysis for Nonlinear Systems
 [Link](https://arxiv.org/abs/2309.08034)
 
Amy K. Strong, Reza Lavaei, Leila J. Bridgeman

*American Control Conference*, 2024

Abstract: 
The L2-gain characterizes a dynamical system’s input-output properties, but can be difficult to determine for nonlinear systems. Previous work designed a nonconvex optimization problem to simultaneously search for a continuous piecewise affine (CPA) storage function and an upper bound on the small-signal L2-gain of a dynamical system over a triangulated region about the origin. This work improves upon those results by establishing a tighter upper-bound on a system’s gain using a convex optimization problem. By reformulating the relationship between the Hamilton-Jacobi inequality and L2-gain as a linear matrix inequality (LMI) and then developing novel LMI error bounds for a triangulation, tighter gain bounds are derived and computed more efficiently. Additionally, a combined quadratic and CPA storage function is considered to expand the nonlinear systems this optimization problem is applicable to. Numerical results demonstrate the tighter upper bound on a dynamical system’s gain.

#### Data Driven Verification of Positive Invariant Sets for Discrete, Nonlinear Systems
[Link](https://proceedings.mlr.press/v242/strong24a/strong24a.pdf)

Amy K. Strong, Leila J. Bridgeman

*6th Annual Conference on Learning for Dynamics and Control* (Oral Presentation), 2024

Abstract:
Invariant sets are essential when establishing safety of nonlinear systems. However, certifying the existence of a positive invariant set for a nonlinear model is difficult and often requires knowledge of the system’s dynamic model. This paper presents a data driven method to certify a positive invariant set for an unknown, discrete, nonlinear system. A triangulation of a subset of the state space is used to query data points. Then, a convex optimization problem is used to create a continuous piecewise affine (CPA) function that fulfills the criteria of the Extended Invariant Set Principle by leveraging an inequality error bound that uses the system’s Lipschitz constant. Numerical results demonstrate the program’s ability to certify positive invariant sets from sampled data.

#### Dissipative Imitation Learning for Robust Dynamic Output Feedback
[Link](https://ieeexplore.ieee.org/abstract/document/9992760)

Amy K. Strong, Ethan J. LoCicero, Leila J. Bridgeman

*IEEE Conference on Decision and Control*, 2022

Abstract: 
Robust imitation learning seeks to mimic expert controller behavior while ensuring stability, but current methods require accurate plant models. Here, robust imitation learning is addressed for stabilizing poorly modeled plants with linear dynamic output feedback. Open-loop input-output properties are used to characterize an uncertain plant, and the feedback matrix of the dynamic controller is learned while enforcing stability through the controller's open-loop QSR-dissipativity properties. The imitation learning method is applied to two systems with parametric uncertainty.

#### Utilizing Hidden Markov Models to Classify Maneuvers and Improve Estimates of an Unmanned Aerial Vehicle
[Link](https://www.sciencedirect.com/science/article/pii/S2405896321022588)

Amy K. Strong, Scott M. Martin, David M. Bevly

*Modelling, Estimation and Controls Conference*, 2021
Abstract:
Estimating the states of a Unmanned Aerial Vehicle (UAV) without the use of onboard sensors can be difficult, particularly if the UAV is performing high dynamic maneuvers. This paper examines if data driven modelling can assist in estimating UAV states, as well as classification of UAV maneuvers. A standard Extended Kalman Filter (EKF) that uses radar measurements and a constant acceleration dynamic model is used as the baseline estimation technique for dynamic UAV maneuvers. The UAV maneuvers are then modelled as Hidden Markov Models (HMM), which classify maneuvers and generate additional state information in the form of acceleration and jerk estimates. These HMM estimates are incorporated into an EKF to create a fusion EKF+HMM. This paper evaluates the robustness of the HMM classification accuracy and compares the EKF+HMM to a standard EKF using both simulated and experimental data.


# Conference Presentations and Posters

#### Development and Testing of a Durable and Novel Breast Phantom for Robotic Autonomous Ultrasound Systems
Amy K. Strong, Siobhan R. Oca, Daniel M. Buckland, Leila J. Bridgeman

*Military Health System Research Sympoium*, 2022 

Poster Presentation

#### Development of an Upperlimb Musculoskeletal Wheelchair Propulsion Model to Analyze the Influence of Axle Position on Shoulder Moments
Amy K. Strong, Nathan Hogaboom, Alicia Koontz, Michael Boninger

*American Society of Biomechanics Conference*, 2018

Poster Presentation
