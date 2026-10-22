---
r2d_id: addendum-100
title: 'Addendum 100 — The Empty Vessel: Recursive Replacement, Observation, and Irreversibility'
subtitle: Dynamic Coins, the Gibbs Limit, and Epoch-Dependent Enclosing Realization
source_type: addendum
authority: addendum
primitive_authority: false
addendum: 100
unit: addendum
indexable: true
integrated_in_publication_canon: true
ask_r2d_status: pending_separate_corpus_update
source_format: author_supplied_markdown
source_file: Addendum 100.md
source_sha256: dac7a7c1608ef7e6d809adad95d9c28dd34e0f46c1cc9ad42b3e3dd82e1c2194
source_canon_commit: 6c0059d32f3b1918f2d7fbdbc854e3d11477db6e
math_representation: LaTeX
review_status: authoritative
promotion_date: '2026-10-21'
---

## Abstract

Recursively Realized Distinguishability (R²D) defines multiplicity before occupancy. A boundary specifies a landscape of possible realizations independently of whether that landscape is occupied. Subordinate occurrences do not construct the enclosing multiplicity landscape. They realize the possibilities already defined by the enclosing boundary.

This addendum examines the filling and emptying of a defined multiplicity landscape through a dynamic ensemble of coins. Ten binary coins define an eleven-macrostate binomial landscape before any coin is tossed. When the individual coin states are fully identified, the occupied configuration has multiplicity one at the subordinate readout. When the enclosing ensemble is realized, the subordinate distinctions are recursively replaced by the enclosing macrostate classification. The two count domains are not simultaneously occupied.

Complete observation of the individual coins reverses the operative replacement. An enclosing 5:5 macrostate has 252 compatible microstates. Observation of all ten individual states replaces that occupied enclosing macrostate with one resolved configuration having multiplicity one. The enclosing landscape remains mathematically defined, but it is no longer the occupied count domain. Observation therefore empties the vessel.

This distinction clarifies the apparent conflict between reversibility and irreversibility. A realized enclosing ensemble may return to its 10:0 macrostate without restoring the initial condition of ten individually identified subordinate states and an unoccupied enclosure. Conversely, complete subordinate observation can restore individual-state readability without undoing the enclosing occurrence through which the ensemble was previously realized.

The direction of recursive replacement depends on enclosing-compatible possibility and retention. The Gibbs limit establishes the complementary condition under which an enclosing landscape ceases to be realized because the distinctions required to sustain it become unreadable. Filling and emptying may therefore reverse locally, while the larger supporting boundary continues to determine the compatible direction of realization.

An enclosing boundary may favor one macrostate direction during one epoch and another direction during a subsequent epoch. Irreversibility does not require globally monotonic macrostate motion. The invariant is the enclosing-first causal ordering of recursive realization: subordinate realizations cannot independently determine or reverse the enclosing occurrence that defines their compatibility.

The addendum applies the existing R²D count architecture without introducing new primitive quantities, entropy production, physical forces, or a bottom-up construction of enclosing possibility. It also identifies recursive replacement of the occupied count boundary as the proposed mathematical foundation for an R²D interpretation of measurement.

---

## 100.1. The Vessel Is Defined Before It Is Filled

A vessel in R²D is a boundary-defined multiplicity landscape.

It is not a physical container constructed by accumulating subordinate objects. Its possibilities are determined by the classification of compatible subordinate realizations before any particular occupancy occurs.

At boundary $B_n$, let

$$
\pi_n:\mathcal U_n\rightarrow\mathcal M_n
$$

classify compatible subordinate joint realizations into distinguishable macrostates.

The multiplicity of macrostate $i$ is

$$
\boxed{
W_{n,i}=|\pi_n^{-1}(i)|.
}
$$

Its dimensionless entropy is

$$
S_{n,i}=\ln W_{n,i}.
$$

The total boundary multiplicity is

$$
\Theta_n=\sum_{i\in\mathcal M_n}W_{n,i}.
$$

These are possible counts. They do not depend on how frequently a macrostate is occupied, or even on whether it has yet been occupied.

A boundary may therefore be fully defined while its enclosing multiplicity landscape remains unoccupied.

This is the empty vessel.

**The vessel defines its possible occupancy. Occupancy does not define the vessel.**

