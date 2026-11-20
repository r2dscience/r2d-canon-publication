---
r2d_id: "addendum-137"
title: "Addendum 137 — Enclosing Compatibility Determines Cross-Stage Recurrence"
subtitle: "Native Matching, Permitted Incidence, and Exact Extension Multiplicities"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 137
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-14"
scope: "Finite unitless complete-matching compatibility, derived cross-stage derangements, exact enclosing extension counts, possible-count distinctions, comparison with additive incidence, and nonselection of physical realization"
---

# R²D Addendum 137 — Enclosing Compatibility Determines Cross-Stage Recurrence

*Native Matching, Permitted Incidence, and Exact Extension Multiplicities*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 scientific revision); Addenda 120 and 122 (native identification and enclosing compatibility); Addenda 135 and 136 (unitless admissible recurrence patterns and comparison identification); Addendum 131 (symmetric background recurrence, distinct from realized counts).  
**Purpose:** Derive nontrivial cross-stage comparison restrictions and exact possible enclosing extensions from a prior unitless native matching specification, without defining a traveling wave, retaining a subordinate object, invoking directed closure, or inferring physical occurrence from possibility.

## Abstract

An enclosing boundary determines which complete joint realizations are possible. Its native response classifications may constrain recurrence comparisons more strongly than their separate marginal multiplicities reveal. Addendum 135 counted unitless stationary and translating incidence classes without selecting them. Addendum 136 showed that identification of a spatial response difference across recurrence stages conditionally forces a zero mixed-difference relation. That identification, however, is an additional condition rather than a consequence of Part I alone.

Here the starting condition is different. One enclosing owner admits complete four-address, four-stage records in which each stage distinguishes all four response classes exactly once and each address distinguishes all four response classes exactly once across the recurrence comparison. These are *native complete-matching conditions*, stipulated independently of propagation, a stage-invariant response difference, or a physical time law. They define possible records only, not realized events.

We prove that comparisons between any two stages are fixed-point-free permutations; their complete correspondence maps obey an exact composition identity. We determine all two-stage enclosing extension counts: a fixed-point comparison has no complete extension; a four-cycle comparison has two; a pair of disjoint transpositions has four. Exactly **576** labeled complete patterns are admitted, rather than the unrestricted $4^{16}$ patterns. The resulting admissible set excludes all stage-stationary patterns, but contains both fixed-translation and nontranslation incidence. Only **144** admitted patterns satisfy Addendum 136's zero mixed-difference relation, and only **48** lie in one of the fixed one-address-per-stage translation classes. Thus native matching produces genuine cross-stage restrictions without selecting a wave law.

The results are conditional consequences of a specified enclosing matching owner. Part I authorizes such a compatibility specification but does not require complete matching at every boundary. None of the finite possible-count results predicts realized recurrence, an electromagnetic phase, physical propagation, or the energetic read $mc^2$.

## 137.1. Logical scope: possibility before realization

R²D distinguishes native multiplicity $W$, compatible enclosing extension $\Theta$, and their across-boundary logarithmic possibility coordinate $P$ from realized occurrence and occupancy. These count types must not be substituted for one another. In the present construction, every enumerated record is **one permitted complete receiving-boundary pattern**; no record is asserted to occur physically.

We investigate a unitless question:

> Can independent native completeness requirements restrict cross-stage spatial–recurrence comparisons, and determine exact enclosing extensions, *without first assigning a propagation rule*?

The result should count permitted complete relations. It should not introduce a moving microstate, a physical time interval, a frequency in hertz, or a directed-closure realization rule. A candidate symmetric complete-turbine signature may be carried alongside these records, but it does not determine the incidence structure and must not be confused with the stage labels used below.

## 137.2. One common enclosing owner and its native matching specification

Fix a common enclosing owner $J$. Let $X$, $T$, and $Q$ be three **different kinds of four-element label set**:

$$
X=\{x_0,x_1,x_2,x_3\},\qquad
T=\{t_0,t_1,t_2,t_3\},\qquad
Q=\{q_0,q_1,q_2,q_3\}.
\tag{137.1}
$$

