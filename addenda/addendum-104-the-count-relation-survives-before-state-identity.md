---
r2d_id: addendum-104
title: Addendum 104 — The Count Relation Survives Before State Identity
subtitle: Normalization, Logarithmic Magnitude, and Recursive Replacement
source_type: addendum
authority: addendum
primitive_authority: false
addendum: 104
unit: addendum
indexable: true
integrated_in_publication_canon: true
ask_r2d_status: pending_separate_corpus_update
source_format: author_supplied_markdown
source_file: Addendum 104.md
source_sha256: 616b940031d450e576510ac74707a2779991ca47e1d31b045c0ee3c2f5eea31d
source_canon_commit: 6c0059d32f3b1918f2d7fbdbc854e3d11477db6e
math_representation: LaTeX
review_status: authoritative
promotion_date: '2026-10-21'
---

# Addendum 104 — The Count Relation Survives Before State Identity

**Normalization, Logarithmic Magnitude, and Recursive Replacement**

## Abstract

Science routinely represents the same count structure through two mathematical operations. Normalization expresses each count relative to a defined total, producing relative frequencies or probabilities. Taking the logarithm expresses multiplicative count relationships as additive magnitudes and differences. Statistical mechanics, chemical thermodynamics, and information theory use both operations extensively.

These representations are related exactly. For positive counts $q_i$, with total $Z=\sum_i q_i$ and normalized weights $p_i=q_i/Z$,

$$
\ln q_i=\ln Z+\ln p_i.
$$

The logarithmic count of an alternative therefore separates into a common total magnitude and a relative coordinate. Comparing two alternatives eliminates the common magnitude:

$$
\ln\frac{p_k}{p_i}
=
\ln\frac{q_k}{q_i}.
$$

Normalization preserves relative count ratios but discards their absolute magnitude. Logarithmic differences preserve relative directional magnitude but likewise eliminate the common total. The complete logarithmic magnitude and the normalized distribution together reconstruct the count landscape.

Recursively Realized Distinguishability (R²D) assigns these mathematical operations a specific place in the recursive definition of states. A count boundary first defines compatible possible realizations and their multiplicities. Normalization and logarithms subsequently represent that count structure. When the operative count boundary changes, subordinate state identities are recursively replaced; their mathematical count consequences may nonetheless be retained in the newly defined enclosing multiplicity.

This addendum derives the exact relationships connecting native multiplicity, enclosing-compatible multiplicity, normalized weights, and logarithmic odds. It establishes the condition under which a normalized possibility distribution survives unchanged and shows why enclosing compatibility can transform logarithmic odds without altering the native local multiplicity landscape.

A standard entropy decomposition further demonstrates how the total logarithmic count can be represented through the normalized distribution among alternatives and the average logarithmic multiplicity within them. Chemical activities provide a related physical example in which standard-state normalization and logarithmic directional magnitude are combined.

The central result is that **recursive replacement preserves compatible-count relationships without requiring conservation of absolute entropy, probability, logarithmic odds, or subordinate state identity.**

---

## 104.1. Two Coordinate Systems Applied to One Count Structure

Let a boundary define a finite set of distinguishable alternatives

$$
i\in\mathcal M
$$

with positive possible counts

$$
q_i>0.
$$

The complete count domain has magnitude

$$
\boxed{
Z=\sum_i q_i.
}
$$

The counts exist mathematically before any normalization or logarithmic transformation is performed.

Two representations are immediately available.

### Normalization

Define

$$
\boxed{
p_i=\frac{q_i}{Z}.
}
$$

Then

$$
\sum_i p_i=1.
$$

Normalization expresses the relative distribution of counts across the alternatives.

When the underlying counts admit the relevant probabilistic interpretation, these normalized weights are probabilities. Otherwise, they remain normalized count fractions.

The normalization does not determine which alternatives exist, which realizations are compatible, or which counts belong to the total.

Those relationships must already have been specified.

### Logarithmic magnitude

Define

$$
\boxed{
s_i=\ln q_i.
}
$$

The logarithm converts multiplication of positive counts into addition:

$$
\ln(q_iq_j)=\ln q_i+\ln q_j.
$$

It also converts ratios into differences:

$$
\ln\frac{q_k}{q_i}=s_k-s_i.
$$

This makes logarithms natural coordinates for statistical mechanics, where compatible independent possibilities compose multiplicatively.

The two operations therefore answer different mathematical questions.

Normalization asks:

**What fraction of the defined total belongs to this alternative?**

The logarithm asks:

**What is the additive magnitude of this multiplicative count, or the directional difference between two counts?**

Neither operation creates the count structure being represented.

## 104.2. The Exact Relationship Between Normalization and Magnitude

Because

$$
p_i=\frac{q_i}{Z},
$$

we have

$$
q_i=Zp_i.
$$

Taking the logarithm gives

$$
\boxed{
s_i=\ln Z+\ln p_i.
}
$$

This is the fundamental normalization–magnitude identity.

A logarithmic count separates into two components:

$$
\underbrace{\ln Z}_{\text{total log magnitude}}
+
\underbrace{\ln p_i}_{\text{relative log weight}}.
$$

The first is common to the complete count domain.

The second distinguishes one alternative from another.

For two alternatives,

$$
s_k-s_i
=
\ln p_k-\ln p_i.
$$

Therefore,

$$
\boxed{
\ln\frac{q_k}{q_i}
=
\ln\frac{p_k}{p_i}.
}
$$

Normalization preserves every pairwise count ratio.

It also preserves the ordering of alternatives:

$$
q_k>q_i
\iff
p_k>p_i.
$$

Consequently, normalization contributes no additional directional term.

### Example — Equal Probabilities, Different Magnitudes

Consider two count landscapes:

$$
(q_1,q_2)=(2,6)
$$

and

$$
(q'_1,q'_2)=(200,600).
$$

Their normalized distributions are identical:

$$
(p_1,p_2)=(0.25,0.75).
$$

Their logarithmic odds are also identical:

$$
\ln\frac{q_2}{q_1}
=
\ln\frac{q'_2}{q'_1}
=
\ln3.
$$

But their total logarithmic magnitudes differ:

$$
\ln Z=\ln8
$$

and

$$
\ln Z'=\ln800.
$$

The normalized distribution does not distinguish the two count domains.

Neither does the logarithmic odds ratio.

This difference matters for R²D because absolute multiplicity is defined by the count boundary.

**Two boundaries may have identical normalized distributions and logarithmic odds without possessing the same multiplicity, state identities, or physical realization structure.**

### Principle — Relative Structure Does Not Determine Total Magnitude

Normalization removes one common multiplicative factor from a complete positive count vector.

To reconstruct the original count vector, the normalized distribution must be supplemented by its total count.

Equivalently, the complete logarithmic representation consists of the total log magnitude and a complete relative distribution.

This is an exact mathematical statement, independent of R²D.

## 104.3. Boltzmann and Shannon Entropy Are Related Through the Same Decomposition

Statistical mechanics provides a particularly informative example.

Let boundary $B_n$ define macrostate multiplicities

$$
W_{n,i}
$$

with total possible multiplicity

$$
\Theta_n=\sum_i W_{n,i}.
$$

Define the native logarithmic multiplicity

$$
S_{n,i}=\ln W_{n,i}.
$$

Under equal weighting of the formal microstates, the normalized macrostate possibility measure is

$$
p_{n,i}^{(W)}
=
\frac{W_{n,i}}{\Theta_n}.
$$

The Shannon entropy of this distribution is

$$
H(p)
=
-\sum_i p_{n,i}^{(W)}
\ln p_{n,i}^{(W)}.
$$

Substituting the normalized multiplicity,

$$
H(p)
=
-\sum_i p_{n,i}^{(W)}
\left(
\ln W_{n,i}-\ln\Theta_n
\right).
$$

Because

$$
\sum_i p_{n,i}^{(W)}=1,
$$

we obtain

$$
H(p)
=
\ln\Theta_n
-
\sum_i p_{n,i}^{(W)}S_{n,i}.
$$

Therefore,

