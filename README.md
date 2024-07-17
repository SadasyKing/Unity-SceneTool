我时常在想，我们程序员可以用编辑器扩展随时写一个方便场景搭建的函数，那美术们怎么办？

于是乎，我尝试做一个工具来方便美术们使用。因为接触过3dMax，所以最开始的想法是将它的阵列功能复制过来。

到后来在美术们的一声声赞美中失去了自我，开始给这个工具增加更多的功能。不过也都是锦上添花罢了，最核心的还是阵列，尤其是后来可以复制预制体、可以多物体复制之后。

这个dll是我个人封装的，防止美术不小心修改导致bug。源码也很简单，需要的自己反编译一下就好。

————7.17更新，增加轨迹（linerender）部分，可以根据子物体点位设置linerender上的点，或者使用现有LineRenderer规律生成物体。详情可参考下图

![image](https://github.com/SadasyKing/Unity-SceneTool/blob/main/SceneTools.png)

![image](https://github.com/SadasyKing/Unity-SceneTool/blob/main/excample.png)
