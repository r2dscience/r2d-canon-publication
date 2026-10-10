---
r2d_id: addendum-007
title: Addendum 7 — Frequency-Selected Readability Occurs Before Cross-Scale Spectra
subtitle: Mechanical Oscillation, Moving Readability Horizons, and Recursive Deprojection in Muscle
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 7
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 1089
pdf_page_end: 1114
math_representation: LaTeX for normalized equations; source-faithful Unicode retained in noncritical schematic/prose expressions
equation_status: source_pdf_visual_reconstruction_and_standalone_render_qa
semantic_sync: 2026-09-25-no-substantive-universality-amendment-required
primitive_authority: false
review_status: author_reviewed
machine_revision: 2026-10-09-equation-reconstruction-v1
qa_status: standalone_render_pass_full_book_pending
promotion_date: null
equation_audit_scope: displayed_equations_and_schematics_visually_checked_against_pdf; clipped_source_text_flagged
---

# Addendum 7 — Frequency-Selected Readability Occurs Before Cross-Scale Spectra

## Mechanical Oscillation, Moving Readability Horizons, and Recursive Deprojection in Muscle


## Abstract


Addendum 6 established that biological function is realized through a hierarchy of closure-complete
subordinate dynamics.

A native subordinate trajectory is physically defined at its own boundary,

$$\Gamma_n,$$

completes there,

$$\Gamma_n\longrightarrow\mathcal C_n,$$

and is recursively replaced before the enclosing boundary acquires its own native state and recurrence:

$$\Gamma_n\longrightarrow\mathcal C_n\overset{\kappa_n}{\longmapsto}B_{n+1}.$$

This raises an experimental question.

If subordinate trajectories have been replaced at the enclosing boundary, how can their dynamics
nevertheless be detected experimentally from the enclosing biological system?

Muscle provides the answer.

When muscle is mechanically oscillated, its mechanical response depends on the frequency of the imposed
perturbation. Increasing the perturbation frequency progressively changes which dynamics contribute
directly to the measured response.

The physical specimen remains the same muscle.

The boundary being dynamically read does not.

This requires a distinction between the system boundary

$$B_{\mathrm{sys}}$$

and the read boundary

<!-- source_pdf_page: 1090 -->

$$B_{\mathrm{read}}(f_p),$$

where $f_p$ is the perturbation frequency.

Let a subordinate boundary $B_n$ possess a native closure frequency

$$f_n^{\mathrm{cl}},$$

and let the imposed perturbation have period

$$T_p=\frac{1}{f_p}.$$

The approximate number of native subordinate closures available during one perturbation cycle is

$$N_C^{(n\mid p)}=\frac{T_p}{T_n^{\mathrm{cl}}}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

If

$$N_C^{(n\mid p)}\gg1,$$

the subordinate boundary closes many times within one probe cycle. Its native trajectory is closure-
complete relative to the measurement, and the experiment primarily reads its recursively replaced
enclosing consequence.

When

$$N_C^{(n\mid p)}\sim1,$$

the perturbation approaches the native recurrence timescale of that boundary. The subordinate dynamics
can no longer disappear completely into the enclosing read before the measurement changes. Their
recurrence becomes dynamically visible.

When

$$N_C^{(n\mid p)}\ll1,$$

that boundary cannot complete even one native recurrence during the imposed cycle. Relative to the
perturbation, it becomes effectively constrained, and the measured response becomes increasingly
dependent on faster subordinate realizations.

Thus increasing perturbation frequency moves a readability horizon through the recursive hierarchy.

The system boundary remains muscle:

$B_{\mathrm{sys}}=B_{\mathrm{muscle}}$.

<!-- source_pdf_page: 1091 -->

But the dynamically selected read boundary changes:

$B_{\mathrm{read}}=B_{\mathrm{read}}(f_p)$.

This resolves an apparent tension in recursive replacement.

A subordinate trajectory that has been replaced is not a hidden coordinate of the enclosing state. Yet an
experiment performed on the enclosing physical system can still couple directly to that subordinate
boundary if the probe operates on the appropriate timescale.

Replacement is therefore not erasure.

It is boundary-relative statehood.

Changing the clock of the experiment changes which native recurrence is resolved.

The central statement is:

> **Probe frequency does not merely change the rate at which an enclosing system is observed.**

Hence:

