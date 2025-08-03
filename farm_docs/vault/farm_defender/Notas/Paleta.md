# Paleta de Cores - Farm Defender

**Data**: 03/08/2025  
**Autor**: Grok (Aia), com base nas interações com Valdomiro (Valdô)  
**Objetivo**: Definir uma paleta de cores para as texturas dos assets do jogo *Farm Defender*, inspirada na história da fazenda Sol Nascente e nos jogos Stardew Valley, Plants vs. Zombies, Bloons Tower Defense, Don’t Starve e Farm Together. A paleta é projetada para ser clara e organizada, apoiando a neuro divergência de Valdô (TDAH e Superdotação).

## Contexto
A paleta reflete o ambiente do Sertão Pernambucano, com a fazenda Sol Nascente como um oásis verde em meio a terras áridas. As cores são divididas em categorias para plantações, entorno, inimigos (Pragóides), defesas e interface, garantindo um visual coeso e vibrante.

## Paleta de Cores

### 1. Fazenda Sol Nascente
Cores vibrantes para plantações, construções e elementos vivos, inspiradas em Stardew Valley e Farm Together.

| Cor             | Hexadecimal | Descrição                                         | Uso                                         | Inspiração                           |
| --------------- | ----------- | ------------------------------------------------- | ------------------------------------------- | ------------------------------------ |
| Verde Milho     | #4CAF50     | Verde vibrante para folhas de milho e feijão.     | Texturas de plantações, grama no Terrain.   | Stardew Valley (folhas de culturas). |
| Amarelo Espiga  | #FBC02D     | Amarelo quente para espigas de milho e girassóis. | Detalhes de plantações, flores.             | Farm Together (culturas maduras).    |
| Marrom Madeira  | #6D4C41     | Marrom rústico para cercas e galinheiros.         | Estruturas de madeira, troncos.             | Stardew Valley (cercas de fazenda).  |
| Verde Irrigado  | #81C784     | Verde claro para áreas irrigadas.                 | Grama no Terrain, plantas jovens.           | Farm Together (áreas cultivadas).    |
| Laranja Abóbora | #EF6C00     | Laranja vibrante para abóboras.                   | Texturas de abóboras, detalhes de colheita. | Stardew Valley (abóboras).           |

### 2. Sertão Árido
Tons terrosos para o entorno da fazenda, inspirados em Don’t Starve.

| Cor             | Hexadecimal | Descrição                           | Uso                                   | Inspiração                     |
| --------------- | ----------- | ----------------------------------- | ------------------------------------- | ------------------------------ |
| Terra Seca      | #8D6E63     | Marrom acinzentado para solo árido. | Textura base do Terrain, rochas.      | Don’t Starve (solo desértico). |
| Areia Poeirenta | #BCAAA4     | Bege claro para poeira e caminhos.  | Caminhos no Terrain, fundo árido.     | Don’t Starve (terreno seco).   |
| Cinza Pedra     | #78909C     | Cinza azulado para rochas e cactos. | Modelos de rochas, cactos no Blender. | Don’t Starve (rochas).         |

### 3. Pragóides
Cores escuras com detalhes brilhantes para inimigos, inspiradas em Plants vs. Zombies e Don’t Starve.

| Cor               | Hexadecimal | Descrição                                     | Uso                                  | Inspiração                             |
| ----------------- | ----------- | --------------------------------------------- | ------------------------------------ | -------------------------------------- |
| Cinza Rochoso     | #424242     | Cinza escuro para Pragóides de Terra.         | Corpo principal dos Pragóides.       | Don’t Starve (aranhas).                |
| Verde Musgo       | #388E3C     | Verde escuro para Pragóides Voadores.         | Asas e detalhes de inimigos.         | Plants vs. Zombies (zumbis verdes).    |
| Amarelo Brilhante | #FFFF00     | Amarelo neon para olhos e detalhes luminosos. | Olhos dos Pragóides, efeitos de luz. | Plants vs. Zombies (olhos brilhantes). |
| Roxo Misterioso   | #7B1FA2     | Roxo para Pragóides Luminosos.                | Corpo de Pragóides raros, efeitos.   | Don’t Starve (criaturas mágicas).      |

### 4. Defesas
Cores que misturam rusticidade e tecnologia, inspiradas em Bloons Tower Defense.

