# DccTool
本人写的若干DCC相关工具，以后如果有写都会放在这里。

## 批量重定向工具
Maya/BatchRetargetingTool.py

本工具是建立在HumanIK基础上的，将其中一个已经设置好HumanIK角色的动画，批量重定向到另一个角色上。

### 用法
将文件中的代码复制到Maya的Python栏中执行。在指定完源蒙皮文件、目标蒙皮文件、动画目录与输出目录后，点击执行即可。（停止按钮是无效的）

要求：
1. 两个蒙皮文件都必须设置好HumanIK，并调整成TPose。而且必须为Ma或者Mb文件。
2. 动画文件必须为fbx。
3. 以上所有文件以及目录中都不许出现中文。

增加HIK的Ue4模板，只需要指定Root骨骼后，再点击Load Skeleton definition-Browse，加载HIK_Ue4.xml即可。