> **Frequency-selected readability occurs before cross-scale spectra.**

## 1. Addendum 6 Leaves an Experimental Problem


Addendum 6 established:

> native subordinate trajectory → closure → recursive replacement → new enclosing state.

A microsecond protein trajectory does not persist as a millisecond switch trajectory.

A millisecond switch trajectory does not persist as the trajectory of muscle-scale function.

An infrared recurrence does not become a hidden version of the slower protein trajectory.

Each recurrence belongs to the boundary at which it is distinguishable.

Yet biological experiments routinely detect dynamics across several timescales from the same physical
specimen.

Mechanical spectroscopy of muscle makes this especially clear.

<!-- source_pdf_page: 1092 -->

## 2. Muscle Can Be Perturbed Without Changing the Physical Specimen

Consider an intact muscle as the experimental system.

The system boundary is

$B_{\mathrm{sys}}=B_{\mathrm{muscle}}$.

A small oscillatory length perturbation may be written

$$\delta L(t)=\Re\!\left[\delta L_0e^{i\omega_pt}\right].$$

The corresponding force response is

$$\delta F(t)=\Re\!\left[\delta F_0e^{i(\omega_pt+\phi)}\right].$$

A complex mechanical response can then be defined schematically as

$$K^*(\omega_p)=\frac{\delta F(\omega_p)}{\delta L(\omega_p)}.$$

The muscle has not changed into a different object because $\omega_p$ changed.

Yet

$$K^*(\omega_p)$$

changes with frequency.

The perturbation frequency therefore changes what part of the nested dynamics is directly consequential to
the read.

## 3. The System Boundary and the Read Boundary Are Different Concepts


The system boundary identifies the physical system being perturbed:

$$B_{\mathrm{sys}}.$$

The read boundary identifies the native recurrence most directly resolved by the experimental timescale:

<!-- source_pdf_page: 1093 -->

$$B_{\mathrm{read}}.$$

In general,

$$B_{\mathrm{read}}\ne B_{\mathrm{sys}}.$$

The muscle may remain the enclosing physical specimen while the perturbation interrogates dynamics
belonging to a subordinate molecular or protein boundary.

Thus:

> **where the experiment is applied is not the same as which boundary is read.**

## 4. Probe Frequency Supplies an Experimental Clock


Let the imposed perturbation frequency be

$$f_p.$$

Its period is

$$T_p=\frac{1}{f_p}.$$

Let a candidate subordinate boundary $B_n$ possess a native closure frequency

$$f_n^{\mathrm{cl}}$$

and native closure period

$$T_n^{\mathrm{cl}}=\frac{1}{f_n^{\mathrm{cl}}}.$$

The perturbation therefore defines a physical interval against which the subordinate recurrence can be
compared.

## 5. Define the Number of Subordinate Closures Per Probe Cycle


The approximate number of native closures available during one perturbation cycle is

$$N_C^{(n\mid p)}=\frac{T_p}{T_n^{\mathrm{cl}}}.$$

Equivalently,

<!-- source_pdf_page: 1094 -->

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

This dimensionless ratio determines whether the native trajectory at $B_n$ is already closure-complete relative
to the experimental read.

## 6. Regime I — Many Subordinate Closures Per Probe Cycle


If

$$N_C^{(n\mid p)}\gg 1,$$

then

$$f_n^{\mathrm{cl}}\gg f_p.$$

The subordinate boundary completes many native recurrences during one imposed cycle.

Its internal trajectory therefore repeatedly closes before the enclosing response is distinguished.

Relative to the probe:

$$\Gamma_n\longrightarrow\mathcal C_n\overset{\kappa_n}{\longmapsto}B_{n+1}$$

has already occurred many times.

The experiment therefore primarily reads the recursively replaced enclosing consequence.

## 7. Fast Subordinate Dynamics Then Appear as Already Realized Structure


When

$$N_C^{(n\mid p)}\gg 1,$$

the experiment does not need to resolve each subordinate recurrence individually.

Their completed realizations contribute to the enclosing response.

Thus:

> many subordinate closures → one slower enclosing read.

<!-- source_pdf_page: 1095 -->

This is why fast dynamics can appear as constitutive structure, compliance, stiffness, occupancy, or other
slower physical properties rather than as directly resolved trajectories.

## 8. Regime II — Probe and Native Recurrence Become Comparable


