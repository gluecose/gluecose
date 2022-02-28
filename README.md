# Introduction
GLUECOSE provides an interoperability framework for various [CBOR Object Signing and Encryption](https://datatracker.ietf.org/doc/html/rfc8152) (COSE) libraries. Additionally, it provides a single place where developers can view the features of various COSE libraries, and thus select a library that is best suited for a project's specific needs.

# Motivation
The COSE signing envelope format, which is broadly applicable from small devices to large-scale server environments, attempts to keep the flavor of [Javascript Object Signing and Encryption](https://datatracker.ietf.org/wg/jose/documents/) (JOSE) specifications ([JWS](https://datatracker.ietf.org/doc/rfc7515/), [JWE](https://datatracker.ietf.org/doc/rfc7516/), [JWK](https://datatracker.ietf.org/doc/rfc7517/), [JWA](https://datatracker.ietf.org/doc/rfc7518/)) while providing additional features and flexibility. To meet requirements for device reach and flexibility, COSE has a very wide feature set and is quite complex. This makes it difficult for library implementors to test and verify their libraries. Also, many implementors choose to implement a subset of the full COSE specification. This makes it difficult for developers to know which COSE library to select given their project's needs.

# Vision
Have a clear view of tables that express the support of features by a certain COSE library, so that a user that needs to decide whether to use a certain crypto primitive for their software project can clearly identify the level of support for that feature in the open-source software ecosystem.

# Deliverables

1. A way to query feature support for a specific COSE implementation in an automated fashion.

2. Comprehensive set of COSE tests which can be used by developers in their projects.

3. Published results of the glucose tests against a specific COSE implementation.

4. Compatibility Matrix of COSE libraries in the ecosystem.

# Project Activites
gluecose is an emerging project. Activities are tracked via github issues and progress tracked via the project [board](https://github.com/orgs/gluecose/projects/1)
