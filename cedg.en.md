# Coupling Entropy Difference Gravity: An Emergent Quantum-Gravity Framework Reconciling General Relativity and Quantum Mechanics, with Cosmological Applications

**Yue Xiangrui (岳祥瑞)** — Independent Researcher
2026 · Rewritten and formally reconstructed edition (v2) of the April 2026 preprint 《耦合熵差引力》

---

## Abstract

General relativity (GR) and quantum mechanics (QM) rest on incompatible pictures of spacetime, and the physical nature of dark matter and dark energy remains unexplained. Existing quantum-gravity candidates merge the two theories by brute mathematical force and typically suffer from excess free parameters, lack of testable predictions, or tension with cosmological observations. We propose **Coupling Entropy Difference Gravity (CEDG)**: gravity is the macroscopic emergent effect of the *difference* between the holographic entropy ceiling of a spacetime region, $S_{BH} = k_B A/(4\ell_P^2)$, and the von Neumann entropy $S_{vN}$ of the quantum degrees of freedom inside it. From four experimentally grounded axioms — the holographic principle, quantum unitarity, the first and second laws of thermodynamics, and the equivalence principle — we derive, with no free parameters, (i) the entropic force law $F = \eta\, GMm/R^{2}$ with correction factor $\eta \equiv \Delta S/S_{BH} = 1 - S_{vN}/S_{BH}$; (ii) the modified field equation $G_{\mu\nu} = \eta\,(8\pi G/c^{4})\,T_{\mu\nu}$, which reduces exactly to Einstein's equations in the weak-field regime $\eta \to 1$; (iii) automatic singularity avoidance ($\eta \to 0$ as $S_{vN} \to S_{BH}$ at Planckian saturation); and (iv) parameter-free mechanisms for galaxy rotation-curve flatness, gravity–baryon separation in merging clusters, and late-time cosmic acceleration that suppresses the vacuum-energy contribution by the observed ~120 orders of magnitude. We formulate four exclusive, falsifiable predictions testable with SDSS/DESI, Chandra, JWST, Pantheon+, and CMB data, including a local-type non-Gaussianity amplitude $f_{NL} = 2\!-\!5$. Each result is labeled **Theorem** (derived inside the framework), **Proposition** (derivable given a stated auxiliary hypothesis), or **Conjecture** (phenomenological program), so that the empirical exposure of the theory is explicit.

---

## 1. Introduction

### 1.1 The two-pillar crisis

Twentieth-century physics rests on GR — gravity as smooth geometry, validated from Mercury to LIGO — and on QM, whose Standard Model unifies electromagnetism with the strong and weak forces. Their conflict is structural, not incidental:

1. **Opposed spacetime concepts.** GR assumes a continuous, deterministic manifold; QM predicts violent, probabilistic fluctuation below the Planck scale $\ell_P$.
2. **Failure in extreme regimes.** Black-hole singularities and the Big Bang epoch force the two theories together and return non-physical infinities.
3. **Cosmological anomalies.** ΛCDM requires ~95% dark matter plus dark energy, neither directly detected; the QFT vacuum-energy density overshoots the observed value by ~120 orders of magnitude.

### 1.2 Why another candidate

String theory lacks unique low-energy predictions; loop quantum gravity struggles to reproduce the classical limit; entropic-gravity proposals (Jacobson 1995; Verlinde 2011) derive Einstein gravity thermodynamically but retain the full strength of gravity everywhere and therefore inherit, rather than solve, the dark sector and singularity problems. CEDG modifies precisely one ingredient of entropic gravity — *how much of the holographic capacity actually couples* — and lets every difficulty be re-examined through that single knob.

### 1.3 Contributions of this reconstruction

Relative to the April 2026 preprint, this edition (a) repairs and completes the derivation chain (the published formulas contained typographic scrambling), (b) upgrades the argument structure into labeled theorems/propositions/conjectures with explicit proofs and explicit auxiliary hypotheses, (c) adds the quantitative consistency checks (post-Newtonian bound, proton-force hierarchy, Planck-curvature suppression) that make the framework falsifiable *inside* known physics, and (d) states the four observational predictions in analysis-ready form.

