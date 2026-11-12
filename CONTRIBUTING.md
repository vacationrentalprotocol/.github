# Contributing to Vacation Rental Protocol projects

Contributions from independent hosts, booking-system developers, agent developers and other implementers are welcome.

## Choose the repository

- [vrp-spec](https://github.com/vacationrentalprotocol/vrp-spec): specification text, schemas and public conformance vectors. Follow its [contribution guide](https://github.com/vacationrentalprotocol/vrp-spec/blob/main/CONTRIBUTING.md) and [governance](https://github.com/vacationrentalprotocol/vrp-spec/blob/main/GOVERNANCE.md).
- [vrp-verify](https://github.com/vacationrentalprotocol/vrp-verify): the JavaScript verifier package, its tests and documentation.
- [.github](https://github.com/vacationrentalprotocol/.github): the public organization profile and these shared community files.

## Report a problem or propose a change

Open an issue in the affected repository. Explain the current behavior, the expected behavior and a reproducible example where possible. For a larger change, discuss the approach before implementing it.

For suspected vulnerabilities, follow the affected repository's security policy. Do not include private keys, credentials or personal guest information in public issues.

## Submit a pull request

Keep each pull request focused. Explain what changes, why it is needed and how you checked it. Follow the affected repository's README and any local contribution instructions.

For verifier code changes, run `npm test` and include an appropriate regression or conformance case. Documentation-only changes should be checked for accuracy, working links and rendering. Report checks honestly, including anything not run.

A change to an implementation does not change the VRP specification. Propose normative protocol changes in vrp-spec under its governance process.

## Licensing and conduct

Each repository's own license applies to contributions there. The specification and its documentation use CC0-1.0; vrp-verify uses Apache-2.0. Consult the relevant repository for the complete license boundary.

Follow the [VRP Code of Conduct](https://github.com/vacationrentalprotocol/vrp-spec/blob/main/CODE_OF_CONDUCT.md). Repository-specific instructions take precedence over these shared defaults.
