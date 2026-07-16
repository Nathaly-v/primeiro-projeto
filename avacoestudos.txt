# Diário de Aprendizado

## Dia 1 - Git e GitHub (Módulo 1)

### Fluxo do Git

Editar → `git add .` → `git commit -m ""` → `git push`

### Comandos

- `git init` → Inicia um repositório Git.
- `git status` → Mostra o estado dos arquivos.
- `git add .` → Adiciona arquivos para o commit.
- `git commit -m ""` → Salva uma nova versão.
- `git push` → Envia commits para o GitHub.
- `git remote add origin URL` → Conecta o repositório local ao remoto.
- `git remote -v` → Lista os repositórios remotos.

### Conceitos

- Git = Controle de versão.
- GitHub = Hospeda repositórios.
- Commit = Snapshot (foto) do projeto.
- Push = Enviar alterações.
- Remote = Ligação entre repositório local e remoto.
- SSH = Autenticação segura.
- M = Modified.
- U = Untracked.

---

## Dia 2 - Colaboração (Módulos 2 e 3)

### Comandos

- `git clone URL` → Clona um repositório.
- `git pull` → Baixa alterações do GitHub.

### Conflitos

- Ocorrem quando duas pessoas alteram a mesma linha.
- Resolver:
  - Escolher a versão correta.
  - Remover as marcações.
  - Salvar.
  - Commit.
  - Push.

### Merge Editor

- Accept Current → Local.
- Accept Incoming → Remoto.
- Accept Combination → Combina os dois.

### Conceitos

- Fork = Cópia de um repositório.
- Pull Request = Solicitação para enviar alterações.
- Open Source = Projeto aberto para colaboração.

### Boas práticas

- Commits pequenos.
- Um commit = uma tarefa.
- Commit apenas com código funcionando.

---

## Dia 3 - Histórico do Git (Módulo 4)

### Comandos

- `git log` → Histórico completo.
- `git log --oneline` → Histórico resumido.
- `git commit --amend` → Edita o último commit.
- `git revert HASH` → Desfaz um commit criando outro.
- `git reset --hard HASH` → Volta apagando alterações.
- `git reset --soft HASH` → Volta mantendo alterações.

### Conceitos

- Cada commit possui um ID único.
- O Git guarda todo o histórico do projeto.
- `revert` é seguro para projetos compartilhados.
- `reset` altera o histórico e deve ser usado com cuidado.

### Boas práticas

- Não alterar commits já enviados ao GitHub.
- Preferir `git revert` quando o commit já foi publicado.
