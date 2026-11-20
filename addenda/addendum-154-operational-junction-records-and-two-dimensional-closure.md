---
r2d_id: "addendum-154"
title: "Addendum 154 — Operational Junction Records and Two-Dimensional Closure"
subtitle: "A Finite Reconstruction Theorem, a Chronology–Attachment Obstruction, and Symplectic Selection"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 154
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-19"
scope: "Finite two-junction three-channel mechanical response owner; complete three-turn enumeration; prefix-neutral enclosing restriction; non-identifiability of two-dimensional attachment from temporal records alone; operational corner and channel-side comparisons; uniqueness of the orientable cellular completion; integral symplectic intersection; recursive replacement and physical-read conditions"
---

# R²D Addendum 154 — Operational Junction Records and Two-Dimensional Closure

*A Finite Reconstruction Theorem, a Chronology–Attachment Obstruction, and Symplectic Selection*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I–IV (September 25, 2026); especially Addenda 105, 116, 120, 122, 125, 131, 150–153.  
**Result type:** Exact finite counting, a non-identifiability theorem, and an exact **conditional reconstruction** of two-dimensional attachment from specified complete operational comparison records. No physical surface, phase-space variables, Hamiltonian, or clock is primitive.

## Abstract

Addendum 153 constructs an integral nondegenerate alternating intersection pairing from a specified complete oriented two-dimensional closure. A remaining selection question concerns a finite mechanical source for the attachment itself: can conservation and complete oriented junction responses determine its face boundaries without a preselected surface? We examine two junctions connected by three distinguishable reciprocal channels. Each junction has seven bounded three-port inventory classifications and six pointed, port-complete three-turn returns. The uncoupled pair admits 36 complete response records. An enclosing requirement that the junction response registers cancel at every intermediate comparison admits precisely six synchronized records. Those six select equal *temporal turn permutations* at the two junctions, up to global reversal.

A crucial obstruction remains: a chronological turn permutation is not automatically a two-dimensional **boundary-corner successor**, and reversal of a single longitudinal momentum vector does not determine transverse channel-sidedness. The original conservation and temporal records therefore do **not**, by themselves, determine a physical two-cell attachment. We give an explicit counterowner and a directional-count transfer counterexample.

We then define the smallest operationally discriminating enlargement: (i) a complete **corner comparison** that identifies one same-side port successor at each junction, and (ii) a complete **two-sided channel comparison** that identifies how response-side labels are paired across reciprocal channel ends. If those measured relations agree with the finite turn records and admit reciprocal, untwisted side continuation, a deterministic face-permutation calculation yields the **unique compatible oriented cellular completion**, up to simultaneous reversal. For the prefix-neutral owner the resulting complete boundary is one six-dart face; its completion has genus one and first homology $\mathbb Z^2$ with unimodular alternating pairing $\mathbb J_1$. The opposed-turn counterowner instead has three faces, genus zero, and no surviving first-homology pairing.

The contribution is an exact **criterion and reconstruction** from independently specified second-order mechanical compatibility. It is not the stronger, unsupported assertion that ordinary inventory conservation or temporal ordering alone forces orientable topology. The physical task is to establish whether an actual apparatus supplies the requisite corner and channel-side readings.

---

## 154.1. The question after Addendum 153

Part I defines native distinctions through enclosing compatibility. Addendum 116 constructs signed interfacial incidence and conservation, and Addendum 152 distinguishes native state, one-step process, and whole-process count domains. Addendum 153 proves that a complete oriented two-cell attachment supplies integral intersection numbers not recoverable from the linear chain operators alone.

The missing implication is not merely

$$
D\mathbf z=0\ \Longrightarrow\ \text{two independent closed-flow vectors}.
$$

It is whether the **complete enclosing mechanical comparison** supplies the additional oriented information that determines the attachment word. We separate three levels:

1. **Inventory and momentum conservation:** signed changes and their exact return.
2. **Temporal turn compatibility:** which ordered port exchanges form a completed junction response.
3. **Boundary-corner and channel-side compatibility:** which ordered port comparison is a *same-side boundary continuation* and how that side is paired across a reciprocal interface.

