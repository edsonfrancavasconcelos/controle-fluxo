Projeto Contador
O projeto Contador é um programa simples desenvolvido em Java que solicita dois parâmetros inteiros ao usuário e, em seguida, conta e imprime os números entre esses dois parâmetros. Além disso, o programa valida se o segundo parâmetro é maior que o primeiro e lança uma exceção caso contrário.

Funcionalidades
Solicitação de Parâmetros: O programa solicita ao usuário que insira dois parâmetros inteiros.
Validação de Parâmetros: Verifica se o segundo parâmetro é maior que o primeiro. Se não for, lança uma exceção ParametrosInvalidosException.
Contagem e Impressão: Realiza uma contagem entre os dois parâmetros inseridos e imprime os números resultantes.
Estrutura do Projeto
O projeto é composto por dois arquivos Java:

Contador.java: Contém a classe principal Contador, que possui o método main para a execução do programa, além do método contar responsável pela lógica de contagem.
ParametrosInvalidosException.java: Define uma exceção personalizada ParametrosInvalidosException para ser lançada quando os parâmetros inseridos forem inválidos.
Como Utilizar
Compilação: Compile os arquivos Java utilizando o comando javac no terminal ou em sua IDE preferida.
Copy code
javac Contador.java
Execução: Execute o programa compilado com o comando java.
Copy code
java Contador
Instruções de Uso: Siga as instruções exibidas no console para inserir os parâmetros. O programa então contará e imprimirá os números entre esses parâmetros.
Exemplo de Uso
Ao executar o programa, será solicitado ao usuário que insira dois parâmetros inteiros:

Copy code
Digite o primeiro parâmetro
3
Digite o segundo parâmetro
7
O programa então imprimirá os números entre esses parâmetros:

Copy code
3
4
5
6
7
Autor
Este projeto foi desenvolvido por Edson França Vasconcelos.
