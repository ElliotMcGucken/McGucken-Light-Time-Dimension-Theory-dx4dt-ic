# Vanquishing Infinities and Singularities via the Continuous and Discrete McGucken Spacetime Geometry

## Two Theorems of the McGucken Principle dx₄/dt = ic: Finite One-Loop QED Vacuum Polarization on a Hybrid Continuous–Discrete Measure, and Axiomatic Foreclosure of the Schwarzschild–Kruskal Interior

**Dr. Elliot McGucken, PhD**  
*Light Time Dimension Theory*  
elliotmcguckenphysics.com

---

> *"More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet."*
>
> — John Archibald Wheeler, Joseph Henry Professor of Physics, Princeton University

---

## Contents

Abstract

1. Introduction
2. The Hybrid Measure as Hypothesis
3. One-Loop Photon Vacuum Polarization with the Hybrid Measure
    3.1 The standard expression
    3.2 The hybrid measure substitution
    3.3 Recovery of the standard running coupling
    3.4 The structural difference from renormalisation
4. Discussion of the QED Result
    4.1 Open problems
5. Resolution of the Schwarzschild–Kruskal Singularity via the Axioms of the Framework
6. Conclusion

References

---

## Abstract

The McGucken Principle, which states that the fourth dimension is expanding at the velocity of light in a spherically symmetric manner dx₄/dt = ic, vanquishes the infinities of general relativity and quantum mechanics. Twentieth-century physics has lived with two unwanted infinities: the ultraviolet divergences of quantum field theory, controlled by renormalization but not eliminated, and the curvature singularities of general relativity at the Schwarzschild–Kruskal interior and at the Big Bang. Both are foreclosed by a structural feature of the McGucken framework — the continuous-and-discrete geometry of spacetime that follows from dx₄/dt = ic, with the spatial three (x₁, x₂, x₃) continuous and the fourth direction x₄ = ict discrete at the Planck wavelength. The QED divergence is foreclosed because the integration domain along the x₄-conjugate momentum is the finite Brillouin zone of the x₄-lattice; the integral is finite by structure, not by regularization. The Schwarzschild–Kruskal interior is foreclosed because the role swap of ∂_r into a timelike direction at r < rₛ is structurally inconsistent with the foundational axioms (A1)–(A3) of the framework; the manifold ends at the horizon and the singularity at r = 0 is not part of it. Two theorems make this precise.

This paper establishes two results within the McGucken framework. *First*, we propose as a working hypothesis that the spacetime integration measure relevant to QFT loop calculations is hybrid: continuous in the three spatial directions x₁, x₂, x₃, and discrete in the fourth direction x₄ = ict with spacing equal to the Planck wavelength λ_P = √ℏ G/c³. The hybrid structure is not derived from dx₄/dt = ic alone, here or in the wider corpus. The corpus position [McGuckenSphere] identifies λ_P and ℏ jointly via a three-step sequence: (i) dx₄/dt = ic fixes c = ℓ_*/t_* as the wavelength-per-period ratio of the substrate, but does not fix the absolute scale ℓ_*; (ii) one quantum of action per substrate cycle is posited as an independent postulate, defining ℏ as the substrate's per-tick action; (iii) Schwarzschild self-consistency r_S = λ at the substrate scale, with G entering as a third independent dimensional input, identifies ℓ_* = λ_P = √ℏ G/c³ and yields ℏ = λ_P² c³/G as a derived expression. Step (ii) is a postulate, not a theorem of dx₄/dt = ic; G enters as external input at step (iii). We treat the hybrid measure of the present paper as an explicit hypothesis on the same footing. Conditional on this hypothesis, the one-loop photon vacuum polarization integral of QED is finite by the structure of the integration domain — the x₄-conjugate momentum is confined to the Brillouin zone of the discrete x₄-lattice — and the integral is computed explicitly to the closed form I_hyb(Δ) = 2π² arcsinh(πℏ/(λ_P√Δ)). At physical scales far below the Planck scale, the renormalized vacuum polarization reproduces the standard one-loop running Π_R(q²) → (α/3π)log(q²/m²) with corrections of order (m/m_P)² ~ 10⁻⁴⁴ at the electron mass scale. The standard logarithmic UV divergence is absent — not regulated, but absent — because the integration domain along the x₄-conjugate direction was always finite. The infinity is vanquished by the discrete x₄-lattice; the standard QED running coupling is recovered at all accessible scales.

*Second*, we establish that the Schwarzschild–Kruskal singularity at r = 0 is not part of the McGucken manifold. The Kruskal–Szekeres maximal extension constructs an interior region (region II of the four-region maximal extension) within which the standard metric is non-singular at the horizon and the curvature singularity at r = 0 is reached. We show that this construction is barred by three structurally independent inconsistencies with the axioms (A1) dx₄/dt = ic invariant and unaffected by mass, (A2) mass affects the spatial geometry x₁, x₂, x₃ by bending and curving them while x₄-advance is unchanged, and (A3) any momentum-energy carried in x₄ has no rest mass. Specifically: (A2) fixes ∂_r as spatial because mass bends it; (A1) fixes x₄ as the unique timelike direction along which dx₄/dt = ic holds; (A3) prohibits massive worldlines from being timelike along non-x₄ directions. The Kruskal interior's role swap of ∂_r into a timelike direction is incompatible with each of these axioms independently. Consequently the McGucken manifold consists of the exterior region r > rₛ only, the maximum curvature is the finite value K_max = 3c⁸/(4G⁴ M⁴) at the horizon, and the singularity at r = 0 is not reached. The Big Bang singularity is treated by a structurally analogous argument. The infinity is vanquished not by smoothing the curvature but by foreclosing, via the foundational axioms, the locus where the curvature would diverge.

The two results are independent. The QED result is mathematical: standard integrals on a hybrid measure. The Schwarzschild result is axiomatic: the Kruskal interior is inconsistent with the foundational axioms of the framework. We are explicit about the two open problems that remain: deriving Hypothesis~1 from dx₄/dt = ic alone — which the corpus does not currently accomplish either, since ℏ enters through an independent action-quantization postulate and G as an external dimensional input — and computing higher-loop QED observables under the hybrid measure.

—

\tableofcontents

—

## Introduction

The McGucken Principle states that the fourth dimension is expanding at the velocity of light in a spherically symmetric manner dx₄/dt = ic. This single principle vanquishes the two great unwanted infinities of twentieth-century physics: the ultraviolet divergences of quantum field theory and the curvature singularities of general relativity. The first is controlled in QED by renormalization, but the divergent integrals remain in the bare theory and are merely subtracted; the divergence is hidden, not eliminated. The second appears at r = 0 inside the Schwarzschild–Kruskal black-hole interior and at t = 0 at the FLRW Big Bang origin, and is accepted in standard general relativity as a true breakdown of the theory.

