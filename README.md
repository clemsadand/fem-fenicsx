# FEM with FEniCSx
![Build Status](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![FEniCSx](https://img.shields.io/badge/FEniCSx-0.4.1-blue.svg)](https://fenicsproject.org/)


## Overview

<img src="./u_sol.gif" alt="gif" width="500px" style="text-align: center;">

This repository contains examples and tutorials for solving various partial differential equations (PDEs) using the FEniCSx library. FEniCSx is a popular open-source computing platform for solving PDEs, and this repository aims to demonstrate its application in finite element methods (FEM).

## Contents

- **Heat Equation**: A tutorial on solving the dynamic heat equation using the Euler backward scheme in time and a finite element method in space. We used Lagrange and  Crouzeix-Raviart finite element methods.
- **Stokes Problem**: An example of solving the dynamic Stokes problem in 2D using Lagrange finite element spaces (coming soon...).
- **Other Examples**: Additional PDE problems and their solutions using FEniCSx.

## Installation

To run the examples in this repository, you need to have FEniCSx installed. You can install it using Docker, Conda, or from source. Detailed installation instructions can be found in the [FEniCSx documentation](https://fenicsproject.org/docs/dolfinx/latest/).

## Usage

Clone the repository and navigate to the desired example directory to run the scripts. For example, to run the heat equation example:

```sh
git clone https://github.com/clemsadand/fem-fenicsx.git
cd fem-fenicsx/heat-equation
python solve_heat_equation.py
