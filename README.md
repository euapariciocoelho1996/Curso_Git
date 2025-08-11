# 🚀 Curso\_Git - Guia Prático

---

## 🔧 Criar e entrar em uma branch

```bash
git checkout -b minha-feature
```

---

## ✍️ Fazer alterações no código

*Edite seus arquivos normalmente usando seu editor favorito.*

---

## ➕ Adicionar arquivos

```bash
git add .
```

> Adiciona todas as alterações feitas para serem incluídas no próximo commit.

---

## 💾 Salvar alterações no histórico (commit)

```bash
git commit -m "Implementada nova feature"
```

> Registra as mudanças adicionadas com uma mensagem descritiva.

---

## 🔄 Voltar para a branch principal

```bash
git checkout main / git checkout -b nome
```

---

## 🔀 Mesclar alterações da branch criada

```bash
git merge minha-feature
```

> Integra as mudanças da branch `minha-feature` na branch atual (`main`).

---

## ☁️ Enviar para o repositório remoto

```bash
git push origin main
```

> Envia os commits da branch local para o repositório remoto no GitHub, GitLab, etc.

---

## ⬇️ Baixar e integrar mudanças do repositório remoto

```bash
git pull origin main
```

> Baixa e integra os commits da branch `main` do repositório remoto para sua branch local.

---

## 🌀 Clonar um repositório remoto

```bash
git clone https://url-do-repositorio.git
```

> Copia todo o repositório remoto para sua máquina local.

---

## 🧹 Limpar arquivos não rastreados

```bash
git clean -f
```

> Remove arquivos não rastreados (não adicionados ao Git) do diretório de trabalho.

---

## 🔄 Descartar alterações em arquivos rastreados

```bash
git checkout -- arquivo.html
```

> Desfaz modificações locais no arquivo `arquivo.html`, restaurando a última versão commitada.

---

## 📚 Glossário Rápido

| Termo                       | Definição                                                        |
| --------------------------- | ---------------------------------------------------------------- |
| **Branch**                  | Ramo de desenvolvimento paralelo.                                |
| **Staging area**            | Área temporária onde arquivos são preparados antes do commit.    |
| **Commit**                  | Registro permanente de alterações.                               |
| **Merge**                   | Combina mudanças de duas branches diferentes.                    |
| **Push**                    | Envia commits locais para o repositório remoto.                  |
| **Pull**                    | Baixa e integra commits do repositório remoto.                   |
| **.gitignore**              | Arquivo que lista arquivos/pastas para serem ignorados pelo Git. |
| **git clone**               | Copiar projeto com link do repositório.                          |
| **git clean -f**            | Remove arquivos não rastreados do diretório de trabalho.         |
| **git checkout -- arquivo** | Descartar alterações locais em arquivos rastreados.              |
| **git log**                 | Mostra a lista dos commits feitos no repositório, com detalhes como autor, data e mensagem. |
---


