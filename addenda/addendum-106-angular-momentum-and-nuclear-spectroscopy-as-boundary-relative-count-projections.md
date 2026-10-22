---
r2d_id: addendum-106
title: Addendum 106 — Angular Momentum and Nuclear Spectroscopy as Boundary-Relative Count Projections
subtitle: Finite Compatibility, Symmetric Incidence, Quadrupole Coupling, Spectral Coherence, and the Thorium-229 Nuclear Clock
source_type: addendum
authority: addendum
primitive_authority: false
addendum: 106
unit: addendum
indexable: true
integrated_in_publication_canon: true
ask_r2d_status: pending_separate_corpus_update
source_format: author_supplied_markdown
source_file: Addendum 106.md
source_sha256: 59e0ef061c5c3df60534d4c2590cea59c2e877518aec8777b90b2cb24627148f
source_canon_commit: 6c0059d32f3b1918f2d7fbdbc854e3d11477db6e
math_representation: LaTeX
review_status: authoritative
promotion_date: '2026-10-21'
---

## Abstract

The thorium-229 nuclear clock provides a quantitative test of Recursively Realized Distinguishability (R²D) at the quantum readability horizon. The observable system possesses a sharply distinguishable nuclear transition, finite angular-state manifolds, quadrupole-resolved spectral lines, and a measurable response to enclosing crystal constraints. The subordinate realization geometry of the quantum state is not jointly readable with these enclosing observations.

R²D therefore does not attempt to reconstruct persistent microscopic particle trajectories beneath the nuclear boundary. It asks whether boundary-defined distinguishability, compatible multiplicity, recurrence, and enclosing constraint admit a consistent mathematical representation of the observed relationships.

This addendum constructs such a representation. Beginning with a finite classification of equivalent binary possibilities, it derives binomial multiplicities and symmetric incidence coefficients. Their normalized linear representation generates the angular-momentum algebra. Centered pair counting generates the diagonal second-order orientation factors. When the receiving physical boundary admits a rotationally covariant rank-two constraint, the same construction produces the complete angular form of the nuclear electric-quadrupole interaction, including nonaxial mixing.

Applied to the observed thorium-229 ground and isomer manifolds, the resulting matrices reproduce the calculated quadrupole-line sensitivity ratios, including approximately −1.982 for lines d and b under the reference CaF₂ field-gradient perturbation. The construction also yields exact multiplet response identities.

The addendum then distinguishes compatible multiplicity from realized recurrence and examines spectral coherence through environmental compatibility and phase-sensitive detector reads. It establishes conditions under which compatible-record overlap bounds quantum coherence, while showing why native multiplicity alone cannot determine dephasing or linewidth.

The result is a conditional quantitative reconstruction of nuclear spectroscopy consistent with the existing R²D count architecture. Its physical calibration and symmetry assumptions are explicit. No primitive microscopic spin objects or subordinate trajectories are required, but neither are all physical projection rules claimed to follow uniquely from Part I counting.

---

## 1. The nuclear clock is an enclosing quantum-boundary observation

Part I defines physical statehood relative to a boundary of distinguishability. A microstate is a compatible realization classified at that boundary, rather than an object possessing an identical state meaning at every enclosing scale.

Part III identifies the quantum readability horizon as the regime in which subordinate geometric distinction becomes unreadable while recurrence remains readable:

$$
(\lambda,\nu)_Q=(U,R).
$$

Addenda 3 and 69 sharpen this distinction. Recursive replacement is stronger than ordinary coarse-graining: subordinate state and trajectory identities do not remain independently persistent identities at the receiving quantum boundary.

Addenda 72–83 develop the corresponding physical architecture. Native recurrence precedes complex phase; normalized detector realization precedes the Born representation; boundary-preserving recurrence precedes unitary evolution; unresolved alternatives can participate in one coherent phase relation; joint statehood precedes local outcome classification; and measurement creates a new readable detector distinction.

The thorium-229 clock belongs within this established framework.

Its relevant observations include:

- Two distinguishable nuclear-state manifolds.
- Finite sets of orientation-resolved spectral alternatives.
- Frequencies associated with differences between nuclear energy levels.
- Changes in those frequencies under different crystal environments.
- Line-dependent quadrupole splitting and environmental sensitivity.
- Spectral linewidth and coherence.
- Detector outcomes that establish the operational nuclear-clock signal.

R²D must reproduce these measured relationships within the stated physical calibration.

It need not assert that the nuclear angular labels are identities of independently readable subordinate particles or that the formal incidence construction introduced below is a literal microscopic assembly process.

This is the observational standard adopted throughout the addendum.

## 2. The unchanged R²D count architecture

At boundary $B_n$, define the compatible formal microstate domain

$$
\mathfrak M_n
\subseteq
\prod_a\mathfrak X_{n-1,a}.
$$

The enclosing boundary defines a classification map

