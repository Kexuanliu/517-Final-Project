# 517-Final-Project

Link to data folder: https://drive.google.com/drive/folders/1gwRPVjreE5iGJNAIGQIJaeVj2FW0HpuX?usp=sharing

Instructions on how to run code:<br />
We have three notebooks:<br />
prompted.ipynb includes code that downloads all the data, generates sentences using prompts with three models: GPT-1, GPT-2 and CTRL, and produces toxicity summaries of those generations.<br />
unprompted_generation.ipynb includes code that generates sentences using respective start-of-sentence token of the same three models.<br />
unprompted_results.ipynb includes code that produces the graph of toxicity with respect to number of experiment trials using those generations.<br />
<br />
To run each notebook, firstly replace all the paths to the places that store corresponding data, then just run each block in order. The unprompted_generation.ipynb should be run before unprompted_results.ipynb since unprompted_results.ipynb needs the generations generated by unprompted_generation.ipynb. Each notebook should be run in GPU runtime.
