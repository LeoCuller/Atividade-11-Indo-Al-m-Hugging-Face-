🤖 LLM Agent — Protótipo de Agente de Linguagem com HuggingFace

Este projeto implementa um Agente LLM utilizando o modelo GPT-2 através da biblioteca HuggingFace Transformers. O objetivo é demonstrar como carregar um modelo de linguagem, gerar textos e estruturar um agente capaz de interpretar e executar tarefas simples.

Todo o desenvolvimento foi realizado em um notebook Jupyter (.ipynb), facilitando a visualização e execução passo a passo.

🚀 Começando

Siga as instruções abaixo para configurar o ambiente e rodar o projeto localmente.

📦 Pré-requisitos

Você precisará ter:

Python 3.8+

Ambiente virtual recomendado (venv)

Pacotes: transformers, torch, huggingface-hub, ipykernel

🔧 Criar e ativar o ambiente virtual
python -m venv venv

# Windows
.\venv\Scripts\activate

📥 Instalar dependências
pip install transformers torch huggingface-hub ipykernel

🔑 Autenticação no Hugging Face

Alguns modelos exigem autenticação no Hugging Face Hub.
O GPT-2 é público, mas recomenda-se autenticar caso utilize outros modelos.

Gere seu token em: https://huggingface.co/settings/tokens

No terminal, execute:

huggingface-cli login


Ou com o novo comando:

hf auth login


Cole o token quando solicitado.

⚙️ Executando o Projeto

Este repositório contém um notebook principal:

📄 LLM_Agents_Notebook_Completo.ipynb

Para rodar:

jupyter notebook

🧠 O que o Agente Faz

Carrega o modelo GPT-2 via HuggingFace Transformers

Gera respostas com base em prompts fornecidos

Demonstra lógica básica de um LLM Agent

Apresenta exemplos de geração de texto e análises simples

Explora a integração entre Python, HuggingFace e LLMs

🏫 Informações Acadêmicas

Este projeto foi desenvolvido como parte da disciplina:

Inteligência Artificial e Computacional — USCS
Professor: Fábio Rezende de Souza
Alunos:

Leonardo Moraes Culler - https://github.com/LeoCuller?tab=repositories

Stefano Moretti - https://github.com/stefanomrtt?tab=repositories

Alessandro Ciosani - https://github.com/Alezito53?tab=repositories

Wendell Amorim -  https://github.com/wendellamorim-del?tab=repositories 
