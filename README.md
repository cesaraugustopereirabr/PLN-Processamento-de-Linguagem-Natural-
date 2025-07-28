# 🎙️ Reconhecimento de Voz via Upload de Áudio no Google Colab

Este projeto tem como objetivo realizar o **reconhecimento automático de fala (ASR)** a partir de um arquivo de áudio enviado pelo usuário. Ele permite que o usuário envie arquivos em diversos formatos (`.mp3`, `.wav`, `.ogg`, etc.), realiza a conversão automática para o formato `.wav`, e depois transcreve o conteúdo falado utilizando a API do Google via `speech_recognition`.

> 🔧 Desenvolvido para rodar diretamente no [Google Colab](https://colab.research.google.com/), sem necessidade de configurações locais complexas.

---

## 🛠️ Tecnologias utilizadas

- [Google Colab](https://colab.research.google.com/)
- [`speech_recognition`](https://pypi.org/project/SpeechRecognition/)
- [`pydub`](https://github.com/jiaaro/pydub) (para conversão de áudio)
- [`ffmpeg`](https://ffmpeg.org/) (backend para manipulação de áudio)
- Python 3.11+

---

## 🚀 Funcionalidades

- Upload de arquivos de áudio no Colab
- Conversão automática de `.mp3`, `.ogg` e outros para `.wav`
- Reprodução do áudio no notebook
- Transcrição de fala (speech-to-text)
- Suporte ao idioma português (`pt-BR`)

---

## 📦 Instalação de dependências

O primeiro bloco de código instala todas as bibliotecas necessárias:

```python
!pip install pydub speechrecognition ffmpeg-python --quiet
