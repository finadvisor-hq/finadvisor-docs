# Supported Bank Statement Formats

FinAdvisor can automatically detect and parse CSV exports from
the following banks. Download your statement as CSV from your
bank's website and upload it in the setup wizard.

## Fully Supported (Auto-detected)

| Bank | Export Format | Notes |
|------|--------------|-------|
| Regions Bank | CSV | Debit/Credit columns |
| Chase | CSV | Amount column (positive/negative) |
| Bank of America | CSV | Standard format |
| Wells Fargo | CSV | Standard format |
| Capital One | CSV | Standard format |
| Citibank | CSV | Standard format |
| US Bank | CSV | Standard format |
| PNC Bank | CSV | Standard format |
| Truist / SunTrust | CSV | Standard format |
| Ally Bank | CSV | Standard format |
| Navy Federal CU | CSV | Standard format |

## Unknown Banks

If your bank is not listed, select "Auto-detect" in the wizard.
FinAdvisor's AI will attempt to identify the format automatically.

If auto-detection fails, select "Other / Unknown" and the wizard
will prompt you to identify the column headers manually.

## Requesting Support for Your Bank

Contact support@finadvisor-hq.com with a sample CSV
(with personal data removed) and we will add support in the
next release.
