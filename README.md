## **如何制作实现圆角图片和圆角矩形图片?** ##
####使用自定义控件继承ImageView,在XML文件里引入这个自定义控件就可以啦
> 注意：
     
- 如果想要实现圆角图片在XML文件添加这句代码：**app:shape_mode="circle"** 

- 如果想要实现圆角矩形图片在XML文件添加这两句代码：
  **app:round_radius="20dp", app:shape_mode="round_rect"**

----------
图片一定是正方形图片,否则没有效果
