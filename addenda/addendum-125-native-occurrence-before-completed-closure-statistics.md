---
r2d_id: "addendum-125"
title: "Addendum 125 — Native Occurrence Before Completed-Closure Statistics"
subtitle: "Proportional Realization, Across-Boundary Recurrence, and the Markov Projection"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 125
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

# R²D Addendum 125 — Native Occurrence Before Completed-Closure Statistics

*Proportional Realization, Across-Boundary Recurrence, and the Markov Projection*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 revision); Addenda 103–108, 120–121  
**Companion addenda:** Addendum 122, *Enclosing Compatibility Before Categorical Composition*; Addendum 123, *Enclosing Possibility Before Model-Based Decision*; Addendum 124, *Enclosing Recurrence Before Competing Closure Counts*  
**Scope:** Finite boundary-owned completed-closure configurations; state occurrence; completed recurrence; exact count correspondences; conditional aggregate recurrence laws; limitations of Markov representations

## Abstract

Recursively Realized Distinguishability (R²D) defines native possible multiplicity at an enclosing count boundary before any subordinate realization is counted. Addendum 124 established that a complete enclosing compatibility relation can determine the native multiplicity landscape of competing closure-count configurations, its exact count-weighted incidences, and even the completed-count direction shared by every admissible configuration. Those possible-count results are not, by themselves, measurements of completed physical recurrences.

This addendum determines the additional mathematical relations needed to connect that landscape to realized completed-closure statistics. Part I postulates proportional realization of **state-occurrence counts** from native multiplicity and separately defines **whole-closure recurrence counts** in a shared recurrence-comparison domain. We preserve that separation. For an enclosing boundary whose readable states classify complete configurations with $k$ closures of mode $\alpha$ and $M-k$ of mode $\beta$, let $W_*(k)$ be native multiplicity, $\nu_*(k)$ realized state occurrences, and $T_k$ completed recurrences of those entire configurations. An explicit complete-recurrence correspondence gives the exact identities

$$
N_\alpha=\sum_k kT_k,\qquad N_\beta=\sum_k(M-k)T_k.
$$

If $T_k=b_k\nu_*(k)$, the realized closure ratio is exactly a recurrence-weighted read of the state-occurrence landscape. If the correspondence factors $b_k$ are common across the readable classes and Part I's proportional occurrence-realization postulate applies, the aggregate recurrence ratio approximately equals the native count-weighted incidence ratio. In Addendum 124's explicitly specified product-compatible six-position boundary, this gives a conditional 2:1 completed-closure ratio without introducing a stochastic transition kernel.

A finite counterexample shows why the correspondence cannot be omitted: the same native multiplicities and the same state-occurrence counts can accompany different completed-recurrence ratios. The canonical recurrence-weighted R²D law supplies additional cross-boundary constraints only for valid representative closures and their corresponding enclosing transitions; it does not authorize summing competing modes into an enclosing occurrence or identifying recurrence with occupancy. Markov frequencies are possible projections of realized counts, not the primitive source of the enclosing compatibility structure or a selector of individual occurrences.

The result is a conditional recurrence-distribution theorem, accompanied by an exact underdetermination result. It identifies what R²D already determines, the boundary mapping required to obtain physical closure statistics, and an independent finite test of that mapping.

## 125.1. The question and the order of definition

The problem is not to invent a microscopic rule that chooses between two subordinate closures. R²D's defining order is already given in Part I:

$$
\chi_{n+1}^{(r)}\Longrightarrow
(\mathcal C_{n,a})_{a\in I_n}\in\mathfrak D_{n+1,\chi}.
$$

The enclosing occurrence determines its compatible joint subordinate realizations. Under recursive carry, a completed subordinate closure is reclassified relative to the enclosing boundary; its subordinate state identity need not persist. The recurrence law then compares two readings of one recursively organized realization rather than treating the subordinate histories as its causal source.

Addendum 124 asked a prior question: *which complete recurrence configurations can an enclosing boundary admit, and how many distinct native realizations belong to each readable closure-count class?* It answered that question using finite counting alone.

The present question is different:

**When does the enclosing native distribution of complete closure-count configurations determine the aggregate counts of closures that actually complete?**

