# WIS

机器视觉纸病检测


###工业相机与OPENCV   


- [x] 1.安装相机自带的驱动和SDK开发包；       
- [x] 2.配置好SDK的动态链接库（或者静态）；   
- [ ] 3.调用SDK开发包中的函数建立相机和PC机件的链接；   
- [ ] 4.建立视频流数据，设立一个回调函数（具体参见各SDK）；   
- [ ] 5.将数据拷贝到Mat中的data中。   


###待解决的问题


1. 找出重点部分函数 尝试重新编写程序   
2. 相机参考/Dalsa_CamExpert 工具的使用介绍.pdf 调整相机参数   
3. 视频显示中两边明暗相间的黑影    
4. 调整速度与画面显示的匹配 速度一变画面就扭曲了   

2017年4月10日 17:02:41         
对比demo文件的代码 逐个分析其作用

2017年4月25日 16:23:34         
对于明暗相间的条纹使用滤波，没有想象中的速度慢。            

接下来尝试directshow的方式提取视频。
