# WindPlantFreqPcontrolIEC
cim:WindPlantFreqPcontrolIEC

Frequency and active power controller model.
Reference: IEC 61400-27-1:2015, Annex D.

*Inherits from: IdentifiedObject*

## Validations

### tpft

Lead time constant in reference value transfer function (<i>T</i><i><sub>pft</sub></i>) (&gt;= 0). It is a project-dependent parameter.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tpfv

Lag time constant in reference value transfer function (<i>T</i><i><sub>pfv</sub></i>) (&gt;= 0). It is a project-dependent parameter.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### twpffiltp

Filter time constant for frequency measurement (<i>T</i><i><sub>WPffiltp</sub></i>) (&gt;= 0). It is a project-dependent parameter.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### twppfiltp

Filter time constant for active power measurement (<i>T</i><i><sub>WPpfiltp</sub></i>) (&gt;= 0). It is a project-dependent parameter.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
