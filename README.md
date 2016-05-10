# multi-screen-projection
To project animation in a device with two projectors
1.Please open the test3_10.vs to start.
2.Up to now, the project has three functions: 
      "找点"：to calibrate the 3D points coordinates into the 2D screens. The device consists of 14 X 13 fishlines and we are going to project some dynamic things through these lines. First we need to find out the relation between the fishlines and screens.
      "画图"：to project dynamic things in the fishlines. We creat the xxx.txt to store the position we want to inlight.
      "标定"：to inlight certain fishlines. As the device and the projectors are not stable enough, we need to adjust the projectors through calibration so that they satisfy the relationship we find during the "找点" step.
3.Now we have realized some animation such as the change of cubes(enlarge, rotate). As we have spend a lot of time to figure out how to create the xxx.txt in order to realize certain effect, we are looking for more models that can be projected in the fishlines. We are also need a program to generate the xxx.txt automatically.
