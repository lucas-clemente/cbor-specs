# Identifiers for CBOR

This document specifies a tag for identifiers in Concise Binary Object Representation (CBOR) [1].

    Tag: 38
    Data item: multiple
    Semantics: Identifier
    Point of contact: Lucas Clemente <lucas@clemente.io>
    Description of semantics: https://github.com/lucas-clemente/cbor-specs/blob/master/id.md

## Semantics

Tag 38 can be applied to multiple types to indicate that the following object has identifier semantics.

## Rationale

Applications might want to treat identifiers different from normal datatype semantics (e.g. not treat a 64bit ID as an arithmetic type on 32bit platforms such as JavaScript).

## References

[1] C. Bormann, and P. Hoffman. "Concise Binary Object Representation (CBOR)". RFC 7049, October 2013.

## Author

Lucas Clemente <lucas@clemente.io>
