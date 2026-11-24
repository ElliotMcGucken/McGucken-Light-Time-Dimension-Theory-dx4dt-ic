# Why There Is No Time Operator in Quantum Mechanics: A Historical and Formal Analysis of Pauli's Theorem and Its Resolution in the McGucken Light–Time–Dimension Framework

**Elliot McGucken** — elliotmcguckenphysics.com

---

## Abstract

The asymmetry between position and time in quantum mechanics — X̂ᵢ exists as a self-adjoint operator on Hilbert space while T̂ does not — has been treated since Pauli (1933) either as a technical no-go obstruction to be circumvented, or as a fundamental clue that time enjoys a categorically different status from spatial coordinates. The literature divides into four broad lines: (i) bypass programmes that construct time-of-arrival, dwell-time, or POVM-valued time observables (Aharonov–Bohm 1961; Galapon 2002; Busch 2008; the Muga–Mayato–Egusquiza compendium 2002/2009); (ii) timeless cosmological interpretations in which evolution is recovered as correlation (Page–Wootters 1983; Connes–Rovelli 1994); (iii) canonical-gravity treatments where the Wheeler–DeWitt equation extinguishes coordinate time outright (DeWitt 1967; Kuchař 1991; Isham 1992; Unruh–Wald 1989; Anderson 2017); and (iv) parameter-versus-observable analyses arguing the question is a category error (Hilgevoord 2002, 2005). Across all four lines, the basic explanation has remained *negative*: it states what time is not (an operator), not what time positively is. The present paper supplies a positive mechanism. We show that within the McGucken Light–Time–Dimension framework, with dx₄/dt = ic taken as a physical principle, Pauli's theorem becomes not an obstruction but a forced consequence: t is the parameter of the universal expansion of the fourth dimension, while x₄ = ict is its integrated coordinate shadow; the spatial coordinates x₁, x₂, x₃ label degrees of freedom in which a system can be localised, and x₄ is locked to t by the active expansion. Operators attach to genuine degrees of freedom; they do not attach to the substrate of evolution itself. We give a full historical reconstruction of the literature, prove the relevant theorems, and identify exactly where the McGucken reading converges with — and diverges from — each prior school. The Wheeler–DeWitt "frozen formalism" resolves automatically as a degenerate special case.

---

## 1. Introduction

Quantum mechanics elevates the position observables X̂₁, X̂₂, X̂₃ and their conjugate momenta P̂₁, P̂₂, P̂₃ to self-adjoint operators on a Hilbert space, satisfying the canonical commutation relations

[X̂ᵢ, P̂ⱼ] = iℏ δᵢⱼ, i, j ∈ {1, 2, 3}.    (1)

There is no fourth pair (T̂, Ĥ) playing the same role. The Hamiltonian Ĥ is the generator of evolution in t, but t enters the Schrödinger equation

iℏ ∂ψ/∂t = Ĥ ψ    (2)

as a c-number parameter, not as an operator. The standard short answer is the one inherited from Pauli (1933): a self-adjoint operator T̂ satisfying [T̂, Ĥ] = iℏ would force Ĥ to have spectrum ℝ, contradicting the empirically required lower bound on energy.

That short answer is correct as far as it goes, but it is structurally negative. It tells us what cannot exist, not why the universe has organised matters so that what cannot exist is exactly what is not needed. The literature on this question is now nearly a century old, generating major programmes in quantum measurement theory, quantum cosmology, and canonical quantum gravity, each grappling in its own way with the residual asymmetry.

**Aim of this paper.** We do two things. First, we provide a complete and historically faithful map of the literature on the time-operator question, organised by approach rather than by date, with the major references read directly and tracked individually. Second, we propose a positive resolution: within the McGucken Light–Time–Dimension (LTD) framework, the parameter t has a clear and concrete physical interpretation as the parameter of the universal active expansion of the fourth dimension at velocity c, the principle dx₄/dt = ic. Under this reading, Pauli's theorem ceases to be an obstruction and becomes a consistency check: of course t admits no self-adjoint operator conjugate to Ĥ, because t is not a coordinate the system inhabits but the parameter of a universal, state-independent, geometric process.

**Structure.** Section 2 reconstructs Pauli's 1933 argument with mathematical care and identifies its precise logical content. Section 3 surveys the bypass literature — Aharonov–Bohm, the time-of-arrival programme, the POVM approach, and Galapon's recent self-adjoint constructions on restricted domains. Section 4 treats the timeless cosmological interpretations of Page–Wootters and Connes–Rovelli. Section 5 treats the canonical-gravity programme: DeWitt 1967, the Kuchař–Isham reviews, Unruh–Wald, and Anderson's modern synthesis. Section 6 treats the parameter-versus-observable line, principally Hilgevoord. Section 7 introduces the McGucken framework and proves the relevant structural theorems. Section 8 shows how the framework reads Pauli's theorem, the Wheeler–DeWitt equation, and the time-of-arrival programme as theorems and special cases of dx₄/dt = ic. Section 9 compares the McGucken resolution to each prior line. Section 10 concludes.

