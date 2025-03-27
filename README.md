# D2F
Welcome to Domain Features Framework (D2F), a conceptual framework that identifies and categorises the aspects of real-world planning domains in varying levels of granularity. D2F is developed with the ambition to provide guidance to knowledge engineers and software engineers in the process of designing, identifying, and categorising realistic and relevant aspects that characterise real-world application domains and are crucial to the development of AI planning systems in all phases. The conceptual framework organises the realistic aspects into seven main categories and seven levels of granularity across these levels with the relations between them.

D2F conceptualises planning domains' realism, provides a common and inclusive notion of AI domain model realism, drives the development of AI planning techniques, can improve the applicability of AI planning, and offers means for comparing different AI planning systems.


## The Seven Categories and their Subcategories

<p align="center">
  <img width="650" height="400" src="https://github.com/user-attachments/assets/d08bf607-72cc-4328-82f0-0a7ac7038208")
>
</p>



**Objectives**

The planning goals that the AI planning system is tasked to achieve. They are categorised by _Types_ (_Soft Goals_, i.e., _Preferences_ or _Hard Goals_, i.e., _Requests_) and _Granularity_ (_Subgoals_ or broader _Goals_). Goals can be _Qualitative_ (e.g., improving comfort) or _Quantitative_ (e.g., minimising costs) and may focus on _Optimisation_ (finding the best solution) or _Satisfaction_ (meeting thresholds).

**Tasks**

The activities performed in the application domain. They are divided into _Complexity_ and _Properties of Relations_. _Complexity_ differentiates between _Actions_ (simple, direct tasks) and _Complex Tasks_ (requiring refinement into subtasks). _Properties of Relations_ include _Abstraction Levels_ (different refinement levels), _Structured Causality_ (causal links between tasks), _Recursion_ (iterative task refinement), _Alternatives_ (multiple ways to achieve a task), and _Conditions_ (requirements for specific refinements). These properties define how tasks interact and evolve to achieve domain-specific goals.

**Quantities**

Measurable values that represent various attributes of resources, actions, and environmental factors relevant to the domain. They are classified by _Type_ and _Computation_. _Types_ include _Resources_ (limits on consumption like money or energy), _Action Costs_ (resources consumed by actions), and _Environmental Inputs_ (measurable characteristics of the domain, like temperature or energy demand). _Computation_ involves determining quantities using either _Linear_ or _Non-linear_ functions, depending on the real-world concepts they represent.

**Determinism**

The extent to which conditions and action outcomes are predictable in the planning domain. Planning domains are categorised into _Deterministic_ or _Non-deterministic_. In _Deterministic_ domains, conditions are fully observable, actions have predefined consequences and costs, and outcomes are predictable. _Non-deterministic_ domains vary based on their _Source_, _Randomness_, and _Consequences_. _Sources_ can be _Internal_ (e.g., agent malfunctions) or _External_ (e.g., environmental variability). _Randomness_ can be _Regular_ (predictable patterns) or _Totally Random_ (unpredictable events). _Consequences_ include _Partial Observability_ (limited knowledge of conditions) and _Action Contingencies_ (uncertain effects or costs). _Non-determinism_ introduces _Risk_ (known probabilities) or _Uncertainty_ (unknown probabilities), influencing decision-making.

**Agents**

The performers of actions in the AI planning system. They are categorised into _Human Agents_ (e.g., building occupants) and _Components_ (e.g., devices, robots, or software). _Components_ vary by _Type_ and _Controllability_, with _Controllable_ ones being directly managed and _Uncontrollable_ ones being influenced by external factors. In uncertain environments, agent _Behaviour_ is shaped by _Risk Tolerance_ (risk-seeking, risk-averse, or risk-neutral) and _Trust_ in the system. _Risk tolerance_ can be _Dynamic_, adjusting based on conditions like resource availability, or _Static_, remaining unchanged.

**Constrains**

The limitations or restrictions that govern the behaviour of actions, resources, or conditions in the application domain. They are classified into _Physical_, defining _Spatial_ and _Temporal_ interactions based on geometric laws; _Ordering_, regulating the sequence and concurrency of _Objectives_, _Tasks_, or _Durative Actions_; _Well-being_, ensuring compliance with _Regulations_, _Standards_, and _Policies_ that enhance _Comfort_, _Privacy_, _Health_, and _Safety_; and _Economic_, managing financial limitations like energy consumption. These constraints may overlap, such as _Well-being_ constraints imposing restrictions on space or resource usage.

**Qualities**

Essential characteristics that the planning domain and the overall planning system, including all its elements, should exhibit. They include aspects like _Robustness_, ensuring adaptability to changes through efficiency, scalability, and resilience; _Compliance with Requirements_, guaranteeing coverage, completeness, accuracy, and adequacy; and _Specificities_, reflecting domain uniqueness and generalisability. _Maintainability_ focuses on modularity, well-defined boundaries, and minimal dependencies for easy modifications. _Explainability_ enhances the system’s interpretability for non-experts, while the _Physical_ aspect ensures accessibility for validation. _Pragmatic_ analysis identifies missing requirements post-design, and _Operationality_ optimises plan generation efficiency, balancing quality and computational constraints.


## Innovative Aspects

D2F highlights some aspects that are simplified and/or neglected in the literature of AI planning:

- **Uncertainty and Risk:** Key aspects that characterise the inherently non-deterministic real-world planning domains.
- **Trust:** A fundamental consideration in all phases of AI planning system development, representing the confidence agents place in the system's ability to make reliable and right decisions.
- **Engineering Guidance:** Support for knowledge engineers and software engineers in the process of designing, identifying, and categorising realistic aspects required for the development process.
- **Categorisation:** Organisation of a broad range of realistic aspects in several abstraction levels.


## Core Features

- **Real-World Impact:** Impact the design, development, and applicability of AI planning systems in real-world settings by supporting software engineers and knowledge engineers in identifying key aspects of real-world planning problems.
- **Comprehensiveness:** Provide a broad range of planning features suitable for real-world planning domains.
- **Customisability:** Enable the selection of realistic aspects based on the specific needs of planning domains and AI planning systems.
- **Transparency:** Support transparency by providing common and inclusive terminology and a notion of domain realism for developing AI planning systems and AI planning domains.
- **Abstraction:** Enable adjusting the level of realistic aspects granularity to align with the domain's specific requirements.


## Engagement and Contribution

Your expertise and insights are essential to the ongoing development of D2F. Whether employed in industrial applications or academic research, sharing your experiences will contribute to the enhancement of D2F for the broader community.

- **For industrial applications:** We invite you to share how D2F has been integrated and adapted within your projects.
- **For academic research:** If you have utilised D2F in your research, kindly reference the following papers:

  [1] Alnazer, E., Georgievski, I. (2023). Understanding Real-World AI Planning Domains: A Conceptual Framework. In: Aiello, M., Barzen, J., Dustdar, S., Leymann, F. (eds) Service-Oriented Computing. SummerSOC 2023. Communications in Computer and Information Science, vol 1847. Springer, Cham.

  [2] Georgievski, I. (2023). Software Development Life Cycle for Engineering AI Planning Systems. In ICSOFT (pp. 751-760).

  [3] Georgievski, I. (2023). Conceptualising software development lifecycle for engineering AI planning systems. In 2023 IEEE/ACM 2nd International Conference on AI Engineering–Software Engineering for AI (CAIN) (pp. 88-89). IEEE.
