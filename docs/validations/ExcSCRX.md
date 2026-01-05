# ExcSCRX
cim:ExcSCRX

Simple excitation system with generic characteristics typical of many excitation systems; intended for use where negative field current could be a problem.

*Inherits from: ExcitationSystemDynamics*

## Validations

### k

Gain (<i>K</i>) (&gt; 0).  Typical value = 200.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tb

Denominator time constant of lag-lead block (<i>Tb</i>) (&gt;= 0). Typical value = 10.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### te

Time constant of gain block (<i>Te</i>) (&gt; 0).  Typical value = 0,02.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