---

## 2. Pauli's Theorem: Statement and Logical Content

### 2.1 The 1933 argument

In his *Handbuch der Physik* article *Die allgemeinen Prinzipien der Wellenmechanik*, Pauli observed in a footnote that the canonical commutation relation

[T̂, Ĥ] = iℏ 𝟙    (3)

cannot hold for a self-adjoint T̂ if Ĥ has a spectrum bounded from below or composed of discrete eigenvalues. The English translation appeared as Pauli's *General Principles of Quantum Mechanics* [1].

The argument is as follows. Suppose T̂ is self-adjoint and (3) holds on a dense domain. Then for each real ε, the operator Uₑ = exp(−iεT̂/ℏ) is unitary. A standard computation gives

Uₑ† Ĥ Uₑ = Ĥ + ε 𝟙.    (4)

If Ĥ φ_E = E φ_E, then Ĥ (Uₑ φ_E) = (E + ε)(Uₑ φ_E), so for every real ε the value E + ε is an eigenvalue (or at least a spectral value) of Ĥ. Since ε ranges over all of ℝ, the spectrum of Ĥ must be all of ℝ.

This contradicts the empirically required semiboundedness of physical Hamiltonians (the ground state of any stable physical system has finite energy bounded below by some E₀ > −∞). Hence no such self-adjoint T̂ exists.

**Theorem 2.1 (Pauli 1933).** *Let Ĥ be a self-adjoint operator on a Hilbert space ℋ with spec(Ĥ) ⊊ ℝ. Then there exists no self-adjoint operator T̂ on ℋ such that [T̂, Ĥ] = iℏ 𝟙 holds on a dense domain invariant under both operators.*

The clearest modern restatements, with the spectral assumption made explicit, appear in Leon and Maccone [33] and in the introductory section of Galapon [19].

### 2.2 What Pauli's theorem does and does not say

Three points are essential.

*(1) The theorem is about self-adjoint T̂ with full canonical commutation on a dense invariant domain.* If any of these conditions is relaxed, the conclusion can fail. This is the loophole exploited by the bypass programmes (Section 3).

*(2) The theorem is a negative existence result, not an explanation.* It tells us no T̂ exists; it does not tell us *why* the world is organised so that no T̂ is needed. The textbook answer is that "t is a parameter, not an observable" [17, 22], which is descriptively correct but explanatorily silent: it labels the asymmetry without grounding it.

*(3) The theorem says nothing about coordinate time as a label.* The variable t that appears in (2) is a real number labelling the integral curves of the evolution generator. Pauli's theorem says only that this label cannot be promoted to an operator without breaking semiboundedness. It is silent on whether t has a deeper geometric or physical meaning.

The present paper takes point (3) seriously. The McGucken framework supplies t with a definite physical content (it parameterises the universal expansion at c), and on that basis Pauli's theorem reads as a forced consequence of the structure, not an isolated technical curiosity.

---

## 3. The Bypass Programme: Time-of-Arrival, POVMs, and Constructive Time Operators

### 3.1 Aharonov and Bohm

Aharonov and Bohm [2], working at Bristol in 1961, took the first major step toward circumventing Pauli's theorem in a constructive direction. Their abstract opens by acknowledging the situation explicitly: "Because time does not appear in Schrödinger's equation as an operator but only as a parameter, the time-energy uncertainty relation must be formulated in a special way." Their target was the common claim that any energy measurement carried out in time Δt must produce an energy uncertainty ΔE ≳ ℏ/Δt. They showed that this conclusion was *not* a consistent corollary of the quantum formalism — the measurement-theoretic argument generalising it was flawed.

In the course of this analysis they introduced what is now called the Aharonov–Bohm time-of-arrival operator. For a free particle of mass m in one dimension, one defines (on a suitable dense domain)

T̂_AB = −(m/2)(X̂ P̂⁻¹ + P̂⁻¹ X̂).    (5)

This operator is symmetric but not self-adjoint: it fails to admit a self-adjoint extension on the full free-particle Hilbert space precisely because Ĥ_free = P̂²/2m has [0, ∞) spectrum. The Pauli obstruction reappears, geometrically, as a defect index. Razavi [3] later extended the construction to spin-0 relativistic particles.

