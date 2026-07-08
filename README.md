# SafelyPay — Relatório de Governança de TI & Gestão de Portfólio

## Sobre o Projeto
Este repositório apresenta o **Case de Governança de TI** desenvolvido para a **SafelyPay**, uma fintech fictícia que opera no modelo SaaS como plataforma digital de pagamentos e gateway antifraude. O objetivo deste estudo é demonstrar o alinhamento estratégico entre as necessidades de negócio e os investimentos em tecnologia, garantindo mitigação de riscos financeiros e escalabilidade.

O projeto faz parte do ecossistema de soluções da SafelyPay, focando na camada estratégica, tomada de decisão e priorização de demandas tecnológicas.

---

## Cenário da Organização & Estratégia
* **Setor:** Fintech / Meios de Pagamento (SaaS).
* **Modelo de Negócio:** Monetização via taxas sobre transações e assinaturas recorrentes.
* **Core Business:** Processamento ágil de PIX, cartões e boletos com análise preditiva de risco.
* **Pilares Estratégicos:** Eficiência operacional, segurança máxima (antifraude), escalabilidade em picos de alta demanda e retenção através da experiência do usuário (UX).

---

## Matriz de Priorização do Portfólio de TI

Para avaliar a viabilidade e o impacto das demandas, as iniciativas foram auditadas sob cinco critérios fundamentais (Alinhamento, Valor, Custo, Urgência e Impacto ao Usuário):

| Iniciativa Tecnológica | Alinhamento Estratégico | Valor de Negócio | Custo Estimado | Urgência | Impacto ao Usuário |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1. Motor Antifraude com IA** | Muito Alto | Muito Alto | Alto | Muito Alta | Alto |
| **2. App Mobile (Produtores)** | Alto | Alto | Médio | Alta | Muito Alto |
| **3. Expansão Multi-Cloud** | Muito Alto | Alto | Alto | Alta | Médio |
| **4. Arquitetura Microserviços** | Muito Alto | Alto | Muito Alto | Média | Médio |
| **5. Dashboard de BI Avançado** | Alto | Médio | Médio | Média | Alto |

---

## Roadmap e Decisões do Comitê de TI

Com base na matriz de valor e risco, o portfólio de TI foi estruturado em três horizontes temporais para garantir sustentabilidade financeira e foco no *core business*:

### Curto Prazo: Execução Prioritária
1. **Upgrade do Motor Antifraude (Machine Learning):** Implementação de modelos preditivos para análise de risco em tempo real. Foco em reduzir *chargebacks* e maximizar a aprovação de vendas legítimas.
2. **Aplicativo Mobile para Produtores:** Canal direto focado na experiência e retenção do cliente B2B para monitoramento de métricas e saques.

### ⏳ Médio Prazo: Planejamento e Preparação
* **Expansão de Infraestrutura Multi-Cloud:** Migração para arquitetura distribuída para mitigar indisponibilidades em eventos de alta conversão (ex: Black Friday).
* **Painel de Business Intelligence (BI):** Dashboards de transparência financeira e volumetria de recusas por fraude.

### Longo Prazo: Evolução Estrutural
* **Migração de Monolito para Microserviços:** Reengenharia de software necessária para suportar o crescimento em escala global, adiada temporariamente devido ao altíssimo custo e complexidade de orquestração técnica inicial.

---

## Uso de IA Generativa na Governança

Este plano estratégico utilizou Inteligência Artificial como ferramenta de aceleração para benchmark e estruturação de ideias. 

> **Exemplos de Prompts Aplicados:**
> * *"Priorize projetos de TI para uma fintech SaaS com foco em antifraude, escalabilidade e experiência do usuário."*
> * *"Compare microserviços vs monolito em termos de custo, risco e escalabilidade."*

**Engenharia de Decisão:** A IA auxiliou na definição dos critérios de priorização e no mapeamento de riscos tecnológicos (como os falsos positivos do motor de IA). O processo contou com **validação e refinamento humano** para customizar as respostas genéricas ao contexto regulatório e operacional da SafelyPay.

---

## Documentação Completa
O relatório executivo expandido, contendo análises de limitações de infraestrutura e detalhamento de riscos operacionais, está disponível na pasta dedicada:
* 📄 [Relatório Técnico de Governança de TI - Fase 1](docs/safelypay-relatorio-governanca-fase1.pdf)
