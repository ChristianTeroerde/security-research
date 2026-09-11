# Christian Terörde · Security research

Personal hall of fame for **0xWaidwerk**, containing publicly credited findings and vendor sources.

- **ESPnet** — unsafe YAML configuration loading; High, CVSS 8.8; fixed in 202609.post2. [Advisory and reporter credit](https://github.com/espnet/espnet/security/advisories/GHSA-rvjf-ppg9-9rwg).
- **PuTTY** — missing Argon2 parameter validation in PPK files; fixed in 0.85. [Vendor advisory and acknowledgment](https://www.chiark.greenend.org.uk/~sgtatham/putty/wishlist/argon2-parameter-checks.html).

Sources checked 12 September 2026. Severity and impact follow the vendor's public assessment.

## Site

Static HTML and CSS, no build step, tracking, cookies, or third-party assets.
Serve this directory with any static HTTP server. GitHub Pages can publish the root of `main`.

To add a finding, require a public vendor acknowledgment or published advisory identifying the reporter. Link the evidence, use the vendor's final severity, and check disclosure permission before adding details. Update the displayed count and verification date together.
