# gen-ai-catalogue
Catalogue of use-cases fit for GenAI

# Usecases
## [Question Answering](./Question-Answering/README.md)
## [Chatbot](./Chatbot/README.md)
## [Agent](./Autonomous%20Agent/README.md)
## [Document Understanding](./Document%20Understanding/README.md)
## [Multi-modal](./Multi-modal/README.md)
## [Fine-tuning](./Fine-tuning/README.md)

# Frameworks
## LlamaIndex
> Try https://github.com/run-llama/llamacloud-demo/tree/main/examples 
### Agents
*Agents* are LLM-powered knowledge assistants that use tools to perform tasks like research, data extraction, and more. Agents range from simple question-answering to being able to sense, decide and take actions in order to complete tasks

## Workflows
*Workflows* are multi-step processes that combine one or more agents, data connectors, and other tools to complete a task. They are event-driven software that allows you to combine RAG data sources and multiple agents to create a complex application that can perform a wide variety of tasks with reflection, error-correction, and other hallmarks of advanced LLM applications

## Frameworks
**LlamaIndex** is the framework for Context-Augmented LLM Applications
- *Data connectors* ingest your existing data from their native source and format. These could be APIs, PDFs, SQL, and (much) more.
- *Data indexes* structure your data in intermediate representations that are easy and performant for LLMs to consume.
- *Engines* provide natural language access to your data. For example:
  - Query engines are powerful interfaces for question-answering (e.g. a RAG flow).
  - Chat engines are conversational interfaces for multi-message, "back and forth" interactions with your data.
- *Agents* are LLM-powered knowledge workers augmented by tools, from simple helper functions to API integrations and more.
- *Observability/Evaluation* integrations that enable you to rigorously experiment, evaluate, and monitor your app in a virtuous cycle.
- *Workflows* allow you to combine all of the above into an event-driven system for flexible than other, graph-based approaches.

# Jargon
- **Adversarial** - Adversarial machine learning (AML) is the process of extracting information about the behavior and characteristics of an ML system and/or learning how to manipulate the inputs into an ML system in order to obtain a preferred outcome.
- **Hallucination** - AI hallucinations occur when an AI model generates incorrect or misleading information, often appearing confident in its output.
  - Reason
    - Insufficient training data: The model may not have enough training data to make accurate predictions.
    - Incorrect assumptions: The model may make incorrect assumptions about the data.
    - Biases: The data used to train the model may be biased. 
    - Processing errors: The model may make errors while processing the data.
    - Misapplied patterns: The model may apply learned patterns that aren't present in the input data.
  - Correction
    - Training with adversarial examples: This strengthens the model. 
    - Fine-tuning with metrics: This penalizes errors in the model. 
    - Using data templates: This provides a predefined format for the model's output. 
    - Limiting responses: This helps prevent the model from producing faulty results. 
    - Using grounding: This anchors the model's responses to real-time data.
- **Quantization** - Quantization is just a method for reducing the size of an LLM by shrinking the accuracy of calculations within the model. Research has shown that up to 4Bit quantization can be achieved for large LLMs without impacting performance too severely