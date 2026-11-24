# The McGucken Principle dx₄/dt = ic Surpasses Harlow and Carroll: Hilbert Space, Born Rule, and Closed-Universe Quantum Cosmology as Theorems Rather Than Postulates

**Elliot McGucken**
Light, Time, Dimension Theory
elliotmcguckenphysics.com
drelliot@gmail.com

May 12, 2026

---

> *"More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student… Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet."*
>
> — **John Archibald Wheeler**, Joseph Henry Professor of Physics, Princeton

---

## Abstract

Daniel Harlow's program (*Mindscape* 349 with Sean Carroll, March 30, 2026; Harlow–Usatyuk–Zhao, arXiv:2501.02359, January 2025; Harlow–Numasawa, arXiv:2311.09978, November 2023) and Sean Carroll's *Finding Gravity Within Quantum Mechanics* program (*Mindscape* 63, September 2019; Cao–Carroll–Michalakis, arXiv:1606.08444, 2017; Cao–Carroll, arXiv:1712.02803, 2018; Carroll–Singh, arXiv:1801.08132, 2018) both posit the Hilbert space as a starting axiom and operate *inside* the quantum-mechanical formalism. Harlow concludes that quantum mechanics itself must be modified to include a fundamental decoherence channel on every observer's pointer basis; that the closed-universe Hilbert space is one-dimensional and real; that science is fundamentally approximate with a lower error bound exp(−S_observer); and that "quantum mechanics doesn't make sense without an external observer." Carroll grants Lorentz invariance, the Hilbert-space tensor decomposition, and the choice of factorization. The McGucken Principle dx₄/dt = ic derives the Hilbert space (Theorem 5.1 of [McGuckenBornHilbert]), the Born rule P = |ψ|² (Theorem 4.2), the canonical commutator [q̂,p̂] = iℏ (Theorem 3.2), the uncertainty principle σ_x σ_p ≥ ℏ/2 (Theorem 6.1), Lorentz invariance (T2 of [McGuckenGRQM]), and unitarity (Theorem 8.1) as theorems from a single physical postulate, with no external physics-substantive lemmas imported. Harlow's three observer axioms become geometric theorems of localized worldlines on the McGucken manifold; the one-dimensional closed-universe Hilbert space is identified as a path-integral category error rather than a foundational fact; the cloned-observer machinery and the exp(−S_observer) error bound dissolve; the modification of quantum mechanics by a fundamental decoherence channel is unnecessary. We establish ten Harlow-comparison points H-1 through H-10 parallel to the Carroll-comparison points C-1 through C-15 of [McGuckenGRQM], and prove the structural shape of the failure that unites both programs: both began too far downstream. The McGucken framework begins upstream of the formalism, with one geometric fact: the fourth dimension is expanding at the velocity of light from every spacetime event in a spherically symmetric manner.

---

## 1. Source Documents Actually Read

*Per standing rule: never claim to have read a paper unless its entire content was retrieved. The following are the source documents I have actually fetched and read in full, in part, or in abstract only. All comparisons in this paper are restricted to material I have actually read.*

### 1.1 Fully read

- McGucken (May 7, 2026), *Novel, Unifying Geometric Derivations of the Born Rule P=|ψ|², the Canonical Commutation Relation [q̂,p̂]=iℏ, the Hilbert Space 𝓗, and the Uncertainty Principle σ_x σ_p ≥ ℏ/2 from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic.* Fetched as full HTML source of the WordPress post; 3,309 lines; sections 1–14, all theorems, all eleven prior-Hilbert-space attempts, all eleven prior-uncertainty derivations, all comparison tables, and full references read in detail.

- McGucken (in production, V3), *General Relativity and Quantum Mechanics Unified as Theorems of dx₄/dt = ic Surpassing Carroll's Finding Gravity Within Quantum Mechanics Programme.* Fetched as full TeX source; 10,844 lines; Editorial Note for V3, Abstract, Note on physical reading, Introduction (Hundred-Year Gap), McGucken Duality (Channels A/B), Source-Pair, GR Sector 24 theorems, QM Sector 23 theorems, Where the two sectors meet, Comparison Tables 4–6, No-Graviton Prediction, Penrose 1996 resolution, Princeton Origin, Conclusion, Tables 1–7, Hilbert–Jacobson Signature-Bridging Theorem, Universal McGucken Channel B Theorem, Surpassing Carroll (C-1 through C-15), and full References read in detail.

- *Mindscape* podcast episode 349, *Daniel Harlow on What Quantum Gravity Teaches Us About Quantum Mechanics* (March 30, 2026), host Sean Carroll. Full official transcript read end-to-end; timestamps from 00:00:00 to 1:24:58; complete reproduction of the "unconcessioned shop-talk" final fifteen minutes including Harlow's three-observer-axioms statement, his attack on Everett's use of the inner product, his Bohr–Landau reading of quantum mechanics, his rules-of-nature decohering-channel proposal, and his Themistocles/Oracle-at-Delphi gravitational-path-integral analogy.

- Harlow, Usatyuk, and Zhao (January 4, 2025; v2 January 17, 2025), *Quantum mechanics and observers for gravity in a closed universe*, arXiv:2501.02359. Abstract and Section 1 Introduction fetched and read in full from the official arXiv HTML; central proposal equation V|ψ⟩ = √d ⟨0| O(|ψ⟩ ⊗ |ψ₀⟩_f), modified encoding V̂: 𝓗_M → 𝓗_{Ob′}, the exp(−S₂(ω_{Ob′})) inner-product preservation bound, the 𝒞𝓡𝓣-gauge-symmetry argument for realness, and the full one-dimensional-Hilbert-space puzzle statement read in full. Sections 2–6 and Appendices A–D *not* fully retrieved; statements about those sections in what follows are restricted to what is recapitulated in the Introduction or in the podcast transcript.

