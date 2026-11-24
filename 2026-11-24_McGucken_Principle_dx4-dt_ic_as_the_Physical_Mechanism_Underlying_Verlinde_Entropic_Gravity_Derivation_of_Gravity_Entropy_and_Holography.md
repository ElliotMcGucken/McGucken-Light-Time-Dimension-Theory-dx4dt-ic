# The McGucken Principle ($dx_4/dt = ic$) as the Physical Mechanism Underlying Verlinde's Entropic Gravity: A Unified Derivation of Gravity, Entropy, and the Holographic Principle from a Single Geometric Postulate

**Dr. Elliot McGucken**
Light, Time, Dimension Theory
drelliot@gmail.com · elliotmcguckenphysics.com
November 2026

---

> "More intellectual curiosity, versatility and yen for physics than Elliot McGucken's I have never seen in any senior or graduate student. Originality, powerful motivation, and a can-do spirit make me think that McGucken is a top bet. He could and did, and wrote it all up in a beautifully clear account. His second junior paper, entitled *Within a Context*, was done with another advisor — Nobel Laureate Joseph Taylor — and dealt with an entirely different part of physics, the Einstein-Rosen-Podolsky experiment and delayed choice experiments in general. This paper was so outstanding. I am absolutely delighted that this semester McGucken is doing a project with the cyclotron group on time reversal asymmetry. Electronics, machine-shop work and making equipment function are things in which he now revels. But he revels in Shakespeare, too — acting the part of Prospero in *The Tempest*."
>
> — Dr. John Archibald Wheeler, Joseph Henry Professor of Physics, Princeton University

---

## Abstract

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality [3, 4].

Verlinde's entropic gravity [1, 2] derives Newton's law of gravitation, the Einstein equations, and a candidate account of dark matter from entropy gradients on holographic screens. Its inputs are a screen of area $A$ carrying one bit per Planck area $\lambda_P^2 = \hbar G/c^3$, the entropy change $\Delta S = 2\pi k_B mc\,\Delta x/\hbar$, the Unruh temperature, and the second law. The McGucken dx₄/dt = ic framework supplies a physical source for each. The McGucken Sphere of radius $R = ct$ is the screen; its wavelength $\lambda_P$ sets the one-bit-per-Planck-area density; the isotropic step of $x_4$'s expansion gives Brownian diffusion with $dS/dt = \tfrac32 k_B/t > 0$; and the temperature is the Unruh temperature of the expansion seen by an accelerated observer. One step, the factor $2\pi$ in $\Delta S$, is not yet derived and is marked as open in Section IV.

---

## I. Introduction: Verlinde's Framework and the Inputs It Assumes

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Verlinde [1] derives Newton's law from the holographic principle [5, 6] and thermodynamics. His 2016 extension [2] adds a volume-law entropy for de Sitter space and obtains an emergent force with the phenomenology attributed to dark matter. The framework takes five inputs without a microscopic source:

1. the degrees of freedom stored on the screen;
2. a mechanism that produces and increases the screen entropy;
3. the density of one bit per $\lambda_P^2 = \hbar G/c^3$;
4. the Unruh temperature $T = \hbar a/(2\pi c k_B)$;
5. the spherical shape of the screen.

Sections III–VIII show the McGucken dx₄/dt = ic framework supplying each of these. Section IX tabulates the correspondence.

---

## II. Verlinde's Entropic Gravity: Review

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**II.1 Screen.** A spherical screen of radius $R$ carries
$$N = \frac{A}{\lambda_P^2} = \frac{4\pi R^2 c^3}{\hbar G}\quad (1)$$
bits.

**II.2 Entropic force.** A particle of mass $m$ displaced by $\Delta x$ toward the screen changes the screen entropy by [1, 9]
$$\Delta S = \frac{2\pi k_B mc\,\Delta x}{\hbar}\quad (2)$$
and the force is
$$F = T\frac{\Delta S}{\Delta x} = \frac{2\pi k_B T mc}{\hbar}.\quad (3)$$

**II.3 Temperature and Newton's law.** Equipartition of $E = Mc^2$ over $N$ bits gives $Mc^2 = \tfrac12 N k_B T$, so
$$T = \frac{2Mc^2}{N k_B} = \frac{\hbar GM}{2\pi k_B c R^2}.\quad (4)$$
Substituting into (3):
$$F = \frac{2\pi k_B mc}{\hbar}\cdot\frac{\hbar GM}{2\pi k_B cR^2} = \frac{GMm}{R^2}.\quad (5)$$