| Cor            | Hexadecimal | Descrição                                 | Uso                                      | Inspiração                                 |
| -------------- | ----------- | ----------------------------------------- | ---------------------------------------- | ------------------------------------------ |
| Cinza Metálico | #B0BEC5     | Cinza prateado para ventiladores solares. | Estruturas metálicas, armadilhas.        | Bloons Tower Defense (torres).             |
| Azul Água      | #0288D1     | Azul vibrante para armadilhas de água.    | Efeitos de água, texturas de armadilhas. | Bloons Tower Defense (torres aquáticas).   |
| Amarelo Solar  | #FFCA28     | Amarelo brilhante para painéis solares.   | Detalhes de ventiladores, lanternas.     | Bloons Tower Defense (torres energéticas). |
| Branco Brilho  | #FFF8E1     | Branco suave para lanternas mágicas.      | Efeitos de luz, lanternas de Luzia.      | Plants vs. Zombies (plantas brilhantes).   |

### 5. UI e HUD
Cores contrastantes para interface, inspiradas em Plants vs. Zombies.

| Cor             | Hexadecimal | Descrição                         | Uso                                | Inspiração                          |
| --------------- | ----------- | --------------------------------- | ---------------------------------- | ----------------------------------- |
| Verde Escuro    | #1B5E20     | Verde profundo para fundos de UI. | Painéis de HUD, menus.             | Plants vs. Zombies (fundo de menu). |
| Amarelo Texto   | #FFEB3B     | Amarelo claro para texto legível. | Textos de HUD, botões.             | Plants vs. Zombies (textos).        |
| Marrom Botão    | #5D4037     | Marrom rústico para botões.       | Botões de menu, interfaces.        | Stardew Valley (UI rústica).        |
| Vermelho Alerta | #D32F2F     | Vermelho vibrante para alertas.   | Indicadores de perigo, vida baixa. | Plants vs. Zombies (alertas).       |

## Aplicação Prática
- **Blender**: Use as cores para texturas de assets:
  - **Milho**: Combine Verde Milho (#4CAF50) para folhas, Amarelo Espiga (#FBC02D) para espigas, e Marrom Madeira (#6D4C41) para caule.
  - **Pragóide de Terra**: Use Cinza Rochoso (#424242) para o corpo e Amarelo Brilhante (#FFFF00) para olhos.
  - **Ventilador Solar**: Use Cinza Metálico (#B0BEC5) para a estrutura e Amarelo Solar (#FFCA28) para painéis.
  - Exporte modelos como .fbx para `farm_unity/Assets/Models/`.
- **Inkscape**: Crie texturas 2D:
  - Desenhe folhas com gradientes de Verde Milho (#4CAF50) a Verde Irrigado (#81C784).
  - Crie texturas de terra com Terra Seca (#8D6E63) e Areia Poeirenta (#BCAAA4).
  - Salve como .svg em `farm_assets/` e exporte como .png para `farm_unity/Assets/Textures/`.
- **Unity**: Aplique as cores no Terrain e materiais:
  - Terrain: Use Terra Seca (#8D6E63) e Grama Verde (#4CAF50) com a ferramenta Paint Texture.
  - Materiais: Crie materiais com cores da paleta (ex.: Material de milho com #4CAF50).
  - UI: Use Verde Escuro (#1B5E20) para fundos e Amarelo Texto (#FFEB3B) para textos.

## Dicas para Valdô (TDAH e Superdotação)
- **Foco (TDAH)**: Escolha uma categoria (ex.: Fazenda) e modele uma textura por vez (ex.: milho em 20 min). Use a paleta como checklist visual.
- **Criatividade (Superdotação)**: Experimente variações (ex.: milho jovem com #81C784, milho maduro com #FBC02D). Teste combinações inesperadas, como Roxo Misterioso (#7B1FA2) em detalhes de plantações.
- **Referências**: Salve imagens dos jogos em `farm_docs/referencias/` (ex.: `stardew_farm.png`, `pvz_zombies.png`) para visualizar a paleta em ação.

## Referências Visuais
- **Stardew Valley**: Capturas de fazendas para plantações e cercas (salvar em `farm_docs/referencias/stardew_farm.png`).
- **Plants vs. Zombies**: Imagens de zumbis e plantas para Pragóides e defesas (salvar em `farm_docs/referencias/pvz_enemies.png`).
- **Don’t Starve**: Cenários áridos para o Sertão (salvar em `farm_docs/referencias/dontstarve_desert.png`).
- **Farm Together**: Fazendas 3D coloridas (salvar em `farm_docs/referencias/farmtogether_crops.png`).
- **Bloons Tower Defense**: Torres e caminhos (salvar em `farm_docs/referencias/bloons_paths.png`).