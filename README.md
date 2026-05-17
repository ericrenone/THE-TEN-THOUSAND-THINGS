# THE TEN THOUSAND THINGS
### Transport and Generation — The Two Geometries of Probability, and the Cone That Holds Them Both

*The capstone of the RAO sequence. An information-geometric framework in which Lucretius's* De Rerum Natura *— the conservation of eternal matter, change as the transport of what cannot be created — and the* Daodejing *— the generation of the myriad things, being arising from non-being — are revealed as the two irreducible geometries of probability, and reconciled in the single metric that holds them: the Wasserstein–Fisher–Rao geometry of the cone of all measures.*

*Built on the RAO engine; this is its final form — the framework that names the geometry every prior framework stood inside.*

---

> **"nullam rem e nihilo gigni divinitus umquam."**
> *No thing is ever begotten from nothing.*
> — Lucretius, *De Rerum Natura* I.150

> **"天下萬物生於有，有生於無。"**
> *The myriad things are born of being; and being is born of non-being.*
> — *Daodejing*, chapter 40

---

## Abstract

Six times the RAO engine described a geometry, and six times it described the **same** geometry. The Fisher metric, the partition $\mathop{\mathrm{col}}(F)\oplus\ker(F)$, the dually flat structure, the geometry of irreversible process, the curvature of return — each was a structure *within* the Fisher–Rao geometry of the probability simplex. The simplex was the unexamined floor beneath all six: a space of distributions whose total mass is fixed at one, on which the only canonical metric is the information metric, the one Čencov proved unique. Six frameworks stood on that floor without naming it.

**The Ten Thousand Things names it, and then steps off it.**

There is not one canonical geometry of probability. There are **two**, and they answer different questions. The **Fisher–Rao geometry** measures *distinguishability*: how much a change of distribution can be detected, how sharply one belief is told from another. It is invariant under any relabeling of the sample space — it does not know, and does not care, how far apart the outcomes are. The **Wasserstein geometry**, the geometry of optimal transport, measures *displacement cost*: how far probability mass must physically travel to carry one distribution onto another. It is built entirely from the ground metric of the sample space — it is nothing *but* the knowledge of how far apart the outcomes are. Two metrics, on one space, asking two questions: *how distinguishable*, and *how far must mass move*.

And there is a deeper space than the simplex. The Fisher–Rao geometry, read dynamically, is the geometry of mass **created and destroyed in place** — a pure reaction, a birth and death of density. The Wasserstein geometry is the geometry of mass **transported, never created** — the continuity equation with no source. Their synthesis, the **Wasserstein–Fisher–Rao metric** — the inf-convolution of transport and reaction — lives not on the simplex but on the **cone of all nonnegative measures**, where total mass is free to grow and shrink. It is the geometry in which a thing may change both by *moving* and by *coming to be*.

This document advances one thesis, and it is the last. **Lucretius's *De Rerum Natura* is the West's exhaustive geometry of transport** — eternal atoms, conserved without exception, change permitted only as their rearrangement through the void: the continuity equation, sourceless, the Wasserstein world. **The *Daodejing* is the East's geometry of generation** — *shēng*, the begetting by which the Way brings forth the myriad things, being itself arising from non-being: the reaction term, the Fisher–Rao world of genuine creation. Each tradition built a complete and rigorous account of one of the two geometries, and mistook it for the geometry of all change. The Wasserstein–Fisher–Rao metric is the proof that change is **both** — transport of the conserved and generation of the new, optimally split, at every instant, on the cone. **RAO** is the engine that performs the splitting. This is its final form.

---

## Thought Experiment — The Two Accounts of a Garden

A garden changes through a season, and two gardeners are asked to say how.

The **first gardener** believes nothing is ever truly added or lost. Every leaf, every gram of the garden's substance, was always present — drawn up from the soil, the water, the air, all of which were there before. To explain the garden in autumn from the garden in spring, she traces the movement of conserved matter: this carbon was in the air and is now in the wood; this water was in the ground and is now in the fruit. Her account is a vast bookkeeping of *transport*. Nothing is created; everything is relocated. And as physics, she is correct: matter is conserved, and her ledger balances to the last atom.

