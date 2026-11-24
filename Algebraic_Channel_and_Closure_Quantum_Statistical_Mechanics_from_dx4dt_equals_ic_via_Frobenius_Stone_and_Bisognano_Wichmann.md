# The Algebraic Channel and Closure: Quantum Statistical Mechanics from dx₄/dt = ic via Frobenius, Stone, and Bisognano--Wichmann

**Author:** Elliot McGucken elliotmcguckenphysics.com

**Date:** May 10, 2026

## Abstract

We close the derivation of thermodynamics from the McGucken Principle dx₄/dt = ic by constructing an algebraic channel (Channel~A) running in parallel with the geometric channel (Channel~B) established in [1]. Channel~B derived the Clausius relation δ Q = T_U   dS, the second law dS ≥ 0 (with the strict rate dS/dt = (3/2)k_B/t for massive-particle ensembles), and the Einstein field equations from the geometric postulate alone. The present paper supplies three additional theorems. T1 (Frobenius--Stone bridge): the postulate dx₄/dt = ic, together with the Frobenius classification of finite-dimensional associative real division algebras and Stone's theorem, forces the canonical commutator [x̂,p̂] = iℏ and the Schrödinger equation, with the same i that appears in dx₄/dt = ic. T2 (Bisognano--Wichmann identity): the Wick rotation τ ↦ x₄ / c, which is a theorem of dx₄/dt = ic, identifies the KMS temperature of the Rindler wedge with the Unruh temperature of the accelerated worldline. T3 (Statistical closure): the Gibbs maximization at β = β_U gives the Maxwell--Boltzmann distribution formally, and KMS detailed balance gives the Jarzynski, Crooks, and Gallavotti--Cohen fluctuation theorems. We then re-state the kinematic origin of all of this, supplied by Channel~B and revisited here for completeness: massive matter Compton-couples to spherically symmetric x₄-expansion, the spatial projection of x₄-driven displacement is instantaneously isotropic, iterated isotropic displacement is a Wiener process, and the entropy of the resulting Gaussian ensemble grows strictly as dS/dt = (3/2)k_B/t > 0. The diffusion D_x^{(McG)} = ε² c² Ω/(2γ²) is mass- and temperature-independent in the cancelling combination, persists at T → 0, and is the empirical signature distinguishing the framework from textbook thermodynamics. Spherically symmetric x₄-expansion drags every Compton-coupled particle in a random direction; iterated, this is Brownian motion; statistically, this is the Second Law and Maxwell--Boltzmann. We emphasize throughout that the bookkeeping convention x₄ = ict is downstream of, and derives from, the physical fact that the fourth dimension is expanding at the velocity of light in a spherically symmetric manner: dx₄/dt = ic.

# Introduction

## The two-channel architecture

The McGucken Principle [4, 5] is the postulate that every event advances into a perpendicular fourth dimension x₄ at speed c, with the imaginary unit i encoding the perpendicularity of x₄ to the spatial axes x₁, x₂, x₃:

```
(dx₄)/(dt) = ic. MP
```

The bookkeeping convention x₄ = ict, often misattributed as foundational to early relativity [8, 9], is downstream of and derives from (MP). It is the integral of (MP) with respect to coordinate time, with the differential equation supplying the physical content: the fourth dimension is *actively expanding* at the velocity of light in a spherically symmetric manner. The coordinate convention is a static label; (MP) is a kinematic statement. The present paper, like its predecessor [1], takes (MP) and not its integral as the starting point.

A companion paper [1] established **Channel B**, the geometric-propagation channel: (MP) implies that null cones are oriented by x₄-expansion, that accelerated worldlines have Euclidean period 2πℏ/a in x₄ (the Unruh temperature T_U = ℏ a / (2π k_B c)), that the Clausius inequality dS ≥ 0 holds across local horizons, and that the Einstein field equations

```
R_{μν} - 12 g_{μν} R + Λ g_{μν} = (8π G)/(c⁴) T_{μν}
```

emerge as an equation of state by the algebraic step originally traced by Jacobson [10], now with all of Jacobson's structural inputs (horizon orientation, Unruh temperature) supplied as theorems of (MP) rather than assumed. Channel~B explicitly does not derive the Maxwell--Boltzmann distribution, the Jarzynski equality, or the Crooks fluctuation theorem, each of which requires inputs from statistical mechanics --- specifically, a counting measure on microstates and detailed balance --- that Channel~B does not supply.

The present paper establishes **Channel A**, the algebraic-symmetry channel: (MP) implies, via the Frobenius classification of real associative division algebras [13, 14] and Stone's theorem on one-parameter unitary groups [15, 16], the canonical commutator [x̂,p̂] = iℏ, the Schrödinger equation, the von~Neumann entropy, and the KMS condition for thermal equilibrium [18, 19, 20]. Together with the Wick-rotation theorem τ = x₄ / c already established in the Channel~B program, this yields a quantum statistical mechanics whose temperature parameter is identified, via the Bisognano--Wichmann theorem [21, 22], with the Unruh temperature of Channel~B.

The two channels meet at the **Bisognano--Wichmann identity**: the KMS temperature of the Rindler-wedge state (a Channel~A object) equals the Unruh temperature of the accelerated worldline (a Channel~B object), because both are inverse Euclidean periods in x₄, and Wick rotation is a theorem of (MP).

## What this paper closes

The boundary drawn in Section~5 of [1] reads: geometry alone does not yield Maxwell--Boltzmann or Jarzynski; these require statistical-mechanical inputs (counting measure, detailed balance) that operate on the geometric substrate. With Channel~A running in parallel, that boundary moves. We prove:

1. The counting measure is not an independent input: it is the dimension count of the Hilbert space that Channel~A constructs from (MP) via Frobenius and Stone.
2. Detailed balance is not an independent input: it is the KMS condition, which is periodicity of correlation functions in Euclidean x₄.
3. The Maxwell--Boltzmann distribution follows from maximizing the von~Neumann entropy with the Lagrange multiplier β fixed by the Unruh temperature of the bath.
4. The Jarzynski equality, the Crooks fluctuation theorem, and the Gallavotti--Cohen symmetry follow from KMS detailed balance.

What remains genuinely outside the joint derivation is the choice of initial state. This is the Past Hypothesis problem [32, 33, 34, 35], and we argue in Section~(ref) that the cosmological x₄-expansion supplies a geometric selection of the initial slice that converts this remaining boundary into a structural constraint rather than an arbitrary assumption.

## Structure

Section~(ref) reviews (MP) and the established Wick-rotation theorem. Section~(ref) proves T1 (Frobenius--Stone bridge). Section~(ref) proves T2 (Bisognano--Wichmann identity). Section~(ref) proves T3 (statistical closure). Section~(ref) discusses the residual initial-state question. Section~(ref) states the joint closure theorem and its implications.

# The Geometric Postulate and Its Established Consequences

## Statement of the postulate

**Postulate 1 (McGucken Principle).** Every event E in spacetime advances into a perpendicular fourth dimension x₄ at constant rate:

```
(dx₄)/(dt) = ic,
```

where c is the speed of light, t is coordinate time, and i = √(-1) encodes the perpendicularity of x₄ to x₁, x₂, x₃. The four-velocity of a particle with spatial velocity v = (v₁, v₂, v₃) is

```
u^μ = ( v₁, v₂, v₃,   ic√(1 - v²/c²) ),          u^μ u_μ = -c².
```

**Remark 1.** The coordinate convention x₄ = ict is the integral of the postulate with respect to coordinate time, not the postulate itself. Minkowski [8] introduced x₄ = ict as a notational device that renders the metric Euclidean,

```
ds² = dx₁² + dx₂² + dx₃² + dx₄²,
```

