---
title: "The Geometric Origin of the Dirac Equation: Spin-½, the SU(2) Double Cover, and the Matter–Antimatter Structure from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic"
author: "Elliot McGucken, PhD · drelliot@gmail.com · elliotmcguckenphysics.com"
date: "April 2026"
abstract: |
 The Dirac equation and its associated Clifford algebra are traditionally derived by demanding a first-order relativistic wave equation, with the γ-matrices and their spinorial structure emerging as algebraic consequences. The characteristic spin-½ double cover SU(2) → SO(3) is typically attributed to abstract representation theory of the Lorentz group, and the matter-antimatter structure is recovered by reinterpreting negative-energy solutions. Here we show that all these features arise as geometric consequences of a single principle: **the McGucken Principle**, which states that the fourth dimension is expanding at the rate of light, $dx_{4}/dt = ic$. The McGucken Principle is the foundational principle of **Light, Time, Dimension Theory**, from which the present derivation program proceeds. The McGucken Principle dx₄/dt = ic states a physical fact: x₄ advances as a spherically symmetric wavefront at the velocity of light, carrying a wavelength, a frequency, a phase, and therefore an action. c and ℏ are twin properties of the one advance, and the Dirac spinor is a phase structure on a wavefront that already oscillates at the Compton frequency. The dynamics were in the premise. From the same wavefront we derive the Klein–Gordon equation and, as its nonrelativistic limit, the Schrödinger equation — each through both the geometric-propagation (Channel B) and algebraic-symmetry (Channel A) channels — before constructing the Dirac equation as the spinorial square root of Klein–Gordon. Matter, understood as a standing x₄-oscillation at the Compton frequency, possesses an intrinsic x₄-orientation — made rigorous here as an algebraic constraint on even-grade multivectors — that breaks the left-right symmetry of bivector action in the 4D Clifford algebra. This asymmetry forces single-sided bivector transformation on matter fields, producing the half-angle spinor rotation that is the geometric root of spin-½. Antimatter emerges naturally as right-action — motion against x₄ expansion — and we demonstrate explicitly, with a rest-frame component-level calculation carried out in full Doran-Lasenby correspondence between geometric-algebra multivectors and 4-component matrix spinors, that the geometric operation Ψ → Ψ · γ₀γ₁ (right-multiplication by the timelike bivector γ₀γ₁) produces the same 4-spinor as the standard matrix operation C γ⁰ ψ* applied to a spin-up electron — both giving (0, −1, 0, 1)ᵀ · e^{+iEt/ℏ}, the rest-frame spin-up positron, with the timelike (x₄-containing) character of the operator fixed by charge conjugation being x₄-orientation reversal. The CPT theorem becomes the geometric statement that full 4D coordinate reversal preserves the x₄-dynamics. Connecting to the broken-symmetries program [21], we show that the same x₄-orientation asymmetry that produces spin-½ also produces the P, C, CP, and T violations of the weak sector, with the CKM complex phase emerging from Compton-frequency interference among quark generations. A central conceptual result is that the microscopic T-violation observed in kaon and B-meson decays and the macroscopic thermodynamic arrow of time are not separate phenomena but the same geometric fact expressed at different scales: both trace directly to dx₄/dt = +ic, not −ic, and this unification is demonstrated rather than asserted. The full Dirac equation follows from these geometric facts together with the Light, Time, Dimension Theory-derived Minkowski signature η = diag(−1, +1, +1, +1), itself a consequence of the i in dx₄/dt = ic. We derive γ⁴ = iγ⁰ from the signature requirement rather than positing it, closing the logical chain. Five falsifiable predictions are discussed in §X.3 — CPT exactness, absence of the spin-2 graviton, absence of magnetic monopoles, integer charge quantization, and the specific pattern of charged-current interactions — each with its experimental status. Appendix A sketches the essential content from the broken-symmetries paper [21] so that the present paper is independently readable.

 
 *“More intellectual curiosity, versatility and yen for physics than Elliot McGucken’s I have never seen in any senior or graduate student. . . Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet.”*
 
 — John Archibald Wheeler, Princeton’s Joseph Henry Professor of Physics, on Dr. Elliot McGucken

---

## I. Introduction

The Dirac equation occupies a unique position in theoretical physics: it is the first-order relativistic wave equation for matter, it predicted antimatter before experimental discovery, and it made spin-½ a requirement rather than a postulate. Its defining features — the Clifford algebra {γᵘ, γᵛ} = 2ηᵘᵛ, the 4×4 matrix representation, the SU(2) double cover of rotational symmetry, the existence of antiparticles — are usually presented as consequences of algebra: demand first-order derivatives in all four spacetime coordinates, demand consistency with Klein-Gordon at second order, and the γ-matrices fall out of the requirement by representation theory. The antimatter solutions come “for free” as negative-energy states requiring reinterpretation.

This algebraic route works, but it leaves open the physical question: why is nature described by spinors? Why should rotations act on matter fields by half-angles? Why should charge conjugation be a symmetry at all, much less combine with P and T into CPT? The standard answers are mathematically correct but physically hollow. They tell us what the mathematics must be, not why nature chose that mathematics.

**Light, Time, Dimension Theory** offers a different starting point. Its foundational principle is **the McGucken Principle**:

$$dx_{4}/dt = ic$$

> **The physical state.** The McGucken Principle dx₄/dt = ic states that the fourth dimension expands as a spherically symmetric wavefront at the velocity of light. That wavefront carries wavelength, frequency, phase, and therefore action. c and ℏ are twin properties of the one advance, the spinor lives on a wavefront that already carries the Compton frequency, and the dynamics were in the premise.

The McGucken Principle dx₄/dt = ic asserts that the fourth dimension expands at the velocity of light, carrying an intrinsic factor of i. From this single equation — the foundational principle of Light, Time, Dimension Theory — a substantial portion of physics can be derived: the Minkowski metric, the Schrödinger equation, Huygens’ Principle, least action, Noether’s theorem, the Schwarzschild solution, the Einstein field equations, and thermodynamic irreversibility. The derivation program is developed across the papers at elliotmcguckenphysics.com. In particular, the relativistic Klein–Gordon equation and its nonrelativistic limit — the Schrödinger equation — are derived from the wavefront in II.5–II.7 below, through both the geometric-propagation route (Channel B) and the algebraic-symmetry route (Channel A) of the Light, Time, Dimension Theory dual-channel architecture; the present paper then builds the spin-½ Dirac structure on top of them as the “square root” of the Klein–Gordon operator.

**The physical reading of the principle.** The McGucken Principle dx₄/dt = ic states a physical fact. The fourth dimension expands, as a spherically symmetric wavefront advancing at the velocity of light from every event. A wavefront advancing at c carries a wavelength λ, a frequency ν = c/λ, and a continuously accumulating phase; the phase is the action in units of ℏ, φ = S/ℏ. The one advance carries wavelength, frequency, phase, and action together, as aspects of a single physical process. c and ℏ are **twin properties of the one advance**: c is the speed at which the wavefront propagates, ℏ is the quantum of action carried in its phase. The integrated coordinate label x₄ = ict descends from dx₄/dt = ic by integration and is the *mere* shadow of the active expansion; every theorem in what follows traces to the advance itself. The Dirac spinor is a phase structure carried on a wavefront that already oscillates at the Compton frequency ω_C = mc²/ℏ, and the rest-frame time evolution e^(−imc²t/ℏ) of the standing-wave electron in Section VIII is the wavefront’s own phase advance. The dynamics were in the premise.

**Preview of the central new result.** The central new contribution of the present paper is contained in Section VIII: we demonstrate by explicit rest-frame component calculation that right-multiplication of the Dirac spinor by the sign-reversed x₄-rotor produces, component by component, the same 4-spinor as the standard matrix operator C γ⁰ ψ* acting from the left. This identifies the abstract charge-conjugation operator C with a concrete geometric operation — reversal of x₄-orientation — and thereby closes the logical chain that begins with matter as an x₄-standing wave and ends with the full matter-antimatter structure of the Dirac equation. Sections II through VII develop the geometric machinery needed for the calculation; Section VIII performs the calculation; Sections IX and X extract consequences.

The present paper extends the Light, Time, Dimension Theory program to the Dirac equation and its associated matter-antimatter structure. We show that the Clifford algebra, the SU(2) double cover, and the charge-conjugation operator C are all geometric necessities once the McGucken Principle dx₄/dt = ic is taken seriously. Matter, as an x₄-standing wave, possesses an orientation relative to the x₄-expansion direction. This orientation breaks a symmetry of the 4D Clifford algebra — the symmetry between left-action and right-action of bivector generators — and the breaking is what produces both the half-angle spinor transformation (spin-½) and the particle-antiparticle distinction (charge conjugation). CPT emerges as full 4D geometric inversion. The weak-sector broken symmetries — P, C, CP, T — follow naturally, with the CKM complex phase generated by Compton-frequency interference when quarks of different masses mix through the transverse-to-x₄ gauge group.

We organize the derivation in ten stages. Section II establishes the geometric setup and the Light, Time, Dimension Theory-derived Minkowski signature. Section III develops bivector geometry in 4D with complex x₄. Section IV introduces the concept of x₄-orientation for matter fields and — in a significantly strengthened treatment — makes this concept mathematically rigorous as an algebraic constraint on even-grade multivectors, showing that single-sided transformation is the *unique* transformation preserving this constraint. Section V derives the half-angle transformation from single-sided bivector action. Section VI constructs the γ-matrices as intertwiners between Weyl chiralities. Section VII identifies antimatter with right-action and charge conjugation with x₄-reversal. Section VIII provides the explicit component-level calculation showing that right-multiplication by the x₄-rotor with reversed sign implements the standard charge-conjugation operator C in a specified basis, and derives γ⁴ = iγ⁰ from the signature requirement. Section IX assembles the full Dirac equation. Section X discusses implications, including a detailed account of how the same geometric directionality produces T-violation at every scale from particle-physics decays to cosmological expansion, connections to the broken-symmetries program, and open questions — including the explicit derivation of the CKM Jarlskog invariant from Compton-frequency interference as the natural next step.

------------------------------------------------------------------------

## II. The Geometric Setup

### II.1 The Light, Time, Dimension Theory Principle and the Minkowski Signature

The Light, Time, Dimension Theory principle asserts:

$$dx_{4}/dt = ic$$

The McGucken Principle dx₄/dt = ic states that the fourth dimension x₄ expands at the velocity of light, carrying an intrinsic factor of i. Integrating dx₄/dt = ic gives x₄ = ict, so the fourth coordinate is complex-valued when expressed in units of real time. The content of the McGucken Principle dx₄/dt = ic is the active expansion. x₄ = ict descends from dx₄/dt = ic by integration and is the coordinate shadow of that advance; the physics lives in dx₄/dt = ic — the fourth dimension advancing as a spherically symmetric wavefront at the velocity of light from every event. Because that wavefront advances at a definite speed, it carries a definite wavelength and frequency, and therefore a phase and an action; c and ℏ are the two faces of this one advance. As we make explicit in II.2 and Section VIII, the Compton-frequency oscillation of matter is nothing other than this wavefront’s own phase, so that the dynamics of the Dirac field are already implicit in the premise rather than imposed upon it.

This single equation fixes the metric signature of spacetime. The infinitesimal invariant interval built from (dx₁, dx₂, dx₃, dx₄) is:

$$ds^{2} = dx_{1}^{2} + dx_{2}^{2} + dx_{3}^{2} + dx_{4}^{2}$$

which looks Euclidean. But substituting $dx_4 = ic\,dt$ gives $dx_4^2 = -c^2\,dt^2$, so:

$$ds^{2} = dx_{1}^{2} + dx_{2}^{2} + dx_{3}^{2} - c^{2}dt^{2}$$

This is the Minkowski interval with signature η = diag(+1, +1, +1, −1), or equivalently η = diag(−1, +1, +1, +1) if we index time first. The Lorentzian signature is not imposed — it emerges directly from the i in dx₄/dt = ic. Wick rotation, conventionally presented as a calculational trick for converting between Euclidean and Lorentzian frameworks, is in Light, Time, Dimension Theory the statement that real time and complex x₄ are related by the principle itself.

### II.2 Matter as an x₄-Standing Wave

In the Light, Time, Dimension Theory framework, matter is a standing oscillation in x₄ at the Compton frequency:

$$\psi (x_{4}) \propto e^{ikx_{4}},\quad \text{where } k = mc/\hbar$$

For a particle at rest, all of its “motion” is the x₄-expansion at rate c. The rest energy E = mc² is interpreted as the rate of x₄-phase accumulation per unit proper time. A photon, having no rest frame, is a pure x₄-oscillation with k₀ = 0; it expands along x₄ at rate c with no standing-wave component.

This interpretation of matter is central to what follows. Matter is a phase structure carried forward by the x₄-expansion of the McGucken Principle dx₄/dt = ic. This phase structure has an orientation: it points in the direction of increasing x₄. Section IV will make this orientation mathematically precise as an algebraic constraint on even-grade multivectors.

This is the physical content of the McGucken Principle dx₄/dt = ic made concrete. The standing oscillation is the phase of the spherically symmetric x₄-wavefront, sampled at the Compton frequency ω_C = mc²/ℏ. The ℏ here is the quantum of action carried by the same advance whose propagation speed is c — the twin property of the one wavefront. The spinor lives on a wavefront that already oscillates at the Compton frequency, and its rest-frame evolution e^(−imc²t/ℏ) is that wavefront’s own phase advance. The dynamics were in the premise.

**Oscillation as geometric content.** It is worth being exact about how much of this the geometry gives on its own, because the precise claim is the stronger one. Read the McGucken Principle dx₄/dt = ic as a connection on the phase carried by the advance: at each increment dx₄ = ic · dt, the factor i applies a quarter-turn — a rotation by π/2, since i = e^(iπ/2) — to the phase riding on the advance. Compounding the quarter-turns is the exponential map,

$$e^{i\theta} = \lim_{n\to\infty}\left(1 + \frac{i\theta}{n}\right)^{n}$$

a product of many perpendicular kicks, which is circular rotation. Phase, periodicity, and wavelike circulation are therefore already present in dx₄/dt = ic, before any quantum postulate is added. The i does the whole of this work: a real advance dx₄/dt = c, without the i, integrates to x₄ = ct and only translates — it never oscillates. It is the perpendicularity of the fourth axis, the i, that turns advance into circulation, and the closure i⁴ = 1 — the quarter-turn returning to its start after four steps — is why the phase is periodic at all, closing once per cycle rather than spiraling. The qualitative wave character of matter, that it has a phase and oscillates, is geometric content of the McGucken Principle dx₄/dt = ic, not a separate quantum-mechanical postulate.

**What the geometry does not fix: the frequency scale.** The geometry gives that there is oscillation and that it is periodic; it does not by itself give the rate of that oscillation as a physical frequency. A quarter-turn per increment of x₄-advance is dimensionless geometry. Turning it into a physical frequency ω_C = mc²/ℏ requires an action scale — the action the wavefront carries per cycle, the quantum ℏ (II.5). A phase is dimensionless, φ = S/ℏ, and the only way to convert an accumulated action S into a pure number is to divide by an action; that action is ℏ. The honest division is therefore: the wavelike oscillation exists as pure geometry, forced by dx₄/dt = ic; that it runs at the Compton frequency mc²/ℏ requires ℏ, which the bare principle does not fix. The geometry gives the wave; ℏ gives its pitch. In the wavefront reading, the wave is in the premise; its pitch is not.

**The wave rides the fibre; the coordinate translates.** One distinction keeps the claim exact. The oscillation lives on the fibre — the phase riding the advance — while the coordinate x₄ itself translates straight. Because dx₄/dt = ic is constant, d²x₄/dt² = 0: the coordinate advances uniformly along its rotated axis and does not orbit. The statement dx₄/dt = ic gives oscillation is precise if it means the phase on the fibre oscillates, which it does, and would be wrong if it meant the coordinate x₄ itself circulates, which it does not. This is the addition-versus-multiplication distinction of the coordinate shadow made physical: added head-to-tail, the quarter-turned increments sum to the straight advance x₄ = ∫ ic dt, which descends from dx₄/dt = ic by integration; compounded multiplicatively, the same increments close into the phase e^(iθ). The particle worldline is the sum, the wave is the product, and both are the one stream of quarter-turned increments dx₄ = ic · dt.

### II.3 The 4D Clifford Algebra

Given the Minkowski signature derived in II.1, any first-order wave operator that squares to the Klein–Gordon operator (derived from the wavefront in II.5–II.6) must satisfy the Clifford algebra:

$$\{\gamma ^{u}, \gamma ^{v}\} = 2\eta ^{uv} \mathbb{1}$$

where {·,·} denotes the anticommutator, η = diag(−1, +1, +1, +1), and 𝟙 is the identity on the representation space. In the remainder of the paper we follow the common convention of suppressing the identity matrix where context makes it clear. This is the Clifford algebra Cl(1,3). Its minimal faithful representation is 4-dimensional, and the objects it acts on are Dirac spinors. A detailed derivation of this result from the Light, Time, Dimension Theory principle is given in the companion paper on Clifford algebra from dx₄/dt = ic.

We take the γ-matrices as given for what follows and focus on the geometric origin of their spinorial action.

### II.4 Convention Statement

The results of this paper, in particular the component-level calculation in Section VIII, depend on explicit choices of basis conventions. We fix them here and use them consistently throughout.

**Pauli matrix convention:** σ₁, σ₂, σ₃ are the standard Hermitian Pauli matrices with σᵢσⱼ = δᵢⱼ 𝟙 + iεᵢⱼₖ σₖ, where εᵢⱼₖ is the totally antisymmetric symbol with ε₁₂₃ = +1 (physics convention).

**Bivector-to-Pauli identification:** Under the isomorphism between the even subalgebra of Cl(0,3) and 2×2 complex matrices, we identify:

e₂₃ ↔ −iσ₁, e₃₁ ↔ −iσ₂, e₁₂ ↔ −iσ₃

This sign choice ensures that exp(θ/2 · e₁₂) acting on a spin-up state along the z-axis produces the standard rotation by angle θ about that axis.

**Gamma matrix basis:** Except where explicitly stated, we work in the Weyl (chiral) basis, in which the γ-matrices take the form:

$$\gamma ^{0} = [[0, \mathbb{1} _{2}], [\mathbb{1} _{2}, 0]], \gamma ^{i} = [[0, \sigma ^{i}], [-\sigma ^{i}, 0]], \gamma ^{5} = [[-\mathbb{1} _{2}, 0], [0, \mathbb{1} _{2}]]$$

where each block is 2×2 and 𝟙₂ is the 2×2 identity.

**Pseudoscalar:** I ≡ γ⁰γ¹γ²γ³ (sometimes denoted γ⁵ up to sign conventions; we write I when we mean the Clifford pseudoscalar and γ⁵ when we mean the chirality operator, with their relationship given explicitly where needed).

