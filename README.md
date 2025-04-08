# Simple Authentication System

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📋 Sobre o Projeto

Um sistema de autenticação básico construído com Laravel.

## ✨ Funcionalidades

-   ✅ Registro de usuários
-   ✅ Login e logout
-   ✅ Gerenciamento de perfil
-   ✅ Verificação de e-mail
-   ✅ Recuperação de senha
-   ✅ Validação de formulários
-   ✅ Interface responsiva
-   ✅ Proteção contra CSRF
-   ✅ Hash seguro de senhas

## 🛠️ Tecnologias Utilizadas

-   **Backend:**

    -   Laravel 10
    -   PHP 8.2
    -   MySQL/SQLite

-   **Frontend:**

    -   Blade Templates
    -   Bootstrap 5
    -   JavaScript Vanilla

-   **Autenticação:**

    -   Laravel Breeze
    -   Laravel Sanctum

-   **Validação:**
    -   Laravel Request Validation

## 📦 Pré-requisitos

-   PHP 8.2 ou superior
-   Composer
-   MySQL ou SQLite
-   Node.js e NPM
-   Git

## 🚀 Instalação

1. Clone o repositório:

```bash
git clone git@github.com:PatriciaLisboa/simple-authentication.git
cd simple-authentication
```

2. Instale as dependências PHP:

```bash
composer install
```

3. Instale as dependências JavaScript:

```bash
npm install
```

4. Copie o arquivo de ambiente:

```bash
cp .env.example .env
```

5. Gere a chave da aplicação:

```bash
php artisan key:generate
```

6. Configure o banco de dados no arquivo `.env`:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nome_do_banco
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha
```

7. Execute as migrações:

```bash
php artisan migrate
```

8. Compile os assets:

```bash
npm run build
```

## 🏃‍♂️ Executando o Projeto

1. Inicie o servidor de desenvolvimento:

```bash
php artisan serve
```

2. Login:

```
http://127.0.0.1:8000/login
```

3. Register:

```
http://127.0.0.1:8000/register
```

4. Dashboard:

```
http://127.0.0.1:8000/dashboard (após fazer login)
```

## 🔒 Segurança

-   Senhas são hasheadas usando bcrypt
-   Proteção CSRF implementada
-   Validação de formulários
-   Verificação de e-mail obrigatória
-   Gerenciamento seguro de sessões

## 📝 Testes

Para executar os testes:

```bash
php artisan test
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
