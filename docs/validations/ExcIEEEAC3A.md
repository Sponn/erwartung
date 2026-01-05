# ExcIEEEAC3A
cim:ExcIEEEAC3A

IEEE 421.5-2005 type AC3A model. The model represents the field-controlled alternator-rectifier excitation systems designated type AC3A. These excitation systems include an alternator main exciter with non-controlled rectifiers. The exciter employs self-excitation, and the voltage regulator power is derived from the exciter output voltage.  Therefore, this system has an additional nonlinearity, simulated by the use of a multiplier whose inputs are the voltage regulator command signal, <i>Va</i>, and the exciter output voltage, <i>Efd</i>, times <i>K</i><i><sub>R</sub></i>.  This model is applicable to excitation systems employing static voltage regulators.
Reference: IEEE 421.5-2005, 6.3.

*Inherits from: ExcitationSystemDynamics*

## Validations

### efdn

Value of <i>Efd </i>at which feedback gain changes (<i>E</i><i><sub>FDN</sub></i>) (&gt; 0).  Typical value = 2,36.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ka

Voltage regulator gain (<i>K</i><i><sub>A</sub></i>) (&gt; 0). Typical value = 45,62.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### kc

Rectifier loading factor proportional to commutating reactance (<i>K</i><i><sub>C</sub></i>) (&gt;= 0).  Typical value = 0,104.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### kd

Demagnetizing factor, a function of exciter alternator reactances (<i>K</i><i><sub>D</sub></i>) (&gt;= 0).  Typical value = 0,499.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### kf

Excitation control system stabilizer gains (<i>K</i><i><sub>F</sub></i>) (&gt;= 0).  Typical value = 0,143.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### kn

Excitation control system stabilizer gain (<i>K</i><i><sub>N</sub></i>) (&gt;= 0).  Typical value = 0,05.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### kr

Constant associated with regulator and alternator field power supply (<i>K</i><i><sub>R</sub></i>) (&gt; 0).  Typical value = 3,77.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### seve1

Exciter saturation function value at the corresponding exciter voltage, <i>V</i><i><sub>E1</sub></i>, back of commutating reactance (<i>S</i><i><sub>E</sub></i><i>[V</i><i><sub>E1</sub></i><i>]</i>) (&gt;= 0). Typical value = 1,143.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### seve2

Exciter saturation function value at the corresponding exciter voltage, <i>V</i><i><sub>E2</sub></i>, back of commutating reactance (<i>S</i><i><sub>E</sub></i><i>[V</i><i><sub>E2</sub></i><i>]</i>) (&gt;= 0). Typical value = 0,1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ta

Voltage regulator time constant (<i>T</i><i><sub>A</sub></i>) (&gt; 0).  Typical value = 0,013.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tb

Voltage regulator time constant (<i>T</i><i><sub>B</sub></i>) (&gt;= 0).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc

Voltage regulator time constant (<i>T</i><i><sub>C</sub></i>) (&gt;= 0).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### te

Exciter time constant, integration rate associated with exciter control (<i>T</i><i><sub>E</sub></i>) (&gt; 0).  Typical value = 1,17.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tf

Excitation control system stabilizer time constant (<i>T</i><i><sub>F</sub></i>) (&gt; 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vamax

Maximum voltage regulator output (<i>V</i><i><sub>AMAX</sub></i>) (&gt; 0).  Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vamin

Minimum voltage regulator output (<i>V</i><i><sub>AMIN</sub></i>) (&lt; 0).  Typical value = -0,95.

- **Maximum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ve1

Exciter alternator output voltages back of commutating reactance at which saturation is defined (<i>V</i><i><sub>E1</sub></i>) (&gt; 0). Typical value = 6,24.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### ve2

Exciter alternator output voltages back of commutating reactance at which saturation is defined (<i>V</i><i><sub>E2</sub></i>) (&gt; 0). Typical value = 4,68.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vemin

Minimum exciter voltage output (<i>V</i><i><sub>EMIN</sub></i>) (&lt;= 0).  Typical value = 0.

- **Maximum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### vfemax

Exciter field current limit reference (<i>V</i><i><sub>FEMAX</sub></i>) (&gt;= 0).  Typical value = 16.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