Both infinities are foreclosed by a structural feature of the framework that follows from dx₄/dt = ic: the spacetime geometry is hybrid — continuous in the three spatial directions (x₁, x₂, x₃), discrete in the fourth direction x₄ = ict at the Planck wavelength λ_P = √ℏ G/c³. The QED divergence is foreclosed because the x₄-conjugate momentum is confined to the finite Brillouin zone of the discrete x₄-lattice; the integral is finite by structure, not by regularization. The Schwarzschild–Kruskal interior is foreclosed because the role swap of ∂_r into a timelike direction at r < rₛ is structurally barred by the foundational axioms (A1)–(A3) of the framework; the manifold ends at the horizon and r = 0 is not in it. Both infinities go away for the same underlying reason: the continuous-and-discrete geometry restricts the manifold (in the QED case, restricts the integration domain; in the Schwarzschild case, restricts the spacetime extent) so that the locus where the divergence would live is not reached.

We make this precise in two theorems. Theorem, mathematical: under the hybrid measure of Hypothesis 1, the one-loop photon vacuum polarization integral of QED is finite, evaluates to the closed form of Equation~(equation), and reproduces the standard α/(3π) running of the QED coupling at scales far below the Planck scale. Theorem, axiomatic: under the axioms (A1)–(A3), the Schwarzschild–Kruskal singularity at r = 0 is not part of the McGucken manifold, by three structurally independent inconsistencies between the Kruskal interior's role swap and the axioms. The maximum curvature attained on the manifold is the finite value K_max = 3c⁸/(4G⁴ M⁴) at the horizon. The Big Bang singularity is treated by a structurally analogous argument.

The hybrid measure of Hypothesis 1 is posited as a working hypothesis. The dimensional argument that fixes the x₄-spacing at λ_P is closed in the wider corpus [McGuckenSphere] via a three-step sequence: dx₄/dt = ic fixes c = ℓ_*/t_* as a substrate wavelength-per-period ratio; an independent postulate quantizes one action quantum per substrate cycle, defining ℏ as the substrate's per-tick action; Schwarzschild self-consistency r_S = λ at the substrate scale identifies ℓ_* = λ_P, with G entering as a third independent dimensional input. The corpus is explicit that step (ii) is a postulate, not a theorem of dx₄/dt = ic. The present paper takes the hybrid measure as a hypothesis on this footing and computes its consequences. Higher-loop QED observables, comparison to alternative discreteness frameworks (loop quantum gravity, causal set theory, doubly special relativity, string-theoretic minimum length), and the Schwinger anomalous magnetic moment aₑ = α/(2π) are treated in companion work and are not pursued here.

**Relationship to previous companion papers.**

The companion paper [McGuckenConstants] establishes that ℏ = m_Pc²/(2π f_P) and that the Planck wavelength has a natural interpretation as a fundamental quantum of x₄'s oscillatory advance. The present paper takes that interpretation as a starting hypothesis and computes its QED consequences. The companion paper [McGuckenFeynman] establishes Feynman propagators, vertices, and the Dyson expansion as theorems of dx₄/dt = ic. The present paper takes those theorems as given and applies them in the context of the hybrid measure. The companion paper [McGuckenQED] establishes the QED Lagrangian itself as a theorem of local x₄-phase invariance. The present paper assumes this Lagrangian and computes one of its loop corrections under the hybrid measure. The companion paper [McGuckenSphere] develops the McGucken Sphere as the foundational atom of spacetime, deriving the amplituhedron and twistor structures as theorems of dx₄/dt = ic, and supplies the substrate-quantization framework on which Hypothesis 1 is built.

## The Hybrid Measure as Hypothesis

> **Hypothesis 1.** The four-dimensional Euclidean spacetime measure relevant to QFT loop calculations, after Wick rotation τ = x₄/c (a theorem of dx₄/dt = ic per [McGuckenWickRotation], not an analytic-continuation hypothesis), is

$$
d\mu \;=\; dx_1\, dx_2\, dx_3 \cdot a_4 \sum_{n \in \mathbb{Z}} \delta(x_4 - n a_4)\, dx_4,
$$

with a₄ = λ_P = √ℏ G/c³. The three spatial directions are continuous; the x₄ direction is a discrete lattice with spacing λ_P.

> **Remark (Status of the hypothesis).** The principle dx₄/dt = ic states that x₄ is the unique dimension carrying an intrinsic dynamical rate. The dimensional argument suggesting that x₄ is quantised at the Planck scale is the following: if x₄-advance is oscillatory rather than monotonic — which the imaginary character of ic suggests but does not prove — then the wavelength of one quantum of x₄-advance is fixed dimensionally by the available constants. The constants c, ℏ, G admit a unique length combination λ_P. However, dx₄/dt = ic as written contains only c; ℏ and G must enter from outside. The corpus [McGuckenSphere] addresses this through an explicit three-step sequence: (i) dx₄/dt = ic fixes c as the wavelength-per-period ratio ℓ_*/t_* of some substrate length-period pair, but does not pin the absolute scale ℓ_*; (ii) the substrate is postulated to carry one quantum of action per oscillation cycle, defining ℏ as the substrate's per-tick action quantum — the corpus is explicit that this is ``a definition of ℏ as the substrate's per-tick action quantum, not a derivation of ℏ from c; a second postulate of the foundational atom''; (iii) Schwarzschild self-consistency r_S = λ at the substrate scale, with G entering as a third independent dimensional input, identifies ℓ_* = λ_P = √ℏ G/c³. The Planck length formula is then a derived expression, but it derives from dx₄/dt = ic *plus* an action-quantization postulate *plus* an external G. We adopt this framing for the present paper: the hybrid measure rests on the same combination, and dx₄/dt = ic alone is insufficient to fix λ_P as the lattice spacing. The hybrid measure is therefore a hypothesis to be tested by its consequences rather than a theorem from dx₄/dt = ic.

> **Remark (Lorentz invariance).** If the x₄-discreteness is to be understood as discreteness along the proper-time axis, with τ the magnitude of accumulated x₄-advance along a worldline, then the spacing λ_P is the same in every inertial frame because proper time is Lorentz-invariant. This avoids the standard objection to spatial-discreteness proposals (which boost-shrink and break Lorentz symmetry). We note this as a structural feature of the hypothesis but do not develop it further here.