Recursive replacement gives this distinction its causal meaning.

When the enclosing multiplicity landscape becomes the operative occupied count domain, subordinate state distinctions are replaced by the enclosing classification. They do not persist as simultaneously occupied states under a finer description.

The subordinate realizations remain necessary for the enclosing realization, but their former state identities are no longer primitive distinctions at the enclosing boundary.

This is not coarse-graining.

Coarse-graining ordinarily permits the same realization to be described simultaneously at different resolutions. R²D instead defines state identity relative to the occupied count boundary. Changing that boundary replaces the count classification.

Consequently, an occupied enclosing macrostate and a fully identified subordinate configuration cannot be treated as simultaneous occupied count states of the same recursively organized realization.

The mathematical possibilities of both boundaries can remain defined.

Their operative occupancy is governed by recursive replacement.

## 100.2. Dynamic Coins: Filling the Enclosing Vessel

Consider ten binary subordinate coins, each admitting the distinguishable states

$$
H,\qquad T.
$$

Define an enclosing ten-coin boundary $B_n$, with macrostates indexed by the number $i$ of tails.

The enclosing multiplicity landscape is

$$
\boxed{
W_{n,i}=\binom{10}{i},
\qquad i=0,\ldots,10.
}
$$

Explicitly,

$$
\{W_{n,i}\}
=
\{1,10,45,120,210,252,210,120,45,10,1\}.
$$

The total multiplicity is

$$
\Theta_n
=
\sum_{i=0}^{10}\binom{10}{i}
=
2^{10}.
$$

The complete eleven-macrostate landscape is defined before a single coin is tossed.

Now suppose the ten coins initially have individually identified states:

$$
(H,H,H,H,H,H,H,H,H,H).
$$

At this fully resolved subordinate readout, there is one identified joint configuration:

$$
W_{\mathrm{resolved}}=1,
$$

and

$$
S_{\mathrm{resolved}}=0.
$$

The enclosing ten-coin vessel is mathematically defined but has not yet become the operative occupied count domain.

Now begin tossing individual coins.

Each selected coin may return heads or tails. A toss need not change the total number of heads or tails.

As subordinate realizations occur, the enclosing multiplicity landscape may become occupied through recursive replacement.

The tosses do not create its possibilities.

For example,

$$
W_{n,5}=\binom{10}{5}=252
$$

before the first toss, after the first toss, and after the tenth toss.

The multiplicity of 5:5 does not grow from one to 252 as individual coins are tossed. It is already defined by the ten-coin boundary.

What changes is the occupied count classification.

The initially resolved subordinate states are replaced by a realized enclosing macrostate whose multiplicity is determined by the pre-existing binomial landscape.

Thus,

$$
\boxed{
\begin{gathered}
\text{Defined enclosing multiplicity}\\
\Downarrow\\
\text{Compatible subordinate realization}\\
\Downarrow\\
\text{Occupied enclosing macrostate}.
\end{gathered}
}
$$

The causal priority belongs to the enclosing possibility relation.

The coin tosses supply subordinate realization. They do not establish the mathematical possibility toward which that realization is organized.

### 100.2.1. Stochastic realization is not the definition of possibility

For illustration, suppose one coin is selected uniformly at each attempt and assigned heads or tails with equal probability.

If the enclosing state contains $i$ tails, the selected protocol gives

$$
T_{i,i+1}=\frac{10-i}{20},
$$

$$
T_{i,i-1}=\frac{i}{20},
$$

and

$$
T_{i,i}=\frac12.
$$

For neighboring macrostates,

$$
\frac{T_{i,i+1}}{T_{i+1,i}}
=
\frac{10-i}{i+1}
=
\frac{W_{n,i+1}}{W_{n,i}}.
$$

Therefore,

$$
\boxed{
\ln\frac{T_{i,i+1}}{T_{i+1,i}}
=
S_{n,i+1}-S_{n,i}.
}
$$

This is an exact relationship for the stipulated resampling protocol.

The protocol reproduces a directional ratio already present in the native multiplicity landscape.

It does not define the multiplicity landscape.

Nor does this conditional stochastic model establish a universal R²D realization rate. The same defined multiplicities can participate in different selected realization protocols.

The purpose of the calculation is to demonstrate that the combinatorial organization is prior to the stochastic readout.

