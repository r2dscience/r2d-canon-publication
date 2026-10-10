---
r2d_id: addendum-005
title: Addendum 5 — Ensemble Replacement Occurs Before Muscle-Scale Statehood
subtitle: Recursive Loss of Switch Identity, Multiplicity, and Closure in the Myosin Ensemble
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 5
unit: addendum
integrated_in_publication_canon: true
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: authoritative_markdown
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 1042
pdf_page_end: 1065
math_representation: LaTeX for normalized equations; source-faithful Unicode retained in noncritical schematic/prose expressions
equation_status: source_pdf_visual_reconstruction_and_standalone_render_qa
semantic_sync: 2026-09-25-no-substantive-universality-amendment-required
primitive_authority: false
review_status: author_review_pending
machine_revision: 2026-10-09-equation-reconstruction-v1
qa_status: standalone_render_pass_full_book_pending
promotion_date: null
equation_audit_scope: all_display_math_reconstructed_and_checked_against_pdf; source_clipped_prose_flagged
---

# Addendum 5 — Ensemble Replacement Occurs Before Muscle-Scale Statehood

## Recursive Loss of Switch Identity, Multiplicity, and Closure in the Myosin Ensemble

## Abstract

Addendum 4 showed that the two states of the myosin switch,

$M_1\equiv M_1\!\cdot D\!\cdot P_i$

and

$M_2\equiv A\!\cdot M_2\!\cdot D$,

can be spectroscopically resolved and their ensemble distribution measured directly.

The observed switch asymmetry

$$A_M=\ln\frac{[M_2]}{[M_1]}$$

is organized by chemical possibility and mechanical retention:

$A_M=P_M-R_M$.

The experiment therefore separates the local realization of the myosin switch from the enclosing chemical-
mechanical relation that organizes it.

A second result follows from the same experiment.

The myosin ensemble does not preserve the identities or trajectories of its individual switches.

Let N myosin switches each occupy one of two states,

$$x_\alpha\in\{M_1,M_2\},\qquad\alpha=1,\ldots,N.$$

A labeled subordinate realization is

$$\mathbf x=(x_1,x_2,\ldots,x_N).$$

The enclosing ensemble does not distinguish every such assignment.

<!-- source_pdf_page: 1043 -->

Instead, it distinguishes the number of switches occupying M2 :

$$i=\#\{\alpha:x_\alpha=M_2\}.$$

The replacement map is therefore

$$\pi_N:\{M_1,M_2\}^{N}\longrightarrow\{0,1,\ldots,N\},$$

with

$$\pi_N(\mathbf x)=i.$$

All labeled subordinate realizations producing the same i are one enclosing macrostate.

Their number is

$$W_N(i)=\left|\pi_N^{-1}(i)\right|=\binom{N}{i}.$$

The individual switch identities have therefore not merely been hidden.

They have been replaced by multiplicity.

Likewise, distinct subordinate switch histories can produce the same ensemble occupancy history. Their
detailed trajectories are distinguishable at the individual-switch boundary but cease to be state coordinates
of the enclosing ensemble boundary.

Thus recursive replacement is stronger than averaging or coarse-graining:

> subordinate state identity → enclosing multiplicity.

Completed subordinate dynamics can occur without an enclosing state change. A switch may undergo

$$M_1\longrightarrow M_2\longrightarrow M_1$$

while the ensemble returns to the same occupancy i.

The molecular transition occurred physically.

Its trajectory does not survive as an independent ensemble variable.

At active isometric stall, the experimentally resolved switch ensemble is symmetric,

$$[M_1]=[M_2],$$

while subordinate molecular activity remains physically necessary to realize the active state.

<!-- source_pdf_page: 1044 -->

Thus:

> **subordinate activity does not imply enclosing state change.**

The individual switches realize the ensemble state.

They do not persist as the state of the ensemble.

The central statement is therefore:

> **The myosin ensemble replaces the identities and trajectories of its individual switches by an enclosing occupancy state.**

Hence:

> **Ensemble replacement occurs before muscle-scale statehood.**

## 1. Addendum 4 Exposed the Intermediate Boundary
Addendum 4 established an experimentally accessible relationship among three independently readable
quantities:

$$P_M,\qquad R_M,\qquad A_M.$$

Chemical possibility and mechanical retention organize the spectroscopically measured myosin-switch
asymmetry:

$A_M=P_M-R_M$.

