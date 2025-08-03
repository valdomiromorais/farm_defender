# Farm Defender

**Farm Defender** é um jogo em desenvolvimento no Unity 3D onde Valdô, o Guardião da Terra, protege a fazenda Sol Nascente, no Sertão Pernambucano, de criaturas famintas chamadas Pragóides. Desenvolvido por Valdomiro (Valdô), o projeto combina simulação de fazenda e tower defense, com um visual vibrante inspirado no Sertão e mecânicas de defesa emocional. Veja a narrativa completa em [`farm_docs/História.md`](#narrativa).

## Narrativa
No coração do Sertão Pernambucano, a fazenda Sol Nascente é um oásis verde de milho, feijão, abóboras e girassóis, cuidado por Valdô com o **Amuleto do Mandacaru**. Quando os Pragóides – criaturas nascidas da Grande Seca – ameaçam as plantações, Valdô, Tina (a galinha valente), Seu Zé (o mecânico), e Luzia (a botânica) usam armadilhas gentis para protegê-las. A missão é curar o coração do sertão, enfrentando o Rei Pragóide em um ritual de cura. Leia mais em [`farm_docs/História.md`](#narrativa).

## Inspirações
O jogo mistura fazenda, defesa e cultura sertaneja, inspirado em:
- **Stardew Valley**: Layout de fazenda e visual colorido.
- **Plants vs. Zombies**: Tower defense com inimigos carismáticos.
- **Bloons Tower Defense**: Caminhos fixos e ondas de inimigos.
- **Don’t Starve**: Contraste árido/vivo e criaturas únicas.
- **Farm Together**: Visual 3D vibrante e personalização.

## Estrutura do Repositório
```
farm_defender/
├── farm_assets/                # Modelos 3D (Blender) e texturas 2D (Inkscape)
├── farm_docs/                  # Documentação do projeto
│   ├── memorias/               # Interações com Grok (Aia) em JSON
│   ├── referencias/            # Paleta de cores (palette.md) e imagens
│   ├── relatorios/             # Relatórios de progresso
│   ├── vault/                  # Cofre Obsidian para notas
│   │   ├── farm_defender/      # Notas em markdown
├── farm_unity/                 # Projeto Unity 3D
├── .gitignore                  # Arquivos ignorados pelo Git
├── README.md                   # Este arquivo
├── História.md                 # Narrativa detalhada do jogo
├── LICENSE                     # Licença MIT
```

- **`farm_assets/`**: Assets como milho (#4CAF50, #FBC02D) e Pragóides (#424242, #FFFF00).
- **`farm_docs/memorias/`**: Registros em JSON (`memoria_aia_farm_defender_vXX.json`).
- **`farm_docs/referencias/`**: Paleta de cores (`palette.md`) e imagens (ex.: `stardew_farm.png`).
- **`farm_docs/relatorios/`**: Relatórios (`relatorio_XX.md`).
- **`farm_docs/vault/farm_defender/`**: Notas no Obsidian.
- **`farm_unity/`**: Projeto Unity (Assets/, Scenes/, Scripts/).

## Paleta de Cores
Definida em `farm_docs/referencias/palette.md`:
- **Fazenda**: Verdes (#4CAF50) e amarelos (#FBC02D) para plantações.
- **Sertão**: Tons terrosos (#8D6E63, #BCAAA4).
- **Pragóides**: Cinza (#424242), amarelo brilhante (#FFFF00).
- **Defesas**: Metálico (#B0BEC5), azul água (#0288D1).
- **UI**: Verde escuro (#1B5E20), amarelo texto (#FFEB3B).

## Como Executar
1. **Pré-requisitos**:
   - Unity 2022.3 LTS ou superior.
   - Blender (modelagem 3D).
   - Inkscape (texturas 2D).
   - Git (clonar repositório).
2. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/valdomiromorais/farm_defender.git
   cd farm_defender
   ```
3. **Abrir o Projeto**:
   - Abra `farm_unity/` no Unity Hub.
   - Carregue `Assets/Scenes/FarmLevel.unity` (em desenvolvimento).
   - Pressione Play no Unity Editor.
4. **Modelagem e Texturas**:
   - Crie assets em Blender (exportar como .fbx para `farm_unity/Assets/Models/`).
   - Crie texturas em Inkscape (salvar .svg em `farm_assets/`, exportar .png para `farm_unity/Assets/Textures/`).

## Ferramentas e Tecnologias
- **Unity 3D**: Desenvolvimento do jogo.
- **Blender**: Modelagem (ex.: milho, Pragóides).
- **Inkscape**: Texturas (ex.: folhas, solo).
- **Obsidian**: Notas em `farm_docs/vault/farm_defender/`.
- **Git/GitHub**: Controle de versão.

## Como Contribuir
1. Faça um fork do repositório.
2. Crie uma branch: `git checkout -b feature/nova-funcionalidade`.
3. Adicione mudanças: `git add .` e `git commit -m "Descrição da mudança"`.
4. Envie um pull request para `main`.

## Licença
MIT License. Veja `LICENSE` para detalhes.