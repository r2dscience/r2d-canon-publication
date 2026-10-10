---
r2d_id: addendum-074
title: Addendum 74 — Boundary-Preserving Recurrence Occurs Before Unitary Evolution
subtitle: Transition-Measure Preservation, Continuous Closure, and the Origin of the Abstract Schrödinger Equation
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: false
addendum: 74
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2449
pdf_page_end: 2475
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

# Addendum 74 — Boundary-Preserving Recurrence Occurs Before Unitary Evolution

*Transition-Measure Preservation, Continuous Closure, and the Origin of the Abstract Schrödinger Equation*

## Abstract

<!-- source_pdf_page: 2449 -->

Addendum 72 derived complex phase from boundary-native recurrent closure.

Addendum 73 then connected normalized detector realization to the Born measure:

$$ \mu_\psi(P)=\operatorname{Tr}(\rho_\psi P), $$

and, for a pure state and rank-one detector alternative,

$$ \mu_\psi(P_\phi)=|\langle\phi|\psi\rangle|^2. $$

The next question is dynamical.

If a quantum boundary evolves without being replaced by a new enclosing measurement boundary, what
mathematical structure must preserve its physical realization relations?

R2D distinguishes two fundamentally different situations.

The first is boundary-preserving recurrence:

$$ B_n\to B_n$$

The count domain remains the same while the boundary-native recurrence changes phase.

The second is boundary replacement:

$$ B_n\to B_{n+1}^{M}$$

where a new enclosing measurement boundary creates a new readable macrostate distinction.

These two physical situations should not be assigned the same mathematical operation.

For boundary-preserving quantum evolution, no new detector macrostate has yet been realized. The
physically meaningful relational structure among admissible quantum states must therefore remain
invariant.

<!-- source_pdf_page: 2450 -->

For two state rays represented by

$$|\psi\rangle$$

and

$$|\phi\rangle$$

Addendum 73 identifies their transition measure as

$$ T(\phi,\psi)=|\langle\phi|\psi\rangle|^2. $$

Boundary-preserving evolution must therefore satisfy

$$ |\langle\phi|\psi\rangle|^2=|\langle\phi\prime|\psi\prime\rangle|^2. $$

A transformation of quantum rays preserving all such transition measures is represented, by Wigner's
theorem, by either a unitary or an antiunitary operator.

Thus:

> transition-measure preservation → unitary or antiunitary representation.

R2D supplies an additional physical condition.

Boundary-native recurrence is continuous in its physical phase representation and must connect
continuously to the identity transformation.

Let

$$\tau$$

denote a recurrence parameter before assignment of physical clock units.

Then:

$$ U(0)=I$$

For continuous recurrence,

$$ U(\tau+\delta\tau)\to U(\tau)$$

as

$$\delta\tau\to0$$

<!-- source_pdf_page: 2451 -->

An antiunitary transformation is not continuously connected to the identity within such a one-parameter
evolution.

The continuous boundary-preserving branch is therefore unitary:

$$ U^\dagger(\tau)U(\tau)=I. $$

For an autonomous boundary-preserving recurrence, composition satisfies

$$ U(\tau_2)U(\tau_1)=U(\tau_1+\tau_2). $$

A strongly continuous one-parameter unitary group has a self-adjoint generator Kτ :

$$ U(\tau)=e^{-iK_\tau\tau}. $$

Hence:

$$ i\frac{d}{d\tau}|\psi(\tau)\rangle=K_\tau|\psi(\tau)\rangle$$

This equation is prior to physical energy.

It describes continuous boundary-preserving phase recurrence in the quantum state representation.

Only after physical clock calibration maps

$$\tau\to t$$

does the generator acquire inverse-time dimensions:

$$ K_t$$

The empirical quantum energy-frequency calibration then assigns

$$ H=\hbar K_t. $$

Therefore:

$$ U(t)=e^{-iHt/\hbar}, $$

and

$$ i\hbar\frac{d}{dt}|\psi(t)\rangle=H|\psi(t)\rangle$$

This is the abstract Schrödinger equation.

