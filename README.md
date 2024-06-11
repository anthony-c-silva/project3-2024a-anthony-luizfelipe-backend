# Stock Control Shelters

Este projeto é um sistema de controle de estoque para abrigos, desenvolvido em Node.js utilizando Express e Sequelize para interação com um banco de dados PostgreSQL.

## Índice

- [Instalação](#instalação)
- [Configuração](#configuração)
- [Endpoints](#endpoints)
  - [Abrigos](#abrigos)
  - [Itens](#itens)
  - [Usuários](#usuários)
  - [Doações](#doações)
- [Execução](#execução)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/project3-2024a-anthony-luizfelipe-backend.git
   cd project3-2024a-anthony-luizfelipe-backend

2. Instale as dependências:

   npm install

## Configuração 

1. Configure o arquivo config/database.js com suas credenciais do PostgreSQL:

    module.exports = {
        username: 'seu_usuario',
        password: 'sua_senha',
        database: 'nome_do_banco',
        host: 'localhost',
        dialect: 'postgres',
    };

2. Certifique-se de que o banco de dados PostgreSQL esteja rodando e que as tabelas sejam criadas automaticamente quando a aplicação iniciar.

## Endpoints