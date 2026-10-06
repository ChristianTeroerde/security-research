# Christian Terörde · Security research

Personal hall of fame for **0xWaidwerk**, containing publicly credited findings and vendor sources.

- **ESPnet** — unsafe YAML configuration loading; High, CVSS 8.8; fixed in 202609.post2. [Advisory and reporter credit](https://github.com/espnet/espnet/security/advisories/GHSA-rvjf-ppg9-9rwg).
- **PuTTY** — missing Argon2 parameter validation in PPK files; fixed in 0.85. [Vendor advisory and acknowledgment](https://www.chiark.greenend.org.uk/~sgtatham/putty/wishlist/argon2-parameter-checks.html).
- **OpenCOOP** — unauthenticated MCP host transport allowed read/write access to files in the configured workspace; High; fixed in `@opencoop/opencode-plugin` 1.15.0. [Advisory and accepted reporter credit](https://github.com/Pajand/opencoop/security/advisories/GHSA-8627-5r8q-pp5p).
- **BizFilo Shopify MCP** — unauthenticated network access to tools using the operator's Shopify token; fixed in `@buildwithabid/shopify-mcp-server` 1.1.1. [Vendor fix and reporter credit](https://github.com/buildwithabid/shopify-mcp#security).
- **ClickOnSearch WhatsApp MCP** — unauthenticated network access to MCP tools; High, CVSS 8.1; fixed in `@clickonsearch/whatsapp-mcp-server` 0.2.0. [Vendor advisory and reporter credit](https://github.com/ClickOnSearch/ai-apps/blob/main/advisories/2026-10-06-mcp-servers-network-exposure.md).

Sources checked 6 October 2026. Severity and impact follow the vendors' public assessments.

## Site

Static HTML and CSS, no build step, tracking, cookies, or third-party assets.
Serve this directory with any static HTTP server. GitHub Pages can publish the root of `main`.

To add a finding, require a public vendor acknowledgment or published advisory identifying the reporter. Link the evidence, use the vendor's final severity, and check disclosure permission before adding details. Update the displayed count and verification date together.
