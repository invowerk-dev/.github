**German e-invoice checker: ZUGFeRD/Factur-X PDFs incl. PDF/A, XRechnung via the KoSIT validator, Peppol BIS. Free web tool, API, MCP.**

invowerk checks e-invoices: ZUGFeRD 2.5.2 and Factur-X 1.09.2 PDFs, XRechnung 3.0.2 (UBL and CII) and Peppol BIS Billing 3.0.21. XRechnung goes through the KoSIT validator. PDFs are also checked for PDF/A and against their embedded invoice data. Common rule messages come with cause and fix in German. Each check returns a report with the file's SHA-256, time, rule sets and result. The Prüfstand test files and their expected results are public. Invoices are processed in memory, not stored. Free web tool; REST API and MCP server with 500 free credits per month.

## Repositories

- [invowerk](https://github.com/invowerk-dev/invowerk): start here, for the MCP server, the Claude Code plugin and the API.
- [invowerk-integrations](https://github.com/invowerk-dev/invowerk-integrations): n8n, Zapier, Make, Workato, Dify, SDKs and templates.
- [invowerk-action](https://github.com/invowerk-dev/invowerk-action): use invowerk in GitHub Actions.

## Links

- **Website:** https://invowerk.dev/go/github
- **API docs:** https://api.invowerk.dev/docs
- **Pricing:** https://invowerk.dev/pricing
- **Support:** https://invowerk.dev/support
