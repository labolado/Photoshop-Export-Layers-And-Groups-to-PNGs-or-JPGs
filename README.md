This script allows you to export specified layers and groups as individual PNGs or JPGs.

####Export Steps
1. Open the psd document you want to export;
2. Add "#" at the beginning of the layer/group's name you want to export;
3. The image will export as png by default. if you want export it as jpg, add ".jpg" at the end of the layer/group's name;
4. If There exists name start with "##", all the name start with "#" will be ignored, only "##" will be exported; 
5. If There exists name start with "/", it will be recognized as a folder; 
6. If you want extend the image size with transparent edge, Add $+num add the end of name, such as #abc$20. The extend data can inherited from the parent group or group folder.
7. Excute the export script.

***

这个脚本允许你导出指定图层或者分组为png或者jpg图片。
###导出步骤
1. 打开你想要的导出的psd文档；
2. 在你想要的导出的图层或分组名称前添加"#"号；
3. 图片默认导出格式是png，如果你想要导出jpg，只要在图层或分组名称后面加上.jpg即可；
4. 如果存在以"##“开头的图层或分组的名称，所有以"#"开始的将被忽略，只有"##"号开头的会被导出；
5. 如果存在以"/“开头的分组的名称，名称将被识别成目录名；
6. 如果你想为导出的图片增加透明边，在要导出的层名字后面加上 $数字 即可，比如 #abc$20 表示扩充20个像素的透明边，这个数字可以继承自父组。
7. 执行导出脚本。


![Screenshot](https://cdn.pbrd.co/images/Sf68rq1.png) 


