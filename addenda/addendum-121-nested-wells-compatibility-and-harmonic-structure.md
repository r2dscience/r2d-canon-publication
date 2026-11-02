---
r2d_id: "addendum-121"
title: "Addendum 121 — Nested Wells, Compatibility, and Harmonic Structure"
subtitle: "Boundary-Owned Replacement, Native Multiplicity, and Exact Harmonic Spacing"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 121
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-01"
promotion_basis: "explicit_author_authorization_2026-11-01"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
original_manuscript_label: "Addendum 114 — Nested Wells, Compatibility and Harmonic Structure"
---

# R²D Addendum 121 — Nested Wells, Compatibility, and Harmonic Structure

*Boundary-Owned Replacement, Native Multiplicity, and Exact Harmonic Spacing*

**Status:** Author-approved for canon publication — November 1, 2026  
**Canonical basis:** R²D Part I, September 25, 2026 authoritative revision

## Abstract

This addendum applies the algebra of boundary-owned replacement to finite nested-well compatibility families. The principal family has an ordered binary status at each elementary slot and excludes neighboring active statuses. Each enclosing boundary admits compatible pairs of child readable classes as its native realizations. An explicit native-identification map ρ identifies those pairs, while a separate map π reads their endpoint statuses and active count.

The admitted classes, native multiplicities, and a finer elementary comparison count are derived. Their supports agree, while their positive counts differ. An eight-slot example has fifteen supported endpoint–occupancy classes, forty native realizations, and 341 finer comparison realizations when the elementary active multiplicity is two. Its native logarithmic levels have no common exact positive harmonic spacing. Exact harmonic spacing occurs in a specified pattern-resolved finer read.

Extensions to longer-range exclusion, coupled rows, and enclosing parity relations establish how the permitted enclosing tests determine the required replacement classes. Cardinalities belong to the specified count domains. Computational work belongs to an EP realization of their description.

## 121.1. Boundary specifications and the elementary domain

The foundational replacement algebra distinguishes native identification, readable classification, and equivalence of enclosing responses [1]. Part I defines a native realization as one compatible joint realization of the immediately subordinate peers [2]. This addendum supplies explicit peer domains and compatibility rules before deriving their counts.

Choose an integer b ≥ 1. At each elementary reference boundary,

$$
\mathfrak M_1=\{o\}\sqcup\{a_1,\ldots,a_b\},
\qquad
\sigma(o)=0,\quad \sigma(a_j)=1.
$$

The inactive class has multiplicity one; the active class has multiplicity b. Elementary native identification is the identity on these native labels, and the readable map is

$$
\pi_1(x)=\bigl(\sigma(x),\sigma(x),\sigma(x)\bigr).
$$

Its middle component is the elementary active count. Thus the supported labels are (0,0,0) and (1,1,1).

Specify N = 2^h ordered slots and a balanced nesting into equal left and right blocks. Ordering and nesting are supplied compatibility structure. Each boundary carries its own tag and position; these tags are suppressed only where unambiguous.

The adjacent-exclusion rule is

$$
\sigma_i\sigma_{i+1}=0
\qquad(1\le i<N).
$$

For each block, the permitted enclosing contexts consist of external left and right statuses l and z and a requested active count K. If a block has endpoints a and r and active count k, its response is

$$
g(a,k,r;l,z,K)
=
\mathbf1[la=0]\mathbf1[rz=0]\mathbf1[k=K].
$$

All binary external statuses and candidate counts are permitted. No additional test of an internal arrangement or elementary active index is included in this family.

The active count is an enclosing classification retained in the interface. It is distinct from the number of native realizations at the block boundary.

## 121.2. Native identification and readable classification at a join

Let S_n be the supported readable labels of a size-n child boundary. The size-2n enclosing boundary specifies the peer domains S_n and S_n and the admitted relation

$$
\Gamma_{2n}
=
\left\{
(s,t)\in\mathcal S_n\times\mathcal S_n:
s_{\mathrm R}t_{\mathrm L}=0
\right\}.
$$

Its native domain is

