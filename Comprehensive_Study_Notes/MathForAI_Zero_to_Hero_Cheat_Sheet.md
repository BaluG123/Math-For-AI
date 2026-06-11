# 🧠 MathForAI — Zero to Hero Cheat Sheet

> Quick reference for all essential formulas across all 15 modules.

---

## Module 01: Linear Algebra Foundations

| Concept | Formula |
|---------|---------|
| Dot Product | **a** · **b** = Σ aᵢbᵢ = ‖a‖‖b‖cos(θ) |
| Matrix Multiply | (AB)ᵢⱼ = Σₖ AᵢₖBₖⱼ |
| Transpose | (Aᵀ)ᵢⱼ = Aⱼᵢ |
| Inverse | AA⁻¹ = A⁻¹A = I |
| Determinant (2×2) | det([[a,b],[c,d]]) = ad - bc |

## Module 02: Advanced Linear Algebra

| Concept | Formula |
|---------|---------|
| Eigenvalue equation | Av = λv |
| Eigendecomposition | A = QΛQ⁻¹ |
| SVD | A = UΣVᵀ |
| PCA | Project onto top-k eigenvectors of covariance matrix |
| L2 Norm | ‖x‖₂ = √(Σ xᵢ²) |
| Frobenius Norm | ‖A‖_F = √(Σᵢⱼ Aᵢⱼ²) |

## Module 03: Calculus — Single Variable

| Concept | Formula |
|---------|---------|
| Power Rule | d/dx [xⁿ] = nxⁿ⁻¹ |
| Chain Rule | d/dx [f(g(x))] = f'(g(x)) · g'(x) |
| Product Rule | d/dx [fg] = f'g + fg' |
| Taylor Series | f(x) = Σ f⁽ⁿ⁾(a)/n! · (x-a)ⁿ |
| Fundamental Theorem | ∫ₐᵇ f'(x)dx = f(b) - f(a) |

## Module 04: Calculus — Multivariable

| Concept | Formula |
|---------|---------|
| Gradient | ∇f = [∂f/∂x₁, ∂f/∂x₂, ..., ∂f/∂xₙ]ᵀ |
| Jacobian | Jᵢⱼ = ∂fᵢ/∂xⱼ |
| Hessian | Hᵢⱼ = ∂²f/∂xᵢ∂xⱼ |
| Directional Derivative | D_u f = ∇f · u |
| Lagrange Multiplier | ∇f = λ∇g at optimum |

## Module 05: Probability Theory

| Concept | Formula |
|---------|---------|
| Bayes' Theorem | P(A|B) = P(B|A)P(A) / P(B) |
| Expectation | E[X] = Σ xᵢP(xᵢ) or ∫ xf(x)dx |
| Variance | Var(X) = E[(X-μ)²] = E[X²] - (E[X])² |
| Covariance | Cov(X,Y) = E[(X-μₓ)(Y-μᵧ)] |
| Law of Total Probability | P(A) = Σ P(A|Bᵢ)P(Bᵢ) |

## Module 06: Distributions & Statistics

| Distribution | PDF/PMF |
|-------------|---------|
| Bernoulli | P(X=k) = pᵏ(1-p)¹⁻ᵏ |
| Gaussian | f(x) = (1/√(2πσ²)) exp(-(x-μ)²/(2σ²)) |
| MLE | θ̂ = argmax Σ log P(xᵢ|θ) |
| Multivariate Gaussian | f(x) = (2π)⁻ᵈ/² |Σ|⁻¹/² exp(-½(x-μ)ᵀΣ⁻¹(x-μ)) |

## Module 07: Optimization

| Concept | Formula |
|---------|---------|
| Gradient Descent | θₜ₊₁ = θₜ - α∇f(θₜ) |
| SGD | θₜ₊₁ = θₜ - α∇fᵢ(θₜ) |
| Momentum | vₜ = βvₜ₋₁ + ∇f(θₜ); θₜ₊₁ = θₜ - αvₜ |
| Adam | Combines momentum + RMSProp with bias correction |
| Convexity | f(λx + (1-λ)y) ≤ λf(x) + (1-λ)f(y) |

## Module 08: Information Theory

| Concept | Formula |
|---------|---------|
| Entropy | H(X) = -Σ p(x) log p(x) |
| Cross-Entropy | H(p,q) = -Σ p(x) log q(x) |
| KL Divergence | D_KL(p‖q) = Σ p(x) log(p(x)/q(x)) |
| Mutual Information | I(X;Y) = H(X) - H(X|Y) |

## Module 09: Matrix Calculus

| Concept | Formula |
|---------|---------|
| ∂(Ax)/∂x | A |
| ∂(xᵀAx)/∂x | (A + Aᵀ)x |
| ∂(‖Ax-b‖²)/∂x | 2Aᵀ(Ax-b) |
| Chain Rule (matrices) | ∂L/∂W = ∂L/∂y · ∂y/∂W |

## Module 10-15: Advanced Topics

*See individual module notebooks for detailed formulas.*

---

*Keep this cheat sheet handy as a quick reference while studying!*
