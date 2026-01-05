# LoadComposite
cim:LoadComposite

Combined static load and induction motor load effects.
The dynamics of the motor are simplified by linearizing the induction machine equations.

*Inherits from: LoadDynamics*

## Validations

### h

Inertia constant (<i>H</i>) (&gt;= 0).  Typical value = 2,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### pfrac

Fraction of constant-power load to be represented by this motor model (<i>P</i><i><sub>FRAC</sub></i>) (&gt;= 0,0 and &lt;= 1,0).  Typical value = 0,5.

- **Maximum Value**: 1.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
