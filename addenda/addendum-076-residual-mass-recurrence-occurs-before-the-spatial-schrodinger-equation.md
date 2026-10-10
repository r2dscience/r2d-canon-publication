---
r2d_id: addendum-076
title: Addendum 76 — Residual Mass Recurrence Occurs Before the Spatial Schrödinger Equation
subtitle: Persistent Compton Recurrence, Translation Phase, and the Nonrelativistic Residual Generator
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 76
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2505
pdf_page_end: 2535
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

# Addendum 76 — Residual Mass Recurrence Occurs Before the Spatial Schrödinger Equation

*Persistent Compton Recurrence, Translation Phase, and the Nonrelativistic Residual Generator*

## Abstract

<!-- source_pdf_page: 2505 -->

The nonrelativistic Schrödinger equation is ordinarily written

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

for a free massive quantum state.

The equation appears to combine several independent quantum postulates:

- complex temporal evolution;
- Planck's constant;
- particle mass;
- spatial differentiation;
- and the quadratic kinetic-energy relation.

The preceding R2D addenda have separated these structures.

Addendum 71 identified a persistent local mass recurrence with physical calibration

$$ mc^2=\hbar\omega_M, $$

and corresponding reduced Compton recurrence length

$$\bar\lambda_M=\frac{c}{\omega_M}=\frac{\hbar}{mc}$$

Addendum 74 showed that boundary-preserving quantum recurrence is represented by a self-adjoint
temporal generator and, after physical clock and energetic calibration,

$$ i\hbar\frac{\partial}{\partial t}|\Psi\rangle=H|\Psi\rangle$$

Addendum 75 showed that boundary-preserving spatial translation has inverse-length generator

$$ \mathbf K=-i\nabla, $$

<!-- source_pdf_page: 2506 -->

and, after momentum calibration,

$$\mathbf P=-i\hbar\nabla$$

The remaining problem is to identify the relation between persistent mass recurrence and spatial
translation recurrence.

For a free massive physical state, the mature relativistic energy-momentum relation is

$$ E^2=m^2c^4+p^2c^2. $$

Using

$$ E=\hbar\omega$$

$$ mc^2=\hbar\omega_M$$

and

$$ p=\hbar k$$

this becomes

$$ \omega^2=\omega_M^2+c^2k^2. $$

Thus:

$$\frac\omega{\omega_M}=\sqrt{1+(\bar\lambda_M k)^2}$$

Define the dimensionless translation-to-mass recurrence coordinate

$$ \eta\equiv\bar\lambda_M k=\frac{p}{mc}. $$

Then:

$$\frac\omega{\omega_M}=\sqrt{1+\eta^2}$$

The full physical recurrence of the massive boundary therefore contains the persistent mass recurrence

$$\omega_M$$

plus a residual recurrence associated with its translational state.

Define

<!-- source_pdf_page: 2507 -->

ωres ≡ ω − ωM .

Then exactly,

$$\frac{\omega_{\mathrm{res}}}{\omega_M}=\sqrt{1+\eta^2}-1$$

The corresponding physical energetic read is

$$ E_{\mathrm{res}}=\hbar\omega_{\mathrm{res}}=E-mc^2. $$

In the nonrelativistic recurrence-separation regime

$$\eta=\frac{p}{mc}=\bar\lambda_M k\ll1$$

one has

$$\sqrt{1+\eta^2}=1+\frac{\eta^2}{2}-\frac{\eta^4}{8}+\cdots$$

Therefore:

$$\omega_{\mathrm{res}}=\frac12\omega_M\eta^2-\frac18\omega_M\eta^4+\cdots$$

To leading order,

$$ \omega_{\mathrm{res}}\approx\frac{\hbar k^2}{2m}. $$

Thus:

$$ E_{\mathrm{res}}\approx\frac{p^2}{2m}$$

The familiar nonrelativistic kinetic energy is therefore the leading physical energy read of recurrence
remaining after the persistent mass recurrence is separated from the total phase evolution.

This distinction becomes explicit at the state level.

Write the complete massive quantum state as

$$ \Psi(x,t)=e^{-i\omega_Mt}\psi(x,t). $$

Using

<!-- source_pdf_page: 2508 -->

$$\omega_M=\frac{mc^2}{\hbar},\qquad\Psi(\mathbf x,t)=e^{-imc^2t/\hbar}\psi(\mathbf x,t)$$

