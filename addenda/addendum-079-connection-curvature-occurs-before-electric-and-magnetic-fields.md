---
r2d_id: addendum-079
title: Addendum 79 — Connection Curvature Occurs Before Electric and Magnetic Fields
subtitle: Gauge Curvature, Covariant Noncommutation, and the Homogeneous Maxwell Structure
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 79
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2593
pdf_page_end: 2621
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

# Addendum 79 — Connection Curvature Occurs Before Electric and Magnetic Fields

*Gauge Curvature, Covariant Noncommutation, and the Homogeneous Maxwell Structure*

## Abstract

<!-- source_pdf_page: 2593 -->

Addendum 78 derived electromagnetic minimal coupling from a more primitive comparison problem.

A quantum boundary possesses closure phase before it possesses an electromagnetic potential. Because
the phase origin is not primitive, equivalent physical representations may use different local phase
references:

$$\psi'=e^{iq\chi/\hbar}\psi$$

When

$$\chi=\chi(x,t)$$

ordinary differentiation mixes physical recurrence change with change of phase reference.

A connection is therefore required.

Using the R2D notation that keeps electromagnetic vector potential distinct from asymmetry A = P − R,
Addendum 78 introduced

$$\mathbf A'_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}+\nabla\chi$$

and

$$\Phi'_{\mathrm{EM}}=\Phi_{\mathrm{EM}}-\partial_t\chi$$

The corresponding connection one-form is

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

with transformation

$$\mathcal A'_{\mathrm{EM}}=\mathcal A_{\mathrm{EM}}+d\chi$$

The connection itself is therefore reference dependent.

<!-- source_pdf_page: 2594 -->

The next question is not how to interpret its value at one point.

The next question is:

What relation remains when locally referenced phase comparisons are carried around a closed infinitesimal loop?

Define the electromagnetic curvature two-form

$$ \mathcal F_{\mathrm{EM}}\equiv d\mathcal A_{\mathrm{EM}}. $$

Under local phase-reference transformation,

$$\mathcal F'_{\mathrm{EM}}=d(\mathcal A_{\mathrm{EM}}+d\chi)$$

Because

$$ d^2\chi=0, $$

one obtains

$$\mathcal F'_{\mathrm{EM}}=\mathcal F_{\mathrm{EM}}$$

The curvature is therefore independent of the arbitrary local phase reference.

This recovers and sharpens the hierarchy already identified in the R2D gauge development:

invariant physical state → reference-dependent connection → reference-independent field relation.

The earlier manuscript explicitly identified Aμ as the projected connection and Fμν as its gauge-invariant
curvature.

The physical meaning of this curvature becomes especially clear through covariant differentiation.

Addendum 78 introduced

$$ D=d-\frac{iq}{\hbar}\mathcal A_{\mathrm{EM}}$$

Apply the covariant derivative twice.

For the Abelian electromagnetic connection,

$$ D^2\psi=-\frac{iq}{\hbar}\mathcal F_{\mathrm{EM}}\psi$$

In component form,

<!-- source_pdf_page: 2595 -->

$$ [D_\mu,D_\nu]\psi=-\frac{iq}{\hbar}F_{\mu\nu}\psi. $$

Thus the electromagnetic field strength measures the failure of locally covariant phase comparisons to
commute.

Compare two neighboring comparison sequences:

$$\mu\to\nu$$

and

$$\nu\to\mu$$

If they return the same phase relation,

$$ F_{\mu\nu}=0$$

If they differ,

$$ F_{\mu\nu}\ne0. $$

The curvature therefore measures the infinitesimal failure of locally referenced phase comparison to close.

This does not make the gauge loop identical to primitive R2D closure.

Rather, it identifies gauge curvature as a mature physical projection in which a closed comparison acquires
a measurable phase mismatch.

The same relation appears geometrically.

For a closed path C ,

$$\Delta\phi_C=\frac{q}{\hbar}\oint_C\mathcal A_{\mathrm{EM}}$$

