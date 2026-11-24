# A Formal Proof of Quantum Mechanics' Nonlocality from Relativity's Spacetime Metric

### The Null Hypersurface as a Nonlocal Manifold, with Double-Slit Interference and Bell Violation as Operational Signatures

**Elliot McGucken**
drelliot@gmail.com
elliotmcguckenphysics.com

*May 2026*

---

## Abstract

We prove that the Minkowski metric *alone*, without any empirical or quantum-mechanical input, formally forces the conclusion that the future light cone 𝒞⁺(P) of any emission event P is a nonlocal manifold: every point on the cone is at zero proper-length separation from P along its connecting null geodesic, every two points on the same null generator are at zero proper-length separation from each other, and the pullback of the Minkowski metric to the null hypersurface is degenerate along its generator directions. This is the *geometric nonlocality* of the null hypersurface, and it is a theorem of differential geometry that requires no experimental input. We then exhibit *two independent operational signatures* of this prior geometric fact, both established experimentally long before Bell's 1964 theorem. The first is double-slit interference, established by Young in 1801 and refined by Davisson–Germer (1927), Jönsson (1961), and Tonomura (1989): the observed two-slit pattern P₁₂(x) violates the classical additivity law P₁₂(x) = w₁P₁(x) + w₂P₂(x) that any positive measure on local trajectories must satisfy, and we prove that this violation is forced by the geometric nonlocality of the cone 𝒞⁺(P) supporting the propagation. The second is the Bell–CHSH violation on common-origin pairs, established empirically in the 2015 loophole-free experiments, which we prove is similarly forced by the same prior geometric fact. The novel content of the paper is the explicit identification of the null hypersurface as a nonlocal manifold by virtue of its own metric structure, with both double-slit nonadditivity and Bell–CHSH violation as operational shadows of one geometric source. We prove this in seven lemmas and five theorems. We then strengthen these results under the McGucken Principle dx₄/dt = ic: the null hypersurface is the locus of x₄-coincident events emanating isotropically from P, and the geometric nonlocality, double-slit nonadditivity, and Bell violation are recovered as theorems of the active expansion. A long historical analysis traces the question of why the inferential step was never formalized despite the fact that the double-slit operational nonlocality has been visible since Young's 1801 paper, the relativistic geometric nonlocality has been visible since Minkowski's 1908 lecture (with Poincaré's 1905–06 imaginary-time formulation as direct precursor), and Penrose's twistor program made null structure primitive in 1967. The argument's pieces have been on the table for over two centuries; the present contribution is to assemble them into the formal statement that quantum nonlocality is the operational shadow of geometric nonlocality of the light cone.

---

## 1. Introduction

The standard textbook treatment of relativistic spacetime and quantum mechanics presents two distinct facts joined by a single bridge. The first is that Minkowski spacetime has a Lorentzian metric of signature (−,+,+,+), with a light cone separating timelike from spacelike directions and serving as the boundary of causal influence. The second is that quantum mechanics violates the Bell–CHSH inequality on suitably prepared common-origin pairs, with the violation |S| = 2√2 exceeding the local-hidden-variable bound |S| ≤ 2. The bridge is the no-signaling theorem, which guarantees that the Bell violation cannot be used to transmit classical information across spacelike separation, so the two theories formally coexist. In this picture, the cone is a constraint on *what is permitted* (no signals beyond it) and the Bell violation is a separate fact about *what is observed* (correlations stronger than classical), and the two are reconciled by the no-signaling theorem rather than derived from a common source.

The present paper rejects this picture in favor of a stronger one. We claim that the Minkowski metric, taken seriously as a piece of differential geometry, *already encodes* the nonlocality that Bell violation reveals. The null hypersurface 𝒞⁺(P) is the locus where the metric's distance function Δs² takes the value zero, and every point on it is at zero proper-length separation from the apex P along the null geodesic that connects them. From the photon's own affine parameterization, every null generator is a single point smeared along an extended spacetime trajectory. Two photons emitted in opposite directions from P, reaching detectors a billion light-years apart, are each on a worldline of zero intrinsic length, and the cone they trace together is a single null hypersurface that the metric treats as a degenerate locus. This is geometric nonlocality, and it is a theorem of the metric alone.

Given this prior geometric fact, the Bell violation is no longer a separate empirical mystery to be reconciled with relativity through the no-signaling theorem. It is the operational shadow of the geometric nonlocality. The cone is already nonlocal as geometry; any field theory living on it inherits joint statistics that no positive measure on a classical sample space can reproduce. The CHSH bound is the bound for theories whose correlations factor through a single classical probability space; the cone's geometric nonlocality is what makes such a factorization structurally impossible for fields on 𝒞⁺(P). The empirical |S| > 2 is then a confirmation of the prior geometric fact, not a separate input.

The argument is novel in its formal statement but not in its raw geometric content: the null structure of the cone has been known since Minkowski [1], the twistor program has built on it since Penrose 1967 [11], the Newman–Penrose tetrad has used it since 1962 [14], and Wheeler's delayed-choice gedanken stages exactly this scenario [21]. The historical question is therefore not why the geometric facts are true — they have been part of the standard apparatus for half a century or more — but *why the inferential step from geometric nonlocality to quantum nonlocality was never formalized*. Section 3 traces this question in detail.

The paper proceeds as follows. Section 2 sets the mathematical preliminaries. Section 3 gives the full historical analysis. Section 4 proves Theorem 1, the geometric nonlocality of the null hypersurface. Section 5 establishes Theorem 2, the spacelike-separation lemma. Section 6 proves Theorem 3, the empirical corollary. Section 7 strengthens the result under the McGucken Principle dx₄/dt = ic. Section 8 discusses i, c, no-signaling, the Wick rotation, and the photon's view from null infinity. Section 9 concludes.

## 2. Mathematical Preliminaries

**Notation.** We work in Minkowski spacetime 𝕄 = (ℝ⁴, η) with metric signature (−,+,+,+). Coordinates (t, x¹, x², x³), spatial three-vector **x** = (x¹, x², x³), r = |**x**|. Units c = 1 unless explicitly restored.

**Definition 2.1 (Lorentzian interval).** For two events A = (t_A, **x**_A) and B = (t_B, **x**_B), set Δt = t_B − t_A, Δ**x** = **x**_B − **x**_A, and Δs²(A, B) = −Δt² + |Δ**x**|². The pair (A, B) is *timelike* if Δs² < 0, *null* if Δs² = 0 with A ≠ B, *spacelike* if Δs² > 0.

**Definition 2.2 (Future light cone, null generator, wavefront).** For P ∈ 𝕄:

- 𝒞⁺(P) = {Q ∈ 𝕄 : Δs²(P, Q) = 0, t_Q ≥ t_P} — future light cone
- 𝒩_n̂(P) = {P + λ(1, n̂) : λ ≥ 0}, n̂ ∈ S² — null generator
- W_t(P) = {Q ∈ 𝒞⁺(P) : t_Q = t_P + t}, t > 0 — wavefront

Then 𝒞⁺(P) = ⋃_{n̂ ∈ S²} 𝒩_n̂(P) = {P} ∪ ⋃_{t > 0} W_t(P).

**Definition 2.3 (Proper length).** For a smooth curve γ: [a, b] → 𝕄, γ(λ) = (t(λ), **x**(λ)), the squared interval element is η(γ̇, γ̇) = −ṫ² + |**ẋ**|² where ˙ = d/dλ. The *proper length* is L(γ) = ∫_a^b √|η(γ̇, γ̇)| dλ. A curve is *null* if η(γ̇, γ̇) = 0 everywhere.

**Definition 2.4 (Affine parameter).** An affine parameter λ along a null geodesic γ is one in which the tangent γ̇ is parallel-transported: ∇_{γ̇} γ̇ = 0. Affine parameters are determined up to affine transformation λ ↦ aλ + b.

*Remark.* Proper time, dτ = √(−η(γ̇, γ̇)) dλ for timelike curves, vanishes identically on null curves. There is no proper time along a null worldline; only the affine parameter is intrinsic, and only up to scaling.

## 3. Historical Background and the Question of Why

### 3.1 Young's 1801 Double-Slit: Operational Nonlocality before Quantum Mechanics

The operational nonlocality of common-origin propagation was demonstrated by Thomas Young in his 1801 Bakerian Lecture to the Royal Society [33]. Young directed sunlight through a small aperture and then through two further closely-spaced apertures, observed the resulting fringes on a screen, and inferred the wave nature of light from the bright-and-dark band pattern. The quantitative content of his result is that the intensity distribution I₁₂(x) on the screen, with both apertures open, is *not* the sum of the two single-aperture distributions I₁(x), I₂(x) weighted by any positive coefficients:

> I₁₂(x) ≠ w₁I₁(x) + w₂I₂(x)  for any w₁, w₂ ≥ 0.

There exist positions x on the screen at which both I₁(x) > 0 and I₂(x) > 0, but I₁₂(x) = 0 — the screen receives light when either aperture is open alone, but receives no light when both are open. This is the destructive-interference minimum, and it is, mathematically, the failure of probability additivity for a positive measure. No positive measure ρ on a sample space Λ of single-aperture trajectories can produce I₁₂(x) = 0 at a point where both I_j(x) > 0.

What Young proved in 1801 is, in modern language, that the intensity-pattern statistics of light propagating from a common-origin source through two paths do not admit a local-trajectory factorization. The conclusion he drew was the wave nature of light. The conclusion we will draw in Theorem 6.7 below is that this same failure is forced by the geometric nonlocality of the cone 𝒞⁺(P) supporting the propagation. Young could not have drawn this conclusion in 1801 because the spacetime structure was a century away from being formulated.

What is most striking historically is that the operational signature of cone-nonlocality was therefore established *before* the geometric source. For 107 years between Young 1801 and Minkowski 1908, the empirical fact of double-slit interference was in plain view, but no spacetime geometry existed to anchor it. For another 117 years between Minkowski 1908 and the present, both pieces have been in plain view and the inferential step has not been made.

### 3.2 Davisson–Germer, Jönsson, Tonomura: The Same Pattern for Matter

The double-slit nonadditivity is not a peculiarity of light. Davisson and Germer [34] in 1927 demonstrated the same phenomenon for electrons scattering off a nickel crystal: the intensity pattern of scattered electrons shows interference fringes incompatible with any positive measure on classical trajectories. Jönsson [35] performed the canonical electron double-slit experiment in 1961, with a literal pair of slits, observing exactly the Young pattern for electrons. Tonomura and collaborators [36] in 1989 confirmed the most striking feature: the interference pattern builds up one electron at a time, with each individual electron arriving at a single localized point on the detector, but the accumulated distribution showing fringes. The single-electron Young experiment closes the loophole that the pattern might be a many-particle wave artifact: each individual electron's arrival position carries the cone-nonlocality, because the distribution from which it is drawn is the non-classical pattern.

The Davisson–Germer, Jönsson, and Tonomura results extend Young's 1801 conclusion to massive particles, with the same mathematical form: additivity fails. The conclusion that the propagation supports nonlocality is therefore established for both massless and massive single-particle propagation, independent of any common-origin pair experiment. The cone 𝒞⁺(P) of the emission event is the locus on which the propagation lives in both cases; the geometric nonlocality of the cone (Theorem 4.4) is the structural source.

### 3.3 Poincaré 1905–06 and the Imaginary-Time Coordinate

The geometric structure of Minkowski spacetime has a direct precursor in Poincaré's 1905–06 work on the Lorentz transformations. In his paper *Sur la dynamique de l'électron* [38], presented to the Académie des Sciences in July 1905 and published in 1906, Poincaré introduced the imaginary-time coordinate ict as the fourth coordinate of a four-dimensional manifold, with the Lorentz transformations becoming rotations in this four-dimensional space. He recognized that the quadratic form x² + y² + z² − c²t² is invariant under Lorentz transformations, and that with x₄ = ict this form becomes the Euclidean four-dimensional norm x₁² + x₂² + x₃² + x₄².

Poincaré thus had the geometric structure on which Minkowski's light cone three years later would be built. The factor i in x₄ = ict that Poincaré introduced is, on the present reading, the same i that the McGucken Principle places at the foundation: the quarter-turn between the spatial three and x₄. Poincaré did not, however, derive the nonlocal-manifold structure of the null hypersurface; the imaginary-time coordinate is in his treatment a calculational convenience for making the Lorentz transformations look like rotations, not a physical statement about an active expansion. Minkowski's 1908 lecture [1] promoted Poincaré's coordinate into a geometric statement about spacetime, but neither Poincaré nor Minkowski took the further step of identifying the cone's null-degeneracy as nonlocality.

### 3.4 The Geometric Facts Are Old

The null structure of the Minkowski light cone was identified in Minkowski's 1908 Köln lecture [1], with the four-dimensional spacetime formulation of special relativity, the light cone as boundary of the causal region, and imaginary coordinate x₄ = ict to render the metric Euclidean in form. The fact that Δs² = 0 on the cone is part of the original formulation, and the fact that the proper length of any null geodesic is zero was understood immediately as a consequence of the metric's signature. None of the geometric content of Theorem 4.4 below is new to the present paper; what is new is the identification of these facts as *constituting nonlocality* of the null hypersurface as a manifold.

The proper-length-zero feature of null geodesics has been folklore in relativity for more than a century. It is taught as "photons do not age" or "the photon's clock reads zero between emission and absorption." The pedagogical point is made in passing, as a curiosity of the metric, rather than as a structural claim about the cone's geometry. The textbooks (Misner, Thorne, Wheeler [24]; Wald [25]; Hawking and Ellis [26]) all state the fact and move on; none formalize it as a nonlocality theorem.

### 3.5 Penrose's Twistor Program: The Closest Approach

Penrose's 1967 *Twistor algebra* [11] took the most radical step toward treating null structure as primitive. The program treats null geodesics, not spacetime points, as basic, and constructs spacetime points as projective lines in twistor space ℙ𝕋. A point x ∈ 𝕄 corresponds to a projective line ℂℙ¹ ≅ S², geometrically the celestial sphere of null rays through x — precisely the wavefront W_t(P) as P → x along a worldline.

Penrose's program comes very close to the geometric statement of nonlocality we make here. The celestial sphere is, in the twistor picture, a single object: a ℂℙ¹ fibre in ℙ𝕋, parameterizing the null rays through a single spacetime point. Penrose develops the formalism in full in *Spinors and Space-Time* [12, 13]. The null hypersurface is, in this formalism, not derived from but constitutive of spacetime structure.

Three things prevented Penrose from formalizing the present argument. *First*, the twistor program is fundamentally a *reformulation* of spacetime geometry in a manifestly conformal setting; its motivation is technical (a natural home for massless field equations, helicity, scattering amplitudes). The nonlocality of the null structure is the starting point rather than the conclusion. Penrose does not formalize the inferential step from "null structure is primitive" to "the light cone is a nonlocal manifold," because the program assumes the former at the outset. The present argument moves in the other direction: from the metric (not assumed primitive) to the nonlocality of the null structure (as a derived theorem).

