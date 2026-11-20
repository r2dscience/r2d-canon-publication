---
r2d_id: "addendum-130"
title: "Addendum 130 — Closure, Recorded Occurrence, and the Quantum Readability Horizon"
subtitle: "Local Return, Recursive Carry, and the Limits of Subordinate Reconstruction"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 130
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
---

# Addendum 130 — Closure, Recorded Occurrence, and the Quantum Readability Horizon

**Local Return, Recursive Carry, and the Limits of Subordinate Reconstruction**

**Status:** Author-approved for canon publication — November 20, 2026  

## Abstract

A physical system may return to its original readable state while an enclosing boundary distinguishes that an occurrence has been completed.

The cardiac pressure–volume loop provides a familiar example. Ventricular pressure and volume return to their initial coordinates after a cardiac cycle, yet blood has been transported and mechanical work has been performed. A turbine likewise returns to its original orientation after a complete revolution while an enclosing system may record the completed turn or receive transferred work.

Recursively Realized Distinguishability (R²D) formalizes this distinction through recursive carry. A completed local closure may be classified as an enclosing occurrence without preserving the local state identity or reversing the causal priority of the enclosing boundary.

Part I already establishes that recursive carry is generally many-to-one. Addendum 120 establishes the corresponding algebra of boundary-owned identity and replacement. The present addendum does not repeat those proofs. It develops their physical consequences and connects them to the quantum readability horizon.

At that horizon, recurrence remains readable through its permitted physical relations, while subordinate geometric distinguishability and unique realization histories are not jointly recoverable.

An individual-electron diffraction pattern is readable through accumulated detector occurrences without establishing a persistent microscopic trajectory. Similarly, the observed 360°/720° rotational interference relationship admits the spinorial representation reconstructed in Addendum 129 without establishing a persistent spinning object or a uniquely recoverable subordinate recurrence class.

The distinction also applies to statistical occupancy. Fermi–Dirac and Bose–Einstein laws describe admissible occupancy structures and their realized distributions. Their mathematical count labels do not independently establish persistent microscopic objects.

The general result is:

$$
\boxed{
\begin{gathered}
\text{Local return}\not\Rightarrow\text{enclosing return},\\[4pt]
\text{Enclosing record}\not\Rightarrow
\text{unique subordinate realization}.
\end{gathered}
}
$$

**A completed occurrence may remain distinguishable after local closure. Its enclosing record does not restore the subordinate identities lost through recursive replacement.**

---

## 1. Three different questions

The physical interpretation of a completed cycle requires distinguishing three questions.

**What has returned?**

A local boundary may classify the beginning and end of a completed cycle as the same state.

**What has been recorded?**

An enclosing boundary may distinguish the completion of that cycle through work, transport, changed occupancy, or another retained relation.

**What can be recovered?**

The enclosing record may or may not distinguish which subordinate realization completed the cycle.

These are not equivalent questions.

Let $B_n$ denote a local count boundary and $B_{n+1}$ an enclosing boundary.

A local completed closure can be represented as

$$
\mathcal C_{n,a}:i\rightarrow k\rightarrow i.
$$

Its local state classification has returned to $i$.

At the enclosing boundary, however, the completed closure may belong to a distinguishable occurrence class

$$
\chi_{n+1}.
$$

The return of $i$ does not require the enclosing occurrence classification to return.

R²D expresses this through recursive carry:

$$
\boxed{
\mathcal C_{n,a}
\overset{\kappa_n}{\mapsto}
\chi_{n+1}.
}
$$

This is a change in count classification, not the physical transport of one persistent object between scales.

The enclosing-first causal relation remains

$$
\boxed{
\chi_{n+1}\Longrightarrow\mathcal C_{n,a}.
}
$$

The enclosing occurrence determines the compatible subordinate closures through which it can be realized.

Recursive carry describes how a completed local closure is counted at the enclosing boundary. It does not imply that the subordinate closure created the enclosing organization that made it possible.

