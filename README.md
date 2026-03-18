{\rtf1\ansi\ansicpg1252\cocoartf2761
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Nazca Layout Generator Notebooks\
\
**Author:** Jason P. Beech \
**Date:** 2026  \
\
This repository contains a collection of Jupyter notebooks for generating parametric micro/nanofabrication layouts using **Nazca**. The notebooks produce GDSII files that can be opened in tools such as **KLayout**.\
\
---\
\
## \uc0\u55357 \u56514  Contents\
\
### 1. Ellipse Array Generator\
Generates arrays of vertically stacked ellipses with varying aspect ratios.\
\
- Fixed width, varying height\
- Aspect ratio sweep within each unit cell\
- Export to GDSII or preview in Nazca\
\
---\
\
### 2. Polygon Array Generator\
Generates arrays of 2\'d72 unit cells containing regular polygons:\
\
- Triangle, square, pentagon, hexagon\
- Uniform circumradius\
- Adjustable spacing and orientation\
\
---\
\
### 3. Random Cluster Generator\
Generates arrays of unique random clustered objects:\
\
- Built from overlapping circles\
- Uses **gdstk** for boolean geometry\
- Each array position contains a unique object\
\
---\
\
### 4. Gaussian Bump Generator\
Generates arrays of circular objects with a localized Gaussian bump:\
\
- Base circle with angular Gaussian perturbation\
- Amplitude varies across the array\
- Optional snake ordering\
\
---\
\
## \uc0\u9881 \u65039  Installation\
\
Clone the repository:\
\
```bash\
git clone https://github.com/beechyboy/particle_generators.git\
cd your-repo-name}
