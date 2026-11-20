---
r2d_id: "addendum-122"
title: "Addendum 122 — Enclosing Compatibility Before Categorical Composition"
subtitle: "Across-Boundary Relations, Native Counts, and Represented Possibilities"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 122
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

# R²D Addendum 122 — Enclosing Compatibility Before Categorical Composition

*Across-Boundary Relations, Native Counts, and Represented Possibilities*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 revision); Addenda 107, 108, 120, and 121  
**Scope:** Finite boundary-owned count domains; comparisons across distinct native domains; relational and categorical composition; the distinction between native possibility and model-generated alternatives

## Abstract

Recursively Realized Distinguishability (R²D) defines a microstate as one compatible joint realization of the immediately subordinate peers, relative to an enclosing count boundary. Its multiplicity is a native count, not a count of descriptions, model trajectories, or completed occurrences. Enclosing-compatible multiplicity separately determines the possibility available to a local state. Recursive replacement changes native state identity rather than carrying a persistent microscopic object through successive descriptions.

This addendum asks whether relations among distinct boundary-native domains can be composed mathematically without confusing that composition with the enclosing relation that determines what is admissible. The answer is conditional. Relational and categorical constructions can represent across-boundary comparisons, but their ordinary composition need not preserve enclosing compatibility. A finite join theorem identifies the exact obstruction: projecting a complete three-boundary relation into two adjacent relations and recomposing them admits every pair sharing an intermediate label. The recomposition is exact precisely when each intermediate fiber already contains all such cross-pairs.

Crucially, the erroneous composite can preserve the full target native image and every target readable multiplicity while altering which enclosing realizations are compatible with a particular local state. In an explicitly specified adjacent-boundary count example, this changes the R²D possibility difference even though the enclosing native count is unchanged. Correct native multiplicity therefore does not imply correct directional possibility.

Addendum 120 already supplies the general native-identification and factorization tests; those results are used here rather than reproved as new theorems. Category theory describes admissible mathematical forms of comparison, while R²D supplies the boundary-owned count and causal interpretation. Learned world models likewise represent alternatives but do not, by generating a branch, establish a native microstate or an occupied future. The addendum establishes a test for such mappings, not an inference that any existing predictive model computes physical R²D possibility.

## 122.1. The question and its causal ordering

At a specified boundary $B_n$, a macrostate is a readable distinction and a native microstate is one compatible joint realization of immediately subordinate peers. The enclosing boundary determines both the admitted domain and its classification. Subordinate realization can change what is occupied; it does not create the multiplicity landscape in which occupancy is classified.

The question of this addendum is not how to find the smallest representation of that landscape. It is:

**When mathematical comparisons pass through several count boundaries, do they preserve the enclosing relation that defines what those comparisons mean?**

This question matters because three operations must not be interchanged:

1. Specifying compatible native realizations at a boundary.
2. Describing the relation among native domains belonging to different boundaries.
3. Composing the mathematical descriptions of that relation.

The first is the R²D count specification. The second and third can use relational algebra or category theory. Their mathematical usefulness does not reverse their logical dependence on the first.

## 122.2. The R²D count types that composition must respect

Let an enclosing boundary $B$ admit a finite native domain $\mathfrak M_B$ and a readable classification

$$
\pi_B:\mathfrak M_B\longrightarrow\mathcal M_B.
$$

For readable macrostate $s$,

$$
\boxed{W_B(s)=|\pi_B^{-1}(s)|},
\qquad
S_B(s)=\ln W_B(s)
$$

when the count is positive. Different presentations of one native realization do not add units to $W_B$; different native realizations belonging to the same readable class do.

For a local boundary $B_n$ and its specified immediately enclosing boundary $B_{n+1}$, Part I defines the compatible enclosing class

$$
\mathcal E_{n+1\mid n,i}
=\{\mu\in\mathcal U_{n+1}:\mu\sim i_n\},
\qquad
\Theta_{n+1\mid n,i}=|\mathcal E_{n+1\mid n,i}|.
$$

Here the members of $\mathcal U_{n+1}$ are distinct realizations in the *enclosing native count domain*. The count is not the number of comparison records relating that domain to a subordinate description. For positive $W_{n,i}$ and $\Theta_{n+1\mid n,i}$,

