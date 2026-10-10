---
r2d_id: addendum-077
title: Addendum 77 — Constraint Phase Bias Occurs Before the Scalar Potential
subtitle: Enclosing Constraint, Local Recurrence Bias, and the Origin of the V ψ Term
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: false
addendum: 77
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2536
pdf_page_end: 2562
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

# Addendum 77 — Constraint Phase Bias Occurs Before the Scalar Potential

*Enclosing Constraint, Local Recurrence Bias, and the Origin of the V ψ Term*

## Abstract

<!-- source_pdf_page: 2536 -->

Addendum 76 derived the free nonrelativistic Schrödinger equation as the residual phase dynamics of a
massive quantum boundary:

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

Every term in that equation had acquired a distinct R2D origin.

Boundary-preserving recurrence supplied the temporal phase generator.

Boundary-preserving spatial translation supplied

$$ P=-i\hbar\nabla$$

Persistent mass recurrence supplied the Compton-scale background from which the slower nonrelativistic
recurrence was separated.

The only major term in the ordinary Schrödinger equation left without R2D boundary ownership is the
scalar potential:

$$ V(x,t)$$

The full equation is

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[-\frac{\hbar^2}{2m}\nabla^2+V(x,t)\right]\psi. $$

R2D does not begin by assigning a particle stored potential energy.

A scalar potential describes how a local quantum boundary is physically related to an enclosing constraint.

The primitive causal ordering is therefore not

$$\text{potential}\to\text{force}\to\text{motion}$$

<!-- source_pdf_page: 2537 -->

It is

 enclosing constraint → local recurrence bias → scalar-potential read → momentum/force projection.

Let an enclosing relation bias the local recurrence phase of a quantum state without replacing its count
boundary.

Over an infinitesimal physical clock interval dt, the corresponding local phase transformation can be written

$$ \psi(x,t+dt)=e^{-i\,d\phi_V(x,t)}\psi(x,t). $$

For the constraint term acting alone,

$$ \left|e^{-i\,d\phi_V}\right|=1, $$

so the transformation changes phase without directly changing normalized realization magnitude.

Define the constraint-induced local phase rate

$$ \omega_V(x,t)\equiv\frac{\partial\phi_V}{\partial t}. $$

Then

$$\frac{\partial\psi}{\partial t}=-i\omega_V(x,t)\psi$$

for the constraint-only contribution.

Multiplying by ℏ,

$$ i\hbar\frac{\partial\psi}{\partial t}=\hbar\omega_V(x,t)\psi$$

The physical scalar-potential energy is therefore the energetic calibration

$$ V(x,t)\equiv\hbar\omega_V(x,t). $$

Hence the enclosing constraint contributes the operator

$$ \hat V\psi=V(x,t)\psi. $$

The potential acts multiplicatively because it is a local temporal phase-rate bias.

This is structurally different from the kinetic term.

<!-- source_pdf_page: 2538 -->

The kinetic contribution originates in spatial translation:

$$ T(a)\to-i\nabla\to P=-i\hbar\nabla\to\frac{P^2}{2m}$$

The scalar-potential contribution originates in enclosing constraint:

$$ \mathrm{constraint}\to\omega_V(x,t)\to V(x,t)=\hbar\omega_V(x,t). $$

Thus the two terms in the Schrödinger equation have different boundary ownership:

kinetic = native translation recurrence,

while

potential = enclosing constraint-induced recurrence bias.

Combining them yields

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[-\frac{\hbar^2}{2m}\nabla^2+V(x,t)\right]\psi. $$

This also explains why the absolute zero of scalar potential is physically redundant.

If

$$ V(x,t)=V_0$$

is spatially uniform and constant, then

$$\psi(x,t)=e^{-iV_0t/\hbar}\psi_{\mathrm{free}}(x,t)$$

The potential changes only global phase.

More generally, for a spatially uniform time-dependent offset V0 (t),

