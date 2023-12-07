# 放入idf项目根目录下即可用的components组件
> __<font size="6">components文件夹内有对应的.h头文件，#include后，可以直接调用.h文件内的函数</font>__

__<font size="4">现在含有UART，TCP_server，Wifi_AP，Wifi_STA程序</font>__
 
+ __<font size="4">原先目录</font>__
```
 - user_project/ - CMakelists.txt
                 - sdkconfig
                 - main/ - app_main.c
                         - Kconfig.projbuild
                 - build/                 
```

+ __<font size="4">移植后的目录</font>__
```
 - user_project/ - CMakelists.txt
                 - sdkconfig
                 - main/ - app_main.c
                         - Kconfig.projbuild
                 - build/                 
                 - components/ - ...
```