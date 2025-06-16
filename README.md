# Curso LangChain - Iniciantes

Bem-vindo ao meu repositório do Curso LangChain para Iniciantes! Aqui você encontrará, além de todos os exemplos de código necessários para acompanhar o curso e aprender sobre LangChain do zero - Os meus códigos e projetos desenvolvidos durante o estudo do curso de LangChain do zero!

---

## 📚 Base do Curso

Este repositório é baseado no curso:

**Título:** [Curso Completo de LangChain para Iniciantes]([https://link-do-curso.com](https://youtu.be/D3oQBfeB23U?si=kJsKD0uh0hQWxZNE))  
**Autor:** @gustavo-sacchi

---

### 🛡️ Aviso de Ética e Uso

> Este repositório **não é uma cópia nem redistribuição** do conteúdo original do curso.  
>  
> O objetivo é **documentar meu aprendizado de forma pessoal e aberta**, respeitando os direitos autorais e incentivando o estudo colaborativo.  

---

## Conteúdo do Curso

1. **Apresentação do curso** - [Clique aqui e acesse o video do youtube](https://youtu.be/mAa9lnK3HQw)
2. **Configuração do Ambiente** - [Clique aqui e acesse o video do youtube](https://youtu.be/D3oQBfeB23U)
3. **Conceito sobre o LangChain** - [Clique aqui e acesse o video do youtube](https://youtu.be/fNspLmXqm1Q)
4. **Unidade de trabalho LangChain** **`Runnable`** - [Clique aqui e acesse o video do youtube](https://youtu.be/zlas_BXp9nc?si=bHxZDgEhAX9iNiPe)
5. **Chat Models** - [Clique aqui e acesse o video do youtube](https://youtu.be/lfYzOlJCAlo?si=tRPaOK3J8p5jFEY1)
6. **Prompt Templates** - [Clique aqui e acesse o video do youtube](https://youtu.be/lfYzOlJCAlo?si=53uF6FfKTD5JFMzq)
7. **Analisadores de Saída** - [Clique aqui e acesse o video do youtube](https://youtu.be/VQl1V2z0X8o)
8. **Chains - Parte 1** - [Clique aqui e acesse o video do youtube](https://youtu.be/RuxyWgRRDGE?si=cbgJiTqYUxz2onPH)
9. **Chains - Parte 2** - [Clique aqui e acesse o video do youtube](https://youtu.be/E36XcPahzTc?si=uFBx7W8UfE-Y-ec3)
10. **Carregadores (Document Loaders)** - [Clique aqui e acesse o video do youtube](https://youtu.be/DC31BICQFEI)
11. **Memória** - [Clique aqui e acesse o video do youtube](https://youtu.be/uZC34c6DXcI)
12. **Chatbot** - [Clique aqui e acesse o video do youtube](https://youtu.be/2Ama0t2evHM)
13. **RAG (Retrieval-Augmented Generation) - Conceito**  - [Clique aqui e acesse o video do youtube](https://youtu.be/f2IUNYCF-G0)
    - Splitters - [Clique aqui e acesse o video do youtube](https://youtu.be/h1urQIW9UTk)
    - Embedding - [Clique aqui e acesse o video do youtube](https://youtu.be/2TRe7K49X94)
    - Bases Vetoriais - [Clique aqui e acesse o video do youtube](https://youtu.be/xzmk1I73YnA)
    - Recuperadores (Retriever) - [Clique aqui e acesse o video do youtube](https://youtu.be/38wlRpU_T5c)
14. **Chatbot com RAG** - [Clique aqui e acesse o video do youtube](https://youtu.be/4Apq46ruzLc)

Extras:
- Como Criar Seu Próprio ChatGPT com Memória em Menos de 20 Linhas de Python usando LangChain - [Clique aqui e acesse o video do youtube](https://youtu.be/SR4K7Tzc9NA?si=BSNcM0TgXx3-IFJl)
- Como Utilizar APIs Gratuitas para fazer o curso da LangChain - [Clique aqui e acesse o video do youtube](https://youtu.be/tGAiSM45kVY)
- Ollama - Como utilizar modelos rodando localmente integrados ao LangChain - [Clique aqui e acesse o video do youtube](https://youtu.be/LO71JhU_mK0)
- Como usar o PostgreSQL para armazenamento de memória - Em Breve!
- Como conectar seu chatbot ao whatsapp usando EvolutionAPI - Em Breve!

## Mantenha seu repositório sempre atualizado
- Pessoal, como eu estou construindo este tutorial conforme me sobra um tempo livre algumas notas de estudo ou código serão atualizados ao longo do tempo, alguns arquivos serão atualizados constantemente. Dessa forma, eu recomendo que você sempre realize um update dos arquivos do repositório para a ultima versão.
- Qualquer alteração eu informarei durante a video aula.
- Qualquer dúvida eu erro que vocês tiverem, não deixe de compartilhar para que eu ou alguém da comunidade possa te auxiliar.
- Os arquivos que poderão ser atualizados com recorrência são:`.env.exemplo` , `requirements.txt` .

## Começando

### Pré-requisitos

- Python  3.11 ou superior.
- Criar um ambiente virtual e clonar o repositório
- Instalar as dependências  presentes no arquivo requirements.txt

### Instalação

1. Clone o repositório:

   ```
   git clone https://github.com/gustavo-sacchi/curso-langchain.git
   ```

2. Instale as dependências:

   ```
   pip install -r requirements.txt
   ```
**Atenção**: Se por acaso o comando de instalação das dependências acima não funciuonar, tente executar a instalação via terminal pip:

``` 
pip install langchain-openai langchain langchain-core langchain-community langchain-experimental python-dotenv SQLAlchemy
```
    

3. Configure as variáveis de ambiente:

   - Renomeie o arquivo `.env.example` para `.env` e atualize as variáveis com seus valores. Exemplo:

   ```
   mv .env.example .env
   ```

5) Crie o ambiente virtual: 

    ```
    python -m venv venv
    ```

6) Execute os exemplos de código via interface ou via terminal, conforme sua preferência.

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

## Participe da comunidade

> Comunidade no Discord: [Participe Clicando Aqui](https://discord.gg/4uTa2YSwAB)

> Comunidade no Whatsapp: [Participe Clicando Aqui](https://chat.whatsapp.com/Fj7dzuUx4TNJBPmNrBkolO)

- Conto com vocês para construirmos uma comunidade bastante cooperativa, então não deixe de compartilhar ideias, erros, sugestões, elogios etc.
- Sempre ajude o próximo! Quando você ensina você aprende duas vezes.
- Erros podem acontecer então compartilhe e se você souver resolver fique a vontade para compartilhar a solução.


## FAQ

**Q: O que é LangChain?**\
A: LangChain é um framework que simplifica o processo de criação de aplicações que utilizam modelos de linguagem.

**Q: Como configuro meu ambiente?**\
A: Siga as instruções na seção "Começando" acima. Certifique-se de ter o Python  3.11 ou superior instalado, clone o repositório, instale as dependências, renomeie o arquivo `.env.example` , ative o ambiente virtual e execute os scripts desejado.

**Q: Estou tendo problemas ao executar os exemplos, o que faço?**\
A: Verifique se todas as dependências foram instaladas corretamente e se as variáveis de ambiente estão configuradas. Se o problema persistir, mande uma mensagem para mim na comunidade do Discord ou do WhatsApp que podemos te ajudar.