$$
\boxed{
\ln\Theta_n
=
H(p)
+
\sum_i p_{n,i}^{(W)}S_{n,i}.
}
$$

This is a standard entropy decomposition.

It separates the logarithmic multiplicity of the complete count domain into two contributions.

The first,

$$
H(p),
$$

represents the uncertainty of the normalized distribution among distinguishable macrostate alternatives.

The second,

$$
\sum_i p_{n,i}^{(W)}S_{n,i},
$$

represents the average logarithmic multiplicity within those macrostate classes.

Their sum reconstructs the logarithmic magnitude of the full formal microstate domain.

This identity explains why Boltzmann and Shannon entropy are closely related without being interchangeable in every application.

Boltzmann's macrostate entropy describes multiplicity within one specified class.

Shannon entropy describes a normalized distribution over alternatives.

The total entropy decomposition requires both the macrostate partition and the specified weighting of its formal microstates.

It does not follow from the numerical value of Shannon entropy alone that the complete microstate multiplicity can be reconstructed.

**The count domain comes first. The two entropy coordinates express different aspects of its already-defined organization.**

## 104.4. Recursive Replacement Changes the Count Domain

In R²D, the formal microstate domain at boundary $B_n$ is

$$
\mathfrak M_n
\subseteq
\prod_{a\in I_{n-1}}\mathfrak X_{n-1,a}.
$$

The boundary defines its compatible joint realizations and their macrostate classification:

$$
\pi_n:\mathfrak M_n\rightarrow\mathcal M_n.
$$

At the immediately enclosing boundary $B_{n+1}$, a new count domain and classification are defined.

Its state identities are not identical to the subordinate state identities:

$$
\boxed{
\mu_n\not\equiv\mu_{n+1}.
}
$$

Recursive replacement is therefore stronger than ordinary coarse-graining.

An enclosing occupied state is not simply a subordinate occupied state with some of its labels concealed.

The operative count identity has changed.

The subordinate possibilities may remain consequential to the multiplicity of the enclosing state. But that contribution does not require the subordinate states to remain independently occupied primitive objects.

This creates a precise mathematical question.

If subordinate state identities do not persist, how can their multiplicities contribute to the enclosing count?

Part I answers through compatible composition.

The answer does not require a persistent object identity.

It requires an enclosing-defined compatibility relation.

## 104.5. The Exact Reconstruction of Enclosing Logarithmic Magnitude

Consider one specified enclosing macrostate

$$
J\in\mathcal M_{n+1}.
$$

Select one subordinate peer at $B_n$, with local alternatives $i$.

Let

$$
W_{n,i}
$$

be its native multiplicity.

Let

$$
\Theta_{n+1|n,i}^{(J)}
$$

be the number of enclosing formal microstates compatible with local alternative $i$ and enclosing macrostate $J$.

Define the mean compatible enclosing extension factor

$$
K_{n+1|n,i}^{(J)}
=
\frac{\Theta_{n+1|n,i}^{(J)}}{W_{n,i}},
$$

and the possibility coordinate

$$
P_{n,i}^{(J)}
=
\ln K_{n+1|n,i}^{(J)}.
$$

Then

$$
\boxed{
\Theta_{n+1|n,i}^{(J)}
=
W_{n,i}e^{P_{n,i}^{(J)}}.
}
$$

Assume the conditional compatibility classes associated with the selected peer form an exhaustive, mutually exclusive partition of the enclosing macrostate's formal possibility domain.

Under that condition, Part I's multiplicity reconstruction theorem gives

$$
\boxed{
W_{n+1,J}
=
\sum_i W_{n,i}e^{P_{n,i}^{(J)}}.
}
$$

Every term in this sum is an enclosing-compatible multiplicity.

The subordinate index identifies the compatibility class used for formal counting. It does not imply that the enclosing occurrence simultaneously retains every subordinate alternative as an occupied state.

Now define

$$
S_{n,i}=\ln W_{n,i}
$$

and

$$
S_{n+1,J}=\ln W_{n+1,J}.
$$

Then

