# Categories of data tests

## Number values - Upper and lower boundaries
For attributes with a range `decimal` or `integer`, upper and lower boundaries can be set using `maximum_value` and `minimum_value`:
```yaml
 Tower:
    description: "Tower asset. Dimensions of the Tower are specified in associated\
      \ DimensionsInfo class.\r\nWhen used for planning purposes, a transmission tower\
      \ carrying two 3-phase circuits will have 2 instances of Connection, each of\
      \ which will have 3 MountingPoint instances, one for each phase all with coordinates\
      \ relative to a common origin on the tower. (It may also have a 3rd Connection\
      \ with a single MountingPoint for the Neutral line).\r\n"
    from_schema: https://cim.ucaiug.io/ns#TC57CIM.IEC61968.InfIEC61968.InfAssets
    is_a: Structure
    slot_usage:
      height:
        maximum_value: 200
        minimum_value: 0
```
## String values - Regular Expressions
Regular expressions can be used to test string values. They are defined as `pattern`:
```yaml
 IdentifiedObject:
    class_uri: cim:IdentifiedObject
    tree_root: true
    from_schema: https://cim.ucaiug.io/ns#TC57CIM.IEC61970.Base.Core
    description: This is a root class to provide common identification for all classes
      needing identification and naming attributes.
    attributes:
      mRID:
        pattern: "^[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}$"
```