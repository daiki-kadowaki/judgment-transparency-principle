
Judgment Transparency Principle

⸻

Core Statement

No system may enforce outcomes based on judgments that are not perceivable by the user.

⸻

Definitions

Judgment
A judgment is any system-internal decision that affects user outcomes, including but not limited to state resolution, hit detection, eligibility determination, prioritization, timing resolution, or authority arbitration.
A judgment may be deterministic or probabilistic, local or networked, real-time or delayed.

Perceivable
Perceivable means that the user can recognize, directly or indirectly, what was judged, when the judgment occurred, and on what basis the outcome was enforced, without requiring developer tools, debugging modes, or privileged system access.

Perceivability does not require constant exposure, full internal disclosure, or technical literacy.
It requires that the judgment becomes perceivable at the moment it affects the user.

User
The user is any human agent whose actions or decisions are constrained, overridden, accepted, or rejected by the system’s judgment.

⸻

Principle Scope

This principle is domain-agnostic.

It applies to interactive systems including, but not limited to:
	•	Digital games and competitive simulations
	•	Networked or distributed interactive systems
	•	XR, VR, AR, and cross-reality environments
	•	Human–machine interfaces that mediate action, control, or consequence

The principle applies regardless of implementation details, computational models, or architectural choices.

⸻

Clarifications

This principle does not mandate constant visualization, permanent overlays, or exhaustive explanation.

This principle does not prohibit abstraction, automation, prediction, or latency compensation.

This principle requires only that when a judgment materially affects the user’s outcome, the existence and nature of that judgment are perceivable to the user.

A system that enforces outcomes while concealing the operative judgment violates this principle, regardless of intent, optimization goals, or user benefit claims.

⸻

Non-Exhaustive Examples of Judgments
	•	Collision or hit resolution
	•	State transitions with eligibility constraints
	•	Priority or authority resolution in concurrent actions
	•	Temporal judgments affected by latency, rollback, or prediction
	•	Hidden thresholds that alter success or failure

These examples are illustrative, not limiting.

⸻

Normative Claim

A system that enforces outcomes based on imperceivable judgments undermines user agency.

Perceivable judgment is a prerequisite for meaningful interaction.

⸻

Status

This document defines the Judgment Transparency Principle.

It is a foundational statement, not an implementation guide.

⸻

Authorship and Provenance

Originally articulated and formally defined by
Daiki Kadowaki.

This principle may be referenced, discussed, criticized, extended,
or implemented freely, provided the principle itself is attributed by name.

⸻

End of document.

⸻
