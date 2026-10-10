---
r2d_id: addendum-078
title: Addendum 78 — Local Phase Comparison Occurs Before Electromagnetic Minimal Coupling
subtitle: Gauge Connection, Retained Charge Orientation, and the Origin of the Electromagnetic Schrödinger Equation
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 78
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2563
pdf_page_end: 2592
math_representation: LaTeX for normalized equations; source PDF layout text retained for remaining equations
equation_status: candidate_visual_reconstruction_pending_author_review
equation_audit_scope: archived_pdf_visual_comparison; author_review_pending
primitive_authority: false
review_status: author_reviewed
semantic_sync: 2026-09-25-boundary-ordering-and-conditional-bridges-preserved
machine_revision: 2026-10-09-equation-reconstruction-v1
qa_status: standalone_render_pass_full_book_pending
promotion_date: null
equation_source_conflict_rule: publication_pdf_controls
---

# Addendum 78 — Local Phase Comparison Occurs Before Electromagnetic Minimal Coupling

*Gauge Connection, Retained Charge Orientation, and the Origin of the Electromagnetic Schrödinger Equation*

## Abstract

<!-- source_pdf_page: 2563 -->

The preceding quantum addenda have constructed the nonrelativistic Schrödinger architecture without
beginning from particle ontology.

Addendum 72 derived complex phase from boundary-native recurrent closure.

Addendum 73 connected normalized detector realization to the Born measure.

Addendum 74 derived unitary evolution from preservation of quantum realization relations under
boundary-preserving recurrence.

Addendum 75 derived

$$ P=-i\hbar\nabla$$

as the physical momentum read of continuous spatial translation.

Addendum 76 derived the free spatial Schrödinger equation as the slow residual dynamics of persistent
mass recurrence.

Addendum 77 identified a scalar potential as the energetic read of an enclosing constraint-induced
temporal phase bias.

Electromagnetic coupling introduces a further problem.

Closure phase has no primitive absolute zero.

A quantum state may therefore be rephased globally without changing its physical realization relations.

If that freedom is allowed to vary locally,

$$\chi=\chi(x,t)$$

neighboring phase coordinates may use different reference origins.

Ordinary differentiation then mixes two distinct quantities:

<!-- source_pdf_page: 2564 -->

physical recurrence change

and

> change of local phase reference.

The existing R2D gauge development already identified this comparison problem: global phase freedom
creates no difficulty, but local phase-reference freedom makes ordinary derivatives unable to separate
physical variation from variation of the coordinate reference.

A connection is therefore required.

For a charge-bearing state, write the local phase-reference transformation as

$$ \psi\prime(x,t)=e^{iq\chi(x,t)/\hbar}\psi(x,t). $$

Here q is not introduced as a primitive substance.

R2D has already assigned charge the physical form

$$ q=\sigma|q|,\qquad\sigma=\pm1, $$

where σ records an orientation distinction that survives recursive replacement and ∣q∣ gives the physical
coupling magnitude.

Because the symbol A is already reserved in R2D for asymmetry,

$$ A=P-R$$

denote the electromagnetic vector potential explicitly by

$$\mathbf A_{\mathrm{EM}}$$

and the electromagnetic scalar potential by

$$\Phi_{\mathrm{EM}}$$

Require the local reference transformation

$$ A_{\mathrm{EM}}\prime=A_{\mathrm{EM}}+\nabla\chi, $$

and

$$\Phi'_{\mathrm{EM}}=\Phi_{\mathrm{EM}}-\partial_t\chi$$

Define the spatial and temporal covariant derivatives

<!-- source_pdf_page: 2565 -->

$$ \mathbf D=\nabla-\frac{iq}{\hbar}\mathbf A_{\mathrm{EM}}, $$

and

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

Then

$$ D'\psi'=e^{iq\chi/\hbar}D\psi$$

and

$$ D'_t\psi'=e^{iq\chi/\hbar}D_t\psi$$

The connection therefore restores comparison among locally different phase coordinates without changing
the underlying physical closure relation.

This reverses the usual explanatory order.

Gauge connection does not create invariance.

The prior R2D development already states the ordering

> counting invariance → closure invariance → gauge invariance.

A gauge transformation changes the representation rather than producing a new R2D occurrence.

Addendum 75 now converts the spatial covariant derivative directly into mechanical momentum.

