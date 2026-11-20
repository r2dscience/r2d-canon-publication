---
r2d_id: "addendum-133"
title: "Addendum 133 — Thermodynamic Doppler Reciprocity"
subtitle: "Symmetric Enclosing Background, Directional Readability, and the Conditional Area–Recurrence Invariant"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 133
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-13"
scope: "Orientation-even complete recurrence, Doppler reciprocal reads, thermodynamic area–energy scaling, finite countermodels, and physical calibration limits"
---

# R²D Addendum 133 — Thermodynamic Doppler Reciprocity

*Symmetric Enclosing Background, Directional Readability, and the Conditional Area–Recurrence Invariant*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I–IV (September 25, 2026); Addenda 35, 36, 63, 69–70, 105, 112, 120, 122, and companion Addenda 131–132.  
**Scope:** The symmetric thermal background before directional Doppler rereading; a conditional joint area–frequency invariant; an exact scaling theorem and a finite obstruction to deriving its exponent from recurrence symmetry alone.

## Abstract

An enclosing thermodynamic background defines the reference relative to which subordinate directional realizations are read. Reciprocal turbine recurrence can be positive without net directional throughput, and relative motion can change opposed observations without reconstructing the enclosing reference. These are distinct statements. Addendum 131 formalizes the first by orientation-even completed-return counts; Addendum 35 supplies positive opposed reference coordinates for the second. Neither alone provides a universal physical speed.

For an ideal isotropic blackbody viewed in relative collinear motion, the opposed axial Doppler temperatures obey $T_+T_-=T_0^2$. Their thermal frequency-equivalent readings therefore satisfy $f_+f_-=f_0^2$, where $f_i=k_BT_i/h$. This product is an exact consequence of the accepted physical Doppler law, not yet a derivation of that law from R²D counts. It is not the same count object as the orientation-even sum of completed turbine cycles.

We next establish a general conditional thermodynamic theorem. For an area-first, self-similar three-dimensional enclosure, preservation of the complete multiplicity landscape under $A\mapsto s^2A$ and $E\mapsto E/s^z$ gives $3pV=zE$. Its $z=1$ class has the radiation-like equation of state and, at fixed entropy, $A f_T^2=\mathrm{constant}$. Ideal equilibrium blackbody radiation realizes the required scaling. The $z=2$ monatomic ideal-gas class and an explicit finite symmetric countermodel show that reciprocal recurrence and orientation symmetry do not select $z=1$.

Combining a *specified* $z=1$ background scaling with an axial reciprocal Doppler reread gives the invariant $\mathcal I=A f_+f_-=A f_0^2$. This is a theorem of the stated joint physical map, not a proof that a unique R²D background supplies that map or that $\mathcal I=c^2$. The background's ruler and clock remain fixed within a chosen reference boundary; the scaling theorem compares separately admitted compatible physical calibrations, not growth of the primitive background during cosmological expansion. The open problem is to derive the $z=1$ joint area–recurrence compatibility from enclosing count structure and test its preservation across the two readability horizons of Addendum 132.

## 133.1. The question left by Addenda 131 and 132

Fix a local turbine boundary $B$ and an enclosing owner $J$. For a realized complete record $h$, Addendum 131 distinguishes the completed orientation counts

$$
N_{\mathrm{even}}(h)=N_+(h)+N_-(h),\qquad
N_{\mathrm{odd}}(h)=N_+(h)-N_-(h).
\tag{133.1}
$$

A reciprocal turbine can have $N_+=N_->0$: realized completion continues while net oriented output vanishes. For an independently specified enclosing background-reference recurrence count $M(h)=N_J^\Phi(h)>0$, define

$$
\chi_J(h)=\frac{N_{\mathrm{even}}(h)}{M(h)}.
\tag{133.2}
$$

Constancy of $\chi_J$ follows from a sufficiently specified complete enclosing recurrence relation, not from orientation symmetry alone. Nor does the ratio independently assign seconds or physical distance.

Addendum 132 asks whether a specified common count invariant survives both quantum-side and gravitational-side read maps. Before applying those maps, we investigate an accessible thermal physical comparison: **a symmetric enclosing background, two opposed directional observations, and an independently specified area calibration**.

## 133.2. Three even quantities that must not be conflated

The word *symmetric* appears at three distinct levels.