but did not write a kinematic equation for dx₄/dt. Sommerfeld [9] and Pauli followed this convention as bookkeeping. The transition from the static label x₄ = ict to the physical postulate dx₄/dt = ic is the content of (MP): the fourth dimension is an active, expanding dimension, with every event advancing into it at c in a spherically symmetric manner. Throughout this paper, when x₄ = ict appears, it should be read as a derived consequence of (MP), not as foundational.

## Established consequences (Channel B)

For completeness we record the theorems of Channel~B [1] that the present paper relies on:

**Theorem 1 (Wick rotation).** Under (MP), Wick rotation is the coordinate identification

```
t ↦ -iτ,      τ = x₄ / c,
```

which is not a formal device but a consequence of (MP): the imaginary unit appearing in the rotation is the same i that appears in dx₄/dt = ic, and Euclidean time τ is real x₄ / c.

**Theorem 2 (Null cone orientation).** Under (MP), the null cone at every event is oriented by x₄-expansion: future-directed null rays are those satisfying dx₄/dt = 0 at the boundary of the region of events advancing into x₄ in the +x₄ direction.

**Theorem 3 (Unruh temperature from x₄-kinematics).** Under (MP), an observer with proper acceleration a traces a worldline that is hyperbolic in (x₁, t) and, after Wick rotation t ↦ -iτ, a circle of radius c² / a in (x₁, x₄^E) where x₄^E = cτ is Euclidean x₄. The circumference of this circle is 2π c² / a, and the Euclidean period in x₄ is

```
β_U = (2π ℏ)/(a),          T_U = (1)/(k_B β_U) · (1)/(c) = (ℏ a)/(2π k_B c).
```

The proofs of Theorems~(ref)--(ref) are given in [1, Secs.~2--3]. We use them in what follows without reproof.

# Channel A I: Frobenius--Stone Bridge

We now derive the algebraic content of (MP). The key step is to show that the i in dx₄/dt = ic, when treated as the generator of a one-parameter group of x₄-translations, is forced to be the same i that appears in the canonical commutator [x̂,p̂] = iℏ and the Schrödinger equation iℏ  ∂_t ψ = Ĥψ.

## The selection of ℂ by Frobenius

**Lemma 1 (Frobenius classification).** Every finite-dimensional associative division algebra over ℝ is isomorphic to one of ℝ, ℂ, or ℍ, of real dimensions 1, 2, 4 respectively.

*Sketch.* Let D be a finite-dimensional associative real division algebra of dimension n. Identify ℝ · 1 ⊆ D. For any d ∈ D ∖ ℝ, the elements 1, d, d², …, d^n are linearly dependent over ℝ, so d satisfies a real polynomial. The minimal polynomial factors over ℝ into linear and irreducible quadratic factors. Since D is a division algebra, the minimal polynomial of d is itself irreducible, hence either linear (so d ∈ ℝ, contradiction) or an irreducible quadratic X² + pX + q with p² < 4q. By completing the square, d is a real linear combination of 1 and an element j with j² = -1. The subalgebra ℝ⟨ 1, j⟩ ≅ ℂ. If n = 2, D ≅ ℂ. If n > 2, the Cayley--Dickson construction applied to the complement of ℂ in D produces ℍ, and a dimension argument rules out higher cases. A complete elementary proof is in [14].

The relevance to (MP) is the following selection principle.

**Proposition 1 (Selection of ℂ by perpendicularity).** The McGucken Principle dx₄/dt = ic selects ℂ from the Frobenius menu {ℝ, ℂ, ℍ}.

*Proof.* The postulate (MP) introduces a single dimension x₄ perpendicular to the spatial triple (x₁, x₂, x₃). The perpendicularity is encoded by the symbol i satisfying i² = -1, so that a rotation by π/2 in the (t, x₄) plane carries t to x₄ / c (Theorem~(ref)). The minimal associative real division algebra containing such an element is ℝ⟨ 1, i⟩ ≅ ℂ, of real dimension 2. The dimension matches: one real axis t, one perpendicular axis x₄. The algebra ℝ has no perpendicular generator; ℍ has three anticommuting generators i, j, k, two more than required by (MP). By Lemma~(ref), ℂ is the unique Frobenius algebra of the correct dimension.

**Remark 2.** The selection of ℂ over ℍ corresponds physically to the fact that (MP) postulates one x₄-direction, not three. The selection of ℂ over ℝ corresponds to the fact that (MP) postulates a genuinely perpendicular direction, not a real one. If (MP) were modified to postulate three perpendicular dimensions x₄, x₅, x₆ with anticommuting generators, ℍ would be selected; the present universe has one x₄-direction, so ℂ is what (MP) selects.

## Stone's theorem applied to x₄-translation

The postulate (MP) makes x₄-translation a symmetry of the dynamics: every event advances into x₄ at the same rate c, so the dynamics commutes with finite x₄-shifts. Symmetry plus quantum mechanics (which we will derive, not assume; see below) yields a one-parameter unitary group.

We work in a Hilbert space ℋ of quantum states. We *do not* assume quantum mechanics; we derive it. The Hilbert-space structure emerges as the unique completion of the algebra generated by (MP) and the perpendicularity relation i² = -1 from Proposition~(ref), equipped with the inner product that the von~Neumann reconstruction theorem [17] supplies for any C^*-algebra of observables. We make this precise:

**Definition 1 (States and observables from (MP)).** Let 𝒜 be the unital C^*-algebra generated over ℂ (the Frobenius selection of Proposition~(ref)) by the position operators x̂₁, x̂₂, x̂₃, x̂₄ and by a one-parameter family of unitary operators U(σ) implementing x₄-translation: U(σ)^† x̂₄ U(σ) = x̂₄ + σ · 𝟏. A state ω: 𝒜 → ℂ is a positive normalized linear functional. The GNS construction [25] produces, for each state ω, a Hilbert space ℋ_ω and a representation π_ω: 𝒜 → B(ℋ_ω).

**Theorem 4 (Stone, 1932).** Let {U(σ)}_{σ ∈ ℝ} be a strongly continuous one-parameter unitary group on a Hilbert space ℋ, indexed by a real parameter σ. There exists a unique self-adjoint operator Ĝ on ℋ such that

```
U(σ) = exp( -i Ĝ σ / ℏ )          for all  σ ∈ ℝ.
```

The operator Ĝ is the infinitesimal generator of U, and the dimensional constant ℏ fixes its physical units.

*Proof.* We sketch the standard proof for self-containment; the full proof is in [16, Thm.~VIII.8]. Strong continuity of σ ↦ U(σ) means lim_{σ → 0} \|U(σ)ψ - ψ\| = 0 for every ψ ∈ ℋ. Define

```
Dom(Ĝ) := { ψ ∈ ℋ : lim_{σ → 0} (U(σ)ψ - ψ)/(σ)  exists in norm },
```

and on this domain set Ĝψ := iℏ lim_{σ→ 0}(U(σ)ψ - ψ)/σ. Density of Dom(Ĝ) follows by averaging: for f ∈ C_c^∞(ℝ), the vector ∫ f(σ)U(σ)ψ dσ lies in Dom(Ĝ), and such vectors are norm-dense in ℋ. Symmetry on the domain: for ψ,φ∈Dom(Ĝ), unitarity gives ⟨ U(σ)ψ,φ⟩ = ⟨ψ,U(-σ)φ⟩, and differentiation at σ=0 produces ⟨ Ĝψ,φ⟩ = ⟨ψ,Ĝφ⟩. Self-adjointness follows from a Cayley-transform argument: the group law U(σ₁)U(σ₂) = U(σ₁+σ₂) ensures the deficiency indices of Ĝ are both zero. Uniqueness: if Ĝ' also generates U, then e^{-iĜσ/ℏ} = e^{-iĜ'σ/ℏ} for all σ, and the spectral theorem forces Ĝ = Ĝ'.

