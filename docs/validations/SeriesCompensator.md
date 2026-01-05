# SeriesCompensator
cim:SeriesCompensator

A Series Compensator is a series capacitor or reactor or an AC transmission line without charging susceptance.  It is a two terminal device.

*Inherits from: ConductingEquipment*

## Validations

### varistorRatedCurrent

The maximum current the varistor is designed to handle at specified duration. It is used for short circuit calculations and exchanged only if SeriesCompensator.varistorPresent is true.
The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_ShortCircuit-AP-Con-Complex-SHACL_v3-0-0.ttl)*
