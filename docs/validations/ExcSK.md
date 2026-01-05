# ExcSK
cim:ExcSK

Slovakian excitation system.  UEL and secondary voltage control are included in this model. When this model is used, there cannot be a separate underexcitation limiter or VAr controller model.

*Inherits from: ExcitationSystemDynamics*

## Validations

### sbase

Apparent power of the unit (<i>Sbase</i>) (&gt; 0).  Unit = MVA. Typical value = 259.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc

PI controller phase lead time constant (<i>Tc</i>) (&gt;= 0). Typical value = 8.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### te

Time constant of gain block (<i>Te</i>) (&gt;= 0).  Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ti

PI controller phase lead time constant (<i>Ti</i>) (&gt;= 0). Typical value = 2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tp

Time constant (<i>Tp</i>) (&gt;= 0).  Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tr

Voltage transducer time constant (<i>Tr</i>) (&gt;= 0).  Typical value = 0,01.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