The answer must keep distinct (i) possible configurations, (ii) occurrences of readable configuration states, (iii) structural occupancy, and (iv) completed whole-closure recurrences. No equality among these count types is assumed from a shared numerical value.

## 125.2. The four count domains

Let $B_*$ be a specified enclosing count boundary with finite native domain $\mathfrak M_*$ and readable classification

$$
\pi_*:\mathfrak M_*\longrightarrow\mathcal K_*,\qquad
\mathcal K_*\subseteq\{0,1,\ldots,M\}.
$$

Each admitted native realization at this boundary is a **complete jointly compatible configuration** of $M$ closure positions, and $\pi_*(\mu)=k$ reads $k$ completed-closure positions of type $\alpha$ and $M-k$ of type $\beta$. These positions are elements of the enclosing comparison specification, not a primitive physical time coordinate or persistent microscopic particles.

**Native possible count.** For each supported readable class,

$$
\boxed{W_*(k)=|\pi_*^{-1}(k)|.}
\tag{125.1}
$$

**State occurrence.** In a specified finite occurrence-realization domain $\mathcal D_O$, let $\nu_*(k)$ count realized occurrences classified as state $k$. Part I's proportional occurrence postulate relates its *relative* structure to $W_*(k)$, in a sufficiently resolved realization domain. It does not equate $\nu_*(k)$ and $W_*(k)$.

**Structural occupancy.** Let $c_*(k)$ denote the corresponding structural occupancy read. Its relative realization depends on enclosing possibility and productive retention and must not be inferred merely by tallying occurrences of state $k$.

**Completed recurrence.** In a fixed, jointly defined recurrence-comparison domain $\mathcal D_R$, let $T_k$ count completed recurrences of an **entire configuration** belonging to class $k$. Let $N_\alpha$ and $N_\beta$ count its subordinate completed closures of each mode, when the complete-recurrence specification permits those incidences to be assigned.

A class label $k$ may be a readable state without itself being one completed recurrence. Equally, one realized state occurrence need not be identified one-to-one with a whole-configuration recurrence. The mapping must be stated.

## 125.3. The exact recurrence-incidence theorem

**Definition 1 — Complete-recurrence correspondence.** Say that a recurrence-comparison domain has an *exact complete-configuration correspondence* when all of the following hold:

1. Every counted full-configuration recurrence has one declared readable class $k$, owned by the same $B_*$ specification.
2. Every such completed configuration has exactly $k$ counted $\alpha$ closures and $M-k$ counted $\beta$ closures within the declared subordinate incidence comparison.
3. Every subordinate closure included in $N_\alpha$ or $N_\beta$ belongs to exactly one counted full-configuration recurrence; the same closure is not duplicated across comparison presentations.
4. The comparison does not assume that the subordinate native identities survive as identical native states at $B_*$. Only the stated complete-configuration incidence read is retained.

These are explicit conditions on a proposed physical count mapping. They are not automatic consequences of merely writing down a formal product of closure labels.

**Theorem 1 — Exact completed-closure incidence.** Under Definition 1,

$$
\boxed{
N_\alpha=\sum_{k\in\mathcal K_*}kT_k,
\qquad
N_\beta=\sum_{k\in\mathcal K_*}(M-k)T_k.
}
\tag{125.2}
$$

Consequently,

$$
\boxed{N_\alpha+N_\beta=M\sum_kT_k.}
\tag{125.3}
$$

For positive $N_\beta$,

$$
\boxed{
\frac{N_\alpha}{N_\beta}
=\frac{\sum_k kT_k}{\sum_k(M-k)T_k}.
}
\tag{125.4}
$$

**Proof.** Every full-configuration recurrence of class $k$ contributes exactly $k$ and $M-k$ subordinate completed closures to the two specified incidence counts. Summing over the $T_k$ complete recurrences and invoking the nonduplication and exhaustion conditions gives Equation (125.2). Their sum gives Equation (125.3), and division gives Equation (125.4). $\square$

This theorem is exact and finite. It contains no sampling postulate or stochastic transition kernel. Its conclusions are **conditional on the complete-recurrence mapping**, not on a bottom-up summation principle that produces the enclosing occurrence. It tallies how an enclosing-owned set of completed recurrences is read subordinately.

## 125.4. The state-occurrence-to-recurrence correspondence

