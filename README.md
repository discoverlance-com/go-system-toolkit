# Go System Toolkit (go-system-toolkit)

A small, evolving Go-based CLI for inspection and validating of systems.

Modern applications require understanding and processing complex commands and setup for different environments and systems like Windows, Linux and MacOS. 
This project aims to build a simple and reliable CLI with Go, that can be used to inspect local system information and provide useful feedback to developers and operators.

## Initial Scope

- Parse CLI arguments
- Run a small set of system checks (eg. running ports, OS info)
- Return a clear, structured output
- Explicitly handle errors
- Include basic testing

## Excluded Goals (for now)

- No Cloud API integrations
- No AI integrations
- No complex concurrency setup
- No Go plugins or extensions

## Why This Project Matters

This project is intentionally made simple with a narrow scope at the start as it's intended for learning. Over time, we'll increase the scope as we learn new concepts including testing, concurrency and system signals.