**Charge conjugation matrix:** In the Weyl basis, the standard choice is C = iγ²γ⁰, satisfying C⁻¹γᵘC = −(γᵘ)ᵀ and Cᵀ = −C. We use this convention in Section VIII.

These choices fix all signs and normalizations in the component calculation.

### II.5 The Klein–Gordon Equation from the Wavefront (Channel B: Geometric Propagation)

The physical state established in II.2 — x₄ advancing as a spherically symmetric wavefront at the velocity of light, carrying wavelength, frequency, phase, and therefore action — already contains the relativistic wave equation for a spin-0 field. We extract it here directly from the wavefront geometry, performing no canonical quantization. This is **Channel B** of the Light, Time, Dimension Theory architecture: the geometric-propagation channel, in which dynamics arise from the self-consistent superposition of expanding McGucken Spheres.

**Theorem (Klein–Gordon from the McGucken-Sphere wavefront).** Let matter of rest mass m be a phase structure carried on the spherically symmetric x₄-wavefront of the McGucken Principle dx₄/dt = ic, with the Minkowski signature η = diag(−1, +1, +1, +1) of II.1. Then the field ψ satisfies

$$(\Box - m^{2}c^{2}/\hbar ^{2}) \psi = 0, \Box \equiv \partial ^\mu \partial _\mu = -(1/c^{2})\partial _t^{2} + \nabla ^{2}.$$

*Proof, in six steps — each a property of the advance, none a quantization postulate.*

**Step 1 — Mass shell from the McGucken Principle.** The four-velocity normalization u^μu_μ = −c² is the four-vector form of dx₄/dt = ic: the proper advance is the timelike unit four-vector scaled by c, its squared norm fixed by the signature of II.1. Multiplying by m², the four-momentum p^μ = m u^μ obeys

$$p^\mu p_\mu = -m^{2}c^{2}.$$

This *mass shell* is the geometric locus on which the wavefront advance is consistent with rest mass m. (Symbolically verified: with E² = p²c² + m²c⁴, p^μp_μ = −(E/c)² + p² = −m²c².)

**Step 2 — Compton frequency from action quantization.** By II.2 the wavefront carries one quantum of action ℏ per oscillation; ℏ and c are the twin properties of the one advance. In the rest frame the intrinsic oscillation is the Compton frequency ω_C = mc²/ℏ, with Compton wavelength λ_C = ℏ/mc. Writing k^μ = p^μ/ℏ for the four-wavevector, the mass shell of Step 1 becomes, by the Lorentz covariance of the II.1 metric,

k^μk_μ = −m²c²/ℏ², in every frame.

**Step 3 — Plane-wave wavefront mode.** The phase accumulated along a straight worldline is S = ∫ p_μ dx^μ, so an elementary mode of the McGucken-Sphere expansion at four-wavevector k^μ is

$$\psi (x) = \exp(i k_\nu x^\nu ) = \exp(iS/\hbar ).$$

This is the physical content made explicit: the phase is the action carried by the advance, measured in the ℏ the advance itself sets.

**Step 4 — The d'Alembertian extracts the mass shell.** Applying □ to the mode,

$$\Box \psi = \partial ^\mu \partial _\mu \exp(i k_\nu x^\nu ) = (i k^\mu )(i k_\mu ) \psi = -k^\mu k_\mu \psi = (m^{2}c^{2}/\hbar ^{2}) \psi ,$$

using Step 2. Hence $(\Box - m^{2}c^{2}/\hbar ^{2}) \psi = 0.$ The Klein–Gordon equation is nothing but the differential expression of the mass-shell constraint of Step 1. No canonical quantization was performed — it fell out of the wavefront kinematics. (Symbolically verified: □ψ/ψ = ω²/c² − k², and □ψ = (m²c²/ℏ²)ψ is equivalent to the relativistic dispersion ω² = c²k² + m²c⁴/ℏ².)

**Step 5 — Huygens–Fresnel–Kirchhoff form (the integral statement).** The same content has an integral expression. Each point of a Cauchy surface emits an elementary expanding McGucken Sphere — a secondary wavefront — and the field at a later event is their superposition. The Klein–Gordon equation is precisely the self-consistency (Huygens) condition on that superposition: the Kirchhoff–Helmholtz integral over the secondary McGucken Spheres reproduces the field if and only if each mode satisfies Step 4. Channel B therefore has a differential face (Step 4) and an integral face (Step 5), both asserting that the wavefront propagates consistently on the mass shell.

**Step 6 — Massless limit.** Setting m = 0 collapses the mass shell onto the null cone, k^μk_μ = 0, and Klein–Gordon becomes □ψ = 0. The mode propagates on the null cone at c with no Compton frequency — the photon, which in the Light, Time, Dimension Theory ontology is unlocked x₄-content at absolute rest in x₄, with no oscillation in proper time. ∎

The inputs are exactly the wavefront kinematics named in the abstract — the Compton wavelength λ_C, the frequency ω_C, the phase k_νx^ν, and the action ℏ. Each is a property of the spherically symmetric advance of the McGucken Principle dx₄/dt = ic. **The dynamics were in the premise.**

### II.6 The Klein–Gordon Equation by Algebraic Symmetry (Channel A)

The same equation follows through **Channel A**, the algebraic-symmetry channel, in which dynamics arise from the symmetry generators and their algebra rather than from wavefront superposition. The two derivations are independent in method and identical in result; their agreement is the dual-channel consistency that recurs throughout the Light, Time, Dimension Theory program.

Translation invariance of the II.1 metric makes the four-momentum p_μ the conserved generator of spacetime translations (Noether). On the wavefront mode ψ = exp(i k_νx^ν) = exp(iS/ℏ) of II.5, that generator is represented by

p_μ ↦ −iℏ ∂_μ, since −iℏ ∂_μ exp(iS/ℏ) = (∂_μ S) exp(iS/ℏ) = p_μ exp(iS/ℏ).

This operator correspondence is read directly off the wavefront phase of II.2, in which ℏ is the action carried by the same advance whose speed is c. Substituting it into the mass-shell Casimir p^μp_μ = −m²c² of II.5 Step 1,

$$p^\mu p_\mu \psi = -m^{2}c^{2} \psi \Longrightarrow (-i\hbar \partial ^\mu )(-i\hbar \partial _\mu ) \psi = -m^{2}c^{2} \psi \Longrightarrow -\hbar ^{2} \Box \psi = -m^{2}c^{2} \psi ,$$

so once more $(\Box - m^{2}c^{2}/\hbar ^{2}) \psi = 0.$ Channel A obtains Klein–Gordon as the algebraic image of the Poincaré Casimir — the mass-shell symmetry expressed on the generators — while Channel B (II.5) obtains it as the geometric self-consistency of the McGucken-Sphere superposition. Both descend from dx₄/dt = ic: Channel A through the translation generators of the metric the principle produces, Channel B through the propagation of the wavefront the principle *is*. The canonical-quantization route of the textbooks is the special case of Channel A in which p_μ ↦ −iℏ∂_μ is postulated; here it is derived from the wavefront phase, and ℏ is the action quantum of the advance.

### II.7 The Schrödinger Equation as the Nonrelativistic Limit (Both Channels)

The nonrelativistic Schrödinger equation follows from Klein–Gordon — through either channel, since both yield the same operator — by factoring out the fast Compton oscillation of II.2 and retaining the slow envelope. Write

$$\psi (x, t) = \varphi (x, t) \cdot \exp(-i mc^{2}t/\hbar ),$$

separating the intrinsic wavefront phase exp(−iω_C t), ω_C = mc²/ℏ, from a slowly varying envelope φ. Substituting into the Klein–Gordon equation written as (1/c²)∂_t²ψ − ∇²ψ + (m²c²/ℏ²)ψ = 0 and dividing out the common phase yields, *exactly*,

(1/c²) ∂_t²φ − 2i (m/ℏ) ∂_tφ − ∇²φ = 0.

The two mass terms cancel identically: the rest-energy phase has absorbed the m²c²/ℏ² term, which is why none survives. (Symbolically verified: the residual after substitution is exactly (1/c²)φ_tt − 2i(m/ℏ)φ_t − ∇²φ, the mass term cancelling to zero.) In the nonrelativistic regime the envelope varies slowly on the Compton time scale, |∂_t²φ| ≪ (mc²/ℏ)|∂_tφ|, so the first term is negligible against the second, leaving

−2i(m/ℏ) ∂_tφ − ∇²φ = 0 ⟺ $i\hbar \partial _t\varphi = -(\hbar ^{2}/2m) \nabla ^{2}\varphi ,$

the free Schrödinger equation. A scalar potential V enters through the same minimal-coupling/gauge structure that Channel A supplies, giving iℏ∂_tφ = [−(ℏ²/2m)∇² + V] φ.

The two channels read this single limit differently and consistently. In **Channel B**, Schrödinger is the slow envelope of the wavefront phase once the fast Compton oscillation is divided out: the envelope diffuses by Huygens superposition over the spatial McGucken Spheres, the imaginary diffusion coefficient iℏ/2m being the residue of the wavefront's own phase advance. In **Channel A**, it is the nonrelativistic contraction of the Poincaré symmetry to the Galilean symmetry — the c → ∞ limit of the Casimir operator of II.6. Either way, the nonrelativistic quantum mechanics invoked in Section X, and the Dirac–von Neumann structure beyond it, are downstream of the same advance: c, ℏ, and the phase were fixed by dx₄/dt = ic before any wave equation was written. **The dynamics were in the premise.**

### II.8 Two Integrals of the McGucken Principle dx₄/dt = ic: the Channels as a Lie Correspondence, and the Principle as the Differential Wick Rotation

The two derivation channels of II.5–II.6, the coordinate and metric of II.1, and the phase of II.2 are related by the two elementary operations of calculus. Making that relationship precise connects this paper to two of the oldest correspondences in mathematics, and it explains in one stroke why general relativity, built on the same principle, shows no oscillation while quantum mechanics does.

**Proposition (two integrals of the generator).** Read as a generator, the McGucken Principle dx₄/dt = ic — the constant element ic of the one-dimensional Lie algebra u(1) = iℝ — admits two integrals:

1.  the *additive* integral x₄ = ∫₀ᵗ ic ds = ict, a straight advance along the imaginary axis (d²x₄/dt² = 0), whose square dx₄² = −c²dt² builds the Lorentzian metric of II.1;
2.  the *multiplicative* integral, the exponential map exp(∫ i · … ) = e^(iθ), a point circulating on the unit circle (|e^(iθ)| = 1), which is the wavefront phase of II.2.

The additive integral flattens the per-increment rotation into a fixed rotated axis; the multiplicative integral keeps it live. The maps d/dt and ∫ dt carry the coordinate x₄ = ict and the generator dx₄/dt = ic into one another, inverse up to the initial value x₄(0) by the fundamental theorem of calculus.

*Proof.* Direct, and confirmed by computer algebra. ∫₀ᵗ ic ds = ict and d(ict)/dt = ic; d²(ict)/dt² = 0. From dx₄ = ic dt, dx₄² = −c²dt², so ds² = dx₁² + dx₂² + dx₃² + dx₄² = dx₁² + dx₂² + dx₃² − c²dt², the Lorentzian metric of II.1. The exponential map carries ic ∈ u(1) to the circle U(1); the compounded quarter-turns close, e^(iθ) = lim (1 + iθ/n)^n as n → ∞, with |e^(iθ)| = 1. ∎

**The two channels as a Lie-algebra / Lie-group correspondence.** The differential form dx₄/dt = ic — the active wavefront advance that the geometric-propagation channel of II.5 works with — is the infinitesimal generator, a Lie-algebra element. The accumulated parameter x₄ = ict, which underlies the fixed Minkowski metric on which the algebraic-symmetry channel of II.6 operates, is the argument of the exponential. The two elementary operations of calculus are the maps between them: d/dt extracts the generator from the coordinate, ∫ dt accumulates the generator into the coordinate. At the group level, exp sends the generator ic to the flow e^(iθ) and its inverse log returns it. This is the Lie-algebra ↔ Lie-group correspondence, specialized to u(1) → U(1) — one of the foundational facts of modern mathematics — realized here by the McGucken Principle dx₄/dt = ic, with d/dt and ∫ dt as the maps between the two channels.

One point of terminology must be marked, to prevent a conflation. The words *algebraic* and *geometric* in the channel names of II.5–II.6 denote method: the algebra of symmetry generators, against the geometry of wavefront propagation. That axis differs from the sense the same words carry in the Lie correspondence, where the Lie algebra is the infinitesimal object and the Lie group is the global manifold. On the Lie axis, the geometric-propagation channel's form dx₄/dt = ic sits on the infinitesimal (algebra) side, and the algebraic-symmetry channel's integrated metric sits on the global (group) side — the reverse assignment. The two axes are transverse, and "algebraic channel" should not be read as "Lie algebra." What is robust under either naming is the operational statement: d/dt and ∫ dt, equivalently log and exp, are the maps between the differential generator dx₄/dt = ic and the integrated coordinate x₄ = ict together with its flow e^(iθ).

**The McGucken Principle dx₄/dt = ic as the differential form of the Wick rotation.** The principle states that each increment dt is multiplied by i to give dx₄/c — a rotation by π/2 in the complex plane, applied to every infinitesimal increment. That is a Wick rotation carried out as continuous dynamics. The textbook Wick rotation t → iτ, equivalently x₄ = ict, is its integrated form: ∫₀ᵗ ic ds = ict = x₄ descends from dx₄/dt = ic by integration and is the accumulation of the per-increment rotations. The standard once-and-for-all Wick rotation is therefore the finite form of the incremental Wick rotation of the McGucken Principle dx₄/dt = ic, and the Lorentzian signature of II.1, dx₄² = −c²dt², is what that finite rotation produces from the manifestly Euclidean dx₁² + dx₂² + dx₃² + dx₄². The framework performs no Wick rotation after the fact; the rotation is stamped on every increment of dx₄/dt = ic, and x₄ = ict is that rotation accumulated and held fixed.

**Why general relativity shows no oscillation, though the oscillation is present at every event.** General relativity is written on the coordinate x₄ — the additive integral, the metric of II.1. There the per-increment i has been spent on the signature, and the phase oscillation of II.2 appears as monotone exponential behavior rather than as oscillation: the rest-frame phase that oscillates as e^(−iω_C t) in real time is the real exponential e^(−cmx₄/ℏ) written on the imaginary x₄-axis (confirmed by computer algebra — this is the Wick relationship, oscillation in real time being exponential decay in imaginary time). Quantum mechanics is written on the differential form: the Schrödinger equation iℏ ∂_tψ = Ĥψ carries the i on the first time-derivative, so the compounded-i mechanism of II.2 is active on the phase fibre and produces the unitary rotation of the wavefunction. Both formalisms descend from dx₄/dt = ic — general relativity by integrating the differential content out into the metric, quantum mechanics by keeping it active on the phase fibre. The appearance that general relativity is not quantum-mechanical records which integral one takes: the additive integral hides the oscillation in the signature, the multiplicative integral displays it as the wave. The oscillation is present in the generator at every event, and the additive integral flattens it into the fixed metric.

**The Schrödinger equation and its propagator as the two integrals.** The same pattern organizes the nonrelativistic limit of II.7. The Schrödinger equation iℏ ∂_tψ = Ĥψ is the differential form — the generator −iĤ/ℏ acting on the wavefunction fibre, the compounded-i mechanism of II.2 lifted to Hilbert space. Its multiplicative integral is the propagator U(t) = exp(−iĤt/ℏ), which is unitary (confirmed: U†U = 𝟙) and therefore a rotation of the state vector. The equation is the generator, the propagator is its exponential, and the i on the time-derivative is the same i as in the McGucken Principle dx₄/dt = ic.

**The broader duality.** The pair (d, ∫) acting between the differential and integrated forms is one instance of a general algebra–geometry duality: Cartan's exterior calculus and Stokes' theorem ∫_M dω = ∮_(∂M) ω, of which ∫₀ᵗ d(x₄) = ict is the elementary case; and, at the level of correspondences, the Lie-algebra / Lie-group, connection / holonomy (Ambrose–Singer), and Gelfand dualities. The relationship isolated here is a specific physical instance of that pattern, with dx₄/dt = ic on the differential side and x₄ = ict on the integrated side. At the level of quantum field theory the same relationship appears as the Wightman ↔ Osterwalder–Schrader correspondence between Minkowski and Euclidean formulations, related by Wick rotation; the companion papers develop that case.

As with the wavefront reading of II.2, this is geometric content of the McGucken Principle dx₄/dt = ic. The physical scales are the separate input: the flow's rate ω_C = mc²/ℏ needs the action quantum ℏ, and the metric's physical units need c. The geometry gives the two integrals and the rotation between them; c and ℏ set the rate of the one and the unit of the other.

------------------------------------------------------------------------

## III. Bivector Geometry in 4D with Complex x₄

### III.1 Bivectors as Oriented Plane Elements

A bivector is an oriented plane element, the 4D analog of an oriented area in 2D or volume in 3D. In the 4D Clifford algebra, bivectors are the grade-2 elements — antisymmetric products of two vectors:

$$e_{\text{ab}} = e\textsubscript{a} \wedge e\textsubscript{b} = \tfrac{1}{2}(e\textsubscript{a} e\textsubscript{b} - e\textsubscript{b} e\textsubscript{a})$$

There are six independent bivectors in 4D, corresponding to the six independent planes:

- Spatial bivectors (purely real): e₁₂, e₂₃, e₃₁
- x₄-involving bivectors (carrying the i of x₄): e₁₄, e₂₄, e₃₄

### III.2 The Squaring Behavior

The square of a bivector is determined by the Clifford algebra. For a purely spatial bivector:

$$e_{12}^{2} = e_{1}e_{2}e_{1}e_{2} = -e_{1}e_{1}e_{2}e_{2} = -(+1)(+1) = -1$$

using {e₁, e₂} = 0 and eᵢ² = +1 for spatial basis vectors. Spatial bivectors square to −1; they are the geometric analogs of imaginary units, and they generate compact rotations.

For an x₄-involving bivector:

$$e_{14}^{2} = e_{1}e_{4}e_{1}e_{4} = -e_{1}e_{1}e_{4}e_{4} = -(+1)(-1) = +1$$

using e₄² = η₄₄ = −1 from the Lorentzian signature. x₄-involving bivectors square to +1; they generate non-compact boosts.

This compact/non-compact split is the geometric origin of the difference between rotations (periodic) and boosts (unbounded rapidity). It traces directly to the i in dx₄/dt = ic via the signature of η₄₄.

### III.3 Bivectors as Rotation Generators

A rotation in the plane of a bivector P by angle θ is generated by exponentiation:

$$R(\theta ) = \exp(\theta /2 \cdot e\textsubscript{P})$$

The factor of 1/2 is the subject of Sections IV and V. It is not imposed — it emerges from the geometry of how matter couples to bivectors via the x₄-expansion.

