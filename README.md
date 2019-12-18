# godot-fps-label
Godot asset to show the frame rate of your games.

This document uses the format of the official Godot docs.

That is `type name` for variables and `return_type name(type name)` for functions.

### Method list

```python
void set_position(Position pos)
```
Set the position type, if you choose `Position.NONE` the label won't be forced to a fixed position. If you set other of the defined values in `Position`.

```python
void update_position()
```
This is called every time you resize the viewport and it is called inside `set_position()`, it updates the position of the Label based on the defined `Position` enum. 


### Enum

Position:
- TOP_LEFT
- TOP_RIGHT
- BOTTOM_LEFT
- BOTTOM_RIGHT
- NONE


### Properties

```python
int margin
```
The margin of the label in pixels.

```python
Label label
```
Direct reference to the active Label node.

```python
Position position
```
Holds the value of the enum Position defined by the user.
