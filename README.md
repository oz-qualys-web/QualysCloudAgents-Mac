# QualysCloudAgents-Mac
Binaries for Qualys Cloud Agents for Mac: 
Current versions
| Name                         | Version  | Description                          |
| ---------------------------- | -------- | ------------------------------------ |
| QualysCloudAgent.Silicon.pkg | 6.0.0.30 | For Silicon architecture (M# series) |
| QualysCloudAgent.x64.pkg     | 6.1.0.20 | For x64 architecture (Intel-based)   |

**Each binary must be renamed to** QualysCloudAgent.pkg **to run using installation commands.** Installation attempts on mismatched architecture _will fail_ using the wrong binary.

The installation steps can be found at:
https://docs.qualys.com/en/ca/install-guide/macos/installation/installation_steps.htm

However, the x's in:
- ActivationId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
- CustomerId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx

...must be replaced with the Activation Key and Customer ID from your Qualys subscription.

Additionally, the x's in: 
- ServerUri=https://qagpublic.xxx.apps.qualys.xxx/CloudAgent/

...must be replaced with the correct URL for your platform. The list of platform URLs can be found at: https://www.qualys.com/platform-identification/
