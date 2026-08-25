AI Ecosystem

Functional Psychology — Public AI Architecture

Author: Vladimir Gulyaev

This document describes the public high-level AI architecture of Functional Psychology.

The purpose of the AI ecosystem is to make the canonical psychological system accessible through intelligent digital interfaces while preserving:

* a single authoritative source of truth
* diagnostic consistency
* multilingual access
* separation between public documentation and proprietary knowledge
* separation between user interfaces and the private core

This document intentionally does not disclose private source code, internal prompts, canonical knowledge packs, scoring logic, credentials, private endpoints or closed inference rules.

⸻

1. General Architecture

The high-level architecture is:

Canonical Corpus
      ↓
Structured Knowledge
      ↓
Gulyaev AI Core
      ↓
Semantic Retrieval / RAG
      ↓
Reasoning Layer
      ↓
API
      ↓
Assistants / Applications
      ↓
Users

The system is designed so that the psychological canon remains logically separate from any single AI model or interface.

⸻

2. Canonical Corpus

The highest knowledge layer is the canonical corpus of Functional Psychology.

This includes the authoritative theoretical and methodological materials of the system.

At the highest level:

Volume I
+
Volume II
+
Volume III
+
approved applications
+
approved diagnostic materials
=
Canonical Corpus

The canonical corpus is the source from which structured AI knowledge is derived.

⸻

3. Single Source of Truth

A central architectural rule is:

one authoritative canon

The AI system should not independently invent alternative versions of Functional Psychology.

The purpose of the core is to preserve consistency across:

* websites
* assistants
* diagnostic tools
* professional interfaces
* APIs
* multilingual environments
* future applications

⸻

4. Canonical Knowledge vs. Public Documentation

The public GitHub repository is not the complete AI knowledge base.

It contains:

public documentation

The private core may contain:

canonical structured knowledge
+
diagnostic logic
+
reasoning constraints
+
internal system instructions
+
private retrieval materials

These layers must remain separate.

⸻

5. Knowledge Engineering

The encyclopedia and diagnostic corpus should not simply be copied into an AI system as raw documents.

They should be transformed into structured knowledge.

Possible internal structures may include:

* canonical definitions
* laws
* rules
* distinctions
* psychotype descriptions
* diagnostic constraints
* hypothesis registries
* contradiction rules
* interaction models
* state models
* reconstruction principles
* scientific-status labels

The exact private implementation is not published here.

⸻

6. Knowledge Pack

A private knowledge layer may be organized into specialized modules.

A conceptual example is:

00_CANON
01_PSYCHOTYPE_A
02_PSYCHOTYPE_B
03_PSYCHOTYPE_C
04_PSYCHOTYPE_D
05_DISINTEGRATION_E
06_DIAGNOSTICS
07_INTERACTION
08_ORGANIZATIONS
09_RECONSTRUCTION
10_RESEARCH

This is a conceptual public illustration.

The actual private knowledge pack may contain additional structure and internal logic.

⸻

7. Why Structured Knowledge Matters

Raw text alone creates several risks.

An AI may:

* retrieve incomplete fragments
* mix old and new definitions
* treat hypotheses as facts
* confuse E with a fifth psychotype
* infer rules not present in the canon
* produce inconsistent terminology

Structured knowledge reduces these risks.

⸻

8. Priority of Canonical Rules

When multiple pieces of information conflict, the AI should follow an explicit hierarchy.

At a high public level:

latest approved canonical rule
↓
approved core knowledge
↓
approved encyclopedia material
↓
public documentation
↓
historical or superseded material

The precise private precedence system may be more detailed.

⸻

9. Gulyaev AI Core

Gulyaev AI Core is the private technological and knowledge layer behind AI implementations of Functional Psychology.

Its role is to coordinate:

* canonical knowledge
* retrieval
* reasoning constraints
* API access
* multilingual processing
* assistant behavior
* future diagnostic services

The core is conceptually independent from any one front-end application.

⸻

10. Core and Interface Separation

The architecture separates:

knowledge and reasoning

from:

user interface

This means the same core may support:

* a public website assistant
* a professional psychologist interface
* a Custom GPT
* mobile applications
* educational tools
* research interfaces
* third-party integrations

without rebuilding the psychological system each time.

⸻

11. Retrieval-Augmented Generation