They label, respectively, distinguishable receiving-boundary addresses, positions in a complete recurrence comparison, and native relative-response classifications. These labels do not require spatial distance, physical time, a cyclic phase group, or any numerical energy. A complete candidate response-incidence record is a function

$$
h:X\times T\longrightarrow Q.
\tag{137.2}
$$

Without further enclosing restriction the complete candidate domain is

$$
\mathcal P=Q^{X\times T},\qquad |\mathcal P|=4^{16}=4{,}294{,}967{,}296.
\tag{137.3}
$$

We now specify **one enclosing compatibility relation**, prior to any description of cross-stage motion:

**(M1) Stage-complete native distinction.** For every stage $t\in T$, the map $p_t:X\to Q$, $p_t(x)=h(x,t)$, is a bijection.

**(M2) Address-complete native distinction.** For every address $x\in X$, the map $r_x:T\to Q$, $r_x(t)=h(x,t)$, is a bijection.

The owner admits exactly the complete patterns satisfying both requirements:

$$
\boxed{\mathcal C_J^{\mathrm{match}}
=\{h\in\mathcal P:\ p_t\text{ and }r_x\text{ are bijections for all }t,x\}.}
\tag{137.4}
$$

These are independent **types** of native matching condition. Neither assumes that a fixed response difference is preserved between stages. Their conjunction is the familiar finite *Latin-square incidence condition*, here used strictly as a count structure, not as a physical square or a history of four persistent objects. The response classes are boundary-owned; a label repeated at different positions denotes a common native **classification**, not one traveling subordinate constituent.

Part I allows an enclosing owner to specify (M1)–(M2). It does not universally require them. All the theorems below are conditional on this declared matching compatibility.

## 137.3. Theorem 1 — Derived fixed-point-free cross-stage correspondence

For two stages $t,t'$, their complete native comparison is the response-class permutation

$$
\boxed{g_{t't}=p_{t'}\circ p_t^{-1}:Q\longrightarrow Q.}
\tag{137.5}
$$

**Theorem 1 (cross-stage derangement).** If $h\in\mathcal C_J^{\mathrm{match}}$ and $t\ne t'$, then $g_{t't}$ has no fixed points:

