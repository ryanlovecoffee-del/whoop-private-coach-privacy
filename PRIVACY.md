# WHOOP Private Health Coach Privacy Policy

**Effective date:** September 3, 2026  
**Operator:** Ryan Zheng

This notice describes **WHOOP Private Health Coach**, an independently operated, private ChatGPT GPT for personal wellness and fitness insights. It is not an official WHOOP product and does not provide medical diagnosis or treatment.

## Data and purpose

With the user's authorization through WHOOP OAuth, the GPT can read the WHOOP data needed to answer the user's requests:

- recovery metrics;
- physiological cycles and day strain;
- sleep records;
- workout records;
- basic WHOOP profile information; and
- body measurements.

The permissions shown on WHOOP's authorization screen determine the access actually granted. The integration requests read-only access and does not request permission to modify WHOOP records.

The data is used only to summarize the user's records and provide recovery, sleep, strain, workout, and training insights.

## Processing and storage

This direct WHOOP-to-ChatGPT configuration does not use a separate integration server or a separate health-data database operated by Ryan Zheng. WHOOP supplies the data requested by the user to ChatGPT/OpenAI, which processes it under the user's ChatGPT account settings and applicable terms.

OAuth credentials and tokens are handled by the authentication systems. Passwords, Client Secrets, access tokens, refresh tokens, and health records should never be posted in this repository or in public support requests.

If the user authorizes offline access, ChatGPT may use refresh tokens to maintain the connection until the authorization expires or is revoked.

## Sharing and retention

The operator does not sell WHOOP data or intentionally share it outside the direct WHOOP and ChatGPT/OpenAI integration. Information included in ChatGPT conversations may remain in the user's ChatGPT history according to the user's settings and OpenAI's applicable retention rules.

## User choices

The user may disconnect the GPT integration or revoke its WHOOP authorization to stop future reads. Revocation does not automatically erase information already included in ChatGPT conversations. The user can manage or delete those conversations through ChatGPT.

## Contact and changes

Questions about this privacy notice may be submitted through this repository's [GitHub Issues](https://github.com/ryanlovecoffee-del/whoop-private-coach-privacy/issues). Do not include health data, passwords, Client Secrets, access tokens, refresh tokens, or other sensitive information in a public issue.

This notice may be updated if the integration changes. The effective date above will be revised when material changes are made.
