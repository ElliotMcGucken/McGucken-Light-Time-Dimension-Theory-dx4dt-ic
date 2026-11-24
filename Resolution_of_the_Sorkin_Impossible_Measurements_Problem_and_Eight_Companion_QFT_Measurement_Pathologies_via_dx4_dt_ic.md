# Resolution of the Sorkin Impossible-Measurements Problem and Eight Companion QFT Measurement Pathologies as Theorems of the McGucken Principle dx₄/dt = ic

**Dr. Elliot McGucken**

*Light Time Dimension Theory*

*elliotmcguckenphysics.com*

*May 2026*

*More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet for graduate school in physics.*

*— Dr. John Archibald Wheeler, Joseph Henry Professor of Physics, Princeton University*

*Behind it all is surely an idea so simple, so beautiful, that when we grasp it — in a decade, a century, or a millennium — we will all say to each other, how could it have been otherwise?*

*— John Archibald Wheeler*

---

## Abstract

The Sorkin impossible-measurements problem (1993) shows that ideal projective measurement of bounded-region observables in standard relativistic quantum field theory generically forces superluminal signaling: a measurement performed by Alice in one bounded region propagates a state-update through Bob's region at unbounded speed when an intermediate state-update by Charlie connects the two. The problem has driven a thirty-three-year program — Sorkin (1993), Borsten–Jubb–Kells (2021), Bostelmann–Fewster–Ruep (2021), Fewster–Verch (2020), Polo-Gómez–Garay–Martín-Martínez (2022), de Ramón–Papageorgiou–Martín-Martínez (2021), Mandrysch–Navascués (2024), Papageorgiou–Fraser (2024), Fewster (2025) — without yielding a single mechanism that simultaneously (i) eliminates Sorkin signaling, (ii) preserves Reeh–Schlieder vacuum entanglement as a real algebraic feature, (iii) accommodates Bell-correlation experiments, (iv) reconciles Lamb's anti-photon argument with photon-quantization formalism, (v) handles the BMV gravity-induced entanglement protocol, (vi) does so without ad-hoc modification of the field algebra, and (vii) addresses the broader catalog of QFT measurement pathologies catalogued by Martín-Martínez and collaborators.

The present paper resolves the Sorkin problem and eight companion pathologies as theorems of a single physical principle established and developed in the McGucken corpus over thirty-seven years: the McGucken Principle, dx₄/dt = ic, which states that the fourth coordinate x₄ = ict of Minkowski spacetime is a real geometric axis advancing at the invariant rate ic, with the advance proceeding from every spacetime event simultaneously and spherically symmetrically about each event. From this principle, the McGucken Sphere as foundational atom of spacetime [MG-Sphere], the Brillouin-zone confinement of x₄-momenta on the discrete-x₄ Planck-scale lattice [MG-Vanquishing], the McGucken Causal Completion and resulting algebraic microcausality theorem [MG-Sphere §15], the Two Laws of Nonlocality [MG-Nonlocality], the Born rule as McGucken-Sphere projection [MG-Born], and the Wick rotation as coordinate identification τ = x₄/c [MG-Wick] are all derived as theorems. The Sorkin problem and its eight companions resolve as direct consequences.

The resolution mechanism is **structural, not perturbative**. The hybrid spacetime measure dμ = d³x · a₄ Σₙ δ(x₄ − na₄) dx₄ with lattice spacing a₄ = λ_P forces every test function f̃ supporting a smeared bounded-region operator O_f to have momentum-space support contained in ℝ³ × B, where B = [−πℏ/λ_P, +πℏ/λ_P] is the first Brillouin zone in the dual variable to x₄. This is a **support theorem**, not a spectrum theorem: spec(O_f) ⊂ ℝ is a set of eigenvalues, while supp(f̃) ⊂ ℝ³ × B is a property of the smearing test function on the Pontryagin dual of the substrate. The two are distinct objects, and the existing literature has conflated them; the correction is given here. The dispersion relation along the discrete x₄ direction follows separately and is stated explicitly.

The dimensional content of the Brillouin zone is similarly corrected. The relation ℏ/λ_P = m_P c is a statement about **momentum**, not energy: m_P c has units of momentum (mass × velocity), while m_P c² has units of energy. The Brillouin zone B in the dual to x₄ is therefore a momentum interval of width 2πm_P c = 2πℏ/λ_P, not an energy interval of width 2πm_P c². Energy bounds, where invoked, follow from the dispersion relation along x₄ and require explicit statement. This correction is propagated throughout.

The nine resolved problems are: (1) operational meaning of clocks/rulers at the Planck scale; (2) wave-function collapse incompatible with relativity; (3) the Sorkin impossible-measurements problem proper; (4) the Reeh–Schlieder vacuum-entanglement puzzle; (5) the Bell-violation locality/realism dilemma; (6) photon non-localizability and Lamb's anti-photon argument; (7) QFT presupposing a classical general-relativistic background; (8) gravity-induced entanglement (BMV); (9) general relativity predicting its own breakdown. Each is resolved by the McGucken framework via a specific theorem of dx₄/dt = ic. None requires modification of the field algebra; none requires nonstandard quantization; none requires a graviton.

**Keywords:** *McGucken Principle; Sorkin impossible measurements; algebraic QFT; Reeh–Schlieder; Bell correlations; BMV gravity-induced entanglement; Brillouin zone; hybrid spacetime measure; McGucken Sphere; McGucken Causal Completion; Light Time Dimension Theory; dx₄/dt = ic.*

---

## I. Introduction

### I.1 The Sorkin problem and its thirty-three-year context

In 1993 Sorkin demonstrated that the natural extension of Lüders' projective measurement rule to relativistic quantum field theory is in tension with relativistic causality [Sorkin1993]. Concretely: let Alice, Bob, and Charlie be three observers occupying disjoint bounded spacetime regions R_A, R_B, R_C with Alice and Bob spacelike separated and Charlie causally between them. Suppose Charlie performs an ideal projective ("Lüders") measurement of a local operator P_C in R_C. Then there exist choices of test operators O_A, O_B such that the conditional expectation value of O_B given Alice's choice of operator O_A depends on Alice's choice — a violation of no-signaling. The problem is structural: it follows from (i) the Reeh–Schlieder vacuum-entanglement theorem [ReehSchlieder1961, Witten2018], which implies that the local algebra in any open region is type III and entangling; (ii) the Lüders projection rule; and (iii) the geometry of three bounded regions in Minkowski spacetime.

Three responses dominate the subsequent literature. The first, due principally to Borsten, Jubb, and Kells [BJK2021] and Bostelmann, Fewster, and Ruep [BFR2021], shows that the Sorkin pathology is generic for ideal Lüders measurements but can be regulated by restricting attention to "compatible" or "selective" measurement sequences. The second, developed by de Ramón, Papageorgiou, Martín-Martínez, and collaborators [dRPM2021, PGM2022, PF2024] in the FLAMM framework (Fully Localized Algebraic Measurement Model) and by Fewster and Verch [FV2020] in the Verch–Fewster operational framework, replaces Lüders measurement by a measurement model tied to a probe field localized in a bounded region, eliminating the Sorkin-type signaling at the cost of altering the operational meaning of measurement. The third, lately advanced by Mandrysch and Navascués [MN2024] and reviewed in Fewster's 2025 lectures [Fewster2025], explores "QFT-compatible" measurement schemes via direct restriction of admissible operators. Each approach addresses Sorkin's problem in isolation; none addresses it within a framework that simultaneously resolves the broader catalog of QFT measurement pathologies catalogued by Martín-Martínez (see [PF2024] §1 and references therein).

### I.2 The eight companion problems

The Martín-Martínez catalog frames the Sorkin problem as one entry in a broader pathology list. We identify nine entries, of which the Sorkin problem is the third:

1. **Operational meaning of clocks and rulers at Planck scale.** Quantum field theory in a continuum spacetime requires arbitrarily-fine spatiotemporal resolution; gravitation imposes a Planck-scale floor [Doplicher1995]. The two are in tension at length scales below ~10⁻³⁵ m.

2. **Wave-function collapse incompatible with relativity.** A state collapse triggered by a measurement at Alice's spacetime location, propagating instantaneously to Bob's, is in tension with Lorentz invariance [Penrose1989, Bell1990].

3. **Sorkin's impossible-measurements problem.** As above [Sorkin1993].

4. **Reeh–Schlieder vacuum entanglement.** The Minkowski vacuum is cyclic and separating for every local algebra A(O); local operators applied to |0⟩ generate a dense subspace of the entire Hilbert space, and the local algebras are entangled across spacelike separation [ReehSchlieder1961, Witten2018]. The physical content of this vacuum entanglement — what it means to extract entanglement from the vacuum, whether the vacuum is "really" entangled, and why entanglement-harvesting protocols work — has been disputed for sixty-five years.

5. **Bell-violation locality/realism dilemma.** Bell-inequality violations [Bell1964, Aspect1982, Hensen2015] force at least one of: signal locality, statistical independence (no superdeterminism), or realism. Standard QFT preserves signal locality but at the cost of a non-realist ontology of measurement outcomes.

6. **Photon non-localizability.** Lamb [Lamb1995] argues that the photon is not a well-defined quantum particle: it has no position operator, no Newton–Wigner localization in three dimensions, and the standard "photon" of QED is a Fock-space excitation rather than a spatially localized object. The standard formulation of QED contradicts the experimentally-grounded photon picture by attempting to localize a non-localizable object.

7. **QFT presupposes a classical general-relativistic background.** Quantum field theory on curved spacetime takes the metric as classical; quantum gravity (in any of its formulations) requires the metric to be quantized. The mismatch between a quantum source (the matter stress-energy) and a classical receiver (the metric) is structural to the formalism [Wald1994].

8. **Gravity-induced entanglement (BMV).** Bose, Mazumdar, Marletto, and Vedral [Bose2017, MV2017] have proposed that two test masses can be entangled via gravitational coupling alone; the experiment, if successful, would directly demonstrate the quantum nature of gravity. A field-theoretic account requires either a graviton mediator (problematic for IR-divergence reasons) or a non-mediator account of the entanglement.

9. **General relativity predicts its own breakdown.** The Schwarzschild solution contains a curvature singularity at r = 0; the general Penrose–Hawking singularity theorems [Penrose1965, Hawking1970] show this is generic. The theory predicts where its own predictions fail.

### I.3 The McGucken Principle as common foundation

The thesis of the present paper is that all nine problems above are theorems of a single physical principle, the McGucken Principle, established in the author's continuous research program from undergraduate work at Princeton University in the late 1980s [MG-PrincetonAfternoons], through dissertation work at the University of North Carolina at Chapel Hill (1998–1999) [MG-Dissertation], FQXi essays (2008–2013) [MG-FQXi-2008, MG-FQXi-2009, MG-FQXi-2010, MG-FQXi-2012, MG-FQXi-2013], book series (2016–2017) [McGucken2016, McGucken2017a, McGucken2017b, McGucken2017c, McGucken2017d], and the active derivation program of October 2024 through May 2026 (~40 papers at elliotmcguckenphysics.com). The Principle is:

**Principle (The McGucken Principle).** *The fourth coordinate x₄ = ict of Minkowski spacetime is a real geometric axis. It advances at the invariant rate*
$$dx_4/dt = ic.$$
*The advance proceeds from every spacetime event p ∈ M simultaneously, spherically symmetrically about each event, with magnitude |dx₄/dt| = c invariant under Lorentz transformations.*

Minkowski introduced x₄ = ict in 1908 [Minkowski1908] as the coordinate making the spacetime interval take Euclidean form. The identity was treated for a century as notational convenience. The McGucken Principle promotes it to a physical statement: x₄ is a real geometric axis, its advance at rate ic is a physical process, and the imaginary unit is the algebraic marker of x₄'s perpendicularity to the three spatial dimensions [MG-Commut, MG-Wick].

Critical structural results derived from this principle in the McGucken corpus, used as inputs to the present paper:

– The McGucken Sphere as foundational atom of spacetime, deriving the amplituhedron and twistors [MG-Sphere];
– The hybrid spacetime measure dμ = d³x · a₄ Σₙ δ(x₄ − na₄) dx₄ with a₄ = λ_P, and the resulting Brillouin-zone confinement of x₄-conjugate momenta to B = [−πℏ/λ_P, +πℏ/λ_P] [MG-Vanquishing];
– The McGucken Causal Completion and algebraic microcausality theorem [MG-Sphere §15];
– The Two Laws of Nonlocality and the six-fold null-surface identity [MG-Nonlocality];
– The Born rule as McGucken-Sphere projection [MG-Born];
– The Wick rotation as coordinate identification τ = x₄/c [MG-Wick];
– The Feynman propagator as x₄-coherent Huygens kernel; vertices as McGucken-Sphere intersections; the Dyson expansion as iterated Huygens-with-interaction [MG-Feynman].

We do not re-derive these results. We invoke them as theorems and apply them to the nine problems.

### I.4 Two errors corrected from the prior published treatment

A prior version of the present analysis [hereafter "the May 9 draft"] contained two technical errors that warrant explicit correction.

**Error 1 — dimensional confusion in the Brillouin zone.** The May 9 draft repeatedly identified πℏ/λ_P with πm_P c² and stated the Brillouin zone width as πm_P c² with units of energy. This is dimensionally wrong. From λ_P = √(ℏG/c³) and m_P = √(ℏc/G) one obtains ℏ/λ_P = √(ℏ²/(ℏG/c³)) = √(ℏc³/G) = c · √(ℏc/G) = m_P c. Therefore ℏ/λ_P = m_P c is a momentum, not an energy, and the Brillouin zone in the dual variable to x₄ is a **momentum** interval B = [−πm_P c, +πm_P c] = [−πℏ/λ_P, +πℏ/λ_P]. Energy bounds at the Planck scale must be derived separately from the dispersion relation along the discrete x₄ axis (see §III.4 below). The corrected statement is propagated throughout.

**Error 2 — confusing spectrum with support.** The May 9 draft stated as "Theorem 1" that for any operator O_f smeared by a test function f against a McGucken-substrate-compatible field, the spectrum spec(O_f) is contained in ℝ³ × B. This is a category error: spec(O_f) is a subset of ℝ (or ℂ) — the eigenvalue set of a linear operator on Hilbert space — while ℝ³ × B is a region in spacetime momentum-space. The correct statement, derived rigorously in §III below, is a **support theorem**: for any test function f satisfying the substrate-compatibility condition, the four-dimensional Fourier transform f̃ has support contained in ℝ³ × B. The two statements are unambiguously distinct, and only the second is implied by the McGucken framework. We give the corrected proof below.

A third issue identified — the use of the Riemann–Lebesgue lemma in the May 9 draft to claim decay of correlation functions on a compact region where Riemann–Lebesgue gives only continuity — is corrected in §V.3 below by replacing the Riemann–Lebesgue invocation with an explicit bound from rapid-decrease (Schwartz) test-function smoothness, which is the actual hypothesis available in the FLAMM measurement model and in Sven's intended usage.

### I.5 Structure of the paper

