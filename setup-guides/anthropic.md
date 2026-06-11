# Anthropic API Setup Guide
*Last verified: June 2026*

The Anthropic Claude API powers AI document extraction in FinAdvisor.
It reads your pay stubs, bank statements, utility bills, and tax returns
automatically so you don't have to type everything manually.

## Before You Begin

API usage is billed to your Anthropic account. Review current pricing at
**anthropic.com/pricing** before proceeding. For a typical FinAdvisor
setup session, usage costs are minimal — we recommend setting a spending
limit in your Anthropic account before use.

## Setting a Spending Limit (Recommended)

1. Log into **console.anthropic.com**
2. Go to **Settings → Limits**
3. Set a monthly spending limit appropriate for your needs
4. This prevents any unexpected charges

## Getting Your API Key

1. Go to **console.anthropic.com** (create account if needed)
2. Click **API Keys** in the left sidebar
3. Click **Create Key**
4. Name it "FinAdvisor" so you know what it's for
5. Copy the key immediately — it only displays once
6. Paste it into FinAdvisor Settings → AI Document Reading

## Security

- Treat your API key like a password
- Do not screenshot it, email it, or share it
- If compromised, delete it at console.anthropic.com/settings/keys
  and create a new one — FinAdvisor will use the new key automatically

## Revoking Access

To stop FinAdvisor from using your Anthropic key:
1. Go to console.anthropic.com/settings/keys
2. Delete the "FinAdvisor" key
3. In FinAdvisor Settings, clear the Anthropic key field
4. Your FinAdvisor dashboard continues working — document upload
   will revert to manual entry mode
