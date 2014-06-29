# Identifiers for CBOR

This document specifies a tag for identifiers in Concise Binary Object Representation (CBOR) [1].

    Tag: 38
    Data item: multiple
    Semantics: Identifier
    Point of contact: Lucas Clemente <lucas@clemente.io>
    Description of semantics: https://github.com/lucas-clemente/cbor-specs/blob/master/id.md

## Semantics

Tag 38 can be applied to multiple types to indicate that the tagged object has identifier semantics.
For numeric identifiers (e.g. an integer as primary key in a database) this implies that they are not necessarily meant for arithmetic computations.

## Rationale

As an example, treating a 64bit unsigned integer as an arithmetic floating point type in JavaScript may lead to incorrect behavior.

## References

[1] C. Bormann, and P. Hoffman. "Concise Binary Object Representation (CBOR)". RFC 7049, October 2013.

## Author

Lucas Clemente <lucas@clemente.io>