$$
\mathfrak M_{2n}
=
\{(B_{2n},s,t):(s,t)\in\Gamma_{2n}\}.
$$

Each admitted ordered child-label pair is one native realization. This is the specified recursive count rule.

A complete one-level comparison presentation is a pair of child native realizations whose exported labels satisfy Γ. Its identification is

$$
\rho_{2n}(\mu_L,\mu_R)
=
\bigl(B_{2n},\pi_n(\mu_L),\pi_n(\mu_R)\bigr).
$$

The new readable classification is

$$
\boxed{
\pi_{2n}\bigl(B_{2n},(a,i,v),(u,j,r)\bigr)
=
(a,i+j,r).
}
$$

Different admitted pairs may share this readable triple. They remain different native realizations and contribute separately to its multiplicity.

The peer export at the next enclosing boundary is π_n. Thus replacement explicitly identifies all child native realizations in the same exported class when they serve as that parent's peer alternative. Their child-native multiplicities are not automatically weights of the new parent-native pair.

**Theorem 1 — Coverage and the coarsest readable interface.** The map ρ at every join covers the declared parent native domain. The supported triples (a,k,r) are the coarsest sufficient classification for the stated enclosing contexts.

**Proof.** Every supported child label has at least one child native representative. For every admitted pair of labels, choosing one representative of each gives an admitted comparison mapped by ρ to that parent pair. Hence ρ is surjective.

All permitted responses depend only on the triple, proving sufficiency. Different k-values are separated by setting both external statuses to zero and requesting one of the counts. At equal k, different left endpoints are separated by an active external left status and an inactive external right status. The analogous right probe separates different right endpoints. Therefore every pair of different supported triples is distinguished by a permitted context. ∎

For example, the two size-eight native pairs

$$
\bigl((0,1,0),(0,1,0)\bigr),
\qquad
\bigl((0,1,1),(0,1,0)\bigr)
$$

are both admitted and both read as (0,2,0). Their native identities differ. Equality of their parent responses does not make their contribution to the parent native count one.

## 121.3. Native and comparison recurrences

Define

$$
W_n(a,k,r)=|\pi_n^{-1}(a,k,r)|,
\qquad
\epsilon_n(a,k,r)=\mathbf1[W_n(a,k,r)>0].
$$

**Theorem 2 — Native recurrence.** The parent native multiplicity is

$$
\boxed{
W_{2n}(a,k,r)
=
\sum_{i+j=k}
\ \sum_{\substack{u,v\in\{0,1\}\\uv=0}}
\epsilon_n(a,i,v)\epsilon_n(u,j,r).
}
$$

**Proof.** Each term selects one supported left label and one supported right label. The middle endpoint condition is exactly the parent compatibility rule. Every admitted ordered pair contributes once to the class selected by π, and its child labels determine one term of the sum. ∎

A separate comparison may resolve the elementary labels throughout an ordered block. Let F_n be the admitted elementary sequences from the domain in Section 1. Let M_n(a,k,r) count sequences in F_n with the requested endpoints and active count. The product structure of this comparison permits independent active-index choices once a status pattern is admitted.

Unique decomposition into left and right elementary sequences gives

$$
M_{2n}(a,k,r)
=
\sum_{i+j=k}\ \sum_{uv=0}
M_n(a,i,v)M_n(u,j,r).
$$

The multiplication counts the finer comparison domain. It does not define the parent native pair count.

There is also a one-level comparison obtained by counting pairs of child native realizations. Its corresponding recurrence uses W_n times W_n. At deeper levels this can differ from both the native recurrence, which uses support indicators, and the elementary recurrence, which uses M_n.

The elementary comparison supplies another complete presentation of the parent native domain. For d in F_n, write Q_n(d) for its endpoint–occupancy triple. Then

$$
\rho_{2n}^{\mathrm{fine}}(d_Ld_R)
=
\bigl(B_{2n},Q_n(d_L),Q_n(d_R)\bigr).
$$

Induction establishes coverage: elementary representatives exist for every supported child class, and any representatives of an admitted pair concatenate compatibly. The identity

