<img src="https://github.com/Arsham-boredom/oop/raw/main/assets/cube_chapter_1.png">

### Introduction
---
- "As name suggests, Object Oriented Programming refer to [programming languages](https://en.wikipedia.org/wiki/Programming_language) that use objects in programming."

**Imagin** you are in a virtual world, it's empty, nothing is there, but you are in God mode and every thing is possible for you.
you can make things, modify them, delete and so on, and you are interested to use this power.

so, simply you open your [virtual_world.py file](github.com) and start with building simple cube.
but wait, you first need to __define__ shape and behave of a cube for your world. we call this kind of definition a Class.

everything in python have definition, numbers have a definition.

```python
my_integer = int(10)
my_second_integer = int(20)

my_integer + my_second_intger
```

Python defined the behavior of integers when they add together. these definitions are defined in a Class called `int`.

<img src="https://github.com/Arsham-boredom/oop/raw/main/assets/int_class.png">

without any more details, we, as god in our virtual world should define our cubes:

```python
Class Cube:
  # definition of 6 axis, 3D cube.
  pass
```

and now we defined our cube, so now we create real cube from our class definition,<br>
this single line, will create an __object__ which is an __instance__ our our __class Cube__
```python
my_cube = Cube()
```

and as this code executed, a Cube will get appeared in our virtual world with name __my_cube__ which is the name of our object.
<img src="https://github.com/Arsham-boredom/oop/raw/main/assets/my_cube.png">
