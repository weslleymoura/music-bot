# Bem vindo ao Music Bot!

<img style="float: left;" src="music_bot.png">
<br>

### Este é o seu assistente musical!

<p>Ele lista as principais músicas da sua banda ou artista favorito e faz uma análise musical dos principais temas e notas musicais que seu ídolo canta e toca! 
<p>Let´s sing!

____

### Serviços utilizados pelo Music Bot

O Music Bot utiliza a API do Vagalume para buscar informações sobre bandas e músicas. Vagalume é um site Brasileiro que possui um catálogo de artistas e músicas nacionais e internacionais. Você pode consultar mais informações em www.vagalume.com.br. O site Cifra Club (https://www.cifraclub.com.br/) também é utilizado pelo Music Bot para busca de notas musicais. 

### Instalação das bibliotecas python

Para executar o Music Box na sua máquina, você precisará do anaconda 3 instalado. Este tutorial foi testado com **jupyter labs** (e não jupyter notebook), por gentileza, utilize o mesmo aplicativo para evitar problemas de configuração.

Acesse o site https://www.anaconda.com/, faça download do anaconda e instale o programa na sua máquina. O anaconda já possui quase todas as bibliotecas que precisamos para executar o Music Bot, mas ainda temos que instalar alguns pacotes. 

<p>Já com o anaconda instalado no seu computador, acesse o terminal do seu conda environment e execute os seguintes comandos:
  
- conda install -c conda-forge nodejs

- conda install -c conda-forge wordcloud

- jupyter labextension install @jupyter-widgets/jupyterlab-manager

### Criando uma API Key no site do Vagalume
Você precisa de uma API Key do Vagalume para conseguir buscar as letras de músicas do seu artista. Siga os seguintes passos para criar sua API Key.

- Acesse o site https://auth.vagalume.com.br/
- Clique no botão "Cadastre-se"
- Clique no botão "Pessoa"
- Escolha uma das opções de cadastro e insira seus dados
- Na sequência, você receberá um email de confirmação para ativar sua API Key. Acesse sua caixa de e-mails e ative sua API Key

### Inserindo sua API Key no notebook
Ao abrir o notebook do Music Bot na sua máquina utilizando o **jupyter labs**, identifique a seção com o título **Define uma API Key** e substitua o texto "cole_aqui_sua_api_key" pela sua API Key em questão.

