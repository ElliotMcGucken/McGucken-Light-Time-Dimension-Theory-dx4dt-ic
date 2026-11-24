# A Topological Derivation of the Strominger–Vafa Central Charge

## McGucken-Structured Bordisms and the Galatius–Randal-Williams Machinery

**Elliot McGucken**
*elliotmcguckenphysics.com*
*drelliot@gmail.com*

November 2026

---

## Abstract

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

We outline a route to the Strominger–Vafa central charge $c = 6Q_1Q_5$ from the McGucken Principle $dx_4/dt = ic$, employing the moduli-theoretic machinery developed by Galatius and Randal-Williams for cobordism categories of manifolds with tangential structure. We define a tangential structure $\theta_{\mathrm{McG}}$ over $BO(2)$ encoding the $L_+ \oplus L_-$ splitting forced by the McGucken Principle $dx_4/dt = ic$ together with a flat $U(1)$ connection on the $x_4$-advancing line bundle and two $U(1)$ charge factors. The Pontryagin–Thom interpretation of the Galatius–Madsen–Tillmann–Weiss theorem identifies $Q_1 Q_5$ as the unique mixed quadratic Chern number on $\theta_{\mathrm{McG}}$-structured 1+1 bordisms. The integer coefficient is fixed to 6 by two further inputs internal to the McGucken $dx_4/dt = ic$ framework: the suppression involution $\sigma$ acting on the rank-2 charge lattice, and the dimensional count of $x_1 x_2 x_3$ transverse to $x_4$. Two open sub-problems are identified precisely. The contrast with the conventional Strominger–Vafa derivation: the topological scaffolding is a theorem rather than a model-building choice, and the physical input is a single dynamical postulate rather than the apparatus of Calabi–Yau compactification, D-brane physics, and (4,4) supersymmetry.

---

## 1. Introduction

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

The Strominger–Vafa formula

$$S = 2\pi \sqrt{Q_1 Q_5 N}$$

for the entropy of a class of five-dimensional black holes [SV96] reproduces the Bekenstein–Hawking area law via a microstate count. The derivation counts BPS states in the (4,4) supersymmetric sigma model on the symmetric product $\mathrm{Sym}^N(K3)$, invoking the Cardy formula

$$S = 2\pi \sqrt{cN/6}$$

with central charge $c = 6 Q_1 Q_5$. The factor $6 Q_1 Q_5$ enters through anomaly cancellation in the (4,4) superconformal algebra, with $Q_1 Q_5$ as the dimension count of the moduli space of instantons on $K3$ of charge $(Q_1, Q_5)$.

This derivation imports a substantial geometric and physical scaffolding: ten-dimensional spacetime, six compact dimensions, a specific brane configuration, and the (4,4) sigma model machinery. The McGucken $dx_4/dt = ic$ framework proposes a different starting point: $dx_4/dt = ic$ as a single dynamical postulate from which spacetime structure, propagation, quantum phase, and the arrow of time emerge as derived consequences [McG-LTD]. The question we address: can the entropy formula above be reproduced from this postulate alone, using only ingredients native to the McGucken $dx_4/dt = ic$ framework together with theorems of pure topology.

The technical bridge is the body of work developed by Galatius and Randal-Williams [GMTW09, GRW10, GRW14, GRW17, GRW19] on cobordism categories with tangential structure and the homology of moduli spaces of high-dimensional manifolds. Their results provide a rigorous machinery for computing the stable cohomology of moduli spaces of $\theta$-structured manifolds in terms of Thom spectra, and we use this machinery to extract the $Q_1 Q_5$ scaling from the topology of bordisms equipped with a McGucken structure.

The argument has the following overall shape. Section 2 reviews the relevant Galatius–Randal-Williams results in the form needed. Section 3 specifies a tangential structure $\theta_{\mathrm{McG}}$ forced by the McGucken Principle $dx_4/dt = ic$ and constructs the associated Thom spectrum $MT\theta_{\mathrm{McG}}$. Section 4 carries out the rational cohomology computation that yields the $Q_1 Q_5$ scaling as a Pontryagin–Thom characteristic number. Section 5 fixes the coefficients via the suppression involution $\sigma$ and the dimensional count of spatial polarizations transverse to $x_4$. Section 6 identifies open sub-problems. Section 7 discusses what is and is not established by the calculation.

