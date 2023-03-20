# Dissecando-uma-variavel
Testes com tipos primitivos.

Caso você não especifique o tipo primitivo o resultado sempre será "str", porque a função input sempre retorna a "string", indenpendente do tipo.
Agora para testar se o que foi digitado mesmo sendo string pode ser um número, por exemplo:

a = input('Digite algo: ')
print('O tipo primitivo desse valor é ', type (a))
print('Só tem espaços? ', a.isspace())
print('É um número? ' a.issnumeric())
print('É alfabético? ', a.isaplha())
print('É alfanúmerico? ', a.isalnum())
print('Está em maiúsculas? ', a.isupper())
print('Está em minúsculas? ', a.islower())
primt('Está capitalizada? ', a.istitle())

O "a" é sempre o que chamamos de objeto, todo objeto tem características e realiza funcionaliadde, eles têm atributos e metódos, no caso de tudo escrito
acima, como tem parênteses() depois de cada um deles, estamos trabalho "métodos", todo objeto "string" têm esses métodos.
