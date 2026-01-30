3D Viewer setup

1) Export your Blender file to glTF Binary (.glb):
   - Open Blender, File > Export > glTF 2.0
   - Format: glTF Binary (.glb)
   - Export file as model.glb

2) Copy model.glb into this folder:
   d:\shree_drive backup\blender_4.1\9_room\web\model.glb

3) Run a local server from the web folder:
   - PowerShell: python -m http.server 8000

4) Open in your browser:
   - http://localhost:8000

Notes
- Browsers cannot load .blend files directly; they need .glb or .gltf.
- If your model is large, consider Draco compression in Blender export.
