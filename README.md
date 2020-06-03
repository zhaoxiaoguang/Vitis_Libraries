# Vitis Solver Library

## Overview

Vitis Solver Library provides a collection of matrix decomposition operations, linear solvers and eigenvalue solvers.

Currently this includes the following operations for dense matrix
  - Matrix decomposition
    * Cholesky decomposition for symmetric positive definite matrix
    * LU decomposition without pivoting and with partial pivoting
    * QR decomposition for general matrix
    * SVD decomposition (single value decomposition) for symmetric matrix and non-symmetric matrix (Jacobi method)
  - Linear solver
    * Tridiagonal linear solver (Parallel cyclic reduction method)
    * Linear solver for triangular matrix
    * Linear solver for symmetric and non-symmetric matrix
    * Matrix inverse for symmetric and non-symmetric matrix
  - Eigenvalue solver
    * Jacobi eigenvalue solver for symmetric matrix

## Software and Hardware requirements
  - CentOS/RHEL 7.4, 7.5 or Ubuntu 16.04.4 LTS, 18.04.1 LTS
  - Vitis 2019.2
  - Alveo U200, U250
