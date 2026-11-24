# A Derivation of the Uncertainty Principle ΔxΔp ≥ ℏ/2 from the McGucken Principle of a Fourth Expanding Dimension dx₄/dt = ic

## The Fourth Dimension, the Imaginary Unit, and the Uncertainty Principle

**Elliot McGucken**
drelliot@gmail.com
November 2026

---

## Abstract

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality. This paper derives the Heisenberg uncertainty principle $\Delta x\,\Delta p \ge \hbar/2$ from the McGucken equation $dx_4/dt = ic$. The equation fixes the four-velocity magnitude at $c$ for every particle, and the contraction $p_\mu x^\mu/\hbar$ of four-momentum with four-position gives each particle the phase $e^{i(\mathbf{p}\cdot\mathbf{x} - Et)/\hbar}$. Momentum is the spatial winding rate of this phase. A particle localized to width $\sigma_x$ is a superposition of winding rates spanning $\sigma_p = \hbar/(2\sigma_x)$. The Cauchy–Schwarz inequality, with $[\hat x,\hat p] = i\hbar$, gives the general bound. Each factor of $i$ in the derivation is the factor of $i$ in $dx_4/dt = ic$.

---

## 1. The McGucken Principle dx₄/dt = ic Reading of the Uncertainty Principle: Introduction

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** The McGucken Principle $dx_4/dt = ic$ predicts that every object, including one at rest in the three spatial dimensions, advances through $x_4$ at rate $c$, and that this advance carries a complex phase. The uncertainty principle is the reciprocal-width property of that phase.

Minkowski (1908) wrote the fourth coordinate as $x_4 = ict$ [1]; Poincaré (1906) had used the imaginary fourth coordinate $\sqrt{-1}\,ct$ [2]; Sommerfeld (1909) read the Lorentz transformation as a rotation through an imaginary angle in this space [3]. McGucken differentiates $x_4 = ict$ with respect to coordinate time and states the result as a physical principle about the rate at which the fourth dimension expands [4]. This paper takes that principle as its starting point and derives $\Delta x\,\Delta p \ge \hbar/2$.

The mathematics of Sections 4–5 (Fourier analysis of a Gaussian, Cauchy–Schwarz, the canonical commutator) is textbook material [8, 9, 10, 15]. The McGucken-specific step is Section 3, which obtains the quantum phase from $dx_4/dt = ic$, and Section 6, which traces every $i$ and $\hbar$ to the Principle.

*Evidence level: Sections 4–5, verified-read against standard derivations (background knowledge); Section 3 and Section 6, derivation steps shown in full below; McGucken's own statements, web-digest of elliotmcguckenphysics.com.*

---

## 2. The McGucken Principle dx₄/dt = ic Reading of the Four-Velocity

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** For an object at rest in space, $dx_4/dt = ic$ gives a four-velocity of magnitude $c$ pointing entirely along $x_4$. Spatial motion at speed $v$ reduces the $x_4$ rate to $c\sqrt{1 - v^2/c^2}$.

The four-velocity $U^\mu = dx^\mu/d\tau$ satisfies [7]

$$\eta_{\mu\nu}U^\mu U^\nu = -c^2, \qquad \eta = \mathrm{diag}(-1,+1,+1,+1). \tag{1}$$

For a particle at rest in space, $dx/d\tau = dy/d\tau = dz/d\tau = 0$, and the whole of $U^\mu$ lies along $x_4$. At spatial speed $v$,

$$v^2 + \left|\frac{dx_4}{dt}\right|^2 = c^2 \;\Longrightarrow\; \left|\frac{dx_4}{dt}\right| = c\sqrt{1 - v^2/c^2}. \tag{2}$$

A photon has $v = c$ and is at rest in $x_4$ ($v_{x_4} = 0$).

The factor $i$ in $x_4 = ict$ gives $x_4^2 = -c^2t^2$, which is the minus sign in the interval $s^2 = x^2 + y^2 + z^2 - c^2t^2$.

