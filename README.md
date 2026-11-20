# Sharpness of the Martin–O’Bryant autoconvolution inequality

This Lean 4 project formalizes **Theorem 1** of Tonći Crmarić, Vjekoslav Kovač, and Jelena Rupčić. For every real $\varepsilon>0$ there exist $d\in\mathbb N_0$ and nonnegative real heights $p_0,\ldots,p_d$, at least one positive, such that

$$
f=\sum_{j=0}^d p_j\mathbf{1}_{[j,j+1)},\qquad
\frac{\|f*f\|_2^2}{\|f*f\|_1\,\|f*f\|_\infty}>1-\varepsilon.
$$

The convolution and all three norms use Lebesgue measure on the real line. The proof follows Section 2, choosing $q$, then $K$, then $n$. [Paper](https://arxiv.org/abs/2611.12685v1) · [Statement](Challenge.lean) · [Proof](Solution.lean) · [Mathematical review](docs/review.md) · [Verification records](docs/verification.md)

## Credits

**Formalization authors.** Tonći Crmarić, Vjekoslav Kovač, and Jelena Rupčić. **Credit for the Lean formalization.** GPT-6 Astra. [Project metadata](formalization.yaml) · [Pinned mathlib source](https://github.com/leanprover-community/mathlib4/tree/56a005855ea17e0b0958f73ec801ae140b0a1679)