As the perturbation frequency increases,

$$f_p\uparrow,$$

the number of subordinate closures available during each probe cycle decreases:

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}\downarrow.$$

When

$$N_C^{(n\mid p)}\sim 1,$$

the perturbation operates on approximately the native closure timescale of $B_n$.

The subordinate boundary no longer completes many recurrences before the imposed state changes again.

Its native dynamics therefore become directly consequential to the measured response.

## 9. A Mechanical Dispersion Can Mark a Native Recurrence Scale


A change in the amplitude or phase of

$$K^*(\omega_p)$$

near some characteristic frequency indicates that the perturbation has entered a different dynamical
regime.

In R²D, such a dispersion is a candidate signature that

$$\omega_p\sim\omega_n^{\mathrm{cl}}.$$

This does not prove by itself that $B_n$ is a distinct recursive boundary.

Ordinary coupled systems also exhibit frequency-dependent response.

But where an independently identifiable state boundary exists, a characteristic mechanical dispersion
provides a direct way to interrogate its native recurrence.

<!-- source_pdf_page: 1096 -->

## 10. Regime III — The Candidate Boundary Cannot Close During the Probe


If

$$N_C^{(n\mid p)}\ll 1,$$

then

$$f_p\gg f_n^{\mathrm{cl}}.$$

The perturbation changes faster than the candidate boundary can complete its native recurrence.

Relative to the probe, that boundary becomes dynamically constrained.

Its slower state cannot fully reorganize within one imposed cycle.

The measured response must therefore be carried increasingly by faster subordinate realizations capable of
responding within the shortened interval.

Thus increasing probe frequency can expose progressively deeper recursive structure.

## 11. The Readability Horizon Moves With Probe Frequency


The hierarchy can be written schematically as

$$B_1\longrightarrow B_2\longrightarrow B_3\longrightarrow\cdots\longrightarrow B_{\mathrm{muscle}},$$

with native closure frequencies approximately ordered as

$$f_1^{\mathrm{cl}}>f_2^{\mathrm{cl}}>f_3^{\mathrm{cl}}>\cdots.$$

At low $f_p$, many subordinate boundaries satisfy

$$f_n^{\mathrm{cl}}\gg f_p.$$

Their trajectories are closure-complete relative to the probe.

As $f_p$ rises, the condition

$$f_p\sim f_n^{\mathrm{cl}}$$

is encountered successively at deeper and faster boundaries.

<!-- source_pdf_page: 1097 -->

The experiment therefore moves through the recursive hierarchy without changing the physical specimen.

## 12. Define the Frequency-Selected Read Boundary


Let

$$B_{\mathrm{read}}(f_p)$$

denote the boundary whose native recurrence becomes directly consequential at perturbation frequency
$f_p$.

Then:

$B_{\mathrm{read}}=B_{\mathrm{read}}(f_p)$.

This does not imply a universal one-to-one mapping between frequency and boundary.

Several processes can occur at similar frequencies.

One boundary can support several recurrent modes.

The assignment must be established physically.

But the perturbation clock determines which recurrence timescales are experimentally accessible.

## 13. The Physical System Boundary Can Remain Fixed


Throughout the experiment,

$B_{\mathrm{sys}}=B_{\mathrm{muscle}}$.

Yet:

$$B_{\mathrm{read}}(f_{p,1})\ne B_{\mathrm{read}}(f_{p,2})$$

can hold.

Thus the experiment does not need to dissect the muscle physically into separate systems in order to
interrogate different recursive depths.

Frequency alone can change the dynamical depth of the read.

<!-- source_pdf_page: 1098 -->

## 14. This Does Not Reverse Recursive Replacement

A higher-frequency experiment does not reconstruct a subordinate trajectory as though replacement had
never occurred.

It couples the measurement directly to a boundary at which that trajectory is still natively defined.

That distinction is essential.

$$B_{n+1},$$

$$\Gamma_n$$

is not an enclosing state coordinate.

$$B_n.$$

Thus:

> replacement at $B_{n+1}$

and

> experimental readability of $B_n$

are entirely compatible.

## 15. Replacement Is Not Erasure


Recursive replacement means:

$$\Gamma_n\notin\text{state coordinates of }B_{n+1}.$$

It does not mean:

> $\Gamma_n$ cannot be physically interrogated at $B_n$.

