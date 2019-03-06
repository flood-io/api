# Flood API OpenAPI Specification

## Generating Clients

### NodeJS (Fetch + TypeScript)

Ensure you have `openapi-generator` installed.

```bash
TS_POST_PROCESS_FILE="/usr/local/bin/prettier --write" \
openapi-generator generate \
    -i ./flood-api.v3.yml \
    -g typescript-fetch \
    -o ./flood-fetch-client
```

