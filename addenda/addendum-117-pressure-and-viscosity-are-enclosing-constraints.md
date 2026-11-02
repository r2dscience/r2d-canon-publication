---
r2d_id: "addendum-117"
title: "Addendum 117 — Pressure and Viscosity Are Enclosing Constraints"
subtitle: "Retained Normal Constraint, Dissipative Mechanical Resistance, and the Physical Stress Projection"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 117
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-01"
promotion_basis: "explicit_author_authorization_2026-11-01"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
---

# R²D Addendum 117 — Pressure and Viscosity Are Enclosing Constraints

*Retained Normal Constraint, Dissipative Mechanical Resistance, and the Physical Stress Projection*

**Status:** Author-approved for canon publication — November 1, 2026  
**Canonical basis:** R²D Parts I–IV, September 25, 2026 authoritative revision

## Abstract

Pressure and viscosity are conventionally introduced into fluid mechanics as distinct mechanical quantities. Pressure supplies normal stress, while viscosity governs the resistance associated with fluid deformation. Their gradients appear as separate terms in the Navier–Stokes equation.

Recursively Realized Distinguishability (R²D) identifies a common organizing structure: both are physical readings of constraint defined by the enclosing fluid boundary.

Part I separates enclosing constraint into retained/output and background-associated components. Part II establishes their mechanical significance in muscle, where retained constraint acquires a productive force read and background-associated constraint acquires a frictional resistance read. The same architecture admits a fluid-mechanical realization in which retained normal constraint is read as pressure and background-associated deformation constraint is read as viscous resistance.

Addendum 115 established that a directional fluid macrostate can persist while subordinate closures recur and enclosing output advances. Addendum 116 constructed the corresponding joint conservation relations for material inventory and directional momentum. These relations permit momentum throughput without material transfer and nonzero throughput without regional accumulation.

The present addendum establishes how those momentum-output relations acquire physical stress readings.

Retained normal constraint admits a pressure–volume work calibration. Unequal pressure readings on opposing enclosing interfaces produce a net normal momentum-throughput imbalance whose spatial projection is the pressure gradient. Background-associated deformation constraint admits a mechanical-power calibration. In a planar shear boundary, this maps the constraint to viscous traction. For a physically isotropic boundary with a linear deformation-constraint response, the resulting stress has the Newtonian form.

The R²D laws do not determine the joint compatibility relation or the viscosity of a particular fluid. Those properties belong to its enclosing physical boundary. The laws relate completed subordinate closure asymmetry and recurrence to the realization of the specified enclosing constraint.

**Pressure and viscosity are therefore not separate primitive causal agents. They are complementary mechanical readings of the enclosing constraint governing one recursively organized fluid realization.**

## 117.1. The Mechanical Question Left by Conservation

Addendum 116 established that an enclosing fluid boundary may admit complete momentum-output occurrences that conserve total directional momentum while redistributing it among subordinate regions.

For a collection of regions and interfaces, the exact count relation is

$$
\boxed{
\Delta\mathbf k=-D\,\Delta\mathbf z_P,
}
\tag{117.1}
$$

where $\mathbf k$ is the regional directional-count vector, $\mathbf z_P$ is the completed momentum-output record, and $D$ is the enclosing interface-incidence relation.

For internal interfaces,

$$
\mathbf1^{\mathsf T}D=0,
$$

so

$$
\boxed{
\Delta K_J=0.
}
\tag{117.2}
$$

The relation establishes conservation for the specified enclosing compatibility class.

It also permits steady regional momentum classification with nonzero completed throughput.

What equation (117.1) does not determine is the physical mechanical resistance associated with that throughput.

A conserved water boundary may admit different normal constraints, different deformation responses, or different physically readable rates under different enclosing preparations.

The distinction is foundational.

**Conservation establishes what an admissible occurrence preserves. Constraint determines which mechanically organized realizations are compatible with the enclosing state.**

Pressure and viscosity enter at this second level.

They are not required to define the invariant conserved by equation (117.1).

They enter when the enclosing fluid boundary and its completed output receive a physical mechanical calibration.

## 117.2. The Canonical Constraint Partition

Part I defines total enclosing constraint as

$$
\boxed{
C_J=C_J^{out}+C_J^\Phi.
}
\tag{117.3}
$$

The retained/output component $C_J^{out}$ enters local retention.

For a readable local transition $i\rightarrow k$,

$$
\boxed{
\Delta R_{i\rightarrow k}
=
C_J^{out}\lambda_{i\rightarrow k}.
}
\tag{117.4}
$$

The background-associated component $C_J^\Phi$ does not subtract from local possibility through this retention relation.

Both components enter the complete enclosing recurrence-weighted realization.

For a representative completed local closure $\mathcal C$, the canonical R²D law is

$$
\boxed{
\Delta A_{\mathcal C}N_{\mathcal C}
=
\left(C_J^{out}+C_J^\Phi\right)
\lambda_JN_\chi.
}
\tag{117.5}
$$

Here

$$
\Delta A_{\mathcal C}
=
\Delta P_{\mathcal C}-\Delta R_{\mathcal C}.
$$

The causal direction remains

$$
\chi^{(r)}
\Longrightarrow
(\mathcal C_a)_a\in\mathfrak D_{J,\chi}.
$$

The complete enclosing occurrence defines its compatible subordinate closures.

The closure does not create the enclosing constraint.

### Constraint is not background production

Part I also establishes the Second Law of Recursive Counting:

$$
\boxed{
\delta_{\mathcal C}\Phi_J
=
\ln\frac{\nu_H}{\nu_L}\geq0.
}
\tag{117.6}
$$

The two count relations must remain distinct.

Equation (117.5) concerns the recurrence-weighted realization of enclosing constraint.

