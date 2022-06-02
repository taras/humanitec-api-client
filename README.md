# Generating Clients

This project uses [Autorest to generate client libraries from OpenAPI](https://github.com/Azure/autorest/blob/main/docs/generate/readme.md) specifications. To run the generator, execute 

```
npx autorest README.md
```

```yaml
input-file: ./humanitec_openapi_spec.yaml
typescript: true
output-folder: .
namespace: humanitec
```
