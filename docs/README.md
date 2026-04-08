<!--- Hugo front matter used to generate the website version of this page:
cascade:
  body_class: otel-docs-spec
  github_repo: &repo https://github.com/open-telemetry/semantic-conventions
  github_subdir: docs
  path_base_for_github_subdir: tmp/semconv/docs/
  github_project_repo: *repo
redirects:
  - { from: 'attributes-registry/*', to: 'registry/attributes/:splat' }
cSpell:ignore: semconv CICD
linkTitle: Semantic conventions
--->

# Semantic Conventions

This repository defines semantic conventions built on the [OpenTelemetry Semantic Conventions](https://opentelemetry.io/docs/specs/semconv/) model and toolchain.

Semantic Conventions are defined for the following areas:

* **[GenAI](gen-ai/README.md)**: Generative AI semantic conventions (spans, metrics, events).
* [Example](example/): Example semantic conventions demonstrating the toolchain.

Also see:

* **[General](general/README.md)**: General Semantic Conventions (attributes, traces, metrics, logs, events).
* [How to write semantic conventions](how-to-write-conventions/README.md)
* [Extension Guide](gen-ai/EXTENSION-GUIDE.md): How to add or extend semantic conventions in this project.
