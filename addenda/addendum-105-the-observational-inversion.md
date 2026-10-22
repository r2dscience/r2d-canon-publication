---
r2d_id: addendum-105
title: Addendum 105 — The Observational Inversion
subtitle: A Mathematical Proof of Top-Down Organizing Causality
source_type: addendum
authority: addendum
primitive_authority: false
addendum: 105
unit: addendum
indexable: true
integrated_in_publication_canon: true
ask_r2d_status: pending_separate_corpus_update
source_format: author_supplied_markdown
source_file: Addendum 105.md
source_sha256: f6c595194132e48f427c0933a23ecdd35f3858501f077c4c6434577e7265d45c
source_canon_commit: 6c0059d32f3b1918f2d7fbdbc854e3d11477db6e
math_representation: LaTeX
review_status: authoritative
promotion_date: '2026-10-21'
---

# Addendum 105 — The Observational Inversion

## A Mathematical Proof of Top-Down Organizing Causality

*Recursive Replacement, Measurable Reality, and the Mistaken Reconstruction of Primitive Bottom-Up Causes*

### Abstract

Recursively Realized Distinguishability (R²D) establishes a mathematical consequence of statistical mechanics that is frequently obscured by conventional microscopic interpretations: when an enclosing state is defined, subordinate state identities are replaced as the operative measurable identities of that state. The enclosing boundary determines what constitutes a measurable macrostate, which changes count as its transitions, and which subordinate realizations are compatible with those transitions.

These are mathematical results. They follow from boundary-defined microstate–macrostate classification, recursive replacement, and compatible multiplicity. The coin construction in Part I demonstrates that changes in enclosing compatibility can reverse the directional support of subordinate alternatives without changing their native multiplicities.

Together, these results establish **top-down organizing causality**: at a realized enclosing boundary, the organization of measurable states, transitions, and compatible possibilities belongs to the enclosure. Subordinate processes realize that organization but do not independently define it.

Scientific observation can obscure this relationship. To resolve an individual microstate of an enclosing macrostate, an observer must change the operative read boundary. The resulting subordinate state is then used to reconstruct the original enclosing classification. The reconstruction is mathematically valid, but it does not establish that the resolved subordinate state was the primitive cause of the enclosing state. Treating it as such reverses the causal meaning of recursive replacement.

Repeated subordinate measurements further obscure this distinction. Variations among compatible realizations may be described as fluctuations, randomness, or noise, while the enclosing multiplicity that makes those realizations compatible is treated as a statistical consequence of their occurrence.

The distinction between physical existence and physical measurability is therefore essential. Subordinate processes may exist and recur without their individual state identities being measurable at the enclosing boundary.

The Bernoulli–Laplace exchange model provides an exact illustration. Exchanges between individual objects change compatible realizations without creating the enclosing multiplicity landscape. Its successful reproduction of enclosing count ratios demonstrates local realization under enclosing constraint, not the primitive creation of enclosing possibility by subordinate objects.

This addendum formalizes the observational inversion and establishes its causal consequence: **when an enclosing boundary is measurably realized, organizing causal priority belongs to that boundary.**

---

### 1. The Central Result

Consider two recursively related count boundaries:

$$
B_n\subset B_{n+1}.
$$

Call $B_{n+1}$ the *top* and $B_n$ the *bottom* for this comparison.

These terms refer to recursive enclosure, not necessarily to spatial height or size.

**Index convention.** When a theorem examines the macrostates and compatibility fibers of one operative boundary, it denotes that boundary generically by $B_n$. For the top–bottom pair just specified, that statement applies to the top after the index shift $n\mapsto n+1$. When the argument explicitly compares the two boundaries—as in Theorem 5 and the recurrence-weighted R²D law—$B_n$ denotes the local peer boundary and $B_{n+1}$ its enclosing boundary. These index shifts do not identify the state identities or count domains of adjacent boundaries.

The central argument consists of three mathematical results.

**First — Replacement.**

When the enclosing boundary becomes the operative read, subordinate state identities do not persist as the same measurable state identities.

**Second — Enclosing transition definition.**

The enclosing boundary defines which differences constitute its measurable state transitions and the compatible-count relationships supporting those transitions.

