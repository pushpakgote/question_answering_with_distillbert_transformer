# Question Answering with Transformers
Question answering (QA) is a task of natural language processing that aims to automatically answer questions. The goal of extractive QA is to identify the portion of the text that contains the answer to a question. For example, when tasked with answering the question 'When will Jane go to Africa?' given the text data 'Jane visits Africa in September', the question answering model will highlight 'September'.

We wil use pre-trained DistilBert model and train it further.

- The goal of *extractive* QA is to identify the portion of the text that contains the answer to a question.
- Transformer models are often trained by tokenizers that split words into subwords.
  - Before processing, it is important that you align the start and end indices with the tokens associated with the target answer word.
