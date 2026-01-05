# ExcHU
cim:ExcHU

Hungarian excitation system, with built-in voltage transducer.

*Inherits from: ExcitationSystemDynamics*

## Validations

### te

Major loop PI tag integration time constant (<i>Te</i>) (&gt;= 0). Typical value = 0,154.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ti

Minor loop PI control tag integration time constant (<i>Ti</i>) (&gt;= 0).  Typical value = 0,01333.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tr

Filter time constant (<i>Tr</i>) (&gt;= 0). If a voltage compensator is used in conjunction with this excitation system model, <i>Tr </i>should be set to 0.  Typical value = 0,01.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