**Third — Enclosing realization definition.**

An enclosing state or occurrence determines the class of subordinate realizations compatible with it.

Together:

$$
\boxed{
\begin{gathered}
\text{Enclosing statehood}\\
\Downarrow\\
\text{Recursive replacement}\\
\Downarrow\\
\text{Enclosing-defined transitions and compatibility}\\
\Downarrow\\
\text{Subordinate realization}.
\end{gathered}
}
$$

The claim is not that the top acts as a mechanical hand that reaches downward to move smaller objects.

The claim is more primitive.

**The top defines the measurable organization that the bottom realizes.**

This is the meaning of organizing causal priority.

### 2. Statistical Mechanics Defines the Top

At boundary $B_n$, let

$$
\mathfrak M_n
$$

be the domain of compatible formal microstates.

The boundary defines its macrostate classification:

$$
\boxed{
\pi_n:\mathfrak M_n\rightarrow\mathcal M_n.
}
$$

For macrostate $i$,

$$
\boxed{
W_{n,i}=|\pi_n^{-1}(i)|.
}
$$

The compatible microstates belonging to that macrostate are

$$
F_{n,i}=\pi_n^{-1}(i).
$$

The logarithmic multiplicity coordinate is

$$
S_{n,i}=\ln W_{n,i}.
$$

These relations define a macrostate through its compatible multiplicity.

They do not require a microscopic trajectory, a probability distribution, or a physical rate.

Crucially, the macrostate is not one particular formal microstate.

It is the boundary-defined classification of compatible possibilities.

The individual possibilities are therefore not additional readable macrostates of the same enclosing boundary.

That distinction has an immediate mathematical consequence.

### 3. Theorem 1 — The Measurable Top Does Not Uniquely Determine Its Microstate

**Statement.**

For a macrostate with $W_{n,i}>1$, observing its enclosing macrostate label alone does not uniquely identify which compatible microstate was realized. The nonuniqueness conclusion applies to nontrivial fibers; the boundary ownership of state and transition identity does not require every fiber to have multiplicity greater than one.

**Proof.**

Let

$$
W_{n,i}>1.
$$

Then at least two distinct formal microstates exist:

$$
\mu_1\neq\mu_2,
$$

with

$$
\pi_n(\mu_1)=\pi_n(\mu_2)=i.
$$

Both distinct microstates have the same observed image $i$. The label $i$ therefore leaves at least two realizations compatible with the observation.

A single-valued selection map $r(i)$ could choose one representative of the fiber, but its choice would introduce information not supplied by the observation and would not identify which compatible microstate was actually realized. Consequently, the observation does not define a unique inverse of the enclosing classification on this fiber.

Therefore,

$$
\boxed{
W_{n,i}>1
\Longrightarrow
\pi_n^{-1}(i)
\text{ is not uniquely recoverable from }i.
}
$$

The enclosing state is measurable without separately measuring the identity of the subordinate realization.

This is not a limitation of instrumentation.

It follows from the mathematical definition of the enclosing macrostate.

**Q.E.D.**

### 4. Theorem 2 — Resolving the Bottom Replaces the Operative State Identity

Suppose an enclosing boundary observes macrostate $i$, with multiplicity

$$
W_{n,i}>1.
$$

To resolve a particular formal microstate $\mu$, a measurement must distinguish members of

$$
F_{n,i}.
$$

Let $\pi_{\mathrm{res}}$ denote such a resolving classification, distinct from the R²D recurrence ratio $\rho_{n+1\mid n,a}$.

Where

$$
\pi_n(\mu_1)=\pi_n(\mu_2),
$$

a complete resolving read distinguishes

$$
\pi_{\mathrm{res}}(\mu_1)\neq\pi_{\mathrm{res}}(\mu_2).
$$

Therefore, $\pi_{\mathrm{res}}$ and $\pi_n$ cannot be the same operative classification.

$$
\boxed{
\text{Resolution of a microstate}
\Longrightarrow
\text{change of operative read classification}.
}
$$

In R²D, the resolved distinctions acquire their native measurable identities at the appropriate subordinate boundary.