Theorem 1 still contains $T_k$, not $\nu_*(k)$. This distinction is not optional: Part I defines state occurrences and whole-closure recurrences separately.

For supported classes with $\nu_*(k)>0$, define the measured or independently specified correspondence factor

$$
\boxed{b_k=\frac{T_k}{\nu_*(k)}.}
\tag{125.5}
$$

If $\nu_*(k)=0$ in the chosen domain, a complete mapping must separately say whether $T_k=0$; otherwise the relation cannot be represented by a finite $b_k$ for that class.

With the positive-count convention, substitution into Theorem 1 gives the exact identity

$$
\boxed{
\frac{N_\alpha}{N_\beta}
=\frac{\sum_k k\,b_k\nu_*(k)}
{\sum_k(M-k)b_k\nu_*(k)}.
}
\tag{125.6}
$$

The factors $b_k$ are **not** probabilities, primitive rates, state-multiplicity corrections, or a new R²D postulate. They state how two already distinguished count domains correspond. A physical construction may supply them through an exact matching of complete occurrences and completed recurrences; it may also fail to supply them, in which case the aggregate recurrence ratio remains only partially determined.

A particularly clear case is a *class-independent complete-recurrence correspondence*:

$$
\boxed{b_k=b>0\quad\text{for every supported class}.}
\tag{125.7}
$$

Then $b$ cancels from Equation (125.6):

$$
\frac{N_\alpha}{N_\beta}
=\frac{\sum_k k\nu_*(k)}{\sum_k(M-k)\nu_*(k)}.
\tag{125.8}
$$

One full-configuration recurrence per counted state occurrence, $b=1$, is a sufficient special case, but not a canonical requirement. A common nonunit factor is equally sufficient for the ratio. The physical mapping must establish the commonality rather than fit it after observing the desired ratio.

## 125.5. Conditional aggregate recurrence-realization theorem

Part I, Section 3.4 and Appendix A.4, postulates proportional *state occurrence* realization. For the supported readable classes of $B_*$, in one fixed and sufficiently resolved realization relation,

$$
\boxed{
\frac{\nu_*(k)}{\nu_*(\ell)}
\approx\frac{W_*(k)}{W_*(\ell)}.
}
\tag{125.9}
$$

This is not an exact finite-sample equality, a stochastic choice rule, or a direct recurrence law.

**Theorem 2 — Conditional aggregate completed-closure realization.** Suppose:

1. The complete native count specification $(\mathfrak M_*,\pi_*)$ is physically admissible, and $W_*(k)$ counts distinct native realizations rather than comparison presentations.
2. The readable configuration classes and a fixed realization domain satisfy Part I's proportional state-occurrence postulate.
3. Definition 1 holds in the matching complete-recurrence domain.
4. The occurrence-to-recurrence correspondence is class independent, as in Equation (125.7).
5. Both aggregate counts are positive.

Then

$$
\boxed{
\frac{N_\alpha}{N_\beta}
\approx
\frac{\displaystyle\sum_k kW_*(k)}
{\displaystyle\sum_k(M-k)W_*(k)}.
}
\tag{125.10}
$$

**Proof.** Equation (125.7) removes the common correspondence factor from the exact recurrence identity (125.6). In the sufficiently resolved domain of Postulate 1, the relative occurrence counts $\nu_*(k)$ approximate a common positive multiple of $W_*(k)$. Substituting this relative structure into Equation (125.8) cancels that common multiplier and yields Equation (125.10), subject to the finite-realization approximation. $\square$

The right-hand side is an **exact count-weighted incidence ratio of possible native configurations**. The left-hand side is an **observed completed-recurrence ratio**. Their correspondence is approximate because the realization postulate is approximate, even though the complete-configuration incidence identity is exact.

This is a derivation from R²D's existing realization postulate plus an explicit physical count mapping—not an attempt to derive that postulate from pure combinatorics.

## 125.6. The six-position result: from native 2:1 to completed 2:1

Addendum 124 specifies one enclosing boundary $B_*$ that admits the entire six-position joint domain built from two $\alpha$-compatible and one $\beta$-compatible native labels per position. Its **complete native count**, under that explicitly declared product-compatible enclosing relation, is

$$
W_6(k)=\binom6k2^k,
\quad k=0,1,\ldots,6.
$$

