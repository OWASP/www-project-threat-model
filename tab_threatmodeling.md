---

title: ThreatModeling
displaytext: Threat Modeling
layout:  null
tab: true
order: 1
tags: threatmodeling

---

## Overview

The term "Threat Modeling" has become quite popular. The "[State Of Threat Modeling Report](https://www.threatmodelingconnect.com/state-of-threat-modeling-2024-25)" points at a robust and improving practice across companies and enterprises of all sizes, embracing a growing number of tools and methodologies.

In 2020, a group of threat modeling practitioners, researchers and authors got together to write the [Threat Modeling Manifesto](https://www.threatmodelingmanifesto.org/) in order to "...share a distilled version of our collective threat modeling knowledge in a way that should inform, educate, and inspire other practitioners to adopt threat modeling as well as improve security and privacy during development". The Manifesto contains values and principles connected to the practice and adoption of Threat Modeling, as well as identified patterns and anti-patterns to facilitate it.

One of the outputs of the Manifesto was this consensus-driven definition:

"Threat modeling is analyzing representations of a system to highlight concerns about security and privacy characteristics."

A threat model is essentially a structured representation of all the
information that affects the security of an application. In essence, it
is a view of the application and its environment through security glasses.

Threat modeling is a process for capturing, organizing and analyzing
all of this information. Threat modeling enables informed
decision-making about application security risk. In addition to
producing a model, typical threat modeling efforts also produce a
prioritized list of security threats identified, and possibly mitigations to the risk they create.

## Why Threat Model?

Threat modeling embodies a family of activities for improving security by
identifying threats, understanding their criticality, and then defining
countermeasures to prevent, or mitigate the effects of these threats to the
system, functionality and user. A threat is a potential or actual undesirable event that may be malicious (such as CSRF attack) or incidental (thunderstorm knocking the power down). Threat modeling is a planned activity for identifying and assessing application threats and vulnerabilities. It can also encompass fields related to Security, like Safety and Privacy.

## Threat Modeling Across the Lifecycle

Threat modeling is best applied continuously throughout a software
development project - at whatever resolution may be practical for that specific project.

The process is essentially the same at different
levels of abstraction, although the information gets more and more
granular throughout the lifecycle. Ideally, a high-level threat model
should be defined in the ideation or design phase, and then refined
throughout the lifecycle. As more details are added to the system, new
attack vectors may be created and exposed. The ongoing threat modeling
process examines, diagnoses, and addresses these threats.

Note that it is a natural part of refining a system for new threats to
be exposed. For example, when you select a particular technology -- such
as Java for example -- you take on the responsibility to identify the
new threats that are created by that choice. Even implementation choices
such as using regular expressions for validation introduce potential new
threats to deal with.

Threat modeling can be divided into two closely related activities: system modeling and threat elicitation. It is very important that all participants in a threat model be able to recognize the system under analysis in whatever representation (diagram, textual, etc.) is chosen, as that recognition will be the basis of the threat elicitation phase.

## Benefits

Done right, threat modeling provides visibility across a
project that helps justify and support security efforts. The threat model allows security decisions to be made rationally, with all the information on
the table. The alternative is to make ad-hoc security decisions with
no support in real data, scenarios and outcomes. The threat modeling process naturally produces an assurance argument, or artifact, that can be used to explain and defend the security of an application. An assurance argument starts with a few high level claims, and justifies them with either sub-claims or evidence.

## Where to go from here?

Check the [Resources tab](https://owasp.org/www-project-threat-model/#div-resources) for more extensive documentation, books and tools to start you on your journey!
