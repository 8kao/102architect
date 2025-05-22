# 102architect

**Home Planning & Homogeneous Coordinates Transformation Tool**  
An educational geometry tool to apply matrix-based transformations (translation, scaling, rotation, reflection) on 2D points, using homogeneous coordinates.  
Project developed as part of the Epitech Mathematics module.

---

## 🛠️ Project Overview

This project simulates part of a home planning software used by architectural firms. Its goal is to compute and display 2D transformations applied to points using matrix operations, without any external libraries such as NumPy.

You can apply the following transformations:
- Translation
- Scaling
- Rotation (around the origin)
- Reflection (over an axis passing through the origin)
- Any combination of the above

---

## 🚀 Usage

```bash
./102architect x y transfo1 arg11 [arg12] [transfo2 arg21 [arg22]] ...
./102architect 1 0 -r 90
# Applies a 90° rotation to point (1, 0)

./102architect 1 2 -t 2 3 -z 1 -2 -r 45 -s 30
# Applies a sequence of transformations to (1, 2)