> **Remark (Wick rotation as coordinate identification, not analytic continuation).** The Wick rotation t → -iτ appearing in Hypothesis 1 and throughout this paper is established as a theorem of dx₄/dt = ic in [McGuckenWickRotation] (Theorem~6 there): the substitution t → -iτ is the coordinate identification τ = x₄/c on the real four-dimensional Euclidean manifold, recovered by solving x₄ = ict for t. Under that result, the τ appearing in the Euclidean measure of (equation) and the x₄ appearing in the discrete lattice are the same axis written in two coordinate systems. The reality of the Euclidean action iS_M = -S_E used in standard treatments of the loop integral, the convergence of ∫ Dφ  e^(-S_E/ℏ), the Osterwalder–Schrader reflection positivity x₄ → -x₄ symmetry, and the Kontsevich–Segal admissible-metric semigroup [KontsevichSegal2021] are all theorems of dx₄/dt = ic via Theorems~9, 10, 19, and 25–26 of [McGuckenWickRotation], with the K–S two-input characterization (holomorphic semigroup plus independent positivity axiom) reduced to the single physical principle. The hybrid measure of Hypothesis 1 is therefore not invoking the Wick rotation as an external mathematical tool; it is positing a discrete structure on the same x₄-axis whose role as the Wick rotation's destination is itself a derived consequence of dx₄/dt = ic.

## One-Loop Photon Vacuum Polarization with the Hybrid Measure

### The standard expression

We work in Minkowski signature η = diag(-1,+1,+1,+1), natural units ℏ = c = 1, with electron mass m and fine-structure constant α = e²/(4π). The standard one-loop photon vacuum polarization tensor, after Wick rotation to Euclidean signature, Feynman-parameter combination, and shift ℓ_E = k_E + xq_E, takes the form

$$
\Pi(q_E^2) \;=\; -\frac{8e^2}{(2\pi)^4} \int_0^1 dx\, x(1-x) \int d^4\ell_E\, \frac{1}{[\ell_E^2 + \Delta(x)]^2},
\qquad \Delta(x) \equiv x(1-x)q_E^2 + m^2.
$$

The inner integral is logarithmically divergent in the standard treatment because the integration over ℓ_E⁰ ∈ (-∞, +∞) is unbounded and the integrand falls only as 1/(ℓ_E⁰)⁴ at large ℓ_E⁰ for fixed spatial ℓ.

### The hybrid measure substitution

Under Hypothesis 1, the x₄-direction is a lattice of spacing λ_P. The Fourier conjugate of a discretely-sampled signal of spacing a₄ is periodic in conjugate-variable with period 2π/a₄, and the unique modes are confined to the first Brillouin zone [-π/a₄, +π/a₄]. In natural units ℏ = c = 1 (declared in Section.1), this gives the conjugate-momentum range [-π/λ_P, +π/λ_P]; we display the result with ℏ explicit so the Brillouin-zone scale πℏ/λ_P = πm_P c is visually transparent. Setting a₄ = λ_P, the substitution is

$$
\int d^4\ell_E \;\longmapsto\; \int_{-\pi\hbar/\lambda_P}^{+\pi\hbar/\lambda_P} d\ell_E^0 \int d^3\boldsymbol{\ell}.
$$

The spatial integration remains continuous and unbounded. In natural units, πℏ/λ_P = πm_P (Planck momentum, up to factors of order unity); we use πℏ/λ_P throughout to keep the Planck scale explicit.

> **Theorem (Finite hybrid one-loop vacuum polarization).** Under Hypothesis 1, the inner loop integral of (equation) evaluates, after substitution (equation), to the closed-form expression

$$
I_{\mathrm{hyb}}(\Delta) \;\equiv\; \int_{-\pi\hbar/\lambda_P}^{+\pi\hbar/\lambda_P} d\ell_E^0 \int d^3\boldsymbol{\ell}\, \frac{1}{[(\ell_E^0)^2 + |\boldsymbol{\ell}|^2 + \Delta]^2}
\;=\; 2\pi^2\, \mathrm{arcsinh}\!\left(\frac{\pi\hbar/\lambda_P}{\sqrt{\Delta}}\right).
$$

The integral is finite for all Δ > 0. In the regime Δ ≪ (πℏ/λ_P)², the result expands as

$$
I_{\mathrm{hyb}}(\Delta) \;=\; 2\pi^2 \log\!\left(\frac{2\pi\hbar/\lambda_P}{\sqrt{\Delta}}\right) + O\!\left(\frac{\Delta\,\lambda_P^2}{\hbar^2}\right).
$$

*Proof.* The spatial integral is performed first. With ρ ≡ |ℓ|, d³ℓ = 4πρ² dρ, and a² ≡ (ℓ_E⁰)² + Δ,

$$
\int d^3\boldsymbol{\ell}\, \frac{1}{[\rho^2 + a^2]^2}
\;=\; 4\pi\int_0^\infty \frac{\rho^2\,d\rho}{(\rho^2 + a^2)^2}.
$$

Substituting ρ = atanθ, dρ = asec²θ dθ, ρ² + a² = a²sec²θ:

$$
4\pi\int_0^\infty \frac{\rho^2\,d\rho}{(\rho^2 + a^2)^2}
\;=\; 4\pi\int_0^{\pi/2}\frac{a^2\tan^2\theta \cdot a\sec^2\theta}{a^4\sec^4\theta}\,d\theta
\;=\; \frac{4\pi}{a}\int_0^{\pi/2}\sin^2\theta\,d\theta
\;=\; \frac{\pi^2}{a}.
\end{equation}
So ∫ d³ℓ/[ρ² + a²]² = π²/√(ℓ_E⁰)² + Δ.

The remaining ℓ_E⁰ integral is

$$
I_{\mathrm{hyb}}(\Delta) \;=\; \pi^2 \int_{-\pi\hbar/\lambda_P}^{+\pi\hbar/\lambda_P} \frac{d\ell_E^0}{\sqrt{(\ell_E^0)^2 + \Delta}}.
$$

Using the antiderivative ∫ dk/√k² + a² = arcsinh(k/a) + C, this evaluates to

$$
I_{\mathrm{hyb}}(\Delta) \;=\; \pi^2 \cdot 2\,\mathrm{arcsinh}\!\left(\frac{\pi\hbar/\lambda_P}{\sqrt{\Delta}}\right) \;=\; 2\pi^2\,\mathrm{arcsinh}\!\left(\frac{\pi\hbar/\lambda_P}{\sqrt{\Delta}}\right).
$$

