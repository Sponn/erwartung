# GovGAST1
cim:GovGAST1

Modified single shaft gas turbine.

*Inherits from: TurbineGovernorDynamics*

## Validations

### b

Turbine power time constant denominator scale factor (<i>b</i>) (&gt;0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### mwbase

Base for power values (<i>MWbase</i>) (&gt; 0).  Unit = MW.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### r

Permanent droop (<i>R</i>) (&gt;0).  Typical value = 0,04.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t1

Governor mechanism time constant (<i>T1</i>) (&gt;= 0). <i>T1</i> represents the natural valve positioning time constant of the governor for small disturbances, as seen when rate limiting is not in effect.  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t2

Turbine power time constant (<i>T2</i>) (&gt;= 0). <i>T2</i> represents delay due to internal energy storage of the gas turbine engine. <i>T2</i> can be used to give a rough approximation to the delay associated with acceleration of the compressor spool of a multi-shaft engine, or with the compressibility of gas in the plenum of the free power turbine of an aero-derivative unit, for example.  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t3

Turbine exhaust temperature time constant (<i>T3</i>) (&gt;= 0). <i>T3</i> represents delay in the exhaust temperature and load limiting system. Typical value = 3.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t4

Governor lead time constant (<i>T4</i>) (&gt;= 0).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t5

Governor lag time constant (<i>T5</i>) (&gt;= 0).  If = 0, entire gain and lead-lag block is bypassed.  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tltr

Valve position averaging time constant (<i>Tltr</i>) (&gt;= 0). Typical value = 10.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
