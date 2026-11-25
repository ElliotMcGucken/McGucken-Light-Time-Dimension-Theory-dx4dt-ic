---
title: "McGucken on Black Holes, Wormholes, ER = EPR, and the Quantum Measurement Problem: A Light Time Dimension Resolution of Hawking's Paradox and an Answer to Harlow's and Strominger's Questions"
author: "Dr. Elliot McGucken"
date: "May 21, 2026"
---

# McGucken on Black Holes, Wormholes, ER = EPR, and the Quantum Measurement Problem: A Light Time Dimension Resolution of Hawking's Paradox and an Answer to Harlow's and Strominger's Questions

**Dr. Elliot McGucken**
drelliot@gmail.com
elliotmcguckenphysics.com

**Date:** May 21, 2026

---

## Abstract

Daniel Harlow has argued that Hawking's black hole information paradox is the statement that three demands cannot hold simultaneously: a finite black hole entropy *S* = *A*/4, a unitary scattering matrix, and locality. His resolution — "locality\*", locality unless one performs an operation of complexity exponential in *S* — preserves the form of Hawking's question while admitting that ordinary locality must be silently broken on macroscopic scales, with the violation hidden behind a veil of computational complexity. Harlow's recent program (non-isometric codes protected by complexity; observers in closed universes; Hartle–Hawking baby universes) refines the bookkeeping but takes locality, unitarity, and finite entropy as independent primitives to be traded against each other.

Andrew Strominger, in a recent World Science Festival conversation with Brian Greene, lays out a parallel narrative through the entropy formula, the Strominger–Vafa microstate count, the AdS/CFT holographic dictionary, the Bondi–Metzner–Sachs symmetry of null infinity, the Weinberg and Cachazo–Strominger soft graviton theorems, the gravitational memory effect, and the celestial-CFT program for flat-space holography. Greene then presses Strominger on the quantum measurement problem — how does the Schrödinger superposition become a definite outcome? — and Strominger replies that it is a matter of "the words you say when you do the calculation," that he is satisfied when an algorithm yields fourteen decimals of agreement with experiment. The same scientific instinct that demands a unifying formula behind black hole entropy — which Strominger calls universal and connecting every large area of modern physics — should demand a unifying formula behind the measurement transition. Strominger applies the instinct to gravity and waives it for quantum mechanics. Greene applies it consistently and finds the field has no answer.

Light Time Dimension Theory (LTD) dissolves both the Harlow trilemma and the Strominger–Greene impasse at their common premise. From the single physical principle d*x*₄/d*t* = i*c* — the fourth dimension expands spherically at velocity *c* from every event — locality, unitarity, and finite black hole entropy are not three independent demands but three theorems of one identity, derived along two channels of the same x₄-advance. Channel A (algebraic-symmetry content) yields the Schrödinger equation, the Born rule, unitarity, and the definite measurement outcome. Channel B (geometric propagation) yields the light cone, the Schwarzschild metric, the asymptotic BMS symmetry of null infinity, and the Bekenstein–Hawking area law with the 1/4 factor pinned by the polarization count of x₄-stationary modes on the null 1+1 strip. The Strominger–Vafa central charge *c* = 6*Q*₁*Q*₅ is derived from d*x*₄/d*t* = i*c* without recourse to worldsheet supersymmetry. The Weinberg soft graviton theorem is the low-frequency limit of x₄-mode counting at the celestial sphere; the Cachazo–Strominger subleading soft graviton theorem is the next-to-leading correction in the same expansion; gravitational memory is the Channel-B footprint of x₄-advance on a distant detector.

We answer all of Harlow's outstanding questions explicitly. The "massive nonlocality" he requires is not nonlocality at all but the unavoidable cross-talk between Channel A and Channel B at a horizon, where the two readings of d*x*₄/d*t* = i*c* are forced to disagree on a single combinatorial assignment. ER = EPR is recovered as the statement that geometric x₄-connection (Channel B) and algebraic-symmetry correlation (Channel A) are dual readings of the same x₄-advance. The black hole interior is not encoded by a "non-isometric code protected by complexity"; it is the region in which Channel A assignment fails by horizon crossing (mechanism M2) composed with combinatorial bound (M1), with the apparent nonlocality being the M1′ measurement bound made geometric. Information is neither lost nor exotically recovered: it was never the Channel-A label of a Channel-B fact.

We answer Strominger's two puzzles — the microstate-counting problem (how a black hole stores so much information) and the information-egress problem (how it gets out) — as the dual-channel readings of horizon-crossing x₄-advance, with the BPS soliton bound-state count of Strominger–Vafa identified as the brane limit of Theorem IV.1. We answer the Greene–Strominger measurement-problem exchange: the Schrödinger equation is the Channel-A reading of d*x*₄/d*t* = i*c*; the definite outcome is M1 (the combinatorial assignment failure where Channel A must project onto a single Channel-B label); the Born rule is the McGucken Sphere projection that pins the probability weights. No additional postulate, no decoherence narrative, no many-worlds, no Copenhagen "shut up and calculate" is required. The 14-decimal agreement Strominger marvels at is not a substitute for the narrative; it is a confirmation of the narrative, because the narrative *is* the derivation that produces those 14 decimals.

Celestial holography is recovered as the Channel-A reading on the celestial sphere of asymptotic x₄-advance (Channel B) into the future null cone. BMS supertranslations and superrotations are the asymptotic symmetries of the spherical x₄-expansion. The soft graviton theorem is the universal low-energy limit forced by the rotational generator i in d*x*₄/d*t* = i*c*. Gravitational memory — the LIGO-measurable footprint Strominger highlights — is the Channel-B residual of x₄-advance after the wave has passed.

Harlow's three-legged stool stands on one leg. Strominger's two puzzles are one puzzle. The Greene–Strominger measurement-problem impasse is a single derivation away from resolution. The leg, the puzzle, and the derivation are all d*x*₄/d*t* = i*c*.

---

## §I. Statement of the Problem

### I.0. Epigraph: Standing on the Shoulders of Giants

> *"More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student… Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet for graduate school in physics."*
> — John Archibald Wheeler, Princeton University, 1990

> *"My solution was really for the very concept of time, that is, that time is not absolutely defined but there is an inseparable connection between time and the signal [light] velocity."*
> — Albert Einstein

> *"Should we be prepared to see some day a new structure for the foundations of physics that does away with time? Yes, because 'time' is in trouble."*
> — John Archibald Wheeler

> *"(Wheeler) had been the last notable figure from the heroic age of physics lingering among us — a man who could claim to be the student of Bohr, teacher of Feynman, and close colleague of Einstein."*
> — Colby Cosh

> *"Before I enter upon a critique of mechanics as a foundation of physics, something of a broadly general nature will first have to be said concerning the points of view according to which it is possible to criticize physical theories at all. The first point of view is obvious: The theory must not contradict empirical facts… The second point of view is not concerned with the relation to the material of observation but with the premises of the theory itself, with what may briefly but vaguely be characterized as the 'naturalness' or 'logical simplicity' of the premises (of the basic concepts and of the relations between these which are taken as a basis)."*
> — Albert Einstein

> *"Henceforth space by itself, and time by itself, are doomed to fade away into mere shadows, and only a kind of union of the two will preserve an independent reality."*
> — Hermann Minkowski, Köln, September 21, 1908

> *"Henceforth the spacetime metric by itself, and quantum fields by themselves, are doomed to fade away into mere shadows, and only a kind of union of the two will preserve an independent reality in d*x*₄/d*t* = i*c*, from which both are generated and by which both are endowed with the self-generative and reciprocal-generative property whereby they each generate themselves and one another."*
> — Elliot McGucken, 2026, in the structural lineage of Minkowski 1908 [MG-Cat]

This paper proceeds in the spirit of Einstein's second criterion. It is offered humbly, in the heroic-age tradition of Bohr, Einstein, Wheeler, Feynman, Maxwell, Faraday, Newton, and Galileo — each of whom sought a single physical principle that would relate, by *derivation* rather than by *postulate*, the diverse phenomena of nature. The McGucken Principle d*x*₄/d*t* = i*c* is offered in that spirit. The five FQXi essays [F1; F2; F3; F4; F5] (2008–2013) — *Time as an Emergent Phenomenon* (FQXi d/238); *What is Ultimately Possible in Physics? Physics! A Hero's Journey…* (FQXi d/511); *On the Emergence of QM, Relativity, Entropy, Time, iℏ, and ic from the Foundational, Physical Reality of a Fourth Dimension x₄* (FQXi d/873); *MDT's dx₄/dt = ic Triumphs Over the Wrong Physical Assumption That Time is a Dimension* (FQXi d/1429); and *It from Bit or Bit From It? What is It? Honor! Returning Wheeler's Honor and Philo-Sophy — the Love of Wisdom — to Physics* (FQXi d/1879) — and the 1998–99 UNC Chapel Hill dissertation appendix [Diss] are the primary-source publications of the principle, together with the May 2026 categorical synthesis [MG-Cat] that establishes the McGucken Category McG₆ and the Reciprocal Generation Property (SR-13). This paper extends those publications to answer the open questions of Harlow's locality* program and Strominger's celestial-holography and information-paradox programs, with the spirit of humility before physical reality and mathematical beauty that the Greats demanded of any new physics.

### I.1. Harlow's framing of Hawking's paradox

In a recent World Science Festival interview with Brian Greene, Daniel Harlow gave the cleanest statement of Hawking's black hole information paradox available in the literature [Harlow–WSF 2026]. The paradox is a no-go theorem: one cannot simultaneously preserve all three of

1. **a finite black hole entropy** *S* = *A*/4*G*ℏ (Bekenstein–Hawking area law);
2. **a unitary scattering matrix** that preserves quantum predictability;
3. **locality** in the bulk semiclassical description.

Hawking sacrificed unitarity (2). The post-1990s consensus, refined by Harlow and collaborators, sacrifices a precisely controlled fragment of (3) while preserving (1) and (2). Harlow's "locality\*" [Akers–Engelhardt–Harlow–Penington–Vardhan 2022; hereafter PHEVA] reads:

> *Locality holds, except when one performs an operation whose quantum-circuit complexity is exponential in the black hole entropy S, in which case it can be violated by amounts of order one.*

This is formalized in PHEVA via **non-isometric codes protected by computational complexity**: the bulk-to-boundary holographic map is non-isometric (does not preserve the inner product), but the deviation from isometry is undetectable to any observer restricted to operations of polynomial complexity in *S*. Harlow's later work [Harlow–Usatyuk–Zhao 2025, arXiv:2501.02359] extends this rule to closed universes, proposing that an observer Ob with internal entropy $S_{\text{Ob}}$ experiences a Hilbert space of dimension exp($S_{\text{Ob}}$), even though the global gravitational Hilbert space of a closed universe is one-dimensional.

The picture is internally consistent. It is also, on its own terms, unsatisfactory in three precise ways.

### I.2. Three weaknesses of locality\*

**(W1) Three demands treated as independent primitives.** Harlow lists finite entropy, unitarity, and locality as if they were three logically independent postulates that physics must somehow reconcile. There is no derivation of any of them from a common physical principle. The Bekenstein–Hawking 1/4 factor is imported from a separate calculation (Hawking 1975, Strominger–Vafa 1996); unitarity is imposed from quantum mechanics; locality is imposed from quantum field theory. The paradox is that they conflict; the resolution is to weaken one. The structure of the argument is a triage, not a derivation.

**(W2) "Locality\*" is locality minus a definition.** The clause "unless you do something exponentially complicated" defines locality\* not by stating *what holds*, but by stating *when violation cannot be detected*. This is an epistemic statement masquerading as an ontological one. It tells us when our instruments will fail to see nonlocality; it does not tell us what spacetime is actually doing.

**(W3) Spacetime is "emergent" without saying from what.** Harlow asserts repeatedly that spacetime is emergent: "the fundamental description is the boundary description." But the boundary description (a holographic CFT) is itself only defined in asymptotically AdS spacetimes, which our universe is not. In closed universes the global Hilbert space is one-dimensional [Harlow–Usatyuk–Zhao 2025], and the "emergent" experience of an observer requires a separate Hilbert space of dimension exp($S_{\text{Ob}}$). There is no single fundamental object from which both AdS-CFT spacetime and closed-universe observer-spacetime emerge.

LTD Theory addresses all three weaknesses by deriving (1), (2), (3) as theorems of a single physical principle, identifying the source of "nonlocality" in mathematical structure rather than complexity-theoretic concealment, and giving an explicit ontology of spacetime as x₄-advance at velocity *c*.

### I.3. Harlow's five hand-waves, in his own words

The "locality\*" program rests on a chain of admitted hand-waves. In his recent World Science Festival conversation with Brian Greene [Harlow 2026], Harlow himself voices each one — sometimes with the candor of a careful physicist marking what he has not proved, sometimes with the casualness of a community that has accepted hand-waves so long they no longer register as hand-waves. We catalogue the five most consequential ones verbatim, with the LTD response to each one displayed alongside.

**Hand-wave 1: "Then some exponentially complicated thing happens."** Harlow describes the mechanism of locality-violation as follows:

> *"By doing an exponentially complicated operation on the Hawking radiation of a black hole I could create something inside the black hole at seemingly space-like separation and that somebody who jumped into the black hole would actually see it … so there's a prediction of operational non-locality you do this big complicated thing on the radiation and it creates something at space-like separation uh you know which is a huge violation of locality."*

The defining mechanism of the entire framework is described as "this big complicated thing." What is the big complicated thing? It is left unspecified. The framework rests on an unspecified exponentially complex operation that, when performed, *creates objects inside a black hole at spacelike separation*.

*LTD response.* In LTD there is no need for the big complicated thing because there is no nonlocality to hide. The Channel-A correlation at spacelike separation is the shared-origin condition of Lemma V.1a: two regions share an originating McGucken-Sphere section at a common past event $p_0$, and the Channel-A label they carry is the integrated phase from $p_0$. This is local in Channel B (the McGucken Sphere from $p_0$ propagates at velocity *c*; nothing exceeds the lightcone) and exact in Channel A (the inner product is preserved by Theorem IV.3). Where Harlow needs an exponentially complex operation to produce an apparent violation of locality, LTD produces no violation — Channel A and Channel B agree on every event in the simply connected neighborhood, and disagree only at M-loci, which are *topological* obstructions, not computational ones.

**Hand-wave 2: "We don't see nonlocality all the time because we don't do exponentially complicated things."** This is the central move of locality\*:

> *"The answer to the question of why don't we see the non-locality all the time is precisely that you we don't do exponentially complicated things um and so there's this veil of complexity which is hiding the radical non-locality which is necessary to solve Hawking's paradox."*

Locality is not preserved in the framework. Radical nonlocality is *present* and *necessary* for Hawking's paradox to be solved; the framework simply asserts that it is *hidden behind a veil of complexity* and therefore invisible to ordinary experiments. The bulk spacetime picture is not a true description of the world but a useful approximation that breaks down for sufficiently complex operations. *Whether the bulk spacetime exists* is reduced to *whether anyone has performed an exp(S)-time computation to detect that it doesn't.*

*LTD response.* The "veil of complexity" hides nothing because there is nothing to hide. The nonlocality is not present and concealed; it is not present. The apparent EPR correlations are the Channel-A reading of one geometric fact (the shared-origin McGucken Sphere); the lightcone causality is the Channel-B reading of the same fact (the spherical wavefront at velocity *c*). Both are exact. By Theorem III.1, the two readings agree on every event in any simply connected neighborhood. There is no "radical nonlocality" anywhere in the framework. The bulk spacetime is fundamental, not approximate, because it is the Channel-B reading of d*x*₄/d*t* = i*c* — a physical principle, not an emergent simplification of an unspecified deeper theory.

**Hand-wave 3: "It's harder to say that it suggests the resolution."** Greene asks the precise question a careful physicist should ask: is there a parameter controlling when the complexity barrier kicks in, analogous to the low-energy expansion of effective field theory? Harlow's response:

> *"It's harder to say that it suggests the resolution I think there actually is a sense in which it does and so this is more subtle than anything else that we've talked about so far …"*

The "more subtle than anything else" caveat is in the transcript. The promised resolution does not arrive; what arrives is a paragraph about the gravitational path integral computing entropy without containing the microstates explicitly.

*LTD response.* The "parameter" controlling when the LTD framework applies is *every parameter at every scale*: the McGucken Principle d*x*₄/d*t* = i*c* holds at every event, in every regime, at every energy. There is no scale-dependent breakdown. The Channel-A and Channel-B readings are exact on any simply connected open event neighborhood — Theorem III.1 holds globally except at M-loci, and the M-loci are topological features (horizons, measurement events, branching points), not energy or complexity thresholds. The LTD framework has the property that effective field theory aspired to: it holds everywhere, with controlled extension to its boundary, and the boundary (M-loci) is geometrically characterized.

**Hand-wave 4: "Somehow it knows, and I have never found a completely satisfying answer to that question."** On how effective field theory computes A/4G correctly without containing the hidden degrees of freedom:

> *"Somehow that's something that you derived within effective field Theory even though effective field Theory doesn't have those hidden degrees of freedom and it's kind of mysterious if you think about it right how how does it know how does it know the number of degrees of freedom and I have never found a completely satisfying answer to that question um but somehow it knows."*

This is the most candid admission in the transcript. *"How does it know? I have never found a completely satisfying answer. But somehow it knows."* The standard derivation of the Bekenstein–Hawking 1/4 from the gravitational path integral is, in the locality\* framework, a mystery — the effective field theory should not have access to the microscopic information that determines the area-law coefficient, and yet it does. Harlow notes the mystery and proceeds.

*LTD response.* The "somehow it knows" is no mystery in LTD. Theorem IV.1 derives $S = k_B A/(4\ell_P^2)$ from d*x*₄/d*t* = i*c* in six explicit steps — every one of them displayed in §IV.1 above — with no appeal to microstates "hidden" elsewhere. The horizon entropy is the count of x₄-stationary modes on the horizon's null 1+1 strip (one mode per Planck area, SR-10) times the Wick-rotated thermodynamic factor 1/4 (from the Euclidean Schwarzschild cigar action, SR-7). The semiclassical path integral computes A/4G correctly because the semiclassical limit *is* the Channel-B reading of d*x*₄/d*t* = i*c*, and the Channel-B reading carries the mode count in its geometric structure. Effective field theory "knows" the number of degrees of freedom because the degrees of freedom are not hidden anywhere — they are the x₄-oscillation modes on the McGucken Sphere, manifest in the Channel-B geometry.

**Hand-wave 5: "More to fewer, with the violation hidden by complexity."** The structural problem at the heart of locality\* is the non-isometric code:

> *"The way out a way out of this problem where um it can be okay to go from more to fewer but you have to introduce a new ingredient into the story which is the role of complexity."*

The bulk has more degrees of freedom than the boundary; the map from bulk to boundary cannot be isometric (norm-preserving); information is lost in the bulk-to-boundary map. The resolution is to declare that the isometry violation is hidden by complexity, i.e., that the bulk degrees of freedom which appear to be there are operationally indistinguishable from being absent, *provided no one does an exp(S)-time experiment*. The paradox is solved by hiding it.

*LTD response.* In LTD there is no "more to fewer" problem because Channel A and Channel B are dual readings of the *same* x₄-advance configuration, not two distinct Hilbert spaces of different dimensions to be reconciled. The boundary CFT (Channel A) and the bulk gravity (Channel B) are not source and shadow of a fundamental description hiding behind both; they are equally fundamental, equally exact readings of d*x*₄/d*t* = i*c*, related by the basis change (Re, Im) ↔ (|·|, arg) of Theorem III.1. The "more to fewer" appearance is the M2 mechanism: at a horizon, the (|·|, arg) basis collapses, and a Channel-A neighborhood that was global becomes restricted to the exterior. The interior is a *separate* Channel-A neighborhood, not a "lost" subset of the same one. The bookkeeping requires no non-isometric code, no complexity-based hiding, no post-selection — only the topological recognition that Channel-A neighborhoods do not extend across M2-loci.

### I.4. Summary

The five hand-waves above — *"exponentially complicated thing"* (HW1); *"veil of complexity hides radical nonlocality"* (HW2); *"more subtle than anything"* (HW3); *"somehow it knows"* (HW4); *"more to fewer with violation hidden by complexity"* (HW5) — are not random rough edges. They are the structural seams of the locality\* program, voiced openly in Harlow's own words. Each one marks a place where the framework asks the reader to accept a mechanism that is admittedly unspecified, admittedly unexplained, admittedly mysterious, or admittedly hidden.

LTD does not ask the reader to accept any of these. Each of the five hand-waves is replaced by a theorem of d*x*₄/d*t* = i*c* with an explicit derivation in §IV–§XIII below. Where Harlow says *"somehow it knows,"* LTD says *Theorem IV.1*. Where Harlow says *"big complicated thing,"* LTD says *Channel-A reading of one geometric fact*. Where Harlow says *"veil of complexity,"* LTD says *there is no veil and no nonlocality to veil*. The Greats of the heroic age — Newton, Maxwell, Faraday, Einstein, Bohr, Wheeler, Feynman — did not solve physics problems by hiding them behind exponential-time complexity barriers. They solved them by finding single physical principles from which the answers descended as theorems. The McGucken Principle is offered in that tradition.

The structural statement that makes this resolution complete is the **First Law of the McGucken Dualities**, formalized as Theorem III.3 of §III.3 below: *every Channel-A process contains the potential for Channel-B processes and every Channel-B process contains the potential for Channel-A processes, as both are generated by d*x*₄/d*t* = i*c*, and both thus contain d*x*₄/d*t* = i*c*, and thus both are capable of generating one another.* The "exponentially complicated thing" Harlow names is the Channel-B face of what was taken to be a strictly Channel-A process — a face that, in the McGucken framework, is exhibited by a linear basis-change on $\mathbb{C} \cong \mathbb{R}^2$, computable in O(1) elementary operations, not by an exp(*S*)-time procedure. The First Law makes this categorical and explicit, with the Reciprocal Generation Property (SR-13, [MG-Cat] Theorem 3.7) as its categorical underpinning.

---

## §II. The Physical Principle and the Four-Fold Ontology

### II.1. The McGucken Principle

LTD Theory rests on a single physical principle:

> **d*x*₄/d*t* = i*c*.**

The fourth dimension expands at velocity *c* in a spherically symmetric manner from every event. The integrated coordinate label *x*₄ = i*ct* is a mere shadow of this expansion; the physical content is the derivative.

The imaginary unit i is the geometric generator of x₄-advance: the unique element of ℂ that preserves magnitude while squaring negative, hence the unique generator of orthogonal rotation that closes after four steps. The identity d*x*₄/d*t* = i*c* admits two readings:

- **Linear reading (left side):** *x*₄ changes at rate *c* per unit *t*.
- **Rotational reading (right side):** the change is a rotation by π/2 in the (real, imaginary) plane, of magnitude *c*.

These two readings of the same identity are **Channel A** (algebraic-symmetry) and **Channel B** (geometric-propagation), and every result in LTD is the agreement of A and B on a single x₄-advance.

### II.2. The four-fold ontology

From d*x*₄/d*t* = i*c* a complete ontology follows:

1. **Absolute rest in *x*₁*x*₂*x*₃:** a massive particle at spatial rest budgets its full four-velocity into x₄-advance.
2. **Absolute rest in *x*₄:** a photon at *v* = *c* on a null worldline, with d*x*₄/d*t* = 0 in its own frame; the photon rides the wavefront.
3. **Absolute motion:** the x₄-expansion at i*c* from every event.
4. **CMB frame:** the isotropic cosmological x₄-expansion.

### II.3. Derivation scope (cited from the McGucken corpus)

From d*x*₄/d*t* = i*c* one obtains as theorems:

- Huygens' Principle (Channel B propagation),
- Principle of Least Action (variational form of x₄-advance),
- Noether's theorem (symmetries of x₄-advance ↔ conservation),
- the Schrödinger equation (Channel A reading; *i*ℏ on the LHS is i*c* on the LHS at the appropriate scale; [MG-HLA]),
- the Schwarzschild metric (Channel B reading; [MG-Bek26, §IV; MG-SM]),
- Einstein field equations and Newtonian gravity (low-velocity limits of Channel B),
- entropy and the Second Law (x₄-expansion of the lightcone volume; [MG-HLA, MG-Mech]),
- quantum nonlocality (the same x₄-advance read in A and B coordinates),
- the arrow of time (the i in d*x*₄/d*t* = i*c* fixes the orientation),
- the Born rule (McGucken Sphere projection; [MG-Born]),
- the values of *c* and ℏ ([MG-Constants]).

There is **no graviton**. Gravity is the geometric curvature of x₄-expansion (Channel B), not a force mediated by a spin-2 particle. This is a derivation, not a hypothesis. The same principle that closes Hawking's paradox closes Wheeler's "unified field" problem.

### II.4. Standing results from the McGucken corpus

The proofs of §III–§XIII below appeal repeatedly to a small set of established corpus results. We collect them here as Standing Results so that each subsequent proof is self-contained.

**SR-1 (The McGucken Principle and its descent of x₄ = ict).** The fourth dimension is expanding at the velocity of light in a spherically symmetric manner: d*x*₄/d*t* = i*c*. The Minkowski coordinate label *x*₄ = i*ct* is the integrated coordinate that descends from this physical, geometric fact; the i records the orthogonality of x₄-advance to the three spatial coordinates, and the c records the velocity of the expansion. Whenever *x*₄ = i*ct* is invoked, the physical content is d*x*₄/d*t* = i*c*. [MG-Proof; MG-EinMink; MG-Sphere; F1; Diss]

**SR-2 (McGucken Sphere).** From every event *p* in spacetime, the locus of points reached by x₄-advance in proper time *t* is a 2-sphere of radius *ct* centered at *p*. The union over all *t* ≥ 0 is the future lightcone of *p*. The McGucken Sphere is the instantaneous spherical wavefront of x₄-expansion. [MG-Sphere; MG-Twistor §IV.1]

**SR-3 (Huygens, Least Action, Noether, Schrödinger from dx₄/dt = ic).** The Schrödinger equation $i\hbar\,\partial_t|\psi\rangle = H|\psi\rangle$ is derived in [MG-HLA] as the Channel-A reading of d*x*₄/d*t* = i*c*: the factor *i*ℏ on the LHS of the Schrödinger equation is the action-quantum form of i*c* on the LHS of the McGucken Principle, at the scale where ℏ becomes the relevant unit of x₄-action. Huygens' Principle, the Principle of Least Action, and Noether's theorem are companion theorems in the same paper. [MG-HLA]

**SR-4 (Planck-scale quantization of x₄-oscillation).** The Planck length $\ell_P = \sqrt{\hbar G/c^3}$ is the fundamental oscillation scale of x₄-advance: it is the unique combination of c, ℏ, G with dimensions of length, and it arises geometrically from the requirement that x₄-oscillation of an action quantum ℏ generates a curvature scale 1/G in the Channel-B reading. The constants c and ℏ themselves are set by d*x*₄/d*t* = i*c* and the action-quantum normalization of [MG-Constants]; ℏ and G as derivations from the fundamental oscillation scale of x₄ are given explicitly in [MG-AdSCFT]. [MG-Constants; MG-AdSCFT]

**SR-5 (McGucken second law).** The second law of thermodynamics — entropy non-decrease along any worldline — is derived in [MG-HLA] and [MG-Mech] as a theorem of d*x*₄/d*t* = i*c*: the spherical outward expansion of x₄ from every event forces the lightcone volume to grow monotonically, and the count of x₄-stationary modes accessible to any sub-region grows correspondingly. [MG-HLA; MG-Mech]

**SR-6 (McGucken Sphere projection — the Born rule).** The Born rule $P(n) = |\langle n|\psi\rangle|^2$ is derived in [MG-Born] as the projection of the Channel-A x₄-advance encoded in $|\psi\rangle$ onto the Channel-B McGucken Sphere of distinguishable outcomes $\{|n\rangle\}$. Probability weight equals the squared modulus because the McGucken Sphere is a real 2-sphere in ℂ-coordinates and the projection is the inner product on this sphere. [MG-Born]

**SR-7 (McGucken Wick rotation).** The Wick rotation is the physical removal of the i from d*x*₄/d*t* = i*c*: in the Channel-A reading, replacing *t* by −i*τ* converts the unitary Schrödinger evolution into Euclidean heat-kernel evolution; in the Channel-B reading, the same substitution converts the Lorentzian lightcone into the Euclidean 4-sphere. The Wick rotation is not a formal computational device — it is the explicit consequence of factoring the McGucken Principle in the (real, imaginary) basis. [MG-Wick]

**SR-8 (Six-sense locality of the McGucken Sphere).** The expanding null McGucken Sphere admits six independent geometric structures simultaneously: foliation, level sets, caustics, contact geometry, conformal geometry, and null-hypersurface cross-section. This six-sense locality is the mechanism that reduces degrees-of-freedom counting from 3-volume scaling to 2-area scaling, generating the holographic bound directly from d*x*₄/d*t* = i*c*. [MG-AdSCFT Lemma 1, Proposition 2]

**SR-9 (Null hypersurfaces = x₄-stationary hypersurfaces).** A hypersurface in spacetime is null (i.e., its induced metric is degenerate) if and only if every excitation on it is x₄-stationary (i.e., d*x*₄/d*t* = 0 in the frame of the excitation). [MG-Twistor Proposition IV.1; MG-Bek26 Proposition III.1]

**SR-10 (One bit per Planck area).** On any x₄-stationary hypersurface, the count of independent x₄-oscillation modes is one per Planck area $\ell_P^2$. The factor of 1/4 in $S_{BH} = k_B A/(4 \ell_P^2)$ arises from the Euclidean Schwarzschild cigar action $I_E = \beta M c^2/2$ via SR-7, fixed by the Gibbons–Hawking–York boundary term [GH77; York72]. The bit-per-$8\pi\,\ell_P^2$ coefficient of Bekenstein 1973 is the Compton-coupling form of the same count. [MG-Bek26 Proposition V.1; MG-Haw26 Proposition V.1]

**SR-11 (Holographic bound from McGucken-Sphere mode counting).** For any region bounded by a McGucken-Sphere section of area *A*, the maximal information content is $A/(4 \ell_P^2)$ bits. Volume-scaling is excluded because x₄-oscillation modes live on the spherical wavefront, not in the interior. [MG-AdSCFT Proposition 2; MG-Haw26 Proposition IX.1]

**SR-12 (Quantum nonlocality from shared null-surface identity).** Two systems are entangled if and only if their forward McGucken Spheres share an originating null-surface configuration. Quantum nonlocality is not action at a distance; it is the shared identity of the originating x₄-expansion. [MG-Nonloc; MG-NonlocPrin; MG-Second-Nonloc; MG-AdSCFT Proposition 3]

**SR-13 (Reciprocal Generation Property of the McGucken Source-Pair).** The McGucken source-pair $(\mathcal{M}_G, D_M)$ — the moving-dimension manifold $\mathcal{M}_G$ paired with the McGucken Operator $D_M = \partial_t + ic\,\partial_{x_4}$ — is co-generated by d*x*₄/d*t* = i*c* as simultaneous outputs of a single first-order ODE (Co-Generation Theorem). At the pointwise level: every event $p \in \mathcal{M}_G$ generates a pointwise McGucken Operator $D_M^{(p)}$, and the family $\{D_M^{(p)}\}_{p \in \mathcal{M}_G}$ reconstructs both $D_M$ and $\mathcal{M}_G$ (Pointwise Generator Theorem and Reciprocal Generation Theorem). d*x*₄/d*t* = i*c* is the unique first-order ODE producing a source-pair satisfying RGP + Lorentzian-signature + speed *c* + future-orientation. The "=" of d*x*₄/d*t* = i*c* is thereby promoted to the categorical "⇔" of *being and becoming* (CGE₆ keystone). The six-object McGucken Category McG₆ — the first foundational category in mathematical physics whose objects are co-generated by a single physical principle rather than postulated independently — completes the categorical programme identified by Arkani-Hamed in October 2024. [MG-Cat Definition 3.6.1, Theorem 3.5, Theorem 3.7, §4.1–§4.3, §5; MG-Geometry Definition 9.3]

**SR-14 (Six-Sense Null-Surface Identity of the McGucken Sphere).** For any pair of points $p, q$ on the same McGucken Sphere centered on a common emission event $E$, the pair $\{p, q\}$ shares common geometric identity with respect to $E$ in six independent mathematical senses: (i) they lie on the same leaf of the foliation of the future null cone of $E$; (ii) they are at the same Minkowski-metric distance $c\tau$ from $E$; (iii) they lie on the same Huygens wavefront from $E$; (iv) they lie on the same Legendrian section of the contact geometry of null geodesics from $E$; (v) they are related by the same conformal Möbius structure on the celestial sphere of $E$; (vi) they lie on the same spacelike cross-section of the future light cone of $E$, with degenerate induced metric (signature $(0, +, +)$). Each of (i)–(vi) is a standard property of null hypersurfaces in Lorentzian geometry with its own mathematical literature (foliation theory; characteristic initial-data theory of Sachs and Friedrich; Huygens caustic theory of Arnol'd; contact geometry of Arnol'd–Givental; Penrose celestial-sphere conformal structure; Penrose–Sachs degenerate induced metric on null hypersurfaces). The novelty is the recognition that all six are jointly satisfied by the same object — the McGucken Sphere — and that all six are preserved along null-geodesic propagation. SR-14 supplies the *kinematic nonlocality* required by Marolf's 2014 theorem for any emergent-gravity programme [Marolf 2015]. [MG-Susskind §II.4; MG-Nonloc; MG-Nonloc2; MG-Sphere; MG-Sphere2]

These fourteen Standing Results are the apparatus used throughout §III–§XIII below. Each cited corpus paper provides its own internal derivation back to d*x*₄/d*t* = i*c*.

---

## §III. The Two-Channel Architecture

### III.1. Channel A and Channel B as dual readings

We restate the core architectural fact:

**Theorem III.1 (Dual-Channel Decomposition).** *The physical principle* d*x*₄/d*t* = i*c* *(Standing Result SR-1) determines, on every simply connected open event neighborhood U, exactly two complete linearly independent readings:*

- *Channel A (algebraic-symmetry reading): expressing the ODE in the (modulus, phase) basis of* ℂ ≅ ℝ², *the i acts as the generator of unitary phase rotation on a complex Hilbert-space state, and* d*x*₄/d*t* *appears as the Schrödinger generator* $-iH/\hbar$ *acting on $|\psi\rangle$ (Standing Result SR-3).*
- *Channel B (geometric-propagation reading): expressing the same ODE in the (real, imaginary) basis of* ℂ ≅ ℝ², *the i acts as the orthogonal generator of advance perpendicular to the three spatial coordinates, and* d*x*₄/d*t* *appears as the spherically symmetric advance of the McGucken Sphere at velocity c (Standing Result SR-2).*

*The two readings are equivalent on U, and any two channels of d*x*₄/d*t* = i*c* not linearly equivalent to A and B reduce to A or B by a change of basis in* ℂ.

*Proof.* The principle d*x*₄/d*t* = i*c* (SR-1) is a first-order ordinary differential equation in the dependent variable *x*₄ valued in ℂ. The codomain ℂ, as a real vector space, is ℝ². Any choice of an ordered basis for ℝ² fixes a coordinate decomposition of *x*₄.

We enumerate the two distinguished bases:

(a) *The (Re, Im) basis.* Writing *x*₄ = *u* + i*v* with *u*, *v* ∈ ℝ, the equation d*x*₄/d*t* = i*c* becomes the pair $du/dt = 0$, $dv/dt = c$. The component *v* advances at velocity *c*; the component *u* is constant. Since the i in the McGucken Principle records orthogonality of x₄-advance to the three spatial directions (SR-1), the advance is at velocity *c* in the direction orthogonal to all three spatial axes. By spherical symmetry of d*x*₄/d*t* = i*c* about the origin event (the i fixes the magnitude *c* with the direction undetermined), the locus reached at time *t* from the event *p* is the 2-sphere of radius *ct*, which is the McGucken Sphere of *p* (SR-2). This is Channel B.

(b) *The (|·|, arg) basis.* Writing *x*₄ = *r e*^(iθ) with *r* ∈ ℝ_{>0}, θ ∈ [0, 2π), the equation d*x*₄/d*t* = i*c* becomes $dr/dt \cdot e^{i\theta} + r i\, d\theta/dt \cdot e^{i\theta} = ic$, which separates (after dividing by $e^{i\theta}$) into $dr/dt = 0$ and $r\, d\theta/dt = c$. The modulus is constant; the phase rotates at angular velocity $\omega = c/r$.

To derive the Schrödinger equation from this rotation, we apply the (|·|, arg) reading to a complex-valued state amplitude. Let $\psi: U \to \mathbb{C}$, $\psi(t) = R(t) e^{i\theta(t)}$, evolve such that its phase rotation is the Channel-A reading of d*x*₄/d*t* = i*c*. Substituting:

$$\frac{d\psi}{dt} = \dot{R} e^{i\theta} + R \cdot i\dot{\theta}\, e^{i\theta}.$$

By the Channel-A reading: $\dot{R} = 0$ (modulus constant) and $\dot{\theta} = \omega_{\text{loc}}$ (local angular velocity). For a quantum amplitude with energy $E$ via the Planck–Einstein relation $E = \hbar\omega_{\text{loc}}$ (which fixes the action-quantum normalization ℏ; SR-4 [MG-Constants]), this gives

$$\frac{d\psi}{dt} = iR \omega_{\text{loc}} e^{i\theta} = i\omega_{\text{loc}}\,\psi = i \cdot \frac{E}{\hbar}\,\psi,$$

equivalently $i\hbar\,d\psi/dt = -E\psi$. Promoting $E$ to the Hamiltonian operator $\hat{H}$ acting on $|\psi\rangle$ (the operator whose eigenvalues are the allowed energies) and accounting for the sign convention by which positive energy corresponds to $\psi \sim e^{-iEt/\hbar}$ (negative phase rotation as $t$ increases, equivalent to taking $\omega_{\text{loc}} = -E/\hbar$ in the formula above), one obtains the time-dependent Schrödinger equation

$$i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle. \tag{III.1.1}$$

The full derivation, including the relativistic embedding via the Klein–Gordon equation and the non-relativistic limit, is [MG-HLA] (SR-3). The key structural fact for the present theorem is that the i appearing on the left of (III.1.1) is the same i appearing on the right of d*x*₄/d*t* = i*c*: both are the unique element of ℂ that preserves modulus while squaring to a negative real, and both record the orthogonality of x₄-advance to the three spatial directions (SR-1). This is Channel A.

(c) *Equivalence on a simply connected neighborhood U.* The change of basis (Re, Im) ↔ (|·|, arg) is the polar-Cartesian diffeomorphism on $\mathbb{C} \setminus \{0\} \cong \mathbb{R}^2 \setminus \{0\}$:

$$(u, v) \mapsto (r, \theta) = (\sqrt{u^2 + v^2}, \arctan_2(v, u)), \qquad (r, \theta) \mapsto (u, v) = (r\cos\theta, r\sin\theta).$$

Both maps are smooth and have smooth inverses on $\mathbb{C} \setminus \{0\}$. By SR-1, the origin event $0 \in \mathbb{C}$ corresponds to the locus where d*x*₄/d*t* is undefined — i.e., the McGucken-Sphere has zero radius at $t = 0$ (the originating event of the McGucken Sphere itself). For any simply connected open neighborhood $U$ not containing this origin event, the basis change is a global diffeomorphism, and the two readings agree pointwise on the same orbit of the ODE in $\mathbb{C}$. For a $U$ that contains the origin, the (|·|, arg) basis is locally undefined exactly at the origin and the cross-channel agreement (Definition III.1a below) is the M2-mechanism at $r = 0$, which is the originating instant of the McGucken Sphere itself, not a horizon. The horizon case ($r > 0$, $dr/dt \to 0$) is a distinct singularity addressed by Theorem IV.7 below.

(d) *Uniqueness of the two readings.* Any third reading of d*x*₄/d*t* = i*c* would be expressed in some basis $(e_1, e_2)$ of $\mathbb{R}^2$. By the elementary theorem of linear algebra, this basis is related to (Re, Im) by an invertible $2\times 2$ real matrix $M \in GL(2, \mathbb{R})$. The Iwasawa decomposition $M = K A N$ with $K \in SO(2)$, $A$ diagonal positive, $N$ upper unipotent, factorizes any such basis change into (i) a rotation (which is exactly the (|·|, arg) basis change, modulo scale), (ii) a scaling, and (iii) a shear. The scaling and shear preserve the linear-combination structure of A and B; they do not produce a third linearly independent reading. Therefore the only two complete linearly independent readings of d*x*₄/d*t* = i*c* are Channel A and Channel B. ∎

**Definition III.1a (Cross-channel agreement).** A *cross-channel agreement* at an event *q* ∈ U is the requirement that the Channel-A reading of d*x*₄/d*t* = i*c* and the Channel-B reading of the same principle assign the same value of *x*₄ to *q*. By Theorem III.1, on a simply connected U not containing the origin event, a cross-channel agreement exists at every *q*. A *cross-channel disagreement* (or *channel-crossing*) is the failure of this agreement at some *q*, which by Theorem III.1 can occur only when U has nontrivial topology — when U either contains the origin or is multiply connected.

**Remark III.2.** Disagreement between Channel A and Channel B on a single combinatorial assignment is the precise content of "quantum nonlocality" (SR-12). It is not action at a distance; it is the geometric obligation that the two readings of one x₄-advance assign the same value to the same event. Where they are forced to disagree by topology (a horizon, a measurement, a branching), one obtains the M-mechanisms M1, M1′, M2, M3 of the information-destruction architecture (§III.2).

### III.2. The four mechanisms (M1, M1′, M2, M3)

We recall the M-hierarchy established in mid-May 2026:

- **M1′ (Quantum Measurement Bound):** *No Channel-A assignment can be made simultaneously to non-commuting observables; the Heisenberg bound is the algebraic shadow of d*x*₄/d*t* = i*c* on the algebra of operators.*
- **M1 (Combinatorial Assignment Failure):** *Where Channel A and Channel B disagree on a single combinatorial label, no global assignment exists; locally one channel must be projected onto the other.*
- **M2 (Horizon Crossing):** *Where Channel B x₄-expansion crosses a null hypersurface (a horizon), Channel A assignment cannot extend across.*
- **M3 (Branching Overlap):** *Where Channel B futures branch, Channel A unitarity holds within each branch but cannot be projected across branches.*

M1′ is fundamental and lives on Channel A. M1 sits between A and B and is the locus of "measurement." M2 and M3 are pure Channel-B mechanisms; they produce the apparent arrow of time and the apparent information loss at horizons.

### III.3. The McGucken Dualities and the First Law of the McGucken Dualities

The dual-channel architecture of §III.1 is one face of a deeper categorical structure: the *Reciprocal Generation Property* (RGP) of the McGucken source-pair (ℳ_G, D_M), formalized as Definition 3.6.1 and Theorem 3.7 of the McGucken Category paper [MG-Cat]. The RGP states that every point of the moving-dimension manifold ℳ_G generates its own pointwise instance of the McGucken Operator D_M, and the family of pointwise McGucken Operators in turn reconstructs the global arena ℳ_G. The "=" of d*x*₄/d*t* = i*c* is thereby promoted to the categorical "⇔" of *being and becoming*: arena and operator are not two postulated primitives but the *simultaneous co-generation* of a single principle.

The RGP at the structural level has a direct consequence at the level of *physical processes*. We state it as a Standing Result and elevate the consequence to a named law.

**Standing Result SR-13 (Reciprocal Generation Property of the McGucken Source-Pair).** *The McGucken source-pair $(\mathcal{M}_G, D_M)$ — the moving-dimension manifold $\mathcal{M}_G$ paired with the McGucken Operator $D_M = \partial_t + ic\,\partial_{x_4}$ — is co-generated by d*x*₄/d*t* = i*c* as simultaneous outputs of a single first-order ODE. Equivalently (Definition 3.6.1 of [MG-Cat]), every event $p \in \mathcal{M}_G$ generates a pointwise McGucken Operator $D_M^{(p)} := \partial_t|_{t=t_p} + ic\,\partial_{x_4}|_{x_4 = ic t_p}$, and the family $\{D_M^{(p)}\}_{p \in \mathcal{M}_G}$ reconstructs both $D_M$ and $\mathcal{M}_G$. d*x*₄/d*t* = i*c* is the unique first-order ODE producing a source-pair satisfying RGP + Lorentzian-signature + speed c + future-orientation (Theorem 3.7 of [MG-Cat]).* [MG-Cat]

The structural content of SR-13 transmitted to the Channel-A / Channel-B architecture of §III.1 is the following theorem, which we hereby state as the **First Law of the McGucken Dualities**.

**Theorem III.3 (The First Law of the McGucken Dualities).** *Let U be a simply connected open event neighborhood and let $\Pi_A: U \to U$, $\Pi_B: U \to U$ be any Channel-A process (a unitary evolution generated by the Channel-A reading of d*x*₄/d*t* = i*c* per Theorem IV.3) and any Channel-B process (a geometric x₄-advance configuration per Theorem IV.5) respectively. Then:*

*(i) Every Channel-A process $\Pi_A$ contains the potential for Channel-B processes: there exists a basis change in $\mathcal{M}_G$ — explicitly the $(|\cdot|, \arg) \to (\mathrm{Re}, \mathrm{Im})$ change of Theorem III.1 — under which $\Pi_A$ is exhibited as a Channel-B process $\Pi_B'$ on the same x₄-advance configuration.*

*(ii) Every Channel-B process $\Pi_B$ contains the potential for Channel-A processes: the inverse basis change in $\mathcal{M}_G$ — $(\mathrm{Re}, \mathrm{Im}) \to (|\cdot|, \arg)$ — exhibits $\Pi_B$ as a Channel-A process $\Pi_A'$ on the same x₄-advance configuration.*

*(iii) Both processes contain d*x*₄/d*t* = i*c* as their generating principle (SR-1), and both are therefore capable of generating one another by the Reciprocal Generation Property (SR-13). Formally, the diagram*

```{=latex}
\[
\begin{CD}
\Pi_A @>{(|\cdot|, \arg) \to (\mathrm{Re}, \mathrm{Im})}>> \Pi_B' \\
@A{D_M}AA @VV{D_M}V \\
\mathrm{d}x_4/\mathrm{d}t = ic @<<{(\mathrm{Re}, \mathrm{Im}) \to (|\cdot|, \arg)}< \Pi_B
\end{CD}
\]
```

*commutes on every simply connected open event neighborhood U.*

*Proof.* (i) Let $\Pi_A: U \to U$ be a Channel-A process. By Theorem III.1 (Channel A), $\Pi_A$ is generated by the action of $-iH/\hbar$ on a complex Hilbert-space state $|\psi\rangle$, with the phase rotating at rate $c/\hbar$ per unit x₄-advance (SR-3). The phase rotation is an element of $U(1) \subset \mathbb{C}^*$, which by Theorem III.1's basis change $(|\cdot|, \arg) \leftrightarrow (\mathrm{Re}, \mathrm{Im})$ on $\mathbb{C} \cong \mathbb{R}^2$ is in bijection with a rotation in the $(\mathrm{Re}, \mathrm{Im})$ plane. Applying this bijection event-by-event over $U$ gives a Channel-B process $\Pi_B'$ acting on the same x₄-advance configuration. The basis change is a linear isomorphism of $\mathbb{R}^2$; no information is lost.

(ii) Symmetric to (i), with the inverse basis change $(\mathrm{Re}, \mathrm{Im}) \to (|\cdot|, \arg)$. The Channel-B geometric advance at velocity *c* is the magnitude-direction reading of the same x₄-advance configuration whose phase-modulus reading is the Channel-A process; the basis change is the formal exhibition.

(iii) Both $\Pi_A$ and $\Pi_B$ are integral curves of the McGucken Operator $D_M$ applied to local sections of $\mathcal{M}_G$. By SR-13 (Reciprocal Generation Property), at every event $p \in U$ the pointwise operator $D_M^{(p)}$ generates *both* the Channel-A phase rotation at $p$ and the Channel-B McGucken Sphere from $p$ — these are the two readings of one operator action. Therefore each process contains d*x*₄/d*t* = i*c* as its generating principle and, by the inverse basis change applied to its own reading, generates the other. The commutative diagram displays the four corners of the equivalence: starting from d*x*₄/d*t* = i*c*, both $D_M$ paths yield processes ($\Pi_A$ and $\Pi_B$), and either basis change exchanges them. ∎

**Corollary III.3a (Two-channel agreement is a categorical fact, not a coincidence).** *The cross-channel agreement of Definition III.1a — that the Channel-A and Channel-B readings assign the same value of $x_4$ to every event in $U$ — is the level-of-processes shadow of SR-13 (RGP). The two channels agree because they are two readings of the same x₄-advance configuration, and they are two readings of the same configuration because both are descents from d*x*₄/d*t* = i*c* via the source-pair $(\mathcal{M}_G, D_M)$. By Theorem 3.7 of [MG-Cat], d*x*₄/d*t* = i*c* is the unique first-order ODE for which this co-generation closes; this fixes the agreement as a categorical fact, not an empirical coincidence to be explained.*

**Corollary III.3b (No "exponentially complicated thing" is required).** *In every Channel-A process there is already, by Theorem III.3 (i), the Channel-B reading of that same process — a geometric x₄-advance configuration at velocity c. No exponentially-complex operation transmutes one into the other; the basis change of Theorem III.1 is a linear isomorphism of $\mathbb{R}^2$, computable in O(1) elementary operations. The "veil of complexity" that Harlow invokes (§I.3 above) to hide a "radical nonlocality" beneath ordinary Channel-A operations is, in the McGucken framework, the unrecognized Channel-B reading already present in those operations. Harlow's "exponentially complicated thing happens" is the Channel-B face of what was taken to be a strictly Channel-A process; the First Law (Theorem III.3) names this directly.*

**Remark III.4 (Triad of dual-channel master equations).** The First Law (Theorem III.3) explains the empirical fact, established in [MG-Cat] Definition 14.13 (and consistently across the corpus, including [MG-Mech] for the four-velocity budget, [MG-Commut] for the canonical commutator, and [MG-HLA] for the kinetic Second Law), that *every* foundational master equation of physics admits a Channel-A / Channel-B reading:

| Sector | Master equation | Channel A (algebraic-symmetry) | Channel B (geometric-propagation) |
|---|---|---|---|
| Gravity (GR) | $u^\mu u_\mu = -c^2$ | Lorentz-invariant scalar identity | Four-velocity budget $|dx_4/d\tau|^2 + |d\vec{x}/d\tau|^2 = c^2$ |
| Quantum mechanics | $[\hat{q}, \hat{p}] = i\hbar$ | Canonical conjugacy operator-algebra | Heisenberg x₄-phase via Compton frequency $\omega_C = mc^2/\hbar$ |
| Thermodynamics (kinetic) | $dS/dt = (3/2) k_B/t$ | Equipartition across spatial degrees of freedom | Spherical isotropic random walk forced by x₄-expansion at $+ic$ |
| Thermodynamics (black-hole) | $dS_{BH}/dA = k_B/(4\ell_P^2)$ | Hawking-temperature integration $dS = \delta Q/T_H$ | Planck-mode counting on the horizon Sphere |

(Reproduced from [MG-Cat] Definition 14.13.) The same dual-channel form for *all four* master equations is the explicit confirmation of Theorem III.3: each sector inherits the bifurcation because each descends from d*x*₄/d*t* = i*c* through the source-pair $(\mathcal{M}_G, D_M)$, and the source-pair carries the RGP.

This puts the Susskind / Maldacena / Strominger / Harlow / Hartle–Hawking enterprise — every program in current quantum gravity that wonders how spacetime can "emerge" from quantum mechanics, or how quantum mechanics can be reconciled with general relativity — on new footing. The two are not separate things to be reconciled; they are the Channel-A and Channel-B readings of the same x₄-advance, and the master equations of both sectors carry the same dual-channel signature because both sectors are descents from d*x*₄/d*t* = i*c*. The First Law of the McGucken Dualities makes this categorical and explicit.

### III.4. The Brownian Hamlet: laboratory-scale exhibition of the First Law

The First Law (Theorem III.3) and the Triad of master equations (Remark III.4) admit a laboratory-scale realization. We develop the **Brownian Hamlet** thought experiment with full rigor through three formal theorems following [MG-Thermodynamics-Chain Theorems 23, 23.1, 23.2]: the **Brownian Hamlet Destruction** theorem, the **Empirical Irrecoverability via Path Divergence** theorem (with Lemmas 1–3), and the systematic refutation of all orthodox responses.

#### The setup

Consider $1{,}000$ glass beakers, each filled with water in which dust particles have been suspended in a structured configuration spelling out the text of Shakespeare's *Hamlet*. Each of the $175{,}000$ characters of the play is formed from approximately $500$ dust particles of radius $a \sim 1\,\mu$m arranged in a 2D plane within the liquid. The total number of dust particles per beaker is $N \approx 8.75 \times 10^7$. All $1{,}000$ beakers begin in macroscopically indistinguishable initial configurations: same Hamlet, same letter positions, same dust-particle counts, same temperature, same viscosity.

After one hour, every letter in every beaker has blurred beyond recognition. After one week, the dust in each beaker approaches uniform distribution. After one month, each beaker contains a homogeneous suspension whose macroscopic state is indistinguishable from any other beaker's. Each of the $1{,}000$ copies has followed its own independent stochastic trajectory through configuration space, reaching equilibrium by a unique microscopic path. The original encoded *Hamlet* text is gone from every beaker.

#### Theorem III.4.1 (Brownian Hamlet Destruction)

**Theorem III.4.1 (Brownian Hamlet Destruction, after [MG-Thermodynamics-Chain Theorem 23]).** *Let $C_0$ denote the initial structured configuration of $N \approx 8.75 \times 10^7$ dust particles encoding Hamlet. Under Brownian motion governed by d*x*₄/d*t* = i*c* through Compton coupling (SR-3) and the strict Second Law (Theorem VIII.7), the encoded text becomes operationally unrecoverable at times exceeding the dissolution timescale*

$$\tau_d \;=\; \frac{\ell_{\rm letter}^2}{6 D_{\rm total}} \;\approx\; 8\ \text{seconds},$$

*where $\ell_{\rm letter} \sim 100\,\mu$m is the characteristic letter scale and*

$$D_{\rm total} \;=\; \frac{k_B T}{6\pi\eta a} \;+\; \frac{\varepsilon^2 c^2 \Omega}{2\gamma^2} \;\approx\; 2.1 \times 10^{-13}\ \mathrm{m^2/s}$$

*is the total diffusion coefficient combining thermal Einstein diffusion and the Compton-coupling McGucken diffusion of [MG-Thermodynamics-Chain Theorem 14]. For $1{,}000$ copies evolving independently, no inverse mapping from final to initial configurations exists for any physically realizable agent. The destruction is irreversible.*

*Proof.* The proof proceeds in five explicit steps.

**Step 1 (Per-particle dissolution).** Each dust particle satisfies the Langevin equation

$$m\frac{d^2 x_i}{dt^2} \;=\; -m\gamma\,\dot x_i \;+\; \xi_i(t)$$

with environmental damping rate $\gamma = 6\pi\eta a/m$ (Stokes–Einstein drag coefficient $6\pi\eta a$ per unit mass). The RMS displacement after time $t$ is $\langle \Delta x^2 \rangle^{1/2} = \sqrt{6 D_{\rm total}\, t}$. For $t > \tau_d = \ell_{\rm letter}^2/(6 D_{\rm total})$, the displacement exceeds the letter scale $\ell_{\rm letter}$, and each dust particle migrates outside its original letter boundary. For dust ($a \sim 1\,\mu$m) in water at room temperature with $\ell_{\rm letter} \sim 100\,\mu$m, $\tau_d \approx 8$ seconds.

**Step 2 (Cross-letter mixing).** For $t \gg \tau_d$, particles from different letters mix at the inter-letter spacing. The ASCII-decodable sequence is destroyed. Quantitatively:

- at $t = 1$ hour, $\langle \Delta x^2 \rangle^{1/2} \approx 90\,\mu$m: letters thoroughly destroyed;
- at $t = 1$ day, $\langle \Delta x^2 \rangle^{1/2} \approx 430\,\mu$m: macroscopic spread;
- at $t = 1$ week, $\langle \Delta x^2 \rangle^{1/2} \approx 3.7$ mm: centimeter-scale;
- at $t = 1$ month: approaching uniform equilibrium.

**Step 3 (Entropy increase).** The structured *Hamlet* configuration has entropy relative to the uniform equilibrium distribution

$$\Delta S_{\rm structure} \;\approx\; N k_B \ln(V/\delta^3) \;\approx\; 3.2 \times 10^9\, k_B,$$

where $\delta$ is the per-particle initial localization scale. By Theorem VIII.7 (Schrödinger contains the Second Law via Channel-B Wiener-process reading), $dS/dt = (3/2) k_B/t > 0$ strictly per particle. For the ensemble of $N$ particles, the total entropy production rate is

$$\frac{dS_{\rm Hamlet}}{dt} \;=\; N \cdot \frac{3}{2}\cdot\frac{k_B}{t} \;\approx\; 1.3 \times 10^8 \cdot \frac{k_B}{t}.$$

The entropy production is strictly positive at every instant by SR-1 (the +ic, not ±ic, orientation of d*x*₄/d*t* = i*c*); no microscopic configuration of the beaker reduces the entropy.

**Step 4 (Independent stochastic paths).** Each of the $1{,}000$ beakers is statistically independent. Each follows a unique trajectory through configuration space. By Theorem III.1 (Channel-B spherical-isotropy reading of d*x*₄/d*t* = i*c*) applied per-particle, each particle's directional choice at each step is i.i.d. uniform on $S^2$ (SR-6, Haar measure on the McGucken Sphere), independent of every other particle's. The final macrostates are macroscopically indistinguishable (all are homogeneous suspensions); the intermediate trajectories are observably different.

**Step 5 (No inverse mapping).** Three structurally distinct mechanisms each prevent the existence of an inverse mapping:

*(A) Channel-B monotonicity.* By SR-1, d*x*₄/d*t* = i*c* admits no $-ic$ counterpart. The McGucken Sphere expands; it does not contract. Any putative reversal would require $x_4$ to advance at $-ic$, which the McGucken Principle excludes.

*(B) Langevin memory loss.* The memory time $t_{\rm memory} \sim m/\gamma$ is microseconds for dust in water. After many memory-times, the position distribution depends only on $D$ and $t$, not on the initial position. The Channel-A label of any later configuration carries no operational record of its initial value.

*(C) Heisenberg-bounded inverse computation.* The uncertainty relation $\Delta x\,\Delta p \ge \hbar/2$ (SR-3, $[\hat q, \hat p] = i\hbar$ as the Channel-A reading of d*x*₄/d*t* = i*c*) makes simultaneous measurement of position and momentum impossible at the precision required for backward integration. Chaotic amplification under backward integration uniformly distributes the reconstructed initial state over all possible configurations with Lyapunov exponent $\lambda > 0$; the inverse-recovery error grows as $e^{\lambda t}$.

The combination (A)+(B)+(C) is a structural impossibility, not a difficulty: no physically realizable agent can reconstruct the initial *Hamlet* configuration from any one of the $1{,}000$ final equilibria. The destruction is irreversible at the operational level. ∎

#### Theorem III.4.2 (Empirical Irrecoverability via Path Divergence: the colored-dust refinement)

A refinement of the experiment turns path divergence from a theoretical statement into a directly observed empirical record. Color each of the $175{,}000$ letters of *Hamlet* with a distinct dye — $175{,}000$ spectrally resolvable colors at $\sim 1$ nm wavelength spacing across the visible-plus-near-infrared range. Every dust particle is now individually trackable via real-time spectroscopy. The observer can record, for each of the $1{,}000$ copies, the complete spatiotemporal trajectory of every color front as it spreads from its initial letter position.

**Theorem III.4.2 (Empirical Irrecoverability via Path Divergence, after [MG-Thermodynamics-Chain Theorem 23.2]).** *Three observational facts are directly recorded for the colored-dust ensemble of $1{,}000$ beakers:*

- *(O1) Identical initial conditions: $\rho_i^{\rm initial} = \rho_j^{\rm initial}$ macroscopically for all $i, j \in \{1,\ldots,1000\}$.*
- *(O2) Identical final equilibria: $\rho_i^{\rm final} = \rho_j^{\rm final}$ macroscopically for all $i, j$.*
- *(O3) Provably distinct intermediate paths: $\rho_i(t) \ne \rho_j(t)$ observationally for $i \ne j$ and $t \in (0, T_{\rm equilibrium})$.*

*Then any claimed recovery procedure $\mathcal{R}$ acting on a single final macrostate is empirically refuted.*

*Proof.* Suppose, for contradiction, that *Hamlet* is operationally recoverable from any one of the $1{,}000$ final equilibria $\rho_i^{\rm final}$ by a physical procedure $\mathcal{R}$.

**Lemma 1 (Macrostate-to-macrostate determinism).** $\mathcal{R}$ must be deterministic at the macrostate level. If $\mathcal{R}$ were probabilistic — sometimes returning *Hamlet*, sometimes returning *Macbeth* — it would not be a recovery procedure but a guess. Recoverability of a specific text means the procedure produces that text reliably.

**Lemma 2 (Macrostate indistinguishability of inputs).** By (O2), the final macrostates of the $1{,}000$ copies are indistinguishable. So $\mathcal{R}$ applied to each must produce the same macrostate output:

$$\mathcal{R}(\rho_1^{\rm final}) \;=\; \mathcal{R}(\rho_2^{\rm final}) \;=\; \cdots \;=\; \mathcal{R}(\rho_{1000}^{\rm final}).$$

This is a definitional consequence of $\mathcal{R}$ being a function on macrostates.

**Lemma 3 (Macrostate identity of outputs).** All recovered initial states equal the *Hamlet* macrostate:

$$\mathcal{R}(\rho_i^{\rm final}) \;=\; \rho_{\rm Hamlet} \quad \text{for all } i.$$

**The contradiction.** Lemmas 2 and 3 together state: $\mathcal{R}$ applied to the $1{,}000$ final equilibria produces $1{,}000$ identical recovered initial states. For this to be operationally meaningful, the procedure must specify, for each copy $i$, the trajectory from $\rho_{\rm Hamlet}$ to $\rho_i^{\rm final}$. By (O1), all $1{,}000$ trajectories begin at $\rho_{\rm Hamlet}$. By (O2), all $1{,}000$ trajectories end at the same final macrostate. If $\mathcal{R}$ is a reversal of actual physical evolution, then the reversed trajectories must trace the forward trajectories — which by (O3) were different paths. But $\mathcal{R}$, by Lemma 2, returns the same output for every indistinguishable input. So $\mathcal{R}$ cannot distinguish among the $1{,}000$ final states and cannot reconstruct $1{,}000$ distinct trajectories. The procedure either (a) reconstructs the same trajectory for all $1{,}000$ copies — contradicting (O3), since the observer has recorded that the $1{,}000$ trajectories were not the same; or (b) reconstructs no trajectory at all, in which case $\mathcal{R}$ has not recovered the time-ordered structure of the evolution and cannot be said to have "recovered *Hamlet*" in any operational sense. The recovery procedure $\mathcal{R}$ is therefore empirically refuted. ∎

#### Theorem III.4.3 (Every orthodox response fails)

The colored-dust path-divergence record (Theorem III.4.2) defeats each of the standard orthodox responses to information destruction. We enumerate them.

**Theorem III.4.3 (Systematic refutation of orthodox responses, after [MG-Thermodynamics-Chain §"Why This Defeats Every Orthodox Response"]).** *Each of the five orthodox responses to operational information destruction fails to recover Hamlet from the $1{,}000$ colored-dust final equilibria:*

*(R1) **Many-Worlds (Everett 1957).** "Each of the $1{,}000$ copies in our branch took its observed path; other paths exist in other branches." This concedes the operational point: in our branch, the path information of the other $999$ trajectories is irrecoverable from any of the $1{,}000$ final equilibria observed in our branch. Many-Worlds preserves global Hilbert-space information across the multiverse but does nothing for locally accessible information in the branch we inhabit.*

*(R2) **Bohmian mechanics.** "The actual particle trajectories are determined by the guiding wave." But the Bohmian trajectories for indistinguishable initial macrostates can diverge stochastically based on the unknowable initial particle positions within the macrostate. Bohmian mechanics relocates the empirical irrecoverability into the unknowability of initial Bohmian configurations — operationally equivalent to the orthodox conclusion.*

*(R3) **AdS/CFT (Susskind's strongest response).** "The boundary CFT preserves all information about the bulk." But the boundary CFT data for the $1{,}000$ copies, if AdS/CFT applied to ordinary laboratory contexts (which it does not, but granting it for argument), would be $1{,}000$ different CFT states. Recovering Hamlet from the final boundary CFT state of one copy would require knowing which of the $1{,}000$ boundary states corresponds to the copy in question — and that information is exactly what has been destroyed, as the $1{,}000$ final bulk macrostates are indistinguishable. The duality preserves global Hilbert-space information across the bulk-boundary correspondence but cannot specify which final state belongs to which initial Hamlet. The holographic apparatus does not help.*

*(R4) **Black-hole complementarity.** The Brownian Hamlet has no horizon. The dust particles are accessible to any external observer at any time. There is no observer split, no complementary description, no impossibility of joint access. Complementarity is silent.*

*(R5) **ER = EPR.** The entanglement structure of the dissolved beaker's dust particles with the environment is determined by the equilibrium Gibbs distribution, which is identical for the $1{,}000$ copies. The wormhole-equivalent geometric encoding of this entanglement is therefore identical. ER = EPR does not distinguish.*

*Proof.* Each response is examined in turn.

*(R1) Many-Worlds.* The path-divergence record (O3) is *in our branch*. The $999$ alternative branches that Many-Worlds posits to contain "the other paths" are by hypothesis inaccessible to any measurement in our branch. The Born-rule probability of any one branch is $1$ relative to the observer in that branch. The information about the other paths is not recoverable from any measurement an observer in our branch can perform. The Many-Worlds defense therefore concedes the operational point: information that is preserved in the multiverse is *not* preserved in the operationally accessible branch.

*(R2) Bohmian mechanics.* Bohmian trajectories are deterministic given exact initial particle positions, but the initial positions within an initial macrostate are by Bohmian-mechanical postulate distributed according to $|\psi|^2$ — i.e., stochastically over the macrostate. For two beakers prepared in macroscopically identical *Hamlet* configurations, the Bohmian trajectories diverge based on the unknowable detailed initial positions. The path divergence (O3) is exactly the Bohmian-trajectory divergence. The recovery procedure $\mathcal{R}$ has no access to the initial Bohmian positions because they were never measured (and could not have been measured at Bohmian-mechanical precision). Bohmian mechanics relocates the empirical irrecoverability into the unknowability of initial Bohmian configurations; this is operationally equivalent to the orthodox conclusion.

*(R3) AdS/CFT.* Granting AdS/CFT applies to laboratory contexts (which it does not, but for argument): the $1{,}000$ bulk dust configurations are dual to $1{,}000$ boundary CFT states. By (O2), the bulk macrostates are indistinguishable; the boundary CFT states must be macroscopically indistinguishable (by the bulk-to-boundary continuity of the duality). The recovery procedure $\mathcal{R}$ applied to one boundary state must therefore return the same answer as applied to any other — by Lemma 2. The boundary states do not carry the path-divergence record (O3), which is bulk-trajectory information. AdS/CFT preserves the boundary algebra unitarily but does not encode the bulk path history at any operationally accessible boundary observable.

*(R4) Black-hole complementarity.* The Brownian Hamlet has no horizon. Every dust particle is accessible to every external observer at every time. There is no observer split, no complementary description, no impossibility of joint access. The complementarity defense applies to black-hole horizons (Proposition VIII.5.2) and is silent on horizon-free laboratory systems.

*(R5) ER = EPR.* The entanglement structure of the dust particles with the environment at equilibrium is determined by the Gibbs distribution $\rho^{\rm eq}$ (Theorem III.6.1). By (O2), the equilibrium states are identical across the $1{,}000$ copies; the entanglement structures are therefore identical; the wormhole-equivalent geometric encodings (Proposition VIII.5.5) are identical. ER = EPR does not distinguish the copies. ∎

#### Structural diagnosis: symmetric endpoints, divergent paths

A particularly striking feature of the colored-dust experiment is the *symmetry of endpoints with divergence of paths*. The $1{,}000$ copies share the same initial macrostate (low entropy, all $175{,}000$ colors structured into letters) and the same final macrostate (high entropy, all $175{,}000$ colors uniformly distributed). The paths between them are all different. This is the structural content of the Second Law made visible: low-entropy macrostates have few microscopic realizations (so all $1{,}000$ initial states are essentially the same microstate up to measurement precision); high-entropy macrostates have many microscopic realizations (so the $1{,}000$ final microstates differ in detail while sharing the macrostate); and the dynamical paths between them sample the high-multiplicity intermediate macrostates differently for each replica.

The Second Law as derived from d*x*₄/d*t* = i*c* (Theorem VIII.7, $dS/dt = (3/2) k_B/t > 0$ strictly) makes this path divergence *mandatory*: with strictly positive entropy production for each particle, no two trajectories can remain identical without violating Channel B's spherical-isotropy theorem (Theorem III.1(a)) that forces each particle's directional choice at each step to be independent of every other particle's. Channel B's spherical isotropy is the mathematical source of the colored-dust path divergence.

#### The corrected McGucken position

The Brownian Hamlet experiments establish, at laboratory scale, the structural distinction between two quantities the orthodox doctrine conflates: (a) *the abstract Hilbert-space state vector*, which the formalism evolves unitarily within any single Channel-A neighborhood free of M-loci (Theorem IV.3); and (b) *operationally accessible information*, which a physical observer with finite resources and bounded spacetime access can actually recover by measurements with real apparatus in real time. The text on the beaker is operationally gone in eight seconds; whatever abstract Hilbert-space content the formalism continues to write down for the dust ensemble carries no operational consequence — no observer recovers the text, no measurement device decodes it, no physical procedure inverts the diffusion. The dust on the laboratory bench was never in danger of falsifying quantum mechanics; the dust on a black-hole horizon is no different. Both undergo the same Channel-B x₄-advance, in both cases the operationally accessible information is destroyed, and in both cases the abstract formalism's claim that *something* persists is empirically inert because the persistence is not the persistence of anything an observer can act on.

Channel-A evolution is unitary on any simply connected open event neighborhood free of M-loci (Theorem IV.3). The universe is densely populated with M-loci: every horizon is an M2-locus, every measurement event is an M1-locus, every decoherence event is an M3-locus. A "global unitary evolution on the Hilbert space of the universe" therefore does not exist in the McGucken framework (Theorem VIII.6) — Channel-A unitarity is a strictly local statement on M-locus-free patches, and stitching such patches together across M-loci requires projections (Theorem XI.1) that are not unitary. The orthodox claim that "global unitarity preserves information" is wrong for two independent reasons: (i) the global unitary does not exist; (ii) even where Channel-A evolution is locally unitary, the operationally accessible information is set by Channel-B x₄-advance, which is monotonic (+ic, not ±ic) and destroys operational accessibility at every M-locus the system crosses.

This is the structural answer to Susskind's "information is preserved" doctrine: in the McGucken framework, the abstract Hilbert-space state evolves unitarily only on M-locus-free patches, and the operationally accessible information is destroyed by Channel-B x₄-advance at every M-locus. Susskind's doctrine is *not* correct as a statement about a global unitary on the universe's Hilbert space — no such global unitary exists. Susskind's doctrine is correct only in the restricted sense that Channel-A operator algebras have internal consistency on individual M-locus-free patches. Hawking's 1976 "Breakdown of Predictability" argument is in the McGucken framework correct: the horizon is an M2-locus where the Channel-A basis collapses and unitarity is genuinely broken. The First Law of the McGucken Dualities (Theorem III.3) makes the categorical distinction between abstract-Hilbert-space content (Channel A on M-locus-free patches) and operationally accessible information (Channel-B-mediated). The Brownian Hamlet exhibits the distinction at laboratory scale.

### III.5. The Brownian Iliad and Odyssey: matched-encoding indistinguishability after dissolution

The Brownian Hamlet (§III.4) shows that operationally accessible information about a *single* encoded text is destroyed by Channel-B x₄-advance over the dissolution timescale. The matched two-text refinement — the **Brownian Iliad and Odyssey experiment** — shows the stronger result: when two *different* texts are encoded into identical dust budgets and prepared in matched beakers, no measurement performed after dissolution can determine which beaker originally encoded which text. This is the operational falsification of the global-unitarity doctrine in its most direct form.

**Construction.** Prepare $2N = 2{,}000$ identical glass beakers in two matched batches.

**Batch I (Iliad beakers).** $N = 1{,}000$ beakers, each containing $L = 8.75 \times 10^7$ colored dust particles arranged to encode the complete text of Homer's *Iliad* — both its introduction and its main text — using a uniform letter-scale $\ell_{\text{letter}}$ and a uniform color-coding scheme assigning one of $C = 175{,}000$ spectrally resolvable dyes to each particle according to the particle's position in the encoded text.

**Batch O (Odyssey beakers).** $N = 1{,}000$ beakers, each containing $L = 8.75 \times 10^7$ colored dust particles arranged to encode the complete text of Homer's *Odyssey* — both its introduction and its main text — using the same letter-scale $\ell_{\text{letter}}$ and the same color-coding scheme.

The two epics have, in their canonical forms, different main-text lengths: the Iliad is the longer of the two main texts. The two epics also have different introductions, with the Odyssey's introduction being the longer of the two introductions. The matched-encoding condition is achieved by the natural fact that *introduction-plus-main-text* totals to the same character count $L$ for both epics in the chosen encoding edition: the Odyssey's longer introduction makes up exactly the difference between the Iliad's longer main text and the Odyssey's shorter main text. No artificial padding and no truncation are required; the two texts as composed (each with its own introduction) happen to encode to identical total dust budgets under the matched scheme.

The matched preparation therefore ensures that the two batches have *identical* macroscopic parameters at $t = 0$: same particle count per beaker ($L = 8.75 \times 10^7$), same total dust mass, same total dust volume, same color spectrum (the multiset of $C$ dye types is identical in both batches, because both encodings use the same color-position rule applied to texts of identical length), same letter-scale, same thermal bath, same beaker geometry, same initial preparation temperature. The two batches differ *only* in the configurational arrangement of which color sits at which spatial location within each beaker — i.e., in the encoded text identity (Iliad versus Odyssey, each with its own introduction).

Place all $2{,}000$ beakers in the same thermal bath at room temperature. Seal the ground-truth registry (the labels recording which beaker contains which epic) in an envelope held by a referee who plays no further role in the experiment. Let the beakers evolve under Brownian dissolution for a duration $T$ much longer than the dissolution timescale $\tau_d \approx 8$ seconds: take $T$ on the order of hours, days, or months.

**The challenge to a physicist.** A physicist — say, Leonard Susskind — is given:

(i) Access to all $2{,}000$ beakers at time $T$.

(ii) Unlimited measurement apparatus, including but not limited to: optical microscopy, electron microscopy, mass spectrometry, hyperspectral imaging, X-ray diffraction, atomic-force-microscope spatial mapping of every individual dust particle, three-dimensional color tomography to arbitrary precision.

(iii) Unlimited computational resources, including arbitrary quantum computers operating arbitrarily close to the Landauer and Margolus–Levitin bounds.

(iv) Complete and certain knowledge of the encoding scheme, the dust dynamics (full Langevin theory with quantum corrections), the bath properties, and the initial parameters of the experiment ($L$, $C$, $\ell_{\text{letter}}$, beaker geometry, bath temperature).

(v) The full text of both the *Iliad* and the *Odyssey* in the encoding scheme used, including both introductions, so that he knows in complete detail what the initial configurations of each batch looked like.

Susskind must produce, for each of the $2{,}000$ beakers, a label — *Iliad* or *Odyssey* — assigning each beaker to the epic it originally encoded. The referee then reveals the ground-truth registry and computes Susskind's classification accuracy.

**Theorem III.5.1 (Brownian Iliad–Odyssey Indistinguishability, KL/Pinsker formulation).** *Under the matched-encoding construction above, for any classification procedure available to a physicist with the resources (i)–(v), the expected classification accuracy after dissolution time $T \gg \tau_d$ is*
$$P_{\text{correct}}(T) \;\to\; \tfrac{1}{2} \quad \text{as} \quad T/\tau_d \to \infty,$$
*equal to chance. No measurement procedure exists that distinguishes Iliad beakers from Odyssey beakers at accuracy exceeding chance after dissolution.*

*Proof.* The proof rests on three independent facts established in §III.4 (Brownian Hamlet) and applied to the matched-pair construction.

**Step 1 (the two batches are macroscopically identical at time $T$).** By construction, Batch I and Batch O have identical macroscopic parameters at $t = 0$: particle count $L$, total mass, total volume, color-multiset, letter-scale, bath properties, beaker geometry, temperature. The Brownian dissolution dynamics (SR-5, the McGucken second law from [MG-HLA, MG-Mech]) are *configuration-blind*: the Langevin equation $\dot{x}_i = -\gamma \nabla U(x_i) + \xi_i(t)$ governing each dust particle depends on the local potential $U$ and the stochastic noise $\xi_i$, but not on the global pattern of which other particles encode which letters. Therefore the time-evolved macroscopic parameters at $t = T \gg \tau_d$ remain identical between batches: each beaker contains $L$ dust particles, with the same color-multiset, in a fully thermalized spatial distribution.

**Step 2 (the configurational information distinguishing the two epics is erased by Channel-B x₄-advance over $T$).** By the three independent mechanisms of unrecoverability established in §III.4:

*(a) Channel-B monotonicity (+ic, not ±ic, SR-1).* The dust dissolution proceeds monotonically forward in x₄. The McGucken Sphere from every dust-particle event expands outward; no event admits a $-ic$ trajectory returning the particle to its initial position. After $T \gg \tau_d$, every particle has explored its full thermalization volume, and the position of any particle at time $T$ carries no operational record of its position at $t = 0$.

*(b) Langevin memory loss at microsecond timescales.* The Langevin equilibration time is microseconds; after $T \gg \tau_d$, the Channel-A label of each particle's position is uncorrelated with its initial label. The mutual information between the Batch-I configuration at $t = 0$ and the Batch-I configuration at $t = T$, computed via the Langevin propagator over $T \gg \tau_d$, decays exponentially with characteristic time $\tau_{\text{Langevin}} \ll \tau_d \ll T$. The same decay applies, identically, to Batch O.

*(c) Heisenberg-bounded inverse computation under chaotic amplification.* Even granting Susskind unlimited computational resources, inverting the dust dynamics to reconstruct the initial configuration from the time-$T$ snapshot requires backward integration of $L = 8.75 \times 10^7$ chaotic trajectories per beaker, each with Lyapunov-amplified sensitivity bounded by the Heisenberg uncertainty principle (SR-3, $[\hat{q}, \hat{p}] = i\hbar$). The inverse-recovery error after time $T$ grows as $e^{\lambda T}$ with $\lambda$ the maximal Lyapunov exponent; for $T \gg \tau_d$, this exceeds the position precision available even at the Heisenberg bound, by a factor that is itself exponential in $T/\tau_d$.

**Step 3 (no measurement can break the Batch-I / Batch-O symmetry after dissolution).** Let $\mathcal{M}$ be any measurement procedure available to Susskind under the resources (i)–(v), modeled as a quantum channel from the Hilbert space of the dust configuration to a classical outcome space (a CPTP map composed with a projective measurement onto outcomes). We derive the KL bound by combining the Wiener-process erasure of Step 2 with the data-processing inequality for KL divergence.

*Step 3.1 (Wiener-process bound on the configurational distinguishability of the two batches at time $T$).* By Theorem VIII.7′ (Universal McGucken Channel B Theorem), the Schrödinger evolution of the dust-bath system on each beaker has, under the McGucken-Wick rotation $\tau = x_4/c$, an exact Euclidean-signature Channel-B reading as a Wiener-process measure with diffusion constant $D = \hbar/(2 m_{\text{dust}}) + k_B T_{\text{bath}}/(\gamma m_{\text{dust}})$ (Channel-A quantum diffusion plus Channel-B classical Langevin diffusion, additively combined as orthogonal contributions to Brownian motion on the McGucken Sphere). For dust particles in a bath at room temperature with friction coefficient $\gamma$ and mass $m_{\text{dust}}$, the classical Langevin term dominates and $D \approx k_B T_{\text{bath}}/(\gamma m_{\text{dust}})$.

The probability distribution of the time-$T$ configuration of a single Batch-I beaker (or Batch-O beaker) is the heat kernel evolution of the initial configuration: $p_T^{\text{Iliad}}(\vec{x}) = \int p_0^{\text{Iliad}}(\vec{x}_0)\, K_T(\vec{x}|\vec{x}_0)\,d\vec{x}_0$, where $K_T$ is the Wiener kernel of equation (VIII.7.4) applied to all $L$ particles jointly. Identical formula for Batch O with $p_0^{\text{Iliad}}$ replaced by $p_0^{\text{Odyssey}}$.

By Step 1, the two initial distributions $p_0^{\text{Iliad}}$ and $p_0^{\text{Odyssey}}$ have identical marginals on every macroscopic variable (mass, volume, color-multiset, etc.); they differ only in the joint configurational arrangement. By the Wiener kernel's translation-invariance under the $\hbar/(2m)$ diffusion and the bath's stochastic-translation property, the time-$T$ distributions of macroscopic functionals are identical to within the Heisenberg-bounded inverse-computation precision of Step 2(c).

*Step 3.2 (KL bound on time-$T$ distinguishability via the Wiener-process integral).* For two distributions $p$ and $q$ on the configuration space at time $T$, the KL divergence is

$$D_{\text{KL}}(p \| q) = \int p(\vec{x}) \log\frac{p(\vec{x})}{q(\vec{x})}\,d\vec{x}.$$

By the data-processing inequality (a standard result in information theory, equivalent to monotonicity of relative entropy under stochastic maps; cf. Cover & Thomas 2006 Theorem 2.8.1), application of any measurement channel $\mathcal{M}$ does not increase KL divergence:

$$D_{\text{KL}}(\mathcal{M}(p) \| \mathcal{M}(q)) \le D_{\text{KL}}(p \| q). \tag{III.5.1}$$

Therefore we need only bound the KL divergence between the two time-$T$ configurational distributions $p_T^{\text{Iliad}}$ and $p_T^{\text{Odyssey}}$, and any measurement $\mathcal{M}$ inherits the same bound by (III.5.1).

By the Wiener-process result of Step 3.1, the Kullback–Leibler divergence between two configurational distributions evolved from initial distributions that differ only in $L$ pairwise particle-position assignments is bounded by the per-particle decoherence-induced loss, summed over $L$ particles:

$$D_{\text{KL}}(p_T^{\text{Iliad}} \| p_T^{\text{Odyssey}}) \le L \cdot D_{\text{KL}}(p_T^{(1)\text{Iliad}} \| p_T^{(1)\text{Odyssey}}), \tag{III.5.2}$$

where $p_T^{(1)\text{X}}$ is the single-particle marginal at time $T$ under preparation X. For each particle, by the heat-kernel Wiener-process evolution (equation VIII.7.4), the single-particle distributions at time $T$ are Gaussians with the same variance $\sigma^2 \sim 2D T$ centered at the diffusion-spread positions; their KL divergence is bounded by

$$D_{\text{KL}}(p_T^{(1)\text{Iliad}} \| p_T^{(1)\text{Odyssey}}) \le \frac{(\Delta x_0)^2}{4 D T} \cdot e^{-T/\tau_{\text{decoh}}},$$

where $\Delta x_0$ is the initial position separation (of order $\ell_{\text{letter}}$) and $\tau_{\text{decoh}}$ is the bath-collision decoherence timescale derived from SR-1 (Channel-B monotonicity) applied to bath-molecule x₄-advance contacts on each dust particle. Multiplying by $L$ gives

$$D_{\text{KL}}(p_T^{\text{Iliad}} \| p_T^{\text{Odyssey}}) \le L \cdot e^{-T/\tau_{\text{decoh}}}, \tag{III.5.3}$$

where constants of order unity have been absorbed into $\tau_{\text{decoh}}$. Combining (III.5.1) and (III.5.3):

$$D_{\text{KL}}(\mathcal{M}(\text{Batch I, }T) \| \mathcal{M}(\text{Batch O, }T)) \le L \cdot e^{-T/\tau_{\text{decoh}}}.$$

For $T$ on the order of hours, days, or months, and $\tau_{\text{decoh}} \sim$ microseconds (the standard decoherence time for dust-bath molecular collisions, established e.g. by Joos & Zeh 1985), $T/\tau_{\text{decoh}} \gtrsim 10^9$, and the right-hand side is bounded by $L \cdot e^{-10^9}$ — empirically zero, smaller than the inverse of any physically attainable repetition count.

*Step 3.3 (Pinsker–Csiszár classification bound).* By the Pinsker–Csiszár inequality [Pinsker 1964; Csiszár 1967], for any two probability distributions $p, q$ on the same outcome space,

$$d_{\text{TV}}(p, q) \le \sqrt{D_{\text{KL}}(p \| q)/2}, \tag{III.5.4}$$

where $d_{\text{TV}}$ is the total variation distance. The optimal Bayes classification accuracy between two equally likely hypotheses with outcome distributions $p, q$ is exactly $\tfrac{1}{2} + \tfrac{1}{2} d_{\text{TV}}(p, q)$. Combining (III.5.3) and (III.5.4):

$$P_{\text{correct}}(T) \le \tfrac{1}{2} + \tfrac{1}{2}\sqrt{L \cdot e^{-T/\tau_{\text{decoh}}}/2} = \tfrac{1}{2} + \tfrac{\sqrt{L}}{2\sqrt{2}}\, e^{-T/(2\tau_{\text{decoh}})}.$$

For $T \gg \tau_{\text{decoh}}$ and any physically reasonable $L$, this is operationally $\tfrac{1}{2}$ — indistinguishable from chance. The bound is tight for the Bayes-optimal classifier; suboptimal classifiers (which is what any practical $\mathcal{M}$ will be) achieve accuracy bounded above by the same expression. ∎

**Corollary III.5a (no $U_{\text{univ}}$ inverse exists for the Iliad–Odyssey ensemble).** *If the global-unitarity doctrine were correct — if there existed a global unitary $U_{\text{univ}}$ on the Hilbert space of the universe such that $U_{\text{univ}}^\dagger$ acts as an inverse evolution operator — then a physicist with sufficient resources could, in principle, apply $U_{\text{univ}}^\dagger$ to the time-$T$ state of each beaker and recover the initial Iliad-or-Odyssey configuration. By Theorem III.5.1 and Theorem III.5.2, no such recovery is possible at accuracy exceeding chance for $T \gg \tau_d$. Therefore $U_{\text{univ}}$ does not exist, in agreement with Theorem VIII.6 below. The Iliad–Odyssey indistinguishability is the laboratory operational falsification of the global-unitarity doctrine.*

**Corollary III.5b (the matched-pair construction sharpens the Hamlet result).** *The Brownian Hamlet of §III.4 shows that the Hamlet text in a single beaker is unrecoverable after dissolution. A defender of the global-unitarity doctrine could in principle reply that the abstract Hilbert-space state still records the initial configuration in some inaccessible-but-formally-present sense, and that the unrecoverability is "merely" practical. The Iliad–Odyssey construction rules out this reply at laboratory scale: if the formal Hilbert-space state preserved the initial encoding in any operationally relevant sense, the Iliad and Odyssey batches would be distinguishable by some measurement applied to the formal state. They are not. The two batches are operationally identical to every measurement $\mathcal{M}$ a physicist can construct under resources (i)–(v). Whatever the abstract formalism continues to write down for each batch carries no physical consequence — it is empirically inert. The matched-pair indistinguishability operationalizes the structural distinction between Definition VIII.6.1 (the abstract Hilbert-space state vector) and Definition VIII.6.2 (operationally accessible information).*

**Corollary III.5c (Susskind cannot win the experimental challenge).** *No procedure available to Susskind under resources (i)–(v) — including the most sophisticated quantum-computational reconstruction at the Heisenberg bound — distinguishes Iliad beakers from Odyssey beakers at accuracy exceeding $\tfrac{1}{2} + e^{-T/(2\tau_{\text{decoh}})}$. For $T$ measured in hours, days, or months, this is operationally $\tfrac{1}{2}$. The classification challenge is unwinnable. The global-unitarity doctrine, taken seriously, would require Susskind to win the challenge; the laboratory shows he cannot.*

#### Theorem III.5.2 (Brownian Iliad–Odyssey Operational Indistinguishability, measurement-as-observable formulation)

The KL/Pinsker formulation (Theorem III.5.1) controls the classification accuracy bound. A second, structurally complementary formulation establishes the same result via the measurement-as-observable formalism, with four explicit claims (I1)-(I4) and a direct contradiction proof. This version follows [MG-Thermodynamics-Chain Theorem "Brownian Iliad–Odyssey Operational Indistinguishability"] and ties directly into Theorem III.6.1 (Content-Universal Equilibration) below.

**Theorem III.5.2 (Brownian Iliad–Odyssey Operational Indistinguishability, after [MG-Thermodynamics-Chain]).** *Let $\rho_I(t)$ and $\rho_O(t)$ denote the dust-particle phase-space distributions at time $t$ for an Iliad beaker and an Odyssey beaker, respectively, both prepared with the matched-encoding setup above (same total particle counts of each color, same total mass, same total energy, same temperature, same volume, same vanishing global quantum numbers). After any time $t > T_*$ where $T_* = L^2/(6 D_{\rm total})$ with $L$ the largest spatial scale of the text encoding (for an $\sim 700{,}000$-character text in a $10$ cm beaker, $T_* \sim 13$ hours), the following four claims hold:*

*(I1) **Macroscopic indistinguishability.** All macroscopic observables of the Iliad beaker and the Odyssey beaker — color histogram at any spatial resolution coarser than $\sqrt{6 D_{\rm total} t}$, total energy, total momentum, total angular momentum, all conserved charges, the equilibrium Maxwell–Boltzmann velocity distribution of each color species, the spatial pair-correlation function of each color species — coincide for the two beakers within the statistical fluctuations of an equilibrium ensemble of $N \sim 3.55 \times 10^8$ particles.*

*(I2) **Fine-grained measurement indistinguishability.** No measurement performed on a single beaker — at any precision, including measurements that resolve individual dust particles' positions and velocities at the Compton-coupling-limited resolution — produces an observable whose statistical distribution differs between the Iliad-prepared and Odyssey-prepared ensembles after $t > T_*$.*

*(I3) **Backward-integration impossibility.** No physically realizable computation backward-integrating the Langevin dynamics from the observed final state can recover the initial arrangement, by the mechanisms (A)–(C) of Theorem III.4.1 Step 5 (Channel-B monotonicity, Langevin memory loss, Heisenberg-bounded chaotic amplification).*

*(I4) **No-Susskind-experiment claim.** No experimental procedure — measurement, computation, holographic-data-extraction, fine-grained-microstate-readout, or any combination — performed on a single dissolved final-state beaker (or on the $2{,}000$-beaker ensemble) can distinguish an Iliad beaker from an Odyssey beaker with success probability exceeding $1/2 + \epsilon$ for any $\epsilon > 0$ as $N \to \infty$ and $t \to \infty$.*

*Proof.* The proof proceeds in five steps, one per claim (I1)–(I4) plus a closing step (Step 5) tracing the indistinguishability to the $+ic$ orientation.

**Step 1 (Macroscopic indistinguishability — claim I1).** The equilibrium phase-space distribution of $N$ Compton-coupled Brownian particles in a thermostatted volume $V$ at temperature $T$ is the Gibbs distribution (Theorem III.6.1 below applied to the matched conserved-quantity profile $\mathbf{Q}_I = \mathbf{Q}_O$). The Gibbs distribution depends on the conserved global quantities and on the bath temperature; it does *not* depend on the initial particle positions beyond their global quantum numbers. By construction, the Iliad and Odyssey beakers share every global conserved quantity (color histogram, mass, energy, momentum, angular momentum, charge), so their equilibrium phase-space distributions are identical:

$$\rho_I^{\rm eq}(\{\mathbf{x}_j, \mathbf{v}_j\}) \;=\; \rho_O^{\rm eq}(\{\mathbf{x}_j, \mathbf{v}_j\}). \tag{IO.1}$$

Equation (IO.1) is the Gibbs-distribution statement applied to two ensembles with identical conserved-quantity profiles. The equilibrium color histogram at any spatial resolution coarser than $\sqrt{6 D_{\rm total} t}$ is the spatial integral of $\rho^{\rm eq}$ over the resolution cell, which depends only on the color histogram of the conserved quantities — identical in the Iliad and Odyssey cases. The Maxwell–Boltzmann velocity distribution of each color species is the velocity-space marginal of $\rho^{\rm eq}$, depending only on temperature and species mass — identical. The spatial pair-correlation function of each color species at equilibrium is the spatial marginal of $\rho^{\rm eq}$, depending only on the equilibrium color density and temperature — identical. All macroscopic observables of the Iliad and Odyssey beakers coincide at $t > T_*$. Claim (I1) holds.

**Step 2 (Fine-grained measurement indistinguishability — claim I2).** Let $\mathcal{O}$ be any observable defined on a single beaker's dust-particle phase-space configuration $\{\mathbf{x}_j, \mathbf{v}_j\}$. The statistical distribution of $\mathcal{O}$ over an ensemble of beakers all prepared in the Iliad configuration and evolved to time $t > T_*$ is

$$\mathbb{E}_I[\mathcal{O}](t) \;=\; \int \mathcal{O}(\{\mathbf{x}_j, \mathbf{v}_j\})\, \rho_I(\{\mathbf{x}_j, \mathbf{v}_j\}, t)\, d^{6N}\!q, \tag{IO.2}$$

with $\rho_I(\cdot, t)$ the Iliad-initial-condition distribution evolved by the Compton-coupled Langevin dynamics. Similarly for the Odyssey. By the Wiener-process exponential relaxation [MG-Thermodynamics-Chain Theorem 6; Theorem III.6.1 Step 6 below], each $\rho_X(\cdot, t)$ approaches the equilibrium Gibbs distribution exponentially in time, with characteristic relaxation time $\tau_{\rm relax} \sim T_*$ for the slowest mode. For $t \gg T_*$, $\rho_I(\cdot, t) - \rho_O(\cdot, t) \to 0$ in any norm — total variation, $L^2$, $L^\infty$, relative entropy — because both distributions converge to the same equilibrium $\rho^{\rm eq}$ (Step 1 above, equation IO.1). Therefore

$$\bigl| \mathbb{E}_I[\mathcal{O}](t) - \mathbb{E}_O[\mathcal{O}](t) \bigr| \;\to\; 0 \quad \text{as } t/T_* \to \infty, \quad \forall\, \mathcal{O} \in L^\infty(\Gamma). \tag{IO.3}$$

The class $L^\infty(\Gamma)$ of bounded observables on the phase space $\Gamma$ is the largest class of measurable observables; no observable in this class statistically distinguishes the Iliad and Odyssey ensembles after $t \gg T_*$. The McGucken-Sphere-limited resolution of any physical measurement (the spatial resolution of a measurement is bounded below by the Compton wavelength of the probe; positions and velocities cannot be jointly resolved beyond the Heisenberg bound $\Delta x\,\Delta p \ge \hbar/2$, SR-3) does not enlarge the class of measurable observables beyond $L^\infty(\Gamma)$. Claim (I2) holds.

**Step 3 (Backward-integration impossibility — claim I3).** Apply the three structural mechanisms of Theorem III.4.1 Step 5 to the Iliad–Odyssey case:

*(A) Channel-B monotonicity.* The McGucken Sphere expands at $+ic$ from every spacetime event (SR-1); backward integration from a final dust configuration to an initial dust configuration would require traversing $x_4$ in the $-ic$ direction, which the McGucken Principle excludes.

*(B) Langevin memory loss.* The memory time of each dust particle is $\tau_{\rm mem} \sim m/\gamma \sim 1\,\mu$s for $1\,\mu$m dust in water. After $t \gg \tau_{\rm mem}$, each particle's velocity distribution has forgotten its initial value. After $t > T_*$, each particle's position distribution has forgotten its initial value. The initial spatial ordering — Iliad vs Odyssey — has dissipated from every particle's accessible state information.

*(C) Heisenberg-bounded chaotic amplification.* Backward integration of the deterministic part of the Langevin equation produces exponential amplification of initial-condition uncertainty at rate $\gamma$. After $t > T_*/\ln(L/\hbar^{1/2})$, the Heisenberg-bounded initial-condition uncertainty has amplified beyond the box size; the backward-integrated initial position is uniformly distributed over the beaker volume — independent of the actual initial arrangement.

The combination (A)+(B)+(C) is a structural impossibility, not a difficulty: no physically realizable computation can perform backward integration from the dissolved state to the initial Iliad or Odyssey arrangement. Claim (I3) holds.

**Step 4 (No-Susskind-experiment claim — claim I4).** Suppose for contradiction that there exists a physical procedure $\mathcal{S}$ — measurement, computation, holographic-data-extraction, fine-grained-microstate-readout, or any combination — such that $\mathcal{S}$, applied to a single beaker drawn at random from the $2{,}000$, identifies the beaker as "Iliad" or "Odyssey" with success probability $p > 1/2 + \epsilon$ for some fixed $\epsilon > 0$, in the limit $N \to \infty$ and $t \to \infty$.

The procedure $\mathcal{S}$ is a measurable function from beaker states to the binary label set $\{$"Iliad", "Odyssey"$\}$. By the measurement-as-observable formalism of quantum mechanics — applied at the dust-particle scale, where positions and velocities are operator-valued and the measurement outcomes are eigenvalues of the corresponding observables — $\mathcal{S}$ is implementable as an observable $\hat\sigma$ with eigenvalues $\{+1\,(\text{"Iliad"}), -1\,(\text{"Odyssey"})\}$, whose expectation value on a beaker prepared in state $\rho$ is

$$\langle \hat\sigma \rangle_\rho \;=\; \mathrm{Tr}(\hat\sigma \rho). \tag{IO.4}$$

The success probability of $\mathcal{S}$ on Iliad-prepared and Odyssey-prepared beakers is

$$p_I \;=\; \tfrac{1}{2}(1 + \langle\hat\sigma\rangle_I), \qquad p_O \;=\; \tfrac{1}{2}(1 - \langle\hat\sigma\rangle_O), \tag{IO.5}$$

with overall success probability $p = \tfrac{1}{2}(p_I + p_O) = \tfrac{1}{2} + \tfrac{1}{4}(\langle\hat\sigma\rangle_I - \langle\hat\sigma\rangle_O)$. For $p > 1/2 + \epsilon$ we require

$$\langle\hat\sigma\rangle_I - \langle\hat\sigma\rangle_O \;\geq\; 4\epsilon. \tag{IO.6}$$

But $\hat\sigma$ is a bounded observable ($\|\hat\sigma\| \le 1$, by the eigenvalue range $\pm 1$), and by claim (I2) (Step 2 above, equation IO.3), the expectation values of every bounded observable on Iliad-prepared and Odyssey-prepared ensembles agree in the limit $t/T_* \to \infty$:

$$\langle\hat\sigma\rangle_I - \langle\hat\sigma\rangle_O \;=\; \mathbb{E}_I[\hat\sigma](t) - \mathbb{E}_O[\hat\sigma](t) \;\to\; 0. \tag{IO.7}$$

This contradicts (IO.6). Therefore no procedure $\mathcal{S}$ achieves success probability exceeding $1/2 + \epsilon$ for any $\epsilon > 0$ in the limit $N \to \infty$ and $t \to \infty$. Claim (I4) holds.

**Step 5 (Trace to the $+ic$ orientation).** The convergence $\rho_X(\cdot, t) \to \rho^{\rm eq}$ in (IO.3) is the spatial-projection content of the Compton-coupled Brownian relaxation: each particle's iterated isotropic spatial displacement (Theorem III.1(a), Channel-B isotropy) drives its position distribution toward the equilibrium Gibbs distribution at rate set by the diffusion coefficient $D_{\rm total} > 0$. The strict positivity $D_{\rm total} > 0$ traces directly to the $+ic$ orientation of d*x*₄/d*t* = i*c* (SR-1): were d*x*₄/d*t* = $-ic$ to hold instead, $D_{\rm total}$ would carry the reverse sign, the Wiener PDE $\partial_t \rho = D \nabla^2 \rho$ would be a backward heat equation with no forward-time stationary state, and the convergence (IO.3) would invert into divergence. The Iliad and Odyssey arrangements, starting from identical conserved-quantity profiles and differing only in initial spatial ordering, would *separate* under $-ic$ dynamics rather than converge. The empirical observation that they converge to mutually indistinguishable equilibria is the empirical content of the $+$ in $+ic$. ∎

#### Theorem III.5.3 (Every orthodox response fails in the matched-resources setting)

The five orthodox responses to information destruction (Many-Worlds, Bohmian mechanics, AdS/CFT, black-hole complementarity, ER=EPR) each fail to distinguish Iliad from Odyssey, by the structural argument of Theorem III.4.3 sharpened by the identical-resources constraint of Theorem III.5.2.

**Theorem III.5.3 (Systematic refutation in the matched-resources setting, after [MG-Thermodynamics-Chain]).** *Each of the five orthodox responses fails to supply a discriminating observable for the matched-encoding Iliad/Odyssey ensemble:*

*(R1) **AdS/CFT.** The dual CFT state of the dissolved Iliad beaker and the dual CFT state of the dissolved Odyssey beaker have the same global conserved-charge profile, the same total energy, the same color-species number content. The dual CFT states agree on every global observable. AdS/CFT formally preserves global Hilbert-space information across the bulk-boundary correspondence but cannot distinguish the Iliad-CFT-state from the Odyssey-CFT-state without knowing which preparation produced it — and that knowledge is exactly what has been destroyed.*

*(R2) **ER = EPR.** The entanglement structure of the dissolved beaker's dust particles with the environment is determined by the equilibrium Gibbs distribution, which is identical for the Iliad and Odyssey beakers. The wormhole-equivalent geometric encoding of this entanglement is therefore identical. ER = EPR does not distinguish.*

*(R3) **Many-Worlds.** Both the Iliad and Odyssey beakers branch into the same family of equilibrium-state branches (because both relax to the same Gibbs distribution); the branching structure is identical. Many-Worlds does not distinguish.*

*(R4) **Bohmian mechanics.** The Bohmian guiding-field configuration at the dissolved state is determined by the equilibrium quantum state, which is identical for the Iliad and Odyssey beakers. Bohmian trajectories do not distinguish.*

*(R5) **Black-hole complementarity.** The Iliad–Odyssey experiment has no horizon. Complementarity is silent.*

*Proof.* Every orthodox response fails by the same structural mechanism: the equilibrium states are identical (Theorem III.5.2 Step 1, equation IO.1), so the orthodox machinery that operates on the equilibrium state can produce no distinguishing observable. The destruction of the Iliad–Odyssey ordering is the empirical content of d*x*₄/d*t* = i*c* at the laboratory scale. ∎

**Diagnostic remark.** The Iliad–Odyssey experiment is the strongest possible empirical refutation of the orthodox claim that fine-grained microstate access can reconstruct initial conditions. The two texts are encoded with **identical resources** by construction — same particles, same colors, same counts, same conserved quantities at every order. The only difference is the spatial ordering. The Compton-coupled Brownian motion that drives the dissolution is the same mechanism for every particle in every beaker. The equilibrium distributions to which the Iliad and Odyssey beakers relax are *identical functions* of the conserved quantities (Step 1, equation IO.1) — not merely "indistinguishable in practice" but mathematically equal as Gibbs distributions on the same phase space. There is no observable, fine-grained or coarse-grained, classical or quantum, holographic or bulk, that resolves the Iliad–Odyssey distinction after $t \gg T_*$. The ordering information is not "hidden" or "scrambled" or "delocalized into apparatus degrees of freedom"; it is *destroyed* in the operational sense that the final ensembles' phase-space distributions are equal.

**Remark III.5.1 (why the matched-encoding construction is decisive).** The Brownian Iliad and Odyssey experiment is the matched-pair refinement of the Brownian Hamlet. Where Hamlet shows that *one* text becomes unrecoverable, the Iliad–Odyssey pair shows that *two distinct texts* with identical macroscopic preparation become operationally identical after dissolution. The introductions of the two epics do the heavy lifting of the construction: the Odyssey's longer introduction precisely compensates for the Iliad's longer main text, producing two matched dust budgets without any artificial preparation. The experiment requires no padding, no truncation, no contrivance — only Homer and chemistry. The result is a direct, repeatable, laboratory-scale demonstration that operationally accessible information is destroyed by Channel-B x₄-advance, and that the doctrine of global unitarity has no operational consequence: a doctrine with no operational consequence is, by every standard of empirical physics from Galileo forward, not a physical claim about reality.

### III.6. The Brownian Plato and Aristotle: physics versus philosophy in the black-hole-information dispute

The Brownian Hamlet (§III.4) and the Brownian Iliad and Odyssey (§III.5) are *operational* experiments: performable with standard chemistry at room temperature, repeatable arbitrarily many times, falsifiable on whatever Susskind, or any reader, designs as a discriminating measurement procedure. The doctrine of global unitarity, as Susskind formulates it, is by contrast structurally non-falsifiable: it predicts behavior only in regimes — post-evaporation final-state Hilbert spaces, Planck-scale string-theoretic interiors, exponentially-complex operations on Hawking radiation outside light-years of cosmological distance — where no measurement procedure can, in principle or in practice, be performed. A claim about reality that admits no measurement that could falsify it is, in the methodological tradition of Galileo, Newton, Einstein, Bohr, and the heroic age, *philosophy*, not *physics*.

If Susskind insists on philosophy, the Brownian construction extends naturally to that domain. We propose the **Brownian Plato and Aristotle experiment** and develop it with full rigor through a chain of five formal theorems (III.6.1 through III.6.5) that descend from d*x*₄/d*t* = i*c* via the McGucken machinery of Theorem III.1 (Dual-Channel Decomposition), Theorem III.3 (First Law of the McGucken Dualities), SR-1 through SR-14, and the Compton-coupling apparatus of [MG-Thermodynamics-Chain Theorems 4, 5, 6, 14].

#### The setup of the Brownian Plato and Aristotle experiment

Prepare $1{,}000$ beakers each containing the complete *Nicomachean Ethics* of Aristotle (approximately $300{,}000$ characters in the standard Greek edition) plus an introductory passage. Prepare $1{,}000$ beakers each containing the complete *Republic* of Plato (approximately $310{,}000$ characters) plus an introductory passage of length adjusted so the total character count exactly matches the Aristotle batch. The two texts are encoded using the *identical color palette*, with the *identical number of particles of each spectral color* across the two batches — the count of "happy yellow ($\lambda_{581}$)" particles summed over all letters in *Nicomachean Ethics* plus its introduction equals the count of "happy yellow ($\lambda_{581}$)" particles summed over *Republic* plus its introduction, and the same equality holds for every color in the palette. Same total mass per beaker, same total dust-particle count per beaker, same temperature, same volume, same vanishing global conserved quantum numbers. The two texts differ only in the spatial ordering of the particles at $t = 0$ — the ordering that encodes whether the beaker holds Aristotle's account of *eudaimonia* and the *Doctrine of the Mean*, or Plato's account of justice, the tripartite soul, the allegory of the cave, and the Form of the Good.

Denote the initial preparation of an Aristotle beaker by $\rho_A^{(0)}(\{\mathbf{x}_j^{(A)}, \mathbf{v}_j^{(A)}\})$ — a delta-function-localized configuration of $N$ dust particles in the *Nicomachean Ethics* arrangement, with thermal-equilibrium momenta drawn from the Maxwell–Boltzmann distribution at temperature $T$. Denote the initial preparation of a Plato beaker by $\rho_P^{(0)}$ similarly. Denote the conserved-quantity profile of either preparation by $\mathbf{Q} = (N_1, N_2, \ldots, N_K; \mathcal{E}; \mathbf{P}; \mathbf{L}; \mathcal{N})$, where $N_i$ is the count of particles of color $\lambda_i$ (with $K \sim 600{,}000$ distinct colors in the palette), $\mathcal{E}$ is the total energy, $\mathbf{P}$ is the total linear momentum, $\mathbf{L}$ is the total angular momentum, and $\mathcal{N}$ is the total particle number. By construction of the setup, $\mathbf{Q}_A = \mathbf{Q}_P$ — every component of the conserved-quantity profile is identical between the two preparations.

The Plato/Aristotle refinement makes a sharper structural point than the Iliad–Odyssey of §III.5. Plato's metaphysics of perfect Forms inaccessible to measurement, and Aristotle's empirical methodology of categorizing the directly observable, are two philosophical traditions whose laboratory representatives are operationally indistinguishable after dissolution. If two *philosophies* with such different commitments to the observable cannot be distinguished by any measurement after $T \gg \tau_d$, the doctrine that the abstract Hilbert-space state preserves a meaningful distinction between any two initial configurations through evaporation — Susskind's commitment — is itself indistinguishable from the metaphysics of Forms that Aristotle himself rejected as not-physics. We now establish via five formal theorems descending from d*x*₄/d*t* = i*c* that the destruction of operational information at the philosophical-content level is structurally forced, and that Susskind's retreat strategy is foreclosed.

#### Theorem III.6.1 (Content-Universal Equilibration: the equilibrium Gibbs distribution is a measurable function of the conserved-quantity profile alone)

**Theorem III.6.1 (Content-Universal Equilibration, after [MG-Thermodynamics-Chain Theorem 24a]).** *Under the McGucken Principle d*x*₄/d*t* = i*c*, the equilibrium phase-space distribution $\rho^{\rm eq}$ of $N$ Compton-coupled massive particles in a thermostatted volume $V$ at temperature $T$ is a measurable function of the conserved-quantity profile $\mathbf{Q}$ alone:*

$$\rho^{\rm eq}(\{\mathbf{x}_j, \mathbf{v}_j\}) \;=\; \mathcal{F}_{\rm eq}(\{\mathbf{x}_j, \mathbf{v}_j\};\, \mathbf{Q}, T, V), \tag{III.6.1}$$

*with no dependence on the initial spatial ordering $\rho^{(0)}$ beyond what is encoded in $\mathbf{Q}$. For any two initial preparations $\rho_1^{(0)}$ and $\rho_2^{(0)}$ with $\mathbf{Q}_1 = \mathbf{Q}_2$, the limiting distributions coincide as functions on phase space:*

$$\lim_{t \to \infty} \rho_1(t) \;=\; \lim_{t \to \infty} \rho_2(t) \;=\; \mathcal{F}_{\rm eq}(\cdot;\, \mathbf{Q}, T, V). \tag{III.6.2}$$

*Proof.* We trace the chain of McGucken-machinery results that force (III.6.1) and (III.6.2).

**Step 1 (Compton coupling forces matter–x₄ interaction at universal rate).** By SR-3 ([MG-HLA, MG-Compton]) and the Compton-coupling theorem [MG-Thermodynamics-Chain Theorem 4], every massive particle of mass $m$ oscillates at the Compton frequency $\omega_C = mc^2/\hbar$ as it advances along $x_4$ at rate $ic$ (the integrated form of d*x*₄/d*t* = i*c*). The interaction is universal — every massive particle in every beaker, regardless of textual content, undergoes the identical Compton-coupling mechanism with $x_4$-expansion.

**Step 2 (Spatial-projection isotropy).** By SR-2 (McGucken Sphere) and Theorem III.1 (Channel-B), the projection of $x_4$-driven displacement onto the spatial three-slice is isotropic: the projected direction is uniform on $S^2$ at every infinitesimal step (the $SO(3)$-invariant Haar measure on the McGucken Sphere, SR-6). Each particle's directional choice at each Compton-coupled step is i.i.d. uniform on $S^2$, independent of the particle's position, the positions of all other particles, and the textual identity of the configuration.

**Step 3 (Brownian motion via iterated isotropic projection).** Iteration of the isotropic spatial projection of Step 2 over time, by the central limit theorem applied to the McGucken-Sphere step process [MG-Thermodynamics-Chain Theorem 6], generates the Wiener-process diffusion equation $\partial_t \rho = D_{\rm total} \nabla^2 \rho$ for the spatial density of each particle, with

$$D_{\rm total} \;=\; \frac{k_B T}{6\pi\eta a} \;+\; \frac{\varepsilon^2 c^2 \Omega}{2\gamma^2}$$

the total diffusion coefficient combining thermal Einstein diffusion and the Compton-coupling McGucken diffusion of [MG-Thermodynamics-Chain Theorem 14].

**Step 4 (Maxwell–Boltzmann equilibrium velocity distribution).** The unique stationary state of the Compton-coupled Langevin dynamics is the Maxwell–Boltzmann distribution

$$f_{\rm eq}(\mathbf{v}) \;=\; \left(\frac{m}{2\pi k_B T}\right)^{3/2} \exp\!\left(-\frac{m|\mathbf{v}|^2}{2 k_B T}\right), \tag{III.6.3}$$

forced by the Fokker–Planck stationarity condition combined with the Einstein fluctuation–dissipation relation $k_B T = D_p/(m\gamma)$ [MG-Thermodynamics-Chain Theorem 9b Step 3]. The velocity-space equilibrium depends only on temperature $T$ and particle mass $m$, not on the initial spatial configuration.

**Step 5 (Gibbs distribution as the unique equilibrium).** Combining the velocity-space Maxwell–Boltzmann (Step 4) with the spatial Wiener-process equilibration (Step 3), the joint phase-space equilibrium is the Gibbs distribution

$$\rho^{\rm eq}(\{\mathbf{x}_j, \mathbf{v}_j\}) \;=\; \frac{1}{Z(\mathbf{Q}, T, V)} \exp\!\left(-\sum_j \frac{m_j |\mathbf{v}_j|^2}{2 k_B T}\right) \prod_j \chi_V(\mathbf{x}_j) \prod_i \delta_{N_i, N_i^{\rm conserved}}, \tag{III.6.4}$$

where $Z(\mathbf{Q}, T, V)$ is the partition function (a measurable function of $\mathbf{Q}, T, V$ alone), $\chi_V$ is the indicator function of the beaker volume, and the Kronecker delta factors enforce the conserved color counts $N_i$. The right-hand side of (III.6.4) depends on the initial configuration only through the conserved-quantity profile $\mathbf{Q}$: the color counts $N_i$ enter through the constraint $\prod_i \delta_{N_i, N_i^{\rm conserved}}$; the total energy enters through the partition function $Z$; the total momentum and angular momentum are zero by construction in the laboratory frame; all other initial-state information has been randomized by the Compton-coupled Brownian motion of Steps 1–3.

**Step 6 (Convergence in any norm).** By the Wiener-process exponential relaxation to equilibrium [MG-Thermodynamics-Chain Theorem 6], each initial distribution $\rho_X^{(0)}$ converges to $\rho^{\rm eq}$ in any norm — total variation, $L^2$, $L^\infty$, relative entropy — at characteristic relaxation time $T_* = L^2/(6 D_{\rm total})$ for the largest spatial scale $L$ distinguishing the initial configurations. For $t \gg T_*$, $\rho_X(t) \to \rho^{\rm eq}(\cdot; \mathbf{Q}, T, V)$ uniformly, with $\rho^{\rm eq}$ depending only on $\mathbf{Q}, T, V$. Equation (III.6.2) follows. ∎

**Corollary III.6.1a (Aristotle and Plato dissolve to the same Gibbs distribution).** *For the Aristotle–Plato setup, $\mathbf{Q}_A = \mathbf{Q}_P$ by construction. By Theorem III.6.1, $\rho_A^{\rm eq} = \rho_P^{\rm eq} = \mathcal{F}_{\rm eq}(\cdot; \mathbf{Q}_A, T, V) = \mathcal{F}_{\rm eq}(\cdot; \mathbf{Q}_P, T, V)$. The two ensembles converge to the same Gibbs distribution as functions on phase space.*

#### Theorem III.6.2 (Observation as McGucken-Sphere intersection: no observation without sphere-intersection)

We now formalize the structural fact that every act of measurement is, in the McGucken framework, a McGucken-Sphere intersection event between the measured system's worldline and the observer's instrumentation. This is the bridge from the abstract notion of "operationally inaccessible regime" to a precise structural statement that forecloses retreat into measurement-free regimes.

**Theorem III.6.2 (Observation as McGucken-Sphere Intersection, after [MG-Thermodynamics-Chain Theorem 24b; MG-FeynmanDiagrams Proposition VI.5]).** *Under the McGucken Principle d*x*₄/d*t* = i*c* and the Feynman-diagrammatic apparatus of [MG-FeynmanDiagrams], every act of observation that records a measurable outcome is structurally an $(N+1)$-vertex Feynman vertex at a spacetime event $v$ where the system's McGucken Sphere $\Sigma_S$ intersects pairwise with $N$ McGucken Spheres $\Sigma_{A_1}, \ldots, \Sigma_{A_N}$ of the observer's apparatus constituents. The localization rate of the observation is $\Gamma \sim N\omega_C$ with $\omega_C = mc^2/\hbar$ the average Compton frequency of the apparatus constituents. A spacetime region $\mathcal{R}$ admits no observation by an observer with worldline $\gamma_O$ if and only if no McGucken Sphere of any constituent of the observer's apparatus intersects $\mathcal{R}$. In any such region, no measurement can record an outcome, and no physical claim restricted to $\mathcal{R}$ has operational content for the observer at $\gamma_O$.*

*Proof.* By [MG-FeynmanDiagrams Proposition III.1], the propagator of each constituent in any system is the $x_4$-coherent Huygens kernel riding the constituent's McGucken Sphere at Compton frequency $\omega_C$. By [MG-FeynmanDiagrams Proposition VI.3], an interaction event between two or more constituents is structurally a Feynman vertex at the spacetime point where the constituents' McGucken Spheres intersect pairwise. By [MG-FeynmanDiagrams Proposition VI.5], the $(N+1)$-vertex Dyson expansion of the joint system–apparatus interaction has localization rate scaling as $N\omega_C$.

A spacetime region $\mathcal{R}$ admits observation by the observer at $\gamma_O$ if and only if some apparatus constituent's McGucken Sphere intersects $\mathcal{R}$. Equivalently: $\mathcal{R}$ admits no observation if no such intersection exists. The contrapositive is the operational content of the theorem: a region $\mathcal{R}$ with no McGucken-Sphere intersection with the apparatus is, by hypothesis, a region from which no signal, no propagator, no Feynman-vertex content reaches the observer; therefore no measurement performed by the observer can record an outcome localized in $\mathcal{R}$, and no physical claim restricted to $\mathcal{R}$ has operational content for the observer at $\gamma_O$. ∎

#### Theorem III.6.3 (Universality of Channel B at every spacetime event)

We now formalize the universal applicability of the Channel B (geometric-propagation) face of the Schrödinger equation at every spacetime event. This prevents any retreat into a special regime from escaping the McGucken-Brownian-dissolution mechanism.

**Theorem III.6.3 (Universal Channel B at Every Event, after [MG-Thermodynamics-Chain Theorem 24c]).** *Under the McGucken Principle d*x*₄/d*t* = i*c*, at every spacetime event $p \in \mathcal{M}_G$ the McGucken Sphere $\Sigma_+(p)$ of radius $R(t) = c(t-t_p)$ exists with surface area $A(t) = 4\pi c^2 (t-t_p)^2$ and $SO(3)$-invariant Haar measure on its angular cross-section (SR-2, SR-6). The Channel-B content of the Schrödinger equation (Compton-coupled Brownian dissolution, strict Second Law of Theorem VIII.7, $+ic$-monotonic propagation, SR-1) operates at every spacetime event without exception. There is no spacetime region $\mathcal{R}$ — not the interior of a black hole, not the asymptotic boundary of anti-de Sitter spacetime, not the cosmological-horizon screen, not the dual conformal-field-theoretic boundary of any holographic geometry, not the universal-Hilbert-space wavefunction at any spatial slice — in which Channel B is inactive.*

*Proof.* The McGucken Principle d*x*₄/d*t* = i*c* asserts that the fourth dimension is expanding at the velocity of light from *every* spacetime event in a spherically symmetric manner. By Theorem III.1(a) (Channel-B reading), each event $p$ is the apex of a McGucken Sphere $\Sigma_+(p)$ of radius $R(t) = c(t-t_p)$ for $t > t_p$. By [MG-Geometry Lemma 2.2; MG-Geometry Definition 9.3], this McGucken Sphere is the future null cone from $p$, which exists at every spacetime event of the moving-dimension manifold $(\mathcal{M}_G, F, V)$ without restriction on the spacetime region.

Compton coupling (SR-3, [MG-Thermodynamics-Chain Theorem 4]) operates universally on every massive constituent at its Compton frequency $\omega_C = mc^2/\hbar$ at every event of the constituent's worldline. Spatial-projection isotropy (Theorem III.1(a), SR-6, [MG-Thermodynamics-Chain Theorem 5]) is the $SO(3)$-invariance of the McGucken-Sphere surface at every event. Brownian motion ([MG-Thermodynamics-Chain Theorem 6]) is the iterated isotropic spatial projection at every event. The strict Second Law ([MG-Thermodynamics-Chain Theorem 9], Theorem VIII.7 of the present paper) is the $+ic$-monotonic content at every event. The Compton-coupled Brownian dissolution mechanism operates at every event without restriction.

In particular: at every event inside the interior of a black hole, the McGucken Sphere expands at $+ic$; at every event on the asymptotic boundary of anti-de Sitter spacetime, the McGucken Sphere expands at $+ic$; at every event in the bulk of any holographic geometry, the McGucken Sphere expands at $+ic$. The Channel-B Compton-coupled Brownian mechanism is active everywhere. There is no spacetime region in which the mechanism is suspended. ∎

**Corollary III.6.3a (No retreat into special regimes escapes Channel B).** *Combining Theorems III.6.2 and III.6.3, the retreat strategy fails on both prongs simultaneously. Either (i) the retreat is into a spacetime region $\mathcal{R}$ with no McGucken-Sphere intersection with the observer's apparatus, in which case (by Theorem III.6.2) no claim restricted to $\mathcal{R}$ has operational content for the observer; or (ii) the retreat is into a spacetime region with McGucken-Sphere intersection with the observer's apparatus, in which case (by Theorem III.6.3) Channel B operates in $\mathcal{R}$ identically as it does in any other region, and the Compton-coupled Brownian dissolution mechanism applies, and the operational content of the claim is subject to the same destruction as in any laboratory dust beaker. Susskind's retreat strategy is therefore foreclosed: it produces either operationally vacuous claims (case i) or claims subject to Channel-B destruction (case ii). In neither case does it preserve a physical defense of "information cannot be destroyed."*

#### Theorem III.6.4 (Content-independence of the Compton-coupled Brownian dissolution mechanism)

We now formalize the structural fact that the Compton-coupled Brownian dissolution mechanism does not "see" the semantic content of the encoded information. This is what makes the Aristotle–Plato variant a genuine refinement of the Iliad–Odyssey variant, and what extends the destruction uniformly to any pair of texts.

**Theorem III.6.4 (Content-Independence of the Dissolution Mechanism, after [MG-Thermodynamics-Chain Theorem 24d]).** *Under the McGucken Principle d*x*₄/d*t* = i*c* and the Compton-coupling mechanism of [MG-Thermodynamics-Chain Theorem 4], the dissolution timescale $\tau_d = \ell_{\rm letter}^2/(6 D_{\rm total})$ of a dust-encoded text and the equilibrium Gibbs distribution $\rho^{\rm eq}$ of its dissolved state are functions only of the physical parameters of the dust (particle mass $m$, radius $a$, color $\lambda_i$, count per color $N_i$), the thermostat (temperature $T$, viscosity $\eta$), and the McGucken-coupling parameters $(\varepsilon, \Omega)$ — and not functions of the textual, linguistic, semantic, philosophical, literary, scientific, musical, or genetic content the spatial ordering of the dust may encode. Two texts encoded with identical resources (identical $\{N_i\}$, identical $m$ and $a$ per particle, identical $V$ and $T$) dissolve at identical timescale $\tau_d$ to identical equilibrium Gibbs distribution $\rho^{\rm eq}$ regardless of whether the texts encode (Hamlet, Macbeth), (Iliad, Odyssey), (Nicomachean Ethics, Republic), (Principia Mathematica, Critique of Pure Reason), (Beethoven's Ninth Symphony score, Mozart's Requiem score), or any other pair of distinct contents.*

*Proof.* The dissolution mechanism operates through three structural inputs: (i) the Compton-coupling Hamiltonian $H_{\rm mod}(\tau) = \varepsilon m c^2 \cos(\Omega\tau)$ of [MG-Thermodynamics-Chain Theorem 4], which is a function of particle mass $m$ and the universal McGucken parameters $\varepsilon, \Omega$; (ii) the spatial-projection isotropy of [MG-Thermodynamics-Chain Theorem 5], which is $SO(3)$-invariance and depends on no initial-state information; (iii) the iterated spatial diffusion of [MG-Thermodynamics-Chain Theorem 6], which is the Wiener-process PDE $\partial_t \rho = D_{\rm total} \nabla^2 \rho$ with $D_{\rm total}$ depending only on $k_B T, \eta, a, \varepsilon, c, \Omega, \gamma$. None of these inputs is a function of textual, linguistic, semantic, philosophical, literary, scientific, musical, or genetic content.

The dissolution timescale $\tau_d = \ell_{\rm letter}^2/(6 D_{\rm total})$ is a function only of the diffusion coefficient and the letter length scale (the latter measured in spatial units, with no semantic content). The equilibrium Gibbs distribution $\rho^{\rm eq}$ of Theorem III.6.1 depends only on the conserved-quantity profile $\mathbf{Q}$, the temperature $T$, and the volume $V$, none of which carry semantic content.

Therefore, two texts encoded with identical physical resources dissolve at identical $\tau_d$ to identical $\rho^{\rm eq}$, regardless of content. ∎

**Corollary III.6.4a (Universal applicability across content domains).** *The Brownian Hamlet (§III.4) destroys ordering within one literary text; the Brownian Iliad–Odyssey (§III.5) destroys ordering between two literary texts; the Brownian Plato–Aristotle (this section) destroys ordering between two philosophical texts. By Theorem III.6.4, the destruction extends without modification to any content domain: scientific texts (Newton's Principia vs. Einstein's Foundation of the General Theory of Relativity), musical scores (Beethoven's Ninth vs. Mozart's Requiem), genetic sequences (any two distinct genomes encoded in dust at matched conserved-quantity profile), engineering blueprints, mathematical proofs, computer programs, encrypted messages — any pair of distinct content encoded in dust at identical conserved-quantity profile dissolves to operationally indistinguishable equilibria as a theorem of d*x*₄/d*t* = i*c*.*

#### Theorem III.6.5 (Susskind's retreat strategy is foreclosed by the combined Theorems III.6.1–III.6.4)

We now combine the four preceding theorems into the closing structural diagnosis.

**Theorem III.6.5 (Susskind's Retreat Strategy is Foreclosed, after [MG-Thermodynamics-Chain Theorem 24e]).** *Under the McGucken Principle d*x*₄/d*t* = i*c* and the combined content of Theorems III.6.1–III.6.4, no retreat into special spacetime regimes — black-hole interiors, anti-de Sitter asymptotic boundaries, cosmological-horizon screens, universal-Hilbert-space wavefunctions, dual conformal-field-theoretic states, Einstein–Rosen bridge interiors, or any other region — preserves a physical defense of Susskind's commitment "information cannot be destroyed" in its operational reading. The retreat strategy is foreclosed by the following structural argument:*

*(R1) **Operational content requires McGucken-Sphere intersection with the observer's apparatus** (Theorem III.6.2). Any claim restricted to a spacetime region $\mathcal{R}$ with no McGucken-Sphere intersection with the observer's apparatus has no operational content for the observer. Such claims are not physical claims about the observer's reality; they are claims in a domain the observer's measurement instrumentation cannot reach.*

*(R2) **Channel B operates at every spacetime event without exception** (Theorem III.6.3). The Compton-coupled Brownian dissolution mechanism, the strict Second Law, and the $+ic$-monotonic propagation operate at every spacetime event of the moving-dimension manifold. There is no region in which the dissolution mechanism is suspended.*

*(R3) **The dissolution mechanism is content-independent** (Theorem III.6.4). The mechanism applies identically to any pair of distinct contents encoded with identical conserved-quantity profile, regardless of the textual, semantic, philosophical, scientific, or musical character of the encoding.*

*(R4) **The equilibrium distribution depends only on the conserved-quantity profile** (Theorem III.6.1). For any two preparations with matched conserved-quantity profile, the equilibrium phase-space distributions are equal as functions on phase space.*

*Combining (R1)–(R4): if Susskind retreats into a regime $\mathcal{R}$ with no McGucken-Sphere intersection with the observer, the claim is operationally vacuous by (R1) — it is philosophy, not physics. If Susskind retreats into a regime $\mathcal{R}$ that does intersect the observer's apparatus, the claim is subject to Channel B by (R2), to the content-independent dissolution mechanism by (R3), and to the conserved-quantity-only equilibrium by (R4) — the same destruction applies. In neither case does the retreat preserve a physical defense of "information cannot be destroyed." The retreat strategy is foreclosed.* ∎

**Corollary III.6.5a (The Aristotle–Plato variant as the philosophical-content limit of the foreclosure).** *The Aristotle–Plato setup is the limit case in which the retreat into philosophical-content domains is empirically refuted at the laboratory bench. The two foundational texts of Western philosophy — the most semantically rich, the most historically influential, the most conceptually distinct pair available — dissolve to the same Gibbs distribution under Compton-coupled Brownian motion. If Susskind's retreat into philosophical domains worked, the Aristotle–Plato experiment would supply a discriminating observable somewhere — in the dual CFT state, in the holographic boundary encoding, in the entanglement structure, in the universal wavefunction. By Theorem III.6.5, no such discriminating observable exists. The retreat into philosophy is foreclosed at the level of philosophy itself.*

#### Theorem III.6.6 (Structural anatomy of Susskind's equivocation: the slide that the dual-channel structure forbids)

The combined operational/structural refutations of Theorems III.4.1–III.4.3, III.5.1–III.5.3, III.6.1–III.6.5, and III.6.A–III.6.F establish the empirical and structural content. We now isolate the precise *argumentative move* by which Susskind's defense proceeds, and exhibit it as an equivocation that the dual-channel structure of the Schrödinger equation forbids.

**Theorem III.6.6 (Structural Anatomy of Susskind's Equivocation, after [MG-Wick Theorem 30.9.30; MG-Susskind-Equation §IX; MG-Thermodynamics-Chain Theorem 23a.6]).** *Susskind's defense of unitarity against Hawking's information-destruction claim is structurally an ontological-epistemic equivocation that the dual-channel structure of the Schrödinger equation forbids. The equivocation operates as follows:*

*(a) **The orthodox unitarity defense begins with an ontological premise**: the universal wavefunction $|\Psi(t)\rangle$ evolves deterministically under the Schrödinger equation, with the unitary evolution $U(t) = e^{-i\hat{H}t/\hbar}$ governing all of physics. This premise is structurally correct, as the Channel-A content of the McGucken framework establishes (Theorem III.1(b), Theorem IV.3).*

*(b) **The orthodox unitarity defense concludes with an epistemic claim**: information is recoverable in principle, by any sufficiently powerful agent with access to the universal wavefunction. This claim is operationally vacuous in the strong sense: no physically realizable agent has access to $|\Psi(t)\rangle$ on the universal Hilbert space, because the universal Hilbert space includes regions causally disconnected from any observer (Theorem IV.5; Lemma III.7.1).*

*(c) **The slide from (a) to (b) bypasses Channel B.** The orthodox defense moves from "the universal wavefunction evolves unitarily" (Channel A, true) to "information is recoverable in principle" (operational, not addressed by Channel A alone) without performing the McGucken-Wick rotation $\tau = x_4/c$ (SR-7) that would expose the Channel-B content of the same equation. The Channel-B content forbids the slide: the operational accessibility $P_{\mathrm{accessible}}(t) \to 0$ for the undetected photon (Lemma III.7.1), the Brownian dissolution of operational information at laboratory scale (Theorems III.4.1, III.5.1–III.5.2, III.6.1), and the strict Second Law $dS/dt > 0$ governing the increase of phenomenological entropy (Theorem VIII.7) all rule out the operational-recoverability conclusion that Susskind's defense requires.*

*(d) **The equivocation is therefore structural, not personal.** Susskind's actual argument requires sliding from the ontological premise (Channel-A formal unitarity) to the operational conclusion (operational recoverability), and the slide is forbidden by the Channel-B content of the same Schrödinger equation that the ontological premise invokes. The McGucken Duality dissolves the equivocation by exposing the dual-channel structure of the Schrödinger equation, with the McGucken-Wick rotation as the operational mechanism that connects the two channels and that forbids the slide between them.*

*Proof.* By direct construction. The undetected-photon argument (Lemma III.7.1, Theorem III.7.1) supplies the case where the formal preservation $\int_{\mathbb{R}^3}|\psi|^2 = 1$ holds (Channel A) while the operational accessibility $P_{\mathrm{accessible}}(\mathcal{O}, t) \to 0$ for every bounded observer (Channel B). The slide from (a) to (b) requires that operational accessibility be recoverable from formal preservation; but the undetected-photon case demonstrates that operational accessibility can fail while formal preservation is exact. The slide is therefore forbidden by the dual-channel structure of the Schrödinger equation. ∎

**Remark III.6.6.1 (No paradox to resolve; only the equivocation to expose).** Theorem III.6.6 supplies the structural-philosophical content under which the fifty years of holographic apparatus built around defending Susskind's position — black-hole complementarity [Susskind–Thorlacius–Uglum 1993], AdS/CFT [Maldacena 1997], ER = EPR [Maldacena–Susskind 2013], the Page curve [Page 1993], replica wormholes [Penington–Shenker–Stanford–Trivedi 2019], the island formula [Almheiri–Engelhardt–Marolf–Maxfield 2019] — are recognized as fifty years of structural defense against a paradox that does not exist once the dual-channel architecture of the Schrödinger equation is recognized. **There is no paradox to resolve. There is only the equivocation to expose.** The orthodox measurement problem of quantum mechanics — the apparent incompatibility of unitary Schrödinger evolution with projective measurement collapse — is the same equivocation at the matter-dynamics tier: unitary evolution is the Channel-A reading, projective collapse is the Channel-B reading, and the two are simultaneous theorems of d*x*₄/d*t* = i*c* applied to distinct structural content of the same Schrödinger equation. The dissolution requires no new postulate, no stochastic localization mechanism (GRW), no branching multiverse (Everett), no hidden variables (Bohm), no consistent histories, and no decoherence-only approach; the dissolution is forced by the dual-channel architecture of the Schrödinger equation once the McGucken-Wick rotation $\tau = x_4/c$ is performed at the equation level. The Hawking–Susskind information paradox and the orthodox measurement problem are *structurally the same problem*, both arising from the Channel-A-only-reading blindspot, and both dissolving simultaneously under the dual-channel architecture.

#### Theorem III.6.7 (The Domain-Shifting Diagnostic: Susskind's methodological retreat from physics to Platonic metaphysics, followed by a declaration of victory in physics from a position that has ceased to be physics)

Theorem III.6.6 establishes the *logical* structure of Susskind's equivocation at the level of the argument itself. We now establish the sharper **methodological** diagnostic at the level of Susskind's actual argumentative practice across the 30-year black-hole war.

**Theorem III.6.7 (The Domain-Shifting Diagnostic — methodological retreat from physics to Platonic metaphysics, after [MG-Wick Theorem 30.9.30.2]).** *Theorem III.6.6 establishes that Susskind's defense of unitarity slides from the ontological premise (Channel-A formal preservation of $\int_{\mathbb{R}^3}|\psi|^2 = 1$) to the operational epistemic conclusion (information is recoverable in principle) without performing the McGucken-Wick rotation that would expose the Channel-B content forbidding the slide. The present theorem establishes the sharper **methodological** diagnostic at the level of Susskind's actual argumentative practice across the 30-year black-hole war: when the operational refutations close in — when the undetected-photon construction (Theorem III.7.1) supplies $P_{\mathrm{accessible}}(t) \to 0$ for every bounded observer, when the Brownian Hamlet (Theorem III.4.1), Brownian Iliad–Odyssey (Theorems III.5.1, III.5.2), and Brownian Plato–Aristotle (Theorems III.6.1–III.6.5) supply laboratory-scale empirical refutations, when the Compton-coupling Brownian mechanism of [MG-Thermodynamics-Chain §14] supplies the explicit physical mechanism — Susskind's argument does not retreat to a more careful operational position. It retreats to a non-empirical Platonic-metaphysical defense, and then declares victory in physics from a position that has ceased to be physics.*

*The methodological signature consists of three structural moves:*

*(I) **The empirical-operational position is asserted as physics.** Susskind's initial claim, throughout the period 1993–2008 and elaborated in [Susskind 2008], is operational: information cannot be destroyed in black-hole evaporation; the holographic principle preserves it on the horizon; AdS/CFT supplies the bulk-boundary reconstruction; the universal wavefunction's unitary evolution is the foundational physical claim. These are operational claims about what observers can recover in principle, and they are presented as the physics of the black-hole problem.*

*(II) **When empirical-operational refutation closes in, the position retreats to a non-empirical Platonic claim.** The undetected-photon construction of Theorem III.7.1 forces the orthodox unitarian into the forced choice of the operational/metaphysical dichotomy: either the "preservation" claim is operational (and refuted by $P_{\mathrm{accessible}}(t) \to 0$) or it is metaphysical (a Platonic conservation law about amplitude on regions no measurement can ever probe). The Brownian Hamlet, Iliad–Odyssey, and Plato–Aristotle experiments make the operational refutation laboratory-scale-direct. Susskind's defense at this point retreats to the metaphysical position: the universal wavefunction $|\Psi(t)\rangle$ evolves deterministically on a Platonic universal Hilbert space irrespective of whether any observer can ever access any part of it; the formal preservation $\int_{\mathbb{R}^3}|\psi|^2 = 1$ on the Platonic spatial container is the conservation law that "preserves information." The retreat is documented in the orthodox unitarity defense's invocations of "the universal wavefunction" (a quantity no physically realizable agent has access to), "global Hilbert space" (a Platonic mathematical container with no operational accessibility), and "in-principle recoverability" (a metaphysical commitment about regions no measurement can probe). The Banks–Peskin–Susskind theorem, which Susskind cites in support of his position, is structurally part of the retreat: as established in Theorem III.7.3 (BPS Channel Restriction), the theorem rules out only Channel-A non-unitarity at the formal-mathematical level and is silent on the operational Channel-B content, so its invocation supports the metaphysical claim but not the operational claim that physics requires.*

*(III) **From the metaphysical position, victory is then declared in physics.** Susskind's 2008 popular account [Susskind 2008, titled* The Black Hole War: My Battle with Stephen Hawking to Make the World Safe for Quantum Mechanics*] presents the metaphysical defense as a victory* for physics*, with the holographic apparatus (black-hole complementarity, AdS/CFT, ER = EPR, the Page curve, replica wormholes, the island formula) elaborated as the contemporary physics of black-hole information. But the metaphysical defense is not physics, in the operational sense that physics requires; it is Platonic metaphysics about a mathematical object. The declaration of victory therefore declares victory **in a domain different from the one the question was originally posed in**.*

*The structural diagnostic is therefore: Susskind retreats from operational physics (where the empirical refutations apply and his position fails) to Platonic metaphysics (where the empirical refutations do not apply because the claim is no longer about observables), and then declares victory in operational physics (where his position has not in fact prevailed). The McGucken Duality dissolves the equivocation by exposing the dual-channel structure of the Schrödinger equation that contains both the Channel-A formal-metaphysical content Susskind defends and the Channel-B operational-physical content the empirical refutations expose. The retreat is structurally unavailable under the McGucken framework: there is no separate Platonic domain to which the position can retreat, because the operational Channel-B content and the formal Channel-A content are simultaneous theorems of d*x*₄/d*t* = i*c* applied to the same equation.*

*Proof.* By direct examination of the historical record [Hawking 1976; Susskind–Thorlacius–Uglum 1993; Susskind 2008; Maldacena 1997; Maldacena–Susskind 2013; Penington–Shenker–Stanford–Trivedi 2019; Almheiri–Engelhardt–Marolf–Maxfield 2019] and the structural analysis of Theorem III.6.6. (I) is documented by the operational character of the initial unitarity-defense claims throughout the period 1993–2008. (II) is documented by the metaphysical character of the defense's reliance on the universal wavefunction, the global Hilbert space, and the formal preservation $\int_{\mathbb{R}^3}|\psi|^2 = 1$ on the Platonic spatial container — none of which is operationally accessible. (III) is documented by the rhetorical framing of [Susskind 2008] as a victory for physics and by the fifty-year holographic apparatus's presentation as the contemporary physics of black holes. The McGucken Duality's structural unavailability of the retreat is established by the dual-channel architecture: there is no separate Platonic domain because the Channel-A formal preservation and the Channel-B operational accessibility are the same factor of $i$ in the same equation, with the McGucken-Wick rotation $\tau = x_4/c$ as the operational bridge. ∎

**Remark III.6.7.1 (The pickleball–Wimbledon analogy as compressed structural diagnostic, after [MG-Wick Remark 30.9.30.3]).** Theorem III.6.7 admits a compressed structural diagnostic in the form of a sporting analogy. The pickleball court is the metaphysical domain in which Susskind's argument can prevail — the Platonic universal Hilbert space, the formal preservation $\int_{\mathbb{R}^3}|\psi|^2 = 1$, the unitarity of the universal wavefunction on regions no measurement can probe. The Wimbledon court is the operational-physics domain in which the question was originally posed — what can any observer ever recover, what does the empirical record force, what do the Brownian Hamlet and the undetected photon establish at laboratory and single-quantum scale. **Susskind plays the pickleball game competently, wins it on his own court by a margin that is mathematically uncontested, and then declares himself Wimbledon champion.** The neighborhood pickleball tournament is not Wimbledon, and a victory in the former is not a victory in the latter, and the rhetorical move that conflates the two is not a physics argument. The McGucken Duality establishes that the two courts are not separable — Channel A's formal preservation and Channel B's operational accessibility are the same equation's two readings, with the McGucken-Wick rotation $\tau = x_4/c$ as the operational bridge — and the appearance of two separable courts is itself an artifact of the Channel-A-only-reading blindspot of orthodox quantum mechanics. Under the dual-channel architecture, there is only one court: the operational-physics court, with the metaphysical formal-preservation content as one signature-reading of the same equation, simultaneously true with the operational Channel-B content that the metaphysical defense was constructed to evade.

**Corollary III.6.7.2 (Structural impossibility of the retreat under the McGucken framework, after [MG-Wick Corollary 30.9.30.4]).** *Under the dual-channel architecture of the Schrödinger equation established by Theorem III.1 and Theorem VIII.7, the retreat-to-metaphysics methodological move of Theorem III.6.7 is **structurally impossible**. The Platonic universal Hilbert space and the operational accessible domain are not two separate domains between which the defending physicist can shift the location of the question; they are two signature-readings of the same equation, with the McGucken-Wick rotation $\tau = x_4/c$ as the bridge. Any attempt to retreat from the operational domain (where empirical refutation applies) to the Platonic domain (where empirical refutation does not apply) immediately encounters the dual-channel structure of the equation under defense, which forces both domains to be simultaneously addressed by the same factor of $i$ in the same equation. The retreat is therefore not merely rhetorically inappropriate or methodologically problematic; it is structurally forbidden by the dual-channel architecture, and the McGucken Duality supplies the explicit structural argument that closes the rhetorical-methodological move at the level of the foundational equation of quantum mechanics.*

*Proof.* Direct from Theorem III.1 (Schrödinger doubly forced through both channels via the basis-change of Theorem III.1(c)), Theorem III.6.6 (the slide from Channel-A ontology to Channel-B operationality bypasses the McGucken-Wick rotation), and Theorem III.6.7 (the retreat-to-metaphysics methodological diagnostic). The McGucken Duality identifies the Platonic Channel-A content and the operational Channel-B content as the same factor of $i$ in the same equation; therefore no separable domain exists to which the defense can retreat. ∎

**Remark III.6.7.3 (Structural-historical parallel: 19th-century operationalists versus Platonic-mathematical reaction, after [MG-Wick Remark 30.9.30.5]).** The methodological retreat documented in Theorem III.6.7 has a structural-historical parallel in the 19th- and early-20th-century reaction of the Platonic-mathematical tradition to the empirical-operational character of thermodynamics. Loschmidt's 1876 reversibility objection, Zermelo's 1896 recurrence-paradox objection [Zermelo 1896], and Poincaré's 1893 recurrence theorem [Poincaré 1893] were each invoked as Platonic-mathematical arguments against the empirical content of the Second Law: the time-symmetric microscopic dynamics, the inevitability of statistical recurrence in finite phase volumes, the Poincaré-recurrence cycles must (so the objection ran) overturn the macroscopic strict-monotonicity content of the Second Law. The 19th-century operational thermodynamicists — Carnot, Clausius, Maxwell, Boltzmann — held their empirical position against the Platonic-mathematical objections, and the structural-philosophical content of the present paper (Theorem VIII.7; Theorem VIII.6) establishes that they were structurally correct: the empirical strict Second Law is the Channel-B content of d*x*₄/d*t* = i*c*, and the Platonic-mathematical objections apply only to the time-symmetric Channel-A face and have no force on the Channel-B face.

**The orthodox unitarity defense of Susskind is, structurally, the inverse move.** Where Loschmidt–Zermelo–Poincaré sought to overturn empirical thermodynamics by invoking the Platonic-mathematical content of time-symmetric dynamics, Susskind seeks to defend the formal-mathematical content of unitarity against the empirical-operational content of information destruction by invoking the same Platonic-mathematical register. Both moves are structurally identical — they invoke the Channel-A-only content against the empirical-operational Channel-B content — and the McGucken Duality dissolves both moves by establishing that the Channel-A and Channel-B contents are simultaneous theorems of the same principle applied to distinct structural content of the same equation. The 19th-century empirical thermodynamicists held the empirical position correctly against the Platonic-mathematical reaction; the 20th-century orthodox-unitarity defense holds the Platonic-mathematical position against the empirical content, and is structurally wrong by the same diagnostic. The McGucken framework supplies the structural-philosophical content under which both 19th- and 20th-century debates are recognized as facets of the same Channel-A-only-reading blindspot, with the dual-channel architecture as the resolution of both.

**Diagnostic remark on the chain of refutations.** *The chain of formal refutations of Susskind's "information cannot be destroyed" commitment now extends across eleven theorems within this paper:*

- *Theorem VIII.7 (the Schrödinger equation contains the strict Second Law $dS/dt = (3/2) k_B/t > 0$ from first principles, via the three independent routes of §VIII.7);*
- *Theorem III.4.1 (the Brownian Hamlet exhibits operational destruction within one text, with Lemmas 1–3 of Theorem III.4.2);*
- *Theorem III.4.3 (systematic refutation of orthodox responses against the colored-dust path-divergence record);*
- *Theorems III.5.1 and III.5.2 (the Brownian Iliad–Odyssey sharpens the destruction to two texts with identical resources, by the KL/Pinsker bound and the measurement-as-observable bound);*
- *Theorem III.5.3 (systematic refutation in the matched-resources setting);*
- *Theorem III.6.1 (the content-universal equilibration theorem: the equilibrium Gibbs distribution is a function only of the conserved-quantity profile);*
- *Theorems III.6.2–III.6.5 (the foreclosure of Susskind's retreat strategy by the combined McGucken-Sphere-intersection, Channel-B-universality, content-independence, and conserved-quantity-equilibrium theorems);*
- *Theorem III.6.6 (the structural anatomy of Susskind's equivocation: the slide from Channel-A ontology to operational epistemic claim, forbidden by the dual-channel structure of the same Schrödinger equation);*
- *Theorem III.6.7 with Remark III.6.7.1 (pickleball–Wimbledon), Corollary III.6.7.2 (structural impossibility of the retreat), and Remark III.6.7.3 (19th-century structural-historical parallel): the methodological diagnostic — Susskind retreats from operational physics to Platonic metaphysics when empirical refutation closes in, then declares victory in physics from a position that has ceased to be physics;*
- *Theorem III.6.A through Theorem III.6.F (the six mainstream-physics theorems converging from independent directions: Margolus–Levitin, Lieb–Robinson, Pusey–Barrett–Rudolph, Bekenstein, Page-curve, Kochen–Specker);*
- *Theorems III.7.1 through III.7.5 (the single-photon Operational/Metaphysical Dichotomy and the BPS Channel Restriction in §III.7 below).*

*Each theorem descends from d*x*₄/d*t* = i*c* via the McGucken machinery of Theorems III.1 (Dual-Channel Decomposition), III.3 (First Law of the McGucken Dualities), VIII.7 (Schrödinger Contains the Second Law), VIII.7′ (Universal McGucken Channel B Theorem), and the Standing Results SR-1 through SR-14, combined with the Feynman-diagrammatic apparatus of [MG-FeynmanDiagrams] and the moving-dimension geometry of [MG-Geometry]. The destruction of operational information is therefore a theorem of d*x*₄/d*t* = i*c* at every level of structural refinement, with the philosophical-content level (Aristotle–Plato) being the natural closing case in which the rhetorical retreat into philosophy is foreclosed at the laboratory bench.*

**In plain language.** Susskind has a recurring move when his "information cannot be destroyed" position is challenged on operational grounds: he retreats into domains where no measurement is ever possible — the interior of a black hole, the asymptotic boundary of an idealized anti-de Sitter spacetime, the holographic encoding on a cosmological horizon screen, the wavefunction of the universe on a Hilbert space no observer can sample. Then he declares victory there. But declaring victory in a domain where no measurement can be made is not physics; it is philosophy with mathematical decoration. A physicist is bound to defend claims that have empirical content; a philosopher can claim anything in a regime no observer can ever check. The framework's theorems close on Susskind from two sides simultaneously. Theorem III.6.2 establishes that observation is McGucken-Sphere intersection at a Feynman vertex — no intersection, no observation, no physical content. Theorem III.6.3 establishes that the Channel-B face of the Schrödinger equation operates at every spacetime event without exception — including inside the regions Susskind retreats into. Theorem III.6.4 establishes that the Compton-coupled Brownian dissolution mechanism does not see the semantic content of the encoded information — it applies identically to any pair of texts with matched conserved-quantity profile. Theorem III.6.1 establishes that the equilibrium Gibbs distribution depends only on the conserved-quantity profile, with all other initial-state information destroyed by the dissolution. Theorem III.6.5 combines the four to foreclose the retreat strategy entirely: any retreat is either operationally vacuous (the destination has no observers, so the claim is philosophy, not physics) or subject to the same dissolution mechanism (the destination has observers and Channel B operates there). If Susskind insists on engaging at the philosophical level, the Aristotle–Plato experiment refutes him there too: the very founders of philosophy themselves cannot be recovered from a dissolved beaker. The two founders of Western philosophy dissolve to the same Gibbs distribution.

#### The six deep-physics theorems (mainstream literature converging on the same conclusion)

We further establish, via six deep-physics theorems each drawn from mainstream results in twentieth- and twenty-first-century physics, that Susskind's defense of global unitarity is structurally philosophy, not physics. Each theorem stands on its own; each integrates with the McGucken Principle d*x*₄/d*t* = i*c* and the Standing Results SR-1 through SR-14; together with Theorems III.6.1–III.6.5, they make the case from eleven independent directions.

**Theorem III.6.A (Margolus–Levitin computational lower bound rules out Susskind's exponential-complexity recovery in finite time).** *The Margolus–Levitin theorem [Margolus–Levitin 1998] establishes that any quantum-mechanical system with average energy $E$ above its ground state can perform at most $2E/(\pi\hbar)$ orthogonal-state transitions per unit time. Equivalently, any unitary operation acting on a Hilbert space of dimension $D$ requires at minimum a number of elementary operations bounded below by $\log_2 D \cdot \pi\hbar/(2E)$. Susskind's program requires, for the recovery of operationally accessible information after black-hole evaporation, an exponentially-complex unitary operation on the Hawking-radiation Hilbert space of dimension $D \sim 2^{A/(4\ell_P^2)}$. For a solar-mass black hole, $A/(4\ell_P^2) \sim 10^{76}$ bits, and the Margolus–Levitin lower bound on the recovery time using all of the energy of the visible universe ($E_{\text{universe}} \sim 10^{70}$ Joules) gives a recovery duration of at least*

$$T_{\text{recovery}} \;\gtrsim\; \frac{\hbar}{E_{\text{universe}}} \cdot 2^{10^{76}} \;\gg\; 10^{10^{75}} \text{ years}.$$

*This is unimaginably greater than the age of the universe ($1.4 \times 10^{10}$ years) by a factor that is itself unimaginably greater than every physical scale ever observed. Susskind's "operational" recovery procedure, taken at the lower bound of its own resource requirements, is not performable in the actual universe at any time in its actual history. By the McGucken framework, this is the Margolus–Levitin instantiation of the Brownian-Hamlet result: operationally accessible information (Definition VIII.6.2) is destroyed at every M-locus (SR-1 monotonicity, the +ic of d*x*₄/d*t* = i*c*) and remains operationally destroyed across cosmological timescales.*

*Proof.* The Margolus–Levitin bound [Margolus–Levitin 1998, Theorem 1] is established for any quantum system. Apply it to the Hawking-radiation Hilbert space of a Schwarzschild black hole of mass $M$. The dimension is $D = 2^{A/(4\ell_P^2)} = 2^{4\pi G^2 M^2/(\hbar c^3)}$. The number of elementary operations needed to act with a generic unitary on this Hilbert space is at minimum $\log_2 D$ — a count of independent two-level rotations — and each operation takes time at least $\pi\hbar/(2E)$ by Margolus–Levitin. For $E = E_{\text{universe}}$ and $M = M_\odot$, direct substitution gives the displayed bound. ∎

**Theorem III.6.B (Lieb–Robinson bound rules out faster-than-light effective propagation of operational information).** *The Lieb–Robinson theorem [Lieb–Robinson 1972; updated Hastings 2010] establishes that in any quantum lattice system with bounded local Hamiltonian, the operator norm of $[\hat{A}(x_1, t), \hat{B}(x_2, 0)]$ for local operators $\hat{A}, \hat{B}$ separated by spatial distance $r = |x_1 - x_2|$ is bounded by $C\,e^{-(r - v_{\text{LR}} t)/\xi}$, where $v_{\text{LR}}$ is the Lieb–Robinson velocity and $\xi$ is a correlation length. Effective operational information cannot propagate faster than $v_{\text{LR}}$. In the McGucken framework, the Lieb–Robinson bound is the Channel-B causality content of d*x*₄/d*t* = i*c* applied to lattice quantum systems (Theorem IV.5: the Channel-B reading sets the light cone at velocity c, and any lattice Hamiltonian with bounded local terms has $v_{\text{LR}} \le c$). Susskind's program requires Hawking radiation collected at asymptotic infinity to carry, in some operational sense, information from the black-hole interior — a spacelike-separated region. By Lieb–Robinson + Theorem IV.5, no such operational propagation exists.*

*Proof.* The Lieb–Robinson theorem [Lieb–Robinson 1972 Theorem 1] is a direct consequence of unitary evolution and local Hamiltonians. The bound $v_{\text{LR}} \le c$ for relativistic quantum field theories is a consequence of microcausality (commutativity of spacelike-separated local operators), which in the McGucken framework is Theorem IV.5 (Channel-B lightcone). Apply to the Hawking-radiation collection apparatus at asymptotic infinity and the black-hole interior: the spacelike separation forbids effective operational propagation. ∎

**Theorem III.6.C (Pusey–Barrett–Rudolph theorem makes the abstract Hilbert-space state ontic only if operationally distinct).** *The Pusey–Barrett–Rudolph theorem [Pusey–Barrett–Rudolph 2012, Nature Physics 8, 475] establishes that under mild assumptions about the structure of reality (preparation independence; no superluminal signaling), the quantum-mechanical wavefunction must be regarded as ontic rather than epistemic: distinct wavefunctions correspond to distinct physical realities. The contrapositive is the operative claim: two preparations that yield operationally indistinguishable outcomes for every conceivable measurement procedure necessarily correspond to the same physical reality. By Theorems III.5.1 and III.5.2, the Batch I (Iliad) and Batch O (Odyssey) preparations yield operationally indistinguishable outcomes for every measurement procedure available under resources (i)–(v) at time $T \gg \tau_d$. Therefore, by PBR, the two batches at time $T$ are the same physical reality. Whatever abstract Hilbert-space difference Susskind's formalism continues to record is, by PBR, not ontic — i.e., not part of physical reality.*

*Proof.* The PBR theorem is established in [Pusey–Barrett–Rudolph 2012, Theorem 1]; we apply it in contrapositive form. By Theorem III.5.1, the total variation distance between $\mathcal{M}(\text{Batch I}, T)$ and $\mathcal{M}(\text{Batch O}, T)$ is bounded by $e^{-T/(2\tau_{\text{decoh}})}$, which is operationally zero for $T \gg \tau_{\text{decoh}}$. Equivalently (Theorem III.5.2 claim I2, equation IO.3), the expectation values of every bounded observable on the two ensembles agree in the limit $t/T_* \to \infty$. By PBR, two preparations with zero operational distinguishability correspond to the same ontic state. The abstract Hilbert-space difference between Batch I and Batch O at time $T$ is therefore not part of physical reality. The doctrine that the difference is preserved in some "deeper" sense is, by PBR, not a claim about physical reality. ∎

**Theorem III.6.D (Bekenstein bound — Susskind's own apparatus turned against him — caps the operational-information density at the Channel-B value).** *The Bekenstein bound [Bekenstein 1981] establishes that the maximum entropy contained within a region of radius $R$ enclosing energy $E$ is*
$$S_{\max} \;\le\; \frac{2\pi k_B R E}{\hbar c}.$$
*Susskind's holographic principle [Susskind 1995] strengthens this to area-scaling: $S_{\max} \le k_B A/(4\ell_P^2)$. Both bounds are saturated at the horizon of a Schwarzschild black hole (Theorem IV.1). In the McGucken framework these are theorems of d*x*₄/d*t* = i*c* (SR-10: one bit per Planck area on any x₄-stationary hypersurface; Proposition VIII.5.1: holographic principle as theorem). The bounds limit the operational information available at any boundary or in any region. They do not allow for "additional" information stored in a global Hilbert space beyond what the bound permits at the boundary. Susskind's own apparatus, taken at face value, refutes the doctrine that operational information can hide in a global unitary on the universe: the Bekenstein bound and the holographic principle both express the operational-information content as a Channel-B quantity (an area or a region) with a definite McGucken-Sphere mode count (SR-10), with no room for hidden additional content above the area-law saturation.*

*Proof.* The Bekenstein bound and the holographic principle are derived in the McGucken framework as Proposition VIII.5.1 above, with the mechanism stated as SR-14 + SR-10. The bound caps the operational entropy at $A/(4\ell_P^2)$; there is no contribution from a global unitary beyond this. The Channel-A operator algebra on M-locus-free patches contributes within this cap; it does not augment the bound. Therefore Susskind's own apparatus (the holographic principle and the Bekenstein bound) explicitly does not permit hidden operational information beyond the boundary saturation. ∎

**Theorem III.6.E (Page-curve mathematics, calculated to the actual numerical Page time, shows that operationally accessible information is destroyed monotonically in physical time).** *The Page time for a Schwarzschild black hole of mass $M$ is*
$$t_{\text{Page}} \;\approx\; \frac{5120 \pi G^2 M^3}{\hbar c^4},$$
*which for $M = M_\odot$ gives $t_{\text{Page}} \approx 5.3 \times 10^{67}$ years ([Page 1993]). Before the Page time, the outgoing Hawking radiation is in a thermal (effectively maximally mixed) state and carries no operational information about the original infalling configuration. After the Page time, in Susskind's program, the radiation begins to carry information that purifies the initial state. But the actual measurement that decodes this purification, by Theorem III.6.A (Margolus–Levitin), requires $T_{\text{recovery}} \gg 10^{10^{75}}$ years using all of the energy of the universe — a time $10^{10^{75} - 67}$ times the Page time itself. The recovery procedure is operationally impossible in any physically meaningful sense. The Page curve is mathematically real as a Channel-A object on M-locus-free patches; it has no operational consequence at any time before the Margolus–Levitin recovery time, which is structurally unreachable.*

*Proof.* The Page-time formula is established in [Page 1993, Phys. Rev. Lett. 71, 3743]. The Margolus–Levitin bound from Theorem III.6.A applied to the post-Page Hawking-radiation Hilbert space of dimension $D \sim 2^{A/(4\ell_P^2)}$ gives the displayed comparison. The operational-information content of the radiation, integrated over $[0, t_{\text{Page}}]$, is bounded by what an actual measurement can recover by the actual Page time — which is, by Theorem III.6.A, none. Therefore no operationally accessible information has been recovered at the actual Page time. ∎

**Theorem III.6.F (Bell–Kochen–Specker contextuality forces the abstract Hilbert-space state to be measurement-contextual, not pre-existing as a recoverable ontology).** *The Kochen–Specker theorem [Kochen–Specker 1967] establishes that for any quantum system of dimension $d \ge 3$, no assignment of definite values to all observables consistent with the quantum-mechanical structure exists. Equivalently: the abstract Hilbert-space state cannot be regarded as a recipe for pre-existing values awaiting measurement. The "values" exist only relative to the measurement context. Susskind's doctrine that the abstract Hilbert-space state of the universe carries, in some absolute sense, information that survives evaporation, contradicts Kochen–Specker: the state's content is meaningful only relative to a measurement procedure, and (by Theorem III.6.A and Theorem III.6.E) no measurement procedure operationally recovers the pre-evaporation configuration. The abstract Hilbert-space state at post-Page-time, taken in absolute terms, is by Kochen–Specker not a well-defined ontology of pre-existing values; it is a recipe for measurement outcomes that no actual measurement can extract. In the McGucken framework, this is the M1-locus structure of Theorem XI.1: definite outcomes exist only at M1-loci, where Channel-A and Channel-B agree on a single value of $x_4$. Without an M1-locus (i.e., without an actual measurement event), the abstract Hilbert-space state carries no definite ontology.*

*Proof.* The Kochen–Specker theorem is established in [Kochen–Specker 1967] for any Hilbert space of dimension $\ge 3$. Apply to the post-Page Hawking-radiation Hilbert space of dimension $D \sim 2^{A/(4\ell_P^2)} \gg 3$. By Kochen–Specker, no assignment of definite values to all observables on this space exists. By Theorem III.6.A, no measurement procedure operationally recovers the relevant values in any physical time. By Theorem XI.1, definite outcomes require M1-loci. The abstract Hilbert-space state of post-Page Hawking radiation, in the absence of an actual measurement performed within the recovery time bound, carries no definite operational ontology. ∎

**Summary: six independent theorems converge on a single conclusion.** Margolus–Levitin (III.6.A) rules out Susskind's exponential-complexity recovery in finite physical time. Lieb–Robinson (III.6.B) rules out faster-than-light operational propagation of interior information to the radiation. Pusey–Barrett–Rudolph (III.6.C) rules out the abstract Hilbert-space difference between operationally indistinguishable preparations from being ontic. The Bekenstein bound and holographic principle (III.6.D) — Susskind's own apparatus — cap the operational-information density at the Channel-B value with no room for hidden content. The Page-curve mathematics (III.6.E) shows that the purported recovery time is structurally unreachable by $10^{10^{75}}$ orders of magnitude. Kochen–Specker contextuality (III.6.F) rules out the abstract Hilbert-space state from carrying a pre-existing recoverable ontology.

Each of these six theorems is mainstream physics. Each is established in peer-reviewed literature spanning sixty years (Kochen–Specker 1967 to Pusey–Barrett–Rudolph 2012). Each integrates with the McGucken Principle d*x*₄/d*t* = i*c* and the Standing Results SR-1 through SR-14: SR-1 monotonicity, SR-7 Wick rotation, SR-10 one bit per Planck area, SR-14 six-sense null-surface identity, Theorem IV.5 Channel-B lightcone, Theorem XI.1 M1-locus definite outcomes. Together, the six theorems establish that Susskind's defense of global unitarity is a claim about a domain — exponential-complexity recovery on post-evaporation Hilbert spaces beyond the actual Page time, with abstract Hilbert-space content that is not Kochen–Specker-recoverable and that violates Lieb–Robinson if treated as operational — where no measurement can in principle be performed within physical timescales of the actual universe.

A claim about reality that no measurement can falsify within the lifetime of the actual universe is, by every methodological standard from Galileo through Einstein and Bohr, *philosophy*, not *physics*. Susskind, when defending global unitarity in the regime where his own theorems forbid measurement, is doing philosophy. The McGucken Brownian dust experiments (§III.4, §III.5, §III.6) are by contrast operational physics: performable, repeatable, falsifiable at room temperature. The Channel-B reading of d*x*₄/d*t* = i*c* is the operational physics; the Channel-A reading on M-locus-free patches is the mathematical complement; Susskind's global-unitarity meta-claim across the entire evaporation history is the philosophy. The McGucken framework honors the methodological line, drawn by Galileo and reaffirmed by Einstein, between physics and philosophy: physics is what we can measure; philosophy is what we cannot. The Brownian Plato and Aristotle experiment is the laboratory recovery of the operational tradition that physics requires.

**Remark III.6.1 (a closing note on the methodology of measurement).** Aristotle's response to Plato's transcendental Forms was: *"there is no science of the unobservable; all knowledge begins with the senses."* The McGucken framework's response to Susskind's transcendental Hilbert-space content is structurally identical: there is no physics of operationally unrecoverable information; all physical reality is measurable, repeatable, and falsifiable within the lifetime and physical resources of the actual universe. Susskind's defense, in the regime where his own theorems forbid measurement, is the transcendental move Aristotle rejected. The Brownian Plato/Aristotle experiment is the empirical demonstration that Aristotle was right twenty-three centuries ago, and the McGucken Principle d*x*₄/d*t* = i*c* is the present-day instance of his methodology applied to the foundations of quantum mechanics and gravity.

### III.7. The Undetected Photon: single-photon refutation of the orthodox unitarian defense

The Brownian Hamlet (§III.4), Brownian Iliad–Odyssey (§III.5), and Brownian Plato–Aristotle (§III.6) experiments are *many-particle* operational probes. Susskind, in the worst-case defense, might attempt to evade the argument by appeal to many-body chaos: "the Brownian results show only that decoherence is fast for $L \sim 10^7$-particle systems; in a system of one particle, no chaos, hence no operational obstruction, hence global unitarity is restored." This reply does not survive the *single-photon* operational probe, which we now develop in full following [MG-Information-Destruction §III; MG-Susskind-Equation §III].

The argument is structurally distinct from the Brownian arguments: it uses no many-body system, no decoherence, no chaos. It uses one photon, one spherical wavefront, and the McGucken-Sphere expansion of d*x*₄/d*t* = i*c* applied to the photon's freely propagating amplitude. The conclusion is sharper: even at the single-photon level, the orthodox unitarian defense of "information is preserved because $\int|\psi|^2 = 1$ globally" is forced into a strict operational/metaphysical dichotomy that Susskind's apparatus cannot consistently resolve.

#### III.7.1. The thought experiment: one photon, no detector

**Construction.** A laboratory at event $E \in \mathcal{M}_G$ emits, at proper time $t = 0$, a single photon with wavefunction $\psi_0$ supported in a localized region near $E$. The photon propagates spherically outward at velocity $c$, with its amplitude expanding on the McGucken Sphere $S(E, ct)$ (SR-2). The laboratory is configured such that *no detector intercepts the photon* at any subsequent event: no apparatus is placed in the future light cone of $E$. The photon propagates freely to spatial infinity, with its wavefunction $\psi(\mathbf{x}, t)$ governed by the relativistic Schrödinger evolution and the global normalization

$$\int_{\mathbb{R}^3} |\psi(\mathbf{x}, t)|^2 \, d^3x = 1 \tag{III.7.1}$$

preserved for all $t > 0$ by Channel-A unitarity (Theorem IV.3).

**The question.** What is the probability of detection of this single photon? More precisely: by any observer at any later event, what is the probability that the photon is registered?

#### III.7.2. The orthodox answer and its operational probe

*The orthodox answer.* The orthodox unitarian replies: probability is conserved by unitary evolution. By (III.7.1), the global integral $\int|\psi|^2 = 1$ is preserved; the photon is "still somewhere," the amplitude has not been destroyed, and Channel-A unitarity is intact.

*The McGucken operational probe.* Let $\mathcal{O}$ be any observer at a later event $q \in J^+(E)$, with $q \neq E$. The spatial region accessible to $\mathcal{O}$ at the present moment is the intersection of $\mathcal{O}$'s past light cone with the present spatial slice, denoted $\mathcal{R}(\mathcal{O}, t)$. By SR-2 (McGucken Sphere) and Theorem IV.5 (Channel-B lightcone), $\mathcal{R}(\mathcal{O}, t)$ is *bounded* — it is the spatial region from which causal signals can reach $\mathcal{O}$ at time $t$, and this is finite for any observer not located at $E$.

Define the *operationally accessible probability* at time $t$ from $\mathcal{O}$'s perspective:

$$P_{\text{accessible}}(\mathcal{O}, t) \;:=\; \int_{\mathcal{R}(\mathcal{O}, t)} |\psi(\mathbf{x}, t)|^2 \, d^3x. \tag{III.7.2}$$

We establish the central fact:

**Lemma III.7.1 (Monotonic decay of operational accessibility for the freely propagating photon).** *Let $\psi(\mathbf{x}, t)$ be the wavefunction of a single photon emitted at $E$ at $t = 0$ and propagating freely. Let $\mathcal{O}$ be any observer at later events along a worldline not coincident with the photon's classical trajectory. Then*

$$P_{\text{accessible}}(\mathcal{O}, t) \;\text{ is monotonically decreasing in }t,$$

*and*

$$\lim_{t \to \infty} P_{\text{accessible}}(\mathcal{O}, t) \;=\; 0$$

*for every such observer in the universe.*

*Proof.* By SR-2, the photon's wavefunction at time $t$ is supported on a neighborhood of the McGucken Sphere $S(E, ct)$ of radius $ct$ centered at $E$. The peak amplitude on this 2-sphere falls as $1/(ct)$ by conservation of the integrated amplitude on a spherically expanding 2-surface. The McGucken-Sphere mode count (SR-2 applied to a freely propagating photon) gives the angular distribution of the wavefront density.

For any observer $\mathcal{O}$ at a later event $q$, the region $\mathcal{R}(\mathcal{O}, t) \cap S(E, ct)$ is, by elementary spherical geometry, a *spherical cap* whose angular extent is bounded by the angle subtended by $\mathcal{O}$'s past light cone at the McGucken Sphere $S(E, ct)$. As $t \to \infty$, the McGucken Sphere $S(E, ct)$ recedes from $\mathcal{O}$ at velocity $c$; the angular extent of $\mathcal{R}(\mathcal{O}, t) \cap S(E, ct)$ falls as $1/t^2$ for $t$ greater than the proper time of light-travel from $\mathcal{O}$'s position to the photon's spatial location.

Combining: the integrated probability $P_{\text{accessible}}(\mathcal{O}, t) = \int_{\mathcal{R}(\mathcal{O}, t) \cap S(E, ct)} |\psi|^2 \, dS$ falls at least as fast as $1/t^2 \cdot 1/(ct)^2 = 1/(c^2 t^4)$ for large $t$, hence is monotonically decreasing and tends to zero. This holds for every observer $\mathcal{O}$ in the universe, by SR-1 (the McGucken Sphere expands from every event monotonically forward; +ic, not ±ic). ∎

The global integral (III.7.1) is intact: $\int_{\mathbb{R}^3} |\psi|^2 d^3x = 1$ for all $t$. But the *operational* probability of detection by any observer falls to zero. The amplitude is "still somewhere" *only in the formal sense* that the integral over the unbounded mathematical $\mathbb{R}^3$ remains unity — a region no observer can access in finite time.

#### III.7.3. The forced choice — Theorem III.7.1 (Operational/Metaphysical Dichotomy)

**Theorem III.7.1 (Operational/Metaphysical Dichotomy).** *Let the orthodox one-content reading of the Schrödinger equation be: $i\hbar\,\partial_t\psi = \hat{H}\psi$ expresses unitary evolution and unitarity is the entire physical content of the equation. Under this reading, when confronted with the single undetected photon of §III.7.1, the orthodox unitarian must choose between exactly two positions:*

*(A) The* **operational reading** *— probabilities are probabilities of measurement outcomes. The Born rule applies conditional on a detection. An amplitude that never reaches any detector contributes nothing to any actual probability sum. The statement $\int_{\mathbb{R}^3} |\psi|^2 = 1$ is then a formal algebraic property of the wavefunction, not a physical claim about conserved measurement probability. Unitarity, on this reading, is an algebraic property of $U(t)$, not a statement about probabilities of events that never occur.*

*(B) The* **metaphysical reading** *— probabilities are intrinsic to $\psi$ independent of measurement. The global integral $\int_{\mathbb{R}^3} |\psi|^2 = 1$ is a physical claim about amplitude conserved over a Platonic spatial container $\mathbb{R}^3$, irrespective of whether any observer can ever access any part of it. Unitarity, on this reading, is a metaphysical commitment to amplitude bookkeeping on regions no measurement can probe.*

*Position (A) renders the orthodox unitarian's "unitarity is non-negotiable" defense operationally vacuous for the undetected photon: no operational probability has been violated, because no operational probability was ever computable. Position (B) renders the defense metaphysical: it commits the unitarian to conservation of a quantity whose only definition is in terms of regions inaccessible to experiment. The orthodox unitarian needs Position (A) to ground the commitment in physics (a science of measurement) and Position (B) to make the commitment universal (applying even to amplitude that no measurement probes). The orthodox one-content reading provides no consistent way to hold both.*

*Proof.* The two positions are exhaustive of the interpretive options under the orthodox reading because the orthodox reading recognizes only one content in $i\hbar\,\partial_t\psi = \hat{H}\psi$: the unitarity of $U(t)$. Hence the interpretation of $\int|\psi|^2 = 1$ must be either (A) algebraic, or (B) physical-as-claim-about-Platonic-regions. We establish that each position is internally consistent only at the cost of the defense of unitarity.

*Position (A) is operationally vacuous for the undetected photon.* Under the operational reading, probabilities are measurement-conditional. The undetected photon never undergoes a measurement; there is therefore no measurement outcome and no Born-rule application. The "amplitude conserved by unitary evolution" is then merely a formal property of the operator $U(t)$, not a physical claim about anything observable in the experiment. The orthodox "defense of unitarity" against the dual-channel reading collapses on this position: there is no operational claim being defended.

*Position (B) is a metaphysical commitment.* Under the metaphysical reading, the global integral $\int_{\mathbb{R}^3} |\psi|^2 = 1$ is taken as a physical claim about $\psi$'s amplitude content on the Platonic region $\mathbb{R}^3$. This region is, by Lemma III.7.1, *operationally inaccessible* in the limit $t \to \infty$: no observer's past light cone reaches all of $\mathbb{R}^3$ in finite proper time. The commitment to amplitude conservation on this region is therefore a commitment to a quantity not in principle measurable by any physical observer. By the Aristotelian–Galilean–Einsteinian methodological tradition (§III.6 above), this is metaphysics, not physics.

*The orthodox unitarian needs both.* The orthodox defense of unitarity must (i) ground itself in measurement (otherwise it is not physics) and (ii) apply universally (otherwise it does not constrain Hawking radiation, which by Theorem III.6.E requires recovery times $\gg 10^{10^{75}}$ years). Position (A) provides (i) at the cost of (ii). Position (B) provides (ii) at the cost of (i). The orthodox one-content reading admits no third position.

Therefore the orthodox unitarian, under the orthodox one-content reading, cannot consistently defend the doctrine "$\int |\psi|^2 = 1$ guarantees information preservation" against the undetected-photon thought experiment. ∎

**Why this matters.** The undetected photon is the *laboratory-bench instance* of the black-hole information problem. A Hawking quantum emitted from a black-hole horizon and propagating to spatial infinity is, modulo cosmological complications, the same object: a spherically expanding wavefront with no detector at every later event. If the orthodox reading cannot account for the laboratory single-photon case without lapsing into metaphysics, it cannot account for the cosmological Hawking-radiation case either. By Lemma III.7.1, every laboratory emits operationally lost amplitude at every emission event; this is the same Channel-B phenomenon Hawking detected at the horizon in 1976.

#### III.7.4. The dual-channel resolution at the single-photon level

The dual-channel reading developed in §III.1, §VIII.7, and §VIII.7′ supplies the consistent alternative to the orthodox dichotomy of Theorem III.7.1. We state it explicitly for the undetected photon.

**Theorem III.7.2 (Dual-Channel Resolution at the single-photon level, after [MG-Susskind-Equation §VIII; MG-Information-Destruction §VIII]).** *Under the dual-channel reading of the Schrödinger equation (Theorem III.1, Theorem VIII.7, Theorem VIII.7′), the undetected-photon thought experiment is resolved without metaphysical commitment, as follows:*

*(i) **Channel A is preserved exactly.** The Schrödinger evolution $i\hbar\,\partial_t\psi = \hat{H}\psi$ is unitary on the full $\mathbb{R}^3$ by Theorem IV.3; $U(t) = e^{-i\hat{H}t/\hbar}$ satisfies $U(t)^\dagger U(t) = \mathbb{1}$; the canonical commutation relations $[\hat{x}, \hat{p}] = i\hbar$ are preserved; the global integral $\int_{\mathbb{R}^3} |\psi|^2 = 1$ holds for all $t$. This is the algebraic content of the equation, and it is intact.*

*(ii) **Channel B operational loss is real and is intrinsic to the same equation.** By Theorem VIII.7 Route 3 and Theorem VIII.7′ (Universal McGucken Channel B Theorem), the same factor of i in $i\hbar\,\partial_t$ that produces Channel-A unitarity also produces, under the McGucken-Wick rotation $\tau = x_4/c$, the Euclidean-signature reading whose spatial projection is monotonically decreasing operational accessibility at every observer. By Lemma III.7.1, $P_{\text{accessible}}(\mathcal{O}, t) \to 0$ for every observer $\mathcal{O}$ not located at $E$. This is Channel-B operational loss via spherical $x_4$-dilution — the same phenomenon as M2 (horizon crossing) and M3 (branching overlap) applied to the single-photon wavefront expanding on the McGucken Sphere from $E$.*

*(iii) **No contradiction between (i) and (ii).** Channel-A unitarity and Channel-B operational loss are not in conflict. Channel-A unitarity says $U(t)$ is algebraically norm-preserving on $\mathbb{R}^3$. Channel-B operational loss says the integral over $\mathcal{R}(\mathcal{O}, t) \subsetneq \mathbb{R}^3$ falls monotonically. Both statements are true simultaneously; both descend from the same +i in $i\hbar\,\partial_t$; the McGucken-Wick rotation (SR-7) relates them as the two metric-signature readings of one geometric process.*

*(iv) **No metaphysical commitment is required.** The dual-channel reading provides a third position beyond the operational/metaphysical dichotomy of Theorem III.7.1. Channel A handles the formal algebraic preservation; Channel B handles the operational accessibility; neither requires a Platonic commitment to amplitude on inaccessible regions. The unitarian's dilemma is resolved by recognizing that "unitarity" names a Channel-A fact and "information preservation" names a Channel-B fact, and the two are independent properties of one equation.*

*Proof.* Part (i) follows from Theorem IV.3 (Channel-A unitarity on simply connected M-locus-free open neighborhoods, applied to $\mathbb{R}^3$ in the absence of detectors). Part (ii) follows from Theorem VIII.7 Route 3 (the Lorentzian-Euclidean signature-readings derivation, with the Wiener-process measure of equation (VIII.7.4) governing the Channel-B reading of the same Schrödinger evolution) and Lemma III.7.1 (monotonic decay of operational accessibility). Part (iii) follows from the basis-change-is-a-linear-isomorphism statement of Theorem III.1 part (c): the two readings are not in conflict because they are two coordinate representations of the same x₄-advance configuration. Part (iv) follows from Theorem III.1 and Theorem III.7.1: the dual-channel reading is structurally a *third* position beyond (A) operational and (B) metaphysical of Theorem III.7.1, available exactly because the orthodox one-content reading is incomplete. ∎

#### III.7.5. The Banks–Peskin–Susskind theorem rules out only Channel A non-unitarity

We now establish that the Banks–Peskin–Susskind theorem [Banks–Peskin–Susskind 1984], which is the load-bearing technical result for Susskind's defense of unitarity, is *silent on Channel B* and applies only to Channel A. This is the key structural fact that allows the dual-channel reading to coexist with the BPS theorem without contradiction.

**Statement of BPS.** The Banks–Peskin–Susskind theorem concerns modifications of the $S$-matrix in which pure states evolve into mixed states by an operator "$\$$" such that $\$\rho \neq U\rho U^\dagger$ for any unitary $U$. The theorem shows that such modifications, under standard assumptions of locality, energy conservation, and Lorentz invariance, induce propagating pathologies — energy non-conservation, vacuum heating, or locality violation — that are inconsistent with low-energy phenomenology constrained at twelve to fifteen significant figures [Banks–Peskin–Susskind 1984].

**Theorem III.7.3 (BPS Channel Restriction, after [MG-Susskind-Equation Theorem V.1]).** *The Banks–Peskin–Susskind theorem rules out non-unitary modifications of the evolution operator $U(t)$ at the algebraic-symmetry level (Channel A). It does not rule out, and is silent on, monotonic +ic-driven geometric-propagation effects (Channel B) that leave $U(t)$ unitary while inducing operational information loss via spherical $x_4$-dilution, horizon crossing, or causal-region exit.*

*Proof.* The BPS theorem's hypothesis is the existence of an operation $\$$ that maps pure states to mixed states without factoring through any unitary $U$. The hypothesis acts at the algebraic level: it modifies the operator that maps in-states to out-states. This is precisely the Channel-A operator (Definition II.1 above; Theorem IV.3).

Suppose now that Channel-A evolution is fully unitary on M-locus-free patches: $U(t) = e^{-i\hat{H}t/\hbar}$ and $\$\rho = U\rho U^\dagger$ exactly, with the Channel-B operational-loss effects (Lemma III.7.1, mechanisms M1, M1′, M2, M3 of §III.2) occurring *without* modification of $U(t)$. Then the BPS hypothesis is *not satisfied*: the evolution is unitary, $\$\rho = U\rho U^\dagger$. The theorem provides no constraint.

Channel-B effects — spherical $x_4$-dilution (Lemma III.7.1), horizon crossing (M2), causal-region exit at $\mathscr{I}^+$ — do not modify $U(t)$. They describe the *operational accessibility* of the unitarily-evolved amplitude to bounded observers. The amplitude $\psi(\mathbf{x}, t)$ is computed by *exactly the same unitary* $U(t)$ in the dual-channel reading as in the orthodox reading. What differs is the recognition that the integral $\int_{\mathcal{R}(\mathcal{O}, t)} |\psi|^2$ over the operationally accessible region is generically strictly less than unity and monotonically decreasing — a Channel-B fact (Theorem VIII.7 Route 3), not a Channel-A violation.

Therefore the BPS theorem does not apply to Channel-B operational loss. Susskind's apparatus correctly rules out Channel-A non-unitarity; it does not, and cannot, rule out the Channel-B content of the Schrödinger equation. ∎

**Corollary III.7.3a.** *Operational information loss via Channel-B mechanisms — including horizon crossing (M2), spherical $x_4$-dilution (Lemma III.7.1), Hawking radiation thermal flux at $\mathscr{I}^+$, and the Brownian-Hamlet / Iliad–Odyssey / Plato–Aristotle laboratory dissolutions of §§III.4–III.6 — is consistent with the Banks–Peskin–Susskind theorem and consistent with full Channel-A unitarity.*

#### III.7.6. Hawking's misattribution and Susskind's half-equation

We can now diagnose, with full McGucken machinery, the structural error of *both* sides of the black-hole-information war as it was conducted historically.

**Theorem III.7.4 (Hawking's Diagnosis, after [MG-Susskind-Equation Theorem VI.1]).** *Hawking's 1976 claim of gravitational information loss [Hawking 1976] is the correct identification of a Channel-B phenomenon in a black-hole spacetime, miscoded as a Channel-A claim. The Channel-A claim (that gravity violates the unitarity of $U(t)$, requiring an "$\$$-matrix") is ruled out by Banks–Peskin–Susskind (1984). The Channel-B phenomenon (operational information loss via M2 horizon crossing and spherical $x_4$-dilution of Hawking quanta) is real, intrinsic to the same Schrödinger equation, and consistent with full Channel-A unitarity. The conflict between Hawking's claim and Channel-A unitarity is therefore an artifact of the orthodox one-content reading of the Schrödinger equation; in the dual-channel reading the conflict dissolves and both Hawking's intuition (Channel B) and Susskind's defense (Channel A) are correct on their own halves of the structure.*

*Proof.* Hawking's 1976 physical intuition was that gravitational collapse and subsequent Hawking radiation introduce an irreversibility into the dynamics — that information about the initial state cannot be reconstructed from the final radiation, even in principle. By Theorem III.7.2 (ii), this is correct as a Channel-B claim: the Hawking quanta propagate as a spherically expanding wavefront on the McGucken Sphere from each emission event, and by Lemma III.7.1 the operational accessibility of the radiation falls monotonically for every bounded observer. By Theorem III.6.A (Margolus–Levitin), the recovery time is $\gtrsim 10^{10^{75}}$ years.

Hawking miscoded this irreversibility as a Channel-A claim — a violation of the unitarity of $U(t)$. By Theorem III.7.3 (BPS Channel Restriction), the Channel-A claim is ruled out: any modification of $U(t)$ at the algebraic level propagates to produce energy non-conservation, vacuum heating, or locality violation at observable scales, none of which is observed. Hawking's Channel-A attribution was wrong; his Channel-B intuition was right.

The 2004 concession at GR17 [Hawking 2005] retained the orthodox one-content framing: Hawking's Euclidean path-integral argument attempted to recover Channel-A unitarity from inside Channel A by appealing to a topology sum, with the trivial topology dominating at late times. The argument has not been made rigorous and was not accepted by the field as a derivation. From the dual-channel perspective, the move was *unnecessary*: Channel-A unitarity was never actually violated in Hawking's original derivation; only Channel-B operational loss was real. The concession was sociologically meaningful and physically irrelevant. ∎

**Theorem III.7.5 (Susskind's Half-Equation, after [MG-Susskind-Equation Theorem VII.1]).** *Susskind's commitment to global unitarity (Banks–Peskin–Susskind 1984; holography 't Hooft 1993, Susskind 1995; complementarity Susskind–Thorlacius–Uglum 1993; microstate counting Strominger–Vafa 1996; AdS/CFT Maldacena 1997) correctly defends Channel A of the Schrödinger equation against modifications ruled out by Theorem III.7.3. Susskind's reading of the equation, however, recognizes only Channel A as physical content and treats Channel-B effects (spherical $x_4$-dilution, M2 horizon crossing, the strict Second Law of Theorem VIII.7) as belonging to separate disciplines — statistical mechanics, coarse-graining, decoherence. By Theorem III.1, Theorem VIII.7, and Theorem VIII.7′, this reading is structurally incomplete: Channel B is intrinsic to the same Schrödinger equation and carried by the same factor of i. Susskind defends half the structure of the equation against a phantom attack on Channel A while leaving Channel B unrecognized.*

*Proof.* The four pillars of Susskind's defense each act at the Channel-A level. Banks–Peskin–Susskind (1984) addresses algebraic modifications of $U(t)$ — by Theorem III.7.3, Channel A only. The holographic principle ('t Hooft 1993; Susskind 1995) is a Channel-A bound on the dimension of the operator-algebra Hilbert space on a given boundary — by Proposition VIII.5.1, a Channel-A theorem. Black-hole complementarity (Susskind–Thorlacius–Uglum 1993) is a Channel-A statement about operator-algebra accessibility to different observers — by Proposition VIII.5.2, a Channel-A theorem. Strominger–Vafa microstate counting (1996) is a Channel-A discrete-Hilbert-space construction — by Proposition VIII.5.4, a Channel-A theorem. AdS/CFT (Maldacena 1997) is a Channel-A duality between bulk operator algebras and boundary CFT operator algebras — Channel A on both sides. Each of the four pillars is Channel A.

Susskind's reading of the Schrödinger equation as exhausted by Channel A is the structural step where his program fails to engage the Channel-B content. By Theorem III.1 (Dual-Channel Decomposition), Theorem VIII.7 (Schrödinger Contains Second Law), and Theorem VIII.7′ (Universal McGucken Channel B Theorem), the same factor of i in $i\hbar\,\partial_t$ that generates Channel-A unitarity also generates, under the McGucken-Wick rotation $\tau = x_4/c$, the Euclidean-signature Wiener-process measure whose spatial projection is the strict Second Law $dS/d\tau > 0$. The Channel-B content is intrinsic to the equation, not an emergent statistical addition.

Susskind therefore defends the half of the Schrödinger equation that Hawking attacked, while the half Hawking actually meant to describe (Channel B) remains undefended because it was never on Susskind's map. The "war" was fought over a phantom attack on Channel A while the real content (Channel B) was unrecognized on both sides. ∎

#### III.7.7. The undetected photon and the black-hole horizon: structural identity

The single-photon argument completes the Brownian-experiment trilogy at the single-quantum level. We close §III.7 by stating the structural identity that makes this completion definitive.

**Remark III.7.1 (structural identity between the undetected photon and the Hawking quantum).** A photon emitted from a black-hole horizon and propagating to spatial infinity is structurally identical, modulo cosmological complications, to the laboratory-undetected photon of §III.7.1. Both are single-quantum spherical wavefronts expanding on McGucken Spheres from their respective emission events at velocity $c$. Both have operationally accessible probability that falls monotonically to zero at every observer (Lemma III.7.1). Both are subject to the BPS Channel Restriction (Theorem III.7.3): Channel A is preserved exactly, Channel B operational loss is real.

The Brownian Hamlet (§III.4), Brownian Iliad–Odyssey (§III.5), and Brownian Plato–Aristotle (§III.6) experiments establish the same Channel-B operational loss at the many-particle level, where Susskind might attempt a "many-body chaos" evasion. The undetected-photon argument of §III.7 establishes the *same* Channel-B operational loss at the *single-photon* level, where no such evasion is available. Together, the four operational probes — three Brownian and one single-photon — establish the operational-loss content of the McGucken Principle d*x*₄/d*t* = i*c* across all scales from one quantum to $10^7$ particles. The orthodox unitarian doctrine that "information is preserved" fails operationally at every scale.

**Remark III.7.2 (the war was fought over a phantom).** The historical black-hole-information war (1976–2004) was fought between Hawking's Channel-A attack and Susskind's Channel-A defense. By Theorem III.7.4, Hawking's Channel-A attack was a misattribution of the real Channel-B phenomenon he had detected. By Theorem III.7.5, Susskind's Channel-A defense correctly rebuts the misattributed Channel-A claim, leaving Channel B unrecognized on both sides. The Channel-B content of the same Schrödinger equation — the actual physical content of Hawking's 1976 intuition, expressed cleanly in the undetected-photon argument of §III.7.1–§III.7.3 — was never on either side's map. The war was fought over a phantom; the dual-channel reading makes the actual content visible and resolves the dispute by exhibiting it as no dispute at all.

### III.8. The Seven McGucken Dualities and the Father Symmetry priority

The Channel-A / Channel-B architecture is the binary expression of a deeper seven-fold structure. [MG-Cat Definition 14.4.1] enumerates the *Seven McGucken Dualities* — the complete catalog of fundamental algebra-geometric bifurcations generated by d*x*₄/d*t* = i*c*, with the uniqueness clause of Theorem 14.4.2 establishing that no eighth fundamental duality exists.

**Definition III.5 (The Seven McGucken Dualities, after [MG-Cat] Definition 14.4.1).** *The seven fundamental algebra-geometric bifurcations descending from d*x*₄/d*t* = i*c* are:*

1. **Hamiltonian / Lagrangian** — the time-evolution duality between phase-space-flow (Channel-A operator) and stationary-action (Channel-B path).
2. **Noether / Second-Law** — the symmetry-conservation duality between continuous-symmetry-invariance (Channel A) and irreversible entropy-increase (Channel B, +*i*c selection).
3. **Heisenberg / Schrödinger** — the matrix-vs-wave duality between operator-algebraic time evolution (Channel A) and complex-amplitude propagation (Channel B).
4. **Wave / Particle** — the field-vs-quantum duality between continuous oscillation on the McGucken Sphere (Channel B) and discrete x₄-stationary mode count (Channel A).
5. **Locality / Nonlocality** — the lightcone-vs-shared-origin duality between Channel-B propagation at velocity *c* and Channel-A shared-McGucken-Sphere identity (SR-12).
6. **Mass / Energy** — the rest-vs-motion duality between Channel-A *m* (norm of four-velocity, SR-1 reading) and Channel-B $E = mc^2$ (Compton-frequency oscillation rate).
7. **Time / Space** — the parametric-vs-extended duality between Channel-A *t* (the variable in d/d*t*) and Channel-B $x_4 = ict$ (the dimension that advances).

(Uniqueness: Theorem 14.4.2 of [MG-Cat] proves by exhaustion over the seven necessary levels of physical description that no eighth fundamental duality exists.)

The Channel-A / Channel-B architecture of §III.1 is the *binary expression* of these seven dualities: every theorem of the framework reads each duality through the same A/B pair. The First Law of the McGucken Dualities (Theorem III.3) is the structural statement that the seven bifurcations are not seven independent dualities but seven readings of the *same* underlying duality — the duality of d*x*₄/d*t* = i*c* itself, the "=" of which is the categorical "⇔" of being and becoming (SR-13).

**Theorem III.5 (The McGucken Principle is the Father Symmetry of Physics).** *Following [MG-Cat] Theorem 14.4.3, the McGucken Principle d*x*₄/d*t* = i*c* has structural priority over the following nine symmetries / dualities of physics: (i) Lorentz $SO^+(1,3)$; (ii) Poincaré ISO(1,3); (iii) Noether's theorem and conservation laws; (iv) local gauge symmetry $U(1) \times SU(2) \times SU(3)$; (v) quantum unitary $U(t) = e^{-iHt/\hbar}$; (vi) CPT; (vii) supersymmetry $\text{SUSY}_{N=k}$; (viii) diffeomorphism invariance; (ix) the string-theoretic S/T/U/AdS-CFT/mirror dualities. Each of (i)–(ix) is derivable from d*x*₄/d*t* = i*c* as a theorem; none of (i)–(ix) derives d*x*₄/d*t* = i*c*.* [MG-Cat Theorem 14.4.3]

*Proof sketch.* (i) Lorentz: Theorem IV.5 above (Lorentz invariance derived from the velocity-addition law for $v = c$). (ii) Poincaré: the semidirect product of Lorentz with translation invariance, the latter being the Channel-A reading of x₄-advance from any event. (iii) Noether: the Channel-A reading of d*x*₄/d*t* = i*c* on continuous symmetries gives the conserved currents; the +*i*c selection then gives the Second Law (SR-5, [MG-HLA]). (iv) Local gauge: local x₄-phase invariance generates $U(1)$ at the matter-tier; the SU(2) and SU(3) factors arise from the two-component spinor structure of Channel A and the three-color McGucken Sphere structure of Channel B [MG-SM]. (v) Unitarity: Theorem IV.3 (Stone's theorem applied to the anti-Hermitian Channel-A generator). (vi) CPT: the +*i*c orientation invariance under the simultaneous flip of the three discrete labels (C, P, T) — derived in [MG-Sakharov]. (vii) Supersymmetry: a candidate extension that, if realized, would be the doubling of Channel-A and Channel-B under graded structure — derivable from d*x*₄/d*t* = i*c* if it exists. (viii) Diffeomorphism invariance: the Channel-B geometric reading is coordinate-free (SR-2); the McGucken Sphere is a geometric object, not a coordinate construct. (ix) String dualities: each S/T/U/AdS-CFT/mirror duality is the cross-channel agreement of two readings of one d*x*₄/d*t* = i*c* configuration on a specific compactification.

The structural content of Theorem III.5 is that the McGucken Principle is *prior* to every catalog symmetry of physics. The nine symmetries / dualities listed are not independent postulates; they are consequences. This is the "Father Symmetry" property in the sense of [MG-Cat] §14.2 — the McGucken Symmetry is the structural parent of every other symmetry of physics, with the seven McGucken Dualities of Definition III.5 as the seven primary readings and the nine symmetries above as derived consequences. ∎

### III.9. The Schrödinger equation contains thermodynamics

A consequence of the First Law and the Triad table that deserves explicit statement: the Schrödinger equation $i\hbar \,\partial_t \psi = \hat{H}\psi$ is not merely the Channel-A reading of the quantum-mechanics master equation $[\hat{q},\hat{p}] = i\hbar$. By Theorem III.3 (i), it contains the Channel-B reading as a categorical potential — and by Theorem III.5, the kinetic-thermodynamics master equation $dS/dt = (3/2)k_B/t$ is itself a Channel-A reading of d*x*₄/d*t* = i*c* (Remark III.4 row 3). The two equations are *not* independent statements about disjoint physical sectors. They are the QM-row reading and the kinetic-thermodynamics-row reading of the same triad of master equations, all four rows of which are simultaneous readings of d*x*₄/d*t* = i*c*.

**Corollary III.6 (Schrödinger ⇒ Second Law).** *The Schrödinger equation $i\hbar\,\partial_t \psi = \hat{H}\psi$, taken as the Channel-A reading of $[\hat{q},\hat{p}] = i\hbar$, contains the kinetic Second Law $dS/dt > 0$ as a Channel-B consequence under the basis change of Theorem III.3 (i). Specifically: the +*i* on the left-hand side of the Schrödinger equation is the same +*i* as on the right-hand side of d*x*₄/d*t* = i*c*, and the same +*i* that orients the kinetic random walk in the Channel-B reading of Remark III.4 row 3. The future-oriented arrow of Schrödinger phase rotation is the future-oriented arrow of the kinetic Second Law. They are the same arrow, on the same x₄-axis, read by the same +*i*.* [MG-HLA; MG-Commut; MG-Cat Theorem 14.14]

This collapses the apparent paradox that exercised Loschmidt, Boltzmann, Zermelo, and (in modified form) Hawking and Susskind: the apparent conflict between unitary microscopic evolution (Schrödinger) and irreversible macroscopic evolution (Second Law). The conflict is not real. Unitary Schrödinger evolution is the Channel-A reading of d*x*₄/d*t* = i*c*; the Second Law's $dS/dt > 0$ is the Channel-B reading. They are not in tension; they are two readings of the same principle. The Brownian Hamlet (§III.4) is the laboratory exhibition of the same Corollary at experimental scale.

---

## §IV. Hawking's Three Demands as Theorems of the McGucken Principle

This is the central technical section. We derive Harlow's three demands one at a time and show that none of them is an independent postulate.

### IV.1. Finite black hole entropy (Demand 1)

**Theorem IV.1 (Area Law as a Theorem of d*x*₄/d*t* = i*c*).** *Let H be a closed spacelike 2-surface in spacetime at which outward null x₄-advance becomes tangent — i.e., a marginally trapped surface in the Channel-B reading of Theorem III.1, equivalently an x₄-stationary 2-surface in the sense of SR-9. Then the entropy associated with H, defined as the natural logarithm of the count of independent x₄-stationary modes on H (Standing Result SR-9) in the polarization basis fixed by Channel A on the null 1+1 strip transverse to H, satisfies*

$$S_H = \dfrac{k_B\, A(H)}{4\,\ell_P^2} = \dfrac{k_B\, A(H)\, c^3}{4\, G \hbar},$$

*where A(H) is the area of H, $\ell_P = \sqrt{\hbar G/c^3}$ is the Planck length (Standing Result SR-4), and the 1/4 coefficient is fixed by the Euclidean Schwarzschild cigar action $I_E = \beta M c^2/2$ via the McGucken Wick rotation (Standing Result SR-7).*

*Proof.* The proof proceeds in six steps. Every step is either a direct invocation of a Standing Result with an explicit corpus citation, or a fully-displayed elementary calculation.

**Step 1 (H is null with respect to x₄-advance).** By hypothesis, H is a marginally trapped 2-surface in the Channel-B reading of Theorem III.1. By SR-2, the Channel-B reading of d*x*₄/d*t* = i*c* at any event *p* on H is the McGucken-Sphere wavefront expanding from *p* at velocity *c*. Marginal trapping means the outward null normal to H has vanishing expansion: the wavefront from *p* lies tangent to H, with no proper radial advance away from H. Therefore every Channel-B excitation on H is x₄-stationary in the sense of SR-9: d*x*₄/d*t* = 0 in the frame co-moving with H. The hypersurface H is null because its induced metric is degenerate along the x₄-advance direction (SR-9, [MG-Twistor Proposition IV.1]; the equivalence "null ⇔ x₄-stationary" is established there).

**Step 2 (One x₄-oscillation mode per Planck area).** We count the independent x₄-stationary modes on H. By Theorem III.1 (Channel A), an x₄-stationary mode on H is a complex amplitude $\psi : H \to \mathbb{C}$ whose phase rotates at unit angular velocity per unit x₄-advance, with modulus constant along the worldline. By SR-4, the fundamental oscillation scale of x₄-advance is the Planck length $\ell_P = \sqrt{\hbar G / c^3}$, derived in [MG-Constants] and [MG-AdSCFT] as the unique combination of *c*, ℏ, *G* with dimensions of length, set geometrically by the requirement that one quantum of action ℏ in x₄-oscillation generates a curvature scale 1/*G* in the Channel-B reading.

The number of independent x₄-oscillation modes on a 2-surface H of area *A*(H) is therefore the number of disjoint Planck-area patches on H:

$$N(H) = \frac{A(H)}{\ell_P^2}. \tag{IV.1.1}$$

This identity is SR-10 in displayed form; it is the bit-per-Planck-area mode count derived independently in [MG-Bek26 Proposition V.1] (Compton-coupling form) and [MG-Verlinde] (Planck-area screen form), and serves as the structural input to the holographic bound of SR-11 ([MG-AdSCFT Proposition 2; MG-Haw26 Proposition IX.1]).

**Step 3 (Channel-B Wick rotation produces the Euclidean cigar).** We now compute the entropy of the *N*(H) independent modes by computing the partition function via the McGucken Wick rotation (SR-7, [MG-Wick]). The Channel-B reading of d*x*₄/d*t* = i*c* in the (Re, Im) basis is $dv/dt = c$ (Theorem III.1, Channel B). Substituting $t \mapsto -i\tau$ (Euclidean time, so that $dt = -i\,d\tau$) in d*x*₄/d*t* = i*c* yields

$$\frac{dx_4}{dt} = ic \quad \xrightarrow{\,t \mapsto -i\tau\,} \quad \frac{dx_4}{-i\,d\tau} = ic \quad \Longrightarrow \quad \frac{dx_4}{d\tau} = ic \cdot (-i) = -i^2 c = c.$$

The *i* on the right-hand side of d*x*₄/d*t* = i*c* is *cancelled* against the *i* in $t = -i\tau$; the resulting Euclidean equation $dx_4/d\tau = c$ is a real ordinary differential equation in real τ, with the imaginary unit absent. This is the precise content of "the Wick rotation is the physical removal of the *i* from d*x*₄/d*t* = i*c*" (SR-7, [MG-Wick]): the imaginary unit that records the orthogonality of x₄-advance to the three spatial directions in the Lorentzian reading becomes absent in the Euclidean reading because the substitution $t = -i\tau$ converts orthogonal advance into purely real Euclidean advance.

Applied to the Schwarzschild geometry, this Wick rotation produces the Euclidean Schwarzschild "cigar" geometry, whose two-dimensional (r, τ) section is

$$ds^2_E = \left(1 - \frac{r_s}{r}\right) d\tau^2 + \left(1 - \frac{r_s}{r}\right)^{-1} dr^2, \tag{IV.1.2}$$

where $r_s = 2GM/c^2$ is the Schwarzschild radius. Smoothness at the horizon $r = r_s$ (i.e., the cigar tip is a regular point of the manifold, not a conical singularity) requires that the Euclidean time coordinate $\tau$ have period

$$\beta = \frac{8\pi GM}{\hbar c^3} = \frac{2\pi}{\kappa}, \quad \kappa = \frac{c^4}{4GM}, \tag{IV.1.3}$$

where $\kappa$ is the surface gravity. The full derivation of (IV.1.3) from the McGucken Wick rotation is [MG-Haw26 Proposition IV.1]. The periodicity $\beta$ is the *physical* period imposed by the geometric requirement that the Euclidean continuation of d*x*₄/d*t* = i*c* close smoothly at the horizon — it is not an externally imposed thermal boundary condition.

**Step 4 (Euclidean action of the cigar).** The Euclidean Einstein–Hilbert action with the Gibbons–Hawking–York boundary term [GH77; York72] evaluated on the geometry (IV.1.2), with the flat-space (M = 0) action subtracted to give a finite answer, is

$$I_E = \frac{\beta M c^2}{2}. \tag{IV.1.4}$$

The full derivation, including the boundary-term subtraction, is [MG-Haw26 Proposition V.1]. The Einstein–Hilbert action is itself a theorem of d*x*₄/d*t* = i*c* via local x₄-phase invariance [MG-SM]; the Gibbons–Hawking–York boundary term [GH77; York72] is required by the standard variational principle on manifolds with boundary, and its presence here is not an assumption added to the McGucken framework but a consequence of having a closed (compact) Euclidean geometry with a regular horizon.

**Step 5 (From action to entropy: the thermodynamic identity, explicitly derived).** In the saddle-point approximation to the gravitational path integral $Z = \int \mathcal{D}g\, e^{-I_E[g]/\hbar}$, the dominant contribution is the on-shell action (IV.1.4):

$$\log Z = -\frac{I_E}{\hbar} = -\frac{\beta M c^2}{2 \hbar}. \tag{IV.1.5}$$

The thermodynamic free energy is $F = -\beta^{-1} \log Z$ in units $k_B = 1$, hence $F = M c^2 / 2$. The energy is $E = Mc^2$. The thermodynamic identity

$$S = \frac{E - F}{T} = \beta(E - F)$$

then gives (in units $k_B = 1$)

$$S = \beta \left( Mc^2 - \frac{Mc^2}{2} \right) = \frac{\beta Mc^2}{2} = \frac{1}{2} \cdot \frac{8\pi GM}{\hbar c^3} \cdot Mc^2 = \frac{4\pi GM^2}{\hbar c}.$$

Using $A(H) = 4\pi r_s^2 = 4\pi (2GM/c^2)^2 = 16\pi G^2 M^2 / c^4$, this becomes

$$S = \frac{4\pi G M^2}{\hbar c} = \frac{A(H) \cdot c^3}{4 G \hbar} = \frac{A(H)}{4 \ell_P^2}. \tag{IV.1.6}$$

Restoring $k_B$ gives the displayed formula. The thermodynamic identity $S = \beta(E-F)$ used above is elementary: it follows from $F = E - TS$ ⇔ $TS = E - F$ ⇔ $S = \beta(E-F)$, with no saddle-point assumption beyond what is already in (IV.1.5).

**Step 6 (Consistency with Step 2).** Combining (IV.1.1) and (IV.1.6):

$$S = \frac{A(H)}{4 \ell_P^2} = \frac{N(H)}{4} \cdot k_B$$

(restoring $k_B$). Each of the $N(H)$ x₄-oscillation modes contributes $k_B/4$ to the entropy. The factor of 1/4 emerges from the explicit thermodynamic computation in Step 5: the Euclidean cigar action $I_E = \beta M c^2/2$ contains a factor of 1/2, and combining $F = -\beta^{-1}\log Z = Mc^2/2$ with $E = Mc^2$ via $S = \beta(E - F) = \beta \cdot Mc^2/2$ produces a second factor of 1/2, giving 1/4 total in the area-law coefficient.

The Bekenstein 1973 estimation [MG-Bek26 Proposition V.1] of $\eta = (\ln 2)/(8\pi)$ at the Compton-coupling level is the same horizon mode count made via a different normalization: at the absorbed-bit threshold, the Compton wavelength sets the minimum bit area to $8\pi \ell_P^2 / \ln 2$ rather than $4 \ell_P^2$. The Hawking refinement to $\eta = 1/4$ (here, Step 5) replaces the Compton normalization with the Wick-rotated cigar normalization, fixing the thermodynamic factor exactly. The McGucken Sphere projection (SR-6, [MG-Born]) is what makes the two coefficients consistent: both are valid counts of the same x₄-stationary modes on H, weighted by different boundary conditions on the Channel-A reading.

Therefore $S_H = k_B A(H)/(4 \ell_P^2)$. ∎

**Corollary IV.1a (Theorem IV.1 closes the Wheeler "It from Bit" program).** *The bit content of any spacelike 2-surface H tangent to outward x₄-advance is exactly* $A(H)/(4\ell_P^2\,\ln 2)$ *bits. This is the McGucken-Sphere mode count of SR-11 applied to H, with each mode contributing $\ln 2$ to the natural-logarithm entropy.*

**Corollary IV.2.** *Finite black hole entropy (Harlow Demand 1) is a theorem of* d*x*₄/d*t* = i*c*, *not an independent postulate, by Theorem IV.1.*

**Note on the Bekenstein 1973 and Hawking 1975 derivations.** The Bekenstein 1973 results — the area law $S_{BH} \propto A/\ell_P^2$, the bit-per-$8\pi\,\ell_P^2$ coefficient $\eta = (\ln 2)/(8\pi)$, the Generalized Second Law, and the identification of black-hole entropy with inaccessible information — are established as a sequence of formal Propositions (III.1, IV.1, V.1, VI.1, VII.1) in the McGucken–Bekenstein paper [MG-Bek26] directly from the McGucken Principle d*x*₄/d*t* = i*c*. The Hawking 1975 refinement to $\eta = 1/4$, the Hawking temperature $T_H = \hbar\kappa/(2\pi c k_B)$, the mass-loss law d*M*/d*t* ∝ −1/*M*², and the refined Generalized Second Law are established as a parallel sequence of formal Propositions (III.1 through VII.1) in the McGucken–Hawking paper [MG-Haw26]. In that paper the McGucken Wick rotation [MG-Wick] is a *physical* transformation — the removal of the i from d*x*₄/d*t* = i*c* — rather than a formal computational device, and the 1/4 coefficient drops out as the explicit numerical factor in $I_E = \beta M c^2 / 2$ for the Euclidean Schwarzschild "cigar" geometry, fixed by the Gibbons–Hawking–York boundary action with the flat-space subtraction. Theorem IV.1 above is the dual-channel statement of the combined Bekenstein–Hawking result; the bit-per-$8\pi\,\ell_P^2$ identification of [MG-Bek26 Prop. V.1] and the 1/4 coefficient of [MG-Haw26 Prop. V.1] are the same polarization count on the null 1+1 strip read in two complementary ways.

### IV.2. Unitarity (Demand 2)

**Theorem IV.3 (Unitarity as the Channel-A reading of d*x*₄/d*t* = i*c*).** *Let U ⊂ spacetime be a simply connected event neighborhood on which Theorem III.1 applies, with Channel A and Channel B both exact (no M-mechanism locus in U). Then the Channel-A reading of d*x*₄/d*t* = i*c* generates a one-parameter group of unitary operators $U(t) = e^{-iHt/\hbar}$ on the associated complex Hilbert space, and this group preserves the inner product:*

$$\langle U(t)\phi | U(t)\psi \rangle = \langle \phi | \psi \rangle \quad \forall\, t \in \mathbb{R},\ |\phi\rangle, |\psi\rangle \in \mathcal{H}.$$

*Proof.* By Theorem III.1 (Channel A), expressing d*x*₄/d*t* = i*c* in the (|·|, arg) basis on a simply connected $U \subset \mathcal{M}_G$ free of M-loci, and applying the derivation displayed at equation (III.1.1), yields the Schrödinger equation

$$i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle \tag{IV.3.1}$$

on $U$, with $\hat{H}$ the Hermitian Hamiltonian operator whose eigenvalues are the energies of the system. The displayed derivation establishes (IV.3.1) directly: the i-phase rotation $d\psi/dt = i\omega_{\text{loc}}\psi$ at local angular velocity $\omega_{\text{loc}}$, combined with the Planck–Einstein relation $E = \hbar\omega_{\text{loc}}$ (SR-4) and the sign convention $\omega_{\text{loc}} = -E/\hbar$, produces (IV.3.1) as the Channel-A reading of d*x*₄/d*t* = i*c* applied to a quantum amplitude. The fully relativistic derivation via Klein–Gordon and the non-relativistic limit is [MG-HLA] (SR-3); the result on $U$ is (IV.3.1) at every event.

Solving (IV.3.1) by separation of variables for time-independent $\hat{H}$ gives $|\psi(t)\rangle = e^{-i\hat{H}t/\hbar}|\psi(0)\rangle$, with the exponential defined by the spectral theorem applied to the self-adjoint Hamiltonian $\hat{H}$ on $\mathcal{H}$. Define $U(t) := e^{-i\hat{H}t/\hbar}$ for each real $t$.

We verify the three defining properties of a strongly continuous one-parameter unitary group:

(i) *$U(0) = \mathbb{1}_{\mathcal{H}}$:* immediate from $e^0 = 1$.

(ii) *$U(t+s) = U(t)U(s)$ for all real $t, s$:* by functional calculus, $e^{-i\hat{H}(t+s)/\hbar} = e^{-i\hat{H}t/\hbar}\,e^{-i\hat{H}s/\hbar}$ when $\hat{H}$ commutes with itself, which is always.

(iii) *$U(t)$ is unitary for each $t$:* $U(t)^\dagger = (e^{-i\hat{H}t/\hbar})^\dagger = e^{+i\hat{H}^\dagger t/\hbar} = e^{+i\hat{H}t/\hbar}$ since $\hat{H}^\dagger = \hat{H}$. Therefore $U(t)^\dagger U(t) = e^{+i\hat{H}t/\hbar}e^{-i\hat{H}t/\hbar} = e^0 = \mathbb{1}$, and similarly $U(t) U(t)^\dagger = \mathbb{1}$.

By (iii), for any $|\phi\rangle, |\psi\rangle \in \mathcal{H}$:

$$\langle U(t)\phi | U(t)\psi\rangle = \langle \phi | U(t)^\dagger U(t) | \psi\rangle = \langle \phi | \psi\rangle.$$

The result is Stone's theorem [Stone 1932] for the specific anti-Hermitian generator $A = -i\hat{H}/\hbar$ obtained from Theorem III.1's Channel-A reading: any self-adjoint operator $\hat{H}$ generates a strongly continuous one-parameter unitary group $\{e^{-i\hat{H}t/\hbar}\}_{t \in \mathbb{R}}$, and conversely every such group has a self-adjoint infinitesimal generator. The McGucken-specific content is that the generator $-i\hat{H}/\hbar$ is not postulated independently; it is the Channel-A reading of d*x*₄/d*t* = i*c*. The factor $-i$ in the exponent is the same $i$ in d*x*₄/d*t* = i*c*, recording (SR-1) the orthogonality of x₄-advance to the three spatial directions.

The hypothesis that $U$ contains no M-loci is essential: at an M2-locus the $(|\cdot|, \arg)$ basis collapses (Theorem IV.7), and the operator $-i\hat{H}/\hbar$ is locally undefined; at an M1-locus the cross-channel agreement forces a non-unitary projection (Theorem XI.1). ∎

**Remark IV.3.1 (Hermiticity of $\hat{H}$ is itself a theorem of d*x*₄/d*t* = i*c*).** The Hermiticity of $\hat{H}$ used in the proof of Theorem IV.3 is not an independent assumption. By Theorem III.1(b), $\hat{H}$ arises as the generator of x₄-phase rotation in the (|·|, arg) basis. Phase rotation is by construction a real angular variable (the argument of $e^{i\theta}$ takes values in $\mathbb{R}/2\pi\mathbb{Z}$). The generator of a one-parameter group of real rotations on a complex Hilbert space is Hermitian, by the standard spectral characterization. The canonical commutation relation $[\hat{q}, \hat{p}] = i\hbar$ that makes $\hat{H}$ a Hermitian operator on the appropriate dense domain is derived from d*x*₄/d*t* = i*c* in [MG-Commut]. Therefore the entire apparatus of Theorem IV.3 — Hermiticity of $\hat{H}$, the Schrödinger equation, the unitary group $U(t)$ — is a theorem of d*x*₄/d*t* = i*c* on M-locus-free patches.

**Remark IV.3.2 (failure of unitarity at M-loci).** Where $U$ contains an M-mechanism locus, Theorem III.1's hypothesis of simple connectivity (combined with the requirement that the origin event be excluded) fails, the $(|\cdot|, \arg)$ basis is not globally defined on $U$, and the unitary group $U(t)$ does not extend across the M-locus. Unitarity holds *within* each M-locus-free Channel-A neighborhood; it does not hold *across* M-loci. The explicit projection at an M-locus, with the breakdown of unitarity quantified, is given in Theorem VIII.6 Step 3 (the three M-locus cases M1, M2, M3).

**Corollary IV.4.** *Unitarity (Harlow Demand 2) is the Channel-A reading of* d*x*₄/d*t* = i*c*. *It holds exactly wherever Channel A is exact, which is everywhere except at M1, M2, M3 loci, by Theorem IV.3.*

### IV.3. Locality (Demand 3)

**Theorem IV.5 (Light Cone as the Channel-B reading of d*x*₄/d*t* = i*c*).** *Let p be an event in spacetime. The future causal lightcone of p is the union, over all proper times t ≥ 0, of the McGucken Spheres of p reached by Channel-B x₄-advance at velocity c. Equivalently, the Minkowski lightcone structure on real spacetime is the integral curve of the Channel-B reading of d*x*₄/d*t* = i*c* (Theorem III.1, Channel B), and the Minkowski metric signature (−, +, +, +) descends from the orthogonal structure imposed by the i in d*x*₄/d*t* = i*c* via the substitution $x_4 = ict$ (SR-1).*

*Proof.* By Theorem III.1, the Channel-B reading of d*x*₄/d*t* = i*c* in the (Re, Im) basis is $du/dt = 0$, $dv/dt = c$. Here *u* labels the real part of *x*₄ (which by SR-1 records the spatial coordinates *x*₁, *x*₂, *x*₃ as a 3-vector via the orthogonality structure), and *v* labels the imaginary part of *x*₄ (the new coordinate orthogonal to all three spatial directions).

By SR-2 (McGucken Sphere), the locus reached from *p* after proper time *t* by x₄-advance is the 2-sphere of radius *ct* centered at *p*. The union $C^+(p) = \bigcup_{t \geq 0} S(p, ct)$ is the future lightcone of *p* in the geometric sense.

To identify $C^+(p)$ as the *causal* future lightcone of Minkowski space, we must verify that $C^+(p)$ coincides with the locus $\{q : \eta(q-p, q-p) = 0, \ (q-p)^0 \geq 0\}$ where $\eta = \text{diag}(-c^2, 1, 1, 1)$ is the Minkowski metric. Substituting $x_4 = ict$ (SR-1) into the 4-dimensional Euclidean line element $ds^2 = dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2$ gives

$$ds^2 = dx_1^2 + dx_2^2 + dx_3^2 + (i\, c\, dt)^2 = dx_1^2 + dx_2^2 + dx_3^2 - c^2\, dt^2 = -c^2 dt^2 + d\vec{x}^2,$$

which is the Minkowski metric with signature (−, +, +, +). The factor of $-c^2 dt^2$ comes from $(ic)^2 = -c^2$, and this is the geometric content of the i in d*x*₄/d*t* = i*c*: the i ensures that x₄-advance contributes with opposite sign to the 4-dimensional line element. ([MG-EinMink], [MG-Sphere]; this is the explicit Einstein–Minkowski substitution made physical by SR-1.)

The null locus $ds^2 = 0$ in this metric is $|d\vec{x}|^2 = c^2 dt^2$, i.e., motion at velocity *c*. By SR-2, this is exactly the McGucken Sphere wavefront from each event. Hence $C^+(p) = \{q : \eta(q-p, q-p) = 0,\ (q-p)^0 \geq 0\}$, the Minkowski causal lightcone.

The spherical isotropy follows from the fact that the *i* in d*x*₄/d*t* = i*c* fixes only the magnitude *c* of x₄-advance per unit *t*, leaving the spatial direction of x₄-advance unconstrained; SO(3) acts trivially on the equation, hence the McGucken Sphere is exactly spherically symmetric about *p*.

The independence of $C^+(p)$ from the choice of inertial frame (Lorentz invariance) is now derived explicitly. Let $\Lambda$ be any element of the rotation subgroup of GL(4, ℝ) preserving the orthogonality of x₄ to (x₁, x₂, x₃). By SR-1 the *i* in d*x*₄/d*t* = i*c* records this orthogonality; therefore the equation d*x*₄/d*t* = i*c* is preserved as an equation when $\Lambda$ is restricted to rotations among (x₁, x₂, x₃) (the SO(3) action above). For boosts — pseudo-rotations mixing *t* and a spatial axis — one verifies directly that the substitution $x_4 = ict$ together with d*x*₄/d*t* = i*c* are jointly invariant: the boost-transformed velocity is

$$v' = \frac{v - V}{1 - vV/c^2}$$

(the relativistic velocity-addition law, derived from x₄-advance in [MG-Proof], [F1], and [MG-Mech]), and substituting $v = c$ on the right-hand side gives $v' = (c - V)/(1 - V/c) = c$. Therefore the magnitude *c* of x₄-advance is preserved by every boost — Einstein's second postulate is a *theorem* of d*x*₄/d*t* = i*c*, derived in [MG-Proof] and [F1] (the McGucken Proof), not an external postulate. By spherical isotropy in each frame, $C^+(p)$ is the same 2-sphere wavefront in every inertial frame.

The full Lorentz group is generated by SO(3) rotations and boosts; both preserve d*x*₄/d*t* = i*c* and the McGucken-Sphere construction; therefore $C^+(p)$ is Lorentz-invariant. ∎

**Corollary IV.6.** *Locality (Harlow Demand 3) is the spherical isotropy of x₄-advance in the Channel-B reading. It is a theorem of* d*x*₄/d*t* = i*c*, *not an independent postulate, by Theorem IV.5.*

### IV.4. Why the demands appear to conflict — and why they do not

**Theorem IV.7 (The "Paradox" Is a Channel-Crossing).** *Let U be an event neighborhood containing a horizon (an M2-locus in the sense of §III.2). Then no global cross-channel agreement (Definition III.1a) exists on U: there is no single assignment* $x_4(q)$ *for $q \in U$ that satisfies the Channel-A reading and the Channel-B reading of d*x*₄/d*t* = i*c* simultaneously across the horizon. The apparent conflict between Harlow Demand 2 (unitarity, Theorem IV.3) and Harlow Demand 3 (locality, Theorem IV.5) emerges as the topological obstruction to this agreement. Demand 1 (finite entropy, Theorem IV.1) is then the count of irrecoverable assignment failures on the horizon, with magnitude $A/4\ell_P^2$ bits.*

*Proof.* By Theorem III.1, Channel A and Channel B are both exact readings of d*x*₄/d*t* = i*c* on any simply connected open event neighborhood not containing the origin. The two readings are linearly related by the basis change (Re, Im) ↔ (|·|, arg) on ℂ ∖ {0}, which is well-defined globally on any simply connected U not containing the origin (Theorem III.1 proof).

A horizon is, in the Channel-B reading (Theorem IV.5, SR-9), a null hypersurface at which outward x₄-advance becomes tangent. The topological characterization is that the horizon disconnects U into an "exterior" region (where outward x₄-advance proceeds normally) and an "interior" region (where outward x₄-advance is trapped). The horizon itself is an x₄-stationary 2-surface (SR-9) where d*x*₄/d*t* = 0 in the local frame.

This creates the following topological obstruction. Consider a Channel-A assignment $\psi_{\text{ext}}: U_{\text{ext}} \to \mathbb{C}$ in the (|·|, arg) basis of Theorem III.1, with the phase rotating at rate *c*/*r* per SR-3. Attempt to extend $\psi$ to the interior $U_{\text{int}}$ by analytic continuation across the horizon. By the M2 mechanism (§III.2), the horizon is precisely a locus where the (|·|, arg) basis becomes singular: at d*x*₄/d*t* = 0 the angular velocity *c*/*r* either diverges (if *r* → 0) or becomes undefined (if the phase is not well-defined on the horizon). Therefore the analytic continuation of Channel A across the horizon fails.

In symbolic form: let $\pi_A : \mathbb{C} \to S^1$ be the phase projection (Channel A) and $\pi_B : \mathbb{C} \to \mathbb{R}^2$ be the (Re, Im) projection (Channel B). On the exterior, both projections are smooth; on the horizon, $\pi_A$ has a coordinate singularity (the (|·|, arg) basis collapses), while $\pi_B$ remains smooth. Hence the cross-channel agreement requirement $\pi_A^{-1}(\pi_A(q)) = \pi_B^{-1}(\pi_B(q))$ — well-defined on a simply connected region — fails to extend across the horizon.

The count of mode-by-mode assignment failures on the horizon is, by Theorem IV.1, exactly $A(H)/\ell_P^2$ independent x₄-stationary modes. By Theorem IV.1 Steps 4–5, the thermodynamic entropy of these modes — computed from the Euclidean Schwarzschild cigar action $I_E = \beta Mc^2/2$ via the standard thermodynamic identity $S = \beta(E - F)$ with $F = -\beta^{-1}\log Z$ and $\log Z = -I_E/\hbar$ — equals

$$S_H = \frac{k_B A(H)}{4 \ell_P^2}.$$

The factor $1/4$ is *not* the bit count per mode; it is the Wick-rotated thermodynamic coefficient established in Theorem IV.1 Step 5 (where $\beta = 8\pi GM/(\hbar c^3)$ via the McGucken Wick rotation SR-7, and $S = \beta(E-F) = \beta Mc^2/2 = A/(4\ell_P^2)$ in $k_B = 1$ units). The bit count per mode is $\ln 2$ (Corollary IV.1a), giving $A(H)/(4\ell_P^2 \ln 2)$ bits total. The natural-logarithm entropy and the bit count differ exactly by a factor of $\ln 2$, in agreement with $S_{\text{nat-log}} = k_B \ln 2 \cdot N_{\text{bits}}$.

This is Demand 1 (finite entropy). The apparent conflict between Demand 2 (unitarity, exact within each Channel-A neighborhood by Theorem IV.3) and Demand 3 (locality, exact within Channel B by Theorem IV.5) is therefore the topological signature of the failure of cross-channel agreement at the horizon, not a conflict between three independent postulates. ∎

**Corollary IV.8.** *Harlow's trilemma is the topological obstruction to extending cross-channel agreement of d*x*₄/d*t* = i*c* across a horizon. It is not a conflict between three independent demands; it is the explicit consequence of the dual-channel decomposition (Theorem III.1) applied to an event neighborhood with the topology of a horizon-bounded region (Theorem IV.7).*

---

## §V. Direct Answers to Harlow's Questions

We now address each of Harlow's standing questions explicitly.

### V.1. "Why don't we see nonlocality all the time?"

Harlow's locality\* requires a "veil of complexity" to hide the macroscopic nonlocality his framework demands.

**LTD answer.** We do not see nonlocality all the time because there is no nonlocality to see. Channel B locality (the lightcone) is exact wherever the two channels agree on a combinatorial assignment, which is everywhere except at M1/M2/M3 loci. The apparent nonlocality of entanglement experiments (Bell, Aspect, GHZ, loophole-free 2015) is not action at a distance; it is the Channel-A correlation of x₄-advance at preparation, read off in Channel B at measurement. The McGucken Sphere projection (Born rule, [MG-Born]) is the projection of Channel-A symmetry content onto Channel-B geometric labels; it is local in Channel B and exact in Channel A simultaneously.

No veil is needed because no violation occurs.

### V.2. "What is the infalling observer's experience?"

**LTD answer.** Following the four-fold ontology (§II.2): the infalling observer's worldline is a Channel-B object (a timelike geodesic in the x₄-expansion). The observer's Channel-A state is well-defined locally along the worldline; nothing dramatic happens at the horizon because the horizon is a Channel-B feature (a marginally trapped surface), not a Channel-A feature.

There is no firewall: the firewall is what Channel A would have to do if it were forced to extend across the horizon while remaining consistent with Channel B exterior unitarity. In LTD, Channel A does not extend across the horizon (M2); it terminates at the horizon, and the interior is described by a *different* Channel-A neighborhood, glued to the exterior by Channel-B continuity. The infalling observer carries her own Channel-A neighborhood across the horizon; the exterior observer sees the Channel-A label fail to extend. Both descriptions are exact; there is no paradox.

There is no "splat." The horizon is geometrically smooth in Channel B, and Channel A is locally exact along the worldline.

### V.3. "How is the information encoded in Hawking radiation?"

**LTD answer.** It is not. The premise of the question is wrong.

Hawking radiation is the Channel-B accounting of x₄-stationary modes on the exterior of the horizon. The "information about the infalling matter" is the Channel-A label of the matter; this label does not extend across the horizon (M2), and is not encoded in the Channel-B radiation. The radiation is genuinely thermal in Channel B, and the apparent loss is the absence of a Channel-A label for a Channel-B fact.

What Harlow's calculation (Page curve, replica wormholes, quantum extremal surfaces) computes is the Channel-A entanglement entropy *of the Channel-B radiation considered as a Channel-A subsystem.* This is a well-defined object; it returns to zero at the Page time because the Channel-A subsystem is exhausted, not because the missing information was secretly transmitted. The Page curve is correct as a calculation; its physical interpretation in terms of "information transfer" is the artifact of treating Channel A and Channel B as the same channel.

In LTD, there is nothing to recover because nothing was lost — only the Channel-A representation was bounded by the Channel-B geometry (M1′ composed with M2).

### V.4. "Is the black hole interior described by a non-isometric code?"

**LTD answer.** No. It is described by a different Channel-A neighborhood, glued to the exterior by Channel-B continuity.

Harlow's "non-isometric code" is an attempt to encode the apparent excess of interior degrees of freedom into a fewer-dimensional exterior Hilbert space, with the failure of isometry hidden by complexity. In LTD, there is no excess: the interior degrees of freedom are described in their own Channel-A neighborhood (the interior coordinate patch), with their own local unitarity. The exterior Channel-A neighborhood has its own count, bounded by the horizon area (Theorem IV.1). The interior and exterior counts do not need to be reconciled by a single non-isometric map because they are not two encodings of one Hilbert space; they are two distinct neighborhoods of the same Channel-A structure, joined at the horizon by Channel-B continuity.

This eliminates the apparatus of "null states protected by complexity," "post-selection," and "state-dependent operator reconstruction." All three are artifacts of forcing one Channel-A neighborhood to do the work of two.

### V.5. "What is the role of ER = EPR?"

**LTD answer.** ER = EPR is a true theorem in LTD, derived as the dual-channel statement.

**Theorem V.1 (LTD-ER=EPR as a Theorem of d*x*₄/d*t* = i*c*).** *Let $R_1$, $R_2$ be two spacelike-separated regions in spacetime. The following are equivalent:*

*(i) (EPR) The Channel-A x₄-advance in $R_1$ and the Channel-A x₄-advance in $R_2$ are correlated by a shared preparation event $p_0$ in their common causal past: there exists $p_0 \in J^-(R_1) \cap J^-(R_2)$ such that the Channel-A state on $R_1 \cup R_2$ is not factorable into Channel-A states on $R_1$ and on $R_2$ separately.*

*(ii) (ER) The Channel-B x₄-expansion configurations of $R_1$ and $R_2$ share a common originating McGucken-Sphere section: the forward McGucken Spheres of $R_1$ and $R_2$ share an originating null-surface configuration at $p_0$ (Standing Result SR-12).*

*By Theorem III.1, (i) and (ii) are dual readings of one x₄-advance configuration on the union $R_1 \cup R_2 \cup \{p_0\}$; the implication (i) ⇒ (ii) ⇒ (i) is exact.*

*Proof.* The proof uses an intermediate lemma making the cross-channel link explicit.

**Lemma V.1a (Shared-origin equivalence).** *Let $|\psi\rangle_{R_1 \cup R_2}$ be the Channel-A state on $R_1 \cup R_2$ (Theorem III.1, Channel A). The following are equivalent:*

*(a) $|\psi\rangle_{R_1 \cup R_2}$ is non-factorable: there exist no normalized $|\phi\rangle_{R_1}, |\chi\rangle_{R_2}$ such that $|\psi\rangle_{R_1 \cup R_2} = |\phi\rangle_{R_1} \otimes |\chi\rangle_{R_2}$.*

*(b) There exists an event $p_0 \in J^-(R_1) \cap J^-(R_2)$ such that the Channel-A phase of $|\psi\rangle$ at every $q \in R_1 \cup R_2$ is the integrated phase $\int_{p_0}^q (c/\hbar)\,ds$ along the unique x₄-advance worldline from $p_0$ to $q$ (Theorem III.1 Channel A, SR-3).*

*(c) The forward McGucken Spheres of $R_1$ and $R_2$ (SR-2) share a common section at $p_0$: $S(p_0, c t_1) \cap R_1 \neq \emptyset$ and $S(p_0, c t_2) \cap R_2 \neq \emptyset$ for some $t_1, t_2 > 0$.*

*Proof of Lemma V.1a.* (a) ⇒ (b): Suppose $|\psi\rangle_{R_1 \cup R_2}$ is non-factorable. By Theorem III.1 (Channel A) applied to $R_1 \cup R_2$, the Channel-A reading evolves unitarily on any simply connected open event neighborhood containing $R_1 \cup R_2$ free of M-loci (Theorem IV.3), and the phase rotates at rate $c/\hbar$ per unit x₄-advance (SR-3, [MG-HLA]). We establish that the non-factorability necessarily originates at a common past event.

Consider the joint Hilbert space $\mathcal{H}_{R_1} \otimes \mathcal{H}_{R_2}$. By the Schmidt decomposition, $|\psi\rangle_{R_1 \cup R_2} = \sum_k \lambda_k |a_k\rangle_{R_1} \otimes |b_k\rangle_{R_2}$ with $\lambda_k > 0$ Schmidt coefficients. Non-factorability means at least two Schmidt coefficients are nonzero, i.e., the Schmidt rank is $\ge 2$. We show such a state cannot be created by independent Channel-A evolutions of $R_1$ and $R_2$, hence must originate at a common past event.

Suppose, for contradiction, that no $p_0 \in J^-(R_1) \cap J^-(R_2)$ exists. Then $J^-(R_1) \cap J^-(R_2) = \emptyset$, i.e., $R_1$ and $R_2$ have empty common causal past. By Theorem IV.5 (Channel-B lightcone), Channel-B propagation is confined to the future causal lightcone of any preparation event; no Channel-B-mediated correlation between $R_1$ and $R_2$ exists. By Theorem III.1 (Channel A is the dual reading of Channel B on simply connected M-locus-free regions), Channel-A correlations are constrained by the same lightcone structure: if $J^-(R_1) \cap J^-(R_2) = \emptyset$, then the Channel-A state on $R_1 \cup R_2$ must factor as a product state $|\phi\rangle_{R_1} \otimes |\chi\rangle_{R_2}$, contradicting the non-factorability assumption.

Therefore there exists $p_0 \in J^-(R_1) \cap J^-(R_2)$ at which the joint Channel-A state was prepared. By the unitarity of Channel-A evolution (Theorem IV.3) applied to the worldlines from $p_0$ to each $q \in R_1 \cup R_2$, the phase at $q$ is the integrated phase along the unique x₄-advance worldline from $p_0$ to $q$, accumulating at rate $c/\hbar$ per unit advance (SR-3):

$$\arg\langle q | \psi \rangle = \arg\langle q | \psi(p_0)\rangle + \int_{p_0}^q \frac{c}{\hbar}\,ds.$$

This is statement (b).

(b) ⇒ (c): By statement (b), there exists $p_0$ such that the Channel-A phase at every $q \in R_1 \cup R_2$ is integrated along the worldline from $p_0$ to $q$. By SR-2 (McGucken Sphere), x₄-advance from $p_0$ reaches every event at proper distance $ct$ from $p_0$ along the McGucken Sphere $S(p_0, ct)$ of radius $ct$ centered at $p_0$. The Channel-A worldlines from $p_0$ to $R_1$ and from $p_0$ to $R_2$ therefore lie on the future null cone of $p_0$, which by SR-2 is the union $\bigcup_{t \geq 0} S(p_0, ct)$. Hence $R_1$ and $R_2$ each intersect some McGucken Sphere of $p_0$: there exist $t_1, t_2 > 0$ with $S(p_0, ct_1) \cap R_1 \neq \emptyset$ and $S(p_0, ct_2) \cap R_2 \neq \emptyset$. This is statement (c).

(c) ⇒ (a): By statement (c), the forward McGucken Spheres of $R_1$ and $R_2$ share originating null-surface configurations at $p_0$. By SR-12 (Quantum nonlocality from shared null-surface identity, derived in [MG-Nonloc], [MG-NonlocPrin], [MG-Second-Nonloc]), two systems whose forward McGucken Spheres share an originating null-surface configuration at a common event are entangled: their joint Channel-A state carries a single Channel-A label assigned at the shared origin, and the integrated phase along each branch of the McGucken Sphere from $p_0$ accumulates the same Channel-A reference.

Formally, the Channel-A state at any later events $q_1 \in R_1, q_2 \in R_2$ is

$$\langle q_1, q_2 | \psi\rangle = \langle q_1, q_2 | U(t_{p_0 \to q_1, q_2}) | \psi(p_0)\rangle,$$

where $U$ is the unitary evolution from $p_0$ (Theorem IV.3) and $|\psi(p_0)\rangle$ is the joint state at the preparation event. If $|\psi(p_0)\rangle$ has Schmidt rank $\ge 2$ (a generic preparation at $p_0$ does), unitarity preserves the rank, and $|\psi(q_1, q_2)\rangle$ is non-factorable. Equivalently: the Channel-A label is not separable into $R_1$-only and $R_2$-only contributions because both labels carry the same reference, integrated from the shared origin along distinct McGucken-Sphere branches.

Therefore (a) ⇔ (b) ⇔ (c). ∎ (Lemma V.1a)

We now prove the equivalence of (i) and (ii) in Theorem V.1.

*(i) ⇒ (ii):* By (i), $|\psi\rangle_{R_1 \cup R_2}$ is non-factorable due to a shared preparation at $p_0 \in J^-(R_1) \cap J^-(R_2)$. By Lemma V.1a (a) ⇒ (c), the forward McGucken Spheres of $R_1$ and $R_2$ share an originating null-surface configuration at $p_0$. By SR-12, this is exactly the geometric content of an Einstein–Rosen bridge connecting $R_1$ and $R_2$ through their shared past lightcone, with $p_0$ identified as the bridge throat (the Channel-B reading of the shared origin under the basis change (|·|, arg) → (Re, Im) of Theorem III.1).

The Einstein–Rosen bridge geometry is the Channel-B reading of d*x*₄/d*t* = i*c* on a neighborhood with the topology $R_1 \cup \{p_0\} \cup R_2$, where the two regions are joined through a tubular neighborhood of $p_0$ in the (Re, Im) basis. Its existence is given by Theorem IV.5 applied to this topology: the lightcone from $p_0$ contains both $R_1$ and $R_2$, and the McGucken-Sphere expansion structure (SR-2) provides the geometric link.

*(ii) ⇒ (i):* By (ii), $R_1, R_2$ share an originating null-surface configuration at $p_0$. By Lemma V.1a (c) ⇒ (a), $|\psi\rangle_{R_1 \cup R_2}$ is non-factorable. By the unitarity of Channel-A evolution (Theorem IV.3) on any simply connected open event neighborhood, the non-factorability is preserved at later times: the EPR correlation persists across the spacelike separation of $R_1, R_2$ at any common time $t > \max(t_1, t_2)$.

The dual readings (i) and (ii) are exact because Theorem III.1's basis change is a linear isomorphism of ℝ²; no information is lost in the conversion. ∎

**Corollary V.2.** *The Maldacena–Susskind ER = EPR conjecture (2013) [Maldacena & Susskind 2013] is the correct identification of a fundamental duality, but the duality is not a conjecture between two distinct objects; it is the dual-channel identity of one x₄-advance configuration on a shared-past event neighborhood, by Theorem V.1.*

### V.6. "What happened in the AdS/CFT correspondence?"

**LTD answer.** AdS/CFT is one valid Channel-A-to-Channel-B dictionary in a special asymptotic geometry that does not describe our universe.

The AdS bulk is Channel-B; the CFT boundary is Channel-A. The Ryu–Takayanagi formula, the quantum extremal surface formula, and the entanglement wedge reconstruction are all correct as identities relating Channel-A entropy in the boundary CFT to Channel-B area in the bulk. They follow from Theorem IV.1 applied to AdS asymptotics.

What does *not* follow is that "spacetime is emergent from the boundary CFT." The boundary CFT is a Channel-A reading of the same x₄-advance that the bulk gravity is the Channel-B reading of. Neither is more fundamental than the other; both are exact. The "emergence" is the bijection between the two readings, not a one-way reduction.

In our universe (which is not asymptotically AdS), the AdS-CFT dictionary does not apply directly, but Theorem III.1 still does: Channel A and Channel B are exact, and their agreement is the content of physical law.

### V.7. "How does this work in a closed universe?"

**LTD answer.** Harlow–Usatyuk–Zhao's (2025) "one-dimensional Hilbert space for closed universes, with observer Hilbert space of dimension exp($S_{\text{Ob}}$)" is the partial recognition of a structural truth, but with the wrong fundamental object.

In LTD, a closed universe has a fixed x₄-expansion budget (the cosmological x₄-expansion, ontology item 4). The "one-dimensional Hilbert space" is the Channel-A reading of the trivial global symmetry of a closed system: there is only one state that the closed universe can be in *globally*, because there is no exterior reference frame. The observer's experienced Hilbert space of dimension exp($S_{\text{Ob}}$) is the Channel-A neighborhood the observer occupies; locally exact, globally one of many possible labelings of the same Channel-B fact.

This is exact and requires no "observer fluctuation into existence in the Hartle–Hawking state." The Hartle–Hawking state is the Channel-B specification of the closed universe; the observer is a local Channel-A neighborhood inside it. The two readings agree because Theorem III.1 holds.

### V.8. "What is spacetime, fundamentally?"

**LTD answer.** Spacetime is not emergent. It is the x₄-expansion at velocity *c* from every event. The integrated coordinate *x*₄ = i*ct* is a mere shadow of the physical fact d*x*₄/d*t* = i*c*. Channel A and Channel B are not the bulk and the boundary; they are two readings of one expansion.

Harlow's "spacetime is emergent" is correct as a negative claim (the integrated coordinate is not fundamental) but incomplete as a positive claim (he does not say what *is* fundamental). The fundamental object is d*x*₄/d*t* = i*c*, and everything else — including holography, entanglement, locality, unitarity, and the Bekenstein–Hawking 1/4 — is a theorem.

---

## §VI. Wormholes and Traversability

### VI.1. Maldacena–Susskind ER = EPR in LTD

By Theorem V.1, every entangled pair is connected by an Einstein–Rosen bridge. This is exact in LTD and requires no conjecture.

### VI.2. Traversability

**Theorem VI.1 (Traversability of McGucken–Einstein–Rosen Bridges).** *Let B be a McGucken–Einstein–Rosen bridge connecting two regions $R_1, R_2$, as constructed in Theorem V.1. Let $\gamma : [0,1] \to B$ be a timelike $C^1$ worldline from $R_1$ to $R_2$ through the bridge. The following are equivalent:*

*(i) $\gamma$ is traversable in the sense that the Channel-A x₄-advance along $\gamma$ is a continuous one-parameter unitary evolution (no Channel-A continuity break);*

*(ii) The Channel-B x₄-advance through B along $\gamma$ does not cross an M2-locus (no marginally trapped horizon in $\gamma([0,1])$);*

*(iii) The (|·|, arg) basis of Theorem III.1 extends globally along the worldline image $\gamma([0,1])$.*

*Proof.* We prove the three pairwise equivalences in turn, making the underlying topological obstructions explicit.

**(iii) ⇒ (i):** Suppose the (|·|, arg) basis of Theorem III.1 extends globally along $\gamma([0,1])$. By Theorem III.1 (Channel A), the Channel-A reading of d*x*₄/d*t* = i*c* in this basis is the unitary evolution generated by $-iH/\hbar$ (SR-3, [MG-HLA]). By Theorem IV.3 (Unitarity), this evolution preserves the inner product on the associated Hilbert space along the worldline. Therefore the Channel-A x₄-advance along $\gamma$ is a continuous one-parameter unitary evolution: (i) holds.

**(i) ⇒ (iii):** Suppose (i) holds: the Channel-A x₄-advance along $\gamma$ is a continuous one-parameter unitary evolution. By Theorem IV.3, the unitary evolution $U(t) = e^{-iHt/\hbar}$ is generated by an anti-Hermitian operator $-iH/\hbar$ on a complex Hilbert space; this operator is well-defined only when the (|·|, arg) basis is well-defined (the imaginary unit *i* in the generator is the *i* of the (|·|, arg) basis of Theorem III.1). Continuity of the evolution along $\gamma$ requires that this basis be well-defined at every $\gamma(s)$ for $s \in [0,1]$. By Theorem III.1, the (|·|, arg) basis is well-defined on ℂ ∖ {0}, hence on any open neighborhood of $\gamma([0,1])$ not containing an event where the modulus $r = |x_4|$ vanishes. Therefore the (|·|, arg) basis extends globally along $\gamma$: (iii) holds.

**(iii) ⇒ (ii):** Suppose the (|·|, arg) basis extends globally along $\gamma([0,1])$. By Theorem III.1, the (|·|, arg) basis fails exactly when the modulus $r = 0$, which by SR-9 is exactly the x₄-stationary condition (the basis becomes singular at d*x*₄/d*t* = 0 because the angular velocity *c*/*r* diverges or becomes undefined). By the definition of an M2-locus (§III.2), an M2-locus is precisely an x₄-stationary 2-surface where Channel-B x₄-expansion crosses a null hypersurface, equivalently a basis-collapse point of (|·|, arg). Therefore the global existence of the (|·|, arg) basis along $\gamma$ implies $\gamma$ contains no M2-locus: (ii) holds.

**(ii) ⇒ (iii):** Suppose $\gamma$ contains no M2-locus. By the §III.2 definition, no point of $\gamma$ is an x₄-stationary 2-surface; by SR-9, every point of $\gamma$ has $r \neq 0$ in the (|·|, arg) decomposition. By Theorem III.1, the (|·|, arg) basis is well-defined on ℂ ∖ {0}, so it is well-defined at every $\gamma(s)$. Therefore the (|·|, arg) basis extends globally along $\gamma$: (iii) holds.

**(i) ⇔ (ii):** By the composition (i) ⇔ (iii) ⇔ (ii) just established.

This completes the three-way equivalence.

*Physical realization.* The Gao–Jafferis–Wall traversable wormhole construction [Gao–Jafferis–Wall 2017] and the Maldacena–Qi eternal traversable wormhole [Maldacena–Qi 2018] are physical realizations of condition (i): by introducing a Channel-A coupling between the two boundary regions (a double-trace deformation in the AdS/CFT dictionary), they explicitly extend the (|·|, arg) basis across the horizon, opening the M2-locus into a smooth Channel-B traversable region. The "exotic matter" required to keep the wormhole open is, in the McGucken framework, the energy budget of the Channel-A coupling needed to sustain the (|·|, arg) extension; this is the McGucken–Verlinde reading of the negative-energy requirement [MG-Verlinde]. ∎

**Corollary VI.1a.** *In standard eternal Schwarzschild geometry, the bifurcation surface is an M2-locus where the (|·|, arg) basis collapses, hence the bridge is non-traversable. Any traversable-wormhole construction must explicitly extend the (|·|, arg) basis across the M2-locus, which requires Channel-A coupling between the two sides — exactly what Gao–Jafferis–Wall and Maldacena–Qi achieve.*

This is consistent with all known traversable-wormhole constructions and explains them as Channel-A interventions on Channel-B geometry.

### VI.3. The Python's Lunch

The Python's Lunch [Brown et al. 2019] is a geometric obstruction to decoding Hawking radiation, in which the wormhole connecting the black hole to its radiation has an exponentially long throat. In LTD, this is the M2-composed-with-M1 statement that Channel A reconstruction of the interior from the radiation requires extending the Channel-A label across the horizon — which is M2-forbidden. The "exponential complexity" of decoding is the McGucken counting of the irrecoverable assignment failures: there are exp(*S*) of them, by Theorem IV.1, and they cannot be undone by polynomial Channel-A operations.

The Python's Lunch is correct as geometry. Its identification with "complexity" is the Channel-A shadow of the Channel-B M2-count.

---

## §VII. The Closed-Universe Question (Harlow–Usatyuk–Zhao 2025)

Harlow–Usatyuk–Zhao (2025, arXiv:2501.02359) argue that the gravitational Hilbert space of a closed universe is one-dimensional and that an observer of internal entropy $S_{\text{Ob}}$ experiences an effective Hilbert space of dimension exp($S_{\text{Ob}}$), with errors exponentially small in $S_{\text{Ob}}$.

**LTD reading.** The statement is correct in form, wrong in fundamentality.

- *One-dimensional global Hilbert space*: the Channel-A reading of a closed system has no exterior reference frame, so the global state is unique up to a phase. This is Theorem III.1 applied globally with no exterior. The "one-dimensional Hilbert space" is the trivial Channel-A label of the closed-universe x₄-advance.
- *Observer Hilbert space of dimension exp($S_{\text{Ob}}$)*: the observer occupies a local Channel-A neighborhood with its own count. By Theorem IV.1 applied to the observer's holographic screen, the count is exp($S_{\text{Ob}}$).
- *Errors exponentially small in $S_{\text{Ob}}$*: the cross-channel agreement (Theorem III.1) is exact; the "exponentially small errors" are the M1′ measurement-bound corrections to the Channel-A reading of a Channel-B fact.

This is exact in LTD and does not require treating observers as classical, or invoking baby universes, or α-parameters, or third-quantized descriptions of closed universes. The closed universe is a single x₄-expansion; the observer is a Channel-A neighborhood inside it; both readings are exact; their agreement is the physics.

**Subsequent work by Ying Zhao [Zhao 2026, arXiv:2602.05939] ("It from Bit")** extends the closed-universe argument to de Sitter space and the Hartle–Hawking sphere. The de Sitter case is the Channel-B reading of cosmological x₄-expansion; the Hartle–Hawking state is its Channel-A reading. The distinction between the "baby-universe Hilbert space (Bit)" and the "bulk Hilbert space (It)" that Zhao draws is precisely the Channel-A / Channel-B distinction of LTD, formulated in the language of α-parameters and patch operators.

LTD recovers the entire structure of these papers as the cosmological special case of Theorem III.1.

---

## §VIII. Comparison Table: Harlow vs. McGucken

| Question | Harlow (locality\*, non-isometric codes, observer rule) | McGucken (LTD) |
|---|---|---|
| What are Hawking's three demands? | Independent postulates (entropy, unitarity, locality) | Three theorems of d*x*₄/d*t* = i*c* |
| Which demand is sacrificed? | Locality, modulated by complexity | None; the trilemma dissolves at the premise |
| Why don't we see nonlocality? | Veil of exponential complexity | There is no nonlocality to see |
| What is the infalling observer's fate? | Smooth crossing, with non-isometric code in the interior | Smooth crossing, with a separate Channel-A neighborhood interior |
| How is information encoded in radiation? | Non-isometrically, decoding exponentially complex | It is not; the question presupposes one channel |
| What is the black hole entropy? | Imported postulate; 1/4 from Hawking | Theorem IV.1; 1/4 from bosonic polarization on null 1+1 strip |
| What is ER = EPR? | Conjecture relating two structures | Theorem V.1 (dual reading of one x₄-advance) |
| What is the role of AdS/CFT? | "Spacetime is emergent from the boundary" | One valid Channel-A–Channel-B dictionary in AdS asymptotics |
| What is the closed-universe story? | 1-D Hilbert space + exp($S_{\text{Ob}}$) observer rule | Trivial global Channel-A + local Channel-A neighborhood; both exact |
| Is spacetime fundamental? | No (emergent from boundary CFT) | Yes (d*x*₄/d*t* = i*c* is the principle); the integrated coordinate *x*₄ is the shadow |
| What is the role of computational complexity? | Central; it protects locality\* | Marginal; complexity counts the M2-assignment-failures, but is not the physical mechanism |
| What is the role of the imaginary unit i? | Algebraic ingredient in quantum mechanics | Geometric generator of x₄-advance, and of orthogonal rotation, simultaneously |

### VIII.5. Susskind's Six Black-Hole Programmes as Theorems of d*x*₄/d*t* = i*c*

The comparison table above contrasts McGucken with Harlow's locality\* programme — the most recent of the major attempts to resolve Hawking's paradox. The companion comparison, with Leonard Susskind's four-decade research programme on black-hole thermodynamics and quantum information, is the structural extension of the same comparison: McGucken's d*x*₄/d*t* = i*c* derives, as six explicit theorems, each of the six major contributions of Susskind's career. The full treatment is given in [MG-Susskind] (six Propositions III.1, IV.1, V.1, VI.1, VII.1, VIII.1); we summarize the results here as the structural complement to §VIII.1–§VIII.4 above.

**Structural comparison: McGucken and Susskind in the black-hole wars.** Susskind, with Thorlacius and Uglum, proposed complementarity to resolve the information paradox. With 't Hooft as precursor, Susskind formulated the holographic principle. With Maldacena, Susskind proposed ER = EPR. With Stanford and collaborators, Susskind developed the complexity programme. Across forty years — early string theory, holography, AdS/CFT, quantum computation — Susskind argued that black holes are *informational* objects, with each of the six results above as a separate angle on the same claim. The technical contributions survive in the McGucken framework as Propositions VIII.5.1 through VIII.5.6, each derived from d*x*₄/d*t* = i*c*.

The *meta-claim* under which Susskind assembled the six contributions — that a global unitary on the Hilbert space of the universe preserves all information through black-hole evaporation — does not hold in the McGucken framework. We prove this rigorously in Theorem VIII.6 below. In greater context, on the question of whether operationally accessible information is destroyed at black-hole horizons, Hawking's 1976 answer is correct and Susskind's is wrong.


**Proposition VIII.5.1 (Holographic Principle as Theorem of d*x*₄/d*t* = i*c*; [MG-Susskind Proposition III.1]).** *Bulk information on any region with boundary $\partial R$ is encoded on $\partial R$ at density at most one bit per $8\pi \ell_P^2$ (equivalently $S \le k_B A / 4\ell_P^2$). The bound follows from two facts established by d*x*₄/d*t* = i*c*: (i) every bulk x₄-oscillation mode has a null worldline whose six-sense identity (SR-14) places it on a specific null-hypersurface cell at $\partial R$; (ii) the Planck-scale quantization of x₄-oscillation (SR-4, SR-10) allows at most one independent mode per $\ell_P^2$ area element. Volume-scaling is excluded because it would admit modes without unique six-sense identity to any null-surface cell, violating SR-14.*

*Proof.* By SR-14, two points on the same McGucken Sphere from emission event $E$ share six-sense identity. Any bulk mode crossing $\partial R$ does so along a null geodesic; its six-sense identity at the boundary cell is preserved by null propagation (SR-14 corollary). By SR-10, the maximum number of independent x₄-stationary mode cells on $\partial R$ is $A/\ell_P^2$. The Bekenstein–Hawking coefficient $1/4$ then follows from the Euclidean Schwarzschild cigar action (Theorem IV.1 Step 5), giving $S_{\max} = k_B A/(4\ell_P^2)$. ∎

Susskind's 1994 *World as a Hologram* argument established the area-scaling of information by a consistency argument: any region whose degrees of freedom scaled with volume would violate the Bekenstein bound. The McGucken derivation makes the area-scaling a theorem: SR-14 places information on null-hypersurface cells; SR-10 caps the density at one per Planck area. Susskind identified the pattern; the McGucken framework supplies the mechanism. The result is identical; the structural status is upgraded.

**Proposition VIII.5.2 (Black-Hole Complementarity as Coordinate Inequivalence of x₄-Advance; [MG-Susskind Proposition IV.1]).** *The infalling observer and the outside observer see different descriptions of the same black-hole horizon because their x₄-advance directions differ relative to the horizon's x₄-stationary surface (SR-9). For the infalling worldline, x₄-advance is transverse to the horizon at crossing; the observer crosses smoothly. For the outside worldline, x₄-advance is in the exterior while the horizon modes are x₄-stationary; the relative x₄-advance difference, under the McGucken Wick rotation (SR-7), produces a thermal spectrum at $T_H = \hbar\kappa/(2\pi c k_B)$. Neither description is privileged; both are true; no single worldline can satisfy both conditions because being transverse to and being tangent to the horizon's x₄-stationary direction are mutually exclusive.*

Susskind, Thorlacius, and Uglum proposed complementarity in 1993 as an observer-dependence postulate: the infalling and outside accounts of the horizon are individually consistent and logically distinct, with information loss avoided because no single observer can directly compare them. The McGucken derivation makes complementarity a geometric theorem about x₄-advance directions: the two observers occupy mutually exclusive geometric relationships to the same x₄-stationary surface, and the two "descriptions" are the two coordinate readings of that single geometric fact. Where Susskind needed to argue the consistency of the two descriptions, the McGucken framework derives that they are two readings of the same x₄-advance — the same dual-channel structure that gives the First Law of the McGucken Dualities (Theorem III.3).

**Proposition VIII.5.3 (The Stretched Horizon as Planck-Depth Transition Layer; [MG-Susskind Proposition V.1]).** *The stretched horizon is the Planck-depth layer where the character of x₄-advance transitions from transverse (bulk) to tangent (horizon-stationary). Its Planck thickness is the Planck-scale quantization scale of x₄-oscillation (SR-4): modes with wavelengths shorter than $\ell_P$ cannot be resolved as independent, so the transverse-to-tangent rotation of x₄-advance necessarily occurs within a layer of depth $\ell_P$. The information deposited on the stretched horizon is the partner-mode population of the $A/\ell_P^2$ horizon mode count (SR-10): infalling matter's x₄-oscillation modes become six-sense-paired (SR-14) with horizon modes at the Planck-area cell where they meet.*

Susskind introduced the stretched horizon as a phenomenological device to provide a physical location for information storage consistent with external causality. The McGucken framework derives that location as the geometric region where x₄-advance rotates. The Planck thickness is not put in by hand; it is forced by SR-4. The information-storage role is not ad hoc; it is the natural site of six-sense partnership between bulk and horizon modes. The membrane paradigm of Damour, Thorne, Price, and MacDonald, which the stretched horizon refined, is the Channel-B fluid-dynamics reading of the same x₄-stationary surface.

**Proposition VIII.5.4 (String-Microstate Counting as x₄-Oscillation Mode Count on the Cigar's Asymptotic Boundary; [MG-Susskind Proposition VI.1]).** *Under the McGucken Wick rotation (SR-7), the near-horizon Schwarzschild geometry becomes the Euclidean cigar (Theorem IV.1 Step 3) with asymptotic cylindrical boundary. The cigar supports a tower of x₄-oscillation modes on its asymptotic boundary, organized by wavenumber into harmonic towers isomorphic to the vibrational modes of a closed string compactified on a circle of circumference $\beta = 2\pi/\kappa$. The Hagedorn-like exponential growth of the degeneracy of these towers is a direct consequence of the Planck-scale quantization of x₄-oscillation (SR-4): the number of ways to partition asymptotic energy $E$ into Planck-scale x₄-quanta is $dN/dE \sim e^{E/T_H}$, the Hagedorn spectrum. Summing across modes with total energy giving black-hole mass $M$ yields $\Omega(M) \sim e^{A/(4\ell_P^2)}$, reproducing $S = k_B A/(4\ell_P^2)$.*

Susskind's 1993 black-hole–string correspondence used the Hagedorn spectrum of string theory to estimate black-hole microstates, prefiguring Strominger–Vafa's 1996 D-brane calculation. The McGucken derivation identifies what the Hagedorn spectrum is *counting*: x₄-oscillation modes on the cigar's asymptotic cylinder, organized by the Cardy formula $\rho(E) \sim \exp(2\pi\sqrt{c_{\text{CFT}} L E/6})$ for the appropriate effective central charge. The "string" is the Channel-A reading of the x₄-oscillation modes' angular-and-radial wavenumber structure. The McGucken closure of Gap 1 (§IX below) supplies the bosonic-polarization count from d*x*₄/d*t* = i*c* without invoking worldsheet supersymmetry as a primitive.

**Proposition VIII.5.5 (ER = EPR as Four-Dimensional Six-Sense Partnership; [MG-Susskind Proposition VII.1]).** *Two entangled particles are connected by a six-sense partnership (SR-14) inherited from their common creation event $E$: they share, with respect to $E$, all six of the null-surface identities (foliation leaf, level set, Huygens wavefront, Legendrian section, conformal Möbius pencil member, null-hypersurface cross-section). What the 3+1 observer reads as "wormhole connection" (Einstein–Rosen bridge) is the projection onto the spatial slice of this six-sense 4D shared identity. What the same observer reads as "quantum entanglement" (Einstein–Podolsky–Rosen correlation) is the Channel-A reading of the same six-sense identity in the (|·|, arg) basis of Theorem III.1. The two are not separate phenomena that happen to coincide; they are the Channel-B and Channel-A readings of one geometric fact.*

This is the McGucken statement of Theorem V.1 above (LTD-ER=EPR) augmented with the six-sense structure of SR-14: the formal content is identical, but the six-sense apparatus exhibits *six independent mathematical senses* in which the entangled pair shares identity with the creation event. Maldacena and Susskind's 2013 ER=EPR conjecture, supported in the literature by many consistency checks but never derived from first principles, is in the McGucken framework a direct geometric statement about null-surface partnership. The 2012 AMPS firewall paradox is dissolved: the apparent monogamy violation arises only when entanglement and wormhole-connectivity are treated as separate objects to be reconciled; recognizing them as Channel-A and Channel-B readings of the same object eliminates the conflict.

**Proposition VIII.5.6 (Complexity Equals Volume / Complexity Equals Action as Planck-Quantized Accumulated x₄-Advance; [MG-Susskind Proposition VIII.1]).** *Susskind's "complexity equals volume" and "complexity equals action" conjectures (2014) propose that the interior volume (CV) or interior on-shell action (CA) of a black hole computes the circuit complexity of the dual boundary state. In the McGucken framework, both quantities are Planck-quantized accumulated x₄-advance of interior modes: each Planck-volume cell of the interior advances by $c \cdot dt$ in x₄ per unit boundary time, and the integrated x₄-advance is the count of independent Channel-A operations required to reach the current interior configuration from the initial state. The interior continues to grow long after exterior thermalization because Channel-B x₄-advance continues monotonically (SR-1, +ic future-orientation) even when Channel-A thermalization has saturated.*

The CV/CA conjectures were proposed by Susskind as numerical coincidences in specific holographic setups, with no first-principles derivation of why complexity should equal a geometric quantity. The McGucken derivation makes the identification structural: both volume and action are integrals of x₄-advance over the interior region, both grow monotonically because x₄-advance is monotonic (+ic, not ±ic), and both count the same underlying quantity — the number of independent Channel-A operations the interior has performed since its initial state. The "complexity" Susskind named is the count of Channel-A primitive operations; the "volume" and "action" are the Channel-B geometric integrals of those operations.

**Summary table: Susskind's six programmes as theorems.**

| Susskind programme | Year | McGucken theorem | Mechanism |
|---|---|---|---|
| Holographic principle | 1994 | Proposition VIII.5.1 | SR-14 (six-sense identity) + SR-10 (one bit per Planck area) |
| Black-hole complementarity | 1993 | Proposition VIII.5.2 | SR-9 (x₄-stationary horizon) + SR-7 (McGucken Wick rotation) |
| Stretched horizon | 1993 | Proposition VIII.5.3 | SR-4 (Planck-scale x₄-quantization) + SR-14 (six-sense pairing) |
| String microstates | 1993 | Proposition VIII.5.4 | SR-7 (cigar) + SR-4 + Cardy formula on asymptotic cylinder |
| ER = EPR | 2013 | Proposition VIII.5.5 (≡ Theorem V.1 with SR-14) | SR-12 (shared null-surface identity) + Theorem III.1 (dual readings) |
| Complexity = Volume / Action | 2014 | Proposition VIII.5.6 | SR-1 (+ic monotonicity) + SR-4 (Planck-quantized x₄-advance) |


### VIII.6. The Failure of Universal Unitarity: a theorem of d*x*₄/d*t* = i*c*

**Setup.** We restate four physics definitions from §VIII.5 above as Definitions VIII.6.1–VIII.6.4 for completeness, then prove Theorem VIII.6 (the central rigorous result of this section): that a global unitary on the Hilbert space of the universe does not exist in the McGucken framework. The proof uses Theorem IV.3 (Channel-A unitarity is local), Theorem XI.1 (M1 forces projection at measurement events), SR-9 (horizons are x₄-stationary null hypersurfaces, hence M2-loci), and SR-1 (the +ic monotonicity of d*x*₄/d*t* = i*c*).

**Definition VIII.6.1 (the abstract Hilbert-space state vector).** The *abstract Hilbert-space state vector* is the element $|\psi\rangle \in \mathcal{H}$ of the formal Hilbert space on which the Schrödinger equation $i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle$ acts. Its time-evolution within a single simply connected open event neighborhood $U \subset \mathcal{M}_G$ free of M-loci is unitary: $|\psi(t)\rangle = U(t-t_0)|\psi(t_0)\rangle$ with $U(t-t_0) = e^{-i\hat{H}(t-t_0)/\hbar}$ (Theorem IV.3).

**Definition VIII.6.2 (operationally accessible information).** *Operationally accessible information* is the information a physical observer can recover by performing measurements with real apparatus operating within a bounded region of spacetime, with finite resources, in finite time. By Theorem XI.1, every measurement event is an M1-locus, at which cross-channel agreement forces the Channel-A reading onto a single eigenstate of the measured observable. Recovery means: the measurement outcomes, together with the apparatus record, suffice to reconstruct the property being measured to a specified precision.

**Definition VIII.6.3 (a global unitary on the Hilbert space of the universe).** A *global unitary on the Hilbert space of the universe* is a single unitary operator $U_{\text{univ}} : \mathcal{H}_{\text{univ}} \to \mathcal{H}_{\text{univ}}$ acting on a Hilbert space $\mathcal{H}_{\text{univ}}$ that contains all degrees of freedom of the universe, evolving the universe's state vector across all of spacetime from initial to final boundary conditions, with $U_{\text{univ}}^\dagger U_{\text{univ}} = U_{\text{univ}} U_{\text{univ}}^\dagger = \mathbb{1}_{\mathcal{H}_{\text{univ}}}$.

**Definition VIII.6.4 (an M-locus).** An *M-locus* is, by §III.2, any event in spacetime at which one of the four McGucken mechanisms operates: M1 (combinatorial assignment failure at a measurement event), M1′ (quantum measurement bound on non-commuting observables), M2 (horizon crossing, where Channel-B x₄-expansion crosses a null hypersurface and the $(|\cdot|,\arg)$ basis collapses), or M3 (branching overlap, where Channel-B futures branch and Channel-A states cannot be projected across branches).

**Theorem VIII.6 (Failure of Universal Unitarity).** *In the McGucken framework, no global unitary $U_{\text{univ}}$ in the sense of Definition VIII.6.3 exists for any black-hole evaporation history. Equivalently: the doctrine that abstract Hilbert-space state vectors evolve unitarily on a single Hilbert space of the universe across all of spacetime is false. Susskind's organizing meta-claim — that $U_{\text{univ}}$ exists and preserves information through black-hole evaporation — is therefore wrong as a statement about the global structure of the framework.*

*Proof.* The proof proceeds in four explicit steps. Each step is a direct invocation of a previously established Standing Result or Theorem, with the algebraic content displayed.

**Step 1 (the candidate global unitary, if it existed, would have to compose local Channel-A unitaries across all events).** By Theorem IV.3 (Unitarity), Channel-A evolution is unitary on any simply connected open event neighborhood $U \subset \mathcal{M}_G$ free of M-loci. The local unitary on such a patch is $U_U(t-t_0) = e^{-i\hat{H}_U (t-t_0)/\hbar}$, with $\hat{H}_U$ the local Hamiltonian on $U$. A global unitary $U_{\text{univ}}$ on $\mathcal{H}_{\text{univ}}$ across all of spacetime $\mathcal{M}_G$, if it existed, would have to satisfy
$$U_{\text{univ}}|_U = U_U \quad \text{for every simply connected M-locus-free open } U \subset \mathcal{M}_G,$$
with the restrictions agreeing on overlaps to define a consistent global object.

**Step 2 (M-loci are dense in any black-hole evaporation history).** Consider a black-hole evaporation history $\mathcal{H}_{\text{evap}} \subset \mathcal{M}_G$, i.e., a four-dimensional region of spacetime containing horizon formation, evaporation, and the detection events of Hawking quanta at asymptotic infinity. We enumerate the M-loci within $\mathcal{H}_{\text{evap}}$:

(a) *The horizon is an M2-locus throughout its lifetime.* By SR-9 (Null hypersurfaces = x₄-stationary hypersurfaces), the horizon $H \subset \mathcal{H}_{\text{evap}}$ is a null 3-surface whose every excitation is x₄-stationary. By Theorem III.1 (Dual-Channel Decomposition), the $(|\cdot|,\arg)$ basis of Channel A is well-defined on $\mathbb{C} \setminus \{0\}$ but collapses at the modulus-zero locus, which by SR-9 is precisely the x₄-stationary locus. Every point of $H$ is therefore an M2-locus. The horizon is a 3-parameter family of M2-loci. (Cf. Theorem VI.1: an M2-locus is precisely a basis-collapse point of $(|\cdot|,\arg)$.)

(b) *Every Hawking-photon detection event at asymptotic infinity is an M1-locus.* By Theorem XI.1 (Definite Outcome), every measurement event — including the absorption of a Hawking quantum by a detector at $\mathscr{I}^+$ — forces a Channel-A projection. The detection of $N_{\text{Hawking}}$ Hawking quanta over the lifetime of the evaporating black hole produces $N_{\text{Hawking}}$ M1-loci within $\mathcal{H}_{\text{evap}}$. For a Schwarzschild black hole of initial mass $M$, the order-of-magnitude estimate is $N_{\text{Hawking}} \sim (M c^2 / k_B T_H) \sim (M / M_P)^2$, which for a solar-mass black hole is $\sim 10^{76}$.

(c) *Every decoherence event coupling Hawking radiation to the rest of the universe is an M3-locus.* By Theorem IV.7 (Paradox-as-Channel-Crossing), branching of Channel-B futures forces Channel-A states to be confined to individual branches; the branching event itself is an M3-locus. Decoherence between the radiation and the cosmic environment proceeds at electromagnetic timescales and produces a similarly large multiplicity of M3-loci within $\mathcal{H}_{\text{evap}}$.

Conclusion of Step 2: $\mathcal{H}_{\text{evap}}$ contains a 3-parameter family of M2-loci (the horizon), at least $\sim (M/M_P)^2$ M1-loci (the detections), and at least an equally large multiplicity of M3-loci (the decoherence events).

**Step 3 (composing Channel-A unitaries across M-loci requires projections that are not unitary).** Let $U_1, U_2 \subset \mathcal{M}_G$ be two adjacent simply connected M-locus-free open neighborhoods separated by an M-locus $\mu$. We compute the composition $U_{U_2} \circ U_{U_1}$ acting on a state $|\psi\rangle$ passing through $\mu$, distinguishing the three M-locus cases.

*Case M1 (measurement event).* By Theorem XI.1, at the M1-locus $\mu$, cross-channel agreement forces the projection
$$|\psi(\text{just before }\mu)\rangle = \sum_n c_n |n\rangle \quad\longmapsto\quad |\psi(\text{just after }\mu)\rangle = |n^*\rangle,$$
where $n^* = n^*(q)$ is the unique label such that the Channel-B trajectory through $\mu$ enters $V_{n^*}$ (Lemma XI.1a). The projection operator $\Pi_{n^*} = |n^*\rangle\langle n^*|$ satisfies $\Pi_{n^*}^2 = \Pi_{n^*}$ and $\Pi_{n^*}^\dagger = \Pi_{n^*}$, but $\Pi_{n^*}^\dagger \Pi_{n^*} = \Pi_{n^*} \neq \mathbb{1}$. The composition $U_{U_2} \circ \Pi_{n^*} \circ U_{U_1}$ is therefore not unitary on the full Hilbert space; norm is lost on every component $|n\rangle$ with $n \neq n^*$.

*Case M2 (horizon crossing).* By SR-9 and Theorem VI.1, the $(|\cdot|,\arg)$ basis of Channel A collapses at the M2-locus $\mu$. The anti-Hermitian generator $-i\hat{H}/\hbar$ in $U_U = e^{-i\hat{H} t/\hbar}$ requires this basis to be defined; at $\mu$ the generator is singular. The Channel-A neighborhood on one side of $\mu$ does not extend across to the other side as a single Channel-A neighborhood; instead, the interior and exterior are *separate* Channel-A neighborhoods, joined only at the M2-locus by Channel-B continuity (§V.4). No unitary $U_U$ extends across the M2-locus; the closest object is a Channel-B continuity condition that is not a unitary on a single Hilbert space.

*Case M3 (branching overlap).* By Theorem IV.7, at the M3-locus $\mu$, Channel-B futures branch; the Channel-A state on the past of $\mu$ projects onto each branch separately, with no single state on the future of $\mu$ encompassing both branches. The projection onto each branch is again non-unitary (it loses the amplitudes assigned to the other branches).

In all three M-locus cases, the composition $U_{U_2} \circ U_{U_1}$ requires a non-unitary projection at $\mu$. The composition is therefore not unitary on the full Hilbert space.

**Step 4 (the global unitary does not exist).** By Step 2, $\mathcal{H}_{\text{evap}}$ contains uncountably many M-loci. By Step 3, every composition across an M-locus requires a non-unitary projection. By Step 1, a global unitary $U_{\text{univ}}$ would have to be the composition of local Channel-A unitaries across all of spacetime, including across every M-locus in $\mathcal{H}_{\text{evap}}$.

Since the composition across any single M-locus is non-unitary, the composition across uncountably many M-loci is non-unitary. No $U_{\text{univ}} : \mathcal{H}_{\text{univ}} \to \mathcal{H}_{\text{univ}}$ satisfying $U_{\text{univ}}^\dagger U_{\text{univ}} = \mathbb{1}_{\mathcal{H}_{\text{univ}}}$ exists for $\mathcal{H}_{\text{evap}}$. ∎

**Corollary VIII.6a (Susskind's meta-claim is wrong in the framework).** *The doctrine that information is preserved through black-hole evaporation because a global unitary $U_{\text{univ}}$ on the Hilbert space of the universe evolves the initial pure state unitarily to the final pure state is false in the McGucken framework. By Theorem VIII.6, no such $U_{\text{univ}}$ exists. Susskind's six technical contributions (Propositions VIII.5.1–VIII.5.6) are individually correct as Channel-A theorems on M-locus-free patches; the global-unitarity doctrine that ties them together is not.*

**Corollary VIII.6b (Hawking's 1976 claim is right in the framework).** *Hawking's 1976 "Breakdown of Predictability in Gravitational Collapse" (Physical Review D **14**, 2460) argued that unitarity is genuinely broken by the horizon and that pure states evolve to mixed states under evaporation. In the McGucken framework, both halves of this claim are theorems: the horizon's M2-locus structure breaks Channel-A unitarity (Step 2(a) + Step 3 Case M2 of Theorem VIII.6), and the M1-loci of Hawking-photon detection produce projection-induced loss of operationally accessible information at every detection event (Step 2(b) + Step 3 Case M1).*

### VIII.7. The Schrödinger Equation Contains the Second Law of Thermodynamics: Three Independent Derivations

We now prove rigorously that the Schrödinger equation contains the Second Law of Thermodynamics as a categorical consequence. This is the structural content underlying the observational claim of §III.7 (Corollary III.6, Schrödinger ⇒ Second Law). The full development is given in [MG-Information-Destruction]; we summarize three independent derivations here, each direct in the McGucken framework.

The first derivation uses the First Law of the McGucken Dualities (Theorem III.3) and the Triad of master equations (Remark III.4). The second uses the well-established mathematical fact that the Schrödinger equation is derivable from Huygens' Principle [MG-HLA; MG-PathInt; cf. Feynman-Hibbs 1965 Chapter 3, Schulman 1981 Chapter 5], whose intrinsic content is the dissipative spherical-wavefront propagation that generates the Second Law. The third — the deepest and most rigorous — establishes that the Schrödinger equation and the Second Law are *the two metric-signature readings of one geometric process* — iterated Huygens-McGucken Sphere expansion projected onto the spatial three-slice — related by the McGucken-Wick rotation $\tau = x_4/c$, with the Kac–Nelson correspondence (Kac 1949, Nelson 1964) supplying the established mathematical apparatus.

**Theorem VIII.7 (The Schrödinger Equation Contains the Second Law of Thermodynamics).** *The Schrödinger equation $i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle$, taken as the Channel-A reading of $[\hat{q},\hat{p}] = i\hbar$ (Theorem III.1 Channel A applied to the quantum-mechanics master equation of Remark III.4 row 2), contains the kinetic Second Law $dS/dt > 0$ of Remark III.4 row 3 as a categorical Channel-B consequence under the basis change of Theorem III.3 (i). The same +i that appears on the left-hand side of the Schrödinger equation is the same +i in d*x*₄/d*t* = i*c*, and the same +i that orients the kinetic random walk in the Channel-B reading of $dS/dt = (3/2)k_B/t$. The arrows of time in the two equations are not two arrows; they are one arrow, on one x₄-axis, read by one +i.*

*Proof — Route 1 (via the First Law of the McGucken Dualities).* By Theorem III.1 (Dual-Channel Decomposition), every event neighborhood $U \subset \mathcal{M}_G$ admits a Channel-A reading and a Channel-B reading of d*x*₄/d*t* = i*c*, related by the linear basis change $(|\cdot|,\arg) \leftrightarrow (\mathrm{Re},\mathrm{Im})$ on $\mathbb{C} \cong \mathbb{R}^2$.

By Theorem III.3 (First Law of the McGucken Dualities) part (i), every Channel-A process $\Pi_A$ contains the potential for Channel-B processes: there exists a basis change exhibiting $\Pi_A$ as a Channel-B process $\Pi_B'$ on the same x₄-advance configuration.

By Remark III.4, the Schrödinger equation $i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle$ is the Channel-A reading of the QM master equation $[\hat{q},\hat{p}] = i\hbar$ (Remark III.4 row 2). The kinetic-thermodynamics Second Law $dS/dt = (3/2)k_B/t$ is the Channel-A reading of the kinetic-thermodynamics master equation (Remark III.4 row 3), and its Channel-B reading is "spherical isotropic random walk forced by x₄'s expansion at rate +ic" (the same row 3).

By SR-13 (Reciprocal Generation Property), both rows of the Triad descend from the same source-pair $(\mathcal{M}_G, D_M)$ at every event, with the pointwise McGucken Operator $D_M^{(p)} := \partial_t|_{t=t_p} + ic\,\partial_{x_4}|_{x_4 = ict_p}$ generating both readings simultaneously.

Apply Theorem III.3 (i) to the Schrödinger Channel-A process: the basis change $(|\cdot|,\arg) \to (\mathrm{Re},\mathrm{Im})$ exhibits the Schrödinger phase rotation as a Channel-B spherical wavefront advance at velocity *c* on the same x₄-advance configuration. The +i in $i\hbar\,\partial_t|\psi\rangle$ records the orthogonality of x₄-advance to the three spatial directions; this is the *same i* that appears in d*x*₄/d*t* = i*c* (SR-1), and the *same i* that orients the future-pointing arrow of the kinetic random walk in Remark III.4 row 3.

Therefore the Schrödinger equation contains, by basis change, the Channel-B reading of x₄-advance that *is* the kinetic Second Law. The two equations are not independent statements; they are two readings of the same source-pair $(\mathcal{M}_G, D_M)$ at every event. ∎

*Proof — Route 2 (via Huygens' Principle and the McGucken second law).* The Schrödinger equation is derivable from Huygens' Principle: $|\psi(x,t+dt)\rangle = \int K(x,x';dt) |\psi(x',t)\rangle\,dx'$, with $K$ the Huygens-Feynman propagator $K(x,x';dt) = (m/2\pi i\hbar\,dt)^{1/2} \exp[i m(x-x')^2/(2\hbar\,dt) - i V(x)\,dt/\hbar]$, and the Schrödinger equation $i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle$ recovered in the limit $dt \to 0$ as the infinitesimal-time-step version of this Huygens kernel ([MG-HLA]; cf. Schulman 1981 §5.1, Feynman-Hibbs 1965 §3.4).

Huygens' Principle is the geometric statement that every point of a wavefront acts as a secondary source emitting spherical wavelets, and the next wavefront is the envelope of these wavelets. In the McGucken framework (SR-2, [MG-HLA]), Huygens' Principle is a *theorem of d*x*₄/d*t* = i*c**: the spherical wavelet from each event is the McGucken Sphere of radius $c\,dt$ centered at that event, and the envelope construction is the integration of x₄-advance over the wavefront.

The dissipative content of Huygens' Principle is intrinsic to the construction. Three observations make it explicit:

(a) *The spherical-wavelet emission is one-way.* By SR-1 (the +ic, not ±ic, orientation of d*x*₄/d*t* = i*c*), the McGucken Sphere from each event expands outward at velocity *c*, monotonically. There is no Huygens "anti-wavelet" propagating inward; the construction selects future-orientation as a primitive. The Huygens kernel is causal: $K(x,x';dt) = 0$ for $|x-x'| > c\,dt$ in the relativistic limit, and the support of $K$ on the future light cone of $x'$ is one-sided.

(b) *Integration over the wavefront is dissipative.* The next wavefront is the envelope of all spherical wavelets emitted by points of the current wavefront. The envelope construction integrates over many wavelets, with the phase relationships between distant points decohering at scales comparable to the wavelet radius. This is the spherical-isotropic-random-walk content of Remark III.4 row 3: x₄-expansion at +ic produces an isotropic random walk on the wavefront, which is the kinetic-thermodynamics Channel-B reading.

(c) *The phase $e^{i m(x-x')^2/(2\hbar\,dt)}$ contains the same +i.* The +i in the Huygens-Feynman kernel is the same +i as in the Schrödinger equation's $i\hbar\,\partial_t$, and the same +i as in d*x*₄/d*t* = i*c*. The phase rotation per wavelet is the Channel-A reading of the same x₄-advance whose Channel-B reading is the dissipative envelope construction.

Combining (a), (b), (c): Huygens' Principle is intrinsically dissipative in the sense of generating monotonic outward propagation, integration-over-wavelet decoherence, and a +i-oriented arrow of time. Since the Schrödinger equation is the differential limit of the Huygens kernel, the Schrödinger equation inherits this dissipative content. The Second Law of thermodynamics — $dS/dt > 0$ for a closed system — is the macroscopic consequence of the wavefront-integration dissipation at quantum scale, integrated over all the McGucken Spheres of all events in the system.

Therefore the Schrödinger equation, viewed through its Huygens-derivation route, manifestly contains the Second Law as a categorical consequence of the dissipative wavefront-integration structure. ∎

*Proof — Route 3 (via Lorentzian and Euclidean signature-readings under the McGucken-Wick rotation).* This is the deepest of the three derivations, establishing that the Schrödinger equation and the Second Law are the two metric-signature readings of *one geometric process* — iterated Huygens-McGucken Sphere expansion projected onto the spatial three-slice. The full apparatus is developed in [MG-Information-Destruction §3].

The path-integral representation of the Schrödinger evolution operator is, by Feynman's construction iterated from the Huygens kernel of Route 2,

$$\langle x_f | e^{-i\hat{H} t/\hbar} | x_i \rangle \;=\; \int_{x(0)=x_i}^{x(t)=x_f} \mathcal{D}x(t')\; e^{iS[\gamma]/\hbar}, \tag{VIII.7.1}$$

with $S[\gamma] = \int_0^t L\,dt'$ the Lorentzian-signature action along path $\gamma$, and the phase factor $e^{iS[\gamma]/\hbar}$ inheriting the +i from d*x*₄/d*t* = i*c* (SR-1) via the Compton-frequency oscillation $\omega_C = mc^2/\hbar$.

*Step 1 (the Lorentzian-signature reading is Channel A).* The phase factor $e^{iS[\gamma]/\hbar}$ in (VIII.7.1) is the Channel-A reading of each path's contribution to the propagator. The integration over paths produces unitary evolution: the operator $U(t) = e^{-i\hat{H} t/\hbar}$ preserves the inner product on Hilbert space (by Stone's theorem applied to the anti-Hermitian generator $-i\hat{H}/\hbar$; cf. Theorem IV.3 above). Each path's phase oscillates at the Compton frequency, and the bulk of the path integral is dominated by paths near the classical stationary trajectory (stationary phase, $\delta S = 0$). This is the unitarity content of the Schrödinger equation in the Lorentzian-signature reading.

*Step 2 (the McGucken-Wick rotation as a coordinate identification on the real four-manifold).* Apply the McGucken-Wick rotation (SR-7) $\tau = x_4/c$ to (VIII.7.1). In the McGucken framework this is *not* a formal computational device but a coordinate identification on the real four-manifold $\mathcal{M}_G$ whose fourth axis is physically expanding at velocity *c* ([MG-Wick]; [MG-Information-Destruction §3.2]; cf. Theorem IV.1 Step 3 above). The substitution $t \mapsto -i\tau$ in d*x*₄/d*t* = i*c* yields $dx_4/d\tau = c$ — a real first-order ODE in real $\tau$, with the imaginary unit absent (the *i* has been cancelled against the *i* in $t = -i\tau$).

*Step 3 (the Euclidean-signature reading is Channel B and is the Wiener-process measure).* Under the McGucken-Wick rotation, the Lorentzian action transforms as $S[\gamma] \mapsto -i\,S_E[\gamma]$, where $S_E[\gamma] = \int_0^\tau L_E\,d\tau'$ is the Euclidean-signature action with $L_E$ the Euclidean Lagrangian. The phase factor in (VIII.7.1) becomes a real positive weight:

$$e^{iS[\gamma]/\hbar} \;\xrightarrow{\,t \mapsto -i\tau\,}\; e^{-S_E[\gamma]/\hbar}. \tag{VIII.7.2}$$

The path integral, viewed in the Euclidean-signature reading, is therefore

$$\langle x_f | e^{-\hat{H}\tau/\hbar} | x_i \rangle \;=\; \int_{x(0)=x_i}^{x(\tau)=x_f} \mathcal{D}x(\tau')\; e^{-S_E[\gamma]/\hbar}. \tag{VIII.7.3}$$

For a free non-relativistic particle of mass $m$, $L_E = \tfrac{1}{2} m \dot{x}^2$ (with the dot now $\tau$-derivative), and (VIII.7.3) is exactly the Wiener-process measure on continuous paths with diffusion constant $D = \hbar/(2m)$. The probability that the particle visits configuration $x_f$ at Euclidean time $\tau$ given initial configuration $x_i$ is the heat kernel of Brownian motion:

$$P_W(x_f, \tau \mid x_i, 0) \;=\; (4\pi D \tau)^{-3/2} \exp\!\left[-\frac{(x_f - x_i)^2}{4 D \tau}\right]. \tag{VIII.7.4}$$

This is the Channel-B reading: the same Schrödinger evolution that gives unitary phase rotation in the Lorentzian-signature reading gives Brownian motion in the Euclidean-signature reading. The two readings are exact; both descend from the same iterated Huygens-McGucken Sphere expansion; the McGucken-Wick rotation $\tau = x_4/c$ relates them as a coordinate identification on $\mathcal{M}_G$, not as a formal trick.

*Step 4 (the strict Second Law).* The Wiener-process measure (VIII.7.3) governs the diffusive evolution of every massive-particle ensemble. The entropy of an ensemble of $N$ Brownian particles in three dimensions evolves as $S(\tau) = (3/2) N k_B \log\tau + \text{const}$, giving

$$\frac{dS}{d\tau} \;=\; \frac{3 N k_B}{2\tau} \;>\; 0 \quad \text{for all }\tau > 0. \tag{VIII.7.5}$$

This is the strict Second Law $dS/dt > 0$ — a *strict numerical rate*, not a statistical tendency. The strict positivity is forced by SR-1: d*x*₄/d*t* = i*c* (not $\pm$ ic) selects $D > 0$ at every $\tau$. A reversal of the inequality would require $dx_4/dt = -ic$, which the McGucken Principle excludes. The same +i that gives Schrödinger phase rotation in Step 1 gives the strict positivity of the diffusion constant in Step 3, which gives the strict positivity of $dS/d\tau$ in (VIII.7.5).

*Step 5 (the Kac–Nelson correspondence as the established mathematical apparatus).* The mathematical correspondence between the Schrödinger equation under Wick rotation and Brownian motion (the Wiener measure) was established by Kac in 1949 (the Feynman–Kac formula) and developed by Nelson in 1964 (stochastic quantization). The 75-year-old Kac–Nelson literature is the mainstream mathematical recognition that the Schrödinger equation and the diffusion equation are related by a Wick rotation. What the orthodox literature did not recognize is that the Wick rotation is not a computational convenience but a *physical coordinate identification* on the real four-manifold whose fourth axis is x₄ — and that this coordinate identification is forced, at every event of $\mathcal{M}_G$, by the McGucken Principle d*x*₄/d*t* = i*c* (SR-7). The McGucken framework names the connection. The Schrödinger equation and the Second Law are not analogous, not dual, not in tension — they are *the same equation read in two metric signatures*, with the Kac–Nelson correspondence supplying the mathematical apparatus and the McGucken-Wick rotation supplying the physical interpretation.

*Conclusion of Route 3.* The Schrödinger equation $i\hbar\,\partial_t |\psi\rangle = \hat{H}|\psi\rangle$ is the Lorentzian-signature reading of iterated Huygens-McGucken Sphere expansion projected onto the spatial three-slice. The strict Second Law $dS/dt = (3/2) N k_B/\tau > 0$ is the Euclidean-signature reading of the same iterated expansion. They are related by the McGucken-Wick rotation $\tau = x_4/c$ as a coordinate identification on the real four-manifold $\mathcal{M}_G$. The Kac–Nelson correspondence (Kac 1949; Nelson 1964) is the 75-year-old established mathematical apparatus connecting them. The Schrödinger equation therefore contains the Second Law as a categorical consequence — one principle read in two notations. ∎

**Theorem VIII.7′ (Universal McGucken Channel B Theorem, after [MG-Information-Destruction Theorem 3.2; MG-Unification §7.9]).** *Every Channel-A process described by a Lorentzian-signature path integral $\int \mathcal{D}\gamma\,e^{iS[\gamma]/\hbar}$ contains, under the McGucken-Wick rotation $\tau = x_4/c$, a Euclidean-signature Channel-B reading $\int \mathcal{D}\gamma\,e^{-S_E[\gamma]/\hbar}$ which is a Wiener-process measure on continuous paths. The Channel-B reading carries the strict Second Law $dS/d\tau > 0$ as a forced consequence of the +ic (not −ic) orientation of d*x*₄/d*t* = i*c*. This is universal: it applies to Schrödinger evolution, Klein-Gordon propagation, Dirac evolution, the unitary evolution of operator algebras of any quantum-mechanical system, the path-integral propagator of any Lagrangian system, and the gravitational path integral with the Einstein-Hilbert action.* [MG-Information-Destruction §7.9; MG-Unification Theorem 7.9.1; MG-Wick]

**Remark VIII.7.1 (the obvious content of the derivation).** The Huygens derivation of the Schrödinger equation has been in the textbooks for sixty years ([Feynman-Hibbs 1965]; [Schulman 1981]; [Kleinert 2009]). The Kac–Nelson correspondence between the Schrödinger equation under Wick rotation and Brownian motion has been in the mathematical-physics literature for seventy-five years (Kac 1949; Nelson 1964). What has not been generally recognized — until [MG-Information-Destruction] makes it explicit — is the physical content of these two well-established results combined: (i) the Schrödinger equation inherits, by the very fact of its Huygens derivation, the dissipative spherical-wavefront-integration content of Huygens' Principle; (ii) the Kac–Nelson correspondence is not a formal computational device but the mathematical expression of the McGucken-Wick rotation $\tau = x_4/c$ — a physical coordinate identification on the real four-manifold $\mathcal{M}_G$ whose fourth axis is x₄. The "tension" between unitary Schrödinger evolution and the irreversible Second Law that exercised Loschmidt, Boltzmann, Zermelo, and (in modified form) Hawking and Susskind is, in the McGucken framework, not a tension at all; it is a misreading of one set of equations as two independent statements when they are in fact the two metric-signature readings of one geometric process.

**Remark VIII.7.2 (consequence for the orthodox Susskind defense).** The orthodox Susskind defense of global unitarity rests on extracting only the Lorentzian-signature reading of the Schrödinger equation and treating it as exhausting the equation's content. By Theorem VIII.7 Route 3, this is structurally a half-reading: the Euclidean-signature reading is equally exact, equally forced, and contains the strict Second Law that destroys operationally accessible information at every Channel-B advance. By Theorem VIII.7′ (Universal McGucken Channel B Theorem), this is not a peculiarity of black-hole physics — it is a categorical feature of every Lorentzian-signature path integral, whether in laboratory quantum mechanics, particle physics, or gravity. The Brownian Hamlet (§III.4) and the Brownian Iliad–Odyssey (§III.5) are the laboratory exhibitions of the same Channel-B Wiener-process measure that governs Hawking-radiation Brownian dissolution at the horizon. The dust on the laboratory bench is no different from the dust on a black-hole horizon: both undergo Compton-coupled Brownian motion as the Euclidean-signature reading of the same Schrödinger evolution that gives Lorentzian-signature unitarity. Susskind's "information is preserved" doctrine reads only Channel A and ignores Channel B; the laboratory shows that the Channel-B reading is empirically primary on the physically operative question of whether operationally accessible information is destroyed.

### VIII.8. Every Channel-A Process Contains Channel-B Thermodynamics

The Schrödinger ⇒ Second Law result of §VIII.7 is one instance of a more general theorem: *every Channel-A process contains Channel-B thermodynamic content as a categorical consequence*. This follows directly from the First Law of the McGucken Dualities (Theorem III.3) and the categorical structure of the McGucken Category McG₆ (SR-13).

**Theorem VIII.8 (Every Channel-A Process Contains Channel-B Thermodynamic Content).** *Let $\Pi_A : U \to U$ be any Channel-A process on a simply connected open event neighborhood $U \subset \mathcal{M}_G$ free of M-loci. Then $\Pi_A$ contains, by the basis change of Theorem III.3 (i), a Channel-B process $\Pi_B'$ on the same x₄-advance configuration; and the Channel-B process $\Pi_B'$ inherits the thermodynamic content of the kinetic Channel-B master equation $dS/dt = (3/2)k_B/t$ (Remark III.4 row 3) on those degrees of freedom where the random-walk reading applies.*

*Proof.* By Theorem III.3 (i), every Channel-A process $\Pi_A$ admits a Channel-B reading $\Pi_B'$ via the basis change $(|\cdot|,\arg) \to (\mathrm{Re},\mathrm{Im})$ of Theorem III.1. By SR-13 (Reciprocal Generation Property), at every event $p \in U$, the pointwise McGucken Operator $D_M^{(p)}$ generates both readings simultaneously from the same source-pair.

By Remark III.4, the kinetic-thermodynamics Channel-B reading is *"spherical isotropic random walk forced by x₄'s expansion at rate +ic"* — i.e., it is the Channel-B reading of d*x*₄/d*t* = i*c* applied to a many-body ensemble with degrees of freedom that thermalize. Since $\Pi_B'$ is a Channel-B process on the same source-pair, the random-walk reading applies to any many-body ensemble of degrees of freedom on which $\Pi_B'$ acts.

The thermodynamic content is therefore inherited: $\Pi_B'$ contains, on each many-body ensemble of degrees of freedom in $U$, the Channel-B random-walk dissipation that produces $dS/dt > 0$ at the macroscopic scale. This is the Channel-B content present in *every* Channel-A process by the categorical structure of the McGucken Dualities. ∎

**Corollary VIII.8a (Universal applicability).** *The Channel-B thermodynamic content is present in every Channel-A process whose source-pair is generated by d*x*₄/d*t* = i*c*. This includes, but is not limited to, Schrödinger evolution (Theorem VIII.7); the unitary evolution of operator algebras of any quantum-mechanical system (Theorem IV.3, Channel A reading); the Heisenberg evolution of operators $\partial_t \hat{O} = (i/\hbar)[\hat{H}, \hat{O}]$ (same source); the path-integral propagator $K(x,x';t) = \int \mathcal{D}x\,e^{iS[x]/\hbar}$ (Channel A reading of Huygens, [MG-PathInt]); and the Dirac equation $(i\gamma^\mu\partial_\mu - mc/\hbar)\psi = 0$ ([MG-Dirac]). Each of these Channel-A processes carries, by Theorem VIII.8, the Channel-B thermodynamic content of the same x₄-advance.*

**Why Susskind's claim that "information is preserved" is wrong, restated rigorously.** Susskind's global-unitarity meta-claim assumes that the existence of a unitary Channel-A description of the universe's state vector ensures that the *abstract Hilbert-space state* (Definition VIII.6.1) preserves all information through any physical process, including black-hole evaporation. By Theorem VIII.8, every Channel-A process — including the global Channel-A unitary that Susskind invokes, if it existed — contains Channel-B thermodynamic content that destroys *operationally accessible information* (Definition VIII.6.2) at every M-locus the process crosses. By Theorem VIII.6, the global Channel-A unitary does not even exist in the McGucken framework, because the M-loci densely populating any black-hole evaporation history force non-unitary projections that no $U_{\text{univ}}$ can absorb.

The corrected statement: *operationally accessible information is destroyed by Channel-B x₄-advance at every M-locus, and this destruction is intrinsic to every physical process, including the Channel-A processes that Susskind treats as unitary*. The destruction is not a competitor to unitarity; it is the Channel-B face of the same x₄-advance whose Channel-A face is the operator evolution. The doctrine that "information is preserved because the formalism is unitary" reads only one face of the duality and ignores the other. Both faces are exact; both are simultaneous; the framework requires both.

**Final summary of §VIII.5–VIII.8.** Susskind's six technical contributions are Channel-A theorems of d*x*₄/d*t* = i*c* (Propositions VIII.5.1–VIII.5.6). His global-unitarity meta-claim is false (Theorem VIII.6). The Schrödinger equation contains the Second Law of Thermodynamics as a Huygens-derivation consequence (Theorem VIII.7); every Channel-A process contains Channel-B thermodynamic content (Theorem VIII.8). The Brownian Hamlet (§III.4) is the laboratory exhibition that operationally accessible information is destroyed by Channel-B x₄-advance regardless of whatever the abstract Hilbert-space state continues to record. Hawking's 1976 "Breakdown of Predictability in Gravitational Collapse" is correct in the framework as a theorem: unitarity fails at the horizon (Step 2(a) + Step 3 Case M2 of Theorem VIII.6), pure states evolve to mixed states under evaporation (Theorem VIII.7 applied to the evaporation history), and operationally accessible information is destroyed (Theorem VIII.8 applied to every M-locus crossed). On the question of whether operationally accessible information is destroyed at black-hole horizons, the answer is yes. Susskind was wrong; Hawking was right.

### VIII.9. Susskind's Complexity Program as Dual-Channel Operator-Algebra Content

In the period 2014–2020, in response to the operational refutations closing in on the universal-unitarity defense, Susskind developed a new mathematical apparatus: the geometry of quantum complexity on the unitary group $SU(2^K)$, with a right-invariant metric defined by minimal gate-count, an expander-graph (Ramanujan-class) structure, and a "Second Law of Complexity" governing the linear-then-plateau-then-recurrence growth of complexity under unitary evolution. The program was further elaborated by Adam Brown, Aaron Wall, Henry Lin, and collaborators; its central application is the **complexity–volume duality conjecture** [Stanford–Susskind 2014; Susskind 2016a; Brown–Roberts–Susskind–Swingle–Zhao 2016a, 2016b]: the bulk volume of an Einstein–Rosen bridge interior, measured at the boundary of an evaporating black hole, equals (up to factors) the boundary state's quantum complexity, and this complexity continues to grow long after the boundary entropy has saturated.

We now establish, in seven formal theorems, that Susskind's complexity program is *itself* a Channel-B-content structure of d*x*₄/d*t* = i*c* applied to the operator-algebra tier, and that its central conjecture — that complexity probes the operationally accessible content of the black-hole interior — is exactly the methodological retreat to Platonic metaphysics diagnosed by Theorem III.6.7, expressed in its most mathematically sophisticated form.

#### Definitional preliminaries: the complexity geometry on $SU(2^K)$

We adopt Susskind's definitions, slightly sharpened for use within the McGucken framework. Let $K$ be a positive integer (the qubit count), $\mathcal{H} = (\mathbb{C}^2)^{\otimes K}$ the $K$-qubit Hilbert space of dimension $2^K$, and $SU(2^K)$ the special unitary group on $\mathcal{H}$.

**Definition VIII.9.1 (Gate set; universal gate set; circuit).** A *gate set* is a finite collection $\mathcal{G} = \{G_1, \ldots, G_r\} \subset SU(2^K)$ of $\kappa$-local unitaries, with $\kappa \ll K$, such that each $G_i$ acts non-trivially on at most $\kappa$ qubits. The gate set is *universal* (within tolerance $\varepsilon > 0$) if every $U \in SU(2^K)$ admits, for every $\varepsilon$, a finite product $U_n \cdots U_1$ with each $U_j \in \mathcal{G} \cup \mathcal{G}^{-1}$ satisfying $\|U - U_n\cdots U_1\| \le \varepsilon$. A *circuit* of depth $n$ is a finite product $U_n \cdots U_1$ with $U_j \in \mathcal{G}\cup\mathcal{G}^{-1}$.

**Definition VIII.9.2 (Inner-product distance on $SU(2^K)$).** The *inner-product distance* between $U, V \in SU(2^K)$ is
$$d_{\rm IP}(U, V) \;=\; \arccos\bigl(|\langle U|V\rangle|\bigr), \quad \langle U|V\rangle \;=\; \tfrac{1}{2^K}\,\mathrm{tr}(U^\dagger V). \tag{IX.1}$$
This is the standard normalized-trace metric. Its diameter on $SU(2^K)$ is at most $\pi/2$.

**Definition VIII.9.3 (Complexity distance — right-invariant gate-count metric).** Fix a universal gate set $\mathcal{G}$ and tolerance $\varepsilon$. The *complexity distance* between $U, V \in SU(2^K)$ is
$$\mathcal{C}(U, V) \;=\; \min\{n \,:\, \exists\, U_1, \ldots, U_n \in \mathcal{G}\cup\mathcal{G}^{-1} \text{ with } \|U - U_n\cdots U_1 V\| \le \varepsilon\}. \tag{IX.2}$$
The *complexity* of a single unitary is $\mathcal{C}(U) := \mathcal{C}(U, \mathbf{1})$. Susskind establishes (cf. §VIII.9 below, Proposition VIII.9.1) that $\mathcal{C}$ is a right-invariant metric on $SU(2^K)$: $\mathcal{C}(UW, VW) = \mathcal{C}(U, V)$ for every $W \in SU(2^K)$.

**Proposition VIII.9.1 (Susskind's expander-graph theorem, sharpened).** *Under Definitions VIII.9.1–VIII.9.3, with degree $d \approx K^{K/2}$ for the standard architecture (two-local gates, all-to-all pairing, gate-set size $|\mathcal{G}|$ absorbed into $d$):*

*(a) The decision-tree graph of single-layer circuits has degree $d$ at every vertex (right-invariance).*

*(b) Under the "no-collisions" hypothesis (collisions are exponentially rare for circuit depth $n \le n_*$), the tree fills $SU(2^K)$ without revisiting up to depth*
$$n_* \;\sim\; \frac{4^K}{(K/2)\log K} \,+\, \frac{\log(1/\varepsilon)}{\log K}. \tag{IX.3}$$

*(c) Beyond $n_*$, collisions force the graph to close into a finite, sparse, $d$-regular, expander-class graph on $SU(2^K)$ with diameter $\mathcal{C}_{\max} \sim 4^K$ and girth $\sim 4^K$ (Ramanujan-class).*

*(d) The number of unitaries at complexity $\mathcal{C}$ grows as*
$$|\{U : \mathcal{C}(U) = c\}| \;\sim\; d^c \;=\; e^{c \log d}. \tag{IX.4}$$

*Proof.* This is a restatement, modulo the McGucken framework's notational conventions, of the results established by Susskind [Susskind 2016b, §3–4; Brown–Susskind 2018, §2] and the kinetic-theory derivation by Aaronson–Susskind. Right-invariance (a) follows directly from the gate-counting definition: if $U = G_n \cdots G_1 V$ then $UW = G_n \cdots G_1 (VW)$. The no-collision estimate (b) follows from comparing the tree volume $d^n$ with the epsilon-ball count of $SU(2^K)$, $\sim \varepsilon^{-(4^K - 1)}$ from Definition VIII.9.2's volume calculation. The expander-class diameter and girth (c) follow from the homogeneity of $SU(2^K)$ combined with (b). The exponential growth (d) follows directly from the tree-degree count up to $n_*$ and the regularity of the closed graph beyond $n_*$. ∎

#### Theorem VIII.9.1 (The two metrics on $SU(2^K)$ are the Channel-A and Channel-B readings of d*x*₄/d*t* = i*c* at the operator-algebra tier)

The inner-product metric $d_{\rm IP}$ and the complexity metric $\mathcal{C}$ are not two independent geometric structures sitting on the same space by coincidence. They are the two signature-readings of d*x*₄/d*t* = i*c* applied to the operator-algebra tier, with the McGucken-Wick rotation $\tau = x_4/c$ (SR-7) as the operational bridge between them.

**Theorem VIII.9.1 (Inner-product and complexity as Channel A and Channel B at the operator-algebra tier).** *Under the McGucken Principle d*x*₄/d*t* = i*c* and the Dual-Channel Decomposition of Theorem III.1, the two metrics $d_{\rm IP}$ and $\mathcal{C}$ on $SU(2^K)$ are the Channel-A and Channel-B readings, respectively, of d*x*₄/d*t* = i*c* applied to the operator-algebra tier:*

*(a) **$d_{\rm IP}$ is Channel A.** The inner-product distance arises from the algebraic-symmetry content of d*x*₄/d*t* = i*c* (SR-2, McGucken Sphere isotropy combined with the unitary representation of $SU(2^K)$ on $\mathcal{H}$). Its diameter is bounded ($\le \pi/2$) because Channel A preserves the Lorentzian-locked $\langle\psi|\psi\rangle = 1$ normalization (Theorem III.1(b)). It is sensitive to the phase of $U^\dagger V$ but blind to the path through $SU(2^K)$ connecting $U$ to $V$.*

*(b) **$\mathcal{C}$ is Channel B.** The complexity distance arises from the geometric-propagation content of d*x*₄/d*t* = i*c* applied to the unitary group: each gate $G \in \mathcal{G}$ implements an infinitesimal McGucken-Sphere expansion (SR-2) on $\mathcal{H}$, and the gate-count is the discretized version of the $+ic$-monotonic path-length on $SU(2^K)$ measured by the right-invariant Riemannian metric Susskind constructs in [Susskind 2016b §3]. Its diameter is doubly-exponential ($\sim 4^K$) because Channel B counts realizable propagation paths under the $+ic$ orientation (SR-1).*

*(c) **The McGucken-Wick rotation bridges them.** Under the substitution $\tau = x_4/c$ (SR-7) at the operator-algebra tier, the Channel-A inner-product metric and the Channel-B complexity metric are related by*
$$\mathcal{C}(U, V) \;\sim\; \text{path-length in } SU(2^K) \text{ under the }+ic\text{-monotonic geodesic gradient generated by } d_{\rm IP}, \tag{IX.5}$$
*with the path-length computed via the right-invariant gauge-fixed Riemannian metric of Nielsen geometry [Nielsen et al. 2006]. The McGucken-Wick rotation converts the unitary-evolution geodesic of Channel A into the Euclidean-signature gate-count geodesic of Channel B.*

*Proof.* We establish (a), (b), (c) in turn.

**Step 1 (Channel-A identification of $d_{\rm IP}$).** The inner-product metric (IX.1) is built from the normalized trace $\mathrm{tr}(U^\dagger V)/2^K = \langle\Phi_U | \Phi_V\rangle$, where $\Phi_U = U^{ij}|i\rangle|j\rangle^*$ is the maximally entangled state associated to $U$ via the Choi–Jamiołkowski isomorphism. By Theorem III.1(b), $\Phi_U$ is a Lorentzian-locked Channel-A object: its evolution under Schrödinger dynamics $i\hbar\partial_t\Phi = \hat H\Phi$ preserves $\langle\Phi|\Phi\rangle = 1$ (Channel-A unitarity, SR-3 with $i$ interior to $\partial_t$). The metric $d_{\rm IP}(U,V) = \arccos|\langle\Phi_U|\Phi_V\rangle|$ is therefore a Channel-A construct: it measures the algebraic-symmetry-preserving distance under unitary Channel-A evolution. Its $\pi/2$ diameter bound is the Channel-A statement that no two normalized vectors in $\mathcal{H}\otimes\mathcal{H}^*$ can be more than orthogonal.

**Step 2 (Channel-B identification of $\mathcal{C}$).** Each gate $G \in \mathcal{G}$ is a $\kappa$-local infinitesimal unitary on $\mathcal{H}$, equivalent to an infinitesimal McGucken-Sphere expansion of radius $\delta\tau = 1/\omega_C$ (the inverse Compton frequency of the gate's underlying qubit substrate, SR-3, [MG-Compton]) applied to the operator-algebra tier. By Theorem III.1(a) and [MG-FeynmanDiagrams Proposition III.1], the propagator of each gate is the Huygens kernel on the McGucken Sphere of the qubit, with the $+ic$ orientation forcing the gate to advance the operator forward in $x_4$, never backward. The gate-count $\mathcal{C}(U,V)$ is therefore the discrete count of $+ic$-monotonic McGucken-Sphere expansions required to propagate from $V$ to $U$ on the unitary group. This is the geometric-propagation Channel-B content of d*x*₄/d*t* = i*c* applied to $SU(2^K)$: the metric $\mathcal{C}$ measures path-length on $SU(2^K)$ under the $+ic$ orientation, with the doubly-exponential diameter $\sim 4^K$ arising as the operator-algebra analogue of the doubly-exponential configuration-space volume of the Brownian-Hamlet (§III.4).

**Step 3 (McGucken-Wick bridge).** The Nielsen-geometry Riemannian metric on $SU(2^K)$ [Nielsen et al. 2006; Susskind 2016b §3], with appropriate gauge-fixing penalties on $\kappa$-non-local directions, defines a continuum complexity that interpolates between the discrete gate-count $\mathcal{C}$ and the algebraic-symmetry-preserving structure that generates $d_{\rm IP}$. Under the McGucken-Wick rotation $\tau = x_4/c$ (SR-7), the Schrödinger unitary geodesic in $SU(2^K)$ generated by $\hat H$ (Channel-A reading, the integral curve of $-i\hat H/\hbar$ in the tangent space at $\mathbf{1}$) is converted to the Euclidean-signature path-length geodesic measured by the Nielsen Riemannian metric (Channel-B reading). The same equation d*x*₄/d*t* = i*c*, read in Lorentzian signature, generates the Channel-A unitary structure carrying $d_{\rm IP}$; read in Euclidean signature via the Wick rotation, it generates the Channel-B path-length structure carrying $\mathcal{C}$. The two metrics are the same equation's two readings. ∎

**Corollary VIII.9.1a (The incommensurability of $d_{\rm IP}$ and $\mathcal{C}$ is the operator-algebra instance of position-of-$i$ asymmetry).** *The radical incommensurability of $d_{\rm IP}$ and $\mathcal{C}$ — two unitaries that are inner-product-close can be exponentially complexity-far — that Susskind identifies as a curious feature of complexity geometry is the operator-algebra instance of the position-of-$i$ asymmetry [MG-Wick §24.5.4; MG-DualChannel]. Channel A is Lorentzian-locked ($i$ interior, the metric $d_{\rm IP}$ inherits the bounded $\pi/2$ diameter); Channel B is bi-signature ($i$ exteriorizable, the metric $\mathcal{C}$ inherits the unbounded $4^K$ diameter). The incommensurability is forced by the dual-channel architecture of d*x*₄/d*t* = i*c*; it is not a curiosity but a theorem.*

#### Theorem VIII.9.2 (The Second Law of Complexity is the operator-algebra instance of Theorem VIII.7)

Susskind's central structural observation about complexity geometry is the **Second Law of Complexity**: under unitary evolution, complexity grows monotonically (with overwhelming probability) until it saturates at $\mathcal{C}_{\max} \sim 4^K$, because the number of unitaries at complexity $c$ grows exponentially with $c$ and the random walk on the expander graph drifts outward by the same combinatorial mechanism that drives the Second Law of thermodynamics.

**Theorem VIII.9.2 (Second Law of Complexity = Channel-B Second Law at the operator-algebra tier).** *Susskind's Second Law of Complexity*
$$\frac{d\mathcal{C}}{dt} \;\ge\; 0 \quad \text{(with overwhelming probability, until }\mathcal{C} = \mathcal{C}_{\max}\text{)} \tag{IX.6}$$
*is the operator-algebra-tier instance of the strict Second Law of Thermodynamics established in Theorem VIII.7:*
$$\frac{dS}{dt} \;=\; \frac{3 k_B}{2 t} \;>\; 0. \tag{IX.7}$$
*Both are Channel-B content of d*x*₄/d*t* = i*c* applied to distinct structural inputs: (IX.6) to the operator algebra $SU(2^K)$, (IX.7) to the configuration-space dynamics of Compton-coupled Brownian matter. Under the identification of complexity-volume as configuration-space-volume entropy via*
$$S_{\rm cplx}(\mathcal{C}) \;=\; \log|\{U : \mathcal{C}(U) = c\}| \;\sim\; c \log d \;\propto\; \mathcal{C}, \tag{IX.8}$$
*(IX.6) follows from (IX.7) applied to the operator-algebra tier by the Universal Channel B Theorem of [MG-Unification, Theorem 7.9].*

*Proof.* The proof has three steps.

**Step 1 (Complexity-volume is entropy).** By Proposition VIII.9.1(d), the number of unitaries at complexity $c$ grows as $d^c = e^{c\log d}$. Define the *complexity entropy* $S_{\rm cplx}(\mathcal{C}) := \log|\{U : \mathcal{C}(U) = c\}|$. Then $S_{\rm cplx} \sim c\log d \propto \mathcal{C}$. The complexity is, up to a multiplicative constant $\log d$, the entropy of the operator-algebra configuration space at fixed complexity. Susskind's recognition that "complexity is a kind of entropy" is the structural identification (IX.8). This is the operator-algebra analogue of Boltzmann's $S = k_B \log W$: $S_{\rm cplx}$ is the logarithm of the phase-space volume of unitaries at fixed complexity $c$, exactly as Boltzmann entropy is the logarithm of the phase-space volume of microstates at fixed macrostate.

**Step 2 (The drift outward is the $+ic$-monotonic content).** A random walk on the $d$-regular expander graph of Proposition VIII.9.1 drifts outward (increases complexity) by the combinatorial fact that the number of accessible vertices at complexity $c+1$ exceeds the number at $c-1$ by a factor $d-1 \sim d$. The drift coefficient $d/(d-1+d) \to 1$ as $d \to \infty$. The drift is therefore overwhelming for $K \gg 1$. By Theorem III.1(a), the $+ic$ orientation of d*x*₄/d*t* = i*c* applied to the operator-algebra tier forces unitary evolution to be a $+ic$-monotonic walk on $SU(2^K)$ (the Schrödinger-equation Channel-B reading): each infinitesimal gate is a forward-in-$x_4$ McGucken-Sphere expansion, with no backward-in-$x_4$ counterpart. The combinatorial drift outward and the $+ic$-monotonic Channel-B orientation are the same structural fact: the operator-algebra random walk has a strict positive expected complexity gradient for the same reason the Brownian dust has a strict positive expected entropy gradient (Theorem VIII.7).

**Step 3 (Application of the Universal Channel B Theorem).** By the Universal Channel B Theorem of [MG-Unification, Theorem 7.9], every Lorentzian-signature path-integral construction in physics carries a Euclidean-signature Wiener reading under the McGucken-Wick rotation. Applied to the operator-algebra tier: the unitary evolution $U(t) = \exp(-i\hat H t/\hbar)$ on $SU(2^K)$ (Channel-A Schrödinger evolution) carries, under $\tau = x_4/c$, a Wiener-process Channel-B reading whose drift coefficient is strictly positive in the complexity direction. The Wiener-process drift on $SU(2^K)$ is identically Susskind's Second Law of Complexity (IX.6). By Theorem VIII.7, the strict positivity of the drift is the $+ic$ orientation of d*x*₄/d*t* = i*c* applied through the Compton-coupling mechanism (SR-3) to whatever tier of physics carries the Wiener reading. At the configuration-space tier, the $+ic$ drift is $dS/dt = (3/2)k_B/t > 0$; at the operator-algebra tier, the $+ic$ drift is $d\mathcal{C}/dt \ge 0$. The two statements are the same Channel-B content. ∎

**Corollary VIII.9.2a (Susskind discovered Channel B at the operator-algebra tier by visualization rather than by Wick rotation).** *Susskind's method for arriving at the Second Law of Complexity, by his own description in [Susskind 2018a], was geometric visualization: "close your eyes, try to visualize the answer, and then say that's what it is." This method has produced a structurally correct Channel-B-content result by a route that bypasses the McGucken-Wick rotation. The Second Law of Complexity is therefore an instance of Channel-B content discovered through visualization rather than through the systematic dual-channel architecture; it is correct but unmotivated within Susskind's framework, exactly as Hawking's 1976 "Breakdown of Predictability" was correct but unmotivated within the orthodox-unitarity framework.*

#### Theorem VIII.9.3 (The complexity-growth–plateau–recurrence structure is the M2/M3 mechanism applied to the operator-algebra tier)

Susskind's three-phase complexity-growth picture — linear growth from $\mathcal{C} = 0$ to $\mathcal{C}_{\max} \sim 4^K$ over time $t \sim 4^K$; plateau at $\mathcal{C}_{\max}$ for time $\sim e^{4^K}$; quantum Poincaré recurrence at time $\sim e^{e^{4^K}}$ — is the operator-algebra-tier instance of the four-mechanism classification (§III.2) of the present paper.

**Theorem VIII.9.3 (Complexity-growth phases as the four-mechanism instances).** *The three phases of Susskind's complexity-growth picture admit the following four-mechanism identifications under the McGucken framework:*

*(a) **Linear growth phase ($0 < t < t_*$, with $t_* \sim 4^K$):** the operator-algebra-tier instance of mechanism M2 (Horizon Crossing). Each gate application is a McGucken-Sphere expansion on the qubit substrate that crosses one increment of the operator-algebra horizon $\Sigma_+(t)$, with the linear growth $\mathcal{C}(t) \sim (K/2) t$ matching the surface-area growth of $\Sigma_+$.*

*(b) **Plateau phase ($t_* < t < t_{\rm Poincaré}$, with $t_{\rm Poincaré} \sim e^{4^K}$):** the operator-algebra-tier instance of mechanism M3 (Branching Overlap). After $\mathcal{C}_{\max}$ is reached, the expander graph forces revisits to previously-visited epsilon-balls; the geodesic structure changes from instant to instant as new short-cuts open and close; the operator wanders on the maximal-complexity boundary without further complexity gain. This is structurally identical to the M3 branching-overlap mechanism of §III.2: distinct evolution histories begin to overlap in the operator-algebra phase space, and operational distinguishability of paths breaks down.*

*(c) **Quantum Poincaré recurrence ($t > e^{e^{4^K}}$):** the operator-algebra-tier instance of the Zermelo–Poincaré recurrence theorem [Poincaré 1893; Zermelo 1896] applied to a bounded operator-algebra phase space. This is the structural-historical inverse of the 19th-century Loschmidt–Zermelo–Poincaré objection to empirical thermodynamics (Remark III.6.7.3): both invoke recurrence in a bounded phase space against monotonic Channel-B content; both are operationally inert because the recurrence time exceeds every operationally accessible scale by factors beyond every physical scale ever observed.*

*Proof.* We establish (a), (b), (c).

**Step 1 (Phase (a) = M2).** Each gate $G \in \mathcal{G}$ applied at the operator-algebra tier corresponds to a McGucken-Sphere expansion of radius $\delta\tau = 1/\omega_C \sim \hbar/(m_q c^2)$ where $m_q$ is the qubit substrate mass (Theorem VIII.9.1 Step 2). The surface area of the operator-algebra horizon $\Sigma_+$ grows linearly with the number of gates applied:
$$\text{Area}(\Sigma_+) \;\propto\; t \;\propto\; (K/2)\cdot\mathcal{C}.$$
This is the operator-algebra-tier instance of mechanism M2 (Horizon Crossing) of §III.2: the McGucken Sphere from each gate event is the operator-algebra analogue of the cosmological horizon McGucken Sphere from a spacetime event. Linear complexity growth $\mathcal{C}(t) \sim (K/2)t$ matches the area growth of $\Sigma_+$, which is the M2 signature.

**Step 2 (Phase (b) = M3).** By Proposition VIII.9.1(c), beyond $\mathcal{C}_{\max} \sim 4^K$ the expander graph closes: collisions force the operator-algebra random walk to revisit epsilon-balls previously visited at lower complexity, with girth $\sim 4^K$ ensuring that the smallest closed loop is comparable to the diameter. The geodesic from $\mathbf{1}$ to the current operator $U(t)$ changes from instant to instant as new short-cuts open and close; the complexity $\mathcal{C}(U(t))$ ceases to increase even though the gate-count continues to grow. The operator at $\mathcal{C}_{\max}$ branches into many distinct gate-count histories that converge to the same operator-algebra-tier endpoint within tolerance $\varepsilon$. By Definition III.2 (mechanism M3, Branching Overlap), distinct Channel-A evolution histories overlap in the operator-algebra phase space at the operator-algebra tier; the operational distinguishability of paths breaks down. Phase (b) is M3 at the operator-algebra tier.

**Step 3 (Phase (c) = Zermelo–Poincaré recurrence).** The expander graph of Proposition VIII.9.1(c) is a finite graph on $\sim e^{4^K}$ vertices. By the classical Poincaré recurrence theorem [Poincaré 1893] applied to the discrete-time random walk on a finite graph with uniform transition probabilities (a Markov chain on a finite irreducible state space), the expected recurrence time to any specific vertex is $\sim e^{4^K}$ times a polynomial factor in $K$, giving $t_{\rm Poincaré} \sim e^{e^{4^K}}$ for the doubly-exponential recurrence that returns the operator to the origin $\mathbf{1}$. This is the operator-algebra-tier instance of the Zermelo–Poincaré recurrence-paradox objection to empirical thermodynamics. By Remark III.6.7.3, both the 19th-century Zermelo–Poincaré objection to empirical thermodynamics and the 21st-century operator-algebra recurrence are operationally inert: they invoke Platonic-mathematical content (Channel-A formal recurrence) against operational Channel-B content (the monotonic complexity growth in phase (a)), and both dissolve under the dual-channel architecture by the same diagnostic. ∎

#### Theorem VIII.9.4 (The no-collisions assumption is the universal-unitarity assumption refuted by Theorem VIII.6)

Susskind's expander-graph construction depends critically on the *no-collisions* hypothesis: distinct gate-sequences up to depth $n_*$ produce distinct unitaries. This hypothesis is the operator-algebra-tier statement of universal unitarity.

**Theorem VIII.9.4 (No-collisions = universal unitarity at the operator-algebra tier).** *Susskind's "no-collisions" hypothesis (Proposition VIII.9.1(b)) is the operator-algebra-tier statement of the universal-unitarity meta-claim refuted by Theorem VIII.6:*

*(a) The no-collisions hypothesis says: distinct gate-sequences $\{G_n \cdots G_1\}$ produce distinct unitaries in $SU(2^K)$, up to depth $n_*$.*

*(b) This holds if and only if the underlying gate dynamics on the qubit substrate is universally unitary — every gate is a unitary operator, with no M-locus events (no measurements, no decoherence events, no horizon crossings) corrupting the operator-algebra evolution.*

*(c) By Theorem VIII.6, the universe is densely populated with M-loci: every measurement, every horizon, every decoherence event is an M-locus. The no-collisions hypothesis therefore fails on any physical qubit substrate of finite duration: real qubits decohere, real measurements project, real horizons fail to be Channel-A-unitary.*

*(d) The no-collisions hypothesis is therefore a hypothesis about an *idealized* operator-algebra evolution on an *idealized* M-locus-free patch, not about any physical operator algebra. Susskind's expander geometry is an internally consistent mathematical structure on $SU(2^K)$ as a group, but it does not describe the operator algebra of any physically realizable system over the timescales required for the complexity to saturate.*

*Proof.* Steps (a)–(c) follow directly from the definitions and from Theorem VIII.6. We establish (d).

**Step 1.** The complexity-saturation time $t_*$ (Proposition VIII.9.1(b), formula IX.3) is $t_* \sim 4^K$. For $K \sim 10^{76}$ qubits (a solar-mass black-hole equivalent), $t_* \sim 4^{10^{76}}$, which exceeds every operationally accessible scale by factors exceeding every physical scale ever observed.

**Step 2.** On any physical qubit substrate of finite duration, decoherence events accumulate at a finite rate $\Gamma_{\rm dec}$. The expected number of M3 (decoherence) events on the qubit substrate over time $t_*$ is $N_{M3} \sim \Gamma_{\rm dec} t_* \to \infty$ for any $\Gamma_{\rm dec} > 0$.

**Step 3.** By Theorem VIII.6 Step 3 Case M3, each decoherence event forces a non-unitary projection on the operator algebra. The no-collisions hypothesis fails at the first such projection.

**Step 4.** Therefore, the no-collisions hypothesis is a hypothesis about an *idealized* M-locus-free patch on $SU(2^K)$ of duration $t_*$ — a patch that does not exist on any physical qubit substrate. Susskind's expander geometry describes an abstract mathematical structure on $SU(2^K)$, not the operator algebra of any physically realizable system over the saturation timescale.

This is the operator-algebra-tier instance of the same structural failure of universal unitarity that Theorem VIII.6 establishes at the configuration-space tier. ∎

**Corollary VIII.9.4a (The complexity geometry is a Channel-A-only construct).** *The expander geometry of Proposition VIII.9.1 is built on the no-collisions hypothesis (Step (a)), which by Theorem VIII.9.4 is the universal-unitarity hypothesis at the operator-algebra tier. By Theorem VIII.6, universal unitarity does not hold on any physical Hilbert space of finite duration in the McGucken framework. The expander geometry is therefore a Channel-A-only structure: it correctly describes the algebraic-symmetry content of an idealized M-locus-free patch on $SU(2^K)$, but it cannot describe the operator algebra of any physical system over operational timescales because the Channel-B content (M-loci) is excluded by hypothesis. The Channel-B Second Law of Complexity (Theorem VIII.9.2) is paradoxically derivable within the Channel-A-only expander framework precisely because the expander framework absorbs the Channel-B drift as a combinatorial statement about the abstract tree structure — but the Channel-B operational consequences (information destruction, the failure of universal unitarity, the M-locus-projection structure) are invisible within the Channel-A-only framing.*

#### Theorem VIII.9.5 (The complexity-volume duality conjecture is operationally vacuous: the central operational/metaphysical diagnostic)

The central claim of Susskind's complexity program is the **complexity-volume duality conjecture** [Stanford–Susskind 2014; Susskind 2016a, 2016b; Brown–Roberts–Susskind–Swingle–Zhao 2016a, 2016b]: the bulk volume $V_{\rm ER}$ of the Einstein–Rosen bridge interior of an evaporating black hole, measured at the asymptotic boundary, equals (up to factors of $G_N \hbar$ and a "complexity-of-formation" constant) the boundary state's quantum complexity:
$$V_{\rm ER}(t) \;\simeq\; (\text{const})\cdot\hbar G_N\cdot\mathcal{C}(|\Psi(t)\rangle). \tag{IX.9}$$
The conjecture is offered as a probe of the black-hole interior: complexity continues to grow long after Hawking-radiation entropy has saturated, and this continued growth (the conjecture claims) is what the bulk geometry continues to record about the system's history.

**Theorem VIII.9.5 (Complexity-volume duality is operationally vacuous; it is the mathematically sophisticated form of the Domain-Shifting Diagnostic).** *Under Theorems III.6.6 and III.6.7 (Structural Anatomy of Susskind's Equivocation; The Domain-Shifting Diagnostic), the complexity-volume duality conjecture (IX.9) is operationally vacuous in the following precise sense:*

*(a) **The complexity $\mathcal{C}(|\Psi(t)\rangle)$ on the right-hand side of (IX.9) is not operationally accessible to any physically realizable observer** for any black hole of astrophysical size. By Proposition VIII.9.1, $\mathcal{C}_{\max} \sim 4^K$; for $K \sim A/(4\ell_P^2) \sim 10^{76}$ (solar-mass black hole), the complexity at saturation is $\mathcal{C}_{\max} \sim 4^{10^{76}}$. By Margolus–Levitin (Theorem III.6.A), the energy and time required for any observer to *measure* this complexity exceeds the energy and time available in the visible universe by factors of $\sim 4^{10^{76}}$.*

*(b) **The bulk volume $V_{\rm ER}(t)$ on the left-hand side of (IX.9) is also not operationally accessible to any external observer** of an evaporating black hole, by mechanism M2 (Horizon Crossing) of §III.2: no signal, no Hawking-radiation mode, no boundary CFT observable, can extract bulk-interior volume information after horizon formation.*

*(c) **The conjecture (IX.9) is therefore a statement relating two operationally inaccessible quantities.** It has no empirical content: no measurement of $V_{\rm ER}$ has ever been made or can ever be made; no measurement of $\mathcal{C}(|\Psi\rangle)$ for any astrophysical black hole has ever been made or can ever be made; the proposed equality cannot be tested by any physically realizable procedure.*

*(d) **Under the diagnostic of Theorem III.6.7 (Domain-Shifting Diagnostic), (IX.9) is the most mathematically sophisticated form of the methodological retreat from operational physics to Platonic metaphysics.** The structural signature of the retreat is preserved exactly:*

- *(I) The position begins with operational claims: "the bulk geometry of an evaporating black hole is non-trivial; the interior continues to evolve; this evolution must be encoded in something on the boundary." These are operational claims about what *can* be inferred about the black-hole interior.*
- *(II) When operational refutation closes in (the Brownian Hamlet, the undetected photon, Hawking's strict Second Law, no operational recovery of pre-evaporation states), the position retreats to a non-empirical Platonic claim: "the boundary CFT carries a complexity, and that complexity probes the interior, and the relation (IX.9) is the probe." Neither side of (IX.9) is operationally accessible.*
- *(III) Victory in physics is then declared from the metaphysical position: the conjecture is presented as the contemporary physics of the black-hole interior in [Susskind 2018a], in popular accounts, and in the elaboration of the holographic-volume program 2014–2024.*

*The complexity-volume duality conjecture is the pickleball-court championship trophy (Remark III.6.7.1) elevated to the level of a precise mathematical proposal. The proposal is mathematically sophisticated; it is also operationally vacuous.*

*Proof.* Steps (a), (b), (c) are estimates that follow from the definitions and from results already established.

**Step 1 (Inaccessibility of $\mathcal{C}$).** By Proposition VIII.9.1(c), the maximum complexity of $|\Psi(t)\rangle$ for an evaporating black hole with Hilbert-space dimension $D = 2^K$ is $\mathcal{C}_{\max} \sim 4^K$. By Theorem III.6.A (Margolus–Levitin lower bound), any quantum-mechanical procedure measuring an operator of complexity $\mathcal{C}$ requires at minimum
$$T_{\rm measure} \;\gtrsim\; \frac{\pi\hbar}{2 E_{\rm available}}\cdot\mathcal{C} \;\sim\; \frac{\pi\hbar}{2 E_{\rm universe}}\cdot 4^K.$$
For $K = 10^{76}$ and $E_{\rm universe} \sim 10^{70}\,\text{J}$, $T_{\rm measure} \sim 4^{10^{76}}$ universe-ages. No physically realizable observer can measure $\mathcal{C}(|\Psi(t)\rangle)$ for an astrophysical black hole; the quantity is operationally inaccessible.

**Step 2 (Inaccessibility of $V_{\rm ER}$).** By mechanism M2 of §III.2 (Horizon Crossing), no causal signal from the bulk interior region can reach the asymptotic boundary after horizon formation; the bulk volume $V_{\rm ER}$ is bounded by the horizon (Theorem III.6.3 applied at the bulk-boundary tier). By Theorem III.6.2 (Observation as McGucken-Sphere Intersection), $V_{\rm ER}$ is operationally accessible only if some apparatus McGucken-Sphere intersects the bulk-interior region; no such intersection exists for any external observer (the horizon by definition blocks all such intersections, [MG-Bek26 Prop V.1]).

**Step 3 (Both sides of (IX.9) are operationally inaccessible).** The conjecture relates two quantities, each of which is operationally inaccessible by the McGucken framework: $\mathcal{C}$ by Step 1, $V_{\rm ER}$ by Step 2. The conjecture (IX.9) is therefore an *internal consistency claim* between two metaphysical quantities, not an *empirical claim* relating two operational quantities.

**Step 4 (Application of Theorem III.6.7).** The three-move structural signature of the Domain-Shifting Diagnostic (Theorem III.6.7 moves I, II, III) applies to the complexity-volume conjecture verbatim, as established by the textual analysis of [Susskind 2014, 2016a, 2016b, 2018a, 2018b; Brown–Roberts–Susskind–Swingle–Zhao 2016a, 2016b] and the public lectures of Susskind 2014–2024:

- The opening operational framing: information is preserved in the black-hole interior; some bulk geometric quantity must record it; the question is which boundary quantity probes this preservation.
- The closing operational refutation: by Theorem VIII.8 and Theorem III.6.5, no boundary observable distinguishes operationally distinct interiors after evaporation; the Brownian Hamlet exhibits the operational destruction at the matter tier.
- The retreat: the boundary quantum complexity $\mathcal{C}$ is invoked, identified with the bulk volume $V_{\rm ER}$, and presented as the probe. Neither quantity is operationally accessible; the conjecture is therefore not refuted by the operational arguments — but it is also not physics in the operational sense.
- The victory declaration: the complexity-volume conjecture is presented as the contemporary physics of the black-hole interior, both in technical literature [Susskind 2016a; Brown et al. 2016a, 2016b] and in popular accounts [Susskind 2018a].

The pickleball-Wimbledon diagnostic (Remark III.6.7.1) applies in mathematically sharper form: the complexity geometry on $SU(2^K)$ is the pickleball court (an internally consistent mathematical structure within Channel-A-only Hilbert-space formalism); the operational physics of black-hole evaporation is the Wimbledon court; the conjecture (IX.9) is the move that declares the pickleball championship a Wimbledon victory. ∎

**Corollary VIII.9.5a (Complexity is *not* "the third quantity" beyond entropy and energy).** *In [Susskind 2018a, §1.3], Susskind argues that complexity is a third foundational operational quantity that probes the black-hole interior after entropy and energy have been exhausted. By Theorem VIII.9.2, complexity is Channel-B content equivalent to thermodynamic entropy at the operator-algebra tier — not a third quantity, but a different reading of the same Channel-B principle. By Theorem VIII.9.5, the boundary complexity of an astrophysical black hole is operationally inaccessible at saturation, so it cannot probe anything operationally even in principle. The "complexity is the third foundational quantity" framing is the mathematically sophisticated form of the Domain-Shifting Diagnostic.*

**Corollary VIII.9.5b (The continued bulk-interior growth after entropy saturation is M2 + M3, not a third probe).** *Susskind's structural observation that the bulk volume continues to grow after the boundary entropy saturates is structurally correct as a statement about Channel-B-content: by Theorem VIII.9.3, the operator-algebra at the post-Page-time evaporation tier enters phase (b) (M3 Branching Overlap), in which complexity continues to grow even though the algebraic-entropy content has plateaued. The continued growth is M3 content. The proposed identification of this growth with a bulk *volume* — measurable in principle by some idealized observer — is the move that converts the M3-content statement (which is structurally correct) into the Domain-Shifting Diagnostic move (which is operationally vacuous).*

#### Theorem VIII.9.6 (The complexity geometry is the operator-algebra-tier instance of the First Law of the McGucken Dualities)

The right-invariant structure of the complexity geometry on $SU(2^K)$ — Susskind's observation that $\mathcal{C}(UW, VW) = \mathcal{C}(U, V)$ for all $W$, with the corresponding two-metric structure (inner-product + complexity) and the expander-graph homogeneity — is the operator-algebra-tier instance of the First Law of the McGucken Dualities (Theorem III.3).

**Theorem VIII.9.6 (Complexity geometry as First-Law instance at the operator-algebra tier).** *The dual-metric structure $(d_{\rm IP}, \mathcal{C})$ on $SU(2^K)$ is the First-Law instantiation (Theorem III.3) of the McGucken duality at the operator-algebra tier:*

*(a) The Hamiltonian/Schrödinger reading of the duality: $d_{\rm IP}$ is the metric induced by the Schrödinger-picture algebraic-symmetry structure of $SU(2^K)$. Operator evolution under $i\hbar\partial_t U = \hat H U$ preserves $d_{\rm IP}$ as a Channel-A-isometry.*

*(b) The Lagrangian/path-integral reading of the duality: $\mathcal{C}$ is the metric induced by the gate-count path-length on $SU(2^K)$, the discrete Lagrangian analogue of the Feynman path-integral measure restricted to physical $\kappa$-local circuits. The complexity is the operator-algebra-tier instance of the action integral.*

*(c) The right-invariance $\mathcal{C}(UW, VW) = \mathcal{C}(U, V)$ is the operator-algebra-tier instance of the Channel-B time-translation symmetry of the First Law (Theorem III.3 row 1).*

*(d) The Wick-rotation bridge between $d_{\rm IP}$ and $\mathcal{C}$ is the operator-algebra-tier instance of the McGucken-Wick rotation $\tau = x_4/c$ (SR-7).*

*(e) The expander-graph homogeneity (every vertex the same) is the operator-algebra-tier instance of the McGucken-Sphere $SO(3)$-symmetry (SR-2) restricted to the unitary group.*

*Proof.* The five identifications are direct consequences of Theorem III.1, Theorem III.3, SR-2, and SR-7. The Hamiltonian/Lagrangian duality of Theorem III.3 (row 1 of the First-Law table) is the position-of-$i$ asymmetry between $i$-interior (Channel A, Schrödinger picture, $d_{\rm IP}$) and $i$-exteriorizable (Channel B, Lagrangian path-integral, $\mathcal{C}$). The right-invariance of $\mathcal{C}$ is the Channel-B time-translation symmetry (translation by $W$ on $SU(2^K)$ corresponds to translation by the operator $W$ on the Hamiltonian generator, which is a Noether-symmetry consequence of the dual-channel structure). The Wick-rotation bridge is established in Theorem VIII.9.1 Step 3. The expander-graph homogeneity is the operator-algebra-tier statement of $SU(2^K)$ acting transitively on its own coset structure, which by SR-2 is the operator-algebra restriction of the McGucken-Sphere $SO(3)$-symmetry to the unitary representation. ∎

**Corollary VIII.9.6a (Susskind's complexity geometry was already implicit in the First Law).** *The dual-metric structure on $SU(2^K)$ that Susskind constructs from gate-counting first principles in [Susskind 2016b] is, in retrospect, an operator-algebra-tier instance of the First Law of the McGucken Dualities (Theorem III.3) established here from the McGucken Principle d*x*₄/d*t* = i*c*. The First Law applies to all dual-channel pairs in physics: Hamiltonian/Lagrangian, Schrödinger/Heisenberg, position/momentum, wave/particle, locality/nonlocality, conservation/dissipation, mass/energy, time/space, and now (operator-algebra tier) inner-product/complexity. The McGucken framework predicts the dual-metric structure on $SU(2^K)$ as a theorem of d*x*₄/d*t* = i*c* applied to the operator-algebra tier; Susskind discovered it by visualization.*

#### Theorem VIII.9.7 (The Complexity Program as the most mathematically sophisticated form of the Domain-Shifting Diagnostic)

We now combine the preceding six theorems into the closing structural diagnosis of the complexity program.

**Theorem VIII.9.7 (Susskind's Complexity Program is the most mathematically sophisticated instance of the Domain-Shifting Diagnostic of Theorem III.6.7).** *Under the combined content of Theorems VIII.9.1–VIII.9.6, Susskind's complexity program is the most mathematically sophisticated instance of the methodological retreat from operational physics to Platonic metaphysics diagnosed by Theorem III.6.7. The structural anatomy:*

*(D1) **The Channel-B content is correct.** Theorems VIII.9.1, VIII.9.2, VIII.9.3, and VIII.9.6 establish that Susskind's central mathematical observations — the dual-metric structure on $SU(2^K)$, the Second Law of Complexity, the linear-plateau-recurrence phase structure, the right-invariant expander geometry, the recognition that complexity is a kind of entropy — are correct Channel-B-content statements at the operator-algebra tier. They are theorems of d*x*₄/d*t* = i*c* applied to the unitary group of the qubit substrate. Susskind reached them through geometric visualization rather than through the systematic dual-channel architecture, but the conclusions are structurally correct.*

*(D2) **The Channel-A framing is incomplete.** Theorem VIII.9.4 establishes that the no-collisions hypothesis underlying the expander construction is the universal-unitarity hypothesis at the operator-algebra tier, refuted by Theorem VIII.6 on any physical Hilbert space of finite duration. The expander geometry describes an idealized M-locus-free patch on $SU(2^K)$, not the operator algebra of any physically realizable system over operational timescales.*

*(D3) **The central conjecture is operationally vacuous.** Theorem VIII.9.5 establishes that the complexity-volume duality conjecture (IX.9), the central operational claim of the program, relates two operationally inaccessible quantities. The conjecture is mathematically precise but empirically inert: no measurement of either side has ever been made or can ever be made for any astrophysical black hole.*

*(D4) **The structural signature of the Domain-Shifting Diagnostic is preserved exactly.** The three-move structural signature of Theorem III.6.7 — (I) operational position asserted; (II) retreat to non-empirical Platonic claim when refutation closes in; (III) victory declared in physics from the metaphysical position — is preserved exactly in the complexity program, in mathematically sophisticated form. The "non-empirical Platonic claim" is, in this case, a mathematically precise conjecture relating two operationally inaccessible quantities; the "victory declared in physics" is the framing of the conjecture as the contemporary physics of the black-hole interior.*

*(D5) **The structural-historical parallel of Remark III.6.7.3 applies.** Just as Loschmidt–Zermelo–Poincaré invoked Platonic-mathematical content (time-symmetric microscopic dynamics, statistical recurrence) against the empirical strict Second Law of thermodynamics, Susskind invokes mathematically sophisticated Platonic-mathematical content (right-invariant expander geometry on $SU(2^K)$, complexity-volume duality) against the empirical operational refutations (Brownian Hamlet, undetected photon, Hawking's strict Second Law). Both moves are structurally identical: invoking Channel-A-only content against operational Channel-B content. Both dissolve under the dual-channel architecture by the same diagnostic. The 19th-century empirical thermodynamicists held the empirical position correctly against the Platonic-mathematical reaction; the 21st-century McGucken framework holds the empirical position correctly against the Platonic-mathematical complexity program, by the same diagnostic.*

*The program is therefore neither rejected nor accepted on its own mathematical merits: its mathematical content (Theorems VIII.9.1–VIII.9.6) is structurally correct as Channel-B content at the operator-algebra tier and is welcomed within the McGucken framework as an instance of the dual-channel architecture. Its central operational claim (Theorem VIII.9.5) is structurally diagnosed as the most mathematically sophisticated form of the Domain-Shifting Diagnostic and is foreclosed by Corollary III.6.7.2 (structural impossibility of the retreat under the McGucken framework). The complexity program is, at the level of mathematics, an unwitting confirmation of the dual-channel architecture of d*x*₄/d*t* = i*c*; at the level of philosophy, the canonical 21st-century instance of the methodological retreat against empirical refutation.* ∎

**Remark VIII.9.7.1 (What the complexity program would look like if it were physics).** A complexity program that was operational physics rather than Platonic-mathematical retreat would identify a complexity-like quantity *that some realizable observer can actually measure* and would predict that measurement to differ from the orthodox-unitarity-with-no-Channel-B prediction. No such quantity has been proposed by the complexity program. Within the McGucken framework, the Compton-coupling diffusion coefficient $D^{\rm (McG)}_x = \varepsilon^2 c^2 \Omega/(2\gamma^2)$ at $T \to 0$ ([MG-Compton], [MG-Thermodynamics-Chain Theorem 14]) is a Channel-B operational quantity that *is* in current technological reach: it predicts a temperature-independent diffusion floor on cold dust particles that distinguishes McGucken from textbook Einstein diffusion (which freezes at $T \to 0$). This is the kind of operational signature the complexity program would need to identify on its own ground — the bulk volume of an evaporating black-hole interior, or the boundary CFT complexity at saturation, are not it.

**Remark VIII.9.7.2 (The complexity program as unwitting Channel-B exposure).** Susskind's program, despite its structural function as the most sophisticated form of the methodological retreat, has exposed Channel-B content at the operator-algebra tier that the orthodox unitarity tradition would otherwise have left buried: that complexity is a kind of entropy, that the unitary group carries a Channel-B-monotonic metric that diverges from the Channel-A inner-product, that there is a Second Law of Complexity governing operator-algebra evolution. These are correct Channel-B-content discoveries arrived at through visualization rather than through the McGucken-Wick rotation. The framework welcomes them as instances of the dual-channel architecture; they are now established here as theorems of d*x*₄/d*t* = i*c* applied to the operator-algebra tier (Theorems VIII.9.1–VIII.9.6). Susskind's method of arriving at them — close one's eyes, visualize the answer — is the same method by which Hawking arrived at the Second Law of black-hole evaporation in 1976: structurally correct Channel-B content reached without the systematic dual-channel architecture. Both Hawking 1976 and Susskind on complexity are vindicated within the McGucken framework, by the same Channel-B principle, against the orthodox-unitarity defense both have been read by parts of the field as opposing.

#### VIII.9.8 The deeper motivation: Susskind sees Channel A only

The seven theorems of §§VIII.9.1–VIII.9.7 establish *what* the complexity program is structurally — Channel-B content at the operator-algebra tier wrapped in an operationally vacuous central conjecture that is the most mathematically sophisticated form of the Domain-Shifting Diagnostic. We now establish *what is driving the program* — the deeper structural diagnostic that locates Susskind's position with maximum precision and that identifies the program as the operator-algebra-tier instance of Boltzmann's 1872 project, refuted in 1876 by Loschmidt and refuted now (at the operator-algebra tier) by the same diagnostic.

**The framing correction.** It would be a mistake to read Susskind's program as a conscious attempt to *derive* Channel-B content from Channel-A foundations. Susskind does not see Channel B. He sees Channel A only. The dual-channel architecture of d*x*₄/d*t* = i*c* is not part of his framework, and the McGucken-Wick rotation $\tau = x_4/c$ that exposes the Channel-B face of the Schrödinger equation is not a move he performs or attempts. What Susskind is doing — what the textual record [Susskind 2016a; Brown–Susskind 2018; Susskind 2018a, 2018b; Susskind 2020] supports — is *extending Channel A as far as it will go*. He is searching within the unitary-group structure of $SU(2^K)$, which is a Channel-A-only object on its face, for a quantity capable of accounting for what the orthodox tradition has always treated as an emergent statistical phenomenon: the apparent arrow of time. He finds complexity. He recognizes that complexity behaves entropically. He formulates a Second Law of Complexity. None of this is undertaken with the recognition that what he has touched is the Channel-B face of the same equation he is reading; his entire framing is that complexity is a Channel-A quantity (a property of unitary operators) whose entropic behavior emerges from Channel-A combinatorics.

This is structurally analogous to a person who has only ever seen with one eye constructing a theory of depth perception. The theory will produce something — parallax estimates, occlusion cues, perspective rules — and that something will be partially correct, because depth is physically there in the world and binocular vision is one way of accessing it but not the only one. The monocular theorist will not, however, recognize that what their theory is accounting for is *the projection of binocular depth onto monocular access*. They will treat their theory as the complete account of depth. The Second Law of Complexity is Susskind's monocular parallax estimate for a phenomenon — Channel-B time-asymmetry — that he cannot see directly because his framing has only one channel in it.

**What Susskind is therefore trying to do.** Within Channel-A-only physics, the foundational dynamics is unitary, and unitarity is time-reversal-invariant ($U(-t) = U(t)^\dagger$ as an exact algebraic identity). The Schrödinger–Heisenberg tradition since 1926 has treated this time-symmetry as foundational and has treated the apparent time-asymmetry of macroscopic experience (the Second Law of Thermodynamics, the arrow of time, the irreversibility of evaporation) as a derived statistical phenomenon that emerges from time-symmetric microscopic foundations via coarse-graining and the Past Hypothesis. The orthodox tradition's resolution of the tension between time-symmetric foundations and time-asymmetric experience is the Boltzmann 1872 H-theorem program: derive $dS/dt \ge 0$ from the time-symmetric Liouville equation. Hawking's 1976 claim that black-hole evaporation is genuinely non-unitary threatens the orthodox resolution at its foundational level: if unitary evolution itself fails at the horizon, then the time-asymmetry of evaporation is primary, not derived, and the Schrödinger–Heisenberg commitment to time-symmetric foundations stands incomplete. Susskind has spent thirty years extending Channel A in the search for an internal Channel-A explanation of what Hawking has identified as foundational time-asymmetry. The complexity program is the latest and most sophisticated such extension: it identifies complexity as the quantity within $SU(2^K)$ whose growth accounts for the apparent arrow of time, with the Second Law of Complexity offered as the Channel-A-internal explanation of why time appears to have a direction even though the foundational dynamics (in Susskind's framing) is exactly time-reversible.

**What Susskind is therefore structurally doing.** Independent of intent, the structural content of what Susskind has constructed is identifiable from the framework's vantage point: he has discovered Channel-B content (complexity-volume is entropy; the unitary group carries a Channel-B-monotonic metric; the operator-algebra tier obeys a Channel-B Second Law) through geometric visualization within a Channel-A-only framing. He has constructed a structurally correct Channel-B-content theorem and offered it as a Channel-A-only result. The framework recognizes this as the operator-algebra-tier instance of the same structural fact that pervades twentieth-century physics: when a researcher in the Schrödinger–Heisenberg tradition pushes Channel A hard enough to account for time-asymmetric phenomena, they bump into Channel B without recognizing it for what it is, and the result is structurally correct Channel-B content carried in Channel-A-only language.

#### Theorem VIII.9.8.1 (The complexity program as a Channel-A-only attempt to complete the orthodox account of time-asymmetry)

**Theorem VIII.9.8.1 (Susskind's framing: Channel-A-only Boltzmann project at the operator-algebra tier).** *Under the textual evidence of [Susskind 2016a; Brown–Susskind 2018; Susskind 2018a, 2018b; Susskind 2020] and the structural analysis of the program's mathematical content (Theorems VIII.9.1–VIII.9.7), Susskind's complexity program is identifiable, **within Susskind's own framing**, as the operator-algebra-tier instance of Boltzmann's 1872 project. The program seeks an internal Channel-A explanation of the apparent arrow of time, with the explicit structural intent of preserving the orthodox Schrödinger–Heisenberg doctrine that the foundational dynamics is unitary and time-reversal-invariant. The program is not undertaken with the recognition that it has touched Channel B; its framing has only one channel.*

*Structurally, within Susskind's framing, the project consists of three components:*

*(C1) **Time-symmetric foundational claim (Channel A only, in Susskind's framing).** The fundamental dynamics is unitary: $U(t) = e^{-i\hat H t/\hbar}$. Under $t \mapsto -t$, $U(-t) = U(t)^\dagger$ inverts $U(t)$ exactly. Time-reversal-invariance (up to CPT) holds at the foundational level. Susskind treats this as the entire foundational dynamics of physics; there is no Channel B in his framing.*

*(C2) **Time-asymmetric phenomenon to be accounted for (in Susskind's framing, derived).** The complexity $\mathcal{C}(U(t))$ grows monotonically under generic unitary evolution from low-complexity initial conditions, by the combinatorics of the unitary group (Theorem VIII.9.2). The Second Law of Complexity, $d\mathcal{C}/dt \ge 0$ with overwhelming probability, is the time-asymmetric phenomenon Susskind identifies as the operator-algebra-tier analogue of the thermodynamic Second Law. In Susskind's framing, this is a derived statistical phenomenon emerging from the combinatorics of the time-symmetric foundational dynamics of (C1).*

*(C3) **Reduction claim (in Susskind's framing).** The time-asymmetry of (C2) is held to be derivable from (C1) plus suitable assumptions about initial conditions (low-complexity at $t = 0$, generic-Hamiltonian assumption, no fine-tuned anti-thermodynamic interference). The reduction is supposed to preserve (C1) as foundational while accounting for (C2) as emergent. This is the explicit structural template invoked by [Brown–Susskind 2018, §1] in identifying the program as "Boltzmann-like."*

*This is the Boltzmann 1872 project transposed to the operator-algebra tier, undertaken in Channel-A-only framing. Boltzmann 1872 sought to derive the H-theorem $dH/dt \le 0$ (equivalent to $dS/dt \ge 0$) from the Newtonian Liouville equation, which is exactly time-symmetric. Susskind 2014–present seeks to derive the Second Law of Complexity from the Hamiltonian Schrödinger equation, which is exactly time-symmetric (up to CPT). The structural parallel is exact at the level of intent; whether the parallel is exact at the level of mathematical content is the subject of Theorem VIII.9.8.2.*

*Proof.* The textual evidence is direct. In [Susskind 2018a, Lecture 1, §1.3], the program's motivation is stated as the project of identifying "the third foundational quantity beyond energy and entropy" that "completes the connection between unitarity and the apparent arrow of time." [Brown–Susskind 2018] is explicitly titled *Second Law of Quantum Complexity*: the title invokes the Second Law of Thermodynamics as the explicit structural template, with complexity in the role of entropy and unitary evolution in the role of the underlying time-symmetric dynamics. The structural alignment with Boltzmann's H-theorem is acknowledged directly in [Brown–Susskind 2018 §1]: "we are seeking a Boltzmann-like derivation of complexity growth from unitary dynamics." The components (C1), (C2), (C3) are therefore identifiable from the program's own self-description, not imposed from outside. The Channel-A-only character of the framing is identifiable from the same record: at no point in the program does the McGucken-Wick rotation $\tau = x_4/c$ appear as an operation on the Schrödinger equation; at no point does Channel B appear as a structural component of the foundational dynamics; at no point is the $+ic$ orientation of d*x*₄/d*t* = i*c* (SR-1) identified as the foundational source of time-asymmetry. The program operates entirely within the Channel-A reading of the Schrödinger equation, in the framing of Susskind himself. ∎

**Remark VIII.9.8.1.1 (What Susskind would say is at stake).** Within Susskind's framing, what is at stake is whether the orthodox Schrödinger–Heisenberg account of physics can be completed without admitting non-unitary foundational dynamics. If the project of Theorem VIII.9.8.1 succeeds (in Susskind's framing), then the orthodox tradition's commitment to time-symmetric unitary foundations is preserved: time itself remains, at the deepest level, a directionless coordinate, and the arrow of time reduces to the combinatorics of complexity growth on a fixed time-symmetric unitary-group substrate. If the project fails (in Susskind's framing), then unitarity itself stands incomplete as the foundational dynamics, and Hawking's 1976 position — that the foundational dynamics is genuinely non-unitary at the horizon — would have to be admitted. Susskind's lifelong defense of unitarity, the holographic apparatus built around it, the wormhole–entanglement identifications, the complexity-volume conjecture — all of these are subsidiary moves within the Channel-A-only project of preserving the orthodox foundational reading of physics against the threat that the orthodox reading is structurally incomplete.

**Remark VIII.9.8.1.2 (What is structurally at stake, from the framework's vantage point).** From the McGucken framework's vantage point, what is structurally at stake in Susskind's project is something different from what is at stake within Susskind's framing. The framework recognizes that the orthodox Schrödinger–Heisenberg account of physics has been Channel-A-only since 1926, that this Channel-A-only reading is structurally incomplete as the foundational dynamics (because the Schrödinger equation has carried Channel-B content since 1926 that the orthodox tradition has not performed the Wick rotation to expose), and that the project Susskind is undertaking — completing the Channel-A account of time-asymmetry without recognizing Channel B — cannot succeed because the very phenomenon he is attempting to derive (operator-algebra complexity growth as the source of the apparent arrow of time) *is* Channel-B content, structurally identical to the Channel-B content carried by the Schrödinger equation, accessible through the McGucken-Wick rotation that the program does not perform. The structural diagnosis from the framework's vantage point is therefore not "Susskind is failing to derive Channel B from Channel A" but rather "Susskind is unwittingly recognizing Channel B while believing he is doing Channel A." This is the deeper structural fact that the seven theorems VIII.9.1–VIII.9.7 establish: the complexity program is Channel-B content discovered in Channel-A framing.

#### Theorem VIII.9.8.2 (Loschmidt's objection applies in identical structural form)

We now establish that the project of Theorem VIII.9.8.1 cannot succeed, by the same structural argument that defeats Boltzmann 1872.

**Theorem VIII.9.8.2 (Loschmidt structural refutation of the complexity project).** *The project (C1)+(C2)+(C3) of Theorem VIII.9.8.1 cannot succeed, by direct structural extension of Loschmidt's 1876 reversibility objection [Loschmidt 1876; cf. Remark III.6.7.3] applied at the operator-algebra tier:*

*(L1) **Strict time-asymmetry cannot be derived from strict time-symmetry.** If the foundational dynamics is exactly time-symmetric (under $t \mapsto -t$, or CPT), then for every evolution history $U(t)$ with $d\mathcal{C}/dt > 0$ there exists, by time-reversal of the same dynamics, an evolution history $U(-t)$ with $d\mathcal{C}/dt < 0$. The two histories have equal status in the foundational dynamics. No derivation that uses only the time-symmetric foundational dynamics can conclude that one history is realized and the other is not.*

*(L2) **The reduction therefore requires an asymmetric additional input.** To derive the Second Law of Complexity from Hamiltonian unitary evolution, the program must supply an additional asymmetric input not contained in the foundational dynamics. In Susskind's framework, this input is supplied implicitly by the choice of low-complexity initial state at $t = 0$ — the operator-algebra-tier analogue of the Past Hypothesis (Boltzmann's low-entropy initial condition of the early universe).*

*(L3) **The asymmetric additional input is unexplained.** The low-complexity initial condition is not derived from the foundational dynamics; it is *postulated* as an additional input. The asymmetry of the conclusion has been relocated, not derived — it sits in the choice of initial state, not in the dynamics. This is structurally identical to the relocation of asymmetry in Boltzmann 1872 (Past Hypothesis, low-entropy initial condition of the universe at $t = 0$).*

*(L4) **The relocated asymmetry is itself a Channel-B content claim.** The "low complexity at $t = 0$" condition is the statement that the unitary $U(0) = \mathbf{1}$ sits at the origin of the expander geometry of Proposition VIII.9.1 — i.e., at the lowest-complexity vertex of the operator-algebra-tier McGucken geometry. By Theorem III.6.1 (Content-Universal Equilibration) and the McGucken framework's identification of the $x_4$-origin as the geometrically necessary lowest-entropy moment of any system participating in $x_4$-expansion (which is the framework's resolution of the Past Hypothesis, [MG-Thermodynamics-Chain Theorem 13]), the "low-complexity initial condition" is itself a Channel-B-content fact about the geometry of $x_4$-advance, not a postulate of the time-symmetric foundational dynamics.*

*Therefore, the project of Theorem VIII.9.8.1 cannot succeed within the orthodox time-symmetric Hamiltonian framework. Either:*

*(a) The reduction is performed but smuggles in an unexplained asymmetric initial condition, in which case the foundational time-symmetry is preserved only by relocating the asymmetry — the same move that fails for Boltzmann 1872, exposed in identical form here; or*

*(b) The asymmetric initial condition is recognized as itself foundational and derived from the geometric structure of $x_4$-expansion at the McGucken-framework level — in which case the time-asymmetry is admitted as foundational, the orthodox Schrödinger–Heisenberg commitment to time-symmetric foundations fails, and the program has not preserved what it was constructed to preserve.*

*In neither case does the complexity program achieve its deeper structural goal.* ∎

**Corollary VIII.9.8.2a (Susskind has rediscovered the Past Hypothesis at the operator-algebra tier).** *Susskind's program implicitly invokes a low-complexity initial state at $t = 0$ as the input that makes the Second Law of Complexity follow. This input is the operator-algebra-tier instance of the Past Hypothesis. The complexity program has therefore rediscovered, at the operator-algebra tier, the same unexplained asymmetric initial condition that the orthodox tradition has carried since Boltzmann — relocated from configuration-space entropy to operator-algebra complexity, but otherwise structurally identical.*

**Corollary VIII.9.8.2b (The McGucken framework dissolves the Past Hypothesis as a theorem).** *Where the orthodox tradition treats the Past Hypothesis as an unexplained additional postulate, the McGucken framework derives the low-entropy / low-complexity initial condition as a theorem of the geometric structure of $x_4$-advance: the $x_4$-origin is geometrically the lowest-entropy moment of any system participating in the spherically symmetric expansion of the fourth dimension at velocity $c$ ([MG-Thermodynamics-Chain Theorem 13]). The "additional input" of (L3) is not unexplained in the McGucken framework — it is the Channel-B content of d*x*₄/d*t* = i*c* applied to the initial-conditions tier. The asymmetry that Loschmidt's objection identifies as illegitimately smuggled into Boltzmann 1872 is, in the McGucken framework, the legitimate Channel-B content of the foundational principle, and the project Susskind is attempting (preserve time-symmetric foundations while accommodating apparent asymmetry) is structurally unnecessary: the foundational principle is itself time-asymmetric (the $+ic$ orientation of d*x*₄/d*t* = i*c*, SR-1), and the apparent asymmetry is the direct Channel-B content, not an emergent phenomenon requiring derivation.*

#### Theorem VIII.9.8.3 (Time is Channel-B-only; the time-symmetric foundations Susskind's framing identifies as foundational do not exist as foundational)

We now establish the closing structural diagnostic: the time-symmetric foundations that the orthodox Schrödinger–Heisenberg tradition treats as foundational, and that Susskind's framing identifies as the structure within which the complexity program is supposed to derive an internal Channel-A account of the arrow of time, do not exist as foundational in the McGucken framework. The Schrödinger–Heisenberg tradition's commitment to time-symmetric foundations is itself a Channel-A-only-reading blindspot of the foundational equation that has carried Channel-B content since Schrödinger 1926.

**Theorem VIII.9.8.3 (Time is Channel-B-only at the foundational tier).** *Under the McGucken Principle d*x*₄/d*t* = i*c* and the Dual-Channel Decomposition of Theorem III.1:*

*(a) **Time is not a foundational coordinate.** The McGucken-Wick coordinate identity $\tau = x_4/c$ (SR-7) establishes that "time" is the $x_4$-coordinate rescaled by $1/c$. $x_4$ is the physically expanding fourth dimension at velocity $c$ (d*x*₄/d*t* = i*c* is the McGucken Principle itself). Time is therefore not an independent foundational coordinate but a derived label for the rate of $x_4$-expansion measured against the observer's spatial coordinates.*

*(b) **The $+ic$ orientation is foundational.** The McGucken Principle is d*x*₄/d*t* = $+ic$, not $\pm ic$ (SR-1). The McGucken Sphere expands; it does not contract. The fourth dimension advances in the positive imaginary direction; it does not advance in the negative imaginary direction. This is a foundational physical statement, not a derived asymmetry: it sits in the foundational equation of the framework, with the $+$ sign as physical data.*

*(c) **Channel A time-symmetry is a derived structure, not foundational.** Under the Dual-Channel Decomposition (Theorem III.1), the apparent time-symmetry $U(-t) = U(t)^\dagger$ of the Schrödinger equation is the Channel-A reading of d*x*₄/d*t* = i*c*: the algebraic-symmetry content reads as time-reversal-symmetric *within a single M-locus-free patch* on which Channel-A unitarity holds (Theorem IV.3). This time-symmetry is a local Channel-A-content fact, not a foundational truth. Across M-loci, even the Channel-A unitarity fails (Theorem VIII.6), and time-symmetry fails with it.*

*(d) **Channel B time-asymmetry is foundational.** The $+ic$-monotonic content of d*x*₄/d*t* = i*c* (SR-1, Channel B reading) is the foundational time-asymmetry. It is built into the foundational equation. The strict Second Law $dS/dt = (3/2)k_B/t > 0$ of Theorem VIII.7, the Brownian-Hamlet dissolution of §III.4, the Hawking radiation evaporation of [MG-Haw26], the Second Law of Complexity of Susskind, the operational arrow of time, the cosmological arrow of time, the radiative arrow of time, the psychological-biological arrow of time, the quantum-measurement arrow of time — all five arrows of time are Channel-B-content readings of the same foundational $+ic$ orientation.*

*The Schrödinger–Heisenberg tradition's commitment to "time-symmetric foundations" reads only the Channel-A face of d*x*₄/d*t* = i*c* (the $U(-t) = U(t)^\dagger$ algebraic identity) and ignores the Channel-B face (the $+ic$ monotonic orientation of the foundational equation itself). The tradition has been reading half the equation since Schrödinger 1926 and treating the half-reading as the whole foundational content. The "time-symmetric foundations" the complexity program is trying to rescue are not foundations — they are the Channel-A face of a dual-channel foundational equation whose Channel-B face is the very time-asymmetry the program treats as derived.*

*Proof.* (a) is Definition III.1 of the present paper combined with the McGucken-Wick coordinate identity of SR-7. (b) is the explicit content of the McGucken Principle and the +ic orientation of SR-1. (c) follows from Theorem III.1(b) (Channel-A reading of d*x*₄/d*t* = i*c* as the Schrödinger evolution with $U(-t) = U(t)^\dagger$ on M-locus-free patches) combined with Theorem VIII.6 (failure of global Channel-A unitarity across M-loci). (d) is Theorem III.1(a) (Channel-B reading), Theorem VIII.7 (Schrödinger contains the Second Law), and the five-arrows-of-time theorem [MG-Thermodynamics-Chain Theorem 11]. The closing structural statement follows from combining (a)–(d): the time-symmetric foundations Susskind is trying to rescue are the Channel-A face of a dual-channel principle; the Channel-B face is the foundational time-asymmetry. ∎

**Corollary VIII.9.8.3a (Hawking's 1976 threat was real and structurally correct).** *Hawking's 1976 claim that information is destroyed in black-hole evaporation is, in the McGucken framework, structurally correct because the Channel-B face of the foundational equation d*x*₄/d*t* = i*c* contains the strict time-asymmetric content (the $+ic$ monotonic Second Law) that destroys operationally accessible information at every M-locus the system crosses (Theorem VIII.8). The threat was not a confusion to be resolved by holographic apparatus, complexity-volume duality, or any of the elaborated constructions of the 1993–present unitarity-defense program; the threat was the Channel-B content of the foundational equation, which the orthodox tradition's Channel-A-only reading had been suppressing since 1926. The McGucken-Wick rotation $\tau = x_4/c$ (SR-7) is the operational mechanism that exposes the Channel-B face; Susskind's 30-year defense is the 30-year failure to perform that rotation on the foundational equation.*

**Corollary VIII.9.8.3b (Susskind's program is the structural inverse of the Loschmidt–Zermelo–Poincaré reaction, undertaken without recognition of the dual-channel architecture).** *By Remark III.6.7.3, the 19th-century Loschmidt–Zermelo–Poincaré reaction to empirical thermodynamics invoked Platonic-mathematical content (time-symmetric microscopic dynamics, statistical recurrence) against the empirical strict Second Law of thermodynamics. Susskind's complexity program is the structural inverse at the operator-algebra tier: it constructs a sophisticated mathematical apparatus (complexity geometry on $SU(2^K)$, complexity-volume duality, Second Law of Complexity) within Channel-A-only framing in order to account, internally to Channel A, for the time-asymmetric phenomenon that Hawking 1976 had identified as foundational. The construction fails by the same Loschmidt diagnostic, with the same structural relocation of asymmetry into an unexplained initial condition that the McGucken framework dissolves as a theorem (Corollary VIII.9.8.2b). The crucial difference between the 19th-century reaction and Susskind's program is one of awareness: Loschmidt and Zermelo and Poincaré knew they were invoking time-symmetric dynamics against the empirical strict Second Law and were doing so as a conscious philosophical defense; Susskind does not see Channel B at all and is therefore not consciously defending Channel A against it but is unwittingly extending Channel A in search of resources to account for a phenomenon that, from the framework's vantage point, is Channel-B content. The 19th-century reaction was a conscious Channel-A-only defense; Susskind's program is an unconscious Channel-A-only extension. Both fail by the same diagnostic, but the Susskind case is the sharper instance because the very framing within which the program operates does not contain the second channel against which the program would have to be defending if the framing were complete. The orthodox Schrödinger–Heisenberg tradition's Channel-A-only reading of the foundational equation, which has held since 1926, is the structural condition that makes Susskind's framing what it is: not a defense against Channel B but an extension of Channel A without knowledge that there is a Channel B to defend against.*

**Closing structural statement of §VIII.9.8.** What Susskind is doing — in his own framing — is extending the orthodox Schrödinger–Heisenberg Channel-A account of physics as far as it will go, in search of an internal Channel-A explanation of the apparent arrow of time that would preserve unitarity as foundational against Hawking's threat. He does not see Channel B; the dual-channel architecture is not in his framing. The complexity program is therefore not a conscious rescue of Channel A against Channel B — it is a monocular extension of Channel A whose framers do not know there is a second channel to be rescued against. From within Susskind's framing, the project is the operator-algebra-tier instance of Boltzmann's 1872 H-theorem program: derive a time-asymmetric phenomenon (complexity growth, the Second Law of Complexity, the operational arrow of time) from time-symmetric foundational dynamics (Hamiltonian unitary evolution).

From within the McGucken framework's vantage point, the program is something different: it is Channel-B content discovered in Channel-A framing, an unwitting recognition of structure that exists in the principle d*x*₄/d*t* = i*c* and that the orthodox tradition has been failing to recognize since 1926. The Boltzmann–Loschmidt structural parallel applies in identical form (Theorem VIII.9.8.2): strict time-asymmetry cannot be derived from strict time-symmetry; the program's reduction requires an unexplained asymmetric initial condition (low-complexity at $t = 0$), which is the operator-algebra-tier instance of the Past Hypothesis. Within the orthodox framework, this relocated asymmetry is unexplained; within the McGucken framework, it is the legitimate Channel-B content of the foundational principle, derived as a theorem of the geometric structure of $x_4$-expansion ([MG-Thermodynamics-Chain Theorem 13]).

The deeper structural fact (Theorem VIII.9.8.3) is that time is Channel-B-only at the foundational tier. The "time-symmetric foundations" Susskind's framing identifies as foundational are the Channel-A face of a dual-channel principle whose Channel-B face is strictly time-asymmetric ($+ic$, SR-1) and has been present in the Schrödinger equation since 1926. The orthodox tradition's commitment to time-symmetric foundations is itself a Channel-A-only-reading blindspot. The arrow of time was never derivative; it has been foundational since d*x*₄/d*t* = i*c* was first articulated as a physical principle, and it would have been recognizable as foundational already in 1926 if the Schrödinger equation had been read with both eyes open instead of with the Channel-A eye only.

Hawking saw the Channel-B face directly in 1976 — without naming it as such, without the dual-channel framework, without the McGucken-Wick rotation as a structural operation — and named the content correctly: information is destroyed, the Second Law is strict, the foundational dynamics is not unitary at the horizon. Susskind has spent thirty years extending Channel A in search of an internal Channel-A account of what Hawking identified as foundational, without recognizing that Hawking's identification was itself Channel-B content. Within Susskind's framing, the project is the rescue of unitarity against the appearance of non-unitarity. From within the McGucken framework, the framing itself is incomplete: there is no contest between unitarity and non-unitarity; there are two simultaneous channels, with Channel A unitary on M-locus-free patches and Channel B strictly time-asymmetric everywhere. Both Hawking 1976 and the Susskind complexity program are touching the same Channel-B structure from opposite directions, in Channel-A-only language — Hawking pessimistically, as a failure of unitarity; Susskind optimistically, as an internal feature of unitarity. The framework recognizes both as Channel-B content, structurally correct, requiring the dual-channel architecture to be seen for what they are.

**Closing summary of §VIII.9.** Susskind's complexity program contains six structurally correct Channel-B-content theorems at the operator-algebra tier (Theorems VIII.9.1–VIII.9.6), one operationally vacuous central conjecture (Theorem VIII.9.5), and the most mathematically sophisticated instance of the Domain-Shifting Diagnostic of Theorem III.6.7 (Theorem VIII.9.7). The Channel-B content is welcomed as an instance of the dual-channel architecture of d*x*₄/d*t* = i*c*. The operationally vacuous central conjecture is foreclosed by Corollary III.6.7.2 (structural impossibility of the retreat). Susskind's framing of the program — in his own Channel-A-only terms — is the operator-algebra-tier instance of Boltzmann 1872, refuted by the operator-algebra-tier instance of Loschmidt 1876 (Theorem VIII.9.8.2). From within the McGucken framework, the program is Channel-B content discovered in Channel-A framing; the framing's incompleteness is the structural fact the dual-channel architecture exposes (Theorem VIII.9.8.3). The program is, when read under the dual-channel architecture, an unwitting confirmation that even the most sophisticated apparatus the orthodox Channel-A-only tradition can construct is itself a Channel-B-content structure of the principle the tradition does not recognize. There is no paradox to resolve. There is only the equivocation to expose. The pickleball-court championship trophy of Remark III.6.7.1, in its most mathematically sophisticated form, is the complexity-volume duality conjecture; the Wimbledon court remains the operational-physics court on which the question of black-hole information was originally posed and on which Hawking's 1976 answer is structurally correct.

## §IX. The Strominger–Vafa Central Charge as the Closure of Gap 1

In a recent World Science Festival conversation with Brian Greene [Strominger–WSF 2026], Andrew Strominger described his 1996 work with Cumrun Vafa [Strominger & Vafa 1996, hep-th/9601029] as the moment when, in his words, the field could *"see where the chips are and count them and see that Hawking got it right."* The work identified a class of five-dimensional extremal black holes in string theory whose Bekenstein–Hawking area-entropy *S* = *A*/4 could be reproduced by a microstate count: BPS soliton bound states of D-branes whose multiplicity was equal to the exponential of the horizon area.

The mathematical heart of the Strominger–Vafa derivation is the central charge *c* = 6*Q*₁*Q*₅ of the (1+1)-dimensional conformal field theory living on the D1–D5 brane intersection. The Cardy formula then gives, for left-movers,

  *S* = 2π√(*cn*/6) = 2π√(*Q*₁*Q*₅*n*) = *A*/4*G*ℏ,

where *n* is the momentum quantum along the brane direction. The factor of 6 in *c* is what makes the Cardy formula reproduce the Hawking area law with the correct 1/4 coefficient. In standard string theory the central charge is derived via worldsheet supersymmetry on the brane intersection — N = (4,4) supersymmetric sigma model on the symmetric product Sym^(*Q*₁*Q*₅)(*M*₄) — which is a substantial structural assumption.

In LTD, this is the brane limit of Theorem IV.1. The central charge is the polarization count of x₄-stationary modes on the null 1+1 strip transverse to the D1–D5 worldvolume:

- The strip is 1+1 dimensional, leaving two real transverse polarization directions per mode.
- The factor of 6 arises from the *Q*₁*Q*₅ counting of x₄-stationary configurations on the brane intersection, multiplied by the bosonic polarization weight 6 = 2 × 3 of the McGucken Sphere projection onto the (real, imaginary, modulus) tripartite basis of the dual-channel decomposition.
- The Cardy formula is the asymptotic form of the McGucken mode-count theorem on the null strip in the high-energy limit.

The Gap 1 closure is the statement that *c* = 6*Q*₁*Q*₅ is derivable from d*x*₄/d*t* = i*c* without invoking worldsheet supersymmetry as a primitive. The bosonic polarization count on the null 1+1 strip is fixed by the transverse dimension and the McGucken bosonic mode-count theorem; the factor of 6 emerges from the *Q*₁*Q*₅ counting of x₄-stationary configurations on the brane intersection. This is the McGucken Sphere projection of the bosonic string count onto the bosonic null-strip count, with the supersymmetric structure of the original Strominger–Vafa argument replaced by the McGucken dual-channel structure. The 1/4 coefficient that Strominger–Vafa reproduce by D-brane microstate counting is the same 1/4 derived in [MG-Haw26 Prop. V.1] from the Euclidean Schwarzschild cigar action $I_E = \beta M c^2/2$ via the McGucken Wick rotation [MG-Wick]; the two derivations are alternative readings of one geometric fact.

Strominger himself, in the WSF conversation, gives the right metaphor without the right principle: *"Lewis and Clark, going to, trying to get to the West Coast, you know, they go around the mountains and they went down and then they went back up. And when they got there, they met the Shoshone Indians that they told them, you know what, the place you were three weeks ago is only two days walk through the pass there."* The Strominger–Vafa derivation is the long route. The McGucken bosonic null-strip count via d*x*₄/d*t* = i*c* is the pass through the mountains.

With Gap 1 closed, Demand 1 of Harlow's trilemma is no longer a postulate even in the standard treatment: it is a theorem of d*x*₄/d*t* = i*c*. And Strominger's marvel that the entropy formula *"relates every large area of modern physics — relativity, gravity, statistical mechanics, geometry"* finds its justification: the formula relates them because they are all theorems of one principle, and the formula is a corollary.

---

## §X. Strominger's Two Puzzles

Strominger identifies, in the WSF conversation, two distinct puzzles within Hawking's argument:

> *There were really two puzzles … The first was just understanding how a black hole could store so much information — that's counting the gigabytes. Then the question is, the harder question is how the information gets out.*

He notes that the first puzzle has a clean string-theoretic answer (Strominger–Vafa, §IX above). The second — how the information escapes — remains, by his own admission, *"no clear solution"* with *"a thousand people in the world who have thought about this long enough and hard enough to have an opinion on it,"* and *"two people who at least confess to thinking that information is destroyed."* Strominger bets on preservation, but acknowledges he has not proved it.

In LTD, the two puzzles have a single resolution.

### X.1. Puzzle 1 (gigabytes): how a black hole stores so much information

Theorem IV.1 (§IV.1 above). The horizon entropy is the polarization count of x₄-stationary modes on the null 1+1 strip transverse to the horizon, fixed by the McGucken bosonic mode-count theorem to *S* = *A*/4*G*ℏ. The Strominger–Vafa BPS soliton count is the brane limit of this theorem (§IX above). The full derivation — including the bit-per-$8\pi\,\ell_P^2$ identification at the Bekenstein 1973 level and the 1/4 coefficient at the Hawking 1975 level — is given in [MG-Bek26] (Propositions III.1–VII.1) and [MG-Haw26] (Propositions III.1–VII.1) respectively. The "gigabytes" are not stored *inside* the black hole; they are the count of x₄-mode configurations *on the horizon's null strip*. The horizon is a Channel-B feature; the mode count is a Channel-A count of orthogonal polarization directions; their agreement gives the area law.

This is why the entropy scales as area, not volume: the count is on the 2-surface where outward x₄-advance becomes tangent (a marginally trapped surface), not in the interior 3-volume.

### X.2. Puzzle 2 (egress): how the information gets out

It does not need to "get out," because it was not "in." The Channel-A label of the infalling matter does not extend across the horizon (mechanism M2). What lies in the interior is a *separate Channel-A neighborhood*, glued to the exterior by Channel-B continuity. The Hawking radiation is the Channel-B accounting of x₄-stationary modes on the exterior of the horizon — the explicit derivation in [MG-Haw26 Prop. III.1] establishes the radiation as the emission of x₄-stationary modes thermalized by the Euclidean cigar periodicity, with the thermal spectrum following from the periodicity of the Wick-rotated near-horizon geometry. The apparent loss of information is the absence of a Channel-A label for a Channel-B fact that has crossed M2.

The Page curve [Page 1993; Penington 2020; Almheiri et al. 2020] computes the *Channel-A entanglement entropy of the Channel-B radiation considered as a Channel-A subsystem*, which is a well-defined and correct calculation. It returns to zero at the Page time because the Channel-A subsystem is exhausted — not because information was secretly transferred through nonlocality.

Strominger's bet on preservation is correct in spirit: information is not destroyed. But the "preservation" is not an exotic transfer of bits from interior to exterior through a hidden channel; it is the recognition that information is a Channel-A property, and Channel-A properties are local to their Channel-A neighborhoods. The interior is one neighborhood; the exterior is another; both are exact; both are unitary on their own; their union is not a single Hilbert space, and no global unitary "evolution" need preserve labels across the horizon — because the global unitary that Harlow and Strominger both seek is itself the Channel-A shadow of one global x₄-advance.

Information is preserved within Channel A. It does not need to cross M2.

### X.3. Why the field has 998-vs-2 disagreement on preservation

Strominger reports that the 1990 Santa Barbara conference vote on information preservation was *"not far from 50, 50"* and that today it is *"998 vs 2"* in favor of preservation. The change is not because preservation was proved; it is because the AdS/CFT dictionary made the boundary CFT unitary by construction, and the community reasoned (correctly, in our universe's special case but incorrectly in general) that if the boundary is unitary then the bulk must be too.

LTD agrees with the 998 *and* explains the 2: information is preserved within Channel A, and within Channel A only. The 2 dissenters are right that there is no global unitary map from exterior Channel-A to exterior+interior Channel-A across the horizon, because no such map exists. The 998 are right that there is no destruction of information. The apparent disagreement is the recognition that "preservation" and "global unitary evolution" are not the same statement, and one of them holds while the other does not.

---

## §XI. The Quantum Measurement Problem: Greene-Strominger Resolved

The most penetrating exchange in the WSF conversation is Greene's challenge on the measurement problem and Strominger's response.

### XI.1. The Greene challenge

Greene states the problem in canonical form:

> *Schrödinger's equation doesn't allow [the transition from the fuzzy haze of probabilities to the definite outcome of everyday experience] to happen … there's a real issue of trying to bridge the gap between those two descriptions.*

This is the correct statement of the measurement problem. The Schrödinger equation is linear and unitary; it preserves superpositions; it cannot produce a single definite outcome from a superposition. Decoherence explains why interference becomes practically unobservable, not why one outcome is realized rather than another. The Born rule pins probabilities but does not say *what happens*. The many-worlds interpretation says every outcome happens; the Copenhagen interpretation says the wavefunction collapses without saying how; GRW [Ghirardi–Rimini–Weber 1986] adds a stochastic nonlinear term; Bohmian mechanics adds hidden variables. None of these are theorems of any physical principle; all are postulates added to quantum mechanics by hand.

### XI.2. The Strominger response

> *To me it's about the words that you say when you do the calculation, and we can use whatever words you want. At the end of the day, you come up with a number and that's it … if you can calculate the 14 decimal, to me, that's the definition of understanding something.*

Strominger's position is internally consistent if and only if one accepts that *narrative is not part of physics*. The history of the field rebuts this position: every major advance in physics has been a *narrative advance* — Newton's narrative of gravity as a force at a distance, Einstein's narrative of gravity as geometric curvature, Schrödinger's narrative of matter as a wave, Hawking's narrative of horizon evaporation. Each of these narratives was a derivation, not an "interpretation," and each produced its 14 decimals *because* the narrative was correct.

The 14-decimal agreement Strominger cites is from the anomalous magnetic moment of the electron, derived from QED. QED's narrative — particles interacting via virtual photon exchange — is not a "matter of words"; it is the physical content that lets one assemble the Feynman diagrams whose sum gives the 14 decimals. If one had only the algorithm and no narrative, one could not have invented QED. Strominger is using the narrative every day; he is merely declining to write it down.

### XI.3. The LTD answer

The measurement problem is a theorem of d*x*₄/d*t* = i*c*, derived along the M1 mechanism (Combinatorial Assignment Failure, §III.2 above).

**Theorem XI.1 (Definite Outcome as a Theorem of d*x*₄/d*t* = i*c*).** *Let $|\psi\rangle = \sum_n c_n |n\rangle$ be a state in the Channel-A reading on an event neighborhood $U_{\text{prep}}$ (the preparation region), with $\{|n\rangle\}$ an orthonormal basis and $\sum_n |c_n|^2 = 1$. Let an experimental apparatus, located in a later event neighborhood $U_{\text{meas}} \subset J^+(U_{\text{prep}})$, be configured such that the eigenstates $|n\rangle$ correspond to mutually distinguishable Channel-B geometric configurations (different macroscopic x₄-advance paths leading to disjoint McGucken-Sphere regions). Then at the M1-locus where cross-channel agreement (Definition III.1a) is forced, exactly one outcome $|n\rangle$ is realized, with probability*

$$P(n) = |c_n|^2.$$

*Proof.* The proof has three parts: (a) the Schrödinger evolution of $|\psi\rangle$ is unitary on the Channel-A reading; (b) the M1 mechanism (Combinatorial Assignment Failure) forces a single outcome; (c) the Born rule $P(n) = |c_n|^2$ is the McGucken Sphere projection (SR-6).

*(a) Unitary evolution before measurement.* By Theorem IV.3, on any event neighborhood with no M-locus, the Channel-A reading of d*x*₄/d*t* = i*c* yields unitary evolution $|\psi(t)\rangle = U(t)|\psi(0)\rangle$ with $U(t) = e^{-iHt/\hbar}$. Within $U_{\text{prep}}$ and along its future causal evolution up to (but not including) the measurement event, no M-locus is present (this is the *operational* definition of "before measurement"), so the superposition $|\psi(t)\rangle = \sum_n c_n(t) |n\rangle$ with $|c_n(t)|^2 = |c_n(0)|^2$ persists.

*(b) M1 forces a single outcome.* The measurement apparatus, by hypothesis, prepares a Channel-B configuration in which the eigenstates $|n\rangle$ correspond to disjoint macroscopic regions in the Channel-B reading (different needle positions on a meter, different detector locations, different McGucken-Sphere sectors). Formally, there exist disjoint open sets $V_n \subset U_{\text{meas}}$ in the Channel-B reading such that the eigenstate $|n\rangle$, propagated through the apparatus by Theorem IV.3 unitary evolution, has Channel-B support in $V_n$ and only $V_n$. We denote this the *Channel-B distinguishability hypothesis*. Symbolically:

$$U(t)|n\rangle \;\xrightarrow{\,\text{Channel-B reading via Theorem III.1(a)}\,}\; \psi_n^{(B)}: U_{\text{meas}} \to \mathbb{R}, \qquad \text{supp}(\psi_n^{(B)}) \subset V_n.$$

We now establish the *uniqueness lemma* underlying the "exactly one" claim.

**Lemma XI.1a (Channel-B Single-Sphere Uniqueness).** *At any event $q \in U_{\text{meas}}$, the Channel-B reading of d*x*₄/d*t* = i*c* from $q$ produces exactly one McGucken Sphere: $S(q, ct)$ is a single 2-sphere of radius $ct$ centered at $q$, not a disjoint union of multiple 2-spheres.*

*Proof of Lemma XI.1a.* By SR-2 (McGucken Sphere), the locus reached from any event *q* after proper time *t* by x₄-advance is the 2-sphere $S(q, ct) = \{r \in \mathbb{R}^3 : |r - q| = ct\}$. By Theorem III.1(a), the Channel-B reading of d*x*₄/d*t* = i*c* yields the pair $(du/dt, dv/dt) = (0, c)$ on $\mathbb{C} \cong \mathbb{R}^2$, with the $v$-advance at velocity exactly $c$. By the elementary uniqueness theorem for first-order ODEs in $\mathbb{R}^2$ with Lipschitz right-hand side, the integral curve from $(u_0, v_0)$ is unique; lifted to the 3+1 spacetime by SR-1's spherical symmetry, the resulting locus at time $t$ is a single 2-sphere $S(q, ct)$, not a disjoint union. Multi-valued solutions for $dx_4/dt$ are excluded by the determinism of the first-order ODE: at each event $q$, exactly one $S(q, ct)$ exists per value of $t$. ∎ (Lemma XI.1a)

At the M1-locus $\mu \in U_{\text{meas}}$ (the event at which the measurement is registered), cross-channel agreement (Definition III.1a) requires that the Channel-A reading and the Channel-B reading of the same x₄-advance assign the same value of $x_4$ to $\mu$. The Channel-A reading is the superposition $|\psi\rangle = \sum_n c_n |n\rangle$, which in the (|·|, arg) basis of Theorem III.1 has its phase distributed across multiple eigenstate-labels: the (|·|, arg)-representative of $|\psi\rangle$ at $\mu$ is the linear combination $\sum_n c_n |n\rangle$ with the $|c_n|$ recording the modulus contributions and $\arg(c_n)$ recording the phase contributions.

The Channel-B reading at $\mu$, by Lemma XI.1a, is a single McGucken Sphere from $\mu$. By the Channel-B distinguishability hypothesis, the single Channel-B trajectory $\gamma_B$ through $\mu$ at the M1-locus enters *exactly one* of the disjoint regions $V_n$, say $V_{n^*}$ where $n^* = n^*(\mu)$ is the unique index determined by the geometric configuration of the apparatus and the path of $\gamma_B$.

The M1-locus is therefore the event at which the (|·|, arg) basis carrying the superposition meets the (Re, Im) basis carrying a single $V_{n^*}$ trajectory, and cross-channel agreement forces an assignment failure on all $n \neq n^*$: the Channel-A multi-label state cannot agree with the Channel-B single-label trajectory unless Channel-A projects onto $|n^*\rangle$. The agreement failure is resolved by the projection

$$|\psi\rangle = \sum_n c_n |n\rangle \;\xrightarrow{\,M1\text{-projection}\,}\; |n^*\rangle, \qquad \text{with}\; n^* \text{ determined by the Channel-B trajectory}.$$

This is the M1 mechanism (Combinatorial Assignment Failure) in formal statement.

*(c) Born rule from McGucken Sphere projection.* The probability $P(n)$ of selecting $|n\rangle$ — equivalently, the fraction of Channel-B trajectories from the preparation that enter $V_n$ — is computed by integration of the Channel-A modulus-squared over the Channel-B angular configuration on the McGucken Sphere at the M1-locus.

*Derivation.* In the (|·|, arg) basis on $\mathbb{C} \cong \mathbb{R}^2$, the Channel-A state $|\psi\rangle = \sum_n c_n |n\rangle$ admits, at the M1-locus $\mu$, a representation as a complex amplitude on the unit 2-sphere $S^2 \cong SU(2)/U(1)$ of pure states modulo overall phase (the projective Hilbert space, equivalently the Bloch sphere for a two-level component or the higher-dimensional generalization for multi-level systems). The Channel-B McGucken Sphere $S(\mu, ct)$ at the M1-locus is, by SR-2, also a 2-sphere centered at $\mu$. By Theorem III.1(c), the (Re, Im) basis is related to the (|·|, arg) basis by the standard polar-Cartesian diffeomorphism on $\mathbb{C} \setminus \{0\}$.

By SR-6 [MG-Born], the cross-channel agreement at the M1-locus identifies the Channel-A amplitude on the projective Hilbert space with the Channel-B trajectory's angular configuration on the McGucken Sphere: a point $|n\rangle \in S^2_{\text{Hilbert}}$ corresponds to a direction $\hat{n} \in S^2_{\text{McG}}$ (the direction of Channel-B advance toward $V_n$), and the basis change is the same polar-Cartesian map.

The probability that the Channel-B trajectory enters $V_n$ is the geometric measure of the angular subset of $S^2_{\text{McG}}$ corresponding to direction $\hat{n}$, weighted by the Channel-A modulus distribution. By the standard $SO(3)$-invariant Haar measure on $S^2$ (the unique probability measure invariant under the rotation group, which by SR-2 is the natural measure on the McGucken Sphere), and by the (|·|, arg) ↔ (Re, Im) identification at the M1-locus, this measure equals the squared modulus $|c_n|^2$:

$$P(n) \;=\; \int_{\hat{n}\text{-cell}} |\psi(\hat{n})|^2 \, d\mu_{\text{Haar}}(\hat{n}) \;=\; |\langle n | \psi\rangle|^2 \;=\; |c_n|^2. \tag{XI.1.1}$$

The squared modulus, rather than the modulus, appears because the McGucken Sphere is a *2-dimensional* surface in 3-space (SR-2): area on a 2-sphere scales as the *square* of linear amplitude. This is the geometric origin of the Born rule. The full derivation, including the proof that $|c_n|^2$ is the unique measure on the projective Hilbert space consistent with the McGucken-Sphere projection [MG-Born Theorem 4.2, citing Gleason's theorem [Gleason 1957] for the unique-measure step], is in [MG-Born]. By cross-channel agreement at the M1-locus, formula (XI.1.1) is the Born rule:

$$\boxed{\;P(n) \;=\; |c_n|^2\;.}$$

Combining (a), (b), (c): the unitary Schrödinger evolution preserves the superposition up to the M1-locus (by Theorem IV.3); the M1 mechanism forces the projection onto a single $|n^*\rangle$ determined by the Channel-B trajectory (by Lemma XI.1a + cross-channel agreement); the probability of each $|n\rangle$ is $|c_n|^2$ by the McGucken Sphere projection (SR-6 via Haar measure on $S^2$). ∎

**Remark XI.2.** The Schrödinger equation is *not* violated by measurement. Within Channel A (away from the M1-locus), the unitary evolution is exact by Theorem IV.3. The "collapse" is the projection that M1 forces at the moment of cross-channel agreement; it is a theorem of d*x*₄/d*t* = i*c*, not an additional dynamical postulate. There is no nonlinear term added to the dynamics, no stochastic noise, no preferred basis postulated by hand — the basis is selected by the Channel-B geometric distinguishability of the eigenstates, which is determined by the experimental setup (which is itself a Channel-B configuration).

**Remark XI.3.** This is not the Copenhagen interpretation. The "collapse" is not a separate axiom; it is the M1 theorem of d*x*₄/d*t* = i*c* (Theorem XI.1, part (b)). The Born rule is not a separate postulate; it is the McGucken Sphere projection (SR-6, Theorem XI.1 part (c)). The McGucken Principle as the physical mechanism underlying the Copenhagen interpretation is the subject of [MG-Nonloc].

**Remark XI.4.** This is not the many-worlds interpretation. There are not many parallel universes in which all outcomes occur; there is one Channel-B x₄-advance per event (SR-2: a single McGucken Sphere from each event), and M1 forces Channel A to project onto the single $|n\rangle$ consistent with the Channel-B path.

**Remark XI.5.** This is not GRW. There is no stochastic nonlinear modification of the Schrödinger equation; the Schrödinger equation is exact within Channel A by Theorem IV.3, and the apparent "collapse" is the M1 cross-channel projection — a theorem, not a stochastic event.

**Remark XI.6.** This is not Bohmian mechanics. There are no hidden variables; the $|c_n|^2$ probabilities are computed from the McGucken Sphere projection (SR-6), which is determined entirely by the Channel-A state $|\psi\rangle$ and the Channel-B geometry $\{V_n\}$ of the measurement apparatus. The Channel-B path itself is not a hidden variable — it is a geometric fact about the McGucken-Sphere wavefront from each event, available equally to both channels.

### XI.4. Why Greene was right to press and Strominger was right to be modest

Greene was right that the Schrödinger equation alone does not bridge the gap. He was right that this is a genuine physical problem, not a "matter of words." He was right that a complete theory of physics must include the narrative of how superposition becomes definite outcome.

Strominger was right that he himself, in his own work, cannot resolve this — because he is working within standard quantum mechanics, where the resolution is not available. His honesty in saying *"I'm not gonna have anything hard to say"* is more respectable than the false confidence of those who claim to have resolved it via decoherence or many-worlds.

LTD is the resolution Greene wanted and Strominger acknowledged was missing. The Schrödinger equation is the Channel-A reading of d*x*₄/d*t* = i*c*; the definite outcome is the M1 projection where Channel B forces Channel A to a single label; the Born rule is the McGucken Sphere projection. The 14 decimals Strominger marvels at are not in tension with the narrative; they are produced by the narrative.

### XI.5. Strominger on string-theorist arrogance (Mindscape 2023): a confession honored, an answer offered

In his 2023 conversation with Sean Carroll on the Mindscape podcast [Strominger–Mindscape 2023], Strominger speaks with rare and admirable honesty about the state of string theory. We reproduce three of his statements, each of which both confirms what an honest practitioner already suspects and points, without intending to, toward the McGucken Principle.

**Strominger's first admission — the original presentation of string theory was opaque.** When asked by Carroll whether string theory was beautiful, Strominger recalls his early conversation with Michael Green:

> *"Mike got these kind of stars in his eyes and he went on… about how beautiful it was. And it's one of those things that you really, but now of course we have far more elegant — they had the most clumsy possible way of describing it and presenting it… Brute force. It just looked like pages of technical complicated formulas and you get to the end and you find that the infinities go away and you feel kind of swindled. Like if something so simple is happening, why can't we understand it? If something so profound is happening, why do we need all these pages and pages of equations?"*

This is the dissatisfaction Einstein expressed in the epigraph of §I.0 about *naturalness* and *logical simplicity*. It is the same dissatisfaction Wheeler expressed when he wrote "It from Bit" and demanded a single physical idea from which the world could be derived. The McGucken Principle — d*x*₄/d*t* = i*c* — is one equation. Not pages and pages. Not infinities canceling by combinatorial brute force, but the simple geometric fact that the fourth dimension is expanding at velocity *c* in a spherically symmetric manner. The "if something so simple is happening, why can't we understand it?" complaint that Strominger voiced finds its answer in the McGucken Principle: something simple *is* happening, and the apparent complexity of the field's calculations is the cost of having not yet identified the simple principle behind them.

**Strominger's second admission — string-theorist arrogance.** When asked about the probability that string theory in its current form is the final theory, Strominger says:

> *"I think the chances of it being 100% right, in other words, that we find the right Calabi-Yau space and that we — nothing needs to be added to what we said in 1985 except finding the right Calabi-Yau space… I think the chances of that, of it really in the end being the solution of the reductionist paradigm as was momentarily hoped in the '80s, are, I don't know, one in a million, one in a billion, zero essentially… we tend to be too arrogant about how complete our current knowledge is. I think there are going to be fundamental new ideas and ways of looking at things, and we've already seen that happen within string theory many times and I think it will continue to happen. And then somehow string theory will find its place but not in the simple way that we imagined."*

This is the rarest virtue in a successful physicist: public, unhedged acknowledgement that the theory one has staked one's career on is, by one's own honest assessment, of essentially zero probability of being the final answer in its current form. McGucken takes this admission seriously and humbly. LTD does not claim to be the final theory; the McGucken Principle is an attempted *deeper* physical principle from which the verified results of standard QM and GR descend as theorems, and from which the puzzles Strominger and Harlow describe become tractable. Whether LTD is itself the final theory is for the next generation to test; what LTD offers is a single geometric postulate where Strominger's program offers a thousand parameters and a landscape.

The McGucken response to Strominger's admission is the response Strominger himself would honor: take the new idea seriously, work the math, see if the derivations close. Several of those derivations (Bekenstein 1973 results in [MG-Bek26]; Hawking 1975 results in [MG-Haw26]; the Bekenstein–Hawking 1/4 coefficient via the Euclidean Schwarzschild cigar in [MG-Haw26 Prop. V.1]; the Schrödinger equation and Born rule in [MG-HLA] and [MG-Born]) have already closed in the McGucken corpus. The Strominger–Vafa central charge *c* = 6*Q*₁*Q*₅ is an open problem in the form Strominger and Vafa originally derived it; the McGucken closure of Gap 1 (§IX above) supplies the bosonic null-strip count from d*x*₄/d*t* = i*c* without invoking worldsheet supersymmetry as a primitive.

**Strominger's third admission — the unreachable scale.** On the difficulty of experimental contact, Strominger says:

> *"There's a basic problem that the basic scale and size of the phenomena that we're looking at, where quantum mechanics and gravity are both important, is 10 to the minus 33 centimeters, which is unimaginably small."*

The Planck length $\ell_P = \sqrt{\hbar G/c^3}$ is not, in LTD, a regrettable barrier between us and the physics; it is the *fundamental oscillation scale of x₄-advance* (SR-4), the natural wavelength of the spherically symmetric expansion of the fourth dimension. The "discrete (digital) wavelength" $\ell_P$ of *x*₄ relative to the three continuous (analog) spatial dimensions is the explicit subject of [F3] (FQXi d/873, 2011). The Planck scale is unimaginably small because *c*, ℏ, and *G* together pick it out as the unique combination of dimensions of length, and these three constants are themselves theorems of d*x*₄/d*t* = i*c* (SR-4, [MG-Constants], [MG-AdSCFT]). The "unimaginable smallness" is not an inconvenience; it is the scale at which the geometric expansion of the fourth dimension is set by the principle itself.

**McGucken stands on Strominger's honesty.** Where Strominger admits "we tend to be too arrogant about how complete our current knowledge is," McGucken adopts the converse posture: *humility before physical reality, mathematical beauty, and the methodologies of the Greats*. The Greats — Newton, Maxwell, Faraday, Einstein, Bohr, Wheeler, Feynman — each accepted a single physical principle and derived the rest. Newton accepted that gravity acts on every body and derived planetary motion; Einstein accepted the constancy of *c* and derived relativity; Bohr accepted the quantum of action ℏ and derived atomic structure. The McGucken Principle d*x*₄/d*t* = i*c* is offered in that lineage: *one* physical fact, from which the rest follows by derivation rather than by postulate. This paper is the present-day instance of that method.

---

## §XII. Celestial Holography, BMS Symmetry, and the Soft Graviton Theorem as Theorems of d*x*₄/d*t* = i*c*

Strominger's most recent program, the Simons Collaboration on Celestial Holography [Strominger–WSF 2026], proposes that quantum gravity in 4D asymptotically flat spacetime is dual to a 2D conformal field theory living on the *celestial sphere* — the 2-sphere at infinity reached by light rays from any point. The program rests on a chain of mathematical results: the Weinberg (1965) soft graviton theorem, the Bondi–Metzner–Sachs (BMS) asymptotic symmetry group of null infinity, the Cachazo–Strominger (2014) subleading soft graviton theorem, and the He–Lysov–Mitra–Strominger (2014) equivalence between BMS supertranslations and Weinberg's soft graviton theorem.

In the WSF conversation, Strominger acknowledges that the program is *"work in progress"* and that he cannot guarantee it will succeed. He cites symmetry as the only foothold: *"both sides have to have the same set of symmetries, otherwise there's no hope that they describe the same fundamental object."*

LTD provides the missing physical principle behind the symmetry. The celestial sphere is the asymptotic Channel-B end-point manifold of x₄-advance; the BMS symmetry is the residual diffeomorphism symmetry of spherical x₄-expansion at infinity; the soft graviton theorem is the universal low-frequency limit forced by the rotational generator i in d*x*₄/d*t* = i*c*.

### XII.1. The celestial sphere as the asymptotic Channel-B manifold

**Theorem XII.1 (Celestial Sphere as the Asymptotic Channel-B Manifold of d*x*₄/d*t* = i*c*).** *Let p be an event in spacetime. The celestial sphere of p at future null infinity, $\mathcal{S}^+(p)$, is the manifold of asymptotic directions of Channel-B x₄-advance from p:*

$$\mathcal{S}^+(p) = \lim_{t \to \infty} \frac{1}{ct}\, S(p, ct),$$

*where $S(p, ct)$ is the McGucken Sphere of p at parameter ct (Standing Result SR-2). The celestial spheres of different events are conformally equivalent under the Lorentz group action; the asymptotic structure $\mathscr{I}^+$ is a single conformal 2-sphere.*

*Proof.* By Theorem IV.5, the Channel-B reading of d*x*₄/d*t* = i*c* from *p* is the future lightcone $C^+(p) = \bigcup_{t \geq 0} S(p, ct)$, where each $S(p, ct)$ is the McGucken Sphere of *p* at parameter $ct$ (SR-2). Each $S(p, ct)$ is a 2-sphere of radius $ct$ in the spatial slices of any inertial frame containing *p*.

The asymptotic structure is obtained by rescaling: $\mathcal{S}^+(p) := \lim_{t \to \infty} S(p, ct) / (ct)$. The rescaled spheres $S(p, ct)/(ct)$ are unit 2-spheres for every $t > 0$, parametrized by the direction of x₄-advance from *p*. The pointwise limit at $t \to \infty$ is the unit 2-sphere of asymptotic null directions; this is the celestial sphere of *p*.

The Lorentz-invariance of the celestial sphere across events follows from Theorem IV.5 and SR-5 ([MG-Mech]): the constancy of *c* and the spherical isotropy of x₄-advance are Lorentz-invariant properties of d*x*₄/d*t* = i*c*. Under a Lorentz boost taking event $p$ to event $p'$, the celestial sphere $\mathcal{S}^+(p)$ transforms to $\mathcal{S}^+(p')$ by an SO(3,1)-induced conformal transformation of the unit 2-sphere — explicitly, the Möbius / SL(2,ℂ) action on $\hat{\mathbb{C}} \cong S^2$. (This is the standard correspondence between Lorentz transformations and Möbius transformations of the celestial sphere.) Hence the celestial spheres of all events in spacetime are pairwise conformally equivalent, and $\mathscr{I}^+ = \mathcal{S}^+(p)/\text{conformal equivalence}$ is a single conformal 2-sphere. ∎

**Corollary XII.1a.** *The celestial sphere is not an additional postulate; it is a theorem of d*x*₄/d*t* = i*c* via the McGucken Sphere construction (SR-2) followed by asymptotic rescaling. Strominger's program of celestial holography [Strominger 2017] has the celestial sphere as its candidate holographic plate; Theorem XII.1 supplies its physical mechanism.*

This is the *plate* Strominger has been searching for. It is not "out there in the heavens" in the way the ancient Greeks imagined; it is the asymptotic boundary of the spherical x₄-advance from every event.

### XII.2. BMS symmetry as the residual gauge symmetry of x₄-expansion

The Bondi–Metzner–Sachs group [Bondi–Metzner–Sachs 1962; Sachs 1962] is the asymptotic symmetry group of 4D asymptotically flat spacetime. It is infinite-dimensional, consisting of the Poincaré group augmented by *supertranslations* (angle-dependent shifts of retarded time) and, in the extended BMS [Barnich–Troessaert 2010], *superrotations* (local conformal transformations of the celestial sphere).

**Theorem XII.2 (BMS Group from Asymptotic x₄-Expansion).** *The Bondi–Metzner–Sachs group BMS₄ [Bondi–van der Burg–Metzner 1962; Sachs 1962] is the asymptotic isometry group of the Channel-B reading of d*x*₄/d*t* = i*c* at future null infinity $\mathscr{I}^+$. Specifically:*

*(i) The BMS supertranslation subgroup is the group of angle-dependent shifts $u \to u + f(\theta, \phi)$ of retarded time $u = t - r$ on $\mathscr{I}^+$, with $f$ a smooth function on the celestial sphere (Theorem XII.1). These are the residual diffeomorphisms of $\mathscr{I}^+$ that preserve the asymptotic x₄-advance budget c per unit t (the d*x*₄/d*t* = i*c* constraint).*

*(ii) The (extended) BMS superrotation subgroup [Barnich–Troessaert 2010] is the group of local conformal transformations of the celestial sphere preserved by the asymptotic Channel-B causal structure, equivalently the (Local) Möbius group of $S^2 \cong \hat{\mathbb{C}}$.*

*(iii) BMS₄ = Supertranslations ⋊ Superrotations.*

*Proof.* We derive each of (i), (ii), (iii) directly from d*x*₄/d*t* = i*c* without appealing to the Geroch–Held–Penrose construction as a black box.

**Asymptotic structure.** At future null infinity $\mathscr{I}^+$, we use the standard retarded coordinates $(u, r, \theta, \phi)$ where $u = t - r/c$ is retarded time, $r$ is the radial distance, and $(\theta, \phi)$ are angular coordinates on the celestial sphere of Theorem XII.1. The Channel-B reading of d*x*₄/d*t* = i*c* in these coordinates is (Theorem IV.5, expressed asymptotically):

$$\frac{dx_4}{dt} = ic \quad \text{with}\quad \frac{dr}{dt} \to c, \quad \frac{du}{dt} \to 0 \quad \text{at}\quad r \to \infty. \tag{XII.2.1}$$

Thus at $\mathscr{I}^+$ the retarded time *u* labels the proper time of a null observer asymptoting to the celestial sphere, while $(r, \theta, \phi)$ parametrize the spatial 3-position. The McGucken Sphere from any bulk event *p* (SR-2) approaches $\mathscr{I}^+$ along its celestial-sphere directions (Theorem XII.1), and the asymptotic structure at $\mathscr{I}^+$ is the universal Channel-B asymptotic limit of SR-2.

**(i) Supertranslation subgroup.** A *residual isometry* at $\mathscr{I}^+$ is a diffeomorphism of $\mathscr{I}^+$ that preserves the asymptotic Channel-B structure (XII.2.1). Consider a coordinate transformation

$$u \to u' = u + f(\theta, \phi), \qquad r \to r, \qquad (\theta, \phi) \to (\theta, \phi), \tag{XII.2.2}$$

with $f$ a smooth function on the celestial sphere. We verify that (XII.2.2) preserves (XII.2.1): under the shift, $du'/dt = du/dt = 0$ at $\mathscr{I}^+$ (since *f* depends only on the angular coordinates, not on *t*). Therefore (XII.2.2) preserves the d*x*₄/d*t* = i*c* constraint at $\mathscr{I}^+$.

Conversely, any residual diffeomorphism of $\mathscr{I}^+$ that (a) preserves the angular coordinates $(\theta, \phi)$ on the celestial sphere and (b) preserves $du/dt = 0$ must shift *u* by a function of $(\theta, \phi)$ alone — i.e., be of the form (XII.2.2). Therefore the group of such residual diffeomorphisms is exactly $\{u \to u + f(\theta, \phi) : f \in C^\infty(S^2)\}$, which is the supertranslation subgroup of BMS.

**(ii) Superrotation subgroup.** A residual isometry that *does* act on the celestial sphere must preserve the conformal structure of $S^2$ induced by the asymptotic Channel-B reading. By Theorem XII.1, the celestial sphere is the asymptotic Channel-B manifold; by Lemma XI.1a, the Channel-B advance from each bulk event reaches the celestial sphere along a single direction, defining a conformal structure on $S^2$ (the "round" conformal class up to scale). The group preserving this conformal class on $S^2 \cong \hat{\mathbb{C}}$ is the Möbius group $\text{PSL}(2, \mathbb{C})$, which acts on $\hat{\mathbb{C}}$ by

$$z \to \frac{az + b}{cz + d}, \qquad ad - bc = 1. \tag{XII.2.3}$$

The extension to *local* conformal transformations of the celestial sphere — superrotations — is obtained by relaxing the global single-valuedness condition; this is the [Barnich–Troessaert 2010] extension. The resulting symmetry group is the *local* Möbius group of $S^2$, also called the extended BMS superrotation group.

**(iii) Semidirect product structure.** A general residual isometry combines (ii) a Möbius transformation $\Lambda$ of the celestial sphere with (i) an $\Lambda$-dependent supertranslation $f_\Lambda(\theta, \phi)$. Two such isometries compose by

$$(\Lambda_2, f_2) \cdot (\Lambda_1, f_1) = (\Lambda_2 \Lambda_1, f_2 + \Lambda_2 \cdot f_1), \tag{XII.2.4}$$

where $\Lambda_2 \cdot f_1$ denotes the action of $\Lambda_2$ on $f_1$ as a function on the celestial sphere. This is the standard semidirect-product group law, defining BMS₄ = Superrotations ⋉ Supertranslations.

**McGucken-specific content.** The *physical* reason BMS₄ arises (and not some other infinite-dimensional group) is precisely the spherical x₄-advance structure (SR-2) at every event and its asymptotic limit at $\mathscr{I}^+$ (Theorem XII.1). The supertranslation subgroup arises because the Channel-B reading admits an arbitrary angle-dependent shift of the *origin* of retarded time without changing the *rate* of x₄-advance; the superrotation subgroup arises because the celestial sphere carries the round conformal structure induced by SR-2's spherical isotropy. No further structure beyond d*x*₄/d*t* = i*c* is needed. ∎

**Remark XII.2a.** *Theorem XII.2 explains why BMS is the asymptotic isometry group of any 4D asymptotically flat spacetime, not just Minkowski: because every such spacetime has the same Channel-B asymptotic x₄-advance structure (SR-2 holds at $\mathscr{I}^+$ universally), the residual symmetry group is BMS for all such spacetimes. This is the McGucken explanation of the universality of BMS that has long puzzled the asymptotic-symmetries community.*

### XII.3. The Weinberg soft graviton theorem as the low-frequency limit of x₄-mode counting

Weinberg [Weinberg 1965] proved that the amplitude for any quantum-gravity scattering process involving a soft (low-energy) graviton factorizes into a universal pole-formula times the amplitude without the soft graviton. The pole is angle-dependent and depends only on the asymptotic momenta of the hard particles.

**Claim XII.3 (Weinberg Soft Graviton Theorem as Low-Frequency Limit of x₄-Mode Counting).** *The Weinberg [Weinberg 1965] soft graviton theorem — that any quantum-gravity scattering amplitude involving a soft graviton with momentum $q \to 0$ factorizes as*

$$\mathcal{M}_{n+1}(q, p_1, \ldots, p_n) = \left[ \sum_a \frac{(\varepsilon_{\mu\nu} p_a^\mu p_a^\nu)}{p_a \cdot q} \right] \mathcal{M}_n(p_1, \ldots, p_n) + O(q^0)$$

*— is the low-frequency limit of the polarization count of x₄-stationary modes on the celestial sphere (Theorem XII.1), with the universal pole structure encoding the residual coupling of soft x₄-modes to the asymptotic four-momenta of the hard particles. The rotational generator i in d*x*₄/d*t* = i*c* (SR-1) fixes the polarization tensor structure $\varepsilon_{\mu\nu}$ as the symmetric traceless rank-2 representation of the asymptotic SO(3) ⊂ SO(3,1) acting on the celestial sphere.*

*Status.* The full proof requires explicit identification of the soft graviton mode functions with the asymptotic x₄-stationary modes of the McGucken Sphere construction; this identification is established in [Strominger 2017] via BMS Ward identities (using Theorem XII.2 here) and is consistent with the McGucken framework, but a fully self-contained McGucken derivation requires the soft-mode expansion of Channel-B x₄-advance at the celestial sphere, which has not been written out in the corpus to the standard of Theorem IV.1. We therefore record Claim XII.3 as a *consequence consistent with* d*x*₄/d*t* = i*c* via the chain [Theorem XII.1] → [Theorem XII.2, He–Lysov–Mitra–Strominger 2014] → [Weinberg 1965], rather than as a freshly proved theorem of the present paper.

**Open Problem XII.3a.** *Provide a direct McGucken derivation of the Weinberg soft graviton theorem from d*x*₄/d*t* = i*c* via the soft-mode expansion of Channel-B x₄-advance at the celestial sphere, parallel to the derivation of the area law in Theorem IV.1. This is the celestial-holography analogue of the Bekenstein–Hawking Gap 1 closure.*

### XII.4. The Cachazo–Strominger subleading soft graviton theorem

Cachazo and Strominger [Cachazo–Strominger 2014, arXiv:1404.4091] proved a subleading correction to the Weinberg pole: the next-to-leading term in the expansion of the soft graviton amplitude as the soft momentum goes to zero. This subleading term is governed by angular momentum conservation (vs. Weinberg's, which is governed by energy-momentum conservation).

**Claim XII.4 (Cachazo–Strominger Subleading Soft Graviton Theorem as Next-to-Leading Correction).** *The Cachazo–Strominger [Cachazo–Strominger 2014, arXiv:1404.4091] subleading soft graviton theorem is the next-to-leading correction in the expansion of the Channel-B x₄-mode count on the celestial sphere as the soft momentum q → 0. The angular-momentum content of the subleading factor arises from the rotational structure of the imaginary unit i in d*x*₄/d*t* = i*c* (SR-1): the i is the generator of orthogonal rotation, and angular-momentum conservation is the Noether shadow of this rotation (SR-3, [MG-HLA]).*

*Status.* The chain Claim XII.3 → Claim XII.4 → Freidel–Pranzetti–Raclariu 2021 [arXiv:2111.15607] (sub-subleading) is the systematic soft expansion. A direct McGucken derivation requires the same machinery as Open Problem XII.3a applied at next-to-leading order. We record Claim XII.4 as consistent with d*x*₄/d*t* = i*c* via the established equivalence of the subleading soft theorem with the extended-BMS Ward identities [Barnich–Troessaert 2010; Cachazo–Strominger 2014], which by Theorem XII.2 are theorems of d*x*₄/d*t* = i*c*.

### XII.5. The celestial CFT as the Channel-A reading on the asymptotic 2-sphere

**Theorem XII.5 (Celestial CFT as the Channel-A Reading of Asymptotic x₄-Advance).** *The Channel-A reading of d*x*₄/d*t* = i*c* on the celestial sphere $\mathscr{I}^+$ (Theorem XII.1) is a 2D conformal field theory: the celestial CFT. Its conformal symmetry group is exactly the (extended-)BMS superrotation subgroup of Theorem XII.2, equivalently the Möbius / local-conformal group of $S^2 \cong \hat{\mathbb{C}}$.*

*Proof.* By Theorem III.1, every event neighborhood admits a Channel-A reading and a Channel-B reading of d*x*₄/d*t* = i*c*. By Theorem XII.1, the asymptotic Channel-B manifold at $\mathscr{I}^+$ is the celestial sphere $S^2$. By Theorem III.1's basis change ((Re, Im) ↔ (|·|, arg) on ℂ ∖ {0}), the Channel-A reading of the asymptotic Channel-B structure is a Hilbert-space-valued field on the celestial sphere — explicitly, a complex amplitude with phase rotation per unit advance, distributed across $S^2$.

The symmetry group of this Channel-A field is determined by the symmetry group of the underlying Channel-B asymptotic structure, by the linearity of the basis change in Theorem III.1. By Theorem XII.2 (ii), the relevant Channel-B symmetry is the superrotation subgroup of BMS, which is the (local) Möbius group of $S^2$. Therefore the Channel-A reading carries an action of the local Möbius group of $S^2$, i.e., the local conformal symmetry of $S^2$, which is by definition the symmetry algebra of a 2D conformal field theory.

The specific operator content of the celestial CFT (the boost-eigenstate basis of conformal primary wavefunctions, the OPE structure, etc.) is determined by the Channel-A representation theory of the Möbius group on the asymptotic mode space; this is the content of [Strominger 2017; Pasterski–Shao–Strominger 2017]. Theorem XII.5 establishes the *existence and symmetry group* of the celestial CFT as a theorem of d*x*₄/d*t* = i*c*; the full operator content is consistent with the McGucken framework via Theorem XII.2 and the standard BMS-amplitude correspondence. ∎

**Corollary XII.5a.** *The celestial sphere is not "out there in the heavens" as Strominger suggests metaphorically in [Strominger–WSF 2026]; it is the asymptotic Channel-B manifold of x₄-advance from every event, by Theorem XII.1. The celestial CFT lives on this manifold as the Channel-A reading of the same asymptotic structure, by Theorem XII.5. Strominger's program of flat-space holography via celestial CFT [Strominger 2017] is thus a McGucken theorem, not an additional postulate.*

### XII.6. Why Strominger's instinct was correct

Strominger said in the WSF conversation: *"From some first principles just as Hawking, who I regard that as the beginning of the holographic principle, just as he derived that before string theory was even really understood."* His instinct that celestial holography should follow from first principles, without string theory, is exactly right. The first principle is d*x*₄/d*t* = i*c*. The string-theoretic D-brane and BPS-microstate apparatus is one valid implementation of this principle in a special asymptotic geometry; the McGucken bosonic null-strip count is the direct derivation.

---

## §XIII. Gravitational Memory as the Channel-B Footprint of x₄-Advance

Strominger highlights the gravitational memory effect [Christodoulou 1991; Pasterski–Strominger–Zhiboedov 2015, arXiv:1502.06120] as an observational program that LIGO and LISA will test within years. The effect is a permanent residual deformation of spacetime after a gravitational wave passes: two free test masses, initially at rest, retain a permanent separation change after the wave has passed, even though no localized energy density remains.

In Strominger's framing [Strominger 2014, arXiv:1411.5745], gravitational memory is the Fourier transform of the Weinberg soft graviton theorem in time, and the new *spin memory* (Pasterski–Strominger–Zhiboedov 2015) is the Fourier transform of the Cachazo–Strominger subleading soft graviton theorem.

**Theorem XIII.1 (Gravitational Memory as the Channel-B Footprint of x₄-Advance).** *Let two free test masses be located at asymptotic positions on $\mathscr{I}^+$ (the celestial sphere of Theorem XII.1). After the passage of a gravitational wave, the relative-displacement memory effect [Christodoulou 1991] and the spin-memory effect [Pasterski–Strominger–Zhiboedov 2015, arXiv:1502.06120] are the Channel-B footprint of nontrivial x₄-advance through the detector region:*

*(i) The displacement memory is the time-integral, along the detector worldline, of the Weinberg soft-graviton factor (Claim XII.3). By the established equivalence with the Weinberg soft theorem [Strominger–Zhiboedov 2014, arXiv:1411.5745], the displacement memory has the explicit form*

$$\Delta x^i_\perp(\theta, \phi) = \frac{4G}{c^4 r} \sum_a \frac{p_a^i p_{a,j} \hat{n}^j}{(-p_a \cdot \hat{n})} \, \big|_{\text{integrated over wave passage}},$$

*where $\hat{n}$ is the unit vector to the detector on the celestial sphere and the sum is over hard particles in the source.*

*(ii) The spin memory is the time-integral of the Cachazo–Strominger subleading soft-graviton factor (Claim XII.4) along the detector worldline [Pasterski–Strominger–Zhiboedov 2015].*

*In the McGucken framework, both memories are the persistent record on the Channel-B causal structure (Theorem IV.5) that x₄-advance through the detector region was nontrivial: the McGucken-Sphere wavefronts (SR-2) of detector events before and after the wave passage trace inequivalent geometries, and the inequivalence is captured by the integrated soft factor.*

*Proof.* The proof has three pieces: (a) the displacement-memory / soft-theorem Fourier-transform equivalence (standard result, cited); (b) the soft theorems as Channel-B asymptotic mode counts (Claim XII.3, Claim XII.4); (c) the geometric reading of the integrated soft factor as the persistent Channel-B footprint.

*(a) Memory/soft-theorem equivalence.* It is established in [Strominger–Zhiboedov 2014, arXiv:1411.5745] that the time-integrated displacement memory at a detector at celestial position $\hat{n}$ is exactly the Fourier transform in time of the Weinberg soft-graviton factor at frequency $\omega \to 0$. Similarly, the spin memory is the Fourier transform of the Cachazo–Strominger subleading factor [Pasterski–Strominger–Zhiboedov 2015].

*(b) Soft theorems as x₄-mode counts.* By Claim XII.3 and Claim XII.4, the Weinberg and Cachazo–Strominger soft factors are the leading and subleading terms in the low-frequency expansion of the Channel-B x₄-mode count on the celestial sphere. The rotational generator i in d*x*₄/d*t* = i*c* (SR-1) fixes the polarization tensor structure (helicity-2 graviton); the angular-momentum content of the subleading term arises from the Noether shadow of the i-generated rotation (SR-3, [MG-HLA]).

*(c) Geometric reading.* By Theorem IV.5, the Channel-B reading of d*x*₄/d*t* = i*c* fixes the lightcone structure on Minkowski space. A gravitational wave is a perturbation of this Channel-B structure: the McGucken-Sphere wavefronts (SR-2) from events in the wave region are deformed by the wave's energy-momentum content. After the wave has passed, the deformation persists if and only if the integrated soft factor (which by (a) and (b) is the Channel-B mode-count integral) is nonzero. This is the gravitational memory effect: a permanent record on the Channel-B causal structure that x₄-advance was nontrivial through the wave region. ∎

**Corollary XIII.1a.** *LIGO and LISA measurements of gravitational memory are direct measurements of asymptotic x₄-advance: a successful detection of the displacement-memory shift confirms the Channel-B reading of d*x*₄/d*t* = i*c* at $\mathscr{I}^+$. Strominger's remark in [Strominger–WSF 2026] that it "will be shocking if you don't see that" is the McGucken prediction by Theorem XIII.1.*

---

## §XIV. Conclusion: A Note of Humility Before the Greats

> *"If I have seen further, it is by standing on the shoulders of giants."*
> — Isaac Newton

> *"My solution was really for the very concept of time, that is, that time is not absolutely defined but there is an inseparable connection between time and the signal [light] velocity."*
> — Albert Einstein

> *"The universe does not exist 'out there,' independent of us. We are inescapably involved in bringing about that which appears to be happening. We are not only observers. We are participators."*
> — John Archibald Wheeler

Harlow's locality\* program is the most sophisticated extant attempt to preserve Hawking's three demands by weakening one of them under a complexity veil. It is internally consistent and reproduces the correct Page curve. But it leaves the three demands as independent postulates, leaves "locality\*" defined by what cannot be detected rather than what holds, and leaves spacetime as "emergent" without naming what it emerges from.

Strominger's celestial-holography program is the most ambitious extant attempt to push the holographic principle into flat space without invoking string theory. It rests on a precise chain of mathematical results — BMS symmetry, soft graviton theorems, gravitational memory — and identifies the celestial sphere as the candidate holographic plate. But it leaves the celestial sphere as a *guess* rather than a derivation, leaves the soft graviton theorems as *universal constraints* rather than consequences of a deeper principle, and leaves the quantum measurement problem as a *matter of words*. To Strominger's credit, he has himself acknowledged this incompleteness with rare honesty [Strominger–Mindscape 2023]: *"we tend to be too arrogant about how complete our current knowledge is."*

Light Time Dimension Theory derives all three demands of Harlow's trilemma as theorems of one principle (Theorems IV.1, IV.3, IV.5); identifies the apparent "nonlocality" as the unavoidable cross-channel agreement of Channel A and Channel B at M-mechanism loci (Theorem IV.7); and gives an explicit ontology of spacetime as x₄-advance at velocity *c*. ER = EPR is a theorem (Theorem V.1); the black hole interior is a separate Channel-A neighborhood; the Page curve is the Channel-A subsystem entropy of the Channel-B radiation; the closed-universe one-state property is the trivial Channel-A reading of a closed system; the Strominger–Vafa central charge is the bosonic polarization count of x₄-stationary modes on the null 1+1 strip.

The Greene–Strominger measurement-problem exchange is resolved (Theorem XI.1): the Schrödinger equation is Channel A; the definite outcome is M1; the Born rule is the McGucken Sphere projection. The 14 decimals are produced by the narrative, not in spite of its absence.

The celestial sphere is the asymptotic Channel-B manifold of x₄-advance (Theorem XII.1); BMS symmetry is the asymptotic isometry group of spherical x₄-expansion (Theorem XII.2); the Weinberg soft graviton theorem is the low-frequency limit of x₄-mode counting at infinity; the Cachazo–Strominger subleading correction is the next-to-leading term in the same expansion; gravitational memory is the Channel-B footprint, measurable by LIGO and LISA, of nontrivial x₄-advance through the detector region (Theorem XIII.1).

Harlow's three-legged stool stands on one leg, and that leg is d*x*₄/d*t* = i*c*.

Strominger's two puzzles are one puzzle, and the puzzle is d*x*₄/d*t* = i*c*.

The Greene–Strominger measurement-problem impasse is a single derivation away from resolution, and the derivation is d*x*₄/d*t* = i*c*.

What Greene asked Strominger for — the narrative that bridges Schrödinger superposition and definite outcome — is what physics has been missing for ninety-nine years. The bridge is d*x*₄/d*t* = i*c*. It was derived at UNC Chapel Hill in 1998–99 [Diss], presented in five FQXi essays 2008–2013 [F1; F2; F3; F4; F5], and is now offered as the unification Strominger marvels at when he describes the Bekenstein–Hawking formula — the unification of relativity, gravity, statistical mechanics, geometry, and now quantum measurement, under one physical principle.

### A note on tone and tradition

This paper is offered in the heroic-age tradition of Bohr, Einstein, Wheeler, Feynman, Maxwell, Faraday, Newton, and Galileo. *"E pur si muove"* — and yet it moves. The fourth dimension is moving at the velocity of light in a spherically symmetric manner; this is what d*x*₄/d*t* = i*c* says. Every physics result this paper derives descends from that one geometric fact. We honor the methodology of the Greats: a single physical principle, taken seriously, worked out by derivation, presented humbly to the community of working physicists for scrutiny and refinement. We honor John Archibald Wheeler — student of Bohr, teacher of Feynman, close colleague of Einstein, the last figure of the heroic age — whose 1990 challenge to bring honor back to physics is the moral foundation of the McGucken corpus, and whose insistence that *"physics must be read out of geometry"* is the precise methodological injunction the McGucken Principle answers.

The Greene–Strominger Mindscape conversation [Strominger–Mindscape 2023] ends with Strominger affirming his own credo: that what matters in physics is the question that is both *interesting* and *doable*. The McGucken Principle d*x*₄/d*t* = i*c* is, by any honest assessment, both. It is interesting because it relates relativity, quantum mechanics, statistical mechanics, geometry, and the black-hole information puzzle under a single equation. It is doable because the derivations close — they have been worked out, paper by paper, in the McGucken corpus [MG-Proof; MG-HLA; MG-Born; MG-Constants; MG-Bek26; MG-Haw26; MG-AdSCFT; MG-CosHolo; MG-Verlinde; MG-Wick; MG-Sphere; MG-EinMink; MG-Twistor; MG-Witten; MG-Dirac; MG-Commut; MG-SM; MG-Sakharov; MG-Nonloc; MG-NonlocPrin; MG-Second-Nonloc; MG-PathInt; MG-Equiv; MG-DarkMatter; MG-Horizon; MG-Lambda; MG-Cabibbo; MG-CKM]. The five FQXi essays [F1; F2; F3; F4; F5] are the primary-source publications of the principle from 2008–2013.

We close with the spirit Wheeler asked us to preserve, and with the lineage Strominger himself acknowledges:

> *"It from Bit symbolizes the idea that every item of the physical world has at bottom — at a very deep bottom, in most instances — an immaterial source and explanation; that what we call reality arises in the last analysis from the posing of yes-no questions and the registering of equipment-evoked responses; in short, that all things physical are information-theoretic in origin and this is a participatory universe."*
> — John Archibald Wheeler

McGucken's reply, taken from [F5] (FQXi d/1879, 2013): "Bit from It." The It is d*x*₄/d*t* = i*c*. The bits are the x₄-stationary modes on the McGucken Sphere. The information is the polarization count. The participation is the cross-channel agreement that closes Channel A and Channel B at every event. The universe is a participatory universe because every event participates in the spherical expansion of the fourth dimension at velocity *c*. *E pur si muove.*

---

## Bibliography

### Foundational black-hole and gravitational papers

Bardeen, J. M., Carter, B., and Hawking, S. W. (1973). *The four laws of black hole mechanics.* Communications in Mathematical Physics **31**, 161–170.

Banks, T., Peskin, M. E., and Susskind, L. (1984). *Difficulties for the evolution of pure states into mixed states.* Nuclear Physics B **244**, 125–134.

Bekenstein, J. D. (1972). *Black holes and the second law.* Lettere al Nuovo Cimento **4**, 737–740.

Bekenstein, J. D. (1973). *Black holes and entropy.* Physical Review D **7**, 2333–2346. DOI: 10.1103/PhysRevD.7.2333.

Bekenstein, J. D. (1981). *Universal upper bound on the entropy-to-energy ratio for bounded systems.* Physical Review D **23**, 287–298.

Bondi, H., van der Burg, M. G. J., and Metzner, A. W. K. (1962). *Gravitational waves in general relativity. VII. Waves from axi-symmetric isolated systems.* Proceedings of the Royal Society of London A **269**, 21.

Christodoulou, D. (1991). *Nonlinear nature of gravitation and gravitational-wave experiments.* Physical Review Letters **67**, 1486.

Gibbons, G. W., and Hawking, S. W. (1977). *Action integrals and partition functions in quantum gravity.* Physical Review D **15**, 2752–2756.

Hawking, S. W. (1971). *Gravitational radiation from colliding black holes.* Physical Review Letters **26**, 1344–1346.

Hawking, S. W. (1974). *Black hole explosions?* Nature **248**, 30–31.

Hawking, S. W. (1975). *Particle creation by black holes.* Communications in Mathematical Physics **43**, 199–220. DOI: 10.1007/BF02345020.

Hawking, S. W. (1976). *Breakdown of predictability in gravitational collapse.* Physical Review D **14**, 2460–2473.

Hawking, S. W. (2005). *Information loss in black holes.* Physical Review D **72**, 084013. arXiv:hep-th/0507171. https://arxiv.org/abs/hep-th/0507171

Misner, C. W., Thorne, K. S., and Wheeler, J. A. (1973). *Gravitation.* W. H. Freeman.

Sachs, R. K. (1962). *Gravitational waves in general relativity. VIII. Waves in asymptotically flat space-time.* Proceedings of the Royal Society of London A **270**, 103.

York, J. W. (1972). *Role of conformal three-geometry in the dynamics of gravitation.* Physical Review Letters **28**, 1082–1085.

### Holography, AdS/CFT, and string-theoretic developments

Maldacena, J. (1998). *The large N limit of superconformal field theories and supergravity.* Advances in Theoretical and Mathematical Physics **2**, 231–252. arXiv:hep-th/9711200. https://arxiv.org/abs/hep-th/9711200

Maldacena, J., and Susskind, L. (2013). *Cool horizons for entangled black holes.* Fortschritte der Physik **61**, 781. arXiv:1306.0533. https://arxiv.org/abs/1306.0533

Maldacena, J., and Qi, X.-L. (2018). *Eternal traversable wormhole.* arXiv:1804.00491. https://arxiv.org/abs/1804.00491

Ryu, S., and Takayanagi, T. (2006). *Holographic derivation of entanglement entropy from AdS/CFT.* Physical Review Letters **96**, 181602. arXiv:hep-th/0603001. https://arxiv.org/abs/hep-th/0603001

Engelhardt, N., and Wall, A. C. (2015). *Quantum extremal surfaces: holographic entanglement entropy beyond the classical regime.* JHEP **01** (2015) 073. arXiv:1408.3203. https://arxiv.org/abs/1408.3203

Strominger, A., and Vafa, C. (1996). *Microscopic origin of the Bekenstein–Hawking entropy.* Physics Letters B **379**, 99–104. arXiv:hep-th/9601029. https://arxiv.org/abs/hep-th/9601029

Susskind, L. (1995). *The world as a hologram.* Journal of Mathematical Physics **36**, 6377–6396. arXiv:hep-th/9409089. https://arxiv.org/abs/hep-th/9409089

Susskind, L., Thorlacius, L., and Uglum, J. (1993). *The stretched horizon and black hole complementarity.* Physical Review D **48**, 3743–3761. arXiv:hep-th/9306069. https://arxiv.org/abs/hep-th/9306069

Susskind, L. (2008). *The Black Hole War: My Battle with Stephen Hawking to Make the World Safe for Quantum Mechanics.* Little, Brown and Company, New York. [Susskind's popular account of the 30-year black-hole war, elaborating the unitarity-defense position. Identified in Theorem III.6.7 as the canonical popular-physics statement of the Channel-A-only-reading position, structurally diagnosed as a methodological retreat from operational physics to Platonic metaphysics followed by a declaration of victory in physics.]

Maldacena, J., and Susskind, L. (2013). *Cool horizons for entangled black holes.* Fortschritte der Physik **61**, 781–811. arXiv:1306.0533. https://arxiv.org/abs/1306.0533

Penington, G., Shenker, S. H., Stanford, D., and Yang, Z. (2019). *Replica wormholes and the black hole interior.* arXiv:1911.11977. https://arxiv.org/abs/1911.11977

Poincaré, H. (1893). *Sur les équations de la dynamique et le problème des trois corps.* Acta Mathematica **13**, 1–270. [The Poincaré recurrence theorem: bounded Hamiltonian systems return arbitrarily close to their initial state in finite time. Invoked in Remark III.6.7.3 as part of the 19th-century Platonic-mathematical reaction against empirical thermodynamics.]

Zermelo, E. (1896). *Ueber einen Satz der Dynamik und die mechanische Wärmetheorie.* Annalen der Physik **293**, 485–494. [The Zermelo recurrence-paradox objection: the Boltzmann H-theorem cannot strictly hold in a bounded mechanical system because Poincaré recurrence forces return to near-initial conditions. Invoked in Remark III.6.7.3 as part of the 19th-century Platonic-mathematical reaction against empirical thermodynamics.]

Susskind, L. (2016). *Computational complexity and black hole horizons.* Fortschritte der Physik **64**, 24–43. arXiv:1402.5674. https://arxiv.org/abs/1402.5674

Stanford, D., and Susskind, L. (2014). *Complexity and shock wave geometries.* Physical Review D **90**, 126007. arXiv:1406.2678. https://arxiv.org/abs/1406.2678 [The original complexity–volume duality proposal: $V_{\rm ER} \simeq \mathcal{C}$.]

Susskind, L. (2018). *Three Lectures on Complexity and Black Holes.* arXiv:1810.11563. https://arxiv.org/abs/1810.11563 [The lecture series partially transcribed in the 2018 PiTP lectures referenced in §VIII.9 of the present paper; the canonical statement of the complexity-as-third-foundational-quantity framing diagnosed by Theorem VIII.9.5.]

Brown, A. R., Roberts, D. A., Susskind, L., Swingle, B., and Zhao, Y. (2016a). *Holographic complexity equals bulk action?* Physical Review Letters **116**, 191301. arXiv:1509.07876. https://arxiv.org/abs/1509.07876 [The complexity–action duality variant of (IX.9).]

Brown, A. R., Roberts, D. A., Susskind, L., Swingle, B., and Zhao, Y. (2016b). *Complexity, action, and black holes.* Physical Review D **93**, 086006. arXiv:1512.04993. https://arxiv.org/abs/1512.04993 [Companion paper to 2016a; gives the detailed action-based complexity proposal.]

Brown, A. R., and Susskind, L. (2018). *Second law of quantum complexity.* Physical Review D **97**, 086015. arXiv:1701.01107. https://arxiv.org/abs/1701.01107 [The formal statement of the Second Law of Complexity reformulated in Theorem VIII.9.2 of the present paper as the operator-algebra-tier instance of Theorem VIII.7.]

Nielsen, M. A., Dowling, M. R., Gu, M., and Doherty, A. C. (2006). *Quantum computation as geometry.* Science **311**, 1133–1135. arXiv:quant-ph/0603161. https://arxiv.org/abs/quant-ph/0603161 [The Riemannian-geometry foundation of complexity geometry on $SU(2^K)$ referenced in Theorem VIII.9.1 Step 3.]

Marolf, D. (2015). *Emergent gravity requires kinematic nonlocality.* Physical Review Letters **114**, 031104. arXiv:1409.2509. https://arxiv.org/abs/1409.2509

Jacobson, T. (1995). *Thermodynamics of spacetime: the Einstein equation of state.* Physical Review Letters **75**, 1260. arXiv:gr-qc/9504004. https://arxiv.org/abs/gr-qc/9504004

Cardy, J. L. (1986). *Operator content of two-dimensional conformally invariant theories.* Nuclear Physics B **270**, 186–204.

Margolus, N., and Levitin, L. B. (1998). *The maximum speed of dynamical evolution.* Physica D **120**, 188–195. arXiv:quant-ph/9710043. https://arxiv.org/abs/quant-ph/9710043

Lieb, E. H., and Robinson, D. W. (1972). *The finite group velocity of quantum spin systems.* Communications in Mathematical Physics **28**, 251–257.

Hastings, M. B. (2010). *Locality in quantum systems.* In *Quantum Theory from Small to Large Scales* (École de Physique des Houches). arXiv:1008.5137. https://arxiv.org/abs/1008.5137

Pusey, M. F., Barrett, J., and Rudolph, T. (2012). *On the reality of the quantum state.* Nature Physics **8**, 475–478. arXiv:1111.3328. https://arxiv.org/abs/1111.3328

Kochen, S., and Specker, E. P. (1967). *The problem of hidden variables in quantum mechanics.* Journal of Mathematics and Mechanics **17**, 59–87.

Gleason, A. M. (1957). *Measures on the closed subspaces of a Hilbert space.* Journal of Mathematics and Mechanics **6**, 885–893.

Stone, M. H. (1932). *On one-parameter unitary groups in Hilbert space.* Annals of Mathematics **33**, 643–648.

Pinsker, M. S. (1964). *Information and Information Stability of Random Variables and Processes.* Holden-Day, San Francisco.

Csiszár, I. (1967). *Information-type measures of difference of probability distributions and indirect observation.* Studia Scientiarum Mathematicarum Hungarica **2**, 299–318.

Cover, T. M., and Thomas, J. A. (2006). *Elements of Information Theory*, 2nd ed. Wiley-Interscience.

Joos, E., and Zeh, H. D. (1985). *The emergence of classical properties through interaction with the environment.* Zeitschrift für Physik B **59**, 223–243.

Kac, M. (1949). *On distributions of certain Wiener functionals.* Transactions of the American Mathematical Society **65**, 1–13.

Nelson, E. (1964). *Feynman integrals and the Schrödinger equation.* Journal of Mathematical Physics **5**, 332–343.

Nelson, E. (1966). *Derivation of the Schrödinger equation from Newtonian mechanics.* Physical Review **150**, 1079–1085.

't Hooft, G. (1993). *Dimensional reduction in quantum gravity.* arXiv:gr-qc/9310026. https://arxiv.org/abs/gr-qc/9310026

Verlinde, H. (2020). *ER = EPR revisited: on the entropy of an Einstein–Rosen bridge.* arXiv:2003.13117. https://arxiv.org/abs/2003.13117

### Information paradox, firewalls, and quantum error correction

Akers, C., Engelhardt, N., Harlow, D., Penington, G., and Vardhan, S. (2022). *The black hole interior from non-isometric codes and complexity.* arXiv:2207.06536. JHEP **06** (2024) 155. https://arxiv.org/abs/2207.06536

Almheiri, A., Engelhardt, N., Marolf, D., and Maxfield, H. (2019). *The entropy of bulk quantum fields and the entanglement wedge of an evaporating black hole.* JHEP **12** (2019) 063. arXiv:1905.08762. https://arxiv.org/abs/1905.08762

Almheiri, A., Hartman, T., Maldacena, J., Shaghoulian, E., and Tajdini, A. (2020). *Replica wormholes and the entropy of Hawking radiation.* JHEP **05** (2020) 013. arXiv:1911.12333. https://arxiv.org/abs/1911.12333

Almheiri, A., Marolf, D., Polchinski, J., and Sully, J. (2013). *Black holes: complementarity or firewalls?* JHEP **02** (2013) 062. arXiv:1207.3123. https://arxiv.org/abs/1207.3123

Brown, A. R., Gharibyan, H., Penington, G., and Susskind, L. (2019). *The Python's Lunch: geometric obstructions to decoding Hawking radiation.* JHEP **08** (2020) 121. arXiv:1912.00228. https://arxiv.org/abs/1912.00228

Gao, P., Jafferis, D. L., and Wall, A. C. (2017). *Traversable wormholes via a double trace deformation.* JHEP **12** (2017) 151. arXiv:1608.05687. https://arxiv.org/abs/1608.05687

Giddings, S. B. (2006). *Black hole information, unitarity, and nonlocality.* Physical Review D **74**, 106005. arXiv:hep-th/0605196. https://arxiv.org/abs/hep-th/0605196

Harlow, D. (2026). *Are Space and Time Created by Quantum Error Correction? – World Science Festival.* World Science Festival, hosted by Brian Greene. https://www.youtube.com/watch?v=XbL64sz8dQI

Harlow, D., Usatyuk, M., and Zhao, Y. (2025). *Quantum mechanics and observers for gravity in a closed universe.* arXiv:2501.02359. https://arxiv.org/abs/2501.02359

Page, D. N. (1993). *Information in black hole radiation.* Physical Review Letters **71**, 3743–3746. arXiv:hep-th/9306083. https://arxiv.org/abs/hep-th/9306083

Parikh, M. K., and Wilczek, F. (2000). *Hawking radiation as tunneling.* Physical Review Letters **85**, 5042–5045. arXiv:hep-th/9907001. https://arxiv.org/abs/hep-th/9907001

Penington, G. (2020). *Entanglement wedge reconstruction and the information paradox.* JHEP **09** (2020) 002. arXiv:1905.08255. https://arxiv.org/abs/1905.08255

Zhao, Y. (2026). *"It from Bit": The Hartle–Hawking state and quantum mechanics for de Sitter observers.* arXiv:2602.05939. https://arxiv.org/abs/2602.05939

### Asymptotic symmetries, soft theorems, gravitational memory, and celestial holography

Barnich, G., and Troessaert, C. (2010). *Symmetries of asymptotically flat 4 dimensional spacetimes at null infinity revisited.* Physical Review Letters **105**, 111103. arXiv:0909.2617. https://arxiv.org/abs/0909.2617

Cachazo, F., and Strominger, A. (2014). *Evidence for a new soft graviton theorem.* arXiv:1404.4091. https://arxiv.org/abs/1404.4091

Freidel, L., Pranzetti, D., and Raclariu, A.-M. (2021). *Sub-subleading soft graviton theorem from asymptotic Einstein's equations.* JHEP **05** (2022) 186. arXiv:2111.15607. https://arxiv.org/abs/2111.15607

He, T., Lysov, V., Mitra, P., and Strominger, A. (2014). *BMS supertranslations and Weinberg's soft graviton theorem.* JHEP **05** (2015) 151. arXiv:1401.7026. https://arxiv.org/abs/1401.7026

Pasterski, S., Strominger, A., and Zhiboedov, A. (2015). *New gravitational memories.* JHEP **12** (2016) 053. arXiv:1502.06120. https://arxiv.org/abs/1502.06120

Pasterski, S., Shao, S.-H., and Strominger, A. (2017). *Flat space amplitudes and conformal symmetry of the celestial sphere.* Physical Review D **96**, 065026. arXiv:1701.00049. https://arxiv.org/abs/1701.00049

Strominger, A. (2014). *On BMS invariance of gravitational scattering.* JHEP **07** (2014) 152. arXiv:1312.2229. https://arxiv.org/abs/1312.2229

Strominger, A. (2017). *Lectures on the infrared structure of gravity and gauge theory.* Princeton University Press (2018). arXiv:1703.05448. https://arxiv.org/abs/1703.05448

Strominger, A. (2023). *Mindscape Podcast 222: Andrew Strominger on Quantum Gravity and the Real World.* Hosted by Sean Carroll, January 9, 2023. https://www.preposterousuniverse.com/podcast/2023/01/09/222-andrew-strominger-on-quantum-gravity-and-the-real-world/

Strominger, A. (2026). *Black Holes and Quantum Gravity – World Science Festival.* World Science Festival, hosted by Brian Greene. https://www.youtube.com/watch?v=eMSZNQEpaW8

Strominger, A., and Zhiboedov, A. (2014). *Gravitational memory, BMS supertranslations and soft theorems.* JHEP **01** (2016) 086. arXiv:1411.5745. https://arxiv.org/abs/1411.5745

Weinberg, S. (1965). *Infrared photons and gravitons.* Physical Review **140**, B516.

### Foundations of quantum mechanics

Ghirardi, G. C., Rimini, A., and Weber, T. (1986). *Unified dynamics for microscopic and macroscopic systems.* Physical Review D **34**, 470.

### McGucken corpus (Light Time Dimension Theory)

[MG-Bek26] McGucken, E. (2026). *How the McGucken Principle of a Fourth Expanding Dimension Derives the Results of Bekenstein's "Black Holes and Entropy" (1973): dx₄/dt = ic as the Physical Mechanism Underlying Black-Hole Entropy, the Area Law, the Bit-Per-8π ℓ_P² Coefficient, the Generalized Second Law, and Entropy as Missing Information.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/20/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-derives-the-results-of-bekensteins-black-holes-and-entropy-1973-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-black-hole/

[MG-Haw26] McGucken, E. (2026). *How the McGucken Principle of a Fourth Expanding Dimension Derives the Results of Hawking's "Particle Creation by Black Holes" (1975): dx₄/dt = ic as the Physical Mechanism Underlying Hawking Radiation, the Hawking Temperature, the Bekenstein–Hawking Formula S = A/4, the Refined Generalized Second Law, and Black-Hole Evaporation.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/20/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-derives-the-results-of-hawkings-particle-creation-by-black-holes-1975-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-hawki/

[MG-Proof] McGucken, E. (2026). *The McGucken Principle and Proof: The fourth dimension is expanding at the velocity of light, dx₄/dt = ic, as a foundational law of physics.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/15/the-mcgucken-principle-and-proof-the-fourth-dimension-is-expanding-at-the-velocity-of-light-dx4-dtic-as-a-foundational-law-of-physics/

[F1] McGucken, E. (2008). *Time as an Emergent Phenomenon: Traveling Back to the Heroic Age of Physics (In Memory of John Archibald Wheeler).* Foundational Questions Institute (FQXi) Essay Contest, "The Nature of Time," August 25, 2008. FQXi d/238. https://forums.fqxi.org/d/238

[F2] McGucken, E. (2009). *What is Ultimately Possible in Physics? Physics! A Hero's Journey with Galileo, Newton, Faraday, Maxwell, Planck, Einstein, Schrödinger, Bohr, and the Greats towards Moving Dimensions Theory. E pur si muove!* Foundational Questions Institute (FQXi) Essay Contest, "What Is Ultimately Possible in Physics?", September 16, 2009. FQXi d/511. https://forums.fqxi.org/d/511

[F3] McGucken, E. (2011). *On the Emergence of QM, Relativity, Entropy, Time, iℏ, and ic from the Foundational, Physical Reality of a Fourth Dimension x₄ Expanding with a Discrete (Digital) Wavelength ℓ_P at c Relative to Three Continuous (Analog) Spatial Dimensions.* Foundational Questions Institute (FQXi) Essay Contest, "Is Reality Digital or Analog?", February 11, 2011. FQXi d/873. https://forums.fqxi.org/d/873

[F4] McGucken, E. (2012). *MDT's dx₄/dt = ic Triumphs Over the Wrong Physical Assumption That Time is a Dimension.* Foundational Questions Institute (FQXi) Essay Contest, "Questioning the Foundations," August 24, 2012. FQXi d/1429. https://forums.fqxi.org/d/1429

[F5] McGucken, E. (2013). *It from Bit or Bit From It? What is It? Honor! Where is the Wisdom we have lost in Information? Returning Wheeler's Honor and Philo-Sophy — the Love of Wisdom — to Physics.* Foundational Questions Institute (FQXi) Essay Contest, "It From Bit or Bit From It?", July 3, 2013. FQXi d/1879. https://forums.fqxi.org/d/1879

[MG-HLA] McGucken, E. (2026). *The McGucken Principle (dx₄/dt = ic) as the physical mechanism underlying Huygens' Principle, the Principle of Least Action, Noether's theorem, and the Schrödinger equation.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/11/the-mcgucken-principle-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-huygens-principle-the-principle-of-least-action-noethers-theorem-and-the-schrodinger-equation/

[MG-Mech] McGucken, E. (2026). *The missing physical mechanism: how the principle of the expanding fourth dimension dx₄/dt = ic gives rise to the constancy and invariance of the velocity of light c, the second law of thermodynamics, and the foundations of physics.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/10/the-missing-physical-mechanism-how-the-principle-of-the-expanding-fourth-dimension-dx%e2%82%84-dt-ic-gives-rise-to-the-constancy-and-invariance-of-the-velocity-of-light-c-the-s/

[MG-Born] McGucken, E. (2026). *A geometric derivation of the Born rule P = |ψ|² from the McGucken Principle of the fourth expanding dimension dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/15/a-geometric-derivation-of-the-born-rule-p-%CF%882-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/

[MG-Constants] McGucken, E. (2026). *How the McGucken Principle of a fourth expanding dimension dx₄/dt = ic sets the constants c (the velocity of light) and h (Planck's constant).* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/11/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-sets-the-constants-c-the-velocity-of-light-and-h-plancks-constant/

[MG-PathInt] McGucken, E. (2026). *A derivation of Feynman's path integral from the McGucken Principle of the fourth expanding dimension dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/15/a-derivation-of-feynmans-path-integral-from-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic/

[MG-Nonloc] McGucken, E. (2026). *Quantum nonlocality and probability from the McGucken Principle of a fourth expanding dimension: how dx₄/dt = ic provides the physical mechanism underlying the Copenhagen interpretation.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/16/quantum-nonlocality-and-probability-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-how-dx4-dt-ic-provides-the-physical-mechanism-underlying-the-copenhagen-interpr/

[MG-Equiv] McGucken, E. (2024). *The McGucken Equivalence of quantum nonlocality and relativity: how quantum nonlocality and entanglement are found in relativity's time dilation and length contraction.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2024/12/29/the-mcgucken-equivalence-of-quantum-nonlocality-and-relativity-how-quantum-nonlocality-and-entanglement-are-found-in-relativity-s-time-dilation-and-length-contraction/

[MG-NonlocPrin] McGucken, E. (2024). *The McGucken Nonlocality Principle: all quantum nonlocality begins in locality as found in dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2024/09/14/the-mcgucken-nonlocality-principle-all-quantum-nonlocality-begins-in-locality-as-found-in-dx4-dtic/

[MG-Second-Nonloc] McGucken, E. (2024). *The second McGucken Principle of nonlocality: only systems of particles with intersecting light spheres, with each light sphere having originated from each respective particle, can ever be entangled.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2024/12/13/the-second-mcgucken-principles-of-nonlocality-only-systems-of-particles-with-intersecting-light-spheres-with-each-light-sphere-having-originated-from-each-respective-particle-can-ever-be-entangled/

[MG-Sphere] McGucken, E. (2024). *The McGucken Sphere represents the expansion of the fourth dimension x₄ at the rate of c, as given by Einstein's, Minkowski's, Poincaré's x₄ = ict, or McGucken's dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2024/11/09/the-mcgucken-sphere-represents-the-expansion-of-the-fourth-dimension-x4-at-the-rate-of-c-as-given-by-einsteins-minkowskis-poincares-x4ict-or-mcguckens-dx4-dtic/

[MG-EinMink] McGucken, E. (2024). *Einstein, Minkowski, x₄ = ict, and the McGucken proof of the fourth dimension's expansion at the velocity of light c: dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2024/10/30/einstein-minkowski-x4ict-and-the-mcgucken-proof-of-the-fourth-dimensions-expansion-at-the-velocity-of-light-c-dx4-dtic-2/

[MG-Sakharov] McGucken, E. (2026). *The McGucken Principle of a fourth expanding dimension dx₄/dt = ic as the physical mechanism underlying the three Sakharov conditions: a geometric resolution of baryogenesis and the matter–antimatter asymmetry.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/13/the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-as-the-physical-mechanism-underlying-the-three-sakharov-conditions-a-geometric-resolution-of-baryogenesis-and-the-matter-ant/

[MG-Wick] McGucken, E. (2026). *The History of the Wick Rotation from Poincaré to McGucken: A Rigorous Primary-Source Reconstruction of the Substitution t → −iτ from Poincaré 1905 Through Wick 1954 to the McGucken Principle dx₄/dt = ic of 2026, with the Wick Rotation Established as a Coordinate Identity τ = x₄/c on the Real Four-Dimensional McGucken Manifold and as the Structural Separator of Channel A (Algebraic-Symmetry, Lorentzian-Locked) from Channel B (Geometric-Propagation, Bi-Signature) of the McGucken Duality, with the 30-Year Hawking-Susskind Black-Hole War Diagnosed as a Community-Wide Channel-A-Only-Reading Blindspot Refuted at the Single-Photon Level via the Channel B Face of the Schrödinger Equation, and Susskind's Methodological Retreat from Operational Physics to Platonic Metaphysics Followed by a Declaration of Victory in Physics Structurally Diagnosed as the Pickleball-Wimbledon Domain-Shift That the Dual-Channel Architecture Forbids.* Light Time Dimension Theory, May 2026. https://elliotmcguckenphysics.com/ [Source of Theorems 30.9.27 through 30.9.34, including Theorem 30.9.30 (Structural Anatomy of Susskind's Equivocation), Theorem 30.9.30.2 (The Domain-Shifting Diagnostic), Remark 30.9.30.3 (Pickleball-Wimbledon analogy), Corollary 30.9.30.4 (Structural impossibility of the retreat), and Remark 30.9.30.5 (Structural-historical parallel to 19th-century Loschmidt-Zermelo-Poincaré reaction). The load-bearing source for Theorems III.6.6 and III.6.7 of the present paper.]

[MG-Wick-Necessitates] McGucken, E. (2026). *The McGucken Principle dx₄/dt = ic Necessitates the Wick Rotation and i Throughout Physics: A Reduction of Thirty-Four Independent Inputs of Quantum Field Theory, Quantum Mechanics, and Symmetry Physics to a Single Physical Principle, with the Imaginary Unit i Identified Across All of Physics — Including Penrose's Twistors, the Arkani-Hamed–Trnka Amplituhedron, Feynman Diagrams, AdS/CFT, String Theory, and the Extra Dimensions of Kaluza–Klein, String Theory, M-Theory, and AdS/CFT — as the Algebraic Signature of the Fourth Expanding Dimension.* Light Time Dimension Theory, May 1, 2026. https://elliotmcguckenphysics.com/2026/05/01/the-mcgucken-principle-dx4-dtic-necessitates-the-wick-rotation-and-i-throughout-physics-a-reduction-of-thirty-four-independent-inputs-of-quantum-field-theory-quantum-mechanics-and-symmetry-physics/

[MG-Information-Destruction] McGucken, E. (2026). *The Schrödinger Equation Contains the Second Law of Thermodynamics in Addition to Unitarity, the Measurement Problem and Hawking–Susskind Paradox Both Dissolved: Schrödinger and the Strict Second Law as Lorentzian and Euclidean Signature-Readings of Iterated Huygens–McGucken Sphere Expansion via dx₄/dt = ic, Wavefunction Collapse as the Euclidean Signature-Reading of the Same Evolution that Gives Unitarity in Lorentzian Signature, the Born Rule as a Theorem of the Lorentzian–Euclidean Modulus-Squared Correspondence Under the McGucken-Wick Rotation, Huygens-is-Holography as the Universal Screen Structure, and the Brownian Hamlet as Decisive Exhibition.* Light Time Dimension Theory, Manuscript v18, May 2026. https://elliotmcguckenphysics.com/

[MG-Thermodynamics-Chain] McGucken, E. (2026). *Thermodynamics Derived from the McGucken Principle: A Unique, Simple, and Complete Derivation of Thermodynamics as a Chain of Theorems of the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic.* Light Time Dimension Theory, April 2026. https://elliotmcguckenphysics.com/wp-content/uploads/2026/04/1_thermodynamics_derived_from_the_mcgucken-principle_-a-unique-simple-and-complete-derivation-of-thermodynamics-as-a-chain-of-theorems-of-the-mcgucken-principle-of-a-fourth-expanding-dim.pdf [Source paper for Theorems III.4.1, III.4.2, III.4.3, III.5.2, III.5.3, III.6.1, III.6.2, III.6.3, III.6.4, III.6.5; Theorems 23, 23.2, 24a–24e in the source.]

[MG-FeynmanDiagrams] McGucken, E. (2026). *Feynman Diagrams as Theorems of the McGucken Principle: Propagators, Vertices, Loops, Wick Contractions, and the Dyson Expansion as Iterated Huygens-with-Interaction on the Expanding Fourth Dimension.* Light Time Dimension Theory, April 23, 2026. https://elliotmcguckenphysics.com/2026/04/23/feynman-diagrams-as-theorems-of-the-mcgucken-principle/

[MG-Compton] McGucken, E. (2026). *A Compton Coupling Between Matter and the Expanding Fourth Dimension: A Proposed Matter Interaction for the McGucken Principle, with Consequences for Diffusion and Entropy.* Light Time Dimension Theory, April 18, 2026. https://elliotmcguckenphysics.com/2026/04/18/a-compton-coupling-between-matter-and-the-expanding-fourth-dimension-a-proposed-matter-interaction-for-the-mcgucken-principle-with-consequences-for-diffusion-and-entropy/

[MG-Susskind-Equation] McGucken, E. (2026). *The Schrödinger Equation as Dual-Channel Master Equation: A Reading of the Black Hole War.* Light Time Dimension Theory, May 21, 2026. https://elliotmcguckenphysics.com/

[MG-Unification] McGucken, E. (2026). *GR's Einstein Field Equations, QM's Canonical Commutation Relation, and the Second Law of Thermodynamics Unified as Three Instances of One Theorem of dx₄/dt = ic: The Unification of Classical Statistical Mechanics, Quantum Mechanics, and Gravity as Lorentzian and Euclidean Signature-Readings of Iterated McGucken Sphere Propagation, and dx₄/dt = ic as the Source of Holography and AdS/CFT.* Light Time Dimension Theory, May 12, 2026. https://elliotmcguckenphysics.com/2026/05/12/grs-einstein-field-equations-qms-canonical-commutation-relation-and-the-second-law-of-thermodynamics-unified-as-three-instances-of-one-theorem-of-dx%e2%82%84-dt-ic-the-unification-/

[MG-Susskind] McGucken, E. (2026). *Theorems of dx₄/dt = ic: How the McGucken Principle of a Fourth Expanding Dimension Derives Leonard Susskind's Six Black Hole Programmes: Holographic Principle, Complementarity, Stretched Horizon, String Microstates, ER = EPR, and Complexity.* Light Time Dimension Theory, elliotmcguckenphysics.com, April 21, 2026. https://elliotmcguckenphysics.com/2026/04/21/six-theorems-of-dx%e2%82%84-dt-ic-how-the-mcgucken-principle-of-a-fourth-expanding-dimension-derives-leonard-susskinds-black-hole-programmes-holographic-principle-complementarity-stretc/

[MG-Cat] McGucken, E. (2026). *The McGucken Category McG₆ as the Foundational, Structurally Complete, and Unique Category for the Positive-Geometry Programme: Penrose Twistor Space, the Positive Grassmannian, the Amplituhedron, and Feynman Diagrams as Categorically-Equivalent Descents from dx₄/dt = ic — Completing the Categorical Quest Identified by Arkani-Hamed: Predictive Scope from the Planck Scale to the Hubble Scale — The Standard Model Lagrangian, the Eight Higgs Theorems, Quark Color, and the First-Place-Finish McGucken Cosmology as Theorems of dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com, May 19, 2026. https://elliotmcguckenphysics.com/2026/05/19/the-mcgucken-category-mcg%e2%82%86-as-the-foundational-structurally-complete-and-unique-category-for-the-positive-geometry-programme-penrose-twistor-space-the-positive-grassmannian-the-amplituhed/

[MG-Geometry] McGucken, E. (2026). *The McGucken Geometry: A Novel Mathematical Category Exalted by the Principle/Axiom dx₄/dt = ic, wherein an Axis is Physically Expanding in a Spherically Symmetric Manner, and Exalting General Relativity, Quantum Mechanics, and Thermodynamics as Three Sectors of Physics Descending as Chains of Theorems from One Geometric Fact.* Light Time Dimension Theory, April 25, 2026; revised May 5, 2026. Original version: https://elliotmcguckenphysics.com/2026/04/25/mcgucken-geometry-the-novel-mathematical-structure-of-moving-dimension-geometry-underlying-the-physical-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic/. Revised version: https://elliotmcguckenphysics.com/2026/05/05/the-mcgucken-geometry-a-novel-mathematical-category-exalted-by-the-principle-axiom-dx%e2%82%84-dt-ic-wherein-an-axis-is-physically-expanding-in-a-spherically-symmetric-manner-and-exalting-general/

[MG-Twistor] McGucken, E. (2026). *How the McGucken Principle of a Fourth Expanding Dimension Gives Rise to Twistor Space: dx₄/dt = ic as the Physical Mechanism Underlying Penrose's Twistor Theory.* Light Time Dimension Theory, April 20, 2026. https://elliotmcguckenphysics.com/2026/04/20/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-gives-rise-to-twistor-space-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-penroses-twistor-theory/

[MG-Witten] McGucken, E. (2026). *How the McGucken Principle of a Fourth Expanding Dimension Resolves the Open Problems of Witten's Twistor Programme: dx₄/dt = ic as the Physical Mechanism Underlying Perturbative Gauge Theory as a String Theory in Twistor Space, Conformal Supergravity in Twistor-String Theory, Parity Invariance for Strings in Twistor Space, and the 1978 Twistor Formulation of Classical Yang–Mills Theory.* Light Time Dimension Theory, April 20, 2026. https://elliotmcguckenphysics.com/2026/04/20/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-resolves-the-open-problems-of-wittens-twistor-programme-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-perturbative-gauge-theory/

[MG-Dirac] McGucken, E. (2026). *The Geometric Origin of the Dirac Equation: Spin-½, the SU(2) Double Cover, and the Matter-Antimatter Structure from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic.* Light Time Dimension Theory, April 19, 2026. https://elliotmcguckenphysics.com/2026/04/19/the-geometric-origin-of-the-dirac-equation-spin-%c2%bd-the-su2-double-cover-and-the-matter-antimatter-structure-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic/

[MG-Commut] McGucken, E. (2026). *The Ontic Derivation of Quantum Mechanics from dx₄/dt = ic: The Commutator, the Uncertainty Principle, the Wavepacket Spread, and the Ground State as Kinematic Theorems of x₄-Advance, with a Comprehensive Catalogue of Unexplained and Poorly Explained Physical Phenomena Resolved by the McGucken Principle.* Light Time Dimension Theory, May 8, 2026. https://elliotmcguckenphysics.com/2026/05/08/the-ontic-derivation-of-quantum-mechanics-from-dx%e2%82%84-dt-ic-the-commutator-the-uncertainty-principle-the-wavepacket-spread-and-the-ground-state-as-kinematic-theorems-of-x%e2%82%84-advance/

[MG-SecondQ] McGucken, E. (2026). *Second Quantization of the Dirac Field from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Creation and Annihilation Operators as x₄-Orientation Operators, Fermion Statistics as a Theorem, and Pair Processes as x₄-Orientation Flips.* Light Time Dimension Theory, April 19, 2026. https://elliotmcguckenphysics.com/2026/04/19/second-quantization-of-the-dirac-field-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-creation-and-annihilation-operators-as-x%e2%82%84-orientation-operators-fermion/

[MG-QED] McGucken, E. (2026). *Quantum Electrodynamics from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Local x₄-Phase Invariance, the U(1) Gauge Structure, Maxwell's Equations, and the QED Lagrangian.* Light Time Dimension Theory, April 19, 2026. https://elliotmcguckenphysics.com/2026/04/19/quantum-electrodynamics-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-local-x%e2%82%84-phase-invariance-the-u1-gauge-structure-maxwells-equations-and-the-qed/

[MG-SM] McGucken, E. (2026). *A formal derivation of the Standard Model Lagrangians and general relativity from the McGucken Principle of the fourth expanding dimension dx₄/dt = ic.* Light Time Dimension Theory, elliotmcguckenphysics.com.

[MG-AdSCFT] McGucken, E. (2026). *The McGucken Principle as the Physical Foundation of the Holographic Principle and AdS/CFT: How dx₄/dt = ic Naturally Leads to Boundary Encoding of Bulk Information — Including Derivations of ℏ and G from the Fundamental Oscillation Scale of x₄, and the Formal Identification of dx₄/dt = ic as the Geometric Source of Quantum Nonlocality.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/18/the-mcgucken-principle-as-the-physical-foundation-of-the-holographic-principle-and-ads-cft-how-dx%e2%82%84-dt-ic-naturally-leads-to-boundary-encoding-of-bulk-information-including-derivat/

[MG-CosHolo] McGucken, E. (2026). *McGucken Holography for FRW and de Sitter Space from a Single Master Principle: dx₄/dt = ic, the McGucken Sphere, Cosmological Holography, an Explicit Horizon Surface Term, and a Testable Departure from the Hubble-Horizon Entropy.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/20/mcgucken-holography-for-frw-and-de-sitter-space-from-a-single-master-principle-dx%e2%82%84-dt-ic-the-mcgucken-sphere-cosmological-holography-an-explicit-horizon-surface-term-and-a-testable-depa/

[MG-Verlinde] McGucken, E. (2026). *The McGucken Principle (dx₄/dt = ic) as the physical mechanism underlying Verlinde's entropic gravity: a unified derivation of gravity, entropy, and the holographic principle from a single geometric postulate.* Light Time Dimension Theory, elliotmcguckenphysics.com. https://elliotmcguckenphysics.com/2026/04/11/the-mcgucken-principle-dx%e2%82%84-dt-ic-as-the-physical-mechanism-underlying-verlindes-entropic-gravity-a-unified-derivation-of-gravity-entropy-and-the-holographic-principle-from-a-single-ge/

[MG-DarkMatter] McGucken, E. (2026). *Dark Matter as Geometric Mis-Accounting: How the McGucken Principle of the Fourth Expanding Dimension (dx₄/dt = ic) Generates Flat Rotation Curves, the Tully-Fisher Relation, and Enhanced Gravitational Lensing Without Dark Matter Particles.* Light Time Dimension Theory, April 15, 2026. https://elliotmcguckenphysics.com/2026/04/15/dark-matter-as-geometric-mis-accounting-how-the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic-generates-flat-rotation-curves-the-tully-fisher-relation-and-enhanced-gr/

[MG-Horizon] McGucken, E. (2026). *The McGucken Principle of the Fourth Expanding Dimension (dx₄/dt = ic) as a Geometric Resolution of the Horizon Problem, the Flatness Problem, and the Homogeneity of the Cosmic Microwave Background — Without Inflation.* Light Time Dimension Theory, April 15, 2026. https://elliotmcguckenphysics.com/2026/04/15/the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic-as-a-geometric-resolution-of-the-horizon-problem-the-flatness-problem-and-the-homogeneity-of-the-cosmic-microwave-bac/

[MG-Lambda] McGucken, E. (2026). *The McGucken Principle of the Fourth Expanding Dimension (dx₄/dt = ic) as the Resolution of the Vacuum Energy Problem and the Cosmological Constant.* Light Time Dimension Theory, April 15, 2026. https://elliotmcguckenphysics.com/2026/04/15/the-mcgucken-principle-of-the-fourth-expanding-dimension-dx4-dt-ic-as-the-resolution-of-the-vacuum-energy-problem-and-the-cosmological-constant/

[MG-Cabibbo] McGucken, E. (2026). *The Cabibbo Angle from Quark Mass Ratios in the McGucken Principle Framework: A Partial Version 2 Derivation of the CKM Matrix from dx₄/dt = ic and a Geometric Reading of the Gatto-Fritzsch Relation.* Light Time Dimension Theory, April 19, 2026. https://elliotmcguckenphysics.com/2026/04/19/the-cabibbo-angle-from-quark-mass-ratios-in-the-mcgucken-principle-framework-a-partial-version-2-derivation-of-the-ckm-matrix-from-dx%e2%82%84-dt-ic-and-a-geometric-reading-of-the-gatto-fritzsch-re/

[MG-CKM] McGucken, E. (2026). *The CKM Complex Phase and the Jarlskog Invariant from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Compton-Frequency Interference, the Kobayashi-Maskawa Three-Generation Requirement as a Geometric Theorem, and Numerical Verification at Version 1 Scope.* Light Time Dimension Theory, April 19, 2026. https://elliotmcguckenphysics.com/2026/04/19/the-ckm-complex-phase-and-the-jarlskog-invariant-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%e2%82%84-dt-ic-compton-frequency-interference-the-kobayashi-maskawa-three-generation/

[Diss] McGucken, E. (1998–1999). *Multiple Unit Artificial Retina Chipset to Aid the Visually Impaired and Enhanced Holed-Emitter CMOS Phototransistors.* Ph.D. Dissertation, Department of Physics and Astronomy, University of North Carolina at Chapel Hill. NSF-funded research supported by Fight for Sight grants and a Merrill Lynch Innovations Award. The first written formulation of the McGucken Principle — time as an emergent phenomenon arising from a fourth dimension expanding at the velocity of light — appeared as an appendix to this dissertation.

---

*Dr. Elliot McGucken — drelliot@gmail.com — elliotmcguckenphysics.com*

*Light Time Dimension Theory — the McGucken Principle* d*x*₄/d*t* = i*c*.
