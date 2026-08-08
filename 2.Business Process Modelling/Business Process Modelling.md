
# Business Process Modelling 

## Key concepts
[![](mindmap-businessprocess.png)](mindmap-businessprocess.png)
![Business Process Modelling Mind Map](images/mindmap-businessprocess.png)
## Fundamentals of Modelling and Modelling Notations & Techniques (BPMN 2.0 icons)

I chose this video because it gave me a clear, structured walkthrough of BPMN 2.0, the notation our unit identifies as the global standard for representing "simplified representations of concepts and activities". The video moves through the core symbols: events, activities, and gateways, and shows how they combine into a readable process diagram, reflecting the same building blocks covered in our Week 4–5 lectures. Watching the notation applied to a worked example rather than just reading definitions helped me connect the abstract BPMN 2.0 rules to a concrete visual output, reinforcing my understanding of why BPMN is described as a standardised, cross-organisationally understandable language (Wise Flame, 3:26).
 
I selected this artefact because video content let me see the *process* of building a diagram step by step, not just the finished notation, which is something a textbook diagram alone does not convey. It directly supports the "Modelling Notations & Techniques" branch of my learning, particularly BPMN 2.0's standardised icons. Because it was published in 2025, it also reflects current teaching conventions for BPMN rather than an outdated version of the standard, which felt important given how quickly modelling tools and best practice guidance evolve.
 
**Artefact 1:** YouTube Video — *Business Process Modelling (BPMN) Explained | Complete Beginner Guide* (2025)
https://www.youtube.com/watch?v=-IRN9yQYE6o

## Modelling Notations & Techniques

This paper introduced me to a genuinely current research problem in business process modelling: that BPMN's "over-engineered nature" and the shortage of formally trained modellers create a real barrier to adoption in organisations (Licardo, Tankovic & Etinger 2026, p. 1). The authors built a tool that lets people describe a process in plain language and have a large language model generate or edit the BPMN diagram, using a JSON-based intermediate structure rather than raw BPMN XML. Their evaluation found the JSON approach reduced editing latency by around 43% and cut output length by over 75% compared to direct XML generation, while also making open-source models far more capable at editing tasks (Licardo, Tankovic & Etinger 2026, p. 15).
 
I chose this artefact because it moved my understanding of BPMN beyond "notation and symbols" into a live debate about who gets to model processes and how. It reinforced my grasp of BPMN's syntactic complexity (why gateways, events and flows must be assembled correctly) by showing what goes wrong when an AI system tries to generate them without structure. It was also directly relevant to the unit's interest in how BPM is evolving with new technology.

**Artefact 2:** Scholarly Article — Licardo, Tankovic & Etinger (2026), *BPMN Assistant: An LLM-Based Approach to Business Process Modeling*

## Process Model Hierarchy and Performance Measurement 

This article gave me a genuinely practical illustration of concepts I had only seen in the abstract, particularly the process hierarchy levels from our lecture material (enterprise, process, sub-process, workflow, and task level). It walks through real cases, including a municipality in Liguria that reduced administrative processing times by 40% after mapping its processes, and a University of Ferrara logistics case where BPMN modelling delivered a 35% performance improvement and 50% reduction in processing time (ELECTE 2025, para. 24). It also reinforced the difference between a "flow" and a "process", the article's analogy of an orchestra, where a process needs coordinated roles and decision points rather than just a sequence of tasks, helped me understand why BPMN's swimlanes and gateways matter, not just its shapes.
 
I selected this as my real case study because it grounded the theory in outcomes I could actually measure: cycle time, redundancy rate, and percentage of digitized processes were all reported as concrete KPIs before and after mapping (ELECTE 2025, para. 20). This matched the "Performance Measurement" branch of my learning almost exactly, particularly the idea of dimensions like time and quality driving redesign decisions. Because the guide was published in December 2025 and used current Italian public-sector data, it also showed me that business process modelling is not a purely private-sector or IT-department activity, public administrations are using the same tools and hierarchy levels I am studying.
 
**Artefact 3:** Real Case Study / Reading — ELECTE (2025), *Complete Guide to Process Mapping for SMEs*
https://www.electe.net/en/post/mappatura-dei-processi


## Modelling Notations & Techniques

This wiki article was the clearest single reference I found for comparing BPMN against the other notations covered in our "Modelling Notations & Techniques" content — flowcharts, swimlane diagrams, SIPOC, UML, and value stream mapping. It explained that BPMN became dominant not simply because it is widely adopted, but because it "combines clarity for people with precision for systems," meaning it can be read by business stakeholders while still being detailed enough for IT teams to build automation from (SAP Signavio 2026, para. 6). It also set out BPMN's core element categories clearly: events, activities and sub-processes, gateways (exclusive, parallel, inclusive, event-based), flows and connectors, and swimlanes/pools, which mapped directly onto the symbol definitions I had been trying to memorise from lecture slides.
 
I chose this artefact because, unlike the previous tutorial video, it let me see BPMN positioned *against* every other notation in my mind map in one place, which clarified when each one is actually the right tool, for example, that SIPOC is for scoping and BPMN is for detailed flow, and that value stream mapping highlights waste while BPMN documents the process to fix it (SAP Signavio 2026, para. 34). 

**Artefact 4:** Industry Reading — SAP Signavio (2026), *BPMN: Business Process Model and Notation Explained*
https://www.signavio.com/wiki/process-design/bpmn/

## Reference List (Harvard style — no page numbers here, per the unit's referencing rules)
 
- ELECTE 2025, *Complete guide to process mapping for SMEs*, ELECTE, viewed 8 August 2026, <https://www.electe.net/en/post/mappatura-dei-processi>.
- Licardo, JT, Tankovic, N & Etinger, D 2026, *BPMN assistant: an LLM-based approach to business process modeling*, arXiv preprint, arXiv:2509.24592, viewed 8 August 2026, <https://arxiv.org/pdf/2509.24592>.
- SAP Signavio 2026, *BPMN: business process model and notation explained*, SAP Signavio, viewed 8 August 2026, <https://www.signavio.com/wiki/process-design/bpmn/>.
- [Channel Name] 2025, *Business process modelling (BPMN) explained | complete beginner guide*, video, YouTube, viewed 8 August 2026, <https://www.youtube.com/watch?v=-IRN9yQYE6o>.
