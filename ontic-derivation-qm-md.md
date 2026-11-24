# The Ontic Derivation of Quantum Mechanics from $dx_4/dt = ic$: The Commutator, the Uncertainty Principle, the Wavepacket Spread, and the Ground State as Kinematic Theorems of $x_4$-Advance, with a Comprehensive Catalogue of Unexplained and Poorly Explained Physical Phenomena Resolved by the McGucken Principle

**Elliot McGucken, Ph.D.**
Light Time Dimension Theory
elliotmcguckenphysics.com
drelliot@gmail.com

---

> *"More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet."*
>
> — John Archibald Wheeler, letter of recommendation, Princeton University, ca. 1990

---

## Abstract

The standard formulation of quantum mechanics treats the canonical commutator $[\hat{q},\hat{p}] = i\hbar$, the Heisenberg uncertainty relation $\Delta q \cdot \Delta p \geq \hbar/2$, the spreading of free wavepackets, and the ground-state saturation $\Delta q \cdot \Delta p = \hbar/2$ as four logically independent facts: the commutator is postulated, the uncertainty relation is derived from it via Robertson's 1929 inequality, the wavepacket spread is computed from the Schrödinger equation, and the ground state is a special wavefunction satisfying the inequality with equality. The interpretive content of these facts is contested: Heisenberg's microscope reading locates them in measurement disturbance, Bohrian complementarity locates them in the limits of meaningful classical description, and modern formal foundations (Robertson, Stone–von Neumann) treat them as algebraic features of the Hilbert-space framework. Each of these readings is *epistemic*: the facts are about the relation between observer and system. Building on the McGucken Principle $dx_4/dt = ic$, we prove in this paper that all four facts are *ontic*: they are kinematic projections of the universal advance of the fourth coordinate, present in every system whether or not any apparatus is involved. The unifying mechanism is the suppression map $\sigma$: the chain-rule identity $\partial/\partial t = ic\,\partial/\partial x_4$ transports $x_4$-advance into every conjugate-pair plane on the spatial slice, with the rate fixed by the Compton angular frequency $\omega_C = mc^2/\hbar$ for any system of rest mass $m$.

We establish, with all proofs given in full and self-contained: the kinematic commutator theorem; persistence at $\Delta t \to 0$; the minimum-action statement; the Robertson–Cauchy–Schwarz lemma proved by an in-paper Cauchy–Schwarz argument with no external import; the kinematic uncertainty theorem $\Delta q \cdot \Delta p \geq \hbar/2$; the kinematic dispersion theorem; the ground-state saturation theorem; and the time-energy uncertainty theorem via the Mandelstam–Tamm covariant route, circumventing Pauli's 1933 obstruction without contradicting it.

The catalogue of §11 extends the kinematic reading across twelve major foundational items, with all proofs integrated in-paper at Princeton-PhD rigor: the constancy and frame-independence of $c$; the foundational asymmetry of $i$; the Tsirelson bound $|\mathrm{CHSH}|\leq 2\sqrt{2}$ via full operator-norm derivation of the Tsirelson identity; Bell-inequality violation via the McGucken-Sphere shared-source mechanism; double-slit forward-conjugate $x_4$-overlap; spin-$\tfrac{1}{2}$ from matter orientation Condition (M) and the Single-Sided Preservation Lemma in $\mathrm{Cl}(1,3)$; universal tunneling time; Hawking temperature via Euclidean cigar plus KMS; area law and $\eta=1/4$; the Born rule $P=|\psi|^2$ via four geometric requirements with Sub-theorems I, II, II$'$, III, IV proved in-paper; the Hilbert space $\mathcal{H}\cong L^2(M_{1,3}, d\mu_M)$ via the four-step ontic chain; and the unification of $i$ across twelve canonical insertions.

