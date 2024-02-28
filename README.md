map_server是一个ROS node，可以从磁盘读取地图并使用ROS service提供地图。 目前实现的map_server可将地图中的颜色值转化成三种占用值： free (0), occupied (100), and unknown (-1). 未来可用0~100之间的不同值指示占用度。

