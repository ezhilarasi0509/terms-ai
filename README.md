# terms-ai
This video serves as a comprehensive primer for software engineers entering the field of artificial intelligence, outlining 20 foundational concepts necessary for effective technical communication and system design.

### Core Artificial Intelligence Fundamentals

*   **Large Language Model (LLM):** A sophisticated **neural network** architecture designed to predict the subsequent token in a sequence of text.
*   **Tokenization:** The foundational process of breaking down raw input text into discrete, manageable units called **tokens**, which allows the model to analyze linguistic patterns.
*   **Vectorization:** A mathematical process that maps words into an **n-dimensional coordinate space**, ensuring that terms with similar semantic meanings are clustered together.
*   **Attention:** A critical mechanism that enables models to resolve ambiguity by weighting the importance of different words in a sentence relative to one another to derive **contextual meaning**.
*   **Self-Supervised Learning:** An efficient training paradigm where the model identifies and predicts hidden structures within raw data, eliminating the need for extensive human-labeled datasets.
*   **Transformer:** The primary neural network architecture that utilizes stacked layers of attention and feed-forward networks to process information effectively.

### Engineering, Training, and Optimization

*   **Fine-tuning:** The process of adapting a pre-trained **base model** to perform domain-specific tasks or adopt specialized jargon through further training on curated question-answer datasets.
*   **Few-shot Prompting:** A technique involving the inclusion of specific, representative examples within the user prompt to guide the model toward a higher-quality output.
*   **Retrieval Augmented Generation (RAG):** An architectural pattern where the system retrieves external, relevant documents from a database to provide the LLM with grounded, real-time context.
*   **Vector Database:** A specialized storage system optimized for performing high-speed **similarity searches** on vector embeddings.
*   **Model Context Protocol (MCP):** A standardized communication interface that allows LLMs to securely connect to and query external tools, APIs, and databases.
*   **Context Engineering:** The holistic management of system prompts, user chat history, and contextual summarization to maintain long-term coherence during interactions.

### Advanced Architectures and Techniques

*   **Agents:** Independent, long-running processes capable of leveraging tools and interacting with external environments to achieve complex, multi-step goals.
*   **Reinforcement Learning:** A training method that utilizes **human feedback** or outcome scores to iteratively improve the model's response quality.
*   **Chain of Thought:** A prompting strategy that forces the model to decompose complex problems into logical, sequential steps, significantly enhancing reasoning capabilities.
*   **Reasoning Models:** Advanced architectures specifically optimized for explicit, step-by-step problem-solving and deduction.
*   **Multi-modal Models:** Versatile systems trained to process and generate content across diverse inputs, including text, images, and video.
*   **Small Language Models (SLM):** Highly efficient models with a significantly lower parameter count, designed for specialized tasks and reduced infrastructure costs.
*   **Distillation:** A knowledge-transfer technique where a smaller student model is trained to mimic the behavioral outputs of a larger teacher model.
*   **Quantization:** A computational optimization that reduces the numerical precision of model weights (e.g., from 32-bit to 8-bit) to decrease memory usage and accelerate inference speeds.
