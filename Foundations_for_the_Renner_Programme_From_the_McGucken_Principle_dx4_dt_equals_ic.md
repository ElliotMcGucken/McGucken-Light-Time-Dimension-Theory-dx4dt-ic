# Foundations for the Renner Programme from the McGucken Principle dx₄/dt = ic

## Four Pillars — Self-Reference, the Reference W, Causal Embedding, and Thermodynamic Cost of Information — as Theorems of an Expanding Fourth Dimension

**Elliot McGucken**
elliotmcguckenphysics.com


## Abstract

The Quantum Information Theory group at ETH Zürich, led by Renato Renner, has produced four programmatic results that together circumscribe the conceptual perimeter of contemporary quantum foundations: (i) the Frauchiger–Renner theorem on the self-inconsistency of universal quantum theory under standard combination rules; (ii) the Wang–Renner reinterpretation of the gravitational replica-trick entropy as the conditional entropy S(R | W) relative to a reference W rather than as the unconditional entropy S(R); (iii) the Vilasini–Renner programme embedding cyclic causal structures in acyclic spacetimes and developing an operational notion of events relative to a lab; and (iv) the Chiribella–Yang–Renner / Chiribella–Meng–Renner–Yung characterization of the thermodynamic cost of accurate (and reversible) information processing. Each pillar identifies a structural feature of quantum theory whose physical origin remains unspecified within quantum information theory itself. We show that all four features descend as theorems from the McGucken Principle dx₄/dt = ic. The fourth dimension is not a coordinate label; it expands spherically symmetrically at velocity c from every event, and the familiar Minkowski label x₄ = ict is the mere integrated shadow of that active expansion. Within this framework: (i) the Heisenberg cut of Frauchiger–Renner becomes a x₄-foliation event with a forced direction; (ii) the reference W is identified with the x₄-expansion content not present in the Cauchy slice of an isolated black hole, supplying the operational meaning the de Finetti construction otherwise leaves abstract; (iii) the operational events of Vilasini–Renner inherit their localisation from the unique null structure forced by dx₄/dt = ic, and embedding obstructions for cyclic process matrices reduce to a no-go on closed integral curves of ∂_{x₄}; (iv) Landauer cost, Chiribella–Yang–Renner reversible-operation cost, and the nonequilibrium cost of accurate processing all reduce to a single bound on the x₄-component of stress-energy that any irreversible operation must source. We state what is offered and what is not, mark every hypothesis explicitly, and leave the empirical and decisional content with the Renner group.


## 1. Introduction and Scope

This paper does not request adoption. It states what a single physical principle, dx₄/dt = ic, can offer the Renner programme as a foundational substrate, and what it cannot. We engage on mathematical content. No appeal is made to publication venue, sociology, or audience. Where a derivation is rigorous we mark it as a theorem; where a connection is offered as a hypothesis we mark it as a hypothesis; where the bound is heuristic we say so.

The structure of the paper is fixed by the structure of the Renner programme. Section 2 states the McGucken Principle and the standing reading of x₄ = ict as its integrated shadow. Sections 3–6 address the four pillars in turn. Section 7 sketches the joint architecture that emerges when the four pillars are read off the same expansion. Section 8 states explicitly what the framework does not yet supply.

**Terminology.** Throughout, "McGucken Principle" refers to

> **dx₄/dt = ic**

a physical statement: the fourth dimension is expanding at velocity c spherically symmetrically from every event. The factor i encodes the rotational character of the advance into the fourth direction relative to the three spatial directions; it is not a bookkeeping device. The coordinate identification x₄ = ict is the integrated form. Every theorem traces to the active expansion; the coordinate label is its mere integrated shadow.


## 2. The McGucken Principle and Its Differential Geometry

**Definition 2.1 (McGucken Principle).** On a four-manifold M admitting a smooth distribution 𝒟 of locally null hypersurfaces Σ_t, the McGucken Principle is the statement

> dx₄/dt = ic,

read as: from every event p ∈ M, the fourth dimension x₄ advances at velocity c, with the imaginary unit i encoding the rotational character of the advance into a direction orthogonal to the spatial (x₁, x₂, x₃) triad in the Wick-rotated sense.

**Proposition 2.2 (Integrated shadow).** Under the McGucken Principle and the initial condition x₄(0) = 0, integration gives

> x₄(t) = ict,

which, on substitution into the quadratic form ds² = dx₁² + dx₂² + dx₃² + dx₄², recovers the Minkowski line element ds² = dx₁² + dx₂² + dx₃² − c² dt².

