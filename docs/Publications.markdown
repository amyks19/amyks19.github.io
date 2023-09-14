---
layout: page
title: Publications
permalink: /Publications/
---

## Journal Articles:

#### [Dissipative Imitation Learning for Discrete Dynamic Output Feedback Control with Sparse Data Sets](https://arxiv.org/abs/2309.06658)
Amy K. Strong, Ethan J. LoCicero, Leila J. Bridgeman

*International Journal of Robust and Nonlinear Control*, 2023 (Submitted)

Abstract:
Imitation learning enables the synthesis of controllers for complex objectives and highly uncertain plant models. However, methods to provide stability guarantees to imitation learned controllers often rely on large amounts of data and/or known plant models. In this paper, we explore an input-output (IO) stability approach to dissipative imitation learning, which achieves stability with sparse data sets and with little known about the plant model. A closed-loop stable dynamic output feedback controller is learned using expert data, a coarse IO plant model, and a new constraint to enforce dissipativity on the learned controller. While the learning objective is nonconvex, iterative convex overbounding (ICO) and projected gradient descent (PGD) are explored as methods to successfully learn the controller. This new imitation learning method is applied to two unknown plants and compared to traditionally learned dynamic output feedback controller and neural network controller. With little knowledge of the plant model and a small data set, the dissipativity constrained learned controller achieves closed loop stability and successfully mimics the behavior of the expert controller, while other methods often fail to maintain stability and achieve good performance.

#### Improved Small Signal L2 Gain Analysis for Nonlinear Systems
Amy K. Strong, Reza Lavaei, Leila J. Bridgeman

*IEEE Control Systems Letters*, 2023 (Submitted)

Abstract: The L2-gain characterizes a dynamical system's input-output properties and is used for important control methods, like H-infinity control. However, gain can be difficult to determine for nonlinear systems. Previous work designed a nonconvex optimization problem to simultaneously search for a continuous piecewise affine (CPA) storage function and an upper bound on the small-signal L2-gain of a dynamical system over a triangulated region about the origin. This work improves upon those results to establish a tighter upper-bound on a system's gain through a convex optimization problem. By reformulating the relationship between the Hamilton-Jacobi equations and gain as a linear matrix inequality (LMI) and then developing novel LMI error bounds for a triangulation, tighter gain bounds are derived and computed more efficiently. Numerical results demonstrate the less conservative upper bound on a dynamical system's gain.

#### [Development and Testing of a Durable and Novel Breast Phantom for Robotic Autonomous Ultrasound Systems](https://www.worldscientific.com/doi/abs/10.1142/S2424905X22410100?cookieSet=1)
Siobhan R. Oca, Amy K. Strong, Jiselle Havas, Daniel M. Buckland, and Leila J. Bridgeman

*Journal of Medical Robotics Reseach*, 2022

Abstract:
For the safe and effective development of evolving autonomous medical robotic systems that traverse the surface of the body, like in breast ultrasound scans, developing phantoms that are durable and mechanically mimic human tissue is critical. In this work a long lasting, inexpensive, and geometrically customizable phantom is described with mechanical and ultrasound acoustic properties that simulate human breast tissue. In comparison to prior work, a priority was designing a highly elastic phantom outer layer modulus ~20 kPa and inner semi liquid layer to mimic the difficulties of traversing human breast tissue with autonomous medical robotic systems. In addition, ultrasound images of the novel phantom with enclosed tumor are similar to in-vivo image of human breast tissue with invasive ductal carcinoma, representing 80\% of breast cancer cases. The performance of a force feedback controller on an autonomous ultrasound scanning system was compared for the novel phantom and a commercial phantom. Overall, the controller performed worse on the novel phantom -- highlighting the importance of testing autonomous systems on realistic phantoms.

## Peer Reviwed Conference Papers:

#### [Dissipative Imitation Learning for Robust Dynamic Output Feedback](https://arxiv.org/abs/2210.00979) 
Amy K. Strong, Ethan J. LoCicero, Leila J. Bridgeman

*IEEE Conference on Decision and Control*, 2022

Abstract: 
Robust imitation learning seeks to mimic expert controller behavior while ensuring stability, but current methods require accurate plant models. Here, robust imitation learning is addressed for stabilizing poorly modeled plants with linear dynamic output feedback. Open-loop input-output properties are used to characterize an uncertain plant, and the feedback matrix of the dynamic controller is learned while enforcing stability through the controller's open-loop QSR-dissipativity properties. The imitation learning method is applied to two systems with parametric uncertainty.

#### [Utilizing Hidden Markov Models to Classify Maneuvers and Improve Estimates of an Unmanned Aerial Vehicle](https://www.sciencedirect.com/science/article/pii/S2405896321022588)
Amy K. Strong, Scott M. Martin, David M. Bevly

*Modelling, Estimation and Controls Conference*, 2021

Abstract:
Estimating the states of a Unmanned Aerial Vehicle (UAV) without the use of onboard sensors can be difficult, particularly if the UAV is performing high dynamic maneuvers. This paper examines if data driven modelling can assist in estimating UAV states, as well as classification of UAV maneuvers. A standard Extended Kalman Filter (EKF) that uses radar measurements and a constant acceleration dynamic model is used as the baseline estimation technique for dynamic UAV maneuvers. The UAV maneuvers are then modelled as Hidden Markov Models (HMM), which classify maneuvers and generate additional state information in the form of acceleration and jerk estimates. These HMM estimates are incorporated into an EKF to create a fusion EKF+HMM. This paper evaluates the robustness of the HMM classification accuracy and compares the EKF+HMM to a standard EKF using both simulated and experimental data.


## Conference Presentations and Posters

#### Development and Testing of a Durable and Novel Breast Phantom for Robotic Autonomous Ultrasound Systems
Amy K. Strong, Siobhan R. Oca, Daniel M. Buckland, Leila J. Bridgeman

*Military Health System Research Sympoium*, 2022 

Poster Presentation

#### Development of an Upperlimb Musculoskeletal Wheelchair Propulsion Model to Analyze the Influence of Axle Position on Shoulder Moments
Amy K. Strong, Nathan Hogaboom, Alicia Koontz, Michael Boninger

*American Society of Biomechanics Conference*, 2018

Poster Presentation