*Second*, the twistor program treats null geometry as *static*: a geometric reorganization in which the celestial sphere is a fixed mathematical object, not an actively expanding wavefront. Under the McGucken Principle dx₄/dt = ic, by contrast, the wavefront is the instantaneous front of an isotropic x₄-expansion. This active reading is foreign to twistor theory.

*Third*, and most importantly: Penrose did not connect the geometric structure of twistor space to the quantum-mechanical nonlocality revealed by Bell. In *The Emperor's New Mind* [18], *Shadows of the Mind* [19], and at length in chapters 23 and 29 of *The Road to Reality* [20], Penrose discusses EPR, Bell, Hardy's theorem, and the role of the light cone. He coins the term "quanglement" for the resulting structure and devotes serious attention to the tension between Lorentz invariance and nonlocal correlation. But the proof of nonlocality he cites is always Bell's theorem with its experimental confirmation, not a derivation from the geometric structure of the cone. The light-cone diagrams on which his EPR discussions are drawn are pedagogical staging, not formal premises. Twistor space, where the null structure is primitive, is presented as a candidate home for quantum nonlocality but never as its source.

The closest Penrose comes is in *Spinors and Space-Time*, Vol. 2 [13], discussing asymptotic structure and null infinity ℐ⁺, ℐ⁻, where the conformal compactification makes the asymptotic null structure into the basic invariant of asymptotically flat spacetimes. Here the null hypersurface is treated as a manifold in its own right, with its own conformal geometry. But the discussion stays at the level of classical relativity; the connection to quantum nonlocality is not formalized.

### 3.6 The Newman–Penrose Tetrad and the Bondi–Sachs Tradition

Newman and Penrose [14] introduced the null-tetrad approach to general relativity in 1962, with a basis of four null vectors (ℓᵃ, nᵃ, mᵃ, m̄ᵃ) replacing the orthonormal frame. The null tetrad is adapted to the natural causal structure and is well-suited to problems in which radiation, characteristic surfaces, or null infinity play a central role. The peeling theorem for gravitational radiation [15] and the Bondi–Sachs analysis of mass loss at null infinity [16, 17] are developed in this formalism.

These developments use null geometry as the natural language of the physics, but they remain firmly within classical general relativity. The null hypersurface is treated as a characteristic surface of the wave equation; its role is to organize the asymptotic structure of radiation. The formalism does not concern itself with quantum nonlocality, and the geometric nonlocality of the cone is not formalized as a structural conclusion.

### 3.7 Wheeler's Delayed-Choice Experiments

Wheeler proposed in 1978 [21] a class of gedanken and laboratory experiments in which the choice of measurement at the detector is made *after* the photon has, in any classical sense, passed the point at which the path is fixed. The cosmic-lens variant uses a single photon emitted from a quasar that reaches the detector along two widely separated null geodesics, with the choice made at the detector.

Wheeler's framing is closer in spirit to the present paper than Penrose's: the photon pair (or the single photon along two null paths) shares a common emission event, and the geometry of the common origin is treated as the underwriter of the observed correlations. Wheeler's "great smoky dragon" metaphor in the 1983 elaboration [22] suggests that the photon's worldline is not fully classical even in the bulk of its trajectory — and the null character of the worldline is part of what makes this so.

But Wheeler did not formalize. His delayed-choice argument is a thought experiment dramatizing the role of measurement choice, not a derivation of nonlocality from the metric. The argument is heuristic and inspirational; the formal step from "the photon's worldline is null" to "the cone is a nonlocal manifold" is not made. Wheeler's deeper instinct — "it from bit" [23], that spacetime structure encodes quantum content — is in the right direction but is not a proof.

### 3.8 The EPR-Bell Tradition

The operational tradition running from Einstein–Podolsky–Rosen [2] through Bohm [3] to Bell [4] and CHSH [5] located nonlocality in the joint statistics of detectors, not in the geometry that hosts them. EPR's argument is about assignment of definite values to non-commuting observables; Bell's argument is about the impossibility of local hidden-variable factorizations; CHSH's argument is the operational bound. None of these involve the metric of spacetime explicitly. Detectors A and B are placed at spacelike separation, but the spacelike separation is treated as a kinematic constraint (no superluminal signal) rather than as a structural feature of the geometry organizing the experiment.

The experimental tradition — Aspect 1982 [7], Hensen 2015 [8], Giustina 2015 [9], Shalm 2015 [10] — inherits this operational framing. The 2015 loophole-free experiments closed the detection-efficiency, freedom-of-choice, and locality loopholes, establishing |S| > 2 at confidence levels exceeding 10⁻⁷. But the empirical conclusion is always stated as "local hidden variables are ruled out," not as "the cone hosting the experiment is geometrically nonlocal." The latter formulation requires the geometric reading we make here.

### 3.9 The No-Signaling Theorem as Binding Constraint

The dominant framing of the relativity-QM relationship treats the no-signaling theorem as the binding constraint. The argument runs: Bell-violating correlations are nonlocal; the Minkowski metric forbids superluminal signaling; the no-signaling theorem reconciles the two by ensuring Bell correlations cannot transmit classical information. In this picture, the cone is the boundary of *permitted* influence, the Bell violation is *permitted* nonlocality, and the no-signaling theorem is the legal document that authorizes their coexistence.

The cost of this framing is that the cone and the Bell violation are treated as logically independent facts joined by a third fact (no-signaling). The deeper reading, in which the cone's geometric nonlocality is the *source* of the Bell violation, is foreclosed by the framing itself. Once the cone is treated as a constraint and the Bell violation as a separate empirical fact, the cone is no longer seen as a nonlocal manifold.

### 3.10 Why Nobody Did This

The historical record exhibits a striking asymmetry. The two operational signatures of cone-nonlocality have been visible since the early nineteenth century (double-slit) and the mid-twentieth (Bell–CHSH). The geometric structure underwriting them has been visible since the early twentieth century (Poincaré's x₄ = ict, Minkowski's light cone, the null-tetrad formalism, Penrose's twistor program). The inferential step joining the two has not been made in over two centuries of access to the first piece and over a century of access to the second. The question is why.

**The 107-year gap, 1801–1908.** Young's double-slit experiment of 1801 established the operational nonlocality of common-origin propagation. From 1801 until Minkowski's 1908 lecture, the empirical signature was in plain view. The reason no one connected the dots in this period is simply that there was no spacetime geometry to connect them to: the Lorentz transformations were derived in 1905 (Einstein), the imaginary time coordinate in 1905–06 (Poincaré), and the light cone in 1908 (Minkowski). Pre-1908 physics had no structural object that could play the role of "locus of geometric nonlocality."

**The 13-year gap, 1908–1921.** Minkowski's 1908 Köln lecture gave the world the light cone, with the explicit statement that x₄ = ict and that the null hypersurface is the locus of zero spacetime interval. By 1921, the null structure had been fully integrated into the theoretical apparatus of physics. In this period the inferential step was not made because (a) the double-slit nonlocality was not yet read as nonlocality — it was read as the wave nature of light, then after 1924–26 as the wave-particle duality of quantum mechanics, but the language of "nonlocality" is later; and (b) the spacetime structure was just settling into place, with foundational priorities (general covariance, gravitation, cosmology) occupying the relativists.

**The 41-year gap, 1921–1962.** By the 1920s and 30s, quantum mechanics had matured; by 1935 EPR had identified what they called the incompleteness of quantum mechanics. In all this period the inferential step from cone-geometry to quantum nonlocality was not made. The reason is the disciplinary split. Quantum mechanics was developed by Bohr, Schrödinger, Heisenberg, Dirac, Pauli, von Neumann — physicists working in the operational/operator-algebra tradition, for whom the spacetime metric was background, not source. General relativity and differential geometry were developed by Einstein, Hilbert, Levi-Civita, Cartan, Weyl, Schouten, Synge — for whom quantum mechanics was a parallel theory whose structure they did not seek to derive from theirs. The two traditions met at boundary problems but did not interpenetrate at the foundational level.

**The 5-year gap, 1962–1967.** Newman and Penrose introduced the null tetrad in 1962, giving the technical apparatus for treating null geometry as primitive. Penrose introduced twistor theory in 1967, making the inferential move from null geodesics as basic to spacetime points as derived. This is the closest the geometric tradition came to formalizing cone-nonlocality. But Penrose's twistor theory was motivated by problems of conformal symmetry, massless field equations, and scattering amplitudes; it was not motivated by quantum nonlocality, and Penrose did not extend the program in that direction.

**The 59-year gap, 1967–2026.** From Penrose 1967 to the present, the inferential step has remained unmade. The reasons in this period are sharper because the pieces were closest to assembly:

*First, the no-signaling theorem.* As quantum information matured in the 1980s and 90s, the no-signaling theorem became the canonical statement of how relativity and quantum mechanics coexist. The cone was read as the boundary of permitted causal influence. Once the cone is a boundary rather than a manifold, the question of its intrinsic geometric nonlocality does not arise.

*Second, the operational reading of Bell.* The post-Bell tradition treats nonlocality as a property of detector statistics, established by Bell-type theorems and confirmed experimentally. The geometric source is not part of the operational story, and the language of "nonlocal correlations" is detector-statistical, not metric-geometric.

*Third, Penrose's static twistor reading.* Twistor theory is a brilliant geometric reformulation, but it treats null structure as a primitive geometric fact, not as an active physical process. Without the active reading, the cone is a fixed mathematical object whose null-degeneracy is a structural feature without dynamical content. The McGucken Principle dx₄/dt = ic supplies the active reading, but the principle was not in the literature before 2024.

*Fourth, the conformal-symmetry reading.* The null hypersurface has been studied as the carrier of conformal symmetry (the cone is invariant under conformal transformations of Minkowski space), and this reading dominates in twistor theory, in Newman–Penrose, and in the asymptotic-symmetry literature (BMS group, soft theorems, celestial amplitudes). In this reading the cone is the carrier of a symmetry group, not the locus of geometric nonlocality. The conformal reading is mathematically rich and physically important, but it foreclosed the metric-nonlocality reading.

*Fifth, the path-integral framing of double-slit.* Feynman's path-integral formulation (1948) gave the double-slit phenomenon a beautiful operational explanation: paths add as amplitudes, and the cross-term is the interference. This explanation is correct and complete in its own terms, and it has functioned as the resting place for the question "why does the double-slit pattern exist?" But it does not anchor the pattern in the geometry of the cone hosting the paths. The Feynman story is local in the paths and nonlocal in the amplitude addition; the geometric story we tell here is that the amplitude addition is forced by the geometric nonlocality of the cone in which the paths live.

Pulling the threads of these obstructions together: the inferential step was never formalized because no single tradition combined the geometric reading of the cone with the operational reading of double-slit and Bell. Each of these obstructions individually was a defensible interpretive choice; their combination foreclosed the geometric reading we make here.

The present paper closes the gap. The geometric nonlocality is a theorem of the metric (Section 4). The double-slit nonadditivity is the operational signature in the single-particle distribution form (Section 6). The Bell violation is the operational signature in the joint-statistics form (Section 7). The McGucken Principle supplies the active mechanism (Section 8). The pieces have been on the table for over two centuries; the present contribution is to assemble them.

### 3.11 The MTW Farewell to x₄ = ict: Audit, Defense, and Resolution

A direct objection to the present paper's appeal to the McGucken Principle dx₄/dt = ic comes from the canonical graduate textbook on gravitation, Misner, Thorne, and Wheeler's *Gravitation* (1973) [24]. In a famous passage — usually known as Box 2.1, *Farewell to "ict"* — MTW set aside the imaginary-time coordinate x₄ = ict that Minkowski had used in his 1908 lecture, on the grounds that it was a calculational crutch that obscured the genuine geometric content of the Lorentzian metric and that did not extend to general curved spacetime. The MTW farewell is the single most influential disciplinary statement on x₄ = ict in the twentieth-century literature, and it has propagated into every major graduate textbook on general relativity that followed. Any defense of the McGucken Principle must engage MTW directly.

The defense proceeds in three steps. First, we audit MTW's actual claim and the four canonical follow-on textbooks (Wald, Carroll, Schutz, Weinberg) to establish precisely what was abandoned and what was kept. Second, we acknowledge that MTW's critique was *sound within its scope*: as a passive coordinate device, x₄ = ict has the defects MTW identified. Third, we show that the McGucken Principle dx₄/dt = ic is *not vulnerable to MTW's critique*, because the principle is an active physical statement, not a notational rotation, and its integrated form is a coordinate label of the expansion, not the expansion itself.

#### What MTW actually said

MTW's farewell to x₄ = ict is precise about what is being abandoned and why. The argument has four parts. (i) In flat Minkowski spacetime, x₄ = ict allows the interval to be written as the formally Euclidean form (Δs)² = (Δx¹)² + (Δx²)² + (Δx³)² + (Δx⁴)² with all-positive signature, the minus sign sitting at the coordinate label rather than at the metric tensor. (ii) This formally Euclidean appearance "hides" the indefinite Lorentzian signature of the spacetime from view, making spacetime look like an ordinary four-dimensional Euclidean space. (iii) In general curved spacetime, the imaginary unit at the coordinate label cannot be maintained under arbitrary diffeomorphisms: no extension of x⁴ = ict to a curved manifold is known that preserves the imaginary unit under coordinate transformations. (iv) Consequently, the imaginary-time convention is set aside in favor of a real time coordinate x⁰ = ct with the minus sign carried explicitly by the metric tensor of signature (−, +, +, +).

The MTW choice has dominated graduate pedagogy since 1973. Wald [25], Carroll [39], Schutz [40], and Weinberg [41] all use real time coordinates with explicit Lorentzian signature in the metric. The imaginary-time convention is, in modern graduate education in general relativity, essentially extinct.

#### The four follow-on textbooks: a verbatim audit

The propagation of MTW's farewell into the standard textbook canon merits documentation, because the question naturally arises: *did the follow-on textbooks engage with the imaginary coordinate at all, or did they silently inherit MTW's abandonment?*

*Wald (1984)* [25]. Wald's *General Relativity* does not use x⁴ = ict, does not mention it, and does not acknowledge it as a historical convention. The book's front matter declares the signature (−, +, +, +), the metric is treated as a real symmetric (0,2) tensor of Lorentzian signature, and abstract-index notation T_ab is used throughout. The Wick rotation appears only in Wald's companion volume on quantum field theory in curved spacetime, as a technical tool, never as a foundational geometric statement.

*Carroll (2004)* [39]. Carroll's *Spacetime and Geometry* and its 1997 open-source precursor lecture notes set up coordinates on Minkowski space as x^μ: x⁰ = ct, x¹ = x, x² = y, x³ = z, with the metric η_μν = diag(−1, +1, +1, +1) as a real symmetric matrix. Lorentz boosts are written in the explicitly hyperbolic form cosh φ, sinh φ — the form that the imaginary-time formalism would convert to Euclidean rotations cos θ, sin θ by analytic continuation φ ↦ −iθ, but Carroll does not draw the connection. The Wick rotation appears in his Chapter 9 (path integrals) as a formal calculational device, with no claim to physical reality of the rotated coordinate. The imaginary fourth coordinate is absent from Carroll's conceptual structure entirely.

*Schutz (1985, 2nd ed. 2009)* [40]. Schutz introduces coordinates in an inertial frame as (t, x, y, z) with interval Δs² = −(Δt)² + (Δx)² + (Δy)² + (Δz)² in geometrized units. Schutz attributes the four-dimensional viewpoint to Minkowski explicitly, but does not mention that Minkowski's 1908 formulation *itself* used x₄ = ict as the fourth coordinate. The historical attribution is given without the historical convention.

*Weinberg (1972)* [41]. Weinberg's *Gravitation and Cosmology* uses signature (+, −, −, −) — the opposite of MTW, Wald, Carroll, and Schutz — with real time coordinate x⁰ = t. The preface explicitly rejects the geometric viewpoint that would have made x₄ = ict natural in favor of an equivalence-principle program treating the metric as a field, not as geometry. There is no role for the imaginary unit anywhere in Weinberg's conceptual structure.

*Summary of the audit.* Of the five canonical graduate textbooks on gravitation, only one (MTW) explicitly acknowledges x₄ = ict before abandoning it. The other four (Wald, Carroll, Schutz, Weinberg) do not engage with the imaginary fourth coordinate at all. A student who learns general relativity in 2026 from any of the latter four will receive no historical signal that the imaginary fourth coordinate was ever a thing. The textbook canon has not just abandoned x₄ = ict; over the half-century since MTW, it has *forgotten* it.

#### Acknowledgment: MTW's critique is sound as a critique of x₄ = ict qua passive coordinate

We acknowledge that MTW were right to set aside x₄ = ict *as a passive coordinate device*. Read passively — as a notational convention that lets one write the Minkowski interval in formally Euclidean form — the convention has the defects MTW identified. (i) It is misleading in flat spacetime, suggesting Euclidean geometry where the structure is genuinely Lorentzian. (ii) It cannot be extended to curved spacetime, because the imaginary unit at the coordinate label is not preserved under arbitrary diffeomorphisms. (iii) It hides the distinction between covariant and contravariant tensors. (iv) It misleadingly suggests rotations between spatial and temporal axes are the same kind of thing as spatial rotations when they are not (they are hyperbolic, not circular, on the real section of the symmetry group). These criticisms are accurate. A passive-coordinate reading of x₄ = ict is a notational crutch, and MTW's farewell was, on its own terms, well-motivated.

#### What MTW could not see: the active reading

What MTW could not see, in 1973, is that there is a second reading of x₄ = ict available, and this second reading is not vulnerable to their critique. The second reading takes the foundational object to be not x₄ = ict but the dynamical principle

> dx₄/dt = ic,

which is the active physical statement that the fourth dimension is advancing at velocity ic at every event of spacetime. The integrated form x₄ = ict is then the kinematic record of this advance — the coordinate label of the expansion at parameter t — not the expansion itself. On this reading, the imaginary unit i in the rate ic is not a coordinate-level feature subject to diffeomorphism action; it is a principle-level feature recording the directional content of the advance, namely the perpendicularity of the x₄-direction to the spatial three.

The four parts of MTW's critique can be re-examined under the active reading:

1. *Hiding the Lorentzian structure.* Under the active reading, the formally Euclidean appearance of the interval (Δs)² = (Δx¹)² + ⋯ + (Δx⁴)² with x₄ = ict is not a misleading notational trick; it is the integrated trace of an active expansion in the imaginary direction at rate ic. The Lorentzian signature *arises* from the squared factor i² = −1 in the integrated coordinate, by Proposition 8.3. The Euclidean appearance is not a disguise of the Lorentzian structure; it is its generative form. The principle generates the Lorentzian metric, rather than the Lorentzian metric being expressed in disguise via the principle.

2. *Inextensibility to curved spacetime.* The McGucken-invariance property of the principle states that the rate dx₄/dt = ic is independent of the metric components g_μν:

> ∂/∂g_μν (dx₄/dt) = 0  for all μ, ν ∈ {0, 1, 2, 3}.

This is precisely the property that MTW identified as making x₄ = ict inextensible to curved spacetime: the rate is "gravity-rigid" — it does not respond to the metric. Under the passive-coordinate reading, this rigidity is the defect that MTW correctly criticized. Under the active reading, the same rigidity is a feature: the principle is invariant under diffeomorphism precisely because the rate is the invariant input to the geometry, not a derived quantity that needs to be transported by the diffeomorphism. The integrated form x₄ = ict then automatically holds in any coordinate chart on the curved spacetime manifold, because it is the time-integrated statement of a coordinate-independent principle. The obstruction MTW identified applies only if the imaginary unit is treated as a coordinate-level feature subject to diffeomorphism action. Under the active reading, the imaginary unit is a principle-level feature not subject to diffeomorphism action.

3. *Covariant/contravariant distinction.* The active reading does not require the formally Euclidean all-positive signature; the integrated form x₄ = ict generates the standard Lorentzian signature (−, +, +, +) via i² = −1 at the coordinate label, and the covariant/contravariant distinction proceeds in the standard way using the Lorentzian metric. The MTW critique on this point applies to a purely formal use of the all-positive signature; it does not apply to the active reading, which produces the Lorentzian signature as a theorem of the principle.

4. *Hyperbolic versus circular rotations.* Under the active reading, the rate dx₄/dt = ic specifies the relationship between the x₄-direction and the spatial three precisely. The factor i encodes the perpendicularity by a quarter-turn in the complexified plane spanned by any spatial axis and x₄. The real Lorentz boost is the real-rapidity element of the same SO(4, ℂ) action whose imaginary-rapidity element is the Wick rotation; the two are real forms of one complex group. The active reading does not collapse the hyperbolic/circular distinction — it sharpens it, by identifying both as elements of SO(4, ℂ) on different real sections. MTW's worry that the imaginary coordinate makes Lorentz boosts look like circular rotations is, on the active reading, replaced by the precise statement that the boost is a real-rapidity rotation and the Wick rotation is its imaginary-rapidity completion.

#### What was lost: the algebraic visibility of dimensional perpendicularity

The structural cost of MTW's abandonment can be stated precisely. When the textbook tradition migrated the minus sign from the coordinate label (x₄ = ict, i² = −1) to the metric tensor (g₀₀ = −1), it lost the *algebraic visibility* of the dimensional perpendicularity of the timelike axis to the spatial three. Under the passive x₄ = ict reading, a student who asks "why is x₄ perpendicular to x₁, x₂, x₃?" receives an answer at the algebraic level: because i² = −1, the same algebraic fact that distinguishes the imaginary axis from the real axis in the complex plane. Under the standard signature (−, +, +, +) reading, the same student receives an answer at the metric-convention level: because the signature happens to have one negative eigenvalue and three positive ones. The two answers are mathematically equivalent in flat spacetime, but they generate structurally different questions in curved spacetime, in quantum mechanics, and in unification programs.

The McGucken Principle restores algebraic visibility, but at the principle level rather than the coordinate level. Under dx₄/dt = ic, the perpendicularity of x₄ to the spatial three is encoded by the factor i in the rate, which records the perpendicularity of the direction of advance to the three spatial directions. The student now receives the answer: *because x₄ is the axis of the McGucken expansion, perpendicular to the three spatial axes in the dynamical sense dx₄/dt = ic, with the imaginary unit recording the perpendicularity of the direction of advance*. The asymmetry is not a feature of the metric convention; it is a feature of the physical principle.

#### Why this matters for the present paper

The present paper's metric-level theorems (Theorems 4.4, 5.1, 6.7, 7.3) do not depend on the choice of signature convention or on whether x₄ = ict is used. They work equally well in MTW's real-coordinate formalism and in the imaginary-time formalism, because the light cone is the same geometric object in both. The geometric nonlocality of the cone, the spacelike separation of the wavefront, the double-slit nonadditivity, and the Bell violation are all robust against the passive-coordinate critique MTW issued. A reader who accepts only the MTW-Wald-Carroll-Schutz tradition can read the paper through Section 7 and accept every result on the basis of standard Lorentzian geometry alone.

What changes under MTW's framing is only the principle-level reading in Section 8. The principle dx₄/dt = ic is not a coordinate convention for the Lorentz transformation; it is the physical statement that x₄ is expanding at velocity ic, and the integrated form x₄ = ict is its mere coordinate label. MTW's farewell was to a passive notational i; the principle's i is active. So the principle is not vulnerable to MTW's critique (which was about i as an inert coordinate device) while still retaining the structural content (which is about i as a geometric quarter-turn). The two readings of i — passive coordinate convention versus active expansion velocity — are precisely what MTW did not distinguish, because no active reading was available to them in 1973.

#### The Wheeler irony

A historical observation closes this subsection. John Archibald Wheeler — the founder of geometrodynamics, author with Misner and Thorne of the 1973 *Gravitation*, the most consequential geometric thinker in twentieth-century gravitational physics — supplied the recommendation letter for the present author at Princeton in the late 1980s. Wheeler's 1986 essay [23] articulated the structural-economy criterion that foundational physics should descend from "a minimum of postulates with a maximum of explanatory reach." The McGucken framework satisfies this criterion in its tightest form: one principle (dx₄/dt = ic) from which the Lorentz transformations, the Schrödinger equation, the Einstein field equations, Newton's law of gravitation, the second law of thermodynamics, and the Born rule are derived as theorems [28, 31, 32]. The principle Wheeler co-authored away in 1973, as a passive coordinate device, returns under the active reading as the foundational input from which the edifice of gravitational, quantum, and thermodynamic physics descends as a chain of theorems. The textbook tradition Wheeler canonized has not, as of 2026, caught up.

## 4. Geometric Nonlocality of the Null Hypersurface

**Lemma 4.1 (Null generators have zero proper length).** Let P ∈ 𝕄 and n̂ ∈ S². Let Q = P + λ₀(1, n̂) ∈ 𝒩_n̂(P) for some λ₀ > 0. Then the proper length of the null geodesic segment from P to Q is zero.

*Proof.* Parameterize by γ(λ) = P + λ(1, n̂) for λ ∈ [0, λ₀]. Then γ̇(λ) = (1, n̂), so η(γ̇, γ̇) = −1 + |n̂|² = −1 + 1 = 0. The squared interval element vanishes identically along γ, hence L(γ) = ∫_0^{λ₀} √0 dλ = 0. ∎

**Lemma 4.2 (Null relation along generators).** Let P ∈ 𝕄 and n̂ ∈ S². Let Q₁, Q₂ ∈ 𝒩_n̂(P) with Q₁ = P + λ₁(1, n̂), Q₂ = P + λ₂(1, n̂), 0 ≤ λ₁ < λ₂. Then Δs²(Q₁, Q₂) = 0, and the proper length of the geodesic segment from Q₁ to Q₂ is zero.

*Proof.* Δs²(Q₁, Q₂) = −(λ₂ − λ₁)² + |(λ₂ − λ₁)n̂|² = −(λ₂ − λ₁)² + (λ₂ − λ₁)² = 0. The geodesic from Q₁ to Q₂ is the segment of 𝒩_n̂(P) between them; by Lemma 4.1 applied to the subsegment, its proper length is zero. ∎

**Lemma 4.3 (The null hypersurface is degenerate as a submanifold).** The pullback of the Minkowski metric η to 𝒞⁺(P) ∖ {P} is a degenerate bilinear form: at every point it has a one-dimensional null direction, given by the tangent to the null generator through that point.

*Proof.* Let Q ∈ 𝒞⁺(P) ∖ {P}, Q = P + λ(1, n̂) for some λ > 0, n̂ ∈ S². Parameterize a neighborhood of Q in 𝒞⁺(P) by (λ, θ, φ), where (θ, φ) are spherical coordinates on S² around n̂. The embedding is (λ, θ, φ) ↦ P + λ(1, sin θ cos φ, sin θ sin φ, cos θ). The tangent vectors are ∂_λ = (1, n̂(θ, φ)), ∂_θ = λ(0, ∂_θ n̂), ∂_φ = λ(0, ∂_φ n̂). Computing pullback metric components:

- η(∂_λ, ∂_λ) = −1 + |n̂|² = 0
- η(∂_λ, ∂_θ) = λ n̂ · ∂_θ n̂ = 0 (since |n̂| = 1)
- η(∂_λ, ∂_φ) = λ n̂ · ∂_φ n̂ = 0
- η(∂_θ, ∂_θ) = λ² |∂_θ n̂|² = λ²
- η(∂_φ, ∂_φ) = λ² |∂_φ n̂|² = λ² sin² θ
- η(∂_θ, ∂_φ) = λ² ∂_θ n̂ · ∂_φ n̂ = 0

The matrix of the pullback in the basis (∂_λ, ∂_θ, ∂_φ) is diag(0, λ², λ² sin² θ), which has rank 2 (the S² block) and a one-dimensional null space spanned by ∂_λ, the tangent to the null generator. The pullback is degenerate, with null direction the generator tangent. ∎

**Theorem 4.4 (Geometric nonlocality of the null hypersurface).** Let P ∈ 𝕄 be an emission event. The future light cone 𝒞⁺(P) is a nonlocal manifold in the following precise sense: for every two events Q₁, Q₂ on the same null generator 𝒩_n̂(P), including the pair (P, Q) for any Q ∈ 𝒞⁺(P), the Lorentzian proper length of the geodesic segment connecting them is zero. The pullback metric on 𝒞⁺(P) ∖ {P} is degenerate with null direction given by the generator tangent. The null hypersurface therefore admits no intrinsic Riemannian distance function along its null directions, and its points are not separated by any positive proper length in the metric the spacetime supplies to them.

*Proof.* The three lemmas establish the claim. Lemma 4.1 establishes that every null generator from P has zero proper length to any of its points. Lemma 4.2 extends this to pairs of points on the same generator. Lemma 4.3 establishes the structural reason: the pullback metric is degenerate with null direction the generator tangent. The conclusion "the points of 𝒞⁺(P) are not separated by any positive proper length" is the precise sense in which 𝒞⁺(P) is a nonlocal manifold. ∎

*Remark (Photon's view from null infinity).* The theorem can be read from the photon's frame. An affine parameter λ along a null geodesic plays the role of "time" for the photon, but it is determined only up to affine transformation. There is no canonical photon clock — the metric supplies none, since proper time is identically zero. From the photon's own metric resources, emission at P and absorption at Q are not separated by any intrinsic measure. The cone is, from this internal perspective, a single locus.

*Remark (Distinction from coordinate distance).* The theorem does not claim that two events on the cone are at the same spacetime coordinates. They are not. The claim is structural: the metric assigns them zero proper length along their connecting null geodesic, even though they are coordinate-distinct. The nonlocality is *geometric* rather than *coordinate-trivial*: the metric, the spacetime's own measure of distance, refuses to distinguish them along the cone's null directions.

**Corollary 4.5 (Independence from spatial three-slice).** The geometric nonlocality of Theorem 4.4 is independent of any choice of spatial three-slice. It is a property of the Lorentzian metric and the null hypersurface alone.

*Proof.* Theorem 4.4 is stated and proven without reference to any time-slicing or spatial three-metric. The Lorentzian interval Δs² is a covariant function of pairs of events; 𝒞⁺(P) is defined invariantly; the proper length functional is covariantly defined on smooth curves. None of these depend on a choice of spatial slicing. ∎

**Remark 4.8 (Identification of W_t(P) with the McGucken Sphere under the principle).** The wavefront W_t(P) = {Q = (t_P + t, **x**_P + t·n̂) | n̂ ∈ S²}, defined in Section 4 purely from the Minkowski metric, is a topological and geometric 2-sphere of radius ct in the spatial three-slice at coordinate time t_P + t. Under the McGucken Principle dx₄/dt = ic (developed in Section 8), W_t(P) admits a second, principle-level identification: it is the *McGucken Sphere* 𝒮_t(P) of parameter t, defined as the unit 2-sphere S² rescaled by factor ct and equipped with the x₄-coincident state carried by the isotropic expansion from P. The McGucken Sphere is the natural carrier of the Born rule projection in the McGucken framework [28, 31]: the probability density for a detector outcome along direction n̂ ∈ S² is the squared modulus of the amplitude carried at the corresponding point of 𝒮_t(P), with the canonical S²-measure as the underlying volume form.

The identification W_t(P) = 𝒮_t(P) is a statement at two distinct levels of structure:

1. *At the metric level (this section, no principle):* W_t(P) is the spatial cross-section of the future null cone 𝒞⁺(P) at parameter t, a 2-sphere in Minkowski coordinates. Its geometric nonlocality (Theorem 4.4) is the metric-level fact that distinct points on the same null generator are at zero proper length, and the pullback metric is degenerate along generator directions.

2. *At the principle level (Section 8):* the same 2-sphere W_t(P) = 𝒮_t(P) is the instantaneous front of an isotropic x₄-expansion from P, with all its points x₄-coincident relative to P (Proposition 8.5). The state propagating on 𝒮_t(P) is a single x₄-coincident amplitude; the Born rule recovers detector probabilities as projections onto the McGucken Sphere.

The metric-level geometric nonlocality (Theorem 4.4) is the structural shadow of the principle-level x₄-coincidence on 𝒮_t(P), made precise in Theorem 8.6. Conversely, the principle's reading supplies the active mechanism that the metric alone does not: the metric tells us the cone is null-degenerate; the principle tells us *why* it is so, namely because the x₄-expansion proceeds at ic from every emission event, and the cone is the locus where the x₄-advance exactly cancels the spatial propagation in the Lorentzian interval (Theorem 8.6 part (i)).

*Precision of the identification.* The McGucken Sphere 𝒮_t(P) is the unit 2-sphere rescaled, so 𝒮_t(P) ≅ ct·S² as a Riemannian manifold with metric g_{S²} = ct·(dθ² + sin²θ dφ²). The wavefront W_t(P) in Minkowski coordinates is the embedded image

> ι: 𝒮_t(P) ↪ 𝕄,  (θ, φ) ↦ (t_P + t, **x**_P + ct·n̂(θ, φ)),

and the pullback of the spatial three-metric to 𝒮_t(P) recovers g_{S²} exactly. Thus W_t(P) and 𝒮_t(P) are isometric as Riemannian 2-spheres; the identification is canonical and rigorous, not metaphorical.

*What this remark does and does not claim at the metric level.* It does *not* use the principle in the proof of Theorem 4.4 (Section 4). The geometric nonlocality of the cone stands on the Lorentzian metric alone, derivable by any relativist working in pure Minkowski geometry without reference to the McGucken framework. The present remark only points forward, recording that the same 2-sphere W_t(P) on which the geometric nonlocality is exhibited is, under the principle, the McGucken Sphere 𝒮_t(P) on which the Born rule projection is naturally defined. The two readings agree on the underlying object; they differ in what additional structure is read into it.

The reader who accepts only the metric should read W_t(P) throughout the paper. The reader who accepts the principle should read W_t(P) = 𝒮_t(P) throughout. The theorems stand on the same proofs in both cases; the principle adds active content, not new geometric input.

**Remark 4.9 (The six-fold geometric identity of W_t(P)).** Theorem 4.4 establishes that the future null cone 𝒞⁺(P) is a nonlocal manifold via its null-hypersurface structure — the pullback metric is degenerate along its generator directions, and distinct points on the same generator are at zero proper length from each other. This is the *Lorentzian-geometric* demonstration that the wavefront W_t(P) ⊂ 𝒞⁺(P) carries a single geometric identity across its spatially separated points.

The Lorentzian-geometric demonstration is the deepest of *six* independent mathematical demonstrations that the wavefront W_t(P) is a single geometric object whose spatially separated points share a common identity traceable to the local origin P [42]. The other five demonstrations, which we summarize here without proof, supply independent confirmations from five distinct mathematical disciplines:

1. *Foliation theory.* The family {W_t(P)}_{t>0} is a foliation of the chronological future of P in ℝ³ by nested 2-spheres S² of radii ct. Each W_t(P) is a leaf of this foliation. All points on a single leaf share the common identity of *lying on the same leaf*, a topological identity invariant under any homeomorphism of the foliation.

2. *Level sets of a distance function.* Define the distance function d_P: ℝ³ → ℝ_{≥0} by d_P(**x**) = |**x** − **x**_P|. Then W_t(P) = d_P⁻¹({ct}). All points on W_t(P) share the metric identity of being at the same Euclidean distance ct from the origin **x**_P, and the level-set structure is preserved under any isometry of ℝ³.

3. *Huygens caustic and wavefronts.* By Huygens' Principle [43], W_t(P) is the caustic of secondary wavelets emanating from every point of W_{t−Δt}(P) in the limit Δt → 0⁺. All points on W_t(P) share the causal identity of being on the boundary of the disturbance propagating from P at parameter t.

4. *Legendrian submanifold of contact geometry.* The graph of W_t(P) in the jet space J¹(ℝ, ℝ³) = ℝ × T*ℝ³ is a Legendrian submanifold of the canonical contact structure, with contact form α = dt − (1/c)·((**x** − **x**_P)/|**x** − **x**_P|)·d**x**. All points on W_t(P) share the contact-geometric identity of belonging to the same Legendrian submanifold.

5. *Conformal pencil member.* The family {W_t(P)}_{t>0} forms a pencil of 2-spheres in the inversive (Möbius) geometry of ℝ³, with **x**_P as the common limit point. The pencil is invariant under the conformal group O(4, 1) acting on ℝ³ ∪ {∞}, and all members of the pencil share the conformal identity of being in the same pencil.

6. *Null-hypersurface cross-section of Minkowski geometry.* W_t(P) is the spatial cross-section of the null hypersurface 𝒞⁺(P) ⊂ 𝕄 at parameter t. By Theorem 4.4, the pullback metric on 𝒞⁺(P) ∖ {P} is degenerate along its null generators, and the Lorentzian proper length between distinct points on the same generator is zero. All points on W_t(P) share the Lorentzian-metric identity of lying on the same null cone at parameter t from P, with no positive Lorentzian proper length separating any two of them along the cone's null directions.

The six demonstrations are mutually reinforcing: each frames the same physical object (the expanding wavefront W_t(P)) in the language of a different mathematical discipline (topology, metric geometry, wave optics, contact geometry, conformal geometry, Lorentzian geometry), and each yields the same conclusion that W_t(P)'s spatially separated points share a common geometric identity traceable to the single local origin P. What appears from a three-dimensional Euclidean perspective as a collection of causally disconnected spatial points is, in any of the six framings, a single unified geometric object.

*Logical relationship to Theorem 4.4.* The present paper's Theorem 4.4 establishes (vi) rigorously from the Lorentzian metric alone, without reference to (i)–(v). Conversely, (i)–(v) are not needed for the proof of Theorem 4.4 or for the operational signatures of Sections 6 and 7: the present paper's results stand on (vi) alone. The other five demonstrations supply independent corroboration: a referee who finds the Lorentzian-metric demonstration (vi) unconvincing may consider the same conclusion reached by foliation theory (i), metric geometry (ii), wave optics (iii), contact geometry (iv), or conformal geometry (v) independently. The robustness of the conclusion across six mathematical frameworks is itself a strong structural argument that the wavefront is a single geometric object, not five-or-six accidentally-aligned ones.

*Active reading under the principle.* Under the McGucken Principle dx₄/dt = ic (Section 8), all six demonstrations are reframed as features of the same active x₄-expansion. The foliation {W_t(P)} is the trajectory of the expansion; the level sets are the level curves of x₄-coincidence; the Huygens caustic is the spatial trace of the x₄-advance; the Legendrian submanifold is the jet-space record of the expansion velocity; the conformal pencil is the inversive image of the principle's spherical symmetry; the null-hypersurface cross-section is the Lorentzian shadow of the cancellation of x₄-advance and spatial propagation along the cone's generators (Theorem 8.6 part (i)). Under the principle, the six frameworks are six aspects of the same active expansion; under the metric alone, they are six independent confirmations of the same null-hypersurface fact.

## 5. Spatial-Slice Spacelike Separation

**Theorem 5.1 (Spacelike separation on the wavefront).** Let P ∈ 𝕄, t > 0, A, B ∈ W_t(P), A ≠ B. Then Δs²(A, B) > 0, and explicitly Δs²(A, B) = 2t²(1 − n̂_A · n̂_B), where n̂_A, n̂_B ∈ S² are the unit directions from P to A, B respectively.

*Proof.* Without loss of generality P = (0, **0**). Then A = (t, t n̂_A), B = (t, t n̂_B), and Δs²(A, B) = −(t − t)² + |t n̂_A − t n̂_B|² = t²|n̂_A − n̂_B|² = 2t²(1 − n̂_A · n̂_B). Since A ≠ B, n̂_A ≠ n̂_B, hence n̂_A · n̂_B < 1, so Δs² > 0. ∎

**Corollary 5.2 (No post-emission classical mediation).** Let A, B ∈ W_t(P), A ≠ B. There is no event X ∈ 𝕄 with X ≠ P and t_X > t_P such that both A and B lie in the causal future of X.

*Proof.* Suppose such an X exists with X = (t_P + τ, **x**_P + **u**), |**u**| ≤ τ, 0 < τ < t. For A = (t_P + t, **x**_P + t n̂_A):

> Δs²(X, A) = −(t − τ)² + |t n̂_A − **u**|².

By the reverse triangle inequality, |t n̂_A − **u**| ≥ |t n̂_A| − |**u**| = t − |**u**| ≥ t − τ, with equality only if **u** is parallel to n̂_A and |**u**| = τ. Hence Δs²(X, A) ≥ 0, with equality requiring **u** = τn̂_A, i.e. X ∈ 𝒩_{n̂_A}(P). Identically, Δs²(X, B) ≥ 0 with equality requiring X ∈ 𝒩_{n̂_B}(P).

For X to lie in the causal past of both A and B, we need Δs²(X, A) ≤ 0 and Δs²(X, B) ≤ 0. Combined with the lower bounds, both equalities are forced, hence X ∈ 𝒩_{n̂_A}(P) ∩ 𝒩_{n̂_B}(P). Since n̂_A ≠ n̂_B, these distinct null half-lines from P intersect only at P. Hence X = P, contradicting X ≠ P. ∎

*Remark.* Theorem 4.4 and Theorem 5.1 together give a complete picture of the cone's nonlocal structure. *Along* the null generators, distinct points are at zero proper length — metrically identified by the cone's intrinsic measure. *Across* the null generators, distinct points are spacelike-separated — maximally non-influenceable by any subluminal signal. The cone is the locus where these two extremes meet.

## 6. Double-Slit Nonadditivity as Operational Signature (Single-Particle Distributions)

In this section we prove that the empirically observed failure of probability additivity in the double-slit experiment is forced by the geometric nonlocality of the cone 𝒞⁺(P) supporting the propagation. This is the operational signature of cone-nonlocality in the single-particle distribution form, complementing the joint-statistics form (Bell–CHSH) proven in Section 7.

### 6.1 The Classical Additivity Law

Let P ∈ 𝕄 be a source event. Let S₁, S₂ be two distinct slits in a barrier placed at coordinate time t_P + t_slit > t_P. Let D be a screen at t_P + t_screen with t_screen > t_slit.

**Definition 6.1 (Single-slit and double-slit distributions).**

- P₁(x): probability density that a particle emitted at P arrives at position x, with S₁ open and S₂ blocked.
- P₂(x): probability density that a particle emitted at P arrives at position x, with S₂ open and S₁ blocked.
- P₁₂(x): probability density with both slits open.

**Definition 6.2 (Local trajectory model).** A *local trajectory model* consists of a probability space (Λ, ℱ, μ) and functions σ: Λ → {1, 2}, ξ: Λ → D such that (i) for each λ, the particle's trajectory passes through slit S_σ(λ) and arrives at ξ(λ); and (ii) configuration changes at one slit do not affect (σ(λ), ξ(λ)) for trajectories with σ(λ) pointing to the other slit.

**Lemma 6.3 (Classical additivity from a local trajectory model).** If the double-slit experiment admits a local trajectory model in the sense of Definition 6.2, then there exist weights w₁, w₂ ≥ 0 with w₁ + w₂ = 1 such that P₁₂(x) = w₁P₁(x) + w₂P₂(x) for all x ∈ D.

*Proof.* Let Λ_j = σ⁻¹({j}); these are disjoint with Λ = Λ₁ ∪ Λ₂, set w_j = μ(Λ_j). With both slits open:

> P₁₂(x) = ∫_Λ δ(ξ(λ) − x) dμ(λ) = ∫_{Λ₁} + ∫_{Λ₂}.

With only S₁ open, the Λ₂ trajectories are removed (their slit is blocked), and the Λ₁ trajectories are unaffected by locality. Hence P₁(x) = (1/w₁) ∫_{Λ₁} δ(ξ(λ) − x) dμ(λ), and similarly P₂. Substituting, P₁₂(x) = w₁P₁(x) + w₂P₂(x). ∎

*Remark (The empirical fact).* The empirical observation of double-slit interference (Young 1801 [33], Davisson–Germer 1927 [34], Jönsson 1961 [35], Tonomura 1989 [36]) is that additivity *fails*: there exist screen positions x where P₁(x), P₂(x) > 0 but P₁₂(x) = 0 (interference minima), and positions where P₁₂(x) exceeds any w₁P₁ + w₂P₂ (interference maxima). The quantitative form is

> P₁₂(x) = |ψ₁(x) + ψ₂(x)|² = |ψ₁|² + |ψ₂|² + 2 Re[ψ₁* ψ₂]

with the cross-term taking both signs across the screen.

### 6.2 Geometric Source: The Slits Lie on W_{t_slit}(P)

**Proposition 6.5 (Slits as wavefront events).** In the idealized limit of slits with negligible spatial extent and a source at rest in the chosen frame, the slit events S₁ = (t_P + t_slit, **x**_P + t_slit·n̂₁) and S₂ = (t_P + t_slit, **x**_P + t_slit·n̂₂) lie on the same wavefront W_{t_slit}(P).

*Proof.* By Definition 2.2, the wavefront W_t(P) consists of all events Q = (t_P + t, **x**_P + t·n̂) for n̂ ∈ S². With t = t_slit, both slit events lie on W_{t_slit}(P) ⊂ 𝒞⁺(P). ∎

### 6.3 Double-Slit Nonadditivity as Theorem of Geometric Nonlocality

**Theorem 6.7 (Double-slit nonadditivity from geometric nonlocality).** Let P ∈ 𝕄 be a source event, S₁, S₂ two distinct slits in the causal future of P, D a screen further in the causal future. Suppose the empirically observed double-slit distribution P₁₂(x) exhibits interference: there exist screen positions x at which the cross-term 2 Re[ψ₁* ψ₂] < 0 and P₁₂(x) < w₁P₁(x) + w₂P₂(x) for all w₁, w₂ ≥ 0 with w₁ + w₂ = 1. Then no local trajectory model in the sense of Definition 6.2 can reproduce P₁₂. The wavefront W_{t_slit}(P), on which S₁ and S₂ both lie (Proposition 6.5), must therefore be regarded as the carrier of a single nonlocal state whose support at S₁ and S₂ is not separable into independent local trajectories.

*Proof.* Suppose for contradiction that a local trajectory model exists. By Lemma 6.3, the double-slit distribution satisfies the additivity law P₁₂(x) = w₁P₁(x) + w₂P₂(x). This contradicts the hypothesis that there exist screen positions where P₁₂(x) < w₁P₁(x) + w₂P₂(x) for all such weights. The structural conclusion follows: Theorem 4.4 establishes that the cone 𝒞⁺(P) is a single null locus; the wavefront W_{t_slit}(P) is its spatial cross-section containing both slits; the state emitted from P and propagating on 𝒞⁺(P) has support on the entire wavefront, including both slit positions, with no factorization into a trajectory-through-S₁ component plus a trajectory-through-S₂ component. The observed nonadditivity is the operational manifestation of this prior geometric fact. ∎

*Remark (Comparison with Bell–CHSH).* The double-slit nonadditivity (Theorem 6.7) and the Bell–CHSH violation (Theorem 7.3 in Section 7) are two independent operational signatures of the same prior geometric fact. The double-slit signature uses a single particle with no settings; the Bell–CHSH signature uses common-origin pairs with chosen settings. Each is sufficient to establish that the cone hosting the propagation cannot be reduced to a positive measure on local configurations. The double-slit signature has been empirically established since Young 1801 and is therefore the oldest operational consequence of cone-nonlocality.

*Remark (Tonomura: single-electron buildup).* Tonomura's 1989 experiment [36] closes the loophole that the pattern might be a many-particle wave artifact: individual electrons arrive one at a time as localized hits, but the accumulated distribution reproduces the interference pattern. Each individual electron is drawn from the nonadditive P₁₂, not from w₁P₁ + w₂P₂. Single-particle cone-nonlocality is empirically established at the level of each individual quantum.

*Remark (Cross-term form).* For the standard two-slit geometry with slit separation d and screen distance L ≫ d, the cross-term is 2|ψ₁||ψ₂| cos(2π d sin θ / λ), where θ = arctan(x/L) and λ is the de Broglie wavelength. The cosine oscillates between ±1, giving maxima at d sin θ = nλ and minima at d sin θ = (n + ½)λ. Its magnitude is bounded by 2√(P₁ P₂), the bound on the cross-term in any complex-amplitude theory.

## 7. Bell Violation as Operational Signature (Joint Statistics)

**Theorem 7.1 (CHSH bound for local hidden variables).** If there exists a probability space (Λ, ℱ, ρ) and measurable functions A: {a, a′} × Λ → {−1, +1}, B: {b, b′} × Λ → {−1, +1} such that 𝔼[𝔸_a 𝔹_b] = ∫_Λ A(a, λ) B(b, λ) dρ(λ) for all settings, then |S| ≤ 2 where S = 𝔼[𝔸_a 𝔹_b] − 𝔼[𝔸_a 𝔹_{b′}] + 𝔼[𝔸_{a′} 𝔹_b] + 𝔼[𝔸_{a′} 𝔹_{b′}].

*Proof.* For any λ, let T(λ) = A(a, λ)[B(b, λ) − B(b′, λ)] + A(a′, λ)[B(b, λ) + B(b′, λ)]. Since each B ∈ {−1, +1}, exactly one of B(b, λ) − B(b′, λ) and B(b, λ) + B(b′, λ) is zero and the other is ±2, so |T(λ)| ≤ 2. Integrating, |S| = |∫T dρ| ≤ ∫|T| dρ ≤ 2. ∎

**Lemma 7.2 (Local realist factorization forced to anchor at P).** Let A, B ∈ W_t(P), A ≠ B. If the joint distribution of detector outcomes admits a local realist decomposition respecting the causal structure of 𝕄, then there exists (Λ, ρ) and functions A(·, λ), B(·, λ) such that ℙ(𝔸_a = α, 𝔹_b = β) = ∫_Λ 𝟙{A(a, λ) = α}·𝟙{B(b, λ) = β} dρ(λ), with ρ determined by the state at P.

*Proof.* By Corollary 5.2, no event X ≠ P lies in the common causal past of A and B after P. The only common cause accessible to a local realist account is the state at P; let λ denote it. Under freedom-of-choice, settings (a, b) are independent of (λ, each other). Under locality, the outcome at A depends only on data within A's past light cone, which by the preceding is (a, λ). Hence ℙ(𝔸_a = α | λ) = 𝟙{A(a, λ) = α} for some deterministic A, and identically for B. Conditional independence given λ yields the factorization. ∎

**Theorem 7.3 (Bell violation as operational signature of geometric nonlocality).** Let P ∈ 𝕄, t > 0, A, B ∈ W_t(P), A ≠ B. Suppose the joint statistics satisfy |S| > 2. Then no local realist decomposition respecting the causal structure of 𝕄 is possible. The geometric nonlocality of the cone (Theorem 4.4) admits, and the experimental Bell-violation confirms, the conclusion that the wavefront W_t(P) hosts joint statistics that no positive measure on a classical sample space can reproduce.

*Proof.* Suppose for contradiction such a decomposition exists. By Lemma 7.2, the distribution factorizes through a probability space at P. By Theorem 7.1, |S| ≤ 2, contradicting |S| > 2.

The relationship to Theorem 4.4: the geometric nonlocality of the cone makes it natural that field theories on 𝒞⁺(P) carry correlations that do not factor through a classical probability space at P, because the cone is already a single null locus from the metric's standpoint. The Bell-violation is the operational manifestation of this prior geometric fact. ∎

*Remark (Empirical premise).* |S| > 2 is supplied by the 2015 loophole-free experiments [8, 9, 10] at confidence exceeding 10⁻⁷, with detection-efficiency, freedom-of-choice, and locality loopholes closed.

*Remark (Independence from Hilbert-space formalism).* Neither Theorem 4.4 nor the argument from |S| > 2 to "no local realist decomposition" invokes Hilbert-space states, operators, the Born rule, or any other apparatus of standard quantum mechanics. The conclusion is structural; any successor theory matching the experimental data must share it.

## 8. The Active Wavefront under dx₄/dt = ic

**Definition 7.1 (McGucken Principle).** The McGucken Principle states that the fourth dimension x₄ is physically expanding at the speed of light: dx₄/dt = ic, where t is the coordinate time of any inertial observer and the factor i encodes the orthogonality of the expansion to the spatial three.

*Remark (Status of the principle).* The principle traces to the present author's undergraduate work under Wheeler at Princeton in the late 1980s, is implicit in the 1998–99 UNC Chapel Hill dissertation appendix, was developed in MDT papers 2003–06, FQXi essays 2008–13, books 2016–17, and the corpus at elliotmcguckenphysics.com from October 2024 onward [28]. Its theorems include the Lorentz transformations, Schrödinger equation, Einstein field equations, Newton gravity, second law of thermodynamics, and the Born rule via the McGucken sphere [28, 31, 32].

**Proposition 8.3 (Metric signature from the principle).** The integrated form x₄ = ict, with Euclidean four-coordinate line element ds_E² = dx₁² + dx₂² + dx₃² + dx₄², yields the Lorentzian metric ds² = dx₁² + dx₂² + dx₃² − c² dt².

*Proof.* Substitute dx₄ = ic dt: (ic dt)² = i² c² dt² = −c² dt². ∎

**Definition 7.3 (x₄-coincidence).** Two events A, B ∈ 𝕄 are *x₄-coincident* relative to P if both have been reached by the isotropic x₄-expansion from P at the same parameter t: t_A = t_B = t_P + t for some common t > 0, with both A, B ∈ 𝒞⁺(P).

**Proposition 8.5 (Wavefront = x₄-coincident locus).** W_t(P) is the locus of events mutually x₄-coincident relative to P at parameter t.

*Proof.* Immediate from the definitions. ∎

**Theorem 8.6 (Geometric nonlocality as theorem of x₄-expansion).** Under the McGucken Principle, the geometric nonlocality of Theorem 4.4 is a theorem of the active x₄-expansion from P. Specifically:

1. The null generators 𝒩_n̂(P) are the worldlines along which the spatial advance |Δ**x**| = c Δt exactly cancels the temporal advance c Δt in the Lorentzian interval — the worldlines along which the active x₄-expansion and the spatial propagation are kinematically identified.

2. The zero proper length of null generators (Lemma 4.1) is the statement that the integrated active x₄-advance and the integrated spatial displacement contribute equally and opposite to ds², with their cancellation expressed by η(γ̇, γ̇) = 0.

3. The wavefront W_t(P) is the instantaneous front of the isotropic x₄-expansion at parameter t, and all its points are x₄-coincident.

*Proof.* For (i): a worldline γ(λ) = P + λ(1, n̂) has |d**x**/dt| = c. Under the principle, |dx₄/dt| = c. Spatial speed equals x₄-advance speed.

For (ii): along γ, ds² = −c² dt² + |d**x**|² = −c² dλ² + c² dλ² = 0, with cancellation between the i² c² contribution from dx₄² via the principle, and |d**x**|². Integrating, L(γ) = 0, recovering Lemma 4.1.

For (iii): by Proposition 8.5. ∎

**Corollary 8.7 (Bell violation under the principle).** Under the McGucken Principle, the Bell violation of Theorem 7.3 is the operational signature of x₄-coincidence on the wavefront. Detectors at distinct A, B ∈ W_t(P) are x₄-coincident with each other and with P in the integrated coordinate; their joint statistics inherit correlations from the single x₄-coincident state, and the spatial spacelike-separation of Theorem 5.1 is the Lorentzian shadow of that coincidence.

*Proof.* Combine Theorem 7.5(iii) with Theorem 6.3. The single x₄-coincident state at parameter t projects onto the spatial three-slice as the wavefront W_t(P). Joint statistics of detectors on W_t(P) inherit the structure of the single state; they cannot factor through a classical probability space at P because the cone is geometrically nonlocal (Theorem 7.5(ii)). The empirical |S| > 2 is the measured form. ∎

## 9. Discussion

### 9.1 The Role of i in x₄ = ict

The factor i in the integrated form x₄ = ict is the generator of a quarter-turn in the complexified plane spanned by any spatial axis and x₄. Multiplication by i is rotation by π/2, and this rotation converts the Euclidean four-coordinate line element into the Lorentzian metric via Proposition 8.3. The Wick rotation [30] is the imaginary-rapidity element of the same SO(4, ℂ) action whose real-rapidity element is the Lorentz boost. The i is the structural ingredient that makes the cone null-degenerate: under i, the temporal advance and the spatial advance contribute oppositely to ds², and the cone is the locus of their cancellation.

### 9.2 The Role of c in dx₄/dt = ic

The factor c in the principle is the magnitude of the x₄-expansion. While i encodes orthogonality (quarter-turn), c encodes the rate. Both are required for dx₄/dt = ic to be a well-defined geometric statement. Under Wick rotation, i is toggled but c survives: in Lorentzian signature, c is the speed of light along null worldlines; in Euclidean signature, c is the conversion factor between τ and spatial length. The light cone, the geometric expression of c as a real velocity, exists only when i is live; under rotation the cone collapses to the origin, but c persists as a length scale.

### 9.3 No-Signaling Compatible with Geometric Nonlocality

Theorem 4.4 establishes the cone is geometrically nonlocal. The no-signaling theorem ensures that the marginal at any single detector is independent of the distant setting; this is not violated by the geometric nonlocality, because the geometric nonlocality is along the cone's null directions while signal propagation is along timelike directions. The marginal at A depends only on data within A's past light cone, which by Corollary 5.2 is the setting at A and the common state at P, not on the distant setting at B. No-signaling is therefore compatible with the geometric nonlocality, and is its proper statement at the level of marginal distributions.

### 9.4 Probability Cloaks Nonlocality: The Joint Geometric Source of the Tsirelson Bound and the No-Signaling Marginal

The previous subsection establishes a compatibility result: no-signaling is consistent with geometric nonlocality. A deeper result is available at the principle level: no-signaling and the Tsirelson saturation of the CHSH bound are not two independent features that happen to be consistent. They are two algebraic shadows of one geometric fact — the SO(3)-invariance of the principle dx₄/dt = ic acting on the singlet wavefront on the McGucken Sphere at the apex emission event. The present subsection states and proves this result. It supplies the structural reason that the Tsirelson saturation |S_CHSH| = 2√2 and the marginal-flatness P(a | x) = 1/2 are jointly exact across all Bell-type experiments since 1972, rather than two approximately-balanced features whose conjunction has no underlying mechanism. The development follows [48, §10.3].

#### Historical orientation

The standard no-signaling theorem of quantum mechanics [49, 50, 51] states that no observer can transmit a message faster than light using entangled pairs, even though the entangled pair exhibits instantaneous nonlocal correlations saturating the Tsirelson bound 2√2 [52]. The standard derivation is purely algebraic: linearity of quantum mechanics combined with the trace-preserving property of completely positive maps gives the marginal probability P(a | x) = Σ_b P(a, b | x, y) at one detector independent of the distant setting y, because the partial trace over the distant subsystem returns the same reduced density matrix regardless of what local operation the distant observer performs. This is a theorem of the algebraic apparatus; it carries no geometric content. The derivation works equally well in a flat-space algebraic formalism with no metric, no light cone, and no specific spacetime structure. This is precisely why no-signaling has historically appeared as an unmotivated coexistence between nonlocality (which appears to require relativistic violation) and relativistic causality (which forbids superluminal signaling). Shimony [53] named this unresolved tension "peaceful coexistence." Bell [54] called it "the real problem with quantum theory: the apparently essential conflict between any sharp formulation [of locality] and fundamental relativity."

The McGucken Point framework [48] reformulates the no-signaling theorem as a property of the physical apparatus (the principle dx₄/dt = ic acting at every event with full SO(3) symmetry on the resulting McGucken Sphere), not of the algebraic formalism. We state the two foundational lemmas, then the main theorem with proof.

#### Foundational lemmas

**Lemma 9.4.1 (SO(3)-symmetry of the McGucken Sphere at the apex event).** Let P ∈ 𝕄 be an emission event and let 𝒮_t(P) = W_t(P) be the McGucken Sphere generated by dx₄/dt = ic at P at parameter t > 0, with 𝒮_t(P) the spatial 2-sphere cross-section at radius r = ct (Remark 4.8). The action of the rotation group SO(3) on 𝒮_t(P) about the apex P is a free and transitive isometry of the surface, and the principle dx₄/dt = ic at P is invariant under this SO(3) action.

*Proof.* The principle dx₄/dt = ic at the apex P specifies the rate of x₄-expansion as a scalar (the real-valued magnitude c paired with the imaginary unit i) with no preferred spatial direction. By the spherical symmetry of the principle's geometric content (Section 8), the locus of events at radius r = ct from P is the spatial 2-sphere 𝒮_t(P) of radius r centered at the spatial projection **x**_P. The action of SO(3) on ℝ³ centered at **x**_P preserves r and permutes the points of 𝒮_t(P) freely and transitively. Since dx₄/dt = ic at P has no preferred spatial direction, SO(3) acts as an isometry of 𝒮_t(P) that leaves the principle's content at P invariant. ∎

**Lemma 9.4.2 (Wavefront-identity inheritance on 𝒮_t(P)).** Let 𝔭_A, 𝔭_B be two spin-½ systems co-emitted at P with shared McGucken Sphere 𝒮_t(P). Let ψ₀ be the singlet wavefront on 𝒮_t(P) at emission, satisfying the SO(3)-singlet condition Ĵ_total ψ₀ = 0 where Ĵ_total = Ĵ_A + Ĵ_B. Then the joint state at later events

> ρ_AB(τ) = |ψ_singlet⟩⟨ψ_singlet|, |ψ_singlet⟩ = (1/√2)(|+⟩_A|−⟩_B − |−⟩_A|+⟩_B)

is preserved along the propagation of 𝔭_A, 𝔭_B from P to any later events p_A, p_B ∈ 𝒞⁺(P) with t_{p_A} = t_{p_B} = t_P + τ.

*Proof.* The singlet wavefront ψ₀ on 𝒮_t(P) at emission P is, by construction, the unique SO(3)-invariant state in the joint Hilbert space ℋ_A ⊗ ℋ_B for spin-½ systems (Wigner [55]; uniqueness of the SO(3)-trivial irrep in (1/2) ⊗ (1/2) = 0 ⊕ 1). Along the propagation, 𝔭_A and 𝔭_B advance with shared x₄-coordinate (Definition 8.4, Proposition 8.5): they remain at the same x₄-coordinate at every τ. The shared x₄-coordinate is the geometric statement that 𝔭_A and 𝔭_B inhabit the same four-dimensional slice — they have not been separated in the four-dimensional sense, only in the three-dimensional projection. The unitary evolution along each worldline acts trivially on the SO(3)-singlet structure (singlets transform trivially under any SO(3)-equivariant unitary), so the joint state remains |ψ_singlet⟩⟨ψ_singlet| at every later τ. ∎

#### The McGucken physical-apparatus no-signaling theorem

**Theorem 9.4.3 (Probability cloaks nonlocality; physical-apparatus no-signaling at the McGucken Sphere level).** Let 𝔭_A, 𝔭_B be two spin-½ systems sharing a common McGucken Sphere 𝒮_t(P). Let the joint state ρ_AB = |ψ_singlet⟩⟨ψ_singlet| be the singlet inherited from the wavefront identity at P via Lemma 9.4.2. Let M̂_A(x), M̂_B(y) be local POVM measurement settings at A, B parametrized by detector orientations **x̂**, **ŷ** ∈ S², each given by the standard spin-½ projector

> M̂_a^A(x) = (1/2)(𝟏_A + a·**σ**_A·**x̂**), M̂_b^B(y) = (1/2)(𝟏_B + b·**σ**_B·**ŷ**).

Then, under the principle dx₄/dt = ic together with the structural assumption (A1) SO(3)-invariance of the Born rule on the McGucken Sphere via Gleason's theorem [56] applied to the SO(3)-action on the surface 2-sphere, the following three conclusions hold jointly:

*(i) Tsirelson-saturating joint statistics.* The joint probability distribution

> P(a, b | x, y) = Tr[(M̂_a^A(x) ⊗ M̂_b^B(y)) ρ_AB] = (1/4)(1 − ab **x̂**·**ŷ**)

yields the singlet correlation E(x, y) = −**x̂**·**ŷ** which, optimized over four detector settings, saturates the CHSH inequality at the Tsirelson value |S_CHSH|_max = 2√2.

*(ii) Marginal-flat statistics (no-signaling).* The marginal probability at detector A

> P(a | x) = Σ_{b ∈ {+, −}} P(a, b | x, y) = 1/2

is exactly independent of the distant setting y. The corresponding marginal at B is P(b | y) = 1/2 exactly independent of x.

*(iii) Geometric conjunction.* The geometric content that establishes (i) — namely, the SO(3)-invariance of dx₄/dt = ic at the apex P acting on the singlet wavefront ψ_singlet — is the same geometric content that establishes (ii). The nonlocal correlation channel of (i) carries no usable information because the cloaking mechanism is structural: the wavefront identity (i) and the wavefront intensity (ii) live on the same geometric object 𝒮_t(P), and any deformation of one is a deformation of the other. The cancellation is exact at the level of the geometry — not approximate, not perturbative.

*Proof.* *Step 1 (Singlet state from wavefront-identity inheritance).* By Lemma 9.4.2, the joint state ρ_AB is the singlet density matrix. The singlet has j = 0 (SO(3)-trivial), purity Tr(ρ_AB²) = 1, and inherits its SO(3)-invariance from the SO(3)-action on 𝒮_t(P) at the apex P (Lemma 9.4.1).

*Step 2 (Joint statistics — direct computation).* The joint probability is P(a, b | x, y) = ⟨ψ_singlet|(M̂_a^A(x) ⊗ M̂_b^B(y))|ψ_singlet⟩. Inserting POVMs and using ⟨**σ**_A⟩_singlet = ⟨**σ**_B⟩_singlet = 0 and ⟨(**σ**_A·**x̂**)(**σ**_B·**ŷ**)⟩_singlet = −**x̂**·**ŷ** [57, §2.6]:

> P(a, b | x, y) = (1/4)(1 − ab **x̂**·**ŷ**).

*Step 3 (CHSH expectation).* E(x, y) = Σ_{a,b} ab·P(a, b | x, y) = −**x̂**·**ŷ**, using Σ_{a,b} ab = 0 and Σ_{a,b}(ab)² = 4.

*Step 4 (Tsirelson saturation).* With **â**₁ = (1, 0, 0), **â**₂ = (0, 1, 0), **b̂**₁ = (1, 1, 0)/√2, **b̂**₂ = (1, −1, 0)/√2:

> S = E(a₁, b₁) + E(a₁, b₂) + E(a₂, b₁) − E(a₂, b₂) = −4/√2 = −2√2.

Therefore |S| = 2√2, the Tsirelson upper bound [52]. This is conclusion (i).

*Step 5 (Marginal at A — exact identity).* P(a | x) = Σ_b (1/4)(1 − ab **x̂**·**ŷ**) = (1/4)[(1 − a **x̂**·**ŷ**) + (1 + a **x̂**·**ŷ**)] = 1/2. The terms containing **ŷ** cancel identically. Therefore P(a | x) = 1/2 exactly independent of **ŷ**, not approximately.

*Step 6 (Marginal at B — exact by symmetry).* Identically, P(b | y) = 1/2 exactly independent of **x̂**. This is conclusion (ii).

*Step 7 (The conjunction of (i) and (ii) is the same geometric fact).* The joint distribution decomposes as

> P(a, b | x, y) = (1/4) [j = 0 scalar (marginal)] + (−1/4) **x̂**·**ŷ** · ab [j = 1 tensor (correlation)].

The two components are the unique decomposition of the SO(3)-invariant singlet wavefront into its scalar and tensor angular-momentum sectors. Both components are SO(3)-invariant readings of dx₄/dt = ic at the apex P (Lemma 9.4.1).

*Step 8 (Deformation of one is deformation of the other).* Suppose for contradiction P̃(a, b | x, y) = (1/4)(1 − ab α **x̂**·**ŷ** + β(a + b) f(x, y)) with α ≠ 1 or β ≠ 0. Then P̃(a | x) = 1/2 + (β/2) a f(x, y). If β ≠ 0, the marginal depends on y and signaling is possible. If β = 0, the CHSH maximum is |S̃|_max = 2√2 α, saturating Tsirelson only when α = 1 (for α > 1 the joint state is not positive). Therefore Tsirelson saturation (α = 1) and exact marginal-flatness (β = 0) are mutually implicative; both are forced by the SO(3)-invariance of dx₄/dt = ic at P.

*Step 9 (Physical-apparatus statement).* Conclusions (i) and (ii) are jointly forced by the SO(3)-invariance of dx₄/dt = ic at the apex P acting on ψ_singlet on 𝒮_t(P). The standard algebraic no-signaling theorem [49, 50, 51] reads only the algebraic shadow of this action — the partial trace over the distant subsystem — and obtains (ii) as a CPTP-map consequence, without recognizing that the same SO(3)-action also forces (i).

*Step 10 (Cancellation is geometric, not algebraic).* The exact cancellation between nonlocal correlation and marginal-flatness, which the standard derivation obtains as an algebraic identity (partial trace giving unchanged reduced density matrix), is a geometric identity: ψ_singlet is the unique SO(3)-invariant state on 𝒮_t(P) [55], and SO(3)-invariance forces both the maximal nonlocal correlation (j = 1, Tsirelson) and the flat marginal (j = 0, uniform 1/4). Conclusion (iii) is established. ∎

#### Structural consequences

**Corollary 9.4.4 (Exactness, not approximation).** The no-signaling theorem is exact — not approximate, not a low-energy effective statement, not a leading-order approximation in any small parameter. Under the McGucken framework this exactness has a single geometric reason: the McGucken Sphere is the one object on which both nonlocality and probability live, and the SO(3)-invariance of dx₄/dt = ic at the apex P forces both Tsirelson saturation and marginal-flatness as joint readings of one symmetry. By Step 8, any deformation of one is a deformation of the other; the cancellation is at the level of the geometry, not of the algebra. This is the structural reason for the exact saturation of the Tsirelson bound 2√2 across forty years of Bell experiments at separations from millimeters to 1200 km.

**Corollary 9.4.5 (Two faces of one expansion).** The two "strange features" of quantum mechanics historically taken as independent — instantaneous nonlocal correlation [5, 4, 58] and irreducible probability [59] — are not two features but one. Nonlocality is the wavefront's identity (singlet structure under SO(3), j = 1 sector); probability is the wavefront's intensity (Born-rule statistics on 𝒮_t(P), j = 0 sector). The relation between them is the no-signaling theorem stated geometrically (Theorem 9.4.3). Nonlocality and probability are not two postulates of nature; they are two faces of the McGucken Sphere generated by the principle at every emission event.

#### Empirical signature: the forty-year Bell-experiment record

The exact joint conjunction of Tsirelson saturation S_CHSH = 2√2 and marginal-flatness P(a | x) = 1/2 at the level required by Theorem 9.4.3 has been confirmed in every Bell-type experiment performed since 1972, with experimental precision growing as the relevant loopholes have been closed:

| Experiment | Year | Loopholes closed | Distance |
|---|---|---|---|
| Freedman–Clauser [60] | 1972 | (locality and detection open) | ~10 m |
| Aspect–Dalibard–Roger [58] | 1982 | timing/orientation (partial locality) | 6.5 m |
| Weihs et al. [61] | 1998 | locality (strict) | 400 m |
| Hensen et al. [8] | 2015 | locality + detection (loophole-free) | 1.3 km |
| Giustina et al. [9] | 2015 | locality + detection (loophole-free) | hundreds of m |
| Shalm et al. [10] | 2015 | locality + detection (loophole-free) | hundreds of m |
| Yin et al. (Micius) [62] | 2017 | locality at planetary scale | 1200 km satellite |

Every experiment confirms the conjunction of three predictions: (i) Tsirelson saturation, (ii) exact marginal-flatness, and (iii) the precise calibration between (i) and (ii). The McGucken framework predicts the conjunction of (i), (ii), and (iii) as a single geometric theorem (Theorem 9.4.3); standard quantum mechanics has them as three independent algebraic facts whose joint exactness has no underlying explanation. The forty-year empirical record is the empirical signature of dx₄/dt = ic acting at every emission event with full SO(3)-symmetry on the resulting McGucken Sphere.

#### Why the standard algebraic no-signaling theorem cannot supply this content

The Ghirardi–Rimini–Weber [49], Eberhard [50], and Bussey [51] derivations of no-signaling proceed entirely within the algebraic formalism: linearity of QM, completely positive trace-preserving maps, partial trace reducing to the same density matrix regardless of distant operations. None of these ingredients carries geometric information about why the nonlocal correlation should exactly cancel against the marginal-flatness in the way required for no-signaling. The standard derivation works; it does not explain why the calibration is exact rather than approximate. It also does not explain why the nonlocal correlation saturates at 2√2 rather than at some other value below the algebraic no-signaling bound of 4 (the PR-box value [63], which is strictly larger than Tsirelson 2√2).

Both exactness and the Tsirelson saturation value 2√2 are calibrated by the geometry of the McGucken Sphere at the apex event, and the standard algebraic derivation, lacking the geometric content, cannot supply the structural reason for either. The McGucken framework supplies both: the SO(3)-symmetry on 𝒮_t(P) at the apex P forces both the maximal singlet correlation and the flat marginal statistics. The standard algebraic derivation is the partial-trace shadow of the geometric SO(3)-action; the present derivation is the full geometric source.

#### Resolution of the peaceful-coexistence puzzle

Shimony's "peaceful coexistence" [53] of relativity and nonlocality is dissolved at the principle level: there is no coexistence to negotiate, because there is only one geometric fact, read through two algebraic channels. Nonlocality and no-signaling are two readings of the same wavefront on 𝒮_t(P) at the apex P, with the wavefront identity (j = 1 SO(3)-tensor sector) carrying the nonlocal correlation and the wavefront intensity (j = 0 SO(3)-scalar sector) carrying the marginal probability statistics, and the calibration between them being forced by the SO(3)-symmetry of dx₄/dt = ic at the source event P.

The coexistence is peaceful in the strict mathematical sense that it is forced by Lemma 9.4.1 — not by any negotiated balance between two independent constraints. This resolves what Bell [54] called "the real problem with quantum theory: the apparently essential conflict between any sharp formulation [of locality] and fundamental relativity." The apparent conflict dissolves on recognition that the two pillars Bell named — sharp locality (no-signaling) and the empirical Bell-CHSH violation (Theorem 7.3) — are not conflicting but joint shadows of one principle. They are not two; they are one — the SO(3)-invariant singlet wavefront on the McGucken Sphere at the apex event.

### 9.5 Wick Rotation and the Disappearance of the Cone

Under Wick rotation ct ↦ −icτ, the cone equation |**x**|² = c²t² becomes |**x**|² + c²τ² = 0, whose only real solution is the origin. The cone collapses. The geometric nonlocality of the cone, which under Lorentzian signature is the null-degenerate structure along its generators, becomes under Euclidean signature the statement that correlations decay Gaussian ∼ e^(−mr) with no cone singularity. Bell-violating correlations are absent on the Euclidean side: positive measures cannot violate CHSH. Osterwalder–Schrader reflection positivity [27] is the precise axiomatic statement of what extra structure the Euclidean correlators must satisfy to be moments of a Lorentzian QFT with cone structure.

### 9.6 The Photon's View from Null Infinity

From the photon's frame, the affine parameter λ plays the role of "time," but it is defined only up to affine transformation; there is no canonical photon-clock because proper time is identically zero. Emission at P and absorption at Q on the same null generator are not separated by any intrinsic measure the photon itself possesses. The cone is, from the photon's internal perspective, a single locus. This is the covariant restatement of Theorem 4.4.

### 9.7 The First and Second Laws of Nonlocality, Theorem 4.4 as Their Metric Support, and the Falsifiability Test

The metric-level results of this paper — the geometric nonlocality of the null hypersurface (Theorem 4.4), the spacelike separation of the wavefront (Theorem 5.1), the double-slit nonadditivity (Theorem 6.7), and the Bell-CHSH violation as operational signature (Theorem 7.3) — admit a principle-level companion treatment in [42], where two formal laws of nonlocality are stated and an experimental falsifiability test is given. The present subsection states these two laws explicitly, identifies the present paper's theorems as their metric-level and operational-level supports, and articulates the falsifiability test.

#### The First Law: All nonlocality begins in locality

**First McGucken Law of Nonlocality** [42]. *Two quantum systems can exhibit nonlocal correlations (entanglement) only if they have shared a common local origin, or if each has interacted locally with members of a system that itself shared a common local origin.*

The First Law has two parts: a structural claim (nonlocality requires a chain of local interactions tracing back to a common local origin) and a causal claim (the chain is established at subluminal velocity, since each local interaction is itself causally constrained). The First Law is the principle-level statement of what Theorems 4.4, 6.7, and 7.3 of the present paper establish at the metric and operational levels.

*Metric-level support.* Theorem 4.4 establishes that the future light cone 𝒞⁺(P) of any emission event P is a nonlocal manifold: its null generators carry zero proper length, the pullback metric is degenerate along them, and the wavefront W_t(P) is a single null locus from P's standpoint. This is the geometric basis of the First Law: the nonlocality of the wavefront W_t(P) is anchored in the single local event P at its apex. Every point of W_t(P) traces back, along its null generator, to P. The First Law's claim that nonlocality requires a common local origin is the principle-level reading of the metric-level fact that the wavefront's null-hypersurface identity is rooted at the apex of the cone.

*Operational-level support.* Theorems 6.7 and 7.3 establish the two empirical signatures of cone-nonlocality. The double-slit nonadditivity is the single-particle distribution signature, observed in experiments with a single source emitting particles through two slits onto a screen — a single common-origin event with the empirical pattern incompatible with any local-trajectory model. The Bell-CHSH violation is the joint-statistics signature, observed in experiments with entangled pairs created at a single common-origin event — the joint statistics empirically incompatible with any local realist account anchored at the common origin. Both signatures are operational realizations of the First Law: the empirical nonlocality is present *because* the source event is common. In experiments with independent (non-common-origin) sources, no Bell violation and no two-slit nonadditivity is observed, in conformity with the First Law's requirement of a common origin.

#### The Second Law: Nonlocality grows at c

**Second McGucken Law of Nonlocality** [42]. *The spatial extent of nonlocality grows over time, limited by the velocity of light c. At parameter t after a local emission event P, the wavefront W_t(P) has spatial radius ct, and no point outside this radius can share the geometric identity of W_t(P) at parameter t.*

The Second Law states the dynamical content of cone-nonlocality: the cone grows. This is the principle-level reading of the metric-level fact that W_t(P) is a 2-sphere of radius ct in the spatial three-slice at coordinate time t_P + t, as established in Definition 2.2 and used throughout the paper. The growth rate c is built into the definition of the null hypersurface; no spacetime-geometric construction is needed beyond the standard one.

*Metric-level support.* The boundary of W_t(P) as t varies traces out the null cone 𝒞⁺(P), which is precisely the boundary of the causal future of P in Minkowski spacetime. The Second Law's claim that nonlocality grows at c is the principle-level reading of the metric-level fact that the cone's spatial cross-section grows at c by construction.

*Connection to the no-signaling theorem.* The Second Law is structurally compatible with the no-signaling theorem of quantum mechanics: although the Bell-violating correlations on W_t(P) are instantaneous (and therefore not constrained by c in the sense of signal propagation), the establishment of these correlations is constrained by c (since the common origin P must be in the causal past of any subsequent measurement event). The instantaneous-correlations / subluminal-establishment structure of entanglement is the precise dynamical content of the First and Second Laws together: nonlocality is established at c (Second Law), and once established, its correlations are instantaneous within the wavefront's null-geometric identity (operational consequence of Theorem 4.4 via the First Law).

#### The McGucken Sphere as the geometric object on which the Laws operate

Both Laws operate on the same geometric object: the McGucken Sphere 𝒮_t(P) = W_t(P) (Remark 4.8), the 2-sphere of radius ct at parameter t from the emission event P. The First Law says the McGucken Sphere has a common-origin identity (it is anchored at P); the Second Law says the McGucken Sphere grows at c (its radius is ct). The geometric content of both Laws is contained in the McGucken Sphere, which under the McGucken Principle dx₄/dt = ic is the locus of x₄-coincident events at parameter t from P (Proposition 8.5). The two Laws of Nonlocality are therefore both theorems of the principle, derivable from the six-fold geometric identity of the McGucken Sphere (Remark 4.9) and the active expansion of x₄ (Theorem 8.6).

#### The New York–Los Angeles falsifiability test

The First Law of Nonlocality admits a concrete experimental falsifiability test, due to [42]. Let electrons A and B be in two distant laboratories — say, New York and Los Angeles — with all their positions, spins, and momenta continuously measured. The experimentalists determine (by communicating via telephone) that there is no correlation between the measurements on A and B: electrons A and B are not entangled.

**The challenge.** Demonstrate a method for entangling electrons A and B that satisfies all of the following three conditions:

1. Electrons A and B are never brought into direct local contact.
2. No intermediary particle or system that has shared a local origin with itself is used to mediate the entanglement.
3. The entanglement is established faster than the velocity of light: no waiting period is required for any signal or system to travel from one laboratory to the other.

**Falsification criterion.** If such a method can be demonstrated — experimentally or even in a thought experiment consistent with the known laws of physics — then the First Law of Nonlocality is falsified, and with it the geometric-nonlocality reading of the present paper. If no such method can be found, then the First Law stands.

**Why the challenge cannot be met within known physics.** Every known method for entangling distant particles requires a locally-originated intermediary. The standard procedure is entanglement swapping [44, 45]: prepare two locally-created entangled pairs (C, D) and (E, F), transport C to New York and F to Los Angeles, have C interact locally with A and F interact locally with B, then perform a Bell-state measurement on (D, E) at an intermediate location. After the Bell-state measurement, electrons A and B become entangled, but only because the chain of local interactions A↔C, C↔D (at creation), D↔E (at measurement), E↔F (at creation), F↔B connects them through a sequence of locally-originated contacts. Every step in this chain involves local contact. The chain's existence is subluminal: each particle's transport is at subluminal velocity, each interaction is at a local event. The final A–B entanglement is instantaneous in its correlations once established, but its establishment required a chain of local contacts whose total causal extent is constrained by c. The First Law is conformed-to.

No alternative method has been proposed in any interpretation of quantum mechanics, in any extension of the Standard Model, or in any thought experiment that creates entanglement between distant particles without a chain of local contacts originating in a common locality [42]. The First Law of Nonlocality is not merely unfalsified empirically; it appears to be unfalsifiable within the known laws of physics, because those laws themselves enforce it. The geometric-nonlocality reading of the present paper supplies the structural explanation of why: the geometric identity of the wavefront W_t(P) is anchored at the local event P (Theorem 4.4), so any nonlocal correlation traceable to that wavefront is necessarily traceable to the local event at its apex. The First Law is the principle-level reading of this metric-level structural fact.

#### Extension to Wheeler delayed-choice and quantum eraser

The double-slit nonadditivity proved in Theorem 6.7 extends, under the McGucken Principle, to Wheeler's delayed-choice experiment [21] and to quantum eraser experiments [46, 47]. The principle-level treatment in [42] establishes that all three experiments — double-slit, delayed-choice, and quantum eraser — take place within a single McGucken Sphere 𝒮_t(P) (or, in entanglement-swapping variants, within a chain of intersecting McGucken Spheres). The apparent paradoxes of these experiments — "which path does the particle take?" (double-slit), "does the future measurement choice influence the past behavior?" (delayed-choice), "can the choice to erase which-path information retroactively restore interference?" (quantum eraser) — dissolve once the experiments are recognized as taking place within the expanding x₄-coincident geometry of a single McGucken Sphere. In the photon's frame, there is no time and no distance between the source event, the slit-passage events, the delayed-choice events, and the detection events; all are at the same x₄-coincident locus on 𝒮_t(P) (Definition 8.4, Proposition 8.5).

The present paper proves only the double-slit case rigorously (Theorem 6.7); the delayed-choice and quantum eraser extensions are developed in [42]. The structural argument is identical in all three cases: the experiment is hosted on a single McGucken Sphere; the wavefront on the sphere is a single nonlocal state; the apparent temporal paradoxes are artifacts of imposing a three-dimensional temporal ordering on a four-dimensional geometric process that admits no such ordering in the photon's frame.

#### Closing remark on logical structure

The present paper's metric-level theorems (Theorems 4.4, 5.1, 6.7, 7.3) and the principle-level Laws of Nonlocality stated in [42] stand in the following logical relationship:

- Theorem 4.4 is the *metric-level support* for both Laws: it establishes that the wavefront W_t(P) = 𝒮_t(P) is a nonlocal manifold (First Law) and that it grows at c (Second Law).
- Theorems 6.7 and 7.3 are the *operational signatures* that the Laws have empirical content: the failure of additivity in double-slit interference and the violation of the CHSH inequality in common-origin pairs are the empirically observed shadows of the geometric nonlocality.
- The McGucken Principle dx₄/dt = ic (Section 8) is the *active mechanism* underlying both Laws: the x₄-expansion at velocity ic from every emission event is what makes every emission a nonlocal-creating event, and what makes the cone the locus of x₄-coincidence.

The present paper, read together with [42], supplies the complete formal architecture for cone-nonlocality: metric-level theorems, operational signatures, principle-level laws, and active mechanism, with the McGucken Sphere 𝒮_t(P) = W_t(P) as the geometric object on which all four levels of structure are unified.

## 10. Conclusion

We have proven that the Minkowski metric alone, without any empirical or quantum-mechanical input, forces the conclusion that the future light cone 𝒞⁺(P) of any emission event is a nonlocal manifold (Theorem 4.4). Every two events on the same null generator, including the apex itself, are at zero proper length from each other; the pullback metric on the null hypersurface is degenerate with null direction the generator tangent; and the hypersurface admits no Riemannian distance function along its null directions.

The spacelike-separation lemma (Theorem 5.1) complements this fact: distinct generators are maximally separated transversally, with no event X ≠ P in the common causal past of two distinct wavefront points after P. The cone is the locus where these two extremes meet — null-degenerate along its generators, spacelike-extended across them.

Given the experimentally established double-slit nonadditivity (Theorem 6.7), no local trajectory model of single-particle propagation through two slits from a common source can reproduce the observed pattern. The double-slit interference is the operational signature of the prior geometric nonlocality in the single-particle distribution form. Given the experimentally established CHSH-violation (Theorem 7.3), no local realist account of joint detector statistics on common-origin pairs is possible. The Bell violation is the operational signature of the prior geometric nonlocality in the joint-statistics form. Both are operational shadows of one geometric source: the cone is already nonlocal as geometry; any field theory or single-particle wavefunction living on it inherits distributions that no positive measure on a classical sample space can reproduce. The double-slit signature has been empirically established since Young 1801; the Bell–CHSH signature has been empirically established since 1964/2015. The geometric source has been visible since Minkowski 1908.

Under the McGucken Principle dx₄/dt = ic (Theorem 8.6), the geometric nonlocality is a theorem of the active x₄-expansion. The cone's null-degenerate structure is the cancellation of x₄-advance and spatial propagation along its generators; the wavefront is the instantaneous front of the isotropic expansion; the Bell-violating correlations and the double-slit nonadditivity are the operational forms of x₄-coincidence in two complementary settings. The role of i is to encode orthogonality; the role of c is to encode the rate; the Lorentzian metric arises from these two by the principle's integration.

The historical record (Section 3) shows that the pieces of this result have been on the table for over two centuries. Young's 1801 double-slit experiment established the operational nonlocality of common-origin propagation 107 years before Minkowski had a spacetime geometry to anchor it to. Poincaré's 1905–06 imaginary-time coordinate and Minkowski's 1908 light cone supplied the geometric structure 56 years before Bell's 1964 theorem refined the operational signature into a quantitative inequality. Penrose's 1967 twistor program made null structure primitive 59 years before the present paper. In all this history, no one assembled the geometric source and the operational signatures into a derivation. The reasons are several — disciplinary split between operational quantum mechanics and geometric relativity, the no-signaling theorem reading the cone as a constraint, the conformal-symmetry reading of the null hypersurface, the path-integral framing of double-slit, the static reading of twistor theory — but none of them was forced. The present paper closes the gap.

Canonical formulation: *every theorem traces to the active expansion; the coordinate label x₄ = ict is its mere integrated shadow*. The geometric nonlocality of the null hypersurface, the spacelike separation of the wavefront, the double-slit nonadditivity of single-particle distributions, the Bell-violating correlations of common-origin pairs, and the no-signaling theorem are five faces of one fact: dx₄/dt = ic.

## References

[1] H. Minkowski, "Raum und Zeit," lecture delivered at the 80th Assembly of German Natural Scientists and Physicians, Köln, 21 September 1908; published in *Physikalische Zeitschrift* **10**, 75–88 (1909).

[33] T. Young, "The Bakerian Lecture: experiments and calculations relative to physical optics," *Philosophical Transactions of the Royal Society of London* **94**, 1–16 (1804); lecture delivered 24 November 1803, presenting the experimental results of 1801.

[34] C. Davisson and L. H. Germer, "Diffraction of electrons by a crystal of nickel," *Phys. Rev.* **30**, 705–740 (1927).

[35] C. Jönsson, "Elektroneninterferenzen an mehreren künstlich hergestellten Feinspalten," *Zeitschrift für Physik* **161**, 454–474 (1961); English translation: "Electron diffraction at multiple slits," *American Journal of Physics* **42**, 4–11 (1974).

[36] A. Tonomura, J. Endo, T. Matsuda, T. Kawasaki, and H. Ezawa, "Demonstration of single-electron buildup of an interference pattern," *American Journal of Physics* **57**, 117–120 (1989).

[37] H. Poincaré, "Sur la dynamique de l'électron," *Comptes Rendus* **140**, 1504–1508 (1905).

[38] H. Poincaré, "Sur la dynamique de l'électron," *Rendiconti del Circolo Matematico di Palermo* **21**, 129–176 (1906).

[2] A. Einstein, B. Podolsky, and N. Rosen, "Can quantum-mechanical description of physical reality be considered complete?" *Phys. Rev.* **47**, 777–780 (1935).

[3] D. Bohm, *Quantum Theory* (Prentice-Hall, Englewood Cliffs, NJ, 1951).

[4] J. S. Bell, "On the Einstein Podolsky Rosen paradox," *Physics* **1**, 195–200 (1964).

[5] J. F. Clauser, M. A. Horne, A. Shimony, and R. A. Holt, "Proposed experiment to test local hidden-variable theories," *Phys. Rev. Lett.* **23**, 880–884 (1969).

[6] B. S. Tsirelson, "Quantum generalizations of Bell's inequality," *Lett. Math. Phys.* **4**, 93–100 (1980).

[7] A. Aspect, J. Dalibard, and G. Roger, "Experimental test of Bell's inequalities using time-varying analyzers," *Phys. Rev. Lett.* **49**, 1804–1807 (1982).

[8] B. Hensen et al., "Loophole-free Bell inequality violation using electron spins separated by 1.3 kilometres," *Nature* **526**, 682–686 (2015).

[9] M. Giustina et al., "Significant-loophole-free test of Bell's theorem with entangled photons," *Phys. Rev. Lett.* **115**, 250401 (2015).

[10] L. K. Shalm et al., "Strong loophole-free test of local realism," *Phys. Rev. Lett.* **115**, 250402 (2015).

[11] R. Penrose, "Twistor algebra," *J. Math. Phys.* **8**, 345–366 (1967).

[12] R. Penrose and W. Rindler, *Spinors and Space-Time, Vol. 1: Two-Spinor Calculus and Relativistic Fields* (Cambridge University Press, Cambridge, 1984).

[13] R. Penrose and W. Rindler, *Spinors and Space-Time, Vol. 2: Spinor and Twistor Methods in Space-Time Geometry* (Cambridge University Press, Cambridge, 1986).

[14] E. T. Newman and R. Penrose, "An approach to gravitational radiation by a method of spin coefficients," *J. Math. Phys.* **3**, 566–578 (1962).

[15] R. K. Sachs, "Gravitational waves in general relativity. VI. The outgoing radiation condition," *Proc. Roy. Soc. A* **264**, 309–338 (1961).

[16] H. Bondi, M. G. J. van der Burg, and A. W. K. Metzner, "Gravitational waves in general relativity. VII. Waves from axi-symmetric isolated systems," *Proc. Roy. Soc. A* **269**, 21–52 (1962).

[17] R. K. Sachs, "Gravitational waves in general relativity. VIII. Waves in asymptotically flat space-time," *Proc. Roy. Soc. A* **270**, 103–126 (1962).

[18] R. Penrose, *The Emperor's New Mind: Concerning Computers, Minds, and the Laws of Physics* (Oxford University Press, Oxford, 1989).

[19] R. Penrose, *Shadows of the Mind: A Search for the Missing Science of Consciousness* (Oxford University Press, Oxford, 1994).

[20] R. Penrose, *The Road to Reality: A Complete Guide to the Laws of the Universe* (Jonathan Cape, London, 2004).

[21] J. A. Wheeler, "The 'past' and the 'delayed-choice' double-slit experiment," in *Mathematical Foundations of Quantum Theory*, edited by A. R. Marlow (Academic Press, New York, 1978).

[22] J. A. Wheeler, "Law without law," in *Quantum Theory and Measurement*, edited by J. A. Wheeler and W. H. Zurek (Princeton University Press, Princeton, 1983).

[23] J. A. Wheeler, "Information, physics, quantum: the search for links," in *Complexity, Entropy, and the Physics of Information*, edited by W. Zurek (Addison-Wesley, Redwood City, 1990).

[24] C. W. Misner, K. S. Thorne, and J. A. Wheeler, *Gravitation* (W. H. Freeman, San Francisco, 1973).

[25] R. M. Wald, *General Relativity* (University of Chicago Press, Chicago, 1984).

[39] S. M. Carroll, *Spacetime and Geometry: An Introduction to General Relativity* (Addison Wesley, San Francisco, 2004); open-source precursor *Lecture Notes on General Relativity*, arXiv:gr-qc/9712019 (1997).

[40] B. F. Schutz, *A First Course in General Relativity*, 2nd ed. (Cambridge University Press, Cambridge, 2009); first edition 1985.

[41] S. Weinberg, *Gravitation and Cosmology: Principles and Applications of the General Theory of Relativity* (Wiley, New York, 1972).

[26] S. W. Hawking and G. F. R. Ellis, *The Large Scale Structure of Space-Time* (Cambridge University Press, Cambridge, 1973).

[27] K. Osterwalder and R. Schrader, "Axioms for Euclidean Green's functions," *Commun. Math. Phys.* **31**, 83–112 (1973); **42**, 281–305 (1975).

[28] E. McGucken, "The McGucken Principle: the fourth dimension is expanding at the velocity of light c, dx₄/dt = ic, the McGucken proof," elliotmcguckenphysics.com (25 October 2024). https://elliotmcguckenphysics.com/2024/10/25/the-mcgucken-principle-the-fourth-dimension-is-expanding-at-the-velocity-of-light-c-dx4-dtic-the-mcgucken-proof/

[42] E. McGucken, "The McGucken Nonlocality Principle: All Quantum Nonlocality Begins in Locality, and All Double Slit, Entanglement, Quantum Eraser, and Delayed Choice Experiments Exist in McGucken Spheres," elliotmcguckenphysics.com (17 April 2026). https://elliotmcguckenphysics.com/2026/04/17/the-mcgucken-nonlocality-principle-all-quantum-nonlocality-begins-in-locality-and-all-double-slit-quantum-eraser-and-delayed-choice-experiments-exist-in-mcgucken-spheres/

[43] C. Huygens, *Traité de la lumière* (Pieter van der Aa, Leiden, 1690); English translation by S. P. Thompson, *Treatise on Light* (Macmillan, London, 1912).

[44] M. Żukowski, A. Zeilinger, M. A. Horne, and A. K. Ekert, "'Event-ready-detectors' Bell experiment via entanglement swapping," *Phys. Rev. Lett.* **71**, 4287–4290 (1993).

[45] J.-W. Pan, D. Bouwmeester, H. Weinfurter, and A. Zeilinger, "Experimental entanglement swapping: entangling photons that never interacted," *Phys. Rev. Lett.* **80**, 3891–3894 (1998).

[46] M. O. Scully and K. Drühl, "Quantum eraser: a proposed photon correlation experiment concerning observation and 'delayed choice' in quantum mechanics," *Phys. Rev. A* **25**, 2208–2213 (1982).

[47] Y.-H. Kim, R. Yu, S. P. Kulik, Y. Shih, and M. O. Scully, "Delayed 'choice' quantum eraser," *Phys. Rev. Lett.* **84**, 1–5 (2000).

[48] E. McGucken, "The McGucken Point (MGP), dx₄/dt = ic: the axiomatic atom of spacetime, general relativity, quantum mechanics, the symmetries, conservation laws, action, nonlocality, entanglement, the vacuum," elliotmcguckenphysics.com (19 May 2026). https://elliotmcguckenphysics.com/2026/05/19/the-mcgucken-point-mcp-dx%e2%82%84-dt-ic-the-axiomatic-atom-of-spacetime-general-relativity-quantum-mechanics-the-symmetries-conservation-laws-action-nonlocality-entanglement-the-vacuu/

[49] G. C. Ghirardi, A. Rimini, and T. Weber, "A general argument against superluminal transmission through the quantum mechanical measurement process," *Lett. Nuovo Cimento* **27**, 293–298 (1980).

[50] P. H. Eberhard, "Bell's theorem and the different concepts of locality," *Nuovo Cimento B* **46**, 392–419 (1978).

[51] P. J. Bussey, "'Super-luminal communication' in Einstein–Podolsky–Rosen experiments," *Phys. Lett. A* **90**, 9–12 (1982).

[52] B. S. Tsirelson, "Quantum generalizations of Bell's inequality," *Lett. Math. Phys.* **4**, 93–100 (1980).

[53] A. Shimony, "Metaphysical problems in the foundations of quantum mechanics," *International Philosophical Quarterly* **18**, 3–17 (1978).

[54] J. S. Bell, *Speakable and Unspeakable in Quantum Mechanics* (Cambridge University Press, Cambridge, 1987).

[55] E. P. Wigner, *Group Theory and Its Application to the Quantum Mechanics of Atomic Spectra* (Academic Press, New York, 1959).

[56] A. M. Gleason, "Measures on the closed subspaces of a Hilbert space," *J. Math. Mech.* **6**, 885–893 (1957).

[57] M. A. Nielsen and I. L. Chuang, *Quantum Computation and Quantum Information*, 10th Anniversary ed. (Cambridge University Press, Cambridge, 2010).

[58] A. Aspect, J. Dalibard, and G. Roger, "Experimental test of Bell's inequalities using time-varying analyzers," *Phys. Rev. Lett.* **49**, 1804–1807 (1982).

[59] M. Born, "Zur Quantenmechanik der Stoßvorgänge," *Zeitschrift für Physik* **37**, 863–867 (1926); English translation in J. A. Wheeler and W. H. Zurek (eds.), *Quantum Theory and Measurement* (Princeton University Press, 1983), pp. 52–55.

[60] S. J. Freedman and J. F. Clauser, "Experimental test of local hidden-variable theories," *Phys. Rev. Lett.* **28**, 938–941 (1972).

[61] G. Weihs, T. Jennewein, C. Simon, H. Weinfurter, and A. Zeilinger, "Violation of Bell's inequality under strict Einstein locality conditions," *Phys. Rev. Lett.* **81**, 5039–5043 (1998).

[62] J. Yin et al., "Satellite-based entanglement distribution over 1200 kilometers," *Science* **356**, 1140–1144 (2017).

[63] S. Popescu and D. Rohrlich, "Quantum nonlocality as an axiom," *Found. Phys.* **24**, 379–385 (1994).

[29] E. McGucken, "How the McGucken Principle of a fourth expanding dimension resolves the open problems of Witten's twistor programme: dx₄/dt = ic as the physical mechanism underlying perturbative gauge theory," elliotmcguckenphysics.com (20 April 2026). https://elliotmcguckenphysics.com/2026/04/20/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-resolves-the-open-problems-of-wittens-twistor-programme-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-perturbative-gauge-theory/

[30] E. McGucken, "The McGucken Principle dx₄/dt = ic necessitates the Wick rotation and i throughout physics: a reduction of thirty-four independent inputs of quantum field theory, quantum mechanics, and symmetry physics," elliotmcguckenphysics.com (1 May 2026). https://elliotmcguckenphysics.com/2026/05/01/the-mcgucken-principle-dx4-dtic-necessitates-the-wick-rotation-and-i-throughout-physics-a-reduction-of-thirty-four-independent-inputs-of-quantum-field-theory-quantum-mechanics-and-symmetry-physics/

[31] E. McGucken, "The McGucken Geometry: a novel mathematical category exalted by the principle-axiom dx₄/dt = ic, wherein an axis is physically expanding in a spherically symmetric manner," elliotmcguckenphysics.com (5 May 2026). https://elliotmcguckenphysics.com/2026/05/05/the-mcgucken-geometry-a-novel-mathematical-category-exalted-by-the-principle-axiom-dx%e2%82%84-dt-ic-wherein-an-axis-is-physically-expanding-in-a-spherically-symmetric-manner-and-exalting-general/

[32] E. McGucken, "GR's Einstein field equations, QM's canonical commutation relation, and the second law of thermodynamics unified as three instances of one theorem of dx₄/dt = ic," elliotmcguckenphysics.com (12 May 2026). https://elliotmcguckenphysics.com/2026/05/12/grs-einstein-field-equations-qms-canonical-commutation-relation-and-the-second-law-of-thermodynamics-unified-as-three-instances-of-one-theorem-of-dx%e2%82%84-dt-ic-the-unification-/
