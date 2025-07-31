
# 🚀 Back-end Labs

Sistema base para construção de APIs reutilizáveis com foco em boas práticas, segurança, escalabilidade e integração com projetos administrativos e de e-commerce.

---

## 🎯 Objetivo Geral

Desenvolver uma API modular, segura e reutilizável que sirva como esqueleto para diversos tipos de sistemas — como PDVs, ERPs e e-commerces — com autenticação robusta, controle de permissões e recursos administrativos completos.

---

## 🧰 Tecnologias Utilizadas

- **PHP** 8.x
- **Laravel** 10+
- **MySQL** ou **MariaDB**
- **Composer**
- **JWT** para autenticação (futuramente)
- **Postman** para testes
- **Git** para versionamento
- **Jira** para organização de tarefas

---

## 📂 Como clonar e iniciar o projeto Laravel

Siga os passos abaixo para rodar o projeto localmente:

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/back-end-labs.git
cd back-end-labs
````

### 2. Instalar as dependências com Composer

```bash
composer install
```

> Certifique-se de ter o [Composer](https://getcomposer.org/download/) instalado na máquina.

### 3. Criar e configurar o arquivo `.env`

```bash
cp .env.example .env
```

Em seguida, edite o `.env` com os dados corretos do seu banco de dados:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=backendlabs
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Gerar a chave da aplicação

```bash
php artisan key:generate
```

### 5. Rodar as migrations (criação das tabelas)

```bash
php artisan migrate
```

> Se quiser adicionar dados de teste, use: `php artisan db:seed`

### 6. Rodar o servidor local

```bash
php artisan serve
```

O Laravel estará disponível por padrão em: [http://localhost:8000](http://localhost:8000)

---

## 📦 Funcionalidades Previstas

* Autenticação com token
* Painel de administração com permissões por papel
* Envio interno de e-mails entre usuários
* Auditoria de ações
* Modularização por áreas/sessões
* API padronizada para frontend/mobile

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

## 👨‍💻 Autor

Desenvolvido por Wesley Rodrigues — [LinkedIn](https://www.linkedin.com/in/seu-perfil)

```

Se quiser, posso criar e subir esse arquivo direto em um repositório `.zip`, ou já incluir uma estrutura inicial do projeto Laravel com esse `README.md`. Deseja isso?
```
