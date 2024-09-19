# CitrineOS

![CitrineOS Logo](assets/logo_white.png#gh-dark-mode-only)
![CitrineOS Logo](assets/logo_black.png#gh-light-mode-only)

The primary goal of CitrineOS is to develop and maintain an open source Charging Station Management System (CSMS) software stack. CitrineOS is developed having modularity and extensibility in mind. It consists of logically separated modules, each encapsulating a subset of functionality pertaining to the definitions of **OCPP 2.0.1** - *Open Charge Point Protocol the standard protocol for communication between charging stations and charge management software*. All modules handle and emit all necessary OCPP messages and are losely coupled by a message broker interface connecting them to a central component that relays the messages to the charging station and vice versa.

With CitrineOS we hope to speed the adoption to eMobility by providing everyone with a thorougly tested and reliable OCPP 2.0.1 reference implementation. CitrineOS will further enable more focus on new features like local energy management, reservations, PV integration, AI tooling, and many more. The CitrineOS project was initiated by S44 LLC, to help with the electrification of the mobility sector.

For questions and support please join our [Discord](https://discord.gg/FhkRJknV3N).

## Getting Started

To get started with CitrineOS, please read our [Guide](https://citrineos.github.io/docs/getting-started.html). CitrineOS's core repository is accessible here:

- [citrineos-core](https://github.com/citrineos/citrineos-core)

## Project Status

- **GitHub Repository:** [CitrineOS Repository](https://github.com/citrineos/citrineos)
- **Website:** [CitrineOS Project Website](https://citrineos.github.io)
- [**See Core Releases**](https://github.com/citrineos/citrineos-core/releases)
- **Last Commit:** [![Last Commit](https://img.shields.io/github/last-commit/citrineos/citrineos-core)](https://github.com/citrineos/citrineos-core/commits/main)

### Overview

- Complete implementation of OCPP 2.0.1, including: Core, Advanced Security, Advanced Device Management, Advanced User Interface, ISO15118 Support, Smart Charging, Reservations, and Local Auth List Management 
- Generated OpenAPI specification, OCPP 2.0.1 types generated from OCPP 2.0.1 Part 3 JSON schemas
- Testing conducted through [OCA's OCTT](https://www.openchargealliance.org/protocols/test-tool-ocpp-201/)

### Roadmap

See on our [project website](https://citrineos.github.io/docs/roadmap.html).

### Hardware Compatibility
CitrineOS has been successfully tested with systems from the following charging providers:

- ABB
- aixACCT
- Alfen
- ChargePoint
- ChargeSim
- Compleo
- EVBox
- EVerest
- SwitchEV
- VectorInformatik
- Wallbox
- XCharge


## Contributing

We welcome contributions from developers and enthusiasts who share our passion for clean energy and sustainable transportation. If you'd like to contribute to CitrineOS, please read our [Contribution Guidelines].

## Governance

This project's governance is located in [GOVERNANCE.md](GOVERNANCE.md).

## Support

If you encounter any issues or have questions about CitrineOS, please [open an issue](https://github.com/citrineos/citrineos/issues) on our GitHub repository, and our community will be happy to assist you.

Thank you for your interest in CitrineOS. Together, we can drive innovation, reshape the EV charging landscape, and create a cleaner, more sustainable world.

- [Changelog]
- [GitHub Pages](https://citrineos.github.io/)

## Licensing

CitrineOS and its subprojects are licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for the full license text.

## Special Thanks

| Avatar    | Contributor | Credit for |
|----------:|------------:|------------:|
| ![](https://avatars.githubusercontent.com/u/118277948?s=64&v=4) | [@miriamCodes](https://github.com/miriamCodes) | [citrineos.github.io](citrineos.github.io) |

[Changelog]: CHANGELOG.md
[Contribution Guidelines]: CONTRIBUTING.md
