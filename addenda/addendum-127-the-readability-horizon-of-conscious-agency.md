---
r2d_id: "addendum-127"
title: "Addendum 127 — The Readability Horizon of Conscious Agency"
subtitle: "Enclosing Possibility, Finite Surveys, and the Loss of Decision Coherence"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 127
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-03"
---

# R²D Addendum 127 — The Readability Horizon of Conscious Agency

*Enclosing Possibility, Finite Surveys, and the Loss of Decision Coherence*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 revision); Part III, especially Sections 1.7–1.19; Addenda 85–88, 103, 105, 107–108, and 120  
**Companion addenda:** Addenda 122–126  
**Scope:** Finite enclosing compatibility, retained projections, decision-relevant readability, goal-compatible control, branching and recursive replacement, and the boundary-relative limits of conscious agency

## Abstract

Recursively Realized Distinguishability (R²D) defines possible native realizations through an enclosing count boundary, independently of their subsequent occurrence or of any subordinate representation of them. An experiencing system reads a projection of that enclosing organization. Under the functional consciousness definition proposed in Addendum 126, it retains part of this read and uses the record to constrain its prospective interpretations and locally realized actions. It cannot thereby create the enclosing possibilities on which those actions depend.

As the relevant enclosing relations become more extensive, a system's survey may cease to distinguish alternatives requiring different actions. This is a loss of **decision-read coherence**, not a loss of coherence in the physical possibility landscape. An exact finite criterion is obtained by specifying the physically admitted action–environment–outcome relation, the controller's operative goal, and its readable classification. A goal-guaranteeing decision rule exists if and only if every readable observation class admits at least one action compatible with the goal across all environmental alternatives in that class. If one class requires mutually incompatible actions, no controller relying on that read alone can guarantee the goal. The result requires no stochastic transition law, primitive decision optimizer, or uniquely selected future.

Three consequences follow. First, the number of branches alone does not fix the limit: two indistinguishable possibilities can defeat a decision, whereas arbitrarily many possibilities can remain compatible with one action. Second, a finer effective read can recover an admissible decision without introducing new physical possibilities. Third, recursive enlargement does not universally multiply native microstates, because changing the enclosing boundary changes the native count domain; branching and readability must be established for each specified relation.

The proposed **conscious decision-read limit** is distinct from Part III's quantum and gravitational readability horizons, which concern the joint accessibility of recursively related distinguishability and recurrence. It is also distinct from physical landscape collapse, computational resource exhaustion, and uncertainty arising from an inaccurate model. The limit qualifies the conscious read of agency: a system can control a subordinate action without being able to read or guarantee every enclosing outcome of that action. The enclosing world remains the owner of the possibilities, whether or not the conscious system can survey them coherently.

## 127.1. The question: what fails when possibilities branch beyond our read?

R²D first defines which joint subordinate realizations are admitted at an operative boundary. For a boundary $B$, let $\mathfrak M_B$ be its native realization domain, with readable classification $\pi_B:\mathfrak M_B\to\mathcal S_B$ and native multiplicities

$$
W_B(s)=|\pi_B^{-1}(s)|.
$$

These quantities do not depend on an experiencing subordinate system enumerating them. Nor does a world model create a new possibility merely by generating a branch. The native units, the compatible domain, and their readable classes belong to the boundary that defines them.

Addendum 88 proposes experience as sustained closure and distinguishes a retained survey of encountered constraint. Addendum 126 proposes a more specific functional consciousness relation: recorded experience participates in constraining a prospective read and subsequent subordinate realization. This proposal does not claim that all experience is explicit forecasting or that the system possesses a complete read of its world.

The present question is: **When can a finite, record-informed read no longer distinguish enough of the enclosing alternatives to sustain a specified goal through one coherent action?**

This cannot be answered by counting the number of simulated trajectories alone. A model's branches may duplicate native realizations, omit them, or combine partial descriptions into globally inadmissible scenarios (Addenda 120 and 122). The question must begin with an enclosing-owned compatibility relation and only then examine what the controller can read.

