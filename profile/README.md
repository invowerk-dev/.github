**German e-invoices: create ZUGFeRD PDFs and XRechnung, check ZUGFeRD/Factur-X, XRechnung (KoSIT) and Peppol BIS. Free tool, API, MCP.**

invowerk creates and checks e-invoices. In the browser it creates ZUGFeRD PDFs and XRechnung from a form and checks each file before download. It checks ZUGFeRD 2.5.2 and Factur-X 1.09.2 PDFs, XRechnung 3.0.2 (UBL and CII) and Peppol BIS Billing 3.0.21. XRechnung goes through the KoSIT validator; PDFs are also checked for PDF/A. Each check returns a report with the file's SHA-256, rule sets and result. Invoices are processed in memory, not stored. Free web tool; REST API and MCP server with 500 free credits a month.

## Repositories

- [invowerk](https://github.com/invowerk-dev/invowerk): start here, for the MCP server, the Claude Code plugin and the API.
- [invowerk-integrations](https://github.com/invowerk-dev/invowerk-integrations): n8n, Zapier, Make, Dify, SDKs and templates.
- [invowerk-action](https://github.com/invowerk-dev/invowerk-action): use invowerk in GitHub Actions.

## Links

- **Website:** https://invowerk.dev/go/github
- **API docs:** https://api.invowerk.dev/docs
- **Pricing:** https://invowerk.dev/pricing
- **Support:** https://invowerk.dev/support
