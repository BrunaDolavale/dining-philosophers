# O Jantar dos Filósofos

Implementação de programação concorrente em Python

```
O problema do jantar dos filósofos é um exemplo ilustrativo de um problema comum de programação concorrente. É mais um problema clássico de sincronização multi-processo.

O problema pode ser resumido como cinco filósofos sentados ao redor de uma mesa redonda, cada qual fazendo exclusivamente uma das duas coisas: comendo ou pensando. Enquanto está comendo, um filósofo não pode pensar, e vice-versa.

Cada filósofo possui um prato cheio à sua frente. Além disso, um garfo é posicionado entre cada par adjacente de filósofos (portanto, cada filósofo tem exatamente um garfo à sua esquerda e exatamente um garfo à sua direita).

Assume-se que um filósofo necessita de dois garfos para poder comer. E, além disso, um filósofo só pode utilizar um garfo que esteja imediatamente à sua esquerda ou imediatamente à sua direita.

A falta de disponibilidade de garfos é uma analogia à falta de recursos compartilhados em programação de computadores (situação conhecida como concorrência). Travar (lock) um recurso é um técnica comumemente utilizada para assegurar que o recurso está sendo acessado somente por um programa ou trecho de código, por vez. Quando um programa está interessado em um recurso que já foi travado por outro, o programa espera até que ele seja destravado. Quando existem vários programas envolvidos no travamento de recursos, um deadlock pode acontecer, dependendo das circunstâncias.

Para exemplificar, podemos citar um programa que necessita processar dois arquivos. Quando duas instâncias desse programa travam um arquivo cada, ambos os programas esperam o outro destravar o arquivo que falta, o que nunca irá ocorrerá.

Em geral, o problema do jantar dos filósofos é um problema genérico e abstrato que é utilizado para explicar diversas situações indesejáveis que podem ocorrer em problemas que tem como principal idéia a exclusão mútua.
Por exemplo, assim como no caso acima, deadlock/livelock é um conceito que pode ser bem explicado através do problema dos filósofos.

```