**The coins do not cause the multiplicity. Multiplicity defines the possible organization of the coins.**

## 100.3. Observation Empties the Vessel

Consider the enclosing ensemble occupying the 5:5 macrostate.

At the enclosing boundary,

$$
W_{n,5}=\binom{10}{5}=252.
$$

The occupied enclosing macrostate is defined through 252 compatible subordinate realizations.

Now observe and individually identify all ten coins.

For example,

$$
HTTHTTHHHT.
$$

The completely identified configuration has exactly one compatible realization at the resolved count boundary:

$$
\boxed{
W_{\mathrm{resolved}}=1.
}
$$

The logarithmic multiplicity is

$$
S_{\mathrm{resolved}}=0.
$$

In R²D, complete subordinate observation necessarily replaces the occupied enclosing macrostate classification.

The ensemble does not remain simultaneously occupied as a 252-microstate macrostate beneath the newly resolved configuration.

The occupied count domain has changed.

Therefore,

$$
\boxed{
\underbrace{W_{n,5}=252}_{\text{enclosing occupation}}
\quad\longrightarrow\quad
\underbrace{W_{\mathrm{resolved}}=1}_{\text{subordinate occupation}}.
}
$$

This is reverse recursive replacement.

The enclosing vessel empties because the subordinate distinctions have become the operative occupied states.

The 252 compatible microstates have not been mathematically destroyed. The original enclosing boundary still defines them as possible realizations of 5:5.

But those 252 possibilities are no longer the multiplicity of the occupied state.

**Complete subordinate observation replaces enclosing occupancy.**

This is a consequence of the R²D replacement ontology, not an optional interpretation in which the same occupied state is viewed at two resolutions.

### 100.3.1. Multiplicity is not ignorance

The distinction is especially important because multiplicity must not be interpreted as uncertainty about which individually identified configuration exists underneath an unchanged macrostate.

At the enclosing boundary, the subordinate configurations possess microstate meaning relative to the enclosing classification. Their individual identities do not simultaneously remain the primitive occupied state.

When observation completely resolves the subordinate distinctions, the occupied count domain is replaced.

The state is now the identified configuration, with multiplicity one.

It is therefore incorrect within R²D to say that the observed configuration remains an occupied 5:5 macrostate containing 252 microstates, but that the observer happens to know which microstate it occupies.

That description imports the coarse-graining ontology R²D replaces.

The correct R²D distinction is between

$$
\text{occupied enclosing multiplicity}
$$

and

$$
\text{occupied resolved subordinate distinction}.
$$

The two conditions belong to different realized count domains.

### 100.3.2. The defined vessel survives its emptying

Observation changes realized occupancy, not mathematical possibility.

The ten-coin binomial landscape remains defined:

$$
W_{n,i}=\binom{10}{i}.
$$

What has changed is whether that landscape constitutes the operative occupied classification.

Thus, emptying is not destruction of possibility.

It is replacement of the realized count boundary.

This distinction permits the enclosing vessel to become occupied again through a subsequent compatible realization.

Filling and emptying are therefore opposite directions of local recursive replacement.

Neither direction is universally forbidden.

## 100.4. The Paradox of Return: Two Different 10:0 States

The dynamic coins example reveals a fundamental ambiguity in the meaning of return.

Initially, all ten subordinate coins may be individually identified as heads:

$$
(10{:}0)_{\mathrm{subordinate}}.
$$

The enclosing vessel is mathematically defined but unoccupied.

After stochastic realization fills the enclosing vessel, its occupied macrostate may eventually return to 10:0:

$$
(10{:}0)_{\mathrm{enclosing}}.
$$

The numerical tallies are identical.

The boundary-defined count states are not.

At the subordinate readout, 10:0 identifies ten separately resolved coin states.

At the enclosing readout, 10:0 identifies one macrostate belonging to an eleven-macrostate binomial landscape.

Although

$$
W_{n,0}=1,
$$

the enclosing boundary's complete multiplicity structure remains

$$
\{W_{n,i}\}_{i=0}^{10}.
$$

Therefore,

$$
\boxed{
(10{:}0)_{\mathrm{subordinate}}
\not\equiv
(10{:}0)_{\mathrm{enclosing}}.
}
$$

The return to 10:0 within the enclosing landscape does not empty the vessel.

