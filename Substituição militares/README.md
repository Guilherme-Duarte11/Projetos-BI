# 📊 Painel – Substituição de  Militares (2024/25)

Este projeto apresenta um painel desenvolvido no **Power BI** com o objetivo de analisar os dados da Portaria Militar de 2024 do Ministério da Defesa, oferecendo visualizações claras e filtros funcionais para melhor interpretação das informações.  
O dashboard foi construído utilizando uma base principal em Excel e uma tabela derivada de um arquivo PDF, sendo necessário realizar modelagem, relacionamentos e tratamentos específicos para viabilizar as análises.

---
️
## ⚠️ Aviso de Confidencialidade: 
Todos os dados apresentados neste painel foram anonimizados. Nomes, valores, identificações e demais informações sensíveis foram alterados ou removidos para garantir total sigilo e segurança, sem comprometer o propósito analítico do projeto.

---

## 📝 Objetivo do Projeto

- Consolidar informações oficiais da portaria militar em um único painel interativo.
- Facilitar a visualização por categorias, gêneros e classificações militares.
- Criar filtros eficientes que permitam analisar os dados em múltiplas perspectivas.
- Transformar um PDF em uma tabela estruturada aproveitável dentro do Power BI.
- Entregar um painel limpo, informativo e com boa composição visual.

---

## 📂 Estrutura dos Dados

O projeto utilizou duas principais fontes de dados:

1. **Tabela principal (Excel)**  
   Contém informações dos militares, gênero, classificações e dados administrativos.

2. **Tabela da Portaria (extraída de PDF)**  
   A portaria estava disponível apenas em PDF, portanto foi necessário:
   - Converter o conteúdo para uma tabela estruturada.
   - Padronizar campos e valores.
   - Ajustar formatos para permitir relacionamentos com a tabela principal.

---

## 🔗 Modelagem e Relacionamentos

Para viabilizar as análises, foi necessário:

- Criar **relacionamentos** entre a tabela da portaria (convertida do PDF) e a tabela principal.
- Garantir integridade entre as tabelas para que os filtros funcionassem em todo o painel.
- Organizar o modelo de dados com foco em clareza e performance.

Esses relacionamentos permitem, por exemplo:

- Filtrar militares por gênero, unidade, círculo hierárquico e secretaria.
- Comparar o efetivo atual com o efetivo previsto pela portaria.
- Identificar unidades que estão acima ou abaixo do limite permitido.

---

## 📊 Estrutura das Páginas do Painel

### **1️⃣ Página da Portaria**
Mostra os números definidos oficialmente pela portaria:
- Total de militares previstos
- Totais por círculo hierárquico
- Totais por unidade e por força
- Regras estruturais definidas pelo documento

### **2️⃣ Página do Efetivo Atual**
Exibe o total de militares efetivamente presentes no Ministério:
- Lista completa dos militares
- Filtro por gênero
- Filtro por círculo hierárquico
- Filtro por unidade e secretaria
- Campo de busca por nome do militar

### **3️⃣ Página de Comparação**
Realiza a análise comparativa entre o previsto e o atual:
- Diferença entre a distribuição ideal e a real
- Identificação de desbalanceamento entre órgãos
- Exemplo: GM com excesso de militares, inclusive excesso de oficiais subalternos

---

## 🛠️ Tecnologias Utilizadas

- **Power BI Desktop**
- **Power Query**
- **Modelagem de Dados**
- **DAX**
- Conversão e tratamento de **PDF para tabela estruturada**

---

## 📷 Imagens do Painel
Tela 1
<img width="1432" height="799" alt="Captura de tela 2025-11-19 174258" src="https://github.com/user-attachments/assets/ce0eeff8-9113-4815-937b-882851b15cb3" />

Tela 2
<img width="1426" height="801" alt="Captura de tela 2025-11-19 174311" src="https://github.com/user-attachments/assets/c4d06e78-a9a7-450e-a508-6759cbf5165e" />

Tela 3
<img width="1427" height="797" alt="Captura de tela 2025-11-19 174320" src="https://github.com/user-attachments/assets/7d96ce15-9205-4cd5-834e-161190a6fb90" />

---

## 📥 Download
O arquivo `.pbix` estará disponível na pasta deste repositório caso você deseje incluí-lo.

---

## 📌 Status do Projeto
✔ Projeto finalizado  
🔜 Futuras melhorias podem incluir novos KPIs e análises avançadas

---

## 📧 Contato

**Guilherme Duarte**  
📩 guilhermeddsilva@gmail.com<br> 
💼 [Linkedin](https://www.linkedin.com/in/guilherme-duarte-da-silva/)

---