The result is not merely a sharper image of an unchanged enclosing state.

The measurable state identity has changed.

Part I establishes the corresponding recursive nonidentity:

$$
\boxed{
\mu_n\not\equiv\mu_{n+1}.
}
$$

Likewise, multiplicities at adjacent boundaries count different boundary-defined possibilities:

$$
\boxed{
W_{n,i}\not\equiv W_{n+1,j}
}
$$

as count objects, even when their numerical values happen to agree.

This is **recursive replacement**.

The subordinate processes do not have to disappear. Their former state identities simply do not remain the operative measurable identities of the enclosing boundary.

**Q.E.D.**

### 5. Theorem 3 — The Top Defines Its Own Measurable Transitions

Let $\mu$ and $\mu'$ be compatible realizations.

At boundary $B_n$, their macrostate classifications are

$$
i=\pi_n(\mu),
\qquad
j=\pi_n(\mu').
$$

A measurable macrostate change occurs at $B_n$ when

$$
\boxed{
\pi_n(\mu)\neq\pi_n(\mu').
}
$$

If instead

$$
\pi_n(\mu)=\pi_n(\mu'),
$$

the subordinate realization may change without any change in the enclosing macrostate.

For example, consider

$$
HT\rightarrow TH.
$$

At a boundary that counts heads,

$$
1\rightarrow1.
$$

There is no macrostate transition.

At a boundary that distinguishes the state of the first coin,

$$
H\rightarrow T.
$$

A transition is readable.

The same subordinate difference has different state meaning under different boundaries.

Therefore, the subordinate change alone does not determine which observable transition occurred.

The enclosing classification is necessary.

$$
\boxed{
\text{The measurable transition identity at }B_n
\text{ is defined by }B_n.
}
$$

The top does not inherit its transition classification from a subordinate ruler.

**Q.E.D.**

### 6. Theorem 4 — The Top Defines Compatible Subordinate Realizations

For any enclosing macrostate $i$, the compatible subordinate formal microstates belong to

$$
\boxed{
F_{n,i}=\pi_n^{-1}(i).
}
$$

The class is defined by the enclosing boundary.

For two different enclosing macrostates $i\neq j$,

$$
\boxed{
F_{n,i}\cap F_{n,j}=\varnothing.
}
$$

Thus, changing the enclosing macrostate changes the compatible realization class.

At the level of enclosing occurrences, Part I establishes

$$
\boxed{
\chi_{n+1}^{(r)}
\Longrightarrow
(\mathcal C_{n,a})_{a\in I_n}
\in\mathfrak D_{n+1,\chi}.
}
$$

The enclosing occurrence determines the compatible joint peer-closure class.

This is a class of realizations, not necessarily one uniquely specified subordinate configuration.

The distinction is essential.

Top-down organization does not require the enclosure to identify which individual subordinate peer supplies every realization.

It requires the enclosure to define which joint subordinate realizations are compatible with its state and transition.

That relation is mathematically defined before any particular compatible realization is selected.

**The top defines what the bottom is realizing.**

The bottom does not independently define the compatible class to which its realization belongs.

**Q.E.D.**

### 7. Theorem 5 — Enclosing Compatibility Determines Directional Possible-Count Support

The preceding theorems establish state identity, transition identity, and compatibility.

The coin construction establishes the corresponding directional count relation.

For a selected peer boundary, let

$$
W_{n,i}
$$

be its native macrostate multiplicity.

Let

$$
\Theta_{n+1\mid n,i}
$$

be the number of compatible enclosing realizations associated with local macrostate $i$.

Define compatible extension multiplicity:

$$
K_{n+1\mid n,i}
=
\frac{\Theta_{n+1\mid n,i}}{W_{n,i}}.
$$

Its logarithmic possibility is

$$
P_{n,i}=\ln K_{n+1\mid n,i}.
$$

For a local transition $i\rightarrow k$,

$$
\Delta S
=
\ln\frac{W_{n,k}}{W_{n,i}},
$$

and

$$
\Delta P
=
\ln\frac{K_{n+1\mid n,k}}{K_{n+1\mid n,i}}.
$$

Therefore,

$$
\boxed{
\Delta S+\Delta P
=
\ln
\frac{\Theta_{n+1\mid n,k}}
{\Theta_{n+1\mid n,i}}.
}
$$

The complete directional possible-count support depends on enclosing compatibility.

The native multiplicity landscape alone does not determine it.

#### Exact coin demonstration

Let $B_n$ be an ensemble of ten binary switches.

Its native multiplicity is

$$
W_{n,i}=\binom{10}{i}.
$$

Now let $B_{n+1}$ enclose ten already-defined $B_n$ landscapes and distinguish their total tail count $J$.

For one selected ten-switch peer,

$$
\boxed{
\Theta_{n+1\mid n,i}^{(J)}
=
\binom{10}{i}\binom{90}{J-i}.
}
$$

The ninety-switch binomial factor is the closed-form evaluation of compatible compositions of the other nine ten-switch landscapes. It does not restore ninety individually readable primitive coins at the enclosing boundary.

Take

$$
J=60
$$

and compare

$$
i=5\rightarrow6.
$$

The native multiplicity relation is

$$
\Delta S=\ln\frac56<0.
$$

The enclosing possibility relation is

$$
\Delta P=\ln\frac{55}{36}>0.
$$

Therefore,

$$
\boxed{
\Delta S+\Delta P
=
\ln\frac{275}{216}>0.
}
$$

Native multiplicity favors five tails.

The enclosing-compatible count favors six.

Nothing about the native ten-switch multiplicity has changed.

The reversal results entirely from the enclosing compatibility relation.

For another enclosing state, $J=40$, the corresponding complete ratio is

$$
\boxed{
\frac{\Theta_{n+1\mid n,6}^{(40)}}
{\Theta_{n+1\mid n,5}^{(40)}}
=
\frac{175}{336}<1.
}
$$

Thus the same native subordinate landscape supports opposite relative directions under two different enclosing conditions.

This is an exact mathematical demonstration that **the bottom's native multiplicity does not independently determine the directional support of its enclosing-compatible realization**.

The enclosure does.

**Q.E.D.**

### 8. Theorem 6 — Subordinate Realization Does Not Create Enclosing Multiplicity

Let

$$
W_{n,i}=|\pi_n^{-1}(i)|.
$$

While the boundary and its compatibility classification remain fixed, this number does not depend on which member of the fiber is realized.

If one subordinate state changes, the realized configuration may change.

The enclosing macrostate may also change.

But the defining multiplicities remain:

$$
W_{n,i}=|\pi_n^{-1}(i)|.
$$

Therefore,

$$
\boxed{
\text{Subordinate realization}
\neq
\text{creation of enclosing multiplicity}.
}
$$

The compatible possibility landscape is defined by the enclosing boundary, not generated anew by each realized subordinate transition.

This result is central to the causal interpretation.

The microscopic event can be a necessary realization of the enclosing state without being the primitive cause of the count structure that defines it.

**Q.E.D.**

### 9. Main Theorem — Top-Down Organizing Causality

**Theorem.**

For an operative, physically realized enclosing boundary satisfying the boundary-indexed statistical-mechanical architecture of Part I, organizing causal priority belongs to the enclosing relation rather than to independently retained subordinate measurable state identities.

**Proof.**

From Theorem 1, when $W_{n,i}>1$, the enclosing macrostate label cannot uniquely identify its compatible subordinate microstate. This nonuniqueness is a special case; enclosing ownership of state, transition, and compatibility relations also holds for singleton fibers.

From Theorem 2, where a nontrivial fiber is resolved, distinguishing its members requires a different operative read and therefore a different measurable state identity.

From Theorem 3, the enclosing boundary defines which differences constitute its own readable macrostate transitions.

From Theorem 4, the enclosing boundary defines the classes of subordinate realizations compatible with its states and occurrences.

From Theorem 5, enclosing compatibility determines the complete directional possible-count support, which can oppose the native subordinate multiplicity preference.

From Theorem 6, subordinate realization changes which possibilities are realized without creating the enclosing multiplicity landscape.

The distinction between organizing possibility and realized occupancy is also quantitative in Part I. For a readable local macrostate transition $i\rightarrow k$ at $B_n$, with positive counts so that the logarithmic coordinates are defined, the **occupancy-realization postulate** gives

$$
\boxed{
\begin{aligned}
\Delta G_{n,i\rightarrow k}
&=\Delta\tau_{n,i\rightarrow k}+\Delta A_{n,i\rightarrow k}\\
&=\Delta\tau_{n,i\rightarrow k}
 +\Delta P_{n,i\rightarrow k}
 -\Delta R_{n,i\rightarrow k}.
\end{aligned}
}
$$

Here $\Delta\tau$ is the logarithmic difference in realized local microstate-occurrence counts, $\Delta P$ comes from compatible enclosing extension, and $\Delta R$ reads productive retention under enclosing constraint. Thus subordinate occurrence is necessary to realize occupancy, while its native occurrence relation does not independently define the enclosing-compatible possibility and retention that organize occupancy. The equality is an R²D realization **postulate**, not a new theorem of coin combinatorics.

Separately, for a completed representative local closure $\mathcal C_{n,a}$ and its enclosing occurrence class $\chi_{n+1}$, the canonical **recurrence-weighted R²D law** states

$$
\boxed{
\Delta A_{n,a,\mathcal C}
N_{\mathcal D_R}(\mathcal C_{n,a})
=
C_{n+1}\lambda_{n+1}
N_{\mathcal D_R}(\chi_{n+1}).
}
$$

For a positive local closure recurrence count, this is equivalently

$$
\boxed{
\Delta A_{n,a,\mathcal C}
=C_{n+1}\lambda_{n+1}\rho_{n+1\mid n,a}.
}
$$

This is a further R²D realization **postulate** relating two boundary-specific recurrence-weighted readings. The closure asymmetry $\Delta A_{n,a,\mathcal C}$ in this equation should not be silently identified with the single-transition asymmetry $\Delta A_{n,i\rightarrow k}$ in the occupancy relation above. The two laws connect realized local change to enclosing organization while retaining their distinct count types and boundary roles.

Suppose, nevertheless, that subordinate states possess independent primitive organizing causal priority over the enclosing state.

They would then have to define, without the enclosing relation, the observable enclosing state identity, its transition distinctions, and the compatible multiplicity governing its directional support.

But the foregoing theorems establish that these mathematical relationships are defined by the enclosure, and that native subordinate multiplicity alone cannot determine the enclosing-compatible directional relation.

The claimed independent subordinate organizing sufficiency is therefore incompatible with the established count architecture.

The subordinate processes remain necessary realizations. Their physical occurrence is not denied.

What is excluded is the assignment of primitive organizing causal agency to subordinate state identities that do not define the measurable enclosing relation.

Therefore,

$$
\boxed{
\begin{gathered}
\text{Physically realized enclosing state}\\
\Downarrow\\
\text{Enclosing-defined measurable identity}\\
\Downarrow\\
\text{Enclosing-defined transitions and compatibility}\\
\Downarrow\\
\text{Enclosing-defined directional possibility}\\
\Downarrow\\
\text{Compatible subordinate realization}.
\end{gathered}
}
$$

This is **top-down organizing causality**.

It is established as a formal theorem within R²D's boundary-indexed causal architecture.

It does not assert that the enclosing boundary mechanically performs every subordinate transition. It identifies the origin of the organization those transitions realize.

**Q.E.D.**

### 10. The Observational Inversion — Creating the Bottom and Reconstructing the Top

Consider an enclosing ten-coin macrostate:

$$
i=5.
$$

Its multiplicity is

$$
\boxed{
W_{n,5}=\binom{10}{5}=252.
}
$$

At $B_n$, the measurable state is the five-tail macrostate.

Its compatible formal microstates constitute its multiplicity.

Now change the read boundary to resolve one particular configuration:

$$
\mu=(H,T,H,T,H,T,H,T,H,T).
$$

The newly resolved read distinguishes one configuration.

Under that fully resolved classification,

$$
W_{\mathrm{resolved}}=1.
$$

These are not two multiplicities simultaneously assigned to the same unchanged occupied count identity.

The enclosing state had one meaning:

$$
i=5,\qquad W_{n,5}=252.
$$

The subordinate resolved state has another:

$$
\mu,\qquad W_{\mathrm{resolved}}=1.
$$

By changing the operative ruler, we have made the bottom measurable.

In that precise sense, **observation creates the measurable bottom**.

It does not create the material realization or imply that the enclosing physical organization must disappear.

It replaces the enclosing state identity as the operative identity of that particular read.

Now reconstruct the former enclosing label:

$$
\boxed{
\pi_n(\mu)=5.
}
$$

This is mathematically valid.

But it is a classification calculation.

It does not demonstrate that the resolved configuration independently generated the original enclosing state or its multiplicity.

The observational inversion occurs when this reconstruction is interpreted as causal construction:

$$
\text{resolved microstate}
\longrightarrow
\text{reconstructed macrostate}
$$

and then promoted to

$$
\text{resolved microstate}
\Longrightarrow
\text{primitive cause of macrostate}.
$$

The second expression does not follow from the first.

The correct logical relationship is that the enclosing classification defines which subordinate realizations belong to the state.

**Our capacity to reconstruct the top from the bottom does not make the bottom the cause of the top.**

### 11. What Is Real, and What Exists?

This distinction reveals an ambiguity in the word *real*.

One meaning is *physically existing*.

Another is *physically measurable*.

R²D requires these concepts to be distinguished.

At the enclosing boundary, subordinate recurrence can physically occur while its individual native state identity remains unreadable.

Therefore,

$$
\boxed{
\text{Existence of subordinate realization}
\not\Longrightarrow
\text{measurability of subordinate state identity at the enclosure}.
}
$$

If *real* means existing, subordinate processes may be real.

If *real* means measurable, their individual identities are not real as separate measurable states **at that enclosing boundary**.

They may become measurable at their own subordinate boundary.

That is a different operative state classification.

The distinction does not require choosing one scale as absolutely real and declaring all others nonexistent.

It requires stating which boundary makes a particular physical distinction measurable.

This also distinguishes R²D from a universal-ruler ontology.

A ruler capable of resolving one myosin motor cannot, by that same state classification, define the complete mechanical state of muscle.

Likewise, a muscle-scale mechanical ruler cannot individually identify the states and trajectories of its myosin motors.

The physical specimen can support both types of measurement. The measurements can be compared. But they do not constitute one unchanged primitive state description.

**Measurability belongs to a boundary. Existence is not equivalent to measurability at every boundary.**

### 12. Repeated Observation Converts Multiplicity into Apparent Randomness

Suppose an enclosing macrostate has multiplicity

$$
W_{n,i}>1.
$$

Repeated measurements at a resolving boundary may distinguish different compatible realizations:

$$
\mu^{(1)},\mu^{(2)},\ldots
$$

while

$$
\pi_n(\mu^{(r)})=i.
$$

The enclosing macrostate classification is unchanged.

The subordinate observations vary.

When the resolved configurations are treated as primitive state identities, their variations may be described as randomness, fluctuations, or noise.

These descriptions can be useful.

But the observations admit a more primitive count interpretation:

$$
\boxed{
\text{Different resolved configurations}
\in
\text{one enclosing compatibility fiber}.
}
$$

The variability need not represent independent disturbances of the enclosing organization. It can represent different compatible subordinate realizations of that organization.

Multiplicity and observed randomness must nevertheless remain distinct.

Multiplicity counts possible compatible realizations.

Repeated observations provide realized occurrence data.

Instrumental noise and disturbances can also contribute to observed variation.

The causal inversion occurs when the observed variation among subordinate realizations is promoted to the source of the enclosing multiplicity itself.

The enclosing compatibility relation is then omitted, and its subordinate consequences appear to be independently acting stochastic causes.

This is particularly important in biology.

At the muscle boundary, subordinate molecular dynamics can appear as fluctuations in an enclosing mechanical response.

Changing perturbation frequency can make faster subordinate recurrence directly readable.

The dynamics have not necessarily acquired new physical existence.

The operative ruler has changed.

What appeared as noise or fluctuation at one boundary may become a distinguishable native state transition at another.

### 13. Bernoulli–Laplace — A Realization Mechanism Is Not the Cause of Multiplicity

The Bernoulli–Laplace model provides a useful demonstration of the distinction between local realization and enclosing organizing causality.

Consider two groups containing 10 and 90 binary objects.

Let the combined system have 60 tails.

The enclosing macrostate is

$$
J=60,
$$

with multiplicity

$$
\boxed{
W_J=\binom{100}{60}.
}
$$

In the R²D recursive construction, this multiplicity is equivalently

$$
\boxed{
W_{n+1,J}
=
\sum_{\sum_{a=1}^{10}i_a=J}
\prod_{a=1}^{10}\binom{10}{i_a}.
}
$$

The closed-form binomial coefficient is obtained from compatible compositions of ten already-defined ten-coin landscapes.

It does not restore one hundred individually readable primitive coin states at the enclosing boundary.

Now perform a Bernoulli–Laplace exchange.

Select one object from each group and exchange their positions.

This operation can occur without first measuring their individual states.

The exchange changes the compatible joint configuration.

It may change the tail count $i$ of the selected ten-object group.

But the enclosing total remains

$$
\boxed{
J=60.
}
$$

Consequently,

$$
\boxed{
W_J=\binom{100}{60}
}
$$

remains unchanged.

The exchange has not created the enclosing multiplicity landscape.

It has realized a change within that landscape.

The model's local exchange weights are

$$
q_i^+=(10-i)(60-i)
$$

and

$$
q_i^-=i(30+i).
$$

For the transition between five and six tails,

$$
q_5^+=275,
$$

and

$$
q_6^-=216.
$$

The resulting stationary count ratio is

$$
\boxed{
\frac{p_6}{p_5}
=
\frac{275}{216}.
}
$$

This is exactly the ratio obtained from enclosing-compatible multiplicity:

$$
\frac{\Theta_{n+1\mid n,6}^{(60)}}
{\Theta_{n+1\mid n,5}^{(60)}}
=
\frac{275}{216}.
$$

The agreement does not establish that microscopic exchanges created the enclosing multiplicity.

Rather, it demonstrates that the exchange mechanism realizes compatible local changes under an already defined enclosing count relation.

The conserved total, group capacities, and compatibility constraints belong to the complete system description.

They are not generated by the independent identity of a selected coin.

Even where the exchange is the immediate mechanism by which a local configuration changes, it is not the organizing cause of the multiplicity landscape or the enclosing compatibility relation.

Thus,

$$
\boxed{
\text{Subordinate exchange}
=
\text{local realization within enclosing compatibility},
}
$$

not

$$
\text{subordinate exchange}
=
\text{creation of enclosing multiplicity}.
$$

Bernoulli–Laplace therefore illustrates a central R²D distinction:

**A mechanism can correctly describe how a transition is realized without identifying the primitive organizing cause of the state space in which that transition is defined.**

### 14. The Two Causal Interpretations

The mathematical and observational results expose two different assignments of causal priority.

In a primitive-object interpretation, one begins with subordinate state identities, reconstructs the enclosing state from them, and assigns the enclosing organization to their dynamics.

In R²D, one begins with the measurable enclosing state and its compatible multiplicity. Subordinate realizations are necessary, but they are not independently primitive state identities within the enclosing read.

The disagreement is not about whether physical molecular changes occur.

It concerns whether their identities can define the enclosing measurable organization independently of the enclosing boundary.

The preceding theorems establish that they cannot.

The enclosing boundary defines its measurable state.

It defines its measurable transitions.

It defines the compatible subordinate realization classes.

And its compatible multiplicity determines the relative directional count support.

A microscopic representation may reconstruct these same relationships. But reconstruction does not reverse their mathematical definitional order.

This is the observational inversion applied to causality.

The direction in which we reconstruct an explanation is not necessarily the direction in which its organizing count relation is defined.

### 15. The Top Is the Truth of the Top

The statement *if the top is observed, the top is the truth* can now be given a precise mathematical meaning.

When $B_{n+1}$ is the operative measurable boundary, its state belongs to

$$
\mathcal M_{n+1}.
$$

Its identity is specified by

$$
\pi_{n+1}.
$$

Its compatible multiplicity belongs to

$$
\mathfrak M_{n+1}.
$$

Its readable transitions belong to that same boundary-defined state architecture.

The subordinate realization is consequential but does not retain its own state identity as a simultaneously primitive coordinate of the enclosing read.

Thus,

$$
\boxed{
\text{If the top is defined,}
\quad
\text{the top defines what is measurable at the top}.
}
$$

This does not mean that $B_{n+1}$ is the largest possible boundary or the ultimate cause of its own state changes.

At a still larger boundary $B_{n+2}$, the state and transition relations of $B_{n+1}$ become subordinate.

The causal ordering remains recursive:

$$
\boxed{
B_{n+2}
\Longrightarrow
B_{n+1}
\Longrightarrow
B_n.
}
$$

Each boundary owns its native measurable states.

Each nonterminal boundary is organized through its enclosing compatibility and constraint relations.

No universal ruler is required to preserve the same primitive object identity across this hierarchy.

### 16. What Has Been Proven

The proofs in this addendum establish three central conclusions.

**1. The top replaces subordinate measurable state identity.**

A nontrivial enclosing macrostate cannot uniquely recover its microstates. Resolving those microstates requires a different classification and therefore a different operative count identity. Part I's boundary-state nonidentity theorem generalizes this replacement recursively.

**2. The top defines its own measurable transition organization.**

The enclosing boundary determines which state differences count as its transitions. Compatible enclosing multiplicity determines their directional possible-count support. The coin construction proves that this support can be reversed by changing the enclosing relation while leaving native subordinate multiplicity unchanged.

**3. The top defines the compatible subordinate realization classes of its states and occurrences.**

The subordinate processes through which the enclosing state is realized belong to classes defined by the enclosing relation. They do not independently create that relation or the multiplicity it counts.

The two canonical realization postulates make the same division explicit for occupancy and cross-boundary closure recurrence: local occurrence realizes change, while enclosing compatibility and constraint define the organizing count relations. Their use does not convert the exact combinatorial theorems into deductions of those postulates.

These results jointly establish:

$$
\boxed{
\textbf{Top-down organizing causal priority}.
}
$$

This is a mathematical result within the boundary-indexed architecture of R²D, grounded in the microstate–macrostate structure of statistical mechanics and demonstrated by exact finite counting.

Its meaning is specific: the primitive organization of measurable state identity, transition classification, and compatible possibility belongs to the enclosing boundary.

The theorem does not depend on assigning intention to the whole or introducing a new force.

It depends on respecting the mathematical meaning of the state being measured.

### 17. Conclusion — Observation Does Not Reverse Causation

A measurable enclosing macrostate is defined through compatible multiplicity.

Its subordinate realizations exist and may recur, but their individual state identities are not separately measurable under the enclosing ruler.

To resolve one, we change the operative read.

That change makes a subordinate state measurable through another classification.

We may then use the subordinate observation to reconstruct the original enclosing state.

But a valid reconstruction is not a demonstration of primitive causal priority.

The apparent bottom-up explanation arises when the reconstructed subordinate state is mistaken for the independent cause of the original enclosing organization.

Repeated measurements compound this error when variations among compatible realizations are interpreted as primitive randomness or noise, rather than being recognized as possible subordinate realizations of an enclosing count relation.

Bernoulli–Laplace illustrates the same inversion dynamically. Exchanging objects changes a realization, not the multiplicity landscape that defines its possibilities.

The mathematical results are therefore unambiguous:

$$
\boxed{
\begin{gathered}
\text{The top defines its measurable states.}\\
\text{The top defines its measurable transitions.}\\
\text{The top defines its compatible subordinate realizations.}
\end{gathered}
}
$$

**Together, these establish top-down organizing causality in R²D.**

The bottom exists. It realizes the top.

But the bottom does not independently define the measurable identity, transition structure, or compatibility landscape of the top.

The observational inversion is the mistake of treating the subordinate state recovered by measurement as though it had always been the independently primitive cause of the enclosing organization.

R²D exposes that inversion through the mathematics of statistical-mechanical statehood.

**If the top is observed, the top is the measurable truth at that boundary. The bottom is its compatible realization—not its independently primitive organizing cause.**
