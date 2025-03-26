# Training a model


## Generate a vector database



## Generate a new model

conde create -n training python=3.10.9

conda acitvitvate training

pip install torch transformers datasets

// test cuda :
python -c "import torch; print(torch.cuda.is_available())"


pip install pymilvus pymupdf sentence-transformers