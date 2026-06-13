# Email on Acid

Email on Acid (now branded as Mailgun Inspect) is an email testing and pre-deployment quality assurance platform with a REST API for rendering email previews across 100+ email clients and devices, checking accessibility compliance (WCAG 2.2), validating HTML/CSS compatibility, running spam filter analysis, and automating pre-send email testing workflows.

## Links

- **Website:** https://www.emailonacid.com
- **API Documentation:** https://api.emailonacid.com/docs/latest
- **Pricing:** https://www.emailonacid.com/pricing/
- **Blog:** https://www.emailonacid.com/blog/
- **Status Page:** https://status.emailonacid.com/
- **GitHub:** https://github.com/emailonacid
- **LinkedIn:** https://www.linkedin.com/company/email-on-acid
- **X (Twitter):** https://twitter.com/EmailOnAcid

## APIs

### Email on Acid API v5

REST API for automating email testing. Base URL: `https://api.emailonacid.com/v5`

**Authentication:** HTTP Basic Authentication using `api_key:account_password` encoded in base-64. Sandbox mode available using `sandbox:sandbox` credentials.

**Key Endpoint Categories:**
- Email Testing — create, retrieve, manage, and delete email tests
- Email Client Lists — manage available and default email clients for testing
- Spam Testing — create spam tests, retrieve spam results, manage seed lists
- Test Searches — search and retrieve historical test results

**Data Retention:** Test results stored for 90 days after processing.

## Plans

| Plan | Monthly Price | Previews/Month | API Access |
|------|--------------|----------------|------------|
| Basic | $99 | 1,000 | Yes |
| Premium | $199 | 2,000 | Yes |
| Contract | Custom | Custom | Yes |

Overage rate: $0.15 per preview. Annual billing saves 15%.

## Maintainer

**Kin Lane** — kin@apievangelist.com