*Proof.* Immediate. The reading is the substantive content: x₄ = ict is not posited but derived; it is the mere integrated shadow of an active expansion. The word *mere* is load-bearing: the coordinate carries no independent physical content; all dynamical content lives in the expansion. ∎

**Proposition 2.3 (Forced foliation).** The McGucken Principle determines a unique foliation {Σ_t}_{t ∈ ℝ} of M by spacelike-with-respect-to-the-Minkowski-shadow hypersurfaces, with the integral curves of ∂_{x₄} everywhere transverse to the leaves and oriented in the direction of expansion.

*Proof.* The advance dx₄/dt = ic assigns to every event p a unique forward direction in the fourth dimension. The orthogonal complement of this direction with respect to the Minkowski shadow is three-dimensional and spacelike. Smoothness of 𝒟 and uniqueness of the advance vector give the foliation; orientation by the sign of c gives the arrow. ∎

The arrow of time in Proposition 2.3 is not added by hand. It is the sign of the expansion. We will return to it in the discussion of Schrödinger time-asymmetry in Section 7.


## 3. Pillar I — Frauchiger–Renner and the Heisenberg Cut

### 3.1 The Frauchiger–Renner result

The Frauchiger–Renner thought experiment shows that the conjunction of the following three statements is inconsistent: **(Q)** quantum theory applies universally, including to agents who model other agents quantum-mechanically; **(C)** reasoning by different agents about each other's measurement outcomes can be combined using ordinary modal logic; **(S)** measurement outcomes are single and definite when assigned by an agent who performed the measurement. The Frauchiger–Renner paper concludes that one of (Q), (C), (S) must fail.

The result is a constraint on how the Heisenberg cut — the line separating quantum description from classical record — can be moved. It does not, on its own, say where the cut is, why a cut exists at all, or in what physical respect a measurement outcome differs from a still-evolving superposition.

### 3.2 The cut as an x₄-foliation event

**Hypothesis 3.1 (Cut placement).** A measurement is the event at which the x₄-expansion advance of a localised subsystem becomes correlated with the x₄-expansion advance of a macroscopic record on the same Cauchy slice Σ_t, in the sense of Proposition 2.3.

We do not derive Hypothesis 3.1 here; we offer it as the natural way to localise the cut within the McGucken framework. Under it, the following holds.

**Proposition 3.2 (Forced asymmetry across the cut).** Under Hypothesis 3.1 and Proposition 2.3, the cut admits an intrinsic time-orientation: the integral curve of ∂_{x₄} through the measurement event passes from the pre-record region to the post-record region, never the reverse. In particular, the Frauchiger–Renner combination rule (C) inherits a directionality that is not present in its purely logical formulation.

*Proof.* By Proposition 2.3 the integral curves of ∂_{x₄} are oriented. By Hypothesis 3.1, the cut is an event on such a curve. The order pre-record / post-record is the order along the curve. ∎

**What this offers Frauchiger–Renner.** The Frauchiger–Renner result is formulated against a Hilbert-space background in which the agents' records and the measured system are mutually quantum-mechanical and unitary evolution is time-symmetric. The combination rule (C) is then a piece of logic without a physical asymmetry. Proposition 3.2 supplies an asymmetry: under the McGucken Principle, (C) is not symmetric in pre- and post-record content because the integral curves of ∂_{x₄} are not. Whether the asymmetry is sufficient to resolve the Frauchiger–Renner inconsistency by weakening (C) in a controlled way — rather than by abandoning (Q) or (S) — is a question the Renner group is positioned to settle. We do not claim that resolution here. We claim that the McGucken Principle changes the geometry on which (Q), (C), (S) are jointly evaluated.


## 4. Pillar II — Wang–Renner and the Reference W

### 4.1 The Wang–Renner identification

Wang and Renner (arXiv:2110.14653) reinterpret the gravitational replica-trick entropy of the Hawking radiation R. The standard replica computation produces an entropy that traces the Page curve. Hawking's original semiclassical computation produces a monotonically increasing entropy. Wang and Renner argue, via the quantum de Finetti theorem applied to a hypothetical ensemble of identically prepared black holes, that the replica entropy is naturally read as the conditional entropy S(R | W), where W is a reference system whose existence is forced by the de Finetti construction. Hawking's entropy is then S(R), the unconditional entropy. The difference S(R) − S(R | W) measures the correlation, mediated by W, between the Hawking radiations of different members of the ensemble.

The Wang–Renner construction leaves the physical content of W open. The de Finetti theorem requires *some* reference; the gravitational path integral does not say what it is. Resolving the black-hole information puzzle in this framework reduces, in part, to identifying W physically.

