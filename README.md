# it4it

[![Consumed by frictionless-architect](https://img.shields.io/badge/consumed%20by-frictionless--architect-blue)](https://github.com/wolffy-au/frictionless-architect)

IT4IT 3.0 value-stream reference model, vendored as plain YAML
(`elements.yaml` / `relationships.yaml`) in the schema authoring convention
used by `frictionless-architect` — see that repo's
`architecture/model/README.md` for the schema and ADR-0029 for why this
lives in its own repo instead of inline in a consumer's model files.

Every element/relationship `id:` carries the `it4it-` prefix so it stays
unique when merged into a consuming project's own identifier pass.

This is not an official Open Group artifact; it is a hand-authored
transcription of the IT4IT 3.0 reference model's value-stream skeleton for
use in ArchiMate-based architecture modelling.
