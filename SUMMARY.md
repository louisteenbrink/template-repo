# Table of contents

* [Welcome](README.md)

## Getting Started

* [Quickstart](getting-started/quickstart.md)
* [Publish your docs](getting-started/publish-your-docs.md)

## Basics

* [Editor](basics/editor.md)
* [Markdown](basics/markdown.md)
* [Images & media](basics/images-and-media.md)
* [Interactive blocks](basics/interactive-blocks.md)
* [OpenAPI](basics/openapi.md)
* [Integrations](basics/integrations.md)

***

* ```yaml
  type: builtin:openapi
  props:
    models: true
  dependencies:
    spec:
      ref:
        kind: openapi
        spec: louis-petstore-api
  ```
