# ![LOGO](logo.png) FabricAdminClient **flow**ground Connector

## Description

A generated **flow**ground connector for the FabricAdminClient API (version 2016-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-LogicalSubnet/2016-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:31+03:00

## API Description

Logical subnet operation endpoints and objects.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of all logical subnets.

*Tags:* `LogicalSubnets`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `logicalNetwork` - _required_ - Name of the logical network.
* `api-version` - _required_ - Client API Version.
* `$filter` - _optional_ - OData filter parameter.

### Returns the requested logical subnet.

*Tags:* `LogicalSubnets`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `logicalNetwork` - _required_ - Name of the logical network.
* `logicalSubnet` - _required_ - Name of the logical subnet.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-logical-subnet-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