It is another occupancy of the realized enclosing boundary.

To restore the original subordinate condition, recursive replacement must reverse so that the individual coin states again become the operative occupied distinctions.

The crucial distinction is

$$
\boxed{
\text{Return to an enclosing macrostate}
\ne
\text{return to subordinate occupancy}.
}
$$

### 100.4.1. Loschmidt and Zermelo

This distinction is relevant to both Loschmidt's reversibility objection and Zermelo's recurrence objection.

Loschmidt's objection concerns how reversible subordinate trajectories can be associated with irreversible ensemble behavior.

Zermelo's objection concerns whether eventual recurrence of a state contradicts irreversibility.

Both require a precise definition of the state whose reversal or recurrence is being asserted.

R²D provides that definition through the count boundary.

A return to the same numerical tally does not demonstrate return to the same occupied count domain.

Likewise, reversal of subordinate transitions does not establish that subordinate trajectories are the primitive source of enclosing possibility or direction.

The two historical objections therefore expose a boundary-identification problem.

The numerical recurrence

$$
10{:}0\longrightarrow\cdots\longrightarrow10{:}0
$$

does not, by itself, distinguish a return within the enclosing landscape from restoration of the original resolved subordinate condition.

R²D requires those returns to be classified separately.

This is an R²D resolution of the boundary ambiguity underlying the paradoxes. It does not prohibit recurrence of a complete state within one fixed boundary-defined domain.

**Reversibility must be defined at the same boundary at which the claimed return is counted.**

## 100.5. Why the Vessel Fills or Empties

The larger boundary is not necessarily favored merely because it is larger.

Recursive realization depends on the relative possibilities of competing boundary-defined alternatives and the applicable retention relation.

Consider a defined enclosing vessel with two alternative realized organizations:

- $F$: the enclosing multiplicity landscape is occupied.
- $E$: subordinate distinctions are occupied instead.

These alternatives must be distinguishable within a common supporting compatibility domain before their relative multiplicities can be compared.

Let

$$
\Theta_F
$$

and

$$
\Theta_E
$$

be their compatible realization counts at that supporting boundary.

The exact possible-count comparison is

$$
\boxed{
\Delta S_{E\to F}
=
\ln\frac{\Theta_F}{\Theta_E}.
}
$$

Part I already establishes the corresponding directional count identity:

$$
\Delta S+\Delta P
=
\ln\frac{\Theta_F}{\Theta_E}.
$$

Under proportional occurrence realization, and including the relevant productive retention difference, the occupancy relation is

$$
\boxed{
\Delta G_{E\to F}
\approx
\ln\frac{\Theta_F}{\Theta_E}
-
\Delta R_{E\to F}.
}
$$

This gives three regimes while both alternatives remain readable.

When

$$
\ln\frac{\Theta_F}{\Theta_E}
>
\Delta R_{E\to F},
$$

the filled enclosure has greater occupancy support.

When

$$
\ln\frac{\Theta_F}{\Theta_E}
<
\Delta R_{E\to F},
$$

subordinate occupation has greater support.

At equality,

$$
\boxed{
\ln\frac{\Theta_F}{\Theta_E}
=
\Delta R_{E\to F},
}
$$

the two alternatives possess equal occupancy support under the stated realization approximation.

In the absence of differential retention, the corresponding count balance reduces to

$$
\Theta_F=\Theta_E.
$$

These relations do not introduce a new primitive ratio. They apply the existing R²D possible-count and occupancy equations to the specified supporting-boundary alternatives.

The balance concerns relative realization support. It does not necessarily imply that the enclosing landscape has collapsed or that occurrence has ceased.

Most importantly, the result does not permit arbitrary comparisons between multiplicities counted at different boundaries. The filled and empty alternatives must first be defined by one supporting compatibility classification.

## 100.6. The Gibbs Limit: Collapse of an Enclosing Landscape

The Gibbs paradox establishes the complementary condition under which an enclosing multiplicity landscape ceases to be realized.

Consider two distinguishable subordinate alternatives $A$ and $B$.

When the enclosing boundary distinguishes

$$
A\ne B,
$$

the species-label multiplicity of mixing is

$$
W_{\mathrm{mix}}
=
\frac{(N_A+N_B)!}{N_A!N_B!}.
$$

Its logarithmic multiplicity is

