# azure-activities
# Using Your Own Data with Azure OpenAI

This guide provides an overview of how to use your own data with Azure OpenAI, Designing and Implementing a Microsoft Azure AI Solution.

## Prerequisites

Before you start, ensure you have the following:
- An Azure OpenAI resource deployed in a supported region.
- Access to Azure Blob Storage and Azure AI Search.
- Cognitive Services Contributor role assigned to your Azure OpenAI resource.

## Steps to Use Your Own Data

### 1. Add Your Data

1. Navigate to the Azure OpenAI Studio.
2. Select the "Bring your own data" tile.
3. Upload your files. Supported file types include .txt, .md, .html, .docx, .pptx, and .pdf.
4. Enable Cross-origin resource sharing (CORS) for your Azure Blob Storage if not already enabled.

### 2. Data Management

1. Choose whether to enable semantic search or vector search for your index. Note that these features may incur additional costs.
2. Use the data preparation script available on GitHub for documents with long text or special formatting.

### 3. Chatting with Your Data

1. Use the Chat playground in Azure OpenAI Studio to interact with your data.
2. This allows for more accurate and contextually relevant responses based on your specific data.


## Conclusion

Using your own data with Azure OpenAI can significantly enhance the capabilities of your AI solutions, providing more accurate and relevant responses. Follow the steps and best practices outlined in this guide to get started.

