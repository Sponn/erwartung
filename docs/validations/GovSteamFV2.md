# GovSteamFV2
cim:GovSteamFV2

Steam turbine governor with reheat time constants and modelling of the effects of fast valve closing to reduce mechanical power.

*Inherits from: TurbineGovernorDynamics*

## Validations

### mwbase

Alternate base used instead of machine base in equipment model if necessary (<i>MWbase</i>) (&gt; 0).  Unit = MW.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t1

Governor time constant (<i>T1</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t3

Reheater time constant (<i>T3</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ta

Time after initial time for valve to close (<i>Ta</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tb

Time after initial time for valve to begin opening (<i>Tb</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc

Time after initial time for valve to become fully open (<i>Tc</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tt

Time constant with which power falls off after intercept valve closure (<i>Tt</i>) (&gt;= 0).

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