1. **Completed-cycle even count:** $N_++N_-$ counts realized whole turbine closures, irrespective of direction. It is a sum of nonnegative integers.
2. **Reference-coordinate even invariant:** Addendum 35 introduces positive opposed coordinates $Z_+,Z_-$, with $Z_+Z_-$ unchanged under a reciprocal reread. The product is an area-like count relation, not a literal physical surface.
3. **Physical Doppler even product:** for opposed measured axial temperatures or frequency-equivalent scales, $T_+T_-$ or $f_+f_-$ may be invariant under a specified relative-motion law.

None of these identities authorizes setting $N_{\mathrm{even}}=Z_+Z_-=f_+f_-$. Any mapping between them must specify its enclosing owner, native identification, and physical calibration. In particular, positive calibrated $Z$ coordinates need not be whole-closure counts; exact continuous exponential rescaling cannot generally map arbitrary integer counts to integer counts.

The canonical scalar realized-background count $b_J>0$, its logarithm $\Phi_J=\ln b_J$, the separate background recurrence count $N_J^\Phi$, a physical thermal frequency equivalent $k_BT/h$, and the observed cosmic microwave background are also distinct.

## 133.3. The reciprocal reread lemma

Let $F_+,F_->0$ be two positive directional read coordinates of one **specified** complete enclosing relation. Define

$$
F_0=\sqrt{F_+F_-},\qquad
\xi=\frac12\ln\frac{F_+}{F_-}.
\tag{133.3}
$$

Then identically

$$
F_+=F_0e^\xi,\qquad F_-=F_0e^{-\xi}.
\tag{133.4}
$$

**Lemma 1 (unique even–odd decomposition).** For positive $F_\pm$, the geometric mean $F_0$ and logarithmic ratio $\xi$ uniquely specify the pair. Under orientation exchange $F_+\leftrightarrow F_-$, $F_0$ is even and $\xi$ is odd. If a reference reread acts by $F_+\mapsto e^\eta F_+$ and $F_-\mapsto e^{-\eta}F_-$, it preserves $F_+F_-=F_0^2$ and shifts $\xi\mapsto\xi+\eta$.

**Proof.** Substitute (133.3) into (133.4), then multiply and divide the transformed coordinates. $\square$

The lemma is algebraic. It does not prove that every admissible physical motion implements this reciprocal action. In the language of Addendum 35, the reciprocal form is a *candidate enclosing reference reread*; the physical Doppler correspondence needs its own grounding.

## 133.4. The ideal blackbody Doppler realization

Consider an ideal isotropic blackbody radiation field with rest-frame temperature $T_0$. A collinearly moving observer, with $\beta=v/c$ and $|\beta|<1$, measures the exact direction-dependent temperature

$$
T(\theta)=T_0\frac{\sqrt{1-\beta^2}}{1-\beta\cos\theta}.
\tag{133.5}
$$

At the two axial directions,

$$
T_+=T_0\sqrt{\frac{1+\beta}{1-\beta}},\qquad
T_-=T_0\sqrt{\frac{1-\beta}{1+\beta}}.
\tag{133.6}
$$

Therefore,

$$
\boxed{T_+T_-=T_0^2.}
\tag{133.7}
$$

Writing $\xi=\operatorname{artanh}\beta$ gives $T_\pm=T_0e^{\pm\xi}$. For the *thermal energetic frequency equivalents*

$$
f_\pm=\frac{k_BT_\pm}{h},\qquad f_0=\frac{k_BT_0}{h},
$$

we likewise have

$$
\boxed{f_+f_-=f_0^2.}
\tag{133.8}
$$

Let $F=(f_++f_-)/2$ and $D=(f_+-f_-)/2$. The same relation becomes

$$
\boxed{F^2-D^2=f_0^2.}
\tag{133.9}
$$

**Theorem 1 (axial thermodynamic Doppler reciprocity).** For a Lorentz-boosted, initially isotropic ideal blackbody, the product of the opposite axial thermal frequency-equivalent readings is equal to the square of the rest-frame thermal frequency equivalent.

**Proof.** Multiply the two exact expressions in (133.6), then apply the common factor $k_B/h$. $\square$

