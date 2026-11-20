---
r2d_id: "addendum-124"
title: "Addendum 124 — Enclosing Recurrence Before Competing Closure Counts"
subtitle: "Complete Recurrence Configurations, Native Multiplicity, and Directional Realization"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 124
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

# R²D Addendum 124 — Enclosing Recurrence Before Competing Closure Counts

*Complete Recurrence Configurations, Native Multiplicity, and Directional Realization*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 revision); Addenda 103–108, 120, and 121; revised Addendum 122  
**Scope:** Finite enclosing-owned recurrence configurations, two competing subordinate completed-closure modes, native multiplicity, compatibility-determined recurrence support, and the separation of possible count from realized recurrence

## Abstract

Recursively Realized Distinguishability (R²D) defines a native microstate through the compatible joint realizations admitted by its enclosing count boundary. An enclosing occurrence specifies which subordinate completed closures are compatible with it; subordinate closures do not generate the enclosing compatibility landscape. Yet two competing subordinate closure modes can remain compatible with the same enclosing occurrence. The relative counts of their possible realizations do not by themselves specify the completed recurrences of either mode.

This addendum asks what becomes mathematically determined when an additional enclosing boundary admits and distinguishes **complete configurations of repeated subordinate closures**. It begins with one enclosing occurrence compatible with three joint realizations: two supporting mode α and one supporting mode β. A separately specified six-position enclosing boundary that admits all joint combinations has a native count landscape

$$
W_6(k)=\binom{6}{k}2^k=(1,12,60,160,240,192,64),
$$

where $k$ counts α closures. Its largest native multiplicity belongs to the 4:2 configuration. An exact generating-function identity gives a 2:1 **count-weighted incidence ratio across possible configurations**, not a 2:1 realized recurrence ratio.

A second enclosing boundary can have the same admitted one-position alternatives but a different joint relation. When it admits only all-α or all-β configurations, the native multiplicity landscape is instead supported only at $k=6$ and $k=0$, with counts 64 and 1. Thus neither the one-position multiplicities nor a locally specified mechanism determines the complete recurrence landscape. The enclosing joint compatibility relation does.

For arbitrary finite enclosing relations, the supported count classes determine exact admissible ranges and may establish an α or β majority in *every* admitted complete realization without selecting any particular microscopic history. An enclosing condition fixing one count class can determine completed-closure totals exactly while retaining many different native realizations. These are theorems of finite count and compatibility, not postulates of stochastic selection or realized occurrence. Connecting their counts to physical recurrence observations remains the distinct task of the proportional realization and across-boundary recurrence relations in Part I, to be developed in Addendum 125.

## 124.1. The question: what does an enclosing recurrence boundary determine?

Part I separates possible multiplicity, state occurrence, structural occupancy, and completed closure recurrence. It also distinguishes an enclosing occurrence's compatibility relation from recursive carry. Causally,

$$
\chi_{n+1}^{(r)}\Longrightarrow
(\mathcal C_{n,a})_{a\in I_n}\in\mathfrak D_{n+1,\chi}.
$$

Under change of count boundary, a completed subordinate closure may be reclassified as the enclosing occurrence,

$$
\mathcal C_{n,a}\overset{\kappa_n}{\mapsto}\chi_{n+1}^{(r)}.
$$

These expressions are not opposed causal directions. They state, respectively, enclosing-defined compatibility and boundary-relative reclassification. A completed subordinate path need not persist as the same native state at the enclosing boundary.

The problem here is not which microscopic mechanism chooses α rather than β. It is:

**How much of a finite distribution of competing complete closure modes can the enclosing compatibility relation determine before any realization-frequency or recurrence-rate postulate is applied?**

The answer must distinguish four quantities:

1. Admitted **complete realizations** of an enclosing count specification.
2. Native multiplicity of each **readable completed-closure count class**.
3. Count-weighted incidences of α and β **over possible native realizations**.
4. Actual completed-closure recurrences in a specified **realization comparison domain**.