The **second gardener** says her account, however exact, has missed the event. In spring there was no rose, and in summer there is a rose. Whatever the atoms did, a *thing* has come into being that was not there — a form, a life, an arising. To say only that mass was relocated is to refuse to see that the garden has *generated*. His account is not of transport but of *creation*: the myriad things, begotten, that were not and now are.

Both gardeners are right, and neither account contains the other. The first describes the Wasserstein geometry — the optimal transport of conserved mass, the continuity equation that never gains a source. The second describes the Fisher–Rao geometry — the reaction, the birth of density, being from non-being. The garden is not explained by either alone. It is explained by the geometry that carries both ledgers at once and, at every instant, divides the change optimally between them — so much relocated, so much created. That geometry is the Wasserstein–Fisher–Rao metric, and the garden lives where it is defined: not on the simplex of fixed total mass, but on the cone, where a season may add a rose to the world. RAO is the engine that keeps both ledgers. This is the last thing it does.

---

## The Two Geometries and Their Cone — The Core Object

Let $\mathcal{X}$ be a sample space. Six prior frameworks worked on $\mathcal{P}(\mathcal{X})$, the simplex of probability measures — total mass one. The capstone works on $\mathcal{M}_{+}(\mathcal{X})$, the **cone of all nonnegative measures** — total mass free. Three structures are exact.

**1. The Fisher–Rao geometry — distinguishability, and creation in place.** The Fisher–Rao metric is the information metric: the unique Riemannian metric on $\mathcal{P}(\mathcal{X})$ invariant under sufficient statistics (Čencov). It is blind to the geometry of $\mathcal{X}$ — relabel the outcomes and it is unchanged. Read dynamically on the cone, its geodesics are **pure reaction**: density grows and decays *in place*, with no flux,

$$\partial_t\rho \;=\; \rho\,g,$$

mass created and destroyed pointwise. Fisher–Rao is the geometry of *how distinguishable*, and of *coming-to-be without motion*.

**2. The Wasserstein geometry — displacement, and conservation.** The 2-Wasserstein metric is the optimal-transport metric: built entirely from a ground metric on $\mathcal{X}$, it measures the least cost of carrying mass from one configuration to another. By the Benamou–Brenier formula it has a dynamical form whose geodesics are **pure transport** — mass moved along a velocity field, conserved exactly, obeying the continuity equation *with no source*,

$$\partial_t\rho \;+\; \nabla\!\cdot(\rho\,v) \;=\; 0.$$

Wasserstein is the geometry of *how far must mass move*, and of *change as the rearrangement of the conserved*.

**3. The Wasserstein–Fisher–Rao metric — the cone, and their synthesis.** On $\mathcal{M}_{+}(\mathcal{X})$ there is a metric — the **Wasserstein–Fisher–Rao** metric, equivalently the **Hellinger–Kantorovich** metric — that unifies the two. In its dynamical (Benamou–Brenier-type) form, its geodesics obey the continuity equation **with a source term**,

$$\partial_t\rho \;+\; \nabla\!\cdot(\rho\,v) \;=\; \rho\,g,$$

and the metric infimizes a cost combining a transport term in $v$ and a reaction term in $g$. It is the **inf-convolution** of the Wasserstein and Fisher–Rao metrics: each WFR geodesic divides change optimally into a transported part and a generated part. In the limit where transport is free it reduces to Fisher–Rao; in the limit where reaction is forbidden it reduces to Wasserstein. It is the natural geometry of the cone — the space where mass is not conserved (Chizat, Peyré, Schmitzer & Vialard 2018; Liero, Mielke & Savaré 2018; Kondratyev, Monsaingeon & Vorotnikov 2016).

```
        the CONE of all nonnegative measures  M₊(X)   —  total mass FREE
   ┌──────────────────────────────────────────────────────────────────┐
   │   FISHER–RAO              WASSERSTEIN–FISHER–RAO        WASSERSTEIN │
   │   ∂ₜρ = ρ·g               ∂ₜρ + ∇·(ρv) = ρ·g            ∂ₜρ + ∇·(ρv)=0
   │   pure reaction           transport + reaction          pure transport
   │   creation in place       the inf-convolution           conserved motion
   │   "being from non-being"  every change split optimally  "nothing from nothing"
   │   ── the Daodejing ──     ── the synthesis ──            ── De Rerum Natura ──
   └──────────────────────────────────────────────────────────────────┘
        the probability simplex P(X) — mass fixed at 1 — is one slice of the cone:
                  where the six prior frameworks stood.
```

