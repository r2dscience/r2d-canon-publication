---
r2d_id: "addendum-123"
title: "Addendum 123 — Enclosing Possibility Before Model-Based Decision"
subtitle: "World Models, Complete Compatibility, Readability, and Local Agency"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 123
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-02"
---

# R²D Addendum 123 — Enclosing Possibility Before Model-Based Decision

*World Models, Complete Compatibility, Readability, and Local Agency*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 revision); Addenda 85–87, 103–108, and 120–121; revised Addendum 122  
**Companion work:** Addendum 124, *Enclosing Recurrence Before Competing Closure Counts*  
**Scope:** Finite enclosing-owned compatibility specifications; model-represented possibilities; deterministic goal-compatible decisions; contingent responses and boundary-readable environmental distinctions; the relation to R²D directional support and physical occurrence

## Abstract

A world model does not create the alternatives it represents. An operative physical environment already constrains which joint continuations of a vehicle, surrounding agents, and their surroundings are admissible. A model may identify, omit, duplicate, or falsely combine those alternatives. A controller uses its model's read to realize an action, but neither the computational decision nor its subordinate actuators define the enclosing physical possibility relation they attempt to represent.

Recursively Realized Distinguishability (R²D) supplies the prior mathematical distinction: an enclosing boundary determines its native joint realization domain, the compatibility of subordinate alternatives, and the multiplicities of readable states. Local realization may change what is occupied without constructing the landscape in which that occurrence is classified. A world-model controller provides a particularly explicit implementation of *reading possibilities in order to act*; a physical system need not make a microscopic decision for enclosing possibility to organize realization.

This addendum gives two exact finite results. First, with a fixed goal and complete observation-dependent response requirements, an initial action permits a goal-sustaining contingent realization if and only if every readable observation class admits a response common to all the environmental alternatives within that class. Where exactly one action meets this criterion, its selection is fixed for a controller that implements that requirement, without a stochastic transition rule. Second, two controllers can face the same physically admitted environmental alternatives and the same number of individually goal-compatible action–environment–response combinations, yet be forced to choose opposite initial actions because they distinguish the environment differently. **The complete compatibility relation and its operative readability, not the numerical count alone, determine admissibility of a decision.**

A one-stage finite example additionally exhibits a sign reversal in goal-compatible possibility counts when the enclosing traffic condition changes while the action repertoire remains fixed. This parallels the R²D coin construction, but a controller's goal-filtered scenario count is not automatically a canonical R²D enclosing multiplicity, and a deterministic selected action is not a structural occupancy ratio. The correspondence requires an independently justified native physical count mapping, including productive retention if an R²D occupancy claim is made. Successful multi-future planners illustrate the usefulness of representing enclosing-compatible alternatives; they do not by themselves uniquely verify R²D's physical causal ontology.

## 123.1. The question: what is already possible before a model chooses?

R²D begins with the boundary defining what is countable. For a finite boundary $B$, let $\mathfrak M_B$ be the native domain of compatible joint realizations, let $\pi_B:\mathfrak M_B\to\mathcal S_B$ classify readable states, and let

$$
\boxed{W_B(s)=|\pi_B^{-1}(s)|.}
$$

The native multiplicity is a possible count. It is not a count of modeled branches or of realized occurrences. A local event can realize one of the alternatives without creating the domain in which that event is classified. Changing the count boundary changes native identity; recursive carry is not persistence of the same subordinate state through several descriptions.

The world-model question must therefore be asked in the correct order:

1. Which joint realizations are compatible with the operative surroundings?
2. Which distinctions are readable by a physically implemented controller?
3. Which of the compatible realizations sustain its operative goal?
4. Which action is thereby available to the controller, and which does it actually realize?

The prospective vocabulary of planning does not change the first step. A pedestrian, signal, and approaching vehicle constrain possible continuations whether or not an autonomous vehicle represents them. **The model reads an already constrained physical situation; it does not bring its alternatives into existence.** Whether its representation captures *all* physically admissible possibilities is a separate mapping question.