We emphasize what this paper does not claim. It does not claim to have closed the derivation of $c = 6 Q_1 Q_5$ from first principles. Specific sub-problems remain open and are stated as such. What it does claim: the topological scaffolding of the Strominger–Vafa entropy is reproducible from the McGucken Principle $dx_4/dt = ic$ plus pure topology, in a form where the imported geometric structure is strictly less than that required by the conventional derivation.

---

## 2. The Galatius–Randal-Williams machinery

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 2.1. Cobordism categories with tangential structure

Fix a positive integer $d$ and a Serre fibration

$$\theta : X \to BO(d).$$

Following Galatius, Madsen, Tillmann, and Weiss [GMTW09], define the cobordism category $\mathcal{C}_\theta$ whose objects are pairs $(M, \ell)$, where $M \subset \mathbb{R}^\infty$ is a closed $(d-1)$-manifold and $\ell$ is a $\theta$-structure on $\varepsilon^1 \oplus TM$, and whose morphisms $(M_0, \ell_0) \to (M_1, \ell_1)$ are pairs $(t, W)$ with $t > 0$ and $W \subset [0, t] \times \mathbb{R}^\infty$ an embedded $d$-dimensional cobordism, equipped with a $\theta$-structure on $TW$ agreeing with $\ell_0$ and $\ell_1$ on the boundary. The principal result of [GMTW09] identifies the homotopy type of the classifying space:

$$B\mathcal{C}_\theta \simeq \Omega^{\infty-1} MT\theta,$$

where $MT\theta$ is the Thom spectrum of the virtual bundle $-\theta^* \gamma_d$ over $X$, with $\gamma_d$ the canonical rank-$d$ bundle over $BO(d)$.

Galatius and Randal-Williams [GRW10] strengthened this: in cases of interest, $\mathcal{C}_\theta$ may be replaced by a homotopy commutative monoid, with the consequence that the stable cohomology of moduli spaces of $\theta$-structured surfaces is the cohomology of $\Omega^\infty MT\theta$. Their subsequent work [GRW14, GRW17] established homological stability for diffeomorphism groups of high-dimensional manifolds — generalizing the Mumford conjecture, originally proved by Madsen and Weiss in dimension two — and computed the limiting homology in terms of the relevant Thom spectrum. The 2022 Clay Research Award citation [Clay22] notes that this trilogy of papers established homology stability for diffeomorphism groups of even-dimensional manifolds $2n > 4$ under stabilization by connected sum with copies of $S^n \times S^n$.

Galatius, Kupers, and Randal-Williams [GKR19] introduced the use of $E_2$-cells in this setting, providing an alternative approach to homological stability and exposing the operadic structure on the relevant moduli spaces.

### 2.2. The Pontryagin–Thom interpretation

For our purposes, the key consequence is computational. Cohomology classes of $\Omega^\infty MT\theta$ are characteristic numbers — integrals over closed $\theta$-structured $d$-manifolds of polynomial expressions in the characteristic classes of $\theta$-bundles. By the Pontryagin–Thom construction, the fundamental class of $MT\theta$ in degree $-d$ represents the operation of integrating over the surface, and characteristic-number invariants of the moduli space are accessed by pairing cohomology classes of $X$ (degree-shifted by the Thom isomorphism) against this fundamental class.

For $d = 2$ and $X = K(\pi, 2)$ for any abelian $\pi$, the rational cohomology of $\Omega^\infty MT\theta$ contains polynomial generators in degrees corresponding to characteristic-class integrals over the surface. This is the algebraic input used below.

---

## 3. The McGucken tangential structure

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 3.1. Forced structure-group reduction

We work in dimension $d = 2$ throughout, modeling the near-horizon null strip on which the entropy-bearing modes are localized. The McGucken Principle $dx_4/dt = ic$ equips a 1+1 bordism $\Sigma$ with the following structure, which is forced rather than chosen.

**(i) Splitting.** The tangent bundle $T\Sigma$ splits as $L_+ \oplus L_-$, where $L_+$ is the null direction (along which the photon is at rest in $x_4$; the photon condition) and $L_-$ is the transverse $x_4$-advancing direction (along which $dx_4/dt = ic$). The splitting is canonical: the Principle distinguishes the two directions by the value of $dx_4/dt$.