A future or expanded implementation may use RAG:

RAG = Retrieval-Augmented Generation

The process can be represented as:

User Query
↓
Semantic Search
↓
Relevant Canonical Fragments
↓
Reasoning
↓
Response

The purpose is to ground AI output in the authoritative corpus.

⸻

12. Semantic Retrieval

Semantic retrieval should search by meaning rather than exact wording.

For example, a user may describe:

fear of disappointing a significant person

without using the terminology of Functional Psychology.

The system should be able to retrieve conceptually relevant canonical material.

⸻

13. Multilingual Semantic Search

The system is designed for international use.

A user may ask a question in:

* English
* Russian
* Chinese
* Spanish
* German
* French
* Arabic
* or another supported language

while the canonical corpus remains primarily Russian.

A multilingual retrieval layer should connect:

foreign-language query
↓
semantic meaning
↓
Russian canonical knowledge

⸻

14. Language Independence

The intended architecture is:

User Language
↓
Language Detection
↓
Semantic Interpretation
↓
Canonical Reasoning
↓
Answer in User Language

Therefore the user does not need to know Russian to access the system.

⸻

15. Canonical Reasoning Must Be Language-Independent

Translation must not change the theory.

For example, the rule:

E ≠ fifth psychotype

must remain unchanged regardless of output language.

The language layer should translate the answer, not reinterpret the canon.

⸻

16. Reasoning Layer

The reasoning layer applies system rules to retrieved knowledge.

At a high level, it may:

* compare hypotheses
* detect contradictions
* separate type from state
* distinguish canonical rules from working hypotheses
* analyze interaction patterns
* preserve uncertainty
* prevent invalid conclusions

The actual internal reasoning instructions remain private.

⸻

17. Reasoning Is Not Free Hallucination

The AI should not be allowed to create new Functional Psychology rules simply because they appear plausible.

The canonical principle is:

AI may reason from the system
AI may not silently rewrite the system

New hypotheses generated by AI should be labeled as new hypotheses.

⸻

18. Diagnostic Reasoning

For diagnostic use, the AI must preserve core distinctions.

Examples include:

A / B / C / D = competing type hypotheses
E = state dimension

and:

Psychotype ≠ Role ≠ Skill ≠ State

The AI should also maintain uncertainty when evidence is insufficient.

⸻

19. Probability Discipline

Where diagnostic probabilities are used:

A + B + C + D = 100%

These values represent competing type hypotheses.

They should change only when new diagnostic evidence appears.

The AI should not increase confidence simply because a conversation becomes longer.

⸻

20. Functional Profile Is Separate

After the underlying type is established, the AI may describe a functional realization profile.

This is different from type probability.

Therefore:

type probabilities
≠
functional profile

The profile values do not need to sum to 100%.

⸻

21. Public Assistant

A public Functional Psychology assistant may help users with:

* understanding system concepts
* exploring relationships
* discussing interaction patterns
* learning the A–D/E architecture
* understanding development
* exploring organizational dynamics
* navigating public documentation

It should not automatically expose private diagnostic logic.

⸻

22. Professional Assistant

A professional interface may provide a deeper level of access for qualified users.

Potential functions may include:

* structured diagnostic sessions
* case formulation
* competing hypothesis analysis
* interaction analysis
* report generation
* longitudinal comparison
* professional notes

Access levels can be separated from public use.

⸻

23. Access Control

Different users may receive different permissions.

A conceptual model is:

Public
↓
Registered
↓
Professional
↓
Research
↓
Administrative / Core

Each level may expose different functions.

The exact access model remains implementation-specific.

⸻

24. API Layer

The API separates the core from external applications.

Conceptually:

Application
↓
API Request
↓
Gulyaev AI Core
↓
Canonical Processing
↓
API Response

This allows external interfaces to use the system without receiving the private knowledge base itself.

⸻

25. Why API Access Matters

API architecture makes it possible to support:

* websites
* mobile applications
* professional software
* educational systems
* research tools
* approved partner services

without copying the entire core into each product.

⸻

26. Controlled External Integration

Third-party AI systems may eventually interact with Functional Psychology through controlled interfaces.

The preferred model is:

third-party system
↓
authorized API
↓
Functional Psychology Core

rather than:

third-party system
← receives full private corpus

This preserves canonical control.

⸻

27. Model Independence