The factor

$$ e^{-imc^2t/\hbar}$$

is not discarded ontology.

It is the physical phase representation of the persistent mass recurrence.

The residual function

$$\psi(\mathbf x,t)$$

carries the slower recurrence relative to that persistent closure.

Substitution into the abstract quantum evolution equation gives

$$ i\hbar\frac{\partial\psi}{\partial t}=(H-mc^2)\psi$$

For a free positive-energy massive state,

$$ H=\sqrt{m^2c^4+c^2\mathbf P^2}. $$

Therefore the exact residual generator is

$$ H_{\mathrm{res}}=\sqrt{m^2c^4+c^2\mathbf P^2}-mc^2. $$

Expanding for

$$\mathbf P^2\ll m^2c^2$$

gives

$$ H_{\mathrm{res}}=\frac{\mathbf P^2}{2m}-\frac{\mathbf P^4}{8m^3c^2}+\cdots$$

To leading order,

$$ H_{\mathrm{res}}\approx\frac{\mathbf P^2}{2m}. $$

Addendum 75 supplies

<!-- source_pdf_page: 2509 -->

$$ \mathbf P=-i\hbar\nabla. $$

Hence:

$$ \mathbf P^2=-\hbar^2\nabla^2. $$

Therefore:

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi. $$

The free spatial Schrödinger equation follows.

The R2D interpretation is therefore different from the usual starting point.

The Schrödinger equation does not govern the complete recurrence of the massive boundary.

The complete physical phase includes the much faster persistent mass recurrence

$$ \omega_M=\frac{mc^2}{\hbar}. $$

Schrödinger dynamics describes the slow residual phase evolution after that boundary-native mass
recurrence has been factored from the physical representation.

The nonrelativistic limit is consequently a recurrence-separation condition:

$$\bar\lambda_M k\ll1$$

Equivalently,

$$ p\ll mc$$

or, using the full Compton wavelength

$$\lambda_M=\frac{h}{mc}$$

and the translation wavelength

$$ k=\frac{2\pi}{\lambda},\qquad\lambda\gg\lambda_M$$

The Schrödinger regime is therefore the physical regime in which spatial translation recurrence is weak
relative to persistent mass recurrence.

This directly connects the spatial Schrödinger equation to the Compton analysis of Addendum 71.

<!-- source_pdf_page: 2510 -->

When

$$\lambda\gg\lambda_M$$

the two recurrence scales are strongly separated and the nonrelativistic residual equation is valid.

As

$$\lambda\to\lambda_M$$

or

$$ p\to mc$$

the separation fails.

Higher-order relativistic terms become readable, and the Schrödinger approximation ceases to be
sufficient.

The same recurrence ratio therefore controls both the appearance of the Compton regime and the
breakdown of the nonrelativistic Schrödinger projection.

The central statement is:

the nonrelativistic Schrödinger equation does not describe the total recurrence of a massive
quantum boundary. The boundary already possesses a persistent mass recurrence $\omega_M=mc^2/\hbar$. Relativistic
compatibility joins that recurrence to spatial translation recurrence through $\omega^2=\omega_M^2+c^2k^2$. Factoring the
 persistent mass phase from the full state leaves the residual generator $H_{\mathrm{res}}=\sqrt{m^2c^4+c^2\mathbf P^2}-mc^2$. In the strongly separated
regime $\eta=p/(mc)=\bar\lambda_M k\ll1$, that residual generator reduces to $H_{\mathrm{res}}\approx\mathbf P^2/(2m)$. With $\mathbf P=-i\hbar\nabla$, the free spatial Schrödinger
equation follows. Schrödinger dynamics is therefore the slow residual phase dynamics of a massive
> boundary relative to its much faster persistent mass recurrence.

And hence:

> residual mass recurrence occurs before the spatial Schrödinger equation.

## 1. Begin With the Persistent Mass Boundary

A massive quantum boundary possesses a persistent local recurrent closure.

Its physical phase-frequency read is

$$\omega_M$$

<!-- source_pdf_page: 2511 -->

## 2. Rest Energy Is a Later Calibration

The physical calibration is

$$ mc^2=\hbar\omega_M$$

Thus:

$$\omega_M=\frac{mc^2}{\hbar}$$

## 3. The Mass Recurrence Exists at Translational Rest

If the massive boundary has

$$\mathbf p=0$$