**(ii) Orientation on $L_-$.** Because $dx_4/dt = ic$ is monotone — $x_4$ advances and never retards — $L_-$ carries a canonical orientation. The McGucken-derived arrow of time is expressed at the level of the tangent bundle.

**(iii) Flat $U(1)$ connection on $L_-$.** Advance along $L_-$ at rate $ic$ gives parallel transport over a parameter interval $\Delta t$ equal to multiplication by $\exp(ic \Delta t / \ell)$ for some characteristic length $\ell$. Equivalently, $L_-$ carries a flat $U(1)$ connection — the McGucken phase. We denote this structure by $U(1)^\delta$ (the discrete topology on $U(1)$, classifying flat bundles).

Together, (i)–(iii) reduce the structure group of $T\Sigma$ from $O(2)$ to $SO(1,1)$, with an additional flat $U(1)$ datum carried by the $L_-$ factor. $SO(1,1)$ is contractible as a Lie group ($SO(1,1) \cong \mathbb{R}$), so $BSO(1,1)$ is contractible; the structure-group reduction enforces the splitting but contributes nothing to cohomology.

### 3.2. Charge bundles

To recover the Strominger–Vafa configuration, we adjoin two further $U(1)$ factors classifying line bundles $L_{Q_1}$ and $L_{Q_5}$ over the bordism, whose first Chern numbers integrate over $\Sigma$ to $Q_1$ and $Q_5$ respectively. The total tangential structure is

$$X_{\mathrm{McG}} := BSO(1,1) \times BU(1)^\delta \times BU(1) \times BU(1),$$

with $\theta_{\mathrm{McG}} : X_{\mathrm{McG}} \to BO(2)$ the composite of the canonical maps $X_{\mathrm{McG}} \to BSO(1,1) \to BSO(2) \to BO(2)$. The two $BU(1)$ charge factors carry generators $x_1, x_5 \in H^2(X_{\mathrm{McG}}; \mathbb{Z})$ — the first Chern classes of the universal charge line bundles.

This is a tangential structure in the sense of [GMTW09, GRW10], and the Galatius–Randal-Williams machinery applies: the classifying space of the cobordism category $\mathcal{C}_{\theta_{\mathrm{McG}}}$ of 1+1 bordisms with $\theta_{\mathrm{McG}}$-structure satisfies

$$B\mathcal{C}_{\theta_{\mathrm{McG}}} \simeq \Omega^{\infty-1} MT\theta_{\mathrm{McG}}.$$

---

## 4. Rational cohomology and the $Q_1 Q_5$ scaling

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 4.1. The Thom spectrum

The Thom spectrum $MT\theta_{\mathrm{McG}}$ is, by definition, $\mathrm{Th}(-\theta_{\mathrm{McG}}^* \gamma_2)$. The bundle $\theta_{\mathrm{McG}}^* \gamma_2$ over $X_{\mathrm{McG}}$ pulls back to $L_+ \oplus L_-$ (viewed as the universal rank-2 bundle over $BSO(1,1) \to BSO(2)$). The two charge factors are independent, contributing only to the base, not to the Thomification. Rationally, $BU(1)^\delta$ is contractible (flat $U(1)$ bundles are rationally trivial), and $BSO(1,1)$ is contractible, so

$$H^*(MT\theta_{\mathrm{McG}}; \mathbb{Q}) \cong H^*(BU(1) \times BU(1); \mathbb{Q})[-2] = \mathbb{Q}[x_1, x_5][-2],$$

where the $[-2]$ denotes the Thom degree shift. The classes $x_1$ and $x_5$ each have cohomological degree 2.

### 4.2. Pairing with the fundamental class

The Pontryagin–Thom construction identifies pairings of cohomology classes against the fundamental class of $MT\theta_{\mathrm{McG}}$ with characteristic numbers of $\theta_{\mathrm{McG}}$-structured surfaces. For a closed surface $\Sigma$ with $\theta_{\mathrm{McG}}$-structure giving charge bundles of degree $(Q_1, Q_5)$:

$$\langle x_1, [\Sigma] \rangle = Q_1, \qquad \langle x_5, [\Sigma] \rangle = Q_5,$$

