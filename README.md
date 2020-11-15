# Perception Develop Environment
Repository housing perception dev environment setup script

Compile on Command Line: 

g++ test.cpp -I/usr/local/include/pcl-1.11 -I/usr/local/include/eigen3 -I/usr/include/boost -I/usr/include/vtk-8.2 -I/usr/include/flann -lpcl_common -lpcl_visualization -lpcl_io -lvtksys-8.2 -lvtkRenderingCore-8.2 -lvtkCommonCore-8.2 -lvtkCommonDataModel-8.2 -lvtkCommonMath-8.2 -lvtkFiltersCore-8.2 -lvtkCommonExecutionModel-8.2 -lvtkFiltersGeometry-8.2 -lboost_system -o test

Run on Command Line:

./test

