# avoid_obstacle
这个是使用matlab联合PreScan做的一个简单的避障场景，场景里面包含了静态的人和车，仿真效果是可以完美地避开障碍物。 避障逻辑：使用TIS雷达测出前方距离和与障碍物的夹角，当障碍物在左边得时候，车就向右转绕过障碍物，障碍物在右边的时候，车就向左转绕过障碍物，然后继续沿着原来的轨迹行驶。
