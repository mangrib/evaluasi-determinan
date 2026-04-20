# Determinan Matriks dengan Ekspansi Baris

## Soal

Hitung determinan dari matriks berikut menggunakan ekspansi baris:

\[ A =
```{=tex}
\begin{bmatrix}
-7 & -5 \\
1 & 4
\end{bmatrix}
```
\]

------------------------------------------------------------------------

## Rumus

Determinan matriks dapat dihitung dengan rumus:

\[ `\det`{=tex}(A)=`\sum`{=tex}*{k=1}^{n}(-1)^{i+k} a*{ik} M\_{ik} \]

Keterangan: - a_ik = elemen matriks - M_ik = minor dari elemen a_ik -
Minor diperoleh dengan menghapus baris ke-i dan kolom ke-k

------------------------------------------------------------------------

## Langkah Penyelesaian

Gunakan ekspansi baris pertama (i = 1)

### 1. Elemen pertama (k = 1)

a_11 = -7

Minor: \[ M\_{11} = 4 \]

Perhitungan: \[ (-1)\^{1+1} `\cdot `{=tex}(-7) `\cdot 4`{=tex} = -28 \]

------------------------------------------------------------------------

### 2. Elemen kedua (k = 2)

a_12 = -5

Minor: \[ M\_{12} = 1 \]

Perhitungan: \[ (-1)\^{1+2} `\cdot `{=tex}(-5) `\cdot 1`{=tex} = +5 \]

------------------------------------------------------------------------

## Hasil Akhir

\[ `\det`{=tex}(A) = -28 + 5 = -23 \]

------------------------------------------------------------------------

## Kesimpulan

\[ `\boxed{\det(A) = -23}`{=tex} \]
