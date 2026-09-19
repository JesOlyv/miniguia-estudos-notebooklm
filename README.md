# 📊 Miniguia de Estudos com NotebookLM: Ciência e Análise de Dados

> Projeto desenvolvido como desafio prático para a plataforma DIO (Digital Innovation One), utilizando a ferramenta **NotebookLM** para criar um caderno de estudos temático e inteligente focado na área de Dados.

---

## 🎯 Contexto e Objetivos

### 📖 Contexto
A importância dos **Dados** na era digital: os dados deixaram de ser apenas registros guardados em servidores para se tornarem o ativo mais valioso das organizações. Mais do que números, eles representam padrões, comportamentos e tendências.

### 🎯 Objetivos de Estudo
- **Compreender o ciclo de vida dos dados:** Mapear os processos desde a coleta e tratamento até a análise e tomada de decisão estratégica.
- **Diferenciar papéis na área:** Entender as responsabilidades e atuações de Engenharia, Análise e Ciência de Dados.
- **Entender o valor de negócio:** Investigar como as empresas usam dados para ganhar competitividade no mercado.
- **Mapear competências:** Construir uma tabela comparativa de habilidades e ferramentas essenciais para os profissionais da área.
- **Aprofundar arquiteturas de integração:** Compreender a diferença prática entre os processos de ETL (Extract, Transform, Load) e ELT (Extract, Load, Transform).
- **Garantir a confiabilidade:** Analisar como a governança de dados garante a qualidade, segurança e conformidade em todo o ciclo de vida da informação.

---

## 🔗 Curadoria de Fontes

Para compor a base de conhecimento no **NotebookLM**, foram selecionadas 4 fontes abertas e especializadas em português:

1. 📄 **Bohm Blog – Dados: O ativo mais valioso das empresas modernas**
   - **Descrição:** Artigo que aborda o papel estratégico dos dados como ativos valiosos no mercado atual e seu impacto na tomada de decisão.
   - **Link / Origem:** https://bohm.com.br/blog/dados-o-ativo-mais-valioso-das-empresas-modernas/#main

2. 📄 **EqualData Blog – Entenda o ciclo de vida dos dados**
   - **Descrição:** Guia detalhado sobre todas as etapas da jornada do dado nas organizações, do gerenciamento ao descarte seguro.
   - **Link / Origem:** https://equaldata.ai/blog/entenda-o-ciclo-de-vida-dos-dados/#content

3. 📄 **Kondado Blog – ETL vs. ELT e Modelos de Integração**
   - **Descrição:** Artigo técnico focado na comparação entre as arquiteturas de integração de dados ETL e ELT e suas aplicações práticas.
   - **Link / Origem:** https://kondado.com.br/blog/a/etl-vs-elt-e-modelos

4. 📄 **Unifor (Melhor Profissão) – Qual a diferença entre Analista, Cientista e Engenheiro de Dados?**
   - **Descrição:** Material explicativo sobre as atribuições, habilidades e diferenças entre os três principais papéis do mercado de dados.
   - **Link / Origem:** https://unifor.br/web/melhor-profissao/qual-a-diferenca-entre-analista-cientista-e-engenheiro-de-dados#main-content

---

## 🧠 Engenharia de Prompts e Troubleshooting

Abaixo estão documentados os testes de prompts efetuados no NotebookLM e as estratégias de refinamento utilizadas durante o estudo:

- **Teste 1 (Ciclo de Vida - EqualData):** Solicitei o mapeamento do ciclo de vida dos dados de ponta a ponta. *Ajuste:* Adicionei restrições para detalhar 7 etapas desde a criação até o descarte seguro.
- **Teste 2 (Diferenciação ETL vs. ELT - Kondado):** Solicitei a comparação de arquiteturas. *Ajuste:* Adicionei filtros solicitando foco no local de transformação, perfil necessário e custo computacional.
- **Teste 3 (Papéis Profissionais - Unifor):** Criei um prompt focado em dividir responsabilidades. *Ajuste:* Pedi a estruturação em tabela para evitar sobreposição entre Engenheiro, Analista e Cientista de Dados.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 1. Resumos Estruturados do Assunto

#### A. Ciclo de Vida dos Dados
O ciclo de vida dos dados compreende 7 etapas principais:
1. **Criação ou Coleta:** Captura de dados de fontes internas (ERP, CRM, IoT) ou externas, exigindo validação na origem e conformidade (LGPD/GDPR).
2. **Armazenamento:** Guarda segura em repositórios apropriados, garantindo integridade, criptografia e controle de acesso.
3. **Processamento e Transformação:** Triagem, limpeza e padronização dos dados brutos através de rotinas de ETL/ELT.
4. **Análise e Uso:** Interpretação através de análises descritivas, preditivas e prescritivas para gerar insights.
5. **Compartilhamento e Distribuição:** Disseminação segura de relatórios e dashboards interativos via APIs para tomadores de decisão.
6. **Arquivamento e Retenção:** Transferência de dados menos acessados para ambientes de menor custo (nuvem fria / cold storage).
7. **Descarte e Eliminação Segura:** Encerramento definitivo apagando informações obsoletas de forma irrecuperável (wipe) para mitigar riscos de vazamento.

