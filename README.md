# Subfinder Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Subfinder cookbook** — passive subdomain discovery from public sources. Second-tier OSINT tool in the wave-8 set. Patterns are planned from the design, not yet from fleet runs. It is intended for Practitioners who discover subdomains passively. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Subfinder patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Practitioners who discover subdomains passively.

## Prerequisites

- Subfinder in the fleet tooling
- An authorized domain
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-run` | A first passive run and its output |
| 02 | `02-sources` | Configuring passive sources and API keys (keys out of repos) |
| 03 | `03-output` | Filtering and deduplicating subdomain lists |

## Repository layout

```text
subfinder-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [sublist3r-cookbook](https://github.com/ZQM-Computing/sublist3r-cookbook) — Subdomain enumeration with search-engine sources
- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [dnsrecon-cookbook](https://github.com/ZQM-Computing/dnsrecon-cookbook) — DNS enumeration from the command line
