# Análise da Evasão Escolar no Ensino Superior

O acesso a uma educação de qualidade é essencialmente um direito fundamental, e governos ao redor do mundo se empenham incansavelmente para assegurar que todas as crianças se matriculem e completem sua educação formal. No entanto, o abandono escolar ainda representa um desafio significativo, sendo influenciado por uma complexa malha de fatores sociais, econômicos e demográficos.

Com base nessa premissa, este notebook, alinhado ao propósito do artigo principal, visa esclarecer essa problemática. Emprega-se, para tanto, uma abordagem analítica robusta, que integra técnicas de engenharia e ciência de dados complementadas pelo uso de aprendizado de máquina.

O objetivo é identificar os principais fatores que contribuem para a evasão escolar, focando especificamente no contexto do ensino superior. Essa delimitação permite uma investigação mais aprofundada e a geração de insights pertinentes que podem fundamentar o desenvolvimento de políticas públicas mais eficazes para mitigar o fenômeno da evasão.

Embora o foco se concentre no ensino superior, os métodos e descobertas deste estudo têm o potencial de servir como base para investigações futuras voltadas a outros níveis educacionais, ampliando assim o escopo de aplicabilidade das estratégias de intervenção educacional.

## Fonte dos Dados

Os dados originais foram extraídos da seguinte fonte:
[UCI Machine Learning Repository: Predict Students' Dropout and Academic Success](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)

**Referência:**
Realinho, Valentim, Vieira Martins, Mónica, Machado, Jorge, and Baptista, Luís. (2021). Predict Students' Dropout and Academic Success. UCI Machine Learning Repository. https://doi.org/10.24432/C5MC89.

## Descrição das Colunas

| Nome da coluna | Descrição |
|----------------|-------------|
| Marital status | O estado civil do estudante. |
| Application mode | O método de aplicação utilizado pelo estudante. |
| Application order | A ordem em que o estudante se aplicou. |
| Course | O curso realizado pelo estudante. |
| Daytime/evening attendance | Se o estudante assiste às aulas durante o dia ou à noite. |
| Previous qualification | A qualificação obtida pelo estudante antes de se matricular no ensino superior. |
| Nacionality | A nacionalidade do estudante. |
| Mother's qualification | A qualificação da mãe do estudante. |
| Father's qualification | A qualificação do pai do estudante. |
| Mother's occupation | A ocupação da mãe do estudante. |
| Father's occupation | A ocupação do pai do estudante. |
| Displaced | Se o estudante é uma pessoa deslocada. |
| Educational special needs | Se o estudante tem necessidades educacionais especiais. |
| Debtor | Se o estudante é devedor. |
| Tuition fees up to date | Se as taxas de matrícula do estudante estão em dia. |
| Gender | O gênero do estudante. |
| Scholarship holder | Se o estudante é bolsista. |
| Age at enrollment | A idade do estudante no momento da matrícula. |
| International | Se o estudante é internacional. |
| Curricular units 1st sem (credited) | O número de unidades curriculares creditadas pelo estudante no primeiro semestre. |
| Curricular units 1st sem (enrolled) | O número de unidades curriculares em que o estudante se matriculou no primeiro semestre. |
| Curricular units 1st sem (evaluations) | O número de unidades curriculares avaliadas pelo estudante no primeiro semestre. |
| Curricular units 1st sem (approved) | O número de unidades curriculares aprovadas pelo estudante no primeiro semestre. |

## Objetivo

O principal objetivo deste estudo é identificar e analisar os fatores que contribuem para a evasão escolar no ensino superior, utilizando técnicas avançadas de ciência de dados e aprendizado de máquina para fornecer insights que possam ser usados na formulação de políticas educacionais mais eficazes.

## Metodologia

A metodologia empregada neste estudo inclui a otimização de hiperparâmetros utilizando Grid Search combinada com validação cruzada para maximizar o desempenho dos modelos de classificação. Esta abordagem permite uma análise sistemática e robusta dos dados, garantindo a identificação das melhores configurações de modelos para prever a evasão escolar.

## Conclusão

Os resultados deste estudo fornecem uma compreensão aprofundada dos fatores que influenciam a evasão escolar no ensino superior, com potencial para aplicação em níveis educacionais variados. As descobertas visam apoiar a formulação de políticas públicas mais eficazes e direcionadas para reduzir a evasão escolar e promover a conclusão dos estudos.

---

**Nota:** Este README fornece uma visão geral do projeto e dos dados utilizados. Para uma análise detalhada e os resultados completos, consulte o notebook e a documentação disponíveis neste repositório.
