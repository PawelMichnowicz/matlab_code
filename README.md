# matlab_code

The algorithm analyses porous structure of a solid oxide fuel cell anode by using FIB-SEM images of their microstructure.
Sets of these images represent the whole microstructure and each color represent particular phase of microstructure:
Black - pore
Grey - YSZ (Yttria-stabilized zirconia)
White - Ni (Nickel)

![alt text](https://i.ibb.co/KhyTs96/1.png)

Each color zone (phase) in microstructure form something like clusters
and these clusters are either isolated from externals surfaces of microstructure or extend through the entire structure (percolated phase)

Algorithm marks teh respective phase as isolated or percolated, and calculate percentage of each one.

![alt text](https://i.ibb.co/VpDw9pC/2.png)
