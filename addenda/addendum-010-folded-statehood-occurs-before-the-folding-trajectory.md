---
r2d_id: addendum-010
title: Addendum 10 — Folded Statehood Occurs Before the Folding Trajectory
subtitle: Recursive Replacement, Conformational Multiplicity, and the Emergence of Protein Structure
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 10
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 1174
pdf_page_end: 1201
math_representation: LaTeX for normalized equations; source-faithful Unicode retained in noncritical schematic/prose expressions
equation_status: source_pdf_visual_reconstruction_and_standalone_render_qa
semantic_sync: 2026-09-25-no-substantive-universality-amendment-required
primitive_authority: false
review_status: author_reviewed
machine_revision: 2026-10-09-equation-reconstruction-v1
qa_status: standalone_render_pass_full_book_pending
promotion_date: null
equation_audit_scope: source_pdf_compared; clipped_text_flagged
---

# Addendum 10 — Folded Statehood Occurs Before the Folding Trajectory

## Recursive Replacement, Conformational Multiplicity, and the Emergence of Protein Structure

## Abstract

Protein folding is commonly described as a trajectory through conformational space.

An unfolded chain explores possible configurations, local interactions bias that exploration, and the protein
eventually reaches a folded structure.

That description is useful dynamically.

R²D asks a more primitive question:

> What makes the folded state a state at all?

The answer cannot be one unique microscopic trajectory.

A folded protein remains dynamically active. Its atoms vibrate, side chains reorient, loops fluctuate,
domains breathe, and local conformations continue to change. Many distinct subordinate configurations
and many different folding histories can nevertheless realize the same folded structure.

The folded state is therefore not identical to any one microscopic configuration or to any one folding path.

Let the subordinate conformational domain be

$$\Omega_{\mathrm{conf}}.$$

Let the folded-state classification be

$$\pi_{\mathrm{fold}}:\Omega_{\mathrm{conf}}\longrightarrow\mathcal M_{\mathrm{fold}}.$$

For folded macrostate $F_i$,

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|.$$

The multiplicity $W_F(i)$ counts the distinct subordinate conformational realizations that are the same folded
state with respect to the enclosing structural boundary.

Thus:

<!-- source_pdf_page: 1175 -->

> many subordinate conformations → one structural state.

The same replacement applies dynamically.

Distinct microscopic folding histories,

$$\Gamma_{\mathrm{fold}}^{(1)},\Gamma_{\mathrm{fold}}^{(2)},\ldots,\Gamma_{\mathrm{fold}}^{(m)},$$

can terminate in the same structural macrostate:

$$\pi_{\mathrm{fold}}[\Gamma_{\mathrm{fold}}^{(1)}]=\pi_{\mathrm{fold}}[\Gamma_{\mathrm{fold}}^{(2)}]=\cdots=F_i.$$

The folded protein therefore does not retain a unique folding trajectory as its state identity.

The trajectory is real at the boundary on which it occurs.

After folding, however, its path identity has been recursively replaced by structural statehood.

This reframes the classical folding problem.

The protein need not sequentially search every subordinate configuration in order to discover a unique
microscopic endpoint. The enclosing structural boundary already defines equivalence classes of
subordinate realizations. Folding is the realization of occupancy within that pre-existing structural
multiplicity landscape.

Sequence is essential because it constrains which structural states and subordinate realizations are
physically admissible.

The environment is equally important because solvent, ligands, membranes, partners, mechanical
constraint, temperature, and chemical conditions can alter the admissible landscape.

Thus the R²D architecture is not

> sequence → one privileged microscopic structure.

It is

   sequence + enclosing compatibility → structural multiplicity landscape → folded realization.

Once folded, subordinate dynamics continue.

A persistent structure can therefore coexist with extensive molecular fluctuation because those faster
recurrences are closure-complete relative to the structural boundary.

Protein structure is not a frozen microscopic configuration.

<!-- source_pdf_page: 1176 -->

It is a persistent enclosing classification of dynamically realized subordinate states.

The central statement is:

**A folded protein is not the endpoint of one privileged molecular trajectory. It is an enclosing structural…**

[Editorial source note: the archived PDF statement is clipped after “enclosing structur…”. The remainder requires author review.]

Hence:

> **Folded statehood occurs before the folding trajectory.**

Here “before” denotes logical and ontological priority of the state classification over any one trajectory that
realizes it, not earlier laboratory time.

## 1. The Folding Problem Is Usually Posed as a Trajectory Problem

A conventional folding picture begins with an unfolded chain.

The chain possesses many conformational degrees of freedom.

It explores a high-dimensional conformational space.

Local interactions alter the relative accessibility of different configurations.

Eventually the protein reaches a stable folded structure.

Schematically:

> unfolded chain → conformational search → folded protein.

This description captures an important physical process.

But it leaves the status of the folded state implicit.

What exactly is being reached?

## 2. A Folded Protein Is Not One Microscopic Configuration

Even a stable folded protein is not microscopically static.

Its subordinate molecular coordinates continue to change.

<!-- source_pdf_page: 1177 -->

Among the possible dynamics are:

- bond vibration;
- side-chain rotation;
- local backbone fluctuation;
- loop motion;
- hydration rearrangement;
- packing fluctuation;
- domain breathing;
- and larger conformational recurrence.

Therefore the folded state cannot generally be identified with one instantaneous subordinate configuration.

If it were, any local fluctuation would destroy the fold.

Experimentally, it does not.

The structural state persists while subordinate coordinates change.

Thus:

> **persistent structure is not persistent microscopic configuration.**

## 3. Structure Requires a New State Classification

Let

$$\Omega_{\mathrm{conf}}$$

denote the subordinate conformational domain relevant to a protein.

An element

$$x\in\Omega_{\mathrm{conf}}$$

specifies a subordinate realization at that level of description.

The folded boundary introduces a new classification:

$$\pi_{\mathrm{fold}}:\Omega_{\mathrm{conf}}\longrightarrow\mathcal M_{\mathrm{fold}}.$$

The codomain

$$\mathcal M_{\mathrm{fold}}$$

contains the structurally distinguishable folded macrostates.

<!-- source_pdf_page: 1178 -->

The fold is therefore defined at a different boundary from the individual subordinate conformations.

## 4. Many Subordinate Realizations Can Be One Folded State

For folded macrostate

$$F_i\in\mathcal M_{\mathrm{fold}},$$

the set

$$\pi_{\mathrm{fold}}^{-1}(F_i)$$

contains all subordinate realizations classified as the same folded state.

Its cardinality is

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|.$$

Thus:

$$W_F(i)>1$$

for a structurally persistent state realized by multiple subordinate conformations.

The subordinate configurations are distinguishable at their native boundaries.

They are degenerate with respect to the structural boundary.

## 5. Folded-State Multiplicity Replaces Subordinate Conformational Identity

The structural boundary does not need to retain every subordinate coordinate in order to identify the fold.

Instead:

> subordinate conformational identity → structural multiplicity.

This is the same replacement architecture developed in the myosin ensemble.

At the switch ensemble:

$$\mathbf x\overset{\pi_N}{\longmapsto}i.$$

<!-- source_pdf_page: 1179 -->

At the folding boundary:

$$x\overset{\pi_{\mathrm{fold}}}{\longmapsto}F_i.$$

In both cases, many lower-boundary realizations become one higher-boundary state.

## 6. Multiplicity Is Not Hidden Structural Detail

The preimage

$$\pi_{\mathrm{fold}}^{-1}(F_i)$$

should not be interpreted as a collection of partially visible versions of the “true” fold.

At the structural boundary they are one state.

Their distinctness belongs to the subordinate boundary.

Their number becomes the multiplicity of the enclosing structural state.

Thus:

structural multiplicity is not incomplete knowledge of one microscopic structure; it is the count of su

## 7. Folding Trajectories Are Replaced as Well

Replacement applies not only to instantaneous conformations.

It applies to histories.

Let

