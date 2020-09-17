---
permalink: /papers/
title: "Accepted papers"
---

-- ***"Towards a Formalization of Explanations for Robots’ Actions and Beliefs"*, Felix Lindner**:

A robot’s capacity to self-explain its behavior is a means of avoiding or mitigating failures and thus ensuring trust. This work presents a preliminary formal characterization of explanations embracing the distinctions between counterfactual explanations and regularity explanations, as well as generative and instrumental explanations. The formalization will guide future work on explanation generation, explanation sharing, and explanation understanding in human-robot interaction.


-- ***"Toward Equipping Artificial Moral Agents with Multiple Ethical Theories"*, J. George Rautenbach and C. Maria Keet**:

Management and use of robots, and Artificial Moral Agents (AMAs) more broadly, may involve contexts where the machines are expected to make moral decisions. The design of an AMA is typically compartmentalised among AI researchers and engineers on the one hand and philosophers on the other. This has had the effect that of the current AMAs, either none or at most one specified normative ethical theory is incorporated as basis. This is problematic because it narrows down the AMA's functional ability and versatility since it results in moral outcomes that only some people agree with, and possibly going counter to cultural norms, thereby undermining an AMA's ability to be moral in a human sense. We aim to address this by taking a first step toward normed behaviour. We propose a three-layered model for general normative ethical theories, therewith enabling the representation of multiple normative theories, and users' specific instances thereof. The main model, called Genet, can be used to serialise in XML the ethical views of people and businesses for an AMA and it is also available in OWL format for use in automated reasoning. This short paper illustrates Genet with Kantianism and utilitarianism, and the 'Mia the alcoholic' use case.


-- ***"Open the Pod Bay Door: Using Ontology to Understand Instructions"*, Yixin Sun and Michael Grüninger**:

There have been a great deal of developments and implementations for conversational robots like Amazon Alexa, and Google Home. Yet, little research has been done for robots to understand a more rigorously structured, instruction-wise natural language. In this paper, we present an ontology approach to convert instructions from natural language to logical formulas, Process Specification Language (PSL) in this case. Verbs, therefore, are treated as indication of actions or processes and are decomposed semantically to understand meanings. As a method of evaluating this approach, verbs, originally in PSL, are worked towards natural language. In this paper, we present how to take natural language instructions and map them to appropriate cutting classes; and moreover, we present the capability of this ontology-centered approach to go in a reverse direction (from PSL to natural language).


-- ***"On Planning in a Knowledge-Hypergraph"*, Joris Sijs, Willeke van Vught and Jeroen Voogd**:

Autonomous robots that operate in indoor, (partly) unknown environments move around from one location to the next to fulfill a set of ordered task. To do so, they need a floor plan of the building to plan their route. In case the building is unfamiliar to a robot it can employ online mapping techniques, though these techniques are resource intensive and time consuming. In addition, processing of the resulting map by an automated planner to determine a feasible route is resource demanding as well. The solution proposed in this article is to develop an ontology that combines knowledge of a floor plan with concepts in automated planning, so that robots become more efficient in planning their route. Moreover, the ontology is implemented as a hypergraph to benefit from its advances in creating elegant inference-rules, e.g., to infer route-alternatives while preparing the operation.


-- ***"Using Linked Data to Help Robots Understand Product-Related Actions"*, Michaela Kümpel, Anna de Groot, Ilaria Tiddi and Michael Beetz**:

Household robots need semantics to understand that a detergent is a cleaning product that can be used to clean physical objects like a table, but laundry detergent is only used to clean/wash laundry. A safely acting autonomous robot should also know that both will not be used as ingredients for meal preparation. We propose a new approach to connect robot sensor data to Linked Data in order to give robotic agents semantic product information about objects that can be found in their environment. For this, we use the robots belief state when recognizing a product and link it to a product ontology that follows Semantic Web standards. We then use the product class information to fetch further information from external sources like Wikidata or ConceptNet that contains action information (e.g. laundry detergent is used for laundering). At last, the action results are mapped to internally known actions of the robotic agent so that it knows which action can be performed with the given object.


-- ***"Robot Meets World"*, Jona Thai and Michael Gruninger**:

The representation of the world in which an autonomous robot interacts with other objects within the world requires the integration of perception, reasoning, and action. The challenge of designing a suite of ontologies that are expressiveness enough to support perception and reasoning is a preeminent challenge for the knowledge representation and applied ontology communities. In this paper, we propose a series of challenge problems oriented around the ways in which a robot encounters the physical world. We outline an approach to the design and application of ontologies that can be used to represent the problems and their solution.


-- ***"What Say You: An Ontological Representation of Imperative Meaning for Human-Robot Interaction"*, Robert Porzel and Vanja Sophie Cangalovic**:

There is a distinct difference between modeling linguistic knowledge and knowledge that is expressed linguistically. The research effort described herein concerns the latter, i.e. how to model the output of a natural language understanding system in a formal ontology in such a way that robotic agents can carry out the tasks given to them via natural language. For this, we build on a given foundational ontology that is suitable for our requirements and introduce the basic modeling principles and design patterns to model and represent the meaning of instructions. Linguistically, our model is informed by constructional approaches to language understanding, i.e. embodied- and fluid construction grammar. Ontologically, we base our model on the foundational framework provided by the Dolce Ultra Light + Descriptions and Situations ontology. The proposed model, called SOMA-SAY, is part of a larger system of ontologies that are employed in the Everyday Activity Science and Engineering collaborative research center.


-- ***"''Knowing from'' -- An Outlook on Ontology Enabled Knowledge Transfer for Robotic Systems"*, Mohammed Diab, Mihai Pomarlan, Daniel Bessler, Stefano Borgo and Jan Rosell**:

Encoding practical knowledge about everyday activities has proven difficult, and is a limiting factor in the progress of autonomous robotics. Learning approaches, e.g. imitation learning from human data, have been used as a way to circumvent this difficulty. While such approaches are on the right track, they require comprehensive knowledge modelling about the data present in records of activity episodes, and about the skills one attempts to have the robot learn. We provide a list of competency questions such knowledge modelling should answer, summarize some recent developments in this direction, and finish with a few open problems.
