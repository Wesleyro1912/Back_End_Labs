# 📌 Descrição

<!-- Explique de forma clara e objetiva o que este PR faz -->

Exemplo:
- Adiciona endpoint para cadastro de usuários
- Ajusta validação no login
- Atualiza documentação da API

---

# ✅ Tipo de Mudança

Marque com um `x` o que se aplica:

- [ ] **feat:** Nova funcionalidade
- [ ] **fix:** Correção de bug
- [ ] **docs:** Mudança apenas na documentação
- [ ] **style:** Alterações de formatação/código (sem impacto na lógica)
- [ ] **refactor:** Refatoração de código (sem mudança de funcionalidade)
- [ ] **test:** Adição/ajuste de testes
- [ ] **chore:** Tarefas de manutenção

---

# 🔎 Como Testar

<!-- Descreva os passos para validar esta mudança -->

1. Clonar este branch
2. Rodar `composer install` (se necessário)
3. Subir o servidor `php artisan serve`
4. Testar o endpoint `POST /api/users` com os dados:
   ```json
   {
     "name": "Wesley",
     "email": "wesley@codareelo.com",
     "password": "123456"
   }
