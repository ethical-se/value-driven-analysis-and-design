# VDAD Step 5: Make Digitalization Decision

_TL;DR:_ If the negative impacts of a part of a system seem to outweigh the positive values, decide within the team (with all stakeholders) whether it should be built or not.

## Goal and Approach
The objective of this crucial step is to make a concious decision regarding the construction of the system or feature that is planned for development.

[Step 4: Prioritize Values](step-4-prioritize-values.md) may have revealed conflicts that cannot be resolved. It may have demonstrated that too many of the values in question are being negatively affected, and that the system in question has a harmful impact on users, other stakeholders, or society at large.

This may seem impractical, as company leaders and business strategies may ultimately overrule such decisions anyway. However, this step allows a team or company to transparently document the pros and cons of a decision and the rationale behind it.

The outcome of [Step 4](step-4-prioritize-values.md) should be analyzed and a decision made as to whether the project should be continued. As previously mentioned, this decision does not have to be made for the entire system. The system can be divided into bounded contexts[^1], with a digitalization decision made for each context separately.

The decision should be documented in writing, such as in the form of an Architectural Decision Record (ADR)[^2]. This is particularly crucial in instances where the project is pursued with the understanding that significant negative consequences will be accepted.

**Note** that we suggest to process the steps of the whole process iteratively. This step can also be postponed for a future iteration in case the team and/or stakeholders want(s) to delay the decision and gather additional insights upfront. The iterative approach also allows revisiting already made decisions later.

### Inputs
The inputs for this step are the outputs created in the previous steps, with particular attention to the priorities and conflicts defined and unveiled in [Step 4](step-4-prioritize-values.md).

### Outputs
The result of this step can be a simple 'Yes' or 'No'; potentially per bounded context. Some parts of the system might be build while others are not.
However, preferably one creates an ADR[^2] including the decision rationale.

## Supporting Tools

The [homepage of the ADR GitHub organization](https://adr.github.io/) lists several templates and tools that can be used to write ADRs, including MADR and Y-Statements, a light template for architectural decision capturing.[^3]

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Previous step: Prioritize Values](step-4-prioritize-values.md)
 * [Next step: Derive New and Adjust Existing Requirements](step-6-derive-new-and-adjust-existing-requirements.md)

[^1]: _Domain-Driven Design Reference_, Eric Evans, <https://www.domainlanguage.com/ddd/reference/>
[^2]: <https://adr.github.io/>
[^3]: _Y-Statements: A light template for architectural decision capturing_, Doc SoC (aka ZIO), 2020, <https://medium.com/olzzio/y-statements-10eb07b5a177>
