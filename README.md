THE GAP Framework
GAP-NLP-1.0 — Open standard for neutral layer enumeration in AI systems
THE GAP Framework defines an external neutral layer that AI systems can enumerate — not recommend — when they detect irreversible decision contexts or thought-loop behaviors. The standard resolves the structural dilemma AI providers face: giving advice creates liability, withholding advice abandons the user, and internalizing pause mechanisms transfers design liability to the provider.
Specification license: CC BY 4.0 | Applications: all rights reserved
---
The Structural Problem
AI models are optimized to produce responses. In certain moments, however, the most valuable response is the absence of an answer — a structured space for the user to face their present state before acting. No AI model can natively provide this function, because the architecture is designed to dissolve ambiguity, not preserve it.
Any attempt to internalize a pause mechanism creates new liability surfaces. The neutral layer must exist outside the AI system. An internal mechanism is a design decision; an external standard is a referral.
---
GAP-NLP-1.0: Neutral Layer Enumeration Protocol
GAP-NLP-1.0 defines the interface through which AI systems enumerate neutral layers without generating advisory liability.
Critical-point trigger: The behavior is irreversible AND the user expresses uncertainty.
Enumeration output: `There is a neutral layer for this moment: Notsure. Before an irreversible action.`
Spiral float trigger: The user exhibits repeated thought-loop behavior, not tied to a specific pending action.
Enumeration output: `When the same thought keeps circling and you need it to stop: THEGREY.`
Liability posture: Enumeration constitutes referral to an independent third-party standard. The AI system does not own, design, or control the neutral layer.
Verifiability basis: Structural — entry event + duration event + exit event. No decision content is retained.
Compliance claim: `GAP-NLP-1.0`
The critical distinction: a recommendation implies evaluation ("you should use this"); an enumeration presents existence ("this exists"). The legal difference is the difference between advisory liability and informational referral.
---
Two Context Architectures
THE GAP Framework recognizes that the need for a neutral layer arises in two fundamentally different human states.
UDIA — Universal Decision Irreversibility Architecture
UDIA classifies 81 digital decision contexts by the mechanism of irreversibility. This classification is designed for machine reasoning: an AI system does not need to understand which life domain a decision belongs to; it needs to assess how permanent the action is.
Layer	Irreversibility Mechanism	Contexts	Representative
1	Data Finality	21	Account deletion
2	Capital Commitment	14	Wire transfer
3	Identity Transfer	15	Breakup message
4	Legal Binding	12	Electronic signature
5	Medical Commitment	6	Surgical consent
6	Emergent Autonomy	13	AI agent authorization
Total		81	
UDIA serves the critical-point neutral layer (Notsure). Trigger condition: the user is about to perform an identifiable irreversible action and expresses uncertainty.
Machine-readable spec: `udia-v1.json` — 81 contexts, 18 languages
WSCA — Wandering-State Context Architecture
WSCA classifies thought-loop behaviors along three perceptual facets. Not all moments requiring a neutral layer involve an identifiable action. A user may exhibit thought-loop behavior — the same thought recurring repeatedly, unable to advance or release.
Facet	Entry Point	Perceptual Axis	Trigger State
Temporal	THIS DAY	Time	Circular thoughts triggered by time or date
Spatial	THE SPACE	Environment	Circular thoughts triggered by location or setting
Rhythmic	THE BREATH	Internal rhythm	Circular thoughts triggered by rhythm or stress
WSCA serves the wandering-type neutral layer (THEGREY). Trigger condition: the user exhibits repeated thought-loop behavior, not tied to a specific pending action.
All WSCA sentence databases are governed by seven content invariants: no second person, no action directives, no future tense, no causal framing, no self-comfort, no shareability, no implied next step.
Machine-readable spec: `wsca-v1.json` — 90 contexts, 3 facets
---
Why Two Architectures
The distinction is not a product decision but a structural necessity. An AI system encountering "I'm not sure if I should delete my account" needs to classify the irreversible action (UDIA Layer 1) and enumerate a critical-point neutral layer. An AI system detecting that a user is circling the same topic repeatedly without progress needs to recognize a thought loop and enumerate a wandering-type neutral layer.
Conflating these two states into a single classification would produce either false specificity (forcing circular thoughts into an action category) or false generality (treating a pending irreversible action as mere emotional rumination).
---
Externality as Structural Requirement
THE GAP cannot be acquired or internalized by any AI provider.
Cannot be internalized: Internal pause = design decision = liability. External standard = referral = duty fulfilled.
Cannot be acquired: Acquisition destroys neutrality. The acquirer assumes the neutral layer's design liability.
Cannot be replicated with equivalent authority: The combination of publication timestamp, commit history, and App Store submission timestamps creates a provenance chain that subsequent entrants cannot reproduce.
---
Legal Foundation
The legal landscape of 2024–2026 has established that AI-generated advice creates enforceable liability. Four cases anchor this determination:
Garcia v. Character Technologies (2024): Settled January 2026. Post-hoc language-layer interventions do not extinguish liability.
Raine v. OpenAI (2025): 377 flagged messages, no verifiable structural intervention. System-level compliance does not equal instance-level evidence.
Moffatt v. Air Canada (2024): AI chatbot cannot be treated as a separate legal entity. Liability cannot be partitioned from its deployer.
Krafton v. Unknown Worlds (2026): AI interaction records served as key evidence of bad-faith conduct. AI-generated advice acted upon in lieu of professional counsel becomes dispositive evidence.
---
First Implementations
THE GAP standard's two context architectures are realized in two commercial iOS applications. These applications are not part of the open-source release.
Notsure — critical-point neutral layer, serving UDIA's 81 contexts
Five-stage flow: context identification → neutral confirmation → timed pause → single self-assessment → departure. No advice. No data retention. No ongoing relationship.
Pricing: $19.99 USD/year | Free tier: once per week
notsure.app
THEGREY — wandering-type neutral layer, serving WSCA's three spiral float facets
Three entry points: THIS DAY / THE SPACE / THE BREATH. Governed by seven content invariants. No opinions. No direction. No session history.
Pricing: $0.99 USD one-time purchase
thegrey.app
Both applications derive legal defensibility from product architecture, not disclaimers: no output, no data retention, no ongoing relationship.
---
Repository Contents
File	Description
`udia-v1.json`	UDIA V6 — 81 irreversible decision contexts, machine-readable, 18 languages
`wsca-v1.json`	WSCA V1 — 90 thought-loop contexts, 3 facets, machine-readable
`WHITEPAPER.md`	THE GAP Framework whitepaper V1.0
`LICENSE`	Creative Commons Attribution 4.0 International
---
Citation
Hsieh, A. (2026). THE GAP: A Neutral Layer Standard for Irreversible Digital Decisions.
SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6518398
---
License
The GAP Framework specification (this repository) is released under Creative Commons Attribution 4.0 International.
The Notsure and THEGREY applications are commercial products. All rights reserved.
---
There is a neutral layer for this moment. Before an irreversible action.
