# UnderexcLimIEEE2
cim:UnderexcLimIEEE2

Type UEL2 underexcitation limiter which has either a straight-line or multi-segment characteristic when plotted in terms of machine reactive power output vs. real power output.
Reference: IEEE UEL2 421.5-2005, 10.2  (limit characteristic lookup table shown in Figure 10.4 (p 32)).

*Inherits from: UnderexcitationLimiterDynamics*

## Validations

### tu1

UEL lead time constant (<i>T</i><i><sub>U1</sub></i>) (&gt;= 0). Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tu2

UEL lag time constant (<i>T</i><i><sub>U2</sub></i>) (&gt;= 0). Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tu3

UEL lead time constant (<i>T</i><i><sub>U3</sub></i>) (&gt;= 0). Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tu4

UEL lag time constant (<i>T</i><i><sub>U4</sub></i>) (&gt;= 0). Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tul

Time constant associated with optional integrator feedback input signal to UEL (<i>T</i><i><sub>UL</sub></i>) (&gt;= 0).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tup

Real power filter time constant (<i>T</i><i><sub>UP</sub></i>) (&gt;= 0).  Typical value = 5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tuq

Reactive power filter time constant (<i>T</i><i><sub>UQ</sub></i>) (&gt;= 0).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tuv

Voltage filter time constant (<i>T</i><i><sub>UV</sub></i>) (&gt;= 0).  Typical value = 5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