The third level cannot be silently inferred from the second. The purpose of this addendum is to establish exactly which implication is provable and to give its finite construction.

## 154.2. Two-junction mechanical count owner

Let $U,V$ be two distinguishable junctions connected by three reciprocal channels $e_1,e_2,e_3$. Fix the conventional orientation $U\to V$ for the signed incidence matrix

$$
\boxed{D=\begin{pmatrix}1&1&1\\-1&-1&-1\end{pmatrix}.}
\tag{154.1}
$$

For a completed return of the regional inventory, $D\mathbf z=0$; hence the integral closed-flow group is rank two. One basis is

$$
\boxed{u=(1,-1,0),\qquad v=(0,1,-1).}
\tag{154.2}
$$

The local junction-response inventory is a **separate count domain** from the net channel-throughput vector $\mathbf z$. Define

$$
\Omega_s^n=\{\mathbf n_s\in\{0,1,2\}^3:\ \mathbf1^{\mathsf T}\mathbf n_s=3\},\quad s\in\{U,V\}.
\tag{154.3}
$$

Its seven records consist of $(1,1,1)$ and the six permutations of $(0,1,2)$. Let $C=(1,1,1)$.

Choose two jointly readable, integer-valued directional-momentum components. At $U$ specify the three port valuations

$$
\mathbf p_1=(2,0),\quad\mathbf p_2=(0,2),\quad\mathbf p_3=(-2,-2),
\qquad \sum_i\mathbf p_i=0,
\tag{154.4}
$$

and at $V$ specify $\mathbf p_{V,i}=-\mathbf p_i$. These are signed count-response valuations, not physical $\mathrm{kg\,m\,s^{-1}}$ units or phase-space coordinates.

Define a compensating junction-response register

$$
\boxed{\mathbf h_s(\mathbf n_s)=-\sum_i n_{s,i}\mathbf p_{s,i}.}
\tag{154.5}
$$

Every admitted local record then satisfies

$$
\sum_i n_{s,i}\mathbf p_{s,i}+\mathbf h_s=0.
\tag{154.6}
$$

Equation (154.6) is exact local count-momentum accounting. It does not assert that the individual port inventories $n_{U,i}$ and $n_{V,i}$ are particle populations conserved separately along each channel. They are endpoint response classifications; global material-throughput conservation is independently represented by (154.1).

## 154.3. Elementary turns and six complete local returns

A turn $i\to j$, $i\ne j$, changes one local inventory distinction:

$$
\mathbf n_s' =\mathbf n_s-\mathbf e_i+\mathbf e_j,
\qquad
\boxed{\Delta\mathbf h_s=\mathbf p_{s,i}-\mathbf p_{s,j}.}
\tag{154.7}
$$

Both the total local inventory and the momentum balance (154.6) remain exact. From $C$, all six oriented turns are possible. Their directional responses at $U$ are

| Turn | $\Delta\mathbf h_U$ |
|---|---|
| $1\to2$ | $(2,-2)$ |
| $2\to3$ | $(2,4)$ |
| $3\to1$ | $(-4,-2)$ |
| $1\to3$ | $(4,2)$ |
| $3\to2$ | $(-2,-4)$ |
| $2\to1$ | $(-2,2)$ |

They are pairwise distinct. The corresponding responses at $V$ have the opposite signs.

Define a *pointed, port-complete, three-turn return* to be a complete ordered comparison

$$
(i\to j,\ j\to k,\ k\to i),
\qquad \{i,j,k\}=\{1,2,3\},
\tag{154.8}
$$

starting at $C$, with all intermediate records in $\Omega_s^n$. Every permutation $(i,j,k)\in S_3$ gives exactly one such comparison, and every comparison returns both $\mathbf n_s$ and $\mathbf h_s$ to their initial values. There are six **pointed** complete records, divided into two cyclic classes:

$$
\boxed{\mathcal C_+=(1\,2\,3),\qquad
\mathcal C_-=(1\,3\,2).}
\tag{154.9}
$$

