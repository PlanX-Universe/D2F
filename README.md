# D2F
Welcome to D2F, a conceptual framework that identifies and categorises the aspects of real-world planning domains in varying levels of granularity. D2F is developed with the ambition to provide guidance to knowledge engineers and software engineers in the process of designing, identifying, and categorising realistic and relevant aspects that characterise real-world application domains and are crucial to the development of AI planning systems in all phases [2]. The conceptual framework organises the realistic aspects into seven main categories and seven levels of granularity across these levels with the relations between them.

D2F conceptualises planning domains' realism, provides a common and inclusive notion of AI domain model realism, drives the development of AI planning techniques, can improve the applicability of AI planning, and offers means for comparing different AI planning systems.


## The Seven Categories and their Subcategories

<p align="center">
  <img width="600" height="350" src="https://github.com/user-attachments/assets/7ba8de5a-fa27-4fb0-bdd0-be4190490847")
>
</p>


**Objectives**

Categorised by Types (Soft Goals, i.e., Preferences or Hard Goals, i.e., Requests) and Granularity (Subgoals or broader goals). Goals can be Qualitative (e.g., improving comfort) or Quantitative (e.g., minimising costs) and may focus on Optimisation (finding the best solution) or Satisfaction (meeting thresholds).

**Tasks**

 Divided into Complexity and Properties of Relations. Complexity differentiates between Actions (simple, direct tasks) and Complex Tasks (requiring refinement into subtasks). Properties of Relations include Abstraction Levels (different refinement levels), Structured Causality (causal links between tasks), Recursion (iterative task refinement), Alternatives (multiple ways to achieve a task), and Conditions (requirements for specific refinements). These properties define how tasks interact and evolve to achieve domain-specific goals.

**Quantities**

Classified by Type and Computation. Types include Resources (limits on consumption like money or energy), Action Costs (resources consumed by actions), and Environmental Inputs (measurable characteristics of the domain, like temperature or energy demand). Computation involves determining quantities using either Linear or Non-linear functions, depending on the real-world concepts they represent.

**Determinism**

Planning domains are categorised into Deterministic or Non-deterministic. In deterministic domains, conditions are fully observable, actions have predefined consequences and costs, and outcomes are predictable. Non-deterministic domains vary based on their Source, Randomness, and Consequences. Sources can be Internal (e.g., agent malfunctions) or External (e.g., environmental variability). Randomness can be Regular (predictable patterns) or Totally Random (unpredictable events). Consequences include Partial Observability (limited knowledge of conditions) and Action Contingencies (uncertain effects or costs). Non-determinism introduces Risk (known probabilities) or Uncertainty (unknown probabilities), influencing decision-making.

**Agents**

Categorised into Human Agents (e.g., building occupants) and Components (e.g., devices, robots, or software). Components vary by Type and Controllability, with controllable ones being directly managed and uncontrollable ones being influenced by external factors. In uncertain environments, agent Behaviour is shaped by Risk Tolerance (risk-seeking, risk-averse, or risk-neutral) and Trust in the system. Risk tolerance can be Dynamic, adjusting based on conditions like resource availability, or Static, remaining unchanged.

**Constrains**

Classified into Physical, defining spatial and temporal interactions based on geometric laws; Ordering, regulating the sequence and concurrency of objectives, tasks, or actions; Well-being, ensuring compliance with regulations that enhance comfort, privacy, health, and safety; and Economic, managing financial limitations like energy consumption. These constraints may overlap, such as well-being constraints imposing restrictions on space or resource usage.

**Qualities**

Include aspects like Robustness, ensuring adaptability to changes through efficiency, scalability, and resilience; Compliance with Requirements, guaranteeing coverage, completeness, accuracy, and adequacy; and Specificities, reflecting domain uniqueness and generalisability. Maintainability focuses on modularity, well-defined boundaries, and minimal dependencies for easy modifications. Explainability enhances the system’s interpretability for non-experts, while the Physical aspect ensures accessibility for validation. Pragmatic analysis identifies missing requirements post-design, and Operationality optimises plan generation efficiency, balancing quality and computational constraints.


## Innovative Aspects

D2F highlights some aspects that are simplified and/or neglected in the literature of AI planning:

- **Uncertainty and Risk:** Key aspects that characterise the inherently non-deterministic real-world planning domains.
- **Trust:** A fundamental consideration in all phases of AI planning system development, representing the confidence agents place in the system's ability to make reliable and right decisions.


## Core Features

- **Adaptability:** Select realistic aspects based on the specific needs of planning domains and AI planning systems.
- **Transparency:** Develop AI planning systems and AI planning domains based on a common and inclusive notion of domain realism.
- **Scalability:** Adjust the level of realistic aspects granularity to align with the domain's specific requirements.


## Engagement and Contribution

Your expertise and insights are essential to the ongoing development of D2F. Whether employed in industrial applications or academic research, sharing your experiences will contribute to the enhancement of D2F for the broader community.

- **For industrial applications:** We invite you to share how D2F has been integrated and adapted within your projects.
- **For academic research:** If you have utilised D2F in your research, kindly reference the following papers:

  [1] Alnazer, E., Georgievski, I. (2023). Understanding Real-World AI Planning Domains: A Conceptual Framework. In: Aiello, M., Barzen, J., Dustdar, S., Leymann, F. (eds) Service-Oriented Computing. SummerSOC 2023. Communications in Computer and Information Science, vol 1847. Springer, Cham.

  [2] Georgievski, I. (2023). Software Development Life Cycle for Engineering AI Planning Systems. In ICSOFT (pp. 751-760).

  [3] Georgievski, I. (2023). Conceptualising software development lifecycle for engineering AI planning systems. In 2023 IEEE/ACM 2nd International Conference on AI Engineering–Software Engineering for AI (CAIN) (pp. 88-89). IEEE.