<!-- source_pdf_page: 2452 -->

Its R2D interpretation is not that a primitive wavefunction physically flows through an underlying Hilbert
space.

The quantum state vector is the mathematical projection of boundary-native recurrence and normalized
realization structure.

Unitary evolution is the transformation law required to preserve that relational realization structure while
the count boundary itself remains unchanged.

Thus:

> unitarity is the quantum projection of boundary-preserving recurrence.

The central statement is therefore:

a quantum boundary that evolves without recursive replacement must preserve the normalized realization relations among its admissible state representations. The Born transition measure provides the relevant invariant. Wigner’s theorem restricts transformations preserving that invariant to unitary or antiunitary form; continuous recurrence connected to the identity selects the unitary branch. Strong continuity then supplies a self-adjoint recurrence generator, and physical energy-frequency calibration converts that generator into the Hamiltonian. The abstract Schrodinger equation is therefore a later physical representation of boundary-preserving recurrence.

And hence:

> boundary-preserving recurrence occurs before unitary evolution.

## 1. Begin With the Boundary, Not the Evolution Operator

Let

$$ B_n$$

be a realized quantum boundary.

Its count domain is already defined.

Its boundary-native recurrence is represented through complex phase.

## 2. The State Representation May Change Without the Boundary Being Replaced

Write the initial quantum state representation as

$$|\psi\rangle$$

After an interval of boundary-preserving recurrence, write

<!-- source_pdf_page: 2453 -->

∣ψ ′ ⟩.

The state coordinate has changed.

The count boundary has not.

## 3. This Must Be Distinguished From Measurement

Measurement creates a new enclosing readable distinction.

Schematically:

$$ B_n\to B_{n+1}^{M}$$

That is a change of count domain.

## 4. Closed Quantum Evolution Instead Has the Form

$$ B_n\to B_n$$

The same boundary remains the owner of state meaning.

## 5. Therefore the First Question Is an Invariance Question

What physical relation must remain unchanged while the state coordinate evolves inside the same
boundary?

## 6. Norm Preservation Alone Is Too Weak

One might propose

$$\langle\psi|\psi\rangle=\langle\psi'|\psi'\rangle$$

This is necessary for normalized quantum states.

But it is not sufficient to derive unitary dynamics.

Nonlinear transformations can preserve norms.

<!-- source_pdf_page: 2454 -->

## 7. Addendum 73 Supplies a Stronger Physical Invariant

For two admissible quantum states,

$$|\psi\rangle$$

and

$$|\phi\rangle$$

the transition measure is

$$ T(\phi,\psi)=|\langle\phi|\psi\rangle|^2$$

## 8. This Quantity Has a Direct Measurement Meaning

If

$$|\phi\rangle$$

defines a rank-one detector alternative, then

$$|\langle\phi|\psi\rangle|^2$$

is the normalized realization measure associated with that alternative.

## 9. Thus the Transition Measure Is More Fundamental Than a Coordinate Component

It expresses a physically realizable relation between quantum state and detector classification.

## 10. Apply the Same Boundary-Preserving Evolution to Two States

Let

$$|\psi\rangle\to|\psi'\rangle$$

and

$$|\phi\rangle\to|\phi'\rangle$$

<!-- source_pdf_page: 2455 -->

If the evolution itself creates no new count boundary, the relational realization structure should remain
unchanged.

## 11. Therefore Require

$$|\langle\phi'|\psi'\rangle|^2=|\langle\phi|\psi\rangle|^2$$

This is transition-measure preservation.

## 12. The Preservation Condition Is Boundary Relative

It does not assert that every physical quantity remains constant.

Phase, energy coordinates, spatial coordinates, and expectation values may change.

What remains invariant is the relational measure defining how state rays compare.

## 13. Quantum States Are Rays Rather Than Absolute Vectors

From Addendum 72,

$$|\psi\rangle$$

and

$$ e^{i\alpha}|\psi\rangle$$

represent the same physical state relation.

Therefore the physical object relevant to the transition measure is a ray.

## 14. The Transition Measure Is Ray Invariant