$$
K_{n+1\mid n,i}=\frac{\Theta_{n+1\mid n,i}}{W_{n,i}},
\qquad
P_{n,i}=\ln K_{n+1\mid n,i}.
$$

For local alternatives $i\to k$,

$$
\boxed{
\Delta P_{n,i\to k}
=\ln\!\left(
\frac{\Theta_{n+1\mid n,k}/W_{n,k}}
{\Theta_{n+1\mid n,i}/W_{n,i}}
\right)
}.
$$

This is compatible *possibility*, not a prediction that one particular occurrence must happen. The local asymmetry additionally depends on retention, $\Delta A=\Delta P-\Delta R$. The ordering and the different roles of possibility, probability, and occurrence are established in Part I and Addendum 107.

Across boundaries, Part I distinguishes an enclosing occurrence determining compatible subordinate closures,

$$
\chi_{n+1}^{(r)}\Longrightarrow
(\mathcal C_{n,a})_{a\in I_n},
$$

from recursive carry,

$$
\mathcal C_{n,a}\overset{\kappa_n}{\mapsto}\chi_{n+1}^{(r)}.
$$

Carry denotes boundary-relative reclassification, not causal construction of an enclosing object out of persistent subordinate objects. It follows that native domains at different boundaries need not be connected by state-preserving functions.

## 122.3. Enclosing-owned comparisons across distinct native domains

Consider recursively related boundaries

$$
B_0\prec B_1\prec B_2
$$

with separate native domains

$$
A=\mathfrak M_0,\qquad
X=\mathfrak M_1,\qquad
Z=\mathfrak M_2.
$$

The recursive order denotes enclosure, not temporal succession or an assertion that one native object persists across all three boundaries.

A common enclosing comparison owner $L$ supplies a complete admitted relation. For a transparent finite example, suppose its comparison records can be identified with distinct triples in

$$
\boxed{\Gamma_L\subseteq A\times X\times Z}.
$$

A triple $(a,x,z)$ asserts compatibility of three boundary-specific *reads within one enclosing comparison*. It is not a trajectory of one physical object through three state spaces. A more general comparison may contain additional enclosing context and several records with the same triple; the native-identification treatment of Section 122.7 covers that case.

Project the admitted relation to its two adjacent descriptions:

$$
R_{01}=\{(a,x):\exists z\ (a,x,z)\in\Gamma_L\},
$$

$$
R_{12}=\{(x,z):\exists a\ (a,x,z)\in\Gamma_L\}.
$$

Ordinary relational composition through $X$ constructs the join

$$
\boxed{
J_X(\Gamma_L)=
\{(a,x,z):(a,x)\in R_{01},\ (x,z)\in R_{12}\}
}.
$$

Every originally admitted triple belongs to this join. The converse does not follow. Matching an intermediate native label is a mathematical condition; it is not, by itself, the enclosing owner's complete admissibility rule.

## 122.4. The enclosing join theorem

**Theorem 1 — Exactness of adjacent relational composition.**  
For each $x\in X$, define

$$
A_x=\{a:\exists z\ (a,x,z)\in\Gamma_L\},
\qquad
Z_x=\{z:\exists a\ (a,x,z)\in\Gamma_L\},
$$

and

$$
\Gamma_x=\{(a,z):(a,x,z)\in\Gamma_L\}.
$$

Then:

1. $\Gamma_L\subseteq J_X(\Gamma_L)$.
2. The adjacent projections and the global source and target images of $\Gamma_L$ and $J_X(\Gamma_L)$ are identical.
3. The adjacent composition is exact, $J_X(\Gamma_L)=\Gamma_L$, if and only if

$$
\boxed{\Gamma_x=A_x\times Z_x\quad\text{for every }x\in X}.
$$

**Proof.** Every complete admitted triple projects to an admitted pair in each adjacent relation, establishing (1). By construction, the join uses exactly the pairs already present in $R_{01}$ and $R_{12}$, so projecting it back onto either adjacent domain reproduces those relations. Every source label in the join comes from $R_{01}$; every target label comes from $R_{12}$. Conversely, each such label occurs in some original triple. This gives (2).

For a fixed $x$, the join contains precisely $A_x\times\{x\}\times Z_x$, while the complete enclosing relation contains precisely $\Gamma_x$ at that label. Equality holds for the entire relation if and only if the two agree at every $x$, giving (3). $\square$

