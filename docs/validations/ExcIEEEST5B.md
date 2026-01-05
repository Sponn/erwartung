# ExcIEEEST5B
cim:ExcIEEEST5B

IEEE 421.5-2005 type ST5B model. The type ST5B excitation system is a variation of the type ST1A model, with alternative overexcitation and underexcitation inputs and additional limits.
The block diagram in the IEEE 421.5 standard has input signal <i>Vc </i>and does not indicate the summation point with <i>Vref</i>. The implementation of the ExcIEEEST5B shall consider summation point with <i>Vref</i>.
Reference: IEEE 421.5-2005, 7.5.

*Inherits from: ExcitationSystemDynamics*

## Validations

### kc

Rectifier regulation factor (<i>K</i><i><sub>C</sub></i>) (&gt;= 0).  Typical value = 0,004.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### kr

Regulator gain (<i>K</i><i><sub>R</sub></i>) (&gt; 0).  Typical value = 200.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t1

Firing circuit time constant (<i>T1</i>) (&gt;= 0).  Typical value = 0,004.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tb1

Regulator lag time constant (<i>T</i><i><sub>B1</sub></i>) (&gt;= 0).  Typical value = 6.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tb2

Regulator lag time constant (<i>T</i><i><sub>B2</sub></i>) (&gt;= 0).  Typical value = 0,01.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc1

Regulator lead time constant (<i>T</i><i><sub>C1</sub></i>) (&gt;= 0).  Typical value = 0,8.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc2

Regulator lead time constant (<i>T</i><i><sub>C2</sub></i>) (&gt;= 0).  Typical value = 0,08.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tob1

OEL lag time constant (<i>T</i><i><sub>OB1</sub></i>) (&gt;= 0). Typical value = 2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tob2

OEL lag time constant (<i>T</i><i><sub>OB2</sub></i>) (&gt;= 0). Typical value = 0,08.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### toc1

OEL lead time constant (<i>T</i><i><sub>OC1</sub></i>) (&gt;= 0). Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### toc2

OEL lead time constant (<i>T</i><i><sub>OC2</sub></i>) (&gt;= 0). Typical value = 0,08.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tub1

UEL lag time constant (<i>T</i><i><sub>UB1</sub></i>) (&gt;= 0). Typical value = 10.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tub2

UEL lag time constant (<i>T</i><i><sub>UB2</sub></i>) (&gt;= 0). Typical value = 0,05.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tuc1

UEL lead time constant (<i>T</i><i><sub>UC1</sub></i>) (&gt;= 0). Typical value = 2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tuc2

UEL lead time constant (<i>T</i><i><sub>UC2</sub></i>) (&gt;= 0). Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vrmax

Maximum voltage regulator output (<i>V</i><i><sub>RMAX</sub></i>) (&gt; 0).  Typical value = 5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vrmin

Minimum voltage regulator output (<i>V</i><i><sub>RMIN</sub></i>) (&lt; 0).  Typical value = -4.

- **Maximum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