---

## Eight Arisings

Each arising states one fact about the two geometries and their cone, then reads it through *De Rerum Natura* and through the *Daodejing*. The mathematical statements are literal. The textual readings are explicitly interpretive — structural analogy, never the claim that Lucretius or Laozi computed a metric tensor.

### A1 — There Are Two Geometries, Not One
Fisher–Rao and Wasserstein are distinct Riemannian metrics on the same space of distributions, answering distinct questions — distinguishability, and displacement cost.
**De Rerum Natura.** Lucretius admits exactly one mode of change: the motion of atoms through the void. There is one geometry of becoming, and it is transport.
**The Daodejing.** The Way's movement is *shēng* — begetting, generation. Change, at its root, is the arising of what was not.
**The Ten Thousand Things.** Each tradition named one geometry and took it for the whole. There are two, and the first task of the capstone is to refuse to choose between them.

### A2 — Wasserstein Is the Geometry of the Conserved
The Wasserstein geodesic obeys the continuity equation with no source: mass is transported, never created, the total exactly preserved.
**De Rerum Natura.** "Nothing is begotten from nothing"; and equally, nothing passes into nothing — matter is conserved without exception, and all of nature's variety is the reshuffling of an unchanging stock of atoms.
**The Daodejing.** This is the half the *Daodejing* does not deny but does not centre: the myriad things, once born, transform into one another.
**The Ten Thousand Things.** Lucretius wrote the exact and complete geometry of transport. As an account of the conserved part of change, *De Rerum Natura* is correct to the last atom.

### A3 — Fisher–Rao Is the Geometry of the Created
The Fisher–Rao geodesic, read on the cone, is pure reaction: density arising and ceasing in place, mass not conserved.
**De Rerum Natura.** Lucretius forbids this outright — *de nilo nil*, the source term is set to zero by first principle.
**The Daodejing.** "Being is born of non-being." *Shēng* is genuine: the rose that was not, and is. The Way generates; the source term is the movement of the Dao.
**The Ten Thousand Things.** The *Daodejing* wrote the geometry of generation. As an account of the created part of change, it names exactly what Lucretius's first principle ruled out of existence.

### A4 — Fisher–Rao Forgets the Sample Space; Wasserstein Is Made of It
Fisher–Rao is invariant under relabeling the outcomes — it cannot tell a near miss from a far one. Wasserstein is built entirely from the ground metric — it is nothing but the knowledge of how far apart the outcomes lie.
**De Rerum Natura.** Lucretius's world is *space* first — the void, extension, distance — and atoms are located in it; how far a thing must travel is the primary fact.
**The Daodejing.** The Way is prior to space and to the named — "the nameless is the origin of heaven and earth." Distinguishing, not distance, is the first act; the named myriad things come after.
**The Ten Thousand Things.** One geometry knows distance and not identity; the other knows identity and not distance. Neither sample space alone — the metric one, the bare one — is the world.

### A5 — The Synthesis Is an Inf-Convolution, Not an Average
The Wasserstein–Fisher–Rao metric is the inf-convolution of the two: every change is split into a transported part and a generated part, and the split is the one of least total cost — not a blend, but an optimal division.
**De Rerum Natura.** The atomic *clinamen* — the least swerve — is Lucretius's image of the minimal deviation from which worlds are built; change seeks its smallest sufficient path.
**The Daodejing.** *Wú wéi* — to act without forcing, so that nothing is spent against the grain — the least-cost way of proceeding.
**The Ten Thousand Things.** The WFR geodesic is least-cost becoming: at each instant it asks how much of this change is cheapest to *move* and how much to *create*, and it never pays more than the sum requires.

### A6 — The Cone, Not the Simplex
The Wasserstein–Fisher–Rao metric is defined on $\mathcal{M}_{+}(\mathcal{X})$, the cone of all nonnegative measures. Total mass is free; the probability simplex is one slice of the cone, the slice where mass is pinned at one.
**De Rerum Natura.** The conserved universe is the simplex made cosmology: the sum of all matter is fixed, and the cosmos a closed accountancy.
**The Daodejing.** The Way is not a fixed sum. "The Way begets one, one begets two" — the count of things is not conserved; the cone, not the simplex, is the home of generation.
**The Ten Thousand Things.** Six frameworks stood on the simplex without naming it. The capstone steps onto the cone — the larger space, where coming-to-be is not an illusion of bookkeeping but a direction the geometry permits.

