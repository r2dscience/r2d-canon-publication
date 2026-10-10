---
r2d_id: addendum-080
title: Addendum 80 — Conserved Oriented Coupling Occurs Before the Maxwell Source Equations
subtitle: Retained Charge Orientation, Conserved Current, and the Dynamical Support of Electromagnetic Curvature
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 80
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2622
pdf_page_end: 2654
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

# Addendum 80 — Conserved Oriented Coupling Occurs Before the Maxwell Source Equations

*Retained Charge Orientation, Conserved Current, and the Dynamical Support of Electromagnetic Curvature*

## Abstract

<!-- source_pdf_page: 2622 -->

Addendum 79 established the electromagnetic curvature relation

$$ \mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}} $$

from the gauge connection required for local phase comparison.

Because

$$ d^2=0$$

the curvature necessarily satisfies

$$ d\mathcal F_{\mathrm{EM}}=0. $$

In a physical space-time decomposition this gives

$$\nabla\cdot\mathbf B=0$$

and

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

These are the homogeneous Maxwell equations.

They follow from connection geometry before electromagnetic source dynamics has been specified.

The remaining equations,

$$\nabla\cdot\mathbf E=\frac{\rho_q}{\epsilon_0}$$

and

$$\nabla\times\mathbf B-\frac{1}{c^2}\frac{\partial\mathbf E}{\partial t}=\mu_0\mathbf J_q$$

<!-- source_pdf_page: 2623 -->

have different logical status.

They do not follow merely from

$$\mathcal F_{\mathrm{EM}}=d\mathcal A_{\mathrm{EM}}$$

They specify how physical source structure supports electromagnetic curvature.

R2D already supplies the natural source owner.

Charge is not introduced as primitive material substance.

It is the physical read of an orientation-sensitive coupling that survives recursive replacement:

$$ q=\sigma|q|,\qquad\sigma=\pm1. $$

The local sign records retained orientation.

The magnitude records coupling strength.

A continuum electromagnetic source therefore begins not with an abstract current field, but with the
physical distribution of retained oriented coupling.

Let

$$\rho_q(x,t)$$

be the continuum read of net oriented coupling per projected spatial volume.

For a region Ω,

$$ Q_\Omega=\int_\Omega\rho_q\,d^3x$$

If this coupling classification is retained under boundary-preserving electromagnetic evolution, the charge
contained in a fixed region can change only through transfer across its enclosing boundary.

Define that oriented flux by

$$\mathbf J_q$$

Then

$$\frac{d}{dt}\int_\Omega\rho_q\,d^3x=-\oint_{\partial\Omega}\mathbf J_q\cdot d\mathbf S$$

<!-- source_pdf_page: 2624 -->

The divergence theorem gives the local continuity relation

$$ \frac{\partial\rho_q}{\partial t}+\nabla\cdot J_q=0. $$

After space-time calibration, define the four-current

$$ J^\mu=(c\rho_q,J_q). $$

Then:

$$\partial_\mu J^\mu=0$$

The four-current is therefore the mature space-time read of transported retained orientation.

It is not primitively a count of persisting particles.

Particle number may change while the net oriented coupling remains conserved.

The same conservation condition arises independently from gauge consistency.

At the level where charged matter has been represented by an effective source current, its coupling to the
electromagnetic connection has the form

$$ S_{\mathrm{src}}=-\int J^\mu A_{\mathrm{EM},\mu}\,d^4x$$

up to the chosen space-time normalization convention.

Under

$$ A_{\mathrm{EM},\mu}\to A_{\mathrm{EM},\mu}+\partial_\mu\chi$$

the change in source action is

$$\delta S_{\mathrm{src}}=-\int J^\mu\partial_\mu\chi\,d^4x$$

After integration by parts,

$$\delta S_{\mathrm{src}}=\int\chi\,\partial_\mu J^\mu\,d^4x$$

apart from the boundary contribution.

Thus, for appropriate boundary conditions, local gauge invariance of the effective source coupling requires

<!-- source_pdf_page: 2625 -->

$$ \partial_\mu J^\mu=0. $$

The same conservation law has therefore appeared twice:

> retained oriented coupling → current continuity,

and

> local gauge consistency → current continuity.

Current conservation, however, still does not determine how much electromagnetic curvature is supported
by a given current.

A further physical relation is required.

Addendum 79 supplied the gauge-invariant curvature

$$ F_{\mu\nu}$$

