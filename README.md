# ***Jogo Quake III Arena -----  quakeParser***
Analisador para arquivo de log do quake 3 arena.
https://github.com/HRROGERIO/parser

<h3> ***Configuração ***</h3>
a- Importar o projeto como Maven Project.</br>
b- Executar a Classe Principal "Parser.java".

<h3>***RELATÓRIOS - ARQUIVOS***</h3>
  Após a execução da Classe Principal será criado 3 arquivos na pasta do projeto:</br>
analisador_.txt (Task 1)</br>
gamesrelatorio_.txt (Task 2)</br>
relatoriomortes_.txt (Plus)</br>

<h3>***SOBRE Quake III Arena***</h3>
  A classe Parser possui o método "parse" que lê o arquivo de log "games.log" e coleta as informações de cada jogo retornando uma lista de Games.</br>
  Os métodos createLogParser, report e meansOfDeath recebem a lista de games e são responsavéis por criarem os arquivos correspondentes aos resultados.
