# Training a model


## Generate a vector database



## Generate a new model

conde create -n training python=3.10.9

conda acitvitvate training

pip install torch transformers datasets

// test cuda :
python -c "import torch; print(torch.cuda.is_available())"


pip install pymilvus pymupdf sentence-transformers


## Vision-parse [No fa molt fi...]

git clone https://github.com/iamarunbrahma/vision-parse

conda create -n vision-parse python=3.10.9

conda activate vision-parse


## Passar PDF per OCR

apt install ocrmypdf
apt install tesseract-ocr-spa tesseract-ocr-cat

ocrmypdf -l cat+spa --force-ocr --output-type pdf src/file001.pdf dest/file001.pdf
