 Wellness and Safety Agentic AI System

An intelligent, safety-critical agentic AI first responder built on **IBM Cloud** using **watsonx Orchestrate** and **watsonx.ai foundation models**.



##  Problem Statement & Solution
Traditional mental health platforms rely on static information or entirely reactive, unstructured chat interfaces. This project bridges the gap by implementing an autonomous agent that delivers structured, vetted self-care routines via **Retrieval-Augmented Generation (RAG)**, while continuously monitoring live interactions for safety risks. 

Using a **ReAct (Reasoning and Acting)** framework, the agent dynamically determines whether to pull calming techniques from its knowledge base or proactively intercept severe psychological distress by triggering direct, deterministic routing to live human crisis lifelines.



## Key Features & Guardrails
* **Secure RAG Framework:** Bounded context ensures answers are strictly limited to verified mindfulness and self-care guidelines.
* **Early Risk Detection:** Automated semantic monitor layer that parses incoming queries for severe distress flags.
* **Deterministic Safety Escalation:** Instantly overrides standard chat flows to deliver active, 24/7 hotline resources directly to users.
* **Warm, Scannable Interface:** Formatted cleanly with intuitive markdown layouts and accessible quick-start conversational choices.



##  Technologies Used
* **IBM Cloud** (Infrastructure hosting)
* **IBM watsonx Orchestrate** (Agentic workflow design & workspace orchestrator)
* **watsonx.ai Foundation Models** (Natural language generation & intent routing)
* **Markdown & Prompt Engineering** (Behavior formatting & system boundaries)



## Repository Contents
* `mental health guidelines.txt`: Vetted knowledge base document for grounding and anxiety reduction.
* `agent_behaviour_prompt.txt`: The system prompt defining custom behaviors, scope rules, and early intervention triggers.
* `agent_profile.txt`: Front-end home screen configurations, descriptions, and quick-start conversational strings.