$$
S_{\mathrm{mix}}=\ln W_{\mathrm{mix}}.
$$

The count is legitimate only while the boundary retains the distinction required to classify exchanges of $A$ and $B$ as different realizations.

Now suppose that distinction becomes unreadable at the enclosing boundary:

$$
A\sim B.
$$

Exchanging $A$ and $B$ no longer creates another distinguishable enclosing realization.

The species-label multiplicity collapses:

$$
\boxed{
W_{\mathrm{mix}}^{A/B}=1.
}
$$

Hence,

$$
S_{\mathrm{mix}}^{A/B}=0.
$$

No entropy has been produced or destroyed.

The distinction that previously defined the enclosing multiplicity is no longer realized.

The subordinate realizations need not disappear. Their former enclosing count meaning has been replaced.

This is the Gibbs limit developed in Part II, Chapter 14.

### 100.6.1. Filling–emptying balance is not landscape collapse

Three conditions must remain distinct:

$$
\boxed{
\text{mode exchange}
\ne
\text{productive stall}
\ne
\text{landscape collapse}.
}
$$

At mode exchange, two occupied macrostates have equal support within a realized landscape.

At productive stall,

$$
P_n=R_n,
$$

and

$$
A_n=0.
$$

The landscape may remain realized.

At Gibbs-type collapse, a distinction required to sustain the enclosing landscape becomes unreadable, and that enclosing classification ceases to belong to the realized count hierarchy.

The filling–emptying balance equation therefore applies only while $E$ and $F$ remain distinguishable alternatives within the same supporting count domain.

Once the defining distinction of $F$ has collapsed, the earlier comparison cannot be continued as though $F$ remained an occupied phase.

The Gibbs limit establishes the boundary of realizability, not necessarily the point of equal occupancy support.

### 100.6.2. Observation and Gibbs collapse as reciprocal count changes

Complete coin observation and Gibbs-type collapse both change which distinctions define the occupied count domain.

In complete coin observation, previously replaced subordinate distinctions become individually readable. The occupied enclosing macrostate is replaced by resolved subordinate occupation.

In Gibbs-type collapse, a distinction necessary to sustain the enclosing landscape becomes unreadable. The former enclosing multiplicity is no longer realized.

The two cases do not require identical physical processes or identical distinctions.

They express the same R²D principle:

**Multiplicity is realized only at the boundary where its defining distinctions constitute the occupied count classification.**

An enclosing vessel can therefore fill and empty without creating or destroying its mathematically defined possibilities.

## 100.7. Recursive Expansion and the Exhaustion of Distinguishable Peers

Recursive replacement can produce greater multiplicity per enclosing unit while reducing the number of independently distinguishable peers available for further replacement.

Consider one hundred binary coins.

They may be organized into ten ten-coin ensembles and then into one hundred-coin enclosure.

For an unrestricted construction with complete disjoint grouping of $q$ peers,

$$
M_{n+1}=\frac{M_n}{q},
$$

where $M_n$ is the number of independently available peer units.

The total multiplicity per new enclosing unit is

$$
\Theta_{n+1}^{unit}
=
(\Theta_n^{unit})^q.
$$

Consequently,

$$
\boxed{
M_{n+1}\ln\Theta_{n+1}^{unit}
=
M_n\ln\Theta_n^{unit}.
}
$$

This exact identity describes the unconstrained grouping construction.

The multiplicity available per enclosing unit increases while the number of independent units decreases.

Under a rule requiring $q$ disjoint peers for another replacement, expansion cannot proceed when fewer than $q$ suitable peer units remain.

This is one finite combinatorial limit.

The Gibbs principle supplies another: even when a proposed enclosing boundary can be mathematically defined, its realization requires sufficient distinguishability and recurrence among the subordinate realizations that sustain it.

If those requirements fail, the enclosing landscape collapses from the realized hierarchy.

The two limits are related but not identical.

One concerns the availability of sufficient peer units for a specified recursive construction.

The other concerns the readability of the distinctions required to sustain an already-defined enclosing classification.

Thus, recursive expansion need not continue indefinitely merely because deeper enclosing possibilities can be written mathematically.

**Expansion stalls when the required next enclosing realization is no longer supported by the available recursive distinguishability and recurrence.**

