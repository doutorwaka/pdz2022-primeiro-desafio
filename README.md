# Curso Programado do Zero 2022
## Primeiro Desafio
### Desafio 1

Neste desafio, você precisa implementar um programa em C ou C++ cujo qual em sua chamada de execução, o programa receberá o nome de dois arquivos de textos por parâmetro. A chamada ficará como segue:

```
[nome_do_executável] [nome do primeiro arquivo] [nome do segundo arquivo]
```

Por exemplo, se o executável se chamar **exec.exe** e os arquivos de textos chamarem **entrada.txt** e **saida.txt** respectivamente, a chamada ficará da seguinte maneira:

```
exec.exe entrada.txt saida.txt
```

O programa em C/C++ irá ler um vetor de inteiros do arquivo de entrada. Em seguida, ele deve fazer uma chamada a um segundo programa em JAVA, passando o vetor por parâmetro na chamada. O programa JAVA irá verificar se existe pelo menos um número repetido entre os inteiros. Caso tenha algum repetido, ele irá escrever no arquivo de saída **repetição detectada**. Caso não haja, ele irá escrever no arquivo de saída **não encontrado repetição**. É importante que o **seu algoritmo possua complexidade O(n)** onde **n** é a quantidade de números lido no arquivo de entrada.

*Dica 1: Você precisará utilizar as variáveis ***args*** da função main do C++ e do JAVA.*

*Dica 2: Seu programa ficará ***dependente de SO***. Quer dizer, para fazer uma chamada do programa C++ para o programa JAVA, você precisará fazer uma chamada de sistema.*

*Dica 3: Você precisará gerar um executável JAVA.*

### Desafio 2

Neste desafio, 