# ![LOGO](logo.png) Workload Monitor **flow**ground Connector

## Description

A generated **flow**ground connector for the Workload Monitor API (version 2018-08-31-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/workloadmonitor-Microsoft.WorkloadMonitor/2018-08-31-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:29+03:00

## API Description

APIs for workload monitoring

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the details of all operations possible on the resource provider.

*Tags:* `WorkloadInsights`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get subscription wide details of components.

*Tags:* `WorkloadInsights`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$select` - _optional_ - Properties to be returned in the response.
* `$filter` - _optional_ - Filter to be applied on the operation.
* `$apply` - _optional_ - Apply aggregation.
* `$orderby` - _optional_ - Sort the result on one or more properties.
* `$expand` - _optional_ - Include properties inline in the response.
* `$top` - _optional_ - Limit the result to the specified number of rows.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get subscription wide health instances.

*Tags:* `WorkloadInsights`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$select` - _optional_ - Properties to be returned in the response.
* `$filter` - _optional_ - Filter to be applied on the operation.
* `$apply` - _optional_ - Apply aggregation.
* `$orderby` - _optional_ - Sort the result on one or more properties.
* `$expand` - _optional_ - Include properties inline in the response.
* `$top` - _optional_ - Limit the result to the specified number of rows.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get list of components for a resource.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$select` - _optional_ - Properties to be returned in the response.
* `$filter` - _optional_ - Filter to be applied on the operation.
* `$apply` - _optional_ - Apply aggregation.
* `$orderby` - _optional_ - Sort the result on one or more properties.
* `$expand` - _optional_ - Include properties inline in the response.
* `$top` - _optional_ - Limit the result to the specified number of rows.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get details of a component.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `componentId` - _required_ - Component Id.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$select` - _optional_ - Properties to be returned in the response.
* `$expand` - _optional_ - Include properties inline in the response.

### Get list of monitor instances for a resource.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$select` - _optional_ - Properties to be returned in the response.
* `$filter` - _optional_ - Filter to be applied on the operation.
* `$apply` - _optional_ - Apply aggregation.
* `$orderby` - _optional_ - Sort the result on one or more properties.
* `$expand` - _optional_ - Include properties inline in the response.
* `$top` - _optional_ - Limit the result to the specified number of rows.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get details of a monitorInstance.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `monitorInstanceId` - _required_ - MonitorInstance Id.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$select` - _optional_ - Properties to be returned in the response.
* `$expand` - _optional_ - Include properties inline in the response.

### Get list of a monitors of a resource.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$filter` - _optional_ - Filter to be applied on the operation.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get details of a single monitor.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `monitorId` - _required_ - Monitor Id.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.

### Update a Monitor's configuration.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `monitorId` - _required_ - Monitor Id.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.

### Get list of notification settings for a resource.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.
* `$skiptoken` - _optional_ - The page-continuation token to use with a paged version of this API.

### Get a of notification setting for a resource.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `notificationSettingName` - _required_ - Default string modeled as parameter for URL to work correctly.
    Possible values: default.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.

### Update notification settings for a resource.

*Tags:* `WLIExtension`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `resourceNamespace` - _required_ - The Namespace of the resource.
* `resourceType` - _required_ - The type of the resource.
* `resourceName` - _required_ - Name of the resource.
* `notificationSettingName` - _required_ - Default string modeled as parameter for URL to work correctly.
    Possible values: default.
* `api-version` - _required_ - The API version to use for this operation.
    Possible values: 2018-08-31-preview.

## License

**flow**ground :- Telekom iPaaS / azure-com-workloadmonitor-microsoft-workload-monitor-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
