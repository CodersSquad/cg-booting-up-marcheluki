[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850916&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

```
These are the following instructions needed to run each program:

- For the 01_hello_world.py the needed installations were the following: "pip install moderngl" and "pip install pygame". Once this was done, the code ran correctly.

- In the case of the 06_multiple_objects.py the following setting up was necessary: "pip install PyGLM" the rest of the imports were already installed thanks to the previous activity: "pip install moderngl" && "pip install pygame"

- To correctly complete the 09_models_and_images.py running the following commands "pip install pywavefront" && "pip install objloader" was needed. Then, following the link "https://github.com/moderngl/moderngl/tree/main/examples/data/models" the files "crate.obj" and "lowpoly_toy_car.obj" need to be downloaded and placed inside a new folder called 09resources along with the image of the logo. When that is done, the code needs to be modified to point to the correct paths of the objects and the images. Also a minor modification to the code needed to be made to ensure the correct orientation of the image, like so: "v_uv = -in_uv;".

```

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs