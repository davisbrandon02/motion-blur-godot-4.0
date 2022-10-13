# motion-blur-godot-4.0
A motion blur plugin created by Bauxitedev, ported to Godot 4.0

To use this plugin in your game, do the following:
1) Copy the motion-blur folder to your project directory.
2) Select the camera you want to apply motion blur to, and click the 'link' button above the scene tree to instance a scene.
3) Select the 'motion_blur.tscn' file, and click Open.

If you want to customize the blur:
1) Select the motion_blur node
2) Click 'Surface Material Override' in the inspector under MeshInstance3D.
3) Click 'Shader Parameters'
4) Mess with the Intensity, Iteration Count, and Start Radius until you have the effect you'd like.

Original plugin by Bauxitedev for Godot 3:
https://godotengine.org/asset-library/asset/211