For the IR expansion: when z = πℏ/(λ_P√Δ) ≫ 1, use arcsinh(z) = log(z + √z²+1) = log(2z) + O(1/z²). Substituting gives (equation), with the O(1/z²) error translating to O(Δλ_P²/ℏ²) = O((m/m_P)²) at the electron mass scale. ∎

### Recovery of the standard running coupling

The renormalized vacuum polarization, defined as Π_R(q²) ≡ Π(q²) - Π(0), is the physical quantity that determines the running of the QED coupling. Substituting (equation) into (equation) and tracking coefficients explicitly: the IR expansion gives I_hyb(Δ) = 2π²log(2πℏ/λ_P) - π²logΔ + O(Δλ_P²/ℏ²). The constant term 2π²log(2πℏ/λ_P) is independent of Δ (and therefore of q²), so it cancels exactly in the subtraction Π(q²)-Π(0). The Δ-dependent piece carries coefficient -π². The prefactor in (equation) is -8e²/(2π)⁴ = -e²/(2π⁴). Multiplying:

$$
\Pi_R(q_E^2) \;=\; -\frac{e^2}{2\pi^4}\cdot(-\pi^2)\int_0^1 dx\,x(1-x)\bigl[\log\Delta(x)-\log m^2\bigr] + O(q^2/m_P^2)
\;=\; \frac{e^2}{2\pi^2}\int_0^1 dx\,x(1-x)\log\frac{\Delta(x)}{m^2} + O(q^2/m_P^2).
$$

For q_E² ≫ m², Δ(x) ≈ x(1-x) q_E², so log[Δ(x)/m²] = log[x(1-x)] + log(q_E²/m²). The first term contributes a q²-independent constant absorbed into the definition of the coupling at scale m; the q²-dependent second term gives, with ∫₀¹ x(1-x) dx = 1/6 and e² = 4πα,

$$
\Pi_R(q_E^2) \;\xrightarrow[q_E^2 \gg m^2]{}\; \frac{e^2}{2\pi^2}\cdot\frac{1}{6}\log\frac{q_E^2}{m^2} \;=\; \frac{\alpha}{3\pi}\log\!\frac{q_E^2}{m^2} + O\!\left(\frac{q_E^2}{m_P^2}\right).
$$

This is the standard one-loop running of the QED coupling. It emerges from the hybrid measure with Planck-suppressed corrections of order (m/m_P)² ~ 10⁻⁴⁴ at the electron mass scale, entirely beyond present experimental reach.

### The structural difference from renormalisation

The standard treatment of (equation) regards the inner integral as logarithmically divergent and removes the divergence by introducing a regulator (dimensional, Pauli–Villars, or hard cutoff), absorbing the divergent part into a counterterm, and extracting the finite physical prediction. The hybrid measure does not regulate a divergent integral. The integral in (equation) is finite from the start because the integration domain along ℓ_E⁰ was always confined to the Brillouin zone [-πℏ/λ_P, +πℏ/λ_P]. There is no divergence to subtract. The constant logarithmic term that would correspond to the standard divergence in the limit λ_P → 0 is in this framework a finite contribution to the bare coupling, which is itself a finite quantity.

This is a structural difference, not a numerical one: at scales q² ≪ m_P², the predicted Π_R(q²) is identical to the standard QED result to corrections of order (m/m_P)². The framework therefore reproduces the precision of standard QED (which, via standard renormalisation, agrees with experiment to twelve digits in g-2) without claiming any deviation that current or foreseeable experiments could see.

## Discussion of the QED Result

Theorem establishes that, under Hypothesis 1, the one-loop photon vacuum polarization integral of QED is finite without renormalization, and that the standard infrared running coefficient α/(3π) emerges from the hybrid measure with corrections suppressed by (m/m_P)². The calculation is explicit. The mathematical content is a pair of standard integrals (the spatial integral evaluates by the substitution ρ = atanθ; the x₄-conjugate integral evaluates by the antiderivative of 1/√k² + a²) and the IR expansion is the Taylor expansion of arcsinh(z) at large z. No step requires anything beyond standard methods.

Hypothesis 1 is taken as a hypothesis, on the footing it inherits from the wider corpus [McGuckenSphere]. The dimensional argument that fixes the spacing at λ_P requires G to enter, and dx₄/dt = ic as written contains only c; the corpus closes the gap via the three-step sequence (dx₄/dt = ic fixes c; an independent action-quantization postulate defines ℏ; Schwarzschild self-consistency r_S = λ at the substrate scale identifies ℓ_* = λ_P with G as a third independent dimensional input). Step (ii) is a postulate; G is an external input. A derivation of the hybrid measure from dx₄/dt = ic alone — without the action-quantization postulate and without an external G — would require either (a) deriving the action-quantization postulate from dx₄/dt = ic, (b) supplying a different dimensional argument that does not require G, or (c) deriving G itself as a theorem of dx₄/dt = ic. We list this as the central open problem.

The Schwinger anomalous magnetic moment aₑ = α/(2π), the on-shell electron self-energy, and higher-loop QED observables follow the same hybrid-measure pattern as the vacuum polarization. The vacuum polarization is treated here as the simplest non-trivial case; the others are extensions of the same calculation under the hybrid measure.

The Schwarzschild–Kruskal singularity is treated rigorously in Section below, where Theorem establishes that the interior region II of the Kruskal extension and the singularity at r = 0 are not part of the McGucken manifold, by the axioms of the framework. The Big Bang singularity is structurally analogous and addressed in the same section.

### Open problems

The open problems that follow from the present work, in priority order:

- **Derive Hypothesis 1 from dx₄/dt = ic alone.** The corpus [McGuckenSphere] fixes λ_P and ℏ jointly via a three-step sequence: dx₄/dt = ic fixes c as a substrate ratio ℓ_*/t_*; an independent postulate quantizes one action quantum per substrate cycle to define ℏ; Schwarzschild self-consistency r_S = λ at the substrate scale identifies ℓ_* = λ_P, with G entering as a third independent dimensional input. The corpus states that the action-quantization step is ``a definition of ℏ as the substrate's per-tick action quantum, not a derivation of ℏ from c.'' A derivation from dx₄/dt = ic alone would have to either (a) derive the action-quantization postulate from dx₄/dt = ic, (b) supply a different dimensional argument that does not require G as external input, or (c) derive G itself as a theorem of dx₄/dt = ic.

- **Compute higher-loop QED observables.** The Schwinger aₑ = α/(2π), the running coupling to two loops, and the precision QED predictions tested at 10⁻¹³ require explicit calculation under the hybrid measure. The vacuum polarization computed here is the simplest case.