The four pillars of quantum mechanics — Born rule, Hilbert space, canonical commutator, uncertainty principle — are reduced to four theorems of one physical principle. Eleven prior programs (von Neumann, Dirac, Mackey, Piron–Solèr, Jordan–von Neumann–Wigner, Hardy, Chiribella–D'Ariano–Perinotti, Abramsky–Coecke, Stueckelberg, Adler, Renou et al.) postulated, axiomatized, reconstructed, characterized, classified, or empirically confirmed $\mathcal{H}$; none operates upstream of the complex Hilbert-space structure itself. Before McGucken, $\mathcal{H}$ was an axiom; after McGucken, $\mathcal{H}$ is a theorem of $dx_4/dt = ic$.

This paper is self-contained: every theorem in §§2–11 is proved in full from $dx_4/dt = ic$ and the structures it generates, with the only external machinery being real analysis (Cauchy–Schwarz, Cauchy completion via Riesz–Fischer 1907, Frobenius's classification of normed division algebras over $\mathbb{R}$).

---

## 1. Introduction: From Epistemic to Ontic Quantum Mechanics

The four foundational facts of non-relativistic quantum mechanics — the canonical commutator $[\hat q, \hat p] = i\hbar$, the Heisenberg uncertainty relation $\Delta q \cdot \Delta p \geq \hbar/2$, the spreading of free wavepackets, and the ground-state saturation of the uncertainty relation — are conventionally treated as separate facts unified only by the algebraic apparatus of canonical quantization. The commutator is a postulate. The uncertainty relation follows from the commutator via the Robertson 1929 inequality, a Cauchy–Schwarz argument on the variance operators. The wavepacket spread is a calculation from the Schrödinger equation. The ground-state saturation is a property of the harmonic-oscillator ground-state wavefunction in position representation. Each fact is rigorous in its own derivation, but the four are not unified by any common physical mechanism in the standard treatment.

The interpretive content of the four facts has been disputed since the founding of the theory. Heisenberg's 1927 microscope thought-experiment reads the uncertainty relation as a constraint on simultaneous measurement: localizing a particle's position with a photon transfers momentum, so the joint precision of $q$ and $p$ is bounded. Bohrian complementarity generalizes this to a positivist principle: complementary observables cannot *simultaneously possess* sharp values. Both readings are *epistemic*: they locate the four facts in the relation between observer and system, the act or possibility of measurement, the limits of classical description.

The McGucken Principle $dx_4/dt = ic$ supplies an alternative reading. In the present paper, the four facts are established as kinematic projections of the universal advance of the fourth coordinate, present in every system whether or not any apparatus is involved. The mechanism is the suppression map $\sigma$: the chain-rule identity $\partial/\partial t = ic\,\partial/\partial x_4$ transports $x_4$-advance into every conjugate-pair plane on the spatial slice, with the rate fixed by the Compton angular frequency $\omega_C = mc^2/\hbar$ for any system of rest mass $m$.

The structural shift is captured by the contrast:

- **Standard reading (epistemic).** The system would have sharp $(q, p)$ values were it not disturbed by measurement. The four facts are constraints on what an observer can know or coherently say about classical-like properties.
- **Kinematic reading (ontic).** The system is being disturbed continuously by $x_4$-advance, whether or not any observer is present. The four facts are kinematic projections of that universal advance, with the apparatus a vivid local example of a phenomenon that holds globally.

The empirical content is sharp. The microscope reading predicts that sufficiently gentle measurements could in principle evade the trade-off; experiments over a century show they do not. The vacuum saturation case is decisive: the harmonic-oscillator ground state attains $\Delta q \cdot \Delta p = \hbar/2$ exactly with no apparatus present. The microscope reading has no explanation. The kinematic reading explains it as the geometric signature of $x_4$-advance at the oscillator's natural frequency.

### 1.1 What the standard derivations leave undetermined

Four substantive accounts of $[\hat{q}, \hat{p}] = i\hbar$ exist in the textbook tradition.

**(I) Born–Heisenberg–Jordan postulate.** The relation is asserted as a quantum condition; the imaginary unit $i$ is a sign convention with no specified physical meaning.

**(II) Dirac correspondence.** Quantum commutators correspond to classical Poisson brackets. Groenewold's 1946 theorem establishes that the analogy cannot hold systematically; it is salvageable only as the Moyal-bracket deformation.

**(III) Hamiltonian-mechanics correspondence.** The argument is structurally circular: $\exp(-i\hat{H}t/\hbar)$ already contains the $i\hbar$ being "derived."

**(IV) Stone–von Neumann uniqueness.** Rigorous, but presupposes the entire complex Hilbert-space structure as input.

Each standard derivation imports the imaginary unit $i$ and the Hilbert-space framework as algebraic features rather than identifying their physical content. None addresses why the right-hand side of the commutator is $i\hbar$. None gives $\hbar$ a physical origin. None explains why the vacuum saturates the uncertainty bound in the absence of any apparatus. The McGucken derivation in the present paper addresses all of these gaps.

---

## 2. The Principle, Its Duality, and the Rigidity of $i$

We follow standard conventions. The four-dimensional manifold $M$ has coordinates $(x_1, x_2, x_3, x_4)$ where $x_4$ is the fourth dimension, $c$ is the universal speed of light, $t$ is the temporal parameter, and $i$ is the rotational generator on the oriented $(t, x_4)$ plane.

**Remark on priority of $dx_4/dt = ic$ over $x_4 = ict$.** $dx_4/dt = ic$ is the foundational physical law. $x_4 = ict$ is the integrated kinematic shadow. Differentiation goes the other way. The mathematical equivalence is one calculus operation in either direction; the physical content is asymmetric. $dx_4/dt = ic$ is the dynamical statement of an actual physical motion of the fourth dimension at every event, expanding spherically at $c$ in the direction perpendicular to the three spatial coordinates. To paraphrase Neil Armstrong: obtaining $x_4 = ict$ by integration of $dx_4/dt = ic$ is one small step for math; recognizing that the fourth dimension is physically expanding at the velocity of light in a spherically symmetric manner, with all the naturally derivational consequences this has across physics, is one giant leap for physics.

### Principle 2.1 (McGucken Principle)

At every event, the fourth coordinate $x_4$ evolves with respect to $t$ according to
$$\frac{dx_4}{dt} = ic.$$

This is a physical principle, not a postulate or axiom: $c$ is established empirically. The full statement specifies further that $x_4$ expands oscillatorily, with one complete oscillation at the Compton frequency carrying one quantum of action $\hbar$.

### 2.1 Linear–rotational duality

The two sides of $dx_4/dt = ic$ encode two distinct geometric operations. On the left, $dx_4/dt$ is the linear advance of a coordinate. On the right, $ic$ is multiplication by $i$ scaled by $c$ — geometrically, rotation by $\pi/2$ in the complex plane, scaled by $c$. The equality sign asserts that linear advance along $x_4$ and rotation in $\mathbb{C}$ are the same operation viewed in two projections.

### Proposition 2.2 (Linear–rotational duality)

The equation $dx_4/dt = ic$ asserts that linear advance in $x_4$ and rotation in $\mathbb{C}$ are the same operation. For any temporal interval $[t_0, t_0 + \Delta t]$:

(i) the linear $x_4$-advance is $\Delta x_4 = ic\, \Delta t$;
(ii) the associated rotation in the $(t, x_4)$ plane has angle $\theta = \omega \Delta t$, with $\omega$ fixed by the rate of advance and the Compton scale of the system;
(iii) for any observable whose evolution is generated by a self-adjoint $\hat{G}$, the unitary $\exp(-i\hat{G}\Delta t/\hbar)$ uses the same $i$ as in (i)–(ii).

### 2.2 Frobenius rigidity of $i$

### Lemma 2.3 (Frobenius rigidity)

The McGucken Principle requires a generator $J$ that satisfies: (1) $J$ preserves magnitude under the rotation it generates; (2) $J$ closes under composition; (3) $J^2 = -1$; (4) $J$ acts within a two-dimensional extension of $\mathbb{R}$. The unique generator (up to sign) satisfying (1)–(4) is $J = i$, the imaginary unit of $\mathbb{C}$.

**Proof.** Conditions (1) and (2) force a normed division algebra over $\mathbb{R}$. Frobenius's theorem of 1878 establishes that the only finite-dimensional associative normed division algebras over $\mathbb{R}$ are $\mathbb{R}$, $\mathbb{C}$, and $\mathbb{H}$ (the reals, complexes, and quaternions). Condition (4) restricts to a two-dimensional extension, which is uniquely $\mathbb{C}$. Within $\mathbb{C}$, the elements squaring to $-1$ are exactly $\pm i$. The two choices $+i$ and $-i$ are related by orientation reversal of the $(t, x_4)$ plane; the McGucken Principle commits to $+i$, with the $-i$ option corresponding to the conjugate orientation invoked in the path-integral conjugate $\psi^*$. ∎

### 2.3 The suppression map $\sigma$

### Definition 2.4 (Suppression map $\sigma$)

Let $M_E$ be the four-dimensional real Euclidean manifold with coordinates $(x_1, x_2, x_3, x_4)$. The McGucken constraint $\Phi_M = x_4 - ict$ vanishes precisely on the worldlines satisfying the Principle. The suppression map
$$\sigma : M_E \to M_{1,3}, \quad (x_1, x_2, x_3, x_4) \mapsto (x_1, x_2, x_3, t),$$
where $t = x_4/(ic) = -ix_4/c$, sends the real Euclidean line element $d\ell^2 = dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2$ to the Lorentzian interval $ds^2 = dx_1^2 + dx_2^2 + dx_3^2 - c^2 dt^2$ via the substitution $dx_4^2 = (ic\,dt)^2 = -c^2 dt^2$, and sends differential operators on $M_E$ involving $\partial/\partial x_4$ to differential operators on $M_{1,3}$ via the chain rule
$$\frac{\partial}{\partial t} = \frac{dx_4}{dt}\cdot \frac{\partial}{\partial x_4} = ic\cdot \frac{\partial}{\partial x_4}.$$

Every $i$ in non-relativistic quantum mechanics is the $\sigma$-chain-rule factor for the corresponding $x_4$-derivative in the underlying real construction on $M_E$.

### Lemma 2.5 (Non-vanishing at every event)

$dx_4/dt = ic \neq 0$ at every event. No deformation of the Principle preserving Lorentzian signature, unitary evolution, and CPT permits $dx_4/dt$ to vanish at any event.

**Proof.** $ic = 0$ requires $i = 0$ or $c = 0$; the first contradicts $i^2 = -1$, the second contradicts the empirical universal speed of light. Replacing $i$ by a real coefficient destroys the Lorentzian signature, destroys unitary evolution, and destroys CPT. By Lemma 2.3, no alternative algebra satisfies the constraints. ∎

### Lemma 2.6 (Integrated form)

For any temporal interval $\Delta t$, $\Delta x_4 = ic\,\Delta t$.

**Proof.** By Principle 2.1 and Lemma 2.5, $dx_4/dt = ic$ is constant in $t$. The fundamental theorem of calculus gives $\Delta x_4 = \int_{t_0}^{t_0+\Delta t}(dx_4/dt')\,dt' = ic\,\Delta t$. ∎

---

## 3. The Commutator as Kinematic Theorem

### 3.1 Phase advance and $x_4$-advance are the same rotation

### Theorem 3.1 (Phase advance and $x_4$-advance are the same rotation)

For a system of rest mass $m$ in a temporal interval $[t_0, t_0 + \Delta t]$, the phase advance $\phi = S/\hbar$ generated by the rest-mass Hamiltonian and the geometric $x_4$-advance $\Delta x_4 = ic\,\Delta t$ are the same rotation in the $(t, x_4)$ plane, both proceeding at angular frequency $\omega_C = mc^2/\hbar$.

**Proof.**

*Step 1 (geometric rotation rate).* By Proposition 2.2, $dx_4/dt = ic$ asserts that linear advance in $x_4$ at rate $c$ and rotation in the $(t, x_4)$ plane at angular frequency $|dx_4/dt|/\ell$ for some characteristic length $\ell$ are the same operation. For a system of rest mass $m$, the unique length constructible from $\hbar$, $m$, $c$ is the reduced Compton wavelength $\ell_C \equiv \hbar/(mc)$. Read in these units,
$$\omega_{\text{geom}} = \frac{|dx_4/dt|}{\ell_C} = \frac{c}{\hbar/(mc)} = \frac{mc^2}{\hbar}.$$

*Step 2 (quantum rotation rate).* The rest-mass component of the time-evolution operator is $\hat{U}_{\text{rest}}(\Delta t) = \exp(-imc^2\Delta t/\hbar)$, rotating the state vector at angular frequency $\omega_{\text{quant}} = mc^2/\hbar = \omega_C$.

*Step 3 (identification).* $\omega_{\text{geom}} = \omega_{\text{quant}} = \omega_C$. The factor $i$ in $\hat{U}(\Delta t) = \exp(-i\hat{H}\Delta t/\hbar)$ is, by Lemma 2.3 and Definition 2.4, the same $i$ as in the Principle, since both are the unique magnitude-preserving generator on a two-dimensional $\mathbb{R}$-extension. The two rotations coincide in both rate and generator. ∎

### 3.2 The kinematic commutator theorem

### Theorem 3.2 (Kinematic commutator theorem)

For conjugate observables $(\hat{q}, \hat{p})$ on the spatial slice and any temporal interval $[t_0, t_0 + \Delta t]$, the equal-time commutator $[\hat{q}(t_0), \hat{p}(t_0)] = i\hbar$ is the projection of $x_4$'s non-zero advance rate onto the conjugate-pair plane via the suppression map $\sigma$, with $i$ in the commutator being the same generator as in $dx_4/dt = ic$.

**Proof.** By Principle 2.1 and Lemma 2.6, $\Delta x_4 = ic\,\Delta t$. Translation invariance of the manifold $M_E$ along each direction $x_\mu$ gives, by Noether's theorem, a conserved four-momentum $p_\mu$. On scalar wavefunctions over $M_E$, $p_\mu$ is the infinitesimal generator of the corresponding translation: writing the plane-wave amplitude $\psi(x) = \exp(ip_\mu x^\mu/\hbar)$ (the path-integral phase, with the $i$ inherited from $dx_4/dt = ic$ via Theorem 3.1),
$$\partial_\mu \psi = (ip_\mu/\hbar)\psi, \quad \text{equivalently} \quad p_\mu = -i\hbar\,\partial_\mu.$$

The factor $-i\hbar$ is fixed by two requirements: (a) the eigenvalue equation $\hat p_\mu \psi = p_\mu \psi$ on plane waves; (b) the Minkowski signature induced by $x_4 = ict$ via $(ict)^2 = -c^2t^2$. Restricting to one spatial axis $q = x_k$ for fixed $k\in\{1,2,3\}$, $\hat p = -i\hbar\,\partial/\partial q$. Computing on a smooth test function $f$:
$$[\hat q, \hat p]\,f = q\cdot(-i\hbar\,\partial_q f) - (-i\hbar\,\partial_q)(qf) = -i\hbar\,q\,\partial_q f + i\hbar(f + q\,\partial_q f) = i\hbar\, f.$$

Since this holds for all smooth $f$, $[\hat q, \hat p] = i\hbar$ as an operator identity. The factor $i$ on the right-hand side traces back through three structurally connected steps to the factor $i$ in $dx_4/dt = ic$: (i) the Minkowski signature comes from $(ict)^2 = -c^2 t^2$; (ii) the path-integral phase inherits its $i$ from the imaginary $x_4$-displacement; (iii) the momentum operator inherits its $i$ from the phase-derivative correspondence. The factor $\hbar$ is the action accumulated per Compton-period oscillation of $x_4$ at the Planck frequency. ∎

### 3.3 Persistence at $\Delta t \to 0$

### Theorem 3.3 (Persistence at $\Delta t \to 0$)

For any $\Delta t > 0$:
(i) $\Delta x_4 = ic\,\Delta t \neq 0$;
(ii) the projection of this advance onto $(\hat{q}, \hat{p})$ accumulates action $\hbar$ at $\Delta t = t_C \equiv \hbar/(mc^2)$;
(iii) the commutator $[\hat{q}, \hat{p}] = i\hbar$ at $\Delta t = 0$ is the differential limit of this non-vanishing integral;
(iv) no Frobenius-compatible deformation of the Principle permits the commutator to vanish.

**Proof.** (i)–(iii) follow directly from Theorem 3.1 and Lemmas 2.5, 2.6. For (iv): if $[\hat{q}, \hat{p}]$ were to vanish at $\Delta t = 0$, then $dx_4/dt$ would have to vanish, requiring either $c = 0$ or $i$ replaced by an algebraic structure permitting zero — excluded by Lemma 2.3. ∎

---

## 4. The Minimum-Action Statement

### Theorem 4.1 (Minimum-action statement)

For any system of rest mass $m$ and any $\Delta t \geq \hbar/(mc^2) = t_C$, the action accumulated along the $x_4$-axis satisfies $S \geq \hbar$. For $\Delta t \to 0$, the differential rate $dS/dt = mc^2$ is non-zero at every event.

**Proof.** By Theorem 3.3, $\Delta x_4 = ic\,\Delta t$ with phase advance $\phi = mc^2 \Delta t/\hbar$. Setting $\phi = 1$ gives $\Delta t = \hbar/(mc^2) = t_C$. For $\Delta t \geq t_C$, $S \geq \hbar$. The continuous-rate statement holds at every event by Lemmas 2.5, 2.3. ∎

### Corollary 4.2 (Universal action accumulation)

For any system with non-zero rest mass, the rate of action accumulation along the $x_4$-axis is $dS/dt = mc^2$, the rest energy. This rate is non-zero at every event, with no dependence on whether the system is observed.

---

## 5. The Robertson–Cauchy–Schwarz Lemma and the Kinematic Uncertainty Theorem

The Heisenberg uncertainty relation $\Delta q \cdot \Delta p \geq \hbar/2$ is conventionally derived from the commutator via the Robertson 1929 inequality. We prove this Robertson inequality in-paper as a self-contained Cauchy–Schwarz lemma, then apply it.

### 5.1 The Robertson–Cauchy–Schwarz lemma

### Lemma 5.1 (Robertson–Cauchy–Schwarz inequality)

Let $\hat A$, $\hat B$ be self-adjoint operators on a complex inner-product space, and let $|\psi\rangle$ be a unit vector on which $\hat A|\psi\rangle$ and $\hat B|\psi\rangle$ are defined. Define $\sigma_A^2 = \langle\psi|(\hat A - \langle\hat A\rangle)^2|\psi\rangle$ and similarly $\sigma_B^2$, where $\langle\hat A\rangle = \langle\psi|\hat A|\psi\rangle$. Then
$$\sigma_A\,\sigma_B \geq \tfrac{1}{2}|\langle\psi|[\hat A, \hat B]|\psi\rangle|.$$

**Proof.** Define centred operators $\hat A_0 = \hat A - \langle\hat A\rangle$ and $\hat B_0 = \hat B - \langle\hat B\rangle$. Both are self-adjoint, and $[\hat A_0, \hat B_0] = [\hat A, \hat B]$ since constant shifts commute.

*Step 1 (Cauchy–Schwarz).* For any two vectors $|\alpha\rangle, |\beta\rangle$ in a complex inner-product space, $|\langle\alpha|\beta\rangle|^2 \leq \langle\alpha|\alpha\rangle\langle\beta|\beta\rangle$. Applied to $|\alpha\rangle = \hat A_0|\psi\rangle$ and $|\beta\rangle = \hat B_0|\psi\rangle$,
$$|\langle\hat A_0\psi | \hat B_0\psi\rangle|^2 \leq \langle\hat A_0\psi|\hat A_0\psi\rangle\,\langle\hat B_0\psi|\hat B_0\psi\rangle = \sigma_A^2\,\sigma_B^2.$$

*Step 2 (Hermitian/anti-Hermitian decomposition).* Using self-adjointness,
$$\langle\hat A_0\psi|\hat B_0\psi\rangle = \langle\psi|\hat A_0\hat B_0|\psi\rangle.$$

Decompose
$$\hat A_0\hat B_0 = \tfrac{1}{2}\{\hat A_0, \hat B_0\} + \tfrac{1}{2}[\hat A_0, \hat B_0],$$

where $\{\hat A_0, \hat B_0\} = \hat A_0\hat B_0 + \hat B_0\hat A_0$ is the anticommutator (self-adjoint) and $[\hat A_0, \hat B_0]$ is the commutator (anti-self-adjoint). Therefore $\langle\psi|\{\hat A_0,\hat B_0\}|\psi\rangle$ is real, $\langle\psi|[\hat A_0,\hat B_0]|\psi\rangle$ is purely imaginary, and the two contributions to $\langle\hat A_0\psi|\hat B_0\psi\rangle$ are orthogonal in the complex plane:
$$|\langle\hat A_0\psi|\hat B_0\psi\rangle|^2 = \tfrac{1}{4}|\langle\{\hat A_0,\hat B_0\}\rangle|^2 + \tfrac{1}{4}|\langle[\hat A_0,\hat B_0]\rangle|^2 \geq \tfrac{1}{4}|\langle[\hat A,\hat B]\rangle|^2.$$

*Step 3 (combine).* From Steps 1 and 2,
$$\sigma_A^2\,\sigma_B^2 \geq \tfrac{1}{4}|\langle\psi|[\hat A,\hat B]|\psi\rangle|^2.$$

Taking the positive square root: $\sigma_A\sigma_B \geq \tfrac{1}{2}|\langle\psi|[\hat A,\hat B]|\psi\rangle|$. ∎

### 5.2 The kinematic uncertainty theorem

### Theorem 5.2 (Kinematic uncertainty theorem)

For any normalized state $|\psi\rangle$ and any pair of conjugate observables $(\hat{q}, \hat{p})$ on the spatial slice, the variance product satisfies
$$\Delta q \cdot \Delta p \geq \tfrac{\hbar}{2}.$$

The lower bound is the kinematic projection of the universal $x_4$-advance onto the conjugate-pair plane via the suppression map $\sigma$. The factor $\hbar$ is the action accumulated per Compton-period oscillation of $x_4$ (Theorem 4.1), inherited via $\sigma$ from the commutator (Theorem 3.2); the factor $\tfrac{1}{2}$ is inherited from the Cauchy–Schwarz step in Lemma 5.1. The inequality holds for every state, measured or unmeasured.

**Proof.** By Theorem 3.2, $[\hat q, \hat p] = i\hbar$ at every $t_0$. By Theorem 3.3, this holds even at $\Delta t \to 0$. Apply Lemma 5.1 with $\hat A = \hat q$ and $\hat B = \hat p$:
$$\sigma_q\,\sigma_p \geq \tfrac{1}{2}|\langle\psi|i\hbar|\psi\rangle| = \tfrac{1}{2}\hbar |\langle\psi|\psi\rangle| = \tfrac{\hbar}{2},$$

using normalization $\langle\psi|\psi\rangle = 1$. The kinematic interpretation: the commutator's value $i\hbar$ is the projection of $x_4$-advance through $\sigma$, with the $i$ identified as the same imaginary unit generating the rotation in the $(t, x_4)$ plane and the $\hbar$ identified as the action per Compton-period oscillation. The bound $\hbar/2$ is half the kinematic action $\hbar$ that the commutator carries, with the factor $\tfrac{1}{2}$ supplied by Cauchy–Schwarz. The proof of Lemma 5.1 invokes nothing measurement-specific; the inequality holds for every state. ∎

### 5.3 Three cases of uncertainty without direct disturbance

**Case 1 (QND measurements).** A quantum non-demolition measurement reads out an observable without disturbing the eigenstate. Microscope reading: QND measurements should evade the trade-offs. Experimentally: they evade in the measured channel but exhibit it in the conjugate channel. Kinematic reading: $x_4$ rotates the conjugate pair regardless of which channel is probed.

**Case 2 (Free evolution).** A state prepared at $t_0$ with $\Delta q\cdot\Delta p = \hbar/2$ and allowed to evolve freely until $t_1$ exhibits wavepacket spreading. Microscope reading has no story (no measurement during $[t_0, t_1]$). Kinematic reading: continuous $x_4$-rotation during the interval.

**Case 3 (Vacuum saturation).** A harmonic oscillator in its ground state has $\Delta q\cdot\Delta p = \hbar/2$ exactly with no apparatus and no measurement. Microscope reading: no explanation. Kinematic reading: minimum spatial-slice projection of $x_4$-advance at the oscillator's natural frequency.

---

## 6. The Kinematic Dispersion Theorem

### Theorem 6.1 (Kinematic dispersion theorem)

For a free-particle Gaussian wavepacket initially at $t = 0$ with width $\sigma_q(0)$, the temporal evolution of the position width is
$$\sigma_q(t) = \sqrt{\sigma_q(0)^2 + \biggl(\frac{\hbar t}{2m\sigma_q(0)}\biggr)^2},$$

with the kinetic-spreading term identified as the spatial-slice projection of $x_4$-advance over $[0, t]$ via $\sigma$.

**Proof.**

*Step 1 (variance evolution).* The Heisenberg-picture position of a free particle evolves as $\hat q(t) = \hat q(0) + \hat p(0)\,t/m$ (free Hamiltonian $\hat H = \hat p^2/2m$ gives $d\hat q/dt = (i/\hbar)[\hat H,\hat q] = \hat p/m$, and $d\hat p/dt = 0$). Computing the variance:
$$\sigma_q(t)^2 = \langle\hat q(t)^2\rangle - \langle\hat q(t)\rangle^2.$$

Expanding $\hat q(t)^2 = \hat q(0)^2 + (t/m)\{\hat q(0),\hat p(0)\} + (t/m)^2\hat p(0)^2$, taking expectation in a state with $\langle\hat q(0)\rangle = \langle\hat p(0)\rangle = 0$:
$$\sigma_q(t)^2 = \sigma_q(0)^2 + \frac{t^2}{m^2}\sigma_p(0)^2.$$

*Step 2 (saturation condition).* For a Gaussian initially saturating the kinematic uncertainty bound, $\sigma_q(0)\,\sigma_p(0) = \hbar/2$, so $\sigma_p(0) = \hbar/(2\sigma_q(0))$. Substituting:
$$\sigma_q(t)^2 = \sigma_q(0)^2 + \biggl(\frac{\hbar t}{2m\sigma_q(0)}\biggr)^2.$$

*Step 3 (kinematic interpretation).* Multiplying the rate $\hbar/(2m\sigma_q(0))$ by $c/c$ and using $\ell_C = \hbar/(mc)$:
$$\frac{\hbar}{2m\sigma_q(0)} = \frac{\ell_C\cdot c}{2\sigma_q(0)} = \frac{c}{2(\sigma_q(0)/\ell_C)}.$$

The geometric content: $x_4$ advances at $c$, the wavepacket compactness is $\sigma_q(0)/\ell_C$ in Compton-wavelength units, the spreading rate is the speed of light scaled by this dimensionless compactness. Free-evolution wavepacket spreading is therefore a kinematic theorem of $x_4$-advance during $[0,t]$ via $\sigma$, not a calculational artifact of the Schrödinger equation. ∎

---

## 7. The Ground-State Saturation Theorem

### Theorem 7.1 (Ground-state saturation theorem)

The harmonic-oscillator ground state $|0\rangle$ saturates the kinematic uncertainty inequality, $\Delta q\cdot\Delta p = \hbar/2$, because it is the state in which the spatial-slice projection of $x_4$-advance via $\sigma$ is minimized at the oscillator's natural frequency. The zero-point energy $E_0 = \hbar\omega/2$ is the action accumulated per half-cycle of $x_4$-rotation along the oscillator's period $T = 2\pi/\omega$.

**Proof.**

*Step 1 (Gaussian saturating states).* The Robertson–Cauchy–Schwarz inequality (Lemma 5.1) is saturated when (a) the Cauchy–Schwarz step is saturated, requiring $\hat A_0|\psi\rangle = c\,\hat B_0|\psi\rangle$ for some $c\in\mathbb{C}$, and (b) the anticommutator expectation vanishes. For $\hat A = \hat q$, $\hat B = \hat p$, condition (a) requires $(\hat q - \langle\hat q\rangle)|\psi\rangle = c(\hat p - \langle\hat p\rangle)|\psi\rangle$, a first-order linear ODE in position representation whose solutions are Gaussian. Condition (b) for centred Gaussians requires the cross term to be purely imaginary, fixing $c$ to be purely imaginary; writing $c = -i\hbar/(2m\omega)$ gives the unnormalized Gaussian
$$\psi_0(q) \propto \exp(-m\omega q^2/2\hbar).$$

*Step 2 (energy minimization fixes the Gaussian).* Among saturating Gaussians parameterized by width $\sigma_q$, the harmonic-oscillator energy at saturation $\sigma_q\sigma_p = \hbar/2$ becomes $E(\sigma_q) = \hbar^2/(8m\sigma_q^2) + \tfrac{1}{2}m\omega^2\sigma_q^2$. Minimizing: $dE/d\sigma_q = -\hbar^2/(4m\sigma_q^3) + m\omega^2\sigma_q = 0$ gives $\sigma_q^2 = \hbar/(2m\omega)$, hence $\sigma_p^2 = m\omega\hbar/2$. Direct substitution: $E_0 = \hbar\omega/4 + \hbar\omega/4 = \hbar\omega/2$, the zero-point energy.

*Step 3 (kinematic interpretation).*
$$\sigma_q\cdot\sigma_p = \sqrt{\frac{\hbar}{2m\omega}}\cdot\sqrt{\frac{m\omega\hbar}{2}} = \frac{\hbar}{2}.$$

This is the saturation. By Theorem 5.2, the bound $\hbar/2$ is the half-cycle kinematic content of $x_4$-rotation projected through $\sigma$. The ground state's $\sigma$-image is the minimal spatial-slice projection of $x_4$-advance compatible with the oscillator's confining potential.

*Step 4 (universality).* The argument generalizes: for any quadratic Hamiltonian, the ground state is a minimum-uncertainty Gaussian whose $\sigma$-image carries the half-cycle action of $x_4$-rotation at the system's characteristic frequency. The vacuum saturation case is the minimum-spatial-slice-projection state with no apparatus required. ∎

---

## 8. The Time-Energy Uncertainty Relation

### Theorem 8.1 (Time-energy uncertainty as kinematic theorem)

For any system with non-zero rest mass $m$ and any covariant observable $\hat A$ that does not commute with the Hamiltonian $\hat H$, the energy spread $\Delta E \equiv \Delta H$ and the characteristic time $\Delta t_A \equiv \Delta A/|d\langle\hat A\rangle/dt|$ over which $\langle\hat A\rangle$ shifts by one standard deviation satisfy
$$\Delta E \cdot \Delta t_A \geq \tfrac{\hbar}{2}.$$

The factor $i$ entering the Heisenberg evolution and the factor $\hbar$ multiplying it are the same $i$ and $\hbar$ that enter $dx_4/dt = ic$ and Theorem 4.1, transported through $\sigma$.

**Proof.**

*Step 1 (Heisenberg evolution).* For a Hermitian observable $\hat A$ in the Heisenberg picture, $\hat A(t) = \hat U^\dagger(t)\hat A\hat U(t)$ with $\hat U(t) = \exp(-i\hat H t/\hbar)$. Differentiating,
$$\frac{d\hat A}{dt} = \frac{i}{\hbar}[\hat H, \hat A].$$

Taking expectation in a state $|\psi\rangle$:
$$\frac{d\langle\hat A\rangle}{dt} = \frac{i}{\hbar}\langle\psi|[\hat H, \hat A]|\psi\rangle.$$

The factor $i$ is the same generator as in $dx_4/dt = ic$ by Theorem 3.1.

*Step 2 (Robertson applied to $\hat H, \hat A$).* Apply Lemma 5.1 to the pair $(\hat H, \hat A)$:
$$\Delta H \cdot \Delta A \geq \tfrac{1}{2}|\langle\psi|[\hat H, \hat A]|\psi\rangle| = \tfrac{\hbar}{2}\biggl|\frac{d\langle\hat A\rangle}{dt}\biggr|.$$

*Step 3 (rearrange).* Define $\Delta t_A \equiv \Delta A/|d\langle\hat A\rangle/dt|$. Then $\Delta H\cdot\Delta t_A \geq \hbar/2$, equivalently $\Delta E\cdot\Delta t_A \geq \hbar/2$.

*Step 4 (Pauli's obstruction circumvented, not contradicted).* Pauli's 1933 theorem excludes a self-adjoint $\hat T$ conjugate to a bounded-below $\hat H$. The proof above introduces no such $\hat T$: $\Delta t_A$ is the characteristic timescale of a covariant observable, defined as the ratio of two well-defined quantities. ∎

---

## 9. Displacement of Heisenberg's Microscope and Bohrian Complementarity

### Theorem 9.1 (Displacement of the microscope reading)

The kinematic theorems (3.2, 5.2, 6.1, 7.1, 8.1) establish that the canonical commutator, the uncertainty relation, the wavepacket spread, the ground-state saturation, and the time-energy relation all hold in the absence of any measurement apparatus, photon scattering, or act of observation.

**Proof.** The proofs of the five theorems invoke only the McGucken Principle, Frobenius rigidity, the suppression map $\sigma$, the Cauchy–Schwarz inequality, and the Compton-frequency identification. No step requires an apparatus, a photon, or a measurement event. ∎

### Theorem 9.2 (Displacement of the complementarity reading)

The kinematic theorems establish that the four foundational facts encode geometric facts about $x_4$-advance, independent of any choice of measurement context, observer, or definitional convention.

**Proof.** The proofs invoke no measurement context, no choice of observer, and no definitional convention about meaningful properties. The vacuum saturation case is decisive: $\Delta q\cdot\Delta p = \hbar/2$ holds for the ground state with no measurement context, and its observable consequences (Casimir force, Lamb shift) are inconsistent with the Bohrian denial that the vacuum has determinate $(q,p)$ structure to constrain. ∎

---

## 10. The Comprehensive Catalogue {#sec-catalogue}

The kinematic theorems of §§3–9 are not the full reach of the McGucken Principle. This section establishes twelve further foundational items in the same spirit, with all proofs given in full.

### 10.1 The constancy and frame-independence of $c$

### Theorem 10.1 (Frame-independence of $c$)

Let $\mathcal{O}$, $\mathcal{O}'$ be two observers in any state of relative motion. Both measure $|dx_4/dt| = c$ with the same numerical value.

**Proof.** The McGucken Principle is a statement about the four-dimensional manifold $M_E$ itself, not about any coordinate chart placed on $M_E$. Two observers in relative motion are two coordinate charts on the same $M_E$. The rate $|dx_4/dt|$ read in each chart is a reading of the manifold's intrinsic rate of $x_4$-expansion, hence equal in both charts. Equivalently in chart-relative form: if $\mathcal O$ at rest reads $u^\mu = (c,0,0,0)$ with $u^\mu u_\mu = -c^2$, and $\mathcal O'$ in relative motion at velocity $v$ reads $u'^\mu = (\gamma c, \gamma v, 0, 0)$, then $u'^\mu u'_\mu = -\gamma^2 c^2 + \gamma^2 v^2 = -\gamma^2 c^2(1 - v^2/c^2) = -c^2$, preserved exactly. ∎

### Corollary 10.2 (Photons at absolute rest in $x_4$)

A massless particle has $dx_4/dt = 0$ along its null worldline.

**Proof.** The four-velocity budget $u^\mu u_\mu = -c^2$ partitions the total rate $c$ between spatial motion and $x_4$-advance. For a photon, $|d\vec x/dt| = c$ exhausts the spatial budget; the $x_4$-component is therefore zero. ∎

### 10.2 The foundational asymmetry of $i$

### Theorem 10.3 (Foundational asymmetry)

The McGucken Principle distinguishes the $+ic$ direction from the $-ic$ direction. No deformation preserving Lorentzian signature, unitarity, and CPT permits the rate to take the value $-ic$ at any event.

**Proof.** The principle commits $M_E$ to the orientation $+ic$ at every event; $-ic$ is the complex-conjugate generator (reverse rotation in the $(t,x_4)$ plane). A universe with $-ic$ at some events and $+ic$ at others would not satisfy a single principle of the manifold. Consistency with Greenberg's 2002 theorem (CPT violation implies Lorentz violation) is automatic since the orientation is universal. ∎

### 10.3 The CHSH and Tsirelson bounds

### Theorem 10.4 (Tsirelson bound)

For two spatially separated observers each making one of two binary $\pm 1$-valued measurements on entangled spin-$\tfrac{1}{2}$ pairs, with measurement operators $A_1, A_2$ on observer A's system and $B_1, B_2$ on observer B's system (all self-adjoint with $A_i^2 = B_j^2 = \mathbb{1}$), the CHSH operator
$$\widehat C = A_1\otimes B_1 + A_1\otimes B_2 + A_2\otimes B_1 - A_2\otimes B_2$$
satisfies $|\langle\widehat C\rangle| \leq 2\sqrt{2}$, the Tsirelson upper bound. Local hidden-variable theories satisfy $|\langle\widehat C\rangle|_{\mathrm{LHV}} \leq 2$, the Bell inequality.

**Proof.**

*Step 1 (singlet correlation).* The two-spin singlet state is $|\Psi^-\rangle = (|\!\!\uparrow\downarrow\rangle - |\!\!\downarrow\uparrow\rangle)/\sqrt 2$. For Pauli measurement $A = \hat a\cdot\vec\sigma$ on observer A and $B = \hat b\cdot\vec\sigma$ on observer B, with unit vectors $\hat a, \hat b\in S^2$, direct computation in the $\hat z$-eigenbasis gives
$$E(\hat a, \hat b) \equiv \langle\Psi^-|A\otimes B|\Psi^-\rangle = -\hat a\cdot\hat b = -\cos\theta_{ab}.$$

*Step 2 (CHSH expectation).* Substituting,
$$\langle\widehat C\rangle = -\hat a_1\cdot\hat b_1 - \hat a_1\cdot\hat b_2 - \hat a_2\cdot\hat b_1 + \hat a_2\cdot\hat b_2.$$

Maximize over unit vectors. Coplanar choice $\hat a_1 = \hat x$, $\hat a_2 = \hat y$, $\hat b_{1,2} = \cos\beta_{1,2}\,\hat x + \sin\beta_{1,2}\,\hat y$ gives $\langle\widehat C\rangle = -\cos\beta_1 - \cos\beta_2 - \sin\beta_1 + \sin\beta_2$. Critical-point analysis yields the maximum at $\beta_1 = -\pi/4$, $\beta_2 = \pi/4$ giving $|\langle\widehat C\rangle| = 2\sqrt 2$, attainable.

*Step 3 (Tsirelson identity).* Define $A_\pm = A_1 \pm A_2$, $B_\pm = B_1 \pm B_2$. Then $\widehat C = A_1\otimes B_+ + A_2\otimes B_-$. Compute
$$\widehat C^2 = A_1^2\otimes B_+^2 + A_2^2\otimes B_-^2 + \{A_1, A_2\}\otimes B_+ B_-.$$

Using $A_i^2 = \mathbb 1$:
$$A_1^2\otimes B_+^2 = \mathbb 1\otimes(B_1+B_2)^2 = \mathbb 1\otimes(2\mathbb 1 + \{B_1,B_2\}),$$
$$A_2^2\otimes B_-^2 = \mathbb 1\otimes(B_1-B_2)^2 = \mathbb 1\otimes(2\mathbb 1 - \{B_1,B_2\}).$$

Sum: $\mathbb 1\otimes 4\mathbb 1 = 4\,\mathbb 1\otimes\mathbb 1$. Cross term: $B_+B_- = -[B_1,B_2]$. Therefore
$$\widehat C^2 = 4\,\mathbb 1\otimes\mathbb 1 - [A_1,A_2]\otimes[B_1,B_2].$$

*Step 4 (commutator-norm bounds).* For self-adjoint $A_i$ with $A_i^2 = \mathbb 1$ (eigenvalues $\pm 1$), $\|A_i\| = 1$:
$$\|[A_1, A_2]\| \leq \|A_1 A_2\| + \|A_2 A_1\| \leq 2\|A_1\|\|A_2\| = 2.$$

For Pauli observables, $[\hat a_1\cdot\vec\sigma, \hat a_2\cdot\vec\sigma] = 2i(\hat a_1\times\hat a_2)\cdot\vec\sigma$, with norm $2|\hat a_1\times\hat a_2| \leq 2$.

*Step 5 (operator-norm conclusion).* Take operator norms:
$$\|\widehat C^2\| \leq 4 + \|[A_1,A_2]\|\cdot\|[B_1,B_2]\| \leq 4 + 2\cdot 2 = 8.$$

Since $\widehat C$ is self-adjoint, $\|\widehat C\| = \sqrt{\|\widehat C^2\|} \leq \sqrt 8 = 2\sqrt 2$. Therefore $|\langle\widehat C\rangle| \leq \|\widehat C\| \leq 2\sqrt 2$.

*Step 6 (LHV bound).* For local hidden variables, each $A_i, B_j$ takes value $\pm 1$ deterministically. Define $C(\lambda) = a_1(b_1+b_2) + a_2(b_1-b_2)$ where $a_i, b_j\in\{-1,+1\}$. Either $b_1 = b_2$ (then $C = 2a_1 b_1\in\{-2,+2\}$) or $b_1 = -b_2$ (then $C = 2a_2 b_1\in\{-2,+2\}$). Either way $|C(\lambda)| \leq 2$, so $|\int C(\lambda) p(\lambda)d\lambda| \leq 2$. ∎

### Theorem 10.5 (Bell-inequality violation via shared McGucken Sphere)

Spatially separated entangled systems prepared at a common spacetime source event share a single McGucken Sphere structure and exhibit correlations that violate the Bell inequalities, mediated by $x_4$ rather than by faster-than-light spatial signaling.

**Proof.** By Theorem 10.4 Step 1, the singlet state on a system prepared at common source event $E$ produces correlation $E(\hat a, \hat b) = -\cos\theta_{ab}$. The CHSH expectation reaches $2\sqrt 2$ at the optimal-angle choice. Each entangled pair carries the McGucken Sphere $\mathcal{M}_E(t)$ centred on $E$: the wavefront of the $x_4$-expansion emanating from the common source. Subsequent cross-section-localizable detection events lie on this single Sphere. Bell-inequality violation is therefore not a violation of relativity but evidence that the universe is four-dimensional in the McGucken sense, with $x_4$ perpendicular to the spatial three. ∎

### 10.4 The double-slit experiment and the forward-conjugate $x_4$-overlap

### Definition 10.6 (McGucken Sphere)

For an event $E$ and proper time $t$, the McGucken Sphere $\mathcal{M}_E(t) = \{p : ds^2(E,p) = 0,\ x_4(p) - x_4(E) = ict\}$ is the wavefront of the $x_4$-expansion emanating from $E$.

### Theorem 10.7 (Huygens identity)

For a particle of rest mass $m$ at event $E$, the spatial-slice wavefront at proper time $\Delta t$ is the sphere $|\vec x - \vec x_E| = c\,\Delta t$, the $\sigma$-image of $\mathcal{M}_E(\Delta t)$.

**Proof.** By Lemma 2.6, $|\Delta x_4| = c\,\Delta t$. The McGucken Sphere is the locus of events at $x_4$-distance $c\,\Delta t$ from $E$; under $\sigma$, this projects onto the sphere $|\vec x - \vec x_E| = c\,\Delta t$ in the spatial slice $\{t = t_E + \Delta t\}$, the Huygens secondary wavefront. ∎

### Theorem 10.8 (Forward-conjugate $x_4$-overlap as the source of interference)

The interference cross-terms $\psi_1^*\psi_2 + \psi_2^*\psi_1$ in $|\psi_1 + \psi_2|^2$ are the geometric overlap, at the screen, of forward $+ic$ expansion (carried by $\psi$) and conjugate $-ic$ expansion (carried by $\psi^*$).

**Proof.**

*Step 1 (path-integral phase from the Principle).* For a path $\gamma$ from source to detection event $B$, the action $S[\gamma] = -mc^2\int_\gamma d\tau$ accumulates $x_4$-displacement $\Delta x_4|_\gamma = ic\,\Delta\tau_\gamma$. The phase per Compton-period oscillation is $\hbar$, giving the path amplitude $A[\gamma] = \exp(iS[\gamma]/\hbar)$. The factor $i$ is the $\sigma$-chain-rule transport of the imaginary $x_4$-displacement.

*Step 2 (Born product as double sum).* The probability density at $B$ is $P(B) = \psi^*(B)\psi(B)$ where $\psi(B) = \int\mathcal D[\gamma]\exp(iS[\gamma]/\hbar)$ and $\psi^*(B) = \int\mathcal D[\gamma']\exp(-iS[\gamma']/\hbar)$. Their product
$$P(B) = \int\!\!\int\mathcal D[\gamma]\mathcal D[\gamma']\exp(i(S[\gamma] - S[\gamma'])/\hbar)$$
is a double sum over forward paths $\gamma$ ($+ic$) and conjugate paths $\gamma'$ ($-ic$).

*Step 3 (two-slit specialization).* For $\psi = \psi_1 + \psi_2$ with $\psi_k$ summing paths through slit $k$,
$$P = |\psi_1|^2 + |\psi_2|^2 + \psi_1^*\psi_2 + \psi_2^*\psi_1.$$

The cross term $\psi_1^*\psi_2 = \int\!\!\int\mathcal D[\gamma_1']\mathcal D[\gamma_2]\exp(i(S[\gamma_2] - S[\gamma_1'])/\hbar)$ is forward $+ic$ propagation through slit 2 overlapping with conjugate $-ic$ propagation through slit 1.