---

## 3. The McGucken Principle dx₄/dt = ic Reading of the Quantum Phase

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** A particle advancing through $x_4$ at rate $c$ accumulates phase at the rate $E/\hbar$ in time and $p/\hbar$ in space. The McGucken Sphere's wavelength sets the action $h$, so $\hbar = h/2\pi$ is the action per unit phase in this accumulation.

A particle of four-momentum $p^\mu = (E/c, p_x, p_y, p_z)$ has the wave function

$$\psi = \exp\!\left(\frac{i\,p_\mu x^\mu}{\hbar}\right) = \exp\!\left(\frac{i(-Et + \mathbf{p}\cdot\mathbf{x})}{\hbar}\right). \tag{3}$$

With $x_4 = ict$ and $p_4 = iE/c$, the fourth-component term is

$$\frac{p_4 x_4}{\hbar} = \frac{(iE/c)(ict)}{\hbar} = \frac{i^2 Et}{\hbar} = -\frac{Et}{\hbar}. \tag{4}$$

Two factors of $i$, one from $x_4$ and one from $p_4$, multiply to $-1$ and produce the sign in the temporal phase $e^{-iEt/\hbar}$, which has modulus 1 at all times. The spatial part $\mathbf{p}\cdot\mathbf{x}/\hbar$ completes one cycle over $\lambda = h/|\mathbf{p}|$, the de Broglie wavelength [14]. The de Broglie relation and the time dependence $e^{-iEt/\hbar}$ are the spatial and temporal projections of the single phase (3).

---

## 4. The McGucken Principle dx₄/dt = ic Reading of Localization: the Wave Packet

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** Each momentum eigenstate $e^{ipx/\hbar}$ is one spatial winding rate of the phase (3). A particle with a single winding rate has $\Delta p = 0$ and $\Delta x = \infty$. Localization in $x$ requires a superposition of winding rates:

$$\psi(x) = \int \varphi(p)\, e^{ipx/\hbar}\, dp. \tag{5}$$

For a Gaussian of position width $\sigma_x$,

$$\psi(x) = (2\pi\sigma_x^2)^{-1/4}\exp\!\left(-\frac{x^2}{4\sigma_x^2}\right), \tag{6}$$

the Fourier transform is a Gaussian [8]

$$\varphi(p) = (2\pi\sigma_p^2)^{-1/4}\exp\!\left(-\frac{p^2}{4\sigma_p^2}\right), \qquad \sigma_p = \frac{\hbar}{2\sigma_x}. \tag{7}$$

Therefore

$$\sigma_x\,\sigma_p = \frac{\hbar}{2}. \tag{8}$$

The Gaussian has the minimum product. Section 5 shows that every other envelope has a larger one.

---

## 5. The McGucken Principle dx₄/dt = ic Reading of the Commutator and the General Bound

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** The eigenfunction of the spatial-translation generator is $e^{ipx/\hbar}$ from (3). Applying $\partial/\partial x$ to it gives $(ip/\hbar)\,e^{ipx/\hbar}$, so the momentum operator is

$$\hat p = -i\hbar\,\frac{\partial}{\partial x}. \tag{9}$$

The $i$ in (9) is the $i$ of the phase (3).

On a test function $f(x)$,

