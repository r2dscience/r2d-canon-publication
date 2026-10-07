---
r2d_id: "canon-part-i"
title: "R²D Part I — A Theory of Dimensionless Recursive Counting"
source_type: "canon"
authority: "canonical"
part: 1
canon_revision: "2026-09-25"
publication_baseline_snapshot: "2026-09-14"
source_format: "authoritative_markdown"
source_of_truth: true
indexable: false
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
semantic_amendments:
  - "2026-09-25-universal-statistical-architecture"
  - "2026-09-25-causal-architecture-logical-status"
  - "2026-09-25-structural-universality-and-domain-mapping-status"
review_status: "authoritative"
---

# Recursively Realized Distinguishability (R²D)

## Part I — A Theory of Dimensionless Recursive Counting

> **Authoritative Markdown Canon.** This file is the authoritative scientific source for R²D Part I beginning with Canon revision 2026-09-25. Mathematical notation was normalized from the equation-preserving Word/OMML source into LaTeX. The September 14, 2026 publication is the archival baseline; explicitly listed semantic amendments define the current Canon revision.

## Contents

- 1.0 Abstract
- 2.0 Introduction
- 3.0 The Primitive Counting Structure of R²D
- 4.0 Principles
- 5.0 Readability Limits and Epiphenomenological (EP) Projection
- 6.0 Two Horizons
- 7.0 Discussion
- Appendix A — Formalism of Dimensionless Recursive Counting
- Appendix B — Worked Example: Recursive Counting in a Coin Ensemble
- Appendix C — Symbol Summary
- References


## 1.0 Abstract

---
r2d_id: "canon-p1-1.0"
title: "Part I — 1.0 Abstract"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 26
pdf_page_end: 26
semantic_amendment: "2026-09-25-structural-universality-and-domain-mapping-status"
review_status: "authoritative"
---
# 1.0 Abstract

Recursively Realized Distinguishability (R²D) is a theory of dimensionless recursive counting motivated by observations in active muscle, where structural change tracks the distribution of protein-switch states rather than the trajectory of any individually identifiable switch. R²D asks whether this reflects a more general principle: that physical states are defined by the boundaries within which distinctions are counted.

At any count boundary, a **macrostate** is a readable state and a **microstate** is one compatible joint realization of the immediately subordinate states. Multiplicity counts how many such realizations belong to each macrostate. This definition makes statehood boundary-relative and separates possible structure from its realization: subordinate transitions can change which state is realized, but they cannot create the multiplicity landscape within which that realization is classified.

R²D then proves a second result. The directional support of a local state depends not only on its native multiplicity but also on how many enclosing realizations are compatible with it. Changing only this enclosing compatibility can create, cancel, or reverse local directional support while leaving the local multiplicity landscape unchanged. An exact coin construction provides a finite illustration of both results.

Statistical mechanics supplies the complementary empirical evidence. For more than a century, experiments have shown that changing enclosing thermal, chemical, mechanical, or field conditions changes local state occupancy. Canonical statistical mechanics likewise derives local statistical weighting from the state structure and constraints of the larger system. R²D therefore separates two roles that are commonly conflated: **subordinate dynamics supply realization; enclosing multiplicity and constraint supply organization.** This reverses the conventional bottom-up attribution of causal agency while preserving the successful mathematics of statistical mechanics.

Across boundaries, completed local realizations are recursively reclassified rather than causally assembled upward. R²D further distinguishes exact structural closure from reciprocal realization and proposes that nonreciprocal occurrence around a local cycle is read at the enclosing boundary as nondirectional background.

R²D thus develops a formal enclosing-to-local ontology based on multiplicity, compatibility, realization, closure, and recursive replacement before energy, temperature, probability, force, field, matter, space, or time are introduced. Statistical mechanics has no preferred physical scale and empirically realizes this same architecture across physical systems. R²D therefore treats the primitive macrostate–microstate count architecture as structurally universal wherever scientific states admit distinguishable macrostates and compatible subordinate realizations. What remains domain-specific is the physical mapping by which a particular theory reads that universal architecture. Gravity, quantum theory, biology, cosmology, and other domains must therefore test their proposed R²D mappings; they do not require a separate re-proof of the primitive statistical grammar.


## 2.0 Introduction

---
r2d_id: "canon-p1-2.0"
title: "Part I — 2.0 Introduction"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 27
pdf_page_end: 37
semantic_amendment: "2026-09-25-causal-architecture-and-structural-universality-synchronization"
review_status: "authoritative"
---
# 2.0 Introduction

The question is simple.

**Why do we use additive mathematics to describe a universe within which distinguishable multiplicities compose multiplicatively?**

Science starts with counting. But counting is usually introduced after the things being counted have already been defined. Once a set of objects and a count domain are given, addition is natural: one object plus another produces a larger count. However, that does not explain how a distinguishable whole arises from subordinate realizations.

At every nonprimitive count boundary, a distinguishable state can be realized in multiple compatible ways by subordinate states. Mutually exclusive possibilities within one count domain add. Compatible possibilities that jointly realize a larger state multiply. Their logarithms transform that multiplicative structure into additive coordinates.

The whole is therefore not primitively the arithmetic sum of its parts. It is the multiplicity of compatible ways in which subordinate distinctions can realize the whole. This distinction is familiar in statistical mechanics (1--4). A macrostate is not defined by adding its microstates. Its multiplicity counts how many microscopic realizations belong to it. Yet the causal interpretation of this structure has usually remained mechanistic: microscopic transitions are treated as the agents through which the system evolves toward macroscopic states of greater statistical weight (1, 5).

R²D separates two relations that the conventional mechanistic interpretation joins. A subordinate transition can change which realization is occupied. It cannot create the multiplicity landscape within which that realization is classified. This follows generally from the definitions. At a fixed boundary $B_{n}$, the compatible formal microstate domain and its macrostate classification define

$$W_{n,i} = \left|\pi_{n}^{-1}(i)\right| .$$

Changing realization does not change this cardinality unless the boundary-defined count domain or classification itself changes.

A second result follows from the enclosing compatibility relation. For two local alternatives, the complete compatible-count difference is determined jointly by native local multiplicity and the multiplicity of compatible enclosing extension. Because the enclosing extension relation can change while the native local landscape remains fixed, enclosing compatibility can create, cancel, or reverse the directional support of the local alternatives without changing their native multiplicities.

These are general results of the R²D formal architecture.

The coin construction developed later provides a finite exact realization of them. It makes visible, without energy, force, probability, or dynamics, both the invariance of local multiplicity under realization and the ability of enclosing compatibility to reverse local directional support.

Statistical mechanics then supplies the empirical complement: changing enclosing thermal, chemical, mechanical, or field conditions changes the relative realization of local states.

Together these results establish the formal causal ordering that follows from the R²D state definitions and enclosing-compatibility theorem:

**The enclosing relation organizes which realization is favored. The subordinate process determines how that realization occurs.**

Statistical mechanics then supplies the empirical realization of this ordering across physical systems without assigning it a preferred scale.

### 2.1 Multiplication Beneath Addition

The relation

$$S = \ln W$$

is ordinarily introduced as an equation for entropy. R²D reads it first as a statement about counting. If compatible multiplicities compose,

$$W_{joint} = \prod_{a}W_{a},$$

then

$$\ln W_{joint} = \sum_{a}\ln W_{a}.$$

Logarithmic addition is therefore the additive reading of multiplicative composition. This relationship is more primitive than any particular thermodynamic interpretation. Multiplication describes the number of compatible ways a joint realization can occur. The logarithm converts that multiplicative structure into an additive coordinate. The distinction matters because additive mathematics can describe a system with extraordinary precision while concealing the count structure beneath the coordinate.

R²D does not reject additive mathematics. It asks what addition is measuring. At the primitive level, two operations are sufficient to generate much of the mathematical structure used later in science: **compatible possibilities multiply;** **mutually exclusive alternatives add.** Logarithms make the first readable through the second.

Units can subsequently be assigned to these additive coordinates. Entropy, energy, chemical potential, action, frequency, probability, curvature, and other familiar quantities may then become measurable physical readings of relations that began as dimensionless count structure.

Science is not made of units. Science uses units to read primitive counts. R²D begins before units are assigned.

### 2.2 The Empirical and Conceptual Origins of R²D

R²D originated in active muscle. A contracting muscle is a locally cycling system that converts an externally maintained asymmetry into force, shortening, heat, and structural change. The molecular transitions involved in contraction are themselves realized under chemical and mechanical conditions defined outside the individual molecular transition (6--8).

Following the source of asymmetry repeatedly encounters another enclosing relation on a larger scale. This motivated a simple question: **Does the subordinate event generate the direction of change, or does it realize a direction defined by a larger organization?**

Simultaneous measurements of force and protein-switch distributions in active muscle motivated the second interpretation (9--12). The experimentally readable structural change tracked the distribution of switch states across a multiplicity landscape rather than the trajectory of an individually identifiable switch. Individual molecular transitions remained necessary for contraction, but the ensemble relation---not the trajectory of one switch---was the structural quantity that changed with force and closure.

This suggested that mechanism and causal organization might not be identical (13--16). A molecular transition can describe how a structural change is realized without necessarily defining why that realization is favored. The same distinction appears much more broadly in science.

Whole-system relations have repeatedly been established before subordinate mechanisms were proposed to explain them. Kepler described orbital regularities before Newtonian dynamics (17). Carnot described cyclic thermal organization (18) before microscopic theories of heat (18, 19). Hill described reproducible relations among force, shortening, and heat (7) before molecular models of contraction (20, 21).

These histories do not prove that whole-system relations are causally primitive. They show that successful science does not require causal explanation to begin with the smallest readable object.

Boltzmann introduced the deeper mathematical clue (22). Statistical mechanics relates macroscopic states to the number of microscopic realizations compatible with them. Multiplicity therefore determines the structure of the macroscopic state space. But this creates a causal problem that is easy to overlook. **Microscopic transitions can move realization through that state space. They cannot create the multiplicity of the states through which they move.**

The formal R²D definitions make the distinction exact. Multiplicity is defined by the boundary-relative classification of compatible realizations and therefore cannot be generated by the particular transitions that subsequently realize it. The enclosing-compatibility relation adds a second theorem: while the native local multiplicity landscape is held fixed, varying only compatible enclosing extension can create, cancel, or reverse the complete directional count relation between local alternatives.

The coin construction is an exact finite illustration of these general results. Individual coin transitions change realization and occupancy but cannot generate the ensemble multiplicity landscape. Recursively composing ten already-defined local landscapes then shows explicitly how enclosing compatibility can reverse the directional support of a local transition without restoring the subordinate coin identities as primitive objects.

Statistical mechanics supplies the complementary empirical result. The formal enclosing-to-local architecture derived by R²D is not merely mathematically possible. Local state occupancies respond reproducibly to enclosing conditions. Temperature, applied fields, chemical potential, pressure, mechanical constraint, and related relations alter which local states are preferentially realized. Canonical statistical mechanics expresses the same organization mathematically by deriving the relative weighting of local states from the state structure and constraints of the larger system.

R²D therefore does not merely observe that statistical mechanics resembles a recursive count theory. It formally exposes the primitive count architecture beneath an empirically established statistical relation. The coin construction removes energy, temperature, force, field, matter, and probability and demonstrates that unequal enclosing compatibility alone is sufficient to create directional count support among local alternatives. The resulting causal architecture is not an additional assumption imposed on the count structure. It follows from the definitions of boundary-relative statehood together with the enclosing-compatibility result:

**the enclosing relation defines the organization of local realization; subordinate transitions realize that organization.**

A formal microstate has microstate meaning only relative to the enclosing boundary that defines the compatible realization domain and its classification. A subordinate transition therefore cannot be logically prior to the state relation required for it to possess microstate identity at that boundary. Likewise, a local transition cannot be sufficient to define a directional relation that can be created, cancelled, or reversed by changing enclosing compatibility while the native local landscape remains fixed.

The conventional mechanistic hierarchy commonly assigns causal priority in the opposite direction because subordinate events are directly observable and necessary for the change. Necessity for realization does not establish primitive causal priority. A competing bottom-up account must therefore provide an alternative formal definition of the macrostate–microstate relation, or an equivalent whole–part state architecture, from which bottom-up causal sufficiency follows.

### 2.3 What Is R²D?

R²D is a theory of boundary-indexed recursive counting. A boundary is not necessarily a physical surface. It is the relation that defines a count domain. It determines which differences are distinguishable, which subordinate realizations are mutually compatible, which compatible realizations belong to the same readable state, and which completed local processes count as realizations of an enclosing occurrence.

Statehood is therefore boundary relative. A state does not first exist independently and then acquire a boundary label. The boundary defines the count domain within which that state has meaning. Within a boundary, R²D distinguishes three count structures that are often conflated.

**Multiplicity** is possible count. It is the number of compatible joint realizations classified as a distinguishable macrostate. **Occurrence** is realized count. It counts realized instances within the specified count domain. **Occupancy** is realized structure. It records how occurrence is distributed among the available macrostates.

A formal microstate at boundary $B_{n}$is one compatible joint realization of the peer subordinate boundaries. A macrostate is the boundary-defined classification of such microstates. Multiplicity therefore belongs to the classification structure itself. This distinction is central. A realized transition can change occurrence or occupancy. It does not thereby change the multiplicity of the macrostate being occupied.

R²D uses **possibility**, $P$, in a more specific across-boundary sense. Possibility does not mean local multiplicity itself. It is the logarithmic measure of how the realizations associated with a local state extend compatibly into the enclosing boundary. Thus: **multiplicity describes how many local realizations belong to a state;** **possibility describes how those local realizations participate in enclosing realizations.**

Unequal enclosing extension gives local alternatives unequal directional possibility. Probability is subsequent to both. It is a normalized reading of possible or realized count, not the primitive source of those counts.

The recursive architecture is not bottom-up construction. An enclosing occurrence defines which joint peer realizations are compatible with it. The subordinate processes through which that occurrence is realized remain locally readable at their own boundaries. When a completed local realization is instead read from the enclosing boundary, its peer-specific path no longer retains the same count meaning.

R²D calls this boundary-relative change in count meaning **recursive carry**. Recursive carry is not causal transport upward. It is reclassification. The causal and recursive relations therefore have different directions:

**enclosing organization → compatible local realization;**

**completed local realization → new enclosing count meaning.**

The first concerns causal definition. The second concerns boundary-relative readout.

This differs from ordinary coarse graining. A subordinate state is not merely hidden while preserving an unchanged ontological identity. Changing the count boundary changes which distinctions define a state. A macrostate transition readable at one boundary can become a microstate transition relative to the next. A completed peer closure can remain consequential after boundary change while its internal path and source identity cease to be readable as the same objects.

R²D is therefore not a theory in which larger things are constructed by adding smaller independently causal things. Enclosing boundaries define distinguishable wholes and the compatible subordinate realizations through which those wholes are locally realized.

#### 2.3.1 Relation to Existing Scale-Dependent Frameworks

R²D is not the first framework to challenge the idea that one fixed set of microscopic variables provides the natural description of nature at every scale. Several major developments in twentieth-century physics established that changing scale can change the variables, state descriptions, and mathematical relations through which a system is most naturally represented.

Kadanoff\'s block-spin construction provides a particularly close precedent (23). Microscopic spins are grouped into cells and replaced by collective variables defined at the larger scale. Wilson\'s renormalization group (24) made this scale transformation systematic, showing how effective descriptions change under repeated rescaling and how microscopic details can become irrelevant to large-scale behavior. The larger-scale theory is therefore not obtained simply by retaining every microscopic variable and following it more carefully; a new description emerges under the scale transformation. Effective field theory makes a related point from another direction. Degrees of freedom relevant to one energy domain need not remain explicit in another, and sufficiently heavy degrees of freedom can decouple from low-energy behavior except through their residual effects on effective parameters (25).

Physicists have also drawn broader conclusions from these developments. Anderson argued that knowledge of microscopic laws does not by itself make the behavior of increasingly complex levels a trivial construction from below; new organizing principles become relevant as scale and organization change (26). Laughlin and Pines similarly emphasized the importance of emergent organizing principles in many-body physics and questioned the assumption that a fundamental microscopic equation is, by itself, the scientifically complete explanation of higher-level organization (27). The conceptual consequences of renormalization for reduction, scale dependence, and the relations among physical descriptions have likewise been examined explicitly by Cao and Schweber (28).

R²D belongs to this intellectual lineage, but it makes a different and more primitive claim. Renormalization and effective theories ordinarily begin with a microscopic state description and determine how its effective representation changes with scale. R²D instead asks what makes a state a microstate or a macrostate in the first place. Its answer is boundary-relative: a formal microstate at $B_{n}$is one compatible joint realization of the immediately subordinate boundaries, while a macrostate is the classification of those realizations defined and readable at $B_{n}$. Changing the count boundary therefore changes not merely the resolution or effective parameters of a persistent state description, but the count domain relative to which state identity itself is defined.

For this reason, **recursive replacement should not be identified with renormalization-group coarse graining**, even though the renormalization group provides an important mathematical precedent for it. R²D does not claim that a subordinate state is simply neglected, averaged, or integrated out while retaining an absolute microscopic identity beneath the new description. Its claim is that microstate and macrostate are themselves boundary-indexed categories. A transition readable as a macrostate transition at one boundary has microstate meaning relative to the next; a completed subordinate realization may remain consequential after the boundary changes without remaining the same readable state, source, or path.

The distinction becomes still sharper when direction is considered. Renormalization, emergence, and effective-theory arguments establish important forms of scale dependence and higher-level autonomy. R²D adds a specific across-boundary count relation: compatible enclosing extension can be changed while the native local multiplicity landscape remains fixed, and that change can create, cancel, or reverse the directional support of a local alternative. The proposed novelty of R²D is therefore **not** the general observation that different scales require different descriptions, nor the philosophical claim that "more is different." It is the attempt to derive boundary-relative statehood, recursive replacement, and enclosing directional organization from one dimensionless theory of recursive counting.

The frameworks above should therefore be understood as precedents rather than competitors. They demonstrate that physics has repeatedly encountered descriptions in which scale change reorganizes the relevant ontology and weakens simple reduction from larger-scale behavior to microscopic detail. R²D asks whether a single primitive reason lies beneath those observations: **changing the count boundary changes what is being counted.** The next section develops the additional relation required to make that boundary dependence directional.

### 2.4 Possibility, Retention, and the Direction of Realization

A local multiplicity landscape defines which states are possible. It does not, by itself, determine which state will be preferentially realized. That distinction follows directly from the coin construction. The same native local multiplicity landscape can participate in different enclosing conditions, and those different conditions can alter or reverse the complete directional support of the same local transition. Direction therefore requires an across-boundary relation.

A local state can participate in many realizations of an enclosing whole. If two local alternatives possess equal enclosing compatibility, the enclosing boundary supplies no directional preference between them. If their compatible enclosing extension differs, one alternative has greater enclosing count support.

R²D calls the logarithmic difference in that enclosing compatibility **directional possibility**. This relationship is not introduced merely to reproduce familiar statistical mechanics. R²D formally demonstrates it from recursive counting.

Its physical significance is independently established by statistical mechanics, where changing enclosing thermal, chemical, mechanical, or field conditions changes local state occupancy. The familiar statistical relations are therefore domain-specific realizations of an enclosing-to-local count architecture that can be defined before those physical quantities are introduced.

Enclosing constraint supplies a second relation. Its productive component retains part of the directional possibility against local distinguishable change. The background-associated component does not enter local retention; it contributes only to the total enclosing constrained realization described by the R2D law. The resulting local asymmetry is

$$\Delta A = \Delta P - \Delta R.$$

This asymmetry biases how occurrence is expressed as occupancy. The primitive causal sequence is therefore not an object being pushed through a pre-existing landscape by a subordinate mechanism.

Instead, native multiplicity defines the available local possibilities; enclosing compatibility defines their directional support; productive constraint determines how much of that directional relation is retained; subordinate occurrence realizes the resulting occupancy change.

This is the meaning of the phrase: **Possibility pulls occupancy.**

The same architecture applies to closure. A completed local path can return to its initial macrostate while the enclosing relation organizing the opposed legs does not return to the same condition. Native multiplicity can therefore close while enclosing possibility remains asymmetric.

Local closure does not imply enclosing reversal. An enclosing occurrence defines the compatible local closures through which it is realized. Those closures do not independently accumulate upward to create the enclosing occurrence. After local completion, recursive carry changes how that realization is counted from the enclosing boundary.

Irreversibility introduces another distinction. Even when native multiplicity closes exactly, opposed branches need not realize occurrence count with equal directional efficiency. R²D calls the resulting logarithmic nonreciprocity **occurrence-count loss**. No count is destroyed. The local state can return while realization around the cycle remains nonreciprocal.

R²D\'s Second Law proposes that this nonreciprocity has a complementary enclosing reading as nondirectional background.

Thus, four relations that are often compressed into one causal narrative are separated: **the enclosing relation defines what is favored;** **the subordinate structure determines how it is realized;** **recursive carry determines how a completed realization is reclassified across boundaries;** **irreversibility determines whether opposed realizations are reciprocal.**

Section 3 develops these distinctions formally.

### 2.5 From Recursive Count to Scientific Description

Part I develops this architecture before physical units are introduced. It does not begin with energy, temperature, force, time, probability, matter, field, or spacetime. It begins with count boundaries, compatible realizations, multiplicity, logarithmic count difference, occurrence, occupancy, enclosing possibility, constraint, closure, and recursive carry.

Later parts ask whether familiar scientific quantities can be recovered as boundary-specific physical readings of these relations. Entropy reads logarithmic multiplicity. Work is proposed to read distinguishability retained against productive constraint. Heat is proposed to read dissipative realization. Physical time and rate are proposed to read recurrence relations among completed realizations; the logarithmic state-occurrence coordinate τ remains an occurrence statistic rather than a clock. Probability reads normalized unresolved possibility. Spacetime is proposed to read recursive count geometry.

These mappings are not assumed in Part I. They are the empirical and theoretical burden of the later program. The claim is therefore not that all sciences study the same objects. They do not. The claim is that apparently different scientific objects may become countable through the same primitive operations.

The domain changes. The units change. The readable ontology changes. The primitive count grammar does not.

### 2.6 Scope, Logical Status, and Empirical Burden

Part I develops R²D as a theory of dimensionless recursive counting. Its claims do not all have the same logical status.

The first level is **mathematical and ontological structure**.

Once a count boundary, compatible realization domain, and classification rule are defined, multiplicity follows exactly. A formal microstate has microstate identity only relative to the enclosing boundary-defined domain and classification in which it is a microstate. Subordinate realization therefore cannot create the state ontology required for it to possess microstate meaning. The formalism further establishes that local directional support depends separately on compatible enclosing extension. Holding native local multiplicities fixed while varying enclosing compatibility can create, cancel, or reverse the complete directional count relation.

These are general results of the R²D framework. Appendix B supplies a transparent finite realization of them. The results formally exclude subordinate transitions as a sufficient source of either the multiplicity structure or the enclosing directional relation they realize. Enclosing-to-local causal organization is therefore not imported as a separate top-down assumption; it is the causal ordering implied by boundary-relative statehood and enclosing-compatible directionality.

The second level is **structural universality and empirical statistical realization**.

The macrostate–microstate relation is a count relation, not a designation of physical scale. Statistical mechanics has no preferred physical scale: electrons, molecules, proteins, coins, cells, and larger ensembles may all occupy the same formal macrostate–microstate architecture while the physical identity of the counted states changes. Wherever a scientific description admits distinguishable macrostates and compatible subordinate realizations, the primitive relation has the same form.

Statistical mechanics supplies the corresponding empirical realization. Experimentally changing enclosing thermal, chemical, mechanical, or field relations changes local occupancy, while canonical statistical mechanics derives local weighting from the compatible state structure and constraints of the larger system. R²D therefore treats the primitive statistical architecture as structurally universal. A counterexample must identify a scientific state that cannot be represented through a boundary-defined macrostate and compatible subordinate realizations, or supply alternative formal definitions from which a different state architecture follows.

The third level is **domain-specific physical mapping and additional realization postulates**.

Part I makes additional postulates concerning how possible multiplicity is realized as occurrence and occupancy, how asymmetry biases occupancy, how finite closure produces directional occurrence-count efficiency, how representative local closure geometry relates to an enclosing occurrence, and how local occurrence-count nonreciprocity is read at the enclosing boundary. Later parts also propose physical readings of the primitive count coordinates in thermodynamics, quantum theory, gravity, biology, cosmology, and other domains.

These propositions and mappings do not follow from structural universality alone. They remain independently testable. A failed gravity, quantum, biological, or cosmological mapping would challenge that mapping and any claims that depend on it; it would not by itself overturn the universal macrostate–microstate count architecture.

The empirical burden is therefore specific rather than repetitive. R²D need not re-establish the primitive statistical grammar independently at every scale. It must show that proposed domain-specific readings preserve the successful local mathematics and observations without redefining the primitive count relations, and it must revise or reject mappings that fail those tests.

R²D would fail at its core if the definitions of macrostate and microstate were shown to be inadequate, if a scientific domain required a state architecture that could not be represented by them, or if an alternative formal state relation demonstrated bottom-up causal sufficiency. Domain-specific realization postulates and mappings have their own additional failure conditions: native multiplicity must structure occurrence as proposed, local asymmetry must organize occupancy where claimed, equivalent peers must satisfy the closure geometry required by the R²D law where applicable, and occurrence-count nonreciprocity must correspond to the proposed enclosing background relation where that mapping is asserted.

The central questions of Part I are consequently:

**What boundary defines the count?**

**What multiplicity defines the possible state?**

**What enclosing relation favors one realization over another?**

**How is that relation realized locally?**

**How is a completed realization reclassified when the count boundary changes?**

And, beneath them all:

**Have we mistaken the mechanism that realizes a relation for the cause that organizes it?**

**\
**


## 3.0 The Primitive Counting Structure of R²D

---
r2d_id: "canon-p1-3.0"
title: "Part I — 3.0 The Primitive Counting Structure of R²D"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 38
pdf_page_end: 89
semantic_amendment: "2026-09-25-universal-statistical-architecture"
review_status: "authoritative"
---
# 3.0 The Primitive Counting Structure of R²D

Recursively Realized Distinguishability (R²D) establishes a dimensionless language of recursive counting. It does not assume energy, force, field, spacetime, temperature, probability, or matter as primitive. These quantities appear later as domain-specific readings of count relations.

R²D begins with a foundation of mathematics: **Counting requires distinguishability.**

### 3.1 The Founding Principle -- Boltzmann's Dimensionless Count

Boltzmann's entropy as originally proposed (1) counts distinctions

$S = \ln W$.

Multiplicity $W$ is a distinguishable degeneracy count that replaces subordinate distinctions. Because the argument of an exponential

$$W = e^{S}$$

must be dimensionless, primitive multiplicity counts must be dimensionless.

Physical laws assign units of measure (e.g., energy, space, and time) to the logarithm of primitive counts. This creates coordinate systems along which measured units add. It also hides the primitive multiplicity beneath those measurements.

The goal of R²D is not to deny the usefulness of continuous coordinate systems. It is to define the primitive multiplicity underlying those coordinate systems.

### 3.2 A Boundary Defines What Is Being Counted

Statistical mechanics has no preferred physical scale. The same counting architecture can describe an ensemble of electrons, each having two distinguishable states; an ensemble of proteins, each having two distinguishable states; or an ensemble of coins, each having two distinguishable states. Nothing in the combinatorics requires one of these objects to be more fundamentally microscopic than another. What changes is the count boundary and, with it, the identity of what is being counted.

This observation places unusual importance on two familiar words: **macrostate** and **microstate**. The most consequential step in R²D is therefore the simplest: the formal definitions of these two words.

R²D defines a macrostate as a distinguishable state readable at a count boundary $B_{n}$. A formal microstate relative to that boundary is one compatible joint realization of the immediately subordinate peer boundaries.

These definitions are the logical fulcrum of Part I. They do not merely provide terminology for a theory developed elsewhere. Once macrostate and microstate are defined as boundary-relative count relations, much of the subsequent R²D architecture follows.

**Principle — Universal Statistical Architecture**

A macrostate–microstate relation is a count relation, not a designation of physical scale. Wherever a scientific description identifies a distinguishable state readable at a boundary and compatible subordinate realizations relative to that boundary, the relation has the same primitive form:

$$
\pi_n:\mathfrak{M}_n\to\mathcal{M}_n,
$$

with native multiplicity

$$
W_{n,i}=\left|\pi_n^{-1}(i)\right|.
$$

Statistical mechanics has no preferred physical scale. The physical identity of the counted states may change from electrons to molecules, proteins, cells, organisms, or larger systems, but the macrostate–microstate count relation does not thereby become a different kind of mathematics. The boundary changes. The readable ontology changes. The primitive statistical architecture does not.

R²D therefore treats this primitive architecture as structurally universal wherever scientific states admit a macrostate–microstate relation. Statistical mechanics supplies the empirical realization of that architecture across physical systems without assigning it a preferred scale. Structural universality does not imply that every proposed R²D physical mapping is correct. Gravity, quantum theory, biology, cosmology, and other domains may read the same primitive relation through different physical coordinates, and each proposed mapping remains independently testable.

A counterexample to the primitive architecture must therefore do more than provide a successful local mechanism or a different physical vocabulary. It must identify a scientific state that cannot be represented through a boundary-defined macrostate and compatible subordinate realizations, or supply alternative formal definitions of macrostate and microstate from which a different state architecture follows. Until such an alternative is supplied, primitive bottom-up causal priority is not established by microscopic terminology, local dynamics, temporal ordering, or predictive success alone.

A microstate is not an intrinsically microscopic object. It has microstate meaning only relative to the boundary that classifies it. If a transition has microstate meaning relative to $B_{n}$, then resolving that transition requires changing to the subordinate boundary at which the same distinction has macrostate meaning. Increased resolution therefore does not reveal the same state while preserving its classification. It changes the count boundary and hence changes what the state is. The primitive observer effect follows immediately. So does the many-body problem: $B_{n}$ can define and classify a compatible joint subordinate realization without individually resolving the peer transitions through which that realization occurs. Recursive replacement follows for the same reason. Changing scale changes the count domain rather than merely exposing additional detail within an unchanged ontology.

The consequences extend still further. If different recursively related count coordinates cease to remain jointly readable as the boundary changes, readability horizons necessarily appear. The later gravitational and black-hole interpretation of one such horizon does not begin with spacetime or gravity. It begins here, with the fact that state identity and readability are boundary relative. Likewise, the quantum interpretation developed later does not begin by declaring microscopic objects intrinsically uncertain. It begins with the loss of one class of distinction under recursive change of count boundary.

For this reason, a critical reader should focus first and foremost on the formal definitions of macrostate and microstate. If these definitions are wrong, the architecture built upon them fails. If they are accepted, most of what follows is not independent assumptions but necessary consequences of boundary-relative statehood.

A familiar counter example assigns directional asymmetry directly to a microstate transition relative to $B_{n}$. The attempt fails within the R²D definitions because a microstate transition is not individually distinguishable at the boundary relative to which it is a microstate transition. Its distinguishable interval is therefore not defined there as a readable local step. To assign asymmetry to that transition, the observer must change to the subordinate boundary $B_{n - 1}$, where the same change is now a readable macrostate transition.

At that boundary its asymmetry can be defined. But its directional possibility is then determined from compatibility with its enclosing boundary $B_{n}$, and its retention is determined by the productive component of enclosing constraint. Thus, moving the proposed causal asymmetry "down into the microstates" does not escape the recursive architecture. It simply moves the count boundary:

$$\text{microstate~asymmetry~at~}B_{n} \longrightarrow \text{macrostate~asymmetry~at~}B_{n - 1} \longrightarrow \text{enclosing~definition~from~}B_{n}.$$

One could instead postulate an intrinsic directional bias attached to formally defined microstate transitions. But this introduces a new primitive not supplied by the statistical state definitions. Worse, different microstate transitions belonging to the same readable macrostate transition may carry different intrinsic biases. Those subordinate biases cannot determine a unique macrostate direction without an additional rule specifying which transitions are compatible and how their directional contributions are related. That rule again belongs to the enclosing count boundary. If the subordinate biases are chosen so that their aggregate already reproduces the enclosing direction, then the enclosing organization has merely been encoded as an external field that acts on microstate transitions through mysterious laws.

The alternative therefore does not restore bottom-up causal priority. Asymmetry cannot be pushed below a boundary without changing the boundary from which it is defined.

This is why the absence of a preferred physical scale in statistical mechanics is not incidental. An electron, a protein, and a coin can each function as a subordinate two-state realization because "microstate" does not name a particular thing. It names a relation to a count boundary. Change the boundary and the identity of the microstate changes with it.

Statistical mechanics uses different physical state descriptions across scientific domains, but it does not require a different primitive macrostate–microstate relation at each scale. R²D supplies the scale-relative definition: a macrostate is readable at the count boundary; a formal microstate is one compatible subordinate realization relative to that boundary. The identity of the physical state changes with the boundary. The statistical relation does not.

The central question for Part I is therefore unusually narrow:

**Are the two formal definitions of microstate and macrostate defined below wrong, or does a scientific domain require a macrostate–microstate relation that cannot be represented by them?**

If either is true, R²D fails at its core.

If neither is true, the primitive statistical architecture does not need to be re-established independently at every physical scale. What remains domain-specific is the mapping by which a physical theory reads that architecture. The observer effect, recursive replacement, the many-body problem, enclosing causal organization, fields, r-squared laws, and readability horizons can then be tested as distinct physical readings or consequences of the same boundary-relative definition of state.

#### 3.2.1 The Formal Definition of Microstate and Macrostate

At every nonprimitive boundary $B_{n}$, states are defined from compatible joint realizations of peer subordinate boundaries. Let the peer boundaries immediately subordinate to $B_{n}$ be

$$\left\{ B_{n - 1,a} \right\}_{a \in I_{n - 1}}.$$

For each peer boundary $a$, let

$$\mathfrak{X}_{n - 1,a}$$

denote its possible realization domain.

A joint peer realization is

$$\mathbf{x}_{n - 1} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}},\quad\quad x_{n - 1,a} \in \mathfrak{X}_{n - 1,a}.$$

The unrestricted product

$$\prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}$$

contains all formally possible combinations of peer realizations. Boundary $B_{n}$ defines which of these combinations are compatible. The compatible subset is the formal microstate domain:

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}.$$

A formal microstate at $B_{n}$ is therefore one compatible joint peer realization:

$$\mu_{n} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}} \in \mathfrak{M}_{n}.$$

The complete peer-resolved identity of $\mu_{n}$ is mathematically defined. It need not be individually readable from $B_{n}$. Boundary $B_{n}$ instead classifies compatible formal microstates into readable macrostates. Let

$$\mathcal{M}_{n}$$

be the readable macrostate set. The classification map is

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}.$$

The relation

$$\pi_{n}\left( \mu_{n} \right) = i$$

means that formal microstate $\mu_{n}$ is read from $B_{n}$ as macrostate $i$. Thus, a macrostate is not an object assembled from independently persistent subordinate states. It is a boundary-defined classification of compatible joint peer realizations. For macrostate $i$, the complete formal microstate fiber is

$$\pi_{n}^{-1}(i) = \left\{ \mu_{n} \in \mathfrak{M}_{n}:\pi_{n}\left( \mu_{n} \right) = i \right\}.$$

Its cardinality defines the native multiplicity:

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|.$$

Multiplicity therefore counts possible compatible joint realizations before any particular realization is selected. Its logarithmic coordinate is

$$S_{n,i} = \ln W_{n,i}.$$

The distinction among microstate, macrostate, and multiplicity is therefore

$$\begin{aligned}
\mu_{n} & = \text{one~compatible~joint~peer~realization}, \\
i & = \text{the~readable~classification~of~that~realization~at~}B_{n}, \\
W_{n,i} & = \text{the~number~of~compatible~realizations~classified~as~}i.
\end{aligned}$$

This state structure is boundary relative. A formal microstate at $B_{n}$does not remain the same formal microstate at $B_{n + 1}$ because the enclosing boundary defines a different realization domain and a different classification map. Thus, changing the count boundary changes the identity of what is being counted.

#### 3.2.1 Possible Count, Occurrence, and Occupancy

R²D distinguishes possible count from realized count. A microstate occurrence is one realized instance of a formally possible microstate:

$$\mu_{n}^{(r)} \in \mathfrak{M}_{n}.$$

If

$$\pi_{n}\left( \mu_{n}^{(r)} \right) = i,$$

that realization contributes one occurrence associated with macrostate $i$. Let

$$\nu_{n,i}$$

denote the number of such realized occurrences within a specified finite realization domain. Its logarithmic occurrence coordinate is

$$\tau_{n,i} = \ln \nu_{n,i}.$$

Macrostate occupancy is a different count. Let

$$c_{n,i}$$

denote the realized occupancy of macrostate $i$ in a specified realized configuration, with logarithmic coordinate

$$G_{n,i} = \ln c_{n,i}.$$

$G$ is not yet a chemical potential and $c$ is not yet an activity or concentration. Energy and molecules have not yet been defined.

The three counts are:

$$\begin{aligned}
W_{n,i} & = \text{possible~count}, \\
\nu_{n,i} & = \text{realized~occurrence~count}, \\
c_{n,i} & = \text{realized~occupancy count}.
\end{aligned}$$

The native multiplicity landscape defines which realizations are possible. Occurrence counts realizations of those possibilities. Occupancy records the realized structure within the multiplicity landscape. Neither occurrence nor occupancy creates the native multiplicity while the boundary definition remains fixed.

#### 3.2.2 Microstate Transitions Are Definable but Not Readable

A microstate transition relative to $B_{n}$ is a change between two formal microstates:

$$\mu_{n} \rightarrow \mu_{n}'.$$

Such a change may be realized through a readable macrostate transition at one particular peer boundary $B_{n - 1}$:

$$B_{n - 1,a}:\quad\quad u \rightarrow v.$$

Relative to $B_{n}$, that same subordinate change is a microstate transition. Thus,

$$\text{macrostate~transition~at~}B_{n - 1,a} = \text{microstate~transition~relative~to~}B_{n}.$$

The transition has not become a different physical occurrence merely because the boundary changed. Its **count meaning** has changed. At $B_{n - 1}$, the source peer $a$ and the transition are readable. At $B_{n}$, subordinate boundary $a$ is not distinguishable from its subordinate peers. The corresponding formal microstate change is therefore individually unresolved.