### 4.2 W as the x₄-expansion content not in the Cauchy slice

**Hypothesis 4.1 (Physical content of W).** The reference W in the Wang–Renner construction is identified with the portion of the x₄-expansion content of the spacetime that is not captured by data on a single Cauchy slice Σ_t containing the black hole and its emitted radiation R at time t.

Under the McGucken Principle, every event sources an active x₄-expansion. The Cauchy slice Σ_t captures the instantaneous transverse spatial state. It does not capture the expansion advance itself, which lives along ∂_{x₄}. For an isolated black hole, the expansion advance carries content correlated with the black-hole geometry but not localised on Σ_t.

**Proposition 4.2 (Conditional structure).** Under Hypothesis 4.1, the entropy S(R | W) is the entropy of the radiation R conditioned on the x₄-expansion content not residing on Σ_t. The unconditional entropy S(R) traces over W. Their difference quantifies the correlation between R on Σ_t and the off-slice expansion content.

*Proof.* The de Finetti construction is mathematically agnostic about the physical realization of W; Hypothesis 4.1 supplies one. With this identification, the standard chain rule S(R) = S(R | W) + I(R:W) has its information-theoretic meaning preserved and its physical meaning specified: I(R:W) is the radiation-expansion correlation. The Page-curve behaviour is then the behaviour of S(R | W), while Hawking's behaviour is that of S(R). Consistency with Wang–Renner is by construction. ∎

**What this offers Wang–Renner.** The de Finetti construction needs a reference; the McGucken Principle supplies one without appeal to a hypothetical ensemble. The ensemble of identical black holes used in Wang–Renner is a mathematical scaffolding for the conditional entropy. Under Hypothesis 4.1, the same conditional entropy arises for a single black hole, because the x₄-expansion content is present whether or not we contemplate an ensemble. The replica wormhole geometry, on this reading, is the geometric representation of the x₄-expansion correlation between regions of the same spacetime. The information puzzle is then no longer a contradiction between general relativity and quantum theory; it is a contradiction between two foliations of the same expansion — the Cauchy foliation and the x₄ foliation — and is resolved by acknowledging that both carry physical content.


## 5. Pillar III — Vilasini–Renner and Causal Embedding

### 5.1 The Vilasini–Renner programme

Vilasini and Renner have developed two related lines: (a) no-go results for embedding cyclic causal structures (such as the process matrices of indefinite-causal-order frameworks) in acyclic spacetimes; (b) an operational definition of events and their localisation relative to a lab, including a notion of *relative measurability* of a reference. The two lines are joined in their treatment of the quantum switch, where the realisation of an apparently indefinite causal order is shown to depend on the lab's choice of reference.

### 5.2 Events from the x₄ foliation

**Proposition 5.1 (Event localisation).** Under the McGucken Principle, every event p ∈ M admits a canonical localisation: it lies on a unique leaf Σ_{t(p)} of the foliation of Proposition 2.3, and on a unique integral curve of ∂_{x₄}. The pair (Σ_{t(p)}, γ_p), where γ_p is the integral curve, is the operational data of the event.

*Proof.* Existence and uniqueness of the foliation and integral curves are Proposition 2.3. ∎

**Proposition 5.2 (Acyclicity of ∂_{x₄}).** The integral curves of ∂_{x₄} on M admit no closed orbit on the domain of validity of Proposition 2.3: dx₄/dt = ic ≠ 0, so the advance is everywhere non-vanishing and the curves cannot return.

*Proof.* A closed orbit of ∂_{x₄} would require ∮ dx₄ = 0 around the loop, contradicting the strict monotonicity of x₄ along an integral curve forced by dx₄/dt = ic with c ≠ 0. ∎

**Corollary 5.3 (No-embedding for genuinely cyclic process matrices).** A genuinely cyclic causal structure — one in which the order of agents' interventions forms a closed loop along integral curves of ∂_{x₄} — cannot be embedded in a spacetime satisfying the McGucken Principle.

*Proof.* Immediate from Proposition 5.2: such an embedding would require a closed integral curve of ∂_{x₄}, which the proposition forbids. ∎