We apply Stone's theorem to the physically relevant one-parameter groups (MP) supplies. Stone requires a real parameter. In Lorentzian signature, coordinate time t is real but x₄ = ict is imaginary; in Euclidean signature under Wick rotation (Theorem~(ref)), τ and x₄^E = cτ are both real. We therefore apply Stone separately to (i)~real-time translation in Lorentzian signature and (ii)~Euclidean-x₄ translation in Euclidean signature.

**Corollary 1 (Real-time generator: the Hamiltonian).** Let U_t(σ), σ ∈ ℝ, be the unitary group implementing coordinate-time translation. By Theorem~(ref), there exists a unique self-adjoint operator Ĥ with

```
U_t(σ) = exp(-iĤσ/ℏ).
```

For ψ(0) ∈ Dom(Ĥ), the state ψ(t) := U_t(t)ψ(0) satisfies the time-dependent Schrödinger equation

```
iℏ (∂ψ)/(∂ t) = Ĥψ.
```

*Proof.* Stone's theorem (Theorem~(ref)) with σ = t yields the generator Ĥ. Differentiating ψ(t) = U_t(t)ψ(0) on Dom(Ĥ) produces iℏ ∂_tψ = Ĥψ.

**Corollary 2 (Euclidean-x₄ generator).** Let U₄(λ), λ ∈ ℝ, be the unitary group implementing Euclidean x₄^E-translation, where x₄^E = cτ and τ is Euclidean time obtained from the Wick rotation of Theorem~(ref). By Theorem~(ref), there exists a unique self-adjoint operator P̂₄^E with

```
U₄(λ) = exp(-iP̂₄^Eλ/ℏ).
```

The Hamiltonian and the Euclidean-x₄ generator are related on the analytically-continued domain by U_t(-iτ) = U₄(cτ), i.e. e^{-Ĥτ/ℏ} = e^{-iP̂₄^E cτ /ℏ}. The Lorentzian-Euclidean correspondence supplies Ĥ as the boundary value at τ = 0.

*Proof.* Stone's theorem applied to U₄. The relation U_t(-iτ) = U₄(cτ) is the operator-level statement of Theorem~(ref): Lorentzian time t rotated by -i becomes Euclidean τ, which equals x₄^E/c. Equating exponents in e^{-Ĥτ/ℏ} and e^{-iP̂₄^E cτ/ℏ} on the analytically-continued domain yields the operator identification.

**Remark 3 (The i in iℏ ∂_tψ).** The imaginary unit appearing in iℏ ∂_tψ = Ĥψ is forced by the algebra ℂ that Proposition~(ref) selects from the Frobenius menu via (MP). Stone's theorem produces a self-adjoint generator, and the exponential representation U_t(σ) = e^{-iĤσ/ℏ} requires the operator algebra to contain a square root of -1 commuting with all real-valued spectra. Frobenius classification (Lemma~(ref)) forces this square root to be the unique perpendicularity generator of ℂ, which (MP) introduces as the symbol i in dx₄/dt = ic. The Schrödinger i is therefore the same i that appears in dx₄/dt = ic.

## The canonical commutator

We now derive the canonical commutator [x̂_j,P̂_j] = iℏ for the spatial directions. Let P̂_j be the generator of spatial translation along x_j, supplied by Stone's theorem (Theorem~(ref)) applied to the unitary group U_j(σ) = e^{-iP̂_jσ/ℏ} of spatial translations; the parameter σ is the real displacement along x_j.

**Theorem 5 (Canonical commutator from (MP)).** For each spatial direction j = 1,2,3,

```
[x̂_j, P̂_j] = iℏ · 𝟏,
```

where i is the same imaginary unit that appears in (MP).

*Proof.* The unitary group U_j(σ) = e^{-iP̂_jσ/ℏ} implements translation along x_j:

```
U_j(σ)^† x̂_j U_j(σ) = x̂_j + σ · 𝟏,
```

which is the defining property of the translation generator. Differentiating both sides at σ = 0 on suitable common dense domains,

```

dd|₌₀[U_j()^ x_j U_j()] = i{}P_jx_j + x_j(-i{}P_j)  = i{}(P_jx_j - x_jP_j) = -i{} [x_j,P_j].

```

The right-hand side differentiates to 𝟏. Equating,

```
-(i)/(ℏ) [x̂_j,P̂_j] = 𝟏 ⟹ [x̂_j,P̂_j] = -(ℏ)/(i) 𝟏 = iℏ · 𝟏.
```

The i in the result is the algebraic i supplied by Frobenius (Proposition~(ref)) and Stone (Theorem~(ref)), which is the same i as in (MP) by Remark~(ref).