Suppose

$$\pi_{n}\left( \mu_{n} \right) = i$$

and

$$\pi_{n}\left( \mu_{n}' \right) = k.$$

If

$$i = k,$$

the microstate transition changes the subordinate realization without changing the readable macrostate classification at $B_{n}$.

If

$$i \neq k,$$

the same microstate transition has a readable macrostate consequence:

$$i \rightarrow k.$$

Boundary $B_{n}$ can therefore read the macrostate consequence without reading which peer transition supplied that local realization. This distinction can be written

$$\mu_{n} \rightarrow \mu_{n}'\quad\overset{\pi_{n}}{\rightarrow}\quad i \rightarrow k,$$

where the first transition is a formally defined microstate transition relative to $B_{n}$, while the second is its readable macrostate classification relative to $B_{n - 1}$. The classification map is not a causal arrow. It states how the realized change is read at the boundary.

Repeated microstate transitions are the local occurrences through which changes in macrostate occupancy are realized. They do not, by themselves, determine why one occupancy change is directionally favored over another. That directional bias is defined separately by the enclosing asymmetry relation:

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - R_{n,i \rightarrow k}.$$

Thus, R²D separates **local realization** from **directional causal organization**. A microstate transition is the local realization of occupancy change whereas enclosing asymmetry is the directional bias of that realization.

A microstate transition is therefore definable without being individually readable from the boundary relative to which it is a microstate transition. To read that transition directly, the observer must change to the subordinate boundary $B_{n - 1}$. But from that boundary the same change is no longer classified as a microstate transition. It is a readable macrostate transition. Therefore, a transition is never directly readable as a microstate transition from the boundary relative to which it is a microstate transition.

This is the primitive R²D observer effect defined before particles, space, time or measuring devices. Observation does not perturb an independently fixed microscopic state. Resolution changes the count boundary, and changing the boundary changes the classification under which the transition becomes readable:

$$\text{resolution} \rightarrow \text{change~of~count~boundary} \rightarrow \text{change~of~state~classification}.$$

The many-body problem is therefore present before bodies are assigned primitive ontology. What is unreadable at $B_{n}$ is not an independently primitive microscopic trajectory hidden beneath the macrostate. It is the peer-resolved realization structure that $B_{n}$ has replaced with a new boundary-defined count classification.

#### 3.2.3 Coins Illustrate Boundary-Relative Resolution.

Consider ten coins at boundary $B_{n}$, initially in the readable macrostate (10,0). The native multiplicity landscape is maximal near (5,5). Under proportional occurrence realization, the ensemble is preferentially realized toward those states. Boundary $B_{n}$ reads this ensemble change, but it cannot directly read the individual $H \rightarrow T$ and $T \rightarrow H$ transitions that realize it, because those transitions have microstate meaning relative to $B_{n}$. To observe one such transition directly, the observer must change to a subordinate boundary $B_{n - 1,a}$, where H and T are themselves readable macrostates. But the causal question has then changed: the observer is no longer asking why the ten-coin ensemble realizes one macrostate rather than another, but why one coin realizes H rather than T. Thus, increasing resolution does not reveal the same causal relation at finer detail; it changes the count boundary and therefore changes the identity of the states and the causal question.

**The foundational consequence is that resolution of a proposed subordinate cause changes the boundary from which causality is defined. Bottom-up causal attribution cannot therefore be established merely by increasing observational resolution.**

### 3.3 Landscapes

A count boundary $B_{n}$ defines a set of readable macrostates

$$\mathcal{M}_{n}$$

and a formal microstate domain

$$\mathfrak{M}_{n}.$$

The classification map

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}$$

assigns compatible formal microstates to readable macrostates. Three distinct count structures can then be defined on the same macrostate domain:

$$W_{n,i} = \text{possible~count},$$

$$\nu_{n,i} = occurrence count,$$

and

$$c_{n,i} = \text{realized~occupancy}.$$

R²D calls the collections of these quantities across the readable macrostate set **landscapes**. The distinction among them is essential. Multiplicity defines the possible-count structure of the boundary. Occurrence counts realized instances within that structure. Occupancy records the realized structural distribution across its macrostates.

The three counts may be expressed logarithmically, but logarithmic representation does not change their count type. For realized counts, logarithmic coordinates are used only where the corresponding raw count is positive. A zero raw occurrence or occupancy remains a valid count but has no finite logarithmic coordinate.

#### 3.3.1 The Native Multiplicity and Entropic Landscapes

For macrostate

$$i \in \mathcal{M}_{n},$$

the formal microstates form the fiber

$$\pi_{n}^{-1}(i).$$

Its cardinality defines the multiplicity:

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|.$$

Thus $W_{n,i}$ counts the number of compatible joint peer realizations that boundary $B_{n}$ classifies as macrostate $i$. Multiplicity is mathematically defined prior to any particular realization. The collection

$$\mathcal{W}_{n} = \left\{ W_{n,i} \right\}_{i \in \mathcal{M}_{n}}$$

is the **native multiplicity landscape** at $B_{n}$. Its logarithmic coordinate is

$$S_{n,i} = \ln W_{n,i}.$$

The collection

$$\mathcal{S}_{n} = \left\{ S_{n,i} \right\}_{i \in \mathcal{M}_{n}}$$

is the corresponding **native entropic landscape**. In Part I,

$$S_{n,i}$$

is not yet thermodynamic entropy. It is the dimensionless logarithmic coordinate of possible multiplicity. For a readable transition

$$i \rightarrow k,$$

the entropic difference is

$$\Delta S_{n,i \rightarrow k} = S_{n,k} - S_{n,i} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right).$$

This compares the possible multiplicities of two readable macrostates. Because the macrostate fibers partition the formal microstate domain,

$$\mathfrak{M}_{n} = \bigsqcup_{i \in \mathcal{M}_{n}}\pi_{n}^{-1}(i),$$

the total boundary multiplicity is

$$\Theta_{n} = \left| \mathfrak{M}_{n} \right| = \sum_{i \in \mathcal{M}_{n}}W_{n,i}.$$

Its logarithmic coordinate is

$$S_{n}^{tot} = \ln \Theta_{n}.$$

Two different composition rules are therefore already visible. Within one boundary, mutually exclusive macrostate multiplicities add:

$$\Theta_{n} = \sum_{i}W_{n,i}.$$

Across unrestricted compatible peer structures, possible multiplicities multiply:

$$W_{joint} = \prod_{a}W_{a}.$$

Their logarithms consequently add:

$$\ln W_{joint} = \sum_{a}\ln W_{a}.$$

Thus, mutually exclusive alternatives add while compatible joint possibilities multiply.

The native multiplicity landscape is fixed. Changes in realization do not by themselves change

$$W_{n,i}.$$

They change occurrence and occupancy within that possible-count structure. The native multiplicity landscape structures realization. It is not created by realization.

#### 3.3.2 The Occupancy Landscape

Multiplicity specifies what can be realized. Occupancy specifies the realized structure currently expressed across the available macrostates. Let

$$c_{n,i}$$

denote the realized occupancy of macrostate $i$ in a specified realized configuration. For

$$c_{n,i} > 0,$$

define the logarithmic occupancy coordinate

$$G_{n,i} = \ln c_{n,i}.$$

The occupancy landscape is therefore

$$\mathcal{G}_{n} = \left\{ G_{n,i} \right\}_{i \in \mathcal{M}_{n}}$$

over macrostates having positive occupancy. For a readable transition

$$i \rightarrow k,$$

the logarithmic occupancy difference is

$$\Delta G_{n,i \rightarrow k} = G_{n,k} - G_{n,i} = \ln\left( \frac{c_{n,k}}{c_{n,i}} \right).$$

This is a realized structural relation. It is not part of the native possible-count landscape. The distinction is therefore

$$W_{n,i} = \text{how~many~compatible~realizations~are~possible~at~}i,$$

whereas

$$c_{n,i} = \text{how~much~realized~occupancy~is~expressed~at~}i.$$

Occupancy does not equal multiplicity:

$$c_{n,i} \neq W_{n,i}$$

in general. Nor should occupancy be described as "realized multiplicity." More precisely, occupancy is **realized structure within a multiplicity-defined landscape**.

Where the occupancy landscape has a unique maximum, define the structural macrostate as

$$i_{n}^{*} = {*{\arg\,\max}}_{i \in \mathcal{M}_{n}}c_{n,i}.$$

Because the logarithm is monotonic,

$$i_{n}^{*} = {*{\arg\,\max}}_{i \in \mathcal{M}_{n}}G_{n,i}.$$

A change

$$i_{n}^{*} \rightarrow k_{n}^{*}$$

is a **structural macrostate transition**.

This transition describes a change in the realized occupancy mode. It does not identify one particular microstate transition or one peer-source trajectory. At a mode-exchange threshold between $i_{n}^{*}$ and $k_{n}^{*}$,

$$c_{n,i} = c_{n,k},$$

so

$$\Delta G_{n,i \rightarrow k} = 0.$$

The relation determining where that exchange occurs will later be given by enclosing possibility and retention. Thus, the occupancy landscape is dynamic even when the native multiplicity landscape remains fixed.

#### 3.3.3 Microstate Occurrence Count and the Primitive Occurrence Coordinate

Occupancy records realized structure. Occurrence count records realized instances. A microstate occurrence at $B_{n}$ is one realized formal microstate

$$\mu_{n}^{(r)} \in \mathfrak{M}_{n}.$$

If

$$\pi_{n}\left( \mu_{n}^{(r)} \right) = i,$$

the realization contributes one occurrence associated with macrostate $i$. Let

$$\nu_{n,i}$$

denote the number of realized microstate occurrences classified as $i$ within a specified finite realization domain.

For

$$\nu_{n,i} > 0,$$

define the logarithmic occurrence coordinate

$$\tau_{n,i} = \ln \nu_{n,i}.$$

For a readable transition

$$i \rightarrow k,$$

the net occurrence-count difference is

$$\Delta\tau_{n,i \rightarrow k} = \tau_{n,k} - \tau_{n,i} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right).$$

The realization domain used to define $\nu_{n,i}$ is a finite domain of count. It is **not assumed to be a time interval**. Likewise,

$$\tau_{n,i}$$

is not physical time, and

$$\Delta\tau_{n,i \rightarrow k}$$

is not a physical rate and is not a closure recurrence count. Those interpretations, if valid, belong to later domain-specific mappings. Closure recurrence is defined separately in Section 3.7.

Occurrence and occupancy are not identical. Many occurrences can be associated with the realization of one occupancy structure, and repeated occurrences can occur without changing the structural macrostate. Thus,

$$\nu_{n,i} \neq c_{n,i}$$

in general. The three landscapes therefore answer different questions:

$$\begin{aligned}
W_{n,i}: & \quad\text{How~many~compatible~realizations~are~possible?} \\
\nu_{n,i}: & \quad\text{How~many~realizations~occur~in~the~specified~count~domain?} \\
c_{n,i}: & \quad\text{What~realized~structure~is~expressed~across~the~macrostates?}
\end{aligned}$$

Their logarithmic coordinates are

$$S_{n,i} = \ln W_{n,i},\quad\quad\tau_{n,i} = \ln \nu_{n,i},\quad\quad G_{n,i} = \ln c_{n,i}.$$

The changes in log counts with a macrostate transition

$i \rightarrow k$

are

$\Delta S_{n,i \rightarrow k} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right)$,

$\Delta\tau_{n,i \rightarrow k} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right)$,

$\Delta G_{n,i \rightarrow k} = \ln\left( \frac{c_{n,k}}{c_{n,i}} \right)$.

These are mathematical coordinates of three different count types. They should not be conflated. The native multiplicity landscape defines the possible structure. Microstate occurrences realize possibilities within that structure. The occupancy landscape records the resulting structural realization.

Direction has still not been supplied by any of these three counts alone. That requires the enclosing compatibility and constraint relations developed below.

### 3.4 Proportional Occurrence Realization

The native multiplicity landscape defines the relative possible-count structure of the macrostates at boundary $B_{n}$.

For two readable macrostates,

$$i,k \in \mathcal{M}_{n},$$

their multiplicity ratio is

$$\frac{W_{n,k}}{W_{n,i}},$$

with logarithmic difference

$$\Delta S_{n,i \rightarrow k} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right).$$

Multiplicity is possible count. It does not specify how many realizations actually occur. Let

$$\nu_{n,i}$$

and

$$\nu_{n,k}$$

denote the realized microstate-occurrence counts associated with the two macrostates within a specified finite realization domain. Their logarithmic occurrence difference is

$$\Delta\tau_{n,i \rightarrow k} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right).$$

R²D postulates that, for a fixed realization relation and a sufficiently resolved realization domain, relative occurrence count proportionally realizes the native multiplicity landscape:

$$\frac{\nu_{n,k}}{\nu_{n,i}} \approx \frac{W_{n,k}}{W_{n,i}}.$$

Equivalently,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k}.$$

This is the **proportional occurrence-realization postulate**. It does not state

$$\nu_{n,i} = W_{n,i}.$$

Multiplicity and occurrence remain different count types. The relation is instead between their **relative structures**:

$$\text{relative~possible~count} \approx \text{relative~occurrence~count}.$$

Thus, if one macrostate has greater native multiplicity than another, then -- within the specified realization relation and sufficiently resolved domain -- it has proportionally greater occurrence support.

#### 3.4.1 Proportional Realization Does Not Require Zero Asymmetry

Proportional occurrence realization does not require

$$\Delta A_{n,i \rightarrow k} = 0.$$

This distinction is essential. The native multiplicity landscape

$$\mathcal{W}_{n} = \left\{ W_{n,i} \right\}_{i \in \mathcal{M}_{n}}$$

defines the relative possible-count structure. Postulate 1 states that occurrence count realizes this native structure proportionally:

$$\Delta\tau \approx \Delta S.$$

Enclosing asymmetry enters through a different relation. For a readable transition,

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - R_{n,i \rightarrow k}.$$

R²D does not postulate that this asymmetry changes the native proportional relation between multiplicity and occurrence. Instead, asymmetry determines how the realized occurrence relation is expressed as occupancy. That relation is developed below as

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

The distinction is therefore

$$\begin{aligned}
\Delta S & \longrightarrow \text{relative~occurrence~structure}, \\
\Delta A & \longrightarrow \text{occupancy~bias}.
\end{aligned}$$

**Multiplicity structures occurrence. Asymmetry structures occupancy.**

#### 3.4.2 Occurrence and Occupancy Are Not the Same Realization

Repeated occurrences can take place without changing the structural occupancy mode. Likewise, a change in occupancy may be realized through many subordinate occurrences whose individual source identities are unreadable at $B_{n}$. The proportional-realization postulate therefore applies to

$$W \longrightarrow \nu,$$

not directly to

$$W \longrightarrow c.$$

The occupancy relation requires the additional enclosing asymmetry developed in Section 3.6. Thus,

$$W \rightarrow \nu \rightarrow c$$

is not a causal chain of persistent objects. It is a sequence of distinct count relations:

$$\begin{aligned}
W & = \text{possible-count~structure}, \\
\nu & = \text{occurrence~realization~of~that~structure}, \\
c & = \text{structural~occupancy~produced~under~enclosing~asymmetry}.
\end{aligned}$$

#### 3.4.3 Proportional Realization Is a Finite-Count Approximation

The relation

$$\Delta\tau \approx \Delta S$$

is not asserted as an exact identity for every finite realization. Multiplicity is a mathematically defined possible-count structure. Occurrence is a realized count over a finite realization domain. A finite realized count need not reproduce every multiplicity ratio exactly.

R²D therefore requires a sufficiently resolved realization domain before proportional occurrence realization is expected. The postulate is

$$\frac{\nu_{n,k}}{\nu_{n,i}} \approx \frac{W_{n,k}}{W_{n,i}},$$

for every finite count. This distinguishes proportional occurrence realization from the finite-count nonreciprocity of asymmetric closure developed later.

Within a specified realization relation, occurrence count may proportionally realize the native multiplicity landscape:

$$\Delta\tau \approx \Delta S.$$

Around a completed asymmetric closure, however, the two opposed legs may realize occurrence count with unequal directional efficiency:

$$\eta_{n,\mathcal{C}} \neq 1.$$

These are not contradictory statements. They describe different relations. The first compares **occurrence among macrostates within one realization relation**. The second compares **directional occurrence efficiency between opposed legs of a completed closure**. Thus, proportional occurrence realization need not equal reciprocal closure realization$.$

With the three count types now separated, the remaining question is what makes one realized occupancy structurally favored over another. Native multiplicity alone does not supply that direction. The directional relation comes from the compatible multiplicity of the enclosing count domain.

### 3.5 Enclosing Multiplicity and Possibility

The native multiplicity landscape at $B_{n}$ defines the possible realizations of each local macrostate. It does not, by itself, determine how those macrostates are realized. The source of directional possibility lies in the enclosing count domain.

Macrostate transitions of an enclosing landscape compatible with local macrostate transitions create across-scale directional possibility, $P$.

#### 3.5.1 Multiplicity Capacity

The multiplicity of macrostate $i$ at $B_{n}$ is

$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|$.

The corresponding entropy is

$$S_{n,i} = \ln W_{n,i}.$$

The total boundary multiplicity of the boundary-defined count domain is

$\Theta_{n} = \sum_{i \in \mathcal{M}_{n}}W_{n,i}$.

The corresponding total boundary entropy is

$$S_{n}^{B} = \ln \Theta_{n}.$$

Changing the boundary changes the count domain. The elements counted by $\Theta_{n}$ are therefore not the same objects as those counted by $\Theta_{n + 1}$. Recursive comparison concerns their multiplicities, not persistence of their identities.

#### 3.5.2 Enclosing Multiplicity Compatible with a Local State

Consider macrostate $i$ for a specified boundary $B_{n}$ on scale $n$. The enclosing boundary $B_{n + 1}$ defines which of its possible realizations are compatible with realization of *i*. Let

$$\mathcal{E}_{n + 1 \mid n,i} = \left\{ \mu_{n + 1} \in \mathcal{U}_{n + 1}:\mu_{n + 1} \sim i_{n} \right\}$$

denote that compatibility class. Its multiplicity is

$$\Theta_{n + 1 \mid n,i} = \left| \mathcal{E}_{n + 1 \mid n,i} \right|.$$

The corresponding compatible enclosing entropy is

$$S_{n + 1 \mid n,i}^{comp} = \ln \Theta_{n + 1 \mid n,i}.$$

Thus, $W_{n,i}$ counts the possibilities available to state $i$ within its local boundary, whereas $\Theta_{n + 1 \mid n,i}$ counts the enclosing possibilities compatible with realization of that local state.

#### 3.5.3 Possibility Is Compatible Enclosing Multiplicity

Consider local macrostate

$i \in \mathcal{M}_{n}$.

Its local multiplicity is

$$W_{n,i}.$$

The enclosing boundary $B_{n + 1}$​ defines the multiplicity of enclosing realizations compatible with the possible subordinate realizations classified as $i$:

$$\Theta_{n + 1 \mid n,i}.$$

The local macrostate $i$ is not itself extended into the enclosing boundary. It is the local classification relative to which compatible enclosing realizations are counted.

Define the mean compatible enclosing extension multiplicity per local possibility as

$$K_{n + 1 \mid n,i} = \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}}.$$

Possibility is the logarithm of this compatible extension multiplicity:

$$P_{n,i} = \ln K_{n + 1 \mid n,i} = \ln\left( \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}} \right).$$

If

$$S_{n + 1 \mid n,i}^{comp} = \ln \Theta_{n + 1 \mid n,i},$$

then

$$P_{n,i} = S_{n + 1 \mid n,i}^{comp} - S_{n,i}.$$

Possibility is therefore an across-boundary difference in logarithmic possible count. More specifically, it measures the multiplicity of enclosing realizations available per local possibility classified as $i$.

The absolute value of $P_{n,i}$​ does not by itself define a directional bias within the local landscape. If every local macrostate has the same compatible enclosing extension multiplicity,

$$K_{n + 1 \mid n,i} = K_{n + 1 \mid n,k} = K,$$

then

$$P_{n,i} = P_{n,k} = \ln K,$$

even though $K$ may be large.

Therefore,

$$\Delta P_{n,i \rightarrow k} = 0.$$

A larger enclosing multiplicity does not create direction merely by being larger. Directional possibility appears only when the alternative local macrostates have unequal compatible enclosing extension multiplicities:

$$K_{n + 1 \mid n,k} \neq K_{n + 1 \mid n,i}.$$

Then

$$\Delta P_{n,i \rightarrow k} = P_{n,k} - P_{n,i} = \ln\left( \frac{K_{n + 1 \mid n,k}}{K_{n + 1 \mid n,i}} \right).$$

Thus, enclosing multiplicity supplies possibility while unequal compatible enclosing multiplicity supplied direction.

Possibility is not generated by local occupancy and is not an independent primitive force acting on the local landscape. It is a boundary-relative count of compatible enclosing extension. Its **difference across local alternatives** is what can directionally bias realization.

#### 3.5.4 Directional Possibility Within the Local Landscape

For a readable local transition

$$i \rightarrow k,$$

the directional possibility difference is

$$\Delta P_{n,i \rightarrow k} = P_{n,k} - P_{n,i}.$$

Substituting the across-scale definition gives

$$\Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{W_{n,k}} \right) - \ln\left( \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}} \right).$$

Therefore,

$$\Delta P_{n,i \rightarrow k} = \ln\left\lbrack \frac{\Theta_{n + 1 \mid n,k}/W_{n,k}}{\Theta_{n + 1 \mid n,i}/W_{n,i}} \right\rbrack.$$

Equivalently,

$$\Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right) - \ln\left( \frac{W_{n,k}}{W_{n,i}} \right).$$

Since

$$\Delta S_{n,i \rightarrow k} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right),$$

the directional possibility relation becomes

$$\Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right) - \Delta S_{n,i \rightarrow k}.$$

Therefore,

$$\Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right).$$

The local multiplicity difference and the across-scale possibility difference together equal the difference in enclosing multiplicity compatible with the two local alternatives. Possibility therefore favors the local state having the greater multiplicity of compatible enclosing realizations.

3.5.5 Productive Constraint and Retention

The enclosing possibility relation does not uniquely determine local realization. Productive constraint $C^{out}$ can retain the locally expressed possibility within the subordinate landscape.

The total enclosing constraint Cₙ₊₁ is defined by the count relation at Bₙ₊₁. Only its productive component enters local retention at Bₙ. The full enclosing constraint is read at Bₙ₊₁ in the recurrence-weighted R2D law. The decomposition is made explicit in Section 3.9.5.

For the readable transition

$$i \rightarrow k,$$

retention is

$$\Delta R_{n,i \rightarrow k} = C_{n + 1}^{out}\lambda_{n,i \rightarrow k}.$$

The locally readable asymmetry is the possibility that remains after retention:

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k}.$$

Thus,

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - C_{n + 1}^{out}\lambda_{n,i \rightarrow k}.$$

The causal order is therefore

$$\Theta_{n + 1 \mid i} \longrightarrow P_{n,i} \longrightarrow \Delta P_{n,i \rightarrow k} \longrightarrow \Delta A_{n,i \rightarrow k}.$$

Possibility is supplied by enclosing compatible multiplicity. Productive constraint determines how much of that possibility is retained locally.

#### 3.5.6 Occupancy Realized Under Asymmetry

For a readable transition

$$i \rightarrow k,$$

possibility asymmetry maps onto the occupancy landscape not the occurrence count, creating the inequality:

$$\Delta A_{n,i \rightarrow k} = \Delta G_{n,i \rightarrow k} - \Delta\tau_{n,i \rightarrow k}.$$

or

$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}$.

When occurrence count proportionally realizes the native multiplicity,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k},$$

the constrained occupancy relation becomes

$$\Delta G_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

This is not yet the Gibbs free energy equation. The quantity $G$ is not free energy. The quantity $S$ is not thermodynamic entropy. The quantity $A$ is not enthalpy. Temperature, energy, and matter have not yet been defined.

At the **mode-exchange threshold** between candidate structural macrostates $G_{n,i^{*}}$ and $G_{n,k^{*}}$,

$$\Delta G_{n,i^{*} \rightarrow k^{*}} \approx 0.$$

Therefore,

$\Delta S_{n,i^{*} \rightarrow k^{*}} \approx - \Delta A_{n,i^{*} \rightarrow k^{*}}$.

Equivalently,

$\frac{W_{n,k^{*}}}{W_{n,i^{*}}} \approx e^{- \Delta A_{n,i^{*} \rightarrow k^{*}}}$.

The mapped within-scale asymmetry therefore determines where occupancy becomes equally supported between competing macrostates within the fixed native multiplicity landscape.

For a finite binary multiplicity,

$\frac{W_{n,k^{*}}}{W_{n,i^{*}}} = \frac{N_{i^{*}}!\, N_{k^{*}}!}{\left( N_{i^{*}} - 1 \right)!\,\left( N_{k^{*}} + 1 \right)!} = \frac{N_{i^{*}}}{N_{k^{*}} + 1}$.

For large occupancy,

$\frac{N_{i^{*}}}{N_{k^{*}} + 1} \approx \frac{N_{i^{*}}}{N_{k^{*}}}$.

The primitive multiplicity relation therefore becomes, approximately,

$\frac{N_{i}}{N_{k}} \approx e^{- \Delta A_{n}}$.

Interpreting this relation as a probability distribution is an epiphenomenological (EP) projection. The quantities $N_{i}$ and $N_{k}$ are not populations of components occupying distinct microstates. They are not microstate probabilities. The primitive relation is between macrostate possibilities:

$\frac{W_{n,k}}{W_{n,i}} \approx e^{- \Delta A_{n}}$.

Distinguishable macrostates are defined by multiplicities after subordinate identities have been replaced. **The conventional bottom-up interpretation of the Boltzmann probability relation inverts this causal agency.**

The same projected exponential form appears in multiple scientific domains. In each case, the domain-specific quantities assigned to the two sides are different. Probability, activity, structural occupancy, and energetic differences are later readings of the primitive count relation.

The primitive relation underlying the familiar exponential projections is not a relation among energies, molecules, chemical activities, or probabilities. It is a balance between logarithmic multiplicity and mapped dimensionless count bias:

$$\Delta S_{n} \approx - \Delta A_{n}.$$

It is recursive counting before time, space, energy, matter, probability, activity, or fundamental constants have been defined.

#### 3.5.7 Possibility Pulls Occupancy

The logarithmic occupancy difference between two local macrostates is

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

When realized occurrence proportionally realizes native multiplicity,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k}.$$

Therefore,

$$\Delta G_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} - C_{n + 1}^{out}\lambda_{n,i \rightarrow k}.$$

Using the enclosing-multiplicity relation derived above,

$\Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid k}}{\Theta_{n + 1 \mid i}} \right)$,

gives

$\Delta G_{n,i \rightarrow k} \approx \ln\left( \frac{\Theta_{n + 1 \mid k}}{\Theta_{n + 1 \mid i}} \right) - C_{n + 1}^{out}\lambda_{n,i \rightarrow k}$.

Equivalently,

$\frac{c_{n,k}}{c_{n,i}} \approx \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}}\exp\left( - C_{n + 1}^{out}\lambda_{n,i \rightarrow k} \right)$.

In the absence of retention,

$$C_{n + 1} = 0,$$

and therefore

$\frac{c_{n,k}}{c_{n,i}} \approx \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}}$.

Thus, without opposing constraint, relative local occupancy realizes the relative enclosing multiplicity compatible with the local alternatives.

This is the primitive meaning of the statement: **Possibility pulls occupancy.**

The local occupancy ratio is not fundamentally caused by independently acting local components. It is the local realization of unequal enclosing possibility.

#### 3.5.8 Boundary-Level Possibility

The local possibility relations also recover the total multiplicity of the enclosing boundary. From

P$_{n,i} = \ln\left( \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}} \right),$

it follows that

$$\Theta_{n + 1 \mid n,i} = W_{n,i}e^{P_{n,i}}.$$

If the compatibility classes relative to the selected subordinate boundary partition the enclosing possibility domain, then

$$\Theta_{n + 1} = \sum_{i \in \mathcal{M}_{n}}\Theta_{n + 1 \mid n,i}.$$

Therefore,

$$\Theta_{n + 1} = \sum_{i \in \mathcal{M}_{n}}W_{n,i}e^{P_{n,i}}.$$

Since

$$\Theta_{n} = \sum_{i \in \mathcal{M}_{n}}W_{n,i},$$

the total across-scale entropy difference is

$$S_{n + 1}^{B} - S_{n}^{B} = \ln\left( \frac{\Theta_{n + 1}}{\Theta_{n}} \right).$$

Using the local possibility relation,

$$S_{n + 1}^{B} - S_{n}^{B} = \ln\left\lbrack \frac{\sum_{i}W_{n,i}e^{P_{n,i}}}{\sum_{i}W_{n,i}} \right\rbrack.$$

Thus, enclosing multiplicity is reconstructed from the multiplicity-weighted collection of local enclosing extension factors. Local $P$ and boundary-level multiplicity are therefore two readings of the same recursive compatibility structure.

### 3.6 Asymmetric Closure and Nonreciprocal Occurrence Realization

A local macrostate path can return to its starting state without reversing the enclosing relations under which its two opposed branches are realized. This distinction is the basis of asymmetric closure. Consider a minimal local return at representative peer $a$ boundary $B_{n}$:

$$\mathcal{C}_{n,a}:i \rightarrow k \rightarrow i.$$

The local path closes because the final macrostate equals the initial macrostate. But the two legs of that return may be realized under different enclosing compatibility and constraint relations. Let the forward branch

$$i \rightarrow k$$

be realized under enclosing condition $H$, and let the return branch

$$k \rightarrow i$$

be realized under enclosing condition $L$. The enclosing extension multiplicities under the two conditions need not be the same:

$$K_{n + 1 \mid n,i}^{H},\quad\quad K_{n + 1 \mid n,k}^{H},$$

and

$$K_{n + 1 \mid n,i}^{L},\quad\quad K_{n + 1 \mid n,k}^{L}.$$

Likewise, the enclosing constraints on the two legs need not be identical. Thus, local path reversal does not require reversal of the enclosing relation. That distinction allows two different closure properties to be separated: native multiplicity closure and occurrence-count reciprocity.

They are not equivalent conditions.

#### 3.6.1 Changing Enclosing Compatibility

Under enclosing condition $H$, the directional possibility for the forward branch

$$i \rightarrow k$$

is

$$\Delta P_{n,a,H} = \ln\left( \frac{K_{n + 1 \mid n,k}^{H}}{K_{n + 1 \mid n,i}^{H}} \right).$$

Under enclosing condition $L$, the return branch

$$k \rightarrow i$$

has directional possibility

$$\Delta P_{n,a,L} = \ln\left( \frac{K_{n + 1 \mid n,i}^{L}}{K_{n + 1 \mid n,k}^{L}} \right).$$

If the enclosing compatibility relation were unchanged between the two legs,

$$K_{n + 1 \mid n,i}^{H} = K_{n + 1 \mid n,i}^{L},$$

and

$$K_{n + 1 \mid n,k}^{H} = K_{n + 1 \mid n,k}^{L},$$

then

$$\Delta P_{n,a,L} = - \Delta P_{n,a,H},$$

and enclosing possibility would close with the local return. Asymmetric closure does not require those equalities. Instead,

$$\Delta P_{n,a,L} \neq - \Delta P_{n,a,H}$$

is possible because the two structural legs belong to different enclosing compatibility relations. The closure possibility is

$$\Delta P_{n,a,\mathcal{C}} = \Delta P_{n,a,H} + \Delta P_{n,a,L}.$$

Substituting the extension multiplicities gives

$$\Delta P_{n,a,\mathcal{C}} = \ln\left( \frac{K_{n + 1 \mid n,k}^{H}K_{n + 1 \mid n,i}^{L}}{K_{n + 1 \mid n,i}^{H}K_{n + 1 \mid n,k}^{L}} \right).$$

Therefore,

$$\Delta P_{n,a,\mathcal{C}} = 0$$

only when

$$K_{n + 1 \mid n,k}^{H}K_{n + 1 \mid n,i}^{L} = K_{n + 1 \mid n,i}^{H}K_{n + 1 \mid n,k}^{L}.$$

The local macrostate can therefore return while the enclosing compatibility relation fails to compose with its reciprocal. This is the primitive count structure of asymmetric closure.

3.6.2 The Asymmetric Productive-Constraint Cycle

The productive component of enclosing constraint can also differ between the two branches. Let the forward branch be realized under productive constraint

$$C_{n + 1}^{out,H},$$

and the return branch under

$$C_{n + 1}^{out,L}.$$

For the forward transition,

$$i \rightarrow k,$$

retention is

$${\Delta R}_{n,a,H} = C_{n + 1}^{out,H}\lambda_{n,a,i \rightarrow k}.$$

The corresponding local asymmetry is

$$\Delta A_{n,a,H} = \Delta P_{n,a,H} - {\Delta R}_{n,a,H}.$$

For the return transition,

$$k \rightarrow i,$$

retention is

$${\Delta R}_{n,a,L} = C_{n + 1}^{out,L}\lambda_{n,a,k \rightarrow i}.$$

Because distinguishability is oriented,

$$\lambda_{n,a,k \rightarrow i} = - \lambda_{n,a,i \rightarrow k}.$$

The return-branch asymmetry is

$$\Delta A_{n,a,L} = \Delta P_{n,a,L} - {\Delta R}_{n,a,L}.$$

The structural path nevertheless returns:

$$i \rightarrow k \rightarrow i.$$

Thus, the turbine-like local path can close even though its opposed branches are realized under different enclosing possibility and productive-constraint relations. The closure-level retention is

$${\Delta R}_{n,a,\mathcal{C}} = {\Delta R}_{n,a,H} + {\Delta R}_{n,a,L}.$$

The closure-level asymmetry is therefore

$${\Delta A}_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - {\Delta R}_{n,a,\mathcal{C}}.$$

Asymmetric closure is therefore not defined by failure of the local state to return. It is defined by the fact that the enclosing relations organizing the two opposed legs need not be recursive inverses.

#### 3.6.3 Exact Native Multiplicity Closure

The native multiplicity landscape remains fixed throughout a completed local return. For the forward branch,

$$\Delta S_{n,a,i \rightarrow k} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right).$$

For the return branch,

$$\Delta S_{n,a,k \rightarrow i} = \ln\left( \frac{W_{n,i}}{W_{n,k}} \right).$$

Therefore,

$$\Delta S_{n,a,\mathcal{C}} = \Delta S_{n,a,i \rightarrow k} + \Delta S_{n,a,k \rightarrow i}.$$

Hence,

$$\Delta S_{n,a,\mathcal{C}} = 0.$$

Native multiplicity closes exactly because the two local multiplicity ratios are reciprocal. This result does not require enclosing possibility to close. Therefore,

$$\Delta S_{n,a,\mathcal{C}} = 0$$

does not imply

$$\Delta P_{n,a,\mathcal{C}} = 0.$$

The two quantities belong to different count relations. The first belongs entirely to the native local multiplicity landscape. The second depends on the enclosing compatibility relations under which the opposed branches are realized.

#### 3.6.4 Retention and Closure Asymmetry

Possibility and productive retention are separately accumulated around the completed closure:

$$\Delta P_{n,a,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,a}}\Delta P_{n,a,\chi},$$

and

$${\Delta R}_{n,a,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,a}}{\Delta R}_{n,a,\chi}.$$

The net closure asymmetry is

$${\Delta A}_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - {\Delta R}_{n,a,\mathcal{C}}.$$

Complete retention around the closure satisfies

$${\Delta A}_{n,a,\mathcal{C}} = 0.$$

Equivalently,

$${\Delta R}_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}}.$$

Incomplete retention satisfies

$${\Delta A}_{n,a,\mathcal{C}} \neq 0.$$

This statement should not be interpreted as a bottom-up export of an unretained quantity. It states only that the enclosing-defined possibility and the local retention relation do not cancel around the completed peer closure. Thus, the closure can satisfy simultaneously

$$\Delta S_{n,a,\mathcal{C}} = 0$$

and

$${\Delta A}_{n,a,\mathcal{C}} \neq 0.$$

The local native multiplicity closes while the enclosing-defined asymmetry need not.

#### 3.6.5 Occurrence Realization Around Closure

Multiplicity specifies possible count. Occurrence count describes realization. Let the completed closure

$$\mathcal{C}_{n,a}$$

contain two opposed oriented legs,

$$H_{n,a}\quad\quad\text{and}\quad\quad L_{n,a},$$

each consisting of an ordered sequence of readable transitions. Within a specified finite realization domain $\mathcal{D}$, let

$$\nu_{n,a,H} = N_{\mathcal{D}}\left( H_{n,a} \right)$$

denote the number of completed realizations of the entire oriented leg $H$, and let

$$\nu_{n,a,L} = N_{\mathcal{D}}\left( L_{n,a} \right)$$

denote the number of completed realizations of the opposed leg $L$.

These are **path occurrence counts**. They count complete realizations of the two opposed legs. They are not sums of the state occurrence counts $\nu_{n,i}$ of the transitions composing those legs. Their logarithmic leg-occurrence coordinates are

$$\tau_{n,a,H} = \ln \nu_{n,a,H},\quad\quad\tau_{n,a,L} = \ln \nu_{n,a,L}.$$

The state occurrence coordinate introduced in Section 3.3.3 remains

$$\tau_{n,i} = \ln \nu_{n,i},$$

with transition difference

$$\Delta\tau_{n,i \rightarrow k} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right).$$

Because $\tau_{n,i}$ is state-defined, the signed transition differences telescope around any genuine closed state path:

$$\sum_{\chi \in \mathcal{C}_{n,a}}\Delta\tau_{n,a,\chi} = 0.$$

This identity says only that the state occurrence coordinate returns with the closed state path. It does **not** count how many times the closure recurs, and it does not determine whether the two opposed legs are realized equally often. Closure recurrence is a separate count relation introduced in Section 3.7.

#### 3.6.6 Reciprocal and Nonreciprocal Occurrence Realization

Define the directional occurrence-count efficiency of the completed closure as

$$\eta_{n,a,\mathcal{C}} = \frac{\nu_{n,a,L}}{\nu_{n,a,H}}.$$

Choose the orientation such that

$$0 < \eta_{n,a,\mathcal{C}} \leq 1.$$

