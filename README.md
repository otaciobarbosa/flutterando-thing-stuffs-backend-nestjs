# CRUD Completo com NestJS (Backend)

Este é o projeto de backend desenvolvido por Jacob Moura da Flutterando que faz parte do CRUD Completo com Flutter e NestJS. O backend é construído utilizando o framework NestJS, com suporte para Firebase, Docker e MySQL.

## Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes pré-requisitos instalados:

- Node.js (versão 14 ou superior)
- npm (gerenciador de pacotes do Node.js)
- Docker (para executar o banco de dados MySQL)
- MySQL (pode ser executado através do Docker)

## Instalação e Configuração

Siga os passos abaixo para configurar o projeto backend:

### Passo 1: Clonando o Repositório

Clone o repositório do projeto em seu ambiente local:

```bash
git clone https://github.com/Flutterando/crud_completo.git
```

### Passo 2: Acessando a Pasta do Backend

Acesse a pasta do projeto backend:

```bash
cd crud_completo/backend_nestjs
```

### Passo 3: Instalando as Dependências

Instale as dependências do projeto:

```bash
npm install
```

### Passo 4: Configurando o Banco de Dados

Certifique-se de ter o Docker instalado e em execução. Em seguida, execute o seguinte comando para criar e executar uma instância do banco de dados MySQL:

```bash
docker-compose up -d
```

### Passo 5: Configurando as Variáveis de Ambiente

Renomeie o arquivo `.env.example` para `.env` e atualize as variáveis de ambiente, se necessário. Por padrão, o arquivo `.env` deve estar configurado corretamente para funcionar com o Docker e o banco de dados MySQL.

### Passo 6: Executando o Servidor

Agora você está pronto para executar o servidor NestJS:

```bash
npm run start:dev
```

O servidor será iniciado e estará ouvindo as requisições na porta especificada no arquivo `.env`.

## Recursos e Vídeos Relacionados

O projeto backend está integrado ao frontend Flutter e oferece as funcionalidades de CRUD para o aplicativo. Se você quiser entender melhor o funcionamento do frontend e sua integração com o backend, confira os vídeos da lista de reprodução:

[CRUD Completo com Flutter e NestJS - Lista de Reprodução](https://www.youtube.com/playlist?list=PLlBnICoI-g-chYzyBQQgFDOVrkpqIfIyL)

## Contribuição

Se encontrar problemas ou quiser contribuir com o projeto, sinta-se à vontade para abrir uma *issue* ou um *pull request* no repositório do [GitHub](https://github.com/Flutterando/crud_completo).

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](https://github.com/Flutterando/crud_completo/blob/master/LICENSE) para detalhes.