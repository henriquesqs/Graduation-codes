# First project
This project illustrates a scene with a bird, a man and other objects composed by the basic primitives (triangles, squares, circles etc). This project:

- Allows you to translate the man and the bird;
- Allows you to rotate and switch the scene from day to night;
- Automatically translates the clouds left to right (and vice versa).

## Getting started
First, install **[python3](https://www.python.org/)** and **[pip](https://pip.pypa.io/en/stable/installing/)**. 

After that, install **glfw**, **numpy** and **PyOpenGL** using:

```
pip install glfw numpy PyOpenGL
```

Then run the project by using:

```
python3 project.py
```

## Controls
- To **translate the man**, use **W, A, S and D** keys *(don't forget to appreciate the 'depth effect' when you move the man using the S key)*;
- To **translate the bird**, use **arrow keys**;
- To **rotate and change from day to night** (or vice versa), use the KEYBOARD numbers 1 and 2 **(not the numpad ones)**

## Notes
- There is a vertical limit so you can't translate the man and the bird to the sky.

## Preview
![](https://i.imgur.com/klZy5DB.png)