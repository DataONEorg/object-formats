---
name: Proposed Format
about: Submit a new format for inclusion in the format list
title: ''
labels: proposed format
assignees: ''

---

# Format Metadata

*Provide the standard metadata for the proposed format, ensuring that the id and name are unique and appropriate to the version of the format being proposed.*

- formatId: 
- formatName:
- formatType: 
- mediaType:
- extension:

Example (delete before submitting):

- formatId: `application/x-hdf5` 
- formatName: `Hierarchical Data Format version 5 (HDF5)`
- formatType: `DATA`
- mediaType : `application/x-hdf5`
- extension: `h5`

# Format description

*Describe why a new format is needed, including items such as where the format type has been encountered, what software produces it, and what software can read it.*

# Specification / Namespace documentation

*Provide the location(s) of the documentation of the format specification or the namespace for the format or vocabulary.*

# Checklist

- [ ] The format is not a duplicate of another in the list under a different name or identifier
- [ ] Format Identifier is unique
- [ ] Format identifier is the commonly-used identifier for the namespace, or the best URI for the namespace, or the best Media type
- [ ] Format identifier is same as the MIME media type if the mime type is specific to *only* this format (e.g., `image/png` is specific to one format, whereas `text/xml` is not specific to one format)
- [ ] Format Name is recognizable and sensible
- [ ] Format includes version info where applicable in formatName and formatId
- [ ] formatType is the correct type from the values: `DATA`, `METADATA`, or `RESOURCE`
- [ ] MediaType is the most specific MIME media type that applies to the format

# Considerations

*Describe or list any considerations that might impact the use of the format, or related issues that we should consider.*

