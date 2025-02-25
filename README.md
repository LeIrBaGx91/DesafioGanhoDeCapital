*O primeiro passo foi analisar o que o programa precisava fazer, que seria:
-receber, uma ou mais linhas, de entrada padrão (stdin);
-cada linha seria uma lista json com operações financeiras de buy ou sell;
-cada operação terá:
  operation: Se é buy ou sell
  unit-cost: valor de cada ação
  quantity: quantidade de ação negociada

*Logo, iria utilizar o System.Text.Json para converter o recebimento de json para c#;
 E Console.ReadLine() para ler a entrada e trabalhar

*Próximo passo foi começar a Estruturar o código propriamente dito, começando por uma
classe que representasse a operação.
