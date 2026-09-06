# SHAR Production n8n Metadata Release Gate

An importable, credential-free n8n workflow that validates a declared
production metadata manifest before a release recommendation. It is published
by [SHAR Production](https://sharprod.com/), an AI-hybrid video production
studio.

The workflow uses only a Manual Trigger and an n8n Code node. It produces a
structured `releasable` result, blocks `rights_status: unknown`, and never
publishes media or claims that declared metadata proves legal clearance.

## Import

Import `production-metadata-release-gate.json` into n8n. Update the `manifest`
object in **Validate Production Metadata** with the declared metadata to review,
then run the workflow manually.

Code and documentation are MIT. The embedded example is synthetic and CC-BY-4.0.