For a surface Σ bounded by C , Stokes' theorem gives

$$\oint_C\mathcal A_{\mathrm{EM}}=\int_\Sigma\mathcal F_{\mathrm{EM}}$$

Therefore:

$$\Delta\phi_C=\frac{q}{\hbar}\int_\Sigma\mathcal F_{\mathrm{EM}}$$

For an infinitesimal oriented loop,

<!-- source_pdf_page: 2596 -->

$$\delta\phi_{\mathrm{loop}}\propto\frac{q}{\hbar}F_{\mu\nu}\,d\Sigma^{\mu\nu}$$

Curvature is therefore the local phase holonomy per oriented area.

The electromagnetic field is not introduced first.

The ordering is:

> closure phase

> ↓

> local phase-reference freedom

> ↓

> connection

> ↓

> connection curvature.

Only after a physical space-time decomposition does that curvature acquire the familiar electric and
magnetic reads.

Using

$$ \mathcal A_{\mathrm{EM}}=A_{\mathrm{EM}}\cdot dx-\Phi_{\mathrm{EM}}dt, $$

the spatial components of

$$ \mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}} $$

give

$$\mathbf B=\nabla\times\mathbf A_{\mathrm{EM}}$$

while its space-time components give

$$\mathbf E=-\nabla\Phi_{\mathrm{EM}}-\frac{\partial\mathbf A_{\mathrm{EM}}}{\partial t}$$

Thus:

$$ F_{\mu\nu}\longrightarrow\{\mathbf E,\mathbf B\}$$

Electric and magnetic fields are therefore not two independent primitive substances.

<!-- source_pdf_page: 2597 -->

They are frame-dependent components of one gauge-invariant connection-curvature relation, consistent
with the earlier R2D gauge analysis.

The curvature construction immediately supplies another result.

Because

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

one has locally

$$ d\mathcal F_{\mathrm{EM}}=d^2\mathcal A_{\mathrm{EM}}=0. $$

This is the electromagnetic Bianchi identity.

In the ordinary space-time decomposition it yields

$$ \nabla\cdot B=0, $$

and

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

Thus two Maxwell equations arise before any electromagnetic source equation has been specified.

They are not source-response laws.

They are consistency conditions following from the curvature of a smooth local U (1) connection.

The other Maxwell equations do not follow from this result.

The relations

$$\nabla\cdot\mathbf E=\frac{\rho}{\epsilon_0}$$

and

$$\nabla\times\mathbf B-\frac{1}{c^2}\frac{\partial\mathbf E}{\partial t}=\mu_0\mathbf J$$

require an additional dynamical bridge between electromagnetic curvature and charge-current support.

In covariant form that missing relation is

<!-- source_pdf_page: 2598 -->

∂μ F μν = μ0 J ν .

That equation is not derived here.

The present addendum therefore separates two structures usually presented together as Maxwell's
equations:

$$ dF=0$$

follows from connection geometry,

whereas

$$ d{*F}\propto J$$

requires source dynamics.

The distinction is essential for R2D boundary ownership.

Addendum 78 already assigns charge

$$ q=\sigma|q|$$

to a retained orientation-sensitive coupling.

The next problem is therefore not to rediscover charge from the gauge field.

It is to determine why retained oriented coupling becomes a source of electromagnetic curvature.

The central statement is:

 the electromagnetic field does not primitively precede the gauge connection. Local phase-
reference freedom first requires a connection so that neighboring closure-phase representations remain
comparable. The gauge-invariant electromagnetic relation is then the curvature of that connection, $\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$,
 equivalently the failure of covariant phase comparisons to commute around an infinitesimal loop. Electric
and magnetic fields are later space-time components of this one curvature relation. Because $d^2=0$, the
curvature automatically satisfies $d\mathcal F_{\mathrm{EM}}=0$, yielding $\nabla\cdot B=0$ and $\nabla\times E+\partial_t B=0$. The source equations require a
> separate bridge between retained oriented coupling and curvature and are not derived here.