relative to an enclosing physical frame, its persistent recurrence does not vanish.

Therefore:

$$\mathbf p=0\not\Rightarrow\omega_M=0$$

## 4. Translational Rest and Recurrence Are Different Relations

Mechanical rest describes relation to an enclosing spatial frame.

Persistent mass recurrence belongs to the local retained boundary.

They must not be conflated.

## 5. The Reduced Compton Length Is the Spatial Read of Mass Recurrence

Define:

$$\bar\lambda_M=\frac{c}{\omega_M}$$

Therefore:

<!-- source_pdf_page: 2512 -->

ˉM = ℏ .

$$\bar\lambda_M=\frac{\hbar}{mc}$$

## 6. This Is Not a Material Radius

The reduced Compton length is a spatial place value assigned to persistent recurrence.

It does not define the geometric size of the massive object.

## 7. Addendum 74 Supplies Temporal Quantum Evolution

For the complete state,

$$ i\hbar\frac{\partial\Psi}{\partial t}=H\Psi$$

Here H is the physical temporal recurrence generator after energetic calibration.

## 8. Addendum 75 Supplies Spatial Translation

$$\mathbf P=-i\hbar\nabla$$

Spatial phase eigenstates satisfy

$$ p=\hbar k$$

## 9. Temporal and Spatial Recurrence Can Therefore Be Compared

The massive boundary carries:

$$\omega$$

as total temporal phase recurrence and

$$ k$$

as spatial translation phase recurrence.

<!-- source_pdf_page: 2513 -->

## 10. Relativistic Compatibility Supplies Their Physical Relation

For a free massive state,

$$ E^2=m^2c^4+p^2c^2$$

This is an imported mature relativistic physical relation.

It is not introduced as a primitive R2D identity.

## 11. Replace Energy and Momentum With Their Phase Reads

Using

$$ E=\hbar\omega$$

$$ mc^2=\hbar\omega_M$$

and

$$ p=\hbar k$$

one obtains

$$\hbar^2\omega^2=\hbar^2\omega_M^2+\hbar^2c^2k^2$$

## 12. Therefore

$$\omega^2=\omega_M^2+c^2k^2$$

This is the relativistic compatibility law written entirely in recurrence coordinates.

## 13. Normalize by the Persistent Mass Recurrence

Divide by

$$\omega_M^2$$

Then:

$$\left(\frac\omega{\omega_M}\right)^2=1+\frac{c^2k^2}{\omega_M^2}$$

<!-- source_pdf_page: 2514 -->

## 14. Use the Reduced Compton Recurrence Length

Because

$$\bar\lambda_M=\frac c{\omega_M},\qquad\frac\omega{\omega_M}=\sqrt{1+(\bar\lambda_Mk)^2}$$

## 15. Define the Translation-to-Mass Recurrence Ratio

Let

$$\eta\equiv\bar\lambda_Mk$$

## 16. This Is Also

$$\eta=\bar\lambda_Mk=\frac p{mc}$$

Thus η is dimensionless.

## 17. The Exact Recurrence Relation Is

$$\frac\omega{\omega_M}=\sqrt{1+\eta^2}$$

This is a particularly useful R2D form of the relativistic dispersion relation.

## 18. The Mass Recurrence Is Already Present in the Total Frequency

For

$$\eta=0$$

$$\omega=\omega_M$$

Thus translational rest still contains persistent phase recurrence.

<!-- source_pdf_page: 2515 -->

## 19. Define the Residual Recurrence

$$\omega_{\mathrm{res}}=\omega-\omega_M$$

## 20. Then

$$\frac{\omega_{\mathrm{res}}}{\omega_M}=\sqrt{1+\eta^2}-1$$

This relation is exact for the positive-energy free physical branch.

## 21. Residual Recurrence Is Not a New Primitive Closure

It is the difference between:

- total physical phase recurrence;
- persistent mass recurrence.

It is a derived physical coordinate.

## 22. Its Energetic Read Is

$$ E_{\mathrm{res}}=\hbar\omega_{\mathrm{res}}$$

Therefore:

$$ E_{\mathrm{res}}=E-mc^2$$

## 23. For a Free Massive Boundary, This Is Kinetic Energy

$$ K=E-mc^2$$

Thus kinetic energy is the physical energetic read of residual recurrence relative to persistent mass closure.

