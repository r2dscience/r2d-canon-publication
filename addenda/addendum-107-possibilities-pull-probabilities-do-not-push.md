---
r2d_id: addendum-107
title: Addendum 107 — Possibilities Pull; Probabilities Do Not Push
subtitle: Markov Statistics, Enclosing Counts, and the EP Projection of Causality
source_type: addendum
authority: addendum
review_status: authoritative
indexable: true
primitive_authority: false
addendum: 107
unit: addendum
integrated_in_publication_canon: true
ask_r2d_status: pending_separate_corpus_update
promotion_date: '2026-10-24'
canon_revision: '2026-10-24'
source_file: Addendum-107-Possibilities-Pull-Markov-Statistics-Draft(1).md
source_sha256: 87f497ee346634c7df3398a2bb58935e585efc4ae9bd06790e6df56b94440dbf
source_review_status: author_review_pending
source_format: author_supplied_markdown
current_text_source: author_supplied_markdown
promotion_basis: author_request_to_update_canon_2026-10-24
---

## Abstract

A Markov model assigns conditional transition weights to states. It does not define, through the occurrence of a transition, what those states are or how many compatible realizations each contains. In a boundary-indexed system, the classification of realizations, the compatible multiplicities, and the admissible transition classes are specified before a Markov transition can be given its count meaning.

This order is demonstrated exactly by the Bernoulli–Laplace exchange construction in Addendum 105. A fixed total of 60 tails distributed across groups of 10 and 90 defines an enclosing multiplicity landscape. Exchanges between the groups realize movements within that landscape. The Markov stationary ratio for the states with five and six tails in the first group is $275/216$, exactly the ratio of their enclosing-compatible counts. The exchange rule reproduces that ratio; the exchanges do not create the count relation.

The same distinction applies to Markov aggregation. Lumpability tests whether a transition kernel can be expressed as a Markov rule on an already specified partition. It supplies no primitive causal priority to the transitions over the partition required to state the test.

**Possibilities pull:** enclosing compatibility supplies directional possible-count support, subject to the relevant enclosing retention relation. **Probabilities do not push:** normalized transition weights describe conditional alternatives; they are not causal agents. Possibilities do not predict the future. They define compatible alternatives and directional support, not a future realized occurrence. An actual transition is a realized occurrence, not a consequence forced into existence by the probability assigned to it. Reversing these dependencies is an epiphenomenological (EP) projection error.

## 107.1. The Question Behind a Successful Markov Calculation

Suppose a system has readable states $i$ and $j$, and a Markov model correctly calculates how frequently transitions between them occur. It is tempting to say that the transition probabilities *cause* the system to move among those states, and that repeated local transitions *produce* the multiplicity landscape the model eventually samples.

The calculation does not establish either causal claim.

To specify a Markov calculation of these boundary-defined states one must already say:

1. which differences define states;
2. which realizations belong to each state;
3. which transitions are admissible; and
4. which count domain is being normalized to make a transition weight.

R²D assigns those distinctions to count boundaries. The Markov rule operates within the resulting state description. Addendum 103 proves that a classification partitions admissible subordinate transitions into ordered macrostate-transition classes. Addendum 104 shows that normalization represents a previously defined count relation. Addendum 105 proves that changing a subordinate realization does not create the enclosing multiplicity landscape in which it is classified.

The result developed here is direct: **the success of a Markov calculation cannot reverse the dependency on the state and compatibility structure needed to define it.**

## 107.2. State, Possibility, Probability, and Occurrence Are Different Count Types

At a selected boundary $B$, let $\mathfrak M_B$ be its compatible formal microstate domain, let $\mathcal M_B$ be its readable macrostate set, and let

$$
\pi_B:\mathfrak M_B\longrightarrow\mathcal M_B
$$

classify the former into the latter. For $i\in\mathcal M_B$, define the fiber and its native multiplicity by

$$
F_{B,i}=\pi_B^{-1}(i),
\qquad
W_{B,i}=|F_{B,i}|.
$$

The fibers and their cardinalities belong to the classification. Moving from one occupied realization to another does not change $W_{B,i}$ while this count boundary and classification remain fixed.

For a local alternative $i$ considered under a specified enclosing boundary, let $\Theta_i$ abbreviate the number of enclosing realizations compatible with $i$. This *enclosing-compatible count* need not equal the native local multiplicity $W_{B,i}$. Where both counts are positive, the logarithmic count difference

$$
\Delta s_{i\to j}^{\mathrm{enc}}
=\ln\frac{\Theta_j}{\Theta_i}
$$

describes the directional support of compatible possibility for this comparison. In the full R²D relation, productive enclosing retention must also be included: local asymmetry is the difference between possibility and retention, $\Delta A=\Delta P-\Delta R$. A possible-count advantage is an organizing relation, not a guarantee about the next realized event.

A normalized count fraction $\Theta_i/\sum_j\Theta_j$ is a representation of the specified possible counts. A Markov transition weight $K_{ij}$ is a conditional weight over specified admissible transitions. A realized occurrence is an event that actually happens. These quantities answer different questions and must not be substituted for one another.