And hence:

> connection curvature occurs before electric and magnetic fields.

<!-- source_pdf_page: 2599 -->

## 1. Begin With the Connection Derived in Addendum 78

The electromagnetic connection is

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

It exists because locally varying phase references require a rule for comparing neighboring quantum phase
reads.

## 2. The Connection Is Not Gauge Invariant

Under

$$\psi'=e^{iq\chi/\hbar}\psi$$

the connection transforms as

$$\mathcal A'_{\mathrm{EM}}=\mathcal A_{\mathrm{EM}}+d\chi$$

## 3. Therefore the Local Value of the Connection Cannot Be the Entire Physical Invariant

Different connection coordinates can represent the same locally referenced physical relation.

## 4. This Is Not a Defect

The connection was introduced precisely to compensate for local reference freedom.

Reference dependence is part of its mathematical role.

## 5. The Next Invariant Must Remove Pure Reference Change

Take the exterior derivative:

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2600 -->

## 6. Transform the Curvature

$$\mathcal F'_{\mathrm{EM}}=d\mathcal A'_{\mathrm{EM}}$$

Therefore:

$$\mathcal F'_{\mathrm{EM}}=d(\mathcal A_{\mathrm{EM}}+d\chi)$$

## 7. Exterior Differentiation Closes

$$ d^2\chi=0$$

Hence:

$$\mathcal F'_{\mathrm{EM}}=\mathcal F_{\mathrm{EM}}$$

## 8. Curvature Is Gauge Invariant

The local reference coordinate has disappeared.

The remaining two-form measures a physical relation independent of the arbitrary choice of local phase
zero.

## 9. This Gives the First Electromagnetic Hierarchy

$$\text{phase-reference freedom}\to\mathcal A_{\mathrm{EM}}\to\mathcal F_{\mathrm{EM}}$$

## 10. Connection and Curvature Have Different Roles

$$\mathcal A_{\mathrm{EM}}=\text{rule for local comparison}$$

while

$$\mathcal F_{\mathrm{EM}}=\text{reference-independent curvature of that comparison rule}$$

## 11. Curvature Can Be Read Through Covariant Derivatives

Addendum 78 defined

<!-- source_pdf_page: 2601 -->

iq

$$ D=d-\frac{iq}{\hbar}\mathcal A_{\mathrm{EM}}$$

## 12. Apply the Covariant Derivative Twice

$$ D^2\psi=\left(d-\frac{iq}{\hbar}\mathcal A_{\mathrm{EM}}\right)^2\psi$$

## 13. For Abelian U (1), the Connection Commutes With Itself

The quadratic connection term does not produce the non-Abelian contribution that would appear for
matrix-valued gauge groups.

## 14. Therefore

$$ D^2\psi=-\frac{iq}{\hbar}d\mathcal A_{\mathrm{EM}}\psi$$

Thus:

$$ D^2\psi=-\frac{iq}{\hbar}\mathcal F_{\mathrm{EM}}\psi$$

## 15. In Components

$$[D_\mu,D_\nu]\psi=-\frac{iq}{\hbar}F_{\mu\nu}\psi$$

## 16. Curvature Is Therefore Covariant Noncommutation

If

$$ F_{\mu\nu}=0$$

then infinitesimal covariant comparisons in the μ and ν directions commute.

<!-- source_pdf_page: 2602 -->

## 17. If

$$ F_{\mu\nu}\ne0$$

the two comparison orders differ.

The local phase relation depends on the infinitesimal loop enclosed by the two paths.

## 18. This Gives a Physical Definition of Field Strength

$$ F_{\mu\nu}=\text{curvature of local phase comparison}$$

## 19. The Field Is Not a Separate Substance Added to the Connection

It is the invariant failure of the connection to be locally removable over an extended two-dimensional
comparison.

## 20. A Pure-Gauge Connection Has Zero Local Curvature

If locally

$$\mathcal A_{\mathrm{EM}}=d\chi$$

then:

$$\mathcal F_{\mathrm{EM}}=d^2\chi=0$$

## 21. The Connection Can Therefore Be Nonzero While Local Curvature Vanishes

This distinction will be important for global holonomy.

## 22. Closed-Loop Comparison Reveals Curvature Geometrically

Consider a closed loop

$$ C$$

<!-- source_pdf_page: 2603 -->

The connection contributes the phase relation

$$\Delta\phi_C=\frac{q}{\hbar}\oint_C\mathcal A_{\mathrm{EM}}$$

## 23. Apply Stokes' Theorem

If

$$\partial\Sigma=C$$

then locally

$$\oint_C\mathcal A_{\mathrm{EM}}=\int_\Sigma d\mathcal A_{\mathrm{EM}}$$

Therefore:

$$\oint_C\mathcal A_{\mathrm{EM}}=\int_\Sigma\mathcal F_{\mathrm{EM}}$$

## 24. Hence

$$\Delta\phi_C=\frac{q}{\hbar}\int_\Sigma\mathcal F_{\mathrm{EM}}$$

## 25. For an Infinitesimal Loop

Let

$$ d\Sigma^{\mu\nu}$$

be its oriented area element.

Then schematically,

$$\delta\phi_{\mathrm{loop}}=\frac{q}{2\hbar}F_{\mu\nu}\,d\Sigma^{\mu\nu}$$

up to the chosen orientation convention for the antisymmetric area element.

<!-- source_pdf_page: 2604 -->

## 26. Curvature Is Thus Phase Holonomy Per Oriented Area

The loop does not merely sample a value of the connection.

It tests whether local comparisons return to the same relational phase after closure.

## 27. This Is Closely Aligned With the R2D Closure Architecture

R2D begins with recurrence and closure.

Gauge curvature is a mature physical representation in which closed comparison can produce an invariant
phase relation.

## 28. But Gauge Holonomy Is Not Yet Primitive R2D Closure

The correspondence is structural, not term-by-term.

The existing R2D gauge analysis makes the same distinction for Wilson loops and the Aharonov–Bohm
relation.

## 29. Expand the Curvature Into Space and Time

Use

$$\mathcal A_{\mathrm{EM}}=\mathbf A_{\mathrm{EM}}\cdot d\mathbf x-\Phi_{\mathrm{EM}}\,dt$$

Then:

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

## 30. The Spatial-Spatial Components Are

$$ F_{ij}=\partial_i A_{\mathrm{EM},j}-\partial_j A_{\mathrm{EM},i}$$

## 31. Define the Magnetic Field

$$\mathbf B=\nabla\times\mathbf A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2605 -->

Equivalently,

$$ F_{ij}=\epsilon_{ijk}B_k$$

## 32. Magnetic Field Is Therefore Spatial Connection Curvature

It measures the failure of gauge-covariant spatial translations to commute.

## 33. The Space-Time Components Are

$$ E_i=-\partial_i\Phi_{\mathrm{EM}}-\partial_t A_{\mathrm{EM},i}$$

Thus:

$$\mathbf E=-\nabla\Phi_{\mathrm{EM}}-\frac{\partial\mathbf A_{\mathrm{EM}}}{\partial t}$$

## 34. Electric Field Is Therefore Space-Time Connection Curvature

It measures the relation between temporal phase comparison and spatial phase comparison.

## 35. Electric and Magnetic Fields Are Not Independent Primitive Objects

They are two component sets of

$$ F_{\mu\nu}$$

## 36. Their Separation Depends on Space-Time Frame

A different inertial decomposition changes the partition between electric and magnetic components.

The invariant electromagnetic object is the curvature relation.

<!-- source_pdf_page: 2606 -->

## 37. Thus the R2D Order Is

$$\mathcal F_{\mathrm{EM}}$$

> ↓

> space-time frame decomposition

> ↓

$$\{\mathbf E,\mathbf B\}$$

## 38. Not

$$\{\mathbf E,\mathbf B\}\to\mathcal F_{\mathrm{EM}}$$

