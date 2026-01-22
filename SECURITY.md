# Security Policy

## Supported Versions

This project is primarily intended for educational and research use.
Only the latest version in the main branch is actively maintained.

| Version | Supported |
|--------|-----------|
| main   | Yes       |
| older releases | No |

---

## Reporting a Vulnerability

If you discover a potential security issue, vulnerability, or unintended behavior,
please report it responsibly.

### How to Report
- Open a **GitHub Issue** with a clear description, **or**
- Contact the project maintainer directly (if contact information is provided)

Please include:
- A detailed description of the issue
- Steps to reproduce the problem
- Affected modules or files
- Simulation or synthesis context, if applicable

Do **not** publicly disclose severe vulnerabilities without giving maintainers
reasonable time to investigate and respond.

---

## Scope of Security Issues

Security-related issues may include:
- Unintended behavior in control or data paths
- RTL bugs leading to incorrect execution
- Memory access violations
- Undefined or unsafe reset behavior
- Simulation vs. synthesis mismatches

The following are generally **out of scope**:
- Performance optimizations
- Feature requests
- Style or formatting issues
- Toolchain-specific warnings without functional impact

---

## Response Expectations

The project maintainers will:
- Acknowledge valid reports in a reasonable timeframe
- Investigate and assess reported issues
- Provide fixes or mitigation where appropriate

As this is a research/educational project, response times are best-effort.

---

## Disclaimer

This project is provided **"as is"**, without warranty of any kind.
It is not intended for use in safety-critical or production environments.

Users are responsible for validating the design before any real-world deployment.
