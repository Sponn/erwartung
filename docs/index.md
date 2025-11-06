# erwartung - what you expect from your energy system data
`erwartung` (pronounced *ɛɐ̯ˈvartʊŋ*, German: expectation) is a collection of data unit tests for the energy domain. It includes software to export these data unit tests to different formats, ready to be used in your data hub.

Electricity Grid Operators maintain a large amount of data that describes their built assets, such as power lines, transformer stations, or electricity consumers and producers. Especially with the concept of a “Digital Twin” of the grid, the amount of data has been rapidly increasing in recent years. To ensure high data quality, extensive testing is required. Examples include:

* data types need to be correct,
* numerical values need to be within reasonable boundaries (minimum and maximum values),
* strings need to conform to regular‑expression patterns,
* quantities of the same assets need to be in reasonable ratios,
* coordinates need to match addresses,
* and many more.
