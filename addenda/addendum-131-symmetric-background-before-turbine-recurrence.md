---
r2d_id: "addendum-131"
title: "Addendum 131 — Symmetric Background Before Turbine Recurrence"
subtitle: "Reciprocal Fluctuation, Directed Completion, and the Enclosing Ownership of the Clock"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 131
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-13"
scope: "Finite enclosing compatibility, symmetric recurrence, actomyosin equilibrium and driving, background recurrence, and physical calibration limits"
---

# R²D Addendum 131 — Symmetric Background Before Turbine Recurrence

*Reciprocal Fluctuation, Directed Completion, and the Enclosing Ownership of the Clock*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I–III (September 25, 2026); Addenda 105, 112, 120, and 122–125.  
**Purpose:** Establish the finite count conditions under which a symmetric enclosing relation owns nonzero turbine recurrence; distinguish that recurrence from net directional cycling; identify what remains open in assigning the enclosing background a physical clock.

## Abstract

A thermal turbine can continue to realize distinct states in the absence of net directional bias. At nucleotide equilibrium, actomyosin nucleotide-dependent transitions do not cease; the chemical relation no longer sustains net ATP-hydrolysis throughput. A maintained ATP–ADP–phosphate gradient gives direction to realizations of the same nucleotide-coupled architecture. The two conditions do not require two turbines or a new subordinate mechanism. They require different enclosing compatibility and constraint relations for the same locally readable state architecture.

This addendum gives the positive counterpart of Addendum 112's critique of thermal fluctuations as inferred persistent subordinate trajectories. An enclosing **symmetric** relation is not the absence of organization; it can admit positive completed-return activity while defining no preferred orientation. An enclosing **asymmetric** relation can change the direction of that activity. R²D attributes the organization of compatible realization to the enclosing boundary. The proposed stronger interpretation—that the symmetric enclosing background itself fixes realized recurrence—is isolated as a physical hypothesis rather than silently assumed from symmetry.

We define orientation-even and orientation-odd completed-closure counts, prove reversal identities, and derive a finite complete-record recurrence theorem without kinetic rates, physical time, energy levels, or probabilities. An exact twelve-position construction demonstrates two symmetric enclosing domains with identical native state counts but distinct completed-recurrence ratios. Consequently, static symmetry does not uniquely determine the clock: a complete enclosing recurrence relation must be supplied. We distinguish possible compatibility counts from realized background, local closure from net directed throughput, recurrence count from physical frequency, and the thermal scale $k_BT/h$ from an independently identified native background clock. The result supplies a controlled mathematical premise for examining complementary quantum and gravitational projections, without claiming to have derived a universal physical $c$.

## 131.1. The target: what organizes reciprocal recurrence?

The usual mechanistic account begins with nucleotide binding and release, conformational changes, and molecular motions, then describes fluctuations and directed cycling as their aggregate result. R²D asks an earlier question: which enclosing organization defines the states and compatible relations through which those events are realized?

The proposed answer is one enclosing chemical and thermal relation, read under two conditions:

- **Symmetric compatibility:** opposed turbine realizations remain admitted without a preferred net cycle direction. Positive activity is possible and may be realized.
- **Asymmetric compatibility:** the same native turbine architecture is realized under an enclosing directional preference, which can sustain net completed cycling and distinguishable output.

The turbine is not replaced when a chemical gradient appears. The permissible states and their structural coupling may remain unchanged; their enclosing compatibility, realized occupancy, and recurrence statistics can change.

The new question is not whether symmetry generates a directional force. It is whether a symmetric enclosing relation **organizes positive recurrence in the first place**, so that what is called thermal fluctuation is a subordinate read of an already enclosing-defined recurrent relation.

## 131.2. Count types and causal order

Fix a local boundary $B$ and enclosing boundary $J$. A readable local state $i$ has native multiplicity

$$W_{B,i}=|\pi_B^{-1}(i)|,$$

and compatible enclosing extension multiplicity

$$\Theta_{J\mid B,i}.$$

Part I defines

