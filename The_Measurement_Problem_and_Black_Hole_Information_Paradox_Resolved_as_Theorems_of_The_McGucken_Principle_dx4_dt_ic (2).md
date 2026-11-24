# The Measurement Problem and Black Hole Information Paradox Resolved as Theorems of The McGucken Principle dx₄/dt = ic: How the McGucken Principle Geometrically Derives the Born Rule, Dissolves Wave Function Collapse, Preserves Information Through the Smoothness of x₄'s Expansion, and Resolves Quantum Nonlocality Through the Spherical Expansion of the Fourth Dimension

**Dr. Elliot McGucken**

*Light Time Dimension Theory — elliotmcguckenphysics.com*

*April 2026*

> *"More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet."*
> — Dr. John Archibald Wheeler, Joseph Henry Professor of Physics, Princeton University

> *"I think I can safely say that nobody understands quantum mechanics."*
> — Richard Feynman, *The Character of Physical Law* (1965)

> *"The measurement problem is the central conceptual problem of quantum mechanics, and any interpretation of quantum mechanics worthy of the name must address it."*
> — Tim Maudlin, *Three Measurement Problems* (1995)

---

## Abstract

The measurement problem of quantum mechanics — the apparent incompatibility between unitary Schrödinger evolution (U) and the stochastic, irreversible reduction (R) invoked at measurement — has stood as the central foundational problem of quantum theory for ninety years. Standard interpretive programmes (Copenhagen, Many-Worlds, Bohmian mechanics, GRW spontaneous localization, decoherence-plus-environmental-selection, Relational Quantum Mechanics, QBism) each address the problem by adding postulates, hidden variables, dynamical modifications, or relational structures to the standard formalism. Each of these programmes, *without exception*, takes the Born rule P = |ψ|² as a postulate or as an assumption requiring independent justification (e.g. Gleason's theorem, decision-theoretic arguments, envariance, frequentist limits). None derives the Born rule from a single underlying physical principle.

The structural advantage of the McGucken dx₄/dt = ic framework over every prior interpretive programme can be summarized in the master comparison table below, which subsumes every comparison developed across the present paper — foundational primitives, mathematical structure, the wave function (§V.1), measurement and collapse (§V), the canonical thought experiments (§V.6), information and dynamics (§X), categorical structure (§XIII.10, §XIII.13), and foundational achievement. The table is reproduced in §XVI.5 (Conclusion) as the consolidated summary of all comparisons established formally throughout the paper.

| Property | **McGucken** | Copenhagen | Many-Worlds | Bohmian | GRW | Decoherence + einselection | RQM | QBism |
|---|---|---|---|---|---|---|---|---|
| **A. Foundational primitives** | | | | | | | | |
| Number of foundational postulates | **one: $dx_4/dt = ic$** | $\geq 6$ + $(R)$ + interpretive choice | $\geq 6$ + branching | $\geq 6$ + hidden variables | $\geq 6$ + stochastic params | $\geq 6$ + system-environment | $\geq 6$ + relational | $\geq 6$ + agent |
| K-complexity bit-budget | **$\sim 10^2$ bits** | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits |
| Primitive law | **$dx_4/dt = ic$ (physical-geometric)** | none specified | none specified | none specified | none specified | none specified | none specified | none specified |
| Physical content of primitive | **$x_4$ expands at $c$, spherically, with $i$ as perpendicularity marker** | — | — | — | — | — | — | — |
| Status of mathematical formalism | **derived theorems** | postulated | postulated | postulated + augmented | postulated + modified | postulated | postulated | postulated |
| **B. Mathematical structure** | | | | | | | | |
| Hilbert space $\mathcal{H}$ | **theorem (Prop. XIII.1)** | postulated | postulated | postulated + config space | postulated | postulated | postulated | postulated |
| Inner product $\langle\psi\|\phi\rangle$ | **theorem (Prop. XIII.4)** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Linearity / superposition (SP) | **theorem (Prop. IV.1)** | postulated | postulated | postulated | modified by hand | postulated | postulated | postulated |
| Unitarity of $U$ | **theorem (Prop. X.2)** | postulated | postulated | postulated | violated by collapse terms | postulated | postulated | postulated |
| Quantum operators $(\hat{H}, \hat{p}, [\hat{q},\hat{p}])$ | **theorem (Prop. XIII.5)** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Schrödinger equation | **theorem (Prop. XIII.5)** | postulated | postulated | postulated | modified by hand | postulated | postulated | postulated |
| Path integral $\int \mathcal{D}x\, e^{iS/\hbar}$ | **theorem (Prop. XII.1–XII.4)** | postulated | postulated | not used | postulated | postulated | postulated | postulated |
| Lorentzian wave operator $\square$ | **theorem (Theorem XIII.F)** | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate |
| Wick rotation | **theorem (Theorem XIII.E)** | analytic prescription | analytic prescription | not addressed | analytic prescription | analytic prescription | not addressed | not addressed |
| **C. The wave function $\psi$** | | | | | | | | |
| Is $\psi$ postulated or derived? | **derived from $dx_4/dt = ic$** | postulated | postulated | postulated + hidden vars | postulated + stochastic | postulated | postulated | postulated |
| Ontological status of $\psi$ | **ontic, geometric, 4D wavefront amplitude** | epistemic / instrumentalist | ontic (universal) | ontic (auxiliary to particles) | ontic | ambiguous | relationally ontic | epistemic (Bayesian) |
| Why is $\psi$ complex? | **theorem: $i$ is perpendicularity marker of $x_4$** | unexplained | unexplained | unexplained | unexplained | unexplained | unexplained | unexplained |
| Why is probability $\|\psi\|^2$? | **theorem: SO(3) Haar measure on $\Sigma_M$ cross-section (Prop. III.1)** | postulated | derived (circular: assumes equiprobable branches) | postulated (quantum equilibrium) | postulated | postulated | postulated | postulated (personal Bayesian) |
| Dimensionality of $\psi$ | **4D on $\mathcal{M}_G$; 3D $\psi(\mathbf{x},t)$ is cross-section at $x_4 = ict$** | 3N-dim config space (postulated) | 3N-dim config space (postulated, real) | 3N-dim config space (postulated, real) | 3N-dim config space (postulated, real) | 3N-dim config space (postulated) | 3N-dim relational | 3N-dim epistemic |
| Multi-particle entanglement structure | **theorem: joint $x_4$-coincidence on common McGucken Sphere (Prop. VIII.1)** | postulated tensor-product | postulated universal-$\psi$ branching | postulated nonlocal guidance | postulated joint stochastic | postulated joint Hamiltonian | postulated relational | postulated joint Bayesian |
| Configuration space ontology | **derivative space (N copies of $\mathcal{M}_G$ joined by McGucken Sphere)** | primitive | primitive | primitive | primitive | primitive | primitive | primitive |
| **D. Measurement and collapse** | | | | | | | | |
| Born rule $P = \|\psi\|^2$ | **theorem (Prop. III.1)** | postulated | postulated (or via decision theory; circular) | postulated (quantum equilibrium) | postulated (with stochastic params) | postulated | postulated | postulated (personal Bayesian) |
| Apparent collapse $(R)$ | **theorem (Prop. V.1, no separate $(R)$)** | separate postulate | branching primitive | guidance equation | stochastic dynamics added | system-environment Hamiltonian added | relational primitive | agent primitive |
| Preferred basis | **theorem from Compton-frequency (Prop. VII.1)** | left arbitrary | left arbitrary | configuration-space | localization parameter | system-environment split (input) | relational | agent |
| Irreversibility of measurement | **theorem (Prop. VI.1)** | left unexplained | branching | trajectories | stochastic | environmental coupling | relational | agent |
| Quantum-classical cut | **continuous via Compton frequency (Prop. VII.1)** | arbitrary placement | no cut (branching) | hidden-variable/wavefunction split | stochastic-rate threshold | system-environment split (input) | relational | agent |
| **E. Canonical thought experiments** | | | | | | | | |
| Schrödinger's cat | **resolved: cat in definite state because $\omega_C \sim 10^{50}$ Hz forces decoherence below detection (§V.6.1); reductio *vindicated*** | superposition until observed | branching into alive+dead worlds | hidden variable picks outcome | stochastic localization | system-environment einselects | relational outcome | agent's Bayesian update |
| Wigner's friend | **dissolved: friend's definite outcome and Wigner's superposition are projections of one $x_4$-extended state onto different slices, with $x_4$-coincidence guaranteeing consistency (§V.6.2)** | paradox / consciousness role | each branch is self-consistent | hidden variable resolves | stochastic dynamics resolves | environmental decoherence | relational, no contradiction | agent-relative facts |
| Bell-inequality violation / nonlocality | **theorem from $x_4$-coincidence (Prop. VIII.1, First Law of Nonlocality)** | acausal | acausal | non-local guidance | local stochastic | acausal | relational | epistemic |
| **F. Information and dynamics** | | | | | | | | |
| Information preservation | **theorem (Prop. X.1)** | imposed | imposed | imposed | violated | imposed | imposed | epistemic |
| Black hole information paradox | **dissolved (Prop. X.4, X.5)** | open | open | open | violates unitarity | open | open | open |
| Page curve | **theorem (Prop. X.3)** | imposed by hand | imposed | imposed | violated | imposed | not addressed | not addressed |
| Origin of dynamics ($\partial_t$) | **theorem: $D_M$'s flow restricted to $\Sigma_t$ (Prop. XIII.5)** | postulated | postulated | postulated | postulated + stochastic | postulated | postulated | postulated |
| **G. Categorical structure (per Wheeler / co-generation)** | | | | | | | | |
| Universe as one object | **yes (one $x_4$-extended state; co-generation theorem XIII.I)** | not formally | partly (universal $\psi$) | no (particles + $\psi$) | no | no | no (relational) | no (agent-relative) |
| Observer co-derived with observed | **yes (both configurations in $\mathcal{M}_G$, Prop. XIII.6)** | no (cut postulated) | no (observers in branches) | no (observers separate) | no | no | partial (relational) | no (agent privileged) |
| Delayed-choice / participatory structure | **theorem from $x_4$-coincidence (Prop. VIII.1)** | acausal influence | branch selection | retrocausal pilot wave | stochastic | acausal | frame-dependent | agent's posterior |
| Space-operator co-generation (Sense 2) | **theorem (Theorem XIII.I)** | absent (independent inputs) | absent | absent | absent | absent | absent | absent |
| Space-operator categorical equivalence (Sense 1) | **recovered as descent image via $F_{\rm Spec}$ (Theorem XIII.G of [1])** | absent | absent | absent | absent | absent | absent | absent |
| **I. Fields and gauge structure** | | | | | | | | |
| Status of field operator $\hat{\phi}(x)$ | **derived: $D_M$-flow on Fock space (§V.bis.3)** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Origin of equations of motion (KG, Dirac, Maxwell, YM) | **theorem: 4 sectors of $\mathcal{L}_{\rm McG}$ forced [2]** | postulated separately | postulated separately | postulated separately | postulated separately | postulated separately | postulated separately | postulated separately |
| Origin of gauge group $U(1) \times SU(2) \times SU(3)$ | **theorem (settled for U(1); programmatic for SU(2), SU(3))** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Origin of microcausality / locality | **theorem: $x_4$-coincidence light-cone (Prop. VIII.1)** | axiom | axiom | axiom | axiom | axiom | axiom | axiom |
| Treatment of gravity | **structural: metric is constraint-projection feature; no graviton needed [3]** | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton |
| Substrate-scale UV regulation | **structural: McGucken-Sphere granularity [1, Theorem H]** | renormalization required | renormalization required | renormalization required | renormalization required | renormalization required | renormalization required | renormalization required |
| GUT embedding required? | **no (gauge group exactly $G_{\rm SM}$; predicts no proton decay)** | open | open | open | open | open | open | open |
| **H. Foundational achievement** | | | | | | | | |
| Measurement problem | **categorically dissolved (Prop. XIII.6)** | open | open / branching | open / non-local | open / stochastic | open / einselection-circularity | open / relational | open / subjective |
| Quantum nonlocality vs. relativity | **reconciled via $x_4$-coincidence (Prop. VIII.1)** | tension | tension | tension | tension (stochastic locality) | tension | relational | epistemic |
| Why these mathematical structures? | **theorems of $dx_4/dt = ic$** | brute facts | brute facts | brute facts | brute facts | brute facts | brute facts | brute facts |
| Empirical falsifiability | **Compton-frequency signature [4]** | not directly distinguishing | not directly distinguishing | quantum-equilibrium tests | direct (collapse rates) | not directly distinguishing | not directly distinguishing | not directly distinguishing |


The master table makes the structural advantage immediate. Where every prior programme has multiple foundational postulates and at least one open foundational problem — and where every prior programme either postulates the wave function or interprets a postulated object — the McGucken dx₄/dt = ic framework derives every entry in the postulate column as a theorem from a single primitive physical-geometric law $dx_4/dt = ic$. This is not a stylistic difference of presentation; it is a categorical difference of structure, established formally by the space-operator co-generation theorem (Theorem XIII.I), quantified by the two-orders-of-magnitude reduction in K-complexity, and made concrete by the wave function being a derived geometric object (§V.1) rather than an interpretively-flexible postulate. The detailed entries summarized in this master table are established as theorems throughout the paper, with section references in the table cells.



The McGucken dx₄/dt = ic framework is unique in deriving the Born rule as a geometric theorem of one foundational principle: the McGucken Principle that the fourth dimension is expanding in a spherically symmetric manner at the velocity of light, dx₄/dt = ic. The depth this derivation gives the McGucken framework into the measurement problem follows directly from what it means to derive Born from a foundational principle rather than postulate it. When Born is postulated, it is a *separate fact* glued onto the linear unitary dynamics — the dynamics evolve states by (U), and the Born rule independently selects probabilities at measurement; the two are logically disconnected, and the measurement problem is precisely the puzzle of how these two disconnected pieces are supposed to fit together at the moment of observation. Every prior interpretive programme inherits this disconnect: Copenhagen patches it with a separate (R) law, Many-Worlds with a branching primitive, Bohmian with quantum equilibrium and a guidance equation, GRW with stochastic localization, decoherence with a system-environment Hamiltonian, RQM with relational facts, and QBism with personal probability assignments. Each of these is, structurally, an *additional ingredient* introduced precisely because (U) and Born are independent inputs whose connection at measurement is not supplied by either of them.

When the McGucken framework derives Born from $dx_4/dt = ic$ as a geometric theorem, the disconnect is dissolved at the source. The Born rule is not added on top of the dynamics — it is a structural feature of the same geometric expansion that produces the dynamics. The squared amplitude $|\psi|^2$ is the SO(3) Haar measure on the McGucken-Sphere wavefront cross-section, the wavefront is the propagation of $x_4$'s spherical advance, and the unitary evolution is the action of $D_M$ on configurations of that wavefront. *Born and (U) are two readings of the same geometric fact*. There is no separate measurement event that has to bridge them, because there is no gap between them. The apparent collapse $R$ is then forced to be what Proposition V.1 establishes — the 3D spatial cross-section reading of an $x_4$-extended state — because there is no other structural slot in the framework where it could live. The preferred basis (Proposition VII.1), the irreversibility (Proposition VI.1), the absence of a separate $(R)$ law (Proposition IX.1), the unitarity itself (Proposition X.2), and the nonlocality without violation of relativistic causality (Proposition VIII.1) all follow as consequences of the same single derivation, because they all descend from the same source.

This is the deeper insight: every component of the standard "measurement problem" — the Born rule, the apparent collapse, the preferred basis, the irreversibility, the nonlocality, the absence of a clean quantum-classical cut — becomes a structural consequence of one geometric principle, and so the standard problem of how these components are supposed to be coordinated at the moment of measurement *does not arise*. The space-operator co-generation theorem (Theorem XIII.I) makes this categorical: because $\mathcal{M}_G$ (the space) and $D_M$ (the operator) are co-generated by $dx_4/dt = ic$, system, apparatus, observer, and dynamics are not four independent categories whose interaction must be coordinated by an additional measurement law — they are projections of one source-pair onto different spatial slices, and the measurement event is the geometric self-intersection $D_M(\Sigma_M(p)) \cap \Sigma_t$ of the source-pair with itself. Proposition XIII.6 establishes that the standard measurement problem cannot even be formulated within the McGucken dx₄/dt = ic framework's category structure, because the categorical separation it requires has been dissolved at the source by the co-generation. Born being a theorem rather than a postulate is the doorway to all of this; what follows in this paper is the formal development of what waits behind that doorway.

 This paper establishes the framework's resolution of the measurement problem through seven formal Propositions. **Proposition III.1** derives the Born rule P = |ψ|² as a forced geometric consequence of the squared-amplitude structure of McGucken-wavefront cross-sections, with the three-piece breakdown imported from [5, §VII] and [6, Theorem 11]: the complex character of ψ from i as perpendicularity marker of x₄, the quadratic exponent forced by elimination of |ψ|¹, |ψ|³, Re(ψ), Im(ψ) alone as candidates, and the SO(3) Haar-measure shape forced by spherical symmetry. **Proposition IV.1** establishes that the superposition principle (SP) is itself a Grade-1 theorem of dx₄/dt = ic, with linear addition of complex amplitudes forced as the unique geometric overlap operation respecting SO(3) Haar-measure, Lorentz-covariance, linearity, and Born-rule compatibility — and not a postulate of the Hilbert-space structure. **Proposition V.1** establishes that the apparent collapse R is not a separate dynamical law but the 3D spatial cross-section reading of an x₄-extended state, with no separate (R) postulate required. §V.6 applies this resolution directly to the two canonical thought experiments — Schrödinger's cat (1935) and Wigner's friend (1961) — showing that Schrödinger's reductio is *vindicated* (the cat is in a definite state because its Compton frequency is enormous and decoherence is below any detection threshold) and Wigner's apparent paradox is *dissolved* (the friend's definite outcome and Wigner's superposition description are projections of one $x_4$-extended state onto different spatial slices, with consistency guaranteed by $x_4$-coincidence). Section V.bis extends the structural derivation strategy from the wave function to fields more broadly — establishing that classical fields (electromagnetic, gravitational), the wave function as a complex scalar field, quantum fields in QFT, and gauge fields are all derived structures rather than independent postulates. Every field type descends from the source-tuple $F_M = (\Sigma_M, \mathcal{G}_M, \mathcal{M}_G, D_M, \mathcal{S}_M, \mathcal{A}_M)$ as a theorem: classical fields are curvatures or potentials of McGucken-derived bundles; the wave function is the cross-section reading of an $x_4$-extended complex scalar field on $\mathcal{M}_G$; quantum fields in QFT are $D_M$-flow structures on Fock space; gauge fields are connections on principal bundles whose Lie-group structure descends from the McGucken Symmetry's internal action (settled for U(1); programmatically in place for SU(2)$_L$ via Cl(1,3)$^+$ spinor structure; open research for SU(3)$_c$ via the substrate-scale Connes-descent route of [1, Theorem H]). The McGucken dx₄/dt = ic framework's commitment is uniform: every aspect of every field type is ultimately a theorem of $dx_4/dt = ic$, and the apparent diversity of field types in standard physics is a structural feature of which sector of the McGucken Lagrangian $\mathcal{L}_{\rm McG} = \mathcal{L}_{\rm kin} + \mathcal{L}_{\rm Dirac} + \mathcal{L}_{\rm YM} + \mathcal{L}_{\rm EH}$ governs the flow. **Proposition VI.1** establishes that the irreversibility of measurement is the same x₄-monotonicity that grounds the second law of thermodynamics throughout the McGucken corpus [7, 8], requiring no separate stochastic dynamics. **Proposition VII.1** establishes that the preferred basis is selected by environmental Compton-frequency decoherence, with the cut between quantum and classical specified by a concrete physical mechanism rather than left arbitrary. **Proposition VIII.1** establishes that quantum nonlocality is the geometric consequence of x₄-mediated correlation through the six-sense null-surface identity of the McGucken Sphere, with the First Law of Nonlocality (all nonlocality begins in locality) supplying the structural account [9]. **Proposition IX.1** establishes that the absence of a separate (R) law is itself a theorem rather than an interpretive choice, with the apparent (R) phenomenon reduced to the 3D-projection reading of unitary x₄-evolution.

§X extends the framework's resolution from the measurement problem to the black hole information paradox, showing that both are the same problem at different scales. Through Propositions X.1 (information preservation as a theorem of x₄'s smoothness), X.2 (unitarity is derived rather than postulated), X.3 (the Page curve as a theorem of x₄-coincidence redistribution during evaporation), X.4 (the structural identification of the measurement problem and the information paradox), and X.5 (the McGucken dx₄/dt = ic framework as the only known framework that derives unitarity itself rather than postulating it), the section establishes that information is never destroyed in any physical process — the preservation is a Grade-1 theorem of x₄'s smoothness rather than an additional postulate, and the same x₄-coincidence mechanism that resolves the measurement problem (Proposition V.1) resolves the information paradox at the cosmological scale.

§XI develops the structural punchline: where the original presentation already established the Born rule as a theorem, the analysis establishes that the *foundational pair* (Q1) linearity and (Q3) Born — the structural core of quantum mechanics — is *jointly* derived from one underlying principle. The Hilbert-space postulate (Q1) is no longer foundational; the Born rule (Q3) is no longer foundational; the apparent collapse (R) is no longer a separate dynamical law; unitarity itself is no longer a foundational commitment. All four are derived consequences of dx₄/dt = ic. The McGucken framework is the only known quantum framework with this joint-derivation property; all seven prior interpretive programmes and all four major information-paradox resolutions either take these structures as postulates or derive them from auxiliary frameworks while leaving deeper structures foundational.

§XII reinforces the structural punchline through the geometric reading of the Feynman path integral. Where Feynman's 1948 formulation of "the particle follows every path" has remained mysterious for nearly eighty years, the McGucken dx₄/dt = ic framework supplies the physical content: x₄'s expansion represents an expanding nonlocality, every point on that nonlocality is the photon's path because the photon's position is always on the expanding surface of nonlocality, and to observers in 3D this appears as the photon following every single possible radius of the expanding sphere. The four-proposition derivation chain — Huygens' principle from x₄-spherical expansion (Proposition XII.1), iterated Huygens generates all paths (Proposition XII.2), accumulated x₄-phase as the Feynman weight (Proposition XII.3), and the path integral as continuum limit (Proposition XII.4) — establishes the path integral as a theorem of dx₄/dt = ic [10, 11]. The reading reinforces Propositions III.1 (Born rule), V.1 (apparent collapse as cross-section reading), and VIII.1 (nonlocality from null-surface identity), supplying a single geometric mechanism that unifies them.

§XIII extends the structural reduction to the Hilbert-space framework itself. Through Propositions XIII.1 (Hilbert space is forced, not postulated), XIII.2 (which Hilbert space is forced for which physical system), XIII.3 (Hilbert space as one of several equivalent representation spaces), and XIII.4 (the Hilbert-space inner product, complex conjugation, and orthogonality structure as theorems of $dx_4/dt = ic$), the entire mathematical scaffolding of standard quantum mechanics — complex scalar field, specific carrier spaces (L²(ℝ³), ℂ² ⊗ L²(ℝ³), Fock space), inner-product structure, and the primacy of Hilbert space among formulations — is shown to be derived rather than primitive. The complete structural reduction places all six postulates Q1–Q6 of the standard Dirac–von Neumann system plus the unitarity foundation in the theorem column, leaving exactly one principle in the postulate column: dx₄/dt = ic. The structural development of §XIII culminates in the **space-operator co-generation theorem** (Theorem XIII.I) and the **dissolution-of-the-measurement-problem theorem** (Proposition XIII.6), which together constitute the deepest structural fact of the McGucken dx₄/dt = ic framework. The co-generation theorem states that the McGucken Principle $dx_4/dt = ic$ generates the McGucken Space $\mathcal{M}_G = (E^4, \Phi_M, D_M, \Sigma_M)$ and the McGucken Operator $D_M = \partial_t + ic\partial_{x_4}$ as a single source space-operator pair: $dx_4/dt = ic \Longrightarrow (\mathcal{M}_G, D_M)$ [12, 13]. The pair has full inverse derivability — $(\mathcal{M}_G, D_M)$ together determine the principle — so that space, operator, and principle are not three independent foundational structures but three readings of one structural fact. Proposition XIII.5 establishes that the principal quantum operators (Hamiltonian, momentum, Schrödinger operator, Dirac operator, canonical commutator $[\hat{q},\hat{p}] = i\hbar$, gauge-covariant derivative) are all theorems of $dx_4/dt = ic$ via $D_M$, recovering the standard operator algebra by projection, quantization, squaring, factorization, and covariantization. Proposition XIII.6 establishes the categorical impossibility of a separate measurement-collapse mechanism in the McGucken dx₄/dt = ic framework: any putative dynamical mechanism $\mathcal{R}$ for collapse must be either a new space (ruled out by the universal derivability principle of [12]), a new operator (ruled out by the universal operator-derivability principle of [13]), or a new principle (ruled out by the inverse derivability of the co-generation theorem). The measurement problem cannot be formulated within the McGucken dx₄/dt = ic framework's category structure, because the categorical separation between system, apparatus, observer, and dynamics that the standard problem requires is dissolved at the source by the co-generation of space and operator. The historical context of §XIII.13 surveys ten major prior frameworks — Hamilton, Heaviside, Noether, Dirac (1928, 1933), Wick, Newton-Wigner, Wheeler-DeWitt, geometric quantization (Kostant, Souriau), and Connes spectral triples — showing that each came close to one or another aspect of source-operator structure but none integrated all three components (space, operator, principle) into one co-generation theorem. The historical climaxes of §§XIII.13.10–XIII.13.11 establish the McGucken-Wheeler correspondence: the formal mathematics of John Archibald Wheeler's 1983 self-excited-circuit diagram (Fig. 22.13 of *Law Without Law*) — the most evocative visual proposal for a participatory observer-involved cosmology — is the space-operator co-generation theorem of the present paper. The three structural features of Wheeler's diagram — (W-A) universe as one connected object, (W-B) observer and observed co-derived from the same object, (W-C) transverse delayed-choice connection — are reproduced respectively by the McGucken Space $\mathcal{M}_G$, the co-generation theorem, and the First Law of Nonlocality (x₄-coincidence). Wheeler's "law without law" is the single source-law $dx_4/dt = ic$ from which space, operator, and dynamics descend together; the gap between observer-participancy and physical reality acknowledged in [14] is filled by the cross-section reading of Proposition V.1 with Born-distributed outcomes from Proposition III.1. Section XIII.13.11 collects the direct quotations from Bohr, Heisenberg, Schrödinger, Wigner, von Neumann, Bohm, and Wheeler in which each of them, in physics-grade writings, articulated some version of the categorical claim about the inseparability of observer and observed in quantum mechanics — Bohr's "isolated material particles are abstractions," Heisenberg's "what we observe is not nature itself but nature exposed to our method of questioning," Schrödinger's identification of entanglement as "the characteristic trait of quantum mechanics" and his cat thought experiment, Wigner's friend with its dividing line that "cannot be eliminated," von Neumann's invariance-under-cut-placement, Bohm's "undivided wholeness," and Wheeler's "no elementary phenomenon is a phenomenon until it is an observed phenomenon." The McGucken dx₄/dt = ic framework's space-operator co-generation theorem is the formal mathematics that the greats reached for but did not have. Section XIII.13.12 then asks the sharpest version of the historical question — *who came closest to recognizing that the operator generates the space and the space generates the operator?* — and answers it carefully by distinguishing two senses of "bidirectional": Sense 1 (categorical equivalence: re-encoding) versus Sense 2 (co-generation from a primitive law). In Sense 1, Stone (1936), Pontryagin (1934), Gelfand-Naimark (1943), the GNS construction (1947), Heisenberg-Born-Jordan matrix mechanics (1925), and Connes's spectral-triple programme with the reconstruction theorem (1980s–2008) all establish bidirectional categorical equivalences between algebraic and spatial structures of various kinds. None of these frameworks proposes a primitive physical law from which both sides descend. Sense-2 co-generation from a primitive physical law has been available in *no* prior framework of mathematical physics; the McGucken space-operator co-generation theorem is the first formal articulation of Sense-2 bidirectionality in the history of mathematical physics. The Connes-descent paper [1] establishes specifically that Connes's spectral triple is a downstream descent image of the McGucken Source-Tuple via a faithful descent functor $F_{\rm Spec}: \mathrm{McG}_6 \to \mathrm{SpecTriple}_{\rm comm}$, with Connes's reconstruction theorem run on the McGucken-Dirac spectral triple recovering the McGucken Euclidean four-manifold canonically — making Connes's framework, the deepest existing mathematical formulation of noncommutative geometry coupled to physics, the formal shadow of the McGucken dx₄/dt = ic framework projected into noncommutative-geometric language.

§XIV develops the comparative analysis. The seven major interpretive programmes — Copenhagen, Many-Worlds, Bohmian mechanics, GRW, decoherence-plus-environmental-selection, Relational Quantum Mechanics, QBism — are surveyed under three structural criteria: (i) does the framework derive the Born rule from a single underlying principle? (ii) does the framework resolve the preferred-basis problem from a specific physical mechanism? (iii) does the framework supply a geometric account of nonlocality consistent with relativistic causality? Each of the seven existing frameworks fails at least one of these criteria; the McGucken framework satisfies all three through the single principle dx₄/dt = ic. The structural payoff is substantial: where the seven existing frameworks each add postulates or modifications, the McGucken dx₄/dt = ic framework subtracts — the (R) postulate is removed, the Born rule becomes a theorem, nonlocality becomes a structural feature of x₄'s expansion, and unitarity itself is reduced to a theorem of x₄'s smoothness.

The paper closes (§XV) with the falsifiability framework specific to the measurement-problem and information-paradox treatments, including the cross-species Compton-frequency decoherence test (Theorem 22 of [6]), the McGucken-Bell directional modulation [15], the no-magnetic-monopole prediction, the Page curve as a falsifiable signature of x₄-coincidence redistribution, and the categorical commitment that information is never destroyed.

**Keywords:** measurement problem; wave function collapse; Born rule; black hole information paradox; unitarity; Page curve; Hawking radiation; McGucken Principle; dx₄/dt = ic; quantum nonlocality; Bell inequality; entanglement; preferred basis; environmental decoherence; Copenhagen interpretation; Many-Worlds; Bohmian mechanics; GRW; Relational Quantum Mechanics; QBism; black-hole complementarity; AdS/CFT; replica wormholes; soft hair; six-sense null-surface identity; Compton coupling; structural overdetermination; geometric derivation of probability; information preservation.

---

## I. Introduction: The Ninety-Year Problem

### I.1 Two dynamical laws

Standard quantum mechanics, as developed by Heisenberg, Schrödinger, Dirac, Born, and von Neumann between 1925 and 1932 and consolidated in the Dirac–von Neumann axiomatic system [16; 17], operates with two distinct dynamical laws:

**(U) Unitary evolution.** Between measurements, the state vector |ψ⟩ evolves according to the Schrödinger equation iℏ ∂|ψ⟩/∂t = Ĥ|ψ⟩. The evolution is deterministic, linear, and time-reversible. It preserves superposition: if |ψ⟩ = α|a⟩ + β|b⟩ at time t = 0, then at time t > 0 the state is |ψ(t)⟩ = α|a(t)⟩ + β|b(t)⟩, with |a(t)⟩ and |b(t)⟩ the unitarily evolved components.

**(R) Reduction at measurement.** Upon measurement of an observable Â with eigenstates {|a_i⟩}, the state vector "collapses" to one of the eigenstates: |ψ⟩ → |a_i⟩, with probability P(a_i) = |⟨a_i|ψ⟩|² (the Born rule). The reduction is stochastic, nonlinear, and time-irreversible. It destroys superposition: after the measurement, only one component survives.

### I.2 The problem

(U) and (R) are logically incompatible as fundamental dynamical laws. Five sharp difficulties:

**(i) When does (R) apply?** No principled rule specifies when (R) replaces (U). A measurement apparatus is itself a quantum system, so its interaction with the measured system should be governed by (U), producing a superposition of apparatus pointer states — never a single definite outcome. The standard pedagogical solution invokes a "quantum-classical cut" placed somewhere between the microscopic system and the macroscopic apparatus, but the placement is arbitrary [18, *Against Measurement*].

**(ii) Why (R) at all?** If (U) is the true dynamics, (R) is unnecessary — measurement should produce a superposition of "pointer reading + outcome" branches, with all branches present. If (R) is the true dynamics, it must be triggered by something. Standard quantum mechanics names neither trigger nor mechanism.

**(iii) Why P = |ψ|²?** The Born rule is a postulate. The squared-amplitude form is taken as given; no derivation from a deeper principle is offered in the standard formalism. Multiple later attempts — Gleason's theorem [19], decision-theoretic derivations [20; 21], envariance [22], frequentist limit theorems [23] — each derive |ψ|² from auxiliary assumptions that themselves require justification.

**(iv) Why irreversibility?** (U) is time-reversible; (R) is not. Where does the asymmetry come from? Standard quantum mechanics gives no answer; environmental decoherence accounts (Zurek, Joos, Zeh) supply *part* of an answer (irreversibility from environmental information leakage) but require additional input on the preferred basis and the Born rule.

**(v) Why nonlocality?** Bell's theorem [24] establishes that quantum correlations cannot be explained by local hidden variables. The CHSH inequality [25] is empirically violated up to the Tsirelson bound 2√2 [26]. The standard formalism reports the violation and proves the no-signalling theorem, but supplies no geometric account of how distant entangled particles maintain correlations consistent with relativistic causality.

### I.3 The seven interpretive programmes

Over ninety years, seven major interpretive programmes have addressed the measurement problem. Each adds structure to the standard formalism; none subtracts; and *none* derives the Born rule from a single foundational principle.

**Copenhagen** (Bohr, Heisenberg, 1927–1932): the wavefunction represents the experimenter's knowledge; (R) is the update of knowledge upon measurement; the quantum-classical cut is operational, placed wherever the experimenter draws it. The framework declines to give an ontological account of (R) and treats the Born rule as a postulate.

**Many-Worlds (Everett, 1957; DeWitt, Wallace, 2012):** all branches of the (U)-evolved superposition are equally real; (R) is the apparent restriction to one branch from the standpoint of an observer within a branch. The Born rule is not a postulate of the dynamics but is recovered through decision-theoretic or envariance arguments [20; 21; 22], each requiring auxiliary assumptions.

**Bohmian mechanics (de Broglie, 1927; Bohm, 1952; Dürr–Goldstein–Zanghì, 1992):** the wavefunction guides hidden variables (definite particle positions) via the guidance equation; (R) is apparent only and arises from observer ignorance of the hidden variables. The Born rule is derived from the equilibrium hypothesis (particles distributed according to |ψ|² initially), but the equilibrium hypothesis itself is an additional postulate [73] (Valentini showed quantum non-equilibrium would predict deviations from |ψ|²).

**GRW (Ghirardi–Rimini–Weber, 1986):** the Schrödinger equation is modified to include stochastic spontaneous-localization terms; (R) is a real physical process governed by these terms, with parameters λ (rate) and a (localization width) chosen to match observed quantum behavior at small scales and classical behavior at large scales. The Born rule emerges from the localization dynamics, but the dynamics itself is added by hand and the parameters are phenomenological.

**Decoherence-plus-environmental-selection (Zurek, Joos, Zeh, 1981–2003):** environmental coupling rapidly diagonalizes the system's reduced density matrix in a specific (pointer) basis, suppressing macroscopic interference and producing apparent (R) without any modification of (U). The framework correctly explains why macroscopic superpositions become unobservable but does not derive the Born rule and does not by itself solve the preferred-basis problem (which basis is the pointer basis depends on the system-environment coupling, and identifying that coupling requires additional input).

**Relational Quantum Mechanics (Rovelli, 1996):** the wavefunction is relational — it describes the state of one system relative to another observer-system. (R) is the update of one system's information about another. The framework takes the Born rule as a postulate and does not derive it.

**QBism (Fuchs, Mermin, Schack, 2002–present):** the wavefunction represents the personal beliefs of a single agent; (R) is the agent's Bayesian update upon experiencing a measurement outcome. The Born rule is taken as a normative constraint on the agent's beliefs, justified by Dutch-book arguments. The framework explicitly declines to derive the Born rule from a deeper physical principle, treating it as a primitive coherence requirement on the agent.

### I.4 What is missing

Every one of the seven programmes either takes the Born rule as a postulate or derives it from auxiliary assumptions that themselves require independent justification. None traces P = |ψ|² to a single foundational principle. Each programme also addresses (R) by adding structure — branches, hidden variables, stochastic localizations, environmental couplings, relational frames, or epistemic constraints. None reduces the apparent (R) phenomenon to a *theorem* of (U) plus a single geometric principle.

What is missing is a single foundational source from which:

* The Born rule P = |ψ|² is *derived*, not postulated.
* The apparent (R) phenomenon is reduced to a *theorem* of (U) plus the foundational source.
* Quantum nonlocality is given a *geometric* mechanism consistent with relativistic causality.
* The preferred basis is selected by a *concrete physical mechanism* with no operational arbitrariness.
* The whole structure follows from *one* principle, not a combination of postulates.

This paper establishes that the McGucken Principle dx₄/dt = ic is exactly such a foundational source, and that the measurement problem is, in the McGucken dx₄/dt = ic framework, a chain of formal theorems descending from this single geometric principle.

### I.5 Structural setup and notation

We adopt the conventions of [6, §1.5]:

**Convention I.5.1 (Spacetime manifold).** Spacetime is a smooth four-dimensional Lorentzian manifold (M, g) of signature (−, +, +, +).

**Convention I.5.2 (The McGucken Principle).** The McGucken Principle dx₄/dt = ic asserts that x₄ is a physical geometric axis advancing at the velocity of light from every spacetime event, with x₄ = ict and the i the perpendicularity marker of the fourth dimension relative to the three spatial dimensions.

**Convention I.5.3 (McGucken Sphere).** The McGucken Sphere of a spacetime event p ∈ M is the future null cone of p — the set of points reachable from p by an outgoing null wavefront propagating at speed c. In a 3D rest frame at proper time τ after the event, the McGucken Sphere intersects the spatial slice in a 2-sphere of radius cτ centered at the spatial location of p. The McGucken Sphere is the geometric expression of x₄'s spherically symmetric expansion projected into 3D space.

**Convention I.5.4 (Compton coupling).** A massive particle of rest mass m couples to x₄'s expansion at its Compton angular frequency ω_C = mc²/ℏ. The rest-frame wavefunction has the form ψ ∼ exp(−i mc²τ/ℏ), with τ the proper time along the particle's worldline [4, §2; 6, Theorem 4].

**Convention I.5.5 (Channel A / Channel B).** The dual-channel content of dx₄/dt = ic is referenced by two labels, following [27, §V.1]: *Channel A* (algebraic-symmetry content) — invariance under spacetime isometries, driving Stone's theorem and the Wigner classification; *Channel B* (geometric-propagation content) — spherical expansion from every event, driving Huygens' principle and the Feynman path integral.

**Convention I.5.6 (Six-sense null-surface identity).** From [28, §II.4], any pair of points p, q on the same McGucken Sphere centered on a common emission event E share geometric identity in six independent mathematical senses: foliation theory, level sets, caustics/Huygens wavefronts, contact geometry, conformal/inversive geometry, and null-hypersurface cross-section. The six-sense identity is preserved under null-geodesic propagation.

**Convention I.5.7 (Graded forcing).** Following [29, §1.4], theorems are tagged with grades: *Grade 1* (forced by the Principle alone), *Grade 2* (forced by Principle + standard structural assumptions), *Grade 3* (forced by Principle + external mathematical framework).

### I.6 The McGucken Principle dx₄/dt = ic Reading of x₄ = ict: The Physically Expanding Fourth Dimension Against the Minkowski Block and the Standard Removable-i View

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality. In this reading $x_4$ is a physical geometric axis, as physical as $x_1, x_2, x_3$, advancing at $c$ from every spacetime event; the coordinate relation $x_4 = ict$ is the mere integrated shadow of that advance, obtained by integrating $dx_4/dt = ic$ at fixed rate from $t_0$, and the imaginary unit $i$ is the perpendicularity marker of $x_4$ relative to the three spatial dimensions — the expansion of $x_4$ is orthogonal to $x_1 x_2 x_3$ in every direction, as the radii of an expanding sphere stand perpendicular to its surface (Convention I.5.2; [30]; [6, Theorem 5]). The present subsection sets this reading against the two readings of $x_4 = ict$ that the literature has carried since 1908, because the whole theorem chain of this paper rests on taking $dx_4/dt = ic$ as a physical law rather than as notation.

#### I.6.1 The three readings of x₄ = ict

The same four-symbol relation $x_4 = ict$ carries three different ontologies in three different programmes.

**The Minkowski reading (1908).** Minkowski introduced the imaginary time coordinate so that the invariant interval of special relativity takes the form of a sum of four squares, $dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2$ with $x_4 = ict$, and the Lorentz transformation becomes a rotation of a four-dimensional continuum. Einstein adopted exactly this device: in *The Meaning of Relativity* he writes "with Minkowski, we introduce in place of the real time co-ordinate $l = ct$, the imaginary time co-ordinate" $x_4 = ict$, and describes the Lorentz transformation as "a rotation, through an imaginary angle, of the four-dimensional system of co-ordinates" (verified-read: Einstein, *The Meaning of Relativity*, special-relativity chapter, p. 17–18). In the popular exposition he regards "Minkowski's 'world' in a formal manner as a four-dimensional Euclidean space (with an imaginary time coordinate)" (verified-read: Einstein, *Relativity: The Special and the General Theory*, Appendix II). In this reading $x_4$ is a genuine fourth coordinate of a single four-dimensional continuum in which past, present, and future events coexist as points — the block universe, or eternalism — and $i$ is the device that renders the four-metric Euclidean in form. What this reading does not contain is any rate: $x_4 = ict$ is the integrated interval, with no statement that $x_4$ advances relative to $t$.

**The standard / MTW reading.** The modern textbook treatment keeps the real indefinite metric $g_{\mu\nu}$ of signature $(-,+,+,+)$ as primary and treats the imaginary unit in $x_4 = ict$ as a removable notational artifact, to be dispensed with (verified-read: Misner, Thorne & Wheeler, *Gravitation*, Box 2.1, "Farewell to $ict$"; background: the imaginary time coordinate is deprecated on the grounds that it disguises the Lorentzian character of the geometry and does not carry over to curved spacetime). In this reading the physical content lives entirely in the real indefinite metric; the $i$ means nothing and is discarded. Einstein's own practice in the general theory matches the first half of this: for general relativity he abandons the imaginary coordinate and introduces "arbitrary co-ordinates $x_1, x_2, x_3, x_4$" with a general indefinite metric $ds^2 = g_{\mu\nu}\,dx^\mu dx^\nu$ (verified-read: Einstein, *The Meaning of Relativity*, general-relativity chapter, p. 34–35).

**The McGucken Principle dx₄/dt = ic reading.** The McGucken dx₄/dt = ic framework takes the $i$ to carry physical meaning as the perpendicularity marker of $x_4$'s advance, and takes the relation $x_4 = ict$ to be the integrated record of a physical rate $dx_4/dt = ic$: $x_4$ expands at the velocity of light, orthogonal to the three spatial dimensions, from every spacetime event, tracing the McGucken Sphere ([30]; [6]; Convention I.5.2–I.5.3). The Lorentzian signature is then a theorem of that perpendicular expansion rather than a postulated feature of a pre-given metric (§I.6.2 below; [12, §16.2]; [3]), and the single $i$ of $x_4 = ict$ is the common origin of every imaginary unit in quantum theory — the Schrödinger $i$, the canonical commutator $[\hat q,\hat p] = i\hbar$, the path-integral weight $e^{iS/\hbar}$, the Dirac $i\gamma^\mu$, the $+i\varepsilon$ prescription, the Fourier kernel, the Heisenberg evolution, the Wick rotation, and the complex wavefunction itself ([31, §V.5]; §III of this paper). Both the Minkowski continuum and the McGucken $x_4$ are physical four-dimensional structures; the distinction between them is not real-versus-imaginary but the following: the McGucken $x_4$ expands at $c$ from every event rather than standing as one static continuum; its $i$ encodes perpendicularity and thereby makes the Lorentzian signature a theorem; its $t$ is the emergent parameter measuring the expansion rather than a fourth axis on the same footing; and $dx_4/dt = ic$ reaches derivationally into relativity, quantum mechanics, and the Second Law, which the bare interval $x_4 = ict$ does not.

#### I.6.2 The Lorentzian signature as a theorem of perpendicularity

The perpendicularity reading of $i$ makes the metric signature a consequence, not an input. The differential advance of the fourth dimension is $dx_4 = ic\,dt$, perpendicular to the spatial three. Its square is

$$(dx_4)^2 = (ic\,dt)^2 = -c^2\,dt^2,$$

so the four-dimensional line element assembled from the spatial displacements and the $x_4$-advance is

$$ds^2 = dx_1^2 + dx_2^2 + dx_3^2 + (dx_4)^2 = dx^2 + dy^2 + dz^2 - c^2\,dt^2,$$

which is the Lorentzian interval of signature $(-,+,+,+)$. The single minus sign is produced by the $i$ in $dx_4/dt = ic$; it is the arithmetic record of the perpendicularity of $x_4$'s expansion to $x_1 x_2 x_3$, not a signature chosen by hand (Theorem 3.6 of [154]; [12, §16.2]; [3]; and §V.bis.1 of this paper, where the metric $g_{\mu\nu}$ is obtained as what the McGucken constraint $\Phi_M = x_4 - ict = 0$ produces when projected onto the spatial-temporal slice). The Minkowski reading obtains the same arithmetic but reads it in the opposite direction — it treats the Euclidean sum of four squares as primary and the $i$ as the device that recovers it — and the standard reading discards the $i$ and postulates the indefinite signature directly. In the McGucken dx₄/dt = ic framework the signature is the theorem $(ic\,dt)^2 = -c^2 dt^2$, read off the physical rate.

#### I.6.3 The logical cost of affirming x₄ = ict while dismissing dx₄/dt = ic

The block-universe argument and the "farewell to $ict$" position are, taken together, in tension, and the tension is exact rather than rhetorical. The eternalist conclusion is drawn from taking $x_4 = ict$ literally: the argument that past, present, and future coexist as points of one four-dimensional manifold requires $x_4$ to be a genuine fourth dimension on the same geometric footing as the spatial three, which is precisely what the assignment $x_4 = ict$ supplies. The same tradition then declares, with the standard reading, that the $i$ in $x_4 = ict$ is a removable artifact with no physical meaning.

These two commitments cannot both hold, because $x_4 = ict$ and $dx_4/dt = ic$ are the same statement under differentiation and integration. Differentiating the coordinate relation $x_4 = ict$ with respect to $t$ returns the rate $dx_4/dt = ic$; integrating the rate $dx_4/dt = ic$ at fixed $c$ from $t_0$ returns $x_4 = ict$. The imaginary unit stands in both expressions as the same factor. To affirm $x_4 = ict$ as physically real enough to ground a four-dimensional block, while dismissing its own derivative $dx_4/dt = ic$ — and with it the $i$ common to both — as a mathematical trick carrying no physical content, is to assert and deny one proposition. A reading that grants the integrated relation its full ontological weight owes the integrand the same weight.

The McGucken dx₄/dt = ic framework removes the tension by taking both expressions literally at once. The $i$ is perpendicularity in both; the rate $dx_4/dt = ic$ is a physical law; and $x_4 = ict$ is its integrated record. The four-dimensional reality this yields is not the static block but the McGucken Sphere expanding at $c$ from every event — an active, growing four-dimensional reality in which the advance of $x_4$ is ongoing physics rather than a frozen coordinate ([30]; [3]). The eternalist's genuine fourth dimension and the rate that the standard reading discards are thereby held in one ontology instead of being affirmed and denied in turn.

#### I.6.4 Why "the imaginary time coordinate fails in general relativity" does not touch the McGucken reading

The standard objection to $x_4 = ict$ is that it is a flat-spacetime convenience: the substitution turns the Minkowski interval into a Euclidean sum of squares only when the metric is constant, and on a curved Lorentzian manifold there is no global coordinate change that renders the indefinite metric positive-definite, so one must work with real coordinates and a general $g_{\mu\nu}$ (background: this is the content of the "Farewell to $ict$" position; it is reflected in Einstein's own switch to arbitrary real coordinates for the general theory, verified-read above). The objection is correct as stated, and it falls on the global-Euclideanization reading of the $i$ — the reading on which $x_4 = ict$ exists in order to flatten the whole manifold into a four-dimensional Euclidean space at once.

The McGucken dx₄/dt = ic framework never uses the $i$ for that purpose, so the objection does not reach it. Here the $i$ marks the perpendicularity of $x_4$'s advance to the spatial three at each event, and the relation $(dx_4)^2 = (ic\,dt)^2 = -c^2 dt^2$ is a local statement about the direction of that advance, holding at every event including in curved spacetime. The metric is not an arena into which an imaginary coordinate is inserted; it is the result of the perpendicular expansion, obtained from the McGucken constraint $\Phi_M = x_4 - ict = 0$ projected onto each spatial-temporal slice, with curvature sourced by the stress-energy of $x_4$-extended states through the Einstein-Hilbert sector of the McGucken Lagrangian (§V.bis.1; [3]; [12, §16.2]; [2]). The general theory is derived in the McGucken corpus with the Lorentzian metric, the Einstein field equations, and the Schwarzschild solution obtained as theorems of $dx_4/dt = ic$ ([3]). What the standard objection excludes is the global coordinate trick; the perpendicularity content of $i$, which is what the McGucken reading uses, carries over to curved spacetime intact, because it is attached to the physical advance of $x_4$ at each event rather than to a flattening of the whole manifold.

#### I.6.5 Comparison

The three readings are set out below, with the McGucken Principle dx₄/dt = ic reading at the left.

| Feature of $x_4 = ict$ | McGucken Principle $dx_4/dt = ic$ | Minkowski (1908) / block-universe | Standard / MTW ("Farewell to $ict$") |
|---|---|---|---|
| Status of $x_4$ | physical fourth dimension expanding at $c$ from every event, tracing the McGucken Sphere | genuine fourth coordinate of a single static four-dimensional continuum | bookkeeping label; physics carried by the real indefinite metric $g_{\mu\nu}$ |
| Meaning of the $i$ | perpendicularity marker of $x_4$'s advance to $x_1 x_2 x_3$ | device rendering the four-metric Euclidean in form (rotation through an imaginary angle) | removable notational artifact, to be discarded |
| Primary object | the rate $dx_4/dt = ic$; $x_4 = ict$ is its integrated shadow | the integrated interval $x_4 = ict$; no rate is stated | the real indefinite metric $g_{\mu\nu}$ |
| Lorentzian signature | theorem: $(ic\,dt)^2 = -c^2 dt^2$ from the perpendicular expansion | the Euclidean four-square form read via the imaginary coordinate | postulated signature $(-,+,+,+)$ |
| Status of $dx_4/dt = ic$ | the physical law from which the theorem chain descends | not considered; only the integrated interval appears | not taken literally; the $i$ is a trick |
| Passage of time | active growing four-dimensional reality: the McGucken Sphere expands at $c$ from every event | static block universe / eternalism | typically block universe / eternalism |
| Role of $t$ | emergent parameter measuring $x_4$'s expansion | a fourth axis on the same footing as the spatial three | the real time coordinate of $g_{\mu\nu}$ |
| Behaviour in general relativity | perpendicularity holds locally at every event; metric derived from $\Phi_M = x_4 - ict = 0$; GR obtained as theorems ([3]) | the imaginary-time Euclideanization is a flat-spacetime device only | real coordinates with indefinite $g_{\mu\nu}$ required; $ict$ abandoned |

Across every row the McGucken dx₄/dt = ic reading takes the imaginary unit and the relation $x_4 = ict$ at full physical weight: the $i$ is the perpendicularity of $x_4$'s expansion, the relation $x_4 = ict$ is the integrated record of the physical rate $dx_4/dt = ic$, the Lorentzian signature is the theorem $(ic\,dt)^2 = -c^2 dt^2$, and the four-dimensional reality is the McGucken Sphere expanding at $c$ from every event. The theorems of the remainder of this paper — the Born rule (§III), superposition (§IV), apparent collapse (§V), nonlocality (§VIII), and the information-paradox resolution (§X) — all descend from this physical reading of $dx_4/dt = ic$.

#### I.6.6 Another formalism-as-physics choice: the photon's undefined four-velocity and absent rest frame

The McGucken Principle dx₄/dt = ic predicts, for the photon, a definite physical state of motion: the photon is at absolute rest in $x_4$ ($v_{x_4} = 0$), carried outward by the expansion of the McGucken Sphere at $c$, while the universal rate $dx_4/dt = ic$ holds at its emission event as at every event. The formalism-as-physics choice set out in §I.6.3 recurs here in the photon's kinematics: the standard framework takes the mathematical degeneracy of the proper-time parametrization along a null worldline and reads it as the physical absence of a state of motion.

In special and general relativity the four-velocity is $u^\mu = dx^\mu/d\tau$, normalized $u^\mu u_\mu = -c^2$ for a massive particle. Along a photon's null worldline the proper time does not advance, $d\tau = 0$, so $u^\mu = dx^\mu/d\tau$ is the undefined quotient $0/0$; the standard treatment replaces it with a null tangent $k^\mu = dx^\mu/d\lambda$ ($k^\mu k_\mu = 0$) carried by an affine parameter $\lambda$, and states that the photon has no rest frame because the boost factor $\gamma = (1 - v^2/c^2)^{-1/2}$ diverges as $v \to c$ (background: standard textbook relativity). The mathematics is correct. The reading laid over it — that the photon therefore has no state of motion of its own — is the formalism-as-physics choice, taking the breakdown of one parametrization for the absence of a physical state.

The McGucken dx₄/dt = ic framework specifies the photon's state through quantities that do not pass through proper time. The universal rate is $dx_4/dt = ic$ at every event (Convention I.5.2). The Sphere-tangent velocity is $v_{x_4} = c/\gamma$ (equal to $c\,d\tau/dt$), the velocity component along the expanding McGucken Sphere; for the photon $\gamma \to \infty$ gives $v_{x_4} = 0$, the state named absolute rest in $x_4$. The photon rides the McGucken Sphere: at rest in $x_4$, carried outward at $c$ as the wavefront of the event from which it was emitted, which is what makes it the tracer of $x_4$'s expansion (§XIII). The vanishing of $d\tau$ removes the proper-time four-velocity $u^\mu = dx^\mu/d\tau$, the object on which the standard framework builds the photon's kinematics; it leaves $dx_4/dt = ic$ and $v_{x_4} = c/\gamma$ intact, and these specify the photon's state with no rest frame and no proper time. Where the standard reading reports an absence, the McGucken dx₄/dt = ic reading reports a definite state, absolute rest in $x_4$.

| The photon's state of motion | McGucken Principle $dx_4/dt = ic$ | Standard SR/GR |
|---|---|---|
| Physical state | absolute rest in $x_4$, $v_{x_4} = c/\gamma = 0$; rides the expanding McGucken Sphere | no rest frame; $\gamma \to \infty$ as $v \to c$ |
| Rate carried at the event | $dx_4/dt = ic$, universal at every event | — |
| Proper-time four-velocity $u^\mu = dx^\mu/d\tau$ | not the carrier of the state; $d\tau = 0$ leaves it undefined | undefined ($0/0$); replaced by null tangent $k^\mu = dx^\mu/d\lambda$ |
| Status of "undefined" | degeneracy of one parametrization | read as: the photon has no state of motion of its own |

The McGucken dx₄/dt = ic framework supplies for the photon what the proper-time four-velocity cannot: a definite physical state, absolute rest in $x_4$ while the McGucken Sphere expands at $c$, carried by the universal rate $dx_4/dt = ic$ rather than by a proper-time parametrization that the null worldline sends to $0/0$.

---

## II. The Standard Statement of the Measurement Problem

### II.1 The von Neumann measurement scheme

Following von Neumann [17], a quantum measurement is modeled as a unitary interaction between system S (Hilbert space ℋ_S) and apparatus A (Hilbert space ℋ_A). Let {|s_i⟩}_i be eigenstates of the system observable Ŝ being measured, and let |A_0⟩ be the apparatus's initial "ready" state. The von Neumann measurement interaction is the unitary operator U_meas defined by

  U_meas |s_i⟩ ⊗ |A_0⟩ = |s_i⟩ ⊗ |A_i⟩,

where {|A_i⟩}_i are orthogonal pointer states of the apparatus correlated with the system's eigenvalues. Linearity of U_meas extends this to superpositions:

  U_meas (Σ_i c_i |s_i⟩) ⊗ |A_0⟩ = Σ_i c_i |s_i⟩ ⊗ |A_i⟩.

The post-measurement state is therefore an entangled superposition. By (U), this is the correct dynamical evolution. By (R), the apparatus is observed to be in a definite pointer state |A_k⟩ for some specific k, with probability |c_k|² (Born rule).

### II.2 The four sub-problems

The measurement problem decomposes into four sub-problems:

**(P1) The probability problem.** Why is the probability of outcome k given by |c_k|² rather than some other function of c_k? The Born rule is taken as a postulate in standard quantum mechanics; its derivation from deeper principles has been the subject of ninety years of foundational work.

**(P2) The collapse problem.** Why does the linear superposition Σ_i c_i |s_i⟩ ⊗ |A_i⟩ appear to reduce to a single branch |s_k⟩ ⊗ |A_k⟩? The reduction is not a consequence of (U); it must either be added as (R) (Copenhagen, GRW) or explained away as observer-relative (Many-Worlds, RQM, QBism) or as ignorance of hidden variables (Bohmian mechanics).

**(P3) The preferred-basis problem.** The reduced density matrix ρ_S = Tr_A |Ψ⟩⟨Ψ| of the post-measurement state in the eigenbasis {|s_i⟩} is diagonal: ρ_S = Σ_i |c_i|² |s_i⟩⟨s_i|. But ρ_S is also diagonal in any other basis obtained by unitary transformation of the eigenbasis. Why is the *eigenbasis of Ŝ* the basis in which we observe definite outcomes, rather than some other basis? The standard answer (decoherence) requires specifying the system-environment coupling — but this just shifts the problem to choosing the coupling.

**(P4) The irreversibility problem.** (R) is irreversible: once the system is in a definite eigenstate, it cannot be returned to the original superposition. (U) is reversible. Where does the asymmetry come from?

To these four standard sub-problems we add a fifth, present in any relativistic treatment:

**(P5) The nonlocality problem.** Bell-type entangled systems exhibit correlations stronger than any local hidden-variable theory permits, with the Tsirelson bound 2√2 setting the maximum quantum violation of CHSH. The standard formalism reports the violation and proves no-signalling, but does not supply a geometric mechanism for the maintained correlations across spacelike separation.

### II.3 The status of the Born rule across interpretations

The treatment of the Born rule across the seven interpretive programmes is summarized in Table II.1.

**Table II.1. Treatment of the Born rule across interpretive programmes.**

| Programme | Status of Born rule | Auxiliary assumptions for derivation |
|-----------|---------------------|--------------------------------------|
| Copenhagen | Postulate | None; explicitly accepted as primitive |
| Many-Worlds | Derived | Decision theory (Deutsch, Wallace) OR envariance (Zurek) — each requires auxiliary postulates |
| Bohmian mechanics | Derived | Equilibrium hypothesis (initial particle distribution = \|ψ\|²) — itself a postulate |
| GRW | Derived | Stochastic-localization dynamics with phenomenological parameters λ, a |
| Decoherence-plus-environmental-selection | Postulate | Decoherence shows \|c_i\|² are diagonal weights; does not derive squared-amplitude form |
| Relational Quantum Mechanics | Postulate | None; explicitly accepted as primitive |
| QBism | Normative | Dutch-book arguments on coherent agent beliefs; not a derivation from physical principles |
| **McGucken** | **Geometric theorem** | **None beyond the McGucken Principle dx₄/dt = ic; the Born rule is forced by the squared-amplitude geometry of the McGucken Sphere via the three-piece breakdown (i) i as perpendicularity marker of x₄, (ii) quadratic exponent forced by C1–C4, (iii) SO(3) Haar measure on spherical x₄-expansion (Proposition III.1)** |

The McGucken dx₄/dt = ic framework is the *only* framework in which the Born rule is derived from a single foundational physical principle (Theorem 11 of [6]; Proposition III.1 below). This is the structural fact that this paper develops in detail.

---

## III. The Born Rule as Geometric Theorem

### III.1 Proposition III.1 (Born rule as squared-amplitude geometry of x₄-wavefront cross-sections)

**Proposition III.1 (The Born rule is a Grade-2 theorem of dx₄/dt = ic).** *The probability density of finding a quantum particle at spatial position x at time t, given wavefunction ψ(x, t), is*

  P(x, t) = |ψ(x, t)|²,

*as a forced geometric consequence of three structural facts about x₄'s spherically symmetric expansion: (i) the complex character of ψ is the perpendicularity marker of x₄ relative to the spatial three; (ii) the squared exponent is the unique simple polynomial order producing a positive-definite probability density that respects superposition and gives correct interference patterns; (iii) the SO(3) Haar measure on the McGucken-wavefront cross-section forces the squared-amplitude form on the angular distribution. The full three-piece derivation is imported from [5, §VII] and [6, Theorem 11]; we reproduce it here in self-contained form.*

**Proof.** The proof proceeds in three pieces, each of which independently rules out alternatives to |ψ|² and which jointly force the Born rule.

#### Piece 1: Why ψ is complex

By Convention I.5.2, x₄ = ict, with the i the perpendicularity marker of x₄ relative to the spatial three. From [6, Theorem 5] (the rest-mass phase factor) and [31, §V.5] (the twelve-i catalog), every appearance of i in quantum theory is the algebraic marker of perpendicularity to the three spatial dimensions, inherited from x₄ = ict. The wavefunction ψ(x, t) is, by [6, Theorem 6] (wave-particle duality as dual-channel reading), the 3D cross-section of the four-dimensional McGucken-wavefront associated with the particle. The four-dimensional object has both a spatial-three projection (real-valued) and an x₄ projection (imaginary-valued), and the complex amplitude

  ψ(x, t) = Re ψ(x, t) + i · Im ψ(x, t)

records both projections simultaneously. The complex structure of ψ is therefore not a postulate — it is the algebraic expression of the four-dimensional structure of the McGucken-wavefront, with i tracking the x₄-component. Real-valued wavefunctions exist as standing waves but cannot account for the probability current j = (ℏ/m) Im(ψ* ∇ψ) or coherent time-evolution; the i is required because x₄ is required.

#### Piece 2: Why the exponent is 2 (not 1 or 3)

A probability density derived from ψ must satisfy four conditions:

**(C1) Positivity.** P(x, t) ≥ 0 everywhere.

**(C2) Normalization.** ∫ P(x, t) d³x = 1 over all space.

**(C3) Superposition-respecting.** If ψ = αφ + βχ with α, β ∈ ℂ, P(x, t) must be computable from φ and χ in a way that gives correct interference patterns observed in double-slit, Mach-Zehnder, neutron interferometry, and matter-wave experiments [32; 33; 34; 35].

**(C4) Lorentz-covariance.** Under a Lorentz transformation, P(x, t) transforms as the time-component of a four-current (with appropriate normalization).

Consider the candidates for the form of P(x, t) as a function of ψ:

* P = |ψ|¹ = |ψ|: violates (C3). For ψ = αφ + βχ, |ψ| = |αφ + βχ| does not produce the cross-term cos(θ) interference observed experimentally; it produces |α||φ| + |β||χ| in the worst case (no interference) or some non-quadratic combination that does not match observation.

* P = |ψ|³: violates (C2) for normalizable ψ in three-dimensional space without additional ad hoc rescalings, and violates (C3) in the same way as |ψ|¹: the cross-term has the wrong functional form to produce experimentally correct interference patterns.

* P = Re(ψ) alone: violates (C1) — ψ may be purely imaginary, in which case Re(ψ) = 0 globally even for nonzero ψ.

* P = Im(ψ) alone: violates (C1) — symmetric problem.

* P = Re(ψ)² + Im(ψ)² = |ψ|²: satisfies all four conditions. (C1) is automatic; (C2) is the requirement that ψ be normalized in L²; (C3) is satisfied because

  |αφ + βχ|² = |α|²|φ|² + |β|²|χ|² + 2 Re(α*β φ*χ),

  and the cross-term 2 Re(α*β φ*χ) is exactly the interference term observed experimentally; (C4) is satisfied because ψ*ψ is the time-component of the conserved Klein-Gordon current j^μ = (iℏ/2m)(ψ*∂^μψ − ψ∂^μψ*) divided by appropriate factors.

* P = |ψ|^{2n} for n > 1: candidates such as |ψ|⁴, |ψ|⁶ violate normalization (C2) without ad hoc rescalings, and produce wrong interference patterns in Piece-2 (C3) tests: the cross-term in |αφ + βχ|^{2n} has higher-order correlations not observed experimentally.

The squared exponent is therefore *forced* by the four conditions (C1)–(C4) and the requirement that the probability density match observed interference patterns. No exponent other than 2 satisfies all conditions.

#### Piece 3: Why the spherical-symmetric SO(3) Haar measure forces the squared form

By Convention I.5.3, the McGucken Sphere is a 2-sphere expanding at speed c from each spacetime event. Spherical symmetry of x₄'s expansion (Convention I.5.2) forces SO(3) invariance of the angular distribution of the McGucken-wavefront cross-section. The unique SO(3)-invariant measure on the 2-sphere is the SO(3) Haar measure, which in standard spherical coordinates (θ, φ) takes the form sin θ dθ dφ.

The probability density of finding the particle in solid angle dΩ at angle (θ, φ) is therefore proportional to the projected amplitude of ψ at that angle, weighted by the SO(3) Haar measure. Explicitly, for a wavefunction with angular structure ψ(r, θ, φ) = R(r) Y(θ, φ),

  P(θ, φ) dΩ ∝ |Y(θ, φ)|² sin θ dθ dφ.

The squared form |Y|² is *forced* by the SO(3) invariance: any other functional form (e.g. |Y|, |Y|³, Re(Y)²) breaks SO(3)-equivariance under change of polar axis, since complex amplitudes Y(θ, φ) acquire phases under SO(3) rotation but |Y|² is phase-invariant. This is the standard fact that |Y_lm|² is the SO(3)-invariant angular distribution; here it is recovered as a forced consequence of the spherical symmetry of x₄'s expansion.

#### Conclusion

The three pieces force the Born rule P = |ψ|² as a geometric theorem of dx₄/dt = ic:

* The complex character of ψ (Piece 1) is forced by the perpendicularity marker i of x₄.
* The squared exponent (Piece 2) is forced by positivity, normalization, superposition, and Lorentz-covariance.
* The squared form on angular distributions (Piece 3) is forced by the SO(3) symmetry of x₄'s spherical expansion.

The Born rule is therefore not a postulate — it is the unique probability density consistent with all three structural facts about x₄'s expansion. **∎**

### III.2 Comparison with prior derivations

The Born rule has been the subject of multiple derivations from auxiliary axioms over ninety years. We compare each to the McGucken derivation.

**Gleason's theorem (1957).** Gleason proved that the only probability measure on the closed subspaces of a separable Hilbert space of dimension ≥ 3 satisfying noncontextuality (the probability of a subspace depends only on the subspace, not on the basis containing it) and σ-additivity is the Born rule [19]. The theorem is mathematically rigorous but takes the Hilbert-space structure and the noncontextuality assumption as starting points. The McGucken dx₄/dt = ic framework derives both — the Hilbert space follows from the linear superposition of McGucken-wavefronts (Convention I.5.3), and noncontextuality follows from SO(3) invariance of the cross-section (Piece 3 above).

**Decision-theoretic derivation (Deutsch 1999; Wallace 2012).** Within Many-Worlds, the Born rule is derived from rationality axioms governing how an agent should bet on outcomes. The derivation requires accepting (i) the equivalence of all branches as "real" outcomes, (ii) specific rationality axioms (independence, transitivity, dominance), and (iii) the Many-Worlds ontology. Multiple critics [36; 37] have argued that the rationality axioms themselves require justification not present in the framework. The McGucken derivation requires no decision theory and no specific ontology: it follows from the geometric structure of x₄'s expansion.

**Envariance (Zurek 2005).** Zurek derives the Born rule from "environment-assisted invariance" — symmetry properties of system-environment entangled states. The derivation requires treating environmental degrees of freedom as part of the framework, and assumes a specific form of environment-system coupling. The McGucken derivation requires no environmental coupling: the Born rule is forced by the geometry of x₄'s expansion alone, with environmental coupling appearing only later in the preferred-basis selection (Proposition VII.1 below).

**Bohmian equilibrium hypothesis.** Bohmian mechanics derives the Born rule from the assumption that particles are initially distributed according to |ψ|² [38]. Valentini [73] showed that quantum non-equilibrium states (with distributions other than |ψ|²) are stable under Bohmian dynamics, so the equilibrium hypothesis is a separate postulate not derivable from the Bohmian dynamics itself. The McGucken dx₄/dt = ic framework requires no equilibrium hypothesis: the Born rule is forced by the geometry of x₄'s expansion at all times, not just initially.

**Frequentist / many-trial limit (Hartle 1968 [23]; Farhi, Goldstone & Gutmann 1989 [153]).** The Born rule is derived as the limit of relative frequencies in an infinite ensemble of measurements. The derivation requires accepting specific operational definitions of probability and infinite-trial limits, and has been criticized for circularity (the derivation uses |ψ|² in defining the limit). The McGucken derivation makes no reference to ensembles or trial limits.

**Structural diagnosis.** Each prior derivation requires auxiliary assumptions: the Hilbert-space structure (Gleason), Many-Worlds ontology plus rationality axioms (decision theory), specific environmental couplings (envariance), the equilibrium hypothesis (Bohmian), or ensemble limits (frequentist). The McGucken derivation requires only the McGucken Principle plus the standard conditions (positivity, normalization, superposition, Lorentz-covariance, SO(3) symmetry) shared with all reasonable physical theories. The structural reduction is substantial: where seven other frameworks each make the Born rule depend on auxiliary postulates, the McGucken dx₄/dt = ic framework makes it depend only on the geometry of x₄'s expansion.

### III.3 What this gains structurally

Proposition III.1 closes a foundational question that has stood since Born's 1926 paper. The Born rule is no longer a postulate in need of interpretation; it is a theorem of one geometric principle. Five structural consequences follow.

**First**, Q3 of the Dirac–von Neumann postulate system (Born rule) is removed from the foundational base of quantum mechanics. The McGucken dx₄/dt = ic framework does not require Born as a postulate; it derives Born from dx₄/dt = ic.

**Second**, the structural simplification is quantitative. By [29, §3.1], the McGucken Principle has Kolmogorov complexity K(McG) ∼ 10² bits; the Dirac–von Neumann axiomatic system has K(Q1–Q6) ∼ 10⁴ bits. Removing Q3 from the postulate list and recovering it as a theorem is one of six such reductions performed by the McGucken dx₄/dt = ic framework, which together account for the two-orders-of-magnitude compression.

**Third**, the squared-amplitude structure now has a geometric source: the spherical-symmetric expansion of x₄. Without the McGucken Principle, |ψ|² is a fact in need of interpretation; with the principle, |ψ|² is the algebraic expression of SO(3)-invariant angular distributions on the McGucken-wavefront cross-section.

**Fourth**, the i in ψ is now traceable to x₄ = ict. The complex structure is not an algebraic peculiarity but the perpendicularity marker of the fourth dimension. This connects the Born rule to the complex structures of [31, §V.5] (the twelve i's by hand): the Schrödinger i, the canonical commutation [q̂, p̂] = iℏ, the path integral weight e^(iS/ℏ), the Dirac iγ^μ, the +iε prescription, the Fourier kernel, the Heisenberg evolution, the Wick rotation, and the complex wave function itself are all geometric consequences of the same dx₄/dt = ic.

**Fifth**, the Lorentz-covariance of the Born rule (condition C4 in Piece 2) is automatic in the McGucken framework, since dx₄/dt = ic is Lorentz-covariant by construction (the Minkowski metric is recovered from x₄ = ict; see [6, §1.5.2; 30]). In other frameworks, Lorentz-covariance of the probability density requires separate argument [39].

---

## IV. Superposition as Geometric Overlap of McGucken-Sphere Wavefronts

### IV.1 Superposition in standard quantum mechanics

The superposition principle is the foundational structural feature of quantum mechanics that distinguishes it from classical mechanics. Stated formally:

**(SP) Superposition principle.** *If |ψ⟩ and |φ⟩ are physically realizable states of a quantum system, then for any α, β ∈ ℂ with |α|² + |β|² = 1, the state |χ⟩ = α|ψ⟩ + β|φ⟩ is also a physically realizable state of the system, distinct from both |ψ⟩ and |φ⟩ and from any classical mixture of them.*

(SP) is not derivable from (U) or (R) alone in the standard formulation. It is taken as part of postulate (Q1) of the Dirac–von Neumann axiomatic system: the state space is a complex Hilbert space, and the linearity of Hilbert space directly implies (SP). The structural status of superposition in standard quantum mechanics is therefore:

* (SP) is built into the Hilbert-space postulate (Q1), not derived.
* (SP) is the structural feature that makes interference patterns possible (double-slit, Mach-Zehnder, neutron interferometry, matter-wave experiments).
* (SP) is the structural feature that makes the measurement problem possible — without superposition, there would be nothing to "collapse."

The interpretive programmes treat (SP) variously. Copenhagen treats superposition as a feature of the experimenter's state of knowledge: prior to measurement, the experimenter does not know which eigenstate the system will be observed in, and the superposition encodes this ignorance. Many-Worlds treats superposition as ontologically real: all branches of the superposition are equally real, and the "world" splits into multiple copies at each measurement. Bohmian mechanics treats superposition as a feature of the guidance wave ψ but not of the hidden particles: the particles always have definite positions, and the superposition is the wave that guides them. GRW treats superposition as physically real but unstable: stochastic localization terms in the modified Schrödinger equation suppress macroscopic superpositions on a phenomenological timescale. Decoherence treats superposition as physically real but rapidly suppressed by environmental coupling. RQM treats superposition as relational. QBism treats superposition as a feature of the agent's beliefs.

None of these treatments derives the superposition principle itself from a deeper physical mechanism. Each accepts (SP) as either a postulate (Copenhagen, Many-Worlds, RQM, QBism), a feature of an additional dynamical structure (GRW, Bohmian), or a feature suppressed by environmental coupling (decoherence). The McGucken dx₄/dt = ic framework does derive (SP): the superposition principle is a Grade-1 theorem of the geometric overlap of McGucken-Sphere wavefronts in four-dimensional spacetime.

### IV.2 Proposition IV.1 (Superposition as geometric overlap of McGucken-Sphere wavefronts)

**Proposition IV.1 (Superposition is a Grade-1 theorem of dx₄/dt = ic).** *Two physically realizable states |ψ⟩ and |φ⟩ of a quantum system correspond to two McGucken-Sphere wavefronts ψ(x, t) and φ(x, t) in four-dimensional spacetime, each a 3D cross-section of a four-dimensional structure. Their linear superposition |χ⟩ = α|ψ⟩ + β|φ⟩ corresponds to the geometric overlap*

  χ(x, t) = α ψ(x, t) + β φ(x, t)

*at each spacetime point. The complex coefficients α, β determine the relative amplitude and phase of the two wavefronts at the overlap. The superposition principle (SP) is forced by three structural facts about x₄'s spherically symmetric expansion: (i) x₄'s expansion proceeds simultaneously and from every spacetime event (Convention I.5.2), so multiple wavefronts can coexist at the same spacetime point without interference at the level of x₄'s advance itself; (ii) the linear addition of complex amplitudes ψ + φ at each spacetime point is the unique algebraic operation that respects both the SO(3) Haar-measure structure of the McGucken Sphere (Proposition III.1, Piece 3) and the Lorentz-covariance of the four-dimensional state (Convention I.5.1); (iii) the perpendicularity marker i in x₄ = ict is the algebraic feature that allows complex coefficients α, β to encode relative phase information in the superposition, with the relative phase determining the interference pattern observed at the overlap (Theorem 6 of [6]).*

**Proof.** The proof proceeds in three pieces, each establishing one of the three structural facts.

#### Piece 1: Why x₄'s expansion permits multiple coexisting wavefronts

By Convention I.5.2, x₄'s expansion proceeds from every spacetime event simultaneously. A single spacetime event p₁ produces a McGucken Sphere expanding at rate c from p₁; a different spacetime event p₂ produces a McGucken Sphere expanding at rate c from p₂. At any spacetime point q reachable from both p₁ and p₂, both McGucken Spheres are present.

The two McGucken Spheres coexist at q without mutual interference at the level of x₄'s advance itself, because x₄ advances at the same rate ic from every spacetime event; the advance is a uniform property of the four-dimensional manifold, not a property that depends on which events have produced which wavefronts. Multiple wavefronts can coexist at q because they are all riding the same uniform x₄-advance.

This is the structural reason why quantum systems can be in superposition states in the first place: the underlying x₄-advance does not "select" between wavefronts. Each wavefront is a 3D cross-section of a four-dimensional structure (a McGucken Sphere from a specific source event), and multiple such cross-sections can be present at the same observation point. The geometric coexistence is automatic.

In contrast, in classical wave mechanics, two wave sources can also produce coexisting wavefronts at a common observation point (e.g., two flashlights illuminating a wall produce two coexisting light wavefronts at the wall). What distinguishes the quantum case is the *complex* structure of the wavefront amplitudes — a feature that, in the McGucken dx₄/dt = ic framework, traces directly to the perpendicularity marker i of x₄ (Piece 3 below).

#### Piece 2: Why linear addition of complex amplitudes is the unique algebraic combination

A combination operation ⊕ on quantum states ψ, φ at each spacetime point must satisfy four conditions:

**(D1) SO(3) Haar-equivariance.** Under SO(3) rotation of the spatial three-axes, the combined amplitude (ψ ⊕ φ)(x, t) must transform with the same SO(3) representation as ψ(x, t) and φ(x, t) individually. This is the requirement that the combination operation respect the SO(3) symmetry of x₄'s spherical expansion (Convention I.5.2 and Proposition III.1, Piece 3).

**(D2) Lorentz-covariance.** Under Lorentz transformations of the four-dimensional spacetime, the combined amplitude must transform as a four-scalar (or, for spinor states, as the appropriate Lorentz spinor representation). This is the requirement that the combination operation respect the Lorentz covariance of the four-dimensional state.

**(D3) Linearity in each argument.** The combination operation must be linear in each argument: (αψ + α'ψ') ⊕ φ = α(ψ ⊕ φ) + α'(ψ' ⊕ φ), and similarly for the second argument. This is required by the empirical fact that quantum interference patterns scale linearly with the source amplitudes — a fact established by every interference experiment from Davisson-Germer onward.

**(D4) Born-rule compatibility.** When the Born rule (Proposition III.1) is applied to the combined state, the resulting probability density must respect the conservation of total probability: ∫ |ψ ⊕ φ|² d³x must equal a finite number that reduces to ∫ |ψ|² d³x + ∫ |φ|² d³x in the limit of orthogonal ψ, φ.

Consider the candidate combination operations:

* *Linear addition: (ψ ⊕ φ)(x, t) = αψ(x, t) + βφ(x, t) with α, β ∈ ℂ.* This combination satisfies all four conditions: (D1) is automatic since complex addition preserves SO(3) representations; (D2) is automatic since complex addition preserves Lorentz scalars; (D3) is the defining property of linearity; (D4) holds with the cross-term 2 Re(α*β ⟨ψ|φ⟩) supplying the interference contribution and reducing to the orthogonal sum when ⟨ψ|φ⟩ = 0.

* *Multiplicative combination: (ψ ⊕ φ)(x, t) = ψ(x, t) · φ(x, t).* Violates (D3) — the multiplicative combination is not linear in either argument. Also violates (D4) — the resulting probability density |ψφ|² does not reduce to |ψ|² + |φ|² in the orthogonal limit.

* *Convex combination: (ψ ⊕ φ)(x, t) = αψ(x, t) + βφ(x, t) with α, β ∈ ℝ_{≥0}, α + β = 1.* This is the classical statistical-mixture combination. It violates (D3) — it is not linear in α, β as complex numbers, so it cannot represent the relative phase information required for interference patterns. The convex combination produces the classical mixture, not the quantum superposition; it does not produce interference.

* *Real linear combination: (ψ ⊕ φ)(x, t) = αψ(x, t) + βφ(x, t) with α, β ∈ ℝ.* This is the real-amplitude combination. It violates (D2) when ψ, φ are general Lorentz-covariant fields, because real linear combinations cannot encode relative phases that are required for Lorentz-covariant interference patterns. The complex coefficients are required.

* *Higher-order combination: (ψ ⊕ φ)(x, t) = ψ(x, t) + φ(x, t) + γ ψ(x, t)φ(x, t).* Violates (D3) for any γ ≠ 0 — the cross-term ψ·φ is not linear in the arguments separately. Also violates (D4) — the cross-term contributes a non-bilinear term to the probability density.

Linear addition with complex coefficients is therefore *forced* by the four conditions (D1)–(D4). No other combination operation satisfies all four. The superposition principle (SP) is therefore not a postulate — it is the unique combination operation consistent with the SO(3) Haar-measure structure of the McGucken Sphere, the Lorentz-covariance of the four-dimensional state, and the empirical interference patterns observed in matter-wave experiments.

#### Piece 3: Why complex coefficients encode relative phase, not just real amplitude

The complex coefficients α, β ∈ ℂ in the superposition χ = αψ + βφ encode two pieces of information at each spacetime point: the *amplitude* (modulus |α|, |β|) and the *relative phase* (argument arg(α) − arg(β)). The relative phase is the structural feature responsible for the interference pattern: when the two wavefronts ψ, φ overlap with the same phase (constructive interference), the combined amplitude is enhanced; when they overlap with opposite phases (destructive interference), the combined amplitude is suppressed.

By Convention I.5.2, the perpendicularity marker i in x₄ = ict is the algebraic feature that allows complex amplitudes to encode relative phase information in the superposition. The mechanism: the rest-mass phase factor exp(−i mc²τ/ℏ) of [6, Theorem 5] encodes the matter wavefunction's oscillation at the Compton frequency along the worldline; this oscillation is in the i direction (perpendicular to the spatial three) because that is the direction of x₄'s advance. Two wavefunctions ψ, φ at the same spacetime point have their phases determined by the integrated x₄-advance along their respective worldlines, with the difference between the two phases (the relative phase) being a real number measured in radians.

The complex coefficients α, β in the superposition represent the relative phases at the source: if α = |α| exp(iθ_α) and β = |β| exp(iθ_β), then the relative phase at the overlap is θ_α − θ_β + (phase accumulated along ψ's worldline) − (phase accumulated along φ's worldline). The complex multiplication αψ + βφ thus encodes the full phase relationship of the two wavefronts.

The factor i in x₄ = ict is therefore the algebraic prerequisite for superposition with relative phase. Without the i, the wavefunctions would be real-valued and could only encode amplitude, not phase; the resulting "superposition" would be a real linear combination with no interference pattern. The empirical fact of quantum interference patterns is, in the McGucken dx₄/dt = ic framework, the experimental signature of the perpendicularity marker i in x₄ = ict, manifest in the complex amplitudes that encode the relative phases of overlapping McGucken-Sphere wavefronts.

#### Conclusion

The three pieces force the superposition principle (SP) as a Grade-1 theorem of dx₄/dt = ic:

* Multiple coexisting wavefronts (Piece 1) are permitted because x₄'s uniform advance does not select between source events.
* Linear addition with complex coefficients (Piece 2) is forced by SO(3) equivariance, Lorentz-covariance, linearity, and Born-rule compatibility.
* Complex coefficients encode relative phase (Piece 3) because the i in x₄ = ict is the algebraic marker that allows phase information to be carried by the wavefunction.

Superposition is therefore not a postulate of quantum mechanics — it is the unique geometric overlap operation consistent with the structural facts of x₄'s spherically symmetric expansion. The Hilbert-space linearity of (Q1) is a derived structural feature of the McGucken-Sphere wavefront geometry, not a foundational postulate. **∎**

### IV.3 Why this is structurally distinct from the prior treatments

The McGucken account of superposition is structurally distinct from the seven prior approaches.

**Difference from Copenhagen.** Copenhagen treats superposition as a feature of the experimenter's knowledge — a representation of ignorance about which eigenstate will be observed. The McGucken dx₄/dt = ic framework treats superposition as a *physical* feature: two McGucken-Sphere wavefronts genuinely coexist at the same spacetime point, with both wavefronts present in the four-dimensional state. There is no ignorance involved; both wavefronts are real geometric objects.

**Difference from Many-Worlds.** Many-Worlds treats superposition as ontologically real, with all branches of the superposition equally real "worlds." The McGucken dx₄/dt = ic framework treats superposition as ontologically real, but as overlapping wavefronts in *one* four-dimensional spacetime, not as separate worlds. The two wavefronts are different McGucken Spheres from different source events, both present in the same four-dimensional manifold. The "branching" of Many-Worlds is replaced by the geometric overlap of wavefronts.

**Difference from Bohmian mechanics.** Bohmian mechanics treats superposition as a feature of the guidance wave ψ but not of the hidden particles. The McGucken dx₄/dt = ic framework requires no hidden particles; the superposition is a feature of the four-dimensional state itself, with no need for a separate hidden-variable layer.

**Difference from GRW.** GRW treats macroscopic superpositions as physically real but unstable, suppressed by stochastic localization terms. The McGucken dx₄/dt = ic framework treats macroscopic superpositions as physically real and *suppressed only by environmental Compton-frequency decoherence* (Proposition VII.1 below) — a derived consequence of the same dx₄/dt = ic principle, not an additional dynamical postulate. The stochastic localization parameters λ, a of GRW are replaced by the Compton frequencies of environmental constituents, which are physically determined.

**Difference from decoherence.** Decoherence treats superposition as physically real but rapidly suppressed by environmental coupling. The McGucken dx₄/dt = ic framework agrees that environmental coupling suppresses macroscopic superposition (Proposition VII.1) but supplies the specific physical mechanism (Compton-frequency coupling) and derives both the superposition principle itself (Proposition IV.1) and its rapid suppression in macroscopic settings from the same dx₄/dt = ic principle.

**Difference from RQM.** RQM treats superposition as relational, with different observers seeing different superpositions. The McGucken dx₄/dt = ic framework treats superposition as observer-independent: the four-dimensional state is the same for all observers, with the apparent observer-dependence arising from each observer's restricted access to the 3D cross-section (Proposition V.1 below).

**Difference from QBism.** QBism treats superposition as a feature of the agent's beliefs, with no observer-independent reality. The McGucken dx₄/dt = ic framework treats superposition as objectively real: the four-dimensional state is the genuine description of the world, and the superposition is a structural feature of overlapping wavefronts.

The structural payoff: the McGucken dx₄/dt = ic framework is the *only* framework that derives the superposition principle (SP) itself from a deeper physical mechanism. All seven prior frameworks accept (SP) as either a postulate or a feature of additional dynamical structure. The McGucken dx₄/dt = ic framework derives (SP) as a Grade-1 theorem of the geometric overlap of McGucken-Sphere wavefronts.

### IV.4 Macroscopic superposition: Schrödinger's cat resolved

The Schrödinger's cat thought experiment [40] illustrates the apparent paradox of macroscopic superposition: a cat in a box with a quantum-triggered poison apparatus is, by linearity of (U), placed into a superposition of "alive" and "dead" states until observation. The standard quantum mechanics framework either accepts this as a real physical state (Many-Worlds, GRW with very slow localization) or invokes (R) to collapse the superposition before observation (Copenhagen), or appeals to environmental decoherence to suppress it rapidly (Zurek decoherence).

The McGucken dx₄/dt = ic framework supplies the structural resolution. The cat-plus-apparatus-plus-environment system has of order 10²⁵ massive constituents, each coupled to x₄'s expansion at its Compton frequency. The Compton-frequency decoherence rate Γ_dec for the cat-system is, by Proposition VII.1,

  Γ_dec ≈ Σ_{i=1}^{10²⁵} ω_{C,i} (g_{S,i})² / ℏ

with the sum dominated by the nucleon and electron Compton frequencies. For typical macroscopic systems, Γ_dec is of order 10⁴⁰ s⁻¹ — far greater than any timescale on which the cat could be observed. The superposition of "alive" and "dead" branches in the four-dimensional state therefore decoheres on a Planck-short timescale, leaving the cat in a definite (alive or dead) configuration in the observer's 3D cross-section.

The cat is *not* in a superposition of alive and dead during the experiment — the superposition has decohered before any observation can be made. The McGucken dx₄/dt = ic framework therefore agrees with the standard decoherence resolution of the cat paradox, but supplies the specific physical mechanism (Compton-frequency coupling) and the specific empirical prediction (the cross-species mass-independence test of Theorem 22 of [6]) that distinguishes it from phenomenological decoherence accounts.

### IV.5 Microscopic superposition: the double-slit experiment

The double-slit experiment is the canonical demonstration of microscopic superposition. A photon (or electron, neutron, or molecule) traversing a double-slit apparatus is in a superposition of "passed through slit A" and "passed through slit B" wavefronts; the resulting interference pattern on the detection screen is the interference of the two wavefronts at each screen pixel.

In the McGucken dx₄/dt = ic framework, the double-slit superposition is the geometric overlap of two McGucken-Sphere wavefronts. The source event at the photon emission produces a single McGucken Sphere expanding at rate c. At the slit aperture, the McGucken Sphere is partially blocked by the aperture material (where massive constituents Compton-couple to x₄ and decohere the local wavefront) and partially transmitted through both slit openings. The transmitted portions of the McGucken Sphere act, by Huygens' principle ([6, Theorem 1]), as secondary sources of new McGucken Spheres expanding from each slit opening. These two new McGucken Spheres overlap at the detection screen, producing the interference pattern.

The complex amplitudes α(slit A), β(slit B) at the detection screen are determined by the integrated x₄-phase along the two paths from the source to the screen via slit A and via slit B. The relative phase α/β at each screen pixel determines whether the interference is constructive (large |α + β|², bright fringe) or destructive (small |α + β|², dark fringe). The Born rule (Proposition III.1) converts this to the observed probability of detection at each pixel.

The McGucken dx₄/dt = ic framework therefore supplies a fully geometric account of the double-slit interference: not as a "wave-particle duality" mystery but as the overlapping of two McGucken-Sphere wavefronts, with the interference pattern determined by the relative x₄-phase along the two paths. Wave-particle duality (Theorem 6 of [6]) is the dual-channel reading of this same geometric structure: the wavefront aspect (Channel B) corresponds to the geometric overlap of the wavefronts, and the particle aspect (Channel A) corresponds to the localized detection event at a specific screen pixel.

### IV.6 Summary

The superposition principle (SP) is a Grade-1 theorem of dx₄/dt = ic via Proposition IV.1, with three structural facts forcing it: (i) x₄'s uniform advance permits multiple coexisting wavefronts, (ii) linear addition with complex coefficients is the unique combination operation respecting SO(3) Haar-measure, Lorentz-covariance, linearity, and Born-rule compatibility, and (iii) the perpendicularity marker i in x₄ = ict is the algebraic feature allowing complex amplitudes to encode relative phase.

The Hilbert-space linearity of postulate (Q1) of the Dirac–von Neumann axiomatic system is a derived structural feature, not a foundational postulate. The interference patterns observed in double-slit, Mach-Zehnder, neutron interferometry, and matter-wave experiments are the empirical signature of the geometric overlap of McGucken-Sphere wavefronts, with the complex amplitudes encoding the relative x₄-phases along the overlapping paths.

The Schrödinger's cat thought experiment is resolved by Compton-frequency decoherence (Proposition VII.1): macroscopic superpositions decohere on Planck-short timescales, leaving the cat in a definite configuration. The double-slit interference is the geometric overlap of two McGucken-Sphere wavefronts from the slit openings, acting as Huygens' secondary sources.

The McGucken dx₄/dt = ic framework is therefore the only framework that derives (SP) itself from a deeper physical principle. All seven prior frameworks accept (SP) as either a postulate or a feature of additional dynamical structure.

---

## V. The Wave Function and Its Apparent Collapse

### V.1 What the wave function *is*: derivation, not interpretation

Among foundational questions in quantum mechanics, "*what is the wave function?*" has been the most stubborn. Physicists have agreed on how to *use* it (Born rule for probabilities, Schrödinger equation for evolution) for nearly a century, but have never agreed on what it *is*. The interpretive landscape on this question is the most divided in physics:

- **Copenhagen / Bohr**: $\psi$ is a calculational device, not a physical thing — "what we can say" about a system, not what the system is. Epistemic, not ontic.
- **Many-Worlds / Everett**: $\psi$ is the complete physical reality; everything is a branch of the universal wave function. Ontic and unique.
- **Bohmian / de Broglie–Bohm**: $\psi$ is a real "pilot wave" guiding actual particle trajectories that are themselves the primary ontology. Ontic but auxiliary.
- **GRW**: $\psi$ is real but undergoes spontaneous stochastic collapse modifications to its evolution. Ontic with stochastic dynamics added.
- **QBism**: $\psi$ is a personal Bayesian state of belief held by an agent. Strongly epistemic, agent-dependent.
- **Relational QM**: $\psi$ exists only relative to a frame of reference; different observers have different valid descriptions. Relationally ontic.
- **PBR theorem (Pusey-Barrett-Rudolph 2012)**: under certain assumptions, rules out psi-epistemic interpretations, suggesting $\psi$ is ontic — but does not specify *what kind* of ontic object.

Each interpretation gives a different answer to "what is $\psi$?", and the disagreement runs deep because the standard formalism *postulates* the wave function as primitive structural data and then *interprets* what kind of object the postulated entity is. The interpretive disputes are downstream of the foundational decision to take $\psi$ as a postulate rather than to derive it.

The McGucken dx₄/dt = ic framework's position is structurally different from all seven interpretations above: the wave function is *derived* from the McGucken Principle $dx_4/dt = ic$, with every aspect of its mathematical form (complex character, phase structure, linearity, evolution equation, Born-rule probability, multi-particle structure) being a theorem rather than a postulate. The interpretive question "what is $\psi$?" is not answered by selecting among competing interpretations of a postulated object; it is answered by reading off what the derivation establishes the object to be.

#### V.1.1 The McGucken definition of the wave function

In the McGucken dx₄/dt = ic framework, the wave function $\psi(\mathbf{x}, t)$ at a spacetime event $(\mathbf{x}, t)$ is the **complex amplitude assigned by the spherical $x_4$-wavefront emanating from a source event, evaluated at the field point $(\mathbf{x}, t)$**. More formally:

**Definition V.1 (The McGucken wave function).** Let $p_0 = (\mathbf{x}_0, t_0)$ be a source event in spacetime, and let $\Sigma_M(p_0, t)$ denote the McGucken Sphere — the spherical $x_4$-wavefront generated from $p_0$ by $dx_4/dt = ic$, expanding at the velocity of light $c$ over the time interval $t - t_0$. The wave function $\psi(\mathbf{x}, t)$ at the field point $\mathbf{x}$ is the complex amplitude carried by $\Sigma_M(p_0, t)$ at the cross-section point $\mathbf{x}$, with the complex character supplied by $i$ as the perpendicularity marker of $x_4$ relative to the spatial axes, and the phase structure supplied by the rate $c$ of $x_4$'s advance per unit time.

The wave function is therefore a *physically real, four-dimensional, geometric object* — the amplitude of a wavefront in physical space that propagates with $x_4$'s expansion at the velocity of light, with the standard 3D wave function $\psi(\mathbf{x}, t)$ being the spatial-slice cross-section of the underlying 4D structure $\Psi(\mathbf{x}, x_4)$ at the McGucken-constraint locus $x_4 = ict$ (the suppression-map $\sigma$ of the Wick-rotation theorem [31]).

#### V.1.2 The seven structural ingredients, each derived

The McGucken derivation gives the wave function its specific mathematical form as a chain of seven theorems, summarized below with the corresponding source theorem:

**Step 1 — Complex character of $\psi$.** The McGucken Principle $dx_4/dt = ic$ requires $x_4$ to advance perpendicular to the temporal direction with $i$ as the perpendicularity marker. The wave function inherits this complex structure from the geometric perpendicularity of $x_4$. The imaginary unit $i$ is not a mathematical convenience; it is the structural signature of $x_4$'s perpendicular advance. (Three-piece breakdown of [5, §VII] and [6, Theorem 11].)

**Step 2 — Phase rate $\omega = E/\hbar$.** The rate of $x_4$-advance is $c$, so the rate of phase accumulation per unit energy at the source event is $\omega = E/\hbar$ — the de Broglie–Planck-Einstein relation, derived in [6, Theorem 4]. The free-particle wave function $\psi \sim e^{i(\mathbf{k}\cdot\mathbf{x} - \omega t)}$ has temporal phase $-\omega t$ as the $x_4$-coordinate of the wavefront at time $t$, multiplied by $i$ from the perpendicularity marker, divided by $\hbar$ to convert energy to frequency.

**Step 3 — Wavefront propagation.** Each source event $p_0$ generates a spherical wavefront expanding at $c$, with the wave function $\psi$ being the amplitude carried by this wavefront. Huygens' principle is a theorem of this structure [41] — every point on the wavefront is itself a source of a new wavefront, and the superposition of wavefronts gives the wave function at later times.

**Step 4 — Linearity and superposition.** Because multiple source events generate wavefronts that pass through a given field point, and amplitude is additive at the level of complex numbers, the wave function at any field point is the linear superposition of contributions from all source events. Linearity is a theorem (Proposition IV.1 of the present paper), not a postulate.

**Step 5 — Schrödinger equation.** The combination of phase advance ($\omega = E/\hbar$), wavefront expansion at $c$, and superposition produces the wave equation; the non-relativistic limit produces the Schrödinger equation [6, Theorem 7]. The Hamiltonian $\hat{H}$ is the generator of $D_M$'s flow restricted to the spatial-slice projection (Proposition XIII.5 of the present paper).

**Step 6 — Born rule.** The probability of detecting the wavefront at a given field point is the SO(3) Haar measure on the spherical cross-section, which is $|\psi|^2$ (Proposition III.1 of the present paper). The squared modulus is forced by spherical symmetry of $x_4$'s expansion plus the elimination of $|\psi|^1$, $|\psi|^3$, $\mathrm{Re}(\psi)$, $\mathrm{Im}(\psi)$ alone as candidates per [5, §VII].

**Step 7 — Multi-particle entanglement structure.** Multi-particle wave functions are tensor products of single-particle wavefront structure, with the joint $x_4$-extended state encoding the entanglement structure. The "configuration space" on which the multi-particle wave function lives is itself a derivative space — N copies of the McGucken-Space carrier $\mathcal{M}_G$ joined by the McGucken Sphere structure (Proposition VIII.1 of the present paper, the First Law of Nonlocality, plus [9]).

Each step is a theorem of $dx_4/dt = ic$. The wave function in the McGucken framework is not just "real" or "geometric" in some metaphorical sense — it is specifically the complex amplitude of a spherically-expanding $x_4$-wavefront, with every aspect of its mathematical form being a derivation rather than a postulate.

#### V.1.3 The structural difference: postulate-and-interpret vs. derive-and-define

The categorical difference between the McGucken dx₄/dt = ic framework's wave function and the seven prior interpretations is the difference between *postulate-and-interpret* and *derive-and-define*. In the seven prior interpretations, the wave function is postulated as primitive structural data and then interpreted; the interpretive disputes are downstream of the postulation. In the McGucken dx₄/dt = ic framework, the wave function is derived from a primitive physical-geometric law and the meaning is fixed by the derivation; there is no separate interpretive step, because the derivation specifies what the derived object is.

The structural significance of this distinction is the following. When the wave function is postulated, the question "what is $\psi$?" admits multiple incompatible answers (epistemic vs. ontic, single-universe vs. branching, primary vs. auxiliary, observer-dependent vs. universal) because the postulate underdetermines the answer. When the wave function is derived from $dx_4/dt = ic$, the answer is fixed by the derivation: $\psi$ is the complex amplitude of an $x_4$-spherical wavefront, complex by perpendicularity, propagating at $c$, with squared-modulus probability fixed by spherical symmetry. The wave function is *physically real* (it is the actual amplitude of a geometric wavefront, not an epistemic device), *four-dimensional* (defined on the $x_4$-extended state, with the 3D $\psi(\mathbf{x}, t)$ being a spatial-slice cross-section), and *unique* (one underlying 4D object, with apparent observer-relative descriptions being projections onto different spatial slices — see Proposition V.1 below).

The wave-function-comparison table:

| Question about $\psi$ | Copenhagen | Many-Worlds | Bohmian | GRW | Decoherence | RQM | QBism | **McGucken** |
|---|---|---|---|---|---|---|---|---|
| Is $\psi$ postulated or derived? | postulated | postulated | postulated + hidden variables | postulated + stochastic terms | postulated | postulated | postulated | **derived from $dx_4/dt = ic$** |
| Is $\psi$ ontic or epistemic? | epistemic / instrumentalist | ontic (universal) | ontic (auxiliary to particles) | ontic | ambiguous | relationally ontic | epistemic (Bayesian) | **ontic and geometric (4D wavefront amplitude)** |
| Why is $\psi$ complex? | unexplained | unexplained | unexplained | unexplained | unexplained | unexplained | unexplained | **theorem: $i$ is perpendicularity marker of $x_4$** |
| Why is probability $\|\psi\|^2$? | postulated | derived (circular: assumes branching equiprobable) | postulated (quantum equilibrium hypothesis) | postulated | postulated | postulated | postulated (personal Bayesian) | **theorem: SO(3) Haar measure on $\Sigma_M$ wavefront cross-section** |
| Does $\psi$ live in 3D, 4D, or higher? | 3N-dim configuration space (postulated) | 3N-dim configuration space (postulated, real) | 3N-dim configuration space (postulated, real) | 3N-dim configuration space (postulated, real) | 3N-dim configuration space (postulated) | 3N-dim configuration space (postulated, relational) | 3N-dim configuration space (postulated, epistemic) | **4D structure on $\mathcal{M}_G$; 3D $\psi(\mathbf{x},t)$ is cross-section at $x_4 = ict$** |
| Does $\psi$ collapse? | yes (postulated $(R)$ rule) | no (branching only) | no (guidance equation) | yes (stochastic localization) | no (system-environment Hamiltonian) | relative collapse (frame-dependent) | yes (agent's Bayesian update) | **no real collapse; spatial-slice changes (Proposition V.1)** |
| Is $\psi$ observer-dependent? | partly (cut placement matters) | no | no | no | no (but cut is in coupling) | yes (frame-relative) | yes (agent-relative) | **no (one underlying 4D state); apparent observer-dependence is cross-section reading** |
| Origin of multi-particle entanglement | postulated tensor-product structure | postulated branching of universal $\psi$ | postulated nonlocal guidance | postulated joint stochastic dynamics | postulated joint Hamiltonian | postulated relational structure | postulated joint Bayesian state | **theorem: joint $x_4$-coincidence structure on common McGucken Sphere (Proposition VIII.1)** |

The pattern is decisive. Every cell in the McGucken column is a theorem with a derivation; every cell in every other column is either a postulate or an unexplained feature. The wave function in the McGucken dx₄/dt = ic framework is not one more competing answer to the question "what is $\psi$?" — it is the answer that emerges when the question is asked in the right form: not "what should we interpret $\psi$ to be?" but "what is $\psi$ derived to be?"

#### V.1.4 What this implies for the rest of §V

The remainder of §V (subsections V.2 through V.6) examines how this derived wave function projects onto spatial slices at the moment of measurement, producing the apparent collapse phenomenon that standard quantum mechanics formalizes via the $(R)$ postulate. The key point established here in §V.1 is that the wave function whose apparent collapse is being examined is *already a derived object* with a fixed geometric meaning. The collapse-related theorems (Proposition V.1, the cross-section reading; the resolution of Schrödinger's cat and Wigner's friend in §V.6, formerly §V.5) are statements about how this *specific* derived geometric object — the complex amplitude of a spherically-expanding $x_4$-wavefront — projects onto observer-event spatial slices, not statements about how some interpretively-flexible postulated object behaves.

The wave function being a derived theorem rather than an interpretively-flexible postulate is what allows the apparent collapse to be a *specific structural feature* of the underlying geometry rather than a *postulated additional law* (Proposition IX.1 of the present paper; the categorical impossibility of separate collapse mechanism, Proposition XIII.6). This is the foundational reason the McGucken dx₄/dt = ic framework can dissolve the measurement problem at the categorical level: the wave function is not a postulated object whose collapse needs an additional postulate; it is a derived geometric structure whose apparent collapse is a structural feature of how 4D wavefronts project onto 3D spatial slices.

---

### V.2 The (R) postulate in standard quantum mechanics

The reduction postulate (R) asserts that upon measurement, the state vector |ψ⟩ collapses to one of the eigenstates |a_i⟩ of the measured observable Â, with probability P(a_i) = |⟨a_i|ψ⟩|². The collapse is stochastic, nonlinear, and time-irreversible. Standard quantum mechanics treats (R) as a separate dynamical law alongside (U), and most interpretive programmes either accept (R) as primitive (Copenhagen, RQM, QBism), modify (U) to incorporate (R) (GRW), or explain (R) away as appearance (Many-Worlds, Bohmian, decoherence).

The McGucken dx₄/dt = ic framework does neither. Instead, it derives the apparent (R) phenomenon as the 3D spatial cross-section reading of an x₄-extended state evolving unitarily, with no separate (R) postulate required.

### V.3 Proposition V.1 (Collapse as 3D cross-section reading)

**Proposition V.1 (The apparent reduction R is the 3D cross-section reading of unitary x₄-evolution).** *Let |Ψ(t)⟩ ∈ ℋ_S ⊗ ℋ_A ⊗ ℋ_E be the unitary-evolved state of system + apparatus + environment at time t after a measurement interaction. Let π_{x_obs} be the projection onto the spatial three-slice Σ_{t} containing the observer at time t. Then the apparent collapse |Ψ(t)⟩ → |s_k⟩ ⊗ |A_k⟩ ⊗ |E_k⟩ observed by the observer is the algebraic content of π_{x_obs} |Ψ(t)⟩, with no separate (R) postulate required. The "outcome" of the measurement is the configuration of the four-dimensional state |Ψ(t)⟩ that lies in the observer's accessible region of the spatial slice Σ_{t} as x₄ advances.*

**Proof.** The proof proceeds through three steps.

**Step 1: The four-dimensional state.** From [6, Theorem 6] (wave-particle duality as dual-channel reading), every quantum state has a four-dimensional structure: it is simultaneously a McGucken Sphere (Channel B reading: spherically expanding x₄-wavefront cross-section) and a localizable particle (Channel A reading: eigenvalue event of position observable at each spacetime point of detection). The unitary-evolved state |Ψ(t)⟩ at time t describes the four-dimensional structure across the entire spacetime region accessible from the measurement interaction's past null cone.

**Step 2: The 3D cross-section.** A specific observer at spatial location x_obs at time t accesses the state through the 3D spatial cross-section Σ_t, the spacelike hypersurface t = const at the observer's instantaneous time. The projection π_{x_obs} : ℋ_S ⊗ ℋ_A ⊗ ℋ_E → ℋ_{Σ_t}^{loc} extracts the locally accessible content of the four-dimensional state at the observer's location. By (U), the global state evolves unitarily; the locally accessible content at the observer is the 3D restriction of this unitary evolution.

**Step 3: The apparent collapse.** The observer, accessing only the 3D cross-section Σ_t at their spatial location x_obs, observes a *single* configuration: the configuration of |Ψ(t)⟩ that lies at x_obs in the spatial slice. This single configuration corresponds, in the orthogonal branch expansion of |Ψ(t)⟩ into correlated system-apparatus-environment components Σ_j c_j |s_j⟩ ⊗ |A_j⟩ ⊗ |E_j⟩, to one specific branch |s_k⟩ ⊗ |A_k⟩ ⊗ |E_k⟩. The other branches |s_j⟩ ⊗ |A_j⟩ ⊗ |E_j⟩ for j ≠ k are present in the four-dimensional |Ψ(t)⟩ but not in the observer's local 3D cross-section: they are at *other* spatial locations x_j ≠ x_obs (where the apparatus pointer reads a different value, where the environmental degrees of freedom have a different configuration). The observer's unique outcome is the unique configuration intersecting their local cross-section.

The probability that the observer's local cross-section intersects branch k rather than branch j is governed by the Born rule (Proposition III.1): P(k) = |c_k|², the squared amplitude of branch k in the four-dimensional state. The squared amplitude is the SO(3)-Haar-weighted geometric measure of the branch's "size" in the spherically symmetric expansion of x₄ from the measurement interaction event. Branches with larger amplitude occupy larger fractions of the McGucken Sphere; the observer's local cross-section is more likely to intersect a larger branch.

The apparent collapse R is therefore not a separate dynamical law: it is the algebraic content of π_{x_obs} |Ψ(t)⟩ for an observer at specific spatial location x_obs at time t. The observer accesses one branch because the observer is at one spatial location; the observer would access a different branch if the observer were at a different spatial location. Both branches exist in the four-dimensional |Ψ(t)⟩; the observer's restricted access to the 3D cross-section is what creates the *appearance* of collapse.

The structure differs from Many-Worlds in that the branches are not separate "worlds" but separate spatial configurations within the same four-dimensional state. It differs from Bohmian mechanics in that there are no hidden variables — the four-dimensional state is the complete state, not a guidance function for hidden particles. It differs from Copenhagen in that there is no operational cut and no observer-relative information — the four-dimensional state is observer-independent. It differs from GRW in that there is no modification of (U) — the unitary evolution is exact. It differs from decoherence-plus-environmental-selection in that the preferred basis is selected by the spatial-three-slice structure of the 3D cross-section, not by the system-environment coupling alone. **∎**

### V.4 Comparison with Many-Worlds, Copenhagen, and Bohmian readings

The McGucken account of apparent collapse shares features with Many-Worlds (the unitary evolution is exact and all branches are present in the full state) and with Bohmian mechanics (the observer's outcome is determined by the observer's spatial configuration), but differs from both in three structural respects.

**Difference from Many-Worlds.** Many-Worlds treats branches as separate "worlds" — independent realities each containing an observer who sees a different outcome. The McGucken dx₄/dt = ic framework treats branches as separate spatial configurations within the same four-dimensional state. There is one reality (the four-dimensional |Ψ(t)⟩); observers at different spatial locations access different parts of it. The "branching" is a feature of the projection π_{x_obs}, not a feature of the dynamics. This avoids the standard objection to Many-Worlds — the proliferation of worlds and the question of why probabilities apply to branches at all — by replacing branching with spatial-slice projection.

**Difference from Bohmian mechanics.** Bohmian mechanics adds hidden variables (definite particle positions guided by ψ via the guidance equation). The McGucken dx₄/dt = ic framework adds *no* hidden variables. The wavefunction ψ is not a guidance function for hidden particles; it is the 3D projection of the four-dimensional state. The "definite outcome" the observer sees is the configuration of the four-dimensional state at the observer's spatial location, not a hidden particle position revealed by measurement.

**Difference from Copenhagen.** Copenhagen treats the wavefunction as the experimenter's knowledge and (R) as a Bayesian update. The McGucken dx₄/dt = ic framework treats the wavefunction as a 3D projection of an objective four-dimensional state, with the apparent collapse a structural feature of the projection (not an epistemic update). There is no observer-relative information; there is one objective four-dimensional reality, with multiple observers accessing different parts of it.

### V.5 In plain language

A photon traveling through a double-slit apparatus emerges as a McGucken Sphere — a four-dimensional object whose 3D cross-section is the Huygens wavefront we describe with ψ. The wavefront passes through both slits simultaneously, producing the interference pattern on the screen. When the photon "is detected" at a specific pixel, what has happened is that the four-dimensional McGucken Sphere has intersected the detector's spatial slice at that specific pixel. The other pixels of the screen — where the photon is not detected — are spatial locations where *this particular* McGucken Sphere does not intersect the slice. The wavefunction did not collapse; the four-dimensional object simply happened to land at one specific pixel as x₄ advanced. From the perspective of an observer at a different pixel (had the photon arrived there instead), it would have looked like the wavefunction collapsed at *that* pixel. There is no privileged collapse event; there is only the geometric fact that a four-dimensional McGucken Sphere intersects each spatial slice at a specific configuration determined by the SO(3)-invariant probability distribution.

The Born rule probabilities |c_k|² govern *which* configuration the McGucken Sphere lands at, and they do so because the squared amplitude is the SO(3)-Haar-weighted geometric measure of the branch's contribution to the spherical expansion. Bigger branches (larger |c_k|²) occupy more of the McGucken Sphere and are more likely to intersect a given observer's spatial slice. There is nothing stochastic about the four-dimensional dynamics — (U) is exact and deterministic. The apparent stochasticity arises from the observer's restricted access to the 3D cross-section. The structural deeper reason this account is forced — and not merely consistent — is the space-operator co-generation theorem of §XIII.10: because $\mathcal{M}_G$ and $D_M$ are co-generated by $dx_4/dt = ic$, there is no categorical room in the framework for a separate dynamical $(R)$ mechanism, and the apparent collapse must be a structural feature of the spatial-slice projection. Proposition XIII.6 establishes this categorical impossibility formally.

---

### V.6 What this means for Schrödinger's cat and Wigner's friend

Two thought experiments dominate the canonical statement of the measurement problem: Schrödinger's cat (1935) and Wigner's friend (1961). Both were proposed as *reductio ad absurdum* arguments — Schrödinger to show that quantum mechanics applied consistently produces "ridiculous cases" of macroscopic superposition, and Wigner to show that quantum mechanics cannot consistently formulate a universal observer-independent description. Each remains a touchstone for any candidate resolution of the measurement problem. The present subsection addresses both directly: what the McGucken dx₄/dt = ic framework's cross-section reading of $R$ (Proposition V.1) means concretely for each thought experiment.

#### V.6.1 Schrödinger's cat

The standard reading of Schrödinger's cat treats the cat as in a superposition of "alive" and "dead" until the box is opened, with the wavefunction $\psi_{\text{cat}} = \alpha|\text{alive}\rangle + \beta|\text{dead}\rangle$ collapsing at observation. Schrödinger himself, in *Die gegenwärtige Situation in der Quantenmechanik* [40, quoted in §XIII.13.11.3], proposed this as an absurdity — he did not believe a cat could really be in such a superposition, and the absurdity was the structural point of the thought experiment.

The McGucken dx₄/dt = ic framework dissolves the apparent paradox concretely through two complementary mechanisms.

**First**, the Compton-frequency decoherence threshold (Proposition VII.1) sets a structural cut between configurations that can sustain superposition long enough to be experimentally relevant and configurations that decohere on timescales below detection thresholds. The Compton frequency of a system of mass $m$ is $\nu_C = mc^2/h$ (the ordinary frequency, in Hz; the angular Compton frequency of Convention I.5.4 is $\omega_C = 2\pi\nu_C = mc^2/\hbar$). For a cat of mass $\sim 5$ kg, $\nu_C \sim 7 \times 10^{50}$ Hz. The cat's rest-mass coupling to $x_4$-flow produces decoherence on timescales orders of magnitude below any conceivable physical detection threshold (cf. §VII.2 for the explicit cross-species ratio $T_{\text{dec},A}/T_{\text{dec},B} = (m_B/m_A)^2$). The cat's pointer states — alive, dead — are einselected by Compton-frequency coupling, *not* by an arbitrary system-environment Hamiltonian as in standard decoherence accounts, but by the cat's own rest mass coupling to the $x_4$-flow that the framework derives as foundational. The cat is in a definite state long before the box is opened. The "superposition" exists only at the level of the *atom* (microscopic, low Compton frequency, decoherence timescale long enough to matter for the radioactive-decay branching).

**Second**, even setting decoherence aside, the four-dimensional state of the system is well-defined throughout (Proposition V.1). The "alive" and "dead" outcomes are not two ontologically simultaneous states of one cat — they are two cross-sections of the same $x_4$-extended wavefront emanating from the radioactive-decay event $p_0$. The atom's $x_4$-wavefront has spherical SO(3)-Haar measure (Proposition III.1), and the observer's spatial slice $\Sigma_t$ at the moment of opening intersects this wavefront in *one* configuration. The probability of intersecting the "decayed" branch versus the "undecayed" branch is given by the spherical measure on the atom's $x_4$-wavefront — exactly the Born-distributed outcomes of the radioactive decay, propagated through the Geiger-counter—hammer—poison chain to the cat's macroscopic state.

Schrödinger's apparent paradox dissolves because the categorical separation it requires — between microscopic quantum and macroscopic classical — is replaced by a *continuous* Compton-frequency mechanism. There is no Heisenberg cut to be drawn arbitrarily between system and apparatus, between atom and cat, between cat and observer. The cut is set by the rest mass, and the rest mass varies continuously across the chain. The atom (Compton frequency $\sim 10^{20}$ Hz, decoherence timescale long enough to permit superposition) is genuinely in a superposition of decayed and undecayed states for the relevant duration. The cat (Compton frequency $\sim 10^{50}$ Hz, decoherence timescale astronomically below any detection threshold) is *not* in a superposition of alive and dead in any operationally meaningful sense — it is in one definite state, with Born-distributed probability of being alive or dead determined by the atom's branching at the moment the chain was triggered.

Schrödinger's reductio is therefore vindicated rather than refuted: he was right that a cat cannot be in a superposition of alive and dead. The McGucken dx₄/dt = ic framework explains *why* — not by adding a stochastic localization term (GRW), not by branching universes (Many-Worlds), not by a guidance equation (Bohmian), and not by an arbitrary system-environment coupling (decoherence), but by deriving the Compton-frequency cut from the same primitive law that derives the Born rule itself.

#### V.6.2 Wigner's friend

Wigner's thought experiment, presented in *Remarks on the Mind-Body Question* [42, quoted in §XIII.13.11.4], goes further. A physicist (Wigner) and a friend both have access to the same quantum system. The friend performs a measurement and obtains a definite result. Wigner, who has not yet asked the friend, describes the joint friend-plus-system state as a superposition. *How can the same physical situation be in superposition for Wigner and definite for the friend?*

In the standard categorical structure of quantum mechanics, this produces an apparent contradiction. If both descriptions are correct, then the state is observer-relative — different observers report different states for the *same* physical situation. If only one description is correct, then standard quantum mechanics has a privileged-observer structure that is foreign to the rest of physics. Wigner himself, in 1961, took this as a reductio of the standard formalism, suggesting that consciousness must play a role in collapse. He later disavowed the consciousness-causes-collapse mechanism, but the structural difficulty he identified remained unresolved.

The McGucken dx₄/dt = ic framework dissolves the friend paradox through four structural features.

**First**, there is one underlying $x_4$-extended state $|\Psi(t)\rangle \in \mathcal{H}$ that includes the full system: the measured object, the friend, the apparatus, and Wigner. Both Wigner and the friend are configurations in $\mathcal{M}_G$ (Theorem XIII.I, the space-operator co-generation theorem); both are subject to $D_M$'s flow; neither has privileged status. There is no observer-relative state — there is a single four-dimensional state, viewed by two observers.

**Second**, what each observer *sees* is the cross-section of this single state at their respective spatial slice. The friend's spatial slice $\Sigma_{t,\text{friend}}$ intersects the wavefront when the friend looks at the apparatus; Wigner's spatial slice $\Sigma_{t,\text{Wigner}}$ intersects it later, when Wigner asks the friend (Proposition V.1). Both readings are correct cross-sections of the same underlying state. The friend's "definite description" and Wigner's "superposition description" are not two competing descriptions of the same 3D-now reality — they are *projections* of one $x_4$-extended state onto different spatial slices.

**Third**, the apparent paradox arises only when one assumes a single privileged 3D-now ontology — the assumption that there is one categorically true state of the universe at each moment, which Wigner and the friend should be reporting on consistently. The McGucken dx₄/dt = ic framework explicitly rejects this assumption. The four-dimensional state is the foundational object; 3D cross-sections are projections of it; different observers project onto different slices and therefore report different cross-sections, *without contradiction*. A 3D object's shadow on a wall and its shadow on a floor can look very different without the object being inconsistent. The friend's "definite outcome" is the shadow on $\Sigma_{t,\text{friend}}$; Wigner's "superposition" is the shadow on $\Sigma_{t,\text{Wigner}}$ before he asks; once Wigner asks, his shadow updates to a definite outcome too. The four-dimensional object never moved.

**Fourth**, the consistency of the two readings is structurally guaranteed by $x_4$-coincidence (Proposition VIII.1; First Law of Nonlocality). When Wigner asks the friend, the friend's outcome is communicated to Wigner not via "collapse propagation" along the U-curve of cosmological time, but via $x_4$-coincidence: Wigner's detection event and the friend's measurement event are points on the same expanding McGucken Sphere from the original quantum measurement source. The two readings agree because they are readings of the same wavefront, with $x_4$-coincidence supplying the structural connection between them. There is no observer-relative inconsistency; there is one wavefront, two cross-sections, one shared $x_4$-coincidence.

The deeper structural point is that Wigner's paradox depends on the standard categorical structure where "definite outcome" and "superposition" are mutually exclusive ontological states of *the same single 3D reality*. In the McGucken dx₄/dt = ic framework, both are projections of one $x_4$-extended state onto different spatial slices. Projections from different slices need not agree pointwise; what is required is that they agree on the common $x_4$-coincidences — and Proposition VIII.1 establishes that they do, by construction. Wigner's reductio dissolves because the categorical structure that makes it a reductio does not exist in the McGucken dx₄/dt = ic framework's category structure (Proposition XIII.6).

#### V.6.3 What both thought experiments share, and what each isolates

Schrödinger's cat and Wigner's friend isolate different aspects of the standard measurement problem. The cat isolates the *quantum-classical cut*: where, and on what physical basis, does macroscopic definiteness emerge from microscopic superposition? The friend isolates the *observer-independence*: how can a definite outcome be a definite outcome regardless of which observer sees it? Standard quantum mechanics struggles with both because (U) and Born are independent inputs whose connection at measurement is not supplied by either of them; the cat exposes the lack of a structural cut, and the friend exposes the lack of observer-independent reality.

The McGucken dx₄/dt = ic framework supplies both structural pieces from the same source. The cut is supplied by Compton-frequency decoherence, derived from rest-mass coupling to $x_4$-flow (Proposition VII.1). Observer-independence is supplied by the four-dimensional state with cross-section projections (Proposition V.1) and $x_4$-coincidence between observer-events (Proposition VIII.1). Both pieces follow as theorems of $dx_4/dt = ic$ via the source-pair $(\mathcal{M}_G, D_M)$, with no additional postulates. The cat is in a definite state because its Compton frequency is enormous; the friend's outcome is observer-independent because the four-dimensional state is observer-independent and the cross-section reading at any spatial slice is unique.

Schrödinger's "subject and object are only one" [43, quoted in §XIII.13.11.3] and Wigner's "the dividing line cannot be eliminated" [42, quoted in §XIII.13.11.4] are, in the McGucken dx₄/dt = ic framework, two readings of the same structural fact: the source-pair $(\mathcal{M}_G, D_M)$ co-generated by $dx_4/dt = ic$, with subject and object as configurations in the same source-space, and the dividing line between them as the spatial-slice projection rather than a categorical division. Both founders of the canonical thought experiments were correct in what they identified; what they lacked was the formal mathematics to make their identifications theorems. The McGucken dx₄/dt = ic framework supplies that mathematics.

---

## V.bis. Fields in the McGucken Framework

Section V established that the wave function $\psi$ is a derived geometric object — the complex amplitude carried by an $x_4$-spherical wavefront, with every aspect of its mathematical form being a theorem of $dx_4/dt = ic$ rather than an interpretive choice on a postulated entity. The structural significance of that result extends naturally to the broader question of what *fields* are in the McGucken dx₄/dt = ic framework.

The present section addresses the question directly. In standard physics, "field" is a polysemous term encompassing at least four structurally distinct kinds of object: classical fields (the electromagnetic field $F_{\mu\nu}$, the metric $g_{\mu\nu}$, hydrodynamic and temperature fields), quantum wave functions treated as fields (the historical Schrödinger reading of $\psi$ as a literal field on configuration space), quantum fields in QFT (operator-valued distributions $\hat{\phi}(x)$ on Fock space), and gauge fields (connections on principal bundles mediating the Standard Model interactions). A complete account of "what is a field?" requires addressing all four senses and explaining how they connect.

The McGucken dx₄/dt = ic framework's account is structurally uniform across the four senses: every kind of field is a *derived* object — a structure carrying values on the McGucken-derived spacetime $\mathcal{M}_{1,3}$ (or its substrate-scale and Fock-space refinements), with the value-space, the dynamics, and the gauge structure descending from the source-tuple $F_M = (\Sigma_M, \mathcal{G}_M, \mathcal{M}_G, D_M, \mathcal{S}_M, \mathcal{A}_M)$ as theorems rather than being postulated independently. This parallels the McGucken account of the wave function in §V.1: the strategic move is *derivation rather than postulation*, with the meaning of each derived object fixed by the derivation that produces it.

The structural unification across the four senses of "field" sits in sharp contrast to standard physics, where each kind of field is postulated as primitive and the connections between them (why electromagnetism is U(1), why the strong force is SU(3), why fermions satisfy Dirac, why gauge fields have curvature equations) are either independent postulates or empirical-input choices. The present section establishes how the four senses of field arise as theorems in the McGucken dx₄/dt = ic framework, contrasts the McGucken account with the seven major prior interpretive programmes plus standard QFT, and identifies which aspects of the field structure are settled in the corpus and which are programmatically in place pending further formalization.

### V.bis.1 Classical fields as cross-section structures of $\mathcal{M}_G$

The deepest structural reading of classical fields in the McGucken dx₄/dt = ic framework is that they are *cross-section structures* on $\mathcal{M}_G$ — smooth assignments of values to each point of the McGucken-derived spacetime $\mathcal{M}_{1,3}$, where the assigned values carry McGucken-derived geometric content. The field is not an independent entity coexisting with spacetime; it is a feature of the spacetime structure that descends from $\mathcal{M}_G$.

For the **electromagnetic field** specifically, the McGucken dx₄/dt = ic framework's account runs through the gauge-bundle derivation of [12, §16.7] together with the McGucken Symmetry [44]. The U(1) gauge structure is a theorem: it descends from the phase-freedom of $\psi$ under the local action $\psi(x) \to e^{i\alpha(x)} \psi(x)$, and this phase freedom is itself a structural feature of $i$ being the perpendicularity marker of $x_4$ in the McGucken Principle. The vector potential $A_\mu$ is the connection one-form on the McGucken-derived U(1) principal bundle; the field strength $F_{\mu\nu} = \partial_\mu A_\nu - \partial_\nu A_\mu$ is the curvature two-form. Maxwell's equations $dF = 0$ and $d\star F = J$ follow from the Bianchi identity (a structural identity of any connection one-form's curvature) plus the Yang-Mills sector $\mathcal{L}_{\rm YM}$ of the McGucken Lagrangian [2]. The electromagnetic field is therefore, in the McGucken dx₄/dt = ic framework, *the curvature of the U(1) connection that descends from the phase-freedom of $x_4$-wavefronts via the McGucken-derived gauge-bundle structure*.

For the **gravitational field**, the structural picture is even cleaner. The metric $g_{\mu\nu}$ on spacetime $\mathcal{M}_{1,3}$ is what the McGucken constraint $\Phi_M = x_4 - ict = 0$ produces when projected onto the spatial-temporal slice — the metric is a derived feature of how $\mathcal{M}_G$'s four-dimensional structure restricts to its constraint locus, with the Lorentzian signature emerging from the imaginary unit $i$ in $dx_4/dt = ic$ converting the Euclidean four-metric into Minkowski signature [3; 12, §16.2]. The Einstein field equations $G_{\mu\nu} = 8\pi G T_{\mu\nu}$ are derived from the Einstein-Hilbert sector $\mathcal{L}_{\rm EH}$ of the McGucken Lagrangian, with the stress-energy tensor $T_{\mu\nu}$ being the source of metric curvature sourced by the $x_4$-extended states whose configurations populate $\mathcal{M}_G$ [2; 3]. The gravitational field is therefore *the curvature of the McGucken-derived spacetime metric, with curvature sourced by stress-energy of $x_4$-extended states* — and crucially, *no graviton is required*, because the metric is not a quantum field but a structural feature of the constraint-projection of $\mathcal{M}_G$ onto $\mathcal{M}_{1,3}$.

The structural unification across classical fields in the McGucken dx₄/dt = ic framework is that *every classical field is the curvature or potential of some structure that descends from $\mathcal{M}_G$ via McGucken-derived bundle/connection machinery*. The bundles are not postulated; the connections are not postulated; the field equations are not postulated. They all descend from the source-tuple via specific theorems whose statements appear in [12, 2, 3, 44] and whose content is the structural derivation of classical-field theory from the single primitive law $dx_4/dt = ic$.

### V.bis.2 The wave function as a complex scalar field on $\mathcal{M}_G$

This sense of "field" was already addressed in §V.1: the wave function $\psi(\mathbf{x}, t)$ is a smooth complex-valued assignment to each point of spacetime, and as such it qualifies as a complex scalar field in the classical-field sense. What §V.1 establishes is that the McGucken-derived wave function is *more* than a field on spacetime alone — the underlying geometric object is the four-dimensional structure $\Psi(\mathbf{x}, x_4)$ on $\mathcal{M}_G$, with the standard 3D wave function being its cross-section reading at the constraint locus $x_4 = ict$.

The historical Schrödinger hope — that quantum mechanics is fundamentally a field theory and $\psi$ is a literal complex field on spacetime, with quantum probabilities being statistical readings of a continuous wave structure — is essentially correct in the McGucken dx₄/dt = ic framework. Schrödinger lacked the additional structural ingredient that the McGucken dx₄/dt = ic framework supplies: the four-dimensional underlying structure of which the 3D wave function is a cross-section. With that ingredient added, the Schrödinger reading becomes precise: $\psi$ is a field, but its foundational existence is on $\mathcal{M}_G$ rather than on $\mathcal{M}_{1,3}$, and what physicists work with as the "3D wave function" is the spatial-slice cross-section of this 4D field.

This is the simplest McGucken-derived field, and it provides the template for understanding the more elaborate quantum fields of QFT (§V.bis.3) as $D_M$-flow structures on multi-particle Fock-space liftings of the basic single-particle wave-function-as-field structure.

### V.bis.3 Quantum fields in QFT as $D_M$-flow on Fock space

This is structurally the deepest of the four senses, and the McGucken dx₄/dt = ic framework's account here connects to what [12, §16.6] establishes about Fock space being downstream in the derivational hierarchy of physical-arena spaces.

A quantum field $\hat{\phi}(x)$ in standard quantum field theory is an operator-valued distribution on spacetime, expandable as

$$\hat{\phi}(x) = \int \frac{d^3k}{(2\pi)^3 \sqrt{2\omega_k}} \left[ \hat{a}_k\, e^{-ik\cdot x} + \hat{a}_k^\dagger\, e^{ik\cdot x} \right]$$

with creation and annihilation operators $\hat{a}_k^\dagger, \hat{a}_k$ acting on Fock space $\mathcal{F}(\mathcal{H})$. In standard QFT, this entire construction is postulated: the Hilbert space is postulated, the Fock-space lifting is postulated, the canonical commutation relations $[\hat{\phi}(x), \hat{\pi}(y)] = i\hbar\,\delta^3(\mathbf{x} - \mathbf{y})$ are postulated, and the equations of motion (Klein-Gordon, Dirac, Maxwell, Yang-Mills) are postulated separately for each field type with structurally-independent Lagrangians.

In the McGucken dx₄/dt = ic framework, every component of the QFT construction is derived as a theorem:

- **The single-particle Hilbert space $\mathcal{H}$** is a theorem (Proposition XIII.1 of the present paper, plus [12, Theorem 12.1]). The Hilbert space is not postulated; it is the structural completion of complex amplitudes on $x_4$-wavefronts under the SO(3)-Haar-measure inner product (Proposition XIII.4).
- **The Fock space $\mathcal{F}(\mathcal{H}) = \bigoplus_n \mathcal{H}^{\otimes_s n}$** for many-particle states is a theorem [12, §16.6]. The symmetric (or antisymmetric) tensor algebra over the single-particle Hilbert space descends from N copies of $\mathcal{M}_G$ joined by McGucken-Sphere structure, with the $x_4$-coincidence connection (Proposition VIII.1 of the present paper) supplying the structural origin of multi-particle entanglement.
- **The creation and annihilation operators $\hat{a}_k^\dagger, \hat{a}_k$** are restrictions of $D_M$'s flow to specific momentum modes — they are theorems via the source-operator's action on Fock-space slots [13]. The "particle-creating" character of $\hat{a}_k^\dagger$ is the structural feature of $D_M$'s flow lifting an N-particle configuration to an (N+1)-particle configuration on the Fock-space hierarchy, with the momentum mode $k$ specifying the McGucken-Sphere wavefront direction.
- **The canonical commutation relations** $[\hat{\phi}(x), \hat{\pi}(y)] = i\hbar\,\delta^3(\mathbf{x} - \mathbf{y})$ are theorems (Proposition XIII.5 of the present paper, plus the two structurally-independent routes of [45]). The canonical $i\hbar$ in $[\hat{q}, \hat{p}] = i\hbar$ is the same $i$ that is the perpendicularity marker of $x_4$ in $dx_4/dt = ic$, and the structure is forced by $D_M$'s commutator action on cross-sections.
- **The equations of motion** for each sector — Klein-Gordon for scalars, Dirac for fermions, Maxwell for U(1), Yang-Mills for non-abelian gauge fields — are derived from the corresponding sector of the McGucken Lagrangian $\mathcal{L}_{\rm McG} = \mathcal{L}_{\rm kin} + \mathcal{L}_{\rm Dirac} + \mathcal{L}_{\rm YM} + \mathcal{L}_{\rm EH}$ [2]. The four-sector decomposition is itself forced — no fewer, no more — by eleven minimal consistency conditions on $dx_4/dt = ic$, per [2, Theorem 1].

A quantum field in the McGucken framework is therefore, structurally, *a momentum-mode decomposition of $D_M$'s flow on Fock space, with the Fock space being the symmetric or antisymmetric tensor algebra over the single-particle Hilbert space derived from $\mathcal{M}_G$, and the field's equation of motion descending from the corresponding sector of the McGucken Lagrangian*. Every component descends from the source-tuple $F_M$. The seemingly disparate field types of standard QFT — bosons and fermions, gauge fields and matter fields, massless and massive — are unified as different sectors of the same source-flow $D_M$ acting on different Fock-space liftings.

### V.bis.4 Gauge fields as connections on McGucken-derived principal bundles

The Standard Model's gauge group $G_{\rm SM} = U(1)_Y \times SU(2)_L \times SU(3)_c$ has, in the McGucken dx₄/dt = ic framework, a structurally explicit derivation route via [44] together with [12, §16.7] and the substrate-scale identifications of [1, Theorem H]. The structural picture, with the gap between *settled* and *programmatically in place* identified explicitly:

**The U(1) gauge structure is settled.** It descends from the phase-freedom of $x_4$-wavefronts: the wave function $\psi$ has the local symmetry $\psi(x) \to e^{i\alpha(x)} \psi(x)$ because $i$ is the perpendicularity marker of $x_4$, and the local nature of the phase freedom forces a connection one-form $A_\mu$ on the U(1) principal bundle. This is the electromagnetic potential, with the field strength $F_{\mu\nu}$ being the curvature two-form. Both the bundle structure and the connection are theorems of [12, §16.7], not postulates.

**The SU(2)_L gauge structure descends programmatically.** The structural route runs through the Cl(1,3) Clifford algebra of the McGucken-Dirac construction [46]: the McGucken-Dirac equation forces a four-component spinor structure decomposing canonically into Weyl components $\psi_L \in S^+$ and $\psi_R \in S^-$, with the $x_4$-reversal $\Theta_{x_4}: x_4 \to -x_4$ acting as charge conjugation $C: \psi_L \leftrightarrow \overline{\psi_R}$. The McGucken-Sphere SO(3) symmetry, acting on the two-component irreducible representation of the even subalgebra Cl(1,3)$^+$ (which is isomorphic to the algebra of complex 2×2 matrices), lifts canonically to an internal SU(2) action on left-handed Weyl doublets. The chirality structure — that SU(2) acts on left-handed components only — descends from the $\Theta_{x_4}$-non-commutativity of the McGucken-Sphere action on Cl(1,3)$^+$ chirality eigenspaces. This route is structurally laid out in [44] but the explicit theorem statement (call it FS-2 in [47]) is research-program-active.

**The SU(3)_c colour gauge structure is the deepest open derivation.** The structural route runs through the substrate-scale identifications of [1, Theorem H], where Planck-volume four-spheres tile the noncommutative four-manifold via the higher Heisenberg commutation relation of [48]. The colour SU(3) is conjecturally the symmetry of how substrate-scale McGucken Spheres pack at the Planck scale, with the three-fold internal structure descending from the three-fold irreducible decomposition of the higher Heisenberg relation. This conjecture (FS-3 in [47]) is genuine open research; the structural route is laid out, but the explicit theorem is not yet written.

**The hypercharge U(1)_Y descends as a structural combination.** The full U(1)_Y of hypercharge descends as a combination of the $x_4$-phase-freedom U(1) (which becomes the McGucken-derived U(1)_em after electroweak symmetry breaking) and a residual internal U(1) emerging from the SU(2)_L × SU(3)_c bundle structure. The Weinberg angle $\theta_W$ would be a structural consequence of the relative McGucken-Sphere-saturation rates of the SU(2) and U(1) sectors at substrate scale (FS-4 in [47]).

**The structural prediction of no GUT.** A specific structural feature distinguishing the McGucken dx₄/dt = ic framework from grand-unified theories (SU(5), SO(10), $E_6$, $E_8$, etc.) is that the gauge group is forced to be *exactly* $U(1)_Y \times SU(2)_L \times SU(3)_c$ — no larger embedding group is structurally necessary. The structural reason: in the McGucken dx₄/dt = ic framework, the gauge group descends from specific geometric features of $\mathcal{M}_G$ and its substrate (Cl(1,3)$^+$ for SU(2), substrate-scale McGucken-Sphere packing for SU(3), $x_4$-phase-freedom for U(1)). There is no geometric feature of the framework that would naturally produce a single embedding group of dimension twelve or larger. GUT gauge groups are mathematically compelling embeddings of $G_{\rm SM}$ but are not *forced* by any deeper geometric principle — and the McGucken dx₄/dt = ic framework, by deriving $G_{\rm SM}$ directly from geometric features, has no structural need to embed it in a larger group. This generates the testable prediction of *no proton decay*: if the framework's no-GUT structure is correct, there is no gauge boson connecting quarks to leptons, and proton decay is forbidden. The current experimental lower bound $\tau_p > 10^{34}$ years is consistent with this prediction and in increasing tension with minimal SU(5).

A gauge field in the McGucken dx₄/dt = ic framework is therefore *a connection on a principal bundle whose Lie-group structure descends from the McGucken Symmetry's internal action on Cl(1,3)$^+$ spinor structure (SU(2)), substrate-scale McGucken-Sphere packing (SU(3)), or $x_4$-phase-freedom (U(1)), with the bundle's base manifold descending from $\mathcal{M}_G$ and the Lie-algebra-valued curvature two-form descending from the corresponding sector of the McGucken Lagrangian*. Connections are not postulated; bundles are not postulated; the gauge group is not postulated. Each piece is a theorem (settled for U(1); programmatically in place for SU(2); open research for SU(3) via the substrate-scale Connes-descent route).

### V.bis.5 Comparison with prior interpretive programmes and standard QFT

The seven major interpretive programmes of quantum mechanics treated in the master comparison table — Copenhagen, Many-Worlds, Bohmian, GRW, Decoherence + einselection, RQM, QBism — each operate within standard QFT for any sufficiently relativistic application. None of them addresses the foundational question of *what fields are* at the level of the present paper's analysis of *what the wave function is* (§V.1). The interpretive programmes accept fields as primitive structural data of QFT and dispute the meaning of the wave function only; the question "what is a quantum field?" is treated as already-answered by the standard QFT formalism, with the field operator $\hat{\phi}(x)$ taken as primitive and the canonical commutation relations and equations of motion postulated together.

Standard quantum field theory itself, taken as a foundational programme rather than as a calculational toolkit, is the closest competitor to the McGucken dx₄/dt = ic framework's account of fields. Its structural commitment is that the field operator $\hat{\phi}(x)$ is primitive, with its locality, its commutation relations, its Lagrangian, its gauge invariances, and its symmetries being either postulates or empirical-input choices. The most rigorous formulation — algebraic QFT [49] — replaces the field operator with the local algebra $\mathcal{A}(\mathcal{O})$ associated to spacetime regions $\mathcal{O}$, and treats locality as a categorical axiom rather than a derived feature. Algebraic QFT gives the most mathematically precise standard-physics account of fields, but as Connes-style noncommutative-geometry analysis [1] establishes, the algebraic-QFT spectral structure is itself a downstream descent image of McGucken Source-Tuple structure via the descent functor $F_{\rm Spec}$. Algebraic QFT is thus, structurally, a Sense-1 categorical equivalence (in the language of §XIII.13.12) — bidirectional in the re-encoding sense, not in the co-generation-from-primitive-law sense — and the McGucken dx₄/dt = ic framework supplies the prior third structure (the primitive law $dx_4/dt = ic$) that standard QFT, including algebraic QFT, lacks.

The field-comparison table:

| Question about fields | Standard QFT | Algebraic QFT | Copenhagen / standard interpretations | **McGucken** |
|---|---|---|---|---|
| Is the field operator $\hat{\phi}(x)$ postulated or derived? | postulated | postulated as local algebra $\mathcal{A}(\mathcal{O})$ | postulated (via standard QFT) | **derived: $D_M$-flow on Fock space** |
| Origin of canonical commutation $[\hat{\phi}, \hat{\pi}] = i\hbar\,\delta^3$ | postulated | postulated (as algebraic relation) | postulated | **theorem: $i$ from perpendicularity, $\hbar$ from $D_M$ commutator (Prop. XIII.5)** |
| Origin of Hilbert space and Fock space | postulated | postulated (GNS construction over algebra) | postulated | **theorem (Prop. XIII.1; [12, §16.5–16.6])** |
| Origin of equations of motion (KG, Dirac, Maxwell, YM) | postulated separately for each field type | postulated as local-algebra structure | postulated | **theorem: four sectors of $\mathcal{L}_{\rm McG}$ forced by 11 conditions [2]** |
| Origin of gauge group $U(1) \times SU(2) \times SU(3)$ | postulated (empirical input) | postulated | postulated (via standard QFT) | **theorem (settled for U(1); programmatic for SU(2), SU(3))** |
| Origin of locality / microcausality | postulated as axiom | postulated as axiom | postulated | **theorem: $x_4$-coincidence light-cone structure (Prop. VIII.1)** |
| Spacetime on which fields live | postulated (Minkowski / curved) | postulated | postulated | **theorem: $\mathcal{M}_{1,3}$ from constraint-projection of $\mathcal{M}_G$ [12, §16.2]** |
| Treatment of gravity | excluded (no graviton in standard QFT) or postulated (perturbative graviton) | excluded or postulated | excluded or postulated | **structural: metric is constraint-projection feature, no graviton needed [3]** |
| Need for renormalization | required (UV divergences) | required (in interacting theories) | required | **substrate-scale cutoff supplied by McGucken-Sphere granularity [1, Theorem H]** |
| Three matter generations | postulated (empirical input) | postulated | postulated | **open research; structurally expected to descend from source-tuple feature [50 programmatic]** |

The pattern is the same as in the wave-function comparison of §V.1: every entry in the McGucken column is a theorem (settled or programmatically in place); every entry in every other column is a postulate or an empirical-input choice or a feature accepted as primitive. The categorical asymmetry is total. The McGucken dx₄/dt = ic framework derives where standard QFT and the interpretive programmes postulate.

### V.bis.6 What is settled and what is open

In intellectual honesty, the McGucken account of fields has different completeness levels for different sectors of the picture. The present subsection identifies these levels explicitly so the reader has a clear map of where the framework is settled, where it is programmatically in place, and where it is genuine open research.

**Settled in the corpus.** The wave function as the McGucken-derived complex amplitude of the $x_4$-wavefront [6, §V.1 of the present paper]. The U(1) gauge structure descending from $x_4$-phase-freedom [12, §16.7]. The Hilbert space and Fock space derivations [12, §16.5–16.6]. The canonical commutation relations and Schrödinger equation [6]. The four-sector decomposition of the McGucken Lagrangian $\mathcal{L}_{\rm McG} = \mathcal{L}_{\rm kin} + \mathcal{L}_{\rm Dirac} + \mathcal{L}_{\rm YM} + \mathcal{L}_{\rm EH}$ [2]. The gravitational field as McGucken-derived metric curvature with no graviton required [3]. The Connes spectral-triple as descent image of the source-tuple via $F_{\rm Spec}$ [1].

**Programmatically in place but with details to be filled in.** The full SU(2)_L × SU(3)_c derivation from the McGucken Symmetry's internal action — the structural derivation route is laid out in [44], but the explicit construction of why SU(2) and SU(3) specifically (and not other Lie groups) descend is research-program-active rather than fully formalized in a single paper, with [47] as the projected dedicated treatment. The exact correspondence between the Chamseddine-Connes-Mukhanov "quanta of geometry" and the McGucken Spheres at substrate scale [1, Theorem H] — this connects fields-on-spacetime to the noncommutative-geometry image of fields, with the descent functor $F_{\rm Spec}$ doing the structural work, but the explicit substrate-scale identifications need further formalization. The empirical-input encoding of the Standard Model parameters (Yukawa couplings, mixing angles, mass spectrum) — the structural framework is present in [2] but the explicit fitting of internal-algebra empirical inputs to observed parameter values is its own program.

**Genuinely open.** A complete derivation of why the matter sector has three generations from the McGucken dx₄/dt = ic framework alone — this is open in standard physics too, but the McGucken dx₄/dt = ic framework would predict that the three-generation structure descends from a specific feature of the source-tuple, and identifying which feature is open work [50]. The full derivation of dark matter and dark energy as McGucken-cosmological consequences [51, 52] is in progress; whether dark matter is a separate field, an artifact of the McGucken-cosmological geometry, or something else entirely is an active research question.

The structural picture is therefore clear in outline and settled in detail for several specific cases, with active research filling in the gaps for full Standard Model and cosmological coverage. The framework's commitment is uniform across the four senses of "field": *every aspect of every field type is ultimately a theorem of $dx_4/dt = ic$*. The work in progress is the explicit derivation of the remaining pieces, with the SU(3) substrate-scale derivation being the deepest open frontier.

### V.bis.7 The McGucken definition of "field"

If pressed for a one-sentence definition that fits the framework: a field in the McGucken dx₄/dt = ic framework is a smooth assignment of values from a McGucken-derived value-space (complex scalars, spinors, vectors, tensors, Lie-algebra elements) to points of $\mathcal{M}_G$ or its constraint-projected spacetime $\mathcal{M}_{1,3}$, with the assignment's dynamics governed by $D_M$'s flow restricted to the relevant sector of the McGucken Lagrangian $\mathcal{L}_{\rm McG} = \mathcal{L}_{\rm kin} + \mathcal{L}_{\rm Dirac} + \mathcal{L}_{\rm YM} + \mathcal{L}_{\rm EH}$ — with the value-space, the dynamics, and the gauge structure all descending from the source-tuple $F_M = (\Sigma_M, \mathcal{G}_M, \mathcal{M}_G, D_M, \mathcal{S}_M, \mathcal{A}_M)$ as theorems rather than being postulated independently.

Compared to the standard "a field is a tensor-valued map from spacetime" definition, the McGucken definition adds the structural content that *what counts as a field, and what dynamics it satisfies, is itself derivable* rather than being a postulated input. This is the same strategic move that the framework makes for the wave function in §V.1: not interpreting a postulated object, but deriving the object so its meaning is fixed by the derivation.

**Definition V.bis.1 (The McGucken field).** *A field $\Phi$ in the McGucken dx₄/dt = ic framework is a section of a fibre bundle $E \to \mathcal{M}_{1,3}$ whose fibre value-space is a McGucken-derived structure (complex scalar, spinor representation of Cl(1,3), vector or tensor representation, Lie-algebra-valued one-form), with the bundle structure descending from $\mathcal{M}_G$ via the universal derivability principle of [12], the field's dynamics governed by $D_M$'s flow restricted to the relevant Lagrangian sector, and the field's gauge symmetries (if any) descending from the McGucken Symmetry's internal action [44] — with each component of the construction being a theorem of $dx_4/dt = ic$ rather than an independent postulate.*

The structural payoff of this definition is that the four senses of "field" — classical, wave-function, QFT-operator, gauge — are unified as different bundle and value-space realizations of the same underlying derivation, rather than being four structurally-independent kinds of object that happen to share the name "field." In the McGucken dx₄/dt = ic framework, a field is what $D_M$'s flow on a McGucken-derived bundle produces, and the apparent diversity of field types in standard physics is a structural feature of which sector of the McGucken Lagrangian governs the flow.

The wave function is what $x_4$'s spherical expansion produces. The classical fields are the curvatures of the bundles that the McGucken Symmetry produces. The quantum fields are the $D_M$-flow on the Fock space that the multi-particle $x_4$-coincidence structure produces. The gauge fields are the connections on the principal bundles that the McGucken Symmetry's internal action produces. Every kind of field descends from the same primitive law, and the McGucken dx₄/dt = ic framework supplies the structural unification that standard physics treats as four distinct subjects.

---

## VI. The Irreversibility of Measurement

### VI.1 The thermodynamic arrow

The irreversibility of measurement is the same irreversibility that characterizes the second law of thermodynamics throughout physics. In the McGucken dx₄/dt = ic framework, both are theorems of x₄'s monotonic advance.

### VI.2 Proposition VI.1 (Measurement irreversibility from x₄-monotonicity)

**Proposition VI.1 (The irreversibility of measurement is the same x₄-monotonicity that grounds the second law).** *The apparent irreversibility of (R) — that once a measurement has been made, the system cannot return to its premeasurement superposition — is a Grade-2 theorem of x₄'s monotonic advance, identical in structural origin to the second law of thermodynamics. No separate stochastic dynamics is required.*

**Proof.** From [7] and [8, §7], the second law of thermodynamics has a dynamical origin in x₄'s monotonic advance: at the initial moment t = 0 of any process, no x₄-advance has occurred and the accessible phase-space volume is minimal; as x₄ advances at rate ic, the accessible phase-space volume grows continuously, driving entropy increase. The arrow of time is the arrow of x₄'s monotonic advance.

A measurement is a specific instance of this general process. Consider the von Neumann measurement scheme of §II.1: prior to the measurement interaction, the system is in a superposition Σ_i c_i |s_i⟩ and the apparatus is in the ready state |A_0⟩. After the measurement interaction at time t > 0, the system-apparatus state is the entangled superposition Σ_i c_i |s_i⟩ ⊗ |A_i⟩, with the apparatus pointer state |A_i⟩ correlated with the system eigenstate |s_i⟩.

The unitary evolution preserves information: the entangled superposition contains the same information as the original superposition plus the apparatus's correlation structure. To "undo" the measurement — to restore the premeasurement superposition — would require reversing the unitary evolution and disentangling the apparatus from the system. This is *in principle* possible (since (U) is reversible) but *practically* impossible: the apparatus has been entangled with the environment via Compton-frequency coupling (Convention I.5.4 and [6, Theorem 22]), and disentangling all the environmental degrees of freedom would require precise control over them — control that x₄'s monotonic advance has dispersed across an exponentially large phase space.

The irreversibility is therefore not a feature of a separate (R) law; it is the same x₄-monotonic dispersion that drives the second law. As x₄ advances, the entangled state spreads through the environmental phase space at rate proportional to the Compton frequencies of the environmental constituents (Theorem 22 of [6]). For a macroscopic apparatus with N ∼ 10²³ environmental degrees of freedom each oscillating at Compton frequencies ω_C ∼ 1.4 × 10²⁴ rad/s for nucleons, the dispersion timescale is Planck-short — far below any observational timescale. The "collapse" appears irreversible because the practical reversibility timescale exceeds the age of the universe by factors involving the entropy of the apparatus.

The structural identification with the second law is precise: both are Grade-2 theorems of dx₄/dt = ic via the same monotonic-advance mechanism. The apparent (R) irreversibility is one consequence of the universal x₄-monotonicity that also produces thermodynamic entropy increase, the cosmological arrow of time, and the radiative arrow [7, 8]. There is one arrow of time, with multiple manifestations. **∎**

### VI.3 Comparison with prior accounts

**Standard quantum mechanics + thermodynamics.** Standard quantum mechanics treats (U) reversibility and (R) irreversibility as a foundational tension, often "resolved" by appealing to thermodynamic-statistical arguments without specifying the underlying mechanism. The McGucken dx₄/dt = ic framework supplies the mechanism: x₄'s monotonic advance, the same mechanism that produces the second law.

**Decoherence accounts (Zurek).** The standard environmental-decoherence account explains irreversibility as information leakage to an environmental phase space too large to track. This is correct as far as it goes but does not specify *why* the environment has the requisite size and structure to produce irreversibility, and does not connect the measurement arrow to other thermodynamic arrows. The McGucken dx₄/dt = ic framework supplies the connection: the environmental phase-space size is set by the Compton-frequency coupling of environmental constituents to x₄'s expansion, and the various arrows of time are unified as manifestations of x₄'s monotonic advance.

**GRW.** The Ghirardi-Rimini-Weber programme adds explicit stochastic terms to (U) to produce (R) directly, with phenomenological parameters for the localization rate. The McGucken dx₄/dt = ic framework requires no additional dynamics: irreversibility emerges from the same (U) plus the geometric structure of x₄'s expansion.

**Past Hypothesis (Albert, Penrose).** The Albert-Penrose Past Hypothesis posits a brute-fact low-entropy initial condition for the universe to ground the thermodynamic arrow. The McGucken dx₄/dt = ic framework replaces this brute fact with a dynamical mechanism [8, §7]: entropy starts low because x₄-advance starts (no phase-space growth has yet occurred at t = 0), and entropy increases because x₄-advance continues. The same mechanism grounds the measurement arrow.

---

## VII. The Preferred Basis Selected by Compton-Frequency Decoherence

### VII.1 The preferred-basis problem

Standard quantum mechanics does not specify a preferred basis. The reduced density matrix ρ_S = Tr_A |Ψ⟩⟨Ψ| of the post-measurement state is diagonal in the eigenbasis of the measured observable, but it is *also* diagonal in any unitary transformation of that basis. Why does the observer see definite outcomes in the eigenbasis of (say) position rather than some superposition basis?

The standard decoherence answer (Zurek, Joos, Zeh) is that the system-environment coupling diagonalizes ρ_S in a specific basis — the *pointer basis* — determined by which observables of the system commute with the system-environment interaction Hamiltonian. The pointer basis is the basis "monitored by the environment," and the preferred basis problem reduces to specifying the environmental coupling.

This shifts the problem rather than solving it: which environmental coupling is the right one? The McGucken dx₄/dt = ic framework supplies a specific physical mechanism — environmental Compton-frequency coupling to x₄ — that fixes the preferred basis from first principles.

### VII.2 Proposition VII.1 (Preferred basis from environmental Compton-frequency decoherence)

**Proposition VII.1 (The preferred basis is selected by environmental Compton-frequency coupling to x₄'s expansion).** *In the McGucken dx₄/dt = ic framework, the preferred basis observed by macroscopic observers is the position basis (and the energy basis for stationary states), and the cut between quantum and classical regimes is the scale at which environmental Compton-frequency coupling to x₄'s expansion produces decoherence faster than coherent dynamics. The cut is specified by a concrete physical mechanism — the Compton frequency of environmental constituents — rather than left arbitrary.*

**Proof.** From Convention I.5.4 (Compton coupling), every massive particle of rest mass m couples to x₄'s expansion at its Compton angular frequency ω_C = mc²/ℏ. For the constituents of a macroscopic environment — nucleons (m_p c²/ℏ ≈ 1.4 × 10²⁴ rad/s), electrons (m_e c²/ℏ ≈ 7.8 × 10²⁰ rad/s), and atomic and molecular systems — the Compton frequencies are extremely high, and the coupling to x₄'s expansion produces extremely rapid phase oscillations.

When a quantum system S interacts with an environmental constituent E, the system's reduced density matrix ρ_S acquires off-diagonal terms that oscillate at the difference frequencies of the system and environment Compton couplings. For macroscopic environments with N ∼ 10²³ constituents, the off-diagonal terms accumulate phase contributions from all N constituents, producing an effective decoherence rate

  Γ_dec ≈ Σ_{i=1}^{N} ω_{C,i} (g_{S,i})² / ℏ

where g_{S,i} is the system-environment coupling strength to constituent i. For typical macroscopic systems, Γ_dec is enormous — far greater than any coherent dynamical timescale — so off-diagonal terms decay to zero on Planck-short timescales relative to the observer's timescale.

The basis in which Γ_dec is *not* enormous — the basis whose elements minimize off-diagonal coupling to environmental Compton oscillations — is the *position basis* (and, for stationary states, the energy basis). Position eigenstates are localized in space and have well-defined spatial relations to environmental constituents at each point of space; their off-diagonal couplings are the smallest possible. This is the structural reason why macroscopic observers see definite spatial configurations and definite energies, but never superpositions of spatial configurations or energies.

The cut between quantum and classical regimes is therefore specified by a concrete physical scale: the scale at which the system's coherent dynamical timescale T_coh exceeds the Compton-frequency decoherence timescale T_dec = 1/Γ_dec. For microscopic systems (e.g., a single atom), T_coh ≪ T_dec, so quantum behavior is observable. For macroscopic systems (e.g., a brick), T_coh ≫ T_dec, so classical behavior dominates. The crossover scale is determined by the physical sizes and Compton couplings — no arbitrary cut is required.

The Compton-frequency decoherence mechanism makes a specific empirical prediction (Theorem 22 of [6]): the cross-species ratio of decoherence times for different masses is

  T_{dec,A} / T_{dec,B} = (m_B / m_A)² = (ω_{C,B} / ω_{C,A})²,

where m_i is the rest mass and ω_{C,i} = m_i c² / ℏ is the Compton angular frequency of species i. The mass-squared scaling reflects the structural fact that Γ_dec is proportional to ω_C² in the McGucken dx₄/dt = ic framework, in contrast to thermal decoherence's 1/m scaling. The prediction is testable in cold-atom systems at ultra-low temperatures, where thermal effects are suppressed and Compton-frequency coupling becomes the dominant decoherence channel. **∎**

### VII.3 Comparison with standard decoherence

The Zurek/Joos/Zeh decoherence programme correctly identifies that environmental coupling produces apparent classicality, but does not specify *which* environmental coupling is the foundational one. Different system-environment couplings produce different pointer bases; the framework requires additional input to fix the coupling.

The McGucken dx₄/dt = ic framework fixes the coupling from first principles: every massive constituent of every environment couples to x₄'s expansion at its Compton frequency, and the position basis is the basis that minimizes this coupling for spatially-localized environmental constituents. The preferred basis is therefore *forced* by the geometric structure of x₄'s expansion, not selected by phenomenological choice of system-environment Hamiltonian.

This is a substantive advance over standard decoherence: where the standard programme has free parameters (the system-environment coupling), the McGucken dx₄/dt = ic framework has a specific mechanism (Compton-frequency coupling) that fixes the preferred basis from first principles. The cross-species mass-independence test (Theorem 22 of [6]) provides an empirical discriminator between the two accounts.

---

## VIII. Quantum Nonlocality from x₄'s Spherical Expansion

### VIII.1 The Bell phenomenon and the standard puzzle

Bell's theorem [24] and the CHSH inequality [25] establish that quantum correlations cannot be reproduced by any local hidden-variable theory. Aspect's experiments [53; 54] confirmed quantum nonlocality up to the Tsirelson bound 2√2 [26], and the loophole-free experiments of [55; 56; 57] closed the remaining locality and detection loopholes.

The standard formalism reports the violation and proves the no-signalling theorem (entangled measurements cannot transmit information faster than light), but supplies no geometric mechanism for how distant entangled particles maintain correlations consistent with relativistic causality. This is the (P5) sub-problem of §II.2.

### VIII.2 Proposition VIII.1 (Nonlocality from six-sense null-surface identity)

**Proposition VIII.1 (Quantum nonlocality is the geometric consequence of x₄-mediated correlation through the six-sense null-surface identity of the McGucken Sphere).** *Two entangled particles created at a common spacetime event E share six-sense null-surface identity with respect to E, with the identity preserved along subsequent null-geodesic propagation. The Bell-violating correlations between the particles are not faster-than-light spatial signaling but the geometric expression of this preserved shared identity, with the spacelike separation of the spatial cross-sections leaving the x₄-coupled state coherent. The First Law of Nonlocality — all nonlocality begins in locality — supplies the structural account.*

**Proof.** From [28, §II.4] and Convention I.5.6, two distinct points p, q on the same McGucken Sphere centered on a common emission event E share geometric identity in six independent mathematical senses with respect to E: foliation theory (both on the same leaf of the null-cone foliation), level sets (both at the same metric distance cτ from E), caustics/Huygens (both on the same wavefront from E), contact geometry (both on the same Legendrian section), conformal/inversive (both invariant under the same Möbius pencil structure), and null-hypersurface (both on the same spacelike cross-section of the future light cone of E).

The corollary established in [28, §II.4]: **the six-sense identity is preserved under null-geodesic propagation**. If p and q share six-sense identity with respect to E, and if their null geodesics from E are continued forward to new points p′, q′, then p′ and q′ still share the same six-sense identity structure with respect to E. The reason: null geodesics are precisely the trajectories that preserve null-hypersurface membership, and each of the six senses is a property of pairs of points on null hypersurfaces from a common emission event.

A pair of entangled particles is created at a common spacetime event E (e.g., a photon-pair source, a parametric down-conversion crystal, an atomic decay). The two particles propagate along null or near-null worldlines from E. By the six-sense corollary, they retain six-sense identity with respect to E throughout their propagation, even as their spatial separation increases.

When the two particles are measured at spacelike-separated detectors A and B at time t after the emission event, the measurement outcomes correlate because the particles are *the same object* with respect to E in six independent geometric senses. The correlations are not the result of faster-than-light signaling between A and B at the time of measurement; they are the result of the shared geometric identity that has persisted from the emission event onward. There is no faster-than-light signal because there is no signal at all — the correlation is a structural feature of the four-dimensional geometry of the McGucken Sphere from E.

The CHSH violation up to 2√2 is the quantitative expression of this shared geometric identity. By [6, Theorem 13] (CHSH and Tsirelson bound), the bound 2√2 is the maximum CHSH score achievable through SO(3) Haar-measure averages on the spherical symmetry of x₄'s expansion. The Tsirelson bound is therefore a Grade-2 theorem of dx₄/dt = ic, not a separate quantum postulate.

The First Law of Nonlocality [9]: all nonlocality begins in locality. Two particles are nonlocally correlated *because* they originated locally at a common spacetime event. There is no nonlocality without a shared local origin. The framework predicts no "spooky action at a distance" between particles with no shared causal past — and standard quantum mechanics, conformingly, predicts no Bell violations between such particles. The First Law unifies the empirical fact (only entangled pairs violate CHSH) with the geometric mechanism (only pairs with shared local origin share six-sense identity).

The mediated case — entanglement swapping and quantum teleportation [58] — extends the structure: each locally-created entangled pair carries its own McGucken Sphere from its own local origin, and entanglement is transferred at the local intersection of those spheres. The resulting correlations trace through a chain of intersecting McGucken Spheres back to local creation events, in accord with the First Law. **∎**

### VIII.3 Why this is geometrically distinct from prior accounts

The McGucken account of nonlocality is structurally distinct from the four prior approaches:

**Copenhagen.** Treats nonlocality as a feature of the wavefunction's holistic character, with no geometric mechanism. The McGucken dx₄/dt = ic framework supplies the mechanism: six-sense identity preserved along null geodesics.

**Bohmian mechanics.** Provides a nonlocal hidden-variable account: the guidance equation depends on the global wavefunction, producing nonlocal influences on hidden particle positions. The McGucken dx₄/dt = ic framework requires no hidden variables; the nonlocality is a structural feature of the four-dimensional state's projection onto spatial slices.

**Many-Worlds.** Treats correlations as preserved across branches by the unitary evolution; no geometric mechanism is given for the correlations themselves. The McGucken dx₄/dt = ic framework supplies the mechanism: shared six-sense identity at emission, preserved along propagation.

**Relational Quantum Mechanics.** Treats correlations as relational features of the wavefunction across observers. The McGucken dx₄/dt = ic framework treats correlations as objective features of the four-dimensional geometry, observer-independent.

**The structural payoff.** The McGucken dx₄/dt = ic framework is the only framework that supplies a *geometric mechanism* for nonlocality consistent with (i) relativistic causality (no faster-than-light signaling), (ii) the Tsirelson bound (the specific quantitative limit on CHSH violations), and (iii) the First Law of Nonlocality (the empirical fact that only entangled pairs with shared local origin exhibit Bell violations). All three are theorems of dx₄/dt = ic.

---

## IX. The Absence of a Separate (R) Law as a Theorem

### IX.1 Proposition IX.1 (No separate (R) law required)

**Proposition IX.1 (The absence of a separate (R) law is a theorem, not an interpretive choice).** *In the McGucken dx₄/dt = ic framework, the apparent reduction (R) at measurement is the cumulative geometric content of four theorems: Proposition III.1 (Born rule from squared-amplitude geometry), Proposition IV.1 (superposition as geometric overlap of McGucken-Sphere wavefronts), Proposition V.1 (apparent collapse as 3D cross-section reading), and Proposition VI.1 (irreversibility from x₄-monotonicity). Together, these reduce (R) to a structural consequence of (U) plus dx₄/dt = ic. No separate (R) postulate is required, and the standard "(U) + (R)" axiomatic structure of quantum mechanics is replaced by "(U) + dx₄/dt = ic" with (R) emerging as a derived appearance.*

**Proof.** The proof is a direct combination of Propositions III.1, IV.1, V.1, and VI.1.

By Proposition IV.1, the superposition principle (SP) is itself a Grade-1 theorem of dx₄/dt = ic via the geometric overlap of McGucken-Sphere wavefronts. Multiple wavefronts can coexist at a common spacetime point because x₄'s uniform advance does not select between source events; the Hilbert-space linearity of (Q1) is a derived structural feature, not a foundational postulate.

By Proposition V.1, the apparent collapse |Ψ(t)⟩ → |s_k⟩ ⊗ |A_k⟩ ⊗ |E_k⟩ observed by an observer at spatial location x_obs is the algebraic content of the projection π_{x_obs} |Ψ(t)⟩, with |Ψ(t)⟩ the unitarily evolved four-dimensional state. The unitary evolution is exact; the apparent collapse is the observer's restricted access to the 3D cross-section.

By Proposition III.1, the probability that the observer's local cross-section intersects branch k is P(k) = |c_k|², the Born rule. The probability is a Grade-2 theorem of the SO(3) Haar measure on the spherically-symmetric expansion of x₄.

By Proposition VI.1, the apparent irreversibility — that the observer cannot return the system to its premeasurement superposition — is the same x₄-monotonic advance that grounds the second law. The reversibility timescale exceeds the age of the universe for macroscopic apparatus, making the appearance of irreversibility practically unbreakable.

The four propositions together account for all four sub-problems of the standard measurement problem (§II.2), supplemented by the additional sub-problem of where superposition itself comes from:

* (P0) The superposition problem (where does (SP) come from?): solved by Proposition IV.1.
* (P1) The probability problem: solved by Proposition III.1.
* (P2) The collapse problem: solved by Proposition V.1.
* (P3) The preferred-basis problem: solved by Proposition VII.1.
* (P4) The irreversibility problem: solved by Proposition VI.1.

And the fifth sub-problem (P5, the nonlocality problem) is solved by Proposition VIII.1.

The standard quantum mechanics axiomatic system "(U) + (R)" is therefore replaced in the McGucken framework by "(U) + dx₄/dt = ic," with (R) emerging as a derived appearance from the combination of (U) and the geometric structure of x₄'s expansion. The axiomatic burden is reduced: where standard quantum mechanics requires two dynamical laws, the McGucken dx₄/dt = ic framework requires one dynamical law (U) and one geometric principle (dx₄/dt = ic). **∎**

### IX.2 The structural significance

The reduction of (U) + (R) to (U) + dx₄/dt = ic is the central structural achievement of the McGucken account of the measurement problem. The reduction is not merely cosmetic. It accomplishes four substantive simplifications:

**First**, it removes (R) from the foundational base of quantum mechanics. The standard axiomatic system has two dynamical laws; the McGucken dx₄/dt = ic framework has one.

**Second**, it derives the Born rule from a single foundational principle. No prior framework — Copenhagen, Many-Worlds, Bohmian, GRW, decoherence, RQM, QBism — derives Born from a single underlying source. The McGucken dx₄/dt = ic framework does.

**Third**, it supplies a geometric account of nonlocality consistent with relativistic causality. Bell violations and the Tsirelson bound are theorems of dx₄/dt = ic via the six-sense null-surface identity of the McGucken Sphere.

**Fourth**, it specifies the preferred basis from a concrete physical mechanism (Compton-frequency coupling), not from an arbitrary choice of system-environment Hamiltonian.

The McGucken dx₄/dt = ic framework is therefore the *only* quantum framework that solves all five sub-problems (P1)–(P5) of the measurement problem from a single foundational principle, with no auxiliary postulates and no modifications of (U).

The structural deeper reason this is uniquely possible — and why no other framework can match it — is the space-operator co-generation theorem of §XIII.10 (Theorem XIII.I). Because $\mathcal{M}_G$ and $D_M$ are co-generated by $dx_4/dt = ic$ as a single source-pair, the McGucken framework's category structure differs from every prior framework at the foundational level. Proposition XIII.6 (§XIII.12) establishes the categorical impossibility of a separate collapse mechanism: any putative dynamical mechanism for $(R)$ would have to be (a) a new space, (b) a new operator, or (c) a new principle — and the universal derivability principles of [12] and [13] together with the inverse derivability of the co-generation theorem rule out all three. The absence of $(R)$ is therefore not a feature of the present formalism that one could imagine adding back; it is a *categorical feature* of the McGucken dx₄/dt = ic framework. This is the deepest structural fact behind the dissolution of the measurement problem.

---

## X. The Black Hole Information Paradox: Unitarity as a Theorem of x₄'s Smoothness

The measurement problem and the black hole information paradox are typically treated as separate foundational problems of physics. The measurement problem concerns the apparent incompatibility of unitary evolution and stochastic reduction at measurement; the information paradox concerns the apparent destruction of information when a black hole evaporates by Hawking radiation. The standard literature treats these as distinct problems with distinct resolutions: the measurement problem is the province of quantum-mechanical interpretation, while the information paradox is the province of quantum-gravity research.

The McGucken dx₄/dt = ic framework reveals that they are the *same problem* — both arise from treating quantum mechanics and general relativity as separately-postulated theories whose joint consistency must be checked at each interface (the measurement apparatus, the event horizon). In the McGucken framework, both theories are theorems of dx₄/dt = ic, and their joint consistency is automatic. The mechanism that resolves the measurement problem (the geometric structure of x₄'s spherical expansion projected onto 3D cross-sections, with the six-sense null-surface identity preserving correlations across spatial separation) is the same mechanism that resolves the information paradox.

This section establishes the resolution formally through five Propositions: **Proposition X.1** (information preservation as a theorem of x₄'s smoothness); **Proposition X.2** (unitarity is derived in the McGucken dx₄/dt = ic framework, not postulated); **Proposition X.3** (the Page curve as a theorem of x₄-coincidence redistribution during evaporation); **Proposition X.4** (the structural identification of the measurement problem and the information paradox); **Proposition X.5** (the McGucken dx₄/dt = ic framework is the only framework that derives unitarity itself rather than postulating it). The section closes (§X.7) with a comparative analysis against the four major prior resolutions — Susskind/'t Hooft complementarity, AdS/CFT-based unitarity, replica wormholes / Penington-Shenker-Stanford-Yang, and Hawking's 2015 soft-hair proposal — establishing that each prior resolution is correct as far as it goes but that the McGucken dx₄/dt = ic framework supplies the geometric foundation that unifies all four.

### X.1 The standard paradox

In 1974–1975, Hawking [59; 60] established by a semiclassical calculation in curved spacetime that black holes radiate thermal particles at the temperature T_H = ℏκ/(2πck_B), where κ is the surface gravity at the horizon. The radiation is exactly thermal in the original calculation, with a spectrum independent of the matter that formed the black hole. Combined with the Bekenstein-Hawking entropy formula S_BH = k_Bc³A/(4Gℏ), Hawking concluded that black holes have well-defined thermodynamic properties and that the radiation carries away mass-energy at a rate that, integrated over time, allows the black hole to fully evaporate.

In 1976, Hawking drew the sharp foundational conclusion [61]: if the radiation is exactly thermal and the black hole evaporates completely, then the information about the matter that formed the black hole is lost. This conflicts with the unitarity of quantum-mechanical evolution: a unitary process cannot map a pure state (the initial matter configuration) to a mixed state (the thermal radiation). Either quantum mechanics is non-unitary in the presence of black holes, or general relativity must be modified, or there must be subtle correlations in the radiation that preserve information beyond the thermal calculation.

The paradox can be sharpened in the form of the **Page curve** [62]. Consider a black hole that forms by the gravitational collapse of matter in a pure quantum state, then evaporates by Hawking radiation. The von Neumann entropy of the radiation, treated as a subsystem of the universe, satisfies the following constraints:

* If the evaporation is unitary, the radiation entropy must rise from zero (initially no radiation), reach a maximum at the **Page time** t_P (when half the black hole's initial entropy has been radiated), and then decrease back to zero (when the black hole has fully evaporated and the radiation is again in a pure state).
* If Hawking's original calculation is correct (exact thermal radiation), the radiation entropy rises monotonically to S_BH (the initial Bekenstein-Hawking entropy) and stays there. There is no decrease at the Page time, because the radiation is uncorrelated thermal noise.

The Page curve — entropy rising and then falling — is the empirical signature of unitarity in black-hole evaporation. The Hawking-1976 calculation produces a monotonically rising curve. The challenge is to reconcile the two: either the Hawking calculation must be corrected to produce the Page curve, or unitarity must be abandoned.

The McGucken dx₄/dt = ic framework corrects the Hawking calculation. The thermal spectrum is the leading-order result of a calculation that ignores the x₄-coincidences between interior and exterior modes; when these coincidences are taken into account, the corrected spectrum produces the Page curve as a theorem.

### X.2 Proposition X.1 (Information preservation as a theorem of x₄'s smoothness)

**Proposition X.1 (Information is never destroyed in the McGucken dx₄/dt = ic framework).** *In the McGucken dx₄/dt = ic framework, the total information content of any closed physical system is preserved under all dynamical evolution. The preservation is a Grade-1 theorem of the smoothness and Lorentz-covariance of x₄'s expansion, with no separate unitarity postulate required.*

**Proof.** The proof has three steps.

**Step 1: x₄'s expansion is smooth and Lorentz-covariant.** By Convention I.5.2 and the foundational arguments of [30, 6], dx₄/dt = ic is a smooth, Lorentz-covariant statement: the rate of x₄-advance is constant (= c in magnitude) at every spacetime event, the direction of advance is the imaginary axis (perpendicularity marker i), and the statement holds in the same form in every inertial frame (Lorentz-covariance follows from x₄ = ict and the standard transformation properties of complex spacetime coordinates).

Smoothness of x₄'s expansion means that there are no discontinuities in dx₄/dt anywhere on the spacetime manifold M. The expansion proceeds at rate ic from every event, including events inside black hole horizons, including events at the moment of horizon crossing, including events during the final stages of black-hole evaporation. There is no privileged region of spacetime where dx₄/dt fails to be ic.

**Step 2: Smoothness of x₄ implies unitarity of dynamical evolution.** The dynamical evolution of any quantum state |Ψ(t)⟩ in the McGucken dx₄/dt = ic framework is governed by the Schrödinger equation iℏ ∂_t|Ψ⟩ = Ĥ|Ψ⟩, which is itself a Grade-2 theorem of dx₄/dt = ic (Theorem 7 of [6]; Q4 in the structural reduction of §XII.8). The Schrödinger equation generates unitary evolution: |Ψ(t)⟩ = U(t, t₀)|Ψ(t₀)⟩ with U(t, t₀) = exp(−iĤ(t − t₀)/ℏ) a unitary operator on the Hilbert space.

The unitarity of U(t, t₀) is not an independent postulate but a direct consequence of the Hermiticity of Ĥ, which in turn is a consequence of the real-valuedness of energy eigenvalues, which is a consequence of the smoothness of x₄'s expansion (since energy is the generator of x₄-translations via Stone's theorem [6, Theorem 10], and a discontinuity in x₄'s expansion would manifest as a non-Hermitian contribution to Ĥ).

The unitary evolution U(t, t₀) preserves the inner product ⟨Ψ(t)|Ψ(t)⟩ = ⟨Ψ(t₀)|Ψ(t₀)⟩ = 1 and, more generally, all transition amplitudes ⟨Φ(t)|Ψ(t)⟩ = ⟨Φ(t₀)|Ψ(t₀)⟩. The von Neumann entropy of any pure state remains zero throughout the evolution; the entropy of any mixed state ρ(t) = U ρ(t₀) U† is preserved at S = −Tr(ρ log ρ).

**Step 3: Information preservation follows from unitarity.** The total information content of a quantum state |Ψ⟩ is encoded in the state vector (for pure states) or in the density matrix ρ (for mixed states). Unitarity preserves the state vector (up to phase) and preserves the density matrix (under the conjugation ρ → UρU†). The total information content is therefore conserved under dynamical evolution.

For a closed system — by definition, a system that does not exchange energy or particles with its environment — the unitary evolution is exact, and information is exactly preserved. For an open system (a system that exchanges energy or particles with its environment), the apparent loss of information from the system to the environment is not a destruction of information but a redistribution: the total information of the (system + environment) closed system is preserved, with the appearance of information loss from the system alone resulting from the observer's restricted access to the system's degrees of freedom.

The three steps together establish that information is never destroyed in the McGucken dx₄/dt = ic framework: the smoothness of x₄'s expansion forces the Hermiticity of Ĥ, which forces the unitarity of U, which forces the preservation of all information content. **∎**

### X.3 Proposition X.2 (Unitarity is derived, not postulated)

**Proposition X.2 (Unitarity is a Grade-2 theorem of dx₄/dt = ic, not a foundational postulate).** *In standard quantum mechanics, unitarity is the structural feature that distinguishes quantum-mechanical evolution from generic dynamics; it is taken as a foundational commitment of the formalism. In the McGucken dx₄/dt = ic framework, unitarity is derived from the smoothness and Lorentz-covariance of x₄'s expansion, with no independent axiomatic content. The derivation proceeds in three stages: the smoothness of x₄'s expansion forces the Hermiticity of the energy operator Ĥ; the Hermiticity of Ĥ forces the unitarity of the evolution operator U(t, t₀) = exp(−iĤ(t − t₀)/ℏ); the unitarity of U forces the preservation of all transition amplitudes and all information content.*

**Proof.** The three stages are established as follows.

**Stage 1: Smoothness of x₄ forces Hermiticity of Ĥ.** By Stone's theorem applied to x₄-translations [6, Theorem 10], the energy operator Ĥ is the generator of one-parameter unitary evolution along x₄ via U(t) = exp(−iĤt/ℏ). For U to be unitary, Ĥ must be Hermitian (self-adjoint). The Hermiticity of Ĥ is equivalent to the real-valuedness of energy eigenvalues.

The real-valuedness of energy eigenvalues follows from the smoothness of x₄'s expansion: energy eigenstates are stationary configurations whose phase advances at rate −iEt/ℏ along x₄, and the smoothness of x₄'s expansion at rate ic forces this phase advance to be along the same imaginary axis (the perpendicularity marker i in x₄ = ict). A discontinuity in x₄'s expansion would manifest as a complex-valued energy eigenvalue with a non-zero imaginary part, corresponding to non-unitary growth or decay of the eigenstate's amplitude. Smoothness of x₄ rules this out.

**Stage 2: Hermiticity of Ĥ forces unitarity of U.** This is a standard result: for any Hermitian operator Ĥ, the operator U(t) = exp(−iĤt/ℏ) is unitary, satisfying U†U = UU† = I. The proof is direct: U†(t) = exp(+iĤt/ℏ) (since Ĥ is Hermitian), so U†U = exp(+iĤt/ℏ) exp(−iĤt/ℏ) = I.

**Stage 3: Unitarity of U forces preservation of information.** This is established in Step 3 of Proposition X.1's proof.

The chain smoothness → Hermiticity → unitarity → information preservation establishes that unitarity is not a foundational commitment of the McGucken dx₄/dt = ic framework but a derived consequence of the smoothness of x₄'s expansion. **∎**

#### Remark X.1 (The structural status of unitarity)

In standard quantum mechanics, unitarity is sometimes treated as foundational and sometimes treated as a consequence of the Hilbert-space framework plus the Schrödinger equation. The McGucken dx₄/dt = ic framework reveals that *both* of these treatments take unitarity as a primitive at some level: standard quantum mechanics either postulates it directly or postulates the framework (Hilbert space, Hermitian operators, Schrödinger equation) from which it follows. The McGucken dx₄/dt = ic framework instead derives unitarity from the smoothness of x₄'s expansion, with the Hilbert space and Schrödinger equation themselves derived (Propositions XI.1 and Theorem 7 of [6]).

This is the deepest structural reduction in the framework: not only the foundational postulates of quantum mechanics (Q1–Q6) but the *unitarity* that connects them to information preservation is moved from the postulate column to the theorem column. What remains in the postulate column is exactly one geometric statement: dx₄/dt = ic.

### X.4 Proposition X.3 (The Page curve as a theorem of x₄-coincidence redistribution)

**Proposition X.3 (The Page curve is a Grade-2 theorem of x₄-coincidence redistribution during black-hole evaporation).** *Consider a black hole that forms by the gravitational collapse of matter in a pure quantum state and evaporates completely by Hawking radiation. The von Neumann entropy of the Hawking radiation, treated as a subsystem of the universe, satisfies the Page curve: rising from zero at the start of evaporation, reaching a maximum at the Page time t_P (when half the initial Bekenstein-Hawking entropy has been radiated), and decreasing back to zero when the black hole has fully evaporated. The Page curve is forced by the redistribution of x₄-coincidences from interior-exterior pairs (during the first half of evaporation) to exterior-exterior correlations (during the second half).*

**Proof.** The proof proceeds in four phases corresponding to the four phases of the evaporation process.

**Phase 1: Initial state (t = 0, no Hawking radiation emitted).** The black hole has just formed by gravitational collapse of matter in a pure quantum state |Ψ_matter⟩. The initial Bekenstein-Hawking entropy is S_BH(0) = k_Bc³A_0/(4Gℏ), where A_0 is the initial horizon area. No Hawking radiation has been emitted; the radiation subsystem is the vacuum with S_rad(0) = 0.

The matter information is encoded in the x₄-coordinates of the infalling particles at the moment of horizon crossing. By [28, §II.4] and Convention I.5.6 (six-sense null-surface identity), each infalling particle's x₄-coordinate at horizon crossing is preserved as a six-sense identity feature relative to the black-hole formation event.

**Phase 2: First half of evaporation (0 < t < t_P, S_rad rising).** Hawking pairs are continuously created at the horizon. Each pair consists of an interior member (which falls into the region r < r_s where x₄'s outward advance is arrested) and an exterior member (which escapes to infinity as Hawking radiation). By the six-sense corollary of Convention I.5.6, the two members share x₄-coincidence at the moment of creation: they are on the same McGucken Sphere centered on the horizon-crossing event, with the same x₄-coordinate.

The exterior member's x₄-coordinate is preserved along its null-geodesic propagation to infinity (six-sense null-surface identity preservation, [28, §II.4 corollary]). The interior member's x₄-coordinate is also preserved, even though the interior member is causally disconnected from the exterior in the three spatial dimensions (the horizon prevents spatial communication). The x₄-coincidence between the two members is therefore maintained as long as both exist.

The von Neumann entropy of the radiation subsystem rises during Phase 2 because each new Hawking pair adds a new interior-exterior x₄-coincidence to the bookkeeping. The radiation, considered alone, is a mixed state because each exterior Hawking quantum is entangled with an interior partner that the radiation subsystem does not include. The entropy growth follows the leading-order Hawking calculation (which is exact in this regime, before exterior-exterior correlations become significant).

**Phase 3: Page time (t = t_P).** At the Page time, exactly half of the initial Bekenstein-Hawking entropy has been radiated: S_rad(t_P) = S_BH(0)/2. This is the maximum of the Page curve. The remaining black hole has Bekenstein-Hawking entropy S_BH(t_P) = S_BH(0)/2 also.

The structural reason for the Page-time maximum: at this moment, the number of interior-exterior x₄-coincidences (which contribute to S_rad) is exactly equal to the number of x₄-stationary modes remaining on the horizon (which contribute to S_BH of the remaining black hole). For t > t_P, additional x₄-coincidences must come from somewhere: since the horizon's x₄-stationary mode count is decreasing (the horizon area is shrinking), the new coincidences must form between Hawking quanta already in the exterior — that is, *exterior-exterior correlations*.

**Phase 4: Second half of evaporation (t_P < t < t_final, S_rad decreasing).** As the black hole continues to shrink, its remaining x₄-stationary modes are exhausted faster than new Hawking pairs are created. The new Hawking pairs are no longer providing fresh interior-exterior coincidences (because the interior horizon is shrinking too fast); instead, they are providing fresh exterior-exterior correlations among already-emitted Hawking quanta.

The von Neumann entropy of the radiation subsystem decreases during Phase 4 because the exterior-exterior correlations correspond to internal entanglement *within* the radiation subsystem rather than entanglement *with* an external interior partner. The radiation subsystem is becoming more correlated with itself rather than with the (vanishing) interior, so its entropy is decreasing.

**Final state (t = t_final, black hole fully evaporated).** When the black hole has fully evaporated, all x₄-coincidences are exterior-exterior. The radiation subsystem is now in a pure state, with all the original matter information encoded in the precise pattern of exterior-exterior correlations among the Hawking quanta. S_rad(t_final) = 0.

The four-phase analysis traces the Page curve directly: rising in Phase 2 from S_rad(0) = 0 to S_rad(t_P) = S_BH(0)/2, then decreasing in Phase 4 from S_rad(t_P) = S_BH(0)/2 to S_rad(t_final) = 0. The curve's qualitative shape (rise and fall) is forced by the redistribution of x₄-coincidences from interior-exterior pairs to exterior-exterior correlations as the horizon shrinks. The quantitative details (slope of rise, location of Page time, slope of fall) are determined by the time-dependence of A(t) under Hawking evaporation. **∎**

#### Remark X.2 (The Page curve as a falsifiable prediction)

The McGucken dx₄/dt = ic framework's prediction of the Page curve is not merely a consistency check — it is a quantitatively specific theorem. The location of the Page time t_P is determined by the time-dependence of the horizon area A(t), with t_P satisfying ∫_0^{t_P} (dS_rad/dt) dt = S_BH(0)/2. For an astrophysical black hole of initial mass M_0, using S_BH ∝ M² and t_evap ∝ M_0³ the half-entropy point is M_P = M_0/√2, so this gives t_P = [1 − 2^{−3/2}] t_evap ≈ 0.65 · t_evap, where t_evap is the total evaporation time.

For a stellar-mass black hole (M_0 ≈ 1 M_⊙), t_evap ≈ 2 × 10^{67} years — far longer than the age of the universe — so direct empirical confirmation of the Page curve is currently impossible. However, the framework's prediction agrees quantitatively with the recent quantum-extremal-surface calculations [63; 64] that derived the Page curve from quantum-information theory in AdS/CFT. The agreement is structurally significant: both calculations identify the Page time with the moment when the radiation subsystem's entropy equals the remaining black-hole entropy, and both attribute the curve's shape to a redistribution of correlations during evaporation. The McGucken dx₄/dt = ic framework supplies the *geometric mechanism* (x₄-coincidence redistribution) that the quantum-extremal-surface approach captures algebraically through replica wormholes (§X.7.3 below).

### X.5 Proposition X.4 (The structural identification of the measurement problem and the information paradox)

**Proposition X.4 (The measurement problem and the black hole information paradox are the same problem at different scales).** *Both arise from the apparent restriction of an observer's access to the four-dimensional state of a system: the measurement problem from the observer's restricted access to the 3D spatial cross-section of a quantum state, the information paradox from the observer's restricted access to the interior of a black-hole horizon. Both are resolved by the same geometric mechanism: x₄-coincidences and the six-sense null-surface identity preserve correlations across the apparent boundary, with the appearance of information loss arising from restricted access to the full four-dimensional structure.*

**Proof.** We establish the structural identification in two parts.

**Part 1: The measurement problem is restricted access to the 3D cross-section of a 4D state.** By Proposition V.1, the apparent collapse of a wavefunction at measurement is the 3D spatial cross-section reading of an x₄-extended state |Ψ(t)⟩. The observer at spatial location x_obs accesses one branch of the state because the observer is at one spatial location; the other branches exist in the four-dimensional state at other spatial locations within the same spatial slice Σ_t. The "loss" of the other branches is not a destruction of their content but a restriction of the observer's access to them. Information about the other branches is preserved in the four-dimensional state, accessible in principle through the correlations in the global wavefunction.

**Part 2: The information paradox is restricted access to the interior of a black-hole horizon.** The interior of a black-hole horizon is, in the McGucken dx₄/dt = ic framework, a region of spacetime where x₄'s outward advance has been arrested by the gravitational geometry but where x₄ continues to advance in the imaginary direction (x₄'s smoothness, Proposition X.1). Observers in the exterior region cannot access the interior in the three spatial dimensions (the horizon prevents spatial communication) but the four-dimensional state extends across the horizon in the x₄ direction. By the six-sense null-surface identity, the interior and exterior modes share x₄-coincidences along the null geodesics that connect them at the horizon.

The exterior observer's access to the interior is therefore restricted in the three spatial dimensions but not in x₄: information about the interior modes is encoded in the x₄-coincidences with exterior modes, and these coincidences are accessible in principle through the radiation pattern as the black hole evaporates (Proposition X.3).

**Structural identification.** Part 1 and Part 2 reveal that the measurement problem and the information paradox have the same structure: in both, an observer has restricted access to part of a four-dimensional state, with the apparent loss of information arising from this restriction. In both, the resolution is that the four-dimensional state is the complete description, and the restriction is a feature of the observer's projection onto a 3D cross-section (in the measurement-problem case) or onto the exterior region of a horizon (in the information-paradox case).

The same geometric mechanism — x₄-coincidences preserved by the six-sense null-surface identity — preserves correlations across both kinds of apparent boundary. The same propositions (III.1 Born rule, IV.1 superposition, V.1 collapse-as-projection, VIII.1 nonlocality from six-sense identity) apply in both cases. The McGucken dx₄/dt = ic framework therefore unifies the measurement problem and the information paradox into a single geometric account, with both resolved by the same dx₄/dt = ic principle. **∎**

#### Remark X.3 (Why the standard literature treats them as separate)

The standard literature treats the measurement problem and the information paradox as separate because they appear at different scales (atomic vs. cosmological) and involve different physical regimes (non-relativistic quantum mechanics vs. semiclassical gravity). The structural identification is hidden behind this surface difference. The McGucken dx₄/dt = ic framework reveals the identification by showing that both problems descend from the same restricted-access structure: in both cases, the observer is confined to a 3D region of a 4D spacetime, and the apparent loss of information is the consequence of x₄-correlations crossing the boundary of this region.

The unification is not merely formal. It has a substantive consequence: any resolution of the measurement problem in the McGucken dx₄/dt = ic framework automatically resolves the information paradox, and vice versa. The two problems are not separate research programmes but two manifestations of the same foundational issue — the relationship between four-dimensional reality and three-dimensional observation.

### X.6 Proposition X.5 (The McGucken dx₄/dt = ic framework as the unique framework that derives unitarity)

**Proposition X.5 (The McGucken dx₄/dt = ic framework is the only known framework that derives unitarity itself rather than postulating it).** *In all standard treatments of quantum mechanics — including all seven major interpretive programmes (Copenhagen, Many-Worlds, Bohmian, GRW, decoherence, RQM, QBism) and all major resolutions of the black hole information paradox (Susskind/'t Hooft complementarity, AdS/CFT-based unitarity, replica wormholes, Hawking soft hair) — unitarity is taken as foundational at some level: either directly postulated, or derived from a Hilbert-space framework that is itself postulated, or asserted to follow from a string-theoretic or holographic structure that is itself postulated. The McGucken dx₄/dt = ic framework is the only known framework in which unitarity is derived from a deeper geometric principle (the smoothness and Lorentz-covariance of x₄'s expansion) without taking the Hilbert-space framework, the unitary Schrödinger evolution, or the holographic structure as foundational inputs.*

**Proof.** The proof is the comparative analysis of §X.7 below, programme by programme. We summarize the result here.

* **Copenhagen, Many-Worlds, Bohmian, GRW, decoherence, RQM, QBism.** All seven of these interpretive programmes take Hilbert-space quantum mechanics with unitary evolution as foundational, with various interpretive overlays. Unitarity is built into the Hilbert-space framework, which is built into the formalism. None derives unitarity from a deeper principle.

* **Susskind/'t Hooft black-hole complementarity.** Postulates that the same information is accessible to interior and exterior observers, with the apparent contradiction resolved by the inaccessibility of joint observation. Takes unitarity as foundational; supplies an interpretive framework that maintains it.

* **AdS/CFT-based unitarity.** Holds that bulk gravity in AdS is dual to a unitary boundary CFT, with the unitarity of the boundary theory implying unitarity of the bulk. Takes the holographic duality as foundational; the unitarity of the boundary CFT is itself foundational at the boundary level.

* **Replica wormholes / Penington-Shenker-Stanford-Yang.** Derives the Page curve from quantum-extremal-surface prescriptions in semiclassical gravity, with replica wormholes contributing to the entropy formula at the Page time. Takes the quantum-extremal-surface prescription as foundational; the unitarity of the underlying quantum theory is foundational.

* **Hawking soft-hair proposal.** Suggests that information is stored on the horizon as supertranslation hair (BMS soft modes). Takes BMS asymptotic symmetries and the soft-mode structure as foundational; unitarity is preserved by the storage mechanism but not derived from a deeper principle.

In each case, unitarity is foundational at some level — either as a direct postulate or as a consequence of a higher-level framework that is itself foundational. The McGucken dx₄/dt = ic framework is the only known framework in which unitarity descends from a deeper geometric source: the smoothness of x₄'s expansion, established in Proposition X.1. **∎**

### X.7 Comparison with prior resolutions of the information paradox

We develop the comparative analysis of §X.6 in detail. Each prior resolution of the information paradox is correct as far as it goes — the McGucken dx₄/dt = ic framework does not contradict these resolutions but supplies the geometric foundation that unifies and grounds them.

**X.7.1 Susskind/'t Hooft black-hole complementarity.** Susskind, 't Hooft, and collaborators [65; 66] proposed that the same information is accessible to both interior and exterior observers, with the apparent contradiction resolved by the impossibility of any single observer accessing both. The interior observer sees the information accumulate inside the black hole; the exterior observer sees it accumulate at the horizon and then come flying out in the Hawking radiation. Both are correct, and there is no actual contradiction because no observer can compare the two readings.

**McGucken interpretation.** Black-hole complementarity is the dual-channel reading of the same x₄-advance at the horizon. The interior observer accesses the Channel B (geometric-propagation) reading: information flows along the McGucken Sphere from the formation event into the interior. The exterior observer accesses the Channel A (algebraic-symmetry) reading: information is encoded in the x₄-stationary modes of the horizon and emerges in the Hawking radiation. Both readings are correct because both descend from the same dx₄/dt = ic principle. The Susskind/'t Hooft proposal is exactly right; the McGucken dx₄/dt = ic framework supplies the geometric mechanism (the dual-channel content of dx₄/dt = ic at the horizon) that makes the proposal structurally inevitable.

**X.7.2 AdS/CFT-based unitarity.** Maldacena's AdS/CFT duality [67] relates bulk gravity in anti-de Sitter space to a unitary conformal field theory on the boundary. For a black hole in AdS, the unitarity of the boundary CFT implies unitarity of the bulk evaporation: the boundary theory is manifestly unitary, the duality is exact, so the bulk must be unitary too. This established that information is preserved in black-hole evaporation — at least in AdS — and provided the framework for subsequent calculations.

**McGucken interpretation.** AdS/CFT itself is a theorem of dx₄/dt = ic in the McGucken framework [68]. The holographic principle is the projection of x₄'s spherical expansion onto a horizon surface (the boundary of AdS being one specific type of horizon); the bulk-boundary correspondence is the dual-channel reading of the same x₄-advance at the boundary. AdS/CFT preserves information for the same reason the McGucken dx₄/dt = ic framework preserves information — both descend from the smoothness of x₄'s expansion. The McGucken dx₄/dt = ic framework is more general: AdS/CFT applies only to AdS spacetimes (with a specific cosmological constant structure), while the McGucken dx₄/dt = ic framework's information-preservation theorem applies to any spacetime where dx₄/dt = ic is smooth.

**X.7.3 Replica wormholes and the Penington-Shenker-Stanford-Yang programme.** A breakthrough in 2019–2020 [63; 64] derived the Page curve from quantum-extremal-surface prescriptions in semiclassical gravity. The key technical tool was the **replica wormhole** — a saddle-point contribution to the gravitational path integral that connects the radiation regions of multiple replicas and dominates the entropy calculation at the Page time. The Page curve emerges as the transition from the empty-replica saddle (dominant before t_P) to the wormhole saddle (dominant after t_P).

**McGucken interpretation.** The replica wormholes are geometric expressions of the x₄-coincidences between distant Hawking quanta. Each wormhole connects the radiation regions of two replicas because the corresponding Hawking quanta share x₄-coincidence with their interior partners (during the first half of evaporation) or with each other (during the second half). The replica trick, which computes Tr ρ^n by integrating over a path-integral with n replicas connected by wormholes, is the algebraic implementation of summing over x₄-coincidence patterns.

The PSSY-Almheiri programme is correct: it derives the Page curve as a mathematical theorem of the gravitational path integral with quantum corrections. The McGucken dx₄/dt = ic framework supplies the *physical mechanism* underlying the technical machinery: the replica wormholes are not abstract mathematical artifacts but geometric expressions of the x₄-coincidence structure of evaporating black holes. The McGucken dx₄/dt = ic framework's Proposition X.3 derives the Page curve directly from x₄-coincidence redistribution, in agreement with PSSY but with a more transparent physical interpretation.

**X.7.4 Hawking's 2015 soft-hair proposal.** In 2015, Hawking, Perry, and Strominger [69] proposed that information is stored on the horizon as supertranslation hair — soft (zero-energy) modes associated with the BMS asymptotic symmetries of asymptotically-flat spacetime. The soft modes are excited by infalling matter and remain as imprints on the horizon, encoding the information about what fell in.

**McGucken interpretation.** The BMS soft modes are the x₄-stationary modes of the horizon — the same modes that contribute to the Bekenstein-Hawking entropy via the area law (Theorem 20 of the Susskind paper [28]). The supertranslation symmetries are the residual gauge freedom of x₄'s expansion at null infinity, with the soft modes corresponding to gauge-fixed configurations on the horizon.

The Hawking-Perry-Strominger proposal is correct in identifying the horizon as the storage location for information, and in identifying soft modes as the carrier. The McGucken dx₄/dt = ic framework supplies the geometric foundation: the horizon's x₄-stationary modes are the natural information carriers because they encode the x₄-coincidences with the matter that crossed the horizon. The soft-hair structure is one specific representation of the horizon's x₄-mode structure; the McGucken dx₄/dt = ic framework provides the dual-channel reading that connects this representation to the Hawking-radiation correlations of §X.4.

**X.7.5 The structural pattern.** All four prior resolutions are correct in their specific scope but incomplete in foundational status. Each takes some structure as foundational — the equivalence of complementarity readings (Susskind/'t Hooft), the holographic duality (AdS/CFT), the quantum-extremal-surface prescription (PSSY), the BMS asymptotic symmetries (Hawking soft hair) — and derives information preservation from that structure. The McGucken framework derives all four structures as theorems of dx₄/dt = ic and supplies the unified geometric account that connects them.

The structural pattern is the same as in the comparative analysis of §XIII (Why Other Born-Rule Derivations Fall Short): each prior framework has the right empirical content but takes some structure as foundational that the McGucken dx₄/dt = ic framework derives. The McGucken dx₄/dt = ic framework is therefore not a competitor to these prior resolutions — it is their geometric foundation.

### X.8 Empirical and falsifiability content

The McGucken account of information preservation makes two specific empirical predictions that distinguish it from competing accounts.

**X.8.1 The Page curve must be observed if direct measurement of an evaporating black hole becomes possible.** The McGucken dx₄/dt = ic framework predicts the Page curve as a forced theorem of x₄-coincidence redistribution. If a direct measurement of an evaporating black hole's radiation entropy ever becomes possible (which is currently impossible because t_evap exceeds the age of the universe for astrophysical black holes), the curve must rise to a maximum at the Page time and then fall to zero. Any monotonic-rise behavior would falsify the framework.

**X.8.2 The McGucken-Bell directional modulation extends to black-hole horizons.** The same x₄-coincidence mechanism that produces Bell-violating correlations in entangled-photon experiments (Proposition VIII.1) produces information-preserving correlations in Hawking radiation. The framework's prediction is that the radiation pattern from an evaporating black hole has specific directional structure (analogous to the McGucken-Bell modulation [15] for entangled pairs) that encodes the x₄-coincidences with the absorbed matter. While direct observation is currently impossible, indirect tests through analog-gravity experiments (Bose-Einstein condensates as black-hole analogs, [70]) may be feasible.

**X.8.3 Information cannot be destroyed.** The strongest empirical commitment of the framework is that information is *never* destroyed in any physical process. This is a categorical statement on the same footing as the no-magnetic-monopole prediction (§XIV.3) and the cross-species Compton-frequency decoherence prediction (§XIV.1). Any observation suggesting information destruction would falsify the McGucken Principle itself, because such an observation would imply a discontinuity in x₄'s expansion (a violation of Proposition X.1, Step 2).

The empirical status of these predictions:

* **Page curve:** Indirect support from quantum-extremal-surface calculations [63; 64]; direct observation impossible at present.
* **Hawking-radiation directional modulation:** Untested but in principle accessible through analog-gravity experiments.
* **No information destruction:** Consistent with all current observations; no counterexample known.

The framework is therefore on the same falsifiability footing for information as for the other foundational predictions: definite, falsifiable in principle, and consistent with all current evidence.

### X.9 Summary

The black hole information paradox is dissolved in the McGucken framework as a theorem of the same geometric principle (dx₄/dt = ic) that resolves the measurement problem. The five Propositions of this section establish:

* **Proposition X.1:** Information is never destroyed, as a Grade-1 theorem of x₄'s smoothness and Lorentz-covariance.

* **Proposition X.2:** Unitarity is derived from x₄'s smoothness, not postulated. The chain smoothness → Hermiticity → unitarity → information preservation reduces unitarity to a derived consequence of the McGucken Principle.

* **Proposition X.3:** The Page curve is forced by x₄-coincidence redistribution from interior-exterior pairs (during the first half of evaporation) to exterior-exterior correlations (during the second half), with the Page-time maximum at S_BH(0)/2 emerging as a direct geometric consequence.

* **Proposition X.4:** The measurement problem and the information paradox are the same problem at different scales — both arise from the observer's restricted access to a four-dimensional state, and both are resolved by the same x₄-coincidence mechanism.

* **Proposition X.5:** The McGucken dx₄/dt = ic framework is the only known framework that derives unitarity itself rather than postulating it. All seven interpretive programmes and all four major information-paradox resolutions take unitarity (or a structure that implies it) as foundational at some level.

The structural identification of the measurement problem and the information paradox (Proposition X.4) is the deepest unification the framework accomplishes in this paper. Two of the central foundational problems of physics — one at the atomic scale (measurement) and one at the cosmological scale (black holes) — are revealed to be the same problem, with the same resolution. This is the kind of unification that John Archibald Wheeler [71] called the goal of foundational physics: not the addition of new postulates to handle each new problem, but the recognition that apparently separate problems are manifestations of the same deeper structure.

The McGucken framework supplies that deeper structure: dx₄/dt = ic. The measurement problem dissolves because the four-dimensional state is the complete description and apparent collapse is the cross-section reading; the information paradox dissolves because the four-dimensional state is the complete description and apparent information loss is the exterior-region reading. Both are theorems of one principle.

> *"Behind it all is surely an idea so simple, so beautiful, that when we grasp it — in a decade, a century, or a millennium — we will all say to each other, how could it have been otherwise?"*
> — John Archibald Wheeler

The idea is dx₄/dt = ic. The measurement problem and the information paradox are two of its theorems.

---

## XI. The Joint Derivation of Superposition and Collapse: The Structural Punchline

The development of the present paper has now reached a point where the structural significance of the McGucken dx₄/dt = ic framework can be stated in its sharpest form. This section makes the structural punchline explicit, develops it in detail, and supports it with the rigorous joint analysis that the foundational status of the claim requires.

### XI.1 The structural punchline

The standard Dirac–von Neumann axiomatization of quantum mechanics rests on six independent postulates Q1–Q6. Of these six, two are foundational in a deeper sense than the others, in that the remaining four either presuppose them or follow naturally from them once they are in place:

**(Q1) Linear superposition (the Hilbert-space postulate).** The state space of a quantum system is a complex separable Hilbert space ℋ, and physically realizable states are unit vectors in ℋ defined up to overall phase. The linearity of ℋ — the fact that for any |ψ⟩, |φ⟩ ∈ ℋ and α, β ∈ ℂ with |α|² + |β|² = 1 the linear combination α|ψ⟩ + β|φ⟩ is also a physically realizable state — is the foundational structural feature that distinguishes quantum mechanics from classical mechanics. Without (Q1), there is no superposition, no interference, and no quantum theory; there is only classical statistical mechanics.

**(Q3) The Born rule.** The probability of measurement outcome a given the wavefunction ψ is |⟨a|ψ⟩|². The squared-amplitude form of (Q3) is what converts the Hilbert-space amplitudes of (Q1) into empirical probabilities. Without (Q3), the Hilbert-space formalism is mathematically well-defined but empirically empty; quantum mechanics has no testable predictions.

These two postulates — (Q1) and (Q3) — are the structural core of quantum mechanics. The other four postulates (Q2 self-adjoint operators, Q4 Schrödinger evolution, Q5 canonical commutation, Q6 tensor product structure) are derivable from (Q1) and (Q3) together with standard structural commitments shared with all reasonable physical theories: real-valuedness of observables forces (Q2), Stone's theorem applied to spacetime translations forces (Q5), Lorentz-covariance plus the rest-mass-phase factor forces (Q4), and the linearity of Hilbert space combined with subsystem decomposition forces (Q6). The structural foundation of quantum mechanics is therefore really *two* postulates: linearity (Q1) and the Born rule (Q3).

**The structural punchline of the McGucken dx₄/dt = ic framework.** Both of these foundational postulates are derived as theorems of one geometric principle. (Q1) is forced by Proposition IV.1 (superposition as geometric overlap of McGucken-Sphere wavefronts); (Q3) is forced by Proposition III.1 (Born rule as squared-amplitude geometry of x₄-wavefront cross-sections). The remaining apparent (R) postulate — wave function collapse — is reduced to a theorem of the same principle by Proposition V.1 (apparent collapse as 3D cross-section reading) and Proposition VI.1 (irreversibility from x₄-monotonicity). The McGucken dx₄/dt = ic framework therefore subtracts the entire foundational base of quantum mechanics from the postulate column and places it in the theorem column: linearity, the Born rule, and the apparent collapse are all consequences of dx₄/dt = ic.

This is a structural reduction without parallel in the foundations of quantum mechanics. No prior framework — Copenhagen, Many-Worlds, Bohmian mechanics, GRW, decoherence-plus-environmental-selection, RQM, QBism, or any combination — derives both (Q1) and (Q3) from a single underlying principle. Each prior framework either takes both as postulates, takes one as primitive and derives the other from auxiliary assumptions, or modifies the dynamics to incorporate one and leaves the other primitive. The McGucken dx₄/dt = ic framework is the unique exception: it derives both from one geometric postulate.

### XI.2 Why this is structurally novel

Three sub-claims must be established to ground the structural punchline.

**(SP-I)** The linearity of the Hilbert-space postulate (Q1) is not foundational in the McGucken dx₄/dt = ic framework; it is a derived structural feature.

**(SP-II)** The Born rule (Q3) is not foundational in the McGucken dx₄/dt = ic framework; it is a derived structural feature.

**(SP-III)** The joint derivation of (Q1) and (Q3) from a single principle is unique to the McGucken dx₄/dt = ic framework among all known quantum interpretations.

**(SP-I)** is established by Proposition IV.1: the superposition principle is forced by the geometric overlap of McGucken-Sphere wavefronts in four-dimensional spacetime, with three structural pieces — multiple wavefronts can coexist (because x₄'s uniform advance does not select between sources), linear addition with complex coefficients is the unique combination operation (because of the four conditions D1–D4), and the perpendicularity marker i encodes relative phase (because x₄ = ict). The Hilbert-space linearity of (Q1) is the algebraic consequence of these three geometric facts, not the source of them.

**(SP-II)** is established by Proposition III.1: the Born rule is forced by the squared-amplitude geometry of the McGucken-Sphere cross-section, with three structural pieces — complex character of ψ from i as perpendicularity marker (Piece 1), quadratic exponent forced by the four conditions C1–C4 on probability density (Piece 2), and SO(3) Haar-measure shape forced by spherical symmetry of x₄'s expansion (Piece 3). The Born rule is the unique probability density consistent with these three structural facts.

**(SP-III)** is the comparative claim and is the substantive content of the present section. It is established by surveying all known quantum interpretations and showing that none of them simultaneously derives both (Q1) and (Q3) from a single underlying principle. The next two subsections develop this comparison in detail.

### XI.3 Why prior frameworks cannot derive both (Q1) and (Q3) from one principle

The seven major interpretive programmes are surveyed under the joint criterion: does the framework derive *both* (Q1) and (Q3) from a single underlying principle? The answer is uniformly negative for all seven prior frameworks. We develop the analysis programme by programme.

**XI.3.1 Copenhagen.** Copenhagen takes both (Q1) and (Q3) as postulates. The Hilbert-space structure is accepted as given; the Born rule is accepted as the operational rule for measurement probabilities. The framework explicitly declines to provide a foundational source for either postulate, treating them as primitive elements of the formalism. There is no claim of derivation from a deeper principle, single or otherwise. **Result: derives neither (Q1) nor (Q3) from any underlying principle.**

**XI.3.2 Many-Worlds.** Many-Worlds takes (Q1) as foundational — the universal wavefunction evolves unitarily on a Hilbert space, and all branches are equally real. The framework attempts to derive (Q3) from auxiliary frameworks: decision theory (Deutsch1999; Wallace2012) requires rationality axioms (independence, transitivity, dominance) plus the Many-Worlds ontology; envariance (Zurek2005) requires symmetry properties of system-environment entangled states with a specific coupling structure. Critics [36; 72; 37] have argued at length that the rationality axioms and envariance assumptions themselves require justification not present in the framework, and that the derivations of (Q3) are circular or incomplete. Even granting the most charitable reading of these derivations, (Q1) remains foundational and (Q3) is derived only from auxiliary postulates (rationality axioms, envariance, etc.) that are not themselves derived from a deeper physical principle. **Result: takes (Q1) as foundational; derives (Q3) only from auxiliary postulates that are themselves foundational.**

**XI.3.3 Bohmian mechanics.** Bohmian mechanics takes (Q1) as foundational — the guidance wave ψ evolves unitarily on a Hilbert space — and adds hidden variables (definite particle positions) plus the guidance equation. (Q3) is derived from the equilibrium hypothesis: particles are initially distributed according to |ψ|². Valentini [73, 74] showed that quantum non-equilibrium distributions are stable under Bohmian dynamics, so the equilibrium hypothesis is an *additional* postulate not derivable from the Bohmian dynamics alone. The framework therefore takes (Q1) as foundational and derives (Q3) only by adding the equilibrium hypothesis as a separate postulate. **Result: takes (Q1) as foundational; derives (Q3) only by adding the equilibrium hypothesis as a separate postulate.**

**XI.3.4 GRW spontaneous localization.** GRW modifies (U) by adding stochastic terms with phenomenological parameters λ (rate) and a (localization width). The modified dynamics produces an effective Born rule in the long-time limit, but the modification itself is the additional postulate, and the parameters are phenomenological (set to match observed quantum-classical behavior). (Q1) remains foundational at the level of the unmodified Schrödinger equation; (Q3) is derived from the modified dynamics, but only by adding parameters that are not themselves derived. **Result: takes (Q1) as foundational; derives (Q3) only by adding stochastic dynamics with phenomenological parameters.**

**XI.3.5 Decoherence-plus-environmental-selection.** The Zurek/Joos/Zeh decoherence programme takes both (Q1) and (Q3) as foundational and supplements them with an account of how environmental coupling produces apparent classicality. The framework correctly explains why off-diagonal terms in ρ_S decay rapidly, but does not derive (Q1) or (Q3) from any deeper source. The diagonal weights |c_i|² are taken as primitive; the linearity of Hilbert space is taken as primitive. **Result: takes both (Q1) and (Q3) as foundational, supplemented with environmental coupling but not derived from a deeper principle.**

**XI.3.6 Relational Quantum Mechanics.** RQM relativizes both (Q1) and (Q3) to observers — different observer-systems may assign different states (and different probabilities) to the same physical situation. The framework takes the Born rule and the Hilbert-space structure as relational primitives, accepting that there is no observer-independent answer to the question "what state is the system in?" The framework is a coherent philosophical position but does not derive (Q1) or (Q3) from a deeper physical principle. **Result: takes both (Q1) and (Q3) as relational primitives; no derivation from underlying principle.**

**XI.3.7 QBism.** QBism takes (Q1) as a feature of the agent's choice of representation (the Hilbert space is a tool for organizing the agent's beliefs about measurement outcomes) and (Q3) as a normative coherence requirement on the agent's beliefs (justified by Dutch-book arguments). The framework explicitly declines to derive either postulate from a deeper physical principle, treating them as primitive coherence requirements on agent reasoning. **Result: takes both (Q1) and (Q3) as agent-relative primitives; no derivation from underlying principle.**

**Summary.** Of the seven major interpretive programmes, none derives both (Q1) and (Q3) from a single underlying principle. Most frameworks take both as foundational (Copenhagen, decoherence, RQM, QBism); some derive one from auxiliary postulates while leaving the other foundational (Many-Worlds derives Q3 from decision-theory or envariance with Q1 foundational; Bohmian mechanics derives Q3 from equilibrium hypothesis with Q1 foundational; GRW derives Q3 from stochastic-dynamics with Q1 foundational). No framework derives both from a single source.

### XI.4 The McGucken dx₄/dt = ic framework's joint derivation

The McGucken dx₄/dt = ic framework derives both (Q1) and (Q3) from the single geometric principle dx₄/dt = ic. The joint derivation has three structural features that distinguish it from the prior frameworks.

**Feature 1: A single principle, not a combination.** The McGucken Principle is one geometric statement: the fourth dimension is expanding in a spherically symmetric manner at the velocity of light. From this single statement, three structural facts follow that jointly force both (Q1) and (Q3): (i) x₄'s expansion proceeds simultaneously and from every spacetime event, permitting multiple coexisting wavefronts; (ii) the spherical symmetry of x₄'s expansion forces SO(3) Haar-measure on angular distributions of the McGucken-Sphere cross-section; (iii) the perpendicularity marker i in x₄ = ict is the algebraic feature that allows complex amplitudes to encode relative phase information.

The first structural fact (i) drives Proposition IV.1's Piece 1 (multiple wavefronts can coexist). The second structural fact (ii) drives both Proposition III.1's Piece 3 (SO(3) Haar measure forces the squared-amplitude form on angular distributions) and Proposition IV.1's Piece 2 (linear addition with complex coefficients is the unique combination operation respecting SO(3) Haar-equivariance). The third structural fact (iii) drives both Proposition III.1's Piece 1 (complex character of ψ from i as perpendicularity marker) and Proposition IV.1's Piece 3 (complex coefficients encode relative phase).

The same three structural facts therefore drive both (Q1) and (Q3). The joint derivation is not a combination of two independent derivations sharing only a label; it is a single derivation whose two outputs (linearity and the Born rule) are the algebraic and probabilistic faces of the same geometric structure.

**Feature 2: No auxiliary postulates beyond standard structural commitments.** The derivation of (Q1) and (Q3) requires only the McGucken Principle plus the standard structural commitments shared with all reasonable physical theories: positivity and normalization of probabilities, Lorentz-covariance of physical predictions, smoothness of the differential structure, finite polynomial order in derivatives, linearity of superposition (which is itself derived in (SP-I), so the commitment is to *that* derivation, not to linearity as a primitive), and locality of field interactions.

These standard commitments are the same commitments accepted by all the prior frameworks; the McGucken dx₄/dt = ic framework requires no additional postulates beyond these and the McGucken Principle. In particular: no rationality axioms (decision theory), no envariance assumption (Zurek), no equilibrium hypothesis (Bohmian), no stochastic-dynamics modification (GRW), no environmental coupling input (decoherence), no relational primitives (RQM), no Dutch-book arguments (QBism). The McGucken derivation requires only what every reasonable physical theory already assumes plus one additional geometric principle.

**Feature 3: Both derivations are intrinsically connected through the same structural facts.** Linearity (from Proposition IV.1) and the Born rule (from Proposition III.1) are not derived independently and then assembled; they are derived from the same three structural facts about x₄'s spherically symmetric expansion. This intrinsic connection has two structural consequences.

*First, the consistency of (Q1) and (Q3) is automatic.* In any framework where (Q1) and (Q3) are postulates or derived from independent auxiliary frameworks, the consistency of the two — the fact that the linearity of Hilbert space is compatible with the squared-amplitude form of the Born rule, that interference patterns observed in double-slit experiments match the squared-modulus of the linear-superposition wavefunction, that the no-cloning theorem and the Born rule are jointly consistent — must be checked separately as additional axiomatic content. In the McGucken dx₄/dt = ic framework, the consistency is automatic because both derivations descend from the same structural facts.

*Second, the joint derivation eliminates the structural arbitrariness of the standard formalism.* In standard quantum mechanics, the choice of Hilbert space (complex, separable) and the choice of probability rule (squared-amplitude) are both made by hand to match experiment, and the joint plausibility of these choices is taken as evidence that the formalism is correct. In the McGucken dx₄/dt = ic framework, both choices are forced by the same geometric facts. There is no arbitrariness: complex Hilbert spaces with squared-amplitude probability rules are the unique formalism consistent with the geometric overlap of McGucken-Sphere wavefronts.

### XI.5 The collapse problem in light of the joint derivation

The structural punchline extends naturally to the collapse problem. In the standard formalism, wave function collapse (R) is a separate dynamical postulate alongside (U), with the foundational tension between unitary evolution and stochastic reduction taken as a primary feature of quantum mechanics. Various interpretive programmes address the collapse problem by adding structure to this foundational tension: Copenhagen accepts (R) as primitive; Many-Worlds explains (R) away as observer-restricted access to branches; Bohmian mechanics replaces (R) with hidden-variable evolution; GRW modifies (U) to incorporate (R) as a real physical process; decoherence shows that (R) becomes operationally invisible after environmental coupling; RQM relativizes (R) to observers; QBism reinterprets (R) as Bayesian update.

The McGucken dx₄/dt = ic framework dissolves the collapse problem entirely by reducing apparent (R) to the joint geometric content of (Q1) and (Q3) via the spatial-cross-section reading of Proposition V.1. The argument has four steps:

**Step 1.** Linearity (Proposition IV.1) gives the four-dimensional state |Ψ(t)⟩ as a superposition of branches |s_i⟩ ⊗ |A_i⟩ ⊗ |E_i⟩ in the Hilbert space ℋ_S ⊗ ℋ_A ⊗ ℋ_E. The unitary evolution (U) preserves this superposition.

**Step 2.** The four-dimensional state |Ψ(t)⟩ is a four-dimensional geometric object — a McGucken Sphere from the measurement interaction event. Its 3D cross-section at any spatial slice Σ_t at time t is determined by the geometric intersection of the McGucken Sphere with the slice (Proposition V.1).

**Step 3.** A specific observer at spatial location x_obs at time t accesses one configuration of the four-dimensional state — the configuration that lies at x_obs in Σ_t. This is one specific branch |s_k⟩ ⊗ |A_k⟩ ⊗ |E_k⟩, with the other branches at other spatial locations within Σ_t.

**Step 4.** The probability that the observer's local cross-section intersects branch k is |c_k|², the squared amplitude of branch k in |Ψ(t)⟩ (Proposition III.1, the Born rule).

The apparent collapse is therefore not a separate dynamical law: it is the joint consequence of (i) linearity (which gives the four-dimensional state as a superposition), (ii) the geometric structure of the McGucken Sphere (which gives the cross-section reading), and (iii) the Born rule (which gives the probability of intersection). All three are theorems of dx₄/dt = ic. The collapse problem dissolves into a theorem of the joint derivation of (Q1) and (Q3).

This is structurally distinct from the prior treatments. Many-Worlds dissolves collapse by appeal to branches but takes both (Q1) and (Q3) as inputs (with Q3 derived from auxiliary postulates); the McGucken dx₄/dt = ic framework dissolves collapse by appeal to the four-dimensional state's cross-section structure with both (Q1) and (Q3) as derived theorems of dx₄/dt = ic. Bohmian mechanics dissolves collapse by appeal to hidden variables but takes (Q1) as foundational and adds the equilibrium hypothesis for (Q3); the McGucken dx₄/dt = ic framework dissolves collapse with no hidden variables and both (Q1) and (Q3) derived. GRW modifies (U) to incorporate (R) and treats (Q3) as emergent from the modification; the McGucken dx₄/dt = ic framework leaves (U) exact and treats (R) as the cross-section reading of the four-dimensional state.

### XI.6 The structural reduction quantified

The structural simplification of the McGucken dx₄/dt = ic framework can be made quantitative. The standard Dirac–von Neumann axiomatic system has six independent postulates Q1–Q6. The structural-foundation pair (Q1, Q3) — linearity and Born — is the irreducible core; the other four postulates (Q2, Q4, Q5, Q6) are derivable from (Q1, Q3) plus standard structural commitments. The McGucken dx₄/dt = ic framework reduces (Q1, Q3) themselves to theorems of one geometric principle.

By [29, §3.1], the McGucken Principle has Kolmogorov complexity K(McG) ∼ 10² bits in any reasonable formal language. The Dirac–von Neumann postulate system has K(Q1–Q6) ∼ 10⁴ bits to specify directly, with the structural-foundation pair (Q1, Q3) accounting for roughly 10³ bits of that total (the Hilbert-space construction with its complex structure, separability, sesquilinear inner product, and projective rays, plus the Born rule with its squared-amplitude form and Lorentz-covariance). The McGucken dx₄/dt = ic framework therefore compresses the structural-foundation pair from ∼ 10³ bits to ∼ 10² bits, a one-order-of-magnitude reduction.

The remaining bit-budget compression — from ∼ 10⁴ bits of full standard quantum mechanics to ∼ 10² bits of the McGucken Principle — is accomplished by the additional theorem chain of [6]: Theorem 7 (Schrödinger), Theorem 8 (Klein-Gordon), Theorem 9 (Dirac with spin-½ and 4π periodicity), Theorem 10 (canonical commutation relation, dual-route derivation), Theorem 12 (Heisenberg uncertainty), Theorem 13 (CHSH and Tsirelson bound), Theorem 15 (Feynman path integral), Theorem 20 (second quantization with spin-statistics and Pauli exclusion), and Theorem 23 (Feynman-diagram apparatus). Each of these theorems removes additional bits from the structural foundation by reducing them to consequences of dx₄/dt = ic.

The total structural reduction is therefore two orders of magnitude in K-complexity. The McGucken Principle is a 10² bit specification from which the entire 10⁴ bit content of standard quantum mechanics descends. By [29, Theorem 3.1], no foundational quantum-mechanical framework with strictly smaller K-complexity can recover the same physical content.

### XI.7 Why this matters: the structural status of quantum mechanics

The structural punchline has consequences for how quantum mechanics should be understood as a physical theory.

**Quantum mechanics is not foundationally axiomatic.** The Dirac–von Neumann presentation of quantum mechanics as a six-postulate axiomatic system has been the standard pedagogy for ninety years, but the McGucken dx₄/dt = ic framework shows that this presentation is not foundationally accurate. Quantum mechanics is foundationally a *derived* theory — its postulates are theorems of a deeper geometric principle. The pedagogical value of the axiomatic presentation is significant (it organizes the formalism for calculation and matches the historical development), but the structural status of quantum mechanics is that of a derived theory, not an axiomatic foundation.

**The "weirdness" of quantum mechanics is the weirdness of x₄'s expansion.** Many of the conceptual difficulties associated with quantum mechanics — the complex wave function, the squared-amplitude probability rule, the apparent collapse at measurement, the violation of Bell inequalities, the wave-particle duality, the Schrödinger's cat paradox — have appeared mysterious because the underlying geometric source has been hidden. In the McGucken dx₄/dt = ic framework, each of these features is the algebraic or probabilistic face of the same single geometric fact: x₄ is a fourth dimension expanding spherically at the velocity of light. The "weirdness" is the consequence of having physics in four spacetime dimensions while observation is confined to three spatial dimensions; the projection of the four-dimensional structure onto three spatial dimensions produces all the apparent peculiarities.

**The unification with relativity is automatic.** Special relativity is the kinematic content of x₄ = ict; quantum mechanics is the wave-mechanical content of dx₄/dt = ic. Both descend from the same geometric principle [30, 6]. The standard problem of "reconciling quantum mechanics with relativity" — which has driven much of the foundational programme of physics for a century — is, in the McGucken dx₄/dt = ic framework, not a problem at all: both theories are theorems of the same principle, and their joint consistency is automatic. The Lorentz-covariance of the Born rule (condition C4 in Proposition III.1) and the Lorentz-covariance of the superposition principle (condition D2 in Proposition IV.1) are guaranteed structurally because dx₄/dt = ic is Lorentz-covariant by construction.

**The unification with general relativity is structurally available.** The companion paper [3] develops general relativity from the same principle dx₄/dt = ic, with the spatial metric h_{ij} as the dynamical object and the Einstein–Hilbert action as the unique Lagrangian compatible with smoothness, locality, and Lorentz-covariance. The unification of quantum mechanics with general relativity — long considered the central unsolved problem of theoretical physics — is structurally available in the McGucken dx₄/dt = ic framework because both theories descend from the same principle. The structural punchline of the present paper (joint derivation of Q1 and Q3 from dx₄/dt = ic) is therefore one half of a larger structural unification (joint derivation of quantum mechanics and general relativity from dx₄/dt = ic).

### XI.8 Summary of the structural punchline

The McGucken dx₄/dt = ic framework is the only known quantum framework that derives both (Q1) linearity and (Q3) the Born rule from a single underlying principle. The joint derivation has three structural features that distinguish it from all prior frameworks:

* **A single principle.** Both derivations descend from the same geometric statement dx₄/dt = ic, with three structural facts about x₄'s spherically symmetric expansion driving both derivations through their respective three-piece breakdowns.

* **No auxiliary postulates.** The derivations require only the McGucken Principle plus the standard structural commitments shared with all reasonable physical theories. No rationality axioms, no envariance assumption, no equilibrium hypothesis, no stochastic-dynamics modification, no environmental coupling input, no relational primitives, no Dutch-book arguments are required.

* **Intrinsic connection.** Linearity and the Born rule are not derived independently and then assembled; they are derived from the same structural facts, with consistency automatic and the structural arbitrariness of the standard formalism eliminated.

The collapse problem dissolves naturally as a consequence of the joint derivation: apparent (R) is the geometric content of the four-dimensional state's 3D cross-section, with linearity supplying the superposition that is the source of branches and the Born rule supplying the probability that the observer's local cross-section intersects each branch.

The structural reduction is quantitative: the McGucken Principle compresses the foundational pair (Q1, Q3) from ∼ 10³ bits to ∼ 10² bits, with the remaining theorem chain of [6] accomplishing the further compression to the full ∼ 10⁴ bit content of standard quantum mechanics. The McGucken dx₄/dt = ic framework is therefore foundationally simpler than standard quantum mechanics by two orders of magnitude in K-complexity, with no loss of physical content.

The structural status of quantum mechanics in the McGucken dx₄/dt = ic framework is that of a *derived* theory, not an axiomatic foundation. Its postulates are theorems of dx₄/dt = ic. The conceptual difficulties associated with quantum mechanics are the consequence of physics in four spacetime dimensions being observed from three spatial dimensions, with the projection structure producing all the apparent peculiarities. The unification with relativity is automatic; the unification with general relativity is structurally available through the parallel theorem chain of [3].

This is the structural punchline: where the original presentation of quantum mechanics in the McGucken dx₄/dt = ic framework already established that the Born rule is a theorem rather than a postulate, the present analysis establishes that the *foundational structure* of quantum mechanics — both linearity and the Born rule — is a theorem rather than a postulate. The Hilbert-space postulate (Q1) is no longer foundational; the Born-rule postulate (Q3) is no longer foundational; the apparent collapse (R) is no longer a separate dynamical law. All three are derived consequences of a single geometric principle: the fourth dimension is expanding at the velocity of light.

---

### XI.9 The structural deeper reason: space-operator co-generation as the source of joint derivation

The joint-derivation argument of the present section establishes that the McGucken dx₄/dt = ic framework derives both (Q1) linearity and (Q3) the Born rule from a single underlying principle, a result no other interpretive programme has achieved. The remainder of §XIII develops a yet-deeper structural fact that explains *why* the joint derivation was possible in the first place: the space-operator co-generation theorem (Theorem XIII.I, which the reader may consult ahead in §XIII.10).

The co-generation theorem states that the McGucken Principle generates the McGucken Space $\mathcal{M}_G$ and the McGucken Operator $D_M$ as a single source space-operator pair: $dx_4/dt = ic \Longrightarrow (\mathcal{M}_G, D_M)$. This co-generation is what makes joint derivation of (Q1) and (Q3) possible. (Q1) — the Hilbert-space linearity postulate — is a fact about the *space* on which states reside. (Q3) — the Born rule — is a fact about the *measure* on outcomes that connects states to probabilities. In the standard categorical structure of quantum mechanics, these are two independent foundational layers, and a framework that derives both must derive them from *separately* foundational structures. The McGucken dx₄/dt = ic framework derives them jointly because the space they describe is itself a derivative of $\mathcal{M}_G$, which is co-generated with the operator algebra $D_M$ that produces the Born measure on the wavefront cross-section. There is no "space side" of the framework separate from the "operator side"; they are co-descendants of one principle, and so anything derivable from one is automatically consistent with anything derivable from the other.

This is the structural deeper reason for the joint derivation. The seven prior interpretive programmes failed to derive both (Q1) and (Q3) from one principle because they operate within the standard categorical structure where space and operator algebra are independent foundational inputs. To derive both, a framework must operate at a deeper categorical level — at the level of a primitive law that co-generates space and operator. The McGucken dx₄/dt = ic framework is the only known framework that operates at this categorical level, and the co-generation theorem is the formal expression of that fact.

The structural punchline of §XI is therefore strengthened by Proposition XIII.6 (in §XIII.12), which states that the co-generation theorem rules out any separate measurement-collapse mechanism. Where §XI.5 argued that the collapse problem is dissolved as a consequence of the joint derivation, Proposition XIII.6 establishes that the dissolution is *categorical*: the standard measurement problem cannot even be formulated within the McGucken dx₄/dt = ic framework's category structure, because the categorical separation it requires (system, apparatus, observer, dynamics as distinct foundational categories) does not exist when space and operator are co-generated.

The reader who has internalized §XI's joint-derivation argument and §XIII.10's co-generation theorem will recognize that they are two readings of the same structural fact viewed at different levels of abstraction. §XI.9 thus serves as a forward-pointer: the deepest structural reason the joint derivation works is the co-generation of $\mathcal{M}_G$ and $D_M$ from $dx_4/dt = ic$, and the deepest consequence of that co-generation is the categorical dissolution of the measurement problem.

---

## XII. The Feynman Path Integral as the 3D Shadow of x₄'s Expanding Wavefront: The Geometric Content of "Every Path"

### XII.1 Feynman's mystery and its dissolution

Richard Feynman's 1948 reformulation of quantum mechanics expressed the propagator as a sum over all paths connecting an initial event A to a final event B, with each path weighted by exp(iS/ℏ) where S is the classical action [75]:

$$K(B;A) = \int \mathcal{D}x(t)\, \exp\!\left(\frac{i}{\hbar}\int_A^B L\,dt\right).$$

The path integral is calculationally equivalent to the Schrödinger and Heisenberg formulations and has become the standard tool of quantum field theory. Yet the *physical* content of "the particle follows every path" has remained mysterious for nearly eighty years. Feynman himself acknowledged the strangeness: in his Nobel lecture he described the procedure as "summing over histories" and offered no underlying mechanism for *why* nature should compute amplitudes by integrating over an infinite continuum of spatial paths, most of which the classical particle never traverses.

The McGucken dx₄/dt = ic framework supplies the missing physical content — and supplies it in a form that the author wishes to state in his own words, because the formulation is novel and the geometric reading it captures is the substantive content of the present section:

> **Author's statement of the geometric content of Feynman's "every path."** Consider a photon propagating on the spherically symmetric expanding wavefront of x₄. Feynman has always stated that a particle follows every path. This is because x₄'s expansion represents an expanding nonlocality, and thus every point on that nonlocality is the photon's path — the photon's position is always on the expanding surface of nonlocality. Thus, to us in 3D, it seems as if the photon is following every single possible path, which we see as being every single possible radius of the expanding sphere.

This is the structural reading. The remainder of the section develops it formally, situates it within the existing derivation chain of the McGucken corpus [10, 11, 6], and shows that it strengthens Propositions III.1 (Born rule), V.1 (apparent collapse as cross-section reading), and VIII.1 (nonlocality from null-surface identity) of the present paper.

### XII.2 The McGucken Sphere as the Geometric Locus of "Every Path"

A photon emitted at event A creates a McGucken Sphere Σ₊(A) — the spherically symmetric forward null surface centered on A and expanding at velocity ic from A in the four-dimensional manifold. By the structural geometry of dx₄/dt = ic [30, §3], every point on Σ₊(A) is null-separated from A: the line element ds² between A and any event on Σ₊(A) vanishes, and the entire wavefront is x₄-coincident with the emission event in the geometric sense established throughout the McGucken corpus [9, §I]. The McGucken Sphere is not a probability cloud, not a "many photons" superposition, and not an ensemble of trajectories. It is one geometric object — one expanding null surface — and the photon's geometric extent in 4D *is* the entire surface.

The structural identification follows immediately:

**Definition XII.1 (McGucken Sphere as path-integral locus).** *The four-dimensional locus on which the photon resides between emission at A and detection at B is the union of all points P on the expanding McGucken Sphere Σ₊(A) such that B lies on the future null surface Σ₊(P). This locus is, by construction, the set of all spatial paths from A to B that lie along null wavefronts.*

The 3D projection of this 4D fact is precisely what Feynman's path integral computes. From the 3D perspective at observer time t, the photon appears to have explored every spatial path connecting A to B — because in 4D it was geometrically present on the entire expanding wavefront, and the projection onto the 3D spatial slice Σ_t makes the wavefront's geometric extent look like an integration over spatial trajectories.

The "every path" of Feynman is the geometric continuum of points on the McGucken Sphere's wavefront. The mystery dissolves because the foundational object is geometric: the photon really is on every point of the expanding null surface, so the "sum over paths" is a literal description of the wavefront's geometric extent in 4D, not an arbitrary calculational prescription.

### XII.3 Formal derivation: the path integral as a theorem of dx₄/dt = ic

The formal derivation has been developed in the prior corpus through four propositions [10]. We restate them here in the structure required by the present paper, with cross-references to the existing derivation.

**Proposition XII.1 (Huygens' principle from x₄-spherical expansion).** *The McGucken Principle dx₄/dt = ic asserts that x₄ advances spherically symmetrically from every spacetime event at rate c. The three-dimensional cross-section at observer time t from emission event p₀ is the McGucken Sphere Σ₊(p₀) of radius c(t − t₀) centered at the spatial location of p₀. This sphere is geometrically the forward light cone of p₀ and structurally the carrier of Huygens' secondary wavelet construction. Huygens' principle is therefore a theorem of dx₄/dt = ic, not an independent postulate.* [Cf. 10, Proposition L1.]

**Proposition XII.2 (Iterated Huygens generates all paths).** *Divide the time interval [t_i, t_f] into N intervals of duration ε = (t_f − t_i)/N. By Proposition XII.1, at the end of each interval the wavefront from any preceding event has expanded into a McGucken Sphere of radius cε. Applying Huygens' principle at each step produces a continuous chain of intermediate positions q₁, q₂, …, q_{N−1}, with each q_k lying on the McGucken Sphere centered on q_{k−1}. In the limit N → ∞, the set of all such chains is, by the standard density argument, the set of all continuous paths from q_i to q_f. The Feynman sum over paths is therefore geometrically the sum over chains of McGucken Spheres.* [Cf. 10, Proposition L2.]

**Proposition XII.3 (Accumulated x₄-phase is the Feynman weight).** *For a particle of rest mass m moving with three-velocity v, the McGucken Principle dx₄/dt = ic holds universally at every event (Convention I.5.2); over a coordinate-time interval ε the proper time elapsed along the worldline is dτ = ε/γ, where γ = (1 − v²/c²)^{−1/2} and v_{x₄} = c/γ is the Sphere-tangent velocity component. The rest-frame x₄-oscillation at the Compton frequency ω_C = mc²/ℏ (Convention I.5.4) therefore accumulates a phase per interval ε of*

$$\Delta\phi = \exp\!\left(\frac{i\, mc^2 \gamma^{-1}\, \epsilon}{\hbar}\right).$$

*In the non-relativistic limit v/c ≪ 1, the expansion γ⁻¹ ≈ 1 − v²/(2c²) gives*

$$mc^2\gamma^{-1} \approx mc^2 - \tfrac{1}{2}mv^2.$$

*The first term mc² is a global phase absorbed by rephasing; the second term −½mv² = −T is the negative kinetic energy. Adding a potential V(q) by minimal coupling yields the short-interval phase*

$$\Delta\phi = \exp\!\left(\frac{i\epsilon}{\hbar}(T - V)\right) = \exp\!\left(\frac{i\epsilon}{\hbar} L_{\mathrm{classical}}\right).$$

*Integrated over the path, the accumulated phase is*

$$\phi[\mathrm{path}] = \exp\!\left(\frac{i}{\hbar}\int L_{\mathrm{classical}}\,dt\right) = \exp\!\left(\frac{iS[\mathrm{path}]}{\hbar}\right).$$

[Cf. 10, Proposition L3.] The same factor $i\hbar$ that appears in the phase $\exp(iS/\hbar)$ is, in the operator language of §XIII.9, the multiplicative factor in the quantum McGucken operator $\hat{M} = i\hbar D_M$. The path-integral phase and the canonical-quantization $i\hbar$ are therefore two readings of the same source quantity: the perpendicularity marker $i$ in $D_M = \partial_t + ic\partial_{x_4}$ together with the quantum of $x_4$-oscillation $\hbar$ [76, 13]. The co-generation theorem of §XIII.10 establishes that the path-integral side and the operator-algebra side are not two separate formulations of quantum mechanics but two derivative consequences of the single source-pair $(\mathcal{M}_G, D_M)$.

**Proposition XII.4 (Feynman path integral as continuum limit).** *Composing the iterated Huygens propagation of Proposition XII.2 with the accumulated phase of Proposition XII.3 and taking N → ∞ yields*

$$K(q_f, t_f; q_i, t_i) = \int \mathcal{D}x(t)\, \exp\!\left(\frac{i}{\hbar}S[x(t)]\right).$$

*The Feynman path integral is therefore a theorem of dx₄/dt = ic.* [Cf. 10, Proposition L4.] **∎**

The four propositions together establish the formal derivation. What the author's statement above adds — and what the present section is centrally concerned with — is the *physical reading* of the formal result: the "every path" is the expanding null surface of the McGucken Sphere; the integration measure 𝒟x(t) is the geometric extent of that surface in 4D; the phase exp(iS/ℏ) is the accumulated x₄-advance along each path with i the perpendicularity marker of x₄ and ℏ the quantum of x₄'s oscillation.

### XII.4 The interpretation: every path is every point on x₄'s expanding nonlocality

The author's statement deserves explicit unpacking, as it captures the structural reading that distinguishes the McGucken account from all prior treatments of the path integral.

**The expanding surface of nonlocality.** In the McGucken dx₄/dt = ic framework, x₄'s spherically symmetric expansion at velocity ic from every event constitutes an expanding surface of nonlocality: every point on the wavefront Σ₊(A) is x₄-coincident with the emission event A, and therefore every point on the wavefront is, in the geometric sense of the First Law of Nonlocality [9], part of the same locality as A. The expansion is not "the photon moving away from A"; it is "the photon's geometric extent growing in 4D, with every point on the growing null surface continuing to share the original locality of A through x₄-coincidence."

**Every point on that nonlocality is the photon's path.** Because the photon is geometrically extended along the entire wavefront, and because every point on the wavefront is part of the same nonlocality as the emission event, the photon's "position" in the standard 3D-particle sense does not exist as a single point. The photon's position *is* the entire expanding null surface. Each point on the surface is, from the photon's geometric standpoint, equally its location.

**The 3D shadow.** Observers in 3D view the photon through the spatial slice Σ_t at their instantaneous time. The 3D cross-section of the McGucken Sphere is a 2-sphere of radius c(t − t_A) centered on A's spatial location. From the observer's restricted viewpoint, the photon appears to have "explored" every point on this 2-sphere — every spatial route from A to that point — because in 4D the photon was indeed geometrically present on the entire wavefront as it expanded through every such point.

**Every single possible radius.** The author's phrase "every single possible radius of the expanding sphere" captures the spatial-trajectory reading precisely. A radial line from A's spatial location to any point P on the 3D sphere of radius c(t − t_A) is a geometric path along which the wavefront passed through every intermediate radius r ∈ [0, c(t − t_A)]. The "every path" of Feynman is, in 3D, the continuum of radial trajectories along which the wavefront expanded — and the path integral's integration measure 𝒟x(t) is the angular continuum of these radii together with the temporal continuum of intermediate wavefronts.

This is the structural content of the McGucken reading of the path integral. The mystery of "why does nature compute amplitudes by integrating over all paths?" is answered: nature does not "compute" the path integral. Nature *is* the expanding wavefront. The path integral is the 3D shadow.

### XII.5 Reinforcement of Proposition III.1: the Born rule

The geometric reading of the path integral reinforces Proposition III.1 of §III in a structural respect. Proposition III.1 establishes the Born rule P = |ψ|² through three pieces — complex character of ψ from i as perpendicularity marker, quadratic exponent from C1–C4, and SO(3) Haar-measure shape from spherical symmetry. The path integral reading sharpens the third piece.

The amplitude ψ at a spatial point B at time t is, by the propagator construction, the path integral over all paths from A to B:

$$\psi(B,t) = \int \mathcal{D}x(t)\, \exp\!\left(\frac{i}{\hbar}S[x(t)]\right)\,\psi(A, t_A).$$

The probability density at B is |ψ(B,t)|². The geometric content: ψ(B,t) is the amplitude of the McGucken Sphere wavefront at the point B in 3D; |ψ(B,t)|² is the SO(3)-Haar-weighted geometric measure of the wavefront's contribution to the spherical expansion at the radius corresponding to B.

The forced character of the squared exponent now has a sharper structural source. The path integral's amplitude is a *complex* quantity because the phase exp(iS/ℏ) is complex; the i in the phase is the same i as in dx₄/dt = ic, the perpendicularity marker of x₄. The probability density must be a *real, positive* quantity formed from this complex amplitude. The unique rotation-invariant real positive density on the McGucken Sphere's wavefront cross-section is the squared modulus |ψ|² — and the path integral construction makes the geometric origin explicit: the squared modulus measures the wavefront's geometric "size" at the radius B, with the SO(3)-Haar measure providing the rotation-invariant weighting.

The path integral and the Born rule are thus two readings of the same geometric structure: the path integral computes ψ as the wavefront's amplitude at a point; the Born rule computes |ψ|² as the wavefront's geometric measure at that point. Both descend from dx₄/dt = ic; their consistency is automatic because they derive from the same structural facts.

### XII.6 Reinforcement of Proposition V.1: apparent collapse as cross-section reading

The geometric reading of the path integral also reinforces Proposition V.1, which establishes that apparent wave function collapse R is the 3D spatial cross-section reading of an x₄-extended state evolving unitarily.

In the path integral framework, the photon's "every path" is the entire wavefront of the McGucken Sphere — the expanding null surface in 4D. When the photon is detected at a specific pixel P on a screen, the standard interpretation of collapse asserts that the wavefunction has reduced from a spread state to a localized state at P. The McGucken dx₄/dt = ic framework rejects this interpretation: nothing has collapsed. The McGucken Sphere has simply intersected the detector's 3D spatial slice at the specific pixel P. Every other pixel on the screen was equally a point on the wavefront's geometric extent — every other pixel was a spatial location where the wavefront geometrically passed — but the observer's local cross-section at the moment of detection happened to intersect the wavefront at P rather than at another pixel.

The path integral makes this geometric reading vivid. The "every path" that contributes to the amplitude at each pixel is the same wavefront, viewed from the perspective of each pixel. The amplitude ψ(P, t) at pixel P is the path integral from A to P; the amplitude ψ(P', t) at any other pixel P' is the path integral from A to P'. Both are well-defined; both are non-zero (for non-shadowed pixels); both correspond to real geometric content of the wavefront at the corresponding radius. The observer's restricted access to the 3D cross-section at the detection moment selects one pixel — the one the wavefront's geometric centroid happens to land at, weighted by the Born-rule probability |ψ|² — but the others were equally part of the four-dimensional state.

The collapse therefore is not a separate dynamical event. It is the geometric fact that a 4D wavefront intersects a 3D spatial slice at one configuration, with the configuration determined by the SO(3)-Haar-weighted geometric extent of the wavefront. Proposition V.1 already establishes this; the path integral reading shows that the *every-path* construction of standard quantum mechanics is precisely the construction that gives the multi-radial geometric content from which the cross-section selection is made.

### XII.7 Reinforcement of Proposition VIII.1: nonlocality from the shared wavefront

The geometric reading of the path integral finally reinforces Proposition VIII.1, which establishes that quantum nonlocality is the geometric consequence of x₄-mediated correlation through the six-sense null-surface identity of the McGucken Sphere [9].

Two photons emitted in an entangled state from a common source share a common McGucken Sphere — they are at different points on the expanding null surface from the same emission event. The path integral for each photon is the integral over all paths from the source to that photon's detection event; both path integrals are integrals over the same wavefront, viewed from the perspective of each detection event.

The author's phrase — "x₄'s expansion represents an expanding nonlocality, and thus every point on that nonlocality is the photon's path" — applies *jointly* to both photons of an entangled pair. Both photons' "every paths" lie on the same expanding nonlocality. The correlations between their detection outcomes are not the result of faster-than-light signaling; they are the consequence of being two cross-sectional readings of the same 4D wavefront.

The path integral reading thereby supplies a vivid geometric content for Bell-type correlations: when Alice's photon "follows every path" and Bob's photon "follows every path," the geometric content is that both photons' paths lie on the same expanding McGucken Sphere from the source, and their detection events are two cross-sections of the same 4D structure. The cos²(θ/2) angular dependence of the correlations is the SO(3)-Haar measure on the angular relationship between the two cross-sections — the same Haar measure that grounds the Born rule in Proposition III.1 and that grounds the path-integral measure in Proposition XII.4.

### XII.8 The Wick rotation: path integral, Brownian motion, and Huygens unified

The path integral derivation of §XII.3 has an immediate companion in the McGucken treatment of Wick rotation [31]. Under the substitution t → −iτ — equivalently, x₄ = ict → x₄ = cτ, replacing the imaginary fourth axis with a real Euclidean axis — the oscillatory phase exp(iS/ℏ) becomes the real Gaussian weight exp(−S_E/ℏ), where S_E is the Euclidean action. The Feynman path integral in real time becomes the diffusion kernel summing over Brownian paths in imaginary time.

The structural identification is striking: the Feynman path integral (quantum, real time), Brownian motion (thermal, imaginary time), and Huygens' wavelet construction (wave, geometric optics) are *the same geometric object* — spherically symmetric propagation in four-dimensional spacetime whose fourth axis advances at c. The three regimes are related by the analytic continuation x₄ = ict that *is* the McGucken Principle.

This unification grounds the structural reading further. The "every path" of Feynman is not a peculiar feature of quantum mechanics that has no classical analog — it is the same spherically symmetric expansion of x₄ that produces classical Huygens wavefronts in optics and diffusive paths in thermodynamics. The three readings differ only in the analytic-continuation status of x₄: imaginary x₄ (i.e., x₄ = ict) gives quantum interference; real x₄ (i.e., x₄ = cτ) gives Brownian diffusion; the SO(3) symmetry shared by both gives Huygens' wavefront construction in either regime.

### XII.9 Comparison with Feynman's original interpretation

Feynman's 1948 paper introduced the path integral as a postulate derived from Dirac's 1933 hint that the quantum amplitude is "analogous to" exp(iS/ℏ). Feynman did not claim a foundational source for the procedure; he treated it as an alternative axiomatization of quantum mechanics that recovered the Schrödinger equation in the short-time limit. Later treatments (e.g., Glimm and Jaffe's *Quantum Physics*; Zinn-Justin's *Quantum Field Theory and Critical Phenomena*; Polyakov's *Gauge Fields and Strings*) take the path integral as primitive and develop quantum field theory upon it.

In the McGucken dx₄/dt = ic framework, the path integral is not a postulate — it is a theorem of dx₄/dt = ic, with the four-proposition derivation of §XII.3 supplying the formal chain. Beyond the formal derivation, the geometric reading of "every path" supplies the physical content that Feynman's original presentation lacked: the path integral is the 3D shadow of the 4D McGucken Sphere's expanding null surface, with the integration measure recording the surface's geometric extent and the phase recording the accumulated x₄-advance along each path.

This is structurally superior to Feynman's original interpretation in three respects, parallel to the three structural improvements identified for the Born rule in §III.3:

**(a)** The path integral acquires a foundational source. Where Feynman could only claim the procedure is consistent with experiment, the McGucken dx₄/dt = ic framework derives it from a single geometric postulate.

**(b)** The integration measure 𝒟x(t) acquires geometric content. Where standard treatments leave the measure as a formal symbol whose mathematical rigor remains contested (the path integral's measure-theoretic status is one of the open problems of mathematical physics), the McGucken dx₄/dt = ic framework identifies the measure as the geometric extent of the McGucken Sphere's expanding wavefront in 4D — a concrete, geometrically well-defined object.

**(c)** The phase exp(iS/ℏ) acquires geometric content. Where Feynman could only assert that the phase is exp(iS/ℏ), the McGucken dx₄/dt = ic framework derives it as the accumulated x₄-advance, with i the perpendicularity marker of x₄ and ℏ the quantum of x₄'s oscillation [76, 77]. The phase is not an arbitrary formal weighting; it records a geometric fact about the manifold.

### XII.10 The path integral as theorem: structural placement in the present paper

The path integral has been treated as a theorem of dx₄/dt = ic since [6, Theorem 15]. The present section adds three things to the prior treatment:

**(i)** The formal four-proposition derivation is restated in the structural language of the present paper, with cross-references to Propositions III.1, V.1, and VIII.1.

**(ii)** The author's novel geometric reading — "every point on the expanding nonlocality is the photon's path" — is preserved verbatim and developed as the substantive interpretive content. This reading is, to the author's knowledge, original to the McGucken dx₄/dt = ic framework: no prior treatment of the path integral identifies the "every path" with the wavefront of an expanding fourth-dimensional null surface, or identifies the integration measure with the SO(3)-Haar-weighted geometric extent of that surface.

**(iii)** The reading is shown to reinforce three of the central propositions of the paper — the Born rule (Proposition III.1), the apparent-collapse-as-cross-section-reading (Proposition V.1), and the nonlocality-from-null-surface-identity (Proposition VIII.1) — by supplying a single geometric mechanism that unifies them.

The structural significance is that the path integral, the Born rule, the apparent collapse, and quantum nonlocality are *not four independent features of quantum mechanics*. They are four readings of one geometric fact: x₄ expands at velocity ic from every event, producing a spherically symmetric expanding null surface — the McGucken Sphere — whose geometric extent in 4D is the integration measure of the path integral, whose squared amplitude is the Born rule's probability density, whose 3D cross-section is the apparent collapse, and whose null-surface identity is the source of quantum nonlocality.

### XII.11 Summary

The Feynman path integral's "every path" is, in the McGucken dx₄/dt = ic framework, the geometric extent of the expanding McGucken Sphere — the spherically symmetric null surface that x₄'s expansion at velocity ic creates from every emission event. Every point on this surface is, by the geometric structure of dx₄/dt = ic, a point of the expanding nonlocality of the emission event. The photon's geometric extent in 4D is the entire surface; the photon's "every path" in the 3D shadow is the projection of this surface onto the observer's spatial slice.

This reading dissolves the eighty-year mystery of "why does nature compute by summing over histories?" The answer is that nature is not computing. Nature is the wavefront. The histories are radii of the expanding sphere; the integration measure is the SO(3)-Haar-weighted geometric extent of the wavefront; the phase is the accumulated x₄-advance with i the perpendicularity marker. The path integral is the 3D shadow of the 4D geometric fact dx₄/dt = ic.

The reading reinforces the joint-derivation argument of §XI: the Born rule (Proposition III.1), the superposition principle (Proposition IV.1), the apparent collapse (Proposition V.1), the irreversibility (Proposition VI.1), the preferred basis (Proposition VII.1), the nonlocality (Proposition VIII.1), the absence of a separate (R) law (Proposition IX.1), and now the path integral itself — eight foundational features of quantum mechanics, all theorems of one geometric principle. The structural reduction continues: where standard quantum mechanics presents these as eight independent features requiring eight independent foundational accounts, the McGucken dx₄/dt = ic framework presents them as eight readings of one geometric fact.

The path integral has been the calculational backbone of quantum field theory for eighty years. It has had no foundational source. The McGucken dx₄/dt = ic framework supplies one — and supplies, with it, the physical content that Feynman acknowledged was missing from his own formulation: the photon really does follow every path, because every point on x₄'s expanding nonlocality is the photon's path, and the photon's position is always on the expanding surface of nonlocality.

---

---

## XIII. Hilbert Space Itself as Derived Structure

The previous section established that linearity (Q1) and the Born rule (Q3) are jointly derived from dx₄/dt = ic. The present section develops a deeper structural claim: not only are the *postulates* about Hilbert space derived, but the Hilbert-space *framework itself* — its complex scalar field, its specific carrier space for any given physical system, its inner-product structure, and its primacy among representations of quantum dynamics — is forced by the same geometric principle, with no independent axiomatic content.

This is the strongest form of the structural reduction the McGucken dx₄/dt = ic framework accomplishes. Standard quantum mechanics begins by postulating Hilbert space as a foundational mathematical structure and then unfolds physics within it. The McGucken framework reverses this order: physics begins with dx₄/dt = ic, and Hilbert space emerges as the natural representation space for the algebraic-symmetry channel of this principle. The Hilbert space is not where physics happens; it is one of several equivalent representation spaces in which the consequences of x₄'s spherical expansion can be formulated.

### XIII.1 The standard role of Hilbert space and its puzzles

In standard quantum mechanics, the Hilbert-space framework appears as postulate (Q1) of the Dirac–von Neumann axiomatic system: the state of an isolated physical system is represented by a unit vector |ψ⟩ in a complex separable Hilbert space ℋ, defined up to overall phase. This postulate has remained foundational across ninety years of quantum-mechanical development, and several distinct puzzles attach to it.

**Puzzle 1: Why complex Hilbert space, rather than real or quaternionic?** Real Hilbert spaces and quaternionic Hilbert spaces are mathematically well-defined alternatives; both have been explored as candidate foundations for quantum mechanics. The standard answer for the choice of complex scalars invokes Stueckelberg's theorem (the absence of certain superselection rules requires complex amplitudes) or various reconstruction arguments [78; 79] that derive complex Hilbert space from operational axioms. None of these arguments traces the choice of ℂ as the scalar field to a deeper physical principle.

**Puzzle 2: Which Hilbert space for a given physical system?** The textbook procedure is to write down the appropriate Hilbert space for each system: L²(ℝ³) for a spinless particle, ℂ² ⊗ L²(ℝ³) for a spin-½ particle, Fock space for a quantum field. Each choice is justified after the fact by matching to experiment, not derived from a foundational principle. The connection between the physical system and its Hilbert space is operationally clear but foundationally opaque.

**Puzzle 3: The probability/amplitude category mismatch.** Wavefunctions are complex-valued amplitudes; measurement outcomes are real-valued probabilities. The Born rule P = |⟨a|ψ⟩|² is the bridge that converts amplitudes to probabilities, and the bridge is taken as a separate axiom (Q3) in the standard formalism. Why amplitudes-then-probabilities rather than probabilities directly? Why squared modulus rather than some other functional form? The standard formalism gives no foundational answer.

**Puzzle 4: The status of Hilbert-space formulation among multiple equivalent formulations.** Hilbert-space quantum mechanics is one of several mathematically equivalent formulations of quantum dynamics: the Hamiltonian operator formulation (Schrödinger / Heisenberg), the Lagrangian path-integral formulation (Feynman), the algebraic C\*-algebra formulation (Haag–Kastler / Segal), the categorical formulation (Selinger / Abramsky / Coecke). All four formulations agree on empirical predictions, but standard quantum mechanics treats Hilbert space as primary and the others as derived. There is no foundational reason for this hierarchy in the standard treatment.

The McGucken dx₄/dt = ic framework supplies foundational answers to all four puzzles.

### XIII.2 Proposition XIII.1 (Hilbert space is forced, not postulated)

**Proposition XIII.1 (The Hilbert-space framework is a Grade-2 theorem of dx₄/dt = ic).** *The standard postulate (Q1) — that quantum states are unit vectors in a complex separable Hilbert space — is replaced in the McGucken dx₄/dt = ic framework by a derived theorem (Q1′): the Hilbert-space structure is forced by the requirement that McGucken-wavefronts form a linear vector space under superposition (Proposition IV.1), with the inner product ⟨ψ|φ⟩ supplied by the Born-rule interpretation of cross-section overlap (Proposition III.1). The complex separable Hilbert space is the natural carrier for the wavefronts of x₄'s spherical expansion, not an axiomatic input.*

**Proof.** The proof has four pieces, each addressing one of the structural elements of the Hilbert-space framework.

#### Piece 1: The vector-space structure is forced by superposition

By Proposition IV.1 (the superposition theorem), the geometric overlap of two McGucken-Sphere wavefronts ψ, φ at each spacetime point is the linear combination αψ + βφ with complex coefficients α, β ∈ ℂ. Linear addition with complex coefficients is the unique combination operation respecting the four conditions (D1) SO(3) Haar-equivariance, (D2) Lorentz-covariance, (D3) linearity in each argument, and (D4) Born-rule compatibility (Piece 2 of Proposition IV.1's proof).

The set of all McGucken-Sphere wavefronts on a spatial slice Σ_t therefore forms a vector space over ℂ: it is closed under the linear-addition operation forced by Proposition IV.1, and the operation satisfies the standard vector-space axioms (associativity, commutativity, identity, inverse, distributivity over scalar multiplication) automatically. The vector-space structure is not an axiomatic input — it is the algebraic content of the geometric overlap of wavefronts.

#### Piece 2: The complex scalar field is forced by x₄'s perpendicularity

By Convention I.5.2, x₄ = ict, with the i the perpendicularity marker of the fourth dimension relative to the spatial three. By Proposition III.1's Piece 1 and Proposition IV.1's Piece 3, the i in the wavefunction ψ is the same i: it is the algebraic marker of the wavefunction's component along x₄, perpendicular to the spatial-three projection.

Real Hilbert spaces are insufficient because real-valued wavefunctions cannot encode the relative-phase information required for interference patterns (Proposition IV.1's Piece 3). Quaternionic Hilbert spaces are unnecessary because the relative-phase information is fully captured by a single i; a second perpendicular axis (j or k) would require a fifth dimension perpendicular to the four of (x, x₂, x₃, x₄), which dx₄/dt = ic does not provide. The choice of ℂ as the scalar field is therefore *forced*: the McGucken Principle gives one perpendicularity marker (i), which produces one complex structure, which produces a complex Hilbert space.

This dissolves Puzzle 1 of §XIII.1. The choice of ℂ over ℝ or ℍ is not an operational consequence of avoiding superselection rules but a direct consequence of the geometric structure of the McGucken Principle: the i is the perpendicularity marker of x₄ = ict.

#### Piece 3: The inner-product structure is forced by Born-rule cross-section overlap

By Proposition III.1 (the Born rule), the probability density of finding a quantum particle at spatial position x given wavefunction ψ is |ψ(x)|² = ψ\*(x) ψ(x), with the squared exponent forced by positivity, normalization, superposition, and Lorentz-covariance. The total probability of finding the particle anywhere is

  ∫ |ψ(x)|² d³x = ⟨ψ|ψ⟩ = 1.

For two wavefunctions ψ, φ, the overlap integral

  ⟨ψ|φ⟩ = ∫ ψ\*(x) φ(x) d³x

is the natural sesquilinear form that measures the geometric correspondence between two McGucken-Sphere cross-sections at spatial slice Σ_t. The properties required of an inner product — sesquilinearity (linear in the second argument, conjugate-linear in the first), positive-definiteness (⟨ψ|ψ⟩ ≥ 0 with equality iff ψ = 0), and conjugate symmetry (⟨ψ|φ⟩ = ⟨φ|ψ⟩\*) — all follow from the Born-rule interpretation: positive-definiteness from the positivity of probability density (C1 of Proposition III.1), sesquilinearity from the linearity of complex addition combined with the conjugation in the squared-modulus form (C3 of Proposition III.1), and conjugate symmetry from the reality of the squared-modulus.

The inner-product structure of Hilbert space is therefore not an additional axiom — it is the algebraic content of cross-section overlap of McGucken-Sphere wavefronts under the Born-rule interpretation. This dissolves Puzzle 3 of §XIII.1: the probability/amplitude category mismatch is not a mismatch at all; the inner product ⟨ψ|φ⟩ is the natural geometric measure of wavefront overlap, with the squared-modulus structure forced by the four conditions of Proposition III.1.

#### Piece 4: Separability is forced by the spatial-slice geometry

Separability of the Hilbert space — the existence of a countable dense subset — follows from the topology of the spatial slice Σ_t, which is a smooth four-dimensional Lorentzian manifold of bounded local geometry (Convention I.5.1). For McGucken-Sphere wavefronts on Σ_t, square-integrable functions on bounded spatial domains form a separable Hilbert space by the Stone–Weierstrass theorem. The separability is therefore a structural feature inherited from the smooth-manifold structure of spacetime, not an additional axiomatic input.

The four pieces together establish that the Hilbert-space framework — vector space structure, complex scalar field, inner-product structure, and separability — is forced by the geometric content of dx₄/dt = ic together with Propositions III.1 (Born) and IV.1 (superposition). No independent axiomatic content is required. **∎**

### XIII.3 Proposition XIII.2 (Which Hilbert space is forced for which physical system)

**Proposition XIII.2 (The specific Hilbert space for any given physical system is forced by the geometric structure of the McGucken-Sphere wavefront for that system).** *The textbook choices L²(ℝ³) for a spinless particle, ℂ² ⊗ L²(ℝ³) for a spin-½ particle, and Fock space for a quantum field are not made by hand — each is forced by the geometric structure of the McGucken-Sphere wavefront for the system in question.*

**Proof.** We establish the three cases.

#### Spinless particle: L²(ℝ³)

For a spinless particle of rest mass m, the McGucken-Sphere wavefront is a complex-valued function ψ(x, t) on the spatial slice Σ_t, with the Compton-frequency phase e^(−imc²t/ℏ) characterizing the rest-mass advance along x₄ (Convention I.5.4 and Proposition VII.1 of [6, Theorem 4]). The Born-rule normalization (Proposition III.1) requires ∫ |ψ|² d³x = 1, restricting ψ to be square-integrable. The natural Hilbert space is therefore L²(ℝ³), the space of square-integrable complex-valued functions on three-dimensional space.

The smoothness of ψ (required by Schrödinger evolution and by the smoothness of x₄'s expansion) restricts ψ further to a dense subspace of L²(ℝ³), but the Hilbert-space completion is L²(ℝ³) itself. No additional structure is required.

#### Spin-½ particle: ℂ² ⊗ L²(ℝ³)

For a spin-½ particle, the Dirac equation [6, Theorem 9] establishes that the wavefunction is a four-component spinor on spacetime. In the non-relativistic limit, the four-component spinor reduces to a two-component spinor on the spatial slice, with the two components corresponding to the two eigenstates of the spin angular momentum operator along any chosen axis.

The two-component structure is forced by the 4π-periodicity of fermion rotation, which is the geometric signature of x₄-rotation under the Clifford algebra of Minkowski space ℝ^{1,3} [6, Theorem 9, §VIII Doran-Lasenby calculation]. Specifically: a rotation of the spatial three through angle θ about any axis corresponds to a rotation of the four-dimensional state through angle θ/2 in the Clifford-algebra representation, so a 2π rotation of the spatial three is a π rotation of the four-dimensional state, and a 4π rotation of the spatial three is the first 2π rotation of the four-dimensional state. The factor of 2 is the geometric signature of the half-integer angular-momentum representation — the spin-½ representation of SU(2) ≅ Spin(3), which is the double cover of SO(3).

The two-component spinor structure is therefore forced by the Clifford-algebra geometry of x₄-rotation, not chosen by hand. The Hilbert space ℂ² ⊗ L²(ℝ³) is the natural carrier for two-component spinors of spatially square-integrable wavefronts: the ℂ² factor for the spin-½ degree of freedom, the L²(ℝ³) factor for the spatial wavefunction, and the tensor product reflecting the independence of these two degrees of freedom.

For higher-spin systems (spin-1, spin-3/2, spin-2), the corresponding Hilbert-space tensor factors are forced by the corresponding higher-dimensional Clifford-algebra representations of x₄-rotation, all derived in the same manner.

#### Quantum field: Fock space

For a quantum field — a system describing a variable number of identical particles — the natural Hilbert space is Fock space, the direct sum of all symmetric or antisymmetric tensor products of the single-particle Hilbert space. The structure is forced by canonical quantization of the matter-field sector of the McGucken Lagrangian ℒ_McG [6, Theorem 20], with the multiplicative composition of independent McGucken-wavefronts producing the tensor-product structure and the spin-statistics theorem (forced by Lorentz-covariance combined with the Clifford-algebra structure of x₄-rotation, [6, Theorem 20]) selecting symmetric (bosonic) or antisymmetric (fermionic) tensor products.

The spin-statistics theorem itself is a forced consequence of the McGucken Principle: integer-spin particles (whose four-dimensional rotation has 2π-periodicity) require symmetric multi-particle states to be Lorentz-covariant; half-integer-spin particles (whose four-dimensional rotation has 4π-periodicity) require antisymmetric multi-particle states. The Pauli exclusion principle for fermions follows from the antisymmetric Fock-space structure.

The three cases together establish that the textbook Hilbert spaces are not chosen by hand — each is forced by the geometric structure of the McGucken-Sphere wavefront for the system in question. This dissolves Puzzle 2 of §XIII.1: the "which Hilbert space?" problem has a foundational answer in the McGucken dx₄/dt = ic framework, with each choice forced by the corresponding geometric content. **∎**

### XIII.4 Proposition XIII.3 (Hilbert space as one of several equivalent representation spaces)

**Proposition XIII.3 (The Hilbert-space formulation is one of several mathematically equivalent representations of the McGucken Principle).** *The Hilbert-space formulation, the Lagrangian path-integral formulation, the algebraic C*-algebra formulation, and the categorical formulation of quantum mechanics are not a hierarchy with Hilbert space at the top but four equivalent representation spaces, each natural for a different channel of the dual-channel content of dx₄/dt = ic. The Hilbert space is the natural carrier for the algebraic-symmetry channel (Channel A); the path-integral kernel is the natural carrier for the geometric-propagation channel (Channel B); the C\*-algebra is the natural carrier for the operator-algebraic channel; the categorical formulation is the natural carrier for the structural-relational channel.*

**Proof.** From Convention I.5.5 and [27, §V.1], dx₄/dt = ic has dual-channel content: Channel A (algebraic-symmetry), driven by invariance under spacetime isometries, producing Stone's theorem and the Wigner classification; Channel B (geometric-propagation), driven by spherical expansion from every event, producing Huygens' principle and the Feynman path integral.

Each channel admits a natural representation space.

**Channel A: Hilbert space.** The algebraic-symmetry content of dx₄/dt = ic — invariance under the isometries of Minkowski spacetime, with the Poincaré group acting on physical states — is naturally represented in a Hilbert space, with self-adjoint operators representing the generators of symmetries (energy, momentum, angular momentum, boost generators) and unitary operators representing the symmetry transformations themselves. Stone's theorem [6, Theorem 10] establishes that the one-parameter unitary groups generated by self-adjoint operators are the natural representations of the spacetime translation group; the Wigner classification establishes that irreducible unitary representations of the Poincaré group correspond to particle types (mass, spin). The Hilbert-space formulation is the natural representation of Channel A.

**Channel B: Path-integral kernel.** The geometric-propagation content of dx₄/dt = ic — Huygens-style spherical expansion of wavefronts from every spacetime event, with secondary wavefronts at each point of a primary wavefront — is naturally represented as a sum over paths from initial to final spacetime events, with each path weighted by exp(iS/ℏ) where S is the classical action along the path [6, Theorem 15]. The path-integral kernel K(x_f, t_f; x_i, t_i) is the McGucken-Sphere amplitude from initial to final events, integrated over all four-dimensional histories connecting them. The path-integral formulation is the natural representation of Channel B.

**Equivalence.** The Hilbert-space and path-integral formulations are mathematically equivalent: the path-integral kernel K(x_f, t_f; x_i, t_i) equals the matrix element ⟨x_f| exp(−iH(t_f − t_i)/ℏ) |x_i⟩ of the Hilbert-space evolution operator. The equivalence is the dual-channel correspondence: the algebraic-symmetry content (Hilbert-space evolution) and the geometric-propagation content (path-integral sum) are two readings of the same physical fact — that x₄ is advancing at rate ic from every event, with the consequences manifesting algebraically in Channel A and geometrically in Channel B.

**C\*-algebra and categorical formulations.** The algebraic and categorical formulations are further representations of the same dual-channel content. The C\*-algebraic formulation (Haag–Kastler, Segal) takes observables as elements of a C\*-algebra and states as positive linear functionals; the GNS construction establishes that any C\*-algebra with a state can be represented as a Hilbert space with a vector state, recovering the Hilbert-space formulation. The categorical formulation (Selinger, Abramsky, Coecke) takes dagger-compact closed categories as primitive and recovers Hilbert space as a specific model.

In the McGucken dx₄/dt = ic framework, all four formulations are descent images of the same underlying geometric content. The Hilbert-space formulation is one model among several, not foundationally privileged. This dissolves Puzzle 4 of §XIII.1: there is no hierarchy with Hilbert space at the top, only a dual-channel structure with multiple equivalent representations. **∎**

### XIII.5 The McGucken Space ℳ_G as source-space and the structural setting for orthogonality

Before stating the orthogonality result, we record the structural setting that makes the result possible. The McGucken Space framework [12] — the source-space ℳ_G generated by dx₄/dt = ic — establishes the universal derivability principle: every mathematically meaningful physical space is derivable from ℳ_G by a finite sequence of admissible physical-space operations.

The McGucken Space is defined as the structured arena

$$\mathcal{M}_G \;=\; (E^4,\, \Phi_M,\, D_M,\, \Sigma_M),$$

where E⁴ is the four-coordinate Euclidean carrier, Φ_M = x₄ − ict is the McGucken constraint function, D_M = ∂_t + ic ∂_{x₄} is the McGucken flow operator, and Σ_M is the spherical wavefront propagation structure. By Theorem 12.1 of [12] (the Hilbert-space emergence theorem), Hilbert space ℋ arises as the completion of the McGucken-derived complex inner-product amplitude space:

$$\mathcal{M}_G \;\longrightarrow\; M^{1,3} \;\longrightarrow\; \mathcal{V} \;\longrightarrow\; \mathcal{H},$$

where M^{1,3} = Φ_M^{−1}(0) is the Lorentzian spacetime obtained as the constraint surface of ℳ_G, 𝒱 is the pre-Hilbert space of complex amplitudes ψ : Σ_t → ℂ over a spatial slice of M^{1,3}, and ℋ = 𝒱̄ is the Hilbert completion under the Born inner product ⟨ψ, φ⟩ = ∫ ψ*(x) φ(x) d³x.

The structural fact that follows from this derivation is that *every feature of the Hilbert space is inherited from a feature of ℳ_G*. The complex character of amplitudes is inherited from the i in dx₄/dt = ic. The vector-space structure (linearity) is inherited from the spherical wavefront superposition supplied by Σ_M and forced by Proposition IV.1. The norm and inner product are inherited from the Born density on the SO(3)-symmetric wavefront cross-section of Σ_M and forced by Proposition III.1. The completion to a full Hilbert space is the standard topological closure under the inherited norm.

What has not yet been addressed in the paper is *orthogonality* — the structure that distinguishes physically distinguishable states within the Hilbert space. Standard quantum mechanics treats orthogonality as a primitive feature of the postulated inner product, with the link between mathematical orthogonality (⟨a|b⟩ = 0) and physical distinguishability (mutually exclusive measurement outcomes) asserted as part of the spectral-theorem combination of (Q2) and (Q3). Neither feature is derived from anything more fundamental; both are postulated.

The McGucken Space framework provides the missing derivation. The next subsection establishes that orthogonality and the inner product itself are theorems of dx₄/dt = ic, descending through ℳ_G via the same SO(3) symmetry that grounds the Born rule and the superposition principle. The inner-product apparatus of Hilbert space — sesquilinear form, complex conjugation in the first slot, integration measure, orthogonality structure, normalization — is shown to be a single geometric object descending from one structural source.

### XIII.6 Proposition XIII.4 (The Hilbert-space inner product and orthogonality as theorems of dx₄/dt = ic)

**Proposition XIII.4 (The Hilbert-space inner product, complex conjugation, and orthogonality structure are theorems of dx₄/dt = ic).** *Let ℋ be the Hilbert space of square-integrable complex amplitudes over the McGucken-derived spatial slice Σ_t ⊂ M^{1,3} = Φ_M^{−1}(0). Then the sesquilinear inner product*

$$\langle \psi_a \mid \psi_b \rangle \;=\; \int_{\Sigma_t} \overline{\psi_a(x)}\, \psi_b(x)\, d^3x$$

*is forced — uniquely up to overall normalization — by three structural facts about ℳ_G: (i) the SO(3) rotational symmetry of x₄'s spherically symmetric expansion; (ii) the U(1) phase symmetry inherited from the perpendicularity marker i in dx₄/dt = ic; and (iii) the conservation of total probability under unitary evolution, which descends from the smoothness of x₄'s expansion. The orthogonality relation ⟨ψ_a | ψ_b⟩ = 0 between two physical states is forced to coincide with the physical distinguishability of their measurement outcomes by the cross-section reading of Proposition V.1. No separate axiomatic content is required for either the inner product, the complex conjugation in the first slot, or the orthogonality–distinguishability link. All three descend from dx₄/dt = ic together with Propositions III.1 and IV.1.*

**Proof.** The proof proceeds through four structural pieces.

**Piece 1 — The SO(3) Haar measure as the unique rotation-invariant pairing.** The McGucken Sphere Σ_M(p, t) — the spherically symmetric wavefront expanding from event p at velocity ic — has SO(3) rotational symmetry about the spatial location of p (Convention I.5.2). Every direction in 3-space is equivalent under x₄'s expansion; no direction is preferred. By Proposition III.1 (Piece 3), this SO(3) symmetry forces the unique rotation-invariant probability measure on the wavefront cross-section to be the SO(3)-Haar measure, which produces the integration measure d³x on the spatial slice Σ_t.

A pairing operation between two complex amplitudes ψ_a(x) and ψ_b(x) must respect this SO(3) symmetry — under any rotation R ∈ SO(3) that takes the spatial slice to itself, the pairing must be invariant:

$$\langle R \psi_a \mid R \psi_b \rangle \;=\; \langle \psi_a \mid \psi_b \rangle.$$

The unique rotation-invariant pairing of complex-valued functions over the wavefront cross-section is the integration of their pointwise product against the SO(3)-Haar measure. The general form is

$$\langle \psi_a \mid \psi_b \rangle \;=\; \int_{\Sigma_t} f(\psi_a(x), \psi_b(x))\, d^3x,$$

where f is some function of the two complex values at each point. The integration measure d³x is forced as the SO(3)-Haar measure; what remains to be determined is f.

**Piece 2 — The U(1) phase symmetry forces sesquilinearity (complex conjugation in the first slot).** The perpendicularity marker i in dx₄/dt = ic encodes a U(1) phase symmetry of the McGucken framework: rotation of x₄ by an arbitrary phase α — equivalently, multiplication of all complex amplitudes by e^{iα} — leaves the geometric content invariant, since the i records orientation in the direction perpendicular to the three spatial dimensions and a rotation in that perpendicular direction is unobservable from the 3D cross-section.

A pairing f(ψ_a, ψ_b) must respect this U(1) phase symmetry under *relative* phase, not just global phase. The relevant requirement is:

(U1) Global phase invariance: f(e^{iα} ψ_a, e^{iα} ψ_b) = f(ψ_a, ψ_b), so that the U(1) symmetry of x₄ leaves the pairing invariant.

(U2) Bilinearity in physical superposition: f(α_1 ψ_1 + α_2 ψ_2, ψ_b) must reduce in some natural way to a combination of f(ψ_1, ψ_b) and f(ψ_2, ψ_b), to preserve the linearity of superposition forced by Proposition IV.1.

(U3) Real-valuedness of the diagonal: f(ψ, ψ) must be real-valued, so that ‖ψ‖² = ⟨ψ|ψ⟩ is a real positive quantity — this is forced by Born-rule compatibility (Proposition III.1, Piece 2: the squared exponent of |ψ|² as positive probability density).

The candidate forms of f are:

(a) **Bilinear**: f(ψ_a, ψ_b) = ψ_a(x) ψ_b(x). This satisfies (U2) but fails (U1): under e^{iα} rotation, f → e^{2iα} f, which is not invariant. It also fails (U3): ψ²(x) is complex in general, not real.

(b) **Sesquilinear with conjugation in the first slot**: f(ψ_a, ψ_b) = ψ_a*(x) ψ_b(x). Under e^{iα} rotation: ψ_a → e^{iα} ψ_a so ψ_a* → e^{−iα} ψ_a*; therefore f → e^{−iα} ψ_a*(x) e^{iα} ψ_b(x) = ψ_a*(x) ψ_b(x), invariant. (U1) is satisfied. The diagonal f(ψ, ψ) = |ψ(x)|² is real-positive, so (U3) is satisfied. (U2) is satisfied: f(α_1 ψ_1 + α_2 ψ_2, ψ_b) = α_1* f(ψ_1, ψ_b) + α_2* f(ψ_2, ψ_b), with conjugate-linearity in the first slot reflecting the complex-conjugation requirement.

(c) **Sesquilinear with conjugation in the second slot**: f(ψ_a, ψ_b) = ψ_a(x) ψ_b*(x). This is the convention used in some physics texts. It is equivalent to (b) up to relabeling of the slots; the structural content is identical.

(d) **Real bilinear forms**: f(ψ_a, ψ_b) = Re[ψ_a*(x) ψ_b(x)] or Im[ψ_a*(x) ψ_b(x)]. Each of these is a real-valued real-bilinear form. They fail to encode the *phase* relationship between ψ_a and ψ_b — the imaginary part of the inner product, which is essential for distinguishing states with the same |ψ|² distribution but different phase patterns. These candidates are eliminated because they cannot resolve states that differ only in their relative phase, which is physically meaningful (e.g., interference patterns in the double-slit experiment depend on relative phase, not just amplitude).

Candidates (a) and (d) are eliminated by U(1) invariance and by the need to encode phase information. Candidates (b) and (c) are equivalent up to slot-labeling. The forced form of the pairing is therefore the sesquilinear inner product

$$\langle \psi_a \mid \psi_b \rangle \;=\; \int_{\Sigma_t} \overline{\psi_a(x)}\, \psi_b(x)\, d^3x,$$

with the complex conjugation in the first slot forced by U(1) phase symmetry of x₄.

**Piece 3 — Conservation of probability forces the normalization condition.** The smoothness of x₄'s expansion (established as a structural commitment in Proposition X.1) requires that the total probability ∫ |ψ(x)|² d³x be conserved under unitary evolution: if ψ(x, t) is normalized at one time, ‖ψ(t)‖² = 1, then by smoothness it must remain normalized at all later times. This is the same smoothness condition that grounds Proposition X.1 (information preservation as a theorem of x₄'s smoothness).

Conservation of probability requires that the inner product be positive-definite on the diagonal: ⟨ψ|ψ⟩ ≥ 0 for all ψ, with equality iff ψ = 0 almost everywhere. The sesquilinear form derived in Piece 2 satisfies this automatically: ⟨ψ|ψ⟩ = ∫ |ψ(x)|² d³x ≥ 0 with equality iff |ψ(x)|² = 0 almost everywhere on Σ_t, i.e., iff ψ = 0 in L².

The normalization condition ‖ψ‖² = ⟨ψ|ψ⟩ = 1 is therefore inherited from the Born rule — it is the same SO(3)-Haar-weighted integral that defines the probability density of Proposition III.1, with the constraint that the total probability over the wavefront cross-section sum to unity. The norm is not an independent structural feature of ℋ; it is the Born rule applied to the diagonal of the inner product.

**Piece 4 — Orthogonality as null geometric overlap, with the cross-section reading establishing physical distinguishability.** With the inner product forced as in Pieces 1–3, two physical states ψ_a and ψ_b are *mathematically orthogonal* iff

$$\langle \psi_a \mid \psi_b \rangle \;=\; \int_{\Sigma_t} \overline{\psi_a(x)}\, \psi_b(x)\, d^3x \;=\; 0.$$

Geometrically, this is the statement that the two wavefront configurations on the McGucken Sphere have *null geometric overlap* in the SO(3)-Haar-weighted sense: their amplitude-product, when integrated against the rotation-invariant measure over the spatial slice, vanishes. The two configurations are "geometrically disjoint" on the wavefront in the precise sense that the Haar-weighted pairing of their complex amplitudes integrates to zero.

To establish that mathematical orthogonality coincides with *physical distinguishability* (mutually exclusive measurement outcomes), we apply Proposition V.1 (apparent collapse as 3D cross-section reading). By Proposition V.1, the configuration that an observer at spatial location x_obs at time t accesses is determined by the SO(3)-Haar-weighted geometric size of each branch at that location. Two states ψ_a and ψ_b correspond to two branches of the four-dimensional state, and the observer's local cross-section at x_obs intersects one branch or the other in the proportion fixed by their Haar-weighted sizes.

If ⟨ψ_a | ψ_b⟩ = 0, the two branches have null Haar-weighted overlap on the wavefront cross-section. By the projection structure of Proposition V.1, the observer's local cross-section that intersects branch a *cannot simultaneously intersect* branch b — the two configurations occupy disjoint regions of the wavefront in the SO(3)-Haar-weighted measure, and the projection π_{x_obs} : ℋ → ℋ_{loc} maps onto the branch the observer's spatial slice intersects. The probability of accessing branch b given that the observer accesses branch a is

$$P(b \mid a) \;=\; \frac{|\langle \psi_a \mid \psi_b \rangle|^2}{\|\psi_a\|^2 \|\psi_b\|^2} \;=\; 0.$$

This is the formal expression of physical distinguishability: an observer who accesses configuration a will *never* simultaneously access configuration b. Mathematical orthogonality (⟨ψ_a | ψ_b⟩ = 0) and physical distinguishability (P(b | a) = 0) are therefore identified at the level of the wavefront's geometric structure. They are not separately postulated; they are two readings of one geometric fact about how SO(3)-Haar-weighted wavefront configurations decompose under the cross-section projection.

The completion of the inner-product apparatus is therefore established. The sesquilinear form is forced by Pieces 1–2; the positivity and normalization are forced by Piece 3; the orthogonality–distinguishability link is forced by Piece 4. All four pieces descend from dx₄/dt = ic together with Propositions III.1, IV.1, and V.1. **∎**

### XIII.7 Comparison with the standard Hilbert-space inner product

The McGucken dx₄/dt = ic framework's derivation of the inner product and orthogonality differs in three structural respects from the standard postulational treatment.

**(a) The inner product acquires a geometric source.** Where the Dirac–von Neumann presentation postulates the sesquilinear form as part of the Hilbert-space structure of (Q1), with no underlying physical source, the McGucken dx₄/dt = ic framework derives it as the SO(3)-Haar-weighted pairing of complex amplitudes on the McGucken Sphere's wavefront cross-section. The complex conjugation in the first slot is forced by the U(1) phase symmetry that records relative orientation of x₄. The integration measure d³x is the SO(3)-Haar measure on the spatial slice. Both are geometric, not stipulated.

**(b) The orthogonality–distinguishability link acquires a derivation.** Where standard quantum mechanics axiomatically connects mathematical orthogonality (zero inner product) to physical distinguishability (mutually exclusive outcomes) through the spectral theorem and Born rule postulates, the McGucken dx₄/dt = ic framework derives the link from the cross-section reading of Proposition V.1. The two are not separately postulated; they are two readings of one geometric fact.

**(c) The inner product joins the Born rule, superposition, and complex amplitudes as siblings of one geometric source.** Orthogonality, the Born rule, the superposition principle, the complex character of ψ, and the inner product all descend from the *same* SO(3) symmetry of x₄'s expansion combined with the *same* U(1) phase symmetry of i in x₄ = ict. Proposition III.1 forces the Haar-measure shape of the probability density; Proposition IV.1 forces the SO(3)-equivariance of the superposition operation; the present Proposition XIII.4 forces the SO(3)-Haar-and-U(1)-invariant inner product. All three are consequences of two structural facts about ℳ_G. They are not three independent postulates that happen to be consistent; they are three readings of the same geometric content.

**(d) The structural place of orthogonality in the McGucken hierarchy.** In the McGucken Space hierarchy [12], the derivational chain is

$$\mathcal{M}_G \;\to\; M^{1,3} \;\to\; \mathcal{V} \;\to\; \mathcal{H} \;\to\; \mathcal{F}(\mathcal{H}) \;\to\; \mathcal{A},$$

and each step is mathematically determined by the structure of ℳ_G. The inner product on ℋ is derived in the step 𝒱 → ℋ (the completion of the pre-Hilbert space under the Born norm), not added by hand at the level of ℋ. Orthogonality, as the null relation ⟨a | b⟩ = 0 of the inner product, is therefore not a feature added to ℋ but a feature inherited from the SO(3)-symmetric structure of ℳ_G itself. The distinguishability of orthogonal states is the cross-section reading of this null relation, descending through the same hierarchy via Proposition V.1.

### XIII.8 The complete inner-product apparatus reduces to one structural source

Combining Propositions III.1 (Born rule), IV.1 (superposition), V.1 (collapse as cross-section reading), XIII.1 (Hilbert space is forced), XIII.2 (which Hilbert space), XIII.3 (representation equivalence), and XIII.4 (inner product and orthogonality), the entire inner-product apparatus of standard quantum mechanics — sesquilinear form, complex conjugation, integration measure, orthogonality structure, normalization, positivity, distinguishability of orthogonal states — descends from a single geometric source: the SO(3)-symmetric, U(1)-phased, smooth expansion of x₄ at velocity ic, encoded in dx₄/dt = ic and structured by the McGucken Space ℳ_G = (E⁴, Φ_M, D_M, Σ_M).

The structural reduction is therefore complete at the level of inner-product geometry: every feature of the Hilbert-space inner product is a theorem of dx₄/dt = ic. Where the Dirac–von Neumann system posits the inner product as part of (Q1), the McGucken dx₄/dt = ic framework derives it. Where (Q3) postulates the Born rule, the McGucken dx₄/dt = ic framework derives it. Where the orthogonality–distinguishability link is asserted by axiom, the McGucken dx₄/dt = ic framework derives it from the cross-section reading. The complete Hilbert-space framework — vector-space structure, complex scalars, inner product, orthogonality, distinguishability of orthogonal states, completeness — reduces to theorems of one geometric principle.

This closes the structural-reduction argument of §XIII at the level of the inner-product apparatus. The Hilbert space ℋ is no longer foundational; its inner product, the orthogonality structure of its inner product, and the physical interpretation of orthogonality as distinguishability are all derived. The only remaining foundational principle is dx₄/dt = ic, with ℳ_G as the source-space and Hilbert space as one of several derived representation arenas under the universal derivability principle of [12].

### XIII.9 The McGucken Operator $D_M$ as source-operator: definition, primary properties, and the operator hierarchy

The derivation of the Hilbert-space inner product in §XIII.6 establishes the structure of the *space* on which quantum states reside. What remains to be situated within the McGucken dx₄/dt = ic framework is the structure of the *operators* that act on those states. Standard quantum mechanics treats observables — the Hamiltonian $\hat{H}$, the momentum operators $\hat{p}_\mu$, the Schrödinger evolution operator $i\hbar\partial_t - \hat{H}$, the Dirac operator $i\gamma^\mu\partial_\mu - m$, the canonical commutator $[\hat{q}, \hat{p}] = i\hbar$, and the gauge-covariant derivative $\nabla_\mu = \partial_\mu + A_\mu$ — as primitive operators acting on a separately postulated Hilbert space. Each is independently introduced; their mutual consistency is non-trivial and is established by separate axiomatic content for each.

The McGucken Operator paper [13] establishes that all of these standard operators descend from a single source operator $D_M$, which is co-generated with the McGucken Space $\mathcal{M}_G$ by the same primitive law $dx_4/dt = ic$. The present subsection imports the principal definitions and theorems of [13] and situates them within the present paper, so that the reader of the present paper has full structural access to the operator side of the framework. The next subsection (§XIII.10) will state and prove the space-operator co-generation theorem, and §XIII.12 will establish the deepest structural consequence: the co-generation theorem rules out a separate measurement-collapse mechanism.

**Definition XIII.5 (The McGucken flow operator $D_M$).** The primary McGucken operator is the first-order differential operator

$$D_M \;:=\; \frac{d}{dt}\bigg|_M \;=\; \partial_t + ic\,\partial_{x_4},$$

acting on sufficiently differentiable functions $\Psi = \Psi(t, x_1, x_2, x_3, x_4)$ by

$$D_M\Psi \;=\; \partial_t\Psi + ic\,\partial_{x_4}\Psi.$$

The notation $\frac{d}{dt}\bigg|_M$ means "differentiate along the McGucken flow." Since $dx_4/dt = ic$, the chain rule applied to any differentiable $\Psi$ along a curve satisfying the McGucken Principle gives

$$\frac{d\Psi}{dt} \;=\; \partial_t\Psi + \frac{dx_4}{dt}\partial_{x_4}\Psi \;=\; \partial_t\Psi + ic\,\partial_{x_4}\Psi.$$

The operator $D_M$ is therefore not chosen — it is forced by the chain rule applied to the McGucken Principle [13, Definition 4.1].

**Theorem XIII.A (Tangency of $D_M$ to the McGucken constraint).** *The operator $D_M$ is tangent to the McGucken constraint hypersurface $\mathcal{C}_M = \Phi_M^{-1}(0)$, where $\Phi_M(t, x_4) = x_4 - ict$. Equivalently,*

$$D_M\Phi_M \;=\; 0.$$

**Proof.** By definition $\Phi_M = x_4 - ict$, so $\partial_t\Phi_M = -ic$ and $\partial_{x_4}\Phi_M = 1$. Applying $D_M = \partial_t + ic\,\partial_{x_4}$,

$$D_M\Phi_M \;=\; (-ic) + ic(1) \;=\; 0.$$

Thus $D_M$ is tangent to the level sets of $\Phi_M$, and in particular to $\mathcal{C}_M$. **∎** [Cf. 13, Theorem 5.1.]

**Theorem XIII.B (Characteristic invariants).** *Let $F$ be differentiable. Then $\Psi(t, x_4) = F(x_4 - ict)$ satisfies $D_M\Psi = 0$.*

**Proof.** Let $u = x_4 - ict$, so $\Psi = F(u)$. The chain rule gives $\partial_t\Psi = -icF'(u)$ and $\partial_{x_4}\Psi = F'(u)$. Hence

$$D_M\Psi \;=\; -icF'(u) + ic\,F'(u) \;=\; 0.$$

Therefore every differentiable function of $x_4 - ict$ is annihilated by $D_M$. **∎** [Cf. 13, Theorem 5.2.]

**Theorem XIII.C (Generator theorem).** *The McGucken Principle $dx_4/dt = ic$ and the McGucken flow operator $D_M$ are equivalent in the sense that the integral curves of $D_M$ satisfy the McGucken Principle, and the chain-rule derivative along any curve satisfying the McGucken Principle is $D_M$. The finite flow generated by $D_M$ acts on functions by*

$$e^{sD_M}\Psi(t, x_4) \;=\; \Psi(t + s,\, x_4 + ics).$$

**Proof.** Let $s$ parameterize integral curves of $D_M$ regarded as the vector field $(1, ic)$ in the $(t, x_4)$-plane. Then $dt/ds = 1$ and $dx_4/ds = ic$, so $dx_4/dt = ic$, recovering the McGucken Principle. Conversely, if a curve satisfies $dx_4/dt = ic$, the chain-rule derivative of any $\Psi(t, x_4)$ along the curve is $\partial_t\Psi + ic\partial_{x_4}\Psi = D_M\Psi$.

For the exponential flow, define $\Psi_s(t, x_4) = \Psi(t + s, x_4 + ics)$. Then

$$\frac{d\Psi_s}{ds} \;=\; \partial_t\Psi(t+s, x_4+ics) + ic\,\partial_{x_4}\Psi(t+s, x_4+ics) \;=\; D_M\Psi_s,$$

with initial condition $\Psi_0 = \Psi$. By uniqueness of the flow generated by a smooth vector field, $\Psi_s = e^{sD_M}\Psi$. **∎** [Cf. 13, Theorem 6.1.]

**Definition XIII.6 (The quantum McGucken operator $\hat{M}$).** The quantum McGucken operator is

$$\hat{M} \;:=\; i\hbar D_M \;=\; i\hbar(\partial_t + ic\,\partial_{x_4}) \;=\; i\hbar\partial_t - \hbar c\,\partial_{x_4}.$$

Using the standard quantum operator identifications $\hat{H} = i\hbar\partial_t$ for the Hamiltonian and $\hat{p}_4 = -i\hbar\partial_{x_4}$ for the fourth-momentum, this becomes

$$\hat{M} \;=\; \hat{H} - ic\,\hat{p}_4.$$

The quantum McGucken constraint is $\hat{M}\Psi = 0$, equivalently $\hat{H}\Psi = ic\,\hat{p}_4\Psi$ [13, Definition 7.1].

**Theorem XIII.D (Plane-wave spectrum).** *On exponential modes $\Psi(t, x_4) = e^{-i\omega t + ik_4 x_4}$, the symbol of $D_M$ is $\sigma(D_M) = -i\omega - ck_4$. The quantum McGucken constraint $\hat{M}\Psi = 0$ imposes the spectral relation*

$$\omega \;=\; ick_4.$$

**Proof.** Apply $D_M$ to the mode: $\partial_t\Psi = -i\omega\Psi$ and $\partial_{x_4}\Psi = ik_4\Psi$, hence $D_M\Psi = (-i\omega + ic\cdot ik_4)\Psi = (-i\omega - ck_4)\Psi$. Setting this to zero gives $\omega = ick_4$. **∎** [Cf. 13, §7.3, Proposition 19.5.]

**Theorem XIII.E (Wick derivative identity from the McGucken flow).** *From the McGucken constraint $x_4 = ict$, the fourth-coordinate derivative satisfies*

$$\partial_{x_4} \;=\; \frac{1}{ic}\partial_t \;=\; -\frac{i}{c}\partial_t,$$

*and hence $\partial_{x_4}^2 = -c^{-2}\partial_t^2$. The Wick rotation between Lorentzian time $t$ and Euclidean time $\tau = x_4/c = it$ is therefore not an external analytic prescription but an immediate operator-level consequence of $D_M$'s flow.*

**Proof.** From $x_4 = ict$ one has $\partial t/\partial x_4 = 1/(ic) = -i/c$ by inversion, so $\partial_{x_4} = (\partial t/\partial x_4)\partial_t = -(i/c)\partial_t$. Squaring, $\partial_{x_4}^2 = -c^{-2}\partial_t^2$. Setting $\tau = x_4/c$ gives $\tau = it$, the Wick rotation identity. The derivative relation $\partial_\tau = \partial t/\partial\tau\cdot\partial_t = -i\partial_t$ follows by the same chain rule. **∎** [Cf. 13, Theorem 10.1.]

**Theorem XIII.F (Lorentzian wave operator from projection of the Euclidean four-Laplacian).** *The four-coordinate Euclidean Laplacian $\Delta_4 = \nabla^2 + \partial_{x_4}^2$, projected by the McGucken constraint $x_4 = ict$, yields the Lorentzian wave operator (d'Alembertian):*

$$\Delta_4 \;\longmapsto\; \square_M \;:=\; \nabla^2 - \frac{1}{c^2}\partial_t^2.$$

**Proof.** By Theorem XIII.E, $\partial_{x_4}^2 = -c^{-2}\partial_t^2$. Substitution into $\Delta_4 = \nabla^2 + \partial_{x_4}^2$ gives $\nabla^2 - c^{-2}\partial_t^2 = \square_M$, the d'Alembertian in the convention with positive spatial part. **∎** [Cf. 13, Theorem 8.2.]

**Theorem XIII.G (Dirac-McGucken square-root theorem).** *In the absence of gauge fields, the Lorentzian wave operator $\square_M + m^2$ admits a Clifford-linear square root via gamma matrices satisfying $\{\gamma^\mu, \gamma^\nu\} = 2\eta^{\mu\nu}\mathbb{I}$:*

$$(i\gamma^\mu\partial_\mu - m)(i\gamma^\nu\partial_\nu + m) \;=\; -(\square_M + m^2)$$

*in natural units. The Dirac-McGucken operator is therefore $\mathcal{D}_M := i\gamma^\mu\partial_\mu - m$, the spinorial first-order square root of the McGucken-induced second-order wave operator.*

**Proof.** Expanding the product, $(i\gamma^\mu\partial_\mu - m)(i\gamma^\nu\partial_\nu + m) = -\gamma^\mu\gamma^\nu\partial_\mu\partial_\nu - m^2$, since the cross terms $im\gamma^\nu\partial_\nu - im\gamma^\mu\partial_\mu = 0$ when $\mu, \nu$ are summed symmetrically. Because $\partial_\mu\partial_\nu$ is symmetric in $(\mu, \nu)$, only the symmetric part of $\gamma^\mu\gamma^\nu$ contributes:

$$\gamma^\mu\gamma^\nu\partial_\mu\partial_\nu \;=\; \tfrac{1}{2}\{\gamma^\mu, \gamma^\nu\}\partial_\mu\partial_\nu \;=\; \eta^{\mu\nu}\partial_\mu\partial_\nu \;=\; \square_M.$$

Therefore $(i\gamma^\mu\partial_\mu - m)(i\gamma^\nu\partial_\nu + m) = -\square_M - m^2 = -(\square_M + m^2)$. **∎** [Cf. 13, Theorem 11.2.]

**Definition XIII.7 (Gauge-covariant McGucken operator).** Replacing partial derivatives in $D_M$ by gauge-covariant derivatives $\nabla_\mu = \partial_\mu + A_\mu$, the gauge-covariant McGucken operator is

$$D_M^A \;:=\; \nabla_t + ic\,\nabla_{x_4} \;=\; D_M + A_M, \quad A_M \;:=\; A_t + ic\,A_4.$$

The McGucken connection component $A_M$ is the gauge field along the invariant fourth-dimensional flow [13, Definition 12.1].

**Theorem XIII.H (Quantum commutators inherited from $D_M$).** *Acting on functions of $(t, x_4)$:*

$$[D_M, t] = 1, \quad [D_M, x_4] = ic, \quad [D_M, \Phi_M] = 0,$$

*and after multiplication by $i\hbar$:*

$$[\hat{M}, t] = i\hbar, \quad [\hat{M}, x_4] = -\hbar c, \quad [\hat{M}, \Phi_M] = 0.$$

*The canonical commutator $[\hat{q}, \hat{p}] = i\hbar$ is therefore inherited from the algebraic structure of $D_M$ acting on $(t, x_4)$ together with the standard quantization $\hat{p}_\mu = -i\hbar\partial_\mu$.*

**Proof.** $D_M(t\Psi) = \Psi + tD_M\Psi$, so $[D_M, t] = 1$. $D_M(x_4\Psi) = (\partial_t + ic\partial_{x_4})(x_4\Psi) = ic\Psi + x_4D_M\Psi$, so $[D_M, x_4] = ic$. Multiplication of $\Psi$ by $\Phi_M = x_4 - ict$ commutes with $D_M$ in the sense $[D_M, \Phi_M]\Psi = (D_M\Phi_M)\Psi = 0$ by Theorem XIII.A. The quantum versions follow by multiplication by $i\hbar$, with $[\hat{M}, x_4] = i\hbar\cdot ic = -\hbar c$. The canonical commutator $[\hat{q}, \hat{p}] = i\hbar$ follows by applying the same calculation to a spatial coordinate $\hat{q} = x$ and its conjugate momentum $\hat{p} = -i\hbar\partial_x$, which is a direct algebraic consequence of $D_M$'s acting as a first-order derivative operator. **∎** [Cf. 13, §14.]

**The operator hierarchy.** The McGucken Operator paper organizes the principal operators of physics as descendants of $D_M$ by projection, quantization, squaring, factorization, and covariantization. Reproducing the structural table of [13, §17.1] in the present notation:

| Layer | Object | Formula | Derivation from $D_M$ | Physical role |
|---|---|---|---|---|
| 0 (constraint) | $\Phi_M$ | $x_4 - ict$ | Defining function | Defines $\mathcal{C}_M$ |
| 1 (flow) | $D_M$ | $\partial_t + ic\,\partial_{x_4}$ | Source operator | Generator along $x_4 = ict$ |
| 1 (conjugate) | $D_M^*$ | $\partial_t - ic\,\partial_{x_4}$ | Conjugate characteristic | Annihilates $F(x_4 + ict)$ |
| 2 (quantum) | $\hat{M}$ | $i\hbar D_M = \hat{H} - ic\hat{p}_4$ | Quantization $i\hbar$-multiplication | Quantum constraint |
| 2 (Hamiltonian) | $\hat{H}$ | $i\hbar\partial_t$ | $t$-sector of $\hat{M}$ | Time-evolution generator |
| 2 (momentum) | $\hat{p}_4$ | $-i\hbar\partial_{x_4}$ | $x_4$-sector of $\hat{M}$ | Fourth-coordinate translation generator |
| 3 (Wick) | $\partial_\tau = -i\partial_t$ | $\tau = x_4/c = it$ | Projection of constraint | Imaginary-time derivative |
| 3 (wave) | $\square_M$ | $\nabla^2 - c^{-2}\partial_t^2$ | $\Delta_4 \to \square_M$ via $\partial_{x_4}^2 = -c^{-2}\partial_t^2$ | Relativistic wave propagation |
| 4 (Schrödinger) | $i\hbar\partial_t - \hat{H}$ | Standard Schrödinger | Time-evolution sector | Quantum unitary dynamics |
| 4 (Dirac) | $\mathcal{D}_M$ | $i\gamma^\mu\partial_\mu - m$ | Clifford square root of $\square_M$ | Spinorial relativistic propagation |
| 5 (gauge) | $D_M^A$ | $\nabla_t + ic\,\nabla_{x_4}$ | Covariantization | Gauge-covariant transport |
| 5 (curvature) | $[D_M^A, D_N^A]$ | Commutator of covariant flows | Field strength descendant | Interaction curvature |
| 5 (commutator) | $[\hat{q}, \hat{p}]$ | $i\hbar$ | Algebraic descendant of $D_M$ | Canonical commutation |

Every operator in this hierarchy is a theorem of $dx_4/dt = ic$ via $D_M$. The operator side of standard quantum mechanics — the Hamiltonian, the momentum, the canonical commutator, the Schrödinger evolution, the Dirac operator, the gauge-covariant derivative, the wave operator — is therefore not a collection of independently postulated operators but a single derivational chain descending from one source operator, which itself descends from one principle.

---

### XIII.10 The Space-Operator Co-Generation Theorem

The McGucken Space paper [12] established that the space $\mathcal{M}_G$ is generated by $dx_4/dt = ic$. The McGucken Operator paper [13] established that the operator $D_M$ is generated by $dx_4/dt = ic$. The structural unification of these two facts is the *space-operator co-generation theorem*: the principle generates space and operator *simultaneously*, with the space and operator being mutually constituting facets of a single source.

**Theorem XIII.I (Space-operator co-generation).** *The McGucken Principle $dx_4/dt = ic$ generates both the McGucken Space $\mathcal{M}_G = (E^4, \Phi_M, D_M, \Sigma_M)$ and the McGucken Operator $D_M = \partial_t + ic\partial_{x_4}$ as a single source space-operator pair:*

$$\frac{dx_4}{dt} = ic \;\Longrightarrow\; (\mathcal{M}_G, D_M).$$

**Proof.** The McGucken Principle integrates to $x_4 = ict + C$. With the source-origin convention $C = 0$, this gives $x_4 = ict$. Define the McGucken constraint

$$\Phi_M \;=\; x_4 - ict.$$

The zero set $\Phi_M = 0$ defines the constraint hypersurface $\mathcal{C}_M = \Phi_M^{-1}(0)$. Combined with the four-coordinate carrier $E^4$ and the spherical propagation structure $\Sigma_M$ (the future null surface generated by Huygens-type propagation at velocity $c$ from each spacetime event, established as a structural feature of the McGucken dx₄/dt = ic framework in [12, §3.4]), this defines the McGucken Space

$$\mathcal{M}_G \;=\; (E^4, \Phi_M, D_M, \Sigma_M).$$

Simultaneously, the chain-rule derivative along the same primitive flow is

$$\frac{d}{dt}\bigg|_M \;=\; \partial_t + \frac{dx_4}{dt}\partial_{x_4} \;=\; \partial_t + ic\,\partial_{x_4} \;=\; D_M.$$

The same primitive law $dx_4/dt = ic$ therefore generates both the source-space $\mathcal{M}_G$ and the source-operator $D_M$. The two are not introduced separately and reconciled; they are co-descendants of a single primitive physical relation. **∎** [Cf. 12, Theorem 0.1; 13, Theorem 0.S.]

**Corollary XIII.J (Mutual derivability).** *The space $\mathcal{M}_G$, the operator $D_M$, and the principle $dx_4/dt = ic$ are mutually derivable: each two of the three determine the third.*

**Proof.** *(I)* $(\mathcal{M}_G, D_M) \Longrightarrow dx_4/dt = ic$: Given the structured arena $\mathcal{M}_G = (E^4, \Phi_M, D_M, \Sigma_M)$, the constraint $\Phi_M = x_4 - ict = 0$ immediately yields $x_4 = ict$, which differentiated gives $dx_4/dt = ic$. Equivalently, the integral curves of $D_M$ as a vector field on $E^4$ satisfy $dx_4/dt = ic$ by Theorem XIII.C.

*(II)* $\mathcal{M}_G \Longrightarrow D_M$: Given $\mathcal{M}_G$, the operator $D_M$ is the unique normalized first-order operator in $(t, x_4)$ tangent to $\Phi_M = 0$, by the minimality result (Theorem XIII.K below). The constraint $\Phi_M = x_4 - ict$ together with the tangency condition $D_M\Phi_M = 0$ and the normalization $\partial_t$-coefficient $= 1$ forces $D_M = \partial_t + ic\,\partial_{x_4}$.

*(III)* $D_M \Longrightarrow \mathcal{M}_G$: Given $D_M = \partial_t + ic\,\partial_{x_4}$, the integral curves of $D_M$ as a vector field define the McGucken constraint surface $\mathcal{C}_M$. The four-coordinate carrier $E^4$ is the ambient arena on which $D_M$ acts. The spherical propagation structure $\Sigma_M$ is the null surface of the Lorentzian wave operator $\square_M$ induced by $D_M$ (Theorem XIII.F). Together these reconstruct $\mathcal{M}_G$.

The three structures $(\mathcal{M}_G, D_M, dx_4/dt = ic)$ are therefore mutually derivable: each is a different reading of the same underlying source-fact. **∎**

**Theorem XIII.K (Uniqueness of $D_M$ as the first-order tangent operator).** *Among first-order linear differential operators of the form $L = a\partial_t + b\partial_{x_4}$, the operator tangent to $\Phi_M = x_4 - ict$ with normalization $a = 1$ is uniquely $D_M = \partial_t + ic\,\partial_{x_4}$.*

**Proof.** Tangency requires $L\Phi_M = 0$. Computing, $L\Phi_M = a(-ic) + b(1) = b - iac$. Setting this to zero gives $b = iac$. With $a = 1$, this yields $b = ic$, hence $L = \partial_t + ic\,\partial_{x_4} = D_M$. **∎** [Cf. 13, Proposition 19.1.]

The operator $D_M$ is therefore not one choice among many first-order operators on the McGucken constraint hypersurface — it is the *unique* normalized first-order tangent operator. The space $\mathcal{M}_G$ is similarly the unique source-space with primitive signature $\{x_4, t, i, c, \Phi_M, D_M, \Sigma_M, dx_4/dt = ic\}$ (Theorem 17.4 of [12]). Both are uniquely determined by the same primitive law.

#### XIII.10.1 Inverse derivability: from $(\mathcal{M}_G, D_M)$ back to the principle

The forward direction of the co-generation theorem ($dx_4/dt = ic \Rightarrow (\mathcal{M}_G, D_M)$) establishes that the source-space and source-operator descend from the principle. The inverse direction is equally important:

**Corollary XIII.L (Inverse derivability theorem).** *The pair $(\mathcal{M}_G, D_M)$ determines the McGucken Principle $dx_4/dt = ic$ uniquely. Equivalently, the principle, the space, and the operator are not three independent foundational objects — they are three readings of one structural object.*

**Proof.** This is part (I) of Corollary XIII.J. The constraint $\Phi_M = x_4 - ict = 0$ contained in $\mathcal{M}_G$ implies $x_4 = ict$, which differentiated gives $dx_4/dt = ic$. Alternatively, the integral curves of $D_M$ as a vector field satisfy $dx_4/dt = ic$ by Theorem XIII.C. Either route recovers the principle. **∎**

This inverse derivability is the structural feature that distinguishes the McGucken dx₄/dt = ic framework from every other framework in mathematical physics. In every standard framework, the space and the operators acting on the space are independently postulated, and the principle that connects them — a Lagrangian, a Hamiltonian, a commutation relation, a probability rule — is a *third* independent structure. There is no inverse derivability; the principle, space, and operators are three separate axiomatic commitments whose mutual consistency must be checked.

In the McGucken dx₄/dt = ic framework, the three are one. The principle generates the pair; the pair determines the principle. There is no axiomatic content that can be added to one without being implicit in the others, and no axiomatic content that can be subtracted from one without losing all three.

#### XIII.10.2 The structural categorical novelty

The categorical structure of the McGucken dx₄/dt = ic framework can be summarized as follows. Standard mathematical physics works with the sequence

$$\text{space (assumed first)} \;\to\; \text{operator (defined on space)} \;\to\; \text{dynamics}.$$

The space is supplied as a primitive object (a manifold, a Hilbert space, a phase space, a fiber bundle). Operators are then introduced as maps acting on the space. Dynamics is then specified through equations relating operators or through Lagrangian/Hamiltonian functions. Three independent layers of axiomatic content are required.

The McGucken dx₄/dt = ic framework works with the source sequence

$$\text{primitive physical law} \;\to\; \text{source-space/source-operator pair} \;\to\; \text{standard spaces, operators, and dynamics}.$$

A single primitive physical law $dx_4/dt = ic$ generates the source-space $\mathcal{M}_G$ and the source-operator $D_M$ together. Standard spaces (Lorentzian spacetime, Hilbert space, phase space, Fock space, fiber bundles, operator algebras) are derived from $\mathcal{M}_G$ by admissible physical-space operations (Universal Derivability Principle of [12]). Standard operators (Hamiltonian, momentum, wave operator, Schrödinger operator, Dirac operator, gauge-covariant derivative, canonical commutator) are derived from $D_M$ by projection, quantization, squaring, factorization, covariantization, and commutation (Universal Operator-Derivability Principle of [13]). Dynamics emerges as the action of $D_M$ on states in $\mathcal{M}_G$, with $\hat{M} = i\hbar D_M$ supplying the quantum constraint.

One layer of axiomatic content, generating two derived layers. This is the structural categorical novelty.

#### XIII.10.3 Comparison with standard categorical structure

The contrast can be tabulated explicitly:

| Aspect | Standard mathematical physics | McGucken dx₄/dt = ic framework |
|---|---|---|
| Number of independent primitive structures | Three (space, operator, principle) | One ($dx_4/dt = ic$) |
| Status of space | Primitive, postulated first | Derived (source-space $\mathcal{M}_G$ from $dx_4/dt = ic$) |
| Status of operator | Defined on space, after space is given | Co-derived ($D_M$ from $dx_4/dt = ic$) |
| Status of dynamics | Specified by Lagrangian/Hamiltonian/equations | Derived from $D_M$ acting on $\mathcal{M}_G$ |
| Inverse derivability | None — space, operator, and dynamics are independent | Full — space and operator together determine the principle |
| Mutual consistency | Must be checked separately for each pair | Automatic — all three are facets of one source |
| Primitive-law complexity | At least three independent laws | $C(\mathcal{M}_G) = C(D_M) = 1$ |
| Source-status | None — each structure is postulated | $\mathcal{M}_G$ is foundationally maximal (Theorem 17.4 of [12]); $D_M$ is operator-maximal (Theorem 23.7 of [13]) |
| Categorical relation between space and operator | Disjoint; operator acts on space | Co-generated; space and operator are mutually constituting |

The "axiomatic compression" achieved by this categorical structure is not a matter of stylistic economy — it has substantive structural consequences for which problems can and cannot be formulated in the framework. The deepest such consequence concerns the measurement problem itself, which the next subsections develop.

---

### XIII.11 Proposition XIII.5: The principal quantum operators are theorems of $dx_4/dt = ic$

The operator hierarchy of §XIII.9 displays the principal quantum operators of standard physics as descendants of $D_M$. The corresponding formal claim, suitable to the structural argument of the present paper, is the following.

**Proposition XIII.5 (The principal quantum operators are theorems of $dx_4/dt = ic$).** *Let $\mathcal{H}$ be the Hilbert space derived from $\mathcal{M}_G$ via the Hilbert-space emergence theorem (Theorem 12.1 of [12], reproduced in §XIII.5). Then the following operators acting on $\mathcal{H}$ — the Hamiltonian $\hat{H} = i\hbar\partial_t$, the momentum operators $\hat{p}_\mu = -i\hbar\partial_\mu$ (in particular the fourth-momentum $\hat{p}_4$), the quantum McGucken operator $\hat{M} = i\hbar D_M = \hat{H} - ic\,\hat{p}_4$, the Schrödinger operator $i\hbar\partial_t - \hat{H}$, the canonical commutator $[\hat{q}, \hat{p}] = i\hbar$, the Lorentzian wave operator $\square_M = \nabla^2 - c^{-2}\partial_t^2$, the Dirac operator $\mathcal{D}_M = i\gamma^\mu\partial_\mu - m$, and the gauge-covariant McGucken derivative $D_M^A = \nabla_t + ic\nabla_{x_4}$ — are derivable from $D_M$ via projection, quantization, squaring, factorization, covariantization, and commutation. Each is a theorem of $dx_4/dt = ic$ via $D_M$, with no independent axiomatic content.*

**Proof.** The proof proceeds operator-by-operator, importing the relevant theorems from §XIII.9 and from [13].

*Hamiltonian $\hat{H}$.* By Definition XIII.6, $\hat{M} = i\hbar D_M = i\hbar\partial_t - \hbar c\,\partial_{x_4} = \hat{H} - ic\,\hat{p}_4$. The Hamiltonian is therefore the $t$-sector of the quantum McGucken operator: $\hat{H} = i\hbar\partial_t$ is recovered as the term in $\hat{M}$ associated with the time coordinate, and $\hat{H}$ generates time-translations as a consequence of $D_M$'s tangent action along $t$. **∎ (Hamiltonian)**

*Momentum operators $\hat{p}_\mu$.* The fourth-momentum $\hat{p}_4 = -i\hbar\partial_{x_4}$ is the $x_4$-sector of $\hat{M}$. The spatial momenta $\hat{p}_i = -i\hbar\partial_i$ for $i = 1, 2, 3$ arise as the canonical generators of spatial translations in the spatial slice $\Sigma_t$ of $\mathcal{M}_G$, with the standard quantization $\hat{p}_i \mapsto -i\hbar\partial_i$ inherited from the algebraic structure of $D_M$ (Theorem XIII.H) generalized to spatial coordinates. The factor $-i\hbar$ in each case reflects the perpendicularity marker $i$ in $D_M$ together with the quantum of $x_4$-oscillation $\hbar$ [76]. **∎ (Momentum)**

*Quantum McGucken operator $\hat{M}$.* By Definition XIII.6, $\hat{M} = i\hbar D_M$ is the canonical quantization of the source-operator $D_M$, achieved by multiplication by $i\hbar$. **∎ (Quantum McGucken)**

*Schrödinger operator $i\hbar\partial_t - \hat{H}$.* The Schrödinger equation $i\hbar\partial_t\psi = \hat{H}\psi$ is the time-evolution sector of the quantum McGucken constraint $\hat{M}\psi = 0$, restricted to the case where the fourth-momentum sector contributes the rest-mass phase $-ic\hat{p}_4 \to -mc^2$ in the non-relativistic limit (Theorem 7 of [6]; cf. §XII.3 for the path-integral version). The factor $i\hbar$ in the Schrödinger operator is the same $i\hbar$ as in $\hat{M} = i\hbar D_M$, with the perpendicularity marker $i$ inherited from $x_4 = ict$. **∎ (Schrödinger)**

*Canonical commutator $[\hat{q}, \hat{p}] = i\hbar$.* By Theorem XIII.H, $D_M$ acts on coordinate-multiplied wavefunctions by $[D_M, x_4]\Psi = ic\Psi$, hence $[\hat{M}, x_4] = -\hbar c$. The same algebraic structure applied to a spatial coordinate $\hat{q} = x$ and its conjugate momentum $\hat{p} = -i\hbar\partial_x$ gives $[\hat{q}, \hat{p}]\Psi = i\hbar\Psi$. The factor $i\hbar$ in the canonical commutator is the same $i\hbar$ as in $\hat{M} = i\hbar D_M$ — the $i$ from the perpendicularity marker of $x_4$, the $\hbar$ from the quantum of $x_4$-oscillation. **∎ (Canonical commutator)**

*Lorentzian wave operator $\square_M$.* By Theorem XIII.F, $\square_M = \nabla^2 - c^{-2}\partial_t^2$ is the projection of the four-coordinate Euclidean Laplacian $\Delta_4 = \nabla^2 + \partial_{x_4}^2$ under the McGucken constraint $x_4 = ict$, which converts $\partial_{x_4}^2$ into $-c^{-2}\partial_t^2$. The Lorentzian signature of spacetime — the minus sign in $\square_M$ — is therefore a theorem of $dx_4/dt = ic$, not a postulated metric structure. **∎ (Wave operator)**

*Dirac operator $\mathcal{D}_M$.* By Theorem XIII.G, $\mathcal{D}_M = i\gamma^\mu\partial_\mu - m$ is the Clifford-linear square root of the McGucken-induced wave operator $\square_M + m^2$. The Dirac operator is therefore not a primitive operator but a factorization-descendant of $\square_M$, which is itself a projection-descendant of $\Delta_4$, which is a derivative-square descendant of $D_M$. **∎ (Dirac)**

*Gauge-covariant McGucken derivative $D_M^A$.* By Definition XIII.7, $D_M^A = \nabla_t + ic\,\nabla_{x_4} = D_M + A_M$ is the covariantization of $D_M$ obtained by replacing partial derivatives with gauge-covariant derivatives. The gauge-covariant Hamiltonian, gauge-covariant momentum, and gauge-covariant Schrödinger operator all descend by analogous covariantization. **∎ (Gauge)**

Each of the eight operator structures listed in the proposition is therefore a theorem of $dx_4/dt = ic$ via the source-operator $D_M$. **∎**

The proposition is the operator-side analogue of the space-side result of §XIII.5: just as Hilbert space itself is a theorem of $dx_4/dt = ic$ via the source-space $\mathcal{M}_G$, the principal quantum operators are theorems of $dx_4/dt = ic$ via the source-operator $D_M$. Together, the two sides exhaust the structural content of the standard quantum-mechanical formalism: state space + operator algebra. Both are derived from one principle.

---

### XIII.12 Proposition XIII.6: The space-operator co-generation theorem rules out a separate measurement-collapse mechanism

The measurement problem of standard quantum mechanics asks: what is the physical mechanism by which the unitary evolution $(U)$ of an entangled system-apparatus state collapses to a single outcome at measurement? Every interpretive programme answers by adding structure: Copenhagen adds the projection postulate $(R)$ as a separate dynamical law; Many-Worlds adds branching as a structural feature of the multiverse; Bohmian mechanics adds hidden variables on configuration space; GRW adds stochastic localization terms to the Hamiltonian; decoherence-plus-environmental-selection adds einselection by environment-system coupling; Relational Quantum Mechanics adds observer-relativity to the state; QBism adds personal Bayesian probability assignments by epistemic agents.

Each addition introduces a *new structural ingredient* not present in the bare formalism of "Hilbert space + unitary evolution." That new ingredient is, in each case, what carries the dissolution of superposition into definite outcome. In Copenhagen the new ingredient is the projection postulate; in Many-Worlds it is the branching primitive; in Bohmian mechanics it is the configuration-space ontology; in GRW it is the stochastic localization parameter; in decoherence-plus-einselection it is the system-environment Hamiltonian; in RQM it is the relational primitive; in QBism it is the agent.

The space-operator co-generation theorem (Theorem XIII.I) supplies a structural impossibility result: in the McGucken dx₄/dt = ic framework, no such addition is possible, because there is nowhere to put it.

**Proposition XIII.6 (The space-operator co-generation theorem rules out a separate measurement-collapse mechanism).** *In the McGucken dx₄/dt = ic framework, any putative dynamical mechanism for wave function collapse — call it $\mathcal{R}$ — must be either (a) a new physical space, (b) a new physical operator, or (c) a new physical principle. Each of these three options is ruled out by the co-generation theorem and the universal derivability principles of [12] and [13]. Therefore no separate dynamical mechanism for wave function collapse can be introduced into the McGucken dx₄/dt = ic framework. The apparent collapse $R$ must reduce to a structural feature of the existing space-operator pair $(\mathcal{M}_G, D_M)$ — specifically, the 3D cross-section reading of Proposition V.1, with no independent dynamical content.*

**Proof.** Suppose, for contradiction, that a separate dynamical mechanism $\mathcal{R}$ for wave function collapse exists in the McGucken dx₄/dt = ic framework. Such a mechanism, to be a *physical* mechanism, must consist of physical entities — entities that are either spatial (live in some space), operatorial (act as some operator), or principial (express some primitive law). We address each option in turn.

*Case (a): $\mathcal{R}$ is a new space.* By the universal derivability principle of [12, Theorem 15.1 (the McGucken Universal Derivability Principle)], every physically meaningful space in fundamental physics is derivable from $\mathcal{M}_G$ by a finite sequence of admissible physical-space operations: constraint, projection, slicing, bundle formation, section formation, cotangent lift, complexification, representation, quantization, completion, tensor product, Fock construction, or operator-algebra construction. The space $\mathcal{M}_G$ is foundationally maximal: every standard physical space lies in $\text{Der}(\mathcal{M}_G)$, while $\mathcal{M}_G$ cannot be derived from any standard derived space without reintroducing the McGucken primitive signature (Theorem 17.4 of [12]). Therefore any "new space" in which $\mathcal{R}$ might live is in fact a derivative of $\mathcal{M}_G$, and is not new. The configuration-space ontology of Bohmian mechanics, the multiverse-branching space of Many-Worlds, the relational-fact space of RQM, and the agent-state space of QBism are all derivable from $\mathcal{M}_G$ via admissible operations, with no independent foundational content. **∎ (Case a)**

*Case (b): $\mathcal{R}$ is a new operator.* By the universal operator-derivability principle of [13, Principle 23.1], every standard operator in the McGucken hierarchy is derivable from $D_M$ via projection, quantization, squaring, factorization, covariantization, commutation, Fourier representation, spectral representation, or domain completion. The operator $D_M$ is operator-foundationally maximal: every standard operator descends from $D_M$, while $D_M$ cannot be derived from any standard descendant operator without reintroducing the McGucken primitive signature (Theorem 23.7 of [13]). Therefore any "new operator" implementing $\mathcal{R}$ is in fact a derivative of $D_M$, and is not new. The stochastic localization Hamiltonian of GRW, the projection operators of Copenhagen, the einselection operators of decoherence, the guidance equation of Bohmian mechanics — each is, structurally, a derivative of $D_M$ when expressed on Hilbert spaces derivable from $\mathcal{M}_G$. None has independent operator content. **∎ (Case b)**

*Case (c): $\mathcal{R}$ is a new principle.* The McGucken Principle $dx_4/dt = ic$ is the unique source-law of the framework. By the inverse derivability of Corollary XIII.L, the principle is determined by the pair $(\mathcal{M}_G, D_M)$ — equivalently, the principle is what makes the source-pair the source-pair. A "new principle" $\mathcal{R}$ would have to be either (i) a refinement of $dx_4/dt = ic$, (ii) an independent additional law, or (iii) a modification of $dx_4/dt = ic$.

(i) A refinement is impossible because $dx_4/dt = ic$ is the unique normalized first-order law tangent to the McGucken constraint (Theorem XIII.K).

(ii) An independent additional law is impossible because the framework has primitive-law complexity $C(\mathcal{M}_G) = C(D_M) = 1$ (Theorem 17.5 of [12]; Theorem 23.8 of [13]) — adding a second independent law would change the primitive-law complexity to 2, which by the simplicity theorems of both papers would no longer be the McGucken dx₄/dt = ic framework but a different framework with more axiomatic content.

(iii) A modification would alter the source-pair $(\mathcal{M}_G, D_M)$ to a different pair $(\mathcal{M}_G', D_M')$, again giving a different framework, not the McGucken dx₄/dt = ic framework. **∎ (Case c)**

All three cases lead to contradiction with the assumption that $\mathcal{R}$ is a *separate* dynamical mechanism within the McGucken dx₄/dt = ic framework. Therefore no such mechanism can be introduced. The apparent collapse $R$ must therefore be a structural feature of the existing space-operator pair $(\mathcal{M}_G, D_M)$ — specifically, the projection $\pi_{x_{\text{obs}}}$ from the four-dimensional state $|\Psi(t)\rangle \in \mathcal{H}$ to the observer's accessible 3D cross-section, as established in Proposition V.1.

The structural conclusion is therefore: in the McGucken dx₄/dt = ic framework, the *measurement problem cannot be formulated*. The standard problem requires a categorical separation between system, apparatus, observer, and dynamics — a separation that maps onto distinct spaces, operators, and principles. The co-generation theorem identifies the space and operator as co-descendants of one principle, eliminating the categorical separation at the source. There is no "measurement-mechanism slot" in the framework's category structure to be filled. **∎**

#### XIII.12.1 The deeper structural meaning

The structural meaning of Proposition XIII.6 is more substantial than the formal proof indicates. The proposition does not merely say that the McGucken dx₄/dt = ic framework *happens* to lack a separate $\mathcal{R}$ mechanism. It says that the framework's category structure *makes such a mechanism impossible*. The reason is the co-generation theorem itself.

In the standard categorical structure of mathematical physics, "system" and "apparatus" are entities of the same kind (both are configurations of states in a Hilbert space), distinguished by some pragmatic boundary (the Heisenberg cut). "Observer" is a third entity, often unspecified, conventionally identified with whatever sits on the classical side of the cut. "Dynamics" is a fourth structure (the unitary evolution between measurements) related to the operators acting on the Hilbert space. Four categories, three boundaries: system/apparatus, apparatus/observer, dynamics/measurement.

In the McGucken dx₄/dt = ic framework, all four are projections of one source. System, apparatus, and observer are all configurations in $\mathcal{M}_G$ — they are spatial slices, wavefronts, and detection events within the same expanding null-spherical structure. Dynamics is the action of $D_M$ on these configurations. Measurement is the geometric event in which an observer's spatial slice $\Sigma_t$ intersects the wavefront $\Sigma_M(p)$ propagating from a source event $p$. There are no four categories — there is one category: the source-pair $(\mathcal{M}_G, D_M)$ and its derivatives. There are no three boundaries — there is one structural fact: the projection $\pi_{x_{\text{obs}}}$ from $\mathcal{M}_G$ to the spatial slice at the observer's location.

The measurement problem is, in standard formulations, the question: *how does the apparatus, which is part of the dynamics, produce a definite measurement outcome that is observed by an observer who is outside the dynamics?* The McGucken dx₄/dt = ic framework does not need to answer this question because the question presupposes a categorical structure that the framework rejects at the source. There is no apparatus "outside the dynamics" — the apparatus, like everything else, is configured by $D_M$ acting on $\mathcal{M}_G$. There is no observer "outside the system" — the observer is a spatial slice $\Sigma_t$ within $\mathcal{M}_G$. There is no measurement event "separate from the unitary evolution" — the measurement event is the geometric intersection of the wavefront with the observer's spatial slice, both of which are parts of the same co-generated structure.

#### XIII.12.2 The measurement event as space-operator self-action

The deepest formulation of the dissolution can now be stated. A measurement event in the McGucken dx₄/dt = ic framework is the moment at which the operator $D_M$, acting through the spherical wavefront $\Sigma_M$, intersects an observer's spatial slice $\Sigma_t$ in $\mathcal{M}_G$. Schematically:

$$\text{measurement} \;=\; D_M(\Sigma_M(p)) \,\cap\, \Sigma_t.$$

Here $D_M(\Sigma_M(p))$ denotes the unitary evolution of the wavefront generated by $D_M$ from the source event $p$, and $\Sigma_t$ denotes the observer's spatial slice at the observation time. The intersection is the geometric event that, in standard quantum mechanics, would be described as "the apparatus measuring the system."

Because $D_M$ and $\Sigma_M$ are co-generated with $\mathcal{M}_G$ by the same primitive law, the measurement event is not a meeting of two separate ontological categories (an operator-thing and a state-thing) but a *self-intersection* within one source structure. The operator-side flow produces a configuration that the space-side projection records. The Born-rule probability $|\psi|^2$ governing which configuration is produced (Proposition III.1) is determined by the SO(3)-Haar measure on $\Sigma_M$. The definiteness of the outcome (Proposition V.1) is a consequence of the projection $\pi_{x_{\text{obs}}}$ from $\mathcal{M}_G$ onto the observer's spatial slice. The unitarity of the underlying evolution (Propositions X.1 and X.2) is a consequence of the smoothness of $D_M$'s flow.

There is no measurement-mechanism that is separate from this geometric structure. The outcome is automatically Born-distributed (because the wavefront has SO(3)-Haar measure), automatically definite (because the projection picks out one configuration at the observer's location), and automatically consistent with unitary evolution (because $D_M$'s flow is unitary). All three features descend from the single co-generation $dx_4/dt = ic \Rightarrow (\mathcal{M}_G, D_M)$.

#### XIII.12.3 Why no other framework can do this

The structural reason no prior interpretive programme can dissolve the measurement problem in this way is now precise. Each prior programme operates within the standard categorical structure (space + operator + principle as three independent foundational layers). Within that structure, system, apparatus, observer, and dynamics are four distinct categories, and the measurement event is a *transition* between categories that requires its own structural account. Whatever account is given becomes the programme's signature contribution: the projection postulate (Copenhagen), the branching primitive (Many-Worlds), the guidance equation (Bohmian), the stochastic localization (GRW), the einselection coupling (decoherence), the relational primitive (RQM), or the agent (QBism).

Each of these contributions is a *new structural ingredient* introduced precisely because the standard categorical structure requires one. Each carries its own difficulties — the projection postulate is non-unitary, branching is ontologically extravagant, guidance equations require non-Lorentz-invariant foliations, stochastic localization has empirical free parameters, einselection imports the system-environment Hamiltonian, relational facts undermine observer-independence, and agents leave the framework subjective.

The McGucken dx₄/dt = ic framework avoids all of these difficulties not by improving on any one of them, but by eliminating the structural slot they fill. Because space and operator are co-generated, there is no "space-operator interface" requiring a special bridging mechanism. Because the principle is the source of both, there is no "first-cause for measurement" requiring an independent law. The measurement problem is dissolved at the level of the framework's category structure, before any of the standard interpretive choices arise.

This is the deepest structural fact about the McGucken dx₄/dt = ic framework: not that it solves the measurement problem better than other interpretations, but that the problem itself does not arise within its categorical structure. The space-operator co-generation theorem is what makes this dissolution possible. No prior framework has a co-generation theorem; that is the structural reason no prior framework has dissolved the measurement problem in this way.

---

### XIII.13 Historical context: who came close to the co-generation theorem, and why no one reached it

The co-generation theorem of §XIII.10 places the McGucken dx₄/dt = ic framework in a structural position that no prior framework occupies. This is not because previous physicists and mathematicians failed to recognize the importance of relating spaces to operators — on the contrary, several major figures in the history of mathematical physics came strikingly close to one or another aspect of co-generation. The honest historical account is that each came close in one direction but missed at least one of the three components (space, operator, primitive law) that the McGucken dx₄/dt = ic framework integrates. The present subsection surveys these historical relatives faithfully, identifying what each captured and what each missed.

#### XIII.13.1 Dirac (1928): first-order operators that square to second-order operators

Paul Dirac's 1928 derivation of the relativistic electron equation [80] introduced what became one of the most consequential operator constructions in physics: a first-order differential operator whose square is a second-order wave operator. Dirac's $i\gamma^\mu\partial_\mu - m$ satisfies, when squared, $(i\gamma^\mu\partial_\mu - m)(i\gamma^\nu\partial_\nu + m) = -(\square + m^2)$, providing a first-order route to relativistic spinorial propagation that the second-order Klein-Gordon equation could not supply.

*What Dirac captured.* The structural insight that a *first-order* operator can stand foundationally below a *second-order* operator that would otherwise appear primitive. The first-order Dirac operator has a deeper structural role than the second-order Klein-Gordon operator: the latter is the *square* of the former. This is the same structural pattern that holds in the McGucken hierarchy: $D_M$ stands first-order below the second-order $\square_M$ as $\square_M = (\Delta_4|_{\text{constraint}})$ projected from the four-coordinate Laplacian, and $\square_M + m^2$ admits the Dirac-McGucken first-order square root $\mathcal{D}_M$.

*What Dirac missed.* Dirac did not derive his operator from a deeper geometric principle. He worked backward from the Klein-Gordon equation, seeking a first-order operator whose square reproduced it. The Clifford algebra of gamma matrices was introduced to make the square-root construction work — it was a mathematical tool selected by the requirement of closure, not a structural consequence of a more primitive law. Dirac's operator therefore has the *form* of a source operator (first-order, with deep structural connections to the second-order operators) but lacks the *primitive signature* of a source operator. It does not contain $x_4$, it does not contain the flow law $dx_4/dt = ic$, and it does not generate the space on which it acts (Lorentzian spacetime is assumed prior to the construction of $\mathcal{D}$).

By the criteria of [13, Theorem 24.4]: *the Dirac operator is not identical to $D_M$. The Dirac operator captures the first-order/second-order structural relation but lacks the primitive signature.*

Dirac's later work on the Lagrangian formulation of quantum mechanics [81] hinted, in his characteristic compressed style, that "the propagator is analogous to $e^{iS/\hbar}$" — a remark that Feynman would later develop into the path-integral formulation [75]. This too had a flavor of source-structure (the action $S$ as the foundational physical content), but Dirac did not propose that $S$ generated either the space or the operator algebra. The remark remained heuristic.

#### XIII.13.2 Wheeler-DeWitt (1967): a constraint operator at the foundational level

The Wheeler-DeWitt equation [82, 83] is the canonical-quantization expression of general relativity in the ADM Hamiltonian framework. The equation $\hat{H}\Psi[h_{ij}] = 0$ asserts that the wave functional $\Psi$ on the space of spatial 3-metrics $h_{ij}$ is annihilated by the Hamiltonian constraint of general relativity. Wheeler famously interpreted this as expressing the timelessness of quantum gravity: the universe as a whole satisfies a constraint, not an evolution equation.

*What Wheeler-DeWitt captured.* The structural form of a *foundational constraint operator* — an operator that does not act inside a pre-given dynamical framework but expresses the foundational relation that the dynamical framework must satisfy. The equation $\hat{M}\Psi = 0$ in the McGucken dx₄/dt = ic framework (Definition XIII.6) has exactly this structural form: it is a constraint, not an evolution equation, and it expresses the foundational relation $dx_4/dt = ic$ in operator language. Wheeler's intuition that the deepest level of quantum gravity should be a constraint, not a Schrödinger equation, prefigures the structural form of the quantum McGucken constraint.

*What Wheeler-DeWitt missed.* The equation acts on a wave functional over the space of spatial 3-metrics — a space that is *itself postulated*, not derived. The configuration space of $h_{ij}$ is the input, the constraint $\hat{H}\Psi = 0$ is then defined on it. The Hamiltonian operator $\hat{H}$ is constructed from the ADM decomposition of general relativity, which presupposes the Lorentzian structure and the metric formulation of gravity. The Wheeler-DeWitt equation is therefore a constraint *within* a pre-existing formulation, not the source of that formulation. It has the *structural form* of a foundational constraint but lacks the *generative power* to produce the space on which it acts.

By the criteria of [13, Theorem 24.7]: *the Wheeler-DeWitt constraint is not identical to $D_M$. Wheeler-DeWitt is a constraint operator within canonical quantum gravity; $D_M$ is generated before any canonical configuration-space machinery and supplies the source-pair that generates configuration space, Hilbert space, and constraint together.*

The contrast is sharp. Wheeler-DeWitt asks: given the configuration space of 3-metrics, what constraint must the wave functional satisfy? McGucken asks: from the source-law $dx_4/dt = ic$, what space and what operator are co-generated, and what constraint do they jointly satisfy? Wheeler-DeWitt operates within a derived structure; the McGucken dx₄/dt = ic framework operates at the source.

#### XIII.13.3 Connes (1980s–1990s; descent identification 2026): the spectral triple as descent image of the McGucken Source-Tuple

Alain Connes's spectral-triple formulation of noncommutative geometry [84] proposes that geometric data can be encoded in the triple $(\mathcal{A}, \mathcal{H}, D)$ — an algebra $\mathcal{A}$, a Hilbert space $\mathcal{H}$ on which $\mathcal{A}$ is represented, and a self-adjoint operator $D$ (the Dirac operator, in the canonical example) satisfying suitable boundedness and commutation properties. The metric structure of the underlying geometry is recoverable from the spectral data of $D$ via Connes's distance formula $d(p,q) = \sup\{|f(p) - f(q)| : f \in \mathcal{A},\, \|[D,f]\| \leq 1\}$. Subsequent work by Connes and collaborators extended this to quantum-field-theoretic settings, with the Standard Model action recoverable from a spectral-action principle [85]. Connes's reconstruction theorem [86] further established that, in the commutative case, every spectral triple satisfying seven axioms (regularity, finiteness, orientability, Poincaré duality, real structure, first-order condition, dimension) arises canonically from a unique smooth oriented Riemannian spin manifold.

*What Connes captured.* The structural insight that *geometry can be encoded by an operator* — the operator $D$ in the spectral triple is not merely an operator acting on a pre-given space but a structural ingredient that, together with the algebra and Hilbert space, encodes the geometry. The spectral-triple framework, of all the historical relatives surveyed in this section, comes closest in mathematical content to the McGucken co-generation theorem: it treats space and operator as deeply linked, with the operator carrying genuine geometric content, and Connes's reconstruction theorem demonstrates that the operator-side data $(\mathcal{A}, \mathcal{H}, D)$ is mathematically *sufficient* to recover the manifold side.

*The pair-paper structural claim.* The McGucken pair-paper [87] examines whether Connes's spectral triple, considered as primitive triple data, satisfies the three structural theorems that the McGucken source-pair $(\mathcal{M}_G, D_M)$ does satisfy: Mutual Containment (MCC), Reciprocal Generation (RGC), and Containment-Generation Equivalence (CGE). The pair-paper establishes that Connes's spectral triple, *taken as primitive triple data*, fails all three: the algebra, the Hilbert space, and the Dirac operator are postulated together as a triple of structured-space data, with no single physical relation among them generating all three from one source. Mutual Containment fails (the algebra does not "contain" the Dirac operator as an algebraic theorem); Reciprocal Generation fails (no constructive procedure produces the operator from the algebra and vice versa, by mutually inverse maps using only elementary operations); Containment-Generation Equivalence fails because both halves fail. Source-pair structure (MCC + RGC + CGE) is what the McGucken pair $(\mathcal{M}_G, D_M)$ has and Connes's triple lacks.

*The Connes-descent paper.* The McGucken Connes-descent paper [1] resolves this apparent tension by establishing that Connes's spectral triple is *not* a competing source-pair but a *downstream descent image* of the McGucken Source-Tuple $F_M = (\Sigma_M, \mathcal{G}_M, \mathcal{M}_G, D_M, \mathcal{S}_M, \mathcal{A}_M)$ established in [88]. The principal results of that paper, summarized:

- **Theorem A** [1, §4]: The triple $(C^\infty(\mathcal{M}), L^2(\mathcal{M}, S), D_\mathcal{M})$ — the *McGucken-Dirac spectral triple* — derived from $dx_4/dt = ic$ at Wick angle $\theta = \pi/2$ via the McGucken Space construction, the Hilbert-space emergence theorem [12, Theorem 12.1], and the Dirac-operator construction [13] satisfies all seven Connes axioms.
- **Theorem D** [1, §7]: When Connes's reconstruction theorem [86] is applied to the McGucken-Dirac spectral triple, the Riemannian spin manifold it produces is canonically isomorphic to the McGucken Euclidean four-manifold $\mathcal{M}$ underlying $\mathcal{M}_G$. Connes's reconstruction is the formal inverse of the McGucken descent: one direction projects $\mathcal{M}$ to the spectral triple; the other reconstructs $\mathcal{M}$ from the spectral triple.
- **Theorem F** [1, §9]: The heat-kernel asymptotic expansion of $\mathrm{Tr}\, f(D/\Lambda)$ at the McGucken-substrate cutoff $\Lambda = M_P c^2/\hbar$ produces, in its Seeley-DeWitt coefficients $a_0, a_2, a_4$, terms in structural correspondence with the four sectors of the McGucken Lagrangian $\mathcal{L}_{\rm McG} = \mathcal{L}_{\rm kin} + \mathcal{L}_{\rm Dirac} + \mathcal{L}_{\rm YM} + \mathcal{L}_{\rm EH}$ established in [2]: cosmological constant $\leftrightarrow a_0$, Einstein-Hilbert $\leftrightarrow a_2$, Yang-Mills + Higgs potential $\leftrightarrow a_4$.
- **Theorem G** [1, §13]: There exists a *faithful descent functor* $F_{\rm Spec}: \mathrm{McG}_6 \to \mathrm{SpecTriple}_{\rm comm}$ from the six-object McGucken category to the category of commutative spectral triples, sending the source-tuple $F_M$ to the McGucken-Dirac spectral triple. The functor factors through the source-axiom point $\bullet$ of [88, Theorem 7.29].
- **Theorem H** [1, §11A]: The Chamseddine-Connes-Mukhanov "quanta of geometry" [48] — the Planck-volume four-spheres into which a noncommutative four-manifold decomposes under the higher Heisenberg commutation relation — are derivationally identical to the McGucken Spheres at substrate scale.

*The structural reason for the McGucken-Connes correspondence.* The McGucken Principle $dx_4/dt = ic$ possesses **dual-channel content** [1, §1.6; 44] — a structural feature that places the McGucken Symmetry as the Father Symmetry of physics, beneath every other physical symmetry, in the depth ladder of [44, §18.4]. Channel A (algebraic-symmetry) — the uniform invariant rate $ic$ of $x_4$'s advance — drives the operator-formal side of physics and supplies the algebraic content of the spectral triple (Connes axioms C1, C2, C5, C6). Channel B (geometric-propagation) — the spherical symmetry of $x_4$'s advance about every event — drives the path-integral side and supplies the geometric content of the spectral triple (Connes axioms C3, C4, C7). The dual-channel character of $dx_4/dt = ic$ is precisely what makes the McGucken framework able to derive Connes's framework as theorems rather than as postulates: the two contents that Connes axiomatizes simultaneously (algebraic + geometric) are present simultaneously in the single statement $dx_4/dt = ic$.

*The categorical position.* Both pair-paper and Connes-descent paper conclusions are simultaneously true and mutually consistent. The pair-paper observes that Connes's spectral triple, considered as a triple of co-primitive structured-space data, fails the source-pair tests (MCC, RGC, CGE). The Connes-descent paper observes that the same triple, considered as a *descent image*, is derivable from the genuine source-tuple $F_M$ via the descent functor $F_{\rm Spec}$. Source-pairs satisfy MCC/RGC/CGE; descent images, in general, do not — and need not, because they are derivative objects whose foundational status is inherited from their source rather than possessed in their own right.

*Position relative to the present paper.* For the measurement-problem and information-paradox content of the present paper, the relevant takeaway is the following: Connes's framework is the deepest existing mathematical formulation of noncommutative geometry coupled to physics, and it descends from the McGucken Principle as a chain of theorems via the descent functor $F_{\rm Spec}$. Connes's reconstruction theorem, run in reverse from the spectral triple back to the manifold, recovers the McGucken Euclidean four-manifold $\mathcal{M}$ — making Connes's theorem *the formal shadow of the McGucken dx₄/dt = ic framework projected into noncommutative-geometric language*. The space-operator co-generation theorem (Theorem XIII.I) of the present paper sits structurally upstream of the entire Connes apparatus: where Connes establishes that operator-side data on a spectral triple suffices to recover the underlying manifold (a unidirectional recovery theorem in the commutative case), the McGucken dx₄/dt = ic framework establishes that both the operator and the space co-generate from a single primitive physical law (a co-generation theorem from a prior third structure that no formulation of Connes's framework supplies). The present paper's structural claim that the measurement problem is dissolved by the co-generation of $\mathcal{M}_G$ and $D_M$ (Proposition XIII.6) cannot be made within Connes's framework because Connes's framework does not have the prior-third-structure content; it can be made within the McGucken dx₄/dt = ic framework because the McGucken dx₄/dt = ic framework does.

#### XIII.13.4 Wick (1954): imaginary-time as analytic continuation

Gian-Carlo Wick's 1954 paper [89] introduced what became the standard technique of analytic continuation between Lorentzian and Euclidean signatures: the substitution $t \to -i\tau$ (equivalently, $\tau = it$) converts the oscillatory time integrals of relativistic quantum mechanics into convergent Euclidean integrals. This transformation became foundational to the path-integral formulation of quantum field theory, the Osterwalder-Schrader axioms, and the rigorous construction of relativistic field theories.

*What Wick captured.* The fundamental structural fact that the imaginary unit $i$ appearing in time evolution and in the action is the same $i$ that converts Lorentzian to Euclidean signature. The Wick rotation $t \to -i\tau$ preserves more than analytic structure — it expresses a deep relationship between time, the complex unit, and the metric signature.

*What Wick missed.* In Wick's treatment and the subsequent literature, the rotation $t \to -i\tau$ is an *analytic prescription*, not a derivative-level identity from a primitive law. The substitution is justified by the analytic properties of correlation functions and by the requirement of convergence; it is not derived from a deeper structural source. The $i$ in the rotation is the same algebraic $i$ that appears in $\hbar$-quantization, but the *physical* origin of that $i$ — why it should be the same $i$ that converts Lorentzian to Euclidean signature — is not addressed.

By Theorem XIII.E of the present paper (cf. [13, Theorem 10.1]), the Wick rotation is the immediate derivative-level consequence of the McGucken Principle: from $x_4 = ict$, one obtains $\partial_{x_4} = -(i/c)\partial_t$ and, setting $\tau = x_4/c$, $\tau = it$. The Wick rotation is therefore not an analytic prescription but a structural identity descending from $D_M$'s flow.

By the criteria of [13, Theorem 24.8]: *Wick rotation is not identical to $D_M$. Wick rotation is the projection of the McGucken constraint to the imaginary-time identity; $D_M$ is the source operator from which Wick rotation descends as a derivative-level fact.*

#### XIII.13.5 Geometric quantization (Kostant, Souriau, 1970): operator construction from phase space

Geometric quantization [90, 91] is the program of constructing quantum operators from a classical symplectic phase space via prequantization, polarization, and metaplectic correction. Given a symplectic manifold $(M, \omega)$, the prequantization line bundle and the choice of polarization produce a Hilbert space, and classical observables (functions on $M$) lift to quantum operators on this Hilbert space.

*What geometric quantization captured.* The structural fact that classical phase space, by itself, contains enough geometric information to determine — up to choices of polarization and bundle — both the Hilbert space and the operator algebra of the quantum theory. The symplectic form $\omega$ on $M$ generates everything else.

*What geometric quantization missed.* The symplectic phase space $(M, \omega)$ is itself postulated. The quantization procedure recovers operators and Hilbert spaces from this prior input but does not derive the input from a more primitive physical law. The choices of polarization and metaplectic correction are not uniquely determined; different choices give inequivalent quantizations. The framework provides a structural *route* from phase space to quantum theory but does not supply the source-law that generates phase space itself.

The contrast with the McGucken dx₄/dt = ic framework is the contrast between starting from $(M, \omega)$ and starting from $dx_4/dt = ic$. Geometric quantization works one level above the McGucken dx₄/dt = ic framework's foundational layer: phase space is, in the McGucken hierarchy, a derivative of $\mathcal{M}_G$ via cotangent lift over a derived configuration space (cf. [12, §16.4]).

#### XIII.13.6 Newton-Wigner (1949): operator-encoded localization

The Newton-Wigner localization [92] addresses the problem of defining position operators for relativistic particles in a Lorentz-covariant way. Newton and Wigner showed that, under certain natural axioms, there is a unique position operator on the one-particle Hilbert space of a Poincaré-irreducible representation. The construction is structurally interesting because it uses operator content (the position operator) to encode geometric content (localization).

*What Newton-Wigner captured.* The use of an operator to encode a geometric property (position) that, in non-relativistic quantum mechanics, would be a primitive coordinate. The position operator is not an external geometric input — it is constructed from group-theoretic data on the Hilbert space.

*What Newton-Wigner missed.* The construction presupposes the one-particle Hilbert space of an irreducible Poincaré representation, which itself presupposes Lorentzian spacetime, the Poincaré group, and the irreducible-representation theory of relativistic quantum mechanics. The position operator is recovered from these inputs but is not generated from a more primitive law. Moreover, the Newton-Wigner position operator is famously *non-Lorentz-covariant in the spacetime sense* — the localization it provides is frame-dependent at the relativistic level.

The contrast with the McGucken dx₄/dt = ic framework: Newton-Wigner constructs an operator from a postulated Hilbert space and group structure. The McGucken dx₄/dt = ic framework generates both the operator and the space from a primitive law, with the spatial coordinates of $\mathcal{M}_G$ supplying the position content directly through the structure of the spatial slice $\Sigma_t$.

#### XIII.13.7 Earlier hints: Hamilton, Noether, Heaviside

The deepest historical roots reach back to Hamilton, Noether, and Heaviside. Hamilton's mechanics (1830s) showed that a function on phase space — the Hamiltonian $H$ — could *generate* dynamics, with the equations of motion deriving from $H$ via the symplectic structure. Noether's theorem (1918) [93] established that continuous symmetries of an action correspond to conservation laws via *generators* — infinitesimal operators encoding the symmetry. Heaviside's operational calculus (1880s–1890s) treated differential operators algebraically, anticipating the operator algebraic methods of quantum mechanics.

*What these captured.* The fundamental insight that *operators are generators* — that the deepest structural role of an operator in physics is not to act on a pre-given state but to generate transformations, conservation laws, or dynamics. The McGucken Operator $D_M$ is, in this lineage, the operator-form of the foundational physical-geometric postulate $dx_4/dt = ic$ — it is the generator of fourth-dimensional advance, in the same structural sense that Hamiltonian operators generate time evolution and Noether generators encode continuous symmetries.

*What these missed.* None of Hamilton, Noether, or Heaviside proposed that operator and space could be co-generated by a single primitive law. Hamilton's $H$ acts within a postulated phase space. Noether's generators act within a postulated action functional. Heaviside's operational methods are calculational tools within postulated differential equations. Each is a step toward the source-operator concept but stops short of the co-generation theorem.

#### XIII.13.8 The historical pattern

The historical pattern that emerges from this survey is striking. Across more than a century of mathematical physics, the principal figures who came closest to source-operator structure each captured one or two of the three components — space, operator, primitive law — but missed at least one. Dirac captured the first-order/second-order operator relation but lacked the primitive law. Wheeler-DeWitt captured the foundational constraint form but lacked the source-space generation. Connes captured the operator-encoded geometry but presupposed the space and algebra as inputs. Wick captured the imaginary-time identity but treated it as analytic continuation rather than derivative-level fact. Geometric quantization captured the phase-space-to-Hilbert-space route but presupposed phase space. Newton-Wigner captured operator-encoded localization but presupposed the Hilbert space. Hamilton, Noether, and Heaviside captured the generator-form of operators but did not propose space-operator co-generation.

The McGucken dx₄/dt = ic framework integrates all of these partial captures into one structural fact via the co-generation theorem. The first-order/second-order relation of Dirac is recovered as $\mathcal{D}_M = i\gamma^\mu\partial_\mu - m$ being the Clifford square root of $\square_M$, with $\square_M$ itself a projection of $D_M$. The constraint form of Wheeler-DeWitt is recovered as $\hat{M}\Psi = 0$, with $\hat{M} = i\hbar D_M = \hat{H} - ic\hat{p}_4$ supplying the constraint at the source level rather than the canonical-quantization level. The spectral-triple structure of Connes is recovered as the algebra $\mathcal{A}_M \subseteq \mathcal{B}(\mathcal{H})$ generated by quantized descendants of $D_M$ acting on $\mathcal{H}$ derived from $\mathcal{M}_G$. The Wick rotation is recovered as Theorem XIII.E. The phase-space-to-Hilbert-space route is recovered as the universal derivability principle of [12]. The Newton-Wigner localization is recovered as the projection $\pi_{x_{\text{obs}}}$ from $\mathcal{M}_G$ onto the spatial slice. The Hamilton-Noether-Heaviside generator structure is recovered as $D_M$ being the generator of the McGucken flow, with the Noether structure given by Theorem 16.1 of [13].

The historical pattern is therefore not that the McGucken dx₄/dt = ic framework dismisses prior work — it is that the McGucken dx₄/dt = ic framework *integrates* prior work into one structural fact via the co-generation theorem. Each historical figure who came close to source-operator structure was right about what they captured; what they missed was the co-generation that would have integrated their captured structure with the rest.

#### XIII.13.9 Tabular summary of historical relatives

| Historical figure / framework | What was captured | What was missed | Status relative to $D_M$ |
|---|---|---|---|
| Hamilton (1830s) | Operator as generator of dynamics | Space-operator co-generation; primitive physical law | Hamiltonian is $t$-sector of $\hat{M} = i\hbar D_M$ |
| Heaviside (1880s–1890s) | Algebraic manipulation of differential operators | Foundational generation of operators from a primitive law | Operational calculus is calculational; $D_M$ is generative |
| Noether (1918) | Symmetry-generator correspondence | Symmetry that generates the space on which it acts | $D_M$ is the generator of the McGucken Symmetry |
| Dirac (1928) | First-order operator squaring to second-order | Primitive law generating the operator | $\mathcal{D}_M$ is Clifford square root of $\square_M$, descending from $D_M$ |
| Dirac (1933) | Action-as-foundation hint via $e^{iS/\hbar}$ | Source-law generating action and operator algebra together | The $i$ in $e^{iS/\hbar}$ is the same $i$ as in $D_M$ |
| Wick (1954) | Imaginary-time analytic continuation | Derivative-level identity from primitive law | Wick is Theorem XIII.E, descendant of $D_M$ |
| Newton-Wigner (1949) | Operator-encoded localization | Source-space generating the localization structure | Recovered as projection $\pi_{x_{\text{obs}}}$ in $\mathcal{M}_G$ |
| Wheeler-DeWitt (1967) | Foundational constraint form $\hat{H}\Psi = 0$ | Source-space generated by the constraint itself | $\hat{M}\Psi = 0$ is constraint at the source level |
| Geometric quantization (1970) | Phase-space-to-Hilbert-space route | Primitive law generating phase space | Recovered as universal derivability principle |
| Spectral triple (Connes 1980s–1990s) | Operator-encoded geometry | Primitive law generating algebra and Hilbert space | $\mathcal{A}_M$ on $\mathcal{H}$ derived from $\mathcal{M}_G$ |
| **McGucken (2026)** | **Space-operator co-generation from primitive law** | — | **$dx_4/dt = ic \Rightarrow (\mathcal{M}_G, D_M)$** |

The structural conclusion is that the McGucken dx₄/dt = ic framework occupies a position in the categorical structure of mathematical physics that no prior framework has occupied. The novelty is not that the framework introduces a new technique or produces a new calculation — it is that the framework's category structure differs from all prior frameworks at the foundational level, with the co-generation theorem supplying the structural reason this difference makes the dissolution of the measurement problem possible.

---

#### XIII.13.10 Wheeler's self-excited circuit (1983): the heuristic image whose formal mathematics is the co-generation theorem

Among the historical relatives surveyed in this section, one stands apart in directness — not because Wheeler proposed any of the formal mathematics that the McGucken dx₄/dt = ic framework develops, but because Wheeler proposed a *heuristic image* of exactly the structural fact that the co-generation theorem formalizes. The image, drawn by Wheeler in his 1983 article "Law Without Law" [94] and reproduced as Fig. 22.13 of *Quantum Theory and Measurement*, depicts the universe as a self-excited circuit: a U-shaped object with a thin tip at the upper right (the early universe), a curved loop at the bottom (cosmological evolution), and an eye at the upper left (the observer), with a dashed line from the eye back to the tip representing what Wheeler called observer-participancy — the closing of the loop through which "acts of observer-participancy [via the mechanism of the delayed-choice experiment] in turn give tangible 'reality' to the universe, not only now but back to the beginning" [94, p. 209].

The diagram has a precise structural content that any underlying mathematics must reproduce. The U-shape requires:

**(W-A)** The universe is one connected object, not a collection of separately postulated entities.

**(W-B)** Observer and observed are co-derived from the same object — the eye and the tip are both parts of the U, not external categories that come together at measurement.

**(W-C)** Observation acts not via temporal succession along the U-curve alone but via a *transverse* connection across the structure (Wheeler's dashed line), which is the geometric content of delayed-choice experiments and the participatory closure of the circuit.

Wheeler proposed (W-A), (W-B), and (W-C) as desiderata for a foundational physics that would close his vision of the participatory universe — but he did not propose mathematics that would make any of them rigorous. The serious literature on Wheeler's diagram has explicitly acknowledged this gap. Manousakis [14] writes: "In Wheeler's article the gap between acts of observer-participancy and physical reality was not filled in, an insufficiency that we attribute to the absence of an appropriate theory of observation." Fuchs [95] observes that Wheeler's thinking was "not well-defined enough to be *right* or *wrong*." Wheeler himself, in his most candid moments, acknowledged that his "law without law" had only "a higgledy-piggledy way to build law: out of the statistics of billions upon billions of acts of observer-participancy each of which by itself partakes of utter randomness" [94, p. 22; cited in 96]. Penrose called the proposal "barely credible" [97, cited in 95].

The McGucken dx₄/dt = ic framework supplies the missing formal mathematics. The space-operator co-generation theorem of §XIII.10, together with the universal derivability principles of [12] and [13] and the First Law of Nonlocality of [9], reproduces all three structural features of Wheeler's diagram from the single primitive law $dx_4/dt = ic$. The mapping is structural and direct.

##### XIII.13.10.1 The structural correspondence

We state the correspondence explicitly. Let the U-curve in Wheeler's diagram be parameterized by an external parameter that traces cosmological evolution from the initial event (tip at upper right) through the loop to the observer-event (upper left); let the eye represent the observer's spatial slice $\Sigma_t$ at the present cosmological time; let the dashed line represent the observer-participancy connection that closes the circuit.

**(W-A) → ℳ_G as one connected object.** The McGucken Space $\mathcal{M}_G = (E^4, \Phi_M, D_M, \Sigma_M)$ is a single structured arena. By the universal derivability principle (Theorem 15.1 of [12]), every physically meaningful space — Lorentzian spacetime, Hilbert space, configuration space, phase space, gauge bundles, Fock space, operator algebras, the cosmological observer, the early universe — is derivable from $\mathcal{M}_G$ by a finite sequence of admissible physical-space operations. The U-curve traced by Wheeler's diagram is, in McGucken language, the cosmological worldline along which $x_4$ has advanced from $x_4 = 0$ at the initial event to $x_4 = ict_{\text{obs}}$ at the observer's present. The "single connected object" of (W-A) is $\mathcal{M}_G$ itself. **(W-A) is satisfied by ℳ_G.**

**(W-B) → Co-generation theorem: observer and observed are co-derived.** The space-operator co-generation theorem (Theorem XIII.I) establishes that the source-pair $(\mathcal{M}_G, D_M)$ is generated by $dx_4/dt = ic$ as a single structural object, with the universal derivability principles establishing that *every* physical entity descends from this source-pair via admissible operations. The early universe at the tip of the U is a configuration in $\mathcal{M}_G$ — specifically, the spatial slice $\Sigma_{t \to 0}$ near the initial event. The observer at the upper left is also a configuration in $\mathcal{M}_G$ — the spatial slice $\Sigma_{t_{\text{obs}}}$ at the present cosmological time, with the observer's apparatus realized as a Compton-frequency-coupled massive system within that slice (Proposition VII.1). Both endpoints of the U are derivatives of one source-pair. The "observer and observed co-derived from the same object" of (W-B) is the co-generation theorem itself. **(W-B) is satisfied by Theorem XIII.I.**

**(W-C) → x₄-coincidence: the dashed line as transverse structural connection.** The dashed line in Wheeler's diagram — connecting the eye to the tip across the U rather than along it — is the structural feature that distinguishes his diagram from any merely temporal-causal cosmological story. This line represents what Wheeler called observer-participancy through the delayed-choice mechanism: the observer's act "reaches back" to the early universe in a way that is not the running-backward of the U-curve but a *transverse* connection across the structure.

In the McGucken dx₄/dt = ic framework, the formal content of this transverse connection is the First Law of Nonlocality [9]: *all nonlocality begins in locality*. Two events that are spatially-temporally separated along the cosmological U-curve may yet be x₄-coincident — sharing a common past x₄-event through the McGucken Sphere structure, with their entanglement and correlation manifesting in 3D+t as nonlocal. Proposition VIII.1 of the present paper establishes this formally: quantum nonlocality is the geometric consequence of x₄-mediated correlation through the six-sense null-surface identity of the McGucken Sphere.

Applied to Wheeler's diagram: the observer's measurement event at the upper left of the U is x₄-coincident with the early universe at the tip through the McGucken Sphere structure of cosmological evolution. The observer's act of observation does not propagate backward along the U-curve in the sense of violating relativistic causality — relativistic causality along $x_1 x_2 x_3$-$t$ is preserved (Proposition VIII.1). Rather, the observer-event and the early-universe-event share x₄-coincidence in the geometric sense established by the First Law of Nonlocality. The dashed line is the x₄-axis itself, perpendicular to the cosmological U-curve, supplying the transverse connection that delayed-choice experiments make manifest at laboratory scales (the Wheeler-Marlan-Scully 1983 delayed-choice quantum eraser; Kim, Yu, Kulik, Shih, and Scully 2000 [98]; Manning, Khakimov, Dall, and Truscott 2015 [99]).

The "tangible reality" that Wheeler's observer imparts to the early universe is, in McGucken language, the structural feature of x₄-coincidence: the measurement event and the source event share x₄ even when separated by cosmological time along the U-curve. Observer-participancy is the Born-distributed cross-section reading (Proposition V.1, with probabilities given by Proposition III.1's Born rule from spherical SO(3)-Haar measure on $\Sigma_M$) that selects which configuration of the four-dimensional state $|\Psi\rangle$ the observer's spatial slice intersects. The "self-excited circuit" closes because the observer-event and the source-event are part of the same expanding McGucken Sphere from the early universe — they are, in the geometric sense, points on one wavefront. **(W-C) is satisfied by the First Law of Nonlocality and Proposition VIII.1.**

##### XIII.13.10.2 The McGucken-Wheeler correspondence stated formally

The correspondence can be stated as the following structural identification, which is interpretive (not formally derived, since Wheeler's diagram is heuristic rather than mathematical) but which is precise enough to be checkable against each structural feature of the diagram.

**The McGucken-Wheeler correspondence.** *Wheeler's self-excited-circuit diagram (Fig. 22.13 of [94]) is the heuristic image of the structure formalized by the space-operator co-generation theorem (Theorem XIII.I), the universal derivability principles of [12] and [13], and the First Law of Nonlocality of [9]. The correspondence is:*

| Feature of Wheeler's diagram | Heuristic content | McGucken formal content | Source theorem |
|---|---|---|---|
| The U-shape | The universe as one connected object | $\mathcal{M}_G = (E^4, \Phi_M, D_M, \Sigma_M)$ as source-space | Theorem 12.1 of [12] |
| Thin tip at upper right | Early universe / initial event $p_0$ | Spatial slice $\Sigma_{t \to 0}$ at the McGucken-FRW initial event | Universal derivability principle |
| Curved loop of the U | Cosmological evolution from $p_0$ to observer | Worldline along which $x_4$ advances from $x_4 = 0$ to $x_4 = ict_{\text{obs}}$ | $dx_4/dt = ic$ generates the cosmological worldline |
| Eye at upper left | Observer; locus of observation | Observer's spatial slice $\Sigma_{t_{\text{obs}}}$ as configuration in $\mathcal{M}_G$ | Proposition VII.1 (Compton-frequency-coupled apparatus) |
| Dashed line from eye to tip | Observer-participancy / delayed-choice closure | x₄-coincidence between observer-event and source-event via McGucken Sphere | Proposition VIII.1; First Law of Nonlocality |
| "Tangible reality" imparted by observation | Observer creates reality of past | Born-distributed cross-section reading at $\pi_{x_{\text{obs}}}$ selecting configuration of $|\Psi\rangle$ | Proposition V.1; Proposition III.1 |
| Self-excited circuit closure | Universe bootstraps itself through self-observation | $D_M(\Sigma_M(p_0)) \cap \Sigma_{t_{\text{obs}}}$ is the geometric self-intersection of the source-pair | Theorem XIII.I; Proposition XIII.6 |
| "It from bit" | Reality from information | Information preservation theorem: information is x₄-coincidence content | Proposition X.1 |
| "Law without law" | No primary cause; observer-participancy builds law | The single source-law $dx_4/dt = ic$ generates space, operator, and dynamics together | Co-generation theorem (Theorem XIII.I) |

##### XIII.13.10.3 Why Wheeler reached for the image without being able to formalize it

The historical pattern surveyed in §XIII.13 — that each major figure who came close to source-operator structure captured one or two of the three components but missed at least one — finds its most striking instance in Wheeler. Wheeler captured *all three* of the structural features (W-A), (W-B), (W-C) in his self-excited-circuit image. He also articulated, in surrounding writings, much of the conceptual content of "law without law," "it from bit," "no phenomenon is a phenomenon until it is an observed phenomenon," and the participatory anthropic principle [94, 71]. What he did *not* propose — and what the present framework supplies — is the formal physical-mathematical content that makes (W-A), (W-B), (W-C) rigorous theorems of a single primitive law.

Wheeler did not propose $dx_4/dt = ic$. He did not derive the Born rule from spherical SO(3)-Haar measure on a McGucken Sphere wavefront. He did not formulate the space-operator co-generation theorem. He did not articulate the First Law of Nonlocality as the formal content of x₄-coincidence. He did not establish that the apparent collapse $R$ is the cross-section reading of an x₄-extended state. He did not derive the Hilbert-space inner product, the canonical commutator, or the Dirac operator as theorems of a source-operator. None of the formal mathematics of the McGucken dx₄/dt = ic framework appears in Wheeler's writings.

What Wheeler *did* propose was the heuristic image of a structure that, in 2026, the McGucken dx₄/dt = ic framework formalizes. The historical resonance is striking but should not be overstated. Wheeler did not foresee the McGucken dx₄/dt = ic framework; he proposed an image that, with hindsight, the framework makes precise. The relationship between Wheeler's 1983 diagram and the 2026 McGucken dx₄/dt = ic framework is the relationship between heuristic vision and formal mathematics — a relationship analogous to the relationship between Faraday's 1830s diagrams of magnetic field lines and Maxwell's 1860s formal equations of electromagnetism, or between Einstein's 1908 thought experiments on accelerated frames and the 1915 formal mathematics of general relativity.

##### XIII.13.10.4 A note on the Wheeler-McGucken historical line

The author of the present paper studied with John Archibald Wheeler at Princeton, with Wheeler's recommendation reading: "More intellectual curiosity, versatility, and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet" [Wheeler personal recommendation, in McGucken dissertation, UNC Chapel Hill, 1999]. The dissertation appendix [100] contains the first written record of what would become the McGucken Principle. It is a matter of historical record, not of inference, that Wheeler's intellectual influence was formative for the framework developed in the present paper and in the broader corpus of [30, 6, 9, 12, 13] and elsewhere.

The historical line from Wheeler to McGucken passes through Wheeler's own preoccupations: the participatory universe, the delayed-choice experiment, the it-from-bit programme, the law-without-law programme, and the self-excited circuit. The McGucken dx₄/dt = ic framework's formal content is original to the author and to the broader corpus, but the structural intuitions it formalizes are recognizably continuous with Wheeler's vision. The Wheeler quotation that closes the present paper — "Behind it all is surely an idea so simple, so beautiful, that when we grasp it — in a decade, a century, or a millennium — we will all say to each other, how could it have been otherwise?" — refers, in the McGucken framework, to $dx_4/dt = ic$. The McGucken-Wheeler correspondence formalized in this subsection is the answer, in 2026, to the question Wheeler asked in 1983.

##### XIII.13.10.5 Why no other framework reproduces all three Wheeler features

The structural distinctness of the McGucken dx₄/dt = ic framework with respect to Wheeler's diagram can be tabulated. The seven major interpretive programmes plus the major historical operator constructions are surveyed for whether each of (W-A), (W-B), (W-C) is reproduced.

| Framework | (W-A) Universe as one object | (W-B) Observer co-derived with observed | (W-C) Transverse / delayed-choice connection | All three? |
|---|---|---|---|---|
| Copenhagen | No — Heisenberg cut separates system from apparatus | No — observer is external | No — cut prohibits transverse connection | No |
| Many-Worlds | Yes — universal wave function | Partial — observer is a branch, but branches are forward in time | No — branching is causal-temporal, not transverse | No |
| Bohmian mechanics | Partial — wave function on configuration space + particles | No — two-ontology structure | Partial — configuration-space nonlocality, but in 3N-dim, not physical 4D | No |
| GRW | Partial — modified Hilbert space | No — observer not specially treated | No — collapse is local in spacetime | No |
| Decoherence + einselection | Yes — system+environment+observer in one Hilbert space | Partial — observer is part of environment | No — einselection is local | No |
| Relational Quantum Mechanics | Partial — relational facts | Yes — observer is part of the relational structure | No — relations do not supply transverse connection | No |
| QBism | No — agent-relative, no observer-independent reality | Partial — agent is part of the structure | No — transverse connection not formalized | No |
| Cramer's Transactional Interpretation | Yes — universe as one transactional structure | Yes — emitter and absorber both part of the handshake | Yes — advanced/retarded waves supply transverse connection in *pseudo*-time | Partial — but in pseudo-time, not physical time, with Born rule imported (cf. [101]) |
| Penrose gravitational collapse | Partial — mass superpositions sourcing collapse | No — observer not explicitly modeled | No — gravitational collapse is local | No |
| Wheeler-DeWitt | Yes — universal wave functional | Partial — observer not explicitly modeled in canonical structure | No — no transverse connection in the formalism | No |
| Connes spectral triples | Yes — geometric data in $(\mathcal{A}, \mathcal{H}, D)$ | No — observer not explicitly part of the triple | No — transverse connection not formalized | No |
| **McGucken dx₄/dt = ic framework** | **Yes — $\mathcal{M}_G$ as source-space** | **Yes — co-generation theorem (Theorem XIII.I)** | **Yes — First Law of Nonlocality and x₄-coincidence (Proposition VIII.1)** | **Yes** |

The transactional interpretation of Cramer is the prior framework that comes structurally closest to reproducing all three features of Wheeler's diagram, and indeed Cramer's framework was developed in part as a response to similar Wheeler-influenced concerns. But Cramer's transverse connection occurs in pseudo-time rather than physical time, and the Born rule is imported rather than derived (as established in detail in [101]). The McGucken dx₄/dt = ic framework reproduces all three features in physical 4D spacetime with the Born rule derived from spherical SO(3)-Haar measure on the McGucken Sphere wavefront cross-section.

##### XIII.13.10.6 Summary

Wheeler's 1983 self-excited-circuit diagram has stood for more than four decades as the most evocative visual proposal for a participatory, observer-involved cosmology. The accompanying writings — "Law Without Law," "It from Bit," the Participatory Anthropic Principle — have been profoundly influential while remaining widely acknowledged as lacking the formal physical-mathematical content that would make them rigorous physics. The McGucken dx₄/dt = ic framework supplies that formal content. The U-curve is the cosmological worldline along which $x_4$ advances; the eye and the tip are configurations in the source-space $\mathcal{M}_G$; the dashed line is x₄-coincidence supplied by the First Law of Nonlocality; observer-participancy is the cross-section reading of Proposition V.1, Born-distributed by Proposition III.1; the self-excited closure is the geometric self-intersection $D_M(\Sigma_M) \cap \Sigma_t$ of the co-generated source-pair with itself; and the law-without-law is the single source-law $dx_4/dt = ic$ from which space, operator, and all derived dynamics descend together. The framework formalizes Wheeler's 1983 vision in 2026 mathematics, with the historical line from Wheeler's Princeton mentorship of the author through to the present paper preserved as a matter of record but with the formal content original to the McGucken corpus.

---

#### XIII.13.11 The greats on observer and observed: direct quotations from Bohr, Heisenberg, Schrödinger, Wigner, von Neumann, Bohm, and Wheeler

The historical survey of sections XIII.13.1 through XIII.13.10 has identified the structural components -- first-order operators (Dirac), foundational constraints (Wheeler-DeWitt), operator-encoded geometry (Connes), imaginary-time identities (Wick), phase-space-to-Hilbert-space construction (Kostant, Souriau), operator-encoded localization (Newton-Wigner), generators (Hamilton, Heaviside, Noether), and the participatory self-excited circuit (Wheeler) -- that the McGucken dx₄/dt = ic framework integrates into a single co-generation theorem. The present subsection collects what the *greats themselves* said, in their own published words, about the categorical relation between observer and observed in quantum mechanics. The pattern that emerges across more than fifty years of writing by the founders and principal developers of quantum theory is striking: each of them, in physics-grade venues, articulated some version of the categorical claim that the McGucken dx₄/dt = ic framework's space-operator co-generation theorem now formalizes. None of them had the formal mathematics to make the categorical claim a theorem. The claim itself, however, is theirs.

We restrict the survey to direct quotation from primary sources by physicists of unambiguous historical standing -- Nobel laureates and major figures of comparable rank -- in physics-grade writings. No interpretive paraphrase is offered for the quotations themselves; the quotations speak for themselves. After each quotation, the present paper notes the structural content and its relation to the co-generation theorem.

##### XIII.13.11.1 Niels Bohr

Bohr's central conceptual claim -- that observed system and observing apparatus cannot be separated by a categorical foundational cut -- is repeated across his writings.

From *Atomic Theory and the Description of Nature* [102]:

> *"Isolated material particles are abstractions, their properties being definable and observable only through their interaction with other systems."*

From his discussions reported by Aage Petersen [103]:

> *"There is no quantum world. There is only an abstract quantum physical description. It is wrong to think that the task of physics is to find out how nature is. Physics concerns what we can say about nature."*

And from *Atomic Physics and Human Knowledge* [104]:

> *"In the great drama of existence we are ourselves both actors and spectators."*

**Structural content.** Bohr's claim is categorical: the observable is not a property of an isolated particle, because the isolated particle is an abstraction; what is real is the *interaction* between system and other systems -- including the observing apparatus. The cut between subject and object is not a primitive of the formalism; it is a pragmatic boundary that physics describes but does not ground.

**Relation to the co-generation theorem.** Bohr is correct that the cut cannot be drawn at the foundational level. The McGucken dx₄/dt = ic framework explains *why*: because the space (where the system lives) and the operator (which the apparatus realizes) are co-generated by $dx_4/dt = ic$, there is no foundational level at which a system-apparatus cut could be drawn. Bohr's "actors and spectators" phrase identifies what the co-generation theorem makes formal: actors and spectators are both configurations in $\mathcal{M}_G$, co-derivatives of the same source. The "great drama" is the geometric self-intersection $D_M(\Sigma_M(p)) \cap \Sigma_t$ of the source-pair with itself.

##### XIII.13.11.2 Werner Heisenberg

Heisenberg's most-quoted philosophical claim about the categorical structure of quantum mechanics appears in *Physics and Philosophy* [105], the published version of his 1955-1956 Gifford Lectures at St. Andrews:

> *"What we observe is not nature itself, but nature exposed to our method of questioning."* (p. 78)

The surrounding passage makes the structural point explicit:

> *"This again emphasises a subjective element in the description of atomic events, since the measuring device has been constructed by the observer, and we have to remember that what we observe is not nature in itself but nature exposed to our method of questioning. Our scientific work in physics consists in asking questions about nature in the language that we possess and trying to get an answer from experiment by the means that are at our disposal."*

And, on the role of the observer in the formalism, from *The Physicist's Conception of Nature* [106]:

> *"Science no longer confronts nature as an objective observer, but sees itself as an actor in this interplay between man and nature."*

**Structural content.** What is observed is not nature *in itself* -- the categorically isolated object that classical physics imagined. What is observed is nature *exposed to our method of questioning* -- that is, nature interacting with the operator that the apparatus realizes. The observation is not a passive uncovering of a pre-existing fact; it is an interaction in which the observer's apparatus and the observed system are categorically entangled.

**Relation to the co-generation theorem.** Heisenberg's "method of questioning" is, in the McGucken dx₄/dt = ic framework, the operator $D_M$ acting through the apparatus on configurations in $\mathcal{M}_G$. "Nature exposed to our method of questioning" is the geometric event $D_M(\Sigma_M(p)) \cap \Sigma_t$ -- the spatial-slice projection of the four-dimensional state. The categorically isolated object Heisenberg denied does not exist in the McGucken dx₄/dt = ic framework: what exists is the source-pair $(\mathcal{M}_G, D_M)$, with the observation event being one of its readings.

##### XIII.13.11.3 Erwin Schrödinger

Schrödinger contributed two of the most influential thought experiments in the foundations of quantum mechanics -- the cat (1935) and the entanglement papers (1935-1936) -- and made explicit categorical statements about subject and object in his late writings.

**On entanglement, from *Discussion of Probability Relations between Separated Systems* [107]:**

> *"When two systems, of which we know the states by their respective representatives, enter into temporary physical interaction due to known forces between them, and when after a time of mutual influence the systems separate again, then they can no longer be described in the same way as before, viz. by endowing each of them with a representative of its own. I would not call that one but rather the characteristic trait of quantum mechanics, the one that enforces its entire departure from classical lines of thought. By the interaction the two representatives [the quantum states] have become entangled."*

> *"Another way of expressing the peculiar situation is: the best possible knowledge of a whole does not necessarily include the best possible knowledge of all its parts."*

(*Mathematical Proceedings of the Cambridge Philosophical Society*, Vol. 31, No. 4, 1935, p. 555.)

**On the cat thought experiment, from *Die gegenwärtige Situation in der Quantenmechanik* [40, Naturwissenschaften 23: 807-812]:**

> *"One can even set up quite ridiculous cases. A cat is penned up in a steel chamber, along with the following device (which must be secured against direct interference by the cat): in a Geiger counter, there is a tiny bit of radioactive substance, so small that perhaps in the course of one hour one of the atoms decays, but also, with equal probability, perhaps none; if it happens, the counter tube discharges and through a relay releases a hammer that shatters a small flask of hydrocyanic acid. The psi-function of the entire system would express this by having in it the living and dead cat (pardon the expression) mixed or smeared out in equal parts."*

**On subject and object, from *Mind and Matter* [43]:**

> *"The world is given to me only once, not one existing and one perceived. Subject and object are only one. The barrier between them cannot be said to have broken down as a result of recent experience in the physical sciences, for this barrier does not exist."*

**Structural content.** Schrödinger's three claims, taken together, are remarkably close to the structural content of the co-generation theorem. (i) The entanglement claim asserts that two systems, after interaction, cannot be described independently -- the categorical separation between them is not preserved by the dynamics. (ii) The cat thought experiment shows that the categorical separation between microscopic quantum and macroscopic classical cannot be drawn cleanly: applying quantum mechanics consistently produces superpositions extending into the classical realm, with the location of the cut unspecified. (iii) The Mind and Matter passage states the categorical thesis directly: subject and object are not two things separated by a barrier; the barrier "does not exist."

**Relation to the co-generation theorem.** Schrödinger's "characteristic trait of quantum mechanics" -- entanglement, the loss of categorical separation between two interacting systems -- is, in the McGucken dx₄/dt = ic framework, a direct consequence of the universal derivability principle: the two systems are co-derivatives of $\mathcal{M}_G$, configured through the same source-operator $D_M$, and their joint state inherits the structural unity of $(\mathcal{M}_G, D_M)$. The cat thought experiment, in the McGucken dx₄/dt = ic framework, has its categorical cut dissolved by Proposition VII.1: the cut between quantum and classical is not arbitrary but is set by Compton-frequency decoherence, with apparatus and cat configured at high enough Compton frequency that decoherence times are below detection thresholds (sections VII.2 and XV.1). The Mind and Matter passage is, in the McGucken dx₄/dt = ic framework, the categorical claim that the co-generation theorem makes formal: subject and object are not two things separated by a barrier; both are configurations in the source-space $\mathcal{M}_G$, with their apparent separation being the spatial-slice projection $\pi_{x_{\text{obs}}}$ rather than a foundational categorical division.

##### XIII.13.11.4 Eugene Wigner

Wigner introduced the friend thought experiment in *Remarks on the Mind-Body Question*, his contribution to *The Scientist Speculates* [42]. The structural claim:

> *"All that quantum mechanics purports to provide are probability connections between subsequent impressions (also called 'apperceptions') of the consciousness, and even though the dividing line between the observer, whose consciousness is being affected, and the observed physical object can be shifted towards the one or the other to a considerable degree, it cannot be eliminated."*

The friend thought experiment itself, paraphrased by Wigner: a physicist (Wigner) measures the state of a quantum system through a friend who is also performing the measurement. From Wigner's perspective, before he asks the friend, the joint state of friend-plus-system is in superposition. From the friend's perspective, the measurement has already produced a definite result. Wigner asks: how can the joint state be superposition for one observer and definite for another?

> *"The question of what result the friend has seen is surely 'already decided in his mind'."* [42, p. 294]

**Structural content.** The dividing line between observer and observed can be shifted -- it is not a primitive of the formalism, but a pragmatic boundary -- but it cannot be eliminated within the standard categorical structure of quantum mechanics. The friend thought experiment is the sharpest formulation of this difficulty: where to place the cut produces *different* descriptions of the same physical situation, depending on which side of the cut the observer is on. Wigner himself in 1961 took this as a reductio: standard quantum mechanics cannot consistently formulate a universal observer-independent description.

**Relation to the co-generation theorem.** Wigner is correct that the cut cannot be eliminated within standard quantum mechanics' categorical structure, where space and operator are independent foundational inputs. The McGucken dx₄/dt = ic framework dissolves the friend paradox by removing the categorical structure that produces it: in the McGucken dx₄/dt = ic framework, both observer (Wigner) and friend are configurations in $\mathcal{M}_G$, and both are equally subject to $D_M$'s flow. The "definite outcome" the friend sees and the "superposition" Wigner describes are the *same* four-dimensional state $|\Psi(t)\rangle$ projected onto two different spatial slices $\Sigma_{t,\text{friend}}$ and $\Sigma_{t,\text{Wigner}}$. There is no observer-relative inconsistency, because Proposition V.1 establishes that what each observer sees is the cross-section of one underlying x_4-extended state, with x_4-coincidence (Proposition VIII.1) tying the two readings together. The dividing line in the McGucken dx₄/dt = ic framework is geometric (the spatial-slice location) rather than ontological, and the apparent paradox is the geometric projection from one underlying source-pair onto two distinct spatial slices.

We note explicitly that Wigner's specific consciousness-causes-collapse mechanism is *not* what the McGucken dx₄/dt = ic framework supports. Wigner himself later distanced himself from that mechanism. The McGucken dx₄/dt = ic framework cites Wigner only for the categorical claim that the cut cannot be eliminated within standard quantum mechanics' formalism -- a claim that is, in the McGucken dx₄/dt = ic framework, a structural consequence of the co-generation theorem.

##### XIII.13.11.5 John von Neumann

Von Neumann's *Mathematical Foundations of Quantum Mechanics* [17] established the formal structure of quantum measurement, including the analysis of the measurement chain that bears his name. The categorical implication of his chain analysis:

> *"That this boundary [between observer and observed] can be displaced arbitrarily far into the interior of the body of the actual observer is the content of the principle of the psycho-physical parallelism -- but this does not change the fact that in each method of description the boundary must be put somewhere, if the method is not to proceed vacuously, i.e., if a comparison with experience is to be possible. Indeed experience only makes statements of this type: an observer has made a certain (subjective) observation; and never any like this: a physical quantity has a certain value."*

(*Mathematical Foundations of Quantum Mechanics*, Princeton University Press, 1955 English edition, p. 420.)

**Structural content.** Von Neumann's chain demonstrates formally that the boundary between observed system and observing apparatus is *arbitrarily placeable* within the standard formalism: one can include the apparatus in the "system" and treat the eye as the apparatus, or include the eye in the "system" and treat the brain as the apparatus, or include the brain and treat consciousness as the apparatus. The formalism is invariant under where the cut is drawn. But the formalism *requires* a cut to be drawn somewhere, in order to make experimental predictions. The cut is therefore not a primitive of nature -- it is a methodological necessity of the formalism.

**Relation to the co-generation theorem.** Von Neumann's invariance-under-cut-placement is, in the McGucken dx₄/dt = ic framework, the structural content of the universal derivability principle. The configurations on both sides of any putative cut are derivatives of $\mathcal{M}_G$ via admissible operations; the "cut" is the spatial-slice projection $\pi_{x_{\text{obs}}}$ at the observer's location, which is not a foundational division of the universe but a geometric feature of which configurations are accessible to which observer. The arbitrariness of the cut, which von Neumann established formally for standard quantum mechanics, is in the McGucken dx₄/dt = ic framework a categorical feature: there is no foundational cut to be drawn, because the source-pair generates everything on both sides of any spatial slice from the same primitive law.

##### XIII.13.11.6 David Bohm

Bohm developed the implicate-order programme in his 1980 monograph *Wholeness and the Implicate Order* [108]. The categorical content of his programme is summarized at the opening of the book:

> *"The new form of insight can perhaps best be called Undivided Wholeness in Flowing Movement. This view implies that flow is, in some sense, prior to that of the 'things' that can be seen to form and dissolve in this flow. One can perhaps illustrate what is meant here by considering the 'stream of consciousness'. This flux of awareness is not precisely definable, and yet it is evidently prior to the definable forms of thoughts and ideas which can be seen to form and dissolve in the flux, like ripples, waves, and vortices in a flowing stream."*

(*Wholeness and the Implicate Order*, Routledge, 1980, p. 14.)

And later, on the implicate order specifically:

> *"In the enfolded [or implicate] order, space and time are no longer the dominant factors determining the relationships of dependence or independence of different elements. Rather, an entirely different sort of basic connection of elements is possible, from which our ordinary notions of space and time, along with those of separately existent material particles, are abstracted as forms derived from the deeper order. These ordinary notions in fact appear in what is called the 'explicate' or 'unfolded' order, which is a special and distinguished form contained within the general totality of all the implicate orders."*

(*Wholeness and the Implicate Order*, p. xv.)

**Structural content.** Bohm's claim is that the universe, at its deepest level, is one undivided wholeness; what appears as distinct material particles, separable observers, and definite spatial-temporal locations are all derivatives of a deeper implicate order. Subject and object are not foundationally separated -- they are abstractions extracted from the deeper wholeness in the explicate (unfolded) order.

**Relation to the co-generation theorem.** Bohm's implicate order is structurally similar to the McGucken Space $\mathcal{M}_G$: a deeper underlying structure from which standard spaces, particles, and observers are derived. Where Bohm's implicate order is *postulated* as a foundational layer, the McGucken dx₄/dt = ic framework *derives* the source-space from a single primitive law $dx_4/dt = ic$. Bohm's specific mechanism (pilot wave plus implicate order, with active information) is not what the McGucken dx₄/dt = ic framework supports: the McGucken dx₄/dt = ic framework does not introduce hidden variables on configuration space, and the spatial-slice projection that produces apparent collapse is not Bohm's quantum potential. But Bohm's *categorical* claim -- that wholeness is foundational and division is derivative -- is exactly the categorical structure that the co-generation theorem formalizes. Bohm's "ordinary notions of space and time, along with those of separately existent material particles, are abstracted as forms derived from the deeper order" is, in the McGucken dx₄/dt = ic framework, the universal derivability principle: standard spaces, particles, and observers all descend from $\mathcal{M}_G$ via admissible physical-space operations.

##### XIII.13.11.7 John Archibald Wheeler

Wheeler's structural claims about the categorical relation between observer and observed have been quoted in section XIII.13.10 in the context of the self-excited circuit. Here we collect the additional direct quotations from his physics-grade writings that bear specifically on the categorical claim.

From *Law Without Law* [94, in Wheeler and Zurek (eds.), *Quantum Theory and Measurement*, Princeton University Press]:

> *"No elementary phenomenon is a phenomenon until it is a registered (observed) phenomenon, brought to a close by an irreversible act of amplification."*

> *"In some strange sense, the universe is a participatory universe."*

> *"Beginning with the big bang, the universe expands and cools. After eons of dynamic development it gives rise to observership. Acts of observer-participancy -- via the mechanism of the delayed-choice experiment -- in turn give tangible 'reality' to the universe, not only now but back to the beginning."* (p. 209)

From *Information, Physics, Quantum: The Search for Links* [71]:

> *"It from bit symbolizes the idea that every item of the physical world has at bottom -- a very deep bottom, in most instances -- an immaterial source and explanation; that which we call reality arises in the last analysis from the posing of yes-no questions and the registering of equipment-evoked responses; in short, that all things physical are information-theoretic in origin and this is a participatory universe."*

And on the impossibility of an outside observer, from his earlier writing:

> *"Nothing is more important about quantum physics than this: it has destroyed the concept of the world as 'sitting out there'."* [109]

**Structural content.** Wheeler's claim is the sharpest formulation of the participatory thesis: the categorical separation between an observer "sitting out there" watching the universe and the universe "sitting out there" being watched is rejected as a fundamental structure. Observation is not a passive registration of pre-existing fact; it is participation in the constitution of fact.

**Relation to the co-generation theorem.** Wheeler's "participatory universe" is, in the McGucken dx₄/dt = ic framework, formalized by the space-operator co-generation theorem (Theorem XIII.I) together with the universal derivability principles. Observers and observed are co-derivatives of $(\mathcal{M}_G, D_M)$; the "registered phenomenon" is the geometric event $D_M(\Sigma_M(p)) \cap \Sigma_t$; the "yes-no questions" of *It from Bit* are the binary cross-section readings selected by the spatial-slice projection at the observer's location, with Born-distributed outcomes from Proposition III.1; and the "tangible reality back to the beginning" is the x_4-coincidence connection between observer-event and source-event through the McGucken Sphere structure (Proposition VIII.1, First Law of Nonlocality). Wheeler's participatory thesis is the heuristic image whose formal mathematics is the co-generation theorem (section XIII.13.10).

##### XIII.13.11.8 The pattern across the greats

The pattern that emerges across these direct quotations from Bohr, Heisenberg, Schrödinger, Wigner, von Neumann, Bohm, and Wheeler is striking. Each of them, in physics-grade writings, made a categorical claim about the inseparability of observer and observed -- and each of them lacked the formal mathematics to make the categorical claim a theorem. The claims, paired with the formal content the McGucken dx₄/dt = ic framework now supplies, can be summarized:

| Physicist | Categorical claim (paraphrased from quotation) | Formal McGucken content |
|---|---|---|
| Bohr (1934, 1958, in Petersen 1963) | Isolated material particles are abstractions; properties are definable only through interaction; the cut between observer and observed is not a primitive of the formalism | Universal derivability principle: every "particle" is a configuration in $\mathcal{M}_G$, with properties defined by $D_M$'s action on cross-sections at $\Sigma_t$ |
| Heisenberg (1955, 1958) | What we observe is not nature itself but nature exposed to our method of questioning | The "method of questioning" is $D_M$; the observation event is $D_M(\Sigma_M(p)) \cap \Sigma_t$ |
| Schrödinger (1935a, 1935b, 1958) | Entanglement is the characteristic trait of quantum mechanics; subject and object are only one; the barrier between them does not exist | Entanglement = co-derivation from $\mathcal{M}_G$; subject-object unity = co-generation theorem; the cat's superposition is the four-dimensional state pre-projection |
| Wigner (1961) | The dividing line between observer and observed can be shifted but cannot be eliminated | Within standard QM's categorical structure, the cut cannot be eliminated; the McGucken dx₄/dt = ic framework eliminates the categorical structure that requires the cut |
| von Neumann (1932) | The boundary between observer and observed is arbitrarily placeable within the formalism | Universal derivability: configurations on both sides of any cut descend from $\mathcal{M}_G$ via admissible operations |
| Bohm (1980) | Undivided wholeness is foundational; separately existent material particles are abstracted from a deeper order | $\mathcal{M}_G$ is the source-space from which all standard spaces and particles are derivative |
| Wheeler (1979, 1983, 1990) | The world is not "sitting out there"; observation is participation; "no elementary phenomenon is a phenomenon until it is an observed phenomenon" | Co-generation theorem: $dx_4/dt = ic \Longrightarrow (\mathcal{M}_G, D_M)$; participation is geometric self-intersection of source-pair |

The cumulative weight is not subtle. Six Nobel laureates and one major figure of comparable rank, writing in physics-grade venues across more than half a century, each articulated a categorical claim about the inseparability of observer and observed in quantum mechanics. Each claim was made *without* the formal mathematics that would make it a theorem; the categorical claim was made *despite* the lack of formal mathematics, on the strength of what each physicist took to be the deepest implication of quantum mechanics for the structure of nature.

The McGucken dx₄/dt = ic framework is the formal mathematics they reached for. The space-operator co-generation theorem (Theorem XIII.I) is the formal expression of the categorical claim that the cut cannot be drawn at the foundational level. The universal derivability principles of [12] and [13] are the formal expression of Bohm's wholeness and Heisenberg's "actor in this interplay." Proposition V.1 -- the apparent collapse as cross-section reading -- is the formal expression of Schrödinger's "subject and object are only one" with the apparent separation arising from the spatial-slice projection. Proposition VIII.1 and the First Law of Nonlocality are the formal expression of Wheeler's "tangible reality back to the beginning." Proposition VII.1 -- preferred basis from Compton-frequency decoherence -- is the formal resolution of Schrödinger's cat thought experiment via a concrete physical mechanism rather than an arbitrary cut placement.

The McGucken dx₄/dt = ic framework therefore does not propose a *new* claim about the categorical structure of quantum mechanics. The categorical claim is Bohr's, Heisenberg's, Schrödinger's, Wigner's, von Neumann's, Bohm's, and Wheeler's. What is new in the present paper, and in [12] and [13], is the formal mathematics that turns the categorical claim into a theorem -- the space-operator co-generation theorem and its derivation from the single primitive physical law $dx_4/dt = ic$. The greats had the right intuition. The framework supplies the math.

---

#### XIII.13.12 Who came closest to recognizing that the operator generates the space and the space generates the operator?

The historical survey of this section has so far identified figures who came close to one or another *unidirectional* aspect of source-operator structure: Dirac (operators that square-root second-order operators), Wheeler-DeWitt (operators that act as foundational constraints), Connes (operators that encode geometric data, recoverable as a descent image of the McGucken Source-Tuple via $F_{\rm Spec}$ per §XIII.13.3), Wick (analytic continuation between time and imaginary-time derivatives), Hamilton-Noether-Heaviside (operators as generators), and Wheeler (the participatory self-excited-circuit image). The sharpest version of the historical question, however, is more specific: who came close to recognizing that the operator generates the space *and* the space generates the operator — that is, to a genuinely *bidirectional* relationship between space and operator in quantum mechanics?

The honest answer, examined carefully below, depends on what "bidirectional" means. Two distinct senses must be distinguished, because conflating them muddies both the historical picture and the structural novelty of the McGucken dx₄/dt = ic framework.

**Sense 1 — Categorical equivalence (re-encoding).** Two structures are "bidirectional" in this sense when each is recoverable from the other by a canonical functorial construction, with the two constructions mutually inverse up to natural isomorphism. The space and the algebra are then two equivalent presentations of the same data; neither generates the other in any causal or foundational sense, but each can be re-encoded as the other. Stone duality (1936), Pontryagin duality (1934), Gelfand-Naimark duality (1943), and Connes's reconstruction theorem (2008) — applied to commutative spectral triples — are all categorical equivalences in this sense. Each is a deep mathematical theorem; none of them proposes a primitive physical law from which both sides descend.

**Sense 2 — Co-generation from a primitive law (descent from a prior third structure).** Two structures are "bidirectional" in this sense when both are *generated* by a third structure prior to and external to both — most foundationally, a primitive physical law — with neither pre-existing the law that brings both into being. The space exists *because* the law holds; the operator exists *because* the law holds. The bidirectionality runs from the law to each, not from one to the other.

These two senses are categorically different. Sense 1 (equivalence) has been widely available in mathematical physics since at least Stone (1936) and Gelfand-Naimark (1943). Sense 2 (co-generation from a primitive law) has been available in *no* prior framework of mathematical physics. The McGucken space-operator co-generation theorem (Theorem XIII.I) is co-generation in Sense 2: the source-pair $(\mathcal{M}_G, D_M)$ is generated by the primitive physical law $dx_4/dt = ic$, with the inverse derivability of [12, 13] establishing that the pair jointly determines the law.

The present sub-subsection examines each Sense-1 precursor in turn — Stone, Pontryagin, Gelfand-Naimark, the GNS construction, Heisenberg-Born-Jordan, and (via [1]) Connes — and identifies precisely what each shares with the McGucken co-generation theorem and what each lacks. The conclusion is sharp: in Sense 1, several precursors achieved bidirectional categorical equivalence; in Sense 2, no prior framework came close. The McGucken dx₄/dt = ic framework's novelty is the *third leg* — the primitive physical law from which both space and operator descend.

##### XIII.13.12.1 Stone (1936) and Pontryagin (1934): the original mathematical dualities

The general mathematical insight that algebraic structures and topological/spatial structures can stand in canonical bidirectional correspondence — that "algebra" and "space" are not two unrelated categories of mathematical object — emerges in the 1930s.

**Stone duality** [110] establishes a categorical equivalence between Boolean algebras and Stone spaces (compact totally disconnected Hausdorff spaces). From a Boolean algebra $B$, one constructs the space of ultrafilters; from a Stone space $X$, one extracts the Boolean algebra of clopen subsets. The two operations are mutually inverse functors — every Boolean algebra is recovered up to isomorphism by going to its Stone space and back, and every Stone space is recovered up to homeomorphism by going to its Boolean algebra and back. Stone duality is the original "algebra-space duality" theorem of twentieth-century mathematics and informed Gelfand's later development.

**Pontryagin duality** [111] establishes that for any locally compact abelian group $G$, the dual group $\hat{G}$ of continuous characters $G \to U(1)$ is also a locally compact abelian group, and $G \cong \hat{\hat{G}}$. The Fourier transform is the mathematical content of this duality. Pontryagin's theorem is bidirectional in the same Sense-1 (equivalence) categorical structure.

*What Stone and Pontryagin captured.* The general mathematical insight that algebraic structures (Boolean algebras, abelian groups) and spatial/topological structures (Stone spaces, dual groups) stand in canonical bidirectional correspondence by mutually inverse functors. "Algebra" and "space" are not two unrelated categories of mathematical object.

*What Stone and Pontryagin missed in relation to the co-generation theorem.* Both worked in commutative/abelian classical settings, with no primitive physical law and no dynamical content. Their dualities are about static structures (Boolean algebras, abelian groups) rather than about quantum mechanical operators acting as generators of flow on configuration space. There is no third structure — no primitive law — from which both the algebra side and the space side descend. The bidirectionality is *re-encoding*, not co-generation. Stone and Pontryagin established that algebraic structure and spatial structure can be equivalent presentations of the same data; they did not establish (and did not propose) that both presentations descend from a more primitive third.

##### XIII.13.12.2 Gelfand and Naimark (1943): the commutative C*-algebra–space equivalence

The most direct mathematical precursor to bidirectional space-operator correspondence in *quantum-relevant* settings is the Gelfand-Naimark theorem [112]. Stated in its modern categorical form: there is a contravariant functorial equivalence between

- the category of compact Hausdorff topological spaces with continuous maps, and
- the category of commutative unital C*-algebras with *-homomorphisms.

The two functors implementing the equivalence: from a compact Hausdorff space $X$, form the algebra $C(X, \mathbb{C})$ of continuous complex-valued functions; from a commutative unital C*-algebra $\mathcal{A}$, form the *spectrum* (the maximal ideal space, equipped with the weak-* topology). These two functors are mutually inverse up to natural isomorphism. The round-trip from a space to its function algebra and back to the spectrum recovers the original space; the round-trip from an algebra to its spectrum and back to the function algebra recovers the original algebra.

This is bidirectional in Sense 1: the commutative C*-algebra and the compact Hausdorff space are two equivalent presentations of the same data, with each recoverable from the other by a canonical functorial construction.

*What Gelfand-Naimark captured.* The structural insight that algebra and space are not two independent kinds of mathematical object but two equivalent presentations of the same data — bidirectional in the strict mathematical (categorical-equivalence) sense. This is the deepest available mathematical instantiation of "the algebra is the space, and the space is the algebra" in classical functional analysis. Connes's noncommutative geometry programme is the attempt to extend this equivalence to the noncommutative case (his motto: noncommutative C*-algebras are "noncommutative spaces").

*What Gelfand-Naimark missed in relation to the co-generation theorem.* Three structural limitations.

*(1) Commutativity.* The Gelfand-Naimark theorem applies only to *commutative* C*-algebras. Quantum mechanics is fundamentally noncommutative — the canonical commutator $[\hat{q}, \hat{p}] = i\hbar$ is not zero. The Gelfand-Naimark equivalence does not directly apply in the quantum (noncommutative) setting. Connes's noncommutative-geometry programme is the deepest extension toward the noncommutative case, and as discussed in §XIII.13.3 above, the Connes-descent paper [1] establishes the McGucken-Dirac spectral triple as the canonical commutative-half realization of this extension. Reyes [113] established that no functor $F: \mathrm{Ring}^{\rm op} \to \mathrm{Set}$ extending the Gelfand spectrum to the noncommutative case can do so without trivializing on the prototypical noncommutative rings $M_n(\mathbb{C})$ for $n \geq 3$ — a no-go theorem demonstrating that the commutative Gelfand-Naimark equivalence does not extend straightforwardly to the noncommutative setting.

*(2) No primitive physical law (Sense-2 absence).* Gelfand-Naimark establishes that the *category* of commutative C*-algebras and the *category* of compact Hausdorff spaces are equivalent. It does not propose any primitive physical law from which either category descends. The space and the algebra are co-equivalent presentations of the same data, but the data itself — *what space, what algebra* — is supplied externally. The McGucken framework supplies the primitive law $dx_4/dt = ic$ from which both the source-space $\mathcal{M}_G$ and the source-operator $D_M$ descend; Gelfand-Naimark has no analogue. Gelfand-Naimark is bidirectional in Sense 1 but has nothing in Sense 2.

*(3) Static, not dynamical.* The Gelfand-Naimark equivalence is between a space and its algebra of *continuous functions* — static topological data. It does not address dynamics, evolution, or the operator $D_M$ as a generator of flow. The McGucken Operator $D_M = \partial_t + ic\,\partial_{x_4}$ is a *first-order differential operator* that generates the dynamics; Gelfand-Naimark addresses the function algebra, not the differential-operator generator.

The Gelfand-Naimark theorem is therefore the *commutative classical precursor* to space-operator bidirectionality. It is bidirectional in the categorical-equivalence (Sense-1) sense, but it is not quantum, not generated by a primitive law, and not dynamical. The McGucken dx₄/dt = ic framework integrates these three additional structural features that Gelfand-Naimark does not address.

##### XIII.13.12.3 The GNS construction (1947): operator → Hilbert space, but not the other direction

The Gelfand-Naimark-Segal (GNS) construction [112, 114] is sometimes cited as a precursor to bidirectional space-operator structure in quantum mechanics specifically. Given a C*-algebra $\mathcal{A}$ and a state $\omega$ (a positive linear functional of norm one), the GNS construction produces a Hilbert space $\mathcal{H}_\omega$, a representation $\pi_\omega: \mathcal{A} \to \mathcal{B}(\mathcal{H}_\omega)$, and a cyclic vector $|\Omega_\omega\rangle \in \mathcal{H}_\omega$ such that $\omega(a) = \langle\Omega_\omega| \pi_\omega(a) |\Omega_\omega\rangle$. The Hilbert space $\mathcal{H}_\omega$ is generated by the algebra-and-state pair $(\mathcal{A}, \omega)$.

*What GNS captured.* GNS is the precise mathematical statement of how an operator algebra plus a state *generates* a Hilbert space representation. It is bidirectional in a limited sense: from $(\mathcal{A}, \omega)$ one constructs $\mathcal{H}_\omega$, and from a representation $\pi: \mathcal{A} \to \mathcal{B}(\mathcal{H})$ one can extract states $\omega_\xi(a) = \langle\xi| \pi(a) |\xi\rangle$ for unit vectors $\xi \in \mathcal{H}$.

*What GNS missed.* GNS is *unidirectional* with respect to the foundational question: it constructs the Hilbert space from the algebra-state pair, but it does *not* construct the algebra from the Hilbert space, and it does *not* generate either from a primitive physical law. GNS presupposes the algebra $\mathcal{A}$ as primitive structural data; it does not explain why this algebra rather than another, or where the algebra comes from. GNS is a construction *within* a fixed algebraic framework, not a co-generation *of* the algebraic framework.

In Sense-1 terms, GNS is asymmetric: algebra-plus-state $\to$ Hilbert space is canonical; the reverse direction (Hilbert space $\to$ algebra) is not canonical without auxiliary data (a state, a choice of cyclic vector). In Sense-2 terms, GNS is silent: there is no primitive physical law from which the algebra descends.

GNS is therefore a *one-direction-out-of-two* precursor — the algebra side generating the Hilbert side, but no prior physical law generating either. It is not co-generation in either Sense.

##### XIII.13.12.4 Heisenberg, Born, and Jordan (1925): matrix mechanics and the algebraic mirror

The earliest physics-side precursor to bidirectional thinking about space and operators in quantum mechanics is the matrix mechanics of Heisenberg [115], rapidly formalized by Born and Jordan [116] and then by all three together [117]. The structural insight: observable physical quantities — position, momentum, energy — are represented by matrices (operators), and the algebraic structure of these matrices (specifically, their commutators) mirrors the geometric/dynamical structure of the underlying physical system. Dirac's later "Poisson bracket to commutator" prescription codified this: the classical phase-space structure $\{f, g\}_{\rm PB}$ is mirrored, in quantum mechanics, by $[\hat{f}, \hat{g}]/i\hbar$.

*What Heisenberg-Born-Jordan captured.* The structural insight that algebraic relations among operators are not arbitrary but mirror the geometric and dynamical content of the system. The canonical commutator $[\hat{q}, \hat{p}] = i\hbar$ is not a mere algebraic stipulation; it carries the geometric content of phase-space symplectic structure transferred to the operator side. This is the historical root of "operators encode geometry."

*What Heisenberg-Born-Jordan missed.* The mirror was presented as a *correspondence* between two pre-existing structures — classical phase space on one side, operator algebra on the other — with no proposal that one generated the other. Both sides were assumed; the mirror simply related them. There is no direction of generation: phase space is not derived from the operators, and the operators are not derived from phase space. They are paired by Dirac's correspondence prescription, not co-generated. The mirror is what we today call canonical quantization, and it operates by *prescription* rather than by derivation from a primitive law. In Sense-1 terms, the mirror is not a categorical equivalence (the prescription is not invertible — different classical phase-space systems can yield the same operator algebra under canonical quantization, and operator-ordering ambiguities prevent a clean inverse). In Sense-2 terms, the mirror has no primitive physical law from which both sides descend.

The matrix-mechanics insight is therefore the physics-side intuition that operator algebra and underlying geometry are structurally linked, but it stops well short of bidirectional generation, let alone co-generation from a primitive physical principle.

##### XIII.13.12.5 Connes (1980s–2008): the spectral triple and the reconstruction theorem

The most sophisticated mathematical-physics framework to date that approaches bidirectional space-operator correspondence in *noncommutative* (and hence quantum-relevant) settings is Connes's spectral-triple programme [84, 86]. This was treated in detail in §XIII.13.3 above, with the descent-functor result of [1]. Here we summarize the structural content of Connes's programme specifically with respect to the bidirectionality question.

*What Connes captured (Sense 1).* For commutative spectral triples, Connes's reconstruction theorem [86] establishes a genuine bidirectional categorical equivalence:

- From a smooth oriented Riemannian spin manifold $M$, construct the canonical commutative spectral triple $(C^\infty(M), L^2(M, S), D_M)$ where $D_M$ is the Dirac operator.
- From a commutative spectral triple $(\mathcal{A}, \mathcal{H}, D)$ satisfying seven axioms (regularity, finiteness, orientability, Poincaré duality, real structure, first-order condition, dimension), reconstruct a smooth oriented Riemannian spin manifold $M$ such that the original triple is unitarily equivalent to the canonical triple of $M$.

These two constructions are mutually inverse up to the appropriate categorical equivalence. The metric structure on $M$ is recoverable from $D$ via Connes's distance formula. The Dirac operator $D$ is unique on $M$ up to the spin structure (which is canonical for spin manifolds). Connes's reconstruction theorem is therefore *bidirectional in Sense 1* — algebra and manifold are equivalent presentations of the same data — for commutative spectral triples. This is the deepest available extension of Gelfand-Naimark duality toward quantum-mechanically-relevant data, with the Dirac operator $D$ playing the role that the function algebra alone plays in Gelfand-Naimark.

*What Connes missed in Sense 1 (the noncommutative obstruction).* For *noncommutative* spectral triples — the full case relevant to quantum mechanics — Connes's reconstruction theorem does not establish a bidirectional equivalence. The pair-paper [87] establishes that the noncommutative spectral triple, considered as primitive triple data with three independently-postulated components, fails the three structural theorems (Mutual Containment MCC, Reciprocal Generation RGC, Containment-Generation Equivalence CGE) that the McGucken source-pair $(\mathcal{M}_G, D_M)$ does satisfy. The bidirectional equivalence available in the commutative case via Connes's reconstruction does not extend to the noncommutative case.

*What Connes missed in Sense 2 (no primitive physical law).* Even in the commutative case where Connes's reconstruction supplies bidirectionality in Sense 1, there is no primitive physical law from which both the algebra side and the manifold side descend. Connes's spectral triple is taken as primitive triple data; the Dirac operator $D$ is the canonical Dirac operator of a *given* manifold; the manifold itself is whatever Riemannian spin manifold one chooses. There is no third structure prior to and external to both algebra and manifold from which both descend.

*The descent-functor resolution* [1]. The Connes-descent paper establishes that Connes's spectral triple is a *downstream descent image* of the McGucken Source-Tuple $F_M = (\Sigma_M, \mathcal{G}_M, \mathcal{M}_G, D_M, \mathcal{S}_M, \mathcal{A}_M)$ under the faithful descent functor $F_{\rm Spec}: \mathrm{McG}_6 \to \mathrm{SpecTriple}_{\rm comm}$. The McGucken-Dirac spectral triple $(C^\infty(\mathcal{M}), L^2(\mathcal{M}, S), D_\mathcal{M})$ is the image $F_{\rm Spec}(F_M)$ of the source-tuple under the descent functor, and Connes's reconstruction theorem applied to this descent image recovers the McGucken Euclidean four-manifold $\mathcal{M}$ canonically (Theorem D of [1]). The Connes framework thus exists *inside* the McGucken descent picture, not parallel to it. Connes's bidirectional Sense-1 equivalence is recovered for the McGucken-Dirac descent image; the McGucken dx₄/dt = ic framework adds the Sense-2 co-generation that Connes lacks.

*Position of Connes in the bidirectionality picture.* Connes is the closest precursor in the mathematical-physics literature to the McGucken co-generation theorem in *content* — both involve operator-and-geometry being deeply linked, both involve a Dirac operator carrying the geometric data, both involve reconstruction theorems. But the structural relationship is asymmetric: the McGucken dx₄/dt = ic framework generates the Connes framework as a downstream descent image (with the additional Sense-2 content of co-generation from a primitive law), while the reverse direction does not hold (Connes's framework alone does not generate the McGucken dx₄/dt = ic framework, because Connes's framework lacks the primitive physical law $dx_4/dt = ic$). Connes captures Sense 1 in the commutative case; McGucken captures Sense 2 universally and recovers Sense 1 commutative as a corollary via the descent functor.

##### XIII.13.12.6 Summary table and the structural novelty of the McGucken dx₄/dt = ic framework

The bidirectionality picture across the historical precursors can be summarized:

| Framework | Sense 1: Categorical equivalence (re-encoding) | Sense 2: Co-generation from primitive law |
|---|---|---|
| Stone duality (1936) | ✓ Boolean algebras ↔ Stone spaces | ✗ no primitive law |
| Pontryagin duality (1934) | ✓ LCA groups ↔ dual groups | ✗ no primitive law |
| Gelfand-Naimark (1943) | ✓ commutative C*-algebras ↔ compact Hausdorff spaces | ✗ no primitive law |
| GNS construction (1947) | partial: $(\mathcal{A}, \omega) \to \mathcal{H}_\omega$ unidirectional | ✗ no primitive law |
| Heisenberg-Born-Jordan (1925) | partial: canonical-quantization mirror, not invertible | ✗ no primitive law |
| Connes spectral triples (1980s) | ✓ commutative case (reconstruction theorem); ✗ noncommutative case (pair-paper [87]) | ✗ no primitive law |
| **McGucken dx₄/dt = ic framework (2026)** | **✓ recovered via descent functor $F_{\rm Spec}$ for the commutative case [1, Theorem G]** | **✓ co-generation from $dx_4/dt = ic$ (Theorem XIII.I)** |

The pattern is striking. Sense-1 (categorical equivalence) bidirectionality has been mathematically known since Stone in 1936 — eight separate frameworks have established categorical equivalences between algebraic and spatial structures of various kinds. None of these frameworks proposes a primitive physical law from which both sides descend. The bidirectionality they establish is *re-encoding*: the algebra and the space are equivalent presentations of the same data, but the data itself is supplied externally.

Sense-2 (co-generation from a primitive physical law) bidirectionality has been available in *no* prior framework of mathematical physics. The McGucken space-operator co-generation theorem (Theorem XIII.I of the present paper) is the first formal statement of Sense-2 bidirectionality: $dx_4/dt = ic \Longrightarrow (\mathcal{M}_G, D_M)$, with the inverse derivability of [12, 13] establishing that the source-pair jointly determines the law.

**Why Sense 2 matters for the measurement problem.** The structural significance of the Sense-1 vs. Sense-2 distinction for the present paper is the following. The standard categorical structure of quantum mechanics — Hilbert space $\mathcal{H}$, observable algebra $\mathcal{B}(\mathcal{H})$, evolution operator $\hat{H}$, measurement operators $\hat{O}_i$, observers as additional categorical entities outside the formalism — produces the measurement problem because system, apparatus, observer, and dynamics enter as four independent categorical inputs whose interaction at measurement must be coordinated by an additional measurement law (Born postulate, $(R)$ rule, branching, collapse, environmental selection, etc., depending on the interpretation). This is precisely what the seven major interpretive programmes (Copenhagen, Many-Worlds, Bohmian, GRW, Decoherence, RQM, QBism) each do — each adds an additional ingredient to coordinate the four independent categories at measurement.

A Sense-1 equivalence (Gelfand-Naimark, Connes-commutative) is insufficient to dissolve this structure. Even with Connes's reconstruction theorem in hand, the algebra and the manifold are equivalent presentations of the *same* underlying data — but the underlying data itself is not generated by a primitive law. The four-category structure (system, apparatus, observer, dynamics) remains in place; the Sense-1 equivalence merely re-encodes it.

Only Sense-2 co-generation from a primitive law dissolves the four-category structure at the source. Because $\mathcal{M}_G$ and $D_M$ are both generated by $dx_4/dt = ic$, system-states, apparatus-states, observer-states, and dynamical-evolution are all configurations in $\mathcal{M}_G$ acted on by $D_M$ — *one* category, four projections, with the interactions between them being structural features of the source-pair rather than additional postulates. Proposition XIII.6 (the categorical impossibility of separate collapse mechanism) is the formal expression of this: the McGucken dx₄/dt = ic framework's category structure does not have the foundational separation between system, apparatus, observer, and dynamics that the standard categorical structure has, and so the standard measurement problem cannot even be formulated within the McGucken dx₄/dt = ic framework. The Sense-2 co-generation is the structural feature that makes this possible.

**The structural novelty of the McGucken dx₄/dt = ic framework.** No prior framework in mathematical physics had a primitive physical law from which both space and operator descend. The closest mathematical precursor — Connes's spectral triple with the reconstruction theorem — achieves Sense-1 bidirectionality in the commutative case, with the descent-functor result of [1] showing that this Sense-1 equivalence is recovered as a downstream consequence of the McGucken dx₄/dt = ic framework's Sense-2 co-generation. The closest physics-side precursor — Wheeler's "law without law" and self-excited circuit — articulated the heuristic image of the McGucken dx₄/dt = ic framework but lacked the formal mathematics. The closest categorical precursor — Gelfand-Naimark — established that algebra and space can be equivalent presentations of the same data, but did not propose a third structure prior to both.

The McGucken framework supplies the primitive law $dx_4/dt = ic$ that all prior frameworks lack, and from this primitive law derives both $\mathcal{M}_G$ (the source-space) and $D_M$ (the source-operator) as co-theorems. Sense-2 bidirectionality in mathematical physics begins with the McGucken dx₄/dt = ic framework. The Sense-1 bidirectionalities of Stone, Pontryagin, Gelfand-Naimark, GNS, Connes (commutative case via reconstruction), and the canonical-quantization mirror of Heisenberg-Born-Jordan are all recovered as downstream descent images or projections within the McGucken dx₄/dt = ic framework, via the descent functors of [1, 118] and the universal derivability principles of [12, 13]. The McGucken dx₄/dt = ic framework supplies the third leg — the primitive physical law — that previous frameworks did not have.

This is the structural answer to the question of who came closest. *In Sense 1, Connes (with the reconstruction theorem) came closest, with Gelfand-Naimark as the foundational mathematical precursor and Stone as the original categorical-equivalence theorem.* *In Sense 2, no prior framework came close.* The McGucken dx₄/dt = ic framework is the first formal articulation of co-generation from a primitive physical law in the history of mathematical physics, and the structural novelty of the framework is precisely this third-leg content that no prior framework has.

---

### XIII.14 Comparative table: structural status of the space-operator relation across frameworks

The structural distinctness of the McGucken dx₄/dt = ic framework with respect to space-operator relation can be tabulated explicitly. The seven major interpretive programmes of quantum mechanics, four major historical operator constructions, and the McGucken dx₄/dt = ic framework are compared on three structural axes: (i) the status of the state space, (ii) the status of the operator algebra, and (iii) the relation between space and operator.

| Framework | Status of state space | Status of operator algebra | Space-operator relation | Categorical novelty? |
|---|---|---|---|---|
| Copenhagen interpretation | Postulated Hilbert space | Postulated observables; projection postulate $(R)$ added | Operators act on a separately postulated space; mediator is the Born rule (postulated) | None — three independent postulates |
| Many-Worlds (Everett) | Postulated Hilbert space | Postulated observables; unitary $U$ takes branches | Operators act on a separately postulated space; mediator is branching (added) | None |
| Bohmian mechanics | Postulated Hilbert space + configuration space | Postulated guidance equation acting on $3N$-dim configuration space | Two-ontology: wave function + particle trajectories | None — adds a new space (configuration), keeps two |
| GRW spontaneous localization | Postulated Hilbert space | Postulated stochastic Hamiltonian with localization terms | Operators act on space; localization is added by hand | None — modifies operator without modifying space |
| Decoherence + einselection | Postulated Hilbert space | Postulated system + environment Hamiltonians | Preferred basis selected by system-environment coupling | None — system-environment split is independent input |
| Relational Quantum Mechanics | Postulated Hilbert space (relational) | Postulated relational facts | Observer-relative; no observer-independent state | None — relational primitive added |
| QBism | Postulated Hilbert space | Personalist probability assignments | Agent-relative; no observer-independent state | None — agent primitive added |
| Geometric quantization | Postulated symplectic phase space | Operators recovered from prequantization | Space presupposed, operators recovered | Partial — operators from space, but space postulated |
| Newton-Wigner | Postulated one-particle Hilbert space | Position operator constructed from group structure | Space presupposed, position operator recovered | Partial — operator from space, but space postulated |
| Wheeler-DeWitt | Postulated configuration space of 3-metrics | Constraint operator constructed from ADM Hamiltonian | Space presupposed, constraint operator constructed | Partial — operator at foundational level, but space postulated |
| Spectral triples (Connes) | Postulated algebra $\mathcal{A}$ + Hilbert space $\mathcal{H}$ | Operator $D$ encodes geometry | Operator and space treated together but both postulated | Closer — operator-space link, but both still input |
| **McGucken dx₄/dt = ic framework** | **Derived from $\mathcal{M}_G$ via Theorem 12.1 of [12]** | **Derived from $D_M$ via Universal Operator-Derivability Principle** | **Co-generated by $dx_4/dt = ic$ via Theorem XIII.I** | **Full — single primitive law generates space and operator together** |

The cumulative structural result is that the McGucken dx₄/dt = ic framework is the only framework in which the space and the operator algebra are derived from a single primitive physical law. In every other framework, at least one of (space, operator algebra, mediator/connecting principle) is postulated independently of the others. The structural feature that makes the McGucken dx₄/dt = ic framework distinctive is the co-generation theorem: the source-pair $(\mathcal{M}_G, D_M)$ is generated together, not assembled from independent inputs.

#### XIII.14.1 The structural reason for the asymmetry

The structural asymmetry reflected in the table — that the McGucken dx₄/dt = ic framework is alone in deriving both space and operators — can be understood as follows.

A framework that postulates the state space and constructs operators on it (Newton-Wigner, geometric quantization, Wheeler-DeWitt) must accept the state space as foundational input. A framework that postulates the operator algebra and recovers geometry (early Connes spectral triples) must accept the operator algebra as foundational input. A framework that postulates both (Copenhagen, Many-Worlds, Bohmian, GRW, decoherence, RQM, QBism) must accept both as foundational input together with a connecting principle. None of these frameworks has the structural resource to derive both from a deeper layer.

The McGucken dx₄/dt = ic framework has this resource because it begins with a primitive physical *law* — $dx_4/dt = ic$ — that is *neither* a space *nor* an operator but a relation that generates both. The law is not a Hilbert space (it is not a vector space of states), not an operator (it is not a map between states), not a probability rule (it is not a measure on outcomes); it is a primitive physical-geometric relation. Because it is primitive in a different *category* than the structures it generates, it has the structural resource to generate them.

This is the deepest sense in which the McGucken dx₄/dt = ic framework's categorical structure differs from all prior frameworks: the foundational layer is at a *different category* (primitive physical-geometric relation) than the derived layers (spaces, operators, probability rules). Standard frameworks operate within a single category (space + operator + rule, all of the same axiomatic kind). The McGucken dx₄/dt = ic framework operates across categories, with the source category supplying the generative resource that derives the others.

---

### XIII.15 The complete structural reduction: space, operator, and principle as one fact

The structural development of §§XIII.5–XIII.14 establishes the strongest form of the McGucken dx₄/dt = ic framework's structural-reduction claim. Combining:

- **§XIII.5** (the McGucken Space framework as source-space hierarchy);
- **Proposition XIII.4** (the Hilbert-space inner product, complex conjugation, and orthogonality structure as theorems of $dx_4/dt = ic$);
- **§XIII.9** (the McGucken Operator $D_M$ as source-operator with full operator hierarchy);
- **Theorem XIII.I** (the space-operator co-generation theorem);
- **Corollary XIII.J** (mutual derivability of $\mathcal{M}_G$, $D_M$, and $dx_4/dt = ic$);
- **Proposition XIII.5** (the principal quantum operators as theorems of $dx_4/dt = ic$);
- **Proposition XIII.6** (the co-generation theorem rules out a separate measurement-collapse mechanism);

the complete structural reduction can be stated:

**Theorem XIII.M (The complete structural reduction).** *In the McGucken dx₄/dt = ic framework, the entire structural content of standard quantum mechanics — the state space (Hilbert space and its specific carrier spaces $L^2(\mathbb{R}^3)$, $\mathbb{C}^2 \otimes L^2(\mathbb{R}^3)$, Fock space), the inner-product apparatus (sesquilinear form, complex conjugation, integration measure, orthogonality, distinguishability), the principal quantum operators (Hamiltonian, momentum, Schrödinger operator, Dirac operator, canonical commutator, gauge-covariant derivative), the unitarity of evolution, the Born rule, the superposition principle, the apparent collapse, the irreversibility, the preferred basis, and the nonlocality — descends from the single primitive physical law $dx_4/dt = ic$ via the co-generated source-pair $(\mathcal{M}_G, D_M)$. The complete structural reduction is*

$$\frac{dx_4}{dt} = ic \;\Longrightarrow\; (\mathcal{M}_G, D_M) \;\Longrightarrow\; \{\mathcal{H}, \langle\cdot|\cdot\rangle, \hat{H}, \hat{p}_\mu, \hat{M}, [\hat{q},\hat{p}], \square_M, \mathcal{D}_M, D_M^A, U, |\psi|^2, \text{SP}, R, \text{irreversibility}, \text{preferred basis}, \text{nonlocality}\}.$$

*This is the structural status of standard quantum mechanics: every postulate, every operator, and every interpretive feature is a theorem of one geometric principle, mediated through the source-pair.*

**Proof.** The proof is the cumulative content of §§III–XIII of the present paper, together with the imported derivations from [12] and [13]. The reduction proceeds in three layers:

*Layer 1: Principle generates source-pair.* By Theorem XIII.I (space-operator co-generation), $dx_4/dt = ic \Longrightarrow (\mathcal{M}_G, D_M)$.

*Layer 2: Source-pair generates standard structures.* By the universal derivability principle of [12] and the universal operator-derivability principle of [13], the source-pair generates all standard physical spaces and operators as derivatives via admissible operations.

*Layer 3: Standard structures supply the content of standard quantum mechanics.* By Propositions III.1, IV.1, V.1, VI.1, VII.1, VIII.1, IX.1, X.1–X.5, XII.1–XII.4, XIII.1–XIII.4, XIII.5, and XIII.6 of the present paper, the standard structures supply the Born rule, superposition, apparent collapse, irreversibility, preferred basis, nonlocality, absence of separate $(R)$ law, information preservation, unitarity derivation, Page curve, structural identification of measurement and information paradoxes, path integral and Feynman phase, Hilbert space and inner product and orthogonality, and dissolution of the measurement problem via the co-generation theorem. **∎**

The structural reduction is therefore *complete* at the level of standard quantum mechanics. Every axiom of the Dirac–von Neumann formulation, every interpretive feature of standard quantum mechanics, and every standard quantum operator is in the theorem column. What remains in the postulate column is exactly one physical-geometric relation: $dx_4/dt = ic$.

#### XIII.15.1 The complete tabular reduction

The reduction can be displayed in a master table:

| Standard postulate / structure | Status in standard QM | Status in McGucken dx₄/dt = ic framework | Source theorem |
|---|---|---|---|
| (Q1) Hilbert space | Postulated | Theorem | Proposition XIII.1 (forced); Theorem 12.1 of [12] (emergence) |
| (Q1') Specific carrier $L^2(\mathbb{R}^3)$, etc. | Postulated for each system | Theorem | Proposition XIII.2 (which Hilbert space) |
| (Q1'') Inner product $\langle\psi\|\phi\rangle$ | Postulated | Theorem | Proposition XIII.4 (Pieces 1–3) |
| (Q1''') Orthogonality structure | Postulated implicitly | Theorem | Proposition XIII.4 (Piece 4) |
| (Q2) Self-adjoint operators for observables | Postulated | Theorem | Proposition XIII.5 (operator hierarchy from $D_M$) |
| (Q3) Born rule $P = \|\psi\|^2$ | Postulated | Theorem | Proposition III.1 |
| (Q4) Schrödinger evolution | Postulated | Theorem | Theorem 7 of [6]; Proposition XIII.5 |
| (Q5) Canonical commutator $[\hat{q},\hat{p}] = i\hbar$ | Postulated | Theorem | Theorem XIII.H; Proposition XIII.5 |
| (Q6) Tensor product structure | Postulated | Theorem | Universal derivability principle of [12] |
| (R) Wave function collapse | Postulated as separate dynamics | Theorem (no separate dynamics) | Proposition V.1; Proposition XIII.6 |
| (SP) Superposition principle | Postulated | Theorem | Proposition IV.1 |
| Unitarity of $U$ | Postulated | Theorem | Proposition X.2 |
| Information preservation | Postulated implicitly | Theorem | Proposition X.1 |
| Path integral $\int \mathcal{D}x\,e^{iS/\hbar}$ | Postulated | Theorem | Proposition XII.4; Theorem 15 of [6] |
| Lorentzian wave operator $\square$ | Inherited from spacetime | Theorem | Theorem XIII.F |
| Wick rotation | Analytic prescription | Theorem | Theorem XIII.E |
| Preferred basis | Phenomenological / einselection | Theorem | Proposition VII.1 |
| Irreversibility of measurement | Postulated implicitly | Theorem | Proposition VI.1 |
| Quantum nonlocality | Empirical fact | Theorem | Proposition VIII.1 |
| Page curve | Conjectured | Theorem | Proposition X.3 |
| Measurement problem | Open foundational problem | Dissolved | Proposition XIII.6 |
| Black hole information paradox | Open foundational problem | Dissolved | Proposition X.4 |
| **Postulate column total** | **6 axiomatic structures + (R) + (SP) + interpretive choices + auxiliary postulates ($\sim 10^4$ bits)** | **One physical-geometric relation $dx_4/dt = ic$ ($\sim 10^2$ bits)** | **Two-orders-of-magnitude K-complexity reduction** |

The two-orders-of-magnitude reduction in K-complexity established in §XI.6 is now seen to be a consequence of the co-generation theorem: because the principle generates space and operator together, the bit-budget required to specify the framework is the bit-budget of the principle alone, with all derived structures inheriting their content from the principle's structural consequences.

#### XIII.15.2 The single-fact summary

The structural development of §§III–XIII can be summarized in one sentence:

*The McGucken dx₄/dt = ic framework dissolves the measurement problem because the space, the operator, and the principle are not three separate things but one fact viewed from three angles, and the apparent measurement event is a structural feature of the projection of that one fact onto the observer's spatial slice.*

The "three angles" are the McGucken Space $\mathcal{M}_G$ (the source-space side), the McGucken Operator $D_M$ (the source-operator side), and the McGucken Principle $dx_4/dt = ic$ (the source-law side). The "one fact" is the structural unity of these three angles, established by the space-operator co-generation theorem (Theorem XIII.I) and the inverse derivability (Corollary XIII.L). The "structural feature of the projection" is the apparent collapse $R$ (Proposition V.1) — not a separate dynamical event but the geometric content of the spatial-slice projection $\pi_{x_{\text{obs}}}$ from $\mathcal{M}_G$.

The measurement problem, in standard formulations, is the question: "How does the system, the apparatus, the observer, and the dynamics combine to produce a definite measurement outcome?" The McGucken dx₄/dt = ic framework answers: there are not four things to combine. There is one thing — the source-pair $(\mathcal{M}_G, D_M)$ generated by $dx_4/dt = ic$ — and the measurement event is the geometric self-intersection of this one thing with itself, viewed through the projection onto the observer's spatial slice. The Born-distributed outcome, the definiteness of the outcome, and the consistency with unitary evolution are all automatic structural features of this self-intersection. There is no separate mechanism, no separate ontology, no separate principle — there is one fact, and the measurement event is one of its readings.

This is the deepest structural statement that the present paper can make about the McGucken dx₄/dt = ic framework's resolution of the measurement problem. Every other interpretive programme has had to *add* structure to the bare formalism (a projection postulate, a branching primitive, a configuration-space ontology, a stochastic localization, an einselection coupling, a relational primitive, an agent) because the bare formalism does not have the structural resource to dissolve the problem. The McGucken dx₄/dt = ic framework has the resource because the source-pair $(\mathcal{M}_G, D_M)$ is co-generated by one law, and the framework's category structure therefore differs from all prior frameworks at the foundational level. The measurement problem, formulated within the standard categorical structure, simply has no place in the McGucken dx₄/dt = ic framework's category structure to live.

---

### XIII.16 Wave-particle duality as the dual-channel reading of x₄'s advance

The wave-particle duality of quantum mechanics has been interpreted in many ways across the history of quantum theory. Bohr called it complementarity. The Copenhagen interpretation called it context-dependent description. Bohmian mechanics retained both as separate ontological facts — a particle plus a guiding wave. de Broglie's pilot-wave theory took the wave as primary; Newton's corpuscular theory and the early Einstein photon-theory took the particle as primary. None of these treatments dissolves the duality; each takes it as a primitive of the formalism that requires interpretive accommodation.

The McGucken dx₄/dt = ic framework dissolves wave-particle duality entirely.

#### Theorem XIII.N (Wave-particle duality as the dual-channel reading of x₄'s advance)

**Theorem XIII.N (Wave-particle duality is a Grade-1 theorem of dx₄/dt = ic, not a primitive postulate).** *A quantum entity is simultaneously a McGucken-Sphere wavefront (Channel B reading) and a localizable particle (Channel A reading), with both aspects geometric consequences of the same physical fact: x₄ is advancing at rate ic from every spacetime event, spherically symmetrically. The wave aspect and the particle aspect are not two competing descriptions of the same entity but the geometric-propagation reading and the algebraic-symmetry reading of the same single physical fact.*

**Proof.**

**The wave aspect.** When x₄ advances at rate ic from a spacetime point p₀, the three-dimensional cross-section at observer time t is the McGucken Sphere Σ_+(p₀) of radius c(t − t₀) centered at the spatial location of p₀ (Convention I.5.3). This is geometrically the forward null cone, structurally Huygens' secondary wavefront from p₀, and operationally the support of the retarded Green's function of the wave equation (Klein-Gordon for a massive particle, d'Alembert for a massless particle). The four are one geometric object under four names: the McGucken Sphere, the forward null cone, Huygens' secondary wavefront, and the support of the retarded Green's function. That object is the wave aspect of every quantum entity.

The wave aspect is therefore not a metaphor or a heuristic — it is the literal three-dimensional cross-section of the four-dimensional expansion of x₄ from the source event p₀. The wave equation governing the propagation of ψ is the equation of motion for this cross-section as t advances; the wavefront's spherical symmetry is x₄'s spherical symmetry projected onto Σ_t.

**The particle aspect.** Channel A's algebraic-symmetry reading of the same physical x₄-advance treats the entity as a localizable point — a position eigenstate in the Hilbert-space representation, with the momentum operator p̂ = −iℏ ∂/∂q as the generator of spatial translations through Stone's theorem [6, Theorem 10]. The position-eigenstate representation diagonalizes the position observable; the momentum-eigenstate representation diagonalizes the momentum observable; the canonical commutation relation [q̂, p̂] = iℏ is the algebraic content of x₄'s spherical advance under spatial translations.

The particle aspect is the algebraic-symmetry side of the same Klein pair whose geometric-propagation side is the wave aspect. The position eigenstate is mathematically a delta function δ(x − x₀), which is a singular limit of the McGucken-Sphere wavefront as the wavefront's spatial extent shrinks to a point — the "particle" is the wavefront localized to a single spatial location. In the position basis, the wavefront ψ(x, t) decomposes as a superposition of position eigenstates: ψ(x, t) = ∫ ψ(x', t) δ(x − x') dx', expressing the wavefront as an integral over its values at each spatial point.

**The duality is the dual-channel structure.** The wave aspect (Channel B reading: McGucken Sphere) and the particle aspect (Channel A reading: position eigenstate) are not two separate ontological items competing for primacy. They are the two readings of the same single physical fact: x₄ is advancing at rate ic from every event, spherically symmetrically. The Channel A reading describes how this advance manifests in the algebraic-symmetry content (Hilbert-space operators, Stone's theorem, Wigner classification); the Channel B reading describes how this advance manifests in the geometric-propagation content (Huygens wavefronts, path-integral histories, retarded Green's functions). Both readings are mathematically equivalent (via the equivalence of Channels A and B established in Proposition XIII.3) and physically simultaneous: the same entity is wave and particle at the same time, in the same spacetime, because it is one four-dimensional object whose 3D cross-section can be read either way.

**The double-slit experiment in geometric form.** The double-slit experiment is the canonical demonstration of wave-particle duality. In the McGucken dx₄/dt = ic framework, the experiment is read as a literal geometric statement. The photon's wavefront — the McGucken Sphere from the photon emission event — propagates at speed c through both slit openings simultaneously, because the wavefront is spherically symmetric and the slits subtend a non-trivial portion of the sphere's solid angle. At each slit, by Huygens' principle ([6, Theorem 1]), the wavefront acts as a secondary source of new McGucken Spheres expanding from the slit openings. These two secondary McGucken Spheres overlap at the detection screen, producing the interference pattern via Proposition IV.1 (superposition as geometric overlap).

The localized detection click — the "particle" aspect — is the projection of the wavefront onto a specific detector pixel, which by the Born rule (Proposition III.1) occurs with probability density |ψ|². The "particle" is not a separate ontological entity from the "wave"; it is the same McGucken Sphere read in the Channel A representation as a position eigenstate at the moment of detection.

The double-slit result — interference pattern with localized detections — is the geometric signature of the dual-channel content: the wavefront passes through both slits (Channel B), interferes at the screen (Proposition IV.1), and is detected at one specific pixel with squared-amplitude probability (Proposition III.1, Channel A reading). No mystery, no collapse problem at the level of physical mechanism, no observer-dependent reality. Just the geometry of x₄'s spherical advance, projected onto a 3D detector.

**Photons as perfect tracers.** A particularly sharp consequence: photons travel at v = c, which by the four-velocity-budget structure (Proposition II.2 of [6, §1.5.2]) implies dx₄/dτ = 0 — photons do not advance in x₄. They ride x₄'s expansion as a surfer rides a wave, stationary relative to it. This is what makes photons the perfect tracers of x₄'s motion: a photon's position on the McGucken Sphere is the position of the wavefront itself, with no offset due to differential x₄-advance. Massive particles, by contrast, advance in x₄ at rate dx₄/dτ = ic in their rest frame, accumulating phase at the Compton frequency mc²/ℏ.

The wave-particle duality of photons is therefore the clearest case: a photon *is* a McGucken-Sphere wavefront, with no separate particle aspect — its position on the wavefront is the position of the wavefront, with the "particle" reading being the Channel A representation of the wavefront's spatial localization at the moment of detection. **∎**

### XIII.17 The "Hilbert space category problem" addressed

The phrase "Hilbert space category problem" appears in some of the foundational literature without a fixed canonical meaning. We address three distinct readings of this phrase, each of which corresponds to a structural concern about the Hilbert-space framework, and each of which is dissolved by the McGucken dx₄/dt = ic framework.

**Reading 1: Which Hilbert space for a given physical system?** Standard textbooks postulate ℋ but give no derivation of *which* ℋ. This is dissolved by Proposition XIII.2: the textbook choices L²(ℝ³), ℂ² ⊗ L²(ℝ³), Fock space, etc., are forced by the geometric structure of the McGucken-Sphere wavefront for the system in question.

**Reading 2: Probability/amplitude category mismatch.** Wavefunctions are amplitudes (complex-valued); measurement outcomes are probabilities (real-valued non-negative). The standard formalism bridges these via the Born rule as a separate axiom. This is dissolved by Proposition III.1: the Born rule is the unique probability density consistent with the geometric structure of x₄'s spherical expansion, with the squared-amplitude form forced by positivity, normalization, superposition, and Lorentz-covariance. The category mismatch is not a mismatch but a consequence of the geometry.

**Reading 3: Categorical foundations of quantum mechanics.** The Selinger / Abramsky / Coecke programme takes dagger-compact closed categories as the foundation, with Hilbert space as one model among others. This is addressed by Proposition XIII.3: the categorical, C\*-algebraic, Hilbert-space, and path-integral formulations are equivalent representations of the dual-channel content of dx₄/dt = ic, with no foundational hierarchy among them. The categorical foundation is one representation of the same physical content as the Hilbert-space formulation.

In all three readings, the structural reason the puzzle arises in standard quantum mechanics is the same: the Hilbert space is taken as foundational, with the physical content unfolding within it. In the McGucken framework, the order is reversed: physics begins with dx₄/dt = ic, and the Hilbert space (with its specific carrier, scalar field, inner product, and place among representations) emerges as one natural representation of the physical content. Removing the Hilbert space from the foundational base and placing it in the theorem column dissolves all three readings of the puzzle simultaneously.

### XIII.18 Hilbert space is not uniquely quantum

A final structural observation. Hilbert spaces are not unique to quantum mechanics: classical wave equations admit Hilbert-space formulations as well. Maxwell's equations admit a Hilbert-space formulation in terms of square-integrable electromagnetic fields on spatial slices; the wave equation in optics admits a Hilbert-space formulation in terms of square-integrable acoustic or optical wavefunctions; Huygens' principle admits a Hilbert-space formulation in terms of square-integrable Green's-function kernels. None of these classical wave-mechanical systems exhibits quantum behavior, despite using Hilbert spaces.

What makes a system *quantum* in the McGucken dx₄/dt = ic framework is not the Hilbert space itself but three additional structural features: (i) the dual-channel content of dx₄/dt = ic (algebraic-symmetry plus geometric-propagation), (ii) the Compton-frequency coupling of matter to x₄'s expansion at rate ω_C = mc²/ℏ, and (iii) the action quantum ℏ as the action-per-x₄-cycle [6, Theorem 5; 76]. A wave equation without these three features is classical; a wave equation with them is quantum. The Hilbert space carries both classical and quantum content; the dual-channel structure plus Compton coupling plus ℏ is what makes the content quantum.

This explains why Hilbert spaces appear in classical contexts (Maxwell, optics, Huygens) without producing quantum behavior: the Hilbert space is necessary for wave mechanics but not sufficient for quantum mechanics. The McGucken dx₄/dt = ic framework supplies the additional ingredients — the dual-channel structure, the Compton coupling, and ℏ — that distinguish quantum from classical wave mechanics, with all three features derived from dx₄/dt = ic.

### XIII.19 The complete structural reduction

We can now state the complete structural reduction of standard quantum mechanics in the McGucken dx₄/dt = ic framework. The standard Dirac–von Neumann axiomatic system has six independent postulates Q1–Q6:

* Q1: state space is a complex separable Hilbert space.
* Q2: observables are self-adjoint operators on the Hilbert space.
* Q3: Born rule for measurement probabilities.
* Q4: Schrödinger evolution between measurements.
* Q5: canonical commutation relation [q̂, p̂] = iℏ.
* Q6: tensor product structure for composite systems.

In the McGucken framework, *all six postulates* are derived theorems of dx₄/dt = ic plus standard structural commitments shared with all reasonable physical theories. The derivations:

* **Q1** (Hilbert space): forced by Proposition XIII.1 (vector-space structure from superposition, complex scalars from x₄-perpendicularity, inner product from Born-rule overlap, separability from spatial-slice geometry).

* **Q2** (self-adjoint operators): forced by the requirement that observables be real-valued combined with the action of one-parameter unitary groups via Stone's theorem [6, Theorem 10].

* **Q3** (Born rule): forced by Proposition III.1 (squared-amplitude geometry of McGucken-Sphere cross-section).

* **Q4** (Schrödinger evolution): forced by Lorentz-covariance plus the rest-mass phase factor e^(−imc²t/ℏ) from x₄-advance at rate ic [6, Theorem 7].

* **Q5** (canonical commutation): forced by Stone's theorem applied to spacetime translations, with the i in [q̂, p̂] = iℏ being the same i as in x₄ = ict [6, Theorem 10; 77].

* **Q6** (tensor product structure): forced by the linearity of Hilbert space (Q1) combined with subsystem decomposition, with the multiplicative composition of independent McGucken-wavefronts producing the tensor product [6, Theorem 20].

The complete structural reduction places all six postulates of standard quantum mechanics in the theorem column, leaving exactly one principle in the postulate column: dx₄/dt = ic. The Kolmogorov-complexity ratio is roughly 10⁴ bits (full Q1–Q6) to 10² bits (McGucken Principle), a two-orders-of-magnitude compression with no loss of physical content [29, §3.1].

### XIII.20 Summary

The Hilbert-space framework of standard quantum mechanics — its complex scalar field, its specific carrier space for any given physical system, its inner-product structure, and its primacy among representations of quantum dynamics — is forced by dx₄/dt = ic together with Propositions III.1 (Born) and IV.1 (superposition), with no independent axiomatic content. Proposition XIII.1 establishes that the Hilbert-space framework itself is derived; Proposition XIII.2 establishes that each specific Hilbert space (L²(ℝ³), ℂ² ⊗ L²(ℝ³), Fock space) is forced by the geometric structure of the corresponding system; Proposition XIII.3 establishes that Hilbert space is one of several mathematically equivalent representations, naturally suited for the algebraic-symmetry channel of the dual-channel content; Proposition XIII.4 establishes that wave-particle duality is the dual-channel reading of x₄'s advance, with the wave aspect (Channel B: McGucken Sphere) and the particle aspect (Channel A: position eigenstate) being the geometric-propagation and algebraic-symmetry readings of the same single physical fact.

The structural reduction is now complete: all six postulates Q1–Q6 of the standard Dirac–von Neumann system are theorems of dx₄/dt = ic. The "Hilbert space category problem" — in any of its three readings — dissolves into the geometric content of the same principle. Wave-particle duality is no longer a primitive of the formalism but a consequence of the dual-channel structure. The double-slit experiment becomes a literal geometric statement about the propagation and overlap of McGucken-Sphere wavefronts, with no observer-dependent reality and no separate collapse mechanism.

The McGucken dx₄/dt = ic framework therefore subtracts the entire Hilbert-space framework from the foundational column. What remains in the foundational column is one geometric principle: the fourth dimension is expanding spherically at the velocity of light. Everything else — the Hilbert space, the Born rule, the superposition principle, wave-particle duality, the apparent collapse, the spin-statistics theorem, the canonical commutation relation, the Schrödinger equation — is in the theorem column.

---

## XIV. Why Other Born-Rule Derivations Fall Short

We now develop the comparative analysis in detail. The seven major interpretive programmes are surveyed under three structural criteria:

**(C-I)** Does the framework derive the Born rule from a single underlying principle?

**(C-II)** Does the framework resolve the preferred-basis problem from a specific physical mechanism?

**(C-III)** Does the framework supply a geometric account of nonlocality consistent with relativistic causality?

Each of the seven existing frameworks fails at least one of these criteria. The McGucken framework satisfies all three through the single principle dx₄/dt = ic.

### XIV.1 Copenhagen

**(C-I) Born rule.** Copenhagen takes the Born rule as a postulate, with no derivation from a deeper principle. The interpretation explicitly accepts |ψ|² as primitive, treating it as the operational rule for converting wavefunction amplitudes to measurement probabilities. **Fails.**

**(C-II) Preferred basis.** Copenhagen places the quantum-classical cut operationally — wherever the experimenter draws it. The cut is observer-dependent and has no specific physical mechanism. **Fails.**

**(C-III) Nonlocality.** Copenhagen treats nonlocality as a holistic feature of the wavefunction, with no geometric mechanism. The framework reports Bell violations and the no-signalling theorem but supplies no underlying account. **Fails.**

**Diagnosis.** Copenhagen fails all three criteria. It is the historically dominant interpretation but offers no foundational reduction.

### XIV.2 Many-Worlds

**(C-I) Born rule.** Many-Worlds attempts to derive the Born rule from auxiliary frameworks: decision theory (Deutsch1999; Wallace2012) requires rationality axioms whose justification has been disputed [36; 37]; envariance (Zurek2005) requires specific environmental-coupling assumptions. Neither derivation reduces to a single underlying physical principle. **Partial — auxiliary postulates required.**

**(C-II) Preferred basis.** Many-Worlds appeals to environmental decoherence to select the pointer basis, inheriting the coupling-dependence from the standard decoherence programme. **Partial — depends on environmental coupling input.**

**(C-III) Nonlocality.** Many-Worlds treats correlations as preserved across branches by the unitary evolution; no geometric mechanism is supplied for the correlations themselves. The framework explains the no-signalling theorem (different branches don't interact) but does not supply a structural account of why entangled particles are correlated in the first place. **Fails.**

**Diagnosis.** Many-Worlds fails (C-III) and partially fails (C-I) and (C-II). Its derivations of the Born rule require auxiliary postulates whose own justification has generated extensive critique.

### XIV.3 Bohmian mechanics

**(C-I) Born rule.** Bohmian mechanics derives the Born rule from the equilibrium hypothesis: particles are initially distributed according to |ψ|². Valentini [73] showed that quantum non-equilibrium distributions are stable under Bohmian dynamics, so the equilibrium hypothesis is a separate postulate not derivable from the Bohmian dynamics itself. **Partial — equilibrium hypothesis is itself a postulate.**

**(C-II) Preferred basis.** Bohmian mechanics has a built-in preferred basis: the position basis, since hidden variables are particle positions. **Satisfies, but at the cost of assuming the position basis.**

**(C-III) Nonlocality.** Bohmian mechanics provides explicit nonlocal hidden-variable dynamics: the guidance equation depends on the global wavefunction, producing nonlocal influences on particle positions. The framework satisfies the no-signalling theorem but exhibits manifest nonlocality at the level of the hidden variables. **Partial — explicit nonlocality, but no geometric mechanism.**

**Diagnosis.** Bohmian mechanics requires the equilibrium hypothesis, hidden-variable particle positions, and an explicitly nonlocal guidance equation. The position basis is built in by hand; nonlocality is mechanical, not geometric.

### XIV.4 GRW spontaneous localization

**(C-I) Born rule.** GRW derives the Born rule from the stochastic-localization dynamics, with phenomenological parameters λ (rate) and a (localization width). The Born rule emerges as the long-time limit of the localization process. **Partial — phenomenological parameters required, dynamics modified.**

**(C-II) Preferred basis.** GRW selects the position basis by construction: the localization terms are spatial Gaussians. The cut between quantum and classical is set by the parameters λ, a. **Partial — specific basis built in, parameters phenomenological.**

**(C-III) Nonlocality.** GRW's stochastic terms are nonlocal in a specific sense (the localization at one point affects the wavefunction globally). No geometric mechanism is supplied for Bell correlations. **Fails.**

**Diagnosis.** GRW modifies (U) by adding stochastic terms, with phenomenological parameters chosen to match observed quantum-classical behavior. The Born rule emerges from the modified dynamics, but the modification itself is an additional postulate.

### XIV.5 Decoherence-plus-environmental-selection

**(C-I) Born rule.** Decoherence does not derive the Born rule. The framework explains why off-diagonal terms in ρ_S decay rapidly, but the diagonal weights |c_i|² are not derived from the decoherence dynamics — they are taken as primitive. **Fails.**

**(C-II) Preferred basis.** Decoherence selects a pointer basis based on system-environment coupling: the pointer basis is the basis monitored by the environment, where "monitored" depends on the coupling Hamiltonian. The framework requires specifying the coupling. **Partial — basis selected, but coupling is input, not derived.**

**(C-III) Nonlocality.** Decoherence does not address nonlocality directly; it supplements the standard formalism with a treatment of environmental coupling. **Fails.**

**Diagnosis.** Decoherence explains apparent classicality but does not derive the Born rule and does not address nonlocality. It supplements rather than replaces the standard interpretation.

### XIV.6 Relational Quantum Mechanics

**(C-I) Born rule.** RQM takes the Born rule as a postulate, treating it as the rule for one system's information about another. **Fails.**

**(C-II) Preferred basis.** RQM treats the preferred basis as relational — different observers have different preferred bases. There is no observer-independent answer. **Fails (operationally arbitrary).**

**(C-III) Nonlocality.** RQM treats nonlocality as relational: correlations exist between systems but are not features of any observer-independent reality. No geometric mechanism is supplied. **Fails.**

**Diagnosis.** RQM addresses the foundational questions by relativizing them to observers, accepting that there is no observer-independent answer to (C-I), (C-II), (C-III). This is a coherent philosophical position but does not supply a structural reduction of the measurement problem.

### XIV.7 QBism

**(C-I) Born rule.** QBism takes the Born rule as a normative coherence requirement on the agent's beliefs, justified by Dutch-book arguments. The framework explicitly declines to derive the Born rule from a deeper physical principle. **Fails (explicitly).**

**(C-II) Preferred basis.** QBism treats the basis as a feature of the agent's choice of measurement, not as an objective feature of the system. **Fails (operationally arbitrary).**

**(C-III) Nonlocality.** QBism treats correlations as features of the agent's beliefs about multiple measurement outcomes, not as objective features of the system. No geometric mechanism. **Fails.**

**Diagnosis.** QBism is explicitly anti-realist about the wavefunction and the measurement process. The Born rule is a coherence requirement on belief, not a derived fact about nature. The framework declines all three criteria as a matter of philosophical position.

### XIV.8 Summary table

**Table XIII.1. Comparison of seven interpretive programmes against the McGucken dx₄/dt = ic framework on three criteria.**

| Programme | (C-I) Born from single principle | (C-II) Preferred basis from physical mechanism | (C-III) Geometric nonlocality |
|-----------|----------------------------------|------------------------------------------------|-------------------------------|
| Copenhagen | Fails | Fails | Fails |
| Many-Worlds | Partial (auxiliary postulates) | Partial (depends on coupling) | Fails |
| Bohmian | Partial (equilibrium hypothesis) | Satisfies (built in) | Partial (mechanical, not geometric) |
| GRW | Partial (phenomenological parameters) | Partial (parameters set by hand) | Fails |
| Decoherence | Fails | Partial (coupling is input) | Fails |
| RQM | Fails | Fails | Fails |
| QBism | Fails (explicitly) | Fails | Fails |
| **McGucken** | **Satisfies (Proposition III.1)** | **Satisfies (Proposition VII.1)** | **Satisfies (Proposition VIII.1)** |

The McGucken dx₄/dt = ic framework is the *only* framework that fully satisfies all three criteria. Each of the seven prior frameworks fails at least one criterion, and most fail multiple criteria.

### XIV.9 The structural reason

The structural reason for the McGucken framework's uniqueness is the dual-channel content of dx₄/dt = ic [27, §V; 6, Theorem 14]:

* **Channel A** (algebraic-symmetry content) drives the derivation of the Born rule via SO(3) Haar measure (Proposition III.1, Piece 3) and the canonical commutation relation [q̂, p̂] = iℏ via Stone's theorem [6, Theorem 10].

* **Channel B** (geometric-propagation content) drives the McGucken Sphere structure (Convention I.5.3), the six-sense null-surface identity (Convention I.5.6, Proposition VIII.1), the wave-particle duality (Theorem 6 of [6]), the geometric overlap of McGucken-Sphere wavefronts that produces superposition (Proposition IV.1), and the spatial-cross-section reading of apparent collapse (Proposition V.1).

The two channels together supply both the algebraic structure of the Born rule (squared amplitudes from SO(3) symmetry) and the geometric structure of nonlocality (six-sense identity from the McGucken Sphere). No single-channel framework can supply both. The structural completeness of the McGucken dx₄/dt = ic framework on the measurement problem is therefore a consequence of the Principle's dual-channel content — the same dual-channel content that, via [29, §6.7], establishes the McGucken Principle as the unique foundational principle satisfying the seven-duality test.

---

## XV. Falsifiability and Empirical Discriminators

The McGucken account of the measurement problem makes specific empirical predictions that distinguish it from competing accounts. Three concrete tests:

### XV.1 Cross-species Compton-frequency decoherence (Theorem 22 of [6])

**Prediction.** The decoherence timescales for different particle species satisfy the cross-species ratio T_{dec,A} / T_{dec,B} = (m_B / m_A)² = (ω_{C,B} / ω_{C,A})², where ω_C = mc²/ℏ is the Compton angular frequency. The mass-squared scaling contrasts with thermal decoherence's 1/m scaling and provides an empirical discriminator between the McGucken dx₄/dt = ic framework and standard thermal-decoherence accounts.

**Test.** Cold-atom systems at ultra-low temperatures, comparing decoherence times for atoms of different masses (e.g., ⁴⁰K vs ⁸⁷Rb in optical lattices). If the McGucken prediction is confirmed, environmental Compton-frequency coupling is established as the preferred-basis selection mechanism. If thermal scaling is observed instead, the McGucken account of preferred-basis selection requires reformulation, but the McGucken Principle itself remains intact.

**Status.** The signature D_x^(McG) = ε²c²Ω/(2γ²) of [4] is the relevant order-of-magnitude prediction, with current experimental bounds at ε ≲ 10^{−20} for Planck-frequency Ω. The prediction is testable at the 10^{−18} fractional precision now achievable with optical atomic clocks.

### XV.2 McGucken-Bell directional modulation [15]

**Prediction.** Bell-inequality violations show specific angular signatures that depend on the x₄-phase geometry of the entangled system's local origin, beyond the standard angular dependence of the CHSH protocol.

**Test.** Modified CHSH experiments in which the angular configurations of measurement bases are varied with respect to the entangled system's emission geometry. The McGucken prediction adds a specific small modulation on top of the standard quantum prediction, testable with current Bell-experiment apparatus at high statistics.

**Status.** The McGucken-Bell modulation is a direct consequence of the six-sense null-surface identity (Proposition VIII.1) combined with the Compton-frequency phase accumulation along the particles' worldlines. Quantitative predictions are developed in [15].

### XV.3 No magnetic monopoles

**Prediction.** The McGucken dx₄/dt = ic framework forces bundle-triviality of the x₄-phase via the globally-defined +ic reference phase [2, §III.5a]. Magnetic monopoles do not exist.

**Test.** Continued non-detection of magnetic monopoles in cosmic-ray and accelerator searches confirms the prediction. Any detection of a magnetic monopole would falsify the McGucken Principle (Level 1 falsification per [6, §1.4]).

**Status.** No magnetic monopoles have been detected to date despite extensive searches [119]. The McGucken dx₄/dt = ic framework's prediction is consistent with the current experimental status.

---

## XV.bis The McGucken Principle dx₄/dt = ic Resolution of the Now–Entropy Paradox: The Advancing Local Now and the Strict Increase of Entropy as Theorems of the Same Fact That Derives Quantum Mechanics, General Relativity, and Thermodynamics

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality. The same physical fact that derives the measurement theorems of this paper resolves a standing conflict in the physics and philosophy of time: relativity, taken as the complete description of the world, leaves no present moment, while the second law of thermodynamics is stated as a law of increase, and increase is change measured against a present. The McGucken dx₄/dt = ic framework supplies the present as the advancing extent of $x_4$ at every event and derives the entropy increase from the expansion of the McGucken Sphere ([7]), so the two statements hold together without a universal now and without an imported boundary condition.

### XV.bis.1 The paradox: three premises and the contradiction

The McGucken Principle dx₄/dt = ic predicts, at every event, a present that advances — the current extent of $x_4$ — and a direction of advance fixed by the sign $+ic$; the paradox below is what remains when that physical present is removed and relativity is read as the whole of the world.

Three premises carry the tension. The **No-Now premise**: spacetime together with the matter and fields in it is the complete description of the world, and in that description there is no universal now and no local now. The **Second-Law premise**: entropy always increases. The **Later-Than-Now premise**: entropy will be higher later than it is now.

**Proposition XV.bis.1 (the Now–entropy contradiction).** The No-Now premise, the Second-Law premise, and the Later-Than-Now premise are not jointly satisfiable.

*Proof.* Assume the No-Now premise. The Later-Than-Now premise compares the entropy at the present event with the entropy at a later event; with no present event the comparison has no first term, so it has no truth value. The Second-Law premise asserts an increase; an increase is a present value replaced by a greater value after the present has advanced, and with no present that advances there is nothing to be replaced. Hence under the No-Now premise neither of the other two premises is satisfiable. ∎

The word "increase" is tensed: it reports a value at a present that is then exceeded. The four-dimensional description that relativity supplies is tenseless: it assigns every event its entropy on equal terms, with no event marked present. Stating the second law as a law of increase states a tenseless world in tensed language, which is the form of the contradiction (the tensed/tenseless distinction is McTaggart's A-series/B-series split, [151]).

### XV.bis.2 What relativity alone keeps and what it loses

The McGucken Principle dx₄/dt = ic predicts that entropy grows because the McGucken Sphere grows; relativity read without that expansion keeps a weaker thing, an ordering, and the gap between the ordering and the growth is exactly what the Principle fills.

Relativistic thermodynamics writes the second law as an entropy current $s^\mu$ with $\partial_\mu s^\mu \ge 0$, and the entropy on a slice $\Sigma$ as $S[\Sigma] = \int_\Sigma s^\mu \, d\Sigma_\mu$. Gauss's theorem applied to the region between two slices, one wholly later than the other, gives $S[\Sigma_{\text{later}}] \ge S[\Sigma_{\text{earlier}}]$ for every foliation, with no universal now required. This is an **ordering** of entropy values across slices. It is not an **increase**: under the No-Now premise every slice and its entropy stand in the description together, no slice is present, and no value is replaced by a later one. Relativity keeps the ordering and loses the increase, and it also loses the direction, since the equations do not mark which end of time is later and the same spacetime carries "entropy rises toward the later end" and "entropy falls toward the later end" under the two namings. A resolution must restore three things the ordering lacks: a local now that advances, the absence of a universal now (Einstein's 1905 relativity of simultaneity, [152]), and a direction of time.

### XV.bis.3 Prior commentary: Eddington's challenge and Price's dilemma

The McGucken Principle dx₄/dt = ic reading of the prior literature is that each prior position isolates one horn of the paradox and pays for it; the McGucken resolution pays none of those costs because the advancing present and the entropy increase descend from one fact.

**Eddington posed it as a challenge (1928).** He coined the term and located the asymmetry in entropy: "I shall use the phrase 'time's arrow' to express this one-way property of time which has no analogue in space," and "So far as physics is concerned, time's arrow is a property of entropy alone" ([134], pp. 69, 80). He also held that the four-dimensional world carries no direction of its own — "there is no signboard to indicate that it is a one-way street" — and that "something must be added to the geometrical conceptions comprised in Minkowski's world before it becomes a complete picture of the world as we know it" ([134], pp. 68–69). The McGucken dx₄/dt = ic framework is the addition Eddington asked for: the physical expansion of $x_4$ at $c$, with its sign $+ic$ as the one-way marker.

**Price sharpened the challenge into a dilemma (1996, 2010).** Price separates the direction of time from its passage and assigns thermodynamics only the former: "the thermodynamic asymmetry is an asymmetry of physical processes in time, not an asymmetry of time itself," the entropy gradient being objective while its up-or-down labelling is conventional, and "asymmetry arises only when we apply a low entropy condition at one end" ([135], pp. 120, 124). He endorses Weyl's "the objective world simply is, it does not happen" ([148], p. 116; quoted in [135]) and concludes "Eddington is wrong about becoming." Callender states the trap as Price's dilemma: "the (local) thermodynamic arrow is explicable just in case (globally) there isn't one" ([136]). The McGucken dx₄/dt = ic framework dissolves the dilemma because the local arrow is the per-event Sphere expansion and the global arrow is the same $+ic$ at every event — one fact at two scales, not a trade-off between them.

**The three standard resolution routes each pay a specific cost.** The deflationary route (Price, [135]; Rovelli, [137]; Davies, [139]) keeps the block and the absence of a now and gives up the increase: Rovelli holds that "all phenomena that distinguish the past from the future … can be traced to entropy increase" while "the entropy we ascribe to the universe depends on the peculiar coupling between us and the rest of the universe" ([137]), so the growth is perspectival; Davies holds that "nothing in known physics corresponds to the passage of time" and "the arrow of time denotes an asymmetry of the world in time, not an asymmetry or flux of time" ([139]). The boundary-condition route (Albert, [145]; Loewer; Carroll, [147]; with Penrose's Weyl-curvature form) keeps time-symmetric dynamics and imports the direction from a low-entropy initial macrostate, the Past Hypothesis ([136], §3.2), which carries Penrose's $10^{-10^{123}}$ fine-tuning as brute input. The primitive route (Maudlin, [143]) keeps both the present and the increase by taking the passage of time as a fundamental fact with no mechanism. A fourth position restores time programmatically without a mechanism (Smolin, [144], via a preferred foliation and evolving laws), a fifth denies time and derives a bidirectional arrow from a Janus point (Barbour, [146]), and a sixth relocates the present to the agent (Mermin, [142]: "physics seems to have nothing whatever to say about the local Now at a single event"). Einstein himself accepted the absence of the now from physics with, in Carnap's report, "painful but inevitable resignation" ([150]), and Gödel concluded that if simultaneity is relative then "reality cannot be split up into such layers" ([149]).

**Two physicists build a physical, advancing present — the nearest prior art.** Ellis proposes the evolving block universe, "a spacetime which grows and incorporates ever more events," whose future boundary is "the ever-changing present," grounded in quantum measurement and general relativity's "preferred timelike lines and surfaces" ([140]). Muller and Maguire propose that "the flow of time consists of the continuous creation of new moments, new nows, that accompany the creation of new space" ([141]). Each supplies an advancing present, as the McGucken dx₄/dt = ic framework does; Ellis grounds it in quantum measurement and a general-relativistic foliation, Muller in the Hubble expansion of the three spatial dimensions. Neither derives the entropy increase from the same fact, and neither keeps the relativity of simultaneity exactly, because a preferred foliation or a cosmic time is introduced. The McGucken resolution grounds the advancing local now in the per-event expansion of $x_4$, keeps Einstein's 1905 result exactly because the accumulated advance $X_4 = ic\,\tau$ is path-dependent and the local nows of different worldlines join into no universal now, and derives the increase from the same expansion.

### XV.bis.4 The resolution from dx₄/dt = ic

The McGucken Principle dx₄/dt = ic predicts, from the one physical fact that $x_4$ expands at $c$ from every event, each of the three things the ordering lacks, and it does so as theorems rather than as posits.

A **local now that advances** is the present extent of the expansion of $x_4$ at a point, which advances at the rate $c$; the Principle places at every event a quantity that changes. **No universal now** survives, because the rate $ic$ is per-event and the accumulated advance $X_4 = ic\,\tau$ along a worldline is path-dependent (the proper time $\tau$ up to the factor $ic$), so the local nows of worldlines that meet twice differ and cannot be joined across the universe; Einstein's 1905 relativity of simultaneity stands ([152]). A **direction of time** is the sign $+ic$, the one symmetry break of the framework, which marks the later end of time at every event. The **strict increase of entropy** is a theorem of the Sphere's expansion: the massive-particle ensemble undergoing the spherical isotropic random walk forced by $dx_4/dt = ic$ has $dS/dt = (3/2)k_B/t > 0$, and the photon entropy on the McGucken Sphere has $dS/dt = 2k_B/(t-t_0) > 0$ (strict geometric rates, Theorem 6 of [154]; [7]). No Past Hypothesis is imported; the lowest-entropy moment is $x_4$'s origin by geometric necessity (Theorem 14 of [154]), so the $10^{-10^{123}}$ fine-tuning the boundary-condition route carries does not arise.

The resolution is not a patch in the deflate, boundary, or primitive categories. It is derivation from one physical fact, and the same fact that resolves the paradox derives general relativity ([3]), quantum mechanics ([6]), and thermodynamics ([7]) each as its own chain of theorems. The advancing local now, the absence of a universal now, the $+ic$ direction, and the strict entropy increase are four readings of the one expansion, and the paradox dissolves as a corollary of the mechanism that is already doing the primary work across those three sectors of physics.

### XV.bis.5 Comparison tables

Each table places the McGucken Principle dx₄/dt = ic at the far left.

**Table XV.bis-1. The five criteria a resolution must meet (§XV.bis.2), by framework.**

| Criterion | McGucken dx₄/dt = ic | Deflationist (Price, Rovelli, Davies) | Boundary condition (Albert, Loewer, Carroll, Penrose) | Primitive passage (Maudlin) | Restore time (Smolin) | Timeless / Janus (Barbour) |
|---|---|---|---|---|---|---|
| Local now that advances | theorem: present extent of $x_4$, advancing at $c$ | denied | not supplied | primitive | asserted (foliation) | denied (illusion) |
| No universal now (1905 kept) | yes: $X_4 = ic\,\tau$ path-dependent | yes | yes | contested | rejected (preferred foliation) | — |
| Direction of time from | $+ic$, one symmetry break | conventional labelling of a gradient | imported low-entropy boundary | primitive | preferred foliation | bidirectional from Janus point |
| Entropy as strict increase | theorem: $dS/dt>0$ ([7]) | ordering only, not increase | increase given the Past Hypothesis | primitive | asserted, not derived | bidirectional, not monotone |
| Supplied by a mechanism | yes: the expansion of $x_4$ | no (deflation) | no (boundary import) | no (primitive) | no (restoration posited) | no (primitive) |

**Table XV.bis-2. Which of the three premises each position abandons.**

| Position | No-Now premise | Second Law as increase | Later-Than-Now | Net |
|---|---|---|---|---|
| McGucken dx₄/dt = ic | kept for the universal now; denied for a local now | kept (theorem) | kept (local now) | all three reconciled |
| Deflationist | kept in full | given up (ordering only) | given up | consistent by deflation |
| Boundary condition | kept in full | kept via boundary input | kept | consistent by added condition |
| Primitive passage | rejected (passage is real) | kept | kept | consistent by primitive |

**Table XV.bis-3. Eddington's challenge and Price's dilemma.**

| | McGucken dx₄/dt = ic | Deflationist | Boundary condition | Primitive passage |
|---|---|---|---|---|
| Local arrow explained | yes (per-event Sphere expansion) | as a local gradient only | yes, given the boundary | no (primitive) |
| Global arrow survives | yes ($+ic$ at every event) | denied at the whole-universe level | yes (one boundary) | yes (primitive) |
| One fact or a trade-off | one fact at two scales | a trade-off (Price's dilemma) | dynamics plus boundary | a primitive |
| Price's dilemma | dissolved | accepted | sidestepped by boundary | sidestepped by primitive |

**Table XV.bis-4. Whether the resolving mechanism also derives the pillars of physics.**

| Derives, from the same fact that resolves the paradox: | McGucken dx₄/dt = ic | Deflationist | Boundary condition | Primitive passage | Restore time | QBist now |
|---|---|---|---|---|---|---|
| The paradox resolution | yes | by deflation | by boundary import | by primitive | asked for, not derived | observer-side |
| Quantum mechanics as a theorem chain | yes ([6]) | no | no | no | no | no |
| General relativity as a theorem chain | yes ([3]) | no | no | no | no | no |
| Thermodynamics as a theorem chain | yes ([7]) | no | no | no | no | no |
| One single physical fact for all of the above | yes | no | no | no | no | no |

**Table XV.bis-5. The No-Now diagnosis in the words of its authors (supporting prior art).**

| Author | Statement | Source |
|---|---|---|
| Einstein (1905) | "we cannot attach any absolute signification to the concept of simultaneity" | [152], §2 |
| Weyl (1949) | "The objective world simply is, it does not happen." | [148], p. 116 |
| Einstein, reported by Carnap (1963) | the experience of the now "does not and cannot occur within physics," accepted with "painful but inevitable resignation" | [150], p. 37 |
| Gödel (1949) | if simultaneity is relative, "reality cannot be split up into such layers" | [149] |
| Eddington (1928) | "there is no signboard to indicate that it is a one-way street" | [134], pp. 68–69 |
| Mermin (2014) | "physics seems to have nothing whatever to say about the local Now at a single event" | [142] |
| Rovelli (2017) | "A present that is common throughout the whole universe does not exist." | [138] |
| Davies (2006) | "Nothing in known physics corresponds to the passage of time" | [139] |

The McGucken Principle dx₄/dt = ic answers every criterion of Table XV.bis-1 and is the one entry in Table XV.bis-4 that derives general relativity, quantum mechanics, and thermodynamics as theorem chains from the same fact that resolves the paradox: the advancing local now is the present extent of $x_4$, the absence of a universal now is the path-dependence of $X_4 = ic\,\tau$, the direction of time is the sign $+ic$, and the strict increase of entropy is the growth of the McGucken Sphere.

---

## XV.ter The McGucken Principle dx₄/dt = ic Reading of Position–Energy Complementarity: The Single Energy Quantum Cloaks the Expanding McGucken Sphere that the Position Ensemble Reveals

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality. The Principle predicts that a measurement of **energy** and a measurement of **position** are two readings of this one expanding object: energy reads the $x_4$-oscillation, the generator of $x_4$-translations at the Compton frequency $\nu_C = mc^2/h$ (ordinary frequency; angular $\omega_C = 2\pi\nu_C = mc^2/\hbar$); position reads the spatial cross-section of the McGucken Sphere, the Born density $|\psi(\mathbf{x})|^2$ diluting as $1/4\pi r^2$. These two readings are Fourier conjugates, and the uncertainty relation $\Delta x\,\Delta p \ge \hbar/2$ is a theorem of exactly that conjugacy between the generator of $x_4$-translations and the spatial position basis ([155], with the energy–time form in its corollary). This section states what the McGucken dx₄/dt = ic framework reads off each measurement, separates that reading from the established prior art on photon localization and number–phase complementarity, and states the result as a proposition.

### XV.ter.1 Prior art: the photon has sharp energy and no position

The asymmetry the reading requires — energy sharp, position not even an observable — is a proven feature of the photon in relativistic quantum theory. Newton and Wigner (1949) constructed localized states for massive and spinless systems and found the construction fails for the photon; in Ojima and Saigo's characterization of that result (verified-read, [157]), "any position operator cannot be defined for a massless free particle with a non-zero finite spin" ([156]; [157]). Working in Wightman's localizability framework, Ojima and Saigo state as their Corollary 2 that "a free photon is not localizable," noting that "in the massless cases … no localized states … are found to exist" (verified-read, [157]). A photon's energy $E = h\nu$ is a sharp observable; its position is not an observable at all. A single detection therefore records an absorption event at the detector, not the reading of a pre-existing position, because there is no photon position observable to read. The spatial distribution — the expanding McGucken Sphere — exists as the statistics of many such detection events, not as a property carried by one photon between emission and absorption.

### XV.ter.2 Prior art: number–phase (energy–phase) value-complementarity

A definite photon number is a definite count of energy quanta $E = h\nu$, and it is maximally spread in the complementary phase variable. In the operational treatment of number and phase by Busch, Lahti, Pellonpää, and Ylinen (web-digest, [158]), the canonical phase observable carries the density $M(\theta) = \frac{1}{2\pi}\sum_{n,m} e^{i(n-m)\theta}\,|n\rangle\langle m|$; a number state $\rho = |k\rangle\langle k|$ then gives the uniform phase density $\mathrm{Tr}[\rho\,M(\theta)] = 1/2\pi$ on $[0,2\pi)$ (direct computation from that density). The tradition runs from Dirac (1927, [159]) through Susskind and Glogower (1964, [160]) to Pegg and Barnett (1989, [161]), and is background knowledge in quantum optics. Because the number–phase pair admits no self-adjoint phase operator conjugate to number, the relation is stated here as value-complementarity — a state sharp in energy quanta is flat in phase — and not as a clean self-adjoint uncertainty relation, with that pair shown to be noncoexistent observables ([158]). A sharp-energy photon is delocalized in the phase that organizes the spatial wavefront; sharpening the spatial reading spreads the energy reading, and the reverse.

### XV.ter.3 The McGucken Principle dx₄/dt = ic reading

The McGucken dx₄/dt = ic framework names the one physical object that carries both readings — the expanding McGucken Sphere, the $dx_4/dt = ic$ wavefront — and specifies how each measurement reads it. Energy reads the $x_4$-oscillation: the quantum of energy is the quantum of $x_4$-advance, and the generator of $x_4$-translations is Fourier-conjugate to the spatial position basis, which is the content of the uncertainty derivation ([155]). Position reads the spatial cross-section: a landing drawn from the Born density $|\psi(\mathbf{x})|^2$, the cross-section of the McGucken Sphere at the detection event, diluting as $1/4\pi r^2$ with the growth of the Sphere.

A single energy-quantum detection is the quantized reading that conceals the Sphere. Theorem 28.13 of §38b ([154], Quantized Collapse Conceals the Sphere), together with the McGucken Cloaking Theorem (Theorem 39 of [154]), gives that one click returns a definite, unitary reading and hides the Sphere's spatial nonlocality behind the single quantum of action. The ensemble of position detections is the reading that reveals the Sphere. Theorem 28.12 of §38b ([154], Single-Photon Opacity and Ensemble Transparency) gives that the accumulated landings reconstruct the Sphere as the $1/4\pi r^2$ Born dilution. The action $h$ — the quantity the Sphere's wavelength sets, carried in the Principle itself — does both tasks at once: it is the Fourier-conjugacy constant that fixes $\hbar/2$ in $\Delta x\,\Delta p$ ([155]), and it is the cloaking quantum, the minimal definite energy reading, which is for that reason maximally indefinite in position. Energy quantization is what makes a single measurement return one sharp click rather than the whole Sphere; the Sphere is cloaked by the very discreteness of $h$ and is recovered only in the many-click position ensemble.

### XV.ter.4 The McGucken Invariance ties the two measurements into one quantity

The McGucken Invariance makes the position–energy tie a single measurable quantity rather than a pair of separate readings. For source events of intrinsic frequency $f$ and intensity $I$ received by an observer with arrival-time interval $\tau$, Doppler frequency $f'$, and received intensity $I'$, the McGucken Invariance $\mathcal{M}$ (Theorem 41 of [154]) is

$$\mathcal{M} \equiv \frac{\tau\,(f')^{2}}{(I')^{1/4}} = L\gamma\,\frac{f^{2}}{c\,I^{1/4}},$$

and this quantity takes the same value for every inertial observer. The three factors are precisely a timing/position reading ($\tau$, the arrival-time interval that locates the event), an energy reading ($f'$, with $E = hf'$), and a photon-flux reading ($I'$). The McGucken Invariance thus binds the position/timing measurement and the energy measurement of the same expanding McGucken Sphere into one Lorentz-covariant number, which is the quantitative form of the statement that the two measurements read one object.

### XV.ter.5 The result, and the division of prior art from the McGucken contribution

**Proposition XV.ter.1 (position–energy reading).** In the McGucken dx₄/dt = ic framework, position and energy are the spatial-cross-section reading and the $x_4$-oscillation reading of one expanding McGucken Sphere. A single energy-quantum detection returns a definite, unitary reading of the $x_4$-oscillation and conceals the Sphere's spatial nonlocality; the ensemble of position detections reconstructs the Sphere as the $1/4\pi r^2$ Born density. The action $h$ is at once the Fourier-conjugacy constant of $\Delta x\,\Delta p \ge \hbar/2$ and the cloaking quantum, and the McGucken Invariance $\mathcal{M} = \tau(f')^{2}/(I')^{1/4}$ is the single Lorentz-covariant quantity that ties the two measurements together.

*Proof.* Energy is the $x_4$-oscillation reading and position is the spatial-cross-section reading by the construction of §XV.ter.3, in which the generator of $x_4$-translations is Fourier-conjugate to the spatial position basis; the uncertainty bound $\Delta x\,\Delta p \ge \hbar/2$ for that conjugate pair is Theorem of [155]. That one energy-quantum detection returns a definite unitary reading and conceals the Sphere is Theorem 28.13 and the Cloaking Theorem 39 of [154]; that the ensemble of position detections reconstructs the Sphere as the $1/4\pi r^2$ Born density is Theorem 28.12 of [154]. The non-existence of a photon position observable (§XV.ter.1, [156]; [157]) makes the single click an absorption event rather than a position reading, so the spatial object is necessarily the ensemble construct, consistent with the two theorems. The constant $h$ appears in the conjugacy bound as $\hbar/2$ ([155]) and is the single quantum of action whose discreteness yields one click per detection, so it serves both roles. That $\mathcal{M} = \tau(f')^{2}/(I')^{1/4}$ is observer-independent and composed of a timing/position factor $\tau$, an energy factor $f'$, and a flux factor $I'$ is Theorem 41 of [154]. Each clause is thus a cited theorem or the construction of §XV.ter.3, and the conjunction is the Proposition. ∎

**What is prior art and what is the McGucken contribution.** The photon-localization theorems (no position operator for a massless particle of non-zero spin; Newton–Wigner, [156]; Wightman localizability, Ojima–Saigo, [157]) and number–phase value-complementarity ([158]–[161]) are the established prior art: together they fix that a photon's energy is sharp while its position is not. What the McGucken dx₄/dt = ic framework adds is the single physical object whose one-click energy reading conceals it and whose many-click position reading reveals it — the one expanding $dx_4/dt = ic$ Sphere — the identification of $h$ as simultaneously the Fourier-conjugacy constant and the cloaking quantum, and the McGucken Invariance $\mathcal{M}$ as the one Lorentz-covariant quantity tying the energy and position/timing measurements together.

---

## XVI. Conclusion

### XVI.1 What this paper has established

This paper has established that the measurement problem of quantum mechanics — the central foundational problem of quantum theory for ninety years — admits a complete resolution as a chain of formal theorems descending from the single geometric principle dx₄/dt = ic, and that the same chain of theorems extends naturally to dissolve the black hole information paradox at the cosmological scale. The resolution proceeds through twenty-two Propositions:

* **Proposition III.1** derives the Born rule P = |ψ|² as a forced geometric consequence of the squared-amplitude structure of McGucken-wavefront cross-sections, with the three-piece breakdown (i) complex character of ψ from i as perpendicularity marker, (ii) quadratic exponent forced by elimination of alternatives, (iii) SO(3) Haar-measure shape forced by spherical symmetry. *The McGucken dx₄/dt = ic framework is the only quantum framework that derives the Born rule from a single foundational principle.*

* **Proposition IV.1** establishes that the superposition principle (SP) is itself a Grade-1 theorem of dx₄/dt = ic, with linear addition of complex amplitudes forced as the unique geometric overlap operation respecting SO(3) Haar-measure, Lorentz-covariance, linearity, and Born-rule compatibility. The Hilbert-space linearity of postulate (Q1) is a derived structural feature, not a foundational postulate. *The McGucken dx₄/dt = ic framework is the only quantum framework that derives the superposition principle itself from a deeper physical mechanism.*

* **Proposition V.1** establishes that the apparent collapse R is the 3D spatial cross-section reading of an x₄-extended state, with no separate (R) postulate required.

* **Proposition VI.1** establishes that the irreversibility of measurement is the same x₄-monotonicity that grounds the second law of thermodynamics, requiring no separate stochastic dynamics.

* **Proposition VII.1** establishes that the preferred basis is selected by environmental Compton-frequency decoherence, with the cut between quantum and classical specified by a concrete physical mechanism rather than left arbitrary.

* **Proposition VIII.1** establishes that quantum nonlocality is the geometric consequence of x₄-mediated correlation through the six-sense null-surface identity of the McGucken Sphere, with the First Law of Nonlocality (all nonlocality begins in locality) supplying the structural account.

* **Proposition IX.1** establishes that the absence of a separate (R) law is itself a theorem rather than an interpretive choice, with the apparent (R) phenomenon reduced to the 3D-projection reading of unitary x₄-evolution.

* **Proposition X.1** establishes that information is never destroyed in the McGucken dx₄/dt = ic framework, as a Grade-1 theorem of x₄'s smoothness and Lorentz-covariance. *The McGucken dx₄/dt = ic framework is the only known framework in which information preservation is a derived theorem rather than a postulate.*

* **Proposition X.2** establishes that unitarity itself is derived from x₄'s smoothness via the chain smoothness → Hermiticity of Ĥ → unitarity of U → information preservation, with no independent axiomatic content. The unitarity of quantum-mechanical evolution is no longer foundational; it is a theorem of dx₄/dt = ic.

* **Proposition X.3** establishes that the Page curve is forced by the redistribution of x₄-coincidences from interior-exterior pairs (during the first half of black-hole evaporation) to exterior-exterior correlations (during the second half), with the Page-time maximum at S_BH(0)/2 emerging as a direct geometric consequence.

* **Proposition X.4** establishes that the measurement problem and the black hole information paradox are the same problem at different scales, both arising from the observer's restricted access to a four-dimensional state and both resolved by the same x₄-coincidence mechanism. *This unification of two of the central foundational problems of physics is the deepest structural identification the framework accomplishes.*

* **Proposition X.5** establishes that the McGucken dx₄/dt = ic framework is the only known framework that derives unitarity itself rather than postulating it. All seven interpretive programmes and all four major information-paradox resolutions take unitarity (or a structure that implies it) as foundational at some level.

* **Proposition XII.1** (Huygens' principle from x₄-spherical expansion) establishes that Huygens' principle is a theorem of dx₄/dt = ic, with the McGucken Sphere Σ₊(p₀) of radius c(t − t₀) identified geometrically with the forward light cone of p₀ and structurally with Huygens' secondary wavelet.

* **Proposition XII.2** (Iterated Huygens generates all paths) establishes that the Feynman sum over paths is geometrically the sum over chains of McGucken Spheres, with the standard density argument supplying the continuum limit.

* **Proposition XII.3** (Accumulated x₄-phase as the Feynman weight) establishes that the phase exp(iS/ℏ) is the accumulated x₄-advance along each path, with i the perpendicularity marker of x₄ and ℏ the quantum of x₄'s oscillation; the non-relativistic limit of the Compton-frequency phase mc²γ⁻¹ε/ℏ reproduces the Lagrangian phase (i/ℏ)L_classical ε.

* **Proposition XII.4** (Feynman path integral as continuum limit) establishes that the Feynman path integral is a theorem of dx₄/dt = ic, with the integration measure 𝒟x(t) the geometric extent of the McGucken Sphere's expanding wavefront and the phase exp(iS/ℏ) the accumulated x₄-advance. *The McGucken dx₄/dt = ic framework is the only quantum framework in which the Feynman path integral is derived rather than postulated.* The geometric reading — that x₄'s expansion represents an expanding nonlocality, every point on that nonlocality is the photon's path because the photon's position is always on the expanding surface of nonlocality, and to observers in 3D this appears as the photon following every single possible radius of the expanding sphere — supplies the physical content that Feynman's 1948 formulation has lacked for nearly eighty years.

* **Proposition XIII.1** establishes that the Hilbert-space framework itself — its complex scalar field, vector-space structure, inner-product structure, and separability — is forced by dx₄/dt = ic together with Propositions III.1 and IV.1, with no independent axiomatic content. *The McGucken dx₄/dt = ic framework is the only quantum framework in which the Hilbert space is derived rather than postulated.*

* **Proposition XIII.2** establishes that the specific Hilbert space for any given physical system — L²(ℝ³) for a spinless particle, ℂ² ⊗ L²(ℝ³) for a spin-½ particle, Fock space for a quantum field — is forced by the geometric structure of the McGucken-Sphere wavefront for that system, dissolving the textbook "which Hilbert space?" question.

* **Proposition XIII.3** establishes that the Hilbert-space, path-integral, C\*-algebraic, and categorical formulations of quantum mechanics are equivalent representations of the dual-channel content of dx₄/dt = ic, with no foundational hierarchy among them. The Hilbert space is one model among several, naturally suited for the algebraic-symmetry channel (Channel A); the path-integral kernel is naturally suited for the geometric-propagation channel (Channel B).

* **Proposition XIII.4** establishes that the Hilbert-space inner product, the complex conjugation in the first slot, and the orthogonality structure are theorems of dx₄/dt = ic, descending through the McGucken Space ℳ_G hierarchy. The sesquilinear form is forced by three structural facts — the SO(3) Haar measure on x₄'s expansion, the U(1) phase symmetry inherited from the perpendicularity marker i, and the conservation of total probability — while the orthogonality–distinguishability link is forced by the cross-section reading of Proposition V.1. *The McGucken dx₄/dt = ic framework is the only quantum framework in which the inner-product apparatus and the orthogonality–distinguishability link are derived rather than postulated.* (Wave-particle duality is now established in §XIII.16 as the dual-channel reading of x₄'s advance.)

* **Proposition XIII.5** establishes that the principal quantum operators — the Hamiltonian Ĥ = iℏ∂_t, the momentum operators p̂_μ = −iℏ∂_μ, the quantum McGucken operator M̂ = iℏD_M = Ĥ − icp̂₄, the Schrödinger operator iℏ∂_t − Ĥ, the canonical commutator [q̂, p̂] = iℏ, the Lorentzian wave operator □_M = ∇² − c⁻²∂_t², the Dirac operator 𝒟_M = iγ^μ∂_μ − m, and the gauge-covariant McGucken derivative D_M^A = ∇_t + ic∇_{x₄} — are all theorems of dx₄/dt = ic via the source-operator D_M, with no independent axiomatic content. *The McGucken dx₄/dt = ic framework is the only quantum framework in which the principal quantum operators are derived rather than postulated.*

* **Proposition XIII.6** establishes the categorical impossibility of a separate measurement-collapse mechanism in the McGucken dx₄/dt = ic framework. Any putative dynamical mechanism R for collapse must be either (a) a new space (ruled out by the universal derivability principle of [12]), (b) a new operator (ruled out by the universal operator-derivability principle of [13]), or (c) a new principle (ruled out by the inverse derivability of the space-operator co-generation theorem). The measurement problem cannot be formulated within the McGucken dx₄/dt = ic framework's category structure, because the categorical separation between system, apparatus, observer, and dynamics that the standard problem requires is dissolved at the source by the co-generation of space and operator. *This is the deepest structural fact of the McGucken dx₄/dt = ic framework: not that it solves the measurement problem better than other interpretations, but that the problem itself does not arise within its categorical structure.*

The complete structural reduction places all six postulates Q1–Q6 of the standard Dirac–von Neumann system, the unitarity foundation of quantum mechanics, and the information-preservation commitment of quantum gravity all in the theorem column. What remains in the postulate column is exactly one geometric principle: dx₄/dt = ic.

### XVI.2 Why this is unique

§XIV has established that the McGucken dx₄/dt = ic framework is the *only* quantum framework that satisfies all three structural criteria — derivation of the Born rule from a single underlying principle, resolution of the preferred-basis problem from a specific physical mechanism, and geometric account of nonlocality consistent with relativistic causality. The seven major interpretive programmes — Copenhagen, Many-Worlds, Bohmian mechanics, GRW, decoherence-plus-environmental-selection, Relational Quantum Mechanics, QBism — each fail at least one criterion, and most fail multiple criteria.

The structural reason is the dual-channel content of dx₄/dt = ic: Channel A (algebraic-symmetry) supplies the SO(3) Haar measure that forces the squared-amplitude form of Born; Channel B (geometric-propagation) supplies the McGucken Sphere structure that forces the six-sense null-surface identity. No single-channel framework can supply both. The McGucken Principle is the unique foundational principle whose statement contains both contents simultaneously, and its uniqueness in resolving the measurement problem is a direct consequence.

The deepest structural reason — established formally in §XIII.10 (the space-operator co-generation theorem) — is that the McGucken Principle generates the McGucken Space ℳ_G and the McGucken Operator D_M as a single source space-operator pair: dx₄/dt = ic ⟹ (ℳ_G, D_M). The pair has full inverse derivability, so that space, operator, and principle are not three independent foundational structures but three readings of one structural fact. No prior framework — Hamilton, Heaviside, Noether, Dirac (1928, 1933), Wick, Newton-Wigner, Wheeler-DeWitt, geometric quantization, or Connes spectral triples — has a co-generation theorem. Each captured one or two of the three components but missed at least one (§XIII.13). The McGucken dx₄/dt = ic framework is the only known framework that operates at the categorical level of source-pair generation, and the co-generation theorem is the formal expression of that fact. By Proposition XIII.6, this categorical structure makes a separate measurement-collapse mechanism impossible: there is no foundational layer at which such a mechanism could live. The dissolution of the measurement problem is therefore not a contingent advantage of the framework but a categorical feature of it.

### XVI.3 What this dissolves

The structural achievement is a *dissolution* of the measurement problem rather than a resolution. The standard "(U) + (R)" axiomatic structure is replaced by "(U) + dx₄/dt = ic," with (R) emerging as a derived appearance. The five sub-problems of the standard framework — probability (P1), collapse (P2), preferred basis (P3), irreversibility (P4), and nonlocality (P5) — are each addressed as a theorem of one geometric principle. There is nothing left to interpret: the Born rule has a derivation, the apparent collapse has a structural account, the irreversibility has a thermodynamic origin, the preferred basis has a physical mechanism, and nonlocality has a geometric mechanism. The measurement problem, ninety years after its formulation, becomes a chapter in the consequences of x₄'s spherical expansion at the velocity of light. More precisely, the measurement problem is *categorically* dissolved: by the space-operator co-generation theorem of §XIII.10, the four standard categories of system, apparatus, observer, and dynamics that the problem requires are projections of one source-pair (ℳ_G, D_M), and the measurement event is the geometric self-intersection of that source-pair with itself, viewed through the projection onto the observer's spatial slice. There are no four things to combine. There is one thing — the source-pair generated by dx₄/dt = ic — and the measurement event is one of its readings.

### XVI.4 What this gains for the broader programme

Within the broader Light Time Dimension Theory programme [30, 6, 28, 31, 9, 5, 4, 7, 8, 2, 27, 29, 120], the resolution of the measurement problem joins the derivations of special relativity [30], general relativity [3], the Schrödinger and Dirac equations [6], the Standard Model Lagrangians [121], the cosmological constant [51], the holographic principle and AdS/CFT [68], the Susskind black-hole programme [28], the Bekenstein–Hawking results [122, 123], the Wick rotation [31], the second law of thermodynamics [7, 8], the Born rule [5], the canonical commutation relation [77], the Compton-coupling diffusion signature [4], baryogenesis [124], the values of the fundamental constants c and ℏ [76], and dozens of other results — each derived as a theorem of dx₄/dt = ic.

The cumulative case is that *physics*, in the literal Greek sense of φυσική, "of nature," has a single foundational principle: the fourth dimension is expanding, spherically symmetrically, at the velocity of light. Every other major principle of physics — special relativity, general relativity, quantum mechanics, the Born rule, the Schrödinger equation, the Dirac equation, the Standard Model, the second law, holography, complementarity — follows as a theorem. Wheeler's 1983 self-excited-circuit diagram (Fig. 22.13 of *Law Without Law*) is, in this light, the heuristic image of the space-operator co-generation theorem: the U-curve is the cosmological worldline along which $x_4$ advances; the eye and the tip are configurations in $\mathcal{M}_G$; the dashed line is x₄-coincidence supplied by the First Law of Nonlocality; and observer-participancy is the cross-section reading of the four-dimensional state. The "law without law" Wheeler reached for in 1983 is, in 2026, the single source-law $dx_4/dt = ic$. The categorical claim that observer and observed cannot be separated at the foundational level — articulated by Bohr in 1934, by Heisenberg in 1955–1958, by Schrödinger in 1935 and 1958, by Wigner in 1961, by von Neumann in 1932, by Bohm in 1980, and by Wheeler in 1979 and 1983 — is, in 2026, a theorem of $dx_4/dt = ic$ via the co-generation of $\mathcal{M}_G$ and $D_M$. The greats had the right intuition. The McGucken dx₄/dt = ic framework supplies the math.

The measurement problem and the black hole information paradox have been the two central conceptual obstacles to that unification. With their joint resolution as Propositions III.1 through IX.1, X.1 through X.5, XII.1 through XII.4, and XIII.1 through XIII.6 of the present paper, both obstacles are removed.

### XVI.5 Master comparison table: every comparison consolidated

The master comparison table reproduced below is the consolidated summary of every structural comparison between the McGucken dx₄/dt = ic framework and the seven major prior interpretive programmes (Copenhagen, Many-Worlds, Bohmian, GRW, Decoherence + einselection, RQM, QBism) developed across the present paper. The table is organized into eight thematic sections — foundational primitives, mathematical structure, the wave function, measurement and collapse, canonical thought experiments, information and dynamics, categorical structure, and foundational achievement — with each row representing a comparison that has been established formally somewhere in the body of the paper. Specific Proposition and Theorem labels in the McGucken column identify the source theorem for each entry.

The reader is invited to read the table not as a tabular display of opinions but as a catalogue of structural results: every cell in the McGucken column is a theorem with a derivation; every cell in every other column is either a postulate, an open problem, or an unexplained feature accepted as primitive structural data. The categorical asymmetry is total. The McGucken dx₄/dt = ic framework derives where the seven prior programmes postulate, dissolves where they patch, and explains where they leave brute facts.

| Property | **McGucken** | Copenhagen | Many-Worlds | Bohmian | GRW | Decoherence + einselection | RQM | QBism |
|---|---|---|---|---|---|---|---|---|
| **A. Foundational primitives** | | | | | | | | |
| Number of foundational postulates | **one: $dx_4/dt = ic$** | $\geq 6$ + $(R)$ + interpretive choice | $\geq 6$ + branching | $\geq 6$ + hidden variables | $\geq 6$ + stochastic params | $\geq 6$ + system-environment | $\geq 6$ + relational | $\geq 6$ + agent |
| K-complexity bit-budget | **$\sim 10^2$ bits** | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits | $\sim 10^4$ bits |
| Primitive law | **$dx_4/dt = ic$ (physical-geometric)** | none specified | none specified | none specified | none specified | none specified | none specified | none specified |
| Physical content of primitive | **$x_4$ expands at $c$, spherically, with $i$ as perpendicularity marker** | — | — | — | — | — | — | — |
| Status of mathematical formalism | **derived theorems** | postulated | postulated | postulated + augmented | postulated + modified | postulated | postulated | postulated |
| **B. Mathematical structure** | | | | | | | | |
| Hilbert space $\mathcal{H}$ | **theorem (Prop. XIII.1)** | postulated | postulated | postulated + config space | postulated | postulated | postulated | postulated |
| Inner product $\langle\psi\|\phi\rangle$ | **theorem (Prop. XIII.4)** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Linearity / superposition (SP) | **theorem (Prop. IV.1)** | postulated | postulated | postulated | modified by hand | postulated | postulated | postulated |
| Unitarity of $U$ | **theorem (Prop. X.2)** | postulated | postulated | postulated | violated by collapse terms | postulated | postulated | postulated |
| Quantum operators $(\hat{H}, \hat{p}, [\hat{q},\hat{p}])$ | **theorem (Prop. XIII.5)** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Schrödinger equation | **theorem (Prop. XIII.5)** | postulated | postulated | postulated | modified by hand | postulated | postulated | postulated |
| Path integral $\int \mathcal{D}x\, e^{iS/\hbar}$ | **theorem (Prop. XII.1–XII.4)** | postulated | postulated | not used | postulated | postulated | postulated | postulated |
| Lorentzian wave operator $\square$ | **theorem (Theorem XIII.F)** | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate | from spacetime postulate |
| Wick rotation | **theorem (Theorem XIII.E)** | analytic prescription | analytic prescription | not addressed | analytic prescription | analytic prescription | not addressed | not addressed |
| **C. The wave function $\psi$** | | | | | | | | |
| Is $\psi$ postulated or derived? | **derived from $dx_4/dt = ic$** | postulated | postulated | postulated + hidden vars | postulated + stochastic | postulated | postulated | postulated |
| Ontological status of $\psi$ | **ontic, geometric, 4D wavefront amplitude** | epistemic / instrumentalist | ontic (universal) | ontic (auxiliary to particles) | ontic | ambiguous | relationally ontic | epistemic (Bayesian) |
| Why is $\psi$ complex? | **theorem: $i$ is perpendicularity marker of $x_4$** | unexplained | unexplained | unexplained | unexplained | unexplained | unexplained | unexplained |
| Why is probability $\|\psi\|^2$? | **theorem: SO(3) Haar measure on $\Sigma_M$ cross-section (Prop. III.1)** | postulated | derived (circular: assumes equiprobable branches) | postulated (quantum equilibrium) | postulated | postulated | postulated | postulated (personal Bayesian) |
| Dimensionality of $\psi$ | **4D on $\mathcal{M}_G$; 3D $\psi(\mathbf{x},t)$ is cross-section at $x_4 = ict$** | 3N-dim config space (postulated) | 3N-dim config space (postulated, real) | 3N-dim config space (postulated, real) | 3N-dim config space (postulated, real) | 3N-dim config space (postulated) | 3N-dim relational | 3N-dim epistemic |
| Multi-particle entanglement structure | **theorem: joint $x_4$-coincidence on common McGucken Sphere (Prop. VIII.1)** | postulated tensor-product | postulated universal-$\psi$ branching | postulated nonlocal guidance | postulated joint stochastic | postulated joint Hamiltonian | postulated relational | postulated joint Bayesian |
| Configuration space ontology | **derivative space (N copies of $\mathcal{M}_G$ joined by McGucken Sphere)** | primitive | primitive | primitive | primitive | primitive | primitive | primitive |
| **D. Measurement and collapse** | | | | | | | | |
| Born rule $P = \|\psi\|^2$ | **theorem (Prop. III.1)** | postulated | postulated (or via decision theory; circular) | postulated (quantum equilibrium) | postulated (with stochastic params) | postulated | postulated | postulated (personal Bayesian) |
| Apparent collapse $(R)$ | **theorem (Prop. V.1, no separate $(R)$)** | separate postulate | branching primitive | guidance equation | stochastic dynamics added | system-environment Hamiltonian added | relational primitive | agent primitive |
| Preferred basis | **theorem from Compton-frequency (Prop. VII.1)** | left arbitrary | left arbitrary | configuration-space | localization parameter | system-environment split (input) | relational | agent |
| Irreversibility of measurement | **theorem (Prop. VI.1)** | left unexplained | branching | trajectories | stochastic | environmental coupling | relational | agent |
| Quantum-classical cut | **continuous via Compton frequency (Prop. VII.1)** | arbitrary placement | no cut (branching) | hidden-variable/wavefunction split | stochastic-rate threshold | system-environment split (input) | relational | agent |
| **E. Canonical thought experiments** | | | | | | | | |
| Schrödinger's cat | **resolved: cat in definite state because $\omega_C \sim 10^{50}$ Hz forces decoherence below detection (§V.6.1); reductio *vindicated*** | superposition until observed | branching into alive+dead worlds | hidden variable picks outcome | stochastic localization | system-environment einselects | relational outcome | agent's Bayesian update |
| Wigner's friend | **dissolved: friend's definite outcome and Wigner's superposition are projections of one $x_4$-extended state onto different slices, with $x_4$-coincidence guaranteeing consistency (§V.6.2)** | paradox / consciousness role | each branch is self-consistent | hidden variable resolves | stochastic dynamics resolves | environmental decoherence | relational, no contradiction | agent-relative facts |
| Bell-inequality violation / nonlocality | **theorem from $x_4$-coincidence (Prop. VIII.1, First Law of Nonlocality)** | acausal | acausal | non-local guidance | local stochastic | acausal | relational | epistemic |
| **F. Information and dynamics** | | | | | | | | |
| Information preservation | **theorem (Prop. X.1)** | imposed | imposed | imposed | violated | imposed | imposed | epistemic |
| Black hole information paradox | **dissolved (Prop. X.4, X.5)** | open | open | open | violates unitarity | open | open | open |
| Page curve | **theorem (Prop. X.3)** | imposed by hand | imposed | imposed | violated | imposed | not addressed | not addressed |
| Origin of dynamics ($\partial_t$) | **theorem: $D_M$'s flow restricted to $\Sigma_t$ (Prop. XIII.5)** | postulated | postulated | postulated | postulated + stochastic | postulated | postulated | postulated |
| **G. Categorical structure (per Wheeler / co-generation)** | | | | | | | | |
| Universe as one object | **yes (one $x_4$-extended state; co-generation theorem XIII.I)** | not formally | partly (universal $\psi$) | no (particles + $\psi$) | no | no | no (relational) | no (agent-relative) |
| Observer co-derived with observed | **yes (both configurations in $\mathcal{M}_G$, Prop. XIII.6)** | no (cut postulated) | no (observers in branches) | no (observers separate) | no | no | partial (relational) | no (agent privileged) |
| Delayed-choice / participatory structure | **theorem from $x_4$-coincidence (Prop. VIII.1)** | acausal influence | branch selection | retrocausal pilot wave | stochastic | acausal | frame-dependent | agent's posterior |
| Space-operator co-generation (Sense 2) | **theorem (Theorem XIII.I)** | absent (independent inputs) | absent | absent | absent | absent | absent | absent |
| Space-operator categorical equivalence (Sense 1) | **recovered as descent image via $F_{\rm Spec}$ (Theorem XIII.G of [1])** | absent | absent | absent | absent | absent | absent | absent |
| **I. Fields and gauge structure** | | | | | | | | |
| Status of field operator $\hat{\phi}(x)$ | **derived: $D_M$-flow on Fock space (§V.bis.3)** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Origin of equations of motion (KG, Dirac, Maxwell, YM) | **theorem: 4 sectors of $\mathcal{L}_{\rm McG}$ forced [2]** | postulated separately | postulated separately | postulated separately | postulated separately | postulated separately | postulated separately | postulated separately |
| Origin of gauge group $U(1) \times SU(2) \times SU(3)$ | **theorem (settled for U(1); programmatic for SU(2), SU(3))** | postulated | postulated | postulated | postulated | postulated | postulated | postulated |
| Origin of microcausality / locality | **theorem: $x_4$-coincidence light-cone (Prop. VIII.1)** | axiom | axiom | axiom | axiom | axiom | axiom | axiom |
| Treatment of gravity | **structural: metric is constraint-projection feature; no graviton needed [3]** | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton | excluded or postulated graviton |
| Substrate-scale UV regulation | **structural: McGucken-Sphere granularity [1, Theorem H]** | renormalization required | renormalization required | renormalization required | renormalization required | renormalization required | renormalization required | renormalization required |
| GUT embedding required? | **no (gauge group exactly $G_{\rm SM}$; predicts no proton decay)** | open | open | open | open | open | open | open |
| **H. Foundational achievement** | | | | | | | | |
| Measurement problem | **categorically dissolved (Prop. XIII.6)** | open | open / branching | open / non-local | open / stochastic | open / einselection-circularity | open / relational | open / subjective |
| Quantum nonlocality vs. relativity | **reconciled via $x_4$-coincidence (Prop. VIII.1)** | tension | tension | tension | tension (stochastic locality) | tension | relational | epistemic |
| Why these mathematical structures? | **theorems of $dx_4/dt = ic$** | brute facts | brute facts | brute facts | brute facts | brute facts | brute facts | brute facts |
| Empirical falsifiability | **Compton-frequency signature [4]** | not directly distinguishing | not directly distinguishing | quantum-equilibrium tests | direct (collapse rates) | not directly distinguishing | not directly distinguishing | not directly distinguishing |


The master table is reproduced from the Abstract, where it serves as the orienting summary that opens the paper. Its reproduction here as the closing summary of the Conclusion is deliberate: the structural advantage of the McGucken dx₄/dt = ic framework over every prior interpretive programme is the same argument when the paper opens and when it closes, because the structural advantage is itself a categorical fact — established formally by the space-operator co-generation theorem (Theorem XIII.I), quantified by the two-orders-of-magnitude reduction in K-complexity, made concrete by the wave function being a derived geometric object rather than an interpretively-flexible postulate (§V.1), and applied directly to the canonical measurement-problem thought experiments via Schrödinger's cat and Wigner's friend (§V.6). The single row at the bottom of the table — *empirical falsifiability* — closes the loop: the framework predicts a specific Compton-frequency decoherence signature [4] that distinguishes it empirically from every prior programme, which means the framework is not merely a different mathematical formalism but a falsifiable physical theory.

The greats had the right intuition. The McGucken dx₄/dt = ic framework supplies the mathematics that makes the intuition a theorem. The measurement problem and the black hole information paradox dissolve simultaneously, as theorems of the same primitive physical-geometric law. The wave function is what $x_4$'s spherical expansion at velocity $c$ produces. The probability is the SO(3) Haar measure on the wavefront cross-section. The collapse is the spatial-slice projection at the observer's event. Born is a theorem. Linearity is a theorem. Hilbert space is a theorem. The Schrödinger equation is a theorem. The path integral is a theorem. Wick rotation is a theorem. Quantum nonlocality is a theorem. Information preservation is a theorem. The Page curve is a theorem. The standard categorical structure of quantum mechanics is dissolved at the source by the space-operator co-generation theorem (Theorem XIII.I), and the standard measurement problem cannot even be formulated within the McGucken dx₄/dt = ic framework's category structure (Proposition XIII.6), because the categorical separation it requires has been removed by the co-generation. Every entry in the master table above is a structural consequence of $dx_4/dt = ic$.

---

> *"Behind it all is surely an idea so simple, so beautiful, that when we grasp it — in a decade, a century, or a millennium — we will all say to each other, how could it have been otherwise?"*
> — John Archibald Wheeler

The idea is dx₄/dt = ic. The measurement problem is one of its theorems.

---

## References

[1] McGucken, E. (2026). Connes' Spectral Triple Geometry derived as Theorems of the McGucken Principle dx₄/dt = ic: McGucken Space, the McGucken–Dirac Spectral Triple, the Spectral Distance Theorem, the Spectral Action–Lagrangian Correspondence, and the Riemannian Reconstruction Theorem as Theorems of dx₄/dt = ic, with the Almost-Commutative Internal Algebra A_F as Empirical-Input Encoding. *Light Time Dimension Theory*, May 3, 2026. https://elliotmcguckenphysics.com/2026/05/03/connes-spectral-triple-geometry-derived-as-theorems-of-the-mcgucken-principle-dx%e2%82%84-dt-ic-mcgucken-space-the-mcgucken-dirac-spectral-triple-the-spectral-distance-theorem-the-spec/

[2] McGucken, E. (2026). The Unique McGucken Lagrangian ℒ_McG = ℒ_kin + ℒ_Dirac + ℒ_YM + ℒ_EH as Forced Theorem of dx₄/dt = ic Plus Eleven Minimal Consistency Conditions. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/23/the-unique-mcgucken-lagrangian-all-four-sectors-free-particle-kinetic-dirac-matter-yang-mills-gauge-einstein-hilbert-gravitational-forced-by-the-mcgucken-principle-dx%e2%82%84-2/

[3] McGucken, E. (2026). General Relativity Derived from the McGucken Principle dx₄/dt = ic: The Lorentzian Metric, the Einstein Field Equations, and the Schwarzschild Solution as Theorems. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/07/05/general-relativity-derived-from-the-mcgucken-principle-dx4-dtic-deriving-general-relativity-as-two-independent-theorem-chains-descending-from-dx4-dtic-along-both-the-geometric-and-algebraic-channel/

[4] McGucken, E. (2026). The Compton coupling and matter–x₄ interaction. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[5] McGucken, E. (2026). The Born rule as a theorem of dx₄/dt = ic: a structural derivation through the squared-amplitude geometry of McGucken-wavefront cross-sections. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[6] McGucken, E. (2026). Quantum mechanics derived from the McGucken Principle: a unique, simple, and complete derivation. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/26/quantum-mechanics-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-quantum-mechanics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-d/

[7] McGucken, E. (2026). The second law of thermodynamics and the arrows of time as theorems of dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/26/thermodynamics-derived-from-the-mcgucken-principle-a-unique-simple-and-complete-derivation-of-thermodynamics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx/

[8] McGucken, E. (2026). The McGucken Principle as a geometric resolution of the horizon, flatness, and homogeneity problems of cosmology. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[9] McGucken, E. (2026). The First Law of Nonlocality: all nonlocality begins in locality. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[10] McGucken, E. (2026). A derivation of Feynman's path integral from the McGucken Principle of the fourth expanding dimension dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/15/a-derivation-of-feynmans-path-integral-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/

[11] McGucken, E. (2026). Feynman diagrams as theorems of the McGucken Principle: propagators, vertices, loops, Wick contractions, and the Dyson expansion as iterated Huygens with interaction on the expanding fourth dimension. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/23/feynman-diagrams-as-theorems-of-the-mcgucken-principle-propagators-vertices-loops-wick-contractions-and-the-dyson-expansion-as-iterated-huygens-with-interaction-on-the-expanding-fourth-dimension/

[12] McGucken, E. (2026). The McGucken Space ℳ_G : The simplest, most complete, and most powerful source space in physics — a formal theory of how dx₄/dt = ic generates spacetime, metric structure, Hilbert space, phase space, spinor space, gauge-bundle space, Fock space, operator algebras, and more. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/29/the-mcgucken-space-%e2%84%b3g-the-source-space-that-generates-spacetime-hilbert-space-and-the-physical-arena-hierarchy/

[13] McGucken, E. (2026). The McGucken Operator $D_M$: The simplest, most complete, and most powerful source operator in physics — a formal theory of how dx₄/dt = ic co-generates space, dynamics, time evolution, Wick rotation, Lorentzian wave propagation, Schrödinger evolution, Dirac factorization, gauge covariance, commutator structure, and more. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/29/the-mcgucken-operator-dm-the-source-operator-that-co-generates-space-dynamics-and-the-operator-hierarchy/

[14] Manousakis, E. (2011). Biological observer-participation and Wheeler's 'law without law.' arXiv:1108.4860.

[15] McGucken, E. (2026). The McGucken-Bell directional modulation: angular signatures of x₄-mediated correlation in Bell-violation experiments. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[16] Dirac, P. A. M. (1958). *The Principles of Quantum Mechanics* (4th ed.). Oxford University Press.

[17] von Neumann, J. (1932). *Mathematische Grundlagen der Quantenmechanik*. Springer.

[18] Bell, J. S. (1990). Against "measurement". *Physics World*, 3(8), 33.

[19] Gleason, A. M. (1957). Measures on the closed subspaces of a Hilbert space. *Journal of Mathematics and Mechanics*, 6, 885.

[20] Deutsch, D. (1999). Quantum theory of probability and decisions. *Proceedings of the Royal Society A*, 455, 3129.

[21] Wallace, D. (2012). *The Emergent Multiverse: Quantum Theory According to the Everett Interpretation*. Oxford University Press.

[22] Zurek, W. H. (2005). Probabilities from entanglement, Born's rule from envariance. *Physical Review A*, 71, 052105.

[23] Hartle, J. B. (1968). Quantum mechanics of individual systems. *American Journal of Physics*, 36, 704–712.

[24] Bell, J. S. (1964). On the Einstein-Podolsky-Rosen paradox. *Physics*, 1, 195.

[25] Clauser, J. F., Horne, M. A., Shimony, A., & Holt, R. A. (1969). Proposed experiment to test local hidden-variable theories. *Physical Review Letters*, 23, 880.

[26] Tsirelson, B. S. (1980). Quantum generalizations of Bell's inequality. *Letters in Mathematical Physics*, 4, 93.

[27] McGucken, E. (2026). The deeper spacetime reality behind quantum mechanics: dual-channel content of dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[28] McGucken, E. (2026). Theorems of dx₄/dt = ic: how the McGucken Principle derives Leonard Susskind's six black hole programmes. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[29] McGucken, E. (2026). The Unique McGucken Lagrangian: All Four Sectors — Free-Particle Kinetic, Dirac Matter, Yang-Mills Gauge, Einstein-Hilbert Gravitational — Forced by the McGucken Principle dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/23/the-unique-mcgucken-lagrangian-all-four-sectors-free-particle-kinetic-dirac-matter-yang-mills-gauge-einstein-hilbert-gravitational-forced-by-the-mcgucken-principle-dx%e2%82%84-2/

[30] McGucken, E. (2026). The McGucken Principle and proof: the fourth dimension is expanding at the velocity of light, dx₄/dt = ic, as a foundational law of physics. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[31] McGucken, E. (2026). The Wick rotation as a theorem of dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[32] Davisson, C., & Germer, L. H. (1927). Diffraction of electrons by a crystal of nickel. *Physical Review*, 30, 705–740.

[33] Tonomura, A., Endo, J., Matsuda, T., Kawasaki, T., & Ezawa, H. (1989). Demonstration of single-electron buildup of an interference pattern. *American Journal of Physics*, 57, 117–120.

[34] Arndt, M., Nairz, O., Vos-Andreae, J., Keller, C., van der Zouw, G., & Zeilinger, A. (1999). Wave–particle duality of C₆₀ molecules. *Nature*, 401, 680–682.

[35] Fein, Y. Y., Geyer, P., Zwick, P., Kiałka, F., Pedalino, S., Mayor, M., Gerlich, S., & Arndt, M. (2019). Quantum superposition of molecules beyond 25 kDa. *Nature Physics*, 15, 1242–1245.

[36] Albert, D. Z. (2010). Probability in the Everett picture. In *Many Worlds? Everett, Quantum Theory, and Reality*, eds. Saunders et al., Oxford University Press.

[37] Saunders, S., Barrett, J., Kent, A., & Wallace, D. (Eds.) (2010). *Many Worlds? Everett, Quantum Theory, and Reality*. Oxford University Press.

[38] Dürr, D., Goldstein, S., & Zanghì, N. (1992). Quantum equilibrium and the origin of absolute uncertainty. *Journal of Statistical Physics*, 67, 843.

[39] Streater, R. F., & Wightman, A. S. (1964). *PCT, Spin and Statistics, and All That*. W. A. Benjamin.

[40] Schrödinger, E. (1935). Die gegenwärtige Situation in der Quantenmechanik. *Naturwissenschaften*, 23, 807–812; 823–828; 844–849. English translation by J. D. Trimmer, *Proceedings of the American Philosophical Society*, 124 (1980), 323–338.

[41] McGucken, E. (2026). A Derivation of Feynman's Path Integral from the McGucken Principle of the Fourth Expanding Dimension dx₄/dt = ic: How Huygens' Principle, Feynman's Many Paths, Brownian Motion, and Entropy's Increase All Emerge from a Single Geometric Postulate. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/10/14/a-derivation-of-feynmans-path-integral-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx%e2%82%84-dt-ic-how-huygens-principle-feynmans-many-paths-brownian-motion-and-entrop/

[42] Wigner, E. P. (1961). Remarks on the mind-body question. In I. J. Good (Ed.), *The Scientist Speculates: An Anthology of Partly-Baked Ideas* (pp. 284–302). London: Heinemann.

[43] Schrödinger, E. (1958). *Mind and Matter*. Cambridge University Press. (Tarner Lectures, Trinity College, Cambridge, 1956.) Reprinted as part of *What Is Life? with Mind and Matter and Autobiographical Sketches*, Cambridge University Press, 1992.

[44] McGucken, E. (2026). The McGucken Symmetry as the Father Symmetry of Physics: Lorentz, Poincaré, Noether, Wigner, Gauge U(1) × SU(2) × SU(3), Quantum-Unitary, CPT, Diffeomorphism, Supersymmetry, and the Standard String-Theoretic Dualities as Descent Theorems. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/28/the-mcgucken-symmetry-%f0%9d%90%9d%f0%9d%90%b1%f0%9d%9f%92-%f0%9d%90%9d%f0%9d%90%ad%f0%9d%90%a2%f0%9d%90%9c-the-father-symmetry-of-physics-completing-kleins-187/

[45] McGucken, E. (2026). Deriving the Hilbert Space and Born Rule from a Foundational Geometric, Physical Principle dx₄/dt = ic: Cogeneration of the Hilbert Space, the Born Rule, the Canonical Commutation Relation, the Uncertainty Principle, and the Schrödinger Equation. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/05/30/deriving-the-hilbert-space-and-born-rule-from-a-foundational-geometric-physical-principle-dx%e2%82%84-dt-ic-cogeneration-of-the-hilbert-space-the-born-rule-the-canonical-commutation-relation-th/

[46] McGucken, E. The Dirac Equation as Theorem of dx₄/dt = ic: Spin-½, the SU(2) Double Cover of SO(3), Charge Conjugation as x₄-Reversal, and Chirality Structure. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/19/the-geometric-origin-of-the-dirac-equation-spin-%c2%bd-the-su2-double-cover-and-the-matter-antimatter-structure-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic/

[47] McGucken, E. The Standard Model Gauge Group $U(1)_Y \times SU(2)_L \times SU(3)_c$ as Theorem of the McGucken Symmetry's Internal Action: Five Theorems and the No-GUT Prediction. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/05/16/the-dx%e2%82%84-dt-ic-derivation-of-the-standard-model-gauge-group-and-higgs-sector-g_sm-u1_y-x-su2_l-x-su3_c-with-the-higgs-as-field-theoretic-pointer-to-ic-as-theorems-of-the/

[48] Chamseddine, A. H., Connes, A., & Mukhanov, V. (2014). Quanta of geometry: noncommutative aspects. *Physical Review Letters*, 114(9), 091302.

[49] Haag, R. (1996). *Local Quantum Physics: Fields, Particles, Algebras* (2nd ed.). Springer-Verlag.

[50] McGucken, E. The Three-Generation Structure of Matter as a Source-Tuple Feature: An Open Research Direction in the McGucken Framework. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/19/the-ckm-complex-phase-and-the-jarlskog-invariant-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-compton-frequency-interference-the-kobayashi-maskawa-three-generation/

[51] McGucken, E. The Cosmological Constant Λ as Theorem of dx₄/dt = ic: McGucken Cosmology and the Resolution of the Vacuum-Energy Problem. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/15/the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic-as-the-resolution-of-the-vacuum-energy-problem-and-the-cosmological-constant/

[52] McGucken, E. Dark Matter as McGucken-Cosmological Geometric Effect: An Open Research Direction. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/15/dark-matter-as-geometric-mis-accounting-how-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic-generates-flat-rotation-curves-the-tully-fisher-relation-and-enhanced-gr/

[53] Aspect, A., Grangier, P., & Roger, G. (1982). Experimental realization of Einstein-Podolsky-Rosen-Bohm Gedankenexperiment: A new violation of Bell's inequalities. *Physical Review Letters*, 49, 91.

[54] Aspect, A. (2015). Closing the door on Einstein and Bohr's quantum debate. *Physics*, 8, 123.

[55] Hensen, B., et al. (2015). Loophole-free Bell inequality violation using electron spins separated by 1.3 kilometres. *Nature*, 526, 682.

[56] Giustina, M., et al. (2015). Significant-loophole-free test of Bell's theorem with entangled photons. *Physical Review Letters*, 115, 250401.

[57] Shalm, L. K., et al. (2015). Strong loophole-free test of local realism. *Physical Review Letters*, 115, 250402.

[58] Pan, J.-W., Bouwmeester, D., Weinfurter, H., & Zeilinger, A. (1998). Experimental entanglement swapping: Entangling photons that never interacted. *Physical Review Letters*, 80, 3891–3894.

[59] Hawking, S. W. (1974). Black hole explosions? *Nature*, 248, 30–31.

[60] Hawking, S. W. (1975). Particle creation by black holes. *Communications in Mathematical Physics*, 43, 199–220.

[61] Hawking, S. W. (1976). Breakdown of predictability in gravitational collapse. *Physical Review D*, 14, 2460–2473.

[62] Page, D. N. (1993). Information in black hole radiation. *Physical Review Letters*, 71, 3743–3746.

[63] Penington, G. (2020). Entanglement wedge reconstruction and the information paradox. *Journal of High Energy Physics*, 2020(9), 002. (arXiv:1905.08255.)

[64] Almheiri, A., Engelhardt, N., Marolf, D., & Maxfield, H. (2019). The entropy of bulk quantum fields and the entanglement wedge of an observer. *Journal of High Energy Physics*, 2019(12), 063. (arXiv:1905.08762.)

[65] Susskind, L., Thorlacius, L., & Uglum, J. (1993). The stretched horizon and black hole complementarity. *Physical Review D*, 48, 3743–3761.

[66] 't Hooft, G. (1985). On the quantum structure of a black hole. *Nuclear Physics B*, 256, 727–745.

[67] Maldacena, J. (1998). The large N limit of superconformal field theories and supergravity. *Advances in Theoretical and Mathematical Physics*, 2, 231–252. (arXiv:hep-th/9711200, 1997.)

[68] McGucken, E. (2026). The McGucken Principle as the physical foundation of holography and AdS/CFT. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[69] Hawking, S. W., Perry, M. J., & Strominger, A. (2016). Soft hair on black holes. *Physical Review Letters*, 116, 231301.

[70] Steinhauer, J. (2016). Observation of quantum Hawking radiation and its entanglement in an analogue black hole. *Nature Physics*, 12, 959–965.

[71] Wheeler, J. A. (1990). Information, physics, quantum: The search for links. In *Complexity, Entropy, and the Physics of Information*, ed. W. H. Zurek, Addison-Wesley.

[72] Kent, A. (2010). One world versus many: The inadequacy of Everettian accounts of evolution, probability, and scientific confirmation. In S. Saunders, J. Barrett, A. Kent, & D. Wallace (Eds.), *Many Worlds? Everett, Quantum Theory, and Reality*. Oxford University Press. (arXiv:0905.0624.)

[73] Valentini, A. (1991). Signal-locality, uncertainty, and the subquantum H-theorem. *Physics Letters A*, 156, 5.

[74] Valentini, A. (2001). Hidden variables, statistical mechanics and the early universe. In J. Bricmont et al. (Eds.), *Chance in Physics: Foundations and Perspectives* (pp. 165–181). Springer.

[75] Feynman, R. P. (1948). Space-time approach to non-relativistic quantum mechanics. *Reviews of Modern Physics*, 20, 367.

[76] McGucken, E. (2026). How the McGucken Principle of a fourth expanding dimension dx₄/dt = ic sets the constants c and ℏ. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[77] McGucken, E. (2026). The canonical commutation relation [q̂, p̂] = iℏ as a theorem of dx₄/dt = ic: dual-route derivation through the Hamiltonian and Lagrangian formulations. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[78] Hardy, L. (2001). Quantum theory from five reasonable axioms. arXiv:quant-ph/0101012.

[79] Masanes, L., & Müller, M. P. (2011). A derivation of quantum theory from physical requirements. *New Journal of Physics*, 13, 063001.

[80] Dirac, P. A. M. (1928). The quantum theory of the electron. *Proceedings of the Royal Society A*, 117, 610.

[81] Dirac, P. A. M. (1933). The Lagrangian in quantum mechanics. *Physikalische Zeitschrift der Sowjetunion*, 3, 64.

[82] DeWitt, B. S. (1967). Quantum theory of gravity. I. The canonical theory. *Physical Review*, 160, 1113.

[83] Wheeler, J. A. (1968). Superspace and the nature of quantum geometrodynamics. In *Battelle Rencontres*, ed. C. M. DeWitt and J. A. Wheeler.

[84] Connes, A. (1994). *Noncommutative Geometry*. Academic Press.

[85] Chamseddine, A. H., & Connes, A. (2008). The uncanny precision of the spectral action. *Communications in Mathematical Physics*, 293, 867–897.

[86] Connes, A. (2013). On the spectral characterization of manifolds. *Journal of Noncommutative Geometry*, 7(1), 1–82. (arXiv:0810.2088, 2008.)

[87] McGucken, E. (2026). The McGucken Source-Pair (𝓜_G, D_M) and the Three Structural Theorems: Mutual Containment, Reciprocal Generation, and Containment-Generation Equivalence. *Light Time Dimension Theory*. (Pair-paper foundation; cited as [19] in [MG-Connes].). https://elliotmcguckenphysics.com/2026/05/02/novel-reciprocal-generation-mcgucken-category-mcg-built-on-dx%e2%82%84-dt-ic-three-theorems-on-the-source-pair-%e2%84%b3_g-d_m-mutual-containment-reciprocal-generation-and-the-contai/

[88] McGucken, E. (2026). The McGucken Source-Tuple F_M = (Σ_M, 𝒢_M, 𝓜_G, D_M, 𝒮_M, 𝒜_M) and the Six-Object McGucken Category McG₆: Intrinsic Characterization Theorem. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/05/19/the-mcgucken-category-mcg%e2%82%86-as-the-foundational-structurally-complete-and-unique-category-for-the-positive-geometry-programme-penrose-twistor-space-the-positive-grassmannian-the-amplituhed/

[89] Wick, G. C. (1954). Properties of Bethe-Salpeter wave functions. *Physical Review*, 96, 1124.

[90] Kostant, B. (1970). Quantization and unitary representations. In *Lectures in Modern Analysis and Applications III*, Springer.

[91] Souriau, J.-M. (1970). *Structure des Systèmes Dynamiques*. Dunod.

[92] Newton, T. D., & Wigner, E. P. (1949). Localized states for elementary systems. *Reviews of Modern Physics*, 21, 400.

[93] Noether, E. (1918). Invariante Variationsprobleme. *Nachrichten der Königlichen Gesellschaft der Wissenschaften zu Göttingen, Mathematisch-Physikalische Klasse*, 235.

[94] Wheeler, J. A. (1983). Law without law. In *Quantum Theory and Measurement*, ed. J. A. Wheeler and W. H. Zurek, Princeton University Press, pp. 182–213.

[95] Fuchs, C. A. (2016). On participatory realism. arXiv:1601.04360.

[96] Stoica, O. C. (2013). The Tao of It and Bit. In *It from Bit or Bit from It?*, ed. A. Aguirre, B. Foster, Z. Merali, Springer (2015), pp. 51–64. arXiv:1311.0765.

[97] Penrose, R. (1989). *The Emperor's New Mind*. Oxford University Press.

[98] Kim, Y.-H., Yu, R., Kulik, S. P., Shih, Y., & Scully, M. O. (2000). Delayed 'choice' quantum eraser. *Physical Review Letters*, 84, 1.

[99] Manning, A. G., Khakimov, R. I., Dall, R. G., & Truscott, A. G. (2015). Wheeler's delayed-choice gedanken experiment with a single atom. *Nature Physics*, 11, 539–542.

[100] McGucken, E. (1999). Multiple Unit Artificial Retina Chipset to Aid the Visually Impaired and Enhanced CMOS Phototransistors, with appendix on Light Time Dimension Theory. PhD dissertation, University of North Carolina at Chapel Hill.

[101] McGucken, E. (2026). The McGucken Principle resolves the shortcomings of the Transactional Interpretation of quantum mechanics. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[102] Bohr, N. (1934). *Atomic Theory and the Description of Nature*. Cambridge University Press.

[103] Petersen, A. (1963). The philosophy of Niels Bohr. *Bulletin of the Atomic Scientists*, 19(7), 8–14.

[104] Bohr, N. (1958). *Atomic Physics and Human Knowledge*. John Wiley & Sons.

[105] Heisenberg, W. (1958). *Physics and Philosophy: The Revolution in Modern Science*. Harper & Row. (Gifford Lectures, University of St. Andrews, 1955–1956.)

[106] Heisenberg, W. (1955). *Das Naturbild der heutigen Physik*. Hamburg: Rowohlt. English translation: *The Physicist's Conception of Nature* (Pomerans, A. J., trans., 1958), Hutchinson.

[107] Schrödinger, E. (1935). Discussion of probability relations between separated systems. *Mathematical Proceedings of the Cambridge Philosophical Society*, 31(4), 555–563.

[108] Bohm, D. (1980). *Wholeness and the Implicate Order*. London: Routledge & Kegan Paul.

[109] Wheeler, J. A. (1979). Frontiers of time. In G. Toraldo di Francia (Ed.), *Problems in the Foundations of Physics, Proceedings of the International School of Physics 'Enrico Fermi', Course LXXII* (pp. 395–497). Amsterdam: North-Holland.

[110] Stone, M. H. (1936). The theory of representations for Boolean algebras. *Transactions of the American Mathematical Society*, 40(1), 37–111.

[111] Pontryagin, L. S. (1934). The theory of topological commutative groups. *Annals of Mathematics*, 35(2), 361–388.

[112] Gelfand, I. M., & Naimark, M. A. (1943). On the imbedding of normed rings into the ring of operators in Hilbert space. *Matematicheskii Sbornik*, 12(2), 197–217.

[113] Reyes, M. L. (2012). Obstructing extensions of the functor Spec to noncommutative rings. *Israel Journal of Mathematics*, 192(2), 667–698.

[114] Segal, I. E. (1947). Irreducible representations of operator algebras. *Bulletin of the American Mathematical Society*, 53(2), 73–88.

[115] Heisenberg, W. (1925). Über quantentheoretische Umdeutung kinematischer und mechanischer Beziehungen. *Zeitschrift für Physik*, 33(1), 879–893.

[116] Born, M., & Jordan, P. (1925). Zur Quantenmechanik. *Zeitschrift für Physik*, 34(1), 858–888.

[117] Born, M., Heisenberg, W., & Jordan, P. (1926). Zur Quantenmechanik II. *Zeitschrift für Physik*, 35(8–9), 557–615.

[118] McGucken, E. (2026). The McGucken Symmetry dx₄/dt = ic — The Father Symmetry of Physics — Completing Klein's 1872 Erlangen Programme. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/28/the-mcgucken-symmetry-%f0%9d%90%9d%f0%9d%90%b1%f0%9d%9f%92-%f0%9d%90%9d%f0%9d%90%ad%f0%9d%90%a2%f0%9d%90%9c-the-father-symmetry-of-physics-completing-kleins-187/

[119] Acharya, B., et al. (MoEDAL Collaboration) (2017). Search for magnetic monopoles with the MoEDAL forward trapping detector in 13 TeV proton–proton collisions at the LHC. *Physical Review Letters*, 118, 061801.

[120] McGucken, E. (2026). The McGucken Category McG₆ as the Foundational, Structurally Complete, and Unique Category for the Positive-Geometry Programme: Penrose Twistor Space, the Positive Grassmannian, the Amplituhedron, and Feynman Diagrams as Categorically-Equivalent Descents from dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/05/19/the-mcgucken-category-mcg%e2%82%86-as-the-foundational-structurally-complete-and-unique-category-for-the-positive-geometry-programme-penrose-twistor-space-the-positive-grassmannian-the-amplituhed/

[121] McGucken, E. (2026). The McGucken dx₄/dt = ic Formulation of Quantum Field Theory: Deriving General Relativity, Quantum Mechanics, Thermodynamics, the Standard Model Gauge Group, the Higgs Sector, the Wightman Axioms, and the Yang-Mills Mass-Gap Manifold as Theorems. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/09/09/the-mcgucken-dx%e2%82%84-dt-ic-formulation-of-quantum-field-theory-deriving-general-relativity-quantum-mechanics-thermodynamics-the-standard-model-gauge-group-the-higgs-sector-the-wightman-axi/

[122] McGucken, E. (2026). Bekenstein's five 1973 results as theorems of dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[123] McGucken, E. (2026). Hawking's 1975 results on black hole radiation as theorems of dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com

[124] McGucken, E. (2026). The McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic as the Physical Mechanism Underlying the Three Sakharov Conditions: A Geometric Resolution of Baryogenesis and the Matter-Antimatter Asymmetry. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/13/the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-as-the-physical-mechanism-underlying-the-three-sakharov-conditions-a-geometric-resolution-of-baryogenesis-and-the-matter-ant/

[125] Born, M. (1926). Zur Quantenmechanik der Stoßvorgänge. *Zeitschrift für Physik*, 37, 863.

[126] Everett, H. (1957). "Relative state" formulation of quantum mechanics. *Reviews of Modern Physics*, 29, 454.

[127] Fuchs, C. A., Mermin, N. D., & Schack, R. (2014). An introduction to QBism with an application to the locality of quantum mechanics. *American Journal of Physics*, 82, 749.

[128] Ghirardi, G. C., Rimini, A., & Weber, T. (1986). Unified dynamics for microscopic and macroscopic systems. *Physical Review D*, 34, 470.

[129] Jaeger, G. (2018). On Wheeler's quantum circuit. In *Information and Interaction*, ed. I. T. Durham and D. Rickles, Springer.

[130] Maudlin, T. (1995). Three measurement problems. *Topoi*, 14, 7.

[131] Rovelli, C. (1996). Relational quantum mechanics. *International Journal of Theoretical Physics*, 35, 1637.

[132] Wheeler, J. A. (1978). The "past" and the "delayed-choice" double-slit experiment. In *Mathematical Foundations of Quantum Theory*, ed. A. R. Marlow.

[133] Zurek, W. H. (2003). Decoherence, einselection, and the quantum origins of the classical. *Reviews of Modern Physics*, 75, 715.
[134] Eddington, A. S. (1928). *The Nature of the Physical World* (Gifford Lectures, 1927). Macmillan, New York; Cambridge University Press, Cambridge. ("time's arrow," pp. 68–69, 74, 80.) https://www.gutenberg.org/ebooks/72963

[135] Price, H. (2010). Time's Arrow and Eddington's Challenge. In *Time* (Séminaire Poincaré XV), pp. 115–140. Birkhäuser, Basel. https://seminaire-poincare.pages.math.cnrs.fr/price.pdf

[136] Callender, C. (2024). Thermodynamic Asymmetry in Time. *The Stanford Encyclopedia of Philosophy*, ed. E. N. Zalta. https://plato.stanford.edu/entries/time-thermo/

[137] Rovelli, C. (2015). Is Time's Arrow Perspectival? arXiv:1505.01125; in *The Philosophy of Cosmology*, eds. K. Chamcham, J. Silk, J. D. Barrow, S. Saunders, Cambridge University Press (2017). https://arxiv.org/abs/1505.01125

[138] Rovelli, C. (2017). *The Order of Time*. Riverhead Books, New York.

[139] Davies, P. C. W. (2006). That Mysterious Flow. *Scientific American*, 295(2), 40–47.

[140] Ellis, G. F. R. (2014). Time really exists! The evolving block universe. *Euresis Journal*, 7, 11–26. https://euresis.org/wp-content/uploads/2019/06/EJv7id2_Ellis.pdf

[141] Muller, R. A., & Maguire, S. (2016). Now, and the Flow of Time. arXiv:1606.07975. (See also R. A. Muller, *Now: The Physics of Time*, W. W. Norton, 2016.) https://arxiv.org/abs/1606.07975

[142] Mermin, N. D. (2014). QBism as CBism: Solving the Problem of "the Now." arXiv:1312.7825. https://arxiv.org/abs/1312.7825

[143] Maudlin, T. (2007). *The Metaphysics Within Physics*, ch. 4 ("On the Passing of Time"). Oxford University Press.

[144] Smolin, L. (2013). *Time Reborn: From the Crisis in Physics to the Future of the Universe*. Houghton Mifflin Harcourt, Boston.

[145] Albert, D. Z. (2000). *Time and Chance*. Harvard University Press, Cambridge, MA.

[146] Barbour, J. (1999). *The End of Time: The Next Revolution in Physics*. Oxford University Press.

[147] Carroll, S. M. (2010). *From Eternity to Here: The Quest for the Ultimate Theory of Time*. Dutton, New York.

[148] Weyl, H. (1949). *Philosophy of Mathematics and Natural Science*. Princeton University Press, Princeton, p. 116.

[149] Gödel, K. (1949). A Remark about the Relationship between Relativity Theory and Idealistic Philosophy. In *Albert Einstein: Philosopher-Scientist*, ed. P. A. Schilpp, pp. 557–562. Library of Living Philosophers, Evanston.

[150] Carnap, R. (1963). Intellectual Autobiography. In *The Philosophy of Rudolf Carnap*, ed. P. A. Schilpp, p. 37. Open Court, La Salle.

[151] McTaggart, J. M. E. (1908). The Unreality of Time. *Mind*, 17(68), 457–474.

[152] Einstein, A. (1905). Zur Elektrodynamik bewegter Körper. *Annalen der Physik*, 17, 891–921, §2.

[153] Farhi, E., Goldstone, J., & Gutmann, S. (1989). How probability arises in quantum mechanics. *Annals of Physics*, 192(2), 368–382.

[154] McGucken, E. (2026). The Physics of Time: Time and Its Arrows, Symmetries, and Asymmetries Derived and Unified as Theorems of the McGucken Principle dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/05/16/the-physics-of-time-time-and-its-arrows-symmetries-and-asymmetries-derived-and-unified-as-theorems-of-the-mcgucken-principle-dx%E2%82%84-dt-ic-the-second-law-of-thermodynamics-and-conservation-l/

[155] McGucken, E. (2026). A Derivation of the Uncertainty Principle Δx·Δp ≥ ℏ/2 from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic. *Light Time Dimension Theory*. https://elliotmcguckenphysics.com/2026/04/11/a-derivation-of-the-uncertainty-principle-%CE%B4x%CE%B4p-%E2%89%A5-%E2%84%8F-2-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%E2%82%84-dt-ic-the-expanding-fourth-dimension-th/

[156] Newton, T. D., & Wigner, E. P. (1949). Localized States for Elementary Systems. *Reviews of Modern Physics*, 21(3), 400–406. https://doi.org/10.1103/RevModPhys.21.400

[157] Ojima, I., & Saigo, H. (2011). Who has seen a free photon? arXiv:1101.5782. https://arxiv.org/abs/1101.5782

[158] Busch, P., Lahti, P., Pellonpää, J.-P., & Ylinen, K. (2001). Are number and phase complementary observables? *Journal of Physics A: Mathematical and General*, 34(30), 5923–5935. https://doi.org/10.1088/0305-4470/34/30/304

[159] Dirac, P. A. M. (1927). The Quantum Theory of the Emission and Absorption of Radiation. *Proceedings of the Royal Society of London A*, 114(767), 243–265. https://doi.org/10.1098/rspa.1927.0039

[160] Susskind, L., & Glogower, J. (1964). Quantum mechanical phase and time operator. *Physics Physique Fizika*, 1(1), 49–61. https://doi.org/10.1103/PhysicsPhysiqueFizika.1.49

[161] Pegg, D. T., & Barnett, S. M. (1989). Phase properties of the quantized single-mode electromagnetic field. *Physical Review A*, 39(4), 1665–1675. https://doi.org/10.1103/PhysRevA.39.1665