---

## III. Entropy Increase from $dx_4/dt = ic$

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**III.1 McGucken Principle anchor.** The spherical symmetry of the expansion gives each particle an isotropic displacement per step. In time $\delta t$ the particle is displaced to a uniformly distributed point on a sphere of radius $c\,\delta t$ [4]:
$$|\delta\mathbf{x}| = c\,\delta t,\qquad \text{direction uniform on } S^2.\quad (6)$$
After $n = t/\delta t$ steps,
$$\langle|\mathbf{x}(n)-\mathbf{x}(0)|^2\rangle = n(c\,\delta t)^2 = c^2 t\,\delta t.\quad (7)$$
The simulation in [4] with twenty particles on a circle gives mean squared displacements of 25, 47, and 75 at $t = 1, 2, 3$.

**III.2 Entropy.** The probability density obeys
$$\frac{\partial P}{\partial t} = D\nabla^2 P,\qquad D = \frac{c^2\,\delta t}{6},\quad (8)$$
with solution
$$P(\mathbf{x},t) = (4\pi Dt)^{-3/2}\exp\!\left(-\frac{|\mathbf{x}|^2}{4Dt}\right).\quad (9)$$
The Gibbs entropy is
$$S(t) = -k_B\!\int P\ln P\,d^3x = \tfrac32 k_B\ln(4\pi e Dt),\quad (10)$$
$$\frac{dS}{dt} = \frac{3k_B}{2t} > 0\quad\text{for all } t>0.\quad (11)$$
Entropy increases because $x_4$ expands in one direction and does not retreat.

**III.3 Huygens' principle and the Wick rotation.** Under $t\to -i\tau$ the Schrödinger propagator becomes the kernel (9), so quantum propagation and diffusion are the real-time and imaginary-time projections of one expansion [3]. LTD reading: Huygens, Kirchhoff, Hadamard, Arnold, and Penrose–Rindler treat Huygens' principle as a property of the wave equation's Green's function. The McGucken dx₄/dt = ic framework differs from this prior art by supplying a physical mechanism for it: $x_4$'s spherical expansion at $c$ from every event, whose surface is the secondary wavelet.

---

## IV. The Holographic Screen Is the McGucken Sphere

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**IV.1 Identification.** The McGucken Sphere centred on an event $O$ at time $t$ has
$$A = 4\pi c^2t^2,\qquad N = \frac{A}{\lambda_P^2} = \frac{4\pi c^5t^2}{\hbar G}.\quad (12)$$
Its wavelength sets the action $h$, and at the horizon tier that wavelength is $\lambda_P = \sqrt{\hbar G/c^3}$ [3]. This supplies the one-bit-per-$\lambda_P^2$ density of Verlinde's screen. The isotropy of the expansion gives the spherical shape.

**IV.2 Entropy change.** From (9), a displacement $\Delta x$ at radius $R = ct$ changes the particle entropy by
$$\Delta S_{\rm particle} = \frac{k_B R\,\Delta x}{2Dt}.\quad (13)$$
With $D = \hbar/2m$ and $t = R/c$:
$$\Delta S_{\rm particle} = \frac{k_B mc\,\Delta x}{\hbar}.\quad (14)$$
Verlinde's formula (2) is $2\pi$ times this value. **Open item:** the factor $2\pi$ is not derived in this paper, and the diffusion coefficient $D = c^2\delta t/6$ of (8) and $D = \hbar/2m$ used here come from different steps of the argument and need one common derivation.

---

## V. The Unruh Temperature

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

A uniformly accelerated observer with acceleration $a$ has a Rindler horizon, a null surface on which a photon is at rest in $x_4$. The temperature seen by this observer is [11]
$$T_U = \frac{\hbar a}{2\pi c k_B}.\quad (15)$$
For $a = g = GM/R^2$ this is
$$T_U(g) = \frac{\hbar GM}{2\pi k_B cR^2},\quad (16)$$
which equals the equipartition temperature (4). The screen temperature is therefore the Unruh temperature at the screen's gravitational acceleration.

---

