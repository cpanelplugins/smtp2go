# SMTP2GO cPanel/WHM Plugin

Our enterprise cPanel/WHM plugin is designed for hosting providers who manage many customer domains and email services.

The plugin is designed to complete the following tasks:

- Add a Verified Senders to your SMTP2GO app dashboard
- Update your DNS with the three required CNAME entries for Sender Domain verification
- Verify the DNS changes have been propagated
- Add an SMTP user and complex password to your SMTP2GO app dashboard
- Update the cPanel EXIM sending configuration files to allow email to send via SMTP2GO's infrastructure
- This app integration is currently in beta, and we welcome customers to test the plugin. Please contact the support team for more information.

---

# Installation

After the plug in has been installed, you will need to add your API key and set your options.

![plugin image](https://raw.githubusercontent.com/cpanelplugins/smtp2go/main/domain-list.jpg "Image Title")[H]

Checking the "Enable SMTP2GO" option will allow the plug in to update the cPanel configuration files so that the domain will automatically route emails via SMTP2GO. This is enabled by default.

You can generate an API key by logging in to your SMTP2GO dashboard, clicking "Settings > API Keys". 

 

Should you need the Settings option again, you can access it on the top right of the screen. Clicking "Go to app" will take you to your SMTP2GO account login page. "Refresh" will update the processing status of your domains.

settings-refresh.png

 

Your domains are displayed on the main screen and offer at-a-glace status information:

domain-list.jpg

 

You can use the "Filter" option to view any of the three statuses:

Enabled
Disabled
Processing
You can manually "Enable" or "Disable" any domain from being used by the plug in by clicking the drop down arrow at the right of the page.

A domain with the status "Processing" will usually be awaiting DNS verification.