$$
\pi_{2n}\circ\rho_{2n}^{\mathrm{fine}}=Q_{2n}
$$

makes the two stages explicit. Counting distinct native images gives W; counting the admitted elementary presentations gives M. The domains agree on whether a class is supported.

## 121.4. Exact comparison counts and supported classes

Use the convention that a binomial coefficient is zero unless its upper and lower entries are nonnegative and the lower does not exceed the upper.

**Theorem 3 — Elementary comparison and support.** For each non-elementary dyadic block n ≥ 2,

$$
\boxed{
M_n(a,k,r)
=
b^k\binom{n-k-1}{k-a-r}.
}
$$

Its support is

$$
\boxed{
\epsilon_n(a,k,r)=1
\iff
a+r\le k\le
\left\lfloor\frac{n+a+r-1}{2}\right\rfloor.
}
$$

**Proof.** Let the k active positions be increasing and nonadjacent. Subtract 0,1,…,k−1 from them. This is a bijection to ordinary k-element subsets of a line of length n−k+1.

The original left endpoint is active precisely when the compressed subset contains its first position; the corresponding statement holds at the right endpoint. Fixing those two membership choices leaves k−a−r positions to select from n−k−1 interior positions, giving the binomial coefficient. Every admitted status pattern has b^k elementary active-index choices. Parameter choices outside the admitted range contribute zero under the stated convention.

Positivity requires k−a−r ≥ 0 and k−a−r ≤ n−k−1. These inequalities give the displayed support bounds. Conversely, those bounds make the binomial coefficient positive. Native and finer supports coincide by the coverage result in Section 3. ∎

The size-one case retains the separately specified elementary counts.

For an even block n = 2m, the supported classes are:

| Endpoints | Active-count range | Number of classes |
| - | - | - |
| 00 | 0 through m−1 | m |
| 01 | 1 through m | m |
| 10 | 1 through m | m |
| 11 | 2 through m | m−1 |

An empty range contributes zero. Hence

$$
|\mathcal S_n|=2n-1
\qquad(n\ge2\text{ even}).
$$

Summing the finer endpoint counts, or compressing the active positions without fixing endpoint membership, gives

$$
\boxed{
\overline M_n(k)=b^k\binom{n-k+1}{k}.
}
$$

The elementary parameter b affects the finer count. Because b is positive, it does not affect which child labels are supported. It therefore disappears from the native recurrence at size two and every subsequent boundary.

## 121.5. Closed native formulas and the occupancy well

Introduce a formal variable t to index the active-count classification. Define the endpoint-support matrix by

$$
E_n^{ar}(t)=\sum_k\epsilon_n(a,k,r)t^k.
$$

For an even child size n = 2m, set

$$
U_m(t)=1+t+\cdots+t^{m-1},
\qquad U_0(t)=0.
$$

The support bounds give

$$
E_n(t)=
\begin{pmatrix}
U_m&tU_m\\
tU_m&t^2U_{m-1}
\end{pmatrix},
\qquad
J=
\begin{pmatrix}
1&1\\
1&0
\end{pmatrix}.
$$

**Theorem 4 — Native count polynomials.** The endpoint-resolved native count matrix at the parent is

$$
\boxed{\mathcal W_{2n}(t)=E_n(t)J E_n(t).}
$$

Set

$$
A=U_m(t),\qquad B=U_{m-1}(t).
$$

The entries are

$$
\begin{aligned}
\mathcal W_{2n}^{00}&=(1+2t)A^2,\\
\mathcal W_{2n}^{01}=\mathcal W_{2n}^{10}
&=t(1+t)A^2+t^2AB,\\
\mathcal W_{2n}^{11}&=t^2A^2+2t^3AB.
\end{aligned}
$$

**Proof.** Matrix multiplication sums over the two contacting endpoint statuses. J removes precisely the forbidden contact 11. Each supported child label has coefficient one, and multiplying the powers of t adds its active count to the other child's count. Coefficient extraction is therefore exactly Theorem 2. Substituting the support polynomials and multiplying gives the displayed entries. ∎

The occupancy read groups the native domain by k while summing over endpoints:

