# GeoLLM-Report-Interpreter
## GeoLLM: Automated Interpretation of Geotechnical Reports and Boring Logs Using Large Language Models

This project proposes GeoLLM, a domain-specialized document intelligence system that leverages Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to automatically extract, normalize, and structure engineering-relevant information from geotechnical reports. Unlike generic document AI systems, GeoLLM incorporates geotechnical semantics, engineering constraints, and schema-driven extraction to ensure outputs suitable for downstream engineering workflows such as preliminary foundation assessment and design verification.

The system ingests raw geotechnical documents (PDFs, scanned boring logs, and laboratory reports), performs robust text extraction and chunking, embeds domain-specific content into a vector database, and queries an LLM using carefully engineered prompts to generate validated, structured outputs (JSON/Excel). The architecture is modular, auditable, and deployable, supporting both academic experimentation and practical engineering use.

From a research perspective, the project evaluates LLM effectiveness in technical civil engineering language, compares prompt-based and retrieval-augmented extraction strategies, analyzes error modes, and assesses consistency against human expert interpretations. The long-term vision is a geotechnical AI co-pilot that enhances standardization, scalability, and efficiency in subsurface data interpretation.
