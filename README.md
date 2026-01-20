# 🏆 Case Study: Do Planejamento Manual (Calculadora) à Estratégia de Compra Precisa

## O2Data: Transformação da Gestão de Estoque Multi-Filial com Decisão Preditiva

[![Status Projeto](https://img.shields.io/badge/Status-Case%20de%20Sucesso-00B34D?style=for-the-badge&logo=checkmark&logoColor=white&labelColor=232B38)](https://www.linkedin.com/in/itilmgf/)
[![Área de Foco](https://img.shields.io/badge/Foco-Supply%20Chain%20%26%20Estoque-FFD700?style=for-the-badge&logo=delivery&logoColor=333333&labelColor=4B8BBE)](https://www.linkedin.com/in/itilmgf/)
[![Melhoria %](https://img.shields.io/badge/Disponibilidade%20M%C3%A9dia-Acima%20de%2099%25-00B34D?style=for-the-badge&logo=trend&logoColor=white&labelColor=232B38)](https://www.linkedin.com/in/itilmgf/)
[![Ferramentas](https://img.shields.io/badge/Stack-DuckDB%2C%20Python%2C%20PowerBI-4B8BBE?style=for-the-badge&logo=Pandas&logoColor=white&labelColor=232B38)](https://www.linkedin.com/in/itilmgf/)

---

![colagem_65320a8e_20260101_235505](https://github.com/user-attachments/assets/e321b856-979c-4230-af95-6a27b1865156)


## I. 🛑 O Cenário Inicial: A Era do *Feeling* e da Calculadora

O cliente, uma rede de distribuição multi-filial (Ex: Maringá e Goiás), operava a gestão de compras e estoque em um modelo totalmente **reativo e manual**.

### O Problema:

*   **Fórmula Primitiva:** A regra de compra era "Giro Anual / 12 meses * 3 meses de cobertura". Essa fórmula fixa (Modelo Antigo, como na imagem) não considerava sazonalidade, variações de demanda nem o *Lead Time* (tempo de entrega) real de cada fornecedor.
*   **Decisão por *Feeling*:** As compras eram baseadas na experiência (ou ansiedade) do comprador, resultando em um ciclo vicioso:
    *   **Ruptura (Falta de Peça):** Perda de venda e clientes insatisfeitos.
    *   **Sobre-Estoque (Excesso de Peça):** Capital de giro parado e custo alto de armazenagem.
*   **Visão Fragmentada:** Sem Dashboards integrados, a disponibilidade real do estoque só era conhecida em relatórios atrasados, dificultando transferências inteligentes entre filiais.
*   **Itens Negativos:** O registro de itens negativos (venda de algo que não estava fisicamente disponível, como visto na imagem) era frequente, indicando uma falha grave na acuracidade do inventário.

---

## II. 🥇 Ciclo 1: Implementação da Estratégia de Estoque Mínimo Fixo (BI/DI)

A **O2Data** iniciou a transformação com a criação de um Sistema de *Decision Intelligence* (DI) para estabelecer o controle mínimo e a acuracidade de dados.

[![Etapa](https://img.shields.io/badge/Fase%201-Modelagem%20e%20BI%2FDI-0077B5?style=flat-square&logo=database&logoColor=white)](https://www.linkedin.com/in/itilmgf/)
[![Modelo](https://img.shields.io/badge/Modelo-Estoque%20M%C3%ADnimo%20Fixo%20(3M)-0077B5?style=flat-square&logo=calculatord&logoColor=white)](https://www.linkedin.com/in/itilmgf/)
[![Resultado Inicial](https://img.shields.io/badge/Melhoria-Acur%C3%A1cia%20e%20Transpar%C3%AAncia-0077B5?style=flat-square&logo=chart&logoColor=white)](https://www.linkedin.com/in/itilmgf/)

### Entregas Chave:

*   **Modelagem de Dados:** Criação de um modelo de dados analítico (Star Schema) que integra ERP, vendas e inventário.
*   **Dashboards de Performance (KPIs):** Implementação de painéis em tempo quase real para monitorar o **Nível de Disponibilidade** por filial. O foco era reduzir os **Itens Negativos** e eliminar a surpresa.
*   **Regra Fixo/Otimizada (Modelo Antigo):** A fórmula de 3 meses de cobertura foi padronizada e aplicada de forma controlada a todos os itens, criando uma base de **Estoque Mínimo Fixo**.

### Resultados do Ciclo 1 (Transparência e Controle):

*   **Disponibilidade Média:** Subiu de ~80% (cenário de *feeling*) para **98,96% (Maringá)** e **99,58% (Goiás)**.
*   **Redução de Itens Negativos:** Queda drástica de dezenas para **16 (Maringá)** e **4 (Goiás)**, validando a acurácia do inventário e a confiabilidade do processo.
*   **Estratégia de Compra Precisa:** A gestão começou a operar com **"Alta Precisão" e "Precisão Extrema"** (como visto nos medidores), eliminando o *feeling*.

---

## III. 🟠 Ciclo 2: Otimização Preditiva - Estoque Flexível por Lead Time

Com a fundação de dados e acurácia estabelecida, a **O2Data** moveu o cliente para uma estratégia *Next-Gen* de **Planejamento de Estoque Flexível por Lead Time (Novo Modelo)**.

[![Etapa](https://img.shields.io/badge/Fase%202-Otimiza%C3%A7%C3%A3o%20Preditiva%20e%20AI-FF8C00?style=flat-square&logo=rocket&logoColor=white)](https://www.linkedin.com/in/itilmgf/)
[![Modelo](https://img.shields.io/badge/Modelo-Estoque%20Flex%C3%ADvel%20por%20Lead%20Time-FF8C00?style=flat-square&logo=speed&logoColor=white)](https://www.linkedin.com/in/itilmgf/)
[![Resultado Final](https://img.shields.io/badge/Melhoria-Otimiza%C3%A7%C3%A3o%20de%20Capital%20de%20Giro-FF8C00?style=flat-square&logo=money&logoColor=white)](https://www.linkedin.com/in/itilmgf/)

### O Trade-Off Estratégico (Novo Modelo):

O cerne da otimização é o Trade-Off entre **Custo de Compra (Logística)** vs. **Risco de Faltar (Disponibilidade)**.

*   **Modelo Antigo (Fixo):** Gerava compras menos frequentes e melhor negociação, mas mantinha capital parado (Estoque Mínimo **3M Fixo**).
*   **Novo Modelo (Flexível):** O estoque mínimo passa a ser calculado dinamicamente com base no **Lead Time Real do Fornecedor (Curto: 30-45 dias; Longo: 60-90 dias)**, ajustado pela previsão de demanda.

### Entregas Chave:

*   **Reposição Eficiente e Preditiva:** O sistema sugere a reposição baseada na **demanda prevista** para cobrir o período exato do *Lead Time* do fornecedor + *Safety Stock*.
*   **Transferências Inteligentes:** O dashboard foi aprimorado para recomendar automaticamente transferências entre filiais (Maringá ↔️ Goiás), utilizando o estoque em excesso em uma filial para cobrir a demanda urgente em outra, reduzindo a necessidade de uma nova compra.
*   **Otimização do Capital de Giro:** Ao reduzir o Estoque Mínimo de 3 meses fixos para um período ajustado e flexível (ex: 45 dias para Lead Time Curto), **milhões em capital de giro** foram liberados para outros investimentos, mantendo a disponibilidade acima de 99%.

---

## IV. 🎯 Conclusão e Impacto Final (Estratégico)

Este projeto demonstra a progressão da **O2Data** em consultoria de dados:

1.  **Da Caos à Ordem (Ciclo 1):** Estabelecemos a fundação de dados, acurácia e o primeiro nível de controle gerencial (99% Disponibilidade).
2.  **Da Ordem à Otimização (Ciclo 2):** Implementamos a inteligência preditiva para gerenciar o **Trade-Off** e otimizar o capital de giro, transformando o Supply Chain de um centro de custos em um motor de eficiência financeira.

O resultado final é uma organização que agora opera com **Alta Disponibilidade e Estratégia de Compra Precisa**, baseada em dados em tempo real e modelos preditivos, e não mais no feeling ou na calculadora.

---

## 👨‍💻 Contato para Transformação do seu Supply Chain

**Elias Andrade** (Next-Gen System & Data Architect) | **O2Data**
*   **E-mail:** **oeliasandrade@gmail.com**
*   **WhatsApp:** **(11) 9 1335 3137**