$$
\boxed{g_{t't}(q)\ne q\quad\text{for every }q\in Q.}
\tag{137.6}
$$

**Proof.** Given $q\in Q$, (M1) identifies the unique address $x=p_t^{-1}(q)$ carrying $q$ at stage $t$. Condition (M2) forbids that same address from carrying the same response class at another stage. Therefore $p_{t'}(x)\ne p_t(x)=q$. By (137.5), $g_{t't}(q)\ne q$. $\square$

A **derangement** is a fixed-point-free permutation. The result is nontrivial: it excludes every stage pairing for which any address repeats its native response class. No shift, phase velocity, or spatial propagation law appears in the premise or proof.

## 137.4. Theorem 2 — Exact composition of native comparisons

**Theorem 2 (common-owner comparison coherence).** For all $t,u,v\in T$, the induced response correspondences satisfy

$$
\boxed{g_{vt}=g_{vu}\circ g_{ut},\qquad
 g_{tt}=\mathrm{id},\qquad g_{tu}=g_{ut}^{-1}.}
\tag{137.7}
$$

**Proof.** By (137.5), $g_{vu}g_{ut}=(p_vp_u^{-1})(p_up_t^{-1})=p_vp_t^{-1}=g_{vt}$. Identity and inverse relations follow immediately. $\square$

These are **comparison identities**, not dynamics. They state that partial descriptions of the *same specified complete owner* are mutually consistent. They are not licenses to join independently given partial records arbitrarily: the enclosing admissibility relation remains (137.4), as emphasized by Addendum 122.

Pairwise derangement and the identities (137.7) are necessary consequences of complete matching. A random collection of individually deranged permutations need not extend to a four-stage owner: all pairwise differences must be derangements, and a full set of four distinct stage matchings must be jointly admitted.

## 137.5. Theorem 3 — Exact two-stage enclosing extension multiplicities

Fix a **labeled** native two-stage record $b=(p_{t_0},p_{t_1})$ with each stage bijective. Let

$$
\Theta_J(b)=\bigl|\{h\in\mathcal C_J^{\mathrm{match}}:
 h|_{X\times\{t_0,t_1\}}=b\}\bigr|
\tag{137.8}
$$

be its count of compatible complete enclosing extensions.

**Theorem 3 (extension trichotomy).** Set $g=p_{t_1}p_{t_0}^{-1}$. Then

$$
\boxed{
\Theta_J(b)=
\begin{cases}
0, & g\text{ has at least one fixed point},\\
2, & g\text{ is a four-cycle},\\
4, & g\text{ is a product of two disjoint transpositions}.
\end{cases}}
\tag{137.9}
$$

**Proof.** If $g$ has a fixed point, some address repeats its response label in the two selected stages, contradicting (M2); therefore no complete extension exists.

Now assume $g$ is a derangement. Each address has exactly two response labels not yet used in the fixed two stages. Consider the bipartite graph joining each address to its two remaining response labels. Completing the final two stages means partitioning this degree-two graph into two labeled perfect matchings.

If $g$ is a four-cycle on response labels, the remaining bipartite graph forms one alternating eight-edge cycle. It has exactly two perfect-matching partitions into the two labeled final stages. If $g$ consists of two disjoint transpositions, the remaining graph consists of two alternating four-edge cycles; the independent choices give $2^2=4$ partitions. $\square$

The theorem derives a **zero or positive enclosing possibility count** from the prior native matching rule. It does not assign a physical realization probability or predict which extension will be occupied.

## 137.6. Theorem 4 — Exact total admissible-pattern count

There are $4!=24$ choices for the first labeled stage. The second labeled stage also has $24$ bijective possibilities, of which $9$ are derangements relative to the first: six four-cycles and three products of two disjoint transpositions. The other fifteen have at least one fixed point.

The table gives the exact number of two-stage records and their extension counts:

| Cross-stage correspondence | Two-stage native records | Extensions per record $\Theta_J(b)$ | Complete extensions |
|---|---:|---:|---:|
| Has a fixed point | $24\cdot15=360$ | $0$ | $0$ |
| Four-cycle | $24\cdot6=144$ | $2$ | $288$ |
| Two disjoint transpositions | $24\cdot3=72$ | $4$ | $288$ |
| **Total** | **576** | — | **576** |

**Theorem 4 (admitted complete-pattern cardinality).** The declared enclosing owner admits precisely

$$
\boxed{|\mathcal C_J^{\mathrm{match}}|=24(6\cdot2+3\cdot4)=576}
\tag{137.10}
$$

labeled native response-incidence patterns. Thus the number excluded from the unrestricted complete-pattern domain is

$$
\boxed{|\mathcal P\setminus\mathcal C_J^{\mathrm{match}}|
=4^{16}-576=4{,}294{,}966{,}720.}
\tag{137.11}
$$

The integer $576$ is the classical count of labeled Latin squares of order four; the contribution here is its enclosing-compatibility interpretation and the derived conditional extension counts, not a claim to a newly discovered combinatorial formula.

**Scope of counting.** Addresses, stages, and response classifications are distinguishable labels of the declared boundary. A relabeling produces another labeled pattern unless the owner separately identifies such patterns under a native quotient. Reference-coordinate transformations and subordinate presentation multiplicities are not silently counted as new native records. The integer $576$ is the cardinality for **this** labeled native pattern domain.

## 137.7. Relation to Part I's compatible-extension possibility

The raw $\Theta_J(b)$ counts in (137.9) count compatible complete *possible* extensions of a specified two-stage record. They are not automatically Part I's logarithmic possibility coordinate $P_{B,k}$: the latter requires the appropriate native local multiplicity $W_{B,k}$ and the correctly specified enclosing count comparison.

For a chosen two-stage boundary whose *individual labeled record* is one native possible realization ($W_{B,b}=1$), and where $\Theta_{J\mid B,b}=\Theta_J(b)$ is the appropriate enclosing compatible extension count, the conditional ratio is

$$
K_{J\mid B,b}=\frac{\Theta_J(b)}{1}=\Theta_J(b).
\tag{137.12}
$$

For the two admitted derangement classes,

$$
P_{\mathrm{4cycle}}=\ln2,\qquad
P_{\mathrm{2+2}}=\ln4,
\quad\boxed{P_{\mathrm{2+2}}-P_{\mathrm{4cycle}}=\ln2.}
\tag{137.13}
$$

If the boundary groups many labeled records into one local macrostate, its $W$ and $\Theta$ must instead be recomputed on that specified class. The resulting across-boundary ratio need not be (137.12). For an incompatible record, $\Theta=0$ is a valid zero **raw possible count**; no finite $\ln0$ or finite $P$ is assigned.

These differences classify possibilities. They neither imply a stochastic realization law nor tell us how many complete records nature realizes.

## 137.8. Theorem 5 — Matching and additive comparison identity are independent

Addendum 136 studied the distinct conditional identification

$$
\Delta_j\Delta_n\delta=0,
\quad\text{equivalently}\quad
\delta(j,n)=c+F(j)+G(n)
\tag{137.14}
$$

when the response classes themselves carry the additive structure $Q=\mathbb Z_4$. That condition is not required in (M1)–(M2), which need only four distinguishable response labels.

To compare the two finite constructions, **now** equip $Q$ with $\mathbb Z_4$ labels. Within the $576$ matching-admissible complete patterns, exact counting gives

$$
\boxed{|\mathcal C_J^{\mathrm{match}}\cap
\mathcal C_J^{\mathrm{id}}|=144.}
\tag{137.15}
$$

**Proof.** A zero-mixed-difference pattern has the unique normalized form $c+F(j)+G(n)$ with $F(0)=G(0)=0$. The matching requirements say that $F$ and $G$ must each enumerate all four values, up to their fixed zero origins. There are four choices of $c$, $3!$ choices of $F$, and $3!$ choices of $G$. Thus $4(3!)(3!)=144$. $\square$

The other $576-144=432$ matching-admissible patterns have nonzero mixed difference somewhere. Conversely, Addendum 136 admits stage-stationary patterns excluded by (M2). Neither compatibility rule implies the other.

Two concrete admitted patterns are

$$
\delta_T(j,n)=j-n\pmod4,
\qquad
\delta_X(j,n)=j\operatorname{XOR}n,
\tag{137.16}
$$

where XOR is on the two-bit labels. Both meet the matching premises. The first has zero mixed difference and fixed diagonal-translation incidence; the second does not. Their row and column histograms are identical. The distinction between them is one of **complete enclosing incidence**, not marginal response multiplicity.

## 137.9. Theorem 6 — Native matching does not select propagation

To compare with Addenda 135–136, regard the four address and stage labels as cyclically ordered and define the unitless one-address-per-stage translation classes

$$
\mathcal W_\pm=\{\delta:\delta(j,n)=H(j\mp n),\ H:\mathbb Z_4\to Q\}.
\tag{137.17}
$$

These are *incidence classifications*, not a physical wave law. A translating pattern lies in the matching-admissible domain precisely when $H$ is bijective.

**Theorem 6 (nonselection and exact subclasses).** The complete-matching domain satisfies

$$
\begin{aligned}
|\mathcal C_J^{\mathrm{match}}\cap\mathcal W_+|&=24,\\
|\mathcal C_J^{\mathrm{match}}\cap\mathcal W_-|&=24,\\
|\mathcal C_J^{\mathrm{match}}\cap\mathcal W_+\cap\mathcal W_-|&=0,\\
|\mathcal C_J^{\mathrm{match}}\cap(\mathcal W_+\cup\mathcal W_-)|&=48.
\end{aligned}
\tag{137.18}
$$

It contains **no stage-stationary patterns**, and **528** of its $576$ admitted patterns lie outside both fixed-translation classes.

**Proof.** Every stage-stationary pattern repeats the same response at each address and violates (M2). A pattern $H(j\mp n)$ satisfies both native matching conditions if and only if $H$ is a permutation, giving $4!=24$ patterns in each class. If a bijective $H$ satisfied both opposed translation laws it would obey $H(x)=H(x+2)$, contradicting injectivity on $\mathbb Z_4$. Therefore the classes do not overlap. $\square$

Of the 48 translating patterns, 16 also satisfy the zero-mixed-difference condition; the other 32 do not. Hence the three distinctions—complete matching, additive cross-stage identification, and diagonal translation—are **not equivalent**.

The owner's native matching requires change of response class at each address between distinct stages, but it does not require that any one identified response object move to a new address. The word *nonstationary* here means only that a response label at one address does not repeat across stages. It is not a physical assertion of motion, energy transport, or realized occurrence.

## 137.10. Symmetric support and the limits of realization

The admitted domain is invariant under arbitrary permutations of its address labels, stage labels, and response labels; accordingly it has no **privileged** stage order or address orientation until the owner separately supplies one. In a cyclic presentation, orientation reversal pairs the admitted positive- and negative-translation subclasses; (137.18) gives their equal **possible** counts.

A candidate symmetric background turbine can be included in each complete record by specifying a balanced complete-recurrence *signature* in a separate recurrence-comparison domain, as in Addendum 131. Such a signature is not inferred from the four Latin-square stages, and must not be confused with a realized equality of physical forward and reverse cycling.

Native possible matching does **not** establish

$$
N_+^{\mathrm{real}}=N_-^{\mathrm{real}},
\quad\text{a realized travelling wave},
\quad\text{or a physical clock frequency}.
\tag{137.19}
$$

If an admitted class $\mathcal K$ is physically realized, its occurrence and occupancy must be counted in a separate realized domain. Positive possible support is not positive realized occurrence. Likewise, equality of possible orientation counts does not require equal realized populations.

## 137.11. Recursive replacement and count preservation

Let $\mathcal H_J$ be an admitted **complete possible** enclosing domain, which may contain multiple finer realization presentations of the same receiving pattern. Let

$$
q:\mathcal H_J\longrightarrow\mathcal C_J^{\mathrm{match}}
\tag{137.20}
$$

be the enclosing-owned receiving read. A property of complete records is readable after replacement precisely if it is constant on the fibers of $q$, as in Addenda 120, 122, 132, and 136.

If $q$ retains the **complete response-incidence pattern** but forgets finer beat histories, the derangement classification and possible extension structure of that pattern remain meaningful. If $q$ retains only stage and address response histograms, every matching-admissible pattern has the same marginals (each response label once per row and column), so its particular cross-stage cycle type or translation membership is generally unreadable. The owner must not reconstruct those differences from marginals after the read has identified them.

The extension counts $2$ and $4$ count distinct complete compatible patterns for a particular two-stage native record. If a later boundary identifies some of those complete patterns, the new native count must be computed in the **new** count domain; the old count may survive only as appropriately retained fiber multiplicity. Neither exact projection nor cardinality equality should be assumed without the specified native identification.

## 137.12. Results and limits

**Established, conditional on (M1)–(M2) and the declared labeled native domains:**

1. Any two distinct stage comparisons are related by a fixed-point-free permutation of response classifications (Theorem 1).
2. Cross-stage correspondences satisfy exact common-owner composition and inverse identities (Theorem 2).
3. A two-stage correspondence has exactly $0$, $2$, or $4$ compatible complete extensions according to its permutation type (Theorem 3).
4. Precisely $576$ complete labeled response-incidence patterns are admitted, out of $4^{16}$ unrestricted patterns (Theorem 4).
5. With a one-pattern local native count, the admitted positive-extension classes have conditional logarithmic possibility difference $\ln2$; zero extension remains a zero raw count, not a finite logarithm.
6. Exactly $144$ matching patterns also obey Addendum 136's zero mixed-difference law; neither finite compatibility condition implies the other (Theorem 5).
7. Exactly $48$ admitted patterns have either fixed one-address-per-stage translation incidence; stage-stationary patterns are excluded, but $528$ nontranslation patterns remain admitted (Theorem 6).
8. Complete-incidence properties can survive loss of subordinate identity when the receiving read preserves them; marginal histograms alone do not generally preserve them.

**Not established:** The necessity of complete matching for all R²D backgrounds; a canonical four-class response alphabet; a physical recurrence period or rate; any rule choosing which admitted record occurs; a universal propagating mode, electromagnetic phase, Doppler shift, speed $c$, gravitational mass class, or $mc^2$.

These limits are substantive. The matching conditions are not primitive axioms already present in Part I, and the finite matching theorem must not be used to supply a wave law or physical realization by changing the meaning of its native pattern labels.

## 137.13. Next mathematical target

The new result asks for a more discriminating native question than whether symmetric recurrence permits a traveling phase. Complete matching gives a large, explicitly structured domain with genuine exclusions and unequal enclosing extension multiplicities, yet without any physical propagation premise.

**Next question:** Under which independently justified boundary-native distinguishability or recursive replacement conditions is *complete matching* itself an admissible or necessary enclosing classification, as opposed to one possible model among many?

A useful next finite audit would vary the prior matching requirements rather than impose a desired phase translation. For example, one could compare complete matching with partial matching, repeated-response allowance, or weighted compatible extensions, and determine which cross-stage restrictions survive. This would retain possibility as the object being proved and keep actual realization and physical calibration separate.

## Conclusion

An enclosing owner that independently requires complete native distinction across both address and recurrence-stage comparisons necessarily restricts how stages can be related. Its permitted cross-stage maps are derangements belonging to a composable comparison family; its complete enclosing extensions have exact multiplicities $0$, $2$, and $4$. These consequences arise from the native matching specification, not from a preassigned phase-propagation law.

The central unitless result is

$$
\boxed{
\begin{gathered}
\text{enclosing-owned native complete matching (M1)–(M2)}\\
\Downarrow\\
\text{cross-stage derangements and coherent compositions}\\
\Downarrow\\
\Theta_J(b)\in\{0,2,4\},\qquad
|\mathcal C_J^{\mathrm{match}}|=576.
\end{gathered}}
\tag{137.21}
$$

The first line is a **declared enclosing possibility condition**, not a universal theorem of Part I. All subsequent arrows are mathematically proved for that condition. The result concerns admitted complete records only. It does not determine which possibility nature realizes.

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*. Authoritative scientific revision September 25, 2026. Native distinguishability, enclosing compatible extension, possibility versus occurrence, and finite recurrence comparison. <https://r2dscience.github.io/r2d-canon-publication/canon/part-i.html>
2. R²D Part II — *Joint Readability of Recurrence and Distinguishability*. Downstream physical calibration. <https://r2dscience.github.io/r2d-canon-publication/canon/part-ii.html>
3. R²D Part III — *The Recursive Clock and the Horizons of Readability*. Complementary quantum and gravitational read limits. <https://r2dscience.github.io/r2d-canon-publication/canon/part-iii.html>
4. R²D Part IV — *Projection: The Physics Constructed from What Remains*. Downstream physical projection, distinct from native admissibility. <https://r2dscience.github.io/r2d-canon-publication/canon/part-iv.html>
5. R²D Addenda 120 and 122 — Boundary-owned identification and enclosing compatibility across recursive comparisons.
6. R²D Addendum 131 — *Symmetric Background Before Turbine Recurrence*.
7. R²D Addendum 135 — *The Admissible Structures of Symmetric Recurrence*.
8. R²D Addendum 136 — *Native Identification Constrains Symmetric Recurrence*.
