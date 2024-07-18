# Nonlinear Differential Equation Solvers

## Introduction

Most physical phenomena in real life are fundamentally nonlinear, which are closely related to the real world. However, there are many differential equation solvers functioning quite well in approaching numerical solutions. This project primarily introduces two approaches: the topology-based Homotopy Analysis Method (HAM) and the deep learning-based Physics-Informed Neural Networks (PINN). Both approaches offer novel insights into the study of Ordinary Differential Equations (ODEs) and Partial Differential Equations (PDEs) with strong nonlinearity in the physical world.

## Methods

### Homotopy Analysis Method (HAM)

The Homotopy Analysis Method is a semi-analytical technique to solve highly nonlinear problems. It provides a way to construct a homotopy, a continuous transformation from a simple problem to the original nonlinear problem. This method is versatile and can be applied to a wide range of nonlinear differential equations. Mathematica code for HAM is based on https://numericaltank.sjtu.edu.cn.

### Physics-Informed Neural Networks (PINN)

Physics-Informed Neural Networks are a deep learning framework that incorporates the underlying physical laws described by differential equations into the learning process. PINNs can solve ODEs and PDEs by minimizing the residuals of the equations during the training of the neural network. This method leverages the power of deep learning to handle complex, nonlinear problems effectively.
