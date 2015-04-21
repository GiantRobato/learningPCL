firstPCL
========

This project is meant to learn how to use the Point Cloud Library (PCL). The main resource used is from the [Writing Point Cloud data to PCD files](http://pointclouds.org/documentation/tutorials/writing_pcd.php#writing-pcd) tutorial.

Some things I learned are:

*CMAKE is awesome
*That I need to learn how to use CMAKE more
*You have to create a build directory and call from the build directory:

```
cmake ..
```

*this generates the CMAKE files and allows you to run:

```
make <program name>
```

*The program works as expected with an output of the following:

```
Saved 5 data points to test_pcd.pcd.
    0.352222 -0.151883 -0.106395
    -0.397406 -0.473106 0.292602
    -0.731898 0.667105 0.441304
    -0.734766 0.854581 -0.0361733
    -0.4607 -0.277468 -0.916762
```
