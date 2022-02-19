# note

```py
import bpy
```

## A,select all

```py
>>> bpy.ops.object.select_all()
{'FINISHED'}

>>> bpy.ops.object.select_all(action='TOGGLE')
{'FINISHED'}

```

## select by name

```py
>>> cube = bpy.data.objects['Cube']
>>> cube
bpy.data.objects['Cube']

>>> bpy.ops.object.delete(
delete()
bpy.ops.object.delete(use_global=False)
>>> bpy.ops.object.delete()
{'FINISHED'}

>>> 
