# Clojure-Linear-Algebra



##### Functions for interacting with linear algebra objects:

- Vectors: 
  - `v+`, `v-`, `v*` - simple arithmetic operations with vectors
  - `scalar` - Dot product
  - `vect` - Cross product 
  - `vsize-equals?` - сhecks if vector sizes are equal
  - `isVector?` - сhecks if a given argument is a vector
- Matrices:
  - `m+`, `m-`, `m*` - simple arithmetic operations with matrices
  - `m*s`, `m*v`, `m*m` - matrix scalar multiplication, matrix vector multiplication, matrix multiplication
  - `transpose` - matrix transpose operation
  - `msize-equals?` - сhecks if matrix sizes are equal
  - `isMatrix?` - сhecks if a given argument is a matrix
- Tensors:
  - `t+`, `t-`, `t*` - simple arithmetic operations with tensors
  - `tsize-equals?` - сhecks if tensors sizes are equal
  - `isTensor?` - сhecks if a given argument is a tensor

##### Additionally:

- Other:
  - `operation-precond`  - [Clojure-function](https://clojure.org/guides/learn/functions#:~:text=Test%20your%20knowledge-,Creating%20Functions,inputs%20yields%20the%20same%20output.) precondition factory
  - `create-operation ` - [Clojure-function](https://clojure.org/guides/learn/functions#:~:text=Test%20your%20knowledge-,Creating%20Functions,inputs%20yields%20the%20same%20output.) factory for operations with linear algebra objects