#### B. Uso Estratégico dos Dados e Competitividade
- **Eficiência Operacional:** Adoção de analytics aumenta a eficiência interna e reduz custos operacionais.
- **Agilidade e Precisão Executiva:** Decisões baseadas em dados são tomadas mais rápido e com maior precisão.
- **Retenção e Personalização:** Organizações Data-Driven conquistam e retêm mais clientes ao oferecer recomendações personalizadas.

#### C. Integração de Dados: ETL vs. ELT

| Atributo | ETL (Extract, Transform, Load) | ELT (Extract, Load, Transform) |
| :--- | :--- | :--- |
| **Local de Transformação** | Ambiente intermediário (staging) antes do envio ao destino. | Diretamente no repositório de destino (Data Warehouse/Lake). |
| **Perfil Necessário** | Desenvolvedores de integração / programadores dedicados. | Analistas e cientistas de dados com conhecimento em SQL. |
| **Flexibilidade** | Menor: mudanças no formato exigem alteração no pipeline. | Maior: dados brutos ficam disponíveis no destino para novos modelos. |
| **Requisito Computacional** | Exige servidores dedicados para o processamento intermediário. | Exige maior poder computacional do banco de dados de destino. |

#### D. Governança de Dados no Ciclo de Vida
A governança atua como a estrutura transversal de sustentação. Ela estabelece políticas, responsabilidades e padrões de qualidade que garantem o cumprimento da LGPD/GDPR e asseguram que as decisões sejam tomadas com base em dados confiáveis.

---

### 📘 2. Tabela Comparativa de Perfis Profissionais

| Perfil Profissional | Foco e Atuação | Habilidades & Ferramentas | Principais Entregáveis |
| :--- | :--- | :--- | :--- |
| **Engenheiro de Dados** | Projetar, construir e manter a infraestrutura e pipelines de integração seguros. | Arquitetura de dados, SQL avançado, Python, ETL/ELT, Data Lakes e Cloud. | Pipelines automatizados, bases limpas/organizadas e arquitetura escalável. |
| **Analista de Dados** | Fornecer análises descritivas e operacionais para responder perguntas de negócio. | SQL, limpeza de dados, estatística descritiva e ferramentas de BI (Power BI/Tableau). | Dashboards interativos, relatórios de desempenho e apresentações executivas. |
| **Cientista de Dados** | Extrair insights complexos, formular perguntas estratégicas e criar modelos preditivos. | Estatística avançada, Machine Learning, Python, R, SQL e visão de negócios. | Modelos preditivos, algoritmos de IA e recomendações estratégicas. |

---

### 📚 3. Glossário de Conceitos-Chave

| Termo | Definição |
| :--- | :--- |
| **Análise Descritiva** | Abordagem analítica focada em interpretar eventos passados e tendências operacionais imediatas. |
| **Cold Storage (Nuvem Fria)** | Armazenamento de baixo custo para dados retidos por motivos fiscais/legais de acesso infrequente. |
| **Data Lake / Warehouse** | Repositórios centralizados para dados brutos (Lake) ou estruturados e otimizados para consulta (Warehouse). |
| **Descarte Seguro (Wipe)** | Procedimento de eliminação definitiva e irrecuperável de dados obsoletos. |
| **ELT** | Processo moderno onde os dados brutos são carregados no destino para transformação posterior via SQL. |
| **ETL** | Processo tradicional de integração que transforma os dados em servidor intermediário antes do banco final. |
| **Governança de Dados** | Diretrizes, papéis e controles que asseguram qualidade, segurança e conformidade legal (LGPD/GDPR). |
| **Pipeline de Dados** | Fluxos automatizados que extraem, movimentam, transformam e entregam dados entre sistemas. |

---

### 🛠️ 4. Prompts Reutilizáveis para Revisão & Treinamento

```text
1. "Atue como um especialista em governança de dados. Com base no cenário da empresa [nome/setor], detalhe como devem ser executadas cada uma das 7 etapas do ciclo de vida dos dados. Indique também quais controles de governança devem ser implementados."
2. "Atue como um arquiteto de dados. Analise a seguinte infraestrutura corporativa: [origens de dados, volume e perfil da equipe]. Elabore uma recomendação comparativa entre adotar ETL ou ELT."
3. "Atue como um Data Lead. Crie um plano de divisão de trabalho para o projeto [objetivo do projeto], definindo responsabilidades, ferramentas e entregáveis do Engenheiro, Analista e Cientista de Dados."
4. "Atue como um auditor de dados. Crie um checklist estruturado para avaliar a maturidade da gestão de dados de uma empresa, cobrindo validação na origem, controle de acesso e eliminação definitiva (wipe) alinhadas à LGPD."
