# Laboratório 5 - Programa 4  :computer:
*O objetivo deste exercício é colocar em prática conceitos de containers, iteradores e algoritmos da STL (Standard Template Library) na linguagem de programação C++*

* :bust_in_silhouette: _Aluno: **Leonardo dos Santos Matos**
* :pencil:  _Matrícula: **20160143879**
 
## Explicando
1. Preenche o vector col com valores de 1 a 9
2. Usa a função da STL *transform* que modifica os vaores com as funções *back_inserter* e *square*
3. Imprime os valores dos elementos de col2 com espaços entres eles

A função *transform* recebe um range de valores. Usa *square*, que calcula o quadrado dos valores dos elementos, e insere, com o *back_inserte*, os valores modificados no col2

Valores de col: 1 2 3 4 5 6 7 8 9
Valores de col2: 1 4 9 25 36 49 64 e 81