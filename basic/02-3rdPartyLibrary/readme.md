## Including Third Party Library

``` 
find_package( OpenCV REQUIRED 4.1.1 )
```

The arguments are:

* OpenCV - Name of the library. This is part of used to find the module file FindOpenCV.cmake

* 4.1.1 - The minimum version of OpenCV to find

* REQUIRED - Tells the module that this is required and to fail it it cannot be found

* COMPONENTS - The list of libraries to find.