Equation (117.6) concerns the relationship between opposed-leg occurrence nonreciprocity and enclosing nondirectional background.

In particular,

$$
\boxed{
C_J^\Phi\lambda_J
\not\equiv
\delta_{\mathcal C}\Phi_J.
}
\tag{117.7}
$$

The background-associated constraint describes how a complete enclosing realization is partitioned.

The background increment describes the nondirectional count consequence of its realized occurrence nonreciprocity.

Neither quantity is a primitive physical energy or force.

## 117.3. Muscle Provides the Mechanical Precedent

The physical interpretation of this partition was established in Part II through muscle mechanics.

At the muscle boundary, productive constraint acquires a mechanical force read, while background-associated constraint acquires a frictional force read.

The enclosing recurrence-weighted mechanical calibration is

$$
k_BT C_J^{out}\lambda_Jr_J
\longleftrightarrow
FV,
$$

and

$$
k_BT C_J^\Phi\lambda_Jr_J
\longleftrightarrow
a_HV.
$$

Their sum is the physical enclosing mechanical realization,

$$
\boxed{
k_BT C_J\lambda_Jr_J
\longleftrightarrow
(F+a_H)V.
}
\tag{117.8}
$$

Combining this calibration with the local asymmetry read recovers the Hill relationship.

The significance is not that $C^{out}$ universally equals force or that $C^\Phi$ universally equals friction.

The physical force coordinates are supplied by the muscle boundary.

The R²D law relates their recurrence-weighted realization to the asymmetry of compatible completed subordinate closures.

Fluid mechanics admits the corresponding distinction:

| R²D relationship | Muscle mechanical read | Fluid mechanical read |
|---|---|---|
| Retained/output constraint | Productive force | Retained normal pressure |
| Background-associated constraint | Frictional resistance | Viscous deformation resistance |
| Enclosing occurrence | Mechanical shortening | Directional mechanical throughput |
| Complete subordinate recurrence | Molecular-switch closure | Compatible water structural closure |
| Nondirectional background | Irreversible background read | Irreversible background read |

The analogy identifies the type of physical calibration to seek.

It does not assume identical geometric or energetic parameters for muscle and water.

## 117.4. Pressure as a Retained Normal Constraint

Pressure belongs to a mechanical read of the enclosing water boundary.

It is defined relative to the boundary's admissible volume, material inventory, energetic conditions, and normal mechanical compatibility.

Part II introduced the thermodynamic pressure–volume retention mapping

$$
\boxed{
k_BT\,dR=-p\,dV
}
\tag{117.9}
$$

for the specified isothermal physical realization.

This relationship is especially transparent for an ideal gas, where conventional statistical thermodynamics gives

$$
p=k_BT
\left(\frac{\partial S_{\mathrm{conf}}}{\partial V}\right)_{N,T}.
$$

The latter equation uses an ideal-gas configurational multiplicity model. It is not a universal R²D equation of state for liquid water.

The more general lesson is the pressure–retention correspondence:

**A normal mechanical volume constraint can be read as pressure when the enclosing retention relation is given an appropriate physical work calibration.**

### The finite normal-displacement read

Consider an enclosing water interface with physical area $\mathcal A_e$.

Let $\lambda_e^c$ be an oriented, dimensionless local compression coordinate.

Assign a physical normal displacement calibration $a_e$ such that

$$
dV_e=-\mathcal A_ea_e\,d\lambda_e^c.
$$

The negative sign identifies increasing compression with decreasing physical volume.

For a locally constant retained normal constraint, write

$$
dR_e=C_{J,e}^{out,n}\,d\lambda_e^c.
$$

Here $C_{J,e}^{out,n}$ is the retained normal-mode reading of the enclosing constraint at the selected interface. It is not a new independently acting primitive pressure force.

Let $\mathcal E_e$ be the relevant physical energy calibration per dimensionless retained-count unit.

Then

$$
\mathcal E_e\,dR_e=-p_e\,dV_e
$$

becomes

$$
\mathcal E_e C_{J,e}^{out,n}\,d\lambda_e^c
=
p_e\mathcal A_ea_e\,d\lambda_e^c.
$$

For a nonzero admissible comparison increment,

$$
\boxed{
p_e=
\frac{\mathcal E_e}{\mathcal A_ea_e}
C_{J,e}^{out,n}.
}
\tag{117.10}
$$

This is the candidate retained-constraint pressure calibration.

Its dimensions are correct:

$$
\frac{\mathrm J}{\mathrm{m^2}\mathrm m}
=
\mathrm{Pa}.
$$

When the physical constraint varies over the comparison, the corresponding differential reading is

$$
\boxed{
p_e=
\frac{\mathcal E_e}{\mathcal A_ea_e}
\left(
\frac{\partial R_e}{\partial\lambda_e^c}
\right)_{\mathrm{preparation}}.
}
\tag{117.11}
$$

Equation (117.10) is the constant-constraint special case.

### Pressure does not require ongoing compression

The pressure–volume relation defines a mechanical response to an admissible volume distinction.

It does not require the water to undergo continuous compression.

A fluid can maintain pressure when its physical volume and net material throughput are unchanged.

Thus a static pressure read must not be defined by dividing a mechanical power by a velocity that may be zero.

The pressure calibration concerns the enclosing normal constraint, not a requirement of continuous displacement.

### Pressure and the mechanical reference

Pressure differences can be read without choosing an absolute zero of pressure.

If the physical representation uses a reference pressure $p_{\mathrm{ref}}$, then under a common fixed calibration factor $\mathcal K_J$,

$$
\boxed{
p_e-p_{\mathrm{ref}}
=
\mathcal K_J
\left(
C_{J,e}^{out,n}
-
C_{J,\mathrm{ref}}^{out,n}
\right).
}
\tag{117.12}
$$

