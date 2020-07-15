## Technical impact heat-map

The Technical Impact Heat Map allows a Technical Lead, for any idea, to provide a high-level estimate of:

- **Size, Complexity and Confidence**

In order to do this, the Technical Lead will discuss the idea and candidate concept with a number of people to determine the high level technical impact. This should include:

- A Product Owner to discuss initial solutions to their requirements, with the aim of balancing their needs versus time-to-market and the ongoing cost of operation, which may necessitate technical enablers, decommissioning activities etc.
- A Service Manager / Owner to ensure that the proposed changes take into account the current technical stack (Technology City Plan) to understand current levels of technical debt, components marked for deprecation and ongoing monitoring and support needs.
- A Business Analyst to understand the proposed value of the deliverable and how the KPIs will be measured. This ensures that the technical solution is pragmatic, i.e. free from "gold-plating".

These discussions would ideally take the form of a workshop to focus effort an reduce timescales as the estimate at this stage is high-level, so work should take no more than 1 day to provide an output.

![Technical Heat-Map](https://github.com/bad-tools/3d.tools/raw/master/RRPD/images/figures/thm.png)
 
The output should be two-fold:

1. A technical impact heat map - This is a high-level view of the technical scope of the change, which should clearly label the initial high-level architectural view in terms of change, i.e.
  - new functionality - shown in GREEN
  - changes to existing functionality - shown in AMBER
  - eprecation/decommissioning of current functionality - shown in RED
2. A high-level estimate - This gives a ballpark figure for:
  - T-shirt size (in terms of XS, S, M, L, XL, XXL), which can be used be approximate duration, e.g.:

  | T-Shirt Size | Candidate Duration |
  |--------------|--------------------|
  | XS           | < 1 Month          |
  | S            | 1 - 3 Months       |
  | M            | 3 - 6 Months       |
  | L            | 6 - 12 Months      |
  | XL           | 12 - 18 Months     |
  | XXL          | 18 - 24 Months     |

- Risk / Complexity (in terms of low, medium or high), which should be written ↓, →, ↑ respectively to avoid confusion with M and L t-shirt sizes. This gives an indication of the level of risk or complexity associated with the proposed changes. Usually the higher the risk, the higher the likelihood of unknowns/issues causing increased cost or delay.

- Confidence (in terms of low, medium or high), which should be written (sad), (tongue), (smile), respectively to avoid confusion with t-shirt sizes. This gives an indication of the confidence in the estimate. Obviously if the proposed solution is large and complex, the estimate is likely to have a certain amount of inaccuracy, especially as risks haven't been elaborated at this stage. Essentially, this measure acts as a validation check for the t-shirt size and risk/complexity estimates and feeds into subsequent steps for Inception and Elaboration & Construction.