## 24. The Nonrelativistic Regime Is Small Relative Recurrence

Require:

$$\eta \ll 1$$

<!-- source_pdf_page: 2516 -->

Equivalently:

$$ p\ll mc$$

## 25. Expand the Exact Recurrence Relation

$$\sqrt{1+\eta^2}=1+\frac{\eta^2}{2}-\frac{\eta^4}{8}+O(\eta^6)$$

## 26. Therefore

$$\frac{\omega_{\mathrm{res}}}{\omega_M}=\frac{\eta^2}{2}-\frac{\eta^4}{8}+O(\eta^6)$$

## 27. The Leading Residual Recurrence Is

$$\omega_{\mathrm{res}}\approx\frac12\omega_M\eta^2$$

## 28. Substitute the Mass Recurrence

$$\omega_M=\frac{mc^2}{\hbar}$$

And

$$\eta=\frac{\hbar k}{mc}$$

## 29. Then

$$\omega_{\mathrm{res}}\approx\frac12\frac{mc^2}{\hbar}\frac{\hbar^2k^2}{m^2c^2}$$

Thus:

$$\omega_{\mathrm{res}}\approx\frac{\hbar k^2}{2m}$$

<!-- source_pdf_page: 2517 -->

## 30. Multiply by ℏ

$$ E_{\mathrm{res}}\approx\frac{\hbar^2k^2}{2m}$$

## 31. Since p = ℏk

$$ E_{\mathrm{res}}\approx\frac{p^2}{2m}$$

The nonrelativistic kinetic-energy law emerges as the leading residual recurrence read.

## 32. This Reverses the Usual Explanatory Order

R2D does not begin with

$$ K=\frac{p^2}{2m}$$

as a primitive mechanical law inserted into quantum theory.

It identifies it as the leading residual term of the full mass-plus-translation recurrence relation.

## 33. Now Separate the Persistent Mass Phase

Write

$$\Psi(\mathbf x,t)=e^{-i\omega_Mt}\psi(\mathbf x,t)$$

## 34. In Energy Units

$$\Psi(\mathbf x,t)=e^{-imc^2t/\hbar}\psi(\mathbf x,t)$$

## 35. This Factorization Has Physical Meaning

The factor

<!-- source_pdf_page: 2518 -->

$$ e^{-imc^2t/\hbar}$$

represents persistent mass recurrence.

It is not merely an arbitrary removable phase inserted for mathematical convenience.

## 36. The Residual Coordinate ψ Has Different Ownership

$$\psi$$

represents the slower phase relation relative to the persistent mass recurrence.

## 37. The Persistent Mass Recurrence Has Not Disappeared

Factoring it from the representation does not destroy or stop the local closure.

The complete physical state remains

$$\Psi$$

## 38. Apply the Abstract Quantum Evolution Equation

Start from

$$ i\hbar\frac{\partial\Psi}{\partial t}=H\Psi$$

## 39. Differentiate the Factored State

$$\frac{\partial\Psi}{\partial t}=e^{-imc^2t/\hbar}\left[-\frac{imc^2}{\hbar}\psi+\frac{\partial\psi}{\partial t}\right]$$

## 40. Multiply by iℏ

$$ i\hbar\frac{\partial\Psi}{\partial t}=e^{-imc^2t/\hbar}\left[mc^2\psi+i\hbar\frac{\partial\psi}{\partial t}\right]$$

<!-- source_pdf_page: 2519 -->

## 41. Equate With HΨ

$$ e^{-imc^2t/\hbar}\left[mc^2\psi+i\hbar\frac{\partial\psi}{\partial t}\right]=He^{-imc^2t/\hbar}\psi$$

## 42. Cancel the Common Mass Phase Factor

Therefore:

$$ i\hbar\frac{\partial\psi}{\partial t}=(H-mc^2)\psi$$

## 43. Define the Exact Residual Generator

$$ H_{\mathrm{res}}\equiv H-mc^2$$

Then:

$$ i\hbar\frac{\partial\psi}{\partial t}=H_{\mathrm{res}}\psi$$

## 44. For a Free Positive-Energy Massive State

$$ H=\sqrt{m^2c^4+c^2\mathbf P^2}$$

## 45. Therefore

$$ H_{\mathrm{res}}=\sqrt{m^2c^4+c^2\mathbf P^2}-mc^2$$

This is the exact free residual Hamiltonian in this physical projection.