*Step 4 (Wick cross-check).* Replacing $dx_4/dt = ic$ by a real rate (removing $i$) converts the path weight to $\exp(-S_E/\hbar)$ with no conjugate orientation, eliminates $\psi^*$ as a structurally distinct object, and removes the cross terms. Classical diffusion exhibits no fringes; quantum interference is the signature of the principle's complex character. ∎

### Corollary 10.9 ("Which slit" detection collapses the cross-overlap)

A measurement that localizes the source event in $x_1 x_2 x_3$ at $E_k$ projects only the local Huygens patch through slit $k$, eliminating the cross terms and recovering the classical-particle distribution.

### 10.5 Spin-$\tfrac{1}{2}$ and the SU(2) double cover

### Definition 10.10 (Condition (M))

Matter, by the McGucken Principle, is an $x_4$-standing wave with phase accumulating at the Compton frequency $\omega_C = mc^2/\hbar$. In the spacetime Clifford algebra $\mathrm{Cl}(1,3)$ with pseudoscalar $I = \gamma_0\gamma_1\gamma_2\gamma_3$ satisfying $I^2 = -1$, the matter-orientation condition is
$$\Psi(\vec x, x_4) = \Psi_0(\vec x)\cdot\exp(+I\cdot k\, x_4), \qquad k = mc/\hbar > 0,$$
with multiplication on the right.