A sufficiently rapid probe can couple to the native recurrence before it disappears into the slower enclosing
read.

Thus:

> subordinate statehood can remain experimentally accessible

even though

<!-- source_pdf_page: 1099 -->

> subordinate statehood has been replaced at the enclosing boundary.

## 16. Mechanical Spectroscopy Is Therefore a Form of Recursive Deprojection

At slow perturbation frequency, the experiment reads the already-replaced enclosing response.

At higher frequency, it becomes sensitive to faster subordinate realization.

The frequency sweep therefore partially reverses the observational compression without reversing the
physical replacement.

It moves the experimental read downward through the hierarchy.

This can be written:

$$f_p\uparrow\quad\Longrightarrow\quad\text{deeper recursive dynamics become readable}.$$

This is recursive deprojection.

## 17. Deprojection Is Not Inversion

The distinction matters.

The many-to-one replacement map

$$\kappa_n$$

remains non-invertible.

A measurement of $B_{n+1}$ still cannot uniquely reconstruct

$$\Gamma_n.$$

Instead, the experiment changes its physical coupling so that it reads $B_n$ more directly.

Thus:

$$\text{recursive deprojection}\ne\kappa_n^{-1}.$$

The measurement does not mathematically invert replacement.

It shifts the boundary at which physical distinctions are read.

<!-- source_pdf_page: 1100 -->

## 18. Muscle Makes the Shift Directly Observable

At muscle-scale timescales, one can measure slow mechanical function.

At higher mechanical frequencies, faster kinetic and structural processes become consequential to the
response.

Schematically:

> s → ms → μs

as the experimental clock is progressively shortened.

The exact assignment of each response regime to a recursive boundary must be established
experimentally.

The important result is structural:

increasing frequency changes which nested dynamics remain unresolved during the measurement.

## 19. A Low-Frequency Muscle Read Does Not Contain Every Faster Trajectory

At low perturbation frequency, faster dynamics can complete many closures during each imposed cycle.

The muscle-scale response therefore need not encode their detailed trajectories.

The experiment reads the consequence of those completed closures.

Thus:

$$K^*(\omega_{\mathrm{low}})$$

is not a complete record of every faster molecular event.

It is an enclosing physical response produced after repeated subordinate replacement.

## 20. Higher Frequency Changes the Meaning of the Response


As the drive frequency approaches a subordinate native recurrence,

<!-- source_pdf_page: 1101 -->

$$f_p\sim f_n^{\mathrm{cl}},$$

that recurrence becomes dynamically unresolved within the enclosing cycle.

The measured amplitude and phase now depend on the inability of $B_n$ to complete its usual closure before
the perturbation changes again.

The response therefore contains information about the native dynamics of $B_n$.

## 21. Phase Lag Is a Natural Read of Incomplete Closure


If the imposed length and measured force are phase shifted by

$$\phi(\omega_p),$$

that phase lag reports a temporal relation between the imposed occurrence and the system's realization.

R²D does not require every phase lag to define a separate boundary.

But frequency-dependent phase provides a natural physical read of the transition between:

> closure complete before read

and

> closure incomplete during read.

Thus mechanical phase can help identify candidate closure scales.

## 22. Increasing Frequency Does Not Simply Reveal Smaller Objects

The hierarchy is not a hierarchy of spatial magnification.

A faster probe does not necessarily read a physically smaller object.

Recursive scale is defined by count boundary and recurrence, not metric size.

Therefore:

$$f_p\uparrow$$

should be interpreted as access to faster native recurrence,

<!-- source_pdf_page: 1102 -->

not necessarily:

> smaller spatial object.

This distinction will matter when the same reasoning is extended toward quantum and gravitational
readability.

## 23. Frequency Is Therefore a Boundary-Selection Coordinate

A perturbation frequency is not itself the boundary.

But it determines which native recurrence can close relative to the read.

Thus frequency acts experimentally as a selector of recursive depth:

$$f_p\longrightarrow B_{\mathrm{read}}(f_p).$$

This is the basis of frequency-selected readability.

## 24. Cross-Scale Spectra Can Now Be Defined More Carefully

A cross-scale spectrum is not necessarily the spectrum of one persistent oscillator possessing many
frequencies.

It can instead contain physical responses from several recursively related boundaries selected by the
measurement frequency.

