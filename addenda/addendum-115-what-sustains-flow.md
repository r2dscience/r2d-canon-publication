---
r2d_id: "addendum-115"
title: "Addendum 115 — What Sustains Flow?"
subtitle: "Persistent Directional Occupancy, Complete Local Closure, and Enclosing Recurrence"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 115
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

# R²D Addendum 115 — What Sustains Flow?

*Persistent Directional Occupancy, Complete Local Closure, and Enclosing Recurrence*

**Status:** Author-approved for canon publication — November 1, 2026  
**Canonical basis:** R²D Parts I–IV, September 25, 2026 authoritative revision

## Abstract

What sustains fluid flow? Conventional physical descriptions commonly begin with moving material constituents and construct macroscopic transport from their trajectories. Recursively Realized Distinguishability (R²D) begins with the enclosing boundary that defines the fluid state, its possible realizations, and the directional occurrences compatible with that state.

A flowing fluid is not defined by a sequence of molecular displacements. It is a boundary-defined directional macrostate whose enclosing relation admits recurrent directed output. The flowing macrostate can remain unchanged while compatible subordinate configurations vary, completed subordinate closures recur, and the enclosing boundary continues to register distinguishable directional occurrences.

This addendum establishes the count architecture of sustained flow. Native multiplicity defines the available subordinate possibilities. Enclosing-compatible multiplicity and productive retention organize directional occupancy. Completed subordinate returns can possess nonzero enclosing-defined asymmetry even though their native multiplicity closes exactly. The recurrence-weighted R²D law relates that asymmetry to distinguishable enclosing output without requiring persistent subordinate state identity.

Three relations must therefore remain separate: selection of a directional fluid macrostate, recurrence of completed compatible subordinate closures, and recurrence of directed enclosing output. None alone establishes the others.

The resulting principle is that **the enclosing compatibility relation sustains the directional organization of flow; subordinate processes realize that organization but do not create the possibility landscape that defines it.**

This extends Addendum 112, *Sampled Multiplicity Before Thermal Fluctuations*, from thermodynamic sampling to fluid motion. Molecular trajectories remain valid physical representations where separately established, but they are not the primitive organizing cause of the enclosing flowing state. Conservation, pressure, viscosity, and the Navier–Stokes projection are developed in subsequent addenda.

## 115.1. The Question: What Is Doing the Flowing?

A fluid may remain in a steady flowing state while water continually passes an observation boundary.

The physical velocity field may satisfy

$$
\frac{\partial \mathbf u}{\partial t}=0
$$

while the fluid has nonzero directional throughput.

Thus, an unchanged macroscopic state does not imply the absence of physical occurrence.

This elementary observation conceals a foundational distinction.

The water boundary may continue to occupy the same directional macrostate even though the enclosing system records new completed output occurrences. Repeated subordinate observations may also differ without changing that macrostate.

These are three different statements:

1. The fluid's directional macrostate remains occupied.
2. Compatible subordinate realizations continue to occur.
3. The enclosing boundary continues to distinguish directed output.

A conventional molecular description may represent these relationships using the motion of material constituents. R²D asks what must already be defined for those constituents, their motions, and the resulting fluid state to acquire distinct scientific meaning.

The answer begins with the enclosing boundary.

The boundary defines the fluid's readable state, its compatible subordinate realizations, and which completed occurrences count as directed transport.

The constituent trajectories do not define the enclosing possibility landscape whose realization they describe.

## 115.2. The Fluid Boundary Defines Direction

Let $B_J$ be an enclosing boundary containing the water system, its mechanical reference, and a directional-output read.

For a minimal directional classification, let

$$
\mathcal M_W=\{M_-,M_0,M_+\}.
$$

Here:

- $M_+$ is a positively directed water macrostate relative to the selected reference.
- $M_-$ is the oppositely directed water macrostate.
- $M_0$ is a nondirectional water macrostate relative to that same classification.

These labels are readable macrostates, not individual molecular velocities.

They are also not claims that physical water has only three possible states. The classification distinguishes one selected directional relationship while leaving other fluid distinctions available to be classified separately.

Direction itself requires a reference.

A local directional alternative cannot define its own zero. The nondirectional condition belongs to an enclosing comparison among compatible alternatives.