The leading local scalar support measure must be constructed from this curvature rather than from the
gauge-dependent connection.

If the support read is insensitive to global reversal

$$ F_{\mu\nu}\to-F_{\mu\nu}$$

its leading nontrivial local scalar is even in curvature:

$$ F_{\mu\nu}F^{\mu\nu}$$

This does not follow from gauge invariance alone.

Higher-order gauge-invariant curvature functionals are possible.

But if the mature physical projection is required to be:

- local;
- Lorentz invariant;
- gauge invariant;
- parity even;
- lowest order in curvature;
- and linear in its resulting source field equation,

then the leading bulk curvature-support functional is quadratic:

$$ S_{\mathrm{curv}}=-\frac{\kappa_{\mathrm{EM}}}{4}\int F_{\mu\nu}F^{\mu\nu}\,d^4x. $$

<!-- source_pdf_page: 2626 -->

Here

$$\kappa_{\mathrm{EM}}$$

is the physical calibration converting curvature magnitude into action density.

The complete leading-order connection-plus-source action is therefore

$$ S_{\mathrm{EM}}=\int\left[-\frac{\kappa_{\mathrm{EM}}}{4}F_{\mu\nu}F^{\mu\nu}-J^\mu A_{\mathrm{EM},\mu}\right]d^4x$$

Vary the electromagnetic connection.

Since

$$ F_{\mu\nu}=\partial_\mu A_{\mathrm{EM},\nu}-\partial_\nu A_{\mathrm{EM},\mu}$$

its variation is

$$\delta F_{\mu\nu}=\partial_\mu\delta A_{\mathrm{EM},\nu}-\partial_\nu\delta A_{\mathrm{EM},\mu}$$

After integration by parts,

$$\delta S_{\mathrm{EM}}=\int\left[\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}-J^\nu\right]\delta A_{\mathrm{EM},\nu}\,d^4x$$

Stationarity for arbitrary connection variation requires

$$ \kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}=J^\nu. $$

Therefore:

$$\partial_\mu F^{\mu\nu}=\kappa_{\mathrm{EM}}^{-1}J^\nu$$

The conventional electromagnetic calibration is

$$ \kappa_{\mathrm{EM}}=\frac{1}{\mu_0}. $$

Hence:

$$ \partial_\mu F^{\mu\nu}=\mu_0J^\nu. $$

These are the Maxwell source equations.

Together with

<!-- source_pdf_page: 2627 -->

$$ dF=0$$

the full Maxwell system has now been separated into two logically different structures:

> connection geometry → dF = 0,

and

> conserved source support + curvature dynamics → d∗F ∝ J.

The distinction is deeper than notation.

The homogeneous equation

$$ dF=0$$

requires no metric.

It follows from the local existence of a connection.

The source equation involves the dual curvature

$${*F}$$

The Hodge dual requires physical space-time metric structure.

Thus electromagnetic source dynamics enters one projection layer later than connection curvature.

The curvature tells how local phase comparison fails to close.

The metric tells how that curvature is converted into a support relation.

The conserved oriented current then supplies the physical source.

This addendum therefore does not claim that primitive R2D counting alone has derived the Maxwell action.

The quadratic curvature-support functional remains a physical bridge.

What has been shown is that once:

1. retained orientation supplies charge;
2. its transport supplies a conserved current;
3. local phase comparison supplies the U(1) connection;
4. connection curvature supplies F;
5. the leading local Lorentz- and gauge-invariant parity-even linear curvature dynamics is selected;

the Maxwell source equations follow.

<!-- source_pdf_page: 2628 -->

The central statement is:

The Maxwell source equations do not begin with primitive charged particles producing primitive electric and magnetic fields. R2D first identifies charge as a retained orientation-sensitive coupling. The continuum transport of that retained classification is read as a conserved four-current $\partial_\mu J^\mu=0$. Local gauge consistency independently requires the same current conservation. Once electromagnetic curvature $\mathcal F_{\mathrm{EM}}$ has been established, the leading local Lorentz- and gauge-invariant parity-even curvature-support functional is quadratic in $F_{\mu\nu}F^{\mu\nu}$. Stationarity of that curvature support in the presence of the conserved oriented current yields $\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}=J^\nu$. Conventional electromagnetic calibration $\kappa_{\mathrm{EM}}=1/\mu_0$ gives the Maxwell source equations. Electromagnetic source curvature is therefore downstream of conserved oriented coupling.

And hence:

> conserved oriented coupling occurs before the Maxwell source equations.

