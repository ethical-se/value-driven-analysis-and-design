# VDAD Step 1: Aquire Domain Understanding

_TL;DR:_ Apply domain-driven practices to analyze the domain with its core, generic and  supporting subdomains[^1] and acquire knowledge about them. Establish a common vocabulary, the Ubiquituous Language[^1] of the domain.

## Goal and Approach
This step ideally involves all project stakeholders from customers, business experts, users to developers. The goal of this first step is to aquire a common understanding between business people and developers/engineers. A common language shall be spoken so that misunderstandings and the need for translation are reduced.

This step usually, at least in the first iterations, produces analysis results on a higher level. A Domain Model must, therefore, not already use [tactic DDD](https://socadk.github.io/design-practice-repository/activities/DPR-TacticDDD.html) patterns and is not ready to be implemented. An Event Storming[^2] or Domain Storytelling[^3] can also be considered a viable alternative to a Domain Model at this stage. It is just important that you model the established understanding. In domain-driven terms: you probably model the real world - as it is - in this step; meaning you are modelling Subdomains (object-oriented analysis), but not Bounded Contexts yet (object-oriented design).

### Inputs
The domain knowledge of the experts and existing business processes are the input to this step.

### Outputs
The knowledge is written down and carved into:

 * A Domain Model, potentially per Subdomain[^1] or already per Bounded Context[^1] (but not necessarily in the first iteration)
 * Workflows that illustrate business processes, elicited with domain-driven practices such as Event Storming[^2] or Domain Storytelling[^3]
 * Use Cases and/or User Stories, as summarized in the Design Practice Repository (DPR)[^4]
 * Already known Non-Functional Requirements (NFRs) and technical/organizational constraints
 * Additional artifacts depending on project context and needs

## Supporting Tools

 * [Egon.io](https://egon.io/) for Domain Storytelling[^3]
 * Whiteboards or digital tools such as [Miro](https://miro.com/) for Event Stormings[^2]
 * [Context Mapper](https://contextmapper.org) for domain modelling, use cases, user stories

## Process Navigation

 * [Complete VDAD Process](./../value-driven-analysis-and-design)
 * [Next Step (2): Identify Stakeholders](./step-2-identify-stakeholders.md)


[^1]: _Domain-Driven Design Reference_, Eric Evans, <https://www.domainlanguage.com/ddd/reference/>
[^2]: <http://ziobrando.blogspot.com/2013/11/introducing-event-storming.html>
[^3]: _Domain Storytelling: A Collaborative, Visual, and Agile Way to Build Domain-Driven Software_, Stefan Hofer, Henning Schwentner, <https://domainstorytelling.org/>
[^4]: _Design Practice Repository (DPR)_, Olaf Zimmermann and Mirko Stocker, <https://github.com/socadk/design-practice-repository>
