---
title: "Model-Driven Parallel and Distributed Stochastic Simulation of Chemical Reaction Networks"
collection: publications
category: conferences
award: "Best Paper Award"
permalink: /publication/model-driven-parallel-and-distributed-stochastic-simulation-of-chemical-reaction-networks
date: 2025-09-17
venue: '2025 29th International Symposium on Distributed Simulation and Real Time Applications (DS-RT)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11186008'
citation: 'Bauco, S., Montesano, F., Pimpini, A., Marotta, R., & Pellegrini, A. (2025, September). Model-Driven Parallel and Distributed Stochastic Simulation of Chemical Reaction Networks. In 2025 29th International Symposium on Distributed Simulation and Real Time Applications (DS-RT) (pp. 1-10). IEEE.'
---

Biochemical systems are characterized by rich stochastic behaviors and complex interaction patterns, often modeled through rule-based frameworks such as BioNetGen. Despite the expressiveness of such high-level specifications, simulating large-scale models remains computationally prohibitive. In this paper, we present a model-driven framework for the parallel and distributed execution of stochastic chemical reaction networks, enabled by a model-to-model transformation of BioNetGen descriptions. The transformation produces an intermediate representation based on the Actor Model, in which actors encapsulate local state and asynchronous communication, aligning with the concurrency of biochemical processes. From this representation, we generate executable code targeting ROOT-Sim, a speculative parallel discrete-event simulation (PDES) environment based on Time Warp. We propose an exact parallel implementation of the Stochastic Simulation Algorithm (SSA), employing reaction partitioning to minimize inter-process dependencies and leveraging an event-exchange protocol to ensure consistency and atomicity of reactant consumption across logical processes. We introduce refined rollback and reaction rescheduling mechanisms to address potential correctness issues such as reactant overconsumption. Extensive experiments on well-established models, such as FcεRI, demonstrate substantial speedups over sequential methods.