This is the distinction underlying the cardiac cycle and turbine examples.

## 2. The cardiac pressure–volume loop

Consider a ventricle operating through a periodic pressure–volume cycle.

Let $P(t)$ and $V(t)$ denote ventricular pressure and volume.

For the readable mechanical coordinates of a steady cycle,

$$
P(t+T)=P(t),
\qquad
V(t+T)=V(t).
$$

The pressure–volume state has returned.

Yet the loop can enclose a nonzero area:

$$
\boxed{
W_{\mathrm{cycle}}
=
\left|\oint P\,dV\right|>0.
}
$$

Under the conventional pressure–volume calibration, this area represents mechanical work per cycle.

During ejection, the ventricle also transfers blood into the circulation. In the standard idealized description,

$$
V_{\mathrm{stroke}}
=
V_{\mathrm{ED}}-V_{\mathrm{ES}}.
$$

The local pressure–volume coordinates return, but an enclosing circulation can distinguish the transported blood and transferred work.

This does not require the complete molecular state of the ventricle to return. Nor does it imply that every enclosing consequence persists permanently as a stored record.

The pressure–volume loop establishes something more precise:

**Local mechanical closure does not erase the enclosing consequences of its completed realization.**

The same observation motivated R²D's distinction between muscle-scale organization and subordinate molecular motor realizations.

The muscle boundary defines the admissible mechanical organization. Its molecular switches realize that organization through their compatible occurrence counts.

Observing molecular switching does not establish that the switches independently create the enclosing muscle state.

Similarly, observing the completed cardiac cycle does not establish that the ventricle independently creates the enclosing cardiovascular organization within which its work and blood transport have meaning.

The causal organization is enclosing-first, even though completed local occurrences remain physically consequential.

## 3. The turbine principle

The turbine gives a simpler example.

Let the readable shaft orientation be

$$
\phi\in S^1.
$$

After a complete revolution,

$$
\phi_{\mathrm{final}}
=
\phi_{\mathrm{initial}}
\pmod{2\pi}.
$$

The local orientation has returned.

Yet an enclosing revolution counter may register

$$
N_{\mathrm{final}}
=
N_{\mathrm{initial}}+1.
$$

Alternatively, an external mechanical load may receive work:

$$
W_{\mathrm{cycle}}
=
\oint\tau\,d\phi,
$$

where $\tau$ is shaft torque.

The original orientation has returned, but the enclosing physical relation need not have returned.

This is not a contradiction. Shaft orientation, revolution count, and transmitted work belong to different physical classifications.

The enclosing constraint determines the admitted direction and organization of turbine operation. The turbine realizes that relation through its completed local motion.

The turbine does not independently establish the pressure or mechanical organization that makes its directed operation possible.

Nor is its revolution count automatically a record of every subordinate mechanical event.

A completed revolution can remain readable without preserving the identities of the many subordinate realizations associated with that revolution.

This is recursive carry expressed in familiar mechanical terms.

## 4. The established mathematics of local closure and enclosing record

The formal results required here already exist in R²D.

Addendum 120 establishes the factorization condition for boundary-owned classifications.

Let $\Omega_J$ denote an enclosing domain of compatible joint presentations.

Define a local endpoint classification

$$
e:\Omega_J\rightarrow\mathcal S_n
$$

and an enclosing record classification

$$
r:\Omega_J\rightarrow\mathcal R_J.
$$

The record can be reconstructed from the local endpoint exactly when $r$ is constant on each fiber of $e$.

Equivalently,

$$
r=f\circ e
$$

for some $f$ on the admitted endpoint image if and only if

$$
e(\omega_1)=e(\omega_2)
\Longrightarrow
r(\omega_1)=r(\omega_2).
$$

Consequently, if

$$
e(\omega_1)=e(\omega_2)
$$

but

$$
r(\omega_1)\ne r(\omega_2),
$$

