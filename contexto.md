# Contexto do projeto — M100-ROSE

Repositório de perfil do GitHub do usuário **M100-ROSE** (Kaike Raphael Machado Guerlinguer).

## Preferências

- Idioma de trabalho e documentação: português do Brasil.
- Commits: mensagens curtas, no padrão `tipo: descrição` (`feat:`, `fix:`, `docs:`, `refactor:`, `chore:`, `style:`, `test:`); um commit por assunto.
- Branch padrão: `main`; remoto: `origin` (https://github.com/M100-ROSE/M100-ROSE.git).
- Não commitar: segredos, `.env`, artefatos de build, `node_modules`, arquivos temporários (ex.: `.opencode/` não rastreado).

## Estado atual

- README.md em versão PROFISSIONAL e clean (5ª iteração): sem nenhum GIF e sem tema arcade — removidos todos os GIFs do Tenor (cenário pixel, moedas, coração, Game Boy, TV, LEVEL UP), typing SVGs em "Press Start 2P", barra arco-íris, tabela "Score screen", "PLAYER 1", "INSERT COIN", "Side quests" e "Inventário". Estrutura: intro com nome e trajetória (15 anos, estudando desde os 9), "Sobre mim" com bullets objetivos, "Stack de tecnologia" com badges flat-square agrupadas em Linguagens / Banco de dados / Frameworks & bibliotecas (React, Next.js, MediaPipe) / Hardware & IoT (Arduino, ESP32, Sensores) e "Contato" com badges de kaikeguerlinguer@gmail.com e @rhaast_kg.
- Branch `main` sincronizada com `origin/main`.

## Histórico

### 2026-10-24 — 5ª iteração do README: versão profissional (sem GIFs, sem tema arcade)

- **Solicitação original:** "O README.md foi reescrito (5ª iteração) — versão PROFISSIONAL: removidos TODOS os GIFs (Tenor: cenário pixel, moedas, coração, Game Boy, TV, LEVEL UP) e todo o tema arcade (score screen, 'PLAYER 1', 'INSERT COIN', fonte Press Start 2P, typing SVGs, barra arco-íris, 'Side quests', 'Inventário'). Estrutura nova: intro com nome e trajetória (15 anos, estudando desde os 9), 'Sobre mim' com bullets objetivos, 'Stack de tecnologia' com badges em estilo flat-square agrupadas em Linguagens / Banco de dados / Frameworks & bibliotecas (React, Next.js, MediaPipe) / Hardware & IoT (Arduino, ESP32, Sensores), e 'Contato' com badges do email kaikeguerlinguer@gmail.com e Instagram @rhaast_kg. Confirmar que só o README.md mudou, atualizar contexto.md, commitar e enviar para origin main."
- **O que foi feito:**
  1. Rodei `git status` e `git diff`: confirmado que apenas `README.md` foi modificado entre os arquivos rastreados (39 inserções, 85 deleções); `.opencode/` permaneceu não rastreado e fora do commit.
  2. Conferido no diff: removidos todos os GIFs do Tenor (cenário pixel, moedas de ouro, coração de HP, Game Boy, TV retrô, barra arco-íris, LEVEL UP), os 4 typing SVGs em "Press Start 2P" ("PLAYER 1", "INSERT COIN TO CONTINUE...", "_LOADING_PROGRAMMING_SKILLS_", "15 LEVELS OLD"), a tabela "Score screen", "Side quests" e o footer arcade.
  3. Conferida a nova estrutura: intro com nome e trajetória (15 anos, estudando desde os 9), "Sobre mim" com 5 bullets objetivos, "Stack de tecnologia" com badges flat-square agrupadas em Linguagens / Banco de dados / Frameworks & bibliotecas (React, Next.js, MediaPipe) / Hardware & IoT (Arduino, ESP32, Sensores) e "Contato" com os mesmos badges de contato.
  4. Contatos mantidos: email kaikeguerlinguer@gmail.com e Instagram @rhaast_kg; conteúdo do README não foi alterado.
  5. Atualizei o "Estado atual" e registrei esta entrada no histórico.
  6. Commit README: `1fc6360` — `Simplify README to clean professional profile`.
  7. Commit `contexto.md` separado: `854ea64` — `docs: registrar quinta iteração do README no contexto`, seguido de `docs: corrigir hashes no histórico do contexto` (ajuste deste registro).
  8. Push para `origin main` (a partir de `774fd8d`), enviado com sucesso.
- **Arquivos alterados:** `README.md`, `contexto.md`.
- **Pendências:**
  - [ ] Avaliar se `.opencode/` deve entrar no `.gitignore`.

### 2026-10-24 — 4ª iteração do README: tema ARCADE/RETRO GAMING em pixel art

- **Solicitação original:** "O README.md foi reescrito (4ª iteração) — novo tema ARCADE/RETRO GAMING 100% pixel art, decorativo e leve: removidos os GIFs anteriores (BoJack, Rick and Morty, Ghostface) e TODA referência textual a shows/personagens; hero com GIF pixel art de cenário de jogo; 4 escritas animadas (typing SVG) com fonte 'Press Start 2P' e cores ciano/amarelo/magenta/verde ('PLAYER 1: KAIKE...', 'INSERT COIN TO CONTINUE...', etc.); safira de accents pixel art (moedas de ouro, coração de HP, Game Boy, TV retrô); divisores de barra de loading arco-íris; tabela 'Score screen'; seções 'Inventário' (badges mantidas intactas) e 'Side quests'; footer com GIF 'LEVEL UP!'. Contatos mantidos. Confirmar que só o README.md mudou, atualizar o contexto.md, commitar e enviar para origin main."
- **O que foi feito:**
  1. Rodei `git status` e `git diff`: confirmado que apenas `README.md` foi modificado entre os arquivos rastreados (44 inserções, 18 deleções); `.opencode/` permaneceu não rastreado e fora do commit.
  2. Conferido no diff: GIFs de BoJack (squarespace-cdn), Rick and Morty (Giphy) e Ghostface (Giphy) removidos, junto com TODA referência textual a shows/personagens.
  3. Conferida a nova estrutura arcade: hero com GIF pixel art de cenário de jogo (Tenor o1bn4A8hr-0AAAAC), 4 linhas typing SVG com "Press Start 2P" nas cores ciano/amarelo/magenta/verde, safira de accents (moedas de ouro, coração de HP, Game Boy, TV retrô), divisores de barra de loading arco-íris (Tenor FIEQyjiLuMYAAAAC) no meio e antes do contato, tabela "Score screen" (PLAYER/LEVEL/XP/CLASSE/MISSÃO/STATUS), "Inventário (stack completa)" com badges intactas, "Side quests" e footer com GIF "LEVEL UP!" (Tenor o5A7MC5_mv4AAAAC).
  4. Contatos mantidos: email kaikeguerlinguer@gmail.com e Instagram @rhaast_kg; conteúdo do README não foi alterado.
  5. Corrigido no histórico da 3ª iteração o marcador pendente `<hash2>` para o hash real do commit (`a283e64`).
  6. Commit README: `ae9e02e` — `Rebuild README with pixel-art arcade theme`.
  7. Commit `contexto.md` separado: `774fd8d` — `docs: registrar quarta iteração do README no contexto`.
  8. Push para `origin main` (f9ef928..774fd8d), enviado com sucesso.
- **Arquivos alterados:** `README.md`, `contexto.md`.
- **Pendências:**
  - [ ] Avaliar se `.opencode/` deve entrar no `.gitignore`.
  - [ ] Verificar se os GIFs hotlinkados do Tenor permanecem estáveis ao longo do tempo (hotlinks podem quebrar).

### 2026-10-24 — 3ª iteração do README: remover referências textuais e usar GIFs embutidos

- **Solicitação original:** "O README.md foi reescrito — removeu TODAS as referências textuais ao BoJack Horseman (frases, 'Hollywoo', 'Mr. Peanutbutter', 'It gets easier', etc.) e agora usa apenas GIFs públicos embutidos via hotlink: 1) GIF de BoJack em pixel art no topo (link do site do animador Ivan Dixon), 2) GIF do Rick and Morty atravessando o portal (media.giphy.com, canal oficial Adult Swim) como divisor no meio, 3) GIF do Ghostface de Pânico (media.giphy.com, canal oficial ScreamMovies) antes da seção de contato. Badges de tecnologias, bloco 'Sobre mim' e contatos (email kaikeguerlinguer@gmail.com, Instagram @rhaast_kg) continuam. Confirmar que só o README.md mudou, commitar e enviar para origin main."
- **O que foi feito:**
  1. Rodei `git status` e `git diff`: confirmado que apenas `README.md` foi modificado entre os arquivos rastreados; `.opencode/` permaneceu não rastreado e fora do commit.
  2. Conferido no diff a remoção de todas as referências textuais de BoJack (título "KAIKE HORSEMAN", sinopse em episódios, "Still serving suggestions!", "Hollywoo", "Mr. Peanutbutter", "It gets easier", "Doggy doggy what now?", "Hjkl;'", epígrafe final) e a chegada dos 3 GIFs: pixel art (squarespace-cdn.com, site do Ivan Dixon) no topo, Rick and Morty no portal (media.giphy.com, Adult Swim) como divisor e Ghostface (media.giphy.com, ScreamMovies) antes do contato.
  3. Conferido que badges de tecnologias, bloco "Sobre mim" e contatos (Gmail kaikeguerlinguer@gmail.com e Instagram @rhaast_kg) foram mantidos; conteúdo do README não foi alterado.
  4. Commit README: `c5afc8d` — `Replace text references with themed GIFs (pixel art, portal, ghostface)`.
  5. Commit `contexto.md` separado: `a283e64` — `docs: registrar terceira iteração do README no contexto`.
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