## 1. Addendum 79 Left One Maxwell Problem Open

Connection geometry gave

$$ dF=0$$

But it did not give

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

## 2. The Missing Object Is the Source

A curvature relation alone does not identify what physically supports its magnitude.

R2D must therefore assign boundary ownership to

$$ J^\mu$$

## 3. Charge Already Has R2D Ownership

A charge-bearing boundary retains an orientation distinction through recursive replacement.

Its physical coupling read is

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

<!-- source_pdf_page: 2629 -->

## 4. Sign and Magnitude Have Different Meanings

$$\sigma=\text{retained orientation class}$$

while

$$|q|=\text{coupling magnitude}$$

## 5. Charge Is Therefore Not Primitive Particle Substance

The physical charge coordinate reads a retained relational classification.

A projected particle can carry that classification without defining its primitive origin.

## 6. Particle Number and Charge Classification Must Remain Distinct

A particle-antiparticle pair may be created or annihilated while net charge remains unchanged.

Therefore:

charge conservation≠particle-number conservation.

## 7. Move From Individual Coupling to an Enclosing Source Read

Let

$$\rho_q(x,t)$$

denote net oriented coupling per projected spatial volume.

## 8. This Density Is Already a Physical Projection

Primitive R2D does not begin with continuous spatial volume.

The density is defined only after the continuum spatial projection has been introduced.

<!-- source_pdf_page: 2630 -->

## 9. Total Oriented Coupling in a Region Is

$$ Q_\Omega=\int_\Omega\rho_q\,d^3x$$

## 10. Fix the Enclosing Charge Domain

Suppose the relevant electromagnetic boundary is preserved.

Then the net retained orientation class cannot simply disappear from that domain.

## 11. Local Amount Can Still Change

The amount inside a subregion can change if oriented coupling crosses its enclosing boundary.

## 12. Define the Oriented Flux

Let

$$\mathbf J_q$$

be the physical spatial flux density of retained oriented coupling.

## 13. Conservation Over a Fixed Region Gives

$$\frac{d}{dt}\int_\Omega\rho_q\,d^3x=-\oint_{\partial\Omega}\mathbf J_q\cdot d\mathbf S$$

## 14. The Minus Sign Records Outward Loss

Positive outward flux reduces the oriented coupling retained inside the region.

## 15. Apply the Divergence Theorem

$$\oint_{\partial\Omega}\mathbf J_q\cdot d\mathbf S=\int_\Omega\nabla\cdot\mathbf J_q\,d^3x$$

<!-- source_pdf_page: 2631 -->

## 16. Therefore

$$\int_\Omega\left[\frac{\partial\rho_q}{\partial t}+\nabla\cdot\mathbf J_q\right]d^3x=0$$

## 17. Since the Region Is Arbitrary

$$\frac{\partial\rho_q}{\partial t}+\nabla\cdot\mathbf J_q=0$$

This is the charge continuity equation.

## 18. The Continuity Equation Is the Continuum Read of Retained Orientation

It says that local oriented coupling can be redistributed without being locally created or destroyed inside a
boundary-preserving source domain.

## 19. Introduce the Four-Current

After physical space-time calibration,

$$ J^\mu=(c\rho_q,\mathbf J_q)$$

## 20. Then

$$\partial_\mu J^\mu=0$$

## 21. Four-Current Is Therefore a Transport Coordinate

It is the space-time read of the distribution and flow of retained orientation.

## 22. It Is Not Primitive Ontology

The current is a mature continuum coordinate.

<!-- source_pdf_page: 2632 -->

The retained classification comes first.

## 23. Gauge Consistency Reaches the Same Conservation Law

Addendum 78 gave the local phase-reference transformation

$$ A_{\mathrm{EM},\mu}\to A_{\mathrm{EM},\mu}+\partial_\mu\chi$$

## 24. Couple an Effective Source to the Connection

At the continuum level write

$$ S_{\mathrm{src}}=-\int J^\mu A_{\mathrm{EM},\mu}\,d^4x$$

## 25. Transform the Connection

The change is

$$\delta A_{\mathrm{EM},\mu}=\partial_\mu\chi$$

Therefore:

$$\delta S_{\mathrm{src}}=-\int J^\mu\partial_\mu\chi\,d^4x$$

## 26. Integrate by Parts

$$\delta S_{\mathrm{src}}=\int\chi\partial_\mu J^\mu\,d^4x-\int_{\partial M}\chi J^\mu\,d\Sigma_\mu$$

