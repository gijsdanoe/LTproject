# Language Technology Project: Frame Identification

By Wanqian Bao, Gijs Danoe and Pauline Schomaker

This is the Github repository of our project on frame identification. In this project, we used 3 different models:

## 1. Promptless BERT

The code can be found in 'LT_BERT.ipynb'.
1. Change the file paths to a folder with the data.
2. Run all cells, if you wish not to remove the topic features avoid running that cell.

## 2. Prompting with BERT

## 3. Prompting with GPT-3

The code can be found in 'LT_GPT3.ipynb'.
1. Change the file paths to a folder with the data.
2. Change the key to your OpenAI API key.
3. Run all cells, if you wish not to remove the topic features avoid running that cell.
4. The GPT-3 approach has five different methods: few-shot prompt completion, zero-shot classification, few-shot classification, zero-shot QA and few-shot QA. Uncomment the code snippets for the prompts accordingly.
5. For QA, the engine needs to be changed to 'text-davinci-002' for acceptable results, but be cautious as this is expensive.
