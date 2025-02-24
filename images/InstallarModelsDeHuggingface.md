---
marp: true
title: Instal·lar models de Hugging Face a Ollama
author: Agusti Moll
paginate: true
---
# Prerequisits

* Instal·lar ```git lfs```: ```sudo pacman -S git-lfs```

# Instal·lar
* Clonar repositori: ```git clone https://huggingface.co/BSC-LT/salamandra-7b```
* Creare un fitxer ```Modelfile``` via ```FROM```: En el directori ```salamandra-7b``` fer un fitxer ```salamadra.Modelfile``` amb ```FROM .```
* Importar-lo ```ollama create salamadra```

