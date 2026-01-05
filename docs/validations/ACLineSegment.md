# ACLineSegment
cim:ACLineSegment

A wire or combination of wires, with consistent electrical characteristics, building a single electrical system, used to carry alternating current between points in the power system.
For symmetrical, transposed three phase lines, it is sufficient to use attributes of the line segment, which describe impedances and admittances for the entire length of the segment.  Additionally impedances can be computed by using length and associated per length impedances.
The BaseVoltage at the two ends of ACLineSegments in a Line shall have the same BaseVoltage.nominalVoltage. However, boundary lines may have slightly different BaseVoltage.nominalVoltages and variation is allowed. Larger voltage difference in general requires use of an equivalent branch.

*Inherits from: Conductor*

## Validations

### r

Positive sequence series resistance of the entire line section.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-452_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*

### x

Positive sequence series reactance of the entire line section.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-452_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*
