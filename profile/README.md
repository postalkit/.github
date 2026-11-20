# PostalKit

**Mexican postal codes, as one API.** Every código postal, every colonia, all 32 estados, from the official SEPOMEX catalog, kept current.

**Códigos postales de México en una API.** Cada código postal, cada colonia y los 32 estados, con datos oficiales de SEPOMEX siempre al día.

```bash
curl https://api.postalkit.mx/v1/postal-codes/06600 \
  -H "Authorization: Bearer $POSTALKIT_KEY"
```

- Website: [postalkit.mx](https://postalkit.mx/) · [English](https://postalkit.mx/en)
- API reference: [postalkit.mx/docs](https://postalkit.mx/docs) · [OpenAPI spec](https://postalkit.mx/docs.openapi)
- Free tier: 100 requests/month, [get a key](https://postalkit.mx/register)

## Open source

| Repo | |
| --- | --- |
| [postalkit-php](https://github.com/postalkit/postalkit-php) | PHP and Laravel client (`composer require postalkit/postalkit-php`) |
| [postalkit-mcp](https://github.com/postalkit/postalkit-mcp) | MCP server for Claude, Cursor and other AI assistants (`npx -y postalkit-mcp`) |