$$|\langle e^{i\beta}\phi|e^{i\alpha}\psi\rangle|^2=|\langle\phi|\psi\rangle|^2$$

Thus it depends only on relational state geometry.

## 15. Wigner's Theorem Applies to Exactly This Structure

A bijective transformation of quantum rays preserving

<!-- source_pdf_page: 2456 -->

∣⟨ϕ∣ψ⟩∣2

is represented by either:

> unitary

or

> antiunitary

transformation of the state vectors.

## 16. This Is Stronger Than Assuming Linear Evolution

Linearity or antilinearity arises from preservation of the physically meaningful transition measure.

R2D therefore need not begin by postulating linear state dynamics.

## 17. The First Quantum-Dynamical Result Is

> boundary relational invariance → unitary or antiunitary representation.

## 18. Antiunitarity Is Still Mathematically Possible at This Stage

Transition-measure preservation alone does not choose between the two branches.

R2D must supply another physical condition.

## 19. Boundary-Native Recurrence Supplies Continuity

Addendum 72 derived phase as the continuous physical representation of recurrent closure.

Thus physical evolution associated with that recurrence should admit continuously neighboring
transformations.

## 20. Introduce a Recurrence Parameter

Let

<!-- source_pdf_page: 2457 -->

τ

parameterize progress through the boundary-native recurrence.

At this stage, τ need not be measured in seconds.

## 21. Identity Corresponds to Zero Recurrence Advance

$$ U(0)=I$$

No recurrence advance means no change of state representation.

## 22. Continuous Recurrence Requires

$$\lim_{\delta\tau\to0}U(\tau+\delta\tau)=U(\tau)$$

The mathematical representation changes continuously with recurrence advance.

## 23. The Evolution Must Therefore Be Connected Continuously to the Identity

There must be a continuous path from

$$ I$$

to the transformation representing any sufficiently small recurrence advance.

## 24. The Antiunitary Branch Is Disconnected From the Identity

Antiunitary transformations involve complex conjugation structure.

They cannot arise as infinitesimal continuous deformations of the identity within a one-parameter evolution
generated from U (0) = I .

## 25. Therefore Continuous Boundary-Native Recurrence Selects the Unitary Branch

$$ U^\dagger U=I$$

<!-- source_pdf_page: 2458 -->

## 26. This Is the Central Unitarity Result

> Born-measure preservation + continuous recurrence → unitarity.

## 27. Unitarity Is Therefore Not a Primitive Law

It is the mathematical representation of a deeper physical condition:

> same quantum boundary + preserved relational realization structure.

## 28. Unitarity Preserves the Norm

Immediately,

$$\langle\psi'|\psi'\rangle=\langle\psi|U^\dagger U|\psi\rangle$$

Therefore:

$$\langle\psi'|\psi'\rangle=\langle\psi|\psi\rangle$$

## 29. It Also Preserves Every Inner Product

For

$$|\psi'\rangle=U|\psi\rangle,\qquad|\phi'\rangle=U|\phi\rangle$$

$$\langle\phi'|\psi'\rangle=\langle\phi|\psi\rangle$$

## 30. Hence It Preserves the Born Transition Measure Automatically

$$|\langle\phi'|\psi'\rangle|^2=|\langle\phi|\psi\rangle|^2$$

The relational count structure is preserved.

## 31. Now Require Composition of Recurrence

For an autonomous closed boundary, recurrence advance by

<!-- source_pdf_page: 2459 -->

τ1

followed by

$$\tau_2$$

is equivalent to total recurrence advance

$$\tau_1+\tau_2$$

Therefore:

$$ U(\tau_2)U(\tau_1)=U(\tau_1+\tau_2)$$

## 32. This Is the One-Parameter Group Law

Together with

$$ U(0)=I$$

it implies

$$ U(-\tau)=U^\dagger(\tau)$$

## 33. Because U Is Unitary

$$ U^{-1}(\tau)=U^\dagger(\tau)$$

Thus:

$$ U(-\tau)=U^\dagger(\tau)$$

## 34. This Reversibility Belongs to the Boundary-Preserving Representation

