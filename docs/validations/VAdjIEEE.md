# VAdjIEEE
cim:VAdjIEEE

IEEE voltage adjuster which is used to represent the voltage adjuster in either a power factor or VAr control system.
Reference: IEEE 421.5-2005, 11.1.

*Inherits from: VoltageAdjusterDynamics*

## Validations

### taoff

Time that adjuster pulses are off (<i>T</i><i><sub>AOFF</sub></i>) (&gt;= 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### taon

Time that adjuster pulses are on (<i>T</i><i><sub>AON</sub></i>) (&gt;= 0).  Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
