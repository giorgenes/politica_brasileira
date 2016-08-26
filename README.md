== O que é

Este projeto é uma tentativa de documentar o cenário político brasileiro
na forma de um grafo.
A ideia é conseguir enxergar melhor as relações e eventos que acontecem entre políticos
e insituições.

== Como gerar o grafo

O grafo pode ser gerado utilizando o graphviz:

```
dot -Tpng main.dot -o politica-brasileira.png
```

== Como contribuir

1. Escolha uma notícia para documentar
2. Coloque o link pra notícia como comentário no arquivo fonte
3. Documente o conteúdo da notícia em forma de grafo
4. Gere o PNG de output e adicione no projeto
5. Faça um pull request

== Grafo atual

![grafo](politica-brasileira.png)