Define

$$ \boldsymbol\Pi\equiv-i\hbar\mathbf D. $$

Then

$$\Pi=-i\hbar\nabla-q\mathbf A_{\mathrm{EM}}$$

Since

$$ P_{\mathrm{can}}=-i\hbar\nabla$$

one obtains

$$ \boldsymbol\Pi=\mathbf P_{\mathrm{can}}-q\mathbf A_{\mathrm{EM}}. $$

<!-- source_pdf_page: 2566 -->

Thus electromagnetic minimal coupling is not introduced as the substitution

$$ p\to p-q\mathbf A$$

by fiat.

It follows because local phase comparison requires the spatial derivative to become covariant.

Likewise,

$$ i\hbar D_t=i\hbar\partial_t-q\Phi_{\mathrm{EM}}. $$

The free residual Schrödinger equation written covariantly is

$$ i\hbar D_t\psi=-\frac{\hbar^2}{2m}D^2\psi. $$

Expanding gives

$$ i\hbar\frac{\partial\psi}{\partial t}-q\Phi_{\mathrm{EM}}\psi=\frac{(-i\hbar\nabla-q\mathbf A_{\mathrm{EM}})^2}{2m}\psi$$

Therefore:

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[\frac{(-i\hbar\nabla-q\mathbf A_{\mathrm{EM}})^2}{2m}+q\Phi_{\mathrm{EM}}\right]\psi$$

This is the nonrelativistic electromagnetic Schrödinger equation.

Its two electromagnetic terms are not independent additions.

They are the spatial and temporal components of one local phase-comparison connection.

The scalar electromagnetic energy read is

$$ V_{\mathrm{EM}}=q\Phi_{\mathrm{EM}}, $$

while the mechanical momentum read is

$$\Pi=P_{\mathrm{can}}-q\mathbf A_{\mathrm{EM}}$$

Thus:

$$\text{local phase-reference freedom}\to\text{connection}\to\{q\Phi_{\mathrm{EM}},q\mathbf A_{\mathrm{EM}}\}$$

The phase itself makes the invariant structure particularly clear.

<!-- source_pdf_page: 2567 -->

Write

$$\psi=|\psi|e^{i\phi}$$

Under local rephasing,

$$\phi'=\phi+\frac{q}{\hbar}\chi$$

Therefore:

$$\hbar\nabla\phi'=\hbar\nabla\phi+q\nabla\chi$$

Since

$$\mathbf A'_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}+\nabla\chi$$

the combination

$$ p_{\mathrm{mech}}=\hbar\nabla\phi-qA_{\mathrm{EM}} $$

is invariant.

Similarly,

$$-\hbar\partial_t\phi'=-\hbar\partial_t\phi-q\partial_t\chi$$

while

$$ q\Phi'_{\mathrm{EM}}=q\Phi_{\mathrm{EM}}-q\partial_t\chi$$

Hence:

$$-\hbar\partial_t\phi-q\Phi_{\mathrm{EM}}$$

is invariant.

The most compact expression uses the electromagnetic connection one-form

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

Under local rephasing,

$$\mathcal A'_{\mathrm{EM}}=\mathcal A_{\mathrm{EM}}+d\chi$$

Then the combination

<!-- source_pdf_page: 2568 -->

$$ d\phi_{\mathrm{rel}}=d\phi-\frac{q}{\hbar}\mathcal A_{\mathrm{EM}} $$

is invariant:

$$ d\phi_{\mathrm{rel}}\prime=d\phi_{\mathrm{rel}}. $$

This is the central geometric relation of the addendum.

The physically comparable phase change is not the coordinate differential dϕ alone.

It is the phase differential after correction for local reference variation.

Electromagnetic minimal coupling is therefore the physical rule for comparing closure phase across locally
different representations.

Charge determines how strongly and in which orientation the state couples to that comparison rule.

For the same connection,

$$ q>0$$

and

$$ q<0$$

produce opposite phase rotations.

This is exactly the physical behavior expected from the prior R2D interpretation of charge as retained
orientation-sensitive coupling. The earlier gauge analysis already identified charge sign as the orientation
of coupling to the gauge connection and charge magnitude as its strength.

The gauge potential itself is not the invariant physical relation.