The multiplicity vector is

$$
(W_6(0),\ldots,W_6(6))
=(1,12,60,160,240,192,64),
$$

with total $729$. Addendum 124's exact generating-function identity gives

$$
\sum_{k=0}^6 kW_6(k)=2916,
\qquad
\sum_{k=0}^6(6-k)W_6(k)=1458.
$$

Thus the **native possible-count incidence ratio** is exactly

$$
\frac{2916}{1458}=2.
$$

Under Theorem 2's independent physical mapping assumptions,

$$
\boxed{
\frac{N_\alpha}{N_\beta}\approx2.
}
\tag{125.11}
$$

No coin, molecular switch, or closure mechanism must count the complete landscape or decide which mode has the larger native incidence. That relation was defined at the enclosing boundary before realization. The completed closures are the subordinate expression of the realized enclosing configurations.

Three qualifications are essential. First, this is a *product-compatible enclosing boundary*; correlated enclosing relations need not give a binomial landscape. Second, $2:1$ is an approximate aggregate recurrence relationship under the postulate and mapping, not a claim that every finite sample has exactly twice as many $\alpha$ closures. Third, the fact that the most numerous native class has four $\alpha$ and two $\beta$ closures does not force every admitted complete occurrence to have that configuration. A further enclosing constraint could instead restrict the domain to a single supported class, yielding an exact within-configuration count as in Addendum 124.

## 125.7. Underdetermination when the correspondence is not fixed

It is possible to hold both the native count landscape and the realized *state occurrence* landscape fixed while changing the tally of completed recurrences.

**Theorem 3 — Native and state-occurrence counts do not uniquely determine completed-closure statistics.** In the absence of a specified complete-recurrence correspondence, two recurrence comparison domains may have identical $W_*(k)$ and $\nu_*(k)$ but different positive completed-closure ratios $N_\alpha/N_\beta$.

**Finite witness.** Take the same six-position native landscape and, as a particularly simple idealized realized occurrence domain, choose

$$
\nu_*(k)=W_6(k)
$$

for every $k$. This is an exact finite special case compatible with, but not required by, proportional realization.

In **comparison A**, suppose a complete configuration recurs once per counted state occurrence:

$$
T_k^{A}=\nu_*(k),\qquad b_k^A=1.
$$

The exact incidence identity gives

$$
(N_\alpha^A,N_\beta^A)=(2916,1458),
\qquad N_\alpha^A/N_\beta^A=2.
$$

In **comparison B**, retain the same native state domain and the same state-occurrence counts, but suppose the class $k=6$ contributes two completed full-configuration recurrences per counted state occurrence while the other classes contribute one:

$$
T_6^{B}=2\nu_*(6)=128,
\qquad T_k^{B}=\nu_*(k)\quad(k\ne6).
$$

Then

$$
(N_\alpha^B,N_\beta^B)=(2916+6\cdot64,1458)
=(3300,1458),
$$

and

$$
\boxed{
\frac{N_\alpha^B}{N_\beta^B}
=\frac{550}{243}\ne2.
}
$$

Both scenarios preserve $W_6$ and $\nu_*$; they differ in the stipulated whole-configuration recurrence mapping. $\square$

This is a **nonuniqueness example for the information supplied so far**, not a declaration that both mappings necessarily satisfy every additional physical R²D recurrence constraint. If the canonical recurrence law and an independent physical closure relation fix or rule out the class-dependent mapping in comparison B, they must be applied before accepting it as a physical realization.

The theorem establishes why Equation (125.11) cannot be asserted from native multiplicity and proportional state occurrence alone. An unknown $b_k$ can change the aggregate recurrence ratio even with the entire native and state-occurrence landscapes unchanged.

## 125.8. The canonical recurrence law supplies a different comparison

Part I defines, in a shared recurrence domain $\mathcal D_R$, completed recurrences of a representative subordinate closure $\mathcal C_{n,a}$ and the corresponding enclosing transition $\chi_{n+1}$. Its recurrence-weighted law is

$$
\boxed{
\Delta A_{n,a,\mathcal C}
N_{\mathcal D_R}(\mathcal C_{n,a})
=C_{n+1}\lambda_{n+1}
N_{\mathcal D_R}(\chi_{n+1}),
}
\tag{125.12}
$$

