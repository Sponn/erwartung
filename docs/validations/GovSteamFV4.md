# GovSteamFV4
cim:GovSteamFV4

Detailed electro-hydraulic governor for steam unit.

*Inherits from: TurbineGovernorDynamics*

## Validations

### ta

Control valves rate opening time (<i>Ta</i>) (&gt;= 0).  Typical value = 0,8.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tam

Intercept valves rate opening time (<i>Tam</i>) (&gt;= 0). Typical value = 0,8.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc

Control valves rate closing time (<i>Tc</i>) (&gt;= 0).  Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tcm

Intercept valves rate closing time (<i>Tcm</i>) (&gt;= 0). Typical value = 0,5.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tdc

Derivative time constant of pressure regulator (<i>Tdc</i>) (&gt;= 0).  Typical value = 90.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tf1

Time constant of fuel regulation (<i>Tf1</i>) (&gt;= 0). Typical value = 10.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tf2

Time constant of steam chest (<i>Tf2</i>) (&gt;= 0).  Typical value = 10.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### thp

High pressure (HP) time constant of the turbine (<i>Thp</i>) (&gt;= 0).  Typical value = 0,15.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tmp

Low pressure (LP) time constant of the turbine (<i>Tmp</i>) (&gt;= 0).  Typical value = 0,4.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### trh

Reheater  time constant of the turbine (<i>Trh</i>) (&gt;= 0). Typical value = 10.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tv

Boiler time constant (<i>Tv</i>) (&gt;= 0).  Typical value = 60.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ty

Control valves servo time constant (<i>Ty</i>) (&gt;= 0). Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
