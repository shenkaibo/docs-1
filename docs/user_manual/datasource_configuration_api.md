## 1 新建数据连接

!!! Abstract ""
    点击【新建数据源】，跳转至新建数据连接页面，填入新建数据源的名称，在【类型】下拉框选定【API】数据源。
 
![新增api数据源](../img/datasource_configuration/新增api数据源.png){ width="900" }

## 2 添加 API 数据表

!!! Abstract ""
    点击【数据表】，跳转至添加 API 数据表页面，添加成功可再次返回新建数据源页面，一个 API 数据源可添加多张 API 数据表。

![数据表](../img/datasource_configuration/数据表.png){ width="900" }

## 3 输入基础信息

!!! Abstract ""
    填写 API 数据表的基础信息，包括名称、完整的请求地址和请求方式，请求方式支持 GET 和 POST；  
    如下示例图以 GET 请求为例，请求类型选择 GET，填入完整的请求地址。

![基础信息](../img/datasource_configuration/基础信息.png){ width="900" }

## 4 填写请求参数

!!! Abstract ""
    填写请求参数，包括请求头、请求体与认证配置，认证配置支持 No Auth 和 Basic Auth；  
    用户无需自行写 JsonPath 系统会自行解析，且可以组合不同层级的字段；  
    如下示例图，认证方式选 No Auth，点击下一步，勾选所需的字段，支持字段重命名，字段类型选择，点击【保存】即可。

![请求参数](../img/datasource_configuration/请求参数.png){ width="900" }

![请求参数2](../img/datasource_configuration/请求参数2.png){ width="900" }

## 5 数据源校验

!!! Abstract ""
    新建数据源页面点击【校验】，校验数据链接性，若信息输入正确，且网络正常，提示校验成功。

![校验api](../img/datasource_configuration/校验api数据源.png){ width="900" }

## 6 数据源保存

!!! Abstract ""
    如下图所示，点击【保存】，配置 API 数据源完成。

![](../img/datasource_configuration/保存api数据源.png){ width="900" }