The Aharonov–Bohm operator remains an active research object. Kijowski [4] associated a POVM to it, satisfying covariance under time translation; Muga and collaborators have analysed dwell time and tunneling time within this framework [20, 26].

### 3.2 Time observables as POVMs

The structural lesson of the Aharonov–Bohm analysis is that demanding self-adjointness may be too strict. Busch, Grabowski, and Lahti developed an operational quantum measurement theory in which observables are positive operator-valued measures (POVMs) rather than projection-valued measures [14]. A POVM time observable need not produce eigenvalues across all of ℝ; it need only assign positive operators to measurable subsets of a time axis, satisfying the appropriate covariance condition.

Busch's encyclopedic review [24] systematises this approach for time-energy uncertainty relations, distinguishing external (parameter) time from event time and from observable time. The volumes edited by Muga, Sala Mayato, and Egusquiza [20, 26] compile the technical state of the art across arrival, dwell, decay, and tunneling times.

Brunetti and Fredenhagen [18, 30] derived time-translation-covariant POVMs associated with positive "event" operators and proved a new uncertainty relation for arrival times alone.

### 3.3 Galapon's bypass: self-adjoint time operators on restricted domains

The most striking modern development is due to Galapon. In two papers [19, 20], he proved that for every discrete semibounded Hamiltonian whose eigenvalues satisfy a mild growth condition and whose eigenvectors span the Hilbert space, there exists a self-adjoint "characteristic time operator" canonically conjugate to Ĥ *on a dense subspace*. The trick is that the canonical commutation relation need not hold on the same domain on which Pauli's argument operates. Galapon's construction has been extended to finite-dimensional Hamiltonians [38] and to generalised Hamiltonians by Arai and collaborators [25].

Isidro [21] pursued an alternative bypass using the holomorphic Fourier transformation rather than the standard Fourier transformation, again producing a self-adjoint T̂ compatible with a semibounded Ĥ.

### 3.4 What the bypass programme establishes

Collectively, the bypass programme establishes that Pauli's theorem is best read as a statement about the domain on which canonical commutation holds, not as a complete prohibition on the existence of any operator labelled "time." Time observables exist in the POVM sense, and self-adjoint time operators exist on restricted domains. The bypass programme tells us *how* to construct such objects when they are useful (e.g., for time-of-arrival statistics in scattering experiments).

What the bypass programme does not address is the deeper question: why is the universe organised so that the operator T̂ canonically conjugate to Ĥ does not arise naturally as part of the fundamental theory? Time-of-arrival is an event observable defined relative to a fixed spatial detector; it is not the analogue of X̂ᵢ. The asymmetry between position and time persists at the level of the fundamental kinematic structure even after every bypass construction has been catalogued.

---

## 4. The Timeless Interpretations: Page–Wootters and Connes–Rovelli

### 4.1 Page and Wootters: evolution as correlation

Page and Wootters [5] took the Pauli obstruction at face value and asked: if the universe as a whole is in a stationary state — if every observable commutes with the total Hamiltonian — then how does the appearance of dynamical evolution arise? Their answer is that evolution is correlation. Within a stationary global state of the universe, split into a "clock" subsystem C and a "rest" subsystem R, the conditional state of R given that C reads a particular clock value τ evolves unitarily in τ. Time emerges as a quantum reference frame internal to the universe.

The construction was criticised early for ambiguities under different choices of clock observable [10]. Giovannetti, Lloyd, and Maccone [32] showed that the ambiguities can be removed and gave an experimental realisation; Smith, Höhn, and collaborators [35, 36] have developed the Page–Wootters approach into a relational framework for quantum reference frames.

The Page–Wootters response to "why no time operator?" is structural: there *is* a time-like quantum reference, but it lives in a clock subsystem of the universe, not in an absolute external parameter. The Schrödinger t is the eigenvalue of a clock observable in a particular relational decomposition. This is metaphysically substantive but does not yet supply a geometric *mechanism* for the asymmetry.

### 4.2 Connes–Rovelli: thermal time

A different timeless line was opened by Rovelli [12, 13] and developed jointly with Connes [11]. The thermal time hypothesis posits that the flow of time is not a fundamental kinematic structure but is determined by the statistical (KMS) state of the system: given a thermal state ω on a von Neumann algebra of observables, the modular automorphism group of Tomita–Takesaki theory provides a one-parameter flow that plays the role of time. In a Robertson–Walker universe, the thermal time associated with the cosmic microwave background coincides with cosmological proper time [13].

Rovelli's longer essay [34] ("Forget time") and the analyses by Martinetti–Rovelli [31] and Chua [37] develop the philosophical and technical content. The position is radical: time is not a substance, not a parameter, not even a quantum reference frame, but a thermodynamic emergent.