This is a comparison of physical constraint readings.

An arbitrary change of pressure datum does not change the mechanical pressure gradient.

A particular retained *useful-output* power read, however, requires a specified physical output reference. It should not depend on an arbitrary gauge convention.

## 117.5. The Enclosing Normal Momentum-Throughput Relation

We now reconnect pressure to the exact finite momentum accounting of Addendum 116.

Consider one intermediate water region $A$ enclosed between a left and right normal mechanical interface.

Let

$$
H_L
$$

be completed positive directional-momentum output entering from the left.

Let

$$
H_R
$$

be completed positive directional-momentum output leaving to the right.

The selected enclosing joint compatibility relation gives

$$
\boxed{
\Delta k_A=H_L-H_R.
}
\tag{117.13}
$$

The source and receiving boundaries carry the equal-and-opposite companion records required for total directional-count conservation.

### Equal normal throughput

If

$$
H_L=H_R,
$$

then

$$
\Delta k_A=0.
$$

The water region does not accumulate directional momentum.

Both completed normal output records can nevertheless be nonzero.

Thus

$$
\boxed{
\text{nonzero normal momentum throughput}
\not\Rightarrow
\text{net momentum accumulation}.
}
$$

### Unequal normal throughput

If

$$
H_L\neq H_R,
$$

then the region possesses a nonzero signed momentum-output imbalance.

After a physical momentum calibration $p_*$,

$$
\Delta P_A=p_*(H_L-H_R).
$$

Let the two physical faces have equal area $\mathcal A$, and let the completed records be counted over the same physical interval $\Delta t$.

If the normal-output records acquire pressure-impulse calibrations

$$
\frac{p_*H_L}{\Delta t}=p_L\mathcal A,
$$

and

$$
\frac{p_*H_R}{\Delta t}=p_R\mathcal A,
$$

then

$$
\boxed{
\left(\frac{\Delta P_A}{\Delta t}\right)_p
=
\mathcal A(p_L-p_R).
}
\tag{117.14}
$$

This is the physical pressure contribution to the finite momentum balance.

The calibration is a consistency condition between completed directional-output count and measured normal traction. It is not implied by the R²D recurrence law alone.

Pressure at a stationary interface may alternatively be read through the static retention response of Section 117.4; ongoing material flow is not required.

## 117.6. The Pressure Gradient Is a Difference of Retained Constraints

Let the water region have physical length $L$ between its two pressure-reading faces.

Its physical volume is

$$
V_A=\mathcal A L.
$$

Divide equation (117.14) by that volume:

$$
\frac1{V_A}
\left(\frac{\Delta P_A}{\Delta t}\right)_p
=
\frac{p_L-p_R}{L}.
$$

Equivalently,

$$
\boxed{
\frac1{V_A}
\left(\frac{\Delta P_A}{\Delta t}\right)_p
=
-\frac{p_R-p_L}{L}.
}
\tag{117.15}
$$

This is an exact finite physical difference relation under the specified calibration.

Where a smooth physical pressure representation is admissible,

$$
\frac{p_R-p_L}{L}
\longrightarrow
\frac{\partial p}{\partial x}.
$$

Therefore,

$$
\boxed{
\mathbf f_p=-\nabla p.
}
\tag{117.16}
$$

The pressure gradient is the spatial representation of the imbalance between enclosing normal-constraint readings.

It is not an additional primitive force introduced independently of the boundary's compatibility relation.

### Three-dimensional pressure read

For a physical fluid region $\Omega$ with oriented boundary faces $e$, the normal pressure contribution is

$$
\boxed{
\left(\frac{\Delta\mathbf P_\Omega}{\Delta t}\right)_p
=
-\sum_{e\in\partial\Omega}
p_e\mathcal A_e\mathbf n_e.
}
\tag{117.17}
$$

Here $\mathbf n_e$ is the outward normal.

For uniform pressure $p_0$,

$$
\sum_e p_0\mathcal A_e\mathbf n_e=0
$$

on a closed physical polyhedral boundary.

Hence uniform nonzero pressure need not change the fluid region's total momentum.

In the smooth continuum representation,

$$
-\int_{\partial\Omega}p\mathbf n\,dA
=
-\int_\Omega\nabla p\,dV.
$$

The gradient follows from the physical projection of face-to-face constraint differences.

### Proposition 117.1 — Retained Normal-Constraint Imbalance Produces the Pressure-Gradient Read

Let a conservation-compatible enclosing fluid boundary admit normal momentum-output records whose physical traction reads are calibrated by a scalar pressure field $p$.

Then the net pressure contribution to a region is the signed difference of its normal interface tractions.

Where the pressure field admits a smooth physical spatial projection, the corresponding momentum-change density is $-\nabla p$.

**Proof.**

The result follows by summing the oriented normal traction reads of the complete enclosing occurrence. The divergence theorem gives their smooth physical volume representation. $\square$

The proposition is exact within its stated mechanical calibration. It does not independently derive a liquid-water equation of state or a pressure field from primitive multiplicity.

## 117.7. Viscosity as a Background-Associated Mechanical Constraint

Now consider a different mechanical mode of the same enclosing fluid system.

Two neighboring water regions may retain their material inventories while admitting relative directional-momentum throughput.

Addendum 116 constructed such occurrences explicitly:

$$
\boxed{
h_M=0,\qquad h_P\neq0.
}
\tag{117.18}
$$

This is the finite-count architecture required for a shear-stress read.

The physical question is no longer which material inventory is transferred.

It is how the enclosing boundary constrains relative directional momentum throughput between neighboring water regions.

In the R²D mechanical analogy, that resistance is associated with the background-associated constraint component.

### The mechanical shear-mode calibration

Let the enclosing boundary possess a selected shear-mode occurrence $\chi_s$.