Thus:

> **one frequency axis does not imply one state boundary.**

Different regions of the response can correspond to different native recurrences within the same enclosing
physical system.

## 25. Boundary Ownership Still Requires More Than Frequency Separation

Different characteristic frequencies alone are insufficient to prove recursive replacement.

Ordinary mechanical systems also possess multiple modes.

<!-- source_pdf_page: 1103 -->

A distinct recursive boundary requires an independently identifiable state classification.

Evidence for boundary ownership includes:

- Native distinguishable states;
- many-to-one subordinate realization;
- closure relative to an enclosing classification;
- and an enclosing recurrence that does not require subordinate path identity.

Thus:

> **different frequency does not imply a different recursive boundary.**

Frequency selects candidate dynamics.

State ownership establishes the boundary.

## 26. The Myosin Switch Provides the Independent State Classification

For muscle, the $M_1/M_2$ switch supplies exactly such an independently identified boundary.

Addendum 4 established the spectroscopically resolved occupancy:

$$[M_1],\qquad [M_2].$$

Addendum 5 established replacement into the ensemble.

Thus a mechanical response near the native recurrence scale of the switch can be interpreted against a
state boundary that is independently known.

This makes muscle more informative than a frequency spectrum alone.

## 27. The Same Logic Extends to Faster Protein Dynamics

The myosin switch is itself realized through faster protein dynamics.

If those faster recurrences possess independently identifiable state structure, then increasing perturbation
frequency can move the read boundary downward again.

Schematically:

> $B_{\mathrm{muscle}}$
>
> ⇓ $f_p\uparrow$
>
<!-- source_pdf_page: 1104 -->
>
> $B_{\mathrm{ensemble}}$
>
> ⇓
>
> $B_{\mathrm{switch}}$
>
> ⇓
>
> $B_{\mu\mathrm{s}}$

where the arrows denote increasing access to faster native recurrence, not literal spatial descent.

## 28. Eventually Mechanical Perturbation Is No Longer the Appropriate Probe

At sufficiently fast recurrence scales, direct mechanical oscillation may no longer be the practical
measurement coordinate.

Other physical probes become necessary.

Spectroscopic probes extend the same logic into faster recurrence domains.

Thus the experimental sequence can continue:

> mechanical frequency response → faster molecular dynamics → IR spectroscopy → …

The instrument changes.

The boundary-selection principle does not.

## 29. Mechanical and Spectroscopic Probes Are Therefore Continuous in Principle


A mechanical oscillation supplies an imposed recurrence

$$f_p.$$

A spectroscopic probe supplies another physical clock with a much faster recurrence.

Both compare an imposed or detected physical recurrence with native dynamics of the system.

Thus both can be interpreted through:

<!-- source_pdf_page: 1105 -->

> probe recurrence ↔ native boundary recurrence.

This provides the bridge from mechanical frequency response to cross-scale spectroscopy.

## 30. The Probe Does Not Create the Native Boundary

Changing $f_p$ does not create a new biological scale.

The candidate boundaries already possess their own state classifications and native recurrences.

The probe changes only which of them becomes dynamically readable.

Thus:

> probe frequency selects readability

rather than

> probe frequency creates statehood.

## 31. Readability Is Therefore Relational

Whether a subordinate recurrence is closure-complete relative to an experiment depends on both:

$$f_n^{\mathrm{cl}}$$

and

$$f_p.$$

The relevant relation is

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

Thus readability is not a property of the system alone.

It is a relation between system recurrence and probe recurrence.

<!-- source_pdf_page: 1106 -->

## 32. This Is a Local Experimental Readability Horizon


The condition

$$N_C^{(n\mid p)}\sim 1$$

defines a local experimental transition between:

> subordinate recurrence already closure-complete

and

> subordinate recurrence dynamically resolved.

This is an experimental readability horizon.

It is not yet the quantum or gravitational readability horizon of Addendum 3.

But it provides an observable biological analogue of the same structural idea.

## 33. Biology Allows the Readability Horizon to Be Moved

This is experimentally unusual.

By changing $f_p$, one can shift the local read horizon while leaving the enclosing physical specimen intact.

Thus biology allows:

$$B_{\mathrm{read}}(f_{p,1})\longrightarrow B_{\mathrm{read}}(f_{p,2})\longrightarrow B_{\mathrm{read}}(f_{p,3})$$

