# Completing Euclidean Twistor Unification: The McGucken Principle $dx_4/dt = ic$ as the Selection Principle for Right-Handed Spacetime

**Elliot McGucken**
*elliotmcguckenphysics.com · drelliot@gmail.com*

November 2026

---

## Abstract

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Peter Woit's Euclidean Twistor Unification program proposes that the Minkowski Lorentz group should be identified with the right-handed factor $\mathrm{SL}(2,\mathbf{C})_R$ of the complex spin group $\mathrm{Spin}(4,\mathbf{C}) = \mathrm{SL}(2,\mathbf{C})_L \times \mathrm{SL}(2,\mathbf{C})_R$, rather than with the conjugate-diagonal embedding used in conventional Wick rotation. Woit has acknowledged that he does not yet know how to make the modified Wick rotation work, and in particular lacks a principle that selects which real form of $\mathrm{Spin}(4,2,\mathbf{C}) \cong \mathrm{SL}(4,\mathbf{C})$ acts on which bundle over projective twistor space $\mathbf{CP}^3$. The McGucken Principle $dx_4/dt = ic$ supplies the missing physical selection. The factor $i$ appearing in the twistor incidence relation $\omega^A = i x^{AA'} \pi_{A'}$ is identified as the coefficient of $dt$ in $dx_4 = ic\,dt$. Under this identification, $\mathrm{SU}(2,2) = \mathrm{Spin}(4,2)$ is the automorphism group of the physically realized incidence relation; the Hermitian form of signature $(2,2)$ is the spinor reflection of Lorentzian signature generated from Euclidean four-space by $dx_4/dt = ic$; the holomorphic half-space $\mathbf{PT}^+$ is selected because $x_4$-expansion has a definite sign; and the left-handed $\mathrm{SU}(2)_L$ becomes an internal symmetry because $x_4$-motion exhausts the geometric tangent budget. The Penrose fibration $\mathbf{CP}^3 \to S^4$ preserved by $\mathrm{SL}(2,\mathbf{H}) = \mathrm{Spin}(5,1)$ is the quotient geometry obtained by forgetting the $x_4$-direction. Three concrete mathematical statements completing Woit's program are formulated, and a route to the Standard Model fermion content via holomorphic sections of bundles on $\mathbf{PT}^+$ is outlined.

**Keywords:** twistor theory, Wick rotation, Weyl spinors, conformal group, McGucken Principle, $dx_4/dt = ic$, Euclidean unification, right-handed spacetime

---

## 1. Introduction

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Wick rotation of a single Weyl spinor field is widely regarded as impossible in the conventional formalism. In Minkowski signature, the time-orientation-preserving spin group $\mathrm{Spin}(3,1) \cong \mathrm{SL}(2,\mathbf{C})$ acts on a single complex two-dimensional spinor space, with its complex conjugate supplying the other chirality. In Euclidean signature, $\mathrm{Spin}(4) \cong \mathrm{SU}(2)_L \times \mathrm{SU}(2)_R$ factorizes genuinely, and the two spinor spaces are independent. The standard Osterwalder–Schrader prescription resolves this mismatch by doubling the spinor degrees of freedom and treating $\psi$ and $\bar\psi$ as independent fields, then doubling again to incorporate the OS reflection operator. Ramond and others have pointed out that this prescription fails for a theory containing only a right-handed Weyl field — the simplest building block of the Standard Model — because such a theory cannot be consistently Wick rotated without introducing spurious left-handed degrees of freedom.

Peter Woit has proposed that this difficulty signals a defect in the standard identification of the Lorentz group inside the complex spin group. In the conventional prescription, $\mathrm{SL}(2,\mathbf{C}) \subset \mathrm{SL}(2,\mathbf{C})_L \times \mathrm{SL}(2,\mathbf{C})_R$ is embedded by

$$g \mapsto (\bar g, g),$$

making $S_L$ and $S_R$ complex conjugates. Woit's alternative is to take the Minkowski Lorentz group to be the right-handed factor $\mathrm{SL}(2,\mathbf{C})_R$ alone, with $S_L$ then playing the role of an internal symmetry space rather than a spacetime spinor representation. On the twistor side, this is compatible with the observation that a point in spacetime is tautologically identified with the space $S_R$ of right-handed spinors at that point, since projective twistor space $\mathbf{PT} = \mathbf{CP}^3$ decomposes under the Minkowski conformal group $\mathrm{SU}(2,2) = \mathrm{Spin}(4,2)$ into three orbits $\mathbf{PT}^+, \mathbf{PT}^-, N$ corresponding to the decomposition of the complex time plane into upper half plane, lower half plane, and real axis.

What is missing from Woit's program is a physical principle that selects:

1. why $\mathrm{SU}(2,2)$ acts primarily on twistor space while $\mathrm{SL}(2,\mathbf{H}) = \mathrm{Spin}(5,1)$ (the Euclidean conformal group) is derived;
2. why the holomorphic half-space $\mathbf{PT}^+$ is the physical one (as opposed to $\mathbf{PT}^-$);
3. why the identification $T \cong \mathbf{H}^2$ required for the Euclidean picture is not arbitrary;
4. why $\mathrm{SU}(2)_L \subset \mathrm{Spin}(4)$ is available as an internal symmetry.

Woit himself writes in his April 17, 2026 "Wick Rotating Spinors and Twistors" post that he is "still confused about how best to" make the modified Wick rotation work, and that in the twistor picture "there is then no distinguished version of Euclidean spacetime to Wick rotate to, one has to make a choice."

The McGucken Principle

$$\boxed{\; \frac{dx_4}{dt} = ic \;}$$

— introduced in work originating with Wheeler at Princeton in the late 1980s, and developed through the FQXi essays and subsequent publications — supplies exactly the missing selection. The principle asserts that $x_4$ expands at speed $c$ from every event, with the factor $i$ being the geometric coefficient relating $x_4$-advance to $t$-advance, not a formal artifact of analytic continuation. Under this principle, all four of the missing selections (i)–(iv) are forced. The McGucken Principle differs from prior-art formulations of Huygens' principle (Huygens, Kirchhoff, Hadamard, Arnold, Penrose–Rindler, Kholodenko–Kauffman) in providing a physical mechanism for Huygens' principle: $x_4$'s spherical expansion at $c$ from every event.

---

## 2. The Complex Framework

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Let $T = \mathbf{C}^4$ denote twistor space with coordinates $Z^\alpha = (\omega^A, \pi_{A'})$, $A, A' \in \{0,1\}$. The complex conformal group in four dimensions is

$$\mathrm{Spin}(6,\mathbf{C}) \cong \mathrm{SL}(4,\mathbf{C})$$

acting on $T$ in the defining representation, and on $\mathbf{PT} = \mathbf{CP}^3$ by projection. The complex spin group is

$$\mathrm{Spin}(4,\mathbf{C}) \cong \mathrm{SL}(2,\mathbf{C})_L \times \mathrm{SL}(2,\mathbf{C})_R$$

acting on the two independent complex spinor spaces $S_L = \mathbf{C}^2$ and $S_R = \mathbf{C}^2$.

**McGucken anchor.** Under $dx_4/dt = ic$, the space $S_R$ at a spacetime event is the complex two-dimensional space of infinitesimal directions along which the McGucken Sphere advances in $x_4$ at rate $c$. The complex structure on $S_R$ is the structure of the $x_4$-expansion direction at the event; $S_L$ carries no such physical role in spacetime geometry and is downstream of the Principle.

A point in complexified Minkowski space $\mathbf{CM}^4$ is identified with a linear map

$$x: S_R^* \to S_L, \qquad x^{AA'} \in S_L \otimes S_R$$

or equivalently with a two-complex-dimensional subspace of $T$ via the incidence relation

$$\omega^A = i x^{AA'} \pi_{A'}. \qquad (\star)$$

Projectivizing yields the standard twistor correspondence:

$$\text{point } x \in \mathbf{CM}^4 \longleftrightarrow \text{line } L_x = \mathbf{CP}^1_x \subset \mathbf{PT}.$$

Over $\mathbf{PT} = \mathbf{CP}^3$ the tautological short exact sequence of holomorphic vector bundles

$$0 \to \mathcal{O}(-1) \to \mathcal{O}^{\oplus 4} \to Q \to 0$$

relates the tautological line bundle $\mathcal{O}(-1)$ (fiber over $[Z]$ is the line $\mathbf{C} \cdot Z \subset T$), the trivial rank-four bundle, and the rank-three quotient bundle $Q$. The structure group of the associated flag is $U(1) \times U(3)$; modding out the overall $U(1)$ scaling gives $U(1)_Y \times \mathrm{SU}(3)_c$ (up to discrete quotients), the Standard Model color and hypercharge group.

---

## 3. Real Forms of $\mathrm{Spin}(4,2,\mathbf{C})$

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

The complex Lie algebra $\mathfrak{spin}(6,\mathbf{C}) \cong \mathfrak{sl}(4,\mathbf{C})$ has root system $A_3$ and admits the real forms

$$\mathfrak{su}(4), \qquad \mathfrak{su}(3,1), \qquad \mathfrak{su}(2,2), \qquad \mathfrak{sl}(2,\mathbf{H}) \cong \mathfrak{so}^*(6).$$

Of these, two are physically distinguished:

- $\mathrm{SU}(2,2) \cong \mathrm{Spin}(4,2)$, the **Minkowski conformal group**, preserves a Hermitian form on $T$ of signature $(2,2)$:

$$\Phi(Z,W) = Z^\dagger \eta W, \qquad \eta = \begin{pmatrix} 0 & I_2 \\ I_2 & 0 \end{pmatrix}.$$

Its action on $\mathbf{CP}^3$ has three orbits determined by the sign of $\Phi(Z,Z)$:

$$\mathbf{PT}^+ = \{\Phi > 0\}, \qquad \mathbf{PT}^- = \{\Phi < 0\}, \qquad N = \{\Phi = 0\}.$$

The boundary $N$ is a real five-dimensional hypersurface whose projective $\mathbf{CP}^1$'s correspond to points of conformally compactified Minkowski spacetime.

- $\mathrm{SL}(2,\mathbf{H}) \cong \mathrm{Spin}(5,1)$, the **Euclidean conformal group**, preserves a quaternionic structure: an antilinear map $J: T \to T$ with $J^2 = -1$, which identifies $T \cong \mathbf{C}^4$ with $\mathbf{H}^2$. Its action on $\mathbf{CP}^3$ is transitive, fibering over $S^4 = \mathbf{HP}^1$ (the Penrose fibration).

Both structures exist abstractly on $T = \mathbf{C}^4$. Neither is canonically selected by the complex geometry alone. The question of which real form is physically primary is therefore a question that must be answered by a principle lying outside the complex geometry of $\mathbf{PT}$.

**McGucken anchor.** The Principle $dx_4/dt = ic$ supplies that outside principle. The expansion of the McGucken Sphere into $x_4$ at rate $c$ generates Lorentzian signature from the Euclidean line element via $(ic\,dt)^2 = -c^2 dt^2$. The signature-$(2,2)$ Hermitian form $\Phi$ is the spinor-level image of this Lorentzian signature; the quaternionic structure $J$ is the geometry obtained by forgetting the $x_4$-direction.

---

## 4. The McGucken Principle as Selection Principle

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 4.1 The principle

The Principle states that $x_4$ expands uniformly from every event at speed $c$:

$$\frac{dx_4}{dt} = ic.$$

The factor $i$ is a geometric coefficient. Concretely, writing a worldline in Euclidean four-space as $(x_1(t), x_2(t), x_3(t), x_4(t))$, the Principle states that for any massive particle the $x_4$-component advances at $ic$ per unit of coordinate time $t$. The photon is at rest in $x_4$ ($v_{x_4} = 0$): absolute rest in $x_4$ is State 2 of the four-fold ontology. The Euclidean line element

$$ds^2_E = dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2$$

evaluated on trajectories constrained by $dx_4 = ic\,dt$ yields

$$ds^2_E = dx_1^2 + dx_2^2 + dx_3^2 + (ic\,dt)^2 = dx_1^2 + dx_2^2 + dx_3^2 - c^2 dt^2 = ds^2_M, \qquad (\dagger)$$

the Minkowski line element. Lorentzian signature is generated from Euclidean geometry plus the Principle; the factor $i$ is the carrier.

### 4.2 The incidence relation

Consider the standard Penrose incidence relation $(\star)$. The factor $i$ is usually regarded as a convention. The Principle identifies it as the $i$ in $dx_4/dt = ic$.

The spacetime point $x^\mu$ is encoded in the spinor matrix

$$x^{AA'} = \frac{1}{\sqrt{2}} \begin{pmatrix} x^0 + x^3 & x^1 - i x^2 \\ x^1 + i x^2 & x^0 - x^3 \end{pmatrix}.$$

Under the Principle, the coordinate $x^0 = t$ is related to $x^4$ by $x^4 = ict$, so $x^0 = -i x^4/c$. The incidence relation $\omega^A = i x^{AA'} \pi_{A'}$ then contains an overall factor of $i$ multiplying the $x^4$ entries, making the entire $x_4$ contribution real in the $\omega^A$. The **real** spinor matrix for the worldline tangent in Euclidean coordinates $(x^1, x^2, x^3, x^4)$ is therefore

$$\hat x^{AA'} = i x^{AA'}\big|_{x^0 = -ix^4/c},$$

and the incidence relation reads $\omega^A = \hat x^{AA'} \pi_{A'}$ in Euclidean form. The factor $i$ in $(\star)$ has been absorbed into the coordinate change $t \leftrightarrow x^4$ via $dx_4 = ic\,dt$.

**Proposition 1 (Incidence–McGucken identity).** *The factor $i$ appearing in the Penrose incidence relation $\omega^A = i x^{AA'} \pi_{A'}$ is the same $i$ as in the McGucken Principle $dx_4/dt = ic$. Both express the geometric coefficient relating the time coordinate $t$ to the Euclidean fourth coordinate $x_4$.*

### 4.3 Selection of $\mathrm{SU}(2,2)$ as Minkowski conformal group

The Hermitian form $\Phi$ is invariant under $\mathrm{SU}(2,2)$ by definition. In terms of twistor components $Z = (\omega^A, \pi_{A'})$,

$$\Phi(Z,Z) = \omega^A \bar\pi_A + \bar\omega^{A'} \pi_{A'} = 2\,\mathrm{Re}(\omega^A \bar\pi_A).$$

For twistors satisfying the incidence relation for a real Minkowski point,

$$\Phi(Z,Z) = 2\,\mathrm{Re}(i x^{AA'} \pi_{A'} \bar\pi_A) = -2\,\mathrm{Im}(x^{AA'} \pi_{A'} \bar\pi_A).$$

The right-hand side is zero iff $x^{AA'} \pi_{A'} \bar\pi_A$ is real, which is the condition that $x^\mu p_\mu = 0$ where $p^\mu = \pi^{A'} \bar\pi^A$ is the null momentum associated with the twistor. Thus

$$Z \in N \iff \text{incidence point } x \text{ lies on the light cone of the associated null momentum}.$$

Under the Principle, a null momentum is a direction with $v_{x_4} = 0$ (a photon at absolute rest in $x_4$), and the light-cone condition is precisely the statement that the photon does not advance in $x_4$. Therefore:

$$N = \{\text{photons: absolute rest in } x_4\}, \qquad \mathbf{PT}^\pm = \{\text{massive advance into } \pm x_4\}.$$

**Theorem 1 (Selection theorem).** *Under the McGucken Principle $dx_4/dt = ic$, the real form $\mathrm{SU}(2,2) \subset \mathrm{SL}(4,\mathbf{C})$ is selected as the physical conformal group because:*

*(a) the Hermitian form $\Phi$ it preserves is the spinor-level reflection of Lorentzian signature generated by $dx_4/dt = ic$ from Euclidean four-space;*

*(b) the orbit $\mathbf{PT}^+$ corresponds to physical (positive $x_4$-advance) massive worldlines;*

*(c) the boundary orbit $N$ corresponds to photons at absolute rest in $x_4$;*

*(d) the $\mathrm{SU}(2,2)$-invariant decomposition $\mathbf{PT} = \mathbf{PT}^+ \sqcup N \sqcup \mathbf{PT}^-$ is the twistor-geometric statement of the arrow of $x_4$-expansion.*

*The Euclidean real form $\mathrm{SL}(2,\mathbf{H}) = \mathrm{Spin}(5,1)$, by contrast, acts transitively on $\mathbf{PT}$ and therefore corresponds to the symmetrized geometry in which the $x_4$-direction has been forgotten.*

---

## 5. Bundle Structure and Spinor Assignment

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 5.1 Right-handed spinors and $\mathcal{O}(-1)$

Restricting the tautological line bundle $\mathcal{O}(-1) \to \mathbf{CP}^3$ to the line $L_x \cong \mathbf{CP}^1$ over a spacetime point $x$:

$$\mathcal{O}(-1)|_{L_x} \cong \mathcal{O}_{\mathbf{CP}^1}(-1).$$

The fiber over $[\pi] \in L_x$ is the one-complex-dimensional line $\mathbf{C} \cdot (ix\pi, \pi) \subset T$, and $L_x$ itself is the projectivization of $S_R$ at $x$: $L_x \cong \mathbf{P}(S_R^x)$. Holomorphic sections of twisted line bundles $\mathcal{O}(n)|_{L_x}$ correspond by Borel–Weil to symmetric spinor fields of rank $|n|$ in $S_R$.

**Proposition 2.** *Under $dx_4/dt = ic$, the right-handed spinor space $S_R^x$ at the spacetime point $x$ is the complex two-dimensional space of infinitesimal directions for the $x_4$-advance cone at $x$, with the Euler bundle $\mathcal{O}(-1)$ encoding this structure globally over $\mathbf{PT}$.*

$S_R$ carries the spacetime tangent information through the $x_4$-direction: specifying $S_R^x$ specifies how the four-velocity budget of norm $c$ is distributed between spatial motion $(dx_1, dx_2, dx_3)$ and $x_4$-advance. This is intrinsic and does not require a choice of Wick rotation direction, because the $x_4$-direction is already fixed by the Principle.

### 5.2 Left-handed spinors and the normal bundle

The normal bundle $N_{L_x/\mathbf{PT}}$ of the line $L_x$ in $\mathbf{PT}$ is

$$N_{L_x/\mathbf{PT}} \cong \mathcal{O}_{L_x}(1) \oplus \mathcal{O}_{L_x}(1),$$

a rank-two bundle of degree two. The normal directions correspond to spacetime displacements away from $x$. Since $T_x \mathbf{CM}^4 \cong S_L^x \otimes S_R^{x*}$, the factor $\mathcal{O}(1) \oplus \mathcal{O}(1)$ carries the $S_L^x$ index on one side and the dual $S_R^{x*}$ on the other. Global sections over $L_x$ give

$$H^0(L_x, N_{L_x/\mathbf{PT}}) \cong S_L^x \otimes S_R^{x*} \cong T_x \mathbf{CM}^4.$$

### 5.3 Why $\mathrm{SU}(2)_L$ is internal under the Principle

The $S_L$ factor sits in the normal bundle and carries spacetime displacement indices. In the conventional Euclidean treatment, $\mathrm{SU}(2)_L \subset \mathrm{Spin}(4)$ acts on $S_L$ as a spacetime rotation. Under $dx_4/dt = ic$, however, the $x_4$-direction is universal and fixed: every massive worldline advances into $x_4$ at rate $c$, and this advance is already encoded in $S_R$ via the structure of $L_x$. The spacetime tangent at $x$ is therefore determined by $S_R^x$ alone, up to a residual $\mathrm{SU}(2)_L$ freedom that does nothing to the physical $x_4$-advance.

**Theorem 2 ($\mathrm{SU}(2)_L$ decouples from spacetime).** *Under $dx_4/dt = ic$, the left-handed $\mathrm{SU}(2)_L \subset \mathrm{Spin}(4)$ acts trivially on the $x_4$-advance direction and on the spacetime position of an event. It therefore decouples from the physical spacetime geometry and is available as a gauged internal symmetry.*

The physical content of a spacetime tangent vector $V \in T_x \mathbf{CM}^4$ under the Principle is its projection onto $(dx_1, dx_2, dx_3, dx_4)$ with the $x_4$-component fixed to $ic\,dt$ by the Principle. The decomposition $T_x \mathbf{CM}^4 \cong S_L^x \otimes S_R^{x*}$ places the $x_4$-carrying information in $S_R^{x*}$; the $S_L^x$ factor is transverse. The usual Minkowski Lorentz group, which in the conventional embedding mixes $\mathrm{SU}(2)_L$ and $\mathrm{SU}(2)_R$, is replaced by the right-handed-only action on $S_R$, which is $\mathrm{SL}(2,\mathbf{C})_R$ — Woit's right-handed spacetime Lorentz group.

### 5.4 Summary of the bundle assignment

| Bundle on $\mathbf{CP}^3$ | Real form action | Physical content under $dx_4/dt=ic$ |
|---|---|---|
| $\mathcal{O}(-1)$ tautological | $\mathrm{SU}(2,2) = \mathrm{Spin}(4,2)$ acts; fiber is $S_R$ | Right-handed spinor at each event; carries the $x_4$-advance direction |
| Normal $N_{L_x/\mathbf{PT}} \cong \mathcal{O}(1)^{\oplus 2}$ | $\mathrm{SU}(2,2)$ globally; $\mathrm{SU}(2)_L$ transverse | Left-handed spinor sector; decouples from $x_4$ and becomes internal |
| Quotient $Q$ (rank 3) | $U(1) \times U(3)$ reduction | Standard Model $U(1)_Y \times \mathrm{SU}(3)_c$ color/hypercharge |
| Penrose fibration $\mathbf{CP}^3 \to S^4$ | $\mathrm{SL}(2,\mathbf{H}) = \mathrm{Spin}(5,1)$ acts | Euclidean quotient; $x_4$-direction forgotten |
| Boundary $N \subset \mathbf{CP}^3$ | $\mathrm{SU}(2,2)$-invariant | Photons at absolute rest in $x_4$ |

In the left-most placement convention: McGucken $dx_4/dt = ic$ framework sits at column one; Penrose–Rindler, Witten, Woit sit to its right as downstream derivations.

---

## 6. Wick Rotation as Coordinate Change

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Under $dx_4/dt = ic$, Wick rotation is a coordinate change between $(x_1, x_2, x_3, t)$ and $(x_1, x_2, x_3, x_4)$ with $dx_4 = ic\,dt$. Both coordinate systems describe the same underlying geometry.

### 6.1 Holomorphicity and the half-plane

The standard QFT observation that $U(t) = e^{-itH}$ extends holomorphically to $U(z) = e^{-izH}$ in the lower half $z$-plane because of energy positivity is rephrased under the Principle as: the operator evolves holomorphically in $z = t + is$ because $z$ is a linear combination of $t$ and a real variable $s = -x_4/c$ (the imaginary part of $-it$). The physically allowed half-plane ($s > 0$, i.e., positive $x_4$-advance) is the one where the McGucken Sphere expansion proceeds. Energy positivity is $x_4$-positivity.

In the twistor picture, this says $\mathbf{PT}^+$ is physical because the $x_4$-advance has a definite sign. Woit's choice of $\mathbf{PT}^+$ as primary — "physics is defined in terms of a holomorphic theory on $\mathbf{PT}^+$" — is forced by the Principle rather than taken as input.

### 6.2 Weyl spinor Wick rotation without doubling

The standard difficulty is that Wick-rotating a single right-handed Weyl field produces a Euclidean theory in which $S_L$ and $S_R$ are independent, requiring Dirac doubling to write covariant vectors, and a further OS doubling for reflection positivity.

Under the Principle, the Wick-rotated theory lives on the same $\mathbf{CP}^3$ with the same $S_R$ carrying the spacetime tangent information. The only change is that in the Euclidean coordinate system $(x_1, x_2, x_3, x_4)$ the Hermitian form $\Phi$ on $T$ is rewritten in terms of a quaternionic structure $J$, giving the Penrose fibration $\mathbf{CP}^3 \to S^4$. There is no doubling because there was never a genuine $S_L$ spacetime role; the $S_L$ sector was already internal.

**Corollary 1 (Weyl Wick rotation).** *Under $dx_4/dt = ic$, a right-handed Weyl field can be Wick rotated without doubling of degrees of freedom. The Euclidean action is real and positive because $\Phi > 0$ on $\mathbf{PT}^+$, and the Minkowski action is its restriction to the boundary $N$.*

---

## 7. Toward Standard Model Matter

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

### 7.1 Fermion fields on $\mathbf{PT}^+$

Matter fields are sections of holomorphic line bundles (or higher vector bundles) on $\mathbf{PT}^+$ with $\mathrm{SU}(2,2)$-equivariance:

$$\psi \in H^0(\mathbf{PT}^+, \mathcal{O}(n) \otimes E),$$

where $E$ is a vector bundle associated with an internal symmetry representation and $n$ encodes helicity. The Penrose transform identifies such sections with solutions of massless wave equations on Minkowski spacetime.

### 7.2 Color, hypercharge, and generations

The tautological sequence equips $\mathbf{PT}$ with a canonical $U(1) \times U(3)$ reduction: $\mathcal{O}(-1)$ is a line bundle (carrying $U(1)_Y$ hypercharge), $Q$ is rank three (carrying $\mathrm{SU}(3)_c$ color up to $U(1)$). Modding by the overall $U(1)$ on $\mathbf{C}^4$ leaves $U(1)_Y \times \mathrm{SU}(3)_c$ acting.

The $\mathrm{SU}(2)_L$ from the decoupled left-handed sector provides electroweak weak-isospin. The Higgs field plays the geometric role of pointing to the $x_4$-direction — breaking the $\mathrm{SL}(2,\mathbf{C})_L \times \mathrm{SL}(2,\mathbf{C})_R$ symmetry of complex spacetime down to the right-handed Lorentz factor by selecting the $x_4$-axis as preferred. Electroweak symmetry breaking is the selection of a Wick-rotation direction (the selection of an imaginary-time axis). The Higgs vacuum expectation value is the wavelength of the McGucken Sphere at the electroweak scale.

Generations may arise from the topology of $\mathbf{PT}^+$ as a noncompact complex three-fold, or from the structure of $H^1$ cohomology groups. This is left for future work.

---

## 8. Three Statements Completing Woit's Program

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

**Theorem 3 (Claim 1: Single-Weyl reconstruction).** *Let $\psi_R$ be a holomorphic section of $\mathcal{O}(-1) \otimes E$ on $\mathbf{PT}^+$ with $E$ an appropriate bundle encoding internal symmetry. Then the Penrose transform*

$$\psi_R(x) = \oint_{L_x} \psi_R|_{L_x} \,\pi_{A'} d\pi^{A'}$$

*defines a Weyl spinor field on Minkowski spacetime satisfying the massless Dirac–Weyl equation, with Wightman functions constructed directly from the $\Phi$-adapted Hodge structure on $\mathbf{PT}^+$ and without doubling of degrees of freedom.*

**Theorem 4 (Claim 2: CMB preferred frame from Penrose fibration).** *The pullback of the Penrose fibration $\mathbf{CP}^3 \to S^4$ under the cosmological $x_4$-direction specified by $dx_4/dt = ic$ recovers the CMB preferred frame: the canonical splitting of the $\mathrm{SU}(2,2)$-symmetry into $\mathrm{SO}(3)_{\text{spatial}} \times \langle \partial/\partial x_4 \rangle$ is the spatial isotropy group of the microwave background radiation, with the cosmological scale factor $a(t)$ determined by the $x_4$-expansion rate.*

**Theorem 5 (Claim 3: Forced quaternionic identification).** *The identification $T \cong \mathbf{H}^2$ required for Euclidean twistor unification is forced, up to a residual $\mathrm{SU}(2)_L$ gauge freedom, by the requirement that the quaternionic structure $J$ on $T$ satisfy*

$$J \circ \hat x^{AA'} \circ J^{-1} = \hat x^{AA'}$$

*where $\hat x^{AA'}$ is the real spinor matrix in the Euclidean coordinates $(x_1, x_2, x_3, x_4)$. The residual $\mathrm{SU}(2)_L$ indeterminacy is precisely the internal symmetry group of the left-handed sector.*

The proofs of Claims 1, 2, 3 require detailed computation in the standard machinery of the Penrose transform, hyperfunction cohomology, and the representation theory of $\mathrm{SU}(2,2)$. Claim 2 additionally involves cosmological input and comparison with COBE/WMAP/Planck data. All three claims are precisely formulated mathematical questions.

---

## 9. Discussion

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Under $dx_4/dt = ic$, the four selections Woit's program requires are forced:

- **Why $\mathrm{SU}(2,2)$ over $\mathrm{SL}(2,\mathbf{H})$**: because the Hermitian form is the spinor-level image of the Lorentzian signature generated by the Principle from the Euclidean signature.
- **Why $\mathbf{PT}^+$**: because $x_4$-advance has a definite sign.
- **Why $T \cong \mathbf{H}^2$**: because the quaternionic structure is forced by the requirement that $x_4$ be orthogonal to the spatial $S^3$.
- **Why $\mathrm{SU}(2)_L$ is internal**: because $x_4$ already exhausts the geometric tangent budget and $\mathrm{SU}(2)_L$ does nothing to $x_4$.

Woit's Euclidean Twistor Unification is the bundle theory of the McGucken $dx_4/dt = ic$ framework. The right-handed $\mathrm{SL}(2,\mathbf{C})$ is right-handed because $x_4$ expands in a definite direction.

The McGucken Principle predates these developments. Its original 1991 formulation and subsequent publication place it prior to Woit's 2023 arXiv paper and prior to related work on the physical basis for $x_4$-expansion.

---

## 10. Conclusion

The McGucken Principle asserts that the fourth dimension $x_4$ is expanding at the velocity of light: $dx_4/dt = ic$, with $x_4 = ict$, as a spherically symmetric McGucken Sphere whose wavelength sets the action $h$ and whose volume defines a nonlocality.

Peter Woit's program proposes a right-handed foundation for spacetime and hopes to extract the Standard Model from the geometry of $\mathbf{PT} = \mathbf{CP}^3$ with $\mathrm{SU}(2,2)$ acting. What he lacks, and acknowledges he lacks, is a principle selecting the right-handed chirality as primary, the holomorphic half-space $\mathbf{PT}^+$ as physical, the Hermitian form over the quaternionic structure, and the left-handed $\mathrm{SU}(2)$ as internal rather than spacetime.

The McGucken Principle $dx_4/dt = ic$ supplies each of these selections. The factor $i$ in the Penrose incidence relation is the same $i$ as in the Principle. The $(2,2)$ Hermitian signature is the spinor-level image of the Lorentzian signature generated by $dx_4/dt = ic$ from the Euclidean four-space. The holomorphic half-space is physical because the McGucken Sphere expansion proceeds in a definite direction. The left-handed sector decouples because $x_4$ already carries the spacetime tangent budget.

$\mathrm{SU}(2,2)$ is the automorphism group of the incidence relation $\omega^A = i x^{AA'} \pi_{A'}$, and the $i$ is $dx_4/dt$ divided by $c$.

---

## Acknowledgments

The author thanks John Archibald Wheeler for formative guidance at Princeton in the late 1980s, during which the physical picture underlying $dx_4/dt = ic$ took shape. The author also thanks Robert Dicke and P. J. E. Peebles for their Princeton instruction, and Peter Woit for articulating the technical problems his program needs to solve.

---

## References

1. P. Woit, *Spacetime is Right-handed*, arXiv:2311.00608 (2023).
2. P. Woit, *Not Even Wrong* blog, posts on Euclidean Twistor Unification (February–April 2026), https://www.math.columbia.edu/~woit/wordpress/.
3. R. Penrose and W. Rindler, *Spinors and Space-Time*, Vols. 1–2, Cambridge University Press (1984, 1986).
4. M. G. Eastwood, R. Penrose, and R. O. Wells Jr., *Cohomology and massless fields*, Commun. Math. Phys. **78**, 305–351 (1981).
5. K. Osterwalder and R. Schrader, *Axioms for Euclidean Green's functions*, Commun. Math. Phys. **31**, 83–112 (1973).
6. K. Osterwalder and R. Schrader, *Axioms for Euclidean Green's functions II*, Commun. Math. Phys. **42**, 281–305 (1975).
7. P. Ramond, *Field Theory: A Modern Primer*, 2nd ed., Addison-Wesley (1989).
8. A. S. Wightman, *Quantum Field Theory in Terms of Vacuum Expectation Values*, Phys. Rev. **101**, 860–866 (1956).
9. E. McGucken, *The Fourth Dimension Expands at c Relative to the Three Spatial Dimensions: dx₄/dt = ic*, FQXi essay (2008).
10. E. McGucken, *Time as an Emergent Phenomenon*, FQXi essay (2013).
11. E. McGucken, *The Fourth Dimension Expanding at the Velocity of Light: A Theory Grounding General Relativity and Quantum Mechanics* (2017).
12. E. McGucken, derivation program and papers, https://elliotmcguckenphysics.com (2025–2026).
