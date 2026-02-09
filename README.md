# Terraform Provider for Firewalla MSP

The Firewalla MSP provider is used to query the limited offerings provided by the Firewalla MSP API, most notably, the ability to maintain custom Target Lists. If you have a Firewalla box, note that Firewalla does not expose the API without a separate Firewalla MSP subscription, from which this provider leverages.

The provider uses the firewalla-msp-go library to interact with the Firewalla MSP API.

Currently, this provider has been tested against Firewalla MSP version 2.9.1. Given that Firewalla has largely treated the API as something of an afterthought, functionality outside of the specific version number is unknown.

[Provider Documentation](./docs/index.md)

Source code will be hosted on [codeforge](https://codeberg.org/joncoole/terraform-provider-firewalla-msp) where contributions are most welcome.