Each class has three choices of the distinguished starting turn. The count six refers to possible complete records, not realized event frequency or elapsed physical time.

The uncoupled two-junction owner admits $6^2=36$ pointed pairs. Nine have each of the four local class combinations $(+,+),(+,-),(-,+),(-,-)$.

## 154.4. Prefix-neutral enclosing compatibility

Define the enlarged complete process owner $J^\ast$ by requiring, for synchronized comparison positions $t=0,1,2,3$,

$$
\boxed{\mathbf h_U(t)+\mathbf h_V(t)=0.}
\tag{154.10}
$$

This is a declared **whole-enclosing response condition**, stronger than requiring the combined response to vanish only at the final return. It is not a consequence of bare local conservation.

**Proposition 154.1 — Exact matching of ordered turns.** For the specified count valuations, (154.10) implies $\mathbf n_U(t)=\mathbf n_V(t)$ at every comparison position, and therefore the ordered turn at each position is the same at both junctions. Exactly six of the 36 pointed joint three-turn records remain.

**Proof.** Equation (154.5) and $\mathbf p_{V,i}=-\mathbf p_i$ give

$$
\mathbf h_U+\mathbf h_V=\sum_i(n_{V,i}-n_{U,i})\mathbf p_i.
$$

The map $\mathbf a\mapsto\sum_i a_i\mathbf p_i$ has kernel $\operatorname{span}(1,1,1)$ over $\mathbb R$, since $\mathbf p_1,\mathbf p_2$ are linearly independent and $\mathbf p_3=-\mathbf p_1-\mathbf p_2$. Both inventories sum to three; thus their difference also has zero component sum. Membership of that difference in the kernel forces it to vanish. The initial inventory is $C$ at both junctions, so equality at all adjacent comparisons forces each ordered inventory change—and therefore its pair $i\to j$—to be identical. Each of the six pointed local records has exactly one synchronized mate. $\square$

The selected complete process domain has

$$
\boxed{|\Omega_{J^\ast}^{(3)}|=6.}
\tag{154.11}
$$

The result is a selection of **matching temporal turn permutations**. Whether those permutations are already two-dimensional attachment information is a separate question.

## 154.5. The chronology–attachment obstruction

**Theorem 154.2 — Temporal mechanical records alone do not determine the two-cell attachment.** The data (154.1)–(154.11), considered strictly as inventory, momentum, and time-ordered complete process records, do not uniquely determine a two-dimensional cellular completion.

**Proof.** Let $\mathcal D=\{e_i^+,e_i^-:i=1,2,3\}$ be the six directed channel ends and let $\alpha(e_i^+)=e_i^-$, $\alpha(e_i^-)=e_i^+$. The temporal records say which turn $i\to j$ follows which comparison position. They contain no predicate identifying that turn with *the next boundary corner on a specified side* of a junction.

One can therefore augment **the same** temporal owner with the cellular vertex rotations

$$
\sigma_A=(e_1^+\ e_2^+\ e_3^+)(e_1^-\ e_2^-\ e_3^-)
\tag{154.12}
$$

or

$$
\sigma_B=(e_1^+\ e_2^+\ e_3^+)(e_1^-\ e_3^-\ e_2^-).
\tag{154.13}
$$

Neither choice changes a single inventory, signed momentum value, temporal response, or admitted pointed sequence, **unless** an additional rule identifies temporal turn order with cellular corner order. Yet the orientable face permutations $\phi=\sigma\circ\alpha$ have respectively one and three orbits. Their closed orientable cellular completions have genera one and zero. Consequently the original records are insufficient. $\square$

There is an independent transverse-sidedness obstruction. A channel whose one recorded longitudinal count-response is $\mathbf p_1=(2,0)$ and whose reciprocal response is $-\mathbf p_1$ is compatible with either linear count transfer

$$
T^{(+)}=-I_2\quad(\det T^{(+)}=+1)
\qquad\text{or}\qquad
T^{(-)}=\begin{pmatrix}-1&0\\0&1\end{pmatrix}
\quad(\det T^{(-)}=-1).
\tag{154.14}
$$