Define the logarithmic opposed-leg occurrence difference

$$\Delta\tau_{n,a,\mathcal{C}} \equiv \tau_{n,a,L} - \tau_{n,a,H} = \ln \eta_{n,a,\mathcal{C}}.$$

Reciprocal occurrence realization satisfies

$$\eta_{n,a,\mathcal{C}} = 1,$$

or equivalently,

$$\nu_{n,a,L} = \nu_{n,a,H}$$

and

$$\Delta\tau_{n,a,\mathcal{C}} = 0.$$

Nonreciprocal occurrence realization satisfies

$$0 < \eta_{n,a,\mathcal{C}} < 1,$$

or equivalently,

$$\nu_{n,a,L} < \nu_{n,a,H}$$

and

$$\Delta\tau_{n,a,\mathcal{C}} < 0.$$

This inequality does not mean that occurrence count has been destroyed. It states that the two opposed legs of the completed closure realize occurrence count with unequal directional efficiency. Reversibility of occurrence realization, state-occurrence closure, and recurrence frequency are therefore distinct relations.

A closure can have

$$\Delta P_{n,a,\mathcal{C}} \neq 0$$

while

$$\eta_{n,a,\mathcal{C}} = 1,$$

or it can have

$$\Delta P_{n,a,\mathcal{C}} \neq 0$$

and

$$0 < \eta_{n,a,\mathcal{C}} < 1.$$

Asymmetric enclosing organization does not by itself mathematically require nonreciprocal occurrence realization. That additional relation is specified by the realization postulates.

#### 3.6.7 Occurrence-Count Loss

For the chosen orientation, define the logarithmic occurrence-count loss as

$$L_{\tau,n,a,\mathcal{C}} = - \ln \eta_{n,a,\mathcal{C}}.$$

Using the opposed-leg occurrence difference,

$$\boxed{L_{\tau,n,a,\mathcal{C}} = - \Delta\tau_{n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right).}$$

Because

$$0 < \eta_{n,a,\mathcal{C}} \leq 1,$$

it follows that

$$L_{\tau,n,a,\mathcal{C}} \geq 0.$$

Hence,

$$L_{\tau,n,a,\mathcal{C}} = 0 \Leftrightarrow \eta_{n,a,\mathcal{C}} = 1,$$

while

$$L_{\tau,n,a,\mathcal{C}} > 0 \Leftrightarrow 0 < \eta_{n,a,\mathcal{C}} < 1.$$

Occurrence-count loss is therefore not a primitive destruction process. It is the logarithmic consequence of unequal directional occurrence-count efficiency around a completed closure. Native multiplicity can close exactly,

$$\Delta S_{n,a,\mathcal{C}} = 0,$$

while the realized opposed-leg occurrence relation remains nonreciprocal,

$$L_{\tau,n,a,\mathcal{C}} > 0.$$

#### 3.6.8 Finite-Count Realization of Directional Efficiency

Finite counts provide a minimal candidate realization of this nonreciprocity. Consider a binary local realization with finite positive counts

$$N_{i} > 0,\quad\quad N_{k} > 0.$$

Define the opposed finite-count realization factors

$$\epsilon_{H} = \frac{N_{i}}{N_{k} + 1},$$

and

$$\epsilon_{L} = \frac{N_{k}}{N_{i} + 1}.$$

Their product is

$$\epsilon_{H}\epsilon_{L} = \frac{N_{i}N_{k}}{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}.$$

For finite positive counts,

$$0 < \epsilon_{H}\epsilon_{L} < 1.$$

This inequality is an exact finite-count result. The two factors are opposed branch factors. They are not an edge and its exact inverse. If the second factor were the exact inverse of the first,

$$\epsilon_{H}^{-1} = \frac{N_{k} + 1}{N_{i}},$$

then

$$\epsilon_{H}\epsilon_{H}^{-1} = 1.$$

The opposed finite-count construction instead gives

$$\epsilon_{H}\epsilon_{L} < 1.$$

R²D makes the additional realization postulate

$$\eta_{n,a,\mathcal{C}} = \epsilon_{H}\epsilon_{L}.$$

Therefore,

$$\eta_{n,a,\mathcal{C}} = \frac{N_{i}N_{k}}{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}.$$

The corresponding occurrence-count loss is then

$$L_{\tau,n,g,\mathcal{C}} = \ln\left\lbrack \frac{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}{N_{i}N_{k}} \right\rbrack.$$

The logical distinction is important:

$$0 < \epsilon_{H}\epsilon_{L} < 1$$

is derived from finite counting. The identification

$$\eta_{n,a,\mathcal{C}} = \epsilon_{H}\epsilon_{L}$$

is an R²D realization postulate. No destruction of multiplicity, occurrence, or direction is assumed.

#### 3.6.9 What Closes and What Need Not Close

A completed asymmetric closure therefore contains several distinct count relations. Native possible multiplicity closes exactly:

$$\Delta S_{n,a,\mathcal{C}} = 0.$$

Enclosing possibility need not close:

$$\Delta P_{n,a,\mathcal{C}} \neq 0$$

in general.

Retention need not equal enclosing possibility:

$$\Delta R_{n,a,\mathcal{C}} \neq \Delta P_{n,a,\mathcal{C}}$$

in general.

Thus closure asymmetry may remain:

$$\Delta A_{n,a,\mathcal{C}} \neq 0.$$

And occurrence realization need not be reciprocal:

$$0 < \eta_{n,a,\mathcal{C}} < 1.$$

These are different statements. They should not be collapsed into one notion of irreversibility. Exact native multiplicity closure describes possible-count return. Closure asymmetry describes the enclosing possibility-retention relation. Opposed-leg efficiency describes directional occurrence reciprocity. The number of times the completed closure recurs is a fourth and separate count relation introduced next.

Nothing in this section requires count destruction or bottom-up export. The relation between nonreciprocal occurrence realization and enclosing nondirectional background is a separate R2D postulate developed later in the Second Law of Recursive Counting.

### 3.7 Recurrence Count and Across-Boundary Recurrence Ratio

Occurrence and recurrence are different count relations.

The state occurrence count

$$\nu_{n,i}$$

counts realized instances classified as macrostate $i$ within a specified finite realization domain. Its logarithmic coordinate

$$\tau_{n,i} = \ln \nu_{n,i}$$

therefore describes relative occurrence structure among states. Likewise, $\nu_{n,a,H}$ and $\nu_{n,a,L}$ count completed realizations of the two opposed legs of one closure relation.

Neither quantity specifies how frequently the complete closure itself recurs relative to an enclosing occurrence.

To define that relation, choose a finite **recurrence-comparison domain** $\mathcal{D}_{R}$ in which completed recurrences at adjacent boundaries are jointly counted. Let

$$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)$$

be the number of completed recurrences of representative peer closure $\mathcal{C}_{n,a}$, and let

$$N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)$$

be the number of completed realizations of the corresponding enclosing transition class $\chi_{n + 1}$ within the same comparison domain.

These are whole-recurrence counts. They are distinct from the state occurrence counts $\nu_{n,i}$ and from the opposed-leg counts $\nu_{n,a,H}$ and $\nu_{n,a,L}$.

For

$$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) > 0,$$

define the adjacent recurrence ratio

$$\boxed{\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}.}$$

The ratio asks:

**How many enclosing recurrences are realized per completed recurrence of the representative local closure?**

No physical time interval is assumed. $\mathcal{D}_{R}$ is a count domain. If the comparison domain is enlarged while the same stationary recurrence relation is preserved, numerator and denominator scale together and $\rho_{n + 1 \mid n,a}$ is unchanged.

The logarithmic recurrence scaling is

$$\gamma_{n + 1 \mid n,a} = \ln \rho_{n + 1 \mid n,a}$$

for $\rho_{n + 1 \mid n,a} > 0$.

A zero recurrence ratio,

$$\rho_{n + 1 \mid n,a} = 0,$$

means that the local closure can recur while the corresponding enclosing transition does not recur within the comparison domain. This is permitted. In particular, it is distinct from $\Delta\tau = 0$, which only states equality of relative state or leg occurrence counts.

The recurrence ratio is the count relation later available for a physical rate mapping. Part I does not yet identify $\mathcal{D}_{R}$ with elapsed time and does not assign units of inverse time to $\rho$.

### 3.8 Recursive Carry

Recursive carry is the change in count meaning that occurs when one recursively organized realization is read from adjacent boundaries. It is not a process by which subordinate closures accumulate to create an enclosing occurrence. The causal relation has the opposite orientation.

An enclosing occurrence defines which joint peer realizations are compatible with it. Those compatible peer realizations provide its locally readable expression. When a completed peer realization is subsequently read from the enclosing boundary, its peer-specific path no longer retains the same count identity.

R²D calls that boundary-relative reclassification **recursive carry**. Thus, recursive carry must be distinguished from causal realization.

#### 3.8.1 The Enclosing Occurrence Defines Compatible Peer Closures

Consider a readable enclosing transition at $B_{n + 1}$,

$$\chi_{n + 1}:j \rightarrow k.$$

Let

$$\chi_{n + 1}^{(r)}$$

denote one realized occurrence associated with that transition. The peer subordinate boundaries are

$$\left\{ B_{n,a} \right\}_{a \in I_{n}}.$$

At each peer boundary, the enclosing occurrence may be locally readable through a completed closure

$$\mathcal{C}_{n,a}.$$

The enclosing occurrence defines the set of jointly compatible peer closures:

$$\mathfrak{D}_{n + 1,\chi} = \left\{ \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}}:\left( \mathcal{C}_{n,a} \right)_{a \in I_{n}}\text{~}\text{is~jointly~compatible~with}\text{~}\chi_{n + 1}^{(r)} \right\}.$$

Therefore,

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

This is the causal realization relation. The enclosing occurrence defines which combinations of peer closures are compatible with its realization. The peer closures do not independently combine to generate that occurrence. Thus, the whole defines its compatible local realizations.

The subordinate peer structures remain necessary. They determine how the enclosing occurrence is locally realized. They do not determine why that enclosing occurrence exists or why one enclosing direction is favored. The causal distinction is therefore

$$\text{enclosing~occurrence} \Longrightarrow \text{compatible~local~realization}.$$

#### 3.8.2 Recursive Carry Is Boundary-Relative Reclassification

Now select one compatible peer $a$. Relative to $B_{n}$, the realization is readable as a completed local macrostate closure:

$$\mathcal{C}_{n,a}.$$

For example,

$$\mathcal{C}_{n,a}:i \rightarrow k \rightarrow i.$$

The local states, peer-source identity, and internal path are readable relative to $B_{n}$. From $B_{n + 1}$, however, those same labels do not remain readable as the same macrostate path. The completed local realization is instead classified according to the enclosing occurrence to which it belongs.

R²D denotes this reclassification by

$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$.

This arrow is not causal. It does not mean

$$\mathcal{C}_{n,a} \Longrightarrow \chi_{n + 1}^{(r)}.$$

The causal relation is instead

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}.$$

Thus, the two relations are causal realization:

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}$$

and recursive carry:

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

The opposite orientations do not describe two opposed causal flows. They answer different questions.

The causal arrow asks: **Which local realizations are compatible with this enclosing occurrence?**

The carry arrow asks: **How is this completed local realization classified when the count boundary changes?**

Recursive carry therefore changes count identity without reversing causal orientation.

#### 3.8.3 Recursive Carry Is Not Persistence of the Same State

Recursive carry should not be interpreted as movement of one unchanged object from $B_{n}$ into $B_{n + 1}$. A local closure

$$\mathcal{C}_{n,a}$$

is defined through the macrostate distinctions readable at $B_{n + 1}$. The enclosing occurrence

$$\chi_{n + 1}^{(r)}$$

belongs to a different count domain with different readable states and transitions. Therefore,

$$\mathcal{C}_{n,a} \not\equiv \chi_{n + 1}^{(r)}$$

as boundary-defined count objects. Recursive carry instead states that they are two boundary-specific readings of one recursively organized realization relation. Thus, local state identity is replaced, and recursive relation remains consequential.

This is stronger than ordinary coarse graining. The subordinate path is not merely hidden while remaining the primitive state of the enclosing description. The count boundary has changed, and with it the classification of the realized relation. A peer closure is therefore more precisely described as the subordinate reading of an enclosed occurrence.

Recursive carry reclassifies that subordinate reading according to the enclosing occurrence to which it belongs.

#### 3.8.4 One Enclosing Occurrence Can Have Multiple Compatible Peer Realizations

One enclosing occurrence generally organizes more than one peer boundary. Thus,

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

For any selected peer ,

$$\mathcal{C}_{n,a} \in {{pr}_{a}\mathfrak{D}}_{n + 1,\chi},$$

where

$${pr}_{a}$$

denotes projection of the compatible joint closure relation onto peer $a$. The local closure at $B_{n}$is therefore one peer-specific realization compatible with the same enclosing occurrence. If the peer boundaries are equivalent under the enclosing compatibility relation, multiple peers can provide equivalent local readings:

$$\mathcal{C}_{n,a} \sim_{n + 1}\mathcal{C}_{n,b}.$$

In that case, one peer $a$ may be selected as a representative peer. Thus,

$$\mathcal{C}_{n,a} = \text{one~representative~local~realization~of~}\chi_{n + 1}^{(r)}.$$

The representative peer is not obtained by averaging the effects of all peers. Nor does the representative peer alone generate the enclosing occurrence. Its role follows from equivalence under the common enclosing compatibility relation. When peer closures are not equivalent, the peer index must remain explicit. No representative-peer reduction is then assumed.

#### 3.8.5 Recursive Carry Is Generally Many-to-One

Different locally readable closures may be classified as realizations of the same enclosing occurrence. Suppose

$$\mathcal{C}_{n,a} \neq \mathcal{C}_{n,b},$$

but

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

and

$$\mathcal{C}_{n,b}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

Then the enclosing occurrence does not uniquely identify which local peer-source path was realized. Schematically,

$$\left| \kappa_{n}^{-1}\left( \chi_{n + 1}^{(r)} \right) \right| > 1.$$

where more than one locally distinguishable realization belongs to the same enclosing classification. Thus, recursive carry can preserve count meaning while removing recoverable local path identity.

This is not destruction of the subordinate realization. The local path remains definable relative to the boundary at which it was readable. It simply cannot be uniquely reconstructed from the enclosing occurrence alone.

#### 3.8.6 The Carry Symbol Denotes Reclassification, Not Dynamics

Throughout Part I,

$$\overset{\kappa_{n}}{\mapsto}$$

denotes recursive reclassification under a change from $B_{n}$ to $B_{n + 1}$. It should not be interpreted as a dynamical evolution operator acting on one persistent state space. For a completed local closure,

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

means that the locally readable realization has enclosing occurrence meaning when read from $B_{n}$. For a relation among compatible local realizations,

$$\mathcal{R}_{n}\overset{\kappa_{n}}{\mapsto}\mathcal{R}_{n + 1}$$

means that the relational organization has a corresponding enclosing classification after the boundary changes. Thus $\overset{\kappa_{n}}{\mapsto}$ denotes the **operation of recursive reclassification**, not a causal interaction between adjacent scales. The common meaning is change in count meaning under change of boundary.

#### 3.8.7 Recursive Carry and Irreversibility Are Different Relations

Recursive carry does not require occurrence realization around the local closure to be reciprocal. From Section 3.7, a completed local closure may satisfy

$$\Delta S_{n,a,\mathcal{C}} = 0$$

while

$$L_{\tau,n,a,\mathcal{C}} > 0.$$

That nonreciprocity does not redefine recursive carry. Recursive carry asks how a completed local realization is classified from the enclosing boundary. Occurrence-count loss asks whether the opposed legs of that local realization have equal directional efficiency.

These are separate questions. Recursive carry is a cross-boundary reclassification. Occurrence count loss is a local directional nonreciprocity.

There is therefore no primitive "surviving fraction" that must first be selected before recursive carry can occur. Nor does recursive carry divide realization into an upward directed channel and an upward background channel. The relation between occurrence-count loss at the representative peer boundary and nondirectional background at the enclosing boundary is a separate R²D postulate:

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

That relation belongs to the Second Law of Recursive Counting developed below. It is not part of the definition of recursive carry.

#### 3.8.8 The Recursive Architecture

For every nonterminal boundary, the architecture can therefore be summarized by two complementary relations. Causally,

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

Under change of count boundary,

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

These equations are not a causal cycle. They are two readings of one recursive relation. The first expresses **enclosing definition of compatible local realization**. The second expresses **boundary-relative reclassification of that completed realization**. Thus, the whole defines its compatible realizations. Recursive carry changes how that realization is counted across boundaries.

This is the recursive architecture required by the R²D law.

### 3.9 The R2D Law

Recursive carry establishes that one recursively organized occurrence can have different readable forms at adjacent boundaries.

At the enclosing boundary $B_{n + 1}$, the occurrence is readable through an enclosing transition

$$\chi_{n + 1}:j \rightarrow k.$$

At a compatible peer boundary $B_{n,a}$, the same recursively organized relation is locally realized through completed recurrences of

$$\mathcal{C}_{n,a}.$$

The causal relation is

$$\chi_{n + 1}^{(r)} \Rightarrow \mathcal{C}_{n,a}.$$

Recursive carry gives the complementary boundary-relative reading:

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

These relations specify compatibility and reclassification. They do not require a one-to-one equality between the number of local closure recurrences and the number of enclosing transition recurrences in a larger comparison domain. Their relative recurrence is counted separately by $\rho_{n + 1 \mid n,a}$.

#### 3.9.1 Representative-Peer Recurrence

Consider one representative peer closure

$$\mathcal{C}_{n,a}.$$

Its accumulated enclosing-defined possibility is

$$\Delta P_{n,a,\mathcal{C}},$$

its accumulated retention is

$$\Delta R_{n,a,\mathcal{C}},$$

and its net closure asymmetry is

$$\Delta A_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - \Delta R_{n,a,\mathcal{C}}.$$

Within a fixed representative closure relation and recurrence-comparison domain $\mathcal{D}_{R}$, let

$$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)$$

count completed local recurrences. The recurrence-weighted local asymmetry is therefore

$$\Delta A_{n,a,\mathcal{C}}\, N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right).$$

This is not energy, power, or elapsed time. It is a dimensionless count relation: closure asymmetry per local recurrence multiplied by the number of local recurrences in the comparison domain.

#### 3.9.2 Enclosing Recurrence

At $B_{n + 1}$, the same recursively organized relation is read through enclosing distinguishability

$$\lambda_{n + 1}$$

and total enclosing constraint

$$C_{n + 1} \geq 0.$$

The constrained distinguishability per enclosing recurrence is

$$C_{n + 1}\lambda_{n + 1}.$$

Let

$$N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)$$

count completed recurrences of the enclosing transition class within the same recurrence-comparison domain. The recurrence-weighted enclosing constrained distinguishability is

$$C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).$$

#### 3.9.3 The R2D Law

R2D postulates equality of these two boundary-specific recurrence-weighted readings:

$$\boxed{\Delta A_{n,a,\mathcal{C}}\, N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).}$$

Using the adjacent recurrence ratio

$$\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)},$$

the law may be written more compactly as

$$\boxed{\Delta A_{n,a,\mathcal{C}} = C_{n + 1}\lambda_{n + 1}\rho_{n + 1 \mid n,a}.}$$

Using

$$\Delta A_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - \Delta R_{n,a,\mathcal{C}},$$

this becomes

$$\boxed{\Delta P_{n,a,\mathcal{C}} - \Delta R_{n,a,\mathcal{C}} = C_{n + 1}\lambda_{n + 1}\rho_{n + 1 \mid n,a}.}$$

This is the **R2D law**.

Its causal interpretation must be stated carefully. The law does not mean

$$\mathcal{C}_{n,a} \Rightarrow \chi_{n + 1}^{(r)}.$$

The local closure does not generate the enclosing occurrence. The causal relation remains

$$\chi_{n + 1}^{(r)} \Rightarrow \mathcal{C}_{n,a}.$$

The equality states that, over one common recurrence-comparison domain, the local asymmetry realized through representative closure recurrence and the enclosing constrained distinguishability read through enclosing recurrence possess one invariant recursive count relation.

The left side asks: **How much enclosing-defined asymmetry is realized per recurrence of the compatible local closure?**

The right side asks: **How much constrained distinguishability is read per enclosing recurrence, and how frequently does that recurrence occur relative to the local closure?**

The equality is an invariant relation between boundary-specific readings, not a causal arrow between them.

#### 3.9.4 Why One Representative Peer Appears in the Law

One enclosing occurrence may be realized compatibly across many peer boundaries:

$$\chi_{n + 1}^{(r)} \Rightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

If peers $a$ and $b$ are equivalent under the enclosing compatibility relation associated with the same enclosing transition class, either may serve as a representative local realization. Applying the R2D law gives

$$\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right),$$

and

$$\Delta A_{n,b,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,b} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).$$

Therefore,

$$\boxed{\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = \Delta A_{n,b,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,b} \right).}$$

Equivalently, when the recurrence ratios are positive,

$$\frac{\Delta A_{n,a,\mathcal{C}}}{\rho_{n + 1 \mid n,a}} = \frac{\Delta A_{n,b,\mathcal{C}}}{\rho_{n + 1 \mid n,b}} = C_{n + 1}\lambda_{n + 1}.$$

The representative peer does not stand in for the other peers because their causal contributions have been averaged. It stands in for them because they occupy the same compatibility class relative to the enclosing occurrence. If peer closures are not equivalent under the relevant enclosing relation, the peer index must remain explicit.

#### 3.9.5 Productive and Background-Associated Constraint

The enclosing constraint may be decomposed into two components:

$$C_{n + 1} = C_{n + 1}^{out} + C_{n + 1}^{\Phi}.$$

The productive component

$$C_{n + 1}^{out}$$

is the component that defines local retention at Bₙ and whose enclosing realization remains readable as distinguishable output. The background-associated component

$$C_{n + 1}^{\Phi}$$

contributes to the same enclosing occurrence but does not enter local retention. Its associated realization is read as background. The two components are not separate transitions or separate occurrence pathways.

The R2D law therefore becomes

$$\boxed{\Delta A_{n,a,\mathcal{C}} = \left( C_{n + 1}^{out} + C_{n + 1}^{\Phi} \right)\lambda_{n + 1}\rho_{n + 1 \mid n,a}.}$$

Or, in recurrence-count form,

$$\boxed{\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = \left( C_{n + 1}^{out} + C_{n + 1}^{\Phi} \right)\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).}$$

The productive term is read as retained distinguishable output:

$$C_{n + 1}^{out}\lambda_{n + 1} \leftrightarrow \text{retained distinguishable output},$$

while

$$C_{n + 1}^{\Phi}\lambda_{n + 1} \leftrightarrow \text{background-associated realization}.$$

The R2D law does **not** separately postulate a quantitative identity between

$$C_{n + 1}^{\Phi}\lambda_{n + 1}$$

and the background increment

$$\delta_{\mathcal{C}}\Phi_{n + 1}.$$

The Second Law separately postulates

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

Thus the two postulates remain distinct:

**R2D law:** local recurrence-weighted asymmetry ↔

enclosing recurrence-weighted constrained distinguishability.

**Second Law:** local opposed-leg occurrence nonreciprocity ↔

enclosing background increment.

#### 3.9.6 The Meaning of the R²D Law

The R²D law can therefore be summarized without implying bottom-up causation. Causally,

$$\chi_{n + 1}^{(r)} \Rightarrow \mathcal{C}_{n,a}.$$

Under change of boundary,

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

Recursively,

$$\Delta A_{n,a,\mathcal{C}} = C_{n + 1}\lambda_{n + 1}\rho_{n + 1 \mid n,a}.$$

The three statements answer three different questions. The causal relation states which local realization belongs to the enclosing occurrence. Recursive carry states how the completed local realization changes count meaning when the boundary changes. The R2D law states how recurrence-weighted realization is related between the two boundaries.

Part I assigns no physical time unit to $\rho$. A later domain-specific mapping may read the same recurrence ratio as a ratio of physical rates. That mapping is an empirical burden of the later program, not an assumption of Part I.

### 3.10 The Second Law of Recursive Counting

The second law concerns the realization of occurrence count around closure. A completed closure contains opposed directional legs. The local structural path may return exactly, and the native multiplicity may close exactly, while the two legs realize occurrence count with different directional efficiencies.

Irreversibility therefore does not require destruction of multiplicity, destruction of occurrence, or destruction of direction. It requires **nonreciprocal occurrence-count realization around closure**. The primitive distinction is that exact structural closure does not produce equal directional efficiency of occurrence count.

#### 3.10.1 Background Is Boundary-Relative

Let peer boundaries $a$ and $b$ have background counts

$$b_{n,a} > 0,\quad\quad b_{n,b} > 0,$$

with logarithmic coordinates

$$\Phi_{n,a} = \ln b_{n,a},$$

and

$$\Phi_{n,b} = \ln b_{n,b}.$$

Within each peer boundary, background is common to the local macrostates:

$$\Delta\Phi_{n,a,i \rightarrow k} = 0.$$

Background therefore does not independently select a local macrostate. But the two peer backgrounds can be distinguishable from the enclosing boundary. Define the enclosing comparison

$$\Delta\Phi_{n + 1 \mid n,a:b} = \Phi_{n,a} - \Phi_{n,b} = \ln\left( \frac{b_{n,a}}{b_{n,b}} \right).$$

If

$$\Delta\Phi_{n + 1 \mid n,a:b} \neq 0,$$

then the enclosing boundary reads a distinguishable relation between the two subordinate backgrounds. The individual quantities remain background locally. Their difference is an enclosing distinction. If

$$\Delta\Phi_{n + 1 \mid n,a:b} = 0,$$

then the two backgrounds are indistinguishable from that enclosing boundary. Thus, background is nondirectional only relative to the boundary at which it is background.

#### 3.10.2 Directional Efficiency of Occurrence Count

Consider one representative peer closure

$$\mathcal{C}_{n,a}$$

with two opposed legs, labeled H and L. Let

$$\nu_{n,a,H}$$

be the occurrence count associated with one leg and

$$\nu_{n,a,L}$$

the occurrence count associated with completion of the opposed return leg. Define the net directional occurrence-count efficiency of the completed closure as

$$\eta_{n,a,\mathcal{C}} = \frac{\nu_{n,a,L}}{\nu_{n,a,H}}.$$

For reciprocal occurrence realization,

$$\eta_{n,a,\mathcal{C}} = 1.$$

Equivalently,

$$\nu_{n,a,L} = \nu_{n,a,H}.$$

For an irreversible closure, choose the orientation such that the return leg has lower directional count efficiency:

$$\nu_{n,a,L} < \nu_{n,a,H}.$$

Then

$$0 < \eta_{n,a,\mathcal{C}} < 1.$$

This does not mean that occurrence count has been destroyed. It means that the opposed legs of the closure realize occurrence count with unequal directional efficiency.

#### 3.10.3 Occurrence-Count Loss

Define the logarithmic occurrence-count loss around the representative closure as

$$L_{\tau,n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right).$$

Using the directional efficiency,

$$L_{\tau,n,a,\mathcal{C}} = - {\ln\eta}_{n,a,\mathcal{C}}.$$

For reciprocal occurrence closure,

$$L_{\tau,n,a,\mathcal{C}} = 0.$$

For irreversible occurrence closure,

$$L_{\tau,n,a,\mathcal{C}} > 0.$$

Occurrence-count loss is therefore not annihilation of count. It is the logarithmic count deficit produced because the two legs of the cycle realize occurrence count with unequal directional efficiency. The native multiplicity nevertheless closes exactly:

$$\Delta S_{n,a,\mathcal{C}} = 0.$$

Thus, an irreversible closure may satisfy simultaneously

$$\Delta S_{n,a,\mathcal{C}} = 0,$$

and

$$L_{\tau,n,a,\mathcal{C}} > 0.$$

Possible multiplicity closes. Occurrence-count realization is nonreciprocal.

#### 3.10.4 Occurrence-Count Loss and Enclosing Background

Let

b~n+1~^-^

and

b~n+1~^+^

denote the enclosing background counts before and after the realization relation associated with the representative closure.

Define the logarithmic background increment

δ~C~ Φ~n+1~ = ln(b~n+1~^+^/b~n+1~^-^).

R²D postulates that the occurrence-count loss read around the representative peer closure and the enclosing background increment are two boundary-specific readings of the same recursively realized occurrence relation:

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

Equivalently,

$$\delta_{\mathcal{C}}\Phi_{n + 1} = - \Delta\tau_{n,a,\mathcal{C}}.$$

This relation equates logarithmic count coordinates. It does not assert arithmetic equality between raw occurrence counts and raw background counts. It also does not describe a bottom-up transfer in which local count loss creates the enclosing background. The causal organization remains enclosing-to-subordinate.

The two quantities are different boundary-specific readings:

$$\begin{aligned}
B_{n,a}: & \quad\text{nonreciprocal~occurrence-count~realization}, \\
B_{n + 1}: & \quad\text{background~increment}.
\end{aligned}$$

Recursive carry relates these readings without reversing their causal ordering.

#### 3.10.5 Productive and Dissipative Realization

The enclosing occurrence may be realized against the total constraint

$$C_{n + 1} = C_{n + 1}^{out} + C_{n + 1}^{\Phi}.$$

The productive component is read as retained distinguishable output:

$$C_{n + 1}^{out}\lambda_{n + 1}.$$

The dissipative component is read after realization as part of the enclosing background:

$$C_{n + 1}^{\Phi}\lambda_{n + 1}.$$

Thus,

$$C_{n + 1}^{out}\lambda_{n + 1}\mspace{6mu} \longleftrightarrow \mspace{6mu}\text{retained~distinguishability}$$

while

$$C_{n + 1}^{\Phi}\lambda_{n + 1}\mspace{6mu} \longleftrightarrow \mspace{6mu}\text{background~realization}.$$

The productive component is also the component that defines local retention at Bₙ; the background-associated component does not enter that retention. The two components do not define separate occurrence pathways. They partition how the same enclosing distinguishable realization is read. The local occurrence-count loss

$$L_{\tau,n,a,\mathcal{C}}$$

describes the unequal directional efficiency of the representative closure. The enclosing background increment

$$\delta_{\mathcal{C}}\Phi_{n + 1}$$

describes the corresponding nondirectional background reading at the enclosing boundary. No primitive category of count destruction or directional destruction is required.

#### 3.10.6 A Passive Closure Does Not Cause Irreversibility

A turbine-like closure is a local realization of an enclosing occurrence. It does not create the enclosing relation that organizes it. The closure may retain part of that enclosing realization as distinguishable output. If the opposed legs realize occurrence count reciprocally,

$$\eta_{n,a,\mathcal{C}} = 1,$$

then

$$L_{\tau,n,a,\mathcal{C}} = 0.$$

If the opposed legs have unequal directional efficiency,

$$\eta_{n,a,\mathcal{C}} < 1,$$

then

$$L_{\tau,n,a,\mathcal{C}} > 0.$$

The presence of productive output does not define whether the closure is irreversible.

In particular,

$$C_{n + 1}^{out} = 0$$

does not require

$$L_{\tau,n,a,\mathcal{C}} = 0.$$

A realization may therefore have positive occurrence-count loss even when no productive distinguishable output is retained. The passive closure determines how the enclosing occurrence is locally realized. It does not supply the causal direction of the occurrence.

#### 3.10.7 The Second Law

The second law of recursive counting can therefore be stated:

**When the opposed legs of a completed closure realize occurrence count with unequal directional efficiency, the resulting logarithmic occurrence-count loss at a representative peer boundary is read at the enclosing boundary as an increment in nondirectional background.**

Formally,

$$L_{\tau,n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right) = \delta_{\mathcal{C}}\Phi_{n + 1} \geq 0.$$

The primitive second-law relations are therefore

$$\Delta S_{n,a,\mathcal{C}} = 0,$$

and

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

These describe three boundary-specific count relations. The first describes exact closure of native possible multiplicity. The second describes the net occurrence-coordinate consequence of unequal directional efficiency between the two legs of the closure. The third describes the corresponding enclosing background increment.

The R²D law relates the enclosing occurrence to the geometry of its representative peer realization.

The second law states the complementary condition. Unequal directional occurrence-count efficiency is related to the enclosing background increment.

Nothing is destroyed. The primitive irreversible quantity is **occurrence-count loss**, defined by the difference in directional efficiency with which the two opposed legs of a closure realize the enclosing occurrence.


## 4.0 Principles

---
r2d_id: "canon-p1-4.0"
title: "Part I — 4.0 Principles"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 90
pdf_page_end: 100
semantic_amendment: "none"
review_status: "authoritative"
---
# 4.0 Principles

### 4.1 Principle -- The Hidden Structure

Science ordinarily uses mathematics to describe physical structure. Physics assigns numbers and units to objects and fields occupying coordinates such as space and time. Chemistry assigns numbers and units to chemical states and their occupancies. Biology assigns numbers and units to biological structures and their transformations. In these descriptions, the mathematics and the objects described by the mathematics are conceptually distinct.

R²D begins one level deeper.

Recursive multiplicity is not a physical object that mathematics describes. **Multiplicity is the primitive mathematical structure by which distinguishable objects, states, and relations are defined.** For macrostate $i$ at boundary $B_{n}$,

$$W_{n,i}$$

is not a measured property assigned to an independently existing state. The multiplicity defines the possible-count structure by which that state is distinguishable in the first place. Its logarithm,

$$S_{n,i} = \ln W_{n,i},$$

is an additive coordinate of that primitive mathematical structure.

Occurrence and occupancy are different. They are realized counts within the structure defined by multiplicity:

$$W \rightarrow \text{possible~structure},\nu \rightarrow \text{realized~occurrence},c \rightarrow \text{realized~occupancy}.$$

The R²D law therefore contains neither $W$ nor $S$ as an additional physical term. The law is already a relation **formed within recursive multiplicity structure**. Multiplicity defines the landscapes, the compatible possibilities, the distinctions, and the recursive relations within which the quantities appearing in the law have meaning.

In conventional scientific description, mathematics describes physical structure.

In R²D, mathematics is the physical structure itself.

Mathematics is therefore not merely the language used to describe the primitive R²D universe. **Recursive multiplicity is the primitive structure being realized.**

This is why multiplicity can remain hidden from the R²D law while structuring every term within it. Mathematics does not appear as another object inside the relations it defines. The R²D law describes realization within recursive multiplicity; it does not place recursive multiplicity beside its own realized quantities as one more physical variable.

**Recursive multiplicity is the hidden mathematical structure of R²D. Physical quantities are boundary-specific readings of its realization.**

### 4.2 Principle -- Boundary-Indexed Recursive Counting Precedes Spacetime Geometry

If recursive multiplicity is the primitive mathematical structure of R²D, then that structure cannot require a pre-existing spacetime in which to occur. Boundaries, multiplicities, occurrences, occupancies, and closures are defined as count relations before space or time is introduced.

The primitive structure within which occurrences become distinguishable is therefore not spacetime geometry. It is the recursive mathematics of nested, boundary-defined multiplicity landscapes.

Spacetime does not provide a prior linear grid onto which recursive counting is placed. Rather, R²D proposes that spatial and temporal coordinates are later readings of relations already defined within recursive counting.

Continuous mathematics is retained. Calculus provides a continuous representation of sufficiently resolved changes in underlying count relations. Its success does not require primitive count structure itself to be continuously divisible. A continuous coordinate can compress large numbers of unresolved discrete count relations into a readable mathematical description.

The same distinction explains the ubiquity of additive and exponential mathematics. When compatible possibilities jointly compose a larger realization, their multiplicities combine multiplicatively:

$W_{whole} = \prod_{\alpha}W_{\alpha}$.

Their logarithmic coordinates add:

$S_{whole} = \sum_{\alpha}S_{\alpha}$.

Exponentiation reverses this logarithmic reading:

$$W = e^{S}.$$

Thus, logarithms provide additive coordinates for multiplicative count structure, while exponentials recover the multiplicity represented by those coordinates. Neither operation creates the primitive structure. Both are mathematical readings of recursive count.

Physical units are introduced only later, when science assigns spatial, temporal, energetic, mechanical, or other domain-specific coordinates to these dimensionless count relations.

**Spacetime geometry is not the mathematical container of occurrences and occupancies. It is a physical reading of boundary-indexed recursive count. In the later program, spatial coordinates may read distinguishability relations while temporal and rate coordinates may read recurrence relations; neither mapping is assumed in Part I.**

### 4.3 Principle -- Possible Count Precedes Probability

Multiplicity is possible count. Probability is a normalized reading of possible or realized count. R²D possibility P is the logarithmic coordinate of compatible enclosing extension.

Probability is not primitive. It appears only when possible counts are normalized relative to a chosen total:

$p_{n,i} = \frac{W_{n,i}}{\sum_{j}W_{n,j}}$

or, for realized counts,

$p_{n,i}^{obs} = \frac{c_{n,i}}{\sum_{j}c_{n,j}}$.

Normalization does not create possibility. It converts a multiplicity relation into a fractional reading. Thus, possibility is what can be realized. Probability is how possibility can be read. R²D therefore treats probability as an epiphenomenological (EP) projection of boundary-relative multiplicity, not as a primitive cause of occurrence.

### 4.4 Principle -- External Asymmetry and Recursive Causal Agency

Biological systems make recursive causal structure especially readable. Protein structural asymmetry biases the occupancy changes that realize muscle contraction, but the direction of protein asymmetry depends on an enclosing nucleotide relation. Nucleotide asymmetry depends in turn on enclosing proton and metabolic relations. Metabolic asymmetry depends on still larger biological and environmental structures that ultimately include the capture of solar radiation.

At each step, expanding the boundary reveals an enclosing relation under which the subordinate asymmetry is realized.

The subordinate structure therefore answers **how** a change is realized. The enclosing structure answers **why one realization is favored over another**.

The two levels of causal agency are therefore

$$\Delta A_{n,i \rightarrow k} \longrightarrow \Delta G_{n,i \rightarrow k}$$

for the immediate cause of local occupancy bias, and

$$\left( \Delta P_{n,i \rightarrow k},{\Delta R}_{n,i \rightarrow k} \right) \longrightarrow \Delta A_{n,i \rightarrow k}$$

for the recursive origin of that local causal asymmetry.

R²D therefore inverts the usual direction assigned to causal agency. Subordinate occurrence is necessary to realize change, but subordinate occurrence does not determine why one realization is favored over another. Direction is supplied by the enclosing count relation and expressed locally as asymmetry.