Part IV establishes this ordering for physical motion: the mechanical reference is enclosing, while the local directional read is defined relative to it.

Consequently, the classification

$$
M_+
$$

does not possess an absolute direction independently of $B_J$.

It is a boundary-relative directional distinction.

### Native multiplicity

Let

$$
W_r=|\pi_W^{-1}(M_r)|
$$

be the native multiplicity of water macrostate $M_r$, for $r\in\{-,0,+\}$.

Its logarithmic entropy is

$$
S_r=\ln W_r.
$$

The native multiplicity counts the possible compatible subordinate realizations assigned to each water macrostate.

It does not count how many times the macrostate has been observed.

Nor does it count how many completed directed fluid-output occurrences have occurred.

The native landscape is established by the boundary classification before a particular realization occupies it.

## 115.3. Enclosing Possibility Selects Directional Occupancy

The native multiplicity of a local water macrostate does not independently determine which directional state will be preferentially occupied under a given enclosing preparation.

For each $M_r$, define

$$
\Theta_{J|r}
$$

as the multiplicity of enclosing realizations compatible with that water macrostate.

The mean compatible enclosing extension multiplicity per native local possibility is

$$
K_{J|r}=\frac{\Theta_{J|r}}{W_r}.
$$

R²D defines possibility as

$$
P_r=\ln K_{J|r}.
$$

For the transition from nondirectional to positively directed water,

$$
M_0\rightarrow M_+,
$$

the directional possibility difference is

$$
\Delta P_{0\rightarrow+}
=
\ln\left(
\frac{\Theta_{J|+}/W_+}
{\Theta_{J|0}/W_0}
\right).
$$

The corresponding native multiplicity difference is

$$
\Delta S_{0\rightarrow+}
=
\ln\frac{W_+}{W_0}.
$$

Therefore,

$$
\boxed{
\Delta S_{0\rightarrow+}
+
\Delta P_{0\rightarrow+}
=
\ln\frac{\Theta_{J|+}}{\Theta_{J|0}}.
}
$$

This is an exact possible-count identity.

R²D distinguishes this possibility relation from realized occupancy.

Let $c_r$ be the realized occupancy count of macrostate $M_r$ in the specified realization domain.

The canonical occupancy-realization relation is

$$
\Delta G_{0\rightarrow+}
=
\Delta\tau_{0\rightarrow+}
+
\Delta A_{0\rightarrow+},
$$

with

$$
\Delta A_{0\rightarrow+}
=
\Delta P_{0\rightarrow+}
-
\Delta R_{0\rightarrow+}.
$$

Where state occurrence proportionally realizes native multiplicity,

$$
\Delta\tau_{0\rightarrow+}
\approx
\Delta S_{0\rightarrow+}.
$$

It follows that

$$
\boxed{
\frac{c_+}{c_0}
\approx
\frac{\Theta_{J|+}}{\Theta_{J|0}}
e^{-\Delta R_{0\rightarrow+}}.
}
\tag{115.1}
$$

The positively directed macrostate has greater occupancy support than the nondirectional macrostate when

$$
\boxed{
\ln\frac{\Theta_{J|+}}{\Theta_{J|0}}
>
\Delta R_{0\rightarrow+}.
}
\tag{115.2}
$$

A uniquely favored positive directional mode must also be favored over the negative alternative.

The result is that **enclosing compatibility and retention organize directional occupancy**.

No constituent trajectory has created the enclosing multiplicities in equation (115.1).

### A finite counting demonstration

Consider a minimal water-oriented classification of two binary peers:

$$
(+,+),\quad(+,-),\quad(-,+),\quad(-,-).
$$

Classify the possible joint realizations as

$$
M_+=\{(+,+)\},
$$

$$
M_0=\{(+,-),(-,+)\},
$$

$$
M_-=\{(-,-)\}.
$$

Their native multiplicities are

$$
\boxed{
W_+=1,\qquad W_0=2,\qquad W_-=1.
}
$$

Now hold that entire native classification fixed.

Under one neutral enclosing compatibility relation, let

$$
(\Theta_{J|+},\Theta_{J|0},\Theta_{J|-})
=
(2,4,2).
$$

