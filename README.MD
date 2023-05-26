# Print Directory Tree

 [![GitHub](https://img.shields.io/badge/Visit-My%20Profile-0891B2?style=flat-square&logo=github)](https://github.com/Tgentil)

Este script em Python tem como objetivo criar uma árvore de diretórios a partir do diretório em que o script está sendo executado. A árvore de diretórios é impressa no console, mostrando todos os subdiretórios e arquivos presentes no diretório raiz.

## Como utilizar
Para utilizar o script, basta chamar a função print_directory_tree() com o caminho para o diretório raiz que se deseja imprimir a árvore de diretórios. O script também aceita um segundo argumento opcional, padding, que define o espaçamento utilizado para identar os subdiretórios na impressão da árvore.

## Exemplo de uso
```python
Copy code
from print_directory_tree import print_directory_tree

# Imprime a árvore de diretórios a partir do diretório raiz
print_directory_tree('.')
```

## Saída do exemplo de uso

```
+-- pasta1/
|   +-- arquivo1.txt
|   +-- arquivo2.txt
|   +-- subpasta1/
|   |   +-- arquivo3.txt
|   |   +-- arquivo4.txt
|   +-- subpasta2/
|       +-- arquivo5.txt
+-- pasta2/
|   +-- arquivo6.txt
|   +-- subpasta3/
|       +-- arquivo7.txt
+-- arquivo8.txt
```

## Dependências
Este script utiliza a biblioteca padrão os, que é instalada junto com a instalação padrão do Python.

## Autores

* Thiago da Silveira Gentil
