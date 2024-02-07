# Python e GPT: crie seu chatbot com IA (Implementação de curso da Alura)

## ⚙️ Configuração do Ambiente

### Criando o Ambiente Virtual e Instalando Bibliotecas Necessárias

**Windows - Anaconda:**
```bash
conda activate base
conda create -p "./chatbot" python
conda activate "./chatbot"
pip install -r requirements.txt
```

**Windows - Python Nativo:**
```bash
python -m venv chatbot
chatbot\Scripts\activate
pip install requirements.txt
```

## Inserindo sua API Key

Após criar sua _API Key_ na plataforma da OpenAI, crie um arquivo chamado ```.env``` na pasta raíz e insira sua _key_ no seguinte formato:

```
OPENAI_API_KEY = "INSIRA SUA KEY"
```

## 📚 Referências de Leitura

- [Documentação Whisper](https://openai.com/research/whisper)
- [Documentação Dall-E](https://openai.com/research/dall-e)
- [Preços OpenAI](https://openai.com/pricing)
- [Áudios Longos](https://platform.openai.com/docs/guides/speech-to-text/prompting)