**Realization occurs locally. The direction of realization is defined externally.**

Biology is not a special exception to this architecture. It provides a readable example of a primitive recursive relation in which local structure realizes change while the asymmetry directing that realization originates outside the local multiplicity landscape.

### 4.5 Principle -- The Limits of Recursive Counting

The recursively realized hierarchy is bounded below by the smallest distinguishable count boundary,

$$B_{\alpha},$$

and above by the largest presently realized count boundary,

$$B_{\omega}.$$

These two limits have fundamentally different meanings.

At the lower limit, $B_{\alpha}$ defines the primitive distinguishable recurrence from which recursive counting begins. No further subordinate count boundary is required to define this primitive distinction:

$$B_{\alpha - 1}$$

is not defined within the realized hierarchy. The primitive recurrence at $B_{\alpha}$ supplies the count unit from which occurrence can be recursively realized through larger boundaries.

Between the two limits,

$$\alpha < n < \omega,$$

A completed local count acquires enclosing occurrence meaning when the count boundary changes:

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}$$

and

$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$.

Thus, intermediate boundaries repeatedly realize the recursive sequence:

$$\text{macrostate~transition} \longrightarrow \text{closure} \longmapsto \text{enclosing~occurrence}.$$

The upper limit is different.

R²D postulates that $B_{\omega}$ is the largest presently realized boundary and that its macrostate path remains open. Let

$$\mathcal{O}_{\omega}:\quad\quad i_{\omega,0} \rightarrow i_{\omega,1} \rightarrow \cdots \rightarrow i_{\omega,m},$$

with

$$i_{\omega,m} \neq i_{\omega,0}.$$

The path has therefore not formed a completed closure:

$$\mathcal{O}_{\omega} \neq \mathcal{C}_{\omega}.$$

Consequently, there is no completed terminal closure available for recursive carry:

$$\mathcal{C}_{\omega}\not\longmapsto\mu_{\omega + 1}.$$

There is therefore no presently realized enclosing boundary $B_{\omega + 1}$ from which the direction of $B_{\omega}$ can be derived in the same way that local asymmetry is derived at nonterminal boundaries.

For every nonterminal boundary $B_{n}$, enclosing compatible multiplicity and productive constraint define the local asymmetry:

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k},$$

with

$${\Delta R}_{n,i \rightarrow k} = C_{n + 1}^{out}\lambda_{n,i \rightarrow k}.$$

The source of local direction can therefore always be followed upward through the recursive hierarchy. That regress terminates at $B_{\omega}$. R²D defines the unresolved asymmetry of the open terminal path as

$$A_{\omega,\mathcal{O}} \neq 0.$$

Unlike local asymmetry at a nonterminal boundary, $A_{\omega,\mathcal{O}}$ is not defined by a still larger realized possibility-retention relation. It is the unresolved asymmetry of terminal nonclosure. The lower and upper limits can therefore be summarized as

$$B_{\alpha} = \text{primitive~distinguishable~recurrence}$$

and

$$B_{\omega} = \text{largest~presently~realized~nonclosure}.$$

The hierarchy between them is

$$B_{\alpha} \longrightarrow \cdots \longrightarrow B_{n} \longrightarrow \cdots \longrightarrow B_{\omega}.$$

Local boundaries close within this hierarchy. The largest presently realized boundary does not.

The nonclosure of $B_{\omega}$ supplies the terminal causal orientation of the recursive hierarchy. Its consequence is expressed downward through the enclosing possibility and constraint relations of subordinate boundaries:

$$A_{\omega,\mathcal{O}} \longrightarrow \left( P_{\omega - 1},R_{\omega - 1} \right) \longrightarrow A_{\omega - 1} \longrightarrow \cdots \longrightarrow \left( P_{n},R_{n} \right) \longrightarrow A_{n}.$$

This does not mean that one unchanged asymmetry is transmitted from scale to scale. Each boundary has its own multiplicity landscape, possibility, constraint, and realized asymmetry. What persists through the hierarchy is the causal direction supplied by enclosing nonclosure.

The upper limit is therefore not a future boundary waiting to come into existence. $B_{\omega}$ is the **presently existing open boundary of recursive realization**. Subordinate boundaries realize repeated closure within that open count domain.

Thus, primitive recurrence begins at $B_{\alpha}$; recursive closure and carry occur between the limits; and global nonclosure remains at $B_{\omega}$. Local closure permits recursive realization, and global nonclosure supplies directionality.

The existence of $B_{\alpha}$ as the lower realized limit, the existence and openness of $B_{\omega}$ as the upper realized limit, and the identification of terminal nonclosure as the source of subordinate directionality are terminal postulates of R²D rather than consequences derived from the intermediate counting laws.

### 4.6 Principle -- Turbines

A turbine is a local closure through which an enclosing occurrence is realized. It does not generate the directional relation under which it operates. At boundary $B_{n}$ local closure occurs within the multiplicity landscape

$i \rightarrow k \rightarrow i$.

At every nonterminal boundary $B_{n}$, the enclosing boundary $B_{n + 1}$ defines the compatible multiplicity that provides directionality.

This is analogous to a wind turbine. A pressure difference does not arise because blades rotate. The external pressure relation defines a directional condition under which blade rotation can occur. The turbine supplies a closed local structure through which that enclosing relation can be realized. The blades return to the same position while the enclosing relation remains directionally organized.

The turbine is not a subordinate cause that drives the larger system.

It is a **local realization of an enclosing occurrence**.

### 4.7 Principle -- Whole-System Relations Precede Mechanistic Attribution

R²D arose from a recurring pattern in the history of science. Stable relations describing the behavior of a whole system have repeatedly been discovered prior to attempts at assigning mechanisms to subordinate objects.

Kepler described planetary motion through relations among complete orbits. The orbital relations were empirical properties of the larger system. Newton subsequently described those relations through forces acting between masses. The whole-system regularity came first; attempts at subordinate causal description came later (17).

Carnot described a heat engine as a cyclic system operating between unequal enclosing thermal conditions (18). The working system returned locally while the external difference driving the cycle remained. The primitive architecture was therefore already turbine-like. Subsequent mechanical theories, including those developed by Clausius (19), sought to explain thermal behavior through motions and interactions assigned to subordinate constituents.

A.V. Hill identified the same whole-system architecture in muscle (7). Force, shortening, and heat were related at the scale of the contracting muscle before a molecular mechanism for contraction had been specified. A.F. Huxley attributed these macroscopic relations to subordinate molecular power strokes (20) that have never been observed (29, 30).

The historical sequence is that whole-system relations are subsequently assigned subordinate mechanisms. R²D originated from asking whether these assignments identify the primitive direction of causality.

Our observations of muscle provided the immediate empirical motivation (9--12). Protein switching is required to realize contraction, but the contractile state is not defined by individual protein-switch trajectories. It is realized through the multiplicity of protein-switch states within the larger muscle landscape. The multiplicity structure determines the possible contractile states, while subordinate switching occurrences realize their occupancy.

This suggested the inversion developed formally in R²D. Subordinate occurrence realizes the change. The enclosing landscape defines its direction.

The mechanistic description is therefore not rejected. Newtonian force, molecular heat models, and molecular mechanisms can remain useful descriptions of how subordinate realizations occur. R²D questions the primitive causal source of the enclosing organization.

**R²D treats the whole-system relation not as incomplete phenomenology awaiting a subordinate cause, but as evidence that the causal relation itself may be defined at the enclosing boundary.**

### 4.8 Principle -- Determinism Within Scale and Coherence Across Scale

An enclosing occurrence organizes subordinate realization in two distinguishable ways.

First, it defines which realizations of multiple peer boundaries are jointly compatible. When this compatibility relation remains stable, the peer realizations remain correlated. R²D calls this **determinism**.

Second, the same recursively organized relation can be read from adjacent count boundaries even though the states and transitions through which it is read change classification. R²D calls this **coherence**.

Determinism is therefore a relation among peers within one scale.

Coherence is the persistence of a relation across a change in count boundary.

Both originate in enclosing organization.

**Determinism Within Scale**

Consider peer boundaries

$$\left\{ B_{n,a} \right\}_{a \in I_{n}}$$

contained by $B_{n}$. Let one enclosing occurrence be associated with the readable transition

$$\chi_{n + 1}:j \rightarrow k.$$

Boundary $B_{n + 1}$defines the compatible joint peer closures through which that occurrence can be locally realized:

$$\mathfrak{D}_{n + 1,\chi} = \left\{ \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}}:\left( \mathcal{C}_{n,a} \right)_{a \in I_{n}}\text{~}\text{is~jointly~compatible~with}\text{~}\chi_{n + 1}^{(r)} \right\}.$$

Thus,

$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}$.

The peer closures do not independently generate their correlation. Nor must they directly act on one another. Their correlation arises because the same enclosing occurrence defines which combinations of peer realizations are compatible with it.

For two peers $a$ and $b$,

$$\mathcal{C}_{n,a}\not\Longrightarrow\mathcal{C}_{n,b},$$

and

$$\mathcal{C}_{n,b}\not\Longrightarrow\mathcal{C}_{n,a}$$

need not hold as primitive causal relations. Instead,

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a},\mathcal{C}_{n,b} \right).$$

Their common organization is enclosing. When the enclosing compatibility relation remains stable across repeated occurrences,

$$\mathfrak{D}_{n + 1,\chi}^{(1)} = \mathfrak{D}_{n + 1,\chi}^{(2)} = \cdots,$$

the same classes of peer realizations remain jointly compatible. Persistent enclosing compatibility therefore produces persistent peer correlation.

R²D calls this **determinism**. Stable enclosing compatibility causes stable correlation among peer realization.

A deterministic law is the within-scale reading of this stable enclosing organization. It describes reproducible relations among peer outcomes without requiring those outcomes to be independently primitive causes of one another.

**Peer-Source Degeneracy**

The enclosing boundary need not distinguish which peer supplied a particular local realization. A transition readable at peer boundary $B_{n - 1}$,

$$i \rightarrow k,$$

is a microstate transition relative to $B_{n}$. The local peer label $a$ is readable at $B_{n - 1}$ but not $B_{n}$. Thus, multiple peer realizations can be equivalent relative to the same enclosing occurrence:

$$\mathcal{C}_{n,a} \sim_{n + 1}\mathcal{C}_{n,b}.$$

This source degeneracy is why a representative peer closure can appear in the R²D law. For equivalent peers,

$$\mathcal{C}_{n,g}\text{~}\text{is~one~representative~local~realization~of}\text{~}\chi_{n + 1}^{(r)}.$$

The representative peer does not stand in for the others because their effects have been averaged. It stands in for them because they occupy the same compatibility class relative to the enclosing occurrence.

**Coherence Across Scale**

Coherence concerns a different question. Suppose a relation among peer realizations is readable at scale $B_{n}$. Denote that relation by

$$\mathcal{R}_{n}\left( \mathcal{C}_{n,1},\ldots,\mathcal{C}_{n,m} \right).$$

From the peer boundaries, the constituent closures and their local paths may be readable. From , those same peer-source identities and internal paths are no longer readable as the same objects. Recursive carry reclassifies the completed local realizations according to the enclosing occurrence to which they belong:

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

This is not bottom-up causation. It is a change in boundary-relative count meaning. Although the constituent peer identities are replaced, a relation expressed through those realizations may remain well defined in the enclosing occurrence. If

$$\mathcal{R}_{n}\left( \mathcal{C}_{n,1},\ldots,\mathcal{C}_{n,m} \right)$$

has a corresponding enclosing reading

$$\mathcal{R}_{n + 1}\left( \chi_{n + 1}^{(r)} \right),$$

such that the relational organization is preserved under the change in count boundary, then R²D calls the relation **coherent**. Schematically,

$$\mathcal{R}_{n}\left( \mathcal{C}_{n,1},\ldots,\mathcal{C}_{n,m} \right)\overset{\kappa_{n}}{\mapsto}\mathcal{R}_{n + 1}\left( \chi_{n + 1}^{(r)} \right).$$

Coherence therefore does not mean that subordinate state identities survive the boundary. They do not. It means that a relation can remain readable in a new count form after the subordinate distinctions through which it was locally expressed cease to be individually readable. Thus, state identity is replaced while relationship organization can persist.

**Determinism and Coherence Are Different Readings of the Same Enclosing Organization**

Determinism and coherence are related because both arise from the same enclosing occurrence relation.

Determinism asks:

Given one stable enclosing compatibility relation, how are peer realizations related within the subordinate scale?

Coherence asks:

When the count boundary changes, does the relation organizing those realizations remain represented after their local identities are replaced?

Thus, determinism is stable correlation among peer realizations whereas coherence is preservation of relational organization across recursive reclassification. The causal architecture underlying both is

$$\text{enclosing~occurrence} \Longrightarrow \text{compatible~peer~realization}.$$

Determinism is the within-scale consequence of that compatibility. Coherence is its across-boundary persistence under a change in count meaning. Neither requires subordinate objects to possess independent primitive causal agency.

R²D therefore distinguishes three relations:

$$\begin{aligned}
\text{causal~organization:}\quad\quad & \chi_{n + 1}^{(r)} \Longrightarrow \left\{ \mathcal{C}_{n,a} \right\}_{compatible}, \\
\text{deterministic~reading:}\quad\quad & \mathcal{C}_{n,a} \leftrightarrow \mathcal{C}_{n,b}, \\
\text{coherent~reading:}\quad\quad & \mathcal{R}_{n}\overset{\kappa_{n}}{\mapsto}\mathcal{R}_{n + 1}.
\end{aligned}$$

The first is the enclosing causal relation. The second is its stable correlation among peers. The third is preservation of relational organization when the boundary changes.

**Determinism is the horizontal reading of enclosing organization. Coherence is its recursive reading across scale.**


## 5.0 Readability Limits and Epiphenomenological (EP) Projection

---
r2d_id: "canon-p1-5.0"
title: "Part I — 5.0 Readability Limits and EP Projection"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 101
pdf_page_end: 108
semantic_amendment: "none"
review_status: "authoritative"
---
# 5.0 Readability Limits and Epiphenomenological (EP) Projection

Two distinct phenomena occur repeatedly throughout recursive scientific description:

**Readability limits** and **epiphenomenological (EP) projection**.

A readability limit arises because what can be directly resolved depends on the boundary from which a distinction is read. A transition readable as a macrostate transition at one boundary becomes an unreadable microstate transition relative to the enclosing boundary. This is a limitation imposed by recursive state definition itself.

EP projection is an interpretive step. It occurs when an enclosing count relation is unreadable or omitted and causal agency is reassigned to the readable consequences that remain.

Thus, a readability limit is a limitation of boundary-relative observation whereas an EP projection is the reassignment of primitive causality after omission of an enclosing relation. Readability limits are unavoidable consequences of recursive replacement. They are not errors.

Omission of an unreadable relation is not necessarily an error. A local description may remain useful and predictive without explicitly representing the enclosing boundary. EP projections become errors when the resulting readable description is promoted from a boundary-specific representation to the primitive causal ontology.

### 5.1 Boundary-Indexed Readability

What is readable depends on the boundary from which a distinction is counted. R²D therefore does not assign an absolute microstate or macrostate identity to a transition. The same realized change has different count meaning when read from adjacent boundaries. Consider a peer subordinate boundary

$$B_{n - 1,a}.$$

A transition

$$i \rightarrow k$$

may be directly readable there as a macrostate transition. Relative to the enclosing boundary , the same subordinate change is a microstate transition:

$$\text{macrostate~transition~at~}B_{n - 1,a} = \text{microstate~transition~relative~to~}B_{n}.$$

The transition remains formally definable relative to , but its peer-source identity $a$ need not remain distinguishable there. Thus, a microstate transition is formally definable but not individually readable from the boundary relative to which it is a microstate transition.

To read the transition directly, the count boundary must change to the subordinate boundary where that same change has macrostate meaning. Therefore,

$$\text{resolution} \rightarrow \text{change~of~count~boundary} \rightarrow \text{change~of~state~classification}.$$

This is the primitive R²D observer relation.

Observation does not reveal an unchanged microscopic object while preserving its classification. Resolution changes the count boundary, and therefore changes the count identity under which the realized relation is readable.

#### 5.1.1 Readability in the Subordinate Direction

Suppose two formal microstates at $B_{n}$differ through a transition at peer $a$:

$$\mu_{n} \rightarrow \mu_{n}'.$$

At the peer boundary $B_{n - 1,a}$, the subordinate change may be readable as

$$u \rightarrow v.$$

At , $B_{n}$ the peer-resolved transition is not necessarily individually readable. What may remain readable is its macrostate consequence.

If

$$\pi_{n}\left( \mu_{n} \right) = i$$

and

$$\pi_{n}\left( \mu_{n}' \right) = k,$$

then, when

$$i \neq k,$$

the enclosing boundary reads

$$i \rightarrow k.$$

Thus,

$$\mu_{n} \rightarrow \mu_{n}'\quad\overset{\pi_{n}}{\rightarrow}\quad i \rightarrow k.$$

The classification arrow is not causal. It states how the realized change is classified at $B_{n}$. The boundary can therefore read the macrostate consequence without resolving the particular peer transition through which that consequence was locally realized.

This is a readability limit, not a failure of the subordinate transition to exist relative to its own boundary.

#### 5.1.2 Readability in the Enclosing Direction

A complementary limit occurs when a completed local realization is read from the enclosing boundary. Consider an enclosing occurrence

$$\chi_{n + 1}^{(r)}$$

and one compatible representative peer closure

$$\mathcal{C}_{n,a}.$$

The causal relation is

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}.$$

The enclosing occurrence defines the compatible local closure through which it is realized. Relative to $B_{n}$, the peer closure may be readable as a complete macrostate path:

$$\mathcal{C}_{n,a}:i \rightarrow k \rightarrow i.$$

The peer-source identity and internal macrostate path do not remain readable as the same objects. The completed realization is instead classified according to the enclosing occurrence to which it belongs. Recursive carry denotes this change in count meaning:

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

This is not the causal reverse of

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}.$$

The two arrows have different meanings:

$$\begin{aligned}
\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a} & \quad\quad\text{causal~realization}, \\
\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)} & \quad\quad\text{recursive~reclassification}.
\end{aligned}$$

Thus, a closure below does not causally become an occurrence above. More precisely, a peer closure is the subordinate reading of an enclosing occurrence. Recursive carry changes how that completed realization is counted when the boundary changes.

#### 5.1.3 Recursive Replacement Is Not Ordinary Coarse Graining

These two readability relations distinguish recursive replacement from ordinary coarse graining. In ordinary coarse graining, an underlying detailed state is generally assumed to retain its identity while the observer elects not to resolve it.

R²D makes a stronger claim. Changing the boundary changes the count domain itself. A macrostate transition at one boundary acquires microstate meaning relative to the enclosing boundary:

$$\text{macrostate~transition~at~}B_{n - 1,a} = \text{microstate~transition~relative~to~}B_{n}.$$

A completed peer closure likewise does not remain the same macrostate path at the enclosing boundary:

$$\mathcal{C}_{n,a} \not\equiv \chi_{n + 1}^{(r)}.$$

The two may remain recursively related without retaining the same state or transition identity. Thus, state identity may be replaced while the recursively organized relation remains consequential.

What becomes unreadable has not necessarily been destroyed. It has ceased to possess the same count meaning from the new boundary.

#### 5.1.4 Readability Limits Are Not EP Projection Errors

A readability limit follows directly from boundary-relative statehood. An EP projection requires an additional interpretive step. If a subordinate transition is not individually readable from $B_{n}$, that is simply a readability limit. If an enclosing relation is not readable from $B_{n}$, that is also simply a readability limit.

Neither is, by itself, an error. The error occurs only when the remaining readable consequence is promoted to the primitive cause of the relation from which it arises.

Thus, a readability limit is not an EP projection.

A readability limit answers:

**What can be directly resolved from this boundary?**

An EP projection answers a different question incorrectly:

**What is assumed to be the primitive cause after the unreadable enclosing relation has been omitted?**

This distinction leads directly to the omission problem developed in Section 5.2.

### 5.2 Omission of the Enclosing Count Relation

At every nonterminal boundary, local realization is directed by an enclosing count relation. Possibility is derived from enclosing compatible multiplicity, productive constraint determines retention, and their difference defines local asymmetry:

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k}.$$

That asymmetry biases occupancy through

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

The local observer can therefore read the occupancy relation even when the enclosing count relation from which its asymmetry originates is unresolved or excluded from the description.

Likewise, a stable enclosing compatibility relation produces persistent correlations among peer subordinate realizations. When the enclosing relation remains stable, these subordinate correlations remain stable and are read locally as deterministic laws.

The causal architecture is therefore

$$\text{enclosing~compatibility~and~constraint} \longrightarrow \text{local~asymmetry~and~deterministic~correlation} \longrightarrow \text{subordinate~realization}.$$

If the enclosing relation is omitted, the readable consequences remain. The observer sees correlated subordinate microstate consequences and attributes interaction to them. What is no longer represented is the enclosing relation that gives local regularities their common causal orientation.

This omission does not itself constitute an EP projection error. It may be a useful boundary-specific description. EP projection errors occur when the omitted causal relation is replaced by primitive causal agency assigned to its readable consequences.

### 5.3 Epiphenomenological (EP) Projection

R²D uses **epiphenomenological projection** to describe the promotion of a readable consequence of recursive organization into the primitive cause of that organization. The primitive recursive relation is schematically

$$\mathcal{L}_{n + 1} \longrightarrow P_{n}\overset{- R_{n}}{\rightarrow}A_{n} \longrightarrow G_{n} \longrightarrow \mathcal{C}_{n} \longmapsto \mu_{n + 1}.$$

When the enclosing landscape is omitted, only the locally readable portion remains. Causal explanation is then reconstructed from those readable quantities.

R²D identifies three successive forms of this reassignment.

#### 5.3.1 EP Projection I --- Primitive Object Error

A subordinate state can be readable at $B_{n - 1}$ while its identity becomes unreadable relative to $B_{n}$.

At $B_{n}$, the distinguishable macrostate is defined by the multiplicity of compatible formal microstates:

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|.$$

The subordinate identities contributing to that multiplicity do not remain primitive state identities at the enclosing boundary. Primitive-object projection occurs when a subordinate identity readable at one boundary is retained as an independently existing primitive object in the causal description of the enclosing boundary.

Schematically,

$$\text{subordinate~readable~identity} \longrightarrow \text{recursive~replacement} \longrightarrow W_{n,i}$$

is replaced by the EP projection

$$\text{subordinate~readable~identity} \longrightarrow \text{primitive~object}.$$

Examples of such projected objects include particles, molecules, point masses, cells, organisms, or agents, depending on the scientific domain.

The error is not that these objects are unreadable or scientifically useless. They are readable at the boundaries at which they are defined. The EP error is treating their boundary-specific identity as primitive across the recursive hierarchy after the enclosing multiplicity relation has been omitted.

#### 5.3.2 EP Projection II --- Primitive Interaction Error

Once subordinate objects are treated as independently primitive, their persistent coordination requires a local causal explanation. Stable enclosing compatibility can produce persistent correlations among subordinate realizations:

$$\text{stable~enclosing~compatibility} \longrightarrow \text{stable~subordinate~correlation}.$$

After the enclosing relation is omitted, the same correlation is instead represented as direct causal interaction:

$$x_{1} \longrightarrow x_{2.}$$

Primitive-interaction projection therefore reverses the causal interpretation:

$$\text{common~enclosing~relation} \longrightarrow \text{correlated~subordinate~realization}$$

becomes the EP projection:

$x_{1} \longrightarrow x_{2}$.

The interaction itself is not the error. A domain-specific deterministic law may describe the readable correlation with extraordinary accuracy.

The EP projection error is assigning primitive causal agency to that interaction after the enclosing relation responsible for the common organization has disappeared from the description.

Depending on the domain, such descriptions include gravitational interaction between masses, electromagnetic interaction, mass-action relations, and interpretations of nonlocal correlation as direct communication between independently primitive objects.

#### 5.3.3 EP Projection III --- Primitive Organizing-Structure Error

Once independently primitive objects and their interactions have been assumed, persistent organization may require an additional mathematical structure through which those interactions are represented.

Schematically,

$$x_{1} \longrightarrow \mathcal{M} \longrightarrow x_{2.}$$

The quantity $\mathcal{M}$ may be represented in different domains as a force, potential, field, geometric relation, state function, or other organizing mathematical structure. These representations can preserve the readable relations with extraordinary precision. R²D does not identify the mathematics as the error. The EP projection occurs when the mathematical structure required to reproduce the readable consequence of an omitted enclosing relation is itself promoted to primitive causal ontology.

The causal sequence has then moved through three stages:

$$\text{enclosing~recursive~structure} \longrightarrow \text{primitive~objects} \longrightarrow \text{primitive~interactions} \longrightarrow \text{primitive~organizing~structures}.$$

R²D proposes that forces, fields, spacetime geometry, wavefunctions, and related domain-specific mathematical structures should therefore be considered possible readings of recursive count relations rather than assumed to be primitive structures prior to counting.

### 5.4 Why EP Projections Remain Predictive

EP projection does not require the projected theory to make incorrect predictions. If an enclosing compatibility relation is stable, its subordinate consequences are also stable:

$$\text{stable~enclosing~relation} \longrightarrow \text{stable~subordinate~correlation}.$$

A theory constructed entirely from the subordinate correlation can therefore reproduce the observable relation even after its enclosing causal source has been omitted. The projected theory may accurately determine how readable quantities vary together. What changes is the assignment of primitive causal agency.

This is why predictive success alone cannot distinguish between the recursive relation proposed by R²D and an EP description constructed from its readable consequences.

R²D therefore distinguishes three questions:

**What is readable?** This is determined by the count boundary.

**What mathematical relation describes what is readable?** This is the domain-specific scientific theory.

**What supplies the causal organization of that relation?** This is the ontological question addressed by recursive counting.

The distinction can be summarized as

$$\text{readability~limit} \neq \text{model~approximation} \neq \text{EP~projection}.$$

A readability limit determines what cannot be directly resolved from a boundary. A model approximation describes the readable consequence without necessarily making an ontological claim. An EP projection error occurs when that readable consequence is assigned the primitive causal role of the omitted recursive structure.


## 6.0 Two Horizons

---
r2d_id: "canon-p1-6.0"
title: "Part I — 6.0 Two Horizons"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 109
pdf_page_end: 111
semantic_amendment: "none"
review_status: "authoritative"
---
# 6.0 Two Horizons

### 6.1 Principle --- Turbine Readability

A recursively realized turbine has two adjacent-boundary readings. At $B_{n}$, it is readable as a distinguishable local closure,

$$\mathcal{C}_{n,a}.$$

At $B_{n + 1}$, the same recursively organized realization is readable as an enclosing occurrence,

$$\chi_{n + 1}.$$The causal relation remains

$$\chi_{n + 1} \Rightarrow \mathcal{C}_{n,a},$$

while recursive carry gives the complementary boundary-relative read

$$\mathcal{C}_{n,a} \mapsto \chi_{n + 1}.$$

Joint readability requires that both the distinguishable local closure and its enclosing recurrence relation remain resolvable. A readability horizon occurs when one of these two boundary-specific readings ceases to be resolvable while the other remains readable. The underlying recursively organized realization need not cease to exist; what fails is joint readability of its two boundary-specific expressions.

### 6.2 -- Horizons

The two horizon coordinates are the two readable aspects of recursive turbine realization.

Recursive comparison across boundaries contains two independent scaling relations. The first is distinguishability. For a readable transition at boundary $B_{j}$, let

$$\lambda_{j}$$

denote its readable distinguishable interval. The second is recurrence. For adjacent boundaries, Section 3.7 defines

$$\rho_{j + 1 \mid j} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{j + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{j} \right)},$$

the number of enclosing recurrences per local closure recurrence within one common recurrence-comparison domain.

Neither quantity is yet physical space or physical time. $\lambda$ is a boundary-defined distinguishability count. $\rho$ is a dimensionless recurrence ratio. A later physical theory may assign spatial and temporal or rate coordinates to these relations, but Part I does not.

For a reference boundary $B_{n}$ and larger boundary $B_{N}$, define accumulated distinguishability scaling

$$\Lambda_{N \mid n} = \ln\left( \frac{\left| \lambda_{N} \right|}{\left| \lambda_{n} \right|} \right),$$

and accumulated recurrence scaling

$$\Gamma_{N \mid n} = \sum_{j = n}^{N - 1}\ln\rho_{j + 1 \mid j}$$

When one recurrence-comparison domain jointly counts every boundary in the chain, the product of adjacent recurrence ratios telescopes:

$$\prod_{j = n}^{N - 1}\rho_{j + 1 \mid j} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{N} \right)}{N_{\mathcal{D}_{R}}\left( \chi_{n} \right)},$$

so

$$\Gamma_{N \mid n} = \ln\left( \frac{N_{\mathcal{D}_{R}}\left( \chi_{N} \right)}{N_{\mathcal{D}_{R}}\left( \chi_{n} \right)} \right).$$

Their accumulated imbalance is

$$H_{N \mid n} = \Lambda_{N \mid n} - \Gamma_{N \mid n}.$$

Equivalently,

$$H_{N \mid n} = \ln\left\lbrack \frac{\left| \lambda_{N} \right|/\left| \lambda_{n} \right|}{\prod_{j = n}^{N - 1}\rho_{j + 1 \mid j}} \right\rbrack.$$

The quantity $H_{N \mid n}$ is not a third primitive coordinate. It is the relative accumulated scaling of distinguishability and recurrence. A large positive value means that distinguishability has increased relative to recurrence:

$$H_{N \mid n} \rightarrow + \infty.$$

A large negative value means that recurrence has increased relative to distinguishability:

$$H_{N \mid n} \rightarrow - \infty.$$

Relative dominance alone does not define a readability horizon. A horizon occurs only when the accumulated scaling is accompanied by loss of resolution of one relation while the other remains readable. Thus,

$$H_{N \mid n} \rightarrow + \infty$$

defines the **distinguishability-dominant limit**. When distinguishability remains readable while recursive recurrence becomes unresolved, this is the distinguishability horizon. Conversely,

$$H_{N \mid n} \rightarrow - \infty$$

defines the **recurrence-dominant limit**. When recurrence remains readable while the associated distinguishability becomes unresolved, this is the recurrence horizon. Between these limits, if both relations remain readable at finite relative geometry, closure remains jointly readable.

Thus, the three readability regimes are

$$\begin{matrix}
H \rightarrow + \infty & :\quad\text{distinguishability-dominant readability}, \\
H \rightarrow - \infty & :\quad\text{recurrence-dominant readability}, \\
|H| < \infty & :\quad\text{jointly readable closure when both relations remain resolved}.
\end{matrix}$$

Occurrence statistics remain separate. The logarithmic state-occurrence coordinate

$$\tau_{n,i} = \ln \nu_{n,i}$$

and the opposed-leg occurrence-count loss

$$L_{\tau,n,a,\mathcal{C}} = - \ln \eta_{n,a,\mathcal{C}} \geq 0$$

describe realization within a boundary. They do not define the across-boundary recurrence scaling $\Gamma$.

The Second Law postulates

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

Background is nondirectional relative to the boundary at which it is background:

$$\Delta\Phi_{n,i \rightarrow k} = 0.$$

Therefore, occurrence nonreciprocity and background do not add a third horizon coordinate. They describe whether a recursively organized closure is realized reciprocally, whereas $H_{N \mid n}$ describes how distinguishability and recurrence scale across boundaries.

R²D therefore identifies two, not three, opposite readability horizons. It proposes that the distinguishability-dominant, recurrence-dominant, and jointly readable regimes are primitive count structures later mapped onto different physical descriptions. Part I does not derive those physical theories. It establishes the boundary-indexed count relations that any such mappings must preserve.


## 7.0 Discussion

---
r2d_id: "canon-p1-7.0"
title: "Part I — 7.0 Discussion"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 112
pdf_page_end: 121
semantic_amendment: "2026-09-25-causal-architecture-and-structural-universality-synchronization"
review_status: "authoritative"
---
# 7.0 Discussion

R²D begins with counting, but its most consequential result concerns causality.

Classical statistical mechanics contains two ideas that have usually been allowed to coexist without being sharply separated. The first is combinatorial: different macrostates possess different numbers of possible microstate realizations. The second is mechanistic: microscopic transitions are assigned causal agency for the evolution of the system through that macroscopic landscape. R²D separates these two statements. The distinction is elementary once exposed.

At a fixed count boundary, multiplicity is defined by the cardinality of the compatible realizations assigned to each readable macrostate. A subordinate transition can change which of those possibilities is realized. It cannot change that cardinality without changing the boundary-defined state structure itself. Subordinate realization therefore cannot be the source of the native multiplicity landscape it realizes.

R²D then establishes a second general result. The complete directional count relation between local alternatives depends not only on their native multiplicities but also on their compatible enclosing extension. Those enclosing extension multiplicities can change while the local classification and native multiplicities remain fixed. Consequently, enclosing compatibility can create directional support where none exists, cancel native support, or reverse its sign without changing the native local landscape.

Appendix B gives these abstract results a finite exact construction. The ten-coin landscape makes multiplicity invariance under realization obvious. The recursive ten-by-ten construction makes equally explicit that the next boundary counts ten already-defined landscapes rather than restoring one hundred subordinate coin identities as primitive objects. The familiar hundred-coin binomial then emerges as the closed-form count consequence of recursive composition.

This is the conceptual break of R²D.

It does not invalidate the mathematics of statistical mechanics. It challenges the conventional assignment of causal agency within that mathematics. The microscopic transition is necessary for realization, but it cannot be the source of a multiplicity structure that exists independently of the transition or of an enclosing bias that can be changed without changing the local landscape.

That conclusion would be important even if it remained a purely combinatorial argument. It does not. Statistical mechanics provides extraordinary empirical evidence for the complementary half of the argument. Local occupancies respond reproducibly to enclosing conditions. Change temperature, an applied field, chemical potential, pressure, mechanical constraint, or related environmental conditions, and local state distributions change accordingly. The Boltzmann-Gibbs framework has described this enclosing control of local realization with extraordinary success.

Taken together, these two results establish the causal ordering implied by the statistical state architecture. The local transition realizes the change. The enclosing relation organizes which change is favored. What science commonly identifies as the microscopic cause is therefore the local realization of an enclosing organization whose state and directional relations are logically prior to that realization. This causal ordering is not added to R²D as a separate assumption; statistical mechanics supplies its empirical physical realization.

### 7.1 The Causal Problem Hidden Inside Statistical Mechanics

The success of statistical mechanics can make its underlying causal assumption difficult to see. A system evolves from one macroscopic condition toward another. At the microscopic level, particles collide, molecules change state, spins reorient, or other subordinate transitions occur. Because these events are necessary for the macroscopic change, it is natural to assign them causal agency for that change.

But statistical mechanics simultaneously says that the macroscopic states through which the system evolves possess unequal multiplicities. These two statements concern different things. Multiplicity describes possible structure. Microscopic dynamics describe realization within that structure.

The possible structure does not have to be produced anew every time the system realizes it. Indeed, it cannot be. The number of ways ten coins can realize five heads and five tails is fixed by the ten-coin count domain. It is true before the coins are tossed, while they are tossed, and after a particular arrangement has been realized.

This conclusion is not specific to coins. Whenever

$W_{n,i} = \left|\pi_{n}^{-1}(i)\right|$,

realization occurs within a multiplicity structure whose definition is logically prior to the particular realization. Subordinate dynamics can select among formally possible realizations, but they cannot be the primitive source of the classification relation that determines how many such realizations belong to each macrostate.

The conventional bottom-up interpretation therefore encounters a formal problem before any physical mechanism is specified: the proposed microscopic cause acquires its microstate identity only relative to the enclosing boundary whose state structure it is subsequently invoked to explain.

### 7.2 The Coin Construction Makes the General Theorem Explicit

The coin example in Appendix B is not required to prove the enclosing dependence. Its value is that every count can be written explicitly and no physical mechanism can obscure the logic. Begin with ten coins. Before any coin moves, the ten-coin boundary already defines a landscape of possible ensemble states. Some ensemble states have one realization. Others have tens or hundreds. The multiplicity belongs to the ensemble classification, not to the trajectory of any individual coin. Now toss the coins.

Individual heads-to-tails and tails-to-heads transitions occur. These transitions are necessary for the ensemble occupancy to change. But they do not alter the native multiplicity landscape. They realize it. This alone separates the source of possible structure from the events through which that structure is occupied.

Embedding the ten coins inside a hundred-coin boundary makes the distinction stronger. The same ten-coin state can participate in different numbers of compatible hundred-coin realizations depending on the enclosing state. Changing only that enclosing condition can increase, eliminate, or reverse the directional support of a local transition even though nothing about the native ten-coin multiplicity has changed.

The local transition therefore cannot contain the full causal relation governing its own directional realization. The relevant organization exists at the enclosing boundary. This is not a statistical approximation. It is a property of the combinatorics.

The coins therefore do more than show that a subsystem can depend on its surroundings. They show why assigning primitive agency to the subordinate transitions is insufficient. Those transitions do not create either the landscape they realize or the enclosing compatibility that can change the direction of that realization.

### 7.3 Statistical Mechanics Becomes Empirical Validation or R²D

If the coin argument ended there, one could reasonably ask whether this distinction mattered in nature. Statistical mechanics answers that question. Local state occupancies are experimentally controlled by enclosing conditions. Thermal populations change when temperature changes. Field-sensitive states change when an applied field changes. Chemical distributions respond to chemical potential and composition. Mechanical systems respond to imposed pressure, tension, load, and related constraints.

These observations are not marginal features of statistical physics. They constitute a large part of its experimental foundation. The canonical statistical-mechanical construction contains the same architecture mathematically. A local state is weighted according to the number of realizations of the larger system that remain compatible with that state. The relative realization of the part therefore depends on the possible structure of the whole.

R²D therefore arrives at the enclosing-to-local architecture twice, by independent routes. The formal framework derives it from boundary-defined counting. Statistical mechanics demonstrates experimentally that nature realizes it: manipulating enclosing conditions changes local occupancy. The coincidence is stronger than correspondence. A primitive mathematical architecture derived without energy, temperature, probability, field, or matter is already instantiated in one of the most empirically successful frameworks in science.

