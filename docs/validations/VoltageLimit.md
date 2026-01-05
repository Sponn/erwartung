# VoltageLimit
cim:VoltageLimit

Operational limit applied to voltage.
The use of operational VoltageLimit is preferred instead of limits defined at VoltageLevel. The operational VoltageLimits are used, if present.

*Inherits from: OperationalLimit*

## Validations

### normalValue

The normal limit on voltage. High or low limit nature of the limit depends upon the properties of the operational limit type. The attribute shall be a positive value or zero.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### value

Limit on voltage. High or low limit nature of the limit depends upon the properties of the operational limit type. The attribute shall be a positive value or zero.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*
