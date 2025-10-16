---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://raw.githubusercontent.com/xing-phys/Group-Seminar-QPME/refs/heads/main/assets/title_figure.png # some information about your slides (markdown enabled)
title: Pontus-Mpemba Effect in Resource Theory
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
hideInToc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# Pontus-Mpemba Effect in Resource Theory

Thursday's seminar


<!-- <v-drag pos="345,422,320,129">
<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>
</v-drag> -->

<v-drag pos="318,402,313,116">
  <LightOrDark>
    <template #dark>
      <img src="/assets/logo-white.png" alt="Dark mode figure" />
    </template>
    <template #light>
      <img src="/assets/logo-white.png" alt="Light mode figure" />
    </template>
  </LightOrDark>
</v-drag>

<v-drag pos="426,344,135,44">
Ze-Yu, Xing
</v-drag>


<div class="abs-br m-6 text-xl">
  <a href="https://github.com/xing-phys/Group-Seminar-QME" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: default
hideInToc: true
---

# Table of Contents

<style>
.toc-container {
  column-count: 2;
  column-gap: 1rem;
}
.toc-container ul {
  list-style-type: none;
  padding-left: 0;
  margin: 0;
}
.toc-container li {
  break-inside: avoid; /* Prevents list items from breaking across columns */
  margin-bottom: 0.5rem;
}
</style>

<div class="toc-container">
  <Toc />
</div>

---
transition: fade
dragPos:
  bib: 647,495,329,62
---

# Pontus-Mpemba Effect

**Protocol**

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