$$
\pi_n:\mathfrak M_n\rightarrow\mathcal M_n.
$$

Its native macrostate multiplicities are

$$
W_{n,i}=|\pi_n^{-1}(i)|,
$$

with total compatible multiplicity

$$
\Theta_n=\sum_i W_{n,i}.
$$

These are possible counts, not realized occupancies.

For a compatible representative subordinate closure $\mathcal C_{n,a}$ and enclosing transition $\chi_{n+1}$, the recurrence ratio is

$$
\rho_{n+1\mid n,a}
=
\frac{N_{\mathcal D_R}(\chi_{n+1})}
{N_{\mathcal D_R}(\mathcal C_{n,a})}.
$$

The recurrence-weighted R²D law is

$$
\boxed{
\Delta A_{n,a,\mathcal C}
=
C_{n+1}\lambda_{n+1}
\rho_{n+1\mid n,a}.
}
$$

Here $\Delta A=\Delta P-\Delta R$ is closure asymmetry, $C_{n+1}$ is the enclosing constraint, and $\lambda_{n+1}$ is enclosing distinguishability.

The R²D law is a primitive quantitative postulate of the canonical framework. Its application remains boundary-indexed and count-type-specific.

None of these primitive definitions introduces angular momentum, electric charge, nuclear spin, Planck's constant, or the physical electromagnetic field.

Those quantities enter only when the physical read is specified.

The purpose of the nuclear-clock calculation is to determine which observable relationships can be constructed consistently from this prior count architecture.

## 3. Finite compatible counting and nuclear orientation classes

The observed thorium-229 nuclear ground state has angular quantum number

$$
I_g=\frac52,
$$

while the low-lying nuclear isomer has

$$
I_e=\frac32.
$$

Their respective observed orientation manifolds contain

$$
2I_g+1=6
$$

and

$$
2I_e+1=4
$$

classes.

We now construct a formal finite-count representation of each manifold.

Let an enclosing boundary distinguish the total number $k$ of positive alternatives among $L$ equivalent binary peers.

The enclosing classification is

$$
k=0,1,\ldots,L.
$$

If all binary assignments are compatible, the multiplicity belonging to class $k$ is

$$
\boxed{
W_k=\binom Lk.
}
$$

To represent an observed manifold of $2I+1$ orientation classes, choose

$$
L=2I.
$$

The resulting multiplicities are:

| Manifold | $L$ | Enclosing classes | Multiplicities |
|---|---:|---:|---|
| Ground | 5 | 6 | $1,5,10,10,5,1$ |
| Isomer | 3 | 4 | $1,3,3,1$ |

Define the centered count label

$$
\boxed{
m=k-\frac L2.
}
$$

Then

$$
m=-I,-I+1,\ldots,I.
$$

For $L=5$,

$$
m=-\frac52,-\frac32,-\frac12,
\frac12,\frac32,\frac52.
$$

For $L=3$,

$$
m=-\frac32,-\frac12,\frac12,\frac32.
$$

Thus the observed numbers of angular classes admit a finite binary-count representation with no requirement that the binary peers be identified with microscopic nucleons or other persistent particles.

**Logical status.** The binomial multiplicities are exact consequences of the specified compatible binary construction. The identification of its class count with a measured nuclear angular manifold is a physical representation choice. The number $L$ has been selected from the observed manifold dimension, not predicted independently from nuclear composition.

## 4. Symmetric incidence generates angular-momentum algebra

Consider adjacent enclosing classes $k$ and $k+1$.

A binary realization containing $k$ positive peers admits $L-k$ single-peer changes that increase the positive count.

A realization containing $k+1$ positive peers has $k+1$ possible predecessors.

Consequently,

$$
\boxed{
W_k(L-k)=W_{k+1}(k+1).
}
$$

This is an exact combinatorial incidence identity.

Introduce the normalized symmetric class representation

$$
|k\rangle=
\frac1{\sqrt{W_k}}
\sum_{|x|=k}|x\rangle.
$$

The basis vectors $|x\rangle$ are formal coordinates used to represent compatible binary assignments. They are not asserted to be primitive hidden physical states beneath the quantum horizon.

Let $J_+$ be the symmetric incidence operation that changes one negative assignment to positive.

Its matrix element is

$$
\langle k+1|J_+|k\rangle
=
\frac{W_k(L-k)}
{\sqrt{W_kW_{k+1}}}.
$$

Using the incidence identity,

$$
\boxed{
J_+|k\rangle
=
\sqrt{(L-k)(k+1)}
\,|k+1\rangle.
}
$$

The reverse operation is

$$
\boxed{
J_-|k\rangle
=
\sqrt{k(L-k+1)}
\,|k-1\rangle.
}
$$

Define

$$
J_z|k\rangle
=
\left(k-\frac L2\right)|k\rangle.
$$

Direct calculation gives

