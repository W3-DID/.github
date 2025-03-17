## W3C DiD implementation
### Abstract
Decentralized identifiers (DIDs) represent a form of identifier designed to support verifiable
and self-sovereign digital identity. 

Unlike traditional federated identifiers (such as state passport), DIDs operate independently of centralized registries,
third-party identity providers, or certificate authorities. These identifiers can represent any entity—such as individuals, 
organizations, devices, or abstract concepts—as defined by the DID controller. 

A core feature of DIDs is that their controllers can authenticate ownership without relying on external authorization,
even if third parties assist in discovering related information.

Structured as URIs, DIDs link a subject (e.g., a person or object) to a corresponding DID document. This document serves 
as a foundation for secure, trustable interactions by detailing cryptographic keys, verification protocols, and service 
endpoints. These components empower controllers to demonstrate control over the identifier. Additionally, services 
specified in the document facilitate trusted engagements with the DID subject. In cases where the subject is an 
information resource (like a dataset), the DID may directly reference the resource itself.

### Content

1) Introduction
   1) [DID example](../fragments/example)
   2) [Architecture overview](../fragments/architecture.md)

