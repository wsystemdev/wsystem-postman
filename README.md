# W System API: Postman collection

Postman collection and environment for the [W System API](https://wsystem.dev): EU VAT (VIES) and EORI validation, company-register lookup, sanctions screening, KYB, and EU e-invoicing (EN 16931 / XRechnung validation, UBL creation, Peppol routing).

## Use it

1. In Postman: **Import** → **Link** and paste
   `https://raw.githubusercontent.com/wsystemdev/wsystem-postman/main/wsystem.postman_collection.json`
2. Optionally import `wsystem.postman_environment.json`.
3. Send a request. Without a key you get 20 free calls/day per IP.
   For more, get a free key (500 units/month, email only, no card) at <https://api.wsystem.dev/account/free-key?ref=postman-github> and put it in the `apiKey` variable (sent as `X-API-Key`).

Good first requests: **VAT → Validate one EU VAT number**, **E-invoice → "Can I e-invoice this company?"**, **E-invoice → Validate an EU e-invoice**.

Also available: [OpenAPI spec](https://api.wsystem.dev/openapi.json) · [JS/TS SDK (`npm i wsystem`)](https://www.npmjs.com/package/wsystem) · [Docs](https://wsystem.dev/docs) · [Pricing](https://wsystem.dev/pricing)

The collection is generated from the OpenAPI spec (`openapi2postmanv2`, tag folders, example values).

## License

MIT
