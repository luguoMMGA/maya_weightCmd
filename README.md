# maya_weightCmd
这是一个maya的小插件。该插件设计了两个命令：divideWeight和weightSmooth。前者用于多个关节根据距离对一个关节的权重进行分割，后者则是对某一区域的权重进行简单平滑。这两个命令皆只能用于蒙皮网格。

该插件包含了可在maya使用的一个自定义ui。该ui可通过在maya脚本编辑器中执行start.py中的脚本代码打开。关于该插件中两个命令的详细信息在ui的help对话框中记录。

.mll文件放在maya的MAYA_PLUG_IN_PATH下，pytransform文件夹和weightCmd_ui.py放在maya的MAYA_SCRIPT_PATH下。在execute前确保load .mll文件。
