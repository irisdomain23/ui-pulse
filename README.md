<div align="center">

# ui-pulse

**Measure what your UI actually costs — render time, layout thrash, and re-render count.**

[![wip](https://img.shields.io/badge/status-planning-orange?style=flat-square)](#roadmap)
[![license](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

</div>

## About

Nothing is implemented yet and that is stated plainly rather than implied
with an empty API. The intended approach is `PerformanceObserver` long-task
entries plus a development-only hook into the reconciler commit phase, so
production bundles carry no cost.

## Quick start

```bash
git clone https://github.com/irisdomain23/ui-pulse
# planning stage — see Roadmap below
```

## Configuration

| Key | Description |
| --- | --- |
| `README.md` | this file — the roadmap lives here until there is code |

> **Status:** planning. This repository intentionally contains no code
> that pretends to work.
## Roadmap

- [ ] Long-task observer v0
- [ ] Re-render counter for a component subtree
- [ ] Overlay timeline in the browser

## Contributing

Issues and pull requests are welcome. Please keep changes small and focused,
and add a test for any behaviour change — every repository here ships with a
runnable test suite and no third-party dependencies, so CI is just
`python3 -m unittest` / `bash test_*.sh`.

## License

[MIT](LICENSE)
