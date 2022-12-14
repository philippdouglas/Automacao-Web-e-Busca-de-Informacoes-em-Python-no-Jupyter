# Automação Web e Busca de Informações em Python no Jupyte

<div style="display: online_block"><br>
	<img align= "center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
	<img align= "center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg">	
</div>

## Desafio
Trabalhamos em uma importadora e o preço dos nossos produtos é vinculado a cotação de:
- Dólar
- Euro
- Ouro

Precisamos pegar na internet, de forma automática, a cotação desses 3 itens e saber quanto devemos cobrar pelos nossos produtos, considerando uma margem de contribuição que temos na nossa base de dados.

Base de Dados: https://docs.google.com/spreadsheets/d/1rIMbuYt4u-IIDmgYCTnzRfnBzKDkAZDG/edit?usp=sharing&ouid=106072107517560133298&rtpof=true&sd=true

Para isso, vamos criar uma automação web:

- Usaremos o selenium
- Importante: baixar o webdriver


<h2>Etapas</h2>

- Pegar a cotação do Dólar,Euro e Ouro
- Importar a lista de produtos 
- Recalcular o preço de cada produto
- Salvar os novos preços dos produtos


<h2>Dependências</h2>
<div style="display: online_block"><br>
	<img align= "center" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/anaconda/anaconda-original-wordmark.svg">	
</div>
	
Anaconda 
https://www.anaconda.com/products/distribution/start-coding-immediately

<div style="display: online_block"><br>
	<img align= "center" height="50" width="60" src="https://miro.medium.com/max/640/1*CMvcTaLSAD5A-WHCtnIFwA.png">	
</div>

ou use a versão online https://jupyter.org/try

<h2>Base de dados</h2>

Caso os arquivos não estejam mais disponíveis no google drive, o projeto acompanha os arquivos, porém é necessário alterar o código para o acesso local aos arquivos de base de dados.
