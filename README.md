# Cursed Knowledge

Cursed knowledge I have learned from working on various projects that I wish I never knew.

## `scipy.linalg.cholesky` is cursed

`np.linalg.cholesky` returns a lower-triangular factor by default, while `scipy.linalg.cholesky` returns an upper-triangular factor by default.

## `random.randint` is cursed

`random.randint(a,b)` returns an integer in the range `[a,b]`, while `numpy.random.randint(a,b)` returns an integer in the range `[a,b)`.

## `np.maximum` is cursed

`np.max` returns the maximum value of a single array, while `np.maximum` computes the element-wise maximum of two arrays.
