# ![LOGO](logo.png) ServiceBusManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ServiceBusManagementClient API (version 2017-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/servicebus/2017-04-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:17+03:00

## API Description

Azure Service Bus client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available ServiceBus REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Check the give namespace name availability.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the available namespaces within the subscription, irrespective of the resource groups.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the available premium messaging regions for servicebus

*Tags:* `PremiumMessagingRegions`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the available Regions for a given sku

*Tags:* `Regions`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `sku` - _required_ - The sku type.

### Gets the available namespaces within a resource group.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an existing namespace. This operation also removes all associated resources under the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a description for the specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a service namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a service namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the authorization rules for a namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a namespace authorization rule.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an authorization rule for a namespace by rule name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an authorization rule for a namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the primary and secondary connection strings for the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary or secondary connection strings for the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all Alias(Disaster Recovery configurations)

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Check the give namespace name availability.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an Alias(Disaster Recovery configuration)

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Retrieves Alias(Disaster Recovery configuration) for primary or secondary namespace

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a new Alias(Disaster Recovery configuration)

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the authorization rules for a namespace.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an authorization rule for a namespace by rule name.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the primary and secondary connection strings for the namespace.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation disables the Disaster Recovery and stops replicating changes from primary to secondary namespaces

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Invokes GEO DR failover and reconfigure the alias to point to the secondary namespace

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the Event Hubs in a service bus Namespace.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation Migrate the given namespace to provided name type

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all migrationConfigurations

*Tags:* `MigrationConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a MigrationConfiguration

*Tags:* `MigrationConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `configName` - _required_ - The configuration name. Should always be "$default".
    Possible values: $default.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Retrieves Migration Config

*Tags:* `MigrationConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `configName` - _required_ - The configuration name. Should always be "$default".
    Possible values: $default.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates Migration configuration and starts migration of entities from Standard to Premium namespace

*Tags:* `MigrationConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `configName` - _required_ - The configuration name. Should always be "$default".
    Possible values: $default.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation reverts Migration

*Tags:* `MigrationConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `configName` - _required_ - The configuration name. Should always be "$default".
    Possible values: $default.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation Completes Migration of entities by pointing the connection strings to Premium namespace and any entities created after the operation will be under Premium Namespace. CompleteMigration operation will fail when entity migration is in-progress.

*Tags:* `MigrationConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `configName` - _required_ - The configuration name. Should always be "$default".
    Possible values: $default.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the queues within a namespace.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$skip` - _optional_ - Skip is only used if a previous operation returned a partial result. If a previous response contains a nextLink element, the value of the nextLink element will include a skip parameter that specifies a starting point to use for subsequent calls.
* `$top` - _optional_ - May be used to limit the number of results to the most recent N usageDetails.

### Deletes a queue from the specified namespace in a resource group.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns a description for the specified queue.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a Service Bus queue. This operation is idempotent.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all authorization rules for a queue.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a queue authorization rule.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an authorization rule for a queue by rule name.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates an authorization rule for a queue.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Primary and secondary connection strings to the queue.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary or secondary connection strings to the queue.

*Tags:* `Queues`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `queueName` - _required_ - The queue name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the topics in a namespace.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$skip` - _optional_ - Skip is only used if a previous operation returned a partial result. If a previous response contains a nextLink element, the value of the nextLink element will include a skip parameter that specifies a starting point to use for subsequent calls.
* `$top` - _optional_ - May be used to limit the number of results to the most recent N usageDetails.

### Deletes a topic from the specified namespace and resource group.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns a description for the specified topic.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a topic in the specified namespace.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets authorization rules for a topic.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a topic authorization rule.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the specified authorization rule.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates an authorization rule for the specified topic.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the primary and secondary connection strings for the topic.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates primary or secondary connection strings for the topic.

*Tags:* `Topics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### List all the subscriptions under a specified topic.

*Tags:* `Subscriptions`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$skip` - _optional_ - Skip is only used if a previous operation returned a partial result. If a previous response contains a nextLink element, the value of the nextLink element will include a skip parameter that specifies a starting point to use for subsequent calls.
* `$top` - _optional_ - May be used to limit the number of results to the most recent N usageDetails.

### Deletes a subscription from the specified topic.

*Tags:* `Subscriptions`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns a subscription description for the specified topic.

*Tags:* `Subscriptions`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a topic subscription.

*Tags:* `Subscriptions`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### List all the rules within given topic-subscription

*Tags:* `Rules`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$skip` - _optional_ - Skip is only used if a previous operation returned a partial result. If a previous response contains a nextLink element, the value of the nextLink element will include a skip parameter that specifies a starting point to use for subsequent calls.
* `$top` - _optional_ - May be used to limit the number of results to the most recent N usageDetails.

### Deletes an existing rule.

*Tags:* `Rules`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `ruleName` - _required_ - The rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Retrieves the description for the specified rule.

*Tags:* `Subscriptions`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `ruleName` - _required_ - The rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a new rule and updates an existing rule

*Tags:* `Rules`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `topicName` - _required_ - The topic name.
* `subscriptionName` - _required_ - The subscription name.
* `ruleName` - _required_ - The rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-servicebus-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
