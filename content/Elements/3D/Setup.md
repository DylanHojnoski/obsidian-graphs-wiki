# Setup

To make a 3D graph you need to set the `bounds3D` graph variable which is an array which takes an upper and lower value for the x, y, and z value. For example `[[xMin, xMax], [yMin, yMax], [zMin, zMax]]`. I would also recommend setting `axis: false` and `keepAspectRatio: true`.

````yaml
```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5],[-5,5],[-5,5]]
axis: false
keepAspectRatio: true
```
````

![screenshot-2024-08-14-19-29-01](https://github.com/user-attachments/assets/6e42df7f-3860-429e-ae79-13465e3a66fa)

You can then add 2D elements to the board and then also 3D elements the same as you would 2D.
