# Awesome Machine Capabilities and Skills
A curated list of various resources related to machine Capabilties and Skills. In case you don't know what capabilities and skills in the context of manufacturing are:

> **Capabilities** and **Skills** aim at a machine-interpretable description and encapsulated implementation of automation functions. **Capabilities** represent a description of the functions that a machine can potentially perform. This description may include possible inputs and outputs as well as constraints to further specify a capability's application. Capabilities are modeled using technologies such as Semantic Web Technologies, the Asset Administration Shell or similar information modeling technologies 
> **Skills** on the other hand are an encapsulated implementation with an invocation interface. Think of a Skill like a web service. The actual implementation is often considered as a black box, while a so-called Skill Interface is provided to interact with a skill. A Skill's interface typically features a machine-interpretable description, too. In automation OPC UA is often used to implement a skill interface.

## Content
- [Standards & Specifications](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#standards--specifications)
- [Models](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#models)
- [Tools](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#tools)
- [Working Groups](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#working-groups)
- [Projects](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#projects)
- [Companies and Academic Institutes](https://github.com/aljoshakoecher/awesome-machine-capabilities-and-skills/main/README.md#companies-and-academic-institutes)


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

## Tools

## Publications
This section contains papers to be highlighted because they are of a more general interest. This could be survey papers consolidating a lot of research, or papers especially pointing out challenges as well as papers with fundamental definitons. Please note however, that this list cannot track all papers in this research area 😉 
- Malakuti et al. _Challenges in Skill-based Engineering of Industrial Automation Systems_ [DOI](http://dx.doi.org/10.1109/ETFA.2018.8502635) - Presents open challenges in capability-based engineering. Note that the term definition of "skill" doesn't match the current definition.
- Froschauer et al. _Capabilities and Skills in Manufacturing: A Survey Over the Last Decade of ETFA_ [DOI](http://dx.doi.org/10.1109/ETFA52439.2022.9921560) - Survey paper covering research about capabilities and skills that was presented at IEEE ETFA conferences over the last 10 years.

## Working Groups
- IDTA Working Group about AAS capability submodel
- IDTA Working Group about AAS control component submodel

## Projects
A list of projects (ongoing and finished) with a connection to capabilities and skills
- [ReCaM](https://cordis.europa.eu/project/id/680759) (11/2015 - 10/2018) - EU project about rapid reconfiguration of production systems through capability-based adaptation

## Companies and Academic Institutes
A list of companies, university groups and other research institutions working in this field
- Institute of Automation @ Helmut Schmidt University, Hamburg, Germany ([Website](https://www.hsu-hh.de/aut/))
