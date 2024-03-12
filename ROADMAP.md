# CitrineOS Roadmap

Welcome to the official roadmap for **CitrineOS**. This document outlines the planned features, improvements, and goals for the project. Please note that the timeline and features might change based on community feedback, technical challenges, and other unforeseen circumstances.

---

## Table of Contents

- [Current Version](#current-version)
- [Next Release](#next-release)
- [Future Plans](#future-plans)
- [Contribution](#contribution)
- [Feedback and Suggestions](#feedback-and-suggestions)

---

## Current Version

- **Version**: 1.0.0
- **Highlights**: First release version. Passes Core and Advanced Security tests using OCA's Testing Tool (OCTT results in [Tests]) 
- **Ongoing Work**: Stable release
- **3rd Party Modules**: Stripe Payment

---

## Next Release

- **Target Version**: 1.1.0
- **Estimated Release Date**: 2024-04-03
- **Features & Improvements**:
  - Support for Advanced Device Management & Advanced UI certification profiles
  - New Location data model supporting:
    - Geolocation
    - Device Status
    - Directus Flows for sending OCPP messages via message api
  - Misc:
    - Refactor of CentralSystem code to better support alternative architectures (such as putting CitrineOS behind an api gateway)
    - In-Memory option for message bus
    - Refactor of project to be an npm workspace; publication of dependencies to npm registry

---

## Future Plans

### 1.2.X

- **Planned Features**:
  - ISO 15118 support certification profile
  - Improved certificate handling
    - Support for replacing certificates without restarting application
    - Support for external Certificate Authorities
  - OICP Roaming module
  - Scan and Charge

### 1.3.X 

- **Planned Features**:
  - Smart Charging certification profile

### 1.4.X 

- **Planned Features**:
  - Reservation & Local Authorization List Management certification profiles (completes OCPP 2.0.1 support)

---

## Contribution

We're always looking for contributors to help us improve **CitrineOS**. If you're interested, please check out our [CONTRIBUTING.md](https://github.com/citrineos/citrineos/blob/main/CONTRIBUTING.md) guide for more details.

---

## Feedback and Suggestions

Your feedback is valuable to us! If you have any suggestions or encounter any issues, please [create an issue](https://github.com/citrineos/citrineos/issues) on our GitHub repository. Note: Please do not create issues on the citrineos-core repository directly moving forward!

---

See something here that you wish was happening sooner, say support for the **Local Authorization List Management** OCPP Certification Profile? Begin working on it! Let us know as well so we can support you and make sure multiple people aren't pursuing the same goals separately.

See something that's not here that you think should be? Let us know! Maybe there's a reason, maybe we haven't considered it and we'd love your input and help. This roadmap will grow and change with your feedback.

Looking to start making a 3rd-party module now? Let us know now! Although thorough documentation for that process doesn't currently exist, we'd love to start figuring it out with you.

The more people interested in helping with development, the more development we can plan.

Thank you for being a part of the **CitrineOS** community! Together, we'll make this project better every day.

[Tests]: TESTS.md
