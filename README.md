# QualysCloudAgents-Mac
Binaries for Qualys Cloud Agents for Mac

The current binary is only for Macs running on Apple Silicon processors. Installation attempts on Intel-based processors will fail using this binary.

The installation steps can be found at:
https://docs.qualys.com/en/ca/install-guide/macos/installation/installation_steps.htm

However, the x's in:
- ActivationId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
- CustomerId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx

...must be replaced with the Activation Key and Customer ID from your Qualys subscription.

Additionally, the x's in: 
- ServerUri=https://qagpublic.xxx.apps.qualys.xxx/CloudAgent/
...must be replaced with the correct URL for your platform. The list of platform URLs can be found at: https://www.qualys.com/platform-identification/