Its complete representative local closure obeys

$$
\Delta A_{\mathcal C_s}N_{\mathcal C_s}
=
C_{J,s}\lambda_{J,s}N_{\chi_s}.
$$

The shear-mode total constraint is

$$
C_{J,s}
=
C_{J,s}^{out}+C_{J,s}^{\Phi}.
$$

Suppose the physical water realization admits the mechanical-power calibration

$$
\boxed{
\mathcal P_\Phi
=
\mathcal E_s C_{J,s}^{\Phi}
\lambda_{J,s}r_{\chi_s}.
}
\tag{117.19}
$$

This is the fluid counterpart of Part II's frictional muscle-power mapping.

It is a boundary-specific physical calibration, not a universal identity between dimensionless background-associated constraint and energy production.

Let the enclosing shear occurrence have physical relative-displacement calibration $a_s$.

Its relative-velocity read is

$$
\boxed{
U=a_s\lambda_{J,s}r_{\chi_s}.
}
\tag{117.20}
$$

For positive shear orientation, let $\tau_\Phi$ be the magnitude of resisting tangential traction over interface area $\mathcal A_s$.

The corresponding physical mechanical-power read is

$$
\boxed{
\mathcal P_\Phi
=
\tau_\Phi\mathcal A_s U.
}
\tag{117.21}
$$

Combining equations (117.19)–(117.21), for nonzero shear recurrence,

$$
\tau_\Phi\mathcal A_s a_s
\lambda_{J,s}r_{\chi_s}
=
\mathcal E_s C_{J,s}^{\Phi}
\lambda_{J,s}r_{\chi_s}.
$$

Therefore,

$$
\boxed{
\tau_\Phi
=
\frac{\mathcal E_s}{\mathcal A_sa_s}
C_{J,s}^{\Phi}.
}
\tag{117.22}
$$

This is the proposed **background-associated constraint-to-viscous-traction mapping**.

It has the required dimensions of pressure.

### Orientation and magnitude must remain distinct

The primitive constraint component $C^\Phi$ is nonnegative.

Physical shear traction is oriented and changes sign when the shear orientation is reversed.

Equation (117.22) therefore determines a traction magnitude in the selected positive-shear class.

The signed physical traction additionally requires the enclosing orientation read.

This distinction prevents an invalid identification of a nonnegative scalar R²D constraint with a signed physical tensor component.

Nor does equation (117.22) imply that every nonzero $C^\Phi$ produces a nonzero mechanical shear stress at rest.

The expression was obtained within a specific nonzero shear-mode power calibration. Static resistance, yielding, and elastic storage require their own admissible physical classifications.

## 117.8. Viscosity Is the Shear-Rate Read of That Constraint

For physical planar shear, let the two velocity readings differ by $U$ across a physical separation $L$.

The shear-rate magnitude is

$$
g=\frac{|U|}{L}.
$$

For nonzero shear rate, effective dynamic viscosity is defined by

$$
\mu_{\mathrm{eff}}=\frac{\tau_\Phi}{g}.
$$

Using equation (117.22),

$$
\boxed{
\mu_{\mathrm{eff},J}
=
\frac{\mathcal E_s}{\mathcal A_sa_s}
\frac{C_{J,s}^{\Phi}}{g}.
}
\tag{117.23}
$$

Thus viscosity is a calibrated physical resistance read of the enclosing dissipative constraint **per unit shear rate**.

It is not numerically identical to the dimensionless constraint.

The constraint is determined by the water boundary and its preparation.

The R²D recurrence law describes the realization of that constraint across complete compatible closures.

### Newtonian flow as a boundary-response regime

Suppose the physical water boundary admits a small-shear response

$$
C_{J,s}^{\Phi}(g)
=
\kappa_{s,J}g+o(g),
\qquad g\rightarrow0^+.
$$

For a fixed mechanical calibration, equation (117.22) gives

$$
\tau_\Phi
=
\frac{\mathcal E_s}{\mathcal A_sa_s}
\left(
\kappa_{s,J}g+o(g)
\right).
$$

Therefore,

$$
\boxed{
\mu_0
=
\frac{\mathcal E_s}{\mathcal A_sa_s}
\kappa_{s,J}.
}
\tag{117.24}
$$

This is the Newtonian-limit viscosity.

The result follows if the physical constraint response is linear in shear rate.

The canonical R²D laws do not require every fluid to possess that linear response.

Different enclosing physical constraints may admit nonlinear shear stress, yield-like behavior, or other deformation responses.

### Proposition 117.2 — Newtonian Viscosity as a Linear Constraint Projection

Let a mechanically calibrated enclosing shear boundary satisfy equation (117.22).

If its signed physical shear-constraint response is orientation-odd and linear in sufficiently small shear rate, then its physical stress is Newtonian to first order, with viscosity given by equation (117.24).

**Proof.**

Under the stated linear response, substituting the constraint into the calibrated stress relation produces a traction proportional to the shear rate. Their ratio tends to the constant in equation (117.24). $\square$

The theorem does not derive $\kappa_{s,J}$ from abstract multiplicity. That coefficient is a property of the specified physical boundary.

## 117.9. Viscous Deformation Is Not Arbitrary Relative Motion

A three-dimensional fluid can possess neighboring velocity differences without undergoing viscous deformation.

Rigid rotation provides the relevant distinction.

Let the physical velocity-gradient tensor be

$$
G_{ij}
=
\frac{\partial u_i}{\partial x_j}.
$$

Its symmetric part is

$$
\boxed{
D_{ij}
=
\frac12
\left(
\frac{\partial u_i}{\partial x_j}
+
\frac{\partial u_j}{\partial x_i}
\right),
}
\tag{117.25}
$$

and its antisymmetric part is

