# GovHydro1
cim:GovHydro1

Basic hydro turbine governor.

*Inherits from: TurbineGovernorDynamics*

## Validations

### at

Turbine gain (<i>At</i>) (&gt; 0).  Typical value = 1,2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### dturb

Turbine damping factor (<i>Dturb</i>) (&gt;= 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### gmin

Minimum gate opening (<i>Gmin</i>) (&gt;= 0 and &lt; GovHydro1.gmax).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### mwbase

Base for power values (<i>MWbase</i>) (&gt; 0).  Unit = MW.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### qnl

No-load flow at nominal head (<i>qnl</i>) (&gt;= 0).  Typical value = 0,08.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### rperm

Permanent droop (<i>R</i>) (&gt; 0).  Typical value = 0,04.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tf

Filter time constant (<i>Tf</i>) (&gt; 0).  Typical value = 0,05.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tg

Gate servo time constant (<i>Tg</i>) (&gt; 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tr

Washout time constant (<i>Tr</i>) (&gt; 0).  Typical value = 5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tw

Water inertia time constant (<i>Tw</i>) (&gt; 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### velm

Maximum gate velocity (<i>Vlem</i>) (&gt; 0).  Typical value = 0,2.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