It does not imply that all physical thermodynamic processes are globally reversible.

The present result applies to the projected closed quantum recurrence before a new irreversible
measurement record is realized.

<!-- source_pdf_page: 2460 -->

## 35. Strong Continuity Gives a Self-Adjoint Generator

A strongly continuous one-parameter unitary group possesses a self-adjoint generator.

Write it as

$$ K_\tau$$

Then:

$$ U(\tau)=e^{-iK_\tau\tau}$$

## 36. Kτ Is a Recurrence Generator

At this stage it should not yet be called energy.

It generates change of the quantum phase-state representation per unit recurrence parameter.

## 37. Differentiate the Unitary Evolution

$$|\psi(\tau)\rangle=U(\tau)|\psi(0)\rangle$$

Thus:

$$\frac{d}{d\tau}|\psi(\tau)\rangle=-iK_\tau|\psi(\tau)\rangle$$

## 38. Therefore

$$ i\frac{d}{d\tau}|\psi(\tau)\rangle=K_\tau|\psi(\tau)\rangle$$

This is the primitive projected recurrence-evolution equation.

## 39. The Equation Is Already Schrödinger-Like

But it contains:

- no ℏ;
- no joules;

<!-- source_pdf_page: 2461 -->

• no physical time unit;
- no spatial kinetic operator.

Those come later.

## 40. The Recurrence Parameter Must Not Be Confused With Primitive Time

R2D already places recursive recurrence before physical clock calibration.

Therefore:

$$\tau\ne t$$

primitively.

## 41. Physical Clock Calibration Produces t

Once the boundary recurrence is compared with an appropriate physical clock,

$$\tau\to t$$

The generator becomes an inverse-time operator:

$$ K_t$$

## 42. Then

$$ i\frac{d}{dt}|\psi(t)\rangle=K_t|\psi(t)\rangle$$

## 43. Eigenstates of the Generator Have Definite Physical Recurrence Rate

Let

$$ K_t|k\rangle=\omega_k|k\rangle$$

Then:

<!-- source_pdf_page: 2462 -->

U (t)∣k⟩ = e−iωk t ∣k⟩.

## 44. The State's Realization Magnitude Does Not Change

For this eigenstate,

$$|e^{-i\omega_kt}|^2=1$$

Thus its Born weight remains constant.

## 45. Yet Its Phase Continues to Recur

$$\phi_k(t)=\phi_k(0)-\omega_k t$$

This is a stationary quantum state in the R2D sense.

## 46. Stationary Does Not Mean Recurrence Has Stopped

> stationary occupancy ≠ zero recurrence.

A state can retain constant realized support while continuously changing phase.

## 47. This Mirrors the Mass-Turbine Result

Mechanical rest did not require mass recurrence to vanish.

Likewise quantum stationarity does not require closure phase recurrence to vanish.

## 48. Energy Is a Later Calibration of the Recurrence Generator

The physical quantum calibration is

$$ E=\hbar\omega$$

Therefore define

$$ H=\hbar K_t$$

<!-- source_pdf_page: 2463 -->

## 49. The Generator Becomes the Hamiltonian

If

$$ K_t|E\rangle=\omega|E\rangle$$

then:

$$ H|E\rangle=\hbar\omega|E\rangle$$

Thus:

$$ H|E\rangle=E|E\rangle$$

## 50. Energy Eigenvalue Is Therefore a Physical Read of Recurrence- Generator Eigenvalue

$$ E=\hbar\omega$$

The recurrence relation comes first.

## 51. The Unitary Operator Becomes

$$ U(t)=e^{-iHt/\hbar}$$

## 52. And the Evolution Equation Becomes

$$ i\hbar\frac{d}{dt}|\psi(t)\rangle=H|\psi(t)\rangle$$

This is the abstract Schrödinger equation.

## 53. The Abstract Schrödinger Equation Is Therefore a Generator Equation

It does not yet specify what

$$ H$$

looks like in a spatial representation.

<!-- source_pdf_page: 2464 -->

## 54. In Particular, This Addendum Does Not Yet Derive