**Physical scope.** This is an exact consequence of the standard relativistic Doppler law, whose $c$ is already present in $\beta$. It does not derive $c$ or the Lorentz law from primitive R²D counts. The product is specifically axial: for an arbitrary opposed pair of angles, $T(\theta)T(\pi-\theta)=T_0^2(1-\beta^2)/(1-\beta^2\cos^2\theta)$, generally not $T_0^2$. It also idealizes away intrinsic CMB anisotropy and spectral distortions.

**R²D interpretation.** A change in the observer's directional read need not change the symmetry of the enclosing radiation reference. The observed dipole is a read of relative motion, not an independent construction of the background temperature by two opposing sources.

## 133.5. The background is fixed at its own boundary

The proposed CMB interpretation must distinguish a background reference from a subordinate cosmological read. Within a specified enclosing reference $\Phi$, its proposed physical ruler $\ell_\Phi$ and fundamental frequency calibration $f_\Phi$ are fixed properties of that *chosen comparison*. A scale transformation below relates separately specified compatible thermodynamic calibrations or physical enclosures. It is **not** an assertion that the chosen background's fundamental ruler grows while its clock slows as the universe expands.

The CMB is a candidate physical realization of a millimetre-scale radiation reference, not an identification of the R²D background with the radius of the universe. A thermal CMB spectrum can supply a reference frame and energetic frequency equivalent; the numerical identification of that read with $N_J^\Phi$ or $b_J$ remains unproved. A cosmological expansion variable, a CMB spectral wavelength, a cavity's physical area, and an R²D boundary count area are four different quantities.

## 133.6. The joint area–energy compatibility theorem

Let $\mathcal H_J(E,A)$ be a specified enclosing-owned domain of compatible complete thermodynamic records with physical energy $E>0$ and a physical area read $A>0$. Let its thermodynamic multiplicity be $W_J(E,A)$ and its dimensionless entropy be

$$
S(E,A)=\ln W_J(E,A).
\tag{133.10}
$$

This is a thermodynamic *possible-count* entropy at its chosen boundary, not the scalar realized background $\Phi_J$. Assume its smooth macroscopic thermodynamic representation has the standard conjugate reads, at fixed other independent variables,

$$
S_E=\frac{1}{k_BT},\qquad S_V=\frac{p}{k_BT}.
\tag{133.11}
$$

Let the associated three-dimensional physical geometry be self-similar, with fixed shape factor $\kappa>0$:

$$
V=\kappa A^{3/2}.
\tag{133.12}
$$

This is a physical projection *after* specifying the area, not a primitive R²D radius or area-count axiom. Assume no independent shape, particle-number, composition, or external-field variable changes along the comparison.

**Theorem 2 (weighted compatibility homogeneity).** Suppose the complete enclosing-compatible multiplicity is preserved between the compared descriptions under

$$
A\mapsto s^2 A,\qquad E\mapsto s^{-z}E,
\qquad s>0,
\tag{133.13}
$$

for a fixed exponent $z>0$ and the same thermodynamic comparison class. Under the differentiability assumptions above,

$$
\boxed{3pV=zE.}
\tag{133.14}
$$

Locally the entropy has the form

$$
\boxed{S(E,A)=F\!\left(\frac{EA^{z/2}}{\Gamma_z}\right),}
\tag{133.15}
$$

where $\Gamma_z$ is a fixed calibration with dimensions energy times length to power $z$, and $F$ is a differentiable function.

**Proof.** The exact count correspondence gives $S(E,A)=S(s^{-z}E,s^2A)$. Differentiate with respect to $s$ at $s=1$:

$$
2AS_A-zES_E=0.
$$

Equation (133.12) implies $2AS_A=3VS_V$. Apply (133.11) to obtain $3pV=zE$. Solving the first-order homogeneity equation by characteristics gives (133.15) locally. $\square$

The theorem's premise is not merely equal numbers of clockwise and counterclockwise returns. It is a **joint compatibility correspondence preserving thermodynamic multiplicity across area and energy reads**. This is the exact extra structure required for a pressure–energy prediction.

## 133.7. The radiation-like member and its frequency consequence

For $z=1$,

$$
\boxed{2AS_A-ES_E=0\quad\Longleftrightarrow\quad 3pV=E.}
\tag{133.16}
$$

Let $x=E\sqrt A/\Gamma_1$ and $S=F(x)$. From the energy derivative,

$$
\frac{1}{k_BT}=\frac{\sqrt A}{\Gamma_1}F'(x),
$$

so