with $\Delta A_{n,a,\mathcal C}=\Delta P_{n,a,\mathcal C}-\Delta R_{n,a,\mathcal C}$. Equivalently,

$$
\Delta A_{n,a,\mathcal C}
=C_{n+1}\lambda_{n+1}\rho_{n+1\mid n,a}.
$$

These are the canonical cross-boundary recurrence counts, not automatically the $T_k$, $\nu_*(k)$, or $N_m$ of the constructed six-position comparison. A physical application must identify the relevant boundaries, representative closure, enclosing transition, and shared comparison domain. It must also show that the comparison is one of the kind for which Part I postulates Equation (125.12).

If two subordinate peers are **equivalent representatives of the same enclosing transition**, Part I permits equating their recurrence-weighted asymmetries. But mutually exclusive closure modes $\alpha$ and $\beta$ are not automatically equivalent representative peers; their modes cannot both be substituted for the same representative closure without proof of the required enclosing equivalence.

Where separate **mode-conditioned** representative comparisons are independently valid, they may obey

$$
\Delta A_m N_{\mathcal C_m}=Q_m M_m,
\qquad Q_m=C_m\lambda_m,
\qquad m\in\{\alpha,\beta\},
$$

where $M_m$ is the corresponding enclosing-transition recurrence count in that mode's valid comparison domain. For positive terms, this yields the conditional identity

$$
\boxed{
\frac{N_{\mathcal C_\alpha}}{N_{\mathcal C_\beta}}
=\frac{Q_\alpha}{Q_\beta}
\frac{\Delta A_\beta}{\Delta A_\alpha}
\frac{M_\alpha}{M_\beta}.
}
\tag{125.13}
$$

This equation does not determine $M_\alpha/M_\beta$ unless the relevant enclosing occurrence classification and realization comparison determine it. Nor does it authorize replacing $M_m$ with a native possible count or assuming the $Q_m/\Delta A_m$ ratios are equal.

There is therefore **no new additive R²D law** of the form $\Delta A_\alpha N_\alpha+\Delta A_\beta N_\beta=Q N_\chi$ established here. The apparent convenience of such a law would not justify changing the representative-peer meaning of Part I's recurrence equality.

Equations (125.10) and (125.13) are complementary conditions on a claimed physical mapping. The first connects native complete-configuration occurrence to aggregate mode incidences under a declared correspondence. The second links valid local and enclosing whole-recurrence readings. A proposed system should satisfy both **when both are applicable**, without selecting unmeasured factors afterward to make them agree.

## 125.9. Why structural occupancy is not the same statistic

A further enclosing boundary $B_+$ may determine the compatible extensions of the $B_*$ configuration classes. Let

$$
\Theta_{+\mid *,k}
$$

count the distinct native enclosing realizations compatible with class $k$. Under Part I's proportional occurrence and asymmetry-biased occupancy postulates, the relative *structural occupancy* satisfies

$$
\boxed{
\frac{c_*(\ell)}{c_*(k)}
\approx
\frac{\Theta_{+\mid *,\ell}}{\Theta_{+\mid *,k}}
 e^{-\Delta R_{k\to\ell}}.
}
\tag{125.14}
$$

The $\Theta$ counts here belong to $B_+$'s enclosing-compatible domain; they are not the native $W_*(k)$ merely because both are possible counts. The retention difference is the productive R²D constraint read, not an engineered cost function assigned after observing the result.

An observed series of visits to a state, durations of occupancy, complete configuration recurrences, and subordinate closure completions may yield different numerical ratios. The R²D canon distinguishes them for this reason. One cannot validate Equation (125.10) by replacing $\nu_*(k)$ with measured $c_*(k)$, nor validate Equation (125.14) by replacing occupancy with $N_{\mathcal C_m}$.

These are distinct quantitative tests of one enclosed recursive organization.

## 125.10. Markov statistics as a subsequent projection

A Markov description may be assigned after readable states and admitted transition classes have been specified. It can be useful and quantitatively correct without being the primitive source of those classifications.

For an observed set of transitions from readable state $i$ to $j$, a normalized **empirical transition read** can be defined where its denominator is positive:

$$
\widehat K_{ij}
=\frac{N_{i\to j}}{\sum_\ell N_{i\to\ell}}.
\tag{125.15}
$$

