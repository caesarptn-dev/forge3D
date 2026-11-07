# Forge3D Studio

Browser 3D viewer/editor. Single file: `index.html`. No build step.

- Formats: GLB, GLTF, OBJ+MTL, FBX, STL, PLY, DAE, 3DS, 3MF, WRL, PCD, XYZ, USDZ, AMF, VTK, HDR env, ZIP bundles
- Auto texture import: drop textures with the model (or after it). Names like `_normal`, `_rough`, `_metal`, `_ao`, `_emissive` are matched automatically
- Tools: move/rotate/scale (W/E/R), duplicate, delete, color, opacity, wireframe, lights, physics, animation, screenshot, export GLB/OBJ/STL
- AI link: OpenAI-compatible (also Ollama) or Anthropic. Key stays in your browser.

## Publish on GitHub Pages
1. github.com → New repository → name `forge3d` → Public → Create
2. Add file → Upload files → drop `index.html` and `README.md` → Commit
3. Settings → Pages → Source: Deploy from a branch → `main` / `/(root)` → Save
4. Wait ~1 min: `https://YOUR-USERNAME.github.io/forge3d/`