$$
\Omega_{ij}
=
\frac12
\left(
\frac{\partial u_i}{\partial x_j}
-
\frac{\partial u_j}{\partial x_i}
\right).
$$

The physical velocity gradient is

$$
\mathbf G=\mathbf D+\boldsymbol\Omega.
$$

For a rigid rotation,

$$
\mathbf u=\boldsymbol\omega\times\mathbf x,
$$

the antisymmetric part may be nonzero while

$$
\boxed{
\mathbf D=0.
}
$$

An ordinary viscous fluid does not produce a deformation-associated viscous stress solely because its entire body rotates rigidly relative to a reference frame.

Therefore, the relevant physical constraint response must distinguish deformation from rigid rotation.

For an ordinary fluid boundary without separate couple-stress modes, write the mechanical dissipative response schematically as

$$
\boxed{
\mathsf B_J^\Phi
=
\mathcal C_J^\Phi[\mathbf D].
}
\tag{117.26}
$$

The symbol $\mathsf B_J^\Phi$ denotes a signed dimensionless *physical projection* of the boundary's deformation-resistance constraints.

It is not a new primitive R²D tensor replacing the scalar $C_J^\Phi$.

The physical classification must be established at the enclosing mechanical boundary.

## 117.10. The Symmetric Viscous-Stress Tensor

The finite momentum-throughput construction of Addendum 116 can be extended to three physical directional coordinates.

Across an interface with outward normal $\mathbf n$, the physically calibrated momentum traction may have components in all three directions.

A local tensor representation is admissible where these traction reads compose linearly under the corresponding physical surface classification:

$$
\mathbf t(\mathbf n)=\mathbf T\mathbf n.
$$

Its components are physical readings of enclosing directional-momentum output.

Their existence does not make the continuum stress tensor primitive.

### Symmetry from the physical angular-momentum classification

For an ordinary fluid without independent internal couple stresses or spin-torque accumulation, the physical angular-momentum balance requires

$$
\boxed{
T_{ij}=T_{ji}.
}
\tag{117.27}
$$

This is a property of the physically calibrated mechanical boundary.

The R²D axioms alone do not require every conceivable material boundary to exclude independent couple-stress distinctions.

The normal and shear mechanical classifications must therefore respect the selected physical angular-momentum relation.

### Isotropic linear deformation response

For a physically isotropic water boundary, suppose the dissipative constraint has a local linear response to the symmetric rate-of-deformation tensor.

Decompose

$$
\mathbf D=
\mathbf D^\circ+\frac13\theta\mathbf I,
$$

where

$$
\mathbf D^\circ
=
\mathbf D-\frac13(\operatorname{tr}\mathbf D)\mathbf I,
$$

and

$$
\theta=\operatorname{tr}\mathbf D=\nabla\cdot\mathbf u.
$$

An isotropic linear map on symmetric tensors distinguishes a trace-free deformation sector and a scalar volumetric sector.

Its signed dimensionless constraint-response read therefore has the form

$$
\boxed{
\mathsf B_J^\Phi
=
2\kappa_{s,J}\mathbf D^\circ
+
\kappa_{b,J}\theta\mathbf I.
}
\tag{117.28}
$$

Assume, for this physical regime, that these modes admit a common stress calibration

$$
\sigma_J=
\frac{\mathcal E_J}{\mathcal A_Ja_J}.
$$

The physical viscous stress is

$$
\boldsymbol\tau^\Phi
=
\sigma_J\mathsf B_J^\Phi.
$$

Define

$$
\mu_J=\sigma_J\kappa_{s,J},
$$

and

$$
\zeta_J=\sigma_J\kappa_{b,J}.
$$

Then

$$
\boxed{
\boldsymbol\tau^\Phi
=
2\mu_J\mathbf D^\circ
+
\zeta_J(\nabla\cdot\mathbf u)\mathbf I.
}
\tag{117.29}
$$

This is the standard isotropic Newtonian viscous-stress form.

The coefficients $\mu_J$ and $\zeta_J$ are the physical shear and bulk viscosity readings.

They are not primitive R²D constants.

### The incompressible fluid limit

For an incompressible physical water representation,

$$
\nabla\cdot\mathbf u=0.
$$

Hence

$$
\boxed{
\boldsymbol\tau^\Phi=2\mu_J\mathbf D.
}
\tag{117.30}
$$

For spatially constant $\mu_J$,

$$
\nabla\cdot\boldsymbol\tau^\Phi
=
\mu_J\nabla^2\mathbf u.
$$

Thus

$$
\boxed{
\nabla\cdot\boldsymbol\tau^\Phi
=
\mu_J\nabla^2\mathbf u.
}
\tag{117.31}
$$

The Navier–Stokes viscous term is recovered as the spatial divergence of the mechanically calibrated dissipative stress.

The Laplacian is not an independently introduced primitive source of molecular momentum transfer.

It is the differential representation of a specified symmetric, isotropic, linear boundary-constraint response.

The linearity and isotropy conditions are physical assumptions about the water boundary, not theorems of the primitive R²D counting laws.

## 117.11. Pressure and Viscosity Are Different Constraint Readings of One Momentum Relation

We can now combine the retained and dissipative mechanical reads.

For an ordinary fluid without additional elastic or couple-stress modes, define the physical force-stress tensor

$$
\boxed{
\mathbf T
=
-p\mathbf I+\boldsymbol\tau^\Phi.
}
\tag{117.32}
$$

The pressure term is the retained isotropic normal-constraint read.

The viscous term is the background-associated deformation-resistance read.

They belong to the same encompassing physical momentum classification.

They do not require separately originating primitive mechanisms.

The traction exerted on a selected fluid region by the material outside its physical boundary is