$$K_{J\mid B,i}=\frac{\Theta_{J\mid B,i}}{W_{B,i}},\qquad P_{B,i}=\ln K_{J\mid B,i}.$$

These are **possible-count** quantities. Their directional differences can bias realized occupancy through the R²D relation

$$\Delta G^{\mathrm{occ}}=\Delta\tau+\Delta P-\Delta R.$$

A completed local macrostate return acquires **closure** meaning when it is compatible with an enclosing occurrence. Its whole-closure recurrence count in one comparison domain is

$$N_{\mathcal D_R}(\mathcal C_B).$$

This count is not native multiplicity, a state-occurrence count, or the count of a single nucleotide-binding leg. Background is another distinct read: Part I defines realized nondirectional background $b_J>0$ and $\Phi_J=\ln b_J$. Part III separately denotes recurring background realization by $N_J^\Phi$.

No primitive identity $\Theta=b_J$ or $P=\Phi_J$ is assumed. The expression **symmetric background organization** in this addendum means the enclosing compatible relation that is nondirectional with respect to the selected alternatives; it does not redefine the canonical realized-background count as possible multiplicity.

The causal claim is **enclosing definition of compatible realization**, not that raw possible multiplicity itself equals the number of physical transitions that occur. This distinction remains essential throughout.

## 131.3. One turbine and two orientations

A binary return $A\to B\to A$ suffices to show completion but does not, from state labels alone, distinguish clockwise from counterclockwise circulation. For a minimal oriented construction use one turbine with three readable stages $A,B,C$. Define

$$\mathcal C_+:A\to B\to C\to A,$$

$$\mathcal C_-:A\to C\to B\to A.$$

They are two orientations of **one** turbine. Let a complete realized record $h$ in a specified common recurrence-comparison domain have nonnegative integer counts

$$N_+(h),\qquad N_-(h).$$

Its orientation-even and orientation-odd coordinates are

$$\boxed{N_{\mathrm{even}}(h)=N_+(h)+N_-(h),} \tag{131.1}$$

$$\boxed{N_{\mathrm{odd}}(h)=N_+(h)-N_-(h).} \tag{131.2}$$

A reciprocal record can satisfy $N_{\mathrm{odd}}=0$ while $N_{\mathrm{even}}>0$. A directionally biased realized record has $N_{\mathrm{odd}}\ne0$. These are **completed-cycle** coordinates; they must not be substituted for opposed-leg occurrence counts in Part I's Second Law.

A local return such as $\mathcal C_+$ is still a closure when enclosing-compatible, even at symmetric equilibrium. Thus **closure** must not be reserved for the driven regime. What distinguishes sustained chemical driving is **net oriented cycle completion**, not the first existence of locally completed returns.

## 131.4. Theorem 1 — Orientation reversal preserves even recurrence

Let $\Gamma_J$ be a finite, enclosing-admitted domain of complete turbine records. Suppose there is an orientation-reversal involution

$$\sigma:\Gamma_J\to\Gamma_J,\qquad\sigma^2=\mathrm{id},$$

that preserves the background reference count and exchanges cycle orientations:

$$N_J^\Phi(\sigma h)=N_J^\Phi(h),$$

$$N_+(\sigma h)=N_-(h),\qquad N_-(\sigma h)=N_+(h).$$

Then

$$\boxed{N_{\mathrm{even}}(\sigma h)=N_{\mathrm{even}}(h),} \tag{131.3}$$

$$\boxed{N_{\mathrm{odd}}(\sigma h)=-N_{\mathrm{odd}}(h).} \tag{131.4}$$

**Proof.** Substitute the two exchanged counts into (131.1)–(131.2). Their sum is unchanged and their difference changes sign. $\square$

In particular, reversal symmetry of the **admissible domain** pairs possible records of equal even count with opposite odd count. Hence the aggregate native incidence sum over the complete domain satisfies

$$\sum_{h\in\Gamma_J}N_{\mathrm{odd}}(h)=0.$$