$$
\boxed{
S_{n+1,J}
=
\ln
\left[
\sum_i e^{S_{n,i}+P_{n,i}^{(J)}}
\right].
}
$$

The logarithm of a sum of exponentials is the exact mathematical coordinate of the reconstructed enclosing multiplicity.

It is not generally equal to one subordinate log multiplicity, nor to a sum of all subordinate logarithmic magnitudes.

The enclosing compatibility relation determines which multiplicative contributions are admitted and which mutually exclusive alternatives are summed.

This expression is a logarithmic reformulation of the existing Part I reconstruction theorem, not an additional physical postulate.

### Principle — Enclosing Magnitude Is Reconstructed, Not Carried Unchanged

The new boundary's logarithmic multiplicity is calculated from its compatible realization classes.

Its numerical value need not equal the magnitude of any subordinate state.

Its computation does not preserve subordinate occupied state identity.

**Compatible count consequences survive as part of a newly defined enclosing count.**

## 104.6. Normalized Enclosing Weights and Logarithmic Odds

For the same exhaustive, disjoint compatibility partition, define

$$
\boxed{
p_{n,i}^{(J)}
=
\frac{\Theta_{n+1|n,i}^{(J)}}{W_{n+1,J}}.
}
$$

This is a normalized possible-count weight.

It is defined mathematically relative to the selected subordinate classification and fixed enclosing macrostate $J$. Its use does not assert that this subordinate label remains independently readable or occupied at $B_{n+1}$.

Substituting the compatible-count relation gives

$$
p_{n,i}^{(J)}
=
\frac{W_{n,i}e^{P_{n,i}^{(J)}}}
{W_{n+1,J}}.
$$

Taking the logarithm,

$$
\boxed{
\ln p_{n,i}^{(J)}
=
S_{n,i}
+
P_{n,i}^{(J)}
-
S_{n+1,J}.
}
$$

This is the normalization–magnitude identity expressed across recursive boundaries.

The three terms have distinct roles.

$$
S_{n,i}
$$

is native local logarithmic multiplicity.

$$
P_{n,i}^{(J)}
$$

is the logarithmic extension into enclosing compatibility.

$$
S_{n+1,J}
$$

is the common enclosing normalization magnitude.

Now compare two local alternatives $i$ and $k$.

Subtracting their logarithmic normalized weights eliminates the common enclosing magnitude:

$$
\boxed{
\ln
\frac{p_{n,k}^{(J)}}{p_{n,i}^{(J)}}
=
\Delta S_{n,i\rightarrow k}
+
\Delta P_{n,i\rightarrow k}^{(J)}.
}
$$

This is exactly Part I's directional enclosing-multiplicity identity in normalized logarithmic coordinates.

It demonstrates that logarithmic odds are a representation of the same relative compatible-count relationship.

Normalization does not create the directional difference.

The directional difference already exists in the enclosing-compatible multiplicities.

### Enclosing Entropy Decomposition

The normalization–magnitude relationship can be extended using the entropy decomposition of Section 104.3.

Because

$$
\ln\Theta_{n+1|n,i}^{(J)}
=
S_{n,i}+P_{n,i}^{(J)},
$$

the Shannon entropy of the conditional possibility distribution satisfies

$$
H[p^{(J)}]
=
S_{n+1,J}
-
\sum_i p_{n,i}^{(J)}
\left(S_{n,i}+P_{n,i}^{(J)}\right).
$$

Therefore,

$$
\boxed{
S_{n+1,J}
=
H[p^{(J)}]
+
\sum_i p_{n,i}^{(J)}
\left(S_{n,i}+P_{n,i}^{(J)}\right).
}
$$

This is an exact identity for the specified finite count partition.

It states that the enclosing logarithmic multiplicity can be decomposed into:

1. The Shannon entropy of the normalized enclosing-compatible alternatives.
2. The average logarithmic multiplicity associated with those alternatives.

The first describes the relative distribution of the compatibility classes.

The second describes their internal compatible-count magnitudes.

Together they reconstruct the complete enclosing log count.

This is not an additional conservation law.

It is a decomposition of the enclosing count that has already been defined.

## 104.7. The Exact Condition for Preserving Normalized Weights