Functional Psychology should not depend permanently on one AI provider.

The architecture should allow the core to interact with different language models when appropriate.

Conceptually:

Functional Psychology Core
↓
Model Adapter
↓
AI Model A / B / C / future model

The theory remains stable even if the underlying model changes.

⸻

28. Provider Independence

This reduces risks associated with:

* model discontinuation
* pricing changes
* regional restrictions
* performance differences
* vendor lock-in

The psychological system remains separate from the commercial AI provider.

⸻

29. Retrieval and Reasoning Separation

The system should distinguish:

What knowledge is relevant?

from:

What conclusion follows?

The retrieval layer finds the relevant canonical material.

The reasoning layer applies the rules.

This separation improves traceability.

⸻

30. Source Traceability

Where practical, AI responses should be able to identify the source of important claims.

For example:

Canonical definition
Working hypothesis
Public documentation
Research evidence

This supports transparency.

⸻

31. Scientific Status Metadata

The AI knowledge system should preserve the scientific status of each proposition.

Possible labels may include:

CANONICAL_DEFINITION
THEORETICAL_MODEL
DIAGNOSTIC_OBSERVATION
WORKING_HYPOTHESIS
EMPIRICALLY_SUPPORTED
EXTERNALLY_REPLICATED

This prevents a working hypothesis from being presented as established fact.

⸻

32. Version Control

The knowledge core should be versioned.

A conceptual model is:

Functional Psychology Core
v1.0
v1.1
v2.0
...

Each version should identify:

* changed definitions
* added knowledge
* deprecated material
* scientific-status changes
* diagnostic updates

⸻

33. Canonical Freeze

When a corpus is declared final or canonical, it should not be silently modified.

Future changes should create a new explicit version.

This helps maintain:

* reproducibility
* historical traceability
* diagnostic consistency

⸻

34. Deprecated Knowledge

Old or superseded material may remain historically available but should be marked clearly.

For example:

STATUS: DEPRECATED

The AI should not use deprecated rules when a newer canonical rule exists.

⸻

35. AI Safety Boundary

The system should distinguish psychological analysis from medical diagnosis.

The AI should not claim to establish:

* psychiatric diagnosis
* neurological diagnosis
* medical diagnosis

unless an appropriately designed and validated medical system exists separately.

⸻

36. Human Professional Oversight

For high-stakes psychological use, human professional oversight may remain important.

AI can assist with:

* organization
* retrieval
* pattern comparison
* documentation
* hypothesis management

but professional judgment may still be required.

⸻

37. Privacy

Diagnostic systems may process highly personal information.

Therefore production implementations should consider:

* data minimization
* access control
* secure storage
* encryption
* retention policy
* user consent
* jurisdiction-specific privacy requirements

This public document does not describe the private operational security design.

⸻

38. Credentials and Secrets

The public repository must never contain:

API keys
tokens
passwords
private certificates
database credentials
private endpoints where disclosure creates risk
environment secrets

Secrets belong in protected infrastructure.

⸻

39. Public Repository Boundary

The public functional-psychology repository serves as:

documentation
+
public architecture
+
research framework
+
system presentation

It does not serve as the complete production backend.

⸻

40. Private Core Boundary

The private core may contain:

* application code
* canonical knowledge pack
* internal prompts
* retrieval configuration
* proprietary inference rules
* diagnostics
* private APIs
* deployment configuration
* protected integration logic

These materials remain separate.

⸻

41. Deployment Layer

A production architecture may conceptually look like:

Git Repository
↓
Deployment Platform
↓
Backend Service
↓
HTTPS API
↓
Applications

The exact infrastructure may change over time.

The conceptual architecture should remain portable.

⸻

42. Website Assistant

A standalone website can act as the primary public interface.

Conceptually:

Functional Psychology Website
↓
Chat Interface
↓
API
↓
Gulyaev AI Core

This allows users to access the system without entering a third-party AI interface.

⸻

43. Custom GPT and Other Assistants

Custom AI assistants can remain additional interfaces.

They may be useful for:

* testing
* professional workflows
* demonstrations
* specialized tasks

However, they should connect to the same canonical logic where possible.

⸻

44. Canonical Consistency Across Interfaces

The same question asked through:

* website
* professional interface
* Custom GPT
* API client

should not produce contradictory definitions of the system.