| Quantity | What it reads | What it does not do |
| --- | --- | --- |
| $W_{B,i}$ | Compatible realizations in a native state fiber | Record how many have occurred |
| $\Theta_i$ | Compatible enclosing realizations of local alternative $i$ | Choose a particular future event |
| $K_{ij}$ | Conditional weight of a defined transition | Define the states or cause the count landscape |
| Realized occurrence | Which admissible transition took place | Retroactively create the possibilities that preceded it |

**Possibilities pull** means that enclosing compatibility organizes directional support among alternatives. It does not mean that a future event exerts a force on the present. **Probabilities do not push** means that normalized weights describe a relation over already specified alternatives. A weight does not perform an exchange.

## 107.3. The Transition-Kernel Dependency Theorem

**Premises.** Fix a boundary classification $\pi_B$ and its fibers $F_{B,i}$. Let $T_B\subseteq\mathfrak M_B\times\mathfrak M_B$ be a set of admissible formal transitions. Let $K(x,y)$ be a normalized, nonnegative transition kernel with support only on $T_B$:

$$
\sum_{y\in\mathfrak M_B}K(x,y)=1,
\qquad
K(x,y)>0\ \Longrightarrow\ (x,y)\in T_B.
$$

**Result.** The kernel describes conditional motion over an already defined microstate domain and its transition classes. No occurrence sampled from $K$ defines $\pi_B$, creates a fiber $F_{B,i}$, or changes its cardinality $W_{B,i}$ while the stipulated boundary remains fixed.

**Proof.** Each $x\in\mathfrak M_B$ has exactly one label $\pi_B(x)=i$. Thus every admissible pair $(x,y)$ has a unique ordered class

$$
T_{B,i\to j}=T_B\cap(F_{B,i}\times F_{B,j}),
\qquad
i=\pi_B(x),\quad j=\pi_B(y).
$$

The quantities $K(x,y)$ are assigned to pairs whose state membership and transition class are already defined. A sampled transition $(x,y)$ changes the realized pair and perhaps the occupied macrostate; it does not alter the map or the cardinalities of its fibers. The premises of the kernel therefore contain the state structure it would be asked to create. **Q.E.D.**

This theorem concerns organizing priority, not whether exchanges physically occur. If the operative boundary or classification changes, the resulting count relation must be evaluated under the new boundary. That change is not the creation of a fixed boundary's multiplicity by an exchange within it.

The Markov property,

$$
\Pr(X_{t+1}=y\mid X_t=x,X_{t-1},\ldots)
=\Pr(X_{t+1}=y\mid X_t=x),
$$

states a conditional sufficiency relation for this selected description. It does not remove the definitions of $x$, $y$, their admissibility, or the boundary at which they count as states.

## 107.4. The Exact $10+90$ Exchange Construction

Take the finite construction from Addendum 105. Divide 100 distinguishable binary objects into groups of 10 and 90. Fix the enclosing total at $J=60$ tails. Let $i$ be the number of tails in the ten-object group. The enclosing-compatible count associated with $i$ is

$$
\Theta_i^{(60)}
=\binom{10}{i}\binom{90}{60-i},
\qquad 0\le i\le 10.
$$

Summing over the mutually exclusive values of $i$ gives the fixed enclosing multiplicity:

$$
W_{J=60}=\sum_{i=0}^{10}\Theta_i^{(60)}
=\binom{100}{60}.
$$

Now choose one object from each group uniformly and exchange them. There are $10\cdot90=900$ ordered cross-group selections. The numbers of selections that increase or decrease $i$ are

$$
q_i^+=(10-i)(60-i),
\qquad
q_i^-=i(30+i).
$$

The Markov transition weights for this chosen exchange rule are

$$
K_{i,i+1}=\frac{q_i^+}{900},\qquad
K_{i,i-1}=\frac{q_i^-}{900},\qquad
K_{i,i}=1-\frac{q_i^++q_i^-}{900}.
$$

An exact adjacent-count identity gives

$$
\frac{\Theta_{i+1}^{(60)}}{\Theta_i^{(60)}}
=\frac{(10-i)(60-i)}{(i+1)(31+i)}
=\frac{q_i^+}{q_{i+1}^-}.
$$

Hence $\Theta_i^{(60)}q_i^+=\Theta_{i+1}^{(60)}q_{i+1}^-$. The exchange chain's stationary weights for this specified selection rule are

$$
p_i^*=\frac{\Theta_i^{(60)}}{\binom{100}{60}}.
$$

At five and six tails,

$$
q_5^+=275,\qquad q_6^-=216,
\qquad
\boxed{\frac{p_6^*}{p_5^*}
=\frac{\Theta_6^{(60)}}{\Theta_5^{(60)}}
=\frac{275}{216}.}
$$

The two calculations agree exactly. They do not run in opposite causal directions. The partition, conserved total, and compatible counts define the alternatives; the exchange rule describes realizations among them. Every exchange leaves $J=60$ and $W_{J=60}=\binom{100}{60}$ unchanged.

Nor does the count ratio announce the next event. At $i=5$ the same rule assigns

