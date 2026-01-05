# VCompIEEEType1
cim:VCompIEEEType1

<font color="#0f0f0f">Terminal voltage transducer and load compensator as defined in IEEE 421.5-2005, 4. This model is common to all excitation system models described in the IEEE Standard. </font>
<font color="#0f0f0f">Parameter details:</font>
<ol>
	<li><font color="#0f0f0f">If <i>Rc</i> and <i>Xc</i> are set to zero, the l</font>oad compensation is not employed and the behaviour is as a simple sensing circuit.</li>
</ol>
<ol>
	<li>If all parameters (<i>Rc</i>, <i>Xc</i> and <i>Tr</i>) are set to zero, the standard model VCompIEEEType1 is bypassed.</li>
</ol>
Reference: IEEE 421.5-2005 4.

*Inherits from: VoltageCompensatorDynamics*

## Validations

### rc

<font color="#0f0f0f">Resistive component of compensation of a generator (<i>Rc</i>) (&gt;= 0).</font>

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tr

<font color="#0f0f0f">Time constant which is used for the combined voltage sensing and compensation signal (<i>Tr</i>) (&gt;= 0).</font>

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### xc

<font color="#0f0f0f">Reactive component of compensation of a generator (<i>Xc</i>) (&gt;= 0).</font>

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
