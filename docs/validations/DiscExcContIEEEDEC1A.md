# DiscExcContIEEEDEC1A
cim:DiscExcContIEEEDEC1A

IEEE type DEC1A discontinuous excitation control model that boosts generator excitation to a level higher than that demanded by the voltage regulator and stabilizer immediately following a system fault.
Reference: IEEE 421.5-2005, 12.2.

*Inherits from: DiscontinuousExcitationControlDynamics*

## Validations

### tan

Discontinuous controller time constant (<i>T</i><i><sub>AN</sub></i>) (&gt;= 0).  Typical value = 0,08.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### td

Time constant (<i>T</i><i><sub>D</sub></i>) (&gt;= 0).  Typical value = 0,03.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tl1

Time constant (<i>T</i><i><sub>L</sub></i><sub>1</sub>) (&gt;= 0). Typical value = 0,025.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tl2

Time constant (<i>T</i><i><sub>L</sub></i><sub>2</sub>) (&gt;= 0). Typical value = 1,25.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tw5

DEC washout time constant (<i>T</i><i><sub>W</sub></i><sub>5</sub>) (&gt;= 0).  Typical value = 5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
