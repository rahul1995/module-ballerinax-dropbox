_Author_:  @rahul1995 \
_Created_: 2024/10/25 \
_Updated_: 2024/10/25 \
_Edition_: Swan Lake

# Sanitation for OpenAPI specification

This document records the sanitation done on top of the official OpenAPI specification from Dropbox. 
The OpenAPI specification is obtained from https://www.postman.com/dropbox-api/dropbox-s-public-workspace/collection/q1zdtug/dropbox-api-reference.
These changes are done in order to improve the overall usability, and as workarounds for some known language limitations.

[//]: # (TODO: Add sanitation details)
1. Add content-type and schema to each empty content
2. 
3. 

## OpenAPI cli command

The following command was used to generate the Ballerina client from the OpenAPI specification. The command should be executed from the repository root directory.

```bash
bal openapi -i docs/spec/openapi.yaml --mode client -o ballerina
```
Note: The license year is hardcoded to 2024, change if necessary.