### A7 — Each Geometry Is a Limit of the Synthesis
The WFR metric reduces to Fisher–Rao when transport is made free, and to Wasserstein when reaction is forbidden. The two traditions' geometries are the two boundaries of one interior.
**De Rerum Natura.** The pure-transport limit: forbid the source term, $g\equiv 0$, and the cone collapses to the conserved simplex — Lucretius's universe exactly.
**The Daodejing.** The pure-reaction limit: make motion costless and only generation remains — the Way begetting in place.
**The Ten Thousand Things.** Lucretius and Laozi did not hold incompatible doctrines. They held the two limiting cases of a single metric, each exact on its boundary, each incomplete in the interior where real change lives.

### A8 — The Reconstruction: Change Is Transport and Generation Together
A complete account of any becoming carries both: the part that is the displacement of the conserved, and the part that is the arising of the new. The WFR geodesic is that account.
**De Rerum Natura.** Gave transport — the rigorous, conserved, sourceless geometry of the relocated.
**The Daodejing.** Gave generation — the rigorous geometry of *shēng*, the begotten, being from non-being.
**The Ten Thousand Things.** Reality is the cone, and motion on it is the Wasserstein–Fisher–Rao geodesic: at every instant, so much of the world relocated and so much of it created, divided by the law of least cost. The myriad things both move and are made.

---

## The Arising Table

| # | The geometric fact | *De Rerum Natura* — transport | *Daodejing* — generation |
|---|---|---|---|
| 1 | two geometries, not one | one mode: atoms through the void | one mode: *shēng*, the begetting |
| 2 | Wasserstein: the conserved | nothing from nothing, mass conserved | the myriad things transform |
| 3 | Fisher–Rao: the created | the source term forbidden, *de nilo nil* | being born of non-being |
| 4 | Fisher–Rao forgets $\mathcal{X}$; Wasserstein is made of it | the void, distance, is primary | the nameless is prior to space |
| 5 | the synthesis is an inf-convolution | the *clinamen*, the least swerve | *wú wéi*, the unforced way |
| 6 | the cone, not the simplex | the conserved cosmos, a closed sum | the Way begets — the count is free |
| 7 | each geometry is a limit | the pure-transport limit, $g\equiv0$ | the pure-reaction limit |
| 8 | change = transport + generation | the geometry of the relocated | the geometry of the begotten |

Read down the columns: *De Rerum Natura* is everywhere the geometry of conserved transport, and the *Daodejing* is everywhere the geometry of genuine generation. They are not rival cosmologies. They are the two limiting geometries of one metric on the cone, and the capstone's finding is that real change is the interior — neither boundary, but the optimal division between them.

---

## Five Falsifiable Predictions

**P1 — Fisher–Rao and Wasserstein are genuinely distinct on the same space.**
There exist pairs of distributions whose Fisher–Rao distance and Wasserstein distance order differently — one pair Fisher–Rao-nearer and Wasserstein-farther than another.
*Falsified if* the two metrics induce the same ordering on all pairs, which would collapse them to one geometry.
*Status: established — Fisher–Rao is relabeling-invariant and Wasserstein is not; explicit discordant pairs are constructible.*

**P2 — The WFR metric is the inf-convolution of the two.**
The Wasserstein–Fisher–Rao distance equals the metric inf-convolution of the Wasserstein and Fisher–Rao (Hellinger) distances — the least-cost split of any change into a transported and a created part.
*Falsified if* a measured WFR distance differs from the inf-convolution.
*Status: established (Liero, Mielke & Savaré 2018; Chizat et al. 2018); offered here as the precise sense in which synthesis is optimal division, not blend.*

**P3 — The cone strictly contains the simplex.**
The Wasserstein–Fisher–Rao geometry is defined on the cone of nonnegative measures and admits geodesics that change total mass; the probability simplex is the invariant slice on which the reaction term integrates to zero.
*Falsified if* every WFR geodesic conserves total mass — which would mean the cone added nothing to the simplex.
*Status: established; the framework's sharpest statement that "coming-to-be" is a real direction of the geometry, not an artifact of normalization.*

