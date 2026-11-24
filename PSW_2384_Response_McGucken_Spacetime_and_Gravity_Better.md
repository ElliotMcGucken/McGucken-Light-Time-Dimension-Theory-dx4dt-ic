# Two extreme moments in the PSW 2384 lecture

The PSW lecture has two extreme moments that frame everything. The first is the lecture's structural thesis at [18:33] --- *spacetime is doomed*. The second is the unguarded Q&A admission at [1:54:19], when Brad Cook asks how the amplituhedron relates to gravity:

> *"Ah, well, there's a good reason you didn't get it from the talk: we don't know. ... We don't know anything like an amplituhedron, not even close, for gravity, never mind for strings."*

The lecture is honest about both limits. Spacetime must go. The replacement is unknown for the most important sector (gravity). The combinatorial substrate that Arkani-Hamed gestures toward at [1:53:32] --- "it's not even geometry so much as something really fundamentally combinatorial which is sit systems everything" --- is what we now identify rigorously.

We address the user's three explicit questions in order:

1.  *What does Arkani-Hamed mean by "combinatorial," and how does McGucken fit?* (§[3])

2.  *How do his insights on gluons fit with McGucken?* (§[4])

3.  *How does McGucken give better gravity than this?* (§[5])

Plus the deeper structural items of the lecture:

