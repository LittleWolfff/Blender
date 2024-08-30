三渲二使用ev渲染器，因为它有一个着色器转RGB的节点，可以做出来比较平面化的投影
# 一、模型打光
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
# 二、上色（着色器编辑器）
## 1、新建着色器转RBG
![alt text](image-3.png)
![alt text](image-5.png)
## 2、新建颜色渐变——调阴影
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-11.png)
这样就可以只用调整蘑菇头的颜色渐变，其他部件的颜色渐变也会跟着变
## 3、新建颜色渐变——做固有色
![alt text](image-12.png)
![alt text](image-13.png)
但发现了一个问题，蘑菇不可能全身是红的，所以就要取消关联，单独上材质
![alt text](image-14.png)
![alt text](image-15.png)

## 4、新建混合颜色
![alt text](image-16.png)
![alt text](image-17.png)
## 5、新建色相饱和度
![alt text](image-18.png)
![alt text](image-19.png)
![alt text](image-20.png)
## 6、调色注意
![alt text](image-21.png)
# 三、加线条
## 1、描边
新建场景线条画
![alt text](image-22.png)
![alt text](image-23.png)
![alt text](image-24.png)
比如可以修改线条的颜色
![alt text](image-25.png)
## 2、画线
![alt text](image-26.png)
![alt text](image-27.png)
![alt text](image-28.png)
### 小知识：中括号可以微调笔刷的大小
![alt text](image-29.png)
![alt text](image-30.png)
![alt text](image-31.png)
# 四、部分设置及最后渲染
![alt text](image-32.png)
可以调低分辨率渲染测试一下，如果发现后面的一些线条跑到了前面（如下图所示）
![alt text](image-33.png)
那么就要打开视图层，勾选Z通道（如下图所示）
![alt text](image-34.png)
这是传递一个距离信息，之后再渲染就不会出现这种问题了
![alt text](image-35.png)