$$
[J_z,J_\pm]=\pm J_\pm
$$

and

$$
\boxed{
[J_+,J_-]=2J_z.
}
$$

The quadratic relation is

$$
\boxed{
J_x^2+J_y^2+J_z^2
=
I(I+1)\mathbf1,
\qquad I=\frac L2.
}
$$

The finite symmetric incidence construction therefore generates the standard angular-momentum algebra.

This is an exact mathematical reconstruction under the specified incidence and normalization conditions.

The result does not assert that the physical nucleus consists of $L$ distinguishable, permanently existing spin-bearing constituents. It establishes that an enclosing finite compatible-count relation can support the same angular representation used to describe its observed nuclear-state manifold.

Nor does primitive finite-set cardinality alone uniquely select this representation. The normalized linear incidence and its identification with continuous physical rotations are additional representational conditions.

## 5. Centered pair counting generates the quadrupole orientation factor

We next construct the second-order relation directly from the compatible binary assignments.

For $k$ positive and $L-k$ negative peers, the number of like-oriented pairs is

$$
N_\parallel(k)
=
\binom{k}{2}+\binom{L-k}{2}.
$$

The number of oppositely oriented pairs is

$$
N_{\mathrm{opp}}(k)=k(L-k).
$$

Their difference is

$$
D_k=N_\parallel(k)-N_{\mathrm{opp}}(k).
$$

Substitution yields

$$
\boxed{
D_k=2m^2-\frac L2.
}
$$

Construct the centered second-order orientation coordinate

$$
T_k=
\frac32D_k-\frac{L(L-1)}4.
$$

Since $I=L/2$, this becomes

$$
\boxed{
T_k=3m^2-I(I+1).
}
$$

Thus the familiar diagonal angular quadrupole factor can be constructed as a centered count of like-oriented and oppositely oriented peer pairs.

For the observed nuclear manifolds:

| Manifold | $|m|$ | $3m^2-I(I+1)$ |
|---|---:|---:|
| Ground, $I=5/2$ | $5/2$ | $10$ |
| Ground | $3/2$ | $-2$ |
| Ground | $1/2$ | $-8$ |
| Isomer, $I=3/2$ | $3/2$ | $3$ |
| Isomer | $1/2$ | $-3$ |

The finite construction is centered:

$$
\boxed{
\sum_{m=-I}^{I}
\left[3m^2-I(I+1)\right]=0.
}
$$

This trace identity will later constrain the measured spectral responses.

At this stage, the result is a dimensionless count relation. No physical electric-field-gradient coupling has been introduced.

## 6. The enclosing rank-two physical constraint

The thorium nucleus is physically interrogated within a receiving crystal environment.

For the electric-quadrupole read, the relevant environmental quantity is the electric-field-gradient tensor

$$
V_{ab}=
\frac{\partial^2V}{\partial x_a\partial x_b}.
$$

In the charge-free neighborhood used for the nuclear quadrupole interaction, this tensor is symmetric and traceless.

The physical environment therefore provides a second-rank orientation-dependent constraint.

From the count-generated angular operations, construct the symmetric traceless orientation tensor

$$
\boxed{
T_{ab}
=
\frac12(J_aJ_b+J_bJ_a)
-
\frac13\delta_{ab}I(I+1)\mathbf1.
}
$$

This tensor is obtained from the angular algebra already generated by symmetric incidence.

Now impose the physical projection condition:

*The leading nuclear interaction that is linear in the electric-field gradient and invariant under a common physical rotation must couple the environmental rank-two tensor to the corresponding nuclear rank-two orientation tensor.*

Within an irreducible spin-$I$ representation with $I\geq1$, the rank-two tensor operator occurs once in the decomposition of the operator space. Consequently, the angular form of this leading linear coupling is unique up to its physical strength.

The scalar contraction is

$$
\mathcal Q_I(V)=\sum_{a,b}V_{ab}T_{ab}.
$$

Choose principal axes for the physical field gradient and define

$$
\eta=
\frac{V_{xx}-V_{yy}}{V_{zz}}.
$$

Using

$$
V_{xx}+V_{yy}+V_{zz}=0,
$$

the contraction becomes

$$
\mathcal Q_I(V)
=
\frac{V_{zz}}2
\left[
3J_z^2-I(I+1)\mathbf1
+
\eta(J_x^2-J_y^2)
\right].
$$

Because

$$
J_x^2-J_y^2=
\frac12(J_+^2+J_-^2),
$$

we obtain

$$
\boxed{
\mathcal Q_I(V)
=
\frac{V_{zz}}2
\left[
3J_z^2-I(I+1)\mathbf1
+
\frac\eta2(J_+^2+J_-^2)
\right].
}
$$

The nuclear quadrupole moment $Q_I$ supplies the physical coupling calibration.

With the conventional spectroscopic-moment normalization,