$$\Gamma_{\mathrm{fold}}^{(1)}$$

and

$$\Gamma_{\mathrm{fold}}^{(2)}$$

be two different folding trajectories.

They may visit different subordinate configurations, proceed through different intermediates, and undergo
different microscopic fluctuations.

<!-- source_pdf_page: 1180 -->

Yet both can realize the same folded state:

$$\pi_{\mathrm{fold}}[\Gamma_{\mathrm{fold}}^{(1)}]=\pi_{\mathrm{fold}}[\Gamma_{\mathrm{fold}}^{(2)}]=F_i.$$

The folded state therefore does not encode a unique folding history.

## 8. The Folding Path Is Boundary Owned

A folding trajectory is physically meaningful at the boundary on which its conformational distinctions are
readable.

The folded state belongs to a different boundary.

Thus:

$$\Gamma_{\mathrm{fold}}$$

is a legitimate subordinate trajectory,

but

$$\Gamma_{\mathrm{fold}}$$

is not the state identity of the folded protein after recursive replacement.

The enclosing state owns its own structural identity.

## 9. Folded Statehood Is Therefore Many-to-One

The folding relation is structurally non-invertible.

Many histories can produce the same folded state:

$$\Gamma_{\mathrm{fold}}^{(1)},\Gamma_{\mathrm{fold}}^{(2)},\ldots,\Gamma_{\mathrm{fold}}^{(m)}\longrightarrow F_i.$$

Therefore:

$$F_i\not\Rightarrow\Gamma_{\mathrm{fold}}.$$

uniquely.

Observing the folded protein does not recover one privileged microscopic path.

<!-- source_pdf_page: 1181 -->

## 10. The Fold Does Not Need to Remember How It Was Reached

A structural state can remain stable even when the precise subordinate history that realized it is no longer
readable.

This is a direct consequence of replacement.

The fold is specified by its enclosing classification, not by a stored microscopic record of every transition that
preceded it.

Thus:

> **structural persistence does not imply trajectory persistence.**

## 11. This Reframes the Folding Search Problem

The classical folding problem can be framed as a search through an enormous number of possible
conformations.

If each microscopic configuration were a candidate final state that had to be individually tested, the search
would appear prohibitively large.

R²D changes the state ontology.

The relevant structural states are not identical to all elements of

$$\Omega_{\mathrm{conf}}.$$

They are the equivalence classes defined by

$$\pi_{\mathrm{fold}}.$$

Thus:

$$\Omega_{\mathrm{conf}}\longrightarrow\mathcal M_{\mathrm{fold}}$$

is many-to-one.

The protein does not need to realize every subordinate microstate in order for a folded macrostate to exist.

<!-- source_pdf_page: 1182 -->

## 12. Folding Is Not Sequential Enumeration of Conformational Space

The existence of a large subordinate conformational domain does not imply that folding proceeds by
sequentially counting every element of that domain.

The structural classification exists independently of whether every subordinate realization is visited.

Thus:

> **large multiplicity does not imply sequential search.**

R²D therefore distinguishes:

> count of admissible realizations

from

> sequence of realized trajectories.

These are different objects.

## 13. The Folded Landscape Is Defined Before Any Particular Realization

For a given boundary definition, the structural state classes and their multiplicities are defined before one
particular folding event selects a realized path.

Thus:

> structural multiplicity landscape → folding realization.

The trajectory occupies the landscape.

It does not create the statistical state classification by traversing it.

## 14. Components Do Not Create the Structural Multiplicity Landscape

This parallels the result developed for the myosin ensemble.

At the ensemble boundary:

<!-- source_pdf_page: 1183 -->

$$W_N(i)=\binom{N}{i}$$

is defined by the state classification, not by which specific myosins happen to occupy $M_2$.

Likewise, for protein folding:

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|$$

is defined by the structural classification.

The particular molecular realization determines occupancy.

It does not define the existence of the enclosing multiplicity class.

## 15. Sequence Is Essential but Is Not the Fold

The amino-acid sequence strongly constrains the physical interactions available to the protein.

Sequence affects:

- local chemistry;
- steric compatibility;
- charge distribution;
- hydrophobicity;
- hydrogen bonding;
- packing;
- flexibility;
- interaction with the environment.

Thus sequence constrains which structural realizations are physically admissible.

But:

> **sequence is not the folded state.**

The sequence belongs to one physical description.

The folded structure belongs to an enclosing structural boundary.

## 16. The Environment Also Constrains the Folding Landscape

Protein structure is not realized in the absence of an enclosing physical relation.

<!-- source_pdf_page: 1184 -->

Relevant conditions can include:

     • solvent;
     • ionic environment;
     • pH;
     • temperature;
     • membrane environment;
     • ligands;
     • binding partners;
     • chaperones;
     • mechanical constraint;
     • covalent modification;
     • and crowding.

Therefore the admissible structural landscape should be represented schematically as

$$\mathcal M_{\mathrm{fold}}=\mathcal M_{\mathrm{fold}}(\text{sequence},\text{environment}).$$

The precise physical variables depend on the protein and experiment.

## 17. Enclosing Compatibility Precedes One Realized Fold

The important R²D ordering is:

> sequence + enclosing compatibility
>
> ⇓
>
> admissible structural landscape
>
> ⇓
>
> particular folded realization.

This does not deny local molecular mechanics.

It assigns those mechanics to the realization process rather than making one microscopic trajectory the
source of structural statehood.

## 18. A Different Environment Can Change Structural Statehood

If the enclosing physical relation changes, the admissible structural landscape can change.

Thus the same sequence can participate in different realized structures under different conditions.

<!-- source_pdf_page: 1185 -->

Schematically:

$$\text{sequence}+E_1\longrightarrow F_1,$$

while

$$\text{sequence}+E_2\longrightarrow F_2.$$

The sequence remains physically important.

But the realized structure belongs to the larger relation.

## 19. The Structural Boundary Can Therefore Be Created and Destroyed

A stable folded state need not exist under every physical condition.

Changing the enclosing compatibility can destroy one structural landscape and permit another.

Thus:

$$\text{folded statehood}$$

is not an immutable property of the sequence alone.

A structural boundary can emerge, persist, reorganize, and collapse.

This parallels the broader R²D principle that stable landscapes can be created and destroyed.

## 20. Folding Does Not End Molecular Dynamics

Once a folded state is realized, subordinate recurrence continues.

The protein still contains faster dynamics.

Schematically:

> IR recurrence
>
> ⇓
>
> fast molecular fluctuations
>
<!-- source_pdf_page: 1186 -->
>
> ⇓
>
> slower conformational recurrence.

These dynamics can continue while the enclosing structural classification remains unchanged.

Thus:

> **subordinate activity does not imply loss of the folded state.**

## 21. Protein Structure Is Therefore Dynamic

A persistent structural state should not be imagined as a frozen atomic arrangement.

R²D instead defines structure as a stable enclosing classification that tolerates a multiplicity of subordinate
realizations.

Thus:

protein structure is a persistent enclosing state realized through continuing subordinate dynamics.

This is a more natural description of a fluctuating protein.

## 22. Structural Persistence Requires Replacement

If every subordinate molecular fluctuation changed the structural state, no persistent fold could exist.

Persistence therefore requires that many subordinate changes become degenerate with respect to the
structural boundary.

That is:

$$x^{(1)},x^{(2)},\ldots\in\pi_{\mathrm{fold}}^{-1}(F_i).$$

The folded state persists precisely because these subordinate distinctions have been replaced at the
enclosing boundary.

## 23. Fluctuations Within a Fold Are Native Dynamics of Subordinate Boundaries

From the structural boundary, faster molecular motions can appear as fluctuations within one state.

At their native boundaries, those same motions can possess structured recurrence.

<!-- source_pdf_page: 1187 -->

Thus:

> subordinate native recurrence → structural fluctuation.

This extends Addendum 6 directly into protein structure.

## 24. A Structural Transition Occurs Only When the Enclosing Classification Changes

