To build locally run the following in the root directory
```
mvn clean package -pl modules/openapi-generator-cli
```

The jar will be in the `modules/openapi-generator-cli/target/openapi-generator-cli.jar`
Replace the openapi-generator-cli.jar file in the portal-server/sdk directory in the portal-server repo with the new one