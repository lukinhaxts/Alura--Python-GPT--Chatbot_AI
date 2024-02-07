# OpenAI: Curso 2

## ⚙️ Configuração do Ambiente

### Criando e Ativando o Ambiente Virtual

**Windows - Anaconda:**
```bash
conda create chatbot python
```

**Windows - Python Nativo:**
```bash
python -m venv chatbot
```

**Mac/Linux:**
```bash
python3 -m venv chatbot
```

### Instalando bibliotecas necessárias

**Windows - Anaconda:**
```bash
conda activate chatbot
pip install requirements.txt
```

**Windows - Python Nativo:**
```bash
chatbot\Scripts\activate
pip install requirements.txt
```

**Mac/Linux:**
```bash
source chatbot/bin/activate
pip install requirements.txt
```

### Inserindo sua API Key

Após criar sua API Key na plataforma da OpenAI, criar um arquivo chamado ```.env```, e inserir sua key no seguinte formato:

```
OPENAI_API_KEY = "INSIRA SUA KEY"
```

## 📚 Referências de Leitura

- [Documentação Whisper](https://openai.com/research/whisper)
- [Documentação Dall-E](https://openai.com/research/dall-e)
- [Preços OpenAI](https://openai.com/pricing)
- [Áudios Longos](https://platform.openai.com/docs/guides/speech-to-text/prompting)