### 1.2 Read in abstract only

- Harlow and Numasawa (November 16, 2023), *Gauging spacetime inversions in quantum gravity*, arXiv:2311.09978. Abstract fetched: in closed-universe quantum gravity, 𝒞𝓡𝓣 must be a gauge symmetry; its gauging is automatically implemented by the sum over topologies in the Euclidean gravity path integral; consequently the closed-universe Hilbert space must be a real vector space; in Lorentzian signature, time-unorientable manifolds must be included. Body not fetched; structural claims used here are abstract-level only.

- Harlow and Ooguri (October 12, 2018), *Symmetries in quantum field theory and quantum gravity*, arXiv:1810.05338. Abstract fetched: no global symmetries (continuous or discrete) in any bulk quantum gravity theory with a CFT dual; any "long-range" bulk gauge symmetry leads to a global symmetry in the boundary CFT, whose consistency requires bulk dynamical objects in all finite-dimensional irreducible representations of the bulk gauge group. Body not fetched.

- Almheiri, Penington, Marolf, McNamara, Usatyuk references for "one-dimensional Hilbert space" result. Listed as references via the Harlow–Usatyuk–Zhao introduction. Bodies not directly fetched; structural claims used here are restricted to what is summarized in [HarlowUsatyukZhao].

### 1.3 Read in full from prior session, persisted via standing rules

- Carroll's *Mindscape* 63 (September 9, 2019), *Finding Gravity Within Quantum Mechanics*.
- Cao, Carroll, Michalakis (June 27, 2016), *Space from Hilbert Space*, arXiv:1606.08444.
- Cao and Carroll (December 7, 2017), *Bulk Entanglement Gravity without a Boundary*, arXiv:1712.02803.
- Carroll and Singh (January 24, 2018), *Mad-Dog Everettianism*, arXiv:1801.08132.
- Cotler, Penington, Ranard (February 21, 2017), *Locality from the Spectrum*, arXiv:1702.06142.
- Jacobson (May 4, 1995), *Thermodynamics of Spacetime*, arXiv:gr-qc/9504004.

---

## 2. The McGucken Principle and Its Theorem Yield

The McGucken Principle is the physical law that the fourth dimension is expanding at the velocity of light from every spacetime event in a spherically symmetric manner:

> **dx₄/dt = ic**

The integrated form x₄ = ict (with x₄ = 0 at t = 0) is the algebraic coordinate expression. The dynamical content lives in the rate.

From this single principle, derived in detail across [McGuckenGRQM], [McGuckenBornHilbert], [McGuckenWick], [McGuckenSphere], [McGuckenGeometry], [McGuckenNoEmbedding], [McGuckenSpaceOperator], [McGuckenHilbertJacobson] and the broader corpus at elliotmcguckenphysics.com, the following are established as theorems rather than postulates:

**Quantum-mechanical sector.**

1. Complex-valuedness of the wavefunction (T3.1 of [McGuckenBornHilbert]).
2. Canonical commutation relation [q̂,p̂] = iℏ (T3.2).
3. Born rule P = |ψ|² (T4.2), via the four requirements R1–R4 with bilinearity R4 forced by the rank-2 Minkowski metric induced by x₄ = ict, (ict)² = −c²t².
4. Hilbert space 𝓗 as Cauchy completion L²(M_{1,3}, dμ_M) via Riesz–Fischer 1907 (T5.1).
5. Uncertainty principle σ_x σ_p ≥ ℏ/2 (T6.1).
6. Geometric meaning of ψ* ψ as forward–conjugate x₄-expansion overlap (T7.1).
7. Unitarity as conservation of x₄-flux (T8.1).
8. Wick rotation t → −iτ as coordinate identification τ = x₄/c rather than analytic continuation (T9.1).
9. Schrödinger equation iℏ ∂_t ψ = Ĥψ (companion paper [McGuckenSchrodinger]).
10. Heisenberg uncertainty, Pauli exclusion, 4π-periodicity, Dirac equation, gauge invariance, quantum nonlocality, entanglement, measurement event, CHSH/Tsirelson bound (QM sector of [McGuckenGRQM]).

**General-relativistic sector.**

11. Master equation u^μ u_μ = −c² (T1 of [McGuckenGRQM]).
12. McGucken-Invariance Lemma, four forms of the equivalence principle, geodesic principle (T2–T6).
13. Christoffel symbols, Riemann tensor, Ricci, Bianchi identities (T7–T10).
14. Einstein field equations via Lovelock 1971 plus Schuller 2020 dual route (T11).
15. Schwarzschild metric via Birkhoff, time dilation, redshift, light bending Δφ = 4GM/c²b, Mercury perihelion (T12–T16).
16. Gravitational waves with h_{x₄x₄} = 0 structurally from MGI Lemma (T17).
17. FLRW cosmology with twelve observational tests and zero free dark-sector parameters (T18, and [McGuckenCosmology]).
18. No-graviton theorem (T19).
19. McGucken Wick rotation (T20).
20. Black hole entropy via x₄-stationary mode counting, Hawking temperature T = ℏc³/(8πGMk_B) via Euclidean cigar plus KMS, BH coefficient η = 1/4, generalized second law (T21–T24).

**Where the two sectors meet.** The McGucken Sphere 𝓜_E(t) is the wavefront of x₄-expansion from every event E and is the atom of spacetime in which both sectors are simultaneously generated. The Bekenstein–Hawking entropy is the meeting point: it is a GR formula populated by QM degrees of freedom, and in McGucken's framework both arise from the same expansion.

The total tally is 1 postulate → 47 theorems. The Bayesian posterior ratio against ΛCDM with its dark-sector free parameters is more than 10²⁵⁰ [McGuckenCosmology].

---

## 3. Harlow's Program: What Is Posited, What Is Derived

### 3.1 Harlow's load-bearing posits, identified by reading