## 127.2. Three different things: physical possibility, the read, and the goal

For a finite test, let $E$ be a declared set of environmental comparison alternatives, $A$ a finite set of locally realizable actions, and $O$ a finite set of outcomes readable for the declared goal. The enclosing owner specifies

$$
\boxed{\Gamma_B\subseteq E\times A\times O.}
\tag{127.1}
$$

A tuple $(e,a,o)$ asserts that outcome $o$ is admitted with environmental alternative $e$ and local action $a$ in this **one complete enclosing comparison**. It does not claim that each label is an independent primitive physical object or that each tuple is automatically one native R²D microstate. Native identification must be supplied separately for any $W_B$ or $\Theta$ claim.

Let $G\subseteq O$ be the outcomes that the controller is required to sustain. This is an **operative goal**, not automatically Part I's productive-retention coordinate $R$. An undesired outcome remains physically possible merely because it lies outside $G$.

For $e\in E$ and $a\in A$, define the complete possible outcome set

$$
\Gamma_B(e,a)=\{o\in O:(e,a,o)\in\Gamma_B\}.
$$

The actions that **guarantee** the declared goal under alternative $e$ are

$$
\boxed{F_B(e)=\{a\in A:\Gamma_B(e,a)\ne\varnothing\ \text{and}\ \Gamma_B(e,a)\subseteq G\}.}
\tag{127.2}
$$

The nonemptiness requirement excludes a vacuously safe action that has no physically admitted realization. Requiring all admitted outcomes to lie in $G$ distinguishes *guaranteed goal compatibility* from the weaker statement that at least one safe outcome is possible. The robust requirement is the declared goal of this example, not a universal definition of what controllers should want.

A conscious controller's effective read includes such things as current sensing, retained records, and their operative organization. Represent it schematically by

$$
\boxed{r_A:E\longrightarrow Z_A.}
\tag{127.3}
$$

This is a comparison map recording what the controller can distinguish **for this decision**. It is not an omniscient measurement of $E$, a new primitive R²D map, or a claim that every environment label is physically readable at the controller boundary. A world model may also make mistakes about which outcomes belong to $\Gamma_B(e,a)$; that modeling error is a further issue beyond the readability question treated first.

## 127.3. The finite decision-coherence theorem

A response rule that depends only on the controller's effective read has the form

$$
f:Z_A\longrightarrow A.
$$

Call $f$ **universally goal-compatible** when $f(r_A(e))\in F_B(e)$ for every $e\in E$. The same observation label must select the same action, even if different enclosing alternatives lie behind that label.

**Theorem 1 — Boundary-relative decision-coherence criterion.** There exists a universally goal-compatible response rule based only on $r_A$ if and only if

$$
\boxed{\forall z\in r_A(E),\qquad \bigcap_{e\in r_A^{-1}(z)}F_B(e)\ne\varnothing.}
\tag{127.4}
$$

**Proof.** If a goal-compatible rule $f$ exists, then for each observation $z$, the one action $f(z)$ belongs to $F_B(e)$ for every $e$ read as $z$. It therefore belongs to their intersection. Conversely, if every displayed intersection is nonempty, choose one action from each intersection and assign it to that observation label. The resulting rule belongs to $F_B(e)$ for every admitted $e$. Its values outside $r_A(E)$ do not affect the comparison. $\square$

**Definition 1 — Decision-read coherence.** The specified boundary, controller read, and goal are *decision-coherent* when (127.4) holds. They reach a *decision-read limit* when it fails.

The theorem is a finite compatibility identity. It does not make $f$ the cause of the enclosing possibility domain; it does not claim that the real controller will necessarily implement the available rule; and it says nothing by itself about native multiplicity, structural occupancy, or the occurrence of any particular outcome. It identifies which goal-guaranteeing **policies are admissible from the stated read**.