## 46. Factor Out mc2

$$ H_{\mathrm{res}}=mc^2\left[\sqrt{1+\frac{\mathbf P^2}{m^2c^2}}-1\right]$$

<!-- source_pdf_page: 2520 -->

## 47. Expand in the Strong-Separation Regime

For

$$\frac{\mathbf P^2}{m^2c^2}\ll1$$

$$ H_{\mathrm{res}}=\frac{\mathbf P^2}{2m}-\frac{\mathbf P^4}{8m^3c^2}+O(\mathbf P^6)$$

## 48. The Leading Residual Generator Is

$$ H_{\mathrm{res}}\approx\frac{\mathbf P^2}{2m}$$

## 49. Addendum 75 Supplies Momentum as Translation Generator

$$\mathbf P=-i\hbar\nabla$$

## 50. Therefore

$$\mathbf P^2=(-i\hbar)^2\nabla^2$$

Thus:

$$\mathbf P^2=-\hbar^2\nabla^2$$

## 51. Substitute Into the Residual Evolution Equation

$$ i\hbar\frac{\partial\psi}{\partial t}=\frac{\mathbf P^2}{2m}\psi$$

Therefore:

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

<!-- source_pdf_page: 2521 -->

## 52. The Free Spatial Schrödinger Equation Has Been Recovered

Its temporal generator came from boundary-preserving recurrence.

Its spatial generator came from boundary-preserving translation.

Its kinetic coefficient came from the leading residual of persistent mass recurrence.

## 53. The Equation Is Therefore Not Primitive

It is a scale-separated physical projection built from earlier recurrence relations.

## 54. Decompose the Left-Hand Side

$$ i\hbar\partial_t$$

comes from:

> closure phase → unitary recurrence generator → energy calibration.

## 55. Decompose the Gradient

$$-i\hbar\nabla$$

comes from:

> spatial phase → translation generator → momentum calibration.

## 56. Decompose the Laplacian

$$\mathbf P^2=-\hbar^2\nabla^2$$

The second spatial derivative arises because the leading residual energy depends quadratically on
translation-generator magnitude.

## 57. Decompose the Factor 1/(2m)

The coefficient

<!-- source_pdf_page: 2522 -->

$$\frac1{2m}$$

comes from the leading expansion of the relativistic compatibility relation around the persistent mass
recurrence.

## 58. The Free Schrödinger Equation Is Therefore the Intersection of Four Prior Structures

> boundary-preserving temporal recurrence

$$+$$

> boundary-preserving spatial translation

$$+$$

> persistent mass recurrence

$$+$$

> strong recurrence separation.

## 59. The Nonrelativistic Limit Has a Recurrence Meaning

Conventionally one writes

$$ v\ll c$$

or

$$ p\ll mc$$

R2D can express the same physical regime as

$$\bar\lambda_M k\ll1$$

## 60. In Full Compton-Wavelength Form

Because

$$\lambda_M=2\pi\bar\lambda_M$$

and

<!-- source_pdf_page: 2523 -->

2π

$$ k=\frac{2\pi}{\lambda}$$

$$\bar\lambda_Mk=\frac{\lambda_M}{\lambda}$$

Thus:

$$\lambda\gg\lambda_M$$

## 61. Schrödinger Dynamics Is Therefore a Large-Separation Regime

The spatial recurrence ruler is much larger than the mass recurrence ruler.

Equivalently, the translation phase gradient is weak relative to the persistent Compton recurrence.

## 62. This Is Directly Connected to Addendum 71

Addendum 71 identified the Compton regime through relative recurrence approaching unity.

Here the same ratio controls the validity of the Schrödinger approximation.

## 63. Strong Separation Gives

$$\frac{p}{mc}\ll1$$

Then:

$$ H_{\mathrm{res}}\approx\frac{\mathbf P^2}{2m}$$

## 64. Loss of Separation Gives

$$\frac{p}{mc}=O(1)$$

Then higher terms become important.

<!-- source_pdf_page: 2524 -->

## 65. The First Correction Is

$$-\frac{\mathbf P^4}{8m^3c^2}$$

Thus:

$$ H_{\mathrm{res}}=\frac{\mathbf P^2}{2m}-\frac{\mathbf P^4}{8m^3c^2}+\cdots$$

## 66. Schrödinger Breakdown Is Therefore Continuous