Both send $(2,0)$ to $(-2,0)$, but they act oppositely on an independent transverse count probe. A reciprocal longitudinal vector thus does not establish the sidedness of a channel's whole two-component response. General (possibly nonorientable) cellular embeddings require edge-sidedness information in addition to vertex rotations.

This theorem is a positive specification of the missing distinguishability, not a rejection of the finite mechanical consistency witness.

## 154.6. Operationally complete corner and side records

We now supply **the precise additional read**, defined without drawing a surface or specifying its genus.

**Corner comparison.** For each selected complete response record $\omega$ at junction $s$, a complete *same-side corner comparison* identifies, among the directed channel ends incident at $s$, whether $d_j$ is the next admitted port end after $d_i$ **in one boundary-side response class**. Denote this relation by $\mathcal K_s(\omega)$. It is not a claim about which exchange occurs at a later physical time. The experiment or full enclosing record must distinguish that boundary-side relation from ordinary temporal succession.

For each selected complete record, require that the independently read $\mathcal K_s(\omega)$ is functional and consists of one three-cycle $\rho_s(\omega)$ on the incident port ends; require also that this corner cycle agrees with that record's measured complete-turn class. The entire owner may admit the two globally reversed classes, but a *specified* record must decide which corner relation belongs to its comparison. This agreement is the **corner-fidelity condition**:

$$
\boxed{\mathcal K_s(\omega)=\operatorname{graph}(\rho_s(\omega)),\quad
\rho_s(\omega)^3=\mathrm{id},\quad
\rho_s(\omega)\text{ has one three-element orbit}.}
\tag{154.15}
$$

A record that distinguishes only chronological succession has not passed this condition.

**Channel-side comparison.** At each reciprocal interface $e_i$, the complete owner can distinguish two independent test-response directions $\mathbf a_i,\mathbf b_i\in\mathbb Z^2$ (or directly distinguish two opposite side tags). The full paired response determines how the oriented pair is read at the other endpoint. In a shared count frame, define the relative parity

$$
\eta_i=\operatorname{sgn}\!\left[
\det(\mathbf a_{V,i},\mathbf b_{V,i})\,
\det(\mathbf a_{U,i},\mathbf b_{U,i})
\right]\in\{-1,+1\}.
\tag{154.16}
$$

Nondegeneracy of the two response pairs is required. This parity is invariant under a **common** change of two-component count basis: each determinant receives the same multiplicative determinant factor. In the selected *untwisted reciprocal* read, the channel transport preserves the orientation of the two-component comparison ($\eta_i=+1$) while reversing the direction of the channel dart, so the two traversal-side labels are paired oppositely.

The statement $\eta_i=+1$ is an **operational condition to be independently established**, not a theorem from the single longitudinal vectors $\mathbf p_i$. If a general local twist is admitted, a pure rotation system no longer specifies the whole embedded surface; one needs the measured signed edge scheme.

Call an enclosing owner *corner-and-side complete* when it fixes every $\mathcal K_s$ and every two-sided reciprocal edge pairing. The untwisted owner studied next is a concrete positive witness.

## 154.7. Theorem: unique two-dimensional attachment from complete operational comparisons

**Theorem 154.3 — Operational cellular completion.** Let a connected finite reciprocal graph have a fixed-point-free dart reversal $\alpha$. Suppose that for a specified complete response record $\omega$, a corner-and-side-complete owner fixes (i) one cyclic corner-successor permutation $\rho_s(\omega)$ on all outward darts at each vertex, and (ii) mutually compatible untwisted side pairings on each reciprocal edge. Then its complete **orientable** cellular attachment is uniquely determined up to labeled cellular isomorphism. If the enclosing read identifies $\omega$ with its simultaneously reversed counterpart, the unoriented attachment is uniquely determined up to common reversal. Its face boundaries are exactly the orbits of

$$
\boxed{\sigma_{\omega}=\prod_s\rho_s(\omega),\qquad\phi_{\omega}=\sigma_{\omega}\circ\alpha.}
\tag{154.17}
$$