- **Comparison with alternative discreteness frameworks.** Loop quantum gravity, causal set theory, doubly special relativity, and string-theoretic minimum length each posit a different form of Planck-scale discreteness with different observational consequences. A systematic comparison of the hybrid measure's predictions against these frameworks is a separate program of work.

## Resolution of the Schwarzschild–Kruskal Singularity via the Axioms of the Framework

The Kruskal extension is barred by the axioms of the McGucken framework: the interior region II is not part of the manifold, and the classical singularity at r = 0 is not reached. The mechanism is not curvature regulation; it is structural. The locus where the singularity would lie is not in the manifold, by the axioms.

**The axioms of the framework.**

We work from three axioms, all stated in or following directly from dx₄/dt = ic:

- **(A1)** The fourth dimension advances at the invariant rate dx₄/dt = ic. The advance is unaffected by the presence of mass: x₄-expansion proceeds at ic at every spacetime event, including events near a mass concentration. The wavelength λ_P of one quantum of x₄-advance is therefore the same at every event.

- **(A2)** Mass affects the spatial geometry x₁, x₂, x₃ — it bends and curves the spatial three. Gravitational time dilation is the projection of invariant proper-time x₄-advance onto a distant observer's coordinate time through the stretched spatial geometry; x₄'s rate does not change near a mass.

- **(A3)** Any momentum-energy carried in x₄ has no rest mass. Photons travel at v = c in space and have dx₄/dτ = 0 on null worldlines (they ride the wavefront, at absolute rest in x₄); massive matter at spatial rest has dx₄/dτ = ic and the entire four-speed budget directed into x₄-advance.

These are not separate postulates beyond dx₄/dt = ic. (A1) is the principle. (A2) is the content of the principle for how mass acts on the geometry, established by the corrected derivation of gravitational time dilation as a spatial-stretching projection. (A3) is the photon-and-massive-matter ontology forced by the master equation u^μ u_μ = -c² together with (A1).

**The Kruskal–Szekeres extension.**

The Schwarzschild metric in standard (t, r, θ, φ) coordinates,

$$
ds^2 \;=\; -\left(1 - \frac{2GM}{rc^2}\right)c^2\,dt^2 \;+\; \left(1 - \frac{2GM}{rc^2}\right)^{-1}dr^2 \;+\; r^2\,d\Omega^2,
$$

has the radial coefficient (1 - 2GM/rc²)⁻¹ diverging as r → rₛ = 2GM/c² from above. Kruskal–Szekeres coordinates (U, V, θ, φ) defined by

$$
U = -e^{-u/(2r_s)}, \qquad V = e^{v/(2r_s)}, \qquad u = ct - r^*, \qquad v = ct + r^*
$$

(with r^* = r + rₛ log|r/rₛ - 1| the tortoise coordinate) recast the metric as

$$
ds^2 \;=\; -\frac{32 G^3 M^3}{r c^6}\, e^{-r/r_s}\, dU\,dV \;+\; r^2\,d\Omega^2,
$$

with r defined implicitly by UV = (1 - r/rₛ) e^(r/rₛ). The metric coefficients in (U, V) are smooth and non-vanishing for all r > 0, and the maximally-extended manifold covers four regions: I (U < 0, V > 0, exterior), II (U > 0, V > 0, black-hole interior), III (U > 0, V < 0, parallel exterior), and IV (U < 0, V < 0, white-hole interior). The curvature singularity at r = 0 lies on the spacelike hyperbola UV = 1 within region II.

Inside region II, the coordinate direction ∂_r becomes timelike and ∂ₜ becomes spacelike — a *role swap* of the radial and time directions relative to the exterior. A timelike worldline traversing region II accumulates proper time along the decreasing-r direction and reaches the singularity at r = 0 in finite proper time of order rₛ/c for radial infallers.

**The role swap is barred by the axioms.**

We show that the Kruskal interior region II, which requires ∂_r to be timelike and ∂ₜ to be spacelike, is structurally inconsistent with the axioms (A1), (A2), (A3). The argument runs through three structurally independent inconsistencies, each sufficient on its own to bar the role swap.

A clarifying remark before the inconsistencies: the McGucken framework distinguishes two notions of *timelike* and *spatial* that standard general relativity identifies. The first is the *coordinate-metric* notion — a direction is timelike or spacelike according to the sign of g_μμ for that coordinate in some chart. The second is the *axiomatic* notion: by (A1), the timelike direction is x₄, the carrier of dx₄/dt = ic; by (A2), spatial directions are those that mass bends and curves. Standard GR makes the two notions coincide globally because the metric is treated as primitive. The McGucken framework treats (A1)–(A3) as primitive, and the metric-signature notion of timelike/spacelike must agree with the axiomatic one wherever the manifold is defined. The Kruskal extension into region II requires the metric-signature notion to flip while the axiomatic one cannot — the mismatch is precisely what bars the extension.

**Inconsistency 1: from (A2).** The axiom (A2) identifies spatial directions by the property that mass bends and curves them. In the exterior Schwarzschild geometry, the radial direction ∂_r is stretched by the factor (1 - 2GM/rc²)^(-1/2), with the stretching becoming infinite at r = rₛ. By (A2), the radial direction is therefore a spatial direction — the identification is forced by the axiomatic content of how mass acts. The identification holds wherever mass is present and acting, which includes the entire region near the mass, not only r > rₛ. The Kruskal extension's reinterpretation of ∂_r as timelike for r < rₛ requires ∂_r to cease being a spatial direction and become a timelike one. By (A2), this reinterpretation is barred: the radial direction was identified as spatial by the axiom of how mass acts, and that identification does not change at the horizon. The metric coefficient changing sign at r = rₛ does not redefine which direction is spatial in the McGucken framework, because in this framework spatiality is fixed by (A2), independently of the local metric signature.

