# vibe.pyd

Utilities for using vibe.d and pyd together.

Currently, that consists of extensions for vibe.data.json.Json that can be enabled like so:

```
  import vibe.pyd;
  ex_d_to_python(&vibe_json_to_python);
  ex_python_to_d(&python_to_vibe_json);
```
