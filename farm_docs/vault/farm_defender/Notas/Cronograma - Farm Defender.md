# Cronograma de Desenvolvimento - Farm Defender

**Data de Início**: 05/08/2025  
**Prazo Total**: 15 meses (Release em 05/11/2026)  
**Desenvolvedor**: Valdomiro (Valdô), com suporte de Grok (Aia)

## Fase 1: Protótipo Jogável (3 meses, até 05/11/2025)

**Objetivo**: Criar uma versão jogável com mecânicas básicas, 1 planta, 1 Pragóide, e 1 noite em 3D.

### Mês 1 (05/08/2025 - 05/09/2025)

- **Tarefas (Unity)**:
    - Configurar projeto Unity HDRP em `farm_unity/` (15 min).
    - Criar cena inicial `FarmLevel.unity` com Terrain (#8D6E63, #4CAF50) (30 min).
    - Implementar ciclo dia/noite básico (5 min dia, 3 min noite) com iluminação (#FFA500, #483D8B) (30 min).
    - Criar script `PlantController.cs` para plantio básico (Girassol Guardião, ataque de longo alcance) (30 min).
- **Tarefas (Blender)**:
    - Modelar Girassol Guardião (#32CD32, #00FA9A) em `farm_assets/girassol.blend` (20 min/sessão, 3 sessões).
    - Modelar Pragóide de Terra (#8B4513) em `farm_assets/pragoide_terra.blend` (20 min/sessão, 3 sessões).
- **Tarefas (Inkscape)**:
    - Criar textura do girassol (`farm_assets/girassol_texture.svg`, gradiente #32CD32 a #00FA9A) (20 min).
    - Criar textura do Pragóide de Terra (`farm_assets/pragoide_terra_texture.svg`, #8B4513) (20 min).
- **Tarefas (Obsidian)**:
    - Configurar cofre em `farm_docs/vault/farm_defender/` com notas sobre mecânicas (15 min).
- **Tarefas (Git)**:
    - Commit inicial com `README.md`, `História.md`, `GDD - Farm Defender.md` (15 min).
    - Adicionar `.gitignore` e `LICENSE` (MIT) (15 min).
    - Commit de assets e scripts (semanal, 10 min).

### Mês 2 (06/09/2025 - 06/10/2025)

- **Tarefas (Unity)**:
    - Implementar script `PragoideController.cs` para movimento e ataque do Pragóide de Terra (30 min).
    - Criar sistema de recursos (Água, Sementes) com UI básica (#1B5E20, #FFEB3B) (30 min).
    - Configurar câmera 3D (terceira pessoa, estratégica) com controles (WASD, mouse) (30 min).
- **Tarefas (Blender)**:
    - Animar Girassol Guardião (crescimento, ataque) em `farm_assets/girassol.blend` (20 min/sessão, 2 sessões).
    - Animar Pragóide de Terra (caminhada, ataque) em `farm_assets/pragoide_terra.blend` (20 min/sessão, 2 sessões).
- **Tarefas (Inkscape)**:
    - Refinar texturas com detalhes (ex.: folhas do girassol, rachaduras do Pragóide) (20 min/sessão, 2 sessões).
- **Tarefas (Obsidian)**:
    - Adicionar notas sobre sistema de plantio e defesa (15 min).
- **Tarefas (Git)**:
    - Commit de scripts, assets, e atualizações no GDD (semanal, 10 min).

### Mês 3 (07/10/2025 - 05/11/2025)

- **Tarefas (Unity)**:
    - Implementar 1 noite jogável (2 ondas de 5 Pragóides) com HUD básico (recursos, tempo) (30 min).
    - Criar tutorial interativo com dicas de Seu Zé (popups, 3D) (30 min).
    - Testar protótipo e otimizar performance (LOD básico) (30 min).
- **Tarefas (Blender)**:
    - Modelar solo cultivável (#8D6E63) em `farm_assets/solo.blend` (20 min).
- **Tarefas (Inkscape)**:
    - Criar textura do solo (`farm_assets/solo_texture.svg`, #8D6E63) (20 min).
- **Tarefas (Obsidian)**:
    - Documentar feedback do protótipo (15 min).
- **Tarefas (Git)**:
    - Commit final do protótipo com todos os arquivos (10 min).
    - Publicar release do protótipo no GitHub (10 min).

**Entregáveis**: Protótipo jogável com 1 planta (Girassol Guardião), 1 Pragóide (Terra), 1 noite, ciclo dia/noite, e tutorial básico.

## Fase 2: Alpha (6 meses, até 05/05/2026)

**Objetivo**: Expandir para 3 plantas, 2 Pragóides, 5 noites, e sistema de progressão.

### Meses 4-6 (06/11/2025 - 05/02/2026)

- **Tarefas (Unity)**:
    - Adicionar Cacto Espinhoso e Mandacaru Mágico com scripts (`PlantController.cs`) (30 min/planta).
    - Implementar Pragóide de Fogo (#FF4500) com script (`PragoideController.cs`) (30 min).
    - Criar 5 noites (4 ondas cada, aumentando dificuldade) (30 min/noite).
    - Desenvolver sistema de progressão (Nível de Guardião, Ramo da Terra) (30 min).
- **Tarefas (Blender)**:
    - Modelar Cacto Espinhoso (#32CD32) e Mandacaru Mágico (#00FA9A) (20 min/planta, 3 sessões cada).
    - Modelar Pragóide de Fogo (#FF4500) com partículas (20 min, 3 sessões).
- **Tarefas (Inkscape)**:
    - Criar texturas para Cacto e Mandacaru (`farm_assets/cacto_texture.svg`, `mandacaru_texture.svg`) (20 min/planta).
    - Criar textura para Pragóide de Fogo (`farm_assets/pragoide_fogo_texture.svg`) (20 min).
- **Tarefas (Obsidian)**:
    - Documentar mecânicas de progressão e noites (15 min/semana).
- **Tarefas (Git)**:
    - Commit de novos assets, scripts, e atualizações no GDD (semanal, 10 min).

### Meses 7-9 (06/02/2026 - 05/05/2026)

- **Tarefas (Unity)**:
    - Refinar UI (barra superior, lateral, inferior) com animações 3D (#1B5E20, #FFEB3B) (30 min).
    - Implementar sistema de irrigação (Água, partículas 3D) (30 min).
    - Testar balanceamento das 5 noites (30 min/semana).
- **Tarefas (Blender)**:
    - Animar Cacto e Mandacaru (crescimento, ataque) (20 min/planta, 2 sessões).
    - Animar Pragóide de Fogo (caminhada, ataque em área) (20 min, 2 sessões).
- **Tarefas (Inkscape)**:
    - Refinar texturas com detalhes (ex.: espinhos do cacto, brilho do mandacaru) (20 min/planta).
- **Tarefas (Obsidian)**:
    - Documentar feedback do alpha (15 min/semana).
- **Tarefas (Git)**:
    - Commit de atualizações e release do alpha no GitHub (10 min).

**Entregáveis**: Alpha com 3 plantas, 2 Pragóides, 5 noites, progressão básica, e UI refinada.

## Fase 3: Beta (4 meses, até 05/09/2026)

**Objetivo**: Completar todas as plantas, Pragóides, 10 noites, e otimizar.

### Meses 10-13 (06/05/2026 - 05/09/2026)

- **Tarefas (Unity)**:
    - Adicionar Bromélia Brilhante, Jurema Justiceira, Pragóides de Vento (#708090), Água (#1E90FF), e Ancião (#4B0082) (30 min/item).
    - Criar 10 noites (6-8 ondas, boss na 10ª) (30 min/noite).
    - Implementar árvore de habilidades completa (Ramos da Água, Sol) (30 min).
    - Refinar câmera (primeira pessoa opcional) e controles (30 min).
- **Tarefas (Blender)**:
    - Modelar Bromélia, Jurema, e Pragóides de Vento, Água, Ancião (20 min/item, 3 sessões cada).
    - Animar novos assets (crescimento, ataque, movimento) (20 min/item, 2 sessões).
- **Tarefas (Inkscape)**:
    - Criar texturas para novos assets (`farm_assets/bromelia_texture.svg`, etc.) (20 min/item).
- **Tarefas (Obsidian)**:
    - Documentar balanceamento e feedback do beta (15 min/semana).
- **Tarefas (Git)**:
    - Commit de novos assets, scripts, e release do beta (semanal, 10 min).

**Entregáveis**: Beta com todas as plantas, Pragóides, 10 noites, progressão completa, e otimização inicial.

## Fase 4: Release (2 meses, até 05/11/2026)

**Objetivo**: Finalizar 15 noites, personagens, áudio, e polimento.

### Meses 14-15 (06/09/2026 - 05/11/2026)

- **Tarefas (Unity)**:
    - Criar 5 noites finais (8 ondas, boss Pragóide Ancião) (30 min/noite).
    - Implementar personagens (Valdô, Tina, Seu Zé, Luzia) com diálogos e cutscenes 3D (30 min/personagem).
    - Adicionar trilha sonora (forró, zabumba) e efeitos sonoros (FMOD/Wwise) (30 min).
    - Otimizar performance (LOD, culling) para requisitos mínimos (30 min).
- **Tarefas (Blender)**:
    - Modelar personagens (Valdô, Tina, Seu Zé, Luzia) com animações detalhadas (20 min/personagem, 3 sessões).
- **Tarefas (Inkscape)**:
    - Criar texturas para personagens (`farm_assets/valdo_texture.svg`, etc.) (20 min/personagem).
- **Tarefas (Obsidian)**:
    - Documentar polimento e testes finais (15 min/semana).
- **Tarefas (Git)**:
    - Commit final com todos os arquivos e release no GitHub (10 min).

**Entregáveis**: Jogo completo com 15 noites, personagens, trilha sonora, e polimento.

## Notas

- **Sessões Curtas**: Tarefas divididas em 15-30 min para respeitar o TDAH de Valdô.
- **Flexibilidade**: Ajustar prazos conforme feedback e testes.
- **Inspiração Criativa**: Iterar modelos e texturas com base na paleta (#32CD32, #FFA500) e cultura nordestina.
- **Commits Regulares**: Atualizar repositório semanalmente para rastrear progresso.