Within statistical mechanics, the existence of enclosing-to-local organization is therefore not conjectural. Because the macrostate–microstate relation is scale-relative rather than tied to a preferred microscopic object, R²D treats the primitive statistical architecture as structurally universal wherever scientific states admit that relation. What remains open is not a repeated proof of the same statistical grammar at each physical scale, but the domain-specific mapping by which different physical theories read it.

### 7.4 Formal Ontology, Formal Directionality, and Empirical Realization

The causal inversion rests on three independent levels of argument.

First, the definitions of boundary, formal microstate, macrostate, and multiplicity establish an enclosing-defined ontology. A microstate has microstate meaning only relative to the boundary that defines the compatible realization domain and its classification. Subordinate realization therefore cannot primitively construct the state ontology required for it to possess microstate identity.

Second, the enclosing-compatibility theorem establishes directional control. With the native local multiplicity landscape held fixed, compatible enclosing extension can create, cancel, or reverse local directional support.

Third, statistical mechanics establishes that this architecture is physically realized. Changing enclosing conditions changes local occupancy with extraordinary reproducibility.

These are not three versions of the same argument. The first establishes state ontology. The second establishes directional organization. The third establishes physical realization.

Together they leave very little causal work for the conventional bottom-up interpretation to perform. Subordinate dynamics remain necessary to realize the change, but they neither define the multiplicity structure in which that change has meaning nor determine the enclosing relation that organizes its direction.

But R²D does more than criticize bottom-up causality. It supplies its replacement: **the whole defines compatible state structure; enclosing compatibility organizes direction; subordinate dynamics supply realization; recursive carry supplies the boundary-relative readout of completed realization.**

### 7.5 Mechanism Describes Realization, Not Causal Origin

This distinction changes the status of mechanism without diminishing its scientific value. A mechanism can describe, in extraordinary detail, how a physical transformation occurs. It can identify molecular rearrangements, collisions, conformational changes, forces, reaction pathways, or other subordinate events required for realization. R²D does not deny any of these.

It questions the inference that identifying the mechanism automatically identifies the primitive source of direction. The distinction is familiar in another form. A turbine can be studied by following every blade. The blade motions are indispensable to the operation of the turbine. But the blade trajectory does not create the pressure difference under which the turbine turns.

Likewise, a molecular transition can be indispensable to a thermodynamic change without generating the enclosing relation that favors that transition. Mechanism therefore answers how. Enclosing organization answers why this realization rather than its alternative is favored. The two questions need not have the same answer.

### 7.6 Whole-System Laws Are More Than Phenomenology

This causal distinction changes the familiar hierarchy between phenomenology and mechanism. Science has repeatedly discovered stable whole-system relations before assigning subordinate mechanisms to them. Kepler described orbital regularities before Newtonian dynamics. Carnot described the organization of heat engines before a molecular theory of heat. Hill described reproducible relations among force, shortening, and heat before molecular mechanisms of contraction were available.

Such relations are commonly regarded as phenomenological: useful descriptions awaiting a deeper explanation in terms of smaller objects. R²D raises the opposite possibility. A whole-system law describes the organizing boundary more directly than the later subordinate mechanism describes it. The subordinate mechanism can then be real and predictive while occupying a different causal role. It explains how the whole-system relation is locally realized rather than replacing that relation as its primitive cause.

This does not make every phenomenological law fundamental. It removes the assumption that smaller automatically means causally deeper.

### 7.7 Resolution Does Not Reveal the Same Cause at Finer Detail

Boundary-relative statehood reinforces this causal argument. Return to the ten coins. From the ten-coin boundary, the readable change is a change in ensemble state. Individual coin transitions have microstate meaning relative to that boundary. To observe one coin directly, the observer must change to the boundary at which heads and tails are readable macrostates. But the causal question has then changed.

At the ten-coin boundary, the question is why the ensemble realizes one collective state rather than another. At the one-coin boundary, the question is why that coin realizes heads rather than tails. Increasing resolution has not uncovered the same causal object in greater detail. It has changed the count domain and therefore changed the identity of the state about which the causal question is being asked.

This makes the usual reductionist appeal to greater observational resolution less decisive than it appears. A subordinate transition can be directly observed. But direct observation of that transition occurs at the boundary where it is a macrostate transition, not at the enclosing boundary where it has microstate meaning. Resolution therefore changes both what is readable and what causal question is being posed.

### 7.8 Recursive Carry Does Not Restore Bottom-Up Causation

Completed local realizations remain consequential when the boundary changes. R²D calls this recursive carry. The fact that a local realization acquires enclosing count meaning can easily be mistaken for bottom-up construction. A local process closes, becomes consequential at a larger boundary, and may be represented there in a new form.

But mathematical direction is not causal direction. Recursive carry states how the meaning of a completed realization changes when it is counted from another boundary. It does not say that subordinate closure creates the enclosing occurrence.

This allows the architecture to contain two apparently opposite arrows without contradiction. Causal organization is enclosing-to-local. Recursive readout is local-to-enclosing. The first determines which local realizations belong to the enclosing occurrence. The second describes what those completed realizations mean after the count boundary changes. R²D therefore separates causal priority from the direction in which count meaning is recursively reclassified.

### 7.9 Probability Conceals the Count Architecture It Accurately Describes

Probability is one of the most successful scientific representations of the structure described here. Its success is not questioned. Its logical position is. A probability distribution begins after a space of possibilities and a normalization rule have been specified. R²D begins one step earlier, with the counts being normalized.

This distinction becomes important in the coin construction because the directional effect of the enclosing boundary resides in the number of compatible enclosing realizations. Normalization can represent the resulting relative weighting perfectly while obscuring where that weighting came from. The familiar Boltzmann factor is therefore not rejected by R²D. It is evidence.

Its extraordinary empirical success demonstrates that local occupancy follows enclosing conditions. R²D formally exposes the count architecture beneath that dependence and asks whether probability has often been mistaken for the primitive source of a relation whose deeper structure is multiplicity and compatibility. Possibility precedes probability because there must be something to normalize before normalization can occur.

### 7.10 Irreversibility Does Not Create Its Own Direction

The same separation between structure and realization changes the interpretation of irreversibility. A local path can return to its starting state while the realization of the two opposed directions is nonreciprocal. Structural closure and reciprocal occurrence are different conditions.

R²D therefore does not require possible states to be destroyed in order to obtain irreversible behavior. Nor does it require the local irreversible process to create the arrow under which it operates. Direction is already supplied by the enclosing relation. Irreversibility describes how that directed relation is realized around closure. This distinguishes the source of the arrow from one of its local consequences.

The Second Law of R²D then asks how nonreciprocal local realization is read after the boundary changes. Its proposed background correspondence is an additional realization postulate, not a restatement of the combinatorial argument. That distinction is important because the empirical support for enclosing control of occupancy does not by itself establish every part of the R²D Second Law. The theory retains separate burdens of proof.

### 7.11 Local Irreversibility and Terminal Direction Are Different Problems

If every nonterminal directional relation is defined through an enclosing relation, the causal question can always be asked again at a larger boundary. R²D therefore produces an explanatory regress.

Part I terminates that regress with an explicit postulate rather than disguising it as a mathematical consequence. The largest presently realized boundary is taken to remain open, and its nonclosure supplies the unresolved orientation of the hierarchy. This is a substantially stronger claim than the combinatorics of the coins or the experimentally established structure of statistical mechanics. It should remain so identified.

The established result is that local realization can be organized by enclosing conditions. The R²D terminal postulate says that recursively following that organization ultimately reaches a presently open boundary whose nonclosure supplies the causal orientation of the realized hierarchy. The first has extensive empirical precedent. The second remains a fundamental conjecture.

### 7.12 Determinism and Coherence Become Forms of Enclosing Organization

The same architecture provides a different view of correlation. If a stable enclosing relation repeatedly permits the same combinations of subordinate realizations, the resulting peer relations will remain reproducible. From within the subordinate scale, this can appear as deterministic law. The peers need not independently organize one another. Their correlation can reflect their common compatibility with the same enclosing relation.

Coherence concerns a different persistence. A relation may survive a change in count boundary even though the identities through which it was expressed locally no longer survive as the same states.

Determinism therefore concerns stable relation among peers. Coherence concerns preservation of relation across recursive replacement. Both are ways in which organization can remain readable even when primitive causal agency is not assigned to the subordinate objects carrying the local realization.

Later parts must determine whether classical determinism and quantum coherence can actually be reconstructed from these primitive distinctions. Part I only establishes the distinction they would have to satisfy.

### 7.13 Readability May Produce Different Scientific Ontologies

R²D also changes the interpretation of apparently incompatible physical descriptions. A recursively realized relation can contain distinguishable structure and occurrence structure that do not remain equally readable across boundaries. At one extreme, distinguishability remains readable while recurrence becomes unresolved. At the other, recurrence remains readable while distinguishability becomes unresolved. Between these limits, both can remain jointly accessible.

Part I proposes that different physical theories may arise as descriptions appropriate to these different readability regimes. The claim is not yet that gravity, quantum mechanics, and thermodynamics have been derived. The important implication is more general.

Different scientific ontologies need not correspond to different primitive substances. They may arise because different portions of one recursive relation remain readable from different boundaries. Particles, fields, spacetime, probabilities, thermodynamic variables, and other familiar scientific objects may therefore be boundary-specific representations rather than competing candidates for the primitive contents of nature.

That proposal remains to be tested by the mappings developed in later parts.

### 7.14 EP Projection and the Inversion of Scientific Explanation

The combined coin and statistical-mechanical argument gives EP projection a more precise meaning. An effective theory may correctly identify the local events through which an enclosing relation is realized. Because those local events are reproducible, their correlations can support highly accurate predictive laws.

Nothing about predictive success requires the causal interpretation to be primitive. The EP error occurs when the realizer of the relation is promoted to the source of the relation. This explains how science can invert causal agency without becoming predictively wrong.

The microscopic mechanism is real. Its correlation with the macroscopic behavior is real. Its usefulness in prediction is real. What R²D disputes is the additional ontological step: because the subordinate mechanism is necessary for realization, it must therefore be the primitive cause of the organized relation.

The coin construction removes that inference formally. The subordinate transitions cannot create the multiplicity landscape or enclosing compatibility that organizes their consequences. Statistical mechanics then supplies the empirical complement: changing the enclosing relation changes those subordinate consequences.

The inversion is therefore not between correct observations and incorrect observations. It is between realization and causal attribution.

### 7.15 Biology Provides an Independent Empirical Entry Point

R²D did not originate from the coin ensemble. It originated from muscle, where the distinction between local molecular events and ensemble structural organization is experimentally accessible. Protein-switch transitions are required for contraction. But the experimentally readable contractile state is expressed through the distribution of switch states rather than through the trajectory of one uniquely identifiable switch. This made it natural to ask whether the molecular event was being assigned more causal agency than the observation justified.

The surrounding biological hierarchy makes the question still more visible. Protein-state bias depends on nucleotide relations. Nucleotide relations depend on metabolic and electrochemical organization. Those depend on still larger cellular, organismal, and environmental relations. Expanding the boundary repeatedly reveals another condition under which the local realization is organized. Muscle therefore provides evidence complementary to statistical mechanics.

Statistical mechanics supplies an extraordinarily broad empirical demonstration that enclosing conditions organize local occupancy. Muscle supplied the experimental setting in which the distinction between ensemble structure and subordinate switching became sufficiently explicit to motivate the recursive causal interpretation developed here.

Muscle does not supply a second proof of the primitive statistical grammar; none is required. It provides an independent physical realization of the same enclosing-to-local organization already explicit in statistical mechanics. Together with the R²D theorems, these observations shift the remaining burden from the universality of the primitive architecture to the correctness of particular domain-specific mappings and realization postulates.

### 7.16 What Is Established and What Remains to Be Tested

R²D makes claims at several different logical levels. The combinatorial structure of Part I establishes that multiplicity belongs to a boundary-defined space of possible realizations, that realization does not create that multiplicity, and that changing enclosing compatibility can change or reverse local directional support without changing the native local landscape. This formally removes subordinate transitions as the sufficient source of the multiplicity structure and enclosing bias they realize.

The definitions also fix the direction of state dependence. A microstate has microstate meaning only relative to the enclosing boundary that defines the compatible realization domain and its macrostate classification. This is not an imported top-down causal assumption. It is the causal ordering implied by the state definitions. Any competing bottom-up account must therefore supply an alternative formal macrostate–microstate relation, or an equivalent whole–part state architecture, from which bottom-up causal sufficiency follows.

Statistical mechanics supplies independent and extensive empirical realization of the corresponding physical architecture: enclosing thermal, chemical, mechanical, and field conditions organize local occupancy, and the statistical formalism has no preferred physical scale. R²D therefore treats the primitive macrostate–microstate count architecture as structurally universal wherever scientific states admit distinguishable macrostates and compatible subordinate realizations.

What remains specifically to be tested are the **domain-specific physical mappings and additional realization postulates**: the proportional occurrence-realization relation in its stated domain, the proposed finite-count origin of directional efficiency, the R²D law, the Second-Law background correspondence, recursive carry as a general physical relation, the terminal nonclosure postulate, and the proposed readings of the primitive count coordinates in thermodynamics, quantum theory, gravity, biology, cosmology, and other domains.

That hierarchy matters. Statistical mechanics already demonstrates the enclosing-to-local statistical architecture and does so without a preferred physical scale. The later program therefore does not ask nature to re-establish that primitive grammar independently in each domain. It asks how each successful local physical theory reads the grammar, whether the proposed deprojection preserves the observations and mathematics of that domain, and whether any physical domain supplies a genuine counterexample to the macrostate–microstate architecture itself.

A failure of one proposed mapping is a failure of that mapping. A failure of structural universality would require a deeper counterexample: a scientific state relation that cannot be represented through boundary-defined macrostates and compatible subordinate realizations, or an alternative formal state architecture that derives a different causal ordering.

### 7.17 From a Universe of Objects to a Universe of Count Relations

The widest implication of R²D is therefore not a new equation. It is a change in what science takes to be causally primitive. Modern science commonly begins with objects and asks how they interact. R²D begins earlier.

Before an object can function as a scientific state, some boundary must define the distinctions through which that state is countable. Before a probability can be assigned, there must be possible realizations to normalize. Before a mechanism can explain a change, there must be a relation determining which changes constitute distinct outcomes. Before a subordinate event can be assigned causal agency for an enclosing organization, one must establish that the event actually defines the structure it is claimed to cause. The R²D framework shows that it does not.

The local event realizes a multiplicity landscape that already exists at the enclosing count boundary. A larger enclosing relation can alter the directional organization of that realization without altering the native local landscape.

Statistical mechanics then shows that nature behaves this way. Enclosing conditions do in fact organize local occupancy with extraordinary regularity.

R²D therefore identifies the familiar causal hierarchy of science as inverted at the level of statistical state architecture. What is usually called the microscopic cause is the local mechanism of realization. What is often called the macroscopic condition is the organizing causal relation.

Because statistical mechanics has no preferred physical scale, this primitive architecture is not restricted to one class of objects. Particles, molecules, fields, organisms, thermodynamic variables, quantum states, and spacetime coordinates may be different boundary-specific readings of one recursive organization of distinguishability, possibility, realization, and closure.

That is the widest structural claim of R²D.

The equations of Part I define its universal statistical grammar.

The remainder of the program must determine how the successful local theories of science map onto that grammar, which proposed mappings survive empirical test, and whether any domain supplies a genuine counterexample to the boundary-defined macrostate–microstate architecture itself.

*\
*


## Appendix A — Formalism of Dimensionless Recursive Counting

---
r2d_id: "canon-p1-app-a"
title: "Part I — Appendix A: Formalism of Dimensionless Recursive Counting"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 122
pdf_page_end: 172
semantic_amendment: "none"
review_status: "authoritative"
---
# Appendix A — Formalism of Dimensionless Recursive Counting

### A.0 Notation and Logical Conventions

A recursive count boundary is denoted

$B_{n}$,

where $n$ indexes the boundary relative to which a quantity is defined or read.

The smallest realized count boundary is denoted

$$B_{\alpha},$$

and the largest presently realized count boundary is denoted

$$B_{\omega}.$$

Thus,

$$\alpha \leq n \leq \omega.$$

The indices $\alpha$ and $\omega$ are reserved for these two limits of the realized hierarchy.

A macrostate readable at $B_{n}$ is denoted

$$i_{n} \in \mathcal{M}_{n}.$$

When the boundary is already clear, the shorter notation $i$ is used.

A readable macrostate transition at $B_{n}$ is denoted

$$i_{n} \rightarrow k_{n}.$$

A finite readable macrostate path that returns to its initial macrostate is denoted

$$\mathcal{O}_{n}.$$

A return that is compatible with recursive carry into the enclosing boundary is a closure,

$$\mathcal{C}_{n}.$$

A quantity indexed by

$$n,i \rightarrow k$$

belongs to one readable transition at $B_{n}$.

A quantity indexed by

$$n,\mathcal{C}$$

is accumulated around one closure at $B_{n}$.

A conditional quantity such as

$$\Theta_{n + 1 \mid n,i}$$

belongs to the enclosing boundary $B_{n + 1}$ but is conditioned on macrostate $i$ at $B_{n}$.

The enclosing constraint

$$C_{n + 1}$$

is defined on scale $n + 1$. It opposes readable macrostate change at $B_{n}$ and, after recursive carry, acts on the corresponding occurrence relation at $B_{n + 1}$.

No state identity, transition identity, multiplicity, occurrence count, occupancy, or closure identity is assumed to persist independently of the boundary relative to which it is defined.

### A.1 Definitions

#### A.1.1 Boundary, State, and Microstate Structure

**Definition 1 --- Count Boundary**

A count boundary

$$B_{n}$$

defines a count domain.

Relative to $B_{n}$, there may be multiple peer subordinate boundaries

$$\left\{ B_{n - 1,a} \right\}_{a \in I_{n - 1}}.$$

Boundary $B_{n}$determines:

-   which joint realizations of its peer subordinate boundaries are compatible;

-   which compatible joint realizations belong to the same readable macrostate;

-   which differences between macrostates are distinguishable;

-   which macrostate transitions are readable;

-   which peer-source distinctions are unresolved from.

A boundary need not be a material surface. It is the relation that defines what is distinguishable, what is equivalent, and what is being counted.

The enclosing boundary $B_{n + 1}$ separately determines which realizations and closures at scale $n$ are compatible with its own occurrences.

Thus, each boundary defines the count domain immediately subordinate to itself.

**Definition 2 --- Macrostate**

The readable macrostate set at $B_{n}$ is

$$\mathcal{M}_{n}.$$

A macrostate

$$i \in \mathcal{M}_{n}$$

is one distinguishable state within that count domain.

A macrostate is a boundary-defined classification. It is not itself a microstate occurrence, an occurrence count, or an occupancy.

**Definition 3 --- Readable Macrostate Transition**

For two distinguishable macrostates

$$i,k \in \mathcal{M}_{n},$$

a readable macrostate transition at $B_{n}$ is

$$\chi_{n,i \rightarrow k}:i \rightarrow k.$$

The transition is readable at $B_{n}$ because the distinction between $i$and $k$ is readable there

**Definition 4 --- Peer Subordinate Realization Domain**

Let

$$\mathfrak{X}_{n - 1,a}$$

denote the possible realization domain of peer subordinate boundary $B_{n - 1,a}$.

A joint peer realization relative to $B_{n}$ is a tuple

$$\mathbf{x}_{n - 1} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}},\quad\quad x_{n - 1,a} \in \mathfrak{X}_{n - 1,a}.$$

The unrestricted joint realization space is

$$\prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}.$$

Boundary $B_{n}$ need not permit every element of this product. It defines a compatible subset.

Compatibility is therefore a property of the boundary-defined whole, not a relation independently supplied by the peers.

**Definition 5 --- Formal Microstate**

The formal microstate space at $B_{n}$ is the set of compatible joint peer realizations:

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}$$

A formal microstate is one element

$$\mu_{n} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}} \in \mathfrak{M}_{n}.$$

Thus, a formal microstate is one complete compatible joint realization of the peer subordinate boundaries counted by $B_{n}$.

Its complete peer-resolved identity is formally defined but need not be individually readable from $B_{n}$.

**Definition 6 --- Microstate Transition**

A microstate transition relative to $B_{n}$ is a change

$$\mu_{n} \rightarrow \mu_{n}'.$$

An elementary microstate transition may arise from a readable macrostate transition at one peer boundary $B_{n - 1,a}$:

$$B_{n - 1,a}:\quad\quad i \rightarrow k.$$

Relative to $B_{n}$, the same change is a microstate transition.

Thus, a macrostate transition at $B_{n - 1,a}$ is a microstate transition relative to $B_{n}.$

The peer label $a$ is readable from $B_{n - 1,a}$ but need not be distinguishable from its peers at $B_{n}$.

A microstate transition is therefore formally definable at $B_{n}$ without being individually readable there.

**Definition 7 --- Macrostate Classification**

Boundary $B_{n}$defines the classification map

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}.$$

The relation

$$\pi_{n}\left( \mu_{n} \right) = i$$

means that formal microstate $\mu_{n}$ is classified as readable macrostate $i$.

Two formal microstates are macrostate-equivalent when

$$\mu_{n} \sim_{n}\mu_{n}'\quad \Longleftrightarrow \quad\pi_{n}\left( \mu_{n} \right) = \pi_{n}\left( \mu_{n}' \right).$$

Thus,

$$\pi_{n}^{-1}(i)$$

is the complete set of compatible formal microstates classified as macrostate $i$.

The map $\pi_{n}$ is a classification relation. It is not a causal arrow from microstate to macrostate.

**Definition 8 --- Multiplicity**

The multiplicity of macrostate $i$ at $B_{n}$ is

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|.$$

Multiplicity is therefore the number of compatible joint peer realizations classified as macrostate $i$.

It is possible-count structure and is defined prior to any particular realization.

#### A.1.2 Multiplicity, Entropy, Occurrence, and Occupancy

**Definition 9 --- Entropy**

The dimensionless entropy of macrostate $i$ is

$$S_{n,i} = \ln W_{n,i}.$$

For a readable transition

$$i \rightarrow k,$$

the entropic difference is

$$\Delta S_{n,i \rightarrow k} = S_{n,k} - S_{n,i} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right).$$

In Part I, entropy is only logarithmic possible count. It is not yet thermodynamic entropy.

**Definition 10 --- Total Boundary Multiplicity**

The total possible multiplicity at boundary $B_{n}$ is the cardinality of its formal microstate domain:

$$\Theta_{n} = \left| \mathfrak{M}_{n} \right|.$$

Thus, $\Theta_{n}$ counts all compatible joint peer realizations contained in the count domain defined by $B_{n}$, before classification into readable macrostates.

Because

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a},$$

is the cardinality of the boundary-defined compatible subset of the unrestricted joint peer-realization space.

No summation over macrostates is included in this definition. That relation follows from the macrostate partition theorem.

**Definition 11 --- Total Boundary Entropy**

The total boundary entropy is

$$S_{n}^{tot} = \ln \Theta_{n}.$$

This is distinct from the entropy $S_{n,i}$ of one macrostate and from the transition difference $\Delta S_{n,i \rightarrow k}$.

**Definition 12 --- Native Multiplicity and Entropic Landscapes**

The native multiplicity landscape at $B_{n}$ is

$$\mathcal{W}_{n} = \left\{ W_{n,i} \right\}_{i \in \mathcal{M}_{n}}.$$

The corresponding entropic landscape is

$$\mathcal{S}_{n} = \left\{ S_{n,i} \right\}_{i \in \mathcal{M}_{n}}.$$

These landscapes define possible-count structure.

Realization occupies this structure but does not create or alter the native multiplicity while the boundary classification remains fixed.

**Definition 13 --- Microstate Occurrence**

A microstate occurrence at $B_{n}$ is one realized instance of a formally possible microstate:

$$\mu_{n}^{(r)} \in \mathfrak{M}_{n}.$$

If

$$\pi_{n}\left( \mu_{n}^{(r)} \right) = i,$$

then that realization contributes one occurrence associated with macrostate $i$.

The complete peer-resolved identity of $\mu_{n}$ need not be readable from $B_{n}$. What $B_{n}$ reads is its macrostate classification.

A microstate occurrence is therefore one realized count of a formally possible joint peer realization.

**Definition 14 --- Microstate-Occurrence Count**

Let

$$\nu_{n,i}$$

denote the number of realized microstate occurrences classified as macrostate $i$ within a specified finite realization domain. Its logarithmic occurrence coordinate is

$$\tau_{n,i} = \ln \nu_{n,i}.$$

For a readable transition

$$i \rightarrow k,$$

the net occurrence-count difference is

$$\Delta\tau_{n,i \rightarrow k} = \tau_{n,k} - \tau_{n,i} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right).$$

The realization domain is a finite domain of count. It is not assumed to be a time interval. The logarithmic occurrence coordinate is an occurrence statistic, not a closure recurrence count.

**Definition 15 --- Macrostate Occupancy**

Let

$$c_{n,i}$$

denote the realized occupancy of macrostate $i$ in a specified realized configuration. Its logarithmic occupancy coordinate is

$$G_{n,i} = \ln c_{n,i}.$$

For a readable transition

$$i \rightarrow k,$$

the occupancy difference is

$$\Delta G_{n,i \rightarrow k} = G_{n,k} - G_{n,i} = \ln\left( \frac{c_{n,k}}{c_{n,i}} \right).$$

**Definition 16 --- Structural Macrostate**

The structural macrostate at $B_{n}$ is the macrostate of maximum occupancy:

$$i_{n}^{*} = {*{\arg\,\max}}_{i \in \mathcal{M}_{n}}c_{n,i}.$$

Because the logarithm is monotonic,

$$i_{n}^{*} = {*{\arg\,\max}}_{i \in \mathcal{M}_{n}}G_{n,i}.$$

**Definition 17 --- Structural Macrostate Transition**

A structural macrostate transition is a readable change in occupancy mode:

$$i_{n}^{*} \rightarrow k_{n}^{*}.$$

It is the net structural change in the occupancy landscape.

It does not identify one particular microstate transition or peer-source trajectory.

#### A.1.3 Enclosing Compatibility and Possibility

**Definition 18 --- Enclosing Compatibility Fiber**

Consider a specified local boundary $B_{n}$contained within $B_{n + 1}$.

Let

$$\mathfrak{M}_{n + 1}$$

be the possible formal microstate domain at the enclosing boundary.

For local macrostate

$$i \in \mathcal{M}_{n},$$

define the enclosing compatibility fiber

$$\mathcal{E}_{n + 1 \mid n,i} = \left\{ \mu_{n + 1} \in \mathfrak{M}_{n + 1}:\mu_{n + 1}\text{~}\text{is~compatible~with~local~classification}\text{~}i \right\}.$$

Its multiplicity is

$$\Theta_{n + 1 \mid n,i} = \left| \mathcal{E}_{n + 1 \mid n,i} \right|.$$

Thus, $\Theta_{n + 1 \mid n,i}$ counts the possible enclosing realizations at $B_{n + 1}$ that are compatible with local macrostate classification $i$ at $B_{n}$.

The conditional index

$$n + 1 \mid n,i$$

means that the **enclosing count is conditioned on a local classification**. It does not imply that macrostate $i$ persists as the same state at $B_{n + 1}$.

When multiple peer boundaries at scale $n$ must be distinguished, retain the peer index explicitly:

$$\mathcal{E}_{n + 1 \mid n,a,i},\quad\quad\Theta_{n + 1 \mid n,a,i}.$$

**Definition 19 --- Enclosing Extension Multiplicity**

For local macrostate

$$i \in \mathcal{M}_{n},$$

let

$$W_{n,i}$$

be its local multiplicity and

$$\Theta_{n + 1 \mid n,i}$$

the multiplicity of enclosing realizations compatible with that local classification.

Define the **mean compatible enclosing extension multiplicity per local possibility** as

$$K_{n + 1 \mid n,i} = \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}}.$$

Thus,

$$K_{n + 1 \mid n,i}$$

is the mean number of compatible realizations at $B_{n + 1}$ available per formal microstate at $B_{n + 1}$ classified as macrostate $i$.

If every formal microstate

$$\mu_{n} \in \pi_{n}^{-1}(i)$$

has the same number of compatible enclosing extensions, then

$$K_{n + 1 \mid n,i}$$

is that common extension count.

In general, $K_{n + 1 \mid n,i}$ is a **multiplicity**, not a probability or normalized fraction. It measures how extensively a local possibility can participate in compatible realizations of the enclosing count domain.

**Definition 20 --- Possibility**

The possibility associated with local macrostate $i$ is

$$P_{n,i} = \ln K_{n + 1 \mid n,i} = \ln\left( \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}} \right).$$

Possibility is therefore defined from compatible enclosing multiplicity.

It is not an independent primitive force or local occupancy variable.

For a readable local transition

$$i \rightarrow k,$$

the directional possibility difference is

$$\Delta P_{n,i \rightarrow k} = P_{n,k} - P_{n,i} = \ln\left( \frac{K_{n + 1 \mid n,k}}{K_{n + 1 \mid n,i}} \right).$$

Direction requires unequal enclosing compatibility:

$$K_{n + 1 \mid n,k} \neq K_{n + 1 \mid n,i}.$$

**Definition 21 --- Compatible Enclosing Entropy**

The compatible enclosing entropy conditioned on local macrostate $i$ is

$$S_{n + 1 \mid n,i}^{comp} = \ln \Theta_{n + 1 \mid n,i}.$$

Therefore,

$$P_{n,i} = S_{n + 1 \mid n,i}^{comp} - S_{n,i}.$$

Possibility is thus an across-boundary logarithmic possible-count difference.

#### A.1.4 Distinguishability, Constraint, Retention, and Asymmetry

**Definition 22 --- Distinguishability**

For a readable transition

$$i \rightarrow k$$

at $B_{n}$, the distinguishable interval is

$$\lambda_{n,i \rightarrow k}$$

It is oriented:

$$\lambda_{n,k \rightarrow i} = - \lambda_{n,i \rightarrow k}.$$

Its magnitude

$$\left| \lambda_{n,i \rightarrow k} \right|$$

is the distinguishable size of the transition.

No primitive spatial, mechanical, energetic, or temporal interpretation is assumed.

**Definition 23 --- Enclosing Constraint**

The enclosing constraint associated with a local realization at $B_{n}$ is

$C_{n + 1} \geq 0$.

It is defined by the enclosing count relation at Bₙ₊₁. The total constraint can be decomposed into productive and background-associated components. Only the productive component participates in retention against local distinguishability at Bₙ; the complete constraint enters the enclosing recurrence read of the R2D law.

When constraint differs between branches, conditions, or peer realizations, the appropriate additional index is retained.

**Definition 24 --- Retention**

For the readable transition

$$i \rightarrow k,$$

retention is

$${\Delta R}_{n,i \rightarrow k} = C_{n + 1}^{out}\lambda_{n,i \rightarrow k}.$$

Because $C_{n + 1}^{out} > 0$ retention inherits the orientation of $\lambda_{n,i \rightarrow k}$:

$${\Delta R}_{n,k \rightarrow i} = - \Delta R_{n,i \rightarrow k}.$$

**Definition 25 --- Net Local Asymmetry**

The net local asymmetry associated with transition

$$i \rightarrow k$$

is the directional possibility remaining after retention:

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k}.$$

This defines what local asymmetry is.

Its effect on occupancy is specified separately by the asymmetric occupancy-realization postulate.

#### A.1.5 Return, Closure, and Occurrence-Count Loss

**Definition 26 --- Macrostate Return**

A macrostate return at $B_{n}$ is a finite readable path

$$\mathcal{R}_{n}:i_{0} \rightarrow i_{1} \rightarrow \cdots \rightarrow i_{m}$$

such that

$i_{m} = i_{0}$.

A return is defined entirely by local path completion.

**Definition 27 --- Closure**

A macrostate return at $B_{n}$ is a closure relative to $B_{n + 1}$ when it is compatible with at least one enclosing occurrence at $B_{n + 1}$.

The closure is denoted

$$\mathcal{C}_{n,a}$$

when the peer label $a$ must be retained.

The path is readable locally from $B_{n}$.

From $B_{n + 1}$, its peer-source identity and internal macrostate path need not remain readable as the same objects.

Thus, return is local path completion whereas closure is local return compatible with an enclosing occurrence.

**Definition 28 --- Asymmetric Closure**

A closure is asymmetric when its opposed structural legs are realized under different enclosing compatibility and/or constraint relations.

For a minimal two-leg closure, label the opposed legs H and L.

Their directional possibilities and retentions may satisfy

$$\Delta P_{n,a,H} \neq - \Delta P_{n,a,L},$$

and/or

$${\Delta R}_{n,a,H} \neq - {\Delta R}_{n,a,L}.$$

Thus, the local macrostate path may close even though the enclosing relations organizing its two legs are not recursive inverses.

**Definition 29 --- Closure Possibility, Retention, and Asymmetry**

For a completed closure at peer $a$,

$$\mathcal{C}_{n,a},$$

let

$$\chi \in \mathcal{C}_{n,a}$$

denote the readable transitions belonging to that closure.

The accumulated directional possibility around the closure is

$$\Delta P_{n,a,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,a}}\Delta P_{n,a,\chi}.$$

The accumulated retention around the closure is

$${\Delta R}_{n,a,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,a}}{\Delta R}_{n,a,\chi}.$$

The **net closure asymmetry** is then

$${\Delta A}_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - {\Delta R}_{n,a,\mathcal{C}}.$$

Thus, ${\Delta A}_{n,a,\mathcal{C}}$ measures the enclosing-defined directional asymmetry that remains after possibility and retention have been accumulated around the completed local closure.

Complete retention around the closure satisfies

$${\Delta A}_{n,a,\mathcal{C}} = 0,$$

or equivalently,

$$\Delta R_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}}.$$

A completed local return does **not** require this condition. The native multiplicity may close exactly while the enclosing-defined closure asymmetry remains nonzero.

**Definition 30 --- Closure Recurrence Count**

Let $\mathcal{D}_{R}$ be a finite recurrence-comparison domain. For completed closure $\mathcal{C}_{n,a}$, define

$$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)$$

as the number of completed recurrences of that closure within $\mathcal{D}_{R}$.

This is a whole-closure recurrence count. It is distinct from the state occurrence counts $\nu_{n,i}$ and from the opposed-leg occurrence counts $\nu_{n,a,H}$ and $\nu_{n,a,L}$.

No physical time interval is assumed. The recurrence-comparison domain is a finite domain of count.

**Definition 31 --- Occurrence-Count Efficiency and Occurrence-Count Loss**

For an oriented two-leg closure, let

$$\nu_{n,a,H}$$

denote the occurrence count associated with one leg and

$$\nu_{n,a,L}$$

the occurrence count associated with completion of the opposed leg.

Define the directional occurrence-count efficiency of the completed closure as

$$\eta_{n,a,\mathcal{C}} = \frac{\nu_{n,a,L}}{\nu_{n,a,H}}.$$

Choose the closure orientation such that

$$0 < \eta_{n,a,\mathcal{C}} \leq 1.$$

Reciprocal occurrence realization satisfies

$$\eta_{n,a,\mathcal{C}} = 1.$$

Nonreciprocal realization satisfies

$$0 < \eta_{n,a,\mathcal{C}} < 1.$$

Define the logarithmic occurrence-count loss as

$$L_{\tau,n,a,\mathcal{C}} = - {\ln\eta}_{n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right).$$

Reversible occurrence closure satisfies

$$L_{\tau,n,a,\mathcal{C}} = 0.$$

Irreversible occurrence closure satisfies

$$L_{\tau,n,a,\mathcal{C}} > 0.$$

Occurrence-count loss is not destruction or annihilation of count. It is the logarithmic count consequence of unequal directional efficiency between the opposed legs of a completed closure.

#### A.1.6 Enclosing Occurrence, Recursive Carry, and Background

**Definition 32 --- Enclosing Occurrence, Recurrence Ratio, and Recursive Carry**

Consider one realized occurrence at $B_{n + 1}$ associated with readable enclosing transition

$$\chi_{n + 1}:j \rightarrow k.$$

Denote one such enclosing occurrence by

$$\chi_{n + 1}^{(r)}.$$

Let the peer boundaries at scale $n$ be

$$\{ B_{n,a}\}_{a \in I_{n}}.$$

The enclosing occurrence defines the compatible joint peer-closure set

$$\mathfrak{D}_{n + 1,\chi}.$$

The causal realization relation is therefore

$$\chi_{n + 1}^{(r)} \Rightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

The enclosing occurrence defines the compatible peer closures through which it is locally realized. The peer closures do not combine causally to generate the enclosing occurrence.

Within the same recurrence-comparison domain $\mathcal{D}_{R}$ used in Definition 30, define

$$N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)$$

as the number of completed recurrences of the enclosing transition class. For a representative peer closure with $N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) > 0$, the adjacent recurrence ratio is

$$\boxed{\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}.}$$

This ratio does not imply a one-to-one event correspondence. It compares the recurrence counts of two boundary-specific readings over one common count domain.

For a compatible peer $a$,

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

denotes recursive carry.

Recursive carry is a cross-boundary reclassification relation. It states that a completed local closure, when read from the enclosing boundary, is counted according to the enclosing occurrence to which it belongs. It is not a causal arrow from $B_{n}$ to $B_{n + 1}$.

**Definition 33 --- Background Count**

Let

$$b_{n} > 0$$

denote realized count at $B_{n}$ whose subordinate directional classification is not readable there.

R²D calls this nondirectional realized count **background**.

Its logarithmic coordinate is

$$\Phi_{n} = \ln b_{n}.$$

Within one local landscape, background is common to the readable macrostates:

$$\Delta\Phi_{n,i \rightarrow k} = 0.$$

Background is realized count. It is not enclosing possibility. Thus, no identity

$$\Phi_{n} = P_{n}$$

is assumed.

Background is boundary-relative. Two quantities that are separately background at peer boundaries $B_{n,a}$and $B_{n,b}$ may define a distinguishable relation from $B_{n + 1}$:

$$\Delta\Phi_{n + 1 \mid n,a:b} = \Phi_{n,a} - \Phi_{n,b}.$$

If this difference is nonzero, it is an enclosing distinction, not local background.

**Definition 34 --- Background Increment**

For a specified realized relation, let

bₙ⁻

and

bₙ⁺

denote background count immediately before and after that realization.