$$ H=-\frac{\hbar^2}{2m}\nabla^2+V$$

That requires the physical momentum, mass, space, and constraint mappings.

## 55. The Spatial Schrödinger Equation Comes Later

The present result establishes only:

> continuous boundary-preserving quantum recurrence → self-adjoint generator.

## 56. This Resolves the Apparent Dual Dynamics of Quantum Theory

Conventional quantum mechanics appears to contain two very different operations:

> unitary evolution

and

> measurement collapse.

R2D assigns them to different recursive situations.

## 57. Unitary Evolution Belongs to One Boundary

$$ B_n\to B_n$$

The count domain remains unchanged.

## 58. Measurement Creates a New Enclosing Boundary

$$ B_n\to B_{n+1}^{M}$$

A new readable macrostate becomes realized.

<!-- source_pdf_page: 2465 -->

## 59. Thus Measurement Is Not Merely Nonunitary Evolution Within the Same Primitive State Space

It changes the boundary at which state identity is defined.

That is a different physical operation.

## 60. The Apparent Conflict Is Therefore a Category Error

Trying to force measurement and closed recurrence into one primitive dynamical rule assumes that both
occur within the same count domain.

R2D denies that assumption.

## 61. The More Primitive Distinction Is

Boundary preserved $\to$ unitary projection; boundary replaced $\to$ new realization.

## 62. This Does Not Yet Solve Every Measurement Problem

R2D must still derive the quantitative coupling between quantum recurrence and measurement-boundary
asymmetry.

But the two mathematical operations now have different boundary ownership.

## 63. Continuous Evolution Also Explains Why Antiunitary Symmetries Can Still Exist

The exclusion above applies to continuous dynamical evolution connected to the identity.

It does not forbid discrete antiunitary symmetries such as time-reversal representation.

## 64. Thus

antiunitary symmetry≠continuous time-evolution branch.

<!-- source_pdf_page: 2466 -->

The distinction should be preserved.

## 65. Autonomous Evolution Is the Clean Group Case

For a time-independent generator,

$$ U(t_2)U(t_1)=U(t_1+t_2)$$

This is the case treated directly by the one-parameter group theorem.

## 66. More General Physical Environments Need Not Have a Time- Independent Generator

If the enclosing physical conditions change,

$$ H=H(t)$$

the propagator is more generally

$$ U(t_2,t_0)=U(t_2,t_1)U(t_1,t_0)$$

## 67. The Boundary-Preserving Principle Still Holds

Even when the generator depends on physical clock time,

$$ U^\dagger U=I$$

remains the defining closed-evolution property as long as the quantum boundary is not replaced.

## 68. The Group Law Should Therefore Not Be Overgeneralized

The simple exponential

$$ e^{-iHt/\hbar}$$

belongs directly to an autonomous generator.

The deeper result is unitarity from preserved relational measure.

<!-- source_pdf_page: 2467 -->

## 69. Principle — Boundary Preservation Precedes Unitarity

A quantum state may change while its count boundary remains the same.

The mathematical representation of that situation must preserve the relational realization structure of that
boundary.

## 70. Principle — Transition Measure Is the Physical Invariant

$$ T(\phi,\psi)=|\langle\phi|\psi\rangle|^2$$

Closed evolution preserves this relation.

## 71. Principle — Transition-Measure Preservation Restricts State Transformations

$$ T'=T$$

implies unitary or antiunitary ray transformation.

## 72. Principle — Continuous Recurrence Selects Unitary Evolution

Because boundary recurrence is continuously connected to the identity,

$$ U(0)=I$$

the continuous dynamical branch is unitary.

## 73. Principle — Unitarity Preserves Normalized Realization Geometry

$$ U^\dagger U=I$$

Therefore norms, inner products, and Born transition measures are preserved.

<!-- source_pdf_page: 2468 -->

## 74. Principle — Continuous Autonomous Recurrence Forms a One- Parameter Group

$$ U(\tau_2)U(\tau_1)=U(\tau_1+\tau_2)$$

## 75. Principle — A Self-Adjoint Generator Follows