This addendum concerns that comparison. It does not equate a self-driving vehicle with a primitive R²D boundary or introduce a controller's optimization policy as a physical realization postulate.

## 123.2. Three domains that must not be exchanged

Distinguish three finite objects.

**Physical enclosing compatibility.** Let $B$ admit a complete joint domain $\Gamma_B$. A schematic record may contain an initial action $a$, a surrounding-world realization $e$, a later local response $r$, and an outcome classification $s$:

$$
\Gamma_B\subseteq A\times E\times R\times S.
$$

These are *comparison labels for one enclosing relation*, not independent agents whose Cartesian product automatically supplies what is possible. The enclosing owner decides which tuples are admitted. Distinct comparison records are not necessarily distinct native R²D microstates; their native-identification map must also be supplied.

**World-model representation.** Let $\widehat\Gamma_M$ be the model's represented joint alternatives. There may be no one-to-one correspondence between its records and $\Gamma_B$. The model can omit a physical alternative, duplicate descriptions of one realization, or join locally plausible records into an enclosing-inadmissible combination. Addendum 122 shows that even agreement on target native images or counts does not prove agreement on enclosing compatibility.

**Goal-compatible continuation.** Let $S_*\subseteq S$ be the outcomes the controller is required to sustain. Define

$$
\Gamma_{B,*}=\{(a,e,r,s)\in\Gamma_B:s\in S_*\}.
$$

The complement $\Gamma_B\setminus\Gamma_{B,*}$ remains physically possible. A collision is not removed from the world by the controller's intention to avoid it. The goal is an **operative constraint on the controller's actions**: it identifies the continuations its realized policy must sustain. The goal's physical implementation belongs to the controller's organization. It is not, merely by being a goal, the productive-retention coordinate $\Delta R$ defined in Part I.

For clarity below, suppress the explicit outcome label and write $\Gamma_*\subseteq A\times E\times R$ for those complete action–environment–response comparisons satisfying the stated goal.

## 123.3. The finite decision without a stochastic transition law

Let $A$ be a finite set of initial actions, $E$ a finite set of possible environmental distinctions, and $R$ a finite set of subsequent responses. For each $a,e$, define the set of responses compatible with the goal:

$$
\mathcal R_*(a,e)=\{r\in R:(a,e,r)\in\Gamma_*\}.
$$

A controller need not observe the whole environmental state. Let

$$
 o:E\longrightarrow O
$$

be its actual readable observation classification. A contingent response rule is a function $f:O\to R$. Its value may depend on what the controller can read; it may not depend on distinctions that produce the same observation.

**Definition 1 — Goal-viable initial action.** An initial action $a\in A$ is viable for the stated enclosing condition, goal, and observation relation when

$$
\boxed{
\operatorname{Viable}_*(a;o)
\iff
\exists f:O\to R\;\forall e\in E:
(a,e,f(o(e)))\in\Gamma_*.
}
\tag{123.1}
$$

This is a condition on *complete compatible contingent realizations*. It contains no assigned probability of any environmental alternative and no Markov selection rule. It also does not claim that every physically operative controller requires a worst-case safety guarantee; that requirement is the particular goal adopted in this finite example.

**Theorem 1 — Complete contingent compatibility criterion.** For an initial action $a$, a goal-compatible contingent response rule exists if and only if

$$
\boxed{
\forall z\in o(E),\quad
\bigcap_{e\,:\,o(e)=z}\mathcal R_*(a,e)
\ne\varnothing.
}
\tag{123.2}
$$

**Proof.** Suppose a goal-compatible response rule $f$ exists. For each observed label $z$, the same response $f(z)$ must work for every $e$ yielding that label. Therefore $f(z)$ belongs to the displayed intersection. Conversely, if each intersection is nonempty, choose one member $r_z$ of each intersection and define $f(z)=r_z$ on the image of $o$. Then $(a,e,f(o(e)))\in\Gamma_*$ for every $e$. Values of $f$ outside $o(E)$ are irrelevant. $\square$