We can now ask whether the native local probability distribution survives enclosing compatibility unchanged.

Define the native normalized possible-count weights

$$
p_{n,i}^{(W)}
=
\frac{W_{n,i}}{\Theta_n},
$$

where

$$
\Theta_n=\sum_iW_{n,i}.
$$

The enclosing-compatible weights are

$$
p_{n,i}^{(J)}
=
\frac{W_{n,i}K_i^{(J)}}
{\sum_jW_{n,j}K_j^{(J)}}.
$$

Substituting the native normalized weights,

$$
\boxed{
p_{n,i}^{(J)}
=
\frac{
p_{n,i}^{(W)}K_i^{(J)}
}{
\sum_j p_{n,j}^{(W)}K_j^{(J)}
}.
}
$$

This is an exact multiplicative reweighting identity.

### Theorem — Uniform Extension Preserves Normalized Possible-Count Structure

Assume every local alternative included in the comparison has positive native multiplicity and positive compatible extension.

Then

$$
\boxed{
p_{n,i}^{(J)}
=
p_{n,i}^{(W)}
\quad\text{for every }i
}
$$

if and only if

$$
\boxed{
K_i^{(J)}=K
\quad\text{for every }i.
}
$$

**Proof**

If every extension factor equals $K$,

$$
p_{n,i}^{(J)}
=
\frac{W_{n,i}K}{\sum_jW_{n,j}K}.
$$

The common factor cancels:

$$
p_{n,i}^{(J)}
=
\frac{W_{n,i}}{\Theta_n}
=
p_{n,i}^{(W)}.
$$

Conversely, suppose the normalized weights agree for every positive-weight alternative.

Then

$$
\frac{W_{n,i}K_i^{(J)}}{\sum_jW_{n,j}K_j^{(J)}}
=
\frac{W_{n,i}}{\Theta_n}.
$$

Canceling $W_{n,i}>0$ gives

$$
K_i^{(J)}
=
\frac{\sum_jW_{n,j}K_j^{(J)}}{\Theta_n},
$$

which is independent of $i$.

Therefore, every extension factor is equal.

The theorem is exact.

### Consequence for Logarithmic Odds

For two alternatives,

$$
\boxed{
\ln\frac{p_{n,k}^{(J)}}{p_{n,i}^{(J)}}
=
\ln\frac{p_{n,k}^{(W)}}{p_{n,i}^{(W)}}
+
\ln\frac{K_k^{(J)}}{K_i^{(J)}}.
}
$$

Hence,

$$
\boxed{
\text{enclosing log odds}
=
\text{native log odds}
+
\text{enclosing possibility difference}.
}
$$

Uniform extension preserves the original log odds.

Nonuniform extension changes them.

The exact change is

$$
\Delta P_{n,i\rightarrow k}^{(J)}.
$$

Thus the numerical invariance of normalized weights or logarithmic odds is conditional on enclosing compatibility.

It is not an automatic consequence of recursive replacement.

Even when the normalized weights remain identical, the absolute enclosing multiplicity and operative state identity may differ.

## 104.8. The Coin Example Demonstrates the Transformation

Consider ten binary coins at $B_n$.

Their native macrostate multiplicities are

$$
W_{n,i}=\binom{10}{i}.
$$

For the adjacent local alternatives

$$
5\rightarrow6,
$$

the native multiplicity ratio is

$$
\frac{W_6}{W_5}
=
\frac{210}{252}
=
\frac56.
$$

Therefore, the native logarithmic odds are

$$
\Delta S_{5\rightarrow6}
=
\ln\frac56
\approx-0.1823.
$$

Now let $B_{n+1}$ define a total enclosing count

$$
J=60
$$

across ten equivalent ten-coin landscapes.

The enclosing-compatible extension factor is

$$
K_i^{(60)}
=
\binom{90}{60-i}.
$$

Thus,

$$
\frac{K_6^{(60)}}{K_5^{(60)}}
=
\frac{55}{36}.
$$

The enclosing possibility difference is

