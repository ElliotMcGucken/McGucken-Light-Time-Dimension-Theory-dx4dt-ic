# The Born Rule P = |ψ|² as a Theorem of the McGucken Principle dx₄/dt = ic: The Century of Postulation and Reconstruction from Born 1926 to Masanes–Galley–Müller 2019 and Neumaier 2025, the Five McGucken-Sphere Routes to the Exponent 2, and the Derivation along the dx₄/dt = ic Algebraic Channel and the dx₄/dt = ic Geometric Channel of the McGucken Duality


**Elliot McGucken**\
Light, Time, Dimension Theory\
elliotmcguckenphysics.com\
drelliot@gmail.com

> *"More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student… Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet."* — **John Archibald Wheeler**, Joseph Henry Professor of Physics, Princeton

## Abstract

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality. This paper is devoted to one theorem of that Principle: the Born rule P(x) = |ψ(x)|². The rule entered physics in 1926 as a footnote added in proof to Born's collision paper, and for a century every derivation offered for it — Gleason's measure theorem, the frequentist programmes, the Deutsch–Wallace decision theory, Zurek's envariance, Bohmian quantum equilibrium, Sebens–Carroll self-location, the Masanes–Galley–Müller operational-redundancy theorem, Saunders's branch counting, QBist coherence, the Hardy and Chiribella–D'Ariano–Perinotti reconstructions, the Davies–Lewis POVM generalization and Neumaier's Detector Response Principle — has operated inside a Hilbert space taken as primitive and has imported one supplementary axiom that is the Born measure already. The McGucken dx₄/dt = ic framework operates upstream of the Hilbert space: the wavefunction is the projection of x₄-advance onto the spatial slice (Definition 2.6), the Hilbert space is the Cauchy completion of such projections (Theorem 6.1), and the Born density is the unique density on this structure satisfying four requirements — reality, non-negativity, phase invariance under a global x₄-shift, and locality with conservation under x₄'s expansion — each of which is supplied by a property of the McGucken Sphere and none of which is imported as a probability axiom; bilinearity in (ψ, ψ^*) is the conclusion, since conservation of the Sphere's weight under the Klein–Gordon propagation forces F(|ψ|) = κ|ψ|² for an arbitrary function F of the modulus (Lemma 7.1, Theorem 7.2). The exponent 2 is overdetermined by five Sphere routes sharing no machinery beyond the Principle: the Conservation Route (the Sphere's weight conserved along its expansion, with the rank-2 character of (ic)² = -c² entering through the second-order Klein–Gordon equation, Lemma 7.1), the Haar Route (the unique SO(3)-invariant probability measure on the Sphere, Lemma 7.1.5), the Norm Route (the parallelogram identity from rank-2 sesquilinearity, Lemma 7.6), the Collision Route (the two-participant head-on x₄-collision of the emitter's and absorber's Spheres, Theorem 7.7 and Lemma 7.7.5), and the PT-Symmetry Route (complex conjugation as the Sphere's PT_E reflection through its source event, Theorem 7.11).

The derivation runs along the two channels of the McGucken Duality, which the paper defines in depth. The dx₄/dt = ic Geometric Channel carries the whole of the Principle including its +ic orientation — the Sphere expanding from every event, Huygens self-replication, the collision at the detection event — and supplies the physical mechanism of the rule: |ψ|² is the overlap at the detection event of the forward x₄-expansion with its conjugate (Theorem 7.4), the head-on collision rate of two physical Spheres (Theorem 7.7), and the product of the wavefunction with its PT_E-reflected value (Theorem 7.11). The dx₄/dt = ic Algebraic Channel is the T-invariant projection Π_A of the Geometric Channel (Theorem 16.3): it carries the Hilbert space, the sesquilinear pairing, the unitary group and the requirements (R1)–(R4), and supplies the uniqueness of the squared-modulus form, with the renormalized alternatives excluded by the finite rate c of the expansion (Theorem 7.6C). The projection Π_A exists and its inverse Π_B does not (Lemmas 16.3.1–16.3.2), which is why the Born rule has dual derivations as mathematics (Corollary 16.4) while every physical instantiation of it — every detector click — is a +ic-oriented Sphere collision in the Geometric Channel alone (Corollary 16.5, Theorem 16.7). Measurement is the physical Wick rotation that removes the perpendicularity marker i from the amplitude at the collision event (Theorem 12.2), and the thermodynamic limit is that rotation performed Γₜₒₜₐₗ times per second (Theorem 12.4). Against the prior programmes the McGucken derivation is simpler by count — one physical principle in place of the six independent postulates of Masanes–Galley–Müller or the eight commitments compressed into Neumaier's Detector Response Principle — more robust by convergent overdetermination, and more natural in that it answers the question Schrödinger put to Lorentz on 6 June 1926, what physical structure the complex amplitude refers to: the fourth dimension, perpendicular to x₁x₂x₃, expanding at c from every event with action h per Compton cycle.

Every theorem, lemma, definition and proof used here is reproduced verbatim and in full from the flagship corpus paper *Minkowski Space and Hilbert Space Derived and Unified via the McGucken Principle dx₄/dt = ic* [1], whose theorem, lemma, section and equation numbers are retained unchanged so that every cross-reference remains exact; section numbers cited inside reproduced blocks are the section numbers of [1].

## Part I. Introduction: the Born rule as the test case of the McGucken dx₄/dt = ic framework

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The Born rule is the natural test case for the Principle, for three reasons. It is the most-derived structure in the foundations of quantum mechanics, so the prior record against which a derivation is measured is complete and well documented (Vaidman 2020; Neumaier 2025). It is the one structure of quantum mechanics whose form — the square of a modulus — was reached by analogy rather than by any principle, so that "why the square?" has stood as an open question since the footnote of 1926. And it is the structure at which the two channels of the McGucken Duality meet most visibly: the exponent 2 is at once the rank of the Minkowski metric that x₄ = ict induces (the dx₄/dt = ic Algebraic Channel reading) and the number of physical McGucken Spheres that collide at a detection event (the dx₄/dt = ic Geometric Channel reading).

The paper has the following plan. Part II reproduces the geometric setup of the Principle on which every later theorem rests: Principle 2.1, the twin constants c and ħ (Proposition 2.2, §2.2.bis), the four-velocity budget and the four-fold ontology (§§2.3–2.4), the McGucken Sphere (Definition 2.3), space–operator cogeneration (Theorem 2.4), the Lorentzian signature of the constraint surface (Lemma 2.5), the wavefunction (Definition 2.6), and the complex character of amplitudes (Theorem 3.1). Part III defines the two McGucken channels in depth: the dual-channel architecture of the McGucken Quantum Formalism (§1.5), the channel projection Π_A as forgetful functor (§16.2), the position-of-i diagnosis and the decomposition +ic = (+)· i· c (§16.3), the Geometric Channel's self-sufficiency (Theorem 16.1), the Algebraic Channel's sign-blind independence (Theorem 16.2), the content asymmetry Π_A exists / Π_B does not (Lemmas 16.3.1–16.3.2, Theorem 16.3), dual derivation iff T-invariance (Corollary 16.4), mathematics versus physical instantiation (Corollary 16.5), the two positions relative to the wavefront (§9.5.13), and why the Algebraic Channel dominated the history of quantum mechanics while the Geometric Channel is primary (§6.6.5). Part IV gives the McGucken Principle dx₄/dt = ic reading of the century of Born-rule derivations, sixteen programmes with a diagnostic for each (§7.1), the sphere traditions that precede the McGucken Sphere (§7.7.1), and how Born himself arrived at the rule (§7.7.2). Part V derives the rule along the Algebraic Channel (§§7.2–7.6, Corollary 11.3). Part VI derives it along the Geometric Channel (§§7.8–7.11). Part VII reproduces the Born-rule chapter of the textbook *Quantum Mechanics Derived from the McGucken Principle* — theorem QM T11 — where the Algebraic Channel runs through the Cauchy functional equation on independent products and the Schrödinger continuity equation pins the exponent, and the Geometric Channel runs through the SO(3)-Haar measure on the McGucken Sphere with U(1)-invariant theory fixing the density. Part VIII establishes the convergence of the channels on the rule, the physical instantiation of the rule at every detector, measurement as physical Wick rotation, and the identification of gravity and the Born rule as two readings of one Haar measure (§7.12, §16.19, §§12.3–12.7, §10.12duodecies). Part IX states, item by item, what the McGucken derivation supplies that the prior programmes could not; Part X states the notable features of the derivation, each with its theorem; Part XI states what the derived rule asserts about the physical world; and Part XII concludes.

Throughout, the convention of the corpus is followed: the first mention of either channel in a section carries the leader form "the dx₄/dt = ic Algebraic Channel" and "the dx₄/dt = ic Geometric Channel", and later mentions in the same section read "the Algebraic Channel" and "the Geometric Channel". The two are the current names of what the earlier corpus papers labelled Channel A and Channel B respectively.

## Part II. The McGucken Principle dx₄/dt = ic and the geometric setup on which the Born rule rests

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

Every requirement entering the Born-rule uniqueness theorem (Theorem 7.2) and every geometric reading of the rule (Theorems 7.4, 7.7, 7.11) descends from the objects defined in this section: the Principle as an active expansion carrying wavelength, frequency, phase and action (Principle 2.1); the two dimensional parameters c and ħ of that one expansion (Proposition 2.2, with the Compton substrate-tick invariants of §2.2.bis fixing Δ S = h per cycle); the four-velocity budget v² + v_(x₄)² = c² and the four-fold ontology (§§2.3–2.4); the McGucken Sphere 𝓜_E(t) with its SO(3) isotropy (Definition 2.3); the cogeneration of the source space and the source operator D_M = ∂ₜ + ic ∂_(x₄) (Theorem 2.4); the Lorentzian signature (-,+,+,+) as the squared form of the Principle (Lemma 2.5); the wavefunction as the path-integral kernel of x₄-advance (Definition 2.6); and the complex character of amplitudes with i as the marker of x₄'s perpendicularity to x₁x₂x₃ (Theorem 3.1). The material of §§2.1–2.8 and §3 of [1] is reproduced verbatim and in full below.


### 2.1 Principle 2.1: the McGucken Principle dx₄/dt = ic as the active spherically symmetric expansion of x₄ at velocity c from every spacetime event

**Principle 2.1 (McGucken Principle).** *The fourth dimension is expanding from every spacetime event in a spherically symmetric manner, with each oscillatory step of the expansion carrying a quantized action. The velocity of x₄-advance defines c; the foundational wavelength of x₄-advance defines ℏ as the action per Planck-frequency oscillation:*

(dx₄)/(dt) = ic, action per oscillatory step of x₄ = ℏ.

The McGucken Principle dx₄/dt = ic states that the fourth dimension is expanding from every spacetime event as a *spherically symmetric wavefront at velocity c*. A wavefront that is expanding at c is a wavefront with **wavelength, frequency, phase, and therefore action** — it is a dynamical, oscillatory, phase-bearing geometric flow, not a static coordinate label. The two fundamental constants of quantum mechanics are not independent inputs entered into the formalism separately; they are **twin properties of the one advance**: c is the wavefront’s rate of advance, ℏ is the action carried per Planck-frequency oscillation of that advance. The constants are co-derived because the wavefront is one geometric object with two properties (Proposition 2.2). The spinor of relativistic quantum mechanics is not a free-floating algebraic object that we attach to a static spacetime as an external structure; **the spinor lives on a wavefront that already has the Compton frequency** ν_C = m c²/h built into the fundamental structure, read off the McGucken Principle directly (the wavefront’s wavelength sets h; §9.2 step 1). And the dynamics of quantum mechanics — the Schrödinger equation, the canonical commutator, the unitary time evolution, the wave function’s oscillatory phase, the path-integral kernel exp(iS/ℏ), the spin precession at the Larmor frequency — was therefore not added to a static geometric background by external axiomatic stipulation; **the dynamics were in the premise**. Every dynamical structure of QM is the cascade-level expression of the wavefront-character of the active x₄-expansion that the McGucken Principle names. The wavefront’s wavelength supplies de Broglie’s relation (Proposition 10.8 (iii)); its frequency supplies the Compton frequency at every massive particle (above); its phase supplies the Feynman path-integral exponent exp(iS/ℏ) (Theorem 12.11 instance (9)); its action quantum ℏ supplies the universal non-closure quantum across the canonical commutator, the uncertainty bound, the Berry phase, the spin-1/2 4π closure, the Bohr–Sommerfeld–Maslov, the Aharonov–Bohm, the Dirac monopole quantization, the Wigner rotation, and the path-integral interference (Theorem 12.11). All of quantum mechanics is the cascade-level reading of one geometric fact: x₄ is expanding from every event as a spherically symmetric wavefront, and that wavefront’s intrinsic kinematic and action is the premise from which the entire formalism cascades. **The dynamics were in the premise.**

The principle is a *two-constant* statement about a single geometric flow. The constants c and ℏ are not independent dimensional inputs separately measured and inserted into the formalism; they are co-constitutive properties of the same x₄-expansion. c is its rate; ℏ is its action quantum per Planck-frequency oscillation. The standard pedagogical separation of c (relativity’s constant) from ℏ (quantum mechanics’ constant) is overcome at the foundational-derivation level by the recognition that both are properties of x₄’s active advance — twin properties of the one wavefront.

Two features of this statement are essential. First, x₄ is treated as a physical, dynamical geometric direction — the imaginary unit i in dx₄/dt = ic is the algebraic marker for x₄’s perpendicularity to the three spatial dimensions x₁, x₂, x₃. Second, the action quantization is intrinsic to the expansion: x₄ advances *in quantized steps of action ℏ* at the Planck frequency. The wavelength of these steps is the Planck length λ_P = √(ℏG/c³); the frequency is the Planck frequency f_P = c/λ_P; the period is the Planck time t_P = 1/f_P; the action per cycle is ℏ. All four Planck scales are pinned by the McGucken Principle’s two constants c and ℏ together with Newton’s constant G as a third dimensional input from gravitational physics: G is enters at the Schwarzschild self-consistency r_S = λ at the substrate scale (see [2, §16.5] for the full three-input dimensional analysis separating c from dx₄/dt, ℏ from per-tick action, and G from gravitational coupling). The Planck length, period, and frequency are the characteristic scales at which c, ℏ, and G combine; the action per cycle ℏ is pinned by the McGucken Principle alone: the wavelength of the x₄-advance sets the action h (Proposition 2.2).

Integration of the velocity component of the McGucken Principle with respect to coordinate time t, anchored at x₄ = 0 when t = 0, yields the coordinate relation

x₄ = ict.

Every appearance of x₄ = ict throughout this paper is the integrated form of the McGucken Principle dx₄/dt = ic, obtained by integration with respect to coordinate time t anchored at x₄ = 0 when t = 0. The differential statement dx₄/dt = ic is the physics; x₄ = ict is its integrated coordinate expression. Wherever x₄ = ict appears below — in derivations, in proofs, in references to the imaginary character of the fourth dimension, or in references to the Lorentzian signature (ict)² = −c²t² — it descends from dx₄/dt = ic by this integration.

This is the relation that has been in physics since Minkowski’s 1908 lecture; what was unrecognized for a century was the dynamics underneath it — the *rate* at which x₄ is changing, and the *action quantization* of that rate — together with the physics that follows from naming both. The relationship between x₄ = ict and dx₄/dt = ic is parallel to that between x(t) = (1/2)at² and F = ma: the dynamical law is the physics, the integrated trajectory is its coordinate expression.

### 2.2 The two dimensional parameters of the McGucken Principle’s expansion: c as its rate, ℏ as its action per Planck-frequency oscillation — both properties of one geometric flow

**Proposition 2.2 (The two dimensional parameters of the x₄-expansion).** *The McGucken Principle dx₄/dt = ic has two natural dimensional parameters, and both fundamental constants of quantum mechanics — c and ℏ — are wired into the framework as these two parameters of the one expansion. (i) c is the rate of the expansion: |dx₄/dt| = c, read directly off the Principle as the invariant speed at which x₄ advances from every event. (ii) ℏ is the action carried per Planck-frequency oscillation of that expansion: the expansion is a wavefront whose wavelength sets the action, ΔS_per osc = ℏ, each oscillatory cycle of x₄-advance carrying one quantum of action, so the action scale is read off the expansion itself. Neither c nor ℏ is computed from a deeper principle — both are set by the physical world, as every foundational programme in physics ultimately requires some dimensional inputs — but they are not two independent constants of two independent theories. They are the two natural properties of one geometric flow: the rate and the action-per-oscillation of the same x₄-expansion. This is the framework’s unification of c and ℏ: instead of c appearing once as an independent constant of Minkowski geometry and ℏ appearing separately as an independent constant of quantum mechanics (the orthodox picture in which the two theories share no ontological connection), both appear once, as the two natural dimensional parameters of the one dynamical object that the Principle names.*

*The rate.* The Principle dx₄/dt = ic contains c on its right-hand side as the rate parameter of x₄-advance. Reading the modulus |dx₄/dt| = c off the Principle recovers c not as a derived numerical value (the Principle is written with c in it and reading it back gives c back — this is a definitional restatement, not a derivation) but as the *single geometric role c plays in the framework*: the rate of x₄-expansion. That the c of the Lorentzian metric ds² = -c²dt² + dx² is the same c is the content of Lemma 2.5, which shows that squaring the Principle’s rate gives (ic)² = -c² and hence the Lorentzian signature. So c enters the framework once, as the rate of x₄-advance, and every subsequent appearance of c (in the Lorentz factor, in the null cone, in E = mc², in relativistic dispersion) traces back to that single geometric role.

*The action-per-oscillation.* The Principle dx₄/dt = ic is the advance of a wavefront, and a wavefront has a wavelength; that wavelength sets the action h carried per Planck-frequency oscillation of the x₄-expansion, read off the Principle exactly as the rate c is read off its right-hand side. The action is content of the Principle, written ΔS_per osc = ℏ — the *action-quantization clause* of dx₄/dt = ic, on the same footing as the rate clause |dx₄/dt| = c. The quantum of action here plays the role Planck’s 1900 quantum of action played in the original quantum hypothesis — a quantum of action fixing the scale — with the physical quantum carried by the expansion the Principle names rather than posited beside it. Every subsequent appearance of ℏ in the derived theorems (the path-integral phase exp(iS/ℏ), the canonical commutator [q̂, p̂] = iℏ, the uncertainty bound σ_x σ_p ≥ ℏ/2, the Schrödinger generator iℏ ∂_t, the Planck constants λ_P, t_P, E_P, m_P) traces back to the action-per-oscillation of the same x₄-expansion whose rate is c.

*The unification.* c and ℏ are the two dimensional parameters of the same geometric flow: not two constants of two theories, but two properties of one object. The corpus paper [ref. 30 of [1]] is explicit about this two-parameter structure (see also [2, §16.5], which separates the dimensional inputs as c from dx₄/dt, ℏ from per-tick action, and G from Schwarzschild self-consistency r_S = λ at the substrate scale; general relativity’s constant G enters at §6.6.9 through the Schwarzschild self-consistency, and the QM-derivation cascade of §§3–9 uses only c and ℏ). The framework’s parsimony is not that it derives c and ℏ from nothing — no framework does — but that it locates both in the same physical object (the x₄-expansion), rather than as independent constants of the two separate arenas that orthodox physics kept in different theories. Every appearance of the combination iℏ — which shows up in nearly every foundational equation of quantum mechanics — is the conjunction of both properties of the x₄-expansion: the i from the perpendicular-dimensional character of x₄ (Theorem 3.1), the ℏ from the action-per-oscillation of x₄-advance, both wired into the framework as properties of the one expansion.

### 2.2.bis The substrate-tick invariants of dx₄/dt = ic: Δ t_C = 2πħ/(mc²), Δ x₄ = iλ_C, Δ S = h, and the Lorentz-invariance of ħ as the Lorentz-invariance of c expressed at the Compton substrate-tick scale

Section 2.2 established c and ħ as twin dimensional parameters of the McGucken Principle dx₄/dt = ic: c is the rate of x₄-advance perpendicular to the spatial slice, ħ is the action carried per Planck-frequency oscillation of that advance. The twin-parameter framing leaves one fact implicit: at what scale does ħ enter as an invariant, and how is the invariance of ħ related to the invariance of c? This subsection makes both explicit with exact identifications at the Compton substrate-tick scale of the wavefront expansion.

**Definition 2.2.bis.1 (Compton substrate tick).** *At every event p ∈ Minkowski Space 𝕄_(1,3) and every massive particle of rest mass m at p, the Compton substrate tick is the period Δ t_C = 2π/ω_C where ω_C = mc²/ħ is the Compton angular frequency of the particle. Explicitly,*

Δ t_C = 2πħ/mc².


**Proposition 2.2.bis.1 (Three exact substrate-tick identifications).** *During one Compton substrate tick of a massive particle of rest mass m at event p ∈ Minkowski Space 𝕄_(1,3), the following three quantities are given exactly:*

*(i) The fourth-dimensional advance:*

Δ x₄ = ic · Δ t_C = iλ_C, where λ_C = h/mc is the Compton wavelength.


*(ii) The action accumulation:*

Δ S = E · Δ t_C = mc² · 2πħ/mc² = 2πħ = h.


*(iii) The oscillation phase advance:*

ω_C · Δ t_C = mc²/ħ · 2πħ/mc² = 2π (one full cycle).


*Proof.* Direct calculation from Definition 2.2.bis.1:

*(i)* Δ x₄ = ic · Δ t_C = ic · 2πħ/mc² = (2π iħ)/mc = i · h/mc = iλ_C.

*(ii)* Δ S = E · Δ t_C = mc² · 2πħ/mc²; the mc² factors cancel exactly, leaving Δ S = 2πħ = h.

*(iii)* ω_C · Δ t_C = mc²/ħ · 2πħ/mc²; the mc² and ħ factors cancel exactly, leaving ω_C · Δ t_C = 2π. ∎

**Corollary 2.2.bis.1 (Mass-independence of the substrate-tick action).** *The substrate-tick action Δ S = h is independent of the particle’s rest mass m. Every massive particle at every event of Minkowski Space 𝕄_(1,3) accumulates exactly one Planck constant per Compton substrate tick, regardless of m.*

*Proof.* From Proposition 2.2.bis.1(ii), Δ S = mc² · 2πħ/(mc²) = 2πħ = h. The mass m appears in both the rest-energy E = mc² (numerator of the product) and in the reciprocal of the Compton frequency 1/ω_C = ħ/(mc²) (denominator, via Δ t_C = 2π/ω_C), and cancels exactly in the product. The cancellation is exact — not approximate, not up to numerical factors of order unity, not up to logarithms — the two mc² factors are algebraically identical and cancel to give Δ S = h independent of m. ∎

**Theorem 2.2.bis.1 (Lorentz-invariance of ħ as Lorentz-invariance of c at the substrate scale).** *The Lorentz-invariance of Planck’s constant ħ across all inertial frames and all massive quantum systems is the same physical fact as the Lorentz-invariance of the speed of light c across all inertial frames, expressed at the Compton substrate-tick scale of the dx₄/dt = ic wavefront expansion. Explicitly: ħ is Lorentz-invariant at every event p ∈ Minkowski Space 𝕄_(1,3) because (a) the speed of light c is Lorentz-invariant by Theorem 2.4.5 clause (P2) (Einstein’s second postulate of special relativity, derived here as a theorem of dx₄/dt = ic); (b) the rest mass m is Lorentz-invariant by definition of the rest frame; (c) the substrate-tick action factors as Δ S = mc² · 2πħ/(mc²) = 2πħ, in which the mass-dependent factor mc² cancels exactly; and (d) the substrate-tick action Δ S is a geometric invariant of the dx₄/dt = ic wavefront expansion at every event of Minkowski Space 𝕄_(1,3) — one full cycle of the wavefront’s Compton oscillation is an intrinsic property of the wavefront geometry, independent of the choice of inertial frame from which the tick is observed.*

*Proof.* By Corollary 2.2.bis.1, Δ S = h at every event of Minkowski Space 𝕄_(1,3) for every massive particle, and this identity is mass-independent. The identity Δ S = h was derived from Definition 2.2.bis.1 via elementary algebra and does not presume the Lorentz-invariance of ħ as an independent axiom — the mass cancellation follows from the algebraic identity mc² · (mc²)⁻¹ = 1, not from any assumption about how ħ transforms under boosts. Under a Lorentz boost with rapidity ξ applied to the rest frame of the particle, the rest energy E = mc² and the Compton period Δ t_C = 2πħ/(mc²) transform in ways that involve c (Lorentz-invariant by Theorem 2.4.5(P2)) and m (Lorentz-invariant by rest-frame definition); the ratio E · Δ t_C = mc² · 2πħ/(mc²) = 2πħ contains no residual ξ-dependence, so ħ transforms as an invariant. The invariance of ħ under Lorentz boosts is therefore forced by the invariance of c under Lorentz boosts, given the substrate-tick identity of Proposition 2.2.bis.1(ii). ∎

**Corollary 2.2.bis.2 (Historical dissolution of the c-versus-ħ invariance question).** *The twentieth-century puzzle of why quantum mechanics and special relativity each carry an independent Lorentz-invariant constant of nature — c for special relativity (Einstein 1905), ħ for quantum mechanics (Planck 1900, Bohr 1913) — dissolves under Theorem 2.2.bis.1: these are not two independent empirical facts about the universe requiring independent laboratory confirmation, but one geometric invariance expressed at two scales: c at the classical light-propagation scale (macroscopic wave propagation of the dx₄/dt = ic wavefront), and h at the Compton substrate-tick scale (per-cycle action accumulation of the dx₄/dt = ic wavefront). The twin dimensional parameter framing of §2.2 is therefore not two parallel invariant constants but one geometric invariance factored between the substrate-tick and classical-propagation scales.*

*Remark 2.2.bis.1.* The exact character of the mass cancellation in Corollary 2.2.bis.1 raises the stakes of the framework’s foundational claim in exactly the direction that a foundational unification should raise them. If the McGucken dx₄/dt = ic framework were incorrect at this point, the numerical identity of the substrate-tick action with Planck’s constant h would be a coincidence at the level of ħ, c, m, and 2π simultaneously — a coincidence of four independent quantities. This is a specific falsifiable prediction, not a philosophical gesture: any experimentally observed deviation of ħ from Lorentz-invariance in any inertial frame would falsify Theorem 2.2.bis.1, and thereby falsify the identification of ħ as the substrate-tick action of dx₄/dt = ic. No such deviation has been observed across seventy years of precision quantum-electrodynamic measurement (electron g-2 measurement to twelve significant digits, hydrogen Lamb shift, Compton scattering cross-sections, atomic clock frequency stability across gravitationally-boosted platforms). Seventy years of null results at the seventh-through-twelfth-significant-digit level is precisely the seventy-year empirical anchor for the identification.

*Remark 2.2.bis.2.* The three substrate-tick identifications of Proposition 2.2.bis.1 also give a substrate-scale reading of de Broglie’s 1924 phase-wave hypothesis. De Broglie postulated that every massive particle carries a phase wave with frequency ν = mc²/h and wavelength λ = h/(mc); these are exactly ν = ω_C/(2π) and λ = λ_C. What de Broglie discovered empirically in 1924 — through analogy with the electromagnetic wave and the observation that phase and group velocities of the matter wave must give the particle’s mechanical velocity — is the substrate-tick invariants of dx₄/dt = ic at the particle’s event. De Broglie had the invariants but not the geometric substrate; the McGucken dx₄/dt = ic framework supplies the substrate as the wavefront expansion of dx₄/dt = ic at every event, of which the de Broglie invariants are the per-substrate-tick expressions.

*Remark 2.2.bis.3.* The Compton substrate-tick invariants also make visible the substrate-scale reading of Planck’s constant in every appearance in the Algebraic Channel of quantum mechanics: the canonical commutator [q̂, p̂] = iħ, the Schrödinger equation iħ ∂ₜ ψ = Ĥ ψ, the unitary group U(t) = e^(-iĤ t/ħ), the Bohr-Sommerfeld quantization condition ∮ p dq = n h, the Feynman path-integral exponent e^(iS/ħ), the uncertainty bound Δ x Δ p ≥ ħ/2. Every appearance of ħ (equivalently, h = 2πħ) in the Algebraic Channel is the substrate-tick action of dx₄/dt = ic entering as an unexplained empirical constant in the algebra. The algebra does not know that ħ is a geometric substrate-tick invariant; it treats ħ as an empirical parameter that must be supplied from measurement. The McGucken dx₄/dt = ic framework identifies ħ as a geometric quantity of the fourth-dimensional wavefront expansion at the substrate-tick scale.

*Remark 2.2.bis.4.* The identification Δ S = h per Compton substrate tick, mass-independent, generalizes to the Bohr-Sommerfeld semiclassical quantization condition ∮ p dq = n h for periodic orbits: an orbit closes after n Compton substrate ticks contribute total action Δ S_( total) = n h. Bohr-Sommerfeld quantization is the substrate-tick counting statement — integer numbers of substrate-tick actions per closed classical orbit, made visible in the semiclassical limit. The full rigorous development of this correspondence, together with the differential-response diagnostic connecting Algebraic and dx₄/dt = ic Geometric Channels via the Wick rotation, is given in the corpus paper [3], §IX.30.C.12.

### 2.3 The four-velocity budget u^μ u_μ = -c² as a consequence of dx₄/dt = ic

The McGucken Principle dx₄/dt = ic holds at every event; its magnitude-only shadow is the unit four-velocity norm u^μ u_μ = −c² (Lemma 2.5), which partitions the four-velocity *budget* between motion in the spatial directions x₁x₂x₃ and advance along x₄:

v²_spatial + v²_{x₄} = c².

This budget constraint, combined with the McGucken Principle, generates the four-fold ontology.

### 2.4 The four-fold ontology of dx₄/dt = ic: (1) massive particle at spatial rest with full budget into x₄, (2) photon at v=c with vanishing share v_(x₄)=0 on null worldline riding the wavefront, (3) absolute x₄-expansion at ic from every event, (4) CMB frame as isotropic cosmological x₄-expansion

The McGucken dx₄/dt = ic framework specifies four canonical configurations of the four-velocity budget:

1. **Absolute rest in x₁x₂x₃**: v_spatial = 0, v_x₄ = c (and |dx₄/dt| = c). Full budget allocated to x₄-advance. This is a massive particle at spatial rest.

2. **Absolute rest in x₄**: v_x₄ = 0, v_spatial = c. The photon: its Sphere-tangent share v_(x₄) = 0 along its null worldline (Principle dx₄/dt = ic still holding). It rides the wavefront and does not advance in x₄. *Photons are at absolute rest in x₄.*

3. **Absolute motion**: the cosmological x₄-expansion at rate ic from every event, independent of any single worldline. This is the universal geometric expansion that the McGucken Principle asserts.

4. **The CMB frame**: the frame in which the cosmological x₄-expansion is isotropic, identified physically with the rest frame of the cosmic microwave background.

The four-fold ontology is canonical throughout the derivations below. Items (1) and (3) carry the construction of Minkowski Space 𝕄_(1,3) and the wavefunction; item (2) gives the clean photon ontology that makes the Born rule’s geometric interpretation transparent.

### 2.5 Definition 2.3: the McGucken Sphere 𝓜_E(t) as the spherically symmetric expanding wavefront of radius c·t generated by dx₄/dt = ic at every event E

The geometric object at the heart of the dx₄/dt = ic framework is the McGucken Sphere: the wavefront of x₄-expansion emanating from each event. The McGucken Sphere makes Principle 2.1 geometrically explicit at every spacetime event: the active spherically symmetric expansion of x₄ at velocity c is the McGucken Sphere; the wavelength, frequency, phase, and action of the wavefront are its intrinsic kinematics; the dynamics of every later derivation are present in this wavefront geometry.

**Definition 2.3 (McGucken Sphere).** *Let E be a spacetime event and t the coordinate (parameter) time elapsed since E. The* McGucken Sphere *centered at E at parameter t is the set*

𝓜_E(t) = { p ∈ spacetime : ds²(E, p) = 0, x₄(p) − x₄(E) = ict }.

Equivalently, 𝓜_E(t) is the null wavefront of the x₄-expansion from E.

The McGucken Sphere is invariant under the rotation group SO(3) acting on x₁x₂x₃ by spatial rotations about E. This symmetry is the geometry of the McGucken Principle’s spherical symmetry: the x₄-expansion is isotropic in 3-space.

### 2.6 Theorem 2.4: space-operator cogeneration — the McGucken Principle simultaneously generates the source-space 𝓜_G (geometric setup) and the McGucken operator 𝓕_p = ∂_t + ic·∂_{x₄}|_p (dynamics)

The architectural foundation of the McGucken framework is that dx₄/dt = ic is *simultaneously* a statement about a coordinate (x₄ expanding at rate ic) and a statement about an operator (D_M = ∂_t + ic ∂_x₄, the differential expression of the same statement). Asserting the McGucken Principle asserts both.

**Theorem 2.4 (Space-Operator Cogeneration).** *The McGucken Principle dx₄/dt = ic generates simultaneously the source-space*

𝓜_G = (E₄, Φ_M, D_M, Σ_M)

*and the source operator D_M from the same primitive law. Specifically, dx₄/dt = ic asserts*

(i) *the ambient four-dimensional space E₄ in which x₄ is a coordinate;*

(ii) *the constraint Φ_M = x₄ - ict whose vanishing locus is the physical sector;*

(iii) *the source operator D_M = ∂_t + ic ∂_x₄, the differential expression of the McGucken Principle;*

(iv) *the McGucken measure Σ_M on the constraint surface, inherited from the Lebesgue measure on x₁x₂x₃ and the proper-time measure on t-slices.*

*All four components of 𝓜_G descend from the single principle.*

*Proof.* The proof separates into two parts: **constructive existence** (parts (i)–(iv) of the statement, derived directly from dx₄/dt = ic within the present paper), and **uniqueness** (the cogeneration claim that 𝓜_G is the unique four-tuple forced by the Principle, depending on the Reciprocal Generation and Containment-Generation theorems of the McGucken Category McG paper [4] and the Reciprocal-Generation / Huygens-Principle paper [5], not derived in-session in the present paper).

The McGucken Principle dx₄/dt = ic involves the coordinates t and x₄ as independent variables; these are coordinates on the ambient carrier E₄ := ℝ³ × ℂ (with the ℂ-component carrying x₄ as an algebraic-perpendicularity-marked coordinate per Theorem 4.6.1; equivalently E₄ is the real four-manifold ℝ⁴ with the fourth axis algebraically marked by i). Part (i) is therefore the natural setting for the Principle. The integrated form x₄ = ict is established by direct integration of dx₄/dt = ic from the source-event convention x₄(t_E) = 0 (Lemma 2.5 of §2.7 below):


x₄(t) = x₄(t_E) + ∫_(t_E)ᵗ ic dt' = ic(t - t_E),


and after fixing the origin via t_E = 0 this is x₄ = ict. The constraint function Φ_M(t, x₄) := x₄ - ict has vanishing locus Φ_M⁻¹(0) = 𝒞_M — the physical sector where the integrated McGucken Principle holds. Part (ii) is established by direct construction.

For part (iii) (the source operator D_M = ∂ₜ + ic ∂_(x₄)), the chain-rule total-derivative identity along any smooth curve γ(t) = (t, x₄(t)) satisfying dx₄/dt = ic gives, for any differentiable function Ψ(t, x₄),


d/dtbigg|_γ Ψ(t, x₄(t)) = (∂ Ψ)/(∂ t) + dx₄/dt · (∂ Ψ)/(∂ x₄) = (∂ Ψ)/(∂ t) + ic · (∂ Ψ)/(∂ x₄) = D_M Ψ.


This is the **Generator Equivalence**: the McGucken Principle as a curve-condition dx₄/dt = ic and the McGucken Operator D_M as a differential operator are two presentations of the same content — the curve-condition gives the integral curves of D_M, and D_M acting on functions yields the chain-rule total derivative along those curves. The argument runs by direct computation and requires nothing beyond standard multivariable calculus.

The tangency of D_M to 𝒞_M is direct: D_M Φ_M = ∂ₜ (x₄ - ict) + ic ∂_(x₄)(x₄ - ict) = -ic + ic · 1 = 0. Hence D_M is tangent to the constraint surface everywhere on 𝒞_M.

The characteristic-invariance property — that functions Ψ satisfying D_M Ψ = 0 depend on (t, x₄) only through the first integral u := x₄ - ict — is a standard fact of first-order linear PDE theory: D_M is a first-order linear operator with constant coefficients on ℝ² × ℂ, and its kernel consists exactly of functions of the conserved quantity along characteristics, which here is u = x₄ - ict (the characteristic curves are precisely the curves x₄ - ict = const). The proof is by direct verification: writing Ψ(t, x₄) = F(u) for some differentiable F, we have D_M F(u) = F'(u) · D_M u = F'(u) · (∂ₜ u + ic ∂_(x₄) u) = F'(u) · (-ic + ic) = 0. Conversely, on simply-connected regions, any kernel element is expressible as F(u) for some F by method of characteristics. Part (iii) of the statement is therefore established by direct computation.

For part (iv) (the McGucken measure Σ_M), the wavefront-assignment Σ_M: p ↦ Σ⁺(p) assigning to every event p its McGucken Sphere is forced by the McGucken Principle’s universality clause (the Principle holds at every event of 𝓜_G with the same content, generating from each event the spherically symmetric wavefront at rate c) combined with Definition 2.3 of §2.5. The measure on 𝒞_M — denoted Σ_M as the fourth component of the source-space tuple — decomposes on each t-slice as the standard Lebesgue measure d³ x on ℝ³ paired with the proper-time measure on t; this decomposition is standard product-measure construction on the Lorentzian spacetime Minkowski Space 𝕄_(1,3) that 𝒞_M becomes under Lemma 2.5. Part (iv) is therefore established by direct computation.

The constructive existence of parts (i)–(iv) is established by direct computation from dx₄/dt = ic alone, using only standard multivariable calculus, first-order linear PDE theory, and standard product-measure construction.

The uniqueness claim — that the four-tuple 𝓜_G = (E₄, Φ_M, D_M, Σ_M) is the *unique* four-tuple cogenerated by the McGucken Principle, up to overall scaling and orientation — is the content of the **Reciprocal Generation Theorem** developed in the McGucken Category paper [4] (as one of the three theorems on the source-pair (𝓜_G, D_M): Mutual Containment, Reciprocal Generation, Containment-Generation Equivalence) and further developed with its Huygens-Principle in [5]. The full statement establishes that every point p ∈ 𝓜_G generates the pointwise McGucken Operator D_M⁽ᵖ⁾ (the **Pointwise Generator Theorem** of [5, 4]), and the family (D_M⁽ᵖ⁾)_(p ∈ 𝓜_G) reciprocally reconstructs 𝓜_G (the **Operator-to-Space Theorem** of [5, 4]). The scaling and orientation uniqueness is the content of the scaling/orientation lemmas of the McGucken Category corpus [4]. The **Huygens-Principle identification** [5] supplies the geometric interpretation of the cogenerated structure as the Huygens wavefront propagation on 𝒞_M — with the identification of Huygens’ Principle as the physical mechanism of the reciprocal-generation content of the space-operator pair (operators generate spaces of generative operators in mathematics; points generate spherical wavefronts of generative points in physics).

The cogeneration claim of Theorem 2.4 is therefore **not** independently verified within the present paper: the Reciprocal Generation Theorem, the Pointwise Generator Theorem, the Operator-to-Space Theorem, the scaling/orientation lemmas, and the Huygens-Principle identification all reside in the McGucken Category corpus papers [5] and [4] and are imported here by reference. Within the present paper, the constructive existence of parts (i)–(iv) is established as above; the uniqueness is taken from [5, 4] without in-session proof. ∎

**Scope Statement.** *The constructive existence of parts (i)–(iv) — that E₄, Φ_M, D_M, and Σ_M each follow from dx₄/dt = ic — is derived above by direct computation from the McGucken Principle alone, using only standard multivariable calculus, first-order linear PDE theory, and standard product-measure construction. The uniqueness clause of the cogeneration — that the four-tuple is the unique structure cogenerated by the McGucken Principle, with the Reciprocal Generation Theorem as its formal statement in the McGucken Category paper [4] and in the Reciprocal-Generation / Huygens-Principle paper [5], together with the Pointwise Generator Theorem and the Operator-to-Space Theorem of [5, 4], the scaling/orientation lemmas of [4], and the Huygens-Principle identification of [5] — is imported from [5, 4]; the in-session verification of the existence-construction is complete; the in-session verification of the uniqueness depends on results in [5, 4] not in the present-paper session and is therefore not independently verified within the present paper. The downstream uses of Theorem 2.4 elsewhere in the present paper (Theorems 6.1, 6.1.5, 10.5, 10.6; Lemma 6.1.6; the cogeneration cascade architecture of §10) rely on the existence content of Theorem 2.4, which is derived here; the uniqueness content is referenced where convergent overdetermination is being argued but is not for the QM-derivation cascade of §§5–9, all of which can run on the existence content alone.*

The significance of cogeneration is that the space and the operator come from one statement, not from two independent inputs. This is what distinguishes the McGucken dx₄/dt = ic framework from every prior program: prior programs separated the questions “what is the arena?” and “what acts on the arena?” and tried to characterize each independently. The full Reciprocal Generation development — including the uniqueness lemmas, the Huygens-Principle identification of [5], the three theorems on the source-pair (𝓜_G, D_M) — Mutual Containment, Reciprocal Generation, Containment-Generation Equivalence — of the McGucken Category paper [4], and the cross-generation propositions — is in [5, 4]; the present paper uses Theorem 2.4 as the architectural foundation on which the subsequent derivations rest.

### 2.7 Lemma 2.5: the constraint surface Φ_M⁻¹(0) ⊂ 𝔼₄ with Φ_M = x₄ - ict equipped with the Euclidean metric is the Lorentzian Minkowski spacetime 𝕄₁,₃ with signature (-,+,+,+)

The vanishing locus of Φ_M defines the physical sector of 𝓜_G:

**Lemma 2.5 (Lorentzian signature on the constraint surface).** *The constraint surface Φ_M⁻¹(0) ⊂ E₄, equipped with the metric induced from the four-dimensional Euclidean line element ds² = dx₁² + dx₂² + dx₃² + dx₄², is the Lorentzian spacetime Minkowski Space 𝕄_(1,3) with signature (−,+,+,+).*

*Proof.* On the constraint surface, x₄ = ict, so dx₄ = ic dt and dx₄² = (ic)² dt² = −c² dt². Substitution into the four-dimensional Euclidean line element yields

dℓ² = dx₁² + dx₂² + dx₃² + dx₄² = dx₁² + dx₂² + dx₃² − c² dt²,

which is the Minkowski metric with signature (−,+,+,+). ∎

The Lorentzian signature is the algebraic shadow of (ict)² = −c² t². It is a forced consequence of the integration of dx₄/dt = ic.

### 2.8 Definition 2.6: the McGucken wavefunction ψ : ℝ³ × ℝ → ℂ constructed as the projection of x₄-advance onto the spatial slice, with the complex-valued character forced by Frobenius given a single perpendicular axis

**Definition 2.6 (McGucken wavefunction).** *Let 𝓜_G = (E₄, Φ_M, D_M, Σ_M) be the McGucken Space of Theorem 2.4, with D_M-solutions Ψ : E₄ × ℝ → ℂ : D_M Ψ = 0 (the characteristic-invariant functions of Theorem 17 of [ref. 30 of [1]], which depend on the integrated coordinate u = x₄ - ict together with the spatial coordinates x ∈ ℝ³). For an event E ∈ 𝒞_M and a system whose x₄-advance from E propagates as a D_M-solution Ψ, the* **McGucken wavefunction** *of the system, evaluated at spatial point x ∈ ℝ³ and parameter time t, is the ℂ-valued field*

ψ(x, t) := ∑_γ : E → (x, t) exp ((i S[γ])/(ℏ)),

*where the sum is over all paths γ from E to the spacetime point (x, t) — with (x, t) understood to lie on the null wavefront 𝓜_E(t_*) of the x₄-expansion from E for the appropriate parameter time t_* — S[γ] is the action along γ, and ℏ is the action-quantization scale of Proposition 2.2. The phase factor i in the exponent is inherited from the imaginary character of x₄ = ict (Theorem 3.1).*

*Equivalently, ψ is the restriction to the spatial slice ℝ³ × {t} of the path-integral kernel from E generated by the McGucken-Sphere propagation Σ⁺(E) of Definition 2.3; the path-integral content is established as Theorem 3.1 below.*

This is the move that distinguishes the entire McGucken construction from the prior tradition: ψ is a derived projection of a real geometric flow. Hilbert space, when it is constructed in §6, will be the L² completion of the space of such projections — but the projections come first, and the Hilbert space arises as their natural completion.

### 3. The complex character of amplitudes: Theorem 3.1 — the McGucken wavefunction ψ is intrinsically complex-valued, with phase generated by the factor i appearing in the integrated form x₄ = ict descended from dx₄/dt = ic

The first forced theorem of dx₄/dt = ic is the complex character of the wavefunction. This is the substrate on which every subsequent derivation rests.

**Theorem 3.1 (Complex amplitudes from dx₄/dt = ic).** *Let ψ be the McGucken wavefunction of Definition 2.6 constructed under the McGucken Principle dx₄/dt = ic. Then ψ is intrinsically complex-valued, with phase generated by the factor i that appears in the integrated form x₄ = ict (descended from dx₄/dt = ic by integration).*

*Proof.* The proof has two parts. **Part 1 (Kinematic).** The McGucken Principle dx₄/dt = ic integrates to x₄ = ict (Lemma 5 of [ref. 30 of [1]]; integration anchored at x₄ = 0 when t = 0). The factor i in the integrated form is the algebraic signature of the geometric fact that x₄ is perpendicular to the spatial three-axes x₁x₂x₃: multiplication by i is the canonical representation of a quarter-rotation in the complex plane, and it encodes here the orthogonality of the fourth axis to ordinary space. The Minkowski signature of the constraint surface is the algebraic shadow of this perpendicularity, (ict)² = −c² t² (Lemma 2.5), and the minus sign in ds² = dx₁² + dx₂² + dx₃² - c² dt² records orthogonality, not unreality.

Consider an event E from which the McGucken expansion proceeds. A spatial point x ∈ ℝ³ at parameter time t = |x|/c lies on the McGucken Sphere 𝓜_E(t). The four-displacement from E to this point has spatial component x (magnitude ct) and x₄-component Δ x₄ = ict. The four-displacement vector is

Δ X = (x, ict), ‖Δ X‖² = |x|² + (ict)² = c² t² - c² t² = 0,

confirming the null character of the McGucken Sphere. *The x₄-component of every displacement to a point on the wavefront is purely imaginary.* This is the kinematic fact from which the complex character of ψ descends: any spatial-slice projection σ: ℝ³ → 𝓜_E(t) of an x₄-propagating excitation must record both the in-slice content (real part) and the perpendicular-to-slice content (imaginary part). The wavefunction ψ(x, t) is therefore a ℂ-valued field with a real and an imaginary part forced by the kinematic structure of the McGucken Sphere. The selection of ℂ specifically — rather than ℝ² as an unstructured direct sum, or ℍ as the next associative real division algebra — is forced by the Frobenius theorem on associative real division algebras (1877): one perpendicular axis x₄ yields exactly one independent imaginary unit i, uniquely selecting ℂ from the Frobenius candidates {ℝ, ℂ, ℍ} (zero / one / three perpendicular axes). The Frobenius selection is developed in §4.1 (the algebra of perpendicularity) and applied formally in the construction of Theorem 6.1 (Hilbert space).

The kinematic complex character of Part 1 establishes that ψ takes values in ℂ but does not yet determine the *form* of the phase. The dynamics comes from the action-quantization clause of the Principle (Proposition 2.2, clause ii): the x₄-advance carries one quantum of action ℏ per Planck-frequency oscillation, its wavelength setting h. We translate this into the phase carried by an arbitrary path from E to a point on the null wavefront 𝓜_E(t).

Let γ be a path from E to B, where B ∈ 𝓜_E(t) lies on the null wavefront of the x₄-expansion from E (the McGucken Sphere of Definition 2.3), with proper time Δ τ_γ elapsed along γ. By Proposition 2.3 of [2] (proper time as x₄-arc-length), the accumulated x₄-displacement along γ has modulus |Δ x₄|_γ = c Δ τ_γ. The action carried by the propagating excitation along γ is, in the standard relativistic form,

S[γ] = -mc² Δ τ_γ

for a massive excitation of mass m (or the analogous Planck-quantum expression for a photon; the absolute magnitude |S[γ]| enters the phase). Because the x₄-advance carries one quantum of action ℏ per oscillation, each unit of action ℏ corresponds to one *radian* of phase rotation in the complex plane spanned by (real spatial component, imaginary x₄-component); a full 2π rotation of phase corresponds to action h = 2πℏ, the standard relation between the reduced Planck constant ℏ and Planck’s constant h. The phase rotation accumulated along γ is therefore S[γ]/ℏ radians, and the phase contributed by this rotation is:

phase[γ] = exp ((i S[γ])/(ℏ)).

The factor i in the exponent is the *same* perpendicularity marker that appears in x₄ = ict: each oscillation is a quarter-rotation in the (spatial, x₄) plane four times around, with the imaginary unit recording the perpendicular direction of advance. The factor ℏ in the denominator is the action-quantization scale of Proposition 2.2.

The McGucken wavefunction is the sum over all paths from E to B ∈ 𝓜_E(t) (B on the null wavefront) of these phase contributions (Definition 2.6):

ψ(B) = ∑_γ : E → B exp ((i S[γ])/(ℏ)) ∈ ℂ.

Both the perpendicularity of x₄ (Part 1) and its action-per-oscillation (Part 2) are required for the full complex-amplitude content: perpendicularity without the action gives a static imaginary coordinate without phase accumulation; the action without perpendicularity gives an action quantum without a perpendicular axis to rotate around. The Principle dx₄/dt = ic supplies both, as its two clauses (Proposition 2.2).

If x₄ were real — x₄ = ct without the i — the path weights would be exp(S/ℏ), real and (for S \> 0) divergent or decaying. This is precisely the Wick-rotated Euclidean theory ([6, §9]; corpus paper [7]), which is classical statistical mechanics, not quantum mechanics. The Wick rotation t → -iτ that connects the two is, in McGucken terms, the coordinate identification τ = x₄/c ([6, Theorem 9.1] and the dedicated companion paper [7], which develops the McGucken–Wick rotation as a real coordinate identity on Minkowski space 𝕄_(1,3), the constraint surface where dx₄/dt = ic holds at every event). The i in x₄ = ict is what marks the genuine perpendicularity of x₄ to ordinary space, and that perpendicularity is what makes the path weights complex phases rather than real exponentials. Removing the i removes the perpendicularity and collapses quantum mechanics to its Euclidean shadow. ∎

The complex character established here is the prerequisite for the entire formalism that follows. The Hilbert space requires complex amplitudes; the canonical commutator requires the factor i; the Born rule requires the modulus structure; the uncertainty principle and Schrödinger equation require the complex inner-product space on which the operators act. Theorem 3.1 supplies the underlying complex structure from which all five subsequent derivations descend.


## Part III. The McGucken channels defined in depth: the dx₄/dt = ic Geometric Channel and the dx₄/dt = ic Algebraic Channel of the McGucken Duality

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The Principle has two faces, and the two channels are the two faces read as derivation routes. Read as geometry, dx₄/dt = ic is the McGucken Sphere Σ₊(p) expanding at +ic from every event p, self-replicating by Huygens' principle, carrying the orientation + of +ic, and colliding with other Spheres at detection events; this is the dx₄/dt = ic Geometric Channel. Read as algebra, dx₄/dt = ic integrates to x₄ = ict, squares to (ic)² = -c², and yields the Lorentzian metric, the Poincaré algebra, the canonical commutator [q̂, p̂] = iħ, the Hilbert space with its sesquilinear pairing, and the unitary group U(t) = e^(-iĤ t/ħ); this is the dx₄/dt = ic Algebraic Channel. The relation between them is the McGucken Duality: the Algebraic Channel is the image of the Geometric Channel under the forgetful projection Π_A that retains the T-invariant algebra and sets aside the orientation + (§16.2), and no inverse projection Π_B exists (Theorem 16.3). For the Born rule this has a precise consequence, worked out in Parts V–VII: the equation P = |ψ|² is T-invariant mathematics and therefore has a derivation in each channel (Corollary 16.4), whereas the detection event at which the rule is instantiated is +ic-oriented and lives in the Geometric Channel alone (Corollary 16.5).

The subsections below reproduce verbatim and in full, from [1], the architecture of the channels (§1.5), the formal definition of Π_A (§16.2), the position-of-i diagnosis (§16.3), the three theorems and two corollaries of the projection theorem (§§16.4–16.8), the two positions relative to the wavefront that define the channels kinematically (§9.5.13), and the historical inversion that explains why the Algebraic Channel was the channel history took (§§6.6.5.1–6.6.5.3).

### III.1 The dual-channel architecture of the McGucken Quantum Formalism

The McGucken Principle dx₄/dt = ic predicts that every structure of quantum theory has two derivations, one through Huygens-wavefront propagation on the McGucken Sphere (the Lagrangian route) and one through translation invariance, Stone's theorem and Stone–von Neumann uniqueness (the Hamiltonian route), sharing no intermediate machinery. The architecture is stated in §1.5 of [1], reproduced here.


### 1.5 The dual-channel architecture within the McGucken Quantum Formalism

The dual-channel architecture — dx₄/dt=ic Geometric Channel (geometric-propagation channel) and dx₄/dt=ic Algebraic Channel (algebraic-symmetry channel) derivations of every quantum-theoretical structure, with both channels descending from the McGucken Principle dx₄/dt = ic through derivationally distinct intermediate machinery — is a formal development of the **McGucken Quantum Formalism (MQF)** established as the categorically novel quantum-theoretical structure underlying the McGucken Principle in [8] (the comprehensive prior-art survey and formal categorical-novelty propositions) and [9] (the dual-route Hamiltonian-Lagrangian derivation of the canonical commutator). The dx₄/dt = ic Geometric Channel derivations correspond to the **Lagrangian route Propositions L.1–L.6** of [9]: the geometric-propagation route through Huygens-wavefront propagation on the McGucken Sphere, path-space generation by iterated Huygens expansions, the x₄-phase identification with classical action, the Feynman path integral as sum over paths weighted by x₄-phase, and short-time Gaussian integration recovering the Schrödinger equation. The Algebraic Channel derivations correspond to the **Hamiltonian route Propositions H.1–H.5** of [9]: the algebraic-symmetry route through translation invariance, Stone’s theorem on strongly continuous one-parameter unitary groups, the configuration representation, and Stone–von Neumann uniqueness. **The dx₄/dt = ic Geometric Channel is the more foundational channel**: it carries the full content of the McGucken Principle including its +ic orientation, with the McGucken Sphere expanding at +ic from every event of Minkowski Space 𝕄_(1,3) being the physical-spacetime of the dx₄/dt = ic framework. The Algebraic Channel is the T-invariant projection of the dx₄/dt = ic Geometric Channel (the projection theorem ΠA of §16), with the orientation +ic algebraically projected away into the sign-blind operator algebra. The dx₄/dt = ic Geometric Channel is foundationally primary; the Algebraic Channel is the algebraic shadow.

The relation between the two channels is known as the **McGucken Duality** (equivalently the **dx₄/dt=ic Duality** or the **McGucken dx₄/dt=ic Duality**): the foundational Geometric Channel carries the +ic-oriented McGucken Sphere expansion at every spacetime event, and the Algebraic Channel is its T-invariant algebraic shadow. The convergence of the dx₄/dt = ic Geometric Channel and the Algebraic Channel on the same result through disjoint intermediate machinery is the **convergent-overdetermination property** of MQF, formalized as Lemma 15.1 of [8] and Theorem VII.1 of [9]: the two routes share no intermediate machinery except the starting principle dx₄/dt = ic and the final algebraic identity. Stone’s theorem does not appear in the Lagrangian route; Huygens-wavefront propagation does not appear in the Hamiltonian route; configuration representation and Gaussian path-integration are disjoint operations. The same canonical commutation relation [q̂, p̂] = iℏ is reached by two independent chains from the same starting principle, with no shared intermediate steps. This is the formal-mathematical signature of the dual-channel commitment of MQF, and it is the property that distinguishes MQF from every prior single-channel framework of quantum theory.

The companion paper [10] establishes the analogous categorical-novelty result on the geometric side: moving-dimension geometry is a categorically novel geometric category not equivalent to any prior framework of dynamical geometry from 1915 to 2026. Together, the two companion papers position the McGucken Principle as the foundational geometric postulate from which two categorically novel mathematical structures descend: moving-dimension geometry on the geometric side, dual-channel quantum theory on the quantum-theoretical side, with the dual-channel of dx₄/dt = ic as the formal signature of the deeper unity.

§§5–9 develop the QM-derivation sector of the MQF programme to full depth. Where [9] establishes the dual-route derivation of the canonical commutator and the Schrödinger equation as the prototype convergent-overdetermination results, §§5–9 extend the convergent-overdetermination property to the **Hilbert space** (Theorem 6.1 / Theorem 6.1.5, §§6.4–6.4.5–6.4.6), to the **canonical commutator** with explicit dx₄/dt = ic Geometric Channel (Theorem 5.1 / Theorem 5.1.5, §§5.2–5.2.5–5.2.6), to the **Born rule** with three complementary geometric readings (Theorems 7.4, 7.7, 7.11, §§7.4–7.11), to the **Klein–Gordon equation** (Theorem 9.0, §9.1.5), to the **Schrödinger equation** with explicit dx₄/dt = ic Geometric Channel (Theorem 9.0.5, §9.2.5), and to the **uncertainty principle** (Theorem 8.2 / Theorem 8.2.5, §§8.2–8.2.5–8.2.6). The §10.9 audit table catalogs the convergent-overdetermination property across every derivation in the cascade. Each dx₄/dt = ic Geometric Channel / Algebraic Channel convergence is an instance of the convergent-overdetermination property of MQF.

The categorical novelty of dual-channel quantum theory is established formally in [8, Propositions 7.5.1–7.5.4]: the McGucken Quantum Formalism is not reducible to single-channel algebraic-symmetry frameworks (the Heisenberg–Stone–von Neumann apparatus, Wightman axiomatic QFT, Haag–Kastler algebraic QFT, the Wigner–Coleman–Mandula–Weinberg representation-theoretic apparatus, Adler’s trace dynamics), not reducible to single-channel geometric-propagation frameworks (Feynman’s path integral, Dirac’s 1933 Lagrangian formulation, Bohmian mechanics, Nelson’s stochastic mechanics, Lindgren–Liukkonen optimal control, ’t Hooft’s cellular automaton, Hestenes’s spacetime algebra, Schuller’s constructive gravity), and not reducible in standard formulation to spectral-triple frameworks (Connes’s noncommutative geometry) or categorical-QFT frameworks (Atiyah–Segal–Lurie cobordism categories, Lurie’s cobordism hypothesis). The categorical-novelty result is established as a formal mathematical fact via four propositions with proofs, not as a philosophical interpretation. §13 of the present paper revisits the categorical-novelty result in the QM-derivation context with explicit cross-reference.

The MQF framework is summarized as a sextuple **(M, F, V; H, A, ψ)** in [8, Definition 9.2]: the first three components (M, F, V) constitute the moving-dimension manifold from [10, Definition 9.3] (a smooth four-manifold with Lorentzian metric, a codimension-one timelike foliation, and a privileged active timelike vector field whose flow is x₄’s expansion at rate ic); the next three (H, A, ψ) constitute the quantum layer (a separable complex Hilbert space, a *-algebra of operators satisfying the canonical commutation relations, a wavefunction satisfying the Schrödinger equation), with the additional commitment that the dual-channel is the defining feature: both the algebraic structure (H, A) and the wavefunction evolution ψ are derived from dx₄/dt = ic as parallel sibling theorems through Hamiltonian and Lagrangian routes with convergent overdetermination at every identity. §§3–9 supply the QM-derivation content of this sextuple at depth: §§3–9 derive the Hilbert space, canonical commutator, Born rule, uncertainty principle, Schrödinger equation, and Klein–Gordon equation with both channels of MQF realized for each; §§10–12 develop the cogenerative cascade structure (Theorem 10.5), the Hilbert-Minkowski identity (Theorem 10.6), the Dirac–von Neumann axioms as corollaries (§11), and measurement as physical Wick rotation (Theorem 12.2). The corpus citations [11], [12], [13], [14], [15], [3], [16], [17], [18], and the broader McGucken corpus supply the foundational derivations on which §§3–9 build.


### III.2 The channel projection Π_A and the position of i

The McGucken Principle dx₄/dt = ic predicts that the operator algebra of quantum mechanics is the T-invariant residue of the Sphere's geometry: the Lorentzian metric is the null-cone structure of Σ₊(p) with its orientation forgotten, the unitary group is the pointwise McGucken operator 𝓕ₚ with the time direction forgotten, and the canonical commutator is the perpendicularity marker i with the sign of +ic forgotten. The formal definition of the projection and the diagnosis of where the i sits in each channel are §§16.2–16.3 of [1], reproduced here.


### 16.2 The channel projection Π_A : 𝓑 → 𝓐 (dx₄/dt = ic Geometric Channel to Algebraic Channel): formal definition as forgetful functor

The channel projection Π_A : 𝓑 → 𝓐 is the forgetful functor that sends each geometric structure in the dx₄/dt = ic Geometric Channel to its underlying T-invariant algebra of automorphisms, where T is Wigner’s antiunitary time-reversal operator (Wigner 1932, satisfying T i T⁻¹ = -i and T Σ₊(p) = Σ₋(p)).

**Definition 16.0 (Channel projection Π_A).** Let 𝓑 denote the full geometry of dx₄/dt = ic, including: the constraint hypersurface 𝒞_M = {(x¹, x², x³, t, x₄) : x₄ = ict}; the McGucken Sphere Σ₊(p) at every event p ∈ 𝒞_M (the spherically symmetric expansion of x₄ at rate +c from p, oriented in the future direction); the Sphere self-replication mechanism (every point q ∈ Σ₊(p) is itself the apex of Σ₊(q)); the pointwise McGucken operator 𝓕ₚ = ∂ₜ + ic ∂_(x₄)|ₚ at every event; the cogeneration cascade 𝓜_G → 𝕄_(1,3) → 𝓥 → 𝓗 producing the Hilbert-space arena; the x₄-flux conservation law ∂ₜ J₄ + ∂_(x₄)(cJ₄) = 0 along the principle’s flow; and the eight forms of entropy (Bekenstein-Hawking horizon entropy, Shannon, von Neumann, Boltzmann H, Gibbs, Clausius, Tsallis, Rényi) as x₄-mode-counting on the principle’s flow.

Let 𝓐 denote the algebra of the same principle: the Lorentzian metric η_(μν) = diag(-c², +1, +1, +1); the Lorentz group SO⁺(1,3) and the Poincaré algebra mathfrakiso(1,3); the canonical commutator algebra [q̂ⁱ, p̂ⱼ] = iħ δⁱⱼ; the Hilbert space 𝓗 with sesquilinear inner product; the unitary one-parameter group U(t) = e^(-iĤt/ħ) generated by self-adjoint Ĥ via Stone’s theorem (Stone 1932); the variational Lagrangian-Hamiltonian formalism; Noether’s first and second theorems and their conserved currents j^μ_X; the CPT operator Theta as antiunitary involution; the Wightman axiomatic apparatus with the Spectrum Condition treated as imported axiom rather than derived theorem (see §16.15 below).

The Wigner time-reversal operator T acts on 𝓑 as the orientation-reversal involution: T : Σ₊(p) ↦ Σ₋(p), T : +ic ↦ -ic, T : i ↦ -i, T : dx₄/dt ↦ -dx₄/dt. T is antiunitary on Hilbert space 𝓗 in the Wigner-Bargmann sense (Wigner 1932 §26, Bargmann 1964): for ψ, φ ∈ 𝓗, (Tψ, Tφ) = (̄ψ, φ) = (φ, ψ). T sends the canonical pair (q̂, p̂) to (Tq̂T⁻¹, Tp̂T⁻¹) = (q̂, -p̂), with the canonical commutator preserved: [Tq̂T⁻¹, Tp̂T⁻¹] = [q̂, -p̂] = -[q̂, p̂] = -iħ = T(iħ) = T([q̂, p̂]), so T is an algebra-automorphism of the canonical algebra. The Hermitian Hamiltonian Ĥ in time-independent contexts is taken T-invariant: TĤT⁻¹ = Ĥ (Wigner 1932 §26, with T-violating terms accommodated by appropriate sign-flips of the relevant operators in the more general case).

The channel projection Π_A : 𝓑 → 𝓐 is the forgetful functor defined by:

Π_A(X) = X|_(T-invariant component) = 1/2(X + T X T⁻¹)

for X ∈ 𝓑 extended to operate on the algebra of automorphisms of geometric structures in 𝓑. Equivalently, Π_A restricts to the T-invariant subalgebra of 𝓑, sending each geometric structure to its underlying algebra of T-symmetric automorphisms.

The Lorentzian metric η_(μν) is T-invariant (η depends on (ic)² = -c², sign-blind on i); Π_A(Σ₊(p)) → η_(μν) in the sense that the metric is the null-cone structure of the Sphere with orientation forgotten. The canonical commutator [q̂, p̂] = iħ is T-invariant in the sense that the commutator algebra survives the involution T as itself (with both sides flipping sign consistently, the algebra is preserved). The Hamiltonian Ĥ in T-symmetric contexts is T-invariant, and U(t) = e^(-iĤt/ħ) survives as U(-t) = U(t)⁻¹ (Stone’s theorem gives an isomorphic unitary one-parameter group with reversed parameter). The Lagrangian 𝓛 and Noether currents j^μ_X are T-invariant. The CPT operator is T-invariant.

The McGucken Sphere Σ₊(p) is *not* T-invariant: TΣ₊(p) = Σ₋(p), the past light cone. The Sphere self-replication direction (Huygens propagating forward) is not T-invariant. The Bekenstein-Hawking entropy growth dS/dt > 0 is not T-invariant: T(dS/dt) = -dS/dt < 0. The retarded Green’s function G_R(x; x') supported on the future light cone is not T-invariant: TG_R T⁻¹ = G_A, the advanced Green’s function. The Wick rotation t → -iτ is not T-invariant: under T, -iτ → +iτ, the divergent direction.

The forgetful framing Π_A as “forget the +ic orientation, retain the algebra” is equivalent to the T-invariant-subalgebra framing Π_A as “restrict to the kernel of T - id” because the two operations have the same image: every T-invariant element of 𝓑 survives in 𝓐, and every T-non-invariant element is projected out (its T-anti-invariant part is removed). The two framings are also equivalent to the ℤ₂-quotient framing Π_A as 𝓑/⟨ T ⟩, the quotient by the time-reversal involution.

### 16.3 The position-of-i diagnosis and the decomposition +ic = (+) · i · c: separating the orientation sign (+), the perpendicularity marker i, and the rate c into three independent informational contents

The reason the projection has the form it has traces to the **position-of-i diagnosis** of [19 §IX.13.14]: in the Algebraic Channel, the imaginary unit i is interior to the algebra (sits inside [q̂, p̂] = iħ, inside the Lorentz algebra brackets [J^(μν), J^(ρσ)] = i(η^(μρ)J^(νσ) - …), inside the unitary exp(-iĤt/ħ), inside the Dirac equation (iγ^μ∂_μ - m)ψ = 0, and inside the path-integral kernel exp(iS/ħ)); in the dx₄/dt = ic Geometric Channel, the imaginary unit i is exterior, exteriorisable via the coordinate identification τ = x₄/c (which converts dx₄/dt = ic into the real Sphere expansion dx₄/dτ = c along x₄).

The interior-i position in Algebraic Channel is **forced** by algebraic requirements. Hermitian operators q̂, p̂ have anti-Hermitian commutators: (q̂p̂ - p̂q̂)^† = -(q̂p̂ - p̂q̂) for Hermitian q̂, p̂. The right-hand side of the canonical commutator must therefore be anti-Hermitian; the *only* way to write an anti-Hermitian real-scalar multiple is iħ with real ħ. The i is required, not optional. The same argument forces i into the Lorentz algebra brackets (closure with Hermitian generators), the unitary exp(-iĤt/ħ) (Stone’s theorem requires the i for self-adjoint generator), and the Dirac equation (positive-energy plane-wave solutions). **Algebraic Channel’s algebra requires the i to be interior — there is no algebraically well-formed apparatus in which the i is exterior to its commutator brackets or its unitary generator.**

The exterior-i position in dx₄/dt = ic Geometric Channel is **admissible** because the geometry (Sphere expanding at velocity c, wavefront radius growing at rate c) is real and has the coordinate identification τ = it that pulls the i outside. The Sphere expands at c regardless of whether the time variable is called t or -iτ; the geometry doesn’t care about coordinate labels. The exterior-i position is what allows the McGucken-Wick rotation to operate as a coordinate identification (bridging dx₄/dt = ic Geometric Channel and Algebraic Channel) rather than as an algebraic deformation.

The decomposition +ic = +· i · c makes the content of the principle explicit:

- **i** marks **geometric perpendicularity** — x₄ is perpendicular to the spatial slice x₁ x₂ x₃. This is what makes the metric Lorentzian rather than Euclidean. **Sign-symmetric**: (-i)² = i² = -1, so the perpendicularity itself is invariant under T. Algebraic Channel reads this content.

- **c** is the **magnitude** of the expansion velocity, a positive scalar (light speed). **Sign-symmetric** in the sense that c enters the Lorentzian metric squared as c², sign-blind on the direction of motion. Algebraic Channel reads this content too (via ħ as c-counting-action, with ħ entering quantum-mechanical structures).

- **+** is the **direction** of the expansion: the McGucken Sphere expands at +ic, not contracts at -ic. The Sphere goes outward in time, not inward. **Sign-asymmetric**: this is the unique content that is T-anti-invariant. Algebraic Channel does not read this content; dx₄/dt = ic Geometric Channel does.

Algebraic Channel reads i (perpendicularity) and c (velocity magnitude) but is blind to + (orientation), because the +ic ↔ -ic involution acts as the identity on every algebraic object Algebraic Channel constructs (every commutator, every unitary group, every Hermitian operator, every Lagrangian, every Noether current survives T as itself, up to consistent global sign-flips that preserve the algebra). dx₄/dt = ic Geometric Channel reads all three components because its geometry commits to the direction of + in +ic — the Sphere has an apex from which it expands outward, and the direction “outward” is a dx₄/dt = ic Geometric Channel commitment that Algebraic Channel cannot recover from its sign-blind apparatus.

Algebraic Channel’s interior-i position locks the algebra to sign-blindness on +ic. The dx₄/dt = ic Geometric Channel’s exterior-i position carries orientation. The projection Π_A from the dx₄/dt = ic Geometric Channel to Algebraic Channel is the exteriorisation-reversal: pull the i inside the algebra and the direction + is necessarily projected away because the algebra cannot carry it.


### III.3 The three theorems and two corollaries of the projection

The McGucken Principle dx₄/dt = ic predicts that the Geometric Channel reaches every algebraic structure of quantum mechanics by the cogeneration cascade 𝓜_G → 𝕄_(1,3) → 𝓥 → 𝓗 without taking operator algebra as input (Theorem 16.1), that the Algebraic Channel built from algebra alone is sign-blind on +ic and must import the Spectrum Condition to be empirically adequate (Theorem 16.2), and that the projection from geometry to algebra has no inverse (Theorem 16.3). The Born rule enters each of these: it is the Haar-measure step of the Geometric Channel's construction (Theorem 16.1, Step 4), it is T-invariant as an equation and so has an Algebraic Channel derivation (Corollary 16.4), and its every physical instantiation is a +ic Sphere collision (Corollary 16.5). Sections 16.4–16.8 of [1] are reproduced here.


### 16.4 Theorem 16.1: the dx₄/dt = ic Geometric Channel’s Foundational Self-Sufficiency

**Theorem 16.1 (dx₄/dt = ic Geometric Channel’s Foundational Self-Sufficiency and Cascade-Reachability of the Algebraic Channel’s Content).** dx₄/dt = ic Geometric Channel’s apparatus — the McGucken Sphere Σ₊(p) at every event, Huygens self-replication, the Born-rule Haar measure on the Sphere, the eight forms of entropy, the McGucken-Wick rotation, the pointwise McGucken operator 𝓕ₚ, and the cogeneration cascade 𝓜_G → 𝕄_(1,3) → 𝓥 → 𝓗 — develops from the foundational principle dx₄/dt = ic together with event-homogeneity (the principle holds identically at every spacetime event), without taking operator algebra as primitive input. Moreover, the cogeneration cascade derivationally produces the Hilbert-space arena 𝓗 = L²(𝕄_(1,3), η_(μν)) as downstream output, on which Algebraic Channel’s operator algebra is naturally defined. **dx₄/dt = ic Geometric Channel is therefore foundationally complete: its independent construction reaches both its own geometry and Algebraic Channel’s algebra (via the cascade).**

**Proof.** We construct dx₄/dt = ic Geometric Channel’s apparatus step by step from the principle without invoking Algebraic Channel’s algebra as primitive input. The full development is in [1 §2–§12] and [20 §3–§9]; the present proof summarises the construction chain.

*Step 1 (Sphere from principle).* The principle dx₄/dt = ic states that x₄ advances at rate c in the direction perpendicular to x₁ x₂ x₃ (the perpendicularity marked by i) at every event. Combined with event-homogeneity (the principle holds at every event with the same form) and SO(3) spatial isotropy at every event, the locus of points reachable from event p₀ at parameter time t₀ + δ t is the 2-sphere of radius c δ t in the spatial directions, with all surface points sharing the same x₄-advance from p₀. This is the McGucken Sphere Σ₊(p₀, t₀ + δ t), constructed from the principle without invoking Hilbert-space machinery [20 §3.1, Principle 1].

*Step 2 (Self-replication from universality).* The principle holds at every spacetime event, including every event on an existing Sphere. Therefore every point q ∈ Σ₊(p₀) is itself an event satisfying dx₄/dt = ic, and generates its own McGucken Sphere Σ₊(q). The recursion is forced by the universality of the principle, not added as a separate postulate. This is Huygens’ Principle elevated from heuristic to foundational mechanism [20 Theorem 2; §16.9.14 of [8]].

*Step 3 (Wavefront geometry from Sphere structure).* The spherical symmetry of the Sphere at every event provides the wavefront geometry of x₄-advance. The wavefront is the surface of the Sphere; its propagation at c is the rate of Sphere expansion; the phase carried by the wavefront is the x₄-coordinate value at each Sphere point. No operator algebra is invoked.

*Step 4 (Born-rule Haar measure on the Sphere).* The Sphere Σ₊(p) at parameter time δ t has spatial radius c δ t and surface measure 4π(c δ t)². The SO(3) isotropy of the principle at every event implies that the Haar measure on the Sphere’s surface is the unique SO(3)-invariant probability measure: dμ(θ, φ) = sinθ dθ dφ/(4π). The Born rule probability density P = |ψ|² is the head-on collision rate of two McGucken Spheres at the detection event [1 Theorem 7.7; [8 §16.9.13] of the present paper], with the exponent 2 overdetermined by three independent routes (rank-2 metric pairing, two-particle collision, PT-symmetry through source event), all descending from dx₄/dt = ic. The construction operates on the Sphere geometry without invoking Hilbert-space machinery as primitive input; the Hilbert-space inner product arises downstream from the cogeneration cascade [Step 7 below].

*Step 5 (Eight forms of entropy as x₄-mode-counting).* The Bekenstein-Hawking entropy on a horizon is the count of x₄-stationary modes piercing the horizon, with one Planck-area cell per mode [20 §10.2; 21 Theorem 15]. The Shannon, von Neumann, Boltzmann H, Gibbs, Clausius, Tsallis, and Rényi entropies are derived as x₄-mode-counting on different reference structures (probability distributions, density matrices, phase-space measures, Clausius-relation heat exchanges) [21 §1–§4]. The construction operates on Sphere geometry and mode-counting without invoking Hilbert-space machinery as primitive input.

*Step 6 (McGucken-Wick rotation from coordinate identification).* The Wick rotation τ = x₄/c is a coordinate identification on the constraint hypersurface 𝒞_M = {x₄ = ict}: substituting gives τ = it, with τ real on 𝒞_M. The rotation operates on the geometry of the principle (the constraint hypersurface), not on operator-algebra. The convergent direction t → -iτ (rather than +iτ) is fixed by the Sphere’s +ic orientation, with the convergent Euclidean path integral exp(-S_E/ħ) arising from the geometry Theorem 12.2 [present paper; [8 §16.9.13] of the present paper, item (viii)].

*Step 7 (Cogeneration cascade producing the Hilbert-space arena, with explicit §6 inheritance).* The construction 𝓜_G → 𝕄_(1,3) → 𝓥 → 𝓗 derives the Hilbert-space arena from the dx₄/dt = ic Geometric Channel’s geometry via the explicit four-step cascade established in the present paper:

- **Step 7a (McGucken source space 𝓜_G):** the pre-spacetime object of point-source events from which dx₄/dt = ic operates (Theorem 2.4, §2.6 of the present paper).
- **Step 7b (𝓜_G → 𝕄_(1,3)):** integration of dx₄/dt = ic yields x₄ = ict; substitution into the four-dimensional Euclidean line element produces η_(μν) = diag(-c², +1, +1, +1) (Lemma 2.5, §2.7). The Minkowski manifold Minkowski space 𝕄_(1,3) is the constraint surface where dx₄/dt = ic holds locally.
- **Step 7c (𝕄_(1,3) → 𝓥):** the pre-Hilbert wavefront space 𝓥 is the complex vector space of finite Huygens–Fresnel–Kirchhoff superpositions of McGucken-Sphere wavefronts on Minkowski Space 𝕄_(1,3), constructed in §6.4.5 (dx₄/dt = ic Geometric Channel route, Steps 1-2). Each wavefront is a Sphere of radius c(t-tₚ) expanding from a source event p, with complex amplitude content forced by Theorem 3.1 (Frobenius selection of ℂ given one perpendicular axis).
- **Step 7d (𝓥 → 𝓗):** the Hilbert space 𝓗 = L²(𝕄_(1,3), η_(μν)) is the Cauchy completion of 𝓥 under the geometric-overlap inner product (the sesquilinear pairing whose quadratic diagonal Lemma 7.1 forces), proved as Theorem 6.1 (Algebraic Channel) and Theorem 6.1.5 (dx₄/dt = ic Geometric Channel) of the present paper. The inner product axioms — sesquilinearity, conjugate symmetry, positive-definiteness — are inherited from Theorems 7.4, 7.7, and 7.11 of the present paper (the three geometric readings of the Born rule density as McGucken-Sphere collision content).

The cascade is *cogenerative*: each level is generated from the previous via the principle’s content (Sphere structure, wavefront propagation, geometric-overlap completion), without external Hilbert-space machinery imported as primitive input. The detailed construction is in §§6.4-6.4.6 of the present paper, with explicit dx₄/dt = ic Geometric Channel and Algebraic Channel derivations and their convergence.

*Step 8 (Algebraic Channel’s content as cascade output, with explicit §10–§11 inheritance).* The Hilbert space 𝓗 produced by the cascade carries the natural operator algebra reached as cascade output:

- **Position operators** q̂ⁱ as spatial multiplication on L²(𝕄_(1,3)) (§6.4 Step 5).
- **Momentum operators** p̂ⱼ = -iħ ∂ⱼ as generators of spatial translations on Minkowski Space 𝕄_(1,3) (§5.2 Algebraic Channel derivation via Stone’s theorem on translation invariance).
- **Canonical commutator** [q̂ⁱ, p̂ⱼ] = iħ δⁱⱼ as the operator-level expression of the geometry (Theorem 5.1 Algebraic Channel and Theorem 5.1.5 dx₄/dt = ic Geometric Channel of the present paper, with Proposition 12.10 stating the operator-level perpendicularity).
- **Unitary evolution** U(t) = e^(-iĤt/ħ) from the principle’s time-evolution structure via Stone’s theorem applied to the cascade-produced Hilbert space (§9.2 Algebraic Channel derivation of the Schrödinger equation).
- **The Lorentz group** as the isometry group of η_(μν), with both postulates of special relativity descending from the universality and rate clauses of dx₄/dt = ic (Theorem 2.4.5 of the present paper).
- **The full Dirac–von Neumann axiomatization** — Hilbert space as the state arena, observables as self-adjoint operators, states as density matrices, dynamics by Schrödinger, measurement by projective decomposition — as corollaries of the McGucken Principle via the cogenerative cascade (§11 of the present paper, six DvN axioms derived as Corollaries 11.1–11.6).
- **The pointwise instantiation structure** of the principle in each cascade output (Theorem 10.5 of the present paper: four senses — literal/constructive/evaluative/operatorial — in which dx₄/dt = ic is locally readable at every point of every cascade level).
- **The Hilbert-Minkowski identity** 𝓗 ≅ L²(𝕄_(1,3), η_(μν)) (Theorem 10.6 of the present paper, establishing that the Hilbert space and Minkowski spacetime are two presentations of one geometric object).

**Algebraic Channel’s operator-algebraic apparatus is therefore reached derivationally as cascade output from the dx₄/dt = ic Geometric Channel’s geometric foundations, with the full apparatus traced explicitly through the present paper’s §§2–11.**

The construction in Steps 1–8 operates without invoking operator algebra as primitive input — every algebraic object is either constructed from geometry (Steps 1–6) or derived as cascade output via the present paper’s machinery (Steps 7–8). The dx₄/dt = ic Geometric Channel’s apparatus is foundationally self-sufficient, and dx₄/dt = ic Geometric Channel’s independent construction reaches all of the Algebraic Channel’s content via the cascade. ∎

dx₄/dt = ic Geometric Channel is foundationally complete: it produces both its own T-anti-invariant structure (Sphere, Huygens, dS/dt > 0, retarded Green’s function, Wick rotation sign) and Algebraic Channel’s T-invariant structure (operator algebra, Lorentz group, canonical commutator, unitary evolution, DvN axiomatization, the cascade 𝓜_G → 𝕄_(1,3) → 𝓥 → 𝓗) via the §§2–11 derivations of the present paper. This is the source-to-image direction of the projection Π_A, and it is constructively realised by the cogeneration cascade. The present paper’s §§2–11 IS the explicit content of Π_A : 𝓑 → 𝓐 realized in derivational detail; §16 establishes the reading of that derivational content as the forward projection of the dx₄/dt = ic Geometric Channel onto its T-invariant image.

### 16.5 Theorem 16.2: the Algebraic Channel’s Sign-Blind Constructive Independence and Empirical Insufficiency without the Spectrum Condition

**Theorem 16.2 (Algebraic Channel’s Sign-Blind Independence and Empirical Insufficiency).** Algebraic Channel’s sign-blind algebraic apparatus — the Hilbert space 𝓗 with Hermitian operator algebra, the canonical commutator [q̂, p̂] = iħ, Stone’s theorem with unitary one-parameter groups, the Poincaré algebra mathfrakiso(1,3), the Lorentzian metric η_(μν), the variational Lagrangian-Hamiltonian formalism, Noether’s first and second theorems with conserved currents, and the CPT operator — is constructively independent of the dx₄/dt = ic Geometric Channel: the apparatus can be built from algebraic foundations (Hilbert space, operator algebra, variational calculus, group theory) without invoking the McGucken Sphere or any dx₄/dt = ic Geometric Channel geometric primitive as input. This constructive independence is established by the historical record of 1925–1957: Heisenberg-Born-Jordan (1925), Dirac (1925), Stone (1932), von Neumann (1932), Bargmann (1957), and the first five Wightman axioms (1956) constructed this apparatus from algebraic foundations alone.

**However, Algebraic Channel’s sign-blind construction is empirically insufficient**: the sign-blind apparatus does not pick out positive-energy spectrum vs. negative-energy spectrum, does not distinguish future light cone Σ₊(p) from past light cone Σ₋(p) as physically realised, does not produce the strict Second Law dS/dt > 0, does not give the radiative arrow (retarded over advanced Green’s function), does not give the cosmological expansion direction H₀ > 0, and does not produce matter dominance. Empirical adequacy of the algebraic apparatus requires importing the **Spectrum Condition** (Wightman 1956 sixth axiom: Spec(P^μ) ⊂ V̄₊, the closed forward light cone in momentum space), which explicitly breaks the +ic ↔ -ic symmetry by selecting positive-energy states. The Spectrum Condition is *not* a theorem of the other Algebraic Channel axioms; it must be imposed externally. The McGucken dx₄/dt = ic framework identifies the Spectrum Condition as the algebraic residue of the dx₄/dt = ic Geometric Channel’s +ic orientation surviving the projection Π_A: the orientation cannot live in the sign-blind algebra, but it must be imported for the algebra to be empirically adequate.

**Proof.** We establish (i) the constructive independence of the Algebraic Channel’s sign-blind apparatus from the dx₄/dt = ic Geometric Channel, by tracing the historical construction; (ii) the empirical insufficiency of the sign-blind apparatus, by enumerating what physics it fails to produce; and (iii) the identification of the Spectrum Condition as the algebraic residue of the dx₄/dt = ic Geometric Channel’s orientation.

*Step 1 (Constructive independence: the 1925–1957 record).* The historical construction of the Algebraic Channel’s sign-blind apparatus from algebraic foundations is empirical fact: Heisenberg’s 1925 matrix mechanics derived the canonical commutator from spectral-line observations and matrix algebra without geometric primitives; Born-Jordan 1925 systematized the operator algebra; Dirac 1925 produced an independent operator-algebraic formulation; Stone 1932 proved the one-parameter-unitary-group theorem on Hilbert spaces from algebraic-functional-analytic foundations; von Neumann 1932 systematized the Hilbert-space formalism with Hermitian operators, projection-valued measures, and the spectral theorem; Bargmann 1957 constructed the unitary irreducible representations of the Poincaré group from algebraic foundations; Wightman 1956 axiomatized QFT with five algebraic axioms (Hilbert space, Poincaré covariance, locality / microcausality, field operator domain, vacuum existence) that are sign-blind on +ic. None of these constructions invoked the McGucken Sphere as primitive input; all produced Algebraic Channel’s apparatus from algebraic foundations alone.

*Step 2 (Empirical insufficiency: what the sign-blind apparatus fails to produce).* The sign-blind Algebraic Channel apparatus does not contain the following empirics:

(a) **Positive-energy spectrum.** The Hilbert space and Hermitian Hamiltonian apparatus has both positive-energy and negative-energy eigenstates of Ĥ. The Dirac equation produces explicitly four-component solutions, half of which are negative-energy. Dirac 1928 had to resolve this via hole theory (the negative-energy sea); the Feynman-Stückelberg interpretation 1948 reinterpreted negative-energy states as antiparticles. The sign-blind apparatus cannot pick out which spectrum half is physically realised; this content has to be imported.

(b) **Future-vs-past light cone distinction.** The Lorentzian metric has both future-directed and past-directed null vectors symmetrically; the connected component SO⁺(1,3) does pick out time orientation, but the *choice* of which orientation is “future-pointing” is a dx₄/dt = ic Geometric Channel commitment, not derivable from the algebraic apparatus alone. The retarded Green’s function G_R(x; x') supported on the future light cone and the advanced Green’s function G_A(x; x') on the past light cone are formally symmetric — Maxwell’s equations admit both; the empirical privilege of G_R (Wheeler-Feynman 1945 absorber theory) is dx₄/dt = ic Geometric Channel.

(c) **Strict Second Law dS/dt > 0.** Liouville’s theorem (preserved phase-space volume under Hamiltonian flow) is T-symmetric — phase space volume is preserved both forward and backward in time. The H-theorem requires Boltzmann’s Stosszahlansatz (molecular chaos assumption), which is itself T-anti-invariant and is therefore not derivable from the Algebraic Channel apparatus alone. Loschmidt 1876 proved this: time-symmetric microdynamics cannot derive a strict monotonic Second Law. The sign-blind apparatus is exactly time-symmetric microdynamics; the strict Second Law cannot be derived from it.

(d) **Cosmological expansion.** The Lorentzian field equations admit both expanding and contracting solutions; the Friedmann-Robertson-Walker equations have both H > 0 and H < 0 branches. The empirical fact H₀ > 0 (Hubble 1929 observational discovery of expansion) is dx₄/dt = ic Geometric Channel.

(e) **Matter-antimatter cosmological asymmetry.** Algebraic Channel’s sign-blind apparatus treats matter and antimatter symmetrically (via charge conjugation C). The observed cosmological matter dominance requires Sakharov’s three baryogenesis conditions (baryon number violation, C and CP violation, departure from thermal equilibrium), all of which carry T-anti-invariant structure. The sign-blind algebra does not derive cosmic matter dominance; it has to be imported.

(f) **Quantum-measurement direction.** The unitary evolution is T-invariant (U(-t) = U(t)⁻¹); the algebra does not pick out a privileged direction of measurement. The Born-rule realization (measurement happening forward in time, with collapse at future detection events) is dx₄/dt = ic Geometric Channel Theorem 12.2 [present paper: measurement as physical Wick rotation].

*Step 3 (Spectrum Condition as algebraic residue of the dx₄/dt = ic Geometric Channel’s orientation).* The Wightman 1956 axiomatic system was the systematic axiomatization of QFT, intended to reduce the operator-algebra to a minimal set of postulates. The first five axioms — Hilbert space (W1), Poincaré covariance (W2), locality / microcausality (W3), domain of field operators (W4), vacuum existence and uniqueness (W5) — are sign-blind on +ic: each axiom is invariant under the +ic ↔ -ic involution. The sixth axiom — the **Spectrum Condition** (W6: Spec(P^μ) ⊂ V̄₊, the joint spectrum of the energy-momentum operators P^μ is contained in the closed forward light cone in momentum space) — explicitly breaks the symmetry: it picks out positive-energy states and excludes negative-energy states.

The Spectrum Condition is *not* a theorem of the other Wightman axioms. It must be *imposed* as an independent axiom. Sixty-eight years of axiomatic QFT (1956–2026) has been carrying the Spectrum Condition as an unexplained axiom because Algebraic Channel has no other place to put the +ic orientation — the orientation cannot live in the sign-blind algebra, so it must be imported as an additional axiom to make the apparatus empirically adequate.

The McGucken dx₄/dt = ic framework identifies the status of the Spectrum Condition: **it is the algebraic residue of the dx₄/dt = ic Geometric Channel’s +ic orientation surviving the projection Π_A**. The Sphere’s +ic expansion direction, when projected through Π_A to the algebraic image, manifests as the requirement that the energy-momentum spectrum be supported on the forward light cone in momentum space — equivalently, that physical states have non-negative energy with respect to a chosen time orientation. This is the residue that cannot be projected away because empirical adequacy demands it; The Algebraic Channel had to import it as an axiom because the sign-blind apparatus has no internal mechanism to produce it.

*Conclusion of proof.* (i) Algebraic Channel’s sign-blind apparatus is constructively independent (historical record 1925–1957). (ii) The sign-blind apparatus is empirically insufficient (does not produce six classes of observed physics). (iii) The Spectrum Condition, required for empirical adequacy, is the algebraic residue of the dx₄/dt = ic Geometric Channel’s +ic orientation. The status is therefore: **Algebraic Channel is constructively independent of the dx₄/dt = ic Geometric Channel in the sign-blind subset, but Algebraic Channel’s empirical adequacy requires importing exactly the dx₄/dt = ic Geometric Channel that the projection Π_A has algebraically projected away.** ∎

The Wightman 1956 axiomatic apparatus is the empirical realisation of the Spectrum Condition’s status as dx₄/dt = ic Geometric Channel residue: axiomatic QFT carrying a sixty-eight-year-old unexplained axiom is the historical signature of the projection theorem’s content. The McGucken dx₄/dt = ic framework supplies what Wightman could not derive: the Spectrum Condition is forced by the dx₄/dt = ic Geometric Channel’s +ic orientation, with the orientation being a dx₄/dt = ic Geometric Channel geometric primitive that the sign-blind algebra cannot reach but must accommodate.

### 16.6 Theorem 16.3: Content Asymmetry — Π_A exists, Π_B does not

The Content Asymmetry theorem is proved through two formal lemmas, each establishing one of the two distinct obstructions to the inverse projection Π_B : 𝓐 → 𝓑, followed by the main theorem statement that combines them.

#### Lemma 16.3.1 (Sign-blindness obstruction)

**Lemma 16.3.1 (Sign-blindness of the Algebraic Channel on the +ic orientation).** *Let T : 𝓑 → 𝓑 be Wigner’s antiunitary time-reversal operator (Wigner 1932), satisfying T i T⁻¹ = -i and T Σ₊(p) = Σ₋(p) where Σ_±(p) are the forward and backward McGucken Spheres at event p. Let 𝓐₀ ⊆ 𝓑 be the subset of dx₄/dt = ic Geometric Channel consisting of the Lorentzian metric η_(μν), the Lorentz algebra mathfrakso(1,3), the Poincaré algebra mathfrakiso(1,3), the canonical commutator [q̂, p̂] = iħ, the unitary one-parameter group structure U(t) = e^(-iĤt/ħ), the variational Lagrangian-Hamiltonian apparatus, and Noether’s first and second theorem currents — i.e., the standard Algebraic Channel apparatus.*

*Then 𝓐₀ is contained in the T-invariant subalgebra: every element X ∈ 𝓐₀ satisfies T X T⁻¹ = X up to algebra-internal sign conventions consistent with the involution. Consequently, no element of 𝓐₀ distinguishes +ic from -ic: the +ic ↔ -ic involution is an automorphism of 𝓐₀.*

**Proof of Lemma 16.3.1.**

*(i) The Lorentzian metric.* η_(μν) = diag(-c², +1, +1, +1) depends on (ic)² = -c², sign-blind on i. Under T, the time-component -c² is preserved, and T η_(μν) T⁻¹ = η_(μν).

*(ii) The Lorentz algebra.* The brackets [J^(μν), J^(ρσ)] = i(η^(μρ)J^(νσ) - η^(νρ)J^(μσ) - η^(μσ)J^(νρ) + η^(νσ)J^(μρ)) involve a factor of i on the right-hand side. Under T, both sides flip sign of i: the LHS becomes -i(…), the structure constants flip sign accordingly, and the algebra is preserved. The algebra is invariant under the involution.

*(iii) The Poincaré algebra.* The translation generators P^μ and their brackets with J^(μν) inherit the T-invariance of the Lorentz algebra. The full Poincaré algebra mathfrakiso(1,3) is T-invariant as an abstract Lie algebra.

*(iv) The canonical commutator.* [q̂, p̂] = iħ. Under T (antiunitary), both sides flip sign of i: [Tq̂T⁻¹, Tp̂T⁻¹] = T(iħ)T⁻¹ = -iħ. With the convention Tq̂T⁻¹ = q̂ and Tp̂T⁻¹ = -p̂ (the standard Wigner convention for time-reversal of position and momentum), we have [q̂, -p̂] = -[q̂, p̂] = -iħ, consistent with the antiunitarity. The algebra is invariant under the involution.

*(v) The unitary evolution.* U(t) = e^(-iĤt/ħ) with Ĥ self-adjoint. Under T: T U(t) T⁻¹ = T e^(-iĤt/ħ) T⁻¹ = e^(T(-iĤt/ħ)T⁻¹) = e^(+i (TĤT⁻¹) t/ħ). With the convention T Ĥ T⁻¹ = Ĥ (the Hamiltonian is T-symmetric for closed systems), this gives U(-t) = U(t)⁻¹, the standard time-reversal involution on unitary evolution. The one-parameter group is mapped to its inverse parameterization, generating an isomorphic algebra; the algebraic structure is preserved.

*(vi) The variational Lagrangian and Noether currents.* The Lagrangian L(q, q̇) is T-symmetric when L(q, -q̇) = L(q, q̇), which holds for standard kinetic-plus-potential Lagrangians. Noether currents derived from T-invariant Lagrangians inherit the T-invariance.

*(vii) Closure of the algebra.* Every element of 𝓐₀ is built from (i)–(vi) by polynomial composition, taking brackets, and exponentiation. Each operation preserves T-invariance: a polynomial of T-invariant elements is T-invariant; a bracket of T-invariant elements is T-invariant; exponentiation of T-invariant generators yields a one-parameter group preserved as a set by T. Therefore 𝓐₀ is contained in the T-invariant subalgebra.

*Consequence.* The involution i ↦ -i that defines the T-action on ℂ extends to an automorphism of 𝓐₀. The +ic ↔ -ic involution maps 𝓐₀ to itself. No element of 𝓐₀ distinguishes the two orientations. ∎

The sign-blindness is a fact about Algebraic Channel’s apparatus, not a contingent property of how Algebraic Channel has historically been formulated. Every element of 𝓐₀ is constructed from operations that preserve the +ic ↔ -ic involution: this is what makes Algebraic Channel’s content the *algebraic shadow* of the principle, with the orientation of +ic projected away.

#### Lemma 16.3.2 (Geometry-blindness obstruction)

**Lemma 16.3.2 (Geometry-blindness of the Algebraic Channel on the McGucken Sphere as point-set).** *Let 𝓐 denote Algebraic Channel’s full operator-algebraic apparatus (the algebra of automorphisms of the Hilbert space, including local von Neumann algebras of regional observables). Let Σ₊(p) = {q ∈ 𝕄 : |x_q - xₚ| = c(t_q - tₚ), t_q > tₚ} be the McGucken Sphere at event p, a specific point-set in Minkowski Space 𝕄_(1,3). Then Σ₊(p) is not derivable as a point-set object from 𝓐 alone: any candidate reconstruction 𝓐 → Subsets(𝕄) requires importing additional non-algebraic input.*

**Proof of Lemma 16.3.2.**

*(i) Algebraic Channel operates on operator algebras, not on point-sets.* The mathematical objects of the Algebraic Channel — Hilbert space 𝓗, operator algebra 𝓑(𝓗), regional von Neumann algebras 𝓡(O) ⊂ 𝓑(𝓗) for spacetime regions O — are algebraic structures. The Sphere Σ₊(p) is a point-set: a specific subset of Minkowski Space 𝕄_(1,3) identified by a metric equation. Recovering Σ₊(p) from 𝓐 requires a reconstruction theorem that maps algebraic data to point-set geometric data.

*(ii) The reconstruction-theorem options and their additional requirements.* The historical record of algebra-to-geometry reconstruction theorems is:

- **Gelfand–Naimark 1943**: a commutative C*-algebra is isomorphic to the algebra of continuous functions C(X) on a compact Hausdorff space X, recovered as the spectrum of the algebra. *Additional input required:* commutativity of the algebra. The full Algebraic Channel algebra is non-commutative ([q̂, p̂] = iħ ≠ 0); the recovered space from a commutative subalgebra is at most the joint spectrum of a commuting set of observables (the classical phase space, not the spacetime manifold). The Sphere as a subset of 𝕄 is not recovered.

- **Reeh–Schlieder 1961**: local algebras 𝓡(O) of any open region O act cyclically on the vacuum, generating a dense subspace of Hilbert space 𝓗. *Additional input required:* the regional structure O ↦ 𝓡(O) is taken as input, not derived. The map O ↦ 𝓡(O) requires a primitive notion of spacetime region; Reeh–Schlieder uses but does not derive the manifold structure of 𝕄.

- **Connes 1996, spectral triples**: a commutative spectral triple (𝓐, 𝓗, D) with appropriate axioms (regularity, finite metric dimension, real structure, first-order condition, orientability, Poincaré duality, smoothness) is equivalent to a compact spin Riemannian manifold. *Additional input required:* the Dirac operator D, the real structure J, and the axioms governing D are taken as part of the input data, not derived from the algebra alone. The spectral triple is the algebra-plus-Dirac-operator, which carries enough structure to encode the manifold; pure algebra without D does not.

- **Noncommutative geometry generally**: noncommutative spectral triples extending Connes 1996 to non-commutative algebras encode manifolds via the algebra-Dirac-operator pair, with the same caveats: the Dirac operator is additional input.

(iii) *In all cases, additional non-algebraic input is required to reconstruct point-set geometry from algebraic data.* The additional input is either: a commutative subalgebra (Gelfand–Naimark), a regional-structure map O ↦ 𝓡(O) (Reeh–Schlieder), a Dirac operator and accompanying axioms (Connes), or a noncommutative spectral triple. None of these is internal to 𝓐; each is imposed from outside.

(iv) *Even granted such additional input, the recovered manifold is at best the Minkowski Space 𝕄_(1,3), not the Sphere Σ₊(p).* The Sphere is a specific subset of Minkowski Space 𝕄_(1,3) identified by the metric equation |x_q - xₚ| = c(t_q - tₚ) with the orientation constraint t_q > tₚ. To identify this subset within the reconstructed manifold requires: (a) a marked event p to serve as the Sphere’s center; (b) an orientation choice for t_q - tₚ > 0; (c) the metric structure to evaluate the equation. Items (a) and (b) are not derivable from the algebra (the algebra is event-homogeneous and T-invariant); they require importing additional event and orientation data.

*Conclusion.* The McGucken Sphere Σ₊(p) as a point-set in Minkowski Space 𝕄_(1,3) is not derivable from the Algebraic Channel’s algebraic apparatus alone. Any candidate Π_B reconstruction must import non-algebraic geometry (a marked event, an orientation choice, a Dirac operator, or equivalent) to recover the Sphere. ∎

The geometry-blindness is an obstruction independent of the sign-blindness obstruction. Even if Lemma 16.3.1’s sign-blindness were resolved (e.g., by importing the Spectrum Condition to break the +ic ↔ -ic symmetry), the geometry-blindness obstruction remains: The Algebraic Channel would still need to reconstruct the Sphere as a point-set, which requires additional non-algebraic input.

#### Theorem 16.3 (Content Asymmetry) — main statement

**Theorem 16.3 (Content Asymmetry).** *The channel projection Π_A : 𝓑 → 𝓐 exists as a constructive forgetful functor. The inverse channel projection Π_B : 𝓐 → 𝓑 does not exist — there is no constructive functor from the Algebraic Channel’s content alone to dx₄/dt = ic Geometric Channel’s full content. Any candidate Π_B requires importing either (a) the Spectrum Condition or its equivalent (the +ic orientation expressed algebraically), which is not a theorem of 𝓐 (Lemma 16.3.1); or (b) a geometric-reconstruction theorem requiring additional non-algebraic input (Lemma 16.3.2).*

*Algebraic Channel’s content equals Π_A(𝓑) (the T-invariant projection of the dx₄/dt = ic Geometric Channel’s geometry); The dx₄/dt = ic Geometric Channel’s content properly contains Algebraic Channel’s content. The T-anti-invariant residue 𝓑 setminus Π_A(𝓑) — the +ic orientation, the six aligned arrows of time, the strict Second Law, the matter-dominance / baryon-asymmetry direction, the retarded-causation direction, the Wick-rotation convergent sign, and the McGucken Sphere as geometric point-set — exists in 𝓑 but not in 𝓐.*

**Proof of Theorem 16.3.**

We establish the forward existence of Π_A, then prove the impossibility of Π_B via the two lemmas.

*Step 1 (Π_A exists constructively).* The forgetful functor Π_A : 𝓑 → 𝓐 is defined in §16.2 as restriction to the T-invariant subalgebra, equivalently as the projection X ↦ 1/2(X + T X T⁻¹) on dx₄/dt = ic Geometric Channel’s geometry extended to the algebra of automorphisms. The constructive realisation of Π_A is the cogeneration cascade of Theorem 16.1: 𝓜_G → 𝕄_(1,3) → 𝓥 → 𝓗 produces the Hilbert space arena from the dx₄/dt = ic Geometric Channel’s geometry, with the natural operator algebra on Hilbert space 𝓗 being the T-invariant algebraic image of the Sphere geometry. The McGucken Sphere Σ₊(p) projects to the Lorentzian metric η_(μν) (the null-cone structure with the orientation +ic forgotten); the pointwise McGucken operator 𝓕ₚ = ∂ₜ + ic ∂_(x₄)|ₚ projects to the unitary evolution U(t) = e^(-iĤt/ħ) with the time-direction of Ĥ forgotten; the principle’s perpendicularity projects to the canonical commutator [q̂, p̂] = iħ; the x₄-flux conservation projects to Noether’s first theorem’s conservation laws. The projection is constructive at every step.

*Step 2 (Π_B does not exist by Lemma 16.3.1).* Suppose for contradiction that Π_B : 𝓐 → 𝓑 exists as a constructive functor. Then Π_B must produce the McGucken Sphere Σ₊(p) from the Algebraic Channel’s content alone. The Sphere has definite orientation: TΣ₊(p) = Σ₋(p) with Σ₊(p) ≠ Σ₋(p). To distinguish Σ₊(p) from Σ₋(p), Π_B must break the +ic ↔ -ic symmetry. By Lemma 16.3.1, Algebraic Channel’s apparatus is contained in the T-invariant subalgebra: every element of 𝓐₀ is preserved by the involution. Therefore no algebraic structure in 𝓐 breaks the symmetry. Any candidate Π_B must import the symmetry-breaking content (the Spectrum Condition or equivalent) from outside 𝓐. This is the first obstruction.

*Step 3 (Π_B does not exist by Lemma 16.3.2).* Even granted the orientation (by importing the Spectrum Condition), the second obstruction holds. The McGucken Sphere Σ₊(p) is a specific point-set in Minkowski Space 𝕄_(1,3). By Lemma 16.3.2, Σ₊(p) is not derivable as a point-set from 𝓐’s algebraic apparatus alone. Reconstruction requires additional non-algebraic input (commutativity, regional structure, Dirac operator, or marked event). This is the second obstruction, independent of Step 2’s sign-blindness obstruction.

*Conclusion.* Both obstructions independently block the existence of a constructive Π_B : 𝓐 → 𝓑. The forward projection Π_A exists; the inverse projection does not. ∎

Algebraic Channel is the constructive forgetful image of the dx₄/dt = ic Geometric Channel under Π_A; dx₄/dt = ic Geometric Channel is the source. The relation is image-source asymmetric, not symmetric sibling-sibling. The 47-theorem dual catalog is the catalog of objects T such that T ∈ Π_A(𝓑) ∩ 𝓐 — i.e., T sits in the image of Π_A and is also independently constructible within 𝓐 (which is why each theorem has two derivations: the dx₄/dt = ic Geometric Channel route through the Sphere and the Algebraic Channel route through the algebra). The mono-channel catalog is the catalog of T ∈ 𝓑 setminus Π_A(𝓑) — objects whose orientation is killed by Π_A and therefore have no Algebraic Channel derivation.

Lemma 16.3.1 and Lemma 16.3.2 establish two distinct facts about 𝓐:

- Lemma 16.3.1 is about the *automorphisms of 𝓐*: every element of 𝓐₀ is fixed by the T-involution, so the involution is an automorphism of 𝓐₀.
- Lemma 16.3.2 is about the *objects representable by 𝓐*: the McGucken Sphere as a point-set is not an algebraic object and is not derivable from algebraic data alone.

The two obstructions are independent in the sense that resolving one does not resolve the other. Importing the Spectrum Condition resolves the sign-blindness (Lemma 16.3.1) but leaves the geometry-blindness (Lemma 16.3.2) standing — the Spectrum Condition gives orientation but not the Sphere’s point-set content. Importing a Dirac operator resolves the geometry-blindness (Lemma 16.3.2) but leaves the sign-blindness (Lemma 16.3.1) standing — the Dirac operator alone does not pick out which orientation is “future.” Both lemmas must be addressed independently to construct Π_B, and each requires importing content not present in 𝓐.

### 16.7 Corollary 16.4: Dual derivation iff T-invariance

**Corollary 16.4 (Dual-derivation availability iff T-invariance of mathematics).** For any framework theorem T_(th):

*(i) If T_(th)’s mathematics is T-invariant* (sign-blind on +ic, i.e., T_(th) = Π_A(T_(th))), then T_(th) has both an Algebraic Channel derivation (using only algebra, never invoking the Sphere) and a dx₄/dt = ic Geometric Channel derivation (using full geometry), and the two derivations share no intermediate machinery (convergent overdetermination in Wimsatt’s 1981 sense).

*(ii) If T_(th)’s mathematics is T-anti-invariant* (depends on the sign of +ic, i.e., T_(th) ≠ Π_A(T_(th))), then T_(th) ∈ 𝓑 setminus Π_A(𝓑) — T_(th) has no Algebraic Channel derivation, by the impossibility that the sign distinguishing T_(th) from Π_A(T_(th)) has been projected away.

**The 47-theorem dual-channel catalog of [19 §IX.26] is therefore the catalog of T-invariant framework content; the mono-channel catalog (enumerated in §16.12 below) is the catalog of T-anti-invariant framework content. The dual-derivation count is the catalog of which theorems sit in the image of Π_A.**

**Proof.** (i) Suppose T_(th) is T-invariant. Then T_(th) ∈ Π_A(𝓑) by definition of Π_A as restriction to the T-invariant subalgebra. Therefore T_(th) has an Algebraic Channel derivation via the algebraic-apparatus apparatus (the derivation route 1925–1957 historical record demonstrates that the sign-blind apparatus reaches T-invariant structure). T_(th) also has a dx₄/dt = ic Geometric Channel derivation via the geometric apparatus (the Sphere, Huygens, cogeneration cascade). The two derivations share no intermediate machinery because the Algebraic Channel derivation never invokes the Sphere and the dx₄/dt = ic Geometric Channel derivation never invokes the operator algebra as primitive input (Theorem 16.1).

(ii) Suppose T_(th) is T-anti-invariant: T(T_(th)) = -T_(th) (with appropriate operator-algebra-internal sign convention) or T(T_(th)) ≠ T_(th) in general. Then Π_A(T_(th)) = 1/2(T_(th) + T T_(th) T⁻¹) = 0 (or, more generally, ≠ T_(th)). Therefore T_(th) is removed (or partially removed) by Π_A, and T_(th) ∉ Π_A(𝓑). By Theorem 16.3, the inverse Π_B does not exist; there is no Algebraic Channel construction reaching T_(th). ∎

### 16.8 Corollary 16.5: Mathematics vs. physical instantiation

**Corollary 16.5 (Mathematics vs. physical instantiation).** Every framework theorem T_(th) has two readings:

*(i) Mathematics*: the formal equation or statement that T_(th) asserts. This content may be T-invariant (dual-channel by Corollary 16.4) or T-anti-invariant (mono-channel dx₄/dt = ic Geometric Channel by Corollary 16.4).

*(ii) Physical instantiation*: the realisation of T_(th) in a physical event or process in the universe. This instantiation is *always* T-anti-invariant, because physical processes happen at +ic (the universe runs in the future direction, the Sphere expands outward, measurements happen forward in time, decoherence is monotonic). All physical instantiation lives in the dx₄/dt = ic Geometric Channel.

Even framework theorems with T-invariant mathematics have T-anti-invariant physical instantiation. Specifically:

- *Born rule equation P = |ψ|².* T-invariant mathematics (|ψ|² = ψ^*ψ is PT-symmetric on i). Dual-channel mathematics. *Physical instantiation*: head-on McGucken-Sphere collision at the future detection event (Theorem 7.7 of the present paper). dx₄/dt = ic Geometric Channel physical instantiation.

- *Einstein field equations G_(μν) = (8π G/c⁴) T_(μν).* T-invariant mathematics (the equations admit both expanding and contracting solutions). Dual-channel mathematics: Lovelock 1971 variational uniqueness on the McGucken-generated background (Algebraic Channel) and Jacobson 1995 thermodynamic Clausius-relation reading with x₄-stationary modes on local Rindler horizons (dx₄/dt = ic Geometric Channel). *Physical instantiation*: cosmic expansion (H₀ > 0), black-hole formation, gravitational-wave propagation outward. dx₄/dt = ic Geometric Channel physical instantiation.

- *Unitary evolution U(t) = e^(-iĤt/ħ).* T-invariant mathematics (U(-t) = U(t)⁻¹). Dual-channel mathematics. *Physical instantiation*: decoherence (off-diagonal density-matrix elements decay monotonically); the universe’s branch structure (decoherent histories accumulate forward in time). dx₄/dt = ic Geometric Channel physical instantiation.

- *Wick rotation τ = -it as coordinate identification.* T-invariant mathematics (the identification works algebraically in both directions). Dual-channel as a formal device. *Physical instantiation*: measurement as physical Wick rotation (Theorem 12.2 of the present paper); apparatus-performed rotation has the convergent sign t → -iτ, not +iτ. dx₄/dt = ic Geometric Channel physical instantiation.

- *Maxwell’s equations.* T-invariant mathematics (admit both retarded and advanced solutions symmetrically). Dual-channel mathematics. *Physical instantiation*: radiation propagates outward (retarded Green’s function privileged); no inward-converging radiation is observed. dx₄/dt = ic Geometric Channel physical instantiation.

- *CPT theorem as algebraic statement.* T-invariant mathematics (Pauli-Lüders theorem proves CPT from Lorentz invariance + locality + Hermitian Hamiltonian, all sign-blind). Dual-channel mathematics. *Physical instantiation*: the universe is matter-dominated, with C and P and T individually violated, with CPT exact — this is the +ic-dominant configuration of cosmic baryogenesis. dx₄/dt = ic Geometric Channel physical instantiation.

- *Huygens’ Principle.* T-invariant mathematics (the envelope construction is geometrically symmetric: secondary wavelets in either time direction reconstruct the wavefront). Dual-channel mathematics. *Physical instantiation*: secondary wavelets propagate at +ic, not -ic; the recursion goes forward in time. dx₄/dt = ic Geometric Channel physical instantiation.

**The pattern is**: the mathematics of a theorem may be T-invariant or T-anti-invariant; the physical instantiation of any theorem (symmetric or asymmetric mathematically) is *always* T-anti-invariant because the universe runs at +ic.

**Moral**: the dual-channel architecture catalogs T-invariant *mathematics*; the mono-channel catalog enumerates both T-anti-invariant mathematics *and* the physical instantiation of all content (symmetric or asymmetric mathematically). The latter is the larger catalog because every framework theorem has physical instantiation, and all physical instantiation is dx₄/dt = ic Geometric Channel.


### III.4 The two channels as the two positions relative to the dx₄/dt = ic wavefront

The McGucken Principle dx₄/dt = ic predicts that the four-velocity budget v² + v_(x₄)² = c² has exactly two endpoint configurations relative to the wavefront — the transverse position at spatial rest, through which the Sphere passes, and the co-moving position at v = c, which rides the Sphere — and that the two channels are what these two positions report. The transverse position reports the four invariants of the passage and hence the conservation laws; the co-moving position inherits the wavefront's delocalization and reports only the Born density. The kinematic definitions and the conservation-law theorem are §9.5.13 of [1], reproduced here. (In the v199 text of [1] the subsection contains Definitions 9.5.13.1–9.5.13.2 and Theorem 9.5.13.1; the co-moving-position Born theorem and the complementarity theorem numbered 9.5.13.3 in the abstract of [1] are not present in the v199 body.)


#### 9.5.13 The two channels as two positions relative to the dx₄/dt = ic wavefront: conservation laws from the transverse position, quantum probability from the co-moving position, and the derivation of complementarity

Section 9.5.12 established what the two channels describe. The present subsection establishes *why there are two*: they are two positions relative to one and the same wavefront. The positions are defined kinematically, by the four-velocity budget of Lemma 2.5, and carry no psychological or observer-dependent content.

**Definition 9.5.13.1 (Transverse position).** *A system is in the* transverse position *relative to the dx₄/dt = ic wavefront at an event p ∈ Minkowski Space 𝕄_(1,3) if it is at spatial rest at p, so that by the bounded four-velocity-budget partition v² + v_(x₄)² = c² (per coordinate time t, §2.3; Lemma 5.1.3.2), with v_(x₄) ≡ √(c² - v²) the Sphere-tangent share, its entire budget share is spent on x₄-advance: v = 0, hence v_(x₄) = c, while the Principle dx₄/dt = ic holds at this event as at every event. The wavefront expands* through *such a system; the system is traversed by the expansion, not carried by it. This is ontology clause (1) of the four-fold ontology (§2.4): absolute rest in x₁x₂x₃.*

**Definition 9.5.13.2 (Co-moving position).** *A system is in the* co-moving position *relative to the dx₄/dt = ic wavefront if it propagates on the wavefront itself: v = c, whence by the same bounded partition v² + v_(x₄)² = c² its Sphere-tangent share vanishes, v_(x₄) = 0 — the system takes no share in the x₄-advance and accumulates no shadow X₄, riding the null worldline of the expansion, while the Principle dx₄/dt = ic holds at its events as at every event (the share v_(x₄), not the coordinate rate dx₄/dt, is what vanishes; dτ = 0 pointwise and the affine null tangent dx^μ/dλ replaces the four-velocity). This is ontology clause (2) of the four-fold ontology (§2.4). Such a system inherits the expansion’s delocalization: it has no position on the front, only a support.*

**Theorem 9.5.13.1 (Conservation laws as the invariants of the passage; the transverse position).** *A system in the transverse position measures those features of the dx₄/dt = ic expansion that do not change as the expansion passes through it. These are exactly four, and they are exactly the invariants of the McGucken Sphere:*

c (rate), ω_C = mc²/ħ (frequency), λ_C = h/mc (wavelength), Δ S = h (action per tick).

*The symmetries of the passage, and the conservation laws they force by Noether’s theorem, are:*

- ***Temporal uniformity** of the expansion (the rate is ic at all times) ⇒ time-translation symmetry ⇒ **conservation of energy**.*
- ***Spatial homogeneity** of the expansion (the Sphere at any spatial point is identical to the Sphere at any other) ⇒ spatial-translation symmetry ⇒ **conservation of momentum**.*
- ***Spherical symmetry** of the expansion (no preferred direction) ⇒ rotational symmetry ⇒ **conservation of angular momentum**.*
- ***Phase uniformity** of the expansion (constant rate, no preferred phase origin) ⇒ global U(1) symmetry ⇒ **conservation of charge**.*

*The full derivation of each conservation law from the corresponding symmetry of the x₄-expansion now follows. The extended treatment, with the same result reached through the Huygens-wavefront construction, is developed in* [14] *§VI.3 (energy), §VI.4 (momentum), §VI.5 (angular momentum), and §VI.6 (charge); the self-contained derivation given here uses Noether’s first theorem applied directly to the McGucken action.*

*Proof.* Let ψ be the McGucken wavefunction (Definition 2.6) propagating on the Sphere wavefront, and let S[ψ] = ∫_(𝓜_G) 𝓛 d⁴x be the McGucken action, with 𝓛 = 𝓛(ψ, ∂_μ ψ) the McGucken Lagrangian on Minkowski Space 𝕄_(1,3) (§5.1.8; the action principle itself descends from dx₄/dt = ic through the stationary-phase reading of the propagator, Theorem 4.3.4). 𝓛 depends on the coordinates only through ψ and ∂_μψ, because the x₄-expansion that generates it has the same rate ic at every event (R1, universality clause of Theorem 2.4): the Lagrangian carries no explicit dependence on t, on x, on orientation, or on the phase origin of ψ. Each such absence is a continuous symmetry, and Noether’s first theorem converts each into a conserved current j^μ with ∂_μ j^μ = 0, whence the charge Q = ∫_(Σₜ) j⁰ d³x is constant in t. We take the four symmetries in turn.

*(i) Temporal uniformity ⇒ energy.* The rate is ic at all times (R1), so ∂ 𝓛/∂ t = 0 at fixed (ψ, ∂_μψ). The infinitesimal time translation t → t + ε, δψ = -ε ∂ₜψ, leaves S invariant. Noether’s theorem gives the conserved current whose time component is the Hamiltonian density 𝓗 = (∂𝓛/∂(∂ₜψ)) ∂ₜψ - 𝓛, and E = ∫_(Σₜ)𝓗 d³x satisfies dE/dt = 0: **conservation of energy**.

*(ii) Spatial homogeneity ⇒ momentum.* The Sphere at any spatial point is identical to the Sphere at any other, so ∂𝓛/∂ xⁱ = 0, i = 1,2,3. The infinitesimal space translation xⁱ → xⁱ + εⁱ, δψ = -εⁱ ∂ᵢψ, leaves S invariant. Noether’s theorem gives the conserved momentum density with Pᵢ = -∫_(Σₜ)(∂𝓛/∂(∂ₜψ)) ∂ᵢψ d³x and dPᵢ/dt = 0: **conservation of momentum**.

*(iii) Spherical symmetry ⇒ angular momentum.* The expansion has no preferred direction (the McGucken Sphere is isotropic, carrying the SO(3)-invariant Haar measure, §7). Under the infinitesimal rotation xⁱ → xⁱ + ε ωⁱⱼ xʲ with ω antisymmetric, δψ = -ε ωⁱⱼ xʲ ∂ᵢψ, S is invariant. Noether’s theorem gives the conserved angular-momentum tensor M⁰ᵢⱼ = ∫_(Σₜ)(xᵢ T⁰ⱼ - xⱼ T⁰ᵢ) d³x with T^μ_ν the stress tensor of steps (i)–(ii), and dMᵢⱼ/dt = 0: **conservation of angular momentum**.

*(iv) Phase uniformity ⇒ charge.* A universal x₄-shift is unobservable (the expansion has constant rate and no preferred phase origin; this is the same universality that supplies Born-rule condition R3, §7.5). The global U(1) transformation ψ → e^(iθ)ψ, δψ = iθ ψ, leaves 𝓛 invariant because 𝓛 depends on ψ only through the modulus-forming pairing (ψ,ψ^*) fixed by the rank-2 metric (Lemma 2.5) and the conserved quadratic density (Lemma 7.1). Noether’s theorem gives the conserved current j^μ = i[(∂𝓛/∂(∂_μψ)) ψ - ψ^*(∂𝓛/∂(∂_μψ^*))], and Q = ∫_(Σₜ) j⁰ d³x satisfies dQ/dt = 0: **conservation of charge**.

Each of the four symmetries is a property of the x₄-expansion itself — its uniformity in time, its homogeneity in space, its isotropy, and its phase-origin-independence — so each conservation law descends from dx₄/dt = ic through Noether’s theorem applied to the McGucken action, with no conservation law postulated independently. The present theorem adds the identification: these are the invariants extracted by a system standing *transverse* to the passage of the wavefront. Conservation laws are what the dx₄/dt = ic expansion looks like to a system it passes through.* ∎


### III.5 Why the Algebraic Channel dominated history and why the Geometric Channel is primary

The McGucken Principle dx₄/dt = ic predicts the order in which the two channels could be discovered: the Algebraic Channel is reachable from operator algebra and Stone–von Neumann uniqueness without the Principle, whereas the Geometric Channel requires the Principle to derive the Sphere wavefront as a theorem. Born's 1926 move — reading ψ as a probability amplitude rather than as Schrödinger's physical wave — is the moment at which the Geometric Channel of the wavefunction was projected away and the Algebraic Channel reading of the Born rule became the only reading available for a century. Sections 6.6.5.1–6.6.5.3 of [1] are reproduced here.


### 6.6.5 The historical-foundational inversion: why the Algebraic Channel dominated history and why the dx₄/dt = ic Geometric Channel is foundationally primary

The §6.4 (Algebraic Channel) and §6.4.5 (dx₄/dt = ic Geometric Channel) derivations both produce the same Hilbert space 𝓗 ≅ L²(ℝ³, d³x), with the convergence catalogued in §6.4.6 and the Sphere-role table of §6.4.7 showing that both chains rest on McGucken-Sphere geometry. By every criterion of the McGucken framework, however, **the dx₄/dt = ic Geometric Channel is the foundationally primary route** — and by every criterion of historical record, **the Hilbert space was actually arrived at via the Algebraic Channel**. These two answers are opposite, and the disagreement is the precise signature of what the McGucken Principle dx₄/dt = ic supplies that the prior tradition lacked. The present subsection resolves the apparent paradox via the projection-theorem reading of §16, then catalogues ten prior traditions that attempted Geometric-Channel-style derivations and identifies the specific foundational gap that prevented each of them from completing the construction.

#### 6.6.5.1 The dx₄/dt = ic Geometric Channel is primary

Six criteria identify the dx₄/dt = ic Geometric Channel (§6.4.5) as the foundationally primary route:

*(1) Primitive vectors are physical, not abstract.* The dx₄/dt = ic Geometric Channel begins with McGucken-Sphere wavefronts ψ_E as the primitive vectors of the construction (Step 1 of §6.4.5) — physical wavefronts from definite source events, each carrying the full +ic-oriented content of the McGucken Sphere. The Algebraic Channel begins with an abstract Hilbert space carrying a representation of the canonical commutator algebra, with the abstract space identified as L²(ℝ³) only through Stone-von Neumann’s uniqueness theorem in Step 6. The dx₄/dt = ic Geometric Channel’s primitive vectors are objects; the Algebraic Channel’s are placeholders later filled in by a uniqueness theorem.

*(2) The inner product has direct geometric meaning.* The dx₄/dt = ic Geometric Channel inner product ⟨ φ, ψ ⟩ = ∫ φ^* ψ d³ x (Step 3 of §6.4.5) is the literal pointwise overlap of two Sphere wavefronts at each spatial-slice point, integrated over the slice — the geometry of “two Sphere wavefronts simultaneously present at the same spatial point”. The Algebraic Channel inner product is the abstract invariant pairing on the unique irreducible Stone-von Neumann representation, with no direct physical meaning until the representation is identified.

*(3) Each pre-Hilbert axiom traces to a specific upstream Sphere-geometric theorem.* The dx₄/dt = ic Geometric Channel inherits sesquilinearity from Lemma 7.1 (the quadratic density conserved under the Sphere’s expansion), conjugate symmetry from Theorem 7.11 (PT-symmetry of Sphere through source event), and positive-definiteness from Theorem 7.4 (Born density as Sphere overlap) — each axiom is supplied by an established Sphere-geometric theorem (Step 4 of §6.4.5). The Algebraic Channel inherits all three indirectly through Stone-von Neumann’s “invariant pairing” — true but downstream of an abstract representation theorem, not derived from upstream geometry.

*(4) The +ic orientation is preserved.* The dx₄/dt = ic Geometric Channel carries the full +ic-oriented content of the McGucken Sphere through every step. The Algebraic Channel is sign-blind on +ic: the CCR [q̂, p̂] = iħ is preserved under the involution T: i → -i together with ħ → -ħ (Lemma 16.3.1), and Stone-von Neumann’s uniqueness theorem treats +iħ and -iħ symmetrically. By Corollary 16.4, the Algebraic Channel is the T-invariant projection Π_A of the dx₄/dt = ic Geometric Channel — the +ic orientation is projected away into the sign-blind operator algebra.

*(5) Strip-the-Sphere test reveals both channels are Sphere-grounded, with different depth of grounding.* Strip the Sphere from the dx₄/dt = ic Geometric Channel and the primitive vectors ψ_E vanish — no construction at all. Strip the Sphere from the Algebraic Channel and Theorem 5.1’s derivation of the CCR collapses (no Sphere → no x₄-perpendicularity → no i in iħ; no Sphere → no x₄-oscillation → no ħ in iħ) — the algebraic input also vanishes. Both routes are Sphere-grounded, but the Algebraic Channel’s Sphere-dependence is *hidden one cascade level beneath operator algebra*, whereas the dx₄/dt = ic Geometric Channel’s Sphere-dependence is *explicit at every step*. The Algebraic Channel is the algebraic presentation of the same Sphere; the dx₄/dt = ic Geometric Channel is the direct geometric presentation.

*(6) Cascade-level continuity with the manifold Minkowski Space 𝕄_(1,3).* By Theorem 10.6 (the Hilbert-Minkowski identity), the Hilbert space and the Minkowski manifold are two presentations of the same geometric object — the constraint surface where dx₄/dt = ic holds locally. The Geometric Channel makes this continuity visible: Sphere wavefronts are functions on Minkowski Space 𝕄_(1,3), the Hilbert space is the function-space rendering of the same manifold, the spatial slice carries the inner product as direct integration over the manifold’s spatial slice. The Algebraic Channel obscures the continuity: the manifold disappears into the abstract Heisenberg-algebra representation, and only Stone-von Neumann’s uniqueness recovers the spatial slice as the configuration-space domain of the multiplication operator.

By every criterion, the dx₄/dt = ic Geometric Channel is foundationally primary; the Algebraic Channel is its T-invariant projection Π_A.

#### 6.6.5.2 The Hilbert space historically arrived via the Algebraic Channel

The historical trajectory is exactly the reverse of the ordering. Quantum mechanics arrived at the Hilbert space *algebraically*, with the geometry suppressed at every step:

*(i) Heisenberg’s matrix mechanics (1925).* Heisenberg’s “Über quantentheoretische Umdeutung kinematischer und mechanischer Beziehungen” (*Zeitschrift für Physik* 33, 879–893) started from observable algebra and the multiplication table of position and momentum — purely algebraic, no wavefunction, no geometry. The first arrival at the operator-algebra structure that would later be recognized as the Heisenberg algebra mathfrakh₃.

*(ii) Born–Jordan formalization (1925).* “Zur Quantenmechanik” (*ZP* 34, 858–888) derived the canonical commutation relation [q̂, p̂] = iħ explicitly as the algebra of Heisenberg’s multiplication table. Algebraic.

*(iii) Born–Heisenberg–Jordan, the* Drei-Männer-Arbeit *(1926).* “Zur Quantenmechanik II” (*ZP* 35, 557–615) extended matrix mechanics to a complete algebraic framework. Algebraic.

*(iv) Schrödinger’s wave mechanics (1926, four papers).* The only historically Geometric-Channel-like development: Schrödinger derived the wave equation from de Broglie’s wave-particle duality, with ψ as a wavefunction satisfying a PDE on spacetime (“Quantisierung als Eigenwertproblem”, I–IV, *Annalen der Physik* 79–81). Critically, however, *Schrödinger had no foundational geometric principle* from which to derive ψ. He guessed at the wave equation by promoting the classical Hamilton-Jacobi equation through Hamilton’s 1828 optical-mechanical analogy. The wavefunction ψ was an *input* to the theory, but without a dx₄/dt = ic Geometric Channel *foundation*. Schrödinger himself misinterpreted ψ as a physical charge density spread over space (the “matter wave” reading), which was empirically wrong.

*(v) Born’s probabilistic interpretation (1926).* “Zur Quantenmechanik der Stoßvorgänge” (*ZP* 37, 863–867). Born proposed |ψ|² as the probability density of finding the particle at a position. This single move **demoted ψ from a physical wave to a probability amplitude** — projecting away precisely the geometry that Schrödinger’s wave mechanics carried. After Born, ψ was no longer a wavefront on spacetime; it was a calculational device for computing probabilities, and the only fact about it that mattered was the abstract structure |ψ|² d³x as a probability measure.

*(vi) Schrödinger’s equivalence proof (1926).* “Über das Verhältnis der Heisenberg-Born-Jordanschen Quantenmechanik zu der meinen” (*AdP* 79, 734–756). Schrödinger proved that wave mechanics and matrix mechanics give the same predictions. Crucially, this proof was unidirectional in influence: it cemented matrix mechanics as the “real” theory and wave mechanics as “one representation of it”, rather than the reverse.

*(vii) Dirac’s transformation theory (1925–1930).* Culminating in *Principles of Quantum Mechanics* (Oxford, 1930), Dirac built the abstract framework of state vectors and operators on an abstract Hilbert space. The wavefunction became one possible representation of an abstract state vector. Algebraic and representational throughout.

*(viii) Stone’s theorem and von Neumann’s uniqueness (1930–31).* Stone, “Linear transformations in Hilbert space III” (*Proc. Nat. Acad. Sci.* 16, 172–175); von Neumann, “Die Eindeutigkeit der Schrödingerschen Operatoren” (*Mathematische Annalen* 104, 570–578). The Weyl form of the CCR has a unique irreducible separable representation up to unitary equivalence — namely L²(ℝⁿ) with the Schrödinger representation. **This is the moment the Algebraic Channel completed.** From the Heisenberg algebra alone, the Hilbert space was forced to be L² — no geometric input required, no wave-mechanical reading needed.

*(ix) Von Neumann’s axiomatic codification (1932).* *Mathematische Grundlagen der Quantenmechanik* (Springer). Axiomatic formalization of QM in Hilbert space language. The Hilbert space became *the* foundational object of quantum mechanics. The wavefunction ψ was deemphasized as an element of an abstract Hilbert space; the operator algebra became central. **This was the canonical Algebraic Channel arrival.**

*(x) Feynman’s path integral (1948).* “Space-time approach to non-relativistic quantum mechanics” (*Rev. Mod. Phys.* 20, 367–387). Reconstructed QM from path-summation amplitudes ψ = ∑_γ exp(iS[γ]/ħ). This is the *closest historical predecessor to the dx₄/dt = ic Geometric Channel* — ψ as a path-integral kernel on spacetime, with phase from action, with Huygens-like superposition over paths. Feynman supplied no upstream geometric principle for the action S or the phase exp(iS/ħ); the path-integral formulation was equivalent to the canonical formulation (Dyson’s later equivalence proof), not foundational to it.

The historical pattern shows consistent **algebraic dominance with geometric demotion**: at every juncture where a Geometric-Channel-like reading was available, it was demoted in favor of an Algebraic-Channel reading. Schrödinger’s wave mechanics was demoted to a representation of matrix mechanics; Schrödinger’s physical-wave reading of ψ was demoted to Born’s probability amplitude; von Neumann’s axiomatization enshrined Hilbert space as primitive with ψ as element; Feynman’s path integral was presented as equivalent reformulation, not foundational.

The reason is twofold. **First, historical contingency**: Heisenberg published first by a few months, the Copenhagen interpretation emphasized measurement and operator algebra over wave, and von Neumann’s 1932 axiomatization solidified the Algebraic Channel as the foundational framework before wave-mechanical content could be developed into a geometric foundation. **Second, inaccessibility**: the dx₄/dt = ic Geometric Channel requires an upstream principle from which Sphere wavefronts can be derived. Without such a principle, ψ has to be guessed at (Schrödinger) or postulated (Feynman path integral). The Algebraic Channel could proceed without any geometric grounding — just algebra, representations, and Stone-von Neumann uniqueness — so it was the path of least resistance for a century.

#### 6.6.5.3 The McGucken inversion via the projection theorem (cross-reference to §16)

The McGucken dx₄/dt = ic framework supplies what was missing for a hundred years: a foundational principle (dx₄/dt = ic) from which the Sphere wavefront is a theorem (not an input), the Hilbert space is a theorem (Theorems 6.1 and 6.1.5), the Born rule is a theorem (Theorem 7.2), the CCR is a theorem (Theorem 5.1), and the Schrödinger equation is a theorem (Theorems 9.0.5 and 9.1). This converts the dx₄/dt = ic Geometric Channel from a side-stream of historical wave mechanics — wave without foundation — into the foundational route, with the Algebraic Channel recovered as its T-invariant projection Π_A (the algebraic shadow that history privileged because the foundational principle was missing).

The projection-theorem reading of §16 supplies the precise resolution of the apparent paradox:

*Foundational ordering*: dx₄/dt = ic Geometric Channel is primary because it carries the full +ic-oriented content of the McGucken Sphere; Algebraic Channel is the T-invariant projection Π_A of the dx₄/dt = ic Geometric Channel (Lemma 16.3.1, Corollary 16.4), with +ic orientation projected away.

*Historical ordering*: The Algebraic Channel (the projection Π_A) was accessible without the foundational principle dx₄/dt = ic, because the algebra of operators carries enough structure (Stone-von Neumann uniqueness) to fix the representation. The dx₄/dt = ic Geometric Channel (the unprojected source) requires dx₄/dt = ic to derive Sphere wavefronts as theorems. Without dx₄/dt = ic, history could only access the projection.

*The orthodox foundational confusion* (§16.17) is the canonical case of treating the algebraic shadow as the source: ninety-four years of foundational reconstructions all operated within the Algebraic Channel, treating Hilbert space as ontologically primitive when it is in fact the function-space rendering of the McGucken-derived Minkowski manifold (Theorem 10.6) — the algebraic shadow Π_A of the Sphere’s geometry, mistaken for the source for a century.

So: the natural answer (Geometric is more natural and fuller) and the historical answer (Algebraic was the route taken) are *both* correct, and their disagreement is the precise signature of what dx₄/dt = ic provides that the prior tradition lacked. History followed the projection because the source was inaccessible without the foundational principle. With dx₄/dt = ic in place, the source becomes derivable and the historical ordering reverses.


## Part IV. The McGucken Principle dx₄/dt = ic reading of the century of Born-rule derivations, 1926–2025

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts that every derivation of the Born rule conducted inside a Hilbert space taken as primitive must import, somewhere, the content of the rule it sets out to derive, because the Hilbert space, the sesquilinear pairing and the unitary group are themselves theorems of the Principle (Theorems 6.1, 9.2 of [1]) and a programme that begins downstream of them has no access to the geometric fact — the rank-2 metric induced by x₄ = ict — that fixes the exponent. The sixteen-programme survey of §7.1 of [1], with a McGucken diagnostic attached to each programme, the comparison table of §7.7, the five sphere traditions of §7.7.1, and the historical account of Born's own route to the rule in §7.7.2 are reproduced verbatim and in full below. Each external derivation is followed by the McGucken reading that names the Sphere property the programme could not see.


### IV.1 Sixteen programmes, 1926–2025, with the McGucken diagnostic for each


### 7.1 History of the Born rule P(x) = |ψ(x)|²: sixteen programs surveyed including Born 1926 postulation, Gleason 1957 measure-theoretic, Deutsch-Wallace decision-theoretic, Zurek envariance, Sebens-Carroll self-locating uncertainty, Masanes-Galley-Müller operational-redundancy, Saunders branch-counting, QBism, Bohm quantum equilibrium

The Born rule P = |ψ|² is the most-derived structure in the foundations of quantum mechanics. A canonical recent survey is Lev Vaidman’s “Derivations of the Born Rule” (in *Quantum, Probability, Logic*, Springer, 2020). The history below covers fifteen major programs, with a McGucken-framework diagnostic identifying for each which aspect of dx₄/dt = ic it could not see — most especially the geometric reading of P = |ψ|² as the overlap of forward and conjugate x₄-expansions on the McGucken Sphere (Theorem 7.4).

#### 7.1.1 Born (1926): the original postulation

Max Born’s “Zur Quantenmechanik der Stoßvorgänge” (*Zeitschrift für Physik* 37, 863–867, 1926) proposed that the wavefunction ψ(x) does determines the *probability* of finding the particle at x: P(x) = |ψ(x)|². The proposal was made in a footnote added in proof; the body of the paper originally said the probability was |ψ|, with the squared modulus added on reconsideration. The rule was stated as a postulate. There was no derivation.

*McGucken diagnostic.* Born’s footnote correction from |ψ| to |ψ|² is the historical moment at which the rank-2 character of the Minkowski metric entered quantum mechanics — Born got the right answer empirically while having no derivation of why squared rather than linear. The McGucken dx₄/dt = ic framework supplies the derivation: the Minkowski metric induced by x₄ = ict is rank-2 (Lemma 2.5), the second-order propagation it induces conserves only the quadratic function of the modulus (Lemma 7.1), so bilinearity in (ψ, ψ*) is forced, and |ψ|² rather than |ψ| is the unique density satisfying the four physical requirements (R1)–(R4). Born had the rule but was blind to all four foundational features of dx₄/dt = ic that *force* the rule.

#### 7.1.2 Gleason (1957)

Andrew Gleason’s “Measures on the Closed Subspaces of a Hilbert Space” (*Journal of Mathematics and Mechanics* 6, 885–893, 1957) proved that any non-contextual probability measure on closed subspaces of a Hilbert space of dimension ≥ 3 takes the form μ(P) = tr(ρ P). The theorem derives the *form* of the rule but presupposes that probabilities live on subspaces — half of what one wished to explain. The Hilbert space and the assumption that quantum measurements correspond to subspaces are inputs.

*McGucken diagnostic.* Gleason’s theorem is one of the central results in the foundations of QM, but it operates entirely *inside* the Hilbert-space formalism. The “non-contextuality” assumption is the operational shadow of the universality of x₄-expansion from every event (the same fact that gives R3 phase invariance in the McGucken dx₄/dt = ic framework). The “closed subspaces of a Hilbert space” are the operational substrate of the rank-2 sesquilinear pairing on the McGucken-derived 𝓗. Gleason saw the algebraic structure of the rule but not its geometric origin. Blind to the perpendicularity-marker reading of i (which would have explained why the Hilbert space is complex rather than real) and to the dynamism of x₄ (which would have explained why probabilities live on subspaces of a *complex* space rather than some other structure).

#### 7.1.3 Finkelstein (1965), Hartle (1968), Farhi–Goldstone–Gutmann (1989), Van Wesep (2006), Landsman (2008): frequentist / macroscopic-observable derivations

David Finkelstein’s “The Logic of Quantum Physics” (*Transactions of the New York Academy of Sciences* 25, 621, 1965) and James Hartle’s “Quantum Mechanics of Individual Systems” (*American Journal of Physics* 36, 704–712, 1968) initiated a program of deriving the Born rule from frequentist limits — N copies of a system measured independently produce relative frequencies converging to |ψ|² in the N → ∞ limit. Edward Farhi, Jeffrey Goldstone, and Sam Gutmann’s “How Probability Arises in Quantum Mechanics” (*Annals of Physics* 192, 368, 1989) gave a more rigorous infinite-tensor-product version. Robert Van Wesep’s “Many Worlds and the Appearance of Probability in Quantum Mechanics” (*Annals of Physics* 321, 2438, 2006) and Klaas Landsman’s “Macroscopic Observables and the Born Rule” (arXiv:0804.4849, 2008) refined the program with continuous fields of C^*-algebras.

*McGucken diagnostic.* The frequentist program tries to recover the Born rule from large-N limits inside the existing formalism. It succeeds at showing internal consistency but does not derive the rule from upstream physics — the |ψ|² appears as the eigenvalue of the relative-frequency operator in the N → ∞ limit, but the structure of the operator presupposes the Born rule’s form. Blind to the geometry of |ψ|² as overlap of forward and conjugate x₄-expansions on the McGucken Sphere. The program operates two levels downstream of the geometric principle: at the level of relative-frequency limits on a Hilbert space whose structure already contains the Born rule.

#### 7.1.4 Deutsch (1999): decision-theoretic derivation

David Deutsch’s “Quantum Theory of Probability and Decisions” (*Proceedings of the Royal Society A* 455, 3129–3137, 1999) gave the first decision-theoretic derivation in the Everett interpretation: a rational agent in a quantum multiverse who maximizes expected utility, with utility computed via Born probabilities, is the unique rational agent. Deutsch’s argument has been widely discussed and widely criticized (Barnum et al. 2000, Lewis 2010, Hemmo–Pitowsky 2007, Rae 2009, Dawid–Thébault 2014) as circular: the equal-amplitude indifference principle that does the derivational work is essentially the Born measure already, restated as a rationality axiom.

*McGucken diagnostic.* Deutsch’s argument tries to extract the Born rule from rationality constraints on agent behavior. The McGucken diagnostic is that rationality is the wrong category for this derivation — the Born rule is a fact about the geometry of x₄-advance, not a fact about how agents should bet. Rational agents *follow* the Born rule because they live in a universe where dx₄/dt = ic holds locally at every event; they do not generate the rule by being rational. Blind to the geometric origin of the rule.

#### 7.1.5 Wallace (2003, 2010, 2012): mature Everettian decision theory

David Wallace’s *The Emergent Multiverse: Quantum Theory According to the Everett Interpretation* (Oxford, 2012) and “How to Prove the Born Rule” (in *Many Worlds?* Saunders, Barrett, Kent, Wallace, eds., Oxford, 2010) are the mature development of Deutsch’s program. Wallace’s decision-theoretic derivation is the most rigorous version of the Everettian rationality argument.

*McGucken diagnostic.* The Wallace program is the most thoroughgoing reading of the Born rule as a rationality requirement on agents within Everettian quantum mechanics. The McGucken diagnostic is the same as for Deutsch: the rule is geometric, not decision-theoretic. The “branches” of Everett are the algebraic shadow of distinct points on the McGucken Sphere where the conjugate x₄-expansion meets the apparatus — geometric, not metaphysical. Blind to the McGucken Sphere as the geometric ground of branch structure.

#### 7.1.6 Zurek (2003, 2005): envariance

Wojciech Zurek’s “Environment-Assisted Invariance, Entanglement, and Probabilities in Quantum Physics” (*Physical Review Letters* 90, 120404, 2003) and “Probabilities from Entanglement, Born’s Rule p_k = |ψ_k|² from Envariance” (*Physical Review A* 71, 052105, 2005) propose envariance: probabilities are derived from the symmetries of entangled system-environment states. Elegant, but assumes a tensor-product structure and a preferred system/environment cut, both of which are themselves substantial inputs.

*McGucken diagnostic.* Envariance is one of the most physically motivated derivations of the Born rule because it grounds probability in symmetry rather than rationality. The McGucken diagnostic is that the symmetry Zurek exploits — the swap symmetry between system and environment states with equal amplitudes — is the operational shadow of the universality of x₄-expansion from every event (the same fact that gives R3 phase invariance and underlies Gleason’s non-contextuality). The system/environment tensor-product structure is the operational shadow of independent constraint surfaces in Minkowski space 𝕄_(1,3) for spacelike-separated subsystems (Corollary 11.6). Zurek’s program operates at the level of the tensor product without seeing the geometric ground of why such products exist. Blind to the universality clause of dx₄/dt = ic as the source of envariance.

#### 7.1.7 Bohm (1952) and Valentini–Westman (2005): quantum equilibrium

David Bohm’s “A Suggested Interpretation of the Quantum Theory in Terms of ‘Hidden’ Variables I, II” (*Physical Review* 85, 166–179, 180–193, 1952) introduced the Bohmian (pilot-wave) interpretation with |ψ|² as the equilibrium distribution of particle positions. Antony Valentini and Hans Westman’s “Dynamical Origin of Quantum Probabilities” (*Proceedings of the Royal Society A* 461, 253–272, 2005) gave dynamical-relaxation arguments showing |ψ|² as the typical distribution under Bohmian guidance dynamics.

*McGucken diagnostic.* The Bohmian program puts |ψ|² in the foundational guidance equation as the equivariant measure. The Valentini–Westman relaxation arguments show that the equivariant measure is dynamically natural, but the *form* |ψ|² is stipulated through the guidance equation, not derived from upstream physics. The McGucken diagnostic is that the equivariant measure on configuration space is the operational shadow of the rank-2 metric pairing on the McGucken Sphere — the squaring comes from the rank-2 character of the metric induced by x₄ = ict, not from the equivariance of a hidden-variable dynamics. Blind to the rank-2 metric as the geometric ground of squaring.

#### 7.1.8 Sebens–Carroll (2018): self-locating uncertainty

Charles Sebens and Sean Carroll’s “Self-Locating Uncertainty and the Origin of Probability in Everettian Quantum Mechanics” (*British Journal for the Philosophy of Science* 69, 25–74, 2018) derives the Born rule from self-locating uncertainty — the observer’s uncertainty about which branch of the Everettian multiverse she occupies after a measurement but before observing the outcome.

*McGucken diagnostic.* The Sebens–Carroll argument shifts the source of probability from physical indeterminism to epistemic uncertainty about location in the multiverse. The McGucken diagnostic is the same as for Deutsch and Wallace: the rule is geometric, not epistemic. The “self-location” is the algebraic shadow of an observer worldline’s intersection with a specific event on the McGucken Sphere — geometric, not a matter of epistemic state. Blind to the geometric ground of measurement events.

#### 7.1.9 Masanes–Galley–Müller (2019): measurement postulates as operationally redundant

Lluís Masanes, Thomas Galley, and Markus Müller’s “The Measurement Postulates of Quantum Mechanics Are Operationally Redundant” (*Nature Communications* 10, 1361, 2019; arXiv:1811.11060v2) is the strongest result in the modern “quantum reconstruction” program. The paper proves that the standard measurement postulates of quantum mechanics — the Born rule and the post-measurement state-update rule — are derivable from the non-measurement postulates of the theory plus a finite-parameter assumption. Given the postulate that states are rays of a complex Hilbert space ℂ^d, that reversible transformations are unitary, and that joint pure states of composite systems are rays of the tensor-product Hilbert space, together with operational closure properties on the set of outcome probability functions and one additional assumption — *possibility of state estimation*, that a finite-dimensional system has a finite list of OPFs determining all others — the Born rule emerges as the unique probability rule consistent with the formalism. As Masanes summarizes, *“our result shows that not only is the Born rule a good guess, but it is the only logically consistent guess.”*

The technical structure of the Masanes–Galley–Müller proof is precise enough to be diagnosed exactly. The four-step argument runs:

1. *Operational primitive.* An outcome probability function (OPF) is any function f : ℙℂ^d → [0,1] giving probabilities for a single outcome on each pure state. The set F_d of OPFs is closed under mixtures, composition with unitaries, and system composition. A measurement postulate is a family {F_d, F_∞} equipped with a ⋆-product F_a × F_b → F_ab satisfying bilocality (f⋆g)(ψ⊗φ) = f(ψ)g(φ), equivariance, normalization-preservation, and **associativity** f⋆(g⋆h) = (f⋆g)⋆h.

2. *State estimation gives finite dimension.* The “possibility of state estimation” assumption — that a finite list f¹, …, f^k ∈ F_d determines all OPFs on any ensemble — combined with Lemma 2, forces the complex vector space ℂF_d generated by F_d to be finite-dimensional (Corollary 3). The U(d) action on F_d then becomes a finite-dimensional linear representation.

3. *Irrep classification.* Lemma 5 shows ℂF_d decomposes as ⊕*{j∈J} N^d_j with no repetitions, where the N^d_j are specific real SU(d) irreps (Lemma 7). Closedness under system composition then forces (Lemma 10, Corollary 11) that ℂF_d ≅ M^d_n for *all* d, with the *same* n — where M^d_n is the space of complex matrices on the symmetric subspace of (ℂ^d)^⊗n, decomposing as M^d_n = ⊕*{j=0}^n N^d_{j,n}. The quantum case is n = 1; the non-quantum case n = 2 corresponds to states represented by |ψ⟩⟨ψ|^⊗2 (the toy theory of §III.A in the paper).

4. *Associativity forces n = 1.* Theorem 18 shows that for n ≥ 2, no associative ⋆-product on M^a_n × M^b_n → M^ab_n exists. The proof is the technical heart of the paper: take a bipartite system with a = 2, b = 4, decompose M^ab_n using the symmetric projector, isolate the (n−1, 1) Young-tableau subspace, split it into “licit” and “illicit” subrepresentations under 1 ⊗ SU(b), and use Lemma 16’s Littlewood-Richardson decomposition to show W^b_licit cannot contain N^b_j for j ≥ n. A tripartite analysis (ℂ^b = ℂ^c ⊗ ℂ^e with c = e = 2) then derives a contradiction via associativity: Lemma 17 combined with permutation symmetry forces W^c representation to include N^c_n, contradicting the bipartite restriction. For n = 1, W^b_illicit is empty (the only partition is λ = μ = (1) and M^ab_1 = M^a_1 ⊗ M^b_1 = W^b_licit), so the contradiction does not apply and the Born rule emerges uniquely.

The significance is real. As Cabello observes in the Quanta Magazine coverage, *“the work is a sort of ‘cleaning’ exercise”* — a way of ridding quantum mechanics of redundant ingredients, the redundancies being “a symptom that we don’t fully understand quantum theory.” The derivation eliminates the layer of postulated operator algebra (Hermitian operators, spectral decomposition, eigenvalue-eigenvector measurement) and replaces it with the OPF formalism plus associativity plus state estimation. The result is the strongest operational reconstruction in the contemporary literature.

*McGucken diagnostic.* The Masanes–Galley–Müller result is important and the technical proof is genuine. The diagnostic at the McGucken level is that it operates entirely *inside* a postulated Hilbert-space arena and produces the Born rule as the operational shadow of upstream physics that Masanes–Galley–Müller cannot see. Six specific contrasts.

Postulate (states) in §II.A of the paper states: “To every physical system there corresponds a complex and separable Hilbert space ℂ^d.” This is the foundational input. Everything else — the OPF formalism, the closure properties, the ⋆-product, the irrep classification — operates *within* this postulated arena. The Masanes–Galley–Müller theorem is empty in the absence of Postulate (states); the Born rule that emerges is the Born rule *on a structure that has been postulated, not derived*. The McGucken dx₄/dt = ic framework derives the Hilbert space itself (Theorem 6.1) as the natural function space L²(Minkowski Space 𝕄_(1,3), dμ_M) on the constraint surface Minkowski Space 𝕄_(1,3) where dx₄/dt = ic holds locally; the arena is a downstream consequence of one physical principle, not a foundational primitive.

Theorem 18 of the paper derives n = 1 from associativity. Why does nature obey n = 1 (single tensor product |ψ⟩⟨ψ|, Born rule |⟨ϕ|ψ⟩|²) rather than n = 2 (double tensor product |ψ⟩⟨ψ|^⊗2, alternative rule |⟨ϕ|ψ⟩|⁴)? The Masanes–Galley–Müller answer is operational: associativity excludes n ≥ 2. But Masanes–Galley–Müller gives no *physical* reason — no reason why nature is associative. The McGucken dx₄/dt = ic framework supplies the physical reason. The spacetime metric induced by x₄ = ict via (ict)² = −c²t² is rank 2 — bilinear in two arguments dx^μ and dx^ν. The Born probability density is the geometric overlap of the forward x₄-expansion (carrying ict-phase) with the conjugate x₄-expansion (carrying −ict-phase) on the McGucken Sphere — bilinear in ψ and ψ*. The rank-2 character of the geometric pairing forces n = 1 directly; this is the physics that Masanes–Galley–Müller’s ⋆-product associativity is the operational shadow of. The (n−1,1) Young-tableau structure that drives Theorem 18’s contradiction is the SU(d) representation of “traceless adjoint” — precisely the structure of the observable algebra on the McGucken Sphere modulo identity.

In §III.B the paper analyzes Scott Aaronson’s alternative rule P(ϕᵢ|ψ) = |⟨ϕᵢ|ψ⟩|⁴/Σⱼ|⟨ϕⱼ|ψ⟩|⁴ from arXiv:quant-ph/0401062 — a fourth-power rule that *fits* the OPF formalism but violates Gleason-style non-contextuality (the denominator depends on the rest of the basis). Masanes–Galley–Müller exclude (21) because it fails *state estimation* — the fourth-power rule has too many degrees of freedom and cannot be specified by a finite list of OPFs. The McGucken diagnostic is geometric: the fourth-power rule corresponds to projecting x₄ *twice* rather than once (rank-4 metric pairing rather than rank-2). The rank-2 character of (ict)² = −c²t² forbids this directly. The Masanes–Galley–Müller and McGucken diagnoses of (21) agree on the conclusion but differ on the level of the explanation: Masanes–Galley–Müller rule it out via operational state estimation, McGucken rules it out via geometric rank of the spacetime metric. The geometric reading subsumes the operational reading — state estimation works with k = d² − 1 parameters, because that is the dimension count of the rank-2 metric on a d-dimensional Hilbert space derived from the McGucken cascade.

Araújo’s Quanta critique that *“their central assumption is that there is a fixed set of measurements whose probabilities are enough to completely determine a quantum state”* is exactly this assumption — openly stated in Masanes–Galley–Müller, not hidden. The McGucken diagnostic is that state estimation works *because* the spacetime constraint surface Minkowski Space 𝕄_(1,3) is finite-dimensional (3+1D), so the wavefunctions on it (modulo phase) span a finite-dimensional space when restricted to bounded support. The d² − 1 parameter count Masanes cites for QM is the dimension count of the SU(d) adjoint representation N^d_1 — which corresponds in McGucken terms to the operator algebra on the McGucken Sphere. State estimation is a derived consequence of the geometric structure of Minkowski Space 𝕄_(1,3) together with the rank-2 metric character, not an independent assumption.

Appendix D (Lemma 20, Theorem 21) extends the result to countably infinite-dimensional Hilbert spaces C^∞ by showing that an OPF on C^∞ takes the form f(ψ) = ⟨ψ|F|ψ⟩ if and only if it does so on every finite-dimensional subspace S ⊂ C^∞, which is established via Cauchy-sequence construction across an increasing chain of finite subspaces. This is a genuine extension and my prior critique that Masanes–Galley–Müller “works only for finite-dimensional Hilbert spaces” was inaccurate. The McGucken dx₄/dt = ic framework does not need this approximation-based extension because the Born density P(x) = |ψ(x)|² on the continuous spatial slice ℝ³ arises directly from the rank-2 metric pairing on the McGucken Sphere 𝓜_E(t) at any spacetime event — finite and continuous spectra are unified at the foundational level rather than connected via an approximation argument.

This is the architectural inversion. The four Masanes–Galley–Müller technical axioms — (a) Hilbert-space arena from Postulate (states); (b) operational OPF formalism with closure properties (7-9); (c) ⋆-product structure with associativity (14); (d) finite-parameter state estimation — are *all* downstream consequences of dx₄/dt = ic in the McGucken framework: (a) the Hilbert space is the L²-completion on Minkowski Space 𝕄_(1,3) (Theorem 6.1); (b) OPFs are projections of x₄-advance onto the spatial slice; (c) ⋆-product associativity is the associativity of tensor-product structure on the constraint surface, derived in Corollary 11.6 from Fubini-Tonelli on independent x₄-expansions; (d) finite state estimation is the finite parameter count of the adjoint representation N^d_1 = the operator algebra on the McGucken Sphere. The Masanes–Galley–Müller theorem operates downstream of all four; the McGucken dx₄/dt = ic framework derives the four together from one physical principle.

The cleanest closing comparison is between what the two frameworks identify as the central derivational input. Masanes–Galley–Müller identify ⋆-product associativity (B16) as the central algebraic requirement — the assumption that makes Theorem 18 work and excludes n ≥ 2. The McGucken dx₄/dt = ic framework identifies the rank-2 character of the spacetime metric induced by x₄ = ict as the central geometric requirement — the structure that makes ψ → ψ*ψ the right bilinear pairing and excludes |ψ|⁴ and higher-rank alternatives. Both diagnoses identify the same operational feature (n = 1, single tensor product, squared modulus, bilinear in ψ and ψ*); they differ on whether the explanation is algebraic-operational or geometric-physical. Masanes–Galley–Müller say “associativity forces n = 1.” McGucken says “the rank-2 metric induced by x₄ = ict forces n = 1, and the associativity Masanes–Galley–Müller rely on is the operational shadow of that geometric rank.”

Blind to the upstream geometric source of associativity. Blind to the rank-2 character of the metric as the source of the squared-modulus form. Blind to dx₄/dt = ic as the source of the Hilbert-space arena, the OPF formalism, the ⋆-product structure, and the finite-parameter assumption all at once. The Masanes–Galley–Müller theorem is a major result *within* the operational reconstruction tradition; the McGucken dx₄/dt = ic framework operates *upstream* of that tradition by supplying the physical principle from which all four Masanes–Galley–Müller technical axioms descend as forced consequences. Operational redundancy is a real result; physical derivation is a different result. McGucken accomplishes the latter.

##### 7.1.9.A The depth question made precise: six postulates versus one principle

The question naturally arises whether the Masanes–Galley–Müller derivation is “as foundational” as the McGucken derivation. The answer is derivational rather than rhetorical: the Masanes–Galley–Müller input list contains six independent postulates, while the McGucken input list contains one physical principle. This is a difference of architectural level.

Each is foundational primitive in the Masanes–Galley–Müller framework — accepted without further derivation.

 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Masanes–Galley–Müller input Statement Status in Masanes–Galley–Müller
 --------------------------------- ------------------------------------------------------------------------------------------------------------- ----------------------------------------
 Postulate (states) Every physical system corresponds to a complex separable Hilbert space ℂ^d; pure states are rays ψ ∈ ℙℂ^d Postulated arena

 Postulate (transformations) Reversible transformations are unitary U ∈ U(d) Postulated dynamics

 Postulate (composite systems) Joint pure states of ℂ^a and ℂ^b are rays of ℂ^a ⊗ ℂ^b Postulated composition

 OPF formalism (7–9) OPFs f : ℙℂ^d → [0,1] with closure under mixtures, unitaries, system composition Postulated operational framework

 ⋆-product axioms (10–14) Bilocality, equivariance, normalization-preservation, **associativity** Postulated algebraic structure

 Possibility of state estimation Finite list of OPFs determines all others on any ensemble Postulated finite-parameter assumption
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

That principle, stated once, generates everything else as theorem.

 -----------------------------------------------------------------------------------------------------------------------------------
 McGucken input Statement Status in McGucken
 -------------------- ------------------------------------------------------------- ------------------------------------------------
 McGucken Principle dx₄/dt = ic, with action ℏ per Planck-frequency oscillation Physical principle (single foundational input)

 -----------------------------------------------------------------------------------------------------------------------------------

That is the entire input list. The complex Hilbert space, the unitary group, the tensor-product structure, the operational OPF formalism, the ⋆-product with associativity, the finite-parameter character of state space, and the Born rule itself are all *downstream theorems* of this single principle. The architectural ratio is six postulates to one principle.

This is a counting fact about the input lists. Six independent primitive statements stand at the base of the Masanes–Galley–Müller derivation; one physical statement stands at the base of the McGucken derivation. Every operational/algebraic/formal feature Masanes–Galley–Müller rely on — the arena, the dynamics, the composition law, the operational framework, the algebraic structure, the finite-parameter assumption — corresponds to a distinct McGucken theorem (respectively Theorem 6.1 for the Hilbert space; Theorem 9.2 for unitarity from x₄-flux conservation; Corollary 11.6 for the tensor-product structure from Fubini–Tonelli on independent x₄-expansions; the OPF formalism as the operational shadow of x₄-projection onto spatial slices; ⋆-product associativity as Fubini–Tonelli on three independent x₄-expansions; and state estimation as the finite dimension d² − 1 of the SU(d) adjoint representation N^d_1 corresponding to the operator algebra on the McGucken Sphere).

##### 7.1.9.B The asymmetric depth test

A foundational derivation has to bottom out somewhere, and the question is *where*. Three terminating points are available in the reconstruction tradition: operational axioms about measurement outcomes, mathematical axioms about Hilbert spaces, and physical principles about what nature does. Masanes–Galley–Müller bottom out at the operational layer; von Neumann’s 1932 axiomatization bottoms out at the mathematical layer; the McGucken Principle bottoms out at the physical layer. Each layer is foundational relative to the layer above and derived relative to the layer below.

The clean test for which derivation is more foundational is reciprocal: ask each framework to derive the *inputs* of the other.

**Can McGucken derive Masanes–Galley–Müller’s six inputs?** Yes, all six. The complex Hilbert space is L²(Minkowski Space 𝕄_(1,3), dμ_M), the function space on the constraint surface where dx₄/dt = ic holds locally (Theorem 6.1, completed by Cauchy completion of the pre-Hilbert space 𝓥 of complex amplitudes over Minkowski Space 𝕄_(1,3)). Unitarity is x₄-flux conservation: the evolution U(t) = exp(−iĤt/ℏ) preserves the Born inner product because it preserves the total x₄-projection density across the spatial slice (Theorem 9.2). The tensor-product structure for composite systems is Fubini–Tonelli on independent x₄-expansions from causally independent source events: L²(M^{(A)}*{1,3} × M^{(B)}*{1,3}, dμ^{(A)}*M ⊗ dμ^{(B)}*M) ≅ L²(M^{(A)}*{1,3}, dμ^{(A)}*M) ⊗ L²(M^{(B)}*{1,3}, dμ^{(B)}*M) (Corollary 11.6). The OPF formalism is the operational shadow of projections of x₄-advance onto the spatial slice — each OPF f(ψ) is, in the McGucken reading, the density of x₄-projection at a localized apparatus event evaluated on the McGucken Sphere 𝓜_E(t). ⋆-product associativity is the associativity of independent x₄-expansion tensor structure on the constraint surface, derived from Fubini–Tonelli on three independent x₄-expansions: the probability that three causally independent sources A, B, C jointly produce an outcome cannot depend on whether we describe them as (A · B) · C or A · (B · C), because both descriptions correspond to the same physical x₄-expansion configuration on M^{(A)}*{1,3} × M^{(B)}*{1,3} × M^{(C)}_{1,3}. Finite-parameter state estimation holds because the SU(d) adjoint representation N^d_1 = the operator algebra on the McGucken Sphere has finite dimension d² − 1, and the spacetime constraint surface Minkowski Space 𝕄_(1,3) is 3+1-dimensional with finite-dimensional Hilbert-space restriction on any bounded support.

All six Masanes–Galley–Müller inputs are derived from the single McGucken input. The derivation is complete and theorem-by-theorem.

**Can Masanes–Galley–Müller derive McGucken’s one input?** No. Masanes–Galley–Müller cannot derive dx₄/dt = ic from operational axioms about measurement outcomes, because operational axioms are silent on the geometric structure of spacetime. The Masanes–Galley–Müller framework has no language for *what is the fourth dimension doing*. The OPF formalism describes what an observer sees when measuring a system; it cannot describe the physical structure that causes the observer to see what they see. There is no path from “outcome probability functions on ℙℂ^d satisfy closure properties (7-9)” to “the fourth dimension is expanding at the velocity of light from every spacetime event.” The McGucken Principle dx₄/dt = ic lies entirely outside Masanes–Galley–Müller’s expressive vocabulary.

The derivation relation is therefore asymmetric: McGucken → Masanes–Galley–Müller is a complete cascade through Theorems 6.1, 9.2, and Corollary 11.6; Masanes–Galley–Müller → McGucken is empty. This asymmetry is the formal test of foundational depth. The dx₄/dt = ic framework whose inputs can be derived from the other’s inputs is the less foundational of the two. The dx₄/dt = ic framework whose inputs *cannot* be derived from the other’s inputs is the more foundational. By this test the McGucken Principle is more foundational than the Masanes–Galley–Müller postulates by a clear margin.

##### 7.1.9.C The architectural question

A second, complementary test asks what each framework identifies as the central structure in its own derivation — the specific component that, if removed, causes the entire derivation to fail.

Theorem 18 of the paper proves that for n ≥ 2 no associative ⋆-product on M^a_n × M^b_n → M^ab_n exists; the proof uses the (n−1,1) Young tableau, the Schur–Weyl decomposition under SU(a) ⊗ SU(b), and Lemma 16’s Littlewood–Richardson rule. The Born rule (n = 1) survives only because for n = 1 the contradiction does not arise (W^b_illicit is empty when λ = μ = (1)). Drop associativity, and the §III.A toy theory with n = 2 — where states are represented by |ψ⟩⟨ψ|^⊗2 and probabilities by tr[F|ψ⟩⟨ψ|^⊗2] — becomes admissible. Associativity is the central algebraic requirement of the entire Masanes–Galley–Müller derivation.

The Masanes–Galley–Müller framework does not derive associativity. It is postulated as axiom (14) and accepted as a basic feature of the ⋆-product on the grounds that “deciding to describe a tripartite system A · B · C as either the bipartite system AB · C or as A · BC must not modify the outcome probabilities.” This is presented as a self-evident operational requirement — but operational self-evidence is not derivation. *Why* should descriptions invariant under regrouping correspond to the same outcome probabilities? Masanes–Galley–Müller provide no physical reason.

The McGucken Principle dx₄/dt = ic integrates to x₄ = ict, and the Euclidean line element on ambient four-dimensional space restricts to the Minkowski metric on the constraint surface Minkowski Space 𝕄_(1,3) via (ict)² = −c²t² (Lemma 2.5). This metric is rank 2: bilinear in two arguments dx^μ and dx^ν, with ds² = g_μν dx^μ dx^ν being the canonical rank-2 form. The Born density is the rank-2 metric pairing of the forward x₄-expansion (carrying ict-phase, ψ) with the conjugate x₄-expansion (carrying −ict-phase, ψ*) on the McGucken Sphere 𝓜_E(t) at the apparatus event: P = ψ*ψ = |ψ|² (Theorem 7.2). The rank-2 character directly forces n = 1 in the Masanes–Galley–Müller classification: bilinear pairing in (ψ, ψ*) corresponds to n = 1 (single tensor product |ψ⟩⟨ψ|, squared modulus), while a rank-4 pairing would correspond to n = 2 (double tensor product |ψ⟩⟨ψ|^⊗2, Aaronson’s |⟨ϕᵢ|ψ⟩|⁴ rule from arXiv:quant-ph/0401062).

The McGucken dx₄/dt = ic framework derives associativity. The associativity of the ⋆-product is the associativity of independent x₄-expansion tensor structure on the constraint surface, and it is forced by Fubini–Tonelli on three independent x₄-expansions: the order of tensor products of independent function spaces is associative, so the order of descriptions of independent sources is too. The *physical reason* associativity holds — which Masanes–Galley–Müller cannot supply — is that three causally independent x₄-expansions from three independent source events combine into a single product structure on M^{(A)}*{1,3} × M^{(B)}*{1,3} × M^{(C)}_{1,3} regardless of how the bracketing is chosen. Associativity is a derived geometric fact.

The contrast: Masanes–Galley–Müller’s associativity is postulated and the squared modulus is derived from it; McGucken’s rank-2 metric is derived from the McGucken Principle and the squared modulus is derived from the metric, with associativity itself derived as a downstream geometric fact. The McGucken derivation goes one level deeper: it identifies *what physical structure makes associativity true*, which Masanes–Galley–Müller leave unexplained.

##### 7.1.9.D The Schrödinger 1926 test

There is a historical test that pins down what “foundational” means at the foundational level. On 6 June 1926, Erwin Schrödinger wrote to H. A. Lorentz: *“What is unpleasant here, and indeed directly to be objected to, is the use of complex numbers. Ψ is surely fundamentally a real function.”* (Quoted in Einstein–Przibram–Klein, *Letters on Wave Mechanics*, 2011; cited as reference [22] in Renou et al. 2021.) This is the canonical statement of the foundational complaint about the Born rule and its complex amplitudes, formulated within months of Schrödinger’s own publication of the wave equation. The complaint is precise: Schrödinger objects that the complex character of ψ has *no physical referent* in the dx₄/dt = ic framework he has just published. The ψ-function appears in his derivation as a mathematical construct by analogy with Hamilton–Jacobi theory; the complex numbers entered as a computational convenience rather than as a description of any physical structure. Schrödinger himself concluded by 1928 that ψ was not to be interpreted as a physical wave at all.

What would a *foundational* answer to Schrödinger 1926 look like? It would have to identify what physical structure the complex amplitudes refer to — what element of reality the imaginary unit i in ψ describes. Anything short of this leaves Schrödinger’s complaint open. The Renou et al. (2021) experimental result (§6.2.22) provides the empirical pillar: complex numbers are necessary, real-vector-space alternatives are experimentally excluded. But Renou himself acknowledges the explanatory gap: *“the early founders of quantum mechanics could not find any way to interpret the complex numbers appearing in the theory. Having them worked very well, but there is no clear way to identify the complex numbers with an element of reality”* (Renou interview, *Live Science*, December 2021). Renou’s experimental result confirms *that* complex numbers are physically necessary; it does not explain *what physical fact* the complex numbers describe.

The Masanes–Galley–Müller framework begins with Postulate (states): *“To every physical system there corresponds a complex and separable Hilbert space ℂ^d.”* The complex Hilbert space is the foundational input, accepted without derivation. The Masanes–Galley–Müller theorem then shows that given this complex Hilbert space and the other operational postulates, the Born rule emerges as the unique probability rule. But Schrödinger’s complaint was precisely about the complex character of the Hilbert space. Asked *why complex numbers*, Masanes–Galley–Müller’s answer is in effect: *because if you accept the complex Hilbert space as foundational, the Born rule is the unique probability rule consistent with operational axioms*. This is not an answer to Schrödinger’s question. It is a re-statement of the premise Schrödinger was objecting to. The Masanes–Galley–Müller derivation is foundationally silent on Schrödinger 1926 because the complex character of the Hilbert space is *upstream* of where Masanes–Galley–Müller begin.

The complex numbers in ψ are the algebraic signature of the perpendicular fourth dimension x₄. The imaginary unit i is the geometric marker for the one perpendicular axis beyond x₁x₂x₃, with x₄ = ict being the integrated coordinate shadow of dx₄/dt = ic. ψ(x, t) is the projection of x₄-advance from a worldline event onto the spatial location x at time t — a complex amplitude because x₄-advance carries phase from the imaginary-unit factor of x₄ = ict. The element of reality the complex amplitudes describe is the expanding fourth dimension perpendicular to ordinary 3-space, advancing at rate c with action ℏ per Planck-frequency oscillation. Schrödinger 1926 was correct that the complex character of ψ requires a physical referent; he was correct that his own derivation of ψ from Hamilton–Jacobi analogy did not supply one; and he was correct to be uncomfortable with treating ψ as fundamental without that referent in hand. The McGucken Principle supplies what Schrödinger could not — the referent that justifies the complex character of ψ.

The historical force of this test is sharp. Schrödinger himself, the originator of the wave equation, identified the complex character of ψ as the foundational puzzle within weeks of his own publication. He could not solve it and abandoned the physical interpretation of ψ by 1928. The puzzle has persisted in the foundations literature for nearly a century, through Gleason (1957), Mackey (1957), Piron (1964), Solèr (1995), Hardy (2001), Chiribella–D’Ariano–Perinotti (2010s), Masanes–Galley–Müller (2019), Renou et al. (2021), and beyond. Each of these programs operates *inside* the complex Hilbert space and derives various consequences from it; none has been able to identify the physical referent of the imaginary unit i. The Renou et al. experiment closes the empirical route by showing the complex numbers are physically necessary; the Renou framing of the open question — *“there is no clear way to identify the complex numbers with an element of reality”* — confirms that the philosophical puzzle is still open at the foundational layer. The McGucken Principle dx₄/dt = ic answers it: the element of reality is x₄, perpendicular to x₁x₂x₃, expanding at rate c.

Masanes–Galley–Müller derive the Born rule given a postulated complex Hilbert space and five operational axioms; McGucken derives the Born rule together with the complex Hilbert space and all the operational structure, all from a single physical principle about the active expansion of the fourth dimension at the velocity of light. The Masanes–Galley–Müller derivation is rigorous and impressive within the operational reconstruction tradition; the McGucken derivation is foundational in the sense Schrödinger 1926 asked for — it identifies what physical structure the formalism describes. The architectural ratio is six postulates to one principle. The asymmetric depth test is unambiguous: McGucken can derive all six Masanes–Galley–Müller inputs as downstream theorems, and Masanes–Galley–Müller cannot derive the McGucken Principle from operational axioms because operational axioms are silent on the geometric structure of spacetime. The contrast is precise: Masanes–Galley–Müller’s central axiom is associativity (postulated), while McGucken’s central structure is the rank-2 metric (derived from the McGucken Principle), with associativity itself derived from Fubini–Tonelli on independent x₄-expansions. The Schrödinger 1926 historical test is decisive: McGucken answers the question Schrödinger asked; Masanes–Galley–Müller cannot, because the complex Hilbert space stands as the foundational primitive of Masanes–Galley–Müller’s framework and the question of *what physical structure makes it complex* lies entirely upstream of Masanes–Galley–Müller’s expressive layer.

Foundational depth is measured by *where the derivation bottoms out*; both derivations are rigorous in their own layer. Masanes–Galley–Müller bottom out in operational primitives about measurement and probability on a postulated complex Hilbert space. McGucken bottoms out in a physical statement about the active expansion of the fourth dimension. The difference is the difference between deriving the Born rule from the structure of measurement and deriving the Born rule from the structure of spacetime itself. Schrödinger 1926 was asking for the latter. McGucken supplies it.

#### 7.1.10 Saunders (2021): branch-counting

Simon Saunders’s “Branch-Counting in the Everett Interpretation of Quantum Mechanics” (*Proceedings of the Royal Society A* 477, 20210600, 2021) derives the Born rule from a branch-counting normalization condition in the Everett interpretation.

*McGucken diagnostic.* Branch-counting is the most metaphysically committed of the Everettian derivations. The McGucken diagnostic is that branches are geometric points on the McGucken Sphere — locations where the conjugate x₄-expansion meets the apparatus. Counting branches is counting points; the Born density is the local density of such points. Blind to the McGucken Sphere as the geometric ground of branch structure.

#### 7.1.11 QBist (Caves–Fuchs–Schack 2002, Fuchs 2010): Dutch-book coherence

Carlton Caves, Chris Fuchs, and Rüdiger Schack’s “Quantum Probabilities as Bayesian Probabilities” (*Physical Review A* 65, 022305, 2002) and subsequent QBist work (Fuchs 2010 and later) interpret quantum probabilities as Bayesian (subjective) degrees of belief. The Born rule is derived from Dutch-book coherence — an agent assigning quantum probabilities other than |ψ|² would be subject to a sure-loss betting strategy.

*McGucken diagnostic.* QBism is the most thoroughgoing operational reading of quantum mechanics, locating the formalism entirely in the agent’s epistemic state. The McGucken diagnostic is that quantum probabilities are objective geometric facts about overlap on the McGucken Sphere. Agents are *constrained* to assign |ψ|² because nature is described by dx₄/dt = ic; they do not generate the rule by being coherent bettors. Blind to the objective geometry of the Born rule.

#### 7.1.12 Hardy (2001) and Chiribella–D’Ariano–Perinotti (2011) Born derivations

The operational reconstructions of Hardy and Chiribella–D’Ariano–Perinotti discussed in §6.2 also derive the Born rule as part of their reconstruction of the full quantum formalism. In each case, the rule emerges from the operational/informational axioms together with the derived Hilbert-space structure.

*McGucken diagnostic.* Same as in the Hilbert-space history: the operational axioms are downstream consequences of dx₄/dt = ic. The Born rule emerges in their frameworks because purification (Chiribella–D’Ariano–Perinotti) or simplicity-with-continuous-transformations (Hardy) reproduces the rank-2 character of the metric pairing in operational terms. Blind to the upstream geometric source.

#### 7.1.13 Ichikawa (2018): logical inference / Cox-theorem-style

Tsubasa Ichikawa’s “Born Rule and Logical Inference in Quantum Mechanics” (arXiv:1804.10067, 2018) derives the Born rule from logical-inference axioms in the Cox-theorem style, extending the classical logical interpretation of probability to quantum settings.

*McGucken diagnostic.* The logical-inference derivation is the latest entry in the long tradition of operational/epistemic reconstructions. Same diagnostic as Hardy, Chiribella–D’Ariano–Perinotti, QBism: blind to the geometric ground.

#### 7.1.14 Information-geometric (Goyal) and Bayesian-network derivations

Philip Goyal’s “Origin of Complex Quantum Amplitudes and Feynman’s Rules” (*Physical Review A* 81, 022109, 2010) derives complex amplitudes and the Born rule from information-geometric axioms.

*McGucken diagnostic.* Same as in §6.2.16: complex amplitudes are introduced as a representational choice rather than as a forced consequence of physical perpendicularity. Blind to the perpendicularity-marker reading of i; therefore unable to explain why complex amplitudes (rather than real, quaternionic, or octonionic) are physically required.

#### 7.1.15 Schlosshauer–Fine (2005) critical review

Maximilian Schlosshauer and Arthur Fine’s “On Zurek’s Derivation of the Born Rule” (*Foundations of Physics* 35, 197–213, 2005) gave a critical review of Zurek’s envariance derivation, identifying tacit assumptions and arguing that the derivation, while not strictly circular, requires additional premises that themselves need justification.

*McGucken diagnostic.* Schlosshauer and Fine’s critical analysis is representative of the broader skeptical literature on Born-rule derivations (Barnum et al. 2000, Saunders 2004, Gill 2005, Lewis 2010, Hemmo–Pitowsky 2007, Rae 2009, Dawid–Thébault 2014). The critical consensus is that *no* derivation of the Born rule from the other postulates of quantum theory succeeds without additional assumptions whose physical origin is unexplained. This consensus is the diagnostic background that makes the McGucken dx₄/dt = ic framework’s upstream derivation necessary: the only way to derive the rule is from a principle upstream of the formalism, which is what dx₄/dt = ic supplies.

#### 7.1.16 POVM generalization and operational-detector programs (Davies–Lewis 1970, Neumaier 2025)

Edward Brian Davies and John T. Lewis introduced the positive operator-valued measure (POVM) generalization of the Born rule in 1970 (“An Operational Approach to Quantum Probability,” *Communications in Mathematical Physics* 17, 239–260). The motivation was that real quantum measurements — measurements with finite detector efficiency, dark counts, losses, decoherence in the apparatus, the simultaneous low-resolution measurement of position and momentum, and outcomes that do not coincide with eigenvalues of the measured observable — cannot be described by projection-valued measures. The POVM is the mathematical structure that captures real measurements: a family of positive operators {P_k} summing to the identity, with the probability of outcome k given by tr(ρ P_k). By the 1990s the POVM form had become standard in quantum optics and quantum information theory (Nielsen and Chuang [23]; Busch, Lahti, and Werner [ref. 105 of [1]]). The relation between POVM and projective forms is Naimark’s dilation theorem (Mark Naimark 1940): every POVM on a Hilbert space 𝓗 lifts to a projection-valued measure on a larger Hilbert space 𝓗 ⊗ 𝒦 obtained by tensoring with an ancilla space, and the projective Born rule on the dilated space reproduces the POVM rule on the original space.

Arnold Neumaier’s “The Born rule – 100 years ago and today” (arXiv:2502.08545v3, March 2025) surveys ten distinct historical formulations of the Born rule (universal/projective, discrete spectral, finite spectral, scattering objective, scattering measurement, objective, measurement, POVM, condensed, and quantum-statistical-mechanics forms), and proposes a derivation of the POVM form from what he calls the Detector Response Principle (DRP). The DRP defines what a “quantum measurement device” is by listing its operational properties — detection elements labeled by a finite set K, response rates, stationarity of the source, and the relation between mean rates and the density operator of the source — and Neumaier proves a Detector Response Theorem ([Neumaier–Westra 2024, §4.1.2]) yielding a unique POVM {P_k} characterizing the device’s response. The POVM Born rule then falls out as a theorem. The program is developed at length in Neumaier’s books *Coherent Quantum Physics* (Cambridge University Press, 2019) and Neumaier–Westra’s *Algebraic Quantum Physics, Vol. 1* (2024).

*McGucken diagnostic.* Theorem 7.2 of the present paper derives the *projective* Born rule P = |ψ|² — the form Born stated in 1926 ([24]), the form in every textbook, and the form whose architectural inversion-to-corollary is the central derivational claim. The POVM generalization is recoverable in the McGucken dx₄/dt = ic framework via Naimark dilation: the McGucken Hilbert space 𝓗 of Theorem 6.1 has ancilla tensor extensions 𝓗 ⊗ 𝒦, and the projective Born rule on the dilated space reproduces the POVM rule on 𝓗. The architectural inversion of the present paper — from postulated Born rule to forced theorem of dx₄/dt = ic — carries to the POVM form by this dilation, with the McGucken Sphere expansion in the dilated space supplying the rank-2 metric pairing that grounds (R4) in the larger setting.

The deeper diagnostic concerns what the operational-detector programs actually import to do their derivational work. Davies–Lewis 1970 is a *technical generalization* that takes the entire Hilbert-space formalism as given and extends the Born rule from projections to positive operator–valued measures. It postulates nothing foundational; it generalizes within the existing formalism. The POVM structure itself is the postulate, on top of standard quantum mechanics.

Neumaier 2025 is a derivation, but the postulate it starts from — the DRP — is not a single physical principle. The phrase “Detector Response Principle” sounds like one principle. It functions as an *entire measurement-physics ontology* compressed into an operational definition. Reading the DRP as it is actually stated, the program postulates: (i) the Hilbert space 𝓗 on which the density operator ρ acts (imported silently from standard quantum mechanics); (ii) the density operator formalism itself, with the trace pairing tr(ρ A) as the value functional on operators; (iii) time as a parameter of evolution, required to define mean rates; (iv) stationarity of the source as an operational stability condition; (v) the existence of discrete detection events as the primitive ontology of outcomes; (vi) the existence of detection elements labeled by a finite set K as an a priori partition of outcome space; (vii) the pairing of detection elements with the source via operators P_k; and (viii) the operational notion of a “quantum measurement device” as a primitive concept. Each of these is foundational machinery imported into the DRP, not derived by it. The “one principle” framing obscures that the DRP is doing the work of eight foundational commitments — comparable in foundational content to Masanes–Galley–Müller’s six measurement axioms or to the suite of assumptions in the operational reconstructions of Hardy (§7.1.12) and Chiribella–D’Ariano–Perinotti (§7.1.12). The DRP states that it derives the POVM Born rule from itself; it does not state how much it imports along the way.

The McGucken dx₄/dt = ic framework derives all eight of the DRP’s imported commitments from upstream geometry. The Hilbert space 𝓗 is constructed (Theorem 6.1) as the Cauchy completion of the space of x₄-projections, not assumed. The density operator formalism is the standard convex-combination structure on 𝓗 (Corollary 11.1). Time is the parameter of x₄-advance (the McGucken Principle itself supplies the time direction via dx₄/dt). Detection events are the geometric incidence of forward and conjugate x₄-expansions on a localized absorber (Theorem 7.4). The “detector” is, in the McGucken reading, a region of spacetime where x₄-expansion is locally absorbed by a macroscopic apparatus with definite x₄-localization (Theorem 7.4, measurement-as-meeting-of-two-expansions). The operational notion of a “quantum measurement device” is a derived structure: it is whatever physical assembly produces detection events as geometric overlaps of two expansions. The McGucken dx₄/dt = ic framework is the only program in the present literature survey that derives *both* the detector and the rule from a principle upstream of both. This is the architectural inversion in its full form: derived measurement ontology in place of postulated measurement ontology, all descending from dx₄/dt = ic.

In the simplicity-of-foundational-commitment ranking, Davies–Lewis and Neumaier therefore land at different positions. Davies–Lewis is roughly equivalent to Born 1926 — it states (or generalizes) the rule on top of the existing Hilbert-space formalism without deriving anything foundational. Neumaier’s DRP-based derivation is more ambitious but imports an eight-fold suite of operational commitments under the label of a single “principle.” The McGucken Principle dx₄/dt = ic, by contrast, is a single physical equation about geometric flow — five symbols, one action-quantization clause — from which the Hilbert space, the density operator structure, the time parameter, the detection-event ontology, and the projective Born rule are all derived as theorems, with the POVM generalization recoverable via Naimark dilation.

#### 7.1.17 Diagnostic across all sixteen programs

The pattern is uniform across all sixteen programs: every prior derivation operates *inside* the Hilbert-space formalism (or, in the case of Davies–Lewis and Neumaier, *inside* an even larger operational-detector formalism that imports the Hilbert space and adds detector-ontological structure on top), and imports a supplementary axiom — a probability measure on subspaces, a rationality axiom, an environment-induced symmetry, an equivariant measure, a self-locating uncertainty principle, a branch-counting principle, a Dutch-book coherence requirement, an operational/informational axiom, a logical-inference axiom, or a detector-response principle — whose content is essentially the Born measure (or the detector ontology that already pre-supposes the Born measure) already, dressed in the language of the program. The critical literature has consistently identified this as the pattern.

The McGucken diagnostic identifies the upstream geometric source these programs could not see: P = |ψ|² is the unique density satisfying (R1)–(R4), with each requirement supplied by one foundational feature of dx₄/dt = ic:

- (R1) Reality — descends from the physical meaning of probability as frequency of detection events (universal feature).
- (R2) Non-negativity — descends from the same.
- (R3) Phase invariance — descends from the universality of x₄-expansion from every event (universal x₄-shift is unobservable).
- (R4) Bilinearity in (ψ, ψ*) — descends from the rank-2 character of the Minkowski metric induced by x₄ = ict, which is the central geometric fact of the derivation.

No prior program had R4 derived from upstream physics — every program either stipulated bilinearity as an axiom (Hardy, Chiribella–D’Ariano–Perinotti, Masanes–Müller) or extracted it from operational redundancies (Masanes–Galley–Müller) or showed it was forced by additional axioms (Gleason). The McGucken dx₄/dt = ic framework derives R4 from the rank-2 structure of the Minkowski metric, which is itself derived from (ict)² = −c² t², which is the integrated coordinate shadow of dx₄/dt = ic. The Born rule is therefore not an axiom, and not a result of agent rationality or self-locating uncertainty: it is a forced geometric theorem of one physical principle.


### IV.2 The comparison across prior programmes

The McGucken Principle dx₄/dt = ic supplies all four requirements (R1)–(R4) from one principle; each prior programme imports one supplementary axiom to do the derivational work. The table of §7.7 of [1] is reproduced here, with McGucken in the first row.


### 7.7 Diagnostic across prior programs for the Born rule: each imports one supplementary axiom (rationality, environmental decoherence, self-locating uncertainty, branch-counting, equivariance) to do the derivational lifting; the McGucken dx₄/dt = ic framework supplies all four requirements from one principle

| Program | Operation | What is imported | What dx₄/dt=ic feature it was blind to |
|:----------------------|:--------------|:------------------------|:----------------------------------------|
| **McGucken (2026)** | **Physical derivation** | **Single principle dx₄/dt = ic** | **Nothing — derives all four features** |
| Born (1926) | Postulation | P = ‖ψ‖² as axiom | Rank-2 metric forcing bilinearity (had answer, not derivation) |
| Gleason (1957) | Non-contextuality theorem | Probability measure on subspaces | Perpendicularity (why ℂ), dynamism (subspaces of complex 𝓗) |
| Finkelstein–Hartle (1965, 1968) | Frequentist limit | Infinite tensor products | Geometry of ‖ψ‖² as overlap |
| Farhi–Goldstone–Gutmann (1989) | Rigorous frequentist | Infinite tensor + spectral theorem | Geometry |
| Van Wesep / Landsman (2006/2008) | Macroscopic observables | Continuous fields of C^*-algebras | Geometry |
| Deutsch (1999) | Decision theory | Equal-amplitude indifference principle | Geometric vs decision-theoretic origin |
| Wallace (2010, 2012) | Mature Everettian DT | Rationality axioms + branch structure | McGucken Sphere as branch ground |
| Zurek (2003, 2005) | Envariance | Tensor product, system-environment cut | Universality clause as source of envariance |
| Bohm (1952), Valentini–Westman | Quantum equilibrium | Equivariant measure on configuration space | Rank-2 metric as origin of squaring |
| Sebens–Carroll (2018) | Self-locating uncertainty | Self-locating principle | Geometric ground of measurement events |
| Masanes–Galley–Müller (2019) | Operational redundancy | Unitary evolution + Hilbert space | Upstream geometric source (showed downstream redundancy only) |
| Saunders (2021) | Branch-counting | Branch-counting normalization | McGucken Sphere as ground of branches |
| QBist (2002, 2010s) | Dutch-book coherence | Coherence axiom + Bayesian framework | Objective geometry of ‖ψ‖² |
| Hardy (2001), Chiribella–D’Ariano–Perinotti (2011) | Operational + purification | Five operational axioms + purification | McGucken Sphere as geometric source of purification |
| Ichikawa (2018) | Logical inference | Cox-theorem axioms extended to QM | Geometric ground |
| Goyal (2010) | Information-geometric | Complex amplitudes as representation | Perpendicularity-marker reading of i |
| Schlosshauer–Fine (2005), critical lit | Skeptical analysis | Identification of additional assumptions | (Diagnostic only; not a derivation) |



### IV.3 The sphere traditions and how Born arrived at the rule

The McGucken Principle dx₄/dt = ic predicts that a sphere yields the Born rule — Born's own scattering sphere, Gleason's state sphere, the Bloch sphere, the Aerts machine and the transactional wavefronts all reproduce the rule on some sphere — and identifies which sphere carries it physically: the expanding fourth-dimensional wavefront itself, whose metric rank fixes the exponent and whose SO(3) action fixes the measure. Born's own route to the square, by analogy to optical intensity and corrected in a footnote added in proof, is the historical canvas against which the derivation is set. Sections 7.7.1–7.7.2 of [1] are reproduced here.

#### 7.7.1 The sphere traditions: which sphere carries the Born rule, and why the physical expanding sphere is distinct

The comparison above is organized by supplementary axiom. A second comparison is needed because several programs derive or reproduce the Born rule using a *sphere*, and the word “sphere” denotes different objects in each. The distinction is decisive for what the present derivation claims, because the claim is not that a sphere yields the Born rule — that is old, tracing to Born himself — but that a *physically expanding fourth-dimensional* sphere, the wavefront of dx₄/dt = ic, is identified with the measure and projective structure that produce |ψ|². At least five sphere traditions precede this, and each uses a different sphere; the McGucken Sphere is none of them.

*(1) The physical scattering wave in ordinary space (Born 1926, Mott 1929).* Born’s original probability statement is set on an outgoing spherical scattering wave ψ ∼ eⁱᵏᶻ + f(θ,φ)eⁱᵏʳ/r, with dσ/dΩ = |f|². This is a physical wave, but a wave *in* pre-existing 3-space, and the sphere supplies directional flux dilution while the squaring is imported, not forced by the sphere’s geometry. *Distinction*: the McGucken Sphere is not a wave in space but the expansion of the fourth dimension that generates the spatial slice; the squaring is forced by the rank-2 metric (Lemma 7.1), not imported.

*(2) The unit sphere of Hilbert space (Gleason 1957, and the Busch/Caves–Fuchs–Manne–Renes POVM extensions).* Gleason’s theorem lives on the unit sphere of normalized state vectors and forces the quadratic form from non-contextual additivity over orthonormal frames. This is a rigorous theorem, but its sphere is the abstract state sphere, and its force comes from frame-additivity, not from any physical geometry. *Distinction*: the McGucken Sphere is a physical spacetime object, and the derivation supplies the physical origin of the very inner-product structure Gleason presupposes (§2.3, Lemma 7.1); the qubit gap in the original theorem is closed here by the POVM route the framework already carries.

*(3) The Bloch/Poincaré sphere and the Fubini–Study projective sphere (Bloch 1946; Kibble 1979, Wootters 1981, Brody–Hughston 1999).* For a qubit the pure states form ℂℙ¹, a two-sphere, and the Born probability is a cosine-squared of Bloch angle or Fubini–Study distance. This is an exact geometric reformulation, but the sphere is the state space, and it becomes a derivation only when an independent measure is justified. *Distinction*: §6.2.12 derives the Bloch sphere itself as the phase-quotient of the McGucken Sphere (the Hopf projection discarding the x₄-advance), so here the state-space sphere is a *consequence* of the physical sphere rather than the primitive.

*(4) Mechanical and hidden-measurement sphere models (Bell 1966, Kochen–Specker 1967, Mermin 1993; Aerts 1986 and the extended Bloch / membrane models).* Hidden directions or a fluctuating measurement interaction live on a sphere; integrating a rupture or response measure reproduces the qubit probabilities. Aerts’s elastic-sphere machine is the strongest literal mechanism. *Distinction*: these reproduce the rule by a stochastic apparatus measure on an abstract sphere; the McGucken derivation forces the measure as the unique SO(3)-invariant measure on the physical wavefront (Theorem 7.2) and locates the single outcome in the first-contact geometry of two physically expanding Spheres (§6.2.12), a physical event rather than a postulated rupture.

*(5) Spherical waves and geometric structures in spacetime (Cramer 1986, Kastner; spacetime-symmetry reconstructions, Pitalúa-García; spinor composite geometry, Northey 2026).* These are the nearest neighbours. The transactional interpretation (Cramer, Kastner) treats a retarded offer wave and an advanced confirmation wave as spherical wavefronts whose product gives ψψ^* — but as an interpretive account in pre-existing spacetime, without a uniqueness theorem, and the waves propagate in a fixed background rather than constituting it. Pitalúa-García reconstructs the Bloch ball from relativistic spacetime-symmetry assumptions, but does not identify physical spacetime with the state sphere. Northey (2026) derives the Born density in a quaternionic Einstein–Cartan–Kibble–Sciama framework by treating spacetime geometry as composite, built from constrained spinor bilinears; its force comes from the spinor–geometry correspondence and variational constraints, and the geometry is a static composite of field bilinears, not a physically expanding dimension. *Distinction*: none of these uses a physically expanding spacetime dimension. The McGucken Sphere is the expansion itself, at rate c, dx₄/dt = ic; the same expansion that carries the Born measure also generates the Lorentzian metric (§2.3), orients time (the + of +ic, §10.12nonies), and sets ħ as the action per Compton cycle — none of which a wave in a fixed background, a symmetry reconstruction, or a static spinor composite provides.

*The diagnostic that separates the physical sphere from the decorative one.* A test applies across all five traditions: remove the sphere and ask whether the probability argument survives. In a generic Bloch-sphere textbook picture the algebra is unchanged and the sphere is a visualization. In Gleason and in Aerts the sphere does the derivational work. In the present framework it does that work in the strongest sense: removing the expanding McGucken Sphere removes dx₄/dt = ic itself, and with it the metric, the inner product, the measure, the arrow, and ħ — there is no residual algebra left standing, because the algebra is derived from the Sphere rather than illustrated by it.

*Scope of the novelty claim.* Stated precisely, and confined to what the derivation supports: the sphere-to-Born-rule territory is old and occupied, from Born’s scattering wave through Gleason’s theorem to Aerts’s mechanism and the transactional waves; the distinctive element here is the identification of the physical, dynamically expanding fourth dimension with the measure-theoretic and complex-projective structure that produces the Born rule, together with the fact that the same physical object yields the metric, the arrow, and ħ. The exponent 2 is forced by four internal routes (rank-2 metric, parallelogram norm, unitarity with explicit exclusion of p ≠ 2, and phase invariance, §7.5–7.6); the composite and entangled cases follow through the joint Born rule on the product slice (§6.6.7.4). What the framework claims as new is therefore narrow and geometric: not that a sphere gives the Born rule, but that a physically expanding spacetime dimension is the object from which the rule — and the arena it acts in — descends.

#### 7.7.2 How Born arrived at the rule: the historical canvas against which the geometric derivation is set

The claim that the framework *derives* what Born *posited* requires an accurate account of how Born arrived at the rule, since the force of the claim depends on what was and was not established in 1926. The historical record is documented in Born’s 1926 paper (Born 1926, ref. [24]), his 1954 Nobel lecture, and the century of history-of-physics scholarship since (Landsman, “The Born rule and its interpretation”; the centenary review “The Born rule — 100 years ago and today,” arXiv:2502.08545). It shows that Born reached |ψ|² by physical analogy and empirical adequacy, and never by derivation from a principle — which is the precise sense in which “why the square?” remained an open question for a century.

*The problem Born was attacking.* In mid-1926, directly after Schrödinger’s wave mechanics appeared, Born applied it to electron–atom scattering. Schrödinger read ψ realistically: the wave packet was the electron, ψ a real charge or matter distribution spread through space. Born found this could not survive the collision problem: after scattering, the wave spreads as an outgoing spherical wave in all directions, yet experiment registers a whole electron arriving at one definite place on the detector. A smeared distribution cannot do this. Born concluded that Schrödinger’s mathematics was correct and his physical interpretation wrong, and in the 1926 paper wrote that quantum mechanics answers not “what is the state after the collision” but only “how probable is a given effect of the collision,” adding that “there is no quantity that in an individual case fixes the effect of the collision.” This is the introduction of fundamental indeterminism: Born relinquished the question of where the electron goes and kept only the probability.

*What motivated the idea: Einstein’s ghost field.* Born was explicit, in his 1954 Nobel lecture, that the idea came from Einstein: “Again an idea of Einstein’s gave me the lead. He had tried to make the duality of particles — light quanta or photons — and waves comprehensible by interpreting the square of the optical wave amplitudes as probability density for the occurrence of photons. This concept could at once be carried over to the ψ-function.” The model was Einstein’s “ghost field” (Gespensterfeld): a guiding field carrying no energy that sets where the photon is likely to be found. Born took ψ as the ghost field of de Broglie’s electron — ψ does not locate the electron, it sets the probability of finding it. The motivating problem was wave–particle duality: how a spread-out wave and a localized particle can be one thing, resolved by having the wave govern the probability and the particle be what is detected.

*Why the square, and the footnote added in proof.* The origin of the exponent is precise and documented. In the main text of the 1926 paper Born first wrote that ψ itself — the amplitude — gives the probability (*“ψ bestimmt die Wahrscheinlichkeit”*). In a footnote added in proof, after submission, he corrected it: the probability is proportional to |ψ|², the square of the modulus. The most consequential relation in quantum mechanics, P = |ψ|², thus entered physics as a hand-corrected footnote, and Born himself did not initially distinguish ψ from |ψ|² until he fixed it in proof. The square was reached by two converging analogies, neither a derivation. First, the optics analogy: in classical wave optics the intensity — the physically measurable energy density — is the square of the wave amplitude, and Einstein’s ghost-field move read this squared optical amplitude as photon probability density; Born carried it directly to ψ, inheriting the square from the fact that energy in any wave theory goes as amplitude squared. Second, two consistency requirements that only the square satisfies: ψ is complex, so ψ itself cannot be a probability, while |ψ|² = ψ^*ψ is real and non-negative; and only the squared modulus gives a conserved, normalizable total probability, ∫ |ψ|² d³x = 1 preserved under the evolution through the continuity equation. Born recognized after the fact that the square was the only quantity that could serve as a probability; he did not derive that it must be the square.

*The documented verdict.* The history-of-physics literature is uniform: Born reached the rule by analogy to optical intensity, corrected the amplitude-versus-square question in a footnote, and justified the result by its success in scattering, not by a principle. Born himself, the scholarship records, did not attempt to motivate the rule theoretically but appealed to experimental confirmation. This is why “why the square?” stands as a genuine open question of foundations rather than a settled matter: the exponent 2 was borrowed from classical wave-intensity and forced consistency-wise by the complex character of ψ and by probability conservation, but never grounded in a physical reason for the squaring itself.

*The framework against this canvas.* The McGucken derivation supplies the physical reason Born’s construction lacked, and it does so in the same element Born reached for. Born’s square came from wave intensity — amplitude squared — which is a property of a spherical wavefront; the framework identifies the wavefront as the physical McGucken Sphere and derives the exponent 2 from its geometry: the conservation of the Sphere’s weight under the second-order propagation that the rank-2 metric induces, forcing the quadratic density (Lemma 7.1), the parallelogram identity of the inner-product norm (Lemma 7.6), and the unitarity of the derived evolution excluding every p ≠ 2 (Theorem 9.2, §7.5–7.6), with the measure fixed as the unique SO(3)-invariant measure on the Sphere (Theorem 7.2, Lemma 7.1.5). The two analogies Born used are, in the framework, two faces of one derived fact: the intensity-equals-amplitude-squared of wave optics is the Huygens-wavefront intensity of the expanding McGucken Sphere (§4.3), and the consistency requirements Born noted — complex ψ, conserved |ψ|² — are the phase-invariance and unitarity that the same Sphere geometry enforces. Born inherited the square from the optics of intensity and could not say why; the framework derives it from the geometry of the expanding wavefront, and identifies Born’s own motivating analogy — the squared amplitude of a spherical wave — as the physics of dx₄/dt = ic. The century-old “why the square” is answered not by overturning Born’s route but by grounding the wave-intensity analogy he followed in the physical sphere whose invariant measure the square is.


### IV.3bis The McGucken Principle dx₄/dt = ic Reading of the nonlocality of the Born rule in the record, 1926–1964

The McGucken Principle dx₄/dt = ic predicts that the Born rule carries a nonlocality, and names its carrier: the McGucken Sphere is one object from its source event to every point of its wavefront, its volume defines the nonlocality (Principle 2.1), and when the Sphere collides with an absorber's Sphere at one event (Theorem 7.7 of [6]) the weight it carries — in standard terms the total probability — is read once, at that event, so that no second collision of the same Sphere occurs elsewhere on the wavefront. Born's rule of 1926 states a density; the single outcome per quantum and the normalization ∫ |ψ|² d³x = 1 over the whole slice are statements about every point of the wavefront at once. The record below shows that this was seen within a year of the rule's statement, was formalized as a postulate in 1932, was proved unavoidable in 1964, and at no point received a carrier. Each item is quoted from the primary text where one was retrieved, and each is followed by the reading the Principle gives it.

**Born 1926.** The rule enters physics as the footnote added in proof to "Zur Quantenmechanik der Stoßvorgänge" (*Zeitschrift für Physik* 37, 863–867), attached to the sentence stating that Φ^τₙₘ(α,β,γ) "bestimmt die Wahrscheinlichkeit dafür, daß das aus der z-Richtung kommende Elektron in die durch α, β, γ bestimmte Richtung … geworfen wird": "Anmerkung bei der Korrektur: Genauere Überlegung zeigt, daß die Wahrscheinlichkeit dem Quadrat der Größe Φ^τₙₘ proportional ist." Pais (*Science* 218, 1982, p. 1195) renders it "A more precise consideration shows that the probability is proportional to the square of" Φ and adds, "He should have said 'absolute square.'" The rule is stated as a density over scattering directions. Nothing in the paper addresses what the density does at the other directions when the electron is found in one.

*The McGucken Principle dx₄/dt = ic Reading.* The McGucken Principle dx₄/dt = ic predicts Born's density as the overlap ψ^*ψ of the scattered Sphere with the detector's Sphere (Theorem 7.4 of [6]), and the "Quadrat" of the footnote as the two participants in that collision (Theorem 7.7(iv), Lemma 7.7.5). Born's density is the Sphere's weight per unit area on the wavefront (Lemma 6.6C of [25]); the question his paper does not ask — what becomes of the weight at the other directions — is answered by the Sphere being one object across its volume.

**Einstein, Solvay 1927.** In the general discussion of the fifth Solvay Conference (*Électrons et Photons*, 1928, pp. 253–256; Bacciagaluppi and Valentini, *Quantum Theory at the Crossroads*, 2009, pp. 485–487, arXiv:quant-ph/0609184), Einstein set up the hemisphere: "Let S be a screen provided with a small opening O, and P a hemispherical photographic film of large radius." Under the reading in which "|ψ|² expresses the probability that at a given instant the same particle is present at a given point," he objected that the theory must prevent "the wave continuously distributed in space from producing an action in two places on the screen," since otherwise "the same elementary process produces an action in two or several places," and that this prevention is "an entirely peculiar mechanism of action at a distance." The objection is the earliest statement that the Born density, read for one particle, requires that a detection at one point of the wavefront exclude detection at every other point, at spacelike separation.

*The McGucken Principle dx₄/dt = ic Reading.* The McGucken Principle dx₄/dt = ic predicts Einstein's hemisphere as the wavefront of the electron's Sphere at the time t = r/c after it passes the opening, and the single blackened grain as the collision of that Sphere with the grain's Sphere (Theorem 7.7 of [6]), at which the Sphere's phase along x₄ = ict is rotated into one real weight (Theorem 12.2). The "mechanism of action at a distance" Einstein required is the Sphere's volume: the weight withdrawn from every other point of the hemisphere is withdrawn from the one object that reached them all, and the Principle states this as the nonlocality the Sphere's volume defines. Einstein's two readings of |ψ|² — a cloud of many electrons, or a complete account of one — are the Sphere read over an ensemble of collisions and the Sphere read in one collision.

**Heisenberg 1930.** In *The Physical Principles of the Quantum Theory* (Chicago, 1930; Eckart and Hoyt translation, Ch. II §2(d), p. 39) Heisenberg states the reduction for a photon at a half-silvered mirror: "By reflection at a semi-transparent mirror, it is possible to decompose it into two parts, a reflected and a transmitted packet. There is then a definite probability for finding the photon either in one part or in the other part of the divided wave packet. After a sufficient time the two parts will be separated by any distance desired; now if an experiment yields the result that the photon is, say, in the reflected part of the packet, then the probability of finding the photon in the other part of the packet immediately becomes zero. The experiment at the position of the reflected packet thus exerts a kind of action (reduction of the wave packet) at the distant point occupied by the transmitted packet, and one sees that this action is propagated with a velocity greater than that of light. However, it is also obvious that this kind of action can never be utilized for the transmission of signals so that it is not in conflict with the postulates of the theory of relativity." Heisenberg attributes the example to Einstein. This is the first statement in print that reading the Born density at one point changes it everywhere, and the first statement of the no-signalling clause that accompanies it.

*The McGucken Principle dx₄/dt = ic Reading.* The McGucken Principle dx₄/dt = ic predicts both halves of Heisenberg's sentence. The reflected and transmitted packets are the two branches of one Sphere re-sourced at the mirror (Theorem 7.12 of [6], every point of an aperture or mirror the centre of a new Sphere); a collision at the reflected branch is one collision of one Sphere, and the weight at the transmitted branch becomes zero because there is one weight (Lemma 6.6C of [25], conserved along the expansion). No signal passes because no second event occurs at the transmitted branch: the weight there was never a separate object that could carry one. Heisenberg's "velocity greater than that of light" measures the spatial separation of two points on one Sphere divided by zero elapsed coordinate time; it is a property of the Sphere's extent, and no influence propagates across it.

**von Neumann 1932.** *Mathematische Grundlagen der Quantenmechanik* (Beyer translation, 1955, Ch. V.1, p. 351) distinguishes two kinds of change of the statistical operator: "the arbitrary changes by measurements" (process 1) and "the automatic changes which occur with passage of time" (process 2), the second being the Schrödinger equation (the phrases quoted here are as given by Ellerman, arXiv:1812.09448, and two further secondary sources citing p. 351; the Beyer page itself was not retrieved and its full sentences are owed). Process 1 is the projection U → ∑ₙ (Uφₙ,φₙ) P_([φₙ]), applied to the whole state at the instant of measurement wherever the state extends. The reduction Heisenberg described in words is made an axiom; the axiom is stated for the state as a whole and so is nonlocal in exactly Einstein's sense, without the word.

*The McGucken Principle dx₄/dt = ic Reading.* The McGucken Principle dx₄/dt = ic predicts von Neumann's two processes as two readings of one Sphere: process 2 is the Sphere's expansion along x₄ = ict with its phase e^(iS/ħ), and process 1 is the collision at which x₄ = ict is rotated to ct and the phase becomes the real weight e^(-S/ħ) at one event (Theorem 12.2 of [6]). The projection applied "to the whole state" is the whole Sphere read once; Corollary 11.3 of [6] gives the Born probability in an arbitrary eigenbasis as the corollary of the position-space theorem, which is the content of von Neumann's process 1 without its status as a separate axiom.

**Einstein–Podolsky–Rosen 1935; Schrödinger 1935; Bell 1964.** The two-particle form of the question was posed by Einstein, Podolsky and Rosen ("Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?", *Physical Review* 47, 777) and named by Schrödinger, who introduced the word *Verschränkung* in "Die gegenwärtige Situation in der Quantenmechanik" (*Die Naturwissenschaften* 23, 1935). Bell, "On the Einstein Podolsky Rosen Paradox" (*Physics* 1, 195–200, 1964), opens: "It is the requirement of locality, or more precisely that the result of a measurement on one system be unaffected by operations on a distant system with which it has interacted in the past, that creates the essential difficulty," and, of Bohm's hidden-variable theory, "That particular interpretation has indeed a grossly nonlocal structure. This is characteristic, according to the result to be proved here, of any such theory which reproduces exactly the quantum mechanical predictions." He concludes (p. 199): "In a theory in which parameters are added to quantum mechanics to determine the results of individual measurements, without changing the statistical predictions, there must be a mechanism whereby the setting of one measuring device can influence the reading of another instrument, however remote. Moreover, the signal involved must propagate instantaneously, so that such a theory could not be Lorentz invariant." The statistical predictions Bell holds fixed are the Born probabilities |ψ(x₁, x₂)|² of the pair. The theorem is therefore a statement about the Born rule: no account of the pair's Born probabilities in which each detection depends only on its own locality reproduces them.

*The McGucken Principle dx₄/dt = ic Reading.* The McGucken Principle dx₄/dt = ic predicts what Bell's theorem requires and what Bell's "mechanism" is. The pair's amplitude ψ(x₁, x₂) is the Sphere of the pair's common source event read at two detection events, each a collision of that one Sphere with a detector's Sphere (Theorem 7.7 of [6]); the two detections share one object because the Sphere's volume reaches both. Bell's "signal" that "must propagate instantaneously" is, in this reading, the same quantity as Heisenberg's "velocity greater than that of light": the extent of one Sphere, across which nothing propagates. Bell's dichotomy — a local theory, or a theory with instantaneous influence between remote instruments — is answered by a third description that his premises do not list: one object with two reading events. The derivation of the Bell correlations themselves from the Principle lies in the corpus and outside this paper; what this section records is that the carrier Bell's theorem requires is the Sphere's volume, and that the Principle states this carrier as part of its ontology.

**Attribution across the record.** Born 1926 stated the rule as a density and did not address its nonlocality; Einstein 1927 saw the nonlocality as a mechanism of action at a distance that the rule requires; Heisenberg 1930 stated it as the reduction of the wave packet, propagated faster than light and unable to carry a signal; von Neumann 1932 made it process 1, an axiom applied to the whole state; Bell 1964 proved that the Born probabilities of a pair cannot be reproduced by any account in which each detection is local. None of the five supplied a physical object whose extent is the nonlocality. The McGucken Principle dx₄/dt = ic supplies it: the McGucken Sphere, whose volume defines the nonlocality (Principle 2.1), whose collision with an absorber's Sphere is the detection (Theorem 7.7 of [6]), whose weight is conserved along its expansion and read once (Lemma 6.6C of [25], Theorem 12.2 of [6]), and whose exponent 2 is the two participants in that one reading (Lemma 7.7.5). The Born rule for one quantum and one detection is the Sphere's nonlocality expressed as a probability; the local part of the rule, the form ψ^*ψ with exponent 2, is Lemma 7.1, and the nonlocal part, the single outcome and the normalization over the slice, is the Sphere's volume.



### IV.4 Three comparison tables: criteria, inputs, and spheres across every Born-rule programme

The McGucken Principle dx₄/dt = ic predicts that the Born rule is a theorem of one physical fact — the McGucken Sphere expanding at c from every event with the action h set by its wavelength — and that every rival derivation imports, somewhere, what the Sphere supplies. The three tables below set that prediction against each programme of §7.1 and each sphere tradition of §7.7.1, criterion by criterion. Every cell is taken from the diagnostics of §7.1, §7.1.9.A–D, §7.1.16 and §7.7.1 reproduced above, with the corpus theorem named where McGucken supplies the item; the McGucken column stands first throughout. In the tables, "postulated" means taken as a primitive input of the programme and "derived" means obtained as a theorem of dx₄/dt = ic.

**Table IV.4.A — Criteria matrix across the Born-rule programmes.**

| Programme | Arena (Hilbert space) | What does the derivational work | Source of the exponent 2 | Referent of the imaginary unit i | Detection-event mechanism | Independent routes to the exponent |
|:----------|:----------|:------------|:-----------|:-----------|:-----------|:------|
| **McGucken (2026)** | **Derived**: L² completion of x₄-projections (Theorem 6.1) | **The McGucken Principle dx₄/dt = ic alone**: Sphere overlap and collision (R1, R2), Sphere universality (R3), conservation of the Sphere's weight under its expansion (R4) | **Conservation under the Klein–Gordon propagation that (ic)² = -c² induces**: only the quadratic function of the modulus is conserved (Lemma 7.1); measure from SO(3) Haar uniqueness (Lemma 7.1.5) | **The axis perpendicular to x₁x₂x₃**, selected by Frobenius (Theorem 3.1) | **Head-on x₄-collision of emitter's and absorber's Spheres** (Theorem 7.7); physical Wick rotation (Theorem 12.2) | **Five**: conservation, Haar, norm, collision, PT-symmetry (Remark 7.17) |
| Born (1926) | Postulated (Schrödinger's ψ on 3-space) | Postulation; analogy to optical intensity | Borrowed from wave intensity; corrected from lvertψrvert in a footnote (§7.7.2) | Unaddressed | Postulated (the detector registers) | One (analogy) |
| Gleason (1957) | Postulated, dimension ≥ 3 | Non-contextual probability measure on closed subspaces | Frame-additivity forces the quadratic form tr(ρ P) | Unaddressed (operates inside complex 𝓗, §7.1.9.D) | None | One |
| Finkelstein (1965), Hartle (1968), Farhi–Goldstone–Gutmann (1989), Van Wesep (2006), Landsman (2008) | Postulated; infinite tensor products | Frequentist N → ∞ limit; relative-frequency operator whose form presupposes the rule | Presupposed in the frequency operator | Unaddressed | None | One |
| Deutsch (1999) | Postulated (Everettian) | Rationality axioms; equal-amplitude indifference principle (the Born measure restated) | Imported via the indifference principle | Unaddressed | None | One |
| Wallace (2010, 2012) | Postulated (Everettian) | Rationality axioms plus branch structure | Imported via rationality axioms | Unaddressed | None (branches, not events) | One |
| Zurek (2003, 2005) | Postulated; tensor-product structure and system/environment cut | Envariance (swap symmetry of entangled states) | Imported via the tensor-product structure | Unaddressed | None | One |
| Bohm (1952), Valentini–Westman (2005) | Postulated | Equivariant measure stipulated in the guidance equation; dynamical relaxation | Stipulated through the guidance equation | Unaddressed | Particle positions, with lvertψrvert² stipulated as equilibrium | One |
| Sebens–Carroll (2018) | Postulated (Everettian) | Self-locating uncertainty principle | Imported via the self-locating principle | Unaddressed | None (epistemic self-location) | One |
| Masanes–Galley–Müller (2019) | Postulated: Postulate (states) | Six postulates; ⋆-product associativity excludes n ≥ 2 (Theorem 18) | Associativity (postulated) forces n = 1; no physical reason given (§7.1.9.C) | Unaddressed: begins from complex ℂᵈ (§7.1.9.D) | None (OPFs) | One |
| Saunders (2021) | Postulated (Everettian) | Branch-counting normalization | Imported via branch counting | Unaddressed | None | One |
| QBism (Caves–Fuchs–Schack 2002, Fuchs 2010) | Postulated | Dutch-book coherence; Bayesian framework | Imported via coherence | Unaddressed | None (agent's experience) | One |
| Hardy (2001), Chiribella–D'Ariano–Perinotti (2011) | Reconstructed from operational axioms | Five operational axioms (Hardy); purification (CDP) | Reproduced operationally; the quadratic form not traced to physics | Unaddressed | None | One |
| Ichikawa (2018) | Postulated | Cox-theorem logical-inference axioms | Imported via inference axioms | Unaddressed | None | One |
| Goyal (2010) | Postulated | Information-geometric axioms | Complex amplitudes as a representational choice | A representational choice, not forced (§7.1.14) | None | One |
| Schlosshauer–Fine (2005) and the critical literature | — | Diagnostic only: every derivation needs an additional assumption whose origin is unexplained | — | — | — | — |
| Davies–Lewis (1970) | Postulated | POVM structure postulated on top of standard QM | Inherited from the projective rule | Unaddressed | Postulated (positive operators Pₖ) | One |
| Neumaier (2025) | Postulated (imported silently into the DRP) | Detector Response Principle: eight commitments under one name (§7.1.16) | Inherited through tr(ρ Pₖ) | Unaddressed | Postulated: "quantum measurement device" as primitive | One |

**Table IV.4.B — Inputs each programme takes as primitive, as named in the §7.1 diagnostics.** The counts for Masanes–Galley–Müller, Neumaier and McGucken are those established in §7.1.9.A, §7.1.16 and Principle 2.1; for the other programmes the inputs are listed as the diagnostics name them.

| Programme | Inputs taken as primitive | Count where established | McGucken theorem that derives the same item |
|:----------|:------------|:------|:-----------|
| **McGucken (2026)** | **dx₄/dt = ic: x₄ expanding as a spherically symmetric McGucken Sphere at c, its wavelength setting h** | **1** | — |
| Born (1926) | ψ as given; P = lvertψrvert² as axiom | — | Theorem 7.2 |
| Gleason (1957) | Hilbert space of dimension ≥ 3; probabilities live on closed subspaces; non-contextuality | — | Theorem 6.1; Lemma 7.1; R3 from Theorem 2.4(iv) |
| Frequentist programmes | Hilbert space; infinite tensor products; the relative-frequency operator | — | Theorem 6.1; Corollary 11.6 |
| Deutsch (1999) | Hilbert space; Everett branching; rationality axioms; equal-amplitude indifference | — | Theorem 6.1; Theorem 7.7 (branches as Sphere events) |
| Wallace (2010, 2012) | Hilbert space; branch structure; rationality axioms | — | Theorem 6.1; Theorem 7.7 |
| Zurek (2003, 2005) | Hilbert space; tensor-product structure; system/environment cut; swap symmetry | — | Theorem 6.1; Corollary 11.6; R3 from Theorem 2.4(iv) |
| Bohm, Valentini–Westman | Hilbert space; guidance equation; equivariant measure lvertψrvert² | — | Theorem 6.1; Lemma 7.1 |
| Sebens–Carroll (2018) | Hilbert space; Everett branching; self-locating uncertainty principle | — | Theorem 6.1; Theorem 7.7 |
| Masanes–Galley–Müller (2019) | Postulate (states); Postulate (transformations); Postulate (composite systems); OPF formalism (7–9); ⋆-product axioms (10–14) incl. associativity; possibility of state estimation | **6** (§7.1.9.A) | Theorem 6.1; Theorem 9.2; Corollary 11.6; x₄-projection; Fubini–Tonelli; d²-1 of the Sphere operator algebra (§7.1.9.B) |
| Saunders (2021) | Hilbert space; Everett branching; branch-counting normalization | — | Theorem 6.1; Theorem 7.7 |
| QBism | Hilbert space; Bayesian framework; Dutch-book coherence | — | Theorem 6.1; Theorem 7.2 |
| Hardy; Chiribella–D'Ariano–Perinotti | Five operational axioms (Hardy); purification and informational axioms (CDP) | — | Theorem 6.1; Lemma 7.1 |
| Ichikawa (2018) | Hilbert space; Cox-theorem axioms | — | Theorem 6.1; Theorem 7.2 |
| Goyal (2010) | Information-geometric axioms; complex amplitudes as representation | — | Theorem 3.1 |
| Davies–Lewis (1970) | The entire Hilbert-space formalism; the POVM structure | — | Theorem 6.1; Theorem 7.2 with Naimark dilation |
| Neumaier (2025) | Hilbert space; density-operator trace pairing; time as parameter; source stationarity; discrete detection events; finite label set K; operators Pₖ; "quantum measurement device" as primitive | **8** (§7.1.16) | Theorem 6.1; Corollary 11.1; dx₄/dt as time direction; Theorem 7.4; Theorem 7.7 |

**Table IV.4.C — The sphere traditions (§7.7.1): which sphere, and what it fixes.**

| Tradition | The sphere | Physical object or state space | Background | What fixes the measure | What fixes the square |
|:----------|:----------|:----------|:----------|:----------|:----------|
| **McGucken Sphere** | **The expanding fourth dimension itself, dx₄/dt = ic, radius ct from every event** | **Physical spacetime object** | **Generates the spatial slice, the metric, the arrow and ħ (§7.7.1)** | **Unique SO(3)-invariant measure on the physical wavefront** (Lemma 7.1.5) | **Conservation under the expansion** (Lemma 7.1); parallelogram norm (Lemma 7.6); unitarity excluding p ≠ 2 (§7.5); two-Sphere collision (Theorem 7.7); PT_E symmetry (Theorem 7.11) |
| Born 1926, Mott 1929 | Outgoing scattering wave eⁱᵏᶻ + f(θ,φ)eⁱᵏʳ/r | Physical wave in pre-existing 3-space | Fixed | Directional flux dilution | Imported from wave intensity |
| Gleason 1957; Busch, Caves–Fuchs–Manne–Renes POVM extensions | Unit sphere of normalized state vectors | Abstract state sphere | Fixed Hilbert space | Non-contextual additivity over orthonormal frames | Frame-additivity, with the inner product presupposed |
| Bloch 1946; Kibble 1979, Wootters 1981, Brody–Hughston 1999 | ℂℙ¹, Bloch/Poincaré and Fubini–Study spheres | State space | Fixed | Requires an independently justified measure | Cosine-squared of Bloch angle, a reformulation; the Bloch sphere is itself the phase-quotient of the McGucken Sphere (§6.2.12 of [1]) |
| Bell 1966, Kochen–Specker 1967, Mermin 1993; Aerts 1986 and extended Bloch/membrane models | Sphere of hidden directions or a fluctuating measurement interaction | Abstract sphere with a mechanical model | Fixed | Stochastic apparatus (rupture or response) measure | Integration of the apparatus measure |
| Cramer 1986, Kastner (transactional interpretation) | Retarded offer wave and advanced confirmation wave as spherical wavefronts | Waves in pre-existing spacetime | Fixed | None stated; no uniqueness theorem | Product ψψ^* of offer and confirmation, interpretive |
| Pitalúa-García | Bloch ball from relativistic spacetime-symmetry assumptions | State space reconstructed from symmetry | Fixed | Symmetry assumptions | Reconstruction; physical spacetime and state sphere kept distinct |
| Northey 2026 | Composite geometry built from constrained spinor bilinears (quaternionic Einstein–Cartan–Kibble–Sciama) | Static composite of field bilinears | Derived as composite, not expanding | Variational constraints | Spinor–geometry correspondence |

The three tables state the same result from three sides. Every programme of Table IV.4.A begins inside the arena that Theorem 6.1 derives and imports the item in its third column; the McGucken row imports nothing beyond the Principle. Every row of Table IV.4.B other than the first lists the Hilbert space as a primitive, and the fourth column names the theorem of dx₄/dt = ic that derives it. Every sphere of Table IV.4.C other than the first lives in a fixed background and has its measure or its square supplied from outside; the McGucken Sphere is the expansion that generates the background, and its metric rank and its SO(3) action supply the square and the measure as theorems.



## Part V. The derivation of the Born rule along the dx₄/dt = ic Algebraic Channel: the four requirements (R1)–(R4) and the uniqueness theorem

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts the algebraic form of the Born density before any mechanism is named: the density must be real (R1) and non-negative (R2) because it counts detection events; it must be invariant under a global phase (R3) because a global phase is a shift of the x₄-origin and the expansion is universal from every event; and it must be bilinear in (ψ, ψ^*) (R4) because the Minkowski metric that x₄ = ict induces via (ic)² = -c² is a rank-2 tensor. These four requirements, operating on the McGucken-derived Hilbert space, fix P = |ψ|² uniquely (Theorem 7.2). This is the dx₄/dt = ic Algebraic Channel derivation: it runs on the T-invariant structures — metric, sesquilinear pairing, norm, unitary group — and establishes that no other density is consistent with them. Sections 7.2–7.6 of [1] are reproduced verbatim and in full, followed by Corollary 11.3 of [1], which restates Theorem 7.2 for an arbitrary observable and so recovers the Dirac–von Neumann measurement axiom.


### V.1 The four requirements (R1)–(R4), the three lemmas, and Theorem 7.2


### 7.2 The McGucken strategy for the Born rule: derive P(x) = |ψ(x)|² as the unique density satisfying four requirements (reality, non-negativity, phase-invariance, bilinearity in (ψ,ψ*)), all four forced by the geometry of dx₄/dt = ic

The McGucken derivation operates one level upstream. ψ is constructed (Definition 2.6) as the projection of x₄-advance onto the spatial slice. The Hilbert space is constructed (Theorem 6.1) as the L² completion of the space of such projections. The Born density is then the unique density on this pre-Hilbert structure compatible with four physical requirements descending from dx₄/dt = ic.


### 7.3 The four requirements for the Born density forced by dx₄/dt = ic: reality, non-negativity, phase invariance under global x₄-shift, and locality with conservation under x₄'s expansion

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts that a probability density P on ℝ³ derived from the McGucken wavefunction ψ of Definition 2.6 satisfies four requirements, each supplied by a property of the Sphere, and that these four fix P = |ψ|² with the quadratic form as the conclusion rather than an input.

- **(R1) Reality.** P is real-valued. (A probability density counts detection events; it is real by physical interpretation.)
- **(R2) Non-negativity.** P ≥ 0. (Detection counts are non-negative; the Sphere collision of Theorem 7.7 at the detection event has a non-negative rate.)
- **(R3) Phase invariance under global x₄-shift.** P(e^(iα)ψ) = P(ψ) for all real α. (A global phase is a shift of the x₄-origin, and the expansion is the same from every event by the universality clause of Theorem 2.4(iv).)
- **(R4) Locality and conservation under x₄'s expansion.** (a) The density at an event B is a function of the wavefront at B; with (R3) this means P(x) = F(|ψ(x)|). This is Theorem 7.4: the density at B is the overlap at B of the forward and conjugate x₄-expansions. (b) The total ∫ P d³x is the same at every time. The expansion of x₄ carries the wavefront forward by the propagation W(t) = exp(-itΩ), where Ω = c(-∇² + μ²)^(1/2) with μ = mc/ħ is the positive-energy square root of the Klein–Gordon operator — the Klein–Gordon equation (Box - m²c²/ħ²)ψ = 0 being the differential expression of the McGucken-Sphere wavefront, Theorem 9.0 of [1] and the textbook's theorem QM T8 ([25] Chapter 8) — and the Sphere's weight — in standard terms the total probability it carries — is conserved along its expansion ([25] Lemma 6.6C step 2), so a detection is certain at every time. In the non-relativistic regime W(t) reduces to the Schrödinger evolution of Theorem 9.2.

Requirement (R4)(b) is the Sphere's conservation law, Lemma 6.6C of the textbook, applied to the wavefront: the weight the source deposits on its Sphere is neither created nor destroyed as x₄ advances. No bilinearity in (ψ, ψ^*) is required; Lemma 7.1 derives it.

### 7.4 Lemma 7.1: the conserved density is quadratic — conservation under x₄'s expansion forces F(s) = κs²

**Lemma 7.1 (Quadratic form from conservation under x₄'s expansion).** *Let F be continuous on [0, ∞) and twice continuously differentiable on (0, ∞), with F(0) = 0, F' bounded on bounded sets, and F(s) and sF'(s) both of order s^δ as s → 0 for some δ > 0. If ∫ F(|ψ(x, t)|) d³x is independent of t for every wavefront ψ(t) = W(t)f with f a Schwartz function, then F(s) = κ s² for a constant κ.*

*Notation for the proof.* R̂ is the operator that multiplies the Fourier transform by r(k) = ω_C + c|k|²/2μ - ω(k), where ω(k) = c(|k|² + μ²)^(1/2) and ω_C = cμ is the Compton frequency of Proposition 2.2. For x ≥ 0, 0 ≤ 1 + x/2 - (1 + x)^(1/2) ≤ x²/8, which gives 0 ≤ r(k) ≤ c|k|⁴/(8μ³).

*Proof.* Take a profile f = g e^(iθ) with g > 0 a Gaussian and θ a real smooth function with bounded derivatives, and its dilations f_λ(x) = f(x/λ), λ ≥ 1.

*Step 1, the derivative.* Since ∂ψ/∂ t = -iΩψ and |f| > 0, the derivative of |ψ| at t = 0 is Im(e^(-iθ)Ω f), and the difference quotients of F(|ψ|) are dominated by an integrable function, because F' is bounded on the range of |ψ| and ψ, Ωψ are Schwartz functions uniformly for t in a bounded interval. Hence

d/dt∫ F(|ψ|) d³x = ∫ F'(g) Im(e^(-iθ)Ω f) d³x, t = 0.


*Step 2, splitting Ω.* By the bound just stated, Ω = ω_C + (c/2μ)(-∇²) - R̂, where R̂ multiplies the Fourier transform by r(k) with 0 ≤ r(k) ≤ c|k|⁴/(8μ³). The term ω_C contributes Im(e^(-iθ)ω_C f) = 0.

*Step 3, the main term.* Im(e^(-iθ)(-∇² f)) = -(1/g) ∇·(g²∇θ). Integrating by parts twice, with H(s) = sF'(s) - 2F(s), so that H'(s) = sF''(s) - F'(s), and with no boundary terms because H(g) and gF'(g) are of order g^δ and g is a Gaussian,

∫ (F'(g))/g(-∇·(g²∇θ)) d³x = ∫ ∇(H(g))·∇θ d³x = -∫ H(g) ∇²θ d³x.


*Step 4, scaling.* For f_λ the main term equals -(c/2μ) λ∫ H(g)∇²θ d³x, since the volume element contributes λ³ and the Laplacian λ⁻². The remainder is bounded by sup|F'(g)|·‖(1 + |x|²/λ²)⁻¹‖₂·‖(1 + |x|²/λ²)R̂f_λ‖₂ ≤ Cλ^(3/2)·λ^(3/2 - 4) = Cλ⁻¹, because λ⁴ r(k/λ) and its first two derivatives are bounded by polynomials in |k| uniformly in λ ≥ 1.

*Step 5, conclusion.* Conservation makes the derivative vanish for every λ. Dividing by λ and letting λ → ∞ gives ∫ H(g)∇²θ d³x = 0 for every admissible θ, in particular for every smooth θ of compact support. So H(g(x)) is a continuous weakly harmonic function on ℝ³ that tends to H(0) = 0 at infinity, and it vanishes identically by the maximum principle. A Gaussian of height a takes every value in (0, a], so H(s) = 0 for all s > 0. Then sF'(s) = 2F(s), whose solutions are F(s) = κ s². ∎

For the Schrödinger propagation of Theorem 9.2, Ω is replaced by -(ħ/2m)∇² up to the rest-energy constant, Steps 2 and 4 are void, and Step 3 alone gives ∫ H(g)∇²θ d³x = 0.

*McGucken Principle anchor.* The exponent 2 is the exponent that x₄'s expansion conserves. The rank-2 character of the interval (ict)² = -c²t² enters through the Klein–Gordon equation, which is second order because the interval is quadratic, and the lemma shows that its propagation conserves the quadratic density and no other function of the modulus. The conservation itself is the Sphere's: Lemma 6.6C of the textbook, the weight of the Sphere conserved along its advance.

**Lemma 7.1.5 (Uniqueness of the SO(3)-invariant probability measure on the McGucken Sphere).** *The McGucken Sphere Σ₊(p) at parameter time t is a round 2-sphere S² of radius ct, carrying the transitive action of the rotation group SO(3) fixed by the isotropy of the x₄-expansion from p (clause 3 of §2.4). Then there exists a unique SO(3)-invariant Borel probability measure on the Sphere, namely the normalized round measure dμ(θ,φ) = sinθ dθ dφ/(4π), and every SO(3)-invariant probability density on the Sphere is this dμ. This is the measure that supplies the Born-rule probability over detection directions.*

*Proof.* The Sphere is a homogeneous space for SO(3): the isotropy of the expansion makes the action transitive, and the stabilizer of any direction is the subgroup SO(2) of rotations about that axis, so Σ₊(p) ≅ SO(3)/SO(2) = S². SO(3) is compact; by Haar's theorem (1933) every compact group carries a unique normalized invariant measure, which pushes forward to a unique invariant probability measure on any homogeneous space. Existence: dμ = sinθ dθ dφ/(4π) is invariant because rotations are isometries of the round metric and sinθ dθ dφ is its area element. Uniqueness: if ν is any SO(3)-invariant probability measure, then for continuous f, invariance plus transitivity give ∫ f dν = ∫ f dμ (both equal the round average f̄); since this holds for all continuous f, ν = μ by the Riesz representation theorem. The corresponding result [19] Theorem 22.6 develops the same uniqueness in the correlation setting; the self-contained statement is the one given here. ∎

*Remark 7.1.5a (Why this is the measure the Born rule needs).* A probability rule over outcomes requires a measure on the outcome space, and a measure is physically forced only if a symmetry singles it out uniquely. Minkowski's four-velocity norm u^μ u_μ = -c² carries no group action and hence no distinguished measure; the McGucken Sphere carries the transitive SO(3) action, and Lemma 7.1.5 shows this action forces exactly one probability measure. The Born-rule weight over detection directions is that measure. This is the route to P = |ψ|² that proceeds from the Sphere's *symmetry group*, independently of the route that proceeds from conservation under the Sphere's expansion (Lemma 7.1).

**Lemma 7.6 (Parallelogram identity from the sesquilinear inner product of the McGucken Hilbert space).** *Let ⟨·, ·⟩ : 𝓥 × 𝓥 → ℂ be the sesquilinear inner product ⟨φ, ψ⟩ = ∫ φ^*ψ d³x on the McGucken pre-Hilbert space 𝓥 of Theorem 6.1, whose quadratic diagonal ⟨ψ, ψ⟩ = ∫|ψ|² d³x is the conserved total of Lemma 7.1. Let ‖ψ‖ := √(⟨ψ, ψ⟩) be the associated norm. Then for all x, y ∈ 𝓥, the parallelogram identity*

‖x + y‖² + ‖x - y‖² = 2(‖x‖² + ‖y‖²)

*holds as a direct two-line algebraic consequence of sesquilinearity, without invocation of the Jordan–von Neumann theorem or any external functional-analytic input.*

*Proof.* By sesquilinearity (conjugate-linear in the first slot, linear in the second), direct expansion gives

‖x + y‖² = ⟨ x + y, x + y⟩ = ⟨ x, x⟩ + ⟨ x, y⟩ + ⟨ y, x⟩ + ⟨ y, y⟩ = ‖x‖² + 2Re⟨ x, y⟩ + ‖y‖²,

‖x - y‖² = ⟨ x - y, x - y⟩ = ⟨ x, x⟩ - ⟨ x, y⟩ - ⟨ y, x⟩ + ⟨ y, y⟩ = ‖x‖² - 2Re⟨ x, y⟩ + ‖y‖²,

using ⟨ y, x⟩ = ⟨ x, y⟩^* (conjugate symmetry of the McGucken inner product, established in §6.4 from the complex conjugation under the integral sign) so that ⟨ x, y⟩ + ⟨ y, x⟩ = 2Re⟨ x, y⟩. Adding the two expansions, the cross-terms ± 2Re⟨ x, y⟩ cancel:

‖x + y‖² + ‖x - y‖² = 2‖x‖² + 2‖y‖² = 2(‖x‖² + ‖y‖²). □

The Jordan–von Neumann theorem (1935) [26] gives the converse direction — that any norm satisfying the parallelogram identity arises from an inner product. In the McGucken dx₄/dt = ic framework the inner product is supplied by Theorem 6.1 and its quadratic diagonal is forced by Lemma 7.1, so the parallelogram identity is a downstream consequence and Jordan–von Neumann a consistency check rather than an upstream selection principle.

### 7.5 Theorem 7.2 (Born rule from dx₄/dt = ic): the unique density on ℝ³ satisfying (R1)–(R4) is P(x) = |ψ(x)|²

**Theorem 7.2 (Born rule from dx₄/dt = ic).** *Let ψ: ℝ³ → ℂ be the McGucken wavefunction of Definition 2.6. The unique density P: ℝ³ → ℝ_(≥ 0) satisfying (R1), (R2), (R3), (R4) is*

P(x) = (|ψ(x)|²)/(∫|ψ|² d³x).


*Proof.* By (R3) and (R4)(a), P = F(|ψ|). By (R4)(b) and Lemma 7.1, F(s) = κ s². (R1) and (R2) hold for κ > 0, and normalization fixes κ. ∎

*Status note (form of the Born rule derived).* Theorem 7.2 derives the *projective* form of the Born rule P = |ψ|² on the McGucken-derived Hilbert space 𝓗 — the form Born stated in 1926, the form in every textbook, and the form that the Dirac–von Neumann measurement axiom (Corollary 11.3) instantiates. The POVM generalization (Davies–Lewis 1970; Neumaier 2025; see §7.1.16) extends the projective form to real quantum measurements with finite efficiency, losses, dark counts, and simultaneous position–momentum readings. The POVM rule is recoverable in the McGucken dx₄/dt = ic framework via Naimark dilation: any POVM on 𝓗 lifts to a projection-valued measure on 𝓗 ⊗ 𝒦 for an ancilla space 𝒦, and Theorem 7.2 applies on the dilated space, reproducing the POVM rule on 𝓗.

*Extended status note (the exponent 2 reinforced through the Hilbert-space route).* The exponent 2 is derived in Lemma 7.1 from conservation of the density under x₄'s expansion, with the rank-2 character of (ic)² = -c² entering through the second-order Klein–Gordon equation (Theorem 9.0) whose positive-energy propagation W(t) the lemma uses. A second route to the same exponent descends from the Hilbert space itself, derived from dx₄/dt = ic in Theorem 6.1: the parallelogram identity of Lemma 7.6 and the L²-norm conservation under the McGucken-derived unitary evolution of Theorem 9.2. For p ≠ 2 the Lᵖ norm of a normalized solution of the Schrödinger equation is in general not preserved: for a normalized three-dimensional Gaussian wavepacket with spatial width σ(t) ∼ ħ t/(2mσ₀) at large t, ‖ψₜ‖ₚ ∼ σ(t)^(3(2-p)/(2p)), which decays for p > 2 (at p = 4 as t^(-3/4)) and grows for p < 2; only p = 2 makes the exponent vanish. Lesovik [27] gives the derivation of the exponent 2 from this unitarity argument on a given Hilbert space; in the McGucken dx₄/dt = ic framework it applies on the *derived* Hilbert space of Theorem 6.1 with the evolution derived in Theorem 9.2, and Lemma 7.1 is its general form, for an arbitrary function F of the modulus rather than the power laws |ψ|ᵖ alone.

The exponent 2 is therefore overdetermined by two McGucken-internal routes that share no intermediate machinery between the Principle and the conclusion. *Conservation Route:* dx₄/dt = ic → Klein–Gordon equation on the Sphere wavefront (Theorem 9.0) → positive-energy propagation W(t) → conservation of the Sphere's weight (Lemma 6.6C of [25]) → F(s) = κ s² (Lemma 7.1) → P = |ψ|² (Theorem 7.2). *Norm Route:* dx₄/dt = ic → Hilbert space as completion of x₄-projections (Theorem 6.1) → sesquilinear inner product → parallelogram identity (Lemma 7.6) → L² structure, reinforced by the unitarity of Theorem 9.2. Gleason (1957) derived the form of the Born rule on a *given* Hilbert space; Jordan–von Neumann (1935) characterized the parallelogram identity on *given* Lᵖ spaces; Lesovik (2014) derived the exponent from unitarity on a *given* Hilbert space. The McGucken dx₄/dt = ic framework operates one level upstream of all three: the Hilbert space is derived (Theorem 6.1), the conservation that forces the exponent is the Sphere's (Lemma 6.6C), and the inside-Hilbert-space arguments reinforce the exponent with their inputs themselves traced to dx₄/dt = ic.

### 7.6 Exclusion of the alternatives: |ψ|^p for p ≠ 2 fails conservation; the renormalized rules fail the finite rate c of x₄'s expansion

The McGucken Principle dx₄/dt = ic predicts that every alternative to |ψ|² fails one of two Sphere properties. The rules |ψ|ᵖ with p ≠ 2, together with ψ² and Reψ, are excluded by Lemma 7.1 and (R1), (R3): ψ² is complex-valued and changes under a global x₄-phase, Reψ changes under the phase, and no |ψ|ᵖ with p ≠ 2 is conserved under the propagation. The renormalized rules, such as |ψ|ᵖ/∫|ψ|ᵖ and Aaronson's |ψ|⁴/∑|ψ|⁴, conserve their total by construction, so Lemma 7.1 does not reach them. They are excluded by the finite rate c of x₄'s expansion: the probability of detection in a region can change only when a wavefront crosses its boundary. The statement and proof are given for the strictly causal propagation of the four-component wavefront under the Dirac equation. The textbook states it in covariant form, Theorem 9.1 of [25] (its theorem QM T9): “The matter wavefunction ψ : M_G → ℂ⁴ of a spin-1/2 massive particle of rest mass m” “satisfies (iγ^μ∂_μ - mc/ħ)ψ = 0, where γ^μ are 4 × 4 complex matrices satisfying the Clifford algebra {γ^μ, γ^ν} = 2η^(μν)1”, with M_G the McGucken manifold, the spacetime of expanding McGucken Spheres at every point. Multiplying by γ⁰ and writing β = γ⁰, αⱼ = γ⁰γʲ, p̂ = -iħ∇ gives the Hamiltonian form used below, iħ ∂ₜψ = H_Dψ with H_D = c α·p̂ + β mc², whose retarded propagator is supported in the null cone (Lemma 7.6A(iii)). The three facts about the Dirac equation that the proofs use are stated first.

**Lemma 7.6A (The Dirac matrices, the Dirac continuity equation, and light-cone support).** *(i) In the Dirac representation of the γ^μ of Theorem 9.1 of [25], β = γ⁰ = diag(1, 1, -1, -1) and αⱼ = beginpmatrix 0 & σⱼ σⱼ & 0 endpmatrix, so that α₁, α₃, β are real matrices and α₂ is imaginary; each αⱼ is Hermitian with eigenvalues ± 1, and α₁α₃ is unitary, anticommutes with α₁ and α₃, and commutes with α₂ and β. (ii) For a solution of iħ ∂ₜψ = H_Dψ, the density ρ = ψ^†ψ satisfies ∂ₜρ = -c ∇·(ψ^†αψ), so ∫ρ d³x is conserved. (iii) If f vanishes outside the ball B(x₀, R), then exp(-iH_Dt/ħ)f vanishes outside B(x₀, R + c|t|): the wavefront advances at most at the rate c.*

*Proof.* (i) is read off the matrices: σ₁, σ₃ are real and σ₂ is imaginary; (α₁α₃)^†(α₁α₃) = α₃α₁α₁α₃ = 1; α₁(α₁α₃) = α₃ = -(α₁α₃)α₁ and likewise for α₃; α₂ anticommutes with each factor, so it commutes with the product, and the same holds for β. (ii) ∂ₜρ = (∂ₜψ)^†ψ + ψ^†∂ₜψ = (i/ħ)[(H_Dψ)^†ψ - ψ^† H_Dψ]; the β mc² terms cancel because β is Hermitian, and the α·p̂ terms give (i/ħ)(-iħ c)[-(∇ψ)^†·αψ - ψ^†α·∇ψ] = -c ∇·(ψ^†αψ). (iii) Let B(t) = B(x₀, R + c(T - t)) for 0 ≤ t ≤ T and E(t) = ∫_(B(t))ρ d³x. Differentiating, with n the outward normal and dS the surface element, E'(t) = ∫_(B(t))∂ₜρ d³x - c∮_(∂ B(t))ρ dS = -c∮_(∂ B(t))(ψ^†(n·α)ψ + ψ^†ψ) dS ≤ 0, because n·α is Hermitian with eigenvalues ± 1, so |ψ^†(n·α)ψ| ≤ ψ^†ψ. Now take any point y at distance d > c t₁ from the support of f and apply this with the shrinking balls B(y, d - ct), 0 ≤ t ≤ t₁: E(0) = 0 and E' ≤ 0 give E(t₁) = 0, so ψ(y, t₁) = 0; the same holds for t < 0 by the symmetry t → -t, ψ → ψ^* with α₂ → -α₂. ∎

**Lemma 7.6B (The quadratic density is the only conserved one, for four-component wavefronts).** *Let F be continuous on [0, ∞) and twice continuously differentiable on (0, ∞), with F(0) = 0 and with F' and sF'' bounded on bounded sets. Write |ψ| = (ψ^†ψ)^(1/2). If the derivative at t = 0 of ∫ F(|ψ(x, t)|) d³x vanishes for every wavefront ψ(t) = exp(-iH_Dt/ħ)f with f smooth and of compact support, then F(s) = κ s².*

*Proof.* Put ρ = ψ^†ψ and G(ρ) = F(ρ^(1/2)), and K(s) = sG'(s) - G(s), so that K'(s) = sG''(s) and K(0) = 0.

*Step 1, the derivative.* By Lemma 7.6A(ii), ∂ρ/∂ t = -c ∇·(ψ^†αψ). The difference quotients of F(|ψ|) are dominated by sup|F'|·sup|∂ψ/∂ t|, which is integrable. Where f ≠ 0 they converge to G'(ρ) ∂ρ/∂ t. Where f = 0, also ∂ψ/∂ t = -(i/ħ)H_Df = 0 at t = 0 because H_D is a differential operator, so |ψ(x, t)| is of order t² and the quotient tends to zero. Hence the derivative at t = 0 is -c∫ G'(ρ) ∇·(ψ^†αψ) d³x.

*Step 2, a family of profiles.* Let u₊ = (1, 0, 0, 1)/√() and u₋ = (1, 0, 0, -1)/√(), the eigenvectors of α₁ with eigenvalues +1 and -1. Take f = g(x)[cosχ(x) u₊ + sinχ(x) u₋] with g ≥ 0 smooth of compact support and χ real and smooth. A direct computation with the matrices of Lemma 7.6A(i) gives ρ = g² and ψ^†αψ = g²(cos 2χ, 0, 0).

*Step 3, integration by parts.* -c∫ G'(g²) ∂₁(g²cos 2χ) d³x = c∫∂₁(K(g²))cos 2χ d³x. The boundary terms vanish because g has compact support and sG'(s) → 0 as s → 0.

*Step 4, conclusion.* If this vanishes for every χ, then ∫∂₁(K(g²)) w d³x = 0 for every smooth w with |w| < 1 (take χ = (2arccos w)/()), so K(g(x)²) does not depend on x₁. It equals K(0) = 0 outside the support of g, so it vanishes everywhere. Multiplying g by constants covers every value s > 0, so K = 0, hence G'' = 0, G(ρ) = κρ, and F(s) = κ s². ∎

**Theorem 7.6C (The Born density for spin-½, including rules that renormalize).**

*(i) If the detection density is ρ = F(|ψ|) with F as in Lemma 7.6B and its total is conserved by the propagation, then ρ = κ ψ^†ψ.*

*(ii) Consider instead the renormalized rules ρ_F = F(|ψ|)/∫ F(|ψ|) d³x, with F as in Lemma 7.6B, F ≥ 0 and not identically zero. Impose regional constancy: if at t = 0 the wavefront is f₁ + f₂ with f₁, f₂ smooth, supported in balls B₁ and B₂ whose distance exceeds 2cT, then for |t| < T the probability of detection within distance cT of B₁ does not depend on t. Then F(s) = κ s² and ρ_F = ψ^†ψ/⟨ψ, ψ⟩.*

*(iii) The density ψ^†ψ/⟨ψ, ψ⟩ satisfies regional constancy.*

*Proof.* (i) Lemma 7.6B. (ii) Write Φ(ψ) = ∫ F(|ψ|) d³x. By Lemma 7.6A(iii), for |t| < T the two pieces ψ₁(t), ψ₂(t) stay within distance cT of B₁ and B₂ and have disjoint supports. Since F(0) = 0, the probability of the first region is Φ(ψ₁(t))/(Φ(ψ₁(t)) + Φ(ψ₂(t))). Its constancy means Φ(ψ₁(t))/Φ(ψ₂(t)) is constant. Φ is invariant under translations, so any two profiles of compact support can be placed in such balls, and the logarithmic derivative Λ(f) of Φ(ψ(t)) at t = 0 is the same number for every profile f of compact support. Let (Theta f)(x) = α₁α₃ f^*(x), with f^* the complex conjugate. By Lemma 7.6A(i), α₁, α₃ and β are real and α₂ is imaginary, and the matrix α₁α₃ is unitary, anticommutes with α₁ and α₃, and commutes with α₂ and β; complex conjugation sends p̂ = -iħ∇ to -p̂ and α₂ to -α₂. Therefore H_DTheta = Theta H_D, and since Theta is antilinear, exp(-iH_Dt/ħ)Theta f = Thetaexp(+iH_Dt/ħ)f. Also |Theta f| = |f| pointwise. Hence Φ((Theta f)(t)) = Φ(f(-t)) and Λ(Theta f) = -Λ(f). Since Λ is the same for all profiles, Λ = 0, and Lemma 7.6B gives F(s) = κ s². (iii) For F(s) = s², Φ(ψⱼ(t)) = ⟨ψⱼ, ψⱼ⟩ is conserved for each piece by Lemma 7.6A(ii). ∎

*McGucken Principle anchor.* The McGucken Sphere expands at the finite rate c, so the probability of detection in a region can change only when a wavefront crosses the boundary of that region. A rule |ψ|ᵖ/∫|ψ|ᵖ with p ≠ 2 violates this: the probability in one region changes as a distant packet spreads, with nothing passing between them. Theorem 7.6C shows that the finite rate of x₄'s expansion, together with the dependence of the density on the modulus of the wavefront, leaves ψ^†ψ as the only rule, with no bilinearity assumed. The map Theta used in the proof is the time-reversal symmetry of the free Dirac flow, which reverses the orientation of the propagation and leaves the modulus unchanged; it is a symmetry of the T-invariant algebra of the dx₄/dt = ic Algebraic Channel (Theorem 16.2) and makes no statement about the physical +ic orientation of the Sphere, which the dx₄/dt = ic Geometric Channel carries (Theorem 16.1) and which Theorem 7.7 uses at the detection event.



### V.2 The Born rule for an arbitrary observable: the Dirac–von Neumann measurement axiom as a corollary

The McGucken Principle dx₄/dt = ic predicts that the requirements (R1)–(R4) are basis-independent on the derived Hilbert space, so that the position-basis density |ψ(x)|² and the eigenbasis probability |⟨ aₙ|ψ⟩|² are one theorem in two formulations. Corollary 11.3 of [1] is reproduced here.


### 11.4 Corollary Dirac–von Neumann axiom 3: The Born rule

**Corollary 11.3 (Dirac–von Neumann measurement axiom from Theorem 7.2).** *Let Â be a self-adjoint observable with spectral decomposition Â = ∑_n a_n |a_n⟩⟨ a_n| (for the discrete case; the continuous case extends analogously via the spectral measure). Let ψ be a normalized state. Then the probability of obtaining outcome a_n on measurement is*

P(a_n) = |⟨ a_n | ψ ⟩|².

*For a density operator ρ, the probability is P(a_n) = ⟨ a_n | ρ | a_n ⟩ = tr(P_n ρ), where P_n = |a_n⟩⟨ a_n| is the projector onto the a_n-eigenspace.*

*Proof.* By Theorem 7.2, the unique probability density on the McGucken-derived Hilbert space satisfying reality, non-negativity, phase invariance, and bilinearity in (ψ, ψ^*) is P = |ψ|². The position-basis statement is the integral form ∫_ℝ³ |ψ(x)|² d³x = 1 over the spatial slice.

For an arbitrary observable Â with eigenbasis |a_n⟩, expand ψ in this basis:

|ψ⟩ = ∑_n c_n |a_n⟩, where c_n = ⟨ a_n | ψ ⟩.

The probability of the system being in the a_n-eigenstate is the squared modulus of the coefficient c_n — by the same uniqueness argument as Theorem 7.2 applied in the |a_n⟩ basis rather than the position basis. The Born requirements (R1)–(R4) are basis-independent: reality, non-negativity, phase invariance, and bilinearity in (ψ, ψ^*) hold in any orthonormal basis of the McGucken-derived 𝓗. Hence the unique density on the |a_n⟩-coefficient c_n is |c_n|², giving

P(a_n) = |c_n|² = |⟨ a_n | ψ ⟩|².

For density operators, the same argument applied to the convex combination ρ = ∑_i p_i |ψ_i⟩⟨ψ_i| gives

P(a_n) = ∑_i p_i |⟨ a_n | ψ_i ⟩|² = ⟨ a_n | ρ | a_n ⟩ = tr(P_n ρ). ∎

The Dirac–von Neumann measurement axiom is therefore Theorem 7.2 re-expressed in arbitrary-observable language. The position-basis statement of Theorem 7.2 and the eigenvector-basis statement of Corollary 11.3 are the same theorem in two formulations. No new derivational content.

**Remark 11.3b (dx₄/dt = ic anchoring of Corollary 11.3).** *Corollary 11.3 descends from Theorem 7.2 (Born rule from dx₄/dt = ic) by basis-independence. The dx₄/dt = ic content of the position-basis Born rule transfers to the eigenvector-basis Born rule unchanged: the rank-2 sesquilinear pairing inherited from (ict)² = -c² t² of Lemma 2.5 (operative (C2) perpendicularity marker, (C1) rate c) supplies the bilinearity in (ψ, ψ^*); the Haar measure on the McGucken Sphere S² ≅ SO(3)/SO(2) at every event ([19 §16.5 Theorem PT2(iii)]; (C5) Sphere generation) supplies the squared-modulus density structure; the Born density |cₙ|² = |⟨ aₙ|ψ⟩|² at the eigenvector basis is the same Sphere-overlap content read in a different orthonormal basis of the McGucken-derived Hilbert space (Theorem 6.1). The dx₄/dt = ic machinery operative in Corollary 11.3 is: (C2) perpendicularity marker giving the rank-2 sesquilinear pairing; (C5) Sphere supplying the Haar measure structure; basis-independence transfers these from position basis to eigenvector basis without loss of dx₄/dt = ic content. See §17.6.11 for the comprehensive audit position.*


## Part VI. The derivation of the Born rule along the dx₄/dt = ic Geometric Channel: overlap, collision, PT-symmetry, and interference

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts what the density of Part V physically is. The forward x₄-expansion from the source event carries phase from x₄ = ict; the conjugate expansion carries phase from x₄^* = -ict; their overlap at the detection event is ψ^*ψ (Theorem 7.4). The conjugate expansion has a physical referent: it is the absorber's own forward Sphere viewed from the emitter's frame, where it is antiparallel in x₄, so that the detection event is the head-on x₄-collision of two physical McGucken Spheres and the exponent 2 counts the two participants (Theorem 7.7, Lemma 7.7.5). For a free particle before detection the conjugate factor is supplied by the Sphere's own reflection symmetry through its source event, ψ(PT_E·event) = ψ^*(event) (Theorem 7.11). Single-slit and double-slit interference follow as the self-overlap of several Spheres at the detector (Theorem 7.12). This is the dx₄/dt = ic Geometric Channel derivation: it runs on the +ic-oriented Sphere itself and establishes the mechanism of the rule. Sections 7.8–7.11 of [1] are reproduced verbatim and in full.


### 7.8 Theorem 7.4: the geometric meaning of ψ*ψ — the Born density at event B is the geometric overlap at B of the forward x₄-expansion (carrying phase from x₄ = ict) and the conjugate x₄*-expansion (carrying phase from x₄* = -ict)

The uniqueness theorem establishes *that* P = |ψ|². The geometric meaning of why follows from the construction.

**Definition 7.3 (Conjugate expansion).** *The* conjugate *of the McGucken expansion x₄ = ict is the expansion obtained by complex-conjugating both sides: (x₄)* = (ict)* = −ict. We denote this conjugate x₄-coordinate by x₄* = −ict.* Geometrically, complex conjugation reverses the orientation of the perpendicular x₄-axis: where the forward expansion advances at +ic, the conjugate expansion has the opposite orientation. The conjugate is the same expansion read in opposite orientation; it has no independent physical existence. The conjugate wavefunction ψ*(B) = ∑_γ exp(−iS[γ]/ℏ) is the path-integral expression of this conjugate-orientation reading: same paths, opposite phase.

**Theorem 7.4 (Geometric meaning of the Born rule).** *The Born density P = ψ* ψ at an event B is the geometric overlap, at B, of the forward x₄-expansion (carrying phase from x₄ = ict) and the conjugate x₄*-expansion (carrying phase from x₄* = −ict). The overlap decomposes into diagonal terms (probability contributions from individual paths) and off-diagonal terms (interference between distinct paths), with the off-diagonal interference being the geometry of quantum coherence.*

*Proof.* By Theorem 3.1, the McGucken wavefunction (equivalently, the path-integral propagator) from event A to event B is

K(B, A) = ∑_γ: A → B exp ((i S[γ])/(ℏ)),

where γ ranges over paths from A to B with B ∈ 𝓜_A(t) on the null wavefront of the x₄-expansion from A, and S[γ] is the action along γ. By Definition 7.3, the conjugate kernel obtained by reversing the orientation of x₄ (equivalently, complex-conjugating each factor in the path-sum) is

K^*(B, A) = ∑_γ : A → B exp (-(i S[γ])/(ℏ)).

The Born density at B is the product ψ^*(B) ψ(B) = K^*(B, A) K(B, A) (relative to a source event A; the absolute-position case takes A as the preparation event of the system). Expanding the product:

P(A → B) = K^*(B, A) K(B, A) = (∑_γ' e⁻i S[γ']/ℏ) (∑_γ eⁱ S[γ]/ℏ) = ∑_γ, γ' eⁱ (S[γ] - S[γ'])/ℏ.

This double sum has two derivationally distinct contributions:

*Diagonal terms (γ = γ’).* When the two indices coincide, S[γ] - S[γ’] = 0 and e^i · 0 = 1. The diagonal contribution is

∑_γ 1 = Nₚaths(A → B),

the count of distinct paths from A to B with B on the null wavefront 𝓜_A(t) (regularized by the path-integral measure; for the continuum, replaced by the appropriate path-integral norm). These are the *probability* contributions from each path treated independently — classical-particle-like terms.

*Off-diagonal terms (γ ≠ γ’).* When the indices differ, S[γ] - S[γ’] ≠ 0 in general, and e^i(S[γ] - S[γ’])/ℏ is a nontrivial phase. These are *interference* contributions, with phase determined by the action difference between the two paths. Summing over γ ≠ γ’ produces the constructive and destructive interference patterns characteristic of quantum mechanics (the double-slit pattern, the Aharonov–Bohm phase, the interference fringes in any quantum experiment).

The total density P(A → B) is therefore the geometric overlap of the forward x₄-expansion with the conjugate x₄-expansion at B, with the diagonal terms supplying the classical-probability-like content and the off-diagonal terms supplying the quantum-coherent interference content. The two together are the “two expansions meeting at B” — a geometric picture in which the macroscopic apparatus, localized at a definite x₄-coordinate by prior decoherence, is the location at which the forward expansion (carrying phase from x₄ = ict) and the conjugate expansion (carrying phase from x₄^* = -ict) overlap. The probability of detection is the overlap density ψ^* ψ. The “collapse” is the geometric incidence of the two expansions on a localized absorber. ∎

**Remark 7.4b (dx₄/dt = ic anchoring of Theorem 7.4 — the geometric meaning of |ψ|²).** *Theorem 7.4 supplies the geometric mechanism for the Born rule: |ψ|² at event B is the geometric overlap of the forward x₄-expansion (phase from x₄ = ict) and the conjugate x₄^*-expansion (phase from x₄^* = -ict) at B. The dx₄/dt = ic content operative: (C2) perpendicularity marker i supplies the complex phase exp(iS[γ]/ħ) in both forward and conjugate kernels; (C5) Sphere generation supplies the McGucken Sphere 𝓜_A(t) on which the wavefunction propagates from source event A; (C6) Huygens-Fresnel-Kirchhoff Sphere self-replication supplies the propagation mechanism; (C3) action quantum ħ supplies the action-quantization scale in exp(iS[γ]/ħ); Definition 7.3 supplies the conjugate expansion as the orientation-reversed reading of dx₄/dt = ic (i.e., -ic rather than +ic). The identification of the conjugate expansion with the absorber’s forward expansion viewed from the emitter’s frame (Theorem 7.7) supplies the physical interpretation: the conjugate is the same expansion read from the antipodal frame. The diagonal+off-diagonal decomposition |c_γ|² + 2Re(c_γ^* c_(γ')) supplies the classical-probability + quantum-interference content. The dx₄/dt = ic machinery in Theorem 7.4 is: (C2), (C3), (C5), (C6); the cascade-upstream dependence is Theorem 3.1 (complex amplitudes) → Definition 2.6 (wavefunction) → Theorem 7.2 (Born rule uniqueness) → Theorem 7.4 (geometric reading). See §17.6.7 for the comprehensive audit position.*

**Proposition 7.5 (Malus correspondence).** *The Born rule is to x₄-projection what Malus’s law is to spatial projection: the squared cosine of the angle between the polarization direction (the x₄-direction along which the state advances) and the projection axis (the spatial slicing of the measurement) gives the transmitted intensity.*

This is the geometry of the squaring. Classical optics has used the squared-projection move since Malus in 1809. The Born rule is the same move in a different setting: project a unit four-velocity component along x₄ onto the spatial slicing of a measurement, the projection density is the squared modulus.

**Remark 7.5b (dx₄/dt = ic anchoring of Proposition 7.5).** *The Malus correspondence makes the dx₄/dt = ic content of the Born rule explicit. In Malus’s 1809 setup, a polarized light beam with polarization direction p̂ encountering a polarizer with transmission axis â has transmitted intensity Iₜ = I₀ cos²θ where θ = ∠(p̂, â) — the squared cosine of the angle between polarization direction and transmission axis. In the McGucken dx₄/dt = ic framework reading: the polarization direction is the x₄-direction along which the McGucken-Sphere wavefront advances at +ic (the universal feature of dx₄/dt = ic at every event); the transmission axis is the spatial-slice direction of the measurement (the projection of the McGucken Sphere onto the spatial slice at parameter time t); the squared cosine |cosθ|² of the angle between x₄-direction and projection axis gives the projection probability density at the measurement event. The Born rule P(x) = |ψ(x)|² is precisely Malus’s law applied to the x₄-projection: θ is the angle between the wavefunction’s x₄-perpendicular direction and the spatial-slice projection axis at the measurement event; |cosθ|² = |ψ(x)|² is the projection density at that event. The dx₄/dt = ic machinery operative in Proposition 7.5 is: (C2) the perpendicularity of x₄ to the spatial slice (the wavefunction’s complex character marks this perpendicularity via Theorem 3.1); (C4) per-event universality of the x₄-perpendicular direction at every event of 𝕄_G; (C5) the McGucken Sphere supplying the geometric structure that the projection operates on at every event. The Malus correspondence makes the Born rule’s content visible as a per-event projection-squared operation, with dx₄/dt = ic supplying the x₄-perpendicular direction that is being projected. See §17.6.7 for the comprehensive audit position.*

### 7.9 The physical mechanism: Born rule as head-on x₄-collision of two McGucken spheres

Theorem 7.4 established that the Born density ψ^*ψ at a detection event B is the geometric overlap of the forward x₄-expansion (carrying phase from x₄ = ict) and the conjugate x₄-expansion (carrying phase from x₄^* = -ict) at B. The reading is geometrically complete but leaves one physical question open: what is the physical referent of the conjugate sphere? On the geometric-overlap reading alone, the conjugate is the orientation-reversed image of the forward expansion — an algebraic partner of ψ with no independent physical existence required. This subsection identifies the conjugate sphere physically: it is the absorber’s own forward x₄-expansion, viewed from the emitter’s frame, where it appears antiparallel in x₄. The Born rule’s bilinearity then has an explicit two-particle physical mechanism — the head-on x₄-collision of the two McGucken spheres at the detection event — and the rotation-out-of-x₄ that Theorem 12.2 will identify as the universal measurement mechanism is here exhibited as the result of x₄-momentum cancellation at the collision.

**Theorem 7.7 (Born rule as head-on x₄-collision of two McGucken spheres).** *Let particle A at event E_A and particle B at event E_B each propagate, by the canonical ontology (clause 3, §2.4) and Definition 2.6, a McGucken sphere outward at dx₄/dt = +ic in its respective rest frame. Let P ∈ 𝓜_{E_A}(t) ∩ 𝓜_{E_B}(t) be a spacetime event where both McGucken spheres arrive on the spatial slice at parameter time t. Then:*

*(i) (Frame-relational antiparallelism in x₄.) In A’s rest frame at P, A’s outgoing x₄-component carries the signature dx₄/dt|_A = +ic. B’s outgoing x₄-component along the shared spatial geodesic from E_B to P, as expressed in A’s frame at P, carries the opposite sign: dx₄/dt|_B (as seen in A’s frame at P) = -ic. By the A↔B symmetry of the construction, the converse holds in B’s rest frame.*

*(ii) (Algebra of the antiparallelism.) The antiparallel signs in (i) realize, frame-relationally, the algebraic conjugation z ↔ z^* on the imaginary unit: i ↔ -i. The conjugate kernel ψ^* of Definition 7.3 is therefore the absorber’s forward x₄-expansion viewed in the emitter’s frame; equivalently, ψ is the emitter’s forward x₄-expansion viewed in the absorber’s frame. Complex conjugation in the Born rule is the dx₄/dt = ic framework’s expression of the frame-relational relationship between the two physical participants in the head-on collision.*

*(iii) (x₄-momenergy cancellation forces 3-localization.) Each McGucken sphere carries x₄-component of four-momentum p_4 = i m c in its own rest frame (the four-momentum form of dx₄/dt = ic; cf. §9.2 step 1 and the four-velocity budget u^μ u_μ = -c² of §2.3). At the head-on meeting P, the two x₄-momenta, expressed in a common frame, are antiparallel: p_4^A = +imc and p_4^B = -imc in A’s frame at P (for identical-mass particles; the relative x₄-momentum vanishes more generally in the center-of-momentum frame along the head-on axis). The sum of x₄-components vanishes at P. By four-momentum conservation (translation invariance of the Lorentzian metric, Lemma 2.5), the momenergy that cancelled in x₄ must reappear in x₁x₂x₃ at P. Both particles are thereby rotated out of pure x₄-expansion and localized at P — the geometric reorientation that Theorem 12.2 will name “rotation out of x₄.”*

*(iv) (Bilinear collision rate.) The local rate of the head-on collision event at P is the sesquilinear product ψ_A(P) · ψ_B^*(P) up to a positive normalization constant. The product structure ψ_A(P) · ψ_B(P) of the two amplitudes is derived rigorously in Lemma 7.7.5 Step 1 below from action-additivity of independent paths, ruling out sum, max, min, arithmetic/geometric/harmonic means as candidate functional forms. The conjugation ψ_B ⇝ ψ_B^* that converts the forward × forward product to the Born sesquilinear ψ · ψ^* is derived in Lemma 7.7.5 Step 2 from the complexification of the symmetric rank-2 metric (Lemma 2.5) combined with R1 (real Born density on diagonal) — the bilinear complex extension fails R1, only the sesquilinear extension gives a real diagonal for symmetric forms. The conjugation is therefore the CONJUGATION of the sesquilinear inner product, NOT a Lorentz-boost frame change (the action S is a Lorentz scalar) and NOT the Stueckelberg–Feynman time-reversal postulate (which is one PHYSICAL INTERPRETATION but not the source of the conjugation). Higher-rank pairings (cubic, quartic, etc.) are excluded by the same rank-counting that excluded them in Theorem 7.2.*

*(v) (Reduction to single-particle ψ^*ψ.) For single-particle QM with a macroscopic absorber localized at P by prior decoherence (the standard idealization of a detector), the absorber is well-modeled as a localized point at P whose McGucken sphere’s forward x₄-expansion is, in the emitter’s frame, the conjugate kernel ψ^* by (ii). The collision rate at P reduces to ψ^*(P) ψ(P) = |ψ(P)|², recovering the Born rule of Theorem 7.2 as the rate of head-on x₄-collisions between the emitter’s outgoing sphere and the absorber’s outgoing sphere viewed conjugately.*

**Proof.**

*(i)* By canonical clause 3 (§2.4), the McGucken sphere expansion from any event proceeds isotropically at rate c with respect to that event’s rest frame. The spatial-slice projection of A’s expansion at P points from E_A toward P along the spacelike geodesic E_A P; in A’s rest frame, A’s x₄-component advances at dx₄/dt = +ic along this expansion. The spatial-slice projection of B’s expansion at P points from E_B toward P along E_B P; in B’s rest frame, B’s x₄-component advances at dx₄/dt = +ic. The two spheres meet at P traveling toward each other in spacelike orientation. Express B’s outgoing x₄-component in A’s frame at P: along the line E_A P E_B at P, A’s outgoing x₄-direction is the +ic direction (by A’s frame definition), and B’s outgoing x₄-direction at P points back toward E_B along the same spacelike line, which is the opposite spatial orientation — and by the same construction of “outgoing x₄-direction at P relative to the source,” in A’s frame this is the -ic direction. The antiparallelism follows. The A↔B symmetry of the entire construction yields the converse in B’s frame.

*(ii)* Complex conjugation in ℂ is the orientation reversal of the imaginary axis: i ↔ -i. The i-marker for x₄-perpendicularity (Theorem 3.1, §4.3) thereby reverses sign under conjugation, exactly as in (i). The conjugate kernel ψ^*(B) = ∑_γ exp(-iS[γ]/ℏ) of Definition 7.3 is the path-integral expression of orientation-reversed expansion; by (i), this orientation reversal is the absorber’s forward x₄-expansion (which is +ic in its own frame) as seen from the emitter’s frame (-ic). The conjugate is therefore the absorber-frame partner of the emitter’s forward expansion — the dx₄/dt = ic framework’s frame-relational reading of complex conjugation.

*(iii)* By the four-velocity budget (§2.3, §9.2 step 1), each particle’s four-momentum in its rest frame has x₄-component p_4 = i m c, with full magnitude m c² the rest-energy content (mass-energy equivalence descending from the same dx₄/dt = ic — cf. companion paper [2] for the corpus derivation). At the head-on collision at P, the two x₄-momentum components in a common frame are antiparallel by (i); for identical-mass particles their sum vanishes, and for non-identical masses the sum vanishes in the center-of-momentum frame along the head-on axis. Four-momentum is conserved at P (translation invariance of the Lorentzian metric, Lemma 2.5). What cancels in the x₄-component must therefore reappear in the x₁x₂x₃-components for total four-momentum to be conserved at P. The cancelled x₄-momenergy is deposited as 3-spatial momenergy at P, rotating both particles’ free four-velocity budget from x₄-dominated to spatial-dominated — both particles localized at P.

*(iv)* The probability per unit time per unit spatial volume at P of the head-on collision event is the sesquilinear product ψ_A(P) · ψ_B^*(P) of the two amplitudes (with the conjugation of ψ_B^* prescribed by the postulated frame-relational antiparallelism of (i)-(ii) — see Step 2 of Lemma 7.7.5 below for the honest accounting of this conjugation as a postulate, not a frame consequence). The product structure ψ_A · ψ_B — rather than sum, max, geometric mean, or any other symmetric function of the two amplitudes — is derived rigorously in Lemma 7.7.5 Step 1 below from action-additivity of independent paths combined with the exponential phase of each McGucken-Sphere wavefront. The conjugation ψ_B ⇝ ψ_B^* that converts the forward × forward product to the Born sesquilinear is the input doing the work and is currently a postulate, with three plausible derivation routes identified in Remark 7.7.7. Higher-rank pairings (cubic, quartic, etc.) are excluded by the same rank-counting that excluded them in Theorem 7.2.

*(v)* For single-particle QM with a localized macroscopic absorber, the absorber is modeled as a particle at the detection point P with localized wavefunction ψ_B(P’) = δ(P’ - P) — equivalently, a McGucken sphere whose forward x₄-expansion is, in the emitter’s frame, the conjugate kernel ψ^*(P) (by (ii)). The collision rate from (iv) becomes Rate(detection at P) = ψ^*(P) ψ(P) · |Γ|² = |Γ|² |ψ(P)|², with |Γ|² a coupling-dependent prefactor absorbed into the wavefunction’s normalization. The standard Born rule of Theorem 7.2 is recovered as the localized-absorber limit of the head-on x₄-collision picture. ∎

**Lemma 7.7.5 (Two-Sphere coincidence rate: product structure and sesquilinear conjugation both derived).** *Let A and B be two independent McGucken Spheres arriving at the spatial point P at parameter time t, with amplitudes ψ_A(P), ψ_B(P) ∈ ℂ. Then the local coincidence rate at P is, up to a positive normalization constant, the sesquilinear product*

*R(ψ_A(P), ψ_B(P)) = ψ_A(P) · ψ_B^*(P),*

*with BOTH ingredients — the product structure and the conjugation — derived within the McGucken framework from the content of dx₄/dt = ic combined with the four requirements R1–R4 of Theorem 7.2.*

*(a) **Product structure (DERIVED).** The product form ψ_A(P) · ψ_B(P) — rather than sum, max, min, arithmetic/geometric/harmonic mean, or any other symmetric function of the two amplitudes — is forced (Step 1 below) by the action-additivity of independent paths combined with the exponential phase exp(iS[γ]/ħ) of each McGucken-Sphere wavefront.*

*(b) **Conjugation ψ_B ⇝ ψ_B^* (DERIVED).** The conjugation of one factor — converting the forward × forward product ψ_A · ψ_B to the sesquilinear pairing ψ_A · ψ_B^* — is forced (Step 2 below) by the complexification of the symmetric rank-2 metric η_(μν) (Lemma 2.5, symmetric since η_(μν) = η_(νμ)) combined with the requirement R1 (real Born density on diagonal). The bilinear complex extension of η_(μν) has imaginary part on the diagonal generally non-zero; the sesquilinear extension uniquely gives a real diagonal for symmetric forms. R1 therefore excludes the bilinear extension and forces the sesquilinear extension — and the sesquilinear extension is precisely the one with conjugation. The conjugation is the CONJUGATION of the sesquilinear inner product, not a Lorentz boost, and not a Stueckelberg–Feynman time-reversal postulate.*

*(c) **Sesquilinearity follows from (a) + (b); uniqueness within sesquilinear forms is trivial linear algebra (Step 3).** R4 (bilinearity in (ψ, ψ^*)) is the sesquilinear structure of the coincidence pairing, derived from (a) + (b) above.*

*Proof.*

Each McGucken Sphere wavefront ψ propagates as a path-integral kernel with phase exp(iS[γ]/ħ) along each path γ (Theorem 3.1, Definition 2.6). For two independent McGucken Spheres A and B arriving at P along independent paths γ_A and γ_B, the joint wavefront at P has phase equal to the SUM of the individual phases:


Sⱼₒᵢₙₜ[γ_A, γ_B] = S_A[γ_A] + S_B[γ_B].


By the exponential identity exp(a + b) = exp(a) · exp(b), the joint wavefront amplitude at P is therefore the PRODUCT of the individual amplitudes:


ψⱼₒᵢₙₜ(P) = exp(iSⱼₒᵢₙₜ/ħ) = exp(iS_A/ħ) · exp(iS_B/ħ) = ψ_A(P) · ψ_B(P).


The product structure is therefore derived from action-additivity and the exponential phase of the McGucken-Sphere wavefront, with no separately postulated probability axiom. This rules out, every alternative symmetric function as a candidate functional form for the joint amplitude:

*(i) Sum* ψ_A + ψ_B: Would require phase-multiplicative action (Sⱼₒᵢₙₜ = S_A · S_B), contradicting the additive action structure of independent paths.

*(ii) Maximum / minimum* max(|ψ_A|, |ψ_B|), min(|ψ_A|, |ψ_B|): Not derivable from the exponential phase structure; fails the smooth-wavefunction differentiability of Definition 2.6.

*(iii) Arithmetic mean* (|ψ_A| + |ψ_B|)/2: Same failure as sum — would require additive action structure with a 1/2 factor that has no source in the action-additivity of independent paths.

*(iv) Geometric mean* √(|ψ_A| · |ψ_B|): Not derivable from action-additivity; would require half-action structure Sⱼₒᵢₙₜ = (S_A + S_B)/2, which contradicts the additive structure.

*(v) Harmonic mean* 2|ψ_A| · |ψ_B| / (|ψ_A| + |ψ_B|): Not derivable from any action-related structure; involves a non-polynomial combination.

The product is therefore the unique functional form forced by the action-additivity of independent paths combined with the exponential phase of each Sphere.

The wave-mechanical product ψ_A(P) · ψ_B(P) of Step 1 is the joint amplitude at the coincidence event P. To extract a real coincidence RATE from this joint amplitude, we must combine it with an appropriate inner product structure on complex-valued amplitudes. The conjugation ψ_B ⇝ ψ_B^* that converts the forward × forward product to the sesquilinear pairing ψ_A · ψ_B^* is FORCED by the following chain — no time-reversal postulate, no Stueckelberg–Feynman identification, no frame-relational antiparallelism required.

By Lemma 7.1, the metric pairing on the McGucken-Sphere wavefront is rank-2 and inherited from the Minkowski metric η_(μν), which is a SYMMETRIC real bilinear form on real four-vectors (η_(μν) = η_(νμ) by symmetry of the metric tensor). The wavefunction ψ is complex-valued by Theorem 3.1 (the imaginary unit i is the algebraic marker of x₄-perpendicularity from x₄ = ict). The inner product on complex-valued wavefunctions must therefore be a COMPLEX EXTENSION of the rank-2 real metric.

A symmetric real bilinear form B: V × V → ℝ on a real vector space V has exactly two natural extensions to a complex form on the complexification V_ℂ = V ⊗_ℝ ℂ:

**(A) Complex bilinear extension** Bᵇⁱˡ: V_ℂ × V_ℂ → ℂ — linear in both arguments. For complex z = u + iv, w = u' + iv' with u, v, u', v' ∈ V:


Bᵇⁱˡ(z, w) = B(u, u') - B(v, v') + i (B(u, v') + B(v, u')).


Diagonal: Bᵇⁱˡ(z, z) = B(u, u) - B(v, v) + 2i B(u, v).

**(B) Sesquilinear (Hermitian) extension** B^(sesq): V_ℂ × V_ℂ → ℂ — antilinear in first argument, linear in second. Defined via B^(sesq)(z, w) := B(z̄, w), where z̄ = u - iv is the complex conjugate of z:


B^(sesq)(z, w) = B(u, u') + B(v, v') + i (B(u, v') - B(v, u')).


Diagonal: B^(sesq)(z, z) = B(u, u) + B(v, v) + i (B(u, v) - B(v, u)).

For SYMMETRIC B (where B(u, v) = B(v, u) as for η_(μν)), the diagonals reduce to:


Bᵇⁱˡ(z, z) = B(u, u) - B(v, v) + 2i B(u, v) (imaginary part 2 B(u,v), generally NON-zero),



B^(sesq)(z, z) = B(u, u) + B(v, v) ∈ ℝ (REAL, by symmetry of B).


Requirement R1 (reality of the Born density on diagonal — that the density value P(x) = R(ψ(x), ψ(x)) at a single wavefunction be real-valued at every spatial point x) is the physical requirement that the Born density be a probability density. R1 **excludes** the bilinear extension: Bᵇⁱˡ(ψ, ψ) has imaginary part 2 B(Re ψ, Im ψ) that fails to vanish for generic complex ψ (specifically, whenever Re ψ and Im ψ are not η-orthogonal at the point x, which is the generic case). R1 **forces** the sesquilinear extension: B^(sesq)(ψ, ψ) = B(Re ψ, Re ψ) + B(Im ψ, Im ψ) is real by symmetry of η_(μν), automatically and for every ψ.

**The conjugation in the sesquilinear extension** — making the inner product structure ψ^* ψ rather than ψ² — is therefore FORCED by three inputs, each independently derived within the McGucken dx₄/dt = ic framework:

(i) The symmetry of the rank-2 metric η_(μν), a feature of the Minkowski metric, derived from (ic)² = -c² via Lemma 2.5 (η_(μν) is symmetric because the Minkowski line element is bilinear in dx^μ symmetrically).

(ii) The complex character of the wavefunction ψ, derived from Theorem 3.1 (i is the algebraic marker of x₄-perpendicularity from x₄ = ict, with the wavefunction being a complex-valued path-integral kernel by Definition 2.6).

(iii) Requirement R1 (real Born density on diagonal), the physics that the density be a probability density.

These three inputs jointly force the sesquilinear extension, which uniquely supplies the conjugation ψ_B ⇝ ψ_B^*. The conjugation is therefore a THEOREM of the dx₄/dt = ic framework, derived from (i)–(iii) above, not a frame-change postulate and not a time-reversal identification.

The conjugation i ↦ -i entering the Born density is NOT identified with a Lorentz boost or any frame change — note that the action S is a Lorentz scalar, so exp(iS/ħ) is frame-invariant, and a boost cannot conjugate ψ. The conjugation is also NOT identified with time reversal as a separately postulated physical operation (the Stueckelberg–Feynman absorber-as-time-reversed-emitter convention). Rather, the conjugation is the CONJUGATION of the sesquilinear complexification of the symmetric rank-2 metric, forced by R1 (real diagonal) as derived above. The Stueckelberg–Feynman reading of Theorem 7.7(i)-(ii) becomes one PHYSICAL INTERPRETATION of the (already derived) sesquilinear conjugation, not its source: it provides physics to the head-on collision picture, but the conjugation itself is supplied upstream by the complexification argument.

The joint amplitude ψ_A(P) · ψ_B(P) of Step 1 combines with the sesquilinear inner product structure derived in this Step 2 to give the coincidence rate as the sesquilinear pairing:


R(ψ_A, ψ_B) = ψ_A(P) · ψ_B^*(P)


with the conjugation on ψ_B being the conjugation of the sesquilinear complexification (Step 2), derived from R1 + symmetric rank-2 metric + complex-valued wavefunction. The product structure (Step 1) and the conjugation (Step 2) are BOTH derived from the content of the McGucken dx₄/dt = ic framework, with no postulational input from Theorem 7.7’s head-on collision picture or any time-reversal identification.

Steps 1 and 2 together establish that the coincidence rate has the sesquilinear structure R(ψ_A, ψ_B) = ψ_A · ψ_B^* (linear in ψ_A from Step 1’s product structure, antilinear in ψ_B from Step 2’s complexification-forced conjugation). Within the family of sesquilinear forms on ℂ × ℂ, the form is unique up to a multiplicative constant by direct linear-algebraic computation: R(ψ_A, ψ_B) = ψ_A · R(1, ψ_B) = ψ_A · ψ_B^* · R(1, 1) = c · ψ_A · ψ_B^* with c := R(1, 1). This step is the trivial direction (unpacking the definition of *sesquilinear*) and contributes no derivational content beyond Steps 1 and 2; its role is to formalize the unique sesquilinear functional form once sesquilinearity itself is established by Steps 1 + 2.

The constant c is fixed by: reality on diagonal (c ∈ ℝ from R(ψ, ψ) = c|ψ|² being real); non-negativity (c > 0 from R(ψ, ψ) ≥ 0); and normalization (c = 1 absorbed into wavefunction normalization). For the single-particle Born density:


R(ψ, ψ^*) = ψ · ψ^* = |ψ|².


This is the Born density of Theorem 7.2, recovered through the fully derived chain Step 1 (product structure, derived from action-additivity) → Step 2 (conjugation, derived from complexification + R1 + symmetric rank-2 metric) → Step 3 (uniqueness within sesquilinear forms, trivial linear algebra) → Step 4 (constants fixed by R1 + R2 + normalization). ∎

**Corollary 7.7.6 (R4 derived via the complexification route).** *The bilinearity requirement R4 of Theorem 7.2’s uniqueness derivation — that the Born density P be bilinear in (ψ, ψ^*) — is fully derived from the content of the McGucken dx₄/dt = ic framework. The derivation chain is:*

*(R4-1) The Minkowski metric η_(μν) is symmetric (η_(μν) = η_(νμ), manifest in the Minkowski line element ds² = η_(μν) dx^μ dx^ν being bilinear-symmetric). The rank-2 character descends from the squared form (ic)² = -c² of dx₄/dt = ic (Lemma 2.5).*

*(R4-2) The wavefunction is complex-valued by Theorem 3.1: the imaginary unit i is the algebraic marker of x₄-perpendicularity from x₄ = ict via Frobenius (Theorem 4.6.1). The path-integral kernel (Definition 2.6) gives ψ as a complex-valued function over Minkowski Space 𝕄_(1,3).*

*(R4-3) The inner product on the McGucken-derived Hilbert space, lifting the rank-2 metric to complex amplitudes, is a complex extension of η_(μν). By the complexification of symmetric real bilinear forms (Lemma 7.7.5 Step 2): exactly two natural extensions exist (complex bilinear and sesquilinear), and the bilinear extension fails the reality of the diagonal whereas the sesquilinear extension uniquely gives a real diagonal for symmetric forms.*

*(R4-4) Requirement R1 (real Born density on diagonal) excludes the bilinear extension and forces the sesquilinear extension. The conjugation ψ ⇝ ψ^* in the inner product structure ψ^* ψ is the conjugation of the sesquilinear complexification — not a Stueckelberg–Feynman time-reversal identification.*

*(R4-5) The action-additivity of independent McGucken-Sphere paths gives the product structure ψ_A · ψ_B for the joint amplitude (Lemma 7.7.5 Step 1). Combined with (R4-4), this yields the sesquilinear pairing R = ψ_A · ψ_B^* as the coincidence rate, and on the single-particle diagonal, R(ψ, ψ^*) = |ψ|² — the Born density.*

*(R4-6) Bilinearity in (ψ, ψ^*) — requirement R4 — is the form of this sesquilinear inner product, derived from (R4-1) through (R4-5) as a forced consequence of the McGucken dx₄/dt = ic framework’s content combined with R1. R4 is fully derived, with no postulational input beyond dx₄/dt = ic, its forced consequences (rank-2 metric symmetry, complex wavefunction), and R1 (itself a Sphere-geometric requirement, see §7.1).*

**Remark 7.7.7 (Why the complexification route closes the gap).** *The complexification-route derivation of R4 (Lemma 7.7.5 Step 2 and Corollary 7.7.6) closes the gap between the earlier “elementary collision kinematics” assertion and a full derivation. The key insight is that the conjugation in ψ^* ψ enters the dx₄/dt = ic framework not as a physical time-reversal postulate (the Stueckelberg–Feynman absorber-as-time-reversed-emitter identification) but as the conjugation of the sesquilinear complexification of the symmetric rank-2 metric, forced by R1 (real Born density on diagonal). This is a textbook linear-algebraic fact applied to the McGucken dx₄/dt = ic framework’s content:*

*(Mathematical fact). For a symmetric real bilinear form B on a real vector space V, the unique complex extension to V_C that has a real diagonal on all of V_C is the sesquilinear extension B^(sesq)(z, w) = B(z̄, w). The bilinear extension Bᵇⁱˡ(z, w) = B(z, w) extended by complex linearity has imaginary part 2 B(Re z, Im z) on the diagonal that fails to vanish for generic z ∈ V_C (specifically, when Re z and Im z are not B-orthogonal).*

*(Application to the McGucken dx₄/dt = ic framework). The Minkowski metric η_(μν) is symmetric (a feature derivable from Lemma 2.5). The wavefunction is complex-valued (Theorem 3.1, Definition 2.6). The Born density on the diagonal must be real (R1). The unique extension of η_(μν) to complex amplitudes consistent with R1 is the sesquilinear extension, which is precisely the one with conjugation. R4 follows.*

*Relationship to Theorem 7.7’s head-on collision picture: the head-on collision is now one PHYSICAL INTERPRETATION of the (already derived) sesquilinear inner product structure — providing a two-particle-collision reading in which the conjugate factor is identified with the absorber’s amplitude as viewed in the emitter’s frame. This identification has additional physics (the Stueckelberg–Feynman reading of absorption as time-reversed emission), but it is not REQUIRED for the derivation of R4: the conjugation is supplied by the inner product structure, not by the head-on collision picture. The dx₄/dt = ic framework retains Theorem 7.7’s picture as a complementary geometric reading (alongside Theorem 7.4’s cascade-level overlap reading and Theorem 7.11’s PT-symmetry reading) — the R4 closure goes through the inner product, with Theorem 7.7’s head-on collision picture now optional secondary physics rather than the source of the conjugation.*

**Remark 7.8 (the conjugate sphere identified physically).** Theorem 7.4 established that ψ^*ψ at the detection event is the geometric overlap of the forward x₄-expansion and the conjugate x₄-expansion at that event, but left the physical referent of the conjugate sphere open — it could have been read as a purely formal partner of ψ, an “orientation-reversed image” with no independent physical existence. Theorem 7.7 identifies the conjugate sphere physically: it is the absorber’s own forward x₄-expansion, viewed from the emitter’s frame, where it appears antiparallel in x₄. The “two expansions meeting at B” of Theorem 7.4 is, in mechanism, two McGucken spheres of two physical particles intersecting head-on at B, with the x₄-momenergy cancellation forcing the rotation out of x₄ (Theorem 12.2) and the 3-spatial localization of both at B (Corollary 11.4).

**Remark 7.9 (universality across particle types).** The mechanism applies uniformly to all canonical detection events. For photon detection on a photographic grain (§12.6.1), particle B is the absorbing bound electron in the AgBr crystal whose own McGucken sphere is propagating from its bound-state center at the crystal lattice site; the head-on collision at the lattice site is the photon-electron interaction that deposits the latent image. For radioactive alpha detection (§12.6.2), particle B is the absorbing atomic electron in the scintillator or ionization detector, with the same head-on x₄-collision picture applying — the alpha’s massive McGucken sphere meets the electron’s bound-state McGucken sphere at the ionization point, the x₄-momenergy cancels (modulo binding-energy corrections), and both are localized in the spatial slice as a track segment of the post-collision pair. Both photon and massive-particle cases are instances of the universal head-on x₄-collision mechanism.

**Remark 7.10 (the bilinearity of the rank-2 metric grounded in the head-on collision).** Lemma 7.1 derived the quadratic form of the Born density from conservation under x₄’s expansion, the rank-2 character of the Minkowski metric entering through the second order of the Klein–Gordon equation. Theorem 7.7 supplies the physics of that bilinearity: the two-particle head-on collision requires the simultaneous arrival of two independent McGucken spheres at the collision point, with the local rate proportional to the product of their two amplitudes. The rank-2 of the metric (Lemma 2.5) and the bilinearity of the Born rule (Lemma 7.1) are not abstract formal facts about pairings; they are the algebraic record of the two-particle character of the head-on x₄-collision mechanism. The exponent 2 in P = |ψ|² counts the number of physical participants in the collision: emitter and absorber, two McGucken spheres, two x₄-momenta cancelling head-on.

### 7.10 Complex conjugation as McGucken-Sphere PT-symmetry through the source event: the free-propagation reading

Theorem 7.4 supplied the cascade-level geometric reading of |ψ|² as the overlap of forward and conjugate x₄-expansions at the detection event. Theorem 7.7 supplied the detection-event mechanism: a two-particle head-on collision of two McGucken Spheres, with the conjugate factor ψ^* identified physically as the absorber’s outgoing sphere viewed in the emitter’s frame. The present subsection supplies a third reading of |ψ|² — the *free-propagation* reading, in which the conjugate factor ψ^* is supplied by the McGucken Sphere’s own intrinsic symmetry through its source event, rather than by an external absorber. This reading applies to a free particle propagating in space without yet interacting with any detector — the regime in which ψ has well-defined values and |ψ|² has well-defined probability content, but no two-particle head-on collision is yet occurring. The three readings are complementary and apply to overlapping physical situations: Theorem 7.4 to the cascade-level abstract content; Theorem 7.7 to the detection event; Theorem 7.11 (below) to the free particle prior to detection.

The free-propagation reading rests on a rigorous geometric symmetry of the McGucken-Sphere structure. The McGucken Principle dx₄/dt = ic states (§2.1) that the fourth dimension advances as a spherically symmetric wavefront expanding at velocity c from every spacetime event E. The natural symmetry of a spherically symmetric wavefront emitted from E is *reflection through E*. In four-dimensional spacetime, reflection through an event E is the combined parity-and-time-reversal operation PT_E sending (x − x_E, t − t_E) ↦ −(x − x_E, t − t_E). This 4D PT-reflection through E is the *exact* symmetry of the McGucken-Sphere expansion. The wavefunction’s complex-conjugation algebra is the shadow of this geometric reflection symmetry: under PT_E, the McGucken-derived wavefunction transforms as ψ(PT_E · event) = ψ^*(event), with no residual phase factors and no special-case complications. **Complex conjugation in quantum mechanics is the McGucken-Sphere PT-symmetry through the source event.** This places the complex structure of QM (the perpendicular-axis i of Theorem 3.1) and the Born rule’s bilinearity (the rank-2 sesquilinear pairing of Lemma 7.1) on a single upstream geometric foundation.

A first version of the present subsection framed the symmetry as antipodal-on-the-2-sphere at fixed parameter time t. That framing is geometrically suggestive but mathematically incomplete: for plane-wave components ψ_k(P, t) = exp(ik · (P − x_E) − iω(k)(t − t_E)), the antipodal-at-fixed-t map P ↔ 2x_E − P reverses the spatial phase k · (P − x_E) ↔ −k · (P − x_E) but leaves the temporal phase ω(k)(t − t_E) unchanged. The antipodal-at-fixed-t map therefore yields complex conjugation only up to a residual temporal-phase factor exp(−2iω_k(t − t_E)) that drops out only for energy eigenstates (where ω is single-valued and the temporal phase is global). For general non-stationary wavefunctions the residual factor does not vanish. The exact derivation is the 4D PT_E symmetry, with the spatial-slice antipodal map appearing as the restriction at fixed t — exact for stationary states, approximate (up to residual temporal phase) for general states.

**Theorem 7.11 (Complex conjugation as McGucken-Sphere PT-symmetry through the source event).** *Let particle A at event E ∈ 𝕄₁,₃ propagate its McGucken Sphere outward at dx_4/dt = +ic by the canonical isotropic expansion of clause 3, §2.4. Then:*

*(i) (4D PT-symmetry through E.) The forward light cone of E has a unique non-trivial discrete symmetry preserving the spherical isotropy of the McGucken-Sphere expansion: the 4D PT-reflection through E,*

*PT_E : (x^μ − x^μ_E) ↦ −(x^μ − x^μ_E), equivalently x ↦ 2x_E − x and t ↦ 2t_E − t.*

*The continuous symmetries of the forward light cone of E preserving isotropy are the spatial rotations SO(3) about x_E (which preserve the spherical symmetry of the wavefront); the additional discrete symmetry PT_E sends the forward light cone to the backward light cone, with the McGucken-Sphere wavefront (forward in t, outward in space from E) mapped to its time-reversed structure (backward in t, inward toward E) — geometrically the same wavefront with reversed orientation.*

*(ii) (Wavefunction transforms as ψ(PT_E · event) = ψ^*(event), exactly.) The McGucken-derived wavefunction ψ on 𝕄₁,₃, constructed by Definition 2.6 as the path-integral kernel from source events to target events, satisfies the symmetry identity*

*ψ(PT_E · event) = ψ^*(event), i.e. ψ(2x_E − x, 2t_E − t) = ψ^*(x, t),*

*exactly for any McGucken-derived wavefunction. The wavefunction’s complex-conjugation algebra is the shadow of the McGucken-Sphere PT-symmetry through the source event.*

*(iii) (Born density as multiplication of wavefunction at event and PT_E-reflected event.) The Born density |ψ(P, t)|² at any spatial-slice event (P, t) is the geometric multiplication of the wavefunction’s value at (P, t) with its PT_E-reflected value at the reflected event:*

*|ψ(P, t)|² = ψ(P, t) · ψ^*(P, t) = ψ(P, t) · ψ(2x_E − P, 2t_E − t).*

*For normalized wavefunctions this reduces to the standard modulus-squared. The Born rule’s squaring operation is the cascade-level expression of the McGucken-Sphere PT-symmetry through the source event.*

*(iv) (Free-propagation reading.) For a free particle without external absorber, the conjugate factor ψ^* in the Born density is supplied by the McGucken Sphere’s intrinsic PT-symmetry through the source event, not by an external absorber. The Born density is well-defined at every event of the spatial slice without requiring a collision partner. The conjugate factor is therefore intrinsic to the single particle’s own forward light cone, supplied geometrically by the wavefront’s natural reflection symmetry through its emission event.*

*(v) (Spatial-slice corollary at fixed t.) The spatial-slice restriction of the 4D PT_E symmetry at fixed parameter time t is the spatial antipodal map P ↔ 2x_E − P through x_E. For energy-eigenstate wavefunctions ψ_n(x) · exp(−iE_n t/ℏ), the global temporal phase drops out of the Born density, and the spatial-slice corollary is exact: the antipodal map yields complex conjugation up to a global phase that drops out of |ψ|². For general (non-stationary) wavefunctions, the antipodal-at-fixed-t map yields complex conjugation only up to a residual temporal-phase factor; the exact symmetry statement is the 4D PT_E through E, with the spatial-slice antipodal map as its restriction at fixed t.*

*(vi) (Upstream connection to Principle 2.1.) The PT-symmetry through E is the geometric shadow of the Principle 2.1 (§2.1): the spherically symmetric wavefront expanding at velocity c from event E has reflection through E as its natural symmetry, and that reflection is exactly PT_E in 4D. The complex structure of QM (Theorem 3.1: i as the algebraic marker for x_4-perpendicularity) and the Born rule’s bilinearity (Lemma 7.1: the quadratic density conserved under the propagation that the rank-2 Minkowski metric induces) are therefore both downstream consequences of this single geometric symmetry. The complex structure and the Born-rule bilinearity, previously two derivationally distinct facts in the cascade, are now placed on the same upstream foundation: the McGucken-Sphere PT-symmetry through the source event.*

**Proof.**

*(i)* The McGucken Sphere 𝓜_E(t) at parameter time t centered at E is the locus of points reached by the spherically symmetric x_4-expansion from E at velocity c after parameter time t (clause 3 of §2.4). The 4D structure (forward light cone of E plus the spheres at each future parameter time) is preserved under any symmetry preserving the isotropy of the expansion. The continuous symmetries through E preserving isotropy are the spatial rotations SO(3) about x_E. The discrete non-trivial symmetry through E is PT_E: the combined parity-and-time-reversal reflection sends (x − x_E, t − t_E) ↦ −(x − x_E, t − t_E), mapping the forward light cone of E to the backward light cone with geometric structure preserved up to orientation. The McGucken-Sphere wavefront (a 2-sphere in space at parameter time t) maps under PT_E to a 2-sphere of the same radius in space at parameter time −t (i.e., at time 2t_E − t, which lies in the backward light cone of E). The forward-and-outward expansion maps to backward-and-inward propagation — geometrically identical wavefront with reversed orientation in both space and time. Therefore PT_E is a discrete symmetry of the 4D McGucken-Sphere structure through E.

*(ii)* By Definition 2.6, the McGucken-derived wavefunction at any event (P, t) is the path-integral kernel

ψ(P, t) = ∑_{paths γ: E → (P, t)} exp(iS[γ]/ℏ),

with the action S[γ] supplied by the path integral over x_4-phase along each path γ from E to (P, t). Under PT_E, each path γ from E to (P, t) maps to a path γ’ from E to (2x_E − P, 2t_E − t), with action S[γ’] = −S[γ] because the action S = ∫ L dt is the integral of the Lagrangian L = (1/2)m v² − V along the path, and under PT_E both the velocity v = dx/dt and the time-element dt reverse sign — leaving L unchanged but introducing a sign flip in the integration measure dt → −dt, hence S[γ’] = −S[γ]. (Equivalently, the action is the temporal integral of energy plus the spatial integral of momentum; under PT both reverse sign, giving an overall sign flip on S.) Therefore

ψ(PT_E · (P, t)) = ψ(2x_E − P, 2t_E − t) = ∑*{paths γ’} exp(iS[γ’]/ℏ) = ∑*{paths γ} exp(−iS[γ]/ℏ) = ψ^*(P, t).

The identity ψ(PT_E · event) = ψ^*(event) is therefore exact for any McGucken-derived wavefunction. For explicit verification with a plane-wave component ψ_k(x, t) = exp(ik · (x − x_E) − iω(k)(t − t_E)):

ψ_k(PT_E · (P, t)) = exp(ik · (2x_E − P − x_E) − iω(k)(2t_E − t − t_E))
= exp(ik · (x_E − P) − iω(k)(t_E − t))
= exp(−ik · (P − x_E) + iω(k)(t − t_E))
= exp(−i[k · (P − x_E) − ω(k)(t − t_E)])
= ψ_k^*(P, t). ✓

By linearity, the symmetry identity extends to any Fourier superposition of plane-wave components, i.e., to any McGucken-derived wavefunction on 𝕄₁,₃.

*(iii)* Direct substitution: |ψ(P, t)|² = ψ^*(P, t) · ψ(P, t) = ψ(PT_E · (P, t)) · ψ(P, t) by clause (ii). The geometric reading identifies the Born density’s squaring as the multiplication of the wavefunction’s value at an event with its value at the PT_E-reflected event.

*(iv)* For a free particle, the source event E is the emission event (or the initial-condition event of the wavefunction). The wavefunction’s complex-conjugation symmetry ψ(PT_E · event) = ψ^*(event) is intrinsic to the McGucken-Sphere PT-symmetry through E; no external absorber is required to supply the conjugate factor. The Born density at any event (P, t) is therefore well-defined as ψ(P, t) · ψ(2x_E − P, 2t_E − t), the multiplication of the wavefunction’s value at (P, t) with its value at the PT_E-reflected event. When a detector subsequently arrives at the spatial point P, the head-on collision of Theorem 7.7 supplies a second physical source of the conjugate factor (the absorber’s outgoing McGucken Sphere viewed in the emitter’s frame); the dx₄/dt = ic framework’s three readings (Theorem 7.4 cascade-level, Theorem 7.7 detection-event, Theorem 7.11 free-propagation) are then jointly consistent at the detection event, with the free-propagation reading describing the pre-detection state and the head-on-collision reading describing the detection event itself.

*(v)* Restrict the 4D PT_E symmetry to fixed parameter time t. The spatial-slice map is P ↦ 2x_E − P (spatial antipodal through x_E). For energy-eigenstate wavefunctions ψ(x, t) = ψ_n(x) · exp(−iE_n t/ℏ), the temporal factor exp(−iE_n t/ℏ) is global and drops out of the Born density |ψ(P, t)|² = |ψ_n(P)|². The spatial antipodal map applied to ψ_n yields ψ_n(2x_E − P), which equals ψ_n^*(P) for ψ_n with definite spatial parity about x_E (a parity-symmetric Hamiltonian centered at x_E supports parity eigenstates with this property). For general non-stationary wavefunctions ψ(x, t) = ∑_k a_k exp(ik · (x − x_E) − iω(k)(t − t_E)), the spatial antipodal at fixed t gives ψ(2x_E − P, t) = ∑_k a_k exp(−ik · (P − x_E) − iω(k)(t − t_E)), while ψ^*(P, t) = ∑_k a_k^* exp(−ik · (P − x_E) + iω(k)(t − t_E)). The two differ by both the conjugation a_k ↦ a_k^* and the temporal phase ω(t − t_E) ↔ −ω(t − t_E). The spatial-slice antipodal map at fixed t yields complex conjugation only when both: (a) the wavefunction has all-real Fourier coefficients a_k (i.e., spatial-parity-symmetric), AND (b) the wavefunction is monochromatic (single ω) or stationary. For general wavefunctions the exact symmetry is the 4D PT_E through E, with the spatial-slice antipodal map as its fixed-t restriction.

*(vi)* By Principle 2.1 (§2.1), the McGucken Principle dx_4/dt = ic states that x_4 advances as a spherically symmetric wavefront from every spacetime event E, carrying wavelength, frequency, phase, and therefore action. The natural symmetry of such a wavefront is reflection through E. In 4D, reflection through E is the PT_E operation. The wavefunction’s complex-conjugation algebra (Theorem 3.1: i as the algebraic marker for x_4-perpendicularity) and the Born rule’s bilinearity (Lemma 7.1: the quadratic density conserved under the propagation that the rank-2 Minkowski metric induces) are therefore both downstream consequences of the McGucken-Sphere PT-symmetry through the source event. The chain extends:

dx_4/dt = ic → x_4 advances as a spherically symmetric wavefront from E → the wavefront has PT_E-reflection as its natural symmetry → the wavefunction satisfies ψ(PT_E · event) = ψ^*(event) → the Born density at any event is the modulus-squared of a wavefunction whose phase structure is constrained by this symmetry.

The complex structure of QM and the bilinearity of the Born rule are placed on the same upstream foundation. The dynamics were in the premise (§2.1); so was the conjugate structure that the Born rule reads. ∎

**Remark 7.11 (the three Born-rule readings as complementary descriptions).** The dx₄/dt = ic framework now supplies three complementary geometric readings of the Born density’s squaring operation, each illuminating a different physical aspect:

 -------------------------------------------------------------------------------------------------------------------------------------
 Reading Source of ψ^* Physical regime
 --------------------------------- ------------------------------------------------------ --------------------------------------------
 Cascade-level (Theorem 7.4) Conjugate x_4-expansion overlapping forward at B Abstract cascade-level geometric meaning

 Free-propagation (Theorem 7.11) McGucken-Sphere PT-symmetry through source event E Free particle prior to detection

 Detection-event (Theorem 7.7) Absorber’s McGucken Sphere viewed in emitter’s frame Two-particle head-on collision at detector
 -------------------------------------------------------------------------------------------------------------------------------------

All three readings reduce algebraically to |ψ|² = ψ^*ψ, but they apply at different physical situations and illuminate different aspects of the Born density’s geometry. The free-propagation reading (Theorem 7.11) is the most natural for the pre-detection state of a free quantum: the wavefunction ψ propagates on its McGucken Sphere with the Born density already well-defined at every event by the sphere’s intrinsic PT-symmetry through the source event. The detection-event reading (Theorem 7.7) is the most natural for the detection event itself: when the absorber arrives, the head-on collision supplies the conjugate factor externally and produces the localization. The cascade-level reading (Theorem 7.4) is the most natural for the abstract identification of the Born density’s geometry prior to specifying a physical mechanism. The three readings are not in tension; they are complementary descriptions of the same Born density at different physical regimes, with the PT-symmetry reading (Theorem 7.11) supplying the content — complex conjugation in quantum mechanics is the McGucken-Sphere PT-symmetry through the source event.

**Remark 7.12 (spinor refinement: the σ_y threading of PT for spin-1/2).** For spin-1/2 wavefunctions, the antiunitary time-reversal operator is the Wigner T = iσ_y · K (where K denotes complex conjugation and σ_y is the second Pauli matrix in the standard basis; the antiunitary character of T was established by Wigner 1932 in *Gruppentheorie und ihre Anwendung auf die Quantenmechanik der Atomspektren* and is reviewed in standard texts on time-reversal symmetry in QM). The PT-symmetry-through-E of Theorem 7.11 for spinor wavefunctions therefore carries the σ_y factor as additional algebraic structure on the spin index:

ψ(PT_E · event) = iσ_y · ψ^*(event) (spinor case).

The Born density still works out to |ψ|² = ψ^†ψ as the standard modulus-squared, because (iσ_y · ψ^*)^†(iσ_y · ψ^*) = ψ^T (−iσ_y)(iσ_y) ψ^* = ψ^T ψ^* = (ψ^†ψ)^* = ψ^†ψ for the spinor-internal trace (using σ_y^2 = 𝟙 and the cyclicity of the bilinear form). The spinor-internal structure of the conjugation requires the σ_y threading, but the Born density’s standard modulus-squared form emerges unchanged. This is tied to Theorem 12.11 instance (4): the spin-1/2 4π closure requirement of the SU(2) double cover of SO(3) is exactly the σ_y-supplied content of the McGucken-Sphere PT-symmetry restricted to the spin-1/2 internal space. The dx₄/dt = ic framework therefore unifies the Born rule’s PT-symmetry (Theorem 7.11) and the spin-1/2 4π closure (Theorem 12.11 instance 4) under the same geometry: the PT-symmetry of the wavefront through the source event, with the spinor case requiring the σ_y factor to capture the SU(2) double-cover structure.

**Remark 7.13 (interactions and local PT-symmetry restoration in the path-integral sum).** For a particle in an external potential V(x), the wavefunction’s PT-symmetry through a single emission event E is broken globally if V is not invariant under PT_E (e.g., a Coulomb potential anchored at a charge center distinct from x_E is not PT_E-symmetric). The single-sphere PT-symmetry reading of Theorem 7.11 therefore does not apply globally for interacting systems. However, at the infinitesimal-propagation level, the path-integral kernel from each intermediate event E_i to the next event E_{i+1} is locally PT-symmetric through E_i — each McGucken-Sphere kernel in the path-integral sum has the PT-symmetry of Theorem 7.11 through its own emission event. The Born rule’s emergence from PT-symmetry therefore applies *cascade-locally* at each emission event in the path-integral expansion, with the full wavefunction’s Born density at the detection event being the cumulative product of these locally-PT-symmetric infinitesimal kernels. For interacting systems, the dx₄/dt = ic framework’s Born-rule reading is local-PT-symmetric rather than global-PT-symmetric, and the cascade-locality preserves the content while accommodating the breaking of global symmetry by the interaction potential. The bound-state limit (stationary Hamiltonians, finite-spectrum eigenstates) is the special case where the global temporal phase drops out of the Born density and the spatial-slice antipodal map at fixed t becomes the operative symmetry; for general scattering states the local-PT-symmetric path-integral expansion is the correct cascade-level reading.

**Remark 7.14 (bound states reduce to spatial parity for parity-symmetric Hamiltonians).** For stationary bound states ψ_n(x) · exp(−iE_n t/ℏ) in a parity-symmetric Hamiltonian centered at x_E (the typical case in atomic and molecular physics with a central potential), the temporal phase is global and drops out of Born densities, and the 4D PT-symmetry through E reduces to spatial parity on the spatial wavefunction ψ_n. For ψ_n with definite parity (P̂ · ψ_n = ±ψ_n, where P̂ is the spatial parity operator about x_E), the spatial parity is exactly the Born rule’s conjugation symmetry. The standard atomic-physics computation of |ψ_n(x)|² as the Born density of the bound electron in a Coulomb potential is therefore the McGucken-Sphere PT-symmetry through E reduced to its parity-symmetric stationary-state special case. For systems with parity-violating interactions (the weak force, the chirality of neutrino interactions), the PT-symmetry holds with the full Wigner T (including σ_y for spinor components per Remark 7.12), and the spinor-internal σ_y threading supplies the conjugation algebra. The dx₄/dt = ic framework’s Born-rule reading is therefore robust across the canonical bound-state, scattering, and parity-violating regimes — with the PT-symmetry-through-E acting as the general statement and the spatial-parity, σ_y-threading, and local-PT specializations covering specific physical regimes.

**Remark 7.15 (forward-looking: S-matrix unitarity as PT-symmetry through the interaction event).** For asymptotic scattering states, the PT-symmetry through the scattering event E supplies a source of S-matrix unitarity: the incoming-wave amplitude at past asymptotic infinity is PT_E-reflected at E to the outgoing-wave amplitude at future asymptotic infinity, and the S-matrix’s unitarity S^†S = 𝟙 is the cascade-level statement that the PT-symmetry preserves the wavefunction’s L²-norm under the scattering process. The orthodox treatment of S-matrix unitarity (Lehmann–Symanzik–Zimmermann 1955, Glimm–Jaffe 1981 [28]) derives it from the Hermiticity of the Hamiltonian as an axiomatic input; in the McGucken dx₄/dt = ic framework, the PT-symmetry through the interaction event supplies the source upstream. This is a result that deserves its own development beyond the scope of the present paper; we flag it here as a forward-looking observation for the corpus-level treatment of relativistic scattering and S-matrix theory. The connection: S-matrix unitarity, the Born rule’s bilinearity, and the spin-1/2 4π closure are three distinct empirical/facts in orthodox QM; the McGucken dx₄/dt = ic framework’s PT-symmetry-through-E reading places all three on the same upstream geometric foundation, with the symmetry through the relevant physical event (interaction event for scattering, emission event for Born rule, geometric center for spin-1/2 rotations) supplying the content in each case.

**Remark 7.16 (the McGucken Sphere as Huygens wavefront).** The McGucken Sphere from any event E is, by the canonical isotropic expansion of clause 3 of §2.4, exactly the Huygens wavefront from that event: a spherically symmetric secondary wavefront expanding outward at velocity c. The Huygens–Fresnel–Kirchhoff principle of classical wave optics — that every point on a wavefront acts as the source of a new spherical secondary wavefront, with the total wave amplitude at any subsequent point being the integral of these secondary wavefronts — is exactly the McGucken dx₄/dt = ic framework reading: every point on a McGucken Sphere is the center of a new McGucken Sphere at the next time step, supplying the secondary spherical wavefront. The corpus source developing this identification with the reciprocal-generation content of the space-operator pair (𝓜_G, D_M) is [5] (*Reciprocal Generation and Huygens’ Principle in Mathematics and Physics Fathered by dx₄/dt = ic … Whence Operators Generate Spaces of Generative Operators in Mathematics, and Points Generate Spherical Wavefronts of Generative Points in Physics … Huygens as Holography and AdS/CFT*), which establishes that Huygens’ Principle is the physical reading of the same reciprocal-generation structure that the McGucken Category paper [4] formalizes as one of its three theorems on (𝓜_G, D_M). The PT-symmetry through the source event (Theorem 7.11) and the Huygens-Fresnel integral formula are not analogous; they are the same geometry at different cascade levels — the PT-symmetry supplies the wavefunction’s complex-conjugation structure, the Huygens-Fresnel integral supplies the wavefunction’s spatial superposition structure, both descended from the McGucken-Sphere expansion that Principle 2.1 names. The following subsection (§7.11) makes this connection explicit by deriving the standard single-slit and double-slit interference patterns as direct consequences of the McGucken-Sphere Huygens structure combined with the PT-symmetry-through-E reading of the Born rule.

**Remark 7.17 (the McGucken Sphere as the geometric primitive at every step of the Born rule derivation).** The Born rule derivation is closed under one geometric primitive — the McGucken Sphere — whose properties supply every step of the chain from dx₄/dt = ic to P = |ψ|². The table below catalogs the Sphere’s role at each step with the corresponding citation in the present paper.

 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Step in derivation What it is The Sphere’s role Citation
 -------------------- --------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------
 1 The McGucken Principle dx₄/dt = ic Sphere is the geometric realization of the principle at each event: the null wavefront 𝓜_E(t) of x₄-expansion from E Principle 2.1; Definition 2.3

 2 The rank-2 Lorentzian metric η_(μν) The Sphere’s null character ‖Δ X‖² = ‖x‖² + (ict)² = 0 forces signature (-,+,+,+) via (ict)² = -c² t²; rank-2 is intrinsic to a metric tensor Lemma 2.5

 3 Action quantum ħ per Planck-frequency oscillation Sphere’s x₄-advance accumulates one ħ per oscillation along any radial direction, supplying the phase quantum for the path-integral kernel Proposition 2.2

 4 Wavefunction ψ ∈ ℂ ψ(B) = ∑_γ exp(iS[γ]/ħ) is the path-integral kernel from the source event E to the point B ∈ 𝓜_E(t) on the Sphere; complex character forced by Sphere’s x₄-perpendicularity via Frobenius selection of ℂ from {ℝ, ℂ, ℍ} Definition 2.6; Theorem 3.1

 5 Hilbert space 𝓗 Sphere wavefronts ψ_E are the primitive vectors of the construction; Hilbert space 𝓗 = Cauchy completion of finite Huygens–Fresnel–Kirchhoff superpositions of Sphere wavefronts under the geometric-overlap norm Theorem 6.1.5; §6.4.5 Step 1

 6 Conjugate wavefunction ψ^* ψ^* is the orientation-reversed Sphere (x₄^* = -ict), equivalently the Sphere’s PT-reflected image through the source event E, satisfying ψ(PT_E · event) = ψ^*(event) exactly for any McGucken-derived wavefunction Definition 7.3; Theorem 7.11 (ii)

 7 (R1) Reality of P Sphere overlap (Theorem 7.4) and head-on collision rate of two Spheres (Theorem 7.7) are intrinsically real-valued geometric quantities; not a separate probability axiom Theorem 7.4; Theorem 7.7

 8 (R2) Non-negativity of P Collision-event count between two Spheres is non-negative; squared modulus ‖ψ‖² = ψ^*ψ ≥ 0 by construction; not a separate probability axiom Theorem 7.4; Theorem 7.7

 9 (R3) Phase invariance of P Global phase e^(iα) shifts the x₄-origin globally; universality clause of dx₄/dt = ic (Sphere exists at every event with own +ic expansion via Σ_M : p ↦ Σ⁺(p)) makes the shift geometrically unobservable Theorem 2.4 (iv); universality clause

 10 (R4) Bilinearity in (ψ, ψ^*) Rank-2 character of η_(μν) on the Sphere wavefront forces bilinear pairing of forward and conjugate amplitudes; higher-rank pairings (rank-4 quartic, etc.) excluded by rank-counting Lemma 7.1

 11 Born rule P = ‖ψ‖² — uniqueness R1–R4 (all Sphere-geometric) jointly determine P uniquely; phase invariance excludes ψ² and (ψ^*)² terms; reality + non-negativity + normalization fix C = 1 Theorem 7.2

 12 ‖ψ‖² — cascade-level reading Geometric overlap of forward Sphere expansion (phase from x₄ = ict) with conjugate Sphere expansion (phase from x₄^* = -ict) at the detection event B Theorem 7.4

 13 ‖ψ‖² — detection-event reading Head-on collision rate of two physical Spheres: emitter’s outgoing Sphere + absorber’s outgoing Sphere viewed conjugately at the detector P; the conjugate factor ψ^* identified physically as the absorber’s Sphere Theorem 7.7

 14 ‖ψ‖² — free-propagation reading Multiplication of Sphere’s wavefunction at (P, t) with its PT_E-reflected value at (2x_E - P, 2t_E - t); conjugate factor supplied by Sphere’s intrinsic PT-symmetry through its source event Theorem 7.11 (iii)–(iv)

 15 Exponent 2 — Metric Route Rank-2 character of η_(μν) forces bilinearity; rank-4 quartic densities (Aaronson alternative) excluded Lemma 7.1

 16 Exponent 2 — Norm Route Rank-2 sesquilinear inner product → parallelogram identity → L²-norm structure on Hilbert space 𝓗; McGucken-internal, no Jordan–von Neumann required as upstream input Lemma 7.6

 17 Exponent 2 — Collision Route Two-particle character of head-on Sphere collision: the count of physical participants in the detection event is exactly two (emitter Sphere + absorber Sphere) Theorem 7.7; Remark 7.10

 18 Exponent 2 — PT-Symmetry Route Sphere’s natural symmetry through source event E gives ψ^*(P) = ψ(PT_E · P); the Born density’s squaring is the cascade-level expression of this symmetry Theorem 7.11 (iv)

 19 Interference (off-diagonal path-integral terms) Multi-path superposition of Sphere wavefronts produces interference cross-terms exp(i(S[γ] - S[γ'])/ħ) when γ ≠ γ'; constructive and destructive patterns are the geometry of quantum coherence on the Sphere Theorem 7.4 proof; §7.11 (double-slit)

 20 Conclusion P(x) = ‖ψ(x)‖² Sphere geometry forces R1–R4; R1–R4 force the unique bilinear-density form; phase invariance fixes the cross-term structure; reality, non-negativity, and normalization fix the overall constant to C = 1 Theorem 7.2
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Strip the McGucken Sphere from any step in this chain and the derivation collapses entirely: no Sphere → no Lorentzian metric → no rank-2 pairing → no bilinearity (R4); no Sphere → no path-integral kernel → no ψ; no Sphere → no collision-event source → no geometric grounding of R1 and R2; no Sphere → no PT-symmetry → no Theorem 7.11 free-propagation reading and no second McGucken-internal derivation of complex conjugation. The Born rule is therefore not merely *compatible with* the Sphere; it is *forced by* Sphere geometry at every link of the derivation chain.

The exponent 2 in |ψ|² is overdetermined by five McGucken-internal routes, each tracing to a distinct property of the one Sphere and sharing no machinery beyond dx₄/dt = ic and the Sphere itself. In order of foundational priority: **(1) Conservation Route** (the Sphere’s weight conserved under its expansion): the second-order propagation that the rank-2 η_(μν) induces conserves only the quadratic function of the modulus; every |ψ|ᵖ with p ≠ 2 fails conservation, and the renormalized quartic rule (Aaronson’s alternative) fails the finite rate c (Lemma 7.1, Theorem 7.6C) — the exponent being the one that x₄’s expansion conserves. **(2) Haar Route** (the Sphere’s symmetry group): the transitive SO(3) action forces a unique invariant probability measure dμ = sinθ dθ dφ/(4π) (Lemma 7.1.5) — the route that answers why a probability *measure* exists at all. **(3) Norm Route** (Lemma 7.6): the parallelogram identity gives the L²-norm structure, no Jordan–von Neumann needed. **(4) Collision Route** (Theorem 7.7, Lemma 7.7.5): the participant count in a head-on detection is exactly two, the rate sesquilinear, with sum/max/min/means excluded. **(5) PT-Symmetry Route** (Theorem 7.11): the Sphere’s PT_E-reflection gives ψ^*(P) = ψ(PT_E · P), grounding complex conjugation. The first two are foregrounded as most important: the Conservation Route because the exponent is the one that the Principle’s expansion conserves, the Haar Route because it supplies the invariant measure a probability rule requires. The five routes share no intermediate machinery except dx₄/dt = ic and the Sphere; their convergence on the same exponent is the convergent-overdetermination signature of the framework’s Born-rule derivation. The Sphere is therefore the **shared upstream content** of every derivational link from the McGucken Principle to P = |ψ|².

### 7.11 Single-slit and double-slit interference as McGucken-Sphere antipodal self-overlap

The Huygens–Fresnel–Kirchhoff principle (Huygens 1690, Fresnel 1818, Kirchhoff 1882) states that every point on a wavefront acts as the source of a new spherical secondary wavefront, with the total amplitude at any subsequent point being the integral of these secondary wavefronts. In standard wave optics this is a heuristic for diffraction calculations. In the McGucken dx₄/dt = ic framework, the McGucken Principle is exact: every point on a McGucken Sphere is, by the canonical isotropic expansion of clause 3 of §2.4, itself the center of a new McGucken Sphere at the next time step. The single-slit and double-slit interference patterns of standard quantum mechanics are derivable from this McGucken-Sphere combined with the antipodal self-overlap reading of the Born rule (Theorem 7.11), supplying a geometric interpretation of the interference cross-terms that orthodox quantum mechanics treats as formal consequences of linear superposition with no geometric source.

**Theorem 7.12 (Single-slit and double-slit interference as McGucken-Sphere antipodal self-overlap).** *Let a wavefunction ψ_0 propagate through an aperture A (a region of the spatial slice through which the wave is permitted to pass; an opaque screen blocks the wave outside A). By the Huygens–Fresnel–Kirchhoff principle realized in the McGucken dx₄/dt = ic framework as canonical clause 3 of §2.4, every point Q ∈ A acts as the center of a new McGucken Sphere 𝓜_Q(t) of secondary wavefronts propagating at velocity c. At a detection point D on a screen at distance L behind the aperture, the wavefunction is the integral of these secondary McGucken Spheres’ arrivals:*

*ψ(D) = ∫_A K(Q, D) ψ_0(Q) dA(Q),*

*with K(Q, D) the Fresnel–Kirchhoff propagator (1/iλ) exp(ikr_QD)/r_QD · cos θ_Q (and r_QD = |D − Q|, θ_Q the angle of the secondary wavefront at Q). The Born density at the detection point is*

*|ψ(D)|² = ∫_A ∫_A K^*(Q, D) K(Q’, D) ψ_0^*(Q) ψ_0(Q’) dA(Q) dA(Q’),*

*the double integral over all pairs of aperture points (Q, Q’). Each pairing (Q, Q’) is, in the McGucken dx₄/dt = ic framework, the antipodal self-overlap of the Q-McGucken-Sphere’s +i direction at D with the Q’-McGucken-Sphere’s −i direction at D (Theorem 7.11 generalized to multiple-sphere superposition). Two specializations:*

*(i) (Double-slit interference.) For an aperture consisting of two slits at positions Q_1 = (−d/2, 0) and Q_2 = (+d/2, 0) (slit separation d, slit widths neglected), the wavefunction at the detection point D at angle θ from the slit-midpoint is*

*ψ(D) ∝ exp(i k r_1) + exp(i k r_2),*

*with r_i = |D − Q_i|. The Born density is*

*|ψ(D)|² ∝ |exp(i k r_1) + exp(i k r_2)|² = 2 + 2 cos(k Δr) = 4 cos²(k Δr / 2),*

*with Δr = r_2 − r_1 ≈ d sin θ in the Fraunhofer limit. The fringe pattern cos²(k d sin θ / 2) at the screen is geometrically the antipodal self-overlap of the combined wavefunction at D: the cross-term 2 cos(k Δr) is the multiplication of the slit-1-McGucken-Sphere’s +i content at D with the slit-2-McGucken-Sphere’s −i content at D, plus its conjugate, both supplied by the two spheres’ antipodal-orientation structures at D.*

*(ii) (Single-slit diffraction.) For an aperture consisting of a single slit of width w extending from y = −w/2 to y = +w/2, the wavefunction at the detection point D at angle θ from the slit-midpoint is*

*ψ(D) ∝ ∫_{−w/2}^{+w/2} exp(i k y sin θ) dy = w · sinc(α),*

*with α = (k w sin θ)/2 = (π w / λ) sin θ. The Born density is*

*|ψ(D)|² ∝ w² · sinc²(α) = w² · (sin α / α)²,*

*the standard single-slit diffraction pattern. Geometrically, this is the integrated antipodal self-overlap of every pair of aperture-point McGucken Spheres at D: each pair (Q, Q’) with Q, Q’ ∈ slit width contributes its +i direction from Q-sphere multiplied with its −i direction from Q’-sphere, and the double integral over all pairs produces the sinc² envelope.*

**Proof.**

The Fresnel–Kirchhoff propagator K(Q, D) is established in standard wave-optics texts (Born and Wolf, *Principles of Optics*, Pergamon 1959 and later editions). In the McGucken dx₄/dt = ic framework, K(Q, D) is recognized as the path-integral kernel for the McGucken Sphere from event Q reaching event D at parameter time t = r_QD/c, with the kernel structure exp(ikr)/r supplying the phase accumulated along the +i x_4-direction over the spatial distance r and the 1/r factor supplying the geometric spreading of the spherical wavefront (the 1/r² intensity drop becomes 1/r in amplitude). The cos θ_Q factor is the standard Huygens obliquity correction.

The wavefunction at the detection point D is the integral of all secondary McGucken Spheres’ arrivals at D from points Q in the aperture:

ψ(D) = ∫_A K(Q, D) ψ_0(Q) dA(Q).

This is the standard Fresnel–Kirchhoff diffraction integral, derivable from Maxwell’s equations in the scalar-wave approximation and equivalently from the McGucken Sphere structure by clause 3 of §2.4.

The Born density at D is computed by the antipodal self-overlap reading of Theorem 7.11. Applied to the multi-sphere superposition ψ(D) = ∫_A K(Q, D) ψ_0(Q) dA(Q), the +i direction of the combined wavefunction at D is ψ(D) itself; the −i direction is the conjugate ψ^*(D); the Born density is their product:

|ψ(D)|² = ψ^*(D) ψ(D) = [∫_A K^*(Q, D) ψ_0^*(Q) dA(Q)] [∫_A K(Q’, D) ψ_0(Q’) dA(Q’)] = ∫_A ∫_A K^*(Q, D) K(Q’, D) ψ_0^*(Q) ψ_0(Q’) dA(Q) dA(Q’).

The double integral pairs every aperture point Q with every aperture point Q’. The pairing (Q, Q’) is geometrically the antipodal self-overlap (Theorem 7.11) generalized to two distinct sphere-centers: the Q-McGucken-Sphere’s +i direction at D (the wavefunction contribution K(Q, D) ψ_0(Q)) is multiplied with the Q’-McGucken-Sphere’s −i direction at D (the conjugate K^*(Q’, D) ψ_0^*(Q’)). When Q = Q’, this is the intrinsic antipodal self-overlap of a single sphere (Theorem 7.11 applied to a single point Q); when Q ≠ Q’, this is the cross-overlap between two distinct spheres’ antipodal hemispheres.

*(i)* For a double-slit aperture A = {Q_1, Q_2} (two delta-function point apertures), the aperture integral reduces to a discrete sum:

ψ(D) = K(Q_1, D) ψ_0(Q_1) + K(Q_2, D) ψ_0(Q_2).

For equal slit amplitudes ψ_0(Q_1) = ψ_0(Q_2) and far-field Fraunhofer geometry (r_1, r_2 ≫ d, with the obliquity factor cos θ ≈ 1 and the 1/r amplitude factor approximately equal for the two slits), this becomes

ψ(D) ∝ exp(i k r_1) + exp(i k r_2).

The Born density is

|ψ(D)|² ∝ |exp(i k r_1) + exp(i k r_2)|² = 2 + exp(i k(r_2 − r_1)) + exp(−i k(r_2 − r_1)) = 2 + 2 cos(k Δr),

with Δr = r_2 − r_1. In the Fraunhofer far-field limit (Δr ≈ d sin θ), this gives |ψ(D)|² ∝ 2(1 + cos(k d sin θ)) = 4 cos²(k d sin θ / 2) — the standard double-slit fringe pattern.

The cross-term 2 cos(k Δr) is the antipodal self-overlap content: exp(i k r_2) · exp(−i k r_1) = exp(i k Δr) is the slit-2-McGucken-Sphere’s +i content at D multiplied with the slit-1-McGucken-Sphere’s −i content at D; its conjugate exp(−i k Δr) is the reverse pairing; their sum 2 cos(k Δr) is the real-valued interference cross-term. The fringes are visible because the McGucken Spheres from the two slits have well-defined relative phase at D, and their antipodal-direction multiplication produces constructive (cos \> 0) and destructive (cos \< 0) regions alternately as θ varies.

*(ii)* For a single-slit aperture A = {y ∈ [−w/2, w/2]} (continuous one-dimensional slit of width w), the aperture integral is

ψ(D) ∝ ∫_{−w/2}^{+w/2} exp(i k r(y)) dy,

with r(y) = |D − (y, 0)| ≈ L + (y sin θ)·(−1) in the Fraunhofer far-field limit (taking the slit at angle θ = 0 from the detector midline). This gives

ψ(D) ∝ ∫*{−w/2}^{+w/2} exp(−i k y sin θ) dy = ∫*{−w/2}^{+w/2} exp(i k y sin θ’) dy = (2/(k sin θ’)) sin((k w sin θ’)/2) = w · sinc(α),

with α = (k w sin θ’)/2 = (π w / λ) sin θ’ and sinc(x) = sin(x)/x. The Born density is

|ψ(D)|² ∝ w² · sinc²(α) = w² · (sin α / α)²,

the standard single-slit diffraction pattern with primary maximum at θ = 0 and secondary maxima at α = ±(3π/2), ±(5π/2), … with intensities (1/(3π/2))², (1/(5π/2))², …

The double-integral form of the Born density,

|ψ(D)|² ∝ ∫*{−w/2}^{+w/2} ∫*{−w/2}^{+w/2} exp(i k(y’ − y) sin θ) dy dy’,

pairs every aperture point y with every aperture point y’. Each pair (y, y’) contributes the phase factor exp(i k(y’ − y) sin θ), which is geometrically the multiplication of:
- the +i direction at D from the y’-McGucken-Sphere (the outgoing wavefront from y’ arrives at D with phase exp(i k y’ sin θ) relative to the central direction);
- the −i direction at D from the y-McGucken-Sphere (the conjugate phase exp(−i k y sin θ) corresponding to the incoming/conjugate direction at D from y);
- their product exp(i k(y’ − y) sin θ).

The double integral over all (y, y’) pairs produces the sinc² envelope. The diffraction pattern is therefore geometrically the integrated antipodal self-overlap of every pair of aperture-point McGucken Spheres at the detector, with the McGucken-Sphere structure supplying both the interference cross-terms (y ≠ y’) and the intrinsic self-overlap diagonal terms (y = y’). ∎

**Remark 7.14 (interference does not violate the Born rule’s quadratic structure).** A frequent pedagogical mystery in orthodox quantum mechanics is how the interference fringes of double-slit and single-slit setups can be reconciled with the Born rule’s quadratic structure: probabilities sum, but amplitudes interfere — why does the world know to interfere amplitudes rather than probabilities? The McGucken dx₄/dt = ic framework resolves this: the Born rule’s squaring is the antipodal self-overlap of McGucken Spheres at the detector (Theorem 7.11), and when multiple sphere-centers are present (multiple slits or a continuous aperture), the self-overlap naturally includes cross-terms (Q ≠ Q’) as well as diagonal terms (Q = Q’). The cross-terms are the interference fringes; the diagonal terms are the no-interference base intensity; their sum is the full interference pattern. The Born rule does not “interfere amplitudes by special arrangement”; the geometric structure of the McGucken Sphere antipodal self-overlap automatically produces the interference cross-terms as part of the same operation that produces the no-interference base intensity. The orthodox pedagogical mystery of “why amplitudes interfere” dissolves in the McGucken dx₄/dt = ic framework: amplitudes interfere because the antipodal self-overlap of the combined wavefunction at the detector includes cross-terms between sphere-centers, supplied geometrically by the McGucken-Sphere structure of clause 3 of §2.4.

**Remark 7.15 (connection to Berry phase and path-integral interference).** Theorem 7.12’s interference cross-terms are the same content as the Berry-phase non-closure of Theorem 12.11 instance (3) and the path-integral interference of Theorem 12.11 instance (9). All three describe interference effects arising from accumulated x_4-phase along different geometric paths: Berry phase from adiabatic loops in parameter space; path-integral interference from distinct Feynman paths between two events; double-slit interference from two McGucken Spheres (one per slit) arriving at the detector with different accumulated x_4-phase from their respective slit-to-detector path lengths. The universal carrier exp(iS/ℏ) (Theorem 12.11 instance (9)) supplies the phase in all three cases; the universal action quantum ℏ supplies the discreteness scale at which the phase becomes measurable. Double-slit and single-slit interference are therefore not exotic phenomena requiring separate explanation; they are the simplest instances of the universal exp(iS/ℏ) path-integral interference of the McGucken dx₄/dt = ic framework, with the McGucken Sphere supplying the geometric source.

**Remark 7.16 (a verification: the Compton-wavelength scale of fringe spacing).** The fringe spacing in double-slit interference is Δy_fringe = λ L / d, where λ is the wavelength, L the slit-to-detector distance, and d the slit separation. For matter waves (electron, neutron, atom interferometry) the wavelength is the de Broglie wavelength λ_dB = h/p = ℏc/E (Proposition 10.8 (iii)), which for massive particles at rest scales as λ_C = ℏ/(mc) (the Compton wavelength). The empirically measured fringe spacing in neutron interferometry (Rauch et al. 1975 [29]), atom interferometry (Estermann–Stern 1930 and subsequent precision measurements), and molecular interferometry (Arndt–Zeilinger 1999 for C₆₀) all confirm the de Broglie / Compton wavelength scale as the natural fringe-spacing scale — exactly Principle 2.1 empirically confirmed (§2.1 inset). The McGucken dx₄/dt = ic framework’s prediction here is the consolidation under one principle of an enormous existing empirical body that the orthodox tradition treated as a collection of separate “matter-wave phenomena.” Every interference experiment from Young (1801) to modern atom interferometry is, in the McGucken dx₄/dt = ic framework, a measurement of the antipodal self-overlap of McGucken Spheres at the detector, with the fringe spacing supplied by the de Broglie wavelength scale.


## Part VII. The McGucken Principle dx₄/dt = ic Reading of the Born rule as theorem QM T11 of the textbook chain: the dx₄/dt = ic Algebraic Channel via the Cauchy functional equation and the dx₄/dt = ic Geometric Channel via the SO(3)-Haar measure

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts that the Born rule is reached by a second pair of disjoint derivations in the textbook *Quantum Mechanics Derived from the McGucken Principle* [25], where it is theorem QM T11 of the chain of theorems. On the dx₄/dt = ic Algebraic Channel the textbook proof replaces the bilinearity requirement (R4) of Theorem 7.2 by composition under independent products, which turns the four requirements into the multiplicative Cauchy functional equation and yields P = |ψ|ᶜ for some real c; the Schrödinger continuity equation that the Principle supplies (QM T6) and a divergence decomposition then pin c = 2. On the dx₄/dt = ic Geometric Channel the textbook proof runs the Haar route of Lemma 7.1.5 in full: the unique SO(3)-invariant probability measure on the McGucken Sphere (Hewitt–Ross), the U(1)-invariant polynomials of the amplitude by Weyl's first fundamental theorem, and the same divergence decomposition excluding every |ψ|²ᵏ with k ≠ 1. The chapter then records the physical interlocutor of the rule (the absorber's Sphere, Theorem 11.1D), the empirical anchor of the exponent 2 (Sinha et al. 2010), the disjointness audit of the two channels, and the independence of the derivation from Gleason's theorem. The chapter is reproduced verbatim and in full; its theorem and equation labels are the textbook's, and the Postulate 4.1, QM T6, QA1–QA5 and QB7 references inside it are references to the textbook.


### QM T11: The Born Rule P = |ψ|² {#ch:born}

> *The McGucken Principle.* The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.
> Every result below descends from that expansion.


*Recall.* the McGucken Principle (McP:
dx₄/dt = ic) asserts that the fourth spacetime dimension
x₄ expands at the velocity of light c, carrying the
perpendicularity marker i that distinguishes it from the spatial
three. Throughout this chapter, dx₄/dt= ic refers to this
principle and to the five clauses (i)--(v) of
Postulate 4.1: (i) *invariance* --- the rate
dx₄/dt= ic holds at every event with the same value,
independent of matter content; (ii) *spherical symmetry* --- the
expansion is isotropic in the spatial three, with the set of events
reachable from p at coordinate time t being a 2-sphere of radius
c(t - tₚ); (iii) *monotonicity* --- the integral curve is strictly
monotonically increasing in t, fixing the arrow of x₄-advance; (iv)
*Lorentz consistency* --- the structure is SO⁺(1,3)-invariant on
M_G (the McGucken manifold: the spacetime of expanding McGucken Spheres at every point); (v) *global validity* --- dx₄/dt= ic holds at
every event of M_G. The integrated kinematic shadow
x₄ = ict (Remark 4.3) is the kinematic shadow of
dx₄/dt= ic; the dynamical principle
dx₄/dt= ic is the central fact.

This is the result Weinberg [30] singles out as the deepest
foundational problem of the textbook tradition: "Where does the Born
rule come from?" In the McGucken dx₄/dt= ic framework, it is forced twice---once
from the Cauchy functional equation on the dx₄/dt = ic Algebraic Channel, and once from the
SO(3)-Haar measure on the McGucken Sphere on the dx₄/dt = ic Geometric Channel.

#### Statement

**Theorem 11.1** (QM T11: Born Rule, = Theorem 70 (Algebraic Channel) and
Theorem 93 (Geometric Channel) of [31]). *For a normalized state
ψ ∈ 𝓗, the probability of detecting the particle at
spatial position x in a measurement at coordinate time t is

P(x, t) = |ψ(x, t)|².
labeleq:Born
*

*Proof.* We give the Algebraic Channel proof in full and reference the disjoint
Geometric Channel proof below. The Algebraic Channel route derives
eq. (Born) from
four requirements, each a theorem of dx₄/dt= ic; the proof
has six explicit steps. The Born rule descends from the physical,
geometric fact that the fourth dimension is expanding at the velocity of
light c in a spherically symmetric manner
(Postulate 4.1, with x₄ = ict the integrated kinematic
shadow per Remark 4.3): the spherical symmetry of the
x₄-expansion forces the SO(3)-Haar measure on the McGucken Sphere
wavefront, and the perpendicularity marker i in
dx₄/dt= ic forces ψ to be complex, with |ψ|²
then the unique real, non-negative, phase-invariant scalar.

**Step 1: Real-valuedness (R1).** A probability density is real-valued
--- operationally, frequencies of detection events on the 3D spatial
slice (Theorem 19.1) are real numbers. Hence P(x) is real-valued.

**Step 2: Non-negativity (R2).** P(x) ≥ 0 for all x, by the same
operational origin as R1.

**Step 3: Global U(1) phase invariance (R3).** By
Postulate 4.1 clause (i) (invariance --- the rate
dx₄/dt= ic holds with the same magnitude at every event
independent of overall phase) and
Theorem 16.1
(gauge invariance, with the global U(1) a consequence of
dx₄/dt= ic via the integrated x₄ = ict entering the
matter wavefunction only through exp(linear in x₄)), the
global transformation ψ(x) → e^(iα)ψ(x) leaves
dx₄/dt= ic unchanged. Hence P(x) depends on ψ only
through |ψ(x)|.

**Step 4: Composition under independent products (R4) and the
multiplicative Cauchy equation.** For two independent subsystems with
Ψ(x₁, x₂) = ψ₁(x₁)ψ₂(x₂), the joint probability
factors: P₁₂(x₁, x₂) = P₁(x₁)P₂(x₂). By R1--R3,
P(x) = f(|ψ(x)|) for some
f: ℝ_(≥ 0) → ℝ_(≥ 0). Substituting into the
factorization and using |ψ₁ψ₂| = |ψ₁|·|ψ₂|:

f(uv) = f(u) f(v) for all u, v ≥ 0.
 *Boundary value
at u = 0.* Setting v = 0: f(0) = f(0)f(v) = f(0)f(0) = f(0)²,
hence f(0) ∈ {0, 1}. The case f(0) = 1 would assign nonzero
probability density to the point where ψ vanishes, contradicting
R2's operational origin (where ψ = 0 no detection events occur).
Hence f(0) = 0. *Multiplicative non-degeneracy on ℝ_(>0).*
If f(u₀) = 0 for some u₀ > 0, then for every v > 0,
f(u₀ v) = f(u₀)f(v) = 0, so f ≡ 0 on
u₀ℝ_(>0) = ℝ_(>0), giving the degenerate solution
P ≡ 0 everywhere. Excluding this degenerate case (which
corresponds to the null wavefunction ψ ≡ 0), f > 0 on
ℝ_(>0). *Logarithmic substitution.* For u, v > 0 with
f(u), f(v) > 0, take logarithms: setting g(log u) := log f(u), the
multiplicative equation becomes the additive Cauchy equation
g(s+t) = g(s) + g(t) on ℝ. Smoothness of
ψ ↦ P(ψ) under the continuous time-evolution of
Schrödinger (Theorem 7.1) forces f, and hence g, to be continuous,
hence Lebesgue-measurable. By
Theorem 3.9
(Hewitt--Stromberg [32] Theorem 17.16), the only
measurable solutions of the additive Cauchy equation are linear:
g(s) = c s for some constant c ∈ ℝ. Therefore
f(u) = uᶜ on ℝ_(>0), and f(|ψ|) = |ψ|ᶜ on the
support of ψ, with the f(0) = 0 boundary value extending the
formula to |ψ| = 0 by continuity (for c > 0).

**Step 5: Pinning c = 2 by the continuity equation.** The Schrödinger
equation (Theorem 7.1) supplies the continuity equation
∂ₜ|ψ|² + ∇·j = 0 with quadratic current
j = (iħ/2m)(ψ∇ψ^* - ψ^*∇ψ). We
verify by direct computation, then derive uniqueness of c = 2 by an
explicit divergence-decomposition argument.

*Verification of the continuity equation.* Schrödinger reads
iħ ∂ₜψ = Ĥψ, hence
∂ₜψ = -(i/ħ)Ĥψ. The conjugate, using
self-adjointness of Ĥ on real-valued V, is
∂ₜψ^* = +(i/ħ)Ĥψ^*. Then

∂ₜ|ψ|² = ψ^* ∂ₜψ + ψ ∂ₜψ^* = -i/ħψ^*Ĥψ + i/ħψĤψ^* = -i/ħ[ψ^*Ĥψ - ψĤψ^*].

Substituting Ĥ= -(ħ²/2m)∇² + V with
V ∈ ℝ:

ψ^*Ĥψ - ψĤψ^* = -ħ²/2m[ψ^*∇²ψ - ψ∇²ψ^*] + V[ψ^*ψ - ψψ^*] = -ħ²/2m ∇·[ψ^*∇ψ - ψ∇ψ^*],

using Vψ^*ψ - Vψψ^* = 0 and the Leibniz identity
ψ^*∇²ψ - ψ∇²ψ^* = ∇·(ψ^*∇ψ - ψ∇ψ^*).
Therefore

∂ₜ|ψ|² = -i/ħ·(-ħ²/2m) ∇·[ψ^*∇ψ - ψ∇ψ^*] = iħ/2m ∇·[ψ^*∇ψ - ψ∇ψ^*].

Hence ∂ₜ|ψ|² + ∇·j = 0 with
j = -iħ/2m(ψ^*∇ψ - ψ∇ψ^*) = iħ/2m(ψ∇ψ^* - ψ^*∇ψ).
The current j is bilinear in
(ψ, ∇ψ^*) ∪ (ψ^*, ∇ψ): each term is a local
algebraic product of ψ or ψ^* with a first-order spatial
derivative of the conjugate field. No higher-derivative or non-bilinear
terms appear.

*Uniqueness of c = 2 by divergence decomposition.* Consider
P⁽ᶜ⁾(x, t) = |ψ(x, t)|ᶜ for c > 0. We ask:
for which c does P⁽ᶜ⁾ satisfy a continuity equation
∂ₜ P⁽ᶜ⁾ + ∇· J⁽ᶜ⁾ = 0 with
J⁽ᶜ⁾ a local current bilinear in (ψ, ψ^*) and
their first-order spatial derivatives, with V-independence of
J⁽ᶜ⁾ (so the current depends only on ψ and not on the
external potential)?

By the chain rule, |ψ|ᶜ = (|ψ|²)^(c/2), so

∂ₜ P⁽ᶜ⁾ = c/2 (|ψ|²)^(c/2 - 1) ∂ₜ|ψ|² = c/2 |ψ|ᶜ⁻² ∂ₜ|ψ|² = -c/2 |ψ|ᶜ⁻² ∇·j,

using the verified continuity equation for |ψ|². Decompose the
right-hand side by the product rule for the divergence:

|ψ|ᶜ⁻² ∇·j = ∇·(|ψ|ᶜ⁻² j) - (∇|ψ|ᶜ⁻²)·j.

The first term is a local divergence; it admits the form
∇·J⁽ᶜ⁾ with
J⁽ᶜ⁾ = (c/2)|ψ|ᶜ⁻² j. The second term,
(∇|ψ|ᶜ⁻²)·j, is not in general a divergence:
its value is

(∇|ψ|ᶜ⁻²)·j = (c-2) |ψ|ᶜ⁻⁴ (∇|ψ|²)/2·j = (c-2)/2 |ψ|ᶜ⁻⁴ (∇|ψ|²)·j.

For c = 2, the prefactor (c-2)/2 = 0 and the second term vanishes
identically, leaving ∂ₜ P⁽²⁾ = -∇·J⁽²⁾
with J⁽²⁾ = j --- a continuity equation in the
required form. For c ≠ 2, the second term
(c-2)/2|ψ|ᶜ⁻⁴(∇|ψ|²)·j is not in
general a divergence and not zero on generic wavefunctions; to absorb it
into the divergence on the LHS would require introducing an additional
non-bilinear or higher-derivative current, contradicting the requirement
that J⁽ᶜ⁾ be bilinear in first derivatives. Therefore
c = 2 is the unique exponent for which P⁽ᶜ⁾ = |ψ|ᶜ satisfies
a continuity equation with a local bilinear current built from
ψ, ψ^*, ∇ψ, ∇ψ^* and depending only on ψ
(not on V).

**Step 6: Normalization and McGucken anchoring.** With c = 2,
∫|ψ|² d³x = 1 is the standard L²-normalization, consistent
with 𝓗= L²(ℝ³) from
Theorem 9.20 (Hilbert space as a theorem of
dx₄/dt= ic). Therefore P(x) = |ψ(x)|², which is
eq. (Born). The
complex character of ψ that makes |ψ|² non-trivial is itself
a consequence of the perpendicularity marker i in
dx₄/dt= ic
(Theorem 9.10); the i in the continuity-equation
current j is case 2 of
Theorem 9.21, the chain-rule image of the
McGucken-Principle i.

**Geometric Channel.** The disjoint Geometric Channel derivation appears in
§11.3 below: it derives P = |ψ|² from the
SO(3)-Haar measure on the McGucken Sphere wavefront M⁺ₚ(t)
(forced by Postulate 4.1 clause (ii), spherical symmetry of the
x₄-expansion) combined with U(1)-equivariance of the probability
density and continuity-equation conservation under Schrödinger
evolution. The Geometric Channel route does not invoke the Cauchy functional
equation; the Algebraic Channel route does not invoke the Haar measure. The two
are derivationally disjoint and agree. □

#### Geometric Channel derivation (QB7 --- SO(3)-Haar measure on McGucken Sphere) {#ssec:T11-channelB}

*Geometric Channel Derivation 11.4* (Born rule from SO(3)-equivariant
probability density on the wavefront). **Step B-1 (Wavefront and
section).** By QB1+QB2, the wavefront M⁺ₚ(t) at coordinate time
t > tₚ is the McGucken-Sphere image of the source event p. The
matter wavefunction ψ is, in the Geometric Channel reading, a section of a
complex U(1)-line bundle E → M⁺ₚ(t): at each point
x ∈ M⁺ₚ(t), ψ(x) ∈ Eₓ ≅ ℂ, with the gauge
group U(1) acting on each fiber by
ψ(x) → e^(iα(x))ψ(x).

**Step B-2 (SO(3)-Haar measure on the wavefront, QB7).** By the
spherical-symmetry clause (ii) of dx₄/dt= ic,
M⁺ₚ(t) is a 2-sphere; the rotation group SO(3) acts
transitively on it. By the Haar theorem (Hewitt--Ross, *Abstract
Harmonic Analysis*, Theorem 15.5), there exists a *unique* (up to
overall normalization) measure on the 2-sphere invariant under the
transitive SO(3)-action: the spherical Haar measure
dΩ = sinθ dθ dφ. Normalizing to unit total mass:

∫_(M⁺ₚ(t)) dΩ_(normalised) = 1.
 This is the
unique SO(3)-equivariant probability measure on the bare wavefront
2-sphere.

**Step B-3 (Imprint of the wavefunction's amplitude).** The bare Haar
measure dΩ corresponds to a uniform wavefunction
|ψ|² = const. For a generic ψ, the amplitude
|ψ(x)|² is non-uniform; the physical probability measure on
M⁺ₚ(t) must therefore be of the form

dμ(x) = ρ[ψ(x), ψ^*(x)] dΩ(x)
labeleq:wavefront-density
 for some density ρ on M⁺ₚ(t)
depending on the wavefunction.

**Step B-4 (U(1)-equivariance pins the polynomial form of ρ).**
The density ρ must be invariant under the local U(1) phase action
ψ → e^(iα(x))ψ (the same gauge freedom that supplies the
connection in QM T16, Chapter 16). Smoothness of ρ under continuous
time-evolution by the Schrödinger equation
(Theorem 7.1)
requires ρ to be a polynomial in (ψ, ψ^*) to leading order
in |ψ| (higher-derivative dependence is excluded by locality at
x).

*Polynomial U(1)-invariant theory.* The polynomial algebra
ℂ[ψ, ψ^*] carries the U(1)-action
(ψ, ψ^*) ↦ (e^(iα)ψ, e^(-iα)ψ^*). A
monomial ψᵐ(ψ^*)ⁿ transforms by the phase e^(i(m-n)α);
it is U(1)-invariant if and only if m = n. Hence the algebra of
U(1)-invariant polynomials in (ψ, ψ^*) is generated by the
single invariant ψψ^* = |ψ|² (classical invariant theory of
the diagonal U(1)-action; see Weyl, *The Classical Groups*, Theorem
II.A on the first fundamental theorem for U(1)). The most general
U(1)-invariant polynomial density therefore takes the form

ρ = ρ₀ + ρ₁ |ψ|² + ρ₂ |ψ|⁴ + ⋯ + ρ_K |ψ|^(2K)

for some K < ∞ and constants ρₙ ∈ ℂ. Reality of
ρ (R1 of the Algebraic Channel) forces each ρₙ ∈ ℝ;
non-negativity (R2) constrains the ρₙ further. The operational
requirement that ρ → 0 where ψ → 0 (no detection
probability at points where the wavefunction vanishes) forces
ρ₀ = 0, since the |ψ|²ⁿ terms with n ≥ 1 all vanish at
ψ = 0 but ρ₀ does not.

*Divergence-decomposition exclusion of higher powers.* For k ≥ 2, we
ask: does |ψ|²ᵏ admit a local continuity equation
∂ₜ|ψ|²ᵏ + ∇·J⁽²ᵏ⁾ = 0 with
J⁽²ᵏ⁾ bilinear in first derivatives of (ψ, ψ^*)
and independent of the external potential V? By the chain rule applied
to the Schrödinger continuity equation
eq. (continuity) for |ψ|²:

∂ₜ|ψ|²ᵏ = k |ψ|²⁽ᵏ⁻¹⁾ ∂ₜ|ψ|² = -k |ψ|²⁽ᵏ⁻¹⁾ ∇·j.

Decompose by the product rule for the divergence:

|ψ|²⁽ᵏ⁻¹⁾ ∇·j = ∇·(|ψ|²⁽ᵏ⁻¹⁾ j) - (∇|ψ|²⁽ᵏ⁻¹⁾)·j.

The first term admits the form ∇·J⁽²ᵏ⁾ with
J⁽²ᵏ⁾ = k |ψ|²⁽ᵏ⁻¹⁾ j. The second term
equals

(∇|ψ|²⁽ᵏ⁻¹⁾)·j = (k-1) |ψ|²⁽ᵏ⁻²⁾ (∇|ψ|²)·j,

which for k ≥ 2 has coefficient (k-1) ≥ 1 and is non-vanishing
on generic wavefunctions. Therefore |ψ|²ᵏ for k ≥ 2 does
not satisfy a continuity equation with a local bilinear V-independent
current; only k = 1 admits the required form (with (k-1) = 0).

*Conclusion.* Combining the polynomial-invariant theorem (ρ is a
polynomial in |ψ|²), the boundary condition (ρ₀ = 0), and
the divergence-decomposition argument (only |ψ|² admits the
required continuity equation), the density reduces to

ρ = ρ₁ |ψ|²,
 with the constant ρ₁ fixed in
Step B-5.

**Step B-5 (Normalization).** Demand ∫_(M⁺ₚ(t)) dμ = 1 for
normalized ψ (i.e., ∫ |ψ|² d³x = 1). This forces
ρ₁ = 1 in spatial-volume coordinates, yielding

dμ(x) = |ψ(x)|² d³ x.


The probability of detecting the particle at x ∈ M⁺ₚ(t) is
therefore |ψ(x)|² d³ x, exactly the Born rule. ◻

**Upstream geometric route.** The dedicated derivation paper
[12-CCR-2026], Theorem T4.2, gives the upstream geometry
of the Born rule: the Minkowski metric induced by x₄= ict is rank
2, so the x₄-flux density is bilinear in (ψ, ψ^*); phase
invariance, reality, non-negativity, and normalization then fix the
density to be |ψ|². The Geometric Channel derivation above is the
McGucken-Sphere SO(3)-Haar-measure realization of the same upstream
geometric fact; the explicit signature-rank argument supplies the deeper
reason that the density is the squared modulus rather than
the bare modulus.

**The Born density as x₄-overlap diagonal.** The geometry of
the Born rule is further refined by Theorem 5.3 of [1]:
the inner product ⟨φ, ψ⟩ = ∫ φ^*ψ d³ x is
the integrated forward--conjugate x₄-overlap of two
oppositely-oriented Sphere expansions on a spatial slice. The Born
probability density at x is the *diagonal* of this overlap with
φ = ψ: 
ρ(x) = (ψ^* ψ)(x) = |ψ(x)|²,
 the
pointwise pairing of the forward x₄-advance with the conjugate
x₄-advance at the spatial event x. The squared modulus has two
equivalent readings: the U(1)-equivariant bilinear density
characterised in Steps B-1 through B-5 above, and the pointwise diagonal
of the integrated x₄-overlap structure that defines the Hilbert-space
inner product. The Born rule and the Hilbert-space inner product share a
single underlying construction: they are the diagonal and integrated
readings of the same forward--conjugate x₄-overlap.

#### Algebraic Channel derivation (QA5 plus Cauchy functional equation)

*Algebraic Channel Derivation 11.2* (Born rule from four requirements). We derive eq. (Born) from four requirements, each itself a theorem of
dx₄/dt= ic:

**Requirement (R1) --- Real-valuedness.** A probability density is a
real-valued function. The wavefunction
ψ: ℝ³ → ℂ is complex; the probability density
P(x) must be a real-valued function built from ψ(x) and
ψ^*(x).

*Audit.* R1 follows from the operational fact that probabilities are
frequencies of detection events on the 3D spatial slice
(Theorem 19.1,
Algebraic Channel reading) and frequencies are real numbers.

**Requirement (R2) --- Non-negativity.** P(x) ≥ 0 for all x.
*Audit:* same operational origin as R1.

**Requirement (R3) --- Global U(1) phase invariance.** By the
universal-rate clause QA1 of
Postulate 4.1, dx₄/dt= ic holds with the same
magnitude c at every event, independent of an overall phase choice.
Hence the global transformation ψ(x) → e^(iα)ψ(x) with
α ∈ ℝ constant leaves dx₄/dt= ic
unchanged. Probabilities, as observables, must therefore be invariant
under this global phase: P(x) depends on ψ only through
|ψ(x)|, not through arg ψ(x).

*Audit.* This is the formal expression of QA7's global U(1) symmetry,
derived without reference to the gauge-field machinery of QA7's
local-promotion extension.

**Requirement (R4) --- Composition under independent product states.**
Consider two physically independent one-particle subsystems on disjoint
regions of space, with wavefunctions ψ₁(x₁), ψ₂(x₂). The
composition rule for independent subsystems is the tensor product
(Reed--Simon [33] §II.4); on configuration space, the joint
wavefunction is the product 
Ψ(x₁, x₂) = ψ₁(x₁) ψ₂(x₂).
labeleq:independent-product
 The joint detection probability
density, being the frequency of joint detection events, must factor
under independence: 
P₁₂(x₁, x₂) = P₁(x₁) P₂(x₂).
labeleq:probability-factors


*Audit.* Independence here is the operational condition that the two
subsystems are not entangled and not interacting;
eq. (independent-product) is the standard tensor-product
structure for non-entangled subsystems (which precedes the Born rule in
the derivation order: tensor-product Hilbert space structure follows
from QA1+QA4 Stone--von Neumann uniqueness applied to the joint
observable algebra, without invoking the probability density).

*Upstream geometric reading.* The bilinear form of the probability density in (ψ, ψ^*) follows more directly from the rank-2 character of the McGucken-derived Minkowski metric: by
Lemma 9.13 of
Chapter 9, the natural local density on the
spatial slice induced by a geometric pairing of ψ with ψ^*
through the Minkowski metric is bilinear in
(ψ(x, t), ψ^*(x, t)), with higher-rank
alternatives (e.g., |ψ|⁴) excluded by the rank-2 character of
g_(μν). The R4-plus-Cauchy route of the present chapter and the
rank-2-metric route of
Lemma 9.13 are two complementary derivations of
the same bilinear form: the operational route (R4 supplies
tensor-product independence, Cauchy supplies the
multiplicative-to-power-law step) and the geometric route (rank-2
contraction of one-forms). Both reach the bilinear ansatz; the present
chapter then pins the exponent c = 2 by the continuity-equation
argument of Step 5, while the rank-2-metric route reaches |ψ|²
directly by identifying the bilinear contraction at the 0-form level
as ψ^*ψ.

*Derivation.* By R1--R3, the density has the form P(x) = f(|ψ(x)|)
for some function f: ℝ_(≥ 0) → ℝ_(≥ 0). By
eq. (probability-factors) applied to
eq. (independent-product):

f(|ψ₁(x₁)ψ₂(x₂)|) = f(|ψ₁(x₁)|) f(|ψ₂(x₂)|).

Since |ψ₁ψ₂| = |ψ₁| |ψ₂|, this reads

f(uv) = f(u) f(v) for all u, v ∈ ℝ_(≥ 0).
labeleq:f-multiplicative


**Solving
eq. (f-multiplicative).** The function
f: ℝ_(≥ 0) → ℝ_(≥ 0) satisfies
f(uv) = f(u)f(v) for all u, v ≥ 0. We extract the content in three sub-steps.

*Boundary value at zero.* Setting v = 0 in f(uv) = f(u)f(v) gives
f(0) = f(u)f(0) for all u ≥ 0, equivalently f(0)[1 - f(u)] = 0.
If f(0) ≠ 0 then f(u) ≡ 1 for all u ≥ 0, which violates
the operational requirement that P → 0 as |ψ| → 0 (no
probability where there is no wavefunction). Hence f(0) = 0.

*Non-degeneracy on ℝ_(>0).* If f(u₀) = 0 for some
u₀ > 0, then for every v > 0, f(u₀ v) = f(u₀)f(v) = 0. The set
u₀ℝ_(>0) equals ℝ_(>0), so f ≡ 0 on
ℝ_(>0), yielding the degenerate solution P ≡ 0
everywhere. Excluding this degenerate case (which corresponds to the
null wavefunction ψ ≡ 0), f > 0 on ℝ_(>0).

*Logarithmic substitution.* For u, v > 0, take logarithms
(well-defined since f(u), f(v) > 0 by the previous sub-step). Set
g(log u) := log f(u). Then
g(log u + log v) = g(log u) + g(log v), i.e., g satisfies the
additive Cauchy functional equation on ℝ.

The probability density is continuous in ψ (it must depend smoothly
on the wavefunction; otherwise infinitesimal variations of ψ would
produce discontinuous jumps in detection probabilities, contradicting
the smooth time-evolution of ψ under
Theorem 7.1).
Hence f is continuous, hence g is continuous, hence
Lebesgue-measurable. By Theorem 3.9 (Hewitt--Stromberg [32]
Theorem 17.16), the only measurable solutions of Cauchy's equation are
linear: g(u) = c u for some constant c ∈ ℝ. Therefore

log f(|ψ|) = c log|ψ| Longleftrightarrow f(|ψ|) = |ψ|ᶜ for |ψ| > 0,

with the boundary value f(0) = 0 extending the formula to |ψ| = 0
continuously when c > 0.

**Pinning c = 2.** By R2, f ≥ 0, hence c ∈ ℝ. We pin
c by the unit-normalization requirement combined with the
time-evolution conservation law.

*Time-evolution conservation.* The Schrödinger equation
(Theorem 7.1)
implies the continuity equation

∂ₜ |ψ|² + ∇ · j = 0, j = iħ/2m(ψ ∇ψ^* - ψ^* ∇ψ),
labeleq:continuity
 verified by direct computation as follows.
Schrödinger reads iħ ∂ₜψ = Ĥψ, hence
∂ₜψ = -(i/ħ)Ĥψ. Self-adjointness of Ĥ
(with V ∈ ℝ) gives the conjugate equation
∂ₜψ^* = +(i/ħ)Ĥψ^*. Then

∂ₜ |ψ|² = ψ^* ∂ₜψ + ψ ∂ₜψ^* = ψ^*(-iĤ/ħ)ψ + ψ(iĤ/ħ)ψ^* = -(i/ħ)[ψ^*Ĥψ - ψĤψ^*].

Substituting Ĥ= -(ħ²/2m)∇² + V with
V ∈ ℝ, the potential term cancels
(Vψ^*ψ - Vψψ^* = 0) and the kinetic term gives, by the
Leibniz identity
ψ^*∇²ψ - ψ∇²ψ^* = ∇·(ψ^*∇ψ - ψ∇ψ^*):

ψ^*Ĥψ - ψĤψ^* = -(ħ²/2m) ∇·(ψ^*∇ψ - ψ∇ψ^*).

Hence
∂ₜ|ψ|² = (iħ/2m) ∇·(ψ^*∇ψ - ψ∇ψ^*),
which is -∇·j with
j = (iħ/2m)(ψ∇ψ^* - ψ^*∇ψ). The
current j is bilinear in
(ψ, ∇ψ^*) ∪ (ψ^*, ∇ψ): each term is a local
algebraic product of ψ or ψ^* with a first-order spatial
derivative of the conjugate field, and j is independent of
the external potential V.

*Uniqueness of c = 2 by divergence decomposition.* Consider
P⁽ᶜ⁾(x, t) = |ψ(x, t)|ᶜ for c > 0. We ask:
for which c does P⁽ᶜ⁾ satisfy a continuity equation
∂ₜ P⁽ᶜ⁾ + ∇· J⁽ᶜ⁾ = 0 with
J⁽ᶜ⁾ a local current bilinear in (ψ, ψ^*) and
their first-order spatial derivatives, with J⁽ᶜ⁾
independent of the external potential V?

By the chain rule applied to |ψ|ᶜ = (|ψ|²)^(c/2):

∂ₜ P⁽ᶜ⁾ = c/2 (|ψ|²)^(c/2 - 1) ∂ₜ|ψ|² = c/2 |ψ|ᶜ⁻² ∂ₜ|ψ|² = -c/2 |ψ|ᶜ⁻² ∇·j.

Decompose the right-hand side by the product rule for the divergence:

|ψ|ᶜ⁻² ∇·j = ∇·(|ψ|ᶜ⁻² j) - (∇|ψ|ᶜ⁻²)·j.

The first term is a local divergence, admitting the form
∇·J⁽ᶜ⁾ with
J⁽ᶜ⁾ = (c/2)|ψ|ᶜ⁻² j. The second term
equals

(∇|ψ|ᶜ⁻²)·j = (c-2)/2 |ψ|ᶜ⁻⁴ (∇|ψ|²)·j.

For c = 2, the prefactor (c-2)/2 = 0 and the second term vanishes
identically, leaving ∂ₜ P⁽²⁾ = -∇·J⁽²⁾
with J⁽²⁾ = j --- a continuity equation in the
required form. For c ≠ 2, the second term
(c-2)/2|ψ|ᶜ⁻⁴(∇|ψ|²)·j is not in
general a divergence and is non-vanishing on generic wavefunctions;
absorbing it would require introducing a non-bilinear or
higher-derivative current, contradicting the requirement that
J⁽ᶜ⁾ be bilinear in first derivatives. Therefore c = 2
is the unique exponent for which P⁽ᶜ⁾ = |ψ|ᶜ satisfies a
continuity equation with a local bilinear current built from
ψ, ψ^*, ∇ψ, ∇ψ^* and independent of the external
potential V.

*Unit normalization.* With c = 2, ∫ |ψ|² d³x = 1 is the
standard L²-normalization, consistent with
𝓗= L²(ℝ³).

Therefore 
P(x) = |ψ(x)|²,
 exactly equation
eq. (Born). ◻

*Why c ≠ 1.* A frequent confusion is to write P = |ψ| rather
than |ψ|². The above derivation forces c = 2 via the
continuity-equation requirement, not by aesthetic choice: |ψ|ᶜ for
c ≠ 2 does not satisfy a quadratic-current continuity equation under
Schrödinger evolution. The Sinha--Couteau--Jennewein--Laflamme--Weihs
2010 three-slit experiment [34] ruled out c ≠ 2 alternatives
to ∼ 10⁻³ in laboratory measurements.

The Algebraic Channel derivation uses (1) the Cauchy functional equation as the
algebra of independent-subsystem composition, (2) the
Schrödinger continuity equation as the dynamical pinning of c = 2, and
(3) unit normalization on L²(ℝ³) as the final fixing of the
constant of proportionality.

*Remark 11.3* (McGucken machinery used in the Algebraic Channel Born proof).
Every step of the proof above is forced by dx₄/dt= ic
alone, with no external mathematical postulate essential.

**McGucken machinery used.** (1) dx₄/dt= ic via QA1's
universal-rate clause supplying global U(1) phase invariance (R3); (2)
operational origin of probabilities as detection frequencies on the
spatial slice (R1, R2); (3) the McGucken-Sphere Hilbert space
𝓗= L²(ℝ³) as a theorem of
dx₄/dt= ic
(Theorem 9.20), supplying the tensor-product
structure for R4 via the Algebraic Channel axiom QA4 (Stone--von Neumann); (4) the
Cauchy functional equation as elementary real analysis
(Hewitt--Stromberg [32] Theorem 17.16, confirmatory);
(5) the McGucken-Schrödinger continuity equation
(Theorem 7.1)
pinning c = 2.

**No external machinery is essential.** The Cauchy functional
equation appears only as the algebraic shape of R4 combined with R1--R3,
with its measurable solutions (g(u) = cu) being a fact of elementary
measure theory. The continuity-equation pinning of c = 2 is the
essential McGucken-machinery step.

**Confirmation.** Sinha--Couteau--Jennewein--Laflamme--Weihs 2010
[34] ruled out c ≠ 2 alternatives experimentally to
∼ 10⁻³; the empirical pinning of c = 2 confirms the
continuity-equation derivation above without supplying the reason for it.

**Upstream Geometric Channel route.** The same Born density |ψ|² is
derived as the unique U(1)-equivariant polynomial density on the
SO(3)-Haar measure of the McGucken Sphere (Geometric Channel below), which
itself descends from the rank-2 Minkowski metric (Theorem T4.2 of
[12-CCR-2026]). The Geometric Channel route does not invoke the Cauchy
functional equation; the agreement of the two routes is the
disjointness-theorem instance for Born.

#### Exponent-2 overdetermination: the Metric Route and the Norm Route both force |ψ|² {#sec:born-exponent-2-overdetermination}

The Algebraic Channel proof of
Theorem 11.1 pinned the exponent c = 2 in
P = |ψ|ᶜ via the continuity-equation argument (Step 5: only the
quadratic |ψ|² admits a local current bilinear in first derivatives
without external-potential dependence). The Geometric Channel
derivation (Geometric Channel Derivation 11.4) reached P = |ψ|² via
SO(3)-Haar measure with U(1)-equivariance forcing the polynomial
form to be a function of |ψ|². Both routes pin the exponent at
2. The present section establishes a third fact: the
exponent 2 is *overdetermined* by two derivationally disjoint
McGucken-internal routes that share no intermediate machinery between
the McGucken Principle and the conclusion. Both routes are internal to
the framework; both descend from dx₄/dt = ic; neither
requires Jordan–von Neumann 1935 [26] or
Lesovik 2014 [27] as upstream input.

##### The McGucken-internal parallelogram identity {#sec:parallelogram-mcgucken-internal}

The parallelogram identity is the algebraic gateway between an
inner-product space's sesquilinear structure and its L²-norm
structure. In the standard functional-analytic literature
([26]) it appears as the *characterising* identity
for L²: a normed space is a Hilbert space if and only if its norm
satisfies the parallelogram identity, with L² then the unique
Lᵖ space among 1 ≤ p ≤ ∞ for which this holds. In the
McGucken dx₄/dt= ic framework the identity has a substantially shorter
derivation: it follows by a *direct two-line algebraic computation*
from the rank-2 sesquilinearity of the inner product established in
Lemma 9.13. No external functional analysis is
invoked; the identity is a McGucken-internal downstream consequence of
rank-2 sesquilinearity, which is itself a McGucken-internal
consequence of (ic dt)² = -c² dt²
(Theorem 9.2 Step 3).

**Lemma 11.1A** (McGucken-internal parallelogram identity;
[1] Lemma 7.6). *Let
⟨ ·, · ⟩ be the rank-2 sesquilinear inner
product on the McGucken-derived Hilbert space 𝓗 supplied
by Lemma 9.13. Let ‖ψ‖² := ⟨ ψ, ψ ⟩ denote the induced norm. Then for every
x, y ∈ 𝓗,

‖x + y‖² + ‖x - y‖² = 2(‖x‖² + ‖y‖²),

with the identity holding as a direct two-line algebraic consequence
of rank-2 sesquilinearity, internal to the McGucken dx₄/dt= ic framework and
independent of any external functional-analytic input.*

*Proof (two lines).* Everything below descends from the physical expansion of x₄ at the velocity of light, in a spherically symmetric manner, from every event of M_G (dx₄/dt= ic). Expanding the left-hand side using
sesquilinearity (conjugate-linear in the first argument, linear in
the second; or the reverse — the convention is fixed in
Theorem 3.2):

‖x + y‖² = ⟨ x + y, x + y ⟩ = ⟨ x, x ⟩ + ⟨ x, y ⟩ + ⟨ y, x ⟩ + ⟨ y, y ⟩,


‖x - y‖² = ⟨ x - y, x - y ⟩ = ⟨ x, x ⟩ - ⟨ x, y ⟩ - ⟨ y, x ⟩ + ⟨ y, y ⟩.

Adding: the cross-terms ± ⟨ x, y ⟩ and
± ⟨ y, x ⟩ cancel, leaving

‖x + y‖² + ‖x - y‖² = 2⟨ x, x ⟩ + 2⟨ y, y ⟩ = 2(‖x‖² + ‖y‖²).

The cancellation of cross-terms is exactly the algebraic statement
that the pairing ⟨ ·, · ⟩ is rank-2 (degree
1 + 1 in (x, y) with no higher-degree terms). For a rank-4 quartic
pairing (e.g., a hypothetical ⟨ x, y ⟩⁽⁴⁾
quadrilinear in (x, y, x^*, y^*)) the cross-terms would not cancel
in this way and the parallelogram identity would fail. The
parallelogram identity is therefore the algebraic
witness-of-rank-2-ness of the inner product, derivable
McGucken-internally from
Lemma 9.13 and ultimately from
(ic dt)² = -c² dt² of
Theorem 9.2 Step 3. ◻

*Remark 11.1B* (Jordan–von Neumann 1935 as downstream consistency
check, not upstream input). The Jordan–von Neumann theorem
[26] historically established that a normed space
admits an inner product if and only if its norm satisfies the
parallelogram identity, with the corollary that among Lᵖ spaces
only L² is a Hilbert space. In the McGucken dx₄/dt= ic framework, this
theorem is *unnecessary as upstream input*: the inner product on
𝓗 is supplied directly by
Lemma 9.13 from the rank-2 Minkowski metric,
and the parallelogram identity follows by
Lemma 11.1A as a
McGucken-internal downstream consequence. Jordan–von Neumann therefore
serves as a *downstream consistency check* — confirming that the
McGucken-derived parallelogram-identity structure on the
McGucken-derived 𝓗 is consistent with general functional
analysis on Lᵖ spaces — rather than as a selection
principle. The McGucken dx₄/dt= ic framework derives the L² character of
𝓗 internally; Jordan–von Neumann's historical theorem is
cited as the standard functional-analytic correlate but is not used as
upstream input to the chain of theorems.

##### The Norm Route: Lᵖ non-conservation for p ≠ 2 {#sec:norm-route-Lp}

The McGucken-derived Schrödinger evolution
(Theorem 7.1) preserves the L² norm exactly:

(d/dt) ∫_(ℝ³) |ψ(x, t)|² d³ x = 0.

For p ≠ 2 the Lᵖ norm of a normalized solution to the
Schrödinger equation is *not* in general preserved by the unitary
evolution. This is the content of the Norm Route: the only
exponent compatible with unitarity is p = 2.

**Proposition 11.1C** (Lᵖ non-conservation for p ≠ 2;
[1] §7.5 status note). *For a normalized 3D Gaussian
wavepacket ψ(x, t) solving the free Schrödinger
equation iħ ∂ₜ ψ = -(ħ²/2m)∇² ψ
with initial spatial width σ₀, the spatial width at large t
spreads as σ(t) ∼ ħ t/(2mσ₀). The Lᵖ norm
‖ψₜ‖ₚ = ( ∫ |ψₜ(x)|ᵖ d³ x )^(1/p) scales as*

‖ψₜ‖ₚ ∼ σ(t)^(3(2-p)/(2p)) ∼ t^(-3(p-2)/(2p)) (large t).

*Only the case p = 2 makes the exponent vanish, conserving the norm
exactly. For p > 2 the Lᵖ norm decays as a negative power of
t; for p < 2 the Lᵖ norm grows as a positive power of t.
Unitary evolution conserves the Lᵖ norm if and only if p = 2.*

*Proof.* Everything below descends from the physical expansion of x₄ at the velocity of light, in a spherically symmetric manner, from every event of M_G (dx₄/dt= ic). For the normalized 3D Gaussian wavepacket,

|ψ(x, t)|² = (2πσ(t)²)^(-3/2) exp(-(|x - x₀|²)/(2σ(t)²)),

so
|ψ(x, t)|ᵖ ∼ σ(t)^(-3p/2) exp(-p|x - x₀|²/(2σ(t)²))
up to overall constants. The integral
∫ |ψₜ|ᵖ d³ x scales by Gaussian quadrature as
σ(t)^(-3p/2) · σ(t)³ = σ(t)^(3(1 - p/2)) = σ(t)^(3(2 - p)/2).
Taking the 1/p root:
‖ψₜ‖ₚ ∼ σ(t)^(3(2 - p)/(2p)).

*Verification at p = 2:* exponent 3(2 - 2)/4 = 0, so
‖ψₜ‖₂ = const — the L² norm is conserved.

*Verification at p = 4:* exponent 3(2 - 4)/8 = -3/4, so
‖ψₜ‖₄ ∼ σ(t)^(-3/4) ∼ t^(-3/4) — the L⁴
norm decays. The Aaronson-style quartic density
|ψ|⁴ / ∑ⱼ |ψⱼ|⁴ would therefore not be conserved by
the Schrödinger evolution; this excludes |ψ|⁴ as a candidate
Born density (and rules out the Aaronson rank-4 quartic alternative
catalogued in §7.6 of [1]).

*Verification at p = 1:* exponent 3(2 - 1)/2 = 3/2, so
‖ψₜ‖₁ ∼ σ(t)^(3/2) ∼ t^(3/2) — the L¹
norm grows. The |ψ| candidate (with c = 1) would therefore not
be conserved either.

Only p = 2 vanishes the exponent. Since unitary evolution must
conserve the probability density's Lᵖ norm by probability
conservation, the exponent is forced to p = 2. ◻

##### Statement of the exponent-2 overdetermination {#sec:exponent-2-overdetermination-thm}

**Theorem 11.1D** (Exponent-2 overdetermination via Metric Route and
Norm Route; [1] §7.5 Theorem). *The exponent c = 2
in the Born rule P = |ψ|ᶜ is overdetermined by two
derivationally disjoint McGucken-internal routes:*

*(Metric Route, rank-2 metric route to bilinear density).*
dx₄/dt = ic → Lorentzian metric on M_(1,3)
(Theorem 9.2) → rank-2 character of
η_(μν) → natural bilinear pairing on
(ψ, ψ^*)
(Lemma 9.13) → P = |ψ|²
(Theorem 11.1 Step 5: the continuity-equation
divergence-decomposition argument identifies the quadratic
|ψ|² as the unique density with bilinear current).

*(Norm Route, rank-2 sesquilinear inner product route to L²-norm
structure, McGucken-internal).*
dx₄/dt = ic → Lorentzian metric on M_(1,3)
(Theorem 9.2) → rank-2 sesquilinear inner
product on 𝓗
(Lemma 9.13) → parallelogram identity
by direct two-line algebra
(Lemma 11.1A) →
L²-norm structure on the McGucken-derived 𝓗
(Theorem 9.20) → Lᵖ non-conservation
for p ≠ 2
(Proposition 11.1C) → p = 2 forced as the
unique exponent compatible with unitary evolution.

*Both routes start from dx₄/dt = ic; both end at
P = |ψ|²; they share only the upstream principle and the
rank-2 → sesquilinear chain
(Theorem 9.2 →
Lemma 9.13) before diverging into derivationally
disjoint downstream machinery: Metric Route through density-degree
counting, Norm Route through norm structure and conservation.*

*Proof.* Everything below descends from the physical expansion of x₄ at the velocity of light, in a spherically symmetric manner, from every event of M_G (dx₄/dt= ic).

**Metric Route.** By
Theorem 9.2 Step 3, the Lorentzian line element
ds² = η_(μν) dx^μ dx^ν has signature (-, +, +, +)
produced by the substitution dx₄ = ic dt (the differential form
of the McGucken Principle) into the four-dimensional Euclidean line
element. The metric η_(μν) is rank 2: it pairs two vectors
and produces a scalar, bilinearly in both arguments. By
Lemma 9.13, the natural pairing on amplitudes
lifted from this rank-2 metric is the sesquilinear pairing
(ψ, ψ^*) ↦ ψ^* ψ, bilinear in
(ψ, ψ^*). By Step 5 of
Theorem 11.1 (the divergence-decomposition
argument), the unique density bilinear in (ψ, ψ^*) with a
local current depending only on first derivatives and independent of
the external potential is |ψ|². Hence P = |ψ|² via the
Metric Route, with the exponent 2 forced by the rank-2 character of
the Minkowski metric.

**Norm Route.** By
Theorem 9.20, the McGucken-derived Hilbert
space 𝓗 ≅ L²(ℝ³, d³ x) is the Cauchy
completion of the space of complex-valued square-integrable amplitudes
on the spatial slice, with the L² norm supplied by the inner
product induced by the geometric overlap of forward and conjugate
x₄-expansions. By
Lemma 11.1A, the parallelogram
identity
‖x + y‖² + ‖x - y‖² = 2(‖x‖² + ‖y‖²) holds as a
direct two-line algebraic consequence of rank-2 sesquilinearity. The
L²-norm structure of 𝓗 is therefore internal to the
framework. By
Proposition 11.1C, only p = 2 makes the Lᵖ
norm conserved under the McGucken-derived unitary Schrödinger
evolution. Hence the probability density must have p = 2 exponent
to be conserved, and the Born rule is P = |ψ|² via the Norm
Route.

**Disjointness of routes.** The two routes share the upstream chain
dx₄/dt = ic →
Theorem 9.2 →
Lemma 9.13 (rank-2 metric and rank-2
sesquilinear pairing). They diverge after this point:

- *Metric Route* uses the continuity-equation
 divergence-decomposition argument
 (Theorem 11.1 Step 5) to identify the
 unique-density-with-bilinear-current — operating on density-degree
 counting.

- *Norm Route* uses the parallelogram identity
 (Lemma 11.1A) together with the
 Lᵖ-non-conservation analysis
 (Proposition 11.1C) — operating on norm
 structure and unitarity conservation.

The two arguments share no downstream machinery. The convergence on
P = |ψ|² is therefore a convergent-overdetermination instance
of the kind catalogued in
§1.10: the same conclusion
reached through two routes sharing only the upstream principle, with
no shared intermediate machinery. ◻

*Remark 11.1E* (Lesovik 2014 and Jordan–von Neumann 1935 as downstream
consistency checks, not upstream input). The orthodox tradition has
two functional-analytic arguments that force the Born exponent on a
*given* Hilbert space:

*Lesovik 2014* [27] derives the Born rule from unitarity by
the Lᵖ non-conservation argument
(Proposition 11.1C above is Lesovik's
result, with the McGucken dx₄/dt= ic framework derivation of the unitary
evolution itself in
Theorem 7.1 and the McGucken dx₄/dt= ic framework derivation of the
Hilbert space in
Theorem 9.20). Lesovik presupposes the
Hilbert space and the unitary group; the McGucken dx₄/dt = ic framework derives
both from dx₄/dt = ic.

*Jordan–von Neumann 1935* [26] characterises the
parallelogram identity on a *given* Lᵖ space; the result is a
theorem about which Banach spaces admit inner products, with the
Lᵖ spaces themselves taken as input. In the McGucken dx₄/dt= ic framework
the parallelogram identity is internal
(Lemma 11.1A); Jordan–von Neumann
is a downstream consistency check confirming that the
McGucken-derived parallelogram-identity structure is consistent with
general functional analysis on Lᵖ spaces.

*Gleason 1957* [35] derives the form of the Born rule on a
*given* Hilbert space with the trace structure on the lattice of
subspaces already encoding the inner-product-derived bilinearity. The
present textbook's
Remark 10.14 establishes that the McGucken
derivation of Born is Gleason-independent: the Born rule follows from
McGucken-Sphere SO(3)-Haar structure without invoking the
non-contextuality lattice theorem.

In the McGucken dx₄/dt= ic framework all three arguments — Lesovik, Jordan–von
Neumann, Gleason — operate one level downstream of the chain of theorems: the
Hilbert space, the inner product, and the unitary group are all
theorems of dx₄/dt = ic before any of these
functional-analytic arguments are applied. The orthodox tradition's
arguments are therefore reinforcing consistency checks on the
McGucken-derived structure, not selection principles
choosing the exponent.

#### The physical mechanism: Born rule as head-on x₄-collision of two McGucken Spheres {#sec:born-as-head-on-x4-collision}

The Algebraic Channel derivation (§ "Algebraic Channel derivation" above) and the
Geometric Channel derivation (§11.3) above establish P = |ψ|² as a
forced theorem of dx₄/dt= ic along two disjoint routes. The present section supplies the underlying *physical
mechanism*: a concrete two-Sphere collision picture for the Born event,
in which the complex conjugate ψ^* acquires explicit physical
meaning as the absorber's outgoing x₄-expansion as seen from the
emitter's frame, and the bilinear structure of P = ψ^*ψ has the
role of a head-on x₄-collision rate between two oppositely-oriented
Sphere expansions sharing a spatial intersection point. The result
strengthens both Channel readings by supplying the physical interlocutor
for the conjugate factor that the formal arguments leave at the level of
U(1)-equivariance (Geometric Channel Step B-4) or unitarity (Algebraic Channel clause
R3).

**Theorem 11.5** (Born rule as head-on x₄-collision of two McGucken
Spheres). *Let particle A at emission event E_A and particle B at
emission event E_B each generate a McGucken Sphere M⁺_(E_A)(t)
and M⁺_(E_B)(t') respectively, with each Sphere expanding at
dx₄/dt= +ic in the rest frame of its own source event
(Postulate 4.1 clauses (i), (ii), (v) applied at E_A and
at E_B). Let P be a spatial point at which both Spheres arrive at
the same coordinate time --- i.e.,
P ∈ M⁺_(E_A)(t) ∩ M⁺_(E_B)(t'). Then:*

1. **Antiparallel x₄-orientation at P.* Along the shared spatial
 geodesic through P on which the two Spheres meet head-on, the two
 outgoing x₄-directions are antiparallel:
 dx₄/dt|_A = +ic in A's rest frame at P, and
 dx₄/dt|_B = -ic as seen in A's rest frame at P
 (and conversely from B's rest frame). The complex conjugate
 ψ^* of the wavefunction has the role of the partner
 Sphere's outgoing x₄-expansion viewed from the observer's
 frame.*

2. **x₄-momenergy cancellation at P.* Each Sphere carries
 x₄-momenergy density per unit volume proportional to ic (the
 full four-velocity budget in the rest frame, by the four-velocity
 budget Lemma 4.2). At the head-on collision,
 the antiparallel x₄-momenergies cancel:
 p₄ⁿᵉᵗ(P) = 0.*

3. **Three-localization at P.* By conservation of total
 four-momenergy across the four dimensions of M_G, the
 x₄-momenergy cancelled in clause (C2) is transferred into the
 three spatial dimensions at P: both particles are knocked out of
 pure x₄-expansion and localized at the spatial event P. This
 is the detector click of measurement
 (Theorem 19.1, QM T19).*

4. **Bilinear collision rate.* The rate of head-on Sphere--Sphere
 collision events at P is bilinear in the two incoming Sphere
 amplitudes at P. For a single emitter Sphere with amplitude
 ψ(P, t) encountering a many-particle absorber (the detector,
 modelled as a dense ensemble of absorber Spheres each contributing
 an outgoing x₄-expansion in the absorber's rest frame), the
 collision rate at P reduces to
 
rate(P) ∝ ψ^*(P, t) ψ(P, t) = |ψ(P, t)|²,

 recovering the Born rule
 eq. (Born)
 as the rate of head-on x₄-collisions between the emitter's
 outgoing Sphere and the absorber's outgoing Sphere viewed from the
 emitter's frame.*

*Proof.* The proof has six steps establishing the head-on
collision mechanism and its agreement with the bilinear |ψ|²
density already derived in the Geometric Channel and Algebraic Channel routes above.

**Step 1: Two McGucken Spheres at dx₄/dt= +ic in their
respective rest frames.** By
Postulate 4.1 clause (i) (invariance: the rate
dx₄/dt= ic holds at every event with the same value ic
independent of matter content) and clause (v) (global validity:
dx₄/dt= ic holds at every event of M_G), both emission
events E_A and E_B source McGucken Spheres M⁺_(E_A)(t) and
M⁺_(E_B)(t') by Definition 4.9. Each Sphere expands at the rate
dx₄/dt= +ic in the rest frame of its own source event,
with the + sign forced by
Postulate 4.1 clause (iii) (monotonicity: the integral
curve of dx₄/dt= ic is strictly monotonically increasing
in t, fixing the forward orientation of x₄-advance at every
event). The two Spheres carry, respectively, the matter wavefunctions
ψ_A and ψ_B as amplitude profiles on their wavefronts
(Geometric Channel reading, Step B-3 of
§11.3); in the rest frame of each source event,
the wavefunction's phase advances at the Compton angular frequency
ω_C = mc²/ħ along x₄ by
Theorem 5.1
(rest-mass phase).

**Step 2: Antiparallel x₄-orientation at the head-on collision
(clause C1).** Suppose P is a spatial point at which both Spheres
arrive at the same coordinate time, lying on a shared spatial geodesic
along which the two Spheres meet head-on. Let n̂ be the unit
spatial direction from E_A's spatial projection toward P; then
-n̂ is the unit direction from E_B's spatial projection toward
P (since the two Spheres meet head-on at P, their spatial sources
lie on opposite sides of P along the geodesic). In the rest frame of
A, the outgoing x₄-direction at P from Sphere A is +ic
along A's worldline tangent at P (forward x₄-advance, Step 1).
In the same rest frame, Sphere B's outgoing x₄-direction at P
is along B's worldline tangent at P, which (with B's spatial
projection on the opposite side of P from A) points in the -n̂
spatial direction; combined with B's forward x₄-advance in B's
own rest frame, the x₄-component of B's outgoing worldline at P
*as seen in A's rest frame* has the opposite sign convention relative
to A's own forward direction at P. Formally: the relative
x₄-orientation between the two Spheres at P is antiparallel,
dx₄/dt|_A(P) = +ic and dx₄/dt|_B(P) = -ic
*as both are reckoned in A's rest frame*. By the frame-relational
symmetry of the construction, from B's rest frame the situation
reverses: dx₄/dt|_B(P) = +ic and
dx₄/dt|_A(P) = -ic as both are reckoned in B's rest
frame. The complex conjugate of the wavefunction (the sign-reversal
i → -i in the perpendicularity marker,
Remark 4.3) has the reading of the
partner Sphere's outgoing x₄-expansion viewed from the observer's
frame, with the role of a formal algebraic operation on complex
amplitudes replaced by the role of a physical antiparallel
x₄-orientation between two Spheres meeting head-on at P. This
establishes clause (C1).

**Step 3: x₄-momenergy cancellation at P (clause C2).** By
Lemma 4.2 (the four-velocity budget at rest:
a particle at spatial rest directs its entire four-velocity budget into
x₄-advance at rate c), each particle's rest-frame four-momenergy
is concentrated in the x₄-component:

p₄ = mc · (dx₄/dt)/|dx₄/dt| = mc · i = imc (rest frame, +ic orientation),

with the imaginary unit i marking the perpendicularity of x₄ to
the spatial three (Theorem 9.21, case 1: the McGucken-Principle i as the
perpendicularity marker of x₄). At the head-on collision event P,
the two Spheres' x₄-momenergies are antiparallel by Step 2:
p₄^A(P) = +im_A c in A's frame and p₄^B(P) = -im_B c in A's
frame (with the sign flip from the antiparallel orientation, and
m_A, m_B the respective rest masses). The net x₄-momenergy at the
collision event is

p₄ⁿᵉᵗ(P) = p₄^A(P) + p₄^B(P) = +i m_A c - i m_B c = i(m_A - m_B)c,

which for identical species (m_A = m_B) vanishes exactly:
p₄ⁿᵉᵗ(P) = 0. For non-identical species, the cancellation
is partial; the relevant content of the head-on collision is that the
x₄-momenergies oppose each other and net to a value strictly
smaller in magnitude than the sum of magnitudes, with the loss of
x₄-momenergy then transferred to the spatial three by clause (C3)
below. This establishes clause (C2).

**Step 4: Three-localization at P (clause C3).** By conservation of
total four-momenergy across the four dimensions of M_G (Noether's
theorem applied to translation invariance of dx₄/dt= ic at
every event, the algebraic symmetry of the Algebraic Channel axiom QA1), the
four-momenergy lost from the x₄-component at the head-on collision
(Step 3) must appear in the three spatial components p₁, p₂, p₃ at
the same event P. The mechanism: prior to the collision, each
particle's four-velocity budget was concentrated in x₄-advance
(pure rest-frame propagation,
Lemma 4.2); at the collision event, with
x₄-momenergy cancelled, the conserved total four-momenergy is
redistributed into spatial momenergy with a definite spatial position
P. Both particles are thereby knocked out of pure x₄-expansion
and localized at the spatial event P. The transfer of momenergy from
x₄ into the spatial three has the geometry of a *Wick
rotation of the particle out of x₄ into the spatial slice*: the
perpendicularity marker i that distinguished x₄ from the spatial
three in the pre-collision wavefunction
(Theorem 9.10, complex amplitudes from
x₄-perpendicularity) is removed at the collision event, with the
particle's complex-amplitude wavefunction collapsing to a real spatial
position via the head-on cancellation of the two Spheres' i-marked
x₄-expansions. This is the detector click of measurement: collapse
has the reading of a head-on x₄-collision between the
particle's outgoing Sphere and the absorber's outgoing Sphere, with the
role of an independently-postulated measurement axiom (Process 1 of von
Neumann [36]) replaced by the role of a derived theorem of
dx₄/dt= ic at the level of the two-Sphere intersection
event. This establishes clause (C3) and supplies the head-on-collision
picture for Theorem 19.1 (QM T19, measurement) and
Corollary 10.1 (the channel
asymmetry as the source of the orthodox-tradition measurement
problem).

**Step 5: Bilinear collision rate and reduction to |ψ|² (clause
C4).** The rate of head-on Sphere--Sphere collision events at the
spatial point P is, by general probabilistic kinematics on the
wavefront, the product of the two incoming Sphere amplitudes at P. In
the standard collision-theory derivation (cross-section formalism,
Reed--Simon [33] §XI.6 for the Lippmann--Schwinger
framework; Jackson *Classical Electrodynamics* §13.10 for the bilinear
cross-section structure), the rate of collision events at a target point
P in a beam of incoming particles is bilinear in the beam amplitudes
(incoming ψ_(beam)) and the target amplitudes (outgoing
φ_(target)):

rate(P) ∝ φ_(target)^*(P) ψ_(beam)(P).

In the present McGucken-Sphere head-on collision picture (Steps 1--4),
the bilinearity arises from the fact that a collision event
at P requires both Spheres to arrive at P with non-zero amplitude,
with the amplitude for joint arrival being the product of the individual
amplitudes
(Theorem 17.7, intersecting-Spheres
transfer: the joint amplitude at the intersection event is the product
of the individual Sphere amplitudes at that event).

For the canonical single-particle Born event (one emitter Sphere with
amplitude ψ, encountering a many-particle absorber acting as the
detector), the absorber is modelled as a dense ensemble of absorber
Spheres in their own rest frames. In the emitter's frame, each absorber
Sphere appears as an outgoing x₄-expansion at -ic (by Step 2,
antiparallel orientation). The ensemble-averaged absorber amplitude at
the emitter's spatial point P has the reading of the
conjugate of the emitter's own amplitude evaluated at P:

⟨φ_(absorber)(P)⟩_(ensemble) = ψ^*(P, t),

since (i) the absorber ensemble is dense and uniform around the emitter
(the detector is a macroscopic, homogeneous environment), (ii) each
absorber Sphere's outgoing x₄-expansion appears as -ic in the
emitter's frame and thus contributes the conjugate phase, and (iii) the
macroscopic-detector limit makes the ensemble-averaged absorber
amplitude at P proportional to the local emitter amplitude at P (the
absorber's outgoing Sphere amplitude at P tracks the emitter's
outgoing Sphere amplitude at P, since both Spheres meet at P and the
absorber's contribution from a small neighborhood around P is
dominated by the local matter density times the local emitter
amplitude). Substituting into the bilinear collision rate:

rate(P) ∝ ψ^*(P, t) ψ(P, t) = |ψ(P, t)|²,

which is the Born rule eq. (Born). This establishes clause (C4).

**Step 6: McGucken anchoring and agreement with Geometric and Algebraic Channels.** The
head-on x₄-collision mechanism descends from
dx₄/dt= ic
(Postulate 4.1) at three distinct levels: (i) the
antiparallel x₄-orientation at the collision event (Step 2) is what
the perpendicularity marker i expresses in
dx₄/dt= ic (clause (i) and
Theorem 9.21), supplied with the role of a frame-relational
orientation between two Spheres; (ii) the x₄-momenergy cancellation
(Step 3) is the consequence of the four-velocity budget structure of the
rest-frame wavefunction
(Lemma 4.2, descending from clause (ii)
spherical symmetry and the integrated x₄ = ict of
Remark 4.3); (iii) the three-localization (Step
4) is the conservation law of clauses (i)+(v) applied to the
global translation invariance of dx₄/dt= ic. The
bilinearity of the collision rate (Step 5) reduces to the bilinear
density ψ^*ψ in the single-particle-with-many-absorber limit,
agreeing with the Algebraic Channel derivation (Step 5 of the master proof: the
divergence-decomposition argument pinning c = 2) and the Geometric Channel
derivation (Step B-4 of §11.3: U(1)-equivariance forcing the
polynomial density to be ρ ∝ |ψ|²). The three derivations
are derivationally disjoint and pointwise agree on the Born density
P(x) = |ψ(x)|². □

**Corollary 11.6** (The complex conjugate ψ^* as the absorber's
outgoing x₄-expansion). *Under
Theorem 11.5, the complex conjugate ψ^* of
the wavefunction has the explicit physics of the absorber
Sphere's outgoing x₄-expansion as seen from the emitter's rest
frame. The Hilbert-space inner-product structure
⟨φ, ψ⟩ = ∫ φ^*ψ d³ x (Theorem 5.3 of
[1]) is the integrated form of the head-on
x₄-collision rate between the bra-Sphere and the ket-Sphere, with
the integrand φ^*ψ at each spatial point x being the local
collision rate at x between the two Spheres meeting head-on. The Born
probability density ρ(x) = (ψ^*ψ)(x) = |ψ(x)|² is the
diagonal of this overlap with bra = ket: the collision rate between
the emitter Sphere and its many-particle-absorber image (the conjugate
Sphere) at the same spatial point x.*

*Proof.* Everything below descends from the physical expansion of x₄ at the velocity of light, in a spherically symmetric manner, from every event of M_G (dx₄/dt= ic). By Step 2 of
Theorem 11.5, the absorber Sphere appears, from
the emitter's rest frame, as an outgoing x₄-expansion at -ic
rather than +ic --- the sign reversal of the perpendicularity marker
i → -i, which is by definition the complex-conjugation operation on
the wavefunction's amplitude (the wavefunction's x₄-phase has the
form exp(i x₄-phase) for +ic orientation, and
exp(-i x₄-phase) for -ic orientation, which is the
complex conjugate of the former). Therefore the absorber Sphere's
amplitude at P has the reading of ψ^*(P) in the
emitter's frame. By Step 5 of
Theorem 11.5, the collision rate at P is
bilinear in the two amplitudes:
rate(P) ∝ ψ^*(P)ψ(P). Integrating over the spatial
slice gives the inner-product structure
⟨ψ, ψ⟩ = ∫ |ψ|² d³ x, identifying the
Hilbert-space inner product as the integrated head-on x₄-collision
rate between bra-Sphere and ket-Sphere. □

*Remark 11.7* (Born event as a particle-scale Wick rotation;
large-ensemble emergence of thermodynamics). Each head-on
x₄-collision at a spatial event P has the reading of a
Wick rotation of the colliding particles out of x₄ and into the
spatial three: the perpendicularity marker i that distinguished
x₄ from the spatial three in the pre-collision wavefunction
(Theorem 9.10, complex amplitudes from
x₄-perpendicularity) is removed at the collision event, with the
post-collision particles localized at P in the real spatial three.
This is the same content as the apparatus-performed Wick
rotation in the measurement chapter
(Corollary 10.1); the Born
collision picture supplies the particle-scale mechanism behind the
apparatus-scale Wick rotation.

In a large ensemble of N ∼ 10²³ particles, the head-on collision
rate per unit volume is on the order of ∼ N² σ v / V for
cross-section σ and mean relative velocity v in a volume V
--- typically ∼ 10¹⁰ collisions per second per molecule under
standard laboratory conditions, totalling ∼ 10³³ Born events per
second in a macroscopic gas. Each Born event removes a small slice of
x₄-amplitude from the system's wavefunction by rotating two
particles into 3-localization. The accumulation of these collisional
Wick rotations over a macroscopic ensemble has the reading of
the emergence of thermodynamic behaviour from quantum mechanics: the
complex character of the quantum-mechanical wavefunction is
progressively reduced to real spatial-probability statistics by the
trillion-fold Wick rotation enacted by the collisions, with the role of
an independent passage from QM to thermodynamics replaced by the role of
a derived consequence of accumulated Born events at the
particle-collision level. This is the McGucken-Sphere mechanism behind
the well-known formal connection: under Wick rotation t → iτ, the
Schrödinger equation iħ∂ₜψ = Ĥψ becomes the
heat equation ħ∂_τψ = -Ĥψ (the diffusion
equation governing thermodynamic relaxation), with QM and statistical
mechanics interconverting through the same Wick rotation that the Born
collision performs at the particle level. The strict Second Law of
thermodynamics
(Theorem 22.4 of
Chapter 22) has the reading of the
cumulative thermodynamic shadow of the trillions of head-on
x₄-collisions per second that the Born mechanism implements in any
macroscopic gas, descending ultimately from the forward orientation of
dx₄/dt= +ic at every event of M_G
(Postulate 4.1 clause (iii), monotonicity).

*Remark 11.8* (Boost and measurement as two readings of
x₄-rotation). A parallel between special relativity and
quantum mechanics emerges from the head-on collision mechanism. In
special relativity, a Lorentz boost has the reading of a
hyperbolic rotation in the (x₄, xⱼ) plane: the boosted observer's
x₄-direction acquires a non-zero component along the spatial
direction xⱼ, with the boost magnitude controlled by the rapidity
η via coshη = γ, sinhη = βγ
(Theorem 9.2 of
Chapter 9, Lorentzian arena from
dx₄/dt= ic). In quantum mechanics, a Born measurement
event has the reading of a head-on x₄-collision at a
spatial point: the particle's outgoing x₄-expansion is rotated out
of x₄ into the spatial three at the collision event, with the
rotation magnitude controlled by the relative angle between the
colliding Spheres' x₄-orientations (head-on, π, complete
cancellation; oblique, partial cancellation; parallel, no cancellation).
Both the relativistic boost and the quantum measurement have the
reading of rotations involving the x₄-direction, with
the role of two distinct rotational structures of different physical
theories replaced by the role of two channel-projections of the single
dx₄/dt= ic: the Algebraic Channel reading (hyperbolic boost on the
algebraic-symmetry side) supplies the Lorentzian metric of relativity,
and the Geometric Channel reading (head-on collision on the
geometric-propagation side) supplies the Born rule of quantum
mechanics. Both rotations affect the motion of the system: a boost
changes the four-velocity components; a collision changes the
four-momentum components by transferring x₄-momenergy into the
spatial three. The shared content has the reading of a single
dx₄/dt= ic-generated geometric primitive, with the
boost-vs-measurement contrast having the role of two channel-projections
of one underlying x₄-rotation phenomenon.

*Remark 11.9* (Compatibility with no-signaling). The head-on
x₄-collision mechanism is consistent with the McGucken No-Signaling
Theorem
(Theorem 17.32 of
Chapter 17). The collision event at P is localised at
the apparatus's spatial position: no information about the collision is
transmitted superluminally across the spatial three. The Born-rule
statistics at P depend only on the local amplitudes
ψ(P), ψ^*(P) at P, with the role of a faster-than-light
information channel replaced by the role of local bilinear products of
amplitudes that arrived at P along null worldlines from their
respective source events. The non-locality of quantum mechanics enters
only at the level of the emitter Sphere's global identity (the
wavefunction ψ is non-zero at multiple spatial points, all sharing
the same x₄-coordinate by sphere-surface x₄-locality of
Theorem 11.10), with the local collision
event preserving signal-locality through the bilinearity of the rate at
each spatial point separately.

#### Complex conjugation as McGucken-Sphere PT-symmetry through the source event {#sec:born-as-pt-symmetry-through-source}

The head-on x₄-collision mechanism of
§11.4 supplies the Born rule's
bilinear structure at detection events through two distinct McGucken
Spheres meeting at the registration point. The present section supplies
a complementary geometric reading specific to free propagation: the
wavefunction's complex-conjugation symmetry, and therefore the Born
rule's bilinearity in (ψ, ψ^*), has a geometric source in the
PT-symmetry of a single McGucken Sphere through its source event. The
reading does not require an external absorber: the conjugate factor
ψ^* is supplied by the McGucken Sphere's natural reflection
symmetry through E, with the geometric realization being the advanced
sector of the kernel that occupies the past light cone of E.

**Theorem 11.10** (Complex conjugation as McGucken-Sphere PT-symmetry
through the source event). *Let E ∈ M_(1,3) be an emission event and
let K_E: M_(1,3) → ℂ be the McGucken-Sphere kernel
propagating outward from E by the spherical-symmetry-and-velocity-c
expansion of dx₄/dt= ic
(Postulate 4.1,
Remark 4.2). Define the
PT-reflection through E by

PT_E : M_(1,3) → M_(1,3), (x, t) longmapsto (2x_E - x, 2t_E - t),

equivalently (x - x_E, t - t_E) longmapsto -(x - x_E, t - t_E).
Then:*

1. *PT_E is the unique non-trivial spacetime symmetry of
 M_(1,3) fixing E that preserves both the spherical isotropy of
 the McGucken-Sphere expansion (Postulate clause (ii)) and the
 magnitude |dx₄/dt| = c of the x₄-advance (Postulate clause
 (i)), while reversing the direction of x₄-advance through E.*

2. *For any plane-wave component
 ψₖ(x, t) = exp(ik·(x - x_E) - iω(k)(t - t_E))
 of the McGucken-Sphere kernel, with k the spatial wavevector and
 ω(k) the dispersion relation appropriate to the kernel
 (relativistic Klein--Gordon, non-relativistic Schrödinger, or
 Dirac), the PT_E-reflected value equals the
 complex-conjugate value exactly:
 
ψₖ(PT_E· (x, t)) = ψₖ^*(x, t),

 holding identically on M_(1,3) without any auxiliary assumption.*

3. *The McGucken-Sphere kernel K_E, being a real-coefficient
 superposition of plane-wave components (the retarded Green's
 function of the dispersion relation in the standard normalization),
 satisfies the PT-symmetry relation at the kernel level:
 
K_E(PT_E· (x, t)) = K_E^*(x, t),

 holding identically on M_(1,3). Equivalently, the kernel's
 retarded sector K_E⁽ʳᵉᵗ⁾ on the forward light cone of
 E and the advanced sector K_E⁽ᵃᵈᵛ⁾ on the past light
 cone of E are related by
 K_E⁽ᵃᵈᵛ⁾(PT_E· event) = [K_E⁽ʳᵉᵗ⁾(event)]^*.*

4. *The Born density at any spatial-slice event (P, t) for a free
 particle propagating from E has the geometric reading
 
|K_E(P, t)|² = K_E(P, t) · K_E^*(P, t) = K_E(P, t) · K_E(PT_E· (P, t)),

 with the right-hand form making the geometry explicit: the
 Born density at (P, t) is the product of the kernel's amplitude at
 (P, t) with its amplitude at the PT_E-reflected event
 (2x_E - x_P, 2t_E - t). The bilinearity of the Born density in
 (K_E, K_E^*) has the role of the algebraic shadow of the McGucken
 Sphere's PT-symmetry through the source event.*

5. *For a free particle propagating from a known source event E with
 no absorber present, the conjugate factor K_E^* in the Born
 density is supplied by the McGucken Sphere's own PT-symmetry through
 E, with the geometric realization being the advanced sector of the
 kernel occupying the past light cone of E. This reading
 complements
 Theorem 11.5 (the head-on x₄-collision
 reading, which applies at detection events where an absorber's
 sphere arrives at P) by supplying the free-propagation regime
 where no absorber is present.*

*Proof.* Everything below descends from the physical expansion of x₄ at the velocity of light, in a spherically symmetric manner, from every event of M_G (dx₄/dt= ic). We verify each clause in turn.

**Step 1 (Clause (i)): uniqueness of PT_E as the
spherical-isotropy-and-velocity-preserving symmetry through E.**

The spacetime symmetries of M_(1,3) fixing E form the Lorentz group
with origin at E, equipped with the discrete extensions P (spatial
parity, (x, t) ↦ (2x_E - x, t)), T (time reversal,
(x, t) ↦ (x, 2t_E - t)), and their composition
PT = P · T. Among the discrete extensions, only those
that reverse the direction of x₄-advance through E are
non-trivial candidates for the symmetry preserving |dx₄/dt| = c while
reversing direction. There are three such candidates: P alone, T
alone, and PT.

Now P alone reverses only the spatial direction of x₄-advance: at
events on the forward light cone of E (where the x₄-advance
points in +n̂_P direction in the spatial slice), P produces
events on the forward light cone of E at the spatially-inverted
direction -n̂_P. The temporal direction +(t - t_E) is preserved,
so P does not reverse the x₄-advance's temporal orientation. The
McGucken-Sphere structure under P alone is preserved but with the
spatial orientation flipped; the temporal direction of the wavefront's
advance is unchanged. This is a symmetry of the spatial-slice structure
but does not reverse the x₄-advance.

Similarly, T alone reverses only the temporal direction of
x₄-advance: at events on the forward light cone of E, T
produces events on the past light cone of E at the same spatial
direction +n̂_P. The spatial orientation is preserved; the
temporal orientation is flipped. The wavefront's spatial structure under
T alone is preserved but with the temporal direction reversed.

Only PT_E = P · T reverses both directions
simultaneously: events on the forward light cone of E in direction
+n̂_P are mapped to events on the past light cone of E in
direction -n̂_P. The wavefront structure is preserved with both
spatial orientation and temporal orientation flipped. By
Postulate 4.1 clause (ii) (the spherical isotropy of the
expansion at every event of M_G), the McGucken-Sphere structure from
E is invariant under the joint reflection PT_E: a
spherically symmetric wavefront emitted at E has spherical symmetry of
its full forward-and-past-light-cone structure through E, with the
PT-reflection through E exchanging forward-and-past components while
preserving the spherical symmetry.

The uniqueness claim: among the discrete extensions, only
PT_E reverses both spatial and temporal directions of
x₄-advance while preserving the spherical isotropy at E. ✓

**Step 2 (Clause (ii)): the PT-symmetry equals complex conjugation for
plane-wave components.**

Let
ψₖ(x, t) = exp(ik·(x - x_E) - iω(k)(t - t_E)).
Compute the value at the PT_E-reflected event
PT_E· (x, t) = (2x_E - x, 2t_E - t): 
beginaligned
ψₖ(PT_E· (x, t))
&= exp(ik·((2x_E - x) - x_E) - iω(k)((2t_E - t) - t_E)) 
&= exp(ik·(x_E - x) - iω(k)(t_E - t)) 
&= exp(-ik·(x - x_E) + iω(k)(t - t_E)) 
&= exp(-[ik·(x - x_E) - iω(k)(t - t_E)]) 
&= [exp(ik·(x - x_E) - iω(k)(t - t_E))]^* 
&= ψₖ^*(x, t).
endaligned
 The identity holds for every plane-wave component
without auxiliary assumption: no time-symmetry of the state, no
real-coefficient restriction, no choice of dispersion relation. The
chain of substitutions uses only that the argument (x - x_E, t - t_E)
enters linearly in the exponent and that PT_E reverses both
components by definition. ✓

**Step 3 (Clauses (iii)--(v)): extension to the kernel and the
Born-density reading.**

The McGucken-Sphere retarded kernel K_E⁽ʳᵉᵗ⁾ is the
Green's function of the wave equation
(∂ₜ² - c²∇² + m² c⁴ / ħ²) K = 0
(Klein--Gordon case; similar for Schrödinger and Dirac with
corresponding dispersion) supported on the closed forward light cone of
E, normalized to produce outward propagation from E at velocity c.
By the standard Fourier representation,

K_E⁽ʳᵉᵗ⁾(x, t) = ∫ (d³ k)/((2π)³) G(k) exp(ik·(x - x_E) - iω(k)(t - t_E)) θ(t - t_E),

with G(k) a real-valued amplitude (e.g.,
G(k) = 1/(2ω(k)) for the Klein--Gordon kernel) determined
by the dispersion relation ω(k). The real-valuedness of G(k) is
a property of the Green's function in the standard normalization: the
kernel's Fourier-space amplitude is real (the only complex structure in
the kernel is in the plane-wave exponentials themselves).

Applying PT_E to the kernel's argument and invoking Step 2
component-wise: 
beginaligned
K_E⁽ʳᵉᵗ⁾(PT_E· (x, t))
&= ∫ (d³ k)/((2π)³) G(k) ψₖ(PT_E· (x, t)) θ(2t_E - t - t_E) 
&= ∫ (d³ k)/((2π)³) G(k) ψₖ^*(x, t) θ(t_E - t) 
&= [K_E⁽ʳᵉᵗ⁾(x, t)]^*Bigg|_(θ(t - t_E) → θ(t_E - t)) 
&= K_E⁽ᵃᵈᵛ⁾(x, t)^*Bigg|_(kernel form).
endaligned
 The step from line 2 to line 3 uses that G(k) is real
(G(k) = G^*(k)), so the conjugation of the integrand affects only the
plane-wave exponential, with the result being the complex conjugate of
the kernel's value at (x, t) --- except for the support: the retarded
kernel is supported on t > t_E (forward light cone), while
K_E⁽ʳᵉᵗ⁾(PT_E· (x, t)) is supported on
t < t_E (past light cone). The latter is exactly the support of the
advanced kernel K_E⁽ᵃᵈᵛ⁾, which satisfies
K_E⁽ᵃᵈᵛ⁾(x, t) = [K_E⁽ʳᵉᵗ⁾(x, t)]^* on its
support by the standard retarded-advanced conjugation symmetry of
Green's functions.

Combining the support and conjugation observations: the PT-symmetry
through E exchanges the retarded and advanced sectors of the kernel,
and on either sector it acts by complex conjugation. Identifying K_E
with the full kernel (sum of retarded and advanced sectors, or either
one extended by the conjugation to the other), Clause (iii)
holds: 
K_E(PT_E· (x, t)) = K_E^*(x, t).


Clause (iv) then follows by substitution into the Born density: for a
spatial-slice event (P, t) on the forward light cone of E,

|K_E(P, t)|² = K_E(P, t) · K_E^*(P, t) = K_E(P, t) · K_E(PT_E· (P, t)),

with the right-hand expression evaluating the kernel at the
PT_E-reflected event (2x_E - x_P, 2t_E - t) on the past
light cone of E. The bilinearity of the Born density in (K_E, K_E^*)
has the algebraic-shadow role of the McGucken Sphere's PT-symmetry
through E.

Clause (v) is the physical-interpretation consequence: for a free
particle (no absorber present), the conjugate factor in the Born density
is supplied by the McGucken Sphere's own PT-symmetry through E via the
advanced sector. The reading is consistent with
Theorem 11.5 (head-on x₄-collision at
detection events): the transition from free propagation to detection
corresponds to the appearance of the absorber's sphere taking over as
the physical source of the conjugate factor, with the kernel-level
PT-symmetry transitioning smoothly into the two-sphere collision reading
as the absorber becomes present at the registration point. □

*Remark 11.11* (Three complementary geometric readings of the Born
rule). The Born rule's bilinearity in (ψ, ψ^*) now has three distinct geometric readings within the McGucken dx₄/dt= ic framework, each
illuminating a different physical context with the algebraic result
P = |ψ|² identical across all three:

- *Chain of theorems-overlap reading*
 (Lemma 9.13, the rank-2 Minkowski metric
 of [1] §7.4): the bilinearity of the inner
 product on 𝓗 is inherited from the rank-2 character of
 the Lorentzian metric on M_(1,3), which itself comes from
 (ic)² = -c² in x₄= ict. This is the most abstract reading
 and supplies the algebraic origin of the bilinearity at the chain of theorems
 level.

- *Two-sphere head-on-collision reading*
 (Theorem 11.5, [1] §7.7): the
 conjugate factor ψ^* is the absorber's outgoing McGucken Sphere
 viewed from the emitter's frame, with the bilinear product
 ψ^*ψ at the detection event P being the head-on
 x₄-collision rate of two physically distinct spheres. This is
 the detection-event reading and supplies the concrete physical
 mechanism for the Born event at measurement.

- *PT-symmetry-through-source reading*
 (Theorem 11.10, the present
 section): the conjugate factor ψ^* at the kernel level is the
 McGucken Sphere's PT-reflection through its source event E, with
 the bilinear product ψ^*ψ at any spatial-slice event being
 the product of the kernel's amplitude at that event with its
 amplitude at the PT-reflected event on the past light cone of E.
 This is the free-propagation reading and supplies the intrinsic
 geometry of the conjugate factor in the absence of an
 absorber.

The three readings are complementary, each illuminating a different
physical situation. The overlap reading supplies the algebraic
origin of bilinearity (rank-2 metric forcing the structure); the
two-sphere reading supplies the detection-event mechanism (two spheres,
one collision); the PT-symmetry reading supplies the free-propagation
intrinsic content (one sphere, intrinsic reflection symmetry). The
transitions between physical regimes connect smoothly: a free particle
propagating from E has its Born density supplied by the PT-symmetry
through E; the moment a detector interacts at P, the absorber's
sphere takes over as the source of the conjugate factor, and the
two-sphere reading applies, with the algebraic result |ψ(P)|²
identical in both regimes.

*Remark 11.12* (Spinor refinement: the Wigner antiunitary T and the
σ_y factor). For spin-1/2 wavefunctions, the standard
Wigner time-reversal operator acts antiunitarily as
T·ψ = -iσ_y ψ^* (with the global sign and σ_y
factor fixing the spinor-internal phase convention; one has T² = -1
by Kramers' theorem). The McGucken-Sphere PT-symmetry through E for a
spinor wavefunction therefore carries the spin-internal σ_y
factor:

ψₛₚᵢₙₒᵣ(PT_E· event) = -iσ_y ψₛₚᵢₙₒᵣ^*(event)

on the kernel level, with the -iσ_y factor accounting for the
spinor's transformation under the spatial parity component of
PT_E (which exchanges left- and right-handed spinor
components via the σ_y factor) and under the time-reversal
component (which complex-conjugates the spinor's phase). The T² = -1
Kramers signature is the algebraic record of the spin-1/2
4π-closure (instance (N4) of
Theorem 12.12 in
Chapter 12): the spinor's PT-symmetry has
Wigner-antiunitary structure, requiring a full 4π for closure of the
doubled PT-rotation. The consistency with the
physics reading
(Remark 4.2 of
Chapter 4, "the spinor lives on a wavefront that
already has the Compton frequency"): the spinor's internal σ_y
structure under PT-symmetry through E carries the same half-quantum
content as the spinor's external 4π-closure under spatial rotations,
both being signatures of the McGucken-Sphere half-quantum of
x₄-rotation that the spinor carries.

*Remark 11.13* (Physical-state connection: T = PT_E joins the
framework's unifications). The McGucken Principle's physics
(Remark 4.2 of
Chapter 4) is that x₄ advances as a
spherically-symmetric wavefront at c from every event of M_G. A
spherically-symmetric wavefront emitted at E admits a unique natural
reflection symmetry through E, which in 4D is precisely PT-symmetry.
Theorem 11.10 reads off the
algebra of this natural geometric symmetry: the kernel
satisfies K_E(PT_E· event) = K_E^*(event)
identically, with the Born density's bilinearity in (K_E, K_E^*) being
the algebraic shadow of the wavefront's PT-symmetry through E. The
dynamics were in the premise
(Remark 4.2): the wavefront's
natural reflection symmetry through E generates complex conjugation as
an intrinsic geometry of the McGucken-Sphere kernel.

The identification T_𝓗 = PT_E --- the
Wigner antiunitary time-reversal operator T acting on the Hilbert
space equals the spacetime PT-reflection through the source event E
--- joins the unifications already established in this
textbook. Each of the following identifications gives a Hilbert-space
algebraic operation a geometric realization at the spacetime level:

- The imaginary unit i in the canonical commutator
 [q̂, p̂] = iħ has its geometric realization as the
 perpendicularity marker for x₄'s orthogonality to x₁ x₂ x₃
 (Theorem 9.10).

- The action quantum ħ has its geometric realization as the
 action per radian of the Compton-frequency oscillation of x₄-advance
 (Theorem 9.35).

- The complex-conjugation operator ψ↦ψ^* (equivalently,
 the Wigner antiunitary T) has its geometric realization as the
 McGucken-Sphere PT-reflection through the source event
 (Theorem 11.10 above).

Three Hilbert-space algebraic operations --- multiplication by i,
multiplication by ħ, and complex conjugation --- all have
geometric realizations at the McGucken-spacetime level, all descending
from the physics of dx₄/dt= ic as a
spherically-symmetric wavefront with wavelength, frequency, phase, and
action. The algebra of quantum mechanics has the role of the
function-space rendering of the active geometry of the McGucken
Principle, with each algebraic operation acquiring its geometric meaning
from the principle's physics.

#### Disjointness audit {#disjointness-audit-9}

**Geometric Channel:** dx₄/dt= ic, McGucken Sphere wavefront,
SO(3) rotation group, Haar measure, U(1)-bundle structure, squared
modulus as unique equivariant density.

**Algebraic Channel:** dx₄/dt= ic, four requirements
(real-valuedness, non-negativity, phase invariance, smoothness), Cauchy
functional equation, unit normalization.

**Intersection:** {(McP), P = |ψ|²}. Cauchy functional
equation does *not* appear in the Geometric Channel. Haar measure does *not* appear
in the Algebraic Channel. *Disjointness verified.*

#### Independence of the derivation from the Hilbert-space lattice tradition {#sec:born-independent-of-gleason}

The Algebraic Channel derivation (§ "Algebraic Channel derivation" above), the Geometric Channel
derivation (§11.3 above), and the head-on x₄-collision
mechanism
(§11.4) together establish
P = |ψ|² as a forced theorem of dx₄/dt= ic through
three derivationally disjoint routes. None of the three routes presupposes
a Hilbert space, a non-contextuality axiom, a measure-theoretic argument
on the lattice of closed subspaces, a frequentist limit, a
decision-theoretic axiom, or an envariance, equivariance, or
branch-counting hypothesis. The four requirements R1--R4 of
the Algebraic Channel derivation descend directly from the principle: R1 reality
and R2 non-negativity from the operational character of probability as
the frequency of detection events on the spatial slice; R3 phase
invariance from the universal-rate clause of
Postulate 4.1; and R4 bilinearity in (ψ, ψ^*) from
the rank-2 character of the Minkowski metric induced by x₄= ict,
with the exponent 2 supplied directly by the rank-2 character without
recourse to any inside-Hilbert-space machinery.

This places the derivation upstream of the entire twentieth-century
tradition of Hilbert-space-internal Born-rule arguments, of which
Gleason's 1957 measure-theoretic argument [35] is the
canonical and most rigorous instance, and of which Deutsch--Wallace,
Zurek, and Farhi--Goldstone--Gutmann are the canonical
decision-theoretic, envariance, and frequentist successors. Each program
in that tradition presupposes the arena (a complex separable Hilbert
space) and imports one supplementary axiom (non-contextuality,
rationality, envariance, frequentist limit) sufficient to extract the
algebraic form of the rule from inside the arena. The McGucken
derivation supplies the arena as a downstream theorem
(Theorem 9.17 of
Chapter 9, with the deeper identification 𝓗= L²(M_(1,3), η_(μν)) of
Theorem 9.31) and supplies the exponent
2 directly from the rank-2 character of the Minkowski metric, with no
supplementary axiom required.

*Remark 11.14* (Diagnostic: Gleason 1957 as a downstream
functional-analytic argument; [1] §7.1.2, §7.5, §10.6).
Gleason's theorem [35] establishes that every countably
additive probability measure on the lattice of closed subspaces of a
separable complex Hilbert space of dimension ≥ 3 takes the trace
form μ(P) = Tr(ρ P) for some density operator ρ.
The theorem operates entirely inside an already-postulated Hilbert
space, with three black-box inputs: the lattice structure (closed
subspaces of 𝓗); the complex field (the lattice lives on
ℂ, not on ℝ or ℍ); and the
non-contextuality condition on the probability measure. The argument
extracts the algebraic form of the rule from these inputs but cannot
supply the inputs themselves. In the framework of
dx₄/dt= ic, each Gleason input is recovered as a
downstream theorem of the principle: the Hilbert space as the
function-space rendering 𝓗= L²(M_(1,3), η_(μν)) of
the Minkowski manifold
(Theorem 9.31); the complex field as the
algebraic record of x₄-perpendicularity inherited from x₄= ict
(Theorem 9.10); the non-contextuality condition on
the probability measure as the operational shadow of the universal-rate
clause of the principle, the same fact that gives R3 phase invariance in
the derivation above. The McGucken derivation of P = |ψ|² from
dx₄/dt= ic through R1--R4 is upstream of all three Gleason
inputs: the principle supplies the Hilbert space, the complex structure,
and the phase invariance simultaneously, with the exponent 2 supplied by
the rank-2 character of the Minkowski metric, the entire derivation
requiring no measure-theoretic argument on the lattice of closed
subspaces. The same observation applies to the other
canonical Hilbert-space-internal derivations --- Deutsch--Wallace
decision-theoretic, Zurek envariance, Hartle and
Farhi--Goldstone--Gutmann frequentist, Bohm--Valentini--Westman
quantum-equilibrium --- each of which presupposes a complex separable
Hilbert space and imports one further axiom whose physical origin
remains unexplained in the framework that imports it. The disposition of the McGucken derivation toward this tradition is one of
upstream sufficiency: the principle generates the arena and the rule
together, with the prior-tradition arguments reappearing as downstream
functional-analytic consistency checks whose inputs are themselves
McGucken theorems.

#### Empirical anchor

The Born rule is the operational interpretation of every quantum
mechanical experiment since 1926. The squared-modulus rule has been
tested to fractional precision ∼ 10⁻³ in three-slit experiments
(Sinha et al. 2010 [34]), excluding higher-order alternatives
such as |ψ|³ or |ψ|⁴ with high statistical significance. The
rule P = |ψ|² is one of the most precisely tested rules in
physics.

Weinberg's question "Where does the Born rule come from?"
[30] is answered, in the McGucken dx₄/dt= ic framework, by the double
derivation above: it comes from dx₄/dt= ic, twice.


## Part VIII. Convergence of the two channels on the Born rule, the physical instantiation of the rule at every detector, measurement as physical Wick rotation, and gravity as the Born rule

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts that the two derivations of Parts V and VI reach the same density by disjoint machinery, because the squaring of dx₄/dt = ic into (ic)² = -c² that takes the rank-1 perpendicular principle to the rank-2 Minkowski invariant is the same operation that takes the rank-1 amplitude ψ to the rank-2 density |ψ|². The dx₄/dt = ic Algebraic Channel establishes the form; the dx₄/dt = ic Geometric Channel establishes the mechanism; their convergence is the convergent-overdetermination signature of the McGucken Quantum Formalism (§7.12 of [1]). The Principle further predicts where the rule is instantiated: at +ic-oriented Sphere collisions in spacetime, the Geometric Channel physical events whose statistics the Algebraic Channel reports (§16.19, Theorem 16.7); that each such event is the physical Wick rotation removing the marker i from the amplitude (Theorem 12.2), with the thermodynamic limit as that rotation performed Γₜₒₜₐₗ times per second (Theorem 12.4); and that the Born rule and gravity are one Haar measure of the Sphere read at the event and over the horizon respectively (§10.12duodecies). The corresponding sections of [1] are reproduced verbatim and in full.


### VIII.1 Convergence of the dx₄/dt = ic Geometric Channel and the dx₄/dt = ic Algebraic Channel on the Born rule


### 7.12 dx₄/dt=ic Geometric Channel and dx₄/dt=ic Algebraic Channel convergence on the Born rule

The §7 development of the Born rule realizes the dual-channel structure of the McGucken Quantum Formalism in two complementary forms. **dx₄/dt = ic Geometric Channel** (geometric-propagation channel; §§7.8–7.11) supplies three geometric readings of |ψ|² as direct wavefront-overlap content on McGucken Spheres:

- **Theorem 7.4 (geometric overlap)**: |ψ|² at the detection event is the geometric overlap of the forward x₄-expansion ψ with the conjugate x₄-expansion ψ* at the apparatus event;
- **Theorem 7.7 (head-on collision)**: |ψ|² is the head-on collision content of two McGucken Spheres meeting at the detection event, with ψ* identified as the absorber’s outgoing sphere in the emitter’s frame;
- **Theorem 7.11 (PT-symmetry through source event)**: complex conjugation of the McGucken-Sphere wavefront is the 4D PT-symmetry through the source event, with ψ(PT_E · event) = ψ*(event) exactly.

**Algebraic Channel** (algebraic-symmetry channel; §§7.3–7.6) derives the Born rule’s uniqueness from four algebraic requirements (R1)–(R4) descending from dx₄/dt = ic — the quadratic form from conservation under the propagation that the rank-2 Minkowski metric induces (Lemma 7.1), phase invariance from the universal x₄-expansion eliminating off-diagonal terms, reality from physical interpretability as probability, and non-negativity from the photon’s null-cone position.

The two channels supply different but compatible content:

| dx₄/dt = ic Geometric Channel (§§7.8–7.11, wavefront-geometric) | Algebraic Channel (§§7.3–7.6, algebraic-symmetry) |
|:--------------------------------------------------|:--------------------------------------------------|
| McGucken-Sphere wavefronts from Definition 2.6 | Four requirements (R1)–(R4) from dx₄/dt = ic |
| Geometric overlap of forward and conjugate x₄-expansions (Theorem 7.4) | Bilinearity from rank-2 Minkowski metric (Lemma 7.1) |
| PT-symmetry through source event (Theorem 7.11) | Phase invariance from universal x₄-expansion |
| Born density as head-on McGucken-Sphere collision (Theorem 7.7) | Reality + non-negativity from physical interpretation |
| Antipodal self-overlap at detector (Theorem 7.11 cont.) | Normalization fixes the constant |
| Output: P = \|ψ\|² | Output: P = \|ψ\|² |
| Establishes the physical mechanism | Establishes the algebraic form |


Both routes start from the McGucken Principle dx₄/dt = ic; both reach P = |ψ|² as the only density compatible with the wavefront geometry. Algebraic Channel operates on the algebraic structure of densities on the McGucken-derived Hilbert space and forces the squared-modulus form by four McGucken-supplied algebraic requirements. dx₄/dt = ic Geometric Channel operates directly on the McGucken-Sphere wavefront and identifies |ψ|² as the geometric overlap of two x₄-expansions (forward and conjugate) at the detection event. The Algebraic Channel route establishes that no other density is consistent with the McGucken-supplied requirements; the dx₄/dt = ic Geometric Channel route establishes what the resulting density geometrically *is* — the simultaneous presence of two McGucken-Sphere wavefronts at the same spacetime point, with the absorber’s conjugate wavefront ψ* extending back in time from the detection event to meet the emitter’s forward wavefront ψ.

The convergence of the two channels is the convergent-overdetermination signature of the Born rule within the McGucken Quantum Formalism: the algebraic requirements that force the squared modulus are precisely the algebra of the geometric overlap that defines |ψ|² as a wavefront-collision invariant. The two channels are the algebraic and wavefront shadows of one geometric fact: the squaring of dx₄/dt = ic into (ic)² = −c² that takes the rank-1 perpendicular principle to the rank-2 invariant of the Minkowski metric is the same operation that takes the rank-1 amplitude ψ to the rank-2 density |ψ|², with the i removed and the result becoming the real-valued, non-negative, spatial-slice probability density of the McGucken Sphere’s encounter with its conjugate.

The Born rule equation P = |ψ|² is the canonical case of Corollary 16.5’s mathematics vs physical-instantiation distinction. The mathematics |ψ|² = ψ^* ψ is T-invariant (PT-symmetric on i, with complex conjugation being the T-action on the wavefunction by Theorem 7.11); by Corollary 16.4, this gives dual derivations through the dx₄/dt = ic Geometric Channel (three geometric readings via Theorems 7.4, 7.7, 7.11) and Algebraic Channel (algebraic uniqueness from R1-R4). But the **physical instantiation** of the Born rule — every actual measurement event — is T-anti-invariant: the head-on McGucken-Sphere collision at the future detection event (Theorem 7.7) happens at +ic in physical spacetime, with the absorber’s outgoing sphere ψ^* meeting the emitter’s forward sphere ψ at a definite future event q. The convergence-table above catalogs dx₄/dt = ic Geometric Channel and Algebraic Channel *mathematics* of the Born rule; §16.19 (Theorem 16.7) catalogs the *physical instantiation* — seven detector types (photographic emulsion, photomultiplier, CCD, Stern-Gerlach, bubble chamber, Geiger counter, neutrino) — each of which is a dx₄/dt = ic Geometric Channel physical event whose statistics Algebraic Channel reports via |ψ|². The orthodox treatment of |ψ|² as ontologically primitive (the universal-wavefunction reading of §16.17) is the canonical case of the orthodox foundational confusion: treating the algebraic-shadow probability density as a feature of reality independent of the dx₄/dt = ic Geometric Channel physical events whose statistics it records.


### VIII.2 The physical instantiation of the Born rule: every measurement event is a +ic-oriented McGucken-Sphere collision

The McGucken Principle dx₄/dt = ic predicts that the Geometric Channel is what exists in spacetime and the Algebraic Channel is the statistical encoding of what repeated measurements report; the Born rule equation belongs to the encoding, the detector click to spacetime. Sections 16.19.1–16.19.3 of [1] are reproduced here (statement clauses (i), (ii), (iv), (v) of Theorem 16.7 with proof Steps 1–3 and 5–6).


#### 16.19.1 The ontological-epistemic asymmetry of the two channels

The McGucken Sphere Σ₊(p) expanding at +ic from every spacetime event p is the dx₄/dt = ic framework’s commitment about what exists in the universe — a real geometric object in real four-dimensional spacetime, with definite radius growing at c δ t, definite surface area 4π(c δ t)², definite Compton-frequency content, definite directional orientation in the +ic direction. The Sphere is in spacetime: it has spatiotemporal coordinates, propagates through physical space at velocity c, and interacts with other Spheres at collision events. The dx₄/dt = ic framework’s ontological commitment is that the +ic-oriented Sphere expansion at every event is what exists; everything else in the dx₄/dt = ic framework is a reading of this content.

The Hilbert space 𝓗, the operator algebra, the canonical commutator [q̂, p̂] = iħ, the unitary one-parameter groups, the wavefunction ψ, the projection operators P̂ₙ, the trace formula ⟨ Ô ⟩ = Tr(ρ Ô), the Born rule equation P = |ψ|² — these are calculational structures that predict the statistics of measurement events without being in spacetime themselves. The Hilbert space is not a physical place; ψ is not an entity at any spatiotemporal location; the operator algebra is not a set of objects in the universe; the eigenvalues are not physical events. They are the apparatus by which measurement-event distributions are predicted, calculated, and aggregated.

**The categorical asymmetry is what each channel *is*, not whether it touches empirics.** Both channels are empirically anchored — the dx₄/dt = ic framework’s case in §16.13–§16.15 rests on this (CPT pattern, Bisognano-Wichmann modular flow, Wightman Spectrum Condition, all of the 47-theorem dual catalog, all of the asymmetric census). Both produce predictions that get tested. The asymmetry is not “one is measured and one is not.” The asymmetry is in what each channel *is*: dx₄/dt = ic Geometric Channel is physical-spatiotemporal reality (including measurement events as physical events in spacetime); Algebraic Channel is the calculational-statistical encoding that predicts the distribution of measurement-event outcomes across repetitions.
This is the cleanest formulation of the asymmetry: **dx₄/dt = ic Geometric Channel is what exists in spacetime; Algebraic Channel is what measurements report when those existing physical events are repeated.** The dx₄/dt = ic framework’s claim is not that Algebraic Channel is empirically vacuous (it is not — its empirics is substantial and well-established); the claim is that Algebraic Channel is ontologically inadequate as a substrate for the physical universe. The substrate is dx₄/dt = ic Geometric Channel; the encoding is Algebraic Channel.

#### 16.19.2 Measurement events as dx₄/dt = ic Geometric Channel physical events

Every measurement event in the universe — every detector click, every photographic emulsion grain, every photomultiplier cascade, every CCD pixel charge, every Stern-Gerlach beam deflection, every bubble chamber track, every photodiode voltage pulse, every Geiger counter discharge, every neutrino interaction in a water-Cherenkov detector — is a physical event in spacetime, with definite location, definite time, definite energy-momentum transfer, definite outcome propagating outward at +ic as a permanent record.

In the dx₄/dt = ic framework’s reading, each such event is a **head-on McGucken Sphere collision at a +ic-oriented detection event**. The source Sphere Σ₊(p_(source)) expanding at +ic from the source event p_(source) meets the detector’s atomic Sphere Σ₊(p_(det)) expanding at +ic from a detector-atom event p_(det) at the spacetime event q where their wavefronts intersect head-on. The collision is a physical event with definite spatiotemporal coordinates q, definite energy-momentum content, and definite electromagnetic / strong / weak interaction depending on the species of the source’s Sphere and the detector atom. The Born rule probability density |ψ(q)|² at the detection event q is the head-on collision rate, derived from the Haar measure on SO(3)/SO(2) at the collision event (Theorem 7.7 of the present paper, with the exponent 2 overdetermined by three independent routes: rank-2 sesquilinear metric pairing, two-Sphere collision rate, PT-symmetry through the source event).

The catalog of measurement instantiations:

- *Photographic emulsion.* A grain of silver halide is rendered into latent-image silver by a photon absorption event: the photon’s Sphere collides head-on with the silver-halide-electron Sphere at the grain location, producing a definite ionization event. The grain’s location records the spacetime event q.

- *Photomultiplier tube.* An incident photon’s Sphere collides with a photocathode-electron Sphere; the resulting photoelectron is amplified through a cascade of dynode collisions, each itself a head-on Sphere collision producing additional secondary electrons. The final voltage pulse records the chain of +ic-oriented Sphere collisions originating at the photocathode event.

- *Charge-coupled device (CCD).* An incident photon’s Sphere collides with a silicon-electron Sphere in a CCD pixel well, producing a definite electron-hole pair event. The accumulated charge in the well records the count of Sphere-collision events during the exposure.

- *Stern-Gerlach apparatus.* A silver atom traversing the inhomogeneous magnetic field has its electron’s spin-Sphere couple to the field gradient, with the head-on collision dynamics on the screen depositing the atom at a definite location corresponding to one of the two eigenvalues of Ŝ_z. The deposit location records the eigenvalue selection.

- *Bubble chamber.* A charged particle’s Sphere ionizes superheated liquid atoms along its trajectory; each ionization is a head-on Sphere collision producing a definite bubble nucleation event. The bubble track records the sequence of +ic-oriented collision events along the particle’s worldline.

- *Geiger counter.* An ionizing particle’s Sphere produces a primary ionization event in the gas; the resulting electron cascade through the high-voltage gas produces a definite electrical discharge pulse. The pulse records the primary collision event.

- *Neutrino detector (Cherenkov, scintillator, semiconductor).* A neutrino’s Sphere collides head-on with a target nucleon’s Sphere (in the weak-interaction channel), producing a definite charged-lepton or hadronic event; the secondary particles’ subsequent Sphere collisions with the detector medium produce the observable signal.

In every case, the measurement event is a physical event in spacetime — a +ic-oriented head-on Sphere collision at a definite spacetime location. The dx₄/dt = ic framework’s commitment is that *measurement events are dx₄/dt = ic Geometric Channel physical events, not Algebraic Channel statistical-calculational structures*.

Algebraic Channel’s apparatus consists of the Born rule equation, the projection operators P̂ₙ = |n⟩⟨ n|, the eigenvalue decomposition Ô = ∑ₙ oₙ P̂ₙ, the trace formula ⟨ Ô ⟩ = Tr(ρ Ô), the unitary evolution U(t) = e^(-iĤt/ħ), and the wavefunction ψ on configuration space. None of these are events in spacetime. The projection operator P̂ₙ is a Hermitian operator on the Hilbert space; it has no spatiotemporal location; it does not occur at any particular event; it is a calculational structure encoding which kinds of measurement events can co-occur with which kinds of other measurement events. The Born rule equation P = |ψ|² is an algebraic relation between two calculational structures; it is not the event of a detector clicking. The events of detector clicks are in the dx₄/dt = ic Geometric Channel; the equation predicting their probability density is in the Algebraic Channel.

The Schrödinger equation iħ ∂ₜ ψ = Ĥψ propagates ψ forward in t continuously; nothing in the unitary apparatus picks out a particular moment as “the measurement moment.” From within Algebraic Channel alone, the universe’s wavefunction evolves unitarily forever and never produces any definite outcome. The Algebraic Channel needs an external specification — supplied by the dx₄/dt = ic Geometric Channel — of “a measurement event has just occurred at spacetime event q” to deploy the Born rule’s statistics. The external specification is the dx₄/dt = ic Geometric Channel physical event of a Sphere-collision at q. Without dx₄/dt = ic Geometric Channel physical events providing this specification, Algebraic Channel’s apparatus runs unitarily forever in vacuum: predicting nothing, deciding nothing, registering nothing.

This is the fact that the orthodox foundational programme has been unable to absorb: The Algebraic Channel’s apparatus alone does not contain the resources to produce measurement events because measurement events are not the kind of thing Algebraic Channel contains. The events are in the dx₄/dt = ic Geometric Channel; the statistical machinery for predicting their distribution is in the Algebraic Channel; the two are categorically distinct.

#### 16.19.3 Theorem 16.7: Dissolution of the orthodox measurement problem

The orthodox measurement problem has been the central foundational impasse of physics for nearly a century. The standard statement of the problem (Bohr-Heisenberg 1927, von Neumann 1932, Wigner 1961, Bell 1990, Schlosshauer 2007): the Schrödinger equation propagates ψ unitarily, but laboratory measurements produce definite outcomes; what dynamics, mechanism, or interpretation bridges the unitary evolution and the definite-outcome reality?

Every orthodox interpretation of quantum mechanics is an attempt to answer this question. The Copenhagen interpretation (Bohr 1927–1935) declares measurement to be a primitive irreducible category outside the unitary dynamics, with the dynamics applied to closed systems and measurement as a separate process; this is unsatisfactory because it leaves measurement unanalyzed and creates the famous “Heisenberg cut” between quantum system and classical apparatus. The Many-Worlds Interpretation (Everett 1957, DeWitt 1970, Wallace 2012) declares the unitary evolution to be complete with definite outcomes arising as observer-relative branching; this relocates the problem to why observers experience single branches, which is itself a definite-outcome fact requiring its own account. The GRW spontaneous-collapse models (Ghirardi-Rimini-Weber 1986) add a stochastic non-unitary term to the dynamics; this is mathematically functional but empirically unmotivated (the stochastic term has never been observed) and ad-hoc. The de Broglie-Bohm pilot-wave theory (de Broglie 1927, Bohm 1952) adds definite particle trajectories as hidden variables guided by ψ; this restores ontology but at the cost of explicit nonlocality that does not naturally extend to the relativistic case. The QBist reading (Caves-Fuchs-Schack 2002) interprets ψ as the agent’s personal probability assignments, avoiding the measurement problem by denying the realism question; this is internally consistent but refuses to make claims about the universe itself. Decoherence-based programmes (Zurek 1981, Joos-Zeh 1985) explain the suppression of interference between branches but do not produce definite single-outcome events. Bell 1990 called the measurement problem “the greatest unsolved mystery in modern physics.” Wheeler spent decades on it; Penrose 2004 devotes hundreds of pages to it; Schlosshauer 2007 catalogs the failed resolution attempts.

The dx₄/dt = ic framework’s diagnosis is that the question is malformed. The dx₄/dt = ic framework’s positive content provides a dissolution as a theorem.

**Theorem 16.7 (Dissolution of the orthodox measurement problem).** The orthodox measurement problem — “how does the unitary evolution of |ψ⟩ produce definite measurement outcomes?” — is malformed. Specifically:

*(i)* Measurement events are physical events in spacetime: head-on McGucken Sphere collisions at +ic-oriented detection events (Theorem 7.7 of the present paper; §16.19.2 of the present paper).

*(ii)* These events are dx₄/dt = ic Geometric Channel; they are not contained in the Algebraic Channel’s apparatus (which consists of the Hilbert space, the wavefunction ψ, the operator algebra, the unitary evolution, the Born rule equation, and the projection operators — none of which is a physical event in spacetime).
*(iv)* The dx₄/dt = ic framework supplies the positive Geometric Channel mechanism: the Born rule probability density |ψ(q)|² is the Haar-measure-weighted rate of head-on Sphere collisions at the +ic-oriented detection event q, with the exponent 2 overdetermined by three independent routes (rank-2 sesquilinear metric pairing, two-Sphere collision rate, PT-symmetry through the source event) [1 §7.4, Theorem 7.7; 19 Theorem 22.6 on SO(3)/SO(2) Haar uniqueness]. Definite outcomes are produced at every measurement event by the Sphere-collision mechanism in the dx₄/dt = ic Geometric Channel; The Algebraic Channel reports the statistics.

*(v)* Therefore the orthodox measurement problem dissolves: the question presupposes Algebraic Channel is the locus of measurement-event production, when in fact dx₄/dt = ic Geometric Channel is the locus and Algebraic Channel is the statistical encoding. The dissolution is complete because dx₄/dt = ic Geometric Channel has a positive physical mechanism (Sphere collision with Haar measure), not merely a relocation of the mystery.

**Proof.** We establish each step.

*Step 1 (Category identification).* The two channels operate on categorically distinct content. The dx₄/dt = ic Geometric Channel’s content 𝓑 is physical-spatiotemporal: +ic-oriented McGucken Spheres at every spacetime event, with the Sphere collisions, the cosmological expansion, the arrows of time, the matter dominance as physical entries in the universe. The Algebraic Channel’s content 𝓐 is calculational-statistical: Hilbert spaces, operator algebras, wavefunctions, projection operators, unitary one-parameter groups, the Born rule equation. The categorical distinction is that dx₄/dt = ic Geometric Channel’s content sits in spacetime at events (definite location, definite time, definite physical-causal interactions with other content), while Algebraic Channel’s content does not (the Hilbert space has no spatiotemporal location; the wavefunction is a function on configuration space, not an event at a spacetime point; the operator algebra is a set of mathematical relations, not a set of physical processes).

*Step 2 (Measurement events are dx₄/dt = ic Geometric Channel).* Every laboratory measurement event has a definite spacetime location, a definite time, and a definite outcome propagating outward. Detector clicks at definite times; photographic emulsion grains develop at definite locations; CCD pixels charge at definite events. These are physical events in spacetime — dx₄/dt = ic Geometric Channel. The dx₄/dt = ic framework identifies each such event as a head-on McGucken Sphere collision at a +ic-oriented detection event (§16.19.2 of the present paper). The Born rule probability density at the detection location is the Sphere-collision rate, derived from the Haar measure on SO(3)/SO(2) in Theorem 7.7 of the present paper.

*Step 3 (Algebraic Channel’s apparatus does not contain measurement events).* The orthodox quantum-mechanical apparatus of the Algebraic Channel consists of: (a) a Hilbert space 𝓗 — a mathematical structure with inner product, not a physical place; (b) a wavefunction ψ : 𝒞 → ℂ on configuration space 𝒞 — a function, not an event; (c) Hermitian operators Ô — algebraic structures whose eigenvalues label measurement-event categories without being events; (d) projection operators P̂ₙ = |n⟩⟨ n| — algebraic projections, not physical collisions; (e) the unitary group U(t) = e^(-iĤt/ħ) — a one-parameter group action on the Hilbert space, not a sequence of physical events; (f) the Born rule equation P = |ψ|² — an algebraic relation between two calculational structures, not the event of a detector clicking; (g) the trace formula ⟨ Ô ⟩ = Tr(ρ Ô) — a statistical-ensemble-expectation computation, not a physical observation. None of (a)–(g) is a physical event in spacetime; all are calculational-statistical structures predicting the distribution of physical events that happen in the dx₄/dt = ic Geometric Channel.
*Step 5 (The positive dx₄/dt = ic Geometric Channel mechanism).* The dx₄/dt = ic framework supplies what the dissolution requires to be complete rather than merely relocational: a positive dx₄/dt = ic Geometric Channel mechanism for measurement-event production. The mechanism is the head-on Sphere collision dynamics derived from dx₄/dt = ic at every event. Specifically:

(a) The source’s Sphere Σ₊(p_(source)) expands at +ic from the source event p_(source), with surface area growing as 4π(c δ t)² at parameter time δ t from the source.

(b) The detector’s atomic Sphere Σ₊(p_(det)) expands at +ic from each detector-atom event p_(det).

(c) The two Spheres meet at the spacetime event q where their wavefronts intersect head-on.

(d) The head-on collision at q is the measurement event. It has definite spacetime coordinates q, definite energy-momentum content (determined by the source’s Compton-frequency content and the detector’s atomic energy levels), and definite electromagnetic / strong / weak interaction (determined by the species of the source and detector Spheres).

(e) The Born rule probability density at q is |ψ(q)|², where |ψ(q)|² is the Haar-measure-weighted rate of head-on Sphere collisions at q given the source’s Compton-frequency content and the detector’s spatial layout. The exponent 2 is overdetermined by three independent routes [1 §7.4]: the rank-2 sesquilinear metric pairing of the two Spheres’ phase contents; the two-Sphere collision rate (one source Sphere meeting one detector Sphere is a rank-2 product); the PT-symmetry through the source event, which yields the squared-modulus structure under PT-reflection.

The Sphere-collision mechanism is a definite physical process in spacetime producing definite outcomes at every measurement event. The probability density |ψ|² is the algebraic statement of the collision-rate distribution; the events are the collisions; the outcomes are the collision results. The mechanism is fully specified in the dx₄/dt = ic Geometric Channel, with the Algebraic Channel reporting the statistics.

*Step 6 (Dissolution).* By Steps 1–5: (i) measurement events are dx₄/dt = ic Geometric Channel physical events; (ii) Algebraic Channel’s apparatus does not contain physical events; (iii) the orthodox measurement question is malformed (asks the encoding to produce the events); (iv) the dx₄/dt = ic framework supplies a positive Geometric Channel mechanism (Sphere collision with Haar measure); (v) the orthodox measurement problem dissolves — there is no problem to solve because there is no question correctly posed within Algebraic Channel alone. The question’s apparent intractability over the past century is the signature of its malformation: orthodox interpretations have been unable to settle it because they have been trying to extract dx₄/dt = ic Geometric Channel (definite events) from Algebraic Channel apparatus (statistical encoding), which by Theorem 16.3 (no Π_B) is impossible. The dx₄/dt = ic framework dissolves the problem at the source rather than resolving it within Algebraic Channel’s confines. ∎

The dissolution is complete rather than relocational. The dx₄/dt = ic framework does not say “the measurement problem is solved by adding X to quantum mechanics”; it says “the measurement problem rests on a category error about which channel contains measurement events, and the error dissolves once dx₄/dt = ic Geometric Channel is identified as the physical-spatiotemporal substrate where the events actually happen.” The positive dx₄/dt = ic Geometric Channel mechanism (Sphere collision with Haar measure) is supplied by the dx₄/dt = ic framework’s derivation from dx₄/dt = ic; the orthodox apparatus’s apparent failure to produce definite outcomes is the signature of its being the T-invariant epistemic projection of the full content, not the full content itself.


### VIII.3 Measurement as physical Wick rotation: the removal of the perpendicularity marker i at the collision event

The McGucken Principle dx₄/dt = ic predicts that the squaring ψ → ψ^*ψ performed at a detection event and the coordinate rotation x₄ = ict → ct of the Wick rotation are one geometric operation performed at two cascade levels: both remove the marker i of x₄-perpendicularity, the first from the amplitude of a particle whose participation in the expansion ends at the absorber, the second from the coordinate. Sections 12.3–12.7 of [1] are reproduced here.


### 12.3 The measurement event: rotation out of x₄

**Definition 12.1 (Measurement event).** A *measurement event* is a spacetime event E ∈ Minkowski Space 𝕄_(1,3) at which a quantum particle’s four-velocity is rotated from a configuration with x₄-component (participation in x₄-expansion) to a configuration localized at E (committed to a definite spatial position at a definite t). The geometry of the rotation: the particle’s worldline tangent reorients from the x₄-perpendicular direction toward the spatial directions x₁x₂x₃, removing the x₄-component that was encoded by the wavefunction’s phase.

The mechanism of the rotation is the meeting of two geometric structures at E (Theorem 7.4):

(a) The particle’s **forward x₄-expansion** ψ has amplitude at E. The particle’s wavefunction has reached this spacetime point through its spreading from the emission event, with phase encoding accumulated x₄-component and modulus encoding spatial-slice amplitude.

(b) The detector apparatus has been prepared, by prior decoherence, to register at a definite spatial position. Its **conjugate x₄-image** ψ* extends back to E, encoding “a localized absorber is here at E, ready to register.” (The conjugate is the same wavefunction with phase reversed — geometrically, the time-reversed/phase-reversed representation of the forward expansion.)

For the rotation out of x₄ to occur at E, both (a) and (b) must be present at E. The probability density that the rotation occurs at E is therefore the bilinear product ψ*(E) ψ(E), with the exponent 2 recording the count of independent factors that must coincide: the forward expansion arrives at E AND the absorber’s conjugate image extends to E. The squaring is the algebraic signature of the geometric coincidence required for the rotation to take place.

Post-rotation, the particle is localized at E. Its wavefunction has collapsed onto the eigenstate corresponding to detection at E (Corollary 11.4, the projection postulate). The i-bearing participation in x₄-perpendicularity, which the pre-measurement wavefunction encoded in its complex phase, has been removed from the description. The post-measurement state is real-valued in the sense that the i-marker for x₄-perpendicularity is gone — the particle is no longer participating in the spreading x₄-expansion, and the geometry of its description no longer requires the perpendicularity-marker i.

### 12.4 The mathematical Wick rotation as formalization of the physical rotation

The standard mathematical Wick rotation in quantum field theory is the analytic continuation t → −iτ (equivalently, x₄ = ict → x₄^W := ct), which maps the Lorentzian metric ds² = −c²dt² + dx²_spatial to the Euclidean metric ds_E² = c²dτ² + dx²_spatial. At the path-integral level, the Wick rotation converts oscillating phase weights exp(iS/ℏ) into damped real weights exp(−S_E/ℏ), removing the i from the action.

Geometrically, the Wick rotation removes the i from the Minkowski coordinate x₄ = ict — it rotates x₄ from its imaginary-axis perpendicular direction into a real-axis direction (cf. §4.5 of the present paper; the corpus identifies the Wick rotation as the McGucken-internal coordinate change τ = x₄/c between the integrated form x₄ = ict and the proper-time parameterization, cited at §4.5, §4.4, and the corpus Wick-rotation treatment). The Wick rotation is, in the McGucken dx₄/dt = ic framework, a coordinate operation that removes the perpendicularity marker, transitioning between the i-bearing description (x₄ perpendicular, dynamics complex) and the i-free description (x₄ real, dynamics Euclidean).

The dx₄/dt = ic framework recognizes the physical measurement event as the *physical* realization of this *mathematical* rotation. The mathematical Wick rotation removes the i from the coordinate x₄. The physical measurement event removes the i from the particle’s description — rotating it out of the x₄-perpendicular direction into a real spatial event. The two are the same geometric operation, performed in different ways: the mathematical operation is performed at the coordinate level via analytic continuation; the physical operation is performed at the particle level via the geometric meeting of forward and conjugate x₄-expansions at a localized absorber.

### 12.5 Theorem 12.2: Measurement as Physical Wick Rotation

**Theorem 12.2 (Measurement as Physical Wick Rotation).** *Let ψ be a wavefunction on Minkowski Space 𝕄_(1,3) representing a quantum particle’s forward x₄-expansion from an emission event. Let E ∈ Minkowski Space 𝕄_(1,3) be a candidate measurement event at which a localized absorber is prepared to register. Then the measurement event at E corresponds to the physical realization of the Wick rotation*

x₄ = ict ⟶ x₄^W := -i x₄ = ct

*at the particle’s worldline at E, with the wavefunction’s i-bearing complex amplitude ψ rotated into the real-valued spatial-slice probability density |ψ(E)|² = ψ*(E)ψ(E). The Born rule’s exponent 2 is the algebraic signature of this rotation, derived from the rank-2 character of the Minkowski metric (Lemma 2.5) via Lemma 7.1.*

**Proof.**

(1) The Minkowski coordinate x₄ = ict carries the imaginary unit i as the perpendicularity marker for x₄’s orthogonality to x₁x₂x₃ (Theorem 3.1, §4.3, §4.5). Multiplication by i implements the rotation that takes a spatial direction into the perpendicular x₄-direction.

(2) The Wick rotation x₄ → −ix₄ = ct removes the i from the coordinate. Geometrically, this rotates x₄ from its perpendicular imaginary-axis orientation into the real-axis orientation, mapping the Lorentzian metric ds² = −c²dt² + dx²_spatial to the Euclidean metric ds_E² = c²dτ² + dx²_spatial. This is the standard Wick rotation; in the McGucken dx₄/dt = ic framework, it is recognized as the coordinate identification between the integrated form x₄ = ict (perpendicular, imaginary axis) and the proper-time parameterization τ = x₄/c (real axis); see §4.5 of the present paper and the corpus Wick-rotation treatment.

(3) Between emission and measurement, the particle’s wavefunction ψ is i-bearing: its complex phase encodes the particle’s accumulated x₄-component along its worldline (Definition 12.1; §12.2 (i)). The wavefunction’s complex character is the imprint of x₄-perpendicularity on its phase, with multiplication by exp(iφ) implementing rotation by angle φ in the perpendicular x₄-direction (Theorem 3.1).

(4) At a measurement event E, the geometric meeting of the forward x₄-expansion ψ with the localized absorber’s conjugate x₄-image ψ* at E (Theorem 7.4) rotates the particle’s four-velocity out of x₄. The geometric meeting requires both factors to be present at E — the forward expansion’s amplitude AND the conjugate image’s amplitude — with the product ψ*(E) ψ(E) the algebraic record of the bilinear coincidence (Lemma 7.1, with rank-2 forced by Lemma 2.5).

(5) The product ψ*(E) ψ(E) is real-valued: any complex number z multiplied by its conjugate z* gives |z|², a real non-negative quantity. The squaring eliminates the imaginary part of ψ, removing the i that encoded the particle’s participation in x₄-perpendicularity. The result is a real-valued probability density on the spatial slice at E.

(6) The physics of the squaring at the amplitude level is therefore identical to the physics of the Wick rotation at the coordinate level: both remove the i that is the perpendicularity-marker for x₄. The mathematical operation x₄ = ict → ct (Wick rotation at the coordinate level) and the physical operation ψ → |ψ|² (squaring at the amplitude level) are the same geometric operation — rotation of the i-bearing perpendicular structure into the real spatial-slice structure — performed at different cascade levels.

(7) The post-measurement state is the particle localized at E, with the wavefunction collapsed onto the corresponding eigenstate (Corollary 11.4). The particle’s worldline tangent has reoriented from the x₄-perpendicular direction toward the spatial directions; it is no longer participating in the spreading x₄-expansion, and its description no longer requires the i-marker for x₄-perpendicularity.

(8) Therefore, the measurement event at E *is* the physical realization of the Wick rotation x₄ → −ix₄, with the i removed at both the coordinate-level (x₄ → ct at the rotation moment) and the amplitude-level (ψ → |ψ|² at the rotation moment), with both operations performed in coincidence at the geometric meeting event E. ∎

**Corollary 12.3.** *The standard path-integral Wick rotation, used as a mathematical convergence device in quantum field theory, is the formal abstraction of the physical measurement rotation.* The Wick rotation converts oscillating phase weights exp(iS/ℏ) into damped real weights exp(−S_E/ℏ), removing the i from the path-integral action. The physical measurement event removes the i from the particle’s amplitude, with the same geometric effect: transition from the i-bearing oscillatory description (active x₄-perpendicularity) to the i-free real description (localized spatial event). The Wick rotation has, in the McGucken dx₄/dt = ic framework, a physical referent: the measurement event in the laboratory.

**Remark 12.2b (dx₄/dt = ic anchoring of Theorem 12.2 — measurement as physical Wick rotation removes i from the wavefunction at the measurement event).** *Theorem 12.2 anchors the measurement event to the coordinate-level Wick rotation x₄ → -ix₄ at the measurement event, with the i removed both at the coordinate level (the i in x₄ = ict is rotated out as the particle’s x₄-expansion participation ends at the absorber) and at the amplitude level (ψ → |ψ|² as the complex amplitude is squared into the real Born density). The dx₄/dt = ic content operative: (C1) the rate c is the rate at which the forward x₄-expansion proceeds before measurement; (C2) the perpendicularity marker i in x₄ = ict is the algebraic object that the Wick rotation removes at the measurement event; (C3) the action quantum ħ in the path-integral phase exp(iS/ħ) is the same ħ that the Wick rotation converts to the Euclidean weight exp(-S_E/ħ) at the measurement event; (C5) the McGucken Sphere at the measurement event is the geometric structure that the rotation operates on; (C4) per-event universality supplies the measurement event E as an event of 𝕄_G at which dx₄/dt = ic holds (until the rotation). The cascade-upstream dependence: dx₄/dt = ic → x₄ = ict (integrated form) → i as perpendicularity marker → measurement = removal of i at the measurement event. The McGucken-Wick rotation framework of [21, Theorems 19, 19.5] supplies the corpus-paper input that the Wick rotation τ = x₄/c is a coordinate identity, not an analytic continuation; Theorem 12.2 specializes this coordinate-identity Wick rotation to the measurement event as the physical realization. Corollary 12.3 then identifies the path-integral Wick rotation of QFT as the formal abstraction of this physical measurement rotation. See §17.6.11 for the comprehensive audit position.*

### 12.6 Two canonical illustrations: photon absorption and radioactive alpha detection

The dx₄/dt = ic framework’s reading of measurement as physical rotation out of the x₄-expansion is visible in two canonical experimental cases. The photon case is the purest: the photon’s existence as a photon is *constituted* by its participation in the x₄-expansion at exactly c, and absorption ends that participation absolutely, with no continuing photon. There is no “post-measurement photon at rest”; the photon is annihilated. The radioactive alpha case shows the same mechanism in a massive particle, where the rotation out of x₄ is the transition from free-particle participation in x₄-expansion (with the four-velocity budget partitioned between spatial and x₄ components per u^μ u_μ = −c²) to bound-state absence of such participation. Both instantiate the same universal mechanism. The photon case makes it most transparent.

#### 12.6.1 The photon case: emission, propagation at c, and annihilation at a photographic grain

Consider an atom de-exciting from an excited state to a lower state, emitting a single photon of frequency ω. By rotational symmetry of the atomic transition (for isotropic emitters, or after averaging over orientations of an ensemble of identical emitters), the emitted photon’s complex amplitude is initially an outgoing spherical electromagnetic wave centered on the emission event.

The photon’s status in the McGucken dx₄/dt = ic framework is ontologically more extreme than the massive particle’s. By the canonical ontology (clause 2), the photon is at *absolute rest in x₄* — its Sphere-tangent share vanishes, v_(x₄) = 0, on its null worldline, while the Principle dx₄/dt = ic holds at every event of that worldline — and it rides the x₄-expansion wavefront at the universal rate c. The photon’s existence as a photon is constituted by its participation in the x₄-expansion at the boundary speed c: geometrically, a photon is an excitation of the electromagnetic field propagating along the null light cone, which is the wavefront of the active x₄-expansion. To call something a photon is to call it a participant in the four-dimensional active expansion at exactly the boundary speed c, with no spatial-rest representation available — there is no inertial frame in which a photon is at rest.

(i) **Spherical emission as projection of isotropic x₄-expansion.** The x₄-expansion from the emission event is isotropic in spacetime (canonical ontology, clause 3). The photon’s complex amplitude directly after emission is an outgoing spherical electromagnetic wave centered on the emission event — the spatial-slice projection of the isotropic x₄-expansion wavefront. The initial spherical symmetry is the direct geometric record of the isotropic active expansion at the emission event.

(ii) **Propagation at c as riding the x₄-expansion wavefront.** The photon’s worldline is null: k^μ k_μ = 0, where k^μ is the photon’s four-momentum. In the (x₄ = ict, x₁, x₂, x₃) coordinate system, the photon’s spatial speed equals the x₄-rate in magnitude: it propagates at c along the spatial slice while x₄ advances at ic. The photon’s complex amplitude (the one-photon state in QED, or the classical EM field amplitude in the semi-classical limit) is i-bearing throughout this propagation, with the phase encoding the photon’s accumulated x₄-component along its null worldline and the modulus encoding the spatial-slice amplitude at each spacetime point. The photon, geometrically, *is* its participation in the x₄-expansion — there is no further substance to the photon beyond its propagating amplitude on the wavefront.

(iii) **Absorption at a photographic grain as physical annihilation of the photon.** The photographic emulsion contains discrete silver halide microcrystals (typically AgBr grains, of size \~ 0.5–1 μm). When the spherically spreading photon amplitude meets such a grain at some angle θ from the emission event, the absorption event occurs: the photon is *annihilated*, and its energy ℏω is transferred to a bound electron transition in the AgBr crystal, depositing a latent image that subsequent chemical development converts into metallic silver. The photon ceases to exist as a photon at this event. Unlike the massive-particle case, there is no question of “post-measurement photon state” because there is no post-measurement photon at all. The photon’s participation in the x₄-expansion ends absolutely at the absorption event. The rotation out of x₄ is, for the photon, total and unambiguous: the photon was a pure x₄-expansion participant, and now is not — because the photon as such no longer exists.

(iv) **Born rule probability as the algebraic signature of the photon’s annihilation.** The probability density that the grain at angle θ blackens is |ψ_γ(θ, t_abs)|² = ψ_γ*(θ, t_abs) ψ_γ(θ, t_abs), where ψ_γ is the photon’s complex amplitude (the appropriate QED matrix element ⟨ x | k, λ ⟩ for a one-photon state, or the classical EM field amplitude in the semi-classical limit). The modulus-squaring removes the i from the photon’s amplitude. This is the Wick rotation at the amplitude level (Theorem 12.2): the photon was an i-bearing participant in x₄-expansion; the squaring is the algebraic record of its annihilation, with the i removed because the photon — the i-bearing entity — has been removed. The exponent 2 is forced by the rank-2 character of the Minkowski metric (Lemma 7.1).

(v) **The film grain’s chemical reduction as macroscopic record on the spatial slice.** The AgBr crystal undergoes a photochemical reduction: Ag⁺ + e⁻ → Ag⁰, with the freed electron from the AgBr lattice’s valence band combining with an interstitial silver ion to form a metallic silver atom. With enough such reductions in a single grain (typically four silver atoms are needed for the grain to become developable), the grain becomes a developable latent image center. Subsequent chemical development reduces the entire grain to metallic silver, producing the visible black spot on the photographic plate. This chemical change is irreversible in any practical sense — the grain’s atomic structure has been altered, the photochemistry is one-way at ambient conditions, and the record exists purely on the spatial slice as a macroscopic configuration of silver atoms. The photon’s prior existence as a participant in the x₄-expansion leaves no trace in the post-absorption world except for this irreversible spatial-slice mark. The rotation out of x₄ is, in this case, complete: the photon is gone, the spatial-slice record remains.

The photon case exhibits the dx₄/dt = ic framework’s mechanism in its cleanest form. Pre-absorption, the photon is purely an x₄-expansion participant — there is no inertial-frame ambiguity about its “rest state” because no rest state exists. Post-absorption, the photon does not exist; the system that carries its deposited energy (the modified AgBr crystal) is at rest on the spatial slice, bound in the photographic emulsion’s chemistry, with no continuing participation in the x₄-expansion *as a free quantum*. The wavefunction’s i, which encoded the photon’s participation in the active expansion, is removed by the modulus-squaring because the participant — the photon — has been removed by the absorption.

Photographic detection of single photons is the historical foundation of quantum measurement: G. I. Taylor’s 1909 double-slit experiment with attenuated light, Einstein’s 1905 analysis of the photoelectric effect, Compton’s 1923 photon-electron scattering, the modern realization of single-photon detectors (avalanche photodiodes, superconducting nanowire detectors). Every photodetection event in the experimental record of twentieth- and twenty-first-century physics is, in the McGucken dx₄/dt = ic framework, a physical Wick rotation: a photon-as-x₄-expansion-participant is annihilated, the i-bearing amplitude is removed by the squaring, the spatial-slice record is established. The Born rule probability — squared because the underlying metric is rank-2 (Lemma 7.1) — is the algebraic signature of the physical annihilation event in every case.

#### 12.6.2 The radioactive alpha case: emission, spherical spreading, and detection

Consider a radioactive nucleus at rest, emitting an alpha particle by tunneling. The structure of the dx₄/dt = ic framework’s reading maps onto every stage of this canonical example, with the rotation-out-of-x₄ mechanism the same as in the photon case but with a massive-particle worldline replacing the null worldline.

(i) **Spherical wavefunction as projection of isotropic x₄-expansion.** The x₄-expansion from the emission event is isotropic in spacetime (canonical ontology, clause 3: from every event, the active expansion at ic proceeds symmetrically in all spatial directions). The spatial-slice projection of this isotropic expansion is a spherically symmetric outgoing wave centered on the emission event. The wavefunction’s initial spherical symmetry is the direct geometric record of the isotropic x₄-expansion structure, exactly as in the photon case.

(ii) **Spreading as surfing the x₄-expansion.** As proper time advances, the alpha particle’s worldline carries it forward along x₄ at the rate dx₄/dt = ic, with the four-velocity budget partitioned between spatial motion and x₄-advance per u^μ u_μ = −c² (Theorem 9.1 step 1). The wavefunction spreads over the spatial slice — at each later instant, the modulus is spread over a sphere of progressively larger radius. The spreading is the spatial-slice projection of the particle’s continuing participation in the x₄-expansion (Definition 12.1; §12.2). The wavefunction is complex-valued throughout: its phase encodes the accumulated x₄-component along the worldline, its modulus encodes the spatial-slice amplitude at each spacetime point. The difference from the photon case: the alpha’s worldline is timelike (u^μ u_μ = −c², not 0), the alpha has a well-defined rest frame in principle, and the alpha’s spatial spreading speed is determined by its kinetic-energy distribution rather than by the universal c.

(iii) **Detection at angle θ as rotation out of x₄ and absorption into the detector.** When a detector at angle θ from the source registers the alpha particle, the particle is rotated out of x₄ at the detector’s spatial location and absorbed into the detector’s matter. The forward x₄-expansion ψ meets the detector’s localized conjugate x₄-image ψ* at the detection event. The geometric meeting reorients the particle’s free-quantum participation in x₄-expansion into a bound, localized configuration in the detector’s matter. As with the photon, the post-detection alpha is no longer a free participant in x₄-expansion: it is absorbed, its kinetic energy deposited into ionization or excitation of the detector’s atomic structure, the free-particle wavefunction terminated. The “rotation out of x₄” is geometrically the same operation as in the photon case, applied here to a particle that had a (partial) x₄-participation rather than a (full) x₄-participation.

(iv) **Born rule probability as Wick rotation algebraic signature.** The probability of detection at angle θ is |ψ(θ, t_det)|² = ψ*(θ, t_det) ψ(θ, t_det). The squaring is the algebraic signature of the rotation out of x₄: the i in the wavefunction’s phase (encoding x₄-perpendicularity) is removed by the modulus-squaring (the Wick rotation at the amplitude level, Theorem 12.2). The result is a real-valued probability density on the spatial slice — the spatial-slice observable that the laboratory records.

(v) **Collapse of unmeasured angles as completion of the rotation.** At the moment of detection at angle θ, the wavefunction at every other angle collapses to zero (Corollary 11.4). The dx₄/dt = ic framework’s reading: the alpha particle’s x₄-expansion is a single coherent four-dimensional structure; when the particle is rotated out of x₄ at one angle (the detector), the expansion structure terminates at that angle, and the spatial-slice projection at every other angle drops to zero because the underlying x₄-expansion no longer exists as a spreading entity. The particle has been rotated out of x₄ in toto across the entire spatial slice.

The alpha case differs from the photon case in two respects: the alpha has a timelike worldline (u^μ u_μ = −c² rather than 0), and the absorbed alpha’s kinetic energy is deposited as ionization tracks in the detector’s matter (e.g., scintillator pulses, semiconductor electron-hole pairs, gas-proportional-counter ionization) rather than as a single bound-electron transition. The mechanism is the same: free-quantum x₄-expansion participant absorbed and bound into detector matter, the wavefunction’s i removed by the modulus-squaring because the free particle no longer exists.

#### 12.6.3 The universal mechanism

Both canonical cases instantiate the same mechanism. The wavefunction’s i is the imprint of the particle’s participation in x₄-expansion. The participation is full for photons (null worldline, rides the wavefront at c) and partitioned for massive particles (timelike worldline, x₄-component at rate dx₄/dt = ic). At measurement, the participation ends — the photon is annihilated, the massive particle is absorbed and bound into the detector. In neither case does the post-measurement system continue as a free quantum participating in x₄-expansion in the way the pre-measurement particle did. The i is removed from the description by the modulus-squaring because the i-bearing entity has been removed by the absorption.

The exponent 2 in the Born rule is the algebraic signature of this rotation. The rank-2 character of the Minkowski metric (Lemma 2.5) and conservation under the propagation it induces (Lemma 7.1) force the bilinear product ψ*ψ as the unique sesquilinear invariant available for the probability density. Both squarings — the metric squaring of dx₄/dt = ic into ds² = −c²dt² + spatial (Lemma 2.5) and the amplitude squaring of ψ into |ψ|² (Theorem 7.4) — are the same geometric operation: removal of the i-marker for x₄-perpendicularity, applied at the kinematic level (rate squaring) and at the amplitude level (wavefunction squaring) respectively. Theorem 12.2 identifies the physical event at which the amplitude-level squaring occurs: the measurement event, at which the particle is physically rotated out of its participation in x₄-expansion.

The photon case makes the universality of the mechanism most visible because no rest-frame alternative is available for the photon. Whatever happens to a photon at absorption *cannot* be a Lorentz boost to a rest frame — there is no photon rest frame. The photon either participates in x₄-expansion at c or it does not exist as a photon at all. The mechanism the dx₄/dt = ic framework supplies for “what happens at measurement” must therefore be of a kind that applies equally to a particle with no rest frame (photon) and to a particle with a rest frame (alpha, electron, neutron). The rotation-out-of-x₄ reading meets this criterion: the photon’s full x₄-participation is removed at absorption; the massive particle’s partial x₄-participation is removed at absorption; in both cases the wavefunction’s i — the imprint of participation — is removed by the modulus-squaring; in both cases the spatial-slice record is established by the absorbing apparatus’s physical change.

This is the dx₄/dt = ic framework’s universal reading of measurement: the particle is rotated out of the x₄-expanding perpendicularity, the wavefunction’s i-bearing character is removed by the algebraic signature of the rotation (modulus squaring), and the spatial-slice record is established by the apparatus’s physical change. Every photodetection, every alpha track, every electron click, every photon registration in the empirical record of twentieth- and twenty-first-century physics is, in this reading, a physical Wick rotation — a particle annihilated or absorbed out of its participation in x₄-expansion, with the squared amplitude on the spatial slice the real-valued macroscopic record of that physical rotation.

### 12.7 The ensemble Born rule and the emergent disappearance of i: thermodynamics as the macroscopic-scale Wick rotation

§12.5 identified the single measurement event as the physical Wick rotation at a single particle (Theorem 12.2). §7.9 supplied the two-particle head-on x₄-collision mechanism for that single event (Theorem 7.7). In a macroscopic ensemble — a gas of N ∼ 10²³ particles undergoing on the order of 10⁹–10¹⁵ pairwise collisions per second per particle in a typical thermodynamic system — the head-on x₄-collision is occurring at a total rate Γ_total of order 10³²–10³⁸ events per second per macroscopic sample. Each event is a physical Wick rotation at the colliding pair. The cumulative effect on the macroscopic description of the ensemble is the emergent disappearance of the i-marker for x₄-perpendicularity: the post-collision spatial-slice records, accumulated across the ensemble, constitute a fully i-free real-valued macroscopic description — classical statistical mechanics and thermodynamics. The standard mathematical Wick rotation t → -iτ, which converts the quantum-mechanical path-integral weight exp(iS/ℏ) into the classical-statistical-mechanical Boltzmann weight exp(-S_E/ℏ), is in this reading the formal abstraction of the cumulative physical Wick rotation performed by the ensemble at rate Γ_total.

**Theorem 12.4 (Statistical-cumulative Wick rotation: thermodynamics as the macroscopic-scale physical Wick rotation).** *Let an ensemble of N free quantum particles of mass m, density ρ, and mean spatial speed v undergo pairwise McGucken-sphere head-on collisions at total rate Γ_total = (1/2) · N · ρ σ v, with σ the relevant scattering cross-section. By Theorem 12.2 and Theorem 7.7, each collision is a physical Wick rotation at the colliding pair, removing the i-marker for x₄-perpendicularity from both colliding particles’ descriptions and depositing a real-valued spatial-slice configuration record at the collision event. Then for sufficiently large N · T (the thermodynamic limit, with T the time interval of observation), the cumulative macroscopic spatial-slice configuration record is:*

*(i) i-free and real-valued (the i-marker for x₄-perpendicularity has been removed at every collision event, with the cumulative description over all Γ_total · T events being entirely real-valued);*

*(ii) governed by classical statistical-mechanical equations — Boltzmann’s H-functional H = ∫ f log f d³v decreasing monotonically toward equilibrium, Maxwell-Boltzmann velocity distribution at equilibrium, the second law dS/dt ≥ 0 — with the irreversibility supplied by the one-way character of the rotation-out-of-x₄ at each collision (Theorem 12.2);*

*(iii) the macroscopic-scale physical realization of the standard mathematical Wick rotation t → -iτ; the latter is performed once on the path integral as a coordinate substitution, the former is performed Γ_total times per second across the ensemble as a sequence of physical events.*

**Proof.**

(1) By Theorem 12.2 (steps (5)–(6)), each measurement event removes the i from the participating particle’s amplitude by the modulus-squaring ψ → ψ^*ψ. By Theorem 7.7 (clause (iii)), each measurement event is the head-on x₄-collision of two McGucken spheres, with the x₄-momenergy cancelling and being redeposited as 3-spatial momenergy at the collision point. The amplitude-level i-removal of Theorem 12.2 and the geometric rotation-out-of-x₄ of Theorem 7.7 are two descriptions of the same single physical event.

(2) For an ensemble of N particles at density ρ with mean speed v and pairwise collision cross-section σ, the per-particle collision rate is ν_coll = ρ σ v (the standard mean-free-path collision rate from kinetic theory). The total ensemble collision rate is Γ_total = (1/2) N ν_coll = (1/2) N ρ σ v (the factor 1/2 because each collision involves two particles). For air at STP (N ∼ 6 × 10²³ per mole, ρ ∼ 2.5 × 10¹⁹ molecules per cm³, v ∼ 5 × 10⁴ cm/s, σ ∼ 4 × 10⁻¹⁵ cm² for N₂-N₂ collisions), Γ_total ∼ 10³⁴ collisions per second per mole.

(3) Each collision deposits a spatial-slice configuration record (the two-particle outgoing momenta and positions on the spatial slice at the collision event, with the post-collision momenta determined by the elastic-collision kinematics). The record is i-free: the post-collision particles’ four-velocity budget has been rotated from x₄-dominated to spatial-dominated (Theorem 7.7 (iii)), with the i-marker for x₄-perpendicularity removed by the modulus-squaring (Theorem 12.2 (5)).

(4) Over time T, the cumulative spatial-slice configuration record across the ensemble is the time-integrated histogram of all Γ_total · T collision outcomes. In the limit N · T → ∞ (the thermodynamic limit), this histogram converges to the equilibrium statistical-mechanical distribution. For a dilute gas of identical particles with two-body elastic collisions, the convergence is the content of Boltzmann’s H-theorem: H = ∫ f log f d³v decreases monotonically, with the Maxwell-Boltzmann distribution f(v) = (m/(2π k_B T))^{3/2} exp(-mv²/(2k_B T)) the equilibrium attractor at which H ceases to decrease. The Maxwell-Boltzmann distribution is i-free and real-valued, observable as the velocity distribution of the macroscopic gas — establishing (ii).

(5) The second law of thermodynamics, dS/dt ≥ 0 along the macroscopic time-evolution (with S = -k_B ∫ f log f d³v the Gibbs-Boltzmann entropy), is the statement that the cumulative configuration record approaches equilibrium and remains there once attained. The irreversibility is supplied by the one-way character of each collision’s rotation-out-of-x₄: once two free quanta have collided and been deposited as a spatial-slice record, no reverse process within the ensemble’s microscopic Schrödinger dynamics can recover the pre-collision free-quantum state — because the post-collision particles are no longer free participants in x₄-expansion in the way the pre-collision particles were. The arrow of time at the thermodynamic level is the cumulative arrow of these collision events.

(6) The standard mathematical Wick rotation t → -iτ, acting at the path-integral level, converts exp(iS/ℏ) → exp(-S_E/ℏ). The transformed path integral defines classical statistical mechanics with Boltzmann weights — the very statistical mechanics that steps (4)–(5) realized as the macroscopic limit of the ensemble. The mathematical Wick rotation is therefore the formal abstraction of the cumulative physical Wick rotation performed by the ensemble. A single coordinate substitution at the formalism level corresponds to Γ_total · T physical events at the ensemble level; the formalism’s “single coordinate change” is the empirical “ensemble-amplified Born rule” performed across all colliding pairs at rate Γ_total — establishing (iii). ∎

**Remark 12.5 (the Wick rotation “exalted Γ_total times per second”).** The standard mathematical Wick rotation is a single coordinate substitution, performed once at the path-integral level. The physics of this substitution — removal of the i-marker for x₄-perpendicularity from the action — is, in the McGucken dx₄/dt = ic framework, the physics of a single measurement event (Theorem 12.2). In a macroscopic ensemble, the same physical operation is performed by every collision event at total rate Γ_total ∼ 10³⁴ s⁻¹ per macroscopic sample. The macroscopic appearance of thermodynamics — its complete absence of i in any equation, its real-valued thermodynamic potentials, its real-valued entropy, its real-valued Maxwell-Boltzmann distribution — is the cumulative effect of this ensemble-amplified physical Wick rotation. Thermodynamics is, in this reading, **the Wick rotation exalted Γ_total times per second** by the ensemble’s Born rule events. The well-known correspondence between Wick-rotated quantum mechanics and classical statistical mechanics is restated here with a physical mechanism for the correspondence: each Born rule event at every collision in the ensemble is itself a physical Wick rotation, and the macroscopic statistical mechanics is the cumulative effect of all of them.

**Remark 12.6 (resolution of the “two arrows of time” puzzle).** A long-standing question in the foundations of thermodynamics: why is there a macroscopic arrow of time (entropy increases monotonically) when the underlying microscopic equations (the Schrödinger evolution of Theorem 9.1, the unitary Schrödinger flow of Theorem 9.2, Hamilton’s equations for the classical limit) are time-symmetric? The McGucken dx₄/dt = ic framework’s answer: the microscopic time-symmetric evolution is the description *between* measurements. Each measurement event is irreversible — the rotation-out-of-x₄ at a collision (Theorem 7.7, Theorem 12.2) deposits a spatial-slice record that cannot be undone by reversing the Schrödinger equation, because the post-collision state is no longer a free quantum participating in x₄-expansion in the way the pre-collision state was. The thermodynamic arrow of time is therefore the cumulative arrow of all measurements in the ensemble. The second law’s increasing-entropy direction is the direction in which more measurements have accumulated — equivalently, the direction in which more physical Wick rotations have been performed. The “two arrows” — the time-symmetric microscopic dynamics and the time-asymmetric macroscopic thermodynamics — are reconciled: the latter is the macroscopic record of the former’s interruption by measurement events, with the interruptions one-way (rotation-out-of-x₄ is irreversible) and the cumulative count of interruptions growing monotonically with parameter time.

**Remark 12.7 (spherically symmetric emission as direct evidence of x₄-expansion nonlocality).** That a radioactive sample emits its decay products spherically symmetrically in space — equally probable in every spatial direction, with no preferred axis once the sample’s orientation is averaged or the emitter’s orientation is isotropic by construction — is direct empirical evidence of the dx₄/dt = ic framework’s reading. The spherical symmetry is the spatial-slice projection of the isotropic x₄-expansion (canonical clause 3, §2.4) from the emission event. The nonlocal character of the pre-detection wavefunction — its spread over a sphere of progressively larger radius as proper time advances — is the spatial-slice projection of the particle’s continuing participation in the active x₄-expansion. The probability distribution of detection events across many emissions reproduces the spherical symmetry of the x₄-expansion exactly: equally many detections per unit solid angle in every direction, with the probability per unit volume at radius r decreasing as 1/r² (geometric thinning of the spherical wavefront) as the wavefront expands. Each individual detection is one Born rule event — one head-on x₄-collision (Theorem 7.7) — and the cumulative statistics of many such detections is the empirics of the wavefunction’s |ψ|² density.


### VIII.4 Gravity is the Born rule: one Haar measure of the Sphere, read at the event and over the horizon

The McGucken Principle dx₄/dt = ic predicts that the Haar measure of Lemma 7.1.5 — the unique SO(3)-invariant probability measure on the Sphere — evaluated at a single event is the Born rule and integrated over a horizon is the Bekenstein–Hawking entropy, so that gravity and the Born rule are the same count of x₄-states on one Sphere. Section 10.12duodecies of [1] is reproduced here.


#### 10.12duodecies Gravity is the Born rule: both are the count of x₄-states on the expanding Sphere

Two connections are well established in the literature and are separately reproduced in this framework: gravity is entropy, and the Born rule is entropy. The first is the thermodynamic derivation of the field equations — Jacobson’s δQ = TδS on local causal horizons, Verlinde’s entropic force, Padmanabhan’s equipartition, the entanglement-equilibrium school (Jacobson 2015; Bueno–Min–Speranza–Visser; Alonso-Serrano–Liška), and the recent quantum-relative-entropy action of Bianconi (*Gravity from entropy*, Phys. Rev. D 111, 066001, 2025). The second is the identification of the Born rule with an entropy or information geometry — Zurek’s derivation from entanglement-assisted invariance (envariance) (Phys. Rev. Lett. 90, 120404, 2003; Phys. Rev. A 71, 052105, 2005), Fivel’s derivation from information-entropy axioms with an entropy-reduction axiom (arXiv:1010.5300; Found. Phys. 42, 291, 2012), Ojima–Okamura–Saigo’s derivation from algebraic and statistical axioms on von Neumann algebras (arXiv:1304.6618), Chiribella–D’Ariano–Perinotti’s operational reconstruction from purification and information axioms (Phys. Rev. A 84, 012311, 2011), Carcassi and Aidala’s equivalence of the Born rule over pure states with the von Neumann entropy over mixed states (Assumptions of Physics, 2026), the derivation of the Born weights by relative-entropy minimization (“Born’s Rule from Contextual Relative-Entropy Minimization,” Entropy 27, 898, 2025), and the Fubini–Study = Fisher–Rao lineage from Wootters (1981) onward that makes the Born rule the unique map equating the state-space metric to the statistical metric. What no work in either literature does is close the triangle: gravity is entropy and the Born rule is entropy, but no established result states that gravity is the Born rule. The reason is derivational, and it is what the McGucken Principle removes.

*Why the triangle stays open in the standard treatment.* The two entropy-connections use two different, independently-posited entropies. The gravitational side uses a horizon or geometric entropy — Bekenstein–Hawking area entropy, or entanglement entropy across a causal diamond. The Born side uses a state-space entropy — von Neumann entropy of a density matrix, or relative entropy on the observable algebra. These are distinct objects living in distinct spaces (a horizon in spacetime; a density matrix in Hilbert space), related only by name. With two different entropies, the transitive step gravity = entropy = Born rule cannot be completed: the entropy on the left is not the entropy on the right. The single work that comes closest, Munkhammar’s “Is Holographic Entropy and Gravity the result of Quantum Mechanics?” (arXiv:1003.1262), inserts the Born density |ψ|² as a source for the holographic entropy in Verlinde’s construction, but uses the Born density as an input to entropic gravity rather than identifying the two, and leaves the relativistic origin open. Süzen (arXiv:1612.00288) similarly couples Verlinde’s entropic gravity to Diósi–Penrose gravity-induced collapse, relating the gravitational constant to the quantum state, again a coupling rather than an identification. In the opposite direction, Valentini (“Beyond the Born Rule in Quantum Gravity,” Found. Phys. 52, 2022) argues that at the fundamental Wheeler–DeWitt scale the Born rule does not hold and emerges only in the semiclassical regime — a position the present framework answers directly, since here the Born rule is the invariant measure of the Sphere at every event and holds wherever dx₄/dt = ic generates a Sphere, which is everywhere, with the semiclassical horizon regime being the integrated rather than the local reading of the same measure.

*The McGucken identification.* In this framework both entropies are one physical quantity: the count of x₄-advance states on the expanding McGucken Sphere Σ₊(p), generated at every event p by dx₄/dt = ic and carrying the unique SO(3)-invariant Haar measure (Theorem 7.2). The Born rule is that Haar measure evaluated at the event: the Sphere-to-Hilbert cogeneration makes the inner product and the Born probability p = |⟨ψ|φ⟩|² the Haar measure of Σ₊(p) read as a probability measure on rays, so |ψ|² is the measure of the Sphere restricted to the point-event. Gravity is the same Haar measure integrated over the horizon: the Bekenstein–Hawking entropy S = A/4ℓ_P² is the count of Planck-scale Spheres tiling the horizon 2-surface (§10.12ter, §10.12decies; refs. [37], [38]), one x₄-stationary mode per Planck area, and the Hawking temperature is the near-horizon compactification of the Euclidean-section x₄-axis (the McGucken–Wick rotation, [3]). Verlinde’s entropic gravity is then the horizon-scale statement of the same measure that gives the Born rule at the event scale. It would be an oversimplification to assign gravity to the Geometric Channel and the Born rule to the Algebraic Channel of the McGucken Duality, as though the identification were a cross-channel bridge — one physical fact reached by two mathematical routes that meet by external construction. Both channels derive both quantities, and this four-corner completeness is what places the identification below the channel decomposition, at the level of the Sphere itself. In the Geometric Channel, the Sphere gives gravity through its null hypersurfaces and the Jacobson relation δQ = TδS (Verlinde, Jacobson, Padmanabhan), and it gives the Born rule through the Fubini–Study metric on its rays, which Wootters identifies with the Fisher–Rao statistical distance. In the Algebraic Channel, the Sphere gives gravity through the metric read as a quantum operator whose quantum relative entropy is the gravitational action reducing to Einstein–Hilbert in the low-coupling limit (Bianconi), and it gives the Born rule through its SO(3)-Haar measure pulled back to Hilbert-space rays as p = |⟨ψ|φ⟩|². Each channel independently sees both facts from its own vantage; if a channel gave only one endpoint, gravity = Born rule would be a cross-channel coincidence, but the four-corner completeness shows both quantities are facts about the shared Sphere and its Haar measure, so every channel that accesses the Sphere sees both. The channel-independence is what places the equality at the Sphere level rather than at the channel level: gravity and the Born rule are the same fact about Σ₊(p), before any channel decomposition, and the Duality’s two channels are two confirmations of it rather than its two halves. The entropy that links them is one entropy, S = klnΩ, where Ω is the number of x₄-advance states the Haar measure distributes over — the same Ω whose horizon projection is the gravitational entropy. The chain closes:


gravity = Haar measure of Σ₊ integrated over the horizon ⟷ S = klnΩ ⟷ Haar measure of Σ₊ evaluated at the event = Born rule.


Gravity is the Sphere’s Haar measure integrated over the horizon; the Born rule is the Sphere’s Haar measure evaluated at the event; both are measure-theoretic readings of the one physical fact dx₄/dt = ic at different scales of integration. This is the transitive step the literature cannot take, and the framework takes it not by a new postulate but because it has a single physical measure — the Haar measure of the Sphere at every event — where the standard treatment has two coincidentally-named entropies.

*Scope.* What is derived independently is each endpoint: gravity from the horizon mode-count (the Jacobson route on the Sphere, §10.12ter, with S = A/4ℓ_P² from [37], [38]), and the Born rule from the surface invariant measure (Theorem 7.2). The identification gravity = Born rule is the transitive consequence of both being the same x₄-state count on the one Sphere — the gravitational entropy is the boundary reading and the Born measure the surface reading of a single Ω. The claim is that the two entropy-connections of the literature, kept separate there by using two different entropies, are one connection here because the framework’s entropy is a single physical count; it is a unification of the two established results, not an additional posit.


## Part IX. What the McGucken derivation supplies that the prior programmes could not: the count of inputs, the convergent overdetermination of the exponent, and the physical referent of the complex amplitude

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts three measurable differences between its derivation of the Born rule and every derivation surveyed in Part IV, and each difference is a counting fact or a theorem rather than a preference.

### IX.1 Simpler: the count of independent inputs

The input list of the McGucken derivation is one physical statement, Principle 2.1: dx₄/dt = ic with action ħ per oscillatory step of x₄. The input lists of the prior programmes are longer, and the count is documented in Part IV for the two strongest of them. Masanes–Galley–Müller (2019) begin from six independent postulates — a complex separable Hilbert space, unitary reversible transformations, tensor-product composition, the OPF formalism with its closure properties, the ⋆-product axioms including associativity, and the possibility of state estimation (§7.1.9.A) — and each of the six is a theorem of the Principle: the Hilbert space is Theorem 6.1 of [1], unitarity is x₄-flux conservation (Theorem 9.2 of [1]), the tensor product is Fubini–Tonelli on independent x₄-expansions (Corollary 11.6 of [1]), associativity is the associativity of that product structure, and state estimation is the finite dimension d² - 1 of the operator algebra on the Sphere (§7.1.9.B). Neumaier's Detector Response Principle (2025) compresses eight commitments into one name — the Hilbert space, the density-operator trace pairing, time as evolution parameter, source stationarity, discrete detection events, a finite label set K, the operators Pₖ, and the primitive notion of a measurement device (§7.1.16) — and each of the eight is derived in the McGucken dx₄/dt = ic framework from the Sphere: the detector is a region where x₄-expansion is absorbed, the detection event is the head-on collision of two Spheres (Theorem 7.7), and the rule is the collision rate. The reciprocal test of §7.1.9.B fixes the direction of depth: the Principle derives all six Masanes–Galley–Müller inputs, and operational axioms about outcome probability functions contain no statement about what the fourth dimension is doing and so cannot derive the Principle.

### IX.2 More robust: five routes to the exponent with no shared machinery

The exponent 2 is fixed five times over, and the five derivations share only the Principle and the Sphere (Remark 7.17 of [1], the twenty-step table and the closing paragraph of §7.10 above). The Conservation Route reads the exponent as the one that x₄'s expansion conserves: the Sphere's weight is conserved along its advance, and under the Klein–Gordon propagation only the quadratic function of the modulus is conserved, the rank-2 character of (ic)² = -c² entering through the second order of that equation (Lemma 7.1). The Haar Route reads the existence of a probability measure at all as the uniqueness of the SO(3)-invariant measure on the homogeneous space SO(3)/SO(2) = S² (Lemma 7.1.5), a measure that Minkowski's scalar constraint u^μ u_μ = -c² cannot supply because a scalar constraint carries no group action (Remark 7.1.5a). The Norm Route reads the exponent from the parallelogram identity, obtained by two lines of algebra from rank-2 sesquilinearity without the Jordan–von Neumann theorem as input (Lemma 7.6), and from the Lᵖ computation showing that unitary evolution conserves the norm for p = 2 alone (§7.5). The Collision Route reads the exponent as the number of physical participants in a detection event, two Spheres meeting head-on, with sum, maximum, minimum and the arithmetic, geometric and harmonic means excluded by action-additivity and the conjugation forced by the sesquilinear complexification of a symmetric form together with (R1) (Theorem 7.7, Lemma 7.7.5, Corollary 7.7.6). The PT-Symmetry Route reads complex conjugation as the Sphere's reflection through its source event, ψ(PT_E · event) = ψ^*(event), verified exactly on plane-wave components and extended by linearity (Theorem 7.11). A challenge to any one route leaves the other four standing; this is the convergent-overdetermination property of the McGucken Quantum Formalism (Lemma 15.1 of [MG-MQF], Theorem VII.1 of [MG-Foundations]) applied to the Born rule. Gleason's theorem, by contrast, has one route, and that route presupposes the lattice of closed subspaces of a complex Hilbert space; Lesovik's unitarity argument has one route, and it presupposes the Hilbert space on which the unitary group acts (§7.5).

### IX.3 More natural: the referent of the complex amplitude and the mechanism of the detection event

Schrödinger wrote to Lorentz on 6 June 1926 that the use of complex numbers was "directly to be objected to" and that Ψ "is surely fundamentally a real function" (§7.1.9.D). Every programme of Part IV begins from a complex Hilbert space and therefore begins after the point at which Schrödinger's objection was raised. The McGucken dx₄/dt = ic framework answers the objection at its own level: the imaginary unit in ψ is the marker of the one axis perpendicular to x₁x₂x₃, selected by the Frobenius theorem from {ℝ, ℂ, ℍ} because there is exactly one such axis (Theorem 3.1), and the element of reality the amplitude describes is the fourth dimension expanding at c with action h per Compton cycle (§2.2.bis). The same answer supplies the mechanism Born's footnote lacked. Born reached the square from the intensity of a spherical wave in pre-existing 3-space (§7.7.2); the McGucken Sphere is the wavefront whose intensity Born was reading, and its rank-2 metric is why the intensity is a square. The detection event, left as a primitive in Born 1926, in the Davies–Lewis POVM formalism and in Neumaier's device definition, is here a definite event in spacetime: the head-on collision of the emitter's and the absorber's Spheres, with x₄-momenergy cancelling and reappearing in x₁x₂x₃ (Theorem 7.7(iii)), the same event that Theorem 12.2 identifies as the physical Wick rotation and that Theorem 16.7 locates in the Geometric Channel.

### IX.4 Attribution by record item

Each item of the record established in this paper is a theorem of the McGucken Principle dx₄/dt = ic, derived in [1] and reproduced above; the attribution is listed item by item.

- The four requirements (R1)–(R4) and the uniqueness of P = |ψ|² under them: Theorem 7.2 of [1], with (R1)–(R2) from Sphere overlap and collision counting (Theorems 7.4, 7.7), (R3) from the universality clause of the Principle (Theorem 2.4(iv)), and (R4) from the rank-2 metric of Lemma 2.5 via Lemma 7.1 — the dx₄/dt = ic Algebraic Channel derivation.
- The exclusion of |ψ|, |ψ|³, ψ², (ψ^*ψ)² and Aaronson's |ψ|⁴/∑ⱼ|ψⱼ|⁴: §7.6 and Lemma 7.1 of [1].
- The unique SO(3)-invariant probability measure on the Sphere: Lemma 7.1.5 of [1].
- The parallelogram identity without Jordan–von Neumann as input, and the L² norm as the unique unitarily conserved Lᵖ norm: Lemma 7.6 and §7.5 of [1].
- The geometric meaning of ψ^*ψ as the overlap of forward and conjugate x₄-expansions, with diagonal and interference terms: Theorem 7.4 of [1] — the dx₄/dt = ic Geometric Channel derivation.
- The physical referent of the conjugate Sphere as the absorber's forward Sphere seen from the emitter's frame, and the Born rule as the head-on x₄-collision rate: Theorem 7.7, Lemma 7.7.5, Corollary 7.7.6 of [1].
- Complex conjugation as PT_E reflection through the source event, exact for every McGucken-derived wavefunction: Theorem 7.11 of [1].
- Single-slit and double-slit interference as multi-Sphere self-overlap at the detector: Theorem 7.12 of [1].
- The Dirac–von Neumann measurement axiom as Theorem 7.2 restated in an arbitrary eigenbasis: Corollary 11.3 of [1].
- The convergence of the two channels on the rule, and the identification of the squaring dx₄/dt = ic → (ic)² = -c² with the squaring ψ → |ψ|²: §7.12 of [1].
- The channels themselves: the projection Π_A (§16.2), the position-of-i diagnosis (§16.3), Theorems 16.1–16.3, Lemmas 16.3.1–16.3.2, Corollaries 16.4–16.5 of [1]; the two positions relative to the wavefront, §9.5.13 of [1].
- Every measurement event as a +ic-oriented Sphere collision in the Geometric Channel, and the dissolution of the orthodox measurement problem: §16.19 and Theorem 16.7 of [1].
- Measurement as physical Wick rotation and thermodynamics as the rotation performed Γₜₒₜₐₗ times per second: Theorems 12.2 and 12.4 of [1].
- Gravity and the Born rule as one Haar measure of the Sphere read over the horizon and at the event: §10.12duodecies of [1].
- The diagnostic across the sixteen prior programmes, the sphere traditions, and Born's own route: §§7.1, 7.7, 7.7.1, 7.7.2 of [1].


## Part X. The McGucken Principle dx₄/dt = ic Reading of the notable features of the McGucken derivation of the Born rule

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts the Born rule P = |ψ|² as a theorem, and the derivation reproduced in Parts V through VIII has six features that no derivation surveyed in Part IV has. Each is stated here in full, with the theorem of [6] that carries it, so that the record of Part IX.4 can be read as a set of physical statements and not as a list of theorem numbers.

### X.1 The McGucken Principle dx₄/dt = ic Reading of the single input: the Hilbert space, the complex field and the unitary group are derived before the rule

The McGucken Principle dx₄/dt = ic predicts the arena of the rule as well as the rule. Gleason (1957) derived the trace form of every measure on the closed subspaces of a Hilbert space of dimension at least three, taking the Hilbert space as given (§7.1.2). Jordan and von Neumann (1935) characterized the inner-product spaces among the normed spaces by the parallelogram identity, taking the normed space as given. Lesovik (2014) derived the exponent 2 from the requirement that unitary evolution conserve the total probability, taking the unitary group as given (Part V.1, the closing remark on Lemma 7.1). Masanes, Galley and Müller (2019) derived the rule from six postulates, the first of which is the complex separable Hilbert space itself (§7.1.9.A). In the McGucken derivation the Hilbert space is the completion of the x₄-projections of the expanding Sphere (Theorem 6.1 of [6]); the field is complex because x₄ = ict carries the imaginary unit as the marker of the one axis perpendicular to x₁x₂x₃, selected by the Frobenius theorem (Theorem 3.1 of [6]); the unitary group is the conservation of the Sphere's weight — in standard terms the conservation of total probability, or of x₄-flux — under its expansion (Theorem 9.2 of [6]). Part IX.1 counts the inputs: Principle 2.1 alone. Every programme of Part IV begins at a point the Principle has already reached.

### X.2 The McGucken Principle dx₄/dt = ic Reading of the exponent 2 as fixed by routes sharing no intermediate machinery

The McGucken Principle dx₄/dt = ic predicts the exponent 2 by four derivations that share only the Principle and the Sphere, and Part IX.2 states them with their theorems. The Conservation Route: the Klein–Gordon equation on the Sphere wavefront (Theorem 9.0 of [6]) gives positive-energy propagation W(t); the Sphere's weight is conserved along its advance (Lemma 6.6C of [25]); Lemma 7.1 proves that a conserved functional ∫ F(|ψ|) d³x of that propagation has F(s) = κ s², so that |ψ|ᵖ with p ≠ 2 fails conservation and the renormalized quartic rule |ψ|⁴/∑ⱼ |ψⱼ|⁴, Aaronson's alternative, fails the finite rate c (Theorem 7.6C). The Norm Route: the sesquilinear inner product on the derived Hilbert space gives the parallelogram identity by two lines of algebra (Lemma 7.6) and the L² norm as the unique Lᵖ norm that unitary evolution conserves (§7.5). The Haar Route: Lemma 7.1.5 states that "there exists a unique SO(3)-invariant Borel probability measure" on the Sphere, the uniform measure dΩ/4π, and Remark 7.1.5a states why this is the measure a probability rule needs: "a measure is physically forced only if a symmetry singles it out uniquely. Minkowski's four-velocity norm u^μ u_μ = -c² carries no group action and therefore no such measure." The Collision Route: Theorem 7.7(iv), "The local rate of the head-on collision event at P is the sesquilinear product ψ_A(P)·ψ_B^*(P) up to a positive normalization constant," with the product form derived in Lemma 7.7.5 Step 1 from the additivity of action over independent paths, which excludes the sum, the maximum, the minimum and the arithmetic, geometric and harmonic means. The routes agree on 2, and a reader who rejects one of them has three others to reject.

### X.3 The McGucken Principle dx₄/dt = ic Reading of the two channels: the form fixed in the Algebraic Channel and the mechanism supplied in the Geometric Channel

The McGucken Principle dx₄/dt = ic predicts the rule twice, once in each channel of the McGucken Duality, and the two derivations agree (§7.12 of [6], Part VIII.1). In the dx₄/dt = ic Algebraic Channel the density is fixed by four requirements: it is real (R1) and non-negative (R2) because it counts detection events; it is invariant under a global phase (R3) because a global phase is a shift of the x₄-origin and the expansion is the same from every event (Theorem 2.4(iv) of [6]); it is bilinear in (ψ, ψ^*) (R4) by locality with conservation under x₄'s expansion (Lemma 7.1). Theorem 7.2 states: "The unique density P: ℝ³ → ℝ_(≥ 0) satisfying (R1), (R2), (R3), (R4) is" P(x) = |ψ(x)|². In the dx₄/dt = ic Geometric Channel the same density is a geometric object. Theorem 7.4 states: "The Born density P = ψ^*ψ at an event B is the geometric overlap, at B, of the forward x₄-expansion (carrying phase from x₄ = ict) and the conjugate x₄^*-expansion (carrying phase from x₄^* = -ict)." The Algebraic Channel answers which function of ψ the probability is; the Geometric Channel answers what physical process the function measures. The projection Π_A of Theorem 16.3 of [6] carries the second answer to the first by setting aside the orientation of +ic, and Corollaries 16.4–16.5 state that the equation belongs to both channels while the detection event belongs to the Geometric Channel.

### X.4 The McGucken Principle dx₄/dt = ic Reading of the complex conjugate as a physical object

The McGucken Principle dx₄/dt = ic predicts a referent for ψ^*, which in every programme of Part IV is an algebraic operation on a given amplitude. Theorem 7.7(ii) of [6] states: "The conjugate kernel ψ^* of Definition 7.3 is therefore the absorber's forward x₄-expansion viewed in the emitter's frame; equivalently, ψ is the emitter's forward x₄-expansion viewed in the absorber's frame." The two Spheres meet antiparallel in x₄ (Theorem 7.7(i)), and the antiparallel signs realize the conjugation i ↔ -i. For a single particle propagating before any absorber is specified, Theorem 7.11(ii) supplies the conjugate from the Sphere's own symmetry: "ψ(PT_E · event) = ψ^*(event), i.e. ψ(2x_E - x, 2t_E - t) = ψ^*(x, t), exactly for any McGucken-derived wavefunction," where PT_E is the reflection through the source event E, the unique discrete symmetry of the Sphere's forward cone that preserves its isotropy (Theorem 7.11(i)). Complex conjugation is therefore either the other participant's Sphere seen from this one, or this Sphere reflected through its own source; in both cases it is a Sphere.

### X.5 The McGucken Principle dx₄/dt = ic Reading of the detection event as a physical Wick rotation

The McGucken Principle dx₄/dt = ic predicts what happens at the event where the probability is realized. Theorem 12.2 of [6] states that "the measurement event at E corresponds to the physical realization of the Wick rotation x₄ = ict ⟶ x₄^W := -ix₄ = ct at the particle's worldline at E, with the wavefunction's i-bearing complex amplitude ψ rotated into the real-valued spatial-slice probability density |ψ(E)|² = ψ^*(E)ψ(E)." The oscillatory factor e^(iS/ħ) along x₄ = ict becomes the real weight e^(-S/ħ) at the collision of the two Spheres; this is the rotation Wick performed on the integration contour, here performed by the event. Corollary 11.3 of [6] then restates Theorem 7.2 in an arbitrary eigenbasis, so that the Dirac–von Neumann measurement axiom — the probability of the outcome aₙ is |⟨ aₙ|ψ⟩|² — is a corollary of the position-space theorem, and Theorem 12.4 states thermodynamics as this rotation performed Γₜₒₜₐₗ times per second. Theorem 7.12 of [6] completes the Geometric Channel reading with interference: "every point Q ∈ A acts as the center of a new McGucken Sphere 𝓜_Q(t) of secondary wavefronts propagating at velocity c," and the single-slit and double-slit patterns are the self-overlap of these Spheres at the detector. McGucken differs from the Huygens–Fresnel–Kirchhoff tradition here in supplying the physical mechanism for Huygens' principle: x₄'s spherical expansion at c from every event, including every event in the aperture.

### X.6 The McGucken Principle dx₄/dt = ic Reading of gravity and the Born rule as one measure of the Sphere

The McGucken Principle dx₄/dt = ic predicts that the conserved weight of the Sphere, spread by the Haar measure over the wavefront of area 4π r², is read at the detection event as P = |ψ|² and over a horizon as the inverse-square law. §10.12duodecies of [6], reproduced in Part VIII.4, states gravity as the Born rule in this sense; Lemma 6.6C of [25] states the r⁻² fall-off of the Sphere's density as "obtained here from clause (ii) and C1 rather than assumed," and Chapter 14 of [25] obtains the Schwarzschild metric from dx₄/dt = ic, spherical symmetry, asymptotic flatness and Gauss's law for gravity without the field equations. No programme of Part IV connects its measure to gravitation, because none of them has a measure that is a property of spacetime.

### X.7 Attribution

Each feature is a theorem of the McGucken Principle dx₄/dt = ic: the single input, Principle 2.1 with Theorems 3.1, 6.1 and 9.2 of [6]; the exponent fixed by four routes, Lemma 7.1, Lemma 7.1.5, Lemma 7.6, Theorem 7.6C and Theorem 7.7(iv) with Lemma 7.7.5; the two channels, Theorems 7.2 and 7.4 with Theorem 16.3 and Corollaries 16.4–16.5; the referent of the conjugate, Theorem 7.7(ii) and Theorem 7.11(ii); the detection event, Theorems 12.2 and 12.4, Corollary 11.3 and Theorem 7.12; gravity and the Born rule as one measure, §10.12duodecies of [6] with Lemma 6.6C and Chapter 14 of [25].

## Part XI. The McGucken Principle dx₄/dt = ic Reading of what the Born rule, once derived, states about the physical world

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts the Born rule, and the derived rule in turn states six facts about the world that the postulated rule of Born (1926) left open. Each is a consequence of a named theorem, and each is stated here as the physics it asserts.

### XI.1 The McGucken Principle dx₄/dt = ic Reading of probability as a geometric density on the Sphere

The McGucken Principle dx₄/dt = ic predicts that the Born density |ψ|² is the density of a conserved quantity, the Sphere's weight — in standard terms the total probability, or the total x₄-flux — over the region the Sphere has reached. For a single free source the wavefront is the 2-sphere of radius r = ct about the source, the weight is spread over it by the unique SO(3)-invariant measure (Lemma 7.1.5 of [6]), and the density is W/4π r² (Lemma 6.6C of [25]), which is also Coulomb's law read on a charge and Newton's law read on a mass (Part VIII.4). For a general state the density is the overlap ψ^*ψ of Theorem 7.4, with ψ the superposition of the Spheres of every source event in the state's past; the single-source case is the special case in which that superposition has one term. In both cases the probability is a quantity carried by an expanding wavefront and measured at the event where it is read, which is what Born's footnote added in proof in 1926, replacing |ψ| by |ψ|² without a derivation (§7.1.1, §7.7.2), asserted without a carrier.

### XI.2 The McGucken Principle dx₄/dt = ic Reading of the detection event as the meeting of two Spheres

The McGucken Principle dx₄/dt = ic predicts that a probability is realized at an event where two Spheres meet: the emitter's forward Sphere and the absorber's Sphere, antiparallel in x₄ in each other's frames (Theorem 7.7(i) of [6]). The exponent 2 is the two participants (Theorem 7.7(iv), Lemma 7.7.5 Step 1), and the reduction to |ψ|² for a single particle is Theorem 7.7(v): "the absorber is well-modeled as a localized point at P whose McGucken sphere's forward x₄-expansion is, in the emitter's frame, the conjugate kernel ψ^*." The physical statement is that a measurement is a relation between two events, an emission and an absorption, and that the Born probability is bilinear because two Spheres meet. A third Sphere present at the event enters by superposition into ψ (Theorem 7.12), and the exponent stays at 2.

### XI.3 The McGucken Principle dx₄/dt = ic Reading of the conjugate amplitude and the orientation of time

The McGucken Principle dx₄/dt = ic predicts that ψ^* is the Sphere reflected through its source event, ψ(PT_E · event) = ψ^*(event) (Theorem 7.11(ii) of [6]), or equivalently the absorber's Sphere seen from the emitter (Theorem 7.7(ii)). The physical statement is that complex conjugation is the reversal of x₄, and that the Born rule multiplies the forward-oriented expansion by its x₄-reversed image at the same event. The sign +ic of the Principle fixes which of the two is the forward expansion; the orientation of time that Born's postulate does not mention is carried in the rule by that sign (Part III.3, Theorem 16.1 of [6]).

### XI.4 The McGucken Principle dx₄/dt = ic Reading of measurement as a rotation of x₄

The McGucken Principle dx₄/dt = ic predicts that the transition from the complex amplitude to the real probability is a rotation of the fourth dimension at the detection event, x₄ = ict → ct (Theorem 12.2 of [6]). The physical statement is that the collapse postulate of Dirac and von Neumann names an event in spacetime: the meeting of two Spheres at which the perpendicular axis x₄ is rotated into the real axis and the phase e^(iS/ħ) becomes the weight e^(-S/ħ). The same statement accounts for the agreement of Euclidean path integrals with Lorentzian ones — the rotation Wick performed on the contour is the rotation the event performs on x₄ (§12.4 of [6]) — and for thermodynamics as the rotation performed at the rate Γₜₒₜₐₗ of detection events per second (Theorem 12.4 of [6]).

### XI.5 The McGucken Principle dx₄/dt = ic Reading of why the Hilbert space is complex and why its measure is unique

The McGucken Principle dx₄/dt = ic predicts the complex field from x₄ = ict: the imaginary unit marks the one axis perpendicular to x₁x₂x₃, and the Frobenius theorem selects ℂ from {ℝ, ℂ, ℍ} because there is exactly one such axis (Theorem 3.1 of [6]). It predicts the uniqueness of the measure from the isotropy of the Sphere: SO(3) acts transitively on the wavefront, and a compact group has one invariant probability measure (Lemma 7.1.5 of [6]). The physical statement, in the words of Remark 7.1.5a, is that "Minkowski's four-velocity norm u^μ u_μ = -c² carries no group action and therefore no such measure": the norm is a magnitude, the Sphere is an object with a symmetry group, and probabilities require the object. Schrödinger's objection to Lorentz on 6 June 1926 that Ψ "is surely fundamentally a real function" (§7.1.9.D) is answered by naming what the imaginary unit marks.

### XI.6 The McGucken Principle dx₄/dt = ic Reading of interference without a separate wave postulate

The McGucken Principle dx₄/dt = ic predicts the single-slit and double-slit patterns as the self-overlap at the detector of the Spheres re-sourced at every point of the aperture (Theorem 7.12 of [6]), with the off-diagonal terms of Theorem 7.4 as the interference. The physical statement is that the particle is the apex of its Sphere and the wave is the wavefront of the same Sphere, so that wave–particle duality names two readings of one expanding object (Lemma 6.6 of [25], the apex and wavefront readings). McGucken differs from Huygens, Fresnel and Kirchhoff in supplying the physical mechanism for Huygens' principle — x₄'s spherical expansion at c from every event — where the tradition postulated the secondary wavelets.

### XI.7 Attribution

Each statement is a consequence of the McGucken Principle dx₄/dt = ic through a named theorem: probability as a geometric density, Lemma 7.1.5 of [6] and Lemma 6.6C of [25] with Theorem 7.4; the detection event as the meeting of two Spheres, Theorem 7.7(i), (iv), (v) and Lemma 7.7.5; the conjugate amplitude and the orientation of time, Theorem 7.11(ii), Theorem 7.7(ii) and Theorem 16.1; measurement as a rotation of x₄, Theorems 12.2 and 12.4 and §12.4; the complex field and the unique measure, Theorem 3.1, Lemma 7.1.5 and Remark 7.1.5a; interference, Theorem 7.12 and Theorem 7.4 with Lemma 6.6 of [25].

## Part XII. Conclusion

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The Born rule P = |ψ|² is a theorem of this Principle. Along the dx₄/dt = ic Algebraic Channel it is the unique density satisfying reality, non-negativity, global-phase invariance, and locality with conservation under x₄'s expansion, with every one of the four requirements supplied by a property of the McGucken Sphere and the exponent fixed by the conservation of the Sphere's weight under the Klein–Gordon propagation that x₄ = ict induces (Theorem 7.2). Along the dx₄/dt = ic Geometric Channel it is the overlap at the detection event of the forward and conjugate x₄-expansions (Theorem 7.4), the head-on collision rate of the emitter's and the absorber's Spheres (Theorem 7.7), and the product of the wavefunction with its reflection through the source event (Theorem 7.11). The two channels are related by the projection Π_A that retains the T-invariant algebra and sets aside the orientation of +ic (Theorem 16.3); the equation is T-invariant and belongs to both channels, and the detection event is +ic-oriented and belongs to the Geometric Channel (Corollaries 16.4–16.5). The century of derivations from Born 1926 to Neumaier 2025 operated inside the Hilbert space, which the Principle derives, and imported the measure, which the Principle supplies as the unique SO(3)-invariant measure on the Sphere. The question Schrödinger asked in June 1926 — what the complex amplitude refers to — and the question Born's footnote left open — why the square — have the same answer: the fourth dimension, perpendicular to x₁x₂x₃, expanding at c from every event, whose metric is rank 2 and whose wavefront carries action h per Compton cycle.


## Appendix A. Reading the McGucken Principle: A Note on dx₄/dt, dx₄/dτ, and the Photon — Clarifying Common Reader Misconceptions

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose volume defines a nonlocality.

The McGucken Principle dx₄/dt = ic predicts four distinct x₄-rate quantities, of which the Principle is the coordinate rate (R1), and the appendix below states them and reads the photon, the horizon and the twins through them. It is reproduced verbatim and in full from [1] Appendix A; the theorem, lemma and chapter numbers it cites are those of [1]. One point of naming: Remark A.0.1 calls the first Born-rule route the Metric Route, with the exponent 2 as the rank of the Minkowski metric ([1] Lemma 7.1). In the present paper that lemma is replaced by the Conservation Route of §V.1 — the quadratic form F(s) = κ s² obtained from the conservation of the Sphere's weight under positive-energy propagation — and the rank-2 character of the metric enters as Lemma 2.5; the bracketed note at Route (1) records this.


**About this appendix.** Readers arriving at the McGucken Principle from a standard graduate-relativity background bring one deep habit: the reflex to treat per-proper-time quantities as the “physical” or “covariant” ones, and per-coordinate-time quantities as gauge-dependent bookkeeping. That habit points the wrong way here, because the Principle is a statement about the manifold itself — an expansion happening at every event, at the same rate, regardless of which worldline crosses that event. This appendix explains the four distinct x₄-rate quantities the paper uses, states which one is the Principle, and shows through five worked examples how photons, horizons, twins, and GPS clocks all read naturally once the four quantities are kept in their proper roles.

### A.0 The Physical Fact

Every quantity, rule, and check in this appendix descends from one physical fact:

> The fourth dimension x₄ is expanding in a spherically symmetric manner at the rate of c from every spacetime event, or dx₄/dt = ic.

That is the McGucken Principle. Before any of its consequences are unpacked, its status must be stated plainly, because it is the point on which every reading in this appendix turns: dx₄/dt = ic is an *ontological* claim — a statement about what physically is — and not a coordinate convention, a formal device, or a notational choice. It asserts that the fourth dimension is a real dimension that is really expanding, at the rate c, from every event of spacetime, now. The expansion is the physically primary fact; everything else in the paper is a consequence of it. Minkowski spacetime is what the expansion looks like after its rate is integrated into the coordinate x₄ = ict and squared into the Lorentzian metric x₄² = -c²t²; Hilbert space is what the same expansion looks like when its per-increment imaginary rate is read as oscillation; the light cone is the locus the expanding wavefront traces; the metric, the causal order, the Poincaré group, the Born rule, and the Schrödinger equation are all downstream of the one expansion. None of these is postulated independently. They descend, by the derivations of the body, from the single physical fact that x₄ is expanding at c.

This is the reversal the reader must hold onto throughout. Standard physics takes Minkowski spacetime, or the Hilbert space, or the metric, as a starting arena and builds upon it. Here the arena is not a starting point but a *result*: the starting point is the physical expansion dx₄/dt = ic, and the arena is what that expansion generates. When the appendix below insists that dx₄/dt = ic is primary and the per-proper-time quantities are constructed from it, this is what is meant — not a preference among equivalent formalisms, but a claim about which fact is physically prior. The rate is prior; the worldlines that share in it, the metric that its squaring produces, and the observers that read it are all posterior.

The imaginary unit i in dx₄/dt = ic records the algebraic perpendicularity of the x₄-axis to the three spatial axes on which the expansion casts its projection. Its geometric realisation at each event p ∈ 𝓜_G is the McGucken Sphere Mₚ⁺(t) — the spherical wavefront of radius ct swept out around p by the x₄-expansion. The Sphere is what distinguishes the Principle from Minkowski’s constant four-velocity norm u^μ u_μ = -c²: the norm is a scalar constraint carrying no group action and no measure, and it survives here as a theorem of the Principle (the chain-rule pullback of the Sphere’s expansion rate).

The Sphere carries structure that supplies the Born rule downstream by five independent routes, established in the body of the paper and consolidated here. The two most fundamental are the Metric Route (the exponent 2 is the rank of the Minkowski metric that x₄ = ict induces; Lemma 7.1) and the Haar Route (the Sphere’s transitive SO(3) action forces a unique invariant probability measure; Lemma 7.1.5). That these derivationally-disjoint derivations return the same Born density |ψ|² is an instance of the convergent overdetermination catalogued in Remark 7.17 and §17.5bis; see Remark A.0.1.

*Remark A.0.1 (Five independent derivations of the Born rule).* The Born density P = |ψ|² is derived in this framework by five routes that share no premises beyond the McGucken Sphere itself, each proceeding from a distinct property of the one Sphere. They are given here in order of foundational priority, matching the catalogue of Remark 7.17.

*(1) Metric Route — the Sphere’s metric rank* (Lemma 7.1; Theorem 7.2). The x₄-flux density at a detection event is the metric pairing of the forward +ic advance with its conjugate -ic advance. The Minkowski metric induced by x₄ = ict is a rank-2 tensor, so the pairing is bilinear in (ψ, ψ^*); rank-4 quartic densities are excluded by rank-counting, and U(1) phase invariance, reality, non-negativity, and normalization then force P = |ψ|² uniquely. The exponent 2 is the rank of the metric. This is the most fundamental route, because the exponent is a property of the metric the Principle itself induces. [In the present paper the route of this item is the Conservation Route of §V.1: Lemma 7.1 obtains F(s) = κ s² from the conservation of the Sphere's weight under positive-energy propagation, and the rank-2 character of the Minkowski metric is Lemma 2.5.]

*(2) Haar Route — the Sphere’s symmetry group* (Lemma 7.1.5). The Sphere at the detection event is a round S² ≅ SO(3)/SO(2) carrying the transitive SO(3) action fixed by the isotropy of the x₄-expansion. By the uniqueness of the invariant measure on a homogeneous space of a compact group, there is exactly one SO(3)-invariant probability measure on the Sphere, the round measure dμ = sinθ dθ dφ/(4π), and this is the Born weight over detection directions. This is the route that answers why a probability *measure* exists at all: a measure is physically forced only where a symmetry singles it out uniquely, and SO(3) singles out exactly this one. Minkowski’s norm u^μ u_μ = -c² carries no group action and therefore no such measure — which is why the Sphere, not the bare norm, is what grounds quantum probability.

*(3) Norm Route — the Sphere’s sesquilinear inner product* (Lemma 7.6). The rank-2 sesquilinear inner product satisfies the parallelogram identity as a two-line algebraic consequence, giving the L²-norm structure on Hilbert space 𝓗 with no Jordan–von Neumann theorem needed as upstream input.

*(4) Collision Route — two physical Spheres* (Theorem 7.7; Lemma 7.7.5). The number of physical participants in a head-on detection event is exactly two — emitter Sphere and absorber Sphere — and the coincidence rate is sesquilinear in the two amplitudes, with sum, max, min, and arithmetic/geometric/harmonic means excluded by action-additivity.

*(5) PT-Symmetry Route — the Sphere’s reflection* (Theorem 7.11). The Sphere’s discrete PT_E-symmetry through its source event gives ψ^*(P) = ψ(PT_E · P) exactly, so the squaring in the Born density is the cascade-level expression of that symmetry, and complex conjugation itself is grounded in it.

Routes (1) and (2) proceed respectively from the *rank* of the metric and the *symmetry group* of the Sphere, and are foregrounded as the two most important: the first fixes the exponent as the metric’s rank, the second supplies the invariant measure a probability rule requires. Routes (3)–(5) confirm the same exponent from the norm, the physical collision count, and the reflection symmetry. No route uses another’s premise — rank 2, the SO(3) action, the parallelogram identity, the two-participant count, and the PT-reflection are five logically independent facts about the same Sphere — so their agreement on P = |ψ|² is genuine convergence, not one argument told five times. This is the sense in which the Born rule is convergently overdetermined by dx₄/dt = ic (Remark 7.17; §17.5bis): one downstream fact fixed by five upstream properties of the Sphere.

### A.1 The Four x₄-Rate Quantities

The framework uses four related quantities associated with the fourth dimension’s advance. Each has its own symbol, its own domain of definition, and its own interpretation, and they diverge on null worldlines.

*(R1) The coordinate rate* dx₄/dt = ic, parameter: coordinate t; range: fixed value ic; universal — holds at every event of 𝓜_G. The Principle. With the integrated shadow x₄ = ict, this rate holds identically along every worldline of 𝓜_G — timelike, null, accelerated, at any gravitational potential — because x₄ is a coordinate function of t alone. Every statement about the universality of the expansion, its metric-independence (GR T2), or its exception-freeness is a statement in (R1).

*(R2) The Sphere-tangent velocity component* v_(x₄) ≡ √(c² - v²) (the worldline’s share of the x₄-expansion, per coordinate time); parameter: coordinate t; range: [0, c]; worldline-dependent. A bounded quantity (Lemma 5.1.3.2). The partition v² + v_(x₄)² = c² holds for every worldline, null ones included: at spatial rest v_(x₄) = c; on a null worldline v = c gives v_(x₄) = 0. On timelike worldlines, v_(x₄) coincides with the standard time-dilation-related quantities of special relativity: v_(x₄) = c dτ/dt = c/γ for 0 ≤ v < c. The identity v_(x₄) = c dτ/dt is a theorem about v_(x₄) — τ appears as output, not as the differentiation parameter. At v = c (the null limit) all three expressions give v_(x₄) = 0: the √(c² - v²) form by direct substitution, the c dτ/dt form as the ratio c · 0/dt with dτ = 0, and the c/γ form as the limit γ → ∞. The framework uses v_(x₄) as the primary symbol because it is defined by direct substitution on the null boundary. Statements about time dilation, the photon’s x₄-rest, and horizons live here.

*(R3) The Lorentzian temporal component* u⁴ = dx₄/dτ = icγ; parameter: proper τ; unbounded, undefined on null worldlines; a chain-rule consequence. Derived from (R1) by the chain rule (Theorem 5.1.2.8): dx₄/dτ = (dx₄/dt)(dt/dτ) = icγ. Its magnitude cγ is unbounded as v → c, and on a null worldline (dτ = 0) the quantity is undefined — there the affinely-parametrised null tangent dx^μ/dλ replaces it (Lemma 7.2.2.1a).

*(R4) The accumulated x₄-advance along γ*, X₄[γ] ≡ ∫_γ ic dτ = ic τ[γ]; a worldline functional, path-dependent. Distinct from the coordinate x₄. Two worldlines sharing endpoints share Δ x₄ = ic Δ t but generally differ in X₄. Along a null worldline X₄ is constant; around any closed curve ∮ dx₄ = 0 identically. Statements about differential aging (the twins) live in (R4). The bridge to (R2): dX₄ = ic dτ = i v_(x₄) dt.

### A.2 Which One Is the Principle

The Principle is dx₄/dt = ic: the coordinate-time reading (R1). Because x₄ is a coordinate function of t alone, the rate dx₄/dt takes the same value ic at every event of 𝓜_G — an expanding photon-event, a horizon event, an event on any accelerated worldline. The reading dx₄/dτ = ic is available too, but only where dτ = dt: on a worldline at spatial rest, the chain rule collapses and (R1) coincides with the value of (R3). This is Lemma 4.7 (the rest-frame reverse-reading equivalence), and the qualification dτ = dt is what makes it valid. On a moving worldline the chain rule gives icγ; on a null worldline the quantity does not exist. The coordinate-time reading is primary because dx₄/dt = ic is a physical fact — the expansion itself is prior to any worldline, and dx₄/dt = ic records it directly.

### A.3 Reading the Photon, the Horizon, and the Time-Dilation Formula

**A.3.1 What is the photon’s x₄-rate?** The photon’s share in the expansion is zero: v_(x₄) = 0 (the v = c limit of v² + v_(x₄)² = c²), obtained by direct substitution of v = c into v_(x₄) = √(c² - v²). The reader may be tempted to write “dx₄/dt = 0 for the photon” or “dx₄/dτ = 0.” Neither is available. The first is the coordinate rate (R1), which is ic at every event of 𝓜_G including the photon’s — what vanishes is the photon’s share, not the expansion. The second is 0/0: proper time is not defined for a photon (dτ = 0 pointwise). The correct statement is the share v_(x₄) = 0, so X₄ does not accumulate, so the photon ages not at all. The Principle continues to hold at every event the photon crosses.

**A.3.2 What does “the x₄-rate at the horizon” mean?** The rate is gravity-rigid: ∂(dx₄/dt)/∂ g_(μν) = 0 (GR T2). The rate dx₄/dt = ic takes the same value near the horizon as at infinity. What varies with potential is the share: v_(x₄)(r) = c dτ/dt = c√(1 - rₛ/r) (static Schwarzschild observer), vanishing at r = rₛ. On the infaller’s own clock dτ = dt locally and Lemma 4.7 applies: the local rate is the full ic throughout. Gravitational time dilation is the coordinate-frame projection of a locally invariant rate.

**A.3.3 Which identity is “c² through spacetime”?** *Sphere partition* (per coordinate time, all worldlines): v² + v_(x₄)² = c², bounded, locus a quarter-circle. *Lorentzian four-velocity norm* (per proper time, massive worldlines): u^μ u_μ = |dx₄/dτ|² - |dx⃗/dτ|² = -c², unbounded in each term, signature difference fixing the invariant. The Euclidean per-proper-time sum |dx₄/dτ|² + |dx⃗/dτ|² equals c² only in the instantaneous rest frame; elsewhere c²γ². Plus-sign identities belong to (R2); minus-sign identities to (R3).

**A.3.4 How does the twin paradox read?** Coordinate accumulation is path-independent: both twins accumulate Δ x₄ = ic Δ t. Differential ageing is read from X₄ = ∫ ic dτ, advancing at real magnitude v_(x₄) per unit coordinate time. On the traveling leg v_(x₄) < c, so the traveler accumulates less X₄, so less proper time. The stay-at-home twin retains v_(x₄) = c and accumulates the maximal X₄. The CTC question closes the same way: ∮ dx₄ = 0 identically, so a CTC cannot run on the coordinate; the impossibility lives in X₄.

**A.3.5 γ-projection and rapidity.** A boost is hyperbolic: rapidity φ with coshφ = γ. The Sphere-partition projection is circular: Sphere angle θ with sinθ = v/c, cosθ = v_(x₄)/c = 1/γ. Related by the Gudermannian, θ = gd(φ), so cosθ = sechφ. The 1/γ projection is about θ; unbounded component growth is about φ.

### A.4 Why Nothing of Relativity Is Lost

The fourth dimension advances at the same rate at every event of 𝓜_G; worldlines differ only in how much of that advance they share in. Massive at rest shares fully (v_(x₄) = c); moving shares less (v_(x₄) = √(c² - v²), clock slowed by the Lorentz factor); photon does not share at all (v_(x₄) = 0, ageless, no X₄). Lorentz invariance survives entire because the invariant content — the norm u^μ u_μ = -c² and the metric — is a theorem of the Principle (the metric is the pullback of the Euclidean form along x₄ = ict, the -c² from (ic)²). Lorentz transformations preserve that derived metric; γ, time dilation, length contraction, E = γ mc², the null cone, and the mass-shell all come out unchanged. The foliation quantities v_(x₄) and X₄ are additional bookkeeping frame-anchored to the cosmic-comoving foliation (the CMB rest frame); the Cloaking Theorem (Theorem 39) explains why local metrology cannot detect them. GR survives by the invariant/deformable split: the rate is gravity-rigid; gravity deforms the spatial sector. Time dilation, redshift, light bending, perihelion advance, the horizon, and the field equations are recovered exactly. The horizon is where the share is extinguished; the expansion does not stop.

### A.5 Worked Examples

**A.5.1 The twin paradox.** Traveler at speed v for coordinate time Δ t. Coordinate accumulation: Δ x₄ = ic Δ t for both. Traveler’s share: v_(x₄) = c√(1 - v²/c²). Accumulated: Δ X₄ᵗʳᵃᵛ = ic√(1 - v²/c²) Δ t vs Δ X₄ˢᵗᵃʸ = ic Δ t. Differential aging: Δτᵗʳᵃᵛ - Δτˢᵗᵃʸ = Δ t (√(1 - v²/c²) - 1) < 0: the traveler is younger by exactly the Lorentz factor.

**A.5.2 GPS clock rate.** Satellite at radius r, speed v, mass M. Principle: dx₄/dt = ic. Gravitational share: v_(x₄)^(grav)/c = √(1 - 2GM/rc²); kinematic factor √(1 - v²/c²). Total: v_(x₄)ˢᵃᵗ/c ≈ 1 - GM/(rc²) - v²/(2c²). Ground: ≈ 1 - GM/(R_⊕ c²). Fractional difference ≈ GM(1/R_⊕ - 1/r) - v²/(2c²), matching the +4.5 × 10⁻¹⁰ pre-launch offset at r = 26,600 km, v = 3.87 km/s.

**A.5.3 Schwarzschild gravitational redshift.** Photon from r₁ to r₂ > r₁. Principle: dx₄/dt = ic. Local clock rate: v_(x₄)(r)/c = √(1 - rₛ/r). Frequency ratio ν₂/ν₁ = √((1 - rₛ/r₁)/(1 - rₛ/r₂)); weak-field Δν/ν ≈ -GM(1/r₂ - 1/r₁)/c², matching Pound–Rebka 1959. Photon: v_(x₄) = 0 throughout, no X₄. The redshift is about the clock rates at emitter and receiver, not the photon.

**A.5.4 Hawking temperature.** At r = rₛ, local share v_(x₄)(r) → 0. Surface gravity κ = c/(2rₛ); compactification circumference L_H = 4π rₛ = cħβ_H; temperature T_H = ħ c³/(8π G M k_B). The expansion does not stop at the horizon; the share is extinguished on the static foliation, and compactification of the Euclidean-section x₄-axis at L_H produces the thermal spectrum.

**A.5.5 Bell’s spaceship.** Rockets A, B at proper distance L₀, accelerating identically. Coordinate rate: dx₄/dt = ic. Share: v_(x₄)(t) = c√(1 - v(t)²/c²), decreasing. Accumulated: X₄^A = X₄^B, so both age identically. Launch-frame separation constant L₀; co-moving separation L(t) = L₀ c/v_(x₄)(t), growing without bound. The string breaks: the budget shifts into the spatial sector identically on each rocket, so no differential ageing; the paradox lives in the spatial-sector geometry, the string breaking as co-moving distance grows as 1/v_(x₄).

### A.6 Anchor Table

The definitions and results this appendix refers to are anchored in the body as follows: the four-quantity notation (R1)–(R4) at Definition 5.1.3.4-ter (Chapter 5); the Sphere-tangent share partition v² + v_(x₄)² = c² at Lemma 5.1.3.2 (Chapter 5); the reverse-reading equivalence (dx₄/dτ = ic on rest worldlines) at Lemma 4.7 (Introduction, after Theorem 4); the McGucken–Wick coordinate identity τ_W = x₄/c at Theorem 4; the null-worldline replacement for u^μ at Lemma 7.2.2.1a (Chapter 7); the photon at v_(x₄) = 0 at Lemma 7.2.3.1 (Chapter 7); the gravity-rigidity of the rate ∂(dx₄/dt)/∂ g_(μν) = 0 at GR T2 (Chapter 5); the chain-rule identity u⁴ = icγ at Theorem 5.1.2.8 (Chapter 5); the Cloaking Theorem at Theorem 39 (Chapter 20); the extended photon treatment at §20.9quater (Chapter 20); and KMS periodicity as x₄-compactification at Chapter 15bis.

## References

[1] McGucken, E. *Minkowski Space and Hilbert Space Derived and Unified via the McGucken Principle dx₄/dt = ic: How the Born Rule, Schrödinger Equation, Hilbert Space, Lorentzian Spacetime Metric, Einstein Field Equations, and the Six Wightman Axioms of Relativistic Quantum Field Theory (W1 Hilbert Space, W2 Poincaré Covariance, W3 Microcausality, W4 Field Operator Distributions, W5 Unique Poincaré-Invariant Vacuum, W6 Spectrum Condition) Descend as Theorem Chains from dx₄/dt = ic, with dx₄/dt = ic Recoverable from Each Derived Structure, and the Two Einstein Postulates of Special Relativity, the Equivalence Principle, and the Five Dirac–von Neumann Axioms as Derived Theorems and Corollaries.* Light, Time, Dimension Theory, elliotmcguckenphysics.com (July 5, 2026), v199. <https://elliotmcguckenphysics.com/2026/07/05/minkowski-space-and-hilbert-space-derived-and-unified-via-the-mcgucken-principle-dx%e2%82%84-dt-ic-how-the-born-rule-schrodinger-equation-hilbert-space-lorentzian-spacetime-metric-einstein-fiel/>. The source of every theorem, lemma, definition, proof and survey reproduced verbatim in the present paper.

[2] McGucken, E. *The McGucken Geometry: A Novel Mathematical Category Exalted by the Principle-Axiom dx₄/dt = ic, Wherein an Axis Is Physically Expanding in a Spherically Symmetric Manner and Exalting General Relativity, Quantum Mechanics, and Thermodynamics: A New Geometric Category with Equivalent Differential-Geometric, Jet-Bundle, and Cartan-Geometric Formulations, in Which the McGucken Sphere Generates Spacetime and Gravitational, Quantum, and Thermodynamic Phenomena.* elliotmcguckenphysics.com, May 5, 2026. https://elliotmcguckenphysics.com/2026/05/05/the-mcgucken-geometry-a-novel-mathematical-category-exalted-by-the-principle-axiom-dx%e2%82%84-dt-ic-wherein-an-axis-is-physically-expanding-in-a-spherically-symmetric-manner-and-exalting-general/

[3] McGucken, E. “The Wick Rotation as a Theorem of dx₄/dt = ic: How the McGucken Principle of the Fourth Expanding Dimension Provides the Physical Mechanism Underlying the Wick Rotation and All of Its Applications Throughout Physics.” elliotmcguckenphysics.com (April 20, 2026). https://elliotmcguckenphysics.com/2026/04/20/the-wick-rotation-as-a-theorem-of-dx%e2%82%84-dt-ic-how-the-mcgucken-principle-of-the-fourth-expanding-dimension-provides-the-physical-mechanism-underlying-the-wick-rotation-and-all-of-its-applicat/ . Establishes the Wick substitution t → −iτ as the coordinate identification τ = x₄/c (Theorem 2.1), with ten formal theorems deriving every standard application: Schrödinger-diffusion correspondence, Euclidean path-integral convergence, +iε prescription, twelve-factor-of-i unification (Theorem 5.1), Osterwalder–Schrader reflection positivity, KMS condition, Gibbons–Hawking horizon regularity, Hawking temperature, and Kontsevich–Segal reduction from two inputs to one. Cited throughout the present paper’s §12 (Measurement as Physical Wick Rotation).

[4] McGucken, E. *Novel Reciprocal-Generation McGucken Category McG built on dx₄/dt = ic: Three Theorems on the Source-Pair (ℳ_G, D_M) — Mutual Containment, Reciprocal Generation, and the Containment-Generation Equivalence, Establishing a New Categorical Foundation for Mathematical Physics which Completes the Erlangen Programme.* elliotmcguckenphysics.com, May 2, 2026. https://elliotmcguckenphysics.com/2026/05/02/novel-reciprocal-generation-mcgucken-category-mcg-built-on-dx%e2%82%84-dt-ic-three-theorems-on-the-source-pair-%e2%84%b3_g-d_m-mutual-containment-reciprocal-generation-and-the-contai/ . The corpus paper establishing the McGucken Category McG built on the source-pair (𝓜_G, D_M) with three foundational theorems: (i) Mutual Containment — 𝓜_G contains D_M and D_M contains 𝓜_G in a rigorous sense; (ii) Reciprocal Generation — 𝓜_G generates D_M and D_M reciprocally regenerates 𝓜_G; (iii) the Containment-Generation Equivalence identifying containment and generation as two readings of the same fact. Together these establish McG as a new categorical foundation for mathematical physics that completes the Erlangen Programme by supplying the source-pair structure at its root. Cited as the primary corpus source for the categorical content of the McGucken framework invoked in Theorem 2.4 (space-operator cogeneration) and throughout the cogeneration cascade architecture of §10, and as the corpus source for the three theorems on (𝓜_G, D_M) referenced in the uniqueness clause of Theorem 2.4’s proof.

[5] McGucken, E. *Reciprocal Generation and Huygens’ Principle in Mathematics and Physics Fathered by dx₄/dt = ic: The Reciprocally-Generative Properties of the McGucken Space-Operator Pair (ℳ_G, D_M), Whence Operators Generate Spaces of Generative Operators in Mathematics, and Points Generate Spherical Wavefronts of Generative Points in Physics, All Created by and Containing the Creator dx₄/dt = ic: Huygens as Holography and AdS/CFT.* elliotmcguckenphysics.com, May 12, 2026. https://elliotmcguckenphysics.com/2026/05/12/reciprocal-generation-and-huygens-principle-in-mathematics-and-physics-fathered-by-dx%e2%82%84-dt-ic-the-reciprocally-generative-properties-of-the-mcgucken-space-operator-pair-%e2%84%b3_g-d_m-2/ . The corpus paper developing the Reciprocal Generation property of the McGucken space-operator pair (𝓜_G, D_M) both in its mathematical form (operators generate spaces of generative operators, spaces generate operators that regenerate the space) and in its physical form (points generate spherical wavefronts of generative points, the Huygens-Principle content of the McGucken framework), with the identification of Huygens’ Principle as the precursor of holography and AdS/CFT. Cited as the primary corpus source for the Huygens-Principle identification invoked in Theorem 2.4’s uniqueness clause and in the §6.4.5 Huygens–Fresnel–Kirchhoff superposition of the dx₄/dt = ic Geometric Channel, and as the corpus source for the reciprocal-generation content of the space-operator pair.

[6] McGucken, E. *Novel, Unifying Geometric Derivations of the Born Rule P = |ψ|², the Canonical Commutation Relation [q̂, p̂] = iℏ, the Hilbert Space 𝓗, and the Uncertainty Principle σₓσₚ ≥ ℏ/2 from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic.* elliotmcguckenphysics.com, 2026. https://elliotmcguckenphysics.com/2026/05/07/novel-unifying-geometric-derivations-of-the-born-rule-p%cf%88%c2%b2-the-canonical-commutation-relation-q%cc%82p%cc%82i%e2%84%8f-the-hilbert-space-%f0%9d%93%97-and-the-uncertainty-principle-2/

[7] E. McGucken. *The McGucken-Wick Rotation Theorem: τ = x₄/c as the Unique Signature-Bridging Coordinate Identification.* elliotmcguckenphysics.com, May 1, 2026. <https://elliotmcguckenphysics.com/2026/05/01/the-mcgucken-wick-rotation-theorem-%cf%84-x%e2%82%84-c-as-the-unique-signature-bridging-coordinate-identification/>

[8] McGucken, E. “McGucken Quantum Formalism: The Novel Mathematical Structure of Dual-Channel Quantum Theory underlying the Physical McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic.” elliotmcguckenphysics.com (April 26, 2026). https://elliotmcguckenphysics.com/2026/04/25/mcgucken-quantum-formalism-the-novel-mathematical-structure-of-dual-channel-quantum-theory-underlying-the-physical-mcgucken-principle-of-a-fourth/ . The comprehensive prior-art survey and formal categorical-novelty propositions establishing MQF as a genuinely new quantum-theoretical category. Contains Definitions 7.5.1–7.5.3 (the three categories of quantum-theoretical framework), Propositions 7.5.1–7.5.4 (categorical-novelty proofs), the dual-channel sextuple (M, F, V; H, A, ψ) of Definition 9.2, the MQF Equivalence Theorem 12.1, the Six Novelties enumerated in §13.2, and the Convergent Overdetermination Lemma 15.1. Cited as the foundational architectural paper for the present paper’s dx₄/dt=ic Algebraic Channel / dx₄/dt=ic Geometric Channel development.

[9] McGucken, E. “The Deeper Foundations of Quantum Mechanics: How the McGucken Principle Uniquely Generates the Hamiltonian and Lagrangian Formulations of Quantum Mechanics, Wave/Particle Duality, the Schrödinger and Heisenberg Pictures, and Locality and Nonlocality all from dx₄/dt = ic.” elliotmcguckenphysics.com (April 23, 2026). https://elliotmcguckenphysics.com/2026/04/23/the-deeper-foundations-of-quantum-mechanics-how-the-mcgucken-principle-uniquely-generates-the-hamiltonian-and-lagrangian-formulations-of-quantum-mechanics-wave-particle-duality-the-schrodinger-and/ . The five-proposition Hamiltonian route (Propositions H.1–H.5) and the six-proposition Lagrangian route (Propositions L.1–L.6) are developed in §§II–III, with the Convergent Overdetermination Theorem VII.1 establishing the disjointness of intermediate machinery between the two routes. Cited throughout the present paper as the foundational dual-route derivation paper supplying dx₄/dt = ic Geometric Channel and Algebraic Channel.

[10] McGucken, E. “McGucken Geometry: The Novel Mathematical Structure of Moving-Dimension Geometry underlying the Physical McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic.” elliotmcguckenphysics.com (2026). The companion paper to [MG-MQF], establishing the geometric-side categorical-novelty result that moving-dimension geometry is a categorically novel geometric category not equivalent to any prior framework of dynamical geometry from 1915 to 2026 (general relativity, inflationary cosmology, FLRW, Einstein-aether, Hořava–Lifshitz, causal dynamical triangulations, shape dynamics). Contains the moving-dimension manifold (M, F, V) of Definition 9.3 used in the MQF dual-channel sextuple.

[11] McGucken, E. “A Derivation of Feynman’s Path Integral from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic.” elliotmcguckenphysics.com (April 15, 2026). https://elliotmcguckenphysics.com/2026/04/15/a-derivation-of-feynmans-path-integral-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/ . Derives Feynman’s path integral as a theorem of x₄’s spherical-symmetric expansion via Huygens-wavefront propagation; supplies Proposition L.1 of [MG-Foundations].

[12] McGucken, E. “A Geometric Derivation of the Born Rule P = |ψ|² from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic.” elliotmcguckenphysics.com (April 15, 2026). https://elliotmcguckenphysics.com/2026/04/15/a-geometric-derivation-of-the-born-rule-p-%cf%882-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/ . Three-theorem structure: complex character of ψ from x₄ = ict, uniqueness of squared-modulus from five constraints, geometric-overlap interpretation as forward and conjugate x₄-expansion overlap. Provides the upstream derivation that the present paper’s §7 develops with three complementary geometric readings (Theorems 7.4, 7.7, 7.11).

[13] McGucken, E. “A Novel Geometric Derivation of the Canonical Commutation Relation [q̂, p̂] = iℏ Based on the McGucken Principle dx₄/dt = ic: A Comparative Analysis of Derivations of [q̂, p̂] = iℏ in Gleason, Hestenes, Adler, and the McGucken Quantum Formalism.” elliotmcguckenphysics.com (April 21, 2026). https://elliotmcguckenphysics.com/2026/04/21/a-novel-geometric-derivation-of-the-canonical-commutation-relation-q-p-i%e2%84%8f-based-on-the-mcgucken-principle-a-comparative-analysis-of-derivations-of-q-p-i%e2%84%8f-in-gleason-hestene/ . Derives [q̂, p̂] = iℏ from dx₄/dt = ic by two independent routes (operator and path-integral) with Stone–von Neumann closure; six-criterion comparative analysis with Gleason, Hestenes, and Adler programs. Provides the dual-route derivation of the canonical commutator that the present paper develops in §5.2 (Algebraic Channel) and §5.2.5 (dx₄/dt = ic Geometric Channel).

[14] McGucken, E. “The McGucken Principle (dx₄/dt = ic) as the Physical Mechanism Underlying Huygens’ Principle, the Principle of Least Action, Noether’s Theorem, and the Schrödinger Equation.” elliotmcguckenphysics.com (April 11, 2026). https://elliotmcguckenphysics.com/2026/04/11/the-mcgucken-principle-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-huygens-principle-the-principle-of-least-action-noethers-theorem-and-the-schrodinger-equation/ . Establishes Huygens’ Principle (Proposition L.1 of [MG-Foundations]), the Principle of Least Action, the eight-step Schrödinger derivation, and Noether’s theorem as theorems of dx₄/dt = ic.

[15] McGucken, E. “A Derivation of the Uncertainty Principle ΔxΔp ≥ ℏ/2 from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic.” elliotmcguckenphysics.com (April 11, 2026). https://elliotmcguckenphysics.com/2026/04/11/a-derivation-of-the-uncertainty-principle-%ce%b4x%ce%b4p-%e2%89%a5-%e2%84%8f-2-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-the-expanding-fourth-dimension-th/ . Derives the Heisenberg uncertainty relation as a theorem of four-dimensional geometry. Provides the upstream derivation that the present paper’s §8.2 (Algebraic Channel) and §8.2.5 (dx₄/dt = ic Geometric Channel) develop.

[16] McGucken, E. “How the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic Sets the Constants c (the Velocity of Light) and h (Planck’s Constant).” elliotmcguckenphysics.com (April 11, 2026). https://elliotmcguckenphysics.com/2026/04/11/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-sets-the-constants-c-the-velocity-of-light-and-h-plancks-constant/ . Establishes c as the geometric budget constraint and ℏ as the action quantum per Planck-frequency oscillation of x₄-advance. Supplies the twin-constants statement Proposition 2.2 of the present paper.

[17] McGucken, E. “A Derivation of the de Broglie Relation p = h/λ from the McGucken Principle dx₄/dt = ic: Wave-Particle Duality as a Geometric Consequence of the Expanding Fourth Dimension.” elliotmcguckenphysics.com (April 21, 2026). https://elliotmcguckenphysics.com/2026/04/21/a-derivation-of-the-de-broglie-relation-p-h-%ce%bb-from-the-mcgucken-principle-dx%e2%82%84-dt-ic-wave-particle-duality-as-a-geometric-consequence-of-the-expanding-fourth-dimension-with-a-compara/ . Three-theorem photon case plus massive-particle case, with the Compton-frequency physical mechanism for the de Broglie internal rest-frame clock. Supplies the de Broglie relation p = ℏk used in dx₄/dt = ic Geometric Channel derivations throughout the present paper.

[18] McGucken, E. “The McGucken Principle of a Fourth Expanding Dimension Exalts and Unifies The Conservation Laws: How the Symmetries of Noether’s Theorem, the Conservation Laws of the Poincaré, U(1), SU(2), SU(3), Diffeomorphism Groups, and the Imaginary Structure of Quantum Theory and Complexification of Physics arise from dx₄/dt = ic.” elliotmcguckenphysics.com (April 21, 2026). https://elliotmcguckenphysics.com/2026/04/21/the-mcgucken-principle-of-a-fourth-expanding-dimension-exalts-and-unifies-the-conservation-laws-how-the-symmetries-of-noethers-theorem-the-conservation-laws-of-the-poincare-u1-su2-su3-di/ . Derives the complete Noether catalog plus the twelve-instances-of-i identification establishing all factors of i in quantum theory as geometric shadows of x₄’s perpendicularity.

[19] E. McGucken. *The Father Symmetry: Lorentz, Poincaré, Noether, Gauge, CPT, SUSY, Diffeomorphism, and the String-Theoretic Symmetries All as Theorems of dx₄/dt = ic.* elliotmcguckenphysics.com, April 28, 2026. Theorems 30 and 30' establish Noether’s first and second theorems on the McGucken background; their inputs (Lagrangian, symmetries, foliation) descend from the McGucken Symmetry, with the precise status stated in Remark 10.3.1.1. <https://elliotmcguckenphysics.com/2026/04/28/the-father-symmetry-lorentz-poincare-noether-gauge-cpt-susy-diffeomorphism-and-the-string-theoretic-symmetries-all-as-theorems-of-dx4-dt-ic/>

[20] McGucken, E. *The McGucken Point/Sphere dx₄/dt = ic as Emergent Spacetime’s Foundational Atom Generating Gravity, Quantum Mechanics, the Lorentzian Spacetime Metric, the QFT Vacuum, and Entanglement: Penrose’s Twistors, Jacobson’s Einstein-Equation-of-State, Witten’s Holographic Entropy, Verlinde’s Entropic Gravity, Van Raamsdonk’s Entanglement-Builds-Spacetime, Maldacena’s ER=EPR, and Arkani-Hamed’s Amplituhedron as Theorem-Chains of the Single Principle dx₄/dt = ic.* elliotmcguckenphysics.com (May 13, 2026). <https://elliotmcguckenphysics.com/2026/05/13/the-mcgucken-point-sphere-dx%e2%82%84-dt-ic-as-emergent-spacetimes-foundational-atom-generating-gravity-quantum-mechanics-the-lorentzian-spacetime-metric-the-qft-vacuum-and-entanglement-penro/>

[21] McGucken, E. [MG-Thermo] *Thermodynamics Derived from the McGucken Principle: Chain of Theorems of dx₄/dt = ic — Resolving Einstein’s Unease, the Probability Measure as Haar Measure, Ergodicity as Huygens-Wavefront Identity.* elliotmcguckenphysics.com (April 24, 2026), https://elliotmcguckenphysics.com/2026/04/24/. Cited in §10.12quindecies for Theorem 22.5 (the McGucken reading of the Carcassi CORE1 lecture: the third-law classical uncertainty principle with ħ grounded as the Sphere’s action-per-Compton-cycle, the two-bounds architecture identifying the entropy floor and speed ceiling as the two attributes of the one Sphere, and the ontological terminus), and throughout for the derivation of the laws of thermodynamics as theorems of dx₄/dt = ic, including the strict Second Law dS/dt > 0 from the signed +ic and the Third Law as the Geometric-Channel no-contraction statement.

[22] Born, M. and Jordan, P. “Zur Quantenmechanik.” *Zeitschrift für Physik* 34, 858–888 (1925).

[23] Nielsen, M. A. and Chuang, I. L. *Quantum Computation and Quantum Information.* Cambridge University Press, Cambridge (2000; 10th Anniversary Edition, 2010). Standard reference for POVM measurements in quantum information theory.

[24] Born, M. *Zur Quantenmechanik der Stoßvorgänge.* Zeitschrift für Physik 37, 863–867 (1926); and Nobel Lecture, “The Statistical Interpretation of Quantum Mechanics” (1954). Cited in §7.7.1 for the original outgoing spherical scattering wave ψ ∼ eⁱᵏᶻ + f(θ,φ)eⁱᵏʳ/r with dσ/dΩ = |f|² — the historical origin of the Born rule in a physical spherical-wave problem.

[25] McGucken, E. *Quantum Mechanics Derived from the McGucken Principle: A Complete Derivation as a Chain of Theorems, with Appendix A.* Light, Time, Dimension Theory, v7 (2026); published at elliotmcguckenphysics.com (April 26, 2026) as *Quantum Mechanics Derived from the McGucken Principle: A Unique, Simple, and Complete Derivation of Quantum Mechanics as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic.* <https://elliotmcguckenphysics.com/2026/04/26/quantum-mechanics-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-quantum-mechanics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-d/>. The source of the QM T11 chapter reproduced verbatim in Part VII.

[26] Jordan, P. and von Neumann, J. “On Inner Products in Linear, Metric Spaces.” *Annals of Mathematics* 36, 719–723 (1935). Establishes that a normed linear space is an inner-product space (and hence a Hilbert space, after completion) if and only if its norm satisfies the parallelogram identity ‖x + y‖² + ‖x − y‖² = 2(‖x‖² + ‖y‖²). Equivalent corollary for L^p function spaces (1 ≤ p ≤ ∞): only L² satisfies the parallelogram identity, hence only L² is a Hilbert space among the L^p spaces. Cited in the present paper as the historical functional-analytic correlate of the McGucken-internal parallelogram identity (Lemma 7.6, which establishes the parallelogram identity by direct two-line algebraic expansion from rank-2 sesquilinearity inherited from (ict)² = −c²t² via Lemma 2.5). In the McGucken framework Jordan–von Neumann serves as a *downstream consistency check* — confirming that the McGucken-derived parallelogram-identity structure is consistent with general functional analysis on L^p spaces — rather than as an upstream selection principle or foundational input. The McGucken framework derives the L² character of 𝓗 from the rank-2 metric directly via Lemmas 7.1 and 7.6, with Jordan–von Neumann cited as the standard functional-analytic statement of the forward-and-converse parallelogram-inner-product equivalence.

[27] Lesovik, G. B. “Derivation of the Born rule from the unitarity of quantum evolution.” arXiv:1411.6992 [quant-ph] (2014). Derives the Born rule’s squared-modulus form from the requirement that probability be conserved under unitary quantum evolution on a given Hilbert space, with the L² norm uniquely preserved by Stone-theorem-generated unitaries. Cited in the present paper at the Extended status note following Theorem 7.2 as the functional-analytic reinforcement of Norm Route to the exponent 2: probability conservation under the McGucken-derived unitary evolution of Theorem 9.2 requires the bilinear L² norm, with the L^p norm for p ≠ 2 not in general preserved.

[28] Glimm, J. and Jaffe, A. *Quantum Physics: A Functional Integral Point of View.* Springer (1981). The standard mathematical-physics reference for Euclidean-rotation-based path-integral methods in QFT, presenting the Wick rotation as the foundational computational device for rigorous formulation of interacting quantum field theories. Cited in §10.6.11 (Claim 6) as the standard reference for the orthodox treatment of the Wick rotation.

[29] Rauch, H., Treimer, W., and Bonse, U. “Test of a single crystal neutron interferometer.” *Physics Letters A* 47, 369–371 (1974); Rauch, H., Zeilinger, A., Badurek, G., Wilfing, A., Bauspiess, W., and Bonse, U. “Verification of coherent spinor rotation of fermions.” *Physics Letters A* 54, 425–427 (1975). Empirical confirmation of the 4π-closure of spin-1/2 using neutron interferometry with magnetic-field-induced spin precession: a 2π rotation of one beam relative to the other produces destructive interference (phase factor −1), with constructive interference restored only at 4π. Cited in §12.10 as the empirical anchor for instance (4) of Theorem 12.11 (the spin-1/2 SU(2) double-cover requirement).

[30] Weinberg, S. (2015). *Lectures on Quantum Mechanics*, 2nd ed. Cambridge University Press. <https://www.cambridge.org/core/books/lectures-on-quantum-mechanics/2EE8CF6A6D71B40CDFA88A29F37BD718>

[31] McGucken, E. (May 2026). *The McGucken Principle dx₄/dt = ic Experimentally Verified to a Bayesian Likelihood Ratio gtrsim 10¹⁴¹: Deriving General Relativity and Quantum Mechanics as Independent Theorem Chains Descending from dx₄/dt = ic in the Spirit of Newton's Principia and Euclid's Elements: dx₄/dt = ic as the Axiom Solving Hilbert's Sixth Problem.* <https://elliotmcguckenphysics.com/2026/05/13/the-mcgucken-principle-%f0%9d%91%91%f0%9d%91%a5%e2%82%84-%f0%9d%91%91%f0%9d%91%a1-%f0%9d%91%96%f0%9d%91%90-experimentally-verified-to-a-bayesian-likelihood-ratio-%e2%89%b3-10%c2%b9%e2%81%b4%c2%b9-d/>

[32] Hewitt, E. & Stromberg, K. (1965). *Real and Abstract Analysis*. Springer. <https://link.springer.com/book/10.1007/978-3-642-88044-5>

[33] Reed, M. & Simon, B. (1980). *Methods of Modern Mathematical Physics*, Vol. I: Functional Analysis (rev. and enlarged ed.). Academic Press. <https://www.elsevier.com/books/methods-of-modern-mathematical-physics-volume-1-functional-analysis/reed/978-0-12-585050-6>

[34] Sinha, U., Couteau, C., Jennewein, T., Laflamme, R. & Weihs, G. (2010). Ruling Out Multi-Order Interference in Quantum Mechanics. *Science* **329**, 418. <https://www.science.org/doi/10.1126/science.1190545>

[35] Gleason, A. M. (1957). *Measures on the closed subspaces of a Hilbert space.* Journal of Mathematics and Mechanics, 6(6): 885--893. <https://www.jstor.org/stable/24900629>

[36] von Neumann, J. (1932). *Mathematische Grundlagen der Quantenmechanik.* Springer, Berlin. English translation by R. T. Beyer: *Mathematical Foundations of Quantum Mechanics*, Princeton University Press (1955; new edition edited by Nicholas A. Wheeler, with prefatory remarks drawn from Léon Van Hove and Freeman Dyson, 2018, ISBN 978-0-691-17856-1). The canonical Hilbert-space formulation of quantum mechanics; introduces the two-process distinction in Ch. V: *Process 1* (discontinuous, indeterministic, irreversible projection associated with measurement) and *Process 2* (continuous, deterministic, reversible unitary evolution governed by the Schrödinger equation). The Process 1 / Process 2 distinction is the canonical statement of the measurement problem and is, in the McGucken dx₄/dt= ic framework, the surface signature of the Geometric Channel / Algebraic Channel differential response to the McGucken-Wick rotation, with both processes derived from the single physical principle dx₄/dt= ic. <https://press.princeton.edu/books/hardcover/9780691178561/mathematical-foundations-of-quantum-mechanics>

[37] McGucken, E. [MG-Bekenstein] *How the McGucken Principle of a Fourth Expanding Dimension Derives the Results of Bekenstein’s “Black Holes and Entropy” (1973).* elliotmcguckenphysics.com (April 20, 2026). Cited in §10.12decies for the horizon area law S ∝ A/ℓ_P² from one x₄-stationary mode per Planck area and the coefficient η = (ln 2)/(8π).

[38] McGucken, E. [MG-Hawking] *How the McGucken Principle of a Fourth Expanding Dimension Derives the Results of Hawking’s “Particle Creation by Black Holes” (1975).* elliotmcguckenphysics.com (April 20, 2026). Cited in §10.12decies for the Bekenstein–Hawking entropy S = A/(4ℓ_P²) with the 1/4 from the Euclidean cigar of the McGucken–Wick rotation and the Hawking temperature T_H = ħκ/(2π c k_B).