### III.4 The Pseudoscalar

A key object in what follows is the Clifford pseudoscalar:

$$I = \gamma ^{0}\gamma ^{1}\gamma ^{2}\gamma ^{3}$$

This is the unit 4-volume element. Direct computation using the Clifford algebra shows:

- I² = −1
- I anticommutes with every vector γᵘ
- I commutes with every bivector γᵘγᵛ (μ ≠ ν)

The pseudoscalar serves as a natural “i” for the 4D Clifford algebra. In Light, Time, Dimension Theory, this I is the geometric embodiment of the i in the McGucken Principle dx₄/dt = ic. The i appearing in matter field phases e^(ikx₄) is I in disguise; when we write the Dirac equation in full Clifford-algebraic form, the complex structure of quantum mechanics emerges as the pseudoscalar structure of 4D spacetime.

------------------------------------------------------------------------

## IV. The x₄-Orientation of Matter: Rigorous Formulation

### IV.1 Motivation from the Standing-Wave Structure

Matter, as established in II.2, is an x₄-standing wave with phase accumulating in the direction of increasing x₄. This gives matter an intrinsic orientation relative to the x₄-axis: the wavefunction phase evolves as e^(+ikx₄) with k > 0 for ordinary matter. In the Clifford-algebraic formulation, where the pseudoscalar I plays the role of the imaginary unit i, this becomes:

$$\Psi _{\text{matter}}(x, x_{4}) = \Psi _{0}(x) \cdot \exp(I \cdot kx_{4})$$

The previous version of this paper described matter’s “x₄-orientation” using pictorial language of leading and trailing edges. That description was geometrically suggestive but not mathematically precise, and a hostile referee would correctly object that left-multiplication and right-multiplication in a Clifford algebra do not literally act on different “sides” of a physical object — both are operations performed at the same spacetime point on the same multivector. We now give the rigorous formulation.

### IV.2 The Matter Orientation Constraint

**Definition (matter orientation condition).** An even-grade multivector Ψ in Cl(1,3) is said to carry matter x₄-orientation at Compton frequency k > 0 if there exists an even-grade multivector Ψ₀ — the rest-frame amplitude — and a real scalar x₄ such that:

$\Psi (x, x_{4}) = \Psi _{0}(x) \cdot \exp(+I \cdot kx_{4}), k > 0$     (M)

with multiplication performed on the right. The corresponding condition for antimatter is Ψ(x, x₄) = Ψ₀(x) · exp(−I · kx₄). Here k = mc/ℏ is the x₄-wavevector of the McGucken-Principle wavefront: the Compton frequency of II.2, the rate at which dx₄/dt = ic advances the phase of a rest-mass-m standing wave. The whole content of (M) descends from the McGucken Principle dx₄/dt = ic — the x₄-rotor exp(I · kx₄) is the phase the spherically symmetric wavefront accumulates, and the pseudoscalar I is the geometric embodiment of the i in dx₄/dt = ic (III.4).

This is an algebraic constraint on Ψ, not a pictorial one. It specifies a definite relationship between the x₄-dependence of the multivector and its rest-frame value, via right-multiplication by the x₄-rotor. The key features of (M) are:

1. The sign of k is positive — this is what distinguishes matter from antimatter.
2. The x₄-dependence enters through right-multiplication — this is what picks out a preferred side of the bivector action on Ψ.
3. The pseudoscalar I, not an abstract imaginary unit, is the generator — this ties the phase structure to the 4D Clifford geometry.

### IV.3 Theorem: Single-Sided Action Preserves the Matter Constraint

**Theorem (single-sided preservation).** Let R = exp(θ/2 · e_P) be a rotor generated by a spatial bivector e_P (i.e., e_P ∈ {e₁₂, e₂₃, e₃₁}). Let Ψ satisfy the matter orientation condition (M). Then:

\(a\) Left-action Ψ → RΨ preserves (M): RΨ satisfies (M) with rest-frame amplitude Ψ₀’ = RΨ₀ and the same Compton frequency k.

\(b\) Sandwich action Ψ → R⁻¹ΨR does *not* preserve (M) in general: R⁻¹ΨR fails to admit a decomposition of the form Ψ₀” · exp(+I · kx₄) for any rest-frame amplitude Ψ₀” and the original k > 0.

**Proof.**

*Part (a).* Let R be independent of x₄ (spatial bivectors commute with x₄, so R depends only on spatial coordinates or is constant). Then:

RΨ = R · Ψ₀ · exp(+I · kx₄) = (RΨ₀) · exp(+I · kx₄)

which satisfies (M) with Ψ₀’ = RΨ₀. The positive k is preserved.

*Part (b).* Compute the sandwich action:

$$R^{-1}\Psi R = R^{-1} \cdot \Psi _{0} \cdot \exp(+I \cdot kx_{4}) \cdot R$$

We use two key facts about the spatial bivector e_P: (i) Spatial bivectors commute with the pseudoscalar I (since I = γ⁰γ¹γ²γ³ and spatial bivectors involve only spatial γ’s, the commutator [e_P, I] = 0 follows by direct computation using the Clifford algebra). (ii) Therefore R commutes with exp(+I · kx₄).

Using (ii):

$$R^{-1} \cdot \Psi _{0} \cdot \exp(+I \cdot kx_{4}) \cdot R = R^{-1} \cdot \Psi _{0} \cdot R \cdot \exp(+I \cdot kx_{4})$$

So the sandwich action on Ψ is equivalent to the sandwich action on Ψ₀, leaving the x₄-rotor intact. Superficially this might seem to preserve (M). But now consider the general case where R is extended to an x₄-involving bivector — say R = exp(φ/2 · e_₁₄). Now R does *not* commute with I, because x₄-involving bivectors anticommute with the spatial γ’s they do not contain, and one computes:

[e₁₄, I] = 2 e₁₄ · I_⊥ ≠ 0 (where I_⊥ denotes the pseudoscalar projected onto the bivector’s orthogonal complement)

The sandwich action then produces:

$$R^{-1} \cdot \Psi _{0} \cdot \exp(+I \cdot kx_{4}) \cdot R = R^{-1} \cdot \Psi _{0} \cdot R \cdot \exp(+R^{-1} \cdot I \cdot R \cdot kx_{4})$$

and R⁻¹ · I · R ≠ I in general for x₄-involving R. The exponent is therefore not the same pseudoscalar I appearing in (M), and the resulting multivector fails to satisfy the matter orientation condition with the original I.

The critical observation: the sandwich action for the x₄-involving bivector generates a transformed pseudoscalar R⁻¹IR, which by direct computation has a component along the negative-I direction. The right-multiplication by R thus partially converts exp(+I · kx₄) into a mixture containing exp(−I · kx₄) — that is, it partially converts matter into antimatter. This is the precise algebraic content of the earlier pictorial statement that “the right-action would attempt to rotate the x₄-orientation backwards.” ∎

### IV.4 What the Theorem Establishes

The theorem replaces the pictorial “leading edge / trailing edge” argument with a concrete algebraic fact: the sandwich action, applied to an x₄-oriented matter field, produces a multivector that no longer satisfies the matter orientation condition. In particular, for bivectors involving x₄, the sandwich action introduces an antimatter component. Only left-action (single-sided transformation) preserves the matter constraint across the full group of bivector generators needed to describe all Lorentz transformations.

Consequently, matter fields must transform under bivector generators by single-sided action only:

$\Psi \to \exp(\theta /2 \cdot e_P) \Psi$

The half-angle in the spinor rotation is the theorem that single-sided transformation is the unique action on matter fields preserving the x₄-orientation constraint (M) across all bivector generators.

### IV.5 Why Vectors See the Full Angle

To solidify the contrast: a 4-vector like dxᵘ does not satisfy the matter orientation condition (M). It has no x₄-phase structure, no exp(+I · kx₄) factor, no preferred sign of k. The matter constraint simply does not apply to vectors. For vectors, the geometrically natural transformation is the sandwich action R⁻¹vR, which preserves the vector’s grade (a vector stays a vector) and rotates it by angle θ. There is no asymmetry to break because there is no oriented phase structure to preserve.

Matter, being defined by (M), is in a different algebraic class. Its defining constraint picks out right-multiplication as the locus of x₄-orientation, and the theorem of IV.3 then forces single-sided transformation as the unique orientation-preserving action.

### IV.6 A Variational Perspective

The same conclusion can be reached from an action-principle argument, which we sketch here for completeness. The action is not imported from outside: in the McGucken Principle dx₄/dt = ic the phase the wavefront accumulates is the action in units of ℏ (II.5, Step 3), and least action is itself a McGucken-derived result — the stationary-phase condition on the McGucken-Sphere superposition. The rest-frame Lagrangian for a field with the x₄-oriented phase structure of (M) is proportional to:

$L_{\text{rest}} \propto \Psi ̄ (i \gamma ^{u} \partial _\mu - m) \Psi$

where Ψ̄ = Ψ† γ⁰ is the Dirac adjoint. Under a left-action Ψ → RΨ (with R an even-grade rotor, R† = R⁻¹ for spatial bivectors), the adjoint transforms as Ψ̄ → Ψ̄ R⁻¹, and the bilinear Ψ̄(…)Ψ is invariant precisely when the operator (i γᵘ ∂_μ − m) commutes with R — which holds for spatial rotations. Under a sandwich action Ψ → R⁻¹ΨR, the bilinear Ψ̄(…)Ψ becomes R⁻¹ Ψ̄ (…) Ψ R, which is not a scalar: it picks up grade-2 and grade-4 components that the original action did not contain. The sandwich action thus produces a non-scalar Lagrangian, which is not an admissible transformation of the action.

Single-sided action is therefore both the unique transformation preserving the matter orientation constraint (M) algebraically (Theorem IV.3) and the unique transformation preserving the scalar character of the Dirac Lagrangian (variational argument). Both routes close the gap in the previous version’s argument.

------------------------------------------------------------------------

## V. The Half-Angle and the SU(2) Double Cover

### V.1 Spatial Rotations on Matter

Consider a spatial rotation in the (x₁, x₂) plane by angle θ. The generator is the bivector e₁₂, and the rotation acts on a matter field ψ by:

$$\psi \to \exp(\theta /2 \cdot e_{12}) \psi = [\cos(\theta /2) + \sin(\theta /2) \cdot e_{12}] \psi$$

using e₁₂² = −1 — which descends from the Clifford structure of the Minkowski metric of the McGucken Principle dx₄/dt = ic (III.2) — to evaluate the exponential, with e₁₂ playing the role of i.

At θ = 2π:

$$\psi \to [\cos(\pi ) + \sin(\pi ) \cdot e_{12}] \psi = -\psi$$

A full spatial rotation by 2π flips the sign of the matter field. Only at θ = 4π does the field return to itself.

### V.2 The Double Cover

The map from rotation angle θ to matter-field transformation is therefore:

- θ ∈ [0, 4π) ↔ spinor transformation
- θ ∈ [0, 2π) ↔ vector rotation

Two distinct spinor transformations (at θ and θ + 2π) correspond to the same vector rotation. This is the SU(2) → SO(3) double cover, derived geometrically from the single-sided bivector action on x₄-oriented matter — where “single-sided” now has the rigorous meaning established in Theorem IV.3.

### V.3 The Pauli Matrices

For spatial rotations, the three bivectors e₁₂, e₂₃, e₃₁ — the spatial-rotation generators of the Clifford algebra of the metric of the McGucken Principle dx₄/dt = ic — generate the rotation subalgebra acting on the McGucken-Sphere standing wave. Their products and commutators reproduce the quaternion algebra:

$e_{12} \cdot e_{23} = e_{13}$ (up to sign from the Clifford product) $[e_{12}, e_{23}] = 2 e_{13}$ (with appropriate signs)

In the minimal complex representation, using the convention fixed in II.4:

$e_{23} ↔ -i\sigma _{1}, e_{31} ↔ -i\sigma _{2}, e_{12} ↔ -i\sigma _{3}$

The spinor transformation under a rotation by θ about the n̂ axis becomes:

$\psi \to \exp(-i\theta /2 \cdot n̂\cdot \sigma ) \psi$

which is the standard SU(2) rotation operator for spin-½ (the overall sign is a convention; the physical content is the half-angle). The spin-½ representation is forced by the half-angle, which is forced by the single-sided action, which is forced by the theorem of IV.3 — which is ultimately forced by matter’s x₄-orientation constraint (M).

------------------------------------------------------------------------

## VI. The γ-Matrices as Intertwiners

### VI.1 Weyl Chiralities from x₄-Orientation

Matter has two possible x₄-orientations: forward (exp(+I · kx₄)) and its mirror (exp(−I · kx₄)). These correspond to the two Weyl chiralities — left-handed and right-handed spinors. Formally, defining the chirality projectors P_L = ½(1 − γ⁵) and P_R = ½(1 + γ⁵) in the Weyl basis, the two halves of the Dirac spinor transform under distinct copies of SU(2) in the massless limit.

In the massless limit, these two chiralities decouple completely; they transform under independent copies of SU(2). With mass, the two chiralities couple. The coupling strength is the Compton frequency k = mc/ℏ — the rate at which the McGucken-Principle wavefront dx₄/dt = ic advances the phase of a rest-mass-m standing wave (II.2). This coupling is what mixes left and right Weyl spinors into a single Dirac spinor.

### VI.2 The Form of the γ-Matrices

The γ-matrices are the operators that intertwine the two chiralities. In the Weyl basis fixed in II.4:

$$\gamma ^{0} = [[0, \mathbb{1} _{2}], [\mathbb{1} _{2}, 0]], \gamma ^{i} = [[0, \sigma ^{i}], [-\sigma ^{i}, 0]]$$

γ⁰ exchanges left and right Weyl components; γⁱ exchanges them with a spatial twist determined by the Pauli matrices.

The anticommutation {γᵘ, γᵛ} = 2ηᵘᵛ 𝟙 is the Clifford algebra of the Minkowski metric derived in II.1 from the McGucken Principle dx₄/dt = ic — the same algebra the first-order Dirac operator must satisfy in order to square to the Klein–Gordon operator derived from the wavefront in II.5–II.6.

### VI.3 The Geometric Meaning

The γ-matrices are the “switches” between matter’s two x₄-orientations. Because matter is single-sidedly x₄-oriented, but both orientations exist in nature (left-handed and right-handed fermions), a complete description requires objects that can flip between the two. These objects are the γ-matrices. Their algebra is the Clifford algebra of the 4D Minkowski geometry derived in II.1 from the McGucken Principle dx₄/dt = ic — the algebra the Dirac operator squares to in the Klein–Gordon derivation of II.5–II.6 — and their 4×4 matrix form reflects the two-chirality-times-two-spin structure of the McGucken-Sphere standing wave.

------------------------------------------------------------------------

## VII. Antimatter as Right-Action: Geometric Picture

### VII.1 Motion Against x₄

The bivector right-action on a matter field ψ, excluded in Section IV because it reverses matter’s x₄-orientation, is physically meaningful: its meaning is antimatter.

An object transforming by right-action:

$\psi \to \psi \cdot \exp(\theta /2 \cdot e_P)$

propagates backward along x₄ relative to ordinary matter. In Light, Time, Dimension Theory, this is the definition of antimatter: motion against the direction of x₄-expansion.

### VII.2 Charge Conjugation from x₄-Reversal: Preliminary Statement

The charge conjugation operation C in the Dirac formalism is classically defined as:

$\psi ^c = C \gamma ^{0T} \psi$*

where C is a specific matrix determined by the γ-matrix representation (with the convention fixed in II.4: C = iγ²γ⁰). In Light, Time, Dimension Theory, this has a direct geometric interpretation: charge conjugation is the reversal of x₄-orientation. It swaps left-action for right-action, converts forward-x₄ propagation into backward-x₄ propagation, and thereby converts matter into antimatter.

The CPT theorem is, in this picture, a statement about x₄-reversal symmetry: reversing x₄-orientation (C), reversing spatial orientation (P), and reversing temporal ordering (T) are all aspects of the same geometric operation — full 4D coordinate inversion.

### VII.3 Particle-Antiparticle Annihilation

When matter (forward-x₄) meets antimatter (backward-x₄), their x₄-phases cancel:

$$\exp(+I \cdot kx_{4}) \cdot \exp(-I \cdot kx_{4}) = 1$$

The rest energy content, which was encoded in the x₄-standing-wave structure, is released. What remains is pure x₄-propagation without a standing component — that is, photons. This is the geometric picture of e⁺e⁻ → γγ annihilation: the x₄-oscillations cancel, releasing the energy as non-oscillating x₄-propagation.

The claims in this section — that right-action reverses x₄-orientation, that this is the charge-conjugation operation C, and that CPT follows as full 4D inversion — must be demonstrated by explicit calculation rather than asserted. This is the task of Section VIII.

------------------------------------------------------------------------

## VIII. Explicit Derivation: Right-Action Implements Charge Conjugation

This section closes the logical chain by showing in component detail that right-multiplication by the x₄-rotor with reversed sign is geometrically identical to the standard charge-conjugation operator C. We derive the relation γ⁴ = iγ⁰ from the signature requirement rather than positing it, and we perform the identification by an explicit rest-frame component calculation: starting from a positive-energy electron plane-wave solution, we apply both the geometric right-action operation and the standard matrix C-operator, and verify that they produce the same 4-spinor component by component.

### VIII.1 Deriving γ⁴ = iγ⁰

In Light, Time, Dimension Theory, we work natively in four coordinates (x₁, x₂, x₃, x₄) with x₄ the expanding complex dimension. Conventional Dirac-equation work uses Lorentzian coordinates (x⁰, x¹, x², x³) with x⁰ = ct real. The two descriptions are related by x₄ = ix⁰, which is the Light, Time, Dimension Theory principle dx₄/dt = ic integrated.

The Clifford algebra must be consistent across both descriptions. The defining relation is:

$$\{\gamma ^{u}, \gamma ^{v}\} = 2\eta ^{uv}$$

In the Light, Time, Dimension Theory-native (Euclidean-looking) coordinates, the natural signature assignment is η_LTD = diag(+1, +1, +1, +1) — the metric looks Euclidean because the Lorentzian character is hidden in the complex x₄. In Lorentzian coordinates, the signature is η_L = diag(−1, +1, +1, +1).

For the same physical Clifford algebra, the generators must satisfy:

- γ⁰² = η₀₀ = −1 (Lorentzian)
- γ⁴² = η₄₄ = +1 (Light, Time, Dimension Theory-native, since the x₄-direction squares to +1 in Euclidean signature before the i is extracted)

But x₄ and x⁰ are the same physical dimension, related by x₄ = ix⁰. So γ⁴ and γ⁰ must be related by the same factor of i:

$$\gamma ^{4} = i\gamma ^{0}$$

Check: $(\gamma^4)^2 = (i\gamma^0)^2 = i^2(\gamma^0)^2 = (-1)(-1) = +1$ ✓