$$
\Delta P_{5\rightarrow6}^{(60)}
=
\ln\frac{55}{36}
\approx0.4238.
$$

The enclosing-compatible logarithmic odds become

$$
\boxed{
\ln\frac{p_6^{(60)}}{p_5^{(60)}}
=
\ln\frac56
+
\ln\frac{55}{36}
=
\ln\frac{275}{216}.
}
$$

Therefore,

$$
\boxed{
\ln\frac{p_6^{(60)}}{p_5^{(60)}}
\approx0.2415>0.
}
$$

The native relative count favors state 5.

The enclosing-compatible relative count favors state 6.

Nothing about the native local binomial multiplicity landscape has changed.

The difference arises entirely from the enclosing compatibility relation.

This is the exact directional reversal developed in Part I, now expressed as a transformation of logarithmic odds.

The corresponding normalized weights over only the two alternatives 5 and 6 are

$$
p(6\mid\{5,6\},J=60)
=
\frac{275}{275+216}
\approx0.560.
$$

For comparison, the native normalized weight over those same two alternatives is

$$
p_n(6\mid\{5,6\})
=
\frac{210}{252+210}
\approx0.455.
$$

The original local alternatives and their native multiplicities have not changed.

But their enclosing-compatible relative weights have changed.

This is not evidence that a physical coin has acquired an independent directional force.

It is exact mathematical evidence that the enclosing classification changes the relative possible-count support of those alternatives.

Whether realized occupancy follows this transformation belongs to the separately stated R²D realization postulates.

## 104.9. Chemical Activity Uses the Same Mathematical Relationship

The distinction between normalization and logarithmic magnitude is already central to chemical thermodynamics.

For an ideal mixture, mole fractions are normalized composition coordinates:

$$
x_j=\frac{n_j}{\sum_k n_k}.
$$

Under the appropriate ideal-solution standard state, activity may be represented as

$$
a_j=x_j.
$$

For nonideal mixtures,

$$
a_j=\gamma_jx_j,
$$

where $\gamma_j$ is an activity coefficient.

Chemical activity is therefore a dimensionless thermodynamic coordinate referenced to a standard state. It is not generally identical to probability, nor must activities of different species sum to one.

The chemical potential is

$$
\boxed{
\mu_j
=
\mu_j^\circ+RT\ln a_j.
}
$$

For an ideal mixture,

$$
\mu_j-\mu_j^\circ
=
RT\ln x_j.
$$

For a nonideal mixture,

$$
\mu_j-\mu_j^\circ
=
RT\ln x_j+RT\ln\gamma_j.
$$

The logarithm converts multiplicative activity relationships into additive chemical-potential differences.

For a chemical reaction with stoichiometric coefficients $\nu_j$, define the reaction quotient

$$
Q_r=\prod_j a_j^{\nu_j}.
$$

Then

$$
\boxed{
\ln Q_r
=
\sum_j\nu_j\ln a_j.
}
$$

The familiar Gibbs relationship is

$$
\Delta_rG
=
\Delta_rG^\circ+RT\ln Q_r.
$$

Part II develops the R²D thermodynamic correspondence

$$
\boxed{
\Delta P-\Delta P^\circ
=
-\ln Q_r.
}
$$

This identifies the activity-dependent shift in reaction direction with a change in the enclosing possibility coordinate under the stated thermodynamic mapping.

The correspondence does not require probability to be a primitive causal agent.

Nor does it identify chemical activity directly with absolute multiplicity.

Rather, chemistry supplies a physical example of how a dimensionless reference coordinate and a logarithmic directional magnitude work together.

The reference condition determines the meaning of the activity.

The logarithm expresses its multiplicative relationship as an additive thermodynamic coordinate.

The reaction quotient then combines the activity coordinates of the participating species into one directional relation.

This is why chemical potential, statistical mechanics, and R²D possibility share closely related logarithmic mathematics.

Their physical meanings remain boundary- and model-specific.

## 104.10. What Actually Survives Recursive Replacement?

The preceding results permit a precise classification.

### Absolute logarithmic multiplicity

The native local quantity

$$
S_{n,i}=\ln W_{n,i}
$$

