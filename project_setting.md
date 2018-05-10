## Project Setting

Configure the project properties (menu PROJECT --> <project_name> Properties...)<br>

__Include Directory__<br>
![Include Directory](https://github.com/stanathong/retained_undistort_image/tree/master/project_setting/include_directory.jpg)

__Library Directory__<br>
![Lib Directory](https://github.com/stanathong/retained_undistort_image/tree/master/project_setting/lib_directory.jpg)

__Library__<br>
Add this libs to the line: opencv_core310.lib;opencv_highgui310.lib;opencv_imgproc310.lib;opencv_video310.lib;opencv_imgcodecs310.lib;opencv_calib3d310.lib;%(AdditionalDependencies)<br>
_Note that the number can be varied depending on your OpenCV version_<br>

![Lib](https://github.com/stanathong/retained_undistort_image/tree/master/project_setting/lib.jpg)