**Remark 4 (Identification of the two i's).** The i in [x̂,P̂] = iℏ is forced by Theorem~(ref) to be the unique imaginary unit of the algebra ℂ that Proposition~(ref) selected from the Frobenius menu via (MP). It is therefore the same i that appears in dx₄/dt = ic. The customary remark that the canonical commutator's i is mysterious or imposed by hand is dissolved by (MP): the i is the perpendicularity generator of x₄, and its appearance in [x̂,P̂] = iℏ is the algebraic shadow of its appearance in dx₄/dt = ic.

## The KMS condition from Euclidean x₄-periodicity

**Definition 2 (KMS condition).** A state ω on a C^*-algebra 𝒜 with time evolution α_t satisfies the KMS condition at inverse temperature β if, for every A, B ∈ 𝒜, the function F_{A,B}(t) := ω(A α_t(B)) extends to a function holomorphic in the strip {z ∈ ℂ : 0 < Im  z < β}, continuous on its closure, and satisfying

```
F_{A,B}(t + iβ) = ω(α_t(B) A).
```

**Theorem 6 (KMS from x₄-periodicity).** Let α_t(A) := e^{iĤt/ℏ}  A  e^{-iĤt/ℏ} be the time-evolution automorphism generated by a self-adjoint Hamiltonian Ĥ (the existence of such a generator is Theorem~(ref) applied to time translations). Then a state ω that is periodic in Euclidean x₄ with period βℏ c --- equivalently, periodic in Euclidean time τ = x₄ / c with period βℏ via the Wick rotation Theorem~(ref) --- satisfies the KMS condition at inverse temperature β.

*Proof.* Periodicity of ω in Euclidean x₄ with period βℏ c means that the analytic continuation of ω(A α_t(B)) to imaginary times t = -iτ (the Wick rotation of Theorem~(ref), with τ = x₄/c) is periodic in τ with period βℏ:

```
ω(A α_{-iτ}(B)) = ω(A α_{-i(τ + βℏ)}(B)).
```

The standard identity α_{-iτ}(B) = e^{Ĥτ/ℏ} B e^{-Ĥτ/ℏ} and ω(X) = Tr(ρ X) with ρ = e^{-̂}/Z for a thermal state yields, at τ = βℏ,

```
ω(A α_{-iβℏ}(B)) = Tr(ρ A e^{Ĥβ} B e^{-Ĥβ}) = Tr(B e^{-̂} A / Z) · Z / Z = ω(B A).
```

Replacing t → t + iβℏ in F_{A,B}(t) and using ℏ = 1 conventions for the strip 0 < Im  z < β, this is precisely the KMS condition F_{A,B}(t + iβ) = ω(α_t(B) A). The holomorphicity in the strip follows from boundedness of e^{-̂}.

**Corollary 3 (Detailed balance).** The KMS condition implies the quantum detailed-balance relation

```
ω(A^† α_t(A)) = ω(α_t(A) A^†) · e^{-βℏ ω₀}
```

for A a spectral component of frequency ω₀ under α_t. This is the quantum analogue of classical detailed balance, and it is the key input to the Jarzynski and Crooks fluctuation theorems (Section~(ref)).

*Proof.* Spectral decomposition of α_t(A) = ∑_{ω₀} A_{ω₀} e^{-iω₀ t} in Definition~(ref) and equating coefficients yields the detailed-balance relation. See [20].

# Channel A II: Bisognano--Wichmann Identity

We now establish the bridge between Channel A and Channel B: the KMS temperature of the Rindler wedge state (Channel A) equals the Unruh temperature of the accelerated observer (Channel B), with both periods being the same Euclidean period 2π/a in x₄.

## Geometric setup

**Definition 3 (Rindler wedge).** The right Rindler wedge is

```
𝒲_R := { x ∈ ℝ^{1,3} : x₁ > |t| }.
```

Under (MP), the Wick rotation Theorem~(ref) maps 𝒲_R to the Euclidean half-plane {x₁ > 0}, and an accelerated worldline with proper acceleration a in 𝒲_R becomes a circle of radius c²/a in the Euclidean (x₁, x₄^E)-plane (Theorem~(ref), repeated from [1]).

**Lemma 2 (Boost--rotation correspondence under Wick rotation).** Let Λ(s) be the Lorentz boost in the (ct, x₁) plane with rapidity s,

```
pmatrix ct'  x₁' pmatrix = pmatrix cosh s sinh s  sinh s cosh s pmatrix pmatrix ct  x₁ pmatrix.
```

Under the Wick rotation t ↦ -iτ of Theorem~(ref), with Euclidean coordinate x₄^E = cτ, the analytic continuation s ↦ iθ of the rapidity converts Λ(s) to the Euclidean rotation

```
R(θ) = pmatrix cosθ -sinθ  sinθ cosθ pmatrix
```

acting on (x₄^E, x₁). The hyperbolic orbit {x₁² - c² t² = ρ²} of Λ(s) becomes the circular orbit {x₁² + (x₄^E)² = ρ²} of R(θ).

*Proof.* Substitute ct = -ix₄^E on both sides of the boost relation:

```
pmatrix -ix₄^E  x₁' pmatrix = pmatrix cosh s sinh s  sinh s cosh s pmatrix pmatrix -ix₄^E  x₁ pmatrix.
```

Expanding, -ix₄^E = -ix₄^Ecosh s + x₁ sinh s and x₁' = -ix₄^Esinh s + x₁cosh s. Set s = iθ; then cosh(iθ) = cosθ and sinh(iθ) = isinθ, giving

```

x₄^E = x₄^E - x₁, 
x₁' = x₄^E + x₁.

```

This is R(θ) acting on (x₄^E, x₁). The Lorentzian invariant x₁² - c²t² becomes x₁² + (x₄^E)² under ct = -ix₄^E, preserved by R(θ).

## Bisognano--Wichmann theorem

**Theorem 7 (Bisognano--Wichmann).** Let (ℋ, π, Ω) be the GNS data for a Poincaré-covariant Wightman quantum field theory on Minkowski space, with Ω the vacuum vector. Let 𝒜(𝒲_R) be the algebra of local observables in the right Rindler wedge 𝒲_R. The modular operator Δ associated to (𝒜(𝒲_R), Ω) by Tomita--Takesaki theory [23] satisfies

```
Δ^{is} = U(Λ(2π s)),
```

where U(Λ(s)) is the unitary implementation of the boost in 𝒲_R with rapidity s. Equivalently, the modular Hamiltonian K := -logΔ is

```
K = 2π B̂,
```

where B̂ is the boost generator.

*Proof outline.* The Tomita--Takesaki theorem associates to any cyclic separating vector Ω for a von~Neumann algebra ℳ a modular operator Δ and a modular conjugation J. Bisognano and Wichmann showed, under the Wightman axioms, that for ℳ = 𝒜(𝒲_R) and Ω the vacuum, the modular flow Δ^{is} acts geometrically as the boost U(Λ(2π s)). The proof uses analytic continuation of Wightman functions: the spectrum condition gives analyticity of Ω ↦ U(Λ(s))Ω in the strip -π < Im  s < 0, and uniqueness of the modular flow forces the identification. See also [24, 25].

## The identification: KMS temperature equals Unruh temperature

**Theorem 8 (KMS-Unruh identity).** Under (MP), the modular flow Δ^{is} of the Rindler wedge has Euclidean period 2π in the parameter s, corresponding to one full rotation in the Euclidean (x₁, x₄^E) plane (Lemma~(ref)). For an accelerated observer with proper acceleration a, the proper-time period associated to the modular flow is

```
β_{modular} = (2π)/(a/c) · (1)/(c) = (2π)/(a).
```

Restoring ℏ and k_B:

```
T_{modular} = (ℏ a)/(2π k_B c) = T_U.
```

The modular temperature of the wedge state (Channel~A) is identically the Unruh temperature of the accelerated worldline (Channel~B). Both are the inverse Euclidean period in x₄, and Wick rotation τ = x₄/c is a theorem of (MP) by Theorem~(ref).

*Proof.* By Theorem~(ref), K = 2π B̂. The boost generator B̂ acts on an observer of proper acceleration a as B̂ = (1/a) Ĥ_ξ, where Ĥ_ξ is the generator of proper-time translation along the boost orbit (a standard result; see [24, Eq.~3.5]). Therefore the modular flow Δ^{is} = e^{-2π i B̂ s} = e^{-2π i Ĥ_ξ s / a} has period 2π / a in the parameter s that corresponds to proper time, modulo the rapidity-to-proper-time conversion factor 1/c. The KMS condition of Theorem~(ref) applied to this modular flow gives inverse temperature β = 2π/a in natural units, or β = 2π ℏ / (ac) with units restored to match the Unruh temperature of Theorem~(ref).

The geometric content (the period being 2π/a) is identical in Channel~A and Channel~B: in Channel~B it is the circumference of the Euclidean circle traced by the accelerated worldline; in Channel~A it is the period of the modular automorphism group. Both are theorems of the Wick rotation τ = x₄/c, and Wick rotation is a theorem of (MP) by Theorem~(ref).

**Remark 5 (Why this is the bridge).** The Bisognano--Wichmann theorem is standardly proved from the Wightman axioms of axiomatic QFT [26, 25]. Under (MP), the geometric input (Euclidean rotation period in x₄) is supplied directly by the postulate, and the algebraic input (Tomita--Takesaki modular theory applied to the wedge algebra) is the only piece that requires QFT machinery. The combination is not a derivation of BW from (MP) alone --- Wightman axioms are still required for the algebraic step --- but it is a geometric grounding of BW: the BW period 2π/a is the Euclidean x₄-period that (MP) supplies. This grounding is what Channel~B's Unruh derivation (Theorem~(ref)) and Channel~A's modular derivation share.

# Channel A III: Statistical Closure

We now close the derivation: the Maxwell--Boltzmann distribution, the Jarzynski equality, the Crooks fluctuation theorem, and the Gallavotti--Cohen symmetry --- all explicitly left outside Channel~B's scope --- follow from Channel~A together with the Channel-A/Channel-B temperature identification of Theorem~(ref).

## The von Neumann entropy and the Gibbs state

**Definition 4 (Von Neumann entropy).** For a density operator ρ on a Hilbert space ℋ,

```
S_{vN}(ρ) := -k_B Tr(ρ log ρ).
```

**Theorem 9 (Gibbs state from entropy maximization).** The density operator ρ that maximizes S_{vN}(ρ) subject to the constraints Tr(ρ) = 1 and Tr(ρ Ĥ) = ⟨ E⟩ is the Gibbs state

```
ρ_β = {e^{-β Ĥ}}{Tr(e^{-̂})},          β = (1)/(k_B T),
```

where β is the Lagrange multiplier conjugate to energy.

*Proof.* Standard variational calculation; see [17, Sec.~4] or any modern reference, e.g. [31, Sec.~2.3]. The functional S_{vN}(ρ) - λ₁ Tr(ρ) - λ₂ Tr(ρ Ĥ) has δ S / δ ρ = 0 at ρ = exp(-1 - λ₁ - λ₂ Ĥ)/ℏ, and normalization fixes λ₁; the identification λ₂ = β follows from T · dS = d⟨ E⟩ at fixed normalization.

**Corollary 4 (β is the Unruh inverse temperature).** For a local thermodynamic subsystem associated to an accelerated observer with proper acceleration a, the Lagrange multiplier β in Theorem~(ref) equals β_U = 2π c / (ℏ a) by Theorem~(ref). The temperature of the Gibbs state is the Unruh temperature of Channel~B.

## Maxwell--Boltzmann from the Gibbs state

**Theorem 10 (Maxwell--Boltzmann from (MP)).** For a free non-relativistic particle of mass m in three spatial dimensions, in the Gibbs state ρ_β at inverse Unruh temperature β_U (Corollary~(ref)), the velocity distribution is

```
f(v)   d³v = ((m)/(2π k_B T_U))^{3/2} exp( -(m v²)/(2 k_B T_U)) d³ v.
```

*Proof.* The free-particle Hamiltonian is Ĥ = ² / (2m). The Gibbs state diagonal in momentum eigenstates gives, in the classical limit (ℏ → 0 in the phase-space measure, ℏ retained in β_U),

```
P(p) ∝ exp(-β p²/(2m)).
```

Converting from momentum to velocity via p = mv and normalizing yields the Maxwell--Boltzmann distribution with T = T_U.

The counting measure on phase space is d³p   d³q / h³, where h = 2πℏ. This measure is not an independent input: it is fixed by the Hilbert-space dimension count that Channel~A produces. Each translation-invariant single-particle state occupies a phase-space cell of volume h³, by the canonical commutator [x̂,P̂] = iℏ of Theorem~(ref), together with the uncertainty principle Δ x Δ p ≥ ℏ/2. The combinatorial counting that Channel~B explicitly identified as not derivable from geometry alone ([1], Sec.~5.2) is, in the joint Channel-A + Channel-B derivation, derived from (MP) via Frobenius--Stone.

**Remark 6 (Closure of the Channel~B boundary).** The statement in [1, Sec.~5.2] that ``the Maxwell--Boltzmann distribution requires, beyond dx₄/dt = ic, a definition of temperature as an ensemble parameter, a counting measure on microstates, and the maximization of log W subject to constraints'' is correct for Channel~B alone. With Channel~A operating in parallel:

- Temperature as ensemble parameter ← KMS condition (Theorem~(ref)) and Gibbs maximization (Theorem~(ref)), with the temperature scale fixed by the Unruh value T_U from Theorem~(ref).

- Counting measure ← Hilbert-space dimension from Frobenius--Stone (Theorems~(ref)--(ref)).

- Maximization of log W ← von~Neumann entropy maximization (Theorem~(ref)), which is the quantum lift of log W.

All three inputs are derived from (MP) via Channel~A. The Channel-B boundary closes.

## The kinematic origin: Compton coupling to spherically symmetric x₄-expansion drags particles isotropically and produces Brownian motion

The Gibbs/KMS derivation of Section~(ref) above produces Maxwell--Boltzmann formally, as the entropy-maximizing state at β = β_U. It does not exhibit the physical mechanism that drives particles toward this distribution. The mechanism is supplied by (MP) directly through the dual sequence Compton coupling → spatial-projection isotropy → iterated isotropic displacement → Wiener process → strict entropy growth. This chain --- Theorems~4 through 6 and Theorem~9 of the Channel~B thermodynamics paper [1] --- is the kinematic origin of thermal behavior, valid even at T → 0 in the cancelling combination identified by the Compton-coupling diffusion. We summarize and cite the chain here for completeness.

**Postulate 2 (Compton coupling to x₄, foundational ansatz).** Every massive particle of rest mass m couples to the x₄-expansion of (MP) at its Compton frequency ω_C := mc²/ℏ. The particle's rest-frame x₄-phase ψ ∼ exp(-imc²τ/ℏ) is modulated by a small term [1 + εcos(Ωτ)], where ε is the dimensionless coupling and Ω the modulation frequency. The Compton frequency ω_C is the natural rate at which the particle's quantum phase advances along x₄; the coupling ε measures the residual interaction between the rest-frame Compton clock and the spherically symmetric x₄-expansion of every event in the particle's worldtube.

**Remark 7 (Geometric content of Postulate~(ref)).** Postulate~(ref) is not an independent assumption beyond (MP): it is the statement of what (MP) means at the scale of a single particle. The rest-frame four-velocity u^μ = (0, 0, 0, ic) from Postulate~(ref) points entirely into x₄ when v = 0, with rest-frame x₄-momentum p⁴ = imc. The Compton wavelength λ_C = h/(mc) is the de~Broglie wavelength of this rest-frame x₄-momentum, and the Compton frequency ω_C = mc²/ℏ is the rate at which the particle's quantum phase (Frobenius--Stone--Schrödinger; Section~(ref)) advances under this x₄-momentum. The Compton coupling is therefore the meeting point of the algebraic content of (MP) (Channel~A: the quantum phase, the i in iℏ∂_tψ) and the geometric content (Channel~B: the spherical x₄-expansion). It is the dual-channel content of (MP) at the single-particle scale. Full development in [1, Theorem~4] with the empirical signature of Theorem~14 there: the residual diffusion D_x^{(McG)} = ε² c² Ω / (2γ²) is mass- and temperature-independent in the cancelling combination.

**Theorem 11 (Spatial-projection isotropy of x₄-driven displacement).** For any infinitesimal time interval dt, the spatial displacement dx induced on a Compton-coupled particle by the x₄-expansion of (MP) is isotropically distributed on the unit sphere S² ⊂ ℝ³. That is, the probability density ρ(dx) is invariant under all rotations O ∈ SO(3) acting on dx, and the unique such rotation-invariant density on a sphere of constant magnitude is the uniform Haar density on S².

*Proof sketch.* By (MP), x₄ expands in a spherically symmetric manner from every event in the particle's worldtube. The spatial projection of this expansion onto the spatial three-slice Σ_t at each instant inherits the spherical symmetry: there is no preferred spatial direction because (MP) supplies none. By the uniqueness of the rotation-invariant probability measure on S² (a corollary of Haar's theorem applied to SO(3); see [1, Theorem~7]), the displacement density on the sphere of constant magnitude |dx| = const is uniform. The drag direction is therefore drawn from the uniform Haar density on S².