$$
\overline W_N(k)=\sum_{a,r}W_N(a,k,r),
\qquad
P_N(t)=\sum_k\overline W_N(k)t^k.
$$

This count profile and its logarithmic read define the occupancy well considered here. Endpoint distinctions remain available in the full interface for later composition.

For a balanced dyadic boundary N = 4m, summing Theorem 4's entries yields

$$
\boxed{
P_N(t)
=
(1+t)(1+3t)U_m(t)^2
+
2t^2(1+t)U_m(t)U_{m-1}(t).
}
$$

The separate size-two base is P₂(t) = 1+2t. Together these formulas cover every non-elementary boundary in the balanced hierarchy.

At t = 1,

$$
\boxed{
|\mathfrak M_N|=\frac{3N^2}{4}-N
\qquad(N=2^h\ge4).
}
$$

The same total follows directly. A child of even size n has 2n−1 supported labels, of which n−1 have right endpoint one and n−1 have left endpoint one. The parent therefore admits

$$
(2n-1)^2-(n-1)^2=3n^2-2n
$$

pairs. Substitution of N = 2n gives the stated total.

## 121.6. An eight-slot well

For N = 8 and b = 2, there are fifteen supported endpoint–occupancy classes and forty native realizations. The elementary comparison has 341 realizations.

| Active count k | Native occupancy multiplicity | Elementary comparison multiplicity |
| - | - | - |
| 0 | 1 | 1 |
| 1 | 6 | 16 |
| 2 | 14 | 84 |
| 3 | 14 | 160 |
| 4 | 5 | 80 |
| Total | 40 | 341 |

The polynomials are

$$
P_8(t)=1+6t+14t^2+14t^3+5t^4,
$$

$$
\sum_k\overline M_8(k)t^k
=
1+16t+84t^2+160t^3+80t^4.
$$

The one-level comparison of pairs of size-four native realizations has total count 55: each child has eight native realizations, three of which have the relevant endpoint active, giving 8²−3² = 55. Thus 40, 55, and 341 count three explicitly different domains.

The endpoint-resolved native class (0,2,0) has multiplicity five. The two pairs displayed in Section 2 are two of those five. Conversely, an elementary comparison can contain several distinct presentations of one parent-native pair; ρ identifies that pair once.

Compatibility also requires more than the child occupancy. A left child of class (0,1,1) and a right child of class (1,1,0) are separately admitted, but their contacting statuses are both active and their join is excluded. Replacing the left class by (1,1,0) makes the join compatible. Both left classes have active count one. Retaining that count alone would erase a distinction required by the join.

## 121.7. Logarithmic levels and harmonic structure

For a positive count W, write S = ln W. Here “harmonic spacing” means an exact constant increment between logarithmic levels in a declared ordered family of count classes.

**Theorem 5 — Criterion for regular logarithmic spacing.** Let W₀,…,W_m be positive multiplicities. Their logarithms satisfy S_j = S₀+jΔ with Δ > 0 if and only if

$$
W_j=W_0r^j
\qquad\text{with}\qquad r=e^\Delta>1.
$$

**Proof.** Exponentiation gives the geometric sequence from the logarithmic ladder. Taking logarithms gives the converse. ∎

An integer base b > 1 is a sufficient choice when the specified multiplicities are W₀b^j. Integer-valued multiplicities alone do not establish this geometric structure.

### Pattern-resolved finer levels

Condition on an admitted elementary status pattern with k active slots. Its finer active-index multiplicity is b^k. Across the family of admitted pattern fibers,

$$
S_{\mathrm{fine}\mid\mathrm{pattern}}=k\ln b.
$$

Every admitted occupancy k is represented by at least one pattern. Thus b > 1 gives an exact ladder of distinct finer logarithmic levels spaced by ln b. Different patterns with the same k have the same level. For b = 1 this contribution is flat.

The active indices counted here belong to the declared elementary comparison. They are identified together by the parent-native map when their exported child labels agree.

### Finer occupancy levels

Including every admitted status pattern at a fixed k gives

