## * 转成JSON

自定义返回数据类型，例如：

变量一：

    name:
	frequency

    type:complex/real

    dimention:181,361

    unit: log normal,

最后返回object

 {

    变量一: [...],

    变量二: [….]

}


## 矩阵

可以定义变量的维度，例如181*361，

返回一个二维矩阵(可能需要使用一些matrix library)

## 记录模板

能将配置保存成文件，并命名，可能需要使用indexDB之类的web数据库


1. 天线测试数据
2. 方向图测试数据。。。