The field tensor is logically prior to its frame decomposition.

## 39. The Existing R2D Gauge Development Already Anticipated This Ordering

It identifies electric and magnetic fields as frame-dependent components of one gauge-invariant field
relation rather than independent primitive substances.

## 40. Mechanical Momentum Makes Spatial Curvature Directly Observable

Addendum 78 gave

$$\Pi_i=-i\hbar\partial_i-qA_{\mathrm{EM},i}$$

## 41. In Covariant-Derivative Form

$$\Pi_i=-i\hbar D_i$$

## 42. Compute the Momentum Commutator

$$[\Pi_i,\Pi_j]=(-i\hbar)^2[D_i,D_j]$$

<!-- source_pdf_page: 2607 -->

Using

$$[D_i,D_j]=-\frac{iq}{\hbar}F_{ij}$$

one obtains

$$[\Pi_i,\Pi_j]=iq\hbar F_{ij}$$

## 43. Therefore

$$[\Pi_i,\Pi_j]=iq\hbar\epsilon_{ijk}B_k$$

## 44. Free Spatial Translation Is Commutative

Without curvature,

$$[P_i,P_j]=0$$

## 45. Electromagnetic Curvature Changes the Translation Algebra

With magnetic curvature,

$$[\Pi_i,\Pi_j]\ne0$$

Thus magnetic field is the noncommutativity of gauge-covariant spatial translation.

## 46. This Deepens Addendum 75

Addendum 75 found momentum from translation.

Addendum 79 now shows that an electromagnetic connection changes the geometry of those translations.

## 47. The Temporal-Spatial Commutator Contains the Electric Field

With

$$ D_t=\partial_t+\frac{iq}{\hbar}\Phi_{\mathrm{EM}}$$

<!-- source_pdf_page: 2608 -->

and

$$ D_i=\partial_i-\frac{iq}{\hbar}A_{\mathrm{EM},i}$$

one finds

$$[D_t,D_i]=\frac{iq}{\hbar}E_i$$

## 48. Electric Field Is Therefore the Noncommutation Between Temporal and Spatial Covariant Comparison

This gives a unified interpretation:

$$\mathbf B=\text{spatial-spatial curvature}$$

$$\mathbf E=\text{temporal-spatial curvature}$$

## 49. The Electromagnetic Field Is the Complete Curvature of Phase Comparison

Neither E nor B alone is fundamental to the gauge structure.

Together they represent different projections of

$$\mathcal F_{\mathrm{EM}}$$

## 50. Curvature Automatically Satisfies a Closure Identity

Since

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

take another exterior derivative:

$$ d\mathcal F_{\mathrm{EM}}=d^2\mathcal A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2609 -->

## 51. Therefore

$$ d\mathcal F_{\mathrm{EM}}=0$$

This is the Abelian Bianchi identity.

## 52. It Is Not an Independent Dynamical Assumption

It follows from the local connection-curvature construction.

## 53. Decompose the Bianchi Identity Into Space and Time

The purely spatial part gives:

$$\nabla\cdot\mathbf B=0$$

## 54. The Mixed Space-Time Part Gives

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

## 55. These Are Two Maxwell Equations

They are conventionally known as:

- Gauss's law for magnetism;
- Faraday's law.

## 56. But Their Logical Status Is Different From the Source Equations

They arise from the geometry of the connection itself.

No charge density or current has yet appeared.

## 57. The Homogeneous Maxwell Structure Is Therefore Kinematic

Within a smooth ordinary electromagnetic gauge region,

<!-- source_pdf_page: 2610 -->

FEM = dAEM

implies

$$ d\mathcal F_{\mathrm{EM}}=0$$

## 58. Thus

> local phase comparison → connection → curvature → homogeneous Maxwell relations.

## 59. The Other Maxwell Equations Do Not Follow

The source equations are

$$\nabla\cdot\mathbf E=\frac{\rho}{\epsilon_0}$$

and