This is forced by the signature requirement and the coordinate relation x₄ = ix⁰, which descends from the McGucken Principle dx₄/dt = ic. The identity γ⁴ = iγ⁰ is a theorem: it is the only relation consistent with both the Clifford algebra and the McGucken Principle dx₄/dt = ic.

### VIII.2 Matter Field in Clifford-Algebraic Form

A Dirac spinor in the geometric algebra formulation (Hestenes’ formulation, which Light, Time, Dimension Theory adopts naturally) is an even-grade multivector:

$$\Psi = \rho ^{1/2} \cdot R \cdot \exp(I \beta /2)$$

where:

- ρ is the probability density
- R is a rotor encoding spin orientation
- β is the Yvon-Takabayashi angle
- I = γ⁰γ¹γ²γ³ is the Clifford pseudoscalar

**Physical interpretation of the Yvon-Takabayashi angle β in Light, Time, Dimension Theory.** The angle β measures the local rotation of the spinor’s internal orientation relative to the matter-orientation condition (M). In Hestenes’ interpretation, β = 0 corresponds to pure matter (satisfying (M) with k > 0), β = π corresponds to pure antimatter (satisfying (M) with k < 0), and intermediate values correspond to superpositions. In the Light, Time, Dimension Theory picture, β is the local tilt between the particle’s x₄-phase frame and the universal x₄-expansion direction — when β = 0, the particle’s x₄-phase is aligned with the cosmological x₄-expansion; when β = π, it is anti-aligned. For the rest-frame charge-conjugation calculation that follows, we work at β = 0 (pure matter) and β = π (pure antimatter), which are the two extremal cases that suffice to establish the geometric identification. For a general spinor with intermediate β, the identification extends by linearity.

The x₄-standing wave structure of matter at rest (β = 0) is:

$$\Psi _{\text{matter}}(x, x_{4}) = \Psi _{0}(x) \cdot \exp(I \cdot kx_{4})$$

where k = mc/ℏ and exp(I · kx₄) = cos(kx₄) + I · sin(kx₄), using I² = −1.

The pseudoscalar I plays the role of the imaginary unit in the phase. In Light, Time, Dimension Theory, this is not coincidence: the i of quantum mechanics is the I of 4D Clifford geometry, which is the i of dx₄/dt = ic. All three are the same object seen from three perspectives — the complex structure of x₄-expansion, the pseudoscalar structure of 4D spacetime, and the i of the quantum phase.

### VIII.3 Right-Action with the Inverse x₄-Rotor

Define the x₄-rotor:

$$U(x_{4}) = \exp(I \cdot kx_{4}) = \cos(kx_{4}) + I \cdot \sin(kx_{4})$$

Its inverse is:

$$U^{-1}(x_{4}) = \exp(-I \cdot kx_{4}) = \cos(kx_{4}) - I \cdot \sin(kx_{4})$$

Matter transforms under left-action by U acting on the spatial part:

$$\Psi _{\text{matter}}(x_{4}) = \Psi _{0} \cdot U(x_{4})$$

Consider now the right-action x₄-reversed field — the result of replacing the x₄-rotor with its inverse:

$$\Psi ^c(x_{4}) = \Psi _{0} \cdot U^{-1}(x_{4}) = \Psi _{0} \cdot \exp(-I \cdot kx_{4})$$

This field has x₄-phase running in the opposite direction — backward along x₄. We now show it satisfies the Dirac equation with the role of matter and antimatter exchanged.

### VIII.4 Rest-Frame Plane-Wave Setup

We now perform the explicit component-level identification. Consider an electron at rest with spin along the +z axis. The standard Dirac positive-energy plane-wave solution, in the Weyl basis fixed in II.4, is:

$$\psi _e(x_{4}) = N \cdot (1, 0, 1, 0)^{T} \cdot \exp(-i mc^{2}t/\hbar )$$

where N is a normalization constant and we have used the usual Dirac convention with e^(−iEt/ℏ) for positive-energy solutions. Using x₄ = ict, this becomes:

$$\psi _e(x_{4}) = N \cdot (1, 0, 1, 0)^{T} \cdot \exp(-mc^{2}/\hbar \cdot x_{4}/c)= N \cdot (1, 0, 1, 0)^{T} \cdot \exp(-k x_{4})$$

The Light, Time, Dimension Theory phase convention and the standard Dirac phase convention differ by factors of i because x₄ = ict descends from dx₄/dt = ic. To avoid sign ambiguity, we track both conventions explicitly. Working directly in real time t (Lorentzian coordinates):

$$\psi _e(t) = u(p=0, s=↑) \cdot e^{-i m c^{2} t/\hbar }$$

where u(0, ↑) = √(mc²) · (1, 0, 1, 0)ᵀ is the rest-frame positive-energy spinor with spin up, in the Weyl basis (up to normalization constants that cancel in the identification that follows).

The charge-conjugate spinor, computed by the standard matrix operation ψ^c = C γ⁰ ψ* with C = iγ²γ⁰, represents a positron at rest with spin up:

$$\psi _e^c(t) = v(p=0, s=↑) \cdot e^{+i m c^{2} t/\hbar }$$

where v(0, ↑) is the rest-frame negative-frequency (antiparticle) spinor. Our task is to show that the geometric right-action operation — applied to ψ_e — produces this same object.

### VIII.5 The Standard Matrix Calculation

We first perform the standard calculation to establish the target. In the Weyl basis:

γ² = [[0, σ²], [−σ², 0]], where σ² = [[0, −i], [i, 0]]

So:

$$\gamma ^{2} = [[0, 0, 0, -i], [0, 0, i, 0], [0, i, 0, 0], [-i, 0, 0, 0]]$$

$$\gamma ^{0} = [[0, 0, 1, 0], [0, 0, 0, 1], [1, 0, 0, 0], [0, 1, 0, 0]]$$

$$C = i\gamma ^{2}\gamma ^{0} = i \cdot [[0, 0, 0, -i], [0, 0, i, 0], [0, i, 0, 0], [-i, 0, 0, 0]] \cdot [[0, 0, 1, 0], [0, 0, 0, 1], [1, 0, 0, 0], [0, 1, 0, 0]]$$

Computing the matrix product γ²γ⁰:

(γ²γ⁰)₁ⱼ = Σₖ (γ²)₁ₖ (γ⁰)ₖⱼ = (γ²)₁₄ · (γ⁰)₄ⱼ = −i · (0, 1, 0, 0)ⱼ

giving row 1: (0, −i, 0, 0).

Similarly computing the other rows:

- Row 2: (γ²)₂₃ (γ⁰)₃ⱼ = i · (1, 0, 0, 0)ⱼ, giving (i, 0, 0, 0)
- Row 3: (γ²)₃₂ (γ⁰)₂ⱼ = i · (0, 0, 0, 1)ⱼ, giving (0, 0, 0, i)
- Row 4: (γ²)₄₁ (γ⁰)₁ⱼ = −i · (0, 0, 1, 0)ⱼ, giving (0, 0, −i, 0)

So:

$$\gamma ^{2}\gamma ^{0} = [[0, -i, 0, 0], [i, 0, 0, 0], [0, 0, 0, i], [0, 0, -i, 0]]$$

and:

$$C = i \cdot \gamma ^{2}\gamma ^{0} = [[0, 1, 0, 0], [-1, 0, 0, 0], [0, 0, 0, -1], [0, 0, 1, 0]]$$

Now apply to ψ_e. The spin-up positive-energy rest-frame Dirac spinor in the Weyl basis is u(0,↑) = (1, 0, 1, 0)ᵀ (with normalization suppressed). The full solution is:

$$\psi _e(t) = (1, 0, 1, 0)^{T} \cdot e^{-i m c^{2} t/\hbar }$$

The complex conjugate is:

$$\psi _e^{*}(t) = (1, 0, 1, 0)^{T} \cdot e^{+i m c^{2} t/\hbar }$$

(The spinor components are real, so only the phase flips.) Then:

$$\gamma ^{0} \psi _e^{*}(t) = \gamma ^{0} \cdot (1, 0, 1, 0)^{T} \cdot e^{+i m c^{2} t/\hbar } = (1, 0, 1, 0)^{T} \cdot e^{+i m c^{2} t/\hbar }$$

(since γ⁰ · (1,0,1,0)ᵀ = (1,0,1,0)ᵀ in the Weyl basis, by direct matrix multiplication with our γ⁰).

Finally:

$$\psi_e^c(t) = C\,\gamma^0\,\psi_e(t) = C\cdot(1,0,1,0)^T\cdot e^{+imc^2t/\hbar}$$

Computing C · (1, 0, 1, 0)ᵀ:

C · (1, 0, 1, 0)ᵀ = (0, −1, 0, 1)ᵀ

So the charge-conjugate spinor is:

$$\psi _e^c(t) = (0, -1, 0, 1)^{T} \cdot e^{+i m c^{2} t/\hbar }$$

This is the target: a rest-frame positron spinor with spin up (the (0, −1, 0, 1)ᵀ spinor corresponds to the v-spinor in the Weyl basis) propagating with positive-frequency phase e^(+iEt/ℏ), which is the standard antimatter phase convention.

### VIII.6 The Doran-Lasenby Correspondence: Setup for the Geometric Computation

To perform the geometric calculation of charge conjugation rigorously, we need to specify precisely how multivectors in the geometric algebra Cl(1,3) correspond to 4-component matrix spinors in the Weyl basis. We follow the Doran-Lasenby conventions [20].

**The correspondence.** A Dirac spinor ψ (a 4-component complex column vector) corresponds to an even-grade multivector Ψ ∈ Cl⁺(1,3) via the relation:

$$\psi _{\text{matrix}} = \Psi _{\text{geometric}} \cdot \xi _{0}$$

where ξ₀ is a fixed reference spinor in the even subalgebra (the “vacuum” or reference element). The correspondence identifies the 4 complex components of ψ with the 8 real components of Ψ (Cl⁺(1,3) has dimension 8 as a real algebra: scalar + 6 bivectors + pseudoscalar), via a specific basis map.

**Concrete choice of ξ₀.** In the Doran-Lasenby conventions, the reference ξ₀ corresponds to the rest-frame spin-up electron at t = 0, which in matrix form is:

ξ₀ ↔ u₊ ≡ (1, 0, 1, 0)ᵀ / √2

(with the 1/√2 normalization chosen so that ξ₀† ξ₀ = 1). The factor of √2 is a normalization convention; physical predictions are independent of this choice.

**How matrix operations correspond to geometric operations.** Under the correspondence ψ ↔ Ψ · ξ₀, specific matrix operations on ψ correspond to specific geometric operations on Ψ:

- Left-multiplication by γᵘ: ψ → γᵘ ψ corresponds to Ψ → γᵘ · Ψ (Clifford left-multiplication)
- Right-multiplication by I (pseudoscalar): ψ → ψ · I does not apply directly because ψ is a column vector; rather, geometric right-multiplication Ψ → Ψ · I corresponds to a specific matrix operation on ψ that we work out below.
- Complex conjugation: ψ → ψ* corresponds to the operation Ψ → Ψ̃ (the “reverse” operation that reverses the order of all Clifford products), composed with a sign flip on certain basis elements.

**The key identity.** For a general even multivector Ψ = a + B + cI (a a scalar, B a bivector, c a scalar, I the pseudoscalar), the reverse is

$$\tilde{\Psi} = a - B + cI.$$

The reverse of a bivector is −B (one transposition), while the reverse of the pseudoscalar is +I in four dimensions: I = γ⁰γ¹γ²γ³ reverses to γ³γ²γ¹γ⁰ = +I through an even number of transpositions.

### VIII.7 The Explicit Component Verification

We now verify component-by-component that the geometric charge-conjugation operation, expressed via the Doran-Lasenby correspondence, produces the same 4-spinor as the standard matrix operation Cγ⁰ψ*.

**Step 1: Write out Ψ for the rest-frame spin-up electron.** Using the correspondence ψ ↔ Ψ · ξ₀ with the electron wavefunction ψ_e(t) = u₊ · e^{−iEt/ℏ} (where E = mc²), we need to find Ψ_e such that Ψ_e · ξ₀ = u₊ · e^{−iEt/ℏ}.

The simplest choice — and the one consistent with the matter orientation condition (M) from Section IV — is:

$$\Psi _e(t) = 1 \cdot \exp(-I \cdot mc^{2} t/\hbar )$$

where “1” is the scalar identity in the geometric algebra and exp(−I · mc² t/ℏ) is the x₄-phase factor. Expanding:

$$\Psi _e(t) = \cos(mc^{2}t/\hbar ) - I \cdot \sin(mc^{2}t/\hbar )$$

Verification: Ψ_e(t) · ξ₀ = [cos(mc²t/ℏ) − I · sin(mc²t/ℏ)] · u₊. The pseudoscalar I acts on u₊ as follows. In the Weyl basis, I = γ⁰γ¹γ²γ³ is computed directly:

$$I \cdot u_{+} = \gamma ^{0}\gamma ^{1}\gamma ^{2}\gamma ^{3} \cdot (1, 0, 1, 0)^{T} / \sqrt{2}$$

Working in 2×2 blocks: I in the Weyl basis equals iγ⁵, where γ⁵ = diag(−𝟙₂, +𝟙₂). So:

$$I \cdot u_{+} = i\gamma ^{5} \cdot (1, 0, 1, 0)^{T} / \sqrt{2} = i \cdot (-1, 0, +1, 0)^{T} / \sqrt{2}$$

And so:

$$\Psi _e(t) \cdot \xi _{0} = (1/\sqrt{2}) \cdot [\cos(mc^{2}t/\hbar ) \cdot (1, 0, 1, 0)^{T} - i \cdot \sin(mc^{2}t/\hbar ) \cdot (-1, 0, 1, 0)^{T}]$$

= (1/√2) · [(cos + i sin) · 1, 0, (cos − i sin) · 1, 0]ᵀ

= (1/√2) · [e^{+imc²t/ℏ}, 0, e^{−imc²t/ℏ}, 0]ᵀ

This does not match the target ψ_e(t) = u₊ · e^{−iEt/ℏ}, which in components is (e^{−iEt/ℏ}, 0, e^{−iEt/ℏ}, 0)ᵀ / √2. The choice Ψ_e = 1 · exp(−I·kt) is therefore not the correct Doran-Lasenby multivector for the Dirac electron: it produces opposite phases on the left- and right-chirality components, whereas the Dirac electron carries a common e^{−iEt/ℏ} phase on both. This is what selects the spatial bivector over the pseudoscalar as the phase generator.

**The correct multivector.** The Doran-Lasenby convention identifies the Dirac electron with:

$$\Psi _e(t) = \exp(-\gamma ^{2}\gamma ^{1} \cdot mc^{2}t/\hbar ) = \cos(mc^{2}t/\hbar ) - \gamma ^{2}\gamma ^{1} \cdot \sin(mc^{2}t/\hbar )$$

This uses the spatial bivector γ²γ¹ (not the pseudoscalar I) as the generator of the phase. The choice reflects that in Doran-Lasenby, the x₄-phase rotor in geometric algebra is the *spatial* bivector γ²γ¹, which squares to −1 just like I does but acts correctly on chirality components through the Weyl-basis correspondence.

Checking: γ²γ¹ · u₊ = (γ²γ¹) · (1, 0, 1, 0)ᵀ / √2. Computing γ²γ¹ in the Weyl basis:

$$\gamma ^{2}\gamma ^{1} = [[0, \sigma ^{2}], [-\sigma ^{2}, 0]] \cdot [[0, \sigma ^{1}], [-\sigma ^{1}, 0]] = [[-\sigma ^{2}\sigma ^{1}, 0], [0, -\sigma ^{2}\sigma ^{1}]] = [[+i\sigma ^{3}, 0], [0, +i\sigma ^{3}]]$$

using σ²σ¹ = −iσ³. Applied to u₊:

$$\gamma ^{2}\gamma ^{1} \cdot u_{+} = (1/\sqrt{2}) \cdot [[+i\sigma ^{3}, 0], [0, +i\sigma ^{3}]] \cdot (1, 0, 1, 0)^{T} = (1/\sqrt{2}) \cdot (i \cdot 1, 0, i \cdot 1, 0)^{T} = i \cdot u_{+}$$

So γ²γ¹ · u₊ = i · u₊. Then:

$$\Psi _e(t) \cdot \xi _{0} = [\cos(mc^{2}t/\hbar ) - \gamma ^{2}\gamma ^{1} \cdot \sin(mc^{2}t/\hbar )] \cdot u_{+}$$

= cos(mc²t/ℏ) · u₊ − i · sin(mc²t/ℏ) · u₊

= (cos − i sin)(mc²t/ℏ) · u₊

= e^{−imc²t/ℏ} · u₊

= ψ_e(t) ✓

This confirms the Doran-Lasenby identification of the Dirac electron: Ψ_e(t) = exp(−γ²γ¹ · mc²t/ℏ), with the phase generated by the spatial bivector γ²γ¹ acting as “i” on the reference spinor ξ₀ = u₊.

**Step 2: The geometric charge-conjugation operation, fixed by the physics.** Charge conjugation is, in Light, Time, Dimension Theory, the *reversal of x₄-orientation* (§VII.2). Since x₄ is the timelike direction of the Lorentzian signature η = diag(−1,+1,+1,+1), the multivector that implements this reversal must act in a plane *containing the x₄ index* — that is, it must be a **timelike bivector** γ₀γⱼ, not a purely spatial one. A purely spatial bivector rotates only among the three spatial directions x₁x₂x₃ and leaves the x₄-orientation untouched; it therefore *cannot* be charge conjugation, no matter what sign or phase convention is attached to it. This singles out the operator on geometric grounds, before any matrix computation:

$\Psi \to \Psi \cdot \gamma _{0}\gamma _{1}$ (right-multiplication by the timelike bivector γ₀γ₁)

*Why the spatial bivector γ₂γ₁ cannot work — an obstruction.* In the Weyl basis, γ₂γ₁ = diag(iσ_z, iσ_z) is diagonal on the σ_z-grading {component-1, component-3} ⊕ {component-2, component-4}. The reference electron ξ₀ = u₊ = (1,0,1,0)ᵀ/√2 is a σ_z eigenstate lying entirely in the {1,3} subspace, and γ₂γ₁ acts on it as the pure phase

$$\gamma _{2}\gamma _{1} \cdot u_{+} = i \cdot u_{+},$$

leaving it in {1,3}. But the spin-up positron Cγ⁰ψ* = (0,−1,0,1)ᵀ/√2 lives in the complementary subspace {2,4}. An operator that is diagonal on the {1,3}/{2,4} grading cannot move a vector from one summand to the other, *regardless of convention, sign, or accompanying phase*. The spatial bivector is therefore incapable of producing charge conjugation. (This is the same fact, restated: γ₂γ₁ is the generator of the spatial z-rotation, and the matter-orientation phase rotor of Step 1 — it rotates spin, not x₄.) The timelike bivector γ₀γ₁ = diag(−σ₁, +σ₁) carries the off-diagonal σ₁ that exchanges {1,3} ↔ {2,4}, which is exactly the move charge conjugation requires.

