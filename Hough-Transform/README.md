## Hough Transform with OpenCV in C++ and Python

### Hough Line Transform

**Usage**

**Python**

- ```python3 hough_lines.py lanes.jpg```

**C++**

- ```g++ hough_lines.cpp `pkg-config opencv --cflags --libs` -o hough_lines```
- ```./hough_lines lanes.jpg```

**CMake**

- ```mkdir build```
- ```cd build```
- ```cmake ..```
- ```cmake --build . --config Release```
- ```cd ..```
- ```./build/hough_lines lanes.jpg```

### Hough Circle Transform

**Usage**

**Python**

- ```python3 hough_circles.py brown-eyes.jpg```

**C++**

- ```g++ hough_circles.cpp `pkg-config opencv --cflags --libs` -o hough_circles```
- ```./hough_circles brown-eyes.jpg```

**CMake**

- ```mkdir build```
- ```cd build```
- ```cmake ..```
- ```cmake --build . --config Release```
- ```cd ..```
- ```./build/hough_circles brown-eyes.jpg```
