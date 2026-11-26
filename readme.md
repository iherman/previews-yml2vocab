# Previewing PR-s

This is a setup for the VC, DID, and PM Working Groups. Those WGs use the [yml2vocab](https://github.com/w3c/yml2vocab/) script to generate vocabularies. However, the effective generation of these vocabularies is often done via GitHub actions, which makes it difficult to preview the results when a Pull Request is created with changes in the vocabularies. Instead of requiring the reviewer to generate the vocabulary files locally, this directory is used to store specific PR previews temporarily.

-   [Verifiable Credentials v2.1, branch: `main`](./vcdm/)
-   [Data Integrity 1.1, branch: `vocabulary-with-mermaid`](./di/)
-   [Recognizable Entities v1.0 branch: `vocabulary-mermaid-diagram-generated`](./re/)
-   [Security Vocabulary v2.0 branch: `main`](./di/)
-   [Bitstring Status List v1.0, branch: `add-TBSLE-to-vocabulary`](./sl/)
-   [Forgery Defense v1.0, branch: `set-up-a-vocabulary`](./fd/)
-   [DID 1.0 v1.0, branch: `main`](./did/)

---

[@iherman](https://github.com/iherman). Comments can also be sent to ivan@w3.org.