**Inconsistency 2: from (A1).** The axiom (A1) identifies the timelike direction by the property that x₄-expansion proceeds along it at the invariant rate ic. With x₄ = ict, this identifies ∂ₜ (up to the factor ic) as the carrier of dx₄/dt = ic. The Kruskal interior region II requires the metric coefficient g_tt = -(1 - 2GM/rc²)c² to change sign at r = rₛ, so that for r < rₛ the direction ∂ₜ becomes spacelike in the metric-signature sense. By (A1), however, ∂ₜ is the axiomatic timelike direction at every event, because dx₄/dt = ic holds invariantly at every event. Two readings of the role of ∂ₜ inside the horizon are then on offer: either (i) ∂ₜ carries dx₄/dt = ic but is metric-signature spacelike, in which case the standard identification of metric signature with the propagation of the four-velocity (u^μ u_μ < 0 along the timelike direction) breaks at the horizon and the Kruskal extension's notion of ``interior worldline'' loses its standard physical content; or (ii) the carrier of dx₄/dt = ic inside the horizon is something other than ∂ₜ, which directly contradicts (A1) since the principle states that x₄-advance is along x₄ at every event without exception. Reading (ii) is barred by (A1) directly. Reading (i) has the consequence that no massive worldline can extend into region II as a timelike-in-the-master-equation sense, because the master equation u^μ u_μ = -c² requires the four-velocity to lie along the axiomatic timelike direction x₄, and x₄ does not extend into region II in any reading consistent with (A1). The Kruskal interior's identification of ∂_r as the new ``timelike'' direction is therefore barred: even if one tried to relabel ∂_r as carrying dx₄/dt = ic inside the horizon, this would contradict Inconsistency~1 (∂_r is spatial by A2).

**Inconsistency 3: from (A3).** The axiom (A3) states that any momentum-energy carried in x₄ has no rest mass. The contrapositive: massive matter must carry its momentum-energy timelike along x₄, with the entire four-speed budget directed into x₄-advance at rate ic in the rest frame. The Kruskal interior region II, in the standard reading, has massive infallers with timelike worldlines along the ∂_r direction (not along x₄). By (A3), a massive worldline cannot be timelike along anything other than x₄ at rate ic; the only timelike direction along which massive momentum-energy can flow is x₄. A massive infaller traversing region II with proper time accumulating along ∂_r (and not along x₄) violates (A3): either the worldline carries rest mass while being timelike along ∂_r (a non-x₄ direction), which is prohibited by (A3), or the worldline is massless (contradicting that it is a massive infaller).

The three inconsistencies are structurally independent. (A2) fixes ∂_r as spatial. (A1) fixes x₄, not ∂_r, as the carrier of dx₄/dτ = ic, and forbids the metric-signature flip of ∂ₜ at the horizon from being interpreted as a change in the axiomatic timelike direction. (A3) prohibits massive worldlines from being timelike along non-x₄ directions. Each axiom alone bars the Kruskal role swap; together they do so unambiguously.

**Theorem.**

> **Theorem (Singularity-free Schwarzschild geometry).** Under the axioms (A1), (A2), (A3) of the McGucken framework, the Schwarzschild geometry of a mass M consists of the exterior region r > rₛ = 2GM/c² only. The Kruskal interior region II and the curvature singularity at r = 0 are not part of the McGucken manifold. The geometry has a natural boundary at the horizon r = rₛ, where the spatial stretching of ∂_r becomes infinite, and beyond which the manifold does not extend.

*Proof.* By the three inconsistencies above. Each of (A1), (A2), (A3) independently bars the role swap that the Kruskal interior requires. The interior region II is therefore structurally inconsistent with the axioms, and the McGucken manifold does not extend past r = rₛ. The classical curvature singularity at r = 0 lies in region II by construction of the Kruskal extension, hence is not in the McGucken manifold. ∎

**Maximum curvature attained on the McGucken manifold.**

The Kretschmann scalar K = R_μνρσR^(μνρσ) of the Schwarzschild geometry is

$$
K(r) \;=\; \frac{48\, G^2 M^2}{c^4\, r^6}.
$$

Since the McGucken manifold contains only r > rₛ, the curvature is bounded above by its value at the horizon:
\begin{equation}
K_{\max} \;=\; K(r_s) \;=\; \frac{48\, G^2 M^2}{c^4\, r_s^6} \;=\; \frac{48\, G^2 M^2}{c^4\, (2GM/c^2)^6} \;=\; \frac{3\, c^8}{4\, G^4 M^4}.
$$

For a stellar-mass black hole (M ~ 10  M_⊙), the formula evaluates to K_max ~ 10⁻¹⁷ m⁻⁴, corresponding to a curvature radius of order the horizon radius rₛ itself; for supermassive black holes the bound is smaller still by M⁻⁴. The curvature is bounded above everywhere on the manifold; the would-be divergence K(r) → ∞ as r → 0 is not reached because r = 0 is not in the manifold. The bound is mass-dependent (it depends on M, not on λ_P alone), and it follows directly from Theorem: the maximum of K on the manifold is the value of K at the manifold's boundary.

**What this resolution is and is not.**

This is not a regularisation of the singularity by quantum-gravity effects. The framework does not smooth out an infinite curvature; rather, the locus where the curvature would diverge is not part of the manifold to begin with. The singularity is foreclosed structurally, by the axioms of the framework, not by introducing new physics at small scales.

This is also not a coordinate-artifact dismissal of the apparent singularity at r = rₛ in standard (t, r) coordinates. The horizon at r = rₛ is a real boundary of the McGucken manifold, not a coordinate singularity removable by reparametrisation. The Kruskal coordinates' regularity at r = rₛ does not extend the McGucken geometry past the horizon, because the role-swap reinterpretation of ∂_r and ∂ₜ that the Kruskal regularity exploits is barred by the axioms (A1), (A2), (A3). The Kruskal extension is a valid mathematical construction within standard general relativity; it is not consistent with the axioms of the McGucken framework.

**Geodesic incompleteness at the horizon.**

A timelike radial geodesic in the exterior Schwarzschild geometry reaches r = rₛ in finite proper time. In standard general relativity this is taken as a defect of the chart that the Kruskal extension repairs by analytic continuation past r = rₛ. In the McGucken framework, by Theorem, the analytic continuation is not available: the manifold does not extend past r = rₛ. The McGucken manifold is therefore geodesically incomplete at the horizon, and an infalling massive worldline reaches the manifold's boundary in finite proper time.

This is acknowledged here as a structural feature of the framework, not concealed. Standard general relativity treats geodesic incompleteness as pathological and uses it as motivation for analytic continuation; the McGucken framework instead identifies the horizon as a true geodesic boundary forced by the axioms, of the same kind as the boundary of any manifold-with-boundary. Whether such a manifold-with-boundary is the right ontology for spacetime in the presence of a black hole is itself a structural question raised by the framework, but it is the question that the axioms (A1)–(A3) place at the foundation, not a defect to be patched. We do not claim that worldlines ``continue'' past the horizon along an extended manifold; we claim that the manifold ends there, and that what happens to an infalling worldline at the boundary is a question requiring physics beyond the present axioms (analogous to the question of what happens at the boundary of any classical evolution).

**Inputs and dependencies.**

