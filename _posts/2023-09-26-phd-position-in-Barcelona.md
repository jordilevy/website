---
layout: post
title: "PhD position in proof systems beyond resolution  (deadline October, 2023)"
shorttitle: "PhD in Barcelona"
author: Jordi Levy
link:  https://www.iiia.csic.es/~levy/
deadline: 2023-10-31
tags: PhD Position Deadline
excerpt: The Artificial Research Institute (IIIA, CSIC), Polytechnic University of Catalonia (UPC) and University of Lleida (UdL) invites applications for a PhD position in satisfiability and combinatorial optimisation.
---

Title: Satisfiability and Optimization with Certificate Proofs Beyond Resolution

Project: "PROOFS BEYOND" funded by the Agencia Estatal de Investigación with contract PID2022-138506NB-C21

IPs: Jordi Levy (levy@iiia.csic.es) and Carlos Ansótegui (carlos.ansotegui@udl.cat)

Duration: 4 years to complete a PhD in Computer or Artificial Intelligence

Eligibility: applicants must hold a MSc in computer science, mathematics, or physics (or related areas) at the time of application

Starting Date: approximately in October 2023

Location: Barcelona and Lleida (Spain)

Goal: Develop new techniques for the problem of constraint satisfaction (SAT) and constraint optimization (MaxSAT), exploring new ideas based on the use of new proof systems

SUMMARY OF THE COORDINATED PROJECT

The satisfiability problem (or, more generally, the constraint satisfaction problem) and MaxSAT (or, more generally, the problem of constrained optimization) are two of the most relevant problems for computer science and artificial intelligence. Despite the tremendous advances of the last decades, there is a feeling among experts that radically new ideas may be necessary for further progress beyond the current barriers. In this grant, we propose to surpass the known intrinsic limitations of the Resolution proof system, the still dominant method in the area, by studying and implementing stronger proof systems for propositional logic.
One of the leading motivations for this grant is to contribute to the ongoing building of bridges between the theoretical and practical sides of the area. We plan to continue the theoretical study of algebraic and semi-algebraic proof systems such as Polynomial Calculus, Sherali-Adams, and Sums-of-Squares, as well as their more practical implementation aspects. This study could lead to a new generation of SAT and MaxSAT solvers beyond Resolution, and to new algorithmic methods for constraint satisfaction problems and their variants. While any proof of completeness of the proof systems implicitly carries with it an automating algorithm, further investigation is needed when it comes to bringing these algorithms to practice. For Sherali-Adams and Sums-of-Squares, the theoretical algorithms are based on linear programming and semi-definite programming, respectively. For Polynomial Calculus, the algorithm is based on Groebner bases. Is the full strength of these general methods needed for automation of real instances? What types of constraints can be solved efficiently by these methods? Answering these types of questions is only possible through the collaboration of leading researchers in the theoretical and practical aspects of SAT, CSP, and optimization. We believe that this proposal can contribute to establishing the required synergy of methods.
The research team is composed of professors from four institutions: the University of Lleida (UdL), the Technical University of Catalonia (UPC), the Spanish Research Council (CSIC), and the University Pompeu Fabra (UPF). The project is structured into two subprojects, one focussed on the foundational aspects, and the other one focussed on the applied ones. The team is distributed across the subprojects according to expertise. We have identified six objectives, three of which are more applied, the rest more theoretical, and all of them appear to be interconnected. This is reflected in the composition of the working teams, but also in the past collaborations and joint publications.

SUMMARY OF THE SUBPROJECT

As we mention in the general summary, in the last few years, there is a feeling among experts that to progress in the development of constraint solving, we have to surpass the known limitations of Resolution. This means that we have to face the automatization of more powerful proof systems from a pragmatic view.
Second, when the so-called SAT-based or core-based MaxSAT solvers became state-of-the-art in optimization for real-world combinatorial problems, it got clear the entangled relation between SAT and MaxSAT. More recently, we have seen that MaxSAT techniques may be competitive in the search for SAT proofs.
Finally, we have observed how solvers that weren't competitive in the SAT competition, became leaders just by configuring some parameters. We must not forget that modern solvers are the result of more than 20 years of experimentation and tunning (probably, the benchmarks used in the competitions are also biased in favor of these more classical techniques).
These three observations are on the base of the definition of the three applied goals of the project. In goal A, we plan to annalize gadgets, i.e. translation methods, between SAT and MaxSAT problems. We plan even to explore the relationship with quantum computing. One of the main aspects will be the practical implementation of proof-search algorithms for more powerful proof systems. Clearly, there is close dependence between this goal and goal D where we will study the complexity of the proof-search problem of these systems. In goal B, we include all the tasks related to improving MaxSAT solvers, and in some way, recovering the leadership that our research group had in MaxSAT solving. Obviously, as we said above, this objective is closely related to goal A. Finally, in goal C, we integrate all the tasks related to automatic configuration and combinatorial testing. These techniques serve, not only for fine-tuning solvers but also other algorithms, or even models, as we showed recently in another project for configuring parameters in infection-spread models.