## 127.4. The smallest failure: two possibilities and one unreadable difference

Take two environmental alternatives $E=\{e_1,e_2\}$ and two actions $A=\{\text{Brake},\text{Proceed}\}$. Specify the enclosing goal-compatible actions as

$$
F_B(e_1)=\{\text{Brake}\},\qquad F_B(e_2)=\{\text{Proceed}\}.
$$

Suppose the controller reads both alternatives as the same observation:

$$
r_A(e_1)=r_A(e_2)=z.
$$

Then

$$
F_B(e_1)\cap F_B(e_2)=\varnothing.
$$

No single goal-guaranteeing action follows from that observation. Both enclosing possibilities remain defined and may be physically realized. Their incompatibility as required responses is not a contradiction in the enclosing world. It is a limit of **the controller's available read**.

If an additional physically realizable distinction permits $r'_A(e_1)\ne r'_A(e_2)$, a policy can choose Brake for the first and Proceed for the second. Nothing new has been added to the enclosing possibility domain. A previously unavailable distinction has become operative within the controller's read.

The example establishes that **only two possibilities may suffice for decision-read failure**. A great number of branches is not a necessary condition.

## 127.5. Branch number is not a universal coherence threshold

Consider $m$ separately indexed environmental peer alternatives, each of which has two admitted readings. If one enclosing owner explicitly admits their full product, its comparison domain has $2^m$ combinations. But the R²D boundary might admit only a subset of them, and the distinct native realization count can differ further if its identification relation does not count each presentation separately.

Now suppose that, across any finite number of admitted environmental alternatives,

$$
\text{Brake}\in F_B(e)\quad\text{for every }e\in E.
$$

Even if every possibility has the same observation label, Equation (127.4) holds: Brake is common to all the goal-compatible action sets. **Arbitrarily many branches can remain decision-coherent.**

Conversely, Section 127.4 fails with only two alternatives. Thus neither $|E|$ nor the number of modeled future branches determines coherence without the complete compatibility of those alternatives with the available actions.

A sharper finite obstruction is possible. Suppose $e_1,\ldots,e_q$ have nonempty but pairwise disjoint viable-action sets, $F_B(e_i)\cap F_B(e_j)=\varnothing$ whenever $i\ne j$. If the controller has fewer than $q$ distinct observation labels across these alternatives, two must share a label. Their shared observation class has an empty action intersection, and a universally goal-compatible rule is impossible. This is a conditional distinguishability requirement, not a formula for how many native microstates a larger R²D boundary must possess.

**Corollary 1.1 — Incompatible alternatives require distinguishable reads.** For any set of pairwise action-incompatible environmental alternatives, a universally goal-compatible policy requires their read labels to be distinct.

The corollary does not introduce an objective of finding the smallest or “coarsest” representation. It tests the sufficiency of an **already specified physical read** against an already specified enclosing compatibility relation.

## 127.6. Pairwise coherence can conceal a joint failure

There is a second finite lesson closely related to Addendum 122: checking compatible alternatives only in pairs may miss a conflict belonging to the complete enclosing relation.

Let the action set be $A=\{a,b,c\}$, with three environmental alternatives having

$$
F_B(e_1)=\{a,b\},\quad
F_B(e_2)=\{b,c\},\quad
F_B(e_3)=\{a,c\}.
$$

Every pair of viable-action sets has a nonempty intersection, yet

$$
\boxed{F_B(e_1)\cap F_B(e_2)\cap F_B(e_3)=\varnothing.}
\tag{127.5}
$$

If all three alternatives share one observation, no universal goal-compatible action exists. The problem cannot be detected by checking only whether each pair is locally reconcilable. The complete joint compatibility must be preserved.

This is the same logical warning as Addendum 122's spurious-composition example: **valid partial comparisons need not compose into a valid enclosing realization**. A world model that treats its branches as independently pairwise plausible may still fail to identify the constraints on their complete joint interpretation.