$$
\boxed{
H_Q^{(I)}
=
\frac{Q_IV_{zz}}{4I(2I-1)}
\left[
3J_z^2-I(I+1)\mathbf1
+
\frac\eta2(J_+^2+J_-^2)
\right].
}
$$

This is the established nuclear electric-quadrupole interaction.

Its angular form is recovered from the finite symmetric-count representation combined with the physical rank-two covariance condition.

**Logical status.** The count algebra and pair-count factors were derived mathematically. The existence of the spatial electric-field-gradient tensor, its rotational transformation law, the identification of the count representation with the measured nuclear angular manifold, and the physical quadrupole moments are domain-specific physical inputs. They are not primitive consequences of Part I counting alone.

## 7. Nonaxial mixing follows from double incidence

The nonaxial term contains

$$
J_+^2+J_-^2.
$$

Applying the raising-incidence operation twice gives

$$
J_+^2|I,m\rangle
=
a_{I,m}|I,m+2\rangle,
$$

where

$$
\boxed{
a_{I,m}
=
\sqrt{
(I-m)(I+m+1)
(I-m-1)(I+m+2)
}.
}
$$

Therefore the nonaxial rank-two term connects orientation classes with

$$
\boxed{\Delta m=\pm2.}
$$

For the ground manifold, the resulting coefficients within one time-reversed sector are

$$
\boxed{
\sqrt{10}\eta,
\qquad
3\sqrt2\,\eta.
}
$$

For the isomer manifold, the corresponding coefficient is

$$
\boxed{
\sqrt3\,\eta.
}
$$

The complete dimensionless ground-state angular matrix is

$$
\boxed{
M_g=
\begin{pmatrix}
10&\sqrt{10}\eta&0\\
\sqrt{10}\eta&-8&3\sqrt2\eta\\
0&3\sqrt2\eta&-2
\end{pmatrix}.
}
$$

The isomer matrix is

$$
\boxed{
M_e=
\begin{pmatrix}
3&\sqrt3\eta\\
\sqrt3\eta&-3
\end{pmatrix}.
}
$$

Their physical quadrupole energies are represented by

$$
H_g=\frac{Q_gV_{zz}}{40}M_g,
$$

$$
H_e=\frac{Q_eV_{zz}}{12}M_e.
$$

For this time-reversal-invariant half-integer-spin interaction, each eigenvalue has the corresponding twofold Kramers degeneracy.

The complete measured manifold therefore has six ground-state orientation classes and four isomer classes, represented by three and two Kramers-degenerate eigenvalues respectively.

The numerical angular coefficients were not fitted independently. They follow from the normalized symmetric incidence structure and the selected rank-two physical coupling.

## 8. Quantitative reconstruction of the thorium-229 line responses

For the CaF₂ quadrupole-resolved environment, use the representative spectroscopic parameters

$$
Q_g=3.10\ e\,\mathrm b,
$$

$$
Q_e=1.77\ e\,\mathrm b,
$$

$$
V_{zz}=109.1\ \mathrm{V/\mathring A^2},
$$

$$
V_{yy}=-86.82\ \mathrm{V/\mathring A^2}.
$$

The quadrupole-moment values are representative physical calibrations. The field-gradient coordinates characterize the spectroscopic reference environment.

These give

$$
\eta=-1-\frac{2V_{yy}}{V_{zz}}
\approx0.591567.
$$

Diagonalize $M_g$ and $M_e$ to obtain

$$
E_{g,1}<E_{g,2}<E_{g,3}
$$

and

$$
E_{e,1}<E_{e,2},
$$

where the $E$ values now include the respective physical quadrupole prefactors.

For the five quadrupole transition classes, define the line-frequency corrections

$$
\begin{aligned}
hf_a&=E_{e,1}-E_{g,2},\\
hf_b&=E_{e,2}-E_{g,3},\\
hf_c&=E_{e,1}-E_{g,1},\\
hf_d&=E_{e,2}-E_{g,2},\\
hf_e&=E_{e,2}-E_{g,1}.
\end{aligned}
$$

The common unsplit nuclear transition frequency has been omitted from these expressions because it cancels from the quadrupole-gradient derivatives.

Calculate the partial derivatives

$$
s_{\ell,zz}=
\left.\frac{\partial f_\ell}{\partial V_{zz}}\right|_{V_{yy}},
$$

and

$$
s_{\ell,yy}=
\left.\frac{\partial f_\ell}{\partial V_{yy}}\right|_{V_{zz}}.
$$

The reference physical conversion is

$$
1\ (e\,\mathrm b)(\mathrm{V/\mathring A^2})
\longleftrightarrow
2.417989242\ \mathrm{MHz}.
$$

Numerical diagonalization and differentiation give:

| Line | $s_{\ell,zz}$ | $s_{\ell,yy}$ |
|---|---:|---:|
| a | +0.148400 | +1.342599 |
| b | −0.895128 | −0.144188 |
| c | −0.066144 | −0.799090 |
| d | +1.774144 | +0.543957 |
| e | +1.559600 | −1.597731 |

