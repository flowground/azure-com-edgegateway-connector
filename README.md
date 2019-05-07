# ![LOGO](logo.png) DataBoxEdgeManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DataBoxEdgeManagementClient API (version 2019-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/edgegateway/2019-03-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:07+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List all the supported operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version.

### Gets all the data box edge/gateway devices in a subscription.

*Tags:* `Devices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `api-version` - _required_ - The API version.
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the resource or Specify $skipToken=<token> to populate the next page in the list.

### Gets all the data box edge/gateway devices in a resource group.

*Tags:* `Devices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the resource or Specify $skipToken=<token> to populate the next page in the list.

### Deletes the data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the properties of the data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Modifies a Data Box Edge/Gateway resource.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates or updates a Data Box Edge/Gateway resource.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets all the alerts for a data box edge/gateway device.

*Tags:* `Alerts`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets an alert by name.

*Tags:* `Alerts`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The alert name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets all the bandwidth schedules for a data box edge/gateway device.

*Tags:* `BandwidthSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes the specified bandwidth schedule.

*Tags:* `BandwidthSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The bandwidth schedule name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the properties of the specified bandwidth schedule.

*Tags:* `BandwidthSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The bandwidth schedule name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates or updates a bandwidth schedule.

*Tags:* `BandwidthSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The bandwidth schedule name which needs to be added/updated.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Downloads the updates on a data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets additional information for the specified data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Installs the updates on the data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the details of a specified job on a data box edge/gateway device.

*Tags:* `Jobs`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The job name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the network settings of the specified data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the details of a specified job on a data box edge/gateway device.

*Tags:* `OperationsStatus`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The job name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Lists all the orders related to a data box edge/gateway device.

*Tags:* `Orders`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes the order related to the device.

*Tags:* `Orders`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets a specific order by name.

*Tags:* `Orders`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates or updates an order.

*Tags:* `Orders`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Lists all the roles configured in a data box edge/gateway device.

*Tags:* `Roles`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes the role on the data box edge device.

*Tags:* `Roles`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The role name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets a specific role by name.

*Tags:* `Roles`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The role name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Create or update a role.

*Tags:* `Roles`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The role name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Scans for updates on a data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Updates the security settings on a data box edge/gateway device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Lists all the shares in a data box edge/gateway device.

*Tags:* `Shares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes the share on the data box edge/gateway device.

*Tags:* `Shares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The share name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets a share by name.

*Tags:* `Shares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The share name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates a new share or updates an existing share on the device.

*Tags:* `Shares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The share name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Refreshes the share metadata with the data from the cloud.

*Tags:* `Shares`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The share name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets all the storage account credentials in a data box edge/gateway device.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes the storage account credential.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The storage account credential name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the properties of the specified storage account credential.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The storage account credential name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates or updates the storage account credential.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The storage account credential name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Lists all the triggers configured in the device.

*Tags:* `Triggers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.
* `$expand` - _optional_ - Specify $filter='CustomContextTag eq <tag>' to filter on custom context tag property

### Deletes the trigger on the gateway device.

*Tags:* `Triggers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The trigger name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Get a specific trigger by name.

*Tags:* `Triggers`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The trigger name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates or updates a trigger.

*Tags:* `Triggers`

#### Input Parameters
* `deviceName` - _required_ - Creates or updates a trigger
* `name` - _required_ - The trigger name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets information about the availability of updates based on the last scan of the device. It also gets information about any ongoing download or install jobs on the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Uploads registration certificate for the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets all the users registered on a data box edge/gateway device.

*Tags:* `Users`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Deletes the user on a databox edge/gateway device.

*Tags:* `Users`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The user name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Gets the properties of the specified user.

*Tags:* `Users`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The user name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

### Creates a new user or updates an existing user's information on a data box edge/gateway device.

*Tags:* `Users`

#### Input Parameters
* `deviceName` - _required_ - The device name.
* `name` - _required_ - The user name.
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `api-version` - _required_ - The API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-edgegateway-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
