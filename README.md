# 📄 Chatbot com RAG usando PDFs e LLMs

## 💡 Visão Geral

Este projeto foi desenvolvido como parte dos estudos do curso [Desenvolvimento de Agentes de IA: Do Zero ao Avançado](https://www.udemy.com/course/desenvolvimento-de-agentes-de-ia-do-zero-ao-avancado) na Udemy, ministrado por Rodrigo Macedo e Paulo Andrade, PhD.

O objetivo é construir um chatbot inteligente que utiliza a técnica de **RAG (Retrieval-Augmented Generation)** para responder perguntas com base em documentos PDF. O sistema combina **LlamaIndex**, **LangChain** e **LLMs** para realizar buscas semânticas e gerar respostas contextualizadas.

---

## 🧠 Conceitos Aplicados

- **RAG (Retrieval-Augmented Generation)**: Técnica que combina recuperação de dados com geração de texto por LLMs.
- **LlamaIndex**: Framework para indexação e consulta de documentos.
- **LangChain**: Integração de ferramentas, memória e raciocínio com LLMs.
- **Streamlit**: Interface web para interação com o chatbot.
- **Embeddings**: Representações vetoriais dos textos para busca semântica.

---

## 🛠️ Tecnologias Utilizadas

- `Python`  
- `LlamaIndex`  
- `LangChain`  
- `OpenAI API`  
- `Streamlit`  
- `dotenv`  
- `PyMuPDF` ou `pdfplumber` (para leitura de PDFs)

---

## 🚀 Primeiros Passos

### ✅ Pré-requisitos
- Python 3.12+
- pip
- Chave de API (OpenAI ou outro provedor LLM)

### 📦 Instalação e Ambiente Virtual

```bash
python3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

>_Configure o arquivo .env com sua chave de API:_
```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```

### ▶️ Executando o Projeto

Para iniciar a interface web:
```Bash
streamlit run .\app.py
```

Isso abrirá uma aba no navegador com o chatbot pronto para receber perguntas baseadas nos PDFs carregados.


## 📁 Estrutura do Projeto
```
chatBotPdfRag/
├── app.py                # Interface Streamlit
├── pdfs/                 # Pasta com documentos PDF
├── index/                # Arquivos de indexação
├── .env                  # Chave de API
├── requirements.txt      # Dependências
└── README.md             # Documentação
```


## 📚 Aprendizados
- Criação de chatbots com base em documentos reais
- Indexação e consulta semântica com LlamaIndex
- Integração de LLMs com fluxos de busca e geração
- Construção de interfaces interativas com Streamlit
- Aplicação prática de RAG em projetos de IA

## 👩‍💻 Autora

Aline Assunção

Engenheira de Qualidade em transição para Inteligência Artificial

📫 [LinkedIn](https://www.linkedin.com/in/alineassuncaoai/)  

📬 aline.jassuncao@gmail.com


>_"Quando a IA encontra seus documentos, ela transforma informação em respostas inteligentes."_