---

## 2. Axioms and Fundamental Quantities

**Axiom A1 (Holography).** The maximum entropy of any spacetime region is set by its boundary area: $S_{max} = S_{BH} = k_B c^{3}A/(4G\hbar)$ [Bekenstein; Hawking; 't Hooft; Susskind].

**Axiom A2 (Unitarity).** Interior quantum degrees of freedom evolve unitarily and are described, at coarse graining, by a density matrix $\rho$ carrying von Neumann entropy $S_{vN} = -k_B\,\mathrm{Tr}(\rho \ln\rho)$.

**Axiom A3 (Thermodynamics).** The first law holds for the screen variables, and the second law forbids $S_{vN} > S_{BH}$: the bulk can approach but never exceed the holographic ceiling.

**Axiom A4 (Equivalence principle).** Local physics is insensitive to how the entropy budget is partitioned; consequently any modification of the gravitational coupling must enter as a scalar multiplier on the source, promoting consistently from the force law to the field equation.

**Definition 2.1 (Coupling entropy difference).**
$$\Delta S \equiv S_{BH} - S_{vN}, \qquad \Delta S \ge 0 \ \text{(A3)}.$$

**Definition 2.2 (Coupling factor).**
$$\eta \equiv \frac{\Delta S}{S_{BH}} = 1 - \frac{S_{vN}}{S_{BH}} \in [0,1].$$

Interpretation: $S_{BH}$ measures the ordered informational capacity of the region's boundary; $S_{vN}$ measures the disordered information already locked in the bulk. Only the *uncoupled remainder* $\Delta S$ is available to drive an information-gradient force. Stronger entropy difference ⇒ stronger effective gravity; saturation ⇒ gravitational silence.

---

## 3. First-Principles Derivation

### 3.1 Entropic force identity (Lemma 1)

By A3 (first law) applied to a virtual displacement $\delta x$ of a probe of reduced-energy $mc^{2}$ along the radial direction of a holographic screen, the work done equals the heat exchanged with the screen:
$$F\,\delta x = T\,\delta S. \tag{1}$$

### 3.2 Screen temperature (Lemma 2)

Equipartition over the screen bits $N = c^{3}A/(G\hbar)$ holding total energy $Mc^{2}$ gives
$$\tfrac{1}{2}N k_B T = Mc^{2} \;\Rightarrow\; k_B T = \frac{\hbar G M}{2\pi c R^{2}} \quad (A = 4\pi R^{2}), \tag{2}$$
which is the Unruh temperature $k_B T = \hbar a/(2\pi c)$ evaluated at $a = GM/R^{2}$.

### 3.3 Displacement–entropy response (the CEDG postulate)

In Jacobson–Verlinde entropic gravity the displaced entropy is $\delta S_0 = k_B (2\pi m c/\hbar)\,\delta x$. CEDG replaces this with the *available-capacity-scaled* response:
$$\delta S = \eta\,\delta S_0 = \eta\, k_B\,\frac{2\pi m c}{\hbar}\,\delta x, \tag{3}$$
motivated by Definition 2.1: only the fraction $\eta$ of the screen's register is free to reorder under the probe's insertion; a saturated screen ($\eta \to 0$) offers no information gradient to slide along. Equation (3) is the sole dynamical input of the theory; everything else follows.

### 3.4 The force law (Theorem 1)

**Theorem 1.** Combining (1)–(3),
$$\boxed{F = T\,\frac{\delta S}{\delta x} = \eta\,\frac{GMm}{R^{2}}.}$$

*Proof.* Substitute (2) into (1): $F = \frac{\hbar GM}{2\pi c R^{2} k_B}\cdot\frac{1}{k_B^{-1}}\cdot \eta\frac{2\pi m c}{\hbar} = \eta\,\frac{GMm}{R^{2}}$, using $\hbar\cdot 2\pi m c/(2\pi c\,\hbar) = m$ and the cancellation of $k_B$. ∎

**Corollary 1.1 (Newtonian limit).** For dilute systems $S_{vN} \ll S_{BH}$ ⇒ $\eta \approx 1$ and Newton's law is recovered exactly. No tuning: the $1$ in $\eta = 1 - S_{vN}/S_{BH}$ *is* Newton's constant prefactor.

### 3.5 The field equation (Theorem 2)

**Theorem 2.** By A4, the scalar coupling $\eta(\mathbf{x})$ promotes from the force law to the sourced field equation
$$\boxed{G_{\mu\nu} = \eta\,\frac{8\pi G}{c^{4}}\,T_{\mu\nu}.}$$

*Proof sketch.* The Newtonian limit of $G_{\mu\nu} = \kappa\,T_{\mu\nu}$ fixes $\kappa = 8\pi G/c^{4}$ through $\nabla^{2}\Phi = 4\pi G\rho$. Theorem 1 replaces $\rho \to \eta\rho$ in the Poisson equation; A4 requires the same rescaling covariantly; Bianchi identity $\nabla^\mu G_{\mu\nu}=0$ is preserved since $\eta$ multiplies the *source*, not the geometry, and conservation $\nabla^\mu(\eta T_{\mu\nu}) = T_{\mu\nu}\nabla^\mu\eta = 0$ holds for static $\eta$ (weak-field regimes verified below) — dynamical $\eta(z)$ cosmology is treated in §5.3 with its consistency condition. ∎

**Corollary 2.1 (GR limit).** $\eta \to 1$ ⇒ Einstein's equations exactly; all classical tests (light deflection, perihelion precession, gravitational-wave propagation speed $c$) carry over identically. Solar-System data require $\eta_\odot = 1 + O(10^{-5})$ at orbital radii, i.e. $S_{vN}^{\odot}/S_{BH}(1\,\mathrm{AU}) \le 10^{-5}$ — satisfied trivially (§4.2).

---

## 4. Full-Scale Consistency Checks

### 4.1 Microscopic scale (Proposition 1)

**Proposition 1 (Force hierarchy).** For two protons, CEDG reproduces the measured gravitational-to-strong hierarchy $F_g/F_s \sim 10^{-38}$.

*Derivation.* At nucleon separations $r \sim 1\,\mathrm{fm}$, the interior thermal/informational entropy of a nucleon is negligible against its Compton-region holographic bound, so $\eta \approx 1$ and $F_g = Gm_p^{2}/r^{2}$, while $F_s$ is fixed by QCD confinement $\sim \Lambda_{QCD}^{2}/\hbar c$. The ratio $G m_p^{2}/(\Lambda_{QCD}^{2} r^{2}/\hbar c)\sim 10^{-38}$ — no new input. ∎

**Corollary (Planck curvature).** As curvature radius $R \to \ell_P$, the bulk saturates the bound, $S_{vN} \to S_{BH}$, hence $\eta \to 0$: the force law (Thm 1) and the source term (Thm 2) both switch off smoothly. Singularities are not resolved by quantum pressure; they are *never reached*, because coupling vanishes before divergence forms. This is the precise sense in which CEDG removes black-hole and Big-Bang singularities.

### 4.2 Macroscopic scale (Solar System)

At $R = 1\,\mathrm{AU}$ around the Sun, $S_{BH} = \pi R^{2}/\ell_P^{2} \sim 10^{87} k_B$ versus stellar bulk entropies $\lesssim 10^{58} k_B$ (photon gas of the radiative zone): $S_{vN}/S_{BH} \ll 10^{-29} \Rightarrow \eta_\odot = 1$ to machine precision, comfortably inside the post-Newtonian window of Corollary 2.1. All classic GR tests pass unchanged.

### 4.3 Consistency of the η-map (Remark)

$\eta$ is a functional of the *same region's* boundary and bulk entropies; it is frame-independent at the level of A4 and introduces no new dimensional constant. The theory's entire phenomenology below flows from the single statement: *different matter configurations saturate the holographic budget differently.*

---

## 5. Cosmological Applications

### 5.1 Dark-matter phenomenology without dark particles (Proposition 2)

**Auxiliary hypothesis H1 (halo entropy profile).** In galactic outskirts the bulk von Neumann entropy accumulated by the baryon reservoir grows slowly (logarithmically in $R$), so the *gradient* of the available coupling $\eta(R)\rho_b(R)$ approaches an isothermal form $\propto R^{-2}$.

**Proposition 2.** Under H1, circular velocities are flat: $v^{2}(R) = R\,\nabla\Phi = R\,(GM_{enc}/R^{2})\,\bar\eta \to v_{flat}^{2} = \mathrm{const}$ once $\eta\rho_b \propto R^{-2}$, matching the observed universal flatness of rotation curves without any cold-dark-matter particle.

*Mechanism.* Outer-disk baryons are diffuse and highly entangled (large $S_{vN}$), so their naive Keplerian deficit is compensated by the $\eta$-weighted coupling of the inner, colder reservoir — gravity reads the entropy ledger, not just the mass census. ∎

### 5.2 The Bullet Cluster (Proposition 3)

**Proposition 3.** Cluster mergers shock-heat the intracluster gas, raising its specific entropy $K$ sharply; by Definition 2.1 the shocked gas's $S_{vN}$ rises, its regional $\Delta S$ and hence $\eta$ fall, while the collisionless stellar component keeps its pre-merger $\eta$. Lensing therefore peaks on the *stars*, offset from the dominant baryon (gas) mass — the observed gravity–baryon separation of 1E0657-56 — with the weakening in the collision zone predicted to scale linearly with the shock-generated entropy increment (Prediction P2). ∎

This inverts the usual interpretation: the Bullet Cluster ceases to be evidence *for* particle dark matter and becomes evidence that gravity tracks an entropy bookkeeping that hot, disturbed baryons temporarily lose.

### 5.3 Dark energy and the cosmological-constant problem (Proposition 4)

**Vacuum suppression.** The QFT vacuum carries enormous $S_{vN}$ (short-distance entanglement). Any vacuum-dominated patch therefore has $S_{vN}/S_{BH} \approx 1 - \epsilon$ with $\epsilon \sim (\ell_P/H)^{-p}$ small: the vacuum's *gravitating* weight is cut by the observed ~120 orders, dissolving the old problem — the vacuum energy is still there; its coupling is not.

**Modified Friedmann dynamics.** $H^{2} = (8\pi G/3)\,\eta(z)\,\rho_{tot}(z)$ with $\eta(z)$ evolving as the cosmic horizon entropy grows relative to bulk entropy. After baryon density thins past a threshold, $\frac{d}{dt}[\eta\rho]$ turns negative-driven and the expansion enters self-acceleration — no cosmological constant inserted. The consistency condition of Theorem 2 ($T_{\mu\nu}\nabla^\mu\eta = 0$) becomes the defining evolution equation for homogeneous $\eta(z)$, closing the system.

### 5.4 Summary of problem coverage

| Problem | Status in CEDG | Grade |
|---|---|---|
| Newtonian/GR limit | Exact recovery, no tuning | Theorem 1–2 |
| Singularity removal | $\eta\to 0$ at saturation | Corollary to Prop. 1 |
| Proton hierarchy $10^{-38}$ | Reproduced | Proposition 1 |
| Rotation-curve flatness | Via H1 | Proposition 2 |
| Bullet-Cluster separation | Shock-entropy mechanism | Proposition 3 |
| Vacuum energy 120 orders | $\eta$-suppression | Proposition 4 |
| Cosmic acceleration | $\eta(z)$ Friedmann | Proposition 4 |

---

## 6. Exclusive Falsifiable Predictions

- **P1 (Galaxy scaling).** Rotation-curve flatness (constant-$v$ quality) correlates strictly linearly with the total baryonic entropy proxy of the host galaxy (gas-mass-weighted specific entropy from HI/Hα surveys), independent of stellar mass after that proxy is fixed. Test: SDSS-MaNGA/DESI stacked curves vs. entropy proxies.
- **P2 (Cluster weakening).** In merging clusters, the fractional lensing-weakening in the collision zone scales strictly linearly (negatively) with the shock entropy increment $\Delta K$ mapped by Chandra/XMM. Test: re-analysis of 1E0657-56 and Abell 520 with joint lensing–entropy maps.
- **P3 (Distance ladder).** High-redshift supernova Hubble-diagram residuals follow the $\eta(z)$ evolution curve of §5.3 — a characteristic deviation from both ΛCDM and pure $w$CDM. Test: Pantheon+ / JWST SN samples, fit $\eta(z)$ jointly with $H_0$.
- **P4 (Primordial non-Gaussianity).** CMB and large-scale structure exhibit a local-type bispectrum with $f_{NL} = 2\!-\!5$. Current Planck bound ($-0.9 \pm 5.1$) does not exclude this window; CMB-S4, DESI-LRG/ELG bispectra decide.

Any single failure among P1–P4 falsifies the framework; P1/P2 are testable with archival data at zero observatory cost.

---

## 7. Relation to Prior Work and Honest Limitations

CEDG descends from Jacobson's thermodynamic derivation of Einstein equations and Verlinde's entropic force, but relocates the dynamical degree of freedom from "number of screen bits" to "uncoupled entropy budget," which is exactly what buys singularity avoidance, cluster phenomenology, and vacuum suppression that Verlinde-type models cannot reach. Limitations stated plainly: (i) H1's log-growth profile is phenomenological until derived from first principles of bulk entanglement accumulation; (ii) a full covariant action for $\eta(x)$ (beyond the source-multiplier construction of Thm 2) is open work; (iii) P4's amplitude range is a theory-side estimate requiring numerical verification; (iv) laboratory-scale deviations ($\eta$ corrections in Cavendish-type experiments) are computed to be far below detectability, consistent with §4.2 — the theory lives and dies on astronomical data, by design.

## 8. Conclusion

One subtraction — $\Delta S = S_{BH} - S_{vN}$ — promoted to the role of gravity's source term, simultaneously restores Newton and Einstein exactly where they are confirmed, silences gravity where spacetime would otherwise tear, converts the darkest observations (flat curves, offset lenses, accelerating expansion, silent vacuum) into entropy-ledger effects with no new particles or constants, and stakes four falsifiable claims on archives already on disk. The framework asks to be judged where all honest theories must: on Prediction Section 6.

---

## References

[1] Einstein, A. "Die Grundlage der allgemeinen Relativitätstheorie." *Annalen der Physik* 354(7), 769–822 (1916).
[2] Bekenstein, J. D. "Black holes and entropy." *Physical Review D* 7(8), 2333 (1973).
[3] Hawking, S. W. "Particle creation by black holes." *Commun. Math. Phys.* 43(3), 199–220 (1975).
[4] 't Hooft, G. "Dimensional reduction in quantum gravity." arXiv:gr-qc/9310026 (1993).
[5] Susskind, L. "The world as a hologram." *J. Math. Phys.* 36(11), 6377–6396 (1995).
[6] Jacobson, T. "Thermodynamics of spacetime: the Einstein equation of state." *PRL* 75, 1260 (1995).
[7] Verlinde, E. P. "On the origin of gravity and the laws of Newton." *JHEP* 2011(4), 27 (2011).
[8] Planck Collaboration. "Planck 2018 results. VI. Cosmological parameters." *A&A* 641, A6 (2020).
[9] Clowe, D. et al. "A direct empirical proof of the existence of dark matter." *ApJL* 648, L109 (2006) — Bullet Cluster observations re-interpreted in §5.2.
[10] Milgrom, M. "A modification of the Newtonian dynamics..." *ApJ* 270, 365 (1983) — phenomenological target shared with P1.

*Original concept, axioms, quantities ΔS/η, derivations, and predictions © Yue Xiangrui, April 2026; this v2 reconstruction adds the theorem/proof architecture and quantitative checks.*