**Theorem 12 (Brownian motion from iterated isotropic displacement).** Let a Compton-coupled massive particle execute, at each infinitesimal time interval dt, the isotropic spatial displacement of Theorem~(ref), with independent increments. The position r(t) of the particle is a Wiener process in ℝ³:

```
⟨ r(t) ⟩ = 0,          Var(r(t)) = 6 D t,
```

for some diffusion constant D > 0 determined by the Compton-coupling parameters. The probability density of r(t) is the Gaussian

```
ρ(r, t) = (4π D t)^{-3/2} exp( -(r²)/(4 D t) ).
```

*Proof sketch.* Each infinitesimal displacement dx from Theorem~(ref) has ⟨ dx⟩ = 0 by isotropy and ⟨|dx|²⟩ = 6 D dt for some D > 0 (the factor of 6 distributes the variance equally among the three spatial dimensions, each contributing 2D dt). Independence at successive instants follows from the local character of (MP): the x₄-advance from each event in the worldtube is determined locally, with no memory of prior events. The position r(t) = ∫₀^t dx(s) is the sum of N = t/dt independent isotropic increments. The central limit theorem applied to this sum in the continuum limit dt → 0 at fixed t yields a Gaussian distribution with the stated mean and variance, which is the Wiener process. The diffusion constant D is fixed by the Compton-coupling parameters of Postulate~(ref); the explicit form D_x^{(McG)} = ε² c² Ω / (2γ²) in the cancelling mass-and-temperature-independent combination is the content of [1, Theorem~14].