$$
\boxed{k_BT\sqrt A=\frac{\Gamma_1}{F'(x)}.}
\tag{133.17}
$$

At fixed $x$ (equivalently at fixed entropy where $F$ is locally one-to-one), and for $f_T=k_BT/h$,

$$
\boxed{Af_T^2=\left(\frac{\Gamma_1}{hF'(x)}\right)^2=\mathrm{constant}.}
\tag{133.18}
$$

The square root of physical area enters only after area is supplied. No microscopic speed, photon, or trajectory has been used to prove this *conditional scaling identity*. For general $z$, the analogous fixed-class relation is $A^z f_T^2=\mathrm{constant}$; the particular quadratic area–frequency expression $Af_T^2$ selects $z=1$.

This does **not** show that the actual recurring background clock has frequency $f_T$. If $f_\Phi=\alpha_\Phi f_T$, then $A f_\Phi^2=\alpha_\Phi^2 A f_T^2$. Preservation across backgrounds additionally requires a common or independently constrained $\alpha_\Phi$.

## 133.8. Equilibrium radiation realizes the $z=1$ landscape

As an independently established physical result, equilibrium blackbody radiation has

$$
E=aVT^4,\qquad p=\frac{E}{3V},\qquad
S=\frac{4aVT^3}{3k_B},
\tag{133.19}
$$

where $a$ is the physical radiation constant and $S$ here is dimensionless. Eliminating $T$ yields

$$
S(E,V)=\frac{4a^{1/4}}{3k_B}E^{3/4}V^{1/4}.
\tag{133.20}
$$

Substituting (133.12),

$$
\boxed{S(E,A)=\frac{4(a\kappa)^{1/4}}{3k_B}(E\sqrt A)^{3/4}.}
\tag{133.21}
$$

Thus the familiar radiation equation of state is a physical example of the precise weighted homogeneity demanded by (133.16). An isentropic family of self-similar radiation enclosures obeys $T\sqrt A=\mathrm{constant}$ and $Af_T^2=\mathrm{constant}$.

**Noncircularity limit.** The observed radiation equation of state verifies the *form* of the proposed thermodynamic bridge. Conventional determination of the radiation constant $a$ already depends on the electromagnetic propagation speed $c$. Substituting its numerical value into (133.18) cannot be advertised as deriving $c$ independently. This addendum derives no universal dimensional value of $Af_T^2$.

## 133.9. Counterexample: symmetry does not select $z=1$

A classical monatomic ideal gas with thermal internal energy $E$ has $pV=2E/3$. Its entropy, at fixed particle number and composition, contains the scale-covariant combination $EV^{2/3}\propto EA$. Therefore it realizes $z=2$, despite admitting isotropic equilibrium and no preferred directional throughput.

An exact finite count construction shows the logical independence without relying on molecules. Fix any $z>0$, $p_*>0$, $K\in\mathbb N$, and a positive calibration $\Gamma_z$. For each declared pair $(E,A)$ define

$$
x_z(E,A)=\frac{EA^{z/2}}{\Gamma_z},\qquad
W_z(E,A)=2^{1+\lfloor K x_z(E,A)^{p_*}\rfloor}.
\tag{133.22}
$$

Take $W_z(E,A)$ complete compatible records in reversal-paired classes. Give each complete record the same balanced completed turbine counts, for example $N_+=N_-=2$, and the independently specified reference recurrence $M=12$. Every complete record then has $N_{\mathrm{odd}}=0$ and $\chi_J=4/12=1/3$. Since $x_z(E/s^z,s^2A)=x_z(E,A)$, the domain cardinality and the reversal pairing are unchanged under the corresponding comparison for **every** selected $z$.

This is an explicit *logical countermodel*: the identical recurrence symmetry and recurrence ratio can coexist with a $z=1$ or $z=2$ area–energy compatibility class. It is not a proposed physical equation of state. The exact finite entropy $\ln W_z$ is stepwise; where a smooth thermodynamic approximation is warranted, it approaches $K\ln2\,x_z^{p_*}$ up to a bounded additive count correction. Thermodynamic derivatives are taken only after that smooth macroscopic mapping, not on the literal step function.

Therefore orientation-even turbine recurrence, even supplemented by a complete fixed $\chi_J$, cannot alone force $3pV=E$. The **spatial–recurrence compatibility law selecting the exponent** remains to be derived.

## 133.10. The joint thermodynamic Doppler invariant

We can now combine two different *specified* physical comparison operations:

- **Axial reference reread:** $f_+\mapsto e^\xi f_+$, $f_-\mapsto e^{-\xi}f_-$, preserving the product.
- **$z=1$ isentropic calibration comparison:** $A\mapsto s^2A$ and both thermal frequency equivalents $f_\pm\mapsto f_\pm/s$, preserving $Af_+f_-$.

Together, for $s>0$,

$$
A'=s^2A,\qquad f_+'=s^{-1}e^\xi f_+,\qquad f_-'=s^{-1}e^{-\xi}f_-.
\tag{133.23}
$$

**Theorem 3 (conditional area–Doppler invariance).** Under the joint map (133.23),

$$
\boxed{\mathcal I=A f_+f_-=Af_0^2}
\tag{133.24}
$$

is unchanged.

**Proof.** Direct multiplication gives $A'f_+'f_-'=s^2A(s^{-1}e^\xi f_+)(s^{-1}e^{-\xi}f_-)=Af_+f_-$. $\square$

The algebra is exact. But the physical operations are not interchangeable: the directional boost rereads one fixed reference, whereas the isentropic scaling compares different admitted thermodynamic descriptions. The latter does not assert that the fundamental ruler/clock of a single fixed enclosing background changes during cosmological expansion.

Nor does (133.24) identify the cavity or comparison area $A$ with Addendum 35's dimensionless product $Z_+Z_-$, with Addendum 70's spectral conversion area $A_f=c^2/f^2$, or with a CMB wavelength-derived resolution area. Any such identification is an additional faithful physical-map requirement.

## 133.11. The Doppler hypothesis is a test of reference ownership

The CMB gives the cleanest candidate for a nearly isotropic physical reference. Its monopole temperature supplies a spectral thermal scale; its dominant dipole supplies a directional relation to the observer. Under the ideal boosted-blackbody model, their relation has the exact reciprocal structure in (133.7). This supports the *possibility* of a symmetric reference with asymmetric observations, rather than identifying the background with a primitive swarm of photons causing the relative motion.

For R²D, the stronger hypothesis is that the **enclosing compatibility relation** owns both the nondirectional reference class and the permitted directional reread. The empirical Doppler equation tests a downstream physical representation of this hierarchy. Its exact measured success alone cannot determine the primitive native count relation or show that the CMB is the unique universal background of mass-energy.

A candidate CMB ruler should be associated with the radiation spectral scale, on the order of millimetres, rather than the cosmological size of the visible universe. This is a **physical-scale proposal**, not a definition of the primitive R²D boundary ruler. The often-written $\ell=c/f$ already inserts electromagnetic $c$ and cannot independently establish that $c$.

## 133.12. What remains open for universal $c$

To elevate the conditional invariant to a universal background result, the following must be established independently:

1. **Native exponent selection.** Construct a complete enclosing area–symmetric-recurrence compatibility whose invariant, prior to energy and time units, selects the analog of $z=1$ rather than $z=2$.
2. **Realization discipline.** Preserve the distinction between possible multiplicity, realized complete returns, scalar background $b_J$, and recurring background count $N_J^\Phi$. Determine which invariant survives actual realized recurrence rather than merely possible symmetric support.
3. **Thermal clock identification.** Show whether and how the physical background recurrence satisfies $f_\Phi=\alpha_\Phi k_BT/h$, and whether $\alpha_\Phi$ remains coherent between the relevant backgrounds.
4. **Physical area identification.** Derive a faithful mapping from area-defining native distinguishability to a particular physical comparison area without defining it through $c/f$.
5. **Two-horizon preservation.** Under Addendum 132's common-owner construction, verify that the quantum and gravitational read maps preserve the *same* invariant and do not merge distinct compatible values.
6. **Universal speed test.** Establish invariance under admissible inertial-frame comparisons and identify independently the electromagnetic propagation read and the background calibration in mass-energy. No step may invoke $E=mc^2$ to define the constant being derived.

These requirements do not imply that every thermal turbine has the radiation equation of state. The selected $z=1$ class, if it exists primitively, may be a distinguished enclosing background relation even while subordinate thermal systems exhibit different physical equations of state.

## 133.13. Established results, conditional results, and limitations

**Established mathematics under explicit assumptions:**

- Positive opposed readings admit a unique geometric-mean/log-ratio decomposition; reciprocal rereads preserve the product.
- A self-similar $3$D thermodynamic compatibility invariant under $(E,A)\mapsto(s^{-z}E,s^2A)$ obeys $3pV=zE$ in its smooth thermodynamic projection.
- The $z=1$ class gives $Af_T^2=\mathrm{constant}$ along fixed-entropy comparison classes.
- A joint $z=1$ calibration comparison and reciprocal axial reread preserve $Af_+f_-$.
- Exact symmetric finite record relations do not uniquely select $z=1$.

**Physical results imported as tests, not R²D derivations:**

- Ideal boosted-blackbody Doppler temperatures obey $T_+T_-=T_0^2$ only for opposite axial directions.
- Equilibrium radiation satisfies $p=E/(3V)$ and realizes $S\propto(E\sqrt A)^{3/4}$ for self-similar $3$D enclosures.
- A monatomic ideal gas instead has $pV=2E/3$ under the specified thermal-energy read.

**Not established:** exact physical realization of Addendum 35's positive count coordinates as CMB spectral temperatures; a unique native selection of $z=1$; equality of the thermal frequency equivalent and the native background clock; a numerical calibration of $Af^2$ without importing electromagnetic $c$; identification of the CMB with primitive $b_J$; or the quantum–gravitational universality of $c$.

## Conclusion

There is one enclosing reference and more than one possible directional read of it. The Doppler effect makes that separation physically explicit: the axial directional decomposition changes while its reciprocal background product remains fixed. A distinct thermodynamic theorem identifies exactly which joint area–energy homogeneity produces a quadratic area–frequency invariant.

The two results combine as

$$
\boxed{
\begin{gathered}
\text{Enclosing symmetric compatibility}\\
\Downarrow\quad\text{(full recurrence relation required)}\\
\text{Positive reciprocal turbine recurrence}\\[2pt]
\text{and a separately specified }z=1\text{ area–energy compatibility}\\
\Downarrow\\
3pV=E,\qquad Af_T^2=\mathrm{constant}\\
\Downarrow\quad\text{(physical axial Doppler reread)}\\
Af_+f_-=Af_0^2.
\end{gathered}}
$$

The unproved arrow is the *selection of $z=1$ by enclosing native compatibility*. That is now the exact thermodynamic target for the universal-$c$ program. Quantum and gravitational extension should follow only after this count-level selection and its physical calibrations have been independently audited.

## References

1. R²D Part I, *A Theory of Dimensionless Recursive Counting*, authoritative September 25, 2026 canon: https://r2dscience.github.io/r2d-canon-publication/canon/part-i.html
2. R²D Part II, *Joint Readability of Recurrence and Distinguishability*: https://r2dscience.github.io/r2d-canon-publication/canon/part-ii.html
3. R²D Part III, *The Recursive Clock and the Horizons of Readability*: https://r2dscience.github.io/r2d-canon-publication/canon/part-iii.html
4. R²D Part IV, *Projection: The Physics Constructed from What Remains*: https://r2dscience.github.io/r2d-canon-publication/canon/part-iv.html
5. R²D Addendum 35, *The Reference Boundary Occurs Before Lorentz Geometry*: https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-035-the-reference-boundary-occurs-before-lorentz-geometry.html
6. R²D Addendum 36, *Invariant Boundary Coupling Occurs Before mc²*; Addendum 63, *Fixed Reference Area Occurs Before Dark-Energy Attribution*.
7. R²D Addenda 69–70, thermal–quantum replacement and blackbody radiation; Addendum 105, observational inversion; Addendum 112, sampled multiplicity before thermal fluctuations.
8. R²D Addenda 120, 122, 124–125, exact enclosing compatibility and native complete-recurrence classifications.
9. R²D Addendum 131, *Symmetric Background Before Turbine Recurrence*.
10. R²D Addendum 132, *The Invariant That Survives Two Horizons*.
11. Particle Data Group, *Cosmic Microwave Background*, Review of Particle Physics (2020): https://pdg.lbl.gov/2021/reviews/rpp2020-rev-cosmic-microwave-background.pdf
12. University of Bonn, *CMB Thermal Spectrum: Blackbody Entropy and Adiabatic Relations*: https://astro.uni-bonn.de/~kbasu/CMB/Online_Slides/CMB.03%20-%20thermal-I.pdf