The local molecular distribution is therefore not uniquely specified by force alone.

Nor does the local molecular distribution uniquely specify force.

This already separates the myosin-switch ensemble from the enclosing mechanical state of muscle.

But it leaves another question unanswered:

> What happens to the individual myosin switches when the ensemble state becomes the readable physical state?

The answer is recursive replacement.

<!-- source_pdf_page: 1045 -->

## 2. Begin With the Individual Switch Boundary
Let the muscle contain N myosin switches.

Each switch has its own state domain:

$$\mathcal X_\alpha=\{M_1,M_2\}.$$

For switch α,

$$x_\alpha=M_1$$

and

$$x_\alpha=M_2$$

are distinguishable alternatives at the switch boundary.

A complete labeled subordinate realization is therefore

$$\mathbf x=(x_1,x_2,\ldots,x_N)$$

with

$$\mathbf x\in\prod_{\alpha=1}^{N}\mathcal X_\alpha.$$

At this subordinate description, switch identity matters.

The statement

$$x_7=M_2$$

is different from

$$x_{19}=M_2.$$

These are distinguishable subordinate assignments.

## 3. The Ensemble Defines a Different State Domain

The spectroscopically resolved ensemble is not classified by the complete labeled vector

$$\mathbf x.$$

It is classified by the distribution between M1 and M2 .

<!-- source_pdf_page: 1046 -->

Let

$$i=\#\{\alpha:x_\alpha=M_2\}.$$

Then

$$N-i=\#\{\alpha:x_\alpha=M_1\}.$$

The ensemble macrostate is therefore indexed by

$$i\in\{0,1,\ldots,N\}.$$

The count domain has changed.

## 4. Recursive Replacement Is an Explicit Map

Define the enclosing classification

$$\pi_N:\{M_1,M_2\}^{N}\longrightarrow\{0,1,\ldots,N\}$$

by

$$\pi_N(\mathbf x)=i.$$

This map is many-to-one.

Distinct subordinate realizations satisfy

$$x^{(1)}\ne x^{(2)}$$

while

$$\pi_N(\mathbf x^{(1)})=\pi_N(\mathbf x^{(2)}).$$

At the ensemble boundary, these are not two different states.

They are two subordinate realizations of the same enclosing state.

## 5. The Number of Replaced Realizations Is Multiplicity

For an ensemble macrostate containing $i$ switches in $M_2$,

$$W_N(i)=|\pi_N^{-1}(i)|.$$
<!-- source_pdf_page: 1047 -->

For a two-state ensemble,

$$W_N(i)=\binom{N}{i}.$$
The corresponding entropy is

$$S_N(i)=\ln W_N(i)=\ln\binom{N}{i}.$$

This is the crucial replacement.

The subordinate assignments do not survive as additional coordinates of the enclosing macrostate.

Their number becomes the multiplicity of that macrostate.

Thus:

> subordinate distinguishability → enclosing multiplicity.

## 6. A Ten-Switch Example Makes the Replacement Explicit

Let

$$N=10$$

and

$$i=5.$$

One subordinate realization is

$$(M_2,M_2,M_2,M_2,M_2,M_1,M_1,M_1,M_1,M_1).$$

Another is

$$(M_1,M_2,M_1,M_2,M_1,M_2,M_1,M_2,M_1,M_2).$$

Many others are possible.

The number is

$$W_{10}(5)=\binom{10}{5}=252.$$

<!-- source_pdf_page: 1048 -->

At the individual-switch boundaries there are 252 distinct labeled assignments compatible with five
switches occupying M2 .

At the ensemble boundary there is one macrostate:

$$i=5.$$

The ensemble does not contain 252 partially visible versions of i = 5.

It contains one ensemble state with multiplicity 252.

This distinction is fundamental.

> **Multiplicity is not hidden state identity; multiplicity is what subordinate state identity becomes after replacement.**

## 7. Replacement Is Not Averaging

A conventional averaging description would retain the subordinate state vector

$$\mathbf x$$

as the underlying physical state and construct an average from it.

Schematically:

$$(x_1,x_2,\ldots,x_N)\longrightarrow\langle x\rangle.$$

The average would be a compressed description of a more fundamental persistent microscopic state.

R²D makes a different claim.

The enclosing boundary defines a new count domain:

$$\mathbf x\xrightarrow{\pi_N}i.$$

Once i is the enclosing state, the labeled assignments are no longer additional state variables of that
boundary.