Not every molecular motion is a folding or unfolding event.

A structural transition occurs when the realized subordinate configuration crosses into a different enclosing
structural class:

$$\pi_{\mathrm{fold}}(x)=F_i$$

followed by

$$\pi_{\mathrm{fold}}(x^{\prime})=F_j,\qquad F_j\ne F_i.$$

The structural transition therefore belongs to the folded-state boundary, not to every microscopic
displacement.

## 25. Folding and Internal Fluctuation Are Boundary-Distinct Processes

This gives a clean distinction:

$$x\longrightarrow x^{\prime}$$

can be a real subordinate conformational change while

$$F_i\longrightarrow F_i$$

at the structural boundary.

Only when

$$F_i\longrightarrow F_j$$

does the enclosing structural state change.

<!-- source_pdf_page: 1188 -->

This is the same distinction previously developed between subordinate switch activity and ensemble
statehood.

## 26. Native-State Ensembles Are Natural in R²D

If a folded state contains many subordinate conformations, then an experimentally observed native-state
ensemble is not a complication added to an otherwise unique structure.

It is exactly what recursive structural statehood predicts.

The enclosing state can remain

$$F_i$$

while subordinate realization moves throughout

$$\pi_{\mathrm{fold}}^{-1}(F_i).$$

Thus structural heterogeneity and structural identity are compatible.

## 27. Multiple Folding Pathways Are Likewise Natural

Distinct folding pathways do not imply multiple final structural identities if they terminate within the same
structural class.

Thus:

$$\Gamma_1,\Gamma_2,\Gamma_3\longrightarrow F_i$$

is not anomalous.

It is the dynamic counterpart of structural multiplicity.

Different histories can be recursively replaced by one folded state.

## 28. The Native Fold Is Therefore Not a Historical Record

The folded structure does not need to encode whether it was reached by pathway 1, pathway 2, or pathway
3.

Unless the enclosing structural classification preserves such a distinction, the histories are degenerate after
replacement.

<!-- source_pdf_page: 1189 -->

Thus:

> **same fold does not imply same history.**

## 29. Folding Memory Requires an Additional Distinction

If a protein retains a physically consequential memory of its folding history, then that memory must itself
become a readable state distinction at some boundary.

For example, if two apparently similar structures behave differently because their histories produced
persistent differences, then those differences belong to a larger state classification.

R²D does not forbid history dependence.

It requires history dependence to be physically readable somewhere.

Thus:

> persistent history → new distinction.

## 30. Misfolding Is a Different Enclosing Structural Classification

A misfolded state should not be described merely as an incorrect microscopic trajectory.

It is a distinct structural macrostate:

$$F_{\mathrm{native}}\ne F_{\mathrm{misfolded}}.$$

Each can possess its own multiplicity:

$$W_{\mathrm{native}},\qquad W_{\mathrm{misfolded}}.$$

Different subordinate histories may realize either state.

The distinction belongs to the enclosing structural boundary.

## 31. Folding Competition Is Competition Between Structural Realizations

Where multiple folded or misfolded states are admissible, the relevant question is not which microscopic
configuration is uniquely correct.

<!-- source_pdf_page: 1190 -->

It is which structural state is realized under the enclosing conditions.

Thus:

$$F_1,F_2,\ldots\in\mathcal M_{\mathrm{fold}}.$$

Their realized occupancy depends on the structure of the enclosing landscape.

The detailed physical mapping may involve free-energy and kinetic coordinates.

R²D does not replace those calculations.

It assigns them boundary ownership.

## 32. Energy Landscapes Can Be Valid Physical Projections

Conventional protein-folding landscapes remain useful.

R²D does not require them to be discarded.

They can represent the physical accessibility and stability of structural states and subordinate transitions.

The R²D claim is that the landscape should not be interpreted as proof that one persistent microscopic
trajectory is the primitive ontology of the folded protein.

Thus:

> **a useful folding landscape does not imply trajectory ontology.**

## 33. The Folding Funnel Can Be Reinterpreted as Replacement

