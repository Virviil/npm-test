# axios-cve-test

Test repo for following CVE-2026-67317 through Aikido and the Root.io sync.

- `axios` is pinned to **1.17.0** (affected range: >= 1.7.0, < 1.18.0, fixed in 1.18.0).
- NVD (NIST) CVSS 3.1: 7.5 HIGH. GitHub / VulnCheck CVSS 4.0: 6.3 MEDIUM (GHSA-jqh4-m9w3-8hp9).
- Lockfile is committed so scanners resolve the exact version.