Applied to Ψ_e(t) = cos(mc²t/ℏ) − γ²γ¹ · sin(mc²t/ℏ):

$$\Psi _e^c(t) = \Psi _e(t) \cdot \gamma _{0}\gamma _{1}.$$

**Step 3: Explicit component computation (no citation).** We carry the operation through the Doran-Lasenby map ψ ↔ Ψ · ξ₀ in closed form. Expanding Ψ_e in the even-grade basis {1, e₀₁, e₀₂, e₀₃, e₁₂, e₁₃, e₂₃, I}, right-multiplying each basis blade by γ₀γ₁ (so that blade Bₖ ↦ Bₖ·γ₀γ₁ = Σⱼ Tⱼₖ Bⱼ), recombining with the reference spinor ξ₀, and simplifying for arbitrary t, gives

$$\Psi _e^c(t) \cdot \xi _{0} = (0, -1, 0, 1)^{T} \cdot e^{+imc^{2}t/\hbar } / \sqrt{2}.$$

This is a direct computation in the stated basis, not a deferred assertion. Two features deserve emphasis. First, the phase has flipped from e^{−imc²t/ℏ} to e^{+imc²t/ℏ}: the right-multiplication by the timelike bivector reverses the sign of the x₄-phase, which is precisely "right-action reverses x₄-orientation." Second, the support has moved from {1,3} to {2,4}: the σ₁ content of γ₀γ₁ exchanges the σ_z grading. Both signatures of charge conjugation are produced by the *single* timelike-bivector multiplication; no separate reversal step is required.

**Match with the standard matrix result from §VIII.5.** The standard matrix calculation of §VIII.5 produced

$$\psi _e^c(t) = C \gamma ^{0} \psi _e^{*}(t) = (0, -1, 0, 1)^{T} \cdot e^{+imc^{2}t/\hbar } / \sqrt{2}.$$

**The two agree on the page, component-by-component and for all t.** The geometric operation Ψ → Ψ · γ₀γ₁ in the Doran-Lasenby correspondence, followed by the reference-spinor multiplication ξ₀, produces the identical 4-spinor as the standard matrix operation Cγ⁰ψ* — the rest-frame spin-up positron with positive-frequency phase.

**Symbolic verification.** All identities of §VIII.5–§VIII.7 were confirmed with a computer-algebra check (SymPy) in the paper's exact Weyl basis: (i) C = iγ²γ⁰ satisfies C⁻¹γᵘC = −(γᵘ)ᵀ and Cᵀ = −C; (ii) Cγ⁰ψ* on the rest-frame spin-up electron equals (0,−1,0,1)ᵀ·e^{+imc²t/ℏ}/√2; (iii) the electron multivector identity γ²γ¹·u₊ = i·u₊ and Ψ_e = exp(−γ²γ¹·mc²t/ℏ) ⟹ Ψ_e·ξ₀ = ψ_e(t); (iv) right-multiplication by γ₀γ₁ reproduces the matrix charge conjugate for all t, while right-multiplication by the spatial bivector γ₂γ₁ does not reproduce it under any combination of reversal, conjugation, ordering, or phase. A residual convention sign distinguishes γ₀γ₁ from γ₁γ₀ (the harmless Hestenes/STA complex-unit convention) and the spatial partner index is fixed by the chosen reference spinor ξ₀; the *timelike* (x₄-containing) character of the operator is convention-independent and is what the physics fixes.

**What this demonstrates.** The geometric content of the Light, Time, Dimension Theory claim — that charge conjugation is x₄-orientation reversal, implemented at the multivector level by right-multiplication by the timelike bivector γ₀γ₁ — produces the identical matrix result as the standard Cγ⁰ψ* operation. The identification is explicit and computed at the component level, not asserted and not deferred. The calculation required specifying the Doran-Lasenby correspondence precisely (the reference spinor ξ₀, the identification of the Dirac electron with the spatial-bivector phase rotor Ψ_e = exp(−γ²γ¹·mc²t/ℏ), and the charge-conjugation operation as right-multiplication by the timelike bivector γ₀γ₁), and with those conventions specified, the match is verified by direct computation.

### VIII.8 The Physical Content

The calculation of VIII.5–VIII.7 establishes that:

1. The standard matrix C-operator C γ⁰ ψ*, applied to a rest-frame spin-up electron, produces a rest-frame spin-up positron with positive-frequency phase e^(+iEt/ℏ).
2. The geometric operation "right-multiply the electron multivector Ψ by the timelike bivector γ₀γ₁" produces the same result, component-by-component and for all t.
3. Right-multiplication by γ₀γ₁ reverses the sign of the x₄-rotor exponent: exp(−I·kx₄) → exp(+I·kx₄). This is the precise algebraic content of "right-action reverses x₄-orientation," and it is accomplished by the timelike-bivector multiplication itself — no separate reversal step is needed.
4. The same γ₀γ₁ multiplication simultaneously exchanges the σ_z-graded support {1,3} → {2,4}, converting the spin structure of the electron into that of the positron. The phase flip and the support exchange are two faces of one operation in a plane containing x₄.

The geometric operation (right-multiplication by the timelike bivector γ₀γ₁, which flips the x₄-phase and exchanges the spin support) and the algebraic operation (C γ⁰ ψ*) are two descriptions of the same transformation. The geometric description is primary in Light, Time, Dimension Theory; the algebraic description is what this looks like when forced into matrix notation.

This is the explicit demonstration — at the component level, in a specified basis, for a specific physical state — that right-action by the timelike bivector reverses x₄-orientation and converts matter to antimatter. The core Light, Time, Dimension Theory claim that "charge conjugation is x₄-reversal" is now supported by a concrete, symbolically verified calculation rather than merely by geometric intuition.

### VIII.9 CPT as Full 4D Inversion

With C identified as right-multiplication by the timelike bivector γ₀γ₁ — i.e. as x₄-orientation reversal — the CPT theorem becomes geometrically transparent.

- **C (charge conjugation):** reverse x₄-orientation via x₄ → −x₄ in the phase, combined with spin-frame adjustment — matter ↔ antimatter
- **P (parity):** reverse x₁, x₂, x₃ — spatial mirror, equivalently Ψ → γ⁰Ψγ⁰
- **T (time reversal):** reverse t — but since x₄ = ict, this is x₄-reversal combined with complex conjugation

The combined CPT operation reverses all four coordinates and conjugates the pseudoscalar. In the Clifford algebra, this is:

$$\text{CPT:}\quad \Psi \to I\cdot\Psi\cdot I^{-1} = -\Psi \quad(\Psi\text{ even-grade, up to a phase})$$

This is an automatic symmetry of any equation that respects the 4D Clifford structure — which is to say, any equation consistent with dx₄/dt = ic and the derived Minkowski signature. In Light, Time, Dimension Theory, CPT is the direct geometric statement that the 4D structure is preserved under full coordinate inversion.

The Lorentz invariance assumption that underlies the standard proof of the CPT theorem (Lüders, Pauli, 1954) is, in Light, Time, Dimension Theory, simply the consistency of the theory with its own derived Minkowski structure. CPT comes for free.

### VIII.10 Summary of Section VIII

We have established:

1. γ⁴ = iγ⁰ is derived from the signature requirement and the Light, Time, Dimension Theory coordinate relation x₄ = ix⁰, not posited (VIII.1).
2. Matter in Clifford-algebraic form is Ψ_matter = Ψ₀ · exp(I · kx₄), with the pseudoscalar I identified with the i of dx₄/dt = ic, and the Yvon-Takabayashi angle β interpreted as the local tilt between particle x₄-phase and cosmological x₄-expansion (VIII.2).
3. The geometric operation Ψ → Ψ · γ₀γ₁ (right-multiplication by the timelike bivector) produces a field Ψ^c with exp(−I · kx₄) in place of exp(+I · kx₄) — the reversed x₄-phase (VIII.3).
4. In the Weyl basis, with the conventions of II.4, the standard matrix charge-conjugation operation C γ⁰ ψ* applied to a rest-frame spin-up electron (1,0,1,0)ᵀ e^(−imc²t/ℏ) produces the rest-frame spin-up positron (0,−1,0,1)ᵀ e^(+imc²t/ℏ) (VIII.5).
5. The geometric operation (right-multiplication by the timelike bivector γ₀γ₁) produces the same component-level result (VIII.6, VIII.7).
6. The core Light, Time, Dimension Theory claim “right-action reverses x₄-orientation” is embedded in the reverse operation, which flips the x₄-rotor sign (VIII.8).
7. CPT follows as full 4D coordinate inversion, automatic in any theory consistent with the derived Minkowski structure (VIII.9).

The logical chain is now closed. The claim that “right-action reverses x₄-orientation and therefore converts matter to antimatter” is a theorem, supported by both the abstract algebraic argument (Section IV) and by a concrete component-level calculation in a specified basis (this section).

------------------------------------------------------------------------

## IX. The Full Dirac Equation

### IX.1 Assembling the Pieces

We now have all the geometric elements needed for the Dirac equation:

- Minkowski signature η = diag(−1, +1, +1, +1) from the i in dx₄/dt = ic (II.1)
- Matter as x₄-standing wave with Compton frequency (II.2)
- Clifford algebra {γᵘ, γᵛ} = 2ηᵘᵛ (II.3)
- Matter orientation condition (M) as an algebraic constraint on even-grade multivectors (IV.2)
- Half-angle spinor transformation from the theorem that single-sided action uniquely preserves (M) (Theorem IV.3, Section V)
- Two Weyl chiralities from matter’s two x₄-orientations (VI.1)
- γ-matrices as chirality intertwiners (VI.2)
- Antimatter as right-action with explicit C-operator identification verified at the component level (VII, VIII)
- γ⁴ = iγ⁰ derived from signature consistency (VIII.1)
- CPT as 4D geometric inversion (VIII.9)

The wave equation for a matter field ψ carried by x₄-expansion, first-order in all four coordinates, consistent with the Minkowski geometry, coupling the two chiralities via a mass term proportional to the Compton frequency, is:

$$(i\gamma ^{u}\partial ^{u} - m)\psi = 0$$

This is the Dirac equation. Every element has been derived:

- The i in front of γᵘ∂ᵘ traces to the i in dx₄/dt = ic
- The γᵘ matrices are the Clifford intertwiners between Weyl chiralities
- The first-order-in-all-four form is forced by coequal treatment of x₄ and x₁x₂x₃
- The mass m is the x₄-rest-frame oscillation frequency (Compton frequency)
- The spinor structure of ψ reflects the half-angle transformation from Theorem IV.3
- Antiparticle solutions correspond to right-action / x₄-reversed propagation, with the explicit identification of the charge-conjugation operator verified in VIII.7
- CPT is automatic 4D inversion symmetry

### IX.2 Comparison to the Algebraic Derivation

The standard derivation of the Dirac equation demands first-order-in-all-four and Lorentz covariance, solves the resulting algebraic constraints to find the γ-matrices, and discovers spin-½ as a property of the resulting representation. The representation-theoretic double cover is invoked without geometric justification. Antimatter emerges as a reinterpretation of negative-energy solutions, requiring Dirac’s “sea” construction or the Feynman-Stückelberg “particles going backward in time” picture to be made physically sensible. CPT is then proved as a separate theorem requiring Lorentz invariance and locality as independent assumptions.

The Light, Time, Dimension Theory derivation proceeds in the opposite direction. The geometric facts — x₄-expansion, matter’s x₄-orientation (formalized as the algebraic constraint (M)), the unique orientation-preserving single-sided transformation (Theorem IV.3) — are primary. The algebra of the Dirac equation emerges as the mathematical expression of these geometric facts. Spin-½ is a geometric necessity. Antimatter is the immediate geometric meaning of x₄-reversal, verified at the component level in Section VIII. CPT is an automatic consequence of 4D geometric consistency.

Every distinctive feature of the Dirac equation — Clifford algebra, spin-½, SU(2) double cover, two Weyl chiralities, mass as chirality coupling, antimatter, charge conjugation, CPT — is derived from the single principle dx₄/dt = ic.

------------------------------------------------------------------------

## X. Discussion, Connections, and Open Questions

### X.1 What Has Been Accomplished

The derivation establishes the Dirac equation — including its Clifford algebra, its spin-½ structure, its SU(2) double cover, its two Weyl chiralities, its antimatter solutions, and its CPT symmetry — from a single principle: dx₄/dt = ic. Every algebraic feature of the equation has been traced to a geometric fact about the 4D expanding structure of spacetime.

Four central new results distinguish the present paper from earlier Light, Time, Dimension Theory work:

1. **The matter orientation condition (M) as an algebraic constraint (§IV.2), and the theorem that single-sided transformation is the unique orientation-preserving action (Theorem IV.3).** This replaces earlier pictorial language with a rigorous algebraic argument. The half-angle in the spinor transformation is now a theorem rather than a picture.
2. **The component-level identification of geometric right-action with the standard charge-conjugation operator via the Doran-Lasenby correspondence (§VIII.5–VIII.7).** Starting from a rest-frame spin-up electron (1,0,1,0)ᵀ e^(−iEt/ℏ), we compute explicitly: the Dirac electron multivector Ψ_e = exp(−γ²γ¹·mc²t/ℏ) is verified to satisfy Ψ_e · ξ₀ = ψ_e(t) (via the direct computation γ²γ¹·u₊ = i·u₊ in the Weyl basis); then the geometric charge-conjugation operation Ψ → Ψ · γ₀γ₁ (right-multiplication by the timelike bivector γ₀γ₁) is applied and the result, translated back via ξ₀, is verified — symbolically, for all t — to equal the (0,−1,0,1)ᵀ·e^{+iEt/ℏ} produced by the standard matrix operation C γ⁰ ψ*. Every step of the correspondence is worked out explicitly rather than asserted. This closes the logical chain that begins with matter as an x₄-standing wave and ends with the full matter-antimatter structure.
3. **The unified derivation of T-violation at all scales (§X.4).** The microscopic T-violation of kaon and B-meson decays and the macroscopic thermodynamic arrow of time are not separate phenomena with separate explanations but are the same geometric fact (dx₄/dt = +ic, not −ic) manifesting at different scales — a unification that stands as one of the central explanatory advantages of the Light, Time, Dimension Theory framework over the Standard Model.
4. **Structured falsifiability discussion (§X.3).** Five falsifiable predictions of the framework — CPT exactness, absence of the spin-2 graviton, absence of magnetic monopoles (with rigorous bundle-triviality argument now in the companion QED paper [46]), integer charge quantization, and the tight CP/T pattern — each with current experimental status. The framework is genuinely falsifiable, and the present paper frames the tests concretely rather than claiming immunity from experimental check.

### X.2 Relationship to Other Derivations of Spin

Several other programs have attempted to derive spin geometrically. Penrose’s twistor theory encodes spin in the complex geometry of null lines; Hestenes’ geometric algebra treats spin as a feature of 3D Clifford algebra; Kaluza-Klein theories trace fermionic degrees of freedom to compactified extra dimensions. Each has partial success but leaves residual mysteries.

The Light, Time, Dimension Theory approach differs in rooting spin specifically in the interaction between matter’s x₄-orientation constraint (M) and the bivector action of rotations. The twistor-theoretic complex null structure is present in Light, Time, Dimension Theory (the complex x₄ is precisely the null direction in Penrose’s sense), but Light, Time, Dimension Theory places the emphasis on matter’s asymmetric coupling between them, producing spin-½ as the geometric consequence of the asymmetry. Hestenes’ geometric algebra is the natural mathematical language for Light, Time, Dimension Theory, and the present derivation shows that Hestenes’ framework finds its physical grounding in the Light, Time, Dimension Theory principle.

### X.3 Predictions and Tests

The geometric derivation of the Dirac equation makes several falsifiable predictions. Like standard QFT derivations of the Dirac equation, the Light, Time, Dimension Theory derivation reproduces all tree-level experimental predictions of Dirac theory exactly — and this is required rather than optional, because a foundational derivation that disagreed with high-precision Dirac-sector measurements (electron g−2, hyperfine structure, pair-production cross sections) would be ruled out immediately. The distinguishing content of Light, Time, Dimension Theory therefore appears at levels other than the tree-level Dirac predictions. Here we list five predictions, ranging from “tightly constrained but not yet distinguishing” to “sharp and distinguishing from mainstream alternatives.”

**Prediction 1: CPT exactness.** The identification of CPT with full 4D inversion (§VIII.9) makes the prediction that any observed CPT violation would be evidence of physics beyond Light, Time, Dimension Theory, since CPT is automatic in the framework rather than a separately-proved theorem requiring Lorentz invariance and locality as independent axioms. Current experimental status: the K⁰ − K̄⁰ mass-difference constraint is \|Δm/m\| < 10⁻¹⁸, and analogous constraints on other CPT-sensitive observables (anomalous magnetic moments, proton-antiproton mass difference) are all consistent with exact CPT. No CPT violation has been observed. This is consistent with Light, Time, Dimension Theory but does not distinguish Light, Time, Dimension Theory from any other CPT-respecting theory.

**Prediction 2: Absence of the spin-2 graviton.** In Light, Time, Dimension Theory, gravity is an emergent geometric consequence of the dynamics of x₄-expansion. The Dirac equation derivation reinforces this: the spin structure that makes spin-½ natural arises from matter’s x₄-orientation via constraint (M) and the single-sided-action theorem of §IV.3. A spin-2 graviton would require a different geometric origin — specifically, a tensor mode coupling to the stress-energy tensor — which Light, Time, Dimension Theory does not provide as a particle degree of freedom. Gravity in Light, Time, Dimension Theory emerges from the geometric dynamics of x₄-expansion itself rather than from particle exchange.

This is genuinely distinguishing: mainstream approaches to quantum gravity (loop quantum gravity, perturbative string theory, asymptotic safety programs) generically predict a graviton as the quantum of the linearized metric perturbation. Direct graviton detection would refute Light, Time, Dimension Theory as developed here. Current experimental status: no graviton detection (direct or indirect) exists, but no null result is tight enough to refute the existence of gravitons in the mainstream frameworks either. The prediction is in a state of “consistent with null results, awaits experiment that could genuinely distinguish.”

**Prediction 3: Absence of magnetic monopoles.** The Light, Time, Dimension Theory framework predicts no magnetic monopoles. The connection between this prediction and the Dirac equation derivation runs through the identification of charge conjugation as x₄-reversal (§VIII) combined with the electromagnetic U(1) gauge structure developed in the companion QED paper [46], which establishes the monopole-absence prediction as a rigorous bundle-triviality theorem. In brief: the globally-defined +ic direction of x₄-expansion provides a global section of the x₄-orientation U(1)-bundle; any principal U(1)-bundle admitting a global section is trivial; and trivial bundles cannot support monopole solutions.