### Lemma 10.11 (Single-Sided Preservation Lemma)

For a rotor $R = \exp(\theta/2\cdot e_P)$ generated by a spatial bivector $e_P\in\{e_{12}, e_{23}, e_{31}\}$ and any $\Psi$ satisfying Condition (M):
(a) left-action $\Psi\to R\Psi$ preserves Condition (M);
(b) sandwich action $\Psi\to R^{-1}\Psi R$ does not preserve Condition (M) when $R$ extends to bivectors involving $x_4$ (specifically, $e_{i4}$ for $i\in\{1,2,3\}$).

**Proof.**

*(a) Spatial bivectors commute with $\exp(I\cdot kx_4)$.* For $e_P\in\{e_{12}, e_{23}, e_{31}\}$, $e_P$ is a product of two spatial gammas. The pseudoscalar $I$ contains all four gammas. By the anticommutation rules, $[e_{12}, I] = 0$, and similarly for $e_{23}, e_{31}$. Therefore $R = \exp(\theta/2\cdot e_P)$ commutes with $\exp(I\cdot kx_4)$. Left-action: $R\Psi = (R\Psi_0)\exp(I\cdot kx_4)$. The matter-orientation factor is preserved.

*(b) Mixed bivector $e_{14}$.* Direct computation in $\mathrm{Cl}(1,3)$ yields $[e_{14}, I] = -2\gamma_2\gamma_3 \neq 0$. The mixed-bivector rotor does not commute with the matter-orientation factor.