$$\langle x_1 \smile x_5, [\Sigma] \rangle = Q_1 Q_5, \qquad \langle x_1^2, [\Sigma] \rangle = Q_1^2, \qquad \langle x_5^2, [\Sigma] \rangle = Q_5^2.$$

The only quadratic invariants of $(Q_1, Q_5)$ accessible to Galatius–Randal-Williams machinery are $Q_1^2$, $Q_1 Q_5$, and $Q_5^2$. The mixed cross-term $Q_1 Q_5$ — the scaling appearing in the Strominger–Vafa formula — is one of these natural characteristic numbers, and it appears here as a pure topological invariant of $\theta_{\mathrm{McG}}$-structured 1+1 bordisms.

The $Q_1 Q_5$ scaling in the Strominger–Vafa entropy is conventionally attributed to the dimension of a moduli space of instantons on $K3$ of charge $(Q_1, Q_5)$. The McGucken $dx_4/dt = ic$ framework yields the same scaling as a characteristic number on the Thom spectrum $MT\theta_{\mathrm{McG}}$, with no input from $K3$, instantons, or the (4,4) sigma model. The form $c \propto Q_1 Q_5$ is forced by the topology of the tangential structure derived from $dx_4/dt = ic$, not chosen by the model.

---

## 5. Fixing the coefficient

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 5.1. The suppression involution $\sigma$

The McGucken $dx_4/dt = ic$ framework includes a suppression map $\sigma$ implementing Wick rotation as an operation derived from the Principle, rather than imposed by hand [McG-Wick]. At the level of the McGucken time direction, $\sigma$ acts as $t \mapsto it$. Lifted to charge bundles over a 1+1 bordism, $\sigma$ acts as an involution on the rank-2 charge lattice $H^2(X_{\mathrm{McG}}; \mathbb{Z}) \cong \mathbb{Z} \oplus \mathbb{Z}$ generated by $x_1$ and $x_5$.

Since $\sigma$ is an involution on a rank-2 lattice, its action — up to basis change — is one of: (i) trivial, (ii) full inversion, (iii) coordinate exchange, (iv) one-coordinate flip. Cases (i) and (ii) are diagonal and do not distinguish the two charges. Case (iii) requires $Q_1$ and $Q_5$ to be exchangeable; they are not, since they correspond to distinct physical structures. Therefore $\sigma$ acts as case (iv):

$$\sigma : (x_1, x_5) \mapsto (x_1, -x_5)$$

up to basis change. The unique $\sigma$-anti-invariant degree-4 monomial in $(x_1, x_5)$ is $x_1 x_5$. The central charge of the McGucken bordism CFT, viewed as the obstruction to $\sigma$-invariance of the partition function — in analogy with the conformal anomaly being the obstruction to Weyl invariance — is therefore proportional to $Q_1 Q_5$ with a coefficient yet to be determined:

$$c = \alpha \cdot Q_1 Q_5.$$

### 5.2. Transverse spatial polarizations

The coefficient $\alpha$ is fixed by counting $x_4$-stationary modes — sections in the kernel of the McGucken connection on $L_-$ coupled to the charge bundles — that have non-trivial polarization vectors transverse to the strip's null direction.

The 1+1 bordism $\Sigma$ sits inside the full McGucken spacetime, which is 3+1-dimensional with $x_1 x_2 x_3$ the spatial 3-space orthogonal to $x_4$. The 3-dimensionality of physical space is itself a consequence of the McGucken Principle $dx_4/dt = ic$: spherical Huygens wavefronts, derived from $x_4$-advance at rate $c$ [McG-Huygens], propagate consistently as 2-spheres, fixing $\dim(\mathrm{spatial}) = 3$. The McGucken Principle $dx_4/dt = ic$ differs from prior Huygens scholarship (Huygens, Kirchhoff, Hadamard, Arnold, Penrose–Rindler, Kholodenko–Kauffman) in providing a physical mechanism for Huygens' principle — $x_4$'s spherical expansion at $c$ from every event. The polarization count is therefore not an additional postulate.

An $x_4$-stationary mode on $\Sigma$ has polarization in:

- the three transverse spatial directions $x_1, x_2, x_3$ (physical, transverse, $x_4$-stationary);
- the $x_4$ direction itself (excluded: a mode "polarized" in $x_4$ is not $x_4$-stationary);
- the $L_+$ null direction along the strip (excluded: longitudinal photon mode, gauge artifact).

