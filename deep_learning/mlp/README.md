# Multilayer perceptrons

Three graduate exercises in English. Each PDF contains the statement and a full worked solution. The sources share [`preamble.tex`](preamble.tex); compile each file from this directory.

| | Topic | PDF | Source |
|---|---|---|---|
| 1 | Forward propagation and backpropagation | [PDF](exercise_01_backpropagation.pdf) | [TeX](exercise_01_backpropagation.tex) |
| 2 | Expressivity and universal approximation | [PDF](exercise_02_expressivity.pdf) | [TeX](exercise_02_expressivity.tex) |
| 3 | Initialization, vanishing gradients, and regularization | [PDF](exercise_03_optimization.pdf) | [TeX](exercise_03_optimization.tex) |

```bash
pdflatex exercise_01_backpropagation.tex
pdflatex exercise_02_expressivity.tex
pdflatex exercise_03_optimization.tex
```

Run a file a second time if its cross-references still show as question marks.

The first exercise differentiates a \(2\)--\(2\)--\(1\) sigmoid network by hand, then lifts the calculation to minibatch matrix form, including the simplification of binary cross-entropy. The second constructs exact ReLU representations (a triangular bump, XOR, and the iterates of a tent map) and proves a univariate depth separation together with one-dimensional universal approximation. The third derives Glorot and He initialisation, a vanishing-gradient bound for a sigmoid chain, the equivalence of \(\ell_2\) regularisation and weight decay for gradient descent, and the exact diagonal penalty induced by dropout on a linear least-squares layer.
