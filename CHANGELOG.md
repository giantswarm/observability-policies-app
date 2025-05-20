# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Add Cluster Role to allow latest Kyverno versions to work (https://github.com/giantswarm/giantswarm/issues/33416)
- Switch `.Values.disabled` to `.Values.enabled` to follow best practices.

## [0.0.1] - 2024-07-30

### Added

- Add a ClusterPolicy to prevent prometheus-operator CRDs deletion.
- Create `observability-policies` app to deploy Kyverno Observability Policies into clusters.

[Unreleased]: https://github.com/giantswarm/observability-policies-app/compare/v0.0.1...HEAD