$$ U(\tau)=e^{-iK_\tau\tau}$$

## 76. Principle — The Generator Is Recurrence Before It Is Energy

$$ i\frac{d}{d\tau}|\psi(\tau)\rangle=K_\tau|\psi(\tau)\rangle$$

Energy has not yet been assigned.

## 77. Principle — Physical Clock Calibration Precedes the Hamiltonian Read

After

$$\tau\to t$$

the generator acquires inverse-time dimensions.

Then:

$$ H=\hbar K_t$$

## 78. Principle — The Abstract Schrödinger Equation Is a Physical Recurrence Projection

$$ i\hbar\frac{d}{dt}|\psi\rangle=H|\psi\rangle$$

It is not the primitive R2D law.

It is the physical generator equation for the quantum recurrence projection.

<!-- source_pdf_page: 2469 -->

## 79. Principle — Stationary State Does Not Mean Static Ontology

For

$$ H|E\rangle=E|E\rangle$$

$$|\psi(t)\rangle=e^{-iEt/\hbar}|E\rangle$$

The Born distribution can remain stationary while phase recurrence continues.

## 80. Principle — Measurement and Unitary Evolution Have Different Boundary Ownership

> same boundary → unitary recurrence,

> new enclosing boundary → measurement realization.

## 81. Logical Status

Canonical R2D

Statehood is boundary indexed.

Recurrence is defined before physical clock time.

Boundary replacement changes the count domain.

Addendum 72

Recurrent closure supplies complex cyclic phase.

Addendum 73

Normalized detector realization acquires the Born measure:

$$\mu_\psi(P)=\operatorname{Tr}(\rho P)$$

For pure rank-one alternatives:

$$\mu=|\langle\phi|\psi\rangle|^2$$

<!-- source_pdf_page: 2470 -->

New Physical Preservation Requirement

Boundary-preserving quantum recurrence preserves the transition measure:

$$|\langle\phi'|\psi'\rangle|^2=|\langle\phi|\psi\rangle|^2$$

Mathematical Representation Theorem

Such ray transformations are represented by unitary or antiunitary operators.

Continuous-Recurrence Selection

Continuous evolution connected to

$$ I$$

selects the unitary branch.

Autonomous Recurrence Representation

$$ U(\tau)=e^{-iK_\tau\tau}$$

Physical Clock Calibration

$$\tau\to t$$

Energy Calibration

$$ H=\hbar K_t$$

Derived Abstract Quantum Evolution Law

$$ i\hbar\frac{d}{dt}|\psi\rangle=H|\psi\rangle$$

Not Yet Established

This addendum does not yet derive:

- the spatial form of the Hamiltonian;
- the momentum operator;
- the kinetic operator

$$-\frac{\hbar^2}{2m}\nabla^2$$

- the physical potential V ;
- time-dependent environmental coupling from primitive R2D;

<!-- source_pdf_page: 2471 -->

• open-system nonunitary evolution;
- or the complete microscopic measurement interaction.

Those are downstream problems.

## 82. The Complete Unitary Architecture

A quantum boundary possesses native recurrence:

$$ B_n$$

Its closure receives complex phase representation:

$$\downarrow$$

$$|\psi\rangle$$

Normalized realization gives the transition measure:

$$\downarrow$$

$$|\langle\phi|\psi\rangle|^2$$

Boundary-preserving recurrence requires that measure to remain invariant:

$$\downarrow$$

$$ T'=T$$

The state transformation is therefore:

$$\downarrow$$

> unitary or antiunitary.

Continuous recurrence connected to identity selects:

$$\downarrow$$

$$ U^\dagger U=I$$

Autonomous recurrence composes:

$$\downarrow$$

$$ U(\tau_1+\tau_2)=U(\tau_2)U(\tau_1)$$

Strong continuity gives:

<!-- source_pdf_page: 2472 -->

⇓

$$ U(\tau)=e^{-iK_\tau\tau}$$

Thus:

$$\downarrow$$

$$ i\frac{d}{d\tau}|\psi(\tau)\rangle=K_\tau|\psi(\tau)\rangle$$

