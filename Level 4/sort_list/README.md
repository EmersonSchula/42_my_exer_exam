## Subject

```
Assignment name  : sort_list
Expected files   : sort_list.c
Allowed functions:
--------------------------------------------------------------------------------

Escreva as seguintes funções:

t_list *sort_list(t_list* lst, int (*cmp)(int, int));

Esta função deve classificar a lista fornecida como parâmetro, usando a função
ponteiro cmp para selecionar a ordem a ser aplicada e retorna um ponteiro para o
primeiro elemento da lista classificada.

Duplicações devem permanecer.

As entradas sempre serão consistentes.

Você deve usar o tipo t_list descrito no arquivo list.h
que é fornecido a você. Você deve incluir esse arquivo
(#include "list.h"), mas não deve entregá-lo. Usaremos o nosso próprio
para compilar sua tarefa.

As funções passadas como cmp sempre retornarão um valor diferente de
0 se a e b estiverem na ordem correta, 0 caso contrário.

Por exemplo, a seguinte função usada como cmp classificará a lista
em ordem crescente:

int ascending(int a, int b)
{
	return (a <= b);
}
```
