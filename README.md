# 放入idf项目根目录下即可用的components组件
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