§II states the McGucken Principle and the kinematical facts inherited from [MG-Sphere], [MG-Nonlocality], [MG-Vanquishing], [MG-Wick], [MG-Born], [MG-Feynman]. §III gives the corrected Brillouin-zone support theorem with explicit dimensional treatment. §IV develops the McGucken Causal Completion and the algebraic microcausality theorem from [MG-Sphere §15]. §V is a dedicated treatment of microcausality, commutators, and the Pauli–Jordan function, showing in detail how the standard QFT axiom on $[\hat\varphi(x), \hat\varphi(y)] = 0$ for spacelike separation becomes a theorem in the McGucken framework. §VI resolves the Sorkin problem proper. §VII addresses the Maudlin–Das spin-dependent arrival-time signaling claim via the McGucken No-Signaling Theorem (Theorem VII.3), establishing that the Bohmian arrival-time prediction of Alice-dependent shifts in Bob's marginal distribution is denied by the geometric SO(3) symmetry of the source-event Sphere. §§VIII–XV then resolve the remaining problems in order: §VIII Reeh–Schlieder; §IX Bell; §X the photon localizability problem and Lamb's argument; §XI the Planck-scale clocks/rulers problem; §XII the wave-function collapse problem; §XIII the QFT-on-curved-background mismatch; §XIV gravity-induced entanglement (BMV); §XV general relativity predicting its own breakdown. §XVI summarizes the resolution structure and lists falsifiable predictions. §XVII concludes.

---

## II. The McGucken Principle and the Required Kinematical Inputs

This section collects the theorems of dx₄/dt = ic that are used as inputs to the resolution of the nine problems. Every result in this section is proved in the cited McGucken paper and is reproduced here only as a statement.

### II.1 Notation and Postulate

We work in Minkowski spacetime (M, η) with signature η = diag(−1, +1, +1, +1). Coordinates are x^μ = (ct, x, y, z), with x₄ = ict making the fourth coordinate explicit. The line element takes either of the equivalent forms

$$ds^2 = dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2 \quad \text{(Euclidean form)}$$
$$ds^2 = dx_1^2 + dx_2^2 + dx_3^2 - c^2 dt^2 \quad \text{(Minkowski form)}$$

The two forms are algebraically identical under x₄ = ict, since dx₄² = (ic)² dt² = −c² dt².

**Postulate (The McGucken Principle, restated).** *The fourth coordinate x₄ = ict of Minkowski spacetime is a real geometric axis advancing at the invariant rate dx₄/dt = ic. The advance proceeds from every spacetime event simultaneously, spherically symmetrically about each event, with magnitude |dx₄/dt| = c invariant under Lorentz transformations.*

### II.2 The McGucken Sphere

**Definition II.1 (McGucken Sphere).** *For each event p₀ ∈ M, the future null cone*
$$\Sigma_+(p_0) = \{ p = (\mathbf{x}, t) : |\mathbf{x} - \mathbf{x}_0|^2 - c^2 (t - t_0)^2 = 0,\ t > t_0 \}$$
*is the McGucken Sphere centered on p₀.*

**Theorem II.2 (Six-fold null-surface identity** [MG-Nonlocality §4; MG-Sphere §7; MG-Feynman §III.6]**).** *The McGucken Sphere Σ₊(p₀) is simultaneously, for every p₀ ∈ M, six independent geometric objects: (1) a leaf of a foliation of the future light cone of p₀ by coordinate-time level sets; (2) a level set of the Minkowski interval function from p₀ at ds² = 0; (3) the caustic surface of the Huygens secondary-wavelet construction emanating from p₀; (4) the projection to the spatial slice of a Legendrian submanifold lifted from the contact bundle of M; (5) a member of a conformal pencil invariant under the conformal group SO(4,2) of M; (6) the cross-section of a null hypersurface of M with the spatial slice at the relevant coordinate time. Each of these six identifications is independently sufficient to establish Σ₊(p₀) as a unified geometric locality whose spatially separated points share a common identity in the corresponding mathematical framework.*

This six-fold identity is essential for the resolution of the locality/nonlocality tensions in problems (3)–(5) and (8): the McGucken Sphere is local in six independent and rigorous mathematical senses. Spacelike-separated points on the same Sphere are not unrelated, even though they are spacelike separated; they share a common geometric identity inherited from the single source event p₀ that generated them all.

### II.3 The hybrid spacetime measure and the Brillouin zone

**Hypothesis II.3 (Hybrid spacetime measure** [MG-Vanquishing Hypothesis 1]**).** *Spacetime carries the measure*
$$d\mu = d^3x \cdot a_4 \sum_{n \in \mathbb{Z}} \delta(x_4 - n a_4)\, dx_4,$$
*with a₄ = λ_P = √(ℏG/c³) the Planck length. The three spatial directions remain continuous; the fourth (x₄) direction is discrete with spacing λ_P.*

This is a hypothesis in [MG-Vanquishing], not yet a theorem of dx₄/dt = ic; the case for it rests on the oscillatory-Principle-form analysis of [MG-OscPrinc] and the requirement that the dimensional combination ℏG/c³ produces the unique length scale at which x₄'s advance is quantized.

**Theorem II.4 (Brillouin zone for x₄-conjugate momentum** [MG-Vanquishing Theorem on hybrid one-loop polarization]**).** *Under Hypothesis II.3, the four-dimensional Fourier transform of any function f ∈ L²(d⁴x) supported on the substrate of Hypothesis II.3 has its x₄-conjugate variable confined to the first Brillouin zone*
$$B = [-\pi\hbar/\lambda_P, +\pi\hbar/\lambda_P] \subset \mathbb{R}.$$
*Equivalently, the dual to x₄ is a circle of circumference 2πℏ/λ_P; modes outside B are aliased to their representatives in B.*

**Dimensional content of B.** The combination ℏ/λ_P has units of [action]/[length] = [momentum]. Specifically:
$$\frac{\hbar}{\lambda_P} = \frac{\hbar}{\sqrt{\hbar G/c^3}} = \sqrt{\frac{\hbar c^3}{G}} = c \sqrt{\frac{\hbar c}{G}} = c \cdot m_P = m_P c,$$
where m_P = √(ℏc/G) is the Planck mass. Therefore B is a **momentum** interval of width 2πm_P c = 2πℏ/λ_P.

The corresponding Planck **energy** is E_P = m_P c², a separate quantity from the Brillouin width. Energy bounds along the x₄ direction follow from the dispersion relation along x₄, which we state next.

### II.4 The dispersion relation along x₄

**Proposition II.5 (Discrete-x₄ dispersion).** *For a free scalar of mass m on the substrate of Hypothesis II.3, the dispersion relation along the discrete x₄ direction is*
$$E(\mathbf{p}, k_4) = c \sqrt{\mathbf{p}^2 + \left(\frac{2\hbar}{\lambda_P} \sin(k_4 \lambda_P / 2)\right)^2 + m^2 c^2}, \quad k_4 \in B,$$
*with the standard sin(k₄λ_P/2)/(λ_P/2) replacement of the continuum k₄ on the lattice. The spatial momenta p remain continuous; only the x₄-conjugate variable is restricted to B.*

The maximum value of |2ℏ sin(k₄λ_P/2)/λ_P| over k₄ ∈ B is 2ℏ/λ_P = 2m_P c, attained at the Brillouin-zone boundary k₄ = ±π/λ_P. Therefore the maximum x₄-component of four-momentum on the lattice is 2m_P c, corresponding to a maximum x₄-component of energy 2m_P c · c = 2 m_P c² (when the spatial momentum and rest mass are negligible). This is the correct origin of the Planck-energy bound: it is a **dispersion-relation maximum**, not a Brillouin-zone width.

In the long-wavelength limit |k₄| ≪ π/λ_P, the dispersion relation reduces to the continuum form:
$$E(\mathbf{p}, k_4) \approx c \sqrt{\mathbf{p}^2 + (\hbar k_4)^2 + m^2 c^2} + O((\hbar k_4 \lambda_P / 2)^2).$$
This recovers standard QFT in the regime where x₄-momenta are small compared to m_P c.

### II.5 The McGucken Causal Completion

**Definition II.6 (Causal completion of a region** [MG-Sphere §15.1]**).** *For an open region O ⊂ M, the McGucken causal completion is*
$$O^{\diamond}_M = \bigcup_{p \in O} \left( \Sigma_+(p) \cup \Sigma_-(p) \right),$$
*the union of the future and past McGucken Spheres of every event in O.*

**Theorem II.7 (McGucken algebraic microcausality** [MG-Sphere §15, Theorem 15.3]**).** *Let A_M(O) denote the algebra of bounded operators on the McGucken substrate generated by smeared local fields with smearing functions supported in O. Then*
$$O_1^{\diamond}_M \cap O_2^{\diamond}_M = \emptyset \implies [A_M(O_1), A_M(O_2)]_{\rm gr} = 0,$$
*where [·,·]_gr denotes the graded commutator (commutator for boson-boson, anticommutator for fermion-fermion, commutator for boson-fermion). When O₁ and O₂ are spacelike-separated bounded regions in the standard Minkowski sense, their McGucken causal completions are disjoint, and standard spacelike microcausality follows as Corollary 15.4.*

This theorem is the structural foundation for the resolution of the Sorkin problem in §VI. The locality theorem is **derived** from the geometric structure of Σ₊(p), not postulated.

### II.6 The Two Laws of Nonlocality

**First Law (Nonlocality Origin** [MG-Nonlocality §2]**).** *Every quantum nonlocality begins in locality: two systems can be entangled if and only if their past light cones contain a common spacetime event (a "shared origin") or are connected by a chain of intermediate local interactions (entanglement swapping).*

**Second Law (Nonlocality Growth** [MG-Nonlocality §3]**).** *The set of spacetime events with which a given event p can share entanglement grows at rate c: it is the future light cone of p, not the entire spacelike-separated complement of p.*

Both laws are theorems of dx₄/dt = ic [MG-Nonlocality, Theorem 4.3]. They resolve the apparent tension between Bell-correlation experiments and signal locality (problem 5) and structurally account for the Reeh–Schlieder vacuum entanglement (problem 4) by identifying it as the algebraic shadow of the McGucken-Sphere structure of the vacuum on x₄.

### II.7 The Born rule as McGucken-Sphere projection

**Theorem II.8 (Born rule from Σ₊** [MG-Born]**).** *The Born rule p(x|ψ) = |⟨x|ψ⟩|² for the probability of detection at spatial location x given a one-particle wavefunction ψ on the McGucken Sphere Σ₊(p₀) of the source event p₀ is the unique probability assignment on Σ₊(p₀) that is (i) invariant under the SO(3) rotation group acting on the Sphere about p₀, (ii) homogeneous of degree 2 in ψ, and (iii) reduces to the classical sub-wavefront probability in the geometric-optics limit.*

The proof identifies the Born rule with the SO(3)-invariant Haar measure on the 2-sphere Σ₊(p₀, t)|_t pulled back through the wavefunction restricted to Σ₊(p₀, t). Crucially, the Born rule is associated with **detection** at a point on Σ₊, not with a "collapse of the wavefunction" that propagates across spacelike separation. This distinction underlies the resolution of problem (2) in §X.

### II.8 The Wick rotation as coordinate identification

**Theorem II.9 (Wick rotation** [MG-Wick]**).** *The substitution t → −iτ in any Lorentz-invariant correlator is the coordinate identification τ = x₄/c. Specifically, writing expressions in t and substituting t → −iτ produces the same result as writing them directly in τ = x₄/c. The Wick rotation is therefore not analytic continuation but coordinate identification.*

This theorem is invoked in §VI.4 below to clarify the relation between Minkowski Sorkin-type signaling claims and Euclidean correlation-function bounds.

### II.9 The Feynman propagator as Huygens kernel

**Theorem II.10 (Feynman propagator** [MG-Feynman, Propositions III.1, III.4]**).** *The Feynman propagator D_F(x − y) is the x₄-coherent Huygens kernel — the amplitude for x₄-phase oscillation at the Compton frequency ω₀ = mc²/ℏ to propagate from event y to event x via iterated Huygens expansion. The propagator's geometric support is on and inside the future McGucken Sphere Σ₊(y) of the source event y; the +iε prescription selects the forward branch of the Sphere's expansion. The Sphere is six-fold local (Theorem II.2).*

These nine inputs (II.1–II.9) are all that is required from the McGucken corpus to resolve the nine problems below.

---

## III. The Brillouin-Zone Support Theorem (Corrected)

This section proves the support theorem that replaces the May 9 draft's incorrect "Theorem 1." We give the corrected statement, establish notation, and prove the support claim with full attention to dimensional content.

### III.1 Setup

Let φ̂(x) be a free scalar field of mass m on Minkowski spacetime, smeared by a complex test function f ∈ S(M) (Schwartz space) to give the smeared operator
$$\hat{O}_f = \int d^4x\, f(x)\, \hat\varphi(x).$$
On the **standard continuum substrate** (M, d⁴x), the four-dimensional Fourier transform
$$\tilde{f}(p) = \int d^4x\, f(x)\, e^{-ip\cdot x/\hbar}$$
is a Schwartz function on ℝ⁴ with no support restriction.

On the **McGucken substrate** of Hypothesis II.3, the situation differs. Test functions are not arbitrary functions on M; they are functions on the substrate dμ = d³x · a₄ Σₙ δ(x₄ − na₄) dx₄. We make this precise.

### III.2 Substrate-compatible test functions

**Definition III.1 (Substrate-compatible test function).** *A function f : M → ℂ is substrate-compatible if it is the restriction to the substrate of Hypothesis II.3 of a Schwartz function on ℝ⁴, equivalently if there exists g ∈ S(ℝ⁴) such that*
$$f(x_1, x_2, x_3, x_4) = g(x_1, x_2, x_3, n\lambda_P) \quad \text{when } x_4 = n\lambda_P,\ n \in \mathbb{Z},$$
*and f is undefined off the substrate. The space of substrate-compatible test functions is denoted S(M; λ_P).*

For any f ∈ S(M; λ_P), the substrate-compatible Fourier transform is
$$\tilde{f}(\mathbf{p}, k_4) = \int d^3x\, \lambda_P \sum_{n \in \mathbb{Z}} f(\mathbf{x}, n\lambda_P)\, e^{-i(\mathbf{p}\cdot\mathbf{x} - n\lambda_P k_4)/\hbar},$$
where p = (p_1, p_2, p_3) ∈ ℝ³ are continuous spatial momenta and k₄ is the variable conjugate to the discrete x₄ axis.

The discrete-x₄ sum produces aliasing in k₄: the function f̃ is periodic in k₄ with period 2πℏ/λ_P, so we may restrict k₄ to one period without loss of information. The conventional choice is the **first Brillouin zone**
$$B = [-\pi\hbar/\lambda_P, +\pi\hbar/\lambda_P].$$

### III.3 The support theorem

**Theorem III.2 (Brillouin-zone support theorem; corrected version of the May 9 "Theorem 1").** *For every f ∈ S(M; λ_P), the substrate-compatible Fourier transform f̃ has compact support in the k₄ direction:*
$$\mathrm{supp}\, \tilde{f} \subseteq \mathbb{R}^3 \times B = \mathbb{R}^3 \times [-\pi\hbar/\lambda_P, +\pi\hbar/\lambda_P].$$
*The support in the spatial momentum directions p remains all of ℝ³, since the spatial directions of the substrate are continuous and unbounded in the present formalism.*

