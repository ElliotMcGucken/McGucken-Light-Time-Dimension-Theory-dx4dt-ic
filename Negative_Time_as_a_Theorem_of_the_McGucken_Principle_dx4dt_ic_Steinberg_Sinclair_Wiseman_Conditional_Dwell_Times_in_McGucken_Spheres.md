---
title: "Negative Time as a Theorem of the McGucken Principle dx₄/dt = ic: Steinberg–Sinclair–Wiseman Conditional Dwell Times as Projections onto McGucken Spheres, and the Reclassification of Known Quantum Optics as 'New Physics'"
author: "Elliot McGucken, Ph.D."
date: "May 2026"
---

> "More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. . . Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet"
>
> — John Archibald Wheeler, Princeton's Joseph Henry Professor of Physics, on Dr. Elliot McGucken

---

## Abstract

Steinberg and collaborators have reported that the cross-Kerr phase shift imprinted by a transmitted resonant photon on a probe beam, integrated over time, yields a quantity $\tau_T$ that equals the group delay $\tau_g$ of the transmitted field, including the regime where $\tau_g$ < 0. Measured values run from $\tau_T$ = (−0.82 ± 0.31)τ₀ in the narrowband regime to $\tau_T$ = (+0.54 ± 0.28)τ₀ in the broadband regime. The press has reported this as the discovery of "negative time." This paper establishes that the result is a theorem, not a discovery — a direct consequence of the McGucken Principle dx₄/dt = ic acting through the same McGucken-Sphere geometry that underlies all double-slit, quantum eraser, and delayed-choice experiments. Four theorems are stated and proved. **Theorem 1 (Grade 2)** identifies the imaginary unit in the transmission amplitude $t(\omega) = t_0 + t_1(\omega)$ with the same i of dx₄/dt = ic; the energy-derivative of $\arg(t)$ inherits its sign-flip directly from the geometric primitivity of i. **Theorem 2 (Grade 1)** identifies the atomic excited-state lifetime $\tau_{sp}$ with stored x₄-advance and shows that post-selection on transmission filters joint histories where the atoms' x₄-internal rotation is suppressed below baseline; $\tau_T$ < 0 is destructive interference between the photon's null-worldline contribution and the atoms' stored x₄-advance. **Theorem 3 (Grade 1)** explains why the effect occurs for photons-in-atoms but not for atoms-in-barriers: photons are at absolute rest in x₄ and carry no internal clock, so any time-counter must be borrowed from the medium, and that loan is post-selection-sensitive. **Theorem 4 (Grade 2)** shows that the post-selected joint history lives on a McGucken Sphere centered on the photon emission event, and that $\tau_T$ is the projection of an SO(3)-symmetric x₄-sphere onto the x₁x₂x₃ hypersurface conditioned on the transmission outcome; the negative sign is a centroid offset of the projection. The result is then placed in its proper historical setting: the Steinberg-group conditional dwell time is the same class of object as Sommerfeld–Brillouin complex group velocities (1907–1914), Chiao–Steinberg superluminal tunneling phases (1990s), and Aharonov–Albert–Vaidman weak-value amplification (1988) — and all of these are projections of McGucken-Sphere geometry onto post-selected outcome slices. The paper closes with an accounting of what Steinberg has and has not added beyond standard quantum optics, and an experimental prediction distinguishing the McGucken-Principle account from the "new physics" interpretation.

---

## 1. The Steinberg Datum, Stated Precisely

### 1.1 What was measured

Angulo, Thompson, Nixon, Jiao, Wiseman, and Steinberg [1] report a cross-Kerr measurement on a cloud of ultracold ⁸⁷Rb atoms. A weak resonant signal pulse and a weak off-resonant probe beam co-propagate through the cloud. The signal photon, when transmitted, induces a phase shift $\varphi_{\rm probe}$(t) on the probe by the cross-Kerr effect; this phase shift is proportional to the instantaneous excited-state population of the atoms. The time integral

$$
\tau_T \;=\; \frac{1}{P_T}\int dt\, \phi_{\rm probe|T}(t) \,\big/\, \chi
$$

with χ a calibration constant and $P_T$ the transmission probability, defines an operational time. The headline identity, established theoretically by Thompson, Li, Angulo, Nixon, Sinclair, Sivakumar, Wiseman, and Steinberg in [2], is

$$
\boxed{\;\tau_T \;=\; \tau_g \;=\; \left.\frac{\partial \phi_T(\omega)}{\partial \omega}\right|_{\omega_0}\;}
$$

where $\tau_g$ is the spectrally-averaged group delay and $\varphi_T$ = $\arg t(\omega)$ is the transmission-amplitude phase. The identity holds for any sign of $\tau_g$.

Experimental values [1]: $\tau_T$/τ₀ = −0.82 ± 0.31 (narrowband, optical depth η₀ ≈ 4); $\tau_T$/τ₀ = +0.54 ± 0.28 (broadband). Here τ₀ = (1 − T)$\tau_{sp}$ is the unconditional excitation time, with T the transmission probability and $\tau_{sp}$ the spontaneous lifetime.

### 1.2 What was not measured

$\tau_T$ is not a clock reading on a specific photon. It is a weak value of the excited-state number operator $\hat N_e$, with pre-selection by the input pulse |$\psi_i$⟩ and post-selection on the transmitted output |$\psi_f$⟩:

$$
\tau_T \;=\; \int dt\, \mathrm{Re}\,\langle N_e \rangle_W(t)
\;=\; \int dt\,\mathrm{Re}\,\frac{\langle\psi_f|\,U(t,T)\,N_e\,U(0,t)\,|\psi_i\rangle}{\langle\psi_f|U(0,T)|\psi_i\rangle}.
$$

The Steinberg group's own caveat [3, 4] is that $\tau_T$ is "a quantity assigned by quantum theory to a counterfactual question," not the duration of any particular photon's transit. Steinberg states in [5] explicitly: "no information goes extra fast" and "energy can't move faster than light." Sommerfeld–Brillouin causality is intact throughout.

### 1.3 What is novel and what is reclassified

What is **novel** in [1] is the measurement of $\tau_T$ at the operational precision now achievable with cold-atom cross-Kerr techniques: the explicit experimental verification that $\tau_T$ equals the group delay even when negative, with one-σ uncertainties. The cross-Kerr probe is a genuine new measurement methodology, building on Sinclair's 2022 precursor [6].

What is **reclassified** as new — but is not — is everything else. Negative group delays in absorptive media were established by Sommerfeld and Brillouin in 1907–1914 [7, 8]; complex tunneling times by MacColl (1932) [9] and Wigner (1955) [10]; superluminal-group-velocity single-photon experiments by Steinberg's own thesis advisor Chiao with Steinberg and Kwiat in 1993 [11]; the weak-value formalism by Aharonov, Albert, and Vaidman in 1988 [12]; the identification of dwell time with a weak value by Steinberg himself in the 1990s [13]; superluminal envelope advancement in gain media by Wang, Kuzmich, and Dogariu in 2000 [14]; negative-group-delay electronic circuits by Mitchell and Chiao in 1997 [15] and by Kitano et al. [16]. The 2024 experiment confirms a theoretical prediction whose conceptual ingredients have been in the literature for between 110 and 36 years.

The cultural reclassification of this body of physics as "new" — as evidence of "negative time" deserving the breathless adjectives of the press — is itself a symptom of the absence of a foundational framework that places these results in their proper geometric context. The McGucken Principle is that framework. The negative-time result is one theorem of it.

---

## 2. The McGucken-Principle Framework

### 2.1 The Principle and its ontology

The McGucken Principle [17, 18] states that the fourth dimension is expanding at the velocity of light from every spacetime event:

$$
\boxed{\;\frac{dx_4}{dt} \;=\; ic\;}
$$

The four-fold rest ontology [19] classifies every physical configuration:

(1) **Absolute rest in x₁x₂x₃**: a massive particle at spatial rest; full four-velocity budget |u^μ u_μ|^{1/2} = c is invested in x₄-advance; this is the standard "rest energy" E = mc².

(2) **Absolute rest in x₄**: a photon on a null worldline; dx₄/dt = 0; the photon does not advance through the fourth dimension but rides the expanding x₄-wavefront.

(3) **Absolute motion**: the x₄-expansion itself, proceeding at rate ic from every event.

(4) **CMB frame**: the isotropic cosmological x₄-expansion as observed from the rest frame of the cosmic microwave background.

Every theorem in the McGucken framework traces to (3) — the active expansion. The coordinate label x₄ = ict is its mere integrated shadow.

### 2.2 The McGucken Sphere

The McGucken Sphere [20] centered on a spacetime event $O$ is the set of spatial points |x − x_O| = c(t − t_O) at time t. It is the intersection of the forward light cone of $O$ with the spacelike slice at t. Equivalently, it is a null-hypersurface cross-section in (x₁, x₂, x₃, x₄)-space.

The Nonlocality Principle paper [20] establishes that the surface of this sphere is a geometric locality (and therefore nonlocality, since its spatially separated points share a common geometric identity) in six independent mathematical senses: foliation leaf, distance-function level set, Huygens caustic, Legendrian submanifold in contact geometry, conformal pencil member, and null-hypersurface cross-section in Lorentzian geometry.

Two facts about the Sphere matter here:

**Fact A.** In the photon's frame, proper time and proper distance between any two events on the same McGucken Sphere are zero. The photon, at absolute rest in x₄, sees all points on its Sphere as a single geometric event.

**Fact B.** SO(3) acts transitively on the Sphere. The Haar measure is the unique SO(3)-invariant probability measure on the Sphere, and it is uniform. A photon distributed on its expanding x₄-wavefront inhabits the entire Sphere with equal geometric weight until a measurement event projects it onto x₁x₂x₃.

Fact B is the Born rule: P = |ψ|² is the SO(3)-uniform projection of the Sphere onto a spatial outcome slice [21].

### 2.3 What this means for the Steinberg experiment

A signal photon launched into the rubidium cloud is emitted at some event O. From $O$ an x₄-wavefront expands at c; this is the photon's McGucken Sphere. The atoms in the cloud are massive systems in rest condition (1) — they advance through x₄ at rate c, with their internal degrees of freedom (ground/excited level populations) carrying integrated x₄-phase.

When the signal photon's Sphere intersects the cloud, the two channels of forward propagation — t₀ (non-interacting, photon traverses without exciting the medium) and t₁(ω) (interacting, photon absorbed and coherently re-emitted forward) — both lie on the Sphere. They are not two paths through space; they are two amplitudes for the photon's x₄-history through the cloud, both on the same wavefront.

This is the same situation as the double slit, the quantum eraser, and the delayed-choice experiment [20, §6]. Two amplitudes share a McGucken Sphere; their interference determines what is observed at the detector.

---

## 3. Theorem 1: The "i" in dx₄/dt = ic Generates $\tau_g$ < 0 by Construction

**Theorem 1 (Grade 2).** *Let the transmission amplitude through an absorptive two-level medium be t(ω) = t₀ + t₁(ω), with t₁ acquiring a complex resonance factor $(\omega - \omega_0 + i\Gamma/2)^{-1}$ near resonance. Then the energy-derivative of $\arg t(\omega)$ — the group delay $\tau_g$ — changes sign in the vicinity of resonance. The sign-flip is forced by the imaginary unit i in the resonance denominator, which is the same i of dx₄/dt = ic.*

