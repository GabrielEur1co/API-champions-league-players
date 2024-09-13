# Champions League Players API

Este projeto é uma API CRUD desenvolvida em Node.js com Express, voltada para a gestão de informações de jogadores da Champions League. A API permite criar, ler, atualizar e deletar dados de jogadores, retornando as informações em formato JSON.

## Funcionalidades

- **Criação de Jogadores:** Adicione novos jogadores à base de dados.
- **Leitura de Jogadores:** Consulte as informações de jogadores específicos ou de todos os jogadores cadastrados.
- **Atualização de Jogadores:** Atualize os dados de jogadores existentes.
- **Exclusão de Jogadores:** Remova jogadores da base de dados.

## Tecnologias Utilizadas

- **Node.js:** Plataforma utilizada para o desenvolvimento do backend.
- **Express:** Framework utilizado para a criação da API.
- **Dotenv:** Módulo utilizado para gerenciar variáveis de ambiente.
- **Arquitetura N-Layers:** Aplicação de boas práticas de arquitetura para separar responsabilidades no código.

## Instalação

Siga os passos abaixo para executar este projeto localmente:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/champions-league-players-api.git

2. **Instale as dependências**
    ```
    npm install

3. **Configure as variáveis de ambiente:**

    Crie um arquivo ``.env`` na raiz do projeto e adicione as variáveis necessárias:
    ```
    PORT=3030

4. **Execute a aplicação**`
    ```
    npm run start:wach

    or

    npm run start:dev

## Endpoints
# Abaixo estão listados os principais endpoints da API:

- **GET /players:** Retorna todos os jogadores.
- **GET /players/:id:** Retorna um jogador específico por ID.
- **POST /players:** Adiciona um novo jogador.
- **PUT /players/:id:** Atualiza as informações de um jogador existente.