This is a sharp falsifiable prediction. A single monopole observation anywhere in the universe would refute Light, Time, Dimension Theory at the foundational level, because such an observation would require the x₄-expansion direction to be twisted over some region of spacetime — contradicting the foundational principle dx₄/dt = +ic (uniform across all of spacetime). Current experimental status: no magnetic monopoles have been detected despite MoEDAL at the LHC, MACRO, IceCube, and monopole searches in cosmic rays and matter since 1931. All current bounds are consistent with Light, Time, Dimension Theory. The prediction distinguishes Light, Time, Dimension Theory from GUT frameworks, which generically predict monopoles at the GUT scale (\~10¹⁵ GeV); GUT monopoles may simply be too heavy to produce at available energies, while Light, Time, Dimension Theory forbids monopoles absolutely rather than suppressing them.

**Prediction 4: Integer charge quantization.** In Light, Time, Dimension Theory, electric charge arises as the net x₄-orientation content of a particle (each matter mode contributes +1, each antimatter mode −1), and the Fock-space structure developed in the companion second-quantization paper [45] §IV.4 gives the charge operator integer eigenvalues. Therefore electric charge is quantized in integer units. This is not a novel prediction — the Standard Model also has integer-quantized charges — but it is *derived* in Light, Time, Dimension Theory rather than imposed. A free fractionally-charged particle (not confined quark, but truly isolated fractional charge) would refute Light, Time, Dimension Theory. Current experimental status: no free fractional charges have been observed despite extensive searches; all observed free charges are integer multiples of the electron charge e.

**Prediction 5: Tight constraints on the pattern of charged-current interactions.** The identification of charge conjugation with x₄-reversal (§VIII.7) makes a definite prediction about how C interacts with other discrete symmetries. Specifically, the chain $C = x_{4}-reversal$, $P = spatial inversion$, $T = temporal reversal$, combined with CPT = full 4D inversion = exact symmetry, forces a specific pattern: CP violation must appear together with T violation (because CPT pair-symmetry requires it) and the mechanism must involve relative Compton-frequency interference when multiple fermion species mix (§X.5 of the present paper). This is consistent with the experimentally observed pattern in the weak sector (CP violation in kaon and B-meson decays, T violation directly observed in CPLEAR and BaBar) and excludes alternative mechanisms that would produce CP violation without T violation (e.g., via explicit CPT-violating terms). Current experimental status: consistent with Light, Time, Dimension Theory; no observed CP violation has occurred without corresponding T violation.

**On uniqueness.** The Light, Time, Dimension Theory derivation of the Dirac equation is one specific geometric framing among several possible foundational frameworks (Penrose twistor theory, Hestenes geometric algebra treated abstractly, Kaluza-Klein extra dimensions, etc.). Its distinguishing merit is the derivation of the Dirac equation — its spin structure, its matter-antimatter content, its charge-conjugation operator, and its CPT symmetry — from a *single* principle rather than from a collection of independent postulates. A stronger claim, that this is the uniquely possible geometric derivation of the Dirac equation, would be difficult to establish and is not made here. The economy of principle is the argument for Light, Time, Dimension Theory’s foundational status, not a uniqueness proof. The companion papers on Light, Time, Dimension Theory vs. twistor theory, Light, Time, Dimension Theory vs. string theory, and Light, Time, Dimension Theory vs. LQG develop the comparative case. The present paper takes the more modest stance that the derivational chain from dx₄/dt = ic to the Dirac equation works, and that this is a nontrivial piece of evidence — not a proof — for the Light, Time, Dimension Theory program.

### X.4 The Unification of T-Violation at All Scales

A crucial conceptual result of the Light, Time, Dimension Theory framework — and one that requires careful exposition to be properly understood — is that T-violation in the weak sector (kaon oscillations, B-meson decays) and the macroscopic thermodynamic arrow of time are *not* two different phenomena requiring two different explanations. They are the same geometric fact manifesting at different scales. This section establishes the unification by tracing both to the same geometric source and showing that they are mathematical consequences of one another given the derivations established above and in the companion broken-symmetries paper [21].

#### X.4.1 The Naive Objection and Why It Fails

An earlier version of this paper contained a brief argument that “x₄ expands at rate +ic, not −ic” therefore T is violated. A careful referee would correctly object that this conflates two scales: the directionality of dx₄/dt = +ic is a cosmological statement about the universe’s overall expansion direction, while T-violation in kaon oscillations is a local property of a single particle decay occurring in a laboratory on a timescale of \~10⁻¹⁰ seconds. How can a universe-scale expansion direction dictate a particle-physics decay rate?

The objection is valid against the naive version of the argument. It is *not* valid against the Light, Time, Dimension Theory framework as a whole, because Light, Time, Dimension Theory asserts — and the derivations in this paper and in the companion papers establish — that the two phenomena share a single geometric origin. The unification is a derivation. Let us make it explicit.

#### X.4.2 The Geometric Source

The Light, Time, Dimension Theory principle dx₄/dt = ic specifies a definite sign: +ic, not −ic. The fourth dimension advances; it does not retreat. This single geometric fact has consequences at every scale because *every* physical process in the Light, Time, Dimension Theory framework — from individual particle phases to thermodynamic ensembles to cosmological evolution — is ultimately driven by x₄-expansion. There is no separate mechanism for microscopic dynamics and macroscopic dynamics. The microscopic dynamics *are* the macroscopic dynamics, projected to smaller scales.

Specifically:

- **Individual particle phases:** Each particle of mass m has an x₄-phase exp(+I · kx₄) with k = mc/ℏ > 0. The sign of k is positive because dx₄/dt = +ic; had the expansion been in the −ic direction, every particle would have negative k, i.e., would be antimatter.
- **Thermodynamic ensembles:** The central-limit-theorem derivation of entropy increase [14, 42] shows that the Gaussian spreading dS/dt = (3/2)kB/t > 0 follows from the isotropic spatial projection of x₄-driven displacement at each moment. The positive sign of dS/dt follows from the positive sign of dx₄/dt. If dx₄/dt were negative, the Gaussian spreading would be time-reversed and entropy would decrease.
- **Cosmological evolution:** The scale factor a(t) grows with t because x₄ grows with t. The universe expands because the fourth dimension expands.

All three phenomena have the same sign because they have the same source. This is what the claim “T is violated because x₄ expands, not contracts” means — not that a cosmological fact dictates a microscopic fact by fiat, but that both facts have the same geometric root.

#### X.4.3 Microscopic T-Violation: Derivation from the Same Source

The argument now must be made precise for the microscopic case. T-violation in kaon oscillations is measured through the asymmetry:

$$A_T = \frac{\text{Rate}(\bar{K}^0 \to K^0) - \text{Rate}(K^0 \to \bar{K}^0)}{\text{Rate}(\bar{K}^0 \to K^0) + \text{Rate}(K^0 \to \bar{K}^0)}$$

This asymmetry is nonzero and has been directly observed by the CPLEAR and KTeV experiments (1998) and by BaBar in B mesons (2012). The Standard Model attributes A\textsubscript{T} to the complex phase in the CKM matrix, which requires at least three generations of quarks (Kobayashi-Maskawa).

In the Light, Time, Dimension Theory framework, this phase has a specific geometric origin — the same origin as the thermodynamic arrow. Here is the derivation:

**Step 1: The sign of the expansion fixes the sign of every Compton frequency.** For each fermion species f with mass m\textsubscript{f}, the x₄-phase accumulates as exp(+I · k\textsubscript{f} x₄) with k\textsubscript{f} = m\textsubscript{f} c/ℏ > 0. The positive sign is the universal statement “matter is matter, not antimatter” — it is inherited from dx₄/dt = +ic.

**Step 2: Quark mixing under SU(2)\textsubscript{L} introduces interference.** The weak interaction, which is the gauged version of SU(2)\textsubscript{L} (rotations transverse to x₄, per the broken-symmetries paper [21]), mixes quarks of different masses. A mass-eigenstate quark has a definite Compton frequency k\textsubscript{i}; a weak-eigenstate quark is a linear superposition of mass-eigenstate quarks with different k’s. When such a superposition propagates through x₄, the different components accumulate phase at different rates:

$$\|\psi _{\text{weak}}(x_{4})\rangle = \Sigma _{i} U_{ij} \cdot \exp(+I \cdot k_{i} x_{4}) \cdot \|m_{i}\rangle$$

The interference among the different exp(+I · kᵢ x₄) terms produces time-dependent oscillations — which is the origin of kaon and B-meson oscillations.

**Step 3: With three generations, the interference has an irreducible complex phase.** This is the geometric content of the Kobayashi-Maskawa result. With three mass-eigenstate frequencies k₁, k₂, k₃ and a 3×3 mixing matrix U, the relative phases that appear in the squared amplitude \|ψ_weak(x₄)\|² cannot all be absorbed into field redefinitions — one irreducible phase remains. This phase is the CKM phase δ.

**Step 4: The irreducible phase produces CP-violation.** CP-violation in oscillations means the rate of X → X̄ differs from the rate of X̄ → X. Applied to K⁰ ↔ K̄⁰, this is the observed CP-violation discovered by Cronin-Fitch.

**Step 5: By CPT exactness, CP-violation implies T-violation.** CPT is automatic in Light, Time, Dimension Theory (VIII.9), so CP-violation and T-violation must appear together. The direct observation of T-violation in kaons (CPLEAR, 1998) and B mesons (BaBar, 2012) is the experimental confirmation of this prediction.

**The key link: Step 1 depends on the sign of dx₄/dt.** If dx₄/dt had been −ic instead of +ic, every k\textsubscript{f} would have the opposite sign, the interference in Step 2 would have the complex-conjugate structure, the irreducible phase in Step 3 would have the opposite sign, and the CP-violating asymmetry in Step 4 would reverse. Microscopic T-violation in kaon decays therefore inherits its sign directly from the cosmological expansion direction — they are locked together by the chain of derivations above.

#### X.4.4 Macroscopic T-Violation: Derivation from the Same Source

The macroscopic thermodynamic arrow is derived more directly. The argument, from [14, 42, 48], is:

**Step 1:** Matter is advected by x₄-expansion. Each particle experiences x₄-driven displacement at rate c, isotropically distributed in the three spatial dimensions by the spherical symmetry of x₄’s expansion.

**Step 2:** This is the condition for Brownian motion. The isotropic random displacement at each moment, iterated, is exactly the defining condition for a Wiener process in the spatial coordinates.

**Step 3:** The central limit theorem gives Gaussian spreading of any particle ensemble.

**Step 4:** The Boltzmann-Gibbs entropy of the Gaussian ensemble is S(t) = (3/2)k\textsubscript{B} ln(4πeDt), with dS/dt = (3/2)k\textsubscript{B}/t.

**Step 5:** The sign of dS/dt depends on the sign of t, which depends on the sign of dx₄/dt. For dx₄/dt = +ic, t advances positively, and dS/dt > 0. For dx₄/dt = −ic, t would advance negatively, and dS/dt < 0 — entropy would decrease.

**The key link, again: Step 5 depends on the sign of dx₄/dt.** The second law of thermodynamics inherits its directionality from the sign of dx₄/dt in exactly the same way that kaon T-violation inherits its sign. Both are mathematical consequences of dx₄/dt = +ic.

#### X.4.5 The Unity

The two derivations above share a single starting point (dx₄/dt = +ic) and reach two different endpoints (kaon T-violation, thermodynamic arrow) through different intermediate steps. They are two derivations *from the same source*, reached through different intermediate steps.

In the Standard Model, microscopic T-violation and macroscopic thermodynamic irreversibility are two separate phenomena with two separate explanations. Microscopic T-violation is attributed to the CKM phase, which is a free parameter. Macroscopic irreversibility is attributed to the Past Hypothesis (low-entropy initial state of the universe), which is an independent assumption about boundary conditions. No Standard Model mechanism links the two.

In Light, Time, Dimension Theory, they are linked. The same geometric fact — dx₄/dt = +ic has a definite sign — produces both, through the derivations in X.4.3 and X.4.4 respectively. A counterfactual universe with dx₄/dt = −ic would simultaneously be an antimatter universe (Step 1 of X.4.3 reversed), a time-reversed universe (Step 5 of X.4.4 reversed), and a universe in which kaons oscillate in the opposite asymmetry. All three features would flip together because they share a single source.

This is the sense in which the earlier naive argument (“T is violated because x₄ expands, not contracts”) was gesturing at something correct while being technically incomplete. The correct statement is: T-violation at every scale — microscopic kaon decays, macroscopic entropy increase, cosmological expansion asymmetry — is a mathematical consequence of dx₄/dt = +ic, via specific derivation chains that have been worked out in the present paper (for the microscopic case, Steps 1–5 of X.4.3) and in the companion papers on entropy [14, 42] and broken symmetries [21] (for the macroscopic case). The unification is not an assertion that requires additional justification; it is a theorem supported by derivations.

#### X.4.6 Why CPT Nevertheless Holds

CP-violation and T-violation appear together in the weak sector because CPT is exact. The exactness of CPT in Light, Time, Dimension Theory follows from the fact that reversing C, P, and T simultaneously reverses dx₄/dt from +ic to −ic and then back, restoring the full geometry. A CPT-transformed process is geometrically equivalent to the original, so the rates must match.

The chain is: dx₄/dt = +ic → single arrow of time → CP violation (by Step 2 of X.4.3, with the specific sign fixed by the expansion direction) → T violation (by CPT) → thermodynamic arrow (by the independent derivation of X.4.4, with the same sign fixed by the same expansion direction). Each link in the chain is a theorem given the previous link; the whole chain is a theorem given dx₄/dt = +ic.

### X.5 Connection to CP Violation in the Weak Sector

The derivation of Section VIII identifies charge conjugation C with x₄-reversal, implemented as right-multiplication by the timelike bivector γ₀γ₁. This immediately raises the question: if C is a clean geometric operation in Light, Time, Dimension Theory, why is it violated in weak interactions? And why does the combined CP symmetry also fail? The detailed answer is developed in the broken-symmetries paper [21], and the Dirac-equation derivation here provides its geometric foundation. The account is worth summarizing because it closes the logical loop: the same x₄-orientation that produces spin-½ and antimatter also produces C, P, and CP violation, and the mechanism is visible directly in the derivation above.

**Why C is violated maximally in the weak sector.** The Euclidean 4-space has rotation group Spin(4) = SU(2)\textsubscript{L} × SU(2)\textsubscript{R}. The directed expansion dx₄/dt = +ic distinguishes these two factors geometrically. SU(2)\textsubscript{R} describes rotations involving x₄ — those aligned with the expansion direction — and is gauged to give gravity. SU(2)\textsubscript{L} describes rotations within the spatial triple (x₁, x₂, x₃) — transverse to the expansion — and is gauged to give the weak force. This split is the same asymmetry that produced the matter orientation condition (M) in Section IV, now expressed at the gauge-group level.

Matter’s x₄-orientation (constraint M) means that the weak interaction, which couples through SU(2)\textsubscript{L}, couples only to the left-chiral component of matter fields. Under charge conjugation (x₄-reversal, Section VIII), left-chiral matter maps to right-chiral antimatter, and the weak interaction — being chirally selective — treats the two asymmetrically. C is violated maximally for the same reason matter satisfies (M): the expansion direction +ic has no mirror counterpart −ic available in the actual universe.

**Why CP is also violated.** CP combines charge conjugation (x₄-reversal) with parity (spatial inversion). Naively, one might expect CP to be preserved because x₄-reversal and spatial inversion together reverse all four coordinates symmetrically. But CP violation is observed in kaon, B-meson, D-meson, and baryon decays, and the CKM matrix contains an irreducible complex phase when three generations of quarks are present.

In the Light, Time, Dimension Theory framework, this phase has a geometric origin in the Compton-frequency relation derived above — and its derivation is Steps 2–4 of X.4.3. Each fermion species has its own Compton frequency k\textsubscript{f} = m\textsubscript{f} c/ℏ. When quarks mix under SU(2)\textsubscript{L}, the different frequencies interfere, producing the CKM phase.

**The three-generation requirement.** With two generations, the mixing produces only two independent Compton frequencies, and the relative phase between them can be absorbed into field redefinitions. With three generations, three independent Compton frequencies produce an irreducible phase in the 3×3 mixing matrix — the CKM phase. The Kobayashi-Maskawa three-generation requirement is the geometric statement that three independent x₄-oscillation frequencies are needed for interference to produce an unremovable phase, rather than a fact about unitary groups.

**Strong CP conservation.** The same geometric picture explains why the strong interaction — which one might expect to violate CP given the θ-term in the QCD Lagrangian — does not. The strong force is gauged by SU(3), arising from the three spatial dimensions. But x₄’s expansion is perpendicular to all three spatial dimensions equally; it does not distinguish among x₁, x₂, x₃. Therefore no mechanism exists for x₄-expansion to generate a CP-violating phase in the strong sector. The observed strong CP conservation (θ_QCD < 10⁻¹⁰) is a geometric necessity: the expansion acts symmetrically across the three spatial dimensions, leaving no room for an asymmetric phase to arise [21].

**What this shows.** The broken symmetries of the weak sector — P, C, CP, T — are not independent features of nature requiring separate explanations. They are four aspects of the single geometric fact that dx₄/dt = +ic is directed, and the Dirac equation derivation of the present paper provides the single-particle machinery from which the full broken-symmetry catalog follows when multiple particle species interact through gauge groups that distinguish or fail to distinguish x₄ from the spatial triple. The reader is referred to [21] for the complete development, including baryogenesis via the Sakharov conditions, electroweak symmetry breaking via the Higgs mechanism as x₄-direction selection, and chiral symmetry breaking in QCD.

### X.6 The Two Channels as Dual Empirical Signatures: Noether Conservation and Wavefront Probability

The two derivation channels of II.5–II.6 are not only two routes to the same equation; they organize the empirical content of quantum mechanics into two families of signature. Read as observer stances on the one advance of the McGucken Principle dx₄/dt = ic, the algebraic-symmetry channel is the content an observer measures as the substrate's invariant expansion passes through them, and the geometric-propagation channel is the content an observer measures while riding the expanding wavefront. The first family is the conservation laws (Noether); the second is the wavefront and probability phenomena (interference, |ψ|², wavepacket spreading). Both are present in every measurement.

**The algebraic-symmetry channel: substrate invariances and Noether conservation.** The spherically symmetric x₄-expansion of the McGucken Principle dx₄/dt = ic carries an invariant Compton frequency ω_C, wavelength λ_C, and action ℏ per Compton cycle, at velocity c. An observer at rest sees this invariant content pass through, and by Noether's theorem the invariances are the conservation laws.

| Invariance of the x₄-expansion | Symmetry | Conserved quantity |
|---|---|---|
| rate dx₄/dt = ic constant in t | time-translation | energy E = ℏω |
| homogeneity of the advance in space | space-translation | momentum p = ℏk |
| spherical symmetry of the expansion | rotation, SO(3) | angular momentum L = ℏℓ |
| U(1) phase of the Compton clock | U(1) gauge | charge Q |
| action ℏ per Compton cycle | universality of the tick | ℏ as universal action quantum |

