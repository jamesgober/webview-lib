# webview-lib - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
> Master plan: C:/Dev/libraries/Rust/lang-collection/_lexersketch/ROADMAP.md and NEW-LIBS.md
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Windows: own WebView2 loader + window; macOS: WKWebView + NSWindow; Linux: WebKitGTK window; local-URL navigation; CI canaries.

## v0.5.0 - Implementation
- [ ] Message bridge, multiple windows, menus, file dialogs.

## v0.9.0 - Hardening
- [ ] Lifecycle stress; runtime-version canaries.

## v1.0.0 - Stable
- [ ] Frozen after Studio's native window ships on it (D18).