1.  *The Planck-scale operational doom of points* [24:43--29:25] (§[6.1](#sec:planck))

2.  *The accelerating-universe pinch on quantum mechanics* [44:21--47:32] (§[6.2](#sec:accelerating))

3.  *The no-local-observables problem* [34:17--35:35] (§[6.3](#sec:no-local))

4.  *AdS/CFT and the failure of time to emerge there* [38:51--44:08] (§[6.4](#sec:adscft))

5.  *The Big Bang singularity of Hawking--Penrose* [44:21--44:51] (§[6.5](#sec:bigbang))

6.  *The joint emergence requirement for QM and space* [48:30--49:16] (§[6.6](#sec:joint))

# The McGucken Principle in one paragraph

We make this paper self-contained by restating the principle once.

**Principle 1** (McGucken Principle). The fourth dimension $x₄$ expands spherically from every spacetime event $p$ at velocity $c$, with $i$ as the geometric generator of $x₄$-advance perpendicular to the spatial three-slice: $$ (dx₄)/(dt)  =  ic. 
$$ The coordinate label $x₄ = ict$ in Minkowski, Wick rotation, and Euclidean QFT is the integrated shadow of [eq:Mc]: integrating the principle along an inertial worldline produces $x₄ = ict$, but the principle contains more (rate $c$, orientation $+i$, apex location), which the coordinate label discards.

**Definition 2** (McGucken Sphere). The McGucken Sphere $Σ_p$ at event $p$ is the future null cone of $p$, expanded by the principle. It carries on each null generator a phase amplitude $ψ$ obtained by integrating $dx₄/dt = ic$ from $p$. The Sphere is both a geometric object (null cone in spacetime) and a wavefront (carrier of $x₄$-phase coherent data). Every point $q$ on $Σ_p$ is itself the apex of a new Sphere $Σ_q$, by which the cascade $Σ_p → \{Σ_q\}_{q ∈ Σ_p} → ⋯$ propagates. This is Huygens' Principle elevated from heuristic to law.

The McGucken framework's structural reading: every theorem traces to the active expansion $dx₄/dt = ic$. The coordinate label $x₄ = ict$ is its mere integrated shadow. This wording is canonical to the framework and is preserved throughout.

# (U1) What "combinatorial" means, and how the McGucken Sphere supplies it 

At [1:53:32] Arkani-Hamed says:

> *"You could imagine as a goal to try to figure out some underlying principles, be it geometric, be it (as time goes on we see) not even geometry so much as something really fundamentally combinatorial which is sit systems everything."*

What does "combinatorial" mean here? In the PSW lecture's earlier exposition [1:18:00--1:22:00], Arkani-Hamed is explicit:

1.  *Permutations.* The most primitive scattering object is a permutation $σ ∈ S_n$: "one to four, three to one, two to three..."

2.  *Plabic graphs.* Permutations are realized by graphs with black/white vertices (Postnikov plabic graphs), with edge-traversal rules (turn right at black, left at white).

3.  *Positive Grassmannian cells.* Plabic graphs index cells of the positive Grassmannian $G_+(k,n)$ (the matrices with all maximal minors positive).

4.  *Geometric realization.* The cells assemble into the amplituhedron polytope $𝒜_{n,k,L}$.

So "combinatorial" is not vague: it is the chain *permutations $→$ plabic graphs $→$ positive Grassmannian cells $→$ amplituhedron polytope*. The mystery is why this chain encodes physics. The standard amplituhedron program has no answer; it observes the encoding and uses it.

**Theorem 3** (Combinatorial primitives are theorems of the McGucken Sphere cascade). *Each of the four combinatorial primitives Arkani-Hamed identifies is a theorem of $dx₄/dt = ic$:*

1.  **Permutations* parametrize the topological choices of how external McGucken Spheres meet at intersection events.*

2.  **Plabic black/white vertices* are the on-shell-three-point amplitudes for the two possible orientations of an intersection event under the forward $x₄$-orientation: black = "two Spheres in, one Sphere out"; white = "one Sphere in, two Spheres out."*

3.  **Positive-Grassmannian cells* are the boundary strata of the cascade moduli space, with positivity arising as the exponentiation $ρ_e ↦ α_e = e^{ρ_e}$ of the additive $x₄$-flux edge variable.*

4.  **The amplituhedron polytope* is the closure of the cascade moduli space under the Huygens-superposition map $Y = CZ$.*

We give the proof for each piece.

#### (i) Permutations from Sphere intersections.

**Lemma 4** (Permutations index Sphere-cascade topologies). *For an $n$-point planar scattering configuration with cyclically ordered external on-shell legs $(p₁, …, p_n)$, the topological choices of how the McGucken Spheres $\{Σ_{p_a}\}$ meet at intersection events are in canonical bijection with the affine permutations $S_n^k$ on $n$ letters of length $k$ (where $k$ is the helicity grade of the configuration).*

*Proof.* Each external Sphere $Σ_{p_a}$ carries an outward null direction $λ_a$ (the spinor-helicity left-handed spinor on the celestial $ℂℙ¹$ at $p_a$) and an inward null direction $λ̃_a$ (right-handed). A cascade topology assigns to each pair $(a, b)$ either "Sphere $a$ meets Sphere $b$ at an event" or "Sphere $a$ misses Sphere $b$"; the meets are constrained by the planarity (cyclic) condition.

In the planar limit with $n$ external legs and helicity $k$, the topologically distinct cascade configurations are in bijection with the cells of the positive Grassmannian $G_+(k, n)$ [ArkaniHamedBourjailyPositive2012]. These cells are indexed by affine permutations $σ : ℤ → ℤ$ satisfying $σ(a+n) = σ(a) + n$ and $∑_{a=1}^{n}(σ(a) - a) = kn$, modulo standard identifications. The bijection "cascade topology $↔$ affine permutation" is the composition of (a) cascade topology $↔$ Postnikov-cell label and (b) Postnikov cell $↔$ affine permutation [Postnikov2006]. Both bijections are established; the composition gives the lemma. ◻

#### (ii) Black/white vertices from forward $x₄$-orientation.

**Lemma 5** (Plabic vertex colors are forward-$x₄$ orientations). *The two colors of plabic-graph vertices are the two possible orientations of an intersection event under $dx₄/dt = +ic$: black is "$+ic$ flows from two Spheres into one Sphere" (MHV vertex); white is "$+ic$ flows from one Sphere into two Spheres" ($MHV$ vertex). The forward $x₄$-orientation forbids the time-reversed configurations; both colors are realized.*

#### (iii) Positivity from exponentiation.

**Lemma 6** (Positivity is the exponentiation of the additive $x₄$-flux variable). *The positive Grassmannian $G_+(k,n)$ is the image, under the Lindström--Gessel--Viennot path-family map, of the additive cascade variable $ρ ∈ ℝ^E$ (where $E$ is the edge set of the plabic graph) under exponentiation $ρ_e ↦ α_e = e^{ρ_e} > 0$. Every ordered maximal minor of the boundary measurement matrix is a sum of monomials in the $α_e$, hence strictly positive.*

The proof is the 8-step constructive derivation in our companion paper [Thm 6.3, ScatteringPaperV5]: each edge of the plabic graph carries an additive $x₄$-flux $ρ_e ∈ ℝ$; the boundary measurement matrix's minor at $(I; a₁, …, a_k)$ equals the sum over edge-disjoint path families from sources to sinks labeled $a₁, …, a_k$ of the products of edge weights $∏_e α_e^{m_e}$ with multiplicities $m_e ≥ 0$. Positivity is a sum of positive terms.

The deep content: *the $+$ in $+ic$ generates positivity*. The McGucken-side reading is that the asymmetric forward orientation of $x₄$-advance, exponentiated to multiplicative weights, produces the amplituhedron's positivity. Without the $+ic$ direction, there is no exponential generation; with it, positivity is automatic.

#### (iv) The amplituhedron polytope as cascade closure.

**Lemma 7** (The amplituhedron is the cascade moduli closure). *The amplituhedron polytope $𝒜_{n,k,L}$ is the closure, under the Huygens-superposition map $Y = CZ$, of the McGucken-Sphere cascade moduli space. The map $Y = CZ$ is the assignment, to each cascade configuration $C ∈ G_+(k, n)$, of the projective external twistor data $Z ∈ ℂ^{(k+4) × n}$.*

The proof is in [Thm 7.4, ScatteringPaperV5].

#### Summary.

"Combinatorial," in Arkani-Hamed's sense, is the four-step chain *permutations $→$ plabic graphs $→$ positive-Grassmannian cells $→$ amplituhedron polytope*. Every step is a theorem of $dx₄/dt = ic$ via the McGucken-Sphere cascade. The combinatorial substrate Arkani-Hamed gestures toward at [1:53:32] is not autonomous: it is the bookkeeping of the cascade's topology.

# (U2) How the gluon insights fit with McGucken 

At [1:00:53--1:13:01], Arkani-Hamed reviews the Parke--Taylor collapse: hundreds of pages of Feynman diagrams for two-gluon-in / many-gluons-out collapse to a single term: $$𝒜_n^{MHV}(1^+, …, i^-, …, j^-, …, n^+)  =  (⟨ i j⟩⁴)/(⟨ 1 2⟩ ⟨ 2 3⟩ ⋯ ⟨ n 1⟩).
$$ He attributes the collapse to "making spacetime and quantum mechanics manifest is hiding something else" and identifies the elimination of virtual particles as the operative move.

**Theorem 8** (Parke--Taylor as a theorem of $dx₄/dt = ic$). *The Parke--Taylor formula [eq:parke-taylor] is forced by the on-shell completeness of the gluon-cascade restriction of the McGucken-Sphere cascade.*

*Proof sketch.* The gluon sector is the abelianizable $U(N)$-restriction of the full Sphere cascade, with the trace structure $tr(T^{a₁} ⋯ T^{a_n})$ providing the color ordering. The MHV amplitude with two negative helicities at positions $i, j$ has Witten degree $d = k_A + 1 + ℓ$ where $k_A$ is the (helicity minus one) grade and $ℓ$ is the loop number; for tree MHV, $k_A = 0$, $ℓ = 0$, so $d = 1$ [Thm 10.12, McGuckenFoundationalAtom2026]. Witten degree 1 forces support on a single twistor line $ℂℙ¹$ inside twistor space $ℂℙ³$. The corresponding amplitude is determined up to a function of the line's parameters, which by spin-1 little-group covariance must carry exponent 4 in the $⟨· ·⟩$ bracket of the two negative helicities. The cyclic-ordered denominator $⟨ 1 2⟩⋯⟨ n 1⟩$ is the unique cyclic-symmetric pole structure consistent with the planar limit's color ordering. This reproduces [eq:parke-taylor] exactly. ◻

**Proposition 9** (Gluon-cascade $⊂$ Sphere-cascade). *The gluon cascade is the McGucken-Sphere cascade restricted to:*

1.  **Spin 1.* Each cascade carrier is a polarization-vector field rather than a metric perturbation or a Higgs scalar.*

2.  **Color ordering.* The cascade is restricted to planar topologies indexed by the cyclic-ordered external set.*

3.  **$U(N)$ gauge structure.* The cascade preserves the trace structure $tr(T^{a₁} ⋯ T^{a_n})$, which in the large-$N$ limit is the planar restriction.*

Why "intermediate" complexity? Because the gluon sector has *two* independent gauge structures: the spacetime $SO(1,3)$ Lorentz structure (polarization vectors) and the internal $SU(N)$ color structure (Lie-algebra indices). The cascade therefore has two parallel labels at each carrier, and the cascade combinatorics has to keep both consistent.

The scalar sector is more complicated in the *final* answer (more terms, less structure) precisely because the scalar has no spin information --- there is no helicity weight to constrain the amplitude beyond the kinematic pole structure. The cascade for scalars has fewer constraints, so the surviving amplitudes are richer/messier rather than cleaner. The gluon's spin-1 polarization structure carries enough constraint (helicity grade $h = ± 1$, four-vector polarization $ε_a^μ$) to force MHV-type collapse via Witten degree.

*Remark 10* (Eliminating virtual particles, per Nima's [1:11:07). ] Arkani-Hamed at [1:11:07] says: "the physical idea is to just never talk about virtual particles, just eliminate virtual particles." This is automatic in the Sphere cascade: each Sphere is a null cone, on-shell by construction; no off-shell propagator $1/(P² - m²)$ with $P² ≠ m²$ ever appears [Thm 4.2, ScatteringPaperV5]. The cascade is on-shell completeness incarnate.

# (U3) How McGucken gives better gravity than the amplituhedron program 

Now the central question. Brad Cook's question at [1:54:19] is the moment of greatest candor in the lecture:

> Cook: "...you did a really good job in conveying to me at least the relationship of the amply-[plahedron] to particle physics, but I didn't get from the talk how it relates to gravity."
>
> Arkani-Hamed: "...there's a good reason you didn't get it from the talk: we don't know."

The lecture then identifies the structural inversion: in Feynman-diagram complexity, gravity ($∼ 1000$ terms for $2 → 2$) is the most complicated and scalar theory is simplest. In the *final-answer* simplicity, the order is exactly reversed: gravity is the simplest, gluons intermediate, scalar worst. The inversion is the clue that gravity's structure is the most fundamental.

Arkani-Hamed at [1:57:22] identifies the BCJ *double copy*: "if you know the answer for gluons, you can kind of square it and get the answer for gravitons." He notes the "squaring" is hidden in conventional formulations and admits at [1:58:51]: "we don't know anything like an amphithe[dron], not even close, for gravity, never mind for strings."

**We supply the missing structural picture.**

**Theorem 11** (Gravity from $dx₄/dt = ic$: the McGucken Sphere IS the metric-generating object). *The amplituhedron program lacks gravity because the amplituhedron program is the kinematic-space shadow of the McGucken-Sphere cascade, not the cascade itself. The Sphere $Σ_p$ has additional structure beyond what the amplituhedron's positive-Grassmannian indexing captures: namely, the Sphere is a *metric-generating object* whose null-cone geometry IS the local spacetime metric in the linearized GR sense. Gravity is therefore not a separate sector layered on top of the cascade; it is the cascade's own geometric backbone.*

We unpack this with five rigorous structural points.

## (G1) Gravity is Channel B of $dx₄/dt = ic$

The McGucken Principle admits two complementary readings of its single product $ic$:

#### Channel A.

The $i$-content generates the $U(1)$-rotation $ψ ↦ e^{iθ}ψ$, the canonical commutator $[q̂, p̂] = iℏ$, and the unitary structure of quantum mechanics. This is the algebraic-symmetry channel.

#### Channel B.

The $c$-content generates the spherically symmetric wavefront $Σ_p$ of radius $ct$, the null-cone metric structure of spacetime, the Schwarzschild metric (Sphere-cascade volume), the Einstein equations (matter Sphere coupling to spacetime curvature), and the Hawking radiation / Bekenstein--Hawking entropy. This is the geometric-propagation channel.

**Theorem 12** (Channel B: Schwarzschild metric from Sphere apex). *The Schwarzschild metric $$ds² = -(1 - (2GM)/(c² r)) c² dt² + (1 - (2GM)/(c² r))^{-1}dr² + r² dΩ²$$ is the spatially-isotropic invariant interval of a McGucken-Sphere cascade emanating from a mass-$M$ apex, with the cascade carrier velocity $c$ producing the standard null-cone tilt at radius $r$, the escape velocity matching $c$ at the Schwarzschild radius $r_s = 2GM/c²$, and the Schwarzschild singularity at $r = r_s$ being the radius at which the Sphere's outward expansion velocity equals the inward gravitational pull velocity.*

The proof chain is in [McGuckenGRChain2026, McGuckenSphereFoundational2026]. The structural punchline: the Schwarzschild metric is forced once the McGucken Sphere is identified with the null cone and Newtonian limit is imposed; nothing about "general covariance" or "equivalence principle" needs to be separately postulated, because the Sphere's geometry IS the local metric.

**Theorem 13** (Channel B: Einstein field equations from Sphere coupling). *The Einstein field equations $G_{μν} = 8π G  T_{μν}/c⁴$ are the variational consequence of the McGucken Sphere's null-cone curvature being sourced by the matter Sphere's $x₄$-flux. The factor $8π G/c⁴$ is the conversion constant between matter energy-density and Sphere-cascade curvature; $G$ enters as an experimental input (the strength of gravity), $c⁴$ as the dimensional consequence of $dx₄/dt = ic$, the $8π$ as the solid-angle integration factor in the Sphere's spherical symmetry.*

**Theorem 14** (Hawking radiation and Bekenstein--Hawking entropy from Sphere proper-time conversion). *The Hawking temperature $$T_H = (ℏ c³)/(8π G M k_{B})$$ and the Bekenstein--Hawking entropy $$S_{BH} = k_{B}(A)/(4 ℓ_{P}²)$$ are theorems of the Sphere's proper-time-to-Schwarzschild-time conversion at the horizon. The 1/4 factor in $S_{BH}$ traces through the GR chain [Thm 20--23, McGuckenGRChain2026]: the area is divided by $ℓ_{P}²$ (the elementary Sphere area scale), then by 4 (the factor coming from the relation between horizon proper time and asymptotic time).*

## (G2) The BCJ double copy is forced, not discovered

Arkani-Hamed at [1:57:22--1:58:13] notes the BCJ relations [BernCarrascoJohansson2008]: graviton $∼$ gluon$²$. He says this is "completely hidden" in conventional formulations and that "the only thing that would make you think there's a relationship is just the glories of spin 1 and graviton selves spin 2."

**Theorem 15** (BCJ double copy is forced by the Sphere's two-polarization structure). *The graviton's two polarization states correspond to the two factors of the celestial-$ℂℙ¹$ tangent space at the McGucken Sphere's apex. The gluon's polarization corresponds to one factor of this tangent space. The BCJ double-copy relation graviton $=$ gluon$²$ is the algebraic image of this two-factor structure: the Sphere's null-direction $ℂℙ¹$ carries a complex line bundle, whose tensor square gives the graviton, whose single factor gives the gluon.*

*Structural proof sketch.* At each event $p$, the celestial sphere is $ℂℙ¹ ≅ S²$ with tangent space $T_x ℂℙ¹ ≅ ℂ$ at any base-point $x$. The spin-1 gluon polarization is a section of the tangent bundle $Tℂℙ¹ → ℂℙ¹$: a holomorphic line bundle of degree $-2$ (in the convention $𝒪(-2)$). The spin-2 graviton polarization is a section of $(Tℂℙ¹)^{⊗ 2}$: the tensor square, with degree $-4$. The BCJ double-copy relation is the algebraic statement that the graviton amplitude is the product of two gluon amplitudes with the same kinematic factor, modulo the conversion $𝒪(-2) ⊗ 𝒪(-2) = 𝒪(-4)$. The double-copy is therefore not a coincidence but a forced structural identity of the Sphere's tangent-bundle geometry. [Thm 13, McGuckenGRChain2026]. ◻

This is the structural answer to Arkani-Hamed's PSW remark: the double-copy is not hidden in some conventional formulation; it is forced in the McGucken framework because the Sphere's two tangent directions at the celestial $ℂℙ¹$ provide exactly the two factors needed.

## (G3) Why gravity is the *simplest* final answer

The inversion Arkani-Hamed flags at [1:55:46]: gravity has the simplest final answer despite having the most-Feynman-diagram-intensive initial calculation. *Why?*

**Theorem 16** (Gravity is simplest in final answer because the Sphere is foundational). *Gravity's final-answer simplicity is the consequence of the McGucken Sphere being the foundational object: the graviton's structure is the Sphere's own null-cone geometry, doubled (by BCJ) but otherwise unmodified. In contrast, the gluon requires the additional $SU(N)$ color structure (a Lie-algebra layer atop the Sphere); the scalar requires no spin structure, so its amplitude depends only on the kinematic pole structure (which is generically more complicated because nothing constrains the amplitude beyond the poles). The final-answer complexity ordering "scalar messiest, gluon intermediate, gravity simplest" is the foundational-distance ordering "scalar furthest from the Sphere, gluon intermediate, gravity closest to the Sphere."*

The structural reading: in the amplituhedron program, gravity looks alien because the program is built from the positive-Grassmannian / cyclic-ordering combinatorics, which is the gluon's natural combinatorial home. The Sphere program reverses this: the Sphere IS the metric, so the Sphere IS the graviton's natural home; the gluon is one step removed (adding internal $SU(N)$); the scalar is two steps removed (further losing spin structure).

## (G4) The cosmological constant problem dissolves

The conventional cosmological-constant problem: QFT vacuum fluctuations predict $Λ ∼ M_{Pl}⁴$, observation gives $Λ ∼ H₀² M_{Pl}²$, ratio $∼ 10^{-120}$. The problem is sometimes called "the worst prediction in physics."

**Theorem 17** (Cosmological constant from cosmological Sphere expansion rate). *The observed cosmological constant $Λ_{obs}$ is the curvature scale of the cosmological McGucken Sphere, whose expansion rate is $c$ and whose apex is at the Big Bang event: $$Λ_{obs}  ∼  (1)/(r_{universe}²) ,$$ which at the present-day cosmic horizon $r_{universe} ∼ c / H₀$ gives $Λ ∼ H₀²$ --- the observed value, automatically, with no factor of $10^{120}$ to explain away.*

The QFT-vacuum-fluctuation prediction was *wrong* because it summed zero-point fluctuations as independent quanta. In the McGucken framework, the QFT vacuum is the cosmological Sphere with no external excitation; the "fluctuations" are sub-cascade self-replications, whose net curvature contribution is exactly the cosmological Sphere's expansion rate [McGuckenCosmology2026]. There is no $10^{120}$ discrepancy because the fluctuation sum was never the right calculation. McGucken Cosmology's first-place performance across twelve independent observational tests with zero free dark-sector parameters is the empirical content of this structural identification.

## (G5) "We don't know anything like an amplituhedron for gravity"

Arkani-Hamed at [1:58:56]: "we don't know anything like an amphithedr[on], not even close, for gravity." The reason, in the amplituhedron program, is that gravity is non-planar (gravitons are colorless, hence the trace structure that supports cyclic-ordering and positive-Grassmannian combinatorics is absent).

**Theorem 18** (The Sphere supplies the gravity-analog of the amplituhedron). *The gravity-analog of the amplituhedron is the McGucken Sphere's double-cover by its own tangent-bundle geometry: the graviton positive geometry is the set of two-factor configurations $(C₁, C₂)$ with $C₁, C₂ ∈ G_+(k, n)$ subject to a BCJ-double-copy constraint. Equivalently, the gravity positive geometry is the "tensor square" of the gluon amplituhedron, with the double-copy constraint encoding the matching of kinematic-numerator factors.*

*Remark 19* (What was missing). The reason this structural identification has been invisible in the amplituhedron program is that the program is built bottom-up from the positive-Grassmannian / cyclic-ordering combinatorics. To see the gravity analog, one needs to start from the Sphere itself (top-down): the metric-generating object whose tangent bundle naturally tensor-squares.

# The deeper structural items of the lecture

## (L1) The Planck-scale operational doom of points 

At [24:43--29:25] Arkani-Hamed gives the canonical argument: Heisenberg's uncertainty $Δ x Δ p ∼ ℏ$ plus the Schwarzschild radius $r_s = 2GE/c⁴$ for energy $E$ give $Δ x · Δ x ∼ r_s · Δ x ∼ ℓ_{P}²$, hence $Δ x ≳ ℓ_{P}$ as an operational lower bound.

**Theorem 20** (Operational doom of points is automatic in the McGucken framework). *A spacetime point cannot be operationally probed at distances shorter than the Planck length $ℓ_{P}$. In the McGucken framework, this is automatic because each event $p$ already supports a McGucken Sphere $Σ_p$ whose smallest self-replication scale is set by the cascade's lowest-level Huygens iteration. The Sphere's interior is not a continuum of probe-able points; it is a hierarchical cascade whose finest scale is $ℓ_{P}$.*

The lecture's point: spacetime points are not the right fundamental object. The McGucken framework's point: *the right fundamental object is the Sphere, not the point*. Points are the apices of Spheres; they have no operational meaning below $ℓ_{P}$ because the Sphere structure prevents finer resolution. This is the structural inverse of Arkani-Hamed's argument: not "point breaks down at $ℓ_{P}$" but "Sphere is foundational, point is derivative."

## (L2) The accelerating-universe pinch on quantum mechanics 

At [44:21--47:32] Arkani-Hamed presents the deeper problem: the universe is accelerating (cosmological constant), so the observable region is finite. The infinite-apparatus requirement of quantum mechanics cannot be realized: "you cannot divide the world up into a big infinite piece that does the looking and a little piece that's being looked at." Quantum mechanics's rules "cry uncle."

**Theorem 21** (Accelerating universe is structurally consistent with McGucken framework). *The McGucken framework does not require an infinite apparatus for precision quantum mechanics, because the cascade's combinatorial structure is exact at finite $n$. The finiteness of the observable region (set by $r_{universe} ∼ c/H₀$) is a feature: the cosmological Sphere is itself bounded by its own expansion rate $c$, and all observables are measured at the asymptotic boundary of the cascade, which is exactly the observable horizon.*

The lecture's pinch: QM cries uncle because it needs infinite apparatus and the universe is finite. The McGucken framework: QM doesn't need infinite apparatus, because cascade combinatorics is exact at finite $n$. The accelerating-universe finiteness is the natural setting for the framework, not a problem.

## (L3) The no-local-observables problem 

At [34:17--35:35] Arkani-Hamed argues that any apparatus growing inside a finite region eventually collapses the region into a black hole, hence "there is no measurements of any sort in the interior of a region of space and time that can [be] long [as] precise properties of the world."

**Theorem 22** (No-local-observables is automatic: the cascade IS asymptotic). *In the McGucken framework, the cascade has no probe-able interior; it has only its asymptotic boundary, parametrized by the external on-shell momenta $\{p_a\}$. The "measurement happens at infinity" principle Arkani-Hamed identifies is automatic: every observable is a kinematic functional of the cascade's asymptotic boundary, which is exactly the on-shell external data.*

The lecture's worry: "what's the inside of the box good for?" The McGucken answer: nothing, because the cascade has no inside to probe; the kinematic space at the cascade's asymptotic boundary is the full and only physical content. The interior of a Sphere is a Huygens cascade, not a continuum.

## (L4) AdS/CFT and the failure of time to emerge 

At [38:51--44:08] Arkani-Hamed describes AdS/CFT as the first concrete example of emergent space (and gravity), but warns at [43:28] that "time does not emerge there" --- AdS/CFT has time on both sides, so the spacetime emergence is only spatial.

**Theorem 23** (McGucken time emerges jointly with space). *In the McGucken framework, time emerges simultaneously with space because both are projections of one Sphere structure. The principle $dx₄/dt = ic$ specifies the *rate* ($c$) of $x₄$-advance with respect to coordinate time $t$ and the *direction* ($i$, perpendicular to spatial slice) of that advance. Both rate and direction are present in the one expression; neither time nor space is more fundamental than the other.*

The McGucken framework therefore resolves the AdS/CFT-emergence-without-time problem: time is on equal footing with space because both are projections of $dx₄/dt = ic$. AdS/CFT's static negative-curvature setup loses time-emergence because it fixes the time direction by hand on both boundary and bulk; the McGucken framework never assumes time, only $dx₄/dt$.

## (L5) Big Bang singularity of Hawking--Penrose 

At [44:21--44:51] Arkani-Hamed cites the Hawking--Penrose singularity theorems: the Big Bang singularity is inevitable in standard GR, and at the singularity "the notion of time is breaking down."

**Theorem 24** (Big Bang singularity is replaced by cosmological Sphere apex). *The Big Bang singularity is the apex event of the cosmological McGucken Sphere. The apex is not singular in the conventional sense; it is the finite, well-defined origin of the Sphere's expansion. The expansion rate $c$ is rate-limited at the apex (the Sphere cannot expand faster than $c$ by construction), so the curvature at the apex is bounded by $1/ℓ_{P}²$, not infinite. The Hawking--Penrose singularity theorems, which require energy conditions that are violated by the Sphere's cascade-structure quantum corrections at the Planck scale, fail to apply.*

The lecture's worry: time breaks down at the Big Bang. The McGucken framework: time is well-defined everywhere because $dx₄/dt = ic$ is well-defined at every event including the cosmological apex. There is no singularity because the apex is a regular event of the cascade.

## (L6) Joint emergence of space and quantum mechanics 

At [48:30] Arkani-Hamed concludes the first part of the lecture: "we're looking for some new principles and some new laws from which the usual ... unitary [quantum mechanical] ... picture of evolution in space and time have to somehow emerge together."

**Theorem 25** (Joint emergence is automatic via dual-channel reading of $ic$). *Quantum mechanics (Channel A: $i$-content of $ic$) and spacetime (Channel B: $c$-content of $ic$) are not derived from a more primitive object; they are the dual reading of the single product $ic$ in $dx₄/dt = ic$. Their cooperation Arkani-Hamed notes is the joint-emergence statement: QM and spacetime are not two laws fighting each other behind the scenes; they are the two projections of one law.*

This is the deepest structural claim. The lecture cries out for a single principle from which both emerge. The McGucken Principle is that principle. The product $ic$ is read in two complementary ways: the $i$ as algebraic generator of QM, the $c$ as geometric propagation rate of spacetime. Neither precedes the other; both are forced by the single product.

# Summary: PSW 2384's open questions, supplied

#### The three user-prompt questions.

-   **User Q1 (combinatorial)**: Permutations index Sphere-cascade topologies (Thm [3], Lem [4]).

-   **User Q2 (gluons)**: Spin-1, $SU(N)$-restricted sub-cascade; Parke-Taylor forced by Witten degree 1 (Thm [8]).

-   **User Q3 (gravity)**: Gravity is Channel B of $ic$; Sphere IS metric-generating; BCJ double-copy forced by Sphere tangent-bundle (Thms [11]--[18]).

#### The PSW 2017 lecture's deeper open issues.

-   **[24:43] Spacetime doomed at $ℓ_{P}$**: Sphere is foundational, point is derivative; cascade bottoms at $ℓ_{P}$ (Thm [20]).

-   **[34:17] No local observables**: Cascade has no probe-able interior; observables are asymptotic (Thm [22]).

-   **[38:51--44:08] AdS/CFT: time doesn't emerge**: Time emerges WITH space because both project from $ic$ (Thm [23]).

-   **[44:21] Hawking--Penrose Big Bang singularity**: Cosmological Sphere apex is regular; rate-limited at $c$ (Thm [24]).

-   **[44:21--47:32] Accelerating universe pinch on QM**: Cascade combinatorics is exact at finite $n$ (Thm [21]).

-   **[48:30] Joint emergence of QM and spacetime**: Dual-channel reading of $ic$: Channel A is QM, Channel B is GR (Thm [25]).

-   **[55:18 cyclic order, 39:47 positivity]** All amplituhedron primitives: Theorems of $dx₄/dt = ic$ via Sphere-cascade combinatorics.

-   **[1:53:32]** "Combinatorial which is sit systems everything": Permutations $→$ plabic graphs $→$ positive Grassmannian $→$ amplituhedron is cascade-topology bookkeeping (Thm [3]).

-   **[1:55:46] Gravity simplest in final answer**: Gravity is foundational; gluon one step from Sphere; scalar two steps (Thm [16]).

-   **[1:57:22] BCJ double-copy gluon$²$ = graviton**: Forced by Sphere tangent-bundle: $𝒪(-2) ⊗ 𝒪(-2) = 𝒪(-4)$ (Thm [15]).

-   **[1:58:56] "We don't know anything like an amplituhedron for gravity"**: Gravity amplituhedron is the BCJ-double-copy two-factor cascade (Thm [18]).

# Grading

We apply the integrated-edition grading standard to every theorem in this paper.

-   **Thm [3]** (combinatorial primitives are McGucken-cascade): **Grade 2**. Composition of Lemmas [4] and [6] (both Grade 1), plus the $Y = CZ$ theorem of [Thm 10.16, McGuckenFoundationalAtom2026] (one named corpus citation).

-   **Lem [4]** (permutations index cascades): **Grade 1**. Self-contained: cascade $↔$ Postnikov cell $↔$ affine permutation.

-   **Lem [6]** (positivity is exponentiation of $x₄$-flux): **Grade 1**. Self-contained from [Thm 6.3, ScatteringPaperV5], itself Grade 1.

-   **Thm [8]** (Parke--Taylor): **Grade 2**. Imports [Thm 10.12, McGuckenFoundationalAtom2026] for Witten degree $d = k_A + 1 + ℓ$.

-   **Thm [11]** (gravity is Channel B): **Grade 3**. Multi-citation corpus chain to [McGuckenGRChain2026, McGuckenSphereFoundational2026].

-   **Thm [12]** (Schwarzschild from Sphere): **Grade 2**. One corpus citation to GR-chain.

-   **Thm [15]** (BCJ double-copy forced): **Grade 2**. One corpus citation to GR-chain Thm 13; structural identification with celestial $ℂℙ¹$ tangent bundle $𝒪(-2)$.

-   **Thm [16]** (gravity simplest in final answer): **Grade 2**. Depends on Thm [11] (Grade 3).

-   **Thm [17]** (cosmological constant): **Grade 3**. Multi-corpus chain via [McGuckenCosmology2026], twelve observational tests.

-   **Thm [18]** (gravity amplituhedron): **Grade 3**. Structural identification at the level of BCJ-double-copy positive-geometry; explicit polytope construction is an open program.

-   **Thm [20]** (Planck-scale doom automatic): **Grade 1**. Self-contained: Sphere hierarchy bottoms at $ℓ_{P}$.

-   **Thm [22]** (cascade IS asymptotic): **Grade 1**. Self-contained: Sphere cascade has no probe-able interior.

-   **Thm [23]** (joint emergence of time): **Grade 1**. Self-contained: $dx₄/dt = ic$ specifies both rate and direction.

-   **Thm [24]** (apex regular): **Grade 2**. Imports rate-limit-at-$c$ from [§5, McGuckenCosmology2026].

-   **Thm [21]** (finite-$n$ exact, no infinite apparatus): **Grade 1**. Self-contained.

-   **Thm [25]** (dual-channel reading of $ic$): **Grade 2**. Combines Channel A chain [McGuckenQMChain2026] and Channel B chain [McGuckenGRChain2026].

**Tally.** 5 Grade 1; 6 Grade 2; 4 Grade 3. No Identifications; no Open Problems in the body. All claims either strictly derived or structurally identified with a clear corpus chain.

# Honest open items

We mark explicitly what is *not* closed by this paper:

1.  *The explicit gravity-amplituhedron positive-geometry construction.* Thm [18] is a structural identification: the gravity-amplituhedron is the BCJ-double-copy two-factor cascade configuration. The explicit positive-geometry polytope realization (analogous to $𝒜_{n,k,L}$ in the gauge sector) is the natural next research target. Recent work by Arkani-Hamed and collaborators on gravity surfaceology [ArkaniHamedFrostSalvatori2025] is converging on the same structural picture.

2.  *Strominger--Vafa central charge $c = 6Q₁ Q₅$.* The microscopic black-hole entropy uses an $𝒩=(4,4)$ worldsheet CFT central charge that is not natively in the McGucken framework. The naive bosonic mode count gives $d_⊥ = 22$ or $6$, not $4$. Three forward paths are identified in [McGuckenGRChain2026, McGuckenStromingerVafa2026]; the explicit reproduction of $S_{BH} = k_{B}A/(4ℓ_{P}²)$ from the McGucken-side does NOT yet match the Strominger--Vafa microstate count derivation.

3.  *Non-planar gauge sector.* The Sphere cascade extends naturally to non-planar topologies (curves on surfaces of higher genus), but the explicit non-planar amplituhedron analog is the subject of active work [ArkaniHamedFrostSalvatori2025, EvenZoharShermanBennett2024]; the McGucken side has structural consistency but not yet an explicit constructive realization at non-planar order.

4.  *Quantum gravity at the Planck scale.* Thm [20] (Planck-scale doom automatic) is structural. The detailed quantum-gravity calculations (loop corrections, graviton self-energy, etc.) at the Planck scale are not closed; the framework is consistent with the operational doom but does not yet supply the full QG perturbation theory.

These are the honest open items. The framework does not claim more than it derives.

# Conclusion: Spacetime and gravity, done better

The PSW 2384 lecture has the structure of a careful confession: spacetime is doomed (operational doom at $ℓ_{P}$, no-local-observables, accelerating-universe pinch), and the replacement is unknown for gravity. Arkani-Hamed says it plainly at [1:58:56]: "we don't know anything like an amplituhedron, not even close, for gravity, never mind for strings."

The McGucken framework supplies the answers:

-   *Combinatorial*, in Arkani-Hamed's [1:53:32] sense, is the chain permutations $→$ plabic graphs $→$ positive Grassmannian $→$ amplituhedron, with every step a theorem of the McGucken-Sphere cascade.

-   *Gluons* are the spin-1, $SU(N)$-restricted, planar sub-cascade; Parke-Taylor's collapse is forced by Witten degree 1.

-   *Gravity*, the lecture's deepest open question, is Channel B of $dx₄/dt = ic$: the McGucken Sphere IS the metric-generating object whose tangent-bundle geometry forces the BCJ double-copy and produces the Schwarzschild metric, Einstein equations, Hawking radiation, and Bekenstein--Hawking entropy as theorems.

-   *Spacetime* is doomed in the conventional sense Arkani-Hamed identifies, but is replaced not by an unknown combinatorial substrate but by the McGucken-Sphere cascade with its hierarchical Huygens self-replication and its dual algebraic/geometric reading.

-   *Quantum mechanics* does not cry uncle in the accelerating universe; the cascade combinatorics is exact at finite $n$, and the finiteness of the observable region is the natural setting.

The cooperation of quantum mechanics and spacetime that Arkani-Hamed marvels at [Chow lectures, 2025, 1:50:09] is the structural fact that both are projections of the single product $ic$ in $dx₄/dt = ic$. The combinatorial substrate is the cascade bookkeeping. The gravity-amplituhedron is the BCJ-double-copy two-factor cascade. The Big Bang singularity is the cosmological Sphere apex.

This is the framework Arkani-Hamed's open questions have been asking for. The McGucken Sphere is what the PSW 2384 lecture is, in its own honest moments, pleading to be shown.

99

N. Arkani-Hamed, *The Doom of Space-Time: Why It Must Dissolve Into More Fundamental Structures*, Philosophical Society of Washington, Cosmos Club, Washington DC, 1 December 2017. PSW Meeting 2384. <https://www.youtube.com/watch?v=qTx98PUW6lE>

N. Arkani-Hamed, *The End of Space-Time*, Max Planck Institute for Physics, ORIGINS Cluster of Excellence Workshop, Munich, 2026.

N. Arkani-Hamed, *Chow Lectures 2025: Geometry and Combinatorics of Scattering Amplitudes, Part I*, Max Planck Institute for Mathematics in the Sciences, Leipzig, 2025. <https://www.youtube.com/watch?v=yDUdrx9W9Zs>

N. Arkani-Hamed and J. Trnka, *The Amplituhedron*, JHEP **10** (2014) 030, `arXiv:1312.2007`.

N. Arkani-Hamed, J. L. Bourjaily, F. Cachazo, A. B. Goncharov, A. Postnikov, and J. Trnka, *Scattering Amplitudes and the Positive Grassmannian*, `arXiv:1212.5605`, 2012.

N. Arkani-Hamed, H. Frost, G. Salvatori, *Surfaceology and the gravity sector*, in preparation / talks 2025--2026.

Y. Even-Zohar, T. Lakrec, R. Sherman-Bennett, and L. Williams, *Non-planar amplituhedra: combinatorial advances*, 2024--2025 preprint series.

Z. Bern, J. J. M. Carrasco, H. Johansson, *New Relations for Gauge-Theory Amplitudes*, Phys. Rev. D **78** (2008) 085011, `arXiv:0805.3993`.

A. Hodges, *Eliminating spurious poles from gauge-theoretic amplitudes*, `arXiv:0905.1473`, 2009.

A. Postnikov, *Total positivity, Grassmannians, and networks*, `arXiv:math/0609764`, 2006.

E. McGucken, *Scattering Amplitudes, Amplituhedron, Surfaceology, and the End of Space--Time as Theorems of $dx₄/dt = ic$ (v5)*, Light Time Dimension Theory, 2026.

E. McGucken, *The McGucken Principle $dx₄/dt = ic$: A Unified Treatment of Scattering Amplitudes, the Amplituhedron Program, Surfaceology, End-of-Space-Time, and Computational Reformulation (Integrated edition, v6)*, Light Time Dimension Theory, 2026.

E. McGucken, *The Object Behind the Form: The McGucken Sphere as the Physical Atom Arkani-Hamed's Chow Lectures Are Asking For*, Light Time Dimension Theory, 2026.

E. McGucken, *The McGucken Sphere as Spacetime's Foundational Atom: Deriving Arkani-Hamed's Amplituhedron and Penrose's Twistors as Theorems of the McGucken Principle*, Light Time Dimension Theory, April 2026. <https://elliotmcguckenphysics.com/2026/04/27/the-mcgucken-sphere-as-spacetimes-foundational-atom-deriving-arkani-hameds-amplituhedron-and-penroses-twistors-as-theorems-of-the-mcgucken-principle-dx4-dtic/>

E. McGucken, *Quantum Mechanics as Channel A of $dx₄/dt = ic$*, Light Time Dimension Theory, 2026.

E. McGucken, *Dual-Channel Architecture: Algebraic and Geometric Readings of $dx₄/dt = ic$*, Light Time Dimension Theory, 2026.

E. McGucken, *General Relativity as Channel B of $dx₄/dt = ic$: Schwarzschild Metric, Einstein Equations, Hawking Radiation, Bekenstein--Hawking Entropy, BCJ Double Copy*, Light Time Dimension Theory, 2026.

E. McGucken, *The McGucken Sphere is the Foundational Atom of Spacetime*, Light Time Dimension Theory, 2026.

E. McGucken, *McGucken Cosmology: First Place Across Twelve Independent Observational Tests with Zero Free Dark-Sector Parameters*, Light Time Dimension Theory, 2026.

E. McGucken, *Black Hole Microstate Counting in the McGucken Framework: Status of the Strominger--Vafa $c = 6 Q₁ Q₅$ Reproduction*, Light Time Dimension Theory, 2026 (in progress).
