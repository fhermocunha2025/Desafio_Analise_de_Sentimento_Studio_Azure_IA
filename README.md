# Introdução

Este resumo tenta detalhar minha experiência assistindo as aulas em vídeo das aulas sobre IA Generativas e Studio Azure IA.

É importante citar que não consegui fazer minha conta empresa para poder práticar.

# **O que é inteligência artificial?**
É a tentativa de fazer máquinas pensarem e agirem como humanos. Abrange um monte de coisa.

# Fundamento de IA Generativa

**Conceitos Básicos de IA Generativa:** Aqui a gente começa a entender a parada da IA que cria coisas novas, tipo um "agente" que o curso vai usar pra explicar como essa mágica acontece.

**O que é uma IA Generativa:** Basicamente, é uma IA que não só analisa dados, mas também *gera* dados que parecem reais. Pensa em criar imagens, textos, músicas... É tipo dar um "brainstorm" pro computador e ele te entrega várias opções.

**Modelos de Linguagem Grandes (LLMs):** Essa é a espinha dorsal da IA generativa pra texto. São modelos gigantescos treinados com quantidades absurdas de texto pra entender e gerar linguagem humana de forma impressionante.

**Modelos de Linguagem Grandes: Transformador:** Uma arquitetura de rede neural chave por trás dos LLMs. A sacada principal é o mecanismo de "atenção" (a gente já chega lá), que permite ao modelo entender as relações entre as palavras em uma frase, mesmo que estejam distantes. É o que deu um salto de qualidade nos LLMs.

**Modelos de Linguagem Grandes: Tokenização:** Antes de um LLM processar texto, ele precisa ser "quebrado" em pedacinhos menores chamados "tokens". Podem ser palavras inteiras, partes de palavras ou até caracteres. A tokenização é crucial pra IA entender e manipular a linguagem.

**Modelos de Linguagem Grandes: Inserções (Embeddings):** Cada token é transformado em um vetor numérico (uma lista de números) chamado "embedding". Esse vetor representa o significado da palavra no espaço semântico. Palavras com significados parecidos vão ter vetores próximos. É como a IA entende a "vibe" de cada palavra.

**Modelos de Linguagem Grandes: Atenção (Attention):** Esse é o pulo do gato da arquitetura Transformer. O mecanismo de atenção permite que o modelo foque nas partes mais importantes da sequência de entrada ao gerar a saída. Por exemplo, ao traduzir uma frase, ele "presta atenção" nas palavras relevantes para gerar a tradução correta.

**Conceitos Básicos de IA Generativa – Copilotos e Engenharia de Prompts:** Aqui a gente começa a ver como *usar* a IA generativa. "Copilotos" são ferramentas que usam IA pra nos ajudar em tarefas (tipo escrever código ou texto). "Engenharia de prompts" é a arte de criar as perguntas (os "prompts") certas pra IA generativa nos dar as respostas ou criações que a gente quer.


# Conceitos Fundamentais de IA

**Sobre as Cargas de Trabalho Comuns de IA**, podemos colocar:

* **Machine learning:** Uma das principais áreas da IA. É sobre ensinar máquinas a aprenderem com dados, sem precisar programar cada passo explicitamente. Elas encontram padrões sozinhas.

* **Visão Computacional:** Fazer as máquinas "enxergarem" e interpretarem imagens e vídeos. Reconhecimento de objetos, detecção de rostos, essas paradas.

* **Processamento de linguagem natural:** Já vimos um pouco, mas aqui reforça que é a área da IA que lida com a compreensão e geração de linguagem humana.

* **Inteligência de documentos:** Usar IA pra entender e extrair informações de documentos (PDFs, Word, etc.). Tipo achar dados importantes em um contrato gigante.

* **Mineração de conhecimento:** Descobrir padrões, informações e insights úteis em grandes volumes de dados. É como garimpar ouro em um oceano de dados.

* **IA Generativa:** De novo ela! Mas aqui é pra mostrar que a geração de conteúdo é uma das "tarefas" que a IA consegue fazer.

* **Imparcialidade (Fairness):** Um ponto super importante. Garantir que os sistemas de IA não sejam tendenciosos e não discriminem certos grupos de pessoas.

* **Confiabilidade e segurança:** Fazer com que os sistemas de IA funcionem de forma consistente e segura, sem falhas inesperadas ou vulnerabilidades.

* **Privacidade e segurança:** Lidar com dados de forma ética e segura, protegendo a privacidade dos usuários ao usar sistemas de IA.

* **Inclusão e transparência:** Desenvolver IA que funcione bem para todos os tipos de usuários e que seja transparente em como toma decisões (pelo menos tentar).

* **Responsabilidade:** Definir quem é responsável pelas ações de um sistema de IA, especialmente se algo der errado. Uma área ainda em debate.


# Fundamentos do Aprendizado de Máquina

**Tipos de aprendizado de máquina:**

As formas básicas de ensinar uma máquina:

* **Supervisionado:**
    * A gente dá exemplos com as respostas certas pra máquina aprender a fazer previsões.

* **Não Supervisionado:**
    * A máquina tenta encontrar padrões sozinha em dados sem rótulos.

* **Por Reforço:** 
    * A máquina aprende por tentativa e erro, recebendo recompensas ou punições por suas ações.

* **Treinamento e avaliação de modelo:**
    * O processo de "ensinar" a máquina usando dados de treinamento e depois verificar se ela aprendeu bem usando dados de avaliação (que ela nunca viu antes). Métricas são usadas pra medir o quão bom o modelo está.

* **Aprendizado profundo (Deep Learning):**
    * Uma subárea do machine learning que usa redes neurais com muitas camadas (as "profundas") pra aprender representações complexas dos dados. É o que tá por trás de muita coisa avançada hoje em dia.


# Conceitos de Processamento de Linguagem Natural

* **Conceitos de processamento de linguagem natural:**
    * Mais uma vez, a base do PLN: como fazer computadores entenderem e processarem a linguagem humana.

* **O que é processamento de linguagem natural?:**
    * Reforçando a definição e a importância de conseguir que máquinas "conversem" conosco.

* **Processamento de linguagem natural e IA conversacional no Azure - Análise de sentimentos e respostas a perguntas:** 
    * Como o Azure usa PLN pra entender se um texto é positivo, negativo ou neutro (análise de sentimentos) e pra criar sistemas que respondem a perguntas em linguagem natural.

* **Processamento de linguagem natural e IA conversacional no Azure - Fala:**
    * A parte do PLN que lida com a conversão de fala em texto (reconhecimento de voz) e de texto em fala (síntese de voz).

* **Processamento de linguagem natural e IA conversacional no Azure - Tradução:**
    * Usar PLN pra traduzir texto e fala entre diferentes idiomas.


# Trabalhando com serviços Azure OpenAI

**O que é OpenAI do Azure:**
* A plataforma da Microsoft que dá acesso aos modelos de linguagem super potentes da OpenAI (tipo o GPT).

**Como usar o OpenAI do Azure:**
* O passo a passo de como começar a usar esses serviços, provavelmente envolvendo APIs e chaves de acesso.

**Funcionalidade de linguagem natural do OpenAI do Azure:**
* As ferramentas e modelos específicos do Azure OpenAI focados em tarefas de PLN, como geração de texto, resumo, tradução, etc.



# Resumo Detalhado de IA - Perspectiva Acadêmica

## Fundamentos de IA Generativa

* **Conceitos Básicos de IA Generativa - Agente do Curso:** Introdução aos princípios fundamentais da IA generativa, estabelecendo um agente de aprendizado para a compreensão dos mecanismos subjacentes.

* **O que é uma IA Generativa:** Definição de Inteligência Artificial Generativa como um domínio da IA dedicado à síntese de novos dados com características estatísticas semelhantes aos dados de treinamento.

* **Modelos de Linguagem Grandes (LLMs):** Arquiteturas de redes neurais profundas, treinadas em extensos corpora textuais, capazes de modelar e gerar sequências de linguagem natural complexas.

* **Modelos de Linguagem Grandes: Transformador:** Arquitetura de rede neural que revolucionou o processamento de sequências, empregando mecanismos de autoatenção para capturar dependências contextuais de longo alcance na linguagem.

* **Modelos de Linguagem Grandes: Tokenização:** Processo de segmentação do texto de entrada em unidades discretas (tokens), que servem como a representação fundamental para o processamento pelos modelos de linguagem.

* **Modelos de Linguagem Grandes: Inserções (Embeddings):** Representações vetoriais densas de tokens, aprendidas durante o treinamento, que codificam as relações semânticas e sintáticas entre as palavras no espaço vetorial.

* **Modelos de Linguagem Grandes: Atenção (Attention):** Mecanismo neural que permite ao modelo ponderar a importância de diferentes partes da sequência de entrada ao gerar a saída, crucial para a modelagem contextual eficaz.

* **Conceitos Básicos de IA Generativa – Copilotos e Engenharia de Prompts:** Exploração das aplicações práticas da IA generativa através de copilotos (ferramentas assistivas baseadas em IA) e da disciplina da engenharia de prompts, focada na formulação eficaz de entradas para elicitar respostas desejadas dos modelos generativos.

## Conceitos Fundamentais de IA

* **Cargas de Trabalho Comuns de IA: O que é inteligência artificial:** Definição formal de Inteligência Artificial como o campo da ciência da computação dedicado à criação de sistemas capazes de realizar tarefas que, quando realizadas por humanos, exigem inteligência.

* **Carga de trabalho comuns de IA: Machine learning:** Ramo da IA que se concentra no desenvolvimento de algoritmos que permitem aos sistemas aprender a partir de dados, identificar padrões e tomar decisões com mínima intervenção humana explícita.

* **Carga de trabalho comuns de IA: Visão Computacional:** Campo da IA que capacita os sistemas a interpretar e compreender informações visuais do mundo, como imagens e vídeos.

* **Carga de trabalho comuns de IA: Processamento de linguagem natural:** Área da IA que se dedica à interação entre computadores e linguagem humana, permitindo que as máquinas compreendam, interpretem e gerem linguagem natural.

* **Carga de trabalho comuns de IA: Inteligência de documentos:** Aplicação de técnicas de IA para analisar, compreender e extrair informações relevantes de documentos textuais e visuais.

* **Carga de trabalho comuns de IA: Mineração de conhecimento:** Processo de descoberta de conhecimento útil e acionável a partir de grandes volumes de dados, utilizando métodos de IA e aprendizado de máquina.

* **Carga de trabalho comuns de IA: IA Generativa:** Reafirmação da IA generativa como uma modalidade de IA com foco na criação de conteúdo original, como texto, imagens e outros tipos de dados.

* **Carga de trabalho comuns de IA: Imparcialidade (Fairness):** Consideração crítica no desenvolvimento de IA, visando mitigar vieses e garantir que os sistemas não produzam resultados discriminatórios ou injustos para diferentes grupos.

* **Carga de trabalho comuns de IA: Confiabilidade e segurança:** Aspectos essenciais do desenvolvimento de IA, enfatizando a necessidade de sistemas robustos, resilientes e protegidos contra falhas e vulnerabilidades.

* **Carga de trabalho comuns de IA: Privacidade e segurança:** Imperativos éticos e técnicos no tratamento de dados em sistemas de IA, assegurando a proteção da informação pessoal e a integridade dos dados.

* **Carga de trabalho comuns de IA: Inclusão e transparência:** Princípios que guiam o desenvolvimento de IA para garantir que os sistemas sejam acessíveis e eficazes para uma ampla gama de usuários, com uma compreensão clara de seus processos de tomada de decisão.

* **Carga de trabalho comuns de IA: Responsabilidade:** Quadro ético e legal que define a atribuição de responsabilidade pelas ações e resultados gerados por sistemas de IA.

## Fundamentos do Aprendizado de Máquina

* **Tipos de aprendizado de máquina:** Classificação das metodologias de aprendizado em supervisionado (aprendizagem a partir de dados rotulados), não supervisionado (identificação de padrões em dados não rotulados) e por reforço (aprendizagem através da interação com um ambiente e maximização de recompensas).

* **Treinamento e avaliação de modelo:** Processo iterativo de ajuste dos parâmetros de um modelo de aprendizado de máquina utilizando dados de treinamento e subsequente avaliação do desempenho em dados independentes para verificar a generalização.

* **Aprendizado profundo (Deep Learning):** Subcampo do aprendizado de máquina que emprega redes neurais artificiais com múltiplas camadas para modelar relações complexas em grandes conjuntos de dados.

## Conceitos de Processamento de Linguagem Natural

* **Conceitos de processamento de linguagem natural:** Introdução aos princípios e técnicas fundamentais que permitem aos computadores processar e compreender a linguagem humana.

* **O que é processamento de linguagem natural?:** Definição expandida do PLN como uma disciplina multidisciplinar que envolve ciência da computação, inteligência artificial e linguística, com o objetivo de permitir a comunicação eficaz entre humanos e máquinas em linguagem natural.

* **Processamento de linguagem natural e IA conversacional no Azure - Análise de sentimentos e respostas a perguntas:** Exploração das aplicações do PLN no Azure para a análise da polaridade emocional em textos e para a construção de sistemas de resposta a perguntas inteligentes.

* **Processamento de linguagem natural e IA conversacional no Azure - Fala:** Discussão das tecnologias de PLN no Azure relacionadas ao reconhecimento e síntese de fala, cruciais para a interação conversacional.

* **Processamento de linguagem natural e IA conversacional no Azure – Tradução:** Abordagem das capacidades de tradução automática oferecidas pelo Azure, baseadas em modelos avançados de PLN.

## Trabalhando com serviços Azure OpenAI

* **O que é OpenAI do Azure:** Apresentação da plataforma Azure OpenAI como um serviço que fornece acesso a modelos de linguagem de última geração desenvolvidos pela OpenAI, integrados à infraestrutura e segurança da Microsoft Azure.

* **Como usar o OpenAI do Azure:** Descrição dos procedimentos e ferramentas necessárias para interagir com os serviços Azure OpenAI, incluindo autenticação, configuração e utilização das APIs.

* **Funcionalidade de linguagem natural do OpenAI do Azure:** Detalhamento das funcionalidades específicas oferecidas pelo Azure OpenAI para o processamento e geração de linguagem natural, abrangendo diversas tarefas como redação, resumo e tradução.