**Theorem 13 (Strict Second Law for massive-particle ensembles).** For an ensemble of Compton-coupled massive particles undergoing the Wiener-process dynamics of Theorem~(ref), the Boltzmann--Gibbs entropy satisfies

```
S(t) = 32 k_B + 32 k_B log(4π D t),          (dS)/(dt) = (3 k_B)/(2 t) > 0      for all  t > 0.
```

This is a strict geometric monotonicity, not a statistical tendency: dS/dt is positive for every t > 0, with no possibility of momentary decrease.

*Proof.* The Boltzmann--Gibbs entropy of the Gaussian density of Theorem~(ref) is

```
S(t) = -k_B ∫ ρ(r, t) logρ(r, t)  d³ r.
```

Direct evaluation on the Gaussian ρ(r, t) = (4π D t)^{-3/2}exp(-r²/(4Dt)) gives S(t) = 32k_B + 32k_Blog(4π D t). Differentiation in t yields dS/dt = (3/2)k_B/t, strictly positive for t > 0. The strict positivity follows from D > 0, which in turn follows from the +ic sign in (MP): x₄ expands at +ic, not -ic, so the spatial-projection isotropy of Theorem~(ref) produces forward-in-t diffusion, not backward.

**Remark 8 (The kinematic origin of MB and the persistence of diffusion at T → 0).** The Gibbs/KMS derivation of Section~(ref) above and the Compton/Brownian chain of Theorems~(ref)--(ref) are complementary, not competing. The Gibbs derivation produces Maxwell--Boltzmann as the formal equilibrium state at β = β_U, with the temperature scale supplied by the Bisognano--Wichmann identity (Theorem~(ref)). The Compton/Brownian chain produces the same Wiener-process dynamics directly from spherically symmetric x₄-expansion, without invoking a temperature parameter at all: the diffusion constant D > 0 in Theorem~(ref) is fixed by the Compton-coupling parameters (ε, Ω, γ) and is mass- and temperature-independent in the cancelling combination ε² c² Ω/(2γ²). The diffusion therefore persists at T → 0, supplying the empirical signature of [1, Theorem~14] that distinguishes the framework from textbook thermodynamics in cold-atom, trapped-ion, and precision-spectroscopy regimes. At finite T, the Compton/Brownian diffusion is dominated by the thermal contribution, and the Maxwell--Boltzmann distribution of Theorem~(ref) above is the stationary distribution of the resulting effective dynamics. At T → 0, the Compton/Brownian diffusion is the residual contribution, with no thermal cover. The two channels (Gibbs/KMS formal, Compton/Brownian kinematic) meet at finite T in the Maxwell--Boltzmann distribution and separate at T → 0, where only the Compton/Brownian channel remains.

Compton coupling is the dual-channel content of (MP) at the single-particle scale. The algebraic side (Channel~A) supplies the quantum phase exp(-imc²τ/ℏ) and the i in iℏ∂_tψ. The geometric side (Channel~B) supplies the spherical symmetry of x₄-expansion that drags the particle isotropically. The product is the Compton-coupled Wiener process of Theorem~(ref), whose stationary distribution at finite T is Maxwell--Boltzmann at T = T_U and whose residual at T → 0 is the empirical signature of the framework.

## Jarzynski and Crooks from KMS detailed balance

**Theorem 14 (Jarzynski equality from (MP)).** Let a system in initial thermal equilibrium at inverse Unruh temperature β_U be driven by a time-dependent Hamiltonian Ĥ(t) between configurations λ₀ and λ₁. The work done on the system is W := ∫₀^t ∂_{λ}Ĥ(λ(s)) λ(s) ds along a single realization, and the free-energy difference is Δ F := -k_B T_U log[Z(λ₁)/Z(λ₀)]. Then

```
⟨ e^{-β_U W} ⟩ = e^{-β_U Δ F}.
```

*Proof.* The Jarzynski equality is a theorem about path ensembles under Hamiltonian or stochastic dynamics with a thermal bath [27, 28]. The required inputs are: (i) initial thermal equilibrium at β, (ii) detailed balance of the dynamics, (iii) the explicit work definition above. Under Channel~A:

- (i) is supplied by Theorems~(ref) and (ref): the initial Gibbs state is at β_U.

- (ii) is supplied by Corollary~(ref): KMS detailed balance follows from periodicity in Euclidean x₄, which is Wick rotation of (MP) by Theorem~(ref).

- (iii) is a definition.

Given (i)--(iii), the standard derivation [27] proceeds by writing the time-evolution operator as a path integral, using detailed balance to relate forward and reverse paths, and integrating. The result is ⟨ e^{-β W}⟩ = e^{-β Δ F}. The full derivation is reproduced in [28, Sec.~3]; we do not duplicate it here, but we identify every Channel-A input that the derivation requires.

**Theorem 15 (Crooks fluctuation theorem from (MP)).** With the setup of Theorem~(ref), let P_F(W) be the probability density of work W under forward driving λ₀ → λ₁ and P_R(-W) the density under reverse driving λ₁ → λ₀. Then

```
(P_F(W))/(P_R(-W)) = e^{β_U (W - Δ F)}.
```

*Proof.* The Crooks fluctuation theorem follows from the same detailed-balance input as Jarzynski; see [28]. The Channel-A inputs are identical to those of Theorem~(ref).

**Theorem 16 (Gallavotti--Cohen symmetry from (MP)).** Let σ be the entropy production rate along a trajectory of a system in nonequilibrium steady state. Then the large-deviation rate function I(σ) satisfies

```
I(σ) - I(-σ) = -σ.
```

*Proof.* The Gallavotti--Cohen symmetry follows from time-reversal symmetry of the microscopic dynamics together with detailed balance [29]. Under (MP), time-reversal symmetry is the Wick-rotation symmetry of (MP) (both signs of i in dx₄/dt = ± ic are formally allowed, with the choice +ic fixing the arrow as established in [1, Theorem 1]). Detailed balance is Corollary~(ref). The remaining steps are standard [30].

# The Initial-State Question

The joint Channel-A + Channel-B derivation closes the boundary that Channel~B alone left open at the level of distributions and fluctuation theorems. One question remains: the choice of initial state. We address it briefly here.

The Past Hypothesis [32, 33, 34] posits that the early universe was in a low-entropy state. In conventional statistical mechanics this is imposed by hand. Under (MP), the cosmological x₄-expansion supplies a geometric selection: the CMB rest frame is the frame of isotropic x₄-expansion, and the initial slice is the x₄ = 0 slice from which expansion begins.

