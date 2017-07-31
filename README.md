# css-create-font-icon
如何自己制作图标字体：
第一步 制作图标字体文件SVG格式 用ai制作，保存为SVG格式图片；
第二步 使用icomoon工具。
    打开https://icomoon.io/ 然后点击页面右上角的 icomoonApp按钮 然后选择 import icons上传svg格式的文件
    上传完毕后选择上传的图标字体 然后选择generate font生成一个打包的文件 下载后解压
第三步 主要可供使用的文件包括
    1 style.css 2 fonts字体文件夹
第四步 使用方法：
    首先引入css样式
    <link rel="stylesheet" href="style.css">
    然后在html中使用，主要是给span标签添加特定的class属性
    <span class="icon-arrow_lift"></span>