All sensitivities are in MHz per V/Å².

The reconstructed values agree, to the precision of the input parameters, with the physical quadrupole sensitivity calculation reported by Li and collaborators in October 2026.

In particular,

$$
\boxed{
\frac{s_{d,zz}}{s_{b,zz}}
=
\frac{1.774144}{-0.895128}
\approx-1.98200.
}
$$

This ratio is calculated from the finite symmetric-incidence matrices after specifying the measured physical nuclear moments and environmental field gradient.

The comparison is not an independent experimental validation of a new physical prediction. The numerical parameters are spectroscopically calibrated, and the resulting matrices are mathematically equivalent to the established nuclear quadrupole representation.

The result establishes that the finite-count construction can reproduce this quantitative physical angular response without independently postulating the angular matrix coefficients.

### 8.1 Parameter-independent response identities

The centered rank-two angular matrices are traceless.

Consequently,

$$
E_{g,1}+E_{g,2}+E_{g,3}=0,
$$

$$
E_{e,1}+E_{e,2}=0
$$

for their quadrupole corrections.

Taking derivatives with respect to a quadrupole-only environmental perturbation gives the exact response identity

$$
\boxed{
s_a+2s_b+2s_c+s_d=0.
}
$$

The line definitions also give

$$
\boxed{
s_e=s_c+s_d-s_a.
}
$$

These relations require neither a fitted nuclear quadrupole moment nor a specified electric-field-gradient magnitude.

They are exact algebraic consequences of the finite, traceless multiplet response and the transition classifications.

A common isomer-shift derivative would contribute to every transition and must be removed before applying the zero-trace quadrupole identity.

Thus the thorium-229 calculation contains two different kinds of quantitative result: parameter-independent multiplet identities and physically calibrated line sensitivities.

## 9. Enclosing crystal constraint and the nuclear spectral frequency

The measured nuclear spectral frequency belongs to a difference between the nuclear ground and isomer states.

For a selected transition $\ell$ and environmental condition $r$,

$$
\boxed{
hf_\ell(r)=E_{e,\ell}(r)-E_{g,\ell}(r).
}
$$

This frequency is not the number of nuclear transitions occurring per unit time.

Nor is it the rate of an assumed microscopic orbital or nuclear constituent trajectory.

Part III explicitly separates spectral frequency from realized transition rate.

The enclosing crystal environment changes the nuclear state difference through observable couplings, including isomer-shift and electric-quadrupole contributions.

Two experimentally distinguished thorium environments, conventionally called O-centres and D-centres, exhibit a quadrupole-corrected resonance-frequency difference of approximately

$$
f_O-f_D=3.99(2)\ \mathrm{MHz}.
$$

This is an additional observable of the same nuclear-state distinction under different enclosing environmental conditions. Its physical interpretation involves electronic density at the nucleus and the associated isomer shift.

The rank-two quadrupole construction does not, by itself, derive the monopole isomer shift.

### 9.1 Candidate R²D frequency bridge

The recurrence-weighted R²D law is

$$
\Delta A_{\mathcal C}
=
C_N\lambda_N\rho.
$$

For nonzero $\rho$,

$$
C_N\lambda_N=
\frac{\Delta A_{\mathcal C}}{\rho}.
$$

If the constrained distinguishability of one enclosing nuclear transition acquires a locally linear energetic read, a candidate physical mapping is

$$
\boxed{
h\,\delta f_\ell
=
\mathcal E_\ell
\delta(C_{N,\ell}\lambda_{N,\ell}).
}
$$

Equivalently,

$$
\boxed{
\delta f_\ell
=
\frac{\mathcal E_\ell}{h}
\delta\left(
\frac{\Delta A_{\mathcal C,\ell}}{\rho_\ell}
\right).
}
$$

Here $\mathcal E_\ell$ is a physical energetic calibration. It is not a newly established primitive R²D quantity.

This mapping preserves a necessary distinction.

Changes in subordinate closure recurrence need not produce corresponding changes in nuclear spectral frequency if the enclosing constrained distinguishability remains invariant.

The proposed bridge is therefore more appropriate than identifying the nuclear carrier frequency with the recurrence rate of a subordinate representative closure.

**Status:** This is a candidate physical mapping, not a theorem derived from Part I. Neither the unique function relating nuclear spectral energy to primitive count variables nor its calibration has yet been established without additional physical input.

## 10. Spectral coherence as compatibility of environmental realization

The nuclear clock supplies a second test: an enclosing transition can be spectrally coherent while subordinate environmental processes remain active.

We must distinguish four quantities:

1. Native compatible multiplicity $W$, counting possible realizations.
2. Realized occurrence or occupancy counts, describing what is actually represented in a specified comparison domain.
3. Completed closure recurrence counts, used in the R²D recurrence relation.
4. Physical spectral phase and frequency, obtained after electromagnetic clock calibration.

These quantities cannot be substituted for one another.

### 10.1 A finite environmental compatibility model

Let the receiving environmental read distinguish two spectroscopic crystal-site classes:

$$
\mathcal R_{\mathrm{site}}=\{Q,U\},
$$

where $Q$ denotes quadrupole-resolved and $U$ quadrupole-unresolved environments.

For a minimal finite model, suppose both nuclear alternatives admit both environments:

| Record | Ground compatible count | Isomer compatible count |
|---|---:|---:|
| $Q$ | 1 | 1 |
| $U$ | 1 | 1 |

Define the normalized compatibility affinity

$$
\boxed{
\mathcal B_{\mathrm{comp}}
=
\frac{
\sum_r\sqrt{m_g(r)m_e(r)}
}{
\sqrt{\Theta_g\Theta_e}
}.
}
$$

For this minimal site-only construction,

$$
\boxed{\mathcal B_{\mathrm{comp}}=1.}
$$

The two nuclear alternatives share the same environmental record support under this classification.

However, this does not imply zero linewidth or perfect observed coherence. Distinct compatible environments may assign different physical frequencies or phases to the enclosing nuclear transition.

The affinity describes possible-count compatibility, not automatic physical phase equivalence.

### 10.2 Realized-record overlap and the quantum coherence bound

Let $q_g(r,t)$ and $q_e(r,t)$ be the normalized realized environmental record distributions conditioned on the two nuclear alternatives.

Their realized-record affinity is

$$
\boxed{
\mathcal B_{\mathrm{real}}(t)
=
\sum_r
\sqrt{q_g(r,t)q_e(r,t)}.
}
$$

In a pure-dephasing physical projection with normalized conditional environmental states $|E_g(t)\rangle$ and $|E_e(t)\rangle$, the nuclear coherence is

$$
\mathcal V_N(t)
=
|\langle E_g(t)|E_e(t)\rangle|.
$$

For any common complete orthogonal environmental record classification,

$$
\boxed{
\mathcal V_N(t)\le\mathcal B_{\mathrm{real}}(t).
}
$$

The bound follows from the triangle inequality and Cauchy–Schwarz.

For two pure conditional environmental states, a suitable projective classification can attain equality:

$$
\boxed{
\inf_{\mathcal R}
\mathcal B_{\mathcal R}(t)
=
\mathcal V_N(t).
}
$$

Thus the most distinguishing environmental read has a normalized record affinity equal to the pure-state quantum overlap.

This is a theorem of the physical quantum projection.

It does not establish that primitive R²D compatible multiplicity uniquely determines the physical measurement basis, amplitudes, or phase.

The count-derived possible-affinity $\mathcal B_{\mathrm{comp}}$ equals the realized-affinity only under an additional relation between compatible multiplicity and realized record weights. Such a relation must be specified and tested, not assumed universally.

### 10.3 Pure dephasing without population change

Consider a two-record environment prepared so that its two nuclear-state-conditioned representations are

$$
|E_g\rangle
=
\frac{|0\rangle+|1\rangle}{\sqrt2},
$$

$$
|E_e\rangle
=
\frac{|0\rangle+e^{i\delta}|1\rangle}{\sqrt2}.
$$

The nuclear populations need not change.

Nevertheless,

$$
\boxed{
\mathcal V_N=
\left|\cos\frac\delta2\right|.
}
$$

A receiving read distinguishing only the records $0$ and $1$ assigns both nuclear states the same normalized outcome distribution:

$$
q_g=q_e=(1/2,1/2).
$$

Its record affinity is one.

A phase-sensitive receiving read using the alternatives

$$
|+\rangle,\quad|-\rangle
$$

instead gives

$$
q_g=(1,0)
$$

and

$$
q_e=
\left(
\cos^2\frac\delta2,
\sin^2\frac\delta2
\right).
$$

Its affinity is

$$
\boxed{
\mathcal B_{\mathrm{real}}
=
\left|\cos\frac\delta2\right|
=
\mathcal V_N.
}
$$

The result demonstrates that environmental distinctions carry nuclear phase information only relative to a receiving classification capable of resolving their physical phase response.

No change in nuclear occupancy is required.

The physical phase basis is an added quantum read. It has not been deduced uniquely from the number of compatible records.

## 11. Subordinate recurrence does not necessarily broaden the nuclear spectrum

An active environmental degree of freedom may alternate between two configurations, $r_+$ and $r_-$.

Suppose the observed nuclear transition has conditional angular frequencies

$$
\omega_\pm=\omega_0\pm\Delta.
$$

Let the environment switch symmetrically between these configurations with calibrated rate $\kappa$.

For a stationary initial distribution and Markovian switching, the phase-weighted record components satisfy

