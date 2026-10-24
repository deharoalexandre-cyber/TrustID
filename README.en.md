# TrustID

**English · [Français](README.md)**

**Proprietary documentation — all rights reserved.** No reuse beyond GitHub platform functions is authorized without the rights holders' written consent. [Rights notice](NOTICE.md).
[Elyne Corp product map](https://github.com/deharoalexandre-cyber/deharoalexandre-cyber)

TrustID is Elyne Corp's family of local identity and endpoint security products. It combines behavioral signals, system checks, a trust score, and responses governed by the operator's policy.

| Edition | Overview | Status shown on the website |
| --- | --- | --- |
| **v1.5 Windows** | Layered protection and weighted trust scoring, without v3's CCD engine. | Production |
| **v3 Windows** | Eleven detection layers and an eight-agent CCD engine, with case memory and governance. | Production |
| **v3 Linux** | Port of the mechanisms to Linux primitives and a systemd service. | Local package and documentation available; deployment qualification to be specified |

TrustID runs on the protected endpoint. Its signals and decisions do not require sending data to a cloud service. Actual capabilities and dependencies vary by edition and environment.

## Architecture and validation

- [Simplified architecture](docs/architecture.en.md)
- [Identified tests, results, and limits](docs/evidence.en.md)
- [Ownership notice](NOTICE.md)

“Production” is the commercial status displayed in the [Elyne Corp catalog](https://elynecorp.com/). It is not a substitute for acceptance testing on a customer's configuration. MITRE technique counts, response times, and cryptographic guarantees must be tied to a specific edition and qualification report before being used as contractual claims.

## Evaluation

Source code, configurations, logs, and unredacted audit reports are not included in this documentation repository. To discuss an edition and its scope: [admin@elynecorp.fr](mailto:admin@elynecorp.fr) · [elynecorp.com](https://elynecorp.com/).
