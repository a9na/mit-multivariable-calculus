# 📘 MIT 18.02 - Lecture 1: Dot Product

## 🧠 Objectives
- Understand the **dot product** of vectors.
- Learn **geometric** and **algebraic** definitions.
- Apply the dot product to find **angles** between vectors and **projections**.

---

## ✏️ Definitions

### Vector Notation
- A vector in 2D: **v** = ⟨v₁, v₂⟩  
- A vector in 3D: **v** = ⟨v₁, v₂, v₃⟩

---

## 🔢 Dot Product

### Algebraic Definition
For vectors **a** = ⟨a₁, a₂, ..., aₙ⟩ and **b** = ⟨b₁, b₂, ..., bₙ⟩:

```
a · b = a₁b₁ + a₂b₂ + ... + aₙbₙ
```

### Geometric Definition

```
a · b = |a||b|cos(θ)
```

Where:
- |a| and |b| are the magnitudes (lengths) of the vectors.
- θ is the angle between **a** and **b**.

---

## 📐 Properties

- **Commutative**:  
  `a · b = b · a`
- **Distributive over addition**:  
  `a · (b + c) = a · b + a · c`
- **Scalar multiplication**:  
  `(ka) · b = k(a · b)`
- **Orthogonality**:  
  `a · b = 0 ⟺ a ⟂ b`

---

## ➕ Applications

### 1. Angle Between Vectors

Using the geometric definition:

```
cos(θ) = (a · b) / (|a||b|)
```

Solve for θ with inverse cosine.

---

### 2. Projection of a onto b

#### Scalar Projection (Component of a in direction of b):

```
comp_b(a) = (a · b) / |b|
```

#### Vector Projection:

```
proj_b(a) = [(a · b) / (b · b)] * b
```

---

## 📌 Example

Given:  
**a** = ⟨3, 4⟩  
**b** = ⟨1, 2⟩

1. **Dot product**:  
   `a · b = 3×1 + 4×2 = 3 + 8 = 11`

2. **Magnitudes**:  
   `|a| = √(3² + 4²) = √(9 + 16) = 5`  
   `|b| = √(1² + 2²) = √(1 + 4) = √5`

3. **Angle**:  
   `cos(θ) = 11 / (5√5)`  
   `θ = cos⁻¹(11 / (5√5))`

4. **Projection of a onto b**:  
   ```
   proj_b(a) = [(3×1 + 4×2) / (1² + 2²)] * ⟨1, 2⟩  
             = (11 / 5) * ⟨1, 2⟩  
             = ⟨11/5, 22/5⟩
   ```

---

## 📚 Summary

- The dot product connects **algebra** and **geometry** of vectors.
- Zero dot product indicates **perpendicular** vectors.
- Useful for:
  - Computing **angles**
  - Finding **projections**
  - Physics applications (e.g. **work** = force · displacement)

---
