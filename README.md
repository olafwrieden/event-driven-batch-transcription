# Event-Driven Batch Transcription
An example of how to batch transcribe voice recordings using an event-driven architecture in Azure.

This repository is an extension of my [Azure Batch Transcription using Python in Databricks](https://github.com/olafwrieden/batch-transcription-python-azure-databricks) example.

## Outcome & Overview
Using the [Speech to Text Cognitive Service](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/) in Azure, we want to transcribe voice recordings into JSON files using parallel (batch) processing. Once a new recording is uploaded to a source Blob Storage container, an event is fired and triggers the transcription function which processes multiple new recordings.

Adopted from: [Speech to Text Batch Transcription - Demo](https://github.com/timleyden/speechtotextdemo)
