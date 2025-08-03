# Farm Defender

**Farm Defender** é um jogo em desenvolvimento no Unity 3D onde Valdô, o Guardião da Terra, protege a fazenda Sol Nascente, no coração do Sertão Pernambucano, de criaturas famintas chamadas Pragóides. Desenvolvido por Valdomiro (Valdô), o projeto combina elementos de simulação de fazenda e tower defense, com visual inspirado no Sertão e mecânicas de combate estratégico. O repositório é organizado para suportar modelagem de assets (Blender/Inkscape), documentação (Obsidian), e desenvolvimento no Unity.

## História
No Sertão Pernambucano, a fazenda Sol Nascente é um oásis verde cultivado por Valdô, com plantações de milho, feijão, abóboras e girassóis. Porém, Pragóides – criaturas travessas com olhos brilhantes – emergem do solo árido à noite, ameaçando destruir as colheitas. Valdô, com a ajuda de Tina (a galinha valente), Seu Zé (o mecânico), e Luzia (a botânica), deve defender a fazenda usando armadilhas como ventiladores solares e lanternas mágicas, enquanto planeja enfrentar o Rei Pragóide em sua caverna.

## Inspirações
O jogo é inspirado em títulos que combinam fazenda, defesa e estética vibrante:
- **Stardew Valley**: Layout de fazenda e visual colorido.
- **Plants vs. Zombies**: Mecânicas de tower defense e inimigos carismáticos.
- **Bloons Tower Defense**: Caminhos fixos e progressão de ondas.
- **Don’t Starve**: Contraste entre ambientes áridos e vivos, inimigos únicos.
- **Farm Together**: Visual 3D vibrante e personalização de fazenda.

## Estrutura do Repositório
```
farm_defender/
├── farm_assets/                # Modelos 3D (Blender) e texturas 2D (Inkscape)
├── farm_docs/                  # Documentação do projeto
│   ├── memorias/               # Interações com Grok (Aia) em JSON
│   ├── referencias/            # Referências visuais e paleta de cores (palette.md)
│   ├── relatorios/             # Relatórios de progresso
│   ├── vault/                  # Cofre Obsidian para notas
│   │   ├── farm_defender/      # Notas em markdown
├── farm_unity/                 # Projeto Unity 3D
├── .gitignore                  # Arquivos ignorados pelo Git
├── README.md                   # Este arquivo
├── LICENSE                     # Licença MIT
```

- **`farm_assets/`**: Assets como plantações (ex.: milho) e Pragóides, criados em Blender/Inkscape.
- **`farm_docs/memorias/`**: Registros detalhados das interações com Grok (Aia) em JSON, com nomenclatura `memoria_aia_farm_defender_vXX.json`.
- **`farm_docs/referencias/`**: Imagens dos jogos inspiradores e paleta de cores (`palette.md`).
- **`farm_docs/relatorios/`**: Relatórios de progresso (`relatorio_XX.md`).
- **`farm_docs/vault/farm_defender/`**: Notas no Obsidian para ideias e planejamento.
- **`farm_unity/`**: Projeto Unity com pastas padrão (Assets/, Packages/, ProjectSettings/).

## Paleta de Cores
A paleta de cores, definida em `farm_docs/referencias/palette.md`, guia as texturas:
- **Fazenda**: Verdes (#4CAF50) e amarelos (#FBC02D) para plantações.
- **Sertão**: Tons terrosos (#8D6E63, #BCAAA4) para o entorno.
- **Pragóides**: Cinza escuro (#424242) e amarelo brilhante (#FFFF00) para inimigos.
- **Defesas**: Metálico (#B0BEC5) e azul água (#0288D1) para armadilhas.
- **UI**: Verde escuro (#1B5E20) e amarelo texto (#FFEB3B) para interface.

## Como Executar
1. **Pré-requisitos**:
   - Unity 2022.3 LTS ou superior.
   - Blender (para modelagem 3D).
   - Inkscape (para texturas 2D).
   - Git (para clonar o repositório).
2. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/valdomiromorais/farm_defender.git
   cd farm_defender
   ```
3. **Abrir o Projeto**:
   - Abra `farm_unity/` no Unity Hub.
   - Carregue a cena `Assets/Scenes/FarmLevel.unity` (em desenvolvimento).
   - Pressione Play no Unity Editor.
4. **Modelagem e Texturas**:
   - Use Blender para criar assets em `farm_assets/` (exportar como .fbx).
   - Use Inkscape para texturas (salvar .svg em `farm_assets/`, exportar .png para `farm_unity/Assets/Textures/`).

## Ferramentas e Tecnologias
- **Unity 3D**: Desenvolvimento do jogo (cenas, scripts em C#).
- **Blender**: Modelagem de assets (ex.: milho, Pragóides).
- **Inkscape**: Criação de texturas 2D (ex.: folhas, solo).
- **Obsidian**: Gerenciamento de notas em `farm_docs/vault/farm_defender/`.
- **Git/GitHub**: Controle de versão e hospedagem.

## Como Contribuir
1. Faça um fork do repositório.
2. Crie uma branch: `git checkout -b feature/nova-funcionalidade`.
3. Adicione mudanças: `git add .` e `git commit -m "Descrição da mudança"`.
4. Envie um pull request para `main`.
