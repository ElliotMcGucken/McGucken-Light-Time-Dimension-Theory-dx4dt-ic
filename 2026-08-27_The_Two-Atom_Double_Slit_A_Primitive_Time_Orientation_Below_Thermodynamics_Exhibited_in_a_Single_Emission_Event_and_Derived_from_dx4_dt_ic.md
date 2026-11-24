---
title: "The Two-Atom Double Slit: A Primitive Time Orientation Below Thermodynamics, Exhibited in a Single Emission Event and Derived from dx₄/dt = ic"
author: "Elliot McGucken"
date: "August 27, 2026"
abstract: |
  A photon emitted by one atom, passing through a double slit, and absorbed by a second atom does not retrace its wave history when the second atom re-emits: the second atom's photon reaches the first with the forward interference weight, and with certainty only under the conjugate boundary data of Theorem 3. The result holds with two atoms, one excitation, and no environment, so it is independent of the statistical arguments that ground the Second Law. The field equations governing the propagation (Helmholtz, Maxwell, Schrödinger with real potential) are invariant under time reversal, and the double-slit geometry with a reflecting barrier is a unitary map. The non-retracing therefore has one source: emission by a point atom is the retarded solution of the field equation, while exact retracing requires the advanced solution, whose boundary data on the detector side is an extended, phase-conjugate wavefront that no point emitter produces. An absorbing barrier adds a second, independent source. The retarded selection is a sign on the time coordinate imposed on a time-symmetric equation. Proposals that supply this sign as an added rule (Ritz's retarded-only postulate, the Wheeler–Feynman absorber condition, a cosmological boundary condition) sit one level above the field equation. The McGucken Principle dx₄/dt = ic supplies the sign as a consequence of a single kinematic statement: the + of +ic selects the +iε prescription, the +iε prescription selects the retarded propagator, and the retarded propagator is outgoing emission. The two-atom double slit thus exhibits, in the smallest possible system, a time orientation that the Principle yields and that the field equations alone do not.
fontsize: 11pt
geometry: margin=1in
header-includes:
  - \usepackage{etoolbox}
  - \AtBeginEnvironment{longtable}{\small}
  - \usepackage{amsthm}
  - \newtheorem{theorem}{Theorem}
  - \newtheorem{lemma}{Lemma}
  - \newtheorem{corollary}{Corollary}
  - \newtheorem{proposition}{Proposition}
  - \theoremstyle{remark}
  - \newtheorem{remark}{Remark}
---

