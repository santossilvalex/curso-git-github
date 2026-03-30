# 🚀 Curso TMW Git & GitHub 2026

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

Curso produzido por **Téo Calvo**, focado em conceitos essenciais de versionamento de código e colaboração remota utilizados no dia a dia do desenvolvedor.

---

## 📚 Conteúdo do Curso
O treinamento abordou desde os fundamentos até fluxos avançados de trabalho:
* **Versionamento de códigos** e repositórios remotos.
* **GitFlow** e boas práticas de ramificação.
* Integração e produtividade com **VS Code**.
* Fluxos de contribuição para projetos **Open-Source**.

---

## 🛠️ Fluxos de Trabalho (Cheat Sheet)

### 1. Fluxo Git Local
Ideal para desenvolvimento individual e testes rápidos.
1. `git checkout -b <nova-branch>`
2. *Criação ou atualização de arquivos*
3. `git status`
4. `git add <arquivos>`
5. `git commit -m "minha mensagem"`
6. `git checkout main`
7. `git merge <nova-branch>`

### 2. Fluxo GitHub ↔️ Local (Projetos Próprios/Empresa)
Padrão para colaboração em equipe com repositórios centralizados.
1. `git clone <endereco-do-projeto>`
2. `git checkout -b <nova_branch>`
3. `git add .` + `git commit -m "nova mensagem"`
4. `git push origin <nova_branch>`
5. **Abrir Pull Request** no GitHub para a `main`
6. `git checkout main`
7. `git branch -D <nova_branch>` (Limpeza local)

### 3. Fluxo Open-Source (Fork & Pull)
Como contribuir com projetos de terceiros de forma segura.
1. **Fork** do projeto original para seu perfil.
2. `git clone <endereco-do-projeto-fork>`
3. Realizar alterações em uma branch específica.
4. `git push origin <nova_branch>`
5. **Abrir Pull Request** da sua branch para a `main` do projeto original.

---

## 📝 Padronização de Nomenclatura (Conventional Commits)

Utilizamos padrões para manter o histórico de commits limpo e semântico:

| Prefixo | Descrição |
| :--- | :--- |
| `feat` | Uma nova funcionalidade |
| `fix` | Correção de um bug |
| `docs` | Apenas mudanças de documentação |
| `style` | Formatação/estilo que não afeta o código |
| `refactor` | Mudança que não corrige bug nem add funcionalidade |
| `perf` | Mudança focada em melhorar performance |
| `test` | Adicionar ou corrigir testes |

---

## ✅ Conclusão
* **Finalizado em:** 18/03/2026
* **Estudante:** Alexsander