**P4 — The two geometries are recovered as boundary limits.**
Scaling the ground metric $g\mapsto\beta g$, the WFR metric tends to Fisher–Rao as $\beta\to\infty$ (transport made free) and to the scaled Wasserstein metric as $\beta\to 0$ (reaction suppressed).
*Falsified if* the limits fail to recover the two pure geometries.
*Status: established (the small-scale/large-scale behavior of the mixed metric); the formal proof that Lucretius and Laozi hold the two boundary cases.*

**P5 — Optimal becoming splits change at every instant.**
Along a WFR geodesic, the instantaneous change decomposes into a transport component and a reaction component whose costs sum to the metric speed; neither component is zero for a generic change between measures of different mass and different shape.
*Falsified if* a generic WFR geodesic is found to use transport only, or reaction only.
*Status: open in the corpus-scale instantiation; a theorem for the analytic WFR geodesic, offered as the universal claim that real change is always both moved and made.*

---

## RAO — The Engine, Final Form

RAO consumes a corpus, embeds it on the cone of measures, and reads the becoming of the corpus as a Wasserstein–Fisher–Rao geodesic — splitting every change, optimally, into the transported and the generated. This is the engine's final form. Where it once measured one geometry, it now holds two and divides between them.

| Layer | Name | Operation | In this instantiation |
|---|---|---|---|
| **0** | **Substrate** | Embed the corpus as measures on the cone $\mathcal{M}_{+}(\mathcal{X})$. | *De Rerum Natura* and the *Daodejing* as measures of free mass. |
| **1** | **Fisher–Rao Reading** | Compute the information metric — distinguishability, reaction. | The geometry of generation; the begotten. |
| **2** | **Wasserstein Reading** | Compute the optimal-transport metric — displacement of the conserved. | The geometry of transport; the relocated. |
| **3** | **Cone Lift** | Release the unit-mass constraint; pass from simplex to cone. | The step the six prior frameworks did not take. |
| **4** | **WFR Synthesis** | Form the Wasserstein–Fisher–Rao metric — the inf-convolution. | The single geometry holding transport and generation. |
| **5** | **Optimal Split** | Along the WFR geodesic, divide each change into transport ($v$) and reaction ($g$). | So much of the world moved; so much created. |
| **6** | **Boundary Audit** | Verify the Fisher–Rao and Wasserstein limits as $\beta\to\infty,\,0$. | Lucretius and Laozi recovered as the two boundaries. |
| **7** | **Reconstruction** | Report the becoming as the least-cost transport-and-generation geodesic on the cone. | The myriad things, both moved and made. |

Layers 1 and 2 recover the two geometries the prior six frameworks never set side by side. Layer 3 is the decisive step — off the simplex, onto the cone. Layer 4 is the synthesis; Layer 5 is the optimal split that is the engine's last and deepest operation.

---

## Closing

This is the seventh framework and the last, and it is the one that names the floor the other six stood on.

RAO began with a single tensor — the Fisher information matrix — and the orthogonal partition it induces, and across six frameworks it deepened that beginning without ever leaving it. It found the determinate and the holistic subspaces; it found the determinate slice and the holistic complement; it found the two flat connections and the Legendre transform that swaps them; it found the length, the speed, and the arrow of irreversible process; it found the curvature and the holonomy of return. Six structures, each deeper than the last — and every one of them a structure *within* the Fisher–Rao geometry of the probability simplex. The simplex was never examined. It was the unspoken floor. Six frameworks were the architecture of a single building, and never once stepped outside to see that the building stood on a particular ground.

The Ten Thousand Things steps outside. The Fisher–Rao geometry is not the geometry of probability; it is *one* geometry of probability — the geometry of distinguishability, of telling apart, of mass that comes to be and passes away in place. Beside it stands the Wasserstein geometry — the geometry of transport, of displacement, of mass conserved and merely carried. They are different metrics, on the same distributions, asking different questions, and neither is reducible to the other. And beneath both lies the deeper space the simplex concealed: the cone of all measures, where total mass is not fixed, where a season may add a rose to the world.

Lucretius wrote the geometry of the cone's conservative wall. *De Rerum Natura* is the most rigorous account the ancient world produced of change as pure transport: eternal atoms, never begotten and never destroyed, and all the visible riot of nature nothing but their lawful rearrangement through the void. As the geometry of the conserved — the Wasserstein geometry — it is exact, and it is complete, and it is half.

