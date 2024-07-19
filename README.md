## Objetivo do Teste

O objetivo deste teste é avaliar a sua habilidade de criar uma aplicação para um sistema de Recuperação Aumentada de Conhecimento (RAG) utilizando as seguintes tecnologias:

1. **LangChain**: Framework para construção de aplicações com base em IA.
2. **ChromaDB**: Banco de dados para armazenamento de vetores.
3. **Ollama**: Modelo de linguagem para processamento de textos.
4. **Docker e Docker Compose**: Para configuração e orquestração do ambiente de desenvolvimento.

## Requisitos do Teste

1. **Leitura do PDF**:
    - Faça o download do PDF da Política de Privacidade da empresa: [Politica_de_Privacidade.pdf](https://softstar.s3.amazonaws.com/documents/Politica_de_Privacidade.pdf)
    - Utilize uma biblioteca de sua escolha para ler e extrair o texto do PDF.

2. **Processamento do Texto**:
    - Use LangChain para processar o texto extraído.
    - Treine o modelo Ollama com o texto da Política de Privacidade.

3. **Armazenamento de Dados**:
    - Configure ChromaDB para armazenar os vetores resultantes do processamento do texto.
    - Garanta que os dados possam ser recuperados e consultados posteriormente.

4. **Uso de Docker e Docker Compose**:
    - Configure o ambiente de desenvolvimento utilizando Docker e Docker Compose.
    - Crie um arquivo `Dockerfile` para a aplicação.
    - Crie um arquivo `docker-compose.yml` para orquestrar os serviços necessários (LangChain, ChromaDB, Ollama).

## Critérios de Avaliação

1. **Funcionalidade**: A aplicação deve ser capaz de ler o PDF, processar o texto, treinar o modelo Ollama e armazenar os dados no ChromaDB.
2. **Integração com LangChain**: O uso do LangChain para processamento do texto deve ser eficiente e bem estruturado.
3. **Armazenamento e Recuperação de Dados**: A integração com o ChromaDB deve permitir o armazenamento e recuperação eficiente dos vetores.
4. **Configuração com Docker**: A configuração do ambiente de desenvolvimento utilizando Docker e Docker Compose deve ser clara e funcional.
5. **Código Limpo**: O código deve ser limpo, seguindo boas práticas de desenvolvimento.

## Passos para Realizar o Teste

1. **Configurar o Ambiente**:
    - Utilize Docker e Docker Compose para configurar e iniciar a aplicação.
    - Crie um arquivo `Dockerfile` para a aplicação.
    - Crie um arquivo `docker-compose.yml` para orquestrar os serviços necessários.
    - Configure as variáveis de ambiente necessárias.

2. **Leitura do PDF**:
    - Implemente a funcionalidade para baixar e ler o PDF da Política de Privacidade.
    - Extraia o texto do PDF.

3. **Processar o Texto com LangChain**:
    - Use LangChain para processar o texto extraído do PDF.
    - Treine o modelo Ollama com o texto processado.

4. **Armazenar Dados no ChromaDB**:
    - Configure ChromaDB para armazenar os vetores resultantes do processamento do texto.
    - Implemente a funcionalidade para recuperar e consultar os dados armazenados.

## Deploy da Aplicação

1. **Deploy em um Serviço de Hospedagem** (Opcional):
    - Faça o deploy da aplicação em um serviço de hospedagem de sua escolha (AWS NVIDIA Tesla Instance).
    - Garanta que a aplicação esteja acessível publicamente.

2. **Incluir Instruções de Deploy** (Opcional):
    - Adicione ao repositório um arquivo `DEPLOY.md` com instruções detalhadas de como fazer o deploy da aplicação.

## Conclusão

Este teste técnico é projetado para avaliar suas habilidades em criar uma aplicação de Recuperação Aumentada de Conhecimento (RAG) usando LangChain, ChromaDB, Ollama e Docker. Ao seguir os requisitos e critérios de avaliação, você poderá demonstrar sua capacidade de trabalhar com essas tecnologias e criar uma aplicação de alta qualidade.

**Após concluir o teste, entre em contato com o recrutador e envie os links do repositório e do deploy da aplicação (se aplicável).**
