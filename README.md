# Assistente Virtual com Áudio, Whisper e ChatGPT 🎤🧠💬🔊

Este repositório contém um protótipo de assistente virtual desenvolvido como parte do desafio do Bootcamp Santander Gen AI & Dados. O projeto integra captura de áudio, reconhecimento de fala, processamento de linguagem natural com ChatGPT e síntese de voz.

----

## 🚀 Funcionalidades


* Gravação de Áudio com Python e JavaScript

Utiliza a API MediaStream Recording via JavaScript para capturar áudio do usuário.

O áudio é processado e salvo em formato .wav no Google Colab.



* Reconhecimento de Fala com Whisper (OpenAI)

Transcreve o áudio gravado para texto.

Suporte a múltiplos idiomas.

Modelo utilizado: small.



* Integração com a API do ChatGPT (OpenAI)

Envia a transcrição para o modelo GPT-4.

Recebe uma resposta contextualizada e inteligente.

Necessário configurar a variável de ambiente OPENAI_API_KEY.



* Síntese de Voz com gTTS (Google Text-to-Speech)

Converte a resposta do ChatGPT em áudio.

Reproduz a resposta sintetizada diretamente no Colab.


----

## 📂 Estrutura do Projeto

├── gravação_audio.py  
├── reconhecimento_whisper.py  
├── integração_chatgpt.py  
├── síntese_resposta.py  
└── README.md  

----

## 🔧 Instalação
- Clone este repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

- Instale as dependências:
pip install git+https://github.com/openai/whisper.git
pip install openai
y pip install gTTS

----

## ⚙️ Configuração

Crie uma conta na OpenAI.

Gere sua API Key em API Keys.

Configure a variável de ambiente:

import os
os.environ['OPENAI_API_KEY'] = 'SUA_API_KEY_AQUI'

----

## ▶️ Execução

Execute o script de gravação de áudio.

Transcreva o áudio com Whisper.

Envie a transcrição para o ChatGPT.

Ouça a resposta sintetizada com gTTS.

----

## 📖 Referências

Whisper - OpenAI

API OpenAI

gTTS - Google Text-to-Speech

MediaStream Recording API

____
👨‍💻 Desenvolvido como parte do Bootcamp Santander Gen AI & Dados em 2026.
