# Changelog

## 0.2.2 — 2026-10-11

- Update the app store remotely for Mac apps, local bridges, CLI tools and iPhone apps. New apps and package versions no longer require a Jevbot release.
- Verify remote catalogs with Ed25519 signatures, retain a verified offline cache, and keep package checksums and developer identity checks at installation and launch.
- Install Orca PPT 0.1.0 and connect its built-in MCP automatically.
- Update managed Mac apps from their store cards, alongside bridges and CLI tools.
- Fix oversized app icons in the task composer and clear the placeholder immediately during typing and IME composition.
- Default new tasks to “Approve for me”, simplify the approval picker, and honor full access for CLI actions while pausing automatic execution after failures.

## 0.2.1 — 2026-10-09

Version 0.2.0 was not published; 0.2.1 includes its changes and a release packaging fix.

- Install creative apps and local MCP bridges from the new app store, with automatic MCP connection after installation.
- Follow the first-use guide to connect ChatGPT / Codex, Claude Code, or DeepSeek, then install an app and start creating.
- Pin tasks in the sidebar, use hover actions to pin or unpin, and collapse sidebar sections.
- Open an app from its store card to start a new task with that app selected. App settings return directly to the store.
- See available Jevbot updates in the activity bell.
- Verify local bridge files at installation and launch, resolve the bundled Node runtime after app moves or updates, and isolate MCP child processes from Jevbot's privacy permissions.
- Built-in app adapters are removed; connect apps through the store or manual MCP configuration.

## 0.1.0 — 2026-10-07

- Initial public macOS release.