Theorem is conditional on (A1), (A2), (A3) being foundational. (A1) is dx₄/dt = ic itself. (A2) is the specific content of the principle for how mass acts on the geometry, with gravitational time dilation derived as the projection of invariant x₄-advance through stretched spatial geometry rather than as an x₄-rate change. (A3) is the photon-and-massive-matter ontology compatible with (A1) via the master equation u^μ u_μ = -c². A reader who accepts the axioms as foundational accepts the theorem; a reader who challenges the axioms challenges the foundation of the framework rather than the theorem. The companion papers [McGuckenConstants,  McGuckenFeynman,  McGuckenQED] provide the foundational material from which (A1), (A2), (A3) descend.

**The Big Bang singularity.**

The standard Big Bang singularity in the Friedmann–Lema\^itre–Robertson–Walker (FLRW) metric is the locus t = 0 where the scale factor a(t) → 0 and the curvature invariants diverge. The structure of the resolution within the McGucken framework parallels the Schwarzschild case, with the role of the spatial-stretching factor played by the FLRW scale factor and the role of the horizon played by the cosmological origin.

By (A1), x₄-advance proceeds at the invariant rate ic at every cosmological epoch, including arbitrarily early epochs. The wavelength λ_P of one quantum of x₄-advance is the same at every epoch. By (A2), what changes across cosmological time is the spatial geometry: the spatial three contract toward the cosmological origin and expand away from it, with the FLRW scale factor measuring the proper extent of the spatial manifold. The Big Bang is the locus at which the spatial manifold reaches its minimum extent, not the locus at which x₄-advance originates.

The standard treatment runs cosmological evolution backward to t = 0 with a(t) → 0 under the assumption that the spatial geometry contracts continuously to a point. Under the McGucken axioms, the spatial geometry has a minimum extent corresponding to the requirement that at least one quantum of x₄-advance be accommodated — equivalently, that the cosmological evolution span at least one Planck time t_P = λ_P/c. At earlier coordinate times the spatial manifold has not yet acquired enough extent to host the discrete x₄-mode structure required by Hypothesis 1, and the framework's geometry is not defined.

The would-be divergent quantities (energy density ρ ∝ a⁻⁴, Hubble rate H = ȧ/a, curvature invariants) at t = 0 are not features of the McGucken manifold because the manifold does not extend to t = 0. The earliest cosmological moment on the manifold corresponds to t ~ t_P, where the spatial extent is at its minimum and the energy density is bounded above by the Planck energy density ρ_Pᵉⁿᵉʳᵍʸ = c⁷/(ℏ G²) (equivalently, the Planck mass density c⁵/(ℏ G²) multiplied by c²). The fourth dimension is unaffected throughout: x₄-advance proceeds at ic at every cosmological moment, the wavelength λ_P is invariant, and the Big Bang is not the origin of x₄ but the boundary of the spatial manifold's contraction.

This argument is structurally less complete than Theorem. The Schwarzschild result rests on three independent axiom-based inconsistencies; the Big Bang result rests on the same axioms but requires the additional input that the FLRW scale factor's contraction is bounded below by the requirement that one x₄-quantum be accommodated. Whether this requirement is itself a theorem of the axioms (A1)–(A3) plus Hypothesis 1, or whether it requires an additional axiom about the discrete-lattice structure's minimum extent, is not settled here. We state the conclusion at the level the axioms support: the Big Bang singularity is foreclosed by the McGucken framework on the same structural grounds as the Schwarzschild singularity — the spatial manifold reaches a boundary, while x₄ advances invariantly — with the precise structure of the cosmological boundary requiring the additional input above.

## Conclusion

The McGucken Principle, that the fourth dimension is expanding at the velocity of light in a spherically symmetric manner dx₄/dt = ic, vanquishes the two great unwanted infinities of twentieth-century physics — the ultraviolet divergences of QED and the curvature singularities of the Schwarzschild–Kruskal interior and the Big Bang. Both are foreclosed by a structural feature of the framework that follows from dx₄/dt = ic: the continuous-and-discrete geometry of spacetime, with the spatial three continuous and x₄ discrete at the Planck wavelength. Each infinity is foreclosed by the same mechanism, applied at different scales: the manifold is restricted in such a way that the locus where the divergence would live is not part of the geometry. In the QED case, the integration domain along the x₄-conjugate momentum is the finite Brillouin zone of the discrete x₄-lattice; the loop integral is finite by structure, not by regularization. In the Schwarzschild case, the manifold ends at r = rₛ because the Kruskal interior's role swap of ∂_r into a timelike direction is structurally inconsistent with the foundational axioms (A1)–(A3); the locus r = 0 is not part of the manifold. The two results are independent in their content but unified in their mechanism.

Theorem: the one-loop photon vacuum polarization in QED, computed under the hybrid spacetime measure of Hypothesis 1, is finite by the structure of its integration domain. The integration along the x₄-conjugate momentum is over the finite Brillouin zone [-πℏ/λ_P, +πℏ/λ_P], and the integral evaluates explicitly to I_hyb(Δ) = 2π² arcsinh(πℏ/(λ_P√Δ)). The renormalized polarization reproduces the standard α/(3π) running with corrections suppressed by (m/m_P)² ~ 10⁻⁴⁴ at the electron mass, entirely beyond present experimental reach. The standard logarithmic UV divergence is absent — not regulated, but absent — because the integration domain was always finite.

Theorem: the Schwarzschild–Kruskal singularity at r = 0 is not part of the McGucken manifold. The Kruskal interior region II requires a role swap of ∂_r (spatial outside) into a timelike direction (inside), and this role swap is barred by three structurally independent inconsistencies with the axioms (A1)–(A3): (A2) fixes ∂_r as spatial because mass bends it; (A1) fixes x₄ as the unique timelike direction along which dx₄/dt = ic holds invariantly, and forbids the metric-signature flip of ∂ₜ at the horizon from being read as a change in the axiomatic timelike direction; (A3) prohibits massive worldlines from being timelike along non-x₄ directions. The maximum curvature attained on the McGucken manifold is the finite value K_max = 3c⁸/(4G⁴ M⁴) at the horizon, mass-dependent and bounded above. The Big Bang singularity is structurally analogous (the spatial manifold reaching minimum extent rather than x₄-advance halting), with the same structural foreclosure though resting on an additional input about the discrete-lattice minimum extent.

