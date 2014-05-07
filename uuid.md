# UUIDs for CBOR

This document specifies a tag for UUIDs in Concise Binary Object Representation (CBOR) [1].

    Tag: 31
    Data item: byte string
    Semantics: Binary UUID (RFC 4122 section 4.1.2)
    Point of contact: Lucas Clemente <lucas@clemente.io>
    Description of semantics: https://github.com/lucas-clemente/cbor-specs/blob/master/uuid.md

# Semantics

Tag 31 can be applied to a byte string (major type 2) to indicate that the byte string is a binary UUID as specified by section 4.1.2. of RFC 4122 [2].

# References

[1] C. Bormann, and P. Hoffman. "Concise Binary Object Representation (CBOR)". RFC 7049, October 2013.

[2] P. Leach, M. Mealling, and R. Salz. "A Universally Unique IDentifier (UUID) URN Namespace". RFC 4122, July 2005.

# Author

Lucas Clemente <lucas@clemente.io>
