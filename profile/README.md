# Vacation Rental Protocol (VRP)

**An open protocol for verifiable vacation rental offers on the host’s own domain.**

VRP gives AI agents, booking systems and independent verifiers a common way to verify a stay offer’s origin, integrity and freshness before presenting it to a guest.

A node publishes discovery metadata, verification keys and Ed25519-signed offers containing stay dates, availability, total price, booking conditions, expiry and a direct booking URL.

**The host’s domain remains the source of truth.**

Anyone can implement VRP and verify offers independently. Verification requires no HemmaBo account, central trust registry or operator approval.

## Start building

- [Implement a node](https://vacationrentalprotocol.com/implement)
- [Read the specification](https://github.com/vacationrentalprotocol/vrp-spec)
- [Run the conformance vectors](https://github.com/vacationrentalprotocol/vrp-spec/tree/main/examples/conformance)
- [Explore reference and independent implementations](https://github.com/vacationrentalprotocol/vrp-spec/blob/main/IMPLEMENTATIONS.md)

## Origin and governance

Created by **Rouiada Abbas**, VRP is stewarded by [three maintainers](https://github.com/vacationrentalprotocol/vrp-spec/blob/main/MAINTAINERS.md) under [published governance](https://github.com/vacationrentalprotocol/vrp-spec/blob/main/GOVERNANCE.md).

HemmaBo provides a reference implementation. Independent signing nodes and verifiers are documented alongside it. Implementations do not control access to the standard.

## Standards participation

- **IANA:** `vacation-rental.json` is [provisionally registered](https://www.iana.org/assignments/well-known-uris/) in the Well-Known URIs registry.
- **W3C community work:** Rouiada Abbas participates in the [Agent Conformance and Benchmarking Community Group](https://www.w3.org/groups/cg/agent-conformance/participants/).
- **AEP contributions:** Public proposals address non-shipped services, merchant-domain authenticity and compact signed verification summaries. See the [editorial decisions and implementation status](https://github.com/A-Comm-Tech/a-comm-evidence-protocol/blob/main/COMMENT-ROUND.md).

## Status and licensing

Current public specification: **v0.1 draft**.

Specification and documentation: **CC0-1.0**. Reference verification code and conformance vectors: **Apache-2.0**.

[Questions and contributions](https://github.com/vacationrentalprotocol/vrp-spec/issues) are welcome.