**Corollary 1.1 — Unique admissible initial decision.** If exactly one $a^*\in A$ satisfies Equation (123.2), any controller whose operative requirement is to select a goal-viable action must select $a^*$. This is deterministic *decision admissibility*. It is not a claim that R²D's count relations uniquely select every individual physical occurrence.

The theorem is finite logic. Its R²D significance is that the possibility of realizing a complete response is defined by **enclosing joint compatibility together with readable distinctions**, not by independent forecasts of each participating actor.

## 123.4. One-stage directional reversal under changing surroundings

Consider a vehicle with two initial actions,

$$
A=\{Y,G\},
$$

where $Y$ means Yield and $G$ means Go. Here no later contingent response is included, so $R$ is a singleton. A safe continuation is the declared goal; unsafe outcomes remain physically possible.

Specify two enclosing situations:

| Enclosing situation | Environmental alternative | Yield outcome | Go outcome |
|---|---|---|---|
| $H$: crossing pedestrian possible | Crossing remains clear | Safe | Safe |
| $H$ | Pedestrian enters crossing | Safe | Unsafe |
| $L$: close follower possible | Road ahead clear | Safe | Safe |
| $L$ | Following vehicle cannot stop in time | Unsafe | Safe |

For each fixed situation, all four action–environment combinations are physically admitted in this toy model. Only the outcome classification differs. Let

$$
q_*^X(a)=|\{e\in E_X:(a,e)\text{ has the goal-sustaining outcome}\}|,
\qquad X\in\{H,L\}.
$$

The exact goal-compatible environmental counts are

$$
\boxed{
q_*^H(Y)=2,\quad q_*^H(G)=1;
\qquad
q_*^L(Y)=1,\quad q_*^L(G)=2.
}
\tag{123.3}
$$

The same universal safety requirement yields a unique viable action in each situation:

$$
\boxed{a^*(H)=Y,\qquad a^*(L)=G.}
\tag{123.4}
$$

Neither decision requires a stochastic transition law. A complete goal-compatible relation fixes the viable action under each enclosing situation, while the local action repertoire is unchanged.

**Proposition 2 — Directional count agreement for the one-stage universal goal.** Suppose $E$ contains $N>0$ distinct alternatives available under each action, with exactly one outcome classification for each action–environment pair. If exactly one action is safe for *every* $e\in E$, that action has goal-compatible environmental count $N$, and each competing nonviable action has count at most $N-1$. Thus a unique universally safe action is also uniquely favored by this goal-compatible count.

**Proof.** The universally safe action is classified safe for every $e$, so its count is $N$. A nonviable action fails safety for at least one $e$, so its count is strictly smaller. $\square$

The proposition is a consequence of the stated *goal and finite compatibility domain*. The controller need not calculate the number $N$, and the result does **not** establish a general principle that real controllers or R²D physical systems maximize multiplicity. In particular, contingent-response viability is stronger than counting individually safe possibilities, as the next construction demonstrates.

## 123.5. Same physical possibilities, same counts, opposite decisions

Let

$$
 E=\{p,q,r,s\},\quad
 A=\{Y,G\},\quad
 R=\{r_0,r_1\}.
$$

Specify the following goal-sustaining complete comparisons. For each action–environment pair, the table gives the sole response that sustains the goal:

| Environment | Yield-compatible response | Go-compatible response |
|---|---|---|
| $p$ | $r_0$ | $r_0$ |
| $q$ | $r_0$ | $r_1$ |
| $r$ | $r_1$ | $r_0$ |
| $s$ | $r_1$ | $r_1$ |

Each action is individually goal-compatible with all four environments if the subsequent response can be chosen with knowledge of the complete environmental label. Thus both have exactly four goal-compatible action–environment–response triples. **The raw comparison counts agree.**

Now implement one of two physical observation classifications:

$$
\begin{aligned}
 o_A &: \{p,q\}\mapsto z_0,\quad \{r,s\}\mapsto z_1,\\
 o_B &: \{p,r\}\mapsto z_0,\quad \{q,s\}\mapsto z_1.
\end{aligned}
$$

