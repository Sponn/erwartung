# ExcBBC
cim:ExcBBC

Transformer fed static excitation system (static with ABB regulator). This model represents a static excitation system in which a gated thyristor bridge fed by a transformer at the main generator terminals feeds the main generator directly.

*Inherits from: ExcitationSystemDynamics*

## Validations

### t1

Controller time constant (<i>T1</i>) (&gt;= 0).  Typical value = 6.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t2

Controller time constant (<i>T2</i>) (&gt;= 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t3

Lead/lag time constant (<i>T3</i>) (&gt;= 0).  If = 0, block is bypassed.  Typical value = 0,05.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t4

Lead/lag time constant (<i>T4</i>) (&gt;= 0).  If = 0, block is bypassed.  Typical value = 0,01.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### xe

Effective excitation transformer reactance (<i>Xe</i>) (&gt;= 0). <i>Xe</i> models the regulation of the transformer/rectifier unit. Typical value = 0,05.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