is defined at $B_n$.

The enclosing quantity

$$
S_{n+1,J}=\ln W_{n+1,J}
$$

is defined at $B_{n+1}$.

They need not be numerically equal.

The enclosing count is reconstructed through its own compatibility relation.

Therefore, **absolute logarithmic multiplicity is not a universally conserved numerical quantity across replacement**.

### Normalized probability

The native normalized possible-count distribution is

$$
p_{n,i}^{(W)}
=
\frac{W_{n,i}}{\Theta_n}.
$$

The enclosing-compatible distribution is

$$
p_{n,i}^{(J)}
=
\frac{W_{n,i}K_i^{(J)}}{\sum_jW_{n,j}K_j^{(J)}}.
$$

These distributions are identical only under the stated uniform-extension condition, assuming the same positive support.

Therefore, **normalized probability is not generally preserved across enclosing compatibility changes**.

### Logarithmic odds

The native logarithmic odds are

$$
\ln\frac{W_{n,k}}{W_{n,i}}.
$$

The enclosing-compatible logarithmic odds are

$$
\ln\frac{W_{n,k}}{W_{n,i}}
+
\ln\frac{K_k^{(J)}}{K_i^{(J)}}.
$$

The difference is exactly the enclosing possibility term.

Therefore, **logarithmic odds are not generally conserved, but their transformation is exactly determined by relative enclosing compatibility**.

### Subordinate state identity

R²D's recursive replacement axiom does not preserve subordinate occupied state identity as an independently primitive state at the enclosing boundary.

The compatibility reconstruction equations do not reverse that replacement.

The use of subordinate labels in a formal sum is not evidence that those subordinate state identities remain simultaneously occupied at the enclosing boundary.

Likewise, reconstructing the enclosing count does not reconstruct a unique realized subordinate trajectory.

### Compatible-count consequences

What remains is the exact relationship

$$
\boxed{
W_{n+1,J}
=
\sum_iW_{n,i}e^{P_{n,i}^{(J)}}.
}
$$

Together with

$$
\boxed{
\ln\frac{p_{n,k}^{(J)}}{p_{n,i}^{(J)}}
=
\Delta S+\Delta P.
}
$$

These equations reconstruct the new boundary's total possible-count magnitude and its relative compatible-count structure.

Their validity depends on the stated compatibility partition and positive-count conditions.

They do not imply that the entire subordinate state history is recoverable.

### Possibility, occurrence, and occupancy remain different counts

R²D distinguishes native multiplicity

$$
W_{n,i},
$$

realized occurrence count

$$
\nu_{n,i},
$$

and realized occupancy

$$
c_{n,i}.
$$

Each may be normalized, but these operations produce different distributions.

An exact normalized possibility distribution does not establish that realized occurrences or occupancy follow that distribution.

The R²D realization postulates separately connect these quantities.

Likewise, the recurrence-weighted R²D law

$$
\Delta A_{n,a,\mathcal C}
N_{\mathcal D_R}(\mathcal C_{n,a})
=
C_{n+1}\lambda_{n+1}
N_{\mathcal D_R}(\chi_{n+1})
$$

specifies an additional across-boundary recurrence relation.

That equality is a postulate.

It is not obtained merely by preserving logarithmic odds or normalizing multiplicities.

The distinction is essential: **exact static compatible-count reconstruction is not automatically a theorem of dynamically realized recursive recurrence**.

## 104.11. Logical Status

The results of this addendum have the following status.

