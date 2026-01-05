# PssRQB
cim:PssRQB

Power system stabilizer type RQB. This power system stabilizer is intended to be used together with excitation system type ExcRQB, which is primarily used in nuclear or thermal generating units.

*Inherits from: PowerSystemStabilizerDynamics*

## Validations

### t4f

Lead lag time constant (<i>T4F</i>) (&gt;= 0). Typical value = 0,045.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t4m

Input time constant (<i>T4M</i>) (&gt;= 0). Typical value = 5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t4mom

Speed time constant (<i>T4MOM</i>) (&gt;= 0). Typical value = 1,27.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tomd

Speed delay (<i>TOMD</i>) (&gt;= 0). Typical value = 0,02.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tomsl

Speed time constant (<i>TOMSL</i>) (&gt;= 0). Typical value = 0,04.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