*Sandwich action consequence.* $R^{-1}\Psi R = R^{-1}\Psi_0\exp(I\cdot kx_4) R$. With $[R, I]\neq 0$, the rotor partially converts the orientation factor to its conjugate $\exp(-I\cdot kx_4)$, which corresponds to antimatter, not matter. Sandwich action with mixed-bivector rotors therefore violates Condition (M). ∎

### Theorem 10.12 (Spin-$\tfrac{1}{2}$ from Condition (M))

Matter fields satisfying Condition (M) transform under spatial rotation by single-sided rotor action $\psi\to R\psi$, $R = \exp(\theta/2\cdot e_P)$, producing the half-angle spinor transformation, the SU(2) double cover, and the $4\pi$-periodicity.

**Proof.**

*Step 1 (single-sided action forced).* By Lemma 10.11, only single-sided action preserves Condition (M); sandwich action with mixed-bivector rotors converts matter to antimatter.

*Step 2 (half-angle).* The rotor $R = \exp(\theta/2\cdot e_{12}) = \cos(\theta/2) + \sin(\theta/2)\cdot e_{12}$ acts as $\psi\to[\cos(\theta/2) + \sin(\theta/2)e_{12}]\psi$. A full classical rotation $\theta = 2\pi$ produces $R(2\pi) = \cos\pi + \sin\pi\cdot e_{12} = -1$, mapping $\psi\to -\psi$. A double rotation $\theta = 4\pi$ produces $R(4\pi) = +1$.

*Step 3 (SU(2) double cover).* The single-sided rotor algebra is the even subalgebra of $\mathrm{Cl}(3)$, isomorphic to the quaternions $\mathbb H$, equivalently to $\mathrm{SU}(2)$. The natural projection $\mathrm{SU}(2)\to\mathrm{SO}(3)$ via $R\to R\cdot R^{-1}$ is two-to-one ($R$ and $-R$ map to the same $\mathrm{SO}(3)$ rotation), establishing the double cover.

*Step 4 (charge conjugation as right-multiplication).* Antimatter corresponds to right-multiplication: $\Psi^{(\text{anti})} = \Psi_0\cdot\exp(-I\cdot kx_4)$. Direct verification on the rest-frame spin-up electron $u_+ = (1,0,1,0)^T\cdot e^{-imc^2t/\hbar}$ under $C\gamma^0\psi^*$ gives the rest-frame spin-up positron, identical to the right-multiplication result.

*Step 5 (Compton-locking).* The rotor frequency $\Omega$ that effects $\theta = 2\pi$ in time $T_C/2$ gives $\Omega = \omega_C/2$. Matter rotates at half the Compton frequency in the spinor representation.

*Step 6 (verification).* Werner–Rauch confirm the $4\pi$-periodicity experimentally on neutrons.

*Step 7 (three pseudoscalars unified).* The $i$ in $dx_4/dt = ic$, the Clifford pseudoscalar $I$, and the spatial bivectors $e_{ij}$ are unified: complex $i$ is the algebraic shadow of $I$, which is the algebraic shadow of $x_4$'s perpendicularity to the spatial three. ∎

### 10.6 Quantum tunneling and the universal tunneling time

### Theorem 10.13 (Imaginary momentum is $x_4$-momentum)

Inside a potential barrier where classical motion is forbidden, the particle's barrier-perpendicular momentum on the spatial slice is purely imaginary, and is the $\sigma$-image of real $x_4$-momentum on $M_E$.

**Proof.** For energy $E < V_0$, the Schrödinger equation gives $\psi(x)\propto\exp(-\kappa x)$ with $\kappa = \sqrt{2m(V_0-E)}/\hbar$, hence momentum eigenvalue $p = i\hbar\kappa$, purely imaginary. By Definition 2.4, $\sigma$ sends $\partial/\partial t\to ic\,\partial/\partial x_4$; any factor of $i$ in a momentum-conjugate variable is the $\sigma$-image of an $x_4$-derivative. The imaginary $p = i|p|$ is therefore the $\sigma$-image of real $x_4$-momentum $p_{x_4} = |p|$. ∎

### Theorem 10.14 (Universal tunneling time)

The tunneling time for a particle of rest mass $m$ traversing any potential barrier is $t_{\text{tunnel}} = t_C = \hbar/(mc^2)$, independent of barrier thickness (Hartman effect).

**Proof.** By Theorem 10.13, during traversal the particle advances along $x_4$ rather than along the barrier-perpendicular spatial direction. By Theorem 4.1, the minimum proper time for an $x_4$-advance to register on the spatial slice is $t_C$, the Compton period. The barrier thickness in $x_1x_2x_3$ does not enter because the traversal occurs in $x_4$. The Hartman effect (saturation with thickness) is the kinematic content. ∎

### 10.7 Hawking temperature, area law, and $\eta = 1/4$

