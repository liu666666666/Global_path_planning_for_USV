# Global Path Planning for USV
&emsp;&emsp;Unmanned Surface Vehicle (USV) is a new type of intelligent surface craft. Global path planning is the key technology of USV research, which can reflect the intelligent level of USV.  
&emsp;&emsp;In order to solve the problem of global path planning of USV, this repository uses the S-57 electronic chart to build the octree grid environment model, and proposes an improved A* algorithm based on sailing safety weight, pilot quantity and path curve smoothing to ensure the safety of the route, reduce the planning time, and improve path smoothness.  
&emsp;&emsp;The result of running the program is shown below. The simulation results show that the environmental model construction method and the improved A* algorithm can generate safe and reasonable global path.  
![](https://www.yanlongwang.net/USV/Global-path-planning-based-on-electronic-chart/ICMIR2017.png)  
&emsp;&emsp;The attached paper related with this project has been published at the ICMIR2017 conference, with the springer's literature address [Research and Implementation of Global Path Planning for Unmanned Surface Vehicle Based on Electronic Chart](https://link.springer.com/chapter/10.1007/978-3-319-65978-7_80#citeas). In additional, you can find the [detail design architecture](https://www.yanlongwang.net/USV/Global-path-planning-based-on-electronic-chart/) in Chinese/English in my personal website if you interested in it.

先安装Shapely-1.6.4.post2-cp36-cp36m-win_amd64.whl
在安装pyproj-1.9.6-cp36-cp36m-win_amd64.whl
在安装basemap-1.2.0-cp36-cp36m-win_amd64.whl

先运行GlobalEnviStructWithSquare.py
在运行GlobalPathPlanWithSquare.py