The first three may be determined by an explicit enclosing count boundary. The fourth is not obtained merely by renaming possible counts as realized counts.

## 124.2. The smallest competing-mode compatibility relation

Let an enclosing occurrence class $\chi$ admit two subordinate peers. The selected peer can complete one of two closure modes, α or β; the second peer has closure readings $p$ or $q$. Specify the complete admitted joint relation

$$
\boxed{\mathfrak D_\chi
=\{(\alpha,p),(\alpha,q),(\beta,p)\}.}
$$

The candidate $(\beta,q)$ is excluded by this enclosing specification. This domain is defined first; it is not obtained by assuming that independently completed subordinate events can be assembled in every combination.

For the present finite construction, specify that the three admitted joint realizations correspond to **three distinct native realizations** of the boundary that owns $\chi$. Denote them

$$
D=\{d_{\alpha p},d_{\alpha q},d_{\beta p}\},
$$

and let the comparison classification $m:D\to\{\alpha,\beta\}$ read the selected peer's closure mode. Then

$$
D_\alpha=m^{-1}(\alpha),\quad |D_\alpha|=2,
\qquad
D_\beta=m^{-1}(\beta),\quad |D_\beta|=1.
$$

Write these native-fiber sizes as

$$
\boxed{u_\alpha=2,\qquad u_\beta=1.}
$$

These are **possible-count fibers**. If the enclosing readable classification assigns all three realizations to the same macrostate $\chi$, that read does not uniquely identify the subordinate closure mode. Its multiplicity is $W_\chi=3$, while the mode comparison distinguishes 2 and 1 possibilities within that fiber. One must not silently promote the comparison label $m$ to an additional native macrostate of the same boundary.

In particular,

$$
\frac{u_\alpha}{u_\beta}=2
$$

is not, on its own, the realized recurrence ratio $N(\mathcal C_\alpha)/N(\mathcal C_\beta)$.

## 124.3. The complete enclosing recurrence specification

Now specify a **further enclosing comparison owner** $B_*$ for a complete organization of $M$ distinguishable closure positions. A position is a component of the declared comparison domain, not a physical time interval, a persistent particle, or a microscopic agent choosing a mode. The label $j\in\{1,\ldots,M\}$ identifies where a completed closure is compared within the whole.

The enclosing owner must supply:

1. A finite admitted complete joint domain $\mathfrak M_*$, together with its native-identification rule.
2. A complete read $h_*:\mathfrak M_*\to\{0,\ldots,M\}$, where $h_*(\mu)$ is the number of α-mode closures in the complete configuration.
3. The required compatibility among its closure positions, including any correlations or exclusions.

If the count $k=h_*(\mu)$ is a **readable macrostate distinction at $B_*$**, write $\pi_*=h_*$ and define

$$
\boxed{W_*(k)=|\pi_*^{-1}(k)|.}
\tag{124.1}
$$

The total compatible native domain has count

$$
\Theta_*=\sum_{k=0}^{M}W_*(k).
$$

For a single admitted configuration $\mu$, define its **within-configuration** completed closure counts by $n_\alpha(\mu)=h_*(\mu)$ and $n_\beta(\mu)=M-h_*(\mu)$. These are not yet the canonical aggregate recurrence counts $N_{\mathcal D_R}(\mathcal C_m)$ of Part I.

This is an enclosing-first specification: $B_*$ determines which whole configurations are admitted and which are native-distinct. A product or sequence notation used to enumerate them is **not** a claim that earlier completed lower-level objects causally construct the enclosing boundary. Conversely, neither existence nor readability of $B_*$ follows from $D$ alone. If no physical boundary actually supplies $h_*$ as a readable class and its native-identification rule, the enumeration remains a comparison count, not an established physical native multiplicity.

The following examples make those assumptions explicit.

## 124.4. The product-compatible enclosing relation

