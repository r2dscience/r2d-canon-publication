---
r2d_id: addendum-112
title: Addendum 112 — Sampled Multiplicity Before Thermal Fluctuations
subtitle: Temperature, Internal Energy, Radiation, and the Projected Subordinate Trajectory
source_type: addendum
authority: addendum
review_status: authoritative
indexable: true
primitive_authority: false
addendum: 112
unit: addendum
integrated_in_publication_canon: true
ask_r2d_status: pending_separate_corpus_update
promotion_date: '2026-10-24'
canon_revision: '2026-10-24'
source_file: Addendum-112-Sampled-Multiplicity-Before-Thermal-Fluctuations-Draft(1).md
source_sha256: 1f1e8cf06b7924caab31019107251feb730df9bb02361aa96467bc9f39e765f1
source_review_status: author_review_pending
source_format: author_supplied_markdown
current_text_source: author_supplied_markdown
promotion_basis: author_request_to_update_canon_2026-10-24
---

## Abstract

R²D distinguishes the multiplicity of an enclosing state from the records produced when its compatible realizations are sampled. Repeated records can differ. That fact does not turn the records into a continuously occupied subordinate trajectory, nor does it make temperature a force that drives such a trajectory. At the thermodynamic boundary, the allegedly hidden, temperature-driven process called a *thermal fluctuation* is not a real causal entity. It is a projection from sampled variation onto an unobserved subordinate history.

The conclusion does not discard the variation in experimental readings. It identifies what those readings count. A microstate is one formally compatible joint realization relative to a specified boundary. Its fiber and multiplicity are defined before any sample. Resolving a particular peer configuration changes the operative read boundary; comparing several resulting records does not restore a single uninterrupted microstate trajectory at the original enclosing boundary.

Temperature, internal energy, and radiative output are subsequent physical reads. R²D Part II treats internal energy as a state coordinate of the thermodynamic boundary and temperature as a calibration of an energetic count relation. Part III uses the blackbody spectrum to read thermal recurrence; Part IV describes radiation as a recurrent enclosing occurrence. None of these constructions assigns temperature primitive agency over hidden microstates or treats internal energy as a store of independently propertied subordinate objects. The exact thermodynamic and radiative equations may be retained without the projected causal story.

This addendum applies the general Markov audit of Addendum 107 to thermodynamics. It states precisely where a valid sampling or transition calculation becomes an epiphenomenological (EP) projection: sampled differences are promoted to persistent subordinate trajectories; a temperature coordinate is then promoted to the cause of those trajectories; and the constructed trajectories are promoted to the origin of the enclosing thermodynamic and radiative organization.

## 112.1. The Claim and the Boundary to Which It Applies

The claim is direct:

> **Thermal fluctuations are not real as temperature-driven trajectories of persistent subordinate microstates beneath an operative thermodynamic boundary. They are an EP projection of sampled multiplicity.**

The phrase *thermal fluctuation* has been used for several different things. A detector can register changing signals. Repeated preparations can yield different configurations. A physical boundary can undergo a readable state transition. Each of these statements identifies an occurrence or a record. None of them, by itself, identifies a hidden object that persists as a microstate of the same enclosing boundary while following a temperature-driven path.

R²D does not need to deny the records in order to reject that extra object. The distinction is between **real sampled variation** and the **projected subordinate trajectory** invented to cause the variation and, subsequently, the enclosing state itself.

This result concerns the boundary relative to which the configurations are called *microstates*. A transition that becomes readable at a subordinate boundary is a macrostate transition there. It is not simultaneously a directly readable microstate trajectory at the original enclosing boundary.

## 112.2. Possibility Precedes the Sample

Fix a thermodynamic count boundary $B$. Let $\mathfrak M_B$ be its domain of compatible joint peer realizations and let

$$
\pi_B:\mathfrak M_B\longrightarrow\mathcal M_B
$$

classify them into readable macrostates. For $i\in\mathcal M_B$, define the compatible fiber and native multiplicity:

$$
F_{B,i}=\pi_B^{-1}(i),
\qquad
W_{B,i}=|F_{B,i}|,
\qquad
S_{B,i}=\ln W_{B,i}.
$$

These are properties of the specified boundary classification. They are not the number of times state $i$ has been observed. An occurrence $\mu_B^{(r)}\in F_{B,i}$ is one realization from that already defined possibility domain; its index $r$ counts an occurrence or sample. It does not, without another premise, denote a physical clock time along the trajectory of one persisting subordinate object.