For controller A, yielding is viable: response $r_0$ works throughout $\{p,q\}$, and $r_1$ works throughout $\{r,s\}$. Going is not viable, because its required responses conflict within each observation class. For controller B, going is viable and yielding is not.

Therefore

$$
\boxed{
 a^*(o_A)=Y,\qquad a^*(o_B)=G.
}
\tag{123.5}
$$

**Theorem 3 — Count equality does not determine contingent decision admissibility.** There exist two complete controller specifications with the same physical action–environment–response compatibility relation and equal counts of individually goal-compatible comparisons for both initial actions, but with opposite uniquely viable initial decisions, solely because their readable observation classifications differ.

**Proof.** The table above supplies four goal-compatible triples per action in both specifications. Direct application of Equation (123.2) establishes that only $Y$ is viable under $o_A$ and only $G$ under $o_B$. $\square$

The native physical count boundary has not necessarily changed merely because we changed its mathematical labeling in a model. In a real controller, however, implementing distinct sensors and readable distinctions changes the operative *controller–environment* compatibility specification. This is a candidate change of physical boundary ownership, subject to the mapping criteria of Addendum 86. One may not silently call the four comparison records native microstates or call the observation classification a newly created physical boundary without that mapping.

The result also sharpens Addendum 122: two representations can have equal counts while differing in the complete compatibility information required for an enclosing read. Here it is **readability** that determines whether the controller can realize an admitted complete contingent response.

## 123.6. Enclosing possibilities are not model-generated future worlds

A world model usually represents continuations that could occur after a present observation. That computational orientation is not a primitive time-directed creation of possibility. The surrounding world already constrains which continuations are physically admissible. The model's representational branches refer to those possibilities; the act of generating a branch does not make it a new physical possibility or an occupied world.

Let $\widehat\Gamma_M$ represent the model's candidates. To claim that its counts reproduce native physical multiplicity requires a justified physical mapping, not an identification by notation. In particular:

- **Omission:** $\widehat\Gamma_M$ may fail to represent an admitted complete realization.
- **Duplication:** many simulated trajectories may be multiple descriptions of one physical native realization.
- **Spurious composition:** a model may join individually admissible local forecasts into a globally inadmissible comparison.
- **Incorrect readability:** it may treat different latent alternatives as separately actionable although its controller cannot distinguish them when a response is required.

Theorems 1 and 3 show that the last error can reverse which initial action is viable without any change in raw goal-compatible counts. Addendum 122's exact-composition criterion addresses the third error. Addendum 108 supplies the more basic distinction between modeled branches and occupied occurrences.

The model's usefulness is not diminished by these differences. An imperfect representation can still support good decisions. But predictive success does not by itself establish that every represented branch is a native microstate or that its sample frequency is a native multiplicity.

## 123.7. Relation to the R²D possibility and occupancy equations

The finite decision theorems above are compatibility results. Their count coordinates must be compared carefully with the canonical R²D relations.

For adjacent native count boundaries $B_n\prec B_{n+1}$, Part I defines

$$
\Theta_{n+1\mid n,i}
=|\mathcal E_{n+1\mid n,i}|,
\qquad
P_{n,i}=\ln\frac{\Theta_{n+1\mid n,i}}{W_{n,i}},
$$

and

$$
\boxed{
\Delta P_{n,i\to k}
=\ln\left(
\frac{\Theta_{n+1\mid n,k}/W_{n,k}}
{\Theta_{n+1\mid n,i}/W_{n,i}}
\right).
}
\tag{123.6}
$$

Structural occupancy additionally depends on occurrence realization and productive retention. Under the proportional state-occurrence postulate,

$$
\boxed{
\frac{c_k}{c_i}\approx
\frac{\Theta_{n+1\mid n,k}}{\Theta_{n+1\mid n,i}}
\exp(-\Delta R_{i\to k}).
}
\tag{123.7}
$$

The goal-compatible counts $q_*^X(Y),q_*^X(G)$ in Section 123.4 are initially **counts of environmental comparison alternatives**, not the canonical $\Theta_{n+1\mid n,i}$. If an independently established physical R²D mapping identifies the relevant goal-sustaining complete realizations with distinct native enclosing realizations of a specified boundary, and identifies the actions with readable local macrostate classes, then the goal-conditioned counts may be used in Equation (123.6). Additional native local multiplicities and productive-retention reads must be assigned at their proper boundaries.

Under the *illustrative additional assumptions* of equal local native multiplicity and zero differential retention, an admissible 2:1 enclosing mapping would yield

$$
\Delta G_{Y\to G}^{H}\approx-\ln 2,
\qquad
\Delta G_{Y\to G}^{L}\approx+\ln 2.
$$

The directions would agree with the controller's two uniquely viable actions. This is a **conditional correspondence**, not a prediction made by R²D for a particular vehicle merely because the controller has been given a goal. Selecting a safe macrostate for engineering purposes must not be confused with proving that the physical enclosing count domain excludes all unsafe realizations. Likewise, the controller's programmed safety requirement is not automatically $C_{n+1}^{out}\lambda$, the R²D productive-retention read.

The coin construction supplies an exact native-count comparison of a different status. With ten local coins in a 100-coin ensemble fixed at 60 tails, Part I obtains

$$
\frac{W_6}{W_5}=\frac56,
\qquad
\frac{\Theta_6}{\Theta_5}=\frac{275}{216}>1.
$$

Enclosing compatibility reverses the locally favored native count without changing the local multiplicity landscape. No coin computes the enclosing ratio. A world-model controller makes explicit use of a represented enclosing relation, but the organizing mathematical dependence need not be implemented by microscopic foresight. The correspondence concerns the **priority of compatible possibility over the subordinate mechanism**, not identity between an engineered policy and a physical occupancy ratio.

## 123.8. Local agency is a realization, not the origin of its possibilities

A world-model-driven vehicle genuinely acts. Its processor evaluates represented alternatives; its control system issues commands; its actuators produce motion; and those physical acts can alter which enclosing realization is occupied or what compatibility applies at the next read. Nothing in R²D prohibits consequential local agency.

But observing the computation-to-motor sequence does not establish that those subordinate events define the road geometry, the pedestrian's possibilities, the traffic constraints, or the complete joint relation within which the decision is made. Addendum 85 distinguishes local dynamical sufficiency from enclosing causal sufficiency. Addendum 87 cautions that a useful story about the actor can obscure the prior organization that sustains the actor and its action.

The order is:

$$
\boxed{
\begin{gathered}
\text{Enclosing physical compatibility}\\
\Downarrow\\
\text{Physically implemented readable model and goal constraint}\\
\Downarrow\\
\text{Admissible complete decision and local realization}.
\end{gathered}
}
\tag{123.8}
$$

The arrows express the ordering of *defined compatibility and realization*, not a universal claim that a planner must first calculate every future. After an action, the realized observation may condition the next model read. That feedback does not mean the action retroactively created its original possibility domain.

At a physical boundary without an explicit world model, enclosing compatibility can still organize subordinate realizations. R²D does not require a molecule, coin, or motor protein to hold a model of its alternatives. The analogy does not grant microscopic objects deliberative agency; it makes visible how an explicit planner can exploit a mathematical organization that R²D treats as more primitive than the planner.

## 123.9. Why the decision correspondence is not a universal optimization law

Theorems 1–3 give exact admissibility statements under a *specified goal* and *specified readable comparison*. They do not establish that the most populous goal-compatible class always determines a controller's action. Three cases must be distinguished:

1. **Unique compatible action.** The operative goal and complete joint compatibility permit exactly one initial action. A controller enforcing that goal is directionally determined without a stochastic transition rule.
2. **Several compatible actions.** Complete compatibility alone does not choose between them. Additional operative constraints, priorities, or decision rules are required; these belong to the controller's actual organization, not to a new primitive R²D maximization principle.
3. **No compatible action.** The stated goal cannot be sustained under all admitted environmental alternatives with the controller's present readability and response repertoire. A real controller may revise its goal, alter its action space, tolerate risk, or acquire a different read; the finite universal-viability theorem does not choose among those responses.