**Definition 1 — Full-product enclosing compatibility.** Let $D=D_\alpha\sqcup D_\beta$ be a finite native realization domain with positive fiber sizes $u_\alpha,u_\beta$. For a specified $M$-position boundary, assume the enclosing owner admits the complete joint relation

$$
\mathfrak M_*^{\mathrm{prod}}=D^M,
$$

identifies distinct admitted tuples as distinct native realizations, and reads the α-mode count

$$
\pi_*(d_1,\ldots,d_M)
=|\{j:m(d_j)=\alpha\}|.
$$

Full-product compatibility is a property of this **chosen enclosing relation**, not a universal independence law for physical recurrences.

**Theorem 1 — Product-compatible recurrence multiplicity.** Under Definition 1,

$$
\boxed{
W_M(k)=\binom{M}{k}u_\alpha^k u_\beta^{M-k},
\qquad 0\le k\le M.
}
\tag{124.2}
$$

Its generating polynomial is

$$
\boxed{
H_M(z)=\sum_{k=0}^{M}W_M(k)z^k
=(u_\beta+u_\alpha z)^M.
}
\tag{124.3}
$$

**Proof.** A complete admitted tuple containing exactly $k$ α positions has $\binom Mk$ choices of the α-position subset. Each chosen α position has $u_\alpha$ admissible native labels and each remaining β position has $u_\beta$. Because the enclosing relation admits precisely all such tuples and native identification distinguishes them, multiplication gives the stated native count. Summing the coefficients of the formal variable $z$ gives Equation (124.3). $\square$

The theorem is combinatorial. It counts realizations admitted by an already specified enclosing relation; it does not assert that each position independently makes a choice, nor that realized recurrences obey a binomial probability law.

## 124.5. Six completed positions: the exact native landscape

Take $M=6$ with $u_\alpha=2$, $u_\beta=1$. Then

$$
\boxed{
W_6(k)=\binom6k2^k.
}
$$

| α closures $k$ | β closures $6-k$ | Native multiplicity $W_6(k)$ |
|---:|---:|---:|
| 0 | 6 | 1 |
| 1 | 5 | 12 |
| 2 | 4 | 60 |
| 3 | 3 | 160 |
| 4 | 2 | **240** |
| 5 | 1 | 192 |
| 6 | 0 | 64 |

The total is

$$
\sum_{k=0}^{6}W_6(k)=3^6=729.
$$

The greatest multiplicity belongs to

$$
\boxed{(k,M-k)=(4,2).}
$$

This conclusion follows exactly from the enclosing native counts, with no stochastic transition kernel.

More generally, adjacent multiplicities satisfy

$$
\boxed{
\frac{W_M(k+1)}{W_M(k)}
=\frac{M-k}{k+1}\frac{u_\alpha}{u_\beta}.
}
\tag{124.4}
$$

For this six-position system,

$$
\frac{W_6(4)}{W_6(3)}=\frac32>1,
\qquad
\frac{W_6(5)}{W_6(4)}=\frac45<1.
$$

Thus the native multiplicity landscape rises through four α completions and falls thereafter. Its logarithmic adjacent native-count difference is

$$
\Delta S_{*,k\to k+1}
=\ln\frac{W_M(k+1)}{W_M(k)}.
$$

This is a comparison of *native possible counts at $B_*$*. It is not automatically the across-boundary directional possibility $\Delta P$, nor does its sign require every realized six-completion configuration to contain exactly four α closures. All seven count classes remain admitted under Definition 1.

## 124.6. Count-weighted closure incidences are not realized recurrence counts

The complete native landscape determines another exact count relation. Sum the number of α and β positions over **all possible native realizations**, counting each native realization once:

$$
I_\alpha=\sum_{k=0}^{M}kW_M(k),
\qquad
I_\beta=\sum_{k=0}^{M}(M-k)W_M(k).
$$

These are *native-incidence counts across the possible configuration domain*. They are not the actual number of completed closures in a physical realization domain.

**Theorem 2 — Product-compatible incidence ratio.** Under Definition 1, with $M>0$ and $u_\alpha,u_\beta>0$,

$$
\boxed{
I_\alpha=M u_\alpha(u_\alpha+u_\beta)^{M-1},
\qquad
I_\beta=M u_\beta(u_\alpha+u_\beta)^{M-1}.
}
$$

Hence

$$
\boxed{\frac{I_\alpha}{I_\beta}=\frac{u_\alpha}{u_\beta}.}
\tag{124.5}
$$

**Proof.** Differentiate $H_M(z)=(u_\beta+u_\alpha z)^M$ and evaluate at $z=1$: $H_M'(1)=\sum_k kW_M(k)=M u_\alpha(u_\alpha+u_\beta)^{M-1}$. Since $\sum_k W_M(k)=(u_\alpha+u_\beta)^M$, the remaining-position incidence count is $M\sum_kW_M(k)-I_\alpha$, giving the expression for $I_\beta$. Division proves the ratio. $\square$

For $M=6$,

$$
I_\alpha=2916,\qquad I_\beta=1458,
\qquad \boxed{I_\alpha/I_\beta=2}.
$$

The native-count-weighted α count per complete native realization is

$$
\frac{I_\alpha}{\Theta_*}
=\frac{2916}{729}=4,
$$

and the corresponding β count is 2. These are **arithmetic properties of the possible-count landscape**, not claims that the observed six-closure recurrence count in every occurrence is 4:2, nor that the count owner samples possible states randomly.

No microscopic chooser appears in the proof because none is mathematically needed to establish the enclosing count identities.

## 124.7. The same local possibilities can support different enclosing landscapes

The full-product construction is a special enclosing compatibility rule. It must not be treated as what local multiplicities automatically generate.

Retain exactly the same one-position domain $D=D_\alpha\sqcup D_\beta$, with $u_\alpha=2$ and $u_\beta=1$. Now specify a different enclosing owner that admits only homogeneous complete configurations:

$$
\boxed{
\mathfrak M_*^{\mathrm{corr}}
=D_\alpha^M\ \sqcup\ D_\beta^M.
}
$$

Every position still has all three labels in its individual projection: $d_{\alpha p}$, $d_{\alpha q}$, and $d_{\beta p}$. But the complete enclosing relation forbids any mixture of α and β across the positions.

For $M=6$, its native multiplicity landscape is

$$
\boxed{
W_6^{\mathrm{corr}}(0)=1,\quad
W_6^{\mathrm{corr}}(6)=64,\quad
W_6^{\mathrm{corr}}(k)=0\ (1\le k\le5).
}
$$

Its total native count is $65$, not 729. Its count-weighted incidence ratio is $64:1$, not 2:1.

**Theorem 3 — One-position compatibility does not determine complete recurrence multiplicity.** Two complete enclosing count boundaries may have the same admitted one-position native projections and different complete configuration multiplicity landscapes, supports, and native-incidence ratios.

**Proof.** The full-product and homogeneous-only enclosing relations have identical one-position projections equal to $D$. Their explicitly computed native multiplicity landscapes differ. $\square$

This example makes the R²D causal ordering mathematically visible. The whole compatibility relation supplies what is countable across the completed recurrence configuration. The individual position domains do not independently determine that relation.

## 124.8. The general enclosing recurrence landscape and its support

The product and homogeneous constructions are instances of the same general structure. For any finite enclosing-native domain $\mathfrak M_*$ with readable count classification $\pi_*$, define the **supported completed-count classes**

$$
\mathcal K_* =\{k\in\{0,\ldots,M\}:W_*(k)>0\}.
$$

No probabilistic, product, or kinetic assumption is required.

**Theorem 4 — Exact compatibility-determined recurrence support.** In every admitted complete native realization $\mu$, the number of α-mode completions belongs to $\mathcal K_*$. Every $k\in\mathcal K_*$ is realized by at least one admitted complete native realization, by the definition of native multiplicity. Hence:

- The **exact admitted α-count domain** is $\mathcal K_*$.
- The **exact admitted β-count domain** is $\{M-k:k\in\mathcal K_*\}$.
- Every admitted realization has an α majority if and only if $\min\mathcal K_*>M/2$.
- Every admitted realization has a β majority if and only if $\max\mathcal K_*<M/2$.
- The completed count pair is uniquely fixed if and only if $|\mathcal K_*|=1$.

**Proof.** Equation (124.1) states that $W_*(k)>0$ precisely when at least one admitted native realization has count $k$. The displayed statements follow by comparing each possible $k$ with $M-k$ and by requiring the support to contain one element for unique completed counts. $\square$

This theorem establishes the **extent of determination by enclosing admissibility**. The boundary may fix an exact count, a count range, an unconditional direction, or no directional majority at all. It need not select a particular subordinate history.

### A simple sufficient bound from position compatibility

Suppose the enclosing comparison distinguishes $A$ positions in which every admitted realization has α, $B$ positions in which every admitted realization has β, and $F$ positions that can have either, with $A+B+F=M$. Additional cross-position constraints may be present.

Then every admitted complete realization satisfies

$$
\boxed{
A\le n_\alpha(\mu)\le A+F,\qquad
B\le n_\beta(\mu)\le B+F,
\qquad n_\alpha(\mu)+n_\beta(\mu)=M.
}
\tag{124.6}
$$

These are bounds, not necessarily realized endpoints. Other enclosing constraints may narrow them.

For $M=6$ with $A=4$, $B=1$, and $F=1$, only $(n_\alpha,n_\beta)=(4,2)$ or $(5,1)$ can occur before any further exclusion. Therefore $n_\alpha>n_\beta$ for every admitted realization, even though the exact count pair has not been fixed. More generally, $A>B+F$ is sufficient to guarantee an α majority.

## 124.9. Fixing completed counts without selecting a microscopic history

A more enclosing condition can restrict the complete domain to one count class. In the six-position full-product example, suppose the enclosing owner admits precisely

$$
\mathfrak M_*^{(4)}
=\{\mu\in D^6:\pi_*(\mu)=4\}.
$$

There are

$$
\boxed{|\mathfrak M_*^{(4)}|=\binom64 2^4=240}
$$

distinct admitted native realizations, but every one has

$$
\boxed{n_\alpha(\mu)=4,\qquad n_\beta(\mu)=2.}
\tag{124.7}
$$

If a complete configuration of this class occurs and each declared position corresponds to one completed subordinate closure, its total α and β closure counts are fixed exactly. It does not matter which of the 240 compatible native realizations is occupied.

Thus one enclosing compatibility constraint can determine the count of completed modes **without** uniquely determining their subordinate sources, arrangements, or histories. The result does not require a lottery among the 240 possibilities or a microscopic rule evaluating their number.

The value 4:2 was imposed here by the additional enclosing constraint; it was **not deduced from** the local 2:1 fiber sizes alone. The fact that 4:2 was also the maximal-count class in Section 124.5 is a separate mathematical fact.

## 124.10. Possible count, enclosing direction, and realized occupancy are distinct

The foregoing results are exact statements about $W_*(k)$, its support, and the admitted complete configurations at $B_*$. They do not yet establish an observed recurrence distribution.

Part I supplies a separate **proportional state occurrence** postulate, for a specified sufficiently resolved realization domain,

$$
\frac{\nu_*(k)}{\nu_*(\ell)}
\approx\frac{W_*(k)}{W_*(\ell)}.
$$

The approximate equality is not a combinatorial identity, and $\nu_*$ is not the count of completed subordinate closures merely because its macrostate label happens to be a completed-closure count.

Similarly, a larger native count $W_*(k)$ does not by itself determine structural occupancy when $B_*$ has a further enclosing boundary $B_+$. With native enclosing-compatible counts $\Theta_{+\mid *,k}$, Part I defines