| Result | Status |
|---|---|
| Normalization preserves relative count ratios | Elementary mathematical identity |
| Logarithms turn multiplicative count ratios into additive differences | Elementary mathematical identity |
| Total log magnitude plus a complete normalized distribution reconstructs the count vector | Exact mathematical identity |
| Boltzmann and Shannon entropy satisfy the stated count-partition decomposition | Standard entropy identity under equal formal microstate weighting |
| Enclosing multiplicity is the sum of disjoint compatible count contributions | Part I reconstruction theorem |
| Enclosing log magnitude has the stated log-sum-exp representation | Exact consequence of reconstruction |
| Enclosing log odds equal native log odds plus enclosing possibility difference | Exact consequence of the count definitions |
| Uniform extension preserves the normalized possible-count distribution | Exact conditional theorem |
| Nonuniform extension can reverse local directional count support | Exact combinatorial result |
| Changing the operative boundary replaces occupied subordinate state identity | R²D recursive replacement axiom |
| Realized occurrence and occupancy follow the stated asymmetry relations | R²D realization postulates |
| The recurrence-weighted R²D law relates completed local closure and enclosing occurrence | R²D postulate |
| The same mathematical architecture describes physical systems across scientific domains | Physical correspondence claim requiring appropriate calibration and validation |

The logarithmic and normalization identities are established mathematics.

The distinction introduced by R²D concerns what those identities represent when the mathematical objects being counted are defined recursively and replaced across boundaries.

No new mathematical operation is required.

The significance is their placement within the primitive architecture of count, compatibility, realization, and replacement.

## 104.12. Principles

**Principle 1 — Count Before Coordinate**

A boundary defines its count domain before its multiplicities are normalized or expressed logarithmically.

**Principle 2 — Normalization Preserves Relative Structure**

Normalization retains relative count ratios while eliminating the common total magnitude.

**Principle 3 — Logarithms Express Multiplicative Magnitude Additively**

Logarithmic magnitude converts compatible multiplication into addition and relative count ratios into directional differences.

**Principle 4 — Total Magnitude and Relative Distribution Are Complementary**

A complete positive count landscape can be reconstructed from its total magnitude and its complete normalized distribution.

**Principle 5 — Enclosing Compatibility Transforms Directional Ratios**

The exact difference between native and enclosing-compatible logarithmic odds is the enclosing possibility difference.

**Principle 6 — Uniform Extension Is the Exact Condition for Relative Preservation**

A common positive extension factor preserves normalized possible-count weights; unequal extension generally transforms them.

**Principle 7 — Compatible Count Reconstruction Does Not Preserve State Identity**

The mathematical contribution of subordinate possibilities can remain part of enclosing multiplicity after the operative subordinate state identities have been replaced.

**Principle 8 — Possible-Count Invariance Is Not Realization Invariance**

Exact compatible-count relationships do not independently establish corresponding occupancy or recurrence relationships. Those require R²D's realization postulates.

## 104.13. Conclusion — The Count Relation Survives Before State Identity

Normalization and logarithms are not independent sources of scientific organization.

They are complementary mathematical representations of count relationships already defined within a particular domain.

Normalization describes how a total count is distributed among alternatives.

The logarithm describes multiplicative count magnitude and directional relative differences.

Their relationship is exact:

$$
\boxed{
\ln q_i=\ln Z+\ln p_i.
}
$$

When R²D changes the operative count boundary, the domain of possible realizations and the identities of its distinguishable states also change.

The newly defined enclosing multiplicity is not obtained by retaining subordinate occupied objects as independent primitive constituents.

It is reconstructed through enclosing compatibility:

$$
\boxed{
S_{n+1,J}
=
\ln\sum_i e^{S_{n,i}+P_{n,i}^{(J)}}.
}
$$

The corresponding normalized directional relation is

$$
\boxed{
\ln\frac{p_{n,k}^{(J)}}{p_{n,i}^{(J)}}
=
\Delta S_{n,i\rightarrow k}
+
\Delta P_{n,i\rightarrow k}^{(J)}.
}
$$

These are two views of one boundary-defined compatible-count structure.

The first reconstructs its logarithmic magnitude.

The second reconstructs its relative directional organization.

Neither requires absolute log multiplicity, normalized probabilities, logarithmic odds, or subordinate occupied state identities to remain numerically or ontologically unchanged across boundaries.

What remains exact is the mathematical relationship by which the enclosing count structure is defined.

The result gives a precise meaning to a central principle of R²D:

**Recursive replacement does not preserve subordinate state identity. It preserves the compatible-count consequences through which the enclosing boundary defines new state identities and multiplicities.**

This is the mathematical sense in which a relation can survive even when the objects used to represent it have been replaced.
