**Lista 1 - Aplicação de grafos na geração de labirintos em PDF** 
=========================
Welison Lucas Almeida Regis - 2019.1

Lieverton Santos Silva - 2019.1

## PROPOSTA

- Utilizou-se o algoritmo de **Depth-Fist-Search (DFS)** para gerar um labirinto aleatório.
- Apresenta-se graficamente o labirinto e sua solução, além dos backtracks realizados pelo algoritmo, tudo com a bibliteca de jogos **pygame**.
- Ao gerar o labirinto o usuário tem a opção de jogar, mostrar, ou resolução e expotar o labirinto como **PNG**/ **PDF**.   

* O algoritmo desenvolvido baseia-se no pseudocódigo de geração de labirintos disponível na [Wikipedia](https://www.wikiwand.com/en/Maze_generation_algorithm).

![Imgur](https://i.imgur.com/Ua6p9LO.png)

## PRÉ-REQUISITOS

Para testar a aplicação, execute os seguintes passos:

1. Faça uma cópia do repositório para o seu computador em um lugar de sua preferência.
	* Através do _git_, faça um _git clone_:

```
    $ git clone https://github.com/projeto-de-algoritmos/Lista1_Lieverton_Welison
```

2. Entre na pasta do projeto:
```
    $ cd Lista1_Lieveton_Welison
```

3. O projeto utiliza algumas bibliotecas. Portanto, instale-as através do comando:
```
    $ pip install -r requirements.txt
```

- Caso tenha problemas com o comando acima, instale manualmente com o `pip` os pacotes: `pygame`, `Pillow` e `img2pdf `.
- Versão python utilizado: `Python v3.7`.

## ACESSE O PROJETO

Para , execute os seguintes passos:
1. Faça uma cópia do repositório para o seu computador em um lugar de sua preferência.
	* Através do _git_, faça um _git clone_:

```
    $ git clone https://github.com/projeto-de-algoritmos/Lista1_Lieverton_Welison
```

2. Entre na pasta do projeto:
```
    $ cd Lista1_Lieverton_Welison/src
```

## EXECUÇÃO

- Na pasta `Lista1_Lieverton_Welison/src` do projeto:
  - `$ python3 main.py`

## INSTRUÇÕES

- Escolha a largura (1-50) e a altura (1-30) do _grid_.
- Aperte ↑ (seta para cima) para aumentar a velocidade da animação.
- Aperte ↓ (seta para baixo) para diminuir a velocidade da animação.
- Após gerar o labirinto digite o número da opção desejada:

    | |opções:      |
    | :---: | :---: |
    | 1 | exportar  |
    | 2 | jogar     |
    | 3 | resolver  |
    | 0 | sair      |