**Qualification.** This is an identity over possible complete records, not a theorem that every realized record has zero net cycling. If realization favors some records over their reversed partners, actual net throughput may remain nonzero despite symmetric support. Equal realized forward and reverse counts require a reciprocal **realization** condition, not just the existence of a reversal map. In a physical equilibrium system, detailed balance is a downstream experimentally supported realization condition, not a substitute for R²D native compatibility.

## 131.5. A finite symmetric well with a determined recurrence ratio

Take a specified enclosing background-reference cycle with twelve distinguishable reference occurrences. Denote its completed reference count by

$$N_J^\Phi=12.$$

This count labels background recurrence positions, not seconds and not the scalar $b_J$.

Let the enclosing relation admit cyclic translations of the following *complete* turbine record and its orientation reversal:

$$h_F:\quad A\,B\,C\,A\,C\,B\,A\,B\,C\,A\,C\,B\;(\to A).$$

The cyclic record contains two forward and two reverse complete oriented cycles, with no intervening unpaired state-changing leg:

$$N_+(h_F)=2,\qquad N_-(h_F)=2.$$

Consequently,

$$N_{\mathrm{even}}(h_F)=4,\qquad N_{\mathrm{odd}}(h_F)=0.$$

Its dimensionless local-to-background recurrence ratio is

$$\boxed{\chi_F=\frac{N_{\mathrm{even}}}{N_J^\Phi}=\frac4{12}=\frac13.} \tag{131.5}$$

Because each permitted cyclic translation and reversal has the same counts, the ratio is fixed for every admitted complete record. This is an exact determination by the **specified enclosing relation**; no kinetic rate or physical time has been introduced.

Now hold the turbine architecture, reference count, and one-position state multiplicities fixed, but consider a second symmetric enclosing relation admitting translations and reversal of

$$h_S:\quad A\,A\,B\,B\,C\,C\,A\,A\,C\,C\,B\,B\;(\to A).$$

Runs of identical states contribute no state-changing leg. This record has one forward and one reverse completed cycle:

$$N_+(h_S)=1,\qquad N_-(h_S)=1,$$

so

$$\boxed{\chi_S=\frac2{12}=\frac16.} \tag{131.6}$$

Both records contain four occurrences each of $A$, $B$, and $C$ in the twelve reference positions. Both are orientation-balanced, and both are supported by a symmetric enclosing relation. Yet $\chi_F\ne\chi_S$.

**Counterexample.** Identical one-position state counts and zero net cycle direction do not determine gross completed recurrence. The complete enclosing *ordered* compatibility relation determines which count ratios are admitted.

## 131.6. Theorem 2 — Exact enclosing determination of a symmetric recurrence ratio

For any finite complete-record domain $\Gamma_J$, assign each admitted record $h$ a positive background reference count $M(h)=N_J^\Phi(h)$ and a completed local even count $E(h)=N_{\mathrm{even}}(h)$.

Define

$$\chi_J(h)=\frac{E(h)}{M(h)}.$$

The enclosing relation **uniquely fixes a nonzero dimensionless symmetric recurrence ratio** if and only if there exists $\chi_J>0$ such that

$$\boxed{E(h)=\chi_JM(h)\quad\text{for every admitted realized complete record }h.} \tag{131.7}$$

Equivalently, for every two records $h,h'$ in that admitted realized support,

$$\boxed{E(h)M(h')=E(h')M(h).} \tag{131.8}$$

**Proof.** Equations (131.7) and (131.8) are equivalent to constancy of $E(h)/M(h)$ on the specified positive-denominator domain. If constant, each admitted realized record has the same ratio; if the ratio is fixed, all cross-products agree. $\square$

**Scope.** The theorem is a necessary-and-sufficient **count specification criterion**, not a derivation of which complete records nature realizes. If $\Gamma_J$ is merely the set of possible records, constancy on that entire set is a sufficient condition for every realized subset, but realized counts do not generally equal possible counts. If different ratios remain possible, an additional enclosing realization constraint is needed to select the observed ratio. Addenda 124–125 already establish this distinction for competing completed-closure configurations.

## 131.7. Complete recurrence compatibility is stronger than pair counts

