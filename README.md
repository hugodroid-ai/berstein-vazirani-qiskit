# Algoritmo de Bernstein-Vazirani — Implementación en Qiskit

## Microcredencial en Fundamentos de Computación Cuántica
### Universidad de La Laguna — 2026

**Autor:** Hugo Tapia

---

## Descripción

Implementación parametrizada del algoritmo de Bernstein-Vazirani utilizando Qiskit 2.x. El algoritmo demuestra una ventaja cuántica al encontrar una cadena de bits secreta `s` oculta dentro de una función oráculo con **una sola consulta**, frente a las `n` consultas requeridas clásicamente.

## Contenido del repositorio

```
├── BV_Demo_Colab.ipynb     # Notebook principal (ejecutable en Google Colab)
├── README.md               # Este archivo
```

## Características

- **Implementación parametrizada:** La función `bernstein_vazirani(s)` acepta cualquier cadena secreta de longitud arbitraria
- **Comparación clásica vs cuántica:** Incluye implementación clásica para contrastar
- **Qiskit 2.x:** Código actualizado a la versión moderna de Qiskit

## Ejecutar en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/bernstein-vazirani/blob/main/BV_Demo_Colab.ipynb)

> Sustituir `TU_USUARIO` por tu nombre de usuario de GitHub.

## Requisitos

```bash
pip install qiskit qiskit-aer
```

## Referencias

- Bernstein, E., & Vazirani, U. (1997). *Quantum Complexity Theory*. SIAM Journal on Computing, 26(5), 1411-1473.
- Du, J. et al. (2001). *Implementation of a quantum algorithm to solve the Bernstein-Vazirani parity problem*. Phys. Rev. A, 64, 042306.