**Elliot McGucken** · drelliot@gmail.com · [elliotmcguckenphysics.com](https://elliotmcguckenphysics.com)

# 1. The thought experiment

Take the double-slit experiment and remove everything that can be removed. Remove the room, the glass, the screen, the thermal bath, the detector electronics. What remains is: a partition with two apertures, one atom $A$ on side $M$, one atom $B$ on side $N$, and one excitation. Atom $A$ emits; the photon passes the partition; atom $B$ absorbs.

Now run it the other way. Atom $B$ emits. Does the photon retrace its path to $A$? Two readings of the question must be separated: whether $A$ ever absorbs, and whether the forward process is run backward.

It reaches $A$ with the forward interference weight (Theorem 5), and it retraces the forward wave history with probability zero. The purpose of this paper is to state precisely why, to locate the asymmetry at the exact point where it enters the mathematics, and to identify the principle from which that asymmetry follows. The system is minimal by construction: two degrees of freedom and one field, no ensemble, no coarse-graining, no entropy count. Whatever irreversibility survives in this system is present before thermodynamics begins.

The conclusion is that the irreversibility is the choice of the retarded solution of a time-symmetric field equation, that this choice is a sign on the time coordinate, and that the McGucken Principle $dx_4/dt = ic$ is the single statement from which that sign follows.

# 2. Setup

Let side $M$ be the half-space $z<0$, side $N$ the half-space $z>0$, and the partition the plane $z=0$ with aperture function

$$T(x,y) = \begin{cases} 1 & (x,y) \in S_1 \cup S_2 \\ 0 & \text{otherwise} \end{cases}$$

where $S_1, S_2$ are the two slits. Atom $A$ sits at $\mathbf{r}_A$ with $z_A<0$; atom $B$ sits at $\mathbf{r}_B$ with $z_B>0$.

Work first with a scalar field for a monochromatic excitation, $\psi(\mathbf{r},t) = U(\mathbf{r})\,e^{-i\omega t}$, $k=\omega/c$. The spatial part obeys the inhomogeneous Helmholtz equation with the emitting atom as source:

$$(\nabla^2 + k^2)\,U(\mathbf{r}) = -\delta(\mathbf{r}-\mathbf{r}_{\rm src}). \tag{2.1}$$

The same analysis carries over verbatim to the vector Maxwell field and to the Schrödinger wave of a massive particle, since each is time-reversal invariant in the sense of Theorem 1 and each has retarded and advanced Green's functions related as in (3.2).

The barrier is taken **reflecting** in §§3–5 and **absorbing** in §6. The two cases give different results and the difference is part of the content.

# 3. Time symmetry of the field equation

**Theorem 1 (T-invariance).** *The wave equation $\square\,\psi = -4\pi\rho$, the source-free Maxwell equations, and the Schrödinger equation with real potential are each invariant under time reversal: if $\psi(\mathbf{r},t)$ is a solution, so is $\psi(\mathbf{r},-t)$ (wave, Maxwell with $\mathbf{B}\to-\mathbf{B}$) or $\psi^*(\mathbf{r},-t)$ (Schrödinger).*

*Proof.* For the wave equation, $\partial_t^2$ is even in $t$. For Maxwell, the substitution $t\to-t$, $\mathbf{E}\to\mathbf{E}$, $\mathbf{B}\to-\mathbf{B}$, $\mathbf{j}\to-\mathbf{j}$ maps the equations to themselves. For Schrödinger, complex conjugation of $i\partial_t\psi = H\psi$ with $H$ real gives $-i\partial_t\psi^* = H\psi^*$, which is the original equation in $-t$. $\square$

Theorem 1 is standard (see e.g. Jackson, *Classical Electrodynamics*, §6.10; Sakurai, *Modern Quantum Mechanics*, §4.4). It is stated here because the rest of the paper turns on it: the equation does not orient time. Whatever orients time in the two-atom experiment is added to the equation, and the question is what adds it.

The Helmholtz equation (2.1) has two Green's functions,

$$G_\pm(\mathbf{r},\mathbf{r}') = \frac{e^{\pm ik|\mathbf{r}-\mathbf{r}'|}}{4\pi|\mathbf{r}-\mathbf{r}'|}, \tag{3.1}$$

which with the time factor $e^{-i\omega t}$ are the **retarded** (outgoing, $G_+$) and **advanced** (incoming, $G_-$) solutions. They are related by

$$G_-(\mathbf{r},\mathbf{r}') = G_+(\mathbf{r},\mathbf{r}')^*. \tag{3.2}$$

Both satisfy (2.1). The equation is indifferent between them. This is the Ritz–Einstein point of 1909 (§7).

# 4. The forward process $A \to B$

**Proposition 2 (Forward amplitude).** *Atom $A$ emits the retarded solution $U_A(\mathbf{r}) = G_+(\mathbf{r},\mathbf{r}_A)$. With a reflecting barrier, the field on side $N$ is given by the Rayleigh–Sommerfeld integral over the aperture plane,*

$$U_A(\mathbf{r}_N) = \frac{1}{2\pi}\iint T(x,y)\,U_A(x,y,0^-)\,\frac{\partial}{\partial z}\!\left(\frac{e^{ikL_N}}{L_N}\right) dx\,dy, \qquad L_N = |\mathbf{r}_N - (x,y,0)|, \tag{4.1}$$

*and the probability that $B$ absorbs is proportional to $|U_A(\mathbf{r}_B)|^2$, the two-slit interference weight at $\mathbf{r}_B$.*

*Proof.* This is Kirchhoff–Rayleigh–Sommerfeld diffraction theory for an aperture in a plane screen (Born and Wolf, *Principles of Optics*, §8.3). The restriction to $S_1 \cup S_2$ is the two-source coherence that produces interference at $\mathbf{r}_B$. $\square$

Denote the forward field on all of side $N$ by $U_A|_N$. It is an extended field, determined on the entire half-space by the aperture data. The number $U_A(\mathbf{r}_B)$ is one value of it.

# 5. Non-retracing with a reflecting barrier

**Theorem 3 (Exact reversal requires the advanced solution).** *The time-reverse of the forward process is the solution $U_A^*$. On side $N$ it is the incoming, phase-conjugate field $U_A^*|_N$, which converges through the apertures onto $\mathbf{r}_A$. It is the advanced solution $G_-(\mathbf{r},\mathbf{r}_A)$ restricted to the two-slit geometry.*

*Proof.* Apply Theorem 1 to the forward solution: $\psi_A(\mathbf{r},t) = U_A(\mathbf{r})e^{-i\omega t}$ maps to $\psi_A(\mathbf{r},-t)$, which has spatial part $U_A^*(\mathbf{r})$ (for Schrödinger, directly; for the scalar wave, by taking the real part convention). By (3.2), $U_A^* = G_-(\cdot,\mathbf{r}_A)$ filtered by $T$. $G_-$ is incoming on $\mathbf{r}_A$. $\square$

**Theorem 4 (A point emitter produces the retarded solution).** *Atom $B$ re-emitting produces $U_B(\mathbf{r}) = G_+(\mathbf{r},\mathbf{r}_B)$, the outgoing spherical wave centered on $\mathbf{r}_B$. Its restriction to the aperture plane $z=0^+$ has phase fixed by the distance from $\mathbf{r}_B$ to each point of $S_1\cup S_2$.*

This is the same physical fact as Proposition 2 with the roles exchanged: spontaneous emission from a localized atom is outgoing. Which of $G_\pm$ describes emission is a property of the emitter, and it is the retarded one.

**Theorem 5 (Non-retracing).** *With a reflecting barrier, the re-emission from $B$ does not retrace the forward path. The field on side $M$ is*

$$U_B(\mathbf{r}_M) = \frac{1}{2\pi}\iint T(x,y)\,U_B(x,y,0^+)\,\frac{\partial}{\partial z}\!\left(\frac{e^{ikL_M}}{L_M}\right)dx\,dy, \tag{5.1}$$

*an extended diffraction pattern over side $M$. The probability that $A$ absorbs is proportional to $|U_B(\mathbf{r}_A)|^2$, and by Helmholtz reciprocity $U_B(\mathbf{r}_A) = U_A(\mathbf{r}_B)$, so the return probability equals the forward interference weight at $B$, which is strictly less than the total weight over side $M$.*

*Proof.* By Theorem 3, exact retracing requires the boundary data $U_A^*|_{z=0^+}$ on the aperture plane, the conjugate of the forward field, which is an extended converging wavefront. By Theorem 4, $B$ supplies $U_B|_{z=0^+}$, the restriction of an outgoing spherical wave. The two agree at no point in general; the overlap of $U_B|_N$ with $U_A^*|_N$ is the single complex number $\langle U_A^*, U_B\rangle \propto U_A(\mathbf{r}_B)^{*}$, one component of the continuum that exact reversal requires. The remainder of $U_B$ diffracts afresh through the apertures and spreads over side $M$ according to (5.1). Reciprocity $G_+(\mathbf{r}_A,\mathbf{r}_B) = G_+(\mathbf{r}_B,\mathbf{r}_A)$ gives the stated return amplitude. $\square$

**Corollary 6 (The asymmetry is not geometric).** *The map from the field on side $M$ to the field on side $N$ through a reflecting two-slit partition is unitary on the transmitted subspace and is inverted exactly by the conjugate boundary data of Theorem 3. The double-slit geometry therefore does not produce the irreversibility. Its role is to spread the boundary data that exact reversal requires over an extended aperture, so that the mismatch between the required incoming wavefront and the outgoing wavefront a point atom supplies is visible at every point of the aperture plane.*

*Proof.* Unitarity: the reflecting barrier conserves the field norm; the transmitted and reflected components are orthogonal projections. Invertibility: phase conjugation of the transmitted field, propagated back, reconstructs $U_A$ on side $M$ (Theorem 3). This is realized experimentally by time-reversal mirrors (Fink 1992). $\square$

**Remark 7 (Scope).** Corollary 6 corrects a natural but wrong reading of the thought experiment, in which the partition is said to "discard information" so that geometry alone forbids reversal. With a reflecting barrier nothing is discarded; the blocked component returns into side $M$ and remains in the system. Reversal fails for one reason only: the emitter is oriented.

# 6. Absorbing barrier: a second, independent source

**Theorem 8 (Absorption adds non-unitarity).** *If the barrier absorbs, the blocked component $U_A\,[1-T]$ leaves the two-atom-plus-field system. The forward evolution restricted to that system is non-unitary, and the reverse process initiated by $B$ has no access to the absorbed component. Exact reversal then fails even with conjugate boundary data on side $N$.*

*Proof.* The absorbed component is transferred to barrier degrees of freedom outside the system. A reversal prepared on side $N$ alone reconstructs at most the transmitted component $U_A\,T$ on the aperture plane; the reconstructed field on side $M$ is the back-propagation of $U_A T$, which differs from $U_A$ by the back-propagation of $U_A[1-T]$. $\square$

**Remark 9.** Theorems 5 and 8 are independent. Theorem 5 holds with a reflecting barrier and no absorption; Theorem 8 holds with conjugate boundary data and no point-emitter restriction. In the physical experiment both are present. Only Theorem 5 survives when everything removable is removed, and it is Theorem 5 that the thought experiment isolates.

# 7. The asymmetry is a sign on the time coordinate

**Theorem 10 (Retarded selection is a sign choice).** *The retarded and advanced Green's functions of the wave operator are the two boundary values of the same analytic function,*

$$\tilde G(\mathbf{k},\omega) = \frac{1}{k^2 - \omega^2/c^2}, \qquad G_{\rm ret} \leftrightarrow \omega \to \omega + i\varepsilon, \quad G_{\rm adv} \leftrightarrow \omega \to \omega - i\varepsilon, \tag{7.1}$$

*and the choice between them is the sign of the infinitesimal imaginary displacement of the frequency, equivalently the sign of the imaginary part of the time coordinate in the Fourier kernel $e^{-i\omega t}$.*

*Proof.* Standard: the poles of (7.1) at $\omega = \pm ck$ are displaced into the lower half $\omega$-plane by $+i\varepsilon$, so that the inverse transform vanishes for $t<0$ (retarded); the opposite displacement gives vanishing for $t>0$ (advanced). $\square$

This is the exact location of the asymmetry. The field equation is symmetric (Theorem 1). Emission is oriented (Theorem 4). The orientation is the sign in (7.1). Every account of irreversibility at the level of a single emission event must supply that sign, and the accounts differ in what they add to the field equation in order to supply it.

**Ritz (1908–1909).** Ritz proposed that only retarded potentials are physical, as a law additional to the field equations. Einstein held that the restriction to retarded solutions is a matter of boundary conditions and probability. Their joint statement (Ritz and Einstein, *Physikalische Zeitschrift* 10, 323, 1909) records the disagreement without resolving it. Ritz's proposal adds a rule: use $G_+$.

**Wheeler–Feynman (1945).** Absorber theory uses the time-symmetric half-sum $\tfrac12(G_+ + G_-)$ and derives the retarded field from the response of a perfectly absorbing universe. The orientation is supplied by a boundary condition on the totality of absorbers. It adds a cosmological condition.

**Cosmological boundary condition.** The standard thermodynamic account traces electromagnetic retardation to the low-entropy initial state of the universe. This adds an initial condition.

Each of these supplies the sign by adding a statement to the field equation at the level of a rule, a boundary condition, or an initial condition. None derives the sign from a prior kinematic fact about events.

# 8. Derivation of the sign from dx₄/dt = ic

The McGucken Principle states that every event advances in the fourth dimension $x_4$ at rate

$$\frac{dx_4}{dt} = ic, \tag{8.1}$$

with $t$ the coordinate time, so that $x_4 = ict$ is the integrated coordinate shadow of the rate (8.1). The Principle is a single kinematic statement about the motion of events. It contains a sign: $+ic$, and the sign is part of the content, since $-ic$ is the same magnitude with the opposite orientation.

**Theorem 11 (The Principle selects the retarded propagator).** *Under (8.1), the Fourier kernel of time evolution acquires the imaginary displacement of Theorem 10 with the sign fixed by the + of +ic, so that the Green's function selected is $G_{\rm ret}$. Emission from a point atom is therefore outgoing as a consequence of (8.1).*

*Derivation.* The Principle identifies the direction of advance in $x_4$ with the direction of increasing $t$ through $x_4 = ict$: as $t$ increases, $x_4$ moves in the $+i$ direction. The Wick substitution $t \to -i\tau$, $\tau = x_4/c$, is under (8.1) the coordinate identification between $t$ and the advance in $x_4$ rather than an analytic continuation (this is Theorem 6 of *The McGucken Principle Necessitates the Wick Rotation and i Throughout Physics*, elliotmcguckenphysics.com, May 1, 2026). The $+i\varepsilon$ prescription of (7.1) is the infinitesimal form of that identification: displacing $\omega$ by $+i\varepsilon$ is equivalent to giving $t$ a small imaginary part of sign fixed by the orientation of $x_4$-advance, and (8.1) fixes that orientation as $+$. With the displacement sign fixed, Theorem 10 yields $G_{\rm ret}$. With $G_{\rm ret}$ selected, a point source emits the outgoing wave $G_+$, which is Theorem 4. $\square$

**Corollary 12 (The two-atom double slit exhibits the Principle's orientation).** *In the two-atom experiment, Theorem 5 (non-retracing) follows from Theorem 4 (point emission is outgoing), Theorem 4 follows from Theorem 11, and Theorem 11 follows from (8.1). The experiment therefore exhibits, in a single emission event with no environment and no statistics, the time orientation that (8.1) yields.*

**Remark 13 (Level of postulate).** The comparison in §7 is at the level of what each account adds to the field equation. Ritz adds a rule about Green's functions. Wheeler–Feynman adds an absorber condition. The cosmological account adds an initial condition. The Principle adds one kinematic statement about events, and the Green's-function selection is a theorem of it (Theorem 11). The Principle is therefore prior to the others in the sense that it does not itself reference Green's functions, absorbers, or initial states; the sign these accounts insert is, under (8.1), the sign in $+ic$.

**Remark 14 (What else the same sign carries).** Under (8.1) the same $+ic$ that orients emission generates the expanding McGucken Sphere from every event, and the interference weight $|U_A(\mathbf{r}_B)|^2$ of Proposition 2 is, in the framework, the Born weight carried by the SO(3)-Haar measure on that Sphere. In the two-atom experiment the orientation of emission and the interference weight at $B$ then have a common origin. This paper establishes the orientation; the Born-weight derivation is carried in the corpus (*Proofs that QM and Relativity Force the McGucken Principle*, elliotmcguckenphysics.com, May 2026, and the QM–GR unification chain) and is cited here rather than reproduced.

# 9. Comparison of accounts of retardation

| Account | What is added to the time-symmetric field equation | Level | Sign origin | Present in two-atom system |
|:--|:--|:--|:--|:--|
| McGucken, $dx_4/dt = ic$ | One kinematic statement about every event | Prior to Green's functions | The + in $+ic$ | Yes: Theorem 11 |
| Ritz, retarded-only | A rule: use $G_+$ | Green's-function level | Postulated | Yes, as postulate |
| Wheeler–Feynman | Perfect-absorber boundary condition on the universe | Cosmological | Absorber response | Requires absorbers beyond the two atoms |
| Cosmological initial condition | Low-entropy initial state | Statistical | Initial condition | Requires ensemble beyond the two atoms |

# 10. Unitarity: the operator and the realized process

The two-atom experiment separates two claims that the word "unitary" usually joins.

**Proposition 15 (The evolution is unitary).** *With a reflecting barrier, the field evolution from any state on side $M$ to the corresponding state on side $N$ is norm-preserving and invertible (Corollary 6).*

**Proposition 16 (The realized process is not the unitary inverse of the forward process).** *The forward process ends with the excitation localized on $B$. The reverse process, initiated by $B$, ends with the excitation localized on $A$ with probability $|U_A(\mathbf{r}_B)|^2$ and elsewhere on side $M$ otherwise. In neither direction is the final state the image of the initial state under $U$ or $U^{-1}$: each process ends in a definite absorption, and the step from the extended field $U_B|_M$ to the excitation on one atom is a projection, not a unitary map.*

*Proof.* $U_B|_M$ is an extended field with support over side $M$ (5.1). Absorption by a single atom takes this field to a state with support on one atom; the map is a projection onto that atom's excited state with weight $|U_B(\mathbf{r}_A)|^2$, and a projection is not norm-preserving on the full field. $\square$

**Remark 17 (Scope).** Propositions 15 and 16 are compatible and both hold. Unitarity is a property of the evolution operator between emission and absorption. The realized process contains two further steps, the oriented emission (Theorem 4) and the localized absorption (Proposition 16), and neither is an instance of the unitary operator. A statement that "physics is unitary" is a statement about Proposition 15 and is silent on the two steps that make the process oriented and definite. The two-atom experiment is the minimal system in which the three components—unitary evolution, oriented emission, localized absorption—can be separated and named, and it shows that the reversibility of the operator does not transfer to the process.

**Remark 18 (Information is lost in the realized process).** Two quantities present at the start of the reverse process are absent at its end. First, the extended field $U_B|_M$ of (5.1), with its value at every point of side $M$; after $A$ absorbs, the state is the excitation on $A$ and the field values elsewhere on side $M$ are gone (Proposition 16). Second, the advanced solution $G_-$; of the two solutions the equation permits, one is realized and the other is discarded before propagation begins (Theorem 4). The standard reply to the first loss is that projection is not physical, that the extended field persists in superposition with the absorber, and that decoherence into an environment accounts for a single observed outcome with no loss. The two-atom system contains no environment. Either the projection occurs and the field values on the rest of side $M$ are lost, or the excitation remains spread over side $M$ and $A$ has not absorbed. The operator-level statement that information is conserved holds between emission and absorption and decides nothing about which of these two descriptions is correct. The standard reply to the second loss is that the retarded selection is an initial condition and that initial conditions are not counted as lost information. That classification is the one §8 replaces: under (8.1) the selection is a theorem of the kinematics, and the discarded advanced solution is excluded by law rather than by initial condition.

# 11. The claim that physics is unitary and information is conserved is wrong

Susskind has stated, as a principle of physics, that information is never lost and that the laws of physics are reversible (Susskind, *The Black Hole War*, 2008; the position is stated throughout his lectures on the black-hole information problem). The two-atom experiment is the direct counterexample, and the reason it is a counterexample is the definition of physics.

Physics is defined by measurement. A physical statement is a statement about what is measured. In the two-atom experiment the measurement is whether $A$ absorbs, and that measurement has an outcome. The outcome is oriented: $B$ emitted an outgoing wave (Theorem 4). The outcome is definite: the excitation is on $A$ or it is elsewhere on side $M$ (Proposition 16). The outcome is not the reverse of the forward outcome (Theorem 5). And once the outcome exists, the field values across the rest of side $M$ and the advanced solution that was never realized are not recoverable from anything that is measured (Remark 18).

The unitarity claim is a claim about $U(t) = e^{-iHt/\hbar}$, the operator that propagates the field between emission and absorption. It is correct as a statement about that operator (Proposition 15). It is wrong as a statement about physics, because the operator is not what is measured; the outcome is. To hold that information is never lost, one must hold that the outcome never occurs, that the excitation remains spread over side $M$ in superposition with $A$, and that absorption is an appearance. Under the operational definition, that is a description of a system in which no physics has taken place.

The two-atom experiment removes every place where this could be hidden. There is no environment to decohere into, no ensemble to coarse-grain, no cosmological initial state to carry the orientation. Two atoms, one partition, one excitation, one measurement. The measurement is oriented and definite, the process is irreversible, and information is lost. The claim that physics is unitary and conserves information is wrong about physics, and it is wrong in the smallest system in which the question can be asked.

**Proposition 19 (The measured event is what exists).** *In the two-atom system the measurement is absorption at $A$. That event is oriented (Theorem 4), definite (Proposition 16), and not the reverse of the forward event (Theorem 5). Information is lost when it occurs (Remark 18). The unitary operator predicts the weight of the event and contains no orientation and no outcome. A claim that physics is unitary and conserves information contradicts the measured event and is therefore wrong. Under $dx_4/dt = ic$ the orientation of every event is fixed by law, and the measured orientation is a theorem (Theorem 11).*

The correct statement is the one this paper derives: the field equation is time-symmetric, and the physics—the measured event—is oriented because $dx_4/dt = ic$ orients every event. The reversibility of the operator is a property of the mathematics. The irreversibility of the outcome is the physics.

# 12. Conclusion

Strip the double-slit experiment to two atoms, one partition, and one excitation. The path is never retraced. The field equations are time-symmetric and the geometry with a reflecting barrier is unitary, so the non-retracing has a single source: emission by a point atom is the retarded solution, and exact retracing requires the advanced one. That selection is a sign on the time coordinate, imposed on an equation that does not contain it. Accounts that supply the sign by rule, absorber condition, or initial condition add a statement at the level of the Green's function or the cosmos. The McGucken Principle $dx_4/dt = ic$ supplies the sign as a consequence of one kinematic statement about events, through the chain $+ic \to +i\varepsilon \to G_{\rm ret} \to$ outgoing emission. The two-atom double slit is the smallest system in which that chain can be observed, and it is observed. Physics is defined by measurement; the measured event in this system is oriented, definite, and irreversible, and information is lost when it occurs. The claim that physics is unitary and conserves information describes the operator between emission and absorption and is wrong about the physics.

# Acknowledgment

The author's undergraduate research on time-reversal asymmetry was assigned by John Archibald Wheeler at Princeton (1988–1990). The present question—what remains of irreversibility when the environment is removed—is in the lineage of that assignment.

# References

1. W. Ritz and A. Einstein, "Zum gegenwärtigen Stand des Strahlungsproblems," *Physikalische Zeitschrift* 10, 323–324 (1909).
2. J. A. Wheeler and R. P. Feynman, "Interaction with the Absorber as the Mechanism of Radiation," *Reviews of Modern Physics* 17, 157–181 (1945).
3. M. Fink, "Time reversal of ultrasonic fields. I. Basic principles," *IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control* 39, 555–566 (1992).
4. M. Born and E. Wolf, *Principles of Optics*, 7th ed. (Cambridge University Press, 1999), §8.3.
5. J. D. Jackson, *Classical Electrodynamics*, 3rd ed. (Wiley, 1999), §6.10.
6. J. J. Sakurai and J. Napolitano, *Modern Quantum Mechanics*, 2nd ed. (Addison-Wesley, 2011), §4.4.
7. E. McGucken, *The McGucken Principle Necessitates the Wick Rotation and i Throughout Physics*, elliotmcguckenphysics.com (May 1, 2026).
8. E. McGucken, *Proofs that QM and Relativity Force the McGucken Principle*, elliotmcguckenphysics.com (May 2026).
9. L. Susskind, *The Black Hole War: My Battle with Stephen Hawking to Make the World Safe for Quantum Mechanics* (Little, Brown, 2008).