There is no need for a sharp mystical point at which quantum mechanics suddenly becomes relativistic.

The approximation degrades as recurrence separation is lost.

## 67. This Is the Same General Architecture Seen Elsewhere

Across the recent addenda, physical regime changes occur when recurrence scales become comparable.

The Schrödinger-to-relativistic crossover fits the same architecture.

## 68. The Residual Wavefunction Must Not Be Mistaken for the Full Massive Recurrence

The nonrelativistic state

$$\psi$$

does not contain the complete phase recurrence of the massive boundary.

## 69. The Complete State Is

$$\Psi(\mathbf x,t)=e^{-i\omega_Mt}\psi(\mathbf x,t)$$

<!-- source_pdf_page: 2525 -->

## 70. Therefore a Slowly Varying ψ Can Coexist With Extremely Fast Native Mass Recurrence

The slow envelope does not imply that the massive boundary itself is only slowly recurrent.

## 71. This Clarifies the Meaning of a Stationary State

Let

$$\psi(\mathbf x,t)=e^{-iE_{\mathrm{NR}}t/\hbar}\phi(\mathbf x)$$

Then:

$$\Psi(\mathbf x,t)=e^{-imc^2t/\hbar}\psi(\mathbf x,t)$$

## 72. The Total Recurrence Frequency Is

$$\omega=\omega_M+\frac{E_{\mathrm{NR}}}{\hbar}$$

## 73. Yet the Born Density Can Be Time Independent

$$|\psi(\mathbf x,t)|^2=|\phi(\mathbf x)|^2$$

Thus:

stationary realized distribution≠absence of recurrence.

## 74. The Same Principle Appeared in the Mass Turbine

Mechanical rest did not imply the local mass recurrence stopped.

Quantum stationarity likewise does not imply phase recurrence has stopped.

## 75. Additive Potential Energy Can Be Located but Is Not Yet Derived

If an enclosing physical interaction supplies a scalar energy read

<!-- source_pdf_page: 2526 -->

V (x, t),

one may write conditionally

$$ H_{\mathrm{res}}\approx\frac{\mathbf P^2}{2m}+V$$

## 76. Then the Familiar Equation Is

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[-\frac{\hbar^2}{2m}\nabla^2+V\right]\psi$$

## 77. But V Has Different Boundary Ownership

The free kinetic term follows from residual mass-plus-translation recurrence.

The potential term belongs to the relation between the local quantum boundary and an enclosing physical
constraint.

## 78. Therefore the Potential Should Not Be Smuggled Into the Present Derivation

A separate R2D bridge is required to identify how the primitive constraint architecture maps onto

$$ V$$

## 79. This Suggests the Next Problem

The next addendum should ask:

> what R2D relation becomes quantum potential energy?

The natural candidate is the enclosing constraint architecture associated with retention.

<!-- source_pdf_page: 2527 -->

## 80. Principle — Persistent Mass Recurrence Precedes Nonrelativistic Motion

$$ mc^2=\hbar\omega_M$$

A massive boundary already recurs before translational kinetic energy is assigned.

## 81. Principle — Relativistic Compatibility Is a Recurrence Relation After Calibration

$$\omega^2=\omega_M^2+c^2k^2$$

## 82. Principle — Relative Translation Recurrence Controls the Regime

$$\eta=\bar\lambda_Mk=\frac p{mc}$$

## 83. Principle — Residual Recurrence Is

$$\omega_{\mathrm{res}}=\omega-\omega_M$$

## 84. Principle — Kinetic Energy Is Its Energetic Read

$$ K=\hbar\omega_{\mathrm{res}}=E-mc^2$$

## 85. Principle — The Nonrelativistic Limit Is Strong Recurrence Separation

$$\bar\lambda_M k\ll1$$

Equivalently:

$$\lambda\gg\lambda_M$$

<!-- source_pdf_page: 2528 -->

## 86. Principle — Nonrelativistic Kinetic Energy Is the Leading Residual Term

$$ H_{\mathrm{res}}\approx\frac{\mathbf P^2}{2m}$$

## 87. Principle — The Persistent Mass Phase Can Be Factored From the Physical Representation

$$\Psi(\mathbf x,t)=e^{-imc^2t/\hbar}\psi(\mathbf x,t)$$

The local recurrence remains physically present.

## 88. Principle — The Residual State Obeys