## 27. Under Appropriate Boundary Conditions

The boundary contribution vanishes.

Thus:

<!-- source_pdf_page: 2633 -->

$$\delta S_{\mathrm{src}}=\int\chi\partial_\mu J^\mu\,d^4x$$

## 28. Local Gauge Invariance Requires

$$\partial_\mu J^\mu=0$$

## 29. Two Independent Physical Requirements Now Converge

From retained orientation:

$$\partial_\mu J^\mu=0$$

From local gauge consistency:

$$\partial_\mu J^\mu=0$$

## 30. This Is Not Yet the Maxwell Source Law

Current conservation constrains the source.

It does not determine the curvature created or supported by that source.

## 31. Addendum 79 Supplies the Curvature

$$ F_{\mu\nu}=\partial_\mu A_{\mathrm{EM},\nu}-\partial_\nu A_{\mathrm{EM},\mu}$$

## 32. The Curvature Is Gauge Invariant

$$ F'_{\mu\nu}=F_{\mu\nu}$$

Thus physical curvature-support dynamics should be constructed from F , not from a gauge-dependent
local potential value.

<!-- source_pdf_page: 2634 -->

## 33. Ask for the Simplest Local Curvature Support Scalar

A local scalar must contract the tensor indices.

The leading parity-even quadratic possibility is

$$ F_{\mu\nu}F^{\mu\nu}$$

## 34. This Is Even Under Orientation Reversal

If

$$ F_{\mu\nu}\to-F_{\mu\nu}$$

then

$$ F_{\mu\nu}F^{\mu\nu}\to F_{\mu\nu}F^{\mu\nu}$$

## 35. This Matches the General R2D Orientation Logic

An orientation-sensitive coordinate can reverse sign while an orientation-insensitive scalar support read
remains even.

## 36. Gauge Invariance Alone Does Not Uniquely Select Maxwell Theory

Higher-order invariants such as

$$(F_{\mu\nu}F^{\mu\nu})^2$$

are possible.

They produce nonlinear electrodynamics.

## 37. There Is Also a Dual Curvature Scalar

In four dimensions one may construct

<!-- source_pdf_page: 2635 -->

Fμν F μν .

For ordinary Abelian electromagnetism with constant coefficient, this is parity odd and contributes a
boundary/topological term rather than the usual Maxwell bulk field equation.

## 38. Therefore the Maxwell Functional Requires Additional Conditions

Select the leading theory to be:

- local;
- gauge invariant;
- Lorentz invariant;
- parity even;
- lowest nontrivial order in curvature;
- and linear in the resulting bulk field equation.

## 39. Under Those Conditions the Leading Curvature Functional Is

$$ S_{\mathrm{curv}}=-\frac{\kappa_{\mathrm{EM}}}{4}\int F_{\mu\nu}F^{\mu\nu}\,d^4x$$

## 40. The Calibration κEM Is Not Yet Primitive

It converts electromagnetic curvature into physical action density.

R2D has not yet derived its numerical value from primitive counts.

## 41. This Distinction Is Essential

The structural form

$$ F^2$$

and its empirical physical normalization are separate questions.

<!-- source_pdf_page: 2636 -->

## 42. Combine Curvature Support and Source Coupling

$$ S_{\mathrm{EM}}=\int\left[-\frac{\kappa_{\mathrm{EM}}}{4}F_{\mu\nu}F^{\mu\nu}-J^\mu A_{\mathrm{EM},\mu}\right]d^4x$$

## 43. The Two Terms Have Different Ownership

The first describes the physical support cost of connection curvature.

The second describes coupling of retained oriented source structure to the connection.

## 44. Vary the Connection

Let

$$ A_{\mathrm{EM},\nu}\to A_{\mathrm{EM},\nu}+\delta A_{\mathrm{EM},\nu}$$

## 45. Then

$$\delta F_{\mu\nu}=\partial_\mu\delta A_{\mathrm{EM},\nu}-\partial_\nu\delta A_{\mathrm{EM},\mu}$$

## 46. Vary the Curvature Term

Using the antisymmetry

$$ F_{\mu\nu}=-F_{\nu\mu}$$

the curvature contribution becomes

$$\delta S_{\mathrm{curv}}=-\kappa_{\mathrm{EM}}\int F^{\mu\nu}\partial_\mu\delta A_{\mathrm{EM},\nu}\,d^4x$$

