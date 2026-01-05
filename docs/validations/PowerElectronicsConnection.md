# PowerElectronicsConnection
cim:PowerElectronicsConnection

A connection to the AC network for energy production or consumption that uses power electronics rather than rotating machines.

*Inherits from: RegulatingCondEq*

## Validations

### ratedS

Nameplate apparent power rating for the unit.
The attribute shall have a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ratedU

Rated voltage (nameplate data, Ur in IEC 60909-0). It is primarily used for short circuit data exchange according to IEC 60909.
The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*
