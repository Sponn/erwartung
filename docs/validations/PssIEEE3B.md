# PssIEEE3B
cim:PssIEEE3B

IEEE 421.5-2005 type PSS3B power system stabilizer model. The PSS model PSS3B has dual inputs of electrical power and rotor angular frequency deviation. The signals are used to derive an equivalent mechanical power signal.
This model has 2 input signals. They have the following fixed types (expressed in terms of InputSignalKind values): the first one is of rotorAngleFrequencyDeviation type and the second one is of generatorElectricalPower type.
Reference: IEEE 3B 421.5-2005, 8.3.

*Inherits from: PowerSystemStabilizerDynamics*

## Validations

### t1

Transducer time constant (<i>T1</i>) (&gt;= 0).  Typical value = 0,012.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### t2

Transducer time constant (<i>T2</i>) (&gt;= 0).  Typical value = 0,012.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tw1

Washout time constant (<i>Tw1</i>) (&gt;= 0).  Typical value = 0,3.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tw2

Washout time constant (<i>Tw2</i>) (&gt;= 0).  Typical value = 0,3.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tw3

Washout time constant (<i>Tw3</i>) (&gt;= 0).  Typical value = 0,6.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