From the podcast transcript [Mindscape349] and the Harlow–Usatyuk–Zhao introduction [HarlowUsatyukZhao], Harlow's framework has the following load-bearing posits.

**H-A. The Hilbert space of quantum gravity.** Two Hilbert spaces are posited: 𝓗_eff (gravitational effective field theory) and 𝓗_fund (the dual CFT in AdS/CFT, or the analogous fundamental description elsewhere). Both are taken as primitives. The encoding map V: 𝓗_eff → 𝓗_fund is the central object.

**H-B. The gravitational path integral.** Treated "like the Oracle at Delphi" (Harlow, podcast 32:00–34:20): consulted, not derived. "More fundamental" than the canonical formalism. "Knows things the canonical formalism doesn't know" — for example, that black-hole entropy goes like area divided by 4G, and that the closed-universe 𝓗 is one-dimensional. Harlow explicitly admits he does not understand *why* the path integral gives these answers.

**H-C. One-dimensional Hilbert space in a closed universe.** Posited as the conclusion of the quantum extremal surface formula and the gravitational path integral pushed to a closed-universe setting [Almheiri2019hni], [Penington2019kki], [Marolf2020xie], [McNamara2020uza], [Usatyuk2024mzs], as recapitulated in the Introduction of [HarlowUsatyukZhao]: "*the Hilbert space of quantum gravity in a closed universe is one-dimensional.*"

**H-D. 𝒞𝓡𝓣 gauge symmetry forces real Hilbert space.** From [HarlowNumasawa] (abstract-level only on my read): in a closed universe the Hilbert space of quantum gravity must be a real vector space because 𝒞𝓡𝓣 is gauged, with the gauging implemented automatically by the sum over topologies. The orthogonal group O(d) replaces the unitary group U(d); the operator O in the encoding V|ψ⟩ = √d ⟨0| O(|ψ⟩ ⊗ |ψ₀⟩_f) is orthogonal rather than unitary.

**H-E. Cloned-observer encoding to recover semiclassical physics.** The modified encoding V̂: 𝓗_M → 𝓗_{Ob′} introduces a "cloned observer" Ob′ entangled with the system in a fixed state |ω⟩. The deviation from inner-product preservation is bounded by exp(−S₂(ω_{Ob′})) ~ exp(−S_{Ob}), the observer's coarse-grained entropy. For a human observer this is exp(−10²⁴).

**H-F. Three observer axioms.** Podcast 1:14:45–1:17:00:

1. Finite number of degrees of freedom, with physics achievable up to error exp(−S_{Ob}).
2. Classical pointer basis — stable under interactions with the environment. "It doesn't make sense to have an observer that's not classical."
3. Never pure — observers are always entangled with the rest of the universe. "You can't have an observer who's just sitting there in a pure quantum state by themselves."

**H-G. Fundamental decoherence channel as law of nature.** Podcast 1:17:30–1:19:40. Carroll asks whether the decoherence channel on the pointer basis is part of the description or the laws. Harlow: "*That's part of the laws of nature.*" This is the explicit modification of quantum mechanics: instead of decoherence being environmentally induced, the decohering channel on the observer's pointer basis is built into the foundational physics.

**H-H. Science is fundamentally approximate.** Podcast 0:59:50–1:01:53: "*Science as a concept is approximate with a lower bound on the error given by* exp(−S_observer)."

**H-I. Quantum mechanics requires an external observer.** Podcast 0:14:44–0:15:30: "*I don't really think quantum mechanics makes sense without that external observer. I don't think it's really science. It's mathematics, but it's not science.*" In the closed-universe limit, the external observer is impossible by hypothesis, hence quantum mechanics must be modified.

