

# LINEAR ALGEBRA NOTES

---

## 🟢 NORMAL NOTES (Clear + Exam-Safe)

### 1. Scalars, Vectors, Matrices

* **Scalar**: single real number
* **Vector**: ordered list of numbers
* **Matrix**: rectangular array of numbers

### 2. Vector Operations

* Addition: component-wise
* Scalar multiplication: multiply each component
* Dot product:
  [
  \mathbf{a}\cdot\mathbf{b} = a_1b_1 + a_2b_2
  ]

### 3. Norm (Magnitude)

[
||\mathbf{x}|| = \sqrt{x_1^2 + x_2^2}
]

---

### 4. Matrices

* Addition: same order only
* Multiplication: rows × columns
* Identity matrix (I): (AI = IA = A)

---

### 5. Determinant

For 2×2:
[
|A| = ad - bc
]

* det = 0 → no inverse
* det ≠ 0 → inverse exists

---

### 6. Inverse of Matrix

[
A^{-1} = \frac{1}{|A|}\text{adj}(A)
]

---

### 7. System of Linear Equations

[
AX = B
]

* Unique solution → det(A) ≠ 0
* Infinite / No solution → det(A) = 0

---

### 8. Eigenvalues & Eigenvectors

[
A\mathbf{x} = \lambda \mathbf{x}
]

---

## 🔵 TOPPER LEVEL NOTES (Concept + Connection)

### 1. Linear Independence

Vectors are independent if none can be written as a combination of others.

Test:

* Determinant ≠ 0
* Rank = number of vectors

---

### 2. Rank of Matrix

* Number of independent rows/columns
* Row rank = column rank

Consistency:
[
\text{rank}(A) = \text{rank}([A|B])
]

---

### 3. Vector Spaces

A set is a vector space if:

* Closed under addition & scalar multiplication
* Has zero vector and inverses

Examples:

* ℝⁿ
* Polynomials
* Solution sets

---

### 4. Basis & Dimension

* **Basis**: smallest spanning set
* **Dimension**: number of basis vectors

---

### 5. Orthogonality

[
\mathbf{a}\cdot\mathbf{b} = 0
]

Orthogonal matrix:
[
Q^TQ = I
]

---

### 6. Diagonalization

[
A = PDP^{-1}
]

Possible if matrix has enough independent eigenvectors.

---

### 7. Geometric Meaning

* Matrix = linear transformation
* Determinant = area/volume scaling
* Eigenvectors = unchanged direction

---

## 🔴 ULTRA-TOPPER / RANKER NOTES (Exam + Intuition + Traps)

### 1. Determinant Deep Insight

* det(A) = 0 → rows lie in same plane
* det(A) < 0 → orientation reversal
* |det| = scaling factor

---

### 2. Rank–Nullity Theorem (🔥)

[
\text{rank}(A) + \text{nullity}(A) = \text{number of columns}
]

Meaning:

* Rank = information
* Nullity = freedom

---

### 3. Eigenvalue Power Moves

* Sum of eigenvalues = trace(A)
* Product of eigenvalues = det(A)
* Eigenvectors are **not unique**

---

### 4. Column Space, Row Space, Null Space

* Column space → output directions
* Null space → lost information
* Row space ⟂ null space

---

### 5. Exam Traps (VERY IMPORTANT)

❌ Assuming matrix multiplication is commutative
❌ Forgetting det=0 ⇒ no inverse
❌ Thinking eigenvectors are unique
❌ Mixing up span and basis

---

### 6. One-Glance Ranker Summary

* det → invertibility
* rank → dimension of info
* null space → constraints
* eigen → stability & scaling
* diagonalization → simplification