The ordering is therefore:

$$
\text{boundary and compatibility}
\longrightarrow
F_{B,i},W_{B,i}
\longrightarrow
\text{realized samples and records}.
$$

Sampling can change which realization is recorded and which boundary makes its details readable. Sampling does not create the fixed boundary's compatible fiber or its multiplicity. This is the distinction among possible count, occurrence count, and occupancy established in Part I and used in Addenda 104, 105, and 107.

## 112.3. A Sequence of Records Is Not a Subordinate Trajectory

Suppose repeated resolved observations produce records $y_1,y_2,\ldots$. After each observation, an analyst may classify its resolved configuration under the original thermodynamic description and find

$$
\pi_B(\mu_B^{(r)})=i
\qquad\text{for every observed }r,
$$

even though $y_r\ne y_{r+1}$ for some samples. The macrostate label has remained $i$; the records distinguish alternative members of its compatible fiber. At the moment the peer-resolved configuration is made the operative read, however, its peer identities belong to that resolving boundary. The full peer record and the original unresolved thermodynamic macrostate are not one unchanged operative state classification.

The inference from records to an enduring hidden path requires additional objects and rules:

1. an identity rule saying what remains *the same subordinate object* between records;
2. a transition rule connecting one possible record to the next;
3. a recurrence or physical clock assigning intervals to those connections; and
4. a reason to treat the resulting path as the primitive cause of the enclosing multiplicity.

Neither $F_{B,i}$ nor $W_{B,i}$ supplies these rules. A formal microstate transition $\mu\to\mu'$ is definable relative to $B$, as Part I explicitly states, but it is not individually readable **as a microstate transition from $B$**. Reading the peer transition changes the boundary at which it is a macrostate transition. Stitching records taken under such resolutions into one continuously readable subordinate trajectory is the added projection.

Thus:

$$
\boxed{
\text{difference between samples}
\;\not\Rightarrow\;
\text{persistent subordinate trajectory at }B.
}
$$

## 112.4. An Exact Finite Example

Consider ten distinguishable binary peers at a fixed ensemble boundary. Let macrostate $i$ classify configurations with five peers in state B and five in state A. Its native multiplicity is

$$
W_i=\binom{10}{5}=252.
$$

Two separate resolving observations might record different assignments of which five peers occupy B. Both records map back to $i$. The first observed assignment did not create the other 251 compatible possibilities; nor did the second record create the multiplicity $252$.

Even if an experimenter chooses an equal-weight resampling protocol, $q(x)=1/252$ for $x\in F_i$, that protocol does not select a unique time history. For example, the family of representation kernels

$$
K_{\varepsilon}(x,y)
=(1-\varepsilon)\mathbf 1_{y=x}+\varepsilon q(y),
\qquad 0<\varepsilon\le 1,
$$

has the same stationary weight $q$ for every $\varepsilon$, while assigning different next-record correlations. Indeed,

$$
\sum_{x\in F_i}q(x)K_{\varepsilon}(x,y)
=q(y).
$$

The equal-weight protocol is an explicit extra assumption; it is not a consequence of $W_i=252$. The kernels are mathematical descriptions of possible sampling rules, not competing primitive causes. Changing $\varepsilon$ changes the proposed connection among records without changing the compatible fiber, its multiplicity, or the one-record frequencies under stationarity. The count does not supply a hidden trajectory; neither does a histogram of resolved configurations.

This is the thermal analogue of Addendum 107's Markov construction. A correct transition calculation can be made once states and a sampling rule have been specified. Its correctness does not confer causal priority over the boundary that defined those states.

## 112.5. What the Word “Thermal” Adds to the Projection

Calling the imagined path a *fluctuation* identifies changing hidden states as if their trajectory were an operative physical object at $B$. Calling it *thermal* commonly assigns temperature the job of driving that imagined motion. Those are two separate inferential steps; neither follows from sampled variation.

In the thermodynamic mapping of Part II, $U_B$ is a boundary-defined energetic state coordinate. For the equilibrium count representation under the stated controls,

$$
\frac{1}{k_{\mathrm B}T_B}
=\left(\frac{\partial\ln W_B}{\partial U_B}\right)_{V,N,X}.
$$

