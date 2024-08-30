# VDAD Step 6: Derive New and Adjust Existing Requirements

_TL;DR:_ Treat ethical values as a type or category of Non-Functional Requirements (NFRs) that complement the desired software qualities. Aim at shaping the requirements in such a way that positive values are promoted and negative values contained as much as possible.

## Goal and Approach
Once the positive and negative consequences on the stakeholders' values have been analyzed and a digitalization decision has been made, the objective of this step is to adjust existing requirements and incorporate ethical values into functional and non-functional requirements.

Typically, ethical values can be carved into NFRs; while defined mitigation actions from previous steps can also lead to additional functional requirements.

In accordance with the values identified in [Step 3](step-3-identify-values-per-stakeholder.md) and their priorities defined in [Step 4](step-4-prioritize-values.md), NFRs shall be written to ensure the protection and fostering of these values throughout the system's lifecycle. NFRs should be specified in a [SMART](https://socadk.github.io/design-practice-repository/activities/DPR-SMART-NFR-Elicitation.html) way: for instance, the 'M' property makes them measurable. It must be possible to check whether the NFR is satisfied or not. 

Existing approaches towards NFRs such as the arc42 Quality Model[^2], Attribute-Driven Design (ADD)[^3] or ATAM (Method for Architecture Evaluation)[^4] could be applied.

Furthermore, any necessary adjustments to existing requirements must be made to avoid any adverse impact on the values in question. The mitigation actions identified in previous steps must be respected in this step.

### Inputs
All outputs of the previous steps have to be respected as input in this step.

### Outputs
All kinds of requirements can be output to this step. 

## Supporting Tools

The requirements can be documented in textual form with word processors, requirements management tools, and/or with special-purpose notations as the ones suggested in ESE[^1].

The arc42 Quality Model [^2] contains many examples as well as definitions and classifications of NFRs of all kinds. Attribute-Driven Design (ADD)[^3] or ATAM (Method for Architecture Evaluation)[^4] can be helpful approaches in this step as well.

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Previous step: Make Digitalization Decision](step-5-make-digitalization-decision.md)
 * [Next step: Design Software Architecture](step-7-design-software-architecture.md)


[^1]: <https://github.com/ethical-se/ese-practices>
[^2]: <https://quality.arc42.org/>
[^3]: <https://insights.sei.cmu.edu/library/attribute-driven-design-method-collection/>
[^4]: <https://insights.sei.cmu.edu/library/atam-method-for-architecture-evaluation/>
