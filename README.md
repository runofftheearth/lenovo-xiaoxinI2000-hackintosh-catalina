# Catalina版
为早期版本，自bigsur版efi修改而来，声卡采用万能声卡驱动，可日用。

在bigsur系统中，声卡驱动无论是原生注入还是万能驱动都不能正常工作，只能使用蓝牙耳机。把系统降级到Catalina后，万能声卡驱动可以正常驱动，因此产生了这版efi。

后来发现打一个热补丁即可，现在使用的系统为Monterey，也修复了开机在出现苹果logo前，屏幕上会显示几行错误代码提示的问题。

此版本并未同步更新，只保留为历史版本。