## 127.7. Recorded experience can improve the read without creating possibilities

Addendum 126 proposes that consciousness reuses retained experience to constrain prospective interpretations and action. This can make an otherwise unreadable distinction operative for a particular controller.

Suppose $r_0:E\to Z_0$ is a current-sensor-only read and $r_1:E\to Z_1$ is a physically realized read that incorporates an additional retained distinction. Say $r_1$ **resolves every distinction of** $r_0$ when there is a map $q:Z_1\to Z_0$ with

$$
\boxed{r_0=q\circ r_1.}
\tag{127.6}
$$

This describes two *fixed comparison maps*, not a rule that a consciousness system must optimize its representation.

**Theorem 2 — Viability is preserved under added readable distinctions.** For fixed $\Gamma_B$, fixed goal $G$, and fixed action repertoire $A$, if a universally goal-compatible policy exists using $r_0$ and (127.6) holds, one also exists using $r_1$.

**Proof.** Given a valid $f_0:Z_0\to A$, set $f_1=f_0\circ q$. Then for every $e$, $f_1(r_1(e))=f_0(r_0(e))\in F_B(e)$. $\square$

The converse can fail, as the two-alternative example demonstrates. Resolving a relevant distinction can recover a goal-compatible decision without changing the original enclosing possibilities.

The result is conditional on an accurate, usable read. An erroneous record may introduce false conclusions; its ability to store more bits or generate more predictions does not prove fidelity to $\Gamma_B$. Nor does the theorem guarantee that a physically implemented controller can compute or realize the valid policy. Its computation, memory, and actuation remain subordinate realizations within their own enclosing constraints.

## 127.8. Recursive enclosure is not an ever-growing tree of persistent states

It is tempting to picture each new enclosing boundary as adding another independent branching factor to the same persistent lower-level states. That would import the bottom-up state ontology excluded by Part I.

At $B_n$, a native microstate is one compatible joint realization of the immediately subordinate peers. At $B_{n+1}$, the native domain and readable classification are defined anew. Recursive carry changes count identity; it does not transport a fixed population of microscopic trajectories into an ever-larger tree.

The number of distinct native realizations may grow, contract, or change its meaning with the specified enclosing relation. A full-product domain can produce exponential growth **within a chosen comparison**; a correlated or more restrictive enclosing relation need not. Addendum 124's product-compatible and homogeneous-only six-position constructions make that difference explicit.

Therefore the statement “the larger the boundary, the more possibilities branch” is a useful hypothesis for certain physical comparison families, **not a universal monotonic law of R²D**. What remains general is that no finite observing boundary possesses a complete read of all enclosing and subordinate recursive domains simultaneously.

This is also why a loss of decision-read coherence does not establish that the enclosing native landscape has physically collapsed or become inconsistent. A failure of the controller's representation is not a failure of the count domain it attempts to survey.

## 127.9. Relation to Part III's readability horizons

Part III distinguishes a **physical readability horizon** from landscape collapse. Toward subordinate closure, recurrence may remain readable when its associated distinguishability no longer remains jointly accessible; toward enclosing closure, distinguishability may remain readable when the corresponding enclosing recurrence is no longer accessible. Both are relative to a specified observing boundary. Neither means that the unread relation has ceased to be realized.

The decision-read limit in this addendum is a different object. It concerns whether a system's available distinction classes permit a single action compatible with a declared goal across an unresolved set of alternatives.

The distinctions should not be collapsed:

| Relation | What may fail | What does not thereby fail |
|---|---|---|
| Part III physical readability horizon | Joint physical access to recursive distinguishability and recurrence | The underlying recursive relation |
| Decision-read limit (this addendum) | Existence of a uniformly goal-compatible policy based only on the operative read | The enclosing compatibility domain |
| Model mismatch | Fidelity of represented scenarios to the physically admitted relation | Physical admission itself |
| Computational or actuator limit | Ability to construct or execute a policy | Mathematical existence of a compatible policy |
| Landscape collapse | Continued physical realization of the specified enclosing count domain | Not merely an observer's read of it |