to be explored within one organized system.

Recursive depth becomes experimentally tunable.

## 34. This Strengthens the Distinction Between Averaging and Replacement

If faster processes merely averaged into a slow variable, increasing measurement frequency would simply
improve temporal resolution of one persistent trajectory.

Recursive replacement predicts something stronger.

<!-- source_pdf_page: 1107 -->

As the probe crosses successive native closure scales, the relevant state classification can change.

Thus:

> higher temporal resolution

can reveal

> different boundary-owned statehood,

not merely a more detailed version of one slow trajectory.

## 35. Principle — System Boundary and Read Boundary Are Distinct


The physical object being perturbed defines

$$B_{\mathrm{sys}}.$$

The recurrence made dynamically readable defines

$$B_{\mathrm{read}}.$$

In general:

$$B_{\mathrm{sys}}\ne B_{\mathrm{read}}.$$

## 36. Principle — Probe Frequency Selects Recursive Depth


For a candidate boundary $B_n$,

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

Changing $f_p$ changes whether the native recurrence is closure-complete relative to the measurement.

Thus:

$$f_p\longrightarrow B_{\mathrm{read}}(f_p).$$

<!-- source_pdf_page: 1108 -->

## 37. Principle — Many Closures Produce an Enclosing Read


If

$$N_C^{(n\mid p)}\gg1,$$

the subordinate trajectory closes repeatedly before the probe distinguishes the enclosing response.

Its effect is therefore read through recursive replacement.

## 38. Principle — Native Recurrence Becomes Readable Near the Probe Timescale


If

$$N_C^{(n\mid p)}\sim1,$$

the probe and native recurrence become comparable.

The subordinate dynamics become directly consequential to the measured amplitude and phase.

## 39. Principle — Faster Probes Can Expose Deeper Subordinate Realization


If

$$N_C^{(n\mid p)}\ll1,$$

the candidate boundary cannot fully close during the imposed cycle.

Its slower reorganization becomes constrained, and faster subordinate dynamics increasingly determine
the response.

Thus:

$$f_p\uparrow\quad\Longrightarrow\quad\text{deeper recursive realization can become readable}.$$

<!-- source_pdf_page: 1109 -->

## 40. Principle — Recursive Deprojection Does Not Invert Replacement

A high-frequency probe does not reconstruct a unique subordinate history from the enclosing state.

Instead, it couples directly to a faster boundary.

Therefore:

> **deprojection is not inverse replacement.**

## 41. Principle — One Spectrum Can Contain Several Boundary-Owned Reads

A common frequency axis can display responses associated with several recursively related boundaries.

Thus:

> **one spectrum does not imply one native recurrence.**

Boundary ownership must be established from state structure, not frequency alone.

## 42. Logical Status


**Established in Addendum 4**

The myosin switch possesses experimentally resolvable states whose occupancy asymmetry is organized by

$A_M=P_M-R_M$.

**Established in Addendum 5**

Individual switch identities and trajectories are replaced by ensemble occupancy and multiplicity.

**Established in Addendum 6**

Subordinate biological trajectories are closure-complete relative to enclosing boundaries and do not persist
as enclosing trajectories:

$$\Gamma_n\longrightarrow\mathcal C_n\overset{\kappa_n}{\longmapsto}B_{n+1}.$$

<!-- source_pdf_page: 1110 -->

**New Distinction**

The physical experimental system boundary,

$$B_{\mathrm{sys}},$$

need not equal the dynamically read boundary,

$$B_{\mathrm{read}}.$$

**New Probe Relation**

For a perturbation frequency $f_p$,

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

estimates the number of native subordinate closures available during one perturbation cycle.

**New Readability Regimes**

$$N_C^{(n\mid p)}\gg1$$

corresponds to repeated subordinate closure before the enclosing read;

$$N_C^{(n\mid p)}\sim1$$

corresponds to direct sensitivity to the candidate native recurrence;

and

$$N_C^{(n\mid p)}\ll1$$

corresponds to a candidate boundary unable to complete its recurrence within the probe interval,
increasing sensitivity to faster subordinate realization.

**New Experimental Interpretation**

Changing perturbation frequency can shift the recursive depth of the read without changing the enclosing
physical specimen.

**Not Yet Claimed**

This addendum does not yet establish:

- A universal one-to-one mapping between perturbation frequency and recursive boundary;

<!-- source_pdf_page: 1111 -->

- that every mechanical dispersion identifies a new state boundary;
- that every spectroscopic line equals a native closure frequency;
- the complete cross-scale spectral replacement law;
- or the quantum and gravitational readability horizons from mechanical frequency response alone.

Those require the next stages of the program.

## 43. The Frequency-Selected Read Architecture


The experiment begins with one physical system:

$B_{\mathrm{sys}}=B_{\mathrm{muscle}}$.

A probe recurrence is imposed:

$$f_p.$$

For each candidate subordinate boundary:

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

At low probe frequency:

$$N_C^{(n\mid p)}\gg 1$$

for many subordinate boundaries.

Their native dynamics close before the read:

> $\Gamma_n\longrightarrow\mathcal C_n$ → enclosing response.

Increasing $f_p$ reduces

$$N_C^{(n\mid p)}.$$

When

$$N_C^{(n\mid p)}\sim 1,$$

a candidate native recurrence enters the readable response.

Increasing frequency farther can move the experimental read toward faster subordinate boundaries.

Thus:

<!-- source_pdf_page: 1112 -->

$B_{\mathrm{read}}=B_{\mathrm{read}}(f_p)$.

The system remains muscle.

The recursive depth of the read changes.

## 44. Conclusion

Recursive replacement does not make subordinate physical dynamics experimentally inaccessible.

It changes the boundary on which those dynamics are state variables.

Addendum 6 established that a native subordinate trajectory closes before it is replaced into an enclosing
state:

$$\Gamma_n\longrightarrow\mathcal C_n\overset{\kappa_n}{\longmapsto}B_{n+1}.$$

The trajectory does not persist as an enclosing coordinate.

Yet muscle mechanics shows that the experimental read need not remain fixed at the enclosing functional
boundary.

A mechanical perturbation introduces its own physical clock.

For perturbation frequency $f_p$, the number of native closures available at candidate boundary $B_n$ during
one probe cycle is

$$N_C^{(n\mid p)}=\frac{f_n^{\mathrm{cl}}}{f_p}.$$

When this ratio is large, subordinate recurrence repeatedly closes before the measurement distinguishes
the response.

The experiment reads the already-replaced enclosing consequence.

As the probe frequency increases,

$$N_C^{(n\mid p)}$$

decreases.

When

$$N_C^{(n\mid p)}\sim 1,$$

<!-- source_pdf_page: 1113 -->

the perturbation approaches the native timescale of the candidate boundary.

Its dynamics become directly consequential to the measured amplitude and phase.

At still higher frequency, that boundary cannot fully reorganize within the imposed cycle, and increasingly
faster subordinate realizations can dominate the response.

Thus:

> increasing probe frequency → increasing recursive depth of the read.

The muscle itself has not changed boundaries.

It remains the physical system under study:

$B_{\mathrm{sys}}=B_{\mathrm{muscle}}$.

What changes is

$$B_{\mathrm{read}}(f_p).$$

This distinction resolves an apparent conflict between recursive replacement and multiscale spectroscopy.

A subordinate trajectory can be absent from the state coordinates of the enclosing boundary while
remaining physically measurable when the experiment couples directly to the subordinate boundary.

Replacement is not erasure.

Nor does high-frequency measurement invert replacement.

The experiment does not reconstruct a hidden molecular path from the muscle-scale state.

It changes the physical timescale of the read until the native subordinate dynamics themselves become
consequential.

Mechanical spectroscopy therefore provides a direct form of recursive deprojection.

By changing the perturbation clock while retaining the same biological specimen, one can move
experimentally from slow functional behavior toward progressively faster native recurrence.

At still faster scales, other physical probes take over.

Spectroscopy continues the same procedure.

The resulting frequency axis should therefore not automatically be interpreted as the spectrum of one
persistent object carrying one trajectory across all scales.

<!-- source_pdf_page: 1114 -->

It may instead contain physical reads from several recursively related boundaries.

The central result is:

> **Probe frequency selects which nested recurrence can close relative to the experimental read.**

[Editorial source note: the rest of this boxed sentence is clipped in the archived PDF after “At low…”. It requires author review.]

Hence:

> **Frequency-selected readability occurs before cross-scale spectra.**