$$
\boxed{
\mathbf t(\mathbf n)
=
-p\mathbf n+\boldsymbol\tau^\Phi\mathbf n.
}
\tag{117.33}
$$

Equivalently, with outward momentum-flux sign convention, the mechanical contribution is

$$
\boxed{
\mathbf j_P^{\mathrm{mech}}(\mathbf n)
=
p\mathbf n-\boldsymbol\tau^\Phi\mathbf n.
}
\tag{117.34}
$$

The distinction between traction exerted *on* a region and momentum flux directed *out* of it fixes the signs.

### The one-boundary principle

**Pressure and viscosity are complementary physical reads of the enclosing mechanical constraint acting within the same admissible momentum-throughput relation.**

The pressure read concerns retained normal compatibility.

The viscosity read concerns background-associated deformation resistance.

The mechanical momentum-output relation is prior to both physical projections.

The two stress contributions do not establish two independently causal layers beneath the fluid.

## 117.12. A Complete Finite Pressure–Viscosity Consistency Example

Return to the water-inventory and momentum-output construction of Addendum 116.

Consider one steady water region $A$ between a supplying boundary $U$ and a receiving boundary $L$, with an enclosing mechanical wall.

Let a complete joint occurrence carry one unit of material-throughput output entering and one leaving:

$$
h_{M,I}=h_{M,O}=1.
$$

Therefore,

$$
\boxed{
\Delta q_A=1-1=0.
}
\tag{117.35}
$$

Let the bulk advective momentum readings be equal at inlet and outlet, so their net contribution to regional momentum accumulation is zero.

Now specify the following complete mechanical normal-impulse classification:

| Joint mechanical read | Signed momentum-count contribution |
|---|---:|
| Retained inlet pressure read | $+3$ |
| Retained outlet pressure read | $-2$ |
| Wall-resistance read | $-1$ |
| Net regional momentum-count change | $0$ |

The complete compatibility relation is

$$
\boxed{
\Delta k_A^{\mathrm{mech}}
=
3-2-1=0.
}
\tag{117.36}
$$

The water inventory and regional momentum classification remain unchanged.

Nevertheless, the enclosing boundary distinguishes continued material throughput, normal pressure transmission, and wall-resistance output.

### Physical calibration

Let the inlet and outlet have the same physical area $\mathcal A$.

Choose a common normal-impulse calibration $I_*$ per count unit over a physical interval $\Delta t$.

Then the pressure readings satisfy

$$
p_I\mathcal A\Delta t=3I_*,
$$

and

$$
p_O\mathcal A\Delta t=2I_*.
$$

The wall's resisting impulse is

$$
I_{\mathrm{wall}}=I_*.
$$

Thus

$$
\boxed{
(p_I-p_O)\mathcal A
=
F_{\mathrm{wall}}.
}
\tag{117.37}
$$

The mechanical momentum balance is exact within the specified finite calibration.

It does not require the material inventory to accumulate or the regional flowing macrostate to change.

Let the complete material-output occurrence additionally acquire a physical volume read $v_*$.

If the enclosing output recurs at physically calibrated rate $r_\chi$, the volumetric throughput is

$$
Q=v_*r_\chi.
$$

For a steady hydraulic realization with no net storage or unresolved change in kinetic, gravitational, or other energetic output, the pressure-work loss is

$$
\boxed{
\mathcal P_\Phi=(p_I-p_O)Q.
}
\tag{117.38}
$$

This is the hydraulic mechanical-power read of the dissipative constraint.

A retained useful-output power can also be assigned when a physical output reference is specified. For example, against a fixed reference pressure $p_{\mathrm{ref}}$,

$$
\mathcal P_{\mathrm{ret}}
=
(p_O-p_{\mathrm{ref}})Q.
$$

The usefulness of that output depends on the specified receiving boundary.

Neither the retained-output partition nor the background-associated partition should be defined using an arbitrary pressure datum without identifying its physical reference.

### What the example establishes

One enclosing occurrence admits simultaneous material throughput, momentum conservation, unequal pressure constraint, and resisting wall output.

The mechanical power difference is consistent with the same joint organization.

It does not determine water viscosity from the integers $3,2,1$.

Those integers classify one possible finite occurrence; their dimensional calibration and the material's constitutive response must be established independently.

## 117.13. Recurrence-Weighted Mechanical Realization

The finite example becomes part of the R²D realization law only when the enclosing occurrence is assigned its compatible completed subordinate closures.

Let

$$
\mathcal C:
i\xrightarrow{H}k\xrightarrow{L}i
$$

be a representative completed closure belonging to the enclosing mechanical occurrence $\chi$.

Its complete native multiplicity return satisfies

$$
\boxed{
\Delta S_{\mathcal C}=0.
}
$$

Its possibility asymmetry is

$$
\Delta P_{\mathcal C}
=
\ln\left(
\frac{K_k^HK_i^L}
{K_i^HK_k^L}
\right),
$$

and its residual asymmetry is

$$
\Delta A_{\mathcal C}
=
\Delta P_{\mathcal C}-\Delta R_{\mathcal C}.
$$

The canonical law is

$$
\boxed{
\Delta A_{\mathcal C}N_{\mathcal C}
=
\left(C_J^{out}+C_J^\Phi\right)
\lambda_JN_\chi.
}
\tag{117.39}
$$

Where the two count readings receive the same independently specified physical clock calibration,

$$
\boxed{
\Delta A_{\mathcal C}r_{\mathcal C}
=
\left(C_J^{out}+C_J^\Phi\right)
\lambda_Jr_\chi.
}
\tag{117.40}
$$

The law applies to the complete enclosing occurrence and its representative compatible closure.

It does not separately postulate one closure recurrence law for pressure and a second for viscosity.

The two mechanical readings partition the constrained realization of the same enclosing relation.