**Proof.** For any directed channel end $d$, a compatible boundary traversal must first cross its channel, reaching the reversed dart $\alpha(d)$. The independently supplied side-pairing condition then requires taking precisely the next same-side corner at the receiving junction. Corner fidelity makes this the unique dart $\sigma(\alpha(d))$. Thus **every** admissible oriented face-boundary successor must equal $\phi(d)$; there is no choice of face edges left to make.

Since $\alpha$ and $\sigma$ are permutations, $\phi$ is a permutation. Every dart belongs to exactly one orbit, and the disjoint orbits partition all possible face-border occurrences. Attach one oriented polygon along each such orbit. Every unoriented channel occurs exactly twice among the polygonal boundaries, once in each reciprocal dart direction. The untwisted, opposite-traversal side pairing glues those two occurrences consistently. Hence the quotient has no free boundary edges and has coherent local orientation. The incident corner links at each vertex are single circles because each $\rho_s$ is one cycle, so the quotient is a closed orientable two-dimensional cell complex whose underlying space is a surface. Connectedness of the graph makes it connected.

Any other oriented cellular completion respecting **the same** labeled edge reversals, measured corner-successor relation, and side pairings must have the same successor $\phi$, the same face orbits, and therefore the same polygonal attachment data. Its cellular realization is isomorphic to this one. Reversing every local corner convention simultaneously reverses the resulting global orientation but not the underlying intersection structure up to sign. $\square$

This is the desired **determination theorem**, not merely the observation that some favorable surface can be drawn. The distinction is that both the corner successor and channel side pairing are independent parts of the complete operational owner. The theorem does **not** infer them from chronology or conservation alone.

## 154.8. Application: exact genus-one and genus-zero outcomes

By Proposition 154.1, the prefix-neutral owner has matching ordered port turns. If its operational corner comparisons pass the fidelity test, then

$$
\rho_U=\rho_V=(1\ 2\ 3)
$$

or both equal the inverse cycle. If the channel-side tests also select untwisted reciprocal pairing, Theorem 154.3 gives

$$
\sigma_A=(e_1^+\ e_2^+\ e_3^+)(e_1^-\ e_2^-\ e_3^-),
$$

and direct permutation composition yields

$$
\boxed{\phi_A=(e_1^+\ e_2^-\ e_3^+\ e_1^-\ e_2^+\ e_3^-).}
\tag{154.18}
$$

Therefore there is exactly one complete face boundary. The full oriented attachment word is calculated, rather than imposed,

$$
\boxed{w_A=e_1e_2^{-1}e_3e_1^{-1}e_2e_3^{-1}.}
\tag{154.19}
$$

For its connected cellular completion,

$$
V=2,\qquad E=3,\qquad F=1,
\qquad \chi=V-E+F=0,
\qquad\boxed{g=1}.
\tag{154.20}
$$

The simultaneous inverse rotation produces the reversed complete boundary and the same genus.

For the opposed-turn counterowner with the same untwisted side convention,

$$
\sigma_B=(e_1^+\ e_2^+\ e_3^+)(e_1^-\ e_3^-\ e_2^-),
$$

there are precisely three two-dart face orbits:

$$
(e_1^+\ e_3^-),\qquad
(e_1^-\ e_2^+),\qquad
(e_2^-\ e_3^+).
\tag{154.21}
$$

Thus $V=2,E=3,F=3$, so $\chi=2$ and $g=0$. The same conservation equations and graph-cycle rank two have yielded no surviving first homology after the three complete face relations are attached.

**Corollary 154.4 — Finite symplectic selection.** In the specified corner-fidelitous, untwisted, prefix-neutral owner, all admitted pointed whole-process records determine one genus-one cellular completion **up to common reversal**, and hence one nondegenerate rank-two integral intersection class up to sign. The opposed-turn owner determines a genus-zero completion instead.

## 154.9. Integral intersection pairing and finite reduction

For the genus-one owner, the linear two-cell boundary is zero: each $e_i$ appears once in each direction in (154.19). Consequently

