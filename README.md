Schematron-Schema-Constraints
=============================

UK Location Schematron Schema Constraints

The Schematron schema was based on GEMINI2.1, and requires no change for GEMINI 2.2. It is designed to validate metadata instances encoded according to the UKLP encoding guidance to support validation of discovery metadata used for INSPIRE in the UK and harvested through to [data.gov.uk](http://data.gov.uk).

Validating a UK Location metadata record is a three stage process. First, a candidate metadata set must be validated against the ISO 19139 schemas. If the metadata set proves to be schema valid, it can then be validated against the ISO 19139 Table A.1 Constraints Schematron schema. The Schematron schema relies on hardcoded XPath statements which will only work effectively on a schema valid XML set. Finally, if the XML is still valid it can be validated against the GEMINI2 Profile Schematron schema.

For more information, see the UK GEMINI Encoding Guidance and Schematron technical guidance [data.gov.uk/library/uk-gemini-schematron-schema-technical-guidance](http://data.gov.uk/library/uk-gemini-schematron-schema-technical-guidance)
