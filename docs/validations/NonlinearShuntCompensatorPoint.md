# NonlinearShuntCompensatorPoint
cim:NonlinearShuntCompensatorPoint

A non linear shunt compensator bank or section admittance value. The number of NonlinearShuntCompenstorPoint instances associated with a NonlinearShuntCompensator shall be equal to ShuntCompensator.maximumSections. ShuntCompensator.sections shall only be set to one of the NonlinearShuntCompenstorPoint.sectionNumber. There is no interpolation between NonlinearShuntCompenstorPoint-s.

## Validations

### g

Positive sequence shunt (charging) conductance per section.

- **Minimum Value**: 0.0
  - *Source: ENTSOE Application Profiles Library v1.1.0 (61970-452_Equipment-AP-Con-Complex-SHACL_v3-0-0.ttl)*
