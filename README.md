# ![LOGO](logo.png) ManagedServiceIdentityClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ManagedServiceIdentityClient API (version 2018-11-30).

Generated from: https://api.apis.guru/v2/specs/azure.com/msi-ManagedIdentity/2018-11-30/swagger.json<br/>
Generated at: 2019-05-07T17:38:29+03:00

## API Description

The Managed Service Identity Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists available operations for the Microsoft.ManagedIdentity provider

#### Input Parameters
* `api-version` - _required_ - Version of API to invoke.

### Lists all the userAssignedIdentities available under the specified subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The Id of the Subscription to which the identity belongs.
* `api-version` - _required_ - Version of API to invoke.

### Lists all the userAssignedIdentities available under the specified ResourceGroup.

#### Input Parameters
* `subscriptionId` - _required_ - The Id of the Subscription to which the identity belongs.
* `resourceGroupName` - _required_ - The name of the Resource Group to which the identity belongs.
* `api-version` - _required_ - Version of API to invoke.

### Deletes the identity.

#### Input Parameters
* `subscriptionId` - _required_ - The Id of the Subscription to which the identity belongs.
* `resourceGroupName` - _required_ - The name of the Resource Group to which the identity belongs.
* `resourceName` - _required_ - The name of the identity resource.
* `api-version` - _required_ - Version of API to invoke.

### Gets the identity.

#### Input Parameters
* `subscriptionId` - _required_ - The Id of the Subscription to which the identity belongs.
* `resourceGroupName` - _required_ - The name of the Resource Group to which the identity belongs.
* `resourceName` - _required_ - The name of the identity resource.
* `api-version` - _required_ - Version of API to invoke.

### Update an identity in the specified subscription and resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The Id of the Subscription to which the identity belongs.
* `resourceGroupName` - _required_ - The name of the Resource Group to which the identity belongs.
* `resourceName` - _required_ - The name of the identity resource.
* `api-version` - _required_ - Version of API to invoke.

### Create or update an identity in the specified subscription and resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The Id of the Subscription to which the identity belongs.
* `resourceGroupName` - _required_ - The name of the Resource Group to which the identity belongs.
* `resourceName` - _required_ - The name of the identity resource.
* `api-version` - _required_ - Version of API to invoke.

## License

**flow**ground :- Telekom iPaaS / azure-com-msi-managed-identity-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