A funnel-like landscape is often interpreted as progressively restricting conformational search.

R²D permits a different interpretation.

As enclosing compatibility becomes increasingly restrictive, many subordinate realizations become
equivalent with respect to a smaller set of structural macrostates.

Thus a funnel can be understood as increasing organization of admissible multiplicity.

Schematically:

<!-- source_pdf_page: 1191 -->

> broad subordinate realization → increasing compatibility → stable structural state.

This is a replacement architecture rather than a literal exhaustive search.

## 34. The Levinthal Problem Is Therefore a Projection Problem

The apparent paradox arises when the number of subordinate conformations is interpreted as the number
of states that must be sequentially visited.

But:

$$\left|\Omega_{\mathrm{conf}}\right|$$

is not the same quantity as

$$\left|\mathcal M_{\mathrm{fold}}\right|.$$

Nor is either necessarily the number of states traversed by one realized path.

Therefore:

> **multiplicity of possibilities is not the length of a realized trajectory.**

The paradox follows from conflating these counts.

## 35. Recursive Replacement Removes the Need for Exhaustive Search

A particular folding event realizes one path.

It need not visit every subordinate realization compatible with the final state.

The folded macrostate exists because the boundary classification groups many possible subordinate
realizations together.

Thus:

> −1

$$\text{folding}\ne\text{enumeration of }\pi_{\mathrm{fold}}^{-1}(F_i).$$

The protein realizes one of many admissible paths into an enclosing structural class.

<!-- source_pdf_page: 1192 -->

## 36. This Does Not Derive Folding Kinetics From R²D Alone

R²D does not, from the replacement map alone, calculate:

- folding rates;
- transition-state barriers;
- pathway probabilities;
- solvent friction;
- specific contact formation;
- atomistic mechanisms.

Those remain physical bridge problems.

The R²D result concerns state ownership.

It identifies what a folded state is relative to the trajectories that realize it.

## 37. Folding Kinetics Belong to the Realization Process

A measured folding rate describes how rapidly subordinate realization changes into the enclosing structural
state.

Thus kinetic variables belong to the physical mapping:

> subordinate dynamics → structural realization.

They do not by themselves define structural statehood.

This distinction parallels the separation between switch kinetics and muscle-scale function.

## 38. A Folded State Can Have Its Own Native Recurrence

Once established, the structural boundary can itself possess dynamics among its own distinguishable
macrostates.

For example:

$$F_i\longrightarrow F_j\longrightarrow F_i.$$

That recurrence belongs to the structural boundary.

It is not simply the continuation of the microscopic folding trajectory.

<!-- source_pdf_page: 1193 -->

Thus:

$$\Gamma_{\mathrm{subordinate}}\ne\Gamma_{\mathrm{structure}}.$$

Recursive replacement occurs before structural recurrence.

## 39. This Connects Folding Directly to Addendum 6

Addendum 6 established:

> subordinate closure → replacement → new enclosing recurrence.

Protein folding supplies a concrete structural realization of that rule.

Faster conformational recurrences close.

Their consequences are replaced into folded statehood.

The folded state can then possess its own slower dynamics.

## 40. This Connects Folding to Addendum 7

Addendum 7 showed that changing probe frequency can shift the read boundary.

A folded protein can therefore be measured at:

- slow structural recurrence;
- faster conformational dynamics;
- still faster molecular vibration.

The protein remains the same physical system.

The dynamically read boundary changes.

Thus:

$$B_{\mathrm{sys}}=B_{\mathrm{protein}}$$

can coexist with

$$B_{\mathrm{read}}=B_{\mathrm{read}}(f_p).$$

Protein folding therefore sits naturally within the frequency-selected readability program.

<!-- source_pdf_page: 1194 -->

## 41. This Connects Folding to Addendum 8

Addendum 8 argued that biology makes replacement observable because several neighboring boundaries
remain experimentally accessible.

Protein folding is another direct example.

One can identify:

> subordinate conformational dynamics
>
> ⇓
>
> persistent structural state.

Their relation can therefore be deprojected.

