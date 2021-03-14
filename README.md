# LineageOS
红米4x  santoni

使用aicp的device，vendor,kernel
BUG：aicp的附加设置在Lineageos上无法使用，请忽略。
下载链接： https://h5.cloud.189.cn/share.html#/t/YJRbaiiI7vI3


如果编译过程中出现JVM heap space啥的，参考https://stackoverflow.com/questions/60468693/java-outofmemoryerror-when-building-aosp-10
请执行
export _JAVA_OPTIONS="-Xmx4g"

或者在.bashrc文件中加入以下内容：
export _JAVA_OPTIONS = -Xmx4096m
