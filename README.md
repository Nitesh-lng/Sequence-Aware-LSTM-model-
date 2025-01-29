![Screenshot 2025-01-29 at 8 21 05 AM](https://github.com/user-attachments/assets/acda9596-725a-4583-a3b8-17048c40ee54)




**Workflow Steps**
------------------------------------------------------------------------------------

**1. Install Dependencies**

Install necessary libraries: torch, torchtext, datasets.

**2. Load Dataset**

Use datasets.load_dataset to fetch text-based data.

**3. Preprocess Data**

Tokenize text using get_tokenizer.

Build vocabulary using build_vocab_from_iterator.

**4. Prepare Data for Training**

Convert tokens into numerical indices.

Create data loaders for batching.

**5. Define the Model**

Implement an LSTM-based model using torch.nn.Module.

**6. Train the Model**

Use torch.optim for optimization.

Implement a training loop with backpropagation.

**7. Evaluate the Model**

Switch to evaluation mode and compute accuracy/metrics.

**8. Save & Export the Mode**l

Save the trained model for later inference.



**NLP pipeline with these key components**
----------------------------------------------------------------------------------------------

1.**Data Loading** – Uses datasets.load_dataset to fetch text data.

2.**Tokenization** – Uses torchtext.data.get_tokenizer for preprocessing.

3.**Vocabulary Building** – Constructs a vocabulary from the dataset.

4.**Model Definition** – Implements a neural network (possibly LSTM).

5.**Training Loop** – Iterates over epochs for model training.

6.**Evaluation** – Switches the model to evaluation mode for performance testing.




**Installation**_

pip install torch torchtext datasets

**Usage**_

python train.py 

python evaluate.py

**Directory Structure**

SALSTM/
|-- data/          
|-- models/        
|-- train.py       
|-- evaluate.py    
|-- requirements.txt 
