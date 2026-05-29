# Publishing Checklist

Use this checklist before creating or uploading a public GitHub repository.

## Content Review

- Confirm all files are documentation or synthetic sample outputs
- Confirm no private source code was copied
- Confirm no runtime output was copied
- Confirm the Email Agent is clearly the main business case study
- Confirm AI-MT4 is clearly marked as secondary
- Confirm no financial advice or profitability claim is made

## Secret Review

Search for:

- `password`
- `token`
- `secret`
- `credential`
- `api_key`
- `OAuth`
- `app password`
- `account`
- `smtp`
- `imap`
- Runtime signal filenames

Policy documents may mention these terms only as excluded content.

## Business Value Review

- README explains the business problem and solution quickly
- Email Agent is the main operational improvement case
- AI-MT4 remains a secondary risk-boundary case study
- Diagrams are easy to find
- Claims are accurate and not overstated
- Technical terms are explained in plain language

## GitHub Upload Review

- Initialize Git only inside this showcase folder
- Review every staged file before the first commit
- Confirm sample outputs are synthetic
- Confirm screenshots, if any, are manually redacted and synthetic
- Do not upload parent project folders

## Final No-Go Conditions

Do not publish if any file contains:

- Real credentials
- Real email content
- Real trading logs
- Runtime signal files
- Account data
- Live config
- Unreviewed screenshots
- Private customer or supplier names

