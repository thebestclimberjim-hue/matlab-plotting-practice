MATLAB 绘图练习

这是我第一次使用 GitHub 完成 MATLAB 项目下载、运行、修改和上传的练习。

原项目来源

基于 pmichaillat 的 matlab-figures 项目学习和修改：
https://github.com/pmichaillat/matlab-figures

保留原项目的 MIT 许可证，详见 LICENSE.md。

我完成的修改

给第一张图添加标题。

添加横轴名称 Year。

增加 PNG 图片导出功能，分辨率为 300 DPI。

文件说明

figures.m：绘图脚本，包含我的修改。

my_first_plot.png：修改后的第一张图。

LICENSE.md：原项目许可证。

运行方法

下载并解压仓库，将文件夹设为 MATLAB 当前文件夹，然后在命令窗口执行：

publish('figures.m')

该命令会运行整个脚本，生成多张图、PDF 文件和 HTML 报告。我的修改会额外生成 my_first_plot.png。

结果预览
