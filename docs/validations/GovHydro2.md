# GovHydro2
cim:GovHydro2

IEEE hydro turbine governor with straightforward penstock configuration and hydraulic-dashpot governor.

*Inherits from: TurbineGovernorDynamics*

## Validations

### bturb

Turbine denominator multiplier (<i>Bturb</i>) (&gt; 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### mwbase

Base for power values (<i>MWbase</i>) (&gt; 0).  Unit = MW.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tg

Gate servo time constant (<i>Tg</i>) (&gt; 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tp

Pilot servo valve time constant (<i>Tp</i>) (&gt;= 0).  Typical value = 0,03.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tr

Dashpot time constant (<i>Tr</i>) (&gt;= 0).  Typical value = 12.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tw

Water inertia time constant (<i>Tw</i>) (&gt;= 0).  Typical value = 2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### uc

Maximum gate closing velocity (<i>Uc</i>) (&lt; 0).  Unit = PU / s. Typical value = -0,1.

- **Maximum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