The Connes–Rovelli approach again declines to provide a positive geometric mechanism. Time emerges from algebra and state, not from any underlying physical process. The framework is elegant but explanatorily "mechanism-free."

---

## 5. The Canonical-Gravity Programme: DeWitt, Kuchař, Isham, Unruh–Wald

### 5.1 The Wheeler–DeWitt equation

DeWitt's 1967 papers [6, 7, 8] initiated the canonical quantisation of general relativity. The Hamiltonian formulation of GR is a constrained system: the super-Hamiltonian constraint 𝓗 ≈ 0 and the supermomentum constraints 𝓗ᵢ ≈ 0 generate gauge transformations corresponding to spacetime diffeomorphisms. Canonical quantisation promotes the constraints to operator equations on physical states:

𝓗̂ Ψ[gᵢⱼ] = 0.    (6)

The constraint (6) is the Wheeler–DeWitt equation, and its central feature is that there is *no t*. The state functional Ψ depends on the spatial three-metric gᵢⱼ but not on any external time. The dynamics of GR, when canonically quantised, freezes.

### 5.2 The Kuchař–Isham reviews

The frozen formalism generated a generation of conceptual analysis. Kuchař [10], in a now-canonical 1991 conference review (republished in IJMPD in 2011), examined ten major attempts to recover dynamics from (6): internal time, matter time, fixed gauges, conditional probabilities, evolving constants of the motion, and so on. Isham's parallel review [16] gave the same problem a different but complementary mathematical organisation. Both authors concluded that no fully consistent recovery existed at the time of writing.

Unruh and Wald [9] argued that the absence of a time observable in canonical quantum gravity is not a technical defect to be remedied but a feature reflecting the diffeomorphism invariance of GR: a coordinate time has no gauge-invariant meaning, hence no operational meaning.

The modern synthesis is Anderson's monograph [29] and his earlier review [27, 28]. Anderson distinguishes eight facets of the problem of time and surveys all major strategies, from time-before-quantisation to time-after-quantisation to fully timeless approaches.

### 5.3 What canonical gravity contributes

The canonical-gravity programme established that the time-operator problem in non-relativistic QM is not isolated. It is the low-energy fragment of a deeper structure in which t is gauge in GR and absent in canonical quantum gravity. Any resolution of "why no T̂?" that does not also explain the Wheeler–DeWitt freezing has missed the point.

Conversely, any framework that takes t to be the parameter of a definite physical process — one that is universal, state-independent, and geometrically explicit — has a candidate response: such a t would not need to be a coordinate at all, and its non-appearance as an operator in QM is precisely what one would expect.

---

## 6. The Parameter-Versus-Observable Line: Hilgevoord

The most philosophically careful argument in the literature that the time-operator question is a category error is due to Hilgevoord. In a sequence of papers [15, 16, 17, 22, 27], he argued that the apparent asymmetry between time and position dissolves once one distinguishes *coordinate* variables from *dynamical* variables.

His argument runs as follows. In a Newtonian world with a fixed spacetime background, *neither* t nor the spatial coordinates xⁱ of the background are operators: they are labels of the manifold. What become operators in QM are the *dynamical* position variables of specific physical systems — the position of an electron, the centre-of-mass coordinate of an atom, and so on. Time, in the relevant operational sense, would be the dynamical time variable associated with a specific physical clock; such variables can indeed be promoted to operators (subject to Galapon-type domain conditions).

Hilgevoord's resolution is conceptually clean and aligns closely with the operational POVM approach. What it does not supply is an account of *why* the background t has the structure it does. The background is taken as given.

---

## 7. The McGucken Light–Time–Dimension Framework

### 7.1 The principle

We now turn to the McGucken Light–Time–Dimension framework. Its central postulate is a single physical principle.

**Principle 7.1 (McGucken Principle).** *The fourth dimension expands at velocity c, spherically symmetrically, from every event in spacetime:*

dx₄/dt = ic.    (7)

*The expansion is universal (it occurs from every event), state-independent (it is the same for every physical system), and geometric (it is a fact about the manifold, not about any matter field).*

The factor of i is essential and carries definite physical content: it encodes the linear–rotational duality between translation along x₄ and rotation in any plane containing the x₄-axis. We address this in detail below.

The integrated coordinate shadow of the principle is

x₄ = ict,    (8)

which is exactly the imaginary fourth Minkowski coordinate familiar from special relativity. *Equation (8) is a derived integral expression, not a postulate.* Every theorem of the framework traces to the active expansion (7); the coordinate label (8) is its mere integrated shadow. The word "mere" is load-bearing: x₄ does not have independent existence as a coordinate of the system. It is bookkeeping for the universal expansion.