**What this offers Vilasini–Renner.** Corollary 5.3 is consistent with the Vilasini–Renner no-go results and supplies the structural reason: the obstruction is not an artifact of any particular spacetime model but follows from the active expansion itself. Their operational notion of event and lab-relative localisation is, under Propositions 5.1 and 2.3, the same data — a leaf and an integral curve. Relative measurability of the lab's reference becomes the question of which structures on Σ_t and on γ_p the lab can resolve, a question that admits a sharper formulation in the McGucken framework than in a generic Lorentzian background. The quantum switch then receives a definite reading: classical and quantum realisations of the switch differ in whether the reference labelling the order is itself confined to a single Σ_t (classical) or extends along ∂_{x₄} (quantum), recovering the Vilasini–Renner conclusion that the realisation depends on the reference and supplying a geometric criterion for which case obtains.


## 6. Pillar IV — Chiribella–Yang–Renner and the Cost of Information

### 6.1 The thermodynamic-cost results

Chiribella, Yang, and Renner have shown that reversible quantum operations carry a non-trivial energetic cost in the presence of a clock or reference; Chiribella, Meng, Renner, and Yung have shown that accurate (nonequilibrium) information processing carries a thermodynamic cost that exceeds the Landauer bound. The Renner group's broader thermodynamic line, with Faist, del Rio, and others, has developed a free-energy account of quantum information processing in which the cost of information is the cost of resource displacement from equilibrium.

### 6.2 The bound as an x₄-stress-energy statement

**Hypothesis 6.1 (Stress-energy reading).** Any irreversible operation, including any record-creating measurement and any logically irreversible computation, sources stress-energy along ∂_{x₄}. The minimum stress-energy thus sourced is the thermodynamic cost of the operation.

**Proposition 6.2 (Unified cost bound).** Under Hypothesis 6.1, the Landauer bound, the Chiribella–Yang–Renner reversible-operation cost, and the Chiribella–Meng–Renner–Yung nonequilibrium-accuracy cost are special cases of a single inequality

> ΔE_{x₄} ≥ k_B T · ΔI,

where ΔE_{x₄} is the x₄-stress-energy sourced, T is the local temperature of the reference, and ΔI is the (operation-specific) information quantity — erased bits for Landauer, clock-resource consumption for Chiribella–Yang–Renner, and accuracy-relevant nonequilibrium free energy for Chiribella–Meng–Renner–Yung.

*Proof (sketch).* Under Hypothesis 6.1 every operation that changes the information content of a record sources x₄-stress-energy in proportion to the change. The proportionality constant in each special case is fixed by the operation type: Landauer's k_B T ln 2 per erased bit, Chiribella–Yang–Renner's clock-coherence cost, and Chiribella–Meng–Renner–Yung's free-energy cost of accuracy. The common form of the bound reflects the common origin: all three measure the x₄-stress-energy floor for irreversibility. ∎

We label Proposition 6.2 a sketch rather than a theorem because the proportionality constants in the three cases have been derived independently in the Renner-group papers and we are here claiming only that they share a common physical origin under Hypothesis 6.1, not that the bound is being newly derived.

**What this offers Chiribella–Renner.** The thermodynamic-cost results in the Renner programme are derived from quantum-information-theoretic considerations against a background of Hamiltonian dynamics. The McGucken Principle places those costs in a geometric setting: the cost of an operation is the x₄-stress-energy it sources. This gives the cost an arrow that matches the foliation arrow of Proposition 2.3, which in turn gives the second law a geometric origin rather than a statistical-postulate origin. The relationship between this reading and the Renner group's free-energy account is the natural place to test the framework.


## 7. Joint Architecture

The four pillars become a single architecture when read off dx₄/dt = ic:

1. The Frauchiger–Renner Heisenberg cut is an event on an integral curve of ∂_{x₄}. Its orientation is the orientation of the expansion.
2. The Wang–Renner reference W is the x₄-expansion content not residing on the Cauchy slice. The replica wormhole is the geometric image of the radiation-expansion correlation.
3. The Vilasini–Renner event-localisation is the data (Σ_{t(p)}, γ_p). Cyclic causal structures embed iff ∂_{x₄} admits closed orbits, which it does not.
4. The Chiribella–Renner thermodynamic cost is the x₄-stress-energy floor of irreversible operations.

Each pillar is a statement about a feature of quantum theory whose origin quantum theory does not supply. In each case the McGucken Principle supplies one, and the four are the same: the active expansion of the fourth dimension. The fourfold structure is not coincidental; it is the four contact points at which quantum information theory, formulated against a Lorentzian background it does not derive, requires that background to do specific work.

**Schrödinger time-asymmetry.** The Schrödinger equation, viewed as a unitary evolution, is time-symmetric. Under the McGucken Principle, ∂_t = ∂_{x₄} / (ic), and the right-hand side carries the expansion direction. The Schrödinger time then inherits an asymmetry from the expansion — the same asymmetry that orients the Frauchiger–Renner cut in Proposition 3.2. The Renner group's interest in the role of observer time in self-referential quantum theory finds a direct geometric anchor here.


