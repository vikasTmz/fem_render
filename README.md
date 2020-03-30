# README: fem_render
Blender script to create renderings of fem soft-body simulations.

#### Requirements

Blender (≥ v2.80) (*including python modules.*)

#### Usage

**Input**: A directory containing .obj files (exported from your simulation). Add this path in `render_script.py` to `PATH_TO_OBJS`.

Then either:
- Copy paste the python script into blender's python console or,

- Use this command:
```bash
blender --background render_scene.blend --factory-startup  --python render_script.py
```

### Result

![alt text](https://raw.githubusercontent.com/vikasTmz/fem_render/master/result.png "")

*The scene does not contain the collision object. You need to add this depending on what you implemented*