The fold is not inferred solely from invisible subordinate mechanics.

It is an experimentally distinguishable enclosing state.

## 42. The Folded Protein Is a Structural Boundary, Not a Static Object

This point summarizes the R²D ontology.

A folded protein is not defined by frozen atoms.

It is defined by persistence of an enclosing structural classification despite continual subordinate
replacement.

Thus:

> folded protein = persistent structural statehood

rather than:

> folded protein = one persistent microscopic configuration.

## 43. Structural Persistence Is Therefore Recursive

The fold persists because subordinate molecular recurrence repeatedly realizes the same enclosing state
classification.

<!-- source_pdf_page: 1195 -->

Schematically:

$$\mathcal C_1,\mathcal C_2,\mathcal C_3,\ldots\overset{\kappa}{\longmapsto}F_i.$$

The subordinate realization changes.

The enclosing structural state persists.

Persistence itself is therefore recursively realized.

## 44. Principle — Folded Statehood Is Boundary Owned

A folded state is defined by a structural classification

$$\pi_{\mathrm{fold}}:\Omega_{\mathrm{conf}}\longrightarrow\mathcal M_{\mathrm{fold}}.$$

The folded macrostate belongs to the enclosing structural boundary.

It is not identical to one subordinate conformation.

## 45. Principle — Structural Multiplicity Replaces Conformational Identity

For folded state $F_i$,

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|.$$

The subordinate realizations within the preimage are distinct at their native boundary and degenerate at
the folded boundary.

## 46. Principle — Folding History Does Not Define Folded Identity

Different subordinate histories can realize the same folded state:

$$\Gamma_{\mathrm{fold}}^{(1)},\Gamma_{\mathrm{fold}}^{(2)},\ldots\longrightarrow F_i.$$

Therefore:

> **folded identity is not a unique folding history.**

<!-- source_pdf_page: 1196 -->

## 47. Principle — Sequence Constrains Structure but Is Not Structure

Sequence determines important physical constraints on the admissible structural landscape.

But:

> **sequence is not the folded state.**

The folded state is realized only within an enclosing physical environment.

## 48. Principle — Enclosing Compatibility Precedes Structural Realization

The admissible folding landscape depends on both sequence and environment:

$$\text{sequence}+\text{enclosing compatibility}\longrightarrow\mathcal M_{\mathrm{fold}}.$$

A particular fold is then realized within that landscape.

## 49. Principle — A Folded Protein Remains Dynamically Active

Persistent structural identity is compatible with continual subordinate recurrence.

Thus:

> **stable fold does not imply a static molecule.**

Subordinate dynamics can remain active while closure-complete relative to the structural boundary.

## 50. Principle — Folding Is Not Exhaustive Conformational Search

The multiplicity of the conformational domain does not equal the number of configurations that must be
sequentially visited.

Thus:

> **possibility count is not trajectory length.**

The folded state is a many-to-one structural classification.

<!-- source_pdf_page: 1197 -->

## 51. Principle — Structural Dynamics Follow Structural Replacement

Once the folded boundary exists, it can possess its own native recurrence.

Thus:

> subordinate conformational closure → folded statehood → structural recurrence.

The structural trajectory is not the preserved continuation of the folding trajectory.

## 52. Logical Status

Established by Addenda 5–8

Recursive replacement is many-to-one, subordinate trajectories are boundary owned, and persistent
enclosing statehood can coexist with continuing subordinate dynamics.

New Structural Classification

$$\pi_{\mathrm{fold}}:\Omega_{\mathrm{conf}}\longrightarrow\mathcal M_{\mathrm{fold}}.$$

New Structural Multiplicity

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|.$$

New Structural Result

Multiple subordinate conformations and multiple folding histories can realize one persistent folded
macrostate.

R²D Interpretation

Protein structure is a persistent enclosing classification of dynamically changing subordinate realizations.

Folding-Problem Interpretation

The number of possible subordinate conformations should not be identified with the number of states that
one realized folding trajectory must sequentially search.

Sequence Interpretation