The logarithmic background increment is

δΦₙ = ln(bₙ⁺/bₙ⁻).

For an increment associated specifically with representative closure $\mathcal{C}_{n + 1}$ and read at $B_{n + 1}$, write

$$\delta_{\mathcal{C}}\Phi_{n + 1}.$$

This is a logarithmic before/after ratio. It does not assert additive composition of raw background counts.

**Definition 35 --- Productive and Dissipative Constraint**

The total enclosing constraint may be decomposed as

$$C_{n + 1} = C_{n + 1}^{out} + C_{n + 1}^{\Phi}.$$

The productive component

$$C_{n + 1}^{out}$$

is the component that defines local retention at Bₙ and whose enclosing realization remains readable as distinguishable output.

The dissipative component

$$C_{n + 1}^{\Phi}$$

does not enter local retention. It contributes to the same total enclosing constrained occurrence, and its realized contribution is read after realization as background-associated.

The corresponding constrained distinguishabilities are

$$C_{n + 1}^{out}\lambda_{n + 1}$$

and

$$C_{n + 1}^{\Phi}\lambda_{n + 1}.$$

They are not separate transitions or separate occurrence pathways.

#### A.1.7 Recurrence and Readability Horizons

**Definition 36 --- Adjacent Recurrence Scaling**

For adjacent boundaries with positive recurrence ratio,

$$\rho_{n + 1 \mid n,a} > 0,$$

define the logarithmic adjacent recurrence scaling

$$\gamma_{n + 1 \mid n,a} = \ln \rho_{n + 1 \mid n,a}.$$

No physical rate or elapsed time is assumed.

**Definition 37 --- Accumulated Count-Geometry Scaling**

For two readable boundaries

$$B_{n},\quad B_{N},\quad\quad N > n,$$

define the accumulated distinguishability scaling

$$\Lambda_{N \mid n} = \ln\left( \frac{\left| \lambda_{N} \right|}{\left| \lambda_{n} \right|} \right),$$

and the accumulated recurrence scaling

$$\Gamma_{N \mid n} = \sum_{j = n}^{N - 1}\ln\rho_{j + 1 \mid j}.$$

The accumulated count-geometry imbalance is

$$\boxed{H_{N \mid n} = \Lambda_{N \mid n} - \Gamma_{N \mid n}.}$$

Equivalently,

$$H_{N \mid n} = \ln\left\lbrack \frac{\left| \lambda_{N} \right|/\left| \lambda_{n} \right|}{\prod_{j = n}^{N - 1}\rho_{j + 1 \mid j}} \right\rbrack.$$

A readability horizon requires this relative scaling together with a boundary-relative loss of resolution of one count relation while the other remains readable. Divergence of $H$ alone does not define a horizon.

**Definition 38 --- Determinism**

For repeated realizations of enclosing transition $\chi$, let

$$\mathfrak{D}_{n + 1,\chi}^{(r)}$$

denote the compatible joint peer-closure relation associated with realization.

When the enclosing compatibility relation remains stable,

$$\mathfrak{D}_{n + 1,\chi}^{(1)} = \mathfrak{D}_{n + 1,\chi}^{(2)} = \cdots,$$

the same classes of peer realizations remain jointly compatible with the same enclosing occurrence relation.

R²D calls the resulting persistent correlation among peer realizations **determinism**. Thus,

$$\text{stable~enclosing~compatibility} \Longrightarrow \text{stable~peer~correlation}.$$

Determinism is a within-scale reading of stable enclosing organization. It does not require primitive causal interaction among the peer realizations themselves.

**Definition 39 --- Across-Scale Coherence**

Let

$$\mathcal{R}_{n}$$

be a relation among compatible subordinate realizations at scale $B_{n}$.

Let

$$\kappa_{n}\left\lbrack \mathbf{x}_{n} \right\rbrack$$

denote the enclosing reclassification of the compatible realization under recursive carry.

The relation is coherent across

$$B_{n} \rightarrow B_{n + 1}$$

when there exists an enclosing relation

$$\mathcal{R}_{n + 1}$$

such that

$$\mathcal{R}_{n}\left( \mathbf{x}_{n} \right) \Longleftrightarrow \mathcal{R}_{n + 1}\left( \kappa_{n}\left\lbrack \mathbf{x}_{n} \right\rbrack \right)$$

for the compatible realizations under consideration. Coherence therefore does not preserve subordinate state identity, peer-source identity, or local path identity.

It preserves relational organization through a boundary at which those constituent identities change count meaning or become unreadable. Thus, state identity may be replaced while relational organization remains coherent.

Determinism and coherence are distinct:

$$\begin{aligned}
\text{determinism} & = \text{stable~correlation~among~peers}, \\
\text{coherence} & = \text{preserved~relational~organization~across~recursive~reclassification}.
\end{aligned}$$

#### A.1.9 Limits of Recursive Realization

**Definition 40 --- Smallest Realized Boundary**

The smallest realized count boundary is denoted

$$B_{\alpha}.$$

It is the lowest boundary at which primitive distinguishable recurrence is defined within the realized R²D hierarchy.

No realized boundary

$$B_{\alpha - 1}$$

is required.

**Definition 41 --- Largest Presently Realized Boundary**

The largest presently realized count boundary is denoted

$$B_{\omega}.$$

Its presently realized path is

$$\mathcal{O}_{\omega}:i_{\omega,0} \rightarrow i_{\omega,1} \rightarrow \cdots \rightarrow i_{\omega,m}.$$

Its openness and causal status are specified by the terminal postulate.

No assumption of a presently realized $B_{\omega + 1}$ is contained in this definition.

### A.2 Axioms of Boundary-Indexed Recursive Counting

**Axiom 1 --- Boundary-Indexed Statehood**

A state is defined only relative to a count boundary.

At boundary

$$B_{n},$$

the possible joint realizations of the immediately subordinate peer boundaries

$$\left\{ B_{n - 1,a} \right\}_{a \in I_{n - 1}}$$

belong to realization domains

$$\mathfrak{X}_{n - 1,a}.$$

Boundary $B_{n}$ defines the compatible formal microstate domain

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}.$$

A formal microstate at $B_{n}$ is therefore

$$\mu_{n} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}} \in \mathfrak{M}_{n}.$$

The same boundary defines the readable macrostate domain

$$\mathcal{M}_{n}$$

and the classification map

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}.$$

Thus,

$$\pi_{n}\left( \mu_{n} \right) = i$$

means that formal microstate $i$ is classified as readable macrostate

$$i \in \mathcal{M}_{n}$$

relative to $B_{n}$.

Neither formal microstate nor macrostate is defined independently of the boundary that defines its count domain. Therefore, statehood is boundary relative. Changing the count boundary changes the domain relative to which state identity is defined.

For adjacent boundaries,

$$B_{n} \neq B_{n + 1},$$

the corresponding formal microstate and macrostate domains are independently boundary-defined:

$$\mathfrak{M}_{n},\quad\quad\mathcal{M}_{n},$$

and

$$\mathfrak{M}_{n + 1},\quad\quad\mathcal{M}_{n + 1}.$$

Hence,

$$B_{n} \neq B_{n + 1}\quad \Longrightarrow \quad\mathfrak{M}_{n} \neq \mathfrak{M}_{n + 1} \text{and/or} \mathcal{M}_{n} \neq \mathcal{M}_{n + 1}.$$

No boundary-independent identity map

$$\mathfrak{M}_{n} \rightarrow \mathfrak{M}_{n + 1}$$

or

$$\mathcal{M}_{n} \rightarrow \mathcal{M}_{n + 1}$$

is assumed.

A distinction may remain recursively consequential after the count boundary changes without remaining the same state at the new boundary.

**Thus, a state is not an object first defined independently and subsequently viewed from a different scale. Rather, the count boundary participates in the definition of the state itself.**

This axiom establishes boundary-relative **statehood**. Axiom 4 then gives the stronger recursive consequence: when the boundary changes, subordinate state, transition, source, and path identities are replaced rather than merely concealed.

**Axiom 2 --- Boundary-Relative Readability of Transitions**

A transition that is readable as a macrostate transition at one boundary is a microstate transition relative to the immediately enclosing boundary.

For a peer subordinate boundary $B_{n - 1,a}$,

$$B_{n - 1,a}:\quad\quad i \rightarrow k$$

is readable as a macrostate transition.

Relative to $B_{n}$, the corresponding change is a microstate transition:

$$\text{macrostate~transition~at~}B_{n - 1,a} = \text{microstate~transition~relative~to~}B_{n}.$$

$B_{n}$may define the microstate transition class while being unable to identify which peer supplied a particular realization.

**Therefore, a microstate transition is formally definable but not individually readable from the boundary relative to which it is a microstate transition.**

Resolving the transition requires changing the count boundary to the subordinate boundary where that same change is classified as a macrostate transition.

**Axiom 3 --- Enclosing Definition of Compatibility**

Compatibility is defined by the boundary of the whole.

At $B_{n}$, the boundary defines which joint realizations of its peer subordinate boundaries

$$\left\{ B_{n - 1,a} \right\}_{a \in I_{n - 1}}$$

belong to the formal microstate space

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}.$$

It also defines their macrostate classification:

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}.$$

Consequently,

$$\pi_{n}^{-1}(i)$$

is not a collection assembled independently by the subordinate peers. It is the set of joint peer realizations that $B_{n}$defines as compatible with macrostate $i$.

**Axiom 4 --- Recursive Replacement**

When the count boundary changes, subordinate state, transition, source, and path identities do not persist automatically as the same identities in the new count domain.

A formal microstate at $B_{n}$,

$$\mu_{n} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}},$$

belongs to a different count domain from a formal microstate at $B_{n + 1}$,

$$\mu_{n + 1} = \left( x_{n,b} \right)_{b \in I_{n}}.$$

Thus,

$$\mu_{n} \not\equiv \mu_{n + 1}.$$

Likewise, a macrostate transition readable at $B_{n}$,

$$i \rightarrow k,$$

does not persist as the same readable macrostate transition at $B_{n + 1}$. Relative to $B_{n + 1}$, it has microstate meaning. A completed peer closure

$$\mathcal{C}_{n,a}$$

may remain consequential at $B_{n + 1}$, but its peer-source label and internal path need not remain readable there.

Recursive replacement is therefore not ordinary concealment or coarse graining. It is a change in what the count means:

$$\text{change~of~boundary} \Longrightarrow \text{change~of~count~identity}.$$

What is preserved across the boundary is a recursively organized count relation, not an unchanged subordinate object.

**Axiom 5 --- Compatible Composition of Multiplicity**

Compatible possibilities compose jointly. For peer subordinate realization domains

$$\left\{ \mathfrak{X}_{n - 1,a} \right\}_{a \in I_{n - 1}},$$

the unrestricted joint possibility space is the Cartesian product

$$\prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}.$$

If every joint peer realization is compatible at $B_{n}$, then

$$\mathfrak{M}_{n} = \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a},$$

and therefore

$$\Theta_{n} = \prod_{a \in I_{n - 1}}\left| \mathfrak{X}_{n - 1,a} \right|.$$

Thus, unrestricted compatible possibilities multiply. If the enclosing boundary permits only a subset of the unrestricted joint realizations, then

$$\mathfrak{M}_{n} \subset \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a},$$

and the total multiplicity is

$$\Theta_{n} = \left| \mathfrak{M}_{n} \right|.$$

The enclosing boundary therefore determines which products of peer possibilities belong to the count domain of the whole. Multiplicity is not obtained by arithmetically adding the possible states of independently persistent subordinate objects. Rather, compatible joint possibilities compose multiplicatively, subject to the compatibility relation of the whole.

The addition of mutually exclusive macrostate multiplicities is not independently axiomatized. It follows from the partition of the formal microstate domain into mutually exclusive macrostate fibers.

**Axiom 6 --- Enclosing Occurrence Realization and Recursive Carry**

An enclosing occurrence and its compatible peer closures are adjacent-boundary readings of one recursively organized realization.

For one occurrence

$$\chi_{n + 1}^{(r)}$$

at $B_{n + 1}$, the enclosing boundary defines its compatible joint peer closures:

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

This is the causal realization relation. For any compatible representative peer *a*,

$$\mathcal{C}_{n,a}$$

is one local realization of that enclosing occurrence.

When the completed peer closure is read from $B_{n + 1}$, it is reclassified according to the enclosing occurrence to which it belongs:

$$\mathcal{C}_{n,g}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

This is recursive carry. The carry arrow does **not** state that

$$\mathcal{C}_{n,a}$$

causes or constructs

$$\chi_{n + 1}^{(r)}.$$

Rather,

$$\begin{aligned}
\text{causal~realization:}\quad\quad & \chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,g}, \\
\text{recursive~carry:}\quad\quad & \mathcal{C}_{n,g}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.
\end{aligned}$$

The arrows have opposite mathematical orientations because they answer different questions.

The first asks: Which local realizations are compatible with this enclosing occurrence?

The second asks: How is this completed local realization classified when read from the enclosing boundary?

Thus, recursive carry is reclassification across a boundary, not bottom-up causation. When multiple peer closures are equivalent relative to the enclosing occurrence, one representative peer closure may express the local relation without implying that it alone generates the enclosing occurrence.

### A.3 Theorems of Recursive Multiplicity

**Theorem 1 --- Microstate Relabeling Invariance**

A permutation of formal microstate labels that preserves macrostate classification leaves multiplicity unchanged.

Let

$$\sigma_{n}:\mathfrak{M}_{n} \rightarrow \mathfrak{M}_{n}$$

be a bijection satisfying

$$\pi_{n} \circ \sigma_{n} = \pi_{n}.$$

Then for every macrostate $i$,

$$\sigma_{n}\left( \pi_{n}^{-1}(i) \right) = \pi_{n}^{-1}(i).$$

Therefore,

$$\left| \sigma_{n}\left( \pi_{n}^{-1}(i) \right) \right| = \left| \pi_{n}^{-1}(i) \right| = W_{n,i}.$$

Multiplicity therefore depends on the cardinality of the compatible joint realizations assigned to a macrostate, not on arbitrary labels assigned to those realizations.

**Theorem 2 --- Macrostate Partition of the Formal Microstate Domain**

The macrostate classification map

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}$$

partitions the formal microstate domain into mutually disjoint macrostate fibers:

$$\mathfrak{M}_{n} = \bigsqcup_{i \in \mathcal{M}_{n}}\pi_{n}^{-1}(i).$$

Therefore,

$$\Theta_{n} = \sum_{i \in \mathcal{M}_{n}}W_{n,i}.$$

Proof

By definition, $B_{n}$ assigns every formal microstate

$$\mu_{n} \in \mathfrak{M}_{n}$$

to one readable macrostate

$$i \in \mathcal{M}_{n}.$$

Therefore, for distinct macrostates

$$i \neq k,$$

their fibers are disjoint:

$$\pi_{n}^{-1}(i) \cap \pi_{n}^{-1}(k) = \varnothing.$$

Every formal microstate has one macrostate classification, so the union of all fibers exhausts the formal microstate domain:

$$\mathfrak{M}_{n} = \bigsqcup_{i \in \mathcal{M}_{n}}\pi_{n}^{-1}(i).$$

Taking cardinalities gives

$$\left| \mathfrak{M}_{n} \right| = \sum_{i \in \mathcal{M}_{n}}\left| \pi_{n}^{-1}(i) \right|.$$

Using Definition 10,

$$\Theta_{n} = \left| \mathfrak{M}_{n} \right|,$$

and the definition of macrostate multiplicity,

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|,$$

we obtain

$$\Theta_{n} = \sum_{i \in \mathcal{M}_{n}}W_{n,i}.$$

Thus, mutually exclusive macrostate alternatives add.

This addition is a theorem of boundary-defined classification, whereas multiplicative compatible composition is the primitive composition rule supplied by Axiom 5.

The resulting hierarchy is especially clean:

$$\begin{aligned}
\text{Definition~10:}\quad\quad & \Theta_{n} = \left| \mathfrak{M}_{n} \right|, \\
\text{Axiom~5:}\quad\quad & \text{compatible~joint~possibilities~compose~multiplicatively}, \\
\text{Theorem~2:}\quad\quad & \Theta_{n} = \sum_{i}W_{n,i}.
\end{aligned}$$

The compact principle: compatible joint possibilities multiply while mutually exclusive alternatives add$.$ The two halves have different and explicit logical status: **multiplication is the composition axiom; addition is derived from classification into disjoint fibers.**

**Theorem 3 --- Boundary-State Nonidentity**

A state defined at $B_{n}$ does not acquire identity as the same state at $B_{n + 1}$ merely by recursive reclassification.

At $B_{n}$,

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a},$$

whereas at $B_{n + 1}$,

$$\mathfrak{M}_{n + 1} \subseteq \prod_{b \in I_{n}}\mathfrak{X}_{n,b}.$$

These are boundary-indexed realization domains with independent classification maps

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}$$

and

$$\pi_{n + 1}:\mathfrak{M}_{n + 1} \rightarrow \mathcal{M}_{n + 1}.$$

Therefore, no canonical identity map

$$\mathfrak{M}_{n} \rightarrow \mathfrak{M}_{n + 1}$$

is defined by the R²D architecture. Thus,

$$\mu_{n} \not\equiv \mu_{n + 1}$$

as boundary-defined state identities, even if two state spaces happen to have equal cardinality or an abstract mathematical isomorphism.

**Theorem 4 --- Multiplicity Is Boundary-Specific**

At adjacent boundaries,

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|,$$

whereas

$$W_{n + 1,j} = \left| \pi_{n + 1}^{-1}(j) \right|.$$

The two cardinalities belong to different boundary-defined formal microstate domains.

Therefore,

$$W_{n,i} \not\equiv W_{n + 1,j}$$

as count objects.

They may have the same numerical value,

$$W_{n,i} = W_{n + 1,j},$$

without counting the same possibilities. Thus, multiplicity is not recursively carried as an unchanged object. Each boundary defines its own multiplicity through its own compatible realization domain and classification map.

**Theorem 5 --- Logarithmic Additivity Under Unrestricted Compatible Composition**

For unrestricted compatible composition,

$W_{joint} = \prod_{a = 1}^{m}W_{a}$.

Therefore,

$S_{joint} = \ln W_{joint} = \sum_{a = 1}^{m}\ln W_{a} = \sum_{a = 1}^{m}S_{a}$.

Thus, logarithmic addition is the additive reading of multiplicative composition.

**Theorem 6 --- Possibility Is an Across-Boundary Entropy Difference**

From Definition 20,

$P_{n,i} = \ln\left( \frac{\Theta_{n + 1 \mid n,i}}{W_{n,i}} \right)$.

Therefore,

$$P_{n,i} = S_{n + 1 \mid n,i}^{comp} - S_{n,i}.$$

Proof

Substitute

$$S_{n + 1 \mid n,i}^{comp} = \ln \Theta_{n + 1 \mid n,i}$$

and

$$S_{n,i} = \ln W_{n,i}.$$

Then

$$P_{n,i} = \ln \Theta_{n + 1 \mid n,i} - \ln W_{n,i}.$$

Theorem 7 --- Directional Enclosing-Multiplicity Identity

For a readable transition $i \rightarrow k$,

$\Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right)$.

Proof

Using

$$\Delta P = \ln\left( \frac{\Theta_{n + 1 \mid n,k}/W_{n,k}}{\Theta_{n + 1 \mid n,i}/W_{n,i}} \right)$$

and

$\Delta S = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right)$,

the local multiplicity factors cancel, leaving the enclosing multiplicity ratio.

**Theorem 8 --- Uniform Enclosing Extension Produces No Directional Possibility**

If two local macrostates have equal compatible enclosing extension multiplicity,

$$K_{n + 1 \mid n,i} = K_{n + 1 \mid n,k},$$

then

$$\Delta P_{n,i \rightarrow k} = 0.$$

Proof

By definition,

$$\Delta P_{n,i \rightarrow k} = \ln\left( \frac{K_{n + 1 \mid n,k}}{K_{n + 1 \mid n,i}} \right).$$

If the extension multiplicities are equal,

$$\Delta P_{n,i \rightarrow k} = \ln 1 = 0.$$

Conversely, for positive extension multiplicities,

$$\Delta P_{n,i \rightarrow k} = 0$$

implies

$$K_{n + 1 \mid n,i} = K_{n + 1 \mid n,k}.$$

Therefore, enclosing multiplicity supplies possibility while unequal enclosing compatibility supplies direction.

**Theorem 9 --- Reconstruction of Enclosing Multiplicity**

If the compatibility fibers

$$\left\{ \mathcal{E}_{n + 1 \mid n,i} \right\}_{i \in \mathcal{M}_{n}}$$

form a disjoint partition of the enclosing possibility domain, then

$\Theta_{n + 1} = \sum_{i}\Theta_{n + 1 \mid n,i}$.

Because

$$\Theta_{n + 1 \mid n,i} = W_{n,i}K_{n + 1 \mid n,i} = W_{n,i}e^{P_{n,i}},$$

it follows that

$\Theta_{n + 1} = \sum_{i}W_{n,i}e^{P_{n,i}}$.

The summation index is local, but every term is an enclosing multiplicity.

**Theorem 10 --- Multiplicity Invariance Under Realization**

Occurrence and occupancy do not change native multiplicity while the boundary classification remains fixed.

Proof

Multiplicity is

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|.$$

Changes in

$$\nu_{n,i}$$

or

$$c_{n,i}$$

do not change the classification map $\pi_{n}$ or its preimage unless the boundary itself is redefined. Therefore,

$$\delta W_{n,i} = 0$$

under realization within a fixed native landscape.

**Theorem 11 --- Exact Multiplicity Closure**

For any completed local return

$$i_{0} \rightarrow i_{1} \rightarrow \cdots \rightarrow i_{m} = i_{0},$$

the net entropic change is

$$\Delta S_{n,\mathcal{C}} = 0.$$

Proof

The multiplicity ratios telescope:

$\prod_{r = 0}^{m - 1}\frac{W_{n,i_{r + 1}}}{W_{n,i_{r}}} = 1$.

Taking the logarithm gives

$\sum_{r = 0}^{m - 1}\Delta S_{n,i_{r} \rightarrow i_{r + 1}} = 0$.

Thus possible local multiplicity closes exactly.

**Theorem 12 --- Asymmetric Possibility Need Not Close**

For

$$i \rightarrow k$$

under enclosing condition H,

$$\Delta P_{H} = \ln\left( \frac{K_{k}^{H}}{K_{i}^{H}} \right).$$

For the return

$$k \rightarrow i$$

under enclosing condition L,

$$\Delta P_{L} = \ln\left( \frac{K_{i}^{L}}{K_{k}^{L}} \right).$$

Therefore,

$$\Delta P_{\mathcal{C}} = \ln\left( \frac{K_{k}^{H}K_{i}^{L}}{K_{i}^{H}K_{k}^{L}} \right).$$

Thus,

$$\Delta S_{\mathcal{C}} = 0$$

does not imply

$$\Delta P_{\mathcal{C}} = 0.$$

Possibility closes only when

$$K_{k}^{H}K_{i}^{L} = K_{i}^{H}K_{k}^{L}.$$

**Theorem 13 --- Local Path Non-recoverability Under Recursive Carry**

Suppose two distinguishable local closures

$$\mathcal{C}_{n,a} \neq \mathcal{C}_{n,b}$$

are both compatible realizations of the same enclosing occurrence

$$\chi_{n + 1}^{(r)}.$$

Recursive carry classifies both according to that enclosing occurrence:

$$\kappa_{n}\left( \mathcal{C}_{n,a} \right) = \chi_{n + 1}^{(r)},$$

and

$$\kappa_{n}\left( \mathcal{C}_{n,b} \right) = \chi_{n + 1}^{(r)}.$$

Therefore,

$$\kappa_{n}^{-1}\left( \chi_{n + 1}^{(r)} \right)$$

contains more than one subordinate realization.

The enclosing occurrence alone therefore does not uniquely determine which peer-source closure or internal local path was realized. Thus, recursive carry can preserve count meaning while removing recoverable local path identity.

**Theorem 14 --- Occurrence-Count Loss Identity**

For an oriented two-leg closure, define

$$\eta_{n,a,\mathcal{C}} = \frac{\nu_{na,L}}{\nu_{n,a,H}},$$

with orientation chosen such that

$$0 < \eta_{n,a,\mathcal{C}} \leq 1.$$

The logarithmic occurrence-count loss is

$$L_{\tau,n,a,\mathcal{C}} = - {\ln\eta}_{n,a,\mathcal{C}}.$$

Because

$$0 < \eta_{n,a,\mathcal{C}} \leq 1,$$

it follows that

$$L_{\tau,n,a,\mathcal{C}} \geq 0.$$

Equality holds exactly when

$$\nu_{n,a,L} = \nu_{n,a,H}.$$

Thus,

$$L_{\tau,n,a,\mathcal{C}} = 0 \Longleftrightarrow \eta_{n,a,\mathcal{C}} = 1.$$

and

$$L_{\tau,n,a,\mathcal{C}} > 0 \Longleftrightarrow 0 < \eta_{n,a,\mathcal{C}} < 1.$$

**Theorem 15 --- Accumulated Count-Geometry Identity**

For positive adjacent recurrence ratios between $B_{n}$ and $B_{N}$,

$$\boxed{H_{N \mid n} = \ln\left\lbrack \frac{\left| \lambda_{N} \right|/\left| \lambda_{n} \right|}{\prod_{j = n}^{N - 1}\rho_{j + 1 \mid j}} \right\rbrack.}$$

If one recurrence-comparison domain jointly counts the recurrence classes across the chain, then

$$\prod_{j = n}^{N - 1}\rho_{j + 1 \mid j} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{N} \right)}{N_{\mathcal{D}_{R}}\left( \chi_{n} \right)},$$

and therefore

$$H_{N \mid n} = \ln\left( \frac{\left| \lambda_{N} \right|}{\left| \lambda_{n} \right|} \right) - \ln\left( \frac{N_{\mathcal{D}_{R}}\left( \chi_{N} \right)}{N_{\mathcal{D}_{R}}\left( \chi_{n} \right)} \right).$$

**Proof**

By Definition 37,

$$H_{N \mid n} = \Lambda_{N \mid n} - \Gamma_{N \mid n}.$$

Substituting the definitions of $\Lambda$ and $\Gamma$ gives the first expression. The second follows because the product of adjacent recurrence-count ratios telescopes when every ratio is defined over one common recurrence-comparison domain.

### A.4 Postulates of Recursive Realization

**Postulate 1 --- Proportional Occurrence Realization**

For a fixed realization relation at $B_{n}$, and for a sufficiently resolved realization domain, realized occurrence count proportionally realizes the native multiplicity landscape.

For readable macrostates $i$ and $k$,

$$\frac{\nu_{n,k}}{\nu_{n,i}} \approx \frac{W_{n,k}}{W_{n,i}}.$$

Equivalently,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k}.$$

This is a proportional relation, not an identity:

$$\nu_{n,i} \neq W_{n,i}.$$

The postulate states that native multiplicity determines the **relative occurrence-count structure** within a specified realization relation. It does not require vanishing local asymmetry:

$$\Delta A_{n,i \rightarrow k}\text{~}\text{need~not~equal}\text{~}0.$$

Local asymmetry enters separately through the occupancy-realization postulate:

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

Therefore, under proportional occurrence realization,

$$\boxed{\Delta G_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.}$$

Using

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k},$$

gives

$$\Delta G_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k}.$$

Thus, native multiplicity structures relative occurrence realization, while enclosing asymmetry biases the occupancy produced by that occurrence relation.

This distinction is central:

$$\begin{aligned}
\Delta S & \longrightarrow \text{relative~occurrence~structure}, \\
\Delta A & \longrightarrow \text{occupancy~bias}.
\end{aligned}$$

Postulate 1 therefore does not state that an enclosing directional bias changes the native relative occurrence-count relation itself.

**Postulate 2 --- Asymmetry-Biased Occupancy Realization**

For a readable transition

$$i \rightarrow k$$

at $B_{n}$, local asymmetry determines how the realized occurrence relation is expressed as occupancy. R²D postulates

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

Using

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k},$$

this becomes

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} - {R\Delta}_{n,i \rightarrow k}.$$

For a fixed occurrence relation,

$$\Delta\tau_{n,i \rightarrow k} = constant,$$

a change in enclosing-defined local asymmetry produces the corresponding change in relative occupancy:

$$\delta\left( \Delta G_{n,i \rightarrow k} \right) = \delta\left( \Delta A_{n,i \rightarrow k} \right).$$

This is the immediate local realization postulate of R²D.

It does not state that occupancy generates asymmetry. The causal ordering remains

$$\text{enclosing~compatibility~and~constraint} \Longrightarrow \Delta A_{n} \Longrightarrow \text{local~occupancy~realization}.$$

**Postulate 3 --- Finite-Count Directional Efficiency Under Asymmetric Closure**

A finite asymmetric closure can realize its opposed legs with unequal occurrence-count efficiency. For a binary local realization with finite positive counts

$$N_{i} > 0,\quad\quad N_{k} > 0,$$

define the opposed finite-count realization factors

$$\epsilon_{H} = \frac{N_{i}}{N_{k} + 1},$$

and

$$\epsilon_{L} = \frac{N_{k}}{N_{i} + 1}.$$

Their product is

$$\epsilon_{H}\epsilon_{L} = \frac{N_{i}N_{k}}{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}.$$

For finite positive counts,

$$0 < \epsilon_{H}\epsilon_{L} < 1.$$

This inequality is a derived finite-count result. R²D postulates that under asymmetric closure this product gives the directional occurrence-count efficiency of the completed cycle:

$$\eta_{n,a,\mathcal{C}} = \epsilon_{H}\epsilon_{L}.$$

Thus,

$$\frac{\nu_{n,a,L}}{\nu_{n,a,H}} = \frac{N_{i}N_{k}}{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}.$$

The corresponding logarithmic occurrence-count loss is then, by the occurrence-count loss theorem,

$$L_{\tau,n,a,\mathcal{C}} = - {\ln\eta}_{n,a,\mathcal{C}}.$$

or

$$L_{\tau,n,a,\mathcal{C}} = \ln\left\lbrack \frac{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}{N_{i}N_{k}} \right\rbrack.$$

The finite-count product is derived. Its identification with directional occurrence-count efficiency is postulated. No count destruction is implied. The postulate states that finite asymmetric realization produces nonreciprocal occurrence-count efficiency around closure.

**Postulate 4 --- The R2D Law**

Consider one realized enclosing occurrence associated with readable transition

$$\chi_{n + 1}:j \rightarrow k.$$

The enclosing occurrence defines the compatible peer closures through which it is locally realized:

$$\chi_{n + 1}^{(r)} \Rightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

Let

$$\mathcal{C}_{n,a}$$

be one representative peer closure from an equivalent peer class associated with that enclosing occurrence.

Its net closure asymmetry is

$$\Delta A_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - \Delta R_{n,a,\mathcal{C}}.$$

Within a common recurrence-comparison domain $\mathcal{D}_{R}$, define

$$\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}.$$

At $B_{n + 1}$, the same recursively organized occurrence is read through distinguishability

$$\lambda_{n + 1}$$

and total enclosing constraint

$$C_{n + 1} = C_{n + 1}^{out} + C_{n + 1}^{\Phi}.$$

R2D postulates

$$\boxed{\Delta A_{n,a,\mathcal{C}} = \left( C_{n + 1}^{out} + C_{n + 1}^{\Phi} \right)\lambda_{n + 1}\rho_{n + 1 \mid n,a}.}$$

Equivalently,

$$\boxed{\Delta P_{n,a,\mathcal{C}} - \Delta R_{n,a,\mathcal{C}} = C_{n + 1}\lambda_{n + 1}\rho_{n + 1 \mid n,a}.}$$

Or, without forming the ratio,

$$\boxed{\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).}$$

The two sides are different boundary-specific count expressions. On the left, closure asymmetry contains local retention defined only by the productive component of enclosing constraint. On the right, the full enclosing constraint, including both productive and background-associated components, multiplies enclosing distinguishability and enclosing recurrence.

The postulate therefore does **not** state

$$\mathcal{C}_{n,a} \Rightarrow \chi_{n + 1}^{(r)}.$$

The causal relation is instead

$$\chi_{n + 1}^{(r)} \Rightarrow \mathcal{C}_{n,a}.$$

Recursive carry,

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)},$$

is the complementary cross-boundary reclassification.

The R2D law postulates an invariant recurrence-weighted relation between these two boundary-specific readings of one recursively organized occurrence. It assigns no physical time unit to either recurrence count.

If the relevant peer closures are not equivalent, the peer index $a$ must remain explicit and no representative-peer reduction is assumed.

**Postulate 5 --- The Second Law of Recursive Counting**

For an oriented representative peer closure, occurrence-count loss is defined by

$$L_{\tau,n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right) \geq 0.$$

This relation is derived from the definition of directional occurrence-count efficiency and is not itself the second-law postulate.

Let

b~n+1~^-^

and

b~n+1~^+^

be the enclosing background counts before and after the corresponding realization relation, with

δ~C~ Φ~n+1~ = ln(b~n+1~^+^/b~n+1~^-^).

R²D postulates

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

Therefore,

$$\delta_{\mathcal{C}}\Phi_{n + 1} = - \Delta\tau_{n,a,\mathcal{C}} \geq 0.$$

This equality is between logarithmic count coordinates.

It does not assert arithmetic equality between raw occurrence counts and raw background counts.

Rather, the postulate identifies two boundary-specific readings of one recursively organized realization:

$$\begin{aligned}
B_{n,a}: & \quad\text{unequal~directional~occurrence-count~efficiency}, \\
B_{n + 1}: & \quad\text{background~increment}.
\end{aligned}$$

Thus,

$$\text{occurrence-count~loss~at~the~representative~peer}\mspace{6mu} \longleftrightarrow \mspace{6mu}\text{enclosing~background~increment}.$$

Nothing is destroyed. The primitive irreversible relation is the correspondence between nonreciprocal local occurrence-count realization and enclosing nondirectional background.

The quantitative relation between

$$C_{n + 1}^{\Phi}\lambda_{n + 1}$$

and

$$\delta_{\mathcal{C}}\Phi_{n + 1}$$

is not separately postulated in Part I.

**Postulate 6 --- Terminal Limits and Causal Orientation**

R²D postulates a lower and upper realized limit to the recursive hierarchy. The smallest realized boundary is

$$B_{\alpha}.$$

It defines primitive distinguishable recurrence within the realized hierarchy. No realized subordinate boundary

$$B_{\alpha - 1}$$

is required.

The largest presently realized boundary is

$$B_{\omega}.$$

Its realized macrostate path is open:

$$\mathcal{O}_{\omega}:i_{\omega,0} \rightarrow i_{\omega,1} \rightarrow \cdots \rightarrow i_{\omega,m},$$

with

$$i_{\omega,m} \neq i_{\omega,0}.$$

Therefore,

$$\mathcal{O}_{\omega} \neq \mathcal{C}_{\omega}.$$

No completed terminal closure exists for recursive reclassification into a presently realized :

$$\mathcal{C}_{\omega}\overset{\kappa_{\omega}}{\mapsto}B_{\omega + 1}\quad\text{is~not~defined~within~the~presently~realized~hierarchy}.$$

For every nonterminal boundary,

$$B_{n} < B_{\omega},$$

local directional asymmetry is defined by an enclosing relation:

$$\Delta A_{n} = \Delta P_{n} - {\Delta R}_{n}.$$

At $B_{\omega}$, no further realized enclosing boundary is available from which to define the terminal orientation by another relation. R²D therefore postulates that the unresolved nonclosure of the open terminal path supplies the causal orientation of the realized hierarchy.

Denote this unresolved terminal asymmetry by

$${\Delta A}_{\omega,\mathcal{O}}.$$

It is not defined as

$${\Delta P}_{\omega} - {\Delta R}_{\omega},$$

because that would require a presently realized $\mathcal{C}_{\omega}$.

Thus,

$$\text{terminal~}\text{nonclosure} \Longrightarrow \text{causal~orientation~of~subordinate~enclosing~relations}.$$

The lower and upper limits therefore have different roles:

$$B_{\alpha} = \text{primitive~recurrence},$$

while

$$B_{\omega} = \text{terminal~open~realization}.$$

Local closure provides the recurring realization structure of the hierarchy.

Terminal nonclosure supplies its unresolved causal orientation.

### A.5 Corollaries and Derived Consequences

**Corollary 1 --- Constrained Occupancy Relation**

From the definition of local asymmetry,

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k},$$

and the asymmetry-biased occupancy-realization postulate,

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k},$$

it follows that

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k}.$$

Thus, relative occupancy is determined by the realized occurrence relation together with enclosing-defined possibility and retention. This relation is exact conditional on Postulate 2.

**Corollary 2 --- Occupancy Under Proportional Realization**

Under proportional realization,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k}.$$

Therefore,

$$\Delta G_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k}.$$

Using the directional enclosing-multiplicity identity,

$$\Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right),$$

gives

$$\Delta G_{n,i \rightarrow k} \approx \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right) - {\Delta R}_{n,i \rightarrow k}.$$

Equivalently,

$$\frac{c_{n,k}}{c_{n,i}} \approx \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}}e^{- R_{n,i \rightarrow k}}.$$

In the absence of retention,

$${\Delta R}_{n,i \rightarrow k} = 0,$$

so

$$\frac{c_{n,k}}{c_{n,i}} \approx \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}}.$$

Thus, in the proportional-realization limit, relative local occupancy reproduces the relative enclosing multiplicity compatible with the local alternatives.

This is the formal meaning of the statement: **possibility pulls occupancy**.

The causal meaning is enclosing-to-local: unequal enclosing compatibility defines the local occupancy bias.

**Corollary 3 --- Mode-Exchange Relation**

At the threshold between two candidate structural macrostates $i$ and $k$,

$$c_{n,i} = c_{n,k}.$$

Therefore,

$$\Delta G_{n,i \rightarrow k} = 0.$$

By Postulate 2,

$$\Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k} = 0.$$

Hence,

$$\Delta A_{n,i \rightarrow k} = - \Delta\tau_{n,i \rightarrow k}.$$

Under proportional realization,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k},$$

so

$$\Delta A_{n,i \rightarrow k} \approx - \Delta S_{n,i \rightarrow k}.$$

Using

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - {\Delta R}_{n,i \rightarrow k},$$

the mode-exchange condition becomes