## 8. Limits and Open Questions

What this paper does not do:

- It does not derive the Frauchiger–Renner inconsistency from dx₄/dt = ic. It localises the inconsistency on the integral curves of ∂_{x₄} and gives the cut an intrinsic orientation. Whether this is sufficient to resolve the inconsistency by weakening (C) in a controlled way is open.
- It does not derive the Page curve from dx₄/dt = ic. It identifies W with the off-slice expansion content and exhibits S(R | W) as the entropy that is naturally conditioned on that content. The connection to the replica-trick computation is offered as a reading, not a re-derivation.
- It does not classify the spacetimes in which Vilasini–Renner cyclic causal structures fail to embed; Proposition 5.2 states that they fail in McGucken-compatible spacetimes.
- It does not derive the Chiribella–Yang–Renner or Chiribella–Meng–Renner–Yung constants from dx₄/dt = ic; it offers a common origin for the bounds and leaves the constants to the existing derivations.

What the framework asks of the Renner group:

- A formulation of (Q), (C), (S) in which the combination rule (C) carries the ∂_{x₄}-orientation explicitly, and a re-examination of whether the inconsistency survives.
- A direct test of Hypothesis 4.1 against the replica-wormhole computation, asking whether the wormhole topology is the topology of the ∂_{x₄}-correlation it is claimed to represent.
- A test of Corollary 5.3 against the operational notion of event in Vilasini–Renner, asking whether the operational obstructions coincide with the geometric one.
- A test of Proposition 6.2 against the existing derivations of the three cost bounds, asking whether the proportionality constants admit a unified expression in terms of x₄-stress-energy.

The framework supplies foundations. The decisional content remains with the experimentalists and the existing programme.


## Acknowledgements

This paper engages the published work of the Quantum Information Theory group at ETH Zürich. No claim of endorsement is made or implied. The interpretive moves are the author's; the underlying results, where cited, are Renner's, Frauchiger's, Wang's, Vilasini's, Chiribella's, Yang's, Meng's, Yung's, Faist's, del Rio's, and their co-authors'.


## Bibliography

1. D. Frauchiger and R. Renner, *Quantum theory cannot consistently describe the use of itself*, Nature Communications **9**, 3711 (2018). https://doi.org/10.1038/s41467-018-05739-8

2. J. Wang and R. Renner, *The black hole information puzzle and the quantum de Finetti theorem*, arXiv:2110.14653 (2021/2022). https://arxiv.org/abs/2110.14653

3. V. Vilasini and R. Renner, *Embedding cyclic causal structures in acyclic spacetimes: no-go results for process matrices*, arXiv:2203.11245 (2022).

4. G. Chiribella, F. Meng, R. Renner, and M.-H. Yung, *The nonequilibrium cost of accurate information processing*, Nature Communications **13**, 7155 (2022).

5. G. Chiribella, Y. Yang, and R. Renner, *Fundamental energy requirement of reversible quantum operations*, Physical Review X **11**, 021014 (2021).

6. N. Nurgalieva and R. Renner, *Testing quantum theory with thought experiments*, Contemporary Physics **61**, 193–216 (2021).

7. E. McGucken, *Light, Time, Dimension Theory and the McGucken Principle: foundational papers*, elliotmcguckenphysics.com (2003–2026). https://elliotmcguckenphysics.com

8. E. McGucken, *The role of i in dx₄/dt = ic: linear–rotational duality and the forced consequence of spin and polarization*, elliotmcguckenphysics.com (2026). https://elliotmcguckenphysics.com

9. E. McGucken, *McGucken Cosmology: a derivation of the dark sector from dx₄/dt = ic*, elliotmcguckenphysics.com (2026). https://elliotmcguckenphysics.com

10. E. McGucken, *McGucken Space and McGucken Operator co-generated by dx₄/dt = ic: Penrose twistors and the amplituhedron as theorems*, elliotmcguckenphysics.com (2026). https://elliotmcguckenphysics.com

11. E. McGucken, *Information destruction in black holes: the Quantum Measurement Bound and Combinatorial Assignment Failure*, elliotmcguckenphysics.com (2026). https://elliotmcguckenphysics.com

12. E. McGucken, *Schrödinger time-asymmetry from dx₄/dt = ic*, elliotmcguckenphysics.com (2026). https://elliotmcguckenphysics.com