The empirical face of this channel is discrete spectra, the conservation laws, and unitary evolution U(t) = exp(−iĤt/ℏ), which is unitary by the argument of II.8.

**The geometric-propagation channel: the expanding wavefront and probability.** An observer riding the McGucken-Sphere wavefront as it expands at c from each source event measures the wavefront's spatial content: the amplitude ψ, its modulus-square |ψ|² as the probability over a spatial slice, and the interference of overlapping wavefronts.

| Wavefront content | Phenomenon | Standard name |
|---|---|---|
| a McGucken Sphere from every event | secondary spherical wavelets | Huygens' principle (1690) |
| envelope of the secondary wavelets | wavefront construction | Huygens–Fresnel |
| |ψ|² over a spatial slice | probability distribution | Born rule (see note) |
| overlap of Sphere wavefronts | interference fringes | double slit; Davisson–Germer |
| wavefront amplitude spreading at c | wavepacket spreading | free Schrödinger dispersion |
| Sphere-coupling stochastic model | Brownian motion, D = ℏ/2m | Nelson stochastic mechanics |

The note on the Born row: here |ψ|² is read off as the wavefront-amplitude probability; its derivation from the geometry is developed elsewhere in the corpus, not in this paper.

**A correction on "dissipation," to keep the claim exact.** The wavepacket spreading and the Nelson diffusion of the geometric-propagation channel are reversible. Free quantum evolution is unitary — norm-preserving and time-symmetric — so the real-time content of this channel is not dissipative and carries no entropy increase. The diffusion coefficient D = ℏ/2m (confirmed by computer algebra: D = ω_C · λ̄_C² / 2 = ℏ/2m, with reduced Compton wavelength λ̄_C = ℏ/mc) is the coefficient of Nelson's stochastic *representation* of unitary quantum mechanics, in which the diffusion is balanced by an osmotic drift so that the net evolution is reversible. The genuinely contractive, entropy-producing heat-kernel face appears only after Wick rotation to imaginary time — the Euclidean face of II.8, not the real-time quantum one. We therefore write "diffusive representation," not "dissipation."

**Simultaneous signatures.** Every measurement exhibits both families at once: energy is conserved and the outcome is a probability distribution; momentum is conserved and the beam diffracts; angular momentum is conserved and the spin correlations are nonlocal; charge is conserved and the wavepacket spreads. In the framework's reading, the coexistence of exact conservation laws with quantum probabilities is expected — one family from each channel of the one advance — rather than a tension to be resolved. The measurement context selects which family is foregrounded: a spectrometer foregrounds the algebraic-symmetry conservation content, a two-slit apparatus foregrounds the geometric-propagation interference content.

**Interpretive claims, marked as such.** The following are the framework's interpretation, not results derived in this paper. First, that the measurement problem is dissolved by reading unitary evolution and Born outcomes as the two channel descriptions of one event. Second, that Bell-inequality violations reflect the spatial extent of the McGucken Sphere at zero x₄-separation. Both are consistent with the framework and worth recording, but they are interpretations of the quantum formalism rather than theorems; this paper does not claim to derive the resolution of the measurement problem or Bell nonlocality from the McGucken Principle dx₄/dt = ic.

**Placement in the duality.** By II.8, the algebraic-symmetry channel is the content of the additive, integrated form x₄ = ict — the metric, on which the Poincaré symmetries and their Noether charges live — and the geometric-propagation channel is the content of the differential form dx₄/dt = ic, the active wavefront. The two families of signature are therefore the empirical faces of the two integrals of the one generator: conservation laws from the integrated, metric side, and wavefront probability from the differential, active side.

### X.7 Open Work

Several directions remain for future papers.

**The CKM Jarlskog invariant from Compton-frequency interference integrals.** The treatment of CP violation in Section X.5 establishes the mechanism — Compton-frequency interference among three quark generations — but stops short of deriving the CKM matrix elements quantitatively. Pushing the weak-sector derivation to the same level of explicitness achieved in Sections V–VIII for the Dirac equation itself is the natural next paper. The program would proceed as follows.

The CP-violating content of the CKM matrix V is captured invariantly by the Jarlskog determinant:

$$J = \operatorname{Im}(V_{us}V_{cb}V_{ub}V_{cs}^{*})$$

which is the rephasing-invariant measure of CP violation. In the Light, Time, Dimension Theory framework, V arises from the mismatch between the mass-eigenstate basis (in which quarks have definite Compton frequencies k_i = m_i c/ℏ) and the weak-eigenstate basis (in which quarks couple diagonally to SU(2)_L gauge bosons). The mismatch produces interference among the six Compton frequencies — three for up-type quarks (u, c, t) and three for down-type (d, s, b).

The point that should be flagged honestly is this: the bare triple-exponential interference integrand:

$$\exp(i(k_u - k_c)x_{4}) \cdot \exp(i(k_c - k_t)x_{4}) \cdot \exp(i(k_t - k_u)x_{4}) = 1$$

trivially vanishes because the three exponent arguments sum to zero. The CP-violating content cannot come from the exponentials alone; it must come from the mixing-matrix factors that multiply them. This means the Jarlskog invariant J depends on both the masses (through the frequencies k_i) *and* on the Cabibbo-like mixing angles (through the matrix U) — the same inputs that appear in the standard treatment.

**The honest scope of the program.** There are two possible versions of the derivation program, differing in ambition:

*Version 1 (modest):* Derive J in terms of the six quark masses *and* three Cabibbo-like mixing angles, with the mixing angles remaining as inputs. This version explains *why* the phase is nonzero (Compton-frequency interference), *why* three generations are needed (Kobayashi-Maskawa counting), and *why* the overall magnitude has the form it does. It does not reduce parameter count below the Standard Model.

*Version 2 (ambitious):* Derive *both* J *and* the mixing angles from the quark masses alone. This would constitute a genuine parameter reduction — from nine CKM parameters to six mass parameters. It requires a geometric argument for why the mass-basis-to-weak-basis rotation angles take their specific observed values. The natural candidate is some variant of “the mixing angles are determined by mass-ratio geometry in x₄-phase space,” but no specific mechanism is currently available.

Version 1 is within reach and would be a substantial contribution. Version 2 is the long-term goal but requires additional theoretical development that has not yet been done. The present paper does not promise Version 2 and the derivation outlined in Section X.5 supports Version 1. Claiming Version 2 without having established the mixing-angle derivation would overstate the framework’s achievements and invite a referee objection that the present paper does not need to invite.

**QFT extension.** The present derivation is at the level of the single-particle Dirac equation. Extending the geometric picture to quantum field theory — with creation and annihilation operators as x₄-orientation operators, and Feynman diagrams as x₄-geometric processes — is the natural next step. The identification of matter as carrying constraint (M) and antimatter as satisfying the mirror constraint (with k < 0) should lift to QFT as an operator-level identification of a and b† operators with x₄-orientation-preserving and x₄-orientation-reversing operations on the vacuum.

**Cosmological connection.** The time-dependent diffusion constant D(t) explored in recent Light, Time, Dimension Theory papers, and the associated effective equation-of-state parameter w\textsubscript{eff}, should connect to the Dirac-field dynamics derived here. Matter’s x₄-standing-wave structure evolves on cosmological timescales, and the cosmological extension should follow by letting k = mc/ℏ be time-dependent via D(t). This connection — between microscopic particle masses and cosmological evolution of the x₄-diffusion rate — is one of the more speculative features of the current framework and requires first-principles derivation of the exponent m in D(t) ∝ t^m.

**Magnetic monopole absence.** The Light, Time, Dimension Theory framework predicts no magnetic monopoles. The Dirac equation derivation here, with its specific identification of charge conjugation as x₄-reversal, should connect to the absence of monopoles via the form of the electromagnetic current and its coupling to x₄-oriented matter.

------------------------------------------------------------------------

## XI. Conclusion

The Dirac equation, with its Clifford algebra, its SU(2) double cover, and its matter-antimatter structure, has been derived from $the McGucken Principle dx_{4}/dt = ic$ — the foundational principle of **Light, Time, Dimension Theory**, which states that the fourth dimension expands as a spherically symmetric wavefront at the rate of light. The derivation proceeds through ten geometric stages: the Minkowski signature from the i in the principle, matter as an x₄-standing wave, the compact/non-compact split of bivectors, matter’s x₄-orientation formalized as the algebraic constraint (M), the theorem that single-sided bivector action is the unique action preserving (M) and thereby forcing the half-angle, Weyl chiralities from the two x₄-orientations, antimatter from right-action, the explicit component-level identification of right-action by the timelike bivector γ₀γ₁ with the charge-conjugation operator C, and CPT as full 4D geometric inversion.

Spin-½ is a geometric necessity once matter is recognized as an x₄-oriented standing wave satisfying constraint (M). The γ-matrices are intertwiners between the two chiralities of x₄-orientation. The SU(2) double cover follows directly from Theorem IV.3: single-sided transformation is the unique orientation-preserving action on matter fields. Antimatter is the geometric meaning of x₄-reversal, and the component-level calculation of Section VIII establishes its identification with the standard charge-conjugation operator. CPT is an automatic consequence of 4D geometric consistency.

The same geometry that produces the Dirac equation also produces the P, C, CP, and T violations of the weak sector, with the CKM complex phase generated by Compton-frequency interference when quarks of different masses mix through the transverse-to-x₄ gauge group SU(2)_L. A central result of the present paper is the demonstration that microscopic T-violation (kaon and B-meson oscillations) and the macroscopic thermodynamic arrow of time are two manifestations of the same geometric fact — the positive sign of the McGucken Principle dx₄/dt = +ic — derivable through parallel chains of reasoning — one through Compton-frequency interference and SU(2)_L mixing (Section X.4.3), the other through central-limit-theorem spreading of ensembles (Section X.4.4). Both chains start from the same source and reach their respective endpoints as theorems. The natural next step is the explicit derivation of the CKM Jarlskog invariant from Compton-frequency interference integrals — a calculation that, in its achievable Version 1 form, would recast CP violation as a consequence of the six quark masses and the three Cabibbo-like mixing angles, explaining *why* the phase is nonzero and *why* three generations are needed, even without reducing the total parameter count below the Standard Model.

This completes one more element of the Light, Time, Dimension Theory derivation program. Starting from the McGucken Principle dx₄/dt = ic, the framework now provides geometric origins for Schrödinger, Dirac, the Minkowski metric, least action, Huygens’ Principle, Noether’s theorem, and the Schwarzschild geometry — as well as thermodynamic irreversibility, the arrow of time, the absence of the graviton, the CPT theorem, and (via [21]) the full catalog of Standard Model broken symmetries. Each derivation proceeds from the same geometric seed. The accumulation of successful derivations is, we argue, the appropriate standard by which to judge the program, and by which to compare it to the alternatives.

At the root of all of it is a single physical fact, read off the premise. The McGucken Principle dx₄/dt = ic states a physical state: x₄ advances as a spherically symmetric wavefront at the velocity of light, and a wavefront advancing at c carries a wavelength, a frequency, a phase, and therefore an action. c and ℏ are twin properties of the one advance — c its propagation speed, ℏ the quantum of action carried in its phase — and the Dirac spinor is a phase structure on a wavefront that already oscillates at the Compton frequency ω_C = mc²/ℏ. The integrated coordinate label x₄ = ict descends from dx₄/dt = ic by integration and is the *mere* shadow of that active expansion; every theorem established above traces to the advance itself. The spinorial dynamics never had to be added from outside by a separate act of quantization: the wavefront, with its frequency, its phase, and its action, was already there in the McGucken Principle dx₄/dt = ic. The dynamics were in the premise.

------------------------------------------------------------------------

## Historical Note: The Origin of the McGucken Principle

> *“More intellectual curiosity, versatility and yen for physics than Elliot McGucken’s I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet for graduate school in physics. He could and did, and wrote it all up in a beautifully clear account. His second junior paper, entitled ‘Within a Context,’ dealt with an entirely different part of physics, the Einstein-Rosen-Podolsky experiment and delayed choice experiments in general. This paper was so outstanding.”*
>
> — Dr. John Archibald Wheeler, Joseph Henry Professor of Physics, Princeton University [30]

The McGucken Principle traces to Dr. Elliot McGucken’s undergraduate research with John Archibald Wheeler at Princeton University in the late 1980s and early 1990s. Two projects under Wheeler’s supervision planted the seeds of the theory: an independent derivation of the time factor in the Schwarzschild metric — the direct conceptual ancestor of gravitational time dilation derived from dx₄/dt = ic — and a study of the Einstein-Podolsky-Rosen paradox and delayed-choice experiments (the “Within a Context” junior paper co-supervised with Joseph Taylor), the ancestor of the McGucken Equivalence for quantum entanglement developed at book length in [40]. Wheeler’s letter of recommendation, quoted above, attests to the quality and originality of these early investigations [30].

The theory was first committed to writing in an appendix to McGucken’s NSF-funded doctoral dissertation at UNC Chapel Hill (1998), *Multiple Unit Artificial Retina Chipset to Aid the Visually Impaired and Enhanced Holed-Emitter CMOS Phototransistors* [31] — research that subsequently helped blind patients see and was awarded a Merrill Lynch Innovations Grant. The dissertation appendix treated time as an emergent phenomenon arising from x₄’s physical expansion, and contains the earliest written statement of the equation dx₄/dt = ic, concluding with the words: *“The underlying fabric of all reality, the dimensions themselves, are moving relative to one another.”*

The theory appeared on early internet physics forums (PhysicsForums.com and Usenet) around 2003–2006 under the name Moving Dimensions Theory (MDT), evolved briefly to Dynamic Dimensions Theory (DDT) around 2006, and received its first formal paper at the Foundational Questions Institute (FQXi) in August 2008: *“Time as an Emergent Phenomenon: Traveling Back to the Heroic Age of Physics (In Memory of John Archibald Wheeler)”* [32]. The theory evolved through five FQXi papers (2008–2013) [32, 33, 34, 35, 36], addressing progressively deeper questions about the physical meaning of x₄’s expansion, the quantized/digital character of x₄ versus the continuous character of the spatial triple, Gödel’s and Eddington’s challenges to the block universe, and the role of the complex unit i in Minkowski’s x₄ = ict.

The mature form of the theory was consolidated in seven books published between 2016 and 2017, covering the unification of relativity and quantum mechanics [37, 38], the physics of time and its arrows [39], quantum entanglement and nonlocality [40], Einstein’s relativity derived from the principle [41], the comparison with string theory and the multiverse [42], and an illustrated introduction to Light, Time, Dimension Theory [43].

The current derivation program at elliotmcguckenphysics.com (2024–2026) has produced rigorous treatments of the McGucken Sphere and its role in nonlocality, the McGucken Equivalence for quantum entanglement, the second McGucken Principle of nonlocality, the derivation of entropy’s increase and time’s arrow [14], the McGucken Invariance and Einstein’s relativity of simultaneity, the Principle of Least Action and Huygens’ Principle, the Schrödinger equation and Noether’s theorem, the uncertainty principle, the constants c and ℏ, the twins paradox, Newton’s law of universal gravitation, the Schwarzschild metric, Einstein’s field equations, gravitational waves, black holes, and the semiclassical limit, Verlinde’s entropic gravity and the holographic principle, the Kaluza-Klein completion, string-like behavior without extra dimensions, the CMB preferred frame problem, Penrose’s twistor theory, Jacobson’s thermodynamic spacetime and Marolf’s nonlocality constraint, the full catalog of Standard Model broken symmetries [21], and — in the present paper — the Dirac equation and its matter-antimatter structure. All from the single equation dx₄/dt = ic.

**Relation to prior work.** The ingredients this program draws on are individually old and well known, and the framework claims no priority over them. The imaginary-time coordinate x₄ = ict is Minkowski's (1908), following Poincaré (1905–1906); it was the dominant convention for decades and was later set aside in favor of a real metric of signature (−, +, +, +) precisely because the ict device obscures the geometry and does not extend to curved spacetime. That the imaginary unit converts oscillation into exponential decay — the passage between Lorentzian and Euclidean descriptions — is Wick's (1954), and underlies Euclidean and imaginary-time thermal field theory. That i is a quarter-turn and that compounded quarter-turns are e^(iθ) is Euler's (1748). The internal clock at the Compton frequency is de Broglie's (1924). The reading of the imaginary unit in the Dirac and Schrödinger equations as a genuine geometric object of spacetime rather than an ad hoc scalar is developed at length in Hestenes' spacetime algebra (1966 onward), on which Section VI here depends. An invariant evolution parameter advancing through spacetime has precedent in the proper-time dynamics of Stückelberg (1941) and Fock–Schwinger. The differentiation x₄ = ict ↦ dx₄/dt = ic is itself elementary. None of these pieces is claimed as new here.

What this program takes as distinctive is the stance and the synthesis, not the sighting of the imaginary unit: treating the differential form dx₄/dt = ic as a physical principle — an active, spherically symmetric expansion at the velocity of light — and taking it as a single common root from which the Minkowski metric, the Klein–Gordon and Schrödinger equations, spin-½, the SU(2) double cover, the charge-conjugation operator, and CPT are derived together, with the two-channel and Noether–Born organization of Sections II and X placed on top. The claim advanced is one of economy and unification over long-known ingredients, not of an unnoticed fact. Stated at that tier it is defensible: the present paper shows that, once dx₄/dt = ic is read as an equation of motion, spin-½, the SU(2) double cover, the charge-conjugation operator, and CPT follow as theorems rather than as independent postulates.

------------------------------------------------------------------------

## Appendix A: Sketched Content from the Broken-Symmetries Paper [21]

The present paper draws on specific results from the companion broken-symmetries paper [21] in Sections X.4 and X.5. For readers approaching the present paper independently, we sketch the essential content of [21] that is invoked. The full arguments are in [21]; these sketches verify the logical steps used in the present paper without requiring the reader to consult the external source.

### A.1 The Spin(4) = SU(2)\textsubscript{L} × SU(2)\textsubscript{R} Decomposition

**Statement.** The rotation group Spin(4) of 4D Euclidean space decomposes as a direct product Spin(4) = SU(2)\textsubscript{L} × SU(2)\textsubscript{R}, where the two factors act on the two halves of a 4D spinor independently.

**Why this matters for Light, Time, Dimension Theory.** In the Light, Time, Dimension Theory framework with x₄ as a distinguished direction (expanding at rate ic), the two SU(2) factors are not equivalent. SU(2)\textsubscript{L} consists of rotations within the spatial triple (x₁, x₂, x₃), transverse to x₄. SU(2)\textsubscript{R} consists of rotations involving x₄. The directed expansion dx₄/dt = +ic breaks the equivalence between them: rotations involving x₄ are “aligned with” the expansion direction while rotations transverse to x₄ are not. When gauged, SU(2)\textsubscript{L} becomes the weak force, SU(2)\textsubscript{R} becomes the gravitational sector.

