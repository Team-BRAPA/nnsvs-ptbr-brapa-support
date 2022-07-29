# nnsvs-ptbr-brapa-support
Brazilian Portuguese language support project for the AI synthesizer [NNSVS](https://github.com/nnsvs/nnsvs) using the connotation [BRAPA](https://github.com/overdramatic/BRAPA)

🇧🇷 Se quiser ler este arquivo em Português Brasileiro [clique aqui](https://github.com/overdramatic/nnsvs-ptbr-brapa-support/blob/main/README.md)

This repository provides hed files and the dictionary table to create an AI singing model in Brazilian Portuguese with support for various language accents.

## 📄 Files

 1. /hed 

 	`nnsvs_ptbr_brapa.hed` - .hed file containing the most common phonemes among Brazilian accents for training

 	`nnsvs_ptbr_brapa_full.hed` - .hed file containing all phonemes found in BRAPA table. Not recommended for training
  
 2. /dic

	`dict.table` - table containing only phonemes used in the common BRAPA list
	
	`dict_full.table` - table containing all the phonemes used in the BRAPA full list

## 🎶 Example
Example of model trained with 8 minutes of data, using [OpenUtau](https://github.com/stakira/OpenUtau) as an editing tool

https://user-images.githubusercontent.com/68165064/181655361-4cf0d0fa-f70f-464d-87bb-ebe180972417.mp4

## ➕ Additional Information
The .hed files were created by hand using as a base the files available within the NNSVS repository

[FONEMAS.md](https://github.com/overdramatic/nnsvs-ptbr-brapa-support/blob/main/FONEMAS.md) (only in portuguese) is a file that contains all BRAPA phonetics converted into X-Sampa + additional phonetics with examples

⚠️ **IMPORTANT:** When using these project files, modifying them or not, carefully read the license found in [LICENSE](https://github.com/overdramatic/nnsvs-ptbr-brapa-support/blob/main/LICENSE) and credit the **Team BRAPA** (HAI-D, Nachokuma, Xiao, Fuka, Kaiske) within your model/file
