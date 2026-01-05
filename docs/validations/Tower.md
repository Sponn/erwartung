# Tower
cim:Tower

Tower asset. Dimensions of the Tower are specified in associated DimensionsInfo class.
When used for planning purposes, a transmission tower carrying two 3-phase circuits will have 2 instances of Connection, each of which will have 3 MountingPoint instances, one for each phase all with coordinates relative to a common origin on the tower. (It may also have a 3rd Connection with a single MountingPoint for the Neutral line).

*Inherits from: Structure*

## Validations

### height

Visible height of structure above ground level for overhead construction (e.g., Pole or Tower) or below ground level for an underground vault, manhole, etc. Refer to associated DimensionPropertiesInfo for other types of dimensions.

- **Maximum Value**: 200