***Proof.*** The Pontryagin dual of the discrete subgroup λ_P ℤ ⊂ ℝ is the circle ℝ/(2πℏ/λ_P)ℤ. Functions on λ_P ℤ have Fourier transforms on this circle. The choice of fundamental domain B = [−πℏ/λ_P, +πℏ/λ_P] is conventional; any other choice differs by translation by integer multiples of 2πℏ/λ_P, which acts trivially on the Fourier transform. Therefore the support of f̃ is at most the cross-product of all of ℝ³ (continuous spatial directions) with B (the fundamental domain of the discrete x₄ direction). □

**Remark III.1 (What this theorem is, and what it is not).** The theorem is a statement about the support of f̃ as a function on (continuous spatial momenta) × (the dual of the discrete x₄). It is **not** a statement about the spectrum of any operator. The May 9 draft conflated these. To be explicit:

– **Spectrum** of an operator T on a Hilbert space H: the set spec(T) = { λ ∈ ℂ : T − λ I is not invertible }. A subset of ℂ.
– **Support** of a function g on a measure space X: the closure of the set { x ∈ X : g(x) ≠ 0 }. A subset of X.

When X = ℝ³ × B is a region of momentum space, the support of f̃ is a subset of ℝ³ × B, hence a 4-dimensional region. The spectrum of O_f is a subset of ℝ (or ℂ); the spectrum of O_f cannot, as a matter of category, be contained in ℝ³ × B. The corrected statement is the support theorem above.

### III.4 The dimensional content of B is momentum, not energy

The May 9 draft consistently identified the Brillouin width with πm_P c² rather than πm_P c. From the Planck quantities:

– Planck length: λ_P = √(ℏG/c³)
– Planck time: t_P = √(ℏG/c⁵) = λ_P/c
– Planck mass: m_P = √(ℏc/G)
– Planck momentum: p_P ≡ m_P c
– Planck energy: E_P = m_P c²

The combination ℏ/λ_P, which appears in the Brillouin-zone width, has dimension [ℏ]/[length] = [action]/[length] = [momentum]:
$$[\hbar/\lambda_P] = \frac{\mathrm{J\cdot s}}{\mathrm{m}} = \frac{\mathrm{kg\cdot m^2/s^2 \cdot s}}{\mathrm{m}} = \mathrm{kg\cdot m/s}.$$

Numerically:
$$\frac{\hbar}{\lambda_P} = \sqrt{\frac{\hbar^2}{\hbar G/c^3}} = \sqrt{\frac{\hbar c^3}{G}} = c\sqrt{\frac{\hbar c}{G}} = c \cdot m_P = m_P c = p_P.$$

Therefore the Brillouin-zone width is 2πℏ/λ_P = 2π m_P c, a **momentum** of magnitude 2π × Planck momentum. The corresponding Planck energy 2π m_P c² appears separately in the dispersion relation along x₄ and is not the Brillouin-zone width itself.

This dimensional correction propagates through all derivations involving B: where the May 9 draft wrote "energy bound πm_P c²," the correct statement is "momentum bound πm_P c" except where the dispersion relation along x₄ is invoked to convert momenta to energies. Whenever an energy bound is asserted in the present paper, the conversion is explicit.

### III.5 Consequence: every smeared local operator is band-limited in x₄-momentum

The combined force of Theorem III.2 and Theorem II.4 is that every smeared field operator O_f for f ∈ S(M; λ_P) has its x₄-conjugate momentum content confined to B. The position-space content of f remains arbitrary (in ℝ³) in the spatial directions and on the discrete λ_P ℤ in the x₄ direction. Equivalently:

**Corollary III.3.** *For any f ∈ S(M; λ_P) and any state |ψ⟩ in the McGucken-substrate Hilbert space, the matrix element ⟨ψ| O_f |ψ⟩ is the integral over ℝ³ × B of a Schwartz function. Modes outside ℝ³ × B do not contribute.*

This corollary is the entry point for the Sorkin resolution in §VI: the test functions defining Alice's, Bob's, and Charlie's measurement operators have substrate-compatible momentum support, and the cross-correlation that drives Sorkin signaling is bounded by the spatial-momentum decay of Schwartz functions through the standard Riemann–Lebesgue / smoothness route, NOT by an x₄-momentum cutoff alone.

We turn now to that resolution.

---

## IV. The McGucken Causal Completion and Algebraic Microcausality

This section reproduces the structure of [MG-Sphere §15] in the form needed for §VI. The full proofs are in [MG-Sphere].

### IV.1 The local net A_M(O)

**Definition IV.1 (McGucken local net).** *For each open bounded region O ⊂ M, let A_M(O) be the von Neumann algebra of bounded operators on the McGucken-substrate Hilbert space H_M generated by smeared field operators O_f with f ∈ S(M; λ_P) and supp(f) ⊂ O. The assignment O ↦ A_M(O) is the McGucken local net.*

The McGucken local net inherits two structural properties from the underlying substrate:

**Property 1 (Isotony).** *O₁ ⊆ O₂ ⇒ A_M(O₁) ⊆ A_M(O₂).* Immediate from Definition IV.1.

**Property 2 (Translation covariance).** *Under spacetime translation x ↦ x + a (with a₄ ∈ λ_P ℤ for compatibility with the substrate), A_M(O + a) = U(a) A_M(O) U(a)†.* Inherited from translation covariance of the substrate.

### IV.2 The McGucken causal completion

**Definition IV.2 (McGucken causal completion, restated).** *For an open bounded region O ⊂ M,*
$$O^{\diamond}_M = \bigcup_{p \in O} \left( \Sigma_+(p) \cup \Sigma_-(p) \right) = J^+(O) \cup J^-(O),$$
*where J⁺(O), J⁻(O) are the future and past causal sets of O in standard Minkowski geometry. The McGucken causal completion of O is the union of the future and past light cones of every event in O — equivalently, the set of all events causally related to some event in O.*

Note that O^⋄_M is **not** simply the standard causal completion of O (which would be O″ = the spacelike-double-complement); it is the union of all light cones from O. The two coincide for "diamond-shaped" regions (intersections of future and past cones of two events) but differ for general bounded O.

### IV.3 The microcausality theorem

**Theorem IV.3 (McGucken algebraic microcausality** [MG-Sphere §15, Theorem 15.3]**).** *For bounded open regions O₁, O₂ ⊂ M,*
$$O_1^{\diamond}_M \cap O_2^{\diamond}_M = \emptyset \implies [A_M(O_1), A_M(O_2)]_{\rm gr} = 0.$$

***Proof (sketch, following [MG-Sphere §15]).*** The McGucken causal completion O^⋄_M is the largest region of M that can be causally influenced by, or causally influence, the region O via propagation along McGucken Spheres. The Feynman propagator (Theorem II.10) has its support on and inside Σ₊(p) ∪ Σ₋(p) for each event p; therefore the support of the propagator G(x, y) for x ∈ O is contained in (∪_{p ∈ O}(Σ₊(p) ∪ Σ₋(p))) = O^⋄_M.

When O₁^⋄_M ∩ O₂^⋄_M = ∅, every propagator from O₁ to a point in O₂ has zero support: there is no McGucken Sphere from any point of O₁ that reaches any point of O₂. The graded commutator of the smeared fields O_{f₁}, O_{f₂} with supp(f_i) ⊂ O_i is given by the standard Pauli–Jordan distribution (or its fermionic analog), which is supported on the union of future and past light cones. Empty intersection of causal completions ⇒ vanishing Pauli–Jordan distribution between O₁ and O₂ ⇒ vanishing graded commutator [A_M(O₁), A_M(O₂)]_gr = 0. □

**Corollary IV.4 (Standard spacelike microcausality, [MG-Sphere §15, Corollary 15.4]).** *When O₁ and O₂ are spacelike-separated bounded regions in standard Minkowski geometry (so that no event in O₁ is in J⁺(O₂) ∪ J⁻(O₂)), then O₁^⋄_M ∩ O₂^⋄_M = ∅, and Theorem IV.3 yields [A_M(O₁), A_M(O₂)] = 0 (the standard spacelike microcausality).*

This is the structural fact that drives the Sorkin resolution. We turn to it now.

### IV.4 What is new here, and what is not

The microcausality theorem itself is standard in algebraic QFT [Haag1996, Streater–Wightman1964]; what is new in [MG-Sphere §15] is the **derivation** of microcausality from the geometric structure of the McGucken Sphere — specifically, from the support structure of the propagator and the construction of O^⋄_M as a union of light cones. In standard algebraic QFT, microcausality is axiomatic; here, it is a theorem of dx₄/dt = ic via Theorem II.10 (propagator support on Σ₊).

This shift from axiom to theorem matters for the Sorkin problem, because the Sorkin signaling argument uses the failure of microcausality to extend from local commutators to projective measurements. When microcausality is geometric, its extension to measurement operations is also geometric — and as we show in §V, the extension goes through.

---

## V. Microcausality, Commutators, and the Pauli–Jordan Function: From Axiom to Theorem

The structural content of §IV is best understood through the lens of standard quantum field theory's microcausality axiom and the Pauli–Jordan distribution that realizes it. This section makes the relation explicit. The conclusion is sharp: what standard QFT imposes as an axiom on the field commutators, the McGucken framework derives as a theorem from the geometric support structure of the Feynman propagator on the McGucken Sphere.

### V.1 Microcausality in standard QFT: an axiom on commutators

In the Wightman axiomatization of relativistic quantum field theory [Streater–Wightman1964, Haag1996], one of the four core axioms — typically labeled W4 in the Wightman list, or "local commutativity" in the Haag–Kastler algebraic formulation — is the microcausality axiom:

**Microcausality Axiom (standard QFT).** *For any two spacetime points x and y with (x − y)² > 0 (spacelike separation), the field operators satisfy*
$$[\hat\varphi(x), \hat\varphi(y)] = 0 \quad \text{(bosonic fields)},$$
$$\{\hat\psi(x), \hat\psi(y)\} = 0 \quad \text{(fermionic fields)}.$$

The physical content of this axiom is the prohibition of superluminal signaling at the operator-algebra level: if the commutator did not vanish, then a measurement of $\hat\varphi(x)$ would disturb $\hat\varphi(y)$ at spacelike separation, violating Einstein's relativistic constraint on causal influence. The axiom is the algebraic formalization of the impossibility of operator-level signaling between spacelike events.

In the algebraic-QFT formulation (Haag–Kastler), the axiom takes the form of an assignment $\mathcal{O} \mapsto \mathcal{A}(\mathcal{O})$ of bounded open spacetime regions to von Neumann algebras, satisfying

$$\mathcal{O}_1 \subset \mathcal{O}_2' \implies [\mathcal{A}(\mathcal{O}_1), \mathcal{A}(\mathcal{O}_2)] = 0,$$

where $\mathcal{O}_2'$ denotes the spacelike complement of $\mathcal{O}_2$. The pointwise commutator-vanishing of W4 becomes the algebra-level commutator-vanishing of Haag–Kastler. The two formulations are equivalent.

### V.2 The Pauli–Jordan distribution

For a free real scalar field of mass m, the commutator can be computed explicitly. The mode expansion

$$\hat\varphi(x) = \int \frac{d^3k}{(2\pi)^3 \sqrt{2\omega_k}} \left( \hat a_k e^{-ik\cdot x} + \hat a_k^\dagger e^{+ik\cdot x} \right), \quad \omega_k = +\sqrt{|\mathbf{k}|^2 + m^2 c^2/\hbar^2},$$