$$\psi\to\exp\!\left[-\frac{i}{\hbar}\int^t V_0(t')\,dt'\right]\psi$$

Normalized realization is unchanged.

Thus absolute potential is not primitive.

What becomes physically consequential is relative constraint-induced recurrence:

$$\Delta V=\hbar\Delta\omega_V$$

<!-- source_pdf_page: 2539 -->

Spatial variation of that phase-rate landscape produces momentum change.

For

$$ H=\frac{P^2}{2m}+V(X)$$

the Heisenberg/Ehrenfest relation gives

$$\frac{d}{dt}\langle P\rangle=-\langle\nabla V\rangle$$

For a sufficiently localized realization,

$$\frac{dp}{dt}\approx-\nabla V$$

Thus the classical force read is

$$ F=-\nabla V. $$

Using

$$ V=\hbar\omega_V, $$

this becomes

$$ F=-\hbar\nabla\omega_V$$

Force is therefore the mechanical projection of a spatial gradient in constraint-induced recurrence bias.

The primitive R2D constraint relation remains earlier.

For a transition at Bn ,

$$ R_{n,i\to k}=C_{n+1}\lambda_{n,i\to k}$$

This addendum does not identify

$$ V=R$$

or

$$ V=C$$

Those quantities belong to different mathematical layers.

The proposed architecture is instead

<!-- source_pdf_page: 2540 -->

Cn+1 → Rn → physical phase-bias mapping → Vn .

The still-unresolved bridge is the exact physical calibration by which a primitive R2D constraint difference
becomes a quantum phase-rate difference.

What has been established is the structural requirement:

$$\Delta V_{i\to j}=\hbar\Delta\omega_{V,i\to j}$$

Thus any successful R2D mapping of primitive retention into quantum potential must reproduce the
observed relative phase rate.

The central statement is therefore:

the scalar potential does not primitively represent stored energy attached to a quantum
particle. An enclosing constraint biases the local recurrence phase of a quantum boundary without
necessarily replacing that boundary. The resulting local phase-rate bias acquires the physical energetic read
$V(x,t)=\hbar\omega_V(x,t)$, which acts multiplicatively on the state. Spatial differences in this constraint-induced recurrence
 rate subsequently generate momentum change and the classical force projection $F=-\nabla V$. The potential is
> therefore the energetic read of an enclosing constraint-induced phase bias.

And hence:

> constraint phase bias occurs before the scalar potential.

## 1. The Free Schrödinger Equation Already Has Boundary Ownership

Addendum 76 obtained

$$ i\hbar\frac{\partial\psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\psi$$

The free equation describes residual massive recurrence after persistent mass phase has been separated.

## 2. The Spatial Term Is Locally Owned

The operator

$$-\frac{\hbar^2}{2m}\nabla^2$$

belongs to the translation structure of the local massive quantum boundary.

<!-- source_pdf_page: 2541 -->

## 3. A Scalar Potential Has Different Ownership

A potential describes how that local boundary is situated relative to another physical relation.

Therefore:

$$ V(x,t)$$

cannot be assigned the same primitive ownership as the free translation term.

## 4. The Natural Owner Is the Enclosing Constraint

Let

$$ B_{n+1}$$

supply the physical compatibility condition constraining local realization at

$$ B_n$$

Then schematically:

$$ B_{n+1}\to B_n$$

## 5. This Is the Existing R2D Causal Architecture

Enclosing relation defines the local constraint environment.

The local boundary realizes compatible recurrence within that environment.

## 6. Primitive Constraint Is Not Yet Potential Energy

R2D writes retained constraint across a distinction as

$$ R_{n,i\to k}=C_{n+1}\lambda_{n,i\to k}$$

Neither R nor C is primitively measured in joules.

<!-- source_pdf_page: 2542 -->

## 7. Therefore

$$ V\ne R$$

primitively.

And:

$$ V\ne C$$

## 8. The Missing Physical Bridge Must Be Identified

The scalar potential belongs to the quantum physical projection.

The problem is:

> How does an enclosing R2D constraint become readable in quantum phase dynamics?

## 9. Begin With Phase Rather Than Energy

Addendum 72 established phase as the cyclic representation of boundary-native recurrence.

A constraint can therefore alter local recurrence by changing phase accumulation.

## 10. Let the Constraint Act Without Boundary Replacement

Suppose over an infinitesimal interval dt, the count boundary remains

$$ B_n$$

The constraint modifies its local phase relation.

## 11. A Local Phase-Only Transformation Has the Form

$$\psi(x,t+dt)=e^{-i\,d\phi_V(x,t)}\psi(x,t)$$

<!-- source_pdf_page: 2543 -->

## 12. Its Modulus Is Unity

$$\left|e^{-i\,d\phi_V}\right|=1$$

Therefore, for the constraint contribution acting alone,

$$|\psi(x,t+dt)|^2=|\psi(x,t)|^2$$

## 13. Constraint Initially Biases Phase, Not Local Magnitude

The immediate local action is therefore on recurrence phase.

Changes in realized spatial magnitude can emerge later through phase-dependent evolution and
translation coupling.

## 14. Define the Local Constraint Phase Rate

$$\omega_V=\partial_t\phi_V$$

## 15. The Infinitesimal Evolution Is

$$\frac{\partial\psi}{\partial t}=-i\omega_V(x,t)\psi$$

## 16. Multiply by the Action Calibration

$$ i\hbar\frac{\partial\psi}{\partial t}=\hbar\omega_V(x,t)\psi$$

## 17. Define the Scalar-Potential Read

$$ V=\hbar\omega_V$$

<!-- source_pdf_page: 2544 -->

## 18. Therefore

$$ i\hbar\frac{\partial\psi}{\partial t}=V(x,t)\psi$$

for the constraint-only contribution.

## 19. This Explains Why V Is Multiplicative

The scalar potential is local in projected position and changes the temporal phase accumulation at that
position.

It therefore multiplies the position-space amplitude rather than generating spatial translation.

## 20. Compare With Momentum

Momentum required

$$ P=-i\hbar\nabla$$

because momentum generates spatial translation.

## 21. Potential Requires No Spatial Derivative

The scalar constraint instead changes local phase rate:

$$ V=\hbar\omega_V$$

Thus:

$$\widehat V=V(x,t)$$

## 22. Kinetic and Potential Terms Are Therefore Structurally Different

$$\frac{P^2}{2m}$$

comes from native spatial translation.

$$ V(x,t)$$

<!-- source_pdf_page: 2545 -->

comes from enclosing phase bias.

## 23. Their Sum Gives the Residual Hamiltonian

$$ H_{\mathrm{res}}=\frac{P^2}{2m}+V$$

## 24. Therefore the Full Nonrelativistic Equation Is

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[-\frac{\hbar^2}{2m}\nabla^2+V(x,t)\right]\psi$$

## 25. The Two Terms Have Opposite Recursive Ownership

The kinetic term is locally generated.

The potential term is enclosingly imposed.

This reproduces the R2D leapfrog architecture:

> local realization ↔ enclosing constraint.

## 26. A Spatially Uniform Potential Gives a Common Phase Rate

Let

$$ V(x,t)=V_0$$

Then:

$$\omega_V=\frac{V_0}{\hbar}$$

## 27. Its Evolution Is

$$\psi(t)=e^{-iV_0t/\hbar}\psi_{\mathrm{free}}(t)$$

<!-- source_pdf_page: 2546 -->

## 28. The Realization Magnitude Is Unchanged

$$|\psi(t)|^2=|\psi_{\mathrm{free}}(t)|^2$$

Thus a common constant potential offset is not independently observable through Born realization.

## 29. The Absolute Potential Zero Is Therefore Not Primitive

The physical state is unchanged by

$$ V\to V+V_0$$

apart from a common phase evolution.

## 30. For a Time-Dependent Uniform Offset

Let

$$ V_0=V_0(t)$$

Then:

$$\psi\to\exp\!\left[-\frac{i}{\hbar}\int^t V_0(t')\,dt'\right]\psi$$

Again only global phase changes.

## 31. Relative Potential Is Physically Consequential

For two locations or alternatives,

$$ i$$

and

$$ j$$

the phase-rate difference is

$$\omega_{V,i}-\omega_{V,j}$$

<!-- source_pdf_page: 2547 -->

## 32. Its Energetic Read Is

$$ V_i-V_j=\hbar(\omega_{V,i}-\omega_{V,j})$$

## 33. Thus Potential Difference Is Relative Recurrence Bias

$$\Delta V=\hbar\Delta\omega_V$$

This is the physically meaningful scalar-potential relation.

## 34. Relative Phase Accumulates Over Time

For static Vi and Vj ,

$$\Delta\phi_{ij}(t)=\Delta\phi_{ij}(0)-\frac{V_i-V_j}{\hbar}t$$

## 35. Potential Differences Therefore Produce Observable Interference

Even when the local amplitude magnitude is initially unchanged, different phase accumulation can later
alter realized detector counts when the alternatives are recombined.

## 36. The Potential Is Therefore Dynamically Real Without Being Primitive Substance

Its physical effect is carried by relative recurrence.

## 37. Return to the Primitive R2D Constraint

The upstream constraint relation is

$$ R_{n,i\to k}=C_{n+1}\lambda_{n,i\to k}$$

<!-- source_pdf_page: 2548 -->

## 38. The Quantum Mapping Must Preserve Boundary Ownership

The enclosing boundary owns

$$ C_{n+1}$$

The local distinction owns

$$\lambda_{n,i\to k}$$

Their retained relation owns

$$ R_{n,i\to k}$$

## 39. Quantum Potential Is a Later Read

The proposed order is

$$ C_{n+1}$$

> ↓

$$ R_n$$

> ↓

$$\omega_V(x,t)$$

> ↓

$$ V(x,t)=\hbar\omega_V(x,t)$$

## 40. The Middle Mapping Is Not Yet Derived

This addendum does not claim a universal primitive equation

$$ R=\frac{V}{E_0}$$

or any equivalent normalization.

The physical calibration remains boundary dependent until derived.

<!-- source_pdf_page: 2549 -->

## 41. What Must Be Preserved Is the Relative Phase Relation

Whatever map connects R2D constraint to the quantum potential must satisfy

$$\Delta\omega_V=\frac{\Delta V}{\hbar}$$

## 42. This Provides an Empirical Target for the Missing Bridge

The R2D constraint architecture must reproduce experimentally observed potential-induced phase
accumulation.

## 43. Momentum Change Follows From the Potential Landscape

For the Hamiltonian

$$ H=\frac{P^2}{2m}+V(X)$$

the expectation value of momentum evolves according to

$$\frac{d}{dt}\langle P\rangle=\frac{i}{\hbar}\langle[H,P]\rangle$$

## 44. The Free Kinetic Term Commutes With Momentum

$$[P^2,P]=0$$

Thus only the potential contributes.

## 45. Use the Position-Momentum Commutator

For a scalar function V (X),

$$[V(X),P]=i\hbar\nabla V$$

<!-- source_pdf_page: 2550 -->

## 46. Therefore

$$\frac{d}{dt}\langle P\rangle=-\langle\nabla V\rangle$$

This is Ehrenfest's momentum equation.

## 47. Substitute the Phase-Rate Read

Since

$$ V=\hbar\omega_V$$

$$\frac{d}{dt}\langle P\rangle=-\hbar\langle\nabla\omega_V\rangle$$

## 48. Momentum Change Is Therefore Driven by Spatial Variation of Constraint Phase Rate

Uniform phase bias produces no momentum change.

Only differential phase bias does.

## 49. This Is the Quantum Precursor of Force

For a localized state,

$$\frac{dp}{dt}\approx-\nabla V$$

## 50. Define the Classical Force Read

$$ F=-\nabla V$$

Then:

$$ F=-\hbar\nabla\omega_V$$

<!-- source_pdf_page: 2551 -->

## 51. Force Is Therefore Downstream of Constraint Phase Bias

The R2D order is

> enclosing constraint

> ↓

> local phase-rate landscape

> ↓

$$ V$$

> ↓

$$-\nabla V$$

> ↓

$$ F$$

## 52. This Reverses Classical Force-First Ontology

R2D does not require force to act primitively on a particle.

Force is a later mechanical summary of an underlying constraint-induced recurrence gradient.

## 53. Position Expectation Evolves Through Momentum

For the same Hamiltonian,

$$\frac{d}{dt}\langle X\rangle=\frac{\langle P\rangle}{m}$$

## 54. Differentiate Again

$$ m\frac{d^2}{dt^2}\langle X\rangle=-\langle\nabla V\rangle$$

<!-- source_pdf_page: 2552 -->

## 55. In the Localized Limit

$$ m\ddot{x}=-\nabla V$$

Newtonian acceleration appears downstream of quantum phase dynamics.

## 56. Classical Dynamics Is Therefore a Localized Projection

The sequence is not

$$\text{primitive force}\to\text{quantum law}$$

It is

$$\text{constraint recurrence}\to\text{quantum phase law}\to\text{localized classical force}$$

## 57. The Phase Field Makes the Relation Especially Clear

Write the quantum state locally as

$$\psi=Ae^{i\phi}$$

Then temporal phase rate contributes to energy.

## 58. Temporal Phase Has Physical Energy Read

Schematically,

$$-\hbar\frac{\partial\phi}{\partial t}\leftrightarrow E$$

## 59. Spatial Phase Has Physical Momentum Read

From Addendum 75,

$$\hbar\nabla\phi\leftrightarrow p$$

<!-- source_pdf_page: 2553 -->

## 60. The Potential Biases the Temporal Side

$$ V=\hbar\omega_V$$

Thus a spatially varying potential creates a spatially varying temporal phase rate.

## 61. The Resulting Relative Phase Alters the Spatial Momentum Read

Because momentum is the spatial phase gradient, spatially differential temporal phase accumulation
changes momentum structure over time.

## 62. This Gives a Unified Phase Interpretation

> temporal phase gradient → energy,

> spatial phase gradient → momentum.

The scalar potential modifies the first and thereby influences the second.

## 63. The Hamilton–Jacobi Limit Is Consistent With This Ordering

Write

$$\psi=Ae^{iS/\hbar}$$

Then the phase is

$$\phi=\frac{S}{\hbar}$$

## 64. Substitution Into Schrödinger Gives a Real Phase Equation

The real part is

$$\frac{\partial S}{\partial t}+\frac{(\nabla S)^2}{2m}+V+Q=0$$

with

<!-- source_pdf_page: 2554 -->

$$ Q=-\frac{\hbar^2}{2m}\frac{\nabla^2A}{A}$$

## 65. Q Is Not the Scalar Potential Derived Here

The term

$$ Q$$

is often called the Bohm quantum potential.

That terminology must not be confused with the scalar potential

$$ V$$

The present addendum concerns only the latter.

## 66. In the Appropriate Slowly Varying-Amplitude Limit

If

$$ Q$$

becomes negligible relative to the other physical terms, then

$$\frac{\partial S}{\partial t}+\frac{(\nabla S)^2}{2m}+V=0$$

This is the Hamilton–Jacobi equation.

## 67. Thus the Classical Action Function Is Also a Phase Read

$$ S=\hbar\phi$$

The classical action landscape is downstream of the same phase architecture.

## 68. This Does Not Make Classical Action Primitive

The R2D ordering remains

$$\text{closure recurrence}\to\text{phase}\to S,E,p,V$$

<!-- source_pdf_page: 2555 -->

## 69. Scalar Potential Must Be Distinguished From Quantum Measurement Bias

A potential can continuously alter recurrence phase while the same quantum boundary persists.

Measurement creates a new enclosing readable macrostate.

These are different operations.

## 70. Therefore

$$\text{potential evolution}\ne\text{measurement}$$

A scalar constraint can act unitarily.

## 71. Constraint Does Not Necessarily Mean Boundary Replacement

The enclosing relation can bias the local boundary while leaving that boundary realized.

This is precisely why V can appear inside the unitary Hamiltonian.

## 72. Principle — Scalar Potential Has Enclosing Ownership

The free translation term is native to the local massive boundary.

The scalar potential belongs to its relation with an enclosing constraint.

## 73. Principle — Constraint Acts First as Phase Bias

For the local constraint contribution,

$$\psi\to e^{-i\,d\phi_V}\psi$$

## 74. Principle — Constraint Phase Rate Precedes Potential Energy

$$\omega_V=\partial_t\phi_V$$

<!-- source_pdf_page: 2556 -->

Then:

$$ V=\hbar\omega_V$$

## 75. Principle — Potential Acts Multiplicatively Because It Is Local Phase Rate

$$\widehat V\psi=V(x,t)\psi$$

## 76. Principle — Constant Potential Is Common Phase Offset

A spatially uniform V0 changes

$$\psi\to e^{-iV_0t/\hbar}\psi$$

without changing normalized realization.

## 77. Principle — Potential Difference Is Relative Recurrence Bias

$$\Delta V=\hbar\Delta\omega_V$$

## 78. Principle — Force Is Downstream of the Potential Landscape

$$ F=-\nabla V$$

Therefore:

$$ F=-\hbar\nabla\omega_V$$

## 79. Principle — Primitive Constraint and Scalar Potential Are Not Identical

$$ V\ne R$$

and

$$ V\ne C$$

<!-- source_pdf_page: 2557 -->

The quantum potential is a later physical calibration of the constraint relation.

## 80. Principle — Kinetic and Potential Terms Have Different Boundary Ownership

$$\frac{P^2}{2m}$$

= native translation recurrence read,

while

V = enclosing constraint-phase read.

## 81. Principle — The Full Schrödinger Equation Joins Local Recurrence and Enclosing Constraint

$$ i\hbar\partial_t\psi=\left[-\frac{\hbar^2}{2m}\nabla^2+V\right]\psi$$

This is the quantum physical projection of the R2D local/enclosing causal architecture.

## 82. Logical Status

Canonical R2D

Enclosing constraint acts on local realization.

The primitive retained constraint is

$$ R=C\lambda$$

Addendum 72

Closure produces phase.

Addendum 74

Boundary-preserving phase recurrence produces the temporal quantum generator.

Addendum 75

Spatial translation produces the momentum generator.

<!-- source_pdf_page: 2558 -->

Addendum 76

Persistent mass recurrence plus translation yields the free nonrelativistic kinetic operator.

New Constraint-Phase Definition

$$\omega_V=\partial_t\phi_V$$

Physical Scalar-Potential Calibration

$$ V=\hbar\omega_V$$

Derived Potential Operator

$$\widehat V\psi=V(x,t)\psi$$

Completed Nonrelativistic Schrödinger Form

$$ i\hbar\partial_t\psi=\left[-\frac{\hbar^2}{2m}\nabla^2+V\right]\psi$$

Derived Momentum Evolution

$$\frac{d}{dt}\langle P\rangle=-\langle\nabla V\rangle$$

Classical Localized Limit

$$ m\ddot{x}=-\nabla V$$

Not Yet Established

This addendum does not yet derive:

- the exact primitive mapping from R = Cλ to V ;
- the numerical value of ℏ;
- electromagnetic vector potential;
- minimal coupling;
- local gauge connection;
- spin coupling;
- or relativistic constraint dynamics.

Those remain downstream bridges.

<!-- source_pdf_page: 2559 -->

## 83. The Complete Scalar-Potential Architecture

An enclosing boundary supplies constraint:

$$ C_{n+1}$$

The local distinction gives retained constraint:

> ↓

$$ R_n=C_{n+1}\lambda_n$$

The quantum physical projection maps that relation to a local phase bias:

> ↓

$$\omega_V(x,t)$$

Energy calibration gives:

> ↓

$$ V(x,t)=\hbar\omega_V(x,t)$$

The state therefore acquires local phase evolution:

> ↓

$$\psi\to e^{-iV\,dt/\hbar}\psi$$

Together with native translation recurrence:

> ↓

$$ H_{\mathrm{res}}=\frac{P^2}{2m}+V$$

Therefore:

> ↓

$$ i\hbar\partial_t\psi=\left[-\frac{\hbar^2}{2m}\nabla^2+V\right]\psi$$

Spatial variation in the constraint bias gives:

> ↓

<!-- source_pdf_page: 2560 -->

−∇V .

And in the localized mechanical projection:

> ↓

$$ F=-\nabla V$$

Thus force is the end of the chain, not its beginning.

## 84. Conclusion

The scalar potential is usually introduced into quantum mechanics as an energy function

$$ V(x,t)$$

added to the kinetic Hamiltonian.

Its physical origin is often inherited from classical mechanics.

R2D reverses that ordering.

The free quantum boundary already possesses native recurrence and translation.

Its kinetic operator

$$-\frac{\hbar^2}{2m}\nabla^2$$

belongs to those local relations.

A scalar potential has different ownership.

It describes how that local boundary is constrained by an enclosing physical relation.

The enclosing constraint need not immediately change the boundary's normalized realization magnitude.

It can first bias its local recurrence phase.

That phase-only contribution has the infinitesimal form

$$\psi\to e^{-i\,d\phi_V}\psi$$

The corresponding local phase rate is

$$\omega_V=\partial_t\phi_V$$

<!-- source_pdf_page: 2561 -->

Only after energetic calibration does this become

$$ V=\hbar\omega_V$$

The scalar potential therefore appears naturally as a multiplicative operator:

$$\widehat V\psi=V(x,t)\psi$$

This completes the ordinary nonrelativistic Schrödinger architecture:

$$ i\hbar\frac{\partial\psi}{\partial t}=\left[-\frac{\hbar^2}{2m}\nabla^2+V(x,t)\right]\psi$$

The two terms now have distinct R2D origins.

The kinetic term reads the boundary's native spatial translation recurrence.

The potential term reads the enclosing constraint's bias on local temporal recurrence.

A spatially uniform potential shifts all phases equally.

It therefore changes only global phase and leaves normalized realization unchanged.

Only relative potential matters:

$$\Delta V=\hbar\Delta\omega_V$$

Spatial gradients in that recurrence bias then alter momentum:

$$\frac{d}{dt}\langle P\rangle=-\langle\nabla V\rangle$$

In the localized mechanical limit,

$$ F=-\nabla V=-\hbar\nabla\omega_V$$

Thus classical force is not the primitive cause of the quantum potential.

It is the downstream mechanical projection of a spatial gradient in enclosing constraint-induced recurrence.

The primitive R2D relation remains earlier:

$$ R=C\lambda$$

The exact physical calibration from this retained constraint to quantum scalar potential remains to be
derived.

<!-- source_pdf_page: 2562 -->

Therefore this addendum does not collapse

$$ R,\quad C,\quad V$$

into one object.

It identifies their causal ordering:

enclosing constraint → retained local relation → phase-rate bias → scalar potential → force.

The central statement is therefore:

the scalar potential does not primitively represent stored energy attached to a quantum
particle. An enclosing constraint biases the local recurrence phase of a boundary while that boundary
 remains realized. The corresponding phase-rate bias receives the energetic read $V(x,t)=\hbar\omega_V(x,t)$, producing the
 multiplicative scalar-potential term in the Schrödinger equation. Spatial differences in this recurrence bias
subsequently produce momentum change and the classical force projection. Potential energy is therefore a
physical read of enclosing constraint-induced recurrence, not a primitive substance or force field.

And hence:

constraint phase bias occurs before the scalar potential.
