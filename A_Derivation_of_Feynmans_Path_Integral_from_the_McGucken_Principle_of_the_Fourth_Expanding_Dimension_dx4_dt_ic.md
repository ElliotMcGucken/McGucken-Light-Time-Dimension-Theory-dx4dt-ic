---
title: "A Derivation of Feynman's Path Integral from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic"
subtitle: "How Huygens' Principle, Feynman's Many Paths, Brownian Motion, and Entropy's Increase All Emerge from a Single Geometric Postulate"
author: "Elliot McGucken"
date: "April 15, 2026; revised October 14, 2026"
---

> "More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. . . Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet for graduate school in physics."
>
> — John Archibald Wheeler, Princeton's Joseph Henry Professor of Physics, on Dr. Elliot McGucken

## Abstract

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality. This paper demonstrates that Feynman's path integral formulation of quantum mechanics is a direct and natural consequence of this single geometric postulate. The expansion of the fourth dimension at c from every event makes each event the apex of a McGucken Sphere, a spherically symmetric wavefront of spatial radius c(t − t₀) whose surface lies at one x₄ location relative to its apex: the physical mechanism of Huygens' Principle. Successive expansions generate the totality of all possible paths connecting any two spacetime points. The intrinsically complex character of the fourth coordinate x₄ = ict assigns each path a phase proportional to its classical action. The sum over all such paths, weighted by these phases, reproduces the Feynman propagator. The classical limit emerges via stationary phase when the action is large compared to ħ. The same geometric mechanism that generates Feynman's many paths [1, 27, 55] (Theorems 4.1 and 6.1) also generates Brownian motion's random walk and the monotonic increase of entropy [6, 11, 38, 40] (Theorem 8.1), unifying quantum mechanics, wave optics, statistical mechanics, and thermodynamics under a single principle [3, 10, 11, 19, 35, 36, 38, 39, 40, 55, 56]. The McGucken Principle thereby provides the missing physical mechanism underlying Feynman's path integral: particles explore all paths because the fourth dimension's expansion physically distributes every point across a spherical wavefront at every instant. The free-particle action is i mc times the accumulated x₄-advance, S[γ] = −mc²∫ dτ = i mc X₄[γ], and the phase e^(iS/ħ) = exp(−(mc/ħ)X₄[γ]) counts that advance in Compton wavelengths (Section 2.1). For two particles, the joint kernel is nonseparable whenever the interaction has a nonzero mixed derivative, and co-emitted photons, each at rest in x₄ with relative displacement Δ x₄ = 0, carry the joint polarization amplitude that gives the Bell correlations E(a,b) = cos 2(a−b) (Section 9).

## 1. Introduction

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

### 1.1 The problem: why all paths?

Feynman's path integral formulation of quantum mechanics [1] asserts that the quantum-mechanical amplitude for a particle to propagate from a spacetime point (x_A, t_A) to (x_B, t_B) is given by a sum over all possible paths connecting these points:


K(x_B, t_B; x_A, t_A) = ∫ 𝒟[x(t)] e^(iS[x(t)]/ħ)


where S[x(t)] = ∫ L(x, ẋ, t) dt is the classical action along the path x(t), and the integral ∫ 𝒟[x(t)] denotes a sum over all continuous paths from x_A to x_B.

This formulation is extraordinarily successful. It reproduces the Schrödinger equation, yields the correct classical limit via stationary phase, and generalizes naturally to quantum field theory. Yet a question remains: why does a particle explore all possible paths? What is the physical mechanism that causes a particle at a definite point to distribute itself across the entirety of path space?

Standard quantum mechanics offers no answer. The path integral is taken as a computational postulate — a mathematical rule that works. Feynman himself presented it as an alternative axiomatization of quantum mechanics, equivalent to but different from the Schrödinger [44] and Heisenberg [45] formulations.

### 1.2 The answer: the fourth dimension is expanding at c

The McGucken Principle [2–9, 19, 35–41, 55, 56] provides the missing physical mechanism. It asserts:

**The McGucken Principle.** The fourth coordinate x₄ is a real geometric axis of nature, expanding at the velocity of light relative to the three spatial dimensions:


dx₄/dt = ic, x₄ = ict


The expansion is spherically symmetric: at each instant, each point in space is distributed across a spherical wavefront by the fourth dimension's expansion.

This single postulate provides a physical origin for every element of the Feynman path integral:

- The spherically-symmetric expansion of x₄ distributes each point into a wavefront at each instant — this is Huygens' Principle, and it generates all possible paths.
- The complex character of x₄ = ict assigns each path a phase proportional to its action — this produces the factor e^(iS/ħ).
- The sum over all wavefront expansions reproduces the path integral measure ∫ 𝒟[x(t)].
- The classical limit arises because, for macroscopic actions S ≫ ħ, only the stationary-phase path (the classical trajectory) survives.

This paper presents the formal derivation.

### 1.3 The McGucken Principle dx₄/dt = ic Reading of the Order of Descent

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states the physical reality that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. Every mathematical object in this paper is defined from that physical expansion, in the following order.

1. The rate dx₄/dt = ic at every event, on every worldline, at every gravitational potential: the physical postulate.
2. The McGucken Sphere about each event p = (x₀, t₀): the 2-sphere of spatial radius c(t − t₀), and the future null cone Σ⁺(p) that the Spheres sweep out (Lemma 3.1).
3. The coordinate x₄ = ict, the integral of the rate, and the line element (Lemma 2.1); the Lorentz transformations are the maps that preserve it.
4. The Sphere-tangent share v_(x₄), the standard time-dilation factor c dτ/dt (Lemma 2.2), and the four-velocity norm u^μ u_μ = −c² (Lemma 2.3).
5. The accumulated x₄-advance X₄[γ] = ic τ[γ], proper time up to the factor ic (Definition 2.4), maximal on the straight worldline (Lemma 2.6).
6. The action S = i mc X₄ (Theorem 2.7) and the gravitational potential term (Proposition 2.10).
7. The phase: its angle from the wavelength of the Sphere (Lemma 2.11), its complex unit from the i of the rate (Lemma 2.12), its sign from the +ic orientation (Theorem 2.13).
8. The histories, generated by iterated Spheres (Theorem 4.1); the kernel (Theorem 6.1); the Schrödinger equation (Corollary 6.2), first order in time from the time-independence of the rate and second order in space from the isotropy of the Sphere (Section 10).
9. The classical trajectory, the history of maximal accumulated advance (Theorem 7.1).
10. Diffusion and entropy, on the real section x₄ = cτ of the same expansion (Section 8).
11. Joint histories and entanglement (Section 9.1); the photon at rest in x₄ on the surface of its emission Sphere (Section 9.2); the Bell correlations (Sections 9.3–9.4).
12. The nonlocality of Feynman's sum, carried by the x₄-local surface of the Sphere (Section 11.3).

The inputs beyond the Principle are stated where they enter: the additive aggregation of phase factors with equal weight for every history in the integration measure (superposition, Section 2; Theorem 6.1), the rest masses, the non-gravitational potentials, the photon source specification (Theorem 9.11), and the Born rule, imported from the corpus derivation [20, 55]. Table 3 in Section 12 records the chain result by result.

## 2. Assumptions and Framework

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

We work in a flat spacetime [14, 15] with coordinates (x, y, z, t) and fourth coordinate x₄ defined by


x₄ = ict


The line element is


ds² = dx² + dy² + dz² − c² dt²


The McGucken Principle is the physical postulate


dx₄/dt = ic


stating that the fourth dimension advances at constant speed c relative to coordinate time t.

For massive particles, the proper time τ is defined by


c² dτ² = −ds²


and the relativistic free-particle action is


S[γ] = −mc² ∫ dτ


along a worldline γ. The classical path extremizes S.

On the quantum side, we assume:

- Amplitudes are complex numbers and obey superposition.
- The McGucken Sphere expands with a wavelength, and one wavelength step of the expansion carries the action h, with ħ = h/2π.
- In the classical limit S ≫ ħ, stationary-phase paths dominate (proved in Section 7 by the stationary-phase theorem; the precise condition is that the variations of S between neighboring histories are large compared to ħ).

The superposition item includes the equal weighting of the histories in the integration measure, made explicit in Theorem 6.1. The first two items correspond to Feynman's Postulates I and II of 1948 [27], quoted in full in Section 11.1, where each is set beside the theorem of the McGucken Principle that supplies it.

The novelty is to connect these standard features to the geometry of the expanding fourth dimension. Section 2.1 derives from the McGucken Principle and the wavelength of the Sphere that interference phases are proportional to action in units of ħ.

### 2.1 The McGucken Principle dx₄/dt = ic Reading of the Action and of the Phase

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality. Here c is the rate of the expansion and h is the action carried by one wavelength step of it.

**McGucken Principle anchor.** This subsection derives from that statement the four-velocity norm, the free-particle action as i mc times the accumulated x₄-advance, and the phase factor e^(iS/ħ) of a history.

The wavelength of the Sphere is the action-quantization element of the corpus construction of c and ħ, which the McGucken Cosmology paper [17] states as "the non-circular three-step construction — (i) the McGucken Principle fixes c as the substrate's wavelength-per-period ratio ℓ_*/t_*; (ii) one action-quantization postulate defines ℏ as the per-tick action quantum; (iii) Schwarzschild self-consistency r_S = λ identifies ℓ_* = ℓ_P = √(ℏG/c³) via Newton's G as the third independent dimensional input".

Four quantities associated with the advance of x₄ are used below, each in its own role [17, Appendix B]:

- (R1) The coordinate rate dx₄/dt = ic: the Principle itself, the same at every event, on every worldline, at every gravitational potential.
- (R2) The Sphere-tangent share v_(x₄) = √(c² − v²), the standard time-dilation factor c dτ/dt: the worldline's share of the expansion, bounded in [0, c].
- (R3) The temporal four-velocity component u⁴ = dx₄/dτ = icγ: a chain-rule consequence of (R1), undefined on null worldlines.
- (R4) The accumulated x₄-advance X₄[γ] = ic τ[γ], proper time up to the factor ic: a path-dependent functional of the worldline, constant along null worldlines.

**Lemma 2.1 (Line element from the rate).** *Integrating dx₄/dt = ic with x₄(0) = 0 gives x₄ = ict, and*

ds² = dx² + dy² + dz² + dx₄² = dx² + dy² + dz² − c²dt².    (2.1)

*On a timelike segment, c²dτ² = −ds² gives dτ = dt√(1 − v²/c²), v = |dx/dt|.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Integrating dx₄/dt = ic gives x₄ = ict, so dx₄ = ic dt and dx₄² = (ic)²dt² = −c²dt², which gives (2.1). On a timelike segment −ds² = c²dt² − |dx|² > 0, so dτ = dt√(1 − |dx|²/(c²dt²)) = dt√(1 − v²/c²). □

**Lemma 2.2 (Sphere-tangent share).** *The Sphere-tangent share v_(x₄), the standard time-dilation factor c dτ/dt, satisfies*

v² + v_(x₄)² = c²    (2.2)

*on every timelike worldline, and v_(x₄) = 0 at v = c.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. By Lemma 2.1, v_(x₄) = c√(1 − v²/c²) = √(c² − v²). At v = c this is 0. □

The McGucken Cosmology paper [17] states: "The four-velocity normalization u^μu_μ = −c² is a chain-rule theorem *forced by* the McGucken Principle when the worldline is proper-time-parametrized (per (R3) of Appendix B; the norm is a downstream consequence of the Principle dx₄/dt = ic in (R1), not identical to it)." Lemma 2.3 gives the chain-rule proof.

**Lemma 2.3 (The four-velocity norm u^μ u_μ = −c² as a consequence of dx₄/dt = ic).** *On a timelike worldline parametrized by τ, let u^μ = dx^μ/dτ with x⁴ ≡ x₄, and let u^μ u_μ = |dx/dτ|² + (u⁴)², the sum of the x₄ = ict convention in which the sign of the time part is carried by i. Then u⁴ = icγ with γ = (1 − v²/c²)^(−1/2), and*

u^μ u_μ = −c².    (2.3)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. By the chain rule and (R1), u⁴ = (dx₄/dt)(dt/dτ) = icγ, with dt/dτ = γ from Lemma 2.1. Also |dx/dτ| = γ v. Then u^μ u_μ = γ²v² + (icγ)² = γ²(v² − c²) = −c². □

The norm (2.3) carries a magnitude; the orientation of the advance is carried by the +ic of the Principle. On a worldline at spatial rest, dτ = dt and u⁴ = ic.

**Definition 2.4 (Accumulated x₄-advance).** For a causal worldline γ, the accumulated x₄-advance, equal to proper time up to the factor ic, is

X₄[γ] = ∫ᵧ ic dτ = ic τ[γ].    (2.4)


**Lemma 2.5 (Properties of the accumulated advance).** *(a) Additivity: if γ = γ₂∘γ₁, then X₄[γ] = X₄[γ₁] + X₄[γ₂]. (b) Reparametrization invariance: X₄[γ] depends only on the image of γ. (c) Null worldlines: X₄ is constant along a null worldline. (d) Rate form: dX₄ = i v_(x₄) dt.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. (a) The integral (2.4) is additive over concatenation. (b) dτ is a reparametrization-invariant line element by Lemma 2.1. (c) On a null worldline ds² = 0, so dτ = 0 pointwise. (d) dX₄ = ic dτ = i (c dτ/dt) dt = i v_(x₄) dt by Lemma 2.2. □

**Lemma 2.6 (Maximal accumulated advance).** *Let B lie in the chronological future of A. Among all timelike worldlines from A to B, the straight worldline uniquely maximizes |X₄| = c τ.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. A Lorentz transformation, which preserves (2.1) and hence τ, brings B − A to (0, T) with T > 0. Along a timelike worldline dt/dτ = γ ≥ 1, so t ∈ [0, T] parametrizes it, and τ = ∫₀ᵀ√(1 − v²/c²) dt ≤ T, with equality if and only if v = 0 almost everywhere. Since |dx/dt| < c, x(t) is Lipschitz, hence absolutely continuous, so v = 0 almost everywhere and x(0) = x(T) give x constant: the straight worldline. □

The following passage is reproduced verbatim and in full from the McGucken Cosmology paper [17], §X.1, which summarizes the Unique McGucken Lagrangian paper [18]. Its internal reference [164] is [18] here.

