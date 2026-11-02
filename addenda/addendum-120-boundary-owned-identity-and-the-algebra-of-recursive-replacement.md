---
r2d_id: "addendum-120"
title: "Addendum 120 — Boundary-Owned Identity and the Algebra of Recursive Replacement"
subtitle: "Native Identification, Readable Classification, Sufficient Interfaces, and Exact Composition"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 120
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-01"
promotion_basis: "explicit_author_authorization_2026-11-01"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
---

# R²D Addendum 120 — Boundary-Owned Identity and the Algebra of Recursive Replacement

*Native Identification, Readable Classification, Sufficient Interfaces, and Exact Composition*

**Status:** Author-approved for canon publication — November 1, 2026  
**Canonical basis:** R²D Part I, September 25, 2026 authoritative revision

## Abstract

R²D defines a native microstate as one compatible joint realization of the immediately subordinate peers and a macrostate as the enclosing boundary's readable classification of those realizations. Recursive replacement changes the count domain within which state identity is defined. A mathematical treatment must therefore distinguish native identity, readable classification, and the equivalence of responses to enclosing contexts.

This addendum introduces an explicit native-identification map ρ alongside the readable-classification map π. It proves invariance under changes of presentation, derives necessary and sufficient factorization conditions, and establishes exact composition through sufficient interfaces. Response classes retain native weights when they represent a fixed boundary; assigning one native unit to each class specifies a further count boundary. Exact gluing and hierarchy-coherence theorems identify when alternative descriptions count the same enclosing realizations. A finite example separates an EP regrouping of a fixed count from a recursive change of native domain. The resulting algebra describes replacement through boundary-owned domains and maps, with computational work assigned to a specified EP realization.

## 120.1. Boundary ownership and native realization

In Part I, the count boundary defines both the compatible joint realization domain and its readable classification. A native realization has a formally defined peer-resolved identity even when that identity is not individually readable from the enclosing boundary. Its membership in a readable class contributes to that class's multiplicity [1]. Finite-set and quotient identities supply the mathematical machinery; boundary ownership determines which domains and identifications those identities describe.

All realization, presentation, class, and context domains considered below are finite. A domain may be empty. Classification maps need not reach every named readable class; an unreached class has multiplicity zero. Quotient and intermediate-label maps are restricted to their images when surjectivity is required.

**Definition 1 — Native boundary specification.** A boundary B_J supplies its immediate peer roles I_J, their realization domains, an admitted joint relation Γ_J, and a readable classification c_J:

$$
\Gamma_J\subseteq\prod_{a\in I_J}X_{J,a},
\qquad
c_J:\Gamma_J\longrightarrow\mathcal S_J.
$$

Its tagged native domain, readable map, and native multiplicity are

$$
\mathfrak M_J=\{(B_J,\mathbf x):\mathbf x\in\Gamma_J\},
\qquad
\pi_J(B_J,\mathbf x)=c_J(\mathbf x),
\qquad
W_J(s)=|\pi_J^{-1}(s)|.
$$

A native realization is one member of this admitted joint domain. Distinct members can belong to the same readable class. The peer roles and their alternatives are part of the enclosing specification; adding an arbitrary descriptive label does not add a native possibility.

**Definition 2 — Presentation and native identification.** Let a candidate presentation domain and formal peer-identification maps be supplied:

$$
\mathcal D_J^0,
\qquad
e_{J,a}:\mathcal D_J^0\longrightarrow X_{J,a},
\qquad
e_J(d)=\bigl(e_{J,a}(d)\bigr)_{a\in I_J}.
$$

Define the admitted presentations and their native identification by

$$
\mathcal D_J=e_J^{-1}(\Gamma_J),
\qquad
\rho_J(d)=(B_J,e_J(d)).
$$

A complete presentation satisfies the coverage condition

$$
e_J(\mathcal D_J)=\Gamma_J.
$$

Thus the two-stage read is

