# ⚡ Pokedex Explorer

![Badge Status](https://img.shields.io/badge/Status-Concluído-success)
![Badge Framework](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white) 
![Badge Linguagem](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)

## 📖 Sobre o Projeto

O **Pokedex Explorer** é uma Single Page Application (SPA) desenvolvida para explorar o universo Pokémon através do consumo da [PokéAPI](https://pokeapi.co/). O projeto foca em oferecer uma interface interativa onde os usuários podem listar, buscar e analisar dados detalhados de diversas criaturas.

Este projeto foi construído para demonstrar habilidades sólidas no desenvolvimento front-end, incluindo manipulação complexa de arrays, gerenciamento de estado reativo, requisições HTTP assíncronas e cálculos dinâmicos baseados no retorno da API.

## ✨ Funcionalidades

- **Listagem Dinâmica:** Exibição inicial de um catálogo com 151 Pokémons.
- **Busca Integrada:** Campo de input para filtrar e encontrar Pokémons específicos rapidamente.
- **Visualização de Detalhes:** Ao selecionar um Pokémon, o sistema realiza uma nova requisição para carregar dados aprofundados (tipos, habilidades e sprites).
- **Cálculo de Poder (Base Stats):** Algoritmo que intercepta os atributos (`base_stats` contidos na propriedade `stats`) e realiza a soma total do poder do Pokémon selecionado, exibindo o resultado em tela.
- **Sistema de Batalha/Comparação (Recurso Extra):** Funcionalidade que permite selecionar dois Pokémons simultaneamente para comparar qual deles possui a maior soma total de *Base Stats*.

## 🛠️ Tecnologias e Ferramentas

- **Angular:** Estruturação da aplicação e componentização.
- **TypeScript:** Tipagem estrita de dados e interfaces para os retornos da API.
- **RxJS:** Tratamento do fluxo de dados assíncronos e encadeamento de requisições.
- **HTML5 & CSS3/SCSS:** Construção de layout criativo com foco em usabilidade.

## 🏗️ Destaques Técnicos

Durante o desenvolvimento, as seguintes práticas foram priorizadas:

- **Separação de Responsabilidades:** Criação de serviços dedicados apenas para a comunicação com a PokéAPI.
- **Manipulação de Arrays:** Uso intensivo de métodos nativos do JavaScript/TypeScript para filtrar, mapear e reduzir (`reduce`) os dados recebidos, especialmente no cálculo dos status.
- **Clean Code:** Estrutura de pastas organizada e código legível, facilitando a manutenção e escalabilidade.

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos
- [Node.js](https://nodejs.org/en/)
- [Angular CLI](https://angular.io/cli) instalado globalmente.

### Rodando a aplicação

```bash
# Clone este repositório
git clone https://github.com/SeuUsuario/pokedex-explorer.git

# Acesse a pasta do projeto
cd pokedex-explorer

# Instale as dependências
npm install

# Inicie a aplicação
ng serve
Acesse http://localhost:4200 no seu navegador para ver a aplicação rodando.
```
## 🤝 Desenvolvedor Criado por Esdras Lima
[LinkedIn](https://www.linkedin.com/in/esdrasdev/)
[GitHub](https://github.com/esdraslimaff)
