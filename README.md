# Spring boot 整合 Activiti Modeler

## 版本

Spring boot : 1.5.3.RELEASE

Activiti Modeler : 5.22.0

## 如何使用
1、 clone项目到本地后，直接运行SpringBootWithActivitiModelerApplication

2、 application.properties默认端口为8081，启动完成后打开：
```
http://localhost:8081/swagger-ui.html
```
此页面由Swagger生成。

3、 在swagger页面先后调用“新建一个空模型”和“获取所有模型”，得到刚刚新建的模型的ID

4、打开Activiti modeler编辑器：

```
http://localhost:8081/static/modeler.html?modelId=1
```

5、如果需要替换编辑器的语言，重命名交换resources目录下的stencilset.json与stencilset.json.zh-cn文件即可。