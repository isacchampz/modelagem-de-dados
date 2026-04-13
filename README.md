# Projeto BI - EVG (Modelagem de Dados)

## 📌 Descrição

Este projeto tem como objetivo aplicar conceitos de Business Intelligence e modelagem dimensional utilizando dados da Escola Virtual de Governo (EVG).

A análise foi construída a partir de uma base de dados contendo informações de matrículas em cursos, incluindo carga horária, localização dos alunos e características dos cursos.

---

## 🧠 Modelagem de Dados

Foi utilizada uma abordagem baseada em **Star Schema (modelo estrela)**, separando os dados em:

* **Tabela Fato:**

  * Fato_Matriculas → contém as métricas principais, como carga horária dos cursos.

* **Tabelas Dimensão:**

  * Dim_Curso → informações sobre cursos e matérias
  * Dim_Localizacao → estado e município dos alunos

---

## 📊 Análise Desenvolvida

A análise construída no Power BI foca na **carga horária total** dos cursos, considerando diferentes dimensões.

Foram exploradas as seguintes combinações:

* Carga horária por curso
* Carga horária por matéria
* Distribuição da carga horária por estado
* Distribuição por município

---

## ❓ Perguntas de Negócio

* Quais cursos possuem maior carga horária total?
* Como a carga horária se distribui entre estados e municípios?
* Existe concentração de cursos em determinadas regiões?
* Quais matérias estão mais presentes nos cursos?

---

## 📈 Visualizações

Foi desenvolvido um gráfico para representar a relação entre cursos e carga horária, permitindo identificar quais cursos possuem maior volume.

---

## ⚙️ Ferramentas Utilizadas

* Power BI (modelagem e visualização)
* Power Query (transformação de dados)
* GitHub (versionamento do projeto)

---

## 👤 Autor
Isac Freitas Fernandes