## 47. Integrate by Parts

Ignoring the boundary term,

<!-- source_pdf_page: 2637 -->

$$\delta S_{\mathrm{curv}}=\kappa_{\mathrm{EM}}\int\partial_\mu F^{\mu\nu}\delta A_{\mathrm{EM},\nu}\,d^4x$$

## 48. The Source Variation Is

$$\delta S_{\mathrm{src}}=-\int J^\nu\delta A_{\mathrm{EM},\nu}\,d^4x$$

## 49. Therefore

$$\delta S_{\mathrm{EM}}=\int\left[\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}-J^\nu\right]\delta A_{\mathrm{EM},\nu}\,d^4x$$

## 50. Stationarity Requires

$$\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}=J^\nu$$

## 51. Therefore

$$\partial_\mu F^{\mu\nu}=\kappa_{\mathrm{EM}}^{-1}J^\nu$$

This is the generic leading source-curvature relation.

## 52. Supply the Conventional Electromagnetic Calibration

In the standard SI-compatible normalization,

$$\kappa_{\mathrm{EM}}=\frac{1}{\mu_0}$$

Thus:

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

<!-- source_pdf_page: 2638 -->

## 53. This Is the Inhomogeneous Maxwell Equation

The two remaining Maxwell equations are its space-time components.

## 54. The Temporal Component Gives Gauss's Electric Law

$$\nabla\cdot\mathbf E=\frac{\rho_q}{\epsilon_0}$$

## 55. The Spatial Components Give the Ampère–Maxwell Law

$$\nabla\times\mathbf B-\frac{1}{c^2}\frac{\partial\mathbf E}{\partial t}=\mu_0\mathbf J_q$$

## 56. The Physical Calibration Relates

$$\mu_0\epsilon_0=\frac{1}{c^2}$$

This relation is part of the mature electromagnetic physical mapping.

Its numerical normalization is not derived here from primitive R2D counts.

## 57. Addendum 79 Already Supplied the Other Two Equations

$$\nabla\cdot\mathbf B=0$$

and

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

## 58. The Maxwell System Is Therefore Split Into Two Logical Halves

Connection identity:

$$ dF=0$$

<!-- source_pdf_page: 2639 -->

Source dynamics:

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

## 59. These Halves Should Not Be Collapsed

The first follows from

$$ F=dA$$

The second requires a curvature-support law.

## 60. Differential Forms Make the Distinction Especially Clear

The homogeneous equation is

$$ dF=0$$

The source equation is

$$ d{*F}=\mu_0{*J}$$

with the precise current-form notation depending on convention.

## 61. The Hodge Dual Introduces New Structure

The operation

$${*F}$$

requires a metric and orientation on physical space-time.

Thus:

$$ dF=0$$

is metric independent,

whereas

$$ d{*F}\propto J$$

depends on the physical space-time geometry used to define the dual.

<!-- source_pdf_page: 2640 -->

## 62. This Is an Important R2D Boundary Distinction

Connection curvature exists before its energetic/support read.

Metric structure enters when curvature is converted into the source-response relation.

## 63. The Source Equation Therefore Lives One Projection Layer Later

The logical order is:

> phase comparison → A → F

before

> metric dual + source current → Maxwell source equation.

## 64. Current Conservation Is Also Built Into the Source Equation

Take

$$\partial_\nu$$

of

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

Then:

$$\partial_\nu\partial_\mu F^{\mu\nu}=\mu_0\partial_\nu J^\nu$$

## 65. The Left-Hand Side Vanishes

The derivative pair is symmetric under

$$\mu\leftrightarrow\nu$$

while

$$ F^{\mu\nu}$$

is antisymmetric.

<!-- source_pdf_page: 2641 -->

Therefore:

$$\partial_\nu\partial_\mu F^{\mu\nu}=0$$

## 66. Hence

$$\partial_\nu J^\nu=0$$

## 67. Three Independent Structures Now Agree

Retained orientation transport:

$$\partial_\mu J^\mu=0$$

Gauge invariance of source coupling:

$$\partial_\mu J^\mu=0$$

Antisymmetric curvature source equation:

$$\partial_\mu J^\mu=0$$

## 68. This Convergence Is the Central Consistency Check

The same conserved-current structure is required by:

- source ontology;
- gauge representation;
- and curvature dynamics.

## 69. Gauss's Law Gives an Area-First Source Read

Integrate

$$\nabla\cdot\mathbf E=\frac{\rho_q}{\epsilon_0}$$

