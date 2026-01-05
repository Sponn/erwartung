# GovHydroFrancis
cim:GovHydroFrancis

Detailed hydro unit - Francis model.  This model can be used to represent three types of governors.
A schematic of the hydraulic system of detailed hydro unit models, such as Francis and Pelton, is provided in the DetailedHydroModelHydraulicSystem diagram.

*Inherits from: TurbineGovernorDynamics*

## Validations

### ta

Derivative gain (<i>Ta</i>) (&gt;= 0).  Typical value = 3.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### td

Washout time constant (<i>Td</i>) (&gt;= 0).  Typical value = 6.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ts

Gate servo time constant (<i>Ts</i>) (&gt;= 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### twnc

Water inertia time constant (<i>Twnc</i>) (&gt;= 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### twng

Water tunnel and surge chamber inertia time constant (<i>Twng</i>) (&gt;= 0). Typical value = 3.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tx

Derivative feedback gain (<i>Tx</i>) (&gt;= 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