This equation gives $T_B$ the role of a physical scale relating an energetic distinction to a logarithmic count distinction. It does not make $T_B$ a primitive mover of subordinate microstates. Likewise, writing $U_B(T_B)$ or a heat capacity

$$
C_V=\left(\frac{\partial U_B}{\partial T_B}\right)_V
$$

relates two physical coordinates under stated conditions. It does not establish a causal chain $T_B\Rightarrow$ hidden trajectory $\Rightarrow U_B$. When a hotter external radiation field is imposed on an absorbing body, the resulting energy exchange is a physical process involving a newly specified source–body boundary. The measured exchange does not make the temperature coordinate the primitive cause of the body's count domain.

The conventional order of *reconstruction* often begins with a temperature or a radiative signal, assigns an internal energy, and explains it by postulated agitation among subordinate objects. R²D audits the reverse dependency: the boundary-defined compatible organization precedes these physical coordinates and the particular records used to infer them. The equations connecting the reads need not change when that causal assignment is corrected.

## 112.6. “Internal” Energy Is a Whole-Boundary Read

Part II locates internal energy at the thermodynamic boundary:

$$
U_B=U_B(\Sigma_B,V_B,N_{1,B},N_{2,B},\ldots).
$$

The adjective *internal* identifies this conventional state coordinate relative to exchanges through the selected system boundary. It does not confer independently persistent energetic properties on the subordinate configurations that count as its microstates. In particular,

$$
U_B\ne \text{a primitive sum of energies owned by the elements of }F_{B,i}.
$$

A useful decomposition of $U_B$ into thermal, chemical, binding, field, or other contributions is a physical representation under specified controls. It must not be read backward as proof that the represented subordinate protagonists generated the enclosing state or its compatible multiplicity. Part II also distinguishes total $U_B$ from the energetic calibration of directional asymmetry, $k_{\mathrm B}T_B A_B$; those are different quantities.

This distinction requires a correction to the language of Addendum 36. Its list of “thermal excitation,” “internal kinetic energy,” “radiation,” and related contributions is not a list of primitive properties carried by invisible constituents. Its mechanical construction of $E_0=Mc^2$ uses an existing rapidity geometry, a momentum read, inertial calibration, and the work–momentum relation. It does not produce $U_B$ or the equality $\Delta U_B=\Delta E_{0,B}$ from primitive multiplicity alone. Where a physical model establishes a change in the *whole boundary's* zero-momentum energy, the calibrated mass relation reads

$$
\Delta M_B=\frac{\Delta E_{0,B}}{c^2}.
$$

Calling a contribution “internal energy” does not, by itself, supply that identification. Neither the valid mass–energy calibration nor a useful decomposition licenses the hidden-trajectory story rejected here.

## 112.7. Radiation Is a Read of Recurrent Enclosing Occurrence

Part III describes a blackbody as a thermodynamic boundary whose occupancy can be read through emitted radiation. Its physical calibration uses $hf$ and $k_{\mathrm B}T$ to express the dimensionless relation

$$
\frac{hf}{k_{\mathrm B}T}.
$$

The count law of repeatable occupancy precedes this physical blackbody assignment. Observed radiance may be used to infer a temperature, but an inference from radiance to $T$ is a measurement procedure. It does not turn the measured radiation into the primitive cause of the body's compatible-count architecture or its $U_B$ read.

Part IV gives a separate structural account of radiation. If $\mathcal C_n$ is a completed compatible local closure and $\chi_{n+1}^{\mathrm{EM}}$ is an enclosing electromagnetic occurrence, the causal relation is

$$
\chi_{n+1}^{\mathrm{EM}}\Rightarrow\mathcal C_n,
$$

while completed closure is **reclassified** at the receiving boundary:

$$
\mathcal C_n\overset{\mathrm{carry}}{\longmapsto}\chi_{n+1}^{\mathrm{EM}}.
$$

The second arrow is not a bottom-up causal push. Radiation requires recurrence of the enclosing occurrence. Physical radiative energy transfer, where measured, is an energetic read within the specified electromagnetic process; formal recursive carry is a change of count meaning, not the upward shipment of an internal-energy packet.

Consequently, the productive R²D inversion is **not** to substitute a new primitive arrow “$U_B$ pushes radiation outward” for the old arrow “radiation or temperature pushes energy inward.” The enclosing compatibility defines the realizable relation; $U_B$, $T_B$, and recurrent radiation are distinct physical reads at their stated boundaries. The phrase “internal energy becomes radiation” names the relation between such reads during emission, not a substance leaping over the count boundary.