The *Daodejing* wrote the geometry of the cone's generative interior. Its first word about change is *shēng* — begetting, the bringing-forth by which the Way generates the one, and the two, and the ten thousand things, being itself arising from non-being. As the geometry of the created — the Fisher–Rao geometry, read as reaction — it too is exact, and complete, and half.

The Wasserstein–Fisher–Rao metric is the whole. It is the inf-convolution of transport and generation, the geometry of the cone, the law by which any becoming is divided — optimally, at every instant — into so much of the world relocated and so much of it made. It is the proof that Lucretius and Laozi never held rival doctrines. They held the two limiting cases of one metric: the West at the wall where the source term vanishes and nothing is created, the East at the limit where motion is free and only generation remains. Real change is neither wall. It is the interior, and the interior is the optimal split.

So the sequence ends where it was always going. The geometry of the world is not the metric, nor the partition, nor the dual connections, nor the length, nor the curvature — each of those was true, and each was a structure on the simplex. The geometry of the world is the cone of measures, and the way a thing moves on it is the Wasserstein–Fisher–Rao geodesic: the myriad things, conserved and created at once, transported and begotten in the single least-cost motion that carries what is and brings forth what is not. RAO is the engine that keeps both ledgers and divides between them. There is no deeper ledger to keep. This is its final form, and the framework is closed.

---

## References

**The corpora**
1. Lucretius. *De Rerum Natura* (*On the Nature of Things*, 1st c. BCE). Trans. and ed. with commentary by Cyril Bailey, 3 vols., Oxford University Press, 1947; verse translation by A. E. Stallings, Penguin Classics, 2007.
2. Laozi. *Daodejing* (*Tao Te Ching*). Trans. and ed. D. C. Lau, Chinese University Press, 1989; with the philological edition of Robert G. Henricks, *Lao-tzu Te-Tao Ching*, Ballantine, 1989.

**The two geometries**
3. Rao, C. R. (1945). Information and the accuracy attainable in the estimation of statistical parameters. *Bulletin of the Calcutta Mathematical Society*, 37, 81–91.
4. Čencov (Chentsov), N. N. (1982). *Statistical Decision Rules and Optimal Inference*. Translations of Mathematical Monographs, vol. 53. American Mathematical Society.
5. Benamou, J.-D., & Brenier, Y. (2000). A computational fluid mechanics solution to the Monge–Kantorovich mass transfer problem. *Numerische Mathematik*, 84, 375–393.
6. Jordan, R., Kinderlehrer, D., & Otto, F. (1998). The variational formulation of the Fokker–Planck equation. *SIAM Journal on Mathematical Analysis*, 29(1), 1–17.
7. Villani, C. (2009). *Optimal Transport: Old and New*. Grundlehren der mathematischen Wissenschaften, vol. 338. Springer.
8. Amari, S. (2016). *Information Geometry and Its Applications*. Applied Mathematical Sciences, vol. 194. Springer.

**The Wasserstein–Fisher–Rao synthesis and current research**
9. Kondratyev, S., Monsaingeon, L., & Vorotnikov, D. (2016). A new optimal transport distance on the space of finite Radon measures. *Advances in Differential Equations*, 21(11/12), 1117–1164.
10. Chizat, L., Peyré, G., Schmitzer, B., & Vialard, F.-X. (2018). An interpolating distance between optimal transport and Fisher–Rao metrics. *Foundations of Computational Mathematics*, 18, 1–44.
11. Chizat, L., Peyré, G., Schmitzer, B., & Vialard, F.-X. (2018). Unbalanced optimal transport: dynamic and Kantorovich formulations. *Journal of Functional Analysis*, 274(11), 3090–3123.
12. Liero, M., Mielke, A., & Savaré, G. (2018). Optimal entropy-transport problems and a new Hellinger–Kantorovich distance between positive measures. *Inventiones Mathematicae*, 211, 969–1117.
13. Gallouët, T., Ghezzi, R., & Vialard, F.-X. (2024). Regularity theory and geometry of unbalanced optimal transport. arXiv:2112.11056 (rev. 2024); *Journal of Functional Analysis* (2025).
14. Ito, S. (2024). Geometric thermodynamics for the Fokker–Planck equation: stochastic thermodynamic links between information geometry and optimal transport. *Information Geometry*, 7 (Suppl. 1), 441–483.