The use of *horizon* in this addendum marks a proposed **goal-relative limit of conscious agency**. It does not introduce a third canonical quantum/gravitational horizon coordinate, nor identify a controller's finite memory with Part III's physical readability conditions.

## 127.10. What happens to free will at the limit?

Addendum 126 revises free will as the conscious read or experience of exercising local control, not independent authorship of enclosing possibility. The present analysis places a further boundary on that read.

Even if Equation (127.4) fails, a controller can still act. It may brake, proceed, defer, seek more information, or revise its goal, insofar as those actions are admitted by the appropriate enclosing specification. What fails is **the guarantee of the declared goal under every alternative that its operative read cannot distinguish**.

This matters for the claim that we choose which possibilities we realize. We can consciously constrain and locally enact an action. We do not independently select the complete enclosing occurrence or guarantee all its consequences. Our ability to make a locally coherent decision is itself conditional on the distinctions available to the experiencing boundary.

A driver may read a child entering the road and brake, yet fail to read another vehicle approaching the child. The braking act is consequential, but it does not supply an exhaustive read of every compatible outcome or become the primitive organizing cause of the child's survival. The driver's locally recorded decision is not the complete enclosing occurrence.

The **projection-of-agency hypothesis** in Addendum 126 is sharpened: a system records what it predicted, decided, and did, then relates that sequence to what it observed. The less of the relevant enclosing organization its read retains, the less justified is an inference from that local record to authorship of the whole. The further claim that this limitation produces a particular subjective *feeling* of free will remains an interpretive hypothesis rather than a theorem of compatibility counting.

## 127.11. Autonomous vehicles as a finite physical test

World-model-driven vehicles are promising tests because their observation maps, stored records, internal predictions, controller constraints, and realized local commands can be examined independently.

A stringent experiment would specify a finite physical or high-fidelity test domain $\Gamma_B$, verify the environmental alternatives and complete action–outcome compatibility, declare the controller's goal, and determine its actual physically operative observation classification. It would then compare three separately measured or constructed objects:

1. The full enclosing-compatible action sets $F_B(e)$.
2. The controller's available read and retained-record relation $r_A$.
3. The implemented policy and realized occurrences.

Theorem 1 predicts exactly when a universal goal-guaranteeing policy exists **for that read**. Theorem 2 predicts that adding faithful, operative distinctions cannot destroy such a policy when physical compatibility, action repertoire, and goal are held fixed. A sensor failure or withheld record can produce an identifiable decision-read limit; restoring the distinction can recover viability. Merely adding thousands of compatible branches that share a common admissible action need not change the result.

The model may misrepresent physically admissible alternatives, and real traffic may not satisfy the finite exhaustive comparison. Such a failure is a question about the physical mapping or completeness of the test domain. These results do not prove that actual autonomous vehicles achieve robust safety or that their success alone verifies R²D's top-down physical ontology. The R²D contribution is the *prior* boundary definition of what the comparisons mean and the nonidentity of local controller action with enclosing causal authorship (Addendum 105).

## 127.12. Results and limits

The addendum establishes four exact finite results under declared enclosing and controller specifications:

**Result 1 — Decision coherence is a full-fiber compatibility property.** A universally goal-compatible policy exists exactly when the action sets associated with every unreadably merged observation class have a nonempty joint intersection.

**Result 2 — Branch count does not define the limit.** Two unresolved alternatives may defeat coherent action, while arbitrarily many admitted alternatives may share one viable action. Pairwise compatibility is insufficient where the complete multi-alternative intersection is empty.

**Result 3 — Added operative readability can restore coherence.** A read preserving all earlier distinctions cannot eliminate an already available universally goal-compatible policy, and can make previously conflicting alternatives actionable without creating new enclosing possibilities.