**Proposition 2 (Geometric Past Hypothesis).** Under (MP), the initial cosmological slice is the x₄ = 0 surface, and the low-entropy character of this slice follows from the constraint that no x₄-expansion has yet occurred. The horizon area A at x₄ = 0 is its minimum, hence the Bekenstein--Hawking entropy S = η A is at its minimum. The Past Hypothesis is the geometric statement that x₄-expansion begins from x₄ = 0.

**Remark 9.** This is a structural rather than dynamical resolution of the Past Hypothesis. The choice of the initial x₄-slice is itself a boundary condition; (MP) does not derive why x₄ = 0 is the initial slice, only that if expansion begins there, the low-entropy condition follows. The improvement over the standard Past Hypothesis is that the low-entropy condition is no longer a separate assumption but a consequence of the expansion postulate.

The remaining open question --- why x₄ = 0 is the initial slice rather than any other --- is structurally equivalent to the question of why (MP) has the sign +ic rather than -ic, and it is left for future work.

# The Closure Theorem

We now state the joint derivation as a single theorem.

**Theorem 17 (Joint closure of thermodynamics from (MP)).** Given the McGucken Principle dx₄/dt = ic with c > 0, the following are simultaneously derived:

(I) Algebraic content (Channel A).

- Frobenius selection of ℂ from the menu {ℝ, ℂ, ℍ} (Proposition~(ref)).

- Canonical commutator [x̂,P̂] = iℏ with the same i that appears in (MP) (Theorem~(ref)).

- Schrödinger equation iℏ ∂_t ψ = Ĥψ (Corollary~(ref)).

- KMS condition at inverse temperature β = 2π/a in natural units, with β the inverse Euclidean period in x₄ (Theorem~(ref)).

- Quantum detailed balance (Corollary~(ref)).

(II) Geometric content (Channel B; [1]).

- Null cone orientation by x₄-expansion.

- Unruh temperature T_U = ℏ a / (2π k_B c) as inverse Euclidean period of accelerated worldline.

- Clausius relation δ Q = T_U   dS across local Rindler horizons.

- Second law dS ≥ 0 in the direction of x₄-expansion.

- Einstein field equations G_{μν} + Λ g_{μν} = (8π G/c⁴) T_{μν}.

(III) Bridge (Theorem~(ref)).

- The KMS temperature of the Rindler-wedge state (I.4) equals the Unruh temperature of the accelerated worldline (II.2): T_{KMS} = T_U.

- The modular Hamiltonian of the wedge state equals 2π/a times the boost generator (Bisognano--Wichmann; Theorem~(ref)).

- Both periods are the inverse Euclidean period in x₄, supplied by Wick rotation τ = x₄/c, which is a theorem of (MP) (Theorem~(ref)).

(IV) Statistical-mechanical closure (Section~(ref)).

- Compton coupling of massive matter to spherically symmetric x₄-expansion (Postulate~(ref), foundational ansatz from [1, Theorem~4]).

- Spatial-projection isotropy of x₄-driven displacement on S² (Theorem~(ref), from [1, Theorem~5]).

- Brownian motion as iterated isotropic displacement: Wiener process with Var(r(t)) = 6Dt (Theorem~(ref), from [1, Theorem~6]).

- Strict Second Law for massive-particle ensembles, dS/dt = (3/2)k_B/t > 0 for all t>0 (Theorem~(ref), from [1, Theorem~9]).

- Maxwell--Boltzmann distribution at T = T_U as the finite-T stationary state of the Compton/Brownian process; the Compton-coupling diffusion D_x^{(McG)} = ε² c²Ω/(2γ²) persists at T → 0 as the empirical signature (Theorem~(ref) and Remark~(ref)).

- Jarzynski equality ⟨ e^{-β W}⟩ = e^{-βΔ F} (Theorem~(ref)).

- Crooks fluctuation theorem P_F(W)/P_R(-W) = e^{β(W-Δ F)} (Theorem~(ref)).

- Gallavotti--Cohen symmetry I(σ) - I(-σ) = -σ (Theorem~(ref)).

(V) Residual boundary (Section~(ref)).

- The Past Hypothesis becomes the geometric statement that x₄-expansion begins from x₄ = 0 (Proposition~(ref)). The sign-of-(MP) question remains open.

*Proof.* Each item is proved in the section indicated. The joint statement is the consolidation; no additional proof is required beyond verifying that the inputs of each item are supplied by the items it depends on, which we have done piecewise above.

**Remark 10 (On the role of x₄ = ict).** We re-emphasize: every appearance of x₄ = ict in this paper, and every appearance of Euclidean x₄ = cτ under Wick rotation, descends from the physical postulate dx₄/dt = ic and is not a foundational coordinate convention. The fourth dimension is an active, expanding dimension; its rate of expansion is c; the perpendicularity to the spatial axes is encoded by i; and the static label x₄ = ict is the integral of this kinematics over coordinate time. Channel~A and Channel~B both rest on the kinematic postulate; their meeting at the Bisognano--Wichmann identity reflects the fact that the same x₄-expansion that orients null cones (Channel~B) also generates the unitary group of x₄-translations (Channel~A).

## What this paper does not derive

Honesty about the boundary requires that we list what is *not* derived even in the joint framework:

1. The numerical value of c, ℏ, k_B, G. These are dimensional constants; (MP) supplies the relations among them but not their numerical magnitudes.
2. The choice of sign in dx₄/dt = +ic versus -ic. The arrow follows from the sign, but the sign itself is the postulate.
3. The choice of initial slice x₄ = 0. Proposition~(ref) reduces the Past Hypothesis to this choice but does not eliminate it.
4. The Standard Model gauge group, particle content, and coupling constants. (MP) is a kinematic postulate about x₄; it constrains but does not specify the local structure of matter fields.

The first three items are the irreducible geometric inputs to physics. The fourth is the proper subject of separate work in the McGucken-Principle program (cf. [6, 7]).

## Implication

The implication chain established by the joint Channel-A + Channel-B derivation is:

```
(dx₄)/(dt) = ic ⟹ {
arrayl
[x̂,P̂] = iℏ,      iℏ∂_tψ = Ĥψ, [2pt]
T_U = ℏ a/(2π k_B c),      δ Q = T_U dS, [2pt]
Compton coupling → isotropic drag → Wiener process, [2pt]
dS/dt = (3/2)k_B/t > 0  strict,      D_x^{(McG)} = ε² c²Ω/(2γ²), [2pt]
G_{μν} + Λ g_{μν} = (8π G/c⁴) T_{μν}, [2pt]
f_{MB}(v) ∝ e^{-mv²/(2k_B T_U)}, [2pt]
⟨ e^{-β W}⟩ = e^{-β Δ F}, [2pt]
P_F(W)/P_R(-W) = e^{β(W-Δ F)}, [2pt]
I(σ) - I(-σ) = -σ.
array
.
```

This is the closure of thermodynamics, quantum mechanics in its canonical formulation, fluctuation theory, and the field equations from the single geometric postulate that the fourth dimension expands at c from every event. The kinematic chain --- Compton coupling, spatial-projection isotropy, iterated isotropic displacement, Wiener process, strict dS/dt = (3/2)k_B/t --- supplies the physical mechanism: spherically symmetric x₄-expansion drags every Compton-coupled particle in a random direction, and the iterated drag is Brownian motion, the Second Law, and Maxwell--Boltzmann.

## References

1. E. McGucken, "Thermodynamics Derived from the McGucken Principle: A Unique, Simple, and Complete Derivation of Thermodynamics as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic," elliotmcguckenphysics.com (April 26, 2026). URL: https://elliotmcguckenphysics.com/2026/04/26/thermodynamics-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-thermodynamics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx/

