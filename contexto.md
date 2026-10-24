# Contexto do projeto — M100-ROSE

Repositório de perfil do GitHub do usuário **M100-ROSE** (Kaike Raphael Machado Guerlinguer).

## Preferências

- Idioma de trabalho e documentação: português do Brasil.
- Commits: mensagens curtas, no padrão `tipo: descrição` (`feat:`, `fix:`, `docs:`, `refactor:`, `chore:`, `style:`, `test:`); um commit por assunto.
- Branch padrão: `main`; remoto: `origin` (https://github.com/M100-ROSE/M100-ROSE.git).
- Não commitar: segredos, `.env`, artefatos de build, `node_modules`, arquivos temporários (ex.: `.opencode/` não rastreado).

## Estado atual

- README.md com tema BoJack Horseman amenizado: mantidos o visual (paleta preto/amarelo, 🐴, tipografia Righteous, badges, boxes) e frases leves ("WOOF!", "Doggy doggy what now?", "Hjkl;'", "BoJack Horseman (1998)"); trechos melancólicos removidos.
- Branch `main` sincronizada com `origin/main`.

## Histórico

### 2026-10-24 — Amenizar referências de BoJack Horseman no README

- **Solicitação original:** "O README.md foi reescrito para amenizar as referências de BoJack Horseman — mantido o visual/estilo e frases leves/engraçadas, removendo trechos melancólicos da versão anterior. Confirmar que só o README.md mudou, commitar e enviar para origin main."
- **O que foi feito:**
  1. Rodei `git status` e `git diff`: confirmado que apenas `README.md` foi modificado (18 inserções, 36 deleções); `.opencode/` permaneceu não rastreado e fora do commit.
  2. Removidos do README: citações melancólicas ("It gets easier…" como epígrafe, "A vida é uma série de desilusões…", história da corrida na colina, "Me deixe sozinho…", "riverbend dos códigos", "sem vender a alma").
  3. Mantidos: paleta amarelo/preto, 🐴, tipografia, badges, sg., "WOOF!", "Schmoopy...", "Doggy doggy what now?", "Hjkl;'", sinopse em formato de episódios.
  4. Commit `f7f0e1e` — `Soften BoJack references in README, keep visual theme`.
  5. Push para `origin main` (4392881..f7f0e1e), enviado com sucesso.
- **Arquivos alterados:** `README.md` (e criação deste `contexto.md`).
- **Pendências:**
  - [ ] Avaliar se `.opencode/` deve entrar no `.gitignore`.

## Modelo para novas entradas

```
### AAAA-MM-DD — Título curto da tarefa

- **Solicitação original:** <texto da solicitação>
- **O que foi feito:**
  1. <passo>
- **Arquivos alterados:** <lista>
- **Pendências:**
  - [ ] <item>
```