The previous R2D gauge treatment correctly distinguishes the reference-dependent connection

$$\mathbf A_{\mathrm{EM}}$$

from its reference-independent curvature.

That curvature will be developed separately.

The Aharonov–Bohm effect nevertheless shows why the connection is physically consequential even though
its local coordinate value is gauge dependent.

For a closed spatial path,

<!-- source_pdf_page: 2569 -->

q

$$\Delta\phi_{AB}=\frac{q}{\hbar}\oint_C\mathbf A_{\mathrm{EM}}\cdot d\mathbf l$$

Under

$$\mathbf A_{\mathrm{EM}}\to\mathbf A_{\mathrm{EM}}+\nabla\chi$$

the additional contribution is

$$\oint_C\nabla\chi\cdot d\mathbf l=0$$

Thus the closed-loop phase relation is gauge invariant.

The earlier R2D gauge development already identified this as particularly suggestive: local connection
coordinates may vary while the closed relational phase remains physically meaningful, though a Wilson
loop should not be identified term-by-term with primitive R2D closure.

The central statement is therefore:

a quantum closure possesses phase before it possesses an electromagnetic gauge
potential. Because absolute phase zero is not primitive, equivalent representations may use different phase
references. When that reference freedom varies locally, ordinary derivatives mix physical recurrence change
with reference change. A connection is therefore required to compare neighboring phase reads. For a
charge-bearing boundary with retained oriented coupling $q=\sigma|q|$, covariance supplies the temporal and
spatial connection corrections $i\hbar D_t=i\hbar\partial_t-q\Phi_{\mathrm{EM}}$ and $\boldsymbol\Pi=\mathbf P_{\mathrm{can}}-q\mathbf A_{\mathrm{EM}}$, yielding the standard electromagnetic minimal-coupling
 Hamiltonian. Gauge coupling is therefore the projected rule for preserving relational closure phase across
> locally different representations, not the primitive source of the invariant state.

And hence:

> local phase comparison occurs before electromagnetic minimal coupling.

## 1. Closure Phase Already Exists Before Electromagnetism

Addendum 72 established

$$\text{closure}\to\text{phase}$$

A boundary-native recurrence can therefore possess

$$\phi$$

without yet being assigned electromagnetic coupling.

<!-- source_pdf_page: 2570 -->

## 2. Absolute Phase Zero Is Not Primitive

For a global phase shift

$$\phi\to\phi+\alpha$$

relative phase differences remain unchanged.

## 3. The Quantum State Therefore Has Global Phase Freedom

$$\psi\to e^{i\alpha}\psi$$

Born realization measures remain unchanged.

## 4. This Freedom Comes From Closure Reference

A closed cycle has no primitive distinguished point that must be called

$$\phi=0$$

The recurrence relation is physical.

The absolute phase label is representational.

## 5. Gauge Freedom Is Not Background Change

A change of physical background can change occupancy, recurrence, or asymmetry.

A gauge change can leave the physical state unchanged.

The two must remain distinct.

## 6. Gauge Transformation Is Not an R2D Occurrence

It need not represent:

- macrostate transition;
- occupancy change;
- closure;
- recursive carry;

<!-- source_pdf_page: 2571 -->

• or background change.

It can alter only the physical mathematical representation.

## 7. Local Phase Freedom Is Stronger Than Global Freedom

Now let the phase reference vary:

$$\chi=\chi(x,t)$$

## 8. For a Charge-Bearing State Write

$$\psi'=e^{iq\chi/\hbar}\psi$$

The normalization convention assigns the physical coupling q to the phase representation.

## 9. Differentiate Spatially

$$\nabla\psi'=\nabla(e^{iq\chi/\hbar}\psi)$$

Therefore:

$$\nabla\psi'=e^{iq\chi/\hbar}\left[\nabla\psi+\frac{iq}{\hbar}(\nabla\chi)\psi\right]$$

## 10. The Additional Term Is Reference Dependent

$$\frac{iq}{\hbar}(\nabla\chi)\psi$$

It appears even though the underlying physical state may be unchanged.

## 11. Ordinary Spatial Differentiation Has Become Ambiguous

It now mixes:

> physical spatial phase change

with

<!-- source_pdf_page: 2572 -->

change of phase reference.

## 12. Differentiate Temporally

