# Atividade de Avalição VI

Este repositório contém exercícios realizados na FATEC SJC - Atividade de Avaliação 6 – Estruturas de Dados.

# Respostas

1) Considerando a lista representada na Figura 4 e que 1ª
instrução a seguir irá imprimir o valor 11. Marque a
alternativa que contém o valor a ser impresso ao
executar a 2ª instrução.
System.out.println( no.conteudo );
System.out.println( no.proximo.proximo.conteudo );

R: Considerando que a primeira irá imprimir 11, o próximo da figura está no endereço e40,
portanto o no.proximo = 4 e o no.proximo.proximo(e40) = 9. A resposta é letra C.


2) Considerando a lista representada na Figura 4 e que 1ª
instrução println a seguir irá imprimir o valor 11.
Marque a alternativa que contém o valor a ser impresso
ao executar a 2ª instrução println.
No temp = no.proximo; //e40 conteudo 4
System.out.println( no.conteudo ); //11
lista.remover(temp.conteudo); // 4
System.out.println( no.proximo.proximo.conteudo );

R: 
