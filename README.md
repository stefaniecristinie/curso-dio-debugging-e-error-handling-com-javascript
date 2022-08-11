# Curso DIO: Debugging e Error Handling com JavaScript

Atividade: validação de erros por tipo

O objetivo é que a função receba um array e retorne ele caso o seu tamanho corresponda ao número enviado como parâmetro na função. Caso contrário, um erro será lançado.

Criação de uma função que recebe um array e um número.

Realização das seguintes validações:
1. Se os parâmetros não forem enviados, um erro do tipo ReferenceError;
2. Se o array não for do tipo 'object', um erro do tipo TypeError;
3. Se o número não for do tipo 'number', um erro do tipo TypeError;
4. Se o tamanho do array for diferente do número enviado como parâmetro, um erro do tipo RangeError.

Utilização da declaração try...catch.

Filtra as chamadas de catch por cada tipo de erro utilizando o operador instanceof.