$$
H_1(X_{J^\sharp};\mathbb Z)=\ker D/\operatorname{im}\partial_2
\cong\mathbb Z^2.
\tag{154.22}
$$

A transparent check of the surface's intersection structure is obtained by collapsing one spanning-tree edge, for example $e_2$. The completed face word then becomes

$$
(e_1)(e_3)(e_1)^{-1}(e_3)^{-1}=[e_1,e_3].
\tag{154.23}
$$

Thus the two remaining loops have signed intersection number $\pm1$, with the sign fixed by the chosen global orientation. In the conserved-flow basis $u=e_1-e_2$ and $v=e_2-e_3$, the second loop is $-v$; therefore the same pairing is unimodular in $(u,v)$.

Choosing the global sign convention $I(u,v)=+1$ gives

$$
\boxed{\mathbb J_1=\begin{pmatrix}0&1\\-1&0\end{pmatrix},\qquad
\det\mathbb J_1=1.}
\tag{154.24}
$$

Global reversal sends $\mathbb J_1\mapsto-\mathbb J_1$, preserving alternation and nondegeneracy. For every $N\ge2$, reduction produces

$$
\left((\mathbb Z/N\mathbb Z)^2,\ I_N(x,y)=x^{\mathsf T}\mathbb J_1y\bmod N\right)
\tag{154.25}
$$

with a nondegenerate alternating form because its determinant is a unit modulo $N$.

There is no assertion that the local two-component momentum determinant *is* the resulting intersection form. The former is a count comparison that helps discriminate local orientation; the latter is a derived pairing on surviving **complete** recurrence classes.

## 154.10. Independent orientation, recursive replacement, and physical calibration

An arbitrary simultaneous reversal of the corner conventions reverses both local three-cycles. It reverses the selected global orientation, but does not change the face count, genus, rank of $H_1$, or nondegeneracy of the intersection pairing. Absolute handedness is not claimed to be selected by unoriented counting alone.

A common invertible change $B$ of the two-component directional-count frame multiplies each local determinant by $\det B$; hence the relative junction comparison

$$
\operatorname{sgn}[\det(\mathbf p_{U,1},\mathbf p_{U,2})\det(\mathbf p_{V,1},\mathbf p_{V,2})]
\tag{154.26}
$$

is unchanged. In the reciprocal example its value is $+1$. This *relative momentum-ray parity* is useful, but it is not a replacement for the independently required corner-fidelity and side-transfer tests.

A recursive replacement preserving the complete dart reversal, measured corner comparison, side-pairing relation, and induced integral homology identification preserves the intersection numbers. Replacement of individual native representatives does not then destroy the paired relation. Arbitrary changes of boundary or observation resolution are not claimed to preserve these objects.

After a separately specified real extension and physical ruler, clock, and momentum calibration, the rank-two intersection module admits a classical one-degree-of-freedom symplectic read $\omega=dq\wedge dp$. The present theorem does not determine the physical $q,p$ calibration, a unique Hamiltonian, stochastic transition rates, or realized closure frequencies.

## 154.11. What an operational test must distinguish

A physical test of this stronger reconstruction must distinguish **more than net inventory and longitudinal momentum**:

1. **Complete response comparison:** resolve the ordered, port-complete junction response and whether the two responses satisfy prefix-level cancellation rather than only final return.
2. **Corner fidelity:** determine whether the recorded ordered turn is the next *same-side boundary-corner* response, not merely the next event in time.
3. **Channel-sidedness:** resolve the transport of two independent response distinctions (or an equivalent two-side record) across every reciprocal channel, distinguishing an untwisted continuation from a permitted twist.

If all three comparisons are admitted and satisfy the stated finite owner, its face words and integral intersection form are fixed. If the latter two comparisons are not readable, the mechanical data remain consistent with multiple surface attachments and do not select one uniquely.

The new requirements are explicit observable/operational hypotheses, not covert physical phase coordinates. The finite proof establishes what follows **if** the actual enclosing compatibility contains them.

## 154.12. Results, scope, and continuation

**Exact results:**