This condition is boundary-specific. It is not a universal claim that a particular number of coins or a particular multiplicity defines the largest possible scale.

## 100.8. Local Reversibility and Epoch-Dependent Enclosing Direction

A defined enclosing vessel can fill, remain occupied, empty, and fill again.

These changes are not necessarily locally irreversible.

A supporting boundary can also favor opposite macrostate directions in different epochs.

For example, during one epoch,

$$
J_1\longrightarrow J_2
$$

may be favored by its enclosing possibility and retention relations.

During another epoch,

$$
J_2\longrightarrow J_1
$$

may be favored.

Neither transition requires reversal of the recursive causal ordering.

The enclosing boundary defines which subordinate joint realizations are compatible with each occurrence.

Part I gives

$$
\boxed{
\chi_{n+1}^{(r)}
\Longrightarrow
(\mathcal C_{n,a})_{a\in I_n}
\in\mathfrak D_{n+1,\chi}.
}
$$

The enclosing occurrence defines its compatible subordinate realization domain.

After the local realization is completed, recursive carry changes its count meaning:

$$
\mathcal C_{n,a}
\overset{\kappa_n}{\mapsto}
\chi_{n+1}^{(r)}.
$$

Recursive carry is not reverse causation.

A subordinate boundary may reverse its own occupancy, but it cannot independently determine or reverse the enclosing occurrence that defines its compatibility.

Accordingly,

$$
\boxed{
\begin{aligned}
&\text{Local occupancy may reverse},\\
&\text{Local phase replacement may reverse},\\
&\text{Enclosing macrostate direction may reverse},\\
&\text{Recursive causal priority remains enclosing-first}.
\end{aligned}
}
$$

The largest supporting boundary need not move monotonically through its landscape.

Its direction may change between epochs.

The invariant is the causal ordering between enclosing possibility and subordinate realization.

## 100.9. Theorem — Non-Inversion of Enclosing Causal Priority

**Theorem.** Let $B_{n+1}$ be a realized enclosing boundary with occurrence $\chi_{n+1}^{(r)}$, and let $\mathfrak D_{n+1,\chi}$ be its compatible joint-realization domain.

A local reversal of subordinate occupancy or recursive phase replacement cannot independently invert the causal priority of that enclosing occurrence.

### Proof

By the R²D enclosing-realization relation,

$$
\chi_{n+1}^{(r)}
\Longrightarrow
\mathbf h_n^{(r)}
\in\mathfrak D_{n+1,\chi}.
$$

Every subordinate realization compatible with the enclosing occurrence belongs to this joint-realization domain.

Suppose one subordinate boundary reverses its occupancy or undergoes a replacement between an enclosing and subordinate occupied classification.

If the reversed local realization remains compatible with the same enclosing occurrence, it remains one of that occurrence's compatible realizations.

If it is not compatible, realization requires a different compatible joint condition or another enclosing occurrence.

Neither alternative gives the subordinate reversal primitive authority over the enclosing occurrence.

Recursive carry does not alter this result because it reclassifies completed realization rather than generating the enclosing occurrence from subordinate causes.

Therefore,

$$
\boxed{
\text{Subordinate reversal}
\not\Longrightarrow
\text{inversion of enclosing causal priority}.
}
$$

This establishes non-inversion of recursive causal ordering.

It does not prohibit the enclosing boundary from undergoing a subsequent occurrence with the opposite macrostate direction.

It does not prohibit return to a previously occupied macrostate.

Nor does it assert that every locally reversible phase change produces nonreciprocal opposed-leg occurrence counts.

The latter remains a separate R²D relation:

$$
L_{\tau,n,a,\mathcal C}
=
-\ln\eta_{n,a,\mathcal C}.
$$

The present theorem concerns the causal ordering of recursive realization, not a universal numerical value of occurrence-count nonreciprocity.

## 100.10. Quantum Measurement and Boundary Replacement

The coin construction supplies a direct count-theoretic foundation for investigating quantum measurement in R²D.

An occupied enclosing macrostate can possess multiple compatible subordinate realizations.

Complete observation of subordinate distinctions replaces that occupied enclosing classification with one resolved occupied state.

For the ten-coin 5:5 example,

$$
W_{\mathrm{enclosing}}=252
$$

becomes

$$
W_{\mathrm{resolved}}=1
$$

