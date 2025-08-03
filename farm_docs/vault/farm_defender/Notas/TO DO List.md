# TO DO List - Farm Defender

## Assets a Modelar (Ordem de Complexidade)
1. **Milho (`milho_base.blend`)**: Planta low-poly com haste (#8D6E63), folhas (#4CAF50), espiga (#FBC02D). Textura fibrosa (`textures.svg`).  
   - [ ] Criar e exportar como `milho_base.glb` para `farm_assets/3D_models_formats/`.
2. **Melancia (`melancia.blend`)**: Planta rasteira low-poly com folhas (#4CAF50), fruto (#4CAF50, #E91E63). Textura listrada.  
   - [ ] Criar e exportar como `melancia.glb`.
3. **Lanterna de Luzia (`lanterna_luzia.blend`)**: Lanterna cilíndrica com emissão (#FFF8E1). Textura simples com shader luminoso.  
   - [ ] Criar e exportar como `lanterna_luzia.glb`.
4. **Ventilador Solar (`ventilador_ze.blend`)**: Ventilador com hélices (#B0BEC5, #FFCA28). Textura metálica, rotação básica.  
   - [ ] Criar e exportar como `ventilador_ze.glb`.
5. **Uva (`uva.blend`)**: Videira low-poly com treliça (#8D6E63), folhas (#4CAF50), cachos (#7B1FA2). Textura translúcida nos cachos.  
   - [ ] Criar e exportar como `uva.glb`.
6. **Goiaba (`goiaba.blend`)**: Árvore low-poly com tronco (#8D6E63), folhas (#4CAF50), frutos (#F06292). Textura suave nos frutos.  
   - [ ] Criar e exportar como `goiaba.glb`.
7. **Pragóide de Terra (`pragoide_terra.blend`)**: Corpo de barro rachado (#424242), olhos (#0288D1). Textura rachada, animação de “escutar”.  
   - [ ] Criar e exportar como `pragoide_terra.glb`.
8. **Manga (`manga.blend`)**: Árvore low-poly com tronco (#8D6E63), folhas (#4CAF50), frutos (#EF6C00, #FFC107). Textura brilhante nos frutos.  
   - [ ] Criar e exportar como `manga.glb`.
9. **Banana (`banana.blend`)**: Bananeira low-poly com tronco (#8D6E63), folhas (#4CAF50), cachos (#FFF176). Textura de nervuras nas folhas.  
   - [ ] Criar e exportar como `banana.glb`.
10. **Tina (`tina.blend`)**: Galinha low-poly (#FBC02D, #D32F2F) com pintinhos. Textura de penas, animação de caminhada.  
    - [ ] Criar e exportar como `tina.glb`.
11. **Pragóide Voador (`pragoide_voador.blend`)**: Corpo com asas translúcidas (#388E3C). Textura vítrea, animação de voo.  
    - [ ] Criar e exportar como `pragoide_voador.glb`.
12. **Pragóide Luminoso (`pragoide_luminoso.blend`)**: Corpo roxo (#7B1FA2) com emissão em morse. Textura brilhante, animação de pulsação.  
    - [ ] Criar e exportar como `pragoide_luminoso.glb`.
13. **Rei Pragóide (`rei_pragoide.blend`)**: Criatura majestosa (#424242, #FFFF00). Textura detalhada, animações de ataque e transformação.  
    - [ ] Criar e exportar como `rei_pragoide.glb`.

## Outras Tarefas
- [ ] Confirmar remoção de `aia_access.tkn` do histórico do repositório: `git rm --cached aia_access.tkn; git commit -m 'Remove token'; git push`.
- [ ] Atualizar `farm_docs/vault/farm_defender/Notas/Insights.md` com ideias de design (ex.: mecânicas de manga, uva, melancia).
- [ ] Salvar `Paleta.md` atualizada em `farm_docs/referencias/` com novas cores do Vale do São Francisco.
- [ ] Verificar no GitHub (`https://github.com/valdomiromorais/farm_defender`) se `FarmDefenderStory.md` foi removido e `História.md` está mantido.

## Sugestões Criativas (Sessões Curtas)
- **Blender (20 min)**:
  - Comece com o **Milho** (`milho_base.blend`): Modele haste (#8D6E63), folhas (#4CAF50), espiga (#FBC02D). Use `textures.svg` pra textura fibrosa. Exporte como `milho_base.glb`. Commit: `git add farm_assets/blender_files/milho_base.blend farm_assets/3D_models_formats/milho_base.glb; git commit -m "Adiciona milho_base.blend e milho_base.glb"`.
  - Ou **Melancia** (`melancia.blend`): Modele planta rasteira (#4CAF50) com fruto (#4CAF50, #E91E63). Textura listrada em `textures.svg`. Exporte como `melancia.glb`.
- **Obsidian (10 min)**:
  - Adicione ao `Insights.md`: “Mangas (#EF6C00) caem com ‘ploc’ sertanejo, atordoando Pragóides de Terra (#424242).” Commit: `git add farm_docs/vault/farm_defender/Notas/Insights.md; git commit -m "Adiciona insight de mecânica de manga"`.
- **Segurança (5 min)**:
  - Verifique se `aia_access.tkn` foi removido do GitHub. Se não, execute: `git rm --cached aia_access.tkn; git commit -m "Remove token"; git push`.