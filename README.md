<!--
SPDX-FileCopyrightText: 2026 Michele Bussolotto <michelebussolotto@pm.me>

SPDX-License-Identifier: Apache-2.0
-->

# Hosteria Configurator

The published (GitHub Pages) copy of the Hosteria installation configurator.

- **Live:** https://hosteria-project.github.io/hosteria-configurator/
- **Source of truth:** https://github.com/hosteria-project/hosteria (`configurator/`)

This repository contains only the static configurator (a single HTML file). The
main project is private; this public copy exists solely so GitHub Pages can
serve the configurator on the free plan. There are no secrets here.

## Syncing

From the main repository:

```bash
make publish-configurator
```

> **Note:** the combustion script this page generates downloads the Hosteria
> release from the private repository. For private or air-gapped installs use
> `hosteria make-installer`, which produces a self-contained script instead.

## License

Apache License 2.0 — see [LICENSES/Apache-2.0.txt](LICENSES/Apache-2.0.txt).
