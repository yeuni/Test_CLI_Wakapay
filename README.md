# Test CLI Wakapay

This repository is used for testing GitHub webhooks, CI/CD pipelines, and Supabase Edge Functions.

## Purpose

- Test webhook triggers from GitHub to external services
- Validate CI/CD pipeline functionality  
- Test Supabase Edge Function integrations
- Monitor webhook delivery and processing

## Testing

This repository is designed to be used with the [GitHub Webhook Testing Suite](../github-webhook-tester/) which provides comprehensive testing tools for:

- Git-based webhook triggers
- Direct API testing with curl
- Webhook payload simulation
- Real-time health monitoring
- Stress testing capabilities

## Usage

Each commit to this repository will trigger configured webhooks and CI/CD processes. This allows for testing the complete flow from code changes to downstream integrations.

## Webhook Events

This repository is configured to send webhook events for:
- Push events
- Pull requests
- Issues
- Releases
- Other GitHub events as configured

---

*This is a test repository for webhook and CI/CD testing purposes.*