# 🚀 COLINHA GIT - USO DIÁRIO (TCC)

## 🟢 COMEÇO DO DIA

```bash
git switch develop
git pull origin develop
```

---

## 🌿 CRIAR / ENTRAR NA FEATURE

```bash
git switch -c feature/nome-da-feature
```

OU (se já existe):

```bash
git switch feature/nome-da-feature
```

---

## 💻 CODANDO...

👉 faz suas alterações normalmente

---

## 💾 SALVAR ALTERAÇÕES

```bash
git add .
git commit -m "feat(escopo): descrição da alteração"
git push
```

---

## 🔁 ABRIR PR (NO GITHUB)

👉 feature → develop
👉 revisar
👉 criar PR
👉 dar merge

---

## 🔄 DEPOIS DO MERGE

```bash
git switch develop
git pull origin develop
```

---

# ⚠️ REGRAS IMPORTANTES

## 🧠 1. SEMPRE:

✔️ começar pela develop
✔️ dar pull na develop

---

## ❌ 2. NUNCA:

❌ codar direto na develop
❌ codar na main

---

## 🌿 3. FEATURE:

✔️ codar nela
✔️ commitar nela
✔️ subir ela

---

## 🔄 4. PULL:

✔️ develop → SEMPRE
✔️ feature → só se necessário

---

## 🚀 FLUXO RESUMIDO

```bash
develop → pull → feature → codar → commit → push → PR → merge → develop → pull
```

---

## 🏆 EXEMPLO REAL

```bash
git switch develop
git pull origin develop
git switch -c feature/mobile-login

# codou...

git add .
git commit -m "feat(mobile): implementar tela de login"
git push

# PR no GitHub

git switch develop
git pull origin develop
```
