# Project Documentation

[中文](README.md) | [English](README.en.md)

This is the documentation index. Start with the user path when installing or operating the plugin. Use the maintainer path when changing code, tracing runtime behavior, or preparing a release.

## User Path

1. [Installation guide](../README-install.md): one-line install, release packages, Docker, and common Python environment issues.
2. [Full user guide](user-guide.en.md): configuration, CLI, multi-bot, multi-profile, upgrades, and troubleshooting.
3. [Migration guide](migration.en.md): migration of older configurations and installation state.
4. [V4.1 safety controls](wiki/v4.1-safety-controls.md): per-chat native delivery, runtime readiness, strict repair, and service management.

## Maintainer Path

1. [Architecture](architecture.en.md): the sidecar-only structure and module responsibilities.
2. [Event protocol](event-protocol.en.md): Hermes events, card state, and terminal handoff.
3. [Installer safety](installer-safety.en.md): patching, recovery, integrity, and failure boundaries.
4. [End-to-end verification](e2e-verification.en.md): preview artifacts, mock E2E, and real Feishu acceptance boundaries.
5. [Testing](testing.en.md): focused tests, full-suite checks, and release gates.
6. [Maintainer wiki](wiki/README.md): hot files, event flow, real Feishu acceptance, and the release playbook.

## Releases And History

- [CHANGELOG](../CHANGELOG.md) is the version index; `release-notes-v*.md` files are public per-version notes.
- [Release readiness](release-readiness.en.md) preserves cross-version verification evidence and untested boundaries. It is not the primary feature guide.
- The [V3.6.0 roadmap](roadmap-v3.6.0.md), `superpowers/plans/`, and `superpowers/specs/` are historical design and implementation records. Current behavior is defined by the README, user guide, maintainer wiki, code, and tests.
- `legacy/` is the V2 archive and is not the active runtime.

## Chinese Documentation

Use the [中文文档总入口](README.md) for the primary Chinese documentation path.