$${\Delta R}_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k} + \Delta P_{n,i \rightarrow k}.$$

Therefore,

$$\Delta R_{n,i \rightarrow k} \approx \ln\left( \frac{\Theta_{n + 1 \mid n,k}}{\Theta_{n + 1 \mid n,i}} \right).$$

Local structural exchange occurs when retention offsets the complete enclosing-compatible multiplicity difference between the competing states.

**Corollary 4 --- Possible Multiplicity Closure Does Not Imply Reciprocal Occurrence Realization**

For every completed local closure,

$$\Delta S_{n,a,\mathcal{C}} = 0.$$

When

$$L_{\tau,n,a,\mathcal{C}} > 0,$$

we have

$$\Delta S_{n,a,\mathcal{C}} = 0$$

Thus, exact possible-count closure does not imply reciprocal occurrence-count realization. Multiplicity and occurrence therefore have distinct closure conditions.

The distinction is possible multiplicity can close exactly while occurrence-count efficiency need not be reciprocal.

**Corollary 5 --- The Second-Law Background Increment Is Nonnegative**

From the occurrence-count loss theorem,

$$L_{\tau,n,a,\mathcal{C}} \geq 0.$$

Postulate 5 gives

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

Therefore,

$$\delta_{\mathcal{C}}\Phi_{n + 1} \geq 0.$$

Moreover,

$$\delta_{\mathcal{C}}\Phi_{n + 1} = 0$$

if and only if

$$L_{\tau,n,a,\mathcal{C}} = 0,$$

which occurs if and only if

$$\eta_{n,a,\mathcal{C}} = 1.$$

Thus,

$$\delta_{\mathcal{C}}\Phi_{n + 1} = 0 \Longleftrightarrow \eta_{n,a,\mathcal{C}} = 1,$$

and

$$\delta_{\mathcal{C}}\Phi_{n + 1} > 0 \Longleftrightarrow 0 < \eta_{n,a,\mathcal{C}} < 1.$$

A positive background increment is therefore the enclosing reading of nonreciprocal occurrence-count efficiency at the representative peer closure.

**Corollary 6 --- Distinguishability Does Not Require Productive Constraint**

Distinguishability is defined by the readable interval

$$\lambda_{n + 1}.$$

Its existence is not defined by productive constraint. Therefore,

$$C_{n + 1}^{out} = 0 \not\Rightarrow \lambda_{n + 1} = 0.$$

If background-associated constraint remains nonzero,

$$C_{n + 1}^{\Phi} > 0,$$

then the R2D law becomes

$$\Delta A_{n,a,\mathcal{C}} = C_{n + 1}^{\Phi}\lambda_{n + 1}\rho_{n + 1 \mid n,a}.$$

Thus zero productive constraint does not imply zero enclosing distinguishability or zero recursive realization. Productive constraint is the component that defines local retention and whose enclosing read remains distinguishable output; it does not define whether enclosing distinguishability itself exists.

**Corollary 7 --- Representative-Peer Invariance of the R2D Relation**

Let peer closures

$$\mathcal{C}_{n,a}$$

and

$$\mathcal{C}_{n,b}$$

belong to the same equivalent peer class relative to one enclosing transition class $\chi_{n + 1}$.

Applying the R2D law to representative peer $a$ gives

$$\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right),$$

and to representative peer $b$,

$$\Delta A_{n,b,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,b} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).$$

Therefore,

$$\boxed{\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = \Delta A_{n,b,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,b} \right).}$$

Equivalently, for positive recurrence ratios,

$$\boxed{\frac{\Delta A_{n,a,\mathcal{C}}}{\rho_{n + 1 \mid n,a}} = \frac{\Delta A_{n,b,\mathcal{C}}}{\rho_{n + 1 \mid n,b}} = C_{n + 1}\lambda_{n + 1}.}$$

Thus equivalent representative peer closures share the same recurrence-weighted R2D relation. No sum or average over peers is implied. The result does not apply to peers that are nonequivalent under the enclosing compatibility relation.

**Corollary 8 --- Stable Enclosing Compatibility Produces Deterministic Peer Correlation**

Let the compatible joint peer-closure relation associated with repeated realizations of enclosing occurrence $\chi$ satisfy

$$\mathfrak{D}_{n + 1,\chi}^{(1)} = \mathfrak{D}_{n + 1,\chi}^{(2)} = \cdots.$$

Then the same classes of peer realizations remain jointly compatible across repeated occurrences. Therefore,

$$\text{stable~enclosing~compatibility} \Longrightarrow \text{persistent~correlation~among~peer~realizations}.$$

R²D identifies this stable within-scale correlation as deterministic law. The correlated peer realizations need not directly cause one another. Their common organization is supplied by the enclosing occurrence relation.

**Corollary 9 --- Background Is Not a Third Directed Coordinate**

Across-boundary readability geometry is defined by two recursively comparable relations: distinguishability scaling and recurrence scaling. The latter is built from the adjacent recurrence ratios

$$\rho_{j + 1 \mid j}.$$

Background is nondirectional within the boundary at which it is background:

$$\Delta\Phi_{n,i \rightarrow k} = 0.$$

Occurrence-count loss may be related to a background increment through

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}},$$

but neither $L_{\tau}$ nor $\Phi$ is independently inserted into the accumulated horizon geometry

$$H_{N \mid n} = \Lambda_{N \mid n} - \Gamma_{N \mid n}.$$

Thus background is not a third directed recurrence coordinate. It is the nondirectional enclosing read of nonreciprocal occurrence realization under the Second Law.

**Corollary 10 --- Two Opposite Readability Horizons**

From the accumulated count-geometry identity,

$$H_{N \mid n} = \Lambda_{N \mid n} - \Gamma_{N \mid n},$$

with

$$\Lambda_{N \mid n} = \ln\left( \frac{\left| \lambda_{N} \right|}{\left| \lambda_{n} \right|} \right)$$

and

$$\Gamma_{N \mid n} = \sum_{j = n}^{N - 1}\ln\rho_{j + 1 \mid j}.$$

The distinguishability-dominant limit is

$$H_{N \mid n} \rightarrow + \infty.$$

When distinguishability remains readable while recursive recurrence becomes unresolved, this defines the distinguishability horizon.

The recurrence-dominant limit is

$$H_{N \mid n} \rightarrow - \infty.$$

When recurrence remains readable while distinguishability becomes unresolved, this defines the recurrence horizon.

At finite relative geometry,

$$\left| H_{N \mid n} \right| < \infty,$$

both relations may remain readable. When they do, closure remains jointly readable.

A mathematical limit alone is not sufficient. The appropriate boundary-relative readability condition must also be satisfied.

**Corollary 11 --- Passive Turbine Architecture**

At every nonterminal boundary, the enclosing occurrence defines the compatible local closure:

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,g}.$$

The local multiplicity landscape determines how that occurrence can be realized through closure.

Recursive carry gives the complementary count reading:

$$\mathcal{C}_{n,g}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

The latter is reclassification, not reverse causation. Thus, enclosing relation determines why, and recursive carry determines how the completed realization is read across boundaries. The turbine is therefore locally active while remaining causally passive with respect to the origin of the enclosing occurrence and its direction.


## Appendix B — Worked Example: Recursive Counting in a Coin Ensemble

---
r2d_id: "canon-p1-app-b"
title: "Part I — Appendix B: Worked Coin Example"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 173
pdf_page_end: 194
semantic_amendment: "2026-09-25-causal-architecture-logical-status"
review_status: "authoritative"
---
# Appendix B — Worked Example: Recursive Counting in a Coin Ensemble

### B.0 Purpose

The coin ensemble provides a finite exact construction of boundary-indexed recursive counting.

The example is not a model of the mechanics of a physical coin toss. No probability, force, energy, trajectory, physical space, or physical time is assumed. The coins supply only finite distinguishable states whose compatible multiplicities can be counted exactly.

The purpose of the construction is to separate four relations that are easily conflated: **possible structure, realization, recursive replacement, and enclosing compatibility.** Three adjacent count levels are used.

At $B_{n - 1}$, one coin has two readable states:

$$H,\quad\quad T.$$

At , $B_{n}$ ten peer $B_{n - 1}$ boundaries are replaced by one new eleven-state multiplicity landscape.

At , $B_{n + 1}$ ten peer $B_{n}$ landscapes are replaced by one new enclosing landscape.

Thus, the recursion is

$$10 \times B_{n - 1} \longrightarrow B_{n},\quad\quad 10 \times B_{n} \longrightarrow B_{n + 1}$$

The second step is especially important.

$B_{n + 1}$ does **not** directly count one hundred unreplaced H/T states. It counts ten already-defined $B_{n}$ landscapes. The fact that the resulting enclosing multiplicity can be written in the familiar closed form

$$\binom{100}{J}$$

is a combinatorial identity obtained from the recursive composition of those ten landscapes. It does not restore the one hundred individual coin states as primitive states at $B_{n + 1}$.

### B.1 The Primitive Coin Boundary

For this construction, $B_{n - 1}$ is taken as the primitive subordinate coin boundary.

At one peer boundary $B_{n - 1,a}$,

$$\mathcal{M}_{n - 1,a} = \left\{ H,T \right\}.$$

No nontrivial entropic landscape is assigned beneath the individual coin.

Now let $B_{n}$ contain ten peer coin boundaries:

$$\left\{ B_{n - 1,a} \right\}_{a = 1}^{10}.$$

One joint realization of those peers is

$$\mu_{n} = \left( x_{n - 1,1},x_{n - 1,2},\ldots,x_{n - 1,10} \right),\quad\quad x_{n - 1,a} \in \left\{ H,T \right\}.$$

The unrestricted formal microstate domain is therefore:

$$\mathfrak{M}_{n} = \left\{ H,T \right\}^{10}.$$

Boundary $B_{n}$does not retain the ten binary state spaces as ten separate readable macrostate systems. It defines a new whole-system classification. Let

$$i = N_{T}$$

be the total number of tails in the joint realization. Then

$$i \in \left\{ 0,1,\ldots,10 \right\}.$$

The readable macrostate set at $B_{n}$is

$$\mathcal{M}_{n} = \left\{ 0,1,\ldots,10 \right\}.$$

Thus, ten two-state peer boundaries have not become twenty macrostates. They have been replaced by one eleven-state landscape.

$$10 \times \left\{ H,T \right\} \neq \mathcal{M}_{n}.$$

Rather,

$$\left\{ B_{n - 1,a} \right\}_{a = 1}^{10} \longrightarrow \mathcal{M}_{n} = \left\{ 0,\ldots,10 \right\}.$$

The eleven-state landscape belongs to $B_{n}$.

**B.2 Formal Microstates and the **$B_{n}$**Multiplicity Landscape**

Boundary $B_{n}$classifies each formal microstate by

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}$$

with

$$\pi_{n}\left( \mu_{n} \right) = N_{T}\left( \mu_{n} \right).$$

For example,

$$\mu_{n} = (H,H,T,H,T,T,H,H,T,H)$$

is one formal microstate and satisfies

$$\pi_{n}\left( \mu_{n} \right) = 4.$$

The multiplicity of macrostate $i$ is therefore

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right| = \binom{10}{i}.$$

Its logarithmic coordinate is

$$S_{n,i} = \ln W_{n,i} = \ln\binom{10}{i}.$$

The native multiplicity landscape is

$$\mathcal{W}_{n} = \left\{ \binom{10}{i} \right\}_{i = 0}^{10}.$$

The total multiplicity is

$$\Theta_{n} = \left| \mathfrak{M}_{n} \right| = 2^{10}.$$

The mutually exclusive macrostate fibers partition the formal microstate domain:

$$2^{10} = \sum_{i = 0}^{10}\binom{10}{i}.$$

This displays the two primitive count operations: compatible possibilities multiply while mutually exclusive alternatives add.

The ten binary peer domains compose multiplicatively:

$$2^{10} = \prod_{a = 1}^{10}{2.}$$

The resulting mutually exclusive whole-system states add:

$$\Theta_{n} = \sum_{i = 0}^{10}W_{n,i}.$$

The whole is therefore not the arithmetic sum of ten-coin state spaces. It is a newly classified multiplicity of compatible joint realizations.

### B.3 Realization Does Not Create the Multiplicity Landscape

The distinction between possible structure and realization can now be made exact. Before any particular joint realization occurs,

$$W_{n,i} = \binom{10}{i}$$

is already fixed by the boundary-defined classification. For example,

$$W_{n,0} = 1,$$

whereas

$$W_{n,5} = 252.$$

A transition of one subordinate coin may change which formal microstate is realized and may therefore change which macrostate is occupied. It does not change either of these multiplicities. Thus

$$\text{subordinate~transition} \longrightarrow \text{change~of~realization},$$

but

$$\text{subordinate~transition}\not\longrightarrow\text{creation~of~}W_{n,i}.$$

The multiplicity landscape belongs to the boundary-defined possibility domain. The subordinate events realize that landscape. They do not generate it. This is the first causal distinction exposed by the coin construction.

### B.4 Boundary-Relative Transitions

At peer boundary $B_{n - 1,a}$,

$$H_{a} \rightarrow T_{a}$$

is a readable macrostate transition. Relative to $B_{n}$, however, the same change is a transition between formal microstates:

$$\mu_{n} = \left( x_{1},\ldots,H_{a},\ldots,x_{10} \right)$$

to

$$\mu_{n}' = \left( x_{1},\ldots,T_{a},\ldots,x_{10} \right).$$

Hence

$$\mu_{n} \rightarrow \mu_{n}'$$

is a microstate transition relative to $B_{n}$.

If the initial formal microstate contains $i$ tails, $B_{n}$ reads the consequence

$$i \rightarrow i + 1.$$

It need not read which peer supplied the transition. Therefore,

$$\text{macrostate~transition~at~}B_{n - 1,a} = \text{microstate~transition~relative~to~}B_{n}.$$

Resolving the subordinate transition changes the count boundary.

It does not reveal the same transition at finer resolution while preserving the same state classification.

**B.5 Native Direction Within the **$B_{n}$**Landscape**

Consider the adjacent $B_{n}$ transition

$$i \rightarrow i + 1.$$

The native multiplicity ratio is

$$\frac{W_{n,i + 1}}{W_{n,i}} = \frac{\binom{10}{i + 1}}{\binom{10}{i}} = \frac{10 - i}{i + 1}.$$

Therefore,

$$\Delta S_{n,i \rightarrow i + 1} = \ln\left( \frac{10 - i}{i + 1} \right).$$

For

$$5 \rightarrow 6,$$

this gives

$$\Delta S_{n,5 \rightarrow 6} = \ln\left( \frac{5}{6} \right) < 0.$$

The native $B_{n}$ landscape therefore contains greater multiplicity at $i = 5$ than at $i = 6$.

Nothing about this result refers yet to an enclosing boundary.

**B.6 The Second Replacement: Ten **$B_{n}$** Landscapes Define **$B_{n + 1}$

Now introduce ten equivalent peer $B_{n}$ boundaries:

$$\left\{ B_{n,a} \right\}_{a = 1}^{10}.$$

Each peer has its own eleven-state landscape

$$\mathcal{M}_{n,a} = \left\{ 0,\ldots,10 \right\},$$

with

$$W_{n,a,i_{a}} = \binom{10}{i_{a}}.$$

At this point the individual $H/T$ states at $B_{n - 1}$ have already been replaced as the readable state classification of each $B_{n}$ peer. The objects entering the next recursive composition are therefore **ten **$B_{n}$** landscapes**, not one hundred individually readable coins.

Let the enclosing boundary classify a joint peer macrostate tuple

$$\left( i_{1},i_{2},\ldots,i_{10} \right)$$

by

$$J = \sum_{a = 1}^{10}i_{a}.$$

Then

$$J \in \left\{ 0,1,\ldots,100 \right\},$$

and

$$\mathcal{M}_{n + 1} = \left\{ 0,1,\ldots,100 \right\}.$$

This is another replacement:

$$10 \times \mathcal{M}_{n} \longrightarrow \mathcal{M}_{n + 1}.$$

The enclosing state $J$ is a new classification of the ten $B_{n}$ peer states. It is not a direct re-reading of one hundred primitive $H/T$ variables.

### B.7 Enclosing Multiplicity Is a Sum of Compatible Products

For one specified peer-state tuple

$$\left( i_{1},\ldots,i_{10} \right),$$

the multiplicities of the ten compatible $B_{n}$ landscapes multiply:

$$W_{tuple} = \prod_{a = 1}^{10}W_{n,a,i_{a}} = \prod_{a = 1}^{10}\binom{10}{i_{a}}.$$

An enclosing macrostate $J$ permits every mutually exclusive peer-state tuple satisfying

$$i_{1} + \cdots + i_{10} = J.$$

Those alternatives add. Therefore, the enclosing multiplicity is defined recursively as

$$W_{n + 1,J} = \sum_{\begin{array}{r}
i_{1} + \cdots + i_{10} = J
\end{array}}{\prod_{a = 1}^{10}W_{n,a,i_{a}}}.$$

For the ten equivalent coin landscapes,

$$W_{n + 1,J} = \sum_{\begin{array}{r}
i_{1} + \cdots + i_{10} = J
\end{array}}{\prod_{a = 1}^{10}\binom{10}{i_{a}}}.$$

The multivariate Vandermonde identity then gives

$$W_{n + 1,J} = \binom{100}{J}.$$

The logical order matters. The primitive recursive definition is

$$W_{n + 1,J} = \sum_{\text{compatible~}B_{n}\text{~tuples}}{\prod_{a}W_{n,a,i_{a}}}.$$

The expression

$$\binom{100}{J}$$

is its closed-form evaluation.

It does **not** mean that $B_{n + 1}$ has restored one hundred unreplaced coin states as its primitive constituents. Thus, recursive replacement preserves the correct count consequence without preserving subordinate state identity. Subordinate identity is replaced. Subordinate multiplicity remains consequential. The total unrestricted multiplicity follows in the same way:

$$\Theta_{n + 1} = \prod_{a = 1}^{10}\Theta_{n,a} = \left( 2^{10} \right)^{10} = 2^{100}.$$

Again, $2^{100}$ is the result of recursively multiplying ten $B_{n}$ landscape multiplicities.

**B.8 A Representative  **$\mathbf{B}_{\mathbf{n}}$ **Landscape Inside **$\mathbf{B}_{\mathbf{n + 1}}$

Select one representative peer $g$ and let its local macrostate be $i$.

For fixed enclosing state $J$, the other nine $B_{n}$ landscapes must jointly satisfy

$$\sum_{a \neq g}i_{a} = J - i.$$

The compatible enclosing multiplicity associated with local state $i$ is therefore

$$\Theta_{n + 1 \mid n,g,i}^{(J)} = W_{n,g,i}\sum_{\begin{array}{r}
\sum_{a \neq g}i_{a} = J - i
\end{array}}{\prod_{a \neq g}W_{n,a,i_{a}}}.$$

Using

$$W_{n,a,i_{a}} = \binom{10}{i_{a}},$$

gives

$$\Theta_{n + 1 \mid n,g,i}^{(J)} = \binom{10}{i}\sum_{\begin{array}{r}
\sum_{a \neq g}i_{a} = J - i
\end{array}}{\prod_{a \neq g}\binom{10}{i_{a}}}.$$

The nine-landscape sum evaluates by Vandermonde to

$$\binom{90}{J - i}.$$

Hence

$$\Theta_{n + 1 \mid n,g,i}^{(J)} = \binom{10}{i}\binom{90}{J - i}.$$

Again, the factor

$$\binom{90}{J - i}$$

is the closed-form count of the compatible compositions of **nine **$B_{n}$** landscapes**.

It should not be interpreted as $B_{n + 1}$ directly resolving ninety individual coins.

The compatible enclosing extension multiplicity per local possibility is

$$K_{n + 1 \mid n,g,i}^{(J)} = \frac{\Theta_{n + 1 \mid n,g,i}^{(J)}}{W_{n,g,i}}.$$

Therefore,

$$K_{n + 1 \mid n,g,i}^{(J)} = \binom{90}{J - i}.$$

and

$$P_{n,g,i}^{(J)} = \ln\binom{90}{J - i}.$$

Possibility is therefore not the native size of the selected $B_{n}$ macrostate. It is the logarithmic multiplicity of compatible enclosing realization available per local possibility.

### B.9 Uniform Enclosing Extension Produces No Direction

Remove the restriction to one fixed enclosing macrostate $J$. For every formal possibility belonging to the selected $B_{n}$ peer, the other nine $B_{n}$ landscapes are unrestricted. Therefore,

$$K_{n + 1 \mid n,g,i} = \prod_{a \neq g}\Theta_{n,a}.$$

Since

$$\Theta_{n,a} = 2^{10},$$

we obtain

$$K_{n + 1 \mid n,g,i} = \left( 2^{10} \right)^{9} = 2^{90}$$

for every $i$. Therefore,

$$P_{n,g,i} = 90\ln 2$$

for every $i$, and

$$\Delta P_{n,g,i \rightarrow k} = 0.$$

Thus, large enclosing multiplicity alone does not create direction. Direction requires unequal enclosing compatibility:

$$K_{n + 1 \mid n,g,i} \neq K_{n + 1 \mid n,g,k}.$$

### B.10 Directional Possibility Under a Fixed Enclosing State

For the adjacent local alternative

$$i \rightarrow i + 1$$

under fixed enclosing state $J$,

$$\Delta P_{n,g,i \rightarrow i + 1}^{(J)} = \ln\left( \frac{K_{n + 1 \mid n,g,i + 1}^{(J)}}{K_{n + 1 \mid n,g,i}^{(J)}} \right).$$

Using the exact extension multiplicities,

$$\Delta P_{n,g,i \rightarrow i + 1}^{(J)} = \ln\left\lbrack \frac{\binom{90}{J - i - 1}}{\binom{90}{J - i}} \right\rbrack.$$

Therefore,

$$\Delta P_{n,g,i \rightarrow i + 1}^{(J)} = \ln\left( \frac{J - i}{91 - J + i} \right).$$

This is an exact enclosing-defined directional count difference. No realization postulate has been used.

### B.11 Exact Reversal of Native Local Bias

Let

$$J = 60$$

and consider the local transition

$$5 \rightarrow 6.$$

The native $B_{n}$landscape gives

$$\Delta S_{n,5 \rightarrow 6} = \ln\left( \frac{5}{6} \right) \approx - 0.1823.$$

The native landscape therefore favors $i = 5$.

The enclosing compatibility difference is

$$\Delta P_{n,5 \rightarrow 6}^{(60)} = \ln\left( \frac{55}{36} \right) \approx 0.4238.$$

The enclosing relation therefore favors $i = 6$.

The complete compatible-count difference is

$$\Delta S + \Delta P = \ln\left( \frac{5}{6} \right) + \ln\left( \frac{55}{36} \right),$$

so

$$\Delta S + \Delta P = \ln\left( \frac{275}{216} \right) \approx 0.2415 > 0.$$

Equivalently,

$$\frac{\Theta_{n + 1 \mid n,6}^{(60)}}{\Theta_{n + 1 \mid n,5}^{(60)}} = \frac{275}{216} > 1.$$

**Thus, native** $\mathbf{B}_{\mathbf{n}}$ **multiplicity favors 5 while enclosing-compatible multiplicity favors 6.**

Nothing about

$$W_{n,i} = \binom{10}{i}$$

has changed.

Only the enclosing compatibility relation has changed.

**Therefore, changing only enclosing compatibility can create, eliminate, or reverse local directional possibility.**

This is an exact combinatorial result.

It also strengthens the separation between structure and realization. The subordinate transition neither creates the native landscape nor defines the enclosing relation capable of reversing its directional significance.

### B.12 Reconstruction of the Fixed Enclosing State

The compatibility fibers associated with one selected $B_{n}$ peer partition the fixed enclosing macrostate $J$. Therefore,

$$W_{n + 1,J} = \sum_{i}\Theta_{n + 1 \mid n,i}^{(J)}.$$

For the coin construction,

$$\binom{100}{J} = \sum_{i}\binom{10}{i}\binom{90}{J - i}.$$

Because

$$e^{P_{n,i}^{(J)}} = \binom{90}{J - i},$$

the same identity is

$$W_{n + 1,J} = \sum_{i}W_{n,i}e^{P_{n,i}^{(J)}}.$$

The enclosing state is reconstructed from mutually exclusive local classifications multiplied by their compatible enclosing extensions.

B.13 Productive Constraint and Occupancy: The First R2D Realization Postulate

Everything above is exact combinatorics. Now introduce an R²D realization relation. For

$$5 \rightarrow 6,$$

choose

$$\lambda_{n,5 \rightarrow 6} = 1.$$

Let the productive component of enclosing constraint satisfy

$$C_{n + 1}^{out} \geq 0$$

This productive component defines retention across the distinguishable step:

$$\Delta R_{n,5 \rightarrow 6} = C_{n + 1}^{out}\lambda_{n,5 \rightarrow 6}.$$

Hence

$$\Delta R_{n,5 \rightarrow 6} = C_{n + 1}^{out}.$$

The local transition asymmetry is

$$\Delta A_{n,5 \rightarrow 6} = \Delta P_{n,5 \rightarrow 6}^{(60)} - \Delta R_{n,5 \rightarrow 6}.$$

R²D then postulates

$$\Delta G_{n,5 \rightarrow 6} = \Delta\tau_{n,5 \rightarrow 6} + \Delta A_{n,5 \rightarrow 6}.$$

Under proportional occurrence realization,

$$\Delta\tau_{n,5 \rightarrow 6} \approx \Delta S_{n,5 \rightarrow 6}.$$

Therefore,

$$\Delta G_{n,5 \rightarrow 6} \approx \Delta S_{n,5 \rightarrow 6} + \Delta P_{n,5 \rightarrow 6}^{(60)} - \Delta R_{n,5 \rightarrow 6}.$$

For the unit distinguishability chosen here,

$$\Delta G_{n,5 \rightarrow 6} \approx \ln\left( \frac{275}{216} \right) - C_{n + 1}^{out}.$$

Thus

$$\frac{c_{n,6}}{c_{n,5}} \approx \frac{275}{216}e^{- C_{n + 1}^{out}}.$$

The combinatorics determine the enclosing-compatible bias. The productive constraint determines local retention, while the occupancy response remains an R2D realization prediction.

### B.14 Local Closure Under Changing Enclosing Compatibility

Now consider the local return

$$\mathcal{C}_{n,g}:5 \rightarrow 6 \rightarrow 5.$$

Let the forward leg occur under

$$J_{H} = 60.$$

Then

$$\Delta P_{H} = \ln\left( \frac{55}{36} \right).$$

Let the return leg occur under

$$J_{L} = 40.$$

For the reverse transition $6 \rightarrow 5$,

$$\Delta P_{L} = \ln\left( \frac{56}{35} \right).$$

The accumulated enclosing possibility difference around the local closure is therefore

$$\Delta P_{n,g,\mathcal{C}} = \Delta P_{H} + \Delta P_{L},$$

giving

$$\Delta P_{n,g,\mathcal{C}} = \ln\left( \frac{55}{36}\frac{56}{35} \right) = \ln\left( \frac{154}{63} \right) > 0.$$

The native $B_{n}$ multiplicity closes exactly:

$$\Delta S_{n,g,\mathcal{C}} = \ln\left( \frac{5}{6} \right) + \ln\left( \frac{6}{5} \right),$$

so

$$\Delta S_{n,g,\mathcal{C}} = 0.$$

Thus,

$$\Delta S_{n,g,\mathcal{C}} = 0\quad\quad\text{while}\quad\quad\Delta P_{n,g,\mathcal{C}} > 0.$$

The local landscape returns. The enclosing compatibility relation does not compose with its reciprocal. This is exact combinatorics. If retention is also specified around the closure, define

$$\Delta R_{n,g,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,g}}\Delta R_{n,g,\chi}$$

and

$$\Delta A_{n,g,\mathcal{C}} = \Delta P_{n,g,\mathcal{C}} - \Delta R_{n,g,\mathcal{C}}.$$

Neither $\Delta A_{n,g,\mathcal{C}}$ nor $\Delta R_{n,g,\mathcal{C}}$ follows from the coin combinatorics alone.

### B.15 An Open Enclosing Path Organizes All Equivalent Peers

Let the enclosing boundary follow an open state path

$$\mathcal{O}_{n + 1}:J_{0} \rightarrow J_{1} \rightarrow \cdots \rightarrow J_{m},$$

with

$$J_{m} \neq J_{0.}$$

For a selected $B_{n}$ peer and local alternative

$$i \rightarrow i + 1,$$

each enclosing state $J$ defines

$$\Delta P_{n,i \rightarrow i + 1}^{\left( J_{r} \right)} = \ln\left( \frac{J_{r} - i}{91 - J_{r} + i} \right).$$

For example, with $i = 5$,

$$60 \rightarrow 61 \rightarrow 62$$

gives

$$\Delta P^{(60)} = \ln\left( \frac{55}{36} \right),\Delta P^{(61)} = \ln\left( \frac{56}{35} \right),$$

and

$$\Delta P^{(62)} = \ln\left( \frac{57}{34} \right).$$

Because the ten $B_{n}$ landscapes are equivalent under the enclosing classification,

$$K_{n + 1 \mid n,a,i}^{(J)} = K_{n + 1 \mid n,b,i}^{(J)}$$

for equivalent peers $a$ and $b$.

Hence

$$\Delta P_{n,a,i \rightarrow i + 1}^{(J)} = \Delta P_{n,b,i \rightarrow i + 1}^{(J)}.$$

One enclosing compatibility relation therefore simultaneously defines the same directional possibility relation for every equivalent peer. The peer transitions do not have to communicate that organization laterally. They share the same enclosing compatibility relation. Whether realized occupancy follows that changing possibility relation is an R²D realization postulate.

### B.16 Enclosing Occurrence and Recursive Carry

The static multiplicity construction also clarifies the distinction between causal definition and recursive readout. Consider a realized enclosing occurrence

$$\chi_{n + 1}^{(r)}.$$

R²D proposes that it defines the compatible set of peer closures through which it is locally realized:

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a = 1}^{10} \in \mathfrak{D}_{n + 1,\chi}.$$

For a representative peer,

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,g}.$$

This is the causal realization relation.

After the local closure is completed, reading that same realization from $B_{n + 1}$ changes its count meaning:

$$\mathcal{C}_{n,g}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

The second relation does not mean that the local closure causes the enclosing occurrence. It is recursive reclassification. Thus,

$$\begin{aligned}
\text{causal~definition:}\quad\quad & \chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,g}, \\
\text{recursive~readout:}\quad\quad & \mathcal{C}_{n,g}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.
\end{aligned}$$

The static coin combinatorics demonstrate that adjacent boundaries possess different state classifications of recursively related count structure.

The realized causal and carry relations remain R²D propositions.

### B.17 Occurrence Realization and Closure Recurrence

Occurrence realization introduces distinctions not contained in static multiplicity. Let the two opposed ordered legs of a closure be

$$\mathcal{H}_{n,a}$$

and

$$\mathcal{L}_{n,a}.$$

Within a specified finite realization domain $\mathcal{D}$, define

$$\nu_{n,a,H} = N_{\mathcal{D}}\left( \mathcal{H}_{n,a} \right)$$

and

$$\nu_{n,a,L} = N_{\mathcal{D}}\left( \mathcal{L}_{n,a} \right).$$

These are path occurrence counts. They count completed realizations of the entire opposed legs. They are not sums of the state occurrence counts of their constituent transitions.

Define the directional leg-realization efficiency

$$\eta_{n,a,\mathcal{C}} = \frac{\nu_{n,a,L}}{\nu_{n,a,H}},$$

with orientation chosen so that

$$0 < \eta_{n,a,\mathcal{C}} \leq 1.$$

Reciprocal realization satisfies

$$\eta_{n,a,\mathcal{C}} = 1,$$

while nonreciprocal realization satisfies

$$0 < \eta_{n,a,\mathcal{C}} < 1.$$

The logarithmic opposed-leg occurrence difference is

$$\Delta\tau_{n,a,\mathcal{C}} = \ln \eta_{n,a,\mathcal{C}},$$

and the occurrence-count loss is

$$L_{\tau,n,a,\mathcal{C}} = - \Delta\tau_{n,a,\mathcal{C}} = - \ln \eta_{n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right).$$

This should not be confused with closure recurrence.

Choose a finite recurrence-comparison domain $\mathcal{D}_{R}$. Define

$$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)$$

as the number of completed recurrences of the local closure and

$$N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)$$

as the number of recurrences of the corresponding enclosing transition class in the same domain. Their adjacent recurrence ratio is

$$\boxed{\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}.}$$

The static coin construction does not determine this ratio. It is a realization quantity entering the R2D law.

Thus the occurrence quantities answer different questions:

$$\begin{matrix}
\Delta\tau_{n,i \rightarrow k} & :\quad\text{relative state occurrence}, \\
L_{\tau,n,a,\mathcal{C}} & :\quad\text{opposed-leg occurrence nonreciprocity}, \\
\rho_{n + 1 \mid n,a} & :\quad\text{recurrence of the enclosing transition relative to local closure recurrence}.
\end{matrix}$$

No physical time is assumed in any of these definitions.

### B.18 Finite-Count Directional Efficiency

The static coin construction does not determine the directional efficiency of realized occurrence. R²D introduces a separate finite-count postulate.

Let

$$N_{i} > 0,\quad\quad N_{k} > 0$$

be the finite counts entering the two opposed realization factors.

Define

$$\epsilon_{H} = \frac{N_{i}}{N_{k} + 1},$$

and

$$\epsilon_{L} = \frac{N_{k}}{N_{i} + 1}.$$

Then

$$\epsilon_{H}\epsilon_{L} = \frac{N_{i}N_{k}}{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)}.$$

For finite positive counts,

$$0 < \epsilon_{H}\epsilon_{L} < 1.$$

For the symmetric example

$$N_{i} = N_{k} = 5,$$

we obtain

$$\epsilon_{H} = \epsilon_{L} = \frac{5}{6},$$

and therefore

$$\epsilon_{H}\epsilon_{L} = \frac{25}{36}.$$

R²D postulates

$$\eta_{n,g,\mathcal{C}} = \epsilon_{H}\epsilon_{L}.$$

Thus the complete leg-realization counts must satisfy

$$\frac{\nu_{n,g,L}}{\nu_{n,g,H}} = \frac{25}{36}.$$

The corresponding occurrence-count loss is

$$L_{\tau,n,g,\mathcal{C}} = \ln\left( \frac{36}{25} \right).$$

The inequality of the finite-count product is mathematical. Its identification with directional leg-realization efficiency is an R²D postulate.

### B.19 Second-Law Readout

R²D\'s Second Law proposes

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,g,\mathcal{C}}.$$

For the finite example,

$$\delta_{\mathcal{C}}\Phi_{n + 1} = \ln\left( \frac{36}{25} \right).$$

If

δ~C~ Φ~n+1~ = ln(b~n+1~^+^/b~n+1~^-^),

then

b~n+1~^+^/b~n+1~^-^ = 36/25.

The local reading is

$$\eta_{n,g,\mathcal{C}} = \frac{25}{36},$$

while the enclosing-background reading is

b~n+1~^+^/b~n+1~^-^ = 36/25.

No count is transported or destroyed. The relation is between two boundary-specific logarithmic count readings linked by the R²D Second-Law postulate. The coin construction does not identify a physical object corresponding to $b_{n + 1}$. It specifies the count relation that any later physical mapping must satisfy.

### B.20 What the Coin Construction Establishes

The coin construction separates exact mathematics from R²D realization and causal claims.

**Exact combinatorial results:**

A new boundary replaces subordinate state spaces with a new classification.

At $B_{n}$,

$$\mathcal{M}_{n} = \left\{ 0,\ldots,10 \right\}.$$

At $B_{n + 1}$,

$$\mathcal{M}_{n + 1} = \left\{ 0,\ldots,100 \right\}.$$

The $B_{n + 1}$ landscape is recursively defined from ten $B_{n}$ landscapes:

$$W_{n + 1,J} = \sum_{\sum_{a}i_{a} = J}{\prod_{a}W_{n,a,i_{a}}}.$$

For the coin construction this evaluates to

$$W_{n + 1,J} = \binom{100}{J}.$$

The equality does not imply that one hundred $B_{n - 1}$ coin states remain primitive at $B_{n + 1}$.

It shows that recursive replacement preserves their multiplicity consequence.

The example further establishes that subordinate transitions change realization but do not create native multiplicity. Uniform enclosing extension produces no directional possibility. Unequal enclosing compatibility produces directional possibility. And changing only enclosing compatibility can reverse local directional support.

For the explicit case,

$$\Delta S_{5 \rightarrow 6} = \ln\left( \frac{5}{6} \right) < 0,$$

while

$$\Delta P_{5 \rightarrow 6}^{(60)} = \ln\left( \frac{55}{36} \right) > 0,$$

and

$$\Delta S + \Delta P = \ln\left( \frac{275}{216} \right) > 0.$$

The example also proves that a local multiplicity path may close while enclosing possibility does not:

$$\Delta S_{n,g,\mathcal{C}} = 0\quad\quad\text{with}\quad\quad\Delta P_{n,g,\mathcal{C}} \neq 0.$$

These are mathematical results.

**What requires R²D realization postulates:**

The combinatorics do not establish

$$\Delta G = \Delta\tau + \Delta A.$$

They do not establish proportional occurrence realization,

$$\Delta\tau \approx \Delta S.$$

They do not establish

$$\eta_{n,g,\mathcal{C}} = \epsilon_{H}\epsilon_{L}.$$

They do not establish the R²D law, or

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,g,\mathcal{C}}.$$

Those are realization propositions applied to the exact count architecture.

**What the coins establish about causal agency:**

The coin construction does establish something stronger than simple statistical dependence.

A subordinate transition cannot be the origin of the multiplicity landscape whose occupancy it changes because that landscape is already defined independently of the particular realization.

Likewise, a $B_{n}$ transition cannot by itself define the $B_{n + 1}$ compatibility relation that can reverse the directional significance of that transition. Thus, the local event realizes structure it does not generate.

That is an exact consequence of the recursive count construction. The enclosing-to-local causal ordering is not an additional assumption appended to that construction. It is the formal consequence of two facts already established above: the compatible subordinate realization has microstate meaning only relative to the enclosing state definition, and the subordinate transition cannot define the enclosing compatibility relation that can change its directional significance.

