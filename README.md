# Fruitcaky
## Y大需求文档

### 1、目标:
    基于实景3D模型的web后台管理系统(3D模型由软件导出)
        --对项目地块的信息读取修改
        --对项目地块的设备控制
### 2、基本要求:
    前端:
        (1)以实景三维模型为基础控制界面，对选择区域（如某栋楼房、某条路）的信息展示及修改。
        (2)信息展示需在三维图中的弹窗显示，修改需再议(是否在非3D模型页面中修改)。
    后台:
        (1)基于实景模型的读取。(需兼容各大3D项目文件格式)
        (2)管理后台的实现(我只是个辣鸡前端，先这样写)
### 3、进阶要求（非紧急）：
    (1)当选择某楼栋后，可能需跳转到楼栋的构造模型(户型图)，可选择范围需精细到物体级
    (2)当选中楼栋内物体时还需对接外部设备(可对接情况下),对设备进行实时操作。
### 4、其他要求:
    (1)在实景三维模型选中其他物体(非系统)可获取物体（如一棵树）的信息(树的种类、学名)。
### 5、目前阶段:
    确定需求
### 6、首要目标:
    完成基本要求
### 7、参考:
    bentley
    acute3d
    vrplanner
### 8、示例:
    https://site.altizure.cn/project/5a172b4ba27ade76d60e7233/model?from=singlemessage&isappinstalled=0
### 9、简易样例(未实现后台模板):
    http://45.78.39.124:8000/