Physical clock calibration gives:

$$\downarrow$$

$$ t$$

Energy-frequency calibration gives:

$$\downarrow$$

$$ H=\hbar K_t$$

Therefore:

$$\downarrow$$

$$ i\hbar\frac{d}{dt}|\psi\rangle=H|\psi\rangle$$

The abstract Schrödinger equation is therefore the end of this chain, not its beginning.

## 83. Conclusion

Quantum theory is usually introduced with unitary evolution already in place.

A state vector

$$|\psi\rangle$$

is assumed to evolve according to

$$ U(t)$$

where

$$ U^\dagger U=I$$

<!-- source_pdf_page: 2473 -->

The Hamiltonian is then introduced as the generator of that evolution.

R2D reverses the explanatory order.

The first question is whether the count boundary has changed.

If it has not, then the quantum state remains a representation of the same boundary-native recurrence
domain.

No new detector macrostate has been realized.

No new enclosing classification has replaced the old one.

The relational realization structure must therefore remain invariant.

Addendum 73 identified the physically relevant relation between quantum rays:

$$ T(\phi,\psi)=|\langle\phi|\psi\rangle|^2$$

Boundary-preserving evolution requires

$$ T(\phi',\psi')=T(\phi,\psi)$$

Once quantum states are represented in the complex state geometry established by the preceding
addenda, transformations preserving this relation are unitary or antiunitary.

The recursive clock supplies the next condition.

Quantum recurrence evolves continuously in its physical phase representation.

At zero recurrence advance,

$$ U(0)=I$$

A continuously connected dynamical path cannot leave the identity through the antiunitary branch.

Therefore:

$$ U^\dagger U=I$$

Unitarity is not primitive.

It is the mathematical signature of recurrence that evolves while preserving its boundary.

For an autonomous recurrence, successive recurrence advances compose:

<!-- source_pdf_page: 2474 -->

U (τ2 )U (τ1 ) = U (τ1 + τ2 ).

Strong continuity then forces a self-adjoint generator:

$$ U(\tau)=e^{-iK_\tau\tau}$$

Hence:

$$ i\frac{d}{d\tau}|\psi(\tau)\rangle=K_\tau|\psi(\tau)\rangle$$

This relation is already the abstract mathematical form of quantum recurrence evolution.

But it is not yet an energy equation.

Only after a physical clock supplies

$$ t$$

and the empirical quantum calibration assigns

$$ E=\hbar\omega$$

does the generator acquire the energetic read

$$ H=\hbar K_t$$

The resulting equation is

$$ i\hbar\frac{d}{dt}|\psi(t)\rangle=H|\psi(t)\rangle$$

The abstract Schrödinger equation therefore appears as a projected physical law downstream of:

> boundary-native recurrence,

> complex phase,

> normalized realization,

and

> preservation of relational count structure.

This also clarifies the longstanding distinction between unitary evolution and quantum measurement.

They are not competing primitive dynamics acting inexplicably on the same ontological wavefunction.

<!-- source_pdf_page: 2475 -->

They describe different recursive situations.

When the boundary remains the same,

$$ B_n\to B_n$$

the state coordinate evolves unitarily.

When a new enclosing measurement boundary becomes realized,

$$ B_n\to B_{n+1}^{M}$$

the count domain changes.

A new distinction has been created.

Thus:

> unitary evolution = boundary-preserving recurrence,

while

> measurement = boundary replacement.

The central statement is therefore:

a quantum boundary that evolves without recursive replacement preserves the normalized realization relations among its admissible states. Preservation of the Born transition measure restricts the state representation to unitary or antiunitary transformation; continuous recurrence connected to the identity selects the unitary branch. Continuous autonomous unitary recurrence then possesses a self-adjoint generator, and physical clock and energy calibration convert that generator into the Hamiltonian. The abstract Schrodinger equation is therefore the physical projection of boundary-preserving recurrence rather than a primitive law of an ontological wavefunction.

And hence:

> boundary-preserving recurrence occurs before unitary evolution.
