# Switch
cim:Switch

A generic device designed to close, or open, or both, one or more electric circuits.  All switches are two terminal devices including grounding switches. The ACDCTerminal.connected at the two sides of the switch shall not be considered for assessing switch connectivity, i.e. only Switch.open, .normalOpen and .locked are relevant.

*Inherits from: ConductingEquipment*

## Validations

### ratedCurrent

The maximum continuous current carrying capacity in amps governed by the device material and construction.
The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*