$$\nabla\times\mathbf B-\frac{1}{c^2}\frac{\partial\mathbf E}{\partial t}=\mu_0\mathbf J$$

## 60. Covariantly

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

## 61. These Equations Require More Than Gauge Geometry

They specify how electromagnetic curvature responds to physical source support.

That is dynamical information.

## 62. Therefore

$$ dF=0$$

and

<!-- source_pdf_page: 2611 -->

d∗F ∝ J

must not be assigned the same derivational status.

## 63. The First Follows From Connection Curvature

$$ dF=0$$

is a structural identity.

## 64. The Second Requires a Source Law

$$ d{*F}\propto J$$

requires a physical bridge between charge-current structure and curvature.

## 65. R2D Already Has a Candidate Source Owner

Charge has been identified as retained orientation-sensitive coupling:

$$ q=\sigma|q|$$

## 66. A Collection of Such Couplings Can Form a Current

At the mature electromagnetic level this is represented by

$$ J^\mu$$

## 67. But the Map

$$\text{retained oriented coupling}\to J^\mu\to\partial_\mu F^{\mu\nu}$$

has not yet been derived.

## 68. That Is the Next Electromagnetic Problem

The source equations require their own R2D boundary ownership and physical calibration.

<!-- source_pdf_page: 2612 -->

## 69. Local Curvature and Global Holonomy Must Be Distinguished

If

$$ F_{\mu\nu}=0$$

throughout a simply connected local region, the connection is locally pure gauge.

## 70. But Global Topology Can Retain a Closed Relation

In a multiply connected physical domain, a state can traverse a region where local field strength vanishes
while still acquiring nontrivial holonomy around an excluded region.

## 71. The Aharonov–Bohm Effect Is the Canonical Example

Along the accessible paths one may have

$$\mathbf B=0$$

while still obtaining

$$\oint\mathcal A_{\mathrm{EM}}\cdot d\mathbf l\ne0$$

## 72. Therefore

zero local curvature⇏zero global holonomy.

## 73. This Is Not a Contradiction

Curvature is local.

Holonomy can depend on the global structure of the physical domain.

## 74. In Differential-Geometric Language

The potential may require multiple local patches even when the curvature two-form is globally defined.

<!-- source_pdf_page: 2613 -->

Therefore the equation

$$ F=dA$$

should be understood locally on gauge patches when the global bundle is nontrivial.

## 75. The More General Statement Is

$$ F=\text{curvature of the }U(1)\text{ connection}$$

Locally:

$$ F=dA$$

## 76. The Bianchi Identity Remains

$$ dF=0$$

on ordinary source-free gauge patches.

## 77. The Global Qualification Strengthens the R2D Interpretation

A locally unreadable or removable coordinate relation can still participate in a globally retained closed
relation.

That is exactly the kind of distinction recursive boundary analysis is designed to preserve.

## 78. Connection Curvature Is Not Yet Electromagnetic Source Dynamics

The present result establishes the geometry of electromagnetic comparison.

It does not explain why a particular physical source produces a particular magnitude of curvature.

## 79. Nor Does Curvature Yet Derive Field Energy

The conventional electromagnetic energy density

<!-- source_pdf_page: 2614 -->

ϵ0 2   1 2

$$\frac{\epsilon_0}{2}\mathbf E^2+\frac{1}{2\mu_0}\mathbf B^2$$

requires a field action or equivalent dynamical structure.

That has not yet been derived from primitive R2D counting.

## 80. Nor Does It Yet Derive Wave Propagation

The vacuum wave equations for E and B require both homogeneous and source-free inhomogeneous
Maxwell equations.

The present addendum supplies only the homogeneous half.

## 81. Principle — Connection Precedes Curvature

$$\mathcal A_{\mathrm{EM}}\to\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

## 82. Principle — Curvature Removes Local Phase-Reference Freedom

$$\mathcal A_{\mathrm{EM}}\to\mathcal A_{\mathrm{EM}}+d\chi$$

but

