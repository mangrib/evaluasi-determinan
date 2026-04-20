# Determinan dan Invers Matriks

## A. Determinan Matriks

### 1. Matriks 2x2
\[
A = \begin{bmatrix} -7 & -5 \\ 1 & 4 \end{bmatrix}
\]

Rumus:
\[
\det(A) = ad - bc
\]

Perhitungan:
\[
= (-7)(4) - (-5)(1) = -28 + 5 = -23
\]

**Jawaban:** det(A) = -23

---

### 2. Matriks 3x3
\[
A =
\begin{bmatrix}
0 & 2 & -3 \\
1 & -2 & -1 \\
0 & 0 & 1
\end{bmatrix}
\]

Karena matriks segitiga atas:
\[
\det(A) = 0 \cdot (-2) \cdot 1 = 0
\]

**Jawaban:** det(A) = 0

---

### 3. Matriks 4x4
\[
A =
\begin{bmatrix}
1 & -3 & 1 & 1 \\
-3 & 1 & 1 & 1 \\
1 & 1 & -3 & 1 \\
1 & 1 & 1 & -3
\end{bmatrix}
\]

Hasil:
\[
\det(A) = -256
\]

**Jawaban:** det(A) = -256

---

## B. Invers Matriks

Rumus:
\[
A^{-1} = \frac{1}{\det(A)} \cdot adj(A)
\]

---

### 4. Matriks 2x2
\[
A = \begin{bmatrix} -7 & -5 \\ 1 & 4 \end{bmatrix}
\]

Determinan:
\[
-23
\]

Adj(A):
\[
\begin{bmatrix}
4 & 5 \\
-1 & -7
\end{bmatrix}
\]

Invers:
\[
A^{-1} = \frac{1}{-23}
\begin{bmatrix}
4 & 5 \\
-1 & -7
\end{bmatrix}
\]

Hasil:
\[
A^{-1} =
\begin{bmatrix}
-4/23 & -5/23 \\
1/23 & 7/23
\end{bmatrix}
\]

---

### 5. Matriks 3x3
\[
A =
\begin{bmatrix}
0 & 2 & -3 \\
1 & -2 & -1 \\
0 & 0 & 1
\end{bmatrix}
\]

Karena:
\[
\det(A) = 0
\]

**Kesimpulan:** Tidak memiliki invers

---

### 6. Matriks 4x4
\[
A =
\begin{bmatrix}
1 & -3 & 1 & 1 \\
-3 & 1 & 1 & 1 \\
1 & 1 & -3 & 1 \\
1 & 1 & 1 & -3
\end{bmatrix}
\]

Determinan:
\[
-256
\]

Invers:
\[
A^{-1} =
\begin{bmatrix}
1/4 & 1/16 & 1/16 & 1/16 \\
1/16 & 1/4 & 1/16 & 1/16 \\
1/16 & 1/16 & 1/4 & 1/16 \\
1/16 & 1/16 & 1/16 & 1/4
\end{bmatrix}
\]