### 7.2 The four-fold ontology

The principle organises kinematics into four distinct modes:

**(1) Absolute rest in x₁x₂x₃.** A massive particle at spatial rest puts its entire kinematic budget into x₄-advance at velocity ic.

**(2) Absolute rest in x₄.** A photon, in the sense that dx₄/dt = 0 along its null worldline, puts its entire kinematic budget into spatial motion at c.

**(3) Absolute motion.** The universal x₄-expansion from every event, at velocity ic, occurs irrespective of state.

**(4) CMB frame.** The isotropic cosmological x₄-expansion is observed empirically as the cosmic microwave background rest frame.

In every mode, t is the parameter of the expansion. It is not an observable of any system; it is the universal scalar bookkeeping for (7).

### 7.3 Position operators versus the time parameter

We now address the central structural point. The spatial coordinates x₁, x₂, x₃ are kinematically distinct from the (x₄, t) axis in a way that admits operator promotion. We make this precise.

**Definition 7.2 (Genuine degree of freedom).** *A coordinate ξ of a physical system is a genuine degree of freedom if the system's state can vary independently in ξ — that is, if ξ admits localised states, superposition over distinct ξ-values, and dynamical conjugation to a generator of ξ-translations.*

**Proposition 7.3 (Spatial coordinates are genuine degrees of freedom).** *x₁, x₂, x₃ are genuine degrees of freedom in the sense of Definition 7.2.*

*Proof.* The spatial position of a system can take any value in ℝ³. Superposition over distinct positions is observed (interference experiments). The generator of xᵢ-translations is the conjugate momentum P̂ᵢ. All three conditions of Definition 7.2 hold. ∎

**Proposition 7.4 (t is not a genuine degree of freedom).** *Under Principle 7.1, t is not a genuine degree of freedom of any physical system.*

*Proof.* By (7), dx₄/dt = ic universally and state-independently. The parameter t labels the integral curves of the universal expansion. A physical system does not have an independent "t-value" that can vary across states; every event in spacetime has a single t assigned by the universal expansion's parameterisation. Superposition over distinct t-values is not a feature of the system but, at most, a feature of how the system is sampled or measured along its worldline. The conjugate generator of "t-translations" is the Hamiltonian Ĥ, but Ĥ generates evolution of the state, not translation of a localisable t-coordinate of the system. ∎

**Proposition 7.5 (x₄ is not an independent coordinate).** *Under Principle 7.1, x₄ is locked to t by x₄ = ict + x₄⁽⁰⁾ for some initial value x₄⁽⁰⁾ and is not an independent coordinate of the system.*

*Proof.* Integration of (7) along an integral curve gives x₄(t) = ict + x₄⁽⁰⁾. There is no freedom in this relation; it follows from the universality and state-independence of the expansion. Hence x₄ supplies no new information beyond t and x₄⁽⁰⁾. ∎

### 7.4 The role of i

The factor of i in (7) is not a notational convenience. It encodes the duality between x₄-translation and rotation in any plane containing the x₄-axis. Multiplication by i in the complexified coordinate x₄ corresponds, in the real Minkowski coordinate, to a rotation of π/2 in the relevant (xᵢ, ct) plane — precisely a Lorentz boost in the rapidity formulation. The i is therefore the algebraic carrier of the linear–rotational duality that makes Lorentz transformations into Euclidean rotations on the imaginary fourth axis.

This has further structural consequences (spin and polarisation arise as forced theorems of the linear–rotational duality reading), which we have developed elsewhere and do not pursue here. What matters for the present argument is that the principle (7) is genuinely geometric: it specifies an active, oriented, complex-valued flow, not a passive coordinate convention.

---

## 8. Resolution of the Time-Operator Question

### 8.1 The main theorem

**Theorem 8.1 (Forced asymmetry under the McGucken Principle).** *Under Principle 7.1, the canonical quantisation of a physical system admits self-adjoint position operators X̂ᵢ with conjugate momenta P̂ᵢ satisfying (1), but admits no self-adjoint operator T̂ canonically conjugate to Ĥ on a dense invariant domain. The asymmetry is forced by Propositions 7.3–7.5 together with Pauli's theorem (Theorem 2.1).*

*Proof.* By Proposition 7.3, x₁, x₂, x₃ are genuine degrees of freedom; canonical quantisation supplies X̂ᵢ, P̂ᵢ with the canonical commutation relations. By Propositions 7.4 and 7.5, neither t nor x₄ is a genuine degree of freedom; there is no system observable corresponding to "t of the system." The Hamiltonian Ĥ generates evolution along the universal expansion parameter t. By Pauli's theorem (Theorem 2.1), no self-adjoint T̂ canonically conjugate to a semibounded Ĥ exists on a dense invariant domain. All three facts cohere: there is no T̂ because there is no degree of freedom for T̂ to operator-promote. ∎

