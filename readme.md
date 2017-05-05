# Android Meetup - 4 anos

[![Status](https://travis-ci.org/gdg-sp/am4anos.svg?branch=master)](https://travis-ci.org/gdg-sp/am4anos)  

## Instruções básicas

* Clone esse repositório

```
git clone <this.repo.git>
cd am4anos
```

* Instale as dependências

```
npm install
```

## Rodando localmente e contribuindo

Coloque o site no ar na sua máquina com

```
gulp server
```

1) Gulp não irá fazer live-reloading de alterações relacionadas à imagens (exclusão, adição ou troca de arquivos)

2) A maioria das tarefas de inclusão de dados está relacionada aos arquivos no diretório `data`

* Após as alterações concluídas, submeta seu PR

## Deploy

TravisCI irá gerar um deploy de forma automática toda vez que o branch `master` for atualizado. Se for preciso fazer um deploy da sua máquina, execute

```
gulp deploy
```