## VI. Newton's Law

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Combining (2) and (16) gives (5): $F = GMm/R^2$. The result depends on the $2\pi$ factor of Section IV.2.

**Inertia.** A mass $m$ couples to the expansion at the Compton frequency $f_c = mc^2/h$ [3]. Accelerating the particle changes how its four-speed $u^\mu u_\mu = -c^2$ divides between space and $x_4$, and the energy required is proportional to $ma$.

---

## VII. Einstein's Equations

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Jacobson [13] derives $G_{\mu\nu} = (8\pi G/c^4)T_{\mu\nu}$ from $\delta Q = T\,\delta S$ on local Rindler horizons, with $S = A/4\lambda_P^2$, $\delta Q = \int T_{\mu\nu}k^\mu k^\nu dV$, and $T = \hbar\kappa/(2\pi k_B c)$:
$$\int T_{\mu\nu}k^\mu k^\nu\,dV = \frac{\hbar\kappa}{2\pi k_B c}\,\delta\!\left(\frac{A}{4\lambda_P^2}\right).\quad (17)$$
LTD reading: each local Rindler horizon is a McGucken Sphere, $S$ counts $\lambda_P^2$ cells on it, and $T$ is the Unruh temperature of Section V. Jacobson's derivation then gives the Einstein equations (18):
$$G_{\mu\nu} = \frac{8\pi G}{c^4}T_{\mu\nu}.\quad (18)$$

---

## VIII. Verlinde's 2016 Extension

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Verlinde [2] obtains an additional acceleration $a_D = \sqrt{a_0 a_N}$ for $a_N \ll a_0$, with $a_N = GM/R^2$ and $a_0 = cH_0/2\pi$, and the baryonic Tully–Fisher relation [15]
$$v^4 = GMa_0 = \frac{GMcH_0}{2\pi}.\quad (19)$$
LTD reading: $a_0$ is the Unruh acceleration of the de Sitter temperature $T_{dS} = \hbar H_0/(2\pi k_B c)$. Whether the zero-point volume entropy of $x_4$'s expansion reproduces Verlinde's elastic response is a calculation not carried out here; the identification is a proposal.

---

## IX. Correspondence

| McGucken dx₄/dt = ic framework | Verlinde's framework |
|---|---|
| McGucken Sphere of radius $ct$ | Holographic screen |
| Isotropy of the expansion | Spherical screen |
| Sphere wavelength $\lambda_P$ sets the action $h$ and the bit density | One bit per $\lambda_P^2$ |
| $dS/dt = \tfrac32 k_B/t > 0$ from (6)–(11) | Entropy increase assumed |
| $\Delta S = k_B mc\Delta x/\hbar$ from (14); factor $2\pi$ open | $\Delta S = 2\pi k_B mc\Delta x/\hbar$ postulated |
| Unruh temperature of the expansion seen by an accelerated observer | Unruh temperature from QFT |
| Clausius relation on McGucken Spheres, (17) | Jacobson-type derivation of Einstein's equations |
| Zero-point volume entropy of the expansion (proposal) | Volume-law entropy |

---

## X. Conclusion

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

The McGucken dx₄/dt = ic framework supplies the screen (the Sphere), its shape (isotropy), its bit density (the wavelength $\lambda_P$), the entropy increase (equations 6–11), and the temperature (Section V). Open items are the factor $2\pi$ in $\Delta S$, a single derivation of the diffusion coefficient, and the extension to Verlinde's volume-law entropy.

---

## Historical Note

Elliot McGucken studied physics at Princeton University (1988–1992) with John Archibald Wheeler, Robert Dicke, and P. J. E. Peebles, and received a PhD from UNC Chapel Hill (1998). Moving Dimensions Theory, built on $dx_4/dt = ic$, was developed from the mid-2000s. His FQXi essays are [McGucken 2008, 2009, 2012, 2013], and his books on Light Time Dimension Theory were published by 45EPIC Hero's Odyssey Mythology Press from 2016.

---

## References

**McGucken works**