$$\mathcal F_{\mathrm{EM}}\to\mathcal F_{\mathrm{EM}}$$

## 83. Principle — Curvature Is Covariant Noncommutation

$$[D_\mu,D_\nu]\psi=-\frac{iq}{\hbar}F_{\mu\nu}\psi$$

## 84. Principle — Curvature Is Closed-Loop Phase Per Oriented Area

$$\Delta\phi_C=\frac{q}{\hbar}\int_\Sigma\mathcal F_{\mathrm{EM}}$$

<!-- source_pdf_page: 2615 -->

## 85. Principle — Electric and Magnetic Fields Are Curvature Components

$$ F_{\mu\nu}\longrightarrow\{\mathbf E,\mathbf B\}$$

## 86. Principle — Magnetic Field Is Spatial Translation Curvature

$$[\Pi_i,\Pi_j]=iq\hbar\epsilon_{ijk}B_k$$

## 87. Principle — Electric Field Is Space-Time Comparison Curvature

$$[D_t,D_i]=\frac{iq}{\hbar}E_i$$

## 88. Principle — Homogeneous Maxwell Structure Follows From Curvature

$$ dF=0$$

Therefore:

$$\nabla\cdot\mathbf B=0$$

and

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

## 89. Principle — Source Equations Require an Additional Physical Bridge

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

does not follow merely from the existence of the connection.

<!-- source_pdf_page: 2616 -->

## 90. Principle — Local Curvature and Global Holonomy Are Different

$$ F_{\mu\nu}=0$$

locally does not necessarily imply

$$\oint A=0$$

globally.

## 91. Logical Status

Canonical R2D

Physical state structure is defined before its coordinate representation.

Closure can remain invariant while representational coordinates vary.

Addendum 72

Boundary-native recurrence gives cyclic phase.

Addendum 78

Local phase-reference freedom requires an electromagnetic connection:

$$\mathcal A_{\mathrm{EM}}$$

New Curvature Definition

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

Derived Gauge Invariance

$$\mathcal F'_{\mathrm{EM}}=\mathcal F_{\mathrm{EM}}$$

Derived Covariant Noncommutation

$$[D_\mu,D_\nu]=-\frac{iq}{\hbar}F_{\mu\nu}$$

Derived Magnetic Component

$$\mathbf B=\nabla\times\mathbf A_{\mathrm{EM}}$$

<!-- source_pdf_page: 2617 -->

Derived Electric Component

$$\mathbf E=-\nabla\Phi_{\mathrm{EM}}-\frac{\partial\mathbf A_{\mathrm{EM}}}{\partial t}$$

Derived Bianchi Identity

$$ d\mathcal F_{\mathrm{EM}}=0$$

Derived Homogeneous Maxwell Equations

$$\nabla\cdot\mathbf B=0$$

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

Not Yet Established

This addendum does not yet derive:

- Gauss's electric source law;
- the Ampère–Maxwell source law;
- the electromagnetic source current from primitive R2D counts;
- the electromagnetic action;
- the field-energy density;
- the vacuum impedance;
- the value of ϵ0 or μ0 ;
- electromagnetic radiation dynamics;
- magnetic monopole structure;
- or the full global topology of the electromagnetic gauge bundle.

Those require additional physical bridges.

## 92. The Complete Curvature Architecture

Boundary-native recurrence gives phase:

$$\phi$$

Local phase-reference freedom gives:

> ↓

$$\chi(x)$$

Local comparison requires a connection:

> ↓

<!-- source_pdf_page: 2618 -->

AEM .

The connection is gauge dependent:

> ↓

$$\mathcal A_{\mathrm{EM}}\to\mathcal A_{\mathrm{EM}}+d\chi$$

Take its curvature:

> ↓

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

The reference term disappears:

$$\mathcal F'_{\mathrm{EM}}=\mathcal F_{\mathrm{EM}}$$

Covariant comparisons fail to commute according to:

> ↓

$$[D_\mu,D_\nu]=-\frac{iq}{\hbar}F_{\mu\nu}$$

