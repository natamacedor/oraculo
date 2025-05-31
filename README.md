# 🤖 Oráculo - Chat Interativo com Dados

O Oráculo é uma aplicação web interativa que permite conversar com diferentes tipos de dados através de uma interface amigável. Desenvolvido inicialmente como um projeto educacional, o Oráculo permite que você interaja com vídeos do YouTube, sites, arquivos PDF, CSV e TXT, utilizando diferentes modelos de linguagem para processar e responder suas perguntas.

## ✨ Funcionalidades

- **Múltiplos Formatos de Dados**:
  - Sites web
  - Vídeos do YouTube
  - Arquivos PDF
  - Arquivos CSV
  - Arquivos TXT

- **Provedores de Modelos de Linguagem**:
  - Groq (gratuito)
    - llama-3.1-70b-versatile
    - gemma2-9b-it
    - mixtral-8x7b-32768
  - OpenAI (pago)
    - gpt-4o-mini
    - gpt-4o
    - o1-preview
    - o1-mini

- **Interface Amigável**:
  - Sidebar para configuração
  - Chat interativo
  - Histórico de conversas
  - Upload de arquivos
  - Seleção de modelos

## 🚀 Como Começar

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/oraculo.git
cd oraculo
```

2. Crie e ative um ambiente virtual:
```bash
python -m venv .venv
# No Windows
.venv\Scripts\activate
# No Linux/Mac
source .venv/bin/activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

### Configuração

1. Obtenha as chaves de API necessárias:
   - Para Groq: [Registre-se em Groq](https://console.groq.com)
   - Para OpenAI: [Registre-se em OpenAI](https://platform.openai.com)

2. Inicie a aplicação:
```bash
streamlit run app.py
```

## 💻 Como Usar

1. **Seleção de Dados**:
   - Escolha o tipo de arquivo que deseja analisar
   - Faça upload do arquivo ou insira a URL (para sites e vídeos)

2. **Configuração do Modelo**:
   - Selecione o provedor (Groq ou OpenAI)
   - Escolha o modelo desejado
   - Insira sua chave de API

3. **Iniciar Conversa**:
   - Clique em "Inicializar Oráculo"
   - Comece a fazer perguntas sobre o conteúdo carregado

4. **Gerenciamento de Conversa**:
   - Use o botão "Apagar Histórico de Conversa" para iniciar uma nova conversa
   - O histórico é mantido durante a sessão

## 🛠️ Tecnologias Utilizadas

- **Streamlit**: Framework para interface web
- **LangChain**: Framework para processamento de linguagem natural
- **Document Loaders**: Para carregamento de diferentes tipos de arquivos
- **Chat Models**: Integração com diferentes provedores de LLMs

## 📚 Aprendizados

Este projeto demonstra:
- Configuração de ambiente de desenvolvimento
- Desenvolvimento de WebApp com Streamlit
- Integração com LangChain
- Uso de Document Loaders
- Construção de chains de conversação
- Manipulação de diferentes tipos de dados

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.