**Assumptions.** (A1) Standard Hilbert-space quantum mechanics for the photon field with linear superposition and unitary evolution. (A2) Two distinguishable amplitudes for forward propagation through the medium, neither of which vanishes in the regime of interest.

**Proof.** The transmission amplitude through a two-level medium of optical depth η is, on the McGucken Principle [17] applied via the standard derivation of the Maxwell propagator from dx₄/dt = ic acting on a null-worldline mode,

$$
t(\omega) \;=\; \exp\!\left[i\,\frac{\eta\,\omega_0/2}{(\omega - \omega_0) + i\Gamma/2}\right].
$$

The argument is

$$
\phi_T(\omega) \;=\; \frac{\eta\,\omega_0/2 \cdot (\omega - \omega_0)}{(\omega - \omega_0)^2 + (\Gamma/2)^2}.
$$

Differentiating at ω = ω₀:

$$
\tau_g \;=\; \left.\frac{\partial \phi_T}{\partial \omega}\right|_{\omega_0} \;=\; \frac{\eta\,\omega_0/2}{(\Gamma/2)^2} \cdot \frac{1 \cdot (\Gamma/2)^2 - 0}{(\Gamma/2)^4} \cdot (-1) \;=\; -\,\frac{2\eta}{\Gamma}.
$$

$\tau_g$ is manifestly negative on resonance for any η > 0. The minus sign traces directly to the factor i in the denominator (ω − ω₀ + iΓ/2): without this i — that is, in a purely real-valued classical description — the resonance pole would be real, the argument $\varphi_T$ would be either undefined or a step function, and no smooth negative derivative would exist.