A space-time frame decomposes the curvature:

> ↓

$$ F_{\mu\nu}\longrightarrow\{\mathbf E,\mathbf B\}$$

Closure of the exterior derivative gives:

> ↓

$$ dF=0$$

Therefore:

> ↓

$$\nabla\cdot\mathbf B=0$$

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

The homogeneous Maxwell structure is therefore downstream of local phase comparison.

<!-- source_pdf_page: 2619 -->

## 93. Conclusion

Electric and magnetic fields are conventionally introduced as basic physical fields.

Maxwell's equations then describe how those fields vary in space and time.

R2D places them later.

A quantum boundary first possesses recurrent closure.

Closure admits a phase representation.

Because absolute phase zero is not primitive, equivalent physical descriptions may use different local phase
references.

Once that freedom becomes local, ordinary differentiation cannot distinguish physical phase change from
change of reference.

A connection is therefore required:

$$\mathcal A_{\mathrm{EM}}$$

The connection itself depends on the chosen local phase coordinates:

$$\mathcal A'_{\mathrm{EM}}=\mathcal A_{\mathrm{EM}}+d\chi$$

It is therefore not yet the invariant electromagnetic relation.

The invariant appears one step later.

Take the curvature:

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

Because

$$ d^2\chi=0,\qquad\mathcal F'_{\mathrm{EM}}=\mathcal F_{\mathrm{EM}}$$

The arbitrary reference has disappeared.

The same curvature appears algebraically as

$$ D^2\psi=-\frac{iq}{\hbar}\mathcal F_{\mathrm{EM}}\psi$$

<!-- source_pdf_page: 2620 -->

Electromagnetic field strength therefore measures the failure of locally covariant phase comparisons to
commute.

Geometrically, the same statement appears as closed-loop phase holonomy:

$$\Delta\phi_C=\frac{q}{\hbar}\int_\Sigma\mathcal F_{\mathrm{EM}}$$

Thus curvature measures the invariant phase mismatch accumulated around a closed comparison.

Only after physical space-time coordinates are selected does this one curvature relation separate into

$$\mathbf B=\nabla\times\mathbf A_{\mathrm{EM}}$$

and

$$\mathbf E=-\nabla\Phi_{\mathrm{EM}}-\frac{\partial\mathbf A_{\mathrm{EM}}}{\partial t}$$

Electric and magnetic fields are therefore not two primitive substances.

They are different frame reads of one gauge-invariant curvature.

The curvature construction itself already contains part of Maxwell structure.

Since

$$ F=dA$$

one obtains

$$ dF=0$$

In ordinary space-time coordinates this becomes

$$\nabla\cdot\mathbf B=0$$

and

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

These equations require no charge or current source law.

They follow from the consistency of the connection-curvature architecture.

The other Maxwell equations are different.

<!-- source_pdf_page: 2621 -->

They specify how physical charge-current support determines curvature:

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

That relation is not obtained from gauge geometry alone.

It requires a separate physical bridge.

R2D already supplies the likely source owner:

$$ q=\sigma|q|$$

as retained orientation-sensitive coupling.

The next task is therefore to determine how retained oriented source structure becomes the physical
current that supports electromagnetic curvature.

The central statement is:

the electromagnetic field is not primitive to the quantum phase relation. Local phase-
reference freedom first requires a connection. The gauge-invariant physical relation is then the curvature of
that connection, equivalently the noncommutativity of neighboring covariant phase comparisons or the
 phase holonomy generated around an infinitesimal loop. Electric and magnetic fields are later space-time
components of this curvature. Because curvature is locally $d\mathcal A_{\mathrm{EM}}$, the identity $d\mathcal F_{\mathrm{EM}}=0$ follows before any
source dynamics and yields the homogeneous Maxwell equations. The remaining Maxwell equations
> require a separate bridge between retained oriented coupling and curvature support.

And hence:

> connection curvature occurs before electric and magnetic fields.