The theorem does not require the enclosing relation to be rectangular. Rather, it says that *unrestricted composition through the intermediate label is justified only when rectangularity has already been supplied by the enclosing relation*.

**Corollary 1.1 — Target-count agreement does not establish compatibility agreement.**  
Let $\pi_2:Z\to\mathcal M_2$ be the fixed target readable classification. Define the represented target-native count for any relation $R\subseteq A\times X\times Z$ by

$$
W_2^{R}(s)=
|\{z\in\operatorname{pr}_Z(R):\pi_2(z)=s\}|.
$$

Then

$$
\boxed{W_2^{\Gamma_L}(s)=W_2^{J_X(\Gamma_L)}(s)}
$$

for every $s$, even when $J_X(\Gamma_L)\ne\Gamma_L$. If the comparison covers all of $Z$, these agree with the target boundary's canonical $W_2(s)$. Thus even equality of *every target native multiplicity* cannot certify that the composed relation preserves enclosing admissibility.

These are finite-set relational identities. Their significance for R²D is determined by the specified boundary ownership of $A$, $X$, $Z$, and $\Gamma_L$.

## 122.5. The three-boundary counterexample

Let

$$
A=\{a,b\},\qquad X=\{x\},\qquad Z=\{u,v\},
$$

and let the enclosing owner admit only

$$
\Gamma_L=\{(a,x,u),(b,x,v)\}.
$$

The two adjacent projections are

$$
R_{01}=\{(a,x),(b,x)\},\qquad
R_{12}=\{(x,u),(x,v)\}.
$$

Joining on $x$ generates

$$
J_X(\Gamma_L)=
\{(a,x,u),(a,x,v),(b,x,u),(b,x,v)\}.
$$

The combinations $(a,x,v)$ and $(b,x,u)$ have no enclosing admission. They arise from recombining true partial comparisons as though agreement on $x$ supplied the entire enclosing relation.

Yet both the correct and erroneous relations have target image $\{u,v\}$. For any fixed $\pi_2$, all represented target-native multiplicities agree. The intermediate boundary still has one native identity $x$; the spurious comparisons are not additional native states of $B_1$ or $B_2$.

The error is therefore **not necessarily a wrong count of target states**. It is the attribution of admissible relationships that the enclosing boundary does not define.

One may preserve the original enclosing relation explicitly as an admissibility predicate on the join. Alternatively, the owner may supply additional comparison context—for example, distinguish $(a,x,u)$ from $(b,x,v)$ with a shared context label. Such a label is a read of the complete comparison, not a newly discovered hidden microstate of $B_1$. Nothing requires selecting a smallest possible label set. The requirement is preservation of the specified enclosing relation.

## 122.6. From a compatibility error to an R²D possibility error

The preceding counterexample preserves target native counts. Does that mean a composition error is invisible to the R²D possibility relation? No. A local alternative's *compatible enclosing image* is a different count from the enclosing boundary's total native multiplicity.

For a supplied comparison relation $R$ and a source readable classification $\pi_A:A\to\mathcal M_A$, define the target-native extension image associated with local class $i$:

$$
\mathcal E_R(i)=
\{z\in Z:\exists a\in\pi_A^{-1}(i),\ \exists x\in X,
\ (a,x,z)\in R\}.
$$

Count distinct enclosing native identities, not the number of triples:

$$
\Theta_R(i)=|\mathcal E_R(i)|.
$$

**Theorem 2 — Compatibility-conditioned count sensitivity.**  
For the direct enclosing relation and its unrestricted adjacent join,

$$
\mathcal E_{\Gamma_L}(i)\subseteq\mathcal E_{J_X(\Gamma_L)}(i)
$$

for every $i$, although the unconditioned global target-native images are equal. The inclusion can be strict for some $i$. Consequently, equal global target-native multiplicities do not imply equal compatible-enclosing counts conditioned on a local alternative.

**Proof.** Inclusion of relations implies inclusion of each conditioned target image. Theorem 1 supplies equality of the global target image, but does not imply equality after restricting the source to a particular readable class. The example below gives strict inclusion. $\square$

For a numerical witness, take

$$
A=\{a,b\},\quad X=\{x\},\quad Z=\{u,v,w\},
$$

$$
\Gamma_L=\{(a,x,u),(b,x,v),(b,x,w)\}.
$$

