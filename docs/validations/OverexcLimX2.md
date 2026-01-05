# OverexcLimX2
cim:OverexcLimX2

Field voltage or current overexcitation limiter designed to protect the generator field of an AC machine with automatic excitation control from overheating due to prolonged overexcitation.

*Inherits from: OverexcitationLimiterDynamics*

## Validations

### t1

Time to trip the exciter at the low voltage or current point on the inverse time characteristic (<i>TIME</i><i><sub>1</sub></i>) (&gt;= 0). Typical value = 120.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t2

Time to trip the exciter at the mid voltage or current point on the inverse time characteristic (<i>TIME</i><i><sub>2</sub></i>) (&gt;= 0). Typical value = 40.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t3

Time to trip the exciter at the high voltage or current point on the inverse time characteristic (<i>TIME</i><i><sub>3</sub></i>) (&gt;= 0). Typical value = 15.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vlow

Low voltage limit (<i>V</i><i><sub>LOW</sub></i>) (&gt; 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
