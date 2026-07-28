# Cinza, modelo 3D para Blender

## Como abrir

Duas opcoes, ambas abrem no Blender:

1. **Cinza.blend** (formato nativo do Blender, recomendado). Baixe na aba **Releases** deste repositorio e abra com **File > Open** ou dando duplo clique. Ja vem com malha, material e as duas texturas empacotadas dentro do arquivo. Nao precisa de mais nada.

2. **Cinza.glb** (glTF 2.0). No Blender: **File > Import > glTF 2.0 (.glb/.gltf)** e selecione o arquivo. As texturas estao embutidas e o importador liga os nos automaticamente.

O modelo e uma malha estatica (cerca de 1 milhao de vertices), material PBR unico chamado `pbr_material`. Nao tem esqueleto (rig) nem animacao.

## Arquivos

- `Cinza.glb` (arvore do repositorio): importavel no Blender.
- `Cinza.blend` (Release v1.0): arquivo nativo, abre direto, texturas empacotadas.
- `mapeamento-tecnico.json`: dump do glTF (imagens, texturas, material).

## Texturas

| Slot | Espaco de cor | Observacao |
|---|---|---|
| Base Color / Albedo | sRGB | cor difusa |
| Metallic-Roughness | Non-Color | Verde = Roughness, Azul = Metallic |
