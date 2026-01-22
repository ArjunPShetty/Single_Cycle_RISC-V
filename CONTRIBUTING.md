# Contributing Guidelines

Thank you for your interest in contributing to this project. Contributions are
welcome from students, researchers, and engineers, provided they follow the
guidelines outlined below.

This repository contains Verilog HDL code intended for educational, research,
and reference purposes.

## How to Contribute

You can contribute in the following ways:

- Fixing bugs or functional issues
- Improving RTL readability or modularity
- Adding comments or documentation
- Enhancing testbenches
- Optimizing logic without changing functionality
- Reporting issues or suggesting improvements

## Getting Started

1. Fork the repository
2. Create a new branch for your changes  
3. Make your changes
4. Commit with a clear and descriptive message
5. Push to your fork and open a Pull Request (PR)

## Verilog Coding Standards

Please follow these conventions to maintain consistency:

- Use **clear and descriptive module names**
- Use **lowercase with underscores** for signals where possible
- Match `module` / `endmodule` correctly (case-sensitive)
- Avoid implicit latches; use complete combinational assignments
- Prefer `wire` for combinational signals and `reg` only when required
- Keep modules **synthesizable** unless explicitly marked as testbench-only

## Testbenches

- All new functional changes should include or update a testbench
- Testbenches should be placed in clearly named files (e.g., `*_tb.v`)
- Avoid non-standard simulator-specific constructs unless documented

## Documentation

- Update `README.md` if functionality or usage changes
- Comment complex logic, especially control-path decisions
- Clearly document assumptions (clocking, reset polarity, memory behavior)

## Pull Request Guidelines

When submitting a PR:

- Clearly describe **what** was changed and **why**
- Reference related issues if applicable
- Ensure the design compiles without errors
- Avoid mixing unrelated changes in a single PR

PRs may be rejected if they:
- Break existing functionality
- Reduce readability without justification
- Violate coding or behavioral standards

## Issue Reporting

When opening an issue, please include:

- A clear description of the problem
- Expected vs. actual behavior
- Simulation tool used (e.g., Icarus, ModelSim, Verilator)
- Relevant logs, waveforms, or code snippets if available

## Code of Conduct

All contributors are expected to follow the project's
[Code of Conduct](CODE_OF_CONDUCT.md).

Unprofessional or abusive behavior will not be tolerated.

## Licensing

By contributing to this repository, you agree that your contributions will be
licensed under the same license as the project (see `LICENSE` file).

## Acknowledgment

Contributions that significantly improve the project may be acknowledged
in documentation or related academic publications where appropriate.
