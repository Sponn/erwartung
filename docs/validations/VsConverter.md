# VsConverter
cim:VsConverter

DC side of the voltage source converter (VSC).

*Inherits from: ACDCConverter*

## Validations

### delta

Angle between VsConverter.uv and ACDCConverter.uc. It is converter’s state variable used in power flow. The attribute shall be a positive value or zero.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_StateVariables-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### droop

Droop constant. The pu value is obtained as D [kV/MW] x Sb / Ubdc. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### droopCompensation

Compensation constant. Used to compensate for voltage drop when controlling voltage at a distant bus. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### maxModulationIndex

The maximum quotient between the AC converter voltage (Uc) and DC voltage (Ud). A factor typically less than 1. It is converter’s configuration data used in power flow.

- **Maximum Value**: 1.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### qShare

Reactive power sharing factor among parallel converters on Uac control. The attribute shall be a positive value or zero.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### targetPWMfactor

Magnitude of pulse-modulation factor. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### targetPhasePcc

Phase target at AC side, at point of common coupling. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### targetPowerFactorPcc

Power factor target at the AC side, at point of common coupling. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### targetUpcc

Voltage target in AC grid, at point of common coupling. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### uv

Line-to-line voltage on the valve side of the converter transformer. It is converter’s state variable, result from power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_StateVariables-AP-Con-Complex-SHACL_v3-0-0.ttl)*
