# Cinza, mascote 3D do DBZ para Blender

Coruja mascote do escritorio, com robe e pergaminho. Disponivel como modelo estatico e com **rig** (esqueleto para animar).

## Como abrir

Baixe na aba **Releases**:

- **v1.1 (com rig)** — recomendado para animar:
  - `Cinza_rigged.blend`: abre direto no Blender (File > Open). Malha, material, texturas empacotadas e a armadura `CinzaRig`.
  - `Cinza_rigged.glb`: glTF 2.0 com skin (15 joints). Importe por File > Import > glTF 2.0.
- **v1.0 (sem rig)**: `Cinza.blend` e `Cinza.glb`, so o modelo.

## Rig (esqueleto)

Armadura `CinzaRig`, 15 ossos, pronta em Pose Mode:

| Osso | Controla |
|---|---|
| root | raiz geral |
| pelvis, spine, chest | tronco (inclinar, curvar) |
| neck, head | pescoco e cabeca (virar, inclinar) |
| arm.L / arm.R | asas / bracos laterais |
| thigh.L/R, shin.L/R | pernas sob o robe |
| scroll | pergaminho flutuante |

Pesos atribuidos por regiao (skinning procedural), validados no Blender: cada osso deforma sua area sem rasgar a malha. Modelo sem animacao pronta; o esqueleto e a base para criar as poses e keyframes.

![Pose de teste](preview-rig-pose.png)

## Texturas

Material unico `pbr_material` (PBR Metallic-Roughness), duas texturas 4096x4096: Base Color (sRGB) e Metallic-Roughness (Non-Color, Verde=Roughness, Azul=Metallic). Ja embutidas nos arquivos.
