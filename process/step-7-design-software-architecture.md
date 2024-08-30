# VDAD Step 7: Design Software Architecture

_TL;DR:_ Incorporate the values of your stakeholders in all decisions about architecture, coding, and testing. Apply domain-driven practices in order to apply the ubiquitous language about the domain knowledge, stakeholders and values to your software architecture, design and code.

## Goal and Approach
The goal of this last step is business as usual, but still worth mentioning: come up with an adequate software architecture that satisfies the functional requirements as well as ethical, and other non-functional requirements elaborated in [Step 6](step-6-derive-new-and-adjust-existing-requirements.md).

However, in the spirit of Domain-Driven Design (DDD), the domain and value models and their ubiquitous language, context maps, etc. (artifacts produced in earlier steps) are still relevant to the design and the architecture of the software as well.

The following, exemplary activities of the Design Practice Repository (DPR)[^1] are typically performed during this step:

 * Architectural Decision Capturing[^2]
 * Architecture Modeling[^3]
 * Strategic Domain-Driven Design (DDD)[^4]
 * Tactic(al) DDD[^5]

### Inputs
The input to this step are mainly the requirements elicited in [Step 6](step-6-derive-new-and-adjust-existing-requirements.md). However, as mentioned in the approach above, artifacts such as domain and value models of earlier steps can also influence design and architecture.

### Outputs
As the name of this step indicates, this step shall produce artifacts describing the software architecture. This can be Architectural Decision Records (ADRs)[^6], component diagrams, deployment models, etc. arc42[^7] suggests a twelve-part section structure to organize this design output.

## Supporting Tools

It is not feasible to provide an exhaustive list of tools that can be employed to document software architecture, as the number is vast. However, a few suggestions that might be suitable:

 * arc42[^7] is available for many formats, such as docx, latex, asciidoc, markdown, etc., and can therefore be used with many editors and tools.
 * Architectural Decision Records (ADRs)[^6] can be written in many formats as well. Many tools are available as well.
 * [Context Mapper](https://contextmapper.org) supports several other steps of the VDAD process already and might therefore be a nice choice to generate component diagrams, context maps, etc. when applying DDD.
 * [PlantUML](https://plantuml.com/) is another DSL-based tools to write UML diagrams in textual form.

There are many online resources about software architecture topics; checkout the following collection of pointers for software architects, if you are interested: [Architectural Knowledge Hubs - Online Resources for Software Architects (Cloud Application Lab @ OST)](https://www.ost.ch/de/forschung-und-dienstleistungen/informatik/ifs-institut-fuer-software/labs/cloud-application-lab/architectural-knowledge-management-akm/architectural-knowledge-hubs)

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Previous step: Derive New and Adjust Existing Requirements](step-6-derive-new-and-adjust-existing-requirements.md)
 * **Whats next?** Please read the notes on *[Process Continuation](step-infinity-process-continuation.md)*.

[^1]: <https://socadk.github.io/design-practice-repository>
[^2]: <https://socadk.github.io/design-practice-repository/activities/DPR-ArchitecturalDecisionCapturing.html>
[^3]: <https://socadk.github.io/design-practice-repository/activities/DPR-ArchitectureModeling.html>
[^4]: <https://socadk.github.io/design-practice-repository/activities/DPR-StrategicDDD.html>
[^5]: <https://socadk.github.io/design-practice-repository/activities/DPR-TacticDDD.html>
[^6]: <https://adr.github.io/>
[^7]: <https://www.arc42.de/>
