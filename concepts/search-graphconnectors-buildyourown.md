---
title: "Build your first custom Graph connector"
ms.author: mecampos
author: mecampos
manager: umas

description: "Build your first custom Graph connector"
---

# Build your first custom Graph connector

## Step 1: Get an access token

### Register an Azure Active Directory app
Go to Azure Active Directory and register an app to allow Microsoft Search to access data for indexing. 

To learn more, refer to the Microsoft Graph documentation on how to [register an app](https://docs.microsoft.com/en-us/graph/auth-register-app-v2).

Before moving to the next step, go to API permissions, add the permission named "ExternalItem.ReadWrite.All", and grant Admin Consent.

### Get an access token for the app
After completing the app registration and taking note of the app name, application (client) ID, and tenant ID, you need to generate a new client secret. The client secret will only be displayed once. Remember to save the client's secret securely. Use the client ID and client secret while configuring a new connection in Microsoft Search.

## Step 2: Build your connector

### Create a connection
Go to [Link needs confirmation](https://graph.microsoft.com/beta/external/connections), use the access token you got in the previous step, and make a request. Select a unique app ID within the tenant.

### Register the connection schema
You can set the search schema attributes to control the search functionality of each source property. Search schema attributes include options to Query, Search, Retrieve, and Refine.

To learn more, visit the following link: [Manage connections](https://docs.microsoft.com/en-us/graph/search-index-manage-schema)

### Index content
Go to your connection and edit the properties of your external items.

To learn more, visit the following link: [Manage items](https://docs.microsoft.com/en-us/graph/search-index-manage-items#access-control-list)

## Step 3: Search index content

### Using Microsoft search experiences
Search content from Microsoft search experiences by customizing your search results, adding a vertical, and defining the results layout.

[Manage verticals and result types](https://docs.microsoft.com/en-us/microsoftsearch/customize-search-page)

[Manage search result layouts](https://docs.microsoft.com/en-us/microsoftsearch/customize-results-layout)

## More resources

- Follow a step by step guide on how to use the Microsoft Graph indexing API to create a connection to the Microsoft Search service and index custom items: [Microsoft Graph Search Connector Sample](https://github.com/microsoftgraph/msgraph-search-connector-sample)

- Watch a video to learn [how to build your own Microsoft Graph Connectors](https://www.youtube.com/watch?v=S6s-bvvtDZk)
<!--- > [!VIDEO https://www.youtube.com/watch?v=S6s-bvvtDZk] --->