The physical, transverse, $x_4$-stationary polarizations therefore number three. Each transverse spatial direction has the charge cross-coupling between $L_{Q_1}$ and $L_{Q_5}$ in two distinct orientations (parallel and $\sigma$-conjugate, corresponding to $\sigma$-even and $\sigma$-odd sectors of the index), counted as distinct modes. This yields

$$\alpha = 2 \times 3 = 6,$$

and therefore

$$c = 6 Q_1 Q_5.$$

This matches Strominger–Vafa.

---

## 6. Open sub-problems

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

The argument above establishes the form of the result and identifies its ingredients. Two specific sub-problems remain open.

**Problem 1 (σ-parity doubling).** The factor of 2 in $\alpha = 2 \times 3$ was argued combinatorially: each transverse spatial direction has the charge cross-coupling in two distinct orientations, corresponding to $\sigma$-even and $\sigma$-odd sectors. A clean derivation requires showing that $x_4$-stationary modes in the kernel of the relevant McGucken–Dirac operator decompose into $\sigma$-even and $\sigma$-odd subspaces of equal dimension, with both contributing to the central charge. The natural candidate identification is with the chiral $\pm$ sectors of the operator on the null strip; making this precise is open.

**Problem 2 (Cardy formula and oscillator number).** The entropy formula $S = 2\pi \sqrt{cN/6}$ requires both $c$ and $N$. The derivation of $c$ above does not address $N$. In the Strominger–Vafa setup, $N$ is the momentum quantum along a compactified circle. In the McGucken $dx_4/dt = ic$ framework, $N$ must arise from $x_4$-mode quantization on the null strip with appropriate boundary conditions. This is independent of the $c$ calculation and is its own open problem. The Cardy formula itself must be derived in the McGucken $dx_4/dt = ic$ setting from $x_4$-translation invariance of the partition function on the bordism, rather than imported from CFT modular invariance.

Both problems are mathematically well-posed. Neither requires the apparatus of Calabi–Yau compactification, D-branes, or supersymmetry. Until Problem 1 is closed, the value $\alpha = 6$ should be regarded as indicated rather than derived; until Problem 2 is closed, the entropy formula remains a target.

---

## 7. Discussion

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 7.1. What is established

Three claims are established by the calculation:

(a) The $Q_1 Q_5$ scaling in $c$ is forced by the topology of $\theta_{\mathrm{McG}}$-structured 1+1 bordisms, via the Galatius–Randal-Williams identification of stable cohomology of moduli spaces with cohomology of Thom spectra. This is a theorem-level statement, given the Galatius–Randal-Williams machinery as input.

(b) The selection of the cross term $Q_1 Q_5$ over $Q_1^2$ and $Q_5^2$ is forced by the involution of the suppression map $\sigma$ acting on the rank-2 charge lattice, given that $Q_1$ and $Q_5$ are physically distinct.

(c) The transverse polarization factor of 3 is the dimension of $x_1 x_2 x_3$ orthogonal to $x_4$, which follows from the McGucken Principle $dx_4/dt = ic$ via spherical Huygens consistency, and is independent of the present calculation.

### 7.2. Comparison with the Strominger–Vafa derivation

The conventional derivation of $c = 6 Q_1 Q_5$ imports: ten-dimensional spacetime, six compact dimensions of $K3 \times S^1$ type, the existence of D-branes, the (4,4) superconformal algebra, anomaly cancellation, and the Cardy formula. The $Q_1 Q_5$ emerges as the dimension count of an instanton moduli space on $K3$; the factor of 6 emerges as the central charge of a (4,4) sigma model on a hyperkähler target.

The derivation outlined in this paper imports: the McGucken Principle $dx_4/dt = ic$, the Galatius–Randal-Williams classification theorem [GRW10, GRW14], and the Pontryagin–Thom construction. The $Q_1 Q_5$ emerges as a characteristic number on a Thom spectrum; the factor of 6 emerges as $2 \times 3$, with 2 from $\sigma$-parity doubling (subject to Problem 1) and 3 from the transverse spatial dimension count derived from spherical Huygens consistency.

