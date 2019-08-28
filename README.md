Configurações

 - Editar o `.github/CODEOWNERS` e deixar apenas os times relevantes para o projeto
 - Entrar no CircleCi e ativar os builds para esse projeto
 - Conferir que os dados foram enviados ao codecov.io

# Nome do Projeto

Descrição breve sobre o projeto


# Variáveis de ambiente

|   Variável    |        Descrição         | Valor padrão |
|:-------------:|:-------------------------|:------------:|
| `B2WADS_PORT` | Porta padrã da aplicação |    `3000`    |

# Como rodar
```sh
npm start
```

# Como rodar os testes
```sh
npm test
```

# Scripts
- `cron:<cron-name>`: Inicia script de tarefa agendada
- `codecov`: Envia métricas de code coverage para o [codecov.io](codecov.io)
- `deps`: Inicializa as dependências de desenvolvimento do projeto
- `fix:<fix-name>`: Executa script de correção
- `fmt`: Formata código segundo estilo definido em [.prettierrc](.prettierrc) e [.eslintrc](.eslintrc)
- `fmt:check`: Verifica se o código segue o padrão de estilo
- `start`: Inicia a aplicação
- `test`: Executa todos os testes
- `test:acceptance`: Execute testes de aceitação
- `test:integration`: Executa testes de integração
- `test:unit`: Execute testes unitários
- `worker:<worker-name>`: Incia worker
