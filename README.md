# Awesome Machine Capabilities and Skills [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of various resources related to machine Capabilties and Skills. In case you don't know what capabilities and skills in the context of manufacturing are:

**Capabilities** and **Skills** aim at a machine-interpretable description and encapsulated implementation of automation functions. 
- **Capabilities** represent a description of the functions that a machine can potentially perform. This description may include possible inputs and outputs as well as constraints to further specify a capability's application. Capabilities are modeled using technologies such as Semantic Web Technologies, the Asset Administration Shell or similar information modeling technologies 
- **Skills** on the other hand are an encapsulated implementation with an invocation interface. Think of a Skill like a web service. The actual implementation is often considered as a black box, while a so-called Skill Interface is provided to interact with a skill. A Skill's interface typically features a machine-interpretable description, too. In automation OPC UA is often used to implement a skill interface.

You can easily add something to this list by creating a pull request with your changes. Just edit the Readme.md file and propose your additions with a short explanation. There is also a [Wish List](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/issues/1) for things you would like to have but which are not on this list.

If you don't know what an Awesome List is, see this [awesome manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md).  And for other Awesome Lists, checkout the [Awesome List Github Topic](https://github.com/topics/awesome-list)

<hr>

## Contents
- [Standards & Specifications](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#standards--specifications)
- [Models](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#models)
- [Software Tools & Demos](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#software-tools--demos)
- [Publications](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#publications)
- [Working Groups](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#working-groups)
- [Projects](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#projects)
- [Companies and Academic Institutes](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#companies-and-academic-institutes)

<hr>

## Standards & Specifications
This section features links to relevant standards and similar publications
- [Reference Model for Capabilities, Skills and Services](https://www.plattform-i40.de/IP/Redaktion/EN/Downloads/Publikation/CapabilitiesSkillsServices.html) - Technically not a "real" standard, but a set of mutually agreed definitions published by the Plattform Industrie 4.0


## Models
This section contains links to existing models to express capabilities and skills
- [CSS-Ontology](https://github.com/hsu-aut/css-ontology) - A rather generic OWL ontology implementing the [Reference Model for Capabilities, Skills and Services](https://www.plattform-i40.de/IP/Redaktion/EN/Downloads/Publikation/CapabilitiesSkillsServices.html)
- [CaSk](https://github.com/hsu-aut/cask) - An OWL ontology extending the [CSS-Ontology](https://github.com/hsu-aut/css-ontology) by more specific model elements. Still a generic model that has more specific extensions.
- [CaSkMan](https://github.com/aljoshakoecher/caskman) - An OWL ontology extending [CaSk](https://github.com/hsu-aut/cask) to model capabilities and skills in manufacturing
- [AAS Capability Submodel](https://github.com/admin-shell-io/submodel-templates/tree/main/development/Capability/1/0) - Asset Administration Shell submodel to express capabilities
- [AAS Control Component Submodel](https://github.com/admin-shell-io/submodel-templates/tree/main/development/Control%20Component%20Type%20and%20Control%20Component%20Instance/1/0) - Asset Administration Shell submodel to model skills ❔ (needs clarification)

## Software Tools & Demos
In this section, software tools and demo applications are listed. These tools may cover the whole lifecycle of capabilities and skills. From engineering over process planning to actual execution.
- [SkillMEx](https://github.com/aljoshakoecher/SkillMEx) - A manufacturing execution system for skill-based manufacturing. Capabilities and skills can be registered and executed using SkillMEx
- [SkillUp](https://github.com/aljoshakoecher/skill-up) - A Java framework to implement skills. Automatically generates a state machine, an ontology description and OPC UA server (or web server) for execution. Uses the [CaSkMan ontology](https://github.com/aljoshakoecher/caskman).
- [PLC2Skill](https://github.com/aljoshakoecher/plc2skill) - An automated mapping approach to convert PLC programs written in IEC 61131-3 to a capability and skill ontology. Can be used to register capabilities and skills with SkillMEx.
- [MTP2Skill](https://github.com/hsu-aut/mtp2skill) - Converts a Module Type Package into a capability & skill ontology. Can be used to register capabilities and skills with SkillMEx.

## Publications
This section contains papers to be highlighted because they are of a more general interest. This could be survey papers consolidating a lot of research, or papers especially pointing out challenges as well as papers with fundamental definitons. Please note however, that this list cannot track all papers in this research area 😉 
- Malakuti et al. _Challenges in Skill-based Engineering of Industrial Automation Systems_ [DOI](http://dx.doi.org/10.1109/ETFA.2018.8502635) - Presents open challenges in capability-based engineering. Note that the term definition of "skill" doesn't match the current definition.
- Froschauer et al. _Capabilities and Skills in Manufacturing: A Survey Over the Last Decade of ETFA_ [DOI](http://dx.doi.org/10.1109/ETFA52439.2022.9921560) - Survey paper covering research about capabilities and skills that was presented at IEEE ETFA conferences over the last 10 years.

## Working Groups
An overview on working groups working on capability and skill standardization
- IDTA working group about AAS capability submodel
- IDTA working group about AAS control component submodel
- Plattform Industrie 4.0 working group about a meta model of capability and skills

## Projects
A list of projects (ongoing and finished) with a connection to capabilities and skills
- [ReCaM](https://cordis.europa.eu/project/id/680759) (11/2015 - 10/2018) - EU project about rapid reconfiguration of production systems through capability-based adaptation

## Companies and Academic Institutes
A list of companies, university groups and other research institutions working in this field
- Institute of Automation @ Helmut Schmidt University, Hamburg, Germany ([Website](https://www.hsu-hh.de/aut/))