This definition turns counted realized transitions into normalized conditional frequencies. It does not assert that a Markov property holds for the selected state descriptions, or that $\widehat K_{ij}$ causes an occurrence. It also does not identify a counted leg transition with a completed closure recurrence.

Addendum 107's Bernoulli–Laplace construction shows why the ordering matters. With ten local binary objects in a hundred-object ensemble constrained to 60 tails, the exact enclosing-compatible count ratio between local states six and five is $275/216$. A particular exchange kernel reproduces the same ratio as its stationary state-weight ratio. Other kernels can have the same stationary relation while differing in their transition and recurrence behavior. The successful calculation therefore does not make its transition weights the origin of the enclosing multiplicity landscape.

Similarly, Equation (125.10) derives **aggregate completed-closure support** from an enclosing native count relation together with declared realization and recurrence mappings. It does not predict an exact individual closure sequence, require a microscopic chooser, or postulate a transition matrix. An observed Markov approximation may describe some aspects of the completed sequence, but its existence or absence does not reverse the boundary-first definition of the counts.

## 125.11. An independently testable finite physical mapping

The following protocol distinguishes the mathematical theorem from its physical mapping.

**First, fix the enclosing count owner.** Identify a physical boundary whose compatible native realizations are complete joint closure configurations, and establish whether its $k$-classification is physically readable. Enumerate $W_*(k)$ without using the observed closure-frequency distribution as a fitting target. If such a boundary cannot be established, the finite construction remains a comparison model rather than a native physical count mapping.

**Second, distinguish the realization reads.** In separately declared but related domains, measure $\nu_*(k)$, $c_*(k)$, completed full-configuration recurrences $T_k$, and subordinate completed closures $N_\alpha,N_\beta$. Record the correspondence between complete configuration recurrences and their subordinate incidences without duplicating the same physical completion in different presentations.

**Third, test the mapping rather than assume it.** Determine whether a class-independent $b_k=T_k/\nu_*(k)$ is warranted by the physical recurrence comparison. The special prediction $N_\alpha/N_\beta\approx2$ is appropriate for the product-compatible six-position system only when this and the other conditions of Theorem 2 are independently satisfied.

**Fourth, check the canonical recurrence law.** For every claimed representative closure/enclosing-transition pair, identify the shared $\mathcal D_R$, the actual completed recurrences, and the separately specified $\Delta P,\Delta R,C,\lambda$. Test the recurrence-weighted equality without fitting a new ratio from the measured aggregate closures.

**Fifth, test alternative enclosures.** Hold the one-position native alternatives fixed while changing the complete enclosing compatibility relation. Addendum 124 predicts that full-product and correlated enclosing specifications can have different native recurrence-count landscapes. Their realized count statistics should be compared using the corresponding independently specified occurrence and recurrence mappings, not assumed to follow a universal binomial law.

These are discriminating tests because a failure of the product-compatible native count formula challenges the proposed enclosing compatibility/native-identification specification; a failure of proportional $\nu$-to-$W$ realization challenges the relevant application of Postulate 1; and a class-dependent or incompatible recurrence mapping prevents the simplified aggregate conclusion even when the native combinatorics are correct. The errors should not be absorbed by redefining the count owner or fitting $b_k$ post hoc.

## 125.12. Results, limits, and conclusion

The addendum establishes five results.

**Result 1 — Exact recurrence incidence.** Once a complete enclosing-to-subordinate recurrence correspondence is specified, aggregate completed closure counts are exact incidences of completed enclosing configurations, Equation (125.2). This is an accounting of one enclosing-owned realized relation, not a bottom-up construction of that relation.

**Result 2 — Conditional realized aggregate ratio.** Under a valid native count boundary, proportional state-occurrence realization, and a class-independent occurrence-to-recurrence correspondence, aggregate completed-closure ratios approximately reproduce the corresponding native count-weighted incidence ratios, Equation (125.10).

**Result 3 — The six-position 2:1 reconstruction.** The product-compatible six-position system of Addendum 124 has an exact possible-count incidence ratio 2:1. Under Result 2's additional physical assumptions, its realized aggregate completed-closure ratio is approximately 2:1 without a primitive stochastic transition law.