### Theorem 10.15 (Hawking temperature)

The temperature of a Schwarzschild black hole is $T_H = \hbar c^3/(8\pi GMk_B)$.

**Proof.**

*Step 1 (Wick rotation as coordinate identification).* On the McGucken manifold, $\tau \equiv x_4/c$ gives, with $x_4 = ict$, the relation $t = -i\tau$. Substituting in the Schwarzschild line element
$$ds^2 = -f(r)c^2 dt^2 + f(r)^{-1}dr^2 + r^2 d\Omega_2^2, \quad f(r) = 1 - 2GM/(c^2 r),$$
gives the Euclidean Schwarzschild metric
$$ds_E^2 = f(r)c^2 d\tau^2 + f(r)^{-1}dr^2 + r^2 d\Omega_2^2.$$

*Step 2 (near-horizon proper-distance coordinate).* Near $r_s = 2GM/c^2$, set $\rho^2 \equiv 4 r_s^2 f(r) c^2/\kappa^2$ where $\kappa = c^4/(4GM)$ is the surface gravity. Direct expansion: $f(r)\approx (r-r_s)/r_s$ near horizon. The line element becomes
$$ds_E^2 \approx \rho^2 d\theta_E^2 + d\rho^2 + r_s^2 d\Omega_2^2$$
where $\theta_E \equiv \kappa\tau/c$.

*Step 3 (conical-singularity avoidance).* The first two terms are the Euclidean plane in polar coordinates. Smoothness at $\rho = 0$ requires $\theta_E$ to have period $2\pi$. The corresponding period in $\tau$ is
$$\beta_{\text{geom}} = \frac{2\pi c}{\kappa} = \frac{8\pi GM}{c^3}.$$

*Step 4 (KMS condition).* Quantum field theory on a thermal background at temperature $T$ has Euclidean correlation functions periodic in imaginary time with period $\beta = \hbar/(k_B T)$. Equating $\beta_{\text{geom}} = \hbar/(k_B T_H)$:
$$T_H = \frac{\hbar c^3}{8\pi GM k_B}. \qquad \blacksquare$$

### Theorem 10.16 (Area law and $\eta = 1/4$)

The Bekenstein–Hawking entropy is $S_{BH} = k_B A/(4\ell_P^2)$ with $\ell_P = \sqrt{\hbar G/c^3}$.

**Proof.**

*Step 1 (area scaling).* Near the horizon, modes whose Compton-frequency $x_4$-advance matches the gravitational kinematic constraint are confined to the 2-surface of horizon area $A$, not the bulk 3-volume. Counting modes at Planck-area resolution gives $N \propto A/\ell_P^2$, hence $S\propto A$.

*Step 2 (first law to fix $\eta$).* The black-hole first law $dE = T_H\,dS$ with $E = Mc^2$ and $T_H$ from Theorem 10.15:
$$c^2 dM = \frac{\hbar c^3}{8\pi GMk_B}\,dS,$$
giving
$$dS = \frac{8\pi G M k_B}{\hbar c}\,dM = \frac{4\pi G k_B}{\hbar c}\,d(M^2).$$

Integrating from $M = 0$:
$$S_{BH} = \frac{4\pi G M^2 k_B}{\hbar c}.$$

Using $A = 4\pi r_s^2 = 16\pi G^2 M^2/c^4$, hence $M^2 = Ac^4/(16\pi G^2)$:
$$S_{BH} = \frac{4\pi G k_B}{\hbar c}\cdot\frac{Ac^4}{16\pi G^2} = \frac{Ac^3 k_B}{4\hbar G} = \frac{k_B A}{4\ell_P^2}. \qquad \blacksquare$$

### 10.8 The Born rule and the Hilbert space

### Theorem 10.17 (Born rule from $dx_4/dt = ic$)

The probability of measurement outcome at position $\vec x$ on a normalized McGucken wavefunction $\psi(\vec x)$ is $P(\vec x) = |\psi(\vec x)|^2$, established through Sub-theorems I–IV proved below.

#### Sub-theorem I: Complex amplitudes from $dx_4/dt = ic$

### Lemma 10.18 (Complex amplitudes)

The McGucken wavefunction $\psi$ is intrinsically complex-valued, with phase generated by the factor $i$ in the integrated form $x_4 = ict$.

**Proof.** By Lemma 2.6, the four-displacement from event $E$ to a point on $\mathcal{M}_E(t)$ is $\Delta X = (\vec x, ict)$ with norm $\|\Delta X\|^2 = |\vec x|^2 - c^2t^2 = 0$ on the null wavefront. The $x_4$-component is purely imaginary because $x_4$ is perpendicular to $\mathbb R^3$, with $i$ marking that perpendicularity. The action along a path $\gamma$ from $E$ to $B\in\mathcal{M}_E(t)$ is $S[\gamma] = -mc^2\int_\gamma d\tau$, with phase contribution $\exp(iS[\gamma]/\hbar)$ inheriting the $i$ from the imaginary $x_4$-displacement (Theorems 3.1, 4.1). Removing $i$ from $x_4$ converts $\exp(iS/\hbar)$ to $\exp(S/\hbar)$, the Wick-rotated Euclidean weight. The presence of $i$ is what makes amplitudes complex. ∎

#### Sub-theorem II: Squared modulus by Cauchy functional equation

### Lemma 10.19 (Squared modulus by Cauchy functional equation)

The unique smooth, phase-invariant, additive-on-orthogonal-superposition density on the space of complex amplitudes is $P(\psi) = C|\psi|^2$ for some constant $C > 0$.

**Proof.**

*Step 1 (phase invariance).* By the homogeneity of the $x_4$-expansion (which emanates from every event with the same rate $ic$), a global phase $\psi\to e^{i\alpha}\psi$ is unobservable. Hence $P(\psi) = P(e^{i\alpha}\psi)$ for all $\alpha\in\mathbb R$, implying $P$ is a function of $|\psi|$ only: $P(\psi) = g(|\psi|)$.

*Step 2 (smoothness rules out $|\psi|$).* The function $|\psi| = \sqrt{\psi^*\psi}$ is not smooth at $\psi = 0$. For $P$ to be a smooth function of $\psi$ and $\psi^*$, $g$ must be a smooth function of $|\psi|^2$, not of $|\psi|$ itself. Therefore $P(\psi) = h(|\psi|^2)$ for some smooth $h:[0,\infty)\to\mathbb R$ with $h(0) = 0$.

*Step 3 (additivity on orthogonal superposition).* For two orthogonal states $\psi_1, \psi_2$ and complex coefficients $c_1, c_2$ with $|c_1|^2 + |c_2|^2 = 1$, the superposition $\psi = c_1\psi_1 + c_2\psi_2$ has total probability satisfying $P(\psi) = |c_1|^2 P(\psi_1) + |c_2|^2 P(\psi_2)$ (the law of total probability for mutually exclusive outcomes; orthogonality means the events are mutually exclusive). Substituting $h$:
$$h(|c_1|^2|\psi_1|^2 + |c_2|^2|\psi_2|^2) = h(|c_1|^2|\psi_1|^2) + h(|c_2|^2|\psi_2|^2).$$

This is the Cauchy functional equation $h(x + y) = h(x) + h(y)$ on $[0,\infty)$.

*Step 4 (smooth solutions of Cauchy's equation are linear).* A smooth function $h:[0,\infty)\to\mathbb R$ satisfying $h(x+y) = h(x) + h(y)$ for all $x, y\geq 0$ with $h(0) = 0$ must be linear: $h(x) = Cx$. Proof: differentiate both sides with respect to $x$ to obtain $h'(x+y) = h'(x)$, and similarly $h'(x+y) = h'(y)$, so $h'(x) = h'(y)$ for all $x, y\geq 0$. Hence $h'$ is constant, $h'(x) = C$. Integrating with $h(0) = 0$ gives $h(x) = Cx$.

*Step 5 (positive constant).* $C > 0$ for $P$ to be non-negative and non-trivial. Therefore $P(\psi) = C|\psi|^2$. Normalization $\int|\psi|^2 d^3x = 1$ fixes $C = 1$. ∎

#### Sub-theorem II$'$: Squared modulus by rank-2 Minkowski metric bilinearity

### Lemma 10.20 (Bilinearity of $x_4$-flux)

The $x_4$-flux density at any event $B\in\mathcal{M}_E(t)$ is bilinear in $(\psi, \psi^*)$.

**Proof.** The $x_4$-flux density at $B$ is the geometric overlap of forward $x_4$-advance with conjugate $x_4$-advance at $B$ (Theorem 10.8). The forward advance carries four-velocity $u_{\text{fwd}}$ with $x_4$-component $+ic$; the conjugate carries $u_{\text{conj}}$ with $x_4$-component $-ic$. The overlap is the Minkowski inner product
$$\Phi_{x_4}(B) = g_{\mu\nu}\,u_{\text{fwd}}^\mu\,u_{\text{conj}}^\nu,$$
where $g_{\mu\nu}$ is the metric induced by $x_4 = ict$ via $(ict)^2 = -c^2t^2$, hence $\eta_{00} = -c^2$, $\eta_{ii} = 1$. The metric is rank 2: it pairs two vectors and produces a scalar. By the definition of a rank-2 tensor, the pairing is bilinear in $(u_{\text{fwd}}, u_{\text{conj}})$. In the amplitude representation, $u_{\text{fwd}}\leftrightarrow\psi$ and $u_{\text{conj}}\leftrightarrow\psi^*$, so $\Phi_{x_4}(B)$ is bilinear in $(\psi, \psi^*)$. Higher-order forms are excluded because the metric inherited from $dx_4/dt = ic$ is rank 2, not rank 4 or higher. ∎

### Lemma 10.21 (Born rule by rank-2 metric route)

On the McGucken Sphere $\mathcal{M}_E(t)$, the unique density satisfying (R1) reality, (R2) non-negativity, (R3) phase-invariance under global $x_4$-shift, (R4) bilinearity in $(\psi,\psi^*)$, and normalization is $P = |\psi|^2$.

**Proof.** By Lemma 10.20, (R4) is supplied by the rank-2 Minkowski metric. The most general bilinear form in $(\psi, \psi^*)$ is
$$P(\psi) = a\psi^2 + (b+c)\psi^*\psi + d(\psi^*)^2.$$

Under (R3), $\psi\to e^{i\alpha}\psi$ gives $\psi^2\to e^{2i\alpha}\psi^2$, $\psi^*\psi\to\psi^*\psi$, $(\psi^*)^2\to e^{-2i\alpha}(\psi^*)^2$. Phase invariance for all $\alpha$ forces $a = d = 0$, leaving $P = C\psi^*\psi$ with $C = b+c$. (R1) forces $C\in\mathbb R$. (R2) forces $C\geq 0$; non-degeneracy forces $C > 0$. Normalization fixes $C = 1$. Hence $P(\vec x) = |\psi(\vec x)|^2$. ∎

#### Sub-theorem III: $\psi^*\psi$ as forward-conjugate $x_4$-overlap

### Lemma 10.22 (Geometric meaning of the Born rule)

The Born density $P = \psi^*\psi$ at an event $B$ is the geometric overlap, at $B$, of the forward $x_4$-expansion (carrying phase from $x_4 = ict$) and the conjugate $x_4^*$-expansion (carrying phase from $x_4^* = -ict$).

**Proof.** The propagator is $K(B,A) = \int\mathcal D[\gamma]\exp(iS[\gamma]/\hbar)$. The conjugate propagator is $K^*(B,A) = \int\mathcal D[\gamma]\exp(-iS[\gamma]/\hbar)$. Their product
$$P(A\to B) = K^*(B,A)K(B,A) = \int\!\!\int\mathcal D[\gamma]\mathcal D[\gamma']\exp(i(S[\gamma]-S[\gamma'])/\hbar)$$
is a double sum over forward paths ($+ic$) and conjugate paths ($-ic$), evaluated at $B$. ∎

