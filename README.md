<h1 align="center">:notes: Music Player</h1>

## :memo: Descrição
Projeto de desenvolvimento de um tocador de músicas utilizando a linguagem de programação c++.

## :computer: Funcionalidades
* <b>Adiciona músicas em uma biblioteca</b>
* <b>Remove músicas de uma biblioteca</b>
* <b>Mostra todas as músicas na biblioteca</b>
* <b>Cria uma playlist</b>
* <b>Adiciona, remove, muda a posição e mostra as músicas em uma playlist</b>

## :wrench: Tecnologias utilizadas
* Cmake;
* Doxygen;

## :cd: Rodando o projeto
Depois de descompactar o arquivo compactado, abrir o terminal na pasta descompactada e dar o seguinte comando para iniciar o projeto:
```
$ make
```
(assumindo que $ seja o prompt do terminal). Em seguida:
```
$ ./musicplayer
```
## :soon: Roteiro (exemplos)
A seguir, exemplos de como prosseguir na aplicação:
```
        ----------------
       |  Music Player  |
        ----------------

 ------------------------------
| a - Add song to library      |
| r - Remove song from library |
| s - Songs in the library     |
| p - Add playlist             |
| q - Quit                     |
 ------------------------------

Choose an option: 
```
Escolhendo as opções a, r, s ou p, é possível prosseguir para adição e remoção de músicas na biblioteca, listagem das músicas e adição de uma playlist.
Selecionando 'q', o programa é finalizado.
Pressionando 'a', temos:
```
 -------------
| Adding song |
 -------------

Enter song's name: 

```
Pressionando 'r', temos:
```
 ---------------
| Removing song |
 ---------------

Enter the song you want to remove: 
```
Pressionando 's', temos (após adicionar três músicas:
```
 -----------------------
| Songs in this library |
 -----------------------

1. Speechless - Morning Parade
2. Fake Plastic Trees - Radiohead
3. Last Kiss - Pearl Jam
```
Pressionar 'p' abre a opção de criar uma playlist, após dar um nome para ela:
```
Relax's Menu
 -----------------------------
| a - Add song                |
| r - Remove song             |
| c - Change position of song |
| s - Songs in the playlist   |
| q - Return                  |
 -----------------------------

Choose an option: 
```
As opções são basicamente iguais as anteriores, com exceção da 'c', que possibilita mover as músicas.
## :triangular_flag_on_post: Dificuldades encontradas
* Não consegui implementar a possibilidade de criação de múltiplas playlists, assim como a remoção delas.

## :robot: Responsável pelo projeto
Eu (Raquel Cavalcante) e a internet. Perdi a conta da quantidade de sites que visitei para finalizar isso.

## :heavy_check_mark: :x: Status do projeto
Precisando melhorar, mas finalizado.
