---
page_type: sample
languages:
  - rest
name: "Quickstart: Semantic ranking in Azure AI Search using REST APIs"
description: |
  Create a multimodal indexing pipeline using skills that extract, chunk, and vectorize text and image content.
products:
  - azure
  - azure-cognitive-search
  - azure-ai-search
urlFragment: rest-api-multimodal-tutorial
---

# Extract, chunk, and vectorize multimodal content

![Flask sample MIT license badge](https://img.shields.io/badge/license-MIT-green.svg)

This sample provides four REST files that demonstrate different combinations of skills for extracting, chunking, and vectorizing text and images from a PDF. All four samples build a complete indexer pipeline. Included are requests for querying the content and checking indexer status.

## What's in this sample

| File | Description |
|------|-------------|
| `document-extraction-azure-ai-vision.rest` | Skills used: Document Extraction, Text Split, Azure AI Vision, Shaper |
| `document-extraction-image-verbalization-text-embedding.rest` | Skills used: Document Extraction, Text Split, Azure OpenAI Embedding, GenAI Prompt, Shaper  |
| `document-layout-azure-ai-vision.rest` | Skills used: Document Layout, Azure AI Vision, Shaper |
| `document-layout-image-verbalization-text-embedding.rest` | Skills used: Document Layout, Azure OpenAI Embedding, GenAI Prompt, Shaper |

## Documentation

This sample is the REST component of the [Tutorial: Extract, chunk, and vectorize multimodal content](https://learn.microsoft.com/azure/search/tutorial-multimodal).

## Next step

You can learn more about Azure AI Search on the [official documentation site](https://learn.microsoft.com/azure/search).
