# react-native-sunmi-inner-printer
http://docs.sunmi.com/htmls/index.html?lang=zh##V1文档资源  根据商米V1文档开发打印接口

for scanner, refer this: https://github.com/januslo/react-native-sunmi-inner-scanner

安装：

1. 下载package到项目

npm install januslo/react-natvie-sunmi-inner-printer --save

2. 修改settings.gradle

include ':react-native-sunmi-inner-printer'
project(':react-native-sunmi-inner-printer').projectDir = new File(rootProject.projectDir, '../node_modules/react-native-sunmi-inner-printer/android')

3.修改app/build.gradle,在dependenceie里面加入：

compile project(':react-native-sunmi-inner-printer')

4.MainPackage.java 中加入package的引用
5.Js中import

