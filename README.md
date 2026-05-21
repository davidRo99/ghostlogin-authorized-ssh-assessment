# GhostLogin - Authorized SSH Exposure Assessment Lab

## Overview

GhostLogin is a documentation-only cybersecurity portfolio project based on an academic lab.

The project demonstrates an authorized SSH exposure assessment workflow in a controlled VMware lab environment. It focuses on discovering exposed SSH services, validating access only under approved lab conditions, running a non-interactive verification command, and generating structured reporting outputs.

No offensive code, credentials, password files, raw logs, or executable attack tools are included in this repository.

## Project Goals

- Demonstrate safe cybersecurity lab documentation
- Document an authorized SSH exposure assessment workflow
- Show Bash-based automation planning
- Explain non-interactive SSH verification without opening an interactive shell
- Present structured reporting using TSV and HTML outputs
- Highlight responsible and controlled security testing practices

## Key Features Documented

- Target range validation
- SSH service discovery on port 22
- Authorized credential validation in a private lab environment
- Non-interactive verification command
- TSV results output
- HTML summary report
- Self-check for required tools
- NoiseGuard mode for reduced-noise execution

## Creativity Feature: NoiseGuard

NoiseGuard was added as a custom improvement to reduce unnecessary network noise during lab execution.

It documents a safer and more controlled assessment approach by adjusting scan intensity, validation behavior, and delay between targets in a private lab environment.

## Lab Environment

- Kali Linux
- VMware private lab network
- Bash scripting
- nmap
- sshpass
- hydra
- HTML reporting

## Repository Contents

docs/
- GhostLogin_Project_Showcase.pdf

Root files:
- README.md
- SAFETY.md

## What I Learned

- Cybersecurity lab documentation
- Bash automation logic
- Network service discovery concepts
- Safe verification workflows
- Structured reporting
- Error handling and logging concepts
- Responsible security presentation for a professional portfolio

## Safety Notice

This repository is for educational and portfolio documentation only.

The project was performed in a private, authorized lab environment. Do not use the concepts described here against public systems, third-party networks, or any environment without explicit written permission.

## Status

Completed as an academic cybersecurity lab project and adapted for professional portfolio presentation.
