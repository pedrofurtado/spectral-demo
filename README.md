# spectral-demo

Spectral OpenAPI yaml linter demo. Just for fun.

```bash
docker container run --rm -it -w /app -v $(pwd):/app node:16 /bin/bash
npm install
npx spectral lint myapispec.yaml --ruleset my-spectral-rulesets.yaml
```
