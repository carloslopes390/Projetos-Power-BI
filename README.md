  # Explicações Power BI

  Dashboards feitos apenas para testar funcionalidades como tabulação, lingagem DAX e Background

  - [Dashboard Comercial](https://github.com/carloslopes390/Projetos-Power-BI/tree/main/Comercial)

### Dashboard Comercial 

# Resumo

Aqui entra a funcionalidade do Background de cores que façam com que o visual fique mais interessante e vivo no contexto das informações
Para esse Dashboard não foram utilizadas muitas fórmulas DAX, pois os dados já estavam consolidados e bem estruturados para subir no Power BI 

Algumas técnicas avançadas utilizadas:
- Filtro em SLICE para Datas, ideal para Períodos Abertos
- Formatação Condicional do Vendedor do menor para o maior faturamento, aqui dá uma idéia de qual vendedor está melhor graficamente


Apenas 2 fórmulas foram utilizadas:
<img width="1110" height="27" alt="image" src="https://github.com/user-attachments/assets/1a40414c-3537-48a3-8813-b35e781827d3" />

### SUM - Para somar o valor faturado total 

<img width="1067" height="23" alt="image" src="https://github.com/user-attachments/assets/6104f396-a010-4b49-a249-810e0eb36daf" />

### DISTINCTCOUNT - Para uma contagem sem duplicidade, no caso de clientes não duplicados

### Relacionamento Entre as Bases 

Importante que as chaves converserm entre si, para que haja a conexação (join) entre as tabelas

<img width="1086" height="376" alt="image" src="https://github.com/user-attachments/assets/a4c56a52-4ce5-4303-a795-3b6596bc790d" />





### Dashboard Financeiro

- [Dashboard Financeiro](https://github.com/carloslopes390/Projetos-Power-BI/tree/main/Dashboard%20-%20Financeiro)

  <img width="1126" height="630" alt="image" src="https://github.com/user-attachments/assets/f780d3a6-b7fe-484d-b3b8-e457b51673ea" />


  Aqui foi um dashboard com um visual mais simples, porém mais rico na linguagem DAX

  Algumas técnicas Avançadas + DAX:

<img width="621" height="167" alt="image" src="https://github.com/user-attachments/assets/151a9807-1a55-4ceb-861c-9d24a60c301a" />

Esse é um card com Target e Linha de tendência, basicamento usamos o faturamento YoY, e colocamos um comparativo entre os períodos.

No primeiro dax, colocamos uma condição no CALCULATE para somar apenas o que foi selecionado na base
No segundo, a idéia é a mesma, porém usamos o SAMEPERIODLASTYEAR, para calcular a soma, comparando com o periodo do ano anterior
Assim conseguimos fazer a diferença entre quando estamos subinddo na Receita e caindo na despesa

<img width="627" height="131" alt="image" src="https://github.com/user-attachments/assets/4d833ad4-6b38-4118-932d-54e2d9979053" />


<img width="1073" height="96" alt="image" src="https://github.com/user-attachments/assets/47798da0-6738-4904-a8a1-7567dbc6d80b" />


### 

Outra técnica realizada foi um comando SWICH, basicamento é o IF na linguagem DAX

<img width="416" height="180" alt="image" src="https://github.com/user-attachments/assets/a9466bd1-1dc4-4304-b94d-6791dde1f042" />

<img width="1014" height="103" alt="image" src="https://github.com/user-attachments/assets/ab89abaf-847d-493b-a4f9-f0d99e0ede7e" />

<img width="125" height="66" alt="image" src="https://github.com/user-attachments/assets/89b054da-2a82-4d51-9f49-62a66db2c073" />

Aqui precisamos montar uma tabela para que aponte qual indicador queremos observar no gráfico, no caso foram a receita e despesa, e colocar no eixo para qual indicador apontar, isso é bom para não precisar fazer um gráfico só de receita e outro só de despesa, nos poupando espaço e memória.

Outras fórmulas muito utilizadas:

<img width="913" height="24" alt="image" src="https://github.com/user-attachments/assets/dba86e09-6baa-4be4-b689-d38a831587cc" />

<img width="878" height="179" alt="image" src="https://github.com/user-attachments/assets/0369a403-c676-4690-ab16-7d58ed305ce1" />


## DIVIDE - Faz a divisão, e caso haja erro, ele retorna zero, bem mais prático do que utlizar uma fração e colocar um SEERRO, mais um ponto para não melhorar performance
## VAR - basicamente ele cria uma variável temporaria no DAX 





















  
