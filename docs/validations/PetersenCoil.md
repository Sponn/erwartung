# PetersenCoil
cim:PetersenCoil

A variable impedance device normally used to offset line charging during single line faults in an ungrounded section of network.

*Inherits from: EarthFaultCompensator*

## Validations

### offsetCurrent

The offset current that the Petersen coil controller is operating from the resonant point.  This is normally a fixed amount for which the controller is configured and could be positive or negative. Typically 0 to 60 A depending on voltage and resonance conditions.

- **Maximum Value**: 60.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_ShortCircuit-AP-Con-Complex-SHACL_v3-0-0.ttl)*
- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_ShortCircuit-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### positionCurrent

The control current used to control the Petersen coil also known as the position current.  Typically in the range of 20 mA to 200 mA.

- **Maximum Value**: 0.2
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_ShortCircuit-AP-Con-Complex-SHACL_v3-0-0.ttl)*
- **Minimum Value**: 0.02
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_ShortCircuit-AP-Con-Complex-SHACL_v3-0-0.ttl)*