A single-state multiplicity landscape $W_i$ cannot recover the ordered complete-return count. Nor do arbitrary two-time marginal counts necessarily recover it, because records with the same pair incidences may differ in which legs are jointly admitted as one completed closure. A full enclosing record specifies the compatibility of the entire return, not merely individual adjacent transitions.

In a specially constrained three-stage turbine where every nontrivial transition belongs to exactly one disjoint completed three-leg cycle, the count of off-diagonal legs $E_{\mathrm{leg}}$ satisfies

$$N_{\mathrm{even}}=\frac{E_{\mathrm{leg}}}3.$$

Without the disjoint-complete-cycle condition, this identity is not authorized: partial paths, other cycle lengths, and overlapping decompositions must remain explicit. In particular, the count of an ATP-binding event is not automatically the count of one completed ATPase turbine closure.

## 131.8. Symmetric and asymmetric enclosing relations are conditions of one turbine

Where two orientation-conditioned **complete-cycle** classes are independently defined, let their native possible enclosing extension factors be $K_+$ and $K_-$, each obtained from the relevant complete enclosing-compatible count divided by its corresponding native local multiplicity. The directional possibility comparison, when those classes form an admissible R²D state comparison, is

$$\Delta P_{+\mid-}=\ln\frac{K_+}{K_-}.$$

One may algebraically decompose these possible supports as

$$S_K=\frac{K_++K_-}2,\qquad D_K=\frac{K_+-K_-}2.$$

Then $K_\pm=S_K\pm D_K$. At $D_K=0$, the relation is orientation-symmetric; at $D_K\ne0$, it is orientation-biased. The same local turbine can be admitted under either condition.

Neither equality $K_+=K_-$ nor inequality $K_+\ne K_-$ fixes the **realized** counts $N_\pm$ by itself. In particular, $K_+K_-={\mathrm{constant}}$ is *not* a primitive R²D invariant across changes of enclosing condition. The hyperbolic identities available from positive pairs of counts are algebraic, not proofs of physical fixed-product coupling.

Part I further distinguishes local closure asymmetry $\Delta A_{\mathcal C}$ from whole-closure recurrence and from the directional occurrence-count efficiency $\eta$. Its recurrence-weighted law is applied only to the specified compatible enclosing transition and representative peer closure. It cannot be repurposed at $\Delta A_{\mathcal C}=0$ to determine the absolute symmetric cycling frequency by division.

Finally, the realized background change postulated by Part I,

$$\delta_{\mathcal C}\Phi_J=L_{\tau,\mathcal C}=\ln\frac{\nu_H}{\nu_L},$$

uses opposed **leg occurrence counts** $\nu_H,\nu_L$, not the possible extension counts $K_\pm$ and not the completed oriented-cycle counts $N_\pm$. Under reciprocal leg realization, the background *increment* vanishes; an existing positive background and positive symmetric recurrence may remain. Thus the background may scale under nonreciprocal realization without requiring background production as the cause of equilibrium recurrence.

## 131.9. Actomyosin as the motivating thermal realization

Consider one nucleotide-coupled actomyosin architecture under alternative enclosing chemical relations.

**Equilibrium ATP–ADP–$P_i$ environment.** Nucleotide binding, hydrolysis-related changes, dissociation, rebinding, and reverse reaction occurrences can continue when the chemical affinities are balanced. The *net* steady-state chemical-cycle flux vanishes under detailed balance, but gross transition activity need not. For example, ATP binding promotes detachment of strongly bound actomyosin; the myosin–ADP–$P_i$ state generally has weak actin affinity. These are distinct biochemical pathways within the same nucleotide-coupled state architecture, not interchangeable reactions.

**Maintained ATP-hydrolysis gradient.** Changing nucleotide activities changes enclosing chemical compatibility and favors one direction of the coupled cycle. The native state architecture need not be reconstructed; the directed incidence of completed realizations and associated mechanical output can change.

**Nucleotide-free rigor limit.** Without ATP, there is no ATP-binding-induced detachment and no sustained nucleotide-dependent ATPase cycle. This is a statement about the specified nucleotide-driven closure class, not a claim that all protein fluctuations or rare actin-binding events vanish.

