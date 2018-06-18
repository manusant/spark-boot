# spark-boot
Spark boot makes it easy to create stand-alone, production-grade Spark applications with features like Beans Validation, endpoints via annotations, marshal/unmarshal of requests and responses, code generation, doc generation, etc, using Spark framework as engine.

This new idea consists in create an abstraction layer over Spark in order to be able to support features and extensions with ease.
The **core** idia will be based in the following diagram:
<img src="concept-diagram.jpg" width="100%">

## Planned Features:
- **JSR-330**: Dependency Injection (Guice or Dagger 2)
- Annotation based endpoint mapping
- **JSR-380**: Beans Validation 2.0
- Marshalling and Unmarshalling of requests/responses
- Swagger doc
- Swagger code generator
- ect