This is one reason for maintaining a centralized core.

⸻

45. Future Research Platform

The AI architecture may later support research.

Potential uses include:

* anonymized structured case analysis
* hypothesis testing
* longitudinal comparison
* inter-rater studies
* multilingual datasets
* pattern discovery

Research use should remain separate from ordinary user data unless appropriate consent and governance exist.

⸻

46. Logging and Auditability

For professional or research use, the system may need to preserve:

* model version
* core version
* evidence used
* diagnostic confidence
* important rule applications
* user corrections

This can support auditability.

⸻

47. Avoiding Knowledge Drift

Knowledge drift occurs when repeated AI generations gradually alter a theory.

The architecture should minimize this through:

canonical source
+
versioning
+
retrieval
+
reasoning constraints
+
explicit updates

This is particularly important for long-term AI use.

⸻

48. No Independent AI Canon

An AI model should not become the source of truth.

The rule is:

Canon → AI

not:

AI → Canon

The author-approved corpus remains authoritative.

⸻

49. Human Author Authority

Canonical changes originate from the author or an explicitly authorized governance process.

AI may:

* identify contradictions
* suggest revisions
* generate hypotheses
* compare versions

but should not silently promote those suggestions into canon.

⸻

50. International Architecture

The long-term ecosystem may support:

one canonical system
+
many languages
+
many interfaces
+
controlled access levels

This is preferable to maintaining independent translated theories that may gradually diverge.

⸻

51. High-Level Ecosystem Diagram

                    FUNCTIONAL PSYCHOLOGY
                         AUTHORITATIVE
                            CANON
                              │
                              ▼
                   STRUCTURED KNOWLEDGE
                              │
                              ▼
                     GULYAEV AI CORE
                              │
             ┌────────────────┼────────────────┐
             │                │                │
             ▼                ▼                ▼
      Semantic Retrieval   Reasoning      Version Control
           / RAG             Layer
             │                │
             └───────┬────────┘
                     ▼
                    API
                     │
       ┌─────────────┼─────────────┐
       ▼             ▼             ▼
 Public Website   Professional   External
   Assistant       Assistant    Integration
       │             │             │
       └─────────────┼─────────────┘
                     ▼
              Multilingual Users

⸻

52. Public AI Principles

The public architectural principles are:

1. One authoritative canon.
2. E remains a state, not a fifth psychotype.
3. Canon is independent from interface.
4. Canon is independent from AI provider.
5. Retrieval should be grounded in approved knowledge.
6. AI must distinguish canon from hypothesis.
7. Public documentation is not the private knowledge core.
8. API access is preferable to distributing the private corpus.
9. Multilingual access must preserve canonical meaning.
10. AI may reason from the system but may not silently rewrite it.

⸻

53. What This Repository Does Not Contain

For clarity, this public repository does not publish:

complete encyclopedia manuscripts
private diagnostic protocols
full internal interview logic
proprietary scoring systems
private system prompts
hidden AI instructions
canonical private RAG corpus
embeddings database
API keys
deployment secrets
private user data
closed inference procedures

⸻

54. Intended Development Path

The long-term public architecture can be represented as:

Encyclopedia
↓
Canonical Knowledge Pack
↓
Gulyaev AI Core
↓
RAG / Semantic Retrieval
↓
Reasoning
↓
API
↓
Public and Professional Interfaces
↓
Multilingual Functional Psychology Ecosystem

⸻

55. Canonical Summary

The central architectural principle is:

Functional Psychology must remain larger than any single AI model, application or interface.

The AI layer exists to provide access to the canon.

It does not replace the canon.

In simplified form:

CANON
↓
CORE
↓
AI
↓
API
↓
INTERFACES
↓
USER

And:

one system
many interfaces
many languages
one authoritative source of truth

⸻

Related Documentation

* Overview
* Functional Architecture
* Psychotypes A–D
* Disintegration State E
* Functional Diagnostics
* Interaction Between Psychotypes
* Organizational Systems
* Scientific Status

⸻

Intellectual Property

This document describes the public high-level AI architecture of Functional Psychology.

Publication does not grant access to the private Gulyaev AI Core, proprietary knowledge packs, diagnostic algorithms, prompts, source code, credentials, datasets or closed inference procedures.

© Vladimir Gulyaev. Functional Psychology. All rights reserved.
