# openapi-vio-types

Auto-generated TypeScript types from the [Vio.com Partners API OpenAPI schema](https://developers.vio.com/docs/Partners-API/openAPI-schema).

## Usage

Install as a git dependency:

```bash
npm install github:bailinca/openapi-vio-types
```

Import in your code:

```typescript
import type { components, operations, paths } from "openapi-vio-types";

type VioSchemas = components["schemas"];
type VioOffer = VioSchemas["Offer"];
```

## Updating the schema

1. Go to https://developers.vio.com/docs/Partners-API/openAPI-schema
2. Copy the contents to `vio-api.yaml`
3. Run `npm run generate`
4. Commit and push
5. In consumer repos, run `npm update openapi-vio-types`
