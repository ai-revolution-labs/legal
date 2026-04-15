# AIRL Vault Invoicer — Privacy Policy

**Last updated:** 2026-04-15

AIRL Vault Invoicer ("the App") is a private, internal application operated by AI Revolution Labs. This policy describes how the App handles data.

## Who uses the App

Only authorized personnel of AI Revolution Labs. No external end users are supported.

## What data the App accesses

The App connects to the operator's own QuickBooks Online company via OAuth 2.0 with the `com.intuit.quickbooks.accounting` scope. It reads and writes:
- Customer records (create/lookup by name)
- Service items (lookup)
- Invoices (create, read)

## What data the App stores

The App stores the following locally on the operator's machine, outside any cloud service:
- OAuth refresh token and realm ID (in a permission-restricted local file)
- QuickBooks customer IDs and invoice IDs (in a local git-tracked vault)

No QuickBooks data is transmitted to any third party.

## Data retention

Data is retained as long as the operator maintains the local vault. There is no external data retention.

## Data sharing

No data is shared with third parties. The App makes API calls only to Intuit's QuickBooks Online API.

## Contact

For questions: michael@airevolutionlabs.com
