# Algoritmi

## Insertionsort:

Inserisco il nuovo elemento nella posizione corretta, a sinistra dell'elemento corrente gli altri elementi sono già ordinati. Finché non trovo valori maggiori, continuo a spostare l'elemento a sinistra fino alla posizione corretta

```
Insertionsort(A)
    for i = 2 to A.length
        key = A[i]
        j = i - 1
        while j > 0 and A[j] > key
            A[j + 1] = A[j]
            j = j - 1
        A[j + 1] = key
```

Esempio:

## Mergesort

Spezzetto ricorsivamente a metà l’array fino a trovare una porzione riordinata, (ovvero l’elemento singolo) per poi ricostruirlo ripercorrendo al contrario la ricorsione e unendo le varie parti con la procedura Merge
 



## Red-Black Tree

è un BST con nodi black o red
- foglie: black NIL
- se un nodo è red, i suoi figli sono black
- ogni cammino da un nodo a una foglia NIL ha lo stesso numero di nodi