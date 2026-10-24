# Contexto do projeto — M100-ROSE

Repositório de perfil do GitHub do usuário **M100-ROSE** (Kaike Raphael Machado Guerlinguer).

## Preferências

- Idioma de trabalho e documentação: português do Brasil.
- Commits: mensagens curtas, no padrão `tipo: descrição` (`feat:`, `fix:`, `docs:`, `refactor:`, `chore:`, `style:`, `test:`); um commit por assunto.
- Branch padrão: `main`; remoto: `origin` (https://github.com/M100-ROSE/M100-ROSE.git).
- Não commitar: segredos, `.env`, artefatos de build, `node_modules`, arquivos temporários (ex.: `.opencode/` não rastreado).

## Estado atual

- README.md sem referências textuais a BoJack Horseman (3ª iteração): título normal ("Olá, eu sou o Kaike..."), seção "Sobre mim"/"Minha stack" e contatos mantidos; apenas GIFs públicos via hotlink (pixel art no topo, Rick and Morty no portal, Ghostface) como elementos visuais.
- Branch `main` sincronizada com `origin/main`.

## Histórico

### 2026-10-24 — 3ª iteração do README: remover referências textuais e usar GIFs embutidos

- **Solicitação original:** "O README.md foi reescrito — removeu TODAS as referências textuais ao BoJack Horseman (frases, 'Hollywoo', 'Mr. Peanutbutter', 'It gets easier', etc.) e agora usa apenas GIFs públicos embutidos via hotlink: 1) GIF de BoJack em pixel art no topo (link do site do animador Ivan Dixon), 2) GIF do Rick and Morty atravessando o portal (media.giphy.com, canal oficial Adult Swim) como divisor no meio, 3) GIF do Ghostface de Pânico (media.giphy.com, canal oficial ScreamMovies) antes da seção de contato. Badges de tecnologias, bloco 'Sobre mim' e contatos (email kaikeguerlinguer@gmail.com, Instagram @rhaast_kg) continuam. Confirmar que só o README.md mudou, commitar e enviar para origin main."
- **O que foi feito:**
  1. Rodei `git status` e `git diff`: confirmado que apenas `README.md` foi modificado entre os arquivos rastreados; `.opencode/` permaneceu não rastreado e fora do commit.
  2. Conferido no diff a remoção de todas as referências textuais de BoJack (título "KAIKE HORSEMAN", sinopse em episódios, "Still serving suggestions!", "Hollywoo", "Mr. Peanutbutter", "It gets easier", "Doggy doggy what now?", "Hjkl;'", epígrafe final) e a chegada dos 3 GIFs: pixel art (squarespace-cdn.com, site do Ivan Dixon) no topo, Rick and Morty no portal (media.giphy.com, Adult Swim) como divisor e Ghostface (media.giphy.com, ScreamMovies) antes do contato.
  3. Conferido que badges de tecnologias, bloco "Sobre mim" e contatos (Gmail kaikeguerlinguer@gmail.com e Instagram @rhaast_kg) foram mantidos; conteúdo do README não foi alterado.
  4. Commit README: `c5afc8d` — `Replace text references with themed GIFs (pixel art, portal, ghostface)`.
  5. Commit `contexto.md` separado: `<hash2>` — `docs: registrar terceira iteração do README no contexto`.
  6. Push para `origin main` (`2b39b77..a283e64`), enviado com sucesso.
- **Arquivos alterados:** `README.md`, `contexto.md`.
- **Pendências:**
  - [ ] Avaliar se `.opencode/` deve entrar no `.gitignore`.
  - [ ] Verificar se o hotlink do GIF de pixel art (squarespace-cdn.com) permanece estável ao longo do tempo (hotlinks podem quebrar).

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