Let $\pi_A$ distinguish $a$ from $b$. The correct and unrestricted-join counts are:

| Local class | Direct compatible target image | Direct count | Join compatible target image | Join count |
|---|---|---:|---|---:|
| $a$ | $\{u\}$ | $1$ | $\{u,v,w\}$ | $3$ |
| $b$ | $\{v,w\}$ | $2$ | $\{u,v,w\}$ | $3$ |

Both relations still have the same *global* target image $\{u,v,w\}$. If $u,v,w$ belong to one target readable class, that class has native multiplicity three in both descriptions.

To read these numbers as Part I's **adjacent-boundary** possibility, an additional physical count specification is required: $a,b$ must be the locally readable alternatives at $B_n$; $u,v,w$ must be distinct native realizations of its immediately enclosing $B_{n+1}$; and $x$ must serve only as a comparison interface for that one enclosing relation, not as a further intervening native boundary. Under that explicit specification,

$$
W_{n,a}=W_{n,b}=1,
$$

and the direct enclosing relation gives

$$
P_{n,a}=\ln 1=0,\qquad
P_{n,b}=\ln 2,
\qquad
\boxed{\Delta P_{n,a\to b}=\ln 2}.
$$

Substituting the incorrect join would give

$$
\widehat P_{n,a}=\widehat P_{n,b}=\ln 3,
\qquad
\boxed{\widehat{\Delta P}_{n,a\to b}=0}.
$$

The native local multiplicities and the complete target native multiplicity have not changed. Only the *assigned enclosing compatibility* has changed. Yet the computed directional possibility has disappeared.

If, instead, $x$ is itself the native state of an intervening boundary in $B_0\prec B_1\prec B_2$, the same table describes a **longer-range comparison**; one may not automatically rename its logarithmic ratio as the adjacent-boundary $P_{n,i}$ of Part I. The relevant native boundary pair and compatibility specification must first be declared. This prevents an attractive relational example from silently introducing a new R²D law.

The result also does not imply that a greater compatible count forces an occurrence. Retention and actual realization remain separate R²D relations.

## 122.7. Exact composition when comparisons have additional context

The triple relation is a transparent case, not the most general one. An enclosing owner may supply a candidate comparison domain $\mathcal D_L^0$, an admitted subset $\mathcal D_L$, and a target native-identification map

$$
\rho_L:\mathcal D_L\longrightarrow\mathfrak M_2.
$$

A complete response can include additional retained enclosing context $g_L$. Extend it over rejected candidates by

$$
F_L(d)=
\begin{cases}
\bot,&d\notin\mathcal D_L,\\
(\rho_L(d),g_L(d)),&d\in\mathcal D_L.
\end{cases}
$$

Let a proposed decomposition present complete candidates through a map $q_T:\mathcal D_L^0\to P_T$, where $P_T$ is a matching-pair or pullback presentation domain.

Addendum 120's factorization criterion applies directly: $F_L$ can be read from $q_T(d)$ alone if and only if

$$
\boxed{
q_T(d)=q_T(d')\Longrightarrow F_L(d)=F_L(d')
}.
$$

Factorization protects the response on presentations arising from complete candidates. It does not authorize every other element of $P_T$. Exact composition also requires rejecting matching pairs with no admitted complete enclosing comparison, representing every admitted complete comparison, and counting **distinct $\rho_L$ images** rather than presentation records.

**Proposition 3 — Native-count invariance under exact enclosing composition.**  
If a decomposition preserves the complete enclosing admission and target native-identification rule, has no admitted spurious presentations, and represents every complete admitted comparison, then its set of admitted target native images is the same as that of direct comparison. Hence each target readable fiber has the same native multiplicity. If the complete specification also preserves source-conditioned enclosing compatibility images, their compatible counts and any properly defined Part I possibility differences are unchanged.

**Proof.** Exact admission and completeness establish equality of the sets of admitted comparisons represented by the two descriptions, up to repetitions with the same specified native identity. Applying $\rho_L$ yields identical distinct target-native image sets. Restriction by the fixed target readable map preserves each native fiber count. Applying the same reasoning after restricting to a declared source-readable class gives equal compatible target images and counts. The possibility identity then follows by substitution into Part I's formula where that formula is defined. $\square$

This is a consequence of the native-identification and exact-gluing machinery in Addendum 120, now applied to across-boundary comparisons. It is not a new premise that subordinate states persist; nor is it a mandate to minimize the intermediate representation.

## 122.8. What category theory describes—and what it does not supply

A comparison between native domains may be represented as a span,

$$
\mathfrak M_i\xleftarrow{a_{ij}}D_{ij}
\xrightarrow{b_{ij}}\mathfrak M_j.
$$

The central domain consists of comparison records, not a population of persistent physical objects. Adjacent spans may be composed through a pullback over a declared common interface,

$$
D_{01}\times_{U_1}D_{12}.
$$

For correctly specified interfaces, pullback composition has its familiar associativity properties up to canonical isomorphism. But ordinary matching does not, on its own, impose $L$'s complete admissibility relation or target native-identification rule. The Section 122.5 counterexample displays that difference exactly.

There is no conflict in using category theory to express boundary-owned relations. Categories, spans, and pullbacks are mathematical languages for organizing objects and morphisms; they do not demand that each morphism be interpreted as a bottom-up physical cause. The distinction is one of *what a mathematical construction is being asked to establish*:

- A span represents a specified comparison.
- A pullback or relational composite describes matching comparison records.
- A native-identification map determines what those records count at a selected boundary.
- An enclosing admission relation determines which jointly represented possibilities are physically admissible **when a physical R²D mapping has been established**.

The mathematical structure does not independently derive the last two assignments. Conversely, R²D does not require forbidding any particular categorical representation. It requires that the representation not replace the count boundary that gives the states their identities.

## 122.9. Relation to world models and modeled future branches

A world model may generate a family $\Omega_{\mathrm{model}}$ of represented future scenarios, associate weights with them, and update the representation when observations change. Those operations can be useful without identifying their branches with R²D native microstates.

Let $\widehat\Gamma$ be a model's represented compatibility relation. Its scenario count

$$
N_{\mathrm{model}}(s)
=|\{\omega\in\Omega_{\mathrm{model}}:
\widehat\pi(\omega)=s\}|
$$

belongs to that model until a physical boundary mapping justifies some further interpretation. In particular, neither the cardinality of sampled branches nor their normalized weights independently determines $W_B$, $\Theta_{n+1\mid n,i}$, or actual occupancy.

Addendum 107 establishes that possible count, probability, and realized occurrence are different count types. Addendum 108 establishes that a branch of a representation is not an independently occupied world by virtue of branching alone. The same logical separation applies to counterfactual paths in planning, without claiming that automotive prediction and quantum branching are the same physical process.

The relevant research question is therefore not whether a planner discovers the coarsest sufficient scenario classes. It is whether a proposed **mapping** from its modeled alternatives to a specified physical count boundary preserves:

1. The boundary's native-identification rule.
2. The enclosing admissibility of the compared alternatives.
3. The compatible enclosing images of local states, where a possibility claim is made.
4. The distinction between represented alternatives and realized occurrences.

These are tests of a proposed mapping, not claims that existing world models already possess an R²D ontology. Optimization of an action is a subsequent planning choice, not the primitive R²D possibility law.

## 122.10. Independently specified enclosing owners

The results above assume one enclosing owner $L$, relative to which competing decompositions are checked. For independent enclosing owners $L$ and $L'$, categorical diagrams may connect their domains without establishing that they define the same admitted physical relation.

If the two descriptions *claim* to represent one and the same enclosing organization, they require a common comparison or a specified equivalence preserving admission, native-identification equivalence, readable classes, and all retained responses needed for that claim. Addendum 120's native-equivalence criterion gives a test when a common complete comparison is available.

R²D does **not** require arbitrary independent boundaries to be path independent or interchangeable. They may define different native domains and different compatible occurrences. Abstractly similar representations are therefore neither proof of identical physical organization nor evidence of inconsistency when their native reads differ.

The unresolved mathematical target is conditional: to characterize equivalence *where equivalence of enclosing organizations is claimed*, not to impose universal coherence on every possible boundary hierarchy.

## 122.11. Recurrence comparisons are a separate count type

For completeness, let $N_0,N_1,N_2>0$ be completed recurrence counts in one explicitly shared recurrence-comparison domain, with compatible representative closure classifications. Then

$$
\rho_{1\mid0}=\frac{N_1}{N_0},
\qquad
\rho_{2\mid1}=\frac{N_2}{N_1}
$$

imply the arithmetic identity

$$
\rho_{2\mid1}\rho_{1\mid0}=\frac{N_2}{N_0}.
$$

This is telescoping of comparable recurrence counts. It is not an independent theorem that the two enclosing compatibility specifications agree; it does not make native multiplicities multiply between boundaries and does not introduce a direct multi-boundary version of the R²D law. The recurrence-weighted R²D law of Part I remains tied to its specified compatible enclosing occurrence and representative subordinate closure.

## 122.12. Results, limits, and conclusion

The addendum establishes the following results within its declared finite comparison specifications:

**Result 1 — Enclosing admission is stronger than adjacent matching.** The join of two correct adjacent projections may introduce complete comparisons that the enclosing owner excludes. Exactness of this join has a necessary and sufficient fiber condition.

**Result 2 — Global native-count equality is weaker than compatibility equality.** Recomposition can preserve every target native image and readable multiplicity while changing which target realizations are compatible with a given local alternative.

**Result 3 — A compatibility error can alter the R²D possibility read.** When the direct and composed relations are explicitly mapped to the same adjacent local/enclosing count domains, an altered compatible-enclosing count changes $P$ and can erase a directional possibility difference without changing the native local or enclosing multiplicity landscape.

**Result 4 — Exact composition does not require persistent microstates.** Native identification, enclosing admission, and complete comparison coverage suffice to preserve the selected target's counts under a valid across-boundary comparison. Different boundaries may retain different native identities.

**Result 5 — Category theory and world models are representational comparisons, not alternative primitive count owners.** They can express relations and modeled alternatives; they do not, by that expressive capacity alone, specify physical native identity, enclosing compatibility, or occupancy.

These results are finite logical and combinatorial statements. They do not prove that a particular world model computes R²D possibility, that a chosen categorical construction is a physical mapping, or that all independently specified enclosing owners must be equivalent. Such claims require explicit boundary specifications and, where physical science is involved, testable observation-to-count mappings.

The organizing conclusion is:

$$
\boxed{
\begin{gathered}
\text{Enclosing compatibility defines admissibility;}\\
\text{native identification defines what is counted;}\\
\text{mathematical composition describes their relations.}
\end{gathered}
}
$$

**A relation can be composed mathematically without being created physically by its components.** Recursive comparison can preserve an enclosing count relation without requiring the subordinate native state identities to persist.

---

## Appendix A — Finite verification checks

All calculations in Sections 122.5–122.6 can be reproduced by enumerating finite triples.

| Check | Required result |
|---|---|
| Two-target direct comparison | Two admitted triples |
| Two-target adjacent join | Four triples, two inadmissible |
| Two-target global native image | $\{u,v\}$ under both relations |
| Three-target direct comparison | Three admitted triples |
| Three-target adjacent join | Six triples |
| Three-target global native image | $\{u,v,w\}$ under both relations |
| Condition on local $a$ | Direct $1$; unrestricted join $3$ |
| Condition on local $b$ | Direct $2$; unrestricted join $3$ |
| With $W_{n,a}=W_{n,b}=1$ at the specified adjacent boundary pair | Direct $\Delta P_{a\to b}=\ln 2$; incorrect join $0$ |

The examples establish existence of the stated failures. The general join criterion and count consequences follow from their proofs and do not depend on these particular labels.

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*. Authoritative revision, September 25, 2026. Especially Sections 3.2, 3.5, 3.8, and 3.9. https://r2dscience.github.io/r2d-canon-publication/canon/part-i.html
2. R²D Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-107-possibilities-pull-probabilities-do-not-push.html
3. R²D Addendum 108 — *A Branch Is Not an Occupied World*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-108-a-branch-is-not-an-occupied-world.html
4. R²D Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-120-boundary-owned-identity-and-the-algebra-of-recursive-replacement.html
5. R²D Addendum 121 — *Nested Wells, Compatibility, and Harmonic Structure*. https://r2dscience.github.io/r2d-canon-publication/addenda/addendum-121-nested-wells-compatibility-and-harmonic-structure.html
6. Finite relational algebra and category theory: projections, natural joins, spans, pullbacks, and factorization. These are mathematical comparison tools, not independent physical causal premises.
