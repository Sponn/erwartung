# SynchronousMachineDetailed
cim:SynchronousMachineDetailed

All synchronous machine detailed types use a subset of the same data parameters and input/output variables.  
The several variations differ in the following ways:
- the number of  equivalent windings that are included;
- the way in which saturation is incorporated into the model;
- whether or not “subtransient saliency” (<i>X''q</i> not = <i>X''d</i>) is represented.
It is not necessary for each simulation tool to have separate models for each of the model types.  The same model can often be used for several types by alternative logic within the model.  Also, differences in saturation representation might not result in significant model performance differences so model substitutions are often acceptable.

*Inherits from: SynchronousMachineDynamics*

## Validations

### efdBaseRatio

Ratio (exciter voltage/generator voltage) of <i>Efd</i> bases of exciter and generator models (&gt; 0). Typical value = 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### saturationFactorQAxis

Quadrature-axis saturation factor at rated terminal voltage (<i>S1q</i>) (&gt;= 0). Typical value = 0,02.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-302_Dynamics-AP-Con-Complex-SHACL_v3-0-0.ttl)*
