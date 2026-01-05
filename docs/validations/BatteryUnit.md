# BatteryUnit
cim:BatteryUnit

An electrochemical energy storage device.

*Inherits from: PowerElectronicsUnit*

## Validations

### ratedE

Full energy storage capacity of the battery. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### storedE

Amount of energy currently stored. The attribute shall be a positive value or zero and lower than BatteryUnit.ratedE.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*
