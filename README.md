# SQL-Querys-List 📊

## Descrição 📝

O SQL (Structured Query Language) é uma linguagem de programação usada para gerenciar e manipular bancos de dados relacionais. No SQL, existem várias consultas e cláusulas que permitem realizar operações específicas nos dados. Aqui estão algumas das consultas e cláusulas mais comuns:

1. 📥 **SELECT:** A query SELECT é usada para recuperar dados de uma tabela ou exibir resultados de uma consulta. Ela permite selecionar colunas específicas ou todas as colunas (*). Exemplo:
    ```sql
    SELECT coluna1, coluna2 FROM tabela;
    ```

2. 📤 **INSERT:** A query INSERT é usada para inserir novos registros em uma tabela. Ela especifica a tabela alvo e os valores a serem inseridos nas colunas correspondentes. Exemplo:
    ```sql
    INSERT INTO tabela (coluna1, coluna2) VALUES (valor1, valor2);
    ```

3. 🔄 **UPDATE:** A query UPDATE é usada para modificar os dados existentes em uma tabela. Ela atualiza os valores das colunas especificadas com novos valores. Exemplo:
    ```sql
    UPDATE tabela SET coluna1 = novo_valor WHERE condição;
    ```

4. 🗑️ **DELETE:** A query DELETE é usada para excluir registros de uma tabela. Ela remove os registros que atendem à condição especificada. Exemplo:
    ```sql
    DELETE FROM tabela WHERE condição;
    ```

5. 🎯 **WHERE:** A cláusula WHERE é usada para filtrar registros com base em uma condição específica. Ela é usada em conjunto com as queries SELECT, UPDATE e DELETE. Exemplo:
    ```sql
    SELECT coluna1, coluna2 FROM tabela WHERE condição;
    ```

6. 🔀 **ORDER BY:** A cláusula ORDER BY é usada para classificar os resultados de uma consulta em ordem crescente (ASC) ou decrescente (DESC) com base em uma ou mais colunas. Exemplo:
    ```sql
    SELECT coluna1, coluna2 FROM tabela ORDER BY coluna1 DESC;
    ```

7. 🌐 **JOIN:** A cláusula JOIN é usada para combinar registros de duas ou mais tabelas com base em uma coluna relacionada entre elas. Existem diferentes tipos de joins, como INNER JOIN, LEFT JOIN, RIGHT JOIN e FULL JOIN. Exemplo:
    ```sql
    SELECT coluna1, coluna2 FROM tabela1 JOIN tabela2 ON tabela1.coluna = tabela2.coluna;
    ```

8. 🌟 **DISTINCT:** A cláusula DISTINCT é usada para retornar apenas valores únicos de uma coluna em uma consulta. Ela elimina duplicatas dos resultados. Exemplo:
    ```sql
    SELECT DISTINCT coluna FROM tabela;
    ```

9. 📊 **GROUP BY:** A cláusula GROUP BY é usada para agrupar registros com base em valores de uma ou mais colunas. Ela é frequentemente usada em conjunto com funções de agregação, como COUNT, SUM, AVG, entre outras. Exemplo:
    ```sql
    SELECT coluna1, COUNT(coluna2) FROM tabela GROUP BY coluna1;
    ```

10. 📉 **HAVING:** A cláusula HAVING é usada para filtrar resultados de uma consulta que envolve uma cláusula GROUP BY. Ela permite aplicar condições às funções de agregação. Exemplo:
    ```sql
    SELECT coluna1, COUNT(coluna2) FROM tabela GROUP BY coluna1 HAVING COUNT(coluna2) > 10;
    ```

11. 📏 **LIMIT:** A cláusula LIMIT é usada para limitar o número de registros retornados em uma consulta. Ela permite especificar um limite superior para o número de resultados a serem exibidos. Exemplo:
    ```sql
    SELECT coluna FROM tabela LIMIT 10;
    ```

12. 🎯 **BETWEEN:** A cláusula BETWEEN é usada para selecionar valores dentro de um intervalo especificado. Ela é comumente utilizada com valores numéricos, datas ou strings. Exemplo:
    ```sql
    SELECT coluna FROM tabela WHERE coluna BETWEEN valor1 AND valor2;
    ```

13. 💬 **LIKE:** A cláusula LIKE é usada para realizar correspondência de padrões em uma consulta. Ela é usada com strings e permite usar caracteres curinga, como "%", para representar qualquer conjunto de caracteres. Exemplo:
    ```sql
    SELECT coluna FROM tabela WHERE coluna LIKE 'abc%';
    ```

14. 🤝 **UNION:** A cláusula UNION é usada para combinar os resultados de duas ou mais consultas em um único conjunto de resultados. Ela retorna todas as linhas resultantes das consultas individuais. Exemplo:
    ```sql
    SELECT coluna1 FROM tabela1 UNION SELECT coluna2 FROM tabela2;
    ```

15. 📈 **AVG:** A função AVG é usada para calcular a média dos valores de uma coluna numérica. Exemplo:
    ```sql
    SELECT AVG(coluna) FROM tabela;
    ```

16. 📊 **SUM:** A função SUM é usada para calcular a soma dos valores de uma coluna numérica. Exemplo:
    ```sql
    SELECT SUM(coluna) FROM tabela;
    ```

17. 🔢 **COUNT:** A função COUNT é usada para contar o número de registros em uma tabela ou o número de registros que atendem a uma condição específica. Exemplo:
    ```sql
    SELECT COUNT(*) FROM tabela;
    ```

18. 🚀 **MAX:** A função MAX é usada para retornar o valor máximo de uma coluna. Exemplo:
    ```sql
    SELECT MAX(coluna) FROM tabela;
    ```

19. 📉 **MIN:** A função MIN é usada para retornar o valor mínimo de uma coluna. Exemplo:
    ```sql
    SELECT MIN(coluna) FROM tabela;
    ```

20. 🌐 **EXISTS:** A cláusula EXISTS é usada para verificar a existência de registros em uma subconsulta. Ela retorna verdadeiro se a subconsulta retornar algum resultado e falso caso contrário. Exemplo:
    ```sql
    SELECT coluna FROM tabela1 WHERE EXISTS (SELECT coluna FROM tabela2 WHERE condição);
    ```

21. 📦 **IN:** A cláusula IN é usada para verificar se um valor corresponde a qualquer valor em uma lista especificada. Exemplo:
    ```sql
    SELECT coluna FROM tabela WHERE coluna IN (valor1, valor2, valor3);
    ```