The two results are independent. The QED loop result is mathematical: standard integrals on a hybrid measure. The Schwarzschild result is axiomatic: structural inconsistency of the Kruskal interior with the foundational axioms of the framework. Each holds on its own terms. They share, however, a common structural source: the continuous-and-discrete geometry of the McGucken manifold, in which the spatial three are continuous and x₄ is discrete. The QED divergence is foreclosed by the discreteness of x₄ (which restricts the loop integration domain). The Schwarzschild singularity is foreclosed by the spatial geometry's response to mass (which, by A2, identifies ∂_r as spatial wherever mass is present, and so bars the role swap that the Kruskal extension would require). Both infinities are vanquished by the same framework, applied to two different problems.

What remains open: derivation of Hypothesis 1 from dx₄/dt = ic alone, without auxiliary postulates and without external dimensional input. The corpus [McGuckenSphere] closes the dimensional argument via a three-step sequence (dx₄/dt = ic fixes c; an independent action-quantization postulate defines ℏ; Schwarzschild self-consistency at the substrate scale brings in G and identifies ℓ_* = λ_P) but explicitly acknowledges step (ii) as a postulate rather than a theorem. The hybrid measure of the present paper inherits this status. A derivation from dx₄/dt = ic alone would have to either derive the action-quantization postulate, or supply a different dimensional argument that does not require G as external input, or derive G itself — none of which is currently available. Also open: explicit calculation of higher-loop QED observables under the hybrid measure, of which the vacuum polarization is the simplest case. These are the two open problems of Section.

The two infinities of twentieth-century physics — the ultraviolet divergence of QED loop integrals and the curvature singularity of the Schwarzschild–Kruskal interior — are vanquished by the same underlying mechanism: the continuous-and-discrete geometry of spacetime under the McGucken Principle dx₄/dt = ic, in which the spatial three are continuous and the fourth direction is discrete at the Planck wavelength. The framework reproduces the precision of standard QED at all accessible scales, foreclosing the loop divergence by structure rather than by regularization, and identifies the Schwarzschild horizon as a true geodesic boundary of the manifold rather than a coordinate artifact to be analytically continued past. Both results follow from the foundational axioms (A1)–(A3) of the framework and the hybrid measure of Hypothesis 1.

—

## References

**[McGuckenPresent]** 
McGucken, E. *Vanquishing Infinities and Singularities via the Continuous and Discrete McGucken Spacetime Geometry — Two Theorems of the McGucken Principle dx₄/dt = ic: Finite One-Loop QED Vacuum Polarization on a Hybrid Continuous–Discrete Measure, and Axiomatic Foreclosure of the Schwarzschild–Kruskal Interior*. elliotmcguckenphysics.com. <https://elliotmcguckenphysics.com/2026/05/05/vanquishing-infinities-and-singularities-via-the-continuous-and-discrete-mcgucken-spacetime-geometry-two-theorems-of-the-mcgucken-principle-dx%E2%82%84-dt-ic-finite-one-loop-qed-vacuum-polarizatio/>

**[McGuckenSphere]** 
McGucken, E. *The McGucken Sphere as Spacetime's Foundational Atom: Deriving Arkani-Hamed's Amplituhedron and Penrose's Twistors as Theorems of the McGucken Principle dx₄/dt = ic*. elliotmcguckenphysics.com. <https://elliotmcguckenphysics.com/2026/04/27/the-mcgucken-sphere-as-spacetimes-foundational-atom-deriving-arkani-hameds-amplituhedron-and-penroses-twistors-as-theorems-of-the-mcgucken-principle-dx4-dtic/>

**[McGuckenConstants]** 
McGucken, E. *How the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic Sets the Constants c (the Velocity of Light) and h (Planck's Constant)*. elliotmcguckenphysics.com. <https://elliotmcguckenphysics.com/2026/04/11/how-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx4-dtic-sets-the-constants-c-the-velocity-of-light-and-h-plancks-constant/>

**[McGuckenFeynman]** 
McGucken, E. *Feynman Diagrams as Theorems of the McGucken Principle: Propagators, Vertices, Loops, Wick Contractions, and the Dyson Expansion as Iterated Huygens-with-Interaction on the Expanding Fourth Dimension*. elliotmcguckenphysics.com. <https://elliotmcguckenphysics.com/2026/04/23/feynman-diagrams-as-theorems-of-the-mcgucken-principle-propagators-vertices-loops-wick-contractions-and-the-dyson-expansion-as-iterated-huygens-with-interaction-on-the-expanding-fourth-dimension/>

**[McGuckenQED]** 
McGucken, E. *Quantum Electrodynamics from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic: Local x₄-Phase Invariance, the U(1) Gauge Structure, Maxwell's Equations, and the QED Lagrangian*. elliotmcguckenphysics.com. <https://elliotmcguckenphysics.com/2026/04/19/quantum-electrodynamics-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-dx%E2%82%84-dt-ic-local-x%E2%82%84-phase-invariance-the-u1-gauge-structure-maxwells-equations-and-the-qed/>

**[McGuckenWickRotation]** 
McGucken, E. *The McGucken Principle dx₄/dt=ic Necessitates the Wick Rotation and i Throughout Physics: A Reduction of Thirty-Four Independent Inputs of Quantum Field Theory, Quantum Mechanics, and Symmetry Physics to a Single Physical Principle*. elliotmcguckenphysics.com. <https://elliotmcguckenphysics.com/2026/05/01/the-mcgucken-principle-dx4-dtic-necessitates-the-wick-rotation-and-i-throughout-physics-a-reduction-of-thirty-four-independent-inputs-of-quantum-field-theory-quantum-mechanics-and-symmetry-physics/>

**[KontsevichSegal2021]** 
Kontsevich, M., \& Segal, G. Wick Rotation and the Positivity of Energy in Quantum Field Theory. *Quarterly Journal of Mathematics* **72**, 673; arXiv:2105.10161.

**[PeskinSchroeder]** 
Peskin, M.~E., \& Schroeder, D.~V. *An Introduction to Quantum Field Theory*. Westview Press.

**[Schwinger1948]** 
Schwinger, J. On Quantum-Electrodynamics and the Magnetic Moment of the Electron. *Physical Review* **73**, 416–417.

**[KruskalSzekeres]** 
Kruskal, M.~D. Maximal Extension of Schwarzschild Metric. *Physical Review* **119**, 1743–1745. Szekeres, G. On the Singularities of a Riemannian Manifold. *Publicationes Mathematicae Debrecen* **7**, 285.

—

*Submitted to elliotmcguckenphysics.com.*

 **Author:** Elliot McGucken, PhD — Theoretical Physics. Undergraduate research with John Archibald Wheeler, Princeton University. PhD, University of North Carolina at Chapel Hill.

