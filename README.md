# Project description
This project includes the following folders:
1.	Data: \
    a.	fodl_math_test.json: tập test \
    b.	fodl_math_val.json: set val \
    c.	fodl_math_train_imputed.json: train set with explanation data completed using GPT-3.5 \
    d.	math_test.json: test set similar to fodl_math_test.json but with an additional id field \
    e.	meta.pkl: file stores the data structures needed to perform tokenization 
2.	notebooks: \
    a.	random_chance.ipynb: choose random answer \
    b.	fodl_math_exp_0.ipynb: CNN-1D QA \
    c.	OpenAI_zero_shot.ipynb: bare LLM zeroshot learning \
    d.	OpenAI_one_shot.ipynb: bare LLM one shot learning \
    e.	OpenAI_few_shot.ipynb: bare LLM few shot learning \
    f.	OpenAI_CoT_zero_shot.ipynb: chain-of-thoughts zero shot learning \
    g.	OpenAI_CoT_one_shot.ipynb: chain-of-thoughts one shot learning \
    h.	OpenAI_CoT_few_shot.ipynb: chain-of-thoughts few shot learning 
3.	misc: \
    a.	OpenAI_generate_explanation: missing explanation generation source code using GPT-3.5 \
4.	predict: \
    a.	.dat files store data structures returned from API calls to the GPT-3.5 service \
    b.	The .json files save predictions as json files, which are the output of the above notebooks. Use notebook convert.ipynb to convert these files to csv format \
    c.	.csv files are files submitted to the Zalo AI Challenge contest 
5.	checkpoint:
    a.	3 checkpoint files include weight, hyperparameters and metrics when training the CNN-1D QA model \

# Use notebook files
Prepare the workspace on Colab as follows using the file fodl_math_exp_0.ipynb (the logs folder and .pdf files are the results after running the notebook). In case of using bare LLM and chain-of-thoughts, just upload the math_test.json file


# Demonstrate test results

<img src="images\image_2024-01-31_17-55-11.png" alt="Italian Trulli">
<img src="images\image_2024-01-31_17-55-12.png" alt="Italian Trulli">
