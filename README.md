# PCL-in-Ros-Melodic

Error: importing PCL in ROS Melodic because of libpcl version 1.8 being currently used but it requiring version 1.7, you can follow this website which is in Chinese. https://blog.csdn.net/tauyangdao/article/details/117048577

It says to download the pcl wheel file from github:  https://github.com/barrygxwan/Python-PCL-Ubuntu18.04

pip install <the downloaded file>
Test by running import pcl in a python file or in terminal: python
  
Another method could be as suggested here: https://stackoverflow.com/questions/56822397/trouble-met-when-installing-pcl-on-ubuntu-18-04
After running make, run below command for system wide access.
```
sudo make install
```
