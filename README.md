# Entrada e saída de dados
Entrada e Saida de dados (I/O) em Java
Basicamente é a forma como seu programa recebe informações (entrada) e como ele mostra informações (saída).
```
1) Saída
O objeto System.out representa a saída padrão, permitindo exibir dados no console quando executamos uma aplicação em Java. O System.out possui diversos métodos para gerar saídas, sendo os mais utilizados os métodos println, printf e print.
```
✅ Método println()
O método System.out.println() gera uma string de texto, cria uma nova linha abaixo da atual e então posiciona o cursor nessa linha.
```
Exemplos:
```
System.out.println("O Gremio vai sair campeão);
System.out.println("Meu segundo println em java.);
✅ Método printf()
```
O método System.out.printf() mostra pos dados na saída formatados. um especificador d formato se inicia com o símnolo %, seguido por um caractere que representa o tipo de dado.
```
Exemplos:
```
Double numDecimal = 23.8954;
int minhaIdade = 29;
String meuNome = "Renato Gaúcho";
char gremio= 'g';
```
System.out.printf("Número = %.2f%n", numDecimal); 
System.out.printf("Minha idade = %.2d%n", minhaIdade); 
System.out.printf("Meu nome = %.2s%n", meuNome); 
System.out.printf("Primeira letra = %C", gremio); 