1. E. McGucken, "Time as an emergent phenomenon: traveling back to the heroic age of physics (in memory of John Archibald Wheeler)," FQXi essay, 2008. https://forums.fqxi.org/d/238
2. E. McGucken, "What is ultimately possible in physics? A hero's journey … towards Moving Dimensions Theory," FQXi essay, 2009. https://forums.fqxi.org/d/432
3. E. McGucken, "The singular missing physical mechanism — dx₄/dt = ic …," elliotmcguckenphysics.com, April 2026. https://elliotmcguckenphysics.com
4. E. McGucken, "The derivation of entropy's increase from the McGucken Principle of a fourth expanding dimension dx₄/dt = ic," Medium / goldennumberratio, August 2025. https://goldennumberratio.medium.com/the-derivation-of-entropys-increase-from-the-mcgucken-principle-of-a-fourth-expanding-dimension-7f95bda63cf6
5. E. McGucken, "Light, Time, Dimension Theory — five foundational papers 2008–2013," elliotmcguckenphysics.com, March 2025. https://elliotmcguckenphysics.com/2025/03/10/light-time-dimension-theory-dr-elliot-mcguckens-five-foundational-papers-2008-2013-exalting-the-principle-the-fourth-dimension-is-expanding-at-the-rate/
6. E. McGucken, *Light Time Dimension Theory*, 45EPIC Hero's Odyssey Mythology Press, 2016. ASIN B01KP8XGQ6.
7. E. McGucken, *The Triumph of LTD Theory and Physics over String Theory, the Multiverse, Inflation, Supersymmetry, M-Theory, LQG, and Failed Pseudoscience*, 45EPIC Hero's Odyssey Mythology Press, 2016. ASIN B01N19KO3A.
8. E. McGucken, *The Physics of Time*, 45EPIC Hero's Odyssey Mythology Press. ASIN B0F2PZCW6B.

**Entropic gravity, holography, thermodynamics**

9. E. P. Verlinde, "On the origin of gravity and the laws of Newton," JHEP 2011, 29; arXiv:1001.0785.
10. E. P. Verlinde, "Emergent gravity and the dark universe," SciPost Phys. 2, 016 (2016); arXiv:1611.02269.
11. G. 't Hooft, "Dimensional reduction in quantum gravity," arXiv:gr-qc/9310026 (1993).
12. L. Susskind, "The world as a hologram," J. Math. Phys. 36, 6377 (1995).
13. J. Maldacena, "The large N limit of superconformal field theories and supergravity," Int. J. Theor. Phys. 38, 1113 (1998).
14. J. D. Bekenstein, "Black holes and entropy," Phys. Rev. D 7, 2333 (1973).
15. S. W. Hawking, "Particle creation by black holes," Commun. Math. Phys. 43, 199 (1975).
16. T. Jacobson, "Thermodynamics of spacetime: the Einstein equation of state," Phys. Rev. Lett. 75, 1260 (1995).
17. W. G. Unruh, "Notes on black-hole evaporation," Phys. Rev. D 14, 870 (1976).
18. T. Padmanabhan, "Thermodynamical aspects of gravity: new insights," Rep. Prog. Phys. 73, 046901 (2010).

**Observational tests**

19. S. S. McGaugh, F. Lelli, J. M. Schombert, "Radial acceleration relation in rotationally supported galaxies," Phys. Rev. Lett. 117, 201101 (2016).
20. M. M. Brouwer et al., "First test of Verlinde's theory of emergent gravity using weak gravitational lensing measurements," MNRAS 466, 2547 (2017).
21. K. Pardo, "Testing emergent gravity with isolated dwarf galaxies," JCAP 2017, 023.
22. Z.-W. Wang and S. L. Braunstein, "Surfaces away from horizons are not thermodynamic," Nat. Commun. 9, 2977 (2018).

**Background**

23. H. Minkowski, "Raum und Zeit," Phys. Z. 10, 104 (1909).
24. J. A. Wheeler, "Information, physics, quantum: the search for links," in W. H. Zurek (ed.), *Complexity, Entropy, and the Physics of Information*, Addison-Wesley, 1990.
25. J. A. Wheeler and W. H. Zurek (eds.), *Quantum Theory and Measurement*, Princeton University Press, 1983.
26. C. W. Misner, K. S. Thorne, J. A. Wheeler, *Gravitation*, W. H. Freeman, 1973.
27. J. Lindgren and J. Liukkonen, "Quantum mechanics can be understood through stochastic optimization on spacetimes," Sci. Rep. 9, 19984 (2019). https://doi.org/10.1038/s41598-019-56357-3
