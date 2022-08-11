# Python-matchTemplate
简单实现了一下模板匹配算法并用于图像与视频
1.使用的第三方库：opencv(version 3.4.14), numpy(version 1.21.5)
2.文件：
Main.py文件是对图片进行模板匹配算法
VideoMatch.py文件是对视频进行模板匹配进而达到实时追踪的效果
TestImage文件里是测试模板匹配使用的图像与视频
3.实现原理：
基于图像s(source)与图像t(template)，对两图中的图像的每一个像素的灰度值通过计算向量余弦夹角的方式计算出R值(R值范围0-1)，再对比R值最大的区域，返回并框选出该区域并显示


This project implements the template matching algorithm manually
1.: The libraries used are: opencv(version 3.4.14), numpy(version 1.21.5)
2.: 
The code in the "main. py" file implements the Template Matching of the images
The code in the "VideoMatch. py" file implements the real-time template matching of the video
The "TestImage" file contains the images and videos used to match the test template