For a realized enclosing occurrence and one compatible local closure, this ordering is written

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,g}.$$

The arrow does not introduce a new source of causal structure. It records which compatible local realization belongs to the enclosing occurrence. Physical claims about how particular systems realize this relation remain domain-specific and testable.

Recursive carry is separately

$$\mathcal{C}_{n,g}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

The second arrow is boundary-relative reclassification, not bottom-up causal production.

The coin ensemble therefore demonstrates the formal distinction at the center of R²D:

**Possible structure is defined by the boundary.**

**Enclosing compatibility defines directional support.**

**Subordinate events realize that structure.**

**Recursive replacement preserves count consequence without preserving subordinate state identity.**

This is the exact mathematical architecture. The additional empirical burden belongs to realization postulates and domain-specific physical mappings, not to a separately imported top-down causal assumption.


## Appendix C — Symbol Summary

---
r2d_id: "canon-p1-app-c"
title: "Part I — Appendix C: Symbol Summary"
source_type: "canon"
authority: "canonical"
indexable: true
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 195
pdf_page_end: 209
semantic_amendment: "none"
review_status: "authoritative"
---
# Appendix C — Symbol Summary

### C.1 Indexing and Logical Conventions

  -------------------------------------------------------------------------------------------------------------------------
  **Symbol**                 **Meaning**
  -------------------------- ----------------------------------------------------------------------------------------------
  $$n$$                      Generic recursive boundary level.

  $$B_{n}$$                  Count boundary at recursive level $n$.

  $$B_{n - 1,a}$$            Peer boundary immediately subordinate to $B_{n}$.

  $$B_{n + 1}$$              Boundary immediately enclosing $B_{n}$.

  $$a,b$$                    Generic peer indices at one recursive level. Either may be used to distinguish peers.

  $$I_{n}$$                  Index set of peer boundaries at recursive level $n$.

  $$i,j,k$$                  Readable macrostate labels within one boundary-defined count domain.

  $$N > n$$                  Generic larger boundary used for accumulated scaling relations.

  $$\alpha$$                 Index reserved for the smallest realized recursive boundary.

  $$\omega$$                 Index reserved for the largest presently realized recursive boundary.

  $$^{(r)}$$                 Optional label for one realized occurrence. The label $r$ is not a recursive boundary index.

  $$H,L$$                    Opposed oriented legs of a minimal two-leg closure.

  $$\Delta$$                 Oriented difference between states or accumulated oriented difference along a path.

  $$\delta_{\mathcal{C}}$$   Increment associated with one specified realized closure.

  $$n + 1 \mid n$$           Quantity defined or read at $B_{n + 1}$ conditional on a relation at $B_{n}$.

  $$^{tot}$$                 Total quantity within one boundary-defined count domain.

  $$^{comp}$$                Quantity associated with compatible enclosing multiplicity.

  $$^{out}$$                 Productive or distinguishable-output component.

  $$^{\Phi}$$                Background-associated or dissipative component.
  -------------------------------------------------------------------------------------------------------------------------

**Peer-index convention**

The indices $a$ and $b$ identify ordinary peers. No special representative-peer index is required.

When one peer from an equivalent class is selected for the R2D law, retain its ordinary peer index:

$$\mathcal{C}_{n,a}.$$

If peers $a$ and $b$ are equivalent under the relevant enclosing compatibility relation, either may be selected. Their recurrence-weighted R2D readings satisfy

$$\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = \Delta A_{n,b,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,b} \right).$$

Equivalently, for positive recurrence ratios,

$$\frac{\Delta A_{n,a,\mathcal{C}}}{\rho_{n + 1 \mid n,a}} = \frac{\Delta A_{n,b,\mathcal{C}}}{\rho_{n + 1 \mid n,b}}.$$

No averaging over peers is implied.

### C.2 Boundary, State, and Readability Symbols

  -----------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                                             **Meaning**
  ------------------------------------------------------ ----------------------------------------------------------------------------------------
  $$B_{n}$$                                              Count boundary defining the count domain at recursive level $n$.

  $$\mathfrak{X}_{n - 1,a}$$                             Possible realization domain of subordinate peer $B_{n - 1,a}$.

  $$\prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}$$   Unrestricted joint peer-realization space subordinate to $B_{n}$.

  $$\mathfrak{M}_{n}$$                                   Formal microstate domain at $B_{n}$: the compatible subset of joint peer realizations.

  $$\mu_{n}$$                                            One formal microstate at $B_{n}$.

  $$\mathcal{M}_{n}$$                                    Set of readable macrostates at $B_{n}$.

  $$i \in \mathcal{M}_{n}$$                              One readable macrostate at $B_{n}$.

  $$\pi_{n}$$                                            Macrostate classification map defined by $B_{n}$.

  $$\mu_{n} \sim_{n}\mu_{n}'$$                           Macrostate equivalence of two formal microstates at $B_{n}$.

  $$\pi_{n}^{-1}(i)$$                                   Fiber of compatible formal microstates classified as macrostate $i$.

  $$\chi_{n,i \rightarrow k}$$                           Readable macrostate transition $i \rightarrow k$ at $B_{n}$.

  $$\mu_{n} \rightarrow \mu_{n}'$$                       Microstate transition relative to $B_{n}$.

  $$\mathcal{R}_{n}$$                                    Finite readable macrostate path returning to its initial macrostate.

  $$\mathcal{C}_{n}$$                                    Closure: a local return compatible with an enclosing occurrence.

  $$\mathcal{C}_{n,a}$$                                  Closure at specified peer $a$.
  -----------------------------------------------------------------------------------------------------------------------------------------------

The formal microstate domain is

$$\mathfrak{M}_{n} \subseteq \prod_{a \in I_{n - 1}}\mathfrak{X}_{n - 1,a}.$$

A formal microstate is

$$\mu_{n} = \left( x_{n - 1,a} \right)_{a \in I_{n - 1}} \in \mathfrak{M}_{n}.$$

The macrostate classification map is

$$\pi_{n}:\mathfrak{M}_{n} \rightarrow \mathcal{M}_{n}.$$

Macrostate equivalence is

$$\mu_{n} \sim_{n}\mu_{n}' \Longleftrightarrow \pi_{n}\left( \mu_{n} \right) = \pi_{n}\left( \mu_{n}' \right).$$

The fundamental boundary-relative transition relation is

$$\text{macrostate~transition~at~}B_{n - 1,a} = \text{microstate~transition~relative~to~}B_{n}.$$

A microstate transition is therefore formally definable relative to $B_{n}$ without being individually readable as a microstate transition from $B_{n}$.

### C.3 Native Multiplicity and Entropy

  ---------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                         **Meaning**
  ---------------------------------- ----------------------------------------------------------------------------------------------------
  $$W_{n,i}$$                        Native multiplicity of macrostate $i$: number of compatible formal microstates classified as$i$.

  $$S_{n,i}$$                        Dimensionless logarithmic possible-count coordinate of macrostate $i$.

  $$\Delta S_{n,i \rightarrow k}$$   Native logarithmic multiplicity difference across readable transition $i \rightarrow k.$

  $$\Theta_{n}$$                     Total possible multiplicity of boundary $B_{n}$.

  $$S_{n}^{tot}$$                    Logarithm of total boundary multiplicity.

  $$\mathcal{W}_{n}$$                Native multiplicity landscape at $B_{n}$.

  $$\mathcal{S}_{n}$$                Native entropic landscape at $B_{n}$.
  ---------------------------------------------------------------------------------------------------------------------------------------

Multiplicity is

$$W_{n,i} = \left| \pi_{n}^{-1}(i) \right|.$$

Entropy is

$$S_{n,i} = \ln W_{n,i}.$$

The native transition difference is

$$\Delta S_{n,i \rightarrow k} = S_{n,k} - S_{n,i} = \ln\left( \frac{W_{n,k}}{W_{n,i}} \right).$$

Total boundary multiplicity is

$$\Theta_{n} = \left| \mathfrak{M}_{n} \right|.$$

Because the macrostate fibers partition the formal microstate domain,

$$\Theta_{n} = \sum_{i \in \mathcal{M}_{n}}W_{n,i}.$$

Total boundary entropy is

$$S_{n}^{tot} = \ln \Theta_{n}.$$

The native landscapes are

$$\mathcal{W}_{n} = \left\{ W_{n,i} \right\}_{i \in \mathcal{M}_{n}},\quad\quad\mathcal{S}_{n} = \left\{ S_{n,i} \right\}_{i \in \mathcal{M}_{n}}.$$

For unrestricted compatible composition,

$$W_{joint} = \prod_{a}W_{a},$$

so

$$\ln W_{joint} = \sum_{a}\ln W_{a}.$$

Thus,

$$\text{compatible~joint~possibilities~multiply;}\quad\quad\text{mutually~exclusive~alternatives~add}.$$

### C.4 Enclosing Compatibility and Possibility

  ------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                           **Meaning**
  ------------------------------------ -----------------------------------------------------------------------------------------------------------------------
  $$\mathcal{E}_{n + 1 \mid n,a,i}$$   Enclosing compatibility fiber: enclosing formal microstates compatible with peer $a$ being locally classified as $i$.

  $$\Theta_{n + 1 \mid n,a,i}$$        Multiplicity of the enclosing compatibility fiber.

  $$K_{n + 1 \mid n,a,i}$$             Mean compatible enclosing extension multiplicity per local possibility.

  $$P_{n,a,i}$$                        Logarithmic compatible enclosing extension associated with local macrostate $i$.

  $$\Delta P_{n,a,i \rightarrow k}$$   Directional possibility difference between local alternatives $i$ and $k$.

  $$S_{n + 1 \mid n,a,i}^{comp}$$      Compatible enclosing entropy conditioned on the local classification $i$.
  ------------------------------------------------------------------------------------------------------------------------------------------------------------

When the peer is already clear, the index $a$ may be suppressed.

The enclosing compatibility fiber is

$$\mathcal{E}_{n + 1 \mid n,a,i} = \left\{ \mu_{n + 1} \in \mathfrak{M}_{n + 1}:\mu_{n + 1}\text{~is~compatible~with~peer~}a\text{~locally~classified~as~}i \right\}.$$

Its multiplicity is

$$\Theta_{n + 1 \mid n,a,i} = \left| \mathcal{E}_{n + 1 \mid n,a,i} \right|.$$

The compatible enclosing extension multiplicity is

$$K_{n + 1 \mid n,a,i} = \frac{\Theta_{n + 1 \mid n,a,i}}{W_{n,a,i}}.$$

Possibility is

$$P_{n,a,i} = \ln K_{n + 1 \mid n,a,i}.$$

Directional possibility is

$$\Delta P_{n,a,i \rightarrow k} = P_{n,a,k} - P_{n,a,i} = \ln\left( \frac{K_{n + 1 \mid n,a,k}}{K_{n + 1 \mid n,a,i}} \right).$$

Compatible enclosing entropy is

$$S_{n + 1 \mid n,a,i}^{comp} = \ln \Theta_{n + 1 \mid n,a,i}.$$

Therefore,

$$P_{n,a,i} = S_{n + 1 \mid n,a,i}^{comp} - S_{n,a,i}.$$

The directional enclosing-multiplicity identity is

$$\Delta S_{n,a,i \rightarrow k} + \Delta P_{n,a,i \rightarrow k} = \ln\left( \frac{\Theta_{n + 1 \mid n,a,k}}{\Theta_{n + 1 \mid n,a,i}} \right).$$

Uniform enclosing extension satisfies

$$K_{n + 1 \mid n,a,i} = K_{n + 1 \mid n,a,k} \Longleftrightarrow \Delta P_{n,a,i \rightarrow k} = 0.$$

Thus,

$$\text{enclosing~multiplicity~supplies~possibility;}\quad\quad\text{unequal~enclosing~compatibility~supplies~direction}.$$

### C.5 Occurrence, Occupancy, and Structural Realization

  -----------------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                           **Meaning**
  ------------------------------------ ----------------------------------------------------------------------------------------------------------------------
  $$\mu_{n}^{(r)}$$                    One realized formal microstate at $B_{n}$.

  $$\nu_{n,i}$$                        Number of realized microstate occurrences classified as macrostate $i$ within a specified finite realization domain.

  $$\tau_{n,i}$$                       Logarithmic occurrence coordinate associated with macrostate $i$.

  $$\Delta\tau_{n,i \rightarrow k}$$   Occurrence-coordinate difference between macrostates $i$ and $k$.

  $$c_{n,i}$$                          Realized occupancy of macrostate $i$.

  $$G_{n,i}$$                          Logarithmic occupancy coordinate.

  $$\Delta G_{n,i \rightarrow k}$$     Logarithmic occupancy difference across transition $i \rightarrow k$.

  $$i_{n}^{*}$$                        Structural macrostate: macrostate of maximum occupancy.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------

One realized microstate is

$$\mu_{n}^{(r)} \in \mathfrak{M}_{n}.$$

If

$$\pi_{n}\left( \mu_{n}^{(r)} \right) = i,$$

that realization contributes one occurrence associated with macrostate $i$.

For positive occurrence count,

$$\tau_{n,i} = \ln \nu_{n,i}.$$

For a readable transition,

$$\Delta\tau_{n,i \rightarrow k} = \tau_{n,k} - \tau_{n,i} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right).$$

For positive occupancy,

$$G_{n,i} = \ln c_{n,i}.$$

The occupancy difference is

$$\Delta G_{n,i \rightarrow k} = G_{n,k} - G_{n,i} = \ln\left( \frac{c_{n,k}}{c_{n,i}} \right).$$

The structural macrostate is

$$i_{n}^{*} = {*{arg\, max}}_{i \in \mathcal{M}_{n}}c_{n,i}.$$

The three primary count types are

$$W_{n,i} = \text{possible~count},$$

and

$$c_{n,i} = \text{realized~occupancy}.$$

Their logarithmic coordinates are

$$S_{n,i},\quad\quad\tau_{n,i},\quad\quad G_{n,i}.$$

These are distinct count types.

### C.6 Distinguishability, Constraint, Retention, and Asymmetry

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                         **Meaning**
  ---------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  $$\lambda_{n,i \rightarrow k}$$    Oriented readable distinguishability interval between macrostates $i$ and $k$.


  $$C_{n + 1}$$                      Total enclosing constraint on the enclosing occurrence; decomposed into productive and background-associated components. Only the productive component enters local retention.

  $$\Delta R_{n,i \rightarrow k}$$   Retention across the readable transition, defined by the productive component of enclosing constraint.

  $$\Delta A_{n,i \rightarrow k}$$   Net local asymmetry across the transition.

  $$C_{n + 1}^{out}$$                Productive/output component of enclosing constraint; defines local retention and remains readable as productive enclosing output.

  $$C_{n + 1}^{\Phi}$$               Background-associated or dissipative component of enclosing constraint; contributes to the total enclosing read but not to local retention.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Distinguishability is oriented:

$$\lambda_{n,k \rightarrow i} = - \lambda_{n,i \rightarrow k}.$$

Retention is a transition-defined quantity determined by productive constraint:

$$\Delta R_{n,i \rightarrow k} = C_{n + 1}^{out}\lambda_{n,i \rightarrow k}.$$

Hence,

$$\Delta R_{n,k \rightarrow i} = - \Delta R_{n,i \rightarrow k}.$$

Local asymmetry is likewise transition-defined:

$$\Delta A_{n,i \rightarrow k} = \Delta P_{n,i \rightarrow k} - \Delta R_{n,i \rightarrow k}.$$

The occupancy-realization postulate is

$$\Delta G_{n,i \rightarrow k} = \Delta\tau_{n,i \rightarrow k} + \Delta A_{n,i \rightarrow k}.$$

Under proportional occurrence realization,

$$\Delta\tau_{n,i \rightarrow k} \approx \Delta S_{n,i \rightarrow k},$$

so

$$\Delta G \approx \Delta S + \Delta P - \Delta R.$$

The total enclosing constraint is separately decomposed as

$$C_{n + 1} = C_{n + 1}^{out} + C_{n + 1}^{\Phi}.$$

### C.7 Return, Closure, Recurrence, and Occurrence Nonreciprocity

  ------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                                                **Meaning**
  --------------------------------------------------------- --------------------------------------------------------------------------------------------------
  $$\mathcal{R}_{n}$$                                       Finite readable macrostate return at $B_{n}$.

  $$\mathcal{C}_{n,a}$$                                     Closure at peer $a$: a local return compatible with an enclosing occurrence.

  $$\Delta S_{n,a,\mathcal{C}}$$                            Net native logarithmic multiplicity difference around the closure.

  $$\Delta P_{n,a,\mathcal{C}}$$                            Accumulated directional possibility around the closure.

  $$\Delta R_{n,a,\mathcal{C}}$$                            Accumulated retention around the closure.

  $$\Delta A_{n,a,\mathcal{C}}$$                            Net enclosing-defined asymmetry remaining around the closure.

  $$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)$$   Number of completed local closure recurrences in recurrence-comparison domain $\mathcal{D}_{R}$.

  $$N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)$$        Number of completed enclosing transition recurrences in the same comparison domain.

  $$\rho_{n + 1 \mid n,a}$$                                 Enclosing recurrence count divided by representative local closure recurrence count.

  $$\nu_{n,a,H}$$                                           Number of completed realizations of oriented closure leg $H$.

  $$\nu_{n,a,L}$$                                           Number of completed realizations of opposed closure leg $L$.

  $$\eta_{n,a,\mathcal{C}}$$                                Directional occurrence-count efficiency of the completed closure.

  $$\Delta\tau_{n,a,\mathcal{C}}$$                          Logarithmic opposed-leg occurrence difference, $\ln\eta_{n,a,\mathcal{C}}$.

  $$L_{\tau,n,a,\mathcal{C}}$$                              Logarithmic nonreciprocity of the opposed leg-realization counts.

  $$\epsilon_{H},\epsilon_{L}$$                             Finite-count realization factors for the opposed closure legs.

  $$N_{i},N_{k}$$                                           Finite positive counts entering the finite-count directional-efficiency construction.
  ------------------------------------------------------------------------------------------------------------------------------------------------------------

Closure possibility is

$$\Delta P_{n,a,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,a}}\Delta P_{n,a,\chi}.$$

Closure retention is

$$\Delta R_{n,a,\mathcal{C}} = \sum_{\chi \in \mathcal{C}_{n,a}}\Delta R_{n,a,\chi}.$$

Closure asymmetry is

$$\Delta A_{n,a,\mathcal{C}} = \Delta P_{n,a,\mathcal{C}} - \Delta R_{n,a,\mathcal{C}}.$$

Complete retention satisfies

$$\Delta A_{n,a,\mathcal{C}} = 0,$$

or equivalently,

$$\Delta P_{n,a,\mathcal{C}} = \Delta R_{n,a,\mathcal{C}}.$$

Native multiplicity closes exactly:

$$\Delta S_{n,a,\mathcal{C}} = 0.$$

**Closure recurrence**

Within a common recurrence-comparison domain $\mathcal{D}_{R}$,

$$\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}.$$

This ratio is distinct from state occurrence and from opposed-leg occurrence efficiency.

**Complete leg occurrence counts**

The quantities

$$\nu_{n,a,H}$$

and

$$\nu_{n,a,L}$$

count complete realizations of the two opposed ordered closure paths.

Directional occurrence-count efficiency is

$$\eta_{n,a,\mathcal{C}} = \frac{\nu_{n,a,L}}{\nu_{n,a,H}},\quad\quad 0 < \eta_{n,a,\mathcal{C}} \leq 1.$$

The logarithmic opposed-leg difference is

$$\Delta\tau_{n,a,\mathcal{C}} = \ln \eta_{n,a,\mathcal{C}},$$

and occurrence-count loss is

$$L_{\tau,n,a,\mathcal{C}} = - \Delta\tau_{n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right).$$

Thus $\rho$ describes cross-boundary recurrence, whereas $L_{\tau}$ describes local opposed-leg nonreciprocity. These are different quantities.

**Finite-count realization factors**

$$\epsilon_{H} = \frac{N_{i}}{N_{k} + 1},\quad\quad\epsilon_{L} = \frac{N_{k}}{N_{i} + 1}.$$

Therefore,

$$0 < \epsilon_{H}\epsilon_{L} = \frac{N_{i}N_{k}}{\left( N_{i} + 1 \right)\left( N_{k} + 1 \right)} < 1.$$

R2D postulates

$$\eta_{n,a,\mathcal{C}} = \epsilon_{H}\epsilon_{L}.$$

### C.8 Enclosing Occurrence, Recursive Carry, and Causal Direction

  ------------------------------------------------------------------------------------------------------
  **Symbol**                      **Meaning**
  ------------------------------- ----------------------------------------------------------------------
  $$\chi_{n + 1}$$                Readable enclosing macrostate transition at $B_{n + 1}$.

  $$\chi_{n + 1}^{(r)}$$          One realized occurrence associated with the enclosing transition.

  $$\mathfrak{D}_{n + 1,\chi}$$   Set of joint peer closures compatible with one enclosing occurrence.

  $$\mathcal{C}_{n,a}$$           Closure at selected peer a compatible with the enclosing occurrence.

  $$\kappa_{n}$$                  Recursive reclassification under change from $B_{n}$ to $B_{n + 1}$.
  ------------------------------------------------------------------------------------------------------

The enclosing compatible-closure set is

$$\mathfrak{D}_{n + 1,\chi} = \left\{ \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}}:\left( \mathcal{C}_{n,a} \right)_{a \in I_{n}}\text{~}\text{is~jointly~compatible~with}\text{~}\chi_{n + 1}^{(r)} \right\}.$$

The causal realization relation is

$$\chi_{n + 1}^{(r)} \Longrightarrow \left( \mathcal{C}_{n,a} \right)_{a \in I_{n}} \in \mathfrak{D}_{n + 1,\chi}.$$

For one selected compatible peer $a$,

$$\chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}.$$

Recursive carry is

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.$$

Thus,

$$\begin{aligned}
\text{causal~definition}\text{:}\quad\quad & \chi_{n + 1}^{(r)} \Longrightarrow \mathcal{C}_{n,a}, \\
\text{recursive~readout}\text{:}\quad\quad & \mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}.
\end{aligned}$$

Recursive carry is reclassification, not reverse causation.

### C.9 Background and the Second Law

  --------------------------------------------------------------------------------------------------------------------------
  **Symbol**                             **Meaning**
  -------------------------------------- -----------------------------------------------------------------------------------
  $$b_{n}$$                              Realized nondirectional background count at $B_{n}$.

  $$\Phi_{n}$$                           Logarithmic background coordinate.

  b~n+1~^-^                              Enclosing background count before one specified realization relation.

  b~n+1~^+^                              Enclosing background count after one specified realization relation.

  $$\delta_{\mathcal{C}}\Phi_{n + 1}$$   Enclosing background increment associated with closure $\mathcal{C}$.

  $$\Delta\Phi_{n + 1 \mid n,a:b}$$      Enclosing comparison between background counts associated with peers $a$ and $b$.
  --------------------------------------------------------------------------------------------------------------------------

Background is

$$\Phi_{n} = \ln b_{n}.$$

Background is nondirectional relative to the boundary at which it is background:

$$\Delta\Phi_{n,i \rightarrow k} = 0.$$

Peer backgrounds may nevertheless define an enclosing distinction:

$$\Delta\Phi_{n + 1 \mid n,a:b} = \Phi_{n,a} - \Phi_{n,b} = \ln\left( \frac{b_{n,a}}{b_{n,b}} \right).$$

The enclosing background increment is

δ~C~ Φ~n+1~ = ln(b~n+1~^+^/b~n+1~^-^).

The Second Law of Recursive Counting is

$$\delta_{\mathcal{C}}\Phi_{n + 1} = L_{\tau,n,a,\mathcal{C}}.$$

This relation equates boundary-specific logarithmic count readings. It does not describe bottom-up transport or destruction of count.

### C.10 Recurrence Ratio and the R2D Law

  ---------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**                                                **Meaning**
  --------------------------------------------------------- -----------------------------------------------------------------------------------------
  $$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)$$   Completed representative local closure recurrences in one recurrence-comparison domain.

  $$N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)$$        Completed enclosing transition recurrences in the same domain.

  $$\rho_{n + 1 \mid n,a}$$                                 Adjacent recurrence ratio, enclosing recurrence divided by local closure recurrence.

  $$\Delta A_{n,a,\mathcal{C}}$$                            Net closure asymmetry per local closure recurrence.

  $$C_{n + 1}\lambda_{n + 1}$$                              Constrained distinguishability per enclosing recurrence.
  ---------------------------------------------------------------------------------------------------------------------------------------------------

The adjacent recurrence ratio is

$$\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}.$$

The R2D law is

$$\boxed{\Delta A_{n,a,\mathcal{C}} = C_{n + 1}\lambda_{n + 1}\rho_{n + 1 \mid n,a}.}$$

Equivalently,

$$\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = C_{n + 1}\lambda_{n + 1}N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right).$$

With productive and background-associated constraint explicitly separated,

$$\Delta A_{n,a,\mathcal{C}} = \left( C_{n + 1}^{out} + C_{n + 1}^{\Phi} \right)\lambda_{n + 1}\rho_{n + 1 \mid n,a}.$$

For equivalent peers $a$ and $b$,

$$\Delta A_{n,a,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right) = \Delta A_{n,b,\mathcal{C}}N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,b} \right).$$

No sum or average over peers is implied.

### C.11 Accumulated Count Geometry and Readability Horizons

  -----------------------------------------------------------------------------------------------------------------
  **Symbol**                          **Meaning**
  ----------------------------------- -----------------------------------------------------------------------------
  $$\Lambda_{N \mid n}$$              Accumulated logarithmic distinguishability scaling from $B_{n}$ to $B_{N}$.

  $$\Gamma_{N \mid n}$$               Accumulated logarithmic recurrence scaling from $B_{n}$ to $B_{N}$.

  $$H_{N \mid n}$$                    Accumulated count-geometry imbalance.
  -----------------------------------------------------------------------------------------------------------------

Define

$$\Lambda_{N \mid n} = \ln\left( \frac{\left| \lambda_{N} \right|}{\left| \lambda_{n} \right|} \right),$$

and

$$\Gamma_{N \mid n} = \sum_{j = n}^{N - 1}\ln\rho_{j + 1 \mid j}.$$

Then

$$\boxed{H_{N \mid n} = \Lambda_{N \mid n} - \Gamma_{N \mid n}.}$$

Equivalently,

$$H_{N \mid n} = \ln\left\lbrack \frac{\left| \lambda_{N} \right|/\left| \lambda_{n} \right|}{\prod_{j = n}^{N - 1}\rho_{j + 1 \mid j}} \right\rbrack.$$

  ----------------------------------------------------------------------------------------------------------------------------------
  **Regime**                    **Condition**                **Meaning**
  ----------------------------- ---------------------------- -----------------------------------------------------------------------
  Distinguishability-dominant   $$H \rightarrow + \infty$$   Distinguishability grows relative to recurrence.

  Recurrence-dominant           $$H \rightarrow - \infty$$   Recurrence grows relative to distinguishability.

  Jointly readable closure      $$|H| < \infty$$             Both relations may remain jointly readable when both remain resolved.
  ----------------------------------------------------------------------------------------------------------------------------------

A mathematical limit alone is not a readability horizon. A horizon additionally requires loss of resolution of one count relation while the other remains readable.

### C.12 Recursive Limits

  ----------------------------------------------------------------------------------------------------------------------
  **Symbol**                          **Meaning**
  ----------------------------------- ----------------------------------------------------------------------------------
  $$B_{\alpha}$$                      Smallest realized count boundary.

  $$B_{\omega}$$                      Largest presently realized count boundary.

  $$\mathcal{O}_{\omega}$$            Presently open macrostate path at $B_{\omega}.$

  $$\mathcal{C}_{\omega}$$            Completed terminal closure; presently not realized under the terminal postulate.

  $$\Delta A_{\omega,\mathcal{O}}$$   Unresolved directional asymmetry of the terminal open path.
  ----------------------------------------------------------------------------------------------------------------------

The lower realized limit is

$$B_{\alpha}.$$

No realized boundary

$$B_{\alpha - 1}$$

is required for primitive distinguishable recurrence.

The upper realized path is

$$\mathcal{O}_{\omega}:i_{\omega,0} \rightarrow \cdots \rightarrow i_{\omega,m},\quad\quad i_{\omega,m} \neq i_{\omega,0}.$$

Therefore,

$$\mathcal{O}_{\omega} \neq \mathcal{C}_{\omega}.$$

No completed terminal closure is presently available for recursive reclassification into a realized $B_{\omega + 1}$.

The unresolved terminal asymmetry is

$$\Delta A_{\omega,\mathcal{O}}.$$

It is not defined by

$$\Delta A_{\omega,\mathcal{O}} = \Delta P_{\omega} - \Delta R_{\omega}$$

because that construction would require a presently realized enclosing boundary $B_{\omega + 1}$.

### C.13 Type Summary

This table makes explicit **where each quantity is defined**.

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Count relation**         **State-defined quantity**   **Transition-defined quantity**                         **Closure / across-boundary quantity**
  -------------------------- ---------------------------- ------------------------------------------------------- --------------------------------------------------------------------------------------
  Native multiplicity        $$W_{n,i}, S_{n,i}$$        $$\Delta S_{n,i \rightarrow k}$$                        $$\Delta S_{n,a,\mathcal{C}} = 0$$

  Enclosing possibility      $$P_{n,a,i}$$                $$\Delta P_{n,a,i \rightarrow k}$$                      $$\Delta P_{n,a,\mathcal{C}}$$

  State occurrence           $$\nu_{n,i}, \tau_{n,i}$$   $$\Delta\tau_{n,i \rightarrow k}$$                      ---

  Closure recurrence         ---                          ---                                                     $$N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right), \rho_{n + 1 \mid n,a}$$

  Occupancy                  $$c_{n,i}, G_{n,i}$$        $$\Delta G_{n,i \rightarrow k}$$                        ---

  Distinguishability         ---                          $$\lambda_{n,i \rightarrow k}$$                         $\lambda_{n + 1}$ when read enclosingly

  Retention                  ---                          $$\Delta R_{n,i \rightarrow k}$$                        $$\Delta R_{n,a,\mathcal{C}}$$

  Asymmetry                  ---                          $$\Delta A_{n,i \rightarrow k}$$                        $$\Delta A_{n,a,\mathcal{C}}$$

  Complete leg realization   ---                          ---                                                     $$\nu_{n,a,H}, \nu_{n,a,L}$$

  Leg nonreciprocity         ---                          ---                                                     $$\eta_{n,a,\mathcal{C}}, \Delta\tau_{n,a,\mathcal{C}}, L_{\tau,n,a,\mathcal{C}}$$

  Background                 $$b_{n}, \Phi_{n}$$         $\Delta\Phi_{n + 1 \mid n,a:b}$ when read enclosingly   $$\delta_{\mathcal{C}}\Phi_{n + 1}$$
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The most important distinctions are:

$$\Delta\tau_{n,i \rightarrow k} = \ln\left( \frac{\nu_{n,k}}{\nu_{n,i}} \right)$$

is a **state occurrence difference**;

$$L_{\tau,n,a,\mathcal{C}} = \ln\left( \frac{\nu_{n,a,H}}{\nu_{n,a,L}} \right)$$

is the **nonreciprocity of complete opposed-leg realizations**; and

$$\rho_{n + 1 \mid n,a} = \frac{N_{\mathcal{D}_{R}}\left( \chi_{n + 1} \right)}{N_{\mathcal{D}_{R}}\left( \mathcal{C}_{n,a} \right)}$$

is the **across-boundary recurrence ratio**.

These three quantities are not interchangeable.

Likewise,

$$P_{n,a,i} = \text{state-defined enclosing extension coordinate},$$

whereas

$$\Delta P_{n,a,i \rightarrow k} = \text{transition-defined directional possibility}.$$

Finally, the principal recursive distinction remains

$$\chi_{n + 1}^{(r)} \Rightarrow \mathcal{C}_{n,a}$$

for causal realization, versus

$$\mathcal{C}_{n,a}\overset{\kappa_{n}}{\mapsto}\chi_{n + 1}^{(r)}$$

for recursive reclassification.

The first specifies which subordinate realization belongs to the enclosing occurrence. The second specifies how that completed realization is counted when the boundary changes.


## References

---
r2d_id: "canon-p1-references"
title: "Part I — References"
source_type: "canon"
authority: "canonical"
indexable: false
part: 1
canon_revision: "2026-09-25"
source_format: "authoritative_markdown"
unit: "section"
source_canon_snapshot: "2026-09-14"
machine_revision: "2026-09-25-authoritative-md-v1"
prose_source: "R2D Part I v14 freeze constraint decomposition.docx; checked against R2D 9-14-2026 Part I retrieval units"
equation_source: "R2D Part I v14 freeze constraint decomposition.docx (OMML)"
math_representation: "LaTeX"
pdf_page_start: 210
pdf_page_end: 211
semantic_amendment: "none"
review_status: "authoritative"
---
# Part I — References

1. Boltzmann, L. 1877. Sitzungsberichte der Kaiserlichen Akademie der Wissenschaften. *Wien* 76.

2. Zwanzig, R. 2001. Nonequilibrium Statistical Mechanics. Oxford University Press.

3. Jaynes, E.T. 1957. Information Theory and Statistical Mechanics. *Phys. Rev.* 106.

4. Gibbs, J. 1902. Elementary Principles in Statistical Mechanics Developed with Especial Reference to the Rational Foundation of Thermodynamics.

5. Brown, H.R., W.C. Myrvold, and J. Uffink. 2009. Boltzmann's H-Theorem, Its Discontents, and the Birth of Statistical Mechanics. *Studies in History and Philosophy of Science Part B Studies in History and Philosophy of Modern Physics* 40:174--191, doi: 10.1016/j.shpsb.2009.03.003.

6. Cooke, R. 1997. Actomyosin interaction in striated muscle. *Physiol. Rev.* 77:671--97.

7. Hill, A.V. 1938. The heat of shortening and the dynamic constants of muscle. *Proceedings of the Royal Society of London. Series B* 126:136--195.

8. Hill, A. 1964. The efficiency of mechanical power development during muscular shortening and its relation to load. *Proc. R. Soc. Lond. B Biol. Sci.* 159:319--324.

9. Baker, J.E., L.E.W. LaConte, I. Brust-Mascher, and D.D. Thomas. 1999. Mechanochemical coupling in spin-labeled, active, isometric muscle. *Biophys. J.* 77:2657--64, doi: 10.1016/S0006-3495(99)77100-6.

10. Baker, J.E., I. Brust-Mascher, S. Ramachandran, L.E. LaConte, and D.D. Thomas. 1998. A large and distinct rotation of the myosin light chain domain occurs upon muscle contraction. *Proc. Natl. Acad. Sci. U. S. A.* 95:2944--9.

11. Baker, J.E., and D.D. Thomas. 2000. A thermodynamic muscle model and a chemical basis for A.V. Hill's muscle equation. *J Muscle Res Cell Motil.* 21:335--344.

12. Baker, J.E., and D.D. Thomas. 2000. Thermodynamics and kinetics of a molecular motor ensemble. *Biophys. J.* 79:1731--6, doi: 10.1016/S0006-3495(00)76425-3.

13. Baker, J.E. 2023. Cells Solved the Gibbs Paradox by Learning How to Contain Entropic Forces. *Sci Rep* 13:16604, doi: 10.1038/s41598-023-43532-w.

14. Baker, J.E. 2023. Within-Scale Irreversible Kinetics of Thermal Turbines. *BioRxiv*, doi: 10.1101/2023.09.20.558706.

15. Baker, J.E. 2024. Across Thermal Scales: Nested Entropic Wells, Scale Creation, and the Relativity of Irreversibility. *BioRxiv*, doi: 10.1101/2024.02.15.580422.

16. Ellsworth, J.A., and J.E. Baker. 2025. Scaling in Biological Systems: A Molecular-Ensemble Dichotomy. *bioRxiv* 2025.01.31.635926, doi: 10.1101/2025.01.31.635926.

17. Wilson, C. 1974. Newton and Some Philosophers on Kepler's "Laws." *J. Hist. Ideas* 35:231, doi: 10.2307/2708760.

18. Carnot, S. 2005. Reflections on the Motive Power of Fire. Dover: New York.

19. Clausius, R. 1865. The Mechanical Theory of Heat: with its Applications to the Steam Engine and to Physical Properties of Bodies. John van Voorst: London.

20. Huxley, A.F. 1957. Muscle structure and theories of contraction. *Prog. Biophys. Biophys. Chem.* 7:255--318.

21. Hill, T.L. 1974. Theoretical formalism for the sliding filament model of contraction of striated muscle. Part I. *Prog. Biophys. Mol. Biol.* 28:267--340.

22. Cercignani, C. 1998. Ludwig Boltzmann: The Man Who Trusted Atoms. Oxford University Press.

23. Kadanoff, L.P. 1966. Scaling laws for ising models near Tc. *Physics Physique Fizika* 2:263--272, doi: 10.1103/PhysicsPhysiqueFizika.2.263.

24. Wilson, K.G. 1971. Renormalization Group and Critical Phenomena. I. Renormalization Group and the Kadanoff Scaling Picture. *Phys. Rev. B* 4:3174--3183, doi: 10.1103/PhysRevB.4.3174.

25. Appelquist, T., and J. Carazzone. 1975. Infrared singularities and massive fields. *Physical Review D* 11:2856--2861, doi: 10.1103/PhysRevD.11.2856.

26. Anderson, P.W. 1972. More Is Different: Broken symmetry and the nature of the hierarchical structure of science. *Science (1979).* 177.

27. Laughlin, R.B., and D. Pines. 2000. The theory of everything. *Proc. Natl. Acad. Sci. U. S. A.* 97:28--31, doi: 10.1073/pnas.97.1.28.

28. Cao, T.Y., and S.S. Schweber. 1993. The conceptual foundations and the philosophical aspects of renormalization theory. *Synthese* 97:33--108, doi: 10.1007/BF01255832.

29. Baker, J.E. 2024. What is the Power Stroke Mechanism of Muscle Contraction? *ArXiv*, doi: https://doi.org/10.48550/arXiv.2410.07193.

30. Baker, J.E. 2023. The Problem with Inventing Molecular Mechanisms to Fit Thermodynamic Equations of Muscle. *Int. J. Mol. Sci.* 24, doi: https://doi.org/10.3390/ijms242015439.
