# AsynchronousMachineTimeConstantReactance
cim:AsynchronousMachineTimeConstantReactance

Parameter details:
<ol>
	<li>If <i>X'' </i>=<i> X'</i>, a single cage (one equivalent rotor winding per axis) is modelled.</li>
	<li>The “<i>p</i>” in the attribute names is a substitution for a “prime” in the usual parameter notation, e.g. <i>tpo</i> refers to <i>T'o</i>.</li>
</ol>
The parameters used for models expressed in time constant reactance form include:
- RotatingMachine.ratedS (<i>MVAbase</i>);
- RotatingMachineDynamics.damping (<i>D</i>);
- RotatingMachineDynamics.inertia (<i>H</i>);
- RotatingMachineDynamics.saturationFactor (<i>S1</i>);
- RotatingMachineDynamics.saturationFactor120 (<i>S12</i>);
- RotatingMachineDynamics.statorLeakageReactance (<i>Xl</i>);
- RotatingMachineDynamics.statorResistance (<i>Rs</i>);
- .xs (<i>Xs</i>);
- .xp (<i>X'</i>);
- .xpp (<i>X''</i>);
- .tpo (<i>T'o</i>);
- .tppo (<i>T''o</i>).

*Inherits from: AsynchronousMachineDynamics*

## Validations

### tppo

Subtransient rotor time constant (<i>T''o</i>) (&gt; 0). Typical value = 0,03.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