The nondirectional state has the largest compatible multiplicity.

Under a second enclosing condition, let

$$
(\Theta_{J|+},\Theta_{J|0},\Theta_{J|-})
=
(5,4,2).
$$

The native multiplicities have not changed.

With zero differential productive retention in the relevant occupancy comparisons, the proportional-realization relation gives

$$
\frac{c_+}{c_0}\approx\frac54,
$$

and

$$
\frac{c_+}{c_-}\approx\frac52.
$$

Thus the same native water multiplicity landscape permits a change from nondirectional preference to positive directional preference when the enclosing compatibility relation changes.

This is a finite counting construction, not a derived multiplicity model of liquid water.

It establishes that the preferred directional macrostate need not originate from a constituent trajectory or a change in native multiplicity.

The enclosing relation supplies the directional organization.

## 115.4. Directional Occupancy Does Not Yet Establish Flow

There is an essential distinction between a directionally occupied water state and recurring directional output.

A boundary may favor $M_+$ without admitting a completed output occurrence through the selected interface.

For example, an enclosing mechanical constraint may permit a directional internal water classification while preventing material throughput at a blocked outlet.

Conversely, a directional output occurrence may be admitted under a preparation in which the positive water macrostate is not the most populated alternative across all possible preparations.

Therefore,

$$
\boxed{
\text{directional occupancy preference}
\not\Rightarrow
\text{completed directional throughput}.
}
$$

A complete R²D description of sustained flow requires both the readable water state and a distinguishable enclosing occurrence.

This distinction is concealed when a flowing macrostate is interpreted as nothing more than a collection of independently moving molecules.

## 115.5. A Persistently Flowing State Can Have Recurrent Enclosing Output

Let the enclosing boundary distinguish an integer directional-output coordinate

$$
z\in\mathbb Z.
$$

This is a completed output-record coordinate. It is not the position of an identified molecule.

Define the enclosing state

$$
J_{+,z}=(M_+,z,\gamma_J),
$$

where $\gamma_J$ records the relevant enclosing preparation, mechanical reference, and compatible supply/background conditions.

A positive enclosing output occurrence is

$$
\boxed{
\chi_+:
J_{+,z}
\longrightarrow
J_{+,z+1}.
}
\tag{115.3}
$$

The water classification remains positively directed:

$$
M_+\longrightarrow M_+.
$$

But the enclosing states differ:

$$
J_{+,z}\neq J_{+,z+1}.
$$

Thus the completed output has a nonzero enclosing distinguishability even though the water's directional macrostate has not changed.

### Proposition 115.1 — Persistent Directional Occupancy Is Compatible with Nonzero Enclosing Recurrence

Let $B_J$ distinguish a water macrostate $M_+$ and an output coordinate $z$. Suppose its compatibility relation admits completed occurrences

$$
\chi_+:
(M_+,z)\rightarrow(M_+,z+1).
$$

Then any finite sequence of such occurrences satisfies

$$
\boxed{
M_f=M_i=M_+,
}
$$

while

$$
\boxed{
z_f-z_i=N_{\chi_+}.
}
\tag{115.4}
$$

**Proof.**

Every admitted occurrence preserves the $M_+$ classification and increments $z$ by one.

After $N_{\chi_+}$ completed occurrences, the water classification remains $M_+$ and the output record has increased by $N_{\chi_+}$.

Therefore persistent water-state classification and nonzero directional-output recurrence are simultaneously possible. $\square$

The result is structural. It does not establish that a particular water boundary admits $\chi_+$ or determine its realized recurrence count.

Those properties belong to the specified enclosing compatibility and realization relations.

### Opposed output classes

If the enclosing boundary also admits reverse output occurrences,

$$
\chi_-:
(M_+,z)\rightarrow(M_+,z-1),
$$

then

$$
\boxed{
z_f-z_i
=
N_{\chi_+}-N_{\chi_-}.
}
\tag{115.5}
$$

Hence positive net throughput requires

$$
\boxed{
N_{\chi_+}>N_{\chi_-}.
}
$$

This condition is separate from the statement that $M_+$ is the favored occupancy mode.

Both output orientations may remain compatible while the positive water-state classification persists.