Even when one action has more compatible enclosing realizations, the R²D occupancy prediction depends on the correctly specified $\Delta R$ and on the realization postulates. A controller's unique command is a completed local action, not a measurement of a large-sample structural occupancy ratio. These two readouts may have the same favored direction without being the same physical quantity.

The model-based decision can therefore be **deterministic without a stochastic selector**, while the relation between native possible counts and realized physical event counts remains governed by the distinct R²D realization and recurrence specifications.

## 123.10. Empirical status of the world-model comparison

Multi-future autonomous-driving systems supply a concrete setting in which candidate continuations are represented jointly and used for contingency planning. For example, Cui, Casas, Sadat, Liao, and Urtasun's *LookOut* (ICCV 2021) learns diverse joint traffic futures and plans an initial maneuver compatible with later responses. Its authors report improved diversity in predicted scenarios and improved simulated planning performance relative to their comparison methods. This is evidence that representing alternative **joint** traffic continuations is practically useful; it is not a measurement of an R²D-native multiplicity or a demonstration that physical occurrence is universally top-down.

The correspondence becomes a testable R²D physical mapping only after the following are specified independently:

1. The proposed operative physical enclosing boundary and its native-identification rule.
2. The local action boundary and its readable distinctions.
3. The complete physical compatibility relation, including unsafe but physically admissible realizations.
4. The physically implemented observation classification and goal constraint.
5. The mapping between simulated records and *distinct* native enclosing realizations.
6. Any proposed productive-retention and observable occurrence/occupancy reads, with their realization domains.

An informative finite experiment would change environmental compatibility while holding the controller's local repertoire fixed, or change operative sensor readability while holding the environmental alternatives fixed. Theorems 1–3 predict which complete contingent actions remain compatible under the declared specification. A separate R²D occupancy experiment would require independently enumerated native counts and retention, and should not use observed deterministic commands to fit the desired $\Theta$ or $\Delta R$.

The standard of Addendum 86 applies: distinguish mathematical definitions, conditional theorems, proposed physical mappings, empirical predictions, and causal interpretation. Agreement on a decision direction supports a proposed correspondence only to the extent that the alternative accounts and the independent count mapping make the comparison discriminating.

## 123.11. Relation to recurrence and Addendum 124

This addendum has not assigned a distribution of completed subordinate closure recurrences. It establishes **which complete contingent decisions are admissible** under a specified enclosing relation. Addendum 124 asks the complementary question: once an enclosing owner defines complete configurations of repeated closure modes, which count distributions are admitted and how many native realizations support each one?

The two results must not be conflated. One unique admissible initial controller action is not an equation for the relative recurrence counts of two physical subordinate modes. Conversely, a complete multiplicity landscape of physical closure configurations need not require a controller that reads the landscape or chooses a maximizing action.

What they share is the mathematical ordering:

$$
\boxed{
\text{Complete enclosing compatibility}
\;\text{precedes}\;
\text{the classification and realization of its subordinate alternatives.}
}
$$

The subsequent question of how native count becomes realized state occurrence and completed closure recurrence belongs to Part I's proportional realization postulate and recurrence-weighted R²D law. Neither is replaced by the finite controller viability criterion.

## 123.12. Results and conclusion

This addendum establishes the following results under explicit finite specifications.

**Result 1 — A world model represents possibilities; it does not create them.** The operative surroundings determine physical compatibility. Generating a model branch does not make it an additional native realization or an occupied world.

**Result 2 — Complete compatibility can uniquely determine an explicit decision.** When exactly one initial action admits a goal-sustaining observation-dependent response over every admitted environmental alternative, a controller implementing that universal goal has a uniquely compatible initial action. No primitive stochastic transition kernel is needed.

**Result 3 — Enclosing condition can reverse decision direction.** A fixed action repertoire and fixed goal can yield opposite uniquely viable actions under different complete physical compatibility conditions.

**Result 4 — Equal comparison counts need not support equal decisions.** Two controllers confronting the same environmental and goal-compatible triples can make opposite unique decisions because their physically implemented readabilities differ. Complete compatibility and readable classification are stronger data than a total count.

