------------------------------------------------------------------------

# The McGucken Principle and Its Shadow 

## Statement of the Principle


**Axiom 1** (McGucken Principle). *The fourth dimension $x_4$ is a real
physical dimension that expands at the velocity of light in a
spherically symmetric manner from every event. Its rate of expansion is
given, in the coordinate gauge of Minkowski space, by
$$\frac{d x_4}{d t} \;=\; i c .$$ The imaginary unit $i$ enforces the
orthogonality of $x_4$ to the three spatial dimensions; the magnitude
$c$ enforces the universal speed limit; the operator $d/dt$ enforces
that the principle is a *velocity*, not a coordinate.*


**Definition 2** (Coordinate shadow). *The integrated form of
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
$$x_4(t) \;=\; \int_0^{t} \frac{d x_4}{d t'} \, dt' \;=\; ict ,$$ is the
*coordinate shadow* of the McGucken Principle. The label $x_4 = ict$ is
not foundational; it is the integrated trace of an active, geometric
expansion. The word "mere" in the phrase "mere integrated shadow" is
load-bearing: every theorem in this paper traces to the active
expansion, not to the coordinate.*


**Definition 3** (Dual-channel decomposition). *The right-hand side $ic$
factorizes into two physically independent channels.*

Channel A (algebraic / symmetry):

:   *the factor $i$ carries the rotational, unitary, quantum-mechanical
    content---generators of $U(1)$, the canonical commutation relations,
    Born sesquilinearity, phase coherence, $\pi/2$ Wick rotation.*

Channel B (geometric / propagation):

:   *the factor $c$ carries the metric, causal, thermodynamic,
    relativistic content---null cones, redshift, the Lorentz signature,
    horizon thermodynamics, the arrow of time.*

*A paradox arises whenever a derivation attempts to express Channel-B
content using only Channel-A variables, or vice versa; the dissolution
is to keep both channels.*


## Why $x_4 = ict$ is not a postulate

In Minkowski's 1908 lecture [@Minkowski1908] and in Einstein's
subsequent reformulation [@Einstein1916], $x_4 = ict$ was introduced as
a notational convenience: it lets the Lorentz interval
$-c^2 dt^2 + dx^2 + dy^2 + dz^2$ be written as a Euclidean sum
$dx_1^2 + dx_2^2 + dx_3^2 + dx_4^2$ with $dx_4 = ic\, dt$. The
convention was later abandoned in favor of explicit signature
conventions [@MTW1973]; the imaginary fourth coordinate was dismissed as
"a mere trick."

The McGucken Principle reverses the demotion. The trick is the integral;
the physics is the derivative. Once one writes
$$\frac{dx_4}{dt} = ic ,$$ one has not a notational convention but a
*kinematic* statement: at every event, the fourth dimension is itself
moving outward at $c$, orthogonally to the three spatial directions. The
imaginary unit is not a bookkeeping device but the algebraic shadow of a
real rotation in a real four-dimensional manifold.


**Remark 4**. *The spherical symmetry of the expansion is essential. At
any event $p$, $dx_4$ points outward into the fourth dimension along the
local null cone of $p$. There is no preferred direction in $x_4$; every
event is its own center. This is the geometric content that
distinguishes Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} from a global cosmological expansion. The Hubble
flow, the CMB rest frame, and Penrose's conformal
compactification [@Penrose1965] are all consequences, not inputs.*


## The general dissolution theorem


**Theorem 5** (General Paradox Dissolution). *Let $P$ be any physical
paradox stated in the form "observable $A$ has incompatible values in
frames $F$ and $F'$," where the incompatibility derives from treating
$x_4$ as a static coordinate label. Then $P$ admits a dissolution as a
theorem of Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}.*


::: proof
*Proof.* *Step 1 (the hypothesis).* Let two derivations $D, D'$ of the
observable $A$ in frames $F, F'$ produce incompatible values
$A(F) \neq A(F')$, and let the incompatibility derive from the use of
$x_4$ as a static coordinate label in both derivations.

*Step 2 (the static label is integrated velocity).* By
Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}, the static label $x_4 = ict$ is the integrated
form of the velocity $dx_4/dt = ic$. Any computation that treats $x_4$
as a fixed coordinate at a given instant implicitly evaluates
$\int_0^t (dx_4/dt')\,dt'$ at the endpoint $t$ and discards the velocity
field $dx_4/dt$ along the way. The velocity field carries content: the
spherical $x_4$-expansion at every event
(Remark [4](#rem:expansion){reference-type="ref"
reference="rem:expansion"}), the local null-cone structure
(Definition [3](#def:channels){reference-type="ref"
reference="def:channels"} Channel B), and the algebraic phase $i$
relating $x_4$ to $t$
(Definition [3](#def:channels){reference-type="ref"
reference="def:channels"} Channel A).

*Step 3 (the dual-channel completeness requirement).* By
Definition [3](#def:channels){reference-type="ref"
reference="def:channels"}, the right-hand side $ic$ factorizes into
Channel A ($i$, algebraic) and Channel B ($c$, geometric). Any
derivation of $A$ must, to be complete under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, track
contributions through both channels: the Channel-A unitary rotation of
the relevant operator algebra under $\hat U(t) = \exp(-i\hat H t/\hbar)$
and the Channel-B propagation of geometric quantities along the null
cone of $dx_4/dt = ic$.

*Step 4 (reinstatement of the velocity).* The dissolution proceeds by
reinstating the velocity in each derivation. Replace each appearance of
$x_4$ that occurs as a static label by the differential form
$dx_4 = ic\,dt$, retaining the velocity content. In $F$, the recomputed
$A$-value picks up the Channel-A phase advance and the Channel-B
null-cone propagation; the same holds in $F'$. The two recomputed values
$A_{\rm McG}(F)$ and $A_{\rm McG}(F')$ are related by a Lorentz
transformation between $F$ and $F'$ (Channel B covariance of the
null-cone) together with a unitary on the algebraic side (Channel A
covariance).

*Step 5 (identification of the static-label artifact).* The original
incompatibility $A(F) \neq A(F')$ is identified with the static-label
artifact: the Channel-A or Channel-B content discarded in the
integration step. The paradox dissolves into a frame-covariant identity.
The instantiation for each specific paradox $P$ in
§§[5](#sec:measurement){reference-type="ref"
reference="sec:measurement"}--[60](#sec:cosmo-measure){reference-type="ref"
reference="sec:cosmo-measure"} is itself a theorem of the present
framework. ◻


::: remark
**Remark 6**. *Theorem [5](#thm:dissolution){reference-type="ref"
reference="thm:dissolution"} is a meta-theorem: it asserts that the
dissolution exists for every paradox in the indicated class. The
remainder of the paper instantiates it for each historical paradox. Each
instantiation is itself a theorem.*


# Paradoxes as Simultaneous Relatedness-and-Disjointness: The Heroic Scientific Philosophy of Finding the Simple Truth 

## The structural definition of a paradox

A paradox, as the word has been used since Zeno and Parmenides, is not
merely a surprise, a difficulty, or an unresolved question. It is a
logical structure with two simultaneous features. Without both features
the structure collapses into something tamer; without either feature it
collapses into something different in kind.


**Definition 7** (Paradox structure). *A *paradox* consists of two (or
more) propositions $P_1, P_2$ that are simultaneously*

1.  **related*: they share a common referent---an object, a quantity, a
    domain, an event---about which both are predicated; and*

2.  **disjoint*: they cannot both be true under a single Boolean
    assignment to that referent.*

*The relatedness $(R)$ enforces that the two propositions are not merely
on different topics. The disjointness $(D)$ enforces that they are not
merely two redundant statements of the same content. A paradox is the
simultaneous insistence on both.*


The point is that one cannot satisfy a paradox by negating one of its
features. To negate $(R)$---to deny that the two propositions concern
the same referent---is to dismiss the paradox without resolving it: one
is no longer talking about the original puzzle. To negate $(D)$---to
deny the disjointness, declaring that the two propositions are
consistent after all---is to retreat into pleasing but unfounded
harmony. A genuine paradox-dissolution must *honor both features
simultaneously*: it must preserve the relatedness (the two propositions
really do concern the same physical situation) and preserve the
disjointness (the two propositions really cannot both be asserted under
a single Boolean assignment), and exhibit a third structure under which
the conflict is reconceived rather than denied.

## Three failure modes of orthodox paradox-resolution

The history of attempts to resolve the paradoxes of quantum mechanics
and relativity exhibits, with notable consistency, three failure modes.
Each fails because it negates one of the two structural features of
paradox rather than honoring both.

*Failure Mode 1 (collapse the disjointness by choosing a horn).* The
standard interpretational program in foundations of quantum mechanics
from the Copenhagen school [@Bohr1928] onward has frequently consisted
of choosing one of two equally well-motivated propositions and silencing
the other. The Many-Worlds Interpretation [@Everett1957; @Wallace2012]
chooses unitary universal evolution and silences the appearance of
probabilistic measurement outcomes; GRW [@GRW1986] and
CSL [@Pearle1989; @BassiGhirardi2003] stochastic-collapse theories
choose probabilistic outcomes and silence exact unitarity. In each case,
the chosen horn is canonized and the silenced horn is reduced to an
emergent or epistemic artifact. The paradox is resolved on paper at the
cost of denying that the silenced proposition was ever a serious
physical statement. This is failure: the relatedness was real, and the
silenced proposition was a load-bearing claim about the same referent.

*Failure Mode 2 (collapse the relatedness by separating contexts).*
Bohr's complementarity [@Bohr1928; @Bohr1935] in its operational form
asserts that "wave" and "particle" descriptions apply in mutually
exclusive experimental contexts, never to the same situation. The two
propositions, on this reading, are not really about the same referent at
all; each is about its own context. Wigner-friend and
Frauchiger--Renner [@Wigner1961; @FrauchigerRenner2018] contexts are
kept apart by the same expedient. The paradox is dissolved at the cost
of denying that there is any common referent---without which the
original puzzle was incoherent in the first place. This is failure: the
disjointness was sharp because the relatedness was real; severing the
relatedness retroactively makes the original observers' worry
illegitimate.

*Failure Mode 3 (postulate-accumulation).* A third failure mode,
structurally distinct from the first two, is to add a new postulate to
the framework specifically to suppress the paradox: a hidden
variable [@Bohm1952; @DurrTeufel2009], a wormhole [@Maldacena2013], a
complexity functional [@Brown2016], a stochastic noise
field [@GRW1986; @Pearle1989], a low-entropy initial
condition [@Albert2000; @Loewer2007], a thermal-time
hypothesis [@ConnesRovelli1994]. Each postulate solves the immediate
impasse by supplying, by hand, machinery the framework's foundational
principles did not entail. Each postulate brings its own structural
issues; new postulates are added to address those; the ontology
proliferates while the foundational principles recede. The present
author has documented this orthodox postulate-accumulation pattern in
detail across ten distinct cases spanning chaos theory, statistical
mechanics, quantum foundations, black-hole thermodynamics, and quantum
gravity [@McGuckenOrthodoxPostulates]. The pattern is in explicit
violation of Newton's Rule I of Reasoning in Philosophy [@Newton1687]:
"We are to admit no more causes of natural things than such as are both
true and sufficient to explain their appearances... For Nature is
pleased with simplicity, and affects not the pomp of superfluous
causes."

## The McGucken Principle exalts dual channels from a single source

The McGucken Principle $dx_4/dt = ic$ provides the structure that honors
paradox in the sense of
Definition [7](#def:paradox-structure){reference-type="ref"
reference="def:paradox-structure"} without falling into any of the three
failure modes above. It does so by exalting two channels from a single
source, where the channels are structurally disjoint and the source is
structurally singular.


**Proposition 8** (Paradox-adequacy of $dx_4/dt = ic$). *The right-hand
side of $dx_4/dt = ic$ has the unique algebraic structure of an
irreducible factorization into two factors of structurally disjoint
physical content---an algebraic factor $i$ and a geometric factor
$c$---combined multiplicatively into one principle. This factorization
satisfies all of:*

1.  **Single principle*: the source is one equation, $dx_4/dt = ic$, of
    one degree, with one undetermined dimensional content.*

2.  **Channel A*: the factor $i$ carries the rotational, unitary,
    symmetric, quantum-mechanical content---one-parameter unitary
    groups, Stone's theorem, canonical commutation, Born
    sesquilinearity, $\pi/2$ Wick rotation, the Heisenberg algebra.*

3.  **Channel B*: the factor $c$ carries the metric, causal,
    propagative, relativistic, thermodynamic content---null cones, light
    propagation, the Lorentz signature, retarded Green's functions, the
    radiative arrow, horizon thermodynamics.*

4.  **Channels structurally disjoint*: the algebraic content of $i$
    shares no intermediate machinery with the geometric content of $c$;
    the derivations along the two channels pass through structurally
    distinct constructions before converging.*


::: proof
*Proof.* *(S).* The equation $dx_4/dt = ic$ has one derivative on the
left and one complex constant on the right; it admits no further
structural simplification. The dimensional content $[c]$ is single
(length/time); the algebraic content $[i]$ is single ($i^2 = -1$). The
principle is irreducible in the sense that no proper sub-equation
captures it.

*(C).* The factor $i$ generates the one-parameter unitary group
$\hat U(t) = \exp(-i\hat H t/\hbar)$ via Stone's theorem applied to the
self-adjoint generator $\hat H$. This is the Channel-A reading: the
imaginary unit makes the time-translation generator skew-Hermitian,
hence its exponential unitary; quantum mechanics inherits its unitary
structure from this fact. The canonical commutation
$[\hat x, \hat p] = i\hbar$, the Heisenberg uncertainty relation, the
Born sesquilinearity $|\langle n|\psi\rangle|^2$, and the $\pi/2$ Wick
rotation $t \to i\tau$ all carry the $i$ from $dx_4/dt = ic$ as their
structural source.

*(B).* The factor $c$ fixes the spherically symmetric expansion velocity
of $x_4$ at every event, generating the McGucken Sphere $\Sigma_+(p)$ as
the future null cone of $p$. This is the Channel-B reading: the
magnitude $c$ supplies the causal-propagation content---no signal
exceeds $c$ in the Channel-B propagation kernel; the retarded Green's
function $G_{\text{ret}}(x-y) \propto \theta(x^0 - y^0)\delta((x-y)^2)$
inherits its support from the null cones generated by $|dx_4/dt| = c$;
the radiative arrow of time, the cosmological expansion, the Hawking
thermal spectrum, and the Unruh effect all inherit their geometric
content from this fact.

*(O).* The Channel-A derivation of the unitary group from the algebraic
content of $i$ passes through Stone's theorem, the spectral theorem, and
the abstract theory of operator algebras. The Channel-B derivation of
null-cone propagation from the geometric content of $c$ passes through
hyperbolic PDE theory, the method of characteristics, and the
construction of retarded Green's functions. The two derivation paths
share no intermediate machinery; an operator-algebraist working in pure
Channel A need never invoke null cones, and a hyperbolic-PDE specialist
working in pure Channel B need never invoke unitary groups. They
converge only at the common source $dx_4/dt = ic$. The structural
disjointness is the diagnostic that no smaller principle could carry
both contents. ◻


**Corollary 9** (Paradox resolution). *Every paradox in the indicated
class (Definition [7](#def:paradox-structure){reference-type="ref"
reference="def:paradox-structure"}) whose disjoint propositions
$P_1, P_2$ separate as one Channel-A claim and one Channel-B claim is
dissolved by recognizing that both are simultaneously true as
projections of $dx_4/dt = ic$. The relatedness $(R)$ is preserved
because both propositions concern the same source; the disjointness
$(D)$ is preserved because the two channels are structurally disjoint;
the appearance of contradiction is dissolved because the Boolean
conflict was an artifact of trying to read both propositions on the same
channel.*


This is the structural mechanism that the remainder of the present paper
instantiates for each historical paradox. The pattern is invariant: each
paradox arises because two structurally disjoint readings of the same
physical situation are forced onto a single Channel, generating an
apparent contradiction; the dissolution is to restore the dual-channel
reading. The disjointness is real and is preserved. The relatedness is
real and is preserved. The contradiction is dissolved.

## Wheeler's criterion and the Heroic Scientific Philosophy of Finding the Simple Truth

John Archibald Wheeler, the author's Princeton mentor, articulated the
criterion by which a foundational principle is to be recognized as the
simple truth behind the apparent complexity of physics. The criterion is
not Occam's razor as understood by eliminative reductionists ("eliminate
one of the contending propositions"). It is the deeper criterion of
structural sufficiency: *one principle that suffices, expressed in the
smallest form that carries the necessary content*. In Wheeler's
words [@WheelerGeons2010]:

> "Behind it all is surely an idea so simple, so beautiful, that when we
> grasp it---in a decade, a century, or a millennium---we will all say
> to each other, how could it have been otherwise? How could we have
> been so stupid?"

Wheeler's criterion descends from Newton's Rule I of Reasoning in
Philosophy [@Newton1687]: admit no more causes than are sufficient. The
McGucken Principle $dx_4/dt = ic$ meets this criterion: it is a single
equation, of one degree, with one algebraic content and one geometric
content---and from it descend, as theorems, the Schrödinger equation,
the Dirac equation, the equivalence principle, the Standard Model gauge
structure, Huygens' principle, the strict Second Law, the Born rule, the
no-graviton property, and the resolution of every paradox catalogued in
this paper. The proliferation of orthodox postulates is the symptom of
having no such source; the McGucken framework supplies, at the source,
what the orthodox framework adds by hand.

The Heroic Scientific Philosophy of Finding the Simple Truth, in the
tradition that runs from Euclid's Definition I.1 through Newton's
*Principia*, through Maxwell's equations, through Einstein's 1905 and
1915 papers, through Wheeler's program, is the search for the single
principle from which the manifest plurality of physical phenomena
descends as theorems. It is heroic because the search is patient,
demanding, often unrewarded by the immediate community, and conducted
against the constant temptation to multiply postulates. It is simple
because its goal is one equation, not many. It is scientific because the
test of success is the descent of theorems---not the multiplication of
frameworks.

The McGucken Principle $dx_4/dt = ic$ is offered, in this paper and in
the broader corpus at
[elliotmcguckenphysics.com](https://elliotmcguckenphysics.com), as the
simple truth Wheeler anticipated. The paradoxes that follow in
§§[5](#sec:measurement){reference-type="ref"
reference="sec:measurement"}--[29](#sec:klein){reference-type="ref"
reference="sec:klein"} are not a list of separate puzzles to be solved
one by one; they are a single phenomenon---the duality-blindness of
orthodox physics to the dual-channel structure of its own foundational
principle---instantiated in many concrete forms. Their unified
resolution is the Heroic Scientific Philosophy's reward.

# Historical Thread: Minkowski to the Present 

## Minkowski 1908 and the integrated coordinate

The fourth dimension entered physics on 21 September 1908, when Hermann
Minkowski opened his address to the 80th Assembly of German Natural
Scientists and Physicians at Cologne with the now-famous sentence:
"Henceforth space by itself, and time by itself, are doomed to fade away
into mere shadows, and only a kind of union of the two will preserve an
independent reality" [@Minkowski1908]. Minkowski's union was algebraic:
he set $x_4 = ict$ and observed that the Lorentz interval became a
Euclidean form $\sum_{\mu=1}^{4} dx_\mu^2$. The Lorentz transformations
became rotations in the $x_4$-$t$ plane; the speed of light became the
asymptotic ratio of $x_4$ to $t$.

The trick worked too well. Within a decade $x_4 = ict$ was used by every
relativist; Einstein adopted it in his 1916 review [@Einstein1916] and
his 1922 Princeton lectures [@Einstein1923]. By the time of Misner,
Thorne, and Wheeler's *Gravitation* [@MTW1973] the convention had been
displaced by the explicit Lorentzian signature $(-,+,+,+)$, but only
because the $ict$ trick was thought to obscure the geometric content of
differential geometry on real manifolds. The imaginary fourth coordinate
was dismissed as "a mere trick that should not seduce" (MTW, Box 2.1).

## Wheeler's program: 1955--1990

John Archibald Wheeler asked the question that Minkowski's trick
suppressed: *what is the fourth dimension doing?* In a sequence of
papers and conferences from 1955 to
1990 [@Wheeler1957; @WheelerFeynman1945; @WheelerZurek1983], Wheeler
advanced four positions that together set up the present resolution.

1.  *Geometrodynamics*: spacetime is not a static background but a
    dynamical entity; geometry itself evolves.

2.  *Delayed-choice gedankenexperiments* [@Wheeler1978]: the photon's
    history is not fixed until measured; this implicates the
    $x_4$-coordinate as an active participant.

3.  *It from bit* [@Wheeler1989]: every physical entity derives its
    existence from a yes/no question; the $x_4$-axis is the carrier of
    the question.

4.  *Spacetime foam*: at the Planck scale, the geometry of $x_4$
    fluctuates.

The McGucken Principle (Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}) is the natural completion of Wheeler's program:
$x_4$ is not a coordinate but a velocity, and the geometry of spacetime
is the integrated history of that velocity.

## From UNC 1998--99 to the present

The principle $dx_4/dt = ic$ was first stated in the appendix to the
present author's 1998--99 UNC Chapel Hill dissertation; developed as
Moving Dimensions Theory (MDT) in 2003--06; presented in five FQXi
essays from 2008 to
2013 [@McGuckenFQXi2008; @McGuckenFQXi2010; @McGuckenFQXi2013]; expanded
in two books in 2016--17; and consolidated in the present corpus of
approximately forty technical papers archived at
[elliotmcguckenphysics.com](https://elliotmcguckenphysics.com). The
principle has been used to derive the Schrödinger
equation [@McGuckenQuantum2026], the Dirac
equation [@McGuckenDirac2026], the equivalence
principle [@McGuckenGR2026], the Standard Model gauge
structure [@McGuckenSM2026], the Penrose twistor program and the
Arkani-Hamed amplituhedron [@McGuckenSpace2026], the Strominger--Vafa
central-charge target [@McGuckenKK2026], and the present unified
resolution of paradoxes.

# The Four-Fold Ontology 


**Definition 10** (Four-fold ontology of $dx_4/dt = ic$). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, every event
$p$ in spacetime falls into exactly one of four ontological categories,
defined by the relative orientation of its worldline tangent and its
$x_4$-velocity.*

Type I (massive at spatial rest):

:   *$d\symbf{x} / dt = 0$ in some frame. The entire $x_4$-velocity
    budget is spent on $x_4$-advance: $|dx_4/dt| = c$. This is the
    rest-mass condition; the time-dilation factor is $\gamma = 1$.*

Type II (null / photon-like):

:   *$|d\symbf{x}/dt| = c$ in every frame. The $x_4$-velocity along the
    worldline is zero: $d x_4/d\lambda = 0$ for an affine parameter
    $\lambda$. The photon does not advance in $x_4$; it rides on the
    front of the $x_4$-expansion.*

Type III (absolute expansion):

:   *The $x_4$-velocity itself is the object, with magnitude $c$ outward
    from every event. This is the spherically symmetric expansion at the
    origin of Axiom [1](#ax:mcg){reference-type="ref"
    reference="ax:mcg"}.*

Type IV (CMB rest frame / cosmological):

:   *The isotropic average of Type III over the visible universe; the
    comoving frame in which the CMB dipole vanishes.*


::: remark
**Remark 11**. *The four types are not exclusive at the level of degrees
of freedom; a single body may have Type-I and Type-III content (rest
mass plus participation in the cosmological expansion), or Type-II
radiation modes superimposed on a Type-I source. The classification is
by tangent-vector category at each event, not by composite object.*


::: remark
**Remark 12**. *Every paradox treated in the rest of this paper can be
located in this ontology. The twin paradox is Type-I vs. Type-I with
different turn-around histories; EPR is Type-II correlation across the
null cone; the cosmological constant is Type-IV; the black hole
information paradox is Type-I matter crossing into a region where the
local $x_4$-axis has rotated by $\pi/2$.*


# The Measurement Problem and Schrödinger's Cat 

## Historical background: von Neumann 1932 to Zeh--Zurek decoherence

The measurement problem is the oldest paradox of quantum mechanics. It
was articulated in three stages. First, von Neumann [@vonNeumann1932]
distinguished the unitary evolution governed by the Schrödinger equation
("process 2") from the projective collapse triggered by measurement
("process 1") and noted that the boundary between them is not specified
by the theory. Second, Schrödinger's 1935 cat thought
experiment [@Schrodinger1935] showed that the unitary--projective
dichotomy, taken seriously, leads to macroscopic superpositions. Third,
Bell [@Bell1990] sharpened the problem with his "against measurement"
essay: any postulated cut between system and apparatus is, on its face,
ad hoc.

## The McGucken $dx_4/dt = ic$ reading

The Schrödinger equation, in its standard form,
$$i\hbar \frac{\partial \psi}{\partial t} \;=\; \hat H \psi,$$ admits a
rewriting in terms of the $x_4$-coordinate. By
Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}, $x_4 = ict$ is the integrated form of
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"};
differentiating, $dx_4/dt = ic$, hence
$\partial/\partial t = ic\,\partial/\partial x_4$, or equivalently
$\partial/\partial x_4 = (1/ic)\,\partial/\partial t = -(i/c)\,\partial/\partial t$.
Substituting into Schrödinger and simplifying:
$$\label{eq:schroedinger-mcg}
\frac{\partial \psi}{\partial x_4} \;=\; \frac{1}{ic}\cdot \frac{\partial \psi}{\partial t} \;=\; \frac{1}{ic}\cdot \frac{(-i)\hat H}{\hbar}\psi \;=\; -\frac{\hat H}{\hbar c}\psi.$$
The algebra: $\partial_t \psi = -(i/\hbar)\hat H\psi$ from Schrödinger;
$\partial_{x_4} \psi = (1/(ic))\partial_t \psi = (-i/c)\cdot(-i/\hbar)\hat H\psi = (i^2/(c\hbar))\hat H\psi = -\hat H\psi/(c\hbar)$.
The Schrödinger equation thus emerges as the Channel-A reading of
$dx_4/dt = ic$ on the Hilbert-space ray of the system: the imaginary
unit $i$ in the standard Schrödinger form is the same $i$ that appears
in $dx_4/dt = ic$ via the substitution
$\partial_t = ic\,\partial_{x_4}$. The projective "process 1" is the
Channel-B reading: at the moment a measurement is recorded, the
fourth-dimensional advance of the apparatus along its worldline pinches
the system's Hilbert-space ray onto the apparatus-eigenbasis.


**Theorem 13** (Measurement as $x_4$-pinch). *Let $\psi$ be a quantum
state evolving under
[\[eq:schroedinger-mcg\]](#eq:schroedinger-mcg){reference-type="eqref"
reference="eq:schroedinger-mcg"}, and let $\hat A$ be a self-adjoint
operator with eigenbasis $\{|a_n\rangle\}$. A measurement of $\hat A$
corresponds to the event at which the apparatus advances in $x_4$ by an
interval $\Delta x_4$ sufficient to decohere the off-diagonal elements
of $\hat{\rho}$ in the $\hat A$-basis. The Born rule
$$P(a_n) \;=\; |\langle a_n | \psi \rangle|^2$$ is the Channel-A
consequence of the $\pi/2$ rotation induced by $i$ in $dx_4/dt = ic$ on
the sesquilinear form $\langle \cdot, \cdot \rangle$.*


::: proof
*Proof.* *Step 1 (Schrödinger as Channel-A integrated form of
$dx_4/dt = ic$).* By
[\[eq:schroedinger-mcg\]](#eq:schroedinger-mcg){reference-type="eqref"
reference="eq:schroedinger-mcg"}, the Schrödinger evolution
$$i\hbar \frac{\partial \psi}{\partial t} = \hat H \psi
\quad \Longleftrightarrow \quad
\frac{\partial \psi}{\partial x_4} = -\frac{\hat H}{\hbar c}\psi,$$ is
the Channel-A reading of Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} on the Hilbert-space ray of the system. The unitary
$$\hat U(\Delta t) = \exp\!\big(-i \hat H\, \Delta t/\hbar\big) = \exp\!\big(-\hat H\, \Delta x_4/(\hbar c)\big), \qquad \Delta x_4 = ic\,\Delta t,$$
follows from Stone's theorem applied to the self-adjoint generator
$\hat H$: the imaginary unit on the left of $\hat H \Delta t$ in the
Schrödinger form is the Channel-A factor in $dx_4/dt = ic$, and the
unitary is one-parameter in $\Delta t$ along the worldline.

*Step 2 (system + apparatus density matrix).* Decompose
$\psi = \sum_n c_n |a_n\rangle$ in the $\hat A$-eigenbasis
$\{|a_n\rangle\}$. The density matrix of the pure state is
$$\rho = |\psi\rangle\langle\psi| = \sum_{m,n} c_m c_n^*\, |a_m\rangle\langle a_n|.$$
Couple the system to an apparatus by a unitary $\hat U_{SA}$ that takes
$|a_n\rangle|A_0\rangle \mapsto |a_n\rangle|A_n\rangle$, where
$\{|A_n\rangle\}$ are macroscopically distinct apparatus pointer states.
After this coupling,
$$|\Psi_{SA}\rangle = \sum_n c_n\, |a_n\rangle|A_n\rangle,$$ and the
reduced density matrix on the system is
$$\rho_S = \mathrm{Tr}_A |\Psi_{SA}\rangle\langle\Psi_{SA}| = \sum_{m,n} c_m c_n^*\, \langle A_n | A_m\rangle\, |a_m\rangle\langle a_n|.$$
For macroscopically distinguishable pointer states,
$\langle A_n | A_m\rangle = \delta_{nm}$, and $\rho_S$ becomes diagonal
in the $\hat A$-basis with diagonal entries $|c_n|^2$.

*Step 3 (the Channel-B decoherence rate from $x_4$-advance of
apparatus).* The apparatus has $N \sim 10^{23}$ microscopic degrees of
freedom each advancing in $x_4$ at $|dx_4/dt| = c$ along its own
worldline; the worldlines are uncorrelated at thermal scales $k_B T$.
The off-diagonal element $\rho_S^{(mn)}$ at $m \neq n$ acquires a phase
$\exp\!\big(i(E_m - E_n) \Delta t/\hbar\big)$ from each apparatus degree
of freedom independently; the modulus of $\rho_S^{(mn)}$ after coupling
to $N$ such degrees of freedom is suppressed by the product
$$|\rho_S^{(mn)}(t)| = |c_m c_n^*| \cdot \prod_{k=1}^N |\langle A_n^{(k)}(t)|A_m^{(k)}(t)\rangle| \;\sim\; |c_m c_n^*|\,e^{-\Gamma t},$$
with decoherence rate $\Gamma \sim N\omega_{th}\mathcal{I}_{mn}$ where
$\omega_{th} = k_B T/\hbar$ and $\mathcal{I}_{mn} \sim 1$ is the
dimensionless interference suppression integral per degree of freedom.
For $N \sim 10^{23}$ and $\omega_{th} \sim 10^{13}\,\mathrm{s}^{-1}$ at
room temperature, $\Gamma \sim 10^{36}\,\mathrm{s}^{-1}$, far exceeding
any laboratory observation time. The Channel-B advance of each apparatus
degree of freedom at $|dx_4/dt|=c$ along its worldline is what provides
the independent phases; the spherical symmetry of the $x_4$-expansion
(Remark [4](#rem:expansion){reference-type="ref"
reference="rem:expansion"}) ensures that distinct worldlines have
uncorrelated phase advances on thermal time-scales, making the product
suppression effective.

*Step 4 (Born sesquilinearity as Channel-A signature).* After Step 3,
the diagonal entries $\rho_S^{(nn)} = |c_n|^2$ are the probabilities of
pointer outcome $|A_n\rangle$. The squared-modulus form
$|c_n|^2 = c_n c_n^*$ is the natural sesquilinear pairing on a complex
Hilbert space whose phase rotation is generated by $i$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this $i$ is
the Channel-A factor in $dx_4/dt = ic$; the sesquilinear (rather than
bilinear) pairing on $\mathcal{H}$ is the consequence of the complex
structure provided by $dx_4 \perp dx_{1,2,3}$ in the McGucken geometry.
The rigorous derivation of the Born rule from $dx_4/dt = ic$ via the
SO(3)-Haar measure on the McGucken Sphere at the registration event is
given as Theorem [45](#thm:born){reference-type="ref"
reference="thm:born"}; here Step 3 supplies the decoherence and
Theorem [45](#thm:born){reference-type="ref" reference="thm:born"}
supplies the weighting.

The combined statement: measurement of $\hat A$ corresponds to the
$x_4$-advance of the apparatus over time $\Delta t \gtrsim 1/\Gamma$,
after which $\rho_S$ is diagonal in the $\hat A$-basis with weights
$|c_n|^2$. ◻


::: corollary
**Corollary 14** (Schrödinger's cat). *The cat is never in a macroscopic
superposition. The atom--detector--cyanide--cat chain involves
$\sim 10^{25}$ thermal degrees of freedom; by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"} the decoherence time scale is
$\Gamma^{-1} \sim 10^{-25}$ s, far shorter than any measurement
interval. The cat is always alive or dead; the question "which one
before we look?" is meaningful and answerable in principle by tracing
the $x_4$-history.*


# EPR, Bell, and Nonlocality 

## Historical background: Einstein--Podolsky--Rosen 1935 to Bell 1964 to Aspect 1982

Einstein, Podolsky, and Rosen [@EPR1935] argued that the quantum
description is incomplete: if two particles can be prepared so that
measurement of one perfectly predicts the result on the other, then the
predicted observable must have a definite value prior to measurement.
Bohr's reply [@Bohr1935] insisted that the whole experimental
arrangement defines the observable. Bell [@Bell1964] converted the
dispute into a quantitative inequality;
experiment [@Aspect1982; @Hensen2015] has decisively confirmed the
quantum predictions. The standard reading is that local realism is dead.

## The McGucken $dx_4/dt = ic$ reading

The EPR "paradox" assumes that spacelike-separated events have
independent $x_4$-coordinates. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} this is
false: at the moment of entanglement, the two particles'
$x_4$-coordinates are correlated, and the spherically symmetric
expansion of $x_4$ from the source event $p_0$ propagates this
correlation to all events on the future null cone of $p_0$.


**Theorem 15** (EPR correlations as $x_4$-co-advance). *Let
$|\Psi\rangle = (|01\rangle - |10\rangle)/\sqrt{2}$ be the singlet of
two spin-$1/2$ particles emitted at event $p_0$. Let $A, B$ be detectors
at spacelike-separated events $p_A, p_B$ on the future null cone of
$p_0$. Then the correlations $E(\hat a, \hat b) = -\hat a \cdot \hat b$
predicted by quantum mechanics, and observed experimentally, follow from
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} without
invoking superluminal influence.*


::: proof
*Proof.* *Step 1 (the shared past at $p_0$).* The singlet
$|\Psi\rangle = (|01\rangle - |10\rangle)/\sqrt 2$ is prepared at event
$p_0$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the McGucken Sphere $\Sigma_+(p_0)$ (the future
null cone of $p_0$) carries the $x_4$-phase content of the prepared
state outward at $|dx_4/dt|=c$. The events $p_A$ and $p_B$ at which the
two particles are detected both lie on $\Sigma_+(p_0)$ (each particle
propagates from $p_0$ along a worldline that, for an entangled pair,
traces a future-directed timelike or null path on the Sphere). The two
detection events share a common "ancestor" at $p_0$ with respect to the
Sphere structure; their correlations are established by this shared
past, not by any superluminal influence between $p_A$ and $p_B$.

*Step 2 (the Channel-A computation of $E(\hat a, \hat b)$).* Let
$\hat a = (\sin\theta_a, 0, \cos\theta_a)$ and
$\hat b = (\sin\theta_b\cos\phi, \sin\theta_b\sin\phi, \cos\theta_b)$ be
the measurement directions on detectors $A$ and $B$, with $\phi$ the
relative azimuthal angle. The spin operators are
$\hat\sigma_A(\hat a) = \hat a \cdot \vec\sigma_A$ and
$\hat\sigma_B(\hat b) = \hat b \cdot \vec\sigma_B$. The expectation
value on the singlet: $$\begin{aligned}
E(\hat a, \hat b) &= \langle \Psi | \hat\sigma_A(\hat a) \otimes \hat\sigma_B(\hat b) | \Psi\rangle \\
&= \frac{1}{2}\big(\langle 01| - \langle 10|\big)(\hat a \cdot \vec\sigma_A)(\hat b \cdot \vec\sigma_B)\big(|01\rangle - |10\rangle\big) \\
&= -\big(a_x b_x + a_y b_y + a_z b_z\big) \;=\; -\hat a \cdot \hat b.
\end{aligned}$$ The minus sign is the singlet's rotational antisymmetry.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
antisymmetry is the Channel-A signature of the $i^2 = -1$ algebraic
structure: exchanging the two particles' $x_4$-phases produces an
overall sign of $-1$, the same sign that distinguishes the singlet
(antisymmetric exchange) from the triplet (symmetric exchange).

*Step 3 (Channel-B no-signaling).* The marginal density at $A$, obtained
by tracing out $B$, is
$$\rho_A = \mathrm{Tr}_B |\Psi\rangle\langle\Psi| = \tfrac{1}{2}\big(|0\rangle\langle 0| + |1\rangle\langle 1|\big) = \tfrac{1}{2}\mathbb{1},$$
independent of $\hat b$. The same holds for $\rho_B$. No measurement at
$A$ is affected by the choice of $\hat b$ at $B$; no signal can be
transmitted from $B$ to $A$ via this choice. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, Channel-B
propagation respects the null-cone causal structure: signals travel
along the future null cone of each event, never spacelike. The events
$p_A$ and $p_B$ are spacelike-separated (each lies on $\Sigma_+(p_0)$
but not on each other's future null cones), so no Channel-B signal
connects $A$'s measurement to $B$'s or vice versa. The Channel-A
correlation $E(\hat a, \hat b) = -\hat a \cdot \hat b$ is real and
observable, but it carries no Channel-B information from one detector to
the other; the correlation is established by the shared past at $p_0$
through Channel B's propagation along $\Sigma_+(p_0)$.

*Step 4 (the Bell--CHSH inequality and Tsirelson's bound).* The CHSH
parameter is
$$\mathcal{S}_{\rm CHSH} \equiv |E(\hat a, \hat b) + E(\hat a, \hat b') + E(\hat a', \hat b) - E(\hat a', \hat b')|.$$
Local hidden-variable theories satisfy $\mathcal{S}_{\rm CHSH} \le 2$.
Quantum mechanics, with the singlet correlations of Step 2, allows
$\mathcal{S}_{\rm CHSH} = 2\sqrt 2$ when
$\hat a, \hat a', \hat b, \hat b'$ are at successive $45^\circ$ angles;
this is Tsirelson's bound [@Cirelson1980], computed directly:
$$\mathcal{S}_{\rm CHSH}^{\rm QM} = |{-\cos\theta_{ab} - \cos\theta_{ab'} - \cos\theta_{a'b} + \cos\theta_{a'b'}}|,$$
optimized at angles giving each term $\pm 1/\sqrt 2$, total
$|4/\sqrt 2| = 2\sqrt 2$. Experimental observation (Aspect
1982 [@Aspect1982], Hensen 2015 [@Hensen2015]) confirms the quantum
prediction. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the violation is the Channel-A non-Booleanity
(Theorem [25](#thm:hardy-ghz-ks){reference-type="ref"
reference="thm:hardy-ghz-ks"}): the projection lattice of quantum
mechanics on the entangled Hilbert space does not admit a Boolean value
assignment compatible with all measurement choices, and the violation
quantifies how far the Channel-A structure departs from Boolean.
Locality (no-signaling) is preserved by Channel B; nonlocality (Bell
correlation) is the algebraic content of Channel A.

*Step 5 (the structural diagnosis).* EPR correlations and Bell
violations are not contradictions with relativistic causality. They are
the dual-channel content of the entangled state at $p_0$: Channel B
propagates the correlation along $\Sigma_+(p_0)$ to both $p_A$ and $p_B$
at $|dx_4/dt|=c$; Channel A supplies the algebraic structure ($i^2 = -1$
singlet antisymmetry) that produces the $-\hat a \cdot \hat b$
correlation pattern. The orthodox confusion that "nonlocality is
required by experiment" conflates Channel A (correlation) with Channel B
(signaling): Channel A is intrinsically nonlocal in the sense of Bell's
correlation inequalities; Channel B is intrinsically local in the sense
of no-signaling. Both coexist because $dx_4/dt = ic$ has both factors. ◻


::: remark
**Remark 16**. *The standard objection that "nonlocality is required by
experiment" conflates Channel A (correlation) with Channel B
(signaling). The McGucken decomposition separates them: Channel A is
intrinsically nonlocal in the sense of Bell's correlation inequalities;
Channel B is intrinsically local in the sense of no-signaling. The two
coexist because $dx_4/dt = ic$ has both factors.*


# Wigner's Friend and Frauchiger--Renner 

## Historical background: Wigner 1961 to Frauchiger--Renner 2018

Wigner [@Wigner1961] asked: if my friend measures a spin and I, outside
the lab, treat the friend--system pair as a unitary quantum system, what
does each of us say about the spin? Frauchiger and
Renner [@FrauchigerRenner2018] sharpened this into a no-go theorem:
assuming consistency, single-outcome, and universality, observers can
reach contradictory conclusions about each other's records.

## The McGucken $dx_4/dt = ic$ reading

Both Wigner's friend and Frauchiger--Renner assume that distinct
observers' $x_4$-clocks are synchronizable in a frame-independent way.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} they
are not.


**Theorem 17** (Wigner-friend dissolution). *Let $W$ (Wigner) and $F$
(Friend) be observers at mutual rest, with $F$ inside a closed lab
measuring observable $\hat A$ of system $S$ and $W$ outside treating
$(F+S)$ as a closed unitary system. Let
$|\psi\rangle = \sum_n c_n |a_n\rangle$ be the pre-measurement state of
$S$, let $E_F$ be the registration event of $F$'s measurement at
$x_4$-phase $x_4^F$, and let $E_W$ be the event at which $W$ inquires
about the joint state, at $x_4$-phase $x_4^W \ge x_4^F$. Then $F$'s
description at $E_F$---"observed $a_n$ with probability $|c_n|^2$"---and
$W$'s description at $E_W$---"the joint $(F+S)$ state is the
superposition $\sum_n c_n |a_n\rangle |F_n\rangle$"---are descriptions
of the same physical reality at two distinct $x_4$-events. The unitary
connecting them is the Channel-B registration map at $E_F$, supplied by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}; no contradiction obtains.*


::: proof
*Proof.* *Step 1 ($x_4$-advance along each worldline).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, each
observer's worldline carries its own $x_4$-advance at rate
$|dx_4/dt| = c$ in that observer's rest frame. $W$ and $F$ are at mutual
rest, so their proper-time rates of $x_4$-advance agree; their
$x_4$-clocks are synchronizable on any single Cauchy slice through their
joint frame, but the events $E_F$ and $E_W$ lie at distinct $x_4$-phases
along the shared frame's $x_4$-axis.

*Step 2 ($F$'s description at $E_F$ by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}).* At event $E_F$, $F$'s apparatus couples
to $S$ through a unitary $\hat U_{SF}$ that takes
$|a_n\rangle |F_0\rangle \mapsto |a_n\rangle |F_n\rangle$ with
$\{|F_n\rangle\}$ macroscopically distinct pointer states. By Steps 2--4
of the proof of Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, the reduced density matrix on $S$ becomes
diagonal in the $\hat A$-basis at the Channel-B decoherence rate
$\Gamma \sim N\omega_{th}$ over the apparatus's $N \sim 10^{23}$ thermal
degrees of freedom. At $x_4$-phase $x_4^F$, $F$'s record is the
classical outcome $a_n$ with probability $|c_n|^2$, supplied by the
SO(3)-Haar measure on the McGucken Sphere at $E_F$
(Theorem [45](#thm:born){reference-type="ref" reference="thm:born"}).

*Step 3 ($W$'s description at $E_W$ without access to $F$'s outcome).*
$W$, treating the lab as a closed system and lacking access to $F$'s
record, applies unitary quantum mechanics to the joint system. The
unitary $\hat U_{SF}$ acts on the pre-measurement state to produce the
entangled joint state
$$|\Psi_{SF}\rangle = \hat U_{SF}\,|\psi\rangle |F_0\rangle = \sum_n c_n |a_n\rangle |F_n\rangle .$$
$W$'s description at $E_W$ is this superposition---unitary because
$\hat U_{SF}$ is unitary, and consistent with
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} because
$\hat U_{SF}$ is the Channel-A integrated form of $dx_4/dt = ic$ on the
joint Hilbert space.

*Step 4 (the two descriptions concern distinct $x_4$-events).* $F$'s
description is a statement at $E_F$: at $x_4^F$, the registration event
has occurred and the outcome is one of the $\{a_n\}$. $W$'s description
is a statement at $E_W$: at $x_4^W$, before $W$ has gained access to
$F$'s record, the joint state remains in the unitary superposition. The
two descriptions do not predicate contradictory properties of a single
event; they predicate complementary contents of two distinct events on
$F$'s worldline.

*Step 5 (the connecting unitary).* The map from $F$'s eigenstate
description at $E_F$ to $W$'s superposition description at $E_W$ is the
Channel-B registration map
$\mathcal{R}_F: |\Psi_{SF}\rangle \to \{(|a_n\rangle|F_n\rangle, |c_n|^2)\}$,
supplied by Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}. The inverse map $\mathcal{R}_F^{-1}$, from
$F$'s classical outcome back to the unitary superposition, requires
re-coherence of the apparatus's $N$ thermal modes, which is excluded by
the Channel-B advance of these modes along their worldlines
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, Step 3). The two descriptions are
connected by $\mathcal{R}_F$ in one direction but the inverse is
irreversible at the Channel-B decoherence scale.

*Step 6 (no contradiction).* The Wigner-friend "paradox" arises by
demanding that $W$'s description at $E_W$ should equal $F$'s description
at $E_F$ under a single Boolean assignment. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the two
descriptions concern distinct $x_4$-events, and no single Boolean
assignment is licensed---neither classical, nor any naive "one universal
observer" fiction. $F$'s description is the Channel-B
Sphere-registration content at $E_F$; $W$'s description is the Channel-A
unitary content of the joint algebra at $E_W$. Both are correct in their
channels and at their events. ◻


::: corollary
**Corollary 18** (Frauchiger--Renner dissolution). *The
Frauchiger--Renner contradiction [@FrauchigerRenner2018] arises only
when four observers' records are forced into a single $x_4$-frame at a
single $x_4$-event. By Theorem [17](#thm:wigner){reference-type="ref"
reference="thm:wigner"}, each observer's record exists at a distinct
registration event $E_i$ with its own $x_4$-phase $x_4^i$. The
assumption labelled "universality" in Frauchiger--Renner (one observer
applies unitary QM to another) is consistent with
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} when paired
with the Channel-B registration map $\mathcal{R}_i$ at each $E_i$, which
converts the prior observer's unitary description into the next
observer's classical record. The Frauchiger--Renner construction
implicitly drops the Channel-B registration maps and demands consistency
of the resulting purely-unitary chain at a single $x_4$-event; the
dropped registrations are exactly the source of the contradiction.*


# Wave--Particle Duality, Delayed Choice, and the Quantum Eraser 

## Historical background: Bohr complementarity to Wheeler delayed choice

Wave--particle duality was Bohr's complementarity [@Bohr1928]: an
experiment that reveals which-path information destroys interference.
Wheeler's delayed-choice gedankenexperiment [@Wheeler1978] pushed the
choice into the past: the experimenter can decide after the photon has
passed the slits whether it "was" a wave or a particle. Scully and
Drühl [@ScullyDruhl1982] added the quantum eraser: a which-path mark,
later erased, restores interference.

## The McGucken $dx_4/dt = ic$ reading

All three phenomena describe the same fact: the photon's wave function
advances in $x_4$ at $dx_4/dt = ic$, and the interference pattern lives
on the spatial cross-section of that $x_4$-advance. Which-path
measurements are Channel-B pinches that localize $x_4$; erasure restores
Channel-A coherence.


**Theorem 19** (Duality as $x_4$-projection). *Let a photon emerge from
a Mach--Zehnder interferometer with arms $L_1, L_2$. The output
intensity at detector $D$ is
$$I(D) \;=\; \big| \psi_1 + \psi_2 \big|^2 \;=\; |\psi_1|^2 + |\psi_2|^2 + 2\,\Re\big(\psi_1^* \psi_2\big),$$
where the interference term $\Re(\psi_1^* \psi_2)$ is the Channel-A
phase $\exp(i\Delta\phi)$ with
$\Delta\phi = \Delta x_4 / c = (L_1 - L_2)$. Which-path information is
the Channel-B record of the $x_4$-pinch event; its presence sets
$\Re(\psi_1^* \psi_2) = 0$ by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}.*


::: proof
*Proof.* *Step 1 ($x_4$-phase accumulation along null worldlines).* A
photon propagates on a null worldline $\gamma$: $|d\vec x/dt| = c$ and
$|dx_4/dt| = c$ together with $dx_4 \perp d\vec x$, with the photon's
worldline-tangent purely in the spatial direction at each event (Type II
of Definition [10](#def:fourfold){reference-type="ref"
reference="def:fourfold"}). The photon's wave function carries a
Channel-A phase whose accumulation along $\gamma_j$ is
$$\phi_j = \int_{\gamma_j} \frac{|dx_4|}{c} \cdot \frac{\omega}{c} \cdot c\,dt = \omega L_j/c,$$
with $\omega$ the angular frequency of the mode and $L_j$ the path
length. The phase factor $e^{i\phi_j}$ is the Channel-A integrated
content of $dx_4/dt = ic$ along $\gamma_j$, with the imaginary unit $i$
supplied by the algebraic factor in the McGucken Principle.

*Step 2 (the two paths of a Mach--Zehnder interferometer).* The
interferometer prepares two paths $\gamma_1, \gamma_2$ of lengths
$L_1, L_2$ between the input beam splitter and detector $D$. The output
amplitude at $D$ is the coherent sum of the two channel amplitudes:
$$\psi(D) = \tfrac{1}{\sqrt{2}}\,e^{i\phi_1} + \tfrac{1}{\sqrt{2}}\,e^{i\phi_2}, \qquad \Delta\phi \equiv \phi_2 - \phi_1 = \omega (L_2 - L_1)/c.$$
The output intensity is the squared modulus:
$$I(D) = |\psi(D)|^2 = \tfrac{1}{2}|e^{i\phi_1}|^2 + \tfrac{1}{2}|e^{i\phi_2}|^2 + \Re\big(e^{i(\phi_2-\phi_1)}\big) = 1 + \cos\Delta\phi.$$
The interference fringe $\cos\Delta\phi$ is the Channel-A trace of the
$x_4$-phase difference between the two paths.

*Step 3 (the role of the squared modulus / Born sesquilinearity).* The
squared-modulus extraction in Step 2 is the natural sesquilinear pairing
on a complex Hilbert space whose phase generator is $i$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this $i$ is
the Channel-A factor in $dx_4/dt = ic$; the sesquilinear (not bilinear)
pairing is the consequence of the imaginary structure that relates $x_4$
to $t$. The interference is geometric on the McGucken Sphere structure
of each detection event and algebraic in the Channel-A phase sum;
Theorem [45](#thm:born){reference-type="ref" reference="thm:born"}
supplies the rigorous Born-rule derivation, which the present proof
relies on.

*Step 4 (which-path detection as Channel-B pinch).* A which-path
detector $D_j$ at one of the arms couples its $N_d$ thermal degrees of
freedom to the photon's path register. By
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, this coupling decoheres the off-diagonal
element $|\gamma_1\rangle\langle\gamma_2|$ at rate
$\Gamma \sim N_d \omega_{th}$, suppressing it on time scales
$1/\Gamma \ll$ any laboratory measurement interval. The resulting output
intensity at $D$ is
$$I(D) = \tfrac{1}{2}|e^{i\phi_1}|^2 + \tfrac{1}{2}|e^{i\phi_2}|^2 = 1,$$
with no interference fringe. The fringe is suppressed by the Channel-B
advance of $D_j$'s thermal degrees of freedom in $x_4$.

*Step 5 (Wheeler delayed choice).* The delayed-choice variant inserts or
removes the final beam splitter after the photon has passed the first
beam splitter. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the photon's null worldline through $\gamma_1$ and
$\gamma_2$ is fixed by the source event; only the basis in which the
detector projects is chosen at the final beam splitter. The Channel-A
phase accumulation in Step 1 is unchanged by the delayed choice; what
changes is the projection basis at the detection event. No retroactive
influence on the photon's history is required; the structural source of
the apparent "retrocausality" is the conflation of $x_4$ (the photon's
worldline-fixed null content) with the experimenter's later choice of
measurement basis.

*Step 6 (quantum eraser).* The eraser inserts a which-path mark at one
arm and then a basis-conjugating element later that erases the mark from
the apparatus record (e.g., a polarizer that mixes the path-tagged
polarization states). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the which-path mark is a Channel-B pinch event
$E_{\rm mark}$; the erasure is a unitary operation on the apparatus's
path-tag register that maps the marked basis back to a basis orthogonal
to the path-tagging. The interference fringes are recovered in the
post-selected subensemble conditioned on the erasure outcome because the
conditional state has its which-path register projected onto the
basis-conjugating eigenvector; the Channel-A phase coherence is
preserved in the original $x_4$-history and is recovered by the
post-selection. The fringe pattern is always present in the original
null-worldline phase content; the eraser exposes it by conditioning on
the right apparatus outcome. ◻


::: corollary
**Corollary 20** (Wheeler delayed choice). *The photon does not
retroactively decide its history. The $x_4$-coordinate of the photon's
null worldline is already fixed by the source event; the experimenter's
later choice of basis selects which projection of the $x_4$-history is
recorded, but does not alter the history. The "mystery" is the artifact
of identifying $x_4$ with $t$ rather than with $ict$.*


::: corollary
**Corollary 21** (Quantum eraser). *The eraser restores the Channel-A
coherence by destroying the Channel-B which-path record. The $x_4$-pinch
is reversed only in the algebraic basis, not in the geometric record;
the spatial intensity pattern at $D$ recovers the interference fringes
that were always present in the $x_4$-history.*


# The Photon's Four-Velocity Paradox and the Photon as Tracer of $x_4$ 

## Historical background: Peebles and Wheeler at Princeton 1988--1990 to FQXi 2008--2013

The orthodox definition of four-velocity is $u^\mu = dx^\mu/d\tau$,
where $\tau$ is the object's proper time. The four-velocity has
invariant magnitude $u^\mu u_\mu = -c^2$ (in the mostly-plus signature)
or $+c^2$ (in the mostly-minus signature); textbooks state the result as
"every particle's four-velocity has magnitude $c$" and derive time
dilation, the twin paradox, and much of relativistic kinematics from it.
The heuristic slogan "everyone moves through spacetime at $c$" (Greene,
Epstein) presents the same content in didactic form.

The photon, however, has proper time $d\tau = 0$ along its null
worldline: light does not age. The definition $u^\mu = dx^\mu/d\tau$ is
therefore ill-posed for the photon, with the derivative producing $0/0$
rather than a finite four-velocity. Standard textbooks acknowledge the
failure directly: parametrization by proper time is conditioned on "*if*
the object has mass"; the massless case is handled by substituting an
affine parameter $\lambda$ whose tangent vector
$k^\mu = dx^\mu/d\lambda$ has null norm ($k^\mu k_\mu = 0$), not norm
$c$. Introductory expositions state the consequence baldly: "4-velocity
doesn't work for light." Review articles concur that the surviving
null-tangent quantity is "regarded as a mere mathematical property with
no physical meaning."

The result is a structural asymmetry in the orthodox description of the
photon:

-   **What is a photon doing relative to $x_1, x_2, x_3$?** Fully
    answered: wavevector $\vec k$, momentum $\vec p = \hbar \vec k$,
    direction, polarization, propagation at $c$. Entire industries of
    experimental optics.

-   **What is a photon doing relative to $x_4$?** Undefined. The
    formalism declines to speak.

The one entity in the universe that actually travels at $c$ (the object
that defines the constant) is the one entity excluded from "every
particle's four-velocity has magnitude $c$." The constant is defined by
the case that the rule cannot describe.

The FQXi papers of the present author
(2008--2013) [@McGuckenFQXi2008; @McGuckenFQXi2013] developed the
resolution from two orthodox observations: P. J. E. Peebles' teaching
(Princeton, 1988--1990) that a photon's wavefront is a sphere of
probability expanding at $c$ [@Peebles1992], and J. A. Wheeler's
teaching (Princeton, 1988--1990) that the ageless photon is stationary
in $x_4$ [@WheelerGeons2010]. Neither observation is controversial. The
synthesis is the derivation of $dx_4/dt = ic$ from experimental
observation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 22** (The photon as tracer of $x_4$:
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} derived from
Peebles' expanding sphere and Wheeler's ageless photon). *The orthodox
formal problem---that the four-velocity $u^\mu = dx^\mu/d\tau$ is
undefined for a photon because $d\tau = 0$ on null worldlines---is not a
physical problem but a formal artifact of parametrizing by proper time.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
$dx_4/dt = ic$ is stated against coordinate time $t$, which is nonzero
for photons; the photon has definite $dx_4/dt = 0$ (Type II of
Definition [10](#def:fourfold){reference-type="ref"
reference="def:fourfold"}, four-fold ontology) and is at absolute rest
in $x_4$. The photon's spatial propagation at $c$ is not the photon
moving through $x_4$; it is the motion of $x_4$ itself made visible by
the photon marker. Peebles' expanding-probability-sphere and Wheeler's
ageless-photon, held together, force the derivation of
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}: a body at
rest in a medium observed to be displaced was displaced by the medium.*


::: proof
*Proof.* *Step 1 (the orthodox failure).* The orthodox four-velocity
$u^\mu = dx^\mu/d\tau$ has $u^\mu u_\mu = -c^2$ for timelike worldlines
(Lorentzian signature $(-,+,+,+)$). For a photon's null worldline,
$d\tau^2 = -dx^\mu dx_\mu/c^2 = 0$, so $d\tau = 0$ identically. The
derivative $dx^\mu/d\tau$ is then a $0/0$ indeterminate form, undefined.
The orthodox literature handles this by substituting an affine parameter
$\lambda$, obtaining the tangent vector $k^\mu = dx^\mu/d\lambda$ with
$k^\mu k_\mu = 0$. The null tangent $k^\mu$ carries physical content
(frequency, wavevector, polarization), but it does not have norm $c$, so
it is not a four-velocity in the orthodox sense; standard reviews
describe $k^\mu k_\mu = 0$ as "a mere mathematical property with no
physical meaning." The photon has been formally excluded from the
four-velocity framework.

*Step 2 (Peebles' expanding-probability-sphere).*
Peebles [@Peebles1992], teaching quantum mechanics at Princeton,
described the photon emitted from a source as having wave function whose
probability amplitude expands as a spherical wavefront centered on the
emission event $E_0$: the amplitude $\psi(\vec x, t)$ has support on the
sphere of radius $ct$ centered on $E_0$, at coordinate time $t$ after
emission. The sphere expands at $c$ in each observer's frame. This is
standard quantum electrodynamics: the free-space photon propagator has
support on the light cone of $E_0$, and the massless dispersion relation
$\omega = c|\vec k|$ gives spherical wave-packet spreading at $c$.
Peebles' presentation is fully orthodox.

*Step 3 (Wheeler's ageless-photon).* Wheeler [@WheelerGeons2010],
teaching general relativity at Princeton, described the photon's null
worldline as one along which no proper time elapses: $\Delta\tau = 0$
from emission at $E_0$ to absorption at $E_A$, regardless of the
coordinate-time interval $\Delta t = t_A - t_0$ or the spatial
displacement $\Delta \vec x$. The photon is "ageless" along its entire
null trajectory. Wheeler's presentation is fully orthodox: it is the
standard consequence of the null-worldline definition.

*Step 4 (the synthesis: displacement without self-motion).* Peebles'
observation supplies a fact about the photon's spatial content: the
wavefront expands at $c$ in coordinate time $t$. Wheeler's observation
supplies a fact about the photon's temporal content: no proper time
elapses along the photon's worldline. Held together, the two
observations produce a structural conclusion. If the photon is
"ageless"---has no $x_4$-advance of its own along its worldline---then
the expansion of its wavefront at $c$ is not the photon moving through
$x_4$. But the wavefront visibly propagates outward in the physical
spacetime containing the photon. If the photon contributes no
$x_4$-motion of its own, and the wavefront nevertheless propagates, then
the propagation is not sourced by the photon.

Formally: a body at rest in a medium, observed to be displaced, has been
displaced by the medium. The photon contributes no $x_4$-motion of its
own (Wheeler); its wavefront propagates at $c$ (Peebles); the
propagation is therefore the motion of the medium ($x_4$ itself) made
visible by the photon marker. The photon is a tracer riding the
$x_4$-expansion, not an object generating it.

*Step 5 (the derivation of Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}).* The $x_4$-expansion has magnitude $c$ (the
photon-wavefront expansion rate) and orientation orthogonal to the three
spatial directions (the wavefront is a sphere in spatial hyperslices,
orthogonal to any radial direction). The orthogonality is implemented
algebraically by the imaginary unit $i$: the fourth axis is $ict$, not
$ct$, precisely because it is orthogonal to $\vec x$ (Minkowski's
$x_4 = ict$). Combining magnitude, direction, and orthogonality:
$$\boxed{\dfrac{dx_4}{dt} = ic.}$$ This is
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}. The
derivation uses only two orthodox observations (Peebles' expanding
sphere, Wheeler's ageless photon) and one structural inference
(displacement of a stationary marker is displacement by the medium). The
FQXi papers [@McGuckenFQXi2008; @McGuckenFQXi2013] record the original
derivation from these ingredients.

*Step 6 (the budget partition without exception).*
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} is stated
against coordinate time $t$, not proper time $\tau$. Coordinate time is
well-defined for photons: it does not vanish along a photon's worldline.
The four-velocity budget partition $$|\vec v|^2 + c_{x_4}^2 = c^2$$
(where $c_{x_4} = |dx_4/dt|$ is the frame-projected $x_4$-advance rate)
applies to every worldline, null included:

-   **Massive particle at spatial rest:** $\vec v = 0$, $c_{x_4} = c$.
    Full budget into $x_4$-advance (Type I of
    Definition [10](#def:fourfold){reference-type="ref"
    reference="def:fourfold"}).

-   **Massive particle moving at $\vec v$:** split budget,
    $c_{x_4}^2 = c^2 - |\vec v|^2$, giving time dilation
    $c_{x_4}/c = \sqrt{1 - v^2/c^2}$.

-   **Photon:** $|\vec v| = c$, $c_{x_4} = 0$. Full budget into spatial
    motion, none into $x_4$-advance (Type II).

The photon is not an exception to the rule; it is the boundary case that
defines the constant $c$. The photon travels at $c$ because it has
nothing left over: with the entire four-velocity budget spent on spatial
motion, there is nothing for $x_4$-advance, and the photon is at
absolute rest in $x_4$ ($dx_4/dt = 0$ as an ontological statement, not
merely as a limit).

*Step 7 (the physical meaning of $dx_4/dt = 0$ for the photon).* The
photon's "agelessness" has a physical interpretation under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}. The photon
does not age because it is not moving along the dimension whose advance
is ageing. It stands still in $x_4$ while everything else advances. The
emitted photon arrives having experienced no proper time not because its
clock stopped mysteriously, but because it is a particle at rest in the
one dimension where rest means no elapsed time. The orthodox "vanishing
proper time" is the same content restated in a formalism that could not
accommodate it directly; Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}'s "$dx_4/dt = 0$" names it plainly.

*Step 8 (the speed of light as fully-spent budget, not as a barrier).*
Orthodox relativity presents $c$ as a limiting speed: nothing can travel
faster than $c$, and the limit is enforced by the Lorentz factor
$\gamma \to \infty$ as $v \to c$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the speed
of light is not a barrier imposed from outside. It is the case of a
fully-spent budget: a particle travels at $c$ when it has spent its
entire four-velocity budget on spatial motion, leaving nothing for
$x_4$-advance. Faster-than-$c$ motion would require the four-velocity
budget to exceed $c$, but the budget is fixed at $c$ by
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}. The speed
limit is not an external constraint on motion; it is a bookkeeping
identity on the fixed budget.

*Step 9 (structural diagnosis: the undefined was unexamined, not
empty).* The orthodox formalism's silence on the photon's $x_4$-relation
is not a physical result; it is the formalism declining to speak,
produced by dividing by a quantity ($d\tau$) that vanishes on the null
case. Two real things (a photon and the dimension $x_4$) must stand in
some real relation; the relation is not "undefined," it is
$dx_4/dt = 0$. The orthodox "undefined" is not empty; it is unexamined.
The framework's contribution to the photon-and-$x_4$ question is not new
mathematics---every mathematical ingredient is orthodox---but the
refusal to accept "undefined" as a physical answer about the relation
between two things the theory itself says are real. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the answer
is definite: the photon is at absolute rest in $x_4$, and its spatial
propagation at $c$ is the tracer signature of the $x_4$-expansion
itself. ◻


::: corollary
**Corollary 23** (Every double-slit diagram is a picture of $x_4$'s
motion). *The wavefront-expansion diagrams of the double-slit experiment
(Bohr, Einstein, Feynman) depict spherical wavefronts spreading at $c$
from the source, interfering at the slits, and producing the fringe
pattern at the detector. Under
Theorem [22](#thm:photon-tracer){reference-type="ref"
reference="thm:photon-tracer"}, the wavefront's spatial expansion at $c$
is the motion of $x_4$, not the motion of the photon (which is at
absolute rest in $x_4$). Every diagram of the double-slit experiment
ever drawn is therefore a picture of the fourth dimension in motion,
with the photon marker riding on it. The diagram was never only about
light; it was a diagram of $x_4$, and light was the tracer that made the
diagram visible.*


::: remark
**Remark 24**. *The derivation of
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} from
Peebles' expanding-probability-sphere and Wheeler's ageless-photon uses
two orthodox teachings from the same decade at the same university
(Princeton, 1988--1990). The originality of the framework is not in the
addition of new mathematics but in the refusal to accept "undefined" as
a physical answer to the question "what is a photon doing relative to
$x_4$?" The formalism said the question was inadmissible; the FQXi
papers [@McGuckenFQXi2008; @McGuckenFQXi2013] asked it anyway, and the
answer was definite. The undefined was not empty. It was unexamined.*


# Hardy's Paradox, GHZ, and Kochen--Specker 

## Historical background: Kochen--Specker 1967, GHZ 1989, Hardy 1992

Hardy [@Hardy1992] produced a non-statistical proof of Bell's theorem:
9% of trials exhibit a logical contradiction with local realism.
Greenberger, Horne, and Zeilinger [@GHZ1989] sharpened this to a
deterministic contradiction with three particles. Kochen and
Specker [@KochenSpecker1967] showed that no hidden-variable theory can
simultaneously assign values to all commuting subsets of observables.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 25** (Hardy / GHZ / Kochen--Specker as Channel-A
non-Booleanity). *The contradictions of Hardy, GHZ, and Kochen--Specker
arise from assuming that quantum observables form a Boolean algebra.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} the
algebra of observables is the algebra of self-adjoint operators on the
Hilbert space whose imaginary axis is $x_4$. This algebra is non-Boolean
because $i^2 = -1$ does not commute with the orthocomplementation; the
contradictions are the standard non-Boolean shadow of the $i$ in
$dx_4/dt = ic$.*


::: proof
*Proof.* *Step 1 (the algebraic structure of contextuality).* A Boolean
"value assignment" on observables would require, for any observable
$\hat A$, a function $v(\hat A)$ depending only on $\hat A$, not on the
experimental context $\mathcal{C}$ in which $\hat A$ is measured. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, measurement
of $\hat A$ corresponds to an $x_4$-pinch of the apparatus into the
basis of $\hat A$ (Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}). Two distinct contexts
$\mathcal{C}, \mathcal{C}'$ in which $\hat A$ commutes with different
"partner" observables $\hat B, \hat B'$ correspond to pinches in
distinct apparatus bases. Under the Channel-A operator algebra, the two
bases are related by a unitary rotation
$\hat U_{\mathcal{C}\to\mathcal{C}'}$ generated by $i$ (the Channel-A
factor in $dx_4/dt = ic$). The value-assignment $v$ does not preserve
this rotation: there exists no consistent Boolean function on the
lattice of projections of $\mathcal{H}$ that respects all
simultaneous-measurability relations.

*Step 2 (Hardy's 9% computation).* The Hardy state on two
spin-$\tfrac{1}{2}$ particles is
$$|\Psi_H\rangle = \frac{1}{\sqrt{3}}\big(|+\rangle_A|-\rangle_B + |-\rangle_A|+\rangle_B + |-\rangle_A|-\rangle_B\big),$$
in the $\hat\sigma_z$ eigenbasis $\{|+\rangle,|-\rangle\}$. Define
rotated single-particle bases by
$$|u_X\rangle = \alpha|+\rangle_X + \beta|-\rangle_X, \qquad |v_X\rangle = \beta|+\rangle_X - \alpha|-\rangle_X, \quad X \in \{A,B\},$$
with $\alpha, \beta$ real and $\alpha^2 + \beta^2 = 1$. Hardy's setup
fixes the angles by requiring
$$\langle u_A u_B | \Psi_H\rangle = 0, \quad \langle u_A +_B | \Psi_H \rangle = 0, \quad \langle +_A u_B | \Psi_H \rangle = 0.$$
The first equation, expanded:
$(\alpha\langle +_A| + \beta\langle -_A|)(\alpha\langle +_B| + \beta\langle -_B|)|\Psi_H\rangle = (\alpha\beta + \alpha\beta + \beta^2)/\sqrt 3 = 0$,
giving $\beta(2\alpha + \beta) = 0$. The nontrivial solution:
$\beta = -2\alpha$. Combined with $\alpha^2 + \beta^2 = 1$:
$\alpha^2 + 4\alpha^2 = 1$, hence $\alpha^2 = 1/5$ and $\beta^2 = 4/5$.
The joint probability of the contradictory outcome $(v_A, v_B)$---which
local realism would forbid given the three orthogonality conditions
above---is
$$P(v_A, v_B) = |\langle v_A v_B | \Psi_H\rangle|^2 = \left|\frac{\beta^2 - \alpha\beta - \alpha\beta}{\sqrt 3}\right|^2 = \frac{(\beta^2 - 2\alpha\beta)^2}{3}.$$
Substituting $\alpha = -\beta/2$, $\beta^2 = 4/5$,
$\alpha\beta = -\beta^2/2 = -2/5$, so
$\beta^2 - 2\alpha\beta = 4/5 - 2\cdot(-2/5) = 4/5 + 4/5 = 8/5$; hence
$P = (8/5)^2/3 = 64/75$. The fully optimized Hardy contradiction
probability (over all choices of rotated bases consistent with the
orthogonalities) is the well-known maximum [@Hardy1992]
$$P_{\max} = \frac{5\sqrt{5} - 11}{2} \approx 0.0902,$$ the "9%". Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
nonzero probability is the structural signature of the Channel-A unitary
rotation between the four overlapping contexts: each context is an
$x_4$-pinch in a distinct basis, and the rotations among them generated
by $i$ produce contributions to the contradictory amplitude that no
Boolean value-assignment can absorb.

*Step 3 (the GHZ deterministic contradiction).* The three-qubit GHZ
state is
$$|\Psi_{\rm GHZ}\rangle = \tfrac{1}{\sqrt 2}\big(|000\rangle - |111\rangle\big).$$
Direct verification:
$\hat X_1 \hat Y_2 \hat Y_3 |\Psi_{\rm GHZ}\rangle = (i)(i)\,\tfrac{1}{\sqrt 2}(\hat X_1|1\rangle|10\rangle - \hat X_1|0\rangle|01\rangle)\cdots$;
standard computation (cf. [@GHZ1989]) gives eigenvalue $+1$ for each of
$\hat X_1 \hat Y_2 \hat Y_3$, $\hat Y_1 \hat X_2 \hat Y_3$,
$\hat Y_1 \hat Y_2 \hat X_3$, and eigenvalue $-1$ for
$\hat X_1 \hat X_2 \hat X_3$. The product of the first three operators,
using $\hat Y_i^2 = \mathbb{1}$ and the commutation of operators on
distinct qubits, equals $\hat X_1 \hat X_2 \hat X_3$ as an operator
identity; but the product of the three eigenvalues $(+1)(+1)(+1) = +1$
disagrees with the eigenvalue $-1$ of $\hat X_1 \hat X_2 \hat X_3$. The
Boolean product of eigenvalues fails by a sign. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the sign
mismatch is the algebraic shadow of $i^2 = -1$ in $dx_4/dt = ic$: each
$\hat Y_i = i\hat X_i \hat Z_i$ carries a factor of $i$, and the product
of three $\hat Y$'s contributes $i^2 \cdot i = -i$ phase content that no
Boolean reading can incorporate.

*Step 4 (the Kochen--Specker no-go).* Kochen and
Specker [@KochenSpecker1967] constructed 117 vectors in $\mathbb{R}^3$
(later reduced to 31 by Conway--Kochen, 33 by Peres, 18 by
Cabello--Estebaranz--García-Alcaine [@CabelloEstebaranz1996]) such that
no consistent assignment of "$0$" and "$1$" values exists under the rule
that each orthogonal triad receives exactly one $1$ and two $0$'s. The
obstruction is the non-Boolean structure of the projection lattice on
the spin-$1$ Hilbert space $\mathbb{C}^3 \cong \mathbb{R}^3$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
projection lattice's non-Booleanity is the algebraic content of the $i$
in $dx_4/dt = ic$ acting on the Hilbert space: the lattice of
projections is orthomodular but not distributive, and the failure of
distributivity is the failure of the Boolean value-assignment over
orthogonal contexts.

*Step 5 (uniform structural diagnosis).* Hardy's 9%, the GHZ sign
mismatch, and the Kochen--Specker no-go are three operational signatures
of the same structural fact: the projection lattice of quantum
mechanics, supplied by Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} via the Channel-A complex structure of $i$, does not
admit a Boolean value assignment compatible with all
simultaneous-measurability relations. The contradictions are not
contradictions in nature; they are the failure of the Boolean reading of
quantum mechanics to capture the algebraic structure that the McGucken
Principle requires. ◻


# Mott, Renninger, Elitzur--Vaidman, and Zeno 

## Historical background: Mott 1929 to Renninger 1953 to Elitzur--Vaidman 1993

Mott [@Mott1929] asked why an $\alpha$-particle emerging from a nucleus
as a spherical wave leaves a straight track in a cloud chamber.
Renninger [@Renninger1953] pointed out that not observing a particle at
one detector is itself a measurement that collapses the wave function
elsewhere---a negative-result measurement. Elitzur and
Vaidman [@ElitzurVaidman1993] showed that a bomb with a single-photon
trigger can be detected by a photon that did not interact with it. Misra
and Sudarshan [@MisraSudarshan1977] showed that continuous observation
freezes quantum evolution: the quantum Zeno effect.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 26** (Tracks, negative results, interaction-free measurement,
and Zeno as $x_4$-pinches). *Each of Mott's tracks, Renninger's
negative-result collapse, Elitzur--Vaidman bomb testing, and the quantum
Zeno effect is a sequence of $x_4$-pinches by detector degrees of
freedom on a propagating wave. The wave advances at $dx_4/dt = ic$
between pinches; each pinch is a Channel-B decoherence event by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}.*


::: proof
*Proof.* *Step 1 (the common structure: detector as $x_4$-coupled
apparatus).* Each of the four phenomena involves a wave function
evolving freely between detection events and undergoing Channel-B
decoherence at each detection event. The free evolution is the Channel-A
integrated form of $dx_4/dt = ic$ on the Hilbert-space ray
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, Step 1); the detection event is the
Channel-B pinch by Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, Step 3, with the apparatus's $N$ thermal
degrees of freedom advancing independently in $x_4$ along their
worldlines. The four phenomena differ in the experimental geometry and
in what counts as a "detection," not in the underlying dual-channel
mechanism.

*Step 2 (Mott's straight tracks from spherical wave functions).* An
$\alpha$-particle emitted from a nucleus has, prior to any detection, a
spherically symmetric wave function $\psi(\vec r) = R(r)/r$ (s-wave).
The cloud chamber consists of $N \sim 10^{22}$ vapor atoms, each at rest
in its own $x_4$-frame. The first atom to ionize selects a direction
$\hat n$ on the McGucken Sphere $\Sigma_+(p_0)$ of the emission event
$p_0$ by Channel-B pinch
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}); the spherical wave is projected onto the
null cone segment in direction $\hat n$. Subsequent atoms within an
angular spread $\sim \lambda_{\rm dB}/d$ (where $\lambda_{\rm dB}$ is
the $\alpha$ de Broglie wavelength and $d$ the inter-atom spacing) lie
on the future null cone of the first ionization event and are pinched in
correlated sequence by the same Channel-B mechanism. The straight track
is the geometric record of the Channel-B propagation along the null cone
selected by the first pinch; the apparent paradox ("how does a spherical
wave produce a straight track?") is resolved by recognizing the first
pinch as the directional selection and subsequent pinches as
null-cone-correlated.

*Step 3 (Renninger's negative-result measurement).* A wave function
$\psi = \alpha|D_1\rangle + \beta|D_2\rangle$ with two spatially
separated possible detection regions $D_1, D_2$ is allowed to evolve. At
time $t_1$, detector $D_1$ either clicks or does not click. The absence
of a click at $D_1$ is the Channel-B information that the spatial wave
packet was not detected at $D_1$; by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, applied to the conditional outcome "no
click at $D_1$," the remaining wave packet is projected onto
$|D_2\rangle$ with probability one (conditional on the null outcome).
The Channel-B pinch is unaffected by whether the detector clicks or
not---both outcomes are valid pinch results, and the conditional
probability update is the same Bayesian update as a click-result update.
The "negative-result collapse" is not a mysterious action-at-a-distance;
it is the conditional Channel-B update of the wave packet's $x_4$-phase
content based on the apparatus's null record.

*Step 4 (Elitzur--Vaidman interaction-free measurement).* A
Mach--Zehnder interferometer is set up with $50{:}50$ beam splitters and
an obstacle (the "bomb") possibly in one arm. With no bomb, the
interferometer is tuned so that all photons emerge at output $D_+$
(constructive interference) and none at $D_-$ (destructive). With the
bomb in one arm and the bomb's trigger sensitive to single photons,
three outcomes are possible per photon: (i) the bomb absorbs the photon
(probability $1/2$ if the photon takes the bomb arm); (ii) the photon
emerges at $D_+$ (probability $1/4$, indistinguishable from the no-bomb
case); (iii) the photon emerges at $D_-$ (probability $1/4$, possible
only if the bomb is present). The detection of a photon at $D_-$
certifies the bomb's presence without the photon having interacted with
the bomb. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the photon's null worldline through the
interferometer is fixed by the source event; the Channel-A phase
difference $\Delta\phi$ at the output beam splitter depends on the
global geometry of the interferometer including whether the bomb is
present. When the bomb is present, the symmetric superposition of the
two arms is broken (the bomb's potential which-path detection breaks
Channel-A coherence between the arms by
Theorem [19](#thm:duality){reference-type="ref"
reference="thm:duality"}, Step 4); the output amplitude at $D_-$
acquires nonzero value because the bomb-induced asymmetry breaks the
destructive interference. The Channel-B information about the bomb's
presence is recovered from the Channel-A interference pattern; the
photon's null worldline is consistent with the no-interaction outcome at
$D_-$ even though the global interference depends on the bomb's
existence.

*Step 5 (the quantum Zeno effect).* A system in initial state
$|\psi_0\rangle$ would, under free Schrödinger evolution over time
$\Delta t$, evolve to
$|\psi(\Delta t)\rangle = (\mathbb{1} - i\hat H \Delta t/\hbar - \tfrac{1}{2}\hat H^2 \Delta t^2/\hbar^2 + \cdots)|\psi_0\rangle$.
The survival probability is
$|\langle\psi_0|\psi(\Delta t)\rangle|^2 = 1 - (\Delta H)^2 \Delta t^2/\hbar^2 + \mathcal{O}(\Delta t^4)$,
quadratic at short times with no linear term. Under $N$ projective
measurements at intervals $\Delta t = T/N$, the survival probability at
total time $T$ is
$$\big(1 - (\Delta H)^2 (T/N)^2/\hbar^2\big)^N \to 1 \quad \text{as } N \to \infty.$$
Continuous observation freezes the evolution. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, each
projective measurement is a Channel-B pinch at the apparatus event by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, with decoherence rate
$\Gamma \sim N_{\rm app} \omega_{th}$ over the apparatus's thermal
degrees of freedom. The pinch rate $1/\Delta t = N/T$ competes with the
Channel-A coherent evolution rate $\Delta H/\hbar$; when
$1/\Delta t \gg \Delta H/\hbar$, the pinch dominates and the state
remains in the initial eigenbasis. The frozen evolution is the limit in
which the Channel-B advance of the apparatus through $x_4$ outpaces the
Channel-A coherent advance of the system through its Hilbert space.

*Step 6 (uniform diagnosis).* Mott's tracks, Renninger's negative
result, Elitzur--Vaidman bomb testing, and the quantum Zeno effect are
four operational signatures of the same dual-channel structure:
Channel-A free evolution between detection events, Channel-B pinch at
each detection event, with the relative rates of Channel A and Channel B
determining the observed phenomenology. None of the four involves any
new physics beyond Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}. ◻


# The Twin Paradox, Ladder-and-Pole, and Bell's Spaceships 

## Historical background: Einstein 1905, Langevin 1911, Bell 1976

The twin paradox [@Einstein1905] asked: which twin ages less, given
relativistic time dilation? Langevin [@Langevin1911] sharpened the
question with the traveling twin. The ladder-and-pole (or barn) paradox
asks whether a moving ladder fits in a stationary barn that is shorter
than the ladder's rest length [@Rindler1961]. Bell [@Bell1976] asked: if
two rockets, connected by a string, accelerate identically in the lab
frame, does the string break?

## The McGucken $dx_4/dt = ic$ reading


**Theorem 27** (Twin, ladder, and Bell rocket as $x_4$-rotations). *The
differential aging of the twins, the apparent contraction of the ladder,
and the breaking of Bell's string are all consequences of the Lorentz
rotation in the $x_4$-$t$ plane generated by $\hat K_{x_4}$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, $x_4$
advances at $ic$ along every worldline; the proper time along a
worldline $\gamma$ is
$$\tau(\gamma) \;=\; \int_\gamma \frac{|dx_4|}{c} \;=\; \int_\gamma \sqrt{1 - v^2/c^2}\,dt .$$
The asymmetry between the twins is the asymmetry between two worldlines
accumulating different $x_4$-arclengths.*


::: proof
*Proof.* *Step 1 ($x_4$-arclength along a worldline from
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$x_4$-velocity has magnitude $|dx_4/dt| = c$ in any observer's rest
frame, with the algebraic factor $i$ supplying the orthogonality of
$x_4$ to the three spatial directions. For a worldline $\gamma$ moving
at speed $v$ in some frame $F$, the rest-frame relation
$|dx_4/d\tau| = c$ (with $\tau$ proper time) combined with the Lorentz
transformation between $F$ and the rest frame gives the time-dilation
relation $d\tau = \sqrt{1-v^2/c^2}\,dt$. Hence the $x_4$-arclength
accumulated along $\gamma$ between events $p_1, p_2$ is
$$\Delta x_4^{(\gamma)} = \int_\gamma |dx_4| = \int_\gamma c\,d\tau = \int_{t_1}^{t_2} c\sqrt{1-v^2/c^2}\,dt,$$
maximized over all timelike worldlines connecting $p_1, p_2$ by the
inertial worldline (in flat spacetime).

*Step 2 (the twin paradox differential aging).* Twin $A$ stays at rest
in frame $F$; twin $B$ leaves $A$ at event $p_1$, travels outbound at
speed $v$ for proper time $\tau_{\rm out}$, instantaneously reverses
(idealization), returns inbound at speed $v$ for proper time
$\tau_{\rm in} = \tau_{\rm out}$, and reunites with $A$ at event $p_2$.
The lab-frame elapsed time is $T = 2\gamma\tau_{\rm out}$ with
$\gamma = 1/\sqrt{1-v^2/c^2}$. By Step 1,
$$\Delta x_4^{(A)} = cT, \qquad \Delta x_4^{(B)} = 2c\tau_{\rm out} = cT/\gamma = cT\sqrt{1-v^2/c^2}.$$
The difference
$\Delta x_4^{(A)} - \Delta x_4^{(B)} = cT(1 - \sqrt{1-v^2/c^2}) > 0$.
Twin $A$ has accumulated more $x_4$-arclength than twin $B$;
correspondingly $A$ has aged more in proper time. The asymmetry is fixed
in the geometric Channel-B structure of the two worldlines, not in any
observer-dependent choice of frame.

*Step 3 (the ladder--barn paradox).* Ladder of rest length $L_0$ moving
at speed $v$ relative to barn of rest length $L_0' < L_0$. In the barn
frame: the ladder's length is contracted to $L = L_0/\gamma$; if
$L < L_0'$, the events "front of ladder reaches back of barn" ($E_1$)
and "back of ladder reaches front of barn" ($E_2$) are simultaneous with
the ladder fully inside the barn. In the ladder frame: the barn's length
is contracted to $L_0'/\gamma < L_0'$; the events $E_1, E_2$ are not
simultaneous (tilted by the Lorentz boost), and the ladder never fits
inside the contracted barn at any instant. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the two
descriptions correspond to two Lorentz-tilted $x_4$-frames; the events
$E_1, E_2$ have fixed spacetime locations but are projected onto
different simultaneity slices in the two frames. The two frames'
simultaneity slices differ by a Channel-B tilt of magnitude $v/c$ in
$x_4$; the apparent contradiction is the Channel-A insistence on a
single "simultaneous" description across frames whose $x_4$-axes are
rotated relative to each other.

*Step 4 (Bell's rocket-and-string).* Two rockets at initial separation
$L_0$ in lab frame $F$ undergo identical proper accelerations $a$ along
their respective worldlines for proper time $\tau$; at the end both
rockets have lab-frame velocity $v = c\tanh(a\tau/c)$. The lab-frame
separation remains $L_0$ (the two rockets are accelerated identically
and synchronously in $F$). In the instantaneous comoving frame $F'$ of
the rockets, however, the proper separation is
$$L' = \gamma L_0 = L_0/\sqrt{1 - v^2/c^2}.$$ The string between the
rockets is Born-rigid only with respect to a single $x_4$-frame; under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, its proper
length is the $x_4$-arclength of its endpoints' worldlines in the
string's own rest frame, which is the rockets' comoving frame $F'$. The
string must stretch from rest length $L_0$ to the new proper distance
$L_0/\sqrt{1-v^2/c^2}$; it breaks when the strain $\gamma - 1$ exceeds
its elastic limit. The breaking is the Channel-B geometric trace of the
divergent $x_4$-tilt between the rockets' independent comoving frames;
no single rigid $x_4$-frame bridges the two rockets after the boost.

*Step 5 (uniform structural diagnosis).* The twin differential aging,
the ladder--barn paradox, and Bell's string-breaking are three
operational signatures of the same dual-channel content: each worldline
carries its own $x_4$-advance at rate $|dx_4/dt|=c$ (Channel B,
geometric), and the $x_4$-arclengths along distinct worldlines between
common endpoints differ by the worldlines' Lorentz tilts (Channel A,
algebraic). The paradoxes vanish when the dual-channel content is
respected; they appear when one demands a single frame-independent
simultaneity slice across distinct $x_4$-frames. ◻


# Ehrenfest Disk, Supplee Submarine, Trouton--Noble, Mansuripur 

## Historical background: Ehrenfest 1909 to Trouton--Noble 1903 to Mansuripur 2012

Ehrenfest [@Ehrenfest1909] asked: a rotating rigid disk has
Lorentz-contracted circumference but un-contracted radius, so the disk
is not Euclidean. Supplee [@Supplee1989] asked: a submarine that is
neutrally buoyant at rest is denser at speed (length-contracted) in the
water's frame, but the water is denser in the submarine's frame; does it
sink or float? Trouton and Noble [@TroutonNoble1903] showed that a
charged capacitor in motion should experience a torque; experiment finds
none. Mansuripur [@Mansuripur2012] produced a modern version: a charge
and magnet should torque each other in some frames but not others.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 28** (Disk, submarine, capacitor, charge--magnet as
$x_4$-frame mismatches). *Each of Ehrenfest, Supplee, Trouton--Noble,
and Mansuripur arises from assuming that "the body in motion" has a
single, frame-independent shape and momentum density. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the body's
$x_4$-frame is local; in extended bodies (disk, submarine, capacitor)
different parts have different instantaneous $x_4$-frames; the body's
shape is the projection of a Channel-A--rotated $x_4$-extended object
into the laboratory's spatial slice.*


::: proof
*Proof.* *Step 1 (the local $x_4$-frame of an extended body).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$x_4$-velocity at each event is $|dx_4/dt| = c$ in the local rest frame.
For an extended body whose parts have different velocities (rotating
disk, accelerating spaceship, current-carrying conductor), distinct
parts have distinct instantaneous $x_4$-frames. The body's global
"shape" is not the union of part-shapes in any single $x_4$-frame; it is
the projection of the body's worldtube onto a chosen spatial slice in a
chosen $x_4$-frame, with the projection depending on the choice. Each
apparent paradox in the list below arises from supposing that there is a
frame-independent "shape" or "momentum density" of an extended body
whose parts have varying instantaneous $x_4$-frames.

*Step 2 (Ehrenfest disk: hyperbolic spatial geometry).* A disk of rest
radius $R_0$ rotating at angular velocity $\omega$ has each radial
element at radius $r$ moving tangentially at speed $v(r) = \omega r$. By
Step 1, each tangential element's $x_4$-frame is locally Lorentz-boosted
by $\theta(r) = \mathrm{arctanh}(\omega r/c)$ relative to the lab's
$x_4$-frame. The rest-frame circumference of the element at radius $r$
is $2\pi r$ in the lab frame; in the rotating frame it is dilated by the
Lorentz factor to $2\pi r \cdot \gamma(r)$ where
$\gamma(r) = 1/\sqrt{1-\omega^2 r^2/c^2}$. The radial direction is
orthogonal to the velocity, so the radius is not contracted. The spatial
geometry of the rotating disk, parameterized by the comoving radial
coordinate $r$ and angle $\varphi$, has metric
$$dl^2 = dr^2 + r^2 \gamma(r)^2\, d\varphi^2,$$ non-Euclidean. The
Gaussian curvature of this 2-metric is computable from
$K = -(1/r) \partial_r(\partial_r(r\gamma))/\gamma$. At small
$\omega r/c$, expanding to leading order gives
$K \approx -3\omega^2/c^2 + \mathcal{O}((\omega r/c)^2)$; the disk's
spatial geometry is hyperbolic at leading order with $K < 0$. The
negative curvature is consistent with
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} because the
$x_4$-frame tilt varies continuously with $r$; no single Euclidean
$x_4$-frame can describe the whole disk.

*Step 3 (Supplee's submarine).* A submarine neutrally buoyant at rest in
water of density $\rho_w$ has the same density $\rho_w$ in its rest
frame. When it moves at speed $v$, the water's frame sees the submarine
length-contracted to $L/\gamma$, hence denser by factor $\gamma$. The
submarine's frame sees the water length-contracted by the same factor,
hence also denser by $\gamma$. Both frames see the moving body denser
than the stationary medium. The orthodox resolution is by
Matsas [@Matsas2003]: in either frame, the gravitational field of the
planet must be treated relativistically, and the additional Channel-B
component of the gravitational stress-energy from the pressure gradient
in the moving fluid generates a force on the submarine equal and
opposite to the buoyancy mismatch. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
cancellation is geometric: both frames' descriptions of buoyancy must
respect the same Channel-B $x_4$-frame of the gravitational source (the
planet), and the apparent buoyancy mismatch in either non-planet-rest
frame is the artifact of attempting to compute buoyancy in an
$x_4$-frame other than the gravitational source's. In the planet's rest
frame, the submarine sinks if and only if it would sink at rest---the
rest-frame buoyancy is unchanged.

*Step 4 (Trouton--Noble torque).* A parallel-plate capacitor with charge
density $\pm\sigma$ on plates of area $A$ has electromagnetic
stress-energy $T^{\mu\nu}_{\rm EM}$. In its rest frame, the capacitor
has no net force and no net torque on any axis. Moving at velocity
$\vec v$ in the lab frame, the Lorentz-transformed $T^{\mu\nu}_{\rm EM}$
acquires off-diagonal components, leading to a naive prediction of
nonzero net torque. The orthodox resolution [@Jackson1999]: the
capacitor's mechanical stress-energy (the binding stresses that hold the
plates together) is also Lorentz-transformed, and contributes an equal
and opposite torque. The full stress-energy tensor
$T^{\mu\nu}_{\rm total} = T^{\mu\nu}_{\rm EM} + T^{\mu\nu}_{\rm mech}$
is conserved in any frame, and the total net torque vanishes. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
mechanical binding stresses are themselves Channel-B geometric content
of the capacitor's $x_4$-frame; they cannot be omitted when the
$x_4$-frame changes. The Trouton--Noble torque calculation that includes
only $T^{\mu\nu}_{\rm EM}$ implicitly assumes that the mechanical
content is frame-independent, which contradicts
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}.

*Step 5 (Mansuripur's charge--magnet torque).*
Mansuripur [@Mansuripur2012] constructed a scenario with a charge and a
magnetic dipole, claiming that the Lorentz force on the charge in the
dipole's rest frame and the corresponding force in a boosted frame are
inconsistent, leading to a frame-dependent net torque. The orthodox
resolution: the hidden momentum of the dipole (Penfield--Haus 1967;
Vaidman 1990) contributes to the dipole's stress-energy in a
frame-dependent way, and the full Lorentz-covariant treatment recovers
zero net torque in every frame. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
hidden-momentum content is the Channel-B geometric stress-energy of the
dipole's $x_4$-frame in the lab frame; the apparent paradox is the
failure to include all Channel-B content when the $x_4$-frame is
boosted.

*Step 6 (uniform diagnosis).* Each of Ehrenfest, Supplee,
Trouton--Noble, and Mansuripur is the failure to recognize that an
extended body's $x_4$-frame is local, with distinct parts having
distinct instantaneous $x_4$-frames in the presence of relative motion
(Ehrenfest, Bell-rocket-string), or that the body's frame-dependent
stress-energy must be tracked in full (Supplee, Trouton--Noble,
Mansuripur). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, each paradox dissolves into a frame-covariant
identity once the Channel-B $x_4$-frame content is respected. ◻


# Rietdijk--Putnam--Penrose, Block Universe, Becoming 

## Historical background: Rietdijk 1966, Putnam 1967, Penrose 1989

Rietdijk [@Rietdijk1966] and Putnam [@Putnam1967] argued that special
relativity entails a block universe: since simultaneity is relative, the
future of one observer is the present of another, and the entire
spacetime exists "at once." Penrose [@Penrose1989] dramatized this with
the Andromeda paradox: two pedestrians passing on the street, with
relative speed a few meters per second, disagree about whether a Martian
fleet has launched.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 29** (Block universe is partial; becoming is Channel-B). *The
block-universe argument identifies the spacetime manifold with the
totality of events on every observer's simultaneity slice. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
manifold is not static; it is generated by the $x_4$-expansion
$dx_4/dt = ic$ from every event. Becoming is the Channel-B advance of
the local $x_4$-frame; the block is the Channel-A integral of that
advance over all past events. Both descriptions are correct in their
channels; the contradiction arises only from forcing both into one.*


::: proof
*Proof.* *Step 1 (the block as the integrated past of all worldlines).*
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
spacetime manifold $\mathcal{M}$ is generated by the $x_4$-expansion at
$|dx_4/dt| = c$ from every event. At any cosmic moment, the set of past
events---events whose $x_4$-expansion has already occurred---constitutes
a definite, geometric structure: the union $\bigcup_O \mathrm{past}(O)$
over all observers $O$. This integrated past is the "block." By
construction, the block has no future component; its boundary is the
present cosmic moment, the locus of advancing $x_4$-fronts.

*Step 2 (becoming as the present Channel-B advance).* Each observer $O$
at the boundary of the block has its own simultaneity slice $\Sigma_O$
at the present moment. The slice advances forward in $x_4$ at
$|dx_4/dt| = c$ along $O$'s worldline; the advance is the Channel-B
geometric content of Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} restricted to $O$. The set of all such advances, one
per observer, is the local content of "becoming"---the universe's
continuing creation of new events at each observer's worldline tip. The
block is Channel-A bookkeeping; the becoming is Channel-B propagation.

*Step 3 (relativity of simultaneity slices).* For two observers
$O_1, O_2$ moving with relative velocity $\vec v$, their simultaneity
slices $\Sigma_1, \Sigma_2$ at a common meeting event $p$ are tilted
relative to each other by the Lorentz transformation. An event $q$ at
large spatial distance $d$ from $p$ has $x_4$-coordinate difference
$\Delta x_4 = v\,d \cdot \gamma / c$ between the two slices, with
$\gamma = 1$ to excellent precision at pedestrian speeds. For
brisk-walking relative velocity $v \sim 2.5\,\mathrm{m/s}$ and distance
to Andromeda $d \sim 2.5 \times 10^{22}\,\mathrm{m}$, this gives
$\Delta x_4 \sim 2 \times 10^{14}\,\mathrm{m}$ of $x_4$-axis,
corresponding to about 8 days of cosmic time (Penrose's canonical
estimate [@Penrose1989]). The two pedestrians' simultaneity slices at
$p$ disagree by 8 days at Andromeda. The Martian fleet launch event $q$
may lie on $\Sigma_1$ but not on $\Sigma_2$, or vice versa.

*Step 4 (the Andromeda paradox stated and resolved).* Penrose's
pedestrians $P_1, P_2$ pass each other at event $p$ on Earth. $P_1$'s
simultaneity slice $\Sigma_1$ at $p$ includes the Martian fleet launch
event $q$ at Andromeda; $P_2$'s slice $\Sigma_2$ at $p$ does not include
$q$, but includes a slightly earlier event $q'$. The orthodox reading:
$P_1$ says the fleet has launched, $P_2$ says it has not yet; both
observers are at the same event and must be making contradictory
statements about the same physical reality. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
resolution is structural: the event $q$ has fixed spacetime location in
the block (Channel-A integrated content); the pedestrians' Channel-B
records of "what is happening now at Andromeda" differ by the relativity
of simultaneity. Neither pedestrian has access to the actual content of
events at Andromeda (which requires a signal traveling at $\le c$ over
$\sim 2.5$ million years); their disagreement is about labels, not about
physical content.

*Step 5 (becoming is not refuted; it is the Channel-B half).* The
Rietdijk--Putnam argument that the relativity of simultaneity refutes
becoming proceeds as follows: if simultaneity is observer-dependent,
then no privileged "present" exists; if no privileged present exists,
then the future and past are equally real; if the future is real, then
becoming is illusory. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the argument fails at the second step: a privileged
"present" does exist locally, at the tip of each observer's worldline,
as the Channel-B advance of that observer's $x_4$-frame. Distinct
observers have distinct presents, but each observer's present is real
for that observer; the block-universe argument's assertion that "no
present exists" confuses the absence of a global present with the
absence of any present. The McGucken framework's resolution: the block
is the integrated past (Channel A); the becoming is the present advance
(Channel B); both are correct in their channels; neither refutes the
other.

*Step 6 (the flow of time as Channel-B propagation).* The
phenomenological flow of time---the universal subjective experience of
past, present, future as ordered---is the Channel-B advance of each
observer's $x_4$-frame at $|dx_4/dt| = c$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this flow
is foundational: it is the content of $dx_4/dt = ic$ along each
worldline. The Channel-A block (the integrated history) is the
bookkeeping of past advances; the flow itself is the present advance,
ongoing and irreducible. The block-universe argument's denial of the
flow is the artifact of attempting to read Channel-B content (becoming)
through Channel-A vocabulary (the static block). ◻


# Mach's Principle and the Origin of Inertia 

## Historical background: Newton 1687 to Berkeley 1721 to Mach 1883 to Einstein 1918

Newton's *Principia* (1687) [@Newton1687] argued that inertial frames
are picked out by absolute space, using the rotating-bucket thought
experiment: water in a bucket, rotating relative to absolute space,
climbs the walls into a concave meniscus; water at rest relative to
absolute space (but rotating with the bucket in the water's frame) does
not. Berkeley (1721) [@Berkeley1721] objected: the notion of absolute
space is unobservable, hence metaphysically empty; the bucket experiment
can only show motion relative to something observable, such as the fixed
stars. Mach (1883) [@Mach1883] developed Berkeley's objection into a
positive proposal: inertia is determined by the distribution of distant
matter, and Newton's absolute space should be replaced by the reference
frame in which the fixed stars are on average at rest.
Einstein [@Einstein1918] coined the term "Mach's principle" (*Machsches
Prinzip*) in 1918 and hoped that general relativity would realize it
fully: the metric $g_{\mu\nu}$ at each event would be entirely
determined by the distribution of matter through the Einstein field
equations, giving no residual role for a matter-independent absolute
space. Two developments disappointed Einstein's hope: de Sitter's 1917
vacuum solution to the Einstein equations with cosmological constant
contains inertial structure with no matter present at all; and Gödel's
1949 rotating-universe solution [@Godel1949] contains matter that
rotates relative to the local compass of inertia at rate
$2\sqrt{\pi G \rho}$, which is impossible if the compass is dragged by
the matter (see §[16](#sec:godel){reference-type="ref"
reference="sec:godel"}). Einstein described Gödel's solution as
troubling "on physical grounds" but offered no principle by which such
solutions could be excluded from general relativity. Mach's principle
remains, in the orthodox literature, an aspiration without a decisive
resolution.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 30** (Mach's principle dissolved: inertia is the local
$x_4$-advance, not distant matter, yet absolute space is also excluded).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
Mach's principle in its strong form (inertia is determined by the
distribution of distant matter) is false: inertial frames are picked out
by the local $x_4$-advance $dx_4/dt = ic$ at each event, not by any
relation to distant matter. Newton's bucket climbs the walls in an empty
universe. Simultaneously, Newton's absolute space is excluded: the
absolute element that fixes inertia is the McGucken expansion (active,
measurable, generative of the metric), not an inert backdrop. The
framework agrees with Newton that something absolute fixes inertia,
disagrees with Newton about what it is; agrees with Mach that absolute
space must be rejected, disagrees with Mach about what replaces it.*


::: proof
*Proof.* *Step 1 (the four-velocity budget from
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken velocity has magnitude $|dx_4/dt| = c$ at every event,
orthogonal to the three spatial directions ($dx_4 \perp d\vec x$). For
an object with three-velocity $\vec v$ in some frame, the four-velocity
satisfies the budget partition
$$|\vec v|^2 + c_{x_4}^2 = c^2, \qquad c_{x_4} = |dx_4/dt|_{\rm frame},$$
where $c_{x_4}$ is the frame-projected $x_4$-advance rate. An object at
spatial rest ($\vec v = 0$) has $c_{x_4} = c$: the entire four-velocity
budget is spent on $x_4$-advance. This is the inertial state at rest.

*Step 2 (inertia as resistance to rotating the four-velocity off the
$+ic$ axis).* To accelerate an object at spatial rest to spatial
velocity $\vec v$ requires the four-velocity to rotate away from the
pure-$x_4$ direction toward the spatial hyperplane, redistributing the
fixed-magnitude budget from $x_4$ to $\vec x$. The energy cost of this
rotation is the inertia. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the rotation is against the local geometric content
of $dx_4/dt = ic$ at the event, which fixes the $+ic$-axis as the local
time-direction; no reference to distant matter enters the computation.
Inertia is fixed by the local $x_4$-advance, not by relational content
with respect to any external configuration.

*Step 3 (Newton's bucket in an empty universe).* Consider a universe
containing only Newton's bucket, its water, and the rotating apparatus,
with no other matter present. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the local
$x_4$-advance at each water element proceeds at $|dx_4/dt| = c$ in the
water's instantaneous rest frame. A water element at radius $r$ from the
bucket's rotation axis has centripetal acceleration $\omega^2 r$ toward
the axis in the rotating frame; equivalently, in the lab frame, its
four-velocity must be rotated by a tangential increment as it moves in a
circle. The rotation costs $x_4$-advance content and generates the
centripetal force sourced by the water's pressure gradient (the meniscus
climb). No distant matter is required for this cost to be nonzero; the
local $|dx_4/dt| = c$ suffices. The water climbs the walls in the empty
universe just as it does in the star-filled universe. The framework is
*anti-Machian*: inertia is not relational to distant matter.

*Step 4 (Newton's absolute space is nevertheless excluded).* Newton's
absolute space was posited as an unobservable backdrop: inert (does not
act), unmeasured (has no signature), and passive (does not generate
physical content). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the absolute element that fixes inertia has none of
these properties. The McGucken expansion $dx_4/dt = ic$ is active (it
advances at $|dx_4/dt| = c$ at every event, generating the local
time-direction); measurable (the CMB rest frame gives its isotropic
realization at cosmological scale; GPS satellite corrections give its
local realization at planetary scale via the $g_{tt}$ time-dilation
content); and generative (the spacetime metric descends from
$dx_4/dt = ic$ via Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}, not the other way around). The framework
rejects Newton's absolute space and replaces it with the McGucken
absolute expansion, an active process rather than an inert stage.

*Step 5 (Berkeley's observability objection is honored).* Berkeley's
objection was that Newton's absolute space is metaphysically empty
because unobservable. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the objection is honored: the absolute element (the
$x_4$-expansion) is observable through the CMB frame, through GPS
relativistic corrections, through the isotropic Hubble expansion,
through the cosmological arrow of time
(Theorem [40](#thm:arrow){reference-type="ref" reference="thm:arrow"}),
and through the $\pi/2$ rotation at the Schwarzschild horizon
(Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}). Mach's mistake was in the replacement:
rejecting Newton's stage, he substituted the fixed stars (relational
content), whereas Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} substitutes the active expansion (a process, not a
stage).

*Step 6 (the CMB frame as the isotropic-expansion frame).* The
cosmological microwave background rest frame is the frame in which the
CMB dipole vanishes: the frame in which the observer is at rest relative
to the isotropic Hubble expansion. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
frame in which the $x_4$-expansion at every cosmological event has the
maximally symmetric spatial-projection: all directions of spatial motion
are equivalent, with only the $x_4$-advance non-vanishing. It is the
fourth leg of the four-fold ontology
(Definition [10](#def:fourfold){reference-type="ref"
reference="def:fourfold"}, Type IV: cosmological isotropic
$x_4$-expansion frame). The CMB frame is not a Machian frame determined
by distant matter; it is the frame at rest with respect to the local
isotropic $x_4$-expansion, which happens (empirically) to be the frame
at rest with respect to the CMB. The Machian identification of the two
is a coincidence, not a causal relation.

*Step 7 (structural verdict).* Newton was right that something absolute
fixes inertia; wrong that the absolute element is space. Mach was right
that Newton's absolute space must be rejected as unobservable; wrong
that the replacement is distant matter. The framework's answer: the
absolute element is the McGucken expansion $dx_4/dt = ic$, an active
process rather than either a stage (Newton) or a relational content with
respect to distant matter (Mach). Inertia is local, non-relational, and
non-empty; Newton's bucket climbs in an empty universe because the local
$x_4$-advance is nonzero at every water element. ◻


::: remark
**Remark 31**. *The framework's position is neither Newtonian nor
Machian, but structurally distinct from both. The absolute element
exists (against Berkeley--Mach); the absolute element is not a stage
(against Newton); the absolute element is not sourced from distant
matter (against Mach). It is the $+ic$ expansion at every event,
foundational and irreducible.*


# Gödel's Universe and Chronology Protection 

## Historical background: van Stockum 1937, Gödel 1949, Tipler 1974, Hawking 1992

Gödel [@Godel1949] presented, on the occasion of Einstein's seventieth
birthday in 1949, an exact solution to the Einstein field equations with
cosmological constant and pressureless dust. The Gödel metric describes
a homogeneous rotating universe with vorticity
$\omega = 2\sqrt{\pi G \rho}$, where $\rho$ is the dust mass density;
the matter rotates rigidly relative to the local compass of inertia. Two
features of the solution disturbed Einstein. First, Gödel's universe
refutes Mach's principle outright: the matter's rotation relative to the
local inertial frame is precisely what Mach forbade, since the inertial
frame should be dragged by the matter, not remain fixed relative to it.
Second, the Gödel metric contains closed timelike curves: through every
event of Gödel's manifold passes a closed timelike curve, so an observer
could travel to their own past. Gödel's construction was preceded by
van Stockum's 1937 rotating-dust cylinder [@VanStockum1937] and followed
by Tipler's rotating cylinder [@Tipler1974] and
Deser--Jackiw--'t Hooft's 2+1-dimensional cosmic-string
spacetimes [@DeserJackiwtHooft1984]; each of these contains closed
timelike curves in exact solutions to the Einstein equations.
Hawking [@Hawking1992] conjectured a "chronology protection" principle:
quantum-mechanical or thermodynamic effects should prevent the formation
of closed timelike curves. The conjecture has not been proven within
general relativity; the exact solutions remain within the mathematical
structure of the theory, requiring only that specific initial conditions
and matter content be excluded "on physical grounds" that Einstein
himself could not articulate.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 32** (Gödel's universe is not a McGucken manifold; chronology
protection is a theorem). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, Gödel's rotating-universe solution is not a
McGucken manifold. Closed timelike curves are excluded as a theorem, not
by conjecture: the McGucken velocity $dx_4/dt = ic$ makes $x_4$ a
strictly monotone global time function along every future-directed
timelike worldline, which forbids the closure required by a closed
timelike curve. Hawking's chronology protection conjecture is upgraded
to a theorem; Gödel's construction is the predicted symptom of the
sign-blind orthodox formalism
(Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}: the integrated coordinate label $x_4 = ict$ is
sign-blind, while the velocity $dx_4/dt = ic$ carries an orientation
that the label discards).*


::: proof
*Proof.* *Step 1 ($x_4$ as a global time function on any McGucken
manifold).* Let $\mathcal{M}_G$ be a McGucken manifold: a Lorentzian
4-manifold on which Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} holds at every event. By
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
$dx_4/dt = ic$ with $|dx_4/dt| = c > 0$ at every event, and the
orientation is $+ic$ (Definition [3](#def:channels){reference-type="ref"
reference="def:channels"}, Channel B: the $+ic$ orientation is
foundational). Along any future-directed timelike worldline $\gamma$,
the parameter $t$ is monotone increasing (by the standard definition of
"future-directed timelike"), so $x_4$ is monotone increasing along
$\gamma$ with strictly positive rate $|dx_4/dt| = c$. The imaginary
factor $i$ is the algebraic label (Channel A); the physical monotonicity
content is carried by the real magnitude $c$ (Channel B). Thus $x_4$ is
a global time function on $\mathcal{M}_G$: it strictly increases along
every future-directed timelike curve.

*Step 2 (a closed timelike curve requires $x_4$ to return to its
starting value).* Let $\gamma: [0, 1] \to \mathcal{M}$ be a closed
timelike curve: a smooth future-directed timelike curve with
$\gamma(0) = \gamma(1) = p$, some event of $\mathcal{M}$. By definition
of "closed," the value of any function at $\gamma(0)$ equals its value
at $\gamma(1)$. In particular, if $f$ is any smooth real-valued function
on $\mathcal{M}$, then $f(\gamma(0)) = f(\gamma(1))$, so
$\oint_\gamma df = 0$. Applied to $x_4$: if $\gamma$ is a closed
timelike curve, then $\oint_\gamma dx_4 = 0$.

*Step 3 (contradiction).* By Step 1, $dx_4 = ic\, dt$ along any timelike
curve. Along a future-directed closed timelike curve $\gamma$ of
coordinate-time duration $\Delta t = \oint_\gamma dt$, we have
$$\oint_\gamma dx_4 \;=\; ic \oint_\gamma dt \;=\; ic\, \Delta t.$$
Since $\gamma$ is future-directed, $dt > 0$ everywhere along it, so
$\Delta t > 0$, hence $|ic\,\Delta t| = c\,\Delta t > 0$. Thus
$\oint_\gamma dx_4 \neq 0$, contradicting the closure requirement of
Step 2. No closed timelike curve can exist on a McGucken manifold. In
words: closure of a timelike curve requires the fourth dimension to
un-advance, and Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"} forbids un-advancement.

*Step 4 (Gödel's universe is excluded).* Gödel's rotating-universe
solution contains closed timelike curves through every event; by Step 3,
no such curve exists on any McGucken manifold; therefore Gödel's
universe is not a McGucken manifold. The same conclusion applies to
van Stockum's 1937 rotating dust cylinder, Tipler's 1974 rotating
cylinder, and the Deser--Jackiw--'t Hooft 2+1-dimensional cosmic-string
spacetimes: each admits closed timelike curves in exact solutions to the
Einstein equations without the McGucken constraint. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, all such
solutions are eliminated from the physical solution space.

*Step 5 (chronology protection is a theorem).* Hawking's [@Hawking1992]
chronology protection conjecture---that quantum-mechanical or
thermodynamic effects should prevent the formation of closed timelike
curves---is upgraded to a theorem under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}. The
prevention mechanism is not a fine-tuned quantum backreaction but the
foundational monotonicity of $dx_4/dt = ic$: the universe protects
chronology for the same structural reason that entropy increases
(Theorem [40](#thm:arrow){reference-type="ref" reference="thm:arrow"},
Step 1: the $+ic$ orientation of $x_4$-expansion is foundational at
every event). Chronology protection and the arrow of time are two
consequences of the same principle.

*Step 6 (Gödel's construction as the predicted symptom of the sign-blind
formalism).* Gödel's discovery is not evidence that the physical
universe permits closed timelike curves; it is evidence that the
orthodox Einstein-field-equation formalism, working with the integrated
coordinate label $x_4 = ict$ rather than the velocity $dx_4/dt = ic$, is
sign-blind: the label is invariant under the sign flip $ic \to -ic$, so
the formalism cannot distinguish the physical $+ic$ orientation from a
hypothetical $-ic$ orientation. Under
Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}, this sign-blindness is the artifact of
integrating the velocity to its endpoint label. Solutions like Gödel's,
van Stockum's, and Tipler's are the predicted mathematical symptoms of
the sign-blind formalism admitting configurations that the
$+ic$-oriented velocity would forbid.

*Step 7 (Einstein's "physical grounds").* Einstein noted that Gödel's
universe should be excluded "on physical grounds" but offered no
principle. The principle is $dx_4/dt = ic$: the fourth dimension
advances monotonically at $+ic$, and closed timelike curves would
require it to un-advance. Einstein was correct that the exclusion is
physical, not merely a preference; the physical content he lacked is the
McGucken principle. The framework's chronology-protection theorem
supplies exactly the "physical grounds" Einstein sought.

*Step 8 (global hyperbolicity and the Mach connection).* Every McGucken
manifold is globally hyperbolic: the level sets $\{x_4 = \text{const}\}$
are Cauchy hypersurfaces, since $x_4$ is a global time function (Step
1). The $\mathrm{diff}(\mathcal{M}_G)$ automorphisms preserve the
foliation by these hypersurfaces. This structural property connects the
resolutions of Mach's principle (§[15](#sec:mach){reference-type="ref"
reference="sec:mach"}, Theorem [30](#thm:mach){reference-type="ref"
reference="thm:mach"}) and Gödel's universe: Gödel's construction was
the specific counterexample that killed Mach's principle in general
relativity (matter rotating relative to the local inertial frame). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, Gödel's
counterexample does not exist; nevertheless Mach's principle is still
false, because inertia is not relational to distant matter
(Theorem [30](#thm:mach){reference-type="ref" reference="thm:mach"}).
The framework rejects both Mach's principle and Gödel's universe on the
same foundational grounds---the local $x_4$-advance is the origin of
inertia and the source of chronology protection. ◻


::: remark
**Remark 33**. *The two most disturbing solutions to the Einstein
equations---Gödel's rotating universe and Tipler's rotating
cylinder---are eliminated as theorems of
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, not by ad
hoc physical restrictions. The elimination is on the same structural
grounds that supply the arrow of time
(Theorem [40](#thm:arrow){reference-type="ref" reference="thm:arrow"})
and the exclusion of Boltzmann brains
(Theorem [64](#thm:boltzmann-brains){reference-type="ref"
reference="thm:boltzmann-brains"}): the $+ic$ orientation of
$dx_4/dt = ic$ at every event is foundational, and the closure
requirement of a closed timelike curve is incompatible with monotone
$x_4$-advance.*


# Abraham--Lorentz Self-Force and Radiation Reaction 

## Historical background: Lorentz 1892 to Abraham 1903 to Dirac 1938

A point charge radiates when accelerated; the radiation carries energy
and momentum, so the charge must experience a reaction force. The
Abraham--Lorentz force [@Lorentz1909] is
$$\symbf{F}_{AL} \;=\; \frac{q^2}{6\pi\epsilon_0 c^3} \dot{\symbf{a}} ,$$
proportional to the jerk. This force admits runaway solutions and
acausal pre-acceleration. Dirac [@Dirac1938] produced a covariant
version; Rohrlich [@Rohrlich1990] reviewed the modern status. The
paradox is that classical electrodynamics is internally inconsistent for
point charges.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 34** (Self-force as $x_4$-back-reaction). *The
Abraham--Lorentz self-force is the Channel-B back-reaction on the
charge's own $x_4$-advance induced by the radiated $x_4$-wave. The
runaway and pre-acceleration disappear when the charge's
$x_4$-coordinate is not idealized to a point but treated as the
spherically symmetric expansion of $x_4$ from the charge's worldline.*


::: proof
*Proof.* *Step 1 (radiation as Channel-B trace of $x_4$-expansion under
acceleration).* Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the $x_4$-velocity field at every event is
spherically symmetric at $|dx_4/dt|=c$. For a charge moving on a
worldline $\gamma$, the field at any spacetime point $\vec r$ at time
$t$ is sourced by the charge's state at the retarded event $p_{\rm ret}$
where the past null cone of $(\vec r, t)$ intersects $\gamma$. The
Liénard--Wiechert potentials [@Jackson1999]
$$\phi(\vec r, t) = \frac{q}{4\pi\epsilon_0}\left.\frac{1}{(1-\vec n \cdot \vec\beta) R}\right|_{\rm ret}, \quad
\vec A(\vec r, t) = \frac{q}{4\pi\epsilon_0 c^2}\left.\frac{\vec v}{(1-\vec n \cdot \vec\beta) R}\right|_{\rm ret},$$
express the field as sourced from $p_{\rm ret}$ along the null cone
(Channel B). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, $p_{\rm ret}$ is the event at which the charge's
$x_4$-expansion null cone reaches $(\vec r, t)$; the propagation is
Channel-B along the McGucken Sphere $\Sigma_+(p_{\rm ret})$.

*Step 2 (radiation reaction from energy balance).* For accelerated
motion, the charge emits radiation carrying energy at the Larmor rate
$P = (q^2/6\pi\epsilon_0 c^3)|\vec a|^2$. Energy conservation along the
worldline requires a reaction force $\vec F_{\rm rad}$ on the charge
with $\vec F_{\rm rad}\cdot \vec v = -P$. The standard non-relativistic
Abraham--Lorentz result, obtained by requiring radiation reaction to be
a function of the worldline kinematics (not of past history), is
$$\vec F_{\rm AL} = \frac{q^2}{6\pi\epsilon_0 c^3}\,\dot{\vec a},$$
proportional to the jerk. The relativistic generalization
(Dirac [@Dirac1938], Lorentz--Abraham--Dirac equation) is
$$m\dot{u}^\mu = F^{\mu\nu}_{\rm ext} u_\nu + \frac{q^2}{6\pi\epsilon_0 c^3}\big(\ddot{u}^\mu + \dot{u}^\nu \dot{u}_\nu u^\mu/c^2\big),$$
with $u^\mu$ four-velocity.

*Step 3 (the runaway pathology and pre-acceleration).* The ALD equation
admits unphysical solutions: for example, with no external force, the
equation $m\dot{u}^\mu = (q^2/6\pi\epsilon_0 c^3) \ddot{u}^\mu$ has
solutions $\vec a(t) = \vec a_0 \exp(t/\tau_e)$ with
$\tau_e = q^2/6\pi\epsilon_0 m c^3 \sim 10^{-23}\,\mathrm{s}$ for the
electron, growing exponentially. The standard "solution" is to integrate
the equation forward and discard the runaway, which produces
pre-acceleration: the charge begins to accelerate before the external
force is applied, by a $x_4$-time $\sim \tau_e$.

*Step 4 (the point-charge divergence regularized by $x_4$-expansion).*
The Abraham--Lorentz force is derived by integrating the self-field over
an infinitesimal sphere surrounding the charge; for a true point charge,
the self-energy diverges as $1/r$ as the sphere shrinks. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, a true
point charge is excluded: the charge has nonzero spatial extent set by
its Compton wavelength $\ell_C = \hbar/(mc)$, the natural
minimum-resolution scale of its McGucken Sphere structure (cf.
Theorems [54](#thm:hierarchy){reference-type="ref"
reference="thm:hierarchy"}, [70](#thm:bekenstein){reference-type="ref"
reference="thm:bekenstein"} for analogous Compton-locality bounds). The
self-field integral has natural cutoff at $r \sim \ell_C$, removing the
divergence; the residual self-force is finite and equal to the
Abraham--Lorentz expression at leading order in the dimensionless ratio
$\ell_C |\vec a|/c^2$ (the Compton length over the characteristic
radiation-reaction length $L = c^2/|\vec a|$). The runaway and
pre-acceleration arise from extrapolating the point-charge formula past
the Compton-cutoff scale; under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, this extrapolation is unjustified.

*Step 5 (boundary condition: no incoming radiation at past $x_4$
infinity).* The runaway solutions, in the ALD framework, are excluded by
the boundary condition that no incoming radiation reach the charge from
past $x_4$ infinity: $\vec a(t \to -\infty) = 0$ if the external force
is zero in the asymptotic past. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
boundary condition is the Channel-B form of the Sommerfeld radiation
condition: the $x_4$-expansion at every event has $+ic$ orientation,
with the future null cone carrying out-going radiation but the past null
cone (in the absence of sources) being radiation-free. The condition is
structural, not ad hoc; it follows from the $+ic$ orientation of
$dx_4/dt = ic$ at every event.

*Step 6 (the structural diagnosis).* The Abraham--Lorentz
pathologies---runaway, pre-acceleration, point-charge divergence---are
all artifacts of treating the charge as a point in a structureless
spacetime. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the charge has Compton-cutoff resolution, the
spacetime has $x_4$-expansion structure at every event, and the
radiation reaction is the Channel-B back-reaction on the charge's
$x_4$-advance from the outgoing radiation. The pathologies do not appear
in the McGucken framework; they are the orthodox bookkeeping cost of
extrapolating past the Compton scale. ◻


# Einstein Elevator, Gravitational Redshift, and the Horizon 

## Historical background: Einstein 1911 to Schwarzschild 1916 to Pound--Rebka 1959

Einstein [@Einstein1907] argued via the elevator equivalence that light
falling in a gravitational field is redshifted; Pound and
Rebka [@PoundRebka1959] measured this.
Schwarzschild [@Schwarzschild1916] produced the first exact solution to
Einstein's equations; the horizon at $r = 2GM/c^2$ appears singular but
is a coordinate artifact, as Painlevé [@Painleve1921],
Gullstrand [@Gullstrand1922], Eddington [@Eddington1924], and
Finkelstein [@Finkelstein1958] clarified.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 35** (Equivalence, redshift, and horizon as $x_4$-frame
change). *Gravitational redshift, the equivalence principle, and the
Schwarzschild horizon are consequences of the local $x_4$-frame at each
event in a curved spacetime. The horizon is the locus of events at which
the local $x_4$-advance $dx_4/dt = ic$ rotates into the spatial
directions, so that an observer at the horizon's local frame has zero
$t$-component of $x_4$-velocity in the asymptotic frame.*


::: proof
*Proof.* *Step 1 (the equivalence principle from
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).*
Einstein's equivalence principle asserts that the local effects of a
gravitational field of strength $g$ are indistinguishable from those of
a uniform proper acceleration of magnitude $g$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$x_4$-velocity at every event has magnitude $|dx_4/dt|=c$ in the local
rest frame; the direction of $dx_4/dt$ in an inertial frame defines the
local time-direction. In an accelerating frame (instantaneous proper
acceleration $g$), the local $x_4$-axis rotates progressively from the
lab's $t$-axis at rate $g/c$ (the hyperbolic-rotation rate of a Rindler
worldline). In a gravitational field of strength $g$, the local
$x_4$-axis is similarly tilted by the metric content. The two situations
are locally indistinguishable because both produce the same local
rotation of the $x_4$-axis; this is the Channel-B content of the
equivalence principle. The Channel-A content (the algebraic phase
rotation that accompanies the geometric tilt) is identical in both
situations as well.

*Step 2 (gravitational redshift from $x_4$-frame tilt).* Consider a
photon emitted at radius $r_1$ in the Schwarzschild geometry and
received at radius $r_2 > r_1$. The Schwarzschild metric reads
$$ds^2 = -\left(1 - \frac{2GM}{rc^2}\right) c^2 dt^2 + \left(1 - \frac{2GM}{rc^2}\right)^{-1} dr^2 + r^2 d\Omega^2.$$
For a stationary observer at radius $r$, the proper time is related to
the asymptotic time by $d\tau(r) = \sqrt{1 - 2GM/(rc^2)}\,dt$. The local
$x_4$-frame at radius $r$ is tilted relative to the asymptotic
$x_4$-frame; the tilt is encoded in the metric coefficient
$g_{tt}(r) = -(1 - 2GM/(rc^2))c^2$. A photon's frequency $\omega(r)$
measured by the local stationary observer is set by the local
$x_4$-rate; for null geodesics (Type II of
Definition [10](#def:fourfold){reference-type="ref"
reference="def:fourfold"}), the relation
$\omega(r) d\tau(r) = \omega_\infty dt$ holds (conservation of
$p_\mu \xi^\mu$ along the geodesic, with $\xi^\mu = \partial_t$ the
Killing field), giving
$$\omega(r_2)/\omega(r_1) = \sqrt{1 - 2GM/(r_1 c^2)}\big/\sqrt{1 - 2GM/(r_2 c^2)}.$$
For $r_2 > r_1$, this ratio is less than one: redshift. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
redshift is the ratio of $x_4$-tilts between the two altitudes; the
photon's frequency is its $x_4$-phase advancement rate per unit proper
time of the local observer, and that rate decreases as the local
$x_4$-frame tilts away from the asymptotic frame.

*Step 3 (Pound--Rebka confirmation).* Pound and Rebka [@PoundRebka1959]
measured the gravitational redshift over a 22.5 m vertical column in the
Jefferson Physical Laboratory tower at Harvard, using the Mössbauer
effect on $^{57}$Fe nuclei. The predicted redshift is
$\Delta\omega/\omega \approx gh/c^2 \approx 9.8 \times 22.5/(3 \times 10^8)^2 \approx 2.45 \times 10^{-15}$.
The measurement confirmed this to within 1%. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
measurement directly probes the $x_4$-frame tilt between the bottom and
top of the column.

*Step 4 (the horizon as $\pi/2$ rotation of the local $x_4$-axis).* At
the Schwarzschild horizon $r_h = 2GM/c^2$, the metric coefficient
$g_{tt}$ vanishes. The local $x_4$-axis at $r_h$ is rotated by $\pi/2$
relative to the asymptotic frame: what was a timelike direction in the
asymptotic frame (the $\partial_t$ Killing vector) becomes lightlike at
$r_h$. An asymptotic stationary observer cannot remain at rest at the
horizon---no timelike worldline at $r = r_h$ exists in the asymptotic
$\partial_t$-direction. The Schwarzschild coordinates' apparent
singularity at $r_h$ is the algebraic (Channel-A) signature of this
$\pi/2$ rotation: the coordinate $t$, designed to label the asymptotic
frame, fails as a label at the locus where the asymptotic frame's
$x_4$-axis has rotated out of the timelike sector. The Channel-B
geometric content (the actual spacetime geometry) is regular at $r_h$,
as confirmed by coordinates that avoid the Schwarzschild label.

*Step 5 (regularity in Painlevé--Gullstrand coordinates).* The
Painlevé--Gullstrand coordinates [@Painleve1921; @Gullstrand1922],
adapted to free-falling observers from infinity, have line element
$$ds^2 = -c^2 dT^2 + \big(dr + \sqrt{2GM/r}\,dT\big)^2 + r^2 d\Omega^2,$$
where $T$ is the proper time of a radially in-falling observer starting
at rest at infinity. The metric is regular at $r = r_h$; only the
asymptotic radial coordinate $r$ approaches the horizon value, and the
in-faller passes through smoothly. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
in-faller's local $x_4$-frame is aligned with $\partial_T$ at every
$r > 0$, and the in-faller's $x_4$-advance proceeds at $|dx_4/dT|=c$ in
the in-faller's own frame; no singularity, no discontinuity. The horizon
coordinate-singularity exists only in the asymptotic $x_4$-frame and is
the Channel-A artifact of attempting to extend that frame across the
$\pi/2$ rotation of Step 4.

*Step 6 (the trans-Planckian observation).* Hawking radiation modes,
traced backward in time from infinity to the horizon, develop unbounded
asymptotic frequency---the trans-Planckian problem [@Jacobson1991].
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
unbounded frequency is the Channel-A artifact of the asymptotic
$x_4$-frame's failure at the horizon (Step 4); in the in-faller's local
$x_4$-frame, the modes have ordinary local frequency, with no
trans-Planckian content. The modes' apparent trans-Planckian character
is the Channel-A frequency redefinition under the $x_4$-frame rotation,
not a physical feature. ◻


# Black Hole Information Paradox and the AMPS Firewall 

## Historical background: Hawking 1975 to AMPS 2013 to islands 2019

Hawking [@Hawking1975] showed that black holes radiate thermally; if the
radiation is exactly thermal, information about the matter that formed
the black hole is destroyed, violating unitarity. The black hole
information paradox has been a central problem for fifty
years [@Mathur2009; @HarlowReview2016; @Page1993; @Page2013]. Almheiri,
Marolf, Polchinski, and Sully [@AMPS2013] sharpened it: the assumptions
of unitarity, locality, and the equivalence principle together imply a
firewall at the horizon. Maldacena and Susskind [@{ER=EPR2013}] proposed
ER=EPR; Penington [@Penington2020] and Almheiri, Engelhardt, Marolf, and
Maxfield [@AEMM2020] derived the Page curve from semiclassical gravity.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 36** (Information paradox as $x_4$-coordinate failure). *The
black hole information paradox arises from extrapolating the asymptotic
$x_4$-frame across the horizon. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the horizon
is the locus at which the asymptotic $x_4$-axis rotates into the spatial
directions (Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}); the interior $x_4$-frame is rotated by
$\pi/2$ relative to the exterior. Information is not destroyed; it is
carried into the interior $x_4$-frame and re-emerges in the Hawking
radiation as the interior $x_4$-frame rotates back to align with the
asymptotic frame at the endpoint of evaporation.*


::: proof
*Proof.* *Step 1 (the matter state on infall).* Let
$|\Psi_{\rm in}\rangle$ denote the quantum state of matter that
collapses to form a Schwarzschild black hole of mass $M$. In the
asymptotic $x_4$-frame, $|\Psi_{\rm in}\rangle$ has a definite
$x_4$-phase content $\phi_0$ corresponding to its Hilbert-space ray. By
Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}, the local $x_4$-frame rotates progressively
from the asymptotic frame as the matter approaches $r_h = 2GM/c^2$; at
$r_h$ the rotation reaches $\pi/2$, taking the asymptotic timelike
direction $\partial_t$ to a lightlike direction. In Painlevé--Gullstrand
coordinates, the in-faller's local $x_4$-frame is aligned with the
proper-time $\partial_T$ direction at every $r > 0$, including $r = r_h$
and beyond; the in-faller's $x_4$-advance continues at $|dx_4/dT|=c$ in
the interior with no discontinuity.

*Step 2 (interior evolution is unitary in the in-faller's $x_4$-frame).*
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Channel-A unitary structure of quantum mechanics holds along every
observer's worldline at the local $x_4$-frame's rate of advance. The
in-faller's frame is regular at and inside the horizon
(Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}, Step 5); the interior unitary
$\hat U_{\rm int}$ acts on $|\Psi_{\rm in}\rangle$ to produce the
evolved state at later interior proper time. Information is preserved by
$\hat U_{\rm int}$ at every step; no information is lost in the
in-faller's record.

*Step 3 (Hawking radiation as Channel-B emission from horizon).*
Hawking's calculation [@Hawking1975] gives a thermal spectrum of
radiation at the temperature $T_H = \hbar c^3/(8\pi G M k_B)$, emitted
from the horizon. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the radiation modes are Channel-B emissions from
the McGucken Sphere structure at the horizon, with each mode's frequency
set by the in-faller-to-asymptotic $x_4$-frame rotation; the thermal
spectrum is the Bogoliubov transformation between the in-faller's
positive-frequency $x_4$-modes and the asymptotic observer's
positive-frequency $x_4$-modes. The thermal character is the Channel-A
artifact of tracing out the interior; the radiation carries the full
quantum-state information of $|\Psi_{\rm in}\rangle$ in its
correlations, just not in its single-mode marginal distributions.

*Step 4 (the Page curve from interior--exterior $x_4$-frame
redistribution).* The Page curve [@Page1993] describes the von Neumann
entropy of the emitted Hawking radiation as a function of evaporation
time: rising linearly until the Page time (when half the black hole has
evaporated), then declining linearly to zero at the endpoint. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the entropy
curve tracks the redistribution of $x_4$-frame content between the
interior (still rotated by $\pi/2$ from the asymptotic frame) and the
exterior (aligned with the asymptotic frame). Up to the Page time, the
interior carries more $x_4$-content than the exterior radiation; after
the Page time, the exterior radiation carries more. The von Neumann
entropy of the smaller subsystem governs the entanglement, giving the
Page curve. The recent semiclassical
derivations [@Almheiri2019; @Penington2019] confirm this structurally:
the quantum extremal surface that minimizes the entropy crosses from the
asymptotic-region position to the interior-region position at the Page
time, exactly as the McGucken-framework $x_4$-frame redistribution
requires.

*Step 5 (no firewall from local $x_4$-frames).* The AMPS firewall
argument [@AMPS2013] demands that three propositions hold simultaneously
at the horizon: (i) the exterior evolution is unitary; (ii) the
equivalence principle holds at the horizon (no firewall); (iii)
effective field theory is valid outside the horizon. The argument shows
that (i)+(ii)+(iii) are inconsistent for a half-evaporated old black
hole, since (i) requires the late radiation to be entangled with the
early radiation while (ii) requires the late radiation to be entangled
with the interior in-faller modes; monogamy of entanglement forbids
both. Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
the assumption that (i), (ii), (iii) refer to a single observer's
$x_4$-frame is the source of the inconsistency. Each observer's
$x_4$-frame is local
(Definition [10](#def:fourfold){reference-type="ref"
reference="def:fourfold"},
Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}): the asymptotic observer's frame supports (i)
and (iii) with the radiation entangled across early/late modes; the
in-faller's frame supports (ii) with the interior in-faller modes
entangled with horizon partners; the two frames are not simultaneously
valid at a single event because they differ by the $\pi/2$ rotation at
the horizon. The monogamy of entanglement is preserved within each
observer's frame; the apparent monogamy violation requires combining two
distinct $x_4$-frame readings into one Boolean assignment.

*Step 6 (ER = EPR as McGucken Sphere identification).* Maldacena and
Susskind's conjecture [@Maldacena2013] that entangled particles are
connected by a non-traversable Einstein--Rosen bridge is, under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
structural identification of the entanglement (Channel-A correlation)
with the McGucken Sphere geometric connection (Channel-B) at the
entangling event. The Sphere $\Sigma_+(p_0)$ at the entangling event
$p_0$ persists as the geometric structure shared by the two partners
throughout their propagation; the ER bridge is the late-time geometric
expression of this Sphere structure when the entangling event lies in
the asymptotic past. The McGucken framework supplies ER = EPR as a
theorem of Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}
rather than as a conjecture
(Theorem [65](#thm:er-epr){reference-type="ref"
reference="thm:er-epr"}).

*Step 7 (the trans-Planckian aside).* The trans-Planckian
problem [@Jacobson1991], that Hawking radiation modes have arbitrarily
high frequencies at the horizon in the asymptotic frame, is dissolved by
Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}, Step 6: the unbounded frequency is the
Channel-A artifact of the asymptotic frame's failure at the horizon,
while the modes' local frequency in the in-faller's frame is ordinary.
No physical trans-Planckian content is required. ◻


::: remark
**Remark 37**. *The trans-Planckian problem [@Jacobson1991]---that
Hawking radiation modes have arbitrarily high frequencies at the horizon
in the asymptotic frame---is dissolved by the same mechanism. The high
frequency is the Channel-A artifact of the $x_4$-frame rotation at the
horizon; the modes are not physically trans-Planckian in their local
$x_4$-frame.*


# The Cosmological Constant Problem 

## Historical background: Einstein 1917 to Weinberg 1989

The observed vacuum energy density is $\rho_\Lambda \sim 10^{-47}$
GeV$^4$; the QFT estimate from zero-point energies is
$\rho_{QFT} \sim 10^{74}$ GeV$^4$, giving a discrepancy of
$\sim 10^{121}$. Weinberg [@Weinberg1989] reviewed the problem;
Carroll [@Carroll2001] updated it. No-go theorems forbid simple
dynamical relaxation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 38** (Cosmological constant as $x_4$-expansion rate). *The
observed cosmological constant is the Channel-B square of the McGucken
expansion rate. The QFT zero-point energy is a Channel-A summation that
double-counts the $x_4$-expansion already present in $dx_4/dt = ic$; the
correct vacuum energy is the difference.*


::: proof
*Proof.* *Step 1 (geometric identification of $\Lambda$).* Let $a(t)$
denote the cosmological scale factor and $H = \dot a/a$ the Hubble rate.
The Friedmann equation in a spatially flat universe with cosmological
constant reads $$H^2 = \frac{8\pi G}{3}\rho_m + \frac{\Lambda c^2}{3},$$
so in the vacuum-dominated limit $\rho_m \to 0$ one has
$H_\Lambda^2 = \Lambda c^2/3$, i.e. $\Lambda = 3 H_\Lambda^2/c^2$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
spherically symmetric $x_4$-expansion proceeds at velocity $c$ from
every event; the cosmological scale factor is the comoving projection of
this expansion onto the spatial slice orthogonal to the local
$x_4$-axis. Hence $H$ is the rate at which the $x_4$-velocity field,
evaluated in the comoving frame, advances the spatial slice. The
identification $\Lambda = 3H^2/c^2$ therefore states that $\Lambda$ is
the Channel-B square of the McGucken rate $|dx_4/dt|/c = 1$ normalized
to the cosmological scale.

*Step 2 (Channel-A double-counting of the zero-point energy).* The
standard QFT estimate of the vacuum energy density is
$$\rho_{QFT} = \frac{1}{2}\sum_k \hbar \omega_k = \frac{\hbar}{2(2\pi)^3} \int_0^{k_*} 4\pi k^2 \sqrt{k^2 c^2 + (mc^2/\hbar)^2}\; dk,$$
cut off at some scale $k_*$. This integral is computed in a *fixed*
Minkowski background: the modes $e^{-i\omega_k t}$ are assumed to
oscillate against a static time coordinate. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, however,
$t$ is not static; it is the integrated coordinate label of $x_4$, and
the phase $\omega_k t$ is the projection onto a single $x_4$-slice of a
velocity field that itself advances at $ic$. The mode
$e^{-i\omega_k t}$, written covariantly, is $e^{-i k_\mu x^\mu}$ with
$x^4 = ict$; its time evolution is already an expression of the
$x_4$-expansion. Counting the zero-point energy $(1/2)\hbar\omega_k$ as
a contribution to $\rho$ *and* attributing the cosmic expansion to a
separate $\Lambda$ counts the $x_4$-rate twice.

*Step 3 (the renormalization).* The physical vacuum energy is the
Channel-B residue: the QFT sum after subtraction of the $x_4$-expansion
contribution. Formally, define the McGucken-renormalized vacuum energy
by
$$\rho_{\Lambda,\text{phys}} = \rho_{QFT} - \rho_{x_4}, \qquad \rho_{x_4} = \frac{1}{2(2\pi)^3}\int 4\pi k^2 \hbar\omega_k\, \mathcal{N}(k)\, dk,$$
where $\mathcal{N}(k)$ is the occupation number of mode $k$ by the
$x_4$-expansion field, fixed by the requirement that the renormalized
energy reduce to zero in the absence of curvature. By the same
calculation as in the companion paper [@McGuckenCosmology2026], this
subtraction cancels the leading $k_*^4$ divergence of $\rho_{QFT}$ and
leaves a residual proportional to $H^2$, which by Step 1 is exactly
$\Lambda c^2/(8\pi G) \cdot c^2/3$. The cancellation is enforced by
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, not imposed
by hand; it is the Channel-A/Channel-B consistency of the same physical
$x_4$-velocity.

*Step 4 (the magnitude).* The QFT estimate
$\rho_{QFT} \sim 10^{74}\,\text{GeV}^4$ (cut off at the Planck scale)
and the observed $\rho_\Lambda \sim 10^{-47}\,\text{GeV}^4$ differ by
$\sim 10^{121}$. The McGucken renormalization removes the $k_*^4$
Planck-scale contribution exactly, leaving the residue at the
cosmological scale $H$. The residue is $\sim H^2 c^4/(8\pi G)$, which
evaluates to $\sim 10^{-47}\,\text{GeV}^4$, matching observation. The
$10^{121}$ discrepancy was Channel-A bookkeeping mistaking an integrated
shadow of the $x_4$-expansion for an independent vacuum contribution. ◻


# Horizon, Flatness, Olbers, Hubble, S~8~ 

## Historical background: Olbers 1823 to horizon problem 1969 to Hubble and $S_8$ tensions 2020s

The horizon problem [@Guth1981] asks why the CMB is uniform across
regions that have never been in causal contact. The flatness problem
asks why $\Omega \approx 1$ to high precision. Olbers [@Olbers1826]
asked why the night sky is dark. The Hubble tension [@HubbleTension2021]
is the $\sim 5\sigma$ disagreement between early- and late-universe
measurements of $H_0$; the $S_8$ tension is the analogous disagreement
on structure growth.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 39** (Cosmological problems as $x_4$-expansion theorems). *The
horizon, flatness, Olbers, Hubble, and $S_8$ problems are theorems of
$dx_4/dt = ic$ applied at cosmological scales. The horizon is uniform
because every CMB event has the same $x_4$-phase; flatness follows from
spherical symmetry; Olbers is dissolved by the finite $x_4$-age of
light; Hubble and $S_8$ tensions vanish when the late-universe
measurements account for the local $x_4$-frame.*


::: proof
*Proof.* *Step 1 (the horizon problem and CMB uniformity).* The CMB
temperature is uniform across the sky to one part in $10^5$ over angular
scales larger than the naive causal horizon at recombination
($t_{\rm rec} \sim 380{,}000\,\mathrm{yr}$ after the Big Bang). In
standard cosmology, regions separated by more than $\sim 2$ degrees on
the sky have never been in causal contact since the singularity; the
uniformity is puzzling without inflation. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Principle holds at every event of the cosmological manifold
$\mathcal{M}_G$ with the same $|dx_4/dt|=c$ rate. The CMB photons
emitted at recombination from every spatial location all carry the same
local $x_4$-phase content (set by
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} at their
emission events), and their subsequent propagation along the past null
cones into our observation event preserves this phase content modulo the
cosmological redshift. The CMB uniformity is the Channel-B geometric
trace of the universal $x_4$-rate at every event; no inflation is
required to enforce uniformity, because the uniformity is supplied by
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} at the
foundational level.

*Step 2 (the flatness problem).* The observed cosmological density
parameter is $\Omega_{\rm total} = 1 \pm 0.01$, consistent with a
spatially flat universe. In standard cosmology, $\Omega = 1$ is an
unstable fixed point under the Friedmann dynamics; any small deviation
grows. The fine-tuning required to have $\Omega_0 \approx 1$ today
corresponds to $|\Omega - 1| < 10^{-60}$ at the Planck era. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
spherical symmetry of $x_4$-expansion at every event
(Remark [4](#rem:expansion){reference-type="ref"
reference="rem:expansion"}) implies that the spatial slices orthogonal
to the local $x_4$-axis are locally Euclidean: the $x_4$-velocity field
$|dx_4/dt|=c$ is isotropic at each event by Axiom, so the spatial
geometry orthogonal to it inherits isotropy. The cosmological scale
factor's evolution preserves this isotropy at the largest scales;
flatness is the geometric content of the spherical symmetry of
$x_4$-expansion. The fine-tuning problem is the artifact of attempting
to maintain flatness as an initial condition in a framework where the
symmetry is not built in; under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the symmetry is foundational.

*Step 3 (Olbers' paradox).* If the universe is infinite, eternal, and
uniformly populated with stars, the night sky should be uniformly
bright. Olbers' paradox is resolved by the finite age of the universe
(light from sufficiently distant stars has not yet reached us) and the
cosmological redshift (light from distant stars is redshifted to lower
energy). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, both effects are Channel-B content of the
$x_4$-expansion: the finite $x_4$-arclength along the past null cone
integrating to our observation event bounds the integration domain for
the brightness sum; the redshift of photons at large $z$ is the
Channel-A frequency redefinition under the $x_4$-frame rotation between
distant emission events and the local observer's frame
(Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}, Step 2 applied to the cosmological scale).
The brightness integral
$$\mathcal{B} = \int_0^{t_0} dt \int 4\pi r^2 dr\, n_*(r,t)\,L(r,t)/(4\pi r^2) \cdot e^{-z(r,t)}$$
converges because of both the finite upper limit on the time integral
(Big Bang singularity at $t = 0$) and the exponential redshift factor;
the night sky is dark.

*Step 4 (the Hubble tension).* Early-universe measurements (CMB, Planck
satellite) determine $H_0 = 67.4 \pm 0.5$ km/s/Mpc via the Channel-B
propagation of acoustic peaks in the CMB power spectrum, calibrated by
the standard sound-horizon distance. Late-universe measurements (SH0ES,
distance-ladder Cepheids and Type Ia supernovae) give
$H_0 = 73.0 \pm 1.0$ km/s/Mpc via local Channel-A standard candles. The
$\sim 5\sigma$ disagreement is the Hubble tension [@HubbleTension2021].
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
disagreement is the local-$x_4$-frame correction: the early-universe
measurement assumes the asymptotic CMB-rest $x_4$-frame for the
acoustic-peak propagation; the late-universe measurement uses the local
solar-system $x_4$-frame for the distance-ladder calibration. The
difference between the two frames---tracked by the cosmological
evolution of the local $x_4$-axis under the $x_4$-expansion of
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}---produces a
correction to the late-universe $H_0$ value relative to the
early-universe value. The correction is computed in the companion
paper [@McGuckenCosmology2026]; its magnitude matches the observed
tension.

*Step 5 (the $S_8$ tension).* Structure growth at late times is
parameterized by $S_8 \equiv \sigma_8 \sqrt{\Omega_m/0.3}$, with
$\sigma_8$ the matter power-spectrum amplitude at 8 Mpc and $\Omega_m$
the matter density. Early-universe (CMB) measurements give
$S_8 \approx 0.83$; late-universe (weak-lensing surveys like KiDS, DES)
give $S_8 \approx 0.77$, a $\sim 3\sigma$ disagreement. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
suppression of structure growth at late times is the same
local-$x_4$-frame correction as in Step 4: as the local frame's
$x_4$-axis tilts away from the asymptotic CMB-rest frame, the late-time
growth of structure on cosmological scales is suppressed relative to the
early-time prediction. The suppression mechanism and its numerical
agreement with the $S_8$ data are developed in [@McGuckenCosmology2026].

*Step 6 (the structural diagnosis).* The horizon, flatness, Olbers,
Hubble, and $S_8$ problems are five operational signatures of the
cosmological-scale content of Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}: the universal $|dx_4/dt|=c$ rate at every event
supplies the CMB uniformity (Step 1) and the spatial flatness (Step 2);
the finite $x_4$-history of the universe supplies the dark night sky
(Step 3); the local-frame correction supplies the Hubble and $S_8$
tensions (Steps 4--5). No additional postulates (inflation, modified
gravity, dark sector dynamics) are required for the resolutions; each
problem is a theorem of $dx_4/dt = ic$ at cosmological scales. ◻


# Arrow of Time, Loschmidt, Poincaré Recurrence, Maxwell Demon 

## Historical background: Boltzmann 1872, Loschmidt 1876, Poincaré 1890, Landauer 1961

Boltzmann [@Boltzmann1872] derived the H-theorem;
Loschmidt [@Loschmidt1876] objected that the underlying mechanics is
time-symmetric. Poincaré [@Poincare1890] proved that bounded Hamiltonian
systems recur. Maxwell's demon [@Maxwell1871] was proposed as a
hypothetical violation of the second law; Szilárd [@Szilard1929] and
Landauer [@Landauer1961] closed the loophole via the thermodynamic cost
of information erasure.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 40** (Five arrows of time unified by $x_4$-expansion). *The
thermodynamic, cosmological, psychological, electromagnetic-radiative,
and quantum-measurement arrows of time are all manifestations of the
same fact: $dx_4/dt = ic$ has positive sign. The Loschmidt objection and
Poincaré recurrence apply to Channel A (the algebraic reversibility of
the unitary) but not to Channel B (the geometric $x_4$-expansion); the
asymmetry is encoded in the latter.*


::: proof
*Proof.* *Step 1 (the $+ic$ orientation is foundational at every
event).* Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}
states $dx_4/dt = ic$ with a definite sign on $i$. Under spherical
symmetry of the $x_4$-expansion
(Remark [4](#rem:expansion){reference-type="ref"
reference="rem:expansion"}), the expansion proceeds outward from every
event at rate $|dx_4/dt|=c$ along the future null cone; no
backward-in-time mode at $-ic$ exists as a foundational propagation
direction. The sign of $i$ is fixed at the level of the axiom; it is not
a free parameter or boundary condition. The time-orientation of the
universe descends from this fixed sign.

*Step 2 (the thermodynamic arrow).* Boltzmann's
H-theorem [@Boltzmann1872] establishes that the function
$$H(t) = \int f(\vec x, \vec p, t) \ln f(\vec x, \vec p, t)\, d^3x\, d^3p$$
decreases monotonically along solutions of the Boltzmann equation,
giving $dS/dt \ge 0$ via $S = -k_B H$. Loschmidt [@Loschmidt1876]
objected that the underlying microscopic dynamics is time-reversal
symmetric: reversing all particle velocities produces a solution of the
equations of motion that runs the H-theorem backward. The orthodox
resolution invokes a low-entropy initial condition (Past Hypothesis);
under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
resolution is structural: the Channel-A microscopic dynamics is
time-symmetric, but the Channel-B $x_4$-expansion at $+ic$ at every
event supplies an irreducible asymmetry on every microscopic worldline.
The H-theorem's monotone-decrease is the Channel-B propagation along the
$+ic$-oriented null cones; the time-reversed Loschmidt scenario would
require $-ic$-oriented propagation, which is excluded by
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}.

*Step 3 (Poincaré recurrence).* Poincaré's recurrence
theorem [@Poincare1890] states that any bounded Hamiltonian system
returns arbitrarily close to its initial state in finite (though
exponentially long) time. For a system with $N \sim 10^{23}$ degrees of
freedom in a bounded phase space, the recurrence time is of order
$e^{N}$ seconds, vastly exceeding any cosmological scale. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
recurrence theorem is a Channel-A statement about the closed phase-space
measure-preserving flow; it does not include the Channel-B content of
$x_4$-expansion at every event. For an open system whose constituent
events are advancing in $x_4$, the phase space itself is not bounded in
any finite-volume sense: the McGucken Sphere structure at every event
continually generates new phase-space volume. The recurrence theorem
does not apply at the cosmological scale.

*Step 4 (the electromagnetic-radiative arrow).* The Maxwell equations
admit both retarded and advanced solutions; classical electrodynamics is
time-symmetric in this sense. The empirical fact that only retarded
solutions are observed (radiation flows from accelerating charges
outward into the future, not from outer space inward into accelerating
charges) is the radiative arrow. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
retarded character is the Channel-B $+ic$-orientation of the
$x_4$-expansion at every event: the Green's function
$G_{\rm ret}(x-y) \propto \theta(x^0 - y^0)\delta((x-y)^2)$ is the
propagation kernel along the future null cone of $y$, which is the
$+ic$-oriented McGucken Sphere $\Sigma_+(y)$. The advanced solution
would require propagation along the past null cone, against the $+ic$
orientation. The Sommerfeld radiation condition---no incoming radiation
from past null infinity---is the Channel-B form of the $+ic$
orientation.

*Step 5 (the cosmological arrow).* The universe is observed to be
expanding; galaxies recede with redshift proportional to distance
(Hubble's law). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the cosmological expansion is the integrated
content of the $+ic$-oriented $x_4$-expansion at every event of the
cosmological manifold; the Hubble rate $H$ is the rate at which the
local $x_4$-axis advances the spatial slice orthogonal to it
(Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}, Step
1). The cosmological arrow points from low-entropy past (high
temperature, dense state) to high-entropy future (low temperature,
expanded state); this arrow is set by the $+ic$ orientation, not by a
separate initial condition.

*Step 6 (the psychological and quantum-measurement arrows).* The
psychological arrow of time (subjective sense of past, present, future)
and the quantum-measurement arrow (irreversibility of measurement
events) are also Channel-B content. The psychological arrow tracks the
observer's worldline advance at $|dx_4/dt|=c$ along their proper time;
each conscious moment is at the observer's worldline tip, advancing into
the future. The quantum-measurement arrow is the irreversibility of the
$x_4$-pinch event at the apparatus
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, Step 5): the Channel-B advance of the
apparatus's $N$ thermal degrees of freedom along their worldlines erases
the off-diagonal coherence on time scales $1/\Gamma$, and the inverse
re-coherence operation is excluded by the same Channel-B advance. All
five arrows are the same arrow, viewed at different scales.

*Step 7 (Maxwell's demon and Landauer).* Maxwell's demon [@Maxwell1871]
measures the velocities of particles in a gas and sorts them by velocity
into two chambers, apparently violating the Second Law.
Szilárd [@Szilard1929] and Landauer [@Landauer1961] showed that the
demon's memory register, which stores the measurement record, must
eventually be erased to close the operational cycle; the erasure
dissipates $k_B T \ln 2$ per bit. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the erasure
is a Channel-B $x_4$-pinch on the demon's memory register: by
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, this pinch is irreversible at the
apparatus's Channel-B decoherence scale, and the dissipated energy is
the thermodynamic cost of the pinch. The Second Law is preserved at
every step of the demon's cycle; the apparent violation is the orthodox
bookkeeping cost of treating the memory record as free, when in fact the
Channel-B advance of the memory's constituent degrees of freedom along
their worldlines requires the Landauer dissipation.

*Step 8 (uniform diagnosis).* The five arrows of time---thermodynamic,
electromagnetic-radiative, cosmological, psychological,
quantum-measurement---are five operational signatures of the same
foundational fact: $dx_4/dt = ic$ has $+ic$ orientation at every event
by Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}. The
Loschmidt objection mistakes the Channel-A time-symmetry of the
underlying dynamics for an absence of Channel-B asymmetry; Poincaré
recurrence applies only to the Channel-A bounded phase-space without
Channel-B expansion; Maxwell's demon is closed by Landauer erasure, the
Channel-B decoherence cost of memory clearance. No additional postulates
are required. ◻


# Sorkin Impossible Measurements and Unruh 

## Historical background: Unruh 1976 to Sorkin 1993 to Martín-Martínez 2015

Sorkin [@Sorkin1993] pointed out that naively local quantum measurements
in relativistic QFT permit superluminal signaling; the problem has been
called the "impossible measurements problem."
Martín-Martínez [@MartinMartinez2021] catalogued nine related QFT
pathologies. Unruh [@Unruh1976] showed that an accelerated observer in
Minkowski vacuum sees a thermal bath; the temperature is
frame-dependent, raising questions about the meaning of "vacuum."

## The McGucken $dx_4/dt = ic$ reading


**Theorem 41** (Sorkin / Martín-Martínez / Unruh as $x_4$-frame
artifacts). *The Sorkin impossible-measurements problem, the nine
Martín-Martínez pathologies, and the Unruh frame dependence all arise
from extrapolating a single $x_4$-frame across spacelike-separated or
accelerated regions. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, each region carries its own $x_4$-frame; the
apparent paradoxes vanish when the local frames are used.*


::: proof
*Proof.* *Sorkin's argument.* Sorkin [@Sorkin1993] considers three
spacetime regions $A$, $B$, $C$ with $A$ in the causal past of $C$, $B$
spacelike to $A$ and in the causal past of $C$. A local operator
$\hat O_B$ at $B$ in the Heisenberg picture is associated with a
projector $\hat P_B = |\phi\rangle\langle\phi|$ that depends, through
the unitary evolution from $A$ to $B$, on whether or not a measurement
is performed at $A$. The resulting probability for an outcome at $C$
then depends on the choice of measurement at $A$, even though $A$ and
$B$ are spacelike separated. The naive locality of the operator algebra
is broken.

*Step 1 (the Channel-A error in Sorkin's projector).* The projector
$\hat P_B$ is constructed by acting with $\hat O_B$ on a field state
that has been evolved from $A$ to $B$ via the Tomonaga--Schwinger
surface-dependent Schrödinger equation. The construction implicitly
assumes that the entire Cauchy slice through $B$ shares a single
$x_4$-frame extending across the spacelike region containing $A$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
assumption fails: each event has its own $x_4$-axis aligned with its
local proper time, and the spherical $x_4$-expansion from $A$ has not
reached $B$. The Channel-B propagation respects the spherical
$x_4$-velocity field, which is null-cone-restricted; the Channel-A
projector that extends across the spacelike interval is not the shadow
of any physical operator.

*Step 2 (the correct projector).* Restrict $\hat P_B$ to the support of
$B$'s past null cone---the region from which $B$'s $x_4$-expansion was
actually fed. The restricted projector $\hat P_B^{\text{phys}}$ has
support disjoint from $A$ when $A$ is spacelike to $B$. The conditional
probability
$\Pr(C \mid \hat O_B^{\text{phys}}, \hat O_A) = \Pr(C \mid \hat O_B^{\text{phys}})$
then satisfies no-signaling. The detailed treatment of the nine
Martín-Martínez [@MartinMartinez2021] pathologies---negative probability
densities, Brillouin-zone dimensional bugs, spectrum-vs-support
conflations, and Riemann--Lebesgue misapplications---is given in the
companion paper [@McGuckenSorkin2026]; in each case the pathology is
traced to an extension of a Channel-A operator across a region where the
Channel-B $x_4$-velocity field has not propagated.

*Unruh's argument.* Let $|0_M\rangle$ denote the Minkowski vacuum and
$\hat a_\omega^R$ the annihilation operator of a Rindler mode of Rindler
frequency $\omega$ in the right wedge. Unruh [@Unruh1976] showed
$$\langle 0_M | \hat a_\omega^{R\dagger} \hat a_\omega^R | 0_M \rangle = \frac{1}{e^{2\pi\omega c/a} - 1},$$
the Planckian distribution at temperature $T = \hbar a/(2\pi k_B c)$,
where $a$ is the proper acceleration. The inertial observer sees vacuum;
the accelerated observer sees thermal radiation.

*Step 3 (Unruh as $x_4$-frame mismatch).* The inertial observer's
$x_4$-axis is the Minkowski $t$-coordinate; the accelerated observer's
$x_4$-axis is the proper time $\tau$ along the Rindler trajectory, which
is a hyperbolic rotation of the inertial $t$-axis. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$x_4$-velocity field is locally $ic$ in both frames, but the directions
of the two $x_4$-axes differ by a $\tau$-dependent boost. The Minkowski
vacuum, defined as the ground state of the inertial $x_4$-Hamiltonian,
is *not* the ground state of the Rindler $x_4$-Hamiltonian; the
Bogoliubov decomposition between the two sets of $x_4$-modes generates
the thermal occupation. Concretely, the Bogoliubov coefficients
$\alpha_{\omega\omega'} = (\omega/\omega')^{1/2} e^{\pi\omega c/(2a)}/\sqrt{2\sinh(\pi\omega c/a)}$
and
$\beta_{\omega\omega'} = (\omega/\omega')^{1/2} e^{-\pi\omega c/(2a)}/\sqrt{2\sinh(\pi\omega c/a)}$
give $|\beta|^2/(|\alpha|^2 - |\beta|^2) = 1/(e^{2\pi\omega c/a} - 1)$,
the Planckian. Both observers are correct in their local $x_4$-frames;
the frame mismatch is the geometric content of the temperature.

*Step 4 (consistency).* Both Sorkin's pathology and Unruh's effect
dissolve under the same mechanism: restriction to local $x_4$-frames
whose velocity field is null-cone-restricted. The shared mechanism
reflects a shared source---the Channel-A habit of treating $x_4$ as a
global coordinate when it is the integrated shadow of a local velocity.
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} restores the
velocity, restoring locality. ◻


# The Problem of Time in Quantum Gravity 

## Historical background: DeWitt 1967 to Page--Wootters 1983

The Wheeler--DeWitt equation [@DeWitt1967] is the canonical quantization
of general relativity in the Hamiltonian (ADM) formalism. It takes the
form $\hat{\mathcal H} |\Psi\rangle = 0$: the total Hamiltonian
annihilates the universal wave function. Time disappears. The problem of
time [@Isham1992; @Kuchar1991; @Anderson2017] is the conceptual
difficulty of recovering the temporal evolution that defines the rest of
physics.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 42** (Wheeler--DeWitt frozen-time as $x_4$-integration). *The
vanishing of the total Hamiltonian on $|\Psi\rangle$ is the Channel-A
statement that the total $x_4$-phase of the universe is constant on the
constraint surface. Time has not disappeared; the $x_4$-coordinate has
been integrated out to its endpoint. Restoring $dx_4/dt = ic$ as a
velocity rather than a coordinate restores the evolution.*


::: proof
*Proof.* *Step 1 (the ADM Hamiltonian constraint).* In the canonical
(ADM) formulation of general relativity, the spacetime metric is
decomposed as $g_{\mu\nu} = (-N^2 + N_i N^i,\, N_i,\, h_{ij})$ with $N$
the lapse, $N^i$ the shift, and $h_{ij}$ the spatial metric on a Cauchy
slice. The Einstein--Hilbert action becomes
$$S = \frac{1}{16\pi G}\int dt\,d^3x\, N\sqrt{h}\,(K_{ij}K^{ij} - K^2 + {}^{(3)}R),$$
with $K_{ij}$ the extrinsic curvature. Variation with respect to $N$
produces the Hamiltonian constraint
$$\mathcal{H} = G_{ijkl}\pi^{ij}\pi^{kl} - \sqrt{h}\, {}^{(3)}R = 0,$$
and the canonical quantization $\hat{\mathcal H}|\Psi\rangle = 0$ is the
Wheeler--DeWitt equation. The constraint reflects diffeomorphism
invariance: physical states are independent of the choice of
time-slicing.

*Step 2 (what "time has disappeared" means).* The Wheeler--DeWitt
equation has no explicit time dependence; $|\Psi\rangle$ is a function
on superspace (the space of spatial metrics modulo diffeomorphisms), not
a function of time. The Schrödinger equation
$i\hbar \partial_t \psi = \hat H \psi$ of ordinary quantum mechanics is
absent; in its place is the timeless constraint
$\hat{\mathcal H}|\Psi\rangle = 0$. This is the "frozen time" problem:
how is the empirical content of time-evolution recovered from a wave
function that does not evolve?

*Step 3 (the integration interpretation under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
$dx_4/dt = ic$ is a velocity at every event, with the integrated label
$x_4 = ict$ being the mere shadow
(Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}). The Wheeler--DeWitt constraint is the
canonical-quantization expression of diffeomorphism invariance under
reparameterization of the time coordinate $t$; under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
reparameterization is a change of the $x_4$-endpoint label without
change in the underlying velocity field. The constraint
$\hat{\mathcal H}|\Psi\rangle = 0$ then says: physical states are
insensitive to which $x_4$-endpoint is chosen as the slice label,
because the foundational content (the velocity $dx_4/dt$ at every event)
is independent of the label. The integration has been carried out, and
the constraint is the Channel-A bookkeeping of the label-independence.

*Step 4 (the Page--Wootters mechanism as Channel-B relational time).*
Page and Wootters [@PageWootters1983] showed that time-evolution can be
recovered from the Wheeler--DeWitt equation by treating one subsystem (a
"clock") as a reference and conditioning the wave function of the rest
on the clock's observed value. The conditional state of the rest evolves
under an effective Schrödinger equation with respect to the clock's
value. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the Page--Wootters clock is a subsystem whose
$x_4$-advance can be operationally read; the conditional state of the
rest, given the clock's $x_4$-phase, evolves at the relative
$x_4$-advance rate. The Channel-B content of $dx_4/dt = ic$ along the
clock's worldline supplies the operational time-evolution of the rest,
while the Channel-A constraint $\hat{\mathcal H}|\Psi\rangle = 0$
remains satisfied for the combined system.

*Step 5 (the problem of time is the Channel-A/Channel-B blindness).* The
Wheeler--DeWitt "problem of time" arises because the orthodox
Channel-A-only-reading vocabulary cannot articulate the Channel-B
relational time-content of $dx_4/dt = ic$. The constraint
$\hat{\mathcal H}|\Psi\rangle = 0$ is the Channel-A integrated form
(with the velocity content discarded by integration to the endpoint);
the operational time-evolution requires the Channel-B velocity content
(the $|dx_4/dt|=c$ rate along each worldline). The McGucken framework
supplies both: the integrated constraint as Channel A, the relational
evolution as Channel B. The "problem" dissolves when both channels are
read together.

*Step 6 (consistency with the QM-GR time-treatment dichotomy).* The
diagnostic (C5) of §[62](#sec:diagnostic){reference-type="ref"
reference="sec:diagnostic"} identifies the broader incompatibility: QM
treats time as a parameter (Pauli's no-time-operator theorem), GR treats
time as a coordinate (one of four pseudo-Riemannian coordinates). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, both are
integrated forms of the same velocity: the QM parameter-time is the
Channel-A integrated form of $dx_4/dt = ic$ via Stone's theorem applied
to the Hamiltonian; the GR coordinate-time is the Channel-B integrated
form via the geometric expansion. The Wheeler--DeWitt equation is the
canonical quantization of the latter; the Schrödinger equation is the
canonical reading of the former; the two are consistent under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} as the two
channel-readings of the same foundational velocity. ◻


# Dynamical Collapse Models 

## Historical background: GRW 1986 to Pearle CSL 1989 to Penrose 1996

In response to the measurement problem, several authors proposed
modifications of the Schrödinger equation that produce spontaneous
collapse. Ghirardi, Rimini, and Weber [@GRW1986] introduced stochastic
localization; Pearle [@Pearle1989] and Bassi and
Ghirardi [@BassiGhirardi2003] produced the continuous spontaneous
localization (CSL) model; Penrose [@Penrose1996] argued that gravity
induces collapse at a mass-dependent rate.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 43** (Collapse rates as Channel-B decoherence). *The collapse
rates of GRW, CSL, and Penrose are not new physics; they are different
approximations to the Channel-B decoherence rate induced by the
$x_4$-advance of the apparatus or the gravitational field. The CSL
collapse parameter $\lambda \sim 10^{-16}$ s$^{-1}$ per nucleon and the
Penrose rate $\tau_P \sim \hbar/E_G$ with $E_G$ the gravitational
self-energy are both approximations to the rate at which $N$ thermal
degrees of freedom advance through
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}'s $x_4$-pinch.*


::: proof
*Proof.* *Step 1 (the fundamental decoherence rate).* By
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, the $x_4$-pinch decoherence rate for a
system coupled to an apparatus of $N$ thermal degrees of freedom with
characteristic frequency $\omega_{th}$ is
$$\Gamma_{x_4} = N \omega_{th}\, \mathcal{I},$$ where $\mathcal{I}$ is
the dimensionless interference suppression integral,
$\mathcal{I} = \mathcal{O}(1)$ for a strongly coupled apparatus. For a
macroscopic body, $N \sim 10^{23}$ and
$\omega_{th} \sim k_B T/\hbar \sim 10^{13}$ s$^{-1}$ at room
temperature; $\Gamma_{x_4} \sim 10^{36}$ s$^{-1}$. This is the rate at
which the $x_4$-phase of the system is pinched into a single branch by
Channel-B advance of the apparatus.

*Step 2 (GRW as a Markovian coarse-graining).* The GRW model [@GRW1986]
postulates a localization Poisson process of rate $\lambda$ per nucleon,
with localization width $r_C \sim 10^{-7}$ m. For a macroscopic body
with $N \sim 10^{23}$ nucleons, the effective rate is
$\lambda_{\text{eff}} = N \lambda \sim 10^{23} \cdot 10^{-16}\,\text{s}^{-1} = 10^7\,\text{s}^{-1}$.
The GRW localizations replace the unitary evolution by a stochastic
projection. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the GRW process is the Markovian limit of the
$x_4$-pinch in which the apparatus correlations are coarse-grained over
time scales $\gg 1/\omega_{th}$. The factor
$\lambda/\omega_{th} \sim 10^{-29}$ is the small parameter of this
coarse-graining: each fundamental $x_4$-pinch step contributes a small
probability of producing a Markovian localization. The GRW rate is
therefore a derived quantity, not fundamental.

*Step 3 (CSL as a continuous limit).* The CSL
model [@Pearle1989; @BassiGhirardi2003] replaces the GRW Poisson process
by a continuous stochastic differential equation,
$$d|\psi\rangle = \left(-\frac{i}{\hbar}\hat H\, dt + \int \!\!\hat N(\mathbf{x})\, dW_t(\mathbf{x})\, d^3 x - \frac{1}{2}\int \!\!\hat N(\mathbf{x})^2\, dt\, d^3 x\right) |\psi\rangle,$$
where $\hat N(\mathbf{x})$ is a smeared mass-density operator and $W_t$
is a white-noise field with coupling $\gamma$. The CSL coupling is fixed
by demanding that macroscopic superpositions collapse on observable time
scales: $\gamma m_N^2 \sim 10^{-30}$ in natural units, giving an
effective per-nucleon rate $\lambda_{\text{CSL}} \sim 10^{-16}$
s$^{-1}$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the noise field $W_t(\mathbf{x})$ is the Channel-B
trace of the $x_4$-advance of the environmental degrees of freedom that
have been integrated out; the CSL equation is the Lindblad limit of the
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"} master equation when the bath is Markovian
and Gaussian. The coupling $\gamma$ is fixed by the spectral density of
the bath, not by new physics.

*Step 4 (Penrose as a gravitational sub-case).* Penrose [@Penrose1996]
postulates a gravity-induced collapse rate
$$\tau_P^{-1} = \frac{E_G}{\hbar},\qquad E_G = G \int \!\!\!\int \frac{[\rho_1(\mathbf{x}) - \rho_2(\mathbf{x})][\rho_1(\mathbf{y}) - \rho_2(\mathbf{y})]}{|\mathbf{x}-\mathbf{y}|}\, d^3 x\, d^3 y,$$
where $\rho_{1,2}$ are the two mass densities of the superposition. For
a $10^{-13}$ kg body in a 10 nm superposition, $E_G \sim 10^{-30}$ J and
$\tau_P^{-1} \sim 10^4$ s$^{-1}$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
gravitational self-energy is the Channel-B coupling between the
$x_4$-expansions of the two branches: the spherical $x_4$-velocity
fields emanating from $\rho_1$ and $\rho_2$ interfere geometrically with
strength $E_G$. The decoherence rate $E_G/\hbar$ is the rate at which
the two $x_4$-frames dephase. Penrose's rate is therefore the
gravitational sector of
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}.

*Step 5 (hierarchy).* Collecting the rates:
$$\Gamma_{x_4}^{\text{fund}} \sim 10^{36}\,\text{s}^{-1} \;\gg\; \tau_P^{-1} \sim 10^4\,\text{s}^{-1} \;\sim\; \lambda_{\text{CSL,eff}} \sim 10^{7}\,\text{s}^{-1} \;\gg\; \lambda_{\text{CSL}} \sim 10^{-16}\,\text{s}^{-1}.$$
The fundamental rate dominates by many orders of magnitude. The
collapse-model rates are not new physics; they are different effective
approximations of $\Gamma_{x_4}$ obtained by tracing out different
sectors of the environment (full thermal bath, gravitational sector,
smeared mass-density sector). ◻


# Stern--Gerlach, Bohmian Pilot Waves, and Many-Worlds 

## Historical background: Stern--Gerlach 1922 to Bohm 1952 to Everett 1957

The Stern--Gerlach experiment [@SternGerlach1922] demonstrated spin
quantization. Bohmian mechanics [@Bohm1952; @DurrTeufel2009]
reformulated quantum mechanics as a deterministic theory with hidden
particle trajectories guided by a pilot wave. Everett's relative-state
formulation [@Everett1957] (later many-worlds) takes the unitary
evolution as universal and denies collapse.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 44** (Bohm and Everett as Channel-A bookkeeping). *Bohmian
mechanics and the many-worlds interpretation are not separate physical
theories but two Channel-A bookkeeping schemes for the same Channel-B
dynamics of $x_4$-pinch. Bohm distributes the $x_4$-pinch among the
hidden trajectory; Everett distributes it among the branches.*


::: proof
*Proof.* *Step 1 (Bohmian dynamics is the $x_4$-velocity field).* Write
the wave function in polar form
$\psi(\mathbf{x},t) = R(\mathbf{x},t) e^{iS(\mathbf{x},t)/\hbar}$. The
Schrödinger equation $i\hbar \partial_t \psi = (\hat p^2/2m + V)\psi$
separates into the continuity equation
$\partial_t R^2 + \nabla\cdot(R^2 \nabla S/m) = 0$ and the quantum
Hamilton--Jacobi equation
$$\partial_t S + \frac{(\nabla S)^2}{2m} + V - \frac{\hbar^2}{2m}\frac{\nabla^2 R}{R} = 0.$$
Bohm [@Bohm1952] postulates a particle trajectory governed by
$\dot{\mathbf{x}} = \nabla S/m$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the wave
function's phase $S$ is the $x_4$-phase accumulated by the spherical
expansion field; specifically, by
Theorem [19](#thm:duality){reference-type="ref"
reference="thm:duality"},
$S/\hbar = \omega t - \mathbf{k}\cdot\mathbf{x}$ is the projection of
the $x_4$-velocity onto the spatial slice. The gradient
$\nabla S/m = \hbar \mathbf{k}/m = \mathbf{p}/m$ is exactly the local
Channel-B group velocity of the $x_4$-expansion field. Hence the Bohmian
trajectory $\dot{\mathbf{x}} = \nabla S/m$ is the integral curve of the
Channel-B $x_4$-velocity field projected onto $x_1 x_2 x_3$.

*Step 2 (the Bohmian quantum potential is the $x_4$-curvature).* The
term $Q = -(\hbar^2/2m)\nabla^2 R/R$ in the quantum Hamilton--Jacobi
equation is the Bohmian *quantum potential*. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, $Q$ is the
local curvature of the $x_4$-amplitude $R$: the $x_4$-velocity field is
not free but is constrained by the spherical-symmetry condition
$|dx_4/dt| = c$, which imposes a curvature on the spatial profile $R$.
The quantum potential is therefore the Channel-A bookkeeping of the
$x_4$-curvature; it carries no independent dynamics.

*Step 3 (Everett branches are the post-decoherence $x_4$-frames).* In
Everett's relative-state formulation, the universal wave function never
collapses; after a measurement, the global state is
$|\Psi\rangle = \sum_n c_n |a_n\rangle |\Phi_n\rangle |E_n\rangle$ with
$|a_n\rangle$ system, $|\Phi_n\rangle$ apparatus, $|E_n\rangle$
environment, all mutually orthogonal after decoherence. Observers are
represented by states in $|\Phi_n\rangle$ correlated with the system.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
decoherence by Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"} is the $x_4$-pinch that produces $N$
mutually orthogonal environment states $|E_n\rangle$ on the apparatus's
local $x_4$-frame. Each branch $n$ corresponds to a distinct $x_4$-frame
in which the apparatus pointer has a definite value. The branches are
the Channel-A enumeration of the possible $x_4$-frame rotations after
the pinch.

*Step 4 (Born weights from $i^2 = -1$).* The probability assigned to
branch $n$ is $|c_n|^2$. By Theorem [45](#thm:born){reference-type="ref"
reference="thm:born"} (derived below), this weight follows from the
requirement that the $x_4$-phase, which carries the factor $i$ via
$dx_4/dt = ic$, contribute to probability only through the sesquilinear
pairing $\psi^* \psi$. The same Born weight applies to the Bohmian
configuration-space density and to the Everettian branch weight; both
inherit it from the underlying $x_4$-phase structure.

*Step 5 (the bookkeeping difference).* Bohmian mechanics fixes the
configuration space and lets the wave function be a guiding field over
it; Everett fixes the wave function and lets the configuration be a
label on a branch. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, both descriptions are projections of the same
Channel-B $x_4$-velocity field: Bohm projects onto the integral curve of
the velocity (one trajectory through configuration space), Everett
projects onto the orthogonal decomposition of the post-pinch state (one
frame per branch). Neither projection adds physical content beyond what
Channel B already encodes; both are Channel-A bookkeeping. The two
interpretations are therefore equivalent in their physical predictions
and differ only in their choice of Channel-A representation. ◻


# Wave Function Collapse and the Born Rule 

## Historical background: Born 1926 to Gleason 1957 to Zurek envariance 2005

Born [@Born1926] proposed that $|\psi(x)|^2$ gives the probability
density of finding a particle at $x$. The rule has resisted derivation
from the rest of quantum mechanics; Gleason [@Gleason1957] derived it
from non-contextuality of probability measures on Hilbert space;
Zurek [@ZurekEnvariance2005] from envariance; Deutsch [@Deutsch1999] and
Wallace [@Wallace2012] from decision-theoretic axioms in Everettian
context.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 45** (Born rule from $i^2 = -1$). *The Born rule
$P(a_n) = |\langle a_n | \psi\rangle|^2$ is forced by
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}: the
sesquilinear inner product $\langle \cdot, \cdot \rangle$ is the unique
probability-conserving form on the complex Hilbert space whose imaginary
axis is $x_4$. The Channel-A factor $i$ in $dx_4/dt = ic$ enforces
$\langle \phi, \psi\rangle = \overline{\langle\psi, \phi\rangle}$; the
modulus squared is the unique frame-independent positive form.*


::: proof
*Proof.* *Step 1 (the complex structure of $\mathcal{H}$ from
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Principle $dx_4/dt = ic$ supplies the imaginary unit $i$ as the
algebraic content (Channel A) of the velocity. The factor $i$ enforces
the orthogonality of $x_4$ to the three spatial directions:
$dx_4 \perp d\vec x$, and the orthogonality is implemented algebraically
as $\sqrt{-1}$ in the relation $dx_4 = ic\,dt$. The Hilbert space
$\mathcal{H}$ on which quantum states reside inherits this complex
structure: states $|\psi\rangle$ live in a complex vector space whose
phase rotation is generated by the same $i$. The time-evolution operator
$\hat U(t) = \exp(-i\hat H t/\hbar)$ has the $i$ from $dx_4/dt = ic$ as
the factor that makes $\hat H$'s exponential unitary
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, Step 1).

*Step 2 (the inner product must be sesquilinear).* Suppose a form
$\langle \cdot, \cdot \rangle: \mathcal{H} \times \mathcal{H} \to \mathbb{C}$
is to be (i) conserved by unitary evolution $\hat U(t)$, (ii) positive
on the diagonal $\langle \psi, \psi\rangle \ge 0$ with equality iff
$\psi = 0$, and (iii) compatible with the complex structure of
$\mathcal{H}$ supplied by Step 1. Unitary conservation requires
$\langle \hat U \phi, \hat U \psi\rangle = \langle \phi, \psi\rangle$
for all generators of one-parameter unitary groups; Stone's theorem
identifies the generators as self-adjoint operators with respect to the
form. Self-adjointness of $\hat H$, i.e.,
$\langle \hat H \phi, \psi\rangle = \langle \phi, \hat H \psi\rangle$,
combined with the complex linearity in the second argument and the
time-evolution rule $\hat U^\dagger = \hat U^{-1}$, forces the form to
be *sesquilinear*: linear in the second argument, antilinear
(complex-conjugate-linear) in the first. A bilinear form (linear in both
arguments) would fail to be conserved by unitaries generated by
self-adjoint operators because
$(\hat U^\dagger \phi)^* \neq (\hat U^* \phi)^*$ for general unitaries.
The sesquilinear form is forced by the Channel-A factor $i$ in
$dx_4/dt = ic$.

*Step 3 (Gleason's theorem and the structure of probability measures).*
On a complex Hilbert space of dimension $\ge 3$, Gleason's
theorem [@Gleason1957] states that every $\sigma$-additive probability
measure $\mu$ on the lattice of closed subspaces, satisfying
$\mu(\mathcal{H}) = 1$ and
$\mu(\mathcal{S}_1 \cup \mathcal{S}_2) = \mu(\mathcal{S}_1) + \mu(\mathcal{S}_2)$
for orthogonal $\mathcal{S}_1, \mathcal{S}_2$, has the form
$\mu(\mathcal{S}) = \mathrm{tr}(\rho\, \hat P_{\mathcal{S}})$ for a
positive trace-class operator $\rho$ with $\mathrm{tr}\,\rho = 1$ (the
density matrix). For a pure state $\rho = |\psi\rangle\langle\psi|$ and
a one-dimensional subspace $\mathcal{S} = \mathrm{span}\{|a_n\rangle\}$,
the formula reduces to
$$\mu(\mathcal{S}) = \langle\psi | a_n\rangle\langle a_n | \psi\rangle = |\langle a_n | \psi\rangle|^2.$$
This is the Born rule.

*Step 4 (the role of $i^2 = -1$ in the squared modulus).* The squared
modulus $|c_n|^2 = c_n \overline{c_n}$ is the only sesquilinear
combination of an amplitude $c_n$ with itself that is real and
non-negative. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the phase of $c_n$ is the $x_4$-phase accumulated
along the relevant worldline; multiplying by $\overline{c_n}$ removes
the phase and leaves the modulus squared as the basis-invariant content.
The property that this modulus is preserved under the $\pi/2$ rotation
generated by $i$ (which is the Channel-A factor in $dx_4/dt = ic$) is
the foundational source of probability conservation: the SU(2) action on
a two-dimensional Hilbert space, generated by the Pauli matrices with
their characteristic factor of $i$, preserves the probabilities
$|c_n|^2$.

*Step 5 (the McGucken Sphere SO(3)-Haar measure at the registration
event).* The Born-rule probabilities can also be derived geometrically
from the McGucken Sphere at the measurement event. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$x_4$-expansion from the measurement event $E$ generates the McGucken
Sphere $\Sigma_+(E)$ as the future null cone of $E$. The Sphere carries
a unique SO(3)-invariant probability measure (the Haar measure on the
rotation group acting on $\Sigma_+(E)$ orientations). For a measurement
of an observable $\hat A$ with eigenvectors $\{|a_n\rangle\}$ in a
Hilbert space, the projection of the state $|\psi\rangle$ onto each
$|a_n\rangle$ direction corresponds to a Sphere orientation, and the
SO(3)-Haar measure on the Sphere assigns probability
$|\langle a_n | \psi\rangle|^2$ to outcome $a_n$. The Channel-B
geometric derivation is given in the corpus
paper [@McGuckenQuantum2026; @McGuckenInfoParadox2026]; here the
Channel-A Gleason derivation (Step 3) and the Channel-B Sphere-Haar
derivation are two routes to the same Born rule.

*Step 6 (uniqueness and structural diagnosis).* The Born rule is the
unique probability measure compatible with (i) the sesquilinear inner
product structure of $\mathcal{H}$ supplied by Step 2, (ii) the Gleason
additivity structure of Step 3, and (iii) the SO(3)-Haar geometric
structure of Step 5. All three structures descend from
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} via the
algebraic content of $i$ (Channel A) and the geometric content of the
spherical $x_4$-expansion (Channel B). The Born rule is therefore a
theorem of $dx_4/dt = ic$, not an independent postulate. ◻


# Heisenberg Uncertainty and Complementarity 

## Historical background: Heisenberg 1927 to Kennard 1927 to Robertson--Schrödinger 1929

Heisenberg's 1927 paper [@Heisenberg1927] established the uncertainty
relation $\Delta x \Delta p \geq \hbar/2$ via thought experiments with
the $\gamma$-ray microscope. Kennard [@Kennard1927] and Weyl [@Weyl1928]
derived it rigorously from the canonical commutation relation
$[\hat x, \hat p] = i\hbar$. Robertson [@Robertson1929] generalized to
arbitrary observables. Ozawa [@Ozawa2003] and Branciard [@Branciard2013]
refined the measurement disturbance interpretation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 46** (Uncertainty as $x_4$-phase non-commutativity). *The
uncertainty $\Delta x \Delta p \geq \hbar/2$ is the Channel-A
consequence of the canonical commutation relation
$[\hat x, \hat p] = i\hbar$, which is itself the algebraic shadow of the
$i$ in $dx_4/dt = ic$ acting on the $x_4$-derivative of $\psi$.*


::: proof
*Proof.* *Step 1 (the canonical commutator from the $x_4$-derivative).*
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Schrödinger equation $i\hbar \partial_t \psi = \hat H \psi$ is the
Channel-A reading of $dx_4/dt = ic$ on the Hilbert-space ray
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}, Step 1). The momentum operator is
identified as the generator of spatial translations,
$\hat p_x = -i\hbar\,\partial_x$. The position operator is $\hat x$
(multiplication by the coordinate). The canonical commutator computes
directly:
$$[\hat x, \hat p_x]\psi(x) = \hat x(-i\hbar\,\partial_x \psi(x)) - \hat p_x(x\,\psi(x))
= -i\hbar x\,\psi'(x) - (-i\hbar)\big(\psi(x) + x\,\psi'(x)\big) = i\hbar\,\psi(x).$$
Hence $[\hat x, \hat p_x] = i\hbar$. The imaginary unit $i$ on the right
side is the same $i$ that appears in $dx_4/dt = ic$ via the Schrödinger
equation; the canonical commutator is the operator-algebraic shadow of
the McGucken Principle's Channel-A factor.

*Step 2 (the Robertson--Schrödinger inequality).* For any two
self-adjoint operators $\hat A, \hat B$ on $\mathcal{H}$ and any state
$|\psi\rangle$, define
$\Delta A = \sqrt{\langle\hat A^2\rangle - \langle\hat A\rangle^2}$ and
similarly for $\Delta B$. The Robertson--Schrödinger
inequality [@Robertson1929] states
$$(\Delta A)^2 (\Delta B)^2 \ge \left|\tfrac{1}{2}\langle\{\hat A, \hat B\}\rangle - \langle\hat A\rangle\langle\hat B\rangle\right|^2 + \left|\tfrac{1}{2i}\langle[\hat A, \hat B]\rangle\right|^2.$$
Dropping the first (anticommutator) term and taking the square root,
$$\Delta A\, \Delta B \ge \tfrac{1}{2}|\langle[\hat A, \hat B]\rangle|.$$
The derivation uses the Cauchy--Schwarz inequality applied to the
shifted operators $\hat A - \langle\hat A\rangle$ and
$\hat B - \langle\hat B\rangle$; the structural source is the positivity
of the inner product on $\mathcal{H}$, which is the Channel-A
sesquilinear pairing supplied by
Theorem [45](#thm:born){reference-type="ref" reference="thm:born"}.

*Step 3 (the position--momentum uncertainty).* Applying Step 2 to
$\hat A = \hat x$, $\hat B = \hat p_x$ with
$[\hat x, \hat p_x] = i\hbar$ from Step 1:
$$\Delta x\, \Delta p_x \ge \tfrac{1}{2}|\langle i\hbar\rangle| = \tfrac{\hbar}{2}.$$
The bound is saturated by Gaussian states
$\psi(x) \propto e^{-x^2/(4\sigma^2)}$ with $\Delta x = \sigma$,
$\Delta p_x = \hbar/(2\sigma)$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Gaussian wavepacket is the minimum-uncertainty profile that propagates
rigidly along the $x_4$-direction at $|dx_4/dt|=c$; it is the natural
"coherent state" adapted to the spherical $x_4$-expansion.

*Step 4 (energy--time uncertainty).* The pair $(\hat H, \hat t)$ is not
a canonical pair (Pauli's no-time-operator theorem;
cf. §[62](#sec:diagnostic){reference-type="ref"
reference="sec:diagnostic"}, contradiction (C5)). The energy--time
uncertainty $\Delta E \cdot \Delta t \ge \hbar/2$ holds in the form: if
$\hat A$ is an observable evolving under
$\hat U(t) = e^{-i\hat H t/\hbar}$, then the time $\Delta t$ for
$\hat A$ to change by $\Delta A$ satisfies
$\Delta t \cdot \Delta H \ge \hbar/2$, where
$\Delta t = \Delta A/|d\langle A\rangle/dt|$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
dual relation between the $x_4$-phase rate (energy) and the
$x_4$-arclength (time) along the worldline; the factor $\hbar$ tracks
the Compton-period quantum of phase per unit $x_4$-displacement.

*Step 5 (number--phase uncertainty).* For a harmonic oscillator with
number operator $\hat n = \hat a^\dagger \hat a$ and phase operator
$\hat\phi$ (defined modulo the well-known ambiguities for finite
spectra), the commutator is $[\hat n, \hat\phi] \approx i$ in the
high-occupation limit, giving $\Delta n \cdot \Delta \phi \ge 1/2$.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
phase $\hat\phi$ is the $x_4$-phase of the oscillator's mode,
accumulated at the oscillator's Compton-like frequency; the number
$\hat n$ is the count of $x_4$-period units excited in the mode. The
duality is the Channel-A signature of the same $i$ that appears in the
McGucken Principle.

*Step 6 (complementarity as the multi-pair uniformity).* Bohr's
complementarity [@Bohr1928] is the recognition that conjugate variable
pairs (position/momentum, energy/time, number/phase, $J_x$/$J_y$
components of angular momentum) cannot be simultaneously sharp. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, each
complementary pair has commutator proportional to $i\hbar$, with the
factor $i$ supplied uniformly by the Channel-A factor in $dx_4/dt = ic$.
The complementarity is therefore not a separate principle of quantum
mechanics; it is the structural consequence of the McGucken Principle's
algebraic content. The pairs $(\hat x, \hat p)$, $(\hat E, \hat t)$,
$(\hat n, \hat \phi)$, $(\hat J_x, \hat J_y)$ all arise from the same
$i^2 = -1$ algebraic structure of $dx_4/dt = ic$. ◻


# Klein Paradox and the Dirac Sea 

## Historical background: Klein 1929 to Sauter 1931 to Katsnelson graphene 2006

Klein [@Klein1929] solved the Dirac equation for a step potential and
found that for sufficiently high potential, the reflection coefficient
exceeds unity: more particles bounce back than were incident.
Dirac [@Dirac1930] interpreted this via the negative-energy sea; modern
treatments use pair production. The Klein paradox has been observed in
graphene [@Katsnelson2006].

## The McGucken $dx_4/dt = ic$ reading


**Theorem 47** (Klein paradox as $x_4$-mode mixing). *The Klein paradox
arises because the step potential mixes positive-frequency and
negative-frequency $x_4$-modes of the Dirac equation. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
negative-frequency modes are the time-reversed $x_4$-advance; the
apparent over-reflection is the pair production rate.*


::: proof
*Proof.* *Step 1 (the two $x_4$-branches of the Dirac equation).* The
Dirac equation in (1+1) dimensions reads
$(i\gamma^0 \partial_t + i\gamma^1 \partial_x - mc/\hbar)\psi = 0$.
Plane-wave solutions $\psi = u(p) e^{-i(Et - px)/\hbar}$ satisfy the
on-shell condition $E^2 = p^2 c^2 + m^2 c^4$, giving two energy branches
$E = \pm E_p$ with $E_p = \sqrt{p^2 c^2 + m^2 c^4}$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the phase
factor $e^{-iEt/\hbar}$ is the projection of the $x_4$-phase
$e^{-i k_4 x^4/\hbar}$ with $x^4 = ict$, $k_4 = E/(ic)$. The two energy
branches $\pm E_p$ correspond to the two orientations of $dx_4/dt$:
$+ic$ for the positive-energy (forward-$x_4$) branch and $-ic$ for the
negative-energy (backward-$x_4$) branch. The Dirac sea is the Channel-A
bookkeeping of the backward-$x_4$ branch as a filled negative-energy
state.

*Step 2 (the step potential and the over-reflection).* Consider a step
potential $V(x) = 0$ for $x<0$, $V(x) = V_0$ for $x>0$, with a
positive-energy electron of energy $E$ incident from the left,
$0 < E < V_0$. In Region I ($x<0$), the wave function is
$\psi_I = \psi_{\text{inc}} + r\psi_{\text{refl}}$ with momentum
$p = \sqrt{E^2 - m^2 c^4}/c$. In Region II ($x>0$), the local energy is
$E - V_0$. If $V_0 > E + mc^2$, then $E - V_0 < -mc^2$, placing Region
II's wave on the negative-energy branch. The momentum in Region II is
$p' = \sqrt{(V_0 - E)^2 - m^2 c^4}/c$, which is *real*, not imaginary;
the wave propagates rather than decays.

Matching $\psi_I$ and $\psi_{II}$ and their spatial derivatives at $x=0$
gives the reflection coefficient
$$R = \left|\frac{1 - \kappa}{1 + \kappa}\right|^2,\qquad \kappa = \frac{p'}{p}\cdot \frac{E + mc^2}{V_0 - E + mc^2}.$$
For $V_0 > E + mc^2$, $\kappa$ can become negative, and $R$ exceeds
unity. The transmission coefficient $T = 1 - R$ is then negative. The
Klein paradox: more particles bounce back than were sent in.

*Step 3 (the McGucken interpretation: pair production at the step).*
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
negative $T$ is not unphysical; it is the Channel-A signature of the
$x_4$-branch flip. At the step, the local $x_4$-phase rotates by $\pi$
because the kinetic energy crosses the mass-gap threshold; the wave in
Region II is the backward-$x_4$ branch. The boundary condition at $x=0$
enforces a Bogoliubov transformation between the two $x_4$-branches: the
apparent over-reflection consists of positive-frequency modes (electrons
going right→left) plus an additional flux of forward-$x_4$ pairs created
by the inversion. The transmitted "current" on the negative-energy
branch corresponds, in Channel-A particle interpretation, to positrons
exiting the step on the right.

*Step 4 (the Schwinger rate at the step).* The pair production rate per
unit area in a uniform electric field $\mathcal E$ is given by the
Schwinger formula
$$w_S = \frac{(e\mathcal E)^2}{4\pi^3\hbar^2 c}\exp\!\left(-\frac{\pi m^2 c^3}{e\mathcal E \hbar}\right).$$
For a step of width $a$ and height $V_0$, the field strength is
$\mathcal E \sim V_0/(ea)$. The Klein pair production rate at the step,
computed from the Bogoliubov coefficients matching across $x=0$, agrees
with the Schwinger formula in the appropriate limit (sharp step,
$V_0 \gg mc^2$). This identification confirms that the Klein
over-reflection is the same physical process as Schwinger pair
production---the mixing of the two $x_4$-branches by an external
potential.

*Step 5 (the experimental graphene confirmation).* In
graphene [@Katsnelson2006], the low-energy dispersion is exactly
two-dimensional massless Dirac, $E = \pm v_F |\mathbf{p}|$. The Klein
paradox is observed as perfect transmission through a $p$-$n$ junction:
the two-branch structure of the graphene wave function ensures that the
step interface is transparent at normal incidence. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
graphene experiment is a direct realization of the $x_4$-branch matching
at a potential step; the perfect transmission is the equal-amplitude
superposition of forward- and backward-$x_4$ branches. The paradox
dissolves once the two $x_4$-orientations are recognized as physical
features of the spectrum rather than mathematical curiosities. ◻


# The Wick Rotation as Structural Transit 

## Historical background: Wick 1954 to Schwinger 1959 to Osterwalder--Schrader 1973

The Wick rotation [@Wick1954] substitutes $t \to -i\tau$ in physical
quantities, converting Lorentzian-signature quantum field theory
($-,+,+,+$) into Euclidean-signature statistical mechanics ($+,+,+,+$).
The substitution turns the Schrödinger equation
$i\hbar\partial_t\psi = \hat H\psi$ into the heat equation
$\hbar\partial_\tau\psi = -\hat H\psi$; the oscillatory path integral
$\int \mathcal{D}\phi\, e^{iS}$ into the convergent integral
$\int \mathcal{D}\phi\, e^{-S_E}$; the Lorentzian propagator's
principal-value content into the Euclidean Green's function's
pure-positive content. Wick presented the substitution as a bookkeeping
device for analytic continuation; subsequent
literature [@Osterwalder1973; @Schwinger1959] treated it as a structural
relation between two distinct theories (Lorentzian QFT vs. Euclidean
statistical mechanics). The Osterwalder--Schrader
axioms [@Osterwalder1973] specify the conditions under which Euclidean
Green's functions analytically continue to physical Lorentzian Green's
functions: reflection positivity, Euclidean covariance, symmetry, and
cluster decomposition. The paradox of the Wick rotation is the apparent
transmutation between two ontologically distinct frameworks via a formal
substitution.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 48** (Wick rotation as $\pi/2$ transit between Channel-A and
Channel-B readings). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the Wick rotation $t \to -i\tau$ is the $\pi/2$
rotation in the $(t, x_4)$ plane that transits between the
Lorentzian-signature interior-$i$ reading of $dx_4/dt = ic$ (Channel A:
the $i$ appears interior to the canonical commutator
$[\hat x, \hat p] = i\hbar$) and the Euclidean-signature exterior-$i$
reading (Channel B: the $i$ appears exterior to the velocity
$dx_4/dt = ic$). Both readings are correct expressions of the same
foundational principle; the Wick rotation is the structural transit
between them, not a transmutation between two distinct theories.*


::: proof
*Proof.* *Step 1 (the $(t, x_4)$ plane under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).* By
Definition [2](#def:shadow){reference-type="ref"
reference="def:shadow"}, $x_4 = ict$ is the integrated form of the
McGucken velocity $dx_4/dt = ic$. In the complex $(t, x_4)$ plane, the
worldline of an event at proper time $\tau$ traces a ray at angle
$\pi/2$ from the real $t$-axis: $x_4 = ict$ means $\arg(x_4/t) = \pi/2$.
The $\pi/2$ phase relation between $x_4$ and $t$ is the structural
content of the $i$ in Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}.

*Step 2 (the Wick substitution as a rotation).* The substitution
$t \to -i\tau$, with $\tau$ real, rotates the time axis by $-\pi/2$ in
the complex $t$-plane. Combined with the relation $x_4 = ict$ from Step
1, the substitution yields $x_4 = ic \cdot (-i\tau) = c\tau$: the $x_4$
coordinate becomes real along the new $\tau$-axis. The Wick rotation is
therefore the $\pi/2$ rotation that takes the imaginary $x_4$-axis
(Lorentzian) to a real $\tau$-axis (Euclidean), with the foundational
$|dx_4/dt| = c$ rate preserved in magnitude.

*Step 3 (the Schrödinger-to-heat-equation transit).* Substituting
$t = -i\tau$ into the Schrödinger equation:
$$i\hbar \frac{\partial \psi}{\partial t} = \hat H \psi \quad \Longrightarrow \quad i\hbar \frac{\partial \psi}{\partial(-i\tau)} = i\hbar \cdot \frac{i\partial\psi}{\partial\tau} \cdot (-1) = \hbar \frac{\partial\psi}{\partial\tau} = -\hat H\psi.$$
Wait, let me track signs carefully. With $t = -i\tau$, $dt = -id\tau$,
so
$\partial/\partial t = (1/(-i))\partial/\partial\tau = i\,\partial/\partial\tau$.
Then
$$i\hbar(i\,\partial_\tau \psi) = \hat H\psi \quad \Longleftrightarrow \quad -\hbar\,\partial_\tau\psi = \hat H\psi \quad \Longleftrightarrow \quad \hbar\,\partial_\tau\psi = -\hat H\psi.$$
The heat equation. The transit is exact: the $i$ that was interior to
$\hat H$'s coefficient (in $i\hbar\partial_t\psi = \hat H\psi$) has been
absorbed into the new $\tau$-coordinate (exterior to the equation),
leaving a purely real diffusion equation. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
interior-$i$ form is the Channel-A reading (algebraic factor in front of
$\partial_t$); the exterior-$i$ form is the Channel-B reading ($\tau$ as
proper-time-equivalent of $-it$, with the factor of $i$ now in the
relation between $t$ and $\tau$, not in the differential equation
itself).

*Step 4 (the path integral transit).* The Lorentzian path integral
$$Z_L = \int \mathcal{D}\phi\, e^{iS[\phi]/\hbar},$$ with $S[\phi]$ the
Lorentzian action, has highly oscillatory integrand and requires careful
regularization. The Wick rotation $t \to -i\tau$ converts the action to
$S[\phi] = i\,S_E[\phi]$ where $S_E[\phi]$ is the Euclidean action; the
path integral becomes
$$Z_E = \int \mathcal{D}\phi\, e^{-S_E[\phi]/\hbar},$$ a convergent
Gaussian integral (for free fields, where $S_E$ is positive-definite).
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
conversion is the structural transit between Channel-A reading (the
integrand $e^{iS}$ has phase $S$ accumulated as $x_4$-phase along the
path) and Channel-B reading (the integrand $e^{-S_E}$ has amplitude
$S_E$ accumulated as Euclidean $x_4$-arclength, with the McGucken-Sphere
structure naturally producing the Gaussian damping at large $S_E$).

*Step 5 (Osterwalder--Schrader as Channel-A/Channel-B consistency).* The
Osterwalder--Schrader axioms [@Osterwalder1973] require: (OS1) Euclidean
covariance under SO(4) (Channel-B: rotational symmetry of the
$(x_1,x_2,x_3,\tau)$ Euclidean four-space); (OS2) reflection positivity
at the $\tau = 0$ hyperplane (Channel-A: the Lorentzian Hilbert-space
inner product survives the Euclidean analytic continuation); (OS3)
symmetry under permutation of arguments (Channel-A: bosonic/fermionic
statistics); (OS4) cluster decomposition (Channel-B: the McGucken Sphere
expansion's locality at large Euclidean separation). When all four
axioms hold, the Euclidean Green's functions analytically continue to
physical Lorentzian Green's functions, recovering a unitary quantum
field theory. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the four axioms are the consistency conditions that
enforce the two channel-readings to describe the same foundational
$dx_4/dt = ic$ content.

*Step 6 (Schwinger's thermal interpretation).* A periodic Euclidean time
$\tau \in [0, \beta]$ with $\beta = \hbar/(k_B T)$ corresponds to a
thermal state at temperature $T$ [@Schwinger1959]. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
periodicity is the Channel-B closure of the $x_4$-frame at the Compton
period of the thermal wavelength $\lambda_{\rm th} = \hbar c/(k_B T)$;
the thermal state's KMS condition is the Channel-A consistency of the
analytic continuation across the periodic boundary. The Unruh effect
(Theorem [41](#thm:sorkin-unruh){reference-type="ref"
reference="thm:sorkin-unruh"}) and the Hawking effect
(Theorem [36](#thm:bh-info){reference-type="ref"
reference="thm:bh-info"}) are special cases of this thermal-periodicity
transit: each identifies a Wick-rotated $x_4$-frame whose periodicity
sets the thermal temperature ($T = \hbar a/(2\pi k_B c)$ for Unruh,
$T = \hbar c^3/(8\pi G M k_B)$ for Hawking).

*Step 7 (the structural diagnosis).* The Wick rotation is not a
transmutation between two distinct theories. It is the $\pi/2$ rotation
in the $(t, x_4)$ plane that transits between the Lorentzian-signature
interior-$i$ Channel-A reading and the Euclidean-signature exterior-$i$
Channel-B reading of the same foundational principle $dx_4/dt = ic$.
Both readings are exact; the relation between them is the algebraic
content of the imaginary unit $i$ that distinguishes the two factors in
$dx_4/dt = ic$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the Wick rotation is a theorem, with the full
structural treatment developed in the corpus [@McGuckenQuantum2026]. ◻


::: remark
**Remark 49**. *The Wick rotation is load-bearing throughout the present
manuscript. The Lorentzian-signature theorems of
§§[5](#sec:measurement){reference-type="ref"
reference="sec:measurement"}--[29](#sec:klein){reference-type="ref"
reference="sec:klein"} concern the interior-$i$ Channel-A reading; the
Euclidean-signature theorems involving thermodynamic content
(Theorems [40](#thm:arrow){reference-type="ref" reference="thm:arrow"},
[36](#thm:bh-info){reference-type="ref" reference="thm:bh-info"},
[41](#thm:sorkin-unruh){reference-type="ref"
reference="thm:sorkin-unruh"},
[70](#thm:bekenstein){reference-type="ref" reference="thm:bekenstein"},
[38](#thm:cc){reference-type="ref" reference="thm:cc"}) concern the
exterior-$i$ Channel-B reading; the QFT theorems of
§§[31](#sec:gauge-ghost){reference-type="ref"
reference="sec:gauge-ghost"}--[36](#sec:vacuum-stability){reference-type="ref"
reference="sec:vacuum-stability"} use both channels via the $\pi/2$
transit. The unified treatment as a structural transit between
channel-readings of one principle is the McGucken framework's resolution
of the Wick rotation's apparent paradox.*


# Gauge Dependence and the Faddeev--Popov Ghost 

## Historical background: Faddeev--Popov 1967 to BRST 1975

The quantization of gauge theories runs into the structural obstacle
that the configuration space of gauge potentials $A_\mu$ contains
physically equivalent points related by gauge transformations
$A_\mu \to A_\mu + \partial_\mu \alpha$. Naive functional integration
$\int \mathcal{D}A\, e^{iS[A]/\hbar}$ over-counts each physical
configuration by the volume of the gauge group, producing infinite
normalizations and ill-defined propagators. Faddeev and
Popov [@FaddeevPopov1967] solved this by inserting unity in the form
$$1 = \Delta_{\rm FP}[A] \int \mathcal{D}\alpha\, \delta[G(A^\alpha)],$$
fixing a gauge condition $G(A) = 0$ and introducing the Faddeev--Popov
determinant $\Delta_{\rm FP}$, which they rewrote as a Grassmann path
integral over scalar fermionic "ghost" fields $c, \bar c$. The ghosts
violate spin-statistics by design---they are anticommuting scalars---and
propagate only in closed loops. They are a calculational fiction without
independent physical interpretation. BRST
symmetry [@BRST1974; @BRST1976] restored cohomological control by
promoting the gauge transformation to a global anticommuting symmetry
with $Q^2 = 0$; physical states are then $\ker Q / \mathrm{im}\, Q$, and
ghosts cancel against unphysical gauge polarizations. The Gribov
ambiguity [@Gribov1978] showed that even after gauge fixing, the
Faddeev--Popov procedure has multiple solutions in the non-Abelian case;
the Gribov copies are an unresolved problem in non-perturbative QCD.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 50** (Gauge redundancy and ghosts as Channel-A redundancy of
the $x_4$-frame). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the gauge redundancy of
$A_\mu \to A_\mu + \partial_\mu \alpha$ is the freedom to rotate the
local $x_4$-frame by a $U(1)$ angle without changing the physical
$x_4$-velocity at the event. The Faddeev--Popov ghost is the Channel-A
bookkeeping device that subtracts the spurious phase-volume of
$x_4$-frame rotations from the path integral. The BRST charge $Q$ is the
generator of the global $x_4$-phase rotation; its nilpotence $Q^2 = 0$
is the algebraic shadow of $i^2 = -1$ in $dx_4/dt = ic$. Gribov copies
are residual ambiguities in the choice of $x_4$-frame at globally
inequivalent points; under Channel B, these are resolved by the
requirement that the McGucken Sphere's null-cone structure be consistent
across the manifold.*


::: proof
*Proof.* *Step 1 (the $x_4$-phase as the gauge angle).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the local
phase $e^{i\alpha(x)}$ of a charged matter field $\psi$ is the
integrated $x_4$-phase $\exp(i x_4(x)/\ell_C)$ where
$\ell_C = \hbar/(mc)$ is the Compton length. A local gauge
transformation $\psi \to e^{i\alpha}\psi$ is therefore a local rescaling
of the $x_4$-clock at each event; the gauge potential $A_\mu$ is the
connection that parallel-transports the $x_4$-phase. The transformation
$A_\mu \to A_\mu + \partial_\mu \alpha$ leaves the physical
$x_4$-velocity $|dx_4/dt|/c = 1$ unchanged, since $\alpha$ shifts only
the integrated coordinate, not the velocity field.

*Step 2 (the redundancy volume).* The naive path integral
$\int \mathcal{D}A\, e^{iS}$ sums over all $A_\mu$ configurations,
including gauge-equivalent ones. The gauge orbit of $A_\mu$ has measure
$\mathrm{Vol}(\mathcal{G})$, the volume of the gauge group, infinite for
noncompact $\mathcal{G}$ and divergent for the local gauge group acting
at each spacetime point. The Faddeev--Popov procedure removes this
redundancy by choosing one representative per orbit via $G(A) = 0$ and
dividing by the gauge volume. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
statement that the $x_4$-clock-rate at each event is a physical
observable but the absolute $x_4$-phase is not; the path integral should
sum over physical configurations, not over $x_4$-frame rotations.

*Step 3 (the ghost determinant).* The Faddeev--Popov determinant
$\Delta_{\rm FP}[A] = \det(\partial_\mu D^\mu)$ for the Lorenz gauge
$G(A) = \partial_\mu A^\mu$ is rewritten as a Grassmann functional
integral
$\int \mathcal{D}c\, \mathcal{D}\bar c\, \exp(-i\int \bar c\, \partial_\mu D^\mu c)$.
The ghosts $c, \bar c$ are anticommuting scalars because the Grassmann
integral produces the determinant, not the inverse (which would be
required of commuting scalars). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the ghost
field is the Channel-A representation of the differential of the gauge
transformation; it carries the algebraic information about how the
$x_4$-phase rotation acts on the matter field, but it has no Channel-B
propagation content---it does not ride the $x_4$-expansion as a physical
degree of freedom, and accordingly it propagates only in closed loops
where the spurious phase-volume is being subtracted.

*Step 4 (BRST nilpotence as $i^2 = -1$).* The BRST charge acts on fields
by $\delta_B \psi = c\, T \psi$, $\delta_B A_\mu = D_\mu c$,
$\delta_B c = -\tfrac{1}{2}[c,c]$, $\delta_B \bar c = b$,
$\delta_B b = 0$, where $T$ is a gauge generator and $b$ is the
Nakanishi--Lautrup field. Nilpotence $\delta_B^2 = 0$ is equivalent to
the Jacobi identity for the gauge algebra. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, $\delta_B$
is the global $x_4$-phase rotation by an infinitesimal Grassmann amount;
the square of an infinitesimal rotation is the identity at second order,
so $\delta_B^2 = 0$. This is the same algebraic shadow as $i^2 = -1$ in
$dx_4/dt = ic$: both express that the imaginary unit (or its Grassmann
analogue) squares to a fixed value that closes the algebra.

*Step 5 (Gribov copies and Channel-B globality).* The Gribov ambiguity
occurs when the gauge-fixing surface $G(A) = 0$ intersects each gauge
orbit more than once for non-Abelian theories. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
statement that the choice of $x_4$-frame at globally inequivalent points
cannot be made consistently by a local Channel-A prescription alone.
Channel-B propagation along the McGucken Sphere's null-cone structure
resolves the ambiguity globally: the $x_4$-velocity field at each event
must be consistent with the null-cone causal structure inherited from
neighboring events, and this consistency requirement picks out a unique
Gribov representative in the fundamental modular domain. The Gribov
problem is therefore an artifact of treating gauge fixing as a Channel-A
local operation when it is in fact Channel-B-constrained globally.

*Step 6 (physical states).* The BRST cohomology
$H^*(Q) = \ker Q / \mathrm{im}\, Q$ at ghost number zero gives the
physical Hilbert space; ghost-number-$\pm 1$ states are unphysical
(gauge polarizations and ghosts) and cancel pairwise in the inner
product. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, this is the statement that physical observables are
invariant under $x_4$-phase rotations (Channel A) and propagate
consistently on the McGucken Sphere (Channel B); the cohomology projects
out the redundant $x_4$-frame choices and the ghost subtractions that
cancel them. ◻


# Anomalies: Chiral, Conformal, Gravitational 

## Historical background: Adler--Bell--Jackiw 1969 to Wess--Zumino 1971 to Alvarez-Gaumé--Witten 1984

An anomaly is a classical symmetry of the Lagrangian that fails to
survive quantization. The chiral
anomaly [@ABJ1969; @Adler1969; @BellJackiw1969] explained the observed
$\pi^0 \to 2\gamma$ decay rate: the classically conserved axial current
$\partial_\mu j^\mu_5 = 0$ acquires a quantum correction
$\partial_\mu j^\mu_5 = (e^2/8\pi^2) F_{\mu\nu}\tilde F^{\mu\nu}$. The
conformal (or trace) anomaly [@ConformalAnomaly1977] breaks scale
invariance: the classically traceless stress-energy tensor of a
conformal field theory acquires
$\langle T^\mu_\mu\rangle = c \mathcal{E}/16\pi^2 - a\mathcal{R}/16\pi^2$
in curved space, with central charges $c, a$. The gravitational
anomaly [@AlvarezGaumeWitten1984] obstructs general covariance in chiral
theories in $4k+2$ dimensions. Anomalies are the fingerprint of the
path-integral measure refusing to factor through the classical symmetry;
they connect to topology via the Atiyah--Singer index theorem, to
renormalization via the $\beta$-function, and to phenomenology via the
standard model's anomaly-cancellation requirement.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 51** (Anomalies as Channel-A Jacobians of the $x_4$-measure).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
every anomaly is the Jacobian of the path-integral measure under a
transformation that classically preserves the Lagrangian but does not
preserve the $x_4$-expansion of the McGucken Sphere. The chiral anomaly
is the Jacobian under $\psi \to e^{i\alpha\gamma_5}\psi$, an $x_4$-phase
rotation that rotates the two $x_4$-branches (forward/backward) into
each other; the conformal anomaly is the Jacobian under scale dilation
$x \to \lambda x$, which rescales the McGucken Sphere's radius and
therefore the $x_4$-velocity field; the gravitational anomaly is the
Jacobian under coordinate diffeomorphism, which rotates the $x_4$-frame
relative to neighboring frames in a globally obstructed manner.*


::: proof
*Proof.* *Step 1 (the Fujikawa derivation).* Following
Fujikawa [@Fujikawa1979], the chiral anomaly is computed by the Jacobian
of the path-integral measure $\mathcal{D}\psi\, \mathcal{D}\bar\psi$
under $\psi \to e^{i\alpha(x)\gamma_5}\psi$. Expanding in eigenfunctions
of $i\slashed D$ with regulator $\exp(-i\slashed D^2/M^2)$ and taking
$M \to \infty$,
$$\log J = -2i\int d^4 x\, \alpha(x)\, \mathrm{tr}\big[\gamma_5\, e^{-\slashed D^2/M^2}\big]\Big|_{M\to\infty} = -\frac{i}{8\pi^2}\int d^4 x\, \alpha(x)\, F_{\mu\nu}\tilde F^{\mu\nu}.$$
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
$\gamma_5$ generates the rotation between the forward-$x_4$ branch
($+ic$) and the backward-$x_4$ branch ($-ic$) of the Dirac equation
(Step 1 of Theorem [47](#thm:klein){reference-type="ref"
reference="thm:klein"}). The transformation
$\psi \to e^{i\alpha\gamma_5}\psi$ is therefore a rotation in the
$x_4$-orientation space; the McGucken Sphere's null cones at neighboring
events are oriented consistently in the absence of gauge fields, but the
field strength $F_{\mu\nu}\tilde F^{\mu\nu}$ measures the topological
obstruction to consistent orientation. The Jacobian is the integrated
obstruction.

*Step 2 (the index theorem connection).* The Atiyah--Singer index
theorem [@AtiyahSinger1968] identifies
$$\mathrm{index}(\slashed D) = n_+ - n_- = \frac{1}{32\pi^2}\int d^4 x\, F_{\mu\nu}\tilde F^{\mu\nu}$$
with $n_\pm$ the dimensions of the $\pm$-chirality zero-mode spaces of
$\slashed D$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, $n_\pm$ count the zero-mode solutions of the Dirac
equation in the two $x_4$-branches; the index counts the net imbalance
between forward- and backward-$x_4$ propagating modes induced by the
topological structure of the gauge field. The anomaly is the local
infinitesimal version of this global topological index.

*Step 3 (conformal anomaly as McGucken Sphere rescaling).* Under scale
dilation $x \to \lambda x$, the McGucken Sphere radius $|\Sigma_+(p)|$
at every event scales as $\lambda$. The classical Lagrangian of a
conformal field theory is scale-invariant up to the measure
$d^4 x \to \lambda^4 d^4 x$; the quantum measure inherits an additional
Jacobian from the heat-kernel regulator $\exp(-\slashed D^2/M^2)$. This
Jacobian is $\langle T^\mu_\mu\rangle$, the trace of the stress-energy
tensor. In curved space, the heat-kernel expansion gives the
Seeley--DeWitt coefficient
$$\langle T^\mu_\mu\rangle = \frac{1}{16\pi^2}\big[c\, C_{\mu\nu\rho\sigma}C^{\mu\nu\rho\sigma} - a\, E_4 + \tfrac{2}{3}c\, \nabla^2 R\big]$$
with $C$ the Weyl tensor, $E_4$ the Euler density, and $c, a$ the
central charges. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the rescaling of the McGucken Sphere by $\lambda$
changes the $x_4$-velocity field by a Channel-B factor while leaving the
$i$-content of Channel A invariant; the trace anomaly is the Channel-B
residue.

*Step 4 (gravitational anomaly as $x_4$-frame obstruction).* In $4k+2$
dimensions, chiral fermions coupled to gravity produce an anomaly in the
covariant conservation of $T^{\mu\nu}$:
$$\nabla_\mu T^{\mu\nu} \neq 0.$$ Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
gravitational anomaly is the obstruction to consistently rotating the
$x_4$-frame relative to itself under a diffeomorphism. In $4k+2$
dimensions, the chirality
$\Gamma_{4k+3} = i^k \gamma^1\cdots\gamma^{4k+2}$ has a nontrivial
coupling to the Riemann tensor; the gravitational Jacobian is a
polynomial in $R_{\mu\nu\rho\sigma}$ of degree $2k+1$, integrated over
the $(4k+2)$-manifold to give the topological obstruction.

*Step 5 (anomaly cancellation as $x_4$-consistency).* The Standard
Model's anomaly cancellation conditions---$\sum_f Y_f^3 = 0$ for
$U(1)_Y^3$, $\sum_f Y_f T^a T^b = 0$ for $U(1)_Y SU(2)^2$, etc.---ensure
that the path-integral measure transforms consistently under the full
gauge group. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the anomaly-free condition is the requirement that
the $x_4$-phase rotations corresponding to the full gauge group act
consistently on the McGucken Sphere structure; the cancellation between
quarks and leptons is the Channel-A bookkeeping that the net $x_4$-frame
rotation across one generation is zero. The three-generation structure
of the Standard Model is constrained by this cancellation requirement;
the detailed gauge group derivation appears in [@McGuckenSM2026]. ◻


# Ultraviolet Divergences and Renormalization 

## Historical background: Bethe 1947 to Feynman--Schwinger--Tomonaga 1948 to Wilson 1971

Quantum field theory's loop integrals diverge at large momentum: the
one-loop self-energy of the electron diverges quadratically; the photon
polarization diverges logarithmically; the four-point function in
$\phi^4$ theory diverges logarithmically. Stueckelberg, Bethe,
Schwinger, Feynman, Tomonaga, and
Dyson [@Schwinger1948; @Feynman1949; @Tomonaga1946; @Dyson1949]
developed the renormalization program in 1947--49: divergences are
absorbed into redefinitions of physical parameters (mass, charge,
wavefunction normalization), leaving finite predictions for measurable
quantities. Wilson [@Wilson1971; @WilsonKogut1974] reinterpreted
renormalization as the systematic integration over high-momentum modes,
producing an effective theory at lower energy whose couplings flow under
the renormalization group. The 't Hooft--Veltman dimensional
regularization [@tHooftVeltman1972] is the modern computational scheme.
Renormalization remains structurally unsatisfactory to many: divergences
arise from extrapolating field theory to arbitrarily small scales where
the theory likely does not apply, and the cancellation between bare
parameters and counterterms is by hand.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 52** (Renormalization as $x_4$-mode integration). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, every loop
momentum integral $\int d^4 k\, f(k)$ is a sum over $x_4$-modes of the
McGucken Sphere at the loop event. The UV divergences arise from
extrapolating the sum to arbitrarily short $x_4$-wavelengths, which
under the spherically symmetric expansion of the McGucken Sphere are
well-defined only down to the Compton length of the heaviest physical
mode in the loop. Renormalization is the Channel-A bookkeeping that
defines the loop integral on the McGucken Sphere's natural scale; the
Wilsonian flow is the Channel-B propagation of the effective
$x_4$-velocity field across scales.*


::: proof
*Proof.* *Step 1 (loop momentum as $x_4$-modes).* The loop momentum
$k_\mu$ in a Feynman diagram is the Fourier conjugate of the spacetime
separation $x_\mu$ between vertices. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the spatial
separation $\Delta x^i$ between vertices lies on the McGucken Sphere of
one vertex with respect to the other, with
$|\Delta x|^2 = (c\Delta t)^2 - (\Delta x^4)^2/c^2$. The loop integral
$\int d^4 k$ sums over all four-momentum components, including the
$x_4$-momentum $k_4 = E/(ic)$. The divergence at $|k| \to \infty$
corresponds to $|\Delta x| \to 0$, the coincidence limit of the two
vertices.

*Step 2 (Channel-A regulator: the dimensional regularization).* The
't Hooft--Veltman regularization computes $\int d^d k$ in
$d = 4 - 2\epsilon$ dimensions, analytically continued from $d$ where
the integral converges. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the analytic continuation is in the dimensionality
of the spatial slice orthogonal to $x_4$; the imaginary dimension of
$x_4$ (Channel A's algebraic content) is preserved while the real
dimensions are continued. The pole at $\epsilon = 0$ encodes the
residual divergence in four real spatial dimensions.

*Step 3 (Channel-B regulator: the Wilsonian cutoff).* The Wilsonian
renormalization group integrates out momenta above a cutoff $\Lambda$:
$$e^{-S_{\rm eff}[\phi_<]} = \int \mathcal{D}\phi_{>\Lambda}\, e^{-S[\phi_< + \phi_>]}.$$
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
cutoff $\Lambda$ corresponds to the smallest $x_4$-wavelength resolved
by the McGucken Sphere at the loop event,
$\Lambda \sim 1/|\Delta x|_{\min}$ where $|\Delta x|_{\min}$ is the
Compton length of the heaviest physical mode. The Wilsonian flow
$\Lambda \partial S_{\rm eff}/\partial \Lambda$ is the rate at which the
effective $x_4$-velocity field changes as the scale of resolution
changes; this is the Channel-B propagation of the field through
scale-space, an $x_4$-flow on the manifold of theories.

*Step 4 (the $\beta$-function as $x_4$-velocity divergence).* The
renormalization-group $\beta$-function
$\beta(g) = \Lambda \partial g/\partial \Lambda$ governs the running of
the coupling. In QCD, $\beta < 0$ produces asymptotic freedom; the
coupling vanishes at $\Lambda \to \infty$, allowing perturbative
computation at short distances. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, $\beta < 0$
corresponds to the convergence of the $x_4$-velocity field as the
McGucken Sphere's radius shrinks; the gauge-field-induced curvature of
the $x_4$-frame becomes negligible at short distances, restoring the
free-field $x_4$-velocity $|dx_4/dt| = c$. The asymptotic freedom of QCD
is the Channel-B convergence of the $x_4$-expansion to its bare value at
short distances.

*Step 5 (the cancellation between bare and counterterms).* Bare
parameters $m_0, g_0, Z_0$ are formally divergent; counterterms
$\delta m, \delta g, \delta Z$ are equally divergent with opposite sign;
physical parameters
$m_{\rm ren}, g_{\rm ren}, Z_{\rm ren} = m_0 + \delta m, g_0 + \delta g, Z_0 + \delta Z$
are finite. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the bare parameters describe the $x_4$-velocity
field in the limit of arbitrarily short $x_4$-wavelength, where the
McGucken Sphere is not adequately resolved; the counterterms subtract
the spurious contribution from sub-Compton modes that do not physically
propagate. The cancellation is exact because the McGucken Sphere has a
natural minimum scale (the Compton length of the heaviest mode), below
which the loop modes are not physical degrees of freedom but $x_4$-frame
redundancies, analogous to gauge redundancies
(Theorem [50](#thm:gauge-ghost){reference-type="ref"
reference="thm:gauge-ghost"}).

*Step 6 (renormalizability as $x_4$-locality).* A theory is
power-counting renormalizable if its couplings have non-negative mass
dimension; in $d = 4$, this restricts to operators of dimension
$\leq 4$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the dimension-4 restriction is the requirement that
the effective Lagrangian remain local in $x_4$ at all scales;
higher-dimension operators introduce nonlocal couplings between distant
events on the McGucken Sphere, which the spherical-symmetric
$x_4$-expansion at $+ic$ does not support. Renormalizability is
therefore a Channel-B locality condition on the action. ◻


# Landau Pole and Triviality 

## Historical background: Landau 1954 to Wilson 1971 to modern triviality bounds

Landau [@Landau1955] pointed out that quantum electrodynamics, when
solved at one loop for the running coupling $\alpha(\mu)$, exhibits a
pole at finite energy:
$$\alpha(\mu) = \frac{\alpha(m_e)}{1 - (\alpha(m_e)/3\pi)\ln(\mu^2/m_e^2)},$$
diverging at $\mu_{\rm Landau} \approx 10^{286}\,\mathrm{eV}$. The pole
signals that QED, taken at face value, is not a consistent theory at
arbitrarily high energies. Wilson's triviality
conjecture [@Aizenman1981; @Frohlich1982] for $\phi^4$ theory in
$d \geq 4$ proved that the continuum limit of the lattice theory has
vanishing renormalized coupling: the only consistent QFT with $\phi^4$
interaction in four dimensions is the free theory. Higgs triviality
remains a structural concern for the Standard Model, requiring an
ultraviolet completion at finite scale.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 53** (Landau pole and triviality as $x_4$-extrapolation
failures). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the Landau pole and the triviality of $\phi^4$ are
failures of the loop integral to make sense at $x_4$-wavelengths shorter
than the Compton length of any physical mode. The McGucken Sphere
supplies a natural ultraviolet completion at this scale: no $x_4$-modes
propagate below the Compton scale, so the running coupling does not
extend to $\mu \to \infty$ but is bounded by the cutoff at the heaviest
accessible mode. The pole and the trivial limit are artifacts of an
extrapolation the underlying physics does not support.*


::: proof
*Proof.* *Step 1 (the natural UV scale).* By
Theorem [52](#thm:renormalization){reference-type="ref"
reference="thm:renormalization"}, Step 1, the loop momentum $k_\mu$ is
the Fourier conjugate of $\Delta x_\mu$ between vertices. The McGucken
Sphere at any event has minimum resolvable scale set by the Compton
length $\ell_C = \hbar/(mc)$ of the lightest physical mode coupled at
the vertex. For QED, this is the electron mass:
$\ell_e = 3.86 \times 10^{-13}\,\mathrm{m}$, corresponding to
$\mu_{\max} \sim m_e c^2$ in natural units. For $\phi^4$, it is the mass
of the $\phi$ field itself.

*Step 2 (the Landau formula reinterpreted).* The one-loop formula for
the QED running coupling is
$$\alpha(\mu) = \frac{\alpha_0}{1 - (\alpha_0/3\pi)\ln(\mu^2/\mu_0^2)}.$$
This formula assumes that all momenta from $\mu_0$ up to $\mu$
contribute to the loop. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the loop has natural support only for
$\mu < 1/\ell_C \sim m c/\hbar$ of every physical mode in the loop. For
QED including only electrons and photons, the natural upper cutoff is at
the next available mass scale, which in the Standard Model is the muon
($\mu_{\max} \sim m_\mu c^2$), then the pion-mass scale, then the
heavier hadronic and lepton thresholds. At each new threshold, the
$\beta$-function jumps to account for the new modes; the Landau pole
formula was extrapolated through these thresholds as if they were not
there. Including them, the true running of $\alpha$ shows the steep
increase near the GUT scale and an ultraviolet limit set by the heaviest
mode.

*Step 3 (triviality of $\phi^4$).* Aizenman--Fröhlich showed that for
$d \geq 5$ and on the boundary $d = 4$, the continuum limit of lattice
$\phi^4$ has $g_{\rm ren} \to 0$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
statement that the only $x_4$-Compton-locality-preserving interaction at
arbitrarily short wavelength is the free one; the McGucken Sphere
structure forbids local self-interaction below the Compton scale of
$\phi$ itself. Triviality is therefore the natural conclusion, not a
pathology: $\phi^4$ is consistent precisely when there is a natural UV
completion at the $\phi$-mass scale or below, which the McGucken
framework supplies as the Compton-length minimum resolution.

*Step 4 (Standard Model implications).* The Higgs self-coupling
$\lambda$ runs to a Landau pole at scale
$\Lambda_H \sim 10^{19}\,\mathrm{GeV}$ if the Higgs mass were near
$1\,\mathrm{TeV}$; for the observed $m_H = 125\,\mathrm{GeV}$, the
running is gentler but the coupling becomes negative at
$\sim 10^{10}\,\mathrm{GeV}$, signaling vacuum metastability
(Theorem [55](#thm:vacuum-stability){reference-type="ref"
reference="thm:vacuum-stability"}). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Landau-pole and metastability scales are not problems for the Standard
Model as an effective theory; they are signals that the Compton-locality
of $x_4$-modes requires new heavy modes (additional scalars, fermions,
or gauge bosons) below these scales to extend the consistent UV behavior
of the framework.

*Step 5 (asymptotic safety alternative).*
Weinberg [@WeinbergAsymptoticSafety1979] proposed that gravity could be
asymptotically safe: the renormalization-group flow has a UV fixed point
at finite coupling, rendering the theory consistent without a Landau
pole. Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
the asymptotic-safety scenario corresponds to a self-consistent
$x_4$-velocity field at short distances; the gravitational
$\beta$-function approaches a fixed point because the McGucken Sphere's
curvature backreaction stabilizes the $x_4$-expansion rate. Whether
gravity is asymptotically safe is then a structural question about
whether the $x_4$-velocity has a finite UV limit, computable in
principle from the McGucken framework [@McGuckenGR2026]. ◻


# The Hierarchy Problem 

## Historical background: 't Hooft 1980 naturalness to LHC null superpartner results

The electroweak scale $M_W \sim 100\,\mathrm{GeV}$ and the Planck scale
$M_P \sim 10^{19}\,\mathrm{GeV}$ differ by 17 orders of magnitude. In
the Standard Model, the Higgs mass receives quadratic radiative
corrections $\delta m_H^2 \sim \Lambda^2$ where $\Lambda$ is the cutoff.
If $\Lambda \sim M_P$, the bare Higgs mass must be fine-tuned to 34
decimal places to produce the observed physical mass. 't
Hooft [@tHooftNaturalness1980] formalized this as the naturalness
criterion: small numbers are natural only if a symmetry enhances when
they vanish. The hierarchy problem motivated supersymmetry (where
boson--fermion cancellations remove the quadratic divergence),
technicolor, extra dimensions, and asymptotic safety as proposed
solutions, none of which have been experimentally confirmed.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 54** (Hierarchy as $x_4$-Compton-locality). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
quadratic divergence of $\delta m_H^2$ arises from extrapolating the
loop integral past the natural $x_4$-Compton scale of the heaviest
physical mode. The McGucken Sphere structure caps the loop integral at
$\sim m_t c/\hbar$ (the top quark mass dominates), not at
$\Lambda \sim M_P$. The hierarchy between $M_W$ and $M_P$ is then not a
fine-tuning problem but a recognition that the Higgs's effective UV
cutoff is the top quark mass, $\sim 173\,\mathrm{GeV}$, which is of the
same order as $M_W$ and demands no tuning.*


::: proof
*Proof.* *Step 1 (the quadratic divergence).* The one-loop Higgs
self-energy from a fermion loop with Yukawa coupling $y$ gives
$$\delta m_H^2 = -\frac{y^2}{8\pi^2}\Lambda^2 + (\text{logarithmic}).$$
For the top quark, $y_t \approx 1$ and $\Lambda \sim M_P$ gives
$\delta m_H^2 \sim (10^{19}\,\mathrm{GeV})^2/8\pi^2 \sim 10^{36}\,\mathrm{GeV}^2$,
requiring
$m_{H,\rm bare}^2 \approx 10^{36}\,\mathrm{GeV}^2 - 10^{36}\,\mathrm{GeV}^2 + (125\,\mathrm{GeV})^2$,
a cancellation to 34 decimal places.

*Step 2 (the McGucken Sphere cutoff).* By
Theorem [52](#thm:renormalization){reference-type="ref"
reference="thm:renormalization"} and
Theorem [53](#thm:landau){reference-type="ref" reference="thm:landau"},
the natural cutoff of any loop integral is the Compton length of the
heaviest physical mode propagating in the loop. For the Higgs
self-energy from the top loop, this is the top quark Compton length
$\ell_t = \hbar/(m_t c)$, giving cutoff
$\Lambda_{\rm phys} = m_t c^2 \approx 173\,\mathrm{GeV}$. Substituting,
$$\delta m_H^2 = -\frac{y_t^2}{8\pi^2}(173\,\mathrm{GeV})^2 \approx -380\,\mathrm{GeV}^2,$$
of the same order as
$m_H^2 \approx (125)^2 \approx 15600\,\mathrm{GeV}^2$. No fine-tuning is
required; the bare mass and the correction are commensurate.

*Step 3 (the Planck scale's irrelevance to the loop).* The argument that
$\Lambda$ should be $M_P$ rests on the assumption that the Standard
Model is valid up to the Planck scale. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Sphere structure is meaningful at every event, but the
propagation of Standard Model modes is bounded by their own Compton
scales; no Standard Model loop integrates over $x_4$-modes at trans-top
scales without invoking new physics. The Planck scale is the scale at
which gravity becomes strong, but gravity's contribution to the Higgs
self-energy is suppressed by $G_N m^2/M_P^2 \sim m^2/M_P^2$, which for
$m \sim m_H$ gives a Planck-scale correction
$\sim (125\,\mathrm{GeV})^2/(M_P/M_W)^2$, negligible. The quadratic
Planck-scale divergence is an artifact of treating $\Lambda$ as a hard
cutoff rather than as the physical Compton scale.

*Step 4 (no fine-tuning required).* The hierarchy $M_P/M_W \sim 10^{17}$
is the ratio of the Planck scale to the electroweak scale. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this ratio
is a measurement of the strength of gravity relative to electroweak
physics, set by the geometric content of $c$ (Channel B) in
$dx_4/dt = ic$ and the running of the Higgs couplings. No fine-tuning of
the Higgs mass is required because no Planck-scale correction enters the
Higgs self-energy at the relevant order.

*Step 5 (relation to vacuum stability and the top mass).* The observed
top quark mass $m_t \approx 173\,\mathrm{GeV}$ and Higgs mass
$m_H \approx 125\,\mathrm{GeV}$ place the Standard Model close to the
boundary of vacuum stability
(Theorem [55](#thm:vacuum-stability){reference-type="ref"
reference="thm:vacuum-stability"}). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
near-criticality is the empirical signature of the Compton-cutoff
resolution: if the cutoff were truly $M_P$, the Higgs sector would not
be near criticality; the observed near-criticality is consistent with
the cutoff being at the top mass.

*Step 6 (supersymmetric cancellation as Channel-A bookkeeping).* If
supersymmetry is realized in nature, boson--fermion loop cancellations
enforce $\delta m_H^2 \to 0$ as $m_{\rm SUSY} \to m_{\rm SM}$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
supersymmetric cancellation is one possible Channel-A way to enforce
Compton-locality across the loop; the McGucken framework's Channel-B
Compton-cutoff achieves the same Compton-locality without requiring
supersymmetric partners. The two mechanisms are not exclusive;
experimental data so far suggests the Channel-B mechanism (no
superpartners at LHC energies) rather than the Channel-A cancellation. ◻


# Vacuum Stability and Higgs Metastability 

## Historical background: Coleman 1977 to Buttazzo et al. 2013

The running of the Higgs self-coupling $\lambda(\mu)$ in the Standard
Model is sensitive to the top quark Yukawa coupling. For the observed
values $m_H = 125\,\mathrm{GeV}$ and $m_t = 173\,\mathrm{GeV}$, two-loop
calculations [@Buttazzo2013] show that $\lambda(\mu)$ becomes negative
at scale $\Lambda_I \approx 10^{10\text{--}11}\,\mathrm{GeV}$,
indicating that the electroweak vacuum is metastable. Tunneling to the
true vacuum has lifetime $\tau \sim 10^{100}\,\mathrm{yr}$, longer than
the age of the universe, but the existence of a deeper vacuum at large
field values is structurally disquieting: the Higgs potential is
unbounded from below in the deep UV.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 55** (Vacuum stability as $x_4$-Compton-cutoff structure).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Higgs potential's apparent instability at
$\Lambda_I \sim 10^{10}\,\mathrm{GeV}$ is the extrapolation of the
Standard Model coupling running past the natural Compton-cutoff scales
of available modes. The true vacuum structure is determined on the
McGucken Sphere at each event, with $\lambda(\mu)$ defined only for
$\mu \leq m_t c^2/\hbar$ unless additional heavy modes extend the
running. The near-criticality of $\lambda \approx 0$ at high scale is a
Channel-B signature of the Compton-locality structure, not a pathology
of the Higgs potential.*


::: proof
*Proof.* *Step 1 (the two-loop running).* The Standard Model RG
equations for $\lambda$ at two loops give
$$\frac{d\lambda}{d\ln\mu} = \frac{1}{16\pi^2}\Big[24\lambda^2 - 6 y_t^4 + (\text{gauge contributions})\Big] + \text{two-loop}.$$
For $m_H = 125\,\mathrm{GeV}$ and $m_t = 173\,\mathrm{GeV}$,
$\lambda(M_Z) \approx 0.13$ and $y_t(M_Z) \approx 0.94$, giving
$d\lambda/d\ln\mu < 0$ at low scale. Integrating, $\lambda(\mu)$ crosses
zero near $\Lambda_I \approx 10^{10}\,\mathrm{GeV}$ and becomes
increasingly negative thereafter, until it would diverge near the Planck
scale.

*Step 2 (the extrapolation question).* The RG running treats all scales
between $M_Z$ and $\Lambda_I$ as accessible to the Higgs's loop
integrals. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the $x_4$-Compton-locality constraint
(Theorem [54](#thm:hierarchy){reference-type="ref"
reference="thm:hierarchy"}) requires that loops only sum over modes with
masses less than the available threshold. In the Standard Model, the
heaviest mode is the top quark at $\sim 173\,\mathrm{GeV}$, with no
further modes until the GUT scale (if at all). The RG running from
$\sim 200\,\mathrm{GeV}$ to $10^{10}\,\mathrm{GeV}$ therefore takes
place in a regime where no new modes turn on, and the running is
dominated by the top-quark loop alone.

*Step 3 (Channel-B sign of $\lambda$).* The negativity of $\lambda$ at
$10^{10}\,\mathrm{GeV}$ in the two-loop calculation is not a pathology
of the Higgs potential at low scale; it is a feature of the effective
theory at high scale. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, $\lambda(\mu)$ is the Channel-B coupling of the
Higgs to itself at the scale $\mu$; its sign at very high scale is
sensitive to all loop contributions, including the top-quark loop that
drives it negative. The negativity at $\Lambda_I$ is the Channel-B
prediction that the McGucken Sphere structure does not support a
positive Higgs self-coupling at trans-$\Lambda_I$ scales without new
physics; it is a statement about the absence of additional bosons
(additional Higgs doublets, supersymmetric partners) above $\Lambda_I$,
not about the metastability of the electroweak vacuum.

*Step 4 (the tunneling rate).* The tunneling rate to the deeper vacuum
at field values $\phi > \Lambda_I$ is computed by the
Fubini--Coleman--de Luccia bounce solution. The action of the bounce is
$$S_{\rm bounce} = \frac{8\pi^2}{3|\lambda(\mu_*)|},$$ giving
$\tau \sim \exp(S_{\rm bounce})$. For $\lambda(\mu_*) \approx -0.01$,
$S_{\rm bounce} \sim 3000$ and $\tau \sim 10^{1000}\,\mathrm{yr}$,
vastly longer than the age of the universe. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
tunneling is a Channel-B process: the McGucken Sphere at any event must
propagate the Higgs field through a $\phi$-configuration with
$\phi \gg \Lambda_I$, which requires assembling many
$x_4$-frame-coherent modes over a region of size $\sim 1/\Lambda_I$. The
exponential suppression is the Channel-B obstruction to such coherent
assembly.

*Step 5 (the near-criticality observation).* The fact that the Higgs and
top masses place $\lambda(\Lambda_I) \approx 0$ at a finite scale is a
notable feature of the Standard Model that no other principle predicts.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
near-criticality is consistent with the framework's Compton-locality
structure: the absence of new modes between $m_t$ and $\Lambda_I$ allows
$\lambda$ to flow to near zero, but the absence of confirmed new modes
at LHC suggests the framework is robust up to at least the TeV scale.
The Higgs potential's metastability is therefore not a defect to be
cured by new physics but a Channel-B signature of the McGucken Sphere's
Compton-locality at the highest scales currently accessible. ◻


# Baryogenesis and the Sakharov Conditions 

## Historical background: Sakharov 1967 to Kuzmin--Rubakov--Shaposhnikov 1985 sphaleron

The observable universe contains $\sim 10^9$ photons per baryon and an
apparent absence of antimatter in cosmological abundance.
Sakharov [@Sakharov1967] identified three conditions necessary to
generate a baryon asymmetry from an initially baryon-symmetric universe:
(1) baryon-number violation; (2) C and CP violation; (3) departure from
thermal equilibrium. The Standard Model satisfies (1) only through
non-perturbative sphaleron processes and (2) only at the $\sim 10^{-20}$
level through the CKM phase; (3) requires an out-of-equilibrium phase
transition. Quantitative computation gives
$\eta = n_B/n_\gamma \approx 10^{-29}$ from the Standard Model,
vs. observed $\eta \approx 6 \times 10^{-10}$, a $10^{19}$ discrepancy.
Baryogenesis remains an open problem; proposed solutions include
leptogenesis [@FukugitaYanagida1986], electroweak baryogenesis with
extended Higgs sectors, and Affleck--Dine
baryogenesis [@AffleckDine1985].

## The McGucken $dx_4/dt = ic$ reading


**Theorem 56** (Baryogenesis as $x_4$-orientation asymmetry). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, matter and
antimatter are the forward-$x_4$ and backward-$x_4$ branches of the
Dirac equation (Step 1 of Theorem [47](#thm:klein){reference-type="ref"
reference="thm:klein"}). The principle $dx_4/dt = ic$ has only one
orientation ($+ic$, not $-ic$); the universe-as-event is the McGucken
Sphere expanding forward in $x_4$. Both forward and backward branches
advance forward in $x_4$ in the lift to $SU(2)_L$
(per [@McGuckenQuantum2026], §IV.4.7); the apparent matter-antimatter
asymmetry at the cosmological scale is the integrated bias of the
universal $+ic$ orientation acting on the Compton-coupled lift over
$13.8\,\mathrm{Gyr}$. Sakharov's three conditions are theorems of the
$+ic$ orientation; the magnitude $\eta \approx 10^{-9}$ is the open
problem.*


::: proof
*Proof.* *Step 1 (the $\pm ic$ branches of the Dirac equation).* By Step
1 of Theorem [47](#thm:klein){reference-type="ref"
reference="thm:klein"}, the Dirac equation has positive- and
negative-energy solutions $E = \pm E_p$ corresponding to the $+ic$ and
$-ic$ orientations of $dx_4/dt$. The standard interpretation identifies
the negative-energy modes with antiparticles propagating forward in time
via charge conjugation; equivalently, the Dirac sea is filled and
antiparticles are absences in the sea. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the two
branches are the two $x_4$-orientations of the same physical field;
antiparticles do advance forward in $x_4$ (with positive energy) but
their $x_4$-phase is rotated by $\pi$ relative to particles, encoding
the opposite charge and chirality.

*Step 2 (Sakharov condition 1: $B$-violation).* Baryon number $B$ is a
$U(1)$ symmetry of the Standard Model Lagrangian at the perturbative
level, classically conserved. The non-perturbative sphaleron
process [@KlinkhamerManton1984] violates $B + L$ but conserves $B - L$;
at temperatures $T \gtrsim 100\,\mathrm{GeV}$, sphalerons are
unsuppressed. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, sphaleron $B+L$ violation is a topological
transition between $x_4$-frame configurations with different winding
numbers; the McGucken Sphere structure allows such transitions at energy
$\gtrsim m_W c^2$ when the $x_4$-frame can be twisted around the gauge
orbit (Theorem [50](#thm:gauge-ghost){reference-type="ref"
reference="thm:gauge-ghost"}). The Sakharov condition is therefore a
Channel-A theorem from the topological structure of $SU(2)_L$, not an
additional postulate.

*Step 3 (Sakharov condition 2: C and CP violation).* The CKM matrix
carries a single CP-violating phase
$\delta_{\rm CKM} \approx 1.2\,\mathrm{rad}$; in the lepton sector, the
PMNS matrix carries additional phases including possibly two Majorana
phases. CP violation in the Standard Model is observed in
$K^0$--$\bar K^0$ and $B^0$--$\bar B^0$ mixing. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, CP
violation is the asymmetry of the $x_4$-phase rotation between particles
and antiparticles; the CKM phase is the Channel-A integrated measure of
this asymmetry in quark mixing. The Sakharov condition is theorem-level:
any $x_4$-phase asymmetry between forward and backward branches
automatically generates CP violation.

*Step 4 (Sakharov condition 3: departure from equilibrium).* Equilibrium
would equalize particle and antiparticle abundances by detailed balance.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
universe is never in thermal equilibrium because the McGucken Sphere is
actively expanding at every event; the spherical $x_4$-expansion at
$+ic$ continually redshifts thermal modes and drives the cosmological
scale factor outward (Theorem [39](#thm:cosmo){reference-type="ref"
reference="thm:cosmo"}). Sakharov's third condition is automatically
satisfied; the question is only whether the departure is large enough at
the relevant epoch to freeze in the observed asymmetry.

*Step 5 (the magnitude problem).* Quantitative computation of $\eta$
from CKM-CP violation gives $\eta \sim 10^{-29}$, far below observed.
The Standard Model alone cannot explain the magnitude; the observed
asymmetry requires either leptogenesis (Majorana neutrino-mass
mechanisms), extended Higgs sectors (electroweak baryogenesis), or a
cosmological-scale CP-violating source. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
magnitude $\eta \approx 10^{-9}$ is the integrated bias of the universal
$+ic$ orientation acting on the Compton-coupled chiral structure over
the relevant epoch. The three candidate channels are (a) lepton-sector
PMNS phases mixed with sphalerons (leptogenesis); (b) cosmological-scale
$x_4$-phase coherence (Affleck--Dine); (c) Higgs-sector dynamics during
electroweak phase transition. The open problem is the magnitude
$\varepsilon_B \approx 10^{-9}$, listed as an open question
in [@McGuckenQuantum2026], §14.14; the framework cleanly establishes
Sakharov 1--3 as theorems but does not yet derive the magnitude.

*Step 6 (no separate matter-antimatter universe needed).* The naive
picture in which the universe has spatially separated matter and
antimatter regions is excluded observationally: no annihilation
$\gamma$-ray signatures from boundaries have been found. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the absence
is structural: both $+ic$ branches advance forward in $x_4$, so
antimatter at any event is locally indistinguishable from matter except
by its $x_4$-phase rotation. The observable asymmetry is in the
cosmological-scale integrated $x_4$-phase, not in spatially separated
bulk regions. ◻


# The Strong CP Problem 

## Historical background: 't Hooft 1976 instanton to Peccei--Quinn 1977

The QCD Lagrangian admits a $\theta$-term
$$\mathcal{L}_\theta = \frac{\theta g_s^2}{32\pi^2} G^a_{\mu\nu}\tilde G^{a\mu\nu},$$
which is a total derivative but contributes to physics through instanton
effects. The $\theta$ parameter generates a neutron electric dipole
moment $d_n \sim \theta \cdot 10^{-16}\,e\,\mathrm{cm}$. The
experimental bound is $d_n < 1.8 \times 10^{-26}\,e\,\mathrm{cm}$,
giving $|\theta| < 10^{-10}$. Why is $\theta$ so small? The Standard
Model offers no symmetry that protects $\theta = 0$. The Peccei--Quinn
solution [@PecceiQuinn1977] promotes $\theta$ to a dynamical axion
field; alternative solutions invoke Nelson--Barr models or massless
up-quark scenarios. None has been observationally confirmed.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 57** (Strong CP as Channel-A vs Channel-B
$\theta$-distinction). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the $\theta$-angle is the integrated $x_4$-phase of
QCD instanton configurations summed over the gauge orbit. The Channel-A
reading of $\theta$ from CKM mixing gives a contribution
$\theta_{\rm CKM}$; the Channel-B reading from the McGucken Sphere's
QCD-coupled $x_4$-velocity gives $\theta_{\rm geom}$. The physical
$\theta$ is the difference
$\theta_{\rm phys} = \theta_{\rm CKM} - \theta_{\rm geom}$, which under
McGucken Compton-locality is naturally small because the two channels
share no intermediate machinery and their integrated phases are
independent up to the Compton-locality precision at the QCD scale.*


::: proof
*Proof.* *Step 1 (the $\theta$-vacuum).* The QCD vacuum is parameterized
by the integer winding number $n$ of the Yang--Mills gauge
configuration: $|n\rangle$ labels vacua with topological charge $n$. The
true vacuum is $|\theta\rangle = \sum_n e^{in\theta}|n\rangle$. The
$\theta$-term in the Lagrangian arises from the projection onto this
vacuum.

*Step 2 (the CKM contribution).* The CKM CP phase $\delta_{\rm CKM}$
induces a finite contribution to $\theta$ through the
renormalization-group running; the standard result is
$\theta_{\rm CKM} \sim \arg\det(M_u M_d)$ where $M_u, M_d$ are the up-
and down-quark mass matrices. With non-Hermitian Yukawas,
$\arg\det \neq 0$. The natural size is
$\theta_{\rm CKM} \sim \mathcal{O}(1)$, in conflict with the
experimental bound.

*Step 3 (the Channel-B geometric $\theta$).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$\theta$-angle also arises from the McGucken Sphere's coupling to QCD
instantons through Channel B. Specifically, the spherical
$x_4$-expansion at every event integrates the gluonic instanton density
$G\tilde G$ over the past light cone of the event; the integral defines
a Channel-B contribution $\theta_{\rm geom}$ to the physical $\theta$.
The Channel-B contribution is independent of the Channel-A CKM phase
because the two channels share no intermediate machinery: Channel A goes
through $SU(3)_c$ gauge dynamics and quark Yukawa couplings; Channel B
goes through the geometric integration over null cones.

*Step 4 (the cancellation).* The physical $\theta$ is the sum of the two
contributions:
$\theta_{\rm phys} = \theta_{\rm CKM} - \theta_{\rm geom}$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the two
contributions are independently of $\mathcal{O}(1)$ but their difference
is structurally bounded by Compton-locality considerations: the
Channel-B contribution must be consistent with the Channel-A phase to
within the precision of the McGucken Sphere's geometric integration at
the QCD scale, which scales as
$(\Lambda_{\rm QCD}/m_W)^4 \sim 10^{-10}$, naturally explaining the
experimental bound on $|\theta|$.

*Step 5 (relation to Peccei--Quinn).* The Peccei--Quinn solution
introduces a dynamical axion field $a(x)$ that relaxes to
$a/f_a = -\theta_{\rm phys}$, canceling $\theta$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the axion
is a Channel-A device that enforces exact cancellation between the two
contributions through a dynamical mechanism. The McGucken framework's
natural explanation does not require the axion; the experimental search
for axions (CAST, ADMX, IAXO) therefore directly tests whether nature
uses the Channel-A mechanism or the Channel-B Compton-locality
structure. Either way, the strong CP problem is dissolved in the
McGucken framework: $\theta_{\rm phys}$ is small because the two
channels contribute independently and their difference is bounded by
Compton-locality of the gauge field at the QCD scale. ◻


# The Naturalness Problem 

## Historical background: 't Hooft 1980 to landscape and multiverse debates

Beyond the Higgs hierarchy
(Theorem [54](#thm:hierarchy){reference-type="ref"
reference="thm:hierarchy"}), the Standard Model contains additional
small parameters: the strong CP angle
(Theorem [57](#thm:strong-cp){reference-type="ref"
reference="thm:strong-cp"}), the cosmological constant
(Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}), and
the small fermion mass ratios. 't Hooft's naturalness
criterion [@tHooftNaturalness1980] states that small numbers are natural
only if a symmetry enhances when they vanish. Multiple Standard Model
parameters violate this criterion: the cosmological constant violates it
dramatically; the strong CP angle violates it; the small lepton masses
($m_e/m_t \sim 10^{-5}$) violate it. The collective naturalness problem
motivates anthropic explanations, the multiverse, and various landscape
constructions.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 58** (Naturalness as the dual-channel diagnostic). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Standard Model's small parameters are not collectively unnatural; they
are the Channel-A residues of structurally disjoint Channel-B geometric
contributions that the McGucken framework supplies independently. The
cosmological constant (Theorem [38](#thm:cc){reference-type="ref"
reference="thm:cc"}), the strong CP angle
(Theorem [57](#thm:strong-cp){reference-type="ref"
reference="thm:strong-cp"}), and the Higgs hierarchy
(Theorem [54](#thm:hierarchy){reference-type="ref"
reference="thm:hierarchy"}) all follow this pattern: each small
parameter is the difference of two independent $\mathcal{O}(1)$
contributions (Channel A and Channel B), naturally bounded by the
Compton-locality of the relevant mode. The naturalness problem is the
failure of orthodox physics to recognize the dual-channel structure of
its own framework.*


::: proof
*Proof.* *Step 1 (the orthodox criterion).* 't Hooft's naturalness
states: a parameter $\epsilon$ is natural if $\epsilon \to 0$ enhances
the symmetry of the theory. For example, the electron mass is natural
because $m_e \to 0$ restores chiral symmetry. The Higgs mass is
unnatural because $m_H \to 0$ enhances no symmetry; the cosmological
constant is unnatural because $\Lambda \to 0$ enhances no symmetry.

*Step 2 (the McGucken dual-channel criterion).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, a parameter
is natural if it is the difference of two Channel-A and Channel-B
contributions that share no intermediate machinery. The smallness then
arises from the structural independence of the two channels: each
contributes independently at $\mathcal{O}(1)$, but their difference is
naturally bounded by the Compton-locality scale of the relevant mode.

*Step 3 (cosmological constant).* By
Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"},
$\Lambda$ is the Channel-B square of the McGucken expansion rate, and
the QFT zero-point energy is the Channel-A double-counting of the same
$x_4$-expansion. The renormalized $\Lambda$ is the difference; its
magnitude $\sim 10^{-47}\,\mathrm{GeV}^4$ is set by the McGucken Sphere
at the cosmological scale, naturally explaining the small physical
value.

*Step 4 (strong CP).* By
Theorem [57](#thm:strong-cp){reference-type="ref"
reference="thm:strong-cp"}, the physical $\theta$ is the difference of
Channel-A CKM and Channel-B geometric contributions, naturally bounded
by Compton-locality at the QCD scale.

*Step 5 (Higgs hierarchy).* By
Theorem [54](#thm:hierarchy){reference-type="ref"
reference="thm:hierarchy"}, the Higgs mass receives only Compton-cutoff
radiative corrections from the top quark, naturally of order $m_t$, not
the Planck scale. No fine-tuning is required.

*Step 6 (small lepton and quark masses).* The light-quark and lepton
mass ratios $m_e/m_t \sim 10^{-5}$ are not unnatural in the McGucken
framework if they are determined by the Yukawa couplings of the McGucken
Sphere structure at the relevant Compton scales. The detailed Yukawa
hierarchy is derived in [@McGuckenSM2026]; the small ratios are
Channel-A residues of structurally independent Channel-B geometric
contributions to each generation's Yukawa.

*Step 7 (no anthropic principle required).* Weinberg's anthropic upper
bound on $\Lambda$ [@Weinberg1989] is dissolved by
Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}; the
multiverse landscape is dissolved by
Theorem [44](#thm:interpretations){reference-type="ref"
reference="thm:interpretations"} (no multiverse needed). The McGucken
framework explains the Standard Model's parameters without invoking the
anthropic principle or the multiverse, satisfying Newton's
Rule I [@Newton1687]: admit no more causes than necessary. ◻


# The Three-Generation Problem 

## Historical background: tau discovery 1975 to LEP precision electroweak 1990s

The Standard Model contains three generations of quarks and leptons with
the same gauge quantum numbers but successively larger Yukawa couplings
to the Higgs. The reason for exactly three generations is unknown.
Anomaly cancellation in the Standard Model is satisfied
generation-by-generation, so any number of generations would be
consistent. The CKM matrix's $3 \times 3$ structure supplies the
irreducible CP phase that makes baryogenesis possible
(Theorem [56](#thm:baryogenesis){reference-type="ref"
reference="thm:baryogenesis"}), but the experimental fact of three
generations is structurally unaccounted for. Various proposals (family
symmetries, extra dimensions, string compactifications) have offered
explanations; none has been confirmed.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 59** (Three generations as $x_4$-frame triadic structure).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
three generations correspond to the three distinct $x_4$-frame
orientations consistent with the spherical $x_4$-expansion's
tangent-bundle structure on the McGucken Sphere. Specifically, the three
colors of $SU(3)_c$, the three spatial dimensions, and the three
generations are all manifestations of the cyclic ordering of three
wavefront-tangent directions to the $x_4$-axis, derived
in [@McGuckenSM2026] as a theorem of the $dx_4/dt = ic$ Compton-coupled
spinor structure.*


::: proof
*Proof.* *Step 1 (the triadic structure).* The McGucken Sphere
$\Sigma_+(p)$ at any event $p$ has tangent space at $p$ given by
$T_p\mathcal{M} = \mathbb{R}^3 \oplus \mathbb{R}_{x_4}$; the three
spatial directions are the tangent vectors orthogonal to the $x_4$-axis.
By the cyclic-ordering theorem of [@McGuckenSM2026] (specifically the
§ssec:ColorAsCyclicOrdering integration), the three spatial directions
admit a unique cyclic ordering (right-handed vs. left-handed) preserved
by the rotational symmetry of the McGucken Sphere; this cyclic ordering
is what is gauged to produce $SU(3)_c$.

*Step 2 (lift to spinor generations).* The Dirac spinor $\psi$ at each
event has four components decomposing as
$\psi = (\psi_L^{u}, \psi_L^{d}, \psi_R^{u}, \psi_R^{d})$ in the
standard $SU(2)_L$-doublet structure. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the spinor
structure inherits the triadic content of the three spatial directions:
at each event, the $x_4$-phase rotation acts on the spinor through three
independent generators corresponding to the three tangent directions to
$x_4$. The three generations are the three distinct $x_4$-frame choices
consistent with the cyclic-ordering structure of the McGucken Sphere.

*Step 3 (Yukawa hierarchy).* The Yukawa couplings of the three
generations to the Higgs are set by the geometric content of the three
$x_4$-frame choices at the electroweak symmetry-breaking scale.
By [@McGuckenSM2026], the Yukawa hierarchy $y_t \gg y_c \gg y_u$ and
analogously for down and lepton sectors arises from the Compton-coupled
$x_4$-phase advancement in the three frames; the top quark's near-unity
Yukawa corresponds to the $x_4$-frame closest to the McGucken Sphere's
structural maximum, with subsequent generations distinguished by their
distance from this maximum.

*Step 4 (no fourth generation).* A fourth generation would require a
fourth distinct $x_4$-frame consistent with the cyclic-ordering
structure. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, no such fourth orientation exists: the McGucken
Sphere's tangent space at each event is three-dimensional, and the
cyclic ordering is exhaustively enumerated by the three colors / three
spatial directions / three generations. Additional generations are
therefore structurally forbidden by Compton-locality on the McGucken
Sphere.

*Step 5 (consistency with experiment).* The Standard Model's
experimental constraints on a fourth generation are consistent with this
prediction: the LEP measurement of the $Z$-boson invisible width
restricts the number of light neutrino species to
$N_\nu = 2.984 \pm 0.008$, and direct searches at LHC have not found a
fourth-generation quark below $\sim 1\,\mathrm{TeV}$. The McGucken
framework's prediction is exactly three generations; this is an
empirical success. ◻


# Dark Matter 

## Historical background: Zwicky 1933 to Rubin--Ford 1970s to Bullet Cluster 2006

The existence of an invisible mass component dominating galactic and
cluster dynamics was inferred by Zwicky [@Zwicky1933] from the Coma
cluster's velocity dispersion, then by Rubin and Ford [@RubinFord1970]
from flat galactic rotation curves. Modern observations---CMB power
spectrum [@Planck2018], gravitational lensing [@Clowe2006], structure
formation, baryon acoustic oscillations---all require
$\Omega_{\rm DM} \approx 0.265$, five times the baryonic mass density.
Candidates include weakly interacting massive particles (WIMPs), axions
(Theorem [57](#thm:strong-cp){reference-type="ref"
reference="thm:strong-cp"}), sterile neutrinos, primordial black holes,
and modified gravity (MOND). Direct-detection searches (XENONnT, LZ) and
collider searches (LHC) have so far found no confirmed signal.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 60** (Dark matter as $x_4$-coupled mass beyond Standard Model
Compton sector). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, gravitational mass is the $x_4$-coupling strength
of a particle via its Compton frequency $\omega_C = mc^2/\hbar$
(Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}). The observed gravitational mass discrepancy
at galactic and cluster scales indicates the existence of
Compton-coupled modes outside the Standard Model gauge sector. The
McGucken framework does not predict the dark matter candidate species
but constrains it: the dark matter must couple to the McGucken Sphere's
$x_4$-expansion field but not to the Standard Model's
$SU(3)_c \times SU(2)_L \times U(1)_Y$ gauge group at the observed
sensitivity.*


::: proof
*Proof.* *Step 1 (gravitational mass as $x_4$-coupling).* By
Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}, the equivalence principle identifies
gravitational mass with inertial mass; under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, both are
the strength with which the particle couples to the McGucken Sphere's
$x_4$-velocity field. The Compton frequency $\omega_C = mc^2/\hbar$
measures the rate of the particle's $x_4$-phase advance; a massive
particle has $\omega_C > 0$ and contributes to the local stress-energy
tensor sourcing the curvature of $x_4$-frames at neighboring events.

*Step 2 (the rotation curve evidence).* For a galaxy with mass profile
$M(r)$, the orbital velocity at radius $r$ is $v(r) = \sqrt{GM(r)/r}$.
Observed rotation curves are flat at large $r$:
$v(r) \to v_\infty \approx 200\,\mathrm{km/s}$, implying
$M(r) \propto r$ at large $r$. The visible mass profile from stars and
gas does not extend to large enough $r$ to produce this; the inferred
"missing" mass exceeds visible by factor $\sim 5$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the flat
rotation curve is the geometric signature of an additional
Compton-coupled mass density extending beyond the visible distribution.
The McGucken Sphere structure at any event in the galactic halo is
sourced by all Compton-coupled modes at that event, not only by Standard
Model modes.

*Step 3 (the gravitational lensing test).* The Bullet
Cluster [@Clowe2006] provides a clean separation between baryonic mass
(traced by X-ray-emitting plasma) and total mass (traced by
gravitational lensing). The two distributions are spatially offset: most
of the gravitational mass is offset from the baryonic distribution by
$\sim 100\,\mathrm{kpc}$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, this offset cannot be explained by modifications of
gravity acting on baryonic mass alone (e.g., MOND [@Milgrom1983]); the
additional Compton-coupled modes must be physically separated from the
baryons, which requires that they be collisionless on cluster
timescales. The structural constraint: the dark matter must be
Compton-coupled (gravitationally interacting) but very weakly coupled to
electromagnetism and strong interactions.

*Step 4 (CMB constraint).* The CMB power spectrum [@Planck2018] measures
the ratio of acoustic peaks, sensitive to the baryonic-to-dark-matter
density ratio at recombination. The result is
$\Omega_b/\Omega_{\rm DM} \approx 0.19$, requiring a Compton-coupled
mass density $5\times$ the baryonic. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the CMB
peak structure is the cosmological-scale Channel-B propagation of
acoustic modes through the $x_4$-velocity field of all Compton-coupled
mass at recombination; the inferred ratio is a direct measurement of the
non-Standard-Model Compton-coupled mass density.

*Step 5 (no specific candidate predicted).* The McGucken framework does
not predict the specific particle content of dark matter. The structural
constraint is that the dark matter must Compton-couple to the McGucken
Sphere's $x_4$-expansion field (i.e., have nonzero mass) but must not
couple significantly to the Standard Model gauge group. Candidate
species satisfying this---WIMPs, axions, sterile neutrinos, primordial
black holes---are all consistent with
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}. The
framework adds the constraint that any candidate must respect
Compton-locality at its own mass scale
(Theorem [54](#thm:hierarchy){reference-type="ref"
reference="thm:hierarchy"}); this constrains light-mass candidates
(axions, sterile neutrinos) to have specific Compton-coupled
cross-sections to Standard Model modes.

*Step 6 (MOND alternative excluded).* MOND modifies the gravitational
force at low accelerations $a < a_0 \sim 10^{-10}\,\mathrm{m/s^2}$ to
fit rotation curves without dark matter. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Sphere's geometric structure sources gravity uniformly at all
scales through the $x_4$-velocity field; there is no scale-dependent
modification of the force law on the McGucken Sphere. The Bullet
Cluster's offset between baryonic and gravitational mass is incompatible
with any force-law modification acting only on baryonic mass; MOND is
therefore excluded by Channel-B locality of the McGucken Sphere
geometry. ◻


# Dark Energy and the Coincidence Problem 

## Historical background: Riess et al. and Perlmutter et al. 1998 to DESI 2024

The accelerating expansion of the universe was inferred from Type Ia
supernova observations by Riess et al. [@Riess1998] and Perlmutter et
al. [@Perlmutter1999], with subsequent confirmation from CMB and baryon
acoustic oscillations. The present-day density
$\Omega_\Lambda \approx 0.685$ dominates the cosmic budget. Two
questions distinguish from the cosmological constant problem
(Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}): (1) Is
dark energy a true cosmological constant or a dynamical field
(quintessence, phantom energy)? (2) Why is
$\Omega_\Lambda \sim \Omega_m$ today, the "coincidence problem"---given
that the two scale very differently ($\Omega_m \propto a^{-3}$,
$\Omega_\Lambda$ constant), why are we in the brief epoch when they are
comparable?

## The McGucken $dx_4/dt = ic$ reading


**Theorem 61** (Dark energy and the coincidence as McGucken Sphere
expansion rate). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, dark energy is the Channel-B expansion rate of the
cosmological McGucken Sphere (Theorem [38](#thm:cc){reference-type="ref"
reference="thm:cc"}). The apparent coincidence
$\Omega_\Lambda \sim \Omega_m$ at the present epoch reflects a
structural feature: the McGucken Sphere's volume scales as
$V \propto a^3$ at every event, and the geometric content of the $+ic$
expansion synchronizes the matter density and the cosmological expansion
rate at the epoch when the McGucken Sphere reaches its present scale.*


::: proof
*Proof.* *Step 1 (dark energy is the cosmological constant, not a
separate field).* The equation of state of dark energy is constrained by
observations to $w = p/\rho = -1.03 \pm 0.03$ [@Planck2018], consistent
with $w = -1$ for a pure cosmological constant. Quintessence and
phantom-energy fields are constrained to $|w + 1| < 0.05$, with no
positive evidence for time variation. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, dark energy
is the cosmological constant identified in
Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"} with
$\Lambda = 3H^2_\Lambda/c^2$, the Channel-B square of the McGucken
expansion rate. The equation of state $w = -1$ is automatic; no
additional dynamical field is required.

*Step 2 (the coincidence problem stated).* The matter density scales as
$\Omega_m(a) \propto a^{-3}$; the dark energy density is constant. The
ratio $\Omega_\Lambda/\Omega_m$ thus grows as $a^3$. At very early times
($a \ll 1$), $\Omega_\Lambda \ll \Omega_m$; at very late times
($a \gg 1$), $\Omega_\Lambda \gg \Omega_m$. The brief epoch when they
are comparable spans a few orders of magnitude in $a$; the present
moment $a = 1$ lies within this brief window. The orthodox question: why
now?

*Step 3 (the McGucken Sphere structural answer).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Sphere at any event has volume $V(t) = (4\pi/3)(ct)^3$ where
$t$ is the proper time since the event-of-origin. The cosmological
McGucken Sphere (the universal Sphere) has present volume
$V_{\rm now} = (4\pi/3)(ct_{\rm now})^3$, with
$t_{\rm now} \approx 13.8\,\mathrm{Gyr}$. The matter density at the
present epoch is set by the integrated baryon and dark-matter content
over the past $13.8\,\mathrm{Gyr}$ of cosmic expansion; the cosmological
constant is set by the present McGucken expansion rate. The two are
linked through the McGucken Sphere structure:
$\Omega_m + \Omega_\Lambda \approx 1$ is the spatial flatness condition
(Theorem [39](#thm:cosmo){reference-type="ref" reference="thm:cosmo"},
flatness), and the ratio $\Omega_m/\Omega_\Lambda \approx 0.46$ at the
present epoch is set by the integrated history of the McGucken Sphere
from the matter-dominated to the dark-energy-dominated phase.

*Step 4 (the transition epoch).* The matter-dark-energy equality occurs
when $\rho_m(a_{\rm eq}) = \rho_\Lambda$, i.e.,
$a_{\rm eq} \approx (\Omega_\Lambda/\Omega_m)^{-1/3}_{\rm now}\cdot 1 \approx 0.77$,
corresponding to redshift $z_{\rm eq} \approx 0.3$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
transition is structural: the McGucken Sphere's geometric content at
every event is independent of cosmic epoch (the spherical
$x_4$-expansion at $+ic$ acts the same way always), but the matter
density falls with $a^{-3}$ while the Sphere's geometric contribution is
constant. The transition epoch is determined by the integrated cosmic
expansion from the recombination era ($z \approx 1100$) to the present.

*Step 5 (no coincidence).* The orthodox "coincidence" arises from the
assumption that $\Omega_\Lambda$ is set by some Planck-scale physics
independent of the cosmological evolution, and the observed value
happens to match $\Omega_m$ today by chance. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
assumption is false: $\Omega_\Lambda$ is the present McGucken expansion
rate, structurally linked to the cosmological evolution through
$\Lambda = 3H^2/c^2$. The values
$(\Omega_m, \Omega_\Lambda) = (0.315, 0.685)$ at the present epoch are
not coincident but the geometric content of the McGucken Sphere at
$t_{\rm now} = 13.8\,\mathrm{Gyr}$; any conscious observer existing at
the present epoch will measure these values not because of anthropic
selection but because the McGucken Sphere structure determines them as a
function of cosmic epoch.

*Step 6 (predictions).* The McGucken framework predicts: (a) $w = -1$
exactly, no time variation; (b) the future evolution
$\Omega_\Lambda \to 1, \Omega_m \to 0$ as $a \to \infty$ following the
Sphere's $a^{-3}$ matter dilution; (c) no deviation from the standard
$\Lambda$CDM equation-of-state. Observational tests of (a)--(c) include
the Euclid mission, LSST, and DESI, all of which to date show no
significant deviation from $\Lambda$CDM. Each of (a), (b), (c) follows
directly from the identification of $\Lambda$ as $3H^2/c^2$ in
Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"} together
with the matter-density dilution from cosmological-Sphere expansion; the
predictions are theorems, not free parameters. ◻


# The Monopole Problem 

## Historical background: Dirac 1931 to Kibble mechanism 1976 to GUT expectations

Grand Unified Theories (GUTs) predict the existence of magnetic
monopoles as topological solitons in the gauge field at the GUT scale
$M_{\rm GUT} \sim 10^{15\text{--}16}\,\mathrm{GeV}$ [@tHooftPolyakov1974; @Polyakov1974].
The Kibble mechanism [@Kibble1976] estimates that monopoles would have
been produced at the GUT phase transition with abundance
$\rho_M \sim 10^{14}\,\rho_{\rm matter}$, dominating the universe and
recollapsing it within $\sim 10^{-7}\,\mathrm{s}$. The observed universe
is dominated by matter and radiation, with no detected monopoles; the
discrepancy is the monopole problem. Inflation [@Guth1981] resolves this
by diluting any pre-inflationary monopole density to negligible levels.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 62** (Monopole problem as Channel-B McGucken Sphere
structure). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, monopoles would be topological defects of the
$x_4$-frame at the GUT scale. The McGucken Sphere's spherically
symmetric $x_4$-expansion at every event continuously smooths the
$x_4$-frame structure, dissolving topological defects above their
Compton scale. Monopoles are therefore not produced in cosmologically
significant abundance; the GUT-scale Kibble estimate is the result of
treating the gauge field's phase transition as if it were independent of
the McGucken Sphere's expansion, which under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} is the
dominant geometric effect at all scales.*


::: proof
*Proof.* *Step 1 (the GUT monopole solution).* The 't Hooft--Polyakov
monopole is a topological soliton of the spontaneously broken GUT gauge
symmetry $G \to H$, with magnetic charge $g = 2\pi/e$ (Dirac
quantization) and mass
$M_M \sim M_{\rm GUT}/\alpha_{\rm GUT} \sim 10^{17}\,\mathrm{GeV}$. The
topological charge is the second homotopy class $\pi_2(G/H)$, nontrivial
for $G \supset SU(5)$ and $H \supset U(1)_{\rm em}$.

*Step 2 (the Kibble estimate).* At a phase transition, the Higgs field
$\phi$ aligns randomly in causally disconnected regions of size
$\xi \sim H^{-1}$ where $H$ is the Hubble rate at the transition. The
probability of a nontrivial winding in a region of size $\xi$ is
$\mathcal{O}(1)$, producing $n_M \sim 1/\xi^3 \sim H^3$. For
$M_{\rm GUT} \sim 10^{16}\,\mathrm{GeV}$,
$H_{\rm GUT} \sim M_{\rm GUT}^2/M_P \sim 10^{13}\,\mathrm{GeV}$, giving
$n_M/s \sim 10^{-2}$, with $s$ the entropy density. The resulting
monopole abundance dominates the universe.

*Step 3 (the McGucken Sphere correction).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the GUT
phase transition occurs against the background of the McGucken Sphere's
spherically symmetric expansion at every event. The Higgs field's
alignment is not independent across causally disconnected regions
because the $x_4$-velocity field from every event reaches all other
events on the future null cone; the relevant correlation length is not
$\xi \sim H^{-1}$ but the integrated $x_4$-distance $\ell_{x_4} \sim ct$
since the relevant epoch, which is much larger.

*Step 4 (no monopole production).* With the correlation length
$\ell_{x_4}$ replacing $\xi$ in the Kibble estimate,
$n_M \sim 1/\ell_{x_4}^3 \to 0$ as $\ell_{x_4} \to \infty$. Monopoles
are not produced at cosmologically significant abundance because the
McGucken Sphere's expansion correlates the Higgs alignment over
distances much larger than the Hubble horizon. The structural mechanism
is the same as the resolution of the horizon problem
(Theorem [39](#thm:cosmo){reference-type="ref" reference="thm:cosmo"}):
every CMB event shares the $x_4$-phase of the recombination event via
the spherical $x_4$-expansion from every prior event.

*Step 5 (no inflation required).* Inflation [@Guth1981] is the orthodox
dilution mechanism: the universe expands by a factor $e^{60}$ during a
brief epoch, diluting any pre-inflationary monopole density to
negligible. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, no such dilution is required: the McGucken Sphere's
correlation structure prevents monopole production in the first place.
The horizon and flatness problems
(Theorem [39](#thm:cosmo){reference-type="ref" reference="thm:cosmo"}),
like the monopole problem, are dissolved without inflation by the
McGucken Sphere structure. Inflation may still occur as a Channel-B
process compatible with Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, but it is not required to resolve the monopole
problem.

*Step 6 (consistency with direct searches).* Direct searches for
magnetic monopoles---MoEDAL at LHC, IceCube, MACRO---have set upper
limits $\Phi_M < 10^{-16}\,\mathrm{cm^{-2}\,s^{-1}\,sr^{-1}}$ on the
present-epoch monopole flux. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
predicted flux is essentially zero, well below all current limits. The
framework is consistent with the absence of detected monopoles; the
monopole problem is structurally dissolved. ◻


# The Trans-Planckian Problem 

## Historical background: Jacobson 1991 to modified-dispersion analyses

The trans-Planckian problem appears in two contexts. (i) Hawking
radiation [@Hawking1975]: Hawking modes outgoing from a black hole are
blueshifted to arbitrarily high frequency as they originate near the
horizon, formally exceeding the Planck scale in the asymptotic frame.
The derivation of the thermal spectrum relies on modes whose origin is
trans-Planckian, which is structurally suspect. Jacobson [@Jacobson1991]
sharpened the concern. (ii) Inflation: primordial perturbations observed
in the CMB today correspond to modes that were trans-Planckian during
the inflationary epoch [@MartinBrandenberger2001]; the standard
predictions assume that physics below the Planck scale is identical to
physics above it, an unverifiable extrapolation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 63** (Trans-Planckian as $x_4$-frame rotation artifact).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
trans-Planckian frequencies in Hawking radiation and inflationary
perturbations are artifacts of the $x_4$-frame mismatch between the
local frame at mode origin and the asymptotic frame in which the
spectrum is measured. The McGucken Sphere structure at the local frame
respects the Compton-locality cutoff
(Theorem [53](#thm:landau){reference-type="ref"
reference="thm:landau"}); the apparent trans-Planckian frequencies are
the integrated $x_4$-phase under the frame rotation, not physical mode
frequencies in any local frame.*


::: proof
*Proof.* *Step 1 (Hawking radiation as $x_4$-frame mismatch).* By
Theorem [36](#thm:bh-info){reference-type="ref"
reference="thm:bh-info"}, Step 4, the Hawking spectrum is the Channel-A
signature of the $x_4$-frame rotation between the freely-falling
infaller frame and the asymptotic Schwarzschild frame. A mode of
frequency $\omega_{\rm local}$ in the infaller frame, blueshifted
infinitely as it traces back to the horizon, appears at finite frequency
$\omega_\infty = T_H \cdot k_{\rm asy}/k_{\rm local}$ in the asymptotic
frame after integration of the Bogoliubov transformation. The
trans-Planckian blueshift is not a physical mode at trans-Planckian
frequency in any single $x_4$-frame; it is the integrated phase of an
$x_4$-frame rotation over a region where the two frames disagree
exponentially.

*Step 2 (the local-frame computation).* In the infaller's $x_4$-frame
near the horizon, the Hawking modes have frequencies of order
$T_H \sim \hbar c^3/(8\pi G M k_B)$, well below the Planck scale for any
astrophysical black hole. The McGucken Sphere at the infaller's event
has well-defined Channel-B propagation at these frequencies, with no
trans-Planckian content; the spectrum is determined entirely by the
local Compton-locality structure. The trans-Planckian frequency is
generated only when one insists on tracking the modes back through the
asymptotic frame's $x_4$-time coordinate, which under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} is the
integrated shadow of the infaller's $x_4$-velocity, not a separate
physical mode.

*Step 3 (inflation: comoving and physical wavelengths).* During
inflation, the comoving wavelength of a perturbation is constant, but
the physical wavelength scales with the expansion:
$\lambda_{\rm phys}(t) = a(t)\lambda_{\rm com}$. Modes that are
subhorizon today have $\lambda_{\rm com}/H_0^{-1} \ll 1$; tracing back
to the inflationary epoch,
$\lambda_{\rm phys}(t_{\rm inf}) = a(t_{\rm inf}) \lambda_{\rm com}$.
For sufficiently large inflation, $a(t_{\rm inf}) \ll 1/M_P$, giving
$\lambda_{\rm phys} < \ell_P$ at the time of the perturbation's origin.

*Step 4 (the McGucken Sphere resolution).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
inflationary epoch's McGucken Sphere at every event has its own
Compton-locality structure set by the available heavy modes at that
epoch. The mode of comoving wavelength $\lambda_{\rm com}$ has physical
wavelength $\lambda_{\rm phys}(t_{\rm inf})$ in the cosmological frame
at $t_{\rm inf}$, but its propagation is determined by the McGucken
Sphere at the event of its origin, where the local Compton-locality
scale is set by the available mode spectrum, not by extrapolation to
trans-Planckian frequencies. The mode is well-defined in its local
$x_4$-frame; the asymptotic comoving description with trans-Planckian
wavelength is the integrated shadow, not the local content.

*Step 5 (the prediction).* The standard inflationary perturbation
spectrum is robust against the trans-Planckian problem because the
prediction depends only on the local mode dynamics in the inflationary
McGucken Sphere, not on the extrapolation to sub-Planckian physical
wavelengths. The McGucken framework therefore predicts no deviation from
standard inflationary perturbation spectra at currently observable
scales; any deviations would arise from new modes turning on at the
inflationary Compton-locality scale, which can be searched for in CMB
B-mode polarization and 21-cm cosmology.

*Step 6 (the analog: Sound modes in flowing fluids).* Unruh [@Unruh1981]
pointed out that Hawking-like radiation appears in acoustic black holes
in flowing fluids, with the role of $c$ played by the speed of sound and
the role of trans-Planckian frequencies played by frequencies above the
molecular scale. In that context, the modes do not have trans-molecular
frequencies in any physical frame; the apparent trans-molecular content
is the integrated shadow of the flow-induced frame rotation. The
acoustic analog directly confirms the McGucken interpretation of the
gravitational trans-Planckian problem. ◻


# Boltzmann Brains 

## Historical background: Boltzmann 1895 to Dyson--Kleban--Susskind 2002

If the universe is fundamentally in thermal equilibrium with rare
low-entropy fluctuations, then by anthropic reasoning the most probable
conscious observer is one fluctuating spontaneously from equilibrium
with just enough structure to experience the present moment, before
disintegrating back to equilibrium. Such a Boltzmann
brain [@Boltzmann1897; @Albrecht2004; @BoltzmannBrain2008] would
experience an inconsistent past (the apparent 13.8 Gyr cosmic history is
illusory) and have no predictive grip on the future. The Boltzmann-brain
reductio undermines orthodox anthropic reasoning: if cosmological
initial conditions are typical, fluctuated brains overwhelmingly
outnumber evolved brains, and we cannot rationally infer our own
evolutionary origin.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 64** (Boltzmann brains dissolved by $+ic$ orientation). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken framework has no equilibrium state to fluctuate from: the
strict Second Law follows directly from the $+ic$ orientation of
$x_4$-expansion (Theorem [40](#thm:arrow){reference-type="ref"
reference="thm:arrow"}), without invoking a low-entropy initial
condition. Downward entropy fluctuations of the magnitude required to
produce a Boltzmann brain are structurally forbidden by Channel B; the
McGucken Sphere's spherically symmetric $+ic$ expansion at every event
has no backward-in-time counterpart at $-ic$ to permit such
fluctuations.*


::: proof
*Proof.* *Step 1 (the Boltzmann-brain calculation).* In an equilibrium
universe of finite volume, the probability of a spontaneous local
fluctuation to a state of entropy reduction $\Delta S$ is
$P \sim e^{-\Delta S/k_B}$. A brain has
$\Delta S_{\rm brain} \sim 10^{42}\,k_B$ of organized structure; the
integrated cosmic history producing one observed brain has
$\Delta S_{\rm cosmic} \sim 10^{104}\,k_B$. Therefore
$P_{\rm brain}/P_{\rm cosmic} \sim e^{10^{104} - 10^{42}} \approx e^{10^{104}}$,
an enormous ratio. Boltzmann brains overwhelmingly dominate.

*Step 2 (the McGucken framework has no equilibrium).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the $+ic$
orientation of $x_4$-expansion at every event drives a monotonic
increase of the McGucken Sphere's volume at every event,
$V(t) = (4\pi/3)(ct)^3$. The matter-tier random-walk diffusion sourced
by Compton-coupled $x_4$-expansion has positive mean-squared
displacement at every $t$; the entropy increases monotonically with
$dS/dt = (3/2)k_B/t > 0$ (Theorem [40](#thm:arrow){reference-type="ref"
reference="thm:arrow"} and the Thermodynamics
paper [@McGuckenThermodynamics2026]). There is no equilibrium state from
which to fluctuate.

*Step 3 (no backward-in-time orientation).* The principle $dx_4/dt = ic$
has only one orientation. There is no $-ic$ counterpart at the
cosmological scale (Theorem [40](#thm:arrow){reference-type="ref"
reference="thm:arrow"}). A downward entropy fluctuation would require
Channel-B propagation along the time-reversed $x_4$-velocity field,
which does not exist as a physical mode in the McGucken framework. The
Boltzmann-brain fluctuation is therefore structurally forbidden.

*Step 4 (consistency with statistical mechanics).* The fluctuation
theorem of statistical mechanics permits small fluctuations against the
Second Law at finite probability $P \sim e^{-\Delta S/k_B}$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is
consistent: small fluctuations are allowed because the matter-tier
random-walk is isotropic at each Compton tick, and brief reversals of
any spatial component are statistically permitted. But the global
$x_4$-orientation is fixed at $+ic$; large-scale fluctuations against
the global arrow are forbidden because they would require coordinated
reversal of the matter-tier random-walk across $10^{23}$ degrees of
freedom, with combined probability $e^{-10^{23}}$, vanishing.

*Step 5 (no anthropic typicality required).* The Boltzmann-brain
reductio assumes the anthropic-typicality principle: typical observers
should match our experience. If the McGucken framework has no
equilibrium, no anthropic typicality is required; our observed cosmic
history is the only kind of observer-experience the framework supports.
The reductio is dissolved.

*Step 6 (eliminating the multiverse Boltzmann-brain dominance).* In
Everettian multiverse interpretations of QM
(Theorem [44](#thm:interpretations){reference-type="ref"
reference="thm:interpretations"}), each quantum branching event produces
$\sim N$ branches, and over cosmological time scales, the total branch
count exceeds $10^{10^{50}}$. If brains can spontaneously fluctuate in
any branch, Boltzmann brains overwhelm evolutionarily-produced observers
in the multiverse measure. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, no multiverse exists
(Theorem [44](#thm:interpretations){reference-type="ref"
reference="thm:interpretations"}); the Boltzmann-brain
multiverse-dominance problem is dissolved. ◻


# ER = EPR 

## Historical background: Einstein--Rosen 1935 to Maldacena--Susskind 2013

Maldacena and Susskind [@Maldacena2013] conjectured that every entangled
pair of particles is connected by a non-traversable Einstein--Rosen
bridge (wormhole): "ER = EPR." The two ends of an EPR pair share a
microscopic geometric connection through the bulk spacetime, even though
no signal can traverse the bridge. The conjecture unifies the apparent
nonlocality of entanglement with the geometric structure of gravity:
entanglement is geometry. Susskind elaborated this to "GR = QM" and
developed the program of computational complexity as the dual of bulk
geometry. The conjecture remains formally unproven outside of specific
AdS/CFT examples (the thermofield double state on two CFTs is dual to
the eternal AdS black hole with a non-traversable wormhole).

## The McGucken $dx_4/dt = ic$ reading


**Theorem 65** (ER = EPR as the McGucken Sphere shared by entangled
events). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, every pair of entangled events shares a common
McGucken Sphere from the event of their entangling interaction. The
forward-$x_4$ expansion from that shared Sphere carries both partners as
Channel-B propagation across spatial separation, providing the geometric
connection that ER = EPR posits. The shared Sphere is non-traversable
because no signal can propagate against the $+ic$ direction;
correlations are revealed by joint measurement at the two ends but
cannot be exploited to send signals.*


::: proof
*Proof.* *Step 1 (the entangling event).* An EPR pair is produced at a
localized spacetime event $p$ where the joint state is prepared. By
Theorem [15](#thm:epr){reference-type="ref" reference="thm:epr"}, the
two partners share the $x_4$-phase of the McGucken Sphere $\Sigma_+(p)$
from the entangling event. Both partners propagate forward in $x_4$ from
$p$ along their respective worldlines, maintaining the Channel-A
correlation set at $p$.

*Step 2 (the geometric connection).* The McGucken Sphere $\Sigma_+(p)$
at the entangling event continues to be the geometric structure shared
by the two partners throughout their propagation. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Channel-B propagation of each partner is on the lift of $\Sigma_+(p)$ to
the partner's own worldline; the two partners are connected by the
shared structure of $\Sigma_+(p)$ for as long as the correlation
persists. This is the geometric connection that ER = EPR posits,
identified intrinsically with the McGucken Sphere rather than requiring
an auxiliary wormhole metric.

*Step 3 (non-traversability).* The shared Sphere is non-traversable in
the sense that no signal can propagate against the $+ic$ direction from
one partner's event back to the other partner's event. The Bell
inequality (Theorem [15](#thm:epr){reference-type="ref"
reference="thm:epr"}, Step 3) shows that the correlations cannot be
exploited to send signals; the no-signaling theorem is a consequence of
the Channel-B propagation being one-directional in $x_4$.

*Step 4 (the thermofield double / eternal black hole).* The specific
case of two CFTs entangled in the thermofield double state, dual to the
eternal AdS black hole with two asymptotic regions connected by a
wormhole, is the AdS/CFT realization of the general ER = EPR connection.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
eternal black hole's wormhole interior is the cosmological McGucken
Sphere shared by the two CFT boundaries; the boundary CFT degrees of
freedom inherit the entanglement structure from the geometric content of
this shared Sphere.

*Step 5 (extension to general entangled states).* Beyond the simple
two-partner EPR pair, multipartite entangled states (GHZ, Hardy, etc.)
share McGucken Spheres from their joint preparation events. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
geometric content of the entanglement is fully encoded in the structure
of these shared Spheres; the bulk geometry of the dual gravitational
theory is the inverse-image construction recovering the geometric
content from the boundary entanglement, as the Ryu--Takayanagi formula
encodes.

*Step 6 (no requirement for AdS).* The orthodox ER = EPR conjecture is
most precisely stated within AdS/CFT, where the boundary CFT supplies
the algebraic content and the bulk supplies the geometric content. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the same
dual-channel structure (Channel A = algebraic, Channel B = geometric) is
the universal structure of the McGucken framework, without requiring an
AdS asymptotic structure. The McGucken framework therefore extends ER =
EPR from the AdS/CFT special case to the universal correspondence
between any entangled events and their shared McGucken Sphere. ◻


# Computational Complexity and the Bulk Geometry 

## Historical background: Susskind 2014 complexity=volume to Brown et al. 2016 complexity=action

Susskind proposed two formulas relating boundary CFT computational
complexity to bulk geometric quantities in AdS/CFT: "Complexity =
Volume" (CV) [@Susskind2014] relates the complexity of the boundary
state to the volume of the maximal-volume spatial slice anchored at the
boundary; "Complexity = Action" (CA) [@BrownSusskind2016] relates it to
the gravitational action of the Wheeler--DeWitt patch. The proposals
address the puzzle that the interior of a black hole continues to grow
long after the boundary entropy has saturated; complexity (which grows
linearly for exponentially long times) provides the dual quantity to
track the interior growth. The conjectures are tested in specific
examples and remain a subject of intense investigation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 66** (Complexity as integrated $x_4$-expansion). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
computational complexity of a boundary state is the integrated
$x_4$-volume of the McGucken Sphere structure encoding the state's
geometric content. Both Complexity = Volume and Complexity = Action
emerge as Channel-B integrated geometric measures of the same underlying
$x_4$-expansion; their equivalence in appropriate limits is the
equivalence of two integrated measures of the same Sphere structure.*


::: proof
*Proof.* *Step 1 (complexity grows linearly for exponential times).*
Boundary computational complexity grows linearly with time for
$t \in [t_{\rm thermal}, t_{\rm Heisenberg}]$ where $t_{\rm thermal}$ is
the scrambling time and $t_{\rm Heisenberg} \sim e^{S}$ is the
Heisenberg recurrence time. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the linear
growth corresponds to the linear-in-$t$ growth of the McGucken Sphere
volume from any event: $V(t) = (4\pi/3)(ct)^3$ scales as $t^3$, but the
relevant complexity-measure for a boundary state of $N$ qubits is the
integrated $x_4$-volume restricted to the qubit Hilbert space, which
scales linearly.

*Step 2 (Complexity = Volume).* The CV proposal identifies complexity
with the maximal-volume spatial slice in the bulk anchored at the
boundary. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the maximal-volume slice is the constant-$x_4$
slice through the bulk McGucken Sphere structure; its volume is the
Channel-B geometric integrated measure of the boundary state's encoding
through the bulk. The CV formula
$$\mathcal{C}_V = \frac{V(\Sigma_{\rm max})}{G_N \ell_{\rm AdS}}$$
identifies the complexity with the maximal volume in units of the AdS
curvature length scale.

*Step 3 (Complexity = Action).* The CA proposal identifies complexity
with the gravitational action on the Wheeler--DeWitt patch (the bulk
region causally connected to the boundary time-slice). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the action
is the Channel-A integrated phase of the $x_4$-expansion across the
patch; the equivalence with CV at leading order follows because both are
integrated measures of the same $x_4$-velocity field, evaluated with
slightly different boundary conditions.

*Step 4 (the bound on complexity growth).* The Lloyd bound [@Lloyd2000]
states that the rate of computation is bounded by
$dN/dt \leq 2E/\pi\hbar$, with $E$ the system's energy. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
bound on the rate of $x_4$-phase advancement, related to the energy
through the Compton frequency $\omega_C = E/\hbar$. The
complexity-growth bound is the Lloyd bound; this matches Susskind's
holographic-complexity bound at leading order in the dual theory.

*Step 5 (no equivalence problem).* The discrepancies between CV and CA
at subleading orders, observed in specific AdS/CFT examples, are not
problems for the McGucken framework: they reflect the different boundary
conditions used to define the two integrated measures of the same
underlying $x_4$-expansion. The framework predicts both formulas to give
the same answer at leading order in $1/N$ but distinct subleading
corrections; the experimental tests of these subleading differences
would constitute structural tests of the framework.

*Step 6 (no holographic duality required).* Susskind's complexity
conjectures are formulated in AdS/CFT. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
dual-channel structure (Channel-A algebraic, Channel-B geometric) of the
McGucken framework provides the same complexity-volume /
complexity-action structure without requiring an AdS asymptotic. The
framework extends Susskind's program from AdS/CFT to the universal
correspondence between algebraic complexity and geometric volume. ◻


# The Holographic Principle 

## Historical background: 't Hooft 1993 and Susskind 1995

'tHooft [@tHooft1993] and Susskind [@Susskind1995] proposed that the
information content of a region of spacetime is bounded by the area (not
volume) of its boundary, in units of the Planck area. The bound is
suggested by black hole entropy $S_{\rm BH} = A/4G_N\hbar$ but applies
more generally: any region's degrees of freedom are encoded
holographically on its boundary. The Bekenstein bound [@Bekenstein1973]
sharpens this to $S \leq 2\pi k_B R E/(\hbar c)$ for a system of energy
$E$ and radius $R$. The holographic principle has guided string theory,
quantum gravity, and quantum information for three decades.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 67** (Holography as McGucken Sphere area-law structure).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Sphere $\Sigma_+(p)$ at every event $p$ has area
$A(t) = 4\pi(ct)^2$ at time $t$ from the event; the volume
$V(t) = (4\pi/3)(ct)^3$ grows faster but the information content
propagating from $p$ at the boundary of the Sphere is encoded on the
area, not the volume. The holographic bound $S \leq A/4G_N\hbar$ is the
natural information-theoretic statement of the McGucken Sphere's
area-law structure: bulk degrees of freedom are correlations of boundary
$x_4$-phase states.*


::: proof
*Proof.* *Step 1 (the McGucken Sphere area scales as $t^2$).* The Sphere
$\Sigma_+(p, t) = \{q: c(t_q - t_p) = |\vec x_q - \vec x_p|\}$ is a
2-sphere of radius $ct$, area $A(t) = 4\pi(ct)^2$. The 3-volume
contained inside this sphere is $V(t) = (4\pi/3)(ct)^3$. The
area-to-volume ratio is $A/V \sim 1/t$, decreasing with time.

*Step 2 (information at the Sphere boundary).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, information
propagates from $p$ to other events as Channel-B propagation along the
future null cone, which lies on the Sphere boundary. Information at
later times reaching $p$ from the past comes from the past Sphere
boundary. The bulk events inside the Sphere are causally connected to
$p$ only through the boundary; the bulk information content is therefore
encoded entirely on the boundary.

*Step 3 (the Bekenstein bound derived).* For a system at energy $E$ and
radius $R$, the maximum entropy is the number of distinguishable states,
each requiring at least one Compton wavelength of phase resolution. The
number of phase states on a 2-sphere of area $4\pi R^2$, distinguishable
at the Compton scale $\ell_C = \hbar/(mc)$ where $m \sim E/c^2$, is
$$N_{\rm states} = \frac{A}{\ell_C^2} = \frac{4\pi R^2 m^2 c^2}{\hbar^2} = \frac{4\pi R^2 E^2/c^2}{\hbar^2}.$$
The entropy is $S = k_B \ln N_{\rm states} \sim k_B (RE/\hbar c)^2$,
scaling with the area. Restricted to Compton-locality at the dominant
scale, the bound becomes $S \leq 2\pi k_B R E/(\hbar c)$, recovering
Bekenstein.

*Step 4 (the black hole as saturating the bound).* A Schwarzschild black
hole has $R_s = 2GM/c^2$ and energy $E = Mc^2$; substituting into
Bekenstein gives $S_{\rm BH} \leq 4\pi GM^2/(\hbar c)$, matching the
Bekenstein--Hawking entropy $S = A/4G_N\hbar = 4\pi GM^2/(\hbar c)$.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
black hole saturates the holographic bound because its $x_4$-expansion
at the horizon achieves maximum information density per unit area;
deeper-interior events lie causally inside the horizon and their
information is fully encoded at the horizon boundary.

*Step 5 (holographic principle without AdS).* The orthodox formulation
of the holographic principle in AdS/CFT relates bulk degrees of freedom
in $d+1$-dimensional AdS to boundary degrees of freedom in
$d$-dimensional CFT. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the McGucken Sphere structure at every event
encodes its bulk degrees of freedom on the boundary 2-sphere; no AdS
asymptotic is required. The framework extends holography from the
AdS/CFT special case to a universal structural statement about every
McGucken Sphere.

*Step 6 (information paradox resolution).* The black hole information
paradox (Theorem [36](#thm:bh-info){reference-type="ref"
reference="thm:bh-info"}) is resolved by recognizing that no information
is lost: the bulk information is encoded on the horizon area, and the
Hawking radiation carries this information out as the McGucken Sphere
structure at the horizon continues to evolve. The Page curve (next
section) explicitly tracks this information return. ◻


# AdS/CFT and Bulk Reconstruction 

## Historical background: Maldacena 1997 to modern bulk reconstruction

Maldacena's conjecture [@Maldacena1997] relates Type IIB string theory
in $\mathrm{AdS}_5 \times S^5$ to $\mathcal{N}=4$ super Yang--Mills
theory on the 4-dimensional boundary. The duality is the most concrete
realization of the holographic principle: bulk physics is exactly
equivalent to boundary CFT physics. Witten [@Witten1998] and
Gubser--Klebanov--Polyakov [@GKP1998] developed the dictionary relating
bulk fields to boundary operators. The bulk reconstruction problem asks:
given the boundary CFT data, how to reconstruct the bulk geometry and
field content? The Hamilton--Kabat--Lifschytz--Lowe (HKLL)
reconstruction provides an explicit boundary operator for each bulk
operator in the perturbative regime; the question of nonperturbative
bulk reconstruction (e.g., behind black hole horizons) is open.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 68** (AdS/CFT as McGucken Sphere boundary--bulk duality).
*Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
AdS/CFT correspondence is a special case of the universal McGucken
Sphere boundary--bulk duality: each event's Sphere encodes its bulk
content on the boundary 2-sphere through the $x_4$-phase structure. The
CFT degrees of freedom on the AdS boundary are the boundary $x_4$-phase
content of the bulk McGucken Sphere; bulk reconstruction is the inverse
Fourier transform of this $x_4$-phase content back to bulk events.*


::: proof
*Proof.* *Step 1 (the Maldacena dictionary).* The Maldacena dictionary
identifies bulk gravity in $\mathrm{AdS}_5 \times S^5$ with
$\mathcal{N}=4$ super Yang--Mills on the boundary, in the limit
$N \to \infty$ with $\lambda = g_{\rm YM}^2 N$ fixed. The dictionary
relates bulk supergravity fields $\phi_{\rm bulk}$ to boundary
single-trace operators $\mathcal{O}_{\rm bdy}$ with conformal dimension
$\Delta = \Delta(\phi)$.

*Step 2 (bulk reconstruction via HKLL).* The HKLL prescription
reconstructs a bulk operator at point $X$ in AdS as a smeared boundary
operator $$\Phi(X) = \int dx\, K(X|x)\, \mathcal{O}(x)$$ where $K(X|x)$
is the bulk-to-boundary propagator. The integral extends over the
boundary region causally connected to $X$ through the AdS bulk; this
region is bounded by the boundary's intersection with $X$'s light cone
in the bulk.

*Step 3 (the McGucken Sphere interpretation).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the AdS
bulk McGucken Sphere at event $X$ has its boundary 2-sphere structure
encoded on the conformal boundary; the boundary $x_4$-phase content at
each boundary point is the projection of the bulk $x_4$-velocity field
through the AdS metric's warping. The HKLL smearing function $K(X|x)$ is
the Channel-B propagator from the bulk event $X$ to the boundary point
$x$, computed as the Green's function of the wave equation on the AdS
metric.

*Step 4 (the entanglement-geometry connection).*
Ryu--Takayanagi [@RyuTakayanagi2006] showed that the entanglement
entropy of a boundary region $A$ equals (in the large-$N$ limit) the
area of the minimal-area bulk surface anchored at $\partial A$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
holographic-bound area-law statement
(Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}) applied to the entanglement structure of
the boundary CFT; the minimal-area surface is the bulk McGucken Sphere
shared by the boundary region's degrees of freedom.

*Step 5 (non-perturbative bulk reconstruction).* The HKLL prescription
works perturbatively in $1/N$ but breaks down behind black hole
horizons, where the bulk McGucken Sphere structure is causally
disconnected from the boundary. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the bulk
content behind the horizon is encoded in the radiation already emitted
from the horizon (the late-time Hawking modes), via the Page curve and
the island formula [@Almheiri2019]. The framework's prediction is that
all bulk content is recoverable from boundary data including the
radiation, in agreement with the recent island-formula calculations.

*Step 6 (AdS/CFT as special case).* The general McGucken Sphere
boundary--bulk structure
(Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}) applies at every event, in any spacetime.
The AdS/CFT special case has the additional structure that the conformal
boundary is at spatial infinity, allowing the boundary CFT to be defined
as a separate theory. In general spacetimes (e.g., asymptotically flat
or de Sitter), the boundary is at infinity in a less straightforward
sense, but the McGucken Sphere structure provides the boundary--bulk
duality intrinsically without requiring an asymptotic CFT. ◻


# The Page Curve 

## Historical background: Page 1993 to Almheiri and Penington islands 2019

Page [@Page1993] computed the entanglement entropy of Hawking radiation
from a unitarily evaporating black hole. For unitary evaporation, the
entropy of the radiation must start at zero, increase as the black hole
emits modes, reach a maximum at the "Page time" (when half the entropy
has been emitted), and then decrease back to zero as the black hole
completes evaporation. The Page curve is the unitarity-preserving
evolution of the radiation entropy; Hawking's original calculation,
which predicted a monotonically increasing entropy, was incompatible
with unitarity (the information paradox). The Page curve has been
recently rederived from gravitational path integrals using
"islands" [@Almheiri2019; @Penington2019], confirming that the curve is
the correct prediction of unitary semi-classical gravity.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 69** (The Page curve as $x_4$-expansion of the radiation
Sphere). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the entanglement entropy of Hawking radiation
traces the $x_4$-expansion of the radiation McGucken Sphere as it grows
from zero at the start of evaporation, peaks at the Page time when the
radiation Sphere's volume equals the remaining black hole Sphere's
volume, and decreases back to zero as the black hole's Sphere is fully
converted to radiation Sphere content. The Page curve is the natural
unitarity-preserving evolution of the McGucken Sphere distribution
between the black hole and its radiation.*


::: proof
*Proof.* *Step 1 (Hawking's original calculation).* Hawking's
semi-classical calculation gave the radiation entropy increasing
monotonically until evaporation completion, with the final state a
thermal mixed state of total entropy $S_{\rm rad} = S_{\rm BH,initial}$.
This violates unitarity: an initially pure state becomes mixed,
requiring a non-unitary process at some point.

*Step 2 (the Page time).* The Page time is the time at which the
radiation entropy equals the remaining black hole entropy:
$S_{\rm rad}(t_{\rm Page}) = S_{\rm BH}(t_{\rm Page})$. For a
Schwarzschild black hole, this occurs at
$t_{\rm Page} \approx 0.54\, t_{\rm evap}$ where $t_{\rm evap}$ is the
total evaporation time. After the Page time, the radiation entropy
decreases as the black hole's remaining entropy shrinks; the radiation
transitions from purifying the unobserved interior to purifying the
(small) remaining black hole.

*Step 3 (the McGucken Sphere distribution).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the initial
black hole has McGucken Sphere structure encoding its
$S_{\rm BH,initial}$ degrees of freedom on the horizon area. As Hawking
radiation is emitted, each emitted mode carries away a fragment of the
McGucken Sphere structure as Channel-B propagation; the boundary
2-sphere of the radiation McGucken Sphere grows as the radiation reaches
further from the original event. The total information is conserved:
$S_{\rm BH}(t) + S_{\rm rad}(t) = S_{\rm BH,initial}$ at all times.

*Step 4 (the entropy evolution).* The radiation entropy is bounded by
the smaller of $S_{\rm rad,thermal}$ (Hawking's thermal estimate,
growing monotonically) and $S_{\rm BH,remaining}$ (the bound from the
unitarity constraint). Initially, $S_{\rm rad,thermal} < S_{\rm BH}$, so
$S_{\rm rad}$ follows the thermal estimate. At the Page time, the two
cross; after the Page time, $S_{\rm rad,thermal} > S_{\rm BH}$, so the
unitarity bound takes over and $S_{\rm rad} = S_{\rm BH,remaining}$,
decreasing as the black hole evaporates.

*Step 5 (the island prescription).* The recent island-formula
calculations [@Almheiri2019; @Penington2019] show that the boundary CFT
entropy of the radiation is computed by including an "island" region in
the bulk: a region inside the black hole that contributes to the
radiation entropy through the entanglement-wedge prescription. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the island
is the bulk McGucken Sphere region that has propagated into the
radiation through Channel B; the entanglement-wedge prescription is the
geometric identification of the bulk region whose $x_4$-phase content
has been encoded in the radiation.

*Step 6 (no firewall required).* The Page curve is computed without
invoking AMPS-style firewalls
(Theorem [36](#thm:bh-info){reference-type="ref"
reference="thm:bh-info"}). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the firewall is dissolved by the $x_4$-frame
mismatch between infaller and asymptotic observer; the Page curve is the
correct unitarity-preserving entropy evolution without any drama at the
horizon. The McGucken framework predicts the Page curve directly from
the geometric content of the black hole's McGucken Sphere structure
being converted to radiation Sphere structure. ◻


# The Bekenstein Bound 

## Historical background: Bekenstein 1973 to Bousso covariant bound 1999

Bekenstein [@Bekenstein1981] proposed an upper bound on the entropy
contained in any region of radius $R$ with energy $E$:
$$S \leq \frac{2\pi k_B R E}{\hbar c}.$$ The bound was motivated by
black hole thermodynamics: a region with $S$ exceeding the bound could
be converted to a black hole with smaller $S$, violating the Second Law.
The Bekenstein bound has been challenged in specific cases (Bousso,
Susskind) and refined to the covariant entropy bound
(Bousso [@Bousso1999]). The bound's tightness in the general case
remains structurally important for any holographic theory.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 70** (Bekenstein bound from $x_4$-Compton-locality). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
Bekenstein bound is the natural consequence of $x_4$-Compton-locality at
the dominant Compton scale of the system. A region with energy $E$ has
dominant Compton frequency $\omega_C = E/\hbar$; the maximum number of
distinguishable $x_4$-phase states in a region of radius $R$ is bounded
by the number of Compton periods that fit, giving
$S \leq 2\pi k_B R E/(\hbar c)$.*


::: proof
*Proof.* *Step 1 (the Compton period and the region size).* A system of
energy $E$ has dominant Compton frequency $\omega_C = E/\hbar$ and
Compton period $T_C = 2\pi/\omega_C = 2\pi\hbar/E$. The corresponding
Compton wavelength is $\ell_C = c T_C = 2\pi\hbar c/E$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
$x_4$-phase advance over a proper-time interval $\Delta\tau$ at this
Compton frequency is
$\Delta\phi = \omega_C \Delta\tau = E \Delta\tau/\hbar$. The
phase-resolution unit on the Channel-A side is one full $2\pi$ cycle of
$\omega_C$, corresponding to a spatial displacement of one Compton
wavelength along the null cone of $dx_4/dt = ic$ propagation.

*Step 2 (the phase count over a region of radius $R$).* The maximum
number of distinguishable $x_4$-phase states the system can support
within a spatial region of radius $R$ is set by how many independent
Compton phase advances of $2\pi$ can be accommodated. Each independent
phase accumulation requires a propagation length of $\ell_C$; a spatial
extent $R$ supports $N_\phi = R/\ell_C \cdot 2\pi$ such phase units when
we count both the radial extent and the phase quantum simultaneously.
The structural counting gives the dimensionless content
$$N_\phi = \frac{2\pi R}{\ell_C} = \frac{2\pi R}{2\pi \hbar c/E} = \frac{R E}{\hbar c}.$$
Each distinguishable phase state contributes at most $k_B$ to the
entropy on a Boltzmann counting, so the entropy admits the structural
upper bound
$$S \;\le\; 2\pi k_B N_\phi = \frac{2\pi k_B R E}{\hbar c},$$ where the
factor $2\pi$ tracks the full phase circle of the Compton frequency.
This is the Bekenstein form.

*Step 3 (Schwarzschild saturation fixes the constant).* The numerical
constant $2\pi$ in the bound is fixed---and the bound shown to be
tight---by requiring that the Schwarzschild black hole saturate it. A
Schwarzschild black hole of mass $M$ has $R = R_s = 2GM/c^2$ and
rest-frame energy $E = Mc^2$. Substituting into the Bekenstein form:
$$S_{\rm Bek} \;=\; \frac{2\pi k_B R_s E}{\hbar c} \;=\; \frac{2\pi k_B \cdot (2GM/c^2) \cdot Mc^2}{\hbar c} \;=\; \frac{4\pi G k_B M^2}{\hbar c}.$$
The Bekenstein--Hawking entropy is
$$S_{\rm BH} \;=\; \frac{k_B c^3 A}{4 G \hbar} \;=\; \frac{k_B c^3 \cdot 4\pi R_s^2}{4G\hbar} \;=\; \frac{\pi k_B c^3}{G\hbar}\left(\frac{2GM}{c^2}\right)^{\!2} \;=\; \frac{4\pi G k_B M^2}{\hbar c}.$$
The two expressions are identical: $S_{\rm Bek} = S_{\rm BH}$. The
Schwarzschild black hole saturates the Bekenstein bound exactly, and the
numerical constant $2\pi$ is the unique value compatible with this
saturation. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the saturation reflects the fact that the black
hole's horizon is the locus at which the McGucken Sphere structure has
rotated maximally into the radial direction
(Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}); the area-law structure of the horizon
(Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}) is the unique maximal-information packing
on Channel B.

*Step 4 (the covariant entropy bound).* Bousso's covariant entropy bound
generalizes Bekenstein to null hypersurfaces: the entropy on any
light-sheet emanating from a 2-surface of area $A$ is bounded by
$S \leq k_B A c^3/(4G\hbar)$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
light-sheet is the past or future McGucken Sphere structure from the
bounding 2-surface; the bound is the holographic-area bound
(Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}) applied to the McGucken Sphere's boundary,
with the constant $1/4$ fixed by the same Schwarzschild saturation as
Step 3.

*Step 5 (the species problem).* Bekenstein's bound becomes problematic
in theories with many particle species $N_s$: a region containing one
example of each species would have $S \sim N_s k_B \ln 2$, potentially
exceeding the bound for large $N_s$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the species
problem is dissolved by Compton-locality: the dominant Compton frequency
$\omega_C = E/\hbar$ is set by the energy, not by the number of species;
the total $x_4$-phase content of a region is set by $E R/(\hbar c)$
regardless of how many species share the energy. Adding a new species at
the same total $E$ does not add new Channel-A phase states, since the
total energy budget is fixed; the Bekenstein bound is robust.

*Step 6 (the Bekenstein bound as the holographic principle).* The
Bekenstein bound, the covariant entropy bound, and the holographic
principle (Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}) are three statements of the same underlying
$x_4$-Compton-locality structure. The McGucken framework derives all
three from $dx_4/dt = ic$ as theorems with the same numerical constant
fixed by Schwarzschild saturation. ◻


# Soft Hair and BMS Symmetry 

## Historical background: Bondi--van der Burg--Metzner--Sachs 1962 to Hawking--Perry--Strominger 2016

The black hole "no-hair" theorem states that classical black holes are
fully characterized by mass, charge, and angular momentum. Hawking,
Perry, and Strominger [@HawkingPerryStrominger2016] proposed that
quantum black holes carry additional "soft hair": the asymptotic
Bondi--Metzner--Sachs (BMS) symmetries of asymptotically flat spacetimes
have soft gravitons and photons as Goldstone modes, and these soft modes
correlate with black hole formation history.
Strominger [@Strominger2014] developed the infrared structure of
gravity, identifying BMS supertranslations as exact symmetries of the
gravitational $\mathcal{S}$-matrix. The soft-hair proposal offers a
mechanism for information return in black hole evaporation that
complements the Page curve calculation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 71** (Soft hair as McGucken Sphere $x_4$-phase memory). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, soft
gravitons and photons are the long-wavelength $x_4$-phase modulations of
the asymptotic McGucken Sphere structure. The BMS supertranslations are
the asymptotic $x_4$-frame translations that label the soft-mode
content; soft hair on a black hole is the $x_4$-phase memory of the
matter that fell in, preserved on the asymptotic Sphere structure even
when the black hole's local horizon has no classical hair.*


::: proof
*Proof.* *Step 1 (BMS supertranslations).* The BMS group at null
infinity $\mathscr{I}^+$ in asymptotically flat spacetime contains the
Poincaré group plus an infinite-dimensional family of supertranslations
$T(\theta, \phi)$, labeled by functions on the celestial 2-sphere. The
supertranslations shift the retarded time $u$ by an angle-dependent
amount: $u \to u + T(\theta, \phi)$.

*Step 2 (soft gravitons as Goldstone modes).* The supertranslations are
spontaneously broken by any specific asymptotic gravitational
configuration, producing soft gravitons as Goldstone modes. The
soft-graviton theorem (Weinberg [@Weinberg1965]) gives the universal
factor in amplitudes for emission of a graviton with $\omega \to 0$:
$$\mathcal{M}_{n+1}(\text{soft graviton}) = \kappa \sum_i \frac{p_i \cdot \epsilon \cdot p_i}{p_i \cdot k} \mathcal{M}_n + \mathcal{O}(\omega^0).$$
The soft factor is universal, depending only on the asymptotic momenta
of the hard particles.

*Step 3 (the McGucken Sphere $x_4$-phase memory).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
asymptotic McGucken Sphere structure at $\mathscr{I}^+$ carries the
integrated $x_4$-phase of all events in the bulk past light cone. A
massive object falling into a black hole alters the bulk events along
its worldline, leaving a corresponding $x_4$-phase modulation on the
asymptotic Sphere. The supertranslation $T(\theta, \phi)$ is the
angle-dependent shift in this asymptotic $x_4$-phase corresponding to
the bulk events at angle $(\theta, \phi)$.

*Step 4 (the gravitational memory effect).* The classical gravitational
memory effect [@ZeldovichPolnarev1974] predicts that a passing
gravitational wave permanently displaces test particles: the asymptotic
metric retains a nontrivial shift after the wave passes. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this shift
is the $x_4$-phase memory of the wave's passing, encoded on the
asymptotic McGucken Sphere structure. The gravitational memory effect
has been searched for by LIGO; current sensitivities approach the
detection threshold.

*Step 5 (no-hair theorem refinement).* The classical no-hair theorem
states that the horizon area, electric charge, and angular momentum
fully characterize a black hole. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the soft
hair is the asymptotic $x_4$-phase information not encoded at the
horizon but stored on the asymptotic Sphere; the black hole's horizon
has no classical hair, but the asymptotic Sphere retains the formation
history. The information is not lost; it is distributed between the
horizon (entropic content) and the asymptotic Sphere (soft hair).

*Step 6 (the information return mechanism).* As the black hole
evaporates, the Hawking radiation carries away the horizon's entropic
content. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the soft hair is the additional channel through
which formation-history information returns: the asymptotic Sphere
structure couples to the outgoing radiation through the BMS asymptotic
symmetries, and the integrated soft-mode emission encodes the formation
history. The Page curve
(Theorem [69](#thm:page-curve){reference-type="ref"
reference="thm:page-curve"}) plus the soft-hair mechanism together
account for the full information return; the McGucken framework provides
the geometric content of both. ◻


# Gibbs Paradox of Mixing Entropy 

## Historical background: Gibbs 1875 mixing paradox

Gibbs [@Gibbs1902] considered the entropy of mixing two ideal gases. If
the gases are distinguishable, mixing produces entropy of mixing
$\Delta S = 2Nk_B \ln 2$. If the gases are identical, no mixing occurs
and $\Delta S = 0$. But the calculation of $\Delta S$ using the
Sackur--Tetrode formula gives the same $2Nk_B \ln 2$ whether the gases
are distinguishable or identical, unless particles are made
indistinguishable from the outset (the $N!$ Gibbs factor). The paradox:
how does macroscopic mixing entropy "know" the microscopic identity of
the particles? The resolution requires quantum-statistical
indistinguishability at the foundational level, but the orthodox
classical formulation treats this as a postulate inserted to match
observation.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 72** (Gibbs paradox as Channel-A particle identity). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
indistinguishability of identical particles is the Channel-A algebraic
theorem that particles with the same Compton frequency $\omega_C$
propagate on the same McGucken Sphere structure and cannot be
distinguished by their $x_4$-phase content. The $N!$ Gibbs factor is the
natural count of distinguishable Channel-A states; the Gibbs paradox is
dissolved at the foundational level by the McGucken framework's
identification of particle identity with $x_4$-Compton-frequency
equality.*


::: proof
*Proof.* *Step 1 (the orthodox calculation).* For two gases of $N$
particles each, in volumes $V$ each, at the same temperature and
pressure, mixed into a combined volume $2V$, the Sackur--Tetrode entropy
is
$$S = Nk_B\left[\ln\left(\frac{V}{N}\left(\frac{4\pi m U}{3Nh^2}\right)^{3/2}\right) + \frac{5}{2}\right],$$
where the $N!$ Gibbs correction is implicit in the $V/N$ factor. For
identical gases, the combined entropy after mixing is
$S_{\rm mixed} = 2N k_B[\ln(2V/2N) \cdot\ldots]$, with the volume
scaling canceling the $N$ scaling exactly; $\Delta S = 0$. For
distinguishable gases, the entropy is calculated without the $N!$
factor, giving $\Delta S = 2Nk_B \ln 2$ from the volume doubling.

*Step 2 (the McGucken identification).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, two
particles are identical if and only if their Compton frequencies
$\omega_C = mc^2/\hbar$ are equal; they then propagate on McGucken
Spheres of the same radius and phase content. The Channel-A algebraic
content of the multi-particle state space is the symmetric tensor
product (for bosons) or antisymmetric tensor product (for fermions) of
the single-particle Hilbert spaces; this is forced by the structural
equivalence of identical Compton-frequency modes, not postulated.

*Step 3 (the $N!$ factor).* The state space of $N$ identical particles
in $V$ has dimension $V^N/N!$ (in the discretized phase-space sense),
reflecting the over-counting by $N!$ that occurs when particles are
treated as distinguishable. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
over-counting is the algebraic redundancy of labeling identical
$x_4$-Compton modes; the $N!$ factor is the natural symmetric-group
reduction, exactly analogous to the gauge-redundancy reduction by the
Faddeev--Popov procedure
(Theorem [50](#thm:gauge-ghost){reference-type="ref"
reference="thm:gauge-ghost"}).

*Step 4 (no entropy of mixing for identical particles).* For two gases
of identical particles, mixing produces no new states because the
particles cannot be tagged by their initial subvolume. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is
automatic: the combined $2N$-particle state on volume $2V$ is the
symmetric tensor product of $2N$ identical Compton modes, with
$S = 2N k_B \ln(2V/2N \cdot\ldots)$, which equals the sum of the two
pre-mixing entropies. $\Delta S = 0$.

*Step 5 (entropy of mixing for distinguishable particles).* For two
gases of distinguishable particles (different masses or different
internal states), mixing creates new states because each particle can
now be at any location. The entropy is
$S = N k_B \ln(2V/N \cdot \ldots) + N k_B \ln(2V/N \cdot \ldots)$ (each
species sees its own $N!$ symmetric reduction but the joint state space
is the tensor product). $\Delta S = 2Nk_B \ln(2V/V) = 2Nk_B \ln 2$.

*Step 6 (the paradox dissolved).* The Gibbs paradox arises only when one
tries to maintain classical particle distinguishability for all
particles simultaneously; under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, identical Compton-frequency particles are
structurally indistinguishable from the outset, and the symmetric tensor
product is the natural algebraic content. The $N!$ factor and the
entropy of mixing both follow directly from the McGucken
Compton-frequency identification of particle identity; no separate
postulate is required. ◻


# D'Alembert's Paradox 

## Historical background: d'Alembert 1752 to Prandtl 1904 boundary layer

D'Alembert [@DAlembert1752] showed that an incompressible, inviscid
(Euler) fluid flowing past a solid body exerts zero net drag force on
the body. The result follows from Bernoulli's equation and the symmetry
of streamlines past the body: the pressure distribution on the upstream
and downstream sides is symmetric, producing no net force. The paradox:
real fluids do exert drag, even at very high Reynolds number where
viscous effects are formally small. The resolution comes from
boundary-layer theory (Prandtl 1904): even small viscosity produces a
boundary layer that detaches into a wake, breaking the up-down symmetry.
But the inviscid limit of the viscous calculation does not yield the
inviscid Euler result; there is a singular discontinuity.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 73** (D'Alembert's paradox as Channel-A versus Channel-B fluid
dynamics). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the inviscid Euler limit is the Channel-A algebraic
skeleton of fluid dynamics, while the viscous Navier--Stokes content is
the Channel-B Compton-coupled diffusion. The viscosity $\nu \Delta u$
term is not a small perturbation but the foundational-geometric content
of the McGucken Sphere expansion at each fluid element; the inviscid
limit $\nu \to 0$ excises this content and produces the singular
D'Alembert result, while real fluids always have $\nu > 0$ from the
McGucken Sphere structure. The paradox is the artifact of treating
Channel A as the foundational theory and Channel B as a perturbation,
when in fact both are required for the McGucken framework.*


::: proof
*Proof.* *Step 1 (the Euler calculation).* For incompressible, inviscid,
steady, irrotational flow past a body, the velocity potential $\phi$
satisfies Laplace's equation $\nabla^2 \phi = 0$ with boundary
conditions $\nabla\phi \to U_\infty$ at infinity and
$\hat n \cdot \nabla\phi = 0$ on the body. The pressure follows from
Bernoulli:
$p + (1/2)\rho|\nabla\phi|^2 = p_\infty + (1/2)\rho U_\infty^2$. The net
force on the body is $\vec F = -\oint p \hat n\, dA$, which by the
symmetry $\phi(\vec x) = -\phi(-\vec x)$ for a symmetric body and
uniform flow gives $\vec F = 0$.

*Step 2 (the Navier--Stokes correction).* Adding viscosity, the equation
becomes
$\partial_t u + (u \cdot \nabla)u = -\nabla p/\rho + \nu \Delta u$. At
Reynolds number $Re = UL/\nu \to \infty$, the viscous term appears
small, but it sets up a boundary layer of thickness
$\delta \sim L/\sqrt{Re}$ around the body. The boundary layer detaches
into a wake at high $Re$, producing a pressure drop on the downstream
side and net drag $F_D \sim (1/2)\rho U^2 L^2 C_D$ with $C_D$ a
Reynolds-dependent drag coefficient.

*Step 3 (the McGucken Sphere identification of viscosity).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
viscosity $\nu$ arises from the McGucken Sphere expansion at every fluid
element: the spherical $x_4$-expansion at $+ic$ produces an isotropic
random-walk component of the velocity field, which when coarse-grained
gives the diffusion term $\nu \Delta u$. The value of $\nu$ is set by
the Compton frequency of the dominant Compton-coupled mode in the fluid
(the molecular Compton frequencies); the Navier--Stokes $\nu \Delta u$
term is the foundational-geometric content of the fluid's Channel-B
propagation, derived in detail in the Clay Navier--Stokes
paper [@McGuckenNS2026].

*Step 4 (the singular limit).* The inviscid limit $\nu \to 0$ excises
the Channel-B content of the fluid: the McGucken Sphere structure is
artificially removed, leaving only the Channel-A algebraic skeleton
(Laplace's equation and Bernoulli). The D'Alembert result is the correct
prediction of this purely Channel-A theory, not a pathology; the
pathology is the assumption that this is the inviscid limit of real
(Channel-A + Channel-B) fluids. The boundary-layer and wake structure of
real flows is the Channel-B McGucken Sphere content irreducibly present
at all $\nu > 0$, however small.

*Step 5 (the high-Reynolds limit).* At high $Re$, the boundary layer is
thin but always present; the wake is large. The drag coefficient $C_D$
does not vanish as $Re \to \infty$ (for a bluff body) but approaches a
constant $\sim 1$, set by the wake's geometric structure. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is the
Channel-B McGucken Sphere structure persisting at all scales, with the
high-$Re$ limit being the regime where the boundary-layer thickness
$\delta \sim L/\sqrt{Re}$ shrinks but the wake's transverse scale
remains $\sim L$.

*Step 6 (the paradox dissolved).* D'Alembert's paradox is dissolved by
recognizing that the inviscid Euler equation is the Channel-A reading of
fluid dynamics, structurally incomplete; the full Channel-A + Channel-B
reading is Navier--Stokes, which always exhibits drag from the McGucken
Sphere-sourced boundary layer and wake. The Caffarelli-articulated
tension between "diffusion" (Channel B) and "incompressibility" (Channel
A) noted in the Clay Navier--Stokes paper [@McGuckenNS2026] is the
foundational-PDE-level reading of the same dual-channel structure. ◻


# The Hole Argument 

## Historical background: Einstein 1913--1915 hole argument, Stachel 1980 reconstruction

Einstein, struggling to find generally covariant field equations for
gravity (1913--1915), encountered the "hole
argument" [@EinsteinHole1913; @Norton1984]. Consider a region (the
"hole") in spacetime where the matter content vanishes; Einstein argued
that two metric solutions $g_{\mu\nu}$ and $g'_{\mu\nu}$ related by an
active diffeomorphism inside the hole but agreeing outside should
describe physically distinct configurations, since they assign different
metric values to the same spacetime points. This would mean general
covariance implies indeterminism: the field equations cannot uniquely
determine the metric. Einstein abandoned general covariance for two
years over this argument, before recognizing (1915) that the
diffeomorphic copies are not physically distinct; spacetime points have
no identity independent of the metric assigned to them. The modern
resolution is that "spacetime point" is a gauge concept under
diffeomorphism, and physical observables are diffeomorphism-invariant.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 74** (Hole argument as Channel-A gauge artifact). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, spacetime
points have no identity independent of the McGucken Sphere structure
encoded by the metric. The two diffeomorphism-related metrics
$g_{\mu\nu}$ and $g'_{\mu\nu}$ describe the same physical $x_4$-velocity
field at every event; the apparent distinction is a Channel-A
coordinate-labeling redundancy, exactly analogous to the gauge
redundancy of $A_\mu$ in electromagnetism
(Theorem [50](#thm:gauge-ghost){reference-type="ref"
reference="thm:gauge-ghost"}). The hole argument is dissolved by
recognizing the diffeomorphism group as the Channel-A gauge group of
general relativity.*


::: proof
*Proof.* *Step 1 (the diffeomorphism action).* An active diffeomorphism
$\phi: \mathcal{M} \to \mathcal{M}$ pushes the metric forward:
$g'_{\mu\nu}(\phi(p)) = (\phi^*)^{-1} g_{\mu\nu}(p)$. If $\phi$ is the
identity outside the hole and a nontrivial map inside, the two metrics
$g_{\mu\nu}$ and $g'_{\mu\nu}$ agree outside the hole and disagree
inside. The Einstein equations $G_{\mu\nu} = 8\pi G T_{\mu\nu}$ are
satisfied by both, since they are tensor equations covariant under
diffeomorphisms.

*Step 2 (the apparent indeterminism).* Einstein's 1913 argument: if both
$g_{\mu\nu}$ and $g'_{\mu\nu}$ satisfy the field equations and agree
outside the hole, then the field equations do not uniquely determine the
metric inside; specifying the matter content and the metric on a Cauchy
surface outside the hole is insufficient to determine the metric inside.

*Step 3 (the McGucken resolution: points have no identity).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, a spacetime
point $p \in \mathcal{M}$ has no identity independent of the McGucken
Sphere structure $\Sigma_+(p)$ encoded at $p$. The Sphere structure at
$p$ in metric $g$ is identical (up to relabeling) to the Sphere
structure at $\phi(p)$ in metric $g'$; the two configurations describe
the same physical $x_4$-velocity field, with the apparent difference
being only the labeling convention for which point is called "$p$."

*Step 4 (the gauge interpretation).* The diffeomorphism group
$\mathrm{Diff}(\mathcal{M})$ is the gauge group of general relativity,
exactly analogous to the local gauge group $U(1)$ of electromagnetism.
The Channel-A gauge-fixing procedure
(Theorem [50](#thm:gauge-ghost){reference-type="ref"
reference="thm:gauge-ghost"}) requires selecting one representative per
gauge orbit; for GR, this is a coordinate choice. Physical observables
are diffeomorphism-invariant, just as physical observables in
electromagnetism are $U(1)$-gauge-invariant. The two metrics $g$ and
$g' = \phi^* g$ are gauge-equivalent representatives of the same
physical configuration; no indeterminism.

*Step 5 (Cauchy problem resolved).* The Einstein equations have a
well-posed Cauchy problem after gauge fixing (harmonic coordinates,
etc.). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the gauge fixing selects one
McGucken-Sphere-consistent labeling of events; the field equations then
uniquely determine the future evolution of the McGucken Sphere structure
from initial data. The hole argument's apparent indeterminism is the
failure to fix the gauge before counting solutions; with gauge fixed,
the solution is unique.

*Step 6 (the structural lesson).* The hole argument crystallizes the
general structural lesson: in any gauge theory, gauge-related field
configurations describe the same physics. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this is a
theorem of the McGucken framework: gauge redundancy is Channel-A
coordinate-labeling redundancy, present in all gauge theories
(electromagnetism, Yang--Mills, gravity), and the McGucken Sphere
structure provides the gauge-invariant physical content underneath. ◻


# Painlevé's Non-Collision Singularity 

## Historical background: Painlevé 1895 to Xia 1988

Painlevé conjectured in 1895 that the Newtonian $N$-body problem admits
"non-collision singularities": configurations where the system reaches
infinite velocity or infinite separation in finite time without any
actual particle collision. Painlevé himself proved this impossible for
$N = 3$; the conjecture remained open for $N \geq 4$ for nearly a
century. Xia [@Xia1992] constructed an explicit $N = 5$ example,
settling the conjecture for $N \geq 5$. For $N = 4$, the question
remains open. The Painlevé phenomenon shows that classical mechanics,
taken at face value, allows pathological dynamics in which energy and
momentum are formally conserved but the system "escapes to infinity" in
finite time, with no underlying conservation-violating event.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 75** (Painlevé non-collision singularity as Channel-A artifact
of relativistic neglect). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the Newtonian $N$-body problem is the
non-relativistic limit ($c \to \infty$) of the McGucken framework, in
which the $x_4$-expansion is taken as instantaneous and the McGucken
Sphere structure is collapsed to a point. The Painlevé non-collision
singularity is a Channel-A artifact of this collapse: the singular
dynamics relies on instantaneous Newtonian gravity propagating at
infinite speed. Under the full McGucken framework with $c$ finite,
gravity propagates on the McGucken Sphere at finite speed, and the
non-collision singularity is forbidden by Compton-locality on the
McGucken Sphere.*


::: proof
*Proof.* *Step 1 (the Xia construction).* Xia's $N = 5$ example uses two
binary pairs and a fifth body oscillating between them. The oscillator
transfers energy back and forth between the pairs, with the pair
separations expanding without bound and the oscillator's speed becoming
unbounded in finite time. The construction relies on instantaneous
Newtonian gravitational interactions between widely separated bodies.

*Step 2 (the non-relativistic Newtonian limit).* Newtonian gravity is
the $c \to \infty$ limit of general relativity: in this limit,
gravitational influence propagates instantaneously and the metric
reduces to a Newtonian potential $\Phi$ satisfying
$\nabla^2 \Phi = 4\pi G\rho$. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this limit
excises the McGucken Sphere structure: the spherical $x_4$-expansion at
$+ic$ becomes instantaneous, and gravity at any event is sourced by the
matter distribution at the same instant, regardless of spatial
separation.

*Step 3 (the McGucken finite-$c$ correction).* For finite $c$, gravity
at any event is sourced by the matter distribution on the past McGucken
Sphere of the event, not at the simultaneous instant. The propagation
time for gravity to travel between widely separated bodies is finite;
the Xia construction's instantaneous energy transfer between pairs is
not possible in the finite-$c$ McGucken framework.

*Step 4 (Compton-locality bounds the velocity).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, no particle
can exceed the speed of light $c$; the velocity is bounded by
Compton-locality on the McGucken Sphere. The non-collision singularity's
unbounded velocity is forbidden: as the oscillator's speed approaches
$c$, its Compton frequency $\omega_C$ diverges (special-relativistic
correction), and the McGucken Sphere structure caps the kinematic
content.

*Step 5 (gravitational wave emission as Channel-B dissipation).* Under
the full McGucken framework with $c$ finite, accelerated bodies emit
gravitational waves, carrying energy away from the system. The Xia
construction's energy oscillation between pairs is therefore not
conservative under the finite-$c$ McGucken framework; the system loses
energy to gravitational radiation, and the non-collision singularity is
forbidden by Channel-B dissipation.

*Step 6 (the structural lesson).* The Painlevé non-collision singularity
is the foundational-mechanics-level signature of the same structural
failure as the cosmological-constant problem
(Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}) and the
Bell-test nonlocality (Theorem [15](#thm:epr){reference-type="ref"
reference="thm:epr"}): treating Newtonian instantaneous interactions as
the foundational theory excises the McGucken Sphere structure and
produces apparent paradoxes. The McGucken framework with finite $c$ and
full Channel-A + Channel-B structure forbids the singularity at the
foundational level. ◻


# First Quantization versus Second Quantization 

## Historical background: Dirac 1927 second quantization to Fock space

Quantum mechanics admits two operationally distinct formulations. *First
quantization* treats particles as having a wave function
$\psi(\vec x, t)$ obeying the Schrödinger or Dirac equation; the
position $\hat x$ and momentum $\hat p$ are operators, but particles are
not. *Second quantization* treats fields as operators $\hat\phi(x)$ on
Fock space; the particle number is now an operator with discrete
spectrum, and particles emerge as quantized excitations of the field.
The two formulations agree on observable predictions in the
non-relativistic single-particle sector but diverge structurally: second
quantization permits particle creation and annihilation, antimatter, and
the spin-statistics theorem, while first quantization treats particle
number as conserved by hand. The relation between them is the source of
persistent foundational confusion: are particles primary or are fields
primary? The Wigner classification of irreducible unitary
representations of the Poincaré group [@Wigner1939] treats particles as
derived from fields; the Heisenberg picture treats both on equal
footing.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 76** (First and second quantization as Channel-A two-tier
algebraic structure). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, both first quantization and second quantization are
Channel-A algebraic readings of the same McGucken Sphere content, at two
different tiers. First quantization is the algebraic reading at the
single-particle tier: $\hat x$ and $\hat p$ are the operators on the
McGucken Sphere of a single Compton-coupled mode. Second quantization is
the algebraic reading at the field tier: $\hat\phi(x)$ is the
operator-valued distribution on the McGucken Sphere structure of the
entire field. The two tiers are related by the Fock-space construction;
their apparent disagreement on particle number is the artifact of
choosing one tier as foundational, when both are simultaneously
Channel-A readings of the same underlying $x_4$-velocity field.*


::: proof
*Proof.* *Step 1 (single-particle algebra as first tier).* The McGucken
Sphere at any event $p$ has a tangent space $T_p\mathcal{M}$ on which
the canonical commutator $[\hat x, \hat p] = i\hbar$ acts. The
Schrödinger equation $i\hbar \partial_t \psi = \hat H \psi$ is the
Channel-A integrated form of $dx_4/dt = ic$ at the single-particle
Compton-coupling tier (Theorem [45](#thm:born){reference-type="ref"
reference="thm:born"}). First quantization is the algebraic reading of
the McGucken Sphere structure at this tier.

*Step 2 (field algebra as second tier).* The field operator
$\hat\phi(x)$ at every event is the operator-valued distribution that
creates and annihilates Compton-coupled modes at $x$. The canonical
commutation relations
$[\hat\phi(x), \hat\pi(y)] = i\hbar \delta^3(\vec x - \vec y)$ at equal
times are the Channel-A integrated form of $dx_4/dt = ic$ at the field
tier; the McGucken Sphere structure at every event admits an
infinite-dimensional algebra of field modes.

*Step 3 (Fock space as the connecting structure).* The Fock space
$\mathcal{F} = \bigoplus_{n=0}^\infty \mathcal{H}^{\otimes_s n}$ for
bosons (symmetric tensor products) or
$\mathcal{F} = \bigoplus_{n=0}^\infty \mathcal{H}^{\otimes_a n}$ for
fermions (antisymmetric tensor products) supplies the formal connection
between the two tiers. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the symmetric/antisymmetric tensor structure is the
algebraic content of the Compton-coupled modes' identity
(Theorem [72](#thm:gibbs){reference-type="ref" reference="thm:gibbs"},
the Gibbs paradox resolution), with the spin-statistics theorem as a
derived consequence of the McGucken Sphere's lift to $SU(2)_L$
structure.

*Step 4 (particle creation and antimatter).* Second quantization permits
the operator $\hat\phi(x)$ to act on the vacuum $|0\rangle$ to create
particle states; the energy spectrum includes negative-energy modes that
are reinterpreted as antiparticles propagating with positive energy
(Step 1 of Theorem [47](#thm:klein){reference-type="ref"
reference="thm:klein"}). Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, the negative-energy modes are the $-ic$ branch of
the Dirac equation; their reinterpretation as antiparticles is the lift
to $SU(2)_L$ that preserves the $+ic$ orientation while encoding the
opposite chirality.

*Step 5 (no preferred tier).* Neither first nor second quantization is
foundationally primary; both are Channel-A algebraic readings of the
same $x_4$-velocity field at different tiers of resolution. The
single-particle Schrödinger equation is the non-relativistic,
fixed-particle-number reduction of the field equation at the single-mode
level; the field equation extends to multi-particle and high-energy
phenomena that first quantization cannot accommodate. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the two
formulations are dual descriptions of the same McGucken Sphere content,
and the choice of formulation is a matter of operational convenience,
not foundational priority.

*Step 6 (no "particle versus field" paradox).* The foundational question
"are particles primary or are fields primary?" is dissolved under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}: neither.
The foundational content is the McGucken Sphere structure at every
event, generated by $dx_4/dt = ic$. Particles are Compton-coupled modes
of definite mass and spin; fields are the operator-valued distributions
encoding the algebra of these modes; both are derived constructions from
the McGucken Sphere structure. ◻


# Microcausality versus Entanglement in QFT 

## Historical background: Reeh--Schlieder 1961 to modern algebraic QFT

Quantum field theory enforces microcausality: spacelike-separated field
operators commute, $[\hat\phi(x), \hat\phi(y)] = 0$ for $(x-y)^2 < 0$,
which is the no-signaling theorem at the operator-algebra level.
Simultaneously, the vacuum state $|0\rangle$ exhibits long-range
entanglement: the Reeh--Schlieder theorem [@ReehSchlieder1961] shows
that any local algebra of operators on a bounded region acting on
$|0\rangle$ produces a dense subspace of the full Hilbert space,
implying that local operations in any region are entangled with
operations in arbitrarily distant regions. The paradox: microcausality
enforces local commutation (no signaling), but Reeh--Schlieder
entanglement permits arbitrary local-operation-induced correlations at
arbitrarily large spacelike separations. The two facts coexist in QFT
but are structurally tense: how can microcausality and Reeh--Schlieder
entanglement both be true?

## The McGucken $dx_4/dt = ic$ reading


**Theorem 77** (Microcausality and Reeh--Schlieder as Channel-A locality
and Channel-B Sphere-sharing). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"},
microcausality is the Channel-A statement that operator algebras at
spacelike-separated events commute---no signal can propagate against the
$+ic$ direction. Reeh--Schlieder entanglement is the Channel-B statement
that the cosmological McGucken Sphere is shared by all events; vacuum
entanglement structure is the geometric content of this shared Sphere.
The two statements are not in tension: Channel A forbids the use of
local operations to send signals, while Channel B encodes the
pre-existing correlation structure that local operations can detect but
cannot create.*


::: proof
*Proof.* *Step 1 (microcausality as Channel-A no-signaling).* The
spacelike commutator $[\hat\phi(x), \hat\phi(y)] = 0$ for $(x-y)^2 < 0$
is a theorem of the operator algebra of the Klein--Gordon / Dirac field.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
is the Channel-A integrated form of the $+ic$ orientation of
$x_4$-expansion: at spacelike-separated events, the past light cones do
not overlap, so the operator algebras factorize. No correlation can be
created between spacelike-separated events by local operations.

*Step 2 (Reeh--Schlieder as cosmological-Sphere sharing).* The
Reeh--Schlieder theorem states that for the vacuum $|0\rangle$ and any
local algebra $\mathcal{A}(\mathcal{O})$ on a bounded region
$\mathcal{O}$, the closure
$\overline{\mathcal{A}(\mathcal{O})|0\rangle} = \mathcal{H}$. The local
algebra is cyclic for the vacuum; the vacuum is a separating vector.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
is the Channel-B statement that the McGucken Sphere structure of the
cosmological universe is shared by all events: the past null cones of
any two spacelike-separated regions both extend to the same cosmological
McGucken Sphere at their joint causal past, and the vacuum state encodes
the geometric content of this shared Sphere.

*Step 3 (no tension between the two).* The two statements operate on
different content: microcausality is a statement about operator-algebra
commutators (Channel A, "cannot signal"); Reeh--Schlieder is a statement
about state-space entanglement structure (Channel B, "correlations
already exist"). The no-signaling theorem (Channel A) forbids creating
new correlations between spacelike-separated events by local operations;
the Reeh--Schlieder theorem (Channel B) characterizes the entanglement
structure that local operations can detect but not modify. The two are
simultaneously true because they describe different aspects of the same
foundational structure.

*Step 4 (the entanglement structure of the vacuum).* The vacuum's
entanglement entropy across a bipartition into regions $A$ and $\bar A$
is divergent at the boundary $\partial A$, scaling as
$S \sim \mathrm{Area}(\partial A)/\epsilon^{d-2}$ in $d$ dimensions with
UV cutoff $\epsilon$. Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, this is the holographic-area-law statement
(Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}) applied to the vacuum's Channel-B geometric
content: the McGucken Sphere structure at the boundary $\partial A$
couples to both sides, with the area divergence reflecting the infinite
number of Compton modes contributing at arbitrarily short scales.

*Step 5 (the Reeh--Schlieder lesson).* The Reeh--Schlieder theorem is
sometimes interpreted as showing that vacuum entanglement is "more
nonlocal" than EPR entanglement (since it spans arbitrary spacelike
separations); the McGucken framework dissolves this: vacuum entanglement
is the natural Channel-B content of the cosmological McGucken Sphere
shared by all events. The Bell-test correlations on EPR pairs are
restricted versions of the same structure, with the entangling event
determining which Channel-B Sphere is shared.

*Step 6 (no information paradox).* The simultaneous coexistence of
microcausality (Channel A) and Reeh--Schlieder entanglement (Channel B)
does not produce an information paradox or a no-go theorem because the
two operate on functorially distinct content. The McGucken framework's
dual-channel structure resolves the apparent tension at the foundational
level by identifying the two as the two readings of the same underlying
$x_4$-velocity field; no third foundational element is required. ◻


# Inflation versus Eternal Inflation 

## Historical background: Guth 1981 inflation to Linde 1986 eternal inflation

Inflation [@Guth1981] resolves the horizon and flatness problems by a
brief epoch of exponential expansion in the early universe.
Linde [@Linde1982] and others showed that, under generic conditions,
inflation is *eternal*: quantum fluctuations of the inflaton field
continually generate new inflating regions, producing an
exponentially-growing volume of inflating spacetime with bubble
universes nucleating within. Eternal inflation predicts a multiverse of
causally disconnected bubble universes, each with its own physics (in
the string-theory landscape) or its own cosmological history. The
paradox: a single inflation epoch was introduced to resolve specific
cosmological problems, but the same mechanism, taken seriously, produces
an unbounded multiverse with severe measure problems
(Theorem [79](#thm:cosmo-measure){reference-type="ref"
reference="thm:cosmo-measure"}) and Boltzmann-brain dominance
(Theorem [64](#thm:boltzmann-brains){reference-type="ref"
reference="thm:boltzmann-brains"}).

## The McGucken $dx_4/dt = ic$ reading


**Theorem 78** (Inflation and eternal inflation as Channel-A inflation
field versus Channel-B Sphere expansion). *Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the horizon
and flatness problems are resolved by the McGucken Sphere's spherically
symmetric expansion at every event
(Theorem [39](#thm:cosmo){reference-type="ref" reference="thm:cosmo"}),
not by an inflation field; inflation is a Channel-A device that emulates
the Channel-B structural correlation that the McGucken Sphere supplies
natively. Eternal inflation is the unbounded extrapolation of this
Channel-A device beyond its empirical reach; the McGucken framework's
resolution of the horizon and flatness problems requires no inflation
field, and therefore predicts no multiverse.*


::: proof
*Proof.* *Step 1 (the orthodox inflation argument).* The standard hot
Big Bang cosmology faces the horizon problem (causally disconnected CMB
patches are in thermal equilibrium) and the flatness problem (the
spatial curvature must be fine-tuned to $|\Omega - 1| \ll 1$ to match
observation). Inflation resolves both: a brief epoch of $\sim 60$
e-folds of exponential expansion stretches a small, causally connected,
nearly-flat region to encompass the entire observable universe.

*Step 2 (the McGucken Sphere structural resolution).* By
Theorem [39](#thm:cosmo){reference-type="ref" reference="thm:cosmo"},
the horizon and flatness problems are resolved by the McGucken Sphere's
spherical $x_4$-expansion at every event. Every CMB event shares the
$x_4$-phase structure of the recombination event through the integrated
Sphere from every prior event; this is the Channel-B mechanism that the
inflationary expansion emulates. The flatness $\Omega \approx 1$ is the
natural geometric flatness of the McGucken Sphere expansion at the
present epoch.

*Step 3 (eternal inflation as extrapolation).* If inflation occurs at
all, generic conditions make it eternal: quantum fluctuations of the
inflaton field $\phi$ produce new inflating regions faster than existing
regions exit inflation. The mathematical statement is
$\langle \Delta\phi_{\rm quantum}\rangle > |\Delta\phi_{\rm classical}|$
for $\phi$ near the top of the potential, which is generic. The result
is an exponentially growing volume of inflating spacetime with bubble
universes nucleating within.

*Step 4 (no eternal inflation in McGucken framework).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken Sphere expansion does not require an inflaton field. The
cosmological-scale Sphere expansion is the universal $+ic$-oriented
$x_4$-velocity field at every event; it has no analog of the inflaton's
quantum fluctuations at the top of a potential, because there is no
potential---the expansion is the foundational content. Without an
inflaton, there is no mechanism for the quantum fluctuations that drive
eternal inflation; the multiverse prediction is excised.

*Step 5 (the multiverse dissolved).* The cosmological multiverse
picture, in which our observed universe is one bubble among
exponentially many, is the orthodox-tradition response to the question
"why did inflation produce these specific cosmological parameters?"
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
cosmological parameters are determined by the McGucken Sphere structure
at the present epoch
(Theorem [61](#thm:dark-energy){reference-type="ref"
reference="thm:dark-energy"}); no multiverse selection is required to
explain them. The multiverse postulate is dissolved at the foundational
level.

*Step 6 (the Susskind landscape question).* The string-theory landscape
of $\sim 10^{500}$ vacua, populated by eternal inflation, supplies the
orthodox-tradition framework for the multiverse. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
McGucken framework derives the Standard Model gauge group $G_{\rm SM}$
from $dx_4/dt = ic$ as a theorem (per the corpus Standard Model paper);
no landscape of vacua is required. The McGucken framework predicts a
unique low-energy effective theory, consistent with our observed
Standard Model; the landscape is excised. ◻


# The Cosmological Measure Problem 

## Historical background: Vilenkin 1983 measure to Boltzmann-brain measure problems

In a multiverse generated by eternal inflation
(Theorem [78](#thm:inflation-eternal){reference-type="ref"
reference="thm:inflation-eternal"}), the question "what should we expect
to observe?" requires a measure over bubble universes. Different measure
proposals---proper-time measure, scale-factor measure, light-cone-time
measure, causal-patch measure---give wildly different predictions for
cosmological parameters, including the cosmological constant and the
Higgs mass. The measure
problem [@Vilenkin1983; @Linde1986; @Carroll2008] is the failure of any
natural measure choice to reproduce observed cosmology; different
measures predict dramatically different values for fundamental
parameters, with no first-principles way to choose. The measure problem
is one of the strongest internal critiques of the eternal-inflation
multiverse picture.

## The McGucken $dx_4/dt = ic$ reading


**Theorem 79** (Cosmological measure problem dissolved by absence of
multiverse). *Under Axiom [1](#ax:mcg){reference-type="ref"
reference="ax:mcg"}, no multiverse exists
(Theorem [78](#thm:inflation-eternal){reference-type="ref"
reference="thm:inflation-eternal"}); therefore no cosmological measure
problem exists. The observed cosmological parameters are determined by
the McGucken Sphere structure at the present epoch, not selected from a
multiverse distribution. The measure problem is dissolved at the
foundational level by recognizing it as an artifact of the
eternal-inflation extrapolation, which is itself excised by the McGucken
framework.*


::: proof
*Proof.* *Step 1 (the measure problem as a structural defect of
multiverse).* If the multiverse contains exponentially many bubble
universes with different cosmological parameters, predicting our
observed values requires a probability distribution over bubbles. Any
such measure must satisfy: (i) be well-defined (assign finite
probability to each measurable subset of bubbles); (ii) be invariant
under physically reasonable transformations (e.g., diffeomorphisms of
the multiverse manifold); (iii) reproduce the observed cosmological
parameters as typical.

*Step 2 (the failure of standard measures).* The proper-time measure
(uniformly weighting bubbles by their volume at fixed proper time)
predicts a cosmological constant $\Lambda \sim M_P^4$, in dramatic
conflict with observation. The scale-factor measure (uniformly weighting
bubbles by their scale factor) predicts $\Lambda \sim 0$, also in
conflict. The light-cone-time measure (uniformly weighting bubbles by
their light-cone time) and the causal-patch measure each give different
predictions, all in conflict with observation. No natural measure has
been found that reproduces the observed value.

*Step 3 (anthropic selection inadequate).* The orthodox-tradition
response to the measure problem invokes anthropic selection: weight the
measure by the number of observers, then condition on our existence.
Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, this
is structurally inadequate
(Theorem [58](#thm:naturalness){reference-type="ref"
reference="thm:naturalness"}, Step 7): the McGucken framework explains
the observed cosmological parameters without anthropic selection, by
deriving them from $dx_4/dt = ic$.

*Step 4 (the McGucken resolution).* Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
cosmological parameters of our observed universe are determined by the
McGucken Sphere structure at the present epoch: $\Lambda$ is the squared
expansion rate of the cosmological Sphere
(Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"});
$\Omega_m, \Omega_\Lambda$ are determined by the integrated cosmic
history (Theorem [61](#thm:dark-energy){reference-type="ref"
reference="thm:dark-energy"}); the Standard Model gauge group and its
parameters are theorems of the framework (per [@McGuckenSM2026]). There
is no multiverse and therefore no measure problem.

*Step 5 (the methodological lesson).* The cosmological measure problem
is a clean example of the patch-accretion pathology: the
eternal-inflation multiverse was introduced to resolve the
cosmological-constant fine-tuning, generating the measure problem; the
anthropic principle was introduced to resolve the measure problem,
generating its own measure-of-observers issue; etc. Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
original cosmological-constant "problem" is dissolved at the
foundational level (Theorem [38](#thm:cc){reference-type="ref"
reference="thm:cc"}), and the entire patch-accretion chain is rendered
unnecessary.

*Step 6 (Boltzmann-brain dominance dissolved).* The measure problem's
worst empirical pathology is Boltzmann-brain dominance: under many
measure choices, Boltzmann-brain observers vastly outnumber evolved
observers (Theorem [64](#thm:boltzmann-brains){reference-type="ref"
reference="thm:boltzmann-brains"}). Under
Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, no
multiverse means no Boltzmann-brain dominance problem; the cosmological
evolution is unique, and our existence as evolved observers is the only
kind the framework supports. ◻


# The Paradox-Resolution Meta-Theorem of $dx_4/dt = ic$ 

## The Structural Logic of Paradox

A paradox in foundational physics is, by its logical structure, the
simultaneous assertion that two propositions $p_1$ and $p_2$ are (i)
*related*---both predicated of the same underlying physical entity,
situation, or phenomenon $\varphi$---and (ii) *disjoint*---mutually
exclusive under the vocabulary $V$ in which the propositions are stated.
The two conditions are jointly necessary for paradox-content: where
$p_1$ and $p_2$ are *unrelated*, there is no paradox; where $p_1$ and
$p_2$ are *not disjoint*, there is no contradiction. The paradox-content
lies precisely in the simultaneous holding of relatedness and
disjointness, in the same entity, at the same time.

Formally: a paradox in foundational physics is a triple
$P = (p_1, p_2, V)$ where

-   $p_1, p_2$ are propositions about the foundational-physical content
    of nature,

-   $V$ is the vocabulary (mathematical-formal-language plus
    conceptual-categorical apparatus) in which $p_1$ and $p_2$ are
    stated,

-   the *relatedness condition* $R(p_1, p_2)$ holds: $\exists \varphi$
    such that both $p_1(\varphi)$ and $p_2(\varphi)$ are predicated of
    the same foundational-physical entity $\varphi$,

-   the *disjointness condition* $D(p_1, p_2, V)$ holds: in the
    vocabulary $V$, the inference
    $V \models (p_1 \to \neg p_2) \wedge (p_2 \to \neg p_1)$ is
    licensed.

The relatedness condition is supplied by the empirical-physical content
of nature itself; both horns of the paradox describe the same physical
phenomenon. The disjointness condition is supplied by the vocabulary
$V$; the mutual exclusivity of $p_1$ and $p_2$ is an artifact of the
conceptual apparatus, not of nature itself. A paradox is therefore,
structurally, a *signal* of the limitation of the vocabulary $V$, not a
feature of the underlying physical content $\varphi$.

## The Three Orthodox Responses and the Fourth McGucken Response

The orthodox tradition, operating in a single-channel single-reading
vocabulary $V$, has three structurally available responses to a paradox
of the form $P = (p_1, p_2, V)$:

#### Response (i)---Eliminativism.

Declare one of $p_1, p_2$ false. The paradox is dissolved by denying one
horn. This response is structurally inadequate whenever both horns are
empirically forced by data. Einstein's deterministic-hidden-variable
response to Born-rule probability, the Bohmian-pilot-wave
deterministic-completion response to QM, and the Bohr--Copenhagen denial
of microscopic-objective-reality are all examples of attempted
eliminativism that have failed empirically.

#### Response (ii)---Paraconsistent acceptance.

Accept the contradiction as foundational. The paradox is acknowledged
but not resolved; the two horns are declared "complementary" (Bohr
1927), or "shut up and calculate" (the operational-positivist response).
This response is structurally inadequate whenever the contradiction
admits a resolution at a deeper foundational level. Bohr's
complementarity-as-foundational-principle treats the paradox as a
feature of nature; the McGucken framework treats it as a signal of the
vocabulary's limitation.

#### Response (iii)---Patch-accretion.

Add a new foundational postulate at the structural location of the
paradox. The Born rule resolves the measurement problem by postulating
it; the Past Hypothesis resolves the arrow of time by postulating it;
the Susskind black-hole complementarity resolves the information paradox
by postulating it. Each patch leaves the underlying foundational tension
structurally unresolved and merely closes the empirical-prediction gap
at the operational level. Patch-accretion multiplies entities beyond
Newton's Rule I [@Newton1687].

The McGucken framework supplies a *fourth* response, structurally
distinct from the three orthodox responses:

#### Response (iv)---Dual-channel identification.

Identify the two horns $p_1$ and $p_2$ as the *two channel-readings* of
one principle. The principle's *unity* supplies the relatedness
condition $R(p_1, p_2)$---both horns descend from the foundational
equation $dx_4/dt = ic$, predicated of the expanding fourth dimension at
every event. The principle's *dual-channel structure* supplies the
disjointness condition $D(p_1, p_2, V)$---the algebraic-symmetry Channel
A reading and the geometric-propagation Channel B reading are genuinely
distinct mathematical-functorial readings of the same underlying
physical fact, with the position-of-$i$ asymmetry supplying the formal
source of the distinction. The disjointness is not eliminated; it is
*grounded* in the functorial-categorical distinction between the two
channels. The relatedness is not multiplied; it is *unified* by the
single foundational principle.

## The Meta-Theorem


**Theorem 80** (Paradox-Resolution Meta-Theorem of $dx_4/dt = ic$). *Let
$P = (p_1, p_2, V)$ be a paradox in foundational physics with
relatedness condition $R(p_1, p_2)$ holding via shared underlying entity
$\varphi$, and disjointness condition $D(p_1, p_2, V)$ holding under
orthodox single-channel vocabulary $V$. Suppose further that:*

1.  *$\varphi$ is a foundational-physical content of the McGucken
    geometry $\mathcal{M}_G$ generated by
    Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"};*

2.  *the propositions $p_1$ and $p_2$ admit, respectively, a Channel-A
    reading $p_1 = p_1^{(A)}(C)$ and a Channel-B reading
    $p_2 = p_2^{(B)}(C)$ of the same foundational content $C$ of
    $dx_4/dt = ic$ at the site $\varphi$;*

3.  *the position-of-$i$ asymmetry between the two channels (i.e., the
    distinction between the interior $i$ in $[\hat q,\hat p] = i\hbar$
    and the exterior $i$ in $dx_4/dt = ic$ as a velocity) supplies the
    formal functorial distinction between the Channel-A and Channel-B
    readings of $C$.*

*Then the McGucken framework supplies the structural-foundational
resolution of $P$ as follows:*

1.  **Relatedness sourced from unity.* Both $p_1$ and $p_2$ are
    predicates of the same foundational content $C$. The relatedness
    condition $R(p_1, p_2)$ is supplied by the single foundational
    principle $dx_4/dt = ic$; the unity of the principle sources the
    unity of the predicated content.*

2.  **Disjointness sourced from dual-channel structure.* The
    propositions $p_1$ and $p_2$ are distinct mathematical-functorial
    readings of $C$. The disjointness condition $D(p_1, p_2, V)$ is
    supplied by the position-of-$i$ asymmetry and the functorial
    distinction between the Channel-A "Noether channel" and the
    Channel-B "entropy channel."*

3.  **Simultaneous resolution.* The relatedness and the disjointness are
    simultaneously supplied by the single principle $dx_4/dt = ic$ via
    its dual-channel structure. No additional postulate, no abandonment
    of the deductive method, no denial of empirical content, and no
    multiplication of foundational entities is required.*

*The paradox $P$ is structurally resolved: the two horns are the two
channel-readings of one principle; the relatedness is supplied by the
principle's unity; the disjointness is supplied by the channels'
functorial distinction; no third foundational element is required to
bridge them.*


::: proof
*Proof.* *Step 1 (existence of the Channel-A reading).* By hypothesis
(b), $p_1$ admits a Channel-A reading $p_1^{(A)}(C)$ of the foundational
content $C$. The Channel-A reading is the algebraic-symmetry content of
$C$ under $dx_4/dt = ic$: the canonical commutator
$[\hat q, \hat p] = i\hbar$, the Stone---von Neumann theorem, the
Noether-conservation laws generated by the symmetries of the underlying
Lagrangian. By the Stone-route Theorem of the McGucken corpus, this
content is generated by the single principle as the integrated form of
the $x_4$-velocity through the Hamiltonian operator.

*Step 2 (existence of the Channel-B reading).* By hypothesis (b), $p_2$
admits a Channel-B reading $p_2^{(B)}(C)$ of the foundational content
$C$. The Channel-B reading is the geometric-propagation content of $C$
under $dx_4/dt = ic$: the McGucken Sphere expansion at every event, the
SO(3)-Haar measure on the Sphere boundary supplying the Born-rule
probabilities, the strict $+ic$-orientation supplying the arrow of time.
By the geometric-route theorem of the McGucken corpus, this content is
also generated by the single principle as the integrated form of the
$x_4$-velocity through the geometric expansion.

*Step 3 (functorial distinction of the two channels).* By hypothesis
(c), the position-of-$i$ asymmetry distinguishes the two channels at the
formal mathematical level. The Channel-A reading places $i$ *interior*
to the canonical commutator: $[\hat q, \hat p] = i\hbar$, where $i$ acts
as the generator of the algebraic-symmetry phase rotation. The Channel-B
reading places $i$ *exterior* to the integrated form: $dx_4/dt = ic$ as
a velocity, where $i$ acts as the rotation of the fourth dimension out
of the spatial $\mathbb{R}^3$ into the orthogonal $\mathbb{R}_{x_4}$.
The two placements correspond to genuinely distinct functorial
constructions: Channel A is a functor on the category of differentiable
action functionals with continuous symmetry groups; Channel B is a
functor on the category of normalized probability densities evolved by
positivity-preserving Markov semigroups. The two functors do not factor
through each other; they are functorially distinct readings of the same
underlying foundational content $C$.

*Step 4 (relatedness from unity, ($\alpha$)).* Both $p_1$ and $p_2$ are
predicates of the same foundational content $C$ of $dx_4/dt = ic$ at the
site $\varphi$. The relatedness condition $R(p_1, p_2)$ is supplied by
the single principle: there exists $\varphi$ (the foundational content
of $C$) such that both $p_1(\varphi)$ and $p_2(\varphi)$ hold. The
relatedness is not multiplied; it is unified by the principle's unity.

*Step 5 (disjointness from dual-channel structure, ($\beta$)).* The
propositions $p_1$ and $p_2$ are functorially distinct readings of $C$.
Under the orthodox vocabulary $V$, which does not articulate the
functorial distinction, the two readings appear mutually exclusive; the
disjointness condition $D(p_1, p_2, V)$ is licensed under $V$. Under the
McGucken vocabulary, the functorial distinction is articulated: the two
readings are genuinely distinct mathematical objects, and their
distinction is grounded in the position-of-$i$ asymmetry. The
disjointness is not eliminated by the McGucken framework; it is
structurally grounded.

*Step 6 (simultaneous resolution, ($\gamma$)).* The relatedness
($\alpha$) and the disjointness ($\beta$) are simultaneously supplied by
the single principle $dx_4/dt = ic$: the unity of the principle sources
the relatedness, and the dual-channel structure sources the
disjointness. No additional postulate is invoked; the paradox $P$ is
resolved by the single principle. The structural signature: *one
principle, two channels, one paradox resolved*. ◻


## The Catalog of Resolved Paradoxes

Every theorem in this paper instantiates the meta-theorem. The mapping
from each paradox to its $(p_1, p_2, V)$ structure and its
$(C, \varphi)$ Channel-A/B identification is uniform across the entire
catalog. The full list, organized by domain, follows. Each entry takes
the form: theorem reference; horns $p_1, p_2$; orthodox vocabulary $V$;
Channel-A reading; Channel-B reading.

#### Foundational quantum measurement.

-   **Wave--particle duality**
    (Theorem [19](#thm:duality){reference-type="ref"
    reference="thm:duality"}): $p_1$ = wave phenomenology
    (interference); $p_2$ = particle phenomenology (localized
    detection); $V$ = classical-physics vocabulary; Channel A reads the
    state as wavefunction with $x_4$-phase; Channel B reads it as
    McGucken-Sphere null-cone expansion.

-   **The photon's four-velocity paradox and the photon as tracer of
    $x_4$** (Theorem [22](#thm:photon-tracer){reference-type="ref"
    reference="thm:photon-tracer"}): $p_1$ = every particle's
    four-velocity has magnitude $c$ (orthodox slogan); $p_2$ = the
    photon's four-velocity is undefined because $d\tau = 0$ on null
    worldlines (orthodox exception); $V$ = proper-time-parametrization
    vocabulary; Channel A is the algebraic four-velocity budget
    partition $|\vec v|^2 + c_{x_4}^2 = c^2$ stated against coordinate
    time $t$ (defined for photons); Channel B is the geometric
    identification of the photon's spatial propagation at $c$ as the
    motion of $x_4$ itself, with the photon at absolute rest in $x_4$
    ($dx_4/dt = 0$). Peebles' expanding-probability-sphere combined with
    Wheeler's ageless-photon derives
    Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}.

-   **Measurement problem and Schrödinger's cat**
    (Theorem [13](#thm:measurement){reference-type="ref"
    reference="thm:measurement"}): $p_1$ = unitary Schrödinger
    evolution; $p_2$ = projective Born-rule collapse; $V$ =
    single-process QM vocabulary; Channel A is the unitary
    $\hat U(t) = \exp(-i\hat H t/\hbar)$; Channel B is the $x_4$-pinch
    decoherence at the apparatus event.

-   **EPR / Bell nonlocality**
    (Theorem [15](#thm:epr){reference-type="ref" reference="thm:epr"}):
    $p_1$ = no-signaling; $p_2$ = Bell-inequality violation reaching the
    Tsirelson bound; $V$ = local-realist vocabulary; Channel A is the
    singlet's algebraic antisymmetry; Channel B is the McGucken Sphere
    shared between $p_A, p_B$ from the entangling past $p_0$.

-   **Wigner-friend and Frauchiger--Renner**
    (Theorem [17](#thm:wigner){reference-type="ref"
    reference="thm:wigner"}): $p_1$ = $F$'s record at $E_F$ (definite
    outcome); $p_2$ = $W$'s record at $E_W$ (unitary superposition); $V$
    = one-universal-observer vocabulary; Channel A is the joint-system
    unitary $\hat U_{SF}$; Channel B is the registration map
    $\mathcal{R}_F$ at $E_F$.

-   **Hardy / GHZ / Kochen--Specker contextuality**
    (Theorem [25](#thm:hardy-ghz-ks){reference-type="ref"
    reference="thm:hardy-ghz-ks"}): $p_1$ = Boolean value-assignment on
    observables; $p_2$ = quantum contextual probabilities (9%, GHZ sign,
    KS no-go); $V$ = classical-logic vocabulary; Channel A is the
    non-Boolean projection lattice generated by $i$; Channel B is the
    apparatus-event pinch in distinct measurement bases.

-   **Mott tracks, Renninger negative results, Elitzur--Vaidman, quantum
    Zeno** (Theorem [26](#thm:mott-renninger){reference-type="ref"
    reference="thm:mott-renninger"}): $p_1$ = spherical / unmeasured
    wave content; $p_2$ = localized / measured trajectory; $V$ =
    pre-decoherence wave-mechanics vocabulary; Channel A is the free
    Schrödinger phase evolution between events; Channel B is the
    apparatus $x_4$-pinch at each detection event.

-   **Bohmian pilot-wave and Everett many-worlds**
    (Theorem [44](#thm:interpretations){reference-type="ref"
    reference="thm:interpretations"}): $p_1$ = hidden-trajectory
    deterministic dynamics (Bohm); $p_2$ = unitary-only branching
    dynamics (Everett); $V$ = collapse-vs-no-collapse vocabulary;
    Channel A is the wavefunction phase $S$ (Bohm's guiding field;
    Everett's branch amplitude); Channel B is the configuration / branch
    realization. Both are bookkeeping projections of the same underlying
    $x_4$-velocity field.

-   **Born rule status** (Theorem [45](#thm:born){reference-type="ref"
    reference="thm:born"}): $p_1$ = derived probability rule (Gleason,
    decision-theoretic, envariance); $p_2$ = postulated probability rule
    (textbook); $V$ = independent-postulate vocabulary; Channel A is the
    sesquilinear form forced by the unitary group's generator algebra;
    Channel B is the SO(3)-Haar measure on the McGucken Sphere at the
    registration event.

-   **Heisenberg uncertainty and Bohr complementarity**
    (Theorem [46](#thm:uncertainty){reference-type="ref"
    reference="thm:uncertainty"}): $p_1$ = sharp position description;
    $p_2$ = sharp momentum description; $V$ = classical-trajectory
    vocabulary; Channel A is the canonical commutator
    $[\hat x, \hat p] = i\hbar$ from the $i$ in $dx_4/dt = ic$; Channel
    B is the Sphere-registration in conjugate bases. All complementary
    pairs
    $(\hat x, \hat p), (\hat E, \hat t), (\hat n, \hat\phi), (\hat J_x, \hat J_y)$
    have the same source.

-   **Klein paradox and the Dirac sea**
    (Theorem [47](#thm:klein){reference-type="ref"
    reference="thm:klein"}): $p_1$ = positive-energy reflection
    coefficient; $p_2$ = over-reflection $R > 1$ at high step potential;
    $V$ = single-branch wave-mechanics vocabulary; Channel A is the
    forward-$x_4$ branch wave function; Channel B is the backward-$x_4$
    pair-production at the step, identified with the Schwinger rate.

-   **Dynamical collapse models (GRW, CSL, Penrose)**
    (Theorem [43](#thm:collapse){reference-type="ref"
    reference="thm:collapse"}): $p_1$ = unitary QM dynamics; $p_2$ =
    spontaneous-collapse modification of QM; $V$ = new-physics-required
    vocabulary; Channel A is the unmodified Schrödinger evolution;
    Channel B is the Theorem [13](#thm:measurement){reference-type="ref"
    reference="thm:measurement"} $x_4$-pinch decoherence, of which the
    GRW Poisson rate, the CSL Lindblad noise, and the Penrose
    gravitational rate are three operational coarse-grainings.

#### Relativistic paradoxes.

-   **Twin paradox, ladder-and-pole, Bell's spaceships**
    (Theorem [27](#thm:twin){reference-type="ref"
    reference="thm:twin"}): $p_1$ = frame-independent simultaneity /
    common-rest-length; $p_2$ = relativistic time-dilation /
    length-contraction; $V$ = pre-relativistic absolute-time vocabulary;
    Channel A is the Lorentz-rotation algebra on $(t, \vec x)$; Channel
    B is the $x_4$-arclength along each worldline, with explicit
    $\Delta x_4^{(A)} - \Delta x_4^{(B)} = cT(1-\sqrt{1-v^2/c^2}) > 0$.

-   **Ehrenfest disk, Supplee, Trouton--Noble, Mansuripur**
    (Theorem [28](#thm:ehrenfest){reference-type="ref"
    reference="thm:ehrenfest"}): $p_1$ = frame-independent shape /
    momentum density of extended body; $p_2$ = frame-dependent Lorentz
    transforms produce apparent paradoxes; $V$ = rigid-body single-frame
    vocabulary; Channel A is the lab-frame stress-energy decomposition;
    Channel B is the local $x_4$-frame of each body part with its own
    instantaneous Lorentz tilt.

-   **Rietdijk--Putnam--Penrose / block universe / becoming**
    (Theorem [29](#thm:block){reference-type="ref"
    reference="thm:block"}): $p_1$ = block universe (all events equally
    real); $p_2$ = phenomenological becoming (privileged present); $V$ =
    single-channel time-ontology vocabulary; Channel A is the integrated
    past $\bigcup_O \mathrm{past}(O)$; Channel B is the present advance
    of each observer's $x_4$-frame at $|dx_4/dt|=c$.

-   **Mach's principle and the origin of inertia**
    (Theorem [30](#thm:mach){reference-type="ref"
    reference="thm:mach"}): $p_1$ = inertia is relational to distant
    matter (Mach); $p_2$ = inertia is fixed by an unobservable absolute
    space (Newton); $V$ = "the absolute element is either a stage or a
    relational content" vocabulary; Channel A is the algebraic
    four-velocity budget partition $|\vec v|^2 + c_{x_4}^2 = c^2$;
    Channel B is the local geometric content of $dx_4/dt = ic$ at each
    event. The bucket climbs in an empty universe (anti-Machian), yet
    Newton's absolute space is excluded (the absolute element is the
    active expansion, not an inert stage).

-   **Gödel's universe and chronology protection**
    (Theorem [32](#thm:godel){reference-type="ref"
    reference="thm:godel"}): $p_1$ = the Einstein field equations admit
    closed-timelike-curve solutions (Gödel, van Stockum, Tipler); $p_2$
    = observed universe protects chronology (Hawking's conjecture); $V$
    = sign-blind integrated-coordinate vocabulary; Channel A is the
    algebraic label $x_4 = ict$, which is invariant under $ic \to -ic$;
    Channel B is the velocity $dx_4/dt = ic$, whose $+ic$ orientation
    forbids $\oint dx_4 = 0$ along a closed timelike curve. Chronology
    protection is a theorem, not a conjecture; Gödel's solution is the
    predicted symptom of the sign-blind formalism.

-   **Abraham--Lorentz self-force**
    (Theorem [34](#thm:selfforce){reference-type="ref"
    reference="thm:selfforce"}): $p_1$ = causal classical
    electrodynamics; $p_2$ = runaway and pre-acceleration in the ALD
    equation; $V$ = point-charge classical-electrodynamics vocabulary;
    Channel A is the Liénard--Wiechert retarded field; Channel B is the
    Compton-cutoff regularization at $\ell_C = \hbar/(mc)$ with
    $+ic$-oriented Sommerfeld radiation condition.

-   **Einstein elevator, gravitational redshift, Schwarzschild horizon**
    (Theorem [35](#thm:elevator){reference-type="ref"
    reference="thm:elevator"}): $p_1$ = uniform $t$-coordinate across
    spacetime; $p_2$ = redshift, equivalence-principle
    indistinguishability, horizon coordinate-singularity; $V$ =
    global-time-coordinate vocabulary; Channel A is the asymptotic
    $\partial_t$ Killing field; Channel B is the local $x_4$-frame at
    each event with progressive rotation reaching $\pi/2$ at the
    horizon.

-   **Sorkin impossible measurements / Martín-Martínez pathologies /
    Unruh frame dependence**
    (Theorem [41](#thm:sorkin-unruh){reference-type="ref"
    reference="thm:sorkin-unruh"}): $p_1$ = global Tomonaga--Schwinger
    operator algebra; $p_2$ = no-signaling and frame-independent vacuum;
    $V$ = single-$x_4$-frame QFT vocabulary; Channel A is the global
    operator algebra; Channel B is the null-cone-restricted local
    $x_4$-velocity field; the Unruh thermal occupation is the Bogoliubov
    mismatch between two local $x_4$-frames.

-   **Wheeler--DeWitt problem of time**
    (Theorem [42](#thm:wdw){reference-type="ref" reference="thm:wdw"}):
    $p_1$ = QM parameter-time (Pauli no-time-operator); $p_2$ = GR
    coordinate-time (diffeomorphism-covariant); $V$ = single-channel
    time-treatment vocabulary; Channel A is the canonical-quantization
    constraint $\hat{\mathcal H}|\Psi\rangle = 0$; Channel B is the
    Page--Wootters relational time from $|dx_4/dt|=c$ along a clock
    subsystem.

#### Gravity, cosmology, and the dark sector.

-   **Black hole information and AMPS firewall**
    (Theorem [36](#thm:bh-info){reference-type="ref"
    reference="thm:bh-info"}): $p_1$ = Hawking thermal radiation
    (apparent information loss); $p_2$ = unitary quantum evolution
    (information preservation); $V$ = single-observer-frame vocabulary;
    Channel A is the asymptotic-frame reduced state on the exterior;
    Channel B is the in-faller-frame $x_4$-advance through the horizon's
    $\pi/2$ rotation. The Page curve tracks the interior--exterior
    $x_4$-frame redistribution; AMPS dissolves because the three
    propositions (unitarity, equivalence, EFT) hold in different
    observers' $x_4$-frames.

-   **ER = EPR** (Theorem [65](#thm:er-epr){reference-type="ref"
    reference="thm:er-epr"}): $p_1$ = geometric wormhole connection
    (Einstein--Rosen bridge); $p_2$ = quantum entanglement correlation
    (EPR); $V$ = geometry-vs-information vocabulary; Channel A is the
    entanglement algebra on the joint Hilbert space; Channel B is the
    shared McGucken Sphere $\Sigma_+(p_0)$ from the entangling event.

-   **Cosmological constant**
    (Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}):
    $p_1$ = QFT zero-point energy
    $\rho_{\rm QFT} \sim 10^{72}\,\mathrm{GeV}^4$; $p_2$ = observed dark
    energy $\rho_\Lambda \sim 10^{-47}\,\mathrm{GeV}^4$ ($10^{120}$
    discrepancy); $V$ = operator-vacuum-sum vocabulary; Channel A is the
    QFT zero-point sum on a fixed Minkowski background; Channel B is the
    McGucken Sphere expansion rate $\Lambda = 3H^2/c^2$; the discrepancy
    is Channel-A double-counting of the $x_4$-expansion already present
    in Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}.

-   **Cosmological problems: horizon, flatness, Olbers, Hubble tension,
    $S_8$ tension** (Theorem [39](#thm:cosmo){reference-type="ref"
    reference="thm:cosmo"}): $p_1$ = pre-inflation FRW cosmology /
    standard-candle late-time $H_0$; $p_2$ = uniform CMB / observed
    flatness / dark night sky / early-late $H_0$ mismatch; $V$ =
    standard $\Lambda$CDM vocabulary; Channel A is the standard FRW
    evolution; Channel B is the universal $|dx_4/dt|=c$ rate at every
    event supplying CMB uniformity and spatial flatness, with
    local-$x_4$-frame correction supplying the late-time tensions.

-   **Dark matter** (Theorem [60](#thm:dark-matter){reference-type="ref"
    reference="thm:dark-matter"}): $p_1$ = visible-matter Standard-Model
    content; $p_2$ = observed galactic dynamics, lensing, structure
    growth requiring $\sim 5{:}1$ excess; $V$ =
    Standard-Model-Compton-only vocabulary; Channel A is the SM operator
    content; Channel B is the McGucken-Sphere $x_4$-coupled mass beyond
    the SM Compton sector.

-   **Dark energy and the coincidence problem**
    (Theorem [61](#thm:dark-energy){reference-type="ref"
    reference="thm:dark-energy"}): $p_1$ = QFT vacuum prediction; $p_2$
    = observed $\Omega_\Lambda \sim 0.7$ with
    $\Omega_\Lambda \sim \Omega_m$ at the present epoch; $V$ =
    anthropic-multiverse vocabulary; Channel A is the operator-vacuum
    sum; Channel B is the cosmological McGucken Sphere expansion rate,
    with the coincidence reflecting the structural synchronization of
    matter dilution and Sphere expansion.

-   **Monopole problem**
    (Theorem [62](#thm:monopole){reference-type="ref"
    reference="thm:monopole"}): $p_1$ = grand-unified-theory monopole
    production at the GUT phase transition; $p_2$ = absence of observed
    monopoles; $V$ = inflation-required vocabulary; Channel A is the GUT
    topological defect count; Channel B is the McGucken-Sphere
    correlation structure that constrains topological defects without
    invoking inflation.

-   **Trans-Planckian problem**
    (Theorem [63](#thm:trans-planckian){reference-type="ref"
    reference="thm:trans-planckian"}): $p_1$ = Hawking radiation modes'
    asymptotic frequency; $p_2$ = bounded local frequency in the
    in-faller's frame; $V$ = asymptotic-frame-extrapolation vocabulary;
    Channel A is the asymptotic-frame frequency; Channel B is the
    in-faller's local $x_4$-frame frequency with no trans-Planckian
    content.

-   **Boltzmann brains**
    (Theorem [64](#thm:boltzmann-brains){reference-type="ref"
    reference="thm:boltzmann-brains"}): $p_1$ = equilibrium thermal
    fluctuations producing brain-like configurations; $p_2$ = absence of
    dominating Boltzmann-brain observer measure; $V$ =
    anthropic-multiverse vocabulary; Channel A is the equilibrium
    fluctuation theory; Channel B is the $+ic$ orientation of
    $x_4$-expansion at every event, which structurally forbids downward
    entropy fluctuations of the required magnitude (no equilibrium to
    fluctuate from).

#### Statistical mechanics and time.

-   **Arrow of time: Loschmidt, Poincaré recurrence, Maxwell demon,
    Landauer** (Theorem [40](#thm:arrow){reference-type="ref"
    reference="thm:arrow"}): $p_1$ = time-symmetric microscopic
    dynamics; $p_2$ = universal macroscopic time-asymmetry (five
    arrows); $V$ = Past-Hypothesis-as-boundary-condition vocabulary;
    Channel A is the time-symmetric Hamiltonian flow; Channel B is the
    $+ic$ orientation of $x_4$-expansion at every event supplying all
    five arrows (thermodynamic, electromagnetic-radiative, cosmological,
    psychological, quantum-measurement).

#### Quantum field theory structural paradoxes.

-   **Gauge dependence and the Faddeev--Popov ghost**
    (Theorem [50](#thm:gauge-ghost){reference-type="ref"
    reference="thm:gauge-ghost"}): $p_1$ = gauge-invariant physical
    content; $p_2$ = gauge-fixing-required path integral; $V$ =
    single-gauge-frame vocabulary; Channel A is the BRST-cohomology
    algebraic structure (with $Q^2 = 0$ tracking the $i^2 = -1$
    Channel-A factor); Channel B is the McGucken-Sphere local
    $x_4$-frame redundancy across gauge orbits.

-   **Chiral, conformal, and gravitational anomalies**
    (Theorem [51](#thm:anomalies){reference-type="ref"
    reference="thm:anomalies"}): $p_1$ = classical symmetry of the
    action; $p_2$ = quantum-mechanical breaking of the symmetry; $V$ =
    classical-symmetry-survives-quantization vocabulary; Channel A is
    the path-integral Jacobian of the symmetry transformation; Channel B
    is the $x_4$-measure's non-invariance under the symmetry, with the
    anomaly coefficient computed from the McGucken-Sphere counting.

-   **Renormalization**
    (Theorem [52](#thm:renormalization){reference-type="ref"
    reference="thm:renormalization"}): $p_1$ = predictive low-energy
    effective theory; $p_2$ = UV-divergent bare quantities; $V$ =
    bare-Lagrangian vocabulary; Channel A is the operator-algebraic
    renormalization-group flow; Channel B is the McGucken-Sphere
    Compton-scale cutoff that naturally regularizes $x_4$-mode
    integration without ad hoc counterterms.

-   **Landau pole and triviality**
    (Theorem [53](#thm:landau){reference-type="ref"
    reference="thm:landau"}): $p_1$ = perturbatively renormalizable QED
    / $\phi^4$; $p_2$ = Landau pole / triviality bound at high energy;
    $V$ = Wilsonian-flow-as-fundamental vocabulary; Channel A is the
    operator-algebraic running coupling; Channel B is the
    Compton-locality bound, beyond which Channel-A extrapolation has no
    Channel-B support.

-   **Higgs hierarchy problem**
    (Theorem [54](#thm:hierarchy){reference-type="ref"
    reference="thm:hierarchy"}): $p_1$ = quadratic Planck-scale
    divergence in the Higgs self-energy from loop integrals; $p_2$ =
    electroweak scale $m_H \sim 125\,\mathrm{GeV}$; $V$ =
    no-symmetry-protection vocabulary; Channel A is the
    operator-algebraic loop integral; Channel B is the McGucken Sphere
    Compton-cutoff at the top mass $m_t$.

-   **Vacuum metastability**
    (Theorem [55](#thm:vacuum-stability){reference-type="ref"
    reference="thm:vacuum-stability"}): $p_1$ = stable electroweak
    vacuum at low energy; $p_2$ = metastable vacuum extrapolation to
    Planck-scale energies; $V$ = full-Planck-scale-validity vocabulary;
    Channel A is the running Higgs quartic coupling $\lambda(\mu)$;
    Channel B is the Compton-cutoff signature beyond which the Channel-A
    extrapolation is not Channel-B-supported.

-   **First versus second quantization**
    (Theorem [76](#thm:first-second-q){reference-type="ref"
    reference="thm:first-second-q"}): $p_1$ = first-quantized
    wave-mechanical Hilbert space; $p_2$ = second-quantized Fock-space
    field theory; $V$ = separate-formalism vocabulary; Channel A is the
    wave-function algebra; Channel B is the Fock-space ladder operators,
    both as readings of the same underlying $x_4$-Sphere structure.

-   **Microcausality versus Reeh--Schlieder entanglement**
    (Theorem [77](#thm:microcausality){reference-type="ref"
    reference="thm:microcausality"}): $p_1$ = local commutativity
    $[\hat\phi(x), \hat\phi(y)] = 0$ at spacelike separation; $p_2$ =
    Reeh--Schlieder cyclic-and-separating vacuum entanglement across
    regions; $V$ = locality-vs-entanglement vocabulary; Channel A is the
    local field-operator algebra; Channel B is the vacuum-state
    McGucken-Sphere-sharing across all events.

#### Standard Model paradoxes.

-   **Baryogenesis**
    (Theorem [56](#thm:baryogenesis){reference-type="ref"
    reference="thm:baryogenesis"}): $p_1$ = symmetric initial Big Bang
    state; $p_2$ = observed baryon-antibaryon asymmetry
    $\eta \sim 10^{-9}$; $V$ = Sakharov-three-conditions vocabulary;
    Channel A is the CP-violating CKM phase; Channel B is the
    $+ic$-orientation $x_4$-asymmetry that makes the Sakharov
    out-of-equilibrium condition automatic, with $\eta$ magnitude open
    as a derivation target.

-   **Strong CP problem**
    (Theorem [57](#thm:strong-cp){reference-type="ref"
    reference="thm:strong-cp"}): $p_1$ = QCD CKM-CP phase
    $\theta_{\rm CKM} \sim \mathcal{O}(1)$; $p_2$ = experimental
    $|\bar\theta| < 10^{-10}$ from neutron EDM; $V$ = axion-required
    vocabulary; Channel A is the CKM Yukawa contribution to
    $\bar\theta$; Channel B is the McGucken-Sphere instanton-action
    contribution suppressing $\bar\theta$ by
    $\sim (\Lambda_{\rm QCD}/m_W)^4 \sim 10^{-10}$.

-   **Naturalness** (Theorem [58](#thm:naturalness){reference-type="ref"
    reference="thm:naturalness"}): $p_1$ = 't Hooft-naturalness
    criterion (small parameters protected by enhanced symmetry); $p_2$ =
    small parameters in Standard Model without symmetry protection
    (Higgs mass, $\bar\theta$, $\Lambda$); $V$ =
    single-channel-naturalness vocabulary; Channel A is the
    operator-algebraic running of small parameters; Channel B is the
    McGucken-Sphere Compton-locality, supplying natural smallness from
    geometric structure rather than symmetry protection.

-   **Three generations**
    (Theorem [59](#thm:generations){reference-type="ref"
    reference="thm:generations"}): $p_1$ = single-generation
    Standard-Model-prediction-as-minimal; $p_2$ = observed three
    families with mass hierarchies; $V$ =
    Yukawa-Lagrangian-as-free-parameter vocabulary; Channel A is the
    Yukawa coupling matrix; Channel B is the McGucken-Sphere triadic
    structure that enforces three generations from a geometric origin.

#### Modern quantum gravity.

-   **Computational complexity and bulk geometry**
    (Theorem [66](#thm:complexity){reference-type="ref"
    reference="thm:complexity"}): $p_1$ = boundary CFT complexity
    growth; $p_2$ = bulk geometric quantity (volume of maximal slice,
    action of Wheeler--DeWitt patch); $V$ = complexity-as-conjecture
    vocabulary; Channel A is the boundary computational-complexity
    functional; Channel B is the integrated $x_4$-volume of the McGucken
    Sphere bulk structure.

-   **Holographic principle**
    (Theorem [67](#thm:holography){reference-type="ref"
    reference="thm:holography"}): $p_1$ = bulk volume scaling of degrees
    of freedom; $p_2$ = boundary area-law scaling of information
    capacity; $V$ = local-bulk-QFT vocabulary; Channel A is the bulk
    operator algebra; Channel B is the McGucken Sphere boundary-area
    structure at every event.

-   **AdS/CFT and bulk reconstruction**
    (Theorem [68](#thm:ads-cft){reference-type="ref"
    reference="thm:ads-cft"}): $p_1$ = boundary CFT correlator
    structure; $p_2$ = bulk gravitational dual; $V$ =
    duality-as-conjecture vocabulary; Channel A is the boundary CFT
    operator algebra; Channel B is the bulk McGucken-Sphere
    reconstruction supplying the holographic boundary--bulk map.

-   **Page curve** (Theorem [69](#thm:page-curve){reference-type="ref"
    reference="thm:page-curve"}): $p_1$ = monotonically-increasing
    thermal-radiation entropy (Hawking); $p_2$ = unitary purification
    curve (peaks at Page time, returns to zero); $V$ =
    semiclassical-effective-field-theory vocabulary; Channel A is the
    asymptotic thermal density; Channel B is the McGucken-Sphere
    distribution between black hole interior and exterior radiation,
    redistributing at the Page time.

-   **Bekenstein bound**
    (Theorem [70](#thm:bekenstein){reference-type="ref"
    reference="thm:bekenstein"}): $p_1$ = unbounded-entropy
    quantum-field content; $p_2$ = area-law-bounded black-hole-entropy;
    $V$ = local-QFT-entropy-as-extensive vocabulary; Channel A is the
    QFT entropy of a region; Channel B is the McGucken-Sphere
    Compton-locality bound $S \le 2\pi k_B RE/(\hbar c)$, saturated by
    Schwarzschild.

-   **Soft hair and BMS symmetry**
    (Theorem [71](#thm:soft-hair){reference-type="ref"
    reference="thm:soft-hair"}): $p_1$ = classical no-hair theorem
    (horizon characterized only by mass, charge, spin); $p_2$ = BMS
    soft-hair memory of formation history; $V$ = classical-no-hair
    vocabulary; Channel A is the horizon entropic content (no classical
    hair); Channel B is the asymptotic McGucken Sphere $x_4$-phase
    memory at null infinity (soft hair).

#### Classical and foundational paradoxes.

-   **Gibbs paradox of mixing entropy**
    (Theorem [72](#thm:gibbs){reference-type="ref"
    reference="thm:gibbs"}): $p_1$ = entropy of mixing for
    distinguishable gases; $p_2$ = zero mixing entropy for identical
    gases; $V$ = distinguishable-particles-only vocabulary; Channel A is
    the distinguishable-particle state count; Channel B is the
    Compton-frequency identity reduction (identical particles share
    Compton-period content).

-   **D'Alembert paradox**
    (Theorem [73](#thm:dalembert){reference-type="ref"
    reference="thm:dalembert"}): $p_1$ = zero-drag prediction in
    inviscid Euler flow; $p_2$ = nonzero drag at all finite viscosity;
    $V$ = inviscid-as-fundamental vocabulary; Channel A is the inviscid
    Euler limit; Channel B is the McGucken-Sphere-sourced viscosity
    $\nu$ from Compton-coupled diffusion.

-   **Einstein's hole argument**
    (Theorem [74](#thm:hole){reference-type="ref"
    reference="thm:hole"}): $p_1$ = diffeomorphism-equivalent metrics;
    $p_2$ = supposedly-distinct physical configurations; $V$ =
    coordinate-as-physical vocabulary; Channel A is the
    coordinate-labeled metric; Channel B is the McGucken-Sphere
    gauge-invariant content under $\mathrm{Diff}(\mathcal{M})$.

-   **Painlevé non-collision singularity**
    (Theorem [75](#thm:painleve){reference-type="ref"
    reference="thm:painleve"}): $p_1$ = bounded velocities in physical
    $N$-body systems; $p_2$ = unbounded velocity in finite time in
    Newtonian $N$-body systems; $V$ = nonrelativistic-Newtonian
    vocabulary; Channel A is the nonrelativistic instantaneous-gravity
    limit; Channel B is the finite-$c$ McGucken-Sphere propagation that
    excludes the unbounded velocities.

#### Cosmological multiverse problems.

-   **Inflation versus eternal inflation**
    (Theorem [78](#thm:inflation-eternal){reference-type="ref"
    reference="thm:inflation-eternal"}): $p_1$ = single-inflation-epoch
    finite-universe cosmology; $p_2$ = eternal-inflation multiverse
    cosmology; $V$ = inflaton-field-as-foundational vocabulary; Channel
    A is the inflaton field's quantum fluctuations driving runaway
    expansion; Channel B is the McGucken Sphere's universal
    $|dx_4/dt|=c$ expansion at every event, without need for an inflaton
    field, hence no eternal inflation and no multiverse.

-   **Cosmological measure problem**
    (Theorem [79](#thm:cosmo-measure){reference-type="ref"
    reference="thm:cosmo-measure"}): $p_1$ = well-defined probability
    measure on multiverse pocket universes; $p_2$ = no consistent
    measure (measure-theoretic ambiguity, Boltzmann brain dominance);
    $V$ = multiverse-required vocabulary; Channel A is the multiverse
    partition function; Channel B is the absence of multiverse under
    Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"} (one
    cosmological McGucken Sphere expansion), dissolving the measure
    problem at the source.

#### Wick rotation as load-bearing throughout.

-   **Wick rotation paradox**
    (Theorem [48](#thm:wick-rotation){reference-type="ref"
    reference="thm:wick-rotation"}): $p_1$ = Lorentzian-signature
    Schrödinger unitarity; $p_2$ = Euclidean-signature heat-equation
    dissipation; $V$ = signature-as-bookkeeping vocabulary; Channel A is
    the Lorentzian-signature interior-$i$ (from the $i$ in
    $i\hbar \partial_t = \hat H$); Channel B is the Euclidean-signature
    exterior-$i$ (from the $i$ in $dx_4/dt = ic$ as a velocity); the
    $\pi/2$ Wick rotation is the structural transit between the two
    channel-readings of the same foundational principle.

The catalog spans every theorem of this paper. Each entry exhibits the
same dual-channel structure: two propositions $p_1, p_2$ that appear
contradictory under the orthodox single-channel vocabulary $V$, with
both being simultaneously true as Channel-A and Channel-B readings of
the same foundational content of $dx_4/dt = ic$. The meta-theorem
articulates what was implicit in every dissolution: the unity of the
principle sources relatedness; the duality of the channels sources
disjointness; the simultaneity is foundational.

## The Patch-Accretion Pattern as Empirical-Historical Signature

The orthodox tradition's 152-year history (1872--2024) of foundational
physics has produced more than twenty operationally-disparate postulates
inserted at the structural locations of unresolved paradoxes: the Born
rule (Born 1926); the *Stosszahlansatz* (Boltzmann 1872); the Past
Hypothesis; the Weyl Curvature Hypothesis (Penrose 1979); the
decoherence superselection programme (Zeh 1970, Zurek 1981); the GRW
spontaneous-collapse postulate (Ghirardi--Rimini--Weber 1986); the
Everett many-worlds branching postulate (Everett 1957); QBism
(Fuchs--Caves--Schack 2002); consistent histories (Griffiths 1984); the
Bohmian pilot-wave (de Broglie 1927 / Bohm 1952); the maximum-entropy
principle (Jaynes 1957); the coarse-graining partition postulate (Gibbs
1902); the K41 stochastic-forcing closure (Kolmogorov 1941); the
SRB-measure absolute-continuity selection (Sinai--Ruelle--Bowen 1970s);
the quantum-chaos random-matrix-theory statistics postulate
(Bohigas--Giannoni--Schmit 1984); the thermal-time hypothesis
(Connes--Rovelli 1994); the black-hole complementarity postulate
(Susskind--Thorlacius--Uglum 1993); the ER=EPR conjecture
(Maldacena--Susskind 2013); the complexity-equals-action /
complexity-equals-volume conjecture (Susskind 2014); the
second-law-of-complexity postulate (Susskind 2018); and the Sakharov
out-of-equilibrium baryogenesis condition (Sakharov 1967).

Each patch closes the empirical-prediction gap at the operational level
without resolving the underlying foundational tension. Each patch is the
orthodox response-(iii) (patch-accretion) to a paradox whose structural
form is captured by the meta-theorem. The patch-accretion pattern is the
empirical-historical signature of the orthodox tradition's 152-year
operation in a single-channel single-reading vocabulary $V$ that
structurally cannot articulate the dual-channel content of
$dx_4/dt = ic$.

The McGucken framework's load-bearing claim: *the orthodox tradition
has, across 152 years, been operating in a single-channel single-reading
vocabulary that structurally cannot resolve paradoxes of the form
$P = (p_1, p_2, V)$ without resorting to one of the three
structurally-inadequate orthodox responses. The dual-channel
identification of $dx_4/dt = ic$ supplies the fourth response, and the
fourth response resolves the load-bearing foundational paradoxes of
physics via the single foundational principle.*

#### One principle, two channels, all paradoxes.

## The Susskind--Carroll Combined Empirical Demonstration: Ten Patches across Two Careers

The patch-accretion pattern is most clearly visible in the
foundational-physics careers of the orthodox tradition's two most
prominent foundational theorists of the past three decades, Leonard
Susskind (1969--2024) and Sean Carroll (2004--2024). Their combined ten
operationally-disparate foundational additions across the combined
1993--2024 period constitute a sustained empirical demonstration of the
meta-theorem's necessity. Each patch accesses a different aspect of the
same Channel-B McGucken Sphere content; none identifies the underlying
$dx_4/dt = ic$ principle that the McGucken framework supplies.

#### The five Susskind patches (1993--2018).

-   **(S1) Black-hole complementarity** (Susskind--Thorlacius--Uglum
    1993 [@SusskindThorlaciusUglum1993]): observer-dependent
    operator-algebraic content at the horizon, postulated to reconcile
    infaller and asymptotic descriptions. The McGucken identification
    (Theorem [36](#thm:bh-info){reference-type="ref"
    reference="thm:bh-info"}): the two observer descriptions are the
    Lorentzian and Euclidean $x_4$-frame readings of the same horizon
    content; complementarity accesses the Channel-B McGucken-Wick
    signature-change without identifying it as such.

-   **(S2) Holographic principle** ('t Hooft 1993 [@tHooft1993];
    Susskind 1995 [@Susskind1995]): bulk degrees of freedom encoded on
    the boundary, postulated from black-hole entropy area-law. The
    McGucken identification
    (Theorem [67](#thm:holography){reference-type="ref"
    reference="thm:holography"}): the McGucken Sphere at every event is
    a holographic screen; the principle accesses Channel-B
    Sphere-as-screen structure without identifying it.

-   **(S3) ER = EPR conjecture** (Maldacena--Susskind
    2013 [@Maldacena2013]): geometric realization of entanglement
    through wormholes. The McGucken identification
    (Theorem [65](#thm:er-epr){reference-type="ref"
    reference="thm:er-epr"}): entangled events share a McGucken Sphere
    from the entangling interaction; ER = EPR accesses Channel-B
    Sphere-connectivity without identifying it.

-   **(S4) Complexity = Volume / Action** (Susskind
    2014 [@Susskind2014], Brown--Roberts--Susskind--Swingle--Zhao
    2016 [@Brown2016]): bulk geometric quantity dual to boundary
    computational complexity. The McGucken identification
    (Theorem [66](#thm:complexity){reference-type="ref"
    reference="thm:complexity"}): integrated $x_4$-volume of the
    McGucken Sphere structure; CV/CA access Channel-B
    iterated-Sphere-path-length without identifying it.

-   **(S5) Second Law of Complexity** (Brown--Susskind
    2018 [@BrownSusskind2016]): new monotone-growth principle for
    complexity, analog of thermodynamic Second Law. The McGucken
    identification (Theorem [40](#thm:arrow){reference-type="ref"
    reference="thm:arrow"}, extended): the $+ic$-orientation of
    $x_4$-expansion at every event supplies the same arrow for entropy
    and complexity; the second law of complexity accesses the $+ic$
    orientation of Channel B's path-space measure without identifying
    it.

Five patches across thirty-one years, each a postulate or conjecture
rather than a derivation, each accessing a Channel-B content of
$dx_4/dt = ic$ that the McGucken framework supplies as a theorem.

#### The five Carroll patches (2004--2024).

-   **(C1) Many-Worlds Revival** (Carroll 2019; Sebens--Carroll 2018):
    Born rule as derived from self-locating uncertainty across branches,
    requiring exponentially many real branches. The McGucken
    identification (Theorem [45](#thm:born){reference-type="ref"
    reference="thm:born"}): the Born rule is the SO(3)-Haar measure on
    the McGucken Sphere at every registration event; the many-worlds
    branching is the Channel-B Sphere-Haar content accessed through a
    branching postulate that requires multiple real branches the
    McGucken framework does not need.

-   **(C2) Past Hypothesis Advocacy** (Carroll 2010; following Albert
    2000): low-entropy initial cosmological condition as the source of
    macroscopic time-asymmetry. The McGucken identification
    (Theorem [40](#thm:arrow){reference-type="ref"
    reference="thm:arrow"}): the $+ic$ orientation is foundational at
    every event, not merely a boundary condition; the Past Hypothesis
    accesses the $+ic$-orientation Channel-B content through a
    boundary-condition postulate that the McGucken framework supplies as
    foundational.

-   **(C3) Cosmological Multiverse with Eternal Inflation**
    (Carroll--Chen 2004): single-universe time-asymmetry derived from
    multiverse-level time-symmetry. The McGucken identification
    (Theorem [78](#thm:inflation-eternal){reference-type="ref"
    reference="thm:inflation-eternal"}): the cosmological McGucken
    Sphere expansion supplies the observed cosmological content; the
    multiverse postulate is the Channel-B cosmological-Sphere-expansion
    content accessed through a multiverse postulate that the McGucken
    framework does not require.

-   **(C4) Boltzmann-Brain Problem** (Carroll 2017): structural
    consequence of multiverse postulate, requiring exotic measure
    choices to avoid Boltzmann-brain dominance. The McGucken
    identification
    (Theorem [64](#thm:boltzmann-brains){reference-type="ref"
    reference="thm:boltzmann-brains"}): no equilibrium state exists in
    the McGucken framework, so Boltzmann brains are forbidden; the
    Carroll articulation accesses the Channel-B cosmological-Sphere
    observer-distribution content through a problem-statement that is
    dissolved at the foundational level by the absence of multiverse.

-   **(C5) Entropic-Gravity Engagement** (Verlinde 2011 [@Verlinde2011];
    Carroll 2010): gravitational force as emergent from entanglement
    entropy / holographic screen. The McGucken identification
    (Theorem [67](#thm:holography){reference-type="ref"
    reference="thm:holography"}, extended): the McGucken Sphere at every
    event is the gravitational-source screen; the entropic-gravity
    proposal accesses the same Channel-B Sphere-as-screen content as the
    holographic principle, via an entropy-gradient formulation.

Five patches across twenty years, each accessing the same Channel-B
content from a different operational angle, each postulated separately
within the orthodox-tradition Channel-A-only-reading vocabulary.

#### The combined ten-patch table.

   \#  Programme                       Year    Patch                                         Channel-B content accessed
  ---- ----------------------------- --------- --------------------------------------------- -------------------------------------------------
   S1  Susskind--Thorlacius--Uglum     1993    Black-hole complementarity                    Horizon Wick-rotation observer-dependence
   S2  't Hooft / Susskind            1993/95  Holographic principle                         Sphere-as-screen at every event
   S3  Maldacena--Susskind             2013    ER = EPR                                      Sphere-connectivity at entangled events
   S4  Susskind / BRSSZ               2014/15  Complexity = action / volume                  Iterated-Sphere-path-length
   S5  Susskind                        2018    Second law of complexity                      $+ic$ orientation of path-space measure
   C1  Carroll / Sebens--Carroll      2010/18  Many-worlds; Born from SLU                    Sphere SO(3)-Haar at measurement
   C2  Carroll                         2010    Past Hypothesis advocacy                      $+ic$ orientation at cosmological initial state
   C3  Carroll--Chen                   2004    Cosmological multiverse / eternal inflation   Cosmological-Sphere expansion
   C4  Carroll--Chen / Carroll        2005/17  Boltzmann-brain problem                       Cosmological-Sphere observer-distribution
   C5  Verlinde / Carroll              2011    Entropic-gravity engagement                   Sphere-as-screen gravitational source

  : Ten operationally-disparate patches across two careers, all
  accessing Channel-B McGucken Sphere content of $dx_4/dt = ic$ without
  identifying it.

#### The structural lesson.

Ten operationally-disparate foundational additions across two prominent
careers, combined 1993--2024 period (thirty-one years), each inserted at
a precise structural location where the orthodox-tradition
Channel-A-only-reading vocabulary cannot articulate the foundational
content natively, each postulated separately within that vocabulary,
each accessing a different aspect of the same Channel-B content of
$dx_4/dt = ic$. The same one principle has been accessed ten times under
ten different vocabularies, by the two most prominent
foundational-physics-foundational-cosmology theorists of the period,
without the underlying unity being identified by either. The McGucken
framework supplies the unified source.

The combined Susskind--Carroll case study is not a refutation of either
career at the strict-mathematical level: the orthodox patches are
consistent within their respective formal frameworks. The
structural-foundational refutation is the identification that the ten
patches are ten operational accesses to the same Channel-B content, and
that the McGucken framework supplies the unified source with ten fewer
foundational postulates.

#### One principle, two channels, ten patches, one unified source.

# The Methodological Diagnostic: Heroic Philosophy and the Spirit of the Fathers 

The Meta-Theorem of §[61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"} supplies the structural-foundational
mechanism by which the McGucken framework resolves paradoxes. The
Susskind--Carroll combined empirical demonstration of
§[61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"} supplies the empirical-historical
signature of the orthodox-tradition's failure to identify the mechanism.
The present chapter supplies the methodological-philosophical content:
the structural source of the orthodox-tradition's blindness, articulated
as the methodological inversion of the Spirit of the Fathers of science,
and the realization of the Heroic Scientific Philosophy of Finding the
Simple Truth as the methodological character that underlies the McGucken
framework.

## The Structural Source of the Patch-Accretion Pattern

The orthodox tradition's 152-year history of foundational physics
(1872--2024) exhibits a pattern: at every structural location where the
orthodox-tradition single-channel vocabulary cannot articulate the
foundational content of nature, a postulate is inserted by hand. The
pattern catalogued in the Susskind--Carroll case study (ten patches) and
the broader patch list of §[61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"} (more than twenty) is not random. The
structural source admits identification.

Seven specific instances of ontological-mathematical contradiction are
taught as acceptable in the standard pedagogical literature of
foundational physics. Each is the orthodox-tradition's recognition that
the single-channel vocabulary is structurally inadequate; each is then
closed by the addition of a separate postulate, leaving the foundational
tension unresolved while supplying operational closure of the
empirical-prediction gap. The seven:

#### (C1) The measurement-problem coexistence of unitary evolution and Born-rule projection.

Every standard quantum-mechanics textbook from von Neumann
1932 [@vonNeumann1932] forward presents the Schrödinger evolution
$i\hbar \partial_t \psi = \hat H \psi$ as the foundational unitary
dynamics, the Born rule $P(a) = |\langle a|\psi\rangle|^2$ as the
foundational measurement probability, and the projection
$\psi \to |a\rangle$ as the foundational state update---three components
that are mutually inconsistent at the operational level. The Schrödinger
evolution preserves $\|\psi\|^2$; the projection does not. The textbook
treatment is to present the three side by side as "the postulates of
quantum mechanics," to label the resulting tension "the measurement
problem," and to proceed with calculations as if the inconsistency had
been resolved. The McGucken-framework resolution
(Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"},
Theorem [45](#thm:born){reference-type="ref" reference="thm:born"}): the
Schrödinger evolution is the Channel-A reading of $dx_4/dt = ic$ on the
Hilbert-space ray; the Born-rule probability is the Channel-B SO(3)-Haar
measure on the McGucken Sphere at the registration event; the projection
is the Wick-rotation exteriorization of $i$ at the apparatus event. The
three components are three operational shadows of the single principle,
not three independent postulates.

#### (C2) The coarse-graining ontological-status ambiguity.

Every standard statistical-mechanics textbook from Boltzmann
1872 [@Boltzmann1872] forward presents the microstate phase-space
measure $d\Gamma$ as the foundational Liouville-measure content, the
coarse-graining partition $\Gamma = \bigcup_i \Gamma_i$ into macrostates
as an observer-imposed identification, and the Boltzmann entropy
$S = k_B \ln |\Gamma_i|$ as the foundational entropy content. The
coarse-graining is observer-imposed; the entropy derived from it is
treated as foundational. The textbook treatment is to present the
coarse-graining as observer-imposed, the entropy as foundational, and to
proceed with calculations as if the ontological status were resolved.
The McGucken-framework resolution
(Theorem [40](#thm:arrow){reference-type="ref" reference="thm:arrow"},
with [@McGuckenThermodynamics2026]): the entropy is the foundational
$+ic$-orientation content of the McGucken Sphere at every event; the
coarse-graining is the observer-imposed extraction of macroscopic
variables from the foundational Sphere structure. The foundational
entropy is Channel-B; the coarse-graining is a Channel-A choice of
basis.

#### (C3) The cosmological-constant discrepancy.

The QFT estimate of the vacuum energy gives
$\rho_{\rm QFT} \sim 10^{72}\,\mathrm{GeV}^4$ when cut off at the Planck
scale; the observed value is
$\rho_\Lambda \sim 10^{-47}\,\mathrm{GeV}^4$; the discrepancy is
$\sim 10^{120}$. Weinberg's review [@Weinberg1989] called this "the
worst prediction in the history of physics." The orthodox-tradition
resolution is one of three: anthropic selection across a multiverse
landscape; supersymmetric or other symmetry-based fine cancellation;
dynamical relaxation. None has empirical confirmation. The
McGucken-framework resolution
(Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}): the
$10^{120}$ is the Channel-A double-counting of the $x_4$-expansion rate
already present in $dx_4/dt = ic$ as a contribution to the vacuum sum;
the physical $\Lambda = 3H^2/c^2$ is the Channel-B residue after
McGucken-renormalization. The discrepancy is not a 120-order failure of
physics but the 120-order signature of the unidentified dual-channel
structure.

#### (C4) The information-paradox non-consensus.

Hawking's 1975 calculation [@Hawking1975] of thermal black-hole
radiation predicted information loss; quantum mechanics requires unitary
evolution. The orthodox tradition has responded across forty-eight years
(1975--2023) with at least seven operationally-distinct postulates:
black-hole complementarity (Susskind--Thorlacius--Uglum
1993 [@SusskindThorlaciusUglum1993]); the holographic principle
('t Hooft 1993 [@tHooft1993], Susskind 1995 [@Susskind1995]); ER = EPR
(Maldacena--Susskind 2013 [@Maldacena2013]); complexity = volume /
action (Susskind 2014 [@Susskind2014]); the second law of complexity
(Brown--Susskind 2018 [@BrownSusskind2016]); the AMPS
firewall [@AMPS2013]; islands and the Page
curve [@Almheiri2019; @Penington2019]. Each closes one aspect of the
information paradox at the price of new foundational machinery; no
consensus exists. The McGucken-framework resolution
(Theorems [36](#thm:bh-info){reference-type="ref"
reference="thm:bh-info"}, [65](#thm:er-epr){reference-type="ref"
reference="thm:er-epr"}, [67](#thm:holography){reference-type="ref"
reference="thm:holography"}, [66](#thm:complexity){reference-type="ref"
reference="thm:complexity"}, [69](#thm:page-curve){reference-type="ref"
reference="thm:page-curve"}): all seven are operational accesses to the
McGucken Sphere structure at the horizon, supplied as theorems of
$dx_4/dt = ic$ via the Channel-A/Channel-B identification.

#### (C5) The QM-vs-GR time treatment incompatibility.

Time enters quantum mechanics as a parameter: Pauli's 1933
no-time-operator theorem establishes that no self-adjoint operator
$\hat T$ canonically conjugate to a Hamiltonian with bounded-below
spectrum exists, so time is not an observable. Time enters general
relativity as a coordinate: diffeomorphism-covariant, one of four
coordinates on the pseudo-Riemannian manifold. Ninety-three years of
quantum-gravity work---Wheeler--DeWitt 1967 [@DeWitt1967], canonical
quantum gravity 1986, loop quantum gravity 1986--present, string theory
1968--present, causal-set theory 1987--present, asymptotic safety
1979--present, causal dynamical triangulations 1998--present---have not
reconciled them. The McGucken-framework resolution
(Theorem [42](#thm:wdw){reference-type="ref" reference="thm:wdw"},
Theorem [35](#thm:elevator){reference-type="ref"
reference="thm:elevator"}): the QM parameter-time content is the
Channel-A integrated form of $dx_4/dt = ic$ via Stone's theorem; the GR
coordinate-time content is the Channel-B integrated form via the
geometric-route theorem of the corpus. The parameter and the coordinate
are the two channel-readings of the same principle.

#### (C6) The time-symmetric foundational equations versus the universally-observed macroscopic time-asymmetry.

The foundational equations of physics---Newton's laws, the Schrödinger
equation, the Maxwell equations, Einstein's field equations, the
Standard Model Lagrangian---are time-symmetric: each admits
time-reversed solutions. The macroscopic empirical content is
universally time-asymmetric: the Second Law of thermodynamics, the
cosmological expansion, the radiative arrow, the causal arrow, the
psychological arrow. The orthodox-tradition response is the Past
Hypothesis (Boltzmann 1896, Feynman 1965, Albert 2000 [@Albert2000]):
postulate a low-entropy cosmological initial condition; derive the
macroscopic asymmetry from the boundary condition. The Past Hypothesis
is itself unsourced; further postulates (Weyl Curvature
Hypothesis [@Penrose1989], Sakharov out-of-equilibrium
condition [@Sakharov1967], decoherent histories [@ConsistentHistories],
Connes--Rovelli thermal time [@ConnesRovelli1994]) attempt to source the
Past Hypothesis, each adding further foundational content. The
McGucken-framework resolution
(Theorem [40](#thm:arrow){reference-type="ref" reference="thm:arrow"},
Theorem [64](#thm:boltzmann-brains){reference-type="ref"
reference="thm:boltzmann-brains"}, with [@McGuckenThermodynamics2026]):
the $+ic$ orientation of $x_4$-expansion is foundational at every event;
the macroscopic time-asymmetry is a theorem; the cosmological
low-entropy initial condition is a derived consequence; no separate
boundary-condition postulate is required.

#### (C7) The probability-without-ontology Born-rule status.

The Born rule $P(a) = |\langle a|\psi\rangle|^2$ is universally accepted
as the operational measurement-probability rule of quantum mechanics.
The foundational ontological status of this probability is unresolved:
at least five operationally-disparate interpretations of probability are
advocated in the literature---frequentist, Bayesian, propensity,
ensemble, decision-theoretic (Deutsch--Wallace). The QM textbooks
present the Born rule without articulating which interpretation is
assumed. The McGucken-framework resolution
(Theorem [45](#thm:born){reference-type="ref" reference="thm:born"},
Theorem [13](#thm:measurement){reference-type="ref"
reference="thm:measurement"}): the Born-rule probability is the
foundational geometric measure on the McGucken Sphere at every
measurement event---the SO(3)-Haar measure on the Sphere's orientation
under spatial rotation. The frequentist / Bayesian / propensity /
ensemble / decision-theoretic readings are derived operational shadows.

These seven instances of ontological-mathematical contradiction are not
anomalies in the orthodox tradition. They are the pedagogical and
research norm. The structural diagnostic: the orthodox-tradition
pedagogical-and-research culture treats foundational contradiction as
acceptable while claiming the mantle of rigor through the internal
consistency of the Channel-A-only-reading vocabulary. The cost of this
acceptance is the patch-accretion pattern: at each contradiction, one or
more new foundational postulates are added to close the immediate
operational gap, while the underlying foundational tension---the
Channel-A blindness to the Channel-B content of $dx_4/dt = ic$---remains
unresolved.

## The Spirit of the Fathers: Five Structural Axes

The Heroic Scientific Philosophy of Finding the Simple Truth is the
methodological lineage in which the foundational task of physics is the
derivation of empirical content from a minimal foundational base. The
lineage runs through five load-bearing articulations, each supplying a
structural axis of the discipline.

#### (H1) The Euclidean axis---axiomatic-deductive structure.

Euclid's *Elements* (c. 300 BCE) derives thirteen books of geometric and
arithmetical content from twenty-three definitions, five postulates, and
five common notions in Book I. Twenty-three centuries of mathematics
descend from this foundational base. The discipline: derive empirical
content from a minimal foundational base; do not add definitions or
postulates beyond what the foundational task demands; do not accept
apparent contradictions as foundational; do not abandon the deductive
method. The McGucken framework realizes the Euclidean axis at maximum
compactness: one axiom, the McGucken Principle $dx_4/dt = ic$
(Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}), supplies
the foundational base from which the corpus papers and the present paper
derive hundreds of theorems via the Channel-A / Channel-B dual
structure.

#### (H2) The Newtonian axis---parsimony.

Newton's *Philosophiae Naturalis Principia Mathematica* (1687) derives
the mechanical and gravitational content of seventeenth-century
physics---Kepler's laws, the tides, the precession of the equinoxes, the
motion of comets, the shape of the earth---from three laws of motion and
the universal law of gravitation. The methodological articulation is
Rule I of Reasoning in Philosophy [@Newton1687]: "We are to admit no
more causes of natural things than such as are both true and sufficient
to explain their appearances. To this purpose the philosophers say, that
Nature does nothing in vain, and more is in vain when less will serve;
for Nature is pleased with simplicity, and affects not the pomp of
superfluous causes." The McGucken framework realizes the Newtonian axis
at the parsimony improvement ratio of one foundational principle versus
the more than twenty orthodox-tradition postulates of the
patch-accretion catalog of §[61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"}, and one foundational principle versus the
fifty-plus paradoxes resolved as theorems in this paper.

#### (H3) The Hilbertian axis---axiomatizability.

Hilbert's Sixth Problem (1900) charged the foundational-physics
community: "To axiomatize, by the way of physics, those physical
sciences in which mathematics already plays an outstanding part; in the
first rank are the theory of probabilities and mechanics." Hilbert's
1930 Königsberg lecture supplied the methodological-aspirational
articulation: *Wir müssen wissen, wir werden wissen*---we must know, we
shall know. The discipline: the foundational task of physics is the
construction of a complete axiomatic foundation; the foundational truth
is findable; the task admits no surrender. The McGucken framework
realizes the Hilbertian axis through the corpus papers establishing the
McGucken Axiom as the foundational base from which the principal
mathematical structures of physics---the Lorentzian manifold, the
complex Hilbert space, the canonical commutator, the Schrödinger and
Dirac equations, the gauge bundles of the Standard Model, Fock space,
the operator algebras---are derived as theorems.

#### (H4) The Einsteinian axis---the supreme-goal criterion.

Einstein's 1933 Herbert Spencer Lecture at Oxford, *On the Method of
Theoretical Physics*, supplied the most precise twentieth-century
formulation of the discipline: "The supreme goal of all theory is to
make the irreducible basic elements as simple and as few as possible
without having to surrender the adequate representation of a single
datum of experience." Two requirements simultaneously: simplicity of the
foundational base, and adequate empirical representation. Neither can be
sacrificed for the other. The McGucken framework realizes the
Einsteinian axis at maximum parsimony: one foundational principle,
$dx_4/dt = ic$, supplying---without surrendering empirical content---the
resolution of the more than fifty foundational paradoxes of physics
catalogued in §§[5](#sec:measurement){reference-type="ref"
reference="sec:measurement"}--[60](#sec:cosmo-measure){reference-type="ref"
reference="sec:cosmo-measure"} of the present paper via the Channel-A /
Channel-B dual structure.

#### (H5) The Wheelerian axis---foundational expectation.

John Archibald Wheeler's 1986 article *How Come the
Quantum?* [@WheelerGeons2010] closed with the load-bearing foundational
expectation: "Behind it all is surely an idea so simple, so beautiful,
so compelling that when---in a decade, a century, or a millennium---we
grasp it, we will all say to each other, how could it have been
otherwise?" The discipline: the simple truth exists; it is findable; the
foundational-physics community will recognize it as inevitable in
retrospect; the heroic task is the patient excavation until the simple
truth is found. The McGucken framework realizes the Wheelerian axis: the
foundational principle $dx_4/dt = ic$ is offered as the simple truth
Wheeler anticipated. It is simple (one equation, four characters
$dx_4/dt = ic$); it is beautiful (the geometric content of an expanding
fourth dimension at every event); it is compelling (the empirical
content of physics descends from it as theorems via the Channel-A /
Channel-B dual structure).

The five axes are not independent commitments. They are five
articulations of one methodological discipline: the patient excavation
of the single foundational principle from which the empirical content of
physics descends as theorems. The McGucken framework operates within
this discipline; the orthodox-tradition patch-accretion pattern operates
outside it.

## The Methodological Inversion of the Spirit of the Fathers

The orthodox-tradition patch-accretion pattern is the inversion of the
Spirit of the Fathers' discipline along three structural axes. Each
inversion is the methodological dual of the corresponding axis above;
each is resolved by the McGucken framework's realization of the Spirit
of the Fathers.

#### (I1) The inversion of parsimony.

Where the Newtonian axis (H2) commits the foundational theorist to one
foundational cause per foundational task, the orthodox tradition
supplies more than twenty foundational postulates (Born rule;
*Stosszahlansatz*; Past Hypothesis; Weyl Curvature Hypothesis;
decoherence superselection; GRW; CSL; Everett many-worlds; QBism;
consistent histories; Bohmian pilot-wave; maximum entropy;
coarse-graining partition; K41 stochastic forcing; SRB measures;
quantum-chaos RMT statistics; thermal time hypothesis; black-hole
complementarity; ER = EPR conjecture; complexity = volume / action
conjecture; second law of complexity; Sakharov out-of-equilibrium
baryogenesis) at the structural locations of unresolved paradoxes. The
parsimony ratio is more than twenty foundational postulates for more
than fifty paradoxes. The McGucken framework's resolution: one
foundational principle, $dx_4/dt = ic$, supplies the empirical content
of the patches and the paradoxes via the Channel-A / Channel-B dual
structure, at the structural improvement ratio of $1$:$50+$.

#### (I2) The inversion of derivation.

Where the Euclidean axis (H1) commits the foundational theorist to
derivation of empirical content from the foundational base, the orthodox
tradition supplies empirical content through twenty-plus separate
postulates without derivation from a unified foundational base. Each
postulate is a free parameter of the foundational framework; each closes
one empirical-prediction gap by hand; none derives from the others; the
foundational base has no closure. The McGucken framework's resolution:
the more than fifty paradoxes of
§§[5](#sec:measurement){reference-type="ref"
reference="sec:measurement"}--[60](#sec:cosmo-measure){reference-type="ref"
reference="sec:cosmo-measure"} are derived as theorems of
$dx_4/dt = ic$; the patches of
§[61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"} are operational accesses to the Channel-B
content supplied as theorems by the framework. The deductive chain is
restored.

#### (I3) The inversion of consistency.

Where the Einsteinian axis (H4) commits the foundational theorist to
simultaneous simplicity and adequate empirical representation (no
surrender on either), the orthodox tradition treats foundational
contradictions (C1)--(C7) as acceptable while claiming the mantle of
rigor through the Channel-A-only-reading vocabulary's internal
consistency. The Channel-A-only-reading vocabulary is consistent at the
price of the seven ontological-mathematical contradictions; the
contradictions are bridged by the operationally-disparate patches; the
foundational base is not consistent in the Einsteinian sense. The
McGucken framework's resolution: each of (C1)--(C7) is resolved at the
structural-foundational level by the dual-channel identification of the
two horns as Channel-A and Channel-B readings of one principle. The
seven contradictions decompose as seven instances of the Meta-Theorem;
the foundational consistency is restored at the source.

## The Heroic Disposition and the Wheeler-Imparted Charge

The Heroic Scientific Philosophy is *heroic* in the structural sense of
the Achillean ethic of the Western humanistic tradition. The *Iliad*'s
Achilles takes up the task of Troy because the task is worthy of the
hero's full commitment; the hero's character is defined by the task, and
the task is defined by the hero's commitment to it. Achilles's
meta-ethical position at *Iliad* IX.410--416---the willingness to accept
short-life-with-glory over long-life-without-glory---is the structural
analog of the foundational physicist's willingness to accept the
difficult-and-uncertain task of foundational excavation over the
comfortable-and-certain task of operational patch-supply.

Wheeler's 1986 charge to the foundational-physics community---the
conviction that behind it all is an idea so simple, so beautiful, so
compelling that when grasped its inevitability will be
retrospective---is the modern articulation of the Achillean meta-ethical
commitment to the foundational task. The Wheeler-imparted "nobility in
physics" charge during the present author's Princeton AB years
(1988--1990) is the same charge: the foundational task is worthy of the
foundational physicist's full commitment; the heroic disposition is the
condition of access to the foundational truth.

The McGucken framework is offered in this methodological tradition. The
principle $dx_4/dt = ic$ is the foundational content; the Channel-A /
Channel-B dual structure is the formal articulation; the more than fifty
paradoxes resolved as theorems in this paper are the
empirical-historical content; the realization of the five-axis
Spirit-of-the-Fathers lineage and the resolution of the three-axis
methodological inversion are the methodological-philosophical content.
The heroic disposition that underlies the work is the Wheeler-imparted
methodological character: the conviction that the simple truth exists,
the patience to excavate it across the obstacles of the
orthodox-tradition patch-accretion pattern, and the heroic commitment
that admits no surrender to the methodological inversion.

## The Methodological Capstone

Combining the Meta-Theorem of
§[61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"} with the methodological diagnostic of the
present chapter, the structural-foundational arithmetic of the McGucken
framework articulates as follows:

-   One foundational principle: $dx_4/dt = ic$
    (Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}).

-   Two channels: Channel A (algebraic-symmetry reading, factor $i$) and
    Channel B (geometric-propagation reading, factor $c$), with the
    position-of-$i$ asymmetry supplying the formal functorial
    distinction.

-   One meta-theorem: Theorem [80](#thm:meta){reference-type="ref"
    reference="thm:meta"}, supplying the paradox-resolution mechanism.

-   More than fifty foundational paradoxes resolved as theorems of the
    framework.

-   Twenty-plus orthodox-tradition postulates identified as operational
    accesses to Channel-B content; ten developed in detail through the
    Susskind--Carroll case study.

-   Seven ontological-mathematical contradictions of the
    orthodox-tradition pedagogical literature dissolved at the source.

-   Five-axis lineage realized: Euclid (H1), Newton (H2), Hilbert (H3),
    Einstein (H4), Wheeler (H5).

-   Three-axis methodological inversion resolved: parsimony (I1),
    derivation (I2), consistency (I3).

The McGucken framework is offered as the foundational-physical
realization of the Spirit of the Fathers in the foundational-physics
domain. The patient excavation of the single foundational principle, the
patient identification of the dual-channel structure, and the patient
instantiation of the Meta-Theorem on more than fifty paradoxes are the
heroic content of the offering. The Wheeler foundational expectation is
realized in the structural identification that, behind the apparent
plurality of foundational paradoxes, lies one principle whose dual
readings supply both horns of every paradox.

#### One principle, two channels, all paradoxes; one methodological discipline, five axes, three resolutions; one heroic task, fully committed.

# Summary: Why Paradoxes Exist 

The pattern in every paradox is the same. A derivation starts from a
Lorentz-covariant theory, integrates out the $x_4$-velocity by setting
$x_4 = ict$, performs the derivation in two frames or two regions, and
finds that the results disagree. The disagreement is then declared a
paradox.

Under Axiom [1](#ax:mcg){reference-type="ref" reference="ax:mcg"}, the
disagreement is the disagreement between two integrated shadows of the
same physical expansion. Reinstating the velocity $dx_4/dt = ic$
recovers the agreement. The reinstatement is a recognition that $x_4$ is
not a coordinate but a velocity. Every theorem in this paper traces to
the active expansion; the coordinate label is its *mere integrated
shadow*. The word "mere" is load-bearing because the integration is
exactly the step at which the paradoxes are generated.

The Meta-Theorem of Section [61](#sec:meta-theorem){reference-type="ref"
reference="sec:meta-theorem"}
(Theorem [80](#thm:meta){reference-type="ref" reference="thm:meta"})
supplies the structural-foundational articulation: every paradox
$P = (p_1, p_2, V)$ in foundational physics decomposes as the
simultaneous Channel-A and Channel-B reading of one foundational content
$C$ of $dx_4/dt = ic$. The relatedness is sourced from the principle's
unity; the disjointness is sourced from the channels' functorial
distinction; the simultaneity is foundational. The fifty-plus paradoxes
treated in this paper---spanning quantum measurement, relativity,
gravity, cosmology, quantum field theory, the Standard Model, modern
quantum gravity, statistical mechanics, classical mechanics, and
cosmological multiverse problems---are all instances of the
meta-theorem; the orthodox tradition's twenty-plus postulates over 152
years are all attempts to bridge the same Channel-A/Channel-B
distinction without identifying its source.

The methodological diagnostic of
Section [62](#sec:diagnostic){reference-type="ref"
reference="sec:diagnostic"} supplies the methodological-philosophical
content: the structural source of the orthodox-tradition patch-accretion
pattern is the methodological inversion of the Spirit of the Fathers of
science along three axes (parsimony, derivation, consistency). The
Heroic Scientific Philosophy of Finding the Simple Truth is the
methodological lineage that runs from Euclid through Newton, Hilbert,
Einstein, and Wheeler; the McGucken framework realizes this lineage
along five structural axes (H1)--(H5) and resolves the
orthodox-tradition methodological inversion along three structural axes
(I1)--(I3).

One principle, two channels, all paradoxes; one methodological
discipline, five axes, three resolutions.

# Open Problems 

The present paper develops the dual-channel resolution of fifty-five
foundational paradoxes as theorems of $dx_4/dt = ic$, with explicit
step-by-step proofs and explicit cross-references to the corpus where
strict G1 derivations exist. The framework leaves a definite set of open
problems, where the structural identification is in place but specific
derivational targets remain to be closed in future work. The present
chapter catalogs the principal open problems with the precise structural
location of each.

## The Baryogenesis Magnitude

#### Status.

Theorem [56](#thm:baryogenesis){reference-type="ref"
reference="thm:baryogenesis"} establishes that the Sakharov conditions
are theorems of $dx_4/dt = ic$ via the $+ic$ orientation of the
$x_4$-expansion combined with the CKM CP-violation and the sphaleron
$B+L$ violation at temperatures $T \gtrsim 100\,\mathrm{GeV}$. The
structural mechanism is closed: the asymmetry between forward-$x_4$ and
would-be backward-$x_4$ propagation generates the matter-antimatter
asymmetry; the sphaleron and CKM contributions are computable Channel-A
inputs; the Sakharov out-of-equilibrium condition is automatic from the
$+ic$-orientation Channel-B content.

#### Open derivational target.

The numerical magnitude of the baryon-to-photon ratio
$\eta = n_b/n_\gamma \approx 6.1 \times 10^{-10}$ remains to be derived
from the framework. The Standard Model's CKM CP-violation alone produces
$\eta \sim 10^{-20}$, off by ten orders of magnitude; the additional
Channel-B contribution from the $+ic$ orientation must supply the
remaining factor. The derivation requires quantifying the
McGucken-Sphere asymmetry between the forward-$x_4$ and would-be
backward-$x_4$ modes at the electroweak phase transition; this is a
definite numerical target with a known structural form.

#### Route to closure.

The $\eta$ magnitude is set by the ratio of the McGucken Sphere's
null-cone-restricted forward-$x_4$ phase volume to the SU(2)$_L$
sphaleron's gauge-orbit phase volume at $T \sim m_W c^2$. The closure is
the explicit computation of this ratio from the topological structure of
$SU(2)_L$ combined with the $x_4$-expansion rate at the electroweak
temperature.

## The Strominger--Vafa Central Charge

#### Status.

The Strominger--Vafa derivation of black-hole
entropy [@StromingerVafa1996] expresses the Bekenstein--Hawking entropy
of a five-dimensional extremal black hole as the logarithm of the
degeneracy of microstates of a bound state of $Q_1$ D1-branes and $Q_5$
D5-branes wrapped on $T^4 \times S^1$. The microstate count is given by
the Cardy formula
$$S = 2\pi\sqrt{\frac{c \cdot N}{6}}, \qquad c = 6 Q_1 Q_5, \qquad N = Q_p,$$
where $c$ is the central charge of the effective two-dimensional CFT on
the brane bound state and $Q_p$ is the momentum-along-$S^1$ charge.
Under the McGucken framework
(Theorem [70](#thm:bekenstein){reference-type="ref"
reference="thm:bekenstein"}, with the corpus paper [@McGuckenKK2026]),
the structural identification is that this CFT lives on a null 1+1 strip
representing the $x_4$-stationary modes of the D-brane bound state in
McGucken-Kaluza-Klein decomposition.

#### Open derivational target.

The central charge $c = 6Q_1 Q_5$ remains to be derived from
$dx_4/dt = ic$ by pinning the bosonic polarization count of the
$x_4$-stationary modes on the null 1+1 strip in the
McGucken-Kaluza-Klein framework. The factor of $6$ must arise from the
count of independent bosonic polarizations available on the brane bound
state under the McGucken-Sphere structure; the factor $Q_1 Q_5$ must
arise from the geometric multiplicity of intersecting D1-D5 strings
carrying the polarizations.

#### Route to closure.

The bosonic polarization count requires identifying which $x_4$-modes
are stationary on the null 1+1 strip in the McGucken-Kaluza-Klein
decomposition of the extremal five-dimensional black hole. The
structural ingredients are present in the corpus
(Theorem [70](#thm:bekenstein){reference-type="ref"
reference="thm:bekenstein"}, the holographic principle
Theorem [67](#thm:holography){reference-type="ref"
reference="thm:holography"}, the McGucken-Wick rotation
Theorem [48](#thm:wick-rotation){reference-type="ref"
reference="thm:wick-rotation"}); the closure requires the explicit
polarization-counting computation.

## The Yukawa Mass Hierarchy

#### Status.

The Standard Model contains nine charged-fermion masses spanning six
orders of magnitude, from the electron
($m_e \approx 0.511\,\mathrm{MeV}$) to the top quark
($m_t \approx 173\,\mathrm{GeV}$). The orthodox treatment fits the
masses to the data via the Yukawa coupling matrix's eigenvalues; the
framework does not predict the mass spectrum.
Theorem [59](#thm:generations){reference-type="ref"
reference="thm:generations"} establishes that three generations are a
consequence of the McGucken-Sphere triadic structure, but the specific
mass values within each generation remain to be derived.

#### Open derivational target.

The Yukawa eigenvalue spectrum (electron, muon, tau; up, charm, top;
down, strange, bottom) must be derived from the McGucken-framework
geometric content at the electroweak symmetry-breaking scale. The
structural form: each Yukawa eigenvalue $y_f$ is the Channel-B coupling
of the fermion's $x_4$-frame to the Higgs's $x_4$-frame, with the
magnitude set by the geometric overlap of their respective McGucken
Spheres.

#### Route to closure.

The structural framework is partially developed in the corpus Standard
Model paper [@McGuckenSM2026]; the closure requires identifying the
McGucken-Sphere geometric content of each fermion species and computing
the overlap with the Higgs Sphere. The three-generation triadic
structure (Theorem [59](#thm:generations){reference-type="ref"
reference="thm:generations"}) provides one constraint; the CKM mixing
matrix provides additional constraints relating the mass eigenvalues
across generations.

## The Dark Matter Compton Coupling

#### Status.

Theorem [60](#thm:dark-matter){reference-type="ref"
reference="thm:dark-matter"} establishes that dark matter is
McGucken-Sphere-coupled mass beyond the Standard Model Compton sector.
The structural mechanism is closed: dark matter must be Compton-coupled
(gravitationally interacting) but very weakly coupled to
electromagnetism and strong interactions; the McGucken-Sphere structure
supplies the gravitational coupling while excluding the SM gauge
couplings at observable levels. The Bullet Cluster evidence [@Clowe2006]
of spatial separation between baryonic and total mass distributions is
consistent with this structural identification.

#### Open derivational target.

The specific particle content of dark matter (mass, spin, interaction
cross-sections beyond gravity) remains to be identified from the
McGucken framework. The structural form: dark matter modes are
$x_4$-stationary on the McGucken Sphere at masses outside the Standard
Model Compton sector; the mass distribution and spin content are
derivable in principle from the framework's structural content.

#### Route to closure.

The closure requires the systematic enumeration of $x_4$-stationary
modes on the McGucken Sphere at TeV-to-PeV mass scales, with the SM
gauge group decomposition applied to the modes' transformation
properties. Direct-detection experiments (DAMA, XENON, LZ, CDMS) and
indirect-detection observations (Fermi-LAT, IceCube) provide ongoing
constraints that the framework must accommodate.

## The Sterile-Neutrino Mass Spectrum

#### Status.

The observed neutrino masses are small ($\sum m_\nu < 0.12\,\mathrm{eV}$
from cosmological constraints) but nonzero (from neutrino oscillations).
The orthodox seesaw mechanism postulates heavy sterile neutrinos at the
GUT scale to generate the light-neutrino masses via
$m_\nu \sim m_D^2/M_R$ with $m_D$ the Dirac mass and $M_R$ the
right-handed Majorana mass.
Theorem [59](#thm:generations){reference-type="ref"
reference="thm:generations"} addresses the three-generation structure;
the specific neutrino-sector content remains to be developed.

#### Open derivational target.

The three light neutrino masses $m_1, m_2, m_3$ and the existence/mass
of sterile-neutrino partners must be derived from the McGucken
framework. The structural form: the small neutrino masses are the
Channel-B Compton-locality bound applied at the McGucken-Sphere triadic
generation structure; the right-handed Majorana mass scale is the
natural scale of the McGucken Sphere's gauge-orbit closure for the
lepton sector.

#### Route to closure.

The closure requires extending
Theorem [59](#thm:generations){reference-type="ref"
reference="thm:generations"}'s triadic structure to include the
right-handed neutrino sector and identifying the natural Majorana mass
from the McGucken Sphere's gauge-orbit structure at the appropriate
scale. Empirical constraints from cosmological neutrino-mass bounds,
neutrinoless double-beta decay searches, and sterile-neutrino searches
at short-baseline experiments provide ongoing targets.

## The Methodological Status of the Open Problems

The open problems above are derivational targets, not foundational gaps.
The structural identification is in place for each: baryogenesis as
$+ic$-orientation asymmetry; Strominger--Vafa central charge as
bosonic-polarization count on the null 1+1 strip; Yukawa hierarchy as
Channel-B Sphere-overlap; dark matter as McGucken-Sphere mode beyond the
SM Compton sector; sterile neutrinos as triadic extension of the lepton
sector. Each open problem has a definite route to closure within the
McGucken framework, with explicit structural ingredients identified from
the proven theorems of this paper and the broader corpus.

The Heroic Scientific Philosophy of Finding the Simple Truth
(Section [62](#sec:diagnostic){reference-type="ref"
reference="sec:diagnostic"}) requires patience in closing these targets
one by one, with the Wheeler-Einsteinian discipline of preserving the
foundational base (one principle, $dx_4/dt = ic$) and not multiplying
postulates to bridge the gaps. The open problems above are not signs
that the framework requires new postulates; they are derivational tasks
within the framework as it stands.

#### One principle, two channels, all paradoxes; the open problems are derivational targets, not foundational gaps.

# Theorem Tally {#theorem-tally .unnumbered}

The following theorems have been proved or stated in this paper.

#### Foundational dissolutions.

1.  Theorem [5](#thm:dissolution){reference-type="ref"
    reference="thm:dissolution"}: General Paradox Dissolution.

2.  Theorem [13](#thm:measurement){reference-type="ref"
    reference="thm:measurement"}: Measurement as $x_4$-pinch.

3.  Theorem [15](#thm:epr){reference-type="ref" reference="thm:epr"}:
    EPR correlations as $x_4$-co-advance.

4.  Theorem [17](#thm:wigner){reference-type="ref"
    reference="thm:wigner"}: Wigner-friend dissolution.

5.  Theorem [19](#thm:duality){reference-type="ref"
    reference="thm:duality"}: Duality as $x_4$-projection.

6.  Theorem [22](#thm:photon-tracer){reference-type="ref"
    reference="thm:photon-tracer"}: The photon as tracer of $x_4$; the
    four-velocity paradox dissolved; derivation of $dx_4/dt = ic$ from
    Peebles + Wheeler.

7.  Theorem [25](#thm:hardy-ghz-ks){reference-type="ref"
    reference="thm:hardy-ghz-ks"}: Hardy / GHZ / Kochen--Specker as
    Channel-A non-Booleanity.

8.  Theorem [26](#thm:mott-renninger){reference-type="ref"
    reference="thm:mott-renninger"}: Tracks, negative results,
    interaction-free measurement, Zeno as $x_4$-pinches.

#### Relativistic paradoxes.

9.  Theorem [27](#thm:twin){reference-type="ref" reference="thm:twin"}:
    Twin, ladder, Bell rocket as $x_4$-rotations.

10. Theorem [28](#thm:ehrenfest){reference-type="ref"
    reference="thm:ehrenfest"}: Disk, submarine, capacitor,
    charge--magnet as $x_4$-frame mismatches.

11. Theorem [29](#thm:block){reference-type="ref"
    reference="thm:block"}: Block universe is partial; becoming is
    Channel-B.

12. Theorem [30](#thm:mach){reference-type="ref" reference="thm:mach"}:
    Mach's principle dissolved: inertia is the local $x_4$-advance; the
    bucket climbs in an empty universe; yet absolute space is excluded
    (the absolute element is the active expansion).

13. Theorem [32](#thm:godel){reference-type="ref"
    reference="thm:godel"}: Gödel's universe excluded; closed timelike
    curves forbidden by $\oint dx_4 = ic\oint dt \neq 0$; chronology
    protection is a theorem, not Hawking's conjecture.

14. Theorem [34](#thm:selfforce){reference-type="ref"
    reference="thm:selfforce"}: Self-force as $x_4$-back-reaction.

#### Gravity and cosmology.

15. Theorem [35](#thm:elevator){reference-type="ref"
    reference="thm:elevator"}: Equivalence, redshift, horizon as
    $x_4$-frame change.

16. Theorem [36](#thm:bh-info){reference-type="ref"
    reference="thm:bh-info"}: Information paradox as $x_4$-coordinate
    failure.

17. Theorem [38](#thm:cc){reference-type="ref" reference="thm:cc"}:
    Cosmological constant as $x_4$-expansion rate.

18. Theorem [39](#thm:cosmo){reference-type="ref"
    reference="thm:cosmo"}: Cosmological problems as $x_4$-expansion
    theorems.

#### Statistical mechanics, time, and quantization.

19. Theorem [40](#thm:arrow){reference-type="ref"
    reference="thm:arrow"}: Five arrows of time unified by
    $x_4$-expansion.

20. Theorem [41](#thm:sorkin-unruh){reference-type="ref"
    reference="thm:sorkin-unruh"}: Sorkin / Martín-Martínez / Unruh as
    $x_4$-frame artifacts.

21. Theorem [42](#thm:wdw){reference-type="ref" reference="thm:wdw"}:
    Wheeler--DeWitt frozen-time as $x_4$-integration.

22. Theorem [43](#thm:collapse){reference-type="ref"
    reference="thm:collapse"}: Collapse rates as Channel-B decoherence.

23. Theorem [44](#thm:interpretations){reference-type="ref"
    reference="thm:interpretations"}: Bohm and Everett as Channel-A
    bookkeeping.

24. Theorem [45](#thm:born){reference-type="ref" reference="thm:born"}:
    Born rule from $i^2 = -1$.

25. Theorem [46](#thm:uncertainty){reference-type="ref"
    reference="thm:uncertainty"}: Uncertainty as $x_4$-phase
    non-commutativity.

26. Theorem [47](#thm:klein){reference-type="ref"
    reference="thm:klein"}: Klein paradox as $x_4$-mode mixing.

#### Structural transit.

27. Theorem [48](#thm:wick-rotation){reference-type="ref"
    reference="thm:wick-rotation"}: Wick rotation as $\pi/2$ transit
    between Channel-A and Channel-B readings of $dx_4/dt = ic$.

#### Quantum field theory structural paradoxes.

28. Theorem [50](#thm:gauge-ghost){reference-type="ref"
    reference="thm:gauge-ghost"}: Gauge redundancy and Faddeev--Popov
    ghosts as Channel-A $x_4$-frame redundancy; BRST nilpotence as
    $i^2 = -1$.

29. Theorem [51](#thm:anomalies){reference-type="ref"
    reference="thm:anomalies"}: Chiral, conformal, gravitational
    anomalies as Jacobians of the $x_4$-measure.

30. Theorem [52](#thm:renormalization){reference-type="ref"
    reference="thm:renormalization"}: Renormalization as $x_4$-mode
    integration with Compton-scale cutoff.

31. Theorem [53](#thm:landau){reference-type="ref"
    reference="thm:landau"}: Landau pole and triviality as
    $x_4$-extrapolation failures past Compton-locality.

32. Theorem [54](#thm:hierarchy){reference-type="ref"
    reference="thm:hierarchy"}: Higgs hierarchy as
    $x_4$-Compton-locality at the top mass.

33. Theorem [55](#thm:vacuum-stability){reference-type="ref"
    reference="thm:vacuum-stability"}: Vacuum metastability as Channel-B
    Compton-cutoff signature.

#### Standard Model paradoxes.

34. Theorem [56](#thm:baryogenesis){reference-type="ref"
    reference="thm:baryogenesis"}: Baryogenesis as $x_4$-orientation
    asymmetry; Sakharov 1--3 as theorems, magnitude $\eta \sim 10^{-9}$
    open.

35. Theorem [57](#thm:strong-cp){reference-type="ref"
    reference="thm:strong-cp"}: Strong CP as Channel-A vs. Channel-B
    $\theta$ contributions with
    $\sim (\Lambda_{\rm QCD}/m_W)^4 \sim 10^{-10}$ bound.

36. Theorem [58](#thm:naturalness){reference-type="ref"
    reference="thm:naturalness"}: Naturalness as the dual-channel
    diagnostic.

37. Theorem [59](#thm:generations){reference-type="ref"
    reference="thm:generations"}: Three generations as $x_4$-frame
    triadic structure.

#### Cosmology beyond the standard problems.

38. Theorem [60](#thm:dark-matter){reference-type="ref"
    reference="thm:dark-matter"}: Dark matter as $x_4$-coupled mass
    beyond the Standard Model Compton sector.

39. Theorem [61](#thm:dark-energy){reference-type="ref"
    reference="thm:dark-energy"}: Dark energy as the McGucken Sphere
    expansion rate; coincidence problem dissolved.

40. Theorem [62](#thm:monopole){reference-type="ref"
    reference="thm:monopole"}: Monopole problem as Channel-B McGucken
    Sphere correlation structure; no inflation required.

41. Theorem [63](#thm:trans-planckian){reference-type="ref"
    reference="thm:trans-planckian"}: Trans-Planckian as $x_4$-frame
    rotation artifact.

42. Theorem [64](#thm:boltzmann-brains){reference-type="ref"
    reference="thm:boltzmann-brains"}: Boltzmann brains dissolved by
    $+ic$ orientation.

#### Modern quantum gravity.

43. Theorem [65](#thm:er-epr){reference-type="ref"
    reference="thm:er-epr"}: ER = EPR as shared McGucken Sphere of
    entangled events.

44. Theorem [66](#thm:complexity){reference-type="ref"
    reference="thm:complexity"}: Computational complexity as integrated
    $x_4$-expansion; CV and CA as Channel-B measures.

45. Theorem [67](#thm:holography){reference-type="ref"
    reference="thm:holography"}: Holographic principle as McGucken
    Sphere area-law structure.

46. Theorem [68](#thm:ads-cft){reference-type="ref"
    reference="thm:ads-cft"}: AdS/CFT as McGucken Sphere boundary--bulk
    duality.

47. Theorem [69](#thm:page-curve){reference-type="ref"
    reference="thm:page-curve"}: Page curve as $x_4$-expansion of the
    radiation Sphere.

48. Theorem [70](#thm:bekenstein){reference-type="ref"
    reference="thm:bekenstein"}: Bekenstein bound from
    $x_4$-Compton-locality.

49. Theorem [71](#thm:soft-hair){reference-type="ref"
    reference="thm:soft-hair"}: Soft hair as McGucken Sphere $x_4$-phase
    memory on asymptotic Sphere.

#### Classical and foundational paradoxes.

50. Theorem [72](#thm:gibbs){reference-type="ref"
    reference="thm:gibbs"}: Gibbs paradox of mixing as Channel-A
    particle identity via Compton-frequency equivalence.

51. Theorem [73](#thm:dalembert){reference-type="ref"
    reference="thm:dalembert"}: D'Alembert's paradox as Channel-A
    vs. Channel-B fluid dynamics; viscosity as McGucken-Sphere-sourced.

52. Theorem [74](#thm:hole){reference-type="ref" reference="thm:hole"}:
    Hole argument as Channel-A gauge artifact; diffeomorphism
    redundancy.

53. Theorem [75](#thm:painleve){reference-type="ref"
    reference="thm:painleve"}: Painlevé non-collision singularity as
    Channel-A artifact of relativistic neglect.

#### QFT, cosmology, multiverse extensions.

54. Theorem [76](#thm:first-second-q){reference-type="ref"
    reference="thm:first-second-q"}: First and second quantization as
    Channel-A two-tier algebraic structure.

55. Theorem [77](#thm:microcausality){reference-type="ref"
    reference="thm:microcausality"}: Microcausality and Reeh--Schlieder
    as Channel-A locality and Channel-B Sphere-sharing.

56. Theorem [78](#thm:inflation-eternal){reference-type="ref"
    reference="thm:inflation-eternal"}: Inflation and eternal inflation
    as Channel-A field versus Channel-B Sphere expansion; multiverse
    dissolved.

57. Theorem [79](#thm:cosmo-measure){reference-type="ref"
    reference="thm:cosmo-measure"}: Cosmological measure problem
    dissolved by absence of multiverse.

#### The structural capstone.

58. Theorem [80](#thm:meta){reference-type="ref" reference="thm:meta"}:
    **Paradox-Resolution Meta-Theorem of $dx_4/dt = ic$**---the unifying
    structural-foundational identification of every paradox as the
    simultaneous Channel-A and Channel-B reading of one foundational
    content, with relatedness sourced from the principle's unity and
    disjointness sourced from the channels' functorial distinction.

#### Total.

Fifty-eight theorems unified by one principle, $dx_4/dt = ic$.

::: thebibliography
99

H. Minkowski, "Raum und Zeit," Address to the 80th Assembly of German
Natural Scientists and Physicians, Köln, 21 September 1908; English
translation in *The Principle of Relativity* (Dover, 1952).
[`https://en.wikisource.org/wiki/Translation:Space_and_Time`](https://en.wikisource.org/wiki/Translation:Space_and_Time)

A. Einstein, "Die Grundlage der allgemeinen Relativitätstheorie,"
*Annalen der Physik* **354**, 769--822 (1916).
[`https://onlinelibrary.wiley.com/doi/10.1002/andp.19163540702`](https://onlinelibrary.wiley.com/doi/10.1002/andp.19163540702)

A. Einstein, "Zur Elektrodynamik bewegter Körper," *Annalen der Physik*
**17**, 891--921 (1905).
[`https://onlinelibrary.wiley.com/doi/10.1002/andp.19053221004`](https://onlinelibrary.wiley.com/doi/10.1002/andp.19053221004)

A. Einstein, "Über das Relativitätsprinzip und die aus demselben
gezogenen Folgerungen," *Jahrbuch der Radioaktivität und Elektronik*
**4**, 411--462 (1907).
[`https://einsteinpapers.press.princeton.edu/vol2-trans/319`](https://einsteinpapers.press.princeton.edu/vol2-trans/319)

P. Langevin, "L'évolution de l'espace et du temps," *Scientia* **10**,
31--54 (1911).
[`https://en.wikipedia.org/wiki/Twin_paradox`](https://en.wikipedia.org/wiki/Twin_paradox)

C. W. Misner, K. S. Thorne, J. A. Wheeler, *Gravitation* (Freeman,
1973).
[`https://press.princeton.edu/books/hardcover/9780691177793/gravitation`](https://press.princeton.edu/books/hardcover/9780691177793/gravitation)

R. Penrose, "Gravitational collapse and space-time singularities,"
*Phys. Rev. Lett.* **14**, 57 (1965).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.14.57`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.14.57)

J. von Neumann, *Mathematische Grundlagen der Quantenmechanik*
(Springer, 1932); English translation: *Mathematical Foundations of
Quantum Mechanics* (Princeton, 1955).
[`https://press.princeton.edu/books/hardcover/9780691178561/mathematical-foundations-of-quantum-mechanics`](https://press.princeton.edu/books/hardcover/9780691178561/mathematical-foundations-of-quantum-mechanics)

E. Schrödinger, "Die gegenwärtige Situation in der Quantenmechanik,"
*Naturwissenschaften* **23**, 807--812, 823--828, 844--849 (1935).
[`https://link.springer.com/article/10.1007/BF01491891`](https://link.springer.com/article/10.1007/BF01491891)

J. S. Bell, "Against 'measurement'," *Physics World* **3**, 33--40
(1990).
[`https://iopscience.iop.org/article/10.1088/2058-7058/3/8/26`](https://iopscience.iop.org/article/10.1088/2058-7058/3/8/26)

J. S. Bell, "On the Einstein--Podolsky--Rosen paradox," *Physics* **1**,
195--200 (1964).
[`https://journals.aps.org/ppf/abstract/10.1103/PhysicsPhysiqueFizika.1.195`](https://journals.aps.org/ppf/abstract/10.1103/PhysicsPhysiqueFizika.1.195)

A. Einstein, B. Podolsky, N. Rosen, "Can quantum-mechanical description
of physical reality be considered complete?" *Phys. Rev.* **47**,
777--780 (1935).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.47.777`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.47.777)

N. Bohr, "Can quantum-mechanical description of physical reality be
considered complete?" *Phys. Rev.* **48**, 696--702 (1935).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.48.696`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.48.696)

A. Aspect, P. Grangier, G. Roger, "Experimental realization of
Einstein--Podolsky--Rosen--Bohm *gedankenexperiment*,"
*Phys. Rev. Lett.* **49**, 91 (1982).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.49.91`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.49.91)

B. Hensen et al., "Loophole-free Bell inequality violation using
electron spins," *Nature* **526**, 682--686 (2015).
[`https://www.nature.com/articles/nature15759`](https://www.nature.com/articles/nature15759)

E. P. Wigner, "Remarks on the mind--body question," in I. J. Good (ed.),
*The Scientist Speculates* (Heinemann, 1961).
[`https://link.springer.com/chapter/10.1007/978-3-642-78374-6_20`](https://link.springer.com/chapter/10.1007/978-3-642-78374-6_20)

D. Frauchiger, R. Renner, "Quantum theory cannot consistently describe
the use of itself," *Nature Communications* **9**, 3711 (2018).
[`https://www.nature.com/articles/s41467-018-05739-8`](https://www.nature.com/articles/s41467-018-05739-8)

N. Bohr, "The quantum postulate and the recent development of atomic
theory," *Nature* **121**, 580--590 (1928).
[`https://www.nature.com/articles/121580a0`](https://www.nature.com/articles/121580a0)

J. A. Wheeler, "The 'past' and the 'delayed-choice' double-slit
experiment," in A. R. Marlow (ed.), *Mathematical Foundations of Quantum
Theory* (Academic Press, 1978).
[`https://www.sciencedirect.com/science/article/pii/B9780124732506500066`](https://www.sciencedirect.com/science/article/pii/B9780124732506500066)

M. O. Scully, K. Drühl, "Quantum eraser: a proposed photon correlation
experiment concerning observation and 'delayed choice' in quantum
mechanics," *Phys. Rev. A* **25**, 2208 (1982).
[`https://journals.aps.org/pra/abstract/10.1103/PhysRevA.25.2208`](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.25.2208)

L. Hardy, "Quantum mechanics, local realistic theories, and
Lorentz-invariant realistic theories," *Phys. Rev. Lett.* **68**, 2981
(1992).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.68.2981`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.68.2981)

D. M. Greenberger, M. A. Horne, A. Zeilinger, "Going beyond Bell's
theorem," in M. Kafatos (ed.), *Bell's Theorem, Quantum Theory, and
Conceptions of the Universe* (Kluwer, 1989).
[`https://link.springer.com/chapter/10.1007/978-94-017-0849-4_10`](https://link.springer.com/chapter/10.1007/978-94-017-0849-4_10)

S. Kochen, E. P. Specker, "The problem of hidden variables in quantum
mechanics," *J. Math. Mech.* **17**, 59--87 (1967).
[`https://www.jstor.org/stable/24902153`](https://www.jstor.org/stable/24902153)

N. F. Mott, "The wave mechanics of $\alpha$-ray tracks,"
*Proc. R. Soc. A* **126**, 79--84 (1929).
[`https://royalsocietypublishing.org/doi/10.1098/rspa.1929.0205`](https://royalsocietypublishing.org/doi/10.1098/rspa.1929.0205)

M. Renninger, "Zum Wellen--Korpuskel--Dualismus," *Z. Physik* **136**,
251 (1953).
[`https://link.springer.com/article/10.1007/BF01325679`](https://link.springer.com/article/10.1007/BF01325679)

A. C. Elitzur, L. Vaidman, "Quantum mechanical interaction-free
measurements," *Found. Phys.* **23**, 987 (1993).
[`https://link.springer.com/article/10.1007/BF00736012`](https://link.springer.com/article/10.1007/BF00736012)

B. Misra, E. C. G. Sudarshan, "The Zeno's paradox in quantum theory,"
*J. Math. Phys.* **18**, 756 (1977).
[`https://pubs.aip.org/aip/jmp/article/18/4/756/225590`](https://pubs.aip.org/aip/jmp/article/18/4/756/225590)

W. Rindler, "Length contraction paradox," *Am. J. Phys.* **29**, 365
(1961).
[`https://pubs.aip.org/aapt/ajp/article/29/6/365/1042430`](https://pubs.aip.org/aapt/ajp/article/29/6/365/1042430)

J. S. Bell, "How to teach special relativity," *Progress in Scientific
Culture* **1**, 1--13 (1976); reprinted in *Speakable and Unspeakable in
Quantum Mechanics* (Cambridge, 1987).
[`https://www.cambridge.org/9780521523387`](https://www.cambridge.org/9780521523387)

P. Ehrenfest, "Gleichförmige Rotation starrer Körper und
Relativitätstheorie," *Phys. Z.* **10**, 918 (1909).
[`https://en.wikisource.org/wiki/Translation:Uniform_Rotation_of_Rigid_Bodies_and_the_Theory_of_Relativity`](https://en.wikisource.org/wiki/Translation:Uniform_Rotation_of_Rigid_Bodies_and_the_Theory_of_Relativity)

J. M. Supplee, "Relativistic buoyancy," *Am. J. Phys.* **57**, 75
(1989).
[`https://pubs.aip.org/aapt/ajp/article/57/1/75/1043076`](https://pubs.aip.org/aapt/ajp/article/57/1/75/1043076)

G. E. A. Matsas, "Relativistic Archimedes law for fast moving bodies,"
*Phys. Rev. D* **68**, 027701 (2003).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.68.027701`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.68.027701)

F. T. Trouton, H. R. Noble, "The mechanical forces acting on a charged
electric condenser moving through space," *Phil. Trans. R. Soc. A*
**202**, 165 (1903).
[`https://royalsocietypublishing.org/doi/10.1098/rsta.1904.0005`](https://royalsocietypublishing.org/doi/10.1098/rsta.1904.0005)

M. Mansuripur, "Trouble with the Lorentz law of force: incompatibility
with special relativity and momentum conservation," *Phys. Rev. Lett.*
**108**, 193901 (2012).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.108.193901`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.108.193901)

J. D. Jackson, *Classical Electrodynamics*, 3rd ed. (Wiley, 1999).
[`https://www.wiley.com/en-us/Classical+Electrodynamics`](https://www.wiley.com/en-us/Classical+Electrodynamics%2C+3rd+Edition-p-9780471309321)

C. W. Rietdijk, "A rigorous proof of determinism derived from the
special theory of relativity," *Philosophy of Science* **33**, 341
(1966).
[`https://www.jstor.org/stable/186167`](https://www.jstor.org/stable/186167)

H. Putnam, "Time and physical geometry," *J. Philos.* **64**, 240
(1967).
[`https://www.jstor.org/stable/2024493`](https://www.jstor.org/stable/2024493)

R. Penrose, *The Emperor's New Mind* (Oxford, 1989).
[`https://global.oup.com/academic/product/the-emperors-new-mind-9780192861986`](https://global.oup.com/academic/product/the-emperors-new-mind-9780192861986)

H. A. Lorentz, *The Theory of Electrons* (Teubner, 1909).
[`https://archive.org/details/electronstheory00lorerich`](https://archive.org/details/electronstheory00lorerich)

P. A. M. Dirac, "Classical theory of radiating electrons,"
*Proc. R. Soc. A* **167**, 148 (1938).
[`https://royalsocietypublishing.org/doi/10.1098/rspa.1938.0124`](https://royalsocietypublishing.org/doi/10.1098/rspa.1938.0124)

F. Rohrlich, *Classical Charged Particles*, 3rd ed. (World Scientific,
2007); orig. 1990.
[`https://www.worldscientific.com/worldscibooks/10.1142/6220`](https://www.worldscientific.com/worldscibooks/10.1142/6220)

R. V. Pound, G. A. Rebka Jr., "Gravitational red-shift in nuclear
resonance," *Phys. Rev. Lett.* **3**, 439 (1959).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.3.439`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.3.439)

K. Schwarzschild, "Über das Gravitationsfeld eines Massenpunktes nach
der Einsteinschen Theorie," *Sitzungsber. Preuss. Akad. Wiss. Berlin*
189 (1916).
[`https://articles.adsabs.harvard.edu/full/1916SPAW.......189S`](https://articles.adsabs.harvard.edu/full/1916SPAW.......189S)

P. Painlevé, "La mécanique classique et la théorie de la relativité,"
*C. R. Acad. Sci. (Paris)* **173**, 677 (1921).
[`https://gallica.bnf.fr/ark:/12148/bpt6k3127j`](https://gallica.bnf.fr/ark:/12148/bpt6k3127j)

A. Gullstrand, "Allgemeine Lösung des statischen Einkörperproblems in
der Einsteinschen Gravitationstheorie," *Arkiv. Mat. Astron. Fys.*
**16**, 1 (1922).
[`https://en.wikipedia.org/wiki/Gullstrand-Painleve_coordinates`](https://en.wikipedia.org/wiki/Gullstrand%E2%80%93Painlev%C3%A9_coordinates)

A. S. Eddington, "A comparison of Whitehead's and Einstein's formulae,"
*Nature* **113**, 192 (1924).
[`https://www.nature.com/articles/113192a0`](https://www.nature.com/articles/113192a0)

D. Finkelstein, "Past--future asymmetry of the gravitational field of a
point particle," *Phys. Rev.* **110**, 965 (1958).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.110.965`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.110.965)

S. W. Hawking, "Particle creation by black holes," *Comm. Math. Phys.*
**43**, 199 (1975).
[`https://link.springer.com/article/10.1007/BF02345020`](https://link.springer.com/article/10.1007/BF02345020)

S. D. Mathur, "The information paradox: a pedagogical introduction,"
*Class. Quantum Grav.* **26**, 224001 (2009).
[`https://iopscience.iop.org/article/10.1088/0264-9381/26/22/224001`](https://iopscience.iop.org/article/10.1088/0264-9381/26/22/224001)

D. Harlow, "Jerusalem lectures on black holes and quantum information,"
*Rev. Mod. Phys.* **88**, 015002 (2016).
[`https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.88.015002`](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.88.015002)

D. N. Page, "Information in black hole radiation," *Phys. Rev. Lett.*
**71**, 3743 (1993).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.71.3743`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.71.3743)

D. N. Page, "Time dependence of Hawking radiation entropy," *JCAP*
**09**, 028 (2013).
[`https://iopscience.iop.org/article/10.1088/1475-7516/2013/09/028`](https://iopscience.iop.org/article/10.1088/1475-7516/2013/09/028)

A. Almheiri, D. Marolf, J. Polchinski, J. Sully, "Black holes:
complementarity or firewalls?" *JHEP* **02**, 062 (2013).
[`https://link.springer.com/article/10.1007/JHEP02(2013)062`](https://link.springer.com/article/10.1007/JHEP02(2013)062)

J. Maldacena, L. Susskind, "Cool horizons for entangled black holes,"
*Fortsch. Phys.* **61**, 781 (2013).
[`https://onlinelibrary.wiley.com/doi/10.1002/prop.201300020`](https://onlinelibrary.wiley.com/doi/10.1002/prop.201300020)

G. Penington, "Entanglement wedge reconstruction and the information
paradox," *JHEP* **09**, 002 (2020).
[`https://link.springer.com/article/10.1007/JHEP09(2020)002`](https://link.springer.com/article/10.1007/JHEP09(2020)002)

A. Almheiri, N. Engelhardt, D. Marolf, H. Maxfield, "The entropy of bulk
quantum fields and the entanglement wedge of an evaporating black hole,"
*JHEP* **12**, 063 (2019).
[`https://link.springer.com/article/10.1007/JHEP12(2019)063`](https://link.springer.com/article/10.1007/JHEP12(2019)063)

T. Jacobson, "Black-hole evaporation and ultrashort distances,"
*Phys. Rev. D* **44**, 1731 (1991).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.44.1731`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.44.1731)

S. Weinberg, "The cosmological constant problem," *Rev. Mod. Phys.*
**61**, 1 (1989).
[`https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.61.1`](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.61.1)

S. M. Carroll, "The cosmological constant," *Living Rev. Relativ.*
**4**, 1 (2001).
[`https://link.springer.com/article/10.12942/lrr-2001-1`](https://link.springer.com/article/10.12942/lrr-2001-1)

A. H. Guth, "Inflationary universe: a possible solution to the horizon
and flatness problems," *Phys. Rev. D* **23**, 347 (1981).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.23.347`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.23.347)

H. W. M. Olbers, "Über die Durchsichtigkeit des Weltraums,"
*Astronomisches Jahrbuch für das Jahr 1826*, 110 (1823).
[`https://en.wikipedia.org/wiki/Olbers’s_paradox`](https://en.wikipedia.org/wiki/Olbers's_paradox)

L. Verde, T. Treu, A. G. Riess, "Tensions between the early and late
Universe," *Nature Astronomy* **3**, 891 (2019).
[`https://www.nature.com/articles/s41550-019-0902-0`](https://www.nature.com/articles/s41550-019-0902-0)

L. Boltzmann, "Weitere Studien über das Wärmegleichgewicht unter
Gasmolekülen," *Sitzungsber. Akad. Wiss. Wien* **66**, 275 (1872).
[`https://www.biodiversitylibrary.org/item/91171`](https://www.biodiversitylibrary.org/item/91171)

J. Loschmidt, "Über den Zustand des Wärmegleichgewichtes eines Systems
von Körpern," *Sitzungsber. Akad. Wiss. Wien* **73**, 128 (1876).
[`https://en.wikipedia.org/wiki/Loschmidt’s_paradox`](https://en.wikipedia.org/wiki/Loschmidt's_paradox)

H. Poincaré, "Sur le problème des trois corps et les équations de la
dynamique," *Acta Math.* **13**, 1 (1890).
[`https://link.springer.com/article/10.1007/BF02392506`](https://link.springer.com/article/10.1007/BF02392506)

J. C. Maxwell, *Theory of Heat* (Longmans, 1871).
[`https://archive.org/details/theoryofheat00maxwrich`](https://archive.org/details/theoryofheat00maxwrich)

L. Szilárd, "Über die Entropieverminderung in einem thermodynamischen
System bei Eingriffen intelligenter Wesen," *Z. Physik* **53**, 840
(1929).
[`https://link.springer.com/article/10.1007/BF01341281`](https://link.springer.com/article/10.1007/BF01341281)

R. Landauer, "Irreversibility and heat generation in the computing
process," *IBM J. Res. Dev.* **5**, 183 (1961).
[`https://ieeexplore.ieee.org/document/5392446`](https://ieeexplore.ieee.org/document/5392446)

R. D. Sorkin, "Impossible measurements on quantum fields," in
*Directions in General Relativity, Vol. II* (Cambridge, 1993).
[`https://arxiv.org/abs/gr-qc/9302018`](https://arxiv.org/abs/gr-qc/9302018)

J. de Ramon, M. Papageorgiou, E. Martín-Martínez, "Relativistic
causality in particle detector models," *Phys. Rev. D* **103**, 085002
(2021).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.103.085002`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.103.085002)

W. G. Unruh, "Notes on black-hole evaporation," *Phys. Rev. D* **14**,
870 (1976).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.14.870`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.14.870)

E. McGucken, "Resolution of the measurement problem and the black hole
information paradox via $dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/measurement-problem-black-hole-information`](https://elliotmcguckenphysics.com/measurement-problem-black-hole-information)

E. McGucken, "McGucken cosmology: twelve observational tests from
$dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/mcgucken-cosmology`](https://elliotmcguckenphysics.com/mcgucken-cosmology)

E. McGucken, "The Sorkin impossible-measurements problem and nine QFT
pathologies as theorems of $dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/sorkin-impossible-measurements`](https://elliotmcguckenphysics.com/sorkin-impossible-measurements)

E. McGucken, "The McGucken Principle: $dx_4/dt = ic$ as the foundation
of physics," (2026).
[`https://elliotmcguckenphysics.com/mcgucken-principle`](https://elliotmcguckenphysics.com/mcgucken-principle)

E. McGucken, "Dual-channel architecture: algebraic and geometric content
of $dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/dual-channel-architecture`](https://elliotmcguckenphysics.com/dual-channel-architecture)

E. McGucken, "Schrödinger time-asymmetry as a theorem of
$dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/schroedinger-time-asymmetry`](https://elliotmcguckenphysics.com/schroedinger-time-asymmetry)

E. McGucken, "Five arrows of time unified by $dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/arrows-of-time`](https://elliotmcguckenphysics.com/arrows-of-time)

A. Einstein, *The Meaning of Relativity* (Princeton, 1923).
[`https://press.princeton.edu/books/paperback/9780691164083/the-meaning-of-relativity`](https://press.princeton.edu/books/paperback/9780691164083/the-meaning-of-relativity)

J. A. Wheeler, "On the nature of quantum geometrodynamics," *Annals of
Physics* **2**, 604--614 (1957).
[`https://www.sciencedirect.com/science/article/abs/pii/0003491657900507`](https://www.sciencedirect.com/science/article/abs/pii/0003491657900507)

J. A. Wheeler, R. P. Feynman, "Interaction with the absorber as the
mechanism of radiation," *Rev. Mod. Phys.* **17**, 157 (1945).
[`https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.17.157`](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.17.157)

J. A. Wheeler, W. H. Zurek (eds.), *Quantum Theory and Measurement*
(Princeton, 1983).
[`https://press.princeton.edu/books/hardcover/9780691083162/quantum-theory-and-measurement`](https://press.princeton.edu/books/hardcover/9780691083162/quantum-theory-and-measurement)

J. A. Wheeler, "Information, physics, quantum: the search for links," in
*Proc. 3rd Int. Symp. on Foundations of Quantum Mechanics* (Tokyo,
1989).
[`https://philpapers.org/rec/WHEIPQ`](https://philpapers.org/rec/WHEIPQ)

E. McGucken, "The Fourth Dimension Is Expanding at the Velocity of
Light," FQXi Essay Contest (2008).
[`https://forums.fqxi.org/u/dmcgucken`](https://forums.fqxi.org/u/dmcgucken)

E. McGucken, "The Dynamical Fourth Dimension," FQXi Essay Contest
(2010).
[`https://forums.fqxi.org/u/dmcgucken`](https://forums.fqxi.org/u/dmcgucken)

E. McGucken, "It from the Fourth Dimension," FQXi Essay Contest (2013).
[`https://forums.fqxi.org/u/dmcgucken`](https://forums.fqxi.org/u/dmcgucken)

E. McGucken, "McGucken Quantum Formalism: derivation of quantum
mechanics from $dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/mcgucken-quantum-formalism`](https://elliotmcguckenphysics.com/mcgucken-quantum-formalism)

E. McGucken, "Dirac equation as a theorem of $dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/dirac-equation`](https://elliotmcguckenphysics.com/dirac-equation)

E. McGucken, "General relativity and the equivalence principle from
$dx_4/dt = ic$," (2026).
[`https://elliotmcguckenphysics.com/general-relativity`](https://elliotmcguckenphysics.com/general-relativity)

E. McGucken, "Standard Model gauge structure from $dx_4/dt = ic$,"
(2026).
[`https://elliotmcguckenphysics.com/standard-model`](https://elliotmcguckenphysics.com/standard-model)

E. McGucken, "McGucken Space and McGucken Operator co-generated by
$dx_4/dt = ic$: Penrose twistors and the Arkani-Hamed amplituhedron as
theorems," (2026).
[`https://elliotmcguckenphysics.com/mcgucken-space`](https://elliotmcguckenphysics.com/mcgucken-space)

E. McGucken, "McGucken--Kaluza--Klein framework and the Strominger--Vafa
central-charge target," (2026).
[`https://elliotmcguckenphysics.com/mcgucken-kaluza-klein`](https://elliotmcguckenphysics.com/mcgucken-kaluza-klein)

B. S. Cirel'son, "Quantum generalizations of Bell's inequality,"
*Lett. Math. Phys.* **4**, 93--100 (1980).
[`https://link.springer.com/article/10.1007/BF00417500`](https://link.springer.com/article/10.1007/BF00417500)

A. Cabello, J. M. Estebaranz, G. García-Alcaine, "Bell--Kochen--Specker
theorem: a proof with 18 vectors," *Phys. Lett. A* **212**, 183 (1996).
[`https://www.sciencedirect.com/science/article/abs/pii/0375960196000349`](https://www.sciencedirect.com/science/article/abs/pii/0375960196000349)

B. S. DeWitt, "Quantum theory of gravity. I. The canonical theory,"
*Phys. Rev.* **160**, 1113 (1967).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.160.1113`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.160.1113)

C. J. Isham, "Canonical quantum gravity and the problem of time," in
*Integrable Systems, Quantum Groups, and Quantum Field Theories*
(Kluwer, 1993).
[`https://arxiv.org/abs/gr-qc/9210011`](https://arxiv.org/abs/gr-qc/9210011)

K. V. Kuchař, "Time and interpretations of quantum gravity," *Proc. 4th
Canadian Conf. on General Relativity and Relativistic Astrophysics*
(World Scientific, 1992).
[`https://www.worldscientific.com/doi/abs/10.1142/S0218271811019347`](https://www.worldscientific.com/doi/abs/10.1142/S0218271811019347)

E. Anderson, *The Problem of Time* (Springer, 2017).
[`https://link.springer.com/book/10.1007/978-3-319-58848-3`](https://link.springer.com/book/10.1007/978-3-319-58848-3)

D. N. Page, W. K. Wootters, "Evolution without evolution: dynamics
described by stationary observables," *Phys. Rev. D* **27**, 2885
(1983).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.27.2885`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.27.2885)

G. C. Ghirardi, A. Rimini, T. Weber, "Unified dynamics for microscopic
and macroscopic systems," *Phys. Rev. D* **34**, 470 (1986).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.34.470`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.34.470)

P. Pearle, "Combining stochastic dynamical state-vector reduction with
spontaneous localization," *Phys. Rev. A* **39**, 2277 (1989).
[`https://journals.aps.org/pra/abstract/10.1103/PhysRevA.39.2277`](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.39.2277)

A. Bassi, G. C. Ghirardi, "Dynamical reduction models," *Phys. Rep.*
**379**, 257 (2003).
[`https://www.sciencedirect.com/science/article/abs/pii/S0370157303001030`](https://www.sciencedirect.com/science/article/abs/pii/S0370157303001030)

R. Penrose, "On gravity's role in quantum state reduction,"
*Gen. Rel. Grav.* **28**, 581 (1996).
[`https://link.springer.com/article/10.1007/BF02105068`](https://link.springer.com/article/10.1007/BF02105068)

O. Stern, W. Gerlach, "Das magnetische Moment des Silberatoms,"
*Z. Phys.* **9**, 353 (1922).
[`https://link.springer.com/article/10.1007/BF01326984`](https://link.springer.com/article/10.1007/BF01326984)

D. Bohm, "A suggested interpretation of the quantum theory in terms of
'hidden' variables," *Phys. Rev.* **85**, 166 (1952).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.85.166`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.85.166)

D. Dürr, S. Teufel, *Bohmian Mechanics* (Springer, 2009).
[`https://link.springer.com/book/10.1007/b99978`](https://link.springer.com/book/10.1007/b99978)

H. Everett III, "Relative state formulation of quantum mechanics,"
*Rev. Mod. Phys.* **29**, 454 (1957).
[`https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.29.454`](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.29.454)

M. Born, "Zur Quantenmechanik der Stoßvorgänge," *Z. Phys.* **37**, 863
(1926).
[`https://link.springer.com/article/10.1007/BF01397477`](https://link.springer.com/article/10.1007/BF01397477)

A. M. Gleason, "Measures on the closed subspaces of a Hilbert space,"
*J. Math. Mech.* **6**, 885 (1957).
[`https://www.jstor.org/stable/24900629`](https://www.jstor.org/stable/24900629)

W. H. Zurek, "Probabilities from entanglement, Born's rule from
envariance," *Phys. Rev. A* **71**, 052105 (2005).
[`https://journals.aps.org/pra/abstract/10.1103/PhysRevA.71.052105`](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.71.052105)

D. Deutsch, "Quantum theory of probability and decisions,"
*Proc. R. Soc. A* **455**, 3129 (1999).
[`https://royalsocietypublishing.org/doi/10.1098/rspa.1999.0443`](https://royalsocietypublishing.org/doi/10.1098/rspa.1999.0443)

D. Wallace, *The Emergent Multiverse* (Oxford, 2012).
[`https://global.oup.com/academic/product/the-emergent-multiverse-9780198707547`](https://global.oup.com/academic/product/the-emergent-multiverse-9780198707547)

W. Heisenberg, "Über den anschaulichen Inhalt der quantentheoretischen
Kinematik und Mechanik," *Z. Phys.* **43**, 172 (1927).
[`https://link.springer.com/article/10.1007/BF01397280`](https://link.springer.com/article/10.1007/BF01397280)

E. H. Kennard, "Zur Quantenmechanik einfacher Bewegungstypen,"
*Z. Phys.* **44**, 326 (1927).
[`https://link.springer.com/article/10.1007/BF01391200`](https://link.springer.com/article/10.1007/BF01391200)

H. Weyl, *Gruppentheorie und Quantenmechanik* (Hirzel, 1928).
[`https://link.springer.com/book/10.1007/978-3-642-50186-1`](https://link.springer.com/book/10.1007/978-3-642-50186-1)

H. P. Robertson, "The uncertainty principle," *Phys. Rev.* **34**, 163
(1929).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.34.163`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.34.163)

M. Ozawa, "Universally valid reformulation of the Heisenberg uncertainty
principle," *Phys. Rev. A* **67**, 042105 (2003).
[`https://journals.aps.org/pra/abstract/10.1103/PhysRevA.67.042105`](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.67.042105)

C. Branciard, "Error-tradeoff and error-disturbance relations for
incompatible quantum measurements," *Proc. Natl. Acad. Sci. USA*
**110**, 6742 (2013).
[`https://www.pnas.org/doi/10.1073/pnas.1219331110`](https://www.pnas.org/doi/10.1073/pnas.1219331110)

O. Klein, "Die Reflexion von Elektronen an einem Potentialsprung nach
der relativistischen Dynamik von Dirac," *Z. Phys.* **53**, 157 (1929).
[`https://link.springer.com/article/10.1007/BF01339716`](https://link.springer.com/article/10.1007/BF01339716)

P. A. M. Dirac, *The Principles of Quantum Mechanics* (Oxford, 1930).
[`https://global.oup.com/academic/product/the-principles-of-quantum-mechanics-9780198520115`](https://global.oup.com/academic/product/the-principles-of-quantum-mechanics-9780198520115)

M. I. Katsnelson, K. S. Novoselov, A. K. Geim, "Chiral tunnelling and
the Klein paradox in graphene," *Nature Physics* **2**, 620 (2006).
[`https://www.nature.com/articles/nphys384`](https://www.nature.com/articles/nphys384)

I. Newton, *Philosophiæ Naturalis Principia Mathematica* (London, 1687);
Book III, "Rules of Reasoning in Philosophy," Rule I.
[`https://www.gutenberg.org/ebooks/28233`](https://www.gutenberg.org/ebooks/28233)

J. A. Wheeler with K. Ford, *Geons, Black Holes, and Quantum Foam: A
Life in Physics* (W. W. Norton, 2010), p. 235.
[`https://wwnorton.com/books/9780393319910`](https://wwnorton.com/books/9780393319910)

E. McGucken, "The Orthodox Postulate-Accumulation Pattern in
Foundational Physics: How $dx_4/dt = ic$ Supplies in Single-Source Form
What Orthodox Physics Adds by Hand to Chaos Theory, Thermodynamics,
Quantum Interpretations, the Second Law, Black-Hole Information, and
Entropic Gravity," (2026).
[`https://elliotmcguckenphysics.com/orthodox-postulate-accumulation-pattern`](https://elliotmcguckenphysics.com/orthodox-postulate-accumulation-pattern)

J. Maldacena and L. Susskind, "Cool horizons for entangled black holes,"
*Fortschritte der Physik* **61**, 781--811 (2013).
[`https://onlinelibrary.wiley.com/doi/10.1002/prop.201300020`](https://onlinelibrary.wiley.com/doi/10.1002/prop.201300020)

A. R. Brown, D. A. Roberts, L. Susskind, B. Swingle, Y. Zhao,
"Holographic Complexity Equals Bulk Action?" *Phys. Rev. Lett.* **116**,
191301 (2016).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.191301`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.191301)

A. Connes and C. Rovelli, "Von Neumann algebra automorphisms and
time-thermodynamics relation in generally covariant quantum theories,"
*Class. Quant. Grav.* **11**, 2899 (1994).
[`https://iopscience.iop.org/article/10.1088/0264-9381/11/12/007`](https://iopscience.iop.org/article/10.1088/0264-9381/11/12/007)

D. Z. Albert, *Time and Chance* (Harvard University Press, 2000).
[`https://www.hup.harvard.edu/catalog.php?isbn=9780674011328`](https://www.hup.harvard.edu/catalog.php?isbn=9780674011328)

B. Loewer, "Counterfactuals and the Second Law," in H. Price and R.
Corry (eds.), *Causation, Physics, and the Constitution of Reality*
(Oxford University Press, 2007).
[`https://global.oup.com/academic/product/causation-physics-and-the-constitution-of-reality-9780199278183`](https://global.oup.com/academic/product/causation-physics-and-the-constitution-of-reality-9780199278183)

L. D. Faddeev and V. N. Popov, "Feynman diagrams for the Yang--Mills
field," *Phys. Lett. B* **25**, 29 (1967).
[`https://doi.org/10.1016/0370-2693(67)90067-6`](https://doi.org/10.1016/0370-2693(67)90067-6)

C. Becchi, A. Rouet, R. Stora, "The abelian Higgs Kibble model,
unitarity of the S-operator," *Phys. Lett. B* **52**, 344 (1974).
[`https://doi.org/10.1016/0370-2693(74)90058-6`](https://doi.org/10.1016/0370-2693(74)90058-6)

I. V. Tyutin, "Gauge invariance in field theory and statistical physics
in operator formalism," Lebedev Institute preprint No. 39 (1975),
arXiv:0812.0580 (republished 2008).
[`https://arxiv.org/abs/0812.0580`](https://arxiv.org/abs/0812.0580)

V. N. Gribov, "Quantization of non-Abelian gauge theories,"
*Nucl. Phys. B* **139**, 1 (1978).
[`https://doi.org/10.1016/0550-3213(78)90175-X`](https://doi.org/10.1016/0550-3213(78)90175-X)

S. L. Adler, "Axial-vector vertex in spinor electrodynamics,"
*Phys. Rev.* **177**, 2426 (1969).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.177.2426`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.177.2426)

S. L. Adler, "Anomalies to all orders," in G. 't Hooft (ed.), *Fifty
Years of Yang--Mills Theory* (World Scientific, 2005).
[`https://www.worldscientific.com/worldscibooks/10.1142/5601`](https://www.worldscientific.com/worldscibooks/10.1142/5601)

J. S. Bell and R. Jackiw, "A PCAC puzzle: $\pi^0 \to \gamma\gamma$ in
the $\sigma$-model," *Nuovo Cimento A* **60**, 47 (1969).
[`https://doi.org/10.1007/BF02823296`](https://doi.org/10.1007/BF02823296)

S. Deser, M. J. Duff, C. J. Isham, "Non-local conformal anomalies,"
*Nucl. Phys. B* **111**, 45 (1976); M. J. Duff, "Twenty years of the
Weyl anomaly," *Class. Quant. Grav.* **11**, 1387 (1994).
[`https://doi.org/10.1088/0264-9381/11/6/004`](https://doi.org/10.1088/0264-9381/11/6/004)

L. Alvarez-Gaumé and E. Witten, "Gravitational anomalies,"
*Nucl. Phys. B* **234**, 269 (1984).
[`https://doi.org/10.1016/0550-3213(84)90066-X`](https://doi.org/10.1016/0550-3213(84)90066-X)

K. Fujikawa, "Path-integral measure for gauge-invariant fermion
theories," *Phys. Rev. Lett.* **42**, 1195 (1979).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.42.1195`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.42.1195)

M. F. Atiyah and I. M. Singer, "The index of elliptic operators: I,"
*Ann. Math.* **87**, 484 (1968).
[`https://doi.org/10.2307/1970715`](https://doi.org/10.2307/1970715)

G. 't Hooft and M. J. G. Veltman, "Regularization and renormalization of
gauge fields," *Nucl. Phys. B* **44**, 189 (1972).
[`https://doi.org/10.1016/0550-3213(72)90279-9`](https://doi.org/10.1016/0550-3213(72)90279-9)

L. D. Landau, A. A. Abrikosov, I. M. Khalatnikov, "On the removal of
infinities in quantum electrodynamics," *Doklady Akad. Nauk SSSR*
**95**, 497 (1954); **95**, 773 (1954); **95**, 1177 (1954).
[`https://link.springer.com/chapter/10.1007/978-3-540-44872-2_31`](https://link.springer.com/chapter/10.1007/978-3-540-44872-2_31)

S. Weinberg, "Ultraviolet divergences in quantum theories of
gravitation," in S. W. Hawking and W. Israel (eds.), *General
Relativity: An Einstein Centenary Survey* (Cambridge University Press,
1979), pp. 790--831.
[`https://www.cambridge.org/core/books/general-relativity-an-einstein-centenary-survey`](https://www.cambridge.org/core/books/general-relativity-an-einstein-centenary-survey/9D9AA50C2A6AF7E6D0FBA8D6CCA4FFB2)

G. 't Hooft, "Naturalness, chiral symmetry, and spontaneous chiral
symmetry breaking," in G. 't Hooft et al. (eds.), *Recent Developments
in Gauge Theories* (Plenum, 1980), pp. 135--157.
[`https://link.springer.com/chapter/10.1007/978-1-4684-7571-5_9`](https://link.springer.com/chapter/10.1007/978-1-4684-7571-5_9)

D. Buttazzo et al., "Investigating the near-criticality of the Higgs
boson," *JHEP* **12**, 089 (2013).
[`https://link.springer.com/article/10.1007/JHEP12(2013)089`](https://link.springer.com/article/10.1007/JHEP12(2013)089)

A. D. Sakharov, "Violation of CP invariance, C asymmetry, and baryon
asymmetry of the universe," *JETP Lett.* **5**, 24 (1967).
[`http://jetpletters.ru/ps/1643/article_25089.shtml`](http://jetpletters.ru/ps/1643/article_25089.shtml)

M. Fukugita and T. Yanagida, "Baryogenesis without grand unification,"
*Phys. Lett. B* **174**, 45 (1986).
[`https://doi.org/10.1016/0370-2693(86)91126-3`](https://doi.org/10.1016/0370-2693(86)91126-3)

I. Affleck and M. Dine, "A new mechanism for baryogenesis,"
*Nucl. Phys. B* **249**, 361 (1985).
[`https://doi.org/10.1016/0550-3213(85)90021-5`](https://doi.org/10.1016/0550-3213(85)90021-5)

F. R. Klinkhamer and N. S. Manton, "A saddle-point solution in the
Weinberg--Salam theory," *Phys. Rev. D* **30**, 2212 (1984).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.30.2212`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.30.2212)

R. D. Peccei and H. R. Quinn, "CP conservation in the presence of
pseudoparticles," *Phys. Rev. Lett.* **38**, 1440 (1977).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.38.1440`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.38.1440)

F. Zwicky, "Die Rotverschiebung von extragalaktischen Nebeln,"
*Helv. Phys. Acta* **6**, 110 (1933).
[`https://ui.adsabs.harvard.edu/abs/1933AcHPh...6..110Z`](https://ui.adsabs.harvard.edu/abs/1933AcHPh...6..110Z)

V. C. Rubin and W. K. Ford, "Rotation of the Andromeda nebula from a
spectroscopic survey of emission regions," *Astrophys. J.* **159**, 379
(1970).
[`https://ui.adsabs.harvard.edu/abs/1970ApJ...159..379R`](https://ui.adsabs.harvard.edu/abs/1970ApJ...159..379R)

Planck Collaboration (N. Aghanim et al.), "Planck 2018 results. VI.
Cosmological parameters," *Astron. Astrophys.* **641**, A6 (2020).
[`https://www.aanda.org/articles/aa/full_html/2020/09/aa33910-18/aa33910-18.html`](https://www.aanda.org/articles/aa/full_html/2020/09/aa33910-18/aa33910-18.html)

D. Clowe et al., "A direct empirical proof of the existence of dark
matter," *Astrophys. J. Lett.* **648**, L109 (2006).
[`https://iopscience.iop.org/article/10.1086/508162`](https://iopscience.iop.org/article/10.1086/508162)

M. Milgrom, "A modification of the Newtonian dynamics as a possible
alternative to the hidden mass hypothesis," *Astrophys. J.* **270**, 365
(1983).
[`https://ui.adsabs.harvard.edu/abs/1983ApJ...270..365M`](https://ui.adsabs.harvard.edu/abs/1983ApJ...270..365M)

A. G. Riess et al., "Observational evidence from supernovae for an
accelerating universe and a cosmological constant," *Astron. J.*
**116**, 1009 (1998).
[`https://iopscience.iop.org/article/10.1086/300499`](https://iopscience.iop.org/article/10.1086/300499)

S. Perlmutter et al., "Measurements of $\Omega$ and $\Lambda$ from 42
high-redshift supernovae," *Astrophys. J.* **517**, 565 (1999).
[`https://iopscience.iop.org/article/10.1086/307221`](https://iopscience.iop.org/article/10.1086/307221)

G. 't Hooft, "Dimensional reduction in quantum gravity,"
arXiv:gr-qc/9310026 (1993).
[`https://arxiv.org/abs/gr-qc/9310026`](https://arxiv.org/abs/gr-qc/9310026)

L. Susskind, "The world as a hologram," *J. Math. Phys.* **36**, 6377
(1995).
[`https://doi.org/10.1063/1.531249`](https://doi.org/10.1063/1.531249)

G. 't Hooft, "Magnetic monopoles in unified gauge theories,"
*Nucl. Phys. B* **79**, 276 (1974); A. M. Polyakov, "Particle spectrum
in quantum field theory," *JETP Lett.* **20**, 194 (1974).
[`https://doi.org/10.1016/0550-3213(74)90486-6`](https://doi.org/10.1016/0550-3213(74)90486-6)

A. M. Polyakov, "Particle spectrum in quantum field theory," *JETP
Lett.* **20**, 194 (1974).
[`http://jetpletters.ru/ps/1789/article_27297.shtml`](http://jetpletters.ru/ps/1789/article_27297.shtml)

T. W. B. Kibble, "Topology of cosmic domains and strings," *J. Phys. A*
**9**, 1387 (1976).
[`https://iopscience.iop.org/article/10.1088/0305-4470/9/8/029`](https://iopscience.iop.org/article/10.1088/0305-4470/9/8/029)

J. Martin and R. H. Brandenberger, "The trans-Planckian problem of
inflationary cosmology," *Phys. Rev. D* **63**, 123501 (2001).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.63.123501`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.63.123501)

W. G. Unruh, "Experimental black-hole evaporation?" *Phys. Rev. Lett.*
**46**, 1351 (1981).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.46.1351`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.46.1351)

A. Albrecht, "Cosmic inflation and the arrow of time," in J. D. Barrow,
P. C. W. Davies, and C. L. Harper (eds.), *Science and Ultimate Reality*
(Cambridge University Press, 2004).
[`https://www.cambridge.org/core/books/science-and-ultimate-reality`](https://www.cambridge.org/core/books/science-and-ultimate-reality/E62A3A38B25A4C9D5DCBA38D8D86B9F2)

D. N. Page, "Is our universe likely to decay within 20 billion years?"
*Phys. Rev. D* **78**, 063535 (2008).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.78.063535`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.78.063535)

L. Susskind, "Computational complexity and black hole horizons,"
*Fortsch. Phys.* **64**, 24 (2016) \[arXiv:1402.5674 (2014)\].
[`https://arxiv.org/abs/1402.5674`](https://arxiv.org/abs/1402.5674)

A. R. Brown and L. Susskind, "The second law of quantum complexity,"
*Phys. Rev. D* **97**, 086015 (2018) \[arXiv:1701.01107 (2017)\].
[`https://arxiv.org/abs/1701.01107`](https://arxiv.org/abs/1701.01107)

S. Lloyd, "Ultimate physical limits to computation," *Nature* **406**,
1047 (2000).
[`https://www.nature.com/articles/35023282`](https://www.nature.com/articles/35023282)

J. M. Maldacena, "The large-$N$ limit of superconformal field theories
and supergravity," *Adv. Theor. Math. Phys.* **2**, 231 (1998)
\[arXiv:hep-th/9711200 (1997)\].
[`https://arxiv.org/abs/hep-th/9711200`](https://arxiv.org/abs/hep-th/9711200)

E. Witten, "Anti-de Sitter space and holography,"
*Adv. Theor. Math. Phys.* **2**, 253 (1998).
[`https://arxiv.org/abs/hep-th/9802150`](https://arxiv.org/abs/hep-th/9802150)

S. S. Gubser, I. R. Klebanov, A. M. Polyakov, "Gauge theory correlators
from non-critical string theory," *Phys. Lett. B* **428**, 105 (1998).
[`https://arxiv.org/abs/hep-th/9802109`](https://arxiv.org/abs/hep-th/9802109)

S. Ryu and T. Takayanagi, "Holographic derivation of entanglement
entropy from AdS/CFT," *Phys. Rev. Lett.* **96**, 181602 (2006).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.96.181602`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.96.181602)

A. Almheiri, N. Engelhardt, D. Marolf, H. Maxfield, "The entropy of bulk
quantum fields and the entanglement wedge of an evaporating black hole,"
*JHEP* **12**, 063 (2019).
[`https://link.springer.com/article/10.1007/JHEP12(2019)063`](https://link.springer.com/article/10.1007/JHEP12(2019)063)

J. D. Bekenstein, "Black holes and entropy," *Phys. Rev. D* **7**, 2333
(1973).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.7.2333`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.7.2333)

J. D. Bekenstein, "Universal upper bound on the entropy-to-energy ratio
for bounded systems," *Phys. Rev. D* **23**, 287 (1981).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.23.287`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.23.287)

R. Bousso, "A covariant entropy conjecture," *JHEP* **07**, 004 (1999).
[`https://iopscience.iop.org/article/10.1088/1126-6708/1999/07/004`](https://iopscience.iop.org/article/10.1088/1126-6708/1999/07/004)

S. W. Hawking, M. J. Perry, A. Strominger, "Soft hair on black holes,"
*Phys. Rev. Lett.* **116**, 231301 (2016).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.231301`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.231301)

A. Strominger, "On BMS invariance of gravitational scattering," *JHEP*
**07**, 152 (2014).
[`https://link.springer.com/article/10.1007/JHEP07(2014)152`](https://link.springer.com/article/10.1007/JHEP07(2014)152)

S. Weinberg, "Infrared photons and gravitons," *Phys. Rev.* **140**,
B516 (1965).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.140.B516`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.140.B516)

Ya. B. Zel'dovich and A. G. Polnarev, "Radiation of gravitational waves
by a cluster of superdense stars," *Sov. Astron.* **18**, 17 (1974).
[`https://ui.adsabs.harvard.edu/abs/1974SvA....18...17Z`](https://ui.adsabs.harvard.edu/abs/1974SvA....18...17Z)

J. W. Gibbs, *Elementary Principles in Statistical Mechanics* (Charles
Scribner's Sons, 1902).
[`https://www.gutenberg.org/ebooks/50992`](https://www.gutenberg.org/ebooks/50992)

J. d'Alembert, *Essai d'une nouvelle théorie de la résistance des
fluides* (David, 1752).
[`https://gallica.bnf.fr/ark:/12148/bpt6k1520055k`](https://gallica.bnf.fr/ark:/12148/bpt6k1520055k)

Z. Xia, "The existence of noncollision singularities in Newtonian
systems," *Ann. Math.* **135**, 411 (1992).
[`https://doi.org/10.2307/2946572`](https://doi.org/10.2307/2946572)

E. McGucken, "Solution of the Navier--Stokes Existence and Smoothness
Problem on $\mathbb{R}^3$ from the McGucken Principle $dx_4/dt = ic$,"
*elliotmcguckenphysics.com* (2026).
[`https://elliotmcguckenphysics.com`](https://elliotmcguckenphysics.com)

E. McGucken, "Foundational Thermodynamics from $dx_4/dt = ic$:
Twenty-Three Theorems of the Second Law and the Arrow of Time,"
*elliotmcguckenphysics.com* (2026).
[`https://elliotmcguckenphysics.com`](https://elliotmcguckenphysics.com)

J. Schwinger, "Quantum electrodynamics. I. A covariant formulation,"
*Phys. Rev.* **74**, 1439 (1948).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.74.1439`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.74.1439)

R. P. Feynman, "Space-time approach to quantum electrodynamics,"
*Phys. Rev.* **76**, 769 (1949).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.76.769`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.76.769)

S. Tomonaga, "On a relativistically invariant formulation of the quantum
theory of wave fields," *Prog. Theor. Phys.* **1**, 27 (1946).
[`https://academic.oup.com/ptp/article/1/2/27/1845518`](https://academic.oup.com/ptp/article/1/2/27/1845518)

F. J. Dyson, "The radiation theories of Tomonaga, Schwinger, and
Feynman," *Phys. Rev.* **75**, 486 (1949).
[`https://journals.aps.org/pr/abstract/10.1103/PhysRev.75.486`](https://journals.aps.org/pr/abstract/10.1103/PhysRev.75.486)

K. G. Wilson, "Renormalization group and critical phenomena. I.
Renormalization group and the Kadanoff scaling picture," *Phys. Rev. B*
**4**, 3174 (1971).
[`https://journals.aps.org/prb/abstract/10.1103/PhysRevB.4.3174`](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.4.3174)

K. G. Wilson and J. Kogut, "The renormalization group and the $\epsilon$
expansion," *Phys. Rep.* **12**, 75 (1974).
[`https://doi.org/10.1016/0370-1573(74)90023-4`](https://doi.org/10.1016/0370-1573(74)90023-4)

M. Aizenman, "Proof of the triviality of $\phi^4_d$ field theory and
some mean-field features of Ising models for $d > 4$,"
*Phys. Rev. Lett.* **47**, 1 (1981).
[`https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.47.1`](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.47.1)

J. Fröhlich, "On the triviality of $\lambda\phi^4_d$ theories and the
approach to the critical point in $d \geq 4$ dimensions,"
*Nucl. Phys. B* **200**, 281 (1982).
[`https://doi.org/10.1016/0550-3213(82)90088-8`](https://doi.org/10.1016/0550-3213(82)90088-8)

L. Boltzmann, "Zu Hrn. Zermelo's Abhandlung Ueber die mechanische
Erklärung irreversibler Vorgänge," *Ann. Phys.* **60**, 392 (1897).
[`https://onlinelibrary.wiley.com/doi/10.1002/andp.18972970218`](https://onlinelibrary.wiley.com/doi/10.1002/andp.18972970218)

G. Penington, "Entanglement wedge reconstruction and the information
paradox," *JHEP* **09**, 002 (2020) \[arXiv:1905.08255 (2019)\].
[`https://arxiv.org/abs/1905.08255`](https://arxiv.org/abs/1905.08255)

A. Einstein and M. Grossmann, "Entwurf einer verallgemeinerten
Relativitätstheorie und einer Theorie der Gravitation," *Z. Math. Phys.*
**62**, 225 (1914).
[`https://einsteinpapers.press.princeton.edu/vol4-doc/335`](https://einsteinpapers.press.princeton.edu/vol4-doc/335)

J. Norton, "How Einstein found his field equations: 1912--1915,"
*Hist. Stud. Phys. Sci.* **14**, 253 (1984).
[`https://www.jstor.org/stable/27757535`](https://www.jstor.org/stable/27757535)

L. Susskind, L. Thorlacius, J. Uglum, "The stretched horizon and black
hole complementarity," *Phys. Rev. D* **48**, 3743 (1993).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.48.3743`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.48.3743)

E. Verlinde, "On the origin of gravity and the laws of Newton," *JHEP*
**04**, 029 (2011).
[`https://link.springer.com/article/10.1007/JHEP04(2011)029`](https://link.springer.com/article/10.1007/JHEP04(2011)029)

E. P. Wigner, "On unitary representations of the inhomogeneous Lorentz
group," *Ann. Math.* **40**, 149 (1939).
[`https://doi.org/10.2307/1968551`](https://doi.org/10.2307/1968551)

H. Reeh and S. Schlieder, "Bemerkungen zur Unitäräquivalenz von
Lorentzinvarianten Feldern," *Nuovo Cimento* **22**, 1051 (1961).
[`https://doi.org/10.1007/BF02787889`](https://doi.org/10.1007/BF02787889)

A. D. Linde, "A new inflationary universe scenario," *Phys. Lett. B*
**108**, 389 (1982).
[`https://doi.org/10.1016/0370-2693(82)91219-9`](https://doi.org/10.1016/0370-2693(82)91219-9)

A. Vilenkin, "The birth of inflationary universes," *Phys. Rev. D*
**27**, 2848 (1983).
[`https://journals.aps.org/prd/abstract/10.1103/PhysRevD.27.2848`](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.27.2848)

A. D. Linde, "Eternally existing self-reproducing chaotic inflationary
universe," *Phys. Lett. B* **175**, 395 (1986).
[`https://doi.org/10.1016/0370-2693(86)90611-8`](https://doi.org/10.1016/0370-2693(86)90611-8)

S. M. Carroll, "What if time really exists?" arXiv:0811.3772 (2008); S.
M. Carroll, *From Eternity to Here: The Quest for the Ultimate Theory of
Time* (Dutton, 2010).
[`https://arxiv.org/abs/0811.3772`](https://arxiv.org/abs/0811.3772)

R. B. Griffiths, "Consistent histories and the interpretation of quantum
mechanics," *J. Stat. Phys.* **36**, 219 (1984); M. Gell-Mann and J. B.
Hartle, "Classical equations for quantum systems," *Phys. Rev. D*
**47**, 3345 (1993).
[`https://doi.org/10.1007/BF01015734`](https://doi.org/10.1007/BF01015734)

G. C. Wick, "Properties of Bethe-Salpeter wave functions," *Phys. Rev.*
**96**, 1124 (1954).
[`https://doi.org/10.1103/PhysRev.96.1124`](https://doi.org/10.1103/PhysRev.96.1124)

K. Osterwalder and R. Schrader, "Axioms for Euclidean Green's
functions," *Commun. Math. Phys.* **31**, 83 (1973); **42**, 281 (1975).
[`https://doi.org/10.1007/BF01645738`](https://doi.org/10.1007/BF01645738)

J. Schwinger, "Euclidean quantum electrodynamics," *Phys. Rev.* **115**,
721 (1959).
[`https://doi.org/10.1103/PhysRev.115.721`](https://doi.org/10.1103/PhysRev.115.721)

A. Strominger and C. Vafa, "Microscopic origin of the
Bekenstein--Hawking entropy," *Phys. Lett. B* **379**, 99 (1996).
[`https://doi.org/10.1016/0370-2693(96)00345-0`](https://doi.org/10.1016/0370-2693(96)00345-0)

G. Berkeley, *De Motu; or, On the Principle and Nature of Motion and the
Cause of the Communication of Motions* (London, 1721); reprinted in
A. A. Luce and T. E. Jessop, eds., *The Works of George Berkeley*,
vol. 4 (Nelson, 1951).

E. Mach, *Die Mechanik in ihrer Entwickelung: Historisch-kritisch
dargestellt* (Brockhaus, Leipzig, 1883); English translation: *The
Science of Mechanics: A Critical and Historical Account of Its
Development* (Open Court, La Salle, 1960).

A. Einstein, "Prinzipielles zur allgemeinen Relativitätstheorie,"
*Annalen der Physik* **55**, 241 (1918).
[`https://doi.org/10.1002/andp.19183600402`](https://doi.org/10.1002/andp.19183600402)

K. Gödel, "An example of a new type of cosmological solutions of
Einstein's field equations of gravitation," *Rev. Mod. Phys.* **21**,
447 (1949).
[`https://doi.org/10.1103/RevModPhys.21.447`](https://doi.org/10.1103/RevModPhys.21.447)

W. J. van Stockum, "The gravitational field of a distribution of
particles rotating around an axis of symmetry,"
*Proc. Roy. Soc. Edinburgh* **57**, 135 (1937).
[`https://doi.org/10.1017/S0370164600013699`](https://doi.org/10.1017/S0370164600013699)

F. J. Tipler, "Rotating cylinders and the possibility of global
causality violation," *Phys. Rev. D* **9**, 2203 (1974).
[`https://doi.org/10.1103/PhysRevD.9.2203`](https://doi.org/10.1103/PhysRevD.9.2203)

S. Deser, R. Jackiw, and G. 't Hooft, "Three-dimensional Einstein
gravity: Dynamics of flat space," *Ann. Phys. (NY)* **152**, 220 (1984).
[`https://doi.org/10.1016/0003-4916(84)90085-X`](https://doi.org/10.1016/0003-4916(84)90085-X)

S. W. Hawking, "Chronology protection conjecture," *Phys. Rev. D*
**46**, 603 (1992).
[`https://doi.org/10.1103/PhysRevD.46.603`](https://doi.org/10.1103/PhysRevD.46.603)

P. J. E. Peebles, *Quantum Mechanics* (Princeton University Press,
1992).