**Result 4 — No universal branch-growth or horizon identity follows across recursive boundaries.** R²D changes native count identity with enclosure. The decision-read limit is neither a universal native-multiplicity threshold nor one of Part III's two physical readability horizons.

All four results are conditional mathematical consequences of the specified comparison. Their classification as *physical* R²D results requires a justified native and readable boundary mapping, not merely a programmed scenario list. Nothing here proves that a definite human subjective experience follows from the intersection criterion or that all conscious decisions aim at universal goal satisfaction. Real controllers may adopt other operative goals and acceptance conditions, each requiring its own enclosing specification.

## 127.13. Conclusion

Enclosing possibility does not lose coherence because a conscious system cannot fully survey it. The system encounters a limit when its retained and current projections no longer distinguish the alternatives needed to make one locally realized action compatible with its declared goal.

$$
\boxed{\begin{gathered}
\text{The enclosing boundary defines possible realizations.}\\
\text{Recorded experience supplies a finite projection.}\\
\text{Consciousness uses that projection as prospective constraint.}\\
\text{Decision coherence depends on preserving the distinctions}\\
\text{required by the enclosing compatibility relation.}
\end{gathered}}
$$

A conscious agent can exercise local control even where the enclosing implications of that control exceed its read. It cannot originate those enclosing possibilities, guarantee every outcome, or recover the entire recursive hierarchy by adding modeled branches. The future, understood as already-admitted compatible continuation, constrains the present action; it is not a later occupied event acting backward in time.

**The limit of conscious agency is not the limit of physical possibility. It is the limit of what an experiencing boundary can read and coherently constrain within a possibility landscape it does not create.**

---

## Appendix A — Finite verification targets

| Verification | Required result |
|---|---|
| Two alternatives, identical read, disjoint viable action sets | Decision-read limit; empty intersection |
| Same two alternatives, distinct operative reads | Goal-compatible policy can exist |
| Arbitrarily many alternatives sharing Brake | Decision coherence survives, independently of branch count |
| $q$ alternatives with pairwise disjoint nonempty viable-action sets, fewer than $q$ read labels | Guaranteed coherence failure |
| Three sets $\{a,b\},\{b,c\},\{a,c\}$ under one read | Every pair intersects; full intersection empty |
| Read refinement $r_0=q\circ r_1$ | Existing viable policy lifts to refined read |
| Change the enclosing native identity rule | Branch count may change; model labels cannot be counted as native automatically |
| Compare Part III readability and decision coherence | Distinct target relations; no new quantum/gravitational horizon asserted |
| Compare potential and realized counts | No identification of branch number, native multiplicity, occupancy, or recurrence without the specified physical mapping |

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*. Authoritative revision, September 25, 2026; Sections 3.2–3.9.
2. R²D Part III — *The Recursive Clock and the Horizons of Readability*; especially Sections 1.7–1.19.
3. R²D Addendum 85 — *Local Agency and Enclosing Dependence*.
4. R²D Addendum 86 — *The Status of a Physical Mapping*.
5. R²D Addendum 87 — *Possibility Relations and the Limits of Agency Stories*.
6. R²D Addendum 88 — *Sustained Closure, Experience, and Recursive Surveying*.
7. R²D Addendum 103 — *The Causal Implications of the Microstate Definition*.
8. R²D Addendum 105 — *The Observational Inversion*.
9. R²D Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*.
10. R²D Addendum 108 — *A Branch Is Not an Occupied World*.
11. R²D Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*.
12. R²D Addendum 122 — *Enclosing Compatibility Before Categorical Composition*.
13. R²D Addendum 123 — *Enclosing Possibility Before Model-Based Decision*.
14. R²D Addendum 124 — *Enclosing Recurrence Before Competing Closure Counts*.
15. R²D Addendum 125 — *Native Occurrence Before Completed-Closure Statistics*.
16. R²D Addendum 126 — *Consciousness, Free Will, and the Projection of Causal Agency*.