over an enclosing volume.

<!-- source_pdf_page: 2642 -->

## 70. Apply the Divergence Theorem

$$\oint_{\partial V}\mathbf E\cdot d\mathbf S=\frac{Q_V}{\epsilon_0}$$

## 71. The Enclosed Source Is Read Through Boundary Flux

This is directly consistent with the R2D area-first architecture.

The enclosing area carries the physical flux read.

## 72. Under Spherical Symmetry

Let the enclosing physical boundary have area

$$ A=4\pi r_A^2$$

Then uniform radial flux gives

$$ EA=\frac{Q}{\epsilon_0}$$

## 73. Therefore

$$ E=\frac{Q}{\epsilon_0A}$$

Only after defining the area-derived radius

$$ r_A=\sqrt{\frac{A}{4\pi}}$$

does this become

$$ E(r_A)=\frac{Q}{4\pi\epsilon_0r_A^2}$$

<!-- source_pdf_page: 2643 -->

## 74. The Electromagnetic Inverse Square Is Therefore Area Derived

Under spherical symmetry,

$$ E\propto A^{-1}$$

comes before

$$ E\propto r_A^{-2}$$

## 75. This Mirrors the Earlier Gravitational Inversion

The radial coordinate is a later representation of an enclosing area relation.

The inverse-square appearance follows from that area geometry.

## 76. Coulomb Force Comes Later Still

For a test coupling qt ,

$$ F=q_tE$$

Under spherical symmetry,

$$ F=\frac{q_tQ}{4\pi\epsilon_0r_A^2}$$

## 77. Force Is Therefore Not the Beginning of Electromagnetism

The order is

> retained oriented source

> ↓

> curvature support

> ↓

> boundary flux

> ↓

<!-- source_pdf_page: 2644 -->

field read

> ↓

> force.

## 78. The Maxwell Action Is a Physical Bridge, Not Yet a Primitive R2D Theorem

The quadratic support law

$$ F_{\mu\nu}F^{\mu\nu}$$

has not been derived solely from Part I counting axioms.

## 79. What Has Been Derived Is Its Position in the Architecture

It must occur after:

- closure phase;
- local phase comparison;
- connection;
- curvature;
- retained charge orientation;
- and conserved source current.

## 80. Maxwell Theory Is the Leading Curvature Dynamics Under Additional Physical Conditions

Within the class of local, Lorentz-invariant, gauge-invariant, parity-even, lowest-order linear theories,

$$ F^2$$

supplies the leading bulk curvature support.

## 81. Nonlinear Electrodynamics Is Not Excluded

Higher-order curvature terms may appear in other physical regimes.

Thus Maxwell dynamics is not being claimed as the only mathematically possible gauge-curvature theory.

<!-- source_pdf_page: 2645 -->

## 82. The Present Result Is Therefore Conditional but Strong

Given the experimentally realized leading electromagnetic curvature-support law, R2D identifies why its
source must be a conserved oriented current and how the Maxwell equations occupy the recursive
boundary architecture.

## 83. Principle — Charge Orientation Precedes Charge Current

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

comes before

$$ J^\mu$$

## 84. Principle — Current Is the Space-Time Read of Transported Retained Orientation

$$ J^\mu=(c\rho_q,\mathbf J_q)$$

## 85. Principle — Retained Source Classification Requires Continuity

$$\partial_\mu J^\mu=0$$

## 86. Principle — Gauge Consistency Requires the Same Continuity

For the effective source coupling

$$-J^\mu A_\mu$$

local gauge invariance requires

$$\partial_\mu J^\mu=0$$

## 87. Principle — Curvature Support Must Be Gauge Invariant

The leading local support functional depends on

<!-- source_pdf_page: 2646 -->

Fμν ,

not directly on gauge-dependent connection coordinates.

## 88. Principle — Maxwell Curvature Support Is Quadratic at Leading Order

Under the stated physical assumptions,

$$ S_{\mathrm{curv}}=-\frac{\kappa_{\mathrm{EM}}}{4}\int F_{\mu\nu}F^{\mu\nu}\,d^4x$$

## 89. Principle — Conserved Source Coupling Completes the Leading Action

$$ S_{\mathrm{EM}}=\int\left[-\frac{\kappa_{\mathrm{EM}}}{4}F^2-J\cdot A\right]d^4x$$

## 90. Principle — Stationarity Gives the Source-Curvature Equation

$$\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}=J^\nu$$