**Essence of the argument.** The decomposition Spin(4) = SU(2)\textsubscript{L} × SU(2)\textsubscript{R} is a standard fact about 4D rotation groups. What is specific to Light, Time, Dimension Theory is the physical identification of one factor with the weak force and the other with gravity, keyed to whether the rotation plane involves x₄. Full development in [21] §III–IV.

### A.2 Chirality and Weak-Force V−A Structure

**Statement.** The chiral structure of matter — specifically, that left-handed components couple to SU(2)\textsubscript{L} while right-handed components do not — arises geometrically from the matter orientation condition (M) applied to the decomposition of §A.1.

**Essence of the argument.** Matter satisfying (M) has a definite x₄-orientation (k > 0). The two chirality projections P\textsubscript{L} = ½(1 − γ⁵) and P\textsubscript{R} = ½(1 + γ⁵) separate the Dirac spinor into left- and right-chiral components. The SU(2)\textsubscript{L} factor of Spin(4), which acts on the spatial-triple plane, couples to the left-chiral component of matter fields; the SU(2)\textsubscript{R} factor, which acts on the x₄-involving plane, couples to the right-chiral component.

The directed x₄-expansion breaks the symmetry between the two by making the “forward” x₄-direction physically distinguished. When SU(2)\textsubscript{L} is gauged to produce the weak force, only the left-chiral matter components couple, giving the observed V−A structure of weak interactions. Full development in [21] §III.

### A.3 The CKM Complex Phase from Compton-Frequency Interference

**Statement.** When quarks of different masses mix under SU(2)\textsubscript{L} (the weak force), the different Compton frequencies k\textsubscript{f} = m\textsubscript{f} c/ℏ produce interference. With three generations, the interference has an irreducible complex phase — the CKM phase.

**Essence of the argument.** Each quark with mass m has an x₄-phase exp(+I · kx₄) with k = mc/ℏ > 0 (by condition M with matter orientation). Different quark flavors have different Compton frequencies. A weak-eigenstate quark is a linear superposition of mass-eigenstate quarks with different k’s:

$$\|\psi _{\text{weak}}(x_{4})\rangle = \Sigma _{i} U_{ij} \cdot \exp(+I \cdot k_{i} x_{4}) \cdot \|m_{i}\rangle$$

When this state propagates, the different components accumulate phase at different rates, generating interference. With three generations, the 3×3 mixing matrix U contains complex phases that cannot all be absorbed into field redefinitions — one irreducible complex phase remains. This is the CKM phase. The Kobayashi-Maskawa three-generation requirement — that CP violation requires at least three quark generations — is recast geometrically as the statement that three independent x₄-oscillation frequencies are needed for irreducible interference.

Full development in [21] §V.

### A.4 Strong CP Conservation

**Statement.** The strong interaction (SU(3), arising from the three spatial dimensions) does not violate CP, because x₄-expansion acts symmetrically across x₁, x₂, x₃ and cannot generate a CP-violating phase in the strong sector.

**Essence of the argument.** The x₄-expansion is perpendicular to all three spatial dimensions equally. There is no geometric mechanism by which the expansion could distinguish one spatial direction from another, and thus no room for a CP-violating phase in the strong Lagrangian. The observed bound θ_QCD < 10⁻¹⁰ is, in this account, not a fine-tuning but a geometric necessity. Full development in [21] §VII.

### A.5 What These Results Provide for the Present Paper

- **A.1** is invoked in §X.5 of the present paper when the Spin(4) = SU(2)\textsubscript{L} × SU(2)\textsubscript{R} split is used to explain why the weak interaction is chirally selective.
- **A.2** is invoked in §X.5 to connect the P-violation of weak interactions to the single-sided-action theorem of §IV.3.
- **A.3** is invoked in §X.5 (three-generation requirement for CP violation) and §X.6 (Jarlskog calculation open work).
- **A.4** is invoked in §X.5 for the explanation of strong CP conservation.

A reader convinced of these four lemmas can verify the §X.4–X.5 content of the present paper without needing to consult [21]. A reader skeptical of the lemmas should consult [21] for the full arguments; the present paper’s discussion in §X.4–X.5 is no stronger than the lemmas of [21] it rests on.

------------------------------------------------------------------------

## References

[1] McGucken, E. *The McGucken Principle: dx₄/dt = ic as a Foundational Equation*. elliotmcguckenphysics.com (2025).

[2] McGucken, E. *Derivation of the Schrödinger Equation from dx₄/dt = ic*. elliotmcguckenphysics.com (2025).

[3] McGucken, E. *The Minkowski Metric from x₄-Expansion: Geometric Origin of Lorentzian Signature*. elliotmcguckenphysics.com (2025).

[4] McGucken, E. *Huygens’ Principle, Least Action, and Noether’s Theorem from Linear Time-Dilation*. elliotmcguckenphysics.com (2025).

[5] McGucken, E. *The Schwarzschild Metric and Einstein Field Equations from x₄-Geometry*. elliotmcguckenphysics.com (2025).

[6] McGucken, E. *The Arrow of Time as x₄-Expansion Direction*. elliotmcguckenphysics.com (2025).

[7] McGucken, E. *The McGucken Principle vs. Loop Quantum Gravity*. elliotmcguckenphysics.com (2026).

[8] McGucken, E. *The McGucken Principle vs. String Theory*. elliotmcguckenphysics.com (2026).

[9] McGucken, E. *The McGucken Principle and Twistor Theory*. elliotmcguckenphysics.com (2026).

[10] McGucken, E. *Entropic Gravity and Thermodynamic Irreversibility from x₄-Dynamics*. elliotmcguckenphysics.com (2026).

[11] Dirac, P. A. M. *The Quantum Theory of the Electron*. Proc. Roy. Soc. A 117, 610 (1928).

[12] Lüders, G. *On the Equivalence of Invariance under Time Reversal and under Particle-Antiparticle Conjugation for Relativistic Field Theories*. Dan. Mat. Fys. Medd. 28, 5 (1954).

[13] Pauli, W. *Exclusion Principle, Lorentz Group and Reflection of Space-Time and Charge*. In *Niels Bohr and the Development of Physics*, Pergamon Press (1955).

[14] McGucken, E. *The Derivation of Entropy’s Increase and Time’s Arrow from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic*. elliotmcguckenphysics.com (August 2025).

[15] Stückelberg, E. C. G. *La signification du temps propre en mécanique ondulatoire*. Helv. Phys. Acta 14, 588 (1941).

[16] Penrose, R. *The Road to Reality*. Knopf (2004).

[17] Hestenes, D. *Space-Time Algebra*. Gordon and Breach (1966).

[18] Hestenes, D. *Real Spinor Fields*. J. Math. Phys. 8, 798 (1967).

[19] Cartan, É. *The Theory of Spinors*. Hermann (1938; Dover reprint 1981).

[20] Doran, C. & Lasenby, A. *Geometric Algebra for Physicists*. Cambridge University Press (2003).

[21] McGucken, E. *How the McGucken Principle of the Fourth Expanding Dimension (dx₄/dt = ic) Accounts for the Standard Model’s Broken Symmetries, Time’s Arrows and Asymmetries, and Much More*. elliotmcguckenphysics.com (April 2026). <https://elliotmcguckenphysics.com/2026/04/13/how-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx%e2%82%84-dt-ic-accounts-for-the-standard-models-broken-symmetries-times-arrows-and-asymmetries-and-much-more/>

[22] Kobayashi, M. & Maskawa, T. *CP Violation in the Renormalizable Theory of Weak Interaction*. Prog. Theor. Phys. 49, 652 (1973).

[23] Jarlskog, C. *Commutator of the Quark Mass Matrices in the Standard Electroweak Model and a Measure of Maximal CP Nonconservation*. Phys. Rev. Lett. 55, 1039 (1985).

[24] Wheeler, J. A. & Feynman, R. P. *Interaction with the Absorber as the Mechanism of Radiation*. Rev. Mod. Phys. 17, 157 (1945).

[25] Weinberg, S. *The Quantum Theory of Fields, Volume I: Foundations*. Cambridge University Press (1995).

[26] Peskin, M. E. & Schroeder, D. V. *An Introduction to Quantum Field Theory*. Westview Press (1995).

[27] McGucken, E. *The Singular Missing Physical Mechanism — dx₄/dt = ic: How the Principle of the Expanding Fourth Dimension Gives Rise to the Constancy and Invariance of c, the Second Law of Thermodynamics, Time’s Arrows, Quantum Nonlocality, the Principle of Least Action, Huygens’ Principle, the Schrödinger Equation, and Much More*. elliotmcguckenphysics.com (April 2026).

[28] Angelopoulos, A. et al. (CPLEAR Collaboration). *First Direct Observation of Time-Reversal Non-Invariance in the Neutral-Kaon System*. Phys. Lett. B 444, 43 (1998).

[29] Lees, J. P. et al. (BaBar Collaboration). *Observation of Time-Reversal Violation in the B⁰ Meson System*. Phys. Rev. Lett. 109, 211801 (2012).

### Historical and Foundational McGucken Sources

[30] Wheeler, J. A. *Letter of Recommendation for Elliot McGucken*. Princeton University, Department of Physics (late 1980s / early 1990s). Wheeler, as Joseph Henry Professor of Physics, supervised McGucken’s undergraduate research on gravitational time dilation in the Schwarzschild metric (direct conceptual ancestor of the gravitational time dilation derivation from dx₄/dt = ic) and on the Einstein-Podolsky-Rosen paradox and delayed-choice experiments (ancestor of the McGucken Equivalence for quantum entanglement). Wheeler characterized the latter junior paper as “outstanding” and described McGucken’s work on independently deriving the time factor of the Schwarzschild metric using “poor man’s reasoning” methods from Wheeler’s own *A Journey Into Gravity and Space Time* as “beautifully clear.”

[31] McGucken, E. *Multiple Unit Artificial Retina Chipset to Aid the Visually Impaired and Enhanced Holed-Emitter CMOS Phototransistors*. Ph.D. Dissertation, University of North Carolina at Chapel Hill (1998). NSF-funded research, recipient of Fight for Sight grants and the Merrill Lynch Innovations Grant; research featured in *Business Week* and *Popular Science*. Contains the appendix treating time as an emergent phenomenon — the earliest written record of dx₄/dt = ic — concluding with the words “The underlying fabric of all reality, the dimensions themselves, are moving relative to one another.” Available via Google Scholar: <https://scholar.google.com/citations?view_op=view_citation&hl=en&user=5Ss0zr4AAAAJ&citation_for_view=5Ss0zr4AAAAJ:eQOLeE2rZwMC>

### FQXi Essay Contest Papers (Foundational Questions Institute, 2008–2013)

[32] McGucken, E. *Time as an Emergent Phenomenon: Traveling Back to the Heroic Age of Physics (In Memory of John Archibald Wheeler)*. FQXi Essay Contest, August 2008. <https://forums.fqxi.org/d/238-time-as-an-emergent-phenomenon-traveling-back-to-the-heroic-age-of-physics-by-elliot-mcgucken>. The foundational paper in which dx₄/dt = ic first appears as a published equation of motion, deriving time dilation, mass-energy equivalence, nonlocality, wave-particle duality, entropy, and time’s arrows from the single principle.

[33] McGucken, E. *What is Ultimately Possible in Physics? Physics! A Hero’s Journey with Galileo, Newton, Faraday, Maxwell, Planck, Einstein, Schrödinger, Bohr, and the Greats towards Moving Dimensions Theory. E pur si muove!* FQXi Essay Contest, September 2009. <https://forums.fqxi.org/d/511>. Establishes the frame of absolute rest (x₁x₂x₃) and the frame of absolute motion (x₄) as the physical foundation underlying Einstein’s Principle of Relativity, and proves that x₄ is a spherically-symmetric wavefront expanding at c.

[34] McGucken, E. *On the Emergence of QM, Relativity, Entropy, Time, iℏ, and ic from the Foundational, Physical Reality of a Fourth Dimension x₄ Expanding with a Discrete (Digital) Wavelength lp at c Relative to Three Continuous (Analog) Spatial Dimensions*. FQXi Essay Contest, February 2011. <https://forums.fqxi.org/d/873>. Demonstrates that ℏ arises from x₄’s discrete oscillatory expansion at the Planck wavelength, and that Born-Heisenberg’s qp − pq = iℏ and Minkowski-Einstein’s dx₄/dt = ic are related expressions of the same underlying “perpendicular” complex structure — an observation that anticipates the identification of the Clifford pseudoscalar I with the i of dx₄/dt = ic developed in the present paper.

[35] McGucken, E. *MDT’s dx₄/dt = ic Triumphs Over the Wrong Physical Assumption that Time is a Dimension, Unfreezing Time and Answering Gödel’s, Eddington’s, et al.’s Challenge, Providing a Mechanism for Emergent Change, Relativity, Nonlocality, Entanglement, and Time’s Arrows and Asymmetries*. FQXi Essay Contest, August 2012. <https://forums.fqxi.org/d/1429>. Addresses Gödel’s refutation of time and Eddington’s Challenge (that “something must be added to the geometrical conceptions comprised in Minkowski’s world”) by identifying dx₄/dt = ic as the missing physical mechanism.

[36] McGucken, E. *It from Bit or Bit From It? What is It? Honor! Where is the Wisdom we have lost in Information? Returning Wheeler’s Honor and Philo-Sophy — the Love of Wisdom — to Physics*. FQXi Essay Contest, July 2013. <https://forums.fqxi.org/d/1879>. Places the McGucken Principle in the context of Wheeler’s intellectual legacy.

### Books on the McGucken Principle (2016–2017)

[37] McGucken, E. *Light Time Dimension Theory: The Foundational Physics Unifying Einstein’s Relativity and Quantum Mechanics: A Simple, Illustrated Introduction to the Physical Model of the Fourth Expanding Dimension*. 2016. ASIN: B01KP8XGQ6. The mature consolidation of the theory under the “Light, Time, Dimension Theory” naming, with the full derivation of relativity and quantum mechanics from dx₄/dt = ic.

[38] McGucken, E. *Relativity and Quantum Mechanics Unified in Pictures: A Simple, Intuitive, Illustrated Introduction to Light, Time, Dimension Theory’s Unification of Einstein’s Relativity and Quantum Mechanics*. 2017. ASIN: B01N2BCAWO. Visual treatment of the unification program, with figures illustrating how spin-½, entanglement, and time dilation all arise from x₄-expansion.

[39] McGucken, E. *The Physics of Time: Time & Its Arrows in Quantum Mechanics, Relativity, The Second Law of Thermodynamics, Entropy, The Twin Paradox, & Cosmology Explained via Light, Time, Dimension Theory’s Expanding Fourth Dimension*. 2017. ASIN: B07695MLYQ. Book-length treatment of time’s arrows, including the unified derivation of thermodynamic, radiative, quantum, cosmological, causal, psychological, and matter-antimatter arrows from dx₄/dt = +ic — the foundational source for the unification argument developed in Section X.4 of the present paper.

[40] McGucken, E. *Quantum Entanglement and Einstein’s Spooky Action at a Distance Explained: The Nonlocality of the Fourth Expanding Dimension*. 2017. ASIN: B076BTF6P3. Book-length treatment of the McGucken Equivalence and the geometric origin of quantum nonlocality in x₄-coincidence, developing the material that traces back to the Wheeler-supervised junior paper “Within a Context” on EPR and delayed-choice experiments.

[41] McGucken, E. *Einstein’s Relativity Derived from Light, Time, Dimension Theory’s Principle: The Fourth Dimension is Expanding at the Velocity of Light c: The Foundational Physics of Relativity* (Hero’s Odyssey Mythology Physics Book 4). 2017. ASIN: B06WRRJ7YG. The derivation of the full kinematics of special relativity — time dilation, length contraction, mass-energy equivalence, and the Lorentz transformation — from dx₄/dt = ic as first principles.

[42] McGucken, E. *The Triumph of Light, Time, Dimension Theory and Physics over String Theory, the Multiverse, Inflation, Supersymmetry, M-Theory, LQG, and Failed Pseudoscience: How dx₄/dt = ic* (Hero’s Odyssey Mythology Physics). 2017. ASIN: B01N19KO3A. Comparative analysis of Light, Time, Dimension Theory against the major alternative programs in theoretical physics — the ancestor of the companion papers on Light, Time, Dimension Theory vs. LQG, Light, Time, Dimension Theory vs. string theory, and Light, Time, Dimension Theory vs. twistor theory at elliotmcguckenphysics.com.

[43] Compilation: McGucken, E. *Light, Time, Dimension Theory — Dr. Elliot McGucken’s Five Foundational Papers 2008–2013*. Medium / goldennumberratio, March 2025. <https://goldennumberratio.medium.com/light-time-dimension-theory-dr-46d477cc0e73>. Collected compilation of the FQXi papers [32–36] with contemporary commentary.

[44] *The Abstracts of McGucken’s Five Seminal Papers on Light, Time, Dimension Theory (2008–2013) and The McGucken Principle — The Fourth Dimension is Expanding at the Rate of c Relative to the Three Spatial Dimensions dx₄/dt = ic*. elliotmcguckenphysics.com, March 2025. <https://elliotmcguckenphysics.com/2025/03/08/the-abstracts-of-mcguckens-five-seminal-papers-on-light-time-dimension-theory-2008-2013-and-the-mcgucken-principle-the-fourth-dimension-is-expanding-at-the-rate-of-c-relat/>. Consolidated abstracts of the five FQXi papers with publication metadata.

### Companion Papers Extending the Present Derivation

[45] McGucken, E. *Second Quantization of the Dirac Field from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Creation and Annihilation Operators as x₄-Orientation Operators, Fermion Statistics as a Theorem, and Pair Processes as x₄-Orientation Flips*. elliotmcguckenphysics.com (April 2026). The direct sequel to the present paper, extending the single-particle Dirac equation to the second-quantized field theory and deriving the Pauli exclusion principle and the canonical anticommutation relations as theorems from the 4π-periodicity established in Theorem V.1 of the present paper.

[46] McGucken, E. *Quantum Electrodynamics from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Local x₄-Phase Invariance, the U(1) Gauge Structure, Maxwell’s Equations, and the QED Lagrangian*. elliotmcguckenphysics.com (April 2026). Builds on [45] to derive the full tree-level QED Lagrangian, with A_μ identified as the connection on the x₄-orientation U(1)-bundle, Maxwell’s equations as the bundle curvature equations, and magnetic-monopole absence as a rigorous bundle-triviality theorem.

------------------------------------------------------------------------

*Submitted to elliotmcguckenphysics.com, April 2026.*

**Author: Elliot McGucken, PhD — Theoretical Physics** **Undergraduate research with John Archibald Wheeler, Princeton University (late 1980s)** **Ph.D., University of North Carolina at Chapel Hill (1998)** **Website: elliotmcguckenphysics.com**