#### Sub-theorem IV: The Hilbert space $\mathcal{H}\cong L^2(M_{1,3}, d\mu_M)$

### Lemma 10.23 (Hilbert space construction)

The Hilbert space of quantum mechanics is the Cauchy completion of the pre-Hilbert space of complex-valued square-integrable amplitudes over the McGucken-derived Lorentzian spacetime, with inner product induced by the Born density.

**Proof.**

*Step 1 (Lorentzian spacetime as constraint surface).* The McGucken constraint $\Phi_M = x_4 - ict$ vanishes on worldlines satisfying the Principle. The line element on the Euclidean manifold $M_E$ is $d\ell^2 = dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2$. Substituting $dx_4^2 = (ic\,dt)^2 = -c^2 dt^2$ gives the Lorentzian interval $ds^2 = dx_1^2 + dx_2^2 + dx_3^2 - c^2 dt^2$. The Lorentzian spacetime $M_{1,3}$ is therefore $\Phi_M^{-1}(0)$, generated by the Principle.

*Step 2 (complex amplitudes by ontic necessity).* A scalar field $\psi:M_{1,3}\to\mathbb C$. By Lemma 10.18, the complex character is forced. The complex algebra $\mathbb C = \mathbb R + i\mathbb R$ is the unique two-real-dimensional algebra (Frobenius rigidity, Lemma 2.3) encoding $x_4$'s perpendicularity. The space of such fields is $\mathcal V = \{\psi:M_{1,3}\to\mathbb C\}$.

*Step 3 (Born inner product).* Restrict to square-integrable amplitudes,
$$\mathcal V_2 = \Big\{\psi\in\mathcal V\,\Big|\,\int_{\mathbb R^3}|\psi(\vec x, t)|^2\,d^3x < \infty\text{ for every }t\Big\},$$
and define
$$\langle\phi, \psi\rangle = \int_{\mathbb R^3}\phi^*(\vec x, t)\psi(\vec x, t)\,d^3x.$$

The three inner-product axioms follow:

**(i) Conjugate symmetry.** $\langle\psi, \phi\rangle = \int\psi^*\phi\,d^3x = \overline{\int\phi^*\psi\,d^3x} = \overline{\langle\phi,\psi\rangle}$.

**(ii) Sesquilinearity.** For $\alpha, \beta\in\mathbb C$ and $\psi_1, \psi_2\in\mathcal V_2$, $\langle\phi, \alpha\psi_1 + \beta\psi_2\rangle = \alpha\langle\phi, \psi_1\rangle + \beta\langle\phi, \psi_2\rangle$. Conjugate-linearity in the first argument follows by (i).

**(iii) Positive-definiteness.** $\langle\psi, \psi\rangle = \int|\psi|^2 d^3x \geq 0$ by Sub-theorem II/II$'$. Equality holds iff $\psi = 0$ almost everywhere; modding out the null subspace $\mathcal N$ gives strict positive-definiteness on $\mathcal V_2/\mathcal N$.

*Step 4 (Cauchy completion).* The pre-Hilbert space $(\mathcal V_2/\mathcal N, \langle\cdot,\cdot\rangle)$ is completed in the norm $\|\psi\| = \sqrt{\langle\psi,\psi\rangle}$. By the Riesz–Fischer theorem of 1907, the Cauchy completion is the $L^2$-space of that measure space:
$$\mathcal H \cong L^2(M_{1,3}, d\mu_M),$$
where $d\mu_M$ is the McGucken measure given on each spatial slice by the Lebesgue measure $d^3x$. The Riesz–Fischer theorem is a real-analytic tool, not a quantum-mechanical assumption. ∎

**Proof of Theorem 10.17.** Sub-theorems I (Lemma 10.18), II (Lemma 10.19), II$'$ (Lemmas 10.20, 10.21), III (Lemma 10.22), and IV (Lemma 10.23) jointly establish that on the McGucken-derived Hilbert space $\mathcal H$, the unique probability density satisfying (R1)–(R4) and normalization is $P(\vec x) = |\psi(\vec x)|^2$. ∎

#### Why every prior program failed to derive $\mathcal{H}$

Eleven prior programs took $\mathcal H$ as input: **von Neumann (1932), Dirac (1958)** as starting axiom; **Mackey** as algebraic conjecture from a lattice of propositions; **Piron–Solèr** as lattice-theoretic restriction yielding $\mathcal H$ from orthomodular orthocomplemented atomistic lattices; **Jordan–von Neumann–Wigner** as Jordan-algebra classification yielding $\mathcal H$ as one option among several; **Hardy (2001), Chiribella–D'Ariano–Perinotti** as operational reconstruction from probability-theoretic axioms; **Abramsky–Coecke** as categorical characterization; **Stueckelberg** as equivalence theorem; **Adler** as quaternionic alternative requiring extra assumptions; **Renou et al. (2021)** as experimental confirmation. None operates upstream of the complex Hilbert-space structure itself.

| Formal feature of $\mathcal H$ | Physical content under $dx_4/dt = ic$ |
|---|---|
| Vector $\psi\in\mathcal H$ | Wavefront in $M_{1,3}$ advancing along $x_4$ at rate $ic$ |
| Inner product $\langle\phi,\psi\rangle$ | Forward-conjugate $x_4$-overlap, integrated over a spatial slice |
| Unit norm $\|\psi\|^2 = 1$ | Conservation of $x_4$-flux through the McGucken Sphere |
| Unitary evolution $U(t) = e^{-iHt/\hbar}$ | Temporal flow of $x_4$-advance at the system's rate |
| Complex structure of $\mathcal H$ | Perpendicularity of $x_4$ to spatial three, transported through $\sigma$ |
| Orthogonality $\langle\phi,\psi\rangle = 0$ | Vanishing forward-conjugate $x_4$-overlap of distinct wavefronts |
| $\dim\mathcal H$ | Number of geometrically independent $x_4$-rotation modes |

**The four twentieth-century blocks.** Each prior program was committed to at least one of: (i) block-universe Minkowski reading where coordinates do not have rates of change, making $dx_4/dt$ look like a category error; (ii) formalist interpretation of $i$ as a notational convenience; (iii) treating $c$ and $\hbar$ as independent inputs from separate theories; (iv) the interpretation industry that takes $\mathcal H$ as inviolable. The McGucken framework refuses all four.

**Bottom line.** Before McGucken, $\mathcal H$ was an axiom (von Neumann, Dirac), an algebraic conjecture (Mackey), a lattice-theoretic restriction (Piron, Solèr), a Jordan-algebra classification (JNW), an operational reconstruction (Hardy, CDP), a categorical characterization (Abramsky–Coecke), an equivalence theorem (Stueckelberg), an alternative-algebra exclusion (Adler), or an experimental confirmation (Renou et al.). After McGucken, $\mathcal H$ is a theorem of $dx_4/dt = ic$.

### 10.9 The universal appearance of $i$ across twelve canonical insertions

### Theorem 10.24 (Twelve canonical $i$-insertions unified)

The twelve canonical insertions of $i$ in physics are projections through the suppression map $\sigma$ of $dx_4/dt = ic$, classified by three mechanisms.

**Proof.**

**Case 1 (canonical quantization $\hat p\to -i\hbar\,\partial/\partial x$).** Plane-wave amplitude $\psi = \exp(ipx/\hbar)$ inherits $i$ from $\sigma$-transport. Differentiation gives $\partial_x\psi = (ip/\hbar)\psi$, hence $\hat p = -i\hbar\,\partial_x$. *Mechanism: $\sigma$-chain-rule factor.*

**Case 2 (Schrödinger equation $i\hbar\,\partial_t\psi = \hat H\psi$).** Time-evolution $\psi(t) = \exp(-i\hat H t/\hbar)\psi(0)$ has the same $i$ as Case 1, transported via $\partial/\partial t = ic\,\partial/\partial x_4$. *Mechanism: $\sigma$-chain-rule factor.*

**Case 3 (canonical commutator $[\hat q, \hat p] = i\hbar$).** Theorem 3.2 establishes the chain-rule transport. *Mechanism: $\sigma$-chain-rule factor.*

**Case 4 (Dirac equation $(i\gamma^\mu\partial_\mu - m)\psi = 0$).** The factor $i$ multiplies $\gamma^\mu\partial_\mu$ to give a real first-order operator on the Lorentzian manifold; under the suppression map, the signature change between Euclidean $M_E$ and Lorentzian $M_{1,3}$ produces this $i$. *Mechanism: $\sigma$-signature-change factor.*

**Case 5 (path integral $\exp(iS/\hbar)$).** As in Theorem 10.8 Step 1, the $i$ is the $\sigma$-image of the imaginary $x_4$-displacement $ic\,d\tau$. *Mechanism: $\sigma$-chain-rule factor.*

**Case 6 (Feynman propagator $+i\epsilon$).** Selects retarded boundary conditions corresponding to the $+ic$ orientation (Theorem 10.3). *Mechanism: $\sigma$-image of integration-contour structure.*

**Case 7 (Wick substitution $t\to -i\tau$).** $\tau\equiv x_4/c$ gives $t = -i\tau$ directly from $x_4 = ict$. The Wick rotation is coordinate identification on the McGucken manifold. *Mechanism: $\sigma$-chain-rule factor.*

**Case 8 (Fresnel-integral $\sqrt i$).** The stationary-phase approximation of $\int dx\exp(iS(x)/\hbar)$ produces $\sqrt{2\pi i\hbar/|S''|}$. *Mechanism: $\sigma$-image of integration-contour structure.*

**Case 9 (Minkowski–Euclidean action bridge $iS_M = -S_E$).** Under $t\to -i\tau$, $S_M = \int L\,dt$ becomes $iS_M = -\int L_E\,d\tau = -S_E$. *Mechanism: $\sigma$-chain-rule factor combined with signature change.*

**Case 10 ($U(1)$ gauge phase $\exp(i\theta)$).** The $i$ is the same generator as in $dx_4/dt = ic$. *Mechanism: $\sigma$-chain-rule factor on the gauge fibre.*

**Case 11 (Dirac spinors and SU(2) double cover).** Theorem 10.12 establishes the half-angle structure inherits the pseudoscalar $I$. *Mechanism: $\sigma$-image of pseudoscalar structure.*

**Case 12 (KMS condition $\langle A(t)B(0)\rangle = \langle B(0)A(t+i\hbar\beta)\rangle$).** The imaginary periodicity is the Wick-rotated thermal time. *Mechanism: $\sigma$-chain-rule factor with thermal periodicity.*

**Three-mechanism meta-classification.** The twelve cases fall into exactly three mechanisms: (a) $\sigma$-chain-rule factor (Cases 1, 2, 3, 5, 7, 9, 10, 12); (b) $\sigma$-signature-change factor (Cases 4, 11); (c) $\sigma$-image of integration-contour structure (Cases 6, 8). Frobenius rigidity (Lemma 2.3) establishes that the generator $i$ in all twelve cases is the same algebraic-geometric object. ∎

---

## 11. Empirical Discriminators

The kinematic reading and the standard treatments make different predictions in seven regimes.

