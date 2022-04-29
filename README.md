## Python-ex
#### exercícios de Python (Do inicio do aprendizado até atualmente).
##### Ínicio no dia 12/02

### Aulas:
-----------------------------
print: escreva
input: leia

operadores aritmético:
+ (adição)
- (subtração)
* (multiplicação)
/ (divisão)
** (potência)
// (divisão inteira)
% (resto da divisão)
** (1/2) ou pow(x, (1/2)) = raiz quadrada

operadores aritmético (ordem):

1 - ()

2 - **

3 - *, /, //, %

4 - +, -

alinhamento dentro do {}:

{:>} - alinhado a direita
{:<} - alinhado a esquerda
{:^} - centralizado


import (biblioteca) - importar (tudo)
from (biblioteca) import xxxx - importar certos itens

ex: math (biblioteca de matemática)

math - 
ceil: arredonda para cima
floor: arredonda para baixo
trunc: nao faz arredondamento
pow: potencia
sqrt: raiz quadrada
factorial: calculo fatorial

lista = [...]


aula09 - 

fatiamento -
frase[9] - 9 letra
frase [9:13] - nao pega o 13
frase [9:21:2] - pula de dois em dois
frase [:5] - começa no inicio e vai até o caracter escolhido
frase [15:] - do caracter inicial até o fim
frase [9::3] - começa no 9 vai até o fim pulando de 3 em 3

análise - 
len(frase) - mostra o tamanho da frase em caracter
frase.count('o') - contar quantas vezes aparece a letra entre ('')
ou frase.count('o', 0, 13) - ve a letra e já fatia
frase.find('deo') - mostrar a posição das letras entre ('')
frase.find('xxx') - valor que não existe -1
'curso' in frase - existe xxxxx em xxxxx

Transformação - 
frase.replace('Python', 'Android') - substitui a palavra
frase.upper() - vai ficar maiusculo
frase.lower() - vai ficar minusculo
frase.capitalize() - Só o primeiro caracter em maiusculo
frase.title() - Tranformar os primeiros caracteres em maiusculo
frase.strip() - remove espaços inuteis
frase.rstrip() - remove espaços do lado direito
frase.lstrip() - remove espaços da esquerda

Divisão - 
frase.split() - divisão considerando os espaços / recomeça a contagem e gera outra lista

Junção - 
'-'.join(frase) - Juntar toda a frase usando o separador '-'