$$
S_{\mathrm{fine}}(n,k)
=
k\ln b+\ln\binom{n-k+1}{k}.
$$

For consecutive admitted occupancies,

$$
S_{\mathrm{fine}}(n,k+1)-S_{\mathrm{fine}}(n,k)
=
\ln b+
\ln\!\left(
\frac{(n-2k+1)(n-2k)}
{(k+1)(n-k+1)}
\right).
$$

This follows by taking the ratio of the two consecutive comparison counts. The additional combinatorial term depends on occupancy. Regular spacing of pattern-resolved levels therefore does not establish regular spacing of the occupancy levels.

### Native occupancy levels

The replaced boundary has the native spectrum

$$
S_{\mathrm{native}}(N,k)=\ln\overline W_N(k).
$$

For eight slots,

$$
\boxed{
S_{\mathrm{native}}(8,k)
=
(0,\ln6,\ln14,\ln14,\ln5).
}
$$

The adjacent differences in occupancy order are ln 6, ln(7/3), zero, and ln(5/14).

These levels do not even lie on a common exact positive-spacing logarithmic lattice. Since zero is a level, such a lattice would make ln 6 and ln 14 positive integer multiples of a common Δ. Their ratio would be rational, giving positive integers p and q with

$$
6^q=14^p.
$$

The left side contains a factor of three and the right side does not. This is impossible.

The occupancy classes k = 2 and k = 3 have equal native multiplicity fourteen, yet the prescribed count contexts distinguish them. Equality of logarithmic level is therefore insufficient to identify readable classes.

## 121.8. Richer enclosing interfaces

The same boundary-owned construction applies when the enclosing tests require additional distinctions. For each family below, let S_A and S_B be the supported child labels, Γ_J the specified admitted ordered label pairs, and m_J their merge classification. The parent maps are

$$
\rho_J(d_A,d_B)
=
\bigl(B_J,Q_A(d_A),Q_B(d_B)\bigr),
\qquad
\pi_J(B_J,s,t)=m_J(s,t).
$$

The presentations must cover the supported child labels. The compatibility rules below ensure that every admitted pair has compatible representatives. Each pair counts once as a parent native realization:

$$
W_J(q)=
\left|
\{(s,t)\in\Gamma_J:m_J(s,t)=q\}
\right|.
$$

This is the same specified native rule used in the principal family. The interface label and its native multiplicity remain separate.

### Exclusion over a longer range

Require at least d inactive positions between consecutive active positions, with d ≥ 1. A block of known length n has label

$$
q_d=(\ell,k,r),
$$

where ℓ and r are its leading and trailing inactive lengths, capped at d. An empty block has k = 0 and ℓ = r = min(d,n).

Exterior contexts specify capped inactive clearances e_L and e_R to their nearest active positions and a requested count K. For k > 0,

$$
g_d=
\mathbf1[k=K]\mathbf1[e_L+\ell\ge d]\mathbf1[r+e_R\ge d].
$$

For an empty block, the exterior active positions can interact across the block, so the response is

$$
g_d=
\mathbf1[K=0]\mathbf1[e_L+n+e_R\ge d].
$$

A clearance equal to d also represents the absence of a relevant nearby exterior active position.

**Theorem 6 — Longer-range replacement classes.** These supported triples are the coarsest sufficient classes for the declared contexts. Two nonempty children join exactly when their facing clearances sum to at least d; if either child is empty, the internal join is admitted.

**Proof.** Equal triples give equal responses. Different counts are separated by K with harmless exterior clearances. For equal positive counts and ℓ < ℓ′, choose e_L = d−1−ℓ and e_R = d. The first class fails and the second passes. The corresponding right probe separates different trailing clearances. The fixed-length empty class is unique.

For two nonempty children, the closest cross-join active positions have exactly the intervening trailing and leading inactive gaps. Their sum determines compatibility. An empty child contributes no active position to an internal cross-join exclusion. ∎

For left label (ℓ,k,r) of length n and right label (a,j,b) of length m, the merged count is k+j, with