## 91. Principle — Electromagnetic Calibration Gives Maxwell

$$\kappa_{\mathrm{EM}}=\frac{1}{\mu_0}$$

Therefore:

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

## 92. Principle — Maxwell Geometry and Maxwell Dynamics Are Different

$$ dF=0$$

comes from connection geometry.

<!-- source_pdf_page: 2647 -->

$$ d{*F}=\mu_0{*J}$$

comes from source-supported curvature dynamics.

## 93. Principle — Source Dynamics Requires the Metric Read

The Hodge dual

$${*F}$$

requires physical metric structure.

Thus source dynamics is downstream of both connection geometry and space-time projection.

## 94. Principle — Gauss Flux Is Area First

$$ E=\frac{Q}{\epsilon_0A}$$

precedes the spherical radial representation

$$ E(r_A)=\frac{Q}{4\pi\epsilon_0r_A^2}$$

## 95. Logical Status

Canonical R2D

Charge is a retained orientation-sensitive coupling:

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

Addendum 78

Local phase comparison gives the electromagnetic connection.

Addendum 79

Connection curvature gives

$$ F=dA$$

<!-- source_pdf_page: 2648 -->

and the homogeneous Maxwell structure

$$ dF=0$$

New Continuum Source Read

$$ J^\mu=(c\rho_q,\mathbf J_q)$$

Conditional Conservation Mapping

If retained charge orientation is preserved under the relevant boundary-preserving electromagnetic
evolution,

$$\partial_\mu J^\mu=0$$

Independent Gauge Requirement

Gauge invariance of the effective source coupling likewise requires

$$\partial_\mu J^\mu=0$$

Additional Physical Assumptions

The leading curvature theory is taken to be:

- local;
- Lorentz invariant;
- gauge invariant;
- parity even;
- lowest order in curvature;
- and linear in its bulk source equation.

Leading Curvature-Support Functional

$$ S_{\mathrm{curv}}=-\frac{\kappa_{\mathrm{EM}}}{4}\int F_{\mu\nu}F^{\mu\nu}\,d^4x$$

Source Coupling

$$ S_{\mathrm{src}}=-\int J^\mu A_\mu\,d^4x$$

Derived Source-Curvature Law

$$\partial_\mu F^{\mu\nu}=\kappa_{\mathrm{EM}}^{-1}J^\nu$$

<!-- source_pdf_page: 2649 -->

Empirical Electromagnetic Calibration

$$\kappa_{\mathrm{EM}}=\frac{1}{\mu_0}$$

Maxwell Source Equations

$$\nabla\cdot\mathbf E=\frac{\rho_q}{\epsilon_0}$$

$$\nabla\times\mathbf B-\frac{1}{c^2}\frac{\partial\mathbf E}{\partial t}=\mu_0\mathbf J_q$$

Combined With Addendum 79

$$\nabla\cdot\mathbf B=0$$

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

Not Yet Established

This addendum does not yet derive from primitive R2D counting alone:

- the quadratic curvature functional Fμν F μν ;
- the numerical values of ϵ0 or μ0 ;
- the elementary charge magnitude;
- charge quantization;
- the full matter-field current from primitive R2D occupancy;
- nonlinear electromagnetic corrections;
- the Standard Model gauge structure;
- or electromagnetic radiation quantization.

These remain downstream physical bridges.

## 96. The Complete Maxwell Architecture

Retained orientation survives recursive replacement:

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

Its continuum distribution is read as:

> ↓

$$\rho_q(x,t)$$

Transport of that orientation gives:

<!-- source_pdf_page: 2650 -->

⇓

$$\mathbf J_q$$

Together:

> ↓

$$ J^\mu$$

Retention requires:

> ↓

$$\partial_\mu J^\mu=0$$

Independently, local gauge consistency requires:

> ↓

$$\partial_\mu J^\mu=0$$

Local phase comparison supplies:

> ↓

$$ A_\mu$$

Connection curvature gives:

> ↓

$$ F^{\mu\nu}$$

Geometry supplies:

> ↓

$$ dF=0$$

The leading curvature-support functional gives:

> ↓

$$\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}=J^\nu$$

Electromagnetic calibration gives:

> ↓

<!-- source_pdf_page: 2651 -->

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

The frame decomposition then yields the full Maxwell system.

Electromagnetic source equations are therefore the end of the conserved-source/curvature-support chain
rather than its beginning.

## 97. Conclusion

