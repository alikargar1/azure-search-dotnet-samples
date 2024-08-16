# C# samples for Azure AI Search fundamentals

This repository contains C# code samples used in Azure AI Search "Day One" quickstarts and tutorials. Unless noted otherwise, all samples run on the shared (free) pricing tier of an [Azure AI Search service](https://learn.microsoft.com/azure/search/search-create-service-portal).

## In this repository

| Sample | Description |
|--------|-------------|
| create-mvc-app | This ASP.NET Core MVC sample demonstrates server-side search behaviors, such as filters and sorting. |
| quickstart | Learn the fundamental tasks of working with a search index: create, load, and query for full text search scenarios. This quickstart is a console application. The index is modeled on a subset of the Hotels dataset, widely used in Azure AI Search samples, but reduced to just four hotels for readability and comprehension. |
| quickstart-semantic-search | Adds semantic search to the previous quickstart.|
| tutorial-ai-enrichment | This console app creates an AI enrichment pipeline consisting of an index, indexer, data source, and skillset. The skillset calls Azure AI Services image analysis and OCR, and natural language processing, extract information and structure from heterogeneous blob content, making it searchable in Azure AI Search. |

## Previously in this repository

The following samples are relocated to new repositories that align content to specific categories. 

| Sample | New location |
|--------|--------------|
| tutorial-search-website-functions-v4 | [azure-search-static-web-app](https://github.com/Azure-Samples/azure-search-static-web-app) |
| check-storage-usage | [azure-search-dotnet-utilities/check-storage-usage](https://github.com/Azure-Samples/azure-search-dotnet-utilities/tree/main/check-storage-usage) |
| data-lake-gen2-acl-indexing | [azure-search-dotnet-utilities/data-lake-gen2-acl-indexing](https://github.com/Azure-Samples/azure-search-dotnet-utilities/tree/main/data-lake-gen2-acl-indexing) |
| export-data | [azure-search-dotnet-utilities/export-data](https://github.com/Azure-Samples/azure-search-dotnet-utilities/tree/main/export-data) |
| index-backup-restore | [azure-search-dotnet-utilities/index-backup-restore](https://github.com/Azure-Samples/azure-search-dotnet-utilities/tree/main/index-backup-restore)|
| search-aggregations | [azure-search-dotnet-utilities/search-aggregations](https://github.com/Azure-Samples/azure-search-dotnet-utilities/tree/main/search-aggregations)|
| multiple-data-sources | [azure-search-dotnet-scale/multiple-data-sources](https://github.com/Azure-Samples/azure-search-dotnet-scale/tree/main/multiple-data-sources) | 
| multiple-search-services | [azure-search-dotnet-scale/multiple-search-services](https://github.com/Azure-Samples/azure-search-dotnet-scale/tree/main/multiple-search-services) |
| optimize-data-indexing | [azure-search-dotnet-scale/optimize-data-indexing](https://github.com/Azure-Samples/azure-search-dotnet-scale/tree/main/optimize-data-indexing) |

## More resources

+ See [Vector samples in Azure AI Search](https://github.com/Azure/azure-search-vector-samples/tree/main/demo-dotnet) for code samples that call the Azure SDK for .NET.

+ See [.NET samples in Azure AI Search](https://learn.microsoft.com/azure/search/samples-dotnet) for a comprehensive list of all Azure AI Search code samples that run on .NET.

+ See [Azure AI Search documentation](https://learn.microsoft.com/azure/search) for product documentation.
