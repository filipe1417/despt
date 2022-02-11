
# despt
Antes de tudo, para contato pode utilizar o e-mail: filipe.araujo@ee.ufcg.edu.br ou instagram @filferraraujo

## Tópicos abordados no README

1. [Sobre e como utilizar](#sobre-o-script-e-como-utiliza-lo)
2. [Como contribuir](#como-contribuir)
3. [A fazer](#a-fazer)

## Sobre o script e como utiliza-lo

Esse é um script feito em shell script com objetivo de descompactar arquivos ou diretórios compactados por tar e/ou zip.

#### Como utilizar globalmente

Para utilizar o script de forma global, independente do seu diretório atual e sem executar utilizando o caminho, exemplo ./despt ou ./despt.sh, é preciso realizar alguns passos.
1. Dar permissão de execução para o script, caso não tenha, utilizando o comando chmod +x
2. Mover o script para um diretório presente no seu PATH

### Utilização e exemplos

Uso: ./despt [-h, -V, Arquivo] [Local]

-h, --help      Tela de ajuda sobre o funcionamento do script\
-v, --version   Imprime a versão atual

Ao passar um arquivo como primeiro argumento, será realizada a sua extração para o diretório atual.\
Para que o diretório destino seja alterado, deve-se passa-lo como segundo argumento.

Exemplos: 
* despt -V    Imprime a versão atual
* despt -h    Tela de ajuda
* despt arquivo.tar   Esse "arquivo.tar" será descompactado para meu diretório atual
* despt arquivo.tar diretorioExemplo/   Agora, o "arquivo.tar" será descompactado para o diretório "diretorioExemplo/"
* despt outroArquivo    Descompactação do arquivo "outroArquivo", note que se o nome do arquivo não incluir a extensão, não é um problema.

## Como contribuir

Para contribuir, faça um fork do meu repositório e modifique o que é desejar. Após isso, faça o pull request e será analisado.\
Alguns pontos interessantes para a contribuição mas que não são obrigatórios - visto que ao analisar o request, posso adiciona-los:
* Você pode modificar qualquer coisa do código, sem restrições. Seja para adicionar, modificar ou remover alguma parte.
* Ao modificar o código, adicionar uma nova linha com a versão seguindo o padrão já estabelecido no código: Versão 1.x - Essas mudanças aconteceram
* Pode adicionar o seu nome ou link do github como comentário no início do código, dentro do header comentado, para aparecer como contribuinte

## A fazer

* Excluir código desnecessário
* Adicionar comentários
