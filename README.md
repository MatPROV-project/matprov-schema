# MatPROV Context

This repository provides the JSON-LD context schema for **MatPROV**, defining the vocabulary for material characteristics and synthesis parameters used in **PROV-DM–based provenance graphs**.

## Usage

To use the MatPROV context in a PROV-JSONLD document, include the following in the `@context` field:

```json
{
  "@context": [
    "https://MatPROV-project.github.io/matprov-schema/context.jsonld"
  ],
  "@graph": [ /* … */ ]
}
```

This ensures that synthesis procedure graphs are semantically annotated with MatPROV’s vocabulary.

## Versions

* Latest (v1.0): /context.jsonld
* v1.0: /releases/1.0/context.jsonld

Backward-incompatible updates will be published under releases/{version}/ and recorded in `versions.json`.

## License

This repository is licensed under [CC BY 4.0](LICENSE).
