# D2F
Welcome to D2F, a conceptual framework that identifies and categorises the aspects of real-world planning domains in varying levels of granularity. D2F is developed with the ambition to provide guidance to knowledge engineers and software engineers in the process of designing, identifying, and categorising realistic and relevant aspects that characterise real-world application domains and are crucial to the development of AI planning systems. The conceptual framework consists of seven main categories of realistic aspects and seven levels of granularity across these levels.


## The Seven Categories and their Subcategories

<p align="center">
  <img width="600" height="350" src="https://github.com/user-attachments/assets/7ba8de5a-fa27-4fb0-bdd0-be4190490847")
>
</p>


**Objectives**

Categorised by Types (Soft Goals, i.e., Preferences or Hard Goals, i.e., Requests) and Granularity (Subgoals or broader goals). Goals can be Qualitative (e.g., improving comfort) or Quantitative (e.g., minimising costs) and may focus on Optimisation (finding the best solution) or Satisfaction (meeting thresholds).

**Tasks**

 Divided into Complexity and Properties of Relations. Complexity distinguishes between Actions (simple, direct tasks) and Complex Tasks (requiring refinement into subtasks). Properties of Relations include Abstraction Levels (tasks at different refinement levels), Structured Causality (causal links between tasks), Recursion (tasks refined iteratively), Alternatives (multiple ways to achieve a task), and Conditions (requirements for specific task refinements). These properties define how tasks interact and are refined to achieve domain-specific goals.

**Quantities**

Classified by Type and Computation. Types include Resources (limits on consumption like money or energy), Action Costs (resources consumed by actions), and Environmental Inputs (measurable characteristics of the domain, like temperature or energy demand). Computation involves determining quantities using either Linear or Non-linear functions, depending on the real-world concepts they represent.

**Determinism**

The fourth high-level category addresses whether a planning domain is Deterministic or Non-deterministic. In Deterministic domains, conditions are Totally Observable, actions have Predefined Consequences and Costs, and outcomes are predictable. In contrast, Non-deterministic domains are classified by the Source, Randomness, and Consequences of non-determinism. Sources can be Internal (e.g., agent malfunctions) or External (e.g., environmental variability). Randomness can be Regular (frequent, predictable variations) or Totally Random (unpredictable events). Consequences include Partial Observability (limited knowledge of conditions) and Action Contingencies, such as unpredictable Effects or Costs of actions. Non-determinism introduces Risk (known probabilities) or Uncertainty (unknown probabilities), impacting decision-making.

**Agents**

classified into Human Agents (e.g., building occupants) and Components. Components are further categorized by their Type (e.g., devices, robots, or software components) and Controllability (controllable or uncontrollable). Controllable components can be directly managed, while uncontrollable components depend on external factors. In domains with risk and uncertainty, agents' Behaviour is influenced by their Risk Tolerance and Degree of Trust in the system. Risk tolerance is classified into Risk-seeking, Risk-averse, and Risk-neutral agents. Dynamic risk tolerance means it can change based on factors like resource availability, while Static tolerance remains constant.

**Constrains**

classified into four types: Physical, Ordering, Well-being, and Economic. Physical Constraints relate to space and time, defining how agents and actions interact spatially and temporally. These can be represented abstractly or purely, considering geometric laws and physical properties. Ordering Constraints govern the sequence and concurrency of objectives, tasks, or actions, such as the prioritization or required timing between actions. Well-being Constraints focus on regulations and policies aimed at enhancing user comfort, privacy, health, and safety. Finally, Economic Constraints are concerned with the financial costs of actions, such as limits on energy consumption. These constraints may overlap, with well-being constraints, for instance, restricting the number of people or components in a given space or time.

**Qualities**

Includes aspects like Robustness, which measures how adaptable the system is to changes, covering efficiency, scalability, and resilience. Compliance with Requirements ensures the system meets the domain’s needs, including coverage, completeness, accuracy, and adequacy. Specificities reflect how well the system represents the domain’s uniqueness and its ability to generalise to other problems. Maintainability concerns how easily the domain model can be modified, with a focus on modularity, well-defined boundaries, and minimal dependencies. Explainability addresses how understandable the system’s behaviour and knowledge are to non-experts. The Physical aspect ensures accessibility and availability for interpretation and future validation, while Pragmatic focuses on post-design analysis to uncover missing requirements. Finally, Operationality deals with the system's ability to generate efficient plans using limited resources, emphasising the quality and speed of plan generation.


## Innovative Aspects



## Core Features

- **Adaptability:** Select realistic aspects based on the specific needs of planning domains and AI planning systems.
- **Transparency:** Develop AI planning systems and AI planning domains based on a common and inclusive notion of domain realism.
- **Scalability:**


## Engagement and Contribution

Your expertise and insights are essential to the ongoing development of D2F. Whether employed in industrial applications or academic research, sharing your experiences will contribute to the enhancement of D2F for the broader community.

- **For industrial applications:** We invite you to share how D2F has been integrated and adapted within your projects.
- **For academic research:** If you have utilised D2F in your research, kindly reference the following paper:

   [1] Alnazer, E., Georgievski, I. (2023). Understanding Real-World AI Planning Domains: A Conceptual Framework. In: Aiello, M., Barzen, J., Dustdar, S., Leymann, F. (eds) Service-Oriented Computing. SummerSOC 2023. Communications in Computer and Information Science, vol 1847. Springer, Cham.
