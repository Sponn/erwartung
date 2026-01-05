# EnergyConsumer
cim:EnergyConsumer

Generic user of energy - a  point of consumption on the power system model.
EnergyConsumer.pfixed, .qfixed, .pfixedPct and .qfixedPct have meaning only if there is no LoadResponseCharacteristic associated with EnergyConsumer or if LoadResponseCharacteristic.exponentModel is set to False.

*Inherits from: EnergyConnection*

## Validations

### p

Active power of the load. Load sign convention is used, i.e. positive sign means flow out from a node.
For voltage dependent loads the value is at rated voltage.
Starting value for a steady state solution.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-456_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### q

Reactive power of the load. Load sign convention is used, i.e. positive sign means flow out from a node.
For voltage dependent loads the value is at rated voltage.
Starting value for a steady state solution.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-456_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*
