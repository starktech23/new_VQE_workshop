# VQE Workshop with PennyLane

A hands-on workshop introducing the Variational Quantum Eigensolver (VQE) using PennyLane.

## Workshop Goals

By the end of this workshop notebook, users should be able to:

- understand the ground-state energy problem at a high level,
- compare exact diagonalization with a variational quantum approach,
- explain the role of the Hamiltonian, ansatz, cost function, and optimizer in VQE,
- run and modify a basic VQE workflow in PennyLane;
- recognize common limitations and open questions around VQE.

## Target Audience

This workshop is designed for a broad scientific audience, including physicists, computer scientists, mathematicians, engineers, chemists, and researchers interested in quantum computing applications. (This should not discourage viewers to interact with the notebook, user interaction and feedback is welcome regardless of background.)

Users are expected to be comfortable with Python and have basic familiarity with quantum computing concepts such as qubits, gates, circuits, and measurement.

## Prerequisites

Recommended background:

- Basic Python programming
- Basic linear algebra
- Familiarity with quantum circuits
- Basic understanding of eigenvalues and eigenvectors

If you are new to the basics of quantum computing, texts such as Ch. 1–4 of Nielsen & Chuang or equivalent are recommended.

No prior experience with PennyLane or VQE is required.

## Software/Libraries Used

- Python
- PennyLane
- NumPy
- SciPy
- Matplotlib

## Workshop Materials

- `VQE_notebook_workshop_version.ipynb` — attendee version
- `VQE_notebook_solutions.ipynb` — completed solution version
- `molecule_viz.ipynb` — optional molecular visualization notebook

## Full Timed Agenda Summary

| Time | Section | Main Activity |
|---:|---|---|
| 0–5 min | Welcome and setup | Introduce goal, notebook, and workflow |
| 5–10 min | Motivation | Real-world applications and energy minimization |
| 10–16 min | Hamiltonians | Connect applications to Hamiltonians and ground states |
| 16–24 min | Exact diagonalization | Build a classical baseline |
| 24–31 min | Variational principle | Introduce the foundation of VQE |
| 31–40 min | Ansatz | Compare ansatz choices and circuit construction |
| 40–49 min | VQE exercises | Run parameter sweep, optimizer, and convergence plot |
| 49–53 min | Interpret result | Compare VQE output with exact baseline |
| 53–56 min | Limitations | Discuss practical caveats and open questions |
| 56–58 min | Extensions | Mention other implementations and ADAPT-VQE direction |
| 58–60 min | Wrap-up | Reading list, next steps, and final takeaway |