The water state and the net output current are different readable distinctions.

## 115.6. Completed Subordinate Closure Does Not Require Enclosing Return

We now identify the local realization compatible with an enclosing directional occurrence.

Let $B_{n,a}$ be a representative subordinate boundary with two readable macrostates, $i$ and $k$.

A complete local return has the form

$$
\boxed{
\mathcal C_a:
i\xrightarrow{H}k\xrightarrow{L}i.
}
\tag{115.6}
$$

The local structural state returns.

Its native multiplicity difference is

$$
\Delta S_{i\rightarrow k}
=
\ln\frac{W_k}{W_i},
$$

and the return difference is

$$
\Delta S_{k\rightarrow i}
=
\ln\frac{W_i}{W_k}.
$$

Therefore,

$$
\boxed{
\Delta S_{\mathcal C_a}=0.
}
\tag{115.7}
$$

This result is exact.

But the enclosing compatibility relation organizing the $H$ leg need not be the same as the one organizing the $L$ leg.

Let the corresponding mean compatible extension multiplicities be

$$
K_i^H,\quad K_k^H,
\qquad
K_i^L,\quad K_k^L.
$$

The possibility accumulated around the complete local return is

$$
\boxed{
\Delta P_{\mathcal C_a}
=
\ln\left(
\frac{K_k^HK_i^L}
{K_i^HK_k^L}
\right).
}
\tag{115.8}
$$

It vanishes only when

$$
K_k^HK_i^L=K_i^HK_k^L.
$$

Thus a completed local return does not generally imply an enclosing possibility return.

The productive retention accumulated around the same closure is

$$
\Delta R_{\mathcal C_a}
=
\lambda_{i\rightarrow k}
\left(
C_J^{out,H}-C_J^{out,L}
\right),
$$

using the signed reversal of local distinguishability on the return leg.

The remaining closure asymmetry is

$$
\boxed{
\Delta A_{\mathcal C_a}
=
\Delta P_{\mathcal C_a}
-
\Delta R_{\mathcal C_a}.
}
\tag{115.9}
$$

The complete local realization can therefore satisfy

$$
\boxed{
\Delta S_{\mathcal C_a}=0,
\qquad
\Delta A_{\mathcal C_a}\neq0.
}
\tag{115.10}
$$

### Proposition 115.2 — Local Multiplicity Closure Does Not Imply Enclosing Recurrence Symmetry

For a complete local return $i\rightarrow k\rightarrow i$, native multiplicity closes exactly.

If the two opposed legs possess nonreciprocal enclosing-compatible extension ratios or unequal productive retention, then the complete closure may retain nonzero asymmetry.

**Proof.**

Native multiplicity closure follows from multiplication of the reciprocal native ratios.

Enclosing possibility closure depends instead on the cross-ratio in equation (115.8), and retention depends on the separately defined enclosing productive constraints.

Neither quantity is determined by native multiplicity closure.

Therefore nonzero residual closure asymmetry is compatible with an exactly closed local structural path. $\square$

This is the mathematical distinction required for sustained enclosing output without persistent subordinate state displacement.

## 115.7. The Enclosing Occurrence Owns Its Compatible Local Closures

A completed local return does not, by itself, create an enclosing flow occurrence.

The causal organization must remain enclosing-first.

For a selected positive output occurrence $\chi_+$, define the complete joint compatibility fiber

$$
\boxed{
\mathfrak D_{J,\chi_+}
=
\left\{
(\mathcal C_a)_{a\in I},
\gamma_{\mathrm{ref}},
\gamma_\Phi:
\text{the complete record is jointly compatible with }\chi_+
\right\}.
}
\tag{115.11}
$$

Here:

- $(\mathcal C_a)_{a\in I}$ is the compatible collection of complete peer closures.
- $\gamma_{\mathrm{ref}}$ is the enclosing mechanical-reference record.
- $\gamma_\Phi$ is the compatible nondirectional-background record.

The enclosing relation specifies which complete combinations belong to the occurrence.

Formally,

$$
\boxed{
\chi_+^{(r)}
\Longrightarrow
(\mathcal C_a,\gamma_{\mathrm{ref}},\gamma_\Phi)
\in\mathfrak D_{J,\chi_+}.
}
\tag{115.12}
$$