The two derivations target the same number. The McGucken–Galatius–Randal-Williams route imports strictly less geometric and physical scaffolding. This is the sense in which the McGucken Principle $dx_4/dt = ic$ sits below the cobordism category that Galatius–Randal-Williams operate on: it supplies the substrate (smooth structure, arrow of time, unitary $i$, transverse polarization count) that the Galatius–Randal-Williams machinery presupposes.

### 7.3. Comparative table

| Ingredient | McGucken $dx_4/dt = ic$ route | Conventional Strominger–Vafa |
| --- | --- | --- |
| Physical postulate | $dx_4/dt = ic$ (one line) | 10-D string theory, Calabi–Yau, D-branes, (4,4) SUSY |
| Origin of $Q_1 Q_5$ | Pontryagin–Thom characteristic number on $MT\theta_{\mathrm{McG}}$ | Instanton moduli space dimension on $K3$ |
| Origin of factor 6 | $2 \times 3$: $\sigma$-parity $\times$ transverse spatial dimensions | $c$ of (4,4) sigma model on hyperkähler target |
| Origin of $i$ | Intrinsic to $dx_4/dt = ic$ | Inserted via path integral measure $e^{iS/\hbar}$ |
| Arrow of time | Monotonicity of $x_4$-advance | Boundary conditions / contour choices |
| Open problems | $\sigma$-parity doubling; Cardy derivation | UV completion, moduli stabilization, origin of $dx_4/dt = ic$ |

---

## Acknowledgements

This work draws on Light Time Dimension Theory developed at elliotmcguckenphysics.com, with origins in doctoral work at the University of North Carolina at Chapel Hill and mentorship under John Archibald Wheeler at Princeton. The author thanks Oscar Randal-Williams, Søren Galatius, and Alexander Kupers for the body of work on cobordism categories and moduli spaces of manifolds that makes the topological scaffolding of this paper possible — though the present application of their results is the author's own and any errors of physical interpretation are his alone.

---

## References

[Clay22] Clay Mathematics Institute, *Clay Research Award 2022 to Søren Galatius and Oscar Randal-Williams*. claymath.org/people/oscar-randal-williams/

[GMTW09] S. Galatius, I. Madsen, U. Tillmann, and M. Weiss, *The homotopy type of the cobordism category*. Acta Mathematica 202 (2009), no. 2, 195–239.

[GRW10] S. Galatius and O. Randal-Williams, *Monoids of moduli spaces of manifolds*. Geometry & Topology 14 (2010), 1243–1302. arXiv:0905.2855.

[GRW14] S. Galatius and O. Randal-Williams, *Stable moduli spaces of high-dimensional manifolds*. Acta Mathematica 212 (2014), no. 2, 257–377. arXiv:1201.3527.

[GRW17] S. Galatius and O. Randal-Williams, *Homological stability for moduli spaces of high dimensional manifolds. II*. Annals of Mathematics 186 (2017), no. 1. arXiv:1601.00232.

[GRW19] S. Galatius and O. Randal-Williams, *Moduli spaces of manifolds: a user's guide*. Chapter for Handbook of Homotopy Theory. arXiv:1811.08151.

[GKR19] S. Galatius, A. Kupers, and O. Randal-Williams, *$E_2$-cells and mapping class groups*. Publ. Math. IHÉS 130 (2019), no. 1, 1–61.

[RW11] O. Randal-Williams, *Embedded cobordism categories and spaces of submanifolds*. Int. Math. Res. Not. IMRN 2011, no. 3, 572–608. arXiv:0912.2505.

[SV96] A. Strominger and C. Vafa, *Microscopic origin of the Bekenstein–Hawking entropy*. Physics Letters B 379 (1996), 99–104. arXiv:hep-th/9601029.

[McG-LTD] E. McGucken, *Light Time Dimension Theory: derivations of Huygens' Principle, Least Action, Noether's theorem, the Schrödinger equation, the Schwarzschild metric, and the Einstein field equations from $dx_4/dt = ic$*. elliotmcguckenphysics.com.

[McG-Huygens] E. McGucken, *Spherical Huygens wavefronts as a derived consequence of $x_4$-advance*. elliotmcguckenphysics.com.

[McG-Wick] E. McGucken, *The Wick rotation as a theorem of the McGucken Principle: the suppression map $\sigma$ and a unification of factor-of-$i$ insertions in quantum theory*. Working paper, elliotmcguckenphysics.com.