$$
\boxed{
\mathcal D_J
\xrightarrow{\rho_J}
\mathfrak M_J
\xrightarrow{\pi_J}
\mathcal S_J,
\qquad \rho_J\text{ surjective}.
}
$$

The presentation may contain alternative encodings or finer comparison distinctions. Its cardinality has native meaning only through the declared identification. These maps describe boundary-owned relations; their mathematical direction does not make subordinate descriptions the causal source of the enclosing domain.

Define native identity equivalence and readable equivalence on presentations:

$$
d\sim_\rho d'
\iff \rho_J(d)=\rho_J(d'),
\qquad
d\sim_\pi d'
\iff \pi_J(\rho_J(d))=\pi_J(\rho_J(d')).
$$

Native identity equivalence refines readable equivalence. A difference within a native-identification fiber contributes no additional native realization. A difference between native realizations within one readable fiber contributes to its multiplicity.

**Theorem 1 — Presentation quotient and native-count invariance.** A complete presentation induces a bijection

$$
\mathcal D_J/{\sim_\rho}\ \cong\ \mathfrak M_J,
\qquad [d]_\rho\longmapsto\rho_J(d).
$$

Consequently,

$$
\boxed{
W_J(s)=
\left|
\left\{
\rho_J(d):
d\in\mathcal D_J,\ 
\pi_J(\rho_J(d))=s
\right\}
\right|.
}
$$

Any repetition or relabeling of presentations that preserves the native image preserves these multiplicities.

**Proof.** The quotient map is well-defined because native identification is constant on each equivalence class. Equality of its images implies equality of those classes, giving injectivity. Coverage gives surjectivity. Restricting the bijection to presentations whose native images have readable class s gives the count formula. That formula depends only on the image set, so preserving the image preserves every count. In particular, if h is a surjection from a new presentation domain onto the old one and the new native map is ρ_J composed with h, the two image sets coincide. ∎

For example, suppose the admitted native tuples are (1,0) and (0,1), both read as “one active.” Two presentations may identify (1,0), while a third identifies (0,1):

| Presentation | Native tuple under ρ_J | Readable class under π_J |
| - | - | - |
| d₁ | (1,0) | One active |
| d₂ | (1,0) | One active |
| d₃ | (0,1) | One active |

There are three presentations, two native realizations, and one supported readable class. The native multiplicity of “one active” is two. Repeated realized occurrences have a separately specified occurrence count.

## 120.2. Replacement as an enclosing relation

A change of boundary requires a new native specification. An old native realization and a new native realization may participate in one enclosing comparison without retaining the same state identity.

Let an enclosing comparison boundary L supply a domain D_L, native reads into two boundaries, and a retained-context read:

$$
a:D_L\to\mathfrak M_-,
\qquad
b:D_L\to\mathfrak M_+,
\qquad
u:D_L\to U_L.
$$

The readable source and target records are π\_- composed with a and π\_+ composed with b. The domain can associate one source realization with several target realizations. A function from source native labels to target native labels exists precisely when b is constant on the fibers of a; this follows from Theorem 2 below. Otherwise the complete joint relation, or additional retained context, supplies the replacement comparison.

When D_L itself is a declared domain of counted comparison realizations, its joint count is

$$
K_L(s,t,v)=
\left|
\{d\in D_L:
\pi_-(a(d))=s,\ 
\pi_+(b(d))=t,\ 
u(d)=v\}
\right|.
$$

Summing this count over source and context labels counts target extensions within D_L. It need not equal the target's native multiplicity. A classification-respecting bijection from D_L to the target native domain is sufficient for equality: it restricts to a bijection on each target readable fiber. Without such an identification, the two counts retain their respective boundary meanings.

The recursive form of native identification becomes explicit when the enclosing relation supplies deterministic peer exports. For a child presentation map and an enclosing-owned export map, write

$$
\rho_a:\mathcal D_a\to\mathfrak M_a,
\qquad
\tau_{J,a}:\mathfrak M_a\to X_{J,a}.
$$

On a complete tuple whose exports belong to Γ_J, the parent identification is

$$
\rho_J\bigl((d_a)_a\bigr)
=
\left(
B_J,\bigl(\tau_{J,a}(\rho_a(d_a))\bigr)_a
\right).
$$

A difference between child native realizations adds no parent native type when their exports agree. Different admitted export tuples are distinct parent native realizations, even when π_J groups them together. These tuple presentations must cover Γ_J to represent the full parent native domain.

If an export also depends on enclosing context, include that context in the complete comparison used by the peer-identification maps. This avoids assuming that an old readable label alone determines its replacement.

## 120.3. Factorization and sufficient classifications

**Theorem 2 — Factorization through a classification.** Let q be a surjection from a finite set X onto Y, and let h map X to Z. A unique map h̄ satisfying

$$
h=\bar h\circ q
$$

exists if and only if

$$
\boxed{
q(x)=q(x')\Longrightarrow h(x)=h(x').
}
$$

**Proof.** If the factorization exists, equal q-values have equal h-values by substitution. Conversely, assign h̄(q(x)) the value h(x). The stated condition makes the assignment independent of the representative. Surjectivity makes it defined on all of Y and unique. ∎

Taking h to be native identification gives the native factorization criterion:

$$
\rho_J=\bar\rho_J\circ q
\quad\Longleftrightarrow\quad
q(d)=q(d')\Longrightarrow\rho_J(d)=\rho_J(d').
$$

This criterion concerns identification of the target native realization. Earlier subordinate distinctions may be replaced wherever the target map already identifies their descriptions. A finer q may retain several labels for one target realization; native counting still counts its distinct native images once.

Now fix a finite family C of enclosing contexts and responses g(μ,c) defined on native realizations. Each context includes the complete joint continuation relevant to the declared read.

A response initially defined on presentations descends to native realizations exactly when it is constant on native-identification fibers. Theorem 2 applied to its full response vector proves this condition. If it fails, that response uses an additional comparison distinction and requires a correspondingly enlarged domain or retained context.

**Definition 3 — Complete readable response profile.** Include the native boundary's readable class in the profile:

$$
\Phi_J(\mu)=
\left(
\pi_J(\mu),\ 
\bigl(g(\mu,c)\bigr)_{c\in C}
\right),
\qquad
\gamma_J:\mathfrak M_J\to Q_J=\operatorname{im}\Phi_J,
\qquad
\gamma_J(\mu)=\Phi_J(\mu).
$$

Projection onto the first component defines θ_J, so

$$
\pi_J=\theta_J\circ\gamma_J.
$$

**Corollary 2.1 — Coarsest sufficient response classification.** The profile classification γ_J is sufficient for the declared readable class and every permitted response. Any other sufficient surjective classification q factors uniquely onto it.

**Proof.** Every required read is a component of the profile and is therefore constant on its fibers. If q assigns the same label to two native realizations, sufficiency requires every profile component to agree. Theorem 2 then gives a unique map k with γ_J = k composed with q. ∎

This coarseness is relative to the declared response family. Adding a context can split classes. It does not establish that every exact count representation must reconstruct individual native realizations.

At a fixed native boundary, each response class retains the weight

$$
w_J(q)=|\gamma_J^{-1}(q)|.
$$

Partitioning a native readable fiber into these disjoint response-class fibers gives

$$
\boxed{
W_J(s)=\sum_{q:\theta_J(q)=s}w_J(q).
}
$$

These weights count current native realizations. They exclude presentation duplicates and do not automatically inherit a previous boundary's multiplicities. Two native realizations with identical responses remain two contributors to the weight of their common response class.

## 120.4. Exact aggregation and substitution

For a supplied finite count domain X, a surjection q to Y, and a nonnegative integer profile f, define aggregation by

$$
(q_*f)(y)=\sum_{x:q(x)=y}f(x).
$$

The domain identifies what the summands count. Taking X to be the native domain and f to be one gives native class weights. Taking X to be a presentation domain instead counts presentations unless its native identifications have already been accounted for.

**Theorem 3 — Universal count substitution.** A response g(x,c) with nonnegative integer values descends through q if and only if there is a response ḡ on Y satisfying, for every nonnegative integer profile f,

$$
\boxed{
q_*(f\,g_c)=(q_*f)\,\bar g_c.
}
$$

The equality is pointwise on Y; products are ordinary multiplication.

**Proof.** If g descends, then for every y and c,

$$
\sum_{x:q(x)=y}f(x)g(x,c)
=
\sum_{x:q(x)=y}f(x)\bar g(y,c)
=
\left(\sum_{x:q(x)=y}f(x)\right)\bar g(y,c).
$$

Conversely, choose f to be one at a single x and zero elsewhere. The identity requires ḡ(q(x),c) = g(x,c). Repeating this argument for each member of a q-fiber forces the response to be constant there. Theorem 2 gives the unique descended response. ∎

For Boolean existence, replace addition by OR and multiplication by AND. The same proof applies, including the single-label profile used for necessity. Equivalently, for nonnegative counts the support map satisfies

$$
\mathbf1\!\left[\sum_i n_i>0\right]
=\bigvee_i\mathbf1[n_i>0],
\qquad
\mathbf1[mn>0]
=\mathbf1[m>0]\wedge\mathbf1[n>0].
$$

Existence and exact multiplicity are distinct reads. Existence does not determine a positive count.

**Theorem 4 — Composition of aggregation.** For surjections q from X to Y and p from Y to Z,

$$
p_*(q_*f)=(p\circ q)_*f.
$$

**Proof.** Partition the direct fiber by its intermediate label:

$$
[p_*(q_*f)](z)
=
\sum_{y:p(y)=z}\sum_{x:q(x)=y}f(x)
=
\sum_{x:p(q(x))=z}f(x).
$$

Every source entry appears once in the relevant disjoint partition. ∎

This identity reexpresses a specified count. A declaration of a new native domain is a separate operation.

## 120.5. Shared interfaces and exact gluing

Composition across overlapping comparisons requires the shared read to remain consistent. Let counted domains D₁ and D₂ have interface maps into the same set U. Their matching-pair domain is

$$
D_1\times_U D_2
=
\{(d_1,d_2):u_1(d_1)=u_2(d_2)\}.
$$

Matching labels refer to a supplied enclosing correspondence. Additional joint constraints must be included in the admitted pair domain.

**Theorem 5 — Count multiplication under exact gluing.** Suppose an enclosing boundary L defines a native domain with a bijection

$$
\lambda:D_1\times_U D_2
\overset{\sim}{\longrightarrow}\mathfrak M_L.
$$

Let D₁ carry an outer read a and D₂ an outer read b, and suppose the native readable map satisfies π_L(λ(d₁,d₂)) = (a(d₁),b(d₂)). Define

$$
K_1(s,v)=|\{d_1:a(d_1)=s,\ u_1(d_1)=v\}|,
\qquad
K_2(v,t)=|\{d_2:u_2(d_2)=v,\ b(d_2)=t\}|.
$$

Then the native count for the joint read is

$$
\boxed{
W_L(s,t)=\sum_{v\in U}K_1(s,v)K_2(v,t).
}
$$

**Proof.** Partition the joint native fiber by interface value v. The bijection identifies each part with the Cartesian product of the corresponding local fibers. Their cardinalities multiply. The interface parts are disjoint, so their cardinalities add. ∎

The bijection establishes that every counted pair is admitted and that each native realization is counted exactly once. If different pairs identify the same native realization, the pair count is a comparison count; native counting takes the distinct images under the actual identification map.

For example, let one local domain contain two records requiring shared value 0, while the other contains two records requiring shared value 1. Each separate count is two, but the admitted matching-pair domain is empty. Multiplying the separate totals gives four; retaining the interface gives zero. A product of separate possibilities is justified only by the enclosing joint relation.

## 120.6. Native composition and hierarchy coherence

Successive factorizations preserve a fixed target identification. Let r₀ be ρ_J and suppose that surjective intermediate maps satisfy

$$
\mathcal D_J=Y_0
\xrightarrow{q_1}Y_1
\xrightarrow{q_2}\cdots
\xrightarrow{q_m}Y_m,
\qquad
r_{k-1}=r_k\circ q_k.
$$

Repeated substitution gives

$$
\boxed{\rho_J=r_m\circ q_m\circ\cdots\circ q_1.}
$$

Each step is valid exactly under Theorem 2's fiber condition for the current target-identification map. The final native image and its π_J-fiber counts therefore remain unchanged. This preserves target-boundary identity without imposing persistence on subordinate state identities.

A local construction gives an explicit family of sufficient formal interfaces. Assume the candidate presentation admits a supplied finite coordinate factorization,

$$
\mathcal D_J^0=\prod_{\ell\in L}E_\ell.
$$

These are comparison coordinates. Compatibility remains governed by the enclosing relation. Extend native identification to all candidates by assigning a rejection value to inadmissible ones:

$$
\widetilde\rho_J(d)=
\begin{cases}
\rho_J(d),&d\in\mathcal D_J,\\
\bot,&d\notin\mathcal D_J.
\end{cases}
$$

For a block A of comparison coordinates, define its complete identification profile by

$$
\Psi_A(d_A):
z\longmapsto\widetilde\rho_J(d_A,z),
\qquad
z\in\prod_{\ell\in L\setminus A}E_\ell.
$$

Two block descriptions have the same formal interface when these functions agree. The profile retains both admissibility and target native identity for every complementary comparison. It is distinct from the Boolean response profile used to answer an existence query.

**Theorem 6 — Native hierarchy coherence.** For disjoint A and B, the operation

$$
\nu_{A,B}\bigl(\Psi_A(d_A),\Psi_B(d_B)\bigr)
=
\Psi_{A\cup B}(d_A,d_B)
$$

is well-defined and associative on disjoint blocks. Every binary hierarchy formed by these operations reaches the same target native realization or rejection value. With complete coverage, every hierarchy has the same admitted native image and native multiplicities.

**Proof.** Suppose representatives d_A and d′\_A have equal A-profiles, and d_B and d′\_B have equal B-profiles. For every remaining complement z,

$$
\widetilde\rho_J(d_A,d_B,z)
=
\widetilde\rho_J(d'_A,d_B,z)
=
\widetilde\rho_J(d'_A,d'_B,z).
$$

The first equality uses A-profile equality and the second B-profile equality. Thus the union profile is independent of representatives.

For three disjoint blocks, both parenthesizations identify the profile of the same combined comparison. Therefore

$$
\nu_{A\cup B,C}\bigl(\nu_{A,B}(u,v),w\bigr)
=
\nu_{A,B\cup C}\bigl(u,\nu_{B,C}(v,w)\bigr).
$$

Inducting over a hierarchy shows that each node carries the profile of its combined comparison. At the root, the complement is empty, and the profile's value is precisely the target native realization or rejection. Coverage identifies the admitted root values with the whole native domain. Counting each distinct admitted value once in its readable fiber gives W_J.

An identically rejected partial profile can be discarded: it has no admitted continuation, including every possible later join. Thus rejection introduces neither missing admitted realizations nor spurious ones. ∎

**Overlapping joins.** A sufficient interface for overlapping A and B retains their shared comparison read S = A ∩ B:

$$
\widehat\Psi_{A\mid S}(d_A)
=
\bigl(d_S,\Psi_A(d_A)\bigr).
$$

Only matching shared reads are joined. Replacing an A representative with an equivalent one leaves S unchanged, and then replacing the B representative leaves it unchanged again. The two substitutions in Theorem 6 therefore preserve the glued comparison's target identification.

If a parent must retain a shared read T for later joins, the children retain S together with their respective parts of T. The same proof preserves both the parent identification profile and the required shared read. Induction establishes coherence for such exact overlapping hierarchies. The complete enclosing relation must remain represented; pairwise projections alone need not preserve it.

The profiles in this theorem are formal identification interfaces. They do not declare native identities individually readable as macrostates. A count representation can use weighted response classes instead, provided its composition preserves the required native counts and shared compatibility.

## 120.7. Equality of replacement descriptions

The preceding results permit an exact comparison of two descriptions claiming to represent the same boundary-owned replacement.

Let a fixed enclosing owner supply a common admitted comparison domain D and two complete presentations

$$
\rho_1:D\twoheadrightarrow\mathfrak M_1,
\qquad
\rho_2:D\twoheadrightarrow\mathfrak M_2.
$$

Use common readable labels, contexts, and response value sets. Let Φ₁ and Φ₂ be the complete readable response profiles, including π₁ and π₂ as in Definition 3.

**Definition 4 — Equivalent replacement descriptions.** The descriptions are equivalent when there is a native-domain bijection α satisfying

$$
\alpha\circ\rho_1=\rho_2,
\qquad
\Phi_2\circ\alpha=\Phi_1.
$$

The first equation preserves which complete comparisons identify the same native realization. The second preserves readable classification and every declared response.

**Theorem 7 — Native equivalence criterion.** Such a bijection exists and is unique precisely when

$$
\rho_1(d)=\rho_1(d')
\iff
\rho_2(d)=\rho_2(d')
\quad\text{for all }d,d'\in D,
$$

and

$$
\Phi_1(\rho_1(d))=\Phi_2(\rho_2(d))
\quad\text{for all }d\in D.
$$

Equivalent descriptions have equal native multiplicities for every corresponding readable class.

**Proof.** A commuting bijection preserves and reflects equality of native images, and profile preservation gives the second condition. Conversely, define α(ρ₁(d)) = ρ₂(d). Equality of native-identification equivalences makes this assignment well-defined and injective; coverage makes it surjective. The profile condition gives preservation of every readable response. Coverage also makes α unique. Its restriction to each readable fiber is a bijection, so the fiber cardinalities agree. ∎

The common comparison and owner are supplied parts of this criterion. An abstract isomorphism between independently specified boundaries does not by itself establish that they are the same boundary.

## 120.8. A new native count domain

A response-class representation of a fixed native boundary retains its native class weights. A recursive replacement can instead declare those classes to be native realization types at a new boundary.

For a specified class map q and nonnegative profile f, let a = q\_\*f. Introduce B\_+ with one newly tagged native type per supported q-class and a declared readable map r:

$$
\mathfrak M_+
=
\{(B_+,y):a(y)>0\},
\qquad
\pi_+(B_+,y)=r(y).
$$

Its native multiplicity is

$$
\boxed{
W_+(t)=\sum_{y:r(y)=t}\mathbf1[a(y)>0].
}
$$

The new identification on positive-support presentations is

$$
\rho_+(x)=(B_+,q(x)),
\qquad x\in X^+=\{x:f(x)>0\}.
$$

This is an explicit new-boundary rule: the supported q-labels are stipulated as identifiers of the new compatible joint peer realizations. Their correspondence with those peer realizations is part of the target boundary specification in Definition 1. If q instead represents an existing native domain, its existing class weights continue to count realizations at that boundary. Equality of responses supplies sufficiency for the declared read; the new native specification supplies the changed count identity.

Write η(n) = 1 when n is positive and η(0) = 0, with the result interpreted as a nonnegative unit count.

**Theorem 8 — Support composition under unit replacement.** For finite class maps q and p and a nonnegative profile f,

$$
\eta\!\left(p_*\eta(q_*f)\right)
=
\eta\!\left((p\circ q)_*f\right).
$$

Here η acts pointwise.

**Proof.** At a target label z, the left side is one exactly when some y with p(y) = z has a positive q-fiber sum. That occurs exactly when some x with p(q(x)) = z has positive f(x), which is the condition for the right side to be one. Both sides are zero otherwise. ∎

The theorem establishes equality of final support. Positive counts before the last unit replacement can differ. Equal support alone therefore does not identify two native count domains.

A four-peer example makes the distinction concrete. Suppose J has four binary immediate peer roles, admits every joint tuple, and reads the active count k. The native domain has sixteen members, six of which have k = 2.

An EP grouping of this fixed count into two pairs gives

$$
W_J(2)=1\cdot1+2\cdot2+1\cdot1=6.
$$

Grouping into three positions and one gives

$$
W_J(2)=3\cdot1+3\cdot1=6.
$$

The intermediate count labels do not identify individual four-peer native realizations, but their weights count the fixed J-owned fibers exactly.

If the intermediate count classes instead become unit native peer types at a new boundary, the immediate pairs giving k = 2 are different:

| New native grouping | Admitted class pairs with total two | Native count |
| - | - | - |
| Two-position class with two-position class | (0,2), (1,1), (2,0) | 3 |
| Three-position class with one-position class | (1,1), (2,0) | 2 |

These are different native-domain specifications. A further replacement to one unit per admitted final count class would introduce another native boundary. Each count follows from its own identification and classification maps.

## 120.9. Consequences for recursive counting

Native identification, readable classification, and response equivalence have distinct mathematical roles. Native identification determines the counted units. Readable classification groups those units into macrostates. Response equivalence determines which labels suffice for specified enclosing comparisons.

At a fixed boundary, exact reclassification retains the appropriate native weights. Across a boundary change, the enclosing specification defines the new joint realization domain and the new count identity. The factorization and coherence theorems establish when descriptions can be substituted or regrouped while retaining the same target relation. A changed native domain requires its own specification.

For a positive native multiplicity, the dimensionless logarithmic read is S = ln W. Its value depends on the native count domain. Consequently, wells and harmonic relations must be derived from specified native multiplicities. They cannot be inferred solely from the number of presentation labels or the existence of a response-class quotient.

This provides the foundation for constructing nested-well compatibility families with explicit native identifications, readable classes, and replacement rules.

## Appendix A EP realization and finite verification

The algebra specifies finite domains, maps, and equalities. Representing a response profile as a table, enumerating its entries, comparing rows, traversing a hierarchy, and storing count weights are operations of an EP realization. Their work bounds belong to that specified representation and procedure.

A direct finite realization forms the required response rows, groups equal rows, retains native image identifications or native class weights as appropriate, and joins labels using complete shared interfaces. Theorem 2 establishes the factorization criterion; Theorems 3–6 establish the relevant substitution and composition laws. These statements do not assign a primitive computational cost to replacement.

Finite checks supplemented the proofs. Selected checks are listed below.

| Finite domain or construction | Checks performed | Result |
| - | - | - |
| Every compatibility subset of two binary peer roles, with one to three presentations per native realization | 256 complete presentations; 10,339 native-image and weighted-class count comparisons | Passed |
| Native-identification maps on four presentation labels with up to three native targets | 765 factorization cases; 862 native-image count checks; 318 legal two-stage chains | Passed |
| Every map from three binary comparison coordinates into rejection and two target native labels | 6,561 maps; 472,392 disjoint-join checks; 314,928 associativity checks; 52,488 retained-overlap checks | Passed |
| Boolean responses on three binary coordinates and two enclosing contexts | 65,536 relations; complete-profile joining, associativity, and retained-overlap checks | Passed |
| Fixed four-peer counting and replacement by intermediate count classes | Fixed-target count six under both EP groupings; new pair-domain counts three and two | Matched the derived counts |

The checks included empty compatibility domains, duplicate presentations, and failures caused by omitting required shared distinctions. They verify finite implementations of the formulas. The proofs establish the general statements independently of those enumerations.

## Reference

[1] R²D Part I — *A Theory of Dimensionless Recursive Counting*, canonical revision 2026-09-25, §3.2.1 and Appendix A, Axioms 1–6. These define boundary-relative native realizations, readable classification, enclosing compatibility, and recursive replacement. The explicit identification map and the algebraic results developed here formalize those distinctions using finite sets, fibers, quotients, and compatible products.
