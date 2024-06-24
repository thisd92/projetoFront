# Projeto Frontend - Consumo de API CRUD

Este repositório contém o código-fonte de um projeto em React com Vite, que consome a API Rest de CRUD (Create, Read, Update, Delete) para gerenciamento de Estados, Cidades e Prefeitos. Este frontend foi desenvolvido para atender ao backend do exercício de desenvolvimento web do curso da Cod3r.

## Tecnologias Utilizadas

- **React**: Biblioteca para construção de interfaces de usuário.
- **Vite**: Ferramenta de build e desenvolvimento rápido para projetos front-end.
- **Axios**: Biblioteca para realizar requisições HTTP.

## Funcionalidades

- **Página Principal**: Apresenta três botões: Estados, Cidades e Prefeitos.
- **Componentes Dinâmicos**: Ao clicar em uma das opções, abre o respectivo componente para cadastro ou consulta dos dados.
- **CRUD**: Permite criar, ler, atualizar e deletar Estados, Cidades e Prefeitos.

## Configuração do Ambiente de Desenvolvimento

### Pré-requisitos

- Node.js
- NPM ou Yarn

### Instalando Dependências
Execute o comando abaixo para instalar as dependências do projeto:
```
npm install
```
ou
```
yarn install
```

## Executando o Projeto
Execute o comando abaixo para iniciar o servidor de desenvolvimento:
```
npm run dev
```
ou
```
yarn dev
```
A aplicação estará disponível em http://localhost:3000.

## Estrutura dos Componentes
### src/assets/css
Contém os arquivos de estilos utilizados na aplicação.

### src/components/buttons/
Componentes de botões utilizados na aplicação.

### src/components/cidade/
Componentes relacionados ao gerenciamento de Cidades.

### src/components/estado/
Componentes relacionados ao gerenciamento de Estados.

### src/components/modals/
Componentes de modais utilizados para interações na aplicação.

### src/components/prefeito/
Componentes relacionados ao gerenciamento de Prefeitos.

### src/models/
Modelos TypeScript para as entidades Cidade (cidade.ts), Estado (estado.ts) e Prefeito (prefeito.ts).

### src/services/service.ts
Serviço para chamadas API utilizando a biblioteca Axios. Contém constantes para operações de get, save, update e delete.

### src/utils/request.ts
Contém a constante BASE_URL que é utilizada nos serviços para realizar as requisições à API.

## Contribuição
Se você quiser contribuir com este projeto, sinta-se à vontade para fazer um fork do repositório, criar uma branch com suas alterações e enviar um pull request.

## Licença

Este projeto está licenciado sob licença MIT. Consulte o arquivo LICENSE para obter mais informações.