under complete subordinate observation.

The transition does not mean that 251 physical configurations have been destroyed.

It means that the former 252-microstate enclosing classification is no longer the occupied count domain.

This is not an optional informational reinterpretation within R²D. It follows from the replacement ontology: the occupied state is defined at its operative boundary, and complete subordinate resolution replaces the enclosing occupancy.

The possible quantum significance is that measurement may be understood as a physical realization of this same boundary-replacement operation.

Rather than treating measurement as an observer learning which primitive microstate was always occupied within an unchanged enclosing state, R²D identifies a change in the occupied count boundary.

Schematically,

$$
\boxed{
\begin{gathered}
\text{Occupied enclosing multiplicity}\\
\Downarrow\\
\text{Complete subordinate measurement}\\
\Downarrow\\
\text{Replacement of the occupied count boundary}\\
\Downarrow\\
\text{Resolved subordinate occupancy}.
\end{gathered}
}
$$

The replacement rule is part of R²D's primitive architecture.

Its quantitative identification with quantum measurement remains a physical mapping problem.

A classical binomial ensemble does not, by itself, derive quantum amplitudes, interference, entanglement, or Born-rule outcome statistics.

Those require the separate R²D quantum readability and recurrence relations.

The significance of this addendum is to identify the proposed primitive operation without importing a coarse-graining ontology.

**Measurement does not merely reveal an unchanged enclosing occupancy. It replaces the occupied boundary through which the realization is counted.**

## 100.11. Discussion

The empty-vessel construction unites several distinctions already developed separately in the R²D canon.

Multiplicity exists before occupancy.

Recursive replacement changes the operative count domain rather than concealing subordinate states beneath an unchanged enclosing occupation.

Dynamic coins demonstrate that stochastic subordinate transitions can realize a defined ensemble landscape without constructing its possibilities.

Complete subordinate observation empties the occupied enclosure by restoring resolved subordinate distinctions as the operative count classification.

The return to 10:0 demonstrates that numerical equality of macrostates does not establish equality of boundary-defined realizations.

The Gibbs limit establishes that an enclosing landscape ceases to be realized when its defining distinctions are no longer supported by sufficient subordinate readability and recurrence.

The existing possibility and retention equations determine relative filling and emptying support when the competing realization alternatives are jointly defined at one supporting boundary.

Local reversals remain compatible with continued enclosing causal priority.

The enclosing boundary may also change its macrostate direction between epochs.

These conclusions require no new primitive force, entropy production, or physical time coordinate.

They do not imply that every vessel must fill, that every filled vessel must persist, or that the largest realized boundary can never revisit an earlier macrostate.

They establish a more precise distinction:

**The direction of occupation may reverse. The causal priority of enclosing possibility over subordinate realization does not.**

The quantum implication is similarly precise. Complete subordinate observation necessarily replaces occupied enclosing multiplicity within R²D. Establishing its full correspondence with physical quantum measurement requires the additional quantum mapping, not a modification of the replacement rule itself.

## 100.12. Conclusion — Possibility, Occupancy, and the Arrow

The vessel is defined before it is filled.

Its multiplicity determines the compatible possibilities of its occupancy. The subordinate realizations that fill it do not create those possibilities.

When the vessel is occupied, subordinate distinctions are recursively replaced by the enclosing macrostate classification.

When all subordinate states are observed, the replacement reverses. The enclosing vessel empties, and the resolved subordinate configuration becomes the occupied count state.

An enclosing 5:5 macrostate with 252 compatible microstates is replaced by one identified configuration with multiplicity one.

The enclosing mathematical possibilities remain defined. They are no longer the multiplicity of the occupied realization.

The same principle distinguishes an enclosing return to 10:0 from a return to the original individually identified ten-head condition.

The Gibbs limit establishes the complementary loss of enclosing realization when the distinctions required to sustain its landscape become unreadable.

Filling and emptying can therefore reverse locally. Enclosing macrostate direction can reverse between epochs.

Neither reversal inverts the causal priority of the supporting boundary.

$$
\boxed{
\text{Enclosing possibility}
\Longrightarrow
\text{compatible subordinate realization}.
}
$$

**Possibility defines the vessel. Realization fills it. Observation empties it. The direction of occupancy may reverse, but the causal ordering of recursive realization does not.**