Conventional second-order binding and detailed-balance measurements supply strong physical tests of this distinction. They need not be installed as primitive R²D kinetic-rate laws. The R²D causal thesis is that the enclosing chemical relation defines the compatibility and directional significance of these subordinate realizations, not that an isolated motor creates the ensemble chemical gradient.

A fixed protein architecture can therefore support reciprocal state activity in one enclosing chemical environment and net directed turbine cycling in another. The biological transition mechanisms remain indispensable realizers; their rates need not remain numerically identical when the enclosing chemical conditions change.

## 131.10. The leapfrog and the status of the causal claim

The leapfrog is a recursive, not chronological, relationship:

$$\text{enclosing compatibility}\ \Longrightarrow\ \text{admitted subordinate realization}\ \xrightarrow{\text{recursive read}}\ \text{new enclosing count meaning}.$$

The first arrow states causal priority of enclosing classification. The second is **recursive carry**, a change in count meaning, not bottom-up creation of the enclosing organization. No persistent native microstate identity across boundary changes is required.

The proposed *Symmetric Background Recurrence Principle* is:

> A symmetric enclosing compatibility relation may organize recurrent realizations of one turbine without producing net directional output. Asymmetric enclosing compatibility may direct the realization of the same turbine. The apparent subordinate fluctuation is a boundary-specific read of the enclosingly organized recurrence, not the primitive cause of the enclosing background.

The canon already gives enclosing ownership of compatible states and the many-to-one recursive clock. The strengthened assertion that **the symmetric background uniquely determines the actual recurrence clock for every physical turbine** requires more than orientation symmetry: it requires an independently justified complete recurrence compatibility and realization rule, as specified in Theorem 2. The finite construction proves consistency and conditional determination, not automatic universal positive recurrence from a scalar background count.

## 131.11. Thermal clock calibration and internal energy

In Part II, temperature is a physical read of thermal enclosing compatibility, not a primitive result of aggregating independently energetic molecular objects. For a restricted reservoir mapping,

$$\frac1{k_BT}=-\frac{\partial P^{\mathrm{th}}}{\partial\varepsilon}.$$

This is a thermodynamic slope calibration, not a native clock law. Likewise,

$$f_T=\frac{k_BT}{h}$$

is a frequency-equivalent energetic scale, not automatically the completed recurrence frequency $f_J^\Phi$ of a specified background closure.

When both a turbine closure and a compatible reference background have independently established physical frequency reads over the same physical interval, their count comparison yields

$$\boxed{\frac{f_B}{f_J^\Phi}=\chi_J.} \tag{131.9}$$

A proposed identification

$$f_J^\Phi=\alpha_J\frac{k_BT}{h}$$

therefore gives

$$f_B=\chi_J\alpha_J\frac{k_BT}{h}.$$

Neither Theorem 1 nor Theorem 2 fixes the physical coefficient $\alpha_J$. The internal-energy read of a thermal state must be reconstructed within that enclosing thermal calibration; it is not a primitive energy assigned to a hidden object and then used to explain the background. Temperature alone, however, need not determine the numerical internal energy without the specified thermal system and its compatible count structure.

## 131.12. Quantum and gravitational horizon implications

Part III describes complementary limits of joint recursive readability. At the quantum horizon, a recurrence or spectral response may remain readable while a unique continuously resolved subordinate distinction is not. At the gravitational horizon, a spatial/geometric distinction may remain readable while the relevant **enclosing organizing recurrence** is not. Neither statement means that all physical motions, all clocks, or all spectral responses disappear.

Background may remain a scale and frame reference across both limits. Thus the same proposed causal ordering could be represented differently:

$$\text{thermal joint read}\longrightarrow\begin{cases}\text{quantum: recurrence-side read},\\\text{gravitational: geometry-side read}.\end{cases}$$

This is a **research target**, not yet an identity between a quantum frequency and gravitational geometry. A quantum IR frequency is not automatically the rate of complete structural return. Gravitationally observable orbital motion is not automatically the unreadable enclosing recurrence class. Both require faithful, boundary-native physical identifications.

