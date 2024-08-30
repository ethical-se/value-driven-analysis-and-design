# VDAD Step 2: Identify Stakeholders

_TL;DR:_ Recognize all (visible and invisible) stakeholders. 

## Goal and Approach
The goal of this second step is to identify all stakeholders (visible and invisible) of the system or feature; meaning all human beings that are somehow affected by the system. A challenge in this step is the identification of _invisible stakeholders_ – stakeholders that do not directly interact with the system. Visible stakeholders are usually already identified when conducting functional requirements with User Stories or Use Cases. Identifying invisible stakeholders means anticipating who might be indirectly affected by the system. Consulting existing stakeholder classifications[^1] might help not forgetting important stakeholder groups.

We recommend applying the [Stakeholder Mapping](./../practices/stakeholder-mapping.md) practice.

### Inputs
The outputs of [Step 1](./step-1-aquire-domain-understanding.md) (such as Use Cases, User Stories, Domain Models, etc.) can be used as inputs to this step, as for example actors in Use Cases or in the "As a ..." part of User Stories are visible stakeholders. Domain Storytelling[^2] or Event Storming[^3] can provide hints as well.

### Outputs
The output of this step should be a compilation of all identified stakeholders. This can be:

 * A list of all stakeholders in textual form
 * A stakeholder map, as a result of the [Stakeholder Mapping](./../practices/stakeholder-mapping.md) practice

**Note**: In case a stakeholder group of yours is huge (for example all shoppers that use an online shop; potentially many human beings) and you are not able to directly communicate with a representative of this group, consider creating Personas[^4] for these cases as an additional output of this step.

## Supporting Tools

Stakeholders can be written down textually or documented visually with tools such as [Miro](https://miro.com). The [Context Mapper](https://contextmapper.org) tools allows you to model your stakeholders together with your domain, user stories, etc. You can further generate [Stakeholder Maps](./../practices/stakeholder-mapping.md) automatically with [Context Mapper](https://contextmapper.org) (more details on the [Stakeholder Mapping](./../practices/stakeholder-mapping.md) practice page).

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Previous step: Aquire Domain Understanding](./step-1-aquire-domain-understanding.md)
 * [Next step: Identify Values per Stakeholder](./step-3-identify-values-per-stakeholder.md)


[^1]: _Ethics in Software Engineering: A Systematic Literature Review_, Razieh Alidoosti, Patricia Lago, Maryam Razavian, Antony Tang, <https://hdl.handle.net/1871.1/6babced3-4bd2-443e-8c1b-b0593a4cb6e1>
[^2]: _Domain Storytelling: A Collaborative, Visual, and Agile Way to Build Domain-Driven Software_, Stefan Hofer, Henning Schwentner, 2021, <https://www.informit.com/store/domain-storytelling-a-collaborative-visual-and-agile-9780137458912>
[^3]: <http://ziobrando.blogspot.com/2013/11/introducing-event-storming.html>
[^4]: <https://www.agilealliance.org/glossary/personas/>
