# Unistock

O Unistock é uma aplicação web de página única (SPA - Single Page Application) construída com Laravel, Vue.js, Inertia.js e Tailwind CSS. Esta plataforma foi desenvolvida como um projeto durante nossa graduação na Unicentro e é um sistema de gerenciamento de estoque simples e eficiente que ajuda pequenas e médias empresas a gerenciar seu estoque.

---

## Histórico do Projeto

O Unistock foi desenvolvido como parte de um projeto principal para nossa graduação. O projeto foi feito em dupla por nós, Gabriel Marochi Schmidt e Gabriel do Nascimento de Lima, e representa o ápice de nossos estudos e nossa paixão compartilhada pelo desenvolvimento de software. Juntos, projetamos e implementamos uma solução para abordar desafios do mundo real no gerenciamento de estoque, incorporando tecnologias de ponta e boas práticas.

---

## Tecnologias Utilizadas (Tech Stack)

- **Backend**: Laravel 10
- **Frontend**: Vue 3, Tailwind CSS, Element Plus, Flowbite
- **Manipulação de SPA**: Inertia.js
- **Autenticação**: Laravel Breeze
- **Banco de Dados**: PostgreSQL
- **Ferramentas**: Composer, NPM, Vite

---

## Funcionalidades

- **Gerenciamento de Estoque**: Adicione, edite, remova e monitore itens do estoque com facilidade, incluindo quantidade, categoria e localização.
- **Gerenciamento de Fornecedores**: Cadastre, edite e gerencie dados de fornecedores, vinculando-os a itens de estoque específicos.
- **Autenticação e Autorização de Usuários**: Login seguro utilizando Laravel Breeze e *policies* (políticas de acesso).
- **Interface de Usuário Moderna**: Construída com Vue 3, Tailwind CSS, Element Plus e Flowbite para uma interface limpa e responsiva.
- **Integração com Inertia.js**: Experiência de aplicação de página única (SPA) fluida, sem a necessidade de construir uma API separada.
- **Design Responsivo**: Otimizado para uso em desktops, tablets e celulares.
- **Seeders e Factories**: Popule rapidamente o banco de dados para desenvolvimento e testes usando *seeders* e *factories*.

---

## Instalação

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/GabrielNLima/ProjetoIntegrador-III.git](https://github.com/GabrielNLima/ProjetoIntegrador-III.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd ProjetoIntegrador-III
    ```
3.  Instale as dependências:
    ```bash
    composer install
    npm install
    ```
4.  Configure as variáveis de ambiente:
    ```bash
    cp .env.example .env
    ```
    Atualize o arquivo `.env` com as configurações do seu banco de dados e outras informações necessárias.

5.  Gere a chave da aplicação:
    ```bash
    php artisan key:generate
    ```
6.  Execute as migrações do banco de dados:
    ```bash
    php artisan migrate
    ```

---

## Uso

1.  Inicie o servidor de desenvolvimento:
   
    ```bash
    php artisan serve
    ```
2.  Em outro terminal, inicie o servidor de desenvolvimento do frontend:
   
    ```bash
    npm run dev
    ```
3.  Acesse a aplicação em `http://localhost:8000`.

---

## Contribuições

Contribuições são bem-vindas! Por favor, siga o [guia de contribuição](https://laravel.com/docs/contributions) e adira ao [código de conduta](https://laravel.com/docs/contributions#code-of-conduct).

---

## Licença

Este projeto é um software de código aberto licenciado sob a [licença MIT](https://opensource.org/licenses/MIT).
