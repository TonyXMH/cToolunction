# cToolunction
##这里是平时编程时写的一些常用的工具函数。
一般会按照添加的时间进行排序。并在README中进行简要介绍
###bool GetFileAbsolutePath(const fs::path &directoryPath, const std::string &fileName, std::string &filePath);
函数功能：在目录下查找指定文件，并合成文件绝对路径，查找成功返回true，否则false。
PS：为了可以跨系统调用了boost/filesystem.hpp中的内容。
在VS的项目如何添加：
调试->属性->c/c++->常规->附加包含目录 中添加你编译过的boost目录
调试->属性->链接器->常规->附加库目录，添加boost/stage/lib