$$[\hat x,\hat p]f = x(-i\hbar f') + i\hbar\,(xf)' = -i\hbar x f' + i\hbar f + i\hbar x f' = i\hbar f, \tag{10}$$

so $[\hat x,\hat p] = i\hbar$.

Define $\tilde x = \hat x - \langle\hat x\rangle$ and $\tilde p = \hat p - \langle\hat p\rangle$, so that $(\Delta x)^2 = \langle\tilde x^2\rangle$ and $(\Delta p)^2 = \langle\tilde p^2\rangle$. Cauchy–Schwarz on the Hilbert-space inner product gives [9, 10]

$$\langle\tilde x^2\rangle\langle\tilde p^2\rangle \ge |\langle\tilde x\tilde p\rangle|^2. \tag{11}$$

Write $\tilde x\tilde p = \tfrac12\{\tilde x,\tilde p\} + \tfrac12[\tilde x,\tilde p]$. The anticommutator has a real expectation value and the commutator, $i\hbar$, has an imaginary one, so

$$|\langle\tilde x\tilde p\rangle|^2 = \tfrac14\langle\{\tilde x,\tilde p\}\rangle^2 + \tfrac14\hbar^2 \ge \tfrac14\hbar^2. \tag{12}$$

Combining (11) and (12):

$$(\Delta x)^2(\Delta p)^2 \ge \frac{\hbar^2}{4} \;\Longrightarrow\; \boxed{\Delta x\,\Delta p \ge \frac{\hbar}{2}} \tag{13}$$

Equality holds when $\langle\{\tilde x,\tilde p\}\rangle = 0$ and $\tilde x|\psi\rangle = i\lambda\tilde p|\psi\rangle$ with $\lambda$ real, which is the Gaussian packet (6) [9].

---

## 6. The McGucken Principle dx₄/dt = ic Reading of Every Symbol in the Result

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

| Item | Where | Source in the McGucken Principle dx₄/dt = ic |
|---|---|---|
| **McGucken** $i$ in $e^{ip\cdot x/\hbar}$ | Eq. (3) | $x_4 = ict$ is imaginary; $p_\mu x^\mu$ gives a rotation on the unit circle |
| Sign in $e^{-iEt/\hbar}$ | Eq. (4) | $i\cdot i = -1$ from $x_4 = ict$ and $p_4 = iE/c$ |
| de Broglie $\lambda = h/p$ | Eq. (3) | Spatial projection of $p_\mu x^\mu/\hbar$ |
| $i$ in $\hat p = -i\hbar\,\partial_x$ | Eq. (9) | Eigenfunction $e^{ipx/\hbar}$ of the translation generator |
| $[\hat x,\hat p] = i\hbar$ | Eq. (10) | Direct computation from Eq. (9) |
| $\hbar$ | Eqs. (3), (7), (9), (13) | Action per unit phase; the McGucken Sphere's wavelength sets $h$ |
| Fourier conjugacy of $x$ and $p$ | Eq. (5) | Superposition over spatial winding rates of the phase (3) |
| $\sigma_x\sigma_p = \hbar/2$ | Eq. (8) | Gaussian Fourier transform, Eq. (7) |
| $\Delta x\,\Delta p \ge \hbar/2$ | Eq. (13) | Cauchy–Schwarz with $[\hat x,\hat p] = i\hbar$ |

---

## 7. The McGucken Principle dx₄/dt = ic Reading of Prior Work

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** $dx_4/dt = ic$ states the rate at which the imaginary coordinate of Poincaré [2] and Minkowski [1] advances, and assigns that advance to a physical expansion of $x_4$ from every spacetime point.

- **Wick (1954)** [13] rotates $t \to -i\tau$ to connect Minkowski and Euclidean formulations. The McGucken reading assigns this rotation to the $i$ in $dx_4/dt = ic$.
- **de Broglie (1924)** [14] introduced $\lambda = h/p$, and **Heisenberg (1927)** [15] stated the uncertainty relation. **Kennard (1927)** [9] and **Robertson (1929)** [10] proved the inequality. The McGucken reading derives both $\lambda = h/p$ and the commutator from the phase (3).
- **Lindgren and Liukkonen (2019)** [16] derive the Schrödinger equation from stochastic optimization on spacetimes, with the imaginary unit arising from relativistic invariance. The McGucken reading assigns this $i$ to $dx_4/dt = ic$.

*Evidence level: [9], [10], [13], [14], [15] background knowledge of the original papers; [16] web-digest of the abstract; McGucken's own papers, web-digest.*

---

## 8. The McGucken Principle dx₄/dt = ic Reading of Position–Momentum Reciprocity

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**McGucken Principle anchor.** A definite momentum is a single winding rate of the phase (3), $e^{ipx/\hbar}$, uniform over all $x$. A definite position is a superposition over all winding rates. Position and momentum are the two Fourier representations of one complex phase function, and $dx_4/dt = ic$ makes that function complex. The width product (8) is the Fourier reciprocity of that function, and $\hbar/2$ is its minimum.

---

## 9. The McGucken Principle dx₄/dt = ic Reading of the Derivation: Conclusion

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

1. $dx_4/dt = ic$ gives each particle the phase $e^{ip_\mu x^\mu/\hbar}$ (Eqs. 3–4).
2. The spatial winding rate is $p/\hbar$, so $\hat p = -i\hbar\,\partial_x$ (Eq. 9).
3. Localization is a superposition of winding rates, so $x$ and $p$ are Fourier conjugates (Eq. 5).
4. A Gaussian of width $\sigma_x$ transforms to width $\hbar/(2\sigma_x)$ (Eqs. 6–8).
5. Cauchy–Schwarz with $[\hat x,\hat p] = i\hbar$ gives $\Delta x\,\Delta p \ge \hbar/2$ (Eqs. 11–13).

---

## References

1. Minkowski, H. (1908). *Raum und Zeit.* Address to the 80th Assembly of German Natural Scientists and Physicians, Cologne. Translation in *The Principle of Relativity*, Dover (1952), pp. 73–91.
2. Poincaré, H. (1906). Sur la dynamique de l'électron. *Rendiconti del Circolo Matematico di Palermo* 21, 129–176.
3. Sommerfeld, A. (1909). Über die Zusammensetzung der Geschwindigkeiten in der Relativtheorie. *Physikalische Zeitschrift* 10, 826–829.
4. McGucken, E. *Light Time Dimension Theory / the McGucken Principle dx₄/dt = ic.* https://elliotmcguckenphysics.com
5. Taylor, E. F., & Wheeler, J. A. (1992). *Spacetime Physics* (2nd ed.). W. H. Freeman.
6. Dirac, P. A. M. (1958). *The Principles of Quantum Mechanics* (4th ed.). Oxford University Press.
7. Landau, L. D., & Lifshitz, E. M. (1975). *The Classical Theory of Fields* (4th ed.). Pergamon. §4.
8. Messiah, A. (1961). *Quantum Mechanics*, Vol. I. North-Holland. Ch. 2.
9. Kennard, E. H. (1927). Zur Quantenmechanik einfacher Bewegungstypen. *Zeitschrift für Physik* 44, 326–352. https://doi.org/10.1007/BF01391200
10. Robertson, H. P. (1929). The Uncertainty Principle. *Physical Review* 34, 163–164. https://doi.org/10.1103/PhysRev.34.163
11. Cohen-Tannoudji, C., Diu, B., & Laloë, F. (1977). *Quantum Mechanics*, Vol. I. Wiley.
12. Sakurai, J. J., & Napolitano, J. (2017). *Modern Quantum Mechanics* (3rd ed.). Cambridge University Press. §1.6.
13. Wick, G.-C. (1954). Properties of Bethe–Salpeter Wave Functions. *Physical Review* 96, 1124–1134. https://doi.org/10.1103/PhysRev.96.1124
14. de Broglie, L. (1925). Recherches sur la théorie des quanta. *Annales de Physique* 3, 22–128.
15. Heisenberg, W. (1927). Über den anschaulichen Inhalt der quantentheoretischen Kinematik und Mechanik. *Zeitschrift für Physik* 43, 172–198. https://doi.org/10.1007/BF01397280
16. Lindgren, J., & Liukkonen, J. (2019). Quantum Mechanics can be understood through stochastic optimization on spacetimes. *Scientific Reports* 9, 19984. https://doi.org/10.1038/s41598-019-56357-3