the local endpoint alone cannot determine the enclosing record.

The cardiac and turbine examples instantiate this existing factorization result.

A second result is already established in Part I.

Recursive carry is generally many-to-one:

$$
\kappa_n(c_1)=\kappa_n(c_2)=\chi
$$

for distinct compatible subordinate closure presentations $c_1$ and $c_2$.

Therefore, the enclosing occurrence $\chi$ need not uniquely identify the subordinate realization.

These are two logically distinct results.

The first establishes that a local endpoint may fail to determine an enclosing record.

The second establishes that an enclosing occurrence may fail to identify its subordinate realization.

Together they give

$$
\boxed{
\begin{aligned}
\text{Local closure}&\not\Rightarrow
\text{enclosing closure},\\
\text{Enclosing occurrence}&\not\Rightarrow
\text{unique subordinate history}.
\end{aligned}
}
$$

Neither result requires a new physical force, conserved microscopic identity, or bottom-up construction of enclosing statehood.

### Work, retention, and irreversible background

Part II provides an additional distinction.

A completed cyclic process may transfer work while its local state returns. An ideal reversible cycle can deliver work without irreversible background production.

Therefore,

$$
W_{\mathrm{out}}>0
$$

does not, by itself, require

$$
\delta_{\mathcal C}\Phi>0.
$$

Enclosing work, a retained record, and irreversible background are different count and physical readings.

A completed local cycle need not create a permanent record. Nor does recording an occurrence imply that its entire subordinate history has been preserved.

This distinction prevents the return of a local state from being mistaken either for the erasure of an occurrence or for proof of irreversibility.

## 5. The quantum readability horizon

The preceding examples concern physical systems for which adjacent-boundary relationships may be jointly measurable.

The pressure–volume cycle and blood transport can both be recorded.

A turbine's rotation and the resulting revolution count can both be observed.

The quantum readability horizon defines a different situation.

Part III establishes that recurrence can remain readable while subordinate distinguishability is no longer jointly accessible.

Schematically,

$$
\boxed{
\mathcal R(\rho)=1,
\qquad
\mathcal R(\lambda_{\mathrm{sub}})=0.
}
$$

The first relation permits a readable recurrence structure.

The second excludes the joint recovery of subordinate distinguishability needed to reconstruct a unique microscopic realization.

The distinction is not between a physically existing mechanism and insufficiently precise instruments.

It concerns what the receiving boundary admits as a physical distinction.

This requires separating three concepts.

**Readable quantum recurrence:** A frequency, ordering, or coherent recurrence relation that the receiving boundary can distinguish.

**Readable enclosing operation:** A controlled experimental operation, such as a calibrated rotation of an apparatus.

**Subordinate recurrence history:** An inferred sequence of microscopic realizations beneath the quantum readability horizon.

The first two can be experimentally meaningful without making the third independently recoverable.

A mathematical model may assign a recurrence label to its subordinate representation.

That label is not thereby established as a native, readable physical state.

At the quantum horizon, R²D therefore does not require us to identify which subordinate recurrence class physically produced an observed detector result.

The observation is real.

Its enclosing count relation is readable.

Its subordinate realization is not restored by constructing a mathematical account of what might have occurred beneath the receiving boundary.

## 6. Individual-electron diffraction

Consider an apparatus that registers individual electron detections.

The enclosing preparation and apparatus define an admissible detector distribution.

Each registered detection is a completed occurrence at the receiving detector boundary.

For detector classes $D_i$, let

$$
c_i
$$

denote the realized number of detections in class $i$.

The accumulated detector distribution is read through

$$
\widehat p_i
=
\frac{c_i}{\sum_jc_j}.
$$

The experimental pattern may be reproduced by a quantum calculation involving complex amplitudes.

But the directly recorded observations are detector occurrences and their distribution.

They do not identify a unique continuous trajectory belonging to one persistent microscopic electron.

Nor does the compatibility of multiple mathematical paths imply that every path was simultaneously occupied.

The diffraction pattern is an enclosing read.

Individual detections realize that read.

The mathematical particle description represents the observed relationship; its successful prediction does not establish an independently readable subordinate trajectory.

This illustrates the same distinction as the turbine, with one critical difference.

The turbine's local revolution may be directly measured.

The subordinate realization associated with an individual quantum detection is not reconstructed from its detector record.

The enclosing occurrence survives as a readable distinction without recovering the subordinate identity.

This is the quantum application of the replacement logic developed in Addenda 81, 101, 102, 104, and 105.

## 7. The spinorial 360°/720° observation

Addendum 129 reconstructs the spinorial rotational sign from the finite angular-momentum representation developed in Addendum 106.

Under the specified rotational representation,

$$
\boxed{
U(2\pi)=(-1)^L\mathbf1.
}
$$

For odd $L$,

$$
U(2\pi)=-\mathbf1,
\qquad
U(4\pi)=+\mathbf1.
$$

The mathematical sign becomes experimentally readable through coherent relative interference.

The enclosing experiment distinguishes a controlled rotational relation and its detector consequences.

But the result does not establish that one persistent microscopic spinor has physically completed two revolutions.

The controlled rotation of the apparatus is readable.

The relative interference relationship is readable.

A unique subordinate quantum recurrence history is not thereby readable.

The classical turbine analogy must therefore stop at the correct point.

A turbine can return to its original orientation while a separately readable revolution counter advances.

It does not follow that a quantum system possesses a physically recoverable hidden revolution counter whose parity produces the spinorial sign.

Such a claim would replace the observed quantum relation with an inaccessible subordinate mechanism.

The appropriate R²D ordering is

$$
\boxed{
\begin{gathered}
\text{Enclosing experimental compatibility}\\
\Downarrow\\
\text{Readable rotational interference}\\
\Downarrow\\
\text{Spinorial mathematical representation}.
\end{gathered}
}
$$

The spinor is an exact mathematical representation under the conditions established in Addendum 129.

It is not a physical explanation that supersedes the enclosing relation from which the observation was obtained.

At the quantum horizon, the task is to establish the observable count relationship and the validity of its mathematical representation—not to recover a uniquely identifiable physical spinor beneath the measurement boundary.

## 8. Statistical occupancy is not particle identity

The same interpretive distinction applies to Fermi–Dirac and Bose–Einstein statistics.

Part III establishes that the Fermi–Dirac form follows from an admitted binary occupancy domain:

$$
m\in\{0,1\}.
$$

With the appropriate occupancy asymmetry $A$,

$$
\boxed{
\bar m_F=\frac{1}{e^{-A}+1}.
}
$$

This form also applies to binary molecular-switch ensembles in muscle.

It does not require those switches to be fermionic particles.

The statistical structure follows from the admissible count relation before introducing a primitive particle interpretation.

For repeatable occupancy,

$$
m\in\{0,1,2,\ldots\},
$$

the corresponding Bose–Einstein form is

$$
\boxed{
\bar m_B=\frac{1}{e^{-A}-1},
\qquad A<0.
}
$$

The count label $m=2$ signifies an admitted occupancy classification.

It does not independently establish two persistent, individually identifiable bosonic objects occupying one physical state.

This does not dispute the success of conventional occupation-number mathematics. It identifies the difference between a mathematical count representation and the physical ontology inferred from it.

The same distinction applies to the $L$ formal binary distinctions in Addendum 129.

Their count-generated angular algebra does not establish $L$ persistent microscopic constituents.

Likewise, the observed two-cycle rotational relationship does not establish one persistent spinorial object.

**An occupancy count is not automatically a count of independent objects. A recurrence representation is not automatically a physical history.**

## 9. Conclusion — The physical meaning of a completed occurrence

The cardiac pressure–volume loop and turbine establish a general physical distinction.

A local state may return while an enclosing boundary distinguishes the completed occurrence.

Part I formalizes this relation through recursive carry. Part II distinguishes productive work from irreversible background. Addendum 120 establishes the classification conditions under which an enclosing record can or cannot be reconstructed from a subordinate read.

These results do not require new mathematical primitives.

They establish the physical meaning of boundary-relative closure.

At the quantum readability horizon, the same architecture has a further consequence.

The enclosing observation remains readable, but the subordinate realization cannot be recovered as a uniquely persistent physical object.

Individual-electron diffraction establishes a detector distribution without identifying a continuous particle trajectory.

Rotational interference establishes the 360°/720° relationship without identifying a persistent microscopic spinor or a uniquely readable subordinate recurrence class.

Fermi–Dirac and Bose–Einstein count laws likewise do not establish primitive particle identities simply because their mathematical representations use particle occupancy language.

The common R²D result is

$$
\boxed{
\begin{gathered}
\text{Local return does not erase enclosing occurrence.}\\[4pt]
\text{Enclosing occurrence does not restore subordinate identity.}
\end{gathered}
}
$$

A completed occurrence may be counted, retained, or made consequential at an enclosing boundary without preserving every distinction involved in its subordinate realization.

The quantum readability horizon places a physical limit on the inverse inference.

**What is observed must not be confused with the mathematical object used to explain it. A successful representation of an enclosing observation does not establish the represented subordinate object as its physical cause.**

This is the observational inversion that R²D rejects.

---

## Logical status and scope

This addendum introduces no new primitive axiom.

Its mathematical foundations are the established R²D results on recursive carry, replacement, classification factorization, and boundary-relative readability.

Its physical contribution is a cross-domain synthesis connecting local closure, enclosing consequences, and limits on subordinate reconstruction.

The cardiac and turbine examples demonstrate local return with measurable enclosing effects.

The quantum examples demonstrate the distinction between readable enclosing recurrence and unreadable subordinate realization.

The addendum does not claim that every completed cycle leaves a permanent record, that work necessarily implies irreversible background, or that the quantum horizon makes all recurrence unreadable.

Nor does it independently derive the spinorial rotation law, the full diffraction distribution, or the Bose–Einstein and Fermi–Dirac occupancy relations. Those results are established or reconstructed elsewhere in the R²D canon and its addenda.

The present result clarifies their common physical interpretation.

## Controlling R²D references

- Part I — *A Theory of Dimensionless Recursive Counting*: recursive carry, enclosing causal priority, and many-to-one replacement.
- Part II — reversible engines, work, and the distinction between productive output and irreversible background.
- Part III — *The Recursive Clock and the Horizons of Readability*: statistical occupancy and the quantum readability horizon.
- Addendum 4 — *Enclosing Organization Occurs Before Myosin Switch Realization*.
- Addendum 5 — *Ensemble Replacement Occurs Before Muscle-Scale Statehood*.
- Addendum 72 — *Closure Phase Occurs Before Complex Amplitude*.
- Addendum 81 — *Repeated Subordinate Closure Occurs Before Quantum Interference*.
- Addendum 83 — *Detector-Boundary Realization Occurs Before Quantum Measurement*.
- Addendum 86 — *The Status of a Physical Mapping*.
- Addendum 100 — *The Empty Vessel: Recursive Replacement, Observation, and Irreversibility*.
- Addendum 101 — *The Enclosing Relation Before Quantum Representation*.
- Addendum 102 — *Particles Are Imagined*.
- Addendum 104 — *The Count Relation Survives Before State Identity*.
- Addendum 105 — *The Observational Inversion*.
- Addendum 106 — *Angular Momentum and Nuclear Spectroscopy as Boundary-Relative Count Projections*.
- Addendum 112 — *Sampled Multiplicity Before Thermal Fluctuations*.
- Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*.
- Addendum 129 — *Spinorial Sign Reversal as Boundary-Relative Closure* (candidate).