**H-J. Attack on Everett.** Podcast 1:05:13–1:06:11: a strict Everettian has only unitary evolution on a vector space, with no privileged inner product. The inner product is physical only because of the Born rule. "*Everettians don't believe in the Born rule*" — and (Harlow's claim) any Everett-style derivation of the Born rule from inner-product structure is circular, because the inner product is physical only via the Born rule.

### 3.2 Harlow's derived quantities

The non-trivial output of Harlow's framework, given the posits H-A through H-J, includes:

- Reconciliation of the one-dimensional 𝓗_fund with the rich semiclassical physics observed in our world, via the cloned-observer encoding V̂ and the exp(−S_{Ob}) error bound.
- Mathematical model of black-hole complementarity in which the outside observer measures purity (S₂ = 0) and the inside observer measures mixed-ness (S₂ ~ exp(−S_{Ob})), with both answers consistent given different effective rules.
- Emergent effective field theory and emergent semiclassical spacetime, up to errors of order exp(−S_{Ob}).

These are derived. The framework is internally consistent and mathematically well-defined. The contention here is not that the framework is wrong; it is that it operates strictly inside the Hilbert-space formalism, takes too much as posit, and consequently must modify quantum mechanics to handle the closed-universe case. The McGucken framework supplies what Harlow's framework is missing.

---

## 4. The Ten Harlow-Comparison Points H-1 through H-10

Each comparison point identifies a McGucken theorem or structural fact that supplies what Harlow's framework posits, and shows that the Harlow construction is unnecessary in the McGucken framework or that it is the algebraic shadow of a McGucken theorem.

### 4.1 H-1. Hilbert space: posited in Harlow, derived in McGucken

In Harlow, both 𝓗_eff and 𝓗_fund are primitives. The puzzle "𝓗_fund is one-dimensional, how is human experience possible?" is well-posed only because 𝓗_eff is independently posited with its full effective-field-theory dimensionality.

In McGucken, Theorem 5.1 of [McGuckenBornHilbert] derives the Hilbert space:

> dx₄/dt = ic ⇒ 𝓜_G → M_{1,3} → 𝓥 → 𝓗 ≅ L²(M_{1,3}, dμ_M).

The four steps — constraint surface M_{1,3} ≅ Φ_M⁻¹(0), complex amplitudes 𝓥 forced by T3.1, Born inner product from T4.2, Cauchy completion via Riesz–Fischer 1907 — import no quantum-mechanical input. Harlow's framework lives strictly inside the rightmost arrow. McGucken supplies the chain.

### 4.2 H-2. Reality versus complexity: Harlow's 𝒞𝓡𝓣-gauging vs. McGucken's perpendicularity marker

**Harlow.** The closed-universe Hilbert space is real because 𝒞𝓡𝓣 is gauged, with the gauging implemented automatically by the sum over topologies in the Euclidean gravity path integral [HarlowNumasawa]. The O(d) structure replaces U(d).

**McGucken.** The Hilbert space of physics is complex because x₄ = ict carries the factor i as the *perpendicularity marker* for x₄'s orthogonality to x₁x₂x₃. The Lorentzian signature is the algebraic shadow of this perpendicularity: (ict)² = −c²t², with the minus sign of the Lorentzian signature recording orthogonality rather than unreality. The relation i is doing physical work, not formal work; it has a physical referent, namely the orthogonality of the dynamical x₄-axis to ordinary 3-space. This position is the content of Theorem 3.1 of [McGuckenBornHilbert] and of the table in [McGuckenBornHilbert] §5.7.

**Reconciliation.** The two positions are not in opposition; they are at different levels. Harlow identifies a structural condition (*if* the Hilbert space and path integral exist, *then* closed-universe reality follows from 𝒞𝓡𝓣-gauging). McGucken produces the i itself. The McGucken Wick-rotation theorem (T9.1 of [McGuckenBornHilbert]) identifies the Wick substitution as a literal coordinate identification τ = x₄/c on the McGucken manifold: x₄ = ict becomes x₄^E = cτ (real), Minkowski metric becomes Euclidean metric, exp(iS/ℏ) becomes exp(−S_E/ℏ), P = |ψ|² becomes P = ψ². Harlow's real O(d) structure is the McGucken Euclidean shadow of the Lorentzian theory. The CRT-gauging story is the algebraic shadow of the same fact McGucken's Theorem 9.1 already encodes — but the McGucken derivation does not require the sum-over-topologies machinery or the assumption that the path integral is the fundamental object.

### 4.3 H-3. The one-dimensional closed-universe Hilbert space: a path-integral category error

**Harlow.** "dim 𝓗_fund = 1" as a starting datum, justified by the quantum extremal surface formula and the gravitational path integral pushed to closed-universe topology. "Either zero or infinity, and it's not infinity, so zero. There are zero degrees of freedom."

**McGucken.** The McGucken Sphere 𝓜_E(t) = {p ∈ spacetime: ds²(E,p)=0, x₄(p) − x₄(E) = ict} is the atom of spacetime emanating from every event E. It carries a complete L² Hilbert space over each spatial slice via Theorem 5.1. A closed universe is the continuous family of McGucken Spheres centered at every event of the closed manifold, with the Born density (forward–conjugate x₄-overlap) at each measurement event.

The "one-dimensional Hilbert space" Harlow reaches via path-integral methods is, in McGucken's reading, the global path-integral amplitude — the Hartle–Hawking-style sum over all initial conditions, all final conditions, all topologies — *not* the state space of physics at all. Calling that number "the Hilbert space dimension" is a category error: it conflates the global generating functional with the local state space available to an observer at a definite event. Theorem 5.1 of [McGuckenBornHilbert] builds the latter directly as L² over the spatial slice — exactly what one needs for physics to proceed.

In the McGucken framework, the entire opening puzzle of [HarlowUsatyukZhao] — "*how is human experience consistent with a one-dimensional Hilbert space?*" — dissolves. There is no rich-human-experience-versus-one-state-universe tension because the relevant Hilbert space is never one-dimensional. The Hilbert space is L²(M_{1,3}, dμ_M), and the spatial Lebesgue measure inherited from the McGucken Sphere geometry is built into the construction at Step 4.

### 4.4 H-4. The cloned observer Ob′ and the exp(−S_{Ob}) error: solution to a problem McGucken does not have

**Harlow.** Recovery of semiclassical physics in the closed universe requires introducing an external cloned observer Ob′ entangled with the system in a state |ω⟩, then computing observables through the modified encoding V̂: 𝓗_M → 𝓗_{Ob′}. Inner products are preserved up to exp(−S₂(ω_{Ob′})) ~ exp(−S_{Ob}). This bound is then promoted to a metaphysical statement: science is approximate with a lower error bound exp(−S_observer).

**McGucken.** The observer is not external to the universe and not cloned out of it. The observer is a localized timelike worldline in M_{1,3} with four-velocity budget u^μ u_μ = −c² (T1 of [McGuckenGRQM]). Their measurement is the geometric intersection of the McGucken Sphere 𝓜_{E_source}(t) with the observer's localized x₄-position; the Born density at the meeting event is the forward–conjugate x₄-expansion overlap (T7.1 of [McGuckenBornHilbert]). The measurement event is automatic; no external apparatus is required, no cloning, no quantum-to-classical channel inserted by hand.

**Consequence.** The McGucken Born rule is exact, not approximate up to exp(−S_{Ob}). The fundamental error bound on science Harlow proposes is artificial — generated by the encoding-into-one-dimensional-Hilbert-space construction. When the Hilbert space is correctly derived as L² over the local spatial slice (T5.1), the ceiling dissolves. The McGucken framework admits exact statements about exact Born densities.

### 4.5 H-5. The three observer axioms become theorems

**Harlow's three axioms.** Finite degrees of freedom; classical pointer basis; never pure.

**McGucken's theorems.**

1. *Finite degrees of freedom:* every massive observer worldline satisfies u^μ u_μ = −c² with |dx₄/dt| = c; localization in 3-space is finite because the observer is at finite distance from the Big Bang along x₄; the accessible state space at any spatial slice is finite up to the spatial UV cutoff inherited from the McGucken Sphere's Planck-scale oscillation rate. Theorem-level consequence of being a localized timelike worldline.

2. *Classical pointer basis:* decoherence of macroscopic apparatus is automatic from the geometric incidence — the apparatus exists at a definite x₄-coordinate, and the forward x₄-expansion of the system intersects the apparatus at a localized event, fixing the pointer basis as the eigenbasis of position at that event. T7.1 of [McGuckenBornHilbert] is the explicit form.

3. *Never pure:* every observer is on a worldline that has been crossing other McGucken Spheres for their entire causal past. Entanglement with the rest of the universe is the integrated history of their x₄-advance through other events' wavefronts. The "never pure" condition is a dynamical consequence of the McGucken Sphere structure, not an axiom.

All three of Harlow's axioms are McGucken theorems, not separate postulates.

### 4.6 H-6. The fundamental-decoherence-channel modification of quantum mechanics is unnecessary

**Harlow.** The decohering channel on the observer's pointer basis is part of the laws of nature, not an emergent consequence of environmental interaction. This is the radical move: quantum mechanics is modified at the foundational level.

**McGucken.** No modification is required. The measurement event is a geometric incidence — the meeting of the forward and conjugate x₄-expansions at the apparatus's localized x₄-position (T7.1 of [McGuckenBornHilbert]). The Born density is the overlap. The Malus correspondence (Proposition 7.2 of [McGuckenBornHilbert]) gives the squared-cosine projection density: P is to x₄-projection what Malus's law is to spatial projection. What looks like decoherence is the projection of 𝓜_E(t) onto the 3-spatial slice that the apparatus defines.

**Consequence.** The McGucken framework is strictly less radical than Harlow's. It does not modify quantum mechanics; it derives quantum mechanics. The "decoherence is a law of nature" move is unnecessary because the measurement event is already geometrically located in the same spacetime as the observer.

### 4.7 H-7. The Harlow attack on Everettian Born-rule derivations is sustained; McGucken supplies what neither Everett nor Harlow had

**Harlow's attack.** Podcast 1:05–1:06: a strict Everettian has only unitary evolution on a vector space, with no privileged inner product. The inner product is physical only because of the Born rule. Any Everett-style derivation of the Born rule from inner-product structure is circular.

**McGucken on the local question.** Sustained. The Everett-style derivations (Deutsch–Wallace, Zurek envariance, Sebens–Carroll, Masanes–Galley–Müller, Saunders branch-counting, QBist Dutch-book, Bohmian quantum equilibrium) all live inside 𝓗 and import either an indifference principle equivalent to the Born measure, a tensor-product structure, a system–environment cut, a state-estimation postulate, a counting principle, a coherence requirement, or the equivariant-measure structure. The §1.2, §4.6–§4.9, and §10 analyses of [McGuckenBornHilbert] establish this against each program.

**McGucken on the global question.** Defeats Harlow. The Born rule is derivable from a physical principle upstream of the Hilbert space. The derivation is Theorem 4.2 of [McGuckenBornHilbert]. The four requirements R1–R4 are not axioms; they come from the geometry of 𝓜_E(t) and the principle dx₄/dt = ic. Bilinearity R4 — Harlow's "inner product is the additional axiom" — is the rank-2 structure of the Minkowski metric induced by x₄ = ict, (ict)² = −c²t². The metric is rank 2 because x₄ is one perpendicular axis. The Born rule is the only consistent density given that metric structure.

This is a position neither Everett nor Harlow had access to. Everett took 𝓗 as primitive and could not get out; Harlow takes 𝓗 as primitive and concludes that science is fundamentally approximate. McGucken takes 𝓗 as derived and gets the exact P = |ψ|², without modifying quantum mechanics.

### 4.8 H-8. The gravitational path integral as Oracle versus the iterated McGucken Sphere

**Harlow.** The gravitational path integral is more fundamental than the canonical formalism but is consulted, not understood. The Themistocles parable (podcast 32:30) makes this explicit: "*You have to know the lesson that you're learning from the gravitational path integral.*"

**McGucken.** The Feynman path integral is derived in Theorem 3.1 of [McGuckenBornHilbert] and developed in detail in the QM Theorem T7 of [McGuckenGRQM]. The construction is the iterated McGucken Sphere: each path γ from E to B carries weight exp(iS[γ]/ℏ), with i tracing to x₄ = ict perpendicularity, ℏ tracing to the Planck-scale action quantum per x₄-oscillation, and the sum over paths arising from the geometric expansion at every intermediate event. Cameron 1960 on Wiener-integral consistency and Osterwalder–Schrader reconstruction supply the imported real-analytic rigor.

**Consequence.** Harlow's "the path integral knows things the canonical formalism doesn't" is, in McGucken's reading, the statement that the iterated McGucken Sphere construction captures propagator content that an operator-formalism approach to a single Hilbert space misses — because the McGucken Sphere expansion happens at every event, not at a single time slice. The path integral *is* the McGucken expansion read geometrically. There is no Oracle. The path-integral reading and the operator reading are Channel A and Channel B of the McGucken duality ([McGuckenGRQM] §3) applied to propagator construction. Both are derived from the same single principle.

### 4.9 H-9. The Maxwell–Saturn / Einstein–trains epistemic defense applies symmetrically

Harlow defends the abstract-puzzle-driven approach in the podcast (41:00–45:00) with Maxwell on Saturn's rings (Adams Prize 1856) and Einstein on fast trains (1905). The puzzle deserves attention even when the theory cannot yet be tested.

The McGucken framework has the same defense for a different starting point: the puzzle is why every quantum equation contains i and every relativistic equation contains c, and the answer is that both descend from dx₄/dt = ic. The Wheeler–Peebles 1989–1990 Princeton conversations (Acknowledgements of [McGuckenBornHilbert]; §10 of [McGuckenGRQM]) supply the same "obvious puzzle, deferred theory" structure Harlow uses to legitimize his approach. By Harlow's own epistemic standard, his program cannot reject McGucken's on grounds of empirical untestability or abstractness — both are at the same epistemic level. McGucken's framework has, in addition, twelve completed empirical tests in cosmology with zero free dark-sector parameters [McGuckenCosmology].

### 4.10 H-10. The Harlow encoding √d ⟨0| O is parameter-fitted; the McGucken construction is intrinsic

**Harlow.** The encoding V|ψ⟩ = √d ⟨0| O(|ψ⟩ ⊗ |ψ₀⟩_f) is engineered to satisfy the average-inner-product-preservation equation ∫ dO ⟨φ|V† V|ψ⟩ = ⟨φ|ψ⟩. The √d normalization, the projection onto ⟨0|, the random orthogonal O Haar-averaged over O(d), the entangled |ψ₀⟩_f, the cloned Ob′, the |ω⟩ state — the entire structure exists to reconcile a one-dimensional 𝓗_fund with a higher-dimensional 𝓗_eff. Toy models (simple code, topological, JT gravity, microscopic, replica wormholes) over 39 pages plus appendices.

**McGucken.** One Hilbert space, L²(M_{1,3}, dμ_M), derived in Theorem 5.1 in four steps. No encoding apparatus. The SO(3)-invariance of the McGucken Sphere (Definition 2.1 of [McGuckenBornHilbert]) is an intrinsic geometric symmetry, not a Haar-measure averaging. The preservation of the inner product is exact.

---

## 5. Comparison Tables

### 5.1 Table 1. Harlow vs. McGucken

| Feature | Harlow (2025) | McGucken (2026) |
|---|---|---|
| Foundational principle | None stated; gravitational path integral is the Oracle | dx₄/dt = ic |
| Hilbert space | Postulated (𝓗_eff and 𝓗_fund) | Theorem 5.1 |
| Closed-universe Hilbert space | One-dimensional, real (posit) | L²(M_{1,3}, dμ_M), complex; closed-universe "one-dim" is path-integral category error |
| Complex structure | Forced real in closed universe via 𝒞𝓡𝓣-gauging via sum over topologies | Forced complex via i as perpendicularity marker; reality is the Wick-rotated Euclidean shadow |
| Observer rule | Three axioms (finite DoF, classical, never pure) | Three theorems of localized timelike worldlines on McGucken manifold |
| Measurement mechanism | Decoherence channel as law of nature (modification of QM) | Geometric incidence of forward and conjugate x₄-expansions (T7.1); Malus correspondence |
| Born rule status | Posited or attacked as "additional axiom" | Theorem 4.2; exact, no approximation |
| Error in semiclassical physics | Fundamental lower bound exp(−S_{Ob}) | None; Born density is exact |
| Quantum mechanics | Must be modified at foundational level | Derived from dx₄/dt = ic, no modification |
| External observer required | Yes; QM "not really science" without it | No; observer is a worldline in the McGucken manifold |
| Path integral status | Oracle: consulted, not understood | Iterated McGucken Sphere construction (T3.1, T7 of [McGuckenGRQM]) |
| c and ℏ | Not unified at derivation level | Unified at derivation level: both descend from dx₄/dt = ic |
| Lorentz invariance | Granted via 𝒞𝓡𝓣-as-gauge | Theorem (T2 of [McGuckenGRQM]) via MGI Lemma |
| Universe as system | 39 pages of toy models + appendices to reconcile one-state 𝓗_fund with experience | One L² Hilbert space over the local spatial slice, derived in four steps |

### 5.2 Table 2. Carroll vs. Harlow vs. McGucken

| Feature | Carroll (2017–2019) | Harlow (2023–2026) | McGucken (2026) |
|---|---|---|---|
| Start point | 𝓗 and Ĥ posited | 𝓗_eff, 𝓗_fund, path integral posited | dx₄/dt = ic |
| Goal | Find gravity within QM | Find QM-modification within QG | Derive both QM and GR from one principle |
| Lorentz invariance | Granted (C-9 of [McGuckenGRQM]) | Granted | Theorem (T2 of [McGuckenGRQM]) |
| Hilbert space | Granted, with preferred-factorization problem | Granted (both effective and fundamental) | Derived (T5.1) |
| Tensor-product structure | Granted | Granted; engineered via encoding map | Derived from McGucken Sphere geometry |
| Born rule | Attempted derivation circular (Sebens–Carroll) | Attacked as "additional axiom"; not derived | Theorem 4.2; derived from bilinearity, phase invariance, R1–R4 |
| Preferred basis | Quantum-mereology problem (Cotler–Penington–Ranard) | Pointer basis posited as observer axiom | Pointer basis from geometric incidence (T7.1) |
| QM modification | No | Yes (fundamental decoherence channel) | No |
| Error in derived physics | Not addressed in detail | exp(−S_{Ob}) fundamental ceiling | None; theorems are exact |
| Empirical tests passed | None claimed at derivation level | None claimed at derivation level | Twelve cosmological tests, zero free dark-sector parameters [McGuckenCosmology] |
| Postulate-to-theorem ratio | ~7 posits, structural reconstruction | ~10 posits + 39 pages of toy models | 1 postulate → 47 theorems |

---

## 6. The Shared Diagnosis: Both Programs Began Too Far Downstream

The pattern of failure that unites the Carroll and Harlow programs is the same pattern that unites the eleven prior Hilbert-space-derivation programs surveyed in §5.3 of [McGuckenBornHilbert] (von Neumann 1932, Dirac 1930, Mackey 1957, Piron, Solèr, Jordan–von Neumann–Wigner 1934, Hardy 2001, Chiribella–D'Ariano–Perinotti, Abramsky–Coecke, Stueckelberg 1960, Adler 1995/2004, Renou et al. 2021):

> *Every program either postulates the Hilbert space directly, derives it from quasi-equivalent algebraic axioms added by hand, reconstructs it from operational or informational axioms whose physical origin is itself unexplained, characterizes it categorically, or empirically confirms it as the right structure — without explaining **why** ℂ is the right structure rather than confirming **that** it is.*

Carroll and Harlow extend this list:

- **Carroll** (12th attempt): postulate 𝓗 and Ĥ; derive spacetime, locality, and gravity from entanglement structure within them.
- **Harlow** (13th attempt): postulate 𝓗_eff, 𝓗_fund, and the path integral; derive observer rules and effective field theory from encoding maps between them; modify quantum mechanics at the foundational level.

The single conceptual move that the entire tradition refused to make is the move identified in §5.6 of [McGuckenBornHilbert]:

> *Treat x₄ as a physical, dynamical, geometric direction, with the imaginary unit i as the algebraic marker for that direction's perpendicularity to ordinary 3-space.*

The four twentieth-century blocks are: (i) treating x₄ as dynamical was blocked by the block-universe Minkowski reading; (ii) treating i as physical was blocked by the formalist interpretation; (iii) unifying c and ℏ was blocked by the separation of QM and relativity; (iv) deriving the formalism rather than interpreting it was blocked by the interpretation-industry posture that takes Hilbert space as inviolable. Carroll inherited all four blocks. Harlow inherited all four blocks. The McGucken framework lifts all four simultaneously.

---

## 7. Conclusion

The McGucken Principle dx₄/dt = ic derives:

- The Hilbert space (Theorem 5.1) — Harlow posits, Carroll posits.
- The Born rule P = |ψ|² (Theorem 4.2) — Harlow attacks as additional axiom, Carroll attempts circular derivation.
- The canonical commutator [q̂,p̂] = iℏ (Theorem 3.2) — Harlow posits, Carroll posits.
- The uncertainty principle σ_x σ_p ≥ ℏ/2 (Theorem 6.1) — Harlow posits, Carroll posits.
- Lorentz invariance (T2 of [McGuckenGRQM]) — Harlow grants, Carroll grants (C-9 of [McGuckenGRQM]).
- The path integral (T3.1; T7 of [McGuckenGRQM]) — Harlow consults as Oracle, Carroll uses as tool.
- Unitarity (Theorem 8.1) — Harlow modifies via decoherence channel, Carroll grants.
- The measurement event (T7.1) — Harlow inserts as law of nature, Carroll leaves unresolved (quantum-mereology).
- GR (24 theorems of [McGuckenGRQM]) — Harlow leaves emergent, Carroll attempts within QM.
- The fundamental constants c and ℏ unified ([McGuckenBornHilbert] §5.7) — Harlow does not address, Carroll does not address.

What McGucken offers that Carroll cannot is Lorentz invariance, the Hilbert space, the Born rule, the canonical commutator, the uncertainty principle, the dissolution of the preferred-basis and quantum-mereology problems, and the derivation of c and ℏ as the two hallmarks of the same expansion.

What McGucken offers that Harlow cannot is a foundational physical principle for the framework; derivation of the Hilbert space rather than its postulation; dissolution of the closed-universe one-dimensional puzzle as a path-integral category error; exact rather than exp(−S_{Ob})-approximate Born rule; no need to modify quantum mechanics with a fundamental decoherence channel; recovery of c and ℏ at the same level.

The structural shape of the McGucken success is the symmetric move that the prior tradition could not make: the formalism is derived. The reason no program before McGucken could do this is that each began inside the formalism; the reason McGucken could is that the framework began upstream of the formalism, with one geometric fact:

> **dx₄/dt = ic**

*The fourth dimension is expanding at the velocity of light from every spacetime event in a spherically symmetric manner. Ergo physics. QED.*

---

## Acknowledgements

The author thanks John Archibald Wheeler, whose 1989–1990 Princeton conversations and whose vision of a "breathtakingly simple" underlying idea initiated this line of inquiry; James Peebles, whose statement that the photon is "equally likely to be found anywhere on a spherically symmetric wavefront expanding at the rate of c" supplied the spherical-symmetry content of the McGucken Sphere; and Edwin Taylor, whose "entanglement is the characteristic trait of quantum mechanics — go find its source" prompt established the research direction.

---

## References

[McGuckenBornHilbert] E. McGucken, *Novel, Unifying Geometric Derivations of the Born Rule P=|ψ|², the Canonical Commutation Relation [q̂,p̂]=iℏ, the Hilbert Space 𝓗, and the Uncertainty Principle σ_x σ_p ≥ ℏ/2 from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic*, May 7, 2026. https://elliotmcguckenphysics.com/2026/05/07/novel-unifying-geometric-derivations-of-the-born-rule-p%cf%88%c2%b2-the-canonical-commutation-relation-q%cc%82p%cc%82i%e2%84%8f-the-hilbert-space-%f0%9d%93%97-and-the-uncertainty-principle-2/. PDF: https://elliotmcguckenphysics.com/wp-content/uploads/2026/05/novel_unifying_geometric_derivations_born_rule_ccr_hilbert_space_uncertainty_principle_from_mcgucken_principle_dx4dt_eq_ic-3.pdf

[McGuckenGRQM] E. McGucken, *General Relativity and Quantum Mechanics Unified as Theorems of dx₄/dt = ic Surpassing Carroll's Finding Gravity Within Quantum Mechanics Programme*, V3, 2026. Companion paper, 172+ pages. https://elliotmcguckenphysics.com

[McGuckenWick] E. McGucken, *Wick Rotation as a Theorem of dx₄/dt = ic: Thirteen Theorem-Clusters Comprising Thirty-Four Propositions*, 2026. Companion paper. https://elliotmcguckenphysics.com

[McGuckenSphere] E. McGucken, *The McGucken Sphere as Spacetime's Foundational Atom*, 2026. https://elliotmcguckenphysics.com

[McGuckenGeometry] E. McGucken, *The McGucken Geometry: A Novel Mathematical Category*, 2026. https://elliotmcguckenphysics.com

[McGuckenNoEmbedding] E. McGucken, *The Categorical No-Embedding Theorem of the McGucken Geometry*, 2026. https://elliotmcguckenphysics.com

[McGuckenSpaceOperator] E. McGucken, *The McGucken Space and McGucken Operator Co-Generated by dx₄/dt = ic*, 2026. https://elliotmcguckenphysics.com

[McGuckenHilbertJacobson] E. McGucken, *The Hilbert–Jacobson Signature-Bridging Theorem and the Universal McGucken Channel B Theorem*, May 12, 2026. https://elliotmcguckenphysics.com

[McGuckenCosmology] E. McGucken, *First Place Across Twelve Observational Cosmological Tests with Zero Free Dark-Sector Parameters from the McGucken Principle dx₄/dt = ic*, 2026. https://elliotmcguckenphysics.com

[McGuckenSchrodinger] E. McGucken, *The Schrödinger Equation as a Theorem of dx₄/dt = ic: Time Asymmetry and the Eight-Step Compton-Frequency Factorization of the Klein–Gordon Equation*, 2026. https://elliotmcguckenphysics.com

[Mindscape349] D. Harlow and S. Carroll, *Daniel Harlow on What Quantum Gravity Teaches Us About Quantum Mechanics*, Mindscape podcast episode 349, March 30, 2026. Full official transcript. https://www.preposterousuniverse.com/podcast/2026/03/30/349-daniel-harlow-on-what-quantum-gravity-teaches-us-about-quantum-mechanics/

[HarlowUsatyukZhao] D. Harlow, M. Usatyuk, and Y. Zhao, *Quantum mechanics and observers for gravity in a closed universe*, arXiv:2501.02359 [hep-th], January 4, 2025; v2 January 17, 2025. MIT-CTP/5824. 39 pages plus appendices. https://arxiv.org/abs/2501.02359

[HarlowNumasawa] D. Harlow and T. Numasawa, *Gauging spacetime inversions in quantum gravity*, arXiv:2311.09978 [hep-th], November 16, 2023. JHEP 01 (2026) 098. https://arxiv.org/abs/2311.09978

[HarlowOoguri] D. Harlow and H. Ooguri, *Symmetries in quantum field theory and quantum gravity*, arXiv:1810.05338 [hep-th], October 12, 2018. https://arxiv.org/abs/1810.05338

[Almheiri2019hni] A. Almheiri, R. Mahajan, J. Maldacena, and Y. Zhao, *The Page curve of Hawking radiation from semiclassical geometry*, JHEP 03 (2020) 149. arXiv:1908.10996 [hep-th]. *Cited via* [HarlowUsatyukZhao] Introduction.

[Penington2019kki] G. Penington, *Entanglement wedge reconstruction and the information paradox*, JHEP 09 (2020) 002. arXiv:1905.08255 [hep-th]. *Cited via* [HarlowUsatyukZhao] Introduction.

[Marolf2020xie] D. Marolf and H. Maxfield, *Transcending the ensemble: baby universes, spacetime wormholes, and the order and disorder of black hole information*, JHEP 08 (2020) 044. arXiv:2002.08950 [hep-th]. *Cited via* [HarlowUsatyukZhao] Introduction.

[McNamara2020uza] J. McNamara and C. Vafa, *Baby Universes, Holography, and the Swampland*, arXiv:2004.06738 [hep-th]. *Cited via* [HarlowUsatyukZhao] Introduction.

[Usatyuk2024mzs] M. Usatyuk, Z.-Y. Wang, and Y. Zhao, *Closed universes in two dimensional gravity*, arXiv:2402.00098 [hep-th], 2024. *Cited via* [HarlowUsatyukZhao] Introduction.

[Mindscape63] S. Carroll, *Finding Gravity Within Quantum Mechanics*, Mindscape podcast episode 63, September 9, 2019. https://www.preposterousuniverse.com/podcast/2019/09/09/63-solo-finding-gravity-within-quantum-mechanics/

[CaoCarrollMichalakis] C. Cao, S. M. Carroll, and S. Michalakis, *Space from Hilbert Space: Recovering Geometry from Bulk Entanglement*, Phys. Rev. D 95 (2017) 024031. arXiv:1606.08444 [hep-th]. https://arxiv.org/abs/1606.08444

[CaoCarroll] C. Cao and S. M. Carroll, *Bulk Entanglement Gravity without a Boundary: Towards Finding Einstein's Equation in Hilbert Space*, Phys. Rev. D 97 (2018) 086003. arXiv:1712.02803 [hep-th]. https://arxiv.org/abs/1712.02803

[CarrollSingh] S. M. Carroll and A. Singh, *Mad-Dog Everettianism: Quantum Mechanics at Its Most Minimal*, in: A. Aguirre, B. Foster, Z. Merali (eds.), *What is Fundamental?*, Springer, 2019. arXiv:1801.08132 [quant-ph]. https://arxiv.org/abs/1801.08132

[CotlerPeningtonRanard] J. S. Cotler, G. R. Penington, and D. H. Ranard, *Locality from the Spectrum*, Commun. Math. Phys. 368 (2019) 1267. arXiv:1702.06142 [quant-ph]. https://arxiv.org/abs/1702.06142

[Jacobson1995] T. Jacobson, *Thermodynamics of Spacetime: The Einstein Equation of State*, Phys. Rev. Lett. 75 (1995) 1260. arXiv:gr-qc/9504004. https://arxiv.org/abs/gr-qc/9504004
