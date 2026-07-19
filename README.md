# Analisador de código com IA

Uma aplicação web moderna, desenvolvida com React e Vite, projetada para auxiliar desenvolvedores na revisão de código. O analisador utiliza a API do Google Gemini para identificar problemas, sugerir melhorias de performance e aplicar boas práticas de desenvolvimento de forma rápida e didática.

## 🚀 Funcionalidades

- **Análise Instantânea:** Cole qualquer trecho de código e receba uma análise imediata.
- **Sugestões Didáticas:** Foco em clareza, legibilidade e manutenibilidade.
- **Insights Técnicos:** Identificação de potenciais bugs, melhorias de performance e refatoração baseada em boas práticas.
- **Formatação Clara:** As respostas da IA são formatadas em Markdown para facilitar a leitura.

## 🛠 Tecnologias

- **Frontend:** React, Vite
- **IA:** Google Generative AI (@google/generative-ai, modelo `gemini-1.5-flash`)
- **Linguagem:** JavaScript

## 📦 Como rodar o projeto

### Pré-requisitos

- Node.js instalado (versão >= 18)
- Uma API Key do Google Gemini (obtenha em [Google AI Studio](https://aistudio.google.com/))

### Passos

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd analisador-de-codigo-com-ia
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Configure as variáveis de ambiente:**
   Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API:
   ```env
   VITE_GEMINI_API_KEY=sua_chave_aqui
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```

5. Acesse `http://localhost:5173` no seu navegador.

## 📂 Estrutura do Projeto

```text
/
├── src/
│   ├── assets/        # Recursos estáticos
│   ├── services/      # Integração com Gemini API
│   ├── App.jsx        # Componente principal
│   ├── App.css        # Estilos da aplicação
│   └── main.jsx       # Ponto de entrada React
├── .env               # Variáveis de ambiente (não versionado)
├── package.json       # Dependências e scripts
└── vite.config.js     # Configuração do Vite
```

## 📝 Licença

Este projeto está sob a licença MIT.
