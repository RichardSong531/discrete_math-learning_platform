# Learning model

A knowledge node should explain one manageable concept and its prerequisites.

1. Build intuition in plain language.
2. Explore a diagram or interactive example.
3. Follow a worked example with explicit reasoning.
4. Try a lab or practice questions.
5. Examine common mistakes and feedback.
6. Complete a mastery check and revisit weaknesses through mixed practice.

Current maps use module-specific browser storage and distinguish learning/review states.
Their UI labels mastery at 80% or above. This prototype scoring rule does not establish
durable understanding. In a four-question check, this means 4/4 for mastery;
3/4 is 75% and marks partial progress. Recommendations operate within a module; cross-topic prerequisites
are not enforced by a shared system.

The Proof Methods & Induction module adds a per-node written-proof notebook.
These drafts are not automatically graded or certified as valid proofs. They are
stored separately from quiz scores in the same browser; resetting mastery preserves
drafts, and clearing drafts preserves scores. A model step order or suggested proof
strategy provides guidance, not a general proof-validity check.

Sequences & Recurrences lets learners compare iterated terms with proposed formulas.
Agreement on finitely many terms illustrates a pattern; it does not prove a claim
for all indices. Its fixed proof-order exercises and multiple-choice checks do not
grade written proofs. Use the [Proofs notebook](../modules/proofs/index.html) for
ungraded drafts and review the reasoning separately.

Discrete Probability combines finite outcome enumeration and formula-based
calculators with random simulations. A simulation illustrates variability and
approximates a model's probabilities; it does not prove a probability identity.
Learners should state assumptions such as equal likelihood, independence, and
replacement before choosing a formula. The module's scored evidence comes from
multiple-choice checks; it does not grade written probability solutions.

Future models should distinguish attempts, feedback, mastery evidence, and review
scheduling. Validate these concepts across modules before introducing a common schema.
The full-curriculum repair pass should also preserve the distinction between scored
practice and ungraded drafts, including their separate persistence and reset behavior.
Retain bilingual explanations where they clarify terminology.