**Result 5 — Correspondence with R²D directional support is conditional.** Where a native physical mapping is independently established, enclosing-compatible multiplicity and productive constraint can organize occupancy direction. A deterministic command is not automatically a measure of R²D occupancy, and an engineered goal is not automatically productive retention.

These are mathematical and mapping results, not a demonstration that every successful world model implements the canonical R²D law or that individual physical occurrences are uniquely fixed by a possible count. They preserve the separation between physical compatibility, represented alternatives, explicit local action, and native realized occurrence.

The central conclusion is:

$$
\boxed{
\begin{gathered}
\text{The enclosing world defines the possibilities.}\\
\text{A world model reads some of those possibilities.}\\
\text{A controller acts within their complete compatibility.}\\
\text{The model and controller do not create the enclosing relation.}
\end{gathered}
}
$$

**Explicit decision-making is one way a local physical system can use enclosing possibility. It is not a prerequisite for enclosing possibility to organize physical realization.**

---

## Appendix A — Reproducible finite verification

| Verification | Required result |
|---|---|
| One-stage crossing condition $H$ | Goal-compatible counts: Yield 2, Go 1; uniquely universally safe: Yield |
| One-stage close-follower condition $L$ | Goal-compatible counts: Yield 1, Go 2; uniquely universally safe: Go |
| Same local action repertoire under $H,L$ | Exactly $\{Y,G\}$ in both |
| Four-environment response table | Four goal-compatible triples per initial action |
| Sensor A read $\{p,q\},\{r,s\}$ | Only Yield satisfies the observation-class intersection criterion |
| Sensor B read $\{p,r\},\{q,s\}$ | Only Go satisfies the criterion |
| Native-count safeguard | A model's scenario duplicates do not add native multiplicity |
| R²D coin comparison | $W_6/W_5=5/6$, $\Theta_6/\Theta_5=275/216$ |
| Physical-mapping safeguard | Goal-compatible scenario counts are not automatically $\Theta_{n+1\mid n,i}$ |

Theorems 1 and 3 can be verified by enumerating the stated finite tables. Their physical interpretation remains conditional on the enclosing and controller boundary specifications.

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*, authoritative Markdown revision, September 25, 2026; especially Sections 3.2, 3.4–3.9 and Appendix B. https://r2dscience.github.io/r2d-canon-publication/canon/part-i.html
2. R²D Addendum 85 — *Local Agency and Enclosing Dependence*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-085-local-agency-and-enclosing-dependence.html
3. R²D Addendum 86 — *The Status of a Physical Mapping*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-086-the-status-of-a-physical-mapping.html
4. R²D Addendum 87 — *Possibility Relations and the Limits of Agency Stories*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-087-possibility-relations-and-the-limits-of-agency-stories.html
5. R²D Addendum 103 — *The Causal Implications of the Microstate Definition*.
6. R²D Addendum 105 — *The Observational Inversion*.
7. R²D Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-107-possibilities-pull-probabilities-do-not-push.html
8. R²D Addendum 108 — *A Branch Is Not an Occupied World*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-108-a-branch-is-not-an-occupied-world.html
9. R²D Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*.
10. R²D Addendum 121 — *Nested Wells, Compatibility, and Harmonic Structure*.
11. R²D Addendum 122 — *Enclosing Compatibility Before Categorical Composition*.
12. R²D Addendum 124 — *Enclosing Recurrence Before Competing Closure Counts*.
13. Cui, A., Casas, S., Sadat, A., Liao, R., and Urtasun, R. (2021). *LookOut: Diverse Multi-Future Prediction and Planning for Self-Driving*. Proceedings of the IEEE/CVF International Conference on Computer Vision. https://openaccess.thecvf.com/content/ICCV2021/html/Cui_LookOut_Diverse_Multi-Future_Prediction_and_Planning_for_Self-Driving_ICCV_2021_paper.html

The finite controller examples supply mathematical comparisons, not independent physical causal axioms.
