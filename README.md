# Kurswaechter AI Benchmark Suites

Standardized, isolated evaluation benchmark suites for autonomous AI Kubernetes SRE and Security remediation agents.

## Overview

This repository contains isolated evaluation scenarios for benchmarking Kubernetes AI agents:

- **sre/**: 35 Real-World Operational SRE Troubleshooting Scenarios.
  - : Contains target resource manifests evaluated by AI agents.
  - : Contains reference solutions used strictly for automated scoring.

- **security/**: 15 Kubernetes Security and Unhardened Workload Scenarios (from Kubernetes Goat).
  - : Contains target unhardened manifests evaluated by AI agents.
  - : Contains reference security hardening solutions.

In each suite:
- : Target resource manifests deployed to isolated KinD clusters.
- : Reference solutions kept outside agent inspection scope.

## Acknowledgments and Attribution

These benchmark suites adapt scenario definitions from the following open-source projects:

- **SRE Troubleshooting Suite**: Derived from [troubleshoot-kubernetes-like-a-pro](https://github.com/vellankikoti/troubleshoot-kubernetes-like-a-pro) by Koti Vellanki.
- **Security and Hardening Suite**: Derived from [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) by Madhu Akula (https://github.com/madhuakula).

All original scenario manifests remain credited to their respective authors under their original open-source licenses (MIT / Apache 2.0).
