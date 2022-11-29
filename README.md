# prompting

This project has notebooks which perform in context learning. The large language models that were used for prompting were GPT-3 and OPT.

To prompt GPT-3 an OpenAI account is required. These notebooks can be run on google colab, and a copy of the open ai api key needs to be saved on the drive before running the colab notebook.

The colab notebooks are as follows:
1. GPT_3_prompting.ipynb - This notebook introduces how to use prompting for natural language inference using the rte dataset. The large langugage model being prompted is GPT-3 (175 Billion parameters) using the inference API provided by OpenAI.

2. ask_gpt_3.ipynb - This notebook uses prompting to generate templates for gpt-3. It evaluates the performance of these prompts on the rte dataset.

3. opt_prompting.ipynb - This notebook uses prompting to generate templates for gpt-3. It evaluates the performance of these prompts on the rte dataset.

4. PoolOfPrompts.ipynb - This notebook analyzes some of the attributes of the collection of prompts in P3.
