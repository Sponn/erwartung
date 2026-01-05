# SynchronousMachineTimeConstantReactance
cim:SynchronousMachineTimeConstantReactance

Synchronous machine detailed modelling types are defined by the combination of the attributes SynchronousMachineTimeConstantReactance.modelType and SynchronousMachineTimeConstantReactance.rotorType.  
Parameter details:
<ol>
	<li>The “p” in the time-related attribute names is a substitution for a “prime” in the usual parameter notation, e.g. tpdo refers to <i>T'do</i>.</li>
	<li>The parameters used for models expressed in time constant reactance form include:</li>
</ol>
- RotatingMachine.ratedS (<i>MVAbase</i>);
- RotatingMachineDynamics.damping (<i>D</i>);
- RotatingMachineDynamics.inertia (<i>H</i>);
- RotatingMachineDynamics.saturationFactor (<i>S1</i>);
- RotatingMachineDynamics.saturationFactor120 (<i>S12</i>);
- RotatingMachineDynamics.statorLeakageReactance (<i>Xl</i>);
- RotatingMachineDynamics.statorResistance (<i>Rs</i>);
- SynchronousMachineTimeConstantReactance.ks (<i>Ks</i>);
- SynchronousMachineDetailed.saturationFactorQAxis (<i>S1q</i>);
- SynchronousMachineDetailed.saturationFactor120QAxis (<i>S12q</i>);
- SynchronousMachineDetailed.efdBaseRatio;
- SynchronousMachineDetailed.ifdBaseType;
- .xDirectSync (<i>Xd</i>);
- .xDirectTrans (<i>X'd</i>);
- .xDirectSubtrans (<i>X''d</i>);
- .xQuadSync (<i>Xq</i>);
- .xQuadTrans (<i>X'q</i>);
- .xQuadSubtrans (<i>X''q</i>);
- .tpdo (<i>T'do</i>);
- .tppdo (<i>T''do</i>);
- .tpqo (<i>T'qo</i>);
- .tppqo (<i>T''qo</i>);
- .tc.

*Inherits from: SynchronousMachineDetailed*

## Validations

### ks

Saturation loading correction factor (<i>Ks</i>) (&gt;= 0). Used only by type J model.  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tc

Damping time constant for “Canay” reactance (&gt;= 0).  Typical value = 0.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tppdo

Direct-axis subtransient rotor time constant (<i>T''do</i>) (&gt; 0).  Typical value = 0,03.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### tppqo

Quadrature-axis subtransient rotor time constant (<i>T''qo</i>) (&gt; 0). Typical value = 0,03.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