### Conditional energetic projection

If that complete occurrence admits one energetic calibration $\mathcal E_J$, its physical mechanical-power reads may satisfy

$$
\boxed{
\mathcal E_J\Delta A_{\mathcal C}r_{\mathcal C}
=
\mathcal E_J
\left(C_J^{out}+C_J^\Phi\right)
\lambda_Jr_\chi.
}
\tag{117.41}
$$

The retained mechanical output and background-associated resistance are then the two calibrated portions of the right side.

This is the fluid counterpart of the muscle mechanical calibration.

But the R²D law itself is dimensionless.

The physical energetic interpretation in equation (117.41) requires independent calibration of the selected complete occurrence.

One must not define the local closure asymmetry or its energetic scale from the target fluid power and then present the equality as an independent prediction.

## 117.14. The Second Law Remains a Separate Relationship

A viscous flow may convert supplied mechanical work into a thermal background read.

For a physically Newtonian fluid, the mechanical deformation-power density is

$$
\boxed{
\mathcal P_\Phi^{\mathrm{vol}}
=
\boldsymbol\tau^\Phi:\mathbf D.
}
\tag{117.42}
$$

Using equation (117.29),

$$
\boxed{
\mathcal P_\Phi^{\mathrm{vol}}
=
2\mu_J\mathbf D^\circ:\mathbf D^\circ
+
\zeta_J(\nabla\cdot\mathbf u)^2.
}
\tag{117.43}
$$

For an ordinary passive fluid, the physically calibrated resistance coefficients satisfy

$$
\mu_J\geq0,
\qquad
\zeta_J\geq0.
$$

Consequently,

$$
\mathcal P_\Phi^{\mathrm{vol}}\geq0.
$$

This is a physical mechanical-dissipation condition.

It is not the primitive definition of the R²D Second Law.

The latter remains

$$
\boxed{
\delta_{\mathcal C}\Phi_J
=
\ln\frac{\nu_H}{\nu_L}.
}
\tag{117.44}
$$

If a specified enclosing thermal boundary completely receives the dissipated mechanical work, then physical energetic closure can relate the mechanical loss to a measured thermal-background increment.

That physical relation must be established for the same complete joint occurrence and its appropriate comparison domain.

It does not authorize the primitive identification

$$
C_J^\Phi\lambda_J
=
\delta_{\mathcal C}\Phi_J.
$$

The distinction is essential.

Retained pressure constraint can be mechanically active without net dissipative background production.

Dissipative deformation constraint can produce a physical background read even while the flowing macrostate and its conserved regional inventory remain unchanged.

Pressure, viscosity, and background production are therefore related, but they are not one interchangeable quantity.

## 117.15. The Navier–Stokes Mechanical Terms Are a Common Projection

Addendum 116 constructed the physical advective momentum-flux read under a selected single-fluid mass-barycentric calibration:

$$
\boxed{
\mathbf F_{\mathrm{adv}}
=
\rho\mathbf u\otimes\mathbf u.
}
$$

The present addendum supplies the complementary mechanical contribution:

$$
\boxed{
\mathbf F_{\mathrm{mech}}
=
p\mathbf I-\boldsymbol\tau^\Phi.
}
$$

Their sum is

$$
\boxed{
\mathbf F_{\mathrm{total}}
=
\rho\mathbf u\otimes\mathbf u
+
p\mathbf I
-
\boldsymbol\tau^\Phi.
}
\tag{117.45}
$$

This is the outward physical momentum-flux representation.

The associated conservative momentum balance is

$$
\boxed{
\frac{\partial(\rho\mathbf u)}{\partial t}
+
\nabla\cdot
(\rho\mathbf u\otimes\mathbf u)
=
-\nabla p
+
\nabla\cdot\boldsymbol\tau^\Phi
+
\rho\mathbf f.
}
\tag{117.46}
$$

Here $\rho\mathbf f$ is an additional physically admitted body-force density, where present.

It is not identified with the primitive R²D constraint.

For constant-density incompressible flow, with constant Newtonian shear viscosity,

$$
\nabla\cdot\boldsymbol\tau^\Phi
=
\mu\nabla^2\mathbf u.
$$

Equation (117.46) then becomes

$$
\boxed{
\rho
\left(
\frac{\partial\mathbf u}{\partial t}
+
(\mathbf u\cdot\nabla)\mathbf u
\right)
=
-\nabla p
+
\mu\nabla^2\mathbf u
+
\rho\mathbf f.
}
\tag{117.47}
$$

This is the familiar incompressible Navier–Stokes equation.

Its reconstruction follows the logical sequence

$$
\boxed{
\begin{gathered}
\text{Enclosing water compatibility}\\
\downarrow\\
\text{Conserved inventory and momentum output}\\
\downarrow\\
\text{Retained and background-associated constraint}\\
\downarrow\\
\text{Recurrence-weighted mechanical realization}\\
\downarrow\\
\text{Physical mass, traction, and clock calibration}\\
\downarrow\\
\text{Continuum Navier–Stokes representation}.
\end{gathered}
}
$$

The differential equation is not treated as primitive.

Nor are its pressure and viscous terms assigned independent foundational causal priority.

The conventional form is recovered where the prepared physical water boundary satisfies the stated mass-barycentric, traction, isotropy, linearity, and continuum conditions.

This is a conditional reconstruction, not yet a unique derivation of the water constitutive law from native counts alone.

## 117.16. What Determines the Physical Constraint?

A final distinction is necessary.

The canonical R²D laws do not calculate the enclosing water compatibility relation.

They relate counts once that relation is defined.

Accordingly, they do not determine a universal viscosity, a universal water pressure, or a universal pressure–flow relation.

Different physical fluids, temperatures, confinement geometries, and mechanical preparations may admit different deformation-constraint responses.