*Remark.* The Galapon-type bypass constructions [19] are compatible with Theorem 8.1: they exhibit operators that satisfy the canonical commutation relation on a restricted dense subspace, but they do not contradict the absence of a system-wide time observable. From the McGucken viewpoint, such constructions are best read as event-observables (time of arrival, time of decay) attached to specific dynamical processes, not as the elusive T̂ conjugate to Ĥ in the universal sense.

### 8.2 The Wheeler–DeWitt equation as a degenerate special case

**Theorem 8.2 (Wheeler–DeWitt freezing as gauge-fixed shadow).** *Within the McGucken framework, the Wheeler–DeWitt equation (6) corresponds to a complete gauge-fixing in which the coordinate time t has been quotiented away, leaving only the integrated x₄-shadow. The absence of t-dependence in Ψ[gᵢⱼ] is the canonical-gravity expression of Proposition 7.4.*

*Proof (sketch).* In canonical GR, the Hamiltonian constraint 𝓗 ≈ 0 generates time-reparameterisations. Quantising yields (6), and the state functional carries no t. Under Principle 7.1, this is not a defect but the expected feature: t is the parameter of the universal expansion, not a degree of freedom of any system, hence not a quantum number labelling states. The state functional Ψ[gᵢⱼ] depends on the spatial three-metric — the genuine kinematic degrees of freedom — and not on t. Equation (6) is the Wheeler–DeWitt expression of the same structural fact that, in non-relativistic QM, manifests as the absence of T̂. ∎

The "problem of time" as catalogued by Kuchař [10] and Isham [16] is therefore not a problem to be solved by ingenuity but a structural prediction: any framework in which t is the parameter of a state-independent process must lose explicit t-dependence under any consistent quantisation.

### 8.3 Schrödinger's equation as evolution along the expansion parameter

**Theorem 8.3 (Reading of the Schrödinger equation).** *Under Principle 7.1, the Schrödinger equation (2) is read as: Ĥ generates evolution of the state along the universal expansion parameter t. The variable t does not require an operator promotion because it is not a coordinate the system inhabits; the state's dependence on t is its evolution along the integral curves of the expansion.*

*Proof (sketch).* The Schrödinger equation is the infinitesimal version of unitary evolution U(t) = exp(−iĤt/ℏ). The variable t parameterises a one-parameter unitary group generated by Ĥ. By Principle 7.1, this t is the universal expansion parameter. Hence Ĥ is the local generator of the expansion as seen by the system's Hilbert-space state. ∎

---

## 9. Comparison with Prior Lines

We summarise how the McGucken resolution stands relative to each prior approach.

### 9.1 Versus the bypass programme (Aharonov–Bohm, Galapon, Busch)

The bypass programme is correct in its own terms: time observables exist as POVMs and self-adjoint operators exist on restricted domains. The McGucken reading agrees, and reinterprets these constructions as event-observables (time of arrival at a detector, time of decay) rather than as system-time conjugates of Ĥ. The deeper question — why is the universal t structured so that no system-wide T̂ arises naturally? — is what the bypass programme does not answer and what the McGucken Principle does.

### 9.2 Versus the timeless interpretations (Page–Wootters, Connes–Rovelli)

The timeless interpretations agree with the McGucken reading on the descriptive fact that t is not a system observable. They differ on the mechanism. Page–Wootters identifies t with the eigenvalue of a clock observable in a relational decomposition; Connes–Rovelli identifies the flow of time with the modular automorphism of a thermal state. Neither supplies a fixed, universal, geometric content for t. The McGucken Principle supplies one: t parameterises the universal x₄-expansion at velocity c. The thermal time of Connes–Rovelli, restricted to the CMB rest frame, coincides with cosmological proper time, which is also the parameter of the isotropic x₄-expansion (mode (4) of the four-fold ontology). The two pictures touch at the cosmological scale but diverge in their accounts of why.

### 9.3 Versus canonical gravity (DeWitt, Kuchař, Isham, Unruh–Wald, Anderson)

The canonical-gravity programme correctly identifies the structural fact: t disappears in the Wheeler–DeWitt equation, and the problem of time has multiple facets [29]. The McGucken reading supplies the underlying mechanism: t is the universal expansion parameter, so its absence as a quantum number is forced. The Wheeler–DeWitt equation is the canonical-gravity shadow of the same structural fact responsible for the absence of T̂ in non-relativistic QM.

### 9.4 Versus the parameter-versus-observable line (Hilgevoord)