$$\partial_t\psi'=e^{iq\chi/\hbar}\left[\partial_t\psi+\frac{iq}{\hbar}(\partial_t\chi)\psi\right]$$

## 13. Temporal Differentiation Has the Same Problem

The additional term

$$\frac{iq}{\hbar}(\partial_t\chi)\psi$$

is not necessarily physical recurrence change.

It can arise from reference choice.

## 14. Local Comparison Therefore Requires Additional Structure

A physical derivative must compare neighboring state representations while compensating for the local
reference change.

## 15. This Structure Is the Gauge Connection

Introduce:

$$\mathbf A_{\mathrm{EM}}$$

and

$$\Phi_{\mathrm{EM}}$$

## 16. The Notation Must Remain Distinct From R2D Asymmetry

R2D reserves

$$ A=P-R$$

<!-- source_pdf_page: 2573 -->

for asymmetry.

Therefore this addendum writes the electromagnetic vector potential explicitly as

$$\mathbf A_{\mathrm{EM}}$$

## 17. Let the Spatial Connection Transform As

$$\mathbf A'_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}+\nabla\chi$$

## 18. Let the Temporal Connection Transform As

$$\Phi'_{\mathrm{EM}}=\Phi_{\mathrm{EM}}-\partial_t\chi$$

## 19. Define the Spatial Covariant Derivative

$$ D=\nabla-\frac{iq}{\hbar}\mathbf A_{\mathrm{EM}}$$

## 20. Transform It

