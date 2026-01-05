# Clamp
cim:Clamp

A Clamp is a galvanic connection at a line segment where other equipment is connected. A Clamp does not cut the line segment. 
A Clamp is ConductingEquipment and has one Terminal with an associated ConnectivityNode. Any other ConductingEquipment can be connected to the Clamp ConnectivityNode.

*Inherits from: ConductingEquipment*

## Validations

### lengthFromTerminal1

The length to the place where the clamp is located starting from side one of the line segment, i.e. the line segment terminal with sequence number equal to 1.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-301_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*