$$ i\hbar\frac{\partial\psi}{\partial t}=(H-mc^2)\psi$$

## 89. Principle — The Free Schrödinger Equation Is the Leading Scale- Separated Residual Law

Using

$$\mathbf P=-i\hbar\nabla$$

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

## 90. Principle — Schrödinger Dynamics Does Not Describe the Full Mass Recurrence

It describes the slower residual phase evolution relative to the persistent Compton-scale recurrence.

<!-- source_pdf_page: 2529 -->

## 91. Principle — Relativistic Corrections Measure Loss of Recurrence Separation

$$ H_{\mathrm{res}}=\frac{\mathbf P^2}{2m}-\frac{\mathbf P^4}{8m^3c^2}+\cdots$$

## 92. Principle — Potential Energy Requires Separate Boundary Ownership

The term

$$ V$$

belongs to an enclosing constraint relation and is not derived by free residual recurrence alone.

## 93. Logical Status

Canonical R2D

Recurrence is boundary native.

Physical clock time, energy, momentum, and spatial coordinates are later projection variables.

Prior Mass-Turbine Result

$$ mc^2=\hbar\omega_M$$

Addendum 71

The corresponding Compton recurrence ruler is

$$\bar\lambda_M=\frac{\hbar}{mc}$$

Addendum 74

Boundary-preserving temporal recurrence gives

$$ i\hbar\frac{\partial\Psi}{\partial t}=H\Psi$$

<!-- source_pdf_page: 2530 -->

Addendum 75

Boundary-preserving spatial translation gives

$$\mathbf P=-i\hbar\nabla$$

Imported Mature Relativistic Compatibility

$$ E^2=m^2c^4+p^2c^2$$

Derived Recurrence Form

$$\omega^2=\omega_M^2+c^2k^2$$

New Relative Recurrence Coordinate

$$\eta=\bar\lambda_Mk=\frac p{mc}$$

Exact Residual Generator

$$ H_{\mathrm{res}}=\sqrt{m^2c^4+c^2\mathbf P^2}-mc^2$$

Nonrelativistic Expansion

$$ H_{\mathrm{res}}=\frac{\mathbf P^2}{2m}-\frac{\mathbf P^4}{8m^3c^2}+\cdots$$

Derived Free Spatial Schrödinger Equation

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

Not Yet Established

This addendum does not yet derive:

- the relativistic energy-momentum relation from primitive R2D;
- the universal numerical value of ℏ;
- the origin of the scalar quantum potential V ;
- electromagnetic minimal coupling;
- spin-dependent dynamics;
- the Dirac equation;
- negative-energy branches;
- or quantum-field particle creation.

These are downstream problems.

<!-- source_pdf_page: 2531 -->

## 94. The Complete Schrödinger Architecture

A massive boundary possesses persistent recurrence:

$$\omega_M$$

Its physical mass read is:

$$\downarrow$$

$$ mc^2=\hbar\omega_M$$

The same boundary acquires spatial translation recurrence:

$$\downarrow$$

$$ k$$

Momentum calibration gives:

$$\downarrow$$

$$ p=\hbar k$$

Relativistic compatibility joins them:

$$\downarrow$$

$$\omega^2=\omega_M^2+c^2k^2$$

Separate the persistent recurrence:

$$\downarrow$$

$$\omega_{\mathrm{res}}=\omega-\omega_M$$

Strong recurrence separation gives:

$$\downarrow$$

$$\bar\lambda_M k\ll1$$

Then:

$$\downarrow$$

$$\omega_{\mathrm{res}}\approx\frac{\hbar k^2}{2m}$$

<!-- source_pdf_page: 2532 -->

At the state level:

$$\Psi(\mathbf x,t)=e^{-imc^2t/\hbar}\psi(\mathbf x,t)$$

Thus:

$$\downarrow$$

$$ i\hbar\partial_t\psi=(H-mc^2)\psi$$

The residual generator becomes:

$$\downarrow$$

$$ H_{\mathrm{res}}\approx\frac{\mathbf P^2}{2m}$$

Translation gives:

$$\downarrow$$

$$\mathbf P^2=-\hbar^2\nabla^2$$

Therefore:

$$\downarrow$$

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

The spatial Schrödinger equation is therefore the end of the recurrence-separation chain rather than its
beginning.

## 95. Conclusion

The spatial Schrödinger equation is among the foundational equations of quantum mechanics.