## 112.8. The Complete EP Projection

The observable and formal sequence is:

$$
\text{specified compatibility}
\longrightarrow
\text{possible realizations}
\longrightarrow
\text{realized samples}
\longrightarrow
\text{readable records}.
$$

Temperature, internal energy, and radiation enter through subsequent domain-specific physical calibrations of the organized relation. The projected causal story reverses this sequence in three steps:

1. Differences between records are assigned to a single persistent, hidden subordinate trajectory.
2. The temperature inferred from the organized thermal or radiative state is assigned agency over that trajectory.
3. The constructed trajectory is said to create the internal energy, radiation, or encompassing multiplicity that made the records classifiable.

The failure begins at the first step. Neither a compatible fiber nor a sequence of resolved samples establishes a hidden trajectory at the operative thermodynamic boundary. The second step assigns causality to a physical calibration. The third asks an already classified subordinate representation to generate the boundary that classified it.

This is the same dependency error proved generally in Addendum 107, now expressed in the physical language of thermodynamics.

## 112.9. What This Result Establishes

The proof obligations are different and should remain visible:

| Claim | Status and basis |
| --- | --- |
| The boundary defines $F_{B,i}$ and $W_{B,i}$ before any sample. | Formal result from the R²D definitions. |
| Differences among resolved records do not by themselves define a persistent subordinate trajectory at $B$. | Formal underdetermination, reinforced by the finite sampling example. |
| A microstate transition relative to $B$ is not directly readable as such from $B$. | Boundary-relative readability result of Part I. |
| Temperature-driven hidden microstate trajectories are not an R²D causal entity. | Consequence of applying those definitions to the stated thermal-fluctuation story. |
| $U_B$ and $T_B$ represent a physical thermodynamic state; blackbody radiation supplies a physical recurrence read. | Conditional physical mappings developed in Parts II and III. |
| $\Delta M_B=\Delta E_{0,B}/c^2$ for a calibrated whole-boundary rest-energy change. | Conditional mechanical/relativistic physical relation used in Addendum 36, not a primitive count identity. |

There may be a measured variance, radiative intensity, or heat-capacity curve to explain. R²D does not erase those observations. It rejects the inferential step that converts their sampled variation into independently causal, thermally driven subordinate trajectories. A successful stochastic model remains a calculation over specified states and sampling rules; its success does not make the projected trajectory the source of the count landscape.

## 112.10. Result

**Thermal fluctuations are not real in the causal sense attributed to them by the microscopic projection.** A thermodynamic boundary has a compatible multiplicity landscape. Sampling produces records that can differ. Their differences do not constitute a temperature-driven path of persisting microstates beneath that same boundary. Temperature is a physical calibration of a count–energy relation; internal energy is a whole-boundary state coordinate; radiation is a recurrent physical read of enclosing occurrence. None has to be generated by imaginary subordinate agitation.

The essential order is:

$$
\boxed{
\text{enclosing compatibility}
\longrightarrow
\text{sampleable multiplicity}
\longrightarrow
\text{realized records and physical reads}.
}
$$

Possibilities pull. Probabilities do not push. Temperature does not animate hidden microstate trajectories. Radiation does not create the enclosing count relation from which its thermal read is constructed.

## Internal sources

- R²D Part I, §§3.2.1–3.2.2 and the coin construction: possible count, occurrence, boundary-relative microstate transitions, and sampling.
- R²D Part II, §§2.3–2.6 and 7.5–7.10: thermal conversion scale, $U_B$ as a boundary state coordinate, and temperature as a count–energy slope.
- R²D Part III, Chapter 4: blackbody occupancy and the $hf/(k_{\mathrm B}T)$ physical read.
- R²D Part IV, Chapter 6: radiative occurrence, causal enclosure, recursive carry, and the distinction between physical energy transport and formal count transport.
- R²D Addendum 36, §§35–37: the conditional physical mass–energy construction and language requiring clarification.
- R²D Addendum 105, §12: repeated subordinate observation and the apparent fluctuation of sampled realizations.
- R²D Addendum 107, §§107.2–107.7: possible count, normalized probability, realized occurrence, and the Markov EP projection.
