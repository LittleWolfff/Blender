# 一、建立基础模型
## 1、新建一个圆环
注意圆环的顶点数要改成18（默认是32）
![alt text](image.png)
在制作比较圆的物体时，遵循的原则是：顶点越少，越容易操作
![alt text](image-1.png)
## 2、做盆帽
先向下挤出
![alt text](image-2.png)
再向内挤出
![alt text](image-3.png)
## 3、做盆身
向下挤出并内缩
![alt text](image-4.png)
## 4、做盆底
先向内挤出
![alt text](image-5.png)
再栅格填充
![alt text](image-6.png)
![alt text](image-7.png)
## 5、做盆栽底角
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)
## 6、二级表面细分
![alt text](image-12.png)
## 7、做盆内体积
![alt text](image-13.png)
![alt text](image-14.png)
![alt text](image-15.png)
## 8、添加环切和倒角
![alt text](image-16.png)
![alt text](image-17.png)
![alt text](image-18.png)
![alt text](image-19.png)
倒角环切线可以让一条变两条，再调整宽度，相当于添加了两条环切，也可以快捷地达到环切盆帽盆身时的效果
![alt text](image-20.png)
![alt text](image-21.png)
![alt text](image-22.png)
## 9、复制分离内部面
![alt text](image-23.png)
![alt text](image-24.png)
![alt text](image-25.png)
![alt text](image-26.png)
![alt text](image-27.png)
![alt text](image-28.png)
![alt text](image-29.png)
![alt text](image-30.png)
这个分离出的内部面是用来做土壤的
## 10、做土壤
![alt text](image-31.png)
![alt text](image-32.png)
![alt text](image-33.png)
![alt text](image-34.png)
![alt text](image-35.png)
## 11、润化土壤
![alt text](image-36.png)
![alt text](image-37.png)
记住一点，修改器的应用只能是在物体模式下应用（而且发现同时选择两个物体，不能将这两个物体的表面细分同时应用掉，得一个一个应用）
而且经过测试发现，应用表面细分修改器后，模型会变成视图层级的样子，与渲染层级无关，渲染结果呈现的也是应用后视图看见的样子
所以应用时不用关心渲染层级，只要关心视图层级是什么，那么结果就是什么
![alt text](image-38.png)
![alt text](image-39.png)
## 12、做小草
![alt text](image-40.png)
![alt text](image-41.png)
![alt text](image-42.png)
![alt text](image-43.png)
![alt text](image-44.png)
![alt text](image-45.png)
衰减编辑工具有点像procreat里的液化功能，点了仅相连项才会只影响我们想要影响的那个小草，如果不点的话，则全部小草同时影响
![alt text](image-46.png)
![alt text](image-47.png)
还可以缩小一下上表面，让草尖一点，注意，弯曲移动时只选择上表面的四个点，选多可能会弯得有点奇怪
![alt text](image-48.png)
# 二、材质上色
# 三、蜡笔绘制