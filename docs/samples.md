---
title: Microsoft Copilot for Microsoft 365 extensibility samples
description: Extend Microsoft Copilot for Microsoft 365 with plugins and Microsoft Graph connectors
author: jasonjoh
ms.author: jasonjoh
ms.topic: conceptual
ms.date: 11/15/2023
---

# Microsoft Copilot for Microsoft 365 extensibility samples

## Plugins for Copilot for Microsoft 365

### Teams message extension samples

The following samples implement Teams message extensions that extend Copilot for Microsoft 365.

| Sample | Description |
|--------|-------------|
| [Northwind Inventory extension](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-northwind-inventory-ts) | This TypeScript sample implements a Teams message extension that allows users to query data from the Northwind sample database and take action on that data. |
| [Azure AI search extension](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-doc-search-js) | This JavaScript sample implements a Teams message extension that uses Azure AI search to enable vector search of documents. |
| [.NET Product support extension](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-product-support-sso-csharp) | This .NET sample implements a Teams message extension that allows users to query Products held in SharePoint Online team site via Microsoft Graph. |
| [TypeScript Product support extension](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-product-support-sso-ts) | This TypeScript sample implements a Teams message extension that allows users to query Products held in SharePoint Online team site via Microsoft Graph. |
| [.NET Multi Parameters](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-multiparam-csharp) | Plugin that demonstrates how to implement complex utterances and support deep retrieval |
| [TypeScript Multi Parameters](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-multiparam-ts) | Plugin that demonstrates how to implement complex utterances and support deep retrieval |
| [JavaScript Multi Parameters](https://github.com/OfficeDev/Copilot-for-M365-Samples/tree/main/samples/msgext-multiparam-js) | Plugin that demonstrates how to implement complex utterances and support deep retrieval |

#### Write a message extension for Teams and Copilot for Microsoft 365

> [!VIDEO https://www.youtube.com/embed/zK-L83cwJ8c]

## Microsoft Graph connector samples

The following samples implement Microsoft Graph connectors that extend Copilot for Microsoft 365.

| Sample | Description |
|--------|-------------|
| [.NET Microsoft Graph docs connector](https://adoption.microsoft.com/sample-solution-gallery/sample/pnp-graph-connector-dotnet-csharp-graphdocs-ttk/) | This sample .NET project shows you how to build a Microsoft Graph connector to ingest unstructured data to Microsoft 365 and make it available to Copilot for Microsoft 365. The project uses Teams Toolkit for Visual Studio to package the connector as a Microsoft Teams apps and simplify its deployment in the organization. |
| [.NET GitHub connector](https://github.com/microsoftgraph/msgraph-sample-github-connector-dotnet) | This .NET application shows you how to use the Microsoft Graph connector API to create a custom connector that indexes issues and repositories from GitHub. This connector sample powers experiences such as Microsoft Search, Copilot in Teams, the Microsoft 365 App, and more. |
| [Python GitHub connector](https://github.com/microsoftgraph/msgraph-sample-github-connector-python) | This Python application shows you how to use the Microsoft Graph connector API to create a custom connector that indexes issues and repositories from GitHub. This connector sample powers experiences such as Microsoft Search, Copilot in Teams, the Microsoft 365 App, and more. |
| [TypeScript GitHub connector](https://github.com/microsoftgraph/msgraph-sample-github-connector-typescript) | This TypeScript application shows you how to use the Microsoft Graph connector API to create a custom connector that indexes issues and repositories from GitHub. This connector sample powers experiences such as Microsoft Search, Copilot in Teams, the Microsoft 365 App, and more. |

### Samples from the community

You can find the latest list of Microsoft Graph connector samples from the community in the [Microsoft Adoption center](https://adoption.microsoft.com/sample-solution-gallery/?product=Microsoft+Graph+connectors&product=Microsoft+365+Copilot).

### Build your first customer Graph connector for Copilot for Microsoft 365

> [!VIDEO https://www.youtube.com/embed/2oQ_6wXrwDQ]