Maxwell's equations are usually presented as four coequal laws governing electric and magnetic fields.

R2D reveals that they have different logical origins.

The homogeneous pair,

$$\nabla\cdot\mathbf B=0$$

and

$$\nabla\times\mathbf E+\frac{\partial\mathbf B}{\partial t}=0$$

follow from connection geometry.

Once local phase comparison requires a gauge connection,

$$ A$$

its curvature is

$$ F=dA$$

Exterior differentiation then gives

$$ dF=0$$

No electromagnetic source has yet been introduced.

The remaining two equations require a different structure.

R2D begins that structure with retained orientation.

A charge-bearing boundary preserves an orientation-sensitive coupling class:

$$ q=\sigma|q|,\qquad\sigma=\pm1$$

<!-- source_pdf_page: 2652 -->

After continuum spatial projection, the local distribution of this retained coupling is read as

$$\rho_q(x,t)$$

Its transport is read as

$$\mathbf J_q$$

Together they define

$$ J^\mu=(c\rho_q,\mathbf J_q)$$

Preservation of the source classification requires

$$\partial_\mu J^\mu=0$$

Local gauge consistency independently demands the same equation.

Thus electromagnetic source current is not an arbitrary term appended to field theory.

Its conserved structure is exactly what is expected of transported retained orientation.

But current conservation alone does not determine electromagnetic curvature.

A physical curvature-support law is still required.

For the experimentally realized leading local theory, impose locality, Lorentz invariance, gauge invariance,
parity-even scalar support, lowest curvature order, and linear bulk dynamics.

The leading functional is then

$$ S_{\mathrm{curv}}=-\frac{\kappa_{\mathrm{EM}}}{4}\int F_{\mu\nu}F^{\mu\nu}\,d^4x$$

Couple the retained source through

$$ S_{\mathrm{src}}=-\int J^\mu A_{\mathrm{EM},\mu}\,d^4x$$

Stationarity gives

$$\kappa_{\mathrm{EM}}\partial_\mu F^{\mu\nu}=J^\nu$$

After the physical electromagnetic calibration

<!-- source_pdf_page: 2653 -->

$$\kappa_{\mathrm{EM}}=\frac{1}{\mu_0}$$

this becomes

$$\partial_\mu F^{\mu\nu}=\mu_0J^\nu$$

Its space-time components are

$$\nabla\cdot\mathbf E=\frac{\rho_q}{\epsilon_0}$$

and

$$\nabla\times\mathbf B-\frac{1}{c^2}\frac{\partial\mathbf E}{\partial t}=\mu_0\mathbf J_q$$

Combined with Addendum 79, the complete Maxwell system is recovered.

The source equation contains another important clue.

Its differential-form representation is

$$ d{*F}=\mu_0{*J}$$

Unlike

$$ dF=0$$

this relation requires the Hodge dual.

The Hodge dual requires physical metric structure.

Thus the homogeneous Maxwell geometry and the source-supported Maxwell dynamics do not arise at the
same projection level.

First comes phase comparison.

Then connection.

Then curvature.

Then physical metric duality and conserved source support.

This ordering also sharpens Gauss's law.

Integrating

<!-- source_pdf_page: 2654 -->

$$\nabla\cdot\mathbf E=\rho_q/\epsilon_0$$

gives

$$\oint\mathbf E\cdot d\mathbf S=\frac{Q}{\epsilon_0}$$

For an isotropic enclosing boundary of area A,

$$ E=\frac{Q}{\epsilon_0A}$$

Only after defining

$$ r_A=\sqrt{\frac{A}{4\pi}}$$

does this become

$$ E(r_A)=\frac{Q}{4\pi\epsilon_0r_A^2}$$

The inverse-square law is therefore a later radial representation of an area-flux relation.

The source comes first.

The enclosing boundary area comes next.

The radial inverse square comes afterward.

The central statement is therefore:

the Maxwell source equations do not begin with primitive particles emitting primitive fields. Charge first appears as a retained orientation-sensitive coupling. Its continuum transport is read as a conserved current. Gauge consistency independently requires the same current conservation. Connection curvature supplies the gauge-invariant electromagnetic relation, while a separate curvature-support law determines how conserved oriented current sources that curvature. Under the leading local Lorentz- and gauge-invariant Maxwell support functional, variation yields the source equations. Electromagnetic source curvature is therefore downstream of conserved oriented coupling.

And hence:

> conserved oriented coupling occurs before the Maxwell source equations.
