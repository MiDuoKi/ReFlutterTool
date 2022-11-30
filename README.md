# ReFlutterTool

基于黑盒调用的Flutter逆向工具，原理上和reflutter工程一致

原理在于 

使用重编译的 libflutter.so 加载目标app的 libapp.so 文件 

导出快照信息文件

### 新增功能 

使用遍历测试方式探测出目标libapp的版本，针对特殊的抹去hash版本的apk。