$$
P_{*,k}=\ln\frac{\Theta_{+\mid *,k}}{W_*(k)},
$$

and the realized structural occupancy relation

$$
\Delta G_{k\to\ell}
=\Delta\tau_{k\to\ell}
+\Delta P_{k\to\ell}-\Delta R_{k\to\ell}.
$$

Under proportional occurrence realization this becomes

$$
\boxed{
\frac{c_*(\ell)}{c_*(k)}
\approx\frac{\Theta_{+\mid *,\ell}}{\Theta_{+\mid *,k}}
 e^{-\Delta R_{k\to\ell}}.
}
\tag{124.8}
$$

Thus the preferred native-count class at $B_*$, the enclosing-compatible possibility under $B_+$, and the physically realized occupancy are different readings. The exact 4:2 native multiplicity maximum in Section 124.5 is not a universal statement that the physical system must have 4:2 occupancy under arbitrary additional enclosing conditions.

This preserves R²D's distinction between the organization of possibility and its realization, without importing an entropy-production requirement or a stochastic event selector.

## 124.11. The recurrence law is not replaced by the multiplicity landscape

Part I separately defines completed local closure recurrence in a common domain $\mathcal D_R$. For a valid representative-peer and enclosing-transition comparison, the canonical R²D law is

$$
\boxed{
\Delta A_{n,a,\mathcal C}
N_{\mathcal D_R}(\mathcal C_{n,a})
=C_{n+1}\lambda_{n+1}
N_{\mathcal D_R}(\chi_{n+1}).
}
\tag{124.9}
$$

These are completed recurrence counts, not native possible multiplicities of complete configurations. The law does not authorize adding all competing closure recurrences as though their sum constructed the enclosing occurrence, nor does it imply that mode-specific closure recurrences are equivalent representative-peer counts.

For the complete configuration construction, a further **occurrence-to-recurrence correspondence** would be necessary to turn counted occurrences of readable $k$-classes into measured totals of completed α and β closures. It must be specified independently, and the canonical recurrence comparison must hold wherever invoked.

Accordingly, the following equation does **not** follow from the present addendum alone:

$$
\frac{N_{\mathcal D_R}(\mathcal C_\alpha)}
{N_{\mathcal D_R}(\mathcal C_\beta)}
\stackrel{?}{=}\frac{u_\alpha}{u_\beta}.
$$

What has been proved is that the corresponding **count-weighted native incidence ratio** equals $u_\alpha/u_\beta$ in the explicit product-compatible domain, and that stronger enclosing constraints can fix or bound completed closure counts in each admissible complete realization.

Connecting these results to realized recurrence statistics is the distinct mathematical task of Addendum 125. No primitive Markov transition kernel is required to state or prove the count results of this addendum.

## 124.12. The connection to the coin construction

The authoritative Part I coin construction fixes an enclosing total—60 tails in a 100-coin ensemble—and then counts which subordinate realizations are compatible with that enclosing state. Its directional-count result cannot be inferred from local binomial multiplicities alone. The enclosing relation supplies the relevant extension counts and can reverse the local native bias without changing the local native landscape.

The present recurrence construction expresses the same logical ordering in a different count domain:

1. An enclosing boundary specifies complete admissible configurations.
2. Its native-identification rule determines what each complete possibility counts as.
3. Its readable classification distinguishes completed-closure count classes.
4. Multiplicity and support follow from that specification before a particular complete realization occurs.

The analogy does not identify a coin toss with a completed R²D closure or replace closure recurrence with a time-ordered random trial. It demonstrates that **an enclosing constraint can determine the organization of subordinate count classes without determining every subordinate path**.

That is also the useful point of contact with world models. A model may represent many possible complete outcomes; neither its branch count nor its decision rule creates the physical compatibility relation. The model's representation must be audited against the enclosing native count and admissibility rules, as required by Addendum 122. The physical system need not explicitly survey its possibilities for those possibilities to constrain what can be realized.

## 124.13. Results and limits

The addendum establishes the following finite results:

**Result 1 — Complete recurrence multiplicity belongs to the enclosing boundary.** An admitted complete configuration domain and its native-identification and readable-class rules determine $W_*(k)$. Local mode-fiber sizes alone do not.

**Result 2 — Product-compatible recurrence multiplicity has an exact binomial form.** Where the enclosing boundary explicitly admits every joint combination, $W_M(k)=\binom Mk u_\alpha^k u_\beta^{M-k}$. For the specified six-position example, the maximal native class is 4:2.

**Result 3 — The count-weighted incidence ratio is an exact possible-count identity.** For the product-compatible relation, $I_\alpha/I_\beta=u_\alpha/u_\beta$. This is not by itself a realized recurrence-frequency law.

**Result 4 — Correlated enclosing compatibility changes the entire landscape.** Complete joint restrictions can change support, multiplicity, and count-weighted incidence ratios even when every one-position projection is unchanged.

**Result 5 — Enclosing support can fix exact counts or directional inequalities.** A count class supported alone fixes the completed-mode totals for every admitted complete realization. A wider support can still ensure an α or β majority in every admitted realization.

These are conditional on the explicit finite native-identification and readability specifications. They do not prove that any arbitrary sequence of completed events forms a new R²D-native boundary, that native microstate identities persist through recursive replacement, or that the maximal possible-count class must be the next observed realization. They introduce no independent stochastic transition law, event-selection mechanism, optimization principle, or microscopic decision-maker.

The central conclusion is:

$$
\boxed{
\begin{gathered}
\text{Enclosing compatibility determines}\\
\text{the admissible completed-closure landscape;}\\
\text{native identification determines its multiplicities;}\\
\text{realization determines which admitted configuration occurs.}
\end{gathered}
}
$$

**An enclosing possibility landscape can fix the distributional constraints and even the direction of competing subordinate closure counts without uniquely fixing a subordinate history.** The further conversion from possible-count relations to physically completed recurrence statistics requires Part I's distinct occurrence and recurrence mappings, rather than a primitive Markov transition rule.

## Appendix A — Finite verification targets

| Verification | Exact result |
|---|---|
| Enumerate the three complete joint realizations of $\mathfrak D_\chi$ | Two α-compatible; one β-compatible |
| Six-position product domain size | $3^6=729$ |
| Product native multiplicity by $k=0,\ldots,6$ | $(1,12,60,160,240,192,64)$ |
| Most numerous product count class | $k=4$; $W_6(4)=240$ |
| Product α incidence count | $\sum kW_6(k)=2916$ |
| Product β incidence count | $\sum(6-k)W_6(k)=1458$ |
| Product native-incidence ratio | $2:1$ |
| Homogeneous-only native support | $k=0,6$ |
| Homogeneous-only native counts | $W(0)=1,\ W(6)=64$ |
| Fixed 4:2 enclosing class | 240 admitted complete realizations, each with four α and two β completions |

These checks can be performed by direct enumeration. The general theorems follow from the stated proofs; the physical occurrence interpretation remains subject to the relevant boundary and recurrence specifications.

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*. Authoritative Markdown revision, September 25, 2026. Sections 3.2, 3.4–3.9; Appendix B.
2. R²D Addendum 103 — *The Causal Implications of the Microstate Definition*.
3. R²D Addendum 104 — *The Count Relation Survives Before State Identity*.
4. R²D Addendum 105 — *The Observational Inversion*.
5. R²D Addendum 107 — *Possibilities Pull; Probabilities Do Not Push*.
6. R²D Addendum 108 — *A Branch Is Not an Occupied World*.
7. R²D Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*.
8. R²D Addendum 121 — *Nested Wells, Compatibility, and Harmonic Structure*.
9. R²D Addendum 122 — *Enclosing Compatibility Before Categorical Composition*.
10. Finite-set combinatorics and generating functions are used only to enumerate explicitly admitted enclosing count domains; they introduce no independent physical causal premises.
