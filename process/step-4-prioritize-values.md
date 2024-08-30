# VDAD Step 4: Prioritize Values

_TL;DR:_ Prioritize the conflicts and values identified so far. Identify the most important values for the team and where it is possible to compromise. Start and follow a requirements prioritization and tradeoff management process that involves all stakeholders.

## Goal and Approach
This VDAD step is both critical and challenging. Values and consequences might need to be analyzed in more depth. Stakeholders have different values and conflicts cannot be avoided. There are opposing values; for example, _privacy_ might require to hide certain data while _transparency_ calls for making it visible. 

The objective of this phase is to facilitate consensus among the project team regarding the prioritization of values and the resolution of conflicts. This process hinges on effective communication and the willingness to compromise.

Modifications to the features or system requirements may be beneficial in the mitigation of potential harm to values that are of importance to stakeholders. The identification of adjusted solutions with which all stakeholders can live may therefore assist in the resolution of conflicts between people.

Furthermore, decomposing the systems into bounded contexts according to Domain-Driven Design (DDD)[^2] might help, as not all values may be of equal criticality across all system components. The [Context Mapper](https://contextmapper.org/) tool, which combines DDD with value-driven analysis and design, may be useful in this context, as it allows the modeling of values at the level of a bounded context.

### Inputs
The outputs of [Step 3](./step-3-identify-values-per-stakeholder.md), i.e. a [Value Impact Map](./../practices/value-impact-mapping.md), a value register[^1], and/or value models created with [Context Mapper](https://contextmapper.org/docs/vdad-support) constitute the input to this step.

### Outputs
The outputs of this step are mainly adjustments to the artifacts produced in [Step 3](./step-3-identify-values-per-stakeholder.md) or even [Step 1](step-1-aquire-domain-understanding.md) and [Step 2](step-2-identify-stakeholders.md):

 * Adjusted value models with stakeholder priorities, detailed consequences and potential mitigation actions
 * Adjusted [Value Impact Map (VIM)](./../practices/value-impact-mapping.md) according to defined priorities
 * Adjusted value register[^1]
 * Changes to domain models, user stories and/or use cases, etc., if necessary

## Supporting Tools

Utilize the same tools used in previous steps to make any necessary adjustments to the produced artifacts.

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Previous step: Identify Values per Stakeholder](./step-3-identify-values-per-stakeholder.md)
 * [Next step: Make Digitalization Decision](step-5-make-digitalization-decision.md)

[^1]: IEEE Standard Model Process for Addressing Ethical Concerns during System Design, 2021, <https://ieeexplore.ieee.org/document/9536679>
[^2]: _Domain-Driven Design Reference_, Eric Evans, <https://www.domainlanguage.com/ddd/reference/>