For example, two mechanically calibrated fluid boundaries may obey

$$
\tau_1(g)=\mu g
$$

and

$$
\tau_2(g)=\alpha g^3,
$$

respectively.

Both can satisfy the same form of material and momentum conservation.

Both can have nonnegative mechanical dissipation for appropriately oriented shear.

Their difference lies in the physical boundary's constraint response, not in a different primitive statistical-mechanical ontology.

Likewise, pressure depends on the enclosing thermodynamic and mechanical state.

For a liquid treated as incompressible, pressure often acts as the physical constraint enforcing the admitted volume and momentum relationship, rather than as an independently prescribed equation of state.

Its spatial field is determined jointly with the enclosing flow and boundary conditions.

R²D places those physical relationships where they belong: in the selected boundary compatibility and constraint, not in a universal bottom-up constituent mechanism.

## 117.17. Logical Status

The results of this addendum have three different mathematical statuses.

### Exact count consequences

For the specified enclosing joint compatibility relations:

1. Equal-and-opposite internal momentum-output records conserve total directional momentum.
2. Unequal interface throughputs can change regional momentum without changing the enclosing total.
3. Zero regional momentum accumulation can coexist with nonzero completed mechanical throughput.
4. Material-inventory transfer and mechanical momentum transfer are distinct output classifications.
5. The complete enclosing occurrence may possess both retained and background-associated constraint readings without defining independent primitive occurrence pathways.

These results are established at the finite count level by the preceding addenda and the explicit constructions used here.

### Canonical R²D realization relationships

The enclosing occurrence owns its compatible complete subordinate closures.

Local retention is defined by the productive/output component of enclosing constraint.

The complete constraint enters the recurrence-weighted R²D law.

Opposed-leg occurrence nonreciprocity is separately related to enclosing background through the Second Law of Recursive Counting.

These are canonical R²D relationships.

### Conditional physical mappings

The following require domain-specific mechanical calibration:

1. Retained normal constraint as pressure.
2. Normal momentum-output imbalance as pressure-gradient force density.
3. Background-associated deformation constraint as viscous traction.
4. A linear, isotropic constraint response as Newtonian viscous stress.
5. A sufficiently smooth spatial field representation as the differential Navier–Stokes equation.

The mappings are mathematically consistent with the count architecture but are not independently determined by the primitive axioms alone.

This addendum therefore does not claim to calculate the viscosity of water from abstract multiplicity or to prove that all fluid boundaries are Newtonian.

It establishes a common enclosing-constraint architecture for their mechanical readings.

## 117.18. Principle — Retained Pressure and Dissipative Viscosity Are Complementary Enclosing Constraint Reads

**A fluid boundary defines the mechanical compatibility under which conserved directional momentum is transmitted. Its retained normal constraint acquires the physical read of pressure, while its background-associated deformation constraint acquires the physical read of viscous resistance.**

These are different physical projections of one enclosing mechanical organization.

The R²D laws relate the complete constraint to compatible subordinate closure asymmetry and enclosing occurrence recurrence.

The physical boundary determines the relevant normal, tangential, energetic, geometric, and constitutive calibrations.

Consequently,

$$
\boxed{
\text{pressure}
\neq
\text{primitive normal pushing mechanism},
}
$$

and

$$
\boxed{
\text{viscosity}
\neq
\text{primitive molecular-friction mechanism}.
}
$$

Both remain real and measurable mechanical quantities at their operative physical boundaries.

Their causal interpretation is reversed.

The enclosing constraint defines the admissible mechanical realization. Subordinate events realize that constraint; they do not establish the enclosing relation from which the physical pressure and viscosity readings are obtained.

## Conclusion — Constraint Before Force

Addendum 115 established that sustained flow is the persistence of an enclosing directional fluid state compatible with recurrent output.

Addendum 116 established that material inventory and directional momentum may be conserved while their throughputs continue, and that momentum throughput need not be accompanied by material transfer.

The present addendum establishes the corresponding mechanical constraint partition.

Pressure is the retained normal-constraint read.

Viscosity is the background-associated deformation-resistance read.

Both are properties of the enclosing fluid organization.

The pressure gradient is the physical spatial reading of unequal retained normal constraints across a water region.

The viscous stress is the calibrated response of the background-associated deformation constraint. Its divergence is the physical spatial reading of unequal mechanical momentum throughput.

Under the appropriate continuum and constitutive conditions, these readings recover the pressure and viscous terms of Navier–Stokes.

The important result is not that new forces have been discovered.

It is that the familiar forces have been returned to their mathematical origin as boundary-defined constraint readings.

**The water's enclosing constraint organizes the momentum relations. Pressure and viscosity are how that organization becomes mechanically readable.**

The next addendum will bring continuity, advection, retained pressure, dissipative viscosity, and the recurrence-weighted R²D law together into a single audited physical Navier–Stokes projection.

---

## Related Canon and Addenda

- R²D Part I — *A Theory of Dimensionless Recursive Counting*, especially §§3.5–3.10.
- R²D Part II — *Joint Readability of Recurrence and Distinguishability*, especially Chapters 7, 11, and 12.
- R²D Part IV — *Projection: The Physics Constructed from What Remains*.
- Addendum 1 — *Recursive Replacement Precedes the Formal Navier–Stokes Singularity*.
- Addendum 105 — *The Observational Inversion*.
- Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*.
- Addendum 112 — *Sampled Multiplicity Before Thermal Fluctuations*.
- Addendum 115 — *What Sustains Flow? Persistent Directional Occupancy, Complete Local Closure, and Enclosing Recurrence*.
- Addendum 116 — *Conservation Before Transport: Boundary-Owned Water Inventory, Directional Momentum Throughput, and the Advective Projection*.
