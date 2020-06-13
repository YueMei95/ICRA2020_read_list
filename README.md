# ICRA2020_read_list

### Autonomous Driving
Brno Urban Dataset -- The New Data for Self-Driving Agents and Mapping Tasks<br>
_数据采集地点捷克共和国 布尔诺(捷克南摩拉维亚省首府,也是捷克的第二大都市)<br>
包含数据类型：four WUXGA cameras, two 3D LiDARs, inertial measurement unit, infrared camera and especially differential RTK GNSS receiver with centimetre accuracy;_<br> _时间戳精度：all the data are precisely timestamped with sub-millisecond precision;_<br> _采集长度：recordings of more than 350 km of rides in varying environment_<br>_下载:_ https: //github.com/RoboticsBUT/Brno-Urban-Dataset.<br>


Urban Driving with Conditional Imitation Learning<br>
_使用imitation learning的例子包括只在lane-following场景下开展自动驾驶，而不是user-defined route；只使用 single camera view or heavily cropped frames，缺乏观察状态；只有横向(steering)控制，没有纵向(speed)控制，并缺乏与交通灯的交互。更重要的是这些例子都在仿真软件下测试，是一个更简单的域。本文专注于从人类驾驶情境下的semantics, geometry and motion中使用IL学习一些特征表示，并输出横向和纵向控制。方法使用的情境是urban following的简单交通场景。 训练数据：30小时(6个月采集，data banlance) 在欧洲都市街道行驶了35km._<br>
_评级标准：更偏向于控制方面的评价，接管率，转向成功率，在pace car后停车的成功率，follow pace car._<br>











