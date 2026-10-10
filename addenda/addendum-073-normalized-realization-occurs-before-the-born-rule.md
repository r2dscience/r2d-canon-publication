---
r2d_id: addendum-073
title: Addendum 73 — Normalized Realization Occurs Before the Born Rule
subtitle: Detector Occupancy, Additive Boundary Measure, and the Origin of Squared Quantum Amplitude
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: false
addendum: 73
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2416
pdf_page_end: 2448
math_representation: LaTeX for normalized equations; source PDF layout text retained for remaining equations
equation_status: candidate_visual_reconstruction_pending_author_review
equation_audit_scope: archived_pdf_visual_comparison; author_review_pending
primitive_authority: false
review_status: author_review_pending
semantic_sync: 2026-09-25-boundary-ordering-and-conditional-bridges-preserved
machine_revision: 2026-10-09-equation-reconstruction-v1
qa_status: standalone_render_pass_full_book_pending
promotion_date: null
equation_source_conflict_rule: publication_pdf_controls
---

# Addendum 73 — Normalized Realization Occurs Before the Born Rule

*Detector Occupancy, Additive Boundary Measure, and the Origin of Squared Quantum Amplitude*

## Abstract

<!-- source_pdf_page: 2416 -->

The Born rule assigns a measurement outcome i the probability

$$ p_i=|\langle i|\psi\rangle|^2. $$

Quantum mechanics ordinarily introduces this relation as a postulate connecting a complex state vector to
observed outcomes.

R2D cannot begin with probability or squared amplitude.

A measurement is first a boundary-realization event.

A detector boundary BM defines a set of mutually exclusive readable macrostates

$$\{i\}$$

Across repeated equivalent realizations, those detector states acquire realized occupancy counts

$$ c_i$$

The total realized detector count is

$$ C=\sum_i c_i$$

The corresponding normalized realization measure is therefore

$$ \mu_i=\frac{c_i}{C}. $$

This relation precedes quantum probability.

It is simply normalized count.

<!-- source_pdf_page: 2417 -->

The existing R2D measurement architecture already distinguishes detector occupancy from the Born rule. It
explicitly states that a binary detector law does not yet establish how an arbitrary quantum amplitude maps
onto measurement-boundary realization.

Addendum 72 supplies the missing phase-side structure.

Boundary-native recurrent closure gives a cyclic group

$$ C_K$$

whose complex characters

$$ \chi_m(j)=e^{i2\pi mj/K} $$

are orthogonal:

$$\frac1K\sum_{j=0}^{K-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

Thus closure gives a natural complex inner-product representation before probability is assigned.

The remaining problem is to connect that complex state representation to normalized detector realization.

The crucial primitive property of detector realization is additivity.

If i and j are mutually exclusive detector macrostates, then their realized counts add:

$$ c_{i\vee j}=c_i+c_j. $$

Therefore their normalized realization measures satisfy

$$ \mu_{i\vee j}=\mu_i+\mu_j. $$

When a complete detector classification is represented quantum mechanically by mutually orthogonal
projectors

$$\{P_i\}$$

with

$$ P_iP_j=0\quad(i\ne j)$$

and

<!-- source_pdf_page: 2418 -->

∑ Pi = I,

$$\sum_iP_i=I$$

the R2D count relation becomes

$$ \mu(P_i+P_j)=\mu(P_i)+\mu(P_j) $$

for orthogonal alternatives, together with

$$ \mu(I)=1. $$

One additional physical requirement is needed.

The normalized realization assigned to a particular detector alternative must depend on the physical
alternative itself and the incoming quantum state, not merely on which other mutually exclusive
alternatives happen to complete the detector classification.

Thus, for the same physical projector P ,

$$\mu_\Psi(P)$$

is invariant under a change of the remainder of the complete classification, provided the physical meaning
of P itself has not changed.

This is the relevant R2D noncontextuality condition.

It does not assert that measurement outcomes possess predetermined values independent of apparatus.

Changing the apparatus can change the physical projector.

It asserts only that the same boundary-defined alternative receives the same normalized realization
measure.

Once the quantum projection is represented in a complex Hilbert space, these requirements are precisely
those needed for the standard measure theorem underlying the Born rule.

For complex Hilbert dimension at least three, a normalized nonnegative additive measure on orthogonal
projectors must have the form

$$ \mu_\rho(P)=\operatorname{Tr}(\rho P), $$

where

$$\rho\ge0$$

and

<!-- source_pdf_page: 2419 -->

Tr ρ = 1.

The quantum density operator is therefore the mathematical object that represents the normalized
realization measure consistently across all complete detector classifications.

For a pure quantum state,

$$ \rho=|\psi\rangle\langle\psi|. $$

For a rank-one detector outcome,

$$ P_i=|i\rangle\langle i|. $$

Then

$$\mu_i=\operatorname{Tr}(|\psi\rangle\langle\psi|\,|i\rangle\langle i|)$$

so

$$\mu_i=|\langle i|\psi\rangle|^2$$

But R2D began with

$$ \mu_i=\frac{c_i}{C}. $$

Therefore:

$$\frac{c_i}{C}=|\langle i|\psi\rangle|^2$$

This is the Born rule interpreted as a normalized boundary-realization law.

The logical order is therefore reversed from the usual presentation.

R2D does not begin with

$$|\psi_i|^2$$

and declare it to be probability.

It begins with mutually exclusive realized detector counts,

$$ c_i$$

normalizes those counts,

<!-- source_pdf_page: 2420 -->

$$\mu_i=\frac{c_i}{C}$$

and requires that the same count measure remain additive and classification-consistent when represented
through the complex quantum state space.

The Born form then follows.

This also resolves the square-root amplitude problem left open by Addendum 72.

In a detector basis,

$$\psi_i=\langle i|\psi\rangle$$

Therefore,

$$|\psi_i|^2=\frac{c_i}{C}$$

Hence:

$$|\psi_i|=\sqrt{\frac{c_i}{C}}$$

Writing the closure phase of alternative i as

$$\phi_i$$

the normalized quantum coordinate becomes

$$\psi_i=\sqrt{\frac{c_i}{C}}\,e^{i\phi_i}$$

An unnormalized count-coordinate can equivalently be written

$$\widetilde\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

The square root of occupancy is therefore not inserted in order to manufacture the Born rule.

It follows after the normalized boundary measure has been shown to possess the Born form.

Thus:

> normalized realization → Born measure → square-root amplitude.

The quadratic form also has a direct physical interpretation.

<!-- source_pdf_page: 2421 -->

Addendum 72 established that the quantum state carries closure phase and that an absolute phase origin
is not primitive.

Under a global phase transformation,

$$|\psi\rangle\to e^{i\alpha}|\psi\rangle$$

the vector itself changes representation.

But the operator

$$\rho_\psi=|\psi\rangle\langle\psi|$$

does not:

$$ e^{i\alpha}|\psi\rangle\langle\psi|e^{-i\alpha}=|\psi\rangle\langle\psi|$$

Thus the quadratic state relation removes arbitrary absolute phase while retaining all physically relevant
relative-phase structure.

The realized detector measure is then

$$\mu_i=\operatorname{Tr}(\rho_\psi P_i)$$

The square in the Born rule is therefore not merely an empirical numerical trick.

It is the phase-invariant count read of a phase-carrying quantum state.

The result also connects directly to the primitive R2D occupancy coordinate

$$ G_i=\ln c_i$$

Since

$$ c_i=C|\psi_i|^2$$

one has

$$ G_i=\ln C+2\ln|\psi_i|$$

For two alternatives in the same normalization domain,

$$ G_i-G_j=2\ln\frac{|\psi_i|}{|\psi_j|}$$

Equivalently,

<!-- source_pdf_page: 2422 -->

ΔG = 2 Δ ln ∣ψ∣.

But primitive R2D already gives

$$\Delta G=\Delta\tau+\Delta A$$

Therefore, within a fixed quantum measurement mapping,

$$2\Delta\ln|\psi|=\Delta\tau+\Delta A$$

This is a new bridge between quantum amplitude magnitude and the primitive R2D realization law.

The amplitude magnitude is the half-logarithmic physical representation of realized occupancy.

The full phase-carrying quantum coordinate can therefore be written schematically as

$$\psi_i\propto e^{G_i/2+i\phi_i}$$

The two parts have distinct origins:

$$ G_i/2$$

comes from normalized realized support,

while

$$\phi_i$$

comes from recurrent closure.

Thus the quantum amplitude joins two R2D coordinates that must not be conflated:

> realized occupancy magnitude + closure phase.

The central statement is therefore:

the Born rule does not primitively convert a mysterious complex amplitude into probability.
A measurement boundary first produces mutually exclusive realized occupancy counts. Normalization gives
an additive boundary measure. When boundary-native recurrence is represented in a complex inner-
 product state space and detector alternatives are represented by orthogonal classifications, a normalized
 classification-independent additive measure has the quantum form $\mu_\rho(P)=\operatorname{Tr}(\rho P)$. For a pure state and rank-one
 detector outcome this becomes $\mu_i=|\langle i|\psi\rangle|^2$. The square-root occupancy amplitude therefore follows from the
> Born measure rather than being assumed to produce it.

And hence:

<!-- source_pdf_page: 2423 -->

normalized realization occurs before the Born rule.

## 1. Measurement Begins With a New Boundary

Let

$$ B_M$$

be a realized measurement boundary.

The detector defines readable macrostates

$$\mathcal M_M=\{i\}$$

## 2. The Detector Does Not Recover the Replaced Subordinate Path

The quantum-side recurrence arrives at the measurement boundary.

The detector creates a new enclosing distinction.

The missing subordinate trajectory is not restored.

This is already part of the R2D measurement architecture.

## 3. Measurement Is Therefore a Realization Event

For outcome i, the detector realizes macrostate

$$ i$$

Across equivalent realizations, count those occurrences.

## 4. Define Detector Occupancy

Let

$$ c_i$$

be the realized count of detector outcome i.

<!-- source_pdf_page: 2424 -->

This is ordinary R2D occupancy.

## 5. Total Realization Count Is

$$ C=\sum_i c_i$$

No probability has yet been introduced.

## 6. Normalize the Realization Count

Define

$$\mu_i=\frac{c_i}{C}$$

Then:

$$0\le\mu_i\le1$$

## 7. Exhaustive Classification Gives

$$\sum_i\mu_i=1$$

This is normalized count.

## 8. Probability Comes Later

The physical probability read will eventually be identified with

$$\mu_i$$

But the primitive R2D object is the count ratio.

## 9. Mutually Exclusive Detector Macrostates Add

If outcomes i and j are distinct readable macrostates, a single realization cannot occupy both
simultaneously within that classification.

<!-- source_pdf_page: 2425 -->

## 10. Grouping Outcomes Gives

$$ c_{i\lor j}=c_i+c_j$$

## 11. Therefore Normalized Measure Is Additive

$$\mu_{i\lor j}=\mu_i+\mu_j$$

This follows directly from counting.

## 12. Additivity Is Not a Quantum Postulate

It is the count relation inherited by the quantum measurement projection.

## 13. Addendum 72 Supplies the Phase Representation

Boundary-native recurrent closure gives cyclic phase classes

$$\chi_m(j)=e^{i2\pi mj/K}$$

## 14. These Classes Are Orthogonal

$$\frac1K\sum_{j=0}^{K-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

Thus complex orthogonality arises naturally from closure.

## 15. Complex Functions on Closure Form an Inner-Product Space

Let

$$\mathcal H_K=\{g:C_K\to\mathbb C\}$$

Define

<!-- source_pdf_page: 2426 -->

$$\langle g,h\rangle=\frac1K\sum_jg^*(j)h(j)$$

## 16. This Is Mathematically a Finite Complex Hilbert Space

The important R2D question is not whether such a space exists mathematically.

It is whether physical quantum state representation inherits this closure structure.

## 17. The Closure Characters Form an Orthonormal Basis

$$\{\chi_m\}$$

Therefore any closure function admits

$$ g=\sum_m\widetilde g_m\chi_m$$

## 18. Parseval Preserves the Quadratic Measure

For the discrete closure transform,

$$\frac1K\sum_j|g(j)|^2=\sum_m|\widetilde g_m|^2$$

The quadratic norm is invariant between the closure-position and closure-character descriptions.

## 19. This Is a Major Clue

A complex closure representation already carries a basis-independent quadratic measure.

Quantum mechanics later uses precisely such a measure.

## 20. But Parseval Alone Is Not the Born Rule

R2D still must identify the preserved quadratic state measure with normalized realized detector support.

That is the physical bridge addressed here.

<!-- source_pdf_page: 2427 -->

## 21. Represent Complete Detector Classifications by Orthogonal Projectors

Let outcome i correspond to

$$\{P_i\}$$

For mutually exclusive outcomes,

$$ P_iP_j=0\quad(i\ne j)$$

## 22. Exhaustiveness Gives

$$\sum_iP_i=I$$

## 23. Grouping Orthogonal Detector Alternatives Gives

$$ P_{i\lor j}=P_i+P_j$$

This mirrors count grouping.

## 24. Therefore the Quantum Measure Must Obey

$$\mu(P_i+P_j)=\mu(P_i)+\mu(P_j)$$

whenever

$$ P_iP_j=0$$

## 25. Complete Classification Requires

$$\mu(I)=1$$

<!-- source_pdf_page: 2428 -->

## 26. Measures Must Be Nonnegative

Because realized counts satisfy

$$ c_i\ge0$$

$$\mu(P)\ge0$$

## 27. One More Requirement Is Needed

A given physical detector alternative must possess the same measure whenever that same alternative
appears inside different complete classifications.

## 28. Define the Measure Relative to the Incoming Quantum State

Write

$$\mu_\Psi(P)$$

This is the normalized realization measure assigned to physical detector alternative P given quantum state
relation Ψ.

## 29. The Same P Must Mean the Same Physical Alternative

If the apparatus changes in a way that changes the physical detector alternative, then the projector has
changed.

There is no requirement that the measure remain the same.

## 30. The Relevant Noncontextuality Is Therefore Limited

R2D requires only:

> same physical P → same μΨ (P ).

It does not posit hidden predetermined outcomes independent of measurement boundary.

<!-- source_pdf_page: 2429 -->

## 31. This Requirement Follows From Boundary Ownership

The realized measure belongs to the boundary-defined alternative itself.

It should not depend on arbitrary decomposition of the remainder of the detector classification.

## 32. We Now Have a Measure on Quantum Alternatives

The required properties are:

$$\mu(P)\ge0$$

$$\mu(I)=1$$

and

$$ P_iP_j=0\Rightarrow\mu(P_i+P_j)=\mu(P_i)+\mu(P_j)$$

## 33. In Complex Hilbert Dimension at Least Three, This Measure Is Fixed in Form

The standard measure theorem then requires

$$\mu_\rho(P)=\operatorname{Tr}(\rho P)$$

for a positive trace-one operator ρ.

## 34. Thus

$$\rho\ge0$$

and

$$\operatorname{Tr}\rho=1$$

## 35. The Density Operator Is Not Introduced as Primitive Matter

It is the quantum representation of a normalized realization measure across possible detector
classifications.

<!-- source_pdf_page: 2430 -->

## 36. Mixed States Fit Naturally

Nothing in the measure theorem requires

$$\rho$$

to be rank one.

Thus the density-operator form is more general than the pure-state Born rule.

## 37. A Pure Quantum State Has

$$\rho_\psi=|\psi\rangle\langle\psi|$$

## 38. A Rank-One Detector Outcome Has

$$ P_i=|i\rangle\langle i|$$

## 39. Substitute These Into the Measure

$$\mu_i=\operatorname{Tr}(|\psi\rangle\langle\psi|\,|i\rangle\langle i|)$$

## 40. Therefore

$$\mu_i=|\langle i|\psi\rangle|^2$$

This is the Born rule.

## 41. Return to the Primitive Count

Because

$$\mu_i=\frac{c_i}{C}$$

we obtain

<!-- source_pdf_page: 2431 -->

$$\frac{c_i}{C}=|\langle i|\psi\rangle|^2$$

## 42. Thus Probability Is a Later Read of Normalized Realization

The R2D ordering is

$$ c_i\to\frac{c_i}{C}\to p_i$$

Probability does not precede occurrence.

## 43. This Reverses the Existing Candidate Construction

One might begin by assuming

$$\widetilde\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

and then observe that

$$|\psi_i|^2=c_i$$

That algebra is correct but does not explain the square root.

## 44. The Correct R2D Order Is

> count measure → Born form → square-root amplitude.

## 45. In a Detector Basis

$$\psi_i=\langle i|\psi\rangle$$

Therefore:

$$|\psi_i|^2=\frac{c_i}{C}$$

<!-- source_pdf_page: 2432 -->

## 46. Hence

$$|\psi_i|=\sqrt{\frac{c_i}{C}}$$

The square root has now been earned.

## 47. Add Closure Phase

From Addendum 72, alternative i carries cyclic recurrence phase

$$\phi_i$$

Therefore:

$$\psi_i=\sqrt{\frac{c_i}{C}}\,e^{i\phi_i}$$

## 48. The Unnormalized Count Coordinate Is

$$\widetilde\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

Then:

$$|\widetilde\psi_i|^2=c_i$$

## 49. The Normalization Factor Is Global

Since

$$ C=\sum_i c_i$$

$$\psi_i=\frac{\widetilde\psi_i}{\sqrt C}$$

## 50. The Amplitude Therefore Has Two Different R2D Inputs

Magnitude:

<!-- source_pdf_page: 2433 -->

∣ψi ∣ ↔ normalized realized support.

Phase:

> eiϕi ↔ boundary-native recurrent closure.

## 51. The Quantum Amplitude Is Their Joint Coordinate

> ψi = realization magnitude × closure phase.

Neither factor should be substituted for the other.

## 52. Global Phase Cannot Alter Detector Count

Let

$$|\psi\rangle\to e^{i\alpha}|\psi\rangle$$

Then:

$$|\langle i|e^{i\alpha}\psi\rangle|^2=|\langle i|\psi\rangle|^2$$

## 53. The Density Operator Makes This Explicit

$$\rho_\psi=|\psi\rangle\langle\psi|$$

Under global phase,

$$\rho_\psi\to e^{i\alpha}|\psi\rangle\langle\psi|e^{-i\alpha}$$

Therefore:

$$\rho_\psi\to\rho_\psi$$

## 54. The Quadratic Read Removes Absolute Phase

This is exactly what a count measure must do.

Detector count cannot depend on an arbitrary phase-zero convention.

<!-- source_pdf_page: 2434 -->

## 55. But Relative Phase Remains

For components

$$\psi_i=A_ie^{i\phi_i}$$

relative phase

$$\phi_i-\phi_j$$

is preserved.

Thus the quadratic construction removes global phase while retaining relational phase.

## 56. This Explains Why Squaring Does Not Destroy Quantum Phase Physics

The Born measure is phase independent only for a single isolated component.

When amplitudes combine coherently, relative phase changes the combined magnitude.

## 57. Consider Two Coherent Contributions to One Detector Alternative

Let

$$\psi=\psi_a+\psi_b$$

Then:

$$|\psi|^2=|\psi_a|^2+|\psi_b|^2+2\operatorname{Re}(\psi_a^*\psi_b)$$

## 58. Writing

$$\psi_a=A_ae^{i\phi_a}$$

and

$$\psi_b=A_be^{i\phi_b}$$

gives

<!-- source_pdf_page: 2435 -->

∣ψ∣2 = A2a + A2b + 2Aa Ab cos(ϕb − ϕa ).

## 59. The Cross Term Is a Closure-Phase Relation

$$2A_aA_b\cos\Delta\phi$$

Thus phase affects realized count when several unresolved recurrence relations feed the same detector
alternative.

## 60. This Is Not Count Additivity Between Distinct Detector Macrostates

If a and b are genuinely distinct detector outcomes, their projectors are orthogonal and their realized
measures add.

## 61. Coherent Paths Are Different

If the detector does not define a and b as separate macrostates, they are not separate realized detector
counts at that boundary.

Their phase-carrying coordinates combine before detector realization.

## 62. This Provides the R2D Boundary Distinction Behind Interference

> distinguishable alternatives → count addition,

whereas

> unreplaced coherent alternatives feeding one outcome → phase-amplitude addition.

The full derivation of linear amplitude addition remains a separate burden, but the boundary distinction is
now clear.

## 63. Which-Path Measurement Changes the Count Domain

If a detector creates distinct readable path macrostates, the alternatives acquire separate boundary
identity.

<!-- source_pdf_page: 2436 -->

Their projectors become orthogonal detector alternatives.

## 64. The Interference Term Then Belongs to a Different Classification

The measurement boundary has changed.

R2D does not need to imagine a pre-existing classical path suddenly being disturbed into quantum
randomness.

## 65. Return to the Primitive Occupancy Coordinate

R2D defines

$$ G_i=\ln c_i$$

## 66. Born Gives

$$ c_i=C|\psi_i|^2$$

Therefore:

$$ G_i=\ln C+2\ln|\psi_i|$$

## 67. Thus

$$ G_i-\ln C=2\ln|\psi_i|$$

The normalized logarithmic occupancy is twice the logarithmic amplitude magnitude.

## 68. Between Two Alternatives

$$ G_i-G_j=2\ln\frac{|\psi_i|}{|\psi_j|}$$

<!-- source_pdf_page: 2437 -->

## 69. For an Occupancy Change

$$\Delta G=2\Delta\ln|\psi|$$

## 70. Primitive R2D Gives

$$\Delta G=\Delta\tau+\Delta A$$

## 71. Therefore

$$2\Delta\ln|\psi|=\Delta\tau+\Delta A$$

This is a direct bridge from quantum amplitude magnitude to R2D realization.

## 72. Equivalently

$$\Delta\ln|\psi|=\frac12(\Delta\tau+\Delta A)$$

## 73. Thus Amplitude Magnitude Is Not Primitive Probability

It is the physical square-root coordinate of realized occupancy.

## 74. The Full Complex Coordinate Becomes

$$\psi_i\propto e^{G_i/2+i\phi_i}$$

## 75. The Real and Imaginary Contributions Have Different Origins

The real logarithmic magnitude

$$ G_i/2$$

encodes realized support.

The imaginary coordinate

<!-- source_pdf_page: 2438 -->

ϕi

encodes cyclic closure.

## 76. Their Combination Is the Quantum Projection

> occupancy + recurrence → complex amplitude.

This is much more precise than treating ψ as a primitive object.

## 77. The Standard Gleason Theorem Has a Dimensional Qualification

The projector-measure theorem stated above applies directly for complex Hilbert dimension

$$ d\ge3$$

## 78. Two-Dimensional Quantum Systems Require Additional Care

A pure two-dimensional projector space admits measures not excluded by the original theorem.

This matters for systems such as spin- 12 .

## 79. Generalized Measurement Structure Resolves the Mathematical Gap

When physically allowed measurement effects are enlarged beyond rank-one projectors to generalized
positive measurement operators, the density-operator form extends to dimension two.

## 80. R2D Has a Natural Reason to Expect Generalized Measurements

A real detector is itself an enclosing boundary with finite physical compatibility and need not correspond
only to ideal rank-one projective classification.

Thus generalized detector effects are physically natural rather than mathematical patches.

<!-- source_pdf_page: 2439 -->

## 81. But the Two-Dimensional Case Should Remain Explicit

The full R2D Born derivation requires a precise theorem covering the measurement structures admitted by
the boundary architecture.

This should not be hidden behind notation.

## 82. Principle — Realization Precedes Probability

A detector first realizes countable outcomes.

Probability is the normalized physical read of those realized counts.

$$ c_i\to\mu_i\to p_i$$

## 83. Principle — Mutually Exclusive Realization Is Additive

$$ c_{i\lor j}=c_i+c_j$$

Therefore:

$$\mu_{i\lor j}=\mu_i+\mu_j$$

## 84. Principle — Orthogonal Projectors Are the Quantum Read of Exclusive Detector Alternatives

$$ P_iP_j=0$$

represents mutually exclusive alternatives within one complete quantum classification.

## 85. Principle — Count Additivity Becomes Projector Additivity

$$\mu(P_i+P_j)=\mu(P_i)+\mu(P_j)$$

## 86. Principle — Complete Realization Is Normalized

$$\mu(I)=1$$

<!-- source_pdf_page: 2440 -->

## 87. Principle — The Same Boundary Alternative Has the Same Measure

If the physical projector P is unchanged, its normalized realization measure is independent of which other
alternatives complete the classification.

## 88. Principle — The Quantum Measure Has Density-Operator Form

Under the stated complex-state-space assumptions,

$$\mu_\rho(P)=\operatorname{Tr}(\rho P)$$

## 89. Principle — The Born Rule Is the Pure-State Rank-One Limit

$$\rho=|\psi\rangle\langle\psi|$$

$$ P_i=|i\rangle\langle i|$$

therefore:

$$\mu_i=|\langle i|\psi\rangle|^2$$

## 90. Principle — Square-Root Amplitude Follows From Realized Count

$$|\psi_i|=\sqrt{\frac{c_i}{C}}$$

The square root is not assumed before the Born measure.

## 91. Principle — Phase and Magnitude Have Different Primitive Sources

$$\psi_i=\sqrt{\frac{c_i}{C}}\,e^{i\phi_i}$$

Here:

<!-- source_pdf_page: 2441 -->

ci → realization magnitude,

while

> ϕi → closure phase.

## 92. Principle — Born Weight Is Global-Phase Invariant

$$|\psi\rangle\to e^{i\alpha}|\psi\rangle$$

leaves

$$\mu(P)$$

unchanged.

## 93. Principle — Relative Phase Remains Physically Consequential

Coherent amplitude composition retains

$$\Delta\phi$$

Thus the Born construction eliminates arbitrary absolute phase without eliminating physical phase relation.

## 94. Principle — Distinguishable Counts Add; Coherent Coordinates Interfere

When a measurement boundary distinguishes alternatives, realized measures add.

When the boundary does not distinguish their subordinate paths, phase-carrying coordinates may combine
before realization.

This is the boundary distinction underlying interference.

## 95. Principle — Quantum Amplitude Is a Projection Coordinate

The amplitude is not a primitive count.

It combines:

<!-- source_pdf_page: 2442 -->

square-root realization magnitude

with

> closure phase.

## 96. Logical Status

Canonical R2D

Occupancy is realized count:

$$ c_i$$

Logarithmic occupancy is

$$ G_i=\ln c_i$$

Distinct detector macrostates are mutually exclusive within one classification.

Prior Measurement Result

Measurement creates a new enclosing readable distinction rather than recovering the replaced subordinate
path.

Addendum 72

Boundary-native closure supplies complex cyclic phase and natural orthogonality.

New Primitive Measurement Relation

$$\mu_i=\frac{c_i}{\sum_jc_j}$$

New Additivity Relation

$$\mu(P_i+P_j)=\mu(P_i)+\mu(P_j)$$

for orthogonal detector alternatives.

Conditional Quantum Measure Theorem

Given a complex Hilbert representation, normalized nonnegative additive classification-independent
measures satisfy

<!-- source_pdf_page: 2443 -->

μ(P ) = Tr(ρP ).

Pure-State Born Rule

$$\mu_i=|\langle i|\psi\rangle|^2$$

Derived Amplitude Magnitude

$$|\psi_i|=\sqrt{\frac{c_i}{C}}$$

New R2D–Amplitude Bridge

$$2\Delta\ln|\psi|=\Delta G=\Delta\tau+\Delta A$$

Not Yet Established

This addendum does not yet derive from primitive R2D alone:

- the full physical Hilbert-space representation;
- why every admissible detector classification corresponds to an orthogonal projector decomposition;
- linear superposition of arbitrary quantum alternatives;
- the most general allowed measurement-effect space;
- unitarity of time evolution;
- tensor-product composition of joint boundaries;
- or the complete spin- 12 dimension-two Born structure.

These are now sharply defined remaining bridges rather than unexplained probability postulates.

## 97. The Complete Born Architecture

A quantum-side recurrence arrives at a detector boundary:

> quantum recurrence.

The detector creates mutually exclusive readable macrostates:

$$\downarrow$$

$$\{i\}$$

Repeated realization produces occupancy counts:

$$\downarrow$$

$$ c_i$$

<!-- source_pdf_page: 2444 -->

Normalize:

$$\mu_i=\frac{c_i}{C}$$

Mutual exclusivity gives additivity:

$$\downarrow$$

$$\mu(P_i+P_j)=\mu(P_i)+\mu(P_j)$$

Closure supplies complex phase geometry:

$$\downarrow$$

$$\mathcal H$$

Classification consistency then gives the quantum measure:

$$\downarrow$$

$$\mu_\rho(P)=\operatorname{Tr}(\rho P)$$

For a pure state:

$$\downarrow$$

$$\rho_\psi=|\psi\rangle\langle\psi|$$

For outcome i:

$$\downarrow$$

$$\mu_i=|\langle i|\psi\rangle|^2$$

Therefore:

$$\downarrow$$

$$|\psi_i|=\sqrt{\frac{c_i}{C}}$$

With closure phase:

$$\downarrow$$

<!-- source_pdf_page: 2445 -->

ci iϕi

$$\psi_i=\sqrt{\frac{c_i}{C}}\,e^{i\phi_i}$$

Thus:

> realized count → normalized measure → Born measure → complex amplitude.

## 98. Conclusion

The Born rule is usually introduced at the point where quantum mathematics meets observation.

A complex amplitude is given.

Its squared magnitude is declared to be a probability.

The rule works.

But the square itself remains primitive.

R2D reverses the explanatory order.

A measurement boundary first creates a readable distinction.

Across equivalent realizations, that distinction can be counted.

For detector outcome i,

$$ c_i$$

is the realized occupancy.

The complete detector classification has total occupancy

$$ C=\sum_i c_i$$

Normalization therefore gives

$$\mu_i=\frac{c_i}{C}$$

This is not yet quantum probability.

It is normalized realization.

<!-- source_pdf_page: 2446 -->

Mutually exclusive detector alternatives obey ordinary count additivity:

$$ c_{i\lor j}=c_i+c_j$$

Therefore:

$$\mu_{i\lor j}=\mu_i+\mu_j$$

Addendum 72 independently showed why boundary-native recurrent closure possesses a natural complex
phase representation and why distinct closure characters are orthogonal.

Once those recurrence states are represented through a complex inner-product space, a complete detector
classification is represented by mutually orthogonal alternatives.

The primitive count law then becomes an additive measure over orthogonal projectors.

If the same physical detector alternative carries the same normalized realization measure regardless of
which other alternatives complete the classification, the measure has the quantum form

$$\mu_\rho(P)=\operatorname{Tr}(\rho P)$$

For a pure state and a rank-one detector outcome,

$$\mu_i=|\langle i|\psi\rangle|^2$$

The Born rule therefore appears not as a primitive probability axiom but as the quantum representation of
normalized additive boundary realization.

Only then does the familiar amplitude magnitude follow:

$$|\psi_i|=\sqrt{\frac{c_i}{C}}$$

Closure phase supplies

$$ e^{i\phi_i}$$

so the quantum coordinate becomes

$$\psi_i=\sqrt{\frac{c_i}{C}}\,e^{i\phi_i}$$

The square root is no longer guessed.

It is required because the complex quantum coordinate carries a quadratic normalized realization measure.

<!-- source_pdf_page: 2447 -->

This also explains why global phase disappears from observed count while relative phase remains physically
consequential.

The operator

$$|\psi\rangle\langle\psi|$$

is invariant under

$$|\psi\rangle\to e^{i\alpha}|\psi\rangle$$

but coherent combinations retain relative phase through interference terms.

The Born construction therefore performs exactly the operation the R2D architecture requires:

> preserve recurrence relation

while

> extracting phase-independent realized count.

Finally, the result connects quantum amplitude directly to the primitive realization law.

Because

$$ G_i=\ln c_i$$

and

$$ c_i=C|\psi_i|^2$$

one obtains

$$\Delta G=2\Delta\ln|\psi|$$

Since R2D gives

$$\Delta G=\Delta\tau+\Delta A$$

the amplitude magnitude satisfies

$$2\Delta\ln|\psi|=\Delta\tau+\Delta A$$

Thus the quantum amplitude is no longer a detached mathematical object.

Its phase is the physical representation of recurrent closure.

<!-- source_pdf_page: 2448 -->

Its magnitude is the square-root representation of normalized realized occupancy.

The central statement is therefore:

 the Born rule does not primitively convert complex amplitude into probability. A detector
boundary first produces realized occupancy. Normalization gives an additive count measure. Closure
supplies the complex phase geometry in which quantum alternatives are represented. When that
 normalized count measure is required to remain additive and classification-consistent across orthogonal
detector alternatives, it acquires the quantum form $\mu_\rho(P)=\operatorname{Tr}(\rho P)$. The familiar rule $\mu_i=|\langle i|\psi\rangle|^2$ follows, and the
> square-root occupancy amplitude follows afterward.

And hence:

normalized realization occurs before the Born rule.