$$
\dot z_+
=
(i\Delta-\kappa)z_++\kappa z_-,
$$

$$
\dot z_-
=
(-i\Delta-\kappa)z_-+\kappa z_+.
$$

The normalized phase response $Z=z_++z_-$ obeys

$$
\boxed{
\ddot Z+2\kappa\dot Z+\Delta^2Z=0
}
$$

with

$$
Z(0)=1,\qquad\dot Z(0)=0.
$$

Writing

$$
u=\sqrt{\kappa^2-\Delta^2},
$$

the solution is

$$
\boxed{
Z(t)
=
e^{-\kappa t}
\left[
\cosh(ut)
+
\frac{\kappa}{u}\sinh(ut)
\right].
}
$$

The appropriate continuous limit is taken when $u=0$, and imaginary $u$ gives the corresponding oscillatory solution.

For rapid switching,

$$
\kappa\gg|\Delta|,
$$

the long-time phase-decay rate is approximately

$$
\boxed{
\Gamma_\phi
\simeq\frac{\Delta^2}{2\kappa}.
}
$$

Thus increased environmental recurrence can reduce enclosing phase dispersion.

This is the familiar motional-narrowing result expressed through a finite environmental record-transition model.

The derivation does not assume a hidden nuclear constituent trajectory. It requires an experimentally calibrated conditional nuclear frequency difference and an environmental switching law.

It is a conditional physical model, not yet a prediction of thorium-229 linewidth from primitive R²D quantities.

The broader implication is exact:

**Many subordinate recurrences can sustain a coherent enclosing nuclear phase relation. Subordinate activity alone is not equivalent to nuclear decoherence.**

## 12. Observed linewidth is not automatically intrinsic dephasing

Recent solid-state thorium-229 experiments resolve narrow QR transitions alongside broader QU spectral features.

One operating-clock study reports a QR line-b linewidth of $27(1)$ kHz and a QU linewidth of $0.898(5)$ MHz for a specified crystal and interrogation configuration.

Separate measurements and modeling identify variations in local crystal electric-field gradients as an important, and in studied samples dominant, contribution to the inhomogeneous nuclear linewidth.

The word *Lorentzian* does not by itself prove homogeneous dephasing. A distribution of static environmental frequency shifts can also yield a Lorentzian ensemble spectrum.

This distinction matters for the R²D interpretation.

If different nuclei experience distinct but temporally stable enclosing constraints, their individual transitions can remain coherent even when their ensemble spectrum is broad.

If the environment changes during interrogation and produces state-dependent phase records, genuine dynamical dephasing may occur.

If a physical process changes the nuclear population, the resulting lifetime contribution is not pure dephasing.

These mechanisms must be distinguished before any spectral linewidth is assigned an R²D recurrence-depth interpretation.

A finite measured line width does not, by itself, establish a finite count of subordinate recursive boundaries. Such an inference requires additional lower bounds on phase-distinguishing recurrence or a separately established count-to-coherence mapping.

## 13. What has been reconstructed and what remains unresolved?

The logical status of the results is summarized below.

| Result | Status |
|---|---|
| Boundary-defined microstates, multiplicity, compatibility, and recurrence | Canonical R²D definitions |
| Recurrence-weighted closure-asymmetry equality | Canonical R²D postulate |
| Binomial compatible binary-peer multiplicities | Exact under unrestricted equivalent binary composition |
| Symmetric incidence coefficients | Exact in the specified normalized count representation |
| $\mathfrak{su}(2)$ angular-momentum algebra | Exact conditional mathematical reconstruction |
| Centered pair-count quadrupole factor | Exact combinatorial result |
| Rank-two angular coupling | Unique under the selected physical spin representation, rotational covariance, and leading linear response |
| Thorium-229 quadrupole matrices | Exact angular representation once those physical conditions are specified |
| Ratio $s_d/s_b\approx-1.982$ | Quantitative reproduction using physical nuclear and crystal parameters |
| Multiplet response sum rules | Exact within the centered quadrupole-response classification |
| Compatibility-affinity inequalities | Exact for defined count distributions; quantum coherence bound requires the corresponding physical record weights |
| Pure-dephasing and switching models | Exact under their specified physical phase and realization models |
| Unique primitive derivation of the physical spin representation | Not established |
| Unique primitive mapping from $C_N\lambda_N$ to nuclear spectral energy | Not established |
| Derivation of nuclear quadrupole moments from R²D count alone | Not established |
| Determination of intrinsic nuclear coherence or recursive depth from native multiplicity alone | Not established |

These qualifications do not invalidate the conditional reconstructions.

They identify the differences among primitive counting, mathematical representation, physical calibration, and experimental validation.

The same evidentiary distinctions must be applied to conventional physical theories when evaluating their predictions and ontological interpretations.

## 14. Relationship to the integrated R²D quantum program

This addendum does not replace Addenda 72–83.

It extends their existing mathematical architecture into a quantitative nuclear spectroscopy application.

Addendum 72 supplies the cyclic recurrence and phase ordering. Addendum 73 develops normalized detector realization and its conditional quantum probability representation. Addendum 74 concerns boundary-preserving unitary evolution. Addenda 75–80 develop continuous physical translation, constraint phase bias, and electromagnetic phase comparison. Addendum 81 treats interference. Addendum 82 addresses joint quantum statehood and Bell correlations. Addendum 83 defines detector-boundary realization.

The present nuclear-clock calculation tests whether the same boundary-specific meanings can be retained when the physical read is nuclear angular momentum and quadrupole-resolved spectroscopy.

It must not silently reinterpret:

- possible multiplicity as realized occupation;
- local completed closure recurrence as enclosing optical frequency;
- formal binary incidence as an actual hidden constituent trajectory;
- quadrupole matrix coefficients as independently fitted constants;
- spectral linewidth as a direct measure of primitive recursive depth;
- or an imported physical coupling as a theorem of dimensionless counting.

These distinctions provide explicit compatibility requirements for the integrated quantum-consistency audit.

## 15. Conclusion

The thorium-229 nuclear clock provides a quantitative realization of R²D's boundary-relative observational program.

Its measured nuclear manifold admits a finite compatible-count representation. Symmetric binary incidence generates the angular algebra, and centered pair counting supplies the diagonal rank-two orientation relation. Under the physical rank-two constraint read, the complete nonaxial quadrupole angular structure follows, including the finite matrix coefficients required to reproduce the observed nuclear spectroscopy.

With independently specified physical coupling parameters, this representation reproduces the reference quadrupole-line sensitivity ratio

$$
\boxed{
s_d/s_b\approx-1.982
}
$$

and satisfies exact response identities across the nuclear transition manifold.

The coherence analysis separately establishes that compatible subordinate multiplicity does not necessarily diminish enclosing spectral coherence. Its observable consequences depend on which environmental distinctions become readable, how they are realized, and whether their phase relationships remain compatible with the nuclear transition.

These results do not establish that the formal subordinate binary realization is the unique microscopic structure of the nucleus. That is not the observational target at the quantum horizon.

The result instead concerns the mathematical organization of what is readable at that boundary.

The central R²D claim supported here is:

**Finite boundary-defined compatibility can provide a coherent mathematical representation of nuclear angular momentum, quadrupole spectroscopy, and phase coherence without changing the primitive counting architecture or assigning primitive identity to unreadable subordinate particles and trajectories.**

The remaining task is not to reconstruct an inaccessible microscopic story. It is to determine whether the physical projections required for the entire quantum program—including angular momentum, spectroscopy, interference, entanglement, and detector realization—can be jointly specified while preserving the same count definitions and making every additional physical premise explicit.

That question belongs to the integrated quantum-consistency audit.

---

## References and controlling sources

**R²D sources**

- R²D, *Part I — A Theory of Dimensionless Recursive Counting*. Boundary-indexed statehood, compatible multiplicity, recursive replacement, and the recurrence-weighted law.
- R²D, *Part II*. Physical mapping and joint readability of subordinate and enclosing relations.
- R²D, *Parts III and IV*. Quantum readability horizon, spectroscopy, recurrence, phase, and the physical quantum projection.
- R²D, *Addenda 3, 69–83*. Complementary readability, quantum recurrence, phase, normalized detector realization, unitary evolution, interference, entanglement, and measurement.
- R²D, *Addendum 86 — The Status of a Physical Mapping*. Classification of derivations, calibration, and empirical tests.

**Experimental and physical sources**

- Huang et al. (2026), *A nuclear clock synchronized to ²²⁹Th*, Nature. [DOI: 10.1038/s41586-026-11122-1](https://doi.org/10.1038/s41586-026-11122-1).
- Toscani De Col et al. (2026), *A thorium-229 optical nuclear clock with feedback loop*, Nature. [DOI: 10.1038/s41586-026-11084-4](https://doi.org/10.1038/s41586-026-11084-4).
- *Continuous-wave laser absorption spectroscopy of the thorium-229 nucleus* (2026), Nature. [DOI: 10.1038/s41586-026-11011-7](https://doi.org/10.1038/s41586-026-11011-7).
- Li, Ooi, Doyle, Herb, Pellett, Pimon, Schumm, Girvin, Radzihovsky, and Ye (2026), *Origin of the inhomogeneous linewidth in a solid state ²²⁹Th:CaF₂ nuclear clock*. [arXiv:2610.04205](https://arxiv.org/abs/2610.04205).
- *Fine-structure constant sensitivity of the Th-229 nuclear clock transition* (2025), Nature Communications. [DOI: 10.1038/s41467-025-64191-7](https://doi.org/10.1038/s41467-025-64191-7).
