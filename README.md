## Overview: 
This Extension Resets the Developer Portal to Default Contoso Version removing all the Pages, Layouts, Contents from the Developer Portal Permanently.
**It cannot be restored back to previous version once implemented.**

## Pre-requisites: 
1.	An Active Service Principle with access to Azure API Management Services. 

## Configure the task:
Add the task to the Build / Release pipeline. 
Select the + Add tasks -> Marketplace -> **Reset Developer Portal for API Management Services**
Add the details as per the table below.

## Extension Overview:
This extension will remove all the Content of the Developer Portal and reset it back to default template.

## Task Usage:

### v1.0
| Options                           |	Description                                             |
|-----------------------------------|-----------------------------------------------------------|
| Azure Service Connection          | Should have Access to both the APIMs                      |
| APIM Subscription ID              | Subscription ID for API Management Services               |
| APIM Resource Group               | Resource Group Name for API Management Services           |
| APIM Service Name	                | Service Name for Source API Management Services           |


### v2.0
| Options                           |	Description                                             |
|-----------------------------------|-----------------------------------------------------------|
| Azure Service Connection          | Should have Access to both the APIMs                      |
| APIM Service Name	                | Service Name for Source API Management Services           |

## Notes:
API Management Services can be of Internal, External or None Virtual Network type.
Once Reset it cannot be reverted back to previous version.

## Highlighted feature:
1.	Easy to set up.
2.  One Click Release
3.  Only Solution to Reset Developer Portal.

## Releases:
| Release Version           | Updates                                                                                                    |
|---------------------------|------------------------------------------------------------------------------------------------------------|
| v2.0.0 (September 2023)   | Updated to Support Dropdowns from Textfields in v2.0. Now supports all Agents and Self-Hosted Agents       | 
| v1.0.0 (March 2023)       | Reset the Azure APIM Developer Portal to Default Template.                                                 |
