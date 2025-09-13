# Universal Time and Tick Suppression: A Realistic Interpretation of Relativistic Effects

We present a realist reinterpretation of relativistic phenomena, *Universal Time and Tick Suppression*. Time is taken not as an observer–relative parameter but as a universal, dynamic axis: a smooth future-directed timelike field $\(U\)$ along which the total mass–energy of the universe advances. Effects usually described as “time dilation” are recast as *tick suppression*: a physical slowing of internal processes (clocks, decays) due to the energy cost of sustaining motion through space or persisting in gravitational fields. This energy–allocation mechanism is formalized as the *Inertial Suppression Principle*, providing a causal reading that is operationally equivalent to standard relativity while ontologically distinct. We also specify a light-based calibration of duration, using local MCIFs and $\(c\)$, that is independent of potentially suppressed clocks. The framework unifies kinematic and gravitational slowdowns under a single mechanism, preserves all empirical predictions, and offers a clear, absolute (yet physical) notion of time that clarifies puzzles of simultaneity without altering relativistic phenomenology.

---

## Repository Layout

- `paper.tex` — main LaTeX source  
- `Makefile` and/or `latexmkrc` — one-command builds  
- `LICENSE` — content license

---

## Quick Roadmap

1. **Universal time ($T$)** — A physical scalar that foliates an open domain $\mathcal U$ into slices $\Sigma_T$. 
    All systems share the same lapse $dT$ (absolute ordering of events).

2. **Moments \& interval** — A moment is an event $p=(T,\vec x)$. The universal interval is the fixed, path-independent $\Delta T=T_2-T_1$ (not the Minkowski metric interval).

3. **Light calibration** — Use light as the invariant standard: $\Delta t_{\text{univ}}=\Delta L_{\text{light}}/c$. On the chosen standard worldline, fix the gauge so $dT=d\tau$.

4. **Duration (what clocks record)** — Along any worldline $\gamma$,
  
   $d\tau = S, \dT, \qquad S \in [0,1]$.

   For ideal clocks, $S=\alpha(v,\Phi)$ (e.g., $\alpha(v)=\sqrt{1-v^2/c^2}$; in weak gravity: $\alpha(\Phi)\approx\sqrt{1+2\Phi/c^2}$).

6. **Tick suppression (mechanism)** — Motion and gravity reduce $S$: fewer ticks per unit $T$. Time $T$ does not slow; devices/processes do.

    \item \textbf{No ``deviation from $T$'' language} — Differences are encoded in $S$ 
    (conversion coefficient), not by leaving or tilting away from $T$.

    \item \textbf{Simultaneity \& frames} — Frame simultaneity is perspectival; 
    $T$-simultaneity is observer-independent. 
    Standard Lorentz transforms translate between observer grids and $(T,\vec X)$.

    \item \textbf{Twin paradox (resolution)} — Both twins share the same $\Delta T$; 
    the traveler accumulates fewer ticks: 
    $\Delta\tau_{\text{trav}}=\alpha(v)\,\Delta T$. 
    Aging difference comes from suppression, not ``time itself'' slowing.

    \item \textbf{Cosmological anchoring (optional)} — On FLRW scales, pick the CMB comoving 
    congruence $U^\mu$; then $T$ coincides (up to affine rescaling) with cosmic time.

    \item \textbf{Device factor (optional)} — Real clocks may have a material factor 
    $s_{\mathrm{tick}} \in (0,1]$ (imperfections). By default set $s_{\mathrm{tick}}=1$; 
    use it only when modeling non-ideal devices.

    \item \textbf{Scope \& locality} — All claims hold on a domain $\mathcal U$ 
    where $U^\mu$ is hypersurface-orthogonal and a $T$–foliation exists; 
    statements are local (MCIF) and GR-compatible.

    \item \textbf{Causality unchanged} — Light cones still govern influence; 
    a universal $\Delta T$ does not enable superluminal signaling.

---

## Build

**One-liner (recommended)**  
```bash
latexmk -pdf paper.tex
```
---

## How to cite

If you use this work, please cite:
**_Universal Time and Tick Suppression: A Realistic Interpretation of Relativistic Effects_**

- **Author:** Dickson A. Terrero  
- **ORCID:** https://orcid.org/0009-0005-4170-149X
- **Zeonodo:** https://doi.org/10.5281/zenodo.16936607

**BibTeX:**
```bibtex
@misc{terrero_dynamic_axis_2025,
  title        = {Universal Time and Tick Suppression: A Realistic Interpretation of Relativistic Effects},
  author       = {Terrero, Dickson A.},
  year         = {2025},
  howpublished = {Preprint},
  doi          = {10.5281/zenodo.16936606},
  primaryClass = {gen-ph},
  orcid        = {0009-0005-4170-149X}
}
```