Nor does a common count recurrence ratio by itself derive $c$. A universal physical speed would additionally require a justified joint spatial–temporal calibration and its invariance across appropriate physical frames. Those questions belong to the proposed companion Addendum 132 and further physical tests.

## 131.13. Experimental and finite falsification targets

A finite or physical candidate for the symmetric-background clock can be tested by checking: (i) that the complete enclosing recurrence relation is independently specified, rather than inferred from the desired rate; (ii) that turbine occurrence, complete return, background realization, and net oriented throughput are counted separately; (iii) that symmetric possible support is not mistaken for equal realized counts without an appropriate reciprocity condition; (iv) that a predicted $\chi_J$ is constant across every claimed admissible realization in the same comparison class; and (v) that any conversion to hertz is independently calibrated.

In actomyosin, the direct physical audit should compare gross nucleotide-dependent state transitions, independently identified full ATPase-cycle returns, their directional chemical throughput, and enclosing nucleotide activity and mechanical constraints. A successful model must predict changes in recurrence while keeping the native state architecture fixed where the experiment does. It must also distinguish the disappearance of a particular nucleotide-driven event class in rigor from the persistence of other molecular activity.

## 131.14. Results and limits

**Established in this addendum:**

1. Orientation reversal leaves the even completed-cycle count invariant and reverses the odd count (Theorem 1).
2. Orientation-symmetric possible support does not alone force equal realized directional counts.
3. A complete finite enclosing record relation can uniquely fix a positive symmetric recurrence ratio relative to counted background reference recurrences (Theorem 2 and the twelve-position construction).
4. Identical native state counts and zero net orientation can coexist with different complete recurrence ratios. Static symmetry is not a unique clock law.
5. The local closure, net directed throughput, background count, and background increment are distinct R²D count types.

**Physical thesis proposed, not yet proved:** Symmetric enclosing background organization is the primitive organizing cause of actual turbine fluctuations, including their recurrence timing, while an asymmetric deformation of that same organization produces net directional cycling. The complete enclosing temporal compatibility that would make that causal thesis quantitatively unique has yet to be derived from independently specified primitive background counts.

**Not established:** $b_J=N_J^\Phi$; $P=\Phi$; $f_J^\Phi=k_BT/h$; identity between quantum spectral frequency and native structural closure rate; a common quantum–gravitational physical invariant; or a universal dimensional $c$.

## Conclusion

There is one turbine, realized within an enclosing organization that may be symmetric or asymmetrically biased. Symmetric compatibility is compatible with positive recurring closure without net orientation; asymmetric compatibility can direct that same recurring architecture into net cycle throughput. This supplies a positive count-level interpretation of what is observed as thermal fluctuation, without granting primitive causal ownership to an independently moving microscopic object.

The new mathematical result is not that symmetry alone generates a clock. It is that **the complete enclosing relation, when it fixes the incidence of whole closures relative to an independently specified background recurrence, uniquely determines the dimensionless symmetric recurrence ratio without a kinetic law**. That distinction is the indispensable foundation for the next question: which enclosing invariant remains readable after quantum and gravitational recursive replacement remove complementary parts of the thermal turbine's joint read?

## References

1. R²D Part I, *A Theory of Dimensionless Recursive Counting*, authoritative revision September 25, 2026. Especially definitions of native multiplicity, enclosing extension, closure, whole-closure recurrence, background, and the two realization postulates.
2. R²D Part II, thermodynamic mappings of chemical activity, ATP coupling, myosin recurrence, and the distinction between temperature, possibility, and realized background.
3. R²D Part III, *The Recursive Clock and the Horizons of Readability*, authoritative revision September 25, 2026. Especially Chapters 1–2 and 10.
4. R²D Addendum 105, *The Observational Inversion*.
5. R²D Addendum 112, *Sampled Multiplicity Before Thermal Fluctuations*.
6. R²D Addenda 120 and 122, enclosing-owned native identification and exact across-boundary compatibility.
7. R²D Addenda 124–125, possible complete recurrence configurations versus realized completed-closure statistics.