A. Nava and R. Egger, [Phys. Rev. Lett. **135**, 140404 (2025)](https://link.aps.org/doi/10.1103/hhgj-89gj)

</span>
</v-drag>

<v-drag pos="216,150,315,223">
<img src="/assets/sketch.svg"/>
</v-drag>

<v-click>

<v-drag pos="593,251,197,65">
  <span style="font-size: 20px;">

$$
t_{\text{SI}} + t_{\text{IF}} < t_{\text{SF}}
$$

  </span>
</v-drag>

</v-click>

---
transition: fade
level: 2
dragPos:
  bib: 647,495,329,62
---

# Framework

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

A. Nava and R. Egger, [Phys. Rev. Lett. **135**, 140404 (2025)](https://link.aps.org/doi/10.1103/hhgj-89gj)

</span>
</v-drag>

<v-click>

<v-drag pos="52,88,556,144">
  <span style="font-size: 20px;">

Lindblad equation:
$$
\frac{\mathrm{d}\rho}{\mathrm{d}t} = -i [H, \rho] + \sum_{m, n=1}^{N^{2}-1}C_{mn} \left( F_{m}\rho F^{\dagger}_{n} - \frac{1}{2} \left\{ F^{\dagger}_{n}F_{m}, \rho \right\}  \right) 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="74,263,373,87">
  <span style="font-size: 20px;">

$\left\{ F_{m} \right\}$: traceless. Kossakowski matrix $C$: positive semidefinite.

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="521,303,414,87">
  <span style="font-size: 20px;">

$$
\mathcal{D}_{T}[\rho_{1}, \rho_{2}] = \frac{1}{2}\mathrm{Tr}\lvert \rho_{1}-\rho_{2} \rvert = \frac{1}{2} \sum_{i} \lvert \lambda_{i} \rvert 
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="556,238,349,77">
  <span style="font-size: 20px;">

Monitoring function: $\mathcal{D}_{T}[\rho(t), \rho_{F}]$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="190,404,504,69">
  <span style="font-size: 20px;">

Convergence: cutoff $\varepsilon \ll 1$, for $t > t_{c}$, $\mathcal{D}_{T}[\rho(t_{c}), \rho _\text{F}] \leq \varepsilon$.

  </span>
</v-drag>

</v-click>

---
level: 2
dragPos:
  bib: 647,495,329,62
transition: fade
---

# Classification

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

A. Nava and R. Egger, [Phys. Rev. Lett. **135**, 140404 (2025)](https://link.aps.org/doi/10.1103/hhgj-89gj)

</span>
</v-drag>

<v-drag pos="699,31,252,188">
<img src="/assets/sketch.svg"/>
</v-drag>

<v-click>

<v-drag pos="63,79,214,65">
  <span style="font-size: 16px;">

Trajectories $\Gamma _\text{SF}$ and $\Gamma _\text{SA}$.

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="44,137,497,405">
  <span style="font-size: 16px;">

- Case 1:
$$
\begin{aligned}
\partial_{t} \mathcal{D}_{T} [\rho^{(\text{A})}(t=0), \rho _\text{F}] &< 0 \\
\exists t_{M} > 0 \, \vert \, \partial_{t} \mathcal{D}_{T}[\rho^{(\text{A})}(t=t_{M} + 0^{+}), \rho _\text{F}] & >0
\end{aligned}
$$
- Case 1.1:

$$
\partial_{t} \mathcal{D}_{T}[\rho^{(\text{A})}(t=0), \rho_{\text{F}}] > \partial_{t} \mathcal{D}_{T}[\rho^{(\text{F})}(t=0), \rho_{\text{F}}]
$$

- Case 1.2:

$$
\partial_{t} \mathcal{D}_{T}[\rho^{(\text{F})}(t=0), \rho_{\text{F}}] < \partial_{t} \mathcal{D}_{T}[\rho^{(\text{F})}(t=0), \rho _\text{F}]
$$

- Case 2:

$$
\partial_{t}\mathcal{D}_{T}[\rho^{(\text{A})}(t=0), \rho_{\text{F}}]> 0
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="522,193,429,324">
  <span style="font-size: 16px;">

General PME classification:

- Weak type A PME:
$$
\mathcal{D}_{T}[\rho^{(\text{A})}(t_\text{SI}), \rho_{\text{F}}] < \mathcal{D}_{T}[\rho^{(\text{F})}(t_\text{SI}), \rho_{\text{F}}]
$$
- Weak type B PME:
$$
\mathcal{D}_{T}[\rho _\text{S}, \rho _\text{F}] > \mathcal{D}_{T}[\rho^{(\text{A})}(t_\text{SI}), \rho_{\text{F}}] > \mathcal{D}_{T}[\rho^{(\text{F})}(t_\text{SI}, \rho_{\text{F}})]
$$
- Strong PME:
$$
\mathcal{D}_{T}[\rho^{(\text{A})}(t_\text{SI}), \rho_{\text{F}}] > \mathcal{D}_{T}[\rho _\text{S}, \rho _\text{F}] > \mathcal{D}_{T}[\rho^{(\text{F})}(t_\text{SI}, \rho_{\text{F}})]
$$

  </span>
</v-drag>

</v-click>

---
level: 2
dragPos:
  bib: 647,495,329,62
transition: fade
---

# Two-level systems

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

A. Nava and R. Egger, [Phys. Rev. Lett. **135**, 140404 (2025)](https://link.aps.org/doi/10.1103/hhgj-89gj)

</span>
</v-drag>

<v-click>

<v-drag pos="97,79,105,68">
  <span style="font-size: 18px;">

$F_{n} \to \sigma_{n}$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="94,147,257,136">
  <span style="font-size: 18px;">

State
$$
\rho(t) = \frac{1}{2} \left[ \mathbb{1} + \sum_{n}r_{n}(t)\sigma_{n} \right]
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="86,307,338,96">
  <span style="font-size: 18px;">
Hamiltonian

$$
H = \sum_{n} h_{n} \sigma_{n}, \quad \boldsymbol{h} = (h_{1}, h_{2}, h_{3})^{T}
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="428,29,238,166">
  <span style="font-size: 18px;">

Kossakowski matrix
$$
C = \begin{pmatrix}
C_{11}  & C_{12} & C_{31}^{\ast} \\
C_{12}^{\ast} & C_{22} & C_{23} \\
C_{31} & C_{23}^{\ast} & C_{33}
\end{pmatrix}
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="708,96,224,69">
  <span style="font-size: 18px;">

$$
\dot{\boldsymbol{r}} = \boldsymbol{v}(\boldsymbol{r}) = 2 \Lambda \cdot \boldsymbol{r} + \boldsymbol{b}
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="91,405,798,105">
  <span style="font-size: 18px;">

$$
\mathcal{L} = - i (H \otimes \mathbb{1} - \mathbb{1} \otimes H^{T}) + \sum_{m,n=1}^{3}C_{mn}\left[ (\sigma_{m} \otimes \sigma_{n}^{T}) - \frac{1}{2} (\sigma_{n}\sigma_{m}\otimes \mathbb{1}) - \frac{1}{2}(\mathbb{1} \otimes \sigma_{m}^{T}\sigma_{n}^{T}) \right]
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="426,190,528,225">
  <span style="font-size: 18px;">

$$
\Lambda = \begin{pmatrix}
-C_{22} - C_{33} & -h_{3} + \mathrm{Re}C_{12} & h_{2} + \mathrm{Re} C_{31} \\
h_{3} + \mathrm{Re} C_{12} & -C_{11} - C_{33} & -h_{1} + \mathrm{Re} C_{23} \\
-h_{2} + \mathrm{Re} C_{31} & h_{1} + \mathrm{Re} C_{23} & -C_{11} - C_{22}
\end{pmatrix}
$$
$$
\boldsymbol{b} = -4 \mathrm{Im} (C_{23}, C_{31}, C_{12})^{T}
$$
$$
\mathcal{D}_{T}[\rho_{1}, \rho_{2}] = \frac{1}{2} \lvert \boldsymbol{r}_{1} - \boldsymbol{r}_{2} \rvert
$$
  </span>
</v-drag>

</v-click>

---
level: 2
dragPos:
  bib: 647,495,329,62
---

# Two-level systems

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

A. Nava and R. Egger, [Phys. Rev. Lett. **135**, 140404 (2025)](https://link.aps.org/doi/10.1103/hhgj-89gj)

</span>
</v-drag>

<v-drag pos="11,99,266,423">
<img src="/assets/f1.png"/>
</v-drag>

<v-drag pos="281,105,267,427">
<img src="/assets/f2.png"/>
</v-drag>

<v-drag pos="543,105,266,423">
<img src="/assets/fA1.png"/>
</v-drag>

<v-drag pos="757,214,266,166,90">
<img src="/assets/fA2.png"/>
</v-drag>

<v-click>

<v-drag pos="441,35,408,66">
  <span style="font-size: 16px;">

$$
\mathrm{Im} C_{12} = -h_{12} + \mathrm{Re} C_{31} = h_{1} + \mathrm{Re} C_{23} = 0
$$

  </span>
</v-drag>

</v-click>

---
transition: fade
dragPos:
  bib: 784,489,195,62
---

# Quantum Resource Theory

<v-drag pos="66,195,423,340">
<img src="/assets/schematic_square.png"/>
</v-drag>

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

S. Aditya _et al._, [arXiv:2509.22176](http://arxiv.org/abs/2509.22176)

</span>
</v-drag>

<v-drag pos="530,6,450,255">
  <span style="font-size: 18px;">

**Quantum Resource Theory**: Nonclassical features

 - free states ($\mathcal{F}_s$): prepared w/o cost

 - free operations ($\mathcal{F}_O$): resource non-generation

 - Resource monotones $M(\rho)$:
  $M(\rho) = 0 \, \forall \rho \in \mathcal{F}_{s}$, $M(\Lambda(\rho)) \leq M(\rho) \, \forall \Lambda \in \mathcal{F}_{O}$

  </span>
</v-drag>

<v-drag pos="526,211,450,304">
  <span style="font-size: 18px;">

**Quantum Mpemba Effect**: local resource content can be dissipated faster when the initial state is more resourceful

**Pontus Mpemba Effect**:

 - heating process $\tilde{U}$, free evolution $U$

 - $M(\tilde{\rho}(T)) > M(\rho(T))$

 - $\exists \tau \, \vert \, M(\tilde{\rho}(T+ \tau)) < M(\rho(T+\tau))$

  </span>
</v-drag>

<v-drag pos="273,75,231,66">
<v-click>
  <span style="font-size: 16px; color: rgb(155, 155, 155);">

$$
\ket{\Psi_{O}(\theta)} = e^{ -i \theta \sum_{i} O_{i} } \ket{0} ^{\otimes N} 
$$

  </span>
</v-click>
</v-drag>

<v-drag pos="264,106,279,95">
<v-click>
  <span style="font-size: 16px; color: rgb(155, 155, 155);">

$$
U_{t} = \prod_{s=1}^{t}u_{s}, \quad u_{s} = \prod_{x \in \mathcal{B}_{s}} u_{s, x, x+1}
$$

  </span>
</v-click>
</v-drag>

<v-drag pos="64,73,204,67">
<v-click>
  <span style="font-size: 16px; color: rgb(155, 155, 155);">

$$
u_{s, x, x+1} \sim \mathcal{G} \subset \mathcal{U}_\text{free}
$$

  </span>
</v-click>
</v-drag>

<v-drag pos="98,121,151,70">
<v-click>
  <span style="font-size: 16px; color: rgb(155, 155, 155);">

  - $\epsilon$: $u_{s,x,x+1}$
  - $1-\epsilon$: $\mathbb{1}_{x, x+1}$

  </span>
</v-click>
</v-drag>

---
level: 2
dragPos:
  bib: 784,489,195,62
transition: fade
---

# Coherence

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

S. Aditya _et al._, [arXiv:2509.22176](http://arxiv.org/abs/2509.22176)

</span>
</v-drag>

<v-drag pos="67,78,230,227">
<img src="/assets/Coherence_ED_linear_scale_L20_Ferro_PEpres.png"/>
</v-drag>

<v-drag pos="67,297,241,224">
<img src="/assets/Coh_PME_AB_heating.png"/>
</v-drag>

<v-drag pos="514,242,279,74">
  <span style="font-size: 18px;">

$$
\ket{\Psi_{Y}(\theta)} = e^{ -i \frac{\theta}{2}\sum_{i}Y_{i} }\ket{0} ^{\otimes N}
$$

  </span>
</v-drag>

<v-drag pos="353,35,247,76">
  <span style="font-size: 18px;">

$$
C(\rho_{A}) = S(\rho^{D}_{A}) - S(\rho_{A})
$$

  </span>
</v-drag>

<v-drag pos="373,97,239,66">
  <span style="font-size: 18px;">

$$
S(\rho) = -\mathrm{Tr}(\rho \log_{2}\rho)
$$

  </span>
</v-drag>

<v-drag pos="605,94,303,69">
  <span style="font-size: 18px;">

$$
\rho^{D}_{A} = \sum_{z} \braket{ z | \rho_{A} | z } \ket{z} \bra{z}
$$

  </span>
</v-drag>

<v-drag pos="333,152,355,106">
  <span style="font-size: 18px;">

$$
u = \exp \left[ -i \sum_{a,b=0}^{1}\alpha_{a,b} Z^{a} \otimes Z^{b} \right]S
$$

  </span>
</v-drag>

<v-drag pos="702,176,254,70">
  <span style="font-size: 16px;">

$0< \alpha_{a,b}\leq 2\pi$, $S = \mathbb{1}$ or SWAP

  </span>
</v-drag>

<v-drag pos="365,310,340,97">
  <span style="font-size: 18px;">

**Preheating**: Haar-random circuits
$$
\ket{\tilde{\Psi}} = \tilde{U}^{A}_{t} \otimes \tilde{U}^{B}_{t}\ket{\Psi(\theta)} 
$$

  </span>
</v-drag>

<v-drag pos="653,336,232,107">
  <span style="font-size: 18px;">

$$
\tilde{U}^{A / B}_{t} = \prod_{s=1}^{t}\tilde{u}^{A/B}_{s}
$$

  </span>
</v-drag>

<v-drag pos="415,419,406,78">
  <span style="font-size: 18px;">

$$
\tilde{u}^{J}_{s} = \prod_{x \in \mathcal{B}^{J}_{s}}\tilde{u}_{s, x, x+1}, \quad J = A, B, \quad \mathcal{B}^{J}_{s} = \mathcal{B}_{s} \cap J
$$

  </span>
</v-drag>

---
transition: fade
level: 2
dragPos:
  bib: 784,489,195,62
---

# Imaginarity

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

S. Aditya _et al._, [arXiv:2509.22176](http://arxiv.org/abs/2509.22176)

</span>
</v-drag>

<v-drag pos="387,59,400,206">
  <span style="font-size: 18px;">

$$
\mathcal{I}(\rho) = S(\mathrm{Re}(\rho)) - S(\rho)
$$
$$
u = \exp[-i \alpha (X\otimes Y - Y \otimes X) / 2]
$$
$$
\alpha \in [0, 2\pi]
$$
$$
\ket{\Psi_{X}(\theta)} = e^{ -i \frac{\theta}{2}\sum_{j}X_{j}}\ket{0} ^{\otimes N} 
$$

  </span>
</v-drag>

<v-drag pos="365,310,340,97">
  <span style="font-size: 18px;">

**Preheating**: Haar-random circuits
$$
\ket{\tilde{\Psi}} = \tilde{U}^{A}_{t} \otimes \tilde{U}^{B}_{t}\ket{\Psi(\theta)} 
$$

  </span>
</v-drag>

<v-drag pos="653,336,232,107">
  <span style="font-size: 18px;">

$$
\tilde{U}^{A / B}_{t} = \prod_{s=1}^{t}\tilde{u}^{A/B}_{s}
$$

  </span>
</v-drag>

<v-drag pos="415,419,406,78">
  <span style="font-size: 18px;">

$$
\tilde{u}^{J}_{s} = \prod_{x \in \mathcal{B}^{J}_{s}}\tilde{u}_{s, x, x+1}, \quad J = A, B, \quad \mathcal{B}^{J}_{s} = \mathcal{B}_{s} \cap J
$$

  </span>
</v-drag>

<v-drag pos="74,79,261,238">
<img src="/assets/Imag_resource_L20_Ferro.png">
</v-drag>

<v-drag pos="72,308,268,244">
<img src="/assets/Imag_PME_AB_heating.png">
</v-drag>

---
transition: fade
level: 2
dragPos:
  bib: 784,489,195,62
---

# Fermionic Non-Gaussianity

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

S. Aditya _et al._, [arXiv:2509.22176](http://arxiv.org/abs/2509.22176)

</span>
</v-drag>

<v-drag pos="567,24,265,62">
  <span style="font-size: 16px;">

$$
\mathcal{NG}(\rho_{A}) = S_{\mathcal{G}} (\rho_{A}) - S(\rho_{A})
$$

  </span>
</v-drag>

<v-drag pos="325,75,298,94">
  <span style="font-size: 16px;">

$$
S_{\mathcal{G}}(\rho_{A}) = \sum_{j=1}^{N_{A}} H \left( \frac{1 + \lambda_{j}}{2} \right) 
$$

  </span>
</v-drag>

<v-drag pos="643,118,258,55">
  <span style="font-size: 12px;">

$$
H(x) = -x \log_{2}x - (1-x) \log_{2}(1-x)
$$

  </span>
</v-drag>

<v-drag pos="645,76,264,63">
  <span style="font-size: 12px;">

$\lambda_{j}\geq 0$: non-negative eigenvalues of $M(\rho_{A})$:

  </span>
</v-drag>

<v-drag pos="345,157,266,86">
  <span style="font-size: 16px;">

$$
M_{a, b}(\rho_{A}) = - \frac{i}{2} \mathrm{Tr}(\rho_{A} [\gamma_{a}, \gamma_{b}])
$$

  </span>
</v-drag>

<v-drag pos="662,180,308,95">
  <span style="font-size: 12px;">

$$
\gamma_{2m-1} = \left( \prod_{i=1}^{m-1} Z_{i} \right)X_{m}, \quad \gamma_{2m} = \left( \prod_{i=1}^{m-1} Z_{i} \right)Y_{m}
$$

  </span>
</v-drag>

<v-drag pos="386,208,274,111">
  <span style="font-size: 16px;">

$$
u = \exp\left[ -i \sum_{a, b=1}^{4} H_{a, b}\gamma_{a} \gamma_{b} \right]
$$

  </span>
</v-drag>

<v-drag pos="365,310,340,97">
  <span style="font-size: 18px;">

**Preheating**: Haar-random circuits
$$
\ket{\tilde{\Psi}} = \tilde{U}^{A}_{t} \otimes \tilde{U}^{B}_{t}\ket{\Psi(\theta)} 
$$

  </span>
</v-drag>

<v-drag pos="653,336,232,107">
  <span style="font-size: 18px;">

$$
\tilde{U}^{A / B}_{t} = \prod_{s=1}^{t}\tilde{u}^{A/B}_{s}
$$

  </span>
</v-drag>

<v-drag pos="415,419,406,78">
  <span style="font-size: 18px;">

$$
\tilde{u}^{J}_{s} = \prod_{x \in \mathcal{B}^{J}_{s}}\tilde{u}_{s, x, x+1}, \quad J = A, B, \quad \mathcal{B}^{J}_{s} = \mathcal{B}_{s} \cap J
$$

  </span>
</v-drag>

<v-drag pos="49,84,262,245">
<img src="/assets/NG_Ferro_L20.png">
</v-drag>

<v-drag pos="54,315,258,234">
<img src="/assets/NG_PME_AB_heating.png">
</v-drag>

---
level: 2
dragPos:
  bib: 784,489,195,62
---

# Magic Resources

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

S. Aditya _et al._, [arXiv:2509.22176](http://arxiv.org/abs/2509.22176)

</span>
</v-drag>

<v-drag pos="354,2,289,111">
  <span style="font-size: 16px;">

$$
M(\rho) = \log_{2}\left( \sum_{r \in \mathbb{Z}^{2N}_{d}} \lvert \mathcal{W}_{r} \rvert  \right)
$$

  </span>
</v-drag>

<v-drag pos="633,12,314,86">
  <span style="font-size: 16px;">

$$
\mathcal{W}_{0} = \sum_{r \in \mathbb{Z}^{2N}_{d}} \frac{P_{r}}{d^{N}}, \quad A_{r} = P_{r} A_{0}P^{\dagger}_{r}
$$

  </span>
</v-drag>

<v-drag pos="389,165,517,88">
  <span style="font-size: 16px;">

$$
P_{r} = \prod_{l=1}^{N} e^{ \pi i \frac{(d+1)r^{x}_{l}r^{z}_{l}}{2} }X^{r^{x}_{l}}_{l}Z^{r^{z}_{l}}_{l}, \quad r = (r_{1}^{x}, r_{1}^{z}, \cdots, r_{N}^{x}r_{N}^{z}) \in \mathbb{Z}^{2N}_{d}
$$

  </span>
</v-drag>

<v-drag pos="402,91,475,97">
  <span style="font-size: 16px;">

$$
Z = \sum_{m=0}^{d-1} e^\frac{ 2\pi i m}{d }\ket{m} \bra{m} , \quad X = \sum_{m=0}^{d-1} \ket{m} \bra{m+1 \mod{d}} 
$$

  </span>
</v-drag>

<v-drag pos="474,226,361,101">
  <span style="font-size: 16px;">

$$
\ket{\Psi_{X}(\theta)} = \exp\left[ -i \theta \sum_{i} (X_{i} + X_{i}^{\dagger}) \right] \ket{0} ^{\otimes N}
$$

  </span>
</v-drag>

<v-drag pos="365,310,340,97">
  <span style="font-size: 18px;">

**Preheating**: Haar-random circuits
$$
\ket{\tilde{\Psi}} = \tilde{U}^{A}_{t} \otimes \tilde{U}^{B}_{t}\ket{\Psi(\theta)} 
$$

  </span>
</v-drag>

<v-drag pos="653,336,232,107">
  <span style="font-size: 18px;">

$$
\tilde{U}^{A / B}_{t} = \prod_{s=1}^{t}\tilde{u}^{A/B}_{s}
$$

  </span>
</v-drag>

<v-drag pos="415,419,406,78">
  <span style="font-size: 18px;">

$$
\tilde{u}^{J}_{s} = \prod_{x \in \mathcal{B}^{J}_{s}}\tilde{u}_{s, x, x+1}, \quad J = A, B, \quad \mathcal{B}^{J}_{s} = \mathcal{B}_{s} \cap J
$$

  </span>
</v-drag>

<v-drag pos="58,79,273,237">
<img src="/assets/Mana_Mpemba_L12_NA2_theta_state.png">
</v-drag>

<v-drag pos="66,308,263,230">
<img src="/assets/PME_Mana_AB_heating.png">
</v-drag>


---
layout: center
class: 'final-slide'
hideInToc: true
---

# Thank You!

<div class="contact-info">
  <p>Ze-Yu Xing</p>
</div>

<div class="footer">
  <p>Presented at Group Seminar October 2025</p>
</div>
