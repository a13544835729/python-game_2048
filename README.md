# 游戏2048
## 1. 架构
    bll.py  业务business 逻辑logic 层layer
            负责处理程序的业务逻辑
    usl.py   用户user  显示show  层layer
            负责处理程序的界面逻辑
    model.py 数据模型
             负责描述项目中需要操作的数据
    main.py  主要/入口
             程序主模块/入口模块
## 2. 流程
    main --->  usl  -model-> bll

## 3. 步骤
    -- 将之前完成的核心算法(函数),移动到bll.py的GameCoreControllerl类中(实例方法).
    --
