# Android Meetup - 4 anos

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

## Rodando localmente

Coloque o site no ar na sua máquina com

```
gulp server
```

1) Gulp não irá fazer live-reloading de alterações relacionadas à imagens (exclusão, adição ou troca de arquivos)

2) A maioria das tarefas de inclusão de dados está relacionada aos arquivos no diretório `data`

* Após as alterações concluídas, submeta seu PR

## Deploy

Basta executar

```
gulp deploy
```

Os deploys deverão ser gerados a partir do branch master atualizado