It is often introduced as a basic dynamical law for a massive quantum particle.

R2D places it much later.

A massive boundary already possesses persistent local recurrence.

Its physical phase-frequency read is

<!-- source_pdf_page: 2533 -->

$$\omega_M=\frac{mc^2}{\hbar}$$

This recurrence remains even when the boundary is translationally at rest.

The same quantum boundary may also acquire spatial translation recurrence

$$ k$$

Addendum 75 showed that this spatial phase relation receives the physical momentum read

$$ p=\hbar k$$

The mature relativistic relation

$$ E^2=m^2c^4+p^2c^2$$

can therefore be rewritten entirely as a relation among physical recurrence coordinates:

$$\omega^2=\omega_M^2+c^2k^2$$

Normalize by the persistent mass recurrence:

$$\frac\omega{\omega_M}=\sqrt{1+(\bar\lambda_M k)^2}$$

The dimensionless quantity

$$\eta=\bar\lambda_Mk=\frac p{mc}$$

then measures spatial translation recurrence relative to persistent mass recurrence.

The nonrelativistic regime is

$$\bar\lambda_M k\ll1$$

In that regime, total recurrence differs only slightly from the persistent mass recurrence.

Define that difference:

$$\omega_{\mathrm{res}}=\omega-\omega_M$$

Then:

$$\omega_{\mathrm{res}}=\omega_M\left[\sqrt{1+(\bar\lambda_M k)^2}-1\right]$$

<!-- source_pdf_page: 2534 -->

For strong scale separation,

$$\omega_{\mathrm{res}}\approx\frac{\hbar k^2}{2m}$$

Its energetic read is

$$ E_{\mathrm{res}}\approx\frac{p^2}{2m}$$

Thus nonrelativistic kinetic energy is not inserted independently.

It is the leading energy read of recurrence remaining after the persistent mass recurrence is separated from
the full phase evolution.

At the state level this separation is represented by

$$\Psi(\mathbf x,t)=e^{-imc^2t/\hbar}\psi(\mathbf x,t)$$

The fast phase factor carries persistent mass recurrence.

The residual coordinate ψ carries the slower quantum recurrence relative to that mass closure.

Substitution into the abstract evolution equation gives exactly

$$ i\hbar\frac{\partial\psi}{\partial t}=(H-mc^2)\psi$$

For a free positive-energy boundary,

$$ H-mc^2=\sqrt{m^2c^4+c^2\mathbf P^2}-mc^2$$

The strong-separation expansion is

$$ H_{\mathrm{res}}=\frac{\mathbf P^2}{2m}-\frac{\mathbf P^4}{8m^3c^2}+O(\mathbf P^6)$$

Keeping only the leading residual recurrence and using

$$\mathbf P=-i\hbar\nabla$$

gives

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

<!-- source_pdf_page: 2535 -->

The free spatial Schrödinger equation therefore does not govern the complete native recurrence of the
massive boundary.

It governs the residual phase dynamics remaining after the persistent Compton-scale mass recurrence has
been factored from the physical representation.

This also explains the boundary of validity of the equation.

When

$$\lambda\gg\lambda_M$$

the mass and translation recurrence scales are strongly separated.

The Schrödinger approximation is valid.

As

$$\lambda\to\lambda_M$$

the recurrence scales become comparable.

The higher-order terms become readable.

The same crossover identified experimentally through the Compton relation is therefore also the crossover
at which nonrelativistic Schrödinger dynamics loses its scale separation.

The central statement is:

the nonrelativistic Schrödinger equation does not describe the total recurrence of a massive
quantum boundary. Persistent mass closure already supplies the fast recurrence $\omega_M=mc^2/\hbar$. Relativistic
compatibility combines this with spatial translation recurrence, while the nonrelativistic regime is the scale-
separated limit in which translation recurrence is small relative to the mass recurrence. Factoring the
persistent mass phase leaves the residual generator $H_{\mathrm{res}}=\sqrt{m^2c^4+c^2\mathbf P^2}-mc^2$, whose leading term is $H_{\mathrm{res}}\approx\mathbf P^2/(2m)$. With the
previously derived translation generator $\mathbf P=-i\hbar\nabla$, the free spatial Schrödinger equation follows as the slow
> residual dynamics of persistent mass recurrence.

And hence:

residual mass recurrence occurs before the spatial Schrödinger equation.