**Result 4 — Underdetermination is exact.** Native multiplicity and even realized state-occurrence counts do not uniquely determine completed-recurrence counts when their cross-boundary correspondence remains unspecified. The finite counterexample in Section 125.7 exhibits two different realized recurrence ratios with the same possible and state-occurrence counts.

**Result 5 — The canonical recurrence law constrains but does not automatically identify the mappings.** Part I's representative-closure recurrence equality applies only in its specified comparison domain. It neither makes competing modes equivalent representative peers nor turns structural occupancy, state occurrence, and completed closure into one count type.

The conclusions are finite, conditional, and explicit about logical status. The exact combinatorial theorems of Addendum 124 concern what an enclosing boundary admits. Part I's realization postulates concern how native state counts are relatively realized and how enclosing asymmetry organizes occupancy. Its recurrence law connects different boundary-specific readings of completed closure. The present theorem links those distinct quantities **only where a complete physical recurrence correspondence has been independently established**.

No primitive Markov kernel, microscopic foresight, or probabilistic event selector is required to formulate these relations. Nor is a unique individual recurrence history derived from the native counts alone.

The central conclusion is:

$$
\boxed{
\begin{gathered}
\text{Enclosing compatibility defines the possible configurations;}\\
\text{native multiplicity defines their relative count structure;}\\
\text{realization and recurrence mappings determine}\\
\text{how those counts appear as completed physical closures.}
\end{gathered}
}
$$

**A system can realize a recurrence distribution organized by enclosing possibility without its subordinate events evaluating that possibility.** An explicit world-model controller is one mechanism for *reading* compatible alternatives and selecting an action; the R²D count relations do not require an analogous microscopic decision-maker. The empirical question is whether an independently specified physical boundary and recurrence mapping reproduce the quantitative realized counts.

---

## Appendix A — Exact finite verification

| Verification | Required result |
|---|---|
| Product-compatible six-position native landscape | $W_6=(1,12,60,160,240,192,64)$ |
| Total possible complete native realizations | $\sum_kW_6(k)=729$ |
| Native α incidence | $\sum_k kW_6(k)=2916$ |
| Native β incidence | $\sum_k(6-k)W_6(k)=1458$ |
| Native incidence ratio | $2916/1458=2$ |
| Common $b_k$, ideal proportional occurrence | Aggregate recurrence ratio $2$ |
| Alternative $b_6=2$, all other $b_k=1$, with $\nu_*=W_6$ | $N_\alpha=3300,\ N_\beta=1458$ |
| Alternative recurrence ratio | $3300/1458=550/243$ |
| Exact incidence conservation | $N_\alpha+N_\beta=6\sum_k T_k$ |
| Independent count-type check | $W_*,\nu_*,c_*,T_k,N_m$ remain distinct quantities |

The product-count identities can be verified by direct enumeration or generating functions. The two recurrence mappings in the counterexample are deliberately different stipulated mappings; they are not asserted to be two independently verified physical realizations of the same complete R²D recurrence relation.

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*. Authoritative Markdown revision, September 25, 2026. Especially Sections 3.2–3.9, Appendix A.4, and Appendix B.16. https://r2dscience.github.io/r2d-canon-publication/canon/part-i.html
2. R²D Addendum 103 — *The Causal Implications of the Microstate Definition*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-103-the-causal-implications-of-the-microstate-definition.html
3. R²D Addendum 104 — *The Count Relation Survives Before State Identity*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-104-the-count-relation-survives-before-state-identity.html
4. R²D Addendum 105 — *The Observational Inversion*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-105-the-observational-inversion.html
5. R²D Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-107-possibilities-pull-probabilities-do-not-push.html
6. R²D Addendum 108 — *A Branch Is Not an Occupied World*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-108-a-branch-is-not-an-occupied-world.html
7. R²D Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-120-boundary-owned-identity-and-the-algebra-of-recursive-replacement.html
8. R²D Addendum 121 — *Nested Wells, Compatibility, and Harmonic Structure*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-121-nested-wells-compatibility-and-harmonic-structure.html
9. R²D Addendum 122 — *Enclosing Compatibility Before Categorical Composition*.
10. R²D Addendum 123 — *Enclosing Possibility Before Model-Based Decision*.
11. R²D Addendum 124 — *Enclosing Recurrence Before Competing Closure Counts*.
