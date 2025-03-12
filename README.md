# Explorando os Recursos de IA Generativa com Copilot e OpenAI  

Teste 5 do Bootcamp **Azure Fundamentals AI 900** da **DIO**  

---

## O que é IA Generativa?  

A **Inteligência Artificial (IA)** busca imitar o comportamento humano por meio do aprendizado de máquina, permitindo que sistemas interajam com o ambiente e executem tarefas sem instruções explícitas.  

A **IA Generativa** é capaz de criar conteúdos originais e é amplamente utilizada em aplicações como chatbots, geração de código e imagens. Seu funcionamento se baseia na entrada de linguagem natural e na produção de respostas apropriadas em diferentes formatos, como:  

- **Geração de linguagem natural:** criação e aprimoramento de textos (ex.: ChatGPT).  
- **Geração de código:** automação e auxílio no aprendizado de linguagens de programação.  
- **Geração de imagens:** produção de ilustrações baseadas em descrições fornecidas pelo usuário.  

---

## Modelos de Linguagem de Grande Escala (LLMs)  

Os aplicativos de IA generativa utilizam **Modelos de Linguagem de Grande Escala (LLMs)**, que são modelos avançados de aprendizado de máquina especializados no **Processamento de Linguagem Natural (PLN)**. Entre suas aplicações, destacam-se:  

- Análise de sentimentos e classificação de textos.  
- Resumo automático de documentos.  
- Comparação semântica entre diferentes fontes de texto.  
- Geração de novos conteúdos em linguagem natural.  

### Arquitetura dos Modelos Transformadores  

A estrutura dos modelos transformadores é composta por dois blocos principais:  

- **Codificador:** cria representações semânticas do vocabulário utilizado no treinamento.  
- **Decodificador:** gera novas sequências de linguagem a partir dessas representações.  

O processo de modelagem envolve a **tokenização do texto**, onde cada palavra ou frase é convertida em tokens numéricos exclusivos. Esses tokens são então processados por camadas de atenção, que determinam a relação entre os elementos textuais e ajudam a prever a sequência mais provável de palavras.  

![Transformadores](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/4db12138-34bc-47ce-957f-38b349105109)  

---

## Tokenização nos Modelos de Linguagem  

A tokenização é uma etapa essencial no treinamento dos modelos transformadores e ocorre em duas fases principais:  

1. **Tokenização:** Decomposição do texto em unidades menores chamadas tokens.  
2. **Inserções ou Incorporações:** Representação dos tokens como vetores numéricos para capturar relações entre palavras.  

![Tokenização](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/335c5321-a9a4-4876-89b5-3db6cb8e306a)  

### Atenção e Relacionamento Entre Tokens  

O modelo de atenção examina a relação entre os tokens para prever com precisão a sequência mais adequada de palavras no decodificador.  

![Atenção](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/13bb4296-cf2c-46c1-b10a-70acc1fd837e)  

---

## Copilotos e a Automação de Tarefas  

Os **copilotos** são assistentes baseados em IA generativa integrados a aplicativos para facilitar a execução de tarefas. Desenvolvedores podem incorporá-los a sistemas existentes, permitindo que usuários obtenham assistência rápida e eficiente.  

Além disso, os copilotos enviam prompts para **LLMs** e geram conteúdos úteis para diferentes aplicações, otimizando fluxos de trabalho e aumentando a produtividade.  

---

## Aprimoramento de Respostas com Engenharia de Prompts  

A **engenharia de prompt** consiste no refinamento das instruções fornecidas à IA para melhorar a qualidade das respostas geradas.  

Para obter melhores resultados, os desenvolvedores podem aplicar técnicas como:  
- Uso de linguagem direta e objetiva.  
- Inclusão de exemplos e dados de referência.  
- Definição de mensagens do sistema para guiar a IA.  

---

## Fundamentos do Serviço Azure OpenAI  

### O que é o Azure OpenAI?  

O **Serviço OpenAI do Azure** é uma plataforma baseada em nuvem que permite a implantação, personalização e hospedagem de **modelos de linguagem de grande escala**.  

Ele oferece:  
- Modelos de IA generativa pré-treinados.  
- Funcionalidades para personalização.  
- Ferramentas de segurança para implementação responsável da IA.  
- Integração com RBAC (controle de acesso baseado em função) e redes privadas.  

### Métodos de Desenvolvimento no Azure OpenAI  

Os desenvolvedores podem criar soluções no **Azure OpenAI** por meio de:  
- **Estúdio de IA do Azure**  
- **API REST**  
- **SDKs compatíveis com CLI do Azure**  

---

## Como Utilizar o Azure OpenAI  

### **Estúdio Azure OpenAI**  
- Permite criar e implantar modelos de IA para diversas aplicações.  
- Baseado em modelos otimizados para diferentes tarefas, como GPT-4, GPT-3.5, Embeddings e DALL-E.  

### **Playgrounds**  
- Ambiente interativo para testar modelos sem necessidade de codificação.  
- Configuração de assistentes personalizados para definir o comportamento da IA.  

---

## Funcionalidades do Azure OpenAI  

Os modelos do Azure OpenAI são amplamente utilizados para:  
- **Compreensão e geração de linguagem natural** por meio de modelos GPT.  
- **Tradução automática de textos e código.**  
- **Edição e criação de imagens** utilizando **DALL-E**, que oferece suporte para:  
  - Criação de imagens em diferentes estilos.  
  - Edição avançada com remoção e adição de elementos.  
  - Geração de variações a partir de uma imagem original.  

---

## Implementação de IA Generativa de Forma Responsável  

O desenvolvimento de **soluções de IA generativa** deve seguir boas práticas de segurança e ética.  

As **quatro fases fundamentais** para uma IA responsável incluem:  
1. **Identificar** riscos e impactos.  
2. **Medir** o desempenho e viés do modelo.  
3. **Mitigar** possíveis danos e falhas.  
4. **Operar** com transparência e segurança.  

![IA Responsável](https://github.com/Edivania88Duarte/-Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI/assets/120994730/94c898d5-36fc-4dc4-bdcf-f876b8709ce0)  

---

## Links Úteis  

- [Explorando IA Generativa no Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)  
- [Introdução ao Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)  
- [Filtros de Conteúdo no Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai.html)  
