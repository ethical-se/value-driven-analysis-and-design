# VDAD Step 3: Identify Values per Stakeholder

_TL;DR:_ Elicit the individual values of the identified stakeholders. Consolidate this information to create and populate a value register progressively.

## Goal and Approach
After having identified the stakeholders in [Step 2](./step-2-identify-stakeholders.md), the goal of this step is to identify the values that are important to the stakeholders and stakeholder groups.

This should ideally be done in direct communication with the affected people. In case this is not possible, it requires an empathic "putting yourself in the perspective of the people affected" approach. 

Apply the [Value Impact Mapping](./../practices/value-impact-mapping.md) practice suggested in this repository to identify all stakeholder's values that might be affected by the system or feature. The impact on such values might be positive, neutral, or negative.

You might wan to create *value models*, for instance with a tool such as [Context Mapper](https://contextmapper.org). Context Mapper supports the [modelling of stakeholders and their values](https://contextmapper.org/docs/vdad-support). Value models express important values are to stakeholders and what the impact of a system or feature to those stakeholders and their values is.

As an alternative to value models and/or [Value Impact Maps](./../practices/value-impact-mapping.md), create a full-fledged value register[^2] as specified in IEEE 7000 standard[^1]. Such a value register contains all important values of the stakeholders and how the system or feature positively or negatively impacts these values as well. ESE practices[^3] such as Story Valuation and the value notations suggested in ESE can further support the creation of the value register; [Context Mapper](https://contextmapper.org) supports the modelling of value registers and the terminology of the IEEE 7000 standard[^1] as well.

### Inputs
The identified stakeholders of [Step 2](./step-2-identify-stakeholders.md), especially the outcome of applying the [Stakeholder Mapping](./../practices/stakeholder-mapping.md) practice, are the input to this step.

### Outputs
This step of the VDAD process shall produce the necessary knowledge about the stakeholders values. This knowledge can be documented in various forms:

 * [Value Impact Maps](./../practices/value-impact-mapping.md)
 * Value models created with [Context Mapper](https://contextmapper.org)
 * Value Registers[^2][^1], for example using ESE notations[^3]
 * Optionally: Already think about mitigation actions that could be taken into account to reduce negative impact (harm) on values.
   * [Context Mapper](https://contextmapper.org) also allows you to model such mitigation actions and adds it to the generated [Value Impact Map](./../practices/value-impact-mapping.md).
   * These considerations will help in [Step 6](step-6-derive-new-and-adjust-existing-requirements.md) as they might lead to adjusted or new requirements towards your system or feature.

Besides the gained knowledge about the values of the stakeholders, this VDAD step should reveal potential conflicts.

## Supporting Tools

The [Context Mapper](https://contextmapper.org) tool supports the [modelling of stakeholders and values](https://contextmapper.org/docs/vdad-support) with its CML language. You can then automatically generate a [Value Impact Map (VIM)](./../practices/value-impact-mapping.md) (more details on the [Value Impact Mapping](./../practices/value-impact-mapping.md) practice page). 

Alternatively, you can use other textual or visual tools. ESE provides alternative notations for maintaining value registers.[^3]

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Previous step: Identify Values per Stakeholder](./step-3-identify-values-per-stakeholder.md)
 * [Next step: Prioritize Values](./step-4-prioritize-values.md)


[^1]: IEEE Standard Model Process for Addressing Ethical Concerns during System Design, 2021, <https://ieeexplore.ieee.org/document/9536679>
[^2]: "An information store created for transparency and traceability reasons, which contains data and decisions gained in ethical values elicitation and prioritization and traceability into ethical value requirements."
[^3]: <https://github.com/ethical-se/ese-practices>
