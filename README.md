# nnsvs-ptbr-brapa-support
Projeto de suporte a língua Portuguesa Brasileira para o sintetizador AI [NNSVS](https://github.com/nnsvs/nnsvs) utilizando a conotação [BRAPA](https://github.com/overdramatic/BRAPA)

🇺🇸 If you want to read this file in English, [click here](https://github.com/overdramatic/nnsvs-ptbr-brapa-support/blob/main/README_EN.md)

Este repositório fornece arquivos hed e a tabela dicionário para criar um modelo de canto AI em Português Brasileiro com suporte a diversos sotaques do idioma. 

## 📄 Arquivos

 1. /hed
 
	 `nnsvs_ptbr_brapa.hed` - arquivo .hed contendo os fonemas mais comuns entre os sotaques do Brasil para o treino 
	 
	 `nnsvs_ptbr_brapa_full.hed` - arquivo .hed contendo todos os fonemas encontrado na tabela BRAPA. Não recomendado para treino 
 2. /dict
 
	 `dict.table` - tabela contendo apenas fonemas utilizados na lista BRAPA comum
	 
	 `dict_full.table`- tabela contendo todos os fonemas utilizados na lista BRAPA full

## 🎶 Exemplo
Exemplo de modelo treinado com 8 minutos de dado, utilizando [OpenUtau](https://github.com/stakira/OpenUtau) como ferramenta de edição

https://user-images.githubusercontent.com/68165064/181655361-4cf0d0fa-f70f-464d-87bb-ebe180972417.mp4

## ➕ Informações Adicionais
Os arquivos .hed foram criados a mão utilizando como base os arquivos disponibilizados dentro do NNSVS

[FONEMAS.md](https://github.com/overdramatic/nnsvs-ptbr-brapa-support/blob/main/FONEMAS.md) é um arquivo que contém toda a fonética BRAPA convertida em X-Sampa + fonética adicionais e com exemplos

⚠️ **IMPORTANTE:** Ao utilizar estes arquivos de projeto, modificando-as ou não, leia atentamente a licença encontrada no [LICENSE](https://github.com/overdramatic/nnsvs-ptbr-brapa-support/blob/main/LICENSE) e credite o **Time BRAPA** (HAI-D, Nachokuma, Xiao, Fuka, Kaiske) dentro do seu modelo/arquivo