**Regime 1 (QND measurements).** Back-action in the unprobed conjugate channel; predicted by Theorem 9.1; confirmed by Lvovsky 2009.

**Regime 2 (Free-evolution wavepacket spread).** Compton-scale rate $c/(2\sigma_q(0)/\ell_C)$ from $x_4$-advance (Theorem 6.1); Compton-coupling residual diffusion provides the discriminator.

**Regime 3 (Vacuum saturation).** Half-cycle action of $x_4$-rotation (Theorem 7.1). Casimir force and Lamb shift are observable consequences in absence of any apparatus.

**Regime 4 (Quantum tunneling).** Universal tunneling time $t_C = \hbar/(mc^2)$ (Theorem 10.14); distinct from Wigner phase time, dwell time, Larmor time.

**Regime 5 (Cosmological-distance entanglement).** Long-baseline Bell tests with gravitationally lensed entangled photon pairs.

**Regime 6 (Spin-correlation residuals).** Compton-frequency residuals in fermionic spin correlations.

**Regime 7 (Cosmological observations).** Twelve-test combined empirical first-place finish established in the cosmology paper companion.

---

## 12. Conclusion

The four foundational facts of non-relativistic quantum mechanics are not four facts but one fact viewed through four projections: the universal advance of $x_4$ at rate $ic$, projected onto the conjugate-pair plane (commutator), the variance product (uncertainty), the temporal evolution of widths (wavepacket spread), and the minimum-action ground state (zero-point saturation), with a fifth projection along $(t, x_4)$ giving the time-energy relation. The mechanism is the suppression map $\sigma$, the chain-rule identity $\partial/\partial t = ic\,\partial/\partial x_4$, with the rate fixed by the Compton angular frequency $\omega_C = mc^2/\hbar$.

The reading is ontic: the universe is not waiting for an observer to disturb it. The fourth coordinate is advancing at every event, accumulating action at rate $mc^2$ per system of rest mass $m$, and projecting onto the spatial slice through the algebraic-geometric mechanism that Frobenius's theorem licenses and that $\sigma$ formalizes. The vacuum is a continuously rotating four-dimensional medium whose minimum-uncertainty saturation $\Delta q\cdot\Delta p = \hbar/2$ is forced kinematically on the ground state of any quadratic Hamiltonian. The wavepacket spreads because $x_4$ rotates it. The ground state is the configuration in which the spatial-slice projection of $x_4$-advance is minimized at the system's natural frequency.

The catalogue of §10 extends this reach across twelve major foundational items, with all proofs given in full and self-contained. The four pillars of quantum mechanics — Born rule, Hilbert space, canonical commutator, uncertainty principle — thereby reduce to four theorems of one physical principle. Eleven prior programs (von Neumann, Dirac, Mackey, Piron–Solèr, JNW, Hardy, CDP, Abramsky–Coecke, Stueckelberg, Adler, Renou et al.) postulated, axiomatized, reconstructed, characterized, classified, or empirically confirmed $\mathcal H$. Before McGucken, $\mathcal H$ was an axiom; after McGucken, $\mathcal H$ is a theorem of $dx_4/dt = ic$.

This paper is self-contained: every theorem in §§2–11 is proved in full from $dx_4/dt = ic$ and the structures it generates, with the only external machinery being real analysis (Cauchy–Schwarz, Frobenius's classification of normed division algebras, Cauchy completion via the Riesz–Fischer theorem). The structural parallel between $dx_4/dt = ic$ and the four foundational facts is, in the kinematic reading, an identity. The universe is acting perpendicularly to the spatial slice, at rate $c$, in quanta of action $\hbar$, and the four foundational facts of non-relativistic quantum mechanics are its calling cards.

---

## Historical Note

The McGucken Principle traces to undergraduate research with John Archibald Wheeler at Princeton University in 1989–1990, third-floor Jadwin Hall, on the photon's stationarity in $x_4$ and Wheeler's directive that the QM–GR foundational gap close not by quantizing gravity but by finding a deeper principle that supplies both the geometry and the quantum. Quantum mechanics conversations with P. J. E. Peebles on the photon's spherically symmetric expansion at $c$ from every emission event, and experimental physics conversations with Joseph Taylor on entanglement as the characteristic trait of quantum mechanics, completed the Princeton triad. The first written formulation appeared as an appendix to the 1998 University of North Carolina Ph.D. dissertation. Bohr noted the structural parallel between $dx_4/dt = ic$ and $[\hat q, \hat p] = i\hbar$ in correspondence with Heisenberg in the late 1920s; the parallel had no physical interpretation in their framework. The McGucken Principle supplies the interpretation: the parallel is an identity because all five facts (commutator, uncertainty, wavepacket spread, ground-state saturation, time-energy) are differential signatures of $x_4$-advance, with $i$ as the unique generator licensed by Frobenius's 1878 theorem.

---

## References

[1] W. Heisenberg, "Über den anschaulichen Inhalt der quantentheoretischen Kinematik und Mechanik," *Zeitschrift für Physik* **43**, 172–198 (1927).

[2] N. Bohr, "The quantum postulate and the recent development of atomic theory," *Nature* **121**, 580–590 (1928).

[3] N. Bohr, "Discussion with Einstein on epistemological problems in atomic physics," in *Albert Einstein: Philosopher-Scientist*, ed. P. A. Schilpp, 200–241, Open Court (1949).

[4] M. Ozawa, "Universally valid reformulation of the Heisenberg uncertainty principle on noise and disturbance in measurement," *Phys. Rev. A* **67**, 042105 (2003).

[5] J. Erhart et al., "Experimental demonstration of a universally valid error-disturbance uncertainty relation in spin measurements," *Nature Physics* **8**, 185–189 (2012).

[6] M. Born and P. Jordan, "Zur Quantenmechanik," *Zeitschrift für Physik* **34**, 858–888 (1925).

[7] E. H. Kennard, "Zur Quantenmechanik einfacher Bewegungstypen," *Zeitschrift für Physik* **44**, 326–352 (1927).

[8] H. P. Robertson, "The uncertainty principle," *Physical Review* **34**, 163–164 (1929).

[9] E. Schrödinger, "Quantisierung als Eigenwertproblem," *Annalen der Physik* **79**, 361–376 (1926).

[10] D. J. Griffiths, *Introduction to Quantum Mechanics*, 3rd ed., Cambridge University Press (2018).

[11] P. A. M. Dirac, *The Principles of Quantum Mechanics*, 4th ed., Clarendon Press (1958).

[12] H. J. Groenewold, "On the principles of elementary quantum mechanics," *Physica* **12**, 405–460 (1946).

[13] T. L. Curtright and C. K. Zachos, "Quantum mechanics in phase space," *Asia Pacific Physics Newsletter* **1**, 37–46 (2012).

[14] J. von Neumann, *Mathematische Grundlagen der Quantenmechanik*, Springer (1932); M. H. Stone, "On one-parameter unitary groups in Hilbert space," *Annals of Mathematics* **33**, 643–648 (1932).

[15] G. Frobenius, "Über lineare Substitutionen und bilineare Formen," *Journal für die reine und angewandte Mathematik* **84**, 1–63 (1878).

[16] F. Riesz, "Sur les systèmes orthogonaux de fonctions," *Comptes Rendus* **144**, 615–619 (1907); E. Fischer, "Sur la convergence en moyenne," *Comptes Rendus* **144**, 1022–1024 (1907).

[17] V. B. Braginsky and F. Y. Khalili, *Quantum Measurement*, Cambridge University Press (1992).

[18] A. I. Lvovsky et al., "Quantum non-demolition measurements: a review," *Reviews of Modern Physics* **81**, 1391–1431 (2009).

[19] W. Pauli, "Die allgemeinen Prinzipien der Wellenmechanik," in *Handbuch der Physik*, vol. 24, Springer (1933).

[20] L. Mandelstam and I. Tamm, "The uncertainty relation between energy and time in nonrelativistic quantum mechanics," *Journal of Physics USSR* **9**, 249–254 (1945).

[21] O. W. Greenberg, "CPT violation implies violation of Lorentz invariance," *Phys. Rev. Lett.* **89**, 231602 (2002).

[22] S. A. Werner et al., "Observation of the phase shift of a neutron due to precession in a magnetic field," *Phys. Rev. Lett.* **35**, 1053 (1975); H. Rauch et al., "Verification of coherent spinor rotation of fermions," *Physics Letters A* **54**, 425 (1975).

[23] G. Nimtz, "Universal tunneling time for all fields," arXiv:0901.3968 (2009).

[24] H. B. G. Casimir, "On the attraction between two perfectly conducting plates," *Proc. Koninkl. Ned. Akad. Wet.* **51**, 793–795 (1948).

[25] G. Bressi et al., "Measurement of the Casimir force between parallel metallic surfaces," *Phys. Rev. Lett.* **88**, 041804 (2002).

[26] W. E. Lamb and R. C. Retherford, "Fine structure of the hydrogen atom by a microwave method," *Physical Review* **72**, 241–243 (1947).

[27] H. A. Bethe, "The electromagnetic shift of energy levels," *Physical Review* **72**, 339–341 (1947).

[28] E. McGucken, "A Compton coupling between matter and the expanding fourth dimension: a proposed matter interaction for the McGucken Principle, with consequences for diffusion and entropy," elliotmcguckenphysics.com (April 2026).

[29] E. McGucken, "The McGucken Principle and Proof: The Fourth Dimension Is Expanding at the Velocity of Light $dx_4/dt = ic$ as a Foundational Law of Physics," elliotmcguckenphysics.com (April 2026).

[30] E. McGucken, "A Derivation of the Canonical Commutation Relation $[q,p] = i\hbar$ from the McGucken Principle," elliotmcguckenphysics.com (April 17, 2026).

[31] E. McGucken, "The McGucken Principle $dx_4/dt = ic$ Necessitates the Wick Rotation and $i$ Throughout Physics," elliotmcguckenphysics.com (May 1, 2026).

[32] E. McGucken, "General Relativity and Quantum Mechanics Unified as Theorems of the McGucken Principle," elliotmcguckenphysics.com (May 5, 2026).

[33] E. McGucken, "Novel, Unifying Geometric Derivations of the Born Rule $P = |\psi|^2$, the Canonical Commutation Relation $[\hat q, \hat p] = i\hbar$, the Hilbert Space $\mathcal H$, and the Uncertainty Principle $\sigma_x\sigma_p \geq \hbar/2$ from the McGucken Principle," elliotmcguckenphysics.com (May 7, 2026).

[34] E. McGucken, "The McGucken Sphere as Spacetime's Foundational Atom," elliotmcguckenphysics.com (April 27, 2026).

[35] E. McGucken, "McGucken Cosmology First-Place Finish," elliotmcguckenphysics.com (May 1, 2026).

[36] J. A. Wheeler, Letter of recommendation for Elliot McGucken, Princeton University, ca. 1990.

[37] J. A. Wheeler, Conversations with Elliot McGucken, third-floor Jadwin Hall, Princeton University, junior year, fall 1989.

[38] P. J. E. Peebles, Quantum mechanics class and office conversations with Elliot McGucken, Princeton University, junior year, 1989–1990.

[39] J. H. Taylor, Conversations with Elliot McGucken, Princeton University, junior year, 1989–1990.

[40] E. McGucken, *Multiple Unit Artificial Retina Chipset to Aid the Visually Impaired and Enhanced Holed-Emitter CMOS Phototransistors*, Ph.D. Dissertation, Department of Physics and Astronomy, University of North Carolina at Chapel Hill (1998).