$$
K_{5,6}=\frac{275}{900},\qquad
K_{5,4}=\frac{175}{900},\qquad
K_{5,5}=\frac{450}{900}.
$$

Upward, downward, and unchanged group counts are all admissible. The ratio $275/216$ compares stationary weights of *states* five and six; $275/900$ weights a *particular next-step class* from state five. Equating the two would confuse possible-count structure, normalized transition weight, and realized occurrence.

There is no single exchange clock encoded in the count ratio. For $0<\varepsilon\le1$, the kernel

$$
K^{(\varepsilon)}=(1-\varepsilon)I+\varepsilon K
$$

retains the same stationary distribution $p^*$ while changing how often the exchange part of the rule runs. Since $p^*K=p^*$, one has $p^*K^{(\varepsilon)}=p^*$. Thus even the complete stationary state ratio does not specify the next realization or a unique local transition timescale.

## 107.5. What Lumpability Actually Establishes

Let $F_i$ be the fibers of an already specified partition $\pi$. A fine-state kernel $K$ is *lumpable with respect to this partition* when, for every source fiber $F_i$, target fiber $F_j$, and $x,x'\in F_i$,

$$
\sum_{y\in F_j}K(x,y)
=\sum_{y\in F_j}K(x',y).
$$

The common sum defines a coarse transition weight $Q_{ij}$. It ensures that the projected sequence of labels $I_t=\pi(X_t)$ has a Markov transition rule independent of which $x\in F_i$ was occupied. This is the classical lumpability condition. It explicitly contains the partition $F_i$ in every term. It neither defines those fibers from a realized exchange nor turns the exchange into the primitive cause of the classification. [Kemeny and Snell, *Finite Markov Chains*, Chapter VI, §6.3](https://link.springer.com/book/9780387901923).

The presence or absence of a Markov rule for the grouped labels is a statement about the closure of that particular transition description. It is not a referendum on whether the enclosing boundary defines the labels and their compatible counts. **Lumpability recovers a valid grouped transition calculation; it does not reverse the count dependency proved in §107.3.**

## 107.6. The Two EP Projection Errors

The first reversal takes a successful realization rule and promotes it to the creator of its own state space:

$$
\text{defined compatibility}
\longrightarrow
\text{admissible transitions}
\longrightarrow
\text{realized exchanges}
$$

is incorrectly read as

$$
\text{realized exchanges}
\longrightarrow
\text{creation of defining compatibility}.
$$

That is an EP projection of local mechanism into primitive organizing cause. The transition calculation remains correct; the reversed causal assignment does not follow from it.

The second reversal confuses a count of possible compatible extensions with knowledge of a particular future occurrence:

$$
\text{possible-count asymmetry}
\nRightarrow
\text{future realized history}.
$$

Possibilities pull by organizing directional support and the compatible class into which realization can occur. They do not foretell the realized future. Assigning future-predicting agency to possibility is an EP projection of realized occurrence back into the possible-count relation. Assigning pushing agency to the normalized probability makes the same mistake in a different coordinate. A probability describes conditional weights. It does not act on a system.

R²D keeps these statements together: the enclosing relation supplies possible-count organization; enclosing constraint supplies retention; subordinate recurrence realizes one of the admissible transitions. Its occupancy-realization law relates these distinct counts without identifying possibility, probability, and occurrence as one thing. Neither successful normalization nor a correct Markov chain licenses such an identification.

## 107.7. Result and Scope

This addendum establishes the following conclusions for the stated boundary and exchange construction:

1. A Markov transition rule depends on a defined state domain, classification, and admissible transitions.
2. The $10+90$ exchange rule reproduces the exact enclosing-compatible ratio $275/216$ while leaving the enclosing multiplicity unchanged.
3. Lumpability tests whether an already classified transition process retains a Markov rule after aggregation. It does not create the classification.
4. Possible-count orientation is distinct from normalized probability and from realized occurrence. Possibilities pull; probabilities do not push; possibilities do not predict the future.
5. Assigning a sampled transition or its normalized weight primitive causal priority over the compatibility relation it requires is an EP projection error.

A local Markov model remains an exact or useful description of transitions where its stated rule applies. The logical result concerns what that description presupposes and the causal priority that cannot be obtained by reversing the presupposition. The same audit applies when the local mathematics concerns reaction kinetics, molecular switches, populations, or other boundary-defined transitions: identify the state classification and compatible-count relation first; then identify which event the transition rule actually describes.

## Internal sources

- R²D Part I, §§2 and 5: boundary-indexed microstates, enclosing compatibility, and EP projection.
- R²D Addendum 103: classification of transitions and status of realization postulates.
- R²D Addendum 104: possible count, normalization, and logarithmic magnitude.
- R²D Addendum 105, §13: the exact Bernoulli–Laplace exchange construction and its enclosing count ratio.

## Mathematical reference

- John G. Kemeny and J. Laurie Snell, *Finite Markov Chains*, Chapter VI, §6.3, lumpability with respect to a partition. [Book record](https://link.springer.com/book/9780387901923).
