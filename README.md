# Amazon Bedrock SDK Lab

A hands-on repository for exploring the Amazon Bedrock SDK through practical examples in both Java and Python.

The goal of this repository is to go beyond documentation and sample code by running, debugging, modifying, and comparing Amazon Bedrock APIs directly.

The same concepts are explored across both SDKs to better understand what belongs to Amazon Bedrock itself and what differs between the Java and Python implementations.

## Repository Structure

```text
amazon-bedrock-sdk-lab/
├── java-sdk/
└── python-sdk/
```

Each SDK directory contains experiments and examples related to different Amazon Bedrock APIs and capabilities.

Examples may include:

* Amazon Bedrock control-plane APIs
* Bedrock Runtime
* Model inference
* Converse API
* Streaming responses
* Embeddings
* Image generation
* Knowledge Bases
* Agents
* Agent Runtime
* Prompt Flows
* Tool use
* Guardrails
* RAG workflows
* Other Bedrock capabilities explored along the way

## Why This Repository Exists

Amazon Bedrock provides several SDK clients and APIs with similar names but very different responsibilities.

For example:

```text
bedrock
bedrock-runtime
bedrock-agent
bedrock-agents-runtime
```

Rather than treating them as abstract SDK documentation, this repository explores them by actually running the code and observing their behavior.

The main questions behind each experiment are:

* What does this API do?
* Is it a control-plane or runtime API?
* What AWS resources does it create, configure, or invoke?
* What is the request and response structure?
* What happens behind the scenes?
* How does the Java implementation compare with Python?
* Where would this API be used in a real-world architecture?

## Java SDK

```text
java-sdk/
```

Experiments using the AWS SDK for Java 2.x.

The Java examples focus on understanding the SDK clients, request and response objects, asynchronous and synchronous APIs, streaming behavior, and integration with other AWS services.

## Python SDK

```text
python-sdk/
```

Experiments using AWS SDK for Python (Boto3).

The Python implementations provide a second perspective on the same Bedrock capabilities and make it easier to distinguish service-level concepts from SDK-specific abstractions.

## Learning Approach

The approach used throughout this repository is simple:

```text
Read the example
      ↓
Run it
      ↓
Debug it
      ↓
Inspect the request
      ↓
Inspect the response
      ↓
Modify it
      ↓
Compare Java and Python
      ↓
Understand the architecture
```

This repository is primarily a learning laboratory rather than a collection of production-ready applications.

The focus is on understanding Amazon Bedrock from the SDK level upward and connecting individual API calls to the larger AWS architecture.

## Reference

Many experiments in this repository are inspired by and adapted from the official AWS SDK code examples:

`awsdocs/aws-doc-sdk-examples`

The original AWS examples serve as a starting point. The code in this repository may be modified, reorganized, debugged, annotated, or extended as part of the learning process.