> **The free-particle action.** Under the McGucken Principle, the natural action functional for a classical massive particle of rest mass m tracing a worldline γ in spacetime is the accumulated magnitude of x₄'s advance along the worldline, scaled by −mc to give units of action:
>
> > **S_free = −mc ∫_γ |dx₄| = −mc ∫_γ √(−η_μν ẋ^μ ẋ^ν) dλ = −mc² ∫_γ dτ.**
>
> The three forms are equivalent: the first form is in the language of x₄-advance; the second is the standard Minkowski-line-element form; the third is the proper-time form. All three express the same functional of the worldline. The Euler-Lagrange equation produced by varying S_free with respect to the worldline is the relativistic free-particle equation of motion d/dτ(mc·u^μ) = 0 with u^μu_μ = −c², which in the rest frame reduces to dx₄/dt = ic — the McGucken Principle itself recovered as the free-worldline equation of motion.
>
> **Theorem X.1 (Uniqueness of the free-particle action — Proposition IV.1 of [164]).** *Let γ be a timelike worldline in Minkowski spacetime and let S[γ] be a real scalar functional of γ satisfying:*
>
> (a) *Poincaré invariance — S[γ] is invariant under the full Poincaré group of spacetime;*
> (b) *Reparametrization invariance — S[γ] depends on γ only through its image as a curve in ℳ;*
> (c) *Locality — S[γ] = ∫_γ F(x^μ, ẋ^μ) dλ for some local F;*
> (d) *First-order derivatives — F depends on ẋ^μ but not on ẍ^μ or higher derivatives;*
> (e) *Dimensional consistency — S has units of action.*
>
> *Then the unique (up to overall multiplicative constant and additive total-derivative terms) functional satisfying (a)–(e) is*
>
> > **S[γ] = −mc ∫_γ √(−η_μν ẋ^μ ẋ^ν) dλ,**
>
> *with m a constant of dimension mass.*
>
> **Proof structure** (full proof in [164], §IV). By condition (c), S[γ] = ∫ F(x, ẋ) dλ for some local F. By condition (b) (reparametrization invariance), F must be homogeneous of degree one in ẋ^μ. By condition (a) (Lorentz invariance), F must be a Lorentz scalar built from ẋ^μ and η_μν. The most general such F homogeneous of degree one in ẋ is F(x, ẋ) = A(x) √(−η_μν ẋ^μ ẋ^ν) + B_μ(x) ẋ^μ, where A(x) is a Lorentz scalar and B_μ(x) is a Lorentz covector. By conditions (a) and (d), A(x) and B_μ(x) cannot depend on x^μ (translation invariance forbids x-dependence) and cannot depend on ẋ^μ (no higher-order derivatives). The free-particle assumption forces F_μν = ∂_μB_ν − ∂_νB_μ = 0; by the Poincaré lemma, B_μ is then a closed exact covector, contributing only a boundary term to S that can be discarded. Therefore F = A √(−η_μν ẋ^μ ẋ^ν) with A constant. Dimensional consistency (e) requires A to have units of mass × velocity, giving A = −mc by convention. □

**Theorem 2.7 (The action is i mc times the accumulated x₄-advance).** *For a free particle of mass m on a timelike worldline γ,*

S[γ] = −mc²∫ᵧ dτ = −mc² τ[γ] = i mc X₄[γ].    (2.5)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. By Theorem X.1, S = −mc²τ. By (2.4), τ = X₄/(ic) = −iX₄/c, so S = −mc²(−iX₄/c) = i mc X₄. Conversely i mc· ic τ = −mc²τ, which is real. □

**Corollary 2.8 (Compton wavelength of accumulated advance).** *Along a timelike worldline, |dS| = mc |dX₄|. The magnitude of accumulated advance carrying the action h is the Compton wavelength λ_C = h/(mc).*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Differentiating (2.5), dS = i mc dX₄, so |dS| = mc |dX₄|; |dS| = h gives |dX₄| = h/(mc). □

**Proposition 2.9 (Nonrelativistic expansion).** *For a worldline with speed bounded by vₘₐₓ < c on [t_A, t_B], T = t_B − t_A,*

S[γ] = −mc²T + ∫_(t_A)^(t_B)1/2 mv² dt + R, |R| ≤ (m vₘₐₓ⁴ T)/(8c²(1 − vₘₐₓ²/c²)^(3/2)).    (2.6)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. By Lemma 2.1, S = −mc²∫√(1 − u) dt with u = v²/c² ∈ [0, uₘₐₓ]. For f(u) = √(1−u), f(0) = 1, f'(0) = −1/2, f''(u) = −1/4(1−u)^(−3/2), and Taylor's theorem with Lagrange remainder gives f(u) = 1 − u/2 + r(u) with |r(u)| ≤ 1/8u²(1 − uₘₐₓ)^(−3/2). Multiplying by −mc² and integrating gives (2.6). □

**Proposition 2.10 (The gravitational potential from the Sphere-tangent share).** *The following is reproduced verbatim from [17], §X.3(iii), which summarizes Theorem 12 of the general relativity paper [19] (its [186]); the full general-relativity chain of theorems is given in [19, 56]:*

> (iii) **The Schwarzschild metric as a theorem.** Theorem 12 of [186]: the Schwarzschild metric is the unique spherically symmetric vacuum solution forced by (a) x₄'s invariant expansion at rate ic, (b) spherical symmetry, (c) asymptotic flatness, and (d) Gauss's law applied to the gravitational source. The temporal component N² = (1 − r_s/r) and the radial component h_rr = 1/(1 − r_s/r) satisfy N²·h_rr = 1, expressing the conservation of x₄'s expansion rate: what is lost in temporal advance is gained in spatial stretching.

*In the weak field, with Φ = −GM/r, a particle of mass m moving with speed v has action*

S = ∫(−mc² + 1/2mv² − mΦ)dt + O((mΦ v²)/c², mv⁴/c², mΦ²/c²)T.    (2.7)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic, which is the same at every gravitational potential; gravity changes the Sphere-tangent share. From the metric quoted, c²dτ² = N²c²dt² − hᵣᵣdr² − r²dΩ², so dτ = dt√(N² − (hᵣᵣvᵣ² + vₚₑᵣₚ²)/c²). With N² = 1 + 2Φ/c² [16] and hᵣᵣ = 1 + O(Φ/c²), expansion gives dτ = dt (1 + Φ/c² − v²/2c²) + O(Φ v²/c⁴, v⁴/c⁴, Φ²/c⁴) dt. The free action in the metric quoted is −mc²∫ dτ with dτ from that metric: the form of Theorem X.1 with η_(μν) replaced by the metric (minimal coupling; background knowledge). Multiplying by −mc² gives (2.7). □

For the other interactions, the potential V is an input of this paper; the electromagnetic interaction enters through the x₄-orientation U(1) bundle of the McGucken QED paper [21], within the corpus derivation of the Standard Model Lagrangians [7].

**Lemma 2.11 (Phase angle from action).** *Let θ[γ] be the phase angle accumulated along a history γ. Suppose (a) θ and S are additive under concatenation of histories, (b) θ depends continuously on S, and (c) an action of magnitude h corresponds to a phase angle of magnitude 2π, by the wavelength of the McGucken Sphere. Then*

θ[γ] = σ 2π/hS[γ] = σ (S[γ])/ħ, σ∈{+1, −1}.    (2.8)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic and the action h per wavelength step. Write θ = g(S). The actions of free histories fill (−∞, 0), since S = −mc²τ and τ takes every positive value, and additivity gives g(S₁ + S₂) = g(S₁) + g(S₂) for S₁, S₂ < 0. Then g(nS) = n g(S) and g(S) = n g(S/n) for positive integers n, so g(qS) = q g(S) for rational q > 0, and continuity extends this to real q > 0. Hence g(S) = κ S on (−∞, 0) with κ = −g(−1) (Cauchy's functional equation on a half-line [52]). The calibration |g(−h)| = 2π gives |κ| = 2π/h = 1/ħ, so κ = σ/ħ. For a history of any real action S, including a potential, concatenate it with a free history of action S' < min(0, −S); additivity gives g(S) = g(S + S') − g(S') = κ(S + S') − κ S' = κ S. □

**Lemma 2.12 (The phase factor is a rotation generated by the i of dx₄/dt = ic).** *Phase angles compose additively modulo 2π. Every continuous injective homomorphism χ: ℝ/2πℤ → ℂ^× has the form χ(θ) = eⁱᶿ or χ(θ) = e⁻ⁱᶿ.*

The phase factor is injective on ℝ/2πℤ because one wavelength is the smallest advance that returns the oscillation to its initial state, so distinct phase angles within one wavelength are distinct states. The algebra of the phase factors is ℂ = ℝ[i], with i the unit of dx₄/dt = ic, which records the perpendicularity of x₄ to the three spatial dimensions; by Frobenius's theorem [22], ℂ is the unique real division algebra of dimension two.

*Proof.* Everything below descends from the i of dx₄/dt = ic, which generates ℂ. (1) |χ| is a continuous homomorphism from the compact group ℝ/2πℤ into (ℝ_(>0), ·); its image is a compact subgroup of ℝ_(>0), which is {1}. (2) Composing with the quotient map gives a continuous homomorphism χ̃: ℝ → U(1) with χ̃(2π) = 1. Since ϕ ↦ e^(iϕ) is a covering map, χ̃ has a unique continuous lift L: ℝ → ℝ with L(0) = 0 and χ̃ = eⁱᴸ. The function L(a+b) − L(a) − L(b) is continuous, takes values in 2πℤ, and vanishes at a = b = 0, so it vanishes identically; by Cauchy's equation L(θ) = nθ. (3) χ̃(2π) = 1 gives n ∈ ℤ. (4) eⁱⁿᶿ is injective on ℝ/2πℤ only for n = ±1: for n = 0 it is constant, and for |n| ≥ 2, χ(2π/n) = χ(0). □

**Theorem 2.13 (Phase factor of a history).** *The phase factor of a history γ with action S[γ] is*

Φ[γ] = e^(iS[γ]/ħ),    (2.9)

*and for a free particle*

Φ[γ] = exp(−mc/ħX₄[γ]) = e^(−iω_Cτ[γ]), ω_C = mc²/ħ.    (2.10)

*The sign in (2.9) is fixed by the +ic orientation of dx₄/dt = ic: it is the unique sign for which the continuation of Section 8.1 to real x₄ gives convergent slice integrals.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate +ic and the action h per wavelength step. By Lemma 2.11 the phase angle is ± S/ħ, and by Lemma 2.12 the factor is e^(± iθ); together the factor is e^(iσ S/ħ) with σ = ±1. The +ic orientation fixes the continuation to real x₄: x₄ = ict equals cτ_W with τ_W > 0 exactly when t = −iτ_W. Under this continuation a time step ε becomes −iε_W with ε_W > 0, and the kinetic action m|η|²/(2ε) of a step with displacement η becomes i m|η|²/(2ε_W). The weight e^(iσ S/ħ) becomes exp(−σ m|η|²/(2ħε_W)). For σ = +1 this is a Gaussian, integrable over η ∈ ℝ³; for σ = −1 it grows without bound and its integral over ℝ³ diverges, so the time-sliced integrals of Section 6.2 and the Wiener integral of Section 8.1 do not exist. Hence σ = +1, which is (2.9). With the opposite orientation −ic, real x₄ requires t = +iτ_W and the same argument selects σ = −1: the sign is the orientation. For a free particle, Theorem 2.7 gives iS/ħ = i· i(mc/ħ)X₄ = −(mc/ħ)X₄, and X₄ = icτ gives −(mc/ħ)icτ = −iω_Cτ, which is (2.10). □

**Corollary 2.14 (The phase counts the accumulated advance in Compton wavelengths).** *For a free particle,*

(S[γ])/ħ = −(|X₄[γ]|)/(λ̄_C) = −2π(|X₄[γ]|)/λ_C, λ_C = h/mc, λ̄_C = ħ/mc.    (2.11)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. By Theorem 2.7, S = −mc²τ = −mc |X₄|, since |X₄| = cτ. Dividing by ħ gives (2.11). □

**LTD reading.** The i in Feynman's weight e^(iS/ħ) is the i of dx₄/dt = ic, carried by the accumulated advance X₄ = icτ: the real exponential exp(−(mc/ħ)X₄) of the advance is an oscillation, one radian per reduced Compton wavelength λ̄_C of accumulated advance. The wavelength of the McGucken Sphere supplies ħ, the i of the Principle supplies the complex unit, and the +ic orientation supplies the sign. Sections 5.1 and 6.1b use this result.

## 3. The McGucken Principle and Huygens' Principle

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

### 3.1 From an expanding dimension to spherical wavefronts

**Lemma 3.1 (Huygens' Principle from dx₄/dt = ic).** If the fourth dimension expands at the rate c in a spherically-symmetric manner, then every point in three-dimensional space acts as a source of a spherical wavefront expanding at speed c.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. Let P be a point in three-dimensional space at time t₀. The McGucken Principle states that the fourth dimension expands at c relative to the three spatial dimensions, and that this expansion is spherically symmetric. After an infinitesimal time dt, the expansion of x₄ has distributed the point P across a spherical shell of radius c dt centered on P. Each point on this shell is itself a point in three-dimensional space, and the McGucken Principle applies to it in turn: after the next interval dt, each of these points is distributed across its own spherical shell of radius c dt.

This is precisely the content of Huygens' Principle: every point on a wavefront acts as a source of a new spherical wavelet, and the new wavefront is the envelope of all such wavelets.

The envelope statement follows from the triangle inequality. Let the wavefront at time t be the sphere |x − x_P| = r. Every point of a wavelet of radius c dt centered on this sphere satisfies r − c dt ≤ |x − x_P| ≤ r + c dt, and for every unit vector n̂ the point x_P + (r + c dt)n̂ lies on the wavelet centered at x_P + rn̂. The outer envelope of the wavelets is therefore the sphere of radius r + c dt about P, tangent to each wavelet at one point.

The McGucken Principle thus provides the physical mechanism underlying Huygens' Principle: wavefronts expand spherically because the fourth dimension expands spherically at c. The envelope argument is a statement about the geometry of the wavefronts; the amplitudes carried on them are constructed in Sections 2.1, 5 and 6. QED.

**Remark.** Huygens stated his principle in 1678 [13] as a phenomenological rule for the propagation of light. Fresnel [42] later showed that it could be made quantitative by including phase information. The McGucken Principle provides, for the first time, a geometric reason why Huygens' Principle holds: the expansion of the fourth dimension at c physically distributes every point into a spherical wavefront.

Huygens' own statement, in Thompson's translation [32, Ch. I], is that each particle of the medium "ought not to communicate its motion only to the next particle which is in the straight line drawn from the luminous point" and "also imparts some of it necessarily to all the others which touch it and which oppose themselves to its movement. So it arises that around each particle there is made a wave of which that particle is the centre." Huygens supplies the secondary wave as a property of an elastic medium. Feynman extended the principle to matter waves: the recursion for the wave function "is easily interpreted physically as the expression of Huygens' principle for matter waves" [27, §7]. The McGucken Principle differs from this prior art in providing a physical mechanism for Huygens' principle: x₄'s spherical expansion at c from every event (Lemma 3.1), with no medium.

### 3.2 Physical example: the expanding light sphere

Consider a photon emitted from a point source at the origin at t = 0. The photon is stationary in x₄ [2], meaning all of its invariant four-speed c is carried by the spatial components. The expanding fourth dimension distributes the photon's position across an expanding spherical wavefront of radius r = ct. At any point on this sphere, the photon has an equal probability of being measured — this is the spherical symmetry of the expansion.

This expanding light sphere is a direct, visible manifestation of the McGucken Principle. It is the cross-section of the expanding fourth dimension with three-dimensional space [2]. Each expanding light sphere can be viewed as a McGucken Sphere — the geometric signature of dx₄/dt = ic made visible in the three spatial dimensions.

## 4. Generation of All Paths from Successive Wavefront Expansions

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

### 4.1 The mechanism: iterated Huygens expansions generate path space

**Theorem 4.1 (All paths from the McGucken Principle).** The successive application of Huygens' Principle, driven by the expansion of the fourth dimension at c, generates the totality of all possible continuous paths connecting any two spacetime points. Within the McGucken Spheres these are the paths of speed at most c, and they exhaust the continuous paths in the nonrelativistic limit c→∞.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. Consider a particle at position x_A at time t_A. Divide the time interval [t_A, t_B] into N equal steps of duration ε = (t_B − t_A)/N.

*Step 1.* At time t_A, the McGucken Principle distributes the point x_A across a spherical wavefront. For a massive particle with energy E, the expansion of x₄ drags the particle in proportion to its energy, distributing its position across a region of characteristic size determined by ε and the particle's de Broglie wavelength. The particle may be found at any position x₁ within this region, with amplitude depending on x₁.

*Step 2.* At time t_A + ε, the McGucken Principle applies again: each point x₁ is itself distributed across a new wavefront. The particle may now be found at any position x₂.

*Step k.* At time t_A + kε, each point xₖ₋₁ is distributed across a wavefront, yielding a new position xₖ.

After N steps, the particle arrives at x_B = x_N. The sequence (x_A, x₁, x₂, …, x_(N−1), x_B) defines a piecewise path from x_A to x_B. Since the McGucken expansion distributes each point across all positions on the wavefront — not a single preferred direction — the totality of all such sequences, over all intermediate positions, generates all possible paths from x_A to x_B.

In the limit N → ∞ (ε → 0), the piecewise paths become continuous, and the set of all sequences becomes the space of all continuous paths — precisely the domain of integration in Feynman's path integral. In precise form: a continuous path x(t) on [t_A, t_B] is uniformly continuous, with modulus of continuity ω; on each step [tₖ, tₖ₊₁] the polygonal path through the values x(tₖ) is a convex combination of x(tₖ) and x(tₖ₊₁), so it differs from x(t) by at most ω(ε), and every continuous path is the uniform limit of the polygonal sequences generated at resolution N. The Sphere of each vertex reaches distance cε in one step, so the polygons generated within the Spheres are those with |xₖ₊₁ − xₖ|≤ cε. For a path with |x(t) − x(s)|≤ c|t − s| its polygon satisfies this bound, and uniform limits of such polygons satisfy it, so the paths generated within the Spheres are exactly the paths of speed at most c; in the nonrelativistic regime, the limit c→∞ of the Remark following Theorem 6.1, this class exhausts the continuous paths. QED.

### 4.2 Physical example: the double-slit experiment

In the classic double-slit experiment, a particle is emitted from a source, passes through one of two slits, and is detected on a screen. The standard quantum-mechanical explanation invokes the superposition principle: the particle passes through both slits simultaneously, and the amplitudes interfere.

The McGucken Principle provides the physical mechanism. At the moment of emission, the expansion of x₄ distributes the particle's position across an expanding spherical wavefront. This wavefront encounters the barrier and passes through both slits. Beyond the barrier, each point on each slit acts as a new source of Huygens wavelets (Lemma 3.1), and the wavelets from both slits overlap and interfere at the detection screen.

The particle does not "choose" a slit. The expansion of the fourth dimension physically distributes it through both. The interference pattern is the geometric consequence of two sets of Huygens wavelets — each generated by the expansion dx₄/dt = ic — overlapping with different accumulated phases. From the source to the screen, the Huygens cascade generated by dx₄/dt = ic includes paths through each slit, including multiple bounces and detours. Each path has a distinct S[γ], hence a distinct x₄-phase. At some screen points, paths through both slits arrive in phase and reinforce; at others, they cancel. The interference pattern on the screen is the visible interference of many x₄-phase histories. The particle "takes all paths" precisely because the expanding fourth dimension actually opens all Huygens histories between source and detector.

Feynman calls the two-slit phenomenon one that is "impossible, absolutely impossible, to explain in any classical way" and adds: "In reality, it contains the only mystery" [31, §1-1]. He states the rule it obeys: "When an event can occur in several alternative ways, the probability amplitude for the event is the sum of the probability amplitudes for each way considered separately" [31, §1-7]. In the McGucken dx₄/dt = ic framework the alternative ways are the Sphere-generated histories (Theorem 4.1), each carrying the phase factor of its accumulated x₄-advance (Theorem 2.13), and the amplitudes through the two slits are added at a detection event whose McGucken Sphere reaches back to both slits.

### 4.3 Physical example: quantum tunneling

In quantum tunneling, a particle penetrates a potential barrier that it classically could not surmount. In the Feynman formulation, this occurs because paths that pass through the barrier contribute to the path integral with nonzero (though exponentially suppressed) amplitude.

The McGucken Principle explains why such paths exist at all. The expansion of x₄ at each instant distributes the particle across all positions on a spherical wavefront — including positions inside and beyond the barrier. No path is excluded by the expansion; every spatial point receives amplitude from the expanding wavefront. The barrier suppresses but does not eliminate the amplitude on the far side, because the fourth dimension's expansion is a geometric fact that applies everywhere, independent of the potential landscape.

## 5. The Phase Factor e^(iS/ħ) from the Complex Fourth Coordinate

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

### 5.1 The origin of the phase

**Theorem 5.1 (Phase from x₄ = ict).** The complex character of the fourth coordinate x₄ = ict assigns each path through spacetime a phase proportional to the classical action along that path.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. Consider a particle of mass m following a path x(t) from (x_A, t_A) to (x_B, t_B). In the four-dimensional manifold with coordinates (x, y, z, x₄) = (x, y, z, ict), the line element is:


ds² = dx² + dy² + dz² + dx₄² = dx² + dy² + dz² − c²dt²


The four-dimensional arc length along the path is:


√(−ds²) = c dt√(1 − |v|²/c²) = c dt/γ = c dτ


where dτ is the proper time increment. The total proper time along the path is:


τ = ∫_(t_A)^(t_B)√(1 − |v|²/c²) dt


Now, the key step. The fourth coordinate is x₄ = ict. The factor i means that displacement along the fourth dimension contributes an imaginary component to the four-dimensional arc length. In the McGucken dx₄/dt = ic framework this i records the perpendicularity of the real fourth dimension x₄ to the three spatial dimensions; it is the i that generates the phase rotation of Lemma 2.12. Along any path, the accumulated displacement in x₄ is:


Δ x₄ = ic(t_B − t_A)


This coordinate displacement is fixed by the rate (R1) and is the same for every path. The path-dependent quantity is the accumulated x₄-advance X₄[γ] = ic τ[γ] of Definition 2.4, which carries the action (Theorem 2.7).

The phase accumulated by a quantum-mechanical particle along a path is determined by the action. For a free particle of mass m, the relativistic action is:


S = −mc²∫ dτ = −mc²∫_(t_A)^(t_B)√(1 − |v|²/c²) dt


In the non-relativistic limit |v| ≪ c:


S ≈ ∫_(t_A)^(t_B)(1/2m|v|² − mc²) dt


The constant rest-energy term −mc²(t_B − t_A) contributes a global phase e^(−imc²(t_B − t_A)/ħ), common to every path between the same endpoint times, which cancels from all probabilities and from all ratios of amplitudes. The remaining action is the familiar non-relativistic Lagrangian:


S = ∫_(t_A)^(t_B)L(x, ẋ) dt = ∫_(t_A)^(t_B)(1/2m|v|² − V(x)) dt


Here the potential V is derived for gravity in Proposition 2.10 (V = mΦ) and is an input for the other interactions.

The phase assigned to each path is e^(iS/ħ). This phase is intrinsically complex because the fourth coordinate x₄ = ict is intrinsically complex — the i in the McGucken equation is the origin of the i in the quantum-mechanical phase. The assignment is Theorem 2.13: by the wavelength of the McGucken Sphere the phase angle has magnitude |S|/ħ (Lemma 2.11), by the i of dx₄/dt = ic the phase factor is a rotation in ℂ (Lemma 2.12), and by the +ic orientation its sign is +. For the free particle, e^(iS/ħ) = exp(−(mc/ħ)X₄[γ]) with S = i mc X₄[γ] (Theorem 2.7). QED.

### 5.2 Physical example: the free particle propagator

For a free particle in one dimension, the Feynman propagator is:


K(x_B, t_B; x_A, t_A) = √(m/(2π iħ T)) exp((im(x_B − x_A)²)/(2ħ T))


where T = t_B − t_A. This can be derived directly from the McGucken Principle as follows. The expansion of x₄ distributes the particle from x_A across all positions at each time step (Theorem 4.1). The complex character of x₄ = ict assigns each path the phase e^(iS/ħ) where S = m(x_B − x_A)²/(2T) for the classical straight-line path (Theorem 5.1). The Gaussian sum over all paths — each a small deviation from the classical path — reproduces the prefactor √(m/(2π iħ T)), which is the standard result. The prefactor follows from the composition identity ∫ K_(T₁)(x_B, z) K_(T₂)(z, x_A) dz = K_(T₁ + T₂)(x_B, x_A) for kernels of this form, a Gaussian integral evaluated with the convergence factor e^(−δ z²), δ→0⁺; applied N−1 times to the one-step kernels of time ε = T/N, it gives the kernel of time T.

The i in the prefactor, which ensures that the propagator oscillates rather than decays, originates directly from the i in x₄ = ict.

In the McGucken picture, at each time step, dx₄/dt = ic drives a Huygens expansion in x-space. Every zig-zag path consistent with the speed-of-light budget is a sequence of such Huygens steps. The free-particle action S[γ] = ∫(1/2mv²) dt (in the nonrelativistic limit) measures the cumulative "inefficiency" of the path through x₄: straighter paths advance more directly through the expanding fourth dimension, while bent paths "waste" x₄-advance on spatial motion. The resulting kernel reproduces the usual spreading Gaussian wavepacket, now understood as the projection of the many Huygens histories of the expanding fourth dimension.

## 6. Action as the Measure of x₄-Advance and the Construction of the Path Integral from the McGucken Principle

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

### 6.1 The action measures advance through the expanding fourth dimension

The relativistic line element is


ds² = dx² + dy² + dz² − c²dt²


The proper time element is


dτ² = dt²(1 − |v|²/c²)


where v = dx/dt is the three-velocity. The free-particle action is


S[γ] = −mc²∫ dτ


along the path γ. In the McGucken interpretation:

- dτ measures the effective "advance" through the fourth dimension x₄ along γ: ic dτ = dX₄, the increment of the accumulated x₄-advance, proper time up to the factor ic (Definition 2.4).
- The action S[γ] is proportional to the integrated advance of the system through the expanding fourth dimension, given the four-speed budget u^μ u_μ = −c², which Lemma 2.3 derives from dx₄/dt = ic.
- The classical path is the one for which this x₄-advance (equivalently, S[γ]) is stationary under small variations of γ. This is the usual principle of stationary action, re-read as stationary flow through the fourth dimension.

Straighter paths advance more directly through x₄; bent paths "waste" x₄-advance on spatial motion. The action quantifies this: it measures how efficiently a given trajectory rides the expanding fourth dimension from A to B.

### 6.1b The parallel: dx₄/dt = ic and [q, p] = iħ

The key bridge from the McGucken Principle to quantum mechanics is the complex nature of the fourth coordinate: x₄ = ict. The natural quantum rule, inspired by the parallel between


dx₄/dt = ic


and the canonical commutation relation [12, 45]


[q, p] = iħ


— both having the factor i on the right side — is: associate a phase increment dφ with each infinitesimal action dS via dφ = dS/ħ. The total amplitude for a path γ is then


A[γ] = exp(iS[γ]/ħ)


In this picture, the path-dependent phase is a record of how a given trajectory has ridden the expanding fourth dimension: how its advance through x₄ compares, in detail, to all neighbouring trajectories.

Section 2.1 derives this rule from the McGucken Principle. The increment dφ = dS/ħ is Lemma 2.11, from the wavelength of the McGucken Sphere, with its sign fixed by Theorem 2.13. With S = i mc X₄ (Theorem 2.7), the amplitude is


A[γ] = exp(iS[γ]/ħ) = exp(−mc/ħX₄[γ]) = e^(−iω_Cτ[γ]), ω_C = mc²/ħ,    (6.1)


and |dφ| = |dX₄|/λ̄_C: the phase advances by one radian per reduced Compton wavelength λ̄_C = ħ/(mc) of accumulated x₄-advance (Corollary 2.14). The i in A[γ] is the i of dx₄/dt = ic, carried by X₄ = icτ, and its sign is fixed by the +ic orientation (Theorem 2.13). Dirac's 1933 statement that the transformation function "corresponds to" exp(i∫ L dt/ħ) [28] becomes, in this reading, an equality with a physical origin (Section 11.1).

### 6.2 The time-sliced propagator

**Theorem 6.1 (The Feynman path integral from dx₄/dt = ic).** The McGucken Principle, applied iteratively at N time slices and taken in the limit N → ∞, reproduces the Feynman path integral.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. Divide the interval [t_A, t_B] into N steps of duration ε = T/N. At each step k, the McGucken expansion distributes the particle from position xₖ to all positions xₖ₊₁. By Theorem 5.1, the amplitude for the particle to propagate from xₖ to xₖ₊₁ in time ε is:


K_ε(xₖ₊₁, xₖ) = A exp(iε L((xₖ₊₁ − xₖ)/ε)/ħ)


where A is a normalization constant and L is the Lagrangian evaluated on the straight-line segment from xₖ to xₖ₊₁, the history of maximal accumulated x₄-advance between the two events (Lemma 2.6). The condition K_ε(xₖ₊₁, xₖ)→δ(xₖ₊₁ − xₖ) as ε→0⁺ fixes A = √(m/(2π iħε)) in one dimension.

**Measure and weight.** Write the one-step kernel in general form, K_ε(x', x) = w_ε(x', x) e^(iS_ε(x', x)/ħ), integrated against a measure μ on the intermediate positions. The expansion of x₄ proceeds at the same rate ic from every event and is spherically symmetric about each, so the construction is invariant under spatial translations and rotations. A translation-invariant Radon measure on ℝᵈ is a constant multiple of Lebesgue measure (uniqueness of Haar measure [58]; background knowledge, mathematical theorem), so μ = const· dᵈx; the constant is absorbed into the normalization. Translation and rotation invariance also give w_ε(x', x) = w_ε(|x' − x|). The phase lemmas of Section 2.1 fix the exponential factor and its unit modulus (Lemma 2.12); they do not by themselves fix the dependence of w_ε on the step length. That w_ε is the constant A, so that every history enters with equal weight, is part of the superposition input of Section 2, the equal-magnitude clause of Feynman's Postulate II [27]; the normalization condition then fixes its value.

The total amplitude for propagation from x_A to x_B through all intermediate positions is obtained by integrating over all intermediate positions x₁, x₂, …, x_(N−1):


K(x_B, t_B; x_A, t_A) = lim_(N→∞)Aᴺ∫ dx₁ dx₂⋯ dx_(N−1) exp(i∑ₖ₌₀ᴺ⁻¹ε Lₖ/ħ)


The sum in the exponent is a Riemann sum for the action:


∑ₖ₌₀ᴺ⁻¹ε Lₖ → ∫_(t_A)^(t_B)L(x, ẋ) dt = S[x(t)]


and the multiple integral over all intermediate positions, in the limit N → ∞, becomes the functional integral over all paths:


K(x_B, t_B; x_A, t_A) = ∫𝒟[x(t)] e^(iS[x(t)]/ħ)


The existence of this limit, as the kernel of e^(−iHT/ħ) with H = −ħ²/2m∂ₓ² + V, is Nelson's theorem [26] for the potentials treated there (background knowledge, mathematical theorem). The Riemann-sum convergence above holds for histories with integrable velocity; the histories that dominate the integral are not differentiable, and for them the path integral is defined as this limit N→∞ of the time-sliced integrals.

This is the Feynman path integral. Every element has been derived from the McGucken Principle: the sum over all paths comes from the spherically-symmetric expansion of x₄ generating all intermediate positions at each time step (Theorem 4.1); the phase e^(iS/ħ) comes from the complex character of x₄ = ict (Theorem 5.1). QED.

**Remark (the causal ball and the integration domain).** The McGucken Sphere of an event reaches distance cε in time ε, while the time-sliced integral integrates each xₖ₊₁ over all of space. The nonrelativistic kernel is the regime |xₖ₊₁ − xₖ|≪ cε, and the region outside the causal ball contributes nothing in the limit c→∞ at fixed ε: for a Schwartz-class wavefunction ψ, |∫_(|η| > cε)A e^(imη²/2ħε)ψ(x + η) dη|≤|A|∫_(|η| > cε)|ψ(x + η)| dη, which tends to zero faster than any power of 1/(cε), uniformly for x in compact sets. Integration over all space is the nonrelativistic limit of integration over the causal ball.

**Proposition 6.3 (Free propagator in the ordered limit).** *Fix endpoints x₀ = x_A, x_N = x_B in ℝᵈ, total time T > 0, ε = T/N, and ηₖ = xₖ₊₁ − xₖ. Let D_(c,N) = {(x₁, …, x_(N−1)) : |ηₖ|≤ cε for all k} be the polygons generated within the McGucken Spheres (Theorem 4.1), and let*

widetilde S_(c,N) = ∑ₖ₌₀ᴺ⁻¹mc²ε(1 − √(1 − (|ηₖ|²)/c²ε²)),    (6.2)

*the free action of Theorem 2.7 on the polygon with the common rest term −mc²T removed. With A_ε = (m/2π iħε)^(d/2) and regulator δ > 0, let*

K_(c,N,δ) = A_εᴺ∫_(D_(c,N))e^(iwidetilde S_(c,N)/ħ) e^(−δ∑ⱼ|xⱼ|²)∏ⱼ₌₁ᴺ⁻¹dᵈxⱼ.    (6.3)

*Then*

lim_(N→∞)lim_(δ→0⁺)lim_(c→∞)K_(c,N,δ) = (m/(2π iħ T))^(d/2)exp((im|x_B − x_A|²)/(2ħ T)),    (6.4)

*the free nonrelativistic propagator, and the iterated limit in δ and c is already independent of N.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. For fixed vertices, (x₁, …, x_(N−1))∈ D_(c,N) once c is large enough, so the indicator of D_(c,N) tends to 1 pointwise. With u = |ηₖ|²/(c²ε²), mc²ε(1 − √(1 − u)) = mc²ε(u/2 + O(u²)) = m|ηₖ|²/(2ε) + O(c⁻²), so widetilde S_(c,N)→ S_(NR,N) = ∑ₖ m|ηₖ|²/(2ε) pointwise. The integrand of (6.3) has modulus at most e^(−δ∑ⱼ|xⱼ|²), which is integrable; by dominated convergence, lim_(c→∞)K_(c,N,δ) = A_εᴺ∫_(ℝᵈ⁽ᴺ⁻¹⁾)e^(iS_(NR,N)/ħ)e^(−δ∑ⱼ|xⱼ|²)∏ⱼ dᵈxⱼ. For fixed endpoints, S_(NR,N) is a quadratic form in the intermediate vertices with positive-definite Hessian, so the regulated Fresnel integral has a limit as δ→0⁺, given by iterated Gaussian composition: ∫(m/2π iħε₁)^(d/2)e^(im|x − z|²/2ħε₁)(m/2π iħε₂)^(d/2)e^(im|z − y|²/2ħε₂)dᵈz = (m/2π iħ(ε₁ + ε₂))^(d/2)e^(im|x − y|²/2ħ(ε₁ + ε₂)). Applying it N − 1 times gives the right side of (6.4) for every N. □

The order of limits is the order of the physics: the Spheres reach distance cε in each step, and the nonrelativistic regime is reached by letting c→∞ at fixed ε before refining the slicing. Restoring the rest term multiplies (6.4) by the common phase e^(−imc²T/ħ) of Theorem 2.13.

### 6.3 Recovery of the Schrödinger equation

**Corollary 6.2.** The Feynman path integral derived from the McGucken Principle reproduces the time-dependent Schrödinger equation.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. This is a standard result in the path integral formalism [1]. The propagator K satisfies:


ψ(x_B, t_B) = ∫ K(x_B, t_B; x_A, t_A) ψ(x_A, t_A) dx_A


Taking the limit t_B → t_A + ε for infinitesimal ε and expanding to first order in ε, the integral equation reduces to:


iħ(∂ψ)/(∂ t) = −ħ²/2m(∂²ψ)/(∂ x²) + V(x)ψ


which is the time-dependent Schrödinger equation. The derivation is standard and follows identically whether the path integral is postulated (as Feynman did) or derived from the McGucken Principle (as done here). QED.

**Explicit expansion.** With η = x_A − x_B and the one-step kernel of Theorem 6.1, ψ(x, t + ε) = e^(−iε V(x)/ħ)∫ G(η) ψ(x + η, t) dη (1 + O(ε^(3/2))) with G(η) = A e^(imη²/2ħε). Evaluated with the factor e^(−δη²), δ→0⁺, the moments are ∫ G = 1, ∫η G = 0, ∫η²G = iħε/m, the third moment is zero, and the fourth is of order ε². Taylor expansion of ψ(x + η) to second order gives ψ(x, t + ε) = ψ + iħε/2m∂ₓ²ψ − iε/ħVψ + O(ε^(3/2)). Subtracting ψ(x, t), dividing by ε, and letting ε→0⁺ gives the Schrödinger equation.

**Remark.** The correspondence between the first derivative with respect to time and the second derivative with respect to space in Schrödinger's equation is now understood physically: the first time derivative reflects the single, uniform expansion of x₄ at rate c (one temporal expansion per time step), while the second spatial derivative reflects the diffusion of the wavefront across three-dimensional space (a Laplacian spreading in the spatial directions) generated by that expansion.

## 7. The Classical Limit via Stationary Phase

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

**Theorem 7.1 (Classical mechanics from the McGucken Principle).** In the limit where the action S is large compared to ħ, the path integral derived from the McGucken Principle reduces to classical mechanics: only the path of stationary action (the classical trajectory) contributes. Precisely, the condition is that the variations of S between neighboring histories are large compared to ħ; when several stationary histories exist, each contributes, with a remainder smaller than any power of ħ divided by those variations.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. In the path integral


K = ∫𝒟[x(t)] e^(iS[x(t)]/ħ)


each path contributes with a phase S/ħ. When S/ħ ≫ 1, neighboring paths have rapidly oscillating phases that cancel by destructive interference — except near the path x_(cl)(t) where the action is stationary: δ S/δ x = 0. Near this classical path, the phases vary slowly and add constructively.

The stationary-action condition δ S = 0 yields the Euler-Lagrange equation:


d/dt((∂ L)/(∂ẋ)) − (∂ L)/(∂ x) = 0


which is the equation of motion of classical mechanics.

In precise form: at fixed N, the integral of Theorem 6.1 is an oscillatory integral ∫ a(y) e^(iS_N(y)/ħ) dy over the intermediate positions y = (x₁, …, x_(N−1)). By the stationary-phase theorem [51] (background knowledge, mathematical theorem), as S_N/ħ→∞ the integral is asymptotic to a sum over the nondegenerate critical points y_∗ of S_N, each contributing (2πħ)^((N−1)/2)|det S_N''(y_∗)|^(−1/2)e^(iπ sgn S_N''(y_∗)/4) a(y_∗) e^(iS_N(y_∗)/ħ), with the regions free of critical points contributing less than any power of ħ/S. The critical points satisfy ∂ S_N/∂ xₖ = 0 for every k, the discrete Euler–Lagrange equations, whose limit as N→∞ is the Euler–Lagrange equation. For a free particle S = i mc X₄ = −mc²τ (Theorem 2.7), so the stationary history is the stationary point of the proper time, which by Lemma 2.6 is the straight worldline of maximal accumulated x₄-advance. Only variations of S enter: replacing S by S + C multiplies every contribution by the common phase e^(iC/ħ), which cancels from every probability, so an additive constant can make |S|/ħ arbitrarily large without changing any interference. This is the argument of Dirac [28] and of Feynman [27, §7], quoted in Section 11.1, with the stationary history now identified as the history of maximal accumulated x₄-advance.

Thus the McGucken Principle contains classical mechanics as a limiting case. At the fundamental level, the expansion of x₄ distributes the particle across all paths. At the macroscopic level, the accumulated phases from the complex fourth coordinate cancel everywhere except along the classical trajectory, and the particle appears to follow a single path — Newton's path. QED.

In the McGucken interpretation, the same picture holds with a geometric gloss:

- Paths near the classical geodesic correspond to histories where the advance through x₄ is nearly stationary with respect to variations.
- Their accumulated x₄-phase changes slowly, so nearby paths reinforce.
- Paths that depart significantly from stationarity suffer rapid x₄-phase oscillations from step to step; their contributions cancel.
- The macroscopic world is thus the interference pattern of the expanding fourth dimension, where only those histories that "surf" x₄ in stationarity survive.

### 7.1 Physical example: a thrown baseball

A baseball thrown from a pitcher's hand to the catcher's mitt has an action S on the order of 10³⁵ħ — an astronomically large number. The kinetic action is of this order, and so is the difference in action between the parabolic path and a path that loops through the upper atmosphere; it is these differences that enter the phases. The McGucken expansion of x₄ still distributes the baseball across all paths, including paths that loop through the upper atmosphere or reverse direction. But the phases along these exotic paths oscillate rapidly — an action change of ħ, about one part in 10³⁵ of S, shifts the phase by one radian — and cancel completely. Only the parabolic trajectory — the path of stationary action — survives. The baseball follows Newton's laws not because it fails to explore other paths, but because the complex fourth coordinate x₄ = ict assigns all non-classical paths destructively interfering phases.

## 8. Unification: Feynman's Many Paths, Huygens' Principle, Brownian Motion, and Entropy

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

**Theorem 8.1 (Four phenomena from one principle).** The McGucken Principle dx₄/dt = ic is the common geometric origin of Huygens' Principle, Feynman's path integral, Brownian motion, and entropy increase.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. The McGucken Principle states that the fourth dimension expands at c in a spherically-symmetric manner. This single fact manifests in four ways depending on the physical context:

(i) *Huygens' Principle.* The spherically-symmetric expansion of x₄ distributes each point into a spherical wavefront (Lemma 3.1). Each point on the wavefront acts as a new source. This is Huygens' Principle — the foundation of wave optics.

(ii) *Feynman's path integral.* Successive Huygens expansions, over N time steps in the limit N → ∞, generate all possible paths connecting two spacetime points (Theorem 4.1). The complex character of x₄ = ict assigns each path the phase e^(iS/ħ) (Theorem 5.1). The sum over all paths with these phases is the Feynman path integral (Theorem 6.1).

(iii) *Brownian motion.* For a classical particle subject to thermal fluctuations, the expansion of x₄ at each time step distributes its position across a spherical shell. Because the direction of displacement is random (uniformly distributed over the sphere), the particle executes a random walk. After N steps of size r, the mean squared displacement grows as Nr² — the signature of Brownian motion and diffusion. (For independent steps r₁, …, r_N with |rᵢ| = r and isotropic directions, ⟨rᵢ·rⱼ⟩ = 0 for i≠ j, so ⟨|∑ᵢrᵢ|²⟩ = ∑ᵢ⟨|rᵢ|²⟩ = Nr². With a step duration τ_∗, the walk has diffusion constant D = r²/(6τ_∗) in three dimensions, since ⟨|Xₜ|²⟩ = 6Dt.) The McGucken Principle is the geometric origin of the random walk [6, 38, 40].

(iv) *Entropy increase.* Consider N particles in an initial configuration. At each time step, the expansion of x₄ displaces each particle by a random amount (as in (iii)). The mean squared displacement from the initial configuration grows monotonically with time, and the accessible phase-space volume grows correspondingly. (For the position Xₙ of a particle after n independent isotropic steps, with X₀ distributed with a density, the differential entropy is nondecreasing: h(Xₙ₊₁) = h(Xₙ + rₙ₊₁)≥ h(Xₙ + rₙ₊₁ | rₙ₊₁) = h(Xₙ), since conditioning does not increase entropy and translation preserves it. This is the entropy of the position distribution under independent isotropic steps. Its identification with thermodynamic entropy, including the energy balance and the momentum distribution, is supplied by the thermodynamics chain of theorems [40], which the McGucken Cosmology paper [17] summarizes as "dS/dt = (3/2)k_B/t > 0 for massive-particle ensembles via the Compton-coupling Brownian mechanism (Theorems 4–9 of [MGT])", with [MGT] = [40] here.) This is entropy increase — the Second Law of Thermodynamics — derived from the expansion of the fourth dimension [6, 11, 40]. The McGucken Principle triumphs over the Past Hypothesis [46] by providing a dynamical mechanism for entropy increase rather than merely assuming special initial conditions. QED.

### 8.1 The deep connection: wave mechanics and statistical mechanics

The unification of (ii) and (iii) illuminates a deep mathematical connection. The Feynman path integral in real time,


K = ∫𝒟[x(t)] e^(iS/ħ)


becomes, under the Wick rotation [48] t → −iτ, the Wiener integral [47] of statistical mechanics:


W = ∫𝒟[x(τ)] e^(−S_E/ħ)


where S_E is the Euclidean action. The Wiener integral describes Brownian motion and diffusion, and with a potential it gives the Feynman–Kac representation [57] of the solution of the diffusion equation.

The McGucken Principle explains why this Wick rotation works. The fourth coordinate is x₄ = ict. The Wick rotation t → −iτ transforms x₄ = ict → x₄ = cτ — it removes the imaginary unit, converting the complex fourth coordinate into a real Euclidean coordinate. In the complex (Minkowskian) form, the expansion of x₄ generates quantum-mechanical amplitudes with oscillating phases (Feynman paths). In the real (Euclidean) form, the expansion of x₄ generates classical statistical distributions with decaying weights (Brownian paths). Both are manifestations of the same geometric expansion — the only difference is whether the fourth coordinate carries its intrinsic factor of i.

This is a profound result. The connection between quantum mechanics and statistical mechanics — between Feynman's path integral and Wiener's integral, between the Schrödinger equation and the diffusion equation — is not a mathematical coincidence. It is a direct consequence of the McGucken Principle: both arise from the expansion of the fourth dimension at c, and the factor i in x₄ = ict is what distinguishes quantum oscillation from classical diffusion.

### 8.2 Physical example: the wave pool and the path integral

Drop a stone into a still pool. Circular wavefronts expand from the point of impact — this is Huygens' Principle made visible, driven by the expansion of x₄. Each point on each wavefront generates new wavelets. If the pool contains obstacles (barriers with slits), the wavelets diffract and interfere, producing the same patterns seen in the quantum double-slit experiment. The wave pool is a macroscopic analog of the Feynman path integral: the stone generates all paths (wavefronts), and the interference of these paths (wavelets) determines the final pattern.

Now drop food coloring into the same pool. The dye molecules undergo Brownian motion — random walks driven by the same fourth-dimensional expansion. The dye spreads irreversibly; entropy increases. The wave pool demonstrates both (ii) and (iii) simultaneously: wave interference (quantum mechanics) and irreversible spreading (thermodynamics), both arising from the same expanding fourth dimension.

## 9. The McGucken Principle dx₄/dt = ic Reading of Two Particles: Joint Histories, the Nonseparable Joint Kernel, and Co-Emitted Photons

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

**McGucken Principle anchor.** Each of two particles has its histories generated by its own iterated McGucken Spheres (Theorem 4.1), and the pair of histories carries the phase of the total accumulated action (Theorem 2.13). This section proves that the joint kernel on the joint configuration space factorizes exactly when the interaction separates, that an interaction with a nonzero mixed derivative makes the joint kernel nonseparable and entangles product states, and that two photons emitted at one event, each at rest in x₄ with relative displacement Δ x₄ = 0, carry a joint polarization amplitude whose correlations exceed the Bell bound.

### 9.1 The McGucken Principle dx₄/dt = ic Reading of Joint Histories and the Joint Kernel

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. Every event on either particle's history is the apex of a Sphere, so each particle's histories are generated by iterated Spheres, and the joint histories are the pairs.

**Lemma 9.1 (Crossing points).** *Every causal history from t_A to t_B crosses each slice t = tₖ, t_A < tₖ < t_B, at exactly one point.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. On a timelike history dt/dτ = γ ≥ 1 (Lemma 2.1); on a future-directed null history |dx| = c dt with dt > 0. In both cases t increases strictly along the history, so it meets each slice exactly once. □

**Definition 9.2 (Joint history and joint configuration space).** A joint history of particles 1 and 2 from t_A to t_B is a pair (γ₁, γ₂) of histories over the same interval of t. By Lemma 9.1, it crosses each slice tₖ at exactly one pair (x₁ₖ, x₂ₖ) ∈ ℝ³×ℝ³. The joint configuration space ℝ⁶ is the space of these crossing-point pairs, and the joint time-sliced integral of Theorem 6.1 integrates over it at each slice.

**Lemma 9.3 (Joint phase factor).** *The action of a joint history is S = S₁[γ₁] + S₂[γ₂] − ∫ V(x₁, x₂, t) dt, where Sₐ is the action of particle a including any external potential acting on it alone and V is the interaction. Its phase factor is*

Φ[γ₁, γ₂] = exp{i/ħ(S₁[γ₁] + S₂[γ₂] − ∫ V dt)}.    (9.1)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Each particle's free action is i mₐc X₄[γₐ] by Theorem 2.7, and the total action is the sum of the actions of the parts plus the interaction term. Lemma 2.11 and Theorem 2.13 apply to the total action. □

By Theorem 6.1 applied on ℝ⁶, the one-step joint kernel, with L evaluated on the straight segment from (y₁, y₂) to (x₁, x₂), is

K_ε((x₁, x₂), (y₁, y₂)) = A₁A₂exp{i/ħ[(m₁|x₁ − y₁|²)/2ε + (m₂|x₂ − y₂|²)/2ε − εV̄]},    (9.2)

with V̄ = ∫₀¹V(y₁ + s(x₁ − y₁), y₂ + s(x₂ − y₂)) ds the value of V averaged along the segment, and A₁A₂ ≠ 0.

**Theorem 9.4 (Factorization for separable interactions).** *If V(x₁, x₂, t) = V₁(x₁, t) + V₂(x₂, t), then for every N the time-sliced joint kernel is the product K_N⁽¹⁾(x₁, y₁) K_N⁽²⁾(x₂, y₂), and the same holds in the limit N → ∞. A product initial state φ⊗χ remains a product state.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Absorb Vₐ into Sₐ. The phase factor (9.1) is then a product of a factor depending only on particle-1 vertices and a factor depending only on particle-2 vertices. The integral over ∏ₖ d³x₁ₖ d³x₂ₖ splits by Fubini's theorem, applied to the integrands with a damping factor e^(−δ(|x₁ₖ|² + |x₂ₖ|²)) and then δ → 0⁺, into the product of the single-particle integrals. The limit of a product is the product of the limits. Applying the product kernel to φ(y₁)χ(y₂) gives (K⁽¹⁾φ)(x₁) (K⁽²⁾χ)(x₂). □

**Lemma 9.5 (Mixed logarithmic derivative test).** *Let F be a C² function on an open set U₁× U₂ ⊂ ℝ³×ℝ³, with U₁, U₂ open balls, that vanishes nowhere. If F(x₁, x₂) = f(x₁)g(x₂) on U₁× U₂, then for any continuous branch of log F,*

(∂²log F)/(∂ x₁ʲ ∂ x₂ᵏ) = 0 on U₁× U₂ for all j, k.    (9.3)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Since F vanishes nowhere, neither do f and g; fixing x̄₂, f = F(·, x̄₂)/g(x̄₂) is C², and likewise g. On the simply connected set U₁× U₂, log F = log f(x₁) + log g(x₂) + 2π in with n constant by continuity, so the mixed second derivative is zero. □

**Theorem 9.6 (Nonseparability of the joint kernel).** *Let V be C² with ∂²V/∂ x₁ʲ∂ x₂ᵏ ≠ 0 at (x̄₁, x̄₂) for some j, k, and let U ⊂ ℝ⁶ be an open ball about (x̄₁, x̄₂) on which this derivative has constant sign. Then for every ε > 0 and every (y₁, y₂) ∈ U, the one-step joint kernel (9.2), as a function of (x₁, x₂), is not of the form f(x₁)g(x₂) on any product of open balls contained in U.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. The kernel (9.2) vanishes nowhere, and a branch of its logarithm is log(A₁A₂) + i/ħ[(m₁|x₁ − y₁|²)/2ε + (m₂|x₂ − y₂|²)/2ε − εV̄]. The kinetic terms each depend on one particle's position, so

(∂²log K_ε)/(∂ x₁ʲ ∂ x₂ᵏ) = −iε/ħ∫₀¹ s² (∂²V)/(∂ x₁ʲ ∂ x₂ᵏ)(y₁ + s(x₁ − y₁), y₂ + s(x₂ − y₂)) ds.

For (x₁, x₂) and (y₁, y₂) in the convex set U, the segment between them lies in U, where the integrand has constant sign and is nonzero; so the integral is nonzero. By Lemma 9.5, K_ε is not a product on any product of balls in U. □

**Theorem 9.7 (Entanglement generation).** *Let V be C^∞ with bounded derivatives and satisfy the hypothesis of Theorem 9.6. Let ψ₀ = φ⊗χ with φ, χ Schwartz-class and ψ₀(x̄₁, x̄₂) ≠ 0. Let ψ_ε = e^(−iε H/ħ)ψ₀, with H = H₁ + H₂ + V the two-particle form of Corollary 6.2, and assume ψ_ε = ψ₀ − iε/ħHψ₀ + R_ε with ‖R_ε‖_(C²(W̄)) = O(ε²) on a compact neighborhood W̄ of (x̄₁, x̄₂). Then there is ε₀ > 0 such that for 0 < ε < ε₀ no f, g ∈ L²(ℝ³) satisfy ψ_ε = f⊗ g almost everywhere: ψ_ε is entangled.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Shrink W̄ to a product of closed balls on which ψ₀ vanishes nowhere and ∂²V/∂ x₁ʲ∂ x₂ᵏ is bounded away from zero. For small ε, ψ_ε vanishes nowhere on W̄, and in C²(W̄)

logψ_ε = logφ + logχ − iε/ħ(H₁φ/φ + H₂χ/χ + V) + O(ε²).

The terms logφ and H₁φ/φ depend on x₁ alone, and logχ and H₂χ/χ on x₂ alone, so

(∂²logψ_ε)/(∂ x₁ʲ ∂ x₂ᵏ) = −iε/ħ(∂²V)/(∂ x₁ʲ ∂ x₂ᵏ) + O(ε²),

which is nonzero on W̄ for 0 < ε < ε₀. Suppose ψ_ε = f⊗ g almost everywhere. Since ψ_ε is continuous and nonzero on W̄, Fubini's theorem gives a slice x₂ = x̄₂' on which the identity holds almost everywhere with g(x̄₂') ≠ 0, so f agrees almost everywhere with the C² function ψ_ε(·, x̄₂')/g(x̄₂'); likewise g. The C² representatives satisfy ψ_ε = fg on the interior of W̄ by continuity, and Lemma 9.5 gives a zero mixed logarithmic derivative, a contradiction. □

**Corollary 9.8 (Newtonian and Coulomb interactions entangle).** *For V = α/|x₁ − x₂| with α ≠ 0 (Newtonian: α = −Gm₁m₂; Coulomb: α = q₁q₂/4πϵ₀), the hypothesis of Theorem 9.6 holds at every configuration with x₁ ≠ x₂, on balls excluding the coincidence set, and Theorem 9.7 applies to every C^∞ potential with bounded derivatives that equals α/|x₁ − x₂| on a neighborhood of the configuration, such as a short-distance regularization of it.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. With r = x₁ − x₂, ∂_(x₁ʲ)∂_(x₂ᵏ)(1/r) = −∂_(rⱼ)∂_(rₖ)(1/r) = (δⱼₖr² − 3rⱼrₖ)/r⁵. Choosing axes with r along xʲ and k = j gives −2/r³ ≠ 0. □

The mutual Newtonian term is counted once in the two-body action; the test-particle expression (2.7) for each body counts it twice, and at Newtonian order the gravitational field energy supplies the compensating term, as in the Einstein–Infeld–Hoffmann two-body Lagrangian [53] (background knowledge).

**LTD reading.** In the McGucken dx₄/dt = ic framework, entanglement generated by interaction is the nonseparability of the phase of the joint accumulated action. Each particle's free phase counts its own accumulated x₄-advance in its own Compton wavelengths (Corollary 2.14), and these phase factors multiply, so separable interactions leave product states as product states (Theorem 9.4). An interaction depending jointly on both positions adds a phase that is a function of the pair, and the joint kernel on the joint configuration space of crossing-point pairs cannot be split (Theorems 9.6 and 9.7). Feynman's 1948 elimination of the field oscillators reaches the same kind of joint phase: "The interactions which result involve relationships of the motion of one particle at one time, and of the other particle at another time" [27, §13]. A phase that depends on the pair of motions is the nonseparable joint phase of Lemma 9.3.

### 9.2 The McGucken Principle dx₄/dt = ic Reading of the Photon: At Rest in x₄

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. A photon moving at c has Sphere-tangent share v_(x₄) = 0: the photon is at rest in x₄, and its worldline lies on the future null cone Σ⁺(p) swept out by the McGucken Spheres of its emission event p, while the rate dx₄/dt = ic holds at every event the photon crosses.

The following definitions and lemma are reproduced verbatim and in full from [17], §X.7.2. In them, (R2) and (R4) "of Appendix B" are the quantities (R2) and (R4) of Section 2.1; [159] is the general relativity paper [19]; [255] is the companion general-relativity paper cited in [17]; Channel A is the dx₄/dt = ic Algebraic Channel and Channel B the dx₄/dt = ic Geometric Channel.

> **Definition (x₄-coordinate of a wavefront point).** Let q = (**x**, t) ∈ Σ_t(p) for p = (**x**₀, t₀). The *x₄-coordinate of q relative to p*, denoted x₄(q; p), is the accumulated x₄-advance X₄[γ] along the radial null geodesic γ from p to q, in the sense of (R4) of Appendix B. By the Massless–Lightspeed Equivalence (a photon has Sphere-tangent share v_x4 = 0 per (R2) of Appendix B, so the (R4) accumulated advance X₄[γ] is constant along the null worldline; equivalently, the affinely-parametrised null tangent dx^μ/dλ has vanishing x₄-component [159, GR Theorem 6; Lemma 7.2.2.1a of [255]]):
>
>   x₄(q; p) = 0 for every q ∈ Σ_t(p), every t > t₀.
>
> **Definition (Sphere-surface x₄-locality).** The McGucken Sphere Σ⁺(p) *has x₄-local surface* if every q ∈ Σ_t(p) satisfies x₄(q; p) = 0, and this property holds for every t > t₀ and every p ∈ M.
>
> **Lemma (Joint forcing of sphere-surface x₄-locality).** The McGucken configuration is forced jointly by the Channel A (algebraic-symmetry) and Channel B (geometric-propagation) readings of the McGucken Principle: Channel A's invariance content forces x₄(q; p) to be constant on Σ⁺(p); Channel B's propagation content forces the constant value to be zero.
>
> *Proof.* **Channel A step.** The quantity x₄(q; p) defined by the (R4) accumulated advance from p to q is a Lorentz scalar. By the Channel A reading, Σ⁺(p) is invariant under the Lorentz subgroup SO(3,1) that fixes p. The orbit structure of SO(3,1) acting on Σ⁺(p) ∖ {p} is a single orbit, since SO⁺(3,1) acts transitively on the future null cone with apex removed. Therefore any SO(3,1)-invariant function on Σ⁺(p) ∖ {p} is constant. Denote this constant K_p. **Channel B step.** By the Massless–Lightspeed Equivalence [159, GR Theorem 6], the photon has Sphere-tangent share v_x4 = 0 (per (R2) of Appendix B), so the accumulated advance X₄[γ] = ∫ic·dτ along the null worldline is 0 (per (R4) of Appendix B; equivalently, dτ = 0 identically on the null worldline so the integral vanishes). Therefore x₄(q; p) = 0, so K_p = 0. ∎

**Note on the quoted passage.** The equivalence stated parenthetically in the quoted Definition holds for the accumulated advance: along an affinely parametrized null worldline, dX₄/dλ = ic dτ/dλ = 0, so X₄ is constant. The coordinate component is dx₄/dλ = ic dt/dλ, which is nonzero along a future-directed null worldline, and the rate dx₄/dt = ic holds at every event of it (R1). The surface statement x₄(q; p) = 0 rests on the vanishing accumulated advance (R4) and is unaffected.

**Lemma 9.9 (Co-emitted photons share one x₄ location).** *Let two photons be emitted at the event p₀. Each is at rest in x₄ (v_(x₄) = 0), each worldline lies on Σ⁺(p₀), each has x₄(q; p₀) = 0 at every event q of its worldline, and the relative x₄-displacement of the two photons is Δ x₄ = 0 at every pair of events on their worldlines. The coordinate rate dx₄/dt = ic holds at every one of these events.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. A photon has v = c, so v_(x₄) = 0 by Lemma 2.2. Its worldline satisfies |x − x₀| = c(t − t₀), which is membership in Σ⁺(p₀). By the Definition and Lemma above, x₄(q; p₀) = 0 at every event q of either worldline, so the difference of the two values is zero. The rate (R1) is the expansion rate at each event, the same whichever worldline crosses it. □

**Lemma 9.10 (No accumulated phase along a photon worldline).** *Along a photon worldline in free space, the phase of a plane wave is constant, and the transverse polarization assigned at p₀ is carried unchanged.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. For e^(i(k·x − ω t)) with ω = c|k| along x = x₀ + c(t − t₀)k̂, the phase k·x − ω t = k·x₀ − ω t₀ is constant. In flat space the transverse polarization vector is parallel-transported without rotation. □

The constant phase of Lemma 9.10 matches the vanishing accumulated advance, X₄ = 0, of Lemma 9.9.

### 9.3 The McGucken Principle dx₄/dt = ic Reading of the Joint Polarization Amplitude

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. The Sphere of a single emission event is SO(3)-symmetric, and the joint polarization amplitude of two photons emitted there is fixed at that event by this symmetry and the source.

**Theorem 9.11 (Joint polarization amplitude).** *Let two photons be emitted at p₀ back-to-back along ±ẑ from a source with total angular momentum zero along ẑ and even parity under reflection in a plane containing ẑ (for example the atomic J = 0 → J = 1 → J = 0 cascade of Aspect, Grangier, and Roger [23], the configuration with which Feynman's 1982 two-photon analysis begins: "What can happen is that an atom emits two photons in opposite direction" [30, §7]). With each photon's polarization space the transverse space span{x̂, ŷ} [21], the joint polarization amplitude is*

Ψ = 1/(√2)(|x⟩|x⟩ + |y⟩|y⟩).    (9.4)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from the single event p₀. Write Ψ = ∑ᵢⱼMᵢⱼ|i⟩|j⟩, i, j ∈ {x, y}. A rotation by ϕ about ẑ acts on both transverse polarization vectors by the same matrix R(ϕ) in the lab basis, so M ↦ RMRᵀ. Zero angular momentum along ẑ is invariance, RMRᵀ = M for all ϕ; since Rᵀ = R⁻¹, M commutes with every R(ϕ) = cosϕ I + sinϕ Ω, Ω = R(π/2) = [[0, −1], [1, 0]], hence with Ω. The matrices commuting with Ω are α I + βΩ. Reflection x → −x acts by P = diag(−1, 1) on each photon, M ↦ PMP, with PIP = I and PΩ P = −Ω; even parity gives β = 0. Normalization gives M = I/√2. □

### 9.4 The McGucken Principle dx₄/dt = ic Reading of the Bell Correlations

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. The amplitude (9.4), fixed at p₀, is carried unchanged by two photons at rest in x₄ at one shared x₄ location, Δ x₄ = 0, however far apart they are in x₁, x₂, x₃.

**Born rule (imported).** The probability of a joint outcome is P = |⟨ a|⟨ b|Ψ⟩|². This paper imports the corpus derivation of the Born rule from the SO(3)-invariant (Haar) measure on the McGucken Sphere [20], which is also a theorem of the quantum-mechanics chain [55].

**Theorem 9.12 (Correlation function and CHSH value).** *For linear polarizers at angles a and b, |a⟩ = cos a |x⟩ + sin a |y⟩, with outcome +1 for transmission along a and −1 along a + π/2,*

P(±, ±|a, b) = 1/2cos²(a − b), P(±, ∓|a, b) = 1/2sin²(a − b), E(a, b) = cos2(a − b).    (9.5)

*For a = 0, a' = π/4, b = π/8, b' = 3π/8, the CHSH quantity 𝒮 = E(a, b) − E(a, b') + E(a', b) + E(a', b') equals 2√2.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic and Theorem 9.11. ⟨ a|⟨ b|Ψ⟩ = (cos acos b + sin asin b)/√2 = cos(a − b)/√2, so P(+, +) = 1/2cos²(a − b); replacing a → a + π/2 and b → b + π/2 gives the others. E = cos²(a−b) − sin²(a−b) = cos2(a − b). With the stated angles, E(a, b) = (√2)/2, E(a, b') = −(√2)/2, E(a', b) = (√2)/2, E(a', b') = (√2)/2, so 𝒮 = 2√2. □

**Theorem 9.13 (Bell bound for factorizable models [24, 25]).** *If there is a variable λ with distribution ρ such that P(A, B|a, b, λ) = P(A|a, λ) P(B|b, λ), then |𝒮| ≤ 2.*

*Proof.* This is a statement about models of the outcomes. Let Ā(a, λ) = ∑_AA P(A|a, λ) ∈ [−1, 1], likewise B̄. Factorization gives E(a, b) = ∫ρ Ā(a, λ)B̄(b, λ) dλ. For numbers in [−1, 1], |Ā(B̄ − B̄') + Ā'(B̄ + B̄')| ≤ |B̄ − B̄'| + |B̄ + B̄'| = 2max(|B̄|, |B̄'|) ≤ 2. Integrating against ρ gives |𝒮| ≤ 2. □

**Theorem 9.14 (Parameter independence holds; outcome independence fails).** *(a) The marginal at either wing is P(±|a, b) = 1/2, independent of the other wing's setting. (b) P(+, +|a, b) ≠ P(+|a, b) P(+|a, b) whenever cos²(a − b) ≠ 1/2. (c) Ψ is not a product state: its coefficient matrix I/√2 has rank 2.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic and Theorem 9.12. (a) P(+|a, b) = 1/2(cos² + sin²) = 1/2. (b) 1/2cos²(a − b) = 1/4 only if cos²(a − b) = 1/2. (c) A product |u⟩|w⟩ has coefficient matrix uwᵀ of rank at most one. □

**LTD reading.** The amplitude (9.4) is fixed at the single event p₀ by the symmetry of its McGucken Sphere and the source. Both photons are at rest in x₄, both worldlines lie on Σ⁺(p₀), and the amplitude is carried unchanged (Lemmas 9.9 and 9.10) at one shared x₄ location, Δ x₄ = 0. Theorem 9.14(a) shows that no signal passes between the wings; Theorem 9.13 shows that no variable fixed in the common past with factorizing response probabilities reproduces (9.5). In the McGucken dx₄/dt = ic framework, the outcome dependence between spacelike-separated detections is located at the shared x₄ location of the two photons, which is the nonlocality of the light sphere named in the Conclusion. Feynman's 1982 conclusion from the same correlations is "That's all. That's the difficulty. That's why quantum mechanics can't seem to be imitable by a local classical computer" [30, §5]; the McGucken dx₄/dt = ic framework locates the source of that difficulty in the x₄-locality of the McGucken Sphere's surface, the quantum nonlocality derived in the quantum-mechanics chain of theorems [55] and in [8, 39].

## 10. The Correspondence Between ∂/∂t and ∂²/∂x² in the Schrödinger Equation

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

**Proposition 10.1.** The first-order time derivative and the second-order spatial derivative in the Schrödinger equation both originate from the expansion of the fourth dimension at c.

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic from every event, as a McGucken Sphere. The Schrödinger equation is:


iħ(∂ψ)/(∂ t) = −ħ²/2m∇²ψ + Vψ


The left side involves the first derivative with respect to time. The right side involves the second derivative with respect to space (the Laplacian). Why first in time but second in space?

The McGucken Principle provides the answer. The expansion of x₄ proceeds uniformly at rate c — a single, directional, irreversible advance. This is a first-order process in time: at each instant, x₄ advances by c dt. Hence the first derivative ∂/∂ t.

The spatial consequence of this expansion is diffusion across a spherical wavefront. Diffusion is described by the Laplacian ∇², which is a second-order operator. The spreading of the wavefront in three-dimensional space after a single temporal expansion step goes as the square of the spatial displacement — the Laplacian encodes this quadratic spreading. Hence the second derivative ∇².

The asymmetry between first-in-time and second-in-space is therefore not mysterious — it is the mathematical expression of a single expansion (first-order in the expanding dimension) producing a diffusive spreading (second-order in the spatial dimensions it expands into). QED.

**Rigorous form.** (a) By Theorem 6.1 the kernels compose, Kₜ₊ₛ = KₜKₛ, for every t and s, because the rate ic is the same at every time. The evolution operators U(t) then form a strongly continuous one-parameter unitary group, and by Stone's theorem [49] (background knowledge, mathematical theorem) U(t) = e^(−iHt/ħ) with H self-adjoint, so ψ(t) = U(t)ψ₀ satisfies iħ ∂ₜψ = Hψ, an equation of first order in t. (b) In the explicit expansion following Corollary 6.2, the term of order ε^(1/2) is the first moment of the kernel, which vanishes because the kernel is invariant under every rotation of η, the isotropy of the McGucken Sphere; the second moment is of order ε, so the lowest nonvanishing spatial operator is of second order. (c) A second-order constant-coefficient operator aⱼₖ∂ⱼ∂ₖ that commutes with all rotations has aⱼₖ = a δⱼₖ, a multiple of ∇². The coefficient iħ/2m is imaginary: the spreading is the diffusion of an amplitude with imaginary diffusion constant, which the continuation t→−iτ of Section 8.1 turns into real diffusion with D = ħ/2m. (d) Explicitly, for the free kernel, widehatU_εψ(k) = e^(−iħε|k|²/2m) ψ̂(k), since the Fourier transform of (m/2π iħε)^(d/2)e^(im|η|²/2ħε) is e^(−iħε|k|²/2m). Hence UₜUₛ = Uₜ₊ₛ and ‖Uₜψ‖₂ = ‖ψ‖₂, and for ψ in the domain of the Laplacian (U_εψ − ψ)/ε→(iħ/2m)Δψ in L², which is iħ ∂ₜψ = −(ħ²/2m)Δψ. For a potential that depends on time, the evolution is a two-time propagator U(t, s) with U(t, r)U(r, s) = U(t, s). Item (a) is the condition Feynman identified for Huygens' principle to hold exactly: "The wave equation of quantum mechanics is first order in the time; therefore, Huygens' principle is correct for matter waves, action replacing time" [27, §7], whereas in optics, with a wave equation of second order in time, "Actually Huygens' principle is not correct" without Kirchhoff's modification [27, §7; 43]. The McGucken Principle supplies both halves: first order in time from the time-independence of the rate ic, and action in place of time from S = i mc X₄ (Theorem 2.7), the accumulated x₄-advance.

## 11. The McGucken Principle dx₄/dt = ic Reading of Feynman's Postulates, Dirac's Correspondence, and Huygens' Principle

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

**McGucken Principle anchor.** The expansion of x₄ at c from every event, with the action h per wavelength step, supplies the elements that Huygens (1690), Dirac (1933), and Feynman (1948) took as given. This section quotes each source, sets each assumption beside the theorem of this paper that supplies it, and proves that Feynman's sum over paths couples every point of a spatial slice to every other with equal magnitude: the coherent sum over a wavefront that his postulates require is a nonlocal operation, and the McGucken Sphere's surface is where that nonlocality resides.

### 11.1 The McGucken Principle dx₄/dt = ic Reading of the Sources

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. Each quoted statement below is followed by the theorem of the Principle that supplies it.

**Dirac, 1933 [28].** Dirac wrote that the transformation function between times T and t "corresponds to exp[i∫_TᵗL dt/h]" (his h is ħ), and for the classical limit that "the only important part in the domain of integration is that for which F is stationary for small variations in all the intermediate q's."

**LTD reading.** Theorem 2.13 gives the correspondence as an equality, Φ[γ] = e^(iS[γ]/ħ), with the phase angle from the wavelength of the McGucken Sphere (Lemma 2.11), the complex unit from the i of dx₄/dt = ic (Lemma 2.12), and the sign from the +ic orientation. Dirac's stationary part is the history of maximal accumulated x₄-advance (Theorem 7.1, Lemma 2.6).

**Feynman, Nobel Lecture, 1965 [29].** Recalling Dirac's paper, Feynman asks "what does he mean, they are analogous; what does that mean, analogous?" and reports that he "had made the discovery that what Dirac thought was analogous, was, in fact, equal." He summarizes the formulation: "for each possible way that the particle can go from one point to another in space-time, there's an amplitude," and "Amplitudes from various paths superpose by addition."

**LTD reading.** Feynman established the equality by showing that the sum reproduces Schrödinger's equation. The McGucken Principle supplies the reason for it: the action of a free history is i mc times its accumulated x₄-advance (Theorem 2.7), and one wavelength step of the expansion carries the action h, so the phase is the count of accumulated advance in Compton wavelengths (Corollary 2.14).

**Feynman, 1948 [27].** The abstract states: "The contribution from a single path is postulated to be an exponential whose (imaginary) phase is the classical action (in units of ℏ) for the path in question." The two postulates read:

> I. If an ideal measurement is performed to determine whether a particle has a path lying in a region of space-time, then the probability that the result will be affirmative is the absolute square of a sum of complex contributions, one from each path in the region.
>
> II. The paths contribute equally in magnitude, but the phase of their contribution is the classical action (in units of ℏ); i.e., the time integral of the Lagrangian taken along the path.

On the classical limit (§7): "If ℏ is very small, the exponent will be a very rapidly varying function of any of its variables xᵢ," and the stationary condition "is Hamilton's principle and leads directly to the Lagrangian equations of motion" [54]. On Huygens (§7): the recursion for the wave function "is easily interpreted physically as the expression of Huygens' principle for matter waves," and "The wave equation of quantum mechanics is first order in the time; therefore, Huygens' principle is correct for matter waves, action replacing time."

**LTD reading.** Each clause of the postulates is a theorem of the McGucken Principle or a stated input, as Table 1 records. "Action replacing time" is, in the McGucken dx₄/dt = ic framework, accumulated x₄-advance replacing time: S = i mc X₄[γ] (Theorem 2.7). The first order in time that Feynman requires is the time-independence of the rate ic (Section 10, item (a)).

**Feynman, *QED*, 1985 [34].** On the reflection of light from a mirror: "The nearby, nearly straight paths—through C and E, for example—also make important contributions. So light doesn't really travel only in a straight line; it ‘smells’ the neighboring paths around it, and uses a small core of nearby space."

**LTD reading.** The core that Feynman describes has a width set by the wavelength. Paths whose phase differs from that of the stationary path by less than about one radian add constructively, and by Corollary 2.14 the phase of a massive particle's history is its accumulated x₄-advance counted in reduced Compton wavelengths: the contributing core consists of the histories whose accumulated advance lies within about λ̄_C = ħ/mc of the maximal advance (Lemma 2.6), and its width is set by the wavelength of the McGucken Sphere. For light the same count is in optical wavelengths: paths whose travel times differ from the stationary one by less than about one period contribute. A single quantum drawing on a core of spatially separated paths is the nonlocality of Section 11.3 on the scale of one wavelength.

**Huygens, 1690 [32].** Quoted in Section 3: around each particle of the medium "there is made a wave of which that particle is the centre."

**LTD reading.** The McGucken Principle provides the physical mechanism: x₄ expands spherically at c from every event, so every event is the apex of a McGucken Sphere with no medium required (Lemma 3.1).

### 11.2 The McGucken Principle dx₄/dt = ic Reading of the Assumed Elements

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h. Table 1 lists what each predecessor assumed and what the Principle supplies; Table 2 lists the sections of this paper that correspond to passages of Feynman's work.

**Table 1.** Elements assumed by Huygens, Dirac, Feynman, and Minkowski, and the theorem or mechanism of the McGucken Principle dx₄/dt = ic that supplies each.

| McGucken Principle dx₄/dt = ic supplies | Assumed by | Assumption as stated or used |
|:---------------------------------|:-----------|:-----------------------------|
| x₄ = ict as the integral of the rate dx₄/dt = ic; the Lorentzian line element (Lemma 2.1) | Minkowski 1908 [15] | The coordinate x₄ = ict is introduced as a notation |
| Every event is the apex of a McGucken Sphere because x₄ expands spherically at c from every event; the envelope is proved (Lemma 3.1) | Huygens 1690 [32] | "around each particle there is made a wave of which that particle is the centre," as a property of an elastic medium |
| Action is i mc times the accumulated x₄-advance, S = i mc X₄ (Theorem 2.7) | Feynman 1948 [27, §7] | Huygens' principle for matter waves with "action replacing time" |
| Phase angle S/ħ from the wavelength of the McGucken Sphere, one wavelength step carrying h (Lemma 2.11) | Feynman 1948, Postulate II [27] | "the phase of their contribution is the classical action (in units of ℏ)" |
| Complex amplitudes: the phase factor is a rotation generated by the i of dx₄/dt = ic (Lemma 2.12) | Feynman 1948, Postulate I [27] | "a sum of complex contributions" |
| Unit magnitude of every phase factor (Lemma 2.12, ∣χ∣ = 1); the equal weighting of histories in the integration measure is part of the superposition input (Theorem 6.1) | Feynman 1948, Postulate II [27] | "The paths contribute equally in magnitude" |
| Equality Φ = e^(iS/ħ) with the sign fixed by +ic (Theorem 2.13) | Dirac 1933 [28]; Feynman 1965 [29] | The transformation function "corresponds to" exp(i∫ L dt/ħ); "analogous" made "equal" |
| Generation of all paths by iterated McGucken Spheres (Theorem 4.1); the additive aggregation remains the superposition input of Section 2 | Feynman 1948, Postulate I [27] | "one from each path in the region" |
| Probability as the squared modulus, from the SO(3)-invariant measure on the McGucken Sphere (imported, [20, 55]) | Feynman 1948, Postulate I [27] | "the absolute square of a sum of complex contributions" |
| Stationary action is maximal accumulated x₄-advance (Theorem 7.1, Lemma 2.6) | Dirac 1933 [28]; Feynman 1948 [27, §7] | Stationary phase selects the classical path |
| The core of contributing paths has a width set by the wavelength of the Sphere: histories within about λ̄_C of maximal accumulated advance (Corollary 2.14) | Feynman 1985 [34] | Light "smells" the neighboring paths and "uses a small core of nearby space" |
| First order in time from the time-independence of the rate ic (Section 10, item (a)) | Feynman 1948 [27, §7] | "The wave equation of quantum mechanics is first order in the time" |
| The real section x₄ = cτ of x₄ = ict fixes the continuation and the sign of the phase (Theorem 2.13, Section 8.1) | Wick rotation [48], as a substitution | t→−iτ as a formal device |
| The surface of the McGucken Sphere is one x₄ location relative to its apex (Section 9.2; Section 11.3) | Feynman 1948, Postulate I and §7 [27] | Coherent sum over all points of a wavefront |

**Table 2.** Sections of this paper and the corresponding passages of Feynman's work.

| This paper (McGucken Principle dx₄/dt = ic) | Feynman source | Correspondence |
|:----------------------------|:---------------|:---------------|
| Section 2 and Section 2.1: phase rule derived | 1948, Postulates I and II [27] | The postulated phase becomes Theorem 2.13 |
| Section 3: Lemma 3.1 and the envelope | 1948, §7 [27] | Huygens' principle for matter waves |
| Section 4.2: double slit | Lectures, Vol. III, §§1-1, 1-7 [31] | The sum of amplitudes for alternative ways |
| Section 5.1 and Section 6.1b: phase from x₄ | Dirac 1933 [28]; Nobel Lecture 1965 [29] | "Analogous" made "equal" |
| Section 6.2: time slicing | 1948, §6 [27] | The recursion for ψ at the next instant |
| Section 7: classical limit | 1948, §7 [27]; Dirac 1933 [28]; *QED* 1985 [34] | Stationary phase, Hamilton's principle, and the core of neighboring paths |
| Section 9.1: nonseparable joint phase | 1948, §§12–13 [27] | Interactions relating one particle's motion at one time to the other's at another |
| Sections 9.3–9.4: two photons, Bell | 1982, §§5, 7–8 [30] | Two photons emitted in opposite directions; no local classical imitation |
| Section 10: first order in time | 1948, §7 [27] | Huygens' principle exact for a wave equation first order in time |
| Section 11.3: nonlocality of the sum | 1948, Postulate I and §7 [27] | Amplitude at a point as a sum over all points of a surface |

**LTD reading.** In every row of Table 1, the right-hand column is an assumption or a formal device, and the left-hand column is a theorem or mechanism of dx₄/dt = ic, except for the inputs this paper states openly: the additive aggregation of phase factors with equal weight for every history in the measure (superposition; Theorem 6.1) and the Born rule, imported from the corpus derivation [20].

### 11.3 The McGucken Principle dx₄/dt = ic Reading of the Nonlocality in Feynman's Sum

**McGucken Principle anchor.** The McGucken Principle dx₄/dt = ic states that x₄ expands at c from every event, as a McGucken Sphere whose wavelength sets h and whose surface defines a nonlocality. Feynman's Postulate I adds, before squaring, the contributions of paths that pass through spatially separated points; his §7 statement of Huygens' principle takes the amplitude at a point as a sum of contributions from all points of a surface [27]. The two theorems below state what this sum entails for the free kernel.

**Theorem 11.1 (Equal magnitude at every separation).** *For the free kernel K_T(x, y) = (m/(2π iħ T))^(3/2)exp((im|x − y|²)/(2ħ T)) and every T > 0,*

|K_T(x, y)| = (m/(2πħ T))^(3/2) for all x, y∈ℝ³.    (11.1)


*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. The exponential has unit modulus because its exponent is imaginary, which is Lemma 2.12; |(2π iħ T/m)^(−3/2)| = (m/2πħ T)^(3/2). □

The magnitude (11.1) does not depend on |x − y|: every point of the slice at time 0 contributes to the amplitude at x at time T with the same magnitude, at every separation. This is Feynman's "The paths contribute equally in magnitude," carried to the kernel, given the equal-weight measure of Theorem 6.1.

**Theorem 11.2 (Dependence on every distant region).** *Let δψ₀ be a nonzero integrable function supported in a ball B⊂ℝ³, and let δψ_T(x) = ∫ K_T(x, y) δψ₀(y) d³y. For every T > 0, δψ_T(x)≠0 for almost every x∈ℝ³, however far x lies from B.*

*Proof.* Everything below descends from the physical expansion of x₄ at rate ic. Expanding |x − y|² = |x|² − 2x·y + |y|²,

δψ_T(x) = (m/(2π iħ T))^(3/2)e^(im|x|²/2ħ T) F(mx/(ħ T)), F(k) = ∫ e^(−ik·y) g(y) d³y, g = e^(im|y|²/2ħ T)δψ₀ .

The function g is integrable, nonzero, and supported in B, so F extends to an entire function on ℂ³ (Paley–Wiener [50]; background knowledge, mathematical theorem) and is not identically zero by injectivity of the Fourier transform. A real-analytic function on ℝ³ that is not identically zero vanishes only on a set of Lebesgue measure zero. Since x↦ mx/ħ T is a linear bijection and the prefactor never vanishes, δψ_T(x)≠0 for almost every x. □

Theorems 11.1 and 11.2 are statements about the amplitude, the propagator acting on wavefunctions. The probability of a normalized detection follows from the Born rule, and no signal is transmitted: every marginal is independent of the distant setting (Theorem 9.14(a)).

In the relativistic theory the corresponding vacuum amplitude for a free particle of mass m at spacelike separation r is, in units ħ = c = 1, D(r) = m/4π²rK₁(mr), nonzero and decaying as e^(−r/λ̄_C) over the reduced Compton wavelength, while the commutator of the fields vanishes at spacelike separation (background knowledge [33]).

**Feynman's assumption.** Feynman's two postulates contain no statement of how contributions from spatially separated points come to be added coherently into one amplitude: the coherence is part of Postulate I. The words "non-local" and "action at a distance" do not appear in the 1948 paper [27]. Theorems 11.1 and 11.2 show what the postulated sum entails: the amplitude at each point depends, with equal magnitude per path and at once in the nonrelativistic kernel, on the amplitude over the whole earlier slice. The surfaces across which Feynman's Huygens construction adds contributions coherently are therefore nonlocal surfaces, and the nonlocality is assumed with the sum.

**LTD reading.** The McGucken Principle provides the physical surface on which the coherent sum is taken. By the verbatim corpus Definition and Lemma of Section 9.2, every point q of the McGucken Sphere Σₜ(p) has x₄(q; p) = 0: the whole surface lies at one x₄ location relative to its apex. Points of a spherical wavefront that are separated in x₁, x₂, x₃ share their x₄ location, and the histories summed in Feynman's kernel share their apex event, from which each history's accumulated x₄-advance and phase are counted (Definition 2.4, Theorem 2.13). The McGucken Sphere's surface defines the nonlocality that Feynman's sum assumes; no signal passes across it, since every marginal is independent of the distant setting (Theorem 9.14(a)).

## 12. Summary of Results

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

From the single postulate dx₄/dt = ic, the following results have been derived:

- **The four-velocity norm** (Lemma 2.3): u^μ u_μ = −c² is a chain-rule consequence of dx₄/dt = ic.
- **Action as accumulated x₄-advance** (Theorem 2.7): S = −mc²∫ dτ = i mc X₄[γ], with X₄[γ] = ic τ[γ].
- **The phase rule** (Lemmas 2.11–2.12, Theorem 2.13, Corollary 2.14): the wavelength of the McGucken Sphere gives the phase angle S/ħ, the i of dx₄/dt = ic gives the complex unit, the +ic orientation gives the sign, and e^(iS/ħ) = exp(−(mc/ħ)X₄) counts the accumulated advance in Compton wavelengths.
- **Huygens' Principle** (Lemma 3.1): Every point acts as a source of spherical wavelets because the fourth dimension's expansion distributes every point across a spherical wavefront.
- **All paths** (Theorem 4.1): Successive Huygens expansions generate the totality of all continuous paths connecting any two spacetime points.
- **The quantum phase** (Theorem 5.1): The complex character of x₄ = ict assigns each path a phase proportional to the classical action.
- **The Feynman path integral** (Theorem 6.1; the quantum-mechanics chain of theorems [55]): The sum over all paths with their phases reproduces the Feynman propagator.
- **The Schrödinger equation** (Corollary 6.2; [55]): The path integral yields the time-dependent Schrödinger equation.
- **Classical mechanics** (Theorem 7.1): The stationary-phase limit recovers Newton's laws.
- **Brownian motion** (Theorem 8.1(iii); the thermodynamics chain of theorems [40]): The random-walk character of the expansion generates classical diffusion.
- **Entropy increase** (Theorem 8.1(iv); [6, 40]): The monotonic growth of phase-space volume driven by the expansion yields the Second Law, triumphing over the Past Hypothesis.
- **The Wick rotation** (Section 8.1): The factor i in x₄ = ict explains why quantum amplitudes become statistical weights under t → −iτ.
- **Entanglement from interaction** (Theorems 9.4, 9.6, 9.7, Corollary 9.8): the joint kernel on the joint configuration space factorizes exactly for separable interactions and is nonseparable when ∂²V/∂ x₁∂ x₂ ≠ 0; Newtonian and Coulomb interactions entangle product states.
- **Co-emitted photons and the Bell correlations** (Lemmas 9.9–9.10, Theorems 9.11–9.14): photons emitted at one event are at rest in x₄ with Δ x₄ = 0; their joint polarization amplitude gives E(a, b) = cos2(a − b) and 𝒮 = 2√2, with parameter independence holding and outcome independence failing.
- **Feynman's sum as a nonlocal sum** (Theorems 11.1–11.2): the free kernel couples every pair of points with equal magnitude, and the amplitude at every point depends on every distant region; the McGucken Sphere's surface, one x₄ location relative to its apex, is the surface on which the coherent sum is taken.
- **The Schrödinger asymmetry** (Proposition 10.1): First-order in time, second-order in space, because a single expansion produces diffusive spreading.
- **Action as x₄-advance** (Section 6.1): The action measures how efficiently a trajectory rides the expanding fourth dimension; the classical path is the path of stationary x₄-advance.
- **The [q, p] = iħ parallel** (Section 6.1b): The parallel between dx₄/dt = ic and the canonical commutation relation bridges geometry and quantum mechanics, and Section 2.1 derives the phase rule it motivates.

All eighteen results emerge from one equation: dx₄/dt = ic. Table 3 records the chain from the Principle to each result and the inputs beyond it.

**Table 3.** The derivation of each result from the McGucken Principle dx₄/dt = ic.

| From dx₄/dt = ic | Result | Inputs beyond the Principle |
|:--------------------------|:-----------------------|:----------------------|
| Rate clause; chain rule (Lemmas 2.1–2.3); [19, 56] | Line element; u^μ u_μ = −c² | None |
| Rate clause; Theorem X.1 (Theorem 2.7) | S = −mc²∫ dτ = i mc X₄ | Rest mass m |
| Wavelength of the Sphere; the i and +ic of the rate (Lemmas 2.11–2.12, Theorem 2.13) | e^(iS/ħ) = exp(−(mc/ħ)X₄) | None beyond h in the Principle |
| Spherical expansion from every event (Lemma 3.1) | Huygens' principle with envelope | None |
| Iterated Spheres (Theorem 4.1) | All continuous paths | None |
| Theorems 2.13, 4.1 (Theorem 6.1); [55] | Feynman's path integral | Superposition with equal weighting in the measure (Section 2, Theorem 6.1); potential V except gravity |
| Time-independence of ic; isotropy of the Sphere (Corollary 6.2, Section 10); [55] | Schrödinger equation | As for Theorem 6.1 |
| Stationary phase; maximal x₄-advance (Theorem 7.1) | Classical mechanics | None |
| Isotropic displacement at each step of the expansion (Theorem 8.1(iii)–(iv)); [6, 40] | Brownian motion; entropy increase | Independence of the steps |
| Gravity changes the Sphere-tangent share at fixed rate ic (Proposition 2.10); [19, 56] | Newtonian potential term | Schwarzschild metric, imported verbatim [17] |
| Real section x₄ = cτ (Section 8.1, Theorem 2.13) | Wick rotation; diffusion | None |
| Joint phase of joint histories (Theorems 9.4–9.7) | Entanglement generated by interaction | Interaction V |
| Photon at rest in x₄; Sphere symmetry (Lemmas 9.9–9.10, Theorems 9.11–9.14); [55] | Bell correlations, 𝒮 = 2√2 | Source specification; Born rule [20] |
| Unit-modulus phase factors (Theorems 11.1–11.2) | Nonlocal dependence in Feynman's sum | None |


## 13. Conclusion

The McGucken Principle asserts that the fourth dimension x₄ is expanding at the velocity of light: dx₄/dt = ic, with x₄ = ict, as a spherically symmetric McGucken Sphere whose wavelength sets the action h and whose surface defines a nonlocality.

Feynman's path integral has been one of the most powerful tools in theoretical physics for over seventy years. Yet the question of why a particle explores all possible paths has remained unanswered. The McGucken Principle answers it: the fourth dimension is expanding at the velocity of light, and this expansion physically distributes every point in space across a spherical wavefront at every instant. The totality of all such expansions generates all paths. The complex character of the expanding fourth coordinate x₄ = ict assigns each path its quantum-mechanical phase. The Feynman path integral is not a mathematical postulate — it is a geometric consequence of dx₄/dt = ic.

The same geometric expansion that generates Feynman's many paths also generates Huygens' wavelets, Brownian motion's random walks, and the irreversible increase of entropy [6, 11, 38, 40]. Quantum mechanics, wave optics, statistical mechanics, and thermodynamics are unified under a single principle [3, 10, 11, 19, 35, 36, 38, 39, 40, 55, 56]: the fourth dimension is expanding at the velocity of light.

And as the principle naturally exalts the light cone and expansive nature of the light sphere, the principle exalts the nonlocality of the light sphere (underlying quantum entanglement) [8, 39] where a photon has an equal chance of being measured due to quantum mechanics. And so it is that in addition to the radiative arrow of time, we glimpse quantum mechanics alongside relativity in the McGucken Principle of the expanding fourth dimension.

The McGucken Principle is a primary law from which the architecture of physical theory is reconstructed.

## Acknowledgements

The author thanks John Archibald Wheeler, whose question — "Can you, by poor-man's reasoning, derive the time part of the Schwarzschild metric?" — initiated this line of inquiry at Princeton, and whose vision of a "breathtakingly simple" underlying idea guided it throughout four decades.

## References

[1] Feynman, R. P. and Hibbs, A. R. *Quantum Mechanics and Path Integrals.* New York: McGraw-Hill, 1965.

[2] McGucken, E. "The McGucken Principle and Proof: The Fourth Dimension Is Expanding at the Velocity of Light." 2024–2026. https://elliotmcguckenphysics.com/2024/10/25/the-mcgucken-principle-the-fourth-dimension-is-expanding-at-the-velocity-of-light-c-dx4-dtic-the-mcgucken-proof-of-the-fourth-dimensions-expansion-at-the-rate-of-c-dx4-dtic/

[3] McGucken, E. "Time as an Emergent Phenomenon: Traveling Back to the Heroic Age of Physics." FQXi Essay Contest, August 25, 2008. https://forums.fqxi.org/d/238-time-as-an-emergent-phenomenon-traveling-back-to-the-heroic-age-of-physics-by-elliot-mcgucken

[4] McGucken, E. "Light, Time, Dimension Theory — Five Foundational Papers on the Fourth Expanding Dimension." 2025. https://elliotmcguckenphysics.com/2025/03/10/light-time-dimension-theory-dr-elliot-mcguckens-five-foundational-papers-2008-2013-exalting-the-principle-the-fourth-dimension-is-expanding-at-the-rate/

[5] McGucken, E. "The Missing Physical Mechanism: How the Principle of the Expanding Fourth Dimension dx₄/dt = ic Gives Rise to the Constancy and Invariance of the Velocity of Light c." 2026. https://elliotmcguckenphysics.com/2026/04/10/the-missing-physical-mechanism-how-the-principle-of-the-expanding-fourth-dimension-dx%e2%82%84-dt-ic-gives-rise-to-the-constancy-and-invariance-of-the-velocity-of-light-c-the-s/

[6] McGucken, E. "The Derivation of Entropy's Increase and Time's Arrow from the McGucken Principle of a Fourth Expanding Dimension dx4/dt=ic." 2025. https://elliotmcguckenphysics.com/2025/08/25/the-derivation-of-entropys-increase-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-a-deeper-connection-between-brownian-motions-random-walk-feynmans/

[7] McGucken, E. "A Formal Derivation of the Standard Model Lagrangians and General Relativity from McGucken's Principle of the Fourth Expanding Dimension dx₄/dt = ic." 2026. https://elliotmcguckenphysics.com/2026/04/14/a-formal-derivation-of-the-standard-model-lagrangians-and-general-relativity-from-mcguckens-principle-of-the-fourth-expanding-dimension-dx%e2%82%84-dt-ic-gauge-symmetry-maxwell/

[8] McGucken, E. "The McGucken Equivalence: Quantum Nonlocality and Relativity Both Emerge From the Expansion of the Fourth Dimension at the Velocity of Light." 2024. https://elliotmcguckenphysics.com/2024/12/29/the-mcgucken-equivalence-of-quantum-nonlocality-and-relativity-how-quantum-nonlocality-and-entanglement-are-found-in-relativitys-time-dilation-and-length-contraction/

[9] McGucken, E. "One Principle Solves Eleven Cosmological Mysteries." 2026. https://elliotmcguckenphysics.com/2026/04/13/one-principle-solves-eleven-cosmological-mysteries-how-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx%e2%82%84-dt-ic-resolves-the-greatest-open-problems-in-cosmology-inclu/

[10] McGucken, E. *Light Time Dimension Theory: The Foundational Physics Unifying Einstein's Relativity and Quantum Mechanics: A Simple, Illustrated Introduction to the Physical Model of the Fourth Expanding Dimension.* 2016. https://www.amazon.com/gp/aw/d/B01KP8XGQ6

[11] McGucken, E. *The Physics of Time: Time & Its Arrows in Quantum Mechanics, Relativity, The Second Law of Thermodynamics, Entropy, The Twin Paradox, & Cosmology Explained via LTD Theory's Expanding Fourth Dimension.* 2017. https://www.amazon.com/Physics-Time-Mechanics-Relativity-Thermodynamics-ebook/dp/B07695MLYQ

[12] Dirac, P. A. M. *The Principles of Quantum Mechanics.* Oxford: Clarendon Press, 1930.

[13] Huygens, C. *Traité de la Lumière.* Leiden, 1690.

[14] Einstein, A. "On the Electrodynamics of Moving Bodies." *Annalen der Physik* 17 (1905): 891–921. https://doi.org/10.1002/andp.19053221004

[15] Minkowski, H. "Raum und Zeit." *Physikalische Zeitschrift* 10 (1908): 104–111.

[16] Wheeler, J. A. *A Journey Into Gravity and Spacetime.* New York: W. H. Freeman, 1990.

[17] McGucken, E. "The McGucken Cosmology dx₄/dt = ic Outranks Every Major Cosmological Model in the Combined Empirical Record (and McGucken accomplishes this with Zero Free Dark-Sector Parameters)." May 19, 2026. https://elliotmcguckenphysics.com/2026/05/19/the-mcgucken-cosmology-dx%e2%82%84-dt-ic-outranks-every-major-cosmological-model-in-the-combined-empirical-record-and-mcgucken-accomplishes-this-with-zero-free-dark-sector-parameters-first-place-3/

[18] McGucken, E. "The Unique McGucken Lagrangian: All Four Sectors — Free-Particle Kinetic, Dirac Matter, Yang-Mills Gauge, Einstein-Hilbert Gravitational — Forced by the McGucken Principle dx₄/dt = ic." April 23, 2026. https://elliotmcguckenphysics.com/2026/04/23/the-unique-mcgucken-lagrangian-all-four-sectors-free-particle-kinetic-dirac-matter-yang-mills-gauge-einstein-hilbert-gravitational-forced-by-the-mcgucken-principle-dx%e2%82%84-2/

[19] McGucken, E. "General Relativity Derived from the McGucken Principle: A Unique, Simple, and Complete Derivation of General Relativity as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic." April 26, 2026. https://elliotmcguckenphysics.com/2026/04/26/general-relativity-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-general-relativity-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension/

[20] McGucken, E. "The Born Rule P = |ψ|² as a Geometric Theorem of the Expanding Fourth Dimension: SO(3) Symmetry of the McGucken Sphere as the Foundational Origin of the Probability Postulate of Quantum Mechanics." April 17, 2026. https://elliotmcguckenphysics.com/2026/04/17/the-born-rule-as-a-geometric-theorem-of-the-expanding-fourth-dimension-a-derivation-from-spacetime-geometry-via-the-mcgucken-principle-how-p-%cf%882-follows-from-the-so3-symmetry/

[21] McGucken, E. "Quantum Electrodynamics from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Local x₄-Phase Invariance, the U(1) Gauge Structure, Maxwell's Equations, and the QED Lagrangian as Theorems of dx₄/dt = ic." April 19, 2026. https://elliotmcguckenphysics.com/2026/04/19/quantum-electrodynamics-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-local-x%e2%82%84-phase-invariance-the-u1-gauge-structure-maxwells-equations-and-the-qed/

[22] Frobenius, F. G. "Über lineare Substitutionen und bilineare Formen." *Journal für die reine und angewandte Mathematik* 84 (1878): 1–63.

[23] Aspect, A., Grangier, P., and Roger, G. "Experimental Realization of Einstein-Podolsky-Rosen-Bohm Gedankenexperiment: A New Violation of Bell's Inequalities." *Physical Review Letters* 49 (1982): 91–94. https://doi.org/10.1103/PhysRevLett.49.91

[24] Bell, J. S. "On the Einstein Podolsky Rosen Paradox." *Physics Physique Fizika* 1 (1964): 195–200. https://doi.org/10.1103/PhysicsPhysiqueFizika.1.195

[25] Clauser, J. F., Horne, M. A., Shimony, A., and Holt, R. A. "Proposed Experiment to Test Local Hidden-Variable Theories." *Physical Review Letters* 23 (1969): 880–884. https://doi.org/10.1103/PhysRevLett.23.880

[26] Nelson, E. "Feynman Integrals and the Schrödinger Equation." *Journal of Mathematical Physics* 5 (1964): 332–343. https://doi.org/10.1063/1.1704124

[27] Feynman, R. P. "Space-Time Approach to Non-Relativistic Quantum Mechanics." *Reviews of Modern Physics* 20 (1948): 367–387. https://authors.library.caltech.edu/47756/

[28] Dirac, P. A. M. "The Lagrangian in Quantum Mechanics." *Physikalische Zeitschrift der Sowjetunion* 3 (1933): 64–72. https://informationphilosopher.com/solutions/scientist/dirac/Lagrangian_1933.pdf

[29] Feynman, R. P. "The Development of the Space-Time View of Quantum Electrodynamics." Nobel Lecture, December 11, 1965. https://www.nobelprize.org/prizes/physics/1965/feynman/lecture/

[30] Feynman, R. P. "Simulating Physics with Computers." *International Journal of Theoretical Physics* 21 (1982): 467–488. https://doi.org/10.1007/BF02650179

[31] Feynman, R. P., Leighton, R. B., and Sands, M. *The Feynman Lectures on Physics*, Vol. III, Ch. 1, "Quantum Behavior." Reading, MA: Addison-Wesley, 1965. https://www.feynmanlectures.caltech.edu/III_01.html

[32] Huygens, C. *Treatise on Light.* Translated by S. P. Thompson. London: Macmillan, 1912. https://www.gutenberg.org/files/14725/14725-h/14725-h.htm

[33] Peskin, M. E. and Schroeder, D. V. *An Introduction to Quantum Field Theory.* Reading, MA: Addison-Wesley, 1995, §2.4.

[34] Feynman, R. P. *QED: The Strange Theory of Light and Matter.* Princeton: Princeton University Press, 1985, Lecture 2, p. 64 of the copy consulted.

[35] McGucken, E. *Multiple Unit Artificial Retina Chipset to Aid the Visually Impaired and Enhanced Holed-Emitter CMOS Phototransistors.* Ph.D. Dissertation, Department of Physics and Astronomy, University of North Carolina at Chapel Hill, 1998. The first written formulation of the McGucken Principle appeared as an appendix to this dissertation [36].

[36] McGucken, E. "The Abstracts of McGucken's Five Seminal Papers on Light, Time, Dimension Theory (2008–2013) and The McGucken Principle–The Fourth Dimension is Expanding at the Rate of c Relative to the Three Spatial Dimensions dx4/dt=ic." March 8, 2025. https://elliotmcguckenphysics.com/2025/03/08/the-abstracts-of-mcguckens-five-seminal-papers-on-light-time-dimension-theory-2008-2013-and-the-mcgucken-principle-the-fourth-dimension-is-expanding-at-the-rate-of-c-relat/

[37] McGucken, E. "What is Ultimately Possible in Physics? Physics! A Hero's Journey with Galileo, Newton, Faraday, Maxwell, Planck, Einstein, Schrodinger, Bohr, and the Greats towards Moving Dimensions Theory. E pur si muove!" FQXi Essay Contest, September 16, 2009. https://forums.fqxi.org/d/511-what-is-ultimately-possible-in-physics-physics-a-heros-journey-with-galileo-newton-faraday-maxwell-planck-einstein-schrodinger-bohr-and-the-greats-towards-moving-dimensions-theory-e-pur-si-muove-by-dr-elliot-mcgucken

[38] McGucken, E. "On the Emergence of QM, Relativity, Entropy, Time, iħ, and ic from the Foundational, Physical Reality of a Fourth Dimension x4 Expanding with a Discrete (Digital) Wavelength lp at c Relative to Three Continuous (Analog) Spatial Dimensions." FQXi Essay Contest, February 11, 2011. https://forums.fqxi.org/d/873-on-the-emergence-of-qm-relativity-entropy-time-i295-and-ic-by-elliot-mcgucken

[39] McGucken, E. "MDT's dx4/dt=ic Triumphs Over the Wrong Physical Assumption that Time is a Dimension, Unfreezing Time and Answering Godel's, Eddington's, et al.'s Challenge, Providing a Mechanism for Emergent Change, Relativity, Nonlocality, Entanglement, and Time's Arrows and Asymmetries." FQXi Essay Contest, August 24, 2012. https://forums.fqxi.org/d/1429-mdts-dx4dtic-triumphs-over-the-wrong-physical-assumption-that-time-is-a-dimension-by-elliot-mcgucken

[40] McGucken, E. "Thermodynamics Derived from the McGucken Principle: A Unique, Simple, and Complete Derivation of Thermodynamics as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic." April 26, 2026. https://elliotmcguckenphysics.com/2026/04/26/thermodynamics-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-thermodynamics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx/

[41] McGucken, E. "It from Bit or Bit From It? What is It? Honor! Where is the Wisdom we have lost in Information? Returning Wheeler's Honor and Philo-Sophy — the Love of Wisdom — to Physics." FQXi Essay Contest, July 3, 2013. https://forums.fqxi.org/d/1879-where-is-the-wisdom-we-have-lost-in-information-returning-wheelers-honor-and-philo-sophy-the-love-of-wisdom-to-physics-by-dr-elliot-mcgucken

[42] Fresnel, A. "Mémoire sur la diffraction de la lumière." *Mémoires de l'Académie Royale des Sciences de l'Institut de France* 5 (1826): 339–475 (prize memoir of 1818).

[43] Kirchhoff, G. "Zur Theorie der Lichtstrahlen." *Annalen der Physik und Chemie* 18 (1883): 663–695.

[44] Schrödinger, E. "Quantisierung als Eigenwertproblem (Erste Mitteilung)." *Annalen der Physik* 79 (1926): 361–376. https://doi.org/10.1002/andp.19263840404

[45] Heisenberg, W. "Über quantentheoretische Umdeutung kinematischer und mechanischer Beziehungen." *Zeitschrift für Physik* 33 (1925): 879–893. https://doi.org/10.1007/BF01328377

[46] Albert, D. Z. *Time and Chance.* Cambridge, MA: Harvard University Press, 2000.

[47] Wiener, N. "Differential-Space." *Journal of Mathematics and Physics* 2 (1923): 131–174.

[48] Wick, G. C. "Properties of Bethe-Salpeter Wave Functions." *Physical Review* 96 (1954): 1124–1134. https://doi.org/10.1103/PhysRev.96.1124

[49] Stone, M. H. "On One-Parameter Unitary Groups in Hilbert Space." *Annals of Mathematics* 33 (1932): 643–648.

[50] Paley, R. E. A. C. and Wiener, N. *Fourier Transforms in the Complex Domain.* American Mathematical Society Colloquium Publications 19, 1934.

[51] Hörmander, L. *The Analysis of Linear Partial Differential Operators I.* Berlin: Springer, 1983, §7.7.

[52] Cauchy, A.-L. *Cours d'analyse de l'École royale polytechnique.* Paris, 1821.

[53] Einstein, A., Infeld, L., and Hoffmann, B. "The Gravitational Equations and the Problem of Motion." *Annals of Mathematics* 39 (1938): 65–100.

[54] Hamilton, W. R. "On a General Method in Dynamics." *Philosophical Transactions of the Royal Society of London* 124 (1834): 247–308. https://doi.org/10.1098/rstl.1834.0017

[55] McGucken, E. "Quantum Mechanics Derived from the McGucken Principle: A Unique, Simple, and Complete Derivation of Quantum Mechanics as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic — A Formal Derivation from First Geometric Principle dx₄/dt = ic to the Schrödinger and Dirac Equations, the Born Rule, Quantum Nonlocality, and the Full Feynman-Diagram Apparatus, with the Postulates of Quantum Mechanics Reduced to Theorems." April 26, 2026. https://elliotmcguckenphysics.com/2026/04/26/quantum-mechanics-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-quantum-mechanics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-d/

[56] McGucken, E. "A Unique, Simple, and Complete Derivation of General Relativity as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic." April 25, 2026. https://elliotmcguckenphysics.com/2026/04/25/a-unique-simple-and-complete-derivation-of-general-relativity-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic/

[57] Kac, M. "On Distributions of Certain Wiener Functionals." *Transactions of the American Mathematical Society* 65 (1949): 1–13.

[58] Halmos, P. R. *Measure Theory.* New York: Van Nostrand, 1950, Ch. XI.
