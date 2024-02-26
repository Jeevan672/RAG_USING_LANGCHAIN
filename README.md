# RAG_USING_LANGCHAIN

![image](https://github.com/Jeevan672/RAG_USING_LANGCHAIN/assets/88030873/8156bc75-eac5-4f55-950f-99d26ace8a9d)


# Retrieval-Augmented Generation

RAG isn’t a specific set of technologies but rather a framework for providing LLMs
access to data they did not see during training. RAG allows LLM-powered applica‐
tions to make use of external data sources and applications to overcome some of the
knowledge limitations previously discussed.

RAG is useful in any case where you want the language model to have access to
additional data that is not contained within the LLMs “parametric memory” learned
during pretraining and fine-tuning. This could be data that did not exist in the origi‐
nal training data, such as proprietary information from your organization’s internal
data stores. Allowing your model to have access to this information helps improve
model completion relevance and helps to mitigate the challenge of hallucinations.
For knowledge cutoffs, RAG allows you to provide access to current information
beyond the model’s training date. This technique can augment foundation models
with additional information, including domain-specific information, without the
need to continuously perform full fine-tuning.

At a high level, a RAG-based architecture provides the model with access to external
sources of knowledge that provide additional context to the original input prompt in
the form of an augmented prompt, which is then used to call the LLM, as shown in FIG



1. Loader_1.ipynb
2. Document_splitter_2.ipynb
3. Vectorstores_and_embeddings_3.ipynb
4. Retrieval.ipynb
5. 05_question_answering.ipynb
6. memory&bot_L6.ipynb

   Note: API KEYS which are used in the code file will not work,Replace with your own API KEYS 