Sequence constrains the admissible structural landscape but is not identical to realized structural
statehood.

<!-- source_pdf_page: 1198 -->

Environmental Interpretation

The enclosing physical environment participates in defining which structural states are admissible and
realized.

Not Yet Claimed

This addendum does not derive:

- an atomistic folding mechanism;
- folding-rate constants;
- transition-state energies;
- detailed free-energy surfaces;
- the native structure of a particular amino-acid sequence;
- a universal algorithm for protein-fold prediction.

It establishes the boundary architecture of folded statehood.

## 53. The Folding Architecture

The full R²D folding sequence can be represented as:

> sequence + enclosing physical relation
>
> ⇓
>
> admissible structural multiplicity landscape
>
> ⇓
>
> $\Omega_{\mathrm{conf}}$
>
> ⇓ $\pi_{\mathrm{fold}}$
>
> $F_i$

with

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|.$$

Dynamically:

> $\Gamma_{\mathrm{fold}}$
>
> ⇓
>
> $\mathcal C_{\mathrm{subordinate}}$

<!-- source_pdf_page: 1199 -->

> ⇓ $\kappa_{\mathrm{fold}}$
>
> $F_i$.

After the fold is established:

$$F_i\longrightarrow F_j\longrightarrow F_i$$

can define native structural recurrence.

The folding trajectory has been replaced.

The structural boundary now owns the state.

## 54. Conclusion

Protein folding appears paradoxical when the folded protein is identified with one microscopic endpoint
reached by a trajectory searching an enormous conformational space.

R²D rejects that identification.

The folded protein is an enclosing structural state.

Its subordinate conformational domain can be written

$$\Omega_{\mathrm{conf}}.$$

Its structural state classification is

$$\pi_{\mathrm{fold}}:\Omega_{\mathrm{conf}}\longrightarrow\mathcal M_{\mathrm{fold}}.$$

For folded state $F_i$,

$$W_F(i)=\left|\pi_{\mathrm{fold}}^{-1}(F_i)\right|.$$

Many subordinate molecular configurations are therefore the same folded state with respect to the
enclosing structural boundary.

The same is true dynamically.

Distinct folding histories can arrive at the same structural state:

$$\Gamma_{\mathrm{fold}}^{(1)},\Gamma_{\mathrm{fold}}^{(2)},\ldots\longrightarrow F_i.$$

The fold does not retain one privileged trajectory as its identity.

<!-- source_pdf_page: 1200 -->

That trajectory remains physically real at the boundary on which it occurred.

After recursive replacement, however, the folded protein possesses a new state classification.

This reframes the conventional folding-search problem.

The number of possible subordinate conformations is a multiplicity count.

It is not the number of configurations that one realized trajectory must visit sequentially.

Thus:

> **possibility multiplicity is not trajectory length.**

Sequence remains essential.

It constrains the molecular interactions and admissible structural landscape.

But sequence is not itself the folded state.

The enclosing physical relation also matters.

Solvent, ligands, binding partners, membranes, mechanical constraints, and other physical conditions can
change which structural states are admissible and which are realized.

Thus the appropriate causal architecture is:

  sequence + enclosing compatibility → structural multiplicity landscape → folded realization.

Once folded, the protein remains dynamically active.

Subordinate recurrence continues.

Fast molecular motions continue.

Conformations fluctuate.

Yet the enclosing structural state can persist.

This is not a contradiction.

It is the expected consequence of recursive replacement.

The subordinate dynamics remain physically real at their own boundaries.

<!-- source_pdf_page: 1201 -->

Their completed distinctions are degenerate with respect to the enclosing structural state.

Protein structure is therefore not a frozen molecular configuration.

It is persistent statehood realized through ongoing subordinate dynamics.

The central result is:

**A folded protein is not the endpoint of one privileged molecular trajectory. It is an enclosing structural…**

[Editorial source note: this repeated statement is clipped in the archived PDF on page 1201. The remainder requires author review.]

Hence:

> **Folded statehood occurs before the folding trajectory.**
