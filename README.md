# 3d  
- **-webkit-transform-style: preserve-3d**  
属性指定嵌套元素是怎样在三维空间中呈现。preserve-3d 表示所有子元素在3D空间中呈现。该属性必须与 transform 属性一同使用。
- **perspective: 300**   
透视距离，当为元素定义 perspective 属性时，其子元素会获得透视效果，而不是元素本身。与 -webkit-perspective-origin 属性一同使用该属性   
指定了观察者与 z=0平面的距离，使具有三维位置变换的元素产生透视效果。（默认值：none，值只能是绝对长度，即负数是非法值）
- **-webkit-perspective-origin: 25% 75%**   
该属性必须与 perspective 属性一同使用，而且只影响 3D 转换元素。  
- **transform-origin: 80px 80px 0**  
旋转元素的基点位置
