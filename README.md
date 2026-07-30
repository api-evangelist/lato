# Lato

Lato (LATO Labs) is a San Francisco company building an agent-native research and simulation
platform for investors. Its agents source and conduct hundreds of voice interviews with verified
domain experts and customers in any language, combine them with thousands of public and
proprietary documents into a single commercial study, and turn that study into a live market
simulation that can be questioned and run scenarios against. Investors use Lato for commercial
due diligence, expert interviews, market sizing, competitive mapping, pricing studies, deal
sourcing, inbound screening, and portfolio value creation.

Founded by Tymek Staniszewski (CEO) and Tien Chu (CTO). Backed by Y Combinator (Summer 2026).

- Website: https://www.latolabs.io/
- Y Combinator: https://www.ycombinator.com/companies/lato

## API status

As of 2026-07-19 Lato publishes **no public developer API**, API documentation, SDKs, or OpenAPI
definition. `api.latolabs.io` and `docs.latolabs.io` do not serve a developer surface, and
`/docs`, `/api`, `/pricing`, `/blog`, `/llms.txt`, `/robots.txt` and `/sitemap.xml` return 404.
The `apis[]` collection is intentionally empty; this repository will be re-enriched if and when a
developer program appears.

## Artifacts

| Artifact | Path | Method |
|---|---|---|
| security.txt (RFC 9116) | `well-known/lato-security.txt` | searched |
| Well-known index | `well-known/lato-well-known.yml` | searched |
| Vulnerability disclosure | `security/lato-vulnerability-disclosure.yml` | searched |
| Domain security | `security/lato-domain-security.yml` | probed |
| llms.txt | `llms/lato-llms.txt` | generated |
