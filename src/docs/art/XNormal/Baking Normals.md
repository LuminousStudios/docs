# How to bake Normals

**Make sure that your meshes are large enough when you export them**

1. On the right side click on the High Definition meshes tab
2. In the center under the file column right click in the blank space and select add meshes (select your high poly mesh)<br/>![xNormal Select Files](./img/2024-07-09%2017_18_39-xNormal%20v3.19.3.39669.png)
3. In the Low Definition meshes tab repeat step 2 this time with your low poly mesh
4. Click on the Baking Options tab<br/>![xNormal Select Files](./img/2024-07-09%2020_04_06-xNormal%20v3.19.3.39669.png)
5. In here you can:
   - set the output destination
   - set the size of image you want
   - change settings for the Normal map
6. For **Unreal** you will want click the three dots next to Normal map and change the **Y** to **Y-** <br/>![xNormal Select Files](./img/2024-07-09%2020_26_33-Normal%20map.png)
7. Once you have everything set you can press the Generate Maps button in the bottom right. 

  
**If you are having artifacting check that your low poly mesh has good UVs. If you are still getting artifacting you may need to change the cage; see next section.**

# How to veiw and change the cage

If you want to view the cage for a bake click on the 3D Viewer tab then click on launch viewer<br/>![xNormal 3D View tab](./img/2024-07-09%2020_43_17-xNormal%20v3.19.3.39669.png)

Once in the 3D Viewer click on show cage <br/>![xNormal Show Cage](./img/2024-07-09%2020_48_37-DX10_GraphicsDrv_Window.png)

Then Click on edit cage <br/>![xNormal Edit Cage](./img/2024-07-09%2020_51_24-DX10_GraphicsDrv_Window.png)

You can drag the slider **left to shrink** the cage and **right to grow** the cage. If Darging it all the way one way is not large enough, while having the marker at one end let go and it will return to the center, you can then drag it again and continue to change the size.