combined with the canonical commutation relation $[\hat a_k, \hat a_{k'}^\dagger] = (2\pi)^3 \delta^3(\mathbf{k} - \mathbf{k}')$, gives

$$[\hat\varphi(x), \hat\varphi(y)] = i \Delta(x - y),$$

where the **Pauli–Jordan distribution** is

$$\Delta(x - y) = -i \int \frac{d^3k}{(2\pi)^3 \, 2\omega_k} \left( e^{-ik\cdot(x-y)} - e^{+ik\cdot(x-y)} \right). \tag{V.1}$$

The Pauli–Jordan distribution has three crucial properties [PeskinSchroeder1995, §2.4]:

(i) **Lorentz invariance.** $\Delta(x - y)$ depends on $x - y$ only through the Lorentz-invariant interval $(x-y)^2$.

(ii) **Support on and inside the light cone.** $\Delta(x - y) = 0$ for $(x-y)^2 > 0$ (spacelike separation). The distribution is supported in the closed forward and backward light cones of the origin.

(iii) **Antisymmetry.** $\Delta(x - y) = -\Delta(y - x)$.

Property (ii) is what realizes the microcausality axiom: when $(x - y)^2 > 0$, the Pauli–Jordan distribution vanishes, so $[\hat\varphi(x), \hat\varphi(y)] = 0$. The light-cone support structure of $\Delta$ is the technical mechanism by which standard QFT achieves spacelike commutator-vanishing for free fields.

For interacting fields, the commutator structure must be checked at each order of perturbation theory. The microcausality axiom requires that the interacting analogue of $\Delta$ preserves the same light-cone support, and theories that fail this requirement (e.g., theories with derivative couplings beyond a certain order, theories with non-local interactions) are rejected as unphysical. The axiom is therefore not automatic for interacting theories; it is a constraint imposed on admissible Lagrangians.

### V.3 The geometric content of $\Delta$: what is doing the work

Property (ii) — the light-cone support of $\Delta$ — is the engine of the microcausality axiom. The question that standard QFT leaves open is **why** $\Delta$ has this support structure. The textbook derivation [PeskinSchroeder1995] proceeds by direct computation: one writes the mode integral (V.1), changes variables, and verifies that the integral vanishes for spacelike separations through a contour-deformation argument. The argument is mathematically correct but geometrically opaque. It does not identify the geometric object whose support structure $\Delta$ inherits; it merely verifies that the integral happens to vanish where required.

The McGucken framework supplies the geometric object. The Feynman propagator $D_F(x - y)$ is related to the Pauli–Jordan distribution by

$$D_F(x - y) = \theta(x^0 - y^0) \langle 0 | \hat\varphi(x) \hat\varphi(y) | 0 \rangle + \theta(y^0 - x^0) \langle 0 | \hat\varphi(y) \hat\varphi(x) | 0 \rangle, \tag{V.2}$$

and the imaginary part of $D_F$ (with appropriate sign conventions) is essentially $\Delta$:

$$\Delta(x - y) = -2i \, \text{Im}\, D_F(x - y) \cdot \text{sign}(x^0 - y^0). \tag{V.3}$$

The support structure of $\Delta$ is therefore inherited from the support structure of $D_F$. And the support structure of $D_F$ is, by Theorem II.10 of the present paper (from [MG-Feynman §III]), the McGucken Sphere $\Sigma_+(y)$ of the source event $y$.

This gives the McGucken-framework derivation of microcausality, which we state as a theorem.

### V.4 The McGucken microcausality theorem

**Theorem V.1 (Microcausality as a theorem of $dx_4/dt = ic$).** *Under the McGucken Principle, the Pauli–Jordan distribution $\Delta(x - y)$ has support contained in the future and past McGucken Spheres of $y$:*

$$\mathrm{supp}\, \Delta(x - y) \subseteq \Sigma_+(y) \cup \Sigma_-(y) \cup \mathrm{interior}(\Sigma_+(y) \cup \Sigma_-(y)).$$

*Consequently, for any two spacetime points $x$ and $y$ with $(x - y)^2 > 0$ (spacelike separation), $\Delta(x - y) = 0$, hence $[\hat\varphi(x), \hat\varphi(y)] = 0$. The microcausality axiom of standard QFT becomes a theorem.*

***Proof.*** By Theorem II.10 of the present paper (the McGucken-framework derivation of the Feynman propagator from [MG-Feynman §III.1]), $D_F(x - y)$ is the $x_4$-coherent Huygens kernel for $x_4$-phase propagation from $y$ to $x$. By [MG-Feynman §III.6] (Proposition III.4, six-fold geometric locality), the propagator's geometric support is on and inside the future McGucken Sphere $\Sigma_+(y)$ of the source event, with the $+i\varepsilon$ prescription (Theorem II.10) selecting the forward branch.

By the relation (V.3), the Pauli–Jordan distribution $\Delta(x - y)$ inherits this support structure, augmented by the past branch through the time-ordering decomposition (V.2): $\Delta$ is supported on the union of the forward Sphere $\Sigma_+(y)$, the backward Sphere $\Sigma_-(y)$, and their interiors. For spacelike separation $(x - y)^2 > 0$, the point $x$ lies outside both spheres and their interiors, so $\Delta(x - y) = 0$, hence $[\hat\varphi(x), \hat\varphi(y)] = 0$. $\blacksquare$

The graded version of this theorem (boson-boson commutator, fermion-fermion anticommutator, boson-fermion commutator) follows by the same argument applied to the corresponding propagator support structures of [MG-Feynman §III.3, Proposition III.3]. The full statement is Theorem IV.3 of the present paper.

### V.5 What changes when the axiom becomes a theorem

The axiom-to-theorem reduction is structurally significant for three reasons.

**First**, the McGucken microcausality theorem identifies the geometric object whose support carries the axiom: the McGucken Sphere. Standard QFT's contour-deformation derivation of $\Delta$'s light-cone support is correct as far as it goes, but it does not identify the Sphere — it merely shows that the integral happens to vanish in the right region. The McGucken framework identifies the Sphere as the foundational atom of spacetime [MG-Sphere], establishes its six-fold locality (Theorem II.2), and derives the propagator's support from the Sphere's geometric structure. The "what is doing the work" question — left open by the textbook derivation — has a geometric answer: the McGucken Sphere of the source event.

**Second**, the McGucken framework derives microcausality for **interacting** theories at no additional cost. In standard QFT, microcausality is automatic for free fields (the mode-integral calculation gives $\Delta$ directly) but must be checked at each order of perturbation theory for interacting fields. Theories with derivative couplings beyond a certain order, or with non-local interactions, can fail microcausality and must be rejected. In the McGucken framework, the propagator's Sphere support is a geometric fact about $dx_4/dt = ic$ that holds independent of the interaction Lagrangian. Interactions modify the propagator via vertex insertions (Proposition IV.1 of [MG-Feynman]) but cannot extend its support beyond the McGucken Sphere of the source event — the Sphere is the geometric envelope of all $x_4$-phase propagation, and no interaction can propagate $x_4$-phase faster than $x_4$ advances. Microcausality for interacting fields is therefore not a check to be performed at each perturbative order; it is a geometric corollary of $dx_4/dt = ic$.

**Third**, the axiom-to-theorem reduction does not by itself close the gap that Sorkin identified. Microcausality at the operator-algebra level ($[\mathcal{A}(\mathcal{O}_1), \mathcal{A}(\mathcal{O}_2)] = 0$ for spacelike-separated regions) does not, by itself, guarantee no-signaling at the **measurement** level (the conditional expectation $\langle \hat O_B \rangle_{p_c \mid \hat O_A}$ does not depend on Alice's operator choice $\hat O_A$). The standard Lüders projection rule, applied to a region $\mathcal{O}_C$ causally between two spacelike-separated regions $\mathcal{O}_A$ and $\mathcal{O}_B$, can produce conditional expectation values that depend on Alice's choice even when the operators commute, because the Reeh–Schlieder vacuum entanglement makes the state non-factorized. This is the Sorkin signaling problem, which is treated structurally in §VI below.

The McGucken framework therefore provides:

- **At the algebraic level (this section):** microcausality as a theorem (Theorem V.1) of the McGucken Sphere support of the propagator. The Pauli–Jordan distribution vanishes for spacelike separation as a geometric consequence of $dx_4/dt = ic$.

- **At the state level (§VI):** the Sorkin signaling expression is bounded by the combination of (i) Sphere-support algebraic locality (Theorem V.1 / Theorem IV.3) and (ii) Schwartz spatial-decay (Theorem VI.2 below). Both pieces are derived from the McGucken framework; neither requires modification of the Lüders projection rule.

### V.6 Comparison with the standard QFT measurement-program literature

The thirty-three-year program of Fewster–Verch [FV2020], Polo-Gómez–Garay–Martín-Martínez [PGM2022], de Ramón–Papageorgiou–Martín-Martínez [dRPM2021], Borsten–Jubb–Kells [BJK2021], Bostelmann–Fewster–Ruep [BFR2021], Mandrysch–Navascués [MN2024], Papageorgiou–Fraser [PF2024], and Fewster's 2025 lectures [Fewster2025] addresses the gap between (i) algebraic microcausality and (ii) state-level no-signaling by modifying the **measurement** formalism. The FLAMM probe-field model replaces Lüders projection by a coupling of the system to a probe field localized in the measurement region; the resulting effective measurement preserves no-signaling automatically because the coupling is local in the operational sense.

The McGucken framework resolves the same gap by a different route: not by modifying the measurement formalism but by deriving both microcausality (Theorem V.1) and state-level Schwartz decay (Theorem VI.2 below) from the same geometric source, $dx_4/dt = ic$. The two pieces fit together because they share the same underlying geometric object — the McGucken Sphere — whose support carries the algebraic locality, and whose Schwartz-smoothness on the substrate carries the state-level decay. Lüders projection is admissible in the McGucken framework because the geometric microcausality is strong enough to bound the Sorkin signaling expression directly, without surgery on the measurement rule.

The two approaches are not in conflict: each is a self-consistent resolution of the Sorkin gap. The question between them is parsimony. The standard program closes the gap one pathology at a time (Sorkin via FLAMM, Reeh–Schlieder via algebraic-QFT reformulation, Bell via interpretation choice, etc.); the McGucken program closes the gap once at the geometric level and inherits the resolution for all nine pathologies catalogued in §I.2. As an axiomatic reduction, the McGucken framework reduces the axiomatic content of QFT (microcausality + Lüders gap + Reeh–Schlieder puzzle + Bell locality + photon localizability + ...) to the single geometric content of $dx_4/dt = ic$ plus Hypothesis II.3 (the hybrid measure with $a_4 = \lambda_P$).

### V.7 What this section does NOT claim

Three honest limitations of the present argument deserve explicit statement.

**(1) Hypothesis II.3 remains a hypothesis.** The hybrid measure $d\mu = d^3x \cdot a_4 \sum_n \delta(x_4 - n a_4) dx_4$ with $a_4 = \lambda_P$ is taken as input. [MG-Vanquishing] motivates it via [MG-OscPrinc] and the requirement that the dimensional combination $\hbar G/c^3$ produces the unique length scale at which $x_4$'s advance is quantized, but does not yet derive it as a theorem of $dx_4/dt = ic$ alone. The Sorkin resolution of §VI rests on Hypothesis II.3 + the McGucken Principle, not on the Principle alone. Tightening Hypothesis II.3 to a theorem is open work.

**(2) Theorem V.1 is the geometric content of microcausality, not its full proof for interacting Standard Model fields.** The proof above invokes the propagator support structure of [MG-Feynman §III] for the scalar field. The full extension to gauge fields, fermions, and Standard Model interactions is sketched in [MG-Feynman §III.3] (Proposition III.3) and [MG-QED], but a complete formal verification across all Standard Model sectors is not given here. The structural argument — that no interaction can propagate $x_4$-phase faster than $x_4$ advances — is robust, but the per-sector formalization is open work.

**(3) The FLAMM and Verch–Fewster programs are not refuted.** The McGucken framework gives an alternative resolution of the Sorkin gap by changing the geometric foundation. Both resolutions can coexist as self-consistent treatments; the choice between them rests on parsimony and on whether one accepts the geometric reading of $x_4 = ict$ as a real physical axis. This paper does not argue against the standard programs; it argues for the simpler axiomatic structure available under the McGucken reading.

---

## VI. Resolution of the Sorkin Impossible-Measurements Problem (Problem 3)

### VI.1 The Sorkin scenario

Let R_A, R_B, R_C ⊂ M be three disjoint open bounded regions with:

– R_A and R_B spacelike separated;
– R_C in J⁺(R_A) ∩ J⁻(R_B), so Charlie's region is in the causal future of Alice and the causal past of Bob.

Alice can measure operators in A_M(R_A); similarly for Bob, Charlie. The Sorkin claim, in its sharpest form, is: *if Charlie performs a Lüders projective measurement of an operator P_C ∈ A_M(R_C), then for some O_A ∈ A_M(R_A), O_B ∈ A_M(R_B), the conditional expectation ⟨O_B⟩_{after Charlie | Alice's choice O_A} depends on Alice's choice — superluminal signaling.*

The signaling, when it occurs, is mediated by the chain A → C → B in operational terms: Charlie's projection updates the state on the basis of an outcome that is correlated with Alice's choice (because R_A is in J⁻(R_C)), and Bob's expectation depends on this updated state (because R_B is in J⁺(R_C)). The chain is causal, but the **endpoints** are spacelike separated — Sorkin's problem is that this endpoint-spacelike-separation is what should preclude signaling, yet the formalism predicts it.

### VI.2 The Sorkin signaling expectation

Let the joint state be the Minkowski vacuum |0⟩ for concreteness (the analysis is identical for any cyclic-and-separating state). The Lüders update under Charlie's projection P_C with outcome p_c is
$$|\psi\rangle \mapsto \frac{P_C^{(p_c)} |\psi\rangle}{\| P_C^{(p_c)} |\psi\rangle \|},$$
where P_C^(p_c) is the Lüders projection associated with the outcome p_c. The conditional expectation of O_B given Charlie's outcome p_c and Alice's pre-measurement (without selection) of O_A is
$$\langle O_B \rangle_{p_c \mid O_A} = \frac{\langle 0| O_A P_C^{(p_c)} O_B P_C^{(p_c)} O_A |0\rangle}{\langle 0| O_A P_C^{(p_c)} O_A |0\rangle}.$$

The Sorkin signaling occurs when this expression depends on the choice of O_A. Sorkin showed [Sorkin1993] that for generic O_A, O_B, P_C, this dependence is nonzero.

### VI.3 Resolution: the McGucken-substrate restriction eliminates the dependence

We give the resolution via the following theorem.

**Theorem VI.1 (Sorkin resolution).** *Let O_A ∈ A_M(R_A), O_B ∈ A_M(R_B), P_C ∈ A_M(R_C) be McGucken-substrate-compatible smeared operators. If R_A and R_B are spacelike separated in the strong sense that R_A^⋄_M ∩ R_B^⋄_M = ∅ (i.e., no McGucken Sphere from R_A reaches R_B and vice versa), then*
$$\langle 0| O_A P_C^{(p_c)} O_B P_C^{(p_c)} O_A |0\rangle = \langle 0| P_C^{(p_c)} O_B P_C^{(p_c)} \rangle \cdot \langle 0| O_A^2 |0\rangle / \langle 0|0\rangle \cdot (1 + \epsilon),$$
*with |ε| ≤ ε(R_A, R_B, R_C) controlled by the spatial-decay smoothness of f_A, f_B as Schwartz test functions and bounded by Theorem VI.2 below. In particular, ε vanishes in the limit where the Schwartz spatial decay rate of f_A, f_B is ≫ the spatial scale of the chain R_A → R_C → R_B.*

**Theorem VI.2 (Schwartz-decay bound, replacing the May 9 draft's Riemann–Lebesgue invocation).** *Let f, g ∈ S(ℝ³) be Schwartz functions on ℝ³ with disjoint supports, separated by spatial distance d > 0. Then for every N > 0 there exists C_N > 0 such that*
$$|(\hat{f} \star \hat{g})(\mathbf{p})| \leq C_N (1 + d/\hbar c)^{-N} (1 + |\mathbf{p}|/\hbar c)^{-N}.$$
*Equivalently, the convolution decays faster than any polynomial in the spatial separation d.*

***Proof of VI.2.*** Standard fact about Schwartz functions; the convolution of two compactly-supported smooth functions separated in space has rapid decay. The bound follows from the standard Schwartz-norm estimates [Reed–Simon vol. I, §IX]. The McGucken substrate restriction (Theorem III.2) does not affect the spatial-momentum decay; it only confines the x₄-conjugate momentum to B, which is irrelevant for spatial separation. □

***Proof sketch of VI.1.*** The key observation is that on the McGucken substrate, the propagator G(x, y) for x ∈ R_A, y ∈ R_B has support contained in R_A^⋄_M ∩ R_B^⋄_M (Theorem II.10 + Theorem IV.3). When this intersection is empty, the matrix element of the field commutator [φ̂(x), φ̂(y)] vanishes for x ∈ R_A, y ∈ R_B. The Lüders projection P_C^(p_c) = Π_C^(p_c) (a projection in A_M(R_C)) commutes with O_A (since R_A^⋄_M ∩ R_C^⋄_M restricted to the relevant "back-reaction" subset is bounded by Theorem VI.2) up to terms decaying as in Theorem V.2. The numerator and denominator factor as in the Theorem statement, and the conditional expectation becomes independent of O_A in the limit ε → 0. □

**Remark VI.1 (Why this is not the FLAMM/probe-field resolution).** The FLAMM framework of [PGM2022, dRPM2021, PF2024] resolves the Sorkin problem by replacing the Lüders projection by a coupling to an auxiliary probe field localized in R_C, which forces the measurement operator to be local in a strong (operational) sense. The McGucken resolution is structural: the locality is not imposed via a measurement model but inherited from the geometry of the McGucken Sphere via Theorem IV.3. Lüders measurements are admissible in the McGucken framework because they respect the geometric microcausality directly.

**Remark VI.2 (What was wrong with the May 9 draft on this resolution).** The May 9 draft attempted to derive the Sorkin resolution by invoking the Riemann–Lebesgue lemma to claim decay of the relevant correlation function on a compact x₄-momentum domain B. Riemann–Lebesgue gives only continuity (and decay at infinity in the Fourier-transform direction); it does not give pointwise decay on a compact domain. The correct route, supplied here, is via the spatial-direction Schwartz-decay bound (Theorem V.2). The Brillouin zone B controls x₄-momentum content but does not, by itself, force the spatial decay. The spatial decay comes from Schwartz-smoothness of the test functions, which is the actual hypothesis available in the FLAMM model and in any rigorous formulation.

### VI.4 The Wick-rotation perspective

Theorem II.9 (Wick rotation as coordinate identification) provides an additional perspective on the Sorkin resolution. In Euclidean signature τ = x₄/c, the Sorkin chain R_A → R_C → R_B becomes a chain of Euclidean regions, and the correlation functions become Euclidean Green's functions with positive-definite kernels. The clustering of Euclidean correlation functions at large spatial separation is the standard Schwartz-decay property of the Euclidean two-point function. The Wick rotation back to Minkowski preserves this decay and yields Theorem V.2 directly.

The Wick-rotation perspective makes clear that the Sorkin resolution is **structural** in the same sense as the locality of Euclidean QFT: it is a geometric property of the substrate, not a perturbative or measurement-theoretic adjustment.

---

## VII. Bohmian Arrival Times, the Maudlin–Das Signaling Claim, and the McGucken No-Signaling Theorem

A second signaling problem, structurally parallel to Sorkin's but located in a different sector of the measurement formalism, has been active in the foundations literature since the Das–Dürr–Goldstein–Struyve series of papers (2019–2022) and was recently elevated to a target empirical test by Maudlin's foundations-of-physics program. The problem is the arrival-time problem in quantum mechanics, and the alleged signaling claim is the Maudlin–Das prediction that an Alice/Bob spin-correlated setup permits faster-than-light information transfer via spin-dependent arrival-time distributions. This section states the problem, gives the McGucken-framework resolution via the **McGucken No-Signaling Theorem** (Theorem 7.3 of [MG-TwoRoutes §V.8.7], reproduced here as Theorem VII.3), and records the resulting falsifiable prediction.

### VII.1 The arrival-time problem in standard quantum mechanics

Pauli's 1933 observation [Pauli1933] established that no Hermitian operator $\hat{T}$ canonically conjugate to a bounded-below Hamiltonian $\hat{H}$ can exist on a quantum-mechanical Hilbert space. The consequence: there is no standard quantum-mechanical observable for "time of arrival of a particle at a detector." Approximately twenty distinct proposals exist in the literature (Aharonov–Bohm [AB1961], Kijowski [Kijowski1974], Werner [Werner1986], Allcock [Allcock1969], Grot–Rovelli–Tate [GRT1996], absorbing-potential methods, two-state-vector methods, time-of-flight quantum-clock methods) and they **disagree in the near and middle field** of the propagation [MuPaGo2000]. They converge in the far-field limit where semiclassical propagation dominates. The arrival-time problem is therefore one of the structurally unresolved questions of standard QM measurement theory: there is no consensus observable, and the framework does not single out a unique prediction.

### VII.2 The Bohmian arrival-time prediction and the Maudlin–Das signaling claim

Bohmian mechanics resolves the operator obstruction directly: Bohmian particles have definite trajectories $\mathbf{q}(t)$ governed by the guidance equation $\dot{\mathbf{q}} = (\hbar/m)\,\mathrm{Im}(\nabla\psi/\psi)$ at the non-relativistic level, or the corresponding Dirac-current guidance equation at the relativistic level. Arrival times are simply the times at which trajectories cross the detector surface, distributed by $|\psi|^2$ at the initial position. This is a clean and unambiguous prediction.

The Das–Dürr–Goldstein–Struyve computation [DasDurr2019], extended in Das–Nöth–Dürr [DasNoethDurr2021, DasNoethDurr2022], applies this prescription to the Pauli equation (and the Dirac equation at the relativistic level) for a spin-½ particle in a Stern–Gerlach apparatus. The resulting arrival-time distribution depends on the spin orientation of the magnetic-field gradient. In an entangled-pair setup — two spin-½ particles in a singlet state, Alice and Bob each performing Stern–Gerlach measurements at spacelike separation — the Bohmian calculation predicts that **Bob's marginal arrival-time distribution depends on Alice's magnetic-field orientation**. If correct, this is genuine superluminal signaling: Alice's choice of magnet orientation, made at her end, shifts the statistical distribution of Bob's arrival times at his end.

Maudlin [Maudlin2023] has identified this as a sharp empirical fork between Bohmian mechanics and any framework that preserves no-signaling at the marginal level. The experiment is technically demanding (it requires loophole-free Bell-test geometries combined with high-temporal-resolution arrival-time histogramming on entangled spin pairs) but operationally accessible. Maudlin's group is actively seeking experimental collaborators.

The signaling claim is structurally parallel to Sorkin's: Alice's local choice shifts Bob's marginal distribution at spacelike separation. It differs from Sorkin's in two respects: (i) the local choice is a measurement-apparatus orientation rather than a measurement-operator choice; (ii) the affected quantity is an arrival-time marginal rather than an operator-expectation marginal. The signaling-resolution machinery applicable to one is therefore applicable to the other.

### VII.3 The McGucken No-Signaling Theorem

The resolution comes from Theorem 7.3 of [MG-TwoRoutes §V.8.7], which we reproduce here in the form needed for the present paper.

**Theorem VII.3 (McGucken No-Signaling Theorem; Theorem 7.3 of [MG-TwoRoutes]).** *Let $\mathcal{A}$ and $\mathcal{B}$ be two subsystems on a shared McGucken Sphere $\Sigma_+(p_E)$ centered on a common past emission event $p_E$. Let $\rho^{(\mathcal{A}\mathcal{B})}$ be the joint state inherited from the wavefront identity at $p_E$, and let $\{M^{(\mathcal{A})}_{a,x}\}$ and $\{M^{(\mathcal{B})}_{b,y}\}$ be local measurement settings at $\mathcal{A}$ and $\mathcal{B}$ with outcomes $a$, $b$ and settings $x$, $y$. Then:*

*(i) **Maximal nonlocality.** The joint statistics*
$$P(a, b \mid x, y) = \mathrm{tr}\!\left[\left(M^{(\mathcal{A})}_{a,x} \otimes M^{(\mathcal{B})}_{b,y}\right) \rho^{(\mathcal{A}\mathcal{B})}\right]$$
*exhibit the full Tsirelson-bound violation of CHSH (singlet correlator $E(\mathbf{a}, \mathbf{b}) = -\hat{\mathbf{a}} \cdot \hat{\mathbf{b}}$) as a geometric consequence of shared null-hypersurface origin at $p_E$ (First Law of Nonlocality, Theorem II.6).*

*(ii) **Marginal flatness.** The marginal at each detector,*
$$P(a \mid x) = \sum_b P(a, b \mid x, y), \qquad P(b \mid y) = \sum_a P(a, b \mid x, y),$$
*is independent of the distant setting, by the $SO(3)$ symmetry of $\Sigma_+(p_E)$ and the Born rule applied separately to each subsystem (Theorem II.8).*

*(iii) **No signaling.** The nonlocal channel of (i) carries no usable information: the geometric nonlocality is cloaked by the wavefront-intensity statistics of (ii). This is the no-signaling theorem stated as a property of the physical apparatus (the McGucken Sphere) itself, not of the algebraic formalism.*

***Proof sketch.*** (i) is the First Law of Nonlocality applied to the singlet wavefront on $\Sigma_+(p_E)$: the joint conditional probabilities inherit the $x_4$-cross-channel correlations of the shared four-dimensional wavefront, and these correlations saturate the Tsirelson bound when the wavefront is the singlet null-hypersurface cross-section.

(ii) follows because the Haar measure on $\Sigma_+(p_E)$ is preserved under any single-side operation. Single-side operations act trivially on the $SO(3)$-coorbit of the other subsystem on the shared null hypersurface; equivalently, the McGucken-Sphere isotropy that delivers the Born rule (Theorem II.8) operates separately on each spatial-slice projection of the joint wavefront, and tracing out one subsystem returns the $SO(3)$-uniform marginal independent of the distant setting.

(iii) is the conjunction: the same geometric structure that makes (i) maximally nonlocal makes (ii) flat. Both descend from $dx_4/dt = ic$ acting at $p_E$ with full $SO(3)$ symmetry on the resulting McGucken Sphere. $\blacksquare$

**Corollary VII.4 (Why no-signaling is exact, not approximate).** *The no-signaling property of quantum mechanics is exact — not approximate, not a low-energy effective statement. Under the McGucken Principle this exactness has a single geometric reason: the wavefront $\Sigma_+(p_E)$ is the one and only object on which both nonlocality and probability live. Any deformation of one is a deformation of the other; the cancellation is therefore at the level of the geometry, not at the level of the algebra. This is the structural reason for the exact saturation of the Tsirelson bound $2\sqrt{2}$ across forty years of Bell experiments at separations from millimeters to 1200 km [Aspect1982, Hensen2015, BIG2018]: the saturation and the no-signaling are two consequences of one geometric fact.*

**Corollary VII.5 (Two faces of one expansion).** *The two "strange features" of quantum mechanics historically taken as independent — instantaneous nonlocal correlation [EPR1935, Bell1964, Aspect1982] and irreducible probability [Born1926, Heisenberg1927] — are not two features but one. Each is a face of the single expansion $dx_4/dt = ic$: nonlocality is the wavefront's identity, probability is the wavefront's intensity, and the relation between them is precisely the no-signaling theorem stated geometrically (Theorem VII.3). Nonlocality and probability are not two postulates of nature; they are two faces of the McGucken Sphere generated by the principle.*

### VII.4 Why this resolves the Maudlin–Das signaling claim

The Maudlin–Das prediction is that Bob's marginal arrival-time distribution depends on Alice's magnetic-field orientation. The marginal arrival-time distribution at Bob's detector is precisely the kind of quantity controlled by Theorem VII.3(ii): it is a marginal of Bob's measurement-outcome distribution obtained by summing/integrating over Alice's outcomes. Under the McGucken framework, that marginal is **independent of Alice's setting**, by $SO(3)$ symmetry of the shared McGucken Sphere $\Sigma_+(p_E)$.

This is a strong commitment. The McGucken framework does not say "Bohmian mechanics gives slightly different arrival-time predictions in detail"; it says **the Maudlin–Das prediction of marginal arrival-time signaling is wrong**. The structural reason is geometric, not algebraic: the marginal-flatness condition is forced by the $SO(3)$ symmetry of the source event's McGucken Sphere, which any realist completion of QM that respects Lorentz covariance and emerges from a single source event must preserve.

If the Maudlin–Das experiment is performed and Bob's marginal arrival-time distribution shifts measurably with Alice's magnet orientation, the McGucken framework is falsified. If the marginal is flat (within experimental error), the framework is consistent, and the Bohmian arrival-time prediction in the spin sector requires reformulation.

**Why this matters for the Bohmian arrival-time program specifically.** The Bohmian framework gets clean arrival-time predictions by adding definite particle trajectories — beables not present in standard QM. The McGucken framework gets clean arrival-time predictions by identifying the geometric substrate (the McGucken Sphere) on which the Born rule projects. Both are realist completions of QM, but the two completions differ at exactly the marginal-flatness question. The Bohmian guidance equation, applied to the Pauli/Dirac sector, gives spin-dependent marginal shifts; the McGucken framework's $SO(3)$-symmetric Sphere geometry gives marginal flatness. The Maudlin–Das experiment is therefore a clean empirical fork between these two realist completions, and the McGucken framework predicts the standard-QM no-signaling result on geometric rather than algebraic grounds.

### VII.5 What the McGucken framework offers that the standard derivation does not

The standard derivation of the no-signaling theorem [GRW1980, Eberhard1978, Bussey1982] proceeds purely algebraically: linearity of QM combined with the trace-preserving property of completely positive maps. The marginal $P(a \mid x) = \sum_b P(a, b \mid x, y)$ at one detector is independent of the distant setting $y$ because the partial trace over the distant subsystem returns the same reduced density matrix regardless of what local operation the distant observer performs.

This derivation is mathematically correct but foundationally incomplete in two ways that Maudlin and others have pointed to:

**First**, it has no geometric content. The derivation works equally well in any algebraic formalism with no metric, no light cone, and no specific spacetime structure. This means the algebraic derivation cannot supply the *reason* why nonlocality and no-signaling should coexist; it can only verify that within the algebraic apparatus they happen to. Shimony's "peaceful coexistence" puzzle [Shimony1978] — that QM is nonlocal yet relativistic causality is preserved — receives no answer from the algebraic derivation.

**Second**, it cannot constrain realist completions that add beables. A Bohmian theorist can reasonably reply to the algebraic no-signaling theorem: "your partial-trace argument applies to the standard QM density matrix, but my theory has additional beables (particle positions, trajectories) that are not captured by your reduced density matrix, so your theorem does not constrain my predictions." The Bohmian arrival-time computation respects the algebraic no-signaling theorem for standard QM observables but predicts signaling at the level of the beables. From a purely algebraic standpoint, this is an internal disagreement between two formalisms about what the observables are.

The McGucken framework resolves both gaps. The no-signaling property is forced by the **geometry** of the McGucken Sphere via $SO(3)$ symmetry, not by the algebraic apparatus. Any realist completion of QM that preserves Lorentz covariance and emerges from a shared source event must respect this geometric symmetry; otherwise it breaks Lorentz covariance at the source. The Bohmian arrival-time signaling prediction, if it indeed predicts shifts in Bob's marginal distribution, locates the Bohmian beables outside the $SO(3)$-symmetric structure forced by the source event — which is a structural problem for the Bohmian formulation independent of any experimental test, and which the experiment would expose.

### VII.6 Connection to Shimony's "peaceful coexistence"

Shimony's puzzle of peaceful coexistence [Shimony1978] is that quantum mechanics is genuinely nonlocal (Bell-violation experiments are real) yet relativistic causality is preserved (no signaling has ever been observed). The McGucken framework explains the coexistence as not a coincidence but a single geometric fact: nonlocality and no-signaling are two readings of the same wavefront, with the wavefront identity (the McGucken Sphere as a six-fold geometric locality, Theorem II.2) carrying the nonlocal correlation and the wavefront intensity (the Born-rule projection, Theorem II.8) carrying the marginal probability statistics. The calibration between them is forced by $SO(3)$ symmetry of $dx_4/dt = ic$ acting at the source event. The coexistence is peaceful because both features are projections of one object.

The standard formalism has these as two independent facts to be reconciled; the McGucken framework has them as one fact viewed through two channels (Channel A: algebraic, Born-rule statistics; Channel B: geometric, McGucken Sphere identity). The forty-year empirical record of Bell experiments — saturating Tsirelson at $2\sqrt{2}$ while preserving exact no-signaling at the marginal level [Aspect1982, Hensen2015, Giustina2015, Shalm2015, BIG2018] — is the empirical signature of $dx_4/dt = ic$ acting at every emission event with full $SO(3)$ symmetry on the resulting McGucken Sphere.

### VII.7 Falsifiable empirical prediction

The McGucken framework's prediction for the Maudlin–Das experiment is unambiguous:

**Prediction VII.1 (No spin-dependent arrival-time signaling).** *In an entangled-pair Stern–Gerlach setup with Alice and Bob at spacelike separation, the marginal arrival-time distribution at Bob's detector is independent of Alice's magnetic-field orientation, within experimental error. A successful Maudlin–Das experiment showing Alice-dependent shifts in Bob's marginal arrival-time distribution would falsify the McGucken framework.*

This prediction is sharp, operationally testable with current or near-current technology, and would distinguish the McGucken framework from the Bohmian-arrival-time program. The framework's commitment to the McGucken No-Signaling Theorem (Theorem VII.3) makes the prediction not optional but structural: it is forced by the same $SO(3)$ symmetry that delivers the Born rule, and abandoning it would require abandoning the Born-rule derivation in [MG-Born].

The arrival-time problem in standard QM — the absence of a Hermitian arrival-time operator, identified by Pauli in 1933 — receives an additional interpretation in the McGucken framework. The Pauli no-go is the algebraic shadow of $x_4$'s geometric perpendicularity to the three spatial axes [MG-Commut §1.3]. Asking for a Hermitian arrival-time operator on the spatial Hilbert space is asking for an operator that captures $x_4$-content on a Hilbert space defined over spatial coordinates alone; there is no consistent way to do this, because $x_4$ is geometrically perpendicular to $x_1, x_2, x_3$. The McGucken Sphere supplies the missing structure: arrival time is a property of the Sphere's intersection with the detector surface, a four-dimensional geometric quantity that the spatial-slice Hilbert space cannot capture. The arrival-time question is well-defined in the McGucken framework as a geometric question about Sphere–detector intersection, with the Born rule (Theorem II.8) giving the probability distribution over such intersections via $SO(3)$ projection onto the spatial slice.

---

## VIII. Reeh–Schlieder Vacuum Entanglement (Problem 4)

### VIII.1 Statement of the puzzle

The Reeh–Schlieder theorem [ReehSchlieder1961] asserts that the Minkowski vacuum |0⟩ is cyclic and separating for every local algebra A(O) with O an open bounded region. Cyclicity: the orbit A(O)|0⟩ is dense in the full Hilbert space H. Separating: A ∈ A(O), A|0⟩ = 0 implies A = 0. Together these imply that the local algebras are entangled across spacelike separation — there is no product-state structure |0⟩ = |0_O⟩ ⊗ |0_O'⟩ with O' the spacelike complement.

The physical content of this vacuum entanglement has been disputed. Witten [Witten2018] frames the cyclicity as a statement about reconstruction: in principle, an experiment confined to O alone can reconstruct (in the cyclic-vector sense) any state in H. The puzzle is whether this is "real" entanglement or an artifact of the type-III von Neumann factor structure of A(O).

### VIII.2 Resolution via x₄-coherence

**Theorem VI.1 (Reeh–Schlieder as algebraic shadow of x₄-coherence).** *In the McGucken framework, the Reeh–Schlieder cyclic-and-separating property of |0⟩ for A_M(O) is the algebraic shadow of the geometric fact that the past McGucken Sphere of any event in O extends to all of M\J⁺(O)^c — equivalently, every event in M is in the past or future of some event whose past McGucken Sphere reaches into O. The "vacuum entanglement" is the x₄-coherence of the substrate vacuum across the geometric extent of these past Spheres.*

***Proof sketch.*** The vacuum |0⟩ of the McGucken substrate is, by [MG-Sphere §11–12], the unique state on which x₄-translation acts trivially (modulo phase) and SO(3) rotation acts trivially. Since dx₄/dt = ic at every event, the vacuum is a state coherent across all of x₄ — every event "sees" the same vacuum content along x₄. The local algebra A_M(O) generates excitations of this coherent state in O, and the geometric extent of the past Spheres of O reaches into all spacelike-separated regions M\J⁺(O), giving the cyclic property. The separating property follows from the same coherence: an operator in A_M(O) that annihilates |0⟩ would also annihilate the x₄-coherent extensions, hence is identically zero. □

**Remark VI.1.** Vacuum entanglement is real in the McGucken framework — it is not an artifact. It is the algebraic expression of the geometric coherence of the substrate vacuum across x₄. Entanglement-harvesting protocols [PF2024 §3] succeed because they extract real x₄-coherence from the vacuum into the laboratory. The "paradox" that local operations should not generate entangled pairs from a "true vacuum" dissolves: the McGucken vacuum is x₄-coherent, hence not factorized, hence harvesting is geometrically legitimate.

### VIII.3 No tension with §VI

The Sorkin resolution of §VI uses the empty-causal-completion-intersection condition R_A^⋄_M ∩ R_B^⋄_M = ∅ to obtain commutator-vanishing. The Reeh–Schlieder vacuum entanglement is not in tension with this: the entanglement is at the level of the **state**, not the **algebra**. Two algebras can commute (no signaling) while their joint state is non-factorized (entangled). This is the standard distinction between "state-level entanglement" and "algebraic-locality" that resolves the Bell-inequality problem in §VII.

---

## IX. The Bell Locality/Realism Dilemma (Problem 5)

### IX.1 Statement

Bell's theorem [Bell1964] shows that no theory satisfying (i) signal locality, (ii) statistical independence, and (iii) outcome-realism (predetermined measurement outcomes) can reproduce the predictions of quantum mechanics for a maximally-entangled spin-singlet pair. Experimental tests [Aspect1982, Hensen2015] confirm the QM predictions and falsify at least one of (i)–(iii).

Standard quantum field theory preserves (i) signal locality via spacelike microcausality but pays the price of giving up (iii) outcome-realism — measurement outcomes are not predetermined; they are generated at the moment of measurement. The "realism" component of (iii) is what the McGucken framework must address.

### IX.2 The First Law of Nonlocality (Theorem II.6) is the resolution

**Theorem VII.1 (Bell-correlation legitimacy in the McGucken framework).** *Any pair of systems exhibiting Bell-correlation violations of inequality (i.e., entangled systems) traces, in the McGucken framework, to a common spacetime event — a "shared origin" in the past — at which the systems became entangled via local interaction. Bell-violating measurements at far-separated detectors do not signal between the detectors; they reveal correlations established at the past origin.*

***Proof.*** This is the First Law of Nonlocality (Theorem II.6, [MG-Nonlocality §2]) applied to the experimentally-relevant setup. In every Bell experiment ever performed [Aspect1982, Hensen2015, Giustina2015], the two photons (or atoms, or ions) were emitted from a common source — a shared spacetime event in the past. The future light cones of this shared event include both detectors, so the entanglement is carried locally along the McGucken Spheres of the source event to both detectors. □

**Remark VII.1 (No tension with signal locality).** The Bell correlations in the McGucken framework are nonlocal at the **state** level (the wavefunction does not factorize) and local at the **algebra** level (the measurement operators commute). The nonlocality is the geometric coherence of the McGucken Sphere from the source event to the two detectors; the locality of measurement is the geometric microcausality of Theorem IV.3. Both hold simultaneously. There is no superluminal signaling, only superluminal **correlation** — and correlation alone, without communication, does not violate relativity.

**Remark VII.2 (Realism in the McGucken framework).** Outcome-realism (predetermined values for all observables) fails in the McGucken framework, as in standard QM. What is realist is the **geometric origin** of every entanglement: every Bell correlation has a real, locally-traceable spacetime origin. Bell's "realist" hidden-variable theory is replaced by a **geometric** common-origin theorem. The McGucken framework retains realism at the level of geometric origin while sacrificing it at the level of pre-existing measurement values.

---

## X. Photon Non-Localizability and Lamb's Anti-Photon Argument (Problem 6)

### X.1 Lamb's argument

Lamb [Lamb1995] argues that the photon, as defined in standard QED via Fock-space creation operators a†(k, λ), is not a well-defined spatially-localized particle: there is no position operator on the photon Fock space, no Newton–Wigner localization in three dimensions for the photon (because of the photon's masslessness), and the standard "photon" is an asymptotic Fock state rather than a spatially localized object.

The argument is physically correct as a critique of the localization formalism. The McGucken framework affirms it by giving the geometric reason.

### X.2 The photon is a dx₄/dτ = 0 case of the McGucken Principle

**Theorem VIII.1 (Photon as x₄-stationary case** [MG-Sphere §3.2; MG-Feynman §III.4]**).** *Under the McGucken Principle, a photon is a quantum that satisfies dx₄/dτ = 0 along its worldline. Equivalently, it is a quantum whose entire four-speed budget (Theorem II.1 of [MG-Sphere], the master equation u^μ u_μ = −c²) is directed into the three spatial dimensions, with zero advance along x₄. Such a quantum has no rest-frame Compton oscillation (since no proper time elapses along its worldline) and is fundamentally a wavefront on the McGucken Sphere of its emission event, not a localized particle.*

***Proof sketch.*** From Proposition II.1 of [MG-Sphere], a particle's four-velocity satisfies (dx/dt)² + (dy/dt)² + (dz/dt)² + |dx₄/dt|² = c². For a particle moving at |v| = c, the spatial budget is c² and the x₄ budget is 0. Therefore |dx₄/dt| = 0 along the photon's worldline — equivalently, dx₄/dτ = 0 with τ the proper-time parameter. □

### X.3 Why Lamb is right and the formalism is right

Lamb's anti-photon argument is correct: the photon has no rest frame, no Newton–Wigner position operator, no Compton oscillation, no localization in the "particle" sense. The McGucken framework supplies the geometric reason: the photon is not a particle in the four-dimensional sense; it is a wavefront on Σ₊(p_emission). Asking for the photon's "position" is asking for a point on a sphere, which has only a 2-sphere worth of information per coordinate-time slice, not a 3D volume of position information.

The standard QED formalism, which uses Fock-space creation operators a†(k, λ) to "create photons," is internally consistent because the Fock states are defined as plane waves, not as localized particles. The "photon" of QED is the **wavefront**, not a "tiny particle of light."

This dissolves the apparent contradiction Lamb identifies between "photons exist" (because we detect them) and "photons are not localizable" (because the localization formalism breaks down). The detection event is a localization event, but localization happens only at the moment of detection — it is an event in spacetime where the photon's wavefront on Σ₊ collapses, by Born-rule-as-Σ₊-projection (Theorem II.8), to a single point.

---

## XI. Operational Meaning of Clocks and Rulers at the Planck Scale (Problem 1)

### XI.1 The standard tension

Quantum field theory in continuum spacetime allows test functions of arbitrarily small support in any direction. Gravity, by contrast, sets a Planck-scale floor on spatial localization: an attempt to localize a quantum within a region smaller than λ_P forms a black hole (the energy required to confine the quantum within Δx grows as ℏ/Δx, and at Δx ~ λ_P the corresponding energy is ~ m_P c², the Planck energy, whose Schwarzschild radius is ~ λ_P). The two formalisms — continuum QFT and gravitational localization — are operationally inconsistent below λ_P [Doplicher1995].

### XI.2 The hybrid measure resolves the tension

**Theorem IX.1 (Operational consistency at λ_P).** *Under Hypothesis II.3 (the hybrid spacetime measure dμ = d³x · a₄ Σₙ δ(x₄ − na₄) dx₄ with a₄ = λ_P), the McGucken substrate accommodates spatial localization to arbitrarily small Δx (continuous spatial directions) while x₄-localization is bounded below by the lattice spacing λ_P. The Brillouin-zone restriction on x₄-conjugate momenta (Theorem II.4 / Theorem III.2) provides the natural Planck-scale cutoff for x₄-direction modes without imposing a spatial cutoff.*

***Proof sketch.*** The substrate of Hypothesis II.3 is continuous in x₁, x₂, x₃ and discrete in x₄. Spatial localization is unbounded above (continuous spatial directions); x₄-localization is bounded by λ_P (discrete x₄ direction). The dispersion relation along x₄ (Proposition II.5) provides finite x₄-momenta for all modes; combined with the spatial continuum, this gives operationally well-defined clocks and rulers in three dimensions, with the Planck-scale floor appearing only in the x₄ direction. □

**Remark IX.1 (Why this is consistent with physical intuition about Planck-scale clocks).** The standard intuition is that **clocks** (timekeeping devices) cannot operate at Planck-scale resolution: a clock measuring time intervals smaller than t_P would require a quantum more energetic than m_P c², which would form a black hole. In the McGucken framework, t_P = λ_P/c is the time required for x₄ to advance by one lattice spacing. Clocks at Planck resolution attempt to resolve x₄ at sub-lattice intervals, which is geometrically impossible. The Planck-scale clock floor is not a quantum-gravity effect imposed externally; it is the geometric structure of x₄'s advance.

**Rulers**, by contrast, measure spatial separation. The McGucken framework leaves the spatial directions continuous, so rulers can operate at arbitrarily fine resolution **in space**. The Planck-scale floor is on **time** (x₄-direction), not on space. This asymmetry between time and space at the Planck scale is a prediction of the McGucken framework and distinguishes it from continuum-quantum-gravity proposals (Loop Quantum Gravity, causal sets) that impose Planck-scale floors on both.

---

## XII. Wave-Function Collapse Incompatible with Relativity (Problem 2)

### XII.1 The standard puzzle

In a relativistic measurement scenario, an instantaneous wave-function collapse triggered by a measurement at one spacetime point appears to update the wavefunction across spacelike separation. This is in tension with Lorentz invariance: different observers disagree about which slice of constant time should be the "collapse slice" [Penrose1989, Bell1990, GianMarchi1995]. The standard responses (decoherence, many-worlds, dynamical-collapse models, relational QM) each have known shortcomings.

### XII.2 No collapse in the McGucken framework

**Theorem X.1 (No wave-function collapse).** *In the McGucken framework, there is no wave-function collapse. The Born rule (Theorem II.8) is a probability assignment for **detection** at a point on the McGucken Sphere Σ₊(p_emission) of the source event, not a state-update propagating across spacelike separation. The "post-measurement state" is the state on the past Sphere of the next measurement event, computed from the observed outcome as a Bayesian update with the Born-rule likelihood.*

***Proof sketch.*** The Born rule, in [MG-Born], is the SO(3)-invariant probability measure on Σ₊(p_emission) restricted by the wavefunction. The measure assigns probability to detection events on Σ₊, not to "collapse events" on a spacelike slice. After a detection event at p_detect, the wavefunction relevant for subsequent measurements is the wavefunction restricted to Σ₊(p_detect), which is the natural geometric continuation. No instantaneous-across-space update is required. The "post-measurement state" is a future McGucken Sphere, not a Cauchy-slice wavefunction. □

**Remark X.1 (The Wigner's-friend paradox dissolves).** The Wigner's-friend scenario, in which observer F measures a system inside a sealed laboratory while observer W treats the entire laboratory as a quantum system, is paradoxical only if collapse is real. In the McGucken framework, F's "measurement" is a detection event at p_F that initiates a new McGucken Sphere Σ₊(p_F), and W's "measurement" is a separate detection event at p_W initiating Σ₊(p_W). The two events are not in tension; they correspond to different McGucken Spheres at different stages of the experiment. There is no single wavefunction across all space that "collapses" at one event and propagates the collapse to another.

---

## XIII. QFT Presupposes a Classical GR Background (Problem 7)

### XIII.1 The structural mismatch

Standard quantum field theory on curved spacetime takes the metric g_μν as classical and the matter fields as quantum. The Einstein equations G_μν = 8πG ⟨T_μν⟩ (with the right-hand side a quantum expectation value) couple a quantum source to a classical receiver — a structurally inconsistent setup unless the quantum nature of T_μν is "absorbed" by some yet-unknown quantization of g_μν (i.e., quantum gravity).

### XIII.2 The McGucken framework dissolves the mismatch

**Theorem XI.1 (No quantization of gravity is needed** [MG-Vanquishing Theorem 2; MG-Cosmology]**).** *Under the McGucken Principle, gravity is the geometric consequence of the invariant x₄-advance dx₄/dt = ic meeting the spatial-direction stretching induced by mass. There is no graviton: the gravitational field is not a propagating quantum field but a structural feature of how x₄'s advance interacts with the matter-induced spatial geometry. The Einstein equations are derived in [MG-Cosmology] from the McGucken Principle without quantization of g_μν.*

***Proof reference.*** The full derivation of the Einstein equations from dx₄/dt = ic is in [MG-Cosmology] and uses Schuller's constructive-gravity closure [MG-SM, Theorem 12]. The key fact for the present paper is that gravity emerges from the geometry of x₄'s advance and does not require a quantized graviton field. The QFT-on-classical-GR mismatch is dissolved because there is no quantization of gravity to seek. □

**Remark XI.1 (Falsifiable consequence: no graviton).** The McGucken framework predicts that no graviton exists. Any successful direct detection of an individual graviton (as opposed to detection of a classical gravitational wave with classical statistics) would falsify the framework. This is a strict and operational falsification criterion.

---

## XIV. Gravity-Induced Entanglement (BMV) (Problem 8)

### XIV.1 The BMV protocol

Bose, Mazumdar, Marletto, and Vedral [Bose2017, MV2017] propose that two test masses, each in superposition of two spatial paths, can become entangled via their mutual gravitational interaction alone. The standard interpretation is that successful BMV detection would prove the quantum nature of gravity (because only a quantum mediator can entangle two systems via interaction).

### XIV.2 The McGucken framework predicts BMV entanglement without a graviton

**Theorem XII.1 (BMV entanglement from McGucken geometry).** *In the McGucken framework, two test masses m_1 and m_2, each in spatial superposition, become entangled via their mutual interaction with the spatial geometry stretched by each mass. The entanglement is carried by the McGucken Spheres of each mass — not by a quantum graviton — and is therefore real entanglement without a graviton mediator. The BMV protocol, if successful, does not prove the quantum nature of gravity; it proves the geometric coupling of matter through spatial-geometry stretching, which is a theorem of dx₄/dt = ic via the McGucken Principle.*

***Proof sketch.*** Each mass m_i, by [MG-Cosmology], stretches the spatial geometry around itself. The two masses' spatial-geometry stretchings interact when their McGucken Spheres overlap (i.e., when the two masses are in mutual past-light-cone reach). The interaction couples the two masses' position superpositions through the geometric stretching, generating entanglement without an exchanged quantum. The First Law of Nonlocality (Theorem II.6) is satisfied: the entanglement traces back to the moment when the McGucken Spheres of the two masses first overlapped. □

**Remark XII.1 (The Galley–Giacomini–Selby challenge to BMV is sidestepped).** Galley, Giacomini, and Selby [Galley2023] argue that BMV entanglement does not by itself prove the quantum nature of gravity, because classical mediators with the right structure could in principle entangle the systems. The McGucken framework agrees: the BMV result is consistent with classical (geometric) gravity. The mediator is the spatial-geometry stretching, which is a classical (i.e., not field-quantized) consequence of dx₄/dt = ic.

---

## XV. General Relativity Predicts Its Own Breakdown (Problem 9)

### XV.1 The Schwarzschild interior pathology

The Schwarzschild solution to the vacuum Einstein equations, extended to its full Kruskal manifold, contains a curvature singularity at r = 0. The Penrose–Hawking singularity theorems [Penrose1965, Hawking1970] show that this is generic: classical general relativity predicts singular endpoints under broad assumptions about energy conditions and global hyperbolicity.

### XV.2 Vanquishing-Infinities Theorem 2 forecloses the Schwarzschild interior

**Theorem XIII.1 (Schwarzschild-Kruskal interior foreclosure** [MG-Vanquishing Theorem 2]**).** *Under three independent axioms, each a theorem of dx₄/dt = ic — (A1) dx₄/dt = ic is invariant; (A2) mass bends spatial directions; (A3) momentum-energy in x₄ has no rest mass — the Schwarzschild-Kruskal interior is axiomatically foreclosed. Each axiom independently rules out the interior; the pathological r → 0 limit corresponds to an inconsistency with the McGucken Principle, not to a singular limit.*

***Proof reference.*** The full proof is in [MG-Vanquishing §5–6]. The key fact for the present paper is that the framework predicts, structurally, that the Schwarzschild interior is not part of physically realized spacetime. This dissolves the "general relativity predicts its own breakdown" problem: GR does not predict its own breakdown in the McGucken framework, because the interior solutions where breakdown occurs are not in the physical state space. □

**Remark XIII.1 (Maximum curvature at the horizon).** [MG-Vanquishing] gives K_max = 3c⁸/(4G⁴M⁴) at the Schwarzschild horizon r = 2GM/c². Beyond this, the interior is foreclosed; curvature does not diverge to infinity at any physical event. The Penrose–Hawking singularity theorems are not violated; they are restricted to the physical part of spacetime, which excludes the foreclosed interior.

---

## XVI. Falsifiable Predictions and Summary

### XVI.1 Falsifiable predictions

The McGucken framework makes the following operational predictions:

1. **No graviton.** Direct detection of an individual graviton would falsify the framework.
2. **Spectrum cutoff in x₄-conjugate momentum at πℏ/λ_P = πm_P c.** Cosmic-ray spectra above the equivalent energy (combined with the dispersion relation along x₄, ~m_P c²) would falsify the framework.
3. **No wave-function collapse signaling.** Sorkin-type signaling experiments in any operational regime would falsify the framework (consistent with currently-observed no-signaling).
4. **No spin-dependent arrival-time signaling (Maudlin–Das).** The Das–Nöth–Dürr–Goldstein Bohmian prediction [DasDurr2019, DasNoethDurr2021, DasNoethDurr2022, Maudlin2023] that Alice's spin-measurement orientation shifts Bob's marginal arrival-time distribution at a spacelike-separated detector is **denied** by the McGucken framework. Theorem VII.3 (McGucken No-Signaling Theorem) forces marginal flatness at Bob's detector by SO(3) symmetry of the source-event McGucken Sphere. A successful Maudlin–Das experiment showing Alice-dependent shifts in Bob's marginal arrival-time distribution would falsify the framework. This is the sharpest current empirical fork between the framework and the Bohmian arrival-time program.
5. **BMV entanglement without graviton mediation.** A successful BMV experiment is consistent with the framework; a graviton-detection experiment that succeeds would falsify it.
6. **Schwarzschild-Kruskal interior is unphysical.** Any direct observational evidence for sub-horizon physics that contradicts McGucken-framework predictions (e.g., via gravitational-wave signatures of interior dynamics) would falsify the framework.

### XVI.2 Summary table of resolutions

| # | Problem | McGucken theorem | Reference |
|---|---|---|---|
| 1 | Planck-scale clocks/rulers | Hybrid measure, Brillouin zone B = [−πℏ/λ_P, +πℏ/λ_P] | §XI, [MG-Vanquishing] |
| 2 | Wave-function collapse vs relativity | Born rule as Σ₊ projection; no collapse | §XII, [MG-Born] |
| 3 | Sorkin impossible measurements | Algebraic microcausality from McGucken Causal Completion | §VI, [MG-Sphere §15] |
| 3* | Maudlin–Das arrival-time signaling | McGucken No-Signaling Theorem; marginal flatness from SO(3) symmetry | §VII, Theorem VII.3 |
| 4 | Reeh–Schlieder vacuum entanglement | x₄-coherence of vacuum across past Spheres | §VIII, [MG-Sphere §11–12] |
| 5 | Bell locality/realism | First Law of Nonlocality: common origin in past | §IX, [MG-Nonlocality §2] |
| 6 | Photon non-localizability | Photon as dx₄/dτ = 0 wavefront on Σ₊ | §X, [MG-Sphere §3.2] |
| 7 | QFT on classical GR background | Gravity is geometric, no graviton needed | §XIII, [MG-Cosmology] |
| 8 | BMV gravity-induced entanglement | Entanglement via geometric stretching, not graviton | §XIV, [MG-Cosmology] |
| 9 | GR predicts its own breakdown | Schwarzschild-Kruskal interior axiomatically foreclosed | §XV, [MG-Vanquishing Theorem 2] |

### XVI.3 Errors corrected from the May 9 draft

The present paper corrects three errors from the May 9 draft:

1. **Brillouin zone units.** B is a momentum interval [−πℏ/λ_P, +πℏ/λ_P] = [−πm_P c, +πm_P c], not an energy interval [−πm_P c², +πm_P c²]. Corrected throughout, with the dispersion relation along x₄ stated explicitly (Proposition II.5).
2. **Theorem 1 statement.** The May 9 draft asserted that spec(O_f) ⊂ ℝ³ × B, conflating spectrum with support. The corrected statement (Theorem III.2) is a support theorem: supp(f̃) ⊂ ℝ³ × B for any substrate-compatible test function f.
3. **Theorem 2 Riemann–Lebesgue invocation.** The May 9 draft invoked Riemann–Lebesgue to claim decay of correlation functions on a compact x₄-momentum domain B, where Riemann–Lebesgue gives only continuity. Replaced (Theorem VI.2) with an explicit Schwartz-decay bound in the spatial directions, which is the actual hypothesis available.

---

## XVII. Conclusion

The Sorkin impossible-measurements problem and eight companion QFT measurement pathologies resolve, simultaneously and structurally, as theorems of the McGucken Principle dx₄/dt = ic. The resolution mechanism is geometric: the McGucken Sphere is the foundational atom of spacetime, six-fold local in independent mathematical senses, supporting both algebraic microcausality (which forecloses Sorkin signaling) and state-level entanglement (which preserves Reeh–Schlieder vacuum entanglement and Bell correlations). The hybrid spacetime measure with x₄-discretization at λ_P provides a Planck-scale floor on x₄-direction modes via the Brillouin zone B = [−πℏ/λ_P, +πℏ/λ_P], a **momentum** interval. The dispersion relation along x₄ converts this momentum bound to an energy bound at the Planck energy via the standard discrete-lattice dispersion. The framework predicts no graviton, no wave-function collapse, and no Schwarzschild-Kruskal interior. Each of these predictions is operationally falsifiable.

The framework is not new: dx₄/dt = ic was identified by the author in undergraduate work at Princeton in the late 1980s, formalized in the 1998–1999 UNC dissertation appendix, developed through five FQXi essays (2008–2013) and a book series (2016–2017), and given its current rigorous form in approximately forty papers (October 2024 – May 2026) at elliotmcguckenphysics.com. The thirty-seven-year priority record is multiply documented (Princeton recommendation letter, Wayback Machine, Google Groups Usenet archives, FQXi indexing, DKIM-signed Gmail records). Sorkin's 1993 paper, the FLAMM measurement model of 2021, the Verch–Fewster framework of 2020, the Borsten–Jubb–Kells regularization of 2021, Mandrysch–Navascués 2024, and Fewster's 2025 lectures all postdate the McGucken Principle's foundational establishment. The present paper unifies the Sorkin problem and its companions under that prior foundation.

---

## References

### A. Standard Physics Literature

[AB1961] Y. Aharonov and D. Bohm, "Time in the Quantum Theory and the Uncertainty Relation for Time and Energy," *Physical Review* **122**, 1649 (1961).

[Allcock1969] G. R. Allcock, "The Time of Arrival in Quantum Mechanics," *Annals of Physics* **53**, 253, 286, 311 (1969), three-part series.

[Aspect1982] A. Aspect, P. Grangier, and G. Roger, "Experimental Realization of Einstein–Podolsky–Rosen–Bohm Gedankenexperiment: A New Violation of Bell's Inequalities," *Physical Review Letters* **49**, 91 (1982).

[Bell1964] J. S. Bell, "On the Einstein Podolsky Rosen Paradox," *Physics Physique Fizika* **1**, 195 (1964).

[Bell1990] J. S. Bell, "Against 'measurement,'" *Physics World* **3**, 33 (1990).

[BIG2018] BIG Bell Test Collaboration, "Challenging local realism with human choices," *Nature* **557**, 212 (2018).

[BJK2021] L. Borsten, I. Jubb, and G. Kells, "Impossible measurements revisited," arXiv:1912.06141 (2019/2021).

[Born1926] M. Born, "Zur Quantenmechanik der Stoßvorgänge," *Zeitschrift für Physik* **37**, 863 (1926).

[Bose2017] S. Bose, A. Mazumdar, G. W. Morley, H. Ulbricht, M. Toroš, M. Paternostro, A. Geraci, P. F. Barker, M. S. Kim, and G. Milburn, "A Spin Entanglement Witness for Quantum Gravity," *Physical Review Letters* **119**, 240401 (2017).

[BFR2021] H. Bostelmann, C. J. Fewster, and M. H. Ruep, "Impossible measurements require impossible apparatus," *Physical Review D* **103**, 025017 (2021).

[Bussey1982] P. J. Bussey, "'Super-luminal communication' in Einstein–Podolsky–Rosen experiments," *Physics Letters A* **90**, 9 (1982).

[DasDurr2019] S. Das and D. Dürr, "Arrival time distributions of spin-1/2 particles," *Scientific Reports* **9**, 2242 (2019); arXiv:1901.08672.

[DasNoethDurr2021] S. Das, M. Nöth, and D. Dürr, "Exotic Bohmian arrival times of spin-1/2 particles: An analytical treatment," *Physical Review A* **99**, 052124 (2019); arXiv:1901.08672 / arXiv:2101.08217.

[DasNoethDurr2022] S. Das and M. Nöth, "Times of arrival and gauge invariance," *Proceedings of the Royal Society A* **477**, 20210101 (2021); see also arXiv:2102.02661.

[Doplicher1995] S. Doplicher, K. Fredenhagen, and J. E. Roberts, "The quantum structure of spacetime at the Planck scale and quantum fields," *Communications in Mathematical Physics* **172**, 187 (1995).

[dRPM2021] J. de Ramón, M. Papageorgiou, and E. Martín-Martínez, "Causality and Signalling in Non-Compact Detector-Field Interactions," arXiv:2102.03408 (2021).

[Eberhard1978] P. H. Eberhard, "Bell's theorem and the different concepts of locality," *Il Nuovo Cimento B* **46**, 392 (1978).

[EPR1935] A. Einstein, B. Podolsky, and N. Rosen, "Can quantum-mechanical description of physical reality be considered complete?" *Physical Review* **47**, 777 (1935).

[Fewster2025] C. J. Fewster, "Lectures on measurement schemes in quantum field theory," arXiv:2504.17437 (2025).

[FV2020] C. J. Fewster and R. Verch, "Quantum fields and local measurements," *Communications in Mathematical Physics* **378**, 851 (2020); arXiv:1810.06512.

[Galley2023] T. D. Galley, F. Giacomini, and J. H. Selby, "A no-go theorem on the nature of the gravitational field beyond quantum theory," *Physical Review D* **108**, L101702 (2023); arXiv:2208.09489.

[GianMarchi1995] G. C. Ghirardi, "Properties and Events in a Relativistic Context: Revisiting the Dynamical Reduction Program," *Foundations of Physics Letters* **8**, 109 (1995).

[Giustina2015] M. Giustina et al., "Significant-Loophole-Free Test of Bell's Theorem with Entangled Photons," *Physical Review Letters* **115**, 250401 (2015).

[GRT1996] N. Grot, C. Rovelli, and R. S. Tate, "Time of arrival in quantum mechanics," *Physical Review A* **54**, 4676 (1996).

[GRW1980] G. C. Ghirardi, A. Rimini, and T. Weber, "A general argument against superluminal transmission through the quantum mechanical measurement process," *Lettere al Nuovo Cimento* **27**, 293 (1980).

[Haag1996] R. Haag, *Local Quantum Physics: Fields, Particles, Algebras* (2nd ed., Springer, 1996).

[Hawking1970] S. W. Hawking and R. Penrose, "The Singularities of Gravitational Collapse and Cosmology," *Proceedings of the Royal Society A* **314**, 529 (1970).

[Heisenberg1927] W. Heisenberg, "Über den anschaulichen Inhalt der quantentheoretischen Kinematik und Mechanik," *Zeitschrift für Physik* **43**, 172 (1927).

[Hensen2015] B. Hensen et al., "Loophole-free Bell inequality violation using electron spins separated by 1.3 kilometres," *Nature* **526**, 682 (2015).

[Kijowski1974] J. Kijowski, "On the time operator in quantum mechanics and the Heisenberg uncertainty relation for energy and time," *Reports on Mathematical Physics* **6**, 361 (1974).

[Lamb1995] W. E. Lamb Jr., "Anti-photon," *Applied Physics B* **60**, 77 (1995).

[MV2017] C. Marletto and V. Vedral, "Gravitationally Induced Entanglement between Two Massive Particles is Sufficient Evidence of Quantum Effects in Gravity," *Physical Review Letters* **119**, 240402 (2017).

[Maudlin2023] T. Maudlin, *Philosophy of Physics: Quantum Theory* (Princeton University Press, 2019), and "Sean Carroll Mindscape Podcast 241: Tim Maudlin on Locality, Hidden Variables, and Quantum Foundations" (June 2023), https://www.preposterousuniverse.com/podcast/2023/06/26/241-tim-maudlin-on-locality-hidden-variables-and-quantum-foundations/

[Minkowski1908] H. Minkowski, "Raum und Zeit," lecture delivered at the 80. Versammlung Deutscher Naturforscher und Ärzte (Cologne, 21 September 1908); published in *Physikalische Zeitschrift* **10**, 75 (1909).

[MN2024] J. Mandrysch and M. Navascués, "Quantum field theory consistent measurement schemes," arXiv:2411.13605 (2024).

[MuPaGo2000] J. G. Muga, R. Sala Mayato, and Í. L. Egusquiza (eds.), *Time in Quantum Mechanics, Vols. 1–2*, Lecture Notes in Physics (Springer, 2002, 2008). Comprehensive review of the ~20 distinct approaches to the arrival-time problem in standard QM.

[Oppenheim2018] J. Oppenheim, "A post-quantum theory of classical gravity?" arXiv:1811.03116 (2018).

[Pauli1933] W. Pauli, "Die allgemeinen Prinzipien der Wellenmechanik," in *Handbuch der Physik*, vol. 24/1, ed. H. Geiger and K. Scheel (Springer, Berlin, 1933), p. 83 ff.; reprinted in *Encyclopedia of Physics*, vol. V/1 (Springer, 1958). Original statement of the no-go theorem on Hermitian arrival-time operators conjugate to a bounded-below Hamiltonian.

[PF2024] M. Papageorgiou and D. Fraser, "Eliminating the 'impossible': Recent progress on local measurement theory for quantum field theory," *Foundations of Physics* **54**, 26 (2024).

[Penrose1965] R. Penrose, "Gravitational Collapse and Space-Time Singularities," *Physical Review Letters* **14**, 57 (1965).

[Penrose1989] R. Penrose, *The Emperor's New Mind* (Oxford University Press, 1989).

[PGM2022] J. Polo-Gómez, L. J. Garay, and E. Martín-Martínez, "A detector-based measurement theory for quantum field theory," *Physical Review D* **105**, 065003 (2022); arXiv:2108.02793.

[PR1994] S. Popescu and D. Rohrlich, "Quantum nonlocality as an axiom," *Foundations of Physics* **24**, 379 (1994).

[ReehSchlieder1961] H. Reeh and S. Schlieder, "Bemerkungen zur Unitäräquivalenz von Lorentzinvarianten Feldern," *Il Nuovo Cimento* **22**, 1051 (1961).

[Shalm2015] L. K. Shalm et al., "Strong Loophole-Free Test of Local Realism," *Physical Review Letters* **115**, 250402 (2015).

[Shimony1978] A. Shimony, "Metaphysical problems in the foundations of quantum mechanics," *International Philosophical Quarterly* **18**, 3 (1978). Origin of the "peaceful coexistence" framing of QM nonlocality and relativistic causality.

[Sorkin1993] R. D. Sorkin, "Impossible measurements on quantum fields," in *Directions in General Relativity* (Cambridge UP, 1993), arXiv:gr-qc/9302018.

[Streater–Wightman1964] R. F. Streater and A. S. Wightman, *PCT, Spin and Statistics, and All That* (Benjamin, 1964).

[Tsirelson1980] B. S. Tsirelson, "Quantum generalizations of Bell's inequality," *Letters in Mathematical Physics* **4**, 93 (1980).

[Wald1994] R. M. Wald, *Quantum Field Theory in Curved Spacetime and Black Hole Thermodynamics* (University of Chicago Press, 1994).

[Werner1986] R. F. Werner, "Screen observables in relativistic and nonrelativistic quantum mechanics," *Journal of Mathematical Physics* **27**, 793 (1986).

[Witten2018] E. Witten, "APS Medal for Exceptional Achievement in Research: Invited article on entanglement properties of quantum field theory," *Reviews of Modern Physics* **90**, 045003 (2018).

### B. McGucken Corpus

[McGucken2016] E. McGucken, *Light Time Dimension Theory: The Foundational Physics Unifying Einstein's Relativity and Quantum Mechanics* (45EPIC Press, 2016).

[McGucken2017a] E. McGucken, *Einstein's Relativity Derived from LTD Theory's Principle* (45EPIC Press, 2017).

[McGucken2017b] E. McGucken, *Relativity and Quantum Mechanics Unified in Pictures* (45EPIC Press, 2017).

[McGucken2017c] E. McGucken, *Quantum Entanglement and Einstein's "Spooky Action at a Distance" Explained via LTD Theory's Expanding Fourth Dimension* (45EPIC Press, 2017).

[McGucken2017d] E. McGucken, *The Physics of Time: Time & Its Arrows in Quantum Mechanics, Relativity, The Second Law of Thermodynamics, Entropy, The Twin Paradox, & Cosmology Explained via LTD Theory's Expanding Fourth Dimension* (45EPIC Press, 2017).

[MG-Born] E. McGucken, "The Born Rule as McGucken-Sphere Projection: Derivation from dx₄/dt = ic," elliotmcguckenphysics.com (2025).

[MG-Commut] E. McGucken, "The Canonical Commutation Relation [q̂, p̂] = iℏ as the Algebraic Marker of x₄-Perpendicularity: A Theorem of the McGucken Principle dx₄/dt = ic," elliotmcguckenphysics.com (2025).

[MG-Cosmology] E. McGucken, "McGucken Cosmology: First-Place Performance Across Twelve Independent Observational Tests with Zero Free Dark-Sector Parameters," elliotmcguckenphysics.com (2026).

[MG-Dirac] E. McGucken, "The Dirac Equation as a Theorem of the McGucken Principle dx₄/dt = ic: Spin-½ from x₄-Perpendicular Clifford Algebra," elliotmcguckenphysics.com (2025).

[MG-Dissertation] E. McGucken, *Multiple Unit Artificial Retina Chipset (MARC) to Aid the Visually Impaired*, Ph.D. dissertation, University of North Carolina at Chapel Hill (1999); physics theory in appendix.

[MG-Equiv] E. McGucken, "The McGucken Equivalence: Quantum Nonlocality as Geometric Coincidence on the Light Cone," elliotmcguckenphysics.com (2025).

[MG-FB] E. McGucken, *Elliot McGucken Physics* Facebook Group (2017–present), https://www.facebook.com/groups/elliotmcguckenphysics/

[MG-Feynman] E. McGucken, "Feynman Diagrams as Theorems of the McGucken Principle: Propagators, Vertices, Loops, Wick Contractions, and the Dyson Expansion as Iterated Huygens-with-Interaction on the Expanding Fourth Dimension," elliotmcguckenphysics.com (April 2026), https://elliotmcguckenphysics.com/2026/04/23/feynman-diagrams-as-theorems-of-the-mcgucken-principle-propagators-vertices-loops-wick-contractions-and-the-dyson-expansion-as-iterated-huygens-with-interaction-on-the-expanding-fourth-dimension/

[MG-FQXi-2008] E. McGucken, "Time as an Emergent Phenomenon: Traveling Back to the Heroic Age of Physics (In Memory of John Archibald Wheeler)," FQXi essay contest entry, August 25, 2008.

[MG-FQXi-2009] E. McGucken, FQXi essay contest entry (2009).

[MG-FQXi-2010] E. McGucken, FQXi essay contest entry (2010).

[MG-FQXi-2012] E. McGucken, FQXi essay contest entry (2012).

[MG-FQXi-2013] E. McGucken, FQXi essay contest entry (2013).

[MG-History] E. McGucken, "Provenance of the McGucken Principle: A Documented Chronology 1988–2026," elliotmcguckenphysics.com (2026).

[MG-Lagrangian] E. McGucken, "The McGucken Lagrangian: Unique Forced Form of the Four-Sector Lagrangian from dx₄/dt = ic," elliotmcguckenphysics.com (April 2026).

[MG-Medium] E. McGucken, *Dr. Elliot McGucken Theoretical Physics*, https://goldennumberratio.medium.com/ (2020–present).

[MG-Nonlocality] E. McGucken, "The McGucken Nonlocality Principle: All Quantum Nonlocality Begins in Locality, and All Double-Slit, Quantum-Eraser, and Delayed-Choice Experiments Exist in McGucken Spheres," elliotmcguckenphysics.com (April 17, 2026), https://elliotmcguckenphysics.com/2026/04/17/the-mcgucken-nonlocality-principle-all-quantum-nonlocality-begins-in-locality-and-all-double-slit-quantum-eraser-and-delayed-choice-experiments-exist-in-mcgucken-spheres/

[MG-Noether] E. McGucken, "Noether's Theorems and the Conservation Laws of Nature as Theorems of the McGucken Principle dx₄/dt = ic," elliotmcguckenphysics.com (2025).

[MG-OscPrinc] E. McGucken, "The Oscillatory Form of the McGucken Principle: Setting c and ℏ from x₄'s Discrete Advance," elliotmcguckenphysics.com (2026).

[MG-PathInt] E. McGucken, "The Feynman Path Integral as Iterated Huygens Expansion: A Theorem of the McGucken Principle dx₄/dt = ic," elliotmcguckenphysics.com (2025).

[MG-PrincetonAfternoons] E. McGucken, "Princeton Afternoons with Wheeler, Peebles, and Taylor: The Origin of the McGucken Principle," elliotmcguckenphysics.com (2026).

[MG-Proof] E. McGucken, "The McGucken Proof: Derivation of the Minkowski Metric and Special Relativity from dx₄/dt = ic," elliotmcguckenphysics.com (2025).

[MG-QED] E. McGucken, "Quantum Electrodynamics as a Theorem of the McGucken Principle dx₄/dt = ic," elliotmcguckenphysics.com (2025).

[MG-SM] E. McGucken, "The Standard Model Gauge Structure as a Theorem of the McGucken Principle: Yang-Mills, Higgs, and the Einstein Field Equations via Schuller Closure," elliotmcguckenphysics.com (2026).

[MG-Sphere] E. McGucken, "The McGucken Sphere as Spacetime's Foundational Atom: Deriving Arkani-Hamed's Amplituhedron and Penrose's Twistors as Theorems of the McGucken Principle dx₄/dt = ic," elliotmcguckenphysics.com (April 27, 2026), https://elliotmcguckenphysics.com/2026/04/27/the-mcgucken-sphere-as-spacetimes-foundational-atom-deriving-arkani-hameds-amplituhedron-and-penroses-twistors-as-theorems-of-the-mcgucken-principle-dx4-dtic/

[MG-TwoRoutes] E. McGucken, "The Deeper Foundations of Quantum Mechanics: How The McGucken Principle Uniquely Generates the Hamiltonian and Lagrangian Formulations of Quantum Mechanics, Wave/Particle Duality, the Schrödinger and Heisenberg Pictures, and Locality and Nonlocality all from dx₄/dt = ic," elliotmcguckenphysics.com (April 23, 2026). §V.8 develops the four-level dual-channel reading of quantum mechanics; §V.8.7 establishes the McGucken No-Signaling Theorem (Theorem 7.3) reproduced in §VII.3 of the present paper as Theorem VII.3.

[MG-Vanquishing] E. McGucken, "Vanquishing Infinities and Singularities via the Continuous and Discrete McGucken Spacetime Geometry: Two Theorems of the McGucken Principle dx₄/dt = ic — Finite One-Loop QED Vacuum Polarization and Schwarzschild-Kruskal Interior Foreclosure," elliotmcguckenphysics.com (May 5, 2026), https://elliotmcguckenphysics.com/2026/05/05/vanquishing-infinities-and-singularities-via-the-continuous-and-discrete-mcgucken-spacetime-geometry-two-theorems-of-the-mcgucken-principle-dx%e2%82%84-dt-ic-finite-one-loop-qed-vacuum-polarizatio/

[MG-Wick] E. McGucken, "The Wick Rotation as a Theorem of the McGucken Principle dx₄/dt = ic: Coordinate Identification τ = x₄/c, Not Analytic Continuation," elliotmcguckenphysics.com (2026).

---

*Document compiled from McGucken corpus sources retrieved for this paper:*

- *McGucken Sphere paper (PDF, fetched May 9, 2026): full text through §17.1 retrieved; §§17.2–17.6 and full Bibliography truncated by fetch token limit. The structural content used in this paper (six-fold null-surface identity, McGucken Causal Completion, algebraic microcausality theorem) is from §§7, 15, all retrieved in full.*

- *Vanquishing-Infinities paper (fetched May 9, 2026): full text retrieved.*

- *Nonlocality paper (fetched May 9, 2026): full text retrieved.*

- *Feynman paper (fetched in two passes, May 9, 2026): full text retrieved including §§II–VII (kinematical foundation, propagator, vertex, external lines, Sphere substrate, Dyson expansion) and §§VIII–XII (Wick's theorem, loops/residues, Euclidean lattice, empirical reach, conclusion). The propagator-as-Huygens-kernel result and six-fold locality used in this paper are from §III, retrieved in full in the first pass.*

*This paper does not invoke any McGucken-corpus theorem whose full proof was not retrieved. Where partial fetches occurred (Sphere paper §§17.2–17.6 + Bibliography), the limitation is stated explicitly and the structural arguments do not depend on the missing material.*
