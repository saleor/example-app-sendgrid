# Troubleshooting

By following the troubleshooting guidelines outlined here, you'll be able to troubleshoot and resolve common email-related issues, ensuring that your emails reach the intended recipients' inboxes.

If you encounter a problem that is not covered here or need further assistance, we recommend reaching out to [the GitHub Issues](https://github.com/saleor/example-app-sendgrid/issues?q=sort%3Aupdated-desc+is%3Aissue+is%3Aopen) page.

## General

- Make sure the configuration is activated
    1. Go to configuration details
    2. In the `Status and name` section, `Active` should be checked
- Configuration is enabled for the channel
    1. Go to configuration details
    2. If channel assignment is overwritten, ensure the channel the event originated from is not excluded
- Ensure the sender details are filled in
    1. Go to configuration details
    2. Fill fields in the `Sender` section
- Event is activated
    1. Go to configuration details
    2. In the `Events` section, `Active` should be checked for events you are investigating

## Sendgrid

- Sandbox mode is not active
    1. Go to configuration details
    2. In the `API connection` section, sandbox mode should not be activated
- The API key is still active
- Sender is configured and available in the Sendgrid account
- Dynamic templates are configured and available
- Check [Email Activity Feed](https://docs.sendgrid.com/ui/analytics-and-reporting/email-activity-feed)