- Seven local bounded inventory records; six pointed complete three-turn returns; two unpointed local orientation classes.
- Thirty-six unconstrained pointed joint returns; six under prefix-neutral response compatibility.
- Exact failure of temporal inventory/momentum records alone to determine boundary-corner attachment or transverse channel-sidedness.
- A deterministic and unique cellular face-boundary reconstruction from separately supplied complete corner and untwisted side-comparison records.
- For the selected aligned complete owner, one six-dart face, genus one, $H_1\cong\mathbb Z^2$, and unimodular alternating pairing, defined up to global sign.
- For the opposed-turn owner, three face circuits, genus zero, and trivial first homology.
- Compatibility of the nondegenerate pairing with orientation-preserving, complete-relation-preserving recursive replacement and all finite moduli.

**Not established:** that bare first-order conservation fixes $\mathcal K_s$ or channel-side transport; that a chronological sequence of fluid exchange is automatically a cellular corner; that all physical channels are untwisted; that a realized experimental junction supplies the postulated whole-comparison read; or that a physical Hamiltonian or time calibration is fixed by the finite count architecture.

The next experimentally and mathematically discriminating question is:

> **Does a realizable three-channel reciprocal mechanical junction supply a complete, measurable same-side corner-and-channel comparison, and does that comparison satisfy prefix neutrality and untwisted transport under admissible preparation changes?**

This is the required bridge from a finite **symplectic consistency construction** to a physically selected complete attachment relation. The distinction is no longer unspecified “geometry”: it is a finite, separately testable compatibility among response order, boundary corner, and channel-sidedness.

## Conclusion

R²D's boundary-first counting can reconstruct a nondegenerate symplectic intersection pairing from a complete finite mechanical compatibility **provided the enclosing owner determines corner successors and side pairing, not just temporal exchange sequences**. The formal determination is exact:

$$
\boxed{
\text{Complete junction-corner and side comparisons}
\;\Longrightarrow\;
\phi=\sigma\alpha
\;\Longrightarrow\;
\text{unique face attachment}
\;\Longrightarrow\;
(H_1,I_J).
}
\tag{154.27}
$$

For the explicit prefix-neutral reciprocal owner, the compatible face attachment is genus one and its integral intersection pairing is unimodular. Conservation and temporal turn records alone admit other attachments; that limitation is proved, not hidden. The mathematical bridge is complete **under a stated operational relation**, and its physical selection remains a clear test of enclosing distinguishability.

---

## Related canon, addenda, and mathematical background

- **R²D Part I:** boundary-owned native state domains, possibility, realized occurrence, and recursive replacement.
- **Addendum 116:** signed incidence and conserved inventory/momentum before physical transport.
- **Addenda 120 and 122:** native identity and complete enclosing composability before arbitrary joins.
- **Addendum 125:** possible process counts versus realized completed-closure recurrence.
- **Addenda 150–151:** reciprocal exchange, nested compatibility, and exact separation of possible and realized counts.
- **Addendum 152:** state and process event algebras, whole-process composability, and conditional process-first reconstruction.
- **Addendum 153:** integral symplectic pairing from complete oriented two-cell attachment, counterexample to incidence-only determination, and conditional classical continuum projection.
- **W. T. Tutte**, *Combinatorial Oriented Maps*, *Canadian Journal of Mathematics* **31** (1979), 986–1004: combinatorial dart, vertex rotation, and face permutation formalism.
- **J. L. Gross et al.**, rotation-system discussion and face boundary walks: https://www.cs.columbia.edu/~gross/research/StringOps-GKMT-AMC.pdf
- **J. L. Gross et al.**, extended rotation systems and face corners: https://www.cs.columbia.edu/~gross/research/EGRS-ACG-DAM1apr15.pdf
- **General signed embedding schemes:** https://www.cs.rochester.edu/~stefanko/Publications-new/C36.pdf

**Review status:** Author-approved for canon publication. The result requires the stated non-identifiability qualification and the explicit operational corner/side assumptions; omitting them would falsely turn a conditional reconstruction into a derivation from first-order conservation alone.
