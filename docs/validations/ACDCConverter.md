# ACDCConverter
cim:ACDCConverter

A unit with valves for three phases, together with unit control equipment, essential protective and switching devices, DC storage capacitors, phase reactors and auxiliaries, if any, used for conversion.

*Inherits from: ConductingEquipment*

## Validations

### baseS

Base apparent power of the converter pole. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### idleLoss

Active power loss in pole at no power transfer. It is converter’s configuration data used in power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### maxUdc

The maximum voltage on the DC side at which the converter should operate. It is converter’s configuration data used in power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### minUdc

The minimum voltage on the DC side at which the converter should operate. It is converter’s configuration data used in power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### poleLossP

The active power loss at a DC Pole 
= idleLoss + switchingLoss*|Idc| + resitiveLoss*Idc^2.
For lossless operation Pdc=Pac.
For rectifier operation with losses Pdc=Pac-lossP.
For inverter operation with losses Pdc=Pac+lossP.
It is converter’s state variable used in power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_StateVariables-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ratedUdc

Rated converter DC voltage, also called UdN. The attribute shall be a positive value. It is converter’s configuration data used in power flow. For instance a bipolar HVDC link with value  200 kV has a 400kV difference between the dc lines.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### resistiveLoss

It is converter’s configuration data used in power flow. Refer to poleLossP. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### switchingLoss

Switching losses, relative to the base apparent power 'baseS'. Refer to poleLossP. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### targetUdc

Target value for DC voltage magnitude. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### uc

Line-to-line converter voltage, the voltage at the AC side of the valve. It is converter’s state variable, result from power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_StateVariables-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### udc

Converter voltage at the DC side, also called Ud. It is converter’s state variable, result from power flow. The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_StateVariables-AP-Con-Complex-SHACL_v3-0-0.ttl)*
