# Synthetic-Data-Creation-in-Blender
describes the process of rendering synthetic data in Blender


Creating a Simple Background in Blender

Starting with the default cube:

1.  Remove faces 
* Tab or select Edit Mode
* Select Faces
![]()
* Select the face (s) you want to delete Z, X, -Y

Look for this tool in the upper right corner 
![]()

Tip - if you hit the blue circle, the view will change and the face pointing in the +Z direction will be facing you 
* Select the face by clicking on it (the border will be white)
* Right click, and then choose Delete Faces

* Repeat for the X and -Y faces

![]()

2.  Flip normals - necessary so image is added correctly

* Select all -> Mesh -> Normals -> Flip

3. Edit UVs

* Select All -> UV -> Unwrap
* Select All -> UV -> Smart UV Project -> OK

4. Add an image

* Tab or click on Object Mode
* Click on Material Icon in bottom right corner
* Click on yellow button (Material Color)
* Choose Image texture (second column)
* Click on icon that looks like a file cabinet and choose the image you want to use as a texture

You won't see your image yet.  You need to swtich to veiwport shading by clicking on the icon in upper right corner

It was a little tricky getting the image to project the correct way onto the cube.

I created a p5.js sketch to use as a template
[Background template](https://editor.p5js.org/kfahn/sketches/qjBEbk-my)

5. 
* 
4. 