$$
\ell_+=
\begin{cases}
\ell,&k>0,\\
\min(d,n+a),&k=0,
\end{cases}
\qquad
r_+=
\begin{cases}
b,&j>0,\\
\min(d,m+r),&j=0.
\end{cases}
$$

These are exact leading and trailing clearances of the joined block. They preserve the distinctions required by later exterior contexts, including short empty blocks.

The maximum active count is

$$
k_{\max}=\left\lfloor\frac{n+d}{d+1}\right\rfloor.
$$

Indeed, k active positions require at least k+d(k−1) positions, and the bound is attained by minimum gaps. Consequently,

$$
|\mathcal S_{n,d}|
\le
(\min(d,n)+1)^2(k_{\max}+1).
$$

For d = 2, the patterns 00100 and 01000 have equal endpoint statuses and active count but different left clearances. An active exterior left status distinguishes them. The shorter adjacent-exclusion interface is insufficient for this enclosing family.

### Several coupled rows

Specify w labeled rows and n ordered columns, excluding adjacent active statuses vertically and horizontally. There are no diagonal constraints.

The admitted elementary column masks are

$$
\mathcal C_w=
\{\alpha\in\{0,1\}^w:\alpha_i\alpha_{i+1}=0\}.
$$

These masks are the elementary peer types of this extension. Neighboring columns are compatible when their bitwise intersection is zero. The enclosing contexts attach admitted exterior column masks and request the total active count.

**Theorem 7 — Coupled-row replacement classes.** The coarsest sufficient supported label is

$$
q_w=(L,k,R),
$$

where L and R are complete endpoint column masks. Child labels (A,i,V) and (U,j,B) join exactly when V ∧ U = 0, with parent label (A,i+j,B).

**Proof.** Every declared exterior test depends only on the two masks and the count. Different counts are separated by their requested value. If two endpoint masks differ at row i, an exterior column active only in row i distinguishes them; that probe is always an admitted column. The opposite exterior mask can be zero. The join condition is precisely horizontal exclusion at the contacting columns. ∎

Let c_w be the number of admitted column masks. Splitting by a first status zero or a beginning 10 gives

$$
c_0=1,\quad c_1=2,\quad c_w=c_{w-1}+c_{w-2}.
$$

The class bound is

$$
|\mathcal S_{n,w}|
\le
c_w^2\bigl(n\lceil w/2\rceil+1\bigr).
$$

Every four-column sequence (L,0,0,R) is admitted. These sequences supply a distinct class for each ordered endpoint pair, so

$$
|\mathcal S_{4,w}|\ge c_w^2\ge 2^w.
$$

The last inequality follows because every subset of odd-numbered rows is an admitted mask, giving at least two choices independently at each odd-numbered row. Independent enclosing row probes require all these distinctions.

### Enclosing parity relations

Retain adjacent exclusion and assign each position a prespecified vector v_i in the binary vector space of dimension ℓ. Define

$$
p(\sigma)=\bigoplus_{i:\sigma_i=1}v_i.
$$

The contexts request endpoint compatibility, active count K, and parity vector P.

**Theorem 8 — Parity replacement classes.** The coarsest sufficient supported label is

$$
q_{\mathrm{parity}}=(a,k,z,p).
$$

Two children with labels (a,i,v,p) and (u,j,z,q) join when vu = 0 and read as (a,i+j,z,p⊕q).

**Proof.** The specified responses depend only on these components. Neutral endpoint probes separate different counts and parity vectors by requesting their values. At equal count and parity, a one-sided active probe separates different endpoint statuses. The merge combines the endpoint exclusion, addition of active counts, and the defining binary sum. ∎

If the position vectors in a block span a subspace of rank r_I, then

$$
|\mathcal S_I|
\le
4\bigl(\lceil n/2\rceil+1\bigr)2^{r_I}.
$$

The rank bounds the possible parity values, and adjacency can further restrict which are realized.

Independent parity distinctions can occur even at fixed endpoints and active count. For ℓ components, consider

$$
0\,[100\text{ or }010]^\ell\,0.
$$