Hilgevoord's analysis is the closest in spirit to the McGucken reading. Hilgevoord distinguishes coordinate variables (which are not operators) from dynamical variables (which can be). The McGucken Principle supplies the missing piece: *what makes t a coordinate variable in particular?* The answer is that t is the parameter of a universal, state-independent, geometric process. Hilgevoord's clean philosophical reading and the McGucken physical principle are complementary.

---

## 10. Conclusion

The absence of a time operator in quantum mechanics has been treated for nearly a century as a technical obstruction (Pauli), a domain question to be circumvented (Aharonov–Bohm, Galapon, Busch), an emergent-relational fact (Page–Wootters, Connes–Rovelli), a constraint-quantisation phenomenon (DeWitt, Kuchař, Isham), or a category-error (Hilgevoord). Each treatment is correct within its scope. None of them supplies a positive geometric mechanism for why t should have the structure it does.

The McGucken Light–Time–Dimension framework supplies the mechanism. Under the principle dx₄/dt = ic, the parameter t is the bookkeeping for a universal active expansion of the fourth dimension at velocity c, occurring from every event in spacetime, the same for every physical system. The spatial coordinates x₁, x₂, x₃ are genuine degrees of freedom in which a system can be localised, superposed, and translated by conjugate momenta. The parameter t is not such a degree of freedom; x₄ = ict is its mere integrated shadow. Pauli's theorem is then a forced consequence: there is no T̂ because there is no degree of freedom for T̂ to quantise. The Wheeler–DeWitt freezing is the same fact under canonical gravity. The time-of-arrival operators and POVM time observables are correct event-observables but not the elusive system-time conjugate of Ĥ.

The four prior lines of attack converge structurally on the conclusion that t is not what naive operator-promotion would make it. The McGucken Principle supplies the positive content for what t is instead. The asymmetry between position and time in quantum mechanics is, on this reading, a theorem of the geometry of the fourth dimension.

---

## References

[1] W. Pauli, *General Principles of Quantum Mechanics*, translated by P. Achuthan and K. Venkatesan (Springer-Verlag, Berlin, 1980). Originally published as "Die allgemeinen Prinzipien der Wellenmechanik," in *Handbuch der Physik*, Vol. 24, Part 1 (Springer, Berlin, 1933).

[2] Y. Aharonov and D. Bohm, "Time in the Quantum Theory and the Uncertainty Relation for Time and Energy," *Phys. Rev.* **122**, 1649–1658 (1961). DOI: 10.1103/PhysRev.122.1649.

[3] M. Razavi, "Quantum-mechanical time operator," *Il Nuovo Cimento B* **63**, 271 (1969).

[4] J. Kijowski, "On the time operator in quantum mechanics and the Heisenberg uncertainty relation for energy and time," *Rep. Math. Phys.* **6**, 361–386 (1974).

[5] D. N. Page and W. K. Wootters, "Evolution without evolution: Dynamics described by stationary observables," *Phys. Rev. D* **27**, 2885–2892 (1983). DOI: 10.1103/PhysRevD.27.2885.

[6] B. S. DeWitt, "Quantum Theory of Gravity. I. The Canonical Theory," *Phys. Rev.* **160**, 1113–1148 (1967). DOI: 10.1103/PhysRev.160.1113.

[7] B. S. DeWitt, "Quantum Theory of Gravity. II. The Manifestly Covariant Theory," *Phys. Rev.* **162**, 1195–1238 (1967).

[8] B. S. DeWitt, "Quantum Theory of Gravity. III. Applications of the Covariant Theory," *Phys. Rev.* **162**, 1239–1256 (1967).

[9] W. G. Unruh and R. M. Wald, "Time and the interpretation of canonical quantum gravity," *Phys. Rev. D* **40**, 2598–2614 (1989).

[10] K. V. Kuchař, "Time and interpretations of quantum gravity," in *Proceedings of the 4th Canadian Conference on General Relativity and Relativistic Astrophysics*, Winnipeg, 1991; reprinted in *Int. J. Mod. Phys. D* **20**, 3–86 (2011).

[11] A. Connes and C. Rovelli, "Von Neumann algebra automorphisms and time–thermodynamics relation in general covariant quantum theories," *Class. Quantum Grav.* **11**, 2899–2917 (1994). arXiv:gr-qc/9406019.

[12] C. Rovelli, "Statistical mechanics of gravity and the thermodynamical origin of time," *Class. Quantum Grav.* **10**, 1549–1566 (1993).

[13] C. Rovelli, "The statistical state of the universe," *Class. Quantum Grav.* **10**, 1567 (1993).

