---
title: Bicep - Complete
---

The `complete` starter module is currently the only option available for Bicep.

The following table describes the inputs required for the `complete` starter module.

| Input | Placeholder | Description |
| - | -- | --- |
| `Prefix` | `landing-zone` | This is the defaut prefix for names of resources and management groups. |
| `Environment` | `live` | The environment name for the landing zone. This can be any lower case string. (e.g. `live` or `canary`)  |
| `networkType` | `hubNetworking` | The type of network configuration to deploy. Currently only `hubNetworking`, `hubNetworkingMultiRegion`, `vwanConnectivity,` `vwanConnectivityMultiRegion` or `none` are supported. |
| `SecurityContact` | `<email-address>` | The email address of the security contact for the landing zone. |

Example input files can be found here:

- [inputs-azure-devops-bicep-complete.yaml][example_powershell_inputs_azure_devops_bicep_complete]
- [inputs-github-bicep-complete.yaml][example_powershell_inputs_github_bicep_complete]
- [inputs-local-bicep-complete.yaml][example_powershell_inputs_local_bicep_complete]

 [//]: # (************************)
 [//]: # (INSERT LINK LABELS BELOW)
 [//]: # (************************)

[example_powershell_inputs_azure_devops_bicep_complete]: https://raw.githubusercontent.com/Azure/ALZ-Bicep/refs/heads/main/accelerator/examples/bootstrap/inputs-azure-devop.yaml "Example - PowerShell Inputs - Azure DevOps - Bicep - Complete"
[example_powershell_inputs_github_bicep_complete]:  https://raw.githubusercontent.com/Azure/ALZ-Bicep/refs/heads/main/accelerator/examples/bootstrap/inputs-github.yaml "Example - PowerShell Inputs - GitHub - Bicep - Complete"
[example_powershell_inputs_local_bicep_complete]:  https://github.com/Azure/ALZ-Bicep/blob/main/accelerator/examples/bootstrap/inputs-local.yaml "Example - PowerShell Inputs - Local - Bicep - Complete"
