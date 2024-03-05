# {Application} Deployment Configuration

This repo contains the copilot configuration for {Application}.

## Setup

Speak to SRE if you need AWS account access. This is required to manually interact with the infrastructure managed by this repository.

## Domains and TLS certificates

SRE manages domains and certificates. Speak to SRE if you need to stand up a new environment, and they will provision the ACM certs and domains for you. The `#dbt-platform-migrations-{application}` or `#sre-requests` Slack channels are the best way to get in touch with us.

## Further reading

- [Platform Documentation](https://platform.readme.trade.gov.uk/overview/)
- [Migration Documentation](https://platform.readme.trade.gov.uk/migrations/migration-progress/{Application}/)
- [{Application} Architecture](https://readme.trade.gov.uk/docs/services/{Application}.html)
- {Application} Codebases:
  - [{Application}](https://github.com/uktrade/{application})
  - [{Application}](https://github.com/uktrade/{application-subapplication})