$$ D'\psi'=\left[\nabla-\frac{iq}{\hbar}\mathbf A'_{\mathrm{EM}}\right]e^{iq\chi/\hbar}\psi$$

## 21. The Reference Terms Cancel

Substitution gives

$$ D'\psi'=e^{iq\chi/\hbar}D\psi$$

The derivative transforms like the state itself.

## 22. Define the Temporal Covariant Derivative

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

<!-- source_pdf_page: 2574 -->

## 23. Transform It

Using

$$\Phi'_{\mathrm{EM}}=\Phi_{\mathrm{EM}}-\partial_t\chi$$

one obtains

$$ D'_t\psi'=e^{iq\chi/\hbar}D_t\psi$$

## 24. Covariant Differentiation Restores Relational Comparison

The physical derivative can now distinguish state change from coordinate-reference change.

That is the mathematical purpose of the connection.

## 25. The Connection Does Not Create the Invariance

The underlying closure relation was already physically invariant.

The connection allows that invariance to remain readable across locally varying representations.

The existing R2D manuscript states this ordering directly.

## 26. The R2D Causal Order Is

> counting invariance

> ↓

> closure invariance

> ↓

> local phase-reference freedom

> ↓

> connection.

<!-- source_pdf_page: 2575 -->

## 27. Charge Has Already Been Assigned Boundary Ownership

R2D writes charge schematically as

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

## 28. Charge Orientation Survives Recursive Replacement

If opposed local closure orientations remain distinguishable after enclosing classification, a signed physical
coupling survives.

This is the R2D antecedent of charge sign.

## 29. Charge Sign Controls Phase Orientation

The local gauge phase shift is

$$\delta\phi=\frac{q}{\hbar}\chi$$

Therefore reversing

$$ q\to-q$$

reverses the phase rotation.

## 30. Thus

$$\operatorname{sgn}(q)=\text{orientation of connection coupling}$$

## 31. Charge Magnitude Controls Coupling Strength

For fixed χ,

$$|\delta\phi|\propto|q|$$

Thus:

$$|q|=\text{physical connection-coupling magnitude}$$

<!-- source_pdf_page: 2576 -->

## 32. Gauge Theory Does Not Create Charge

The R2D order is

> retained orientation coupling → q → gauge representation.

This is already the ordering established in the integrated R2D development.

## 33. Return to the Spatial Translation Generator

Addendum 75 gave

$$ P_{\mathrm{can}}=-i\hbar\nabla$$

In the free case this is also the mechanical momentum read.

## 34. Local Phase Reference Changes That Identification

Ordinary spatial differentiation is no longer gauge covariant.

Therefore the physically comparable momentum must be built from

$$ D$$

## 35. Define the Gauge-Covariant Momentum

$$\Pi=-i\hbar D$$

## 36. Substitute the Covariant Derivative

$$\Pi=-i\hbar\left[\nabla-\frac{iq}{\hbar}\mathbf A_{\mathrm{EM}}\right]$$

Thus:

$$\Pi=-i\hbar\nabla-q\mathbf A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2577 -->

## 37. Therefore

$$\Pi=P_{\mathrm{can}}-q\mathbf A_{\mathrm{EM}}$$

This is electromagnetic minimal momentum coupling.

## 38. Canonical and Mechanical Momentum Are Now Distinct

$$ P_{\mathrm{can}}=-i\hbar\nabla$$

generates coordinate translation.

The gauge-covariant mechanical momentum is

$$\Pi=P_{\mathrm{can}}-q\mathbf A_{\mathrm{EM}}$$

## 39. This Refines Addendum 75 Rather Than Contradicting It

Without electromagnetic connection,

$$\mathbf A_{\mathrm{EM}}=0$$

so

$$\Pi=P_{\mathrm{can}}$$

## 40. The Temporal Connection Produces the Scalar Electromagnetic Energy

From

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

one has

$$ i\hbar D_t=i\hbar\partial_t-q\Phi_{\mathrm{EM}}$$

<!-- source_pdf_page: 2578 -->

## 41. Write the Free Residual Schrödinger Equation Covariantly

$$ i\hbar D_t\psi=-\frac{\hbar^2}{2m}D^2\psi$$

## 42. Replace the Spatial Derivative With Mechanical Momentum

Since

$$\Pi=-i\hbar D$$

$$-\hbar^2D^2=\Pi^2$$

## 43. Therefore

$$ i\hbar D_t\psi=\frac{\Pi^2}{2m}\psi$$

## 44. Expand the Temporal Side

$$ i\hbar\partial_t\psi-q\Phi_{\mathrm{EM}}\psi=\frac{\Pi^2}{2m}\psi$$

## 45. Rearranging Gives

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[\frac{\Pi^2}{2m}+q\Phi_{\mathrm{EM}}\right]\psi$$

## 46. Substitute the Mechanical Momentum

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[\frac{(-i\hbar\nabla-q\mathbf A_{\mathrm{EM}})^2}{2m}+q\Phi_{\mathrm{EM}}\right]\psi$$

This is the electromagnetic minimally coupled Schrödinger equation.

<!-- source_pdf_page: 2579 -->

## 47. The Two Electromagnetic Terms Have One Origin

Spatial connection:

$$ q\mathbf A_{\mathrm{EM}}$$

Temporal connection:

$$ q\Phi_{\mathrm{EM}}$$

Both arise from local phase comparison.

## 48. Addendum 77 Is Recovered as the Pure Scalar Limit

If

$$\mathbf A_{\mathrm{EM}}=0$$

then:

$$ V_{\mathrm{EM}}=q\Phi_{\mathrm{EM}}$$

Thus the scalar electromagnetic potential is one physical instance of the more general constraint phase bias
developed in Addendum 77.

## 49. The Connection Can Be Written as One Differential Object

Define

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

## 50. Under Local Gauge Transformation

$$\mathcal A'_{\mathrm{EM}}=\mathcal A_{\mathrm{EM}}+d\chi$$

## 51. The Phase Coordinate Transforms As

$$\phi'=\phi+\frac{q}{\hbar}\chi$$

<!-- source_pdf_page: 2580 -->

Thus:

$$ d\phi'=d\phi+\frac{q}{\hbar}\,d\chi$$

## 52. Define the Relational Phase Differential

$$ d\phi_{\mathrm{rel}}=d\phi-\frac{q}{\hbar}\mathcal A_{\mathrm{EM}}$$

## 53. It Is Gauge Invariant

$$ d\phi'_{\mathrm{rel}}=d\phi+\frac{q}{\hbar}d\chi-\frac{q}{\hbar}(\mathcal A_{\mathrm{EM}}+d\chi)$$

Therefore:

$$ d\phi'_{\mathrm{rel}}=d\phi_{\mathrm{rel}}$$

## 54. This Is the Core Physical Relation

The physically comparable recurrence is not

$$ d\phi$$

alone.

It is the relational phase change after local reference correction.

## 55. The Spatial Part Gives Mechanical Momentum

The spatial component is

$$\nabla\phi-\frac{q}{\hbar}\mathbf A_{\mathrm{EM}}$$

Multiplying by ℏ,

$$ p_{\mathrm{mech}}=\hbar\nabla\phi-q\mathbf A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2581 -->

## 56. This Quantity Is Gauge Invariant

Under

$$\phi'=\phi+\frac{q}{\hbar}\chi$$

and

$$\mathbf A'_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}+\nabla\chi$$

the added terms cancel.

## 57. The Temporal Part Gives Gauge-Invariant Recurrence Energy

The temporal component of

$$ d\phi_{\mathrm{rel}}$$

is

$$\partial_t\phi+\frac{q}{\hbar}\Phi_{\mathrm{EM}}$$

Multiplying by −ℏ,

$$ E_{\mathrm{rel}}=-\hbar\partial_t\phi-q\Phi_{\mathrm{EM}}$$

## 58. This Quantity Is Also Gauge Invariant

The change in temporal phase reference is exactly cancelled by the change in scalar connection.

## 59. Energy and Momentum Therefore Have Parallel Gauge- Covariant Forms

$$ E_{\mathrm{rel}}=-\hbar\partial_t\phi-q\Phi_{\mathrm{EM}}$$

$$ p_{\mathrm{mech}}=\hbar\nabla\phi-q\mathbf A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2582 -->

## 60. Electromagnetic Minimal Coupling Is Phase Comparison in Space and Time

The usual substitutions

$$ E\to E-q\Phi_{\mathrm{EM}}$$

and

$$ p\to p-q\mathbf A_{\mathrm{EM}}$$

are therefore later physical summaries of local phase covariance.

## 61. The Potential Coordinates Are Not the Gauge-Invariant Field

The values of

$$\Phi_{\mathrm{EM}}$$

and

$$\mathbf A_{\mathrm{EM}}$$

depend on the phase-reference convention.

They cannot themselves be primitive invariant ontology.

## 62. But Gauge Dependence Does Not Make Them Physically Meaningless

They carry the comparison information needed to relate local phase representations.

The existing R2D gauge chapter makes this distinction explicitly.

## 63. Gauge Curvature Comes Later

The invariant electromagnetic field relation is constructed from derivatives of the connection.

In the usual spatial-temporal decomposition,

$$\mathbf B=\nabla\times\mathbf A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2583 -->

and

$$\mathbf E=-\nabla\Phi_{\mathrm{EM}}-\partial_t\mathbf A_{\mathrm{EM}}$$

## 64. These Are Not Derived Here as Primitive R2D Fields

They are the gauge-invariant curvature of the projected connection.

Their deeper R2D interpretation belongs to the next addendum.

## 65. The Aharonov–Bohm Relation Shows Why Connection Matters

Consider a closed spatial path C .

The connection contributes the phase

$$\Delta\phi_{AB}=\frac{q}{\hbar}\oint_C\mathbf A_{\mathrm{EM}}\cdot d\mathbf l$$

## 66. Gauge Transformation Adds

$$\frac{q}{\hbar}\oint_C\nabla\chi\cdot d\mathbf l$$

For a single-valued regular gauge function,

$$\oint_C\nabla\chi\cdot d\mathbf l=0$$

## 67. Therefore the Closed-Loop Phase Is Gauge Invariant

$$\Delta\phi'_{AB}=\Delta\phi_{AB}$$

## 68. Stokes' Theorem Gives

$$\oint_C\mathbf A_{\mathrm{EM}}\cdot d\mathbf l=\int_\Sigma\mathbf B\cdot d\mathbf S$$

<!-- source_pdf_page: 2584 -->

Thus:

$$\Delta\phi_{AB}=\frac{q}{\hbar}\int_\Sigma\mathbf B\cdot d\mathbf S$$

## 69. This Is Especially Natural in R2D

Local representation can vary while a closed relational quantity remains invariant.

That architecture closely resembles recurrent closure.

But the two mathematical objects should not yet be identified term by term.

## 70. Principle — Closure Invariance Precedes Gauge Invariance

The physical count relation must remain invariant before gauge redundancy can represent it.

Thus:

> counting invariance → closure invariance → gauge invariance.

## 71. Principle — Global Phase Freedom Precedes Local Gauge Connection

A constant change of phase origin causes no local comparison problem.

A local change does.

Thus:

> α → χ(x, t) → connection.

## 72. Principle — Gauge Transformation Is Not Physical Boundary Replacement

> gauge change ≠ R2D occurrence.

The physical count class can remain unchanged.

<!-- source_pdf_page: 2585 -->

## 73. Principle — Local Phase Comparison Requires Covariant Differentiation

$$ D=\nabla-\frac{iq}{\hbar}\mathbf A_{\mathrm{EM}}$$

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

## 74. Principle — Charge Is the Oriented Coupling to the Connection

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

Its sign controls phase-rotation orientation.

Its magnitude controls coupling strength.

## 75. Principle — Mechanical Momentum Is Gauge-Covariant Translation

$$\Pi=-i\hbar\nabla-q\mathbf A_{\mathrm{EM}}$$

## 76. Principle — Electromagnetic Scalar Energy Is the Temporal Connection Read

$$ V_{\mathrm{EM}}=q\Phi_{\mathrm{EM}}$$

## 77. Principle — Minimal Coupling Is Not Primitive Substitution

The familiar rule

$$ p\to p-q\mathbf A_{\mathrm{EM}}$$

is the consequence of requiring local phase comparison to remain physically meaningful.

<!-- source_pdf_page: 2586 -->

## 78. Principle — Temporal and Spatial Coupling Are One Connection

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

## 79. Principle — Relational Phase Is Gauge Invariant

$$ d\phi_{\mathrm{rel}}=d\phi-\frac{q}{\hbar}\mathcal A_{\mathrm{EM}}$$

## 80. Principle — Gauge Potential Is Connection, Not Primitive Field Substance

The potential records how locally different phase representations are compared.

Gauge-invariant curvature comes later.

## 81. Logical Status

Canonical R2D

State identity is boundary indexed.

Recursive closure is invariant under changes that do not alter the underlying count structure.

Charge is a retained orientation-sensitive coupling.

Addendum 72

Closure produces phase and no primitive absolute phase zero.

Addendum 73

Born realization depends on phase-independent relational state structure.

Addendum 74

Boundary-preserving recurrence is represented unitarily.

Addendum 75

Boundary-preserving spatial translation gives

<!-- source_pdf_page: 2587 -->

Pcan = −iℏ∇.

Addendum 77

A scalar phase-rate bias produces a potential term.

Prior Gauge Result

Local phase-reference freedom requires a connection because ordinary differentiation mixes physical
change with reference change.

New Covariant Derivatives

$$ D=\nabla-\frac{iq}{\hbar}\mathbf A_{\mathrm{EM}}$$

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

Derived Mechanical Momentum

$$\Pi=-i\hbar\nabla-q\mathbf A_{\mathrm{EM}}$$

Derived Electromagnetic Scalar Energy

$$ V_{\mathrm{EM}}=q\Phi_{\mathrm{EM}}$$

Derived Minimal-Coupling Schrödinger Equation

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[\frac{(-i\hbar\nabla-q\mathbf A_{\mathrm{EM}})^2}{2m}+q\Phi_{\mathrm{EM}}\right]\psi$$

New Gauge-Invariant Relational Phase Differential

$$ d\phi_{\mathrm{rel}}=d\phi-\frac{q}{\hbar}\mathcal A_{\mathrm{EM}}$$

Not Yet Established

This addendum does not yet derive:

- the elementary charge magnitude;
- the Standard Model charge spectrum;
- Maxwell's equations from primitive R2D counting;
- the dynamical action of the electromagnetic connection;
- electromagnetic field energy;
- spin coupling;
- magnetic moment;

<!-- source_pdf_page: 2588 -->

• or the unique emergence of physical electromagnetism from all possible U (1) connections.

Those remain downstream physical bridges.

## 82. The Complete Minimal-Coupling Architecture

Boundary-native closure gives phase:

$$\phi$$

Absolute phase zero is not primitive:

> ↓

$$\phi\to\phi+\alpha$$

Allow the reference to vary locally:

> ↓

$$\chi=\chi(x,t)$$

Ordinary differentiation becomes reference contaminated:

> ↓

$$\partial\psi\to\partial\psi+\text{reference term}$$

Local comparison requires a connection:

> ↓

$$\Phi_{\mathrm{EM}},\quad\mathbf A_{\mathrm{EM}}$$

Charge sets oriented coupling:

> ↓

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

The derivatives become covariant:

> ↓

$$ D_t,\quad D$$

Spatial covariance gives:

<!-- source_pdf_page: 2589 -->

⇓

$$\Pi=-i\hbar\nabla-q\mathbf A_{\mathrm{EM}}$$

Temporal covariance gives:

> ↓

$$ V_{\mathrm{EM}}=q\Phi_{\mathrm{EM}}$$

Together:

> ↓

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[\frac{(-i\hbar\nabla-q\mathbf A_{\mathrm{EM}})^2}{2m}+q\Phi_{\mathrm{EM}}\right]\psi$$

Electromagnetic minimal coupling is therefore the end of the local phase-comparison chain, not its
beginning.

## 83. Conclusion

Quantum phase is logically prior to electromagnetic gauge potential.

A boundary-native recurrence closes before any electromagnetic field coordinate is assigned.

That closure admits a phase representation.

Because closure possesses no primitive absolute phase zero, different mathematical representations can
use different phase origins without changing the physical state.

For a global phase-reference shift, this freedom is harmless.

Every point changes by the same amount.

Relative phase is preserved automatically.

The situation changes when the reference freedom becomes local:

$$\chi=\chi(x,t)$$

Then ordinary derivatives no longer distinguish physical recurrence change from change in reference.

For a charge-bearing state,

<!-- source_pdf_page: 2590 -->

ψ ′ = eiqχ/ℏ ψ,

spatial differentiation produces an additional term proportional to

$$\nabla\chi$$

and temporal differentiation produces another proportional to

$$\partial_t\chi$$

A physical comparison therefore requires a connection.

Introduce

$$\mathbf A'_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}+\nabla\chi$$

and

$$\Phi'_{\mathrm{EM}}=\Phi_{\mathrm{EM}}-\partial_t\chi$$

The corresponding covariant derivatives are

$$ D=\nabla-\frac{iq}{\hbar}\mathbf A_{\mathrm{EM}}$$

and

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

These derivatives compare locally different phase representations while preserving the same physical
closure relation.

The spatial connection changes the momentum read from

$$ P_{\mathrm{can}}=-i\hbar\nabla$$

to

$$-i\hbar\nabla-q\mathbf A_{\mathrm{EM}}$$

The temporal connection contributes

$$ q\Phi_{\mathrm{EM}}$$

Thus:

<!-- source_pdf_page: 2591 -->

∂ψ    (−iℏ∇ − qAEM )2

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[\frac{(-i\hbar\nabla-q\mathbf A_{\mathrm{EM}})^2}{2m}+q\Phi_{\mathrm{EM}}\right]\psi$$

Minimal coupling therefore does not need to be imposed as an unexplained replacement rule.

It follows from local phase comparison.

The physical charge coordinate likewise acquires a direct role.

R2D has already identified

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

as a retained orientation-sensitive boundary coupling.

The sign σ determines which direction the state rotates under the same local phase-reference change.

The magnitude ∣q∣ determines how strongly it couples.

Gauge theory does not create this orientation.

It is the projected representation of an orientation already retained by the boundary architecture.

The most compact expression of the complete relation is

$$ d\phi_{\mathrm{rel}}=d\phi-\frac{q}{\hbar}\mathcal A_{\mathrm{EM}}$$

where

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

The coordinate phase

$$ d\phi$$

depends on local reference.

The connection

$$\mathbf A_{\mathrm{EM}}$$

also depends on local reference.

Their combination does not.

This is the electromagnetic physical read that survives.

<!-- source_pdf_page: 2592 -->

The central statement is therefore:

 electromagnetic minimal coupling is the physical rule required to compare closure phase
across locally different phase references. The underlying count relation remains invariant before gauge
coordinates are introduced. Local phase freedom makes ordinary derivatives reference dependent,
requiring a connection. Charge determines the orientation and strength with which the quantum state
couples to that connection. The familiar substitutions $\mathbf P_{\mathrm{can}}\to\mathbf P_{\mathrm{can}}-q\mathbf A_{\mathrm{EM}}$ and $i\hbar\partial_t\to i\hbar\partial_t-q\Phi_{\mathrm{EM}}$ therefore arise after local
> phase comparison rather than before it.

And hence:

> local phase comparison occurs before electromagnetic minimal coupling.
