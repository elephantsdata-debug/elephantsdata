# ElephantsData

**Email and cloud data migration software for supported mail, files, photos, and archive workloads.**

[Website](https://elephantsdata.com) | [Start a migration](https://elephantsdata.com/email-migration-tool) | [Supported migrations](https://elephantsdata.com/supported-migrations) | [Migration guides](https://elephantsdata.com/migration-guides)

ElephantsData provides encrypted source-to-destination migration pipelines that help organizations move data between supported cloud platforms. The guided workflow covers connection setup, resource mapping, preflight validation, migration execution, checkpoints, retries, and reporting.

## Migration capabilities

- Large mailbox and email-data migrations
- Supported primary and archive mailbox content
- Email routes involving Google Workspace, Microsoft 365, Zoho Mail, Rediffmail, and supported IMAP services
- Google Drive, OneDrive, and Google Photos workloads on supported routes
- Source and destination authentication
- User and resource mapping
- Pre-migration validation
- Checkpoints and retry handling for long-running migrations
- Progress visibility and migration reports

Capabilities vary by source, destination, account type, provider API, and selected workload. Review the [supported migration routes](https://elephantsdata.com/supported-migrations) before starting a production migration.

## How it works

1. Sign in to ElephantsData.
2. Connect an authorized source and destination.
3. Select and map users or resources.
4. Run the available preflight checks.
5. Start with a small test migration.
6. Monitor progress and review the migration report.

ElephantsData is designed to transfer data efficiently through its encrypted migration pipeline. Actual throughput depends on provider throttling, API limits, permissions, network conditions, item count, file size, and source/destination availability. We do not promise a fixed transfer rate.

## Start safely

- Begin with test accounts and non-critical sample data.
- Confirm that the required source, destination, and workload are supported.
- Verify permissions and destination capacity before migration.
- Review results before scheduling a larger production migration.
- Never publish credentials, access tokens, tenant data, or customer information in a GitHub issue.

## Feedback

This repository is the public product-information and feedback space for ElephantsData. Use [GitHub Issues](https://github.com/elephantsdata-debug/elephantsdata/issues) to report documentation problems, request features, or share reproducible product feedback.

For account-specific or sensitive matters, use the support/contact option on the [ElephantsData website](https://elephantsdata.com).

## Security

Do not report suspected vulnerabilities in a public issue. Follow the private reporting instructions in [SECURITY.md](SECURITY.md).

## Repository scope

This is a public product-information repository. It is not presented as the complete ElephantsData application source code, and the absence of source code here does not mean the platform is open source.

## Affiliation

This repository is maintained by the ElephantsData team. Product descriptions should be treated as first-party information and verified against the current website and supported-routes documentation.
