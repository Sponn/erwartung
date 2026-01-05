# OverexcLimX1
cim:OverexcLimX1

Field voltage over excitation limiter.

*Inherits from: OverexcitationLimiterDynamics*

## Validations

### t1

Time to trip the exciter at the low voltage point on the inverse time characteristic (<i>TIME</i><i><sub>1</sub></i>) (&gt;= 0).  Typical value = 120.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t2

Time to trip the exciter at the mid voltage point on the inverse time characteristic (<i>TIME</i><i><sub>2</sub></i>) (&gt;= 0).  Typical value = 40.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t3

Time to trip the exciter at the high voltage point on the inverse time characteristic (<i>TIME</i><i><sub>3</sub></i>) (&gt;= 0). Typical value = 15.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vlow

Low voltage limit (<i>V</i><i><sub>LOW</sub></i>) (&gt; 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
