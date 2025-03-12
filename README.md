# Explorando os Recursos de IA Generativa com Copilot e OpenAI  

Teste 5 do Bootcamp **Azure Fundamentals AI 900** da **DIO**  

---

## O que é IA Generativa?  

A **Inteligência Artificial (IA)** utiliza aprendizado de máquina para simular o raciocínio humano, permitindo que sistemas processem informações e realizem tarefas sem comandos diretos.  

A **IA Generativa** é uma vertente que cria conteúdos originais e tem diversas aplicações, como:  

- **Geração de texto:** criação e aprimoramento de conteúdos escritos (ex.: ChatGPT).  
- **Geração de código:** suporte ao desenvolvimento e automação de tarefas.  
- **Criação de imagens:** produção de ilustrações a partir de descrições fornecidas pelos usuários.  


---

## Modelos de Linguagem de Grande Escala (LLMs)  

Os modelos de IA generativa utilizam **Modelos de Linguagem de Grande Escala (LLMs)**, que são redes neurais treinadas para entender e gerar linguagem natural. Suas aplicações incluem:  

- Identificação de sentimentos e categorização de textos.  
- Resumo automático de documentos extensos.  
- Comparação semântica entre diferentes conteúdos.  
- Criação de textos coerentes e contextuais.  

### Arquitetura dos Modelos Transformadores  

Os modelos transformadores possuem dois componentes principais:  

- **Codificador:** processa a entrada e cria representações semânticas.  
- **Decodificador:** usa essas representações para gerar novos conteúdos.  

Esse processo envolve a **tokenização do texto**, convertendo palavras em tokens numéricos que passam por camadas de atenção, permitindo à IA gerar respostas precisas.  

![Transformadores](https://github.com/Ilair/Explorando_Recursos_IA_Generativa_Copilot_OpenAI/blob/main/img01.jpg?raw=true)  

---

## Tokenização nos Modelos de Linguagem  

O processo de tokenização é essencial para os LLMs e ocorre em duas etapas:  

1. **Tokenização:** separação do texto em pequenas unidades chamadas tokens.  
2. **Incorporações:** conversão dos tokens em vetores numéricos que capturam seus significados.  

![Tokenização](https://github.com/Ilair/Explorando_Recursos_IA_Generativa_Copilot_OpenAI/blob/main/img02.jpg?raw=true)  

### Atenção e Relacionamento Entre Tokens  

A técnica de **atenção** analisa a relação entre tokens, permitindo que a IA gere respostas mais naturais e contextualmente relevantes.  

![Atenção](https://github.com/Ilair/Explorando_Recursos_IA_Generativa_Copilot_OpenAI/blob/main/img03.jpg?raw=true)  

---

## Copilotos e Automação de Tarefas  

Os **copilotos** são assistentes baseados em IA generativa que ajudam os usuários a executar tarefas de forma mais eficiente. Eles podem ser integrados a aplicativos para otimizar fluxos de trabalho e fornecer sugestões inteligentes.  

Além disso, os copilotos interagem com **LLMs**, enviando comandos e retornando respostas personalizadas.  
 

---

## Engenharia de Prompts: Melhorando Respostas da IA  

A **engenharia de prompt** consiste na formulação de comandos mais precisos para obter respostas melhores da IA. Algumas estratégias incluem:  

- Uso de linguagem objetiva e bem definida.  
- Inclusão de exemplos para guiar o modelo.  
- Ajuste de parâmetros para garantir maior precisão nas respostas. 

---

## Fundamentos do Serviço Azure OpenAI  

### O que é o Azure OpenAI?  

O **Azure OpenAI Service** é uma plataforma que oferece modelos avançados de IA para criação, personalização e implantação de soluções baseadas em aprendizado de máquina.  

Seus principais recursos incluem:  

- Modelos de IA generativa pré-treinados.  
- Ferramentas para personalização e adaptação.  
- Recursos de segurança e governança.  
- Integração com **RBAC (Role-Based Access Control)** e redes privadas.  

### Métodos para Desenvolvimento no Azure OpenAI  

Os desenvolvedores podem acessar os modelos do Azure OpenAI por meio de:  
- **Azure AI Studio**  
- **API REST**  
- **SDKs compatíveis com a CLI do Azure**   

---

## Utilizando o Azure OpenAI  

### **Azure OpenAI Studio**  
- Permite criar e implantar modelos de IA personalizados.  
- Baseado em modelos avançados como **GPT-4, GPT-3.5, Embeddings e DALL-E**.  

### **Playgrounds**  
- Ferramenta interativa para testar modelos sem necessidade de programação.  
- Configuração de assistentes para personalizar o comportamento da IA.   

---

## Principais Funcionalidades do Azure OpenAI  

Os modelos do Azure OpenAI são amplamente utilizados para:  

- **Análise e criação de textos em linguagem natural.**  
- **Tradução e conversão de código.**  
- **Geração e edição de imagens com o DALL-E.**  

Os modelos de IA generativa permitem:  
- Criar imagens personalizadas em diferentes estilos.  
- Editar e modificar imagens existentes.  
- Gerar variações de imagens com base em um exemplo original.   

---

## Desenvolvendo IA Generativa de Forma Responsável  

A implementação da **IA generativa responsável** deve seguir diretrizes éticas e de segurança.  

As **quatro fases essenciais** desse processo incluem:  
1. **Identificação:** análise de possíveis riscos.  
2. **Medição:** avaliação do desempenho e impacto do modelo.  
3. **Mitigação:** aplicação de correções e melhorias.  
4. **Operação:** monitoramento contínuo para garantir o uso seguro.  

![IA Responsável](https://github.com/Ilair/Explorando_Recursos_IA_Generativa_Copilot_OpenAI/blob/main/img04.jpg?raw=true)  

---

## Links Úteis  

- [Explorando IA Generativa no Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)  
- [Introdução ao Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)  
- [Filtros de Conteúdo no Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai.html)  