In gadget j, assign vector zero to the first position, basis vector e_j to the second, and zero to the third. Each pattern has inactive endpoints and ℓ active positions. Choosing 100 contributes zero and choosing 010 contributes e_j. Thus all 2^ℓ parity values occur and are separated by the enclosing parity requests. Inactive padding supplies a dyadic block length when required.

A parity component can also be redundant: assigning the same one-bit vector to every position makes it the parity of k. Assigning every vector zero recovers the original endpoint–occupancy classification and its native spectrum. A binary parity read alone therefore supplies no universal logarithmic spacing.

## 121.9. What the families establish

Each family specifies the enclosing tests, derives sufficient readable classes, and declares how those classes serve as peer realization types at the next boundary. Native identification determines the admitted joint pair; readable classification determines its class and multiplicity.

| Family | Required readable interface |
| - | - |
| Adjacent exclusion | Endpoint statuses and active count |
| Longer-range exclusion | Capped endpoint clearances and active count |
| Coupled rows | Endpoint masks and active count |
| Enclosing parity | Endpoint statuses, active count, and parity vector |

Changing the enclosing relation changes the required distinctions. It can leave a short numerical interface or require many independently distinguishable classes. These are statements about the specified classifications and native domains.

The principal nested-well family supplies exact native multiplicities and a discrete logarithmic spectrum. Regular harmonic spacing follows when the relevant count sequence has the geometric structure of Theorem 5. The eight-slot native spectrum does not have that structure, while the pattern-resolved elementary comparison does. Each harmonic claim therefore belongs to its declared count and classification.

## Appendix A EP construction and verification

Explicitly enumerating classes, storing their labels, multiplying polynomial representations, or traversing a hierarchy are EP realizations of the algebra. Their computational work is distinct from the native cardinalities being described.

For the principal balanced family, a size-N interface with N ≥ 2 contains 2N−1 labels and its parent-pair native domain has quadratic cardinality in N. A direct implementation can inspect admitted label pairs to construct the native count table. Summing pair inspections over an explicitly represented balanced N-slot hierarchy gives O(N²) inspections; integer and label operations require their corresponding bit costs. A succinct encoding of the height describes a different input-size problem.

The coupled-row and parity examples establish large class cardinalities as width or rank grows. Enumerating all classes explicitly inherits those sizes. The algebra does not require that particular EP representation.

The principal family was checked by direct status-pattern enumeration, recursive native and finer counts, and the closed formulas. Earlier checks covered elementary status patterns through sixteen slots for b = 1, 2, and 3, and the recurrences and polynomial identities through 128 slots.

The explicit ρ–π formulation was additionally checked as follows:

| Check | Scope | Result |
| - | - | - |
| Image of the elementary presentation under ρ equals the declared native pair domain | Sizes 2, 4, 8, and 16 | Passed |
| Endpoint-resolved elementary comparison formula | 408 comparisons for b = 1, 2, and 3 | Passed |
| Literal elementary-label realizations mapped to native pairs | 1,639 admitted realizations across sizes 2, 4, and 8 | Passed |
| Distinct native pairs in readable class (0,2,0) | Five native pairs at size eight | Confirmed |
| Native, one-level comparison, and elementary comparison totals | 40, 55, and 341 at size eight with b = 2 | Confirmed |

The richer-interface constructions were checked for exclusion ranges one through four and lengths through ten; strips of up to five rows and four columns; and parity assignments through ten slots, with independent-parity constructions through six components. These checks compared admitted patterns, response classes, and recursive joins.

The finite enumerations are EP checks of the implementations. The counting formulas, coarseness claims, and composition rules follow from the proofs above.

## References

[1] [Addendum 120 — Boundary-Owned Identity and the Algebra of Recursive Replacement](addendum-120-boundary-owned-identity-and-the-algebra-of-recursive-replacement.md). Foundational R²D addendum: native identification, readable classification, native weights, exact gluing, and replacement composition.

[2] [R²D Part I — A Theory of Dimensionless Recursive Counting](../canon/part-i.md), §3.2.1 and Appendix A, Axioms 1–6: boundary-defined joint realizations, native multiplicity, enclosing compatibility, and recursive replacement.
