# M4-Group-Assignment-2
Submitted: 14/02/2024

Created by Benjamin, Camilla and Tobias.

## Part 1 Semantic search using Text and GIFs

### Task
Create something innovative using SBERT and semantic search

### Dataset
The dataset used for this project is various GIF's and its description with 125k datapoints. Can be found [here.](https://github.com/raingo/TGIF-Release/archive/master.zip)

### Approach
1. **Feature Selection**: Identify relevant features.

2. **Feature Engineering**: Conduct any necessary feature transformations. Reducing Dataset to 20k data rows.

3. **Modelling/Embedding**: Load the CLIP model and make embeddings on the dataset.

4. **Defining the semantic search function**: search function to return GIF url, description and cosinus score
   
5. **Make Application**: Making an application with the Gradio interface.

### Results

A functional Gradio application that gives the approapriate GIF to the text that you write. The app can be seen [here.](https://6dfc4a400a4e616c4a.gradio.live/)


## Part 2 Gradient Descent and Attention Mechanism Exercises

### Task
1. Gradient Descent Exercise: Execute the process of updating weights for two examples using Stochastic Gradient Descent (SGD). Document each step, including input calculation, prediction, loss assessment, weight adjustments, and updates.

2. Attention Mechanism Exercise: Implement the attention mechanism on two distinct sentences. Choose sentences with polysmous words to demonstrate its functionality effectively.
### Data
The two distinct sentences presented are:
sentence1 = "She saw a bat flying in the night sky"
sentence2 = "He used a bat to hit the baseball during the game"

### Approach
1. **Load Model**: Using SBERT to solve this task
   
3. **Embedding**: Compute embedding and encoding the sentences
   
5. **Compute attention scores and context vector**
  
7. **Evaulating**: Plotting a heatmap and evaulating the score

### Results
We see that the model finds a strong correlation between the words 'bat' and 'baseball' in sentence 2, where it struggles a bit more in sentence 1. Here the strongest corralations with the word 'bat' is in the words 'sky' and 'she'. So the model misunderstands the context a bit in sentence 1.

