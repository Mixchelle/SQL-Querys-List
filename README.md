# SQL-Querys-List

<style>
  body {
    background-color: #2c2a2a;
    font-family: 'Harry Potter', sans-serif;
    color: #767474;
    text-align: justify;
    text-align: center;
  }
  
  h1 {
    font-size: 32px;
    font-weight: bold;
    color: #00060b;
  }
  
  p {
    font-size: 30px;
   

  }

  code {
    display: block;
    padding: 10px;
    background-color: #1e1e1e;
    color: #ffffff;
    margin-bottom: 20px;
    width: 80%;
    font-size: 25px;
  }

  ol {
    padding-left: 40px;
    text-align: left;
  }

  li {
    margin-bottom: 20px;
    font-size: 25px;
  }
</style>
</head>
<body>
<h1>Título: SQL - Consultas e Cláusulas</h1>
<p>Descrição:</p>
<p>
O SQL (Structured Query Language) é uma linguagem de programação usada para gerenciar e manipular bancos de dados relacionais. No SQL, existem várias consultas e cláusulas que permitem realizar operações específicas nos dados. Aqui estão algumas das consultas e cláusulas mais comuns:</p>

<ol>
  <li>
    <strong>SELECT:</strong> A query SELECT é usada para recuperar dados de uma tabela ou exibir resultados de uma consulta. Ela permite selecionar colunas específicas ou todas as colunas (*). Exemplo:<br><br>
    <code>SELECT coluna1, coluna2 FROM tabela;</code>
  </li>
  <li>
    <strong>INSERT:</strong> A query INSERT é usada para inserir novos registros em uma tabela. Ela especifica a tabela alvo e os valores a serem inseridos nas colunas correspondentes. Exemplo:<br><br>
    <code>INSERT INTO tabela (coluna1, coluna2) VALUES (valor1, valor2);</code>
  </li>
  <li>
    <strong>UPDATE:</strong> A query UPDATE é usada para modificar os dados existentes em uma tabela. Ela atualiza os valores das colunas especificadas com novos valores. Exemplo:<br><br>
    <code>UPDATE tabela SET coluna1 = novo_valor WHERE condição;</code>
  </li>
  <li>
    <strong>DELETE:</strong> A query DELETE é usada para excluir registros de uma tabela. Ela remove os registros que atendem à condição especificada. Exemplo:<br><br>
    <code>DELETE FROM tabela WHERE condição;</code>
  </li>
  <li>
    <strong>WHERE:</strong> A cláusula WHERE é usada para filtrar registros com base em uma condição específica. Ela é usada em conjunto com as queries SELECT, UPDATE e DELETE. Exemplo:<br><br>
    <code>SELECT coluna1, coluna2 FROM tabela WHERE condição;</code>
  </li>
  <li>
    <strong>ORDER BY:</strong> A cláusula ORDER BY é usada para classificar os resultados de uma consulta em ordem crescente (ASC) ou decrescente (DESC) com base em uma ou mais colunas. Exemplo:<br><br>
    <code>SELECT coluna1, coluna2 FROM tabela ORDER BY coluna1 DESC;</code>
  </li>
  <li>
    <strong>JOIN:</strong> A cláusula JOIN é usada para combinar registros de duas ou mais tabelas com base em uma coluna relacionada entre elas. Existem diferentes tipos de joins, como INNER JOIN, LEFT JOIN, RIGHT JOIN e FULL JOIN. Exemplo:<br><br>
    <code>SELECT coluna1, coluna2 FROM tabela1 JOIN tabela2 ON tabela1.coluna = tabela2.coluna;</code>
  </li>
  <li>
    <strong>DISTINCT:</strong> A cláusula DISTINCT é usada para retornar apenas valores únicos de uma coluna em uma consulta. Ela elimina duplicatas dos resultados. Exemplo:<br><br>
    <code>SELECT DISTINCT coluna FROM tabela;</code>
  </li>
  <li>
    <strong>GROUP BY:</strong> A cláusula GROUP BY é usada para agrupar registros com base em valores de uma ou mais colunas. Ela é frequentemente usada em conjunto com funções de agregação, como COUNT, SUM, AVG, entre outras. Exemplo:<br><br>
    <code>SELECT coluna1, COUNT(coluna2) FROM tabela GROUP BY coluna1;</code>
  </li>
  <li>
    <strong>HAVING:</strong> A cláusula HAVING é usada para filtrar resultados de uma consulta que envolve uma cláusula GROUP BY. Ela permite aplicar condições às funções de agregação. Exemplo:<br><br>
    <code>SELECT coluna1, COUNT(coluna2) FROM tabela GROUP BY coluna1 HAVING COUNT(coluna2) > 10;</code>
  </li>
  <li>
    <strong>LIMIT:</strong> A cláusula LIMIT é usada para limitar o número de registros retornados em uma consulta. Ela permite especificar um limite superior para o número de resultados a serem exibidos. Exemplo:<br><br>
    <code>SELECT coluna FROM tabela LIMIT 10;</code>
  </li>
  <li>
    <strong>BETWEEN:</strong> A cláusula BETWEEN é usada para selecionar valores dentro de um intervalo especificado. Ela é comumente utilizada com valores numéricos, datas ou strings. Exemplo:<br><br>
    <code>SELECT coluna FROM tabela WHERE coluna BETWEEN valor1 AND valor2;</code>
  </li>
  <li>
    <strong>LIKE:</strong> A cláusula LIKE é usada para realizar correspondência de padrões em uma consulta. Ela é usada com strings e permite usar caracteres curinga, como "%", para representar qualquer conjunto de caracteres. Exemplo:<br><br>
    <code>SELECT coluna FROM tabela WHERE coluna LIKE 'abc%';</code>
  </li>
  <li>
    <strong>UNION:</strong> A cláusula UNION é usada para combinar os resultados de duas ou mais consultas em um único conjunto de resultados. Ela retorna todas as linhas resultantes das consultas individuais. Exemplo:<br><br>
    <code>SELECT coluna1 FROM tabela1 UNION SELECT coluna2 FROM tabela2;</code>
  </li>
  <li>
    <strong>AVG:</strong> A função AVG é usada para calcular a média dos valores de uma coluna numérica. Exemplo:<br><br>
    <code>SELECT AVG(coluna) FROM tabela;</code>
  </li>
  <li>
    <strong>SUM:</strong> A função SUM é usada para calcular a soma dos valores de uma coluna numérica. Exemplo:<br><br>
    <code>SELECT SUM(coluna) FROM tabela;</code>
  </li>
  <li>
    <strong>COUNT:</strong> A função COUNT é usada para contar o número de registros em uma tabela ou o número de registros que atendem a uma condição específica. Exemplo:<br><br>
    <code>SELECT COUNT(*) FROM tabela;</code>
  </li>
  <li>
    <strong>MAX:</strong> A função MAX é usada para retornar o valor máximo de uma coluna. Exemplo:<br><br>
    <code>SELECT MAX(coluna) FROM tabela;</code>
  </li>
  <li>
    <strong>MIN:</strong> A função MIN é usada para retornar o valor mínimo de uma coluna. Exemplo:<br><br>
    <code>SELECT MIN(coluna) FROM tabela;</code>
  </li>
  <li>
    <strong>EXISTS:</strong> A cláusula EXISTS é usada para verificar a existência de registros em uma subconsulta. Ela retorna verdadeiro se a subconsulta retornar algum resultado e falso caso contrário. Exemplo:<br><br>
    <code>SELECT coluna FROM tabela1 WHERE EXISTS (SELECT coluna FROM tabela2 WHERE condição);</code>
  </li>
  <li>
    <strong>IN:</strong> A cláusula IN é usada para verificar se um valor corresponde a qualquer valor em uma lista especificada. Exemplo:<br><br>
    <code>SELECT coluna FROM tabela WHERE coluna IN (valor1, valor2, valor3);</code>
  </li>
  <li>
    <strong>NOT:</strong> O operador NOT é usado para negar uma condição em uma cláusula WHERE. Ele retorna registros que não atendem à condição especificada. Exemplo:<br><br>
    <code>SELECT coluna FROM tabela WHERE NOT condição;</code>
  </li>
</ol>
</body>
