We provide code of our proposed technique FEVOR for 3D object recognition.
If you have any query please contact me. Email: piyushjoshi3839@gmail.com


Run FEVOR
.\FEVOR .\scene_brush2.pcd .\brush.pcd .\1feature.txt .\2feature.txt 0 3 0.0001 0.0001 0.25 0.0005 0.05 


argv[0] = .\FEVOR.exe
argv[1] = "Scene"
argv[2] = "Object"
argv[3] = .\1feature.txt 
argv[4] = .\2feature.txt
argv[5] = Translation to object
argv[6] = Rotation to object
argv[7] = VoxelGrid leaf size for Scene
argv[8] = VoxelGrid leaf size for Object
argv[9] = grouping threshold
argv[10] = False rejection threshold
argv[11] = Similarity constraint