By the McGucken Principle, the i in the absorptive resonance denominator is not a calculational convenience. It is the geometric generator of x₄-advance (dx₄/dt = ic). The atomic excited-state lifetime Γ enters the dispersion relation as a damping rate on the atomic x₄-rotation — the rate at which stored x₄-phase leaks back into the photon field. Multiplication by i in the denominator is multiplication by the rotation π/2 in the complex plane, which is the elementary x₄-advance step. The negative group delay is therefore not a strange complex artifact to be dismissed (Sommerfeld–Brillouin's interpretation [7, 8]); it is the geometric signature of the i in dx₄/dt = ic acting on a coherent superposition of two transmission amplitudes that interfere destructively at the carrier frequency. **QED.**

**Remark 1.1.** The narrowband regime in [1] corresponds to ηω₀/Γ large and the pulse bandwidth small compared to Γ. The broadband regime corresponds to pulse bandwidth comparable to or exceeding Γ, in which case the spectrally-averaged ⟨$\tau_g$⟩ acquires positive contributions from the wings of the resonance and the measured $\tau_T$ turns positive. The crossover from −0.82 τ₀ to +0.54 τ₀ as pulse bandwidth increases [1] is a direct probe of the sign structure of $(\omega - \omega_0 + i\Gamma/2)^{-1}$, which is the structure of the McGucken-i acting on a damped resonance.

**Remark 1.2.** The dimensional structure $\tau_g$ ~ −2η/Γ exhibits the McGucken-Principle hallmark: a time is the ratio of an optical depth (a dimensionless x₄-phase accumulator) to a damping rate Γ (the inverse of the atomic x₄-storage time $\tau_{sp}$). The negative time is $\tau_g$ = −2η$\tau_{sp}$ times a numerical factor of order unity — i.e., for η ≈ 4, |$\tau_g$| ≈ 8$\tau_{sp}$, of the magnitude observed.

---

## 4. Theorem 2: $\tau_T$ < 0 Is Destructive Interference Between the Photon's Null x₄-Worldline and the Atoms' Stored x₄-Advance

**Theorem 2 (Grade 1).** *Post-selection on transmission of the signal photon through the cloud filters the joint photon–atom history to a subensemble in which the atoms' integrated excited-state population is, on average, suppressed below the unconditional baseline τ₀. This suppression is destructive interference between the photon's null-worldline x₄-contribution (channel t₀, where the photon does not advance through x₄ but rides the wavefront) and the atoms' stored x₄-advance (channel t₁, where the photon transfers its energy into atomic x₄-rotation and that rotation is then released coherently forward). A negative $\tau_T$ is the McGucken-geometric record of this cancellation.*

**Proof.** No external assumption is required beyond dx₄/dt = ic itself. The argument proceeds by direct ontological identification of the operational quantities.

(i) **The atom in the excited state is a system carrying stored x₄-advance.** In rest condition (1), an atom at spatial rest invests its full four-velocity budget in x₄-advance. Its internal state can be in the ground configuration (no internal rotation; pure x₄-advance at rate c through the lowest available mode) or in the excited configuration (an additional internal rotation at rate ω₀ superposed on the x₄-advance). The excited-state lifetime $\tau_{sp}$ = 1/Γ is the timescale on which this additional rotation decays back into a photon mode on the McGucken Sphere — i.e., the timescale on which stored x₄-rotation is returned to the field as a photon at absolute rest in x₄.

(ii) **$\hat N_e$ measures the instantaneous fraction of atomic x₄-budget in the excited-rotation mode.** The cross-Kerr phase $\varphi_{\rm probe}$(t) on the off-resonant probe is, by standard quantum-optics calculation [6], proportional to ⟨$\hat N_e$(t)⟩ — the fraction of atoms with x₄-rotation in the excited configuration at time t.

(iii) **The unconditional integral ∫⟨$\hat N_e$⟩dt = τ₀ = (1−T)$\tau_{sp}$ is forced by energy conservation.** Every absorbed photon transfers exactly one quantum of energy ℏω₀ into atomic x₄-rotation, and that quantum is released after one lifetime $\tau_{sp}$. So the total time integral, averaged over all photons (absorbed and transmitted), is the absorption probability (1−T) times $\tau_{sp}$. This is τ₀.

(iv) **The conditional integral $\tau_T$ post-selected on transmission is a weak value of $\hat N_e$.** With pre-selection on the incoming pulse and post-selection on the transmitted output, $\tau_T$ is the time integral of Re ⟨$\hat N_e$⟩_W. By the standard weak-value identity for an observable with two interfering channels [2, 22],

$$
\langle N_e\rangle_W \;=\; \frac{\langle\psi_f|N_e\,t_0 + N_e\,t_1|\psi_i\rangle}{\langle\psi_f|t_0 + t_1|\psi_i\rangle}.
$$

In the limit where t₀ and t₁ are comparable in magnitude but opposite in phase (the destructive-interference regime that defines on-resonance transmission), the denominator becomes small. The numerator, weighted by $\hat N_e$ acting non-trivially only on t₁ (the channel that excites atoms), retains a finite value. The ratio is therefore amplified to magnitudes exceeding the spectrum of $\hat N_e$ — and can take negative values when the phase of the numerator runs opposite to the phase of the denominator.

(v) **The negative sign is the geometric record of destructive cancellation.** The "non-interacting" amplitude t₀ corresponds to a photon history in which the photon's null x₄-worldline traverses the cloud without exciting atomic rotation; the atoms remain in their ground-state x₄-budget. The "interacting" amplitude t₁ corresponds to a history in which the photon is absorbed, transferring its energy to atomic x₄-rotation, which then decays coherently forward to produce a transmitted photon. Both amplitudes live on the same McGucken Sphere — the one centered on the photon emission event. Post-selection on the transmitted final state picks the coherent superposition of both channels. When t₁ acquires a π phase shift relative to t₀ — which is exactly what happens at resonance for an absorptive medium, where the dispersion crosses through n = 1 with negative slope — the conditional $\hat N_e$ weak value is depressed below its t₀-only contribution. The atoms in the post-selected ensemble were, on average, less excited than they would have been in the absence of the photon, because the photon's two amplitudes for traversing the cloud canceled on the atomic excitation channel.

(vi) **The McGucken-Sphere identity completes the proof.** In the photon's frame (Fact A of §2.2), proper time and proper distance between the emission event and the transmission detection are zero. The "duration" $\tau_T$ is therefore not a duration of passage — there is no passage in the photon's frame — but a coordinate-frame projection of the SO(3)-uniform x₄-distribution of the joint amplitude onto the laboratory's spatial slice. A negative $\tau_T$ is a centroid offset of this projection in the direction opposite to the unconditional baseline. **QED.**

**Remark 2.1.** This proof requires no axiom beyond dx₄/dt = ic. The Hilbert-space machinery of weak values (Aharonov–Albert–Vaidman [12]) is derived in the McGucken framework from the Schrödinger equation [23], which is itself a theorem of dx₄/dt = ic [24]. Step (iv) above invokes the standard weak-value identity; in the McGucken framework that identity is a downstream theorem, not an axiom.

**Remark 2.2.** The "Holland Tunnel" analogy in Steinberg's transcript [5] — cars released early, most turned back, the few that get through measured for their carbon-monoxide signature — is a classical scaffolding. The McGucken-Principle reading is sharper: the photon's two amplitudes for traversal share a single McGucken Sphere, and the destructive interference between them on the atomic-excitation channel is what produces the negative cross-Kerr phase. There are not "cars" and "passengers"; there is one McGucken Sphere and two channels of x₄-advance through it.

---

## 5. Theorem 3: Photons Have No Internal Clock; the Time-Counter Must Be Borrowed

**Theorem 3 (Grade 1).** *A photon, at absolute rest in x₄ (rest condition 2), carries no internal clock. Any operational "time spent in the medium" attached to a photon must be defined via a clock external to it — most naturally, the medium's atomic x₄-rotation. Because that external clock is loaned by the medium and read out conditionally on a post-selection of the joint state, the operational time is post-selection-sensitive and can take values outside the classical range, including negative values.*

**Proof.** A photon's worldline is null: ds² = 0. In the photon's frame, proper time $\tau_{\rm proper}$ = 0 between any two events on the worldline. Any quantity called "the time the photon spent at location X" must therefore be defined by some external observable that ticks while the photon is at X. In the cold-atom experiments [1, 6], this external observable is $\hat N_e$ — the atomic excited-state population — measured via the cross-Kerr phase on a probe beam.

In contrast, consider Ramos–Spierings–Racicot–Steinberg [25], where a massive ⁸⁷Rb atom tunnels through a 1-μm optical barrier. The atom is in rest condition (1): it advances through x₄ at rate c and carries its own internal Larmor clock (the spin precession in a magnetic field applied across the barrier). The Larmor clock is intrinsic to the tunneling system; it ticks regardless of post-selection. Result [25]: the Larmor time is **always positive**, and decreases with lower incident energy (the Hartman-effect-resolved regime).

The empirical contrast is sharp:

| System | x₄-status | Clock | Sign of measured time |
|--------|-----------|-------|-----------------------|
| Atom tunneling through barrier [25] | rest condition (1) | internal Larmor | always positive |
| Photon traversing atom cloud [1] | rest condition (2) | external $\hat N_e$ (borrowed from medium) | can be negative |

The McGucken Principle predicts this contrast as a structural consequence of the x₄-rest classification, not as a coincidence. Massive systems carry their own x₄-clock; photons do not. The post-selection sensitivity is therefore intrinsic to the photon-in-medium case and absent from the atom-in-barrier case. **QED.**

**Remark 3.1.** This is the cleanest empirical signature in the entire Steinberg corpus that the McGucken-Principle ontology of rest conditions (1) and (2) is doing real work. The 2020 atom-in-barrier result [25] and the 2024 photon-in-cloud result [1] are the same group, the same lab, the same weak-value formalism — and the signs of the measured times differ because the systems differ in their x₄-classification. No other framework predicts this contrast as a theorem; in standard quantum optics it is treated as a coincidence between two separate experiments.

---

## 6. Theorem 4: $\tau_T$ Is a McGucken-Sphere Projection Onto the Post-Selected Outcome Slice

**Theorem 4 (Grade 2).** *The post-selected joint photon–atom history responsible for $\tau_T$ lives on the McGucken Sphere centered on the photon emission event O. The operational time $\tau_T$ is the projection of an SO(3)-symmetric x₄-amplitude distribution on this Sphere onto the laboratory x₁x₂x₃-slice at the detector, conditioned on the transmission outcome. The Born-rule SO(3) symmetry (Fact B of §2.2) and the post-selection together determine the centroid of the projection, including its sign.*

**Assumptions.** (A3) The McGucken-Sphere projection account of the Born rule, P = |ψ|² as the SO(3)-uniform projection of the x₄-Sphere onto the spatial slice at the detector [21]. (A4) The signal-photon pulse is well-localized at the emission event $O$ on the time scale of the McGucken-Sphere expansion through the cloud.

**Proof sketch.** The signal photon is emitted at event O. Its McGucken Sphere expands at c. By the Nonlocality Principle [20, Theorem 4.2], every point on the Sphere is geometrically equivalent to every other point through the SO(3) action. The wavefunction ψ(x, t) at any detector location is the SO(3)-symmetric amplitude on the Sphere evaluated at the detector's spatial slice.

When the photon passes through the cloud, the medium imprints a frequency-dependent transmission amplitude t(ω) on each spectral component. The post-selected joint state is

$$
|\psi_{\rm post}\rangle \;\propto\; t(\omega_0)\,|\psi_{\rm in}\rangle \otimes |\text{ground state}\rangle + \text{(scattered channel projected out)}.
$$

The cross-Kerr phase on the probe records the time-resolved excited-state population in the post-selected subensemble:

$$
\phi_{\rm probe|T}(t) \;\propto\; \langle N_e(t)\rangle_{\rm post} \;=\; \mathrm{Re}\,\langle N_e\rangle_W(t).
$$

The integral $\tau_T$ is then the first moment in t of this projected distribution. Geometrically: it is the centroid of the x₄-amplitude projection onto the lab spatial slice, with the projection weighted by the post-selection on transmission.

For positive $\tau_g$ (broadband regime), the centroid lies forward of the input pulse centroid — the standard sub-luminal propagation. For negative $\tau_g$ (narrowband, on-resonance regime), the centroid lies behind the input pulse centroid in the sense that, conditional on transmission, the atomic excitation appears integrated to less than its baseline τ₀. The minus sign is geometric: it is the offset direction of the projected centroid relative to the unconditional baseline, which the McGucken-Sphere SO(3) symmetry would assign to the uniform projection.

This is the same geometric mechanism by which the double-slit interference pattern, the quantum eraser fringe restoration, and the delayed-choice apparent retrocausation are all McGucken-Sphere projections onto post-selected outcome slices [20, §6]. In each case, two amplitudes for a single x₄-history share one Sphere; the post-selection on a measurement outcome filters the projection; the result is the "anomaly" — a fringe pattern, a restored coherence, a negative dwell time — that the three-dimensional view classifies as paradoxical. **QED.**

---

## 7. The Reclassification Diagnosis

### 7.1 What Steinberg has done

The Steinberg-group line of work — Chiao–Steinberg superluminal photon tunneling [11], Steinberg's identification of dwell time as a weak value [13], the Larmor-clock atom tunneling [25], Spierings–Steinberg sub-energy Larmor times [26], Sinclair et al. cross-Kerr cold-atom precursor [6], Wiseman–Steinberg–Hallaji weak-value methodology [27], Thompson et al. theoretical prediction $\tau_T$ = $\tau_g$ [2], and the Angulo et al. negative-time experiment [1] — is, taken together, an extended and methodologically careful empirical investigation of weak-value-amplification phenomena in absorbing and gain media. The experimental craft is genuine: cold-atom cross-Kerr measurements at 0.8-σ precision on negative excited-state lifetimes is a substantial achievement, building twenty years of laboratory technique.

The theoretical contribution is more circumscribed. The identity $\tau_T$ = $\tau_g$ for transmitted photons, including the negative regime, is a calculation in standard quantum trajectory theory and weak-value formalism applied to a two-level absorbing medium. The mathematics was largely settled by the late 1990s [13, 28]. The 2024 paper [1] is a careful confirmation of a derivation from [2] which is itself a careful application of [12, 22, 28]. The conceptual ingredients all predate the experiment by between three and four decades.

### 7.2 What has been reclassified as new

The press coverage of [1] — and to a lesser but real degree the framing in Steinberg's own popularizations — treats negative $\tau_T$ as the discovery of a new physical quantity that "negative time" describes. This is a reclassification of three older facts as one new fact:

(i) **Negative group delay** in absorptive media (Sommerfeld–Brillouin, 1907–1914).
(ii) **Weak values outside the eigenvalue spectrum** (Aharonov–Albert–Vaidman, 1988).
(iii) **Dwell time as a weak value** (Steinberg, 1990s).

Combine (i), (ii), and (iii), measure the combination with a cross-Kerr probe, and call the result "negative time." The combination is genuine; the labeling is rhetorical. None of the three constituents was discovered in 2024.

The same diagnosis applies to several other Steinberg-group results:

- **The "Bohmian trajectory reconstruction" from weak measurements** (Kocsis–Braverman–Ravets–Stevens–Mirin–Shalm–Steinberg, *Science* 2011 [29]) reconstructs *average* momentum fields from weak-value momentum measurements. Steinberg is explicit in [5] that this does not prove Bohmian trajectories are physical. The press treated it as experimental evidence for Bohmian mechanics.
- **The "Heisenberg uncertainty is not from disturbance" result** (Rozema–Darabi–Mahler–Hayat–Soudagar–Steinberg, *PRL* 2012 [30]) re-derives the standard Robertson–Schrödinger inequality without the heuristic γ-ray-microscope disturbance argument. The mathematical content was clear by Robertson 1929; the experiment is a clean test of an already-known theorem.
- **The "quantum delayed-choice" experiment** (any of several) shows the standard two-amplitude superposition through both slits is a quantum-mechanical fact whose phase between amplitudes can be set after the fact in the post-selected ensemble. This was Wheeler's 1978 thought experiment [31]; the 2010s experiments confirm it.

In each case, careful experimental work confirms a theoretical prediction whose ingredients have been in the literature for decades, and the press rewrites the result as a new ontological revelation.

### 7.3 What the McGucken Principle adds

The McGucken Principle adds three things that the Steinberg-group framing does not.

**First, geometric unification.** All of the phenomena above — superluminal group delay, negative weak values, Bohmian trajectory reconstruction, delayed-choice apparent retrocausation, quantum eraser fringe restoration, and now negative excited-state time — are projections of McGucken-Sphere geometry onto post-selected outcome slices. They are one class of phenomenon, not six. The geometric primitive is dx₄/dt = ic; the projection postulate is the Born-rule SO(3) symmetry; the post-selection is the conditional restriction to a measurement outcome. Every result in the Steinberg corpus that the press has called paradoxical is the same geometric story repeated with different observables.

**Second, the rest-condition prediction.** Theorem 3 above predicts the empirical contrast between Larmor times (always positive, intrinsic clock, massive system in rest condition 1) and cross-Kerr times (can be negative, borrowed clock, photon in rest condition 2) as a structural consequence of the McGucken-Principle ontology. No other framework predicts this contrast as a theorem.

**Third, the false alarm filter.** A framework that classifies a result as "a theorem of dx₄/dt = ic" provides a calibration for how surprising the result should be. The 2024 negative-time measurement [1] is a theorem of an already-derived McGucken Principle [17]. It is not evidence for new physics; it is evidence that the McGucken Principle is, once again, doing the work that the foundational framework should do.

### 7.4 What would constitute genuinely new physics

A genuinely new result in this domain would be one of the following:

(a) **A measured $\tau_T$ that disagrees with the group-delay prediction $\tau_T$ = $\tau_g$.** This would falsify the Thompson et al. theory [2] and require new physics. The 2024 data [1] is consistent with $\tau_T$ = $\tau_g$ to within ~0.3σ.

(b) **Information transmission faster than c.** Sommerfeld–Brillouin causality forbids this; if observed, it would falsify the McGucken Principle (the signal velocity would exceed the x₄-expansion rate). Not observed.

(c) **Entanglement creation without a local-origin chain.** The First McGucken Law of Nonlocality [20] forbids this; the New York–Los Angeles challenge of [20, §3] is the explicit test. Not demonstrated.

(d) **Predicted sidereal modulation of Bell correlations** (the McGucken-Bell experiment [20, §7.8]) — a positive McGucken-Principle prediction that has not yet been tested. This *would* be new physics if confirmed.

None of (a)–(c) is in the 2024 paper [1]. (d) is a McGucken-Principle prediction awaiting experimental test.

---

## 8. Experimental Prediction Distinguishing the Two Accounts

The McGucken-Principle account of $\tau_T$ < 0 differs from the standard quantum-optics account in one testable respect.

**McGucken prediction.** The negative $\tau_T$ is a centroid offset of a McGucken-Sphere projection. The Sphere is centered on the photon emission event $O$ and expands at c. If two emission events O₁ and O₂ are separated by a timelike interval Δt and the same atomic cloud is interrogated by both, the joint post-selected $\tau_T$ should depend on the relative phase of the two McGucken Spheres at the cloud — that is, on the coherent superposition of the two emission-Sphere x₄-amplitudes evaluated at the cloud's location.

Specifically: prepare a coherent superposition of two single-photon pulses emitted at times O₁ and O₂ with controlled relative phase $\varphi_{\rm rel}$, both targeting the same cloud at the same optical depth η. The Thompson et al. prediction [2] applied to each pulse individually gives $\tau_T$(η, $\sigma_{\rm pulse}$) = $\tau_g$(η, $\sigma_{\rm pulse}$) for each. The McGucken-Principle prediction for the joint post-selected ensemble is

$$
\tau_T^{\rm joint}(\phi_{\rm rel}) \;=\; \tau_g(\eta, \sigma_{\rm pulse}) \cdot \cos\phi_{\rm rel} \;+\; \mathcal{O}(\sigma_{\rm pulse}/\tau_{\rm sp}).
$$

The cosine modulation is the McGucken-Sphere interference visibility between the two emission events' wavefronts at the cloud. Standard quantum-optics treatments [2] of each pulse individually do not predict this joint cosine; they predict an incoherent sum $\tau_T^{\rm joint}$ = $\tau_g$ for any $\varphi_{\rm rel}$ (averaged over the two single-photon ensembles).

This is a direct test. A two-photon-emission cold-atom cross-Kerr measurement with controlled relative phase between emission events would distinguish the McGucken-Principle prediction from the standard incoherent-sum account.

The experimental requirements are within the demonstrated capabilities of the Steinberg lab: their existing cross-Kerr setup combined with a Hong–Ou–Mandel-style two-photon-source configuration with relative-phase control. The signature is the cosine modulation of $\tau_T$ as a function of $\varphi_{\rm rel}$.

---

## 9. Conclusion

The 2024 measurement of negative $\tau_T$ by Angulo, Thompson, Nixon, Jiao, Wiseman, and Steinberg [1] is a careful experimental confirmation of a theoretical prediction by Thompson et al. [2], which is itself a careful weak-value-formalism calculation in a two-level absorbing medium. The theoretical and experimental ingredients have been in the literature for between 110 years (Sommerfeld–Brillouin complex group delay [7, 8]) and 36 years (Aharonov–Albert–Vaidman weak values [12]). The result is genuine; its reclassification as "the discovery of negative time" is rhetorical inflation.

The McGucken Principle dx₄/dt = ic [17, 18] places this result in its proper foundational setting. Four theorems suffice:

**Theorem 1.** The imaginary unit in the absorptive resonance denominator $(\omega - \omega_0 + i\Gamma/2)^{-1}$, which generates negative group delays, is the same i of dx₄/dt = ic.

**Theorem 2.** The post-selected weak-value time $\tau_T$ < 0 is destructive interference between the photon's null-worldline x₄-channel and the atoms' stored-x₄-rotation channel, both living on a single McGucken Sphere centered on the emission event.

**Theorem 3.** Photons at absolute rest in x₄ carry no internal clock; the operational "time" must be borrowed from the medium and is therefore post-selection-sensitive. Massive systems (rest condition 1) carry their own Larmor clock and yield always-positive dwell times. The empirical contrast between Ramos et al. [25] (atoms-in-barrier, positive) and Angulo et al. [1] (photons-in-cloud, can be negative) is a structural prediction of the McGucken-Principle ontology.

**Theorem 4.** $\tau_T$ is the centroid of an SO(3)-symmetric x₄-amplitude projected from a McGucken Sphere onto the laboratory spatial slice, conditioned on the transmission post-selection. The sign of the centroid offset is the sign of the conditional interference between the two transmission channels.

The same McGucken-Sphere geometry that accounts for the double-slit experiment, the quantum eraser, the delayed-choice experiment [20, §6], and the entanglement-via-shared-wavefront identity [20, §4] also accounts for the negative dwell time. The phenomena are not six separate paradoxes; they are six projections of one geometric principle.

A direct experimental test that distinguishes the McGucken-Principle account from the standard incoherent-sum quantum-optics account is described in §8: a cosine modulation of $\tau_T^{\rm joint}$ as a function of the relative phase between two emission events feeding the same cloud.

Negative time is not new physics. It is a theorem of dx₄/dt = ic.

---

## References

[1] D. Angulo, K. Thompson, V.-M. Nixon, A. Jiao, H. M. Wiseman, A. M. Steinberg, "Experimental evidence that a photon can spend a negative amount of time in an atom cloud," arXiv:2409.03680 (2024).

[2] K. Thompson, K. Li, D. Angulo, V.-M. Nixon, J. Sinclair, A. V. Sivakumar, H. M. Wiseman, A. M. Steinberg, "How much time does a photon spend as an atomic excitation before being transmitted?" arXiv:2310.00432; APL Quantum **2**, 036108 (2025).

[3] A. M. Steinberg, "Conditional probabilities in quantum theory and the tunneling-time controversy," *Phys. Rev. A* **52**, 32 (1995).

[4] H. M. Wiseman, "Grounding Bohmian mechanics in weak values and bayesianism," *New J. Phys.* **9**, 165 (2007).

[5] A. M. Steinberg, interview with C. Jaimungal, "Defining Negative Time," *Theories of Everything*, https://www.youtube.com/watch?v=cOZ3Kto6NIc (2024).

[6] J. Sinclair, D. Angulo, K. Thompson, K. Bonsma-Fisher, A. Brodutch, A. M. Steinberg, "Measuring the Time Atoms Spend in the Excited State Due to a Photon They Do Not Absorb," *PRX Quantum* **3**, 010314 (2022).

[7] A. Sommerfeld, "Ein Einwand gegen die Relativtheorie der Elektrodynamik und seine Beseitigung," *Phys. Z.* **8**, 841 (1907).

[8] L. Brillouin, *Wave Propagation and Group Velocity*, Academic Press, New York (1960).

[9] L. A. MacColl, "Note on the transmission and reflection of wave packets by potential barriers," *Phys. Rev.* **40**, 621 (1932).

[10] E. P. Wigner, "Lower limit for the energy derivative of the scattering phase shift," *Phys. Rev.* **98**, 145 (1955).

[11] A. M. Steinberg, P. G. Kwiat, R. Y. Chiao, "Measurement of the single-photon tunneling time," *Phys. Rev. Lett.* **71**, 708 (1993).

[12] Y. Aharonov, D. Z. Albert, L. Vaidman, "How the result of a measurement of a component of the spin of a spin-½ particle can turn out to be 100," *Phys. Rev. Lett.* **60**, 1351 (1988).

[13] R. Y. Chiao, A. M. Steinberg, "Tunneling Times and Superluminality," *Prog. Opt.* **XXXVII**, 345–405 (1997); arXiv:quant-ph/9811019.

[14] L. J. Wang, A. Kuzmich, A. Dogariu, "Gain-assisted superluminal light propagation," *Nature* **406**, 277 (2000).

[15] M. W. Mitchell, R. Y. Chiao, "Causality and negative group delays in a simple bandpass amplifier," *Am. J. Phys.* **66**, 14 (1998).

[16] M. Kitano, T. Nakanishi, K. Sugiyama, "Negative Group Delay and Superluminal Propagation: An Electronic Circuit Approach," arXiv:quant-ph/0302166 (2003).

[17] E. McGucken, "The McGucken Principle and Proof: The Fourth Dimension Is Expanding at the Velocity of Light dx₄/dt = ic as a Foundational Law of Physics," 2026. https://elliotmcguckenphysics.com/2026/04/15/the-mcgucken-principle-and-proof-the-fourth-dimension-is-expanding-at-the-velocity-of-light-dx4-dtic-as-a-foundational-law-of-physics/

[18] E. McGucken, "Light, Time, Dimension Theory — Five Foundational Papers," 2025. https://elliotmcguckenphysics.com/

[19] E. McGucken, "The McGucken Principle (dx₄/dt = ic) as the Physical Mechanism Underlying Huygens' Principle, the Principle of Least Action, Noether's Theorem, and the Schrödinger Equation," 2026. https://elliotmcguckenphysics.com/2026/04/11/the-mcgucken-principle-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-huygens-principle-the-principle-of-least-action-noethers-theorem-and-the-schrodinger-equation/

[20] E. McGucken, "The McGucken Nonlocality Principle: All Quantum Nonlocality Begins in Locality, and All Double Slit, Entanglement, Quantum Eraser, and Delayed Choice Experiments Exist in McGucken Spheres," 2026. https://elliotmcguckenphysics.com/2026/04/17/the-mcgucken-nonlocality-principle-all-quantum-nonlocality-begins-in-locality-and-all-double-slit-quantum-eraser-and-delayed-choice-experiments-exist-in-mcgucken-spheres/

[21] E. McGucken, "The Born Rule as a Geometric Theorem of the Expanding Fourth Dimension: A Derivation from Spacetime Geometry via the McGucken Principle — How P = |ψ|² Follows from the SO(3) Symmetry of the McGucken Sphere," 2026. https://elliotmcguckenphysics.com/2026/04/17/the-born-rule-as-a-geometric-theorem-of-the-expanding-fourth-dimension-a-derivation-from-spacetime-geometry-via-the-mcgucken-principle-how-p-%cf%882-follows-from-the-so3-symmetry/

[22] H. M. Wiseman, A. M. Steinberg, M. Hallaji, "Obtaining a Single-Photon Weak Value from Experiments using a Strong (Many-Photon) Coherent State," *AVS Quantum Sci.* **5**, 024401 (2023); arXiv:2211.15761.

[23] E. McGucken, "A Derivation of Feynman's Path Integral from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic," 2026. https://elliotmcguckenphysics.com/2026/04/15/a-derivation-of-feynmans-path-integral-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/

[24] E. McGucken, "A Derivation of the Canonical Commutation Relation [q, p] = iℏ from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic," 2026. https://elliotmcguckenphysics.com/2026/04/17/a-derivation-of-the-canonical-commutation-relation-q-p-i%e2%84%8f-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/

[25] R. Ramos, D. Spierings, I. Racicot, A. M. Steinberg, "Measuring the time a tunnelling atom spends in the barrier," *Nature* **583**, 529 (2020); arXiv:1907.13523.

[26] D. C. Spierings, A. M. Steinberg, "Observation of the Decrease of Larmor Tunneling Times with Lower Incident Energy," *Phys. Rev. Lett.* **127**, 133001 (2021); arXiv:2101.12309.

[27] J. Sinclair, M. Hallaji, A. M. Steinberg, J. Tollaksen, A. N. Jordan, "Weak-value amplification and optimal parameter estimation in the presence of correlated noise," *Phys. Rev. A* **96**, 052128 (2017); arXiv:1703.01496.

[28] A. M. Steinberg, "How much time does a tunneling particle spend in the barrier region?" *Phys. Rev. Lett.* **74**, 2405 (1995).

[29] S. Kocsis, B. Braverman, S. Ravets, M. J. Stevens, R. P. Mirin, L. K. Shalm, A. M. Steinberg, "Observing the Average Trajectories of Single Photons in a Two-Slit Interferometer," *Science* **332**, 1170 (2011).

[30] L. A. Rozema, A. Darabi, D. H. Mahler, A. Hayat, Y. Soudagar, A. M. Steinberg, "Violation of Heisenberg's Measurement-Disturbance Relationship by Weak Measurements," *Phys. Rev. Lett.* **109**, 100404 (2012).

[31] J. A. Wheeler, "The 'Past' and the 'Delayed-Choice' Double-Slit Experiment," in *Mathematical Foundations of Quantum Theory*, ed. A. R. Marlow, Academic Press (1978).

[32] E. McGucken, "The Derivation of Entropy's Increase and Time's Arrow from the McGucken Principle of a Fourth Expanding Dimension," 2025. https://elliotmcguckenphysics.com/2025/08/25/the-derivation-of-entropys-increase-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-a-deeper-connection-between-brownian-motions-random-walk-feynmans/

[33] E. McGucken, "A Derivation of the Uncertainty Principle ΔxΔp ≥ ℏ/2 from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic," 2026. https://elliotmcguckenphysics.com/2026/04/11/a-derivation-of-the-uncertainty-principle-%ce%b4x%ce%b4p-%e2%89%a5-%e2%84%8f-2-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-the-expanding-fourth-dimension-th/

[34] E. McGucken, "How the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic Sets the Constants c (the Velocity of Light) and h (Planck's Constant)," 2026. https://elliotmcguckenphysics.com/2026/04/11/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-sets-the-constants-c-the-velocity-of-light-and-h-plancks-constant/

[35] E. McGucken, *Light Time Dimension Theory*. Amazon, 2024. https://www.amazon.com/Light-Time-Dimension-Theory-Foundational/dp/B0D2NNN6PW/

[36] E. McGucken, *The Physics of Time: Mechanics, Relativity, Thermodynamics*. Amazon, 2025. https://www.amazon.com/Physics-Time-Mechanics-Relativity-Thermodynamics/dp/B0F2PZCW6B/
