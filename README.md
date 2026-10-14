# real-time-resume

<!-- intent-select-partner:start -->
<p><a href="https://intentsolutions.io/"><img src="https://raw.githubusercontent.com/intent-solutions-io/.github/b82af5d3e7951d85e39ea9e65cc24ee8278722a7/assets/brand/claude-select-partner.svg" alt="Intent Solutions: Claude Partner Network Select Services Partner" width="300" height="95" /></a></p>

Intent Solutions is a Claude Partner Network Select Services Partner.
<!-- intent-select-partner:end -->

Real-time collaborative resume builder built with Rust, Leptos SSR + hydration, and Tailwind CSS.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U5S225PTME)

## Quick Start

```bash
# Install dependencies
cargo install cargo-leptos trunk
rustup target add wasm32-unknown-unknown

# Development (SSR + hot reload)
cargo leptos watch

# Production build
cargo leptos build --release
```

## Stack

- **Frontend**: Leptos 0.6+ (SSR + hydration)
- **Backend**: Axum + leptos_axum
- **Styling**: Tailwind CSS v3 (standalone CLI)
- **Build**: Trunk (WASM), cargo-leptos (SSR)

## Development

Server runs at `http://127.0.0.1:3000`

```bash
cargo leptos watch
```

## Project Structure

```
real-time-resume/
├── 000-docs/          # Documentation (flat, no subdirs)
├── src/               # Rust source code
├── styles/            # Tailwind CSS
├── templates/         # HTML templates
├── assets/            # Static assets
└── .github/workflows/ # CI/CD
```

## Documentation

All documentation lives in `000-docs/` following Doc Filing System Standard v3.0. See `CLAUDE.md` for rules.

## License

MIT License - See [LICENSE](LICENSE) for details.

---
intent solutions io
jeremy@intentsolutions.io