[14] P. Busch, M. Grabowski, and P. J. Lahti, *Operational Quantum Physics* (Springer, Berlin, 1995).

[15] J. Hilgevoord, "The uncertainty principle for energy and time," *Am. J. Phys.* **64**, 1451–1456 (1996).

[16] C. J. Isham, "Canonical Quantum Gravity and the Problem of Time," in L. A. Ibort and M. A. Rodríguez (eds.), *Integrable Systems, Quantum Groups, and Quantum Field Theories* (Springer, Dordrecht, 1993), pp. 157–287. arXiv:gr-qc/9210011.

[17] J. Hilgevoord, "Time in quantum mechanics," *Am. J. Phys.* **70**, 301–306 (2002). DOI: 10.1119/1.1430697.

[18] R. Brunetti and K. Fredenhagen, "Time of occurrence observable in quantum mechanics," *Phys. Rev. A* **66**, 044101 (2002).

[19] E. A. Galapon, "Self-adjoint time operator is the rule for discrete semi-bounded Hamiltonians," *Proc. R. Soc. Lond. A* **458**, 2671–2689 (2002). arXiv:quant-ph/0111061.

[20] E. A. Galapon, "Pauli's theorem and quantum canonical pairs: The consistency of a bounded, self-adjoint time operator canonically conjugate to a Hamiltonian with non-empty point spectrum," *Proc. R. Soc. Lond. A* **458**, 451–472 (2002).

[21] J. M. Isidro, "Bypassing Pauli's theorem," arXiv:quant-ph/0410070 (2004).

[22] J. Hilgevoord, "Time in quantum mechanics: a story of confusion," *Stud. Hist. Philos. Mod. Phys.* **36**, 29–60 (2005).

[23] J. G. Muga, R. Sala Mayato, and Í. L. Egusquiza (eds.), *Time in Quantum Mechanics*, Vol. 1, Lecture Notes in Physics 734 (Springer, Berlin, 2002; 2nd ed. 2008).

[24] P. Busch, "The Time–Energy Uncertainty Relation," in [23], 2nd ed., pp. 73–105 (Springer, Berlin, 2008). arXiv:quant-ph/0105049.

[25] A. Arai, "Strong time operators associated with generalized Hamiltonians," *Lett. Math. Phys.* **87**, 67–80 (2009).

[26] J. G. Muga, A. Ruschhaupt, and A. del Campo (eds.), *Time in Quantum Mechanics*, Vol. 2, Lecture Notes in Physics 789 (Springer, Berlin, 2009).

[27] E. Anderson, "The Problem of Time in Quantum Gravity," arXiv:1009.2157 (2010).

[28] J. Hilgevoord and D. Atkinson, "Time in quantum mechanics," in C. Callender (ed.), *The Oxford Handbook of Philosophy of Time* (Oxford University Press, 2011), pp. 647–662.

[29] E. Anderson, "Problem of Time in Quantum Gravity," arXiv:1206.2403 (2012).

[30] R. Brunetti and K. Fredenhagen, "Remarks on time-energy uncertainty relations," arXiv:quant-ph/0207048 (revised 2013).

[31] P. Martinetti and C. Rovelli, "Diamond's temperature: Unruh effect for bounded trajectories and thermal time hypothesis," *Class. Quantum Grav.* **20**, 4919–4932 (2003).

[32] V. Giovannetti, S. Lloyd, and L. Maccone, "Quantum time," *Phys. Rev. D* **92**, 045033 (2015).

[33] E. Anderson, *The Problem of Time: Quantum Mechanics versus General Relativity*, Fundamental Theories of Physics 190 (Springer, Cham, 2017).

[34] J. Leon and L. Maccone, "The Pauli objection," *Found. Phys.* **47**, 1597–1608 (2017). arXiv:1705.09212.

[35] C. Rovelli, "Forget time," essay for the FQXi contest on the nature of time, arXiv:0903.3832 (2009); revised version *Found. Phys.* **41**, 1475–1490 (2011).

[36] P. A. Höhn, "Switching internal times and a new perspective on the 'wave function of the universe'," *Universe* **5**, 116 (2019).

[37] A. R. H. Smith and M. Ahmadi, "Quantizing time: Interacting clocks and systems," *Quantum* **3**, 160 (2019).

[38] E. Y. S. Chua, "The time in thermal time," arXiv:2407.18948 (2024).

[39] E. A. Galapon, "Self-adjoint time operator is the rule for finite-dimensional bounded discrete Hamiltonians," *Proc. Samahang Pisika ng Pilipinas* (2024).

[40] E. McGucken, "The McGucken Principle and the Light–Time–Dimension framework," technical paper corpus at elliotmcguckenphysics.com.
