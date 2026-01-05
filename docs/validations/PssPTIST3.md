# PssPTIST3
cim:PssPTIST3

PTI microprocessor-based stabilizer type 3.

*Inherits from: PowerSystemStabilizerDynamics*

## Validations

### dtc

Time step related to activation of controls (<i>deltatc</i>) (&gt;= 0).  Typical value = 0,025 (0,03 for 50 Hz).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### dtf

Time step frequency calculation (<i>deltatf</i>) (&gt;= 0). Typical value = 0,025 (0,03 for 50 Hz).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### dtp

Time step active power calculation (<i>deltatp</i>) (&gt;= 0). Typical value = 0,0125  (0,015 for 50 Hz).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### nav

Number of control outputs to average (<i>NAV</i>) (1 &lt;= <i>NAV</i> &lt;= 16).  Typical value = 4.

- **Maximum Value**: 16.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
- **Minimum Value**: 1.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ncl

Number of counts at limit to active limit function (<i>NCL</i>) (&gt; 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t1

Time constant (<i>T1</i>) (&gt;= 0).  Typical value = 0,3.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t2

Time constant (<i>T2</i>) (&gt;= 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t3

Time constant (<i>T3</i>) (&gt;= 0).  Typical value = 0,2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t4

Time constant (<i>T4</i>) (&gt;= 0).  Typical value = 0,05.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t5

Time constant (<i>T5</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t6

Time constant (<i>T6</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tf

Time constant (<i>Tf</i>) (&gt;= 0).  Typical value = 0,2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tp

Time constant (<i>Tp</i>) (&gt;= 0).  Typical value = 0,2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
