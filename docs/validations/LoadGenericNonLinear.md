# LoadGenericNonLinear
cim:LoadGenericNonLinear

Generic non-linear dynamic (GNLD) load. This model can be used in mid-term and long-term voltage stability simulations (i.e., to study voltage collapse), as it can replace a more detailed representation of aggregate load, including induction motors, thermostatically controlled and static loads.

*Inherits from: LoadDynamics*

## Validations

### tp

Time constant of lag function of active power (<i>T</i><i><sub>P</sub></i>) (&gt; 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tq

Time constant of lag function of reactive power (<i>T</i><i><sub>Q</sub></i>) (&gt; 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
