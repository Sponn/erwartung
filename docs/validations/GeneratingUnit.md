# GeneratingUnit
cim:GeneratingUnit

A single or set of synchronous machines for converting mechanical power into alternating-current power. For example, individual machines within a set may be defined for scheduling purposes while a single control signal is derived for the set. In this case there would be a GeneratingUnit for each member of the set and an additional GeneratingUnit corresponding to the set.

*Inherits from: Equipment*

## Validations

### normalPF

Generating unit economic participation factor.  The sum of the participation factors across generating units does not have to sum to one. It is used for representing distributed slack participation factor. The attribute shall be a positive value or zero.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_SteadyStateHypothesis-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ratedGrossMaxP

The unit's gross rated maximum capacity (book value).
The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ratedGrossMinP

The gross rated minimum generation level which the unit can safely operate at while delivering power to the transmission grid.
The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ratedNetMaxP

The net rated maximum capacity determined by subtracting the auxiliary power used to operate the internal plant machinery from the rated gross maximum capacity.
The attribute shall be a positive value.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*