They define its multiplicity:

$$W_N(i)=|\pi_N^{-1}(i)|.$$
Thus:

<!-- source_pdf_page: 1049 -->

> **replacement is not averaging.**

## 8. Replacement Is Also Not Coarse-Graining
Coarse-graining normally implies that the finer state remains the underlying state but is observed with
insufficient resolution.

That would suggest:

> same state space + less resolution.

Recursive replacement instead gives:

> different boundary → different state space.

At the subordinate boundary,

$$x_\alpha$$

is a legitimate distinction.

At the ensemble boundary,

$$i$$

is the legitimate distinction.

The subordinate state is not merely blurred.

Its identity has been replaced.

## 9. Permuting Switch Identity Does Not Change the Ensemble State
Consider two switches α and β .

Exchange their states:

$$x_\alpha\leftrightarrow x_\beta.$$

If the total number of M2 switches remains i, then

$$\pi_N(\mathbf x)=\pi_N(\mathbf x').$$

The ensemble state is unchanged.

<!-- source_pdf_page: 1050 -->

Therefore:

> which switch occupies $M_2$

is not an enclosing ensemble distinction.

The ensemble distinguishes

> how many switches occupy $M_2$.

The count domain has replaced switch identity by occupancy.

## 10. The Ensemble State Is Prior to Any Particular Assignment

The multiplicity

$W_N(i)=\binom{N}{i}$

is defined statistically by the ensemble classification.

It does not depend on which particular molecules happen to occupy M2 at a given instant.

Thus the switches do not create the multiplicity landscape.

The ensemble state definition creates the combinatorial structure:

$$i\longrightarrow W_N(i).$$

The individual switches realize occupancy within that structure.

This distinction can be written:

> **multiplicity structure is not realized occupancy.**

## 11. Components Realize Multiplicity; They Do Not Define It

For the myosin ensemble,

$W_N(i)=\binom{N}{i}$

follows from the binary state classification itself.

<!-- source_pdf_page: 1051 -->

The particular myosin molecules do not determine the binomial coefficient.

They determine which ensemble state is realized.

Thus:

> switch realization → ensemble occupancy,

while

> ensemble classification → multiplicity structure.

This distinction prevents the subordinate components from being mistaken for the source of the enclosing
state space.

## 12. State Identity Is Replaced Dynamically as Well as Statistically
Recursive replacement applies not only to instantaneous assignments.

It also applies to trajectories.

Let

$$\Gamma^{(1)}=\{\mathbf x^{(1)}(t)\}$$

and

$$\Gamma^{(2)}=\{\mathbf x^{(2)}(t)\}$$

be two different subordinate histories.

Suppose that both produce the same ensemble occupancy history:

$$i^{(1)}(t)=i^{(2)}(t).$$

Then

$$\Gamma^{(1)}\ne\Gamma^{(2)}$$

at the subordinate switch boundaries, but

$$\pi_N[\Gamma^{(1)}]=\pi_N[\Gamma^{(2)}]$$

at the ensemble boundary.

<!-- source_pdf_page: 1052 -->

The enclosing boundary therefore does not possess enough state structure to distinguish the two
subordinate histories.

Their detailed path identities have been replaced.

## 13. The Ensemble Does Not Contain Hidden Molecular Trajectories
This point should be stated carefully.

R²D does not claim that the subordinate molecular transitions failed to occur.

They occurred physically at their own boundaries.

The claim is instead:

> the completed subordinate trajectory is not a state coordinate of the enclosing boundary.

Thus:

> **subordinate trajectory is not a hidden enclosing trajectory.**

The trajectory belongs to the boundary at which it is distinguishable.

After recursive replacement, the enclosing state is defined differently.

## 14. Closure Makes the Dynamic Replacement Explicit

Consider one myosin switch undergoing

$$M_1\longrightarrow M_2\longrightarrow M_1.$$

This is a completed subordinate recurrence.

The switch changed state twice.

But if the enclosing ensemble returns to the same occupancy,

$$i\longrightarrow i,$$

then no lasting ensemble transition has occurred.

The subordinate trajectory is real.

<!-- source_pdf_page: 1053 -->

Its completed path is not an independently readable ensemble occurrence.

Thus:

> **subordinate closure does not imply enclosing state change.**

## 15. Many Subordinate Closures Can Occur During One Enclosing State
This is especially important for active biological systems.

During an interval in which the ensemble remains within one macrostate classification, many individual
switches may undergo state changes.

Schematically,

$$M_1\longrightarrow M_2\longrightarrow M_1,$$

$$M_2\longrightarrow M_1\longrightarrow M_2,$$

and many other switch-level closures may occur.

Yet the ensemble can remain near the same occupancy state:

$$i\approx\text{constant}.$$

Thus:

> **continued subordinate dynamics do not imply continued enclosing progression.**

This is the beginning of the distinction between local recurrence and enclosing recurrence.

## 16. The Enclosing Boundary Reads the Closure Consequence
What survives upward is not the molecular path itself.

The completed subordinate activity contributes to the realization of the enclosing occupancy.

Schematically:

$$\mathcal C_{M,\alpha}\xrightarrow{\text{replacement}}\text{ensemble count consequence}.$$

The detailed sequence inside

<!-- source_pdf_page: 1054 -->

$$\mathcal C_{M,\alpha}$$

is not carried as a trajectory.

Its contribution is readable only through the enclosing count structure.

This is dynamic recursive replacement.

## 17. Closure Degeneracy and Multiplicity Must Remain Distinct
Two related quantities now appear.

The static multiplicity

$$W_N(i)=|\pi_N^{-1}(i)|.$$
counts the subordinate realizations compatible with ensemble state i.

Closure degeneracy concerns the counts generated by completed subordinate recurrence and carried into
the enclosing realization.

These are not the same object.

Thus:

$$W_N\ne\nu_N.$$

Multiplicity defines the ensemble landscape.

Closure counts participate in its realization.

This distinction will become increasingly important when replacement is extended across additional scales.

## 18. Addendum 4 and Addendum 5 Now Fit Together

Addendum 4 showed:

$A_M=P_M-R_M$.

The enclosing chemical-mechanical relation organizes the switch ensemble.

Addendum 5 now shows that the ensemble does not preserve the individual switch assignments from
which it is realized.

<!-- source_pdf_page: 1055 -->

Thus the experimentally accessible architecture is:

> enclosing chemical-mechanical relation → $A_M$ → individual switch realization

while completed subordinate realization maps upward as

> switch closure → ensemble occupancy (by replacement).

The two directions answer different questions.

## 19. Downward Organization and Upward Realization Are Not the Same Arrow

The enclosing relation determines the asymmetry:

$$P_M-R_M\longrightarrow A_M.$$

The subordinate switches realize that asymmetry.

Their completed activity contributes upward to the ensemble state.

Thus R²D distinguishes:

> organization

from

> realization.

The enclosing relation answers why the distribution is oriented as it is.

The individual switches answer how that distribution is physically realized.

## 20. This Is the Observable Leapfrog Architecture
The muscle experiment therefore exposes both directions simultaneously.

<!-- source_pdf_page: 1056 -->

Causally,

$$B_{\mathrm{muscle}}\Longrightarrow B_{\mathrm{ensemble}}.$$

Locally,

$$B_{\mathrm{switch}}\longrightarrow\text{ensemble realization}.$$

The larger relation organizes downward.

The subordinate closures realize upward.

There is no contradiction because these are different operations.

The subordinate transition does not have to contain the causal definition of the enclosing state in order to
realize it.

## 21. Active Isometric Stall Makes the Separation Especially Clear

At active isometric stall,

$$[M_1]=[M_2].$$

For a symmetric idealized ensemble,

$$i=\frac{N}{2}.$$

The corresponding binomial multiplicity is maximal:

$$W_N\!\left(\frac{N}{2}\right)=W_{N,\max}.$$

Thus:

$$S_N=S_{N,\max}.$$

At the same time, Addendum 4 established

$A_M=0$

and

$P_M=R_M$.

<!-- source_pdf_page: 1057 -->

Yet active muscle does not become a collection of inactive molecules.

The equality of ensemble occupancy is compatible with continued subordinate molecular realization.

## 22. Stall Is Therefore Not the Absence of Switch Dynamics

The ensemble condition

$A_M=0$

means that the resolved occupancy is symmetric.

It does not mean

> no $M_1\leftrightarrow M_2$ transitions occur.

Individual molecular events can continue while the enclosing occupancy remains unchanged.

This makes the distinction explicit:

> **subordinate recurrence is not enclosing progression.**

## 23. “Averaging Out” Is Too Weak a Description
One might say that the individual molecular transitions simply average out at stall.

That language misses the deeper structural point.

If they merely averaged out, the individual trajectories would remain the primitive state and the ensemble
would merely report their mean.

But the ensemble state is independently defined by

$$i.$$

Its multiplicity is

$$W_N(i)=\binom{N}{i}.$$
Its asymmetry is measured by the ensemble distribution.

The identities of the individual switches are not among its state variables.

<!-- source_pdf_page: 1058 -->

Thus:

> **The subordinate trajectories do not merely average to the ensemble state; they are replaced by it.**

## 24. Replacement Explains Why Many Histories Can Realize One Function
Biological function is robust to enormous variation in subordinate history.

Many different sequences of molecular events can produce the same ensemble state.

Mathematically:

$$|\pi_N^{-1}(i)|>1.$$

Dynamically, many different paths satisfy

$$\pi_N[\Gamma^{(1)}]=\pi_N[\Gamma^{(2)}].$$

This many-to-one structure is not an experimental nuisance.

It is the defining architecture of replacement.

## 25. The Enclosing State Is Not Reconstructible From One Molecular History
Because the replacement map is many-to-one, observing one subordinate trajectory does not uniquely
determine the enclosing state architecture.

Likewise, observing the enclosing macrostate does not identify one unique subordinate history.

Thus:

> **enclosing state does not imply a unique subordinate history.**

and

> **one subordinate history does not imply complete enclosing organization.**

This is a structural non-invertibility.

<!-- source_pdf_page: 1059 -->

## 26. Recursive Replacement Is Therefore Physical, Not Epistemic
The many-to-one map is sometimes interpreted as an observer losing information.

R²D gives it a different meaning.

The boundary defines what counts as a state.

At the subordinate boundary, the labeled switch assignment is a distinction.

At the ensemble boundary, the occupancy count is the distinction.

Thus the information loss is not merely an observer choosing not to look.

It reflects a change in the physical count domain.

> replacement = change of boundary-defined statehood.

## 27. Principle — Ensemble Statehood Replaces Individual Switch Identity

For an ensemble of $N$ two-state switches,

$$\pi_N:\{M_1,M_2\}^N\longrightarrow\{0,\ldots,N\}.$$

Distinct subordinate assignments with the same image are one enclosing macrostate.

Thus:

> subordinate identity → enclosing occupancy.

## 28. Principle — Multiplicity Is the Count of Replaced Realizations

For ensemble state $i$,

$$W_N(i)=\left|\pi_N^{-1}(i)\right|=\binom{N}{i}.$$

Multiplicity therefore counts the subordinate realizations that have become degenerate with respect to the
enclosing classification.

<!-- source_pdf_page: 1060 -->

## 29. Principle — Replacement Is Not Coarse-Graining
The enclosing boundary does not merely observe the subordinate state with poorer resolution.

It defines a different state domain.

Thus:

> **recursive replacement is not coarse-graining.**

## 30. Principle — Completed Subordinate Dynamics Need Not Produce Enclosing Change

A subordinate switch may close:

$$M_1\longrightarrow M_2\longrightarrow M_1$$

while the enclosing ensemble remains

$$i\longrightarrow i.$$

Therefore:

> **subordinate closure does not imply an enclosing transition.**

## 31. Principle — Subordinate Trajectories Are Boundary Owned
A switch trajectory is meaningful at the switch boundary.

After replacement, it is not an additional trajectory of the ensemble boundary.

Thus:

> **subordinate trajectory is not a subset of an enclosing trajectory.**

The enclosing boundary possesses its own state history.

<!-- source_pdf_page: 1061 -->

## 32. Principle — Realization and Organization Run in Opposite Recursive Directions

Subordinate activity realizes the enclosing state:

$$B_{n-1}\longrightarrow B_n.$$

The enclosing relation organizes subordinate realization:

$$B_{n+1}\Longrightarrow B_n.$$

These are complementary recursive relations, not competing causal descriptions.

## 33. Logical Status

**Direct Experimental Foundation**

Addendum 4 established that the ensemble distribution between M1 and M2 is spectroscopically readable
and responds to chemical possibility and mechanical retention.

**Ensemble Definition**

For N binary switches,

$$i=\#(M_2)$$

defines the enclosing occupancy macrostate.

**Replacement Map**

$$\pi_N:\{M_1,M_2\}^N\longrightarrow\{0,1,\ldots,N\}.$$

**Multiplicity**

$$W_N(i)=\left|\pi_N^{-1}(i)\right|=\binom{N}{i}.$$

**Entropy**

$$S_N(i)=\ln W_N(i).$$

**Structural Result**

Distinct subordinate switch assignments that map to the same i are not distinct ensemble states.

<!-- source_pdf_page: 1062 -->

Their number is the multiplicity of the ensemble state.

**Dynamic Result**

Distinct subordinate histories can map onto the same ensemble occupancy history.

The detailed subordinate trajectories therefore do not survive as independent coordinates of the enclosing
state.

**R²D Interpretation**

> subordinate distinguishability → recursive replacement → enclosing multiplicity.

**Not Yet Claimed**

This addendum does not yet establish that:

- microsecond protein fluctuations are replaced by the myosin-switch state;
- IR recurrence is replaced by larger protein-scale statehood;
- quantum recurrence is replaced before molecular spectroscopy becomes readable;
- all subordinate biological scales are closure-complete relative to their enclosing state;
- or quantum and gravitational unreadability are complementary limits of the same replacement hierarchy.

Those claims require the next stages of the program.

## 34. The Replacement Architecture

The full switch-to-ensemble architecture can now be written:

> individual switch states → $\mathbf x=(x_1,\ldots,x_N)$ → $i=\#(M_2)$ (under $\pi_N$)

$$W_N(i)=|\pi_N^{-1}(i)|.$$
> ↓

$$S_N(i)=\ln W_N(i).$$

<!-- source_pdf_page: 1063 -->

Distinct switch assignments are replaced by one ensemble state.

Dynamically:

> subordinate switch closure → closure count consequence → ensemble realization.

The subordinate trajectory itself is not carried upward.

Meanwhile the enclosing chemical-mechanical relation acts downward:

> $P_M-R_M$ → $A_M$ → switch realization.

The experimentally accessible system therefore contains both directions of the recursive architecture.

## 35. Conclusion
The myosin ensemble provides a direct physical example of recursive replacement.

At the individual-switch boundary, each myosin molecule can occupy

$$M_1$$

or

$$M_2.$$

The labeled state of N switches can be written

$$\mathbf x=(x_1,\ldots,x_N).$$

But the enclosing ensemble does not preserve that labeled state as its own state variable.

<!-- source_pdf_page: 1064 -->

It distinguishes instead the occupancy

$i=\#\{\alpha:x_\alpha=M_2\}$.

The mapping

$$\pi_N(\mathbf x)=i$$

is many-to-one.

For a given i,

$$W_N(i)=\left|\pi_N^{-1}(i)\right|=\binom{N}{i}.$$

The subordinate assignments therefore do not survive as additional ensemble coordinates.

Their number becomes multiplicity.

This is the defining distinction between recursive replacement and coarse-graining.

The ensemble does not merely see an incomplete version of the individual switches.

It possesses a different state domain.

The same replacement occurs dynamically.

Different individual-switch histories can generate the same ensemble occupancy history.

A switch may undergo

$$M_1\longrightarrow M_2\longrightarrow M_1$$

without producing an enclosing ensemble transition.

Its molecular trajectory occurred physically at its own boundary.

After closure, that trajectory is no longer an independent coordinate of the ensemble state.

Thus:

> **subordinate activity does not imply enclosing progression.**

This is especially clear in active isometric muscle.

The spectroscopically resolved ensemble can remain symmetric,

<!-- source_pdf_page: 1065 -->

$$[M_1]=[M_2],$$

while subordinate molecular activity remains necessary to sustain the active state.

Calling those molecular events fluctuations that merely “average out” misses the essential change in
statehood.

The individual switches do not remain hidden ensemble coordinates.

They have been replaced.

Their distinguishable assignments become the multiplicity of the ensemble state, and their completed
dynamics contribute to its realization without preserving their path identity.

Addenda 4 and 5 therefore expose both sides of an experimentally accessible recursive relation.

Addendum 4 showed that the ensemble asymmetry is organized by the enclosing relation

$A_M=P_M-R_M$.

Addendum 5 shows that the individual molecular switches realizing this asymmetry do not remain the state
variables of the ensemble.

The enclosing relation organizes downward.

The subordinate switches realize upward.

Their identities are replaced in the passage between boundaries.

The central result is therefore:

> **The myosin ensemble does not contain the identities and trajectories of its individual switches as hidden ensemble coordinates.**

Hence:

> **Ensemble replacement occurs before muscle-scale statehood.**
