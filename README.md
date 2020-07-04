# Minimum-Bounding-Box
The goal is to find a minimum area convex hull in higher dimensions. The work here is done under the jurisdiction of Information Technology University, Lahore, Pakistan

### Minimum Volume Bounding Box for 3D set of points

Given a 3D set of points in 3D, we intend to find the minimum area bounding box that can contain the convex hull ergo can contain all the points in space.

#### Example:

**Tetrahedron points:**

```python
sphere_points = array([ [0,0,1], [0,1,0], [1,0,0], [1,1,1] ])
sphere_points = Scale * sphere_points
```

![Image of Simplex](https://github.com/ObaidUllah-ITU-2019/Minimum-Bounding-Box/blob/master/images/Given_set_of_points.png)


**Bounding Box:**

![Bounding Box](https://github.com/ObaidUllah-ITU-2019/Minimum-Bounding-Box/blob/master/images/Minimum_volume_bounding_box.png)

**Convex Hull:**

![Convex Hull](https://github.com/ObaidUllah-ITU-2019/Minimum-Bounding-Box/blob/master/images/Convex_hull.png)

**Bounding Box and Convex Hull:**

![Bounding Box vs Convex Hull](https://github.com/ObaidUllah-ITU-2019/Minimum-Bounding-Box/blob/master/images/Bbox_vs_convexHull.png)

**Bounding Box Volume as a function of Angle of Rotaions:**

![Bounding Box Volume as a function of Angle of Rotaions](https://github.com/ObaidUllah-ITU-2019/Minimum-Bounding-Box/blob/master/images/Volume_by_rotations.png)

