# object-formats

The DataONE Object Formats controlled vocabulary is a simple vocabulary listing 
key metadata for file and object formats used within the DataONE network (https://dataone.org).
The goal of the list is to provide a unique identifier for each file format. The formatId
is typically more specific than an associated Media Type, but sometimes they can be the same.
For example, the `formatId` for PNG images is `image/png` and matches the media type `image/png`
because the media type is specific to one file format. In contrast, the `formatId` for WaterML is
`http://www.loc.gov/METS/`, which is more specific than the Media type which is `text/xml` and which
is shared across many formats in the XML family.

## Related work

There have been many format vocabularies created (and many abandoned), including UDFR, GDFR, ProNom, and others.
The DataONE vocabulary is simpler, more highly structured, and maintained by the repositories that use it.

## Contributing

We welcome the addition of new formats as needed for object types within DataONE and related repositories.
To propose a new format identifier:

- Create an issue describing the proposed identifier using the new format template
- Discuss the format with the community
- Create a Pull Request that creates the format in the XML dialect used in the formats file