A completed subordinate closure can then be read from the enclosing boundary as belonging to that occurrence:

$$
\mathcal C_a
\overset{\kappa}{\longmapsto}
\chi_+^{(r)}.
$$

The second arrow denotes recursive reclassification, not upward causation.

Therefore,

$$
\mathcal C_a\not\Longrightarrow\chi_+^{(r)}
$$

as a primitive causal claim.

The enclosing boundary defines the complete admissible flow relation. Its subordinate realizations make that relation locally readable.

The set $\mathfrak D_{J,\chi_+}$ may contain multiple distinguishable complete local realizations of the same enclosing occurrence.

Their individual identities need not remain distinguishable at $B_J$.

The cardinality of that possible joint fiber must not be confused with the number of times $\chi_+$ actually recurs.

## 115.8. The Recurrence-Weighted R²D Law

Part I relates complete local closure recurrence to enclosing occurrence recurrence.

Let

$$
N_{\mathcal C_a}
$$

count completed recurrences of a representative compatible local closure in a specified finite comparison domain.

Let

$$
N_{\chi_+}
$$

count the completed enclosing positive-output occurrences in that same comparison domain.

The canonical R²D law is

$$
\boxed{
\Delta A_{\mathcal C_a}N_{\mathcal C_a}
=
C_J\lambda_JN_{\chi_+}.
}
\tag{115.13}
$$

The constraint is the complete enclosing constraint,

$$
C_J=C_J^{out}+C_J^\Phi.
$$

Only its productive component enters local retention, whereas the complete constraint enters the recurrence-weighted enclosing relation.

For nonzero enclosing constrained distinguishability,

$$
\boxed{
\frac{N_{\chi_+}}{N_{\mathcal C_a}}
=
\frac{\Delta A_{\mathcal C_a}}
{C_J\lambda_J}.
}
\tag{115.14}
$$

The left side compares completed occurrences at two boundaries.

The right side compares complete local closure asymmetry with enclosing constrained distinguishability.

The equality does not mean that subordinate closures create flow.

It states that the same recursively organized realization possesses two boundary-specific count readings related by the R²D law.

### The count types are distinct

The following must not be equated:

$$
W_i
\neq
N_{\mathcal C_a}
\neq
N_{\chi_+}.
$$

The first counts native possibilities.

The second counts completed subordinate closure recurrence.

The third counts enclosing directional-output recurrence.

Moreover, the opposed-leg occurrence counts

$$
\nu_H,\quad\nu_L
$$

are not the counts of positive and negative enclosing flow occurrences.

The Second Law separately relates those opposed-leg counts to nondirectional background:

$$
\boxed{
\delta_{\mathcal C}\Phi_J
=
\ln\frac{\nu_H}{\nu_L}.
}
\tag{115.15}
$$

This relationship does not establish that every complete closure produces background or that the background-associated constraint is numerically identical to the background increment.

**Directional flow, complete closure recurrence, and irreversible background realization are different R²D count relationships.**

## 115.9. A Finite Consistency Construction

Consider the representative local closure

$$
\mathcal C:i\xrightarrow{H}k\xrightarrow{L}i.
$$

Specify the following mean compatible extension counts:

| Enclosing leg | State $i$ | State $k$ |
|---|---:|---:|
| $H$ | 1 | 2 |
| $L$ | 1 | 1 |

The closure possibility is

$$
\Delta P_{\mathcal C}
=
\ln\frac{2(1)}{1(1)}
=
\ln2.
$$

Let the opposed-leg productive retention contributions cancel:

$$
\Delta R_{\mathcal C}=0.
$$

Therefore,

$$
\boxed{
\Delta A_{\mathcal C}=\ln2.
}
$$

Suppose the enclosing water boundary admits a distinguishable positive-output occurrence with

$$
C_J\lambda_J=\ln2.
$$

The R²D law then gives

$$
\ln2\,N_{\mathcal C}
=
\ln2\,N_{\chi_+},
$$

so

$$
\boxed{
N_{\chi_+}=N_{\mathcal C}.
}
$$

The local state can return repeatedly while the enclosing positive-output record advances repeatedly.

Both statements remain compatible with a persistent $M_+$ water classification.

This is a consistency construction using stipulated complete compatibility and constraint relations. It does not claim that water generally possesses these particular extension counts or a one-to-one recurrence ratio.

It establishes the mathematical admissibility of sustained directional output through completed subordinate returns.

A physical water realization must supply its own enclosing compatibility and constraint.

## 115.10. What Sustains the Directional Occurrence?

We can now identify the complete requirement.

First, the enclosing possibility and retention relations must permit the positively directed water macrostate to be occupied under the selected preparation.

Second, the enclosing compatibility relation must admit completed output occurrences that preserve that water classification.

Third, those occurrences must be realized through compatible complete subordinate closures with recurrence satisfying the canonical R²D law.

Where both positive and negative output classes are admitted, sustained positive throughput further requires

$$
N_{\chi_+}-N_{\chi_-}>0
$$

over the specified comparison domain.

These requirements are not interchangeable.

A positive occupancy bias does not establish positive throughput.

A compatible output possibility does not guarantee its recurrence.

A completed subordinate closure does not independently define the enclosing output to which it belongs.

And an unchanged flowing macrostate does not imply the absence of completed occurrences.

### Principle — Enclosing Sustainment of Directional Flow

**A sustained directional fluid state is an enclosing-defined macrostate whose compatibility relation continues to admit and realize directional output occurrences while preserving the readable fluid classification.**

Compatible subordinate closures can complete and recur without changing the enclosing fluid state. Their individual histories do not supply the primitive causal definition of the flow.

The enclosing boundary sustains the directional organization; subordinate realizations express that organization under the boundary's possibility and constraint relations.

## 115.11. The Relation to Sampled Multiplicity

Addendum 112 established that changing subordinate records do not, merely by differing, establish a persistent hidden trajectory beneath an unchanged enclosing thermodynamic macrostate.

The same logic applies to flowing water.

An observer can collect successive records of differently resolved water configurations. Those records may vary while the enclosing flowing macrostate remains unchanged.

The observer may construct a trajectory linking recorded molecular or constituent positions.

Such a trajectory can be a useful physical representation.

But a sequence of sampled configurations does not, by itself, establish that the reconstructed subordinate trajectory created the enclosing directional state.

The causal inversion occurs when the representation is promoted into the primitive organizer of the state that defined its admissible alternatives.

The correct R²D distinction is

$$
\boxed{
\text{compatible subordinate variation}
\not\Rightarrow
\text{independent creation of enclosing flow}.
}
$$

This does not deny experimentally observed fluid movement.

Nor does it deny the physical existence of subordinate processes at the boundaries where those processes are readable.

It identifies their boundary-specific role.

A trajectory read at a resolving boundary is a legitimate physical description there. It does not retain its microscopic state identity unchanged when the operative count boundary is replaced by the enclosing fluid read.

## 115.12. The Physical Velocity Read Comes After Enclosing Recurrence

R²D Part IV locates velocity within a background-relative physical representation of enclosing occurrence.

The dimensionless primitive architecture does not contain meters per second.

Let a selected enclosing flow-output occurrence acquire a physical volume calibration $v_*$.

Let a common completed comparison domain acquire physical duration $\Delta t$ through a separately established clock.

Where the positive and negative output occurrences carry equal and opposite calibrated volume units, the net physical volumetric throughput is

$$
\boxed{
Q
=
v_*
\frac{N_{\chi_+}-N_{\chi_-}}{\Delta t}.
}
\tag{115.16}
$$

If an appropriate physical section has area $\mathcal A$, a bulk velocity read may then be

$$
\boxed{
\bar u=\frac{Q}{\mathcal A}.
}
\tag{115.17}
$$

These are downstream physical calibrations.

The output coordinate is not an independently tracked molecular position, and the physical clock is not a primitive update rule that forces a local pair to exchange once per tick.

The R²D law relates completed closure recurrence and enclosing occurrence recurrence before either is assigned a physical time unit.

Actual indefinite sustained flow also requires the larger enclosing preparation to remain compatible with continued output, through admissible supply and removal or through a closed circulation relation.

The occurrence does not manufacture the material inventory or the sustaining boundary condition.

## 115.13. What This Addendum Establishes

The exact count results are:

1. Native multiplicity belongs to the boundary-defined fluid classification and is not created by an individual realization.
2. Changing enclosing-compatible multiplicity can change directional possibility while leaving the native landscape fixed.
3. Completed local structural returns satisfy $\Delta S_{\mathcal C}=0$.
4. Such returns can possess nonzero enclosing-defined closure possibility and residual asymmetry.
5. A persistent directional water classification can coexist with nonzero recurring enclosing output, provided the corresponding joint occurrence class is admitted.
6. Net directed output is a signed comparison of complete enclosing occurrence counts, distinct from both macrostate occupancy and opposed-leg closure efficiency.

The canonical realization postulates additionally relate occupancy to enclosing possibility and retention, complete local closure recurrence to enclosing occurrence recurrence, and opposed-leg occurrence nonreciprocity to nondirectional background.

These results establish a coherent mathematical architecture for sustained directional flow without making constituent trajectories primitive.

They do not independently determine the physical water boundary's compatibility relation, its constraint, or the dimensional output calibration.

In particular, this addendum does not derive mass conservation, pressure, viscosity, turbulence statistics, or the Navier–Stokes equation.

Those physical relationships require additional jointly compatible count classifications and mechanical calibrations.

The distinction is deliberate.

The purpose of this addendum is to establish **what flow counts before explaining its physical resistance or writing its differential equation**.

## 115.14. Relationship to Subsequent Fluid-Mechanics Addenda

The present result provides the starting point for three further developments.

**Conservation before transport.** A subsequent addendum will define a conserved enclosing water-inventory relation jointly with directional momentum output. It will distinguish material accumulation from material throughput and recover the physical continuity equation under a specified mass calibration.

**Pressure and viscosity as enclosing constraints.** A second development will apply the Part II mechanical distinction between retained/output constraint and background-associated constraint. In ordinary fluid mechanics, these can acquire the respective physical readings of retained normal pressure and dissipative viscous resistance, without making either a primitive independent causal agent.

**The Navier–Stokes projection.** A final synthesis will investigate whether the boundary-owned conservation, momentum-throughput, and constraint relations admit a common physical continuum projection recovering the Navier–Stokes equations. It will distinguish exact count identities from R²D realization postulates and domain-specific constitutive assumptions.

Addendum 1, *Recursive Replacement Precedes the Formal Navier–Stokes Singularity*, addressed the limits of a continuum fluid representation. The present addendum addresses a logically prior question: the enclosing count structure of the flowing fluid itself.

## Conclusion — The Flowing State Does Not Flow Away

The central result is simple.

A fluid may remain in the same directional macrostate while completed subordinate closures recur and its enclosing boundary records continued directional output.

There is no contradiction because these are different boundary-defined counts.

The flowing state is not identical to the succession of its subordinate configurations.

The completed local closure is not identical to the enclosing output occurrence.

And the recurring enclosing output is not the cause of the compatibility relation that gives that output meaning.

R²D therefore reverses the usual causal interpretation of sustained flow.

**Water does not acquire its flowing state because independently moving molecular microstates generate the state that defines them. The enclosing water boundary defines the directional possibility and constraint relations under which those subordinate motions can be realized and read.**

Flow is sustained when the enclosing compatibility relation continues to support a directionally occupied fluid state and recurrent compatible directional output.

The fluid's readable macrostate can remain unchanged.

Its subordinate structure can continually recur.

Its enclosing directional output can continue.

**What sustains flow is the enclosing organization, not a reconstructed trajectory beneath it.**

---

## Related Canon and Addenda

- R²D Part I — *A Theory of Dimensionless Recursive Counting*, especially §§3.5–3.10.
- R²D Part III — *The Recursive Clock and the Horizons of Readability*.
- R²D Part IV — *Projection: The Physics Constructed from What Remains*.
- Addendum 1 — *Recursive Replacement Precedes the Formal Navier–Stokes Singularity*.
- Addendum 105 — *The Observational Inversion*.
- Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*.
- Addendum 112 — *Sampled Multiplicity Before Thermal Fluctuations*.