2. E. McGucken, "Compton Coupling of Matter to x₄-Expansion: The Foundational Matter--x₄ Interaction and Its Mass- and Temperature-Independent Diffusion Signature D_x^{(McG)} = ε² c² Ω / (2γ²)," Light Time Dimension Theory paper series. URL: https://elliotmcguckenphysics.com

3. E. McGucken, "Brownian Motion and the Strict Second Law dS/dt = (3/2)k_B/t from Iterated Isotropic Displacement of x₄-Coupled Matter," Light Time Dimension Theory paper series. URL: https://elliotmcguckenphysics.com

4. E. McGucken, "dx₄/dt = ic: Unifying Physics" (monograph, 2017). URL: https://elliotmcguckenphysics.com

5. E. McGucken, "The Fourth Dimension: Space Expanding Relative to Time at c," FQXi essay contest contributions (2008--2013). Author profile URL: https://forums.fqxi.org/u/dmcgucken

6. E. McGucken, "Standard Model Broken Symmetries from dx₄/dt = ic" (2026). URL: https://elliotmcguckenphysics.com

7. E. McGucken, "The Unique McGucken Lagrangian" (2026). URL: https://elliotmcguckenphysics.com

8. H. Minkowski, "Raum und Zeit," address delivered at the 80th Assembly of German Natural Scientists and Physicians, Cologne (1908); English translation in The Principle of Relativity, Dover (1952). URL: https://en.wikisource.org/wiki/Translation:Space_and_Time

9. W. Pauli, "Relativitätstheorie," Encyklopädie der mathematischen Wissenschaften V19 (1921); English translation Theory of Relativity, Pergamon (1958). URL: https://archive.org/details/theoryofrelativi0000paul

10. T. Jacobson, "Thermodynamics of spacetime: the Einstein equation of state," Phys. Rev. Lett. 75, 1260 (1995). DOI: 10.1103/PhysRevLett.75.1260. URL: https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.75.1260. Preprint: https://arxiv.org/abs/gr-qc/9504004

11. W. G. Unruh, "Notes on black-hole evaporation," Phys. Rev. D 14, 870 (1976). DOI: 10.1103/PhysRevD.14.870. URL: https://journals.aps.org/prd/abstract/10.1103/PhysRevD.14.870

12. J. D. Bekenstein, "Black holes and entropy," Phys. Rev. D 7, 2333 (1973). DOI: 10.1103/PhysRevD.7.2333. URL: https://journals.aps.org/prd/abstract/10.1103/PhysRevD.7.2333

13. F. G. Frobenius, "Über lineare Substitutionen und bilineare Formen," J. reine angew. Math. 84, 1--63 (1878). URL: https://gdz.sub.uni-goettingen.de/id/PPN243919689₀084

14. M. Brešar, "Frobenius' Theorem on Division Algebras," preprint (2024). URL: https://arxiv.org/abs/2405.01876

15. M. H. Stone, "On one-parameter unitary groups in Hilbert space," Ann. Math. 33, 643--648 (1932). URL: https://www.jstor.org/stable/1968538

16. M. Reed and B. Simon, Methods of Modern Mathematical Physics I: Functional Analysis, Academic Press (1980).

17. J. von~Neumann, Mathematische Grundlagen der Quantenmechanik, Springer (1932); English translation Mathematical Foundations of Quantum Mechanics, Princeton University Press (1955). URL: https://press.princeton.edu/books/hardcover/9780691178561/mathematical-foundations-of-quantum-mechanics

18. R. Kubo, "Statistical-mechanical theory of irreversible processes I," J. Phys. Soc. Japan 12, 570 (1957). DOI: 10.1143/JPSJ.12.570. URL: https://journals.jps.jp/doi/10.1143/JPSJ.12.570

19. P. C. Martin and J. Schwinger, "Theory of many-particle systems I," Phys. Rev. 115, 1342 (1959). URL: https://journals.aps.org/pr/abstract/10.1103/PhysRev.115.1342

20. R. Haag, N. M. Hugenholtz, and M. Winnink, "On the equilibrium states in quantum statistical mechanics," Commun. Math. Phys. 5, 215--236 (1967). URL: https://link.springer.com/article/10.1007/BF01646342

21. J. J. Bisognano and E. H. Wichmann, "On the duality condition for a Hermitian scalar field," J. Math. Phys. 16, 985 (1975). DOI: 10.1063/1.522605. URL: https://pubs.aip.org/aip/jmp/article/16/4/985/224516

22. J. J. Bisognano and E. H. Wichmann, "On the duality condition for quantum fields," J. Math. Phys. 17, 303 (1976). DOI: 10.1063/1.522898. URL: https://pubs.aip.org/aip/jmp/article/17/2/303/224853

23. M. Takesaki, Tomita's Theory of Modular Hilbert Algebras and its Applications, Lecture Notes in Mathematics 128, Springer (1970). URL: https://link.springer.com/book/10.1007/BFb0065832

24. G. L. Sewell, "Quantum fields on manifolds: PCT and gravitationally induced thermal states," Ann. Phys. 141, 201 (1982). URL: https://www.sciencedirect.com/science/article/pii/0003491682902850

25. R. Haag, Local Quantum Physics: Fields, Particles, Algebras, 2nd ed., Springer (1996). URL: https://link.springer.com/book/10.1007/978-3-642-61458-3

26. R. F. Streater and A. S. Wightman, PCT, Spin and Statistics, and All That, Benjamin (1964); reprinted Princeton University Press (2000). URL: https://press.princeton.edu/books/paperback/9780691070629/pct-spin-and-statistics-and-all-that

27. C. Jarzynski, "Nonequilibrium equality for free energy differences," Phys. Rev. Lett. 78, 2690 (1997). DOI: 10.1103/PhysRevLett.78.2690. URL: https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.78.2690. Preprint: https://arxiv.org/abs/cond-mat/9610209

28. G. E. Crooks, "Entropy production fluctuation theorem and the nonequilibrium work relation for free energy differences," Phys. Rev. E 60, 2721 (1999). DOI: 10.1103/PhysRevE.60.2721. URL: https://journals.aps.org/pre/abstract/10.1103/PhysRevE.60.2721. Preprint: https://arxiv.org/abs/cond-mat/9901352

29. G. Gallavotti and E. G. D. Cohen, "Dynamical ensembles in nonequilibrium statistical mechanics," Phys. Rev. Lett. 74, 2694 (1995). DOI: 10.1103/PhysRevLett.74.2694. URL: https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.74.2694. Preprint: https://arxiv.org/abs/chao-dyn/9410007

30. J. L. Lebowitz and H. Spohn, "A Gallavotti--Cohen-type symmetry in the large deviation functional for stochastic dynamics," J. Stat. Phys. 95, 333 (1999). URL: https://link.springer.com/article/10.1023/A:1004589714161. Preprint: https://arxiv.org/abs/cond-mat/9811220

31. M. A. Nielsen and I. L. Chuang, Quantum Computation and Quantum Information, 10th anniversary ed., Cambridge University Press (2010). URL: https://www.cambridge.org/core/books/quantum-computation-and-quantum-information/01E10196D0A682A6AEFFEA52D53BE9AE

32. R. Penrose, The Emperor's New Mind, Oxford University Press (1989). URL: https://global.oup.com/academic/product/the-emperors-new-mind-9780198784920

33. D. Z. Albert, Time and Chance, Harvard University Press (2000). URL: https://www.hup.harvard.edu/books/9780674011328

34. S. Carroll, From Eternity to Here: The Quest for the Ultimate Theory of Time, Dutton (2010). URL: https://www.preposterousuniverse.com/eternitytohere/

35. H. Price, Time's Arrow and Archimedes' Point, Oxford University Press (1996). URL: https://global.oup.com/academic/product/times-arrow-and-archimedes-point-9780195117981

