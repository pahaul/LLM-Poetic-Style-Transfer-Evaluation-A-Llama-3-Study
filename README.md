# LLM-Poetic-Style-Transfer-Evaluation-A-Llama-3-Study

This project demonstrates expertise in Generative AI deployment and advanced prompt engineering by utilizing a powerful local Large Language Model (LLM) to automatically generate a structured corpus of German poems. The goal was to create a novel dataset for downstream quantitative analysis (specifically, an [Burrows Delta](https://github.com/fastdatascience/faststylometry) analysis against the [German Poetry Corpus (DLK)](https://github.com/tnhaider/DLK).

The focus lies on two core tasks: unconstrained creative generation and complex stylistic imitation (style transfer).

**Core Competencies & Data Generation Workflow**

Generative AI Deployment (Local): Successful implementation of the Meta-Llama-3-8B-Instruct model using the Hugging Face transformers library and PyTorch for efficient, local inference.

Data Generation & Structuring: Automated creation of a sizable, structured corpus of generated text (100+ poems) ready for specialized evaluation.

Advanced Prompt Engineering: Development of a strict System Prompt and dynamically generated User Prompts to enforce constraints and initiate complex creative tasks (style transfer).

Data Sourcing Integration: Integration of external linguistic data (DLK-derived list of top 20 German authors) to guide the constrained generation process.
