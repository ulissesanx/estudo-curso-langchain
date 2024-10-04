# Curso LangChain - Iniciantes

Bem-vindo ao repositório do Curso LangChain para Iniciantes! Aqui você encontrará todos os exemplos de código necessários para acompanhar o curso e aprender sobre LangChain do zero. Ao final do curso, você será capaz de criar seus próprios aplicativos com LLM integrado, construir chatbots RAG e automatizar tarefas com IA.

## Conteúdo do Curso

1. **Configuração do Ambiente**
2. **Conceito sobre o LangChain**
3. \*\*Unidade de trabalho LangChain \*\***`Runnable`**
4. **Chat Models**
5. **Prompt Templates**
6. **Analisadores de Saída**
7. **Chains**
8. **Carregadores (Document Loaders)**
9. **Memória**
10. **Chatbot**
11. **RAG (Retrieval-Augmented Generation)**
    - Splitters
    - Embedding
    - Bases Vetoriais
    - Recuperadores (Retriever)

## Começando

### Pré-requisitos

- Python  3.11 ou superior.
- Criar um ambiente virtual e clonar o repositório
- Instalar as dependências  presentes no arquivo requirements.txt

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/gustavo-sacchi/curso-langchain.git
   ```

2. Instale as dependências usando o UV:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure as variáveis de ambiente:

   - Renomeie o arquivo `.env.example` para `.env` e atualize as variáveis com seus valores. Exemplo:

   ```bash
   mv .env.example .env
   ```

5) Execute os exemplos de código via interface ou via terminal, conforme sua preferencia.

## Estrutura do Repositório

Veja o que você encontrará em cada pasta:

### 1. Chat Models

- Exemplos de como interagir com modelos de linguagem como ChatGPT e Claude utilizando o componente `Models` do LangChain.

### 2. Prompt Templates

- Exemplos que explicam os conceitos básicos dos tipos de templates que o langchain oferece e como usá-los.

### 3. Analisadores de Saída

- Demonstraremos os tipos mais importantes dos analisadores de saída (textual e estruturada).

### 4. Chains

- Como criar cadeias usando modelos de chat, prompts e outros componentes para criar integrações e aplicações que usam LLM.

### 5. Carregadores (Document Loaders)

- Como carregar documentos de diferentes fontes para utilizar nos seus projetos.

### 6. Memória

- Exploração dos conceitos de memória para interações prolongadas com modelos.

### 7. Chatbot

- Construindo um chatbot interativo usando LangChain.

### 8. RAG (Retrieval-Augmented Generation)

- Conceitos como Splitters, Embedding, Bases Vetoriais e Recuperadores.

## Como Utilizar Este Repositório

1. **Acompanhe o Curso:** Inicie assistindo às aulas do curso LangChain no canal do Youtube.
2. **Execute os Exemplos:** Siga junto com os exemplos de código fornecidos neste repositório. Cada módulo do curso corresponde a uma pasta neste repositório.
3. **Estude**, sempre que possivel, para manter fresco o assunto na sua cabeça, tente criar variações do que estamos ensinando e compartilhe conosco.
4. **Participe da Comunidade:** Caso tenha dúvidas ou queira trocar experiências com outros desenvolvedores, junte-se à comunidade.

## Documentação Completa

Cada script neste repositório contém comentários detalhados explicando o propósito e a funcionalidade do código. Isso ajudará você a entender o fluxo e a lógica por trás de cada exemplo.

## FAQ

**Q: O que é LangChain?**\
A: LangChain é um framework que simplifica o processo de criação de aplicações que utilizam modelos de linguagem.

**Q: Como configuro meu ambiente?**\
A: Siga as instruções na seção "Começando" acima. Certifique-se de ter o Python  3.11 ou superior instalado, clone o repositório, instale as dependências, renomeie o arquivo `.env.example` , ative o ambiente virtual e execute os scripts desejado.

**Q: Estou tendo problemas ao executar os exemplos, o que faço?**\
A: Verifique se todas as dependências foram instaladas corretamente e se as variáveis de ambiente estão configuradas. Se o problema persistir, mande uma mensagem para mim na comunidade do Discord ou do WhatsApp que podemos te ajudar.

