# 📝 COLINHA DE COMMITS (PADRÃO PROFISSIONAL)

## 🚀 FORMATO PADRÃO

```bash
tipo(escopo): descrição curta
```

### 📌 EXEMPLOS:

```bash
feat(mobile): adiciona tela de login
fix(api): corrige erro no cadastro de usuário
style(web): ajusta cores do dashboard
refactor(backend): melhora organização dos controllers
```

---

# 🧠 TIPOS DE COMMIT

## ✨ feat

👉 Nova funcionalidade

```bash
feat(mobile): cria tela de cadastro
feat(api): adiciona rota de login
```

---

## 🐛 fix

👉 Correção de bug

```bash
fix(mobile): corrige erro ao clicar no botão
fix(api): resolve falha na autenticação
```

---

## 🎨 style

👉 Apenas visual (sem mudar lógica)

```bash
style(web): altera cores do dashboard
style(mobile): ajusta padding da tela
```

---

## ♻️ refactor

👉 Melhoria no código (sem mudar comportamento)

```bash
refactor(api): reorganiza estrutura de rotas
refactor(mobile): melhora reutilização de componentes
```

---

## 📚 docs

👉 Documentação

```bash
docs: adiciona guia de instalação
docs: atualiza README
```

---

## 🧪 test

👉 Testes

```bash
test(api): adiciona teste de login
test(mobile): testa fluxo de cadastro
```

---

## 🔧 chore

👉 Configuração / manutenção

```bash
chore: atualiza dependências
chore: configura eslint
```

---

## ⚡ perf

👉 Melhoria de performance

```bash
perf(api): melhora tempo de resposta da consulta
```

---

## 🔥 remove

👉 Remoção de código/arquivo

```bash
remove(api): remove rota antiga
```

---

## 🚧 wip (evitar em produção)

👉 Trabalho em progresso

```bash
wip(mobile): tela de login em andamento
```

---

# 📦 ESCOPO (MUITO IMPORTANTE)

👉 Indica ONDE foi feita a alteração:

| Escopo        | Uso             |
| ------------- | --------------- |
| mobile        | app mobile      |
| web           | frontend web    |
| api / backend | backend         |
| hardware      | arduino / esp32 |
| db            | banco de dados  |

---

# 🏆 EXEMPLOS REAIS 

```bash
feat(mobile): adiciona tela de boas-vindas
feat(api): cria endpoint de refeições
fix(mobile): corrige envio de dados da refeição
style(web): melhora layout do dashboard
refactor(api): separa lógica de análise
chore: configura projeto inicial
docs: cria guia de uso do sistema
```

---

# ⚠️ BOAS PRÁTICAS

✔️ Sempre usar verbo no presente
✔️ Ser direto (sem texto gigante)
✔️ Um commit = uma responsabilidade
✔️ Evitar "commit lixo":

❌ errado:

```bash
git commit -m "arrumei coisas"
```

✔️ correto:

```bash
git commit -m "fix(api): corrige erro no cadastro de criança"
```

---

# 🔥 PADRÃO TOP (OPCIONAL)

👉 Commit com mais detalhes:

```bash
feat(api): adiciona endpoint de login

- valida email e senha
- retorna token JWT
- trata erro de usuário inválido
```

---

# 🇧🇷 REPOSITÓRIOS (PT-BR)

👉 Guia em português:
🔗 https://github.com/iuricode/padroes-de-commits

👉 Outro muito bom:
🔗 https://github.com/renatodev/conventional-commits

👉 Documentação oficial:
🔗 https://www.conventionalcommits.org/pt-br/v1.0.0/

---

# 🚀 RESUMÃO

```bash
feat → nova funcionalidade
fix → bug
style → visual
refactor → melhoria interna
docs → documentação
test → testes
chore → config
perf → performance
remove → remover
```


## Nossas branches
```
feature/mobile-auth  
feature/mobile-crianca  
feature/mobile-refeicao  
feature/mobile-historico  
feature/mobile-dashboard  
feature/mobile-bluetooth  

feature/web-dashboard  
feature/web-relatorios  
feature/web-terapeuta  

feature/backend-crianca  
feature/backend-alimento  
feature/backend-refeicao  
feature/backend-analises  
feature/hardware-leitura  
feature/hardware-bluetooth  

docs/documentacao  